digineo.passenger
=========

Installs Apache2-worker, Ruby 2.1 and [Phusion Passenger](https://www.phusionpassenger.com/) on Ubuntu and Debian Jessie.
On Ubuntu Ruby is installed from the [Brightbox PPA](https://launchpad.net/~brightbox/+archive/ubuntu/ruby-ng).

Role Variables
--------------

The following variables are defaults an can be overridden:

    ruby_version: "2.1"
    passenger_version: "4.0.56"
    passenger_friendly_error_pages: false

Example Playbook
----------------

    - hosts: servers
      roles:
      - { role: digineo.passenger, passenger_version: "4.0.56" }

License
-------

This code is licensed under [MIT license](http://opensource.org/licenses/MIT)
