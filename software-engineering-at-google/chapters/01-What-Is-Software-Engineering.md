# 1. What Is Software Engineering?

Author:
  - [gkz](https://twitter.com/gkzvoice)

See the following, if you want to see the memos of other chapters.
  - [software-engineering-at-google.md](../software-engineering-at-google.md)

## 1-1. Overview
- `The book explains what software engineering is like by comparing programming`

### 1-1-1. What is the differences between software engineering and programming?

### 1-1-2. One of the differences is `time`

> “Software engineering is programming integrated over time.”


- programming
  - focused on development only
    > how you generate new software in the first place.
- software engineering
  - focused on `not only development, but also modification, maintenance`

### 1-1-3. Another difference is `scale`

- programming
  - individually

- software engineering
  - collaboratively
    - issues increases around communication 

### 1-1-4. Third difference is `complexity in decision making`

My opinion:
```
A difficulty on software engineering is you are forced to make decision which to choose under limited conditions and with little information. 
Moreover the choices's relationship is trade-off.
```

## 1-2. What I've been thinking

My opinion:
- One of the difficulty in software engineering for me is as follows.

  - It's where you're forced to make software enginerring improvements to non-software engineering problems.

- But isn't this situation changing?

- I've read cases of non-software engineer marketers using SQL commands to solve problems, which may be a fundamental shift in my thinking. 

  - [広報だけどSQLの勉強はじめました！ データ分析は職種を超えて必要になっている](https://webtan.impress.co.jp/e/2020/03/24/35524)

- If software engineering approaches will be using in every problem-solving situation as described in the following article, I will have to think twice to apply it.

  - [Why Software Is Eating the World](https://a16z.com/2011/08/20/why-software-is-eating-the-world/)



In Japanese:
- ソフトウェアエンジニアリングの難しさは、非ソフトウェアエンジニアリング的な問題をソフトウェアエンジニアリング的に解決するところ。

- しかし、この状況は変わってきているのではないか？

- たとえば、マーケティング担当者がSQLコマンドを使っているケースがあったり。

- こういった、非ソフトウェアエンジニアリング的な問題をソフトウェアエンジニアリング的に解決するケースが
  あらゆる場面でみられていくとなると、僕の考えは見直さなちゃいけないはず。

## 1-3. Notes

- `higher stakes`
  > The word "stakes", in this case, refers to something that is at risk of being lost.

  sources: [What does "the stakes are high" mean?](https://www.reddit.com/r/EnglishLearning/comments/94w009/what_does_the_stakes_are_high_mean/)

- `implicit`
  - adj
  - meaning: suggested though not directly expressed.
    - e.g.: "comments seen as implicit criticism of the policies"
    - Syn: implied, indirect, inferred, understood, hinted, ted materials

- `explicit`
  - adj
  - meaning: stated clearly and in detail, leaving no room for confusion or doubt.
    - e.g.: "the arrangement had not been made explicit"
    - Syn: clear, direct, plain, obvious, straightforward, clear-cut

- `distinction`
  - noun
  - meaning: a difference or contrast between similar things or people.
    - e.g: "there is a sharp distinction between domestic politics and international politics"
    - Syn.: difference, contrast, dissimilarity, dissimilitude, divergence
  
  - meaning: excellence that sets someone or something apart from others.
    - e.g.: "a novelist of distinction"
    - Syn.: importance, significance, note, consequence, account, renown

- `dependency`
  - noun
  - meaning: dependence
    - e.g: "the country's dependency on the oil industry"
    - Syn.: dependence, reliance


## 1-4. The related materials

- The following is an example of using software to solve the non-software engineering problem of measuring team activity.

  -  [開発チームの生産性・健全性を客観的に知るためにリポジトリ履歴から機械的に可視化するツールを作った](https://qiita.com/hirokidaichi/items/ceece347f808cc9d14dd)


## 1-5. A summary of #event_20200809 on discord

- GoogleのSoftware Engineeringの考え方
  > Our point is not that software engineering is superior, merely that these represent two different problem domains with distinct constraints, values, and best practices. Rather, the value in pointing out this difference comes from recognizing that some tools are great in one domain but not in the other.
  >
  > Programming is the immediate act of producing code. Software engineering is the set of policies, practices, and tools that are necessary to make that code useful for as long as it needs to be used and allowing collaboration across a team.
- 仕様に依存した処理を書いてしまうあるある話
- 企業とOSSとの関係性
- Beyoncéの歌詞

![discord-20200809](https://user-images.githubusercontent.com/38461277/92316354-ab847280-f02d-11ea-9fd3-d6bbec8552cb.png)

