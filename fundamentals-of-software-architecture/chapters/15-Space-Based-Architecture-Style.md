# 15. Space-Based Architecture Style

Author:
  - [gkz](https://twitter.com/gkzvoice)

See the following, if you want to see the memos of other chapters.
  - [fundamentals-of-software-architecture.md](../fundamentals-of-software-architecture.md)


## 15-1. Overview

This chaptes says as follows:
 - `Space-Based Architecture Style`

## 15-2. Notes
- As a prerequisite, review the flow of requests received by each server
- Explain the background to the need for space-based architecture
- If there is some high user load (more requests?) If so, just scale out the web server
- For higher user loads, the bottleneck will not be resolved
- The application server/database server behind it becomes a bottleneck
- It's hard to scale out the database, so you have to use caching and database products, but it's still hard to deal with the general application load.

- address the problems ≒  solve problems
  - cf. [address the problems / synonyms](https://www.powerthesaurus.org/address_the_problems/synonyms)

- > Space-based architecture gets its name from the concept of tuple space , the technique of using multiple parallel processors communicating through shared memory.
  - cf. [Linda - Wikipedia](https://ja.wikipedia.org/wiki/Linda)
    - > Linda はこれらとは異なるアプローチであり、既存の言語仕様に修正を加えずに協調モデル（coordination model）を付加することで並列処理を実現する。このため Linda は「協調言語（coordination language）」とも呼ばれ、並列性のない言語で書かれたアプリケーション間の協調動作にのみ注目している。Linda のモデルでは、タプルスペース（tuplespace）と呼ばれる概念上の共有メモリ上で型つきのデータレコード（タプル）をそこに格納する。

- Q. What is `a remote call`?
  - > Remote procedure calls used in modern operating systems trace their roots back to the RC 4000 multiprogramming system,[2] which used a request-response communication protocol for process synchronization.
    - [Remote procedure call - Wikipedia](https://en.wikipedia.org/wiki/Remote_procedure_call)

- Q. What does UR^2 of Collision Rate mean?

- > how many requests arrive during the processing of a request by the application

