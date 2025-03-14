# Drupal Playground
This is where I play around with Drupal to understand it better.

## Setting Up a Local Drupal Instance
### Prerequisites
- Make sure PHP is installed via the terminal `php -v`
- Make sure phpMyAdmin is installed. `sudo apt-get install phpmyadmin`
- Make sure composer is installed. `sudo apt-get install composer`

### Set-Up Steps
1. Create a Drupal Project.
    > `composer create-project drupal/recommended-project my_site_name_dir`
    > 
    > Replace `my_site_name_dir` with the name of your project.

2. If needed, change directory into `my_site_name_dir`. You might not need to do this.
3. If needed, run `composer install`. You might not need to do this.
4. Run the instance: `php -S localhost:8080 -t web`
    > Replace 8080 with whichever port needed to deploy.

This is not how it should be done in production; this is merely a local project.

## Notes
To be added.