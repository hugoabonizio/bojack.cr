# BoJack client

A Crystal shard client for [BoJack](https://github.com/marceloboeira/bojack) key-value store.

## Installation


Add this to your application's `shard.yml`:

```yaml
dependencies:
  bojack:
    github: hugoabonizio/bojack.cr
```


## Usage


```crystal
require "bojack-client"

client = BoJack::Client.new
client.set("foo", "bar")
puts client.get("foo")
```

## Development

TODO: Write development instructions here

## Contributing

1. Fork it ( https://github.com/hugoabonizio/bojack/fork )
2. Create your feature branch (git checkout -b my-new-feature)
3. Commit your changes (git commit -am 'Add some feature')
4. Push to the branch (git push origin my-new-feature)
5. Create a new Pull Request

## Contributors

- [hugoabonizio](https://github.com/hugoabonizio) Hugo Abonizio - creator, maintainer
