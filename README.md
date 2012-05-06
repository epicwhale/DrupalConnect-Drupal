**Drupal distribution maintained by the [DrupalConnect](http://github.com/epicwhale/drupalconnect) project. Configured and ready to use Drupal as a pure data store.**

### Installation Steps

1. [Download](https://github.com/epicwhale/DrupalConnect-Drupal/zipball/master) this distribution & unzip it in a directory.
2. Copy `sites/default/example.settings.php` and rename to `sites/default/settings.php`.
3. Update the MySQL database name, username, password & host near line 208.
4. Create a database with the same name as above and import the `dump.sql` file from the download into your new database.
5. Visit your Drupal website in your browser and login with username: `admin` & password: `admin`.
6. Optionally, clear your Drupal cache and change your admin password.