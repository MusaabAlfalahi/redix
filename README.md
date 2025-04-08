# Redix

**Redix** is a simple in-memory database implemented in Go, inspired by Redis. It supports basic Redis operations for strings and hashes, parses commands using the Redis Serialization Protocol (RESP), handles multiple concurrent connections with Go routines, and ensures data persistence via the Append-Only File (AOF) method.