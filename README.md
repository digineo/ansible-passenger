digineo.passenger
=========

Installs Apache2-worker, Ruby 2.1 and [Phusion Passenger](https://www.phusionpassenger.com/) on Ubuntu and Debian.
On Ubuntu Ruby is installed from the [Brightbox PPA](https://launchpad.net/~brightbox/+archive/ubuntu/ruby-ng).

Role Variables
--------------

The following variables are defaults an can be overridden:

    ruby_version: "2.2"
    passenger_version: "5.0.7"
    passenger_friendly_error_pages: false

`passenger_version` is only relevant if Phusion does not offer APT packages for your distribution.

Example Playbook
----------------

    - hosts: servers
      roles:
      - digineo.passenger

License
-------

This code is licensed under [MIT license](http://opensource.org/licenses/MIT)
