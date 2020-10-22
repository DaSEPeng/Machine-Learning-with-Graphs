## Understanding Graph Neural Networks via Trajectory Analysis
SUMMARY：
- 总结了GNN的两种drawback：表达能力差，由于过平滑问题难以deep；
- 通过求导分析参数变化对结点表示的影响得出了几点结论：
  - GNN的训练相当于两步：构建相似度矩阵+基于相似度矩阵进行标签更新；
  - 标签更新有潜在的问题：预测过好的点对周围点的影响变小；
  - GNN迅速收敛加剧了这个问题；
  - 有更多的分析值得进行；
  
ANNOTATED PAPER: [PDF](TrajectoryAnalysis.pdf)
