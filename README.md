<!--

---
lang: american
---
-->

[![Build Status](https://travis-ci.org/cw-ansible/<ANSIBLE-ROLE>.svg?branch=master)](https://travis-ci.org/cw-ansible/<ANSIBLE-ROLE>)
[![Tweet this](http://img.shields.io/badge/%20-Tweet-00aced.svg)](https://twitter.com/intent/tweet?tw_p=tweetbutton&via=renard_0&url=https%3A%2F%2Fgithub.com%2Fcw-ansible%2F<ANSIBLE-ROLE>&text=<TEXT>)
[![Follow me on twitter](http://img.shields.io/badge/Twitter-Follow-00aced.svg)](https://twitter.com/intent/follow?region=follow_link&screen_name=renard_0&tw_p=followbutton)


# Create BackupPC user

Create and configure [BackupPC](http://backuppc.sourceforge.net/) access.

## Usage

Include the `cw.backuppc` module to your playbook.

## Description

This role creates a `backuppc` user and configure `sudo` in order to perform
`root`-less backups.

## Configuration

See specific documentation in `defaults/main.yml`


## Copyright

Author: Sébastien Gross `<seb•ɑƬ•chezwam•ɖɵʈ•org>` [@renard_0](https://twitter.com/renard_0)

License: WTFPL, grab your copy here: http://www.wtfpl.net
