---
layout: home
header:
  title: Privacy Respecting Proximity Tracing
  text: >
    The app which helps you determine if you got in close contact with a person infected
    by the coronavirus disease 2019 (COVID-19).<br /><br />
    No personally identifiable information collected.<br /><br />
    Your proximity interactions with other users never leaves your phone.
  action: # action button is optional
    label: Download Now
    url: '#download'
    icon: fa-download


sections:
  - type: download.html
    section_id: download
    #background_style: bg-primary
    background_style: bg-dark
    title: CoviTrace Download!
    text: Download the app.<br />
          Enable bluetooth.<br />
          Protect yourself, your family and your friends!
    actions:
      - title: Android
        #url: 'https://play.google.com/store/apps/details?id=org.covitrace.covitrace'
        url: '#'
        icon: fa fa-android
        #class: btn-light
      - title: iPhone
        url: '#'
        icon: fa fa-apple
        #class: btn-light

  - type: privacy.html
    section_id: privacy
    #background_style: bg-info
    title: Privacy Respecting
    services:
      - title: No Personal Info
        text: Your phone only broadcasts a random number via bluetooth.<br />
              This number changes every hour.
        icon: fa-ban
      - title: Data control
        text: Your proximity interfactions with other users never leaves your phone.
        icon: fa-mobile text-info
      - title: No Localisation
        text: No GPS.<br />
              Only bluetooth is used
              to measure the distance between you and other nearby users.
        icon: fa-location-arrow
      - title: Open Source
        text: All source code related to this project is publicly available.
        icon: fa-code text-info
        url: https://github.com/covitrace
---
