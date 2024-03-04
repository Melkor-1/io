# io
Missing I/O functions from the C Standard Library

No need to build, simply add the header to a source file like so:

```
#define IO_IMPLEMENTATION
#define IO_STATIC
#define TEST_MAIN
#include "io.h"
```

All documentation can be found in `io.h`. It also includes a test `main()`
program if `TEST_MAIN` is defined before its inclusion.


