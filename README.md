# Sparkplug

![Sparkplug from Transformers](sparkplug.jpg)

Quickly try out fastlane plugins.

## Installation

Install this using:

    $ gem install sparkplug

## Usage

Simply run it with a plugin name as argument, in a fresh directory:

```bash
$ mkdir test
$ cd test
$ sparkplug ascii_art
$ bundle exec fastlane yolo
```

If you are still developing your plugin, this will ask you for a local path or GitHub URL. A `Fastfile` with all the options will be automatically created, so you are immediately good to go!

## Contributing

Bug reports and pull requests are welcome on GitHub at <https://github.com/neonichu/sparkplug>.


## License

The gem is available as open source under the terms of the [MIT License](http://opensource.org/licenses/MIT).
