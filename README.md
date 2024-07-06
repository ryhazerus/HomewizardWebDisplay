# P1 Energy Dashboard ⚡

> ⚠️Everything is working but this is still in development ⚠️

A self-hosted webapp for displaying information of a P1 smart meter. Currently the system is in development and only supports the `HomeWizard P1 Smart Meter`.

### Shortcomings

- ⚠️ Has not yet been tested on a linux host but should work

## Description

This is a self-hosted web-ui for running an energy dashboard for your smart meter. View total electricity usage, gas usage and water usage for different P1 smart meters. Currently we support the following meters but sign-up and stay up-to-date for when we release support for more meters.

### Roadmap

- [x] Nothing is currently working but everything is there
- [x] Support Static Meters for Energy, Water and Gas Usage
- [x] Add local db for graphing information
- [ ] Add exporting data feature
- [ ] Add configurable tariffs for gas/energy prices
- [ ] Add Configurable Meters for users
- [ ] Support other smart meters

## Screens

You can view a sample of the current screens below, a link to a demo page will be setup later as a demo.

**Setup**

Once finished, you can configure your Energy Display in your browser by settings its IP and choosing your meter (there is a plan to support more smart meters) and saving your settings.
![alt text](/docs/setup-page.png)

**Dashboard**

After everything is finished, you will be redirected to your dashboard.
![alt text](/docs/dashboard.png)

## Prerequisites

Check out the following steps before running the system.

- NodeJS & NPM
- Docker

## Authors

Contributors names and contact info

- [@Ryhazerus](http://github.com/ryhazerus)

## License

This project is licensed under the MIT License - see the LICENSE.md file for details

## Acknowledgements

This project is inspired by the HomeWizard Energy Display hardware device.

- [HomeWizard Energy Display](https://www.homewizard.com/)
