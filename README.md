# Whitelie

A self hosted white space compiler. It works on 64-bit Linux

# Usage

```console
$ whitelie < source.ws > output
$ chmod +x output
$ ./output
```

# Confirming it is self hosted

```console
$ whitelie < whitelie.ws > whitelie2
$ md5sum whitelie whitelie2
418b0b9a58caaa9e99a2d5e3649f6faf  whitelie
418b0b9a58caaa9e99a2d5e3649f6faf  whitelie2
```


# The trick

This is a joke of April Fool's Day.
I didn't write whitespace.
I wrote a whitespace assembler and write in it.

It is available from this gist.

https://gist.github.com/KeenS/6081b0c802a4e575ddbacb1930680870
