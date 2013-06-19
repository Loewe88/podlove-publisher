# Podlove Podcast Publisher

Work before progress. Feel free to touch but handle with care.

[![Flattr This][2]][1]

  [1]: http://flattr.com/thing/728463/Podlove-Podcasting-Plugin-for-WordPress
  [2]: http://api.flattr.com/button/flattr-badge-large.png (Flattr This)

## Running the test suite

There is a test suite validating some Publisher functionality. It is based on PHPUnit and Selenium. You can get most dependencies via Composer.

You need a Selenium Server. If you are on a Mac, get it via Homebrew (`brew install selenium-server-standalone`). Otherwise, go there: http://docs.seleniumhq.org/download/

You need a local WordPress instance for tests. **The tests will override the database! DO NOT use the same database as for development or production!**.

Open `phpunit.xml` and configure the php constants.

Run the suite: `./vendor/bin/phpunit`.