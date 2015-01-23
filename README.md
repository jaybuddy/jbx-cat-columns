# JBX Category Columns

A simple plugin that allows users to insert columns of categories. In addition, you can set the number of posts to display. 

The plugin is available in the wordpress repository here. 
[https://wordpress.org/plugins/jbx-category-columns](https://wordpress.org/plugins/jbx-category-columns)


## Description
JBX Category Columns displays any number latest posts from selected categories in a column format. You can choose to display 2-6 columns. You also have the ability to display a featured image with either the first post, all posts, or no posts. 


## Installation
1. Upload all the `jbx-catcolumns` folder and all its contents to the `/wp-content/plugins/` directory
2. Activate the plugin through the 'Plugins' menu in WordPress
3. Place `<?php display_jbxCatColumns(); ?>` in your template, outside the loop, where ever you would like the contents to be displayed.


## Usage
Add the following tag to any template file. Keep the tag outside the loop. 

`<?php display_jbxCatColumns(); ?>`

The default number of posts per category the plugin will show is 4. You can specify the number of posts to show in each category by passing a number to to the function. See below:

`<?php display_jbxCatColumns(3); ?>` // Displays 3 posts
`<?php display_jbxCatColumns(7); ?>` // Displays 7 posts

Styles can be edited in the stylesheet included in the jbx-catcolumns plugin folder. The file is entitled `jbxCatColumns-style.css`.

## Changelog

= 1.0 =
* Initial plugin release.
