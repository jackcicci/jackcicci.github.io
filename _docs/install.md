---
toc:
    install:
        _title: Install
        using-a-pre-bundled-release: Using a pre-bundled released
        composer: Composer
nav: 1
---

## Install

You can install Pico either using a pre-bundled release or with composer. Pico is also available on [Packagist.org][] and may be included in other projects via `composer require picocms/pico`. Pico requires PHP 5.3+

### Using a pre-bundled release

Just [download the latest Pico release][LatestRelease] and upload all files to the `httpdocs` directory (e.g. `/var/www/html`) of your server.

### Composer

#### Step 1 - for users
[Download the *source code* of Pico's latest release][LatestRelease], upload all files to the `httpdocs` directory (e.g. `/var/www/html`) of your server and navigate to the upload directory using a shell.

#### Step 1 - for developers
Open a shell and navigate to the desired install directory of Pico within the `httpdocs` directory (e.g. `/var/www/html`) of your server. You can now clone Pico's Git repository as follows:
<pre><code>$ git clone {{ site.gh_project_url }}.git .</code></pre>
Please note that this gives you the current development version of Pico, what is likely *unstable* and *not ready for production use*!

#### Step 2
Download [composer][] and run it with the `install` option:
<pre><code>$ curl -sS https://getcomposer.org/installer | php
$ php composer.phar install</code></pre>

[Packagist.org]: http://packagist.org/packages/picocms/pico
[LatestRelease]: {{ site.gh_project_url }}/releases/latest
[composer]: https://getcomposer.org/
