Java static initializers

SSL deprecated. Use TSL.
A certificate contains the server public key.
Asymmetric encryption for key exchange, e.g. RSA.
TSL handshake to generate a shared secret.
Symmetric encryption for encrypting the files, e.g. AES-256
The key is encrypted using asymmetric encryption.


Process
Each process provides the resources needed to execute a program. A process has a virtual address space, executable code, open handles to system objects, a security context, a unique process identifier, environment variables, a priority class, minimum and maximum working set sizes, and at least one thread of execution. Each process is started with a single thread, often called the primary thread, but can create additional threads from any of its threads.

Thread
A thread is an entity within a process that can be scheduled for execution. All threads of a process share its virtual address space and system resources.


Java:

Stack<Integer> stack = new Stack<>();
Queue<Integer> queue = new LinkedList<>();
PriorityQueue<Integer> pQueue = new PriorityQueue<>();


Python
```
stack = []
stack.pop()
stack.append()
```

```
queue = []
queue.popleft()
queue.append()
```

```
import heapq
h = [5,6,7,1,3]
heapq.heapify(h)
# h = [1,3,7,6,5]
heapq.heappush(h,8)
# h = [1,3,7,6,5,8]
heapq.heappop(h)
# 1
```

[1,2,3,4]
1 2
1 3
1 4
2 3
2 4
3 4 
