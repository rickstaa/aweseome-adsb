<!--lint disable awesome-git-repo-age-->
<!--TODO: Remove when repository is older than 30 days. -->

<!-- GITHUB LOGO PLACEHOLDER -->

<div align="center">

<!-- title -->

<!--lint ignore double-link-->

# <a style="color: inherit" href="https://github.com/rickstaa/awesome-adsb">Awesome ADS-B</a> [![Awesome](https://awesome.re/badge.svg)](https://awesome.re) [![lint](https://github.com/rickstaa/awesome-adsb/actions/workflows/lint.yaml/badge.svg)](https://github.com/rickstaa/awesome-adsb/actions/workflows/lint.yaml) [![GitHub contributors](https://img.shields.io/github/contributors/rickstaa/awesome-adsb?color=geen)](https://github.com/rickstaa/awesome-adsb/graphs/contributors) [![GitHub Repo stars](https://img.shields.io/github/stars/rickstaa/awesome-adsb)](https://github.com/rickstaa/awesome-adsb/stargazers) <!-- omit in toc -->

> **Note**
> Just type `adsb.cool` to go here.

<!-- subtitle -->

A curated list of awesome [ASD-B](https://en.wikipedia.org/wiki/Automatic_Dependent_Surveillance%E2%80%93Broadcast) tools, projects, docker images, resources and other shiny things 📡.

<!-- image -->

<a href="https://www.sportys.com/blog/ads-b-101-what-you-need-know" target="_blank" rel="noopener noreferrer">
  <img width="600" src="https://www.sportys.com//media/wysiwyg/blog/13_-_Navigating_and_Automation_in_the_21st_Century.png" />
</a>

<!-- description -->

**Automatic Dependent Surveillance–Broadcast (ADS-B)** is a surveillance technology and form of Electronic [Conspicuity](https://en.wikipedia.org/wiki/Airborne_collision_avoidance_system#Aircraft_collision_avoidance) in which an [aircraft](https://en.wikipedia.org/wiki/Aircraft) determines its position via [satellite navigation](https://en.wikipedia.org/wiki/Satellite_navigation) or other sensors and periodically broadcasts it, enabling it to be tracked.

</div>

<!-- TOC -->

## Contents

- [Docs and Quickstarts](#docs-and-quickstarts)
- [Books and Articles](#books-and-articles)
- [ADS-B Aggregators](#ads-b-aggregators)
  - [Open source orientated](#open-source-orientated)
  - [Community driven](#community-driven)
  - [Non-profits](#non-profits)
  - [Commercial](#commercial)
  - [Other](#other)
- [Software](#software)
  - [General](#general)
  - [Feeding](#feeding)
  - [Visualisation](#visualisation)
  - [Browser extensions](#browser-extensions)
  - [Apps](#apps)
  - [Social](#social)
- [Hardware](#hardware)
  - [SBC](#sbc)
  - [Receivers](#receivers)
  - [Filters](#filters)
  - [Antennas](#antennas)
- [Follow](#follow)

<!-- CONTENT -->

## Docs and Quickstarts

<!-- List ADS-B documentation and quickstarter guides -->

- [ADS-B docker guide](https://sdr-enthusiasts.gitbook.io/ads-b/) - Everything you want to know about ADS-B reception, decoding and sharing.
- [ADS-B equipment guide](https://sdr-enthusiasts.gitbook.io/ads-b/intro/equipment-needed) - A excellent ADS-B hardware guide written by the community.
- [PiAware ADS-B tutorial](https://flightaware.com/adsb/piaware/build/) - FlightAware's ADS-B setup tutorial.
- [ADSB-B transponders guide](https://www.sportys.com/blog/ads-b-out-questions-1090-978/) - A guide explaining the difference between 978 and 1090 MHz transponders.

## Books and Articles

<!-- List interesting ADS-B books and articles -->

- [The 1090 Megahertz Riddle - Junzi Sun](https://mode-s.org/decode/index.html) - A Guide to Decoding Mode S and ADS-B Signals.

## ADS-B Aggregators

<!--lint ignore double-link-->

> **Note**
> The aggregators below are displayed per category based on the number of feeders [on 27-02-2023](https://vmst.io/@ottergoose/109937649240642289). If the number of feeders was unavailable, sites were compared based on the number of planes they tracked. Feel free to open a [create a pull request](https://github.com/rickstaa/awesome-adsb/pulls) if you think the order needs to be updated.

<!-- List ADS-B aggregators. -->

### Open source orientated

<!-- List open source ADS-B aggregators. -->

- [adsb.fi](https://adsb.fi) - A community-driven flight tracker with hundreds of feeders worldwide that provides open and unfiltered access to worldwide air traffic data.
- [ADSB One](https://adsb.one) - A one-stop resource for all aero-related information and a community-driven aggregator for aero-feed data legally dedicated to the public interest.
- [ADSB.lol](https://adsb.lol) - A completely open-source and community-driven flight tracker that displays and provides [ODbL-licensed](https://opendatacommons.org/licenses/odbl/summary/) flight tracking data via a [free API](https://api.adsb.lol/).

### Community driven

<!-- List community driven ADS-B aggregators. -->

- [ADSBHub.org](https://www.adsbhub.org) - A service for real-time ADS-B data sharing and exchange between plane tracking enthusiasts, plane spotters, radio amateurs and professionals interested in developing ADS-B-related software.
- [TheAirTraffic](https://theairtraffic.com) - A community-driven ADS-B aggregator dedicated to keeping the air-tracking data on their site open and unfiltered.
- [PlaneSpotters.net](https://www.planespotters.net) - A civil aviation database and aggregator with a large collection of aircraft photos and information.
- [Plane.watch](https://plane.watch) - A community hosted flight tracker.
- [www.live-military-mode-s.eu](https://www.live-military-mode-s.eu) - A community driven flight tracker that is focused at tracking military aircraft.

### Non-profits

<!-- List non-profit ADS-B aggregators. -->

- [Opensky Network](https://opensky-network.org) - The OpenSky Network is a non-profit association based in Switzerland that provides open access to flight tracking control data. It was set up as a research project by several universities and government entities to improve the security, reliability and efficiency of the airspace.

### Commercial

<!-- List commercial ADS-B aggregators. -->

<!--TODO: Remove when awesome-lint/issues/160 is fixed. -->
<!--lint ignore no-undefined-references awesome-list-item-->

- [FlightAware](https://flightaware.com)[^1] - An American multinational technology company that provides real-time, historical, and predictive flight tracking data and products.
- [FlightRadar24](https://www.flightradar24.com)[^1] - A Swedish internet-based service that shows real-time aircraft flight tracking information on a map.
- [RadarBox](https://www.radarbox.com)[^1] - A Tampa-based global flight tracking and data services company that offers worldwide commercial and general aviation flight tracking.
- [ADS-B Exchange](https://www.adsbexchange.com/) - A flight tracking company that offers high fidelity, stable, and secure flight tracking service. It was started by volunteers and flight enthusiasts but was recently acquired by [JETNET](https://www.jetnet.com/).
- [PlaneFinder.net](https://planefinder.net)[^1] - A United Kingdom-based real-time flight tracking service shows global flight data like flight numbers, how fast an aircraft moves, elevation, and travel destination.
- [AvDelphi](https://www.avdelphi.com) - An aviation data and services company that shows airframes, registrations, types, airports and flights, radar and nav points, and owner and flight histories.
- [RadarVirtuel](https://www.radarvirtuel.com) - A flight data collector that offers premium features. Its primary focus is collecting information about traffic around smaller airports worldwide.

<!--TODO: Remove when awesome-lint/issues/160 is fixed. -->
<!--lint ignore no-undefined-references-->

[^1]: Adheres to the [FAA](https://www.faa.gov/)'s [Aircraft Tail Number Blocking/Unblocking list](https://www.faa.gov/pilots/ladd/request) list. Therefore, the data found on this platform is filtered and may not include all data found on other aggregators.

### Other

- [Airframes.io](https://app.airframes.io/) - Airframes is an aircraft-related aggregation service that receives ACARS, VDL, HFDL, and SATCOM data from volunteers worldwide. It collaborates closely with ADS-B aggregators and works with ADS-B data internally.

## Software

<!-- list ADS-B software, apps and docker containers. -->

### General

- [readsb](https://github.com/wiedehopf/readsb) - ADS-B decoder swiss knife.
- [sdr-enthusiasts/plane-alert-db](https://github.com/sdr-enthusiasts/plane-alert-db) - A list of exciting aircraft - Governments, Dictators, Military, Historical and just plain odd.
- [junzis/pyModeS](https://github.com/junzis/pyModeS) - A python decoder for Mode S and ADS-B signals.

### Feeding

- [sdr-enthusiasts/docker-multifeeder](https://github.com/sdr-enthusiasts/docker-multifeeder) - Feed multiple ADS-B and MLAT aggregators from a single container.
- [adsbfi/adsb-fi-scripts](https://github.com/adsbfi/adsb-fi-scripts) - Easy to use feeder install script for feeding to adsb.fi.
- [adsblol/feed](https://github.com/adsblol/feed) - Easy to use, container-based MLAT/ADS-B/ACARS/VDL2 multi feed client. Powered by [SDR-Enthusiasts](https://github.com/sdr-enthusiasts) images.

### Visualisation

- [wiedehopf/tar1090](https://github.com/wiedehopf/tar1090) - A great way to view your ADS-B data.
- [Grafana](https://grafana.com/) - Open source analytics and monitoring solution for every database.

### Browser extensions

- [RadarAtlas](https://chrome.google.com/webstore/detail/radaratlas/kgionpkdifedafldjflcbeojkencnaja) - An ADSB & tar1090 add on that makes it fun and accessible to track the most interesting aircraft in the world.

### Apps

- [d4rken/adsb-meta-tracker](https://github.com/d4rken/adsb-meta-tracker) - An android ADS-B Meta Tracker that shows metadata about ADS-B aggregators.

### Social

- [docker-planefence](https://github.com/kx1t/docker-planefence) - A little tool that can be used to log, display and tweet the aircraft that come within range of your receiver (i.e. the fence).
- [Jxck-S/plane-notify](https://github.com/Jxck-S/plane-notify) - Notify if a selected plane has taken off or landed using OpenSky or ADS-B Exchange data.

## Hardware

<!-- List ADS-B hardware resources. -->

### SBC

- [Rasbpberry Pi](https://www.raspberrypi.org/) - Small single-board computers developed in the United Kingdom.
- [Orange Pi](http://www.orangepi.org/html/hardWare/computerAndMicrocontrollers/details/Orange-Pi-5.html) - Single-board computers created using OS cost-effective hardware.
- [Banana Pi](https://banana-pi.org/) - Single-bard computers created by a Chinese open-source hardware community.

### Receivers

- [FlightAware ADS-B USB receivers](https://flightaware.store/collections/radio-dongles) - ADS-B USB receivers made by FlightAware.
- [AirNav RadarBox ADS-B USB receivers](https://www.radarbox.com/store) - ADS-B USB receivers made by RadarBox.
- [RTL-SDR DONGLES](https://www.rtl-sdr.com/buy-rtl-sdr-dvb-t-dongles/) - A premium RTL-SDR dongle provider focused on maintaining fair retail pricing.

### Filters

> **Warning**
> Some ADS-B USB receivers already contain an onboard filter.

- [FlightAware Signal filters](https://flightaware.store/collections/signal-filters) - Different signal filters made by FlightAware.

### Antennas

- [Vinnant antennas](https://vinnant.sk/) - Specialized premium antennas made in Slovakia.
- [DPD antennas](https://dpdproductions.com/) - High-quality antennas for various radio services produced in the USA.

## Follow

<!-- List people worth following on social sites (Twitter, LinkedIn, GitHub, YouTube etc.) -->

<!--lint ignore double-link-->

> **TODO:**
> Please [create a pull request](https://github.com/rickstaa/awesome-adsb/pulls) if you know people in the ADS-B space that are worth following.

Who else should we [be following](https://github.com/rickstaa/awesome-adsb/issues/new?assignees=&labels=&template=suggestion.yaml)?

<!-- END CONTENT -->

**[⬆ back to top](#contents)**

<!-- REPO INFO -->

## Contributing

Contributions of any kind are welcome 💙! Please check out the [contributing guidelines](contributing.md).

[![CC0](https://i.creativecommons.org/p/zero/1.0/88x31.png)](https://creativecommons.org/publicdomain/zero/1.0/)

### Contributors

<!--lint ignore double-link-->

This project exists thanks to all the people [that contributed](https://github.com/rickstaa/awesome-adsb/graphs/contributors)!

<!--lint ignore double-link-->
<a href="https://github.com/rickstaa/awesome-adsb/graphs/contributors">
  <img src="https://contrib.rocks/image?repo=rickstaa/awesome-adsb" />
</a>
</br>
</br>
