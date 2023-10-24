# description
This plugin is the bee's knees for bossbars – top-notch animations and complete customization options, you won't find anything simpler or better!

# features
- very easy to setup bossbars
- highly optimized
- easy, but full customization

# cores
- Spigot
- Paper (and Forks)

# versions
- 1.13
- 1.14
- 1.15
- 1.16
- 1.17
- 1.18
- 1.19
- 1.20

# config
```
settings:
  # THIS SETTING ONLY TAKES EFFECT UPON SERVER REBOOT :0

  # Should players receive a bossbar when they join?
  #   - If set to true, players will immediately receive a bossbar upon joining.
  #   - If set to false, players will only receive a bossbar when it's updated to the next one.
  # Using the 'false' value provides a slight optimization, though it's relatively minor. If you require maximum performance, set it to 'false.'
  join-event: true

  # Please leave it enabled :)
  bstats: true

bossbars:
  # Available styles: SOLID, SEGMENTED_6, SEGMENTED_10, SEGMENTED_12, and SEGMENTED_20
  # Available colors: BLUE, GREEN, PINK, PURPLE, RED, WHITE, and YELLOW

  # Example configuration:
  #  test:
  #    title: "test"  # Defaults to an empty string if not provided
  #    color: WHITE  # Defaults to WHITE if not provided
  #    style: SOLID  # Defaults to SOLID if not provided
  #    delay: 10.0   # Defaults to 10.0 if not provided

  #    If set to true, the bossbar won't decrease over time
  #    still: true or false  # Defaults to false if not provided

  #    If set to true, the control panel will shrink smoothly rather than jerkily.
  #    smooth: true or false  # Defaults to false if not provided

  #    If set to true, the bossbar will increase rather than decrease.
  #    invert: true or false  # Defaults to false if not provided

  bar1:
    title:
    - "&bThe First Bossbar!"
    color: BLUE
    style: SOLID
    delay: 10.0

  bar2:
    title: "&aThe Second Bossbar!"
    color: GREEN
    style: SEGMENTED_6
    delay: 10.0
    still: true

  bar3:
    title: "&dThe Third Bossbar!"
    color: PINK
    style: SEGMENTED_10
    delay: 10.0
    smooth: true

  bar4:
    title: "&5The Fourth Bossbar!"
    color: PURPLE
    style: SEGMENTED_12
    delay: 10.0
    invert: true
```

**I'm aware that my English might not be up to scratch. :P**
