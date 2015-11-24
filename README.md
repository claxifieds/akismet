# Introduction

This is a simple little PHP5 class that enables you use the Akismet anti-spam service in your application.
Most of the ground work was done by Alex Potsides, [http://www.achingbrain.net](http://www.achingbrain.net)

# Download

Since we are not currently registered with packageist, need to provide the repo info:

Composer:

	"repositories": [
		{
			"type": "vcs",
			"url": "https://github.com/servicescout/akismet"
		}
	],

	"require": {
		"servicescout/akismet": "dev-master",
	},

Or check out the git repository:

	git clone git@github.com:kenmoini/akismet.git

## Changelog

Although this is forked from the Ken Moini Laravel package, I've removed all the Laravel support,
so the Changelog is listed relative to the original code from Alex Potsides, with some of the Ken Moini changes.

### Version 0.5.2
* Fixed namespacing bugs with Exceptions

### Version 0.5.1
* Changed HTTP header blacklist to whitelist
* Composer support
