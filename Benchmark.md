Don't take these results too seriously, because they were not run in a controlled environment.

A similar blog which was showed at the [tutorial](http://shaml.sztupy.hu/tutorial-start.html) was created in rails, merb and S#aml. The benchmark used was `ab` with the following parameters:

```
ab -c 20 -n 2000 website
```

The mean requests per second results were the following (best results from three runs):
  * rails using mod\_rails: 7.86  `[#/sec] (mean)`
  * merb  using mod\_rack: 9.75  `[#/sec] (mean)`
  * shaml using xsp2: 19.51  `[#/sec] (mean)`
  * shaml using mod\_mono: 20.32  `[#/sec] (mean)`