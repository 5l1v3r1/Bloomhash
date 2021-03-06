# Bloomhash

## Introduction

Bloomhash allows you to instantly check if a hash can _not_ be created using a specific wordlist. The chance of false positives is about 1/3'rd, but the chance for false negatives is zero. The purpose of bloomhash is providing information about wordlists that can be skipped when cracking hashes.

What does this mean? It means that if the lookup tells you that a word might be contained in the wordlist, it's useless. But if the result is negative (hash cannot be created), it's not possible that the wordlist can create the hash. This lookup can be done instantly. 

## License

Bloomhash is licensed under a Creative Commons Attribution-NonCommercial 4.0 International License. This means you are free to:

* Share — copy and redistribute the material in any medium or format
* Adapt — remix, transform, and build upon the material

**Under the following terms:**
* Attribution — You must give appropriate credit, provide a link to the license, and indicate if changes were made. You may do so in any reasonable manner, but not in any way that suggests the licensor endorses you or your use.
* NonCommercial — You may not use the material for commercial purposes. 

For more information about the license see:
[https://creativecommons.org/licenses/by-nc/4.0/](https://creativecommons.org/licenses/by-nc/4.0/)
