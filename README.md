# Disco Coverart Library

Native library for M4A metadata embedding using Bento4.

## Features

- Embed cover art in M4A files
- Add metadata (title, artist, album, year)
- High-performance native C++ implementation
- Android JNI interface

## Integration

### As Git Submodule

```bash
git submodule add https://github.com/omarkarimli/disco-coverart-lib.git libs/coverart
```

### In your CMakeLists.txt

```cmake
add_subdirectory(libs/coverart)
target_link_libraries(your_target coverart)
```

## Building

This library uses CMake and is designed to be built as part of an Android NDK project.

### Requirements

- Android NDK r21+
- CMake 3.18+

## License

This library includes Bento4, which is licensed under the GPLv2 license.
See [bento4/README.md](bento4/README.md) for more details.

## Credits

- [Bento4](https://github.com/axiomatic-systems/Bento4) - MP4/MPEG-4 Toolkit
