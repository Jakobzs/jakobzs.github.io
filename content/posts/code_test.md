+++
title="Test code syntax highlight"
date=2024-01-01
draft=false

[taxonomies]
tags=["test", "code"]

[extra]
disable_comments = true
+++

```rust
fn factorial(n: u64) -> u64 {
    match n {
        0 => 1,
        _ => n * factorial(n-1)
    }
}
```

```typescript
const sum = (n: number) =>  n * (n + 1) / 2
```

```cpp
#include <iostream>

int main() {
    std::cout << "Hello, World!" << std::endl;
    return 0;
}
```
