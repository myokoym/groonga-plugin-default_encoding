# groonga-plugin-default_encoding

TODO: Write description.

## Prepare

```sh
$ git clone git@github.com:[USERNAME]/groonga-plugin-default_encoding.git
$ cd groonga-plugin-default_encoding
$ ./autogen.sh
```

## Build

Groonga is installed in `/usr/local`:

```sh
$ ./configure
$ make
```

Groonga is installed in other directory (e.g.: `/tmp/local`):

```sh
$ ./configure --prefix=/tmp/local
$ make
```

## Test

Using [grntest](https://github.com/groonga/grntest).

```sh
$ test/run-test.sh
```

## Install

For system directory (e.g.: `/usr/local`):

```sh
$ sudo make install
```

For user directory (e.g.: `/tmp/local`):

```sh
$ make install
```

## Usage

TODO: Write usage.

## Development

### Add test

```sh
$ vi test/suite/new_test.test
$ test/run-test.sh
$ cat test/suite/new_test.actual  # Confirm result
$ mv test/suite/new_test.{actual,expected}  # Rename confirmed test
```
