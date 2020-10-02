# 1. The Intersection of Security and Reliability

Author:
  - [gkz](https://twitter.com/gkzvoice)

See the following, if you want to see the memos of other chapters.
  - [building-secure-and-reliable-systems.md](../building-secure-and-reliable-systems.md)


## 1-1. Overview


## 1-2. what this chapter reminded me

> では、なぜSREがセキュリティに貢献しているのか。その背景にあるのが信頼性とセキュリティの共通点だ。
>
>　SREは取り組みの中で、レイテンシやスループット、可用性などのSLI（Service Level Indicator：サービスレベルインジケーター）を利用してSLO（Service Level Objective：サービスレベル目標）という数値を設定する。
>
>　例えば、SLOとして99.95％の可用性を設定したサービスの場合、30日間で許容される停止時間は21.9分になる。この時間はエラーバジェット（Error Budget：エラー予算）という指標として管理され、サービス停止に応じて「エラーバジェットをどれくらい消費したか」を判断する。

Source: [ミクシィのSREがセキュリティに貢献する理由](https://www.atmarkit.co.jp/ait/articles/2004/07/news002.html)


## 1-3. Notes

`Cascading failure`
  - noun
  - meaning: A cascading failure is a process in a system of interconnected parts in which the failure of one or few parts can trigger the failure of other parts and so on. Such a failure may happen in many types of systems, including power transmission, computer networking, finance,
  - sources: [wiki/Cascading_failure](https://en.wikipedia.org/wiki/Cascading_failure)

`malicious`
  - adj
  - meaning: characterized by malice; intending or intended to do harm.
    - e.g.: "he was found guilty of malicious damage"
    - Syn: spiteful, malevolent, hostile, bitter, venomous, poisonous

`vulnerability`
  - noun
  - meaning: the quality or state of being exposed to the possibility of being attacked or harmed, either physically or emotionally.
    - e.g.: "conservation authorities have realized the vulnerability of the local population" 

`Faile-safe`
 - meaning: In engineering, a fail-safe is a design feature or practice that in the event of a specific type 
  of failure, inherently responds in a way that will cause minimal or no harm to other equipment, to the environment or to people. 
  `Unlike inherent safety to a particular hazard, a system being "fail-safe" does not mean that failure is impossible or improbable, but rather that the system's design prevents or mitigates unsafe consequences of the system's failure.` 
  That is, if and when a "fail-safe" system fails, it remains at least as safe as it was before the failure.[1][2] Since many types of failure are possible, failure mode and effects analysis is used to examine failure situations and recommend safety design and procedures.
  `Some systems can never be made fail-safe, as continuous availability is needed. Redundancy, fault tolerance, or contingency plans are used for these situations` (e.g. multiple independently controlled and fuel-fed engines).
- sources: [wiki/Fail-safe](https://en.wikipedia.org/wiki/Fail-safe)

`redundancy`
 - noun
 - meaning: the state of being not or no longer needed or useful.
    - e.g.: "the redundancy of 19th-century heavy plant machinery"


## References

- [Building Secure and Reliable Systems 読書メモ - Chapter 1 & 2](https://muziyoshiz.hatenablog.com/entry/2020/04/30/014824)