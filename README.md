# dijkstra算法简述
* 将所有节点的到起点最小距离设置成Max，起点自身为0
* 迭代
  * 找到到起点最小距离最小的点(第一次是起点)，为其相邻节点更新到起点最小距离
* 迭代完成既得最小距离 