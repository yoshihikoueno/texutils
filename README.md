# Tex Utilities

Provides a module that compiles a tex file and shows the resulting PDF file.
Note that the result pdf will be opened only if the compiling was successful.

If makefile is available and `ignore_makefile` is not set,
this module will just call make.

## Usage:

```bash
    $ preview_tex <TEX file> [ignore_makefile]
```

