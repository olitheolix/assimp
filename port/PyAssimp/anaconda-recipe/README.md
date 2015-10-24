# Anaconda receipes for PyAssImp

The recipe builds the AssImp library as well as Python bindings. Note that any
system installed AssImp library will ignored by the Python bindings.

To build the package:

```
conda build --python 2.7 --python 3.4 --python 3.5 assimp
```
