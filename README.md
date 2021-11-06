#  Moonraker - API Web Server for Klipper

Moonraker is a Python 3 based web server that exposes APIs with which
client applications may use to interact with
[Klipper](https://github.com/KevinOConnor/klipper). Communcation between
the Klippy host and Moonraker is done over a Unix Domain Socket.  Tornado
is used to provide Moonraker's server functionality.

Documentation for users and developers can be found on
[Read the Docs](https://moonraker.readthedocs.io/en/latest/).

### Clients

Note that Moonraker does not come bundled with a client, you will need to
install one.  The following clients are currently available:

- [Mainsail](https://github.com/meteyou/mainsail) by Meteyou
- [Fluidd](https://github.com/fluidd-core/fluidd) by Cadriel
- [KlipperScreen](https://github.com/jordanruthe/KlipperScreen) by jordanruthe
- [mooncord](https://github.com/eliteSchwein/mooncord) by eliteSchwein

### Raspberry Pi Images

Moonraker is available pre-installed with the following Raspberry Pi images:

- [MainsailOS](https://github.com/raymondh2/MainsailOS) by Ray
  - Includes Klipper, Moonraker, and Mainsail
- [FluiddPi](https://github.com/fluidd-core/FluiddPi) by Cadriel
  - Includes Klipper, Moonraker, and Fluidd

### Docker Containers

The following projects deploy Moonraker via Docker:

- [prind](https://github.com/mkuf/prind) by mkuf
  - A suite of containers which allow you to run Klipper in
    Docker.  Includes support for Octoprint and Moonraker.
- [mainsail-docker](https://github.com/mainsail-crew/mainsail-docker) by un!t
  - A complete stack including mainsail as the frontend, klipper and moonraker as a service, it features service restart, full updateable (only system updates require pulling a new docker image).
  - Numpy and packages for adxl345 resonance functionality are also included and precompiled.
  - Multi printer per host ist possible and easy to setup

### Changes

This section contains changelogs that users and developers may reference
to see if any action is necessary on their part.  The date of the most
recent change is included.

Users:\
[user_changes.md](https://moonraker.readthedocs.io/en/latest/user_changes/) - April 19th 2021

Developers:\
[api_changes.md](https://moonraker.readthedocs.io/en/latest/api_changes/) - March 15th 2021
