# energyPackages

## Folders

- **test_packages/original:** the original packages, downloaded from npn/pypi.
-  **test_packages/zopfli:** the packages compressed using zopfli.
-  **test_packages/xz:** the packages compressed using xz.
-  **test_packages/zstd:** the packages compressed zstd.

## Commands used for compression/decompression

All the other tools have been installed from [homebrew]([https://www.example.com](https://formulae.brew.sh/)).

### gzip

Decompress to a tar file:

`gunzip path_to_file` 

Compress a tar file:

`gzip path_to_file`

### zopfli

It relies on gzip for decompression, use:

`gunzip path_to_file` 

Compress a tar file:

`zopfli path_to_file`

### xz

Decompress to a tar file:

`xz --decompress path_to_file` 

Compress a tar file:

`xz path_to_file`

### zstd

Decompress to a tar file:

`zstd --decompress path_to_file` 

Compress a tar file:

`zstd path_to_file`
