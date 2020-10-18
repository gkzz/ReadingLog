# 5. Design for Least Privilege

Author:
  - [gkz](https://twitter.com/gkzvoice)

See the following, if you want to see the memos of other chapters.
  - [building-secure-and-reliable-systems.md](../building-secure-and-reliable-systems.md)


## 5-1. Overview

This chapter shows us the follwos:

-  How to classify access based on risk and examine best practices that enforce least privilege

- Common concepts in IT industry and at Google
  - Least Privilege
  - Zero Trust Networking, for example, Google Tool Proxy
  - Zero Touch

- Best practices
  - Small Functional APIs
  - Breakglass
  - Auditing

## 5-1-1. My opinion

- The following is natural:
  - Development efficiency and velocity and Deployment velocity are lost 
    when there is a double burden of functional and non-functional requirements


## 5-2. what this chapter reminded me

> 1つ1つのサービスにはそれぞれの責務の範囲が明確にあり、ユーザーはそれらをビルディング・ブロックとして組み合わせることでシステムを作っていく. 各 AWS サービスはそれぞれの API を呼ぶ形で疎結合に組み合わせることができ、一部のブロックを他のブロックに、例えば ECS から Lambda に置き換えられる. この思想と哲学が、AWS が幅広いユースケースをカバーすることを可能にし、ユーザーが AWS 上で持続可能なシステム構築と運用を行うことを可能にしていると言えます.
(少し話は逸れますが、AWS を使うユーザーが感じることがあると思われる、いわゆるマイクロサービスならではのツラみのようなものも、この思想と哲学によって副作用的に発生していると考えます)

Sources: [プラットフォームの上でものを作るということ | トリの部屋](https://toris.io/2019/12/what-i-think-about-when-i-think-about-kubernetes-and-ecs/)

>  マイクロサービスにおいて横断的な関心事に対処するときは、常に標準の規格を意識することが大切です。そして、社内向けのライブラリを作るときは、その標準の規格に乗った形で実装するのがポイントです。
> 上の設計だと、あるユーザを認可するには認可タグをつける必要があり、そのためには必ずユーザテーブルにレコードを作成 (略) しかし、まれに「ADアカウントさえ持っていれば、何の認可も不要で一定レベルまでは利用できるようにしたい」という要求がありました。これを Authenticated Guest と呼ぶ

Sources: [マイクロサービスで管理画面が乱立する問題と対策](https://medium.com/finc-engineering/microservices-admin-tools-7b8f6c73b14a)
