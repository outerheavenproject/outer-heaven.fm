---
title: "{{ replace .Name "-" " " | title }}"
date: {{ .Date }}
draft: true
podcast:
    # The path to the mp3 file [required]
    mp3: sounds/001/***.m4a
    # Episode duration, e.g 1:04:02 (iTunes). [required]
    duration: **:**
    # image:
    #     src:                # Episode image src, place inside the assets directory (iTunes).
    #     alt:                # Alt text for the image, explain what is on the image.
    #     width:              # Image width in the article, defaults to 250px.
    #     class:              # Image wrapper class.
    # Episode explicit setting, default to false (iTunes).
    explicit: false
    # Episode number (iTunes).
    episode: 1
    # Episode season (iTunes).
    season: 1
    # Block the episode from iTunes, default to no (iTunes).
    # block: yes
---

