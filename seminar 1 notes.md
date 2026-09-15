楊道恩 `9/15/2026 Montclair state University` 王大進教授 `- System-level diagnosis - An introduction and recent results` 網路診斷與容錯

```
Network node faulty node diagnosis: based on the tests of status of neighbor
nodes
```

```
= Tester node =
```

```
The tester node itself could be a faulty node!
```

`Faulty 'c' - The result is uncertain` （任意的 `-` 不可靠，不確定） `, therefore is invalid node Faulty 'b' - ?` 

```
= PMC model =
t-diagnosability: If there's too many faulty nodes, arbiter cannot arbitrate
correctly
```

```
Given a network, there is a maximum of [t faulty nodes]. When faulty node amount
exceeds t, arbiter no longer works properly
```

```
Sufficient condition if a diagnosable G(V, E):
|V| >= 2t+1
```

```
where k(G) >= t
```

```
V is total number of nodes
k(G) is the minimum degree of G
```

```
If we assume that the neighboring nodes of any node cannot be all faulty
simultaneously (which is high likely), there is more faulty nodes allowed for
arbiter to fully arbitrate
```

```
= Conditional Diagnosability =
```

```
Given a network scenario that is unlikely to occur, then we can eliminate
uncertain syndromes, therefore faulty nodes are more accurately arbitrate
```

