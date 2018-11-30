# SHA-256

A python implementation of the Secure Hashing Algorithm 256 (SHA-256). 

## Usage 

As shown in `test.py`, use SHA-256 as such:

    from SHA_256 import SHA_256
    s = SHA_256()
    hash = s.hash("ascii string")
    print(hash)