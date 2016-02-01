# hemish

## Summary

hemish is a bash script to know if you are in the north or in the south hemisphere.

## Usage

Use `hemish` to get your hemisphere:

```sh
$ ./hemish
$ north
```

The script will scrape your coordinate itself.
If you have your coordinates (format as "float float"), you can use `hemish` like this:

```sh
$ ./hemish -c -42.42 73.31
$ south
```

## Motivation

Fun and learning bash.
