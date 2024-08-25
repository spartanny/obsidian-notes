https://discord.com/blog/how-discord-stores-billions-of-messages

What didn't worked ? 
	Discord used MongoDB as first technology to write but this was not well suited for scaling as they grew

#### #Cassandra

- Its a KKS : (Key,Key) -> Value store. The keys can be compounded as well
	-  2 keys because : 1 for node/partition and other same as your indexing key
- Reads are more expensive (takes more time) than writes ..... to study more on this  !
- it is an AP database, means writes are eventually consistent.
- Cassandra uses GC (built on java) | whereas its alternate Scylla is written on c++

> Deletion in Cassandra is done by marking the row as tombstone and ignoring any subsequents requests for this data entry.
> Point to note here is adding null values is also treated as a tombstone event in cassandra


