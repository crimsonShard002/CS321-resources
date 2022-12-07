# Intro to Threads and Parallelism

Shows basic usage and benefits of threads in Java.

Example 1:  hellothreads

```
java hellothreads.Dance
```

Example2: widgetmaker

```
time java widgetmaker.WidgetMaker 100
time java FasterWidgetMaker 100
```

Example 3: parallel mergesort

First run sequentially 

```
time mergesort 30000000
```

Then run in parallel.

```
time mergesort 30000000 -p 3
```

This creates one thread for each recrsive call, up to 3 levels deep.