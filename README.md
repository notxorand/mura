# ムラ

Mura (Japanese for inconsistency) is a general purpose endpoint guard for multiple writers.

## Features

+ Mutex guard for attempting concurrent writes.
+ Indempotency keys generated from seeded data payloads.
+ CAS-style write attempts.

## Stack

+ Rust
+ Turso (SQLite primitive)

## Transports

+ [ ] HTTP
+ [ ] WS
+ [ ] gRPC
+ [ ] TCP/IP 
