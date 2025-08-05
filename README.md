![saplings](https://github.com/kanopi/saplings/assets/5177009/a6377e32-deb2-49d8-873a-f3dd5a36fa7c)



# Saplings - Gin Admin Experience Drupal Recipe
A simple Drupal Recipe for installing and configuring the Gin admin theme and supporting base modules.

## Configuring Drupal for Recipes
If you need to configure your project to use recipes, please see the [Getting Started: Configuring Drupal 11 to Apply Recipes¶](https://project.pages.drupalcode.org/distributions_recipes/getting_started.html) documentation page.

## Requiring this Recipe

### For Drupal 11.2 and above
`composer require kanopi/gin-admin-experience:^2`

### For Drupal 10, 11.0/1

For Drupal 10 and 11.0/1 recipe can only be applied when Stark is the admin theme as set by the minimal profile if you are starting a new site.

## Applying this Recipe

### Using Drush

`drush recipe ../recipes/gin-admin-experience`

### Using Drupal core's script

From your webroot run `php core/scripts/drupal recipe ../recipes/gin-admin-experience`

## Unpacking this Recipe

For the best recipe experience, make sure you project is configured to use Drupal core's Recipe Unpacking system. When a recipe is required, this plugin "unpacks" it by moving the recipe's dependencies directly into your project's root composer.json, and removes the recipe as a project dependency.

New projects started from Drupal 11.2 will most likely have this on by default, but it can be configured on and Drupal 10/11 project.

View the [New Recipe Unpack composer plugin change record](https://www.drupal.org/node/3522189) to learn how.

