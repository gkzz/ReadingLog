# 10. Layered Architecture Style

Author:
  - [gkz](https://twitter.com/gkzvoice)

See the following, if you want to see the memos of other chapters.
  - [fundamentals-of-software-architecture.md](../fundamentals-of-software-architecture.md)


## 10-1. Overview

This chaptes says as follows:
 - `a layered architecture`

## 10-2. Notes

- > Each layer of the layered architecture style has a specific role and responsibility within the architecture.
  - cf.[[DDD]ドメイン駆動 + オニオンアーキテクチャ概略](https://qiita.com/little_hand_s/items/2040fba15d90b93fc124)
    - `「EricEvansのドメイン駆動」で紹介されたレイヤードアーキテクチャ`
      - > 伝統的レイヤードアーキテクチャから、Domain層のモデルに業務的な知識を持たせ、メンテナンス性を高めようとした。(中略) この設計によってモデリングのしやすいさは大幅に改善されましたが、まだ弱点があります。 Domain層がInfrastructure層に依存していること です。これはつまり、ライブラリの変更やデータベースの切り替えなどのインフラストラクチャレイヤの変更により、ビジネスロジック全体に影響が発生する可能性がある 

    - `オニオンアーキテクチャ`と`依存関係逆転の原則`
      - > ローレベルなレイヤを実装してからハイレベルなレイヤに依存させるのではなく、ハイレベルなレイヤが公開したInterfaceに基づいてローレベルレイヤが実装するのです！これにより、ハイレベルなレイヤの独立性を高めることができます。

- > The trade-off of this benefit, however, is `a lack of overall agility (the ability to respond quickly to change)`. 
  - Reviw of `the layered architecture`(More ☆, More reviws)
    - ![](https://i.imgur.com/Sawnc7F.png =200x)
