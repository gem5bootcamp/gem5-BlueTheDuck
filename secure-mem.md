Notes:

Cache stores:
1. Data hash
2. Counter address
3. Node address 1
4. Node address 2
5. Node address 3

When the SecureMemory object receives a request:
- Forward data request to main memory
- Request metadata from main memory
- Request metadata from cache

If the data hash is found in cache, don't need counter and merkel
If the counter is found in cache, don't need merkel tree

