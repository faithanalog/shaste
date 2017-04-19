# `shaste` - A Simple Hastebin Client

`shaste` is a simple bash [hastebin](https://hastebin.com) client.

`shaste` uses `curl` for requests. It is the only dependency aside from the
usual coreutils.

# Using `shaste`

```
Usage: shaste [-h] [-- <files>]

  Options:

    -h

      Print this help message and exit successfully

    -- <files>

      All arguments following a '--' will be treated as filenames. Each file
      will be uploaded separately, and URLs will be returned separated by
      newlines. If this argument is not present, STDIN will be uploaded
      instead.
```
