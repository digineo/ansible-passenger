digineo.passenger
=========

Installs Apache2-worker, Ruby 2.1 from [Brightbox PPA](https://launchpad.net/~brightbox/+archive/ubuntu/ruby-ng) and [Phusion Passenger](https://www.phusionpassenger.com/) on Ubuntu 14.04

Role Variables
--------------

The following variables are defaults an can be overridden:

    ruby_version: "2.1"
    passenger_version: "4.0.53"
    passenger_friendly_error_pages: false

Example Playbook
----------------

    - hosts: servers
      roles:
      - { role: digineo.passenger, passenger_version: "4.0.53" }

License
-------

This code is licensed under [MIT license](http://opensource.org/licenses/MIT)
