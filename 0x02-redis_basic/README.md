0x02. Redis basic
Back-end
Redis
What is Redis?
Redis stands for REmote DIctionary Server. It is an open-source (BSD licensed), in-memory data structure store that can be used as a database, cache, and message broker. Redis is known for its high performance, flexibility, and support for a variety of data structures.

Key Features of Redis
In-Memory Storage: Redis stores data in memory, making it extremely fast for read and write operations. It can persist data to disk periodically or through append-only files (AOF) to ensure durability.

Data Structures: Redis supports several data structures, including:

Strings: Basic key-value pairs.
Lists: Collections of ordered elements.
Sets: Unordered collections of unique elements.
Sorted Sets: Sets where each element is associated with a score, and elements are ordered by their scores.
Hashes: Maps of fields to values, like a dictionary.
Bitmaps: Bit-level operations.
HyperLogLogs: Probabilistic data structures for counting unique items.
Streams: Append-only log data structures.
Persistence: Redis provides options for persistence to disk, including snapshots (RDB) and append-only files (AOF). This allows data to be stored even after a restart.

Replication: Redis supports master-slave replication, enabling data redundancy and high availability.

Pub/Sub Messaging: Redis can be used as a message broker with its publish/subscribe (pub/sub) capabilities, allowing message broadcasting to multiple receivers.

Transactions: Redis supports atomic operations and transactions using the MULTI, EXEC, DISCARD, and WATCH commands.

Lua Scripting: Redis supports server-side scripting with Lua, enabling complex operations to be executed atomically.

Cluster Mode: Redis can be deployed in a clustered mode for horizontal scalability and distributed storage.

Common Use Cases
Caching: Redis is often used as a cache to speed up data retrieval by storing frequently accessed data in memory.

Session Storage: Web applications use Redis to store session data, providing fast access to user sessions.

Real-Time Analytics: With its fast in-memory operations, Redis is suitable for real-time analytics and monitoring.

Message Queues: Redis’s lists and pub/sub capabilities make it a good choice for implementing message queues and task queues.

Leaderboards and Counting: Redis’s sorted sets are ideal for building leaderboards and implementing counting systems.

Distributed Locks: Redis can be used to implement distributed locks for coordinating distributed systems.
