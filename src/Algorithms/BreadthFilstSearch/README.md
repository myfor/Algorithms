﻿# 广度优先搜索

和深度优先搜索不同的是，广度优先搜索不是一条道路走到黑的方式。
广度优先搜索从一点出发，记录从该点走一步能达到的所有没经过的点。
不断往外扩展，直到走遍所有的点。

和深度优先搜索相比，广度优先搜索快得多，在测试用例里对比
因为广度优先搜索不会重复经过已经经过的路径，而深度优先搜索会走遍每一条分支路径，已经经过的点也会重复走过