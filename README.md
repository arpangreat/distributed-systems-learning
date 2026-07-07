# distributed-systems-learning
learning distributed systems through mit 6.824 (6.5840) in youtube

  - Lab 1: MapReduce -> Lecture 1: Introduction and Lecture 2: RPC and Threads. The schedule explicitly assigns Lab 1 after Lecture 1 and pairs Lecture 2 with the Go tutorial, which is the
  main implementation support you need for the lab code. schedule (https://pdos.csail.mit.edu/6.5840/schedule.html) lines 7-11
  - Lab 2: Key/Value server -> Lecture 2: RPC and Threads and Lecture 3: GFS. The RPC/threading lecture is the coding base; GFS gives you the replicated-storage mindset the lab builds on.
  schedule (https://pdos.csail.mit.edu/6.5840/schedule.html) lines 10-15
  - Lab 3: Raft -> Lecture 4: Paxos for the consensus idea, then Lecture 6: Fault Tolerance: Raft (1) and Lecture 7: Fault Tolerance: Raft (2) for the actual algorithm, plus Lecture 8:
  Consistency and Linearizability to reason about correctness. schedule (https://pdos.csail.mit.edu/6.5840/schedule.html) lines 16-18 and 28-37
  - Lab 4: KV Raft -> Lectures 6, 7, 8, with Lecture 9: Zookeeper as a useful systems-pattern lecture once you’re already building replicated services. schedule
  (https://pdos.csail.mit.edu/6.5840/schedule.html) lines 28-42
  - Lab 5: Sharded KV -> Lecture 11: Distributed Transactions, Lecture 12: Spanner, Lecture 13: Chain Replication, and Lecture 14: Optimistic Concurrency Control. Those are the core
  conceptual pieces for sharding, reconfiguration, and moving data safely. schedule (https://pdos.csail.mit.edu/6.5840/schedule.html) lines 47-69

  - structs, methods, slices, maps
  - goroutines and sync.Mutex
  - file I/O
  - interfaces and RPC basics

  The one lecture-level Go item that matters early is Lecture 2’s Go tutorial prep and, later, Lecture 5: Go patterns when the code gets more concurrent. schedule
  (https://pdos.csail.mit.edu/6.5840/schedule.html) lines 10-11 and 23-24

# Priority Order:

  1. Lecture 1
  2. Lecture 2
  3. Lab 1
  4. Lecture 3
  5. Lab 2
  6. Lectures 4, 6, 7, 8
  7. Lab 3 and Lab 4
  8. Lectures 11-14
  9. Lab 5

  That is the shortest path that matches the actual course structure.
