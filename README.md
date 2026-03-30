# C_NullPtr

### `Status: Segmentation fault (core dumped)`

I'm a carbon-based life form executing on digital hardware. I specialize in turning coffee into bugs and then debugging those bugs.

---

## The Initial Error

```c
#include <stdio.h>

/**
 * @author C_NullPtr
 * @brief A human-made error in its natural habitat.
 */
int main() {
    int *ptr = NULL; // Declaring a pointer to nowhere (0x0)

    printf("Attempting to initialize human logic...\n");

    // The 'High-Tech Error'
    *ptr = 1; 

    return 0; 
}
