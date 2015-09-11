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
		"kenmoini/akismet": "dev-master",
	},

Or check out the git repository:

	git clone git@github.com:kenmoini/akismet.git

## Changelog

### Version 0.6.1

* Replaced references to original repo in install instructions
* Removed Laravel support (this is intended to be a bare bones fork of the Akismet lib)
* Removed speculative guzzle dependency

### Version 0.6

* Cleaned up README.md.  I know, a big change.	Tests coming next update.

### Version 0.5

* Internal testing version found operational. Deployed to GitHub
