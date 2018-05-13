## Sensu-Plugins-skel

[![Build Status](https://travis-ci.org/sensu-plugins/sensu-plugins-skel.svg?branch=master)](https://travis-ci.org/sensu-plugins/sensu-plugins-skel)
[![Gem Version](https://badge.fury.io/rb/sensu-plugins-skel.svg)](http://badge.fury.io/rb/sensu-plugins-skel)
[![Dependency Status](https://gemnasium.com/sensu-plugins/sensu-plugins-skel.svg)](https://gemnasium.com/sensu-plugins/sensu-plugins-skel)
[![Community Slack](https://slack.sensu.io/badge.svg)](https://slack.sensu.io/badge)

## Files

* bin/check-upgrade.sh

## Usage

* sh **check_routeros-upgrade.sh** *snmp* *HOST* [*PORT*] [*COMMUNITY*] [*RELEASE-TREE*]
* sh **check_routeros-upgrade.sh** *ssh* *HOST* [*PORT*] [*USER*] [*RELEASE-TREE*]

The default values for SNMP are:
* PORT=161
* COMMUNITY=public

For a check over SSH:
* PORT=22
* USER=user

You need an user and SSH keys. There is no option for a password.

**[RELEASE TREE]**

Different settings are available. The default is `stable`. Choose wise.

* stable
* bugfix
* release-candidate


## Installation

[Installation and Setup](http://sensu-plugins.io/docs/installation_instructions.html)
