# Investment-Support

■出力内容の解説
1.最適パラメータの出力
　内容：各ティッカーについて、ベイズ最適化により見つけた最適なパラメータが表示されます。
　例：Best parameters for 6758.T: {'bb_period': 50, 'long_window': 176, 'rsi_period': 50, 'short_window': 50}
　詳細：
　・bb_period：ボリンジャーバンドの計算に使用する期間
　・long_window：長期移動平均の期間
　・rsi_period：RSIの計算に使用する期間
　・short_window：短期移動平均の期間
　・これらのパラメータが最適化されることで、投資戦略のパフォーマンスが最大化されます。

2.最適化されたシャープレシオの出力
　内容：最適化されたパラメータで計算されたシャープレシオが表示されます。
　例：Best Sharpe ratio for 6758.T: 0.6398
　詳細：
　・シャープレシオは、リスク調整後のリターンを測定する指標です。
　・高いシャープレシオは、高リターンを低リスクで達成していることを示します。

3.最終ポートフォリオ価値の出力
　内容：バックテストの終了時点でのポートフォリオの価値が表示されます。
　例：Final Portfolio Value for 6758.T with Optimized Parameters: $324464.38
　詳細：
　・バックテスト期間の終わりにおけるポートフォリオの価値を示します。これにより、投資戦略の実績を評価できます。

4.年率換算シャープレシオの出力
　内容：最適化されたパラメータで計算された年率換算のシャープレシオが表示されます。
　例：Annualized Sharpe Ratio for 6758.T: 0.6398
　詳細：
　・シャープレシオを年率換算した値です。
　・年間を通じてのリスク調整後のリターンを評価するために使用されます。
 
5.最大ドローダウンの出力
　内容：バックテスト期間中の最大ドローダウン（損失の最大値）が表示されます。
　例：Maximum Drawdown for 6758.T: $-113576.30
　詳細：
　・ドローダウンはポートフォリオが過去のピークからどれだけ減少したかを示します。
　・最大ドローダウンは、投資戦略のリスクを評価するための重要な指標です。
　・ドローダウンの値が小さいほど、投資戦略が安定していることを示します。

■グラフの読み方
1.Portfolio Value Over Time
　・横軸（X軸）：時間（日付）
　・縦軸（Y軸）：ポートフォリオの価値
【解釈】
・このグラフはバックテスト期間中のポートフォリオの価値の推移を示しています。 ポートフォリオがどのように成長または減少したかを視覚的に確認できます。
・ポートフォリオが順調に成長している場合は、グラフは右肩上がりになります。
・一方、ポートフォリオが損失を被っている場合は、グラフは左肩下がりになります。
・グラフの傾斜が急であれば、ポートフォリオの価値が短期間で大きく変化したことを示します。
・グラフの曲線に波形が見られる場合は、ポートフォリオの価値が変動しながら推移したことを示します。

2.Drawdown Over Time
　・横軸（X軸）：時間（日付）
　・縦軸（Y軸）：ドローダウンの値
【解釈】
・このグラフはバックテスト期間中のドローダウン（損失）の推移を示しています。 ドローダウンが大きくなる時期や、最大の損失が発生した時期を視覚的に確認できます。
・ドローダウンが大きくなる時期は、ポートフォリオが大きな損失を被った時期であることを示します。
・グラフの曲線に谷が見られる場合は、ポートフォリオが大きな損失を被った時期であることを示します。
・ドローダウンの値が小さいほど、ポートフォリオのリスクが低いことを示します。
・最大ドローダウン（最大の谷の深さ）は、ポートフォリオがどれだけの損失を経験したかを示し、投資戦略のリスクを評価するために重要な指標となります。
