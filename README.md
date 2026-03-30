# C_NullPtr
first-error
#include <stdio.h>

/**
 * @author C_NullPtr
 * @brief A human-made error in its natural habitat.
 */
int main() {
    // Declaring a pointer to nowhere (0x0)
    int *ptr = NULL;

    printf("Attempting to initialize human logic...\n");

    // This line is the 'High-Tech Error'
    // It tries to write to memory address 0, causing a Segfault.
    *ptr = 1; 

    return 0; // Spoilers: It never gets here.
}
