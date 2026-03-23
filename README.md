# mybase64

A minimal Bash utility for encoding and decoding Base64 strings from the command line.

## Usage

```bash
./mybase64.sh <STRING> [-d]
```

**Arguments:**

- `<STRING>` — The string to encode, or the Base64 string to decode.
- `-d` — (Optional) Decode mode. When provided, the input is decoded from Base64.

## Examples

Encode a string:

```bash
$ ./mybase64.sh "Hello, World!"
SGVsbG8sIFdvcmxkIQ==
```

Decode a Base64 string:

```bash
$ ./mybase64.sh "SGVsbG8sIFdvcmxkIQ==" -d
Hello, World!
```