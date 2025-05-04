# Saddle
A YAML parser for Cloudwrights Saddle config file.

## Usage

The `saddle` file is executable directly. It assumes a file called `saddle.yaml` exists in the same directory, and will output an error if it does not.

The script takes a single argument, which is the name of a key or key path in the `saddle.yaml` file. A path to a nested key can be provided, in the format of period-separated values.

## Errors

If an error is encountered, an empty string will be returned on stdout, and the error will be returned in stderr.
