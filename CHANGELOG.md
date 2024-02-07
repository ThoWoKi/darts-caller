## 2.7.5

- hotfix: disables: prevent app from start twice


## 2.7.4

- improve web-caller (load all files on start + "change/ban-caller"-function)
- add voice-pack 'en-US-Matthew-Male'
- preview banned voice-packs
- add fallback for unreachable audio device
- prevent app from start twice


## 2.7.3

- hotfix: fix typo


## 2.7.2

- hotfix: fix occasional call-stops after one match
- change file-hoster for more stable downloads
- add option for downloads: only download specific voice-pack by its name
- add ambient_gameshot_{playername}, ambient_matchshot_{playername} and more
- add voice-pack 'en-US-Gregory-Male'


## 2.7.1

- hotfix: receive_local_board_address


## 2.7.0

- extend lobby-calling (lobbychanged -> lobby_ambient_in)
- improve web-caller (using indexeddb for caching to continously prevent delays)
- change file-hoster for more stable downloads (dropbox)
- update voice-packs (new lobby-sounds, 2000+ new playernames)
- add path argument for blacklist-file
- fix token-requests
- fix empty-SHARED_MEDIA_PATH error


## 2.6.3

- add CHANGELOG
- add BACKLOG
- fix possible invalid path configuration for linux/macos
- reintroduce "lobbychanged" sound-file-key
- introduce support for game-variant "ATC" (Around-the-clock); thanks to @takki2602 
- improve -M / -DL description
- CALL_CURRENT_PLAYER_ALWAYS only with more than one player


## 0.0.0

- prevent from double calling
- only one webhook with all information (to prevent race condition on receiving app): leg_end, turn, throw_number, throw_value, points_left, variant, user
- let the user configure caller-volume
- sounds for every throw (single, double, tripple, missed)
- add start argument for surpressing checkout calls
- add sites for free sound-file downloads
- cricket: Change call behaviour to default
- improved possible checkout call for bogey numbers
- yr_2-yr_170.{wav | mp3} different sounds-files for possible checkout calls
- fix sound-play repetition
- improved error logging
- dont care about last slash in webhook
- fix webhook for apps that need info of every throw
- offer multiple WTT`s
- add [playername] to gameshot like in [playername] you require
- add configurable pygame.mixer
- add possibility to have more sound-files for one event (random if multiple found)
- add ambient-sounds for gameon, gamewon, noscore etc.
- call every field possible
- added matchshot
- use WS
- -E 25 will be called as 25 (that is wrong)
- improve console logs
- add debug by argument
- add caller-profile-downloader
- add media_path_shared
- fix sending to websocket take too long / waiting for sound-playing (rework process_*)
- optional activation of third dart (-E)
- add "ambient1More"
- add Readme-section for updating
- background-audio-muting for windows-os
- keys for dart-number-combinations ie ambient_t1d1s1 -> sound
- add linux start-script
- start board on app-start if board-address is available!
- dl limit remove 1000 cap
- consider x.leg/set -> Gameshot / !x_leg! / player
- add ambient_group_level
- prohibit -M and -MS in main-directory; prohibit -MS in -M
- https://discord.com/channels/802528604067201055/955745166134747196/1089977962725650603
- add web-caller
- configure custom web-caller-port
- added caller language and gender filter
- fixed random-caller and random-caller-each-leg
- adds PCCYO
- rework PCC
- add support for game control
- add support for gc: dart-correction (multiple)
- add ban/change caller