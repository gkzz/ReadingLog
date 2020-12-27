# 17. Microservices Architecture 

Author:
  - [gkz](https://twitter.com/gkzvoice)

See the following, if you want to see the memos of other chapters.
  - [fundamentals-of-software-architecture.md](../fundamentals-of-software-architecture.md)


## 17-1. Overview

This chaptes says as follows:
 - `Microservices Architecture`

## 17-2. Notes

- Microservice is influenced by many architectural ideas.
  - > One concept in particular from DDD, bounded context, decidedly inspired microservices. The concept of bounded context represents a decoupling style.
  - cf. [どうやってBounded Contextを見つけるか](https://qiita.com/suin/items/49545ba8ca041a41b5d3)
    - > 組織といったコミュニケーション構造に従ってSub Domainを模索することはBounded Contextを設計するための近道


- monolithic v.s. microservice
  - | monolithic  | microservice  |
    |-------------|---------------|
    |             |bounded context(Resources are shared only within the context, not outside of it.)
    |coupling     |decoupling     |
    |reusable     |non-reusable   |
    |> some resource becomes constrained on the shared infrastructure??	|  |
    |             |> Each service is meant to represent a domain or subdomain |
  
  - > with cloud resources and container technology, teams can reap the benefits of extreme decoupling, both at the domain and operational level.

  - synchronous or asynchronous communication
    - synchronous communication
      - protocol aware heterogeneous interoperability
    - asynchronous communication
      - messages

- Q. Is every single service in microservices monolithic?
  - "Monolithic" rather than microservices components
