## Twitter

### Desktop

pscan

```zsh
**** Graph Clustering (Release): ../dataset, 0.3, 5 ***
	*** Finished loading graph!
Total time without IO: 2340757763
	*** Start write result into disk!
```

sequential

```zsh
int size:4
n:41652230, m:1369000750
read degree file time:103 ms
read adjacency list file time:3082 ms
check input graph file time:1752 ms

Total input cost:6502 ms
with google perf start------------
1st: prune execution time:12238 ms
2nd: check core first-phase bsp time:2378220 ms
2nd: check core second-phase bsp time:142053 ms
3rd: core clustering time:424 ms
4th: non-core clustering time:936 ms

prune0 definitely not reachable:346551512
prune1 definitely reachable:4856528
intersection times:333092335
cmp0:305687955207
cmp1:270084254384
equal cmp:40209354722
max portion:22493
with google perf end--------------
PROFILE: interrupts/evictions/bytes = 252943/229135/14664480
Total time without IO:2533875 ms
Total output cost:528 ms
```

parallel

```zsh
int size:4
n:41652230, m:1369000750
read degree file time:1300 ms
read adjacency list file time:37902 ms
check input graph file time:1801 ms

Total input cost:42550 ms
with google perf start------------
1st: prune execution time:4700 ms
2nd: check core first-phase bsp time:1853156 ms
2nd: check core second-phase bsp time:49436 ms
3rd: core clustering time:448 ms
4th: non-core clustering time:841 ms
with google perf end--------------
PROFILE: interrupts/evictions/bytes = 265429/18187/1756040
Total time without IO:1908585 ms
Total output cost:503 ms
```

### Cluster: gpu-23

sequential

```zsh
int size:4
n:41652230, m:1369000750
read degree file time:167 ms
read adjacency list file time:36128 ms
check input graph file time:2174 ms

Total input cost:40450 ms
1st: prune execution time:12652 ms
2nd: check core first-phase bsp time:2765647 ms
2nd: check core second-phase bsp time:117539 ms
3rd: core clustering time:431 ms
4th: non-core clustering time:965 ms

prune0 definitely not reachable:346551512
prune1 definitely reachable:4856528
intersection times:333092335
cmp0:305687955207
cmp1:270084254384
equal cmp:40209354722
max portion:22493
Total time without IO:2897236 ms
Total output cost:3042 ms
```

parallel

```zsh
int size:4
n:41652230, m:1369000750
read degree file time:410 ms
read adjacency list file time:41889 ms
check input graph file time:2071 ms

Total input cost:46358 ms
1st: prune execution time:3073 ms
2nd: check core first-phase bsp time:1972818 ms
2nd: check core second-phase bsp time:27115 ms
3rd: core clustering time:973 ms
4th: non-core clustering time:1141 ms
Total time without IO:2005122 ms
Total output cost:3239 ms
```

## Webbase

### Desktop

pscan

```zsh
**** Graph Clustering (Release): ../dataset, 0.3, 5 ***
	*** Finished loading graph!
Total time without IO: 59182874
	*** Start write result into disk!
```

sequential

```zsh
int size:4
n:118142143, m:1050026736
read degree file time:221 ms
read adjacency list file time:4030 ms
check input graph file time:1728 ms

Total input cost:7543 ms
with google perf start------------
1st: prune execution time:6547 ms
2nd: check core first-phase bsp time:57428 ms
2nd: check core second-phase bsp time:10702 ms
3rd: core clustering time:3496 ms
4th: non-core clustering time:2447 ms

prune0 definitely not reachable:203886616
prune1 definitely reachable:46119741
intersection times:275007011
cmp0:2061408067
cmp1:15685059958
equal cmp:6698684510
max portion:20398
with google perf end--------------
PROFILE: interrupts/evictions/bytes = 8048/7144/456808
Total time without IO:80626 ms
Total output cost:18280 ms
```

parallel

```zsh
int size:4
n:118142143, m:1050026736
read degree file time:251 ms
read adjacency list file time:3930 ms
check input graph file time:1728 ms

Total input cost:7431 ms
with google perf start------------
1st: prune execution time:1427 ms
2nd: check core first-phase bsp time:13011 ms
2nd: check core second-phase bsp time:2002 ms
3rd: core clustering time:3377 ms
4th: non-core clustering time:2469 ms
with google perf end--------------
PROFILE: interrupts/evictions/bytes = 13010/2314/223248
Total time without IO:22290 ms
Total output cost:16729 ms
```

### Cluster: gpu-23

sequential

```zsh
int size:4
n:118142143, m:1050026736
read degree file time:469 ms
read adjacency list file time:38215 ms
check input graph file time:2177 ms

Total input cost:42694 ms
1st: prune execution time:7448 ms
2nd: check core first-phase bsp time:67899 ms
2nd: check core second-phase bsp time:12014 ms
3rd: core clustering time:3403 ms
4th: non-core clustering time:2755 ms

prune0 definitely not reachable:203886616
prune1 definitely reachable:46119741
intersection times:275007011
cmp0:2061408067
cmp1:15685059958
equal cmp:6698684510
max portion:20398
Total time without IO:93521 ms
Total output cost:65509 ms
```

parallel

```zsh
int size:4
n:118142143, m:1050026736
read degree file time:1073 ms
read adjacency list file time:41282 ms
check input graph file time:2166 ms

Total input cost:46372 ms
1st: prune execution time:681 ms
2nd: check core first-phase bsp time:4594 ms
2nd: check core second-phase bsp time:1008 ms
3rd: core clustering time:4341 ms
4th: non-core clustering time:2763 ms
Total time without IO:13388 ms
Total output cost:65331 ms
```

## Uk

### Desktop

pscan

```zsh

```

### Cluster: gpu-23