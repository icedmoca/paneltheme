
## How do I use this for my Pterodactyl Panel?
The theme has a small code snippet (build.sh) that you must install and follow down below:

## Steps to Install:
1. Download the script: `bash <(curl -s https://raw.githubusercontent.com/icedmoca/paneltheme/master/build.sh`
2. Modify the .env file `nano /var/www/pterodactyl/.env` change pterodactyltheme `pterodactyl` to `argon` then save.
3. Change directory: `cd /var/www/pterodactyl` 
4. Run these commands after you saved the file: `php artisan theme:refresh-cache` `php artisan view:clear`
5. Refresh the browser `CTRL+F5` Success.
## FAQ:
What if this script doesn't work? 
A: The implementation command will take a backup of your current panel in case anything goes wrong during the theme change! So you don't need to worry about losing anything!

What design system does this panel use?
A: https://www.creative-tim.com/product/argon-design-system

## Suggestions
If theres something you want added, just head over to the issues tab and type away.

## Themes Ready for you to use:
`argon`

https://pterodactyl.io/panel/configuration.html
