[![Snap Status](https://build.snapcraft.io/badge/RSATom/janus-gateway-snap.svg)](https://build.snapcraft.io/user/RSATom/janus-gateway-snap)

# janus-gateway-snap
Helper repo for build Janus WebRTC Server on build.snapcraft.io

## Directories mapping
* Configs: `$SNAP_COMMON/etc` (`/var/snap/janus-gateway/common/etc`)
* Recordings: `$SNAP_COMMON/share/recordings` (`/var/snap/janus-gateway/common/share/recordings`)
* Voicemail: `$SNAP_COMMON/share/voicemail` (`/var/snap/janus-gateway/common/share/voicemail`)

## Installing on debian
* apt update
* apt install snapd
* snap install core
* snap install janus-gateway
* snap start janus-gateway
* Make a redirect from the http://domain.com/janus to https://domain.com/janus OR change sertificates path /var/snap/janus-gateway/common/etc

<br>

[![Get it from the Snap Store](https://snapcraft.io/static/images/badges/en/snap-store-white.svg)](https://snapcraft.io/janus-gateway)
