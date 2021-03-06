---
layout: plugin

id: smsnotifier
title: SMS Notifier (with Twilio)
description: Receive SMS notifications when OctoPrint jobs are complete.
author: Richard Bateman
license: AGPLv3

# today's date in format YYYY-MM-DD, e.g.
date: 2016-12-10

homepage: https://github.com/taxilian/OctoPrint-Twilio
source: https://github.com/taxilian/OctoPrint-Twilio
archive: https://github.com/taxilian/OctoPrint-Twilio/archive/master.zip

# set this to true if your plugin uses the dependency_links setup parameter to include
# library versions not yet published on PyPi. SHOULD ONLY BE USED IF THERE IS NO OTHER OPTION!
follow_dependency_links: false

tags:
- notification

screenshots:
- url: /assets/img/plugins/smsnotifier/smsnotifier.png
  alt: Settings dialog and SMS notification screenshot
  caption: Configure notification recipient, Twilio API SID and Auth Token, printer name, and from number.

featuredimage: /assets/img/plugins/smsnotifier/smsnotifier.png

compatibility:
  # list of compatible versions, for example 1.2.0. If left empty no specific version requirement will be assumed
  octoprint:
  - 1.2.4

---

Receive email notifications when OctoPrint jobs are complete.
