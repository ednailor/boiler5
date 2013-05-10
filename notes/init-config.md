# Boiler5 Init Configuration

Out of the box, Boiler5 is setup to work quite effectively for most common setups. However, you have the ability to make some configuration changes rather easily.

## $boiler5init Variable

The `$boiler5init` variable is used to set up a number of features for the site. Make changes as needed.

**auto_headlines
`$boiler5init['auto_headlines'] = 'all'; `**

* Options
 - `all` : displays titles for all content types
 - `pages` : displays titles only on Pages 
 - `posts` : displays titles only on Posts 
 - `none` : does not display titles on any content types - author must add to the content 
 
*Controls if the H1 tag for each page or post is automatically created based on the Page/Post title. If active, the post title will create a H1 tag for the page, proceeded by the content. If not active, the author will need to create their own H1 titles within the content editor. This is very useful if you want the page titles in the Admin side to differ from the page title shown to the actual reader. For example, you may want a page title in the Admin side to simply be **About Us**, but the content say **About the Boiler5 Framework**. This allows for better organization on the Admin side.*
