# exfile

`exfile` is a shell script designed to extract various types of compressed files. By default, it extracts files to the same location as the compressed file. Users can optionally specify a different output directory using the `-o` option.

## Features

- Supports multiple compressed file formats including `.tar.bz2`, `.tar.gz`, `.tar.xz`, `.bz2`, `.rar`, `.gz`, `.tar`, `.tbz2`, `.tgz`, `.zip`, `.Z`, and `.7z`.
- Extracts files to the same location as the compressed file by default.
- Allows specifying an output directory with the `-o` option.
- Provides a summary including the decompressed size and the time taken for extraction.

## Usage

### Basic Usage

To extract a file to its current directory:

```bash
./exfile <filename>
```
