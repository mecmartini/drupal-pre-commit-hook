# Drupal pre-commit hook
### by [SoulWeb Solutions](https://soulweb.it)

Pre-Commit hook script for Drupal 8.x to check your Drupal coding standard and more with ESLint and PHPCS code sniffer. Auto-fix enabled!

#### Requirements

* Drupal 8.x
* Node.js
* ESLint
* PHP Code Sniffer (phpcs) with Drupal Coder (https://www.drupal.org/project/coder)

#### Usage

Go to your drupal subtheme folder (or create this one).

* 1 - Move to your Drupal project git hook folder `cd /path/to/your/project/.git/hooks`
* 2 - Download the pre-commit hook script `curl -O https://raw.githubusercontent.com/mecmartini/drupal-pre-commit-hook/master/pre-commit`
* 3 - Make sure script is executable `chmod +x pre-commit`
* 4 - Edit the script with your favorite editor and setup the bin tools on the `#Setup` section222222222222
* 5 - Ready to commit!
