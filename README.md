# fabwptest
new deploy make a db and put the name of it in the wp-config.php file
then add the wordpress local build you have to a github repo.
add that repo to a directory in cpanel
add a domain or subdomain for that repository/reponame/ in cpanel


htaccess was added for this wp deploy to work from a github repo instead of old ass filemanager.

theme
https://github.com/understrap/understrap
documentation: https://docs.understrap.com/#/
for the theme westcoast to work you need to follow the directions from the understrap theme which is a npm install.

`npm install`
to make style css edits
`npm run watch` or `"watch-run-css": "nodemon --watch src/sass/ --ext scss --exec \"npm-run-all css-bs4\"",`

Todo work out the SCSS updates