# 6. Design for Understandability

Author:
  - [gkz](https://twitter.com/gkzvoice)

See the following, if you want to see the memos of other chapters.
  - [building-secure-and-reliable-systems.md](../building-secure-and-reliable-systems.md)


## 6-1. Overview

This chapter shows us the follwos:

- Understandablity of systems gives us the following benefits for developers
  - Decreases security vulnerabilities or resilience failures

## 6-1-1. My opinion

- The following is natural:
  - Development efficiency and velocity and Deployment velocity are lost 
    when there is a double burden of functional and non-functional requirements

- The larger the system, the more complex each service is. 
- Modifying the specifications of one service an lead to changes in the specifications of multiple other functions, 
such as the Pythagorean switch.

## 6-2. what this chapter reminded me

>“新商品の追加を行うと、PC版でカスタマーの新規登録ができなくなる。”
>『Pairsの開発中の話』より （共著: 小島ヒロキ・森川タクマ）
Source: [Go言語での決済システムとマイクロサービス化について](https://medium.com/eureka-engineering/go%E8%A8%80%E8%AA%9E%E3%81%A7%E3%81%AE%E6%B1%BA%E6%B8%88%E3%82%B7%E3%82%B9%E3%83%86%E3%83%A0%E3%81%A8%E3%83%9E%E3%82%A4%E3%82%AF%E3%83%AD%E3%82%B5%E3%83%BC%E3%83%93%E3%82%B9%E5%8C%96%E3%81%AB%E3%81%A4%E3%81%84%E3%81%A6-d80dd4e6f684)


## 6-3. Notes

`invariant`
  - adj.
  - meaning: never changing.
    - e.g.: "the pattern of cell divisions was found to be invariant"