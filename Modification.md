## Modifications for power users

## /themes/all-global-positioning.css

- adjust the size of the tabs, line 99, set your desired value `--uc-vertical-tabs-width`
- remove tabs, set `--uc-vertical-tabs-width` to `0.1` not 0
- remove rounded window borders, line 8 `--uc-all-border-radius`
- adjust spacing between windows, line 9 `--uc-all-margins`
- sidebar margins, line 16 `--uc-sb-margins`
- bookmarks toolbar height, line 18 `--uc-bookbar-height`

## /verttab/mini-button-bar

- delete the mini button bar BUT, you can also drag all buttons out and it will be gone
- the following buttons work for the button bar, NO EXTENSIONS:
![mini button bar](https://github.com/soulhotel/FF-CSS-ULTIMA/assets/155501797/c0322340-9c81-47f3-bdda-44bd520cb14a)
- you can adjust when the buttons dissappear, line 93
- with minor adjustments you can adjust the number of buttons allowed, and size them based on view height

## /themes/all-global-positioning.css

- everything related to color, borders, shadows, are located here
- line 6 to 11
  - `--uc-tabs-background`, sidebar header: `--uc-sb-themed`, sidebar body: `--uc-sb-themed-two`, `--uc-sb-background`
- line 14 to 21
  - scroll bar color, and customize toolbar page color
- the rest is pretty simple, theme the window using the properties above
- and when themes are used from add on store, the windows will be themed using `--lwt-accent-color`