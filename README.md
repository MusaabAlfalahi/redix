# Redix

**Redix** is a simple in-memory database implemented in Go, inspired by Redis. It supports basic Redis operations for strings and hashes, parses commands using the Redis Serialization Protocol (RESP), handles multiple concurrent connections with Go routines, and ensures data persistence via the Append-Only File (AOF) method.

## Run locally
### 1. Clone the Redix Repository

```bash
git clone https://github.com/MusaabAlfalahi/redix.git
cd redix
```

### 2. Install dependencies & build

```bash
go mod tidy
go build -o redix
```

### 3. Run Redix Server
```bash
./redix
```

### 4. Run the Client (e.g., redis-cli)
```bash
redis-cli
```

### 5. Now you can use Redix :)
