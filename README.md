[![Join the chat at https://gitter.im/unsign-mach-o/Lobby](https://badges.gitter.im/unsign-mach-o/Lobby.svg)](https://gitter.im/unsign-mach-o/Lobby?utm_source=badge&utm_medium=badge&utm_campaign=pr-badge&utm_content=badge) [![ISC License](https://img.shields.io/badge/license-ISC%20License-blue.svg)](https://opensource.org/licenses/ISC)

### Building

   `make ARCHS="-arch x86_64"`

Add more `-arch` options to `ARCHS` if you wish to make a FAT binary.  This
specifies what host architectures to support.  It does not affect what
architectures the built `unsign` binary will handle.

### Testing

    `make test`

### Installing

1. `make`.
2. Move `unsign` to wherever you like.

### License
ISC

### Original

http://www.woodmann.com/collaborative/tools/index.php/Unsign

