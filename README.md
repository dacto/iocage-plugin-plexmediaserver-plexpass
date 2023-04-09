## HOW-TO Install this fork

```shell
BRANCH=master
JSON=/tmp/plex.json

fetch -o "$JSON" "https://raw.githubusercontent.com/dacto/iocage-plugin-plexmediaserver-plexpass/${BRANCH}/plexmediaserver-plexpass.json"
iocage fetch -P "$JSON" --branch "$BRANCH" -n plexmediaserver-plexpass
```
# iocage-plugin-plexmediaserver-plexpass
Artifact file(s) for PlexMediaServer (PlexPass) iocage plugin
