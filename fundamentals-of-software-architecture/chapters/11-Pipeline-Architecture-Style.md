# 11. Pipeline Architecture Style

Author:
  - [gkz](https://twitter.com/gkzvoice)

See the following, if you want to see the memos of other chapters.
  - [fundamentals-of-software-architecture.md](../fundamentals-of-software-architecture.md)


## 11-1. Overview

This chaptes says as follows:
 - `pipeline architecture style`

## 11-2. Notes

- Pipes
  - Be form the communication channel between filters. 
  - Each pipe is typically unidirectional and point-to-point (rather than broadcast)

- Filters
  - Be self-contained, independent from other filters, and generally stateless. 
  - Should perform one task only. 
      - Producer, Transformer, Tester, Consumer
  - cf.[データパイプラインに関する知見をカジュアルに語る！ Data Pipeline Casual Talkに参加してきた #DPCT](https://dev.classmethod.jp/articles/report-data-pipeline-casual-talk-vol-1/)
      - > 『最初にかっちり決めて作るのはほぼ不可能』。環境や条件は変わることを前提にして、むしろ『進化させていく』ように作っていくべき。イコール『データ基盤を"育てる"』。
      - > Airflow導入で苦労したこと：バージョンアップが結構面倒、ExecutionDateと実際の実行時刻がずれる、ジョブのスケジュール管理が全て解決した訳ではない
  - cf. [Airflow のアーキテクチャをざっくり理解して、どうやって使うのか学んでみた](https://dev.classmethod.jp/articles/airflow-gs-arch-learn/)
      - > Airflowは、 管理画面表示部の Webserver と、Job実行のスケジュール管理部の Scheduler 、Job実行部の Worker(Executer) 

- Reviw of `the pipeline architecture`(More ☆, More reviws)
  - ![](https://i.imgur.com/VnhUYBe.png =300x)

