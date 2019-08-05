# whitefox-keyboard
key mapping and workaround for white fox keyboard

1. Use Input-Club's configurator for key mapping
  See whitefox-keymap.jpg for end result
  https://input.club/configurator-whitefox/
  For generated zip, see uploaded zip
2. Use Karabiner-Elements for key swapping
  After step #1, there's one key left with a problem
  `(grave accent and tilde) is input as §(Section sign)
  this is probably due to wrong keyboard language detection.
  Use Karabiner-Elements to add one rule in simple modification:
  From Key                 To key
  non_us_backslash         grave_accent_and_tilde(`)
  Link to download Karabiner:
  https://pqrs.org/osx/karabiner/
