# Manganese.app

Wrap Chromium with user flags.

## Usage

1. Create a `~/.launchd.conf` containing a `CHROMIUM_USER_FLAGS` property with
   the desired values, e.g.:

        cat << EOF >> ~/.launchd.conf
        setenv CHROMIUM_USER_FLAGS "--no-referrers"
        EOF

## Author

© 2013 Tom Vincent <http://tlvince.com/contact>

## License

Released under the [MIT license][license].

  [license]: http://tlvince.mit-license.org
