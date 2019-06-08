# Vulnerable OpenWrt luci feed

#### NOTE :
> **DO NOT COPY AND USE THIS REPOSITORY, THIS LUCI FEED IS VULNERABLE WITH A CRITICAL OS COMMAND INJECTION BUG. THIS FEED IS CURRENTLY BEING UTILISED IN IOT-GOAT PROJECT**

## Description

This is a fork of OpenWrt "luci"-feed containing LuCI - OpenWrt Configuration Interface reverted back to the commit `f5671b4` _(https://github.com/openwrt/luci/commit/f5671b420a0a418a217cf55dd4fbee73f336b4de)_



## Usage

This feed is enabled by default. Your feeds.conf.default (or feeds.conf) should contain a line like:
```
src-git luci https://github.com/0x48piraj/luci.git
```

To install all its package definitions, run:
```
./scripts/feeds update luci
./scripts/feeds install -a -p luci
```

## API Reference

You can browse the generated API documentation [directly on Github](http://htmlpreview.github.io/?http://raw.githubusercontent.com/openwrt/luci/master/documentation/api/index.html).

## Development

Documentation for developing and extending LuCI can be found [in the Wiki](https://github.com/openwrt/luci/wiki)

## License

See [LICENSE](LICENSE) file.
 
## Package Guidelines

See [CONTRIBUTING.md](CONTRIBUTING.md) file.
