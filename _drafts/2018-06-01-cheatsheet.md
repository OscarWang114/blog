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

* DNS
  * The trailing dots in domain names
  * [StackExchange](https://webmasters.stackexchange.com/questions/73934/how-can-urls-have-a-dot-at-the-end-e-g-www-bla-de/73937)
  * [dns-sd.org](http://www.dns-sd.org/trailingdotsindomainnames.html)
* [status code](https://www.w3.org/Protocols/rfc2616/rfc2616-sec10.html)
* [TCP UDP port numbers](https://en.wikipedia.org/wiki/List_of_TCP_and_UDP_port_numbers)
* ping, traceroute
* IPv4 vs IPv6
  * IPv4 - Internet Protocol Version 4:
  Four 8-bit decimal numbers (0-255) separated by periods. 32 bits in total.
  Example:
  8.8.8.8 [Google Public DNS](https://developers.google.com/speed/public-dns/docs/using)
  * IPv6 - Internet Protocol Version 6:
  Eight 16-bit hexadecimal blocks (0-ffff) separated by colons. 128 bits in total.
  Example:
  2001:4860:4860:0:0:0:0:8888 [Google Public DNS](https://developers.google.com/speed/public-dns/docs/using)
  2001:4860:4860::8888 [Google Public DNS using abbreviated syntax ](https://developers.google.com/speed/public-dns/docs/using)
* Reserved IP Address:
  * [Reference](https://en.wikipedia.org/wiki/Reserved_IP_addresses)
* [Common ports](http://www.pearsonitcertification.com/articles/article.aspx?p=1868080)
* Source port, destination port
* NAT Network address translation
* MAC Address
* Floating IP Address
* Ghostery
