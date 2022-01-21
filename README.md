### How to reproduce

1. Run docker compose `docker compose up`. 
2. Open console [http://localhost:9001](http://localhost:9001).
3. Log in with username `reader-user` and password `reader-user`.
4. Click on Browse button on the right side to browse the _test-bucket_.
5. The Console crash.

Expected: The `reader-user` can browse the bucket with attached [policy.json](./policy.json).


Note:
- docker compose version v2.2.1
