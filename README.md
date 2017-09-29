# suitcase_interim_custom-module
A blank module for adding custom stylesheets to individual sites using Suitcase Interim. Its most basic use is to add a CSS stylesheet after all the other theme and modules stylesheets load, allowing on-the-fly styling changes.

## Instructions

1. Rename the folder to your module name, usually just the name of the site.
2. Place in sites/all/modules/custom
3. Replace all modulename with your module name. Don't forget the preprocess function in the .module file.
4. Activate the module in the Drupal admin UI under Modules.
