# uuid
This is a simple UUID utillity based on libuuid, use -luuid to link the libuuid library.

Usage:

```c++
#include <iostream>
#include "uuid.hpp"
#include <cassert>

int main() {
    UUID uuid;

    assert(uuid.is_null() == true);

    uuid = UUID::generate();
    std::cout << uuid << std::endl;

    uuid.clear();
    assert(uuid.is_null() == true);

    return 0;
}
```

