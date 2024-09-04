# TSP-Competition
TSP挑战赛的Artist部分
将给定的图片转化为TSPLIB格式数据集，要求采用TSP算法将图片对应点连线，基于数据集找出性能最高的求解TSP精确解的SOTA方法。
对比Neighbor, nearest insertion, farest insertion, Christofides,  2-opt以及LKH六种算法，考虑顶点规模和GAP误差等指标，最终选择LKH算法并结合模拟退火算法来进行生成。
