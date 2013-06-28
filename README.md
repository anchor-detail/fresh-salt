# Fresh Salt

An Alfred 2 workflow to quickly copy freshly generated WordPress security/secret keys to your clipboard.

## Requirements

* Mac OS X
* [Alfred 2](http://www.alfredapp.com)
* [Alfred Powerpack](http://www.alfredapp.com/powerpack/)

## Installation

Download [Fresh Salt](https://raw.github.com/boogah/fresh-salt/master/Fresh%20Salt.alfredworkflow) and double-click to import it into [Alfred 2](http://www.alfredapp.com).

## Usage

* In Alfred, type `wpsalt` and hit `ENTER`.
* Paste the security keys over the existing ones in `wp-config.php`.

## Release Notes

Listen, it's just a stupid `curl` request piped to `pbcopy`. But it's faster than loading the [WordPress Secret Key Generator](https://api.wordpress.org/secret-key/1.1/salt/) and copying the results manually.

Since I deal with *at least* a couple exploited WordPress sites a week — and regenerating the keys is always a part of my cleanup workflow — I'm sort of scratching my own itch here. And while I'm not sure if anyone else will find this useful, I still figure that it's worth sharing.

## Credits

[Icon](http://sensibleworld.com/news/salt-shaker-icon-131/) courtesy of Jory Raphael at Sensible World.
