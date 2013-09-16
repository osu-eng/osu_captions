osu_captions
============

Image captioning for media.

This Drupal module adds the appropriate markup and styling for image captioning with the media module.
It uses the image file entity's "title" field for captions. For this to work, make sure the title field is
set to visible in the image's field display settings (admin/structure/file-types/manage/image/display), for the 
particular view modes you will be using (i.e. default, teaser, etc.).
