FreeFrom Website
===

This is a WordPress theme for the FreeFrom website, which is being developed at [https://freefrom.mystagingwebsite.com/](https://freefrom.mystagingwebsite.com/)  Please contact Morgan Kay ([@wpalchemist](https://github.com/wpalchemist) or @Morgan Kay on RagTag Slack) if you need access to the staging site.

Installation
---------------

### Requirements

`FreeFrom` requires the following dependencies:

- [Node.js](https://nodejs.org/)
- [Composer](https://getcomposer.org/)

### Setup

To start using all the tools that come with `FreeFrom`  you need to install the necessary Node.js and Composer dependencies :

```sh
$ composer install
$ npm install
```

### Available CLI commands

`FreeFrom` comes packed with CLI commands tailored for WordPress theme development :

- `composer lint:wpcs` : checks all PHP files against [PHP Coding Standards](https://developer.wordpress.org/coding-standards/wordpress-coding-standards/php/).
- `composer lint:php` : checks all PHP files for syntax errors.
- `composer make-pot` : generates a .pot file in the `languages/` directory.
- `npm run compile:css` : compiles SASS files to css.
- `npm run compile:rtl` : generates an RTL stylesheet.
- `npm run watch` : watches all SASS files and recompiles them to css when they change.
- `npm run lint:scss` : checks all SASS files against [CSS Coding Standards](https://developer.wordpress.org/coding-standards/wordpress-coding-standards/css/).
- `npm run lint:js` : checks all JavaScript files against [JavaScript Coding Standards](https://developer.wordpress.org/coding-standards/wordpress-coding-standards/javascript/).
- `npm run bundle` : generates a .zip archive for distribution, excluding development and system files.

How to Contribute
---------------
Head over to the [Project Board](https://github.com/RagtagOpen/freefrom-website/projects/1) where we have a list of tasks that need to be done.  If you see something you'd like to work on, assign yourself and get to work!  If you have questions, ping Morgan or hop in the #proj-freefrom-website channel in Ragtag Slack to find answers.

If take a task that requires writing code, please do not work on the `main` branch.  Create your own branch, and when you're done, submit a Pull Request and the rest of the team will take a look.
