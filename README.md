# The Book of Forgotten Styles: a small list of WordPress generated classes that we tend to shamefully ignore

## Post, Pages and Custom Post Types
* `.post-edit-link`

## Archive, Blog and Search
* Pagination links

## Images
* `.wp-caption-text`

## Comments section
* Pagination links
* `.logged-in-as`
* `.must-log-in`: When the user has to login in to comment
* `.reply`: The wrapper `<div>`
  * `.comment-reply-link`: The reply link
  * `.comment-reply-login`: When the user has to login in to comment

* `.comment-notes`
  * `#email-notes` 
* `.form-allowed-tags`: The allowed HTML tags that appear right before the Submit button. Uses [`comment_form()`](https://developer.wordpress.org/reference/functions/comment_form/)


### Comment list
* `.bypostauthor`: A comment by the post author
* `.byuser`: A comment by a logged user
* `.comment-author-admin`: A comment by one of the logged admins

## Gallery
* `.gallery { }` /* The Gallery container (div) */

* `.gallery .gallery-item { }` /* A Gallery item container, for 3, 2 and 4 column galleries */
* `.gallery-columns-2 .gallery-item { }`
* `.gallery-columns-4 .gallery-item { }`

* `.gallery img { }` /* The actual image inside a container for 3, 2 and 4 column galleries */
* `.gallery-columns-2 .attachment-medium { }`
* `.gallery-columns-4 .attachment-thumbnail { }`

* `.gallery .gallery-caption { }` /* A gallery image caption */

* `.gallery dl, .gallery dt { }` /* Definition lists elements */

* `.gallery br+br { }` /* Pick the second line break if two line breaks are adjacent */
