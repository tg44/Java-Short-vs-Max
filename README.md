Java-Short-vs-Max
=================

A small program for measureing the Collections.sort.get(last) how much slower then max search


Some result with an x64 win7 on AMD Phenom || x6 1090T (but in a normally used machine):

```
Element number: 1
Repeat number: 10000
Avg max: 6.55E-4ms
Avg sort: 0.001848ms
Rate: 2.8213740458015266

Element number: 10
Repeat number: 10000
Avg max: 1.11E-4ms
Avg sort: 0.001407ms
Rate: 12.675675675675675

Element number: 100
Repeat number: 10000
Avg max: 4.1799999999999997E-4ms
Avg sort: 0.013500999999999999ms
Rate: 32.29904306220096

Element number: 1000
Repeat number: 10000
Avg max: 0.0037170000000000003ms
Avg sort: 0.137708ms
Rate: 37.04815711595373

Element number: 10000
Repeat number: 10000
Avg max: 0.063197ms
Avg sort: 1.861513ms
Rate: 29.455717834707343

Element number: 100000
Repeat number: 10000
Avg max: 0.648336ms
Avg sort: 29.175113ms
Rate: 44.99998920312924
```
