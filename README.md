## Sensu-Plugins-RouterOS

[![Build Status](https://travis-ci.org/sensu-plugins/sensu-plugins-routeros.svg?branch=master)](https://travis-ci.org/sensu-plugins/sensu-plugins-routeros)
[![Gem Version](https://badge.fury.io/rb/sensu-plugins-routeros.svg)](http://badge.fury.io/rb/sensu-plugins-routeros)
[![Dependency Status](https://gemnasium.com/sensu-plugins/sensu-plugins-routeros.svg)](https://gemnasium.com/sensu-plugins/sensu-plugins-routeros)
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

**ENV ROUTEROS_UPDATEURL**

If you want to save the update information on your own server you can use `export ROUTEROS_UPDATEURL` to overwrite the default `https://download.mikrotik.com/routeros`.

## Installation

[Installation and Setup](http://sensu-plugins.io/docs/installation_instructions.html)
