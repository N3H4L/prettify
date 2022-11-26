# Prettify

A simple and dumb script that highlights all the GET parameters from a big fat URL, so that you do not miss any of those while looking at a dump.

## INSTALLATION:

```bash
$ git clone https://github.com/N3H4L/prettify.git
$ cd prettify
$ sudo cp prettify /usr/local/bin/
```

## USAGE:

```bash
$ echo "https://example.com/path/of/dir?param1=value1&param2=value2#fragment" | prettify
$ cat urls.txt | prettify
```