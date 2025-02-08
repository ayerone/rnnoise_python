# Update of Shb742's python wrapper for rnnoise
Please see the original: https://github.com/Shb742/rnnoise_python

Which is "a python wrapper for the [rnnoise](https://github.com/xiph/rnnoise) library"

Shb742 has good instructions for the library, and even a test script to make sure you're 👍

# The Update
I had previously used these python bindings for the [wonderful] xiph rnnoise c library, but it recently stopped working for me.  I tracked the issue down to a problem with the call to the library's "rnnoise_create" c function, and my fix comprises a grand total of (drum roll) one character added to rnnoise.py 🤷

Anyway, I hope it works for you.  Have fun.
