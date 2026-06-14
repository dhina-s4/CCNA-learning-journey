TOPOLOGY


<pre>
[ New York Branch ]                                                                                    [ Tokyo Branch ]
                                                                                                               
  +-------+                                                                                                      +---------+
  |  PC2  |----+                                                                                          +----> | Server0 |
  +-------+    |    +---------+     +---------+     +-------+     +------------+     +-------+     +---------+    |         |
               +--->| Switch0 |---->| Router0 |---->| ASA0  |---->|    2911    |---->| ASA1  |---->| Router1 |--->+---------+
  +-------+    |    +---------+     +---------+     +-------+     |The Internet|     +-------+     +---------+    |
  |  PC1  |----+                                                  +------------+                                  +---------+
  +-------+                                                             |                                         | Server1 |
                                                                        v                                         +---------+
                                                                  +----------+
                                                                  |  Laptop  |
                                                                  | Attacker |
                                                                  +----------+
</pre>
# Objective

Understand how network devices connect together.

# Devices Used

- 2 PCs
- 1 Switch
- 2 Routers
- 2 ASA Firewalls

# What I Learned

- Switches connect hosts
- Routers connect networks
- Firewalls filter traffic

# Verification

Successfully connected devices in Packet Tracer.
