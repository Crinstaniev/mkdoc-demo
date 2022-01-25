# Welcome to MkDocs

For full documentation visit [mkdocs.org](https://www.mkdocs.org).

## Commands

* `mkdocs new [dir-name]` - Create a new project.
* `mkdocs serve` - Start the live-reloading docs server.
* `mkdocs build` - Build the documentation site.
* `mkdocs -h` - Print help message and exit.

## Project layout

    mkdocs.yml    # The configuration file.
    docs/
        index.md  # The documentation homepage.
        ...       # Other markdown pages, images and other files.

Coding block test

```c
#include <stdio.h>
#include <stdlib.h>

int main(int argc, char **argv)
{
    int *p_int = (int *)malloc(10 * sizeof(int));
    free(p_int);
    return 0;
}
```
