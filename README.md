# Fetch Dependencies Base Image

Alpine-based image containing [UPX](https://github.com/upx/upx)-compressed dependencies for downloading and verifying files, specifically [Axel](https://github.com/axel-download-accelerator/axel) and [GnuPG](https://gnupg.org).


## Usage

Extend this image and, as appropriate / available, import GnuPG keys, download files and checksums, validate and verify.

For an example, see [nevstokes/php-src](https://github.com/nevstokes/docker-php-src/tree/fetchdeps)
