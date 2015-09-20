# Manganese.app

Wrap Chromium with user flags.

**NOTE**: currently broken in Yosemite (`.launchd.conf` support was removed)

## Usage

1. Create a `~/.launchd.conf` containing a `CHROMIUM_USER_FLAGS` property with
   the desired values, e.g.:

```shell
cat << EOF >> ~/.launchd.conf
setenv CHROMIUM_USER_FLAGS "--no-referrers"
EOF
```

## Author

© 2015 Tom Vincent <https://tlvince.com/contact>

## License

Released under the [MIT license][license].

  [license]: http://tlvince.mit-license.org
