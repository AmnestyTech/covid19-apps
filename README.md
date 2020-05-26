# COVID-19 Contact Tracing Apps

Most governments around the world have started to roll out mobile apps to aid the containment of the COVID-19 pandemic. Some of the apps are purely informational, other instead implement some forms of digital contact tracing, or geographical location tracking. Because of the considerable privacy implications of the use of such apps, Amnesty International's Security Lab has been conducting technical analysis of many of these apps to unearth potential privacy and security issues, and better understand what collection of data are users required to concede.

This repository contains notes and raw data from the technical analyses we conducted. **Please note**: this repository receives rolling updates.

| Country | App Name | Android | iOS | Notes |
|----------|------------|----------|-----|---|
| [Qatar](qatar/) | EHTERAZ | https://play.google.com/store/apps/details?id=com.moi.covid19 | https://apps.apple.com/us/app/ehteraz/id1507150431 | Egregious privacy issues with QR codes and other APIs. Does Bluetooth contact tracing. Capable of enabling GPS location tracking for all or selected users.
