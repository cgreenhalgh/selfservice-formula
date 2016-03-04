# SelfService SaltStack Formula

A SaltStack formula to help create web services. Initially wordpress
instances. Requires mysql-formula, apach-formula and php-formula.

Currently being tested/developed on Ubuntu so other distros untested.

Currently just support creating basic WordPress installations, either
virtual hosts or site subdirectories.

In state top include:

- `selfservice.vhost.standard` to set up apache config
- `selfservice.sites` to create/update sites

By Chris Greenhalgh, chris.greenhalgh@nottingham.ac.uk

Copyright (c) The University of Nottingham, 2016

