# 6. Measuring and Governing Architecture Characteristics

Author:
  - [gkz](https://twitter.com/gkzvoice)

See the following, if you want to see the memos of other chapters.
  - [fundamentals-of-software-architecture.md](../fundamentals-of-software-architecture.md)


## 6-1. Overview

This chaptesr says as follows:

- some of the more common architecture characteristics and building governance mechanisms for them.


## 6-3. Notes.

`They aren’t physics`
- Is the following my understaing true?
 - Does the fact that the design features of a system vary with context mean that nothing is as clear-cut as the discrimination of things?
  - It depends on the scene

`Too composite`
- The whole system we are developing is exactly this. Such as a method that returns a response to a request for some administration screens.

`Operational Measures`
- Do you use in-house or SaaS to detect outliers?
  - In the case I'm working on, I'm only notified when the threshold is exceeded, and I don't think there was any outlier detection.
    - Depending on the scene, you can take the average or the maximum value. It also depends on whether you have one car as a maximum value or 10 cars running.

`That guidance mechanism is called `a fitness function`: an object function used to assess how close the output comes to achieving the aim.`
 - The fitness function was not well differentiated from the test code, so I looked it up.
   - [読書メモの見返し(進化的アーキテクチャ第2章 適応度関数)](https://note.com/ryoma_0923/n/na019812888e9)より
     > 適応度関数を用いて定量・定性的な判断を行えるようにすることで`システムの非機能的な観点でのコミュニケーションの円滑化などを図る`

`commingle`
- verb
- meaning: mix; blend.
  - e.g.: "the part of the brain where the senses commingle"

`sterr`
- verb
- meaning: guide or control the movement of (a vehicle, vessel, or aircraft), for example by turning a wheel or operating a rudder.
  - e.g.: "he steered the boat slowly towards the busy quay"
  - Syn:guide, direct, manoeuvre, navigate, pilot, drive


- [TSLintでTypeScriptの循環的複雑度(cyclomatic-complexity)を検証する](https://qiita.com/shisama/items/8d5ace30a1111fdb4a1c)

- [適合度関数によってアーキテクチャの目標満足性を検証する](https://www.infoq.com/jp/news/2019/04/fitness-functions-architecture/)
