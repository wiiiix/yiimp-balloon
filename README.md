##yiimp-balloon

from yiimp, call the 'balloon_128' function.

the hash function has only been tested extensively with 80 byte headers, but you can include the len
parameter so yiimp can pretend (ive now added it).

additionally make sure you compile against libssl and libcrypto for the evp/aes functions (-lssl -lcrypto)
