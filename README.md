# JBX Category Columns

A simple plugin that allows users to insert columns of categories in posts, pages, custom post types or directly in a template. In addition, you can set the number of posts to display and whether or not to display the featured image associated with the post. 

The plugin is available in the wordpress repository here. 
[https://wordpress.org/plugins/jbx-category-columns](https://wordpress.org/plugins/jbx-category-columns)


## Description
JBX Category Columns displays any number latest posts from selected categories in a column format. You can choose to display 2-6 columns.

## Installation
1. Upload the `jbx-catcolumns` folder and all its contents to the `/wp-content/plugins/` directory
2. Activate the plugin through the 'Plugins' menu in WordPress
3. Place `[jbx]` in your post, page or custom post type, where ever you would like the contents to be displayed.


## Usage
Add the following tag to any post, page or custom post type.

`[jbx]`

The default number of posts per category the plugin will show is 3. You can specify the number of posts to show by specifying in the numberposts attribute. See below for examples:

`[jbx columns='3' names='Category Name 1, Category Name 2, Category Name 3' numberposts='3' images='true']`

You can also add it directly to a template using the folowing code and adjusting the attributes to your likeing. 

`<?php echo do_shortcode("[jbx columns='3' names='Category Name 1, Category Name 2, Category Name 3' numberposts='3' images='true']"); ?>`

In addition, you now can also add multiple instances to by using the shortcode multiple times.

Styles can be edited in the stylesheet included in the jbx-catcolumns plugin folder. The file is entitled `jbxCatColumns-style.css`.

## Changelog

1.1
Changed the plugin to work off a simple shortcode. No more template tags. Minor performance updates. This is a major update such that upgrading will require you to remove the old template tags and use the methods described in the above **Usage** section.

1.0
Initial plugin release.
