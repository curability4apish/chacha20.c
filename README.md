A unified version "unified-chacha20.c" was added as a fork, with an example implementation, and it doesn't require chacha20.h.

# chacha20-c
ChaCha20 stream cipher implemented in C

```c

struct chacha20_context ctx;
chacha20_init_context(&ctx, key, nonce, counter);
chacha20_xor(&ctx, buffer, size_of_buffer);

```
