# 9. Foundations

Author:
  - [gkz](https://twitter.com/gkzvoice)

See the following, if you want to see the memos of other chapters.
  - [fundamentals-of-software-architecture.md](../fundamentals-of-software-architecture.md)


## 9-1. Overview

This chaptes says as follows:
 - `Fundamental Patterns`

## 9-2. Notes

- `Big Ball of Mud`
  > A big ball of mud is a software system that lacks a perceivable architecture. Although undesirable from a software engineering point of view, such systems are common in practice due to business pressures, developer turnover and code entropy. They are a type of design anti-pattern.
[wiki](https://en.wikipedia.org/wiki/Big_ball_of_mud)

- `the absence of any discernible architecture structure`
  - `discernible` (adj)
    - meaning: able to be discerned; perceptible.
      - e.g.: "the scandal had no discernible effect on his career"

- `Unitary Architecture`
  - > Generally, software systems tend to grow in functionality over time, `requiring separation of concerns to maintain operational architecture characteristics`, such as performance and scale.
    - `unitary` (adj)
       - meaning: forming a single or uniform entity.
         - e.g.: "a sort of unitary wholeness"

- `the fallacies of distributed computing`
  - > `A fallacy is something that is believed or assumed to be true but is not`. All eight of the fallacies of distributed computing apply to distributed architectures today.

- How to solve `Stamp coupling`
  - > Create private RESTful API endpoints, Use field selectors in the contract, Use GraphQL to decouple contracts, Use value-driven contracts with consumer-driven contracts (CDCs), Use internal messaging endpoints 
    - cf. [設計におけるオブジェクトの責務分配に有効なものさし -凝集度と結合度-](https://www.ogis-ri.co.jp/otc/hiroba/technical/Cohesion_Coupling/Cohesion_Coupling.html)
      - > 結合度は、望ましいものから順に、以下のように分類されます。
      - > 1.非直接結合, 2.データ結合, `3.スタンプ結合(Stamp coupling)`, 4.制御結合, 5.外部結合, 6.共通結合, 7.内容結合
