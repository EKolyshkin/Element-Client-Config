# Element-Matrix-Client
Configuration file to enable various Labs features in [Element Matrix Client](https://element.io/), such as pinned messages and Element Call.

**Warning:** Some features enabled in this configuration file may not work on the stable Element client and require **Element Nightly** client instead. You can download it by finding it on the [download page](https://element.io/download) or [releases page](https://packages.element.io/nightly/install/index.html).

## Where to Put ```config.json```
```$NAME``` = Name of the client, usually "Element" or "Element Nightly".

- **Windows** - ```%APPDATA%\$NAME\config.json```
- **Linux** - ```$XDG_CONFIG_HOME/$NAME/config.json``` or ```~/.config/$NAME/config.json```
- **macOS** - ```~/Library/Application Support/$NAME/config.json```

## Reference Links
- [Where to put ```config.json```](https://github.com/vector-im/element-desktop#user-specified-configjson)
- [General ```config.json``` Notation](https://github.com/vector-im/element-web/blob/develop/docs/config.md)
- [How to enable Labs Flags](https://github.com/vector-im/element-web/blob/develop/docs/config.md#labs-flags)
- [Labs Flag Notation](https://github.com/vector-im/element-web/blob/develop/docs/labs.md)
