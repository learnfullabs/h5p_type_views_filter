# Purpose

When the H5P Library Type is exposed in views and you want to create a views filter for it, the views filter will default to a textfield.

This is less than ideal, even when coupled with autocomplete.

This module converts the textfield to checkboxes. Letting the end-user view/select the h5p types they want to filter by.

## Notes

This is a custom drupal module developed for use in Learnful Studio. You will need to make modifications to it if you want to have it work on your own (non-Learnful Studio) drupal sites.

You should use this module with the patch provided here: [https://www.drupal.org/project/h5p/issues/3114732](https://www.drupal.org/project/h5p/issues/3114732).