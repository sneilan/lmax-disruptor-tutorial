# Hello World LMAX Disruptor (C++ & < 200 LOC)

## TLDR

This is an implementation of the LMAX disruptor (commonly used in major stock exchanges like NASDAQ) in C++ < 200 LOC. An LMAX disruptor is a ring buffer on top of a shared memory buffer with one process writing to the ring buffer and one or more processes consuming from it.

This allows for insanely fast communication between processes at the cost of durability and increased memory usage.

For now check out https://github.com/sneilan/stock-exchange for an example of it in action.

I'm also open to employment opportunities. Email me at sean@seanneilan.com!
