# COVID-19 Contact Tracing Apps

Most governments around the world have started to roll out mobile apps to aid the containment of the COVID-19 pandemic. Some of the apps are purely informational, other instead implement some forms of digital contact tracing, or geographical location tracking. Because of the considerable privacy implications of the use of such apps, Amnesty International's Security Lab has been conducting technical analysis of many of these apps to unearth potential privacy and security issues, and better understand what collection of data are users required to concede.

This repository contains notes and raw data from the technical analyses we conducted. **Please note**: this repository receives rolling updates.

| Country | App Name | Android | iOS | Notes |
|----------|------------|----------|-----|---|
| Algeria | Coronavirus Algérie | https://play.google.com/store/apps/details?id=com.covid19_algeria | | Collects GPS location history. Data is shared only if the user decides to report themselves with symptoms.
| [Bahrain](bahrain/) | BeAware Bahrain | https://play.google.com/store/apps/details?id=bh.bahrain.corona.tracker | https://apps.apple.com/app/id1501478858 | Written with Ionic Framework. Uploads GPS location automatically. Tracks users with Bluetooth bracelets.
| [France](france/) | StopCovid | https://play.google.com/store/apps/details?id=fr.gouv.android.stopcovid | https://apps.apple.com/app/id1511279125 | Centralised contact-tracing using Bluetooth, data are supposed to be anonymised but concerns over metadata |
| [Israel](israel/) | Hamagen | https://play.google.com/store/apps/details?id=com.hamagen | https://apps.apple.com/us/app/%D7%94%D7%9E%D7%92%D7%9F-%D7%90%D7%A4%D7%9C%D7%99%D7%A7%D7%A6%D7%99%D7%94-%D7%9C%D7%9E%D7%9C%D7%97%D7%9E%D7%94-%D7%91%D7%A7%D7%95%D7%A8%D7%95%D7%A0%D7%94/id1503224314 | Records locally GPS locations and Wi-Fi SSIDs. Checks location against a download list of GPS coordinates diagnosed patients visited.
| [Kuwait](kuwait/) | Shlonik - شلونك‎ | https://play.google.com/store/apps/details?id=com.healthcarekw.app | https://apps.apple.com/kw/app/shlonik-%D8%B4%D9%84%D9%88%D9%86%D9%83/id1503978984 | Every 5 minutes automatically uploads GPS location, bluetooth events, and bracelet tracking events.
| Morocco | Wiqaytna | https://play.google.com/store/apps/details?id=covid.trace.morocco&hl=en | https://apps.apple.com/us/app/%D9%88%D9%82%D8%A7%D9%8A%D8%AA%D9%86%D8%A7/id1512666410 | Does Bluetooth scanning with a BlueTrace-compatible protocol. Data is probably uploaded on request.
| [Norway](norway/) | Smittestopp | https://play.google.com/store/apps/details?id=no.simula.smittestopp | https://apps.apple.com/no/app/smittestopp/id1506165384 | Records and uploads both GPS locations and Bluetooth events. Registration tied to phone number.
| [Qatar](qatar/) | EHTERAZ | https://play.google.com/store/apps/details?id=com.moi.covid19 | https://apps.apple.com/us/app/ehteraz/id1507150431 | Egregious privacy issues with QR codes and other APIs. Does Bluetooth contact tracing. Capable of enabling GPS location tracking for all or selected users.
| [Tunisia](tunisia/) | E7mi | https://play.google.com/store/apps/details?id=tn.onmne.e7mi | https://apps.apple.com/us/app/e7mi-%D8%A5%D8%AD%D9%85%D9%8A/id1513856060#?platform=iphone | Does Bluetooth scanning with rotating identifiers. Any contact is automatically reported to a central server.
| UAE | TraceCovid | https://play.google.com/store/apps/details?id=ae.tracecovid.app | https://apps.apple.com/sg/app/tracecovid/id1505485835 | Records contacts over Bluetooth. The data does not seem to be automatically uploaded. The data seems to be only uploaded upon request from the health authorities.
| Saudi arabia | tabaud- تباعد | in development | https://apps.apple.com/sa/app/tabaud-covid-19-ksa/id1514704802 | uses google/apple exposure api, and it supposedly only uses bluetooth contact tracing.
