# bin/

## bin/libtest

Tests a C++ header-only library using samples in `test`.

```bash
./bin/libtest
```

```
Testing cpplib...
Testing cpplib/data-structures...
Testing cpplib/data-structures/trees...
Testing cpplib/data-structures/trees/segment-tree...
Testing range-sum-queries_0... OK
Testing range-sum-queries_1... OK
Testing range-sum-queries_2... OK
```

The samples must follow the structure:

```
...
foo.cpp
foo.stdin
foo.stdout
...
```

Where `foo.stdin` is the input of `foo.cpp` and `foo.stdout` is the expected output.

## bin/pyth

Adds the project path to the `PYTHONPATH` variable.

```bash
source bin/pyth
```

## bin/venv

Sets up a python virtual environment using python-pip and python-venv.

```bash
source bin/venv PYTHON
```

Requires a `requirements.txt` and a `PYTHON` interpreter.
