# OpenMetings Video Conference for Moodle

This Moodle plugin uses Apache OpenMeetings.
You need your own Apache OpenMeetings instance running.

[![Build Status](https://travis-ci.org/openmeetings/openmeetings-moodle-plugin.svg?branch=master)](https://travis-ci.org/openmeetings/openmeetings-moodle-plugin)

## Requirements
PHP 7.0 or later, OpenMeetings 5.0.0 or later and Moodle 3.5 or later.

## tested Versions
OpenMeetings: 5.0.1

Moodle: 3.6, 3.7, 3.8, 3.9

## Building/Developing

* Checkout necessary branch `git checkout <branch_name>`
* Perform necessary edits
* set correct version in line `<property name="project.version" value="4.1.2" />` in build.xml
* run `ant` command

As a result `version.php` packed will have correct `$plugin->release` and `$plugin->version` set

## Check out:

https://openmeetings.apache.org

## Mailinglists

* https://mail-archives.apache.org/mod_mbox/openmeetings-user/
* https://mail-archives.apache.org/mod_mbox/openmeetings-dev/

## Tutorials for installing OpenMeetings and Tools

* https://cwiki.apache.org/confluence/display/OPENMEETINGS/Tutorials+for+installing+OpenMeetings+and+Tools

## Development: Apache Build Server & JIRA Issue Navigator

* https://ci-builds.apache.org/job/OpenMeetings/job/openmeetings/
* https://issues.apache.org/jira/browse/OPENMEETINGS/?selectedTab=com.atlassian.jira.jira-projects-plugin:summary-panel

## Commercial Support links

* https://openmeetings.apache.org/commercial-support.html
* mailto:om.unipro@gmail.com

