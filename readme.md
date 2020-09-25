# GitPress Example

The objective here is to create example project for the ![Gitpress platform](https://github.com/pschoffer/gitpress).
Its very easy to install and you can try it easily home.

## Instalation
 - Unzip the package in an empty directory and upload everything;
 - Open `wp-admin/install.php` in your browser. It will take you through the process to set up a `wp-config.php` file with your database connection details;
    - If for some reason this doesn't work, don't worry. It doesn't work on all web browsers. Open up `wp-config-example.php` with a text editor like WordPad or similar and fill in your database connection details;
    - Save the file as `wp-config.php` and upload it;
    - Open ![wp-admin/install.php](wp-admin/install.php) in your browser;
- Once the configuration file is set up, the installer will set up the tables needed for your site. If there is an error, double check your `wp-config.php` file, and try again. If it fails again, please go to the ![WordPress support forums](https://wordpress.org/support/forums/) with as much data as you can gather;  
- **If you did not enter a password, note the password given to you** If you did not provide a username, it will be `admin`;
- The installer should then send you to the ![login page](wp-login.php). Sign in with the username and password you chose during the installation. If a password was generated for you, you can then click on `Profile` to change the password.

## Updating
### Using the Automatic Updater
If you are updating from version 2.7 or higher, you can use the automatic updater:

- Open ![wp-admin/update-core.php](wp-admin/update-core.php) in your browser and follow the instructions;
- You wanted more, perhaps? That's it!

### Updating Manually

- Before you update anything, make sure you have backup copies of any files you may have modified such as `index.php`;
- Delete your old WordPress files, saving ones you've modified;
- Upload the new files;
- Point your browser to ![wp-admin/upgrade.php](/wp-admin/upgrade.php).

## Migrating from other systems
WordPress can ![import from a number of systems](https://wordpress.org/support/article/importing-content/). First you need to get WordPress installed and working as described above, before using ![our import tools](wp-admin/import.php)

## System Requirements

- ![PHP](https://secure.php.net/) version __5.6.20__ or higher.
- ![MySQL](https://www.mysql.com/) version **5.0** or higher.


### Recommendations 

- ![PHP](https://secure.php.net/) version **7.3** or higher;
- ![MySQL](https://www.mysql.com) version **5.6** or higher;
- The ![mod_rewrite](https://httpd.apache.org/docs/2.2/mod/mod_rewrite.html) Apache module;
- ![HTTPS](https://wordpress.org/news/2016/12/moving-toward-ssl/) support;
- A link to ![wordpress.org](https://wordpress.org/) on your site.

## Online Resources
If you have any questions that aren't addressed in this document, please take advantage of WordPress-numerous online resources:

- ![The WordPress Codex](https://codex.wordpress.org/)
	- The Codex is the encyclopedia of all things WordPress. It is the most comprehensive source of information for WordPress available.
- ![The WordPress Blog](https://wordpress.org/news/)
	- This is where you'll find the latest updates and news related to WordPress. Recent WordPress news appears in your administrative dashboard by default.
- ![WordPress Planet](https://planet.wordpress.org/)
	- The WordPress Planet is a news aggregator that brings together posts from WordPress blogs around the web.
- ![Support Forums](https://wordpress.org/support/forums/)
	- If you've looked everywhere and still can't find an answer, the support forums are very active and have a large community ready to help. To help them help you be sure to use a descriptive thread title and describe your question in as much detail as possible.
- ![<abbr>IRC</abbr> (Internet Relay Chat) Channel](https://codex.wordpress.org/IRCWordPress)
	- There is an online chat channel that is used for discussion among people who use WordPress and occasionally support topics. The above wiki page should point you in the right direction. (irc://irc.freenode.net/wordpress>irc.freenode.net #wordpress)


## Final Notes

- If you have any suggestions, ideas, or comments, or if you (gasp!) found a bug, join us in the ![Support Forums](https://wordpress.org/support/forums/);
- WordPress has a robust plugin <abbr>API</abbr> (Application Programming Interface) that makes extending the code easy. If you are a developer interested in utilizing this, see the ![Plugin Developer Handbook](https://developer.wordpress.org/plugins/). You shouldn't modify any of the core code.


## Share the Love
WordPress has no multi-million dollar marketing campaign or celebrity sponsors, but we do have something even better-you. If you enjoy WordPress please consider telling a friend, setting it up for someone less knowledgable than yourself, or writing the author of a media article that overlooks us.

WordPress is the official continuation of ![cafélog](http://cafelog.com/), which came from Michel V. The work has been continued by the ![WordPress developers](https://wordpress.org/about/). If you would like to support WordPress, please consider ![donating](https://wordpress.org/donate/).

## License
WordPress is free software, and is released under the terms of the <abbr>GPL</abbr> (GNU General Public License) version 2 or (at your option) any later version. See ![license.txt](license.txt).




