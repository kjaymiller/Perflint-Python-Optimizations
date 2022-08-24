# Perflint-Python-Optimizations
Tutorials for more efficient python using [Perflint](https://github.com/tonybaloney/perflint) recommendations

Matches:
- W8101 : Unnecessary `list()` on already iterable type (`unnecessary-list-cast`)
- W8102: Incorrect iterator method for dictionary (`incorrect-dictionary-iterator`)
- W8201: Loop invariant statement (`loop-invariant-statement`)
-# Notes on loop invariance
- W8202: Global name usage in a loop (`loop-global-usage`)
- R8203 : Try..except blocks have a significant overhead. Avoid using them inside a loop (`loop-try-except-usage`).
- W8204 : Looped slicing of bytes objects is inefficient. Use a memoryview() instead (`memoryview-over-bytes`)
- W8205 : Importing the "%s" name directly is more efficient in this loop. (`dotted-import-in-loop`)
- W8301 : Use tuple instead of list for a non-mutated sequence. (`use-tuple-over-list`)
- W8401 : Use a list comprehension instead of a for-loop (`use-list-comprehension`)
- W8402 : Use a list copy instead of a for-loop (`use-list-copy`)
- W8403 : Use a dictionary comprehension instead of a for-loop (`use-dict-comprehension`)
