# 14. Event-Driven Architecture Style

Author:
  - [gkz](https://twitter.com/gkzvoice)

See the following, if you want to see the memos of other chapters.
  - [fundamentals-of-software-architecture.md](../fundamentals-of-software-architecture.md)


## 14-1. Overview

This chaptes says as follows:
 - `Event-Driven Architecture Style`

## 14-2. Notes
- Pros of Broker
  - ![](https://i.imgur.com/R4KsdLD.png =400x)
    - Sources: [Architectural Patterns For IoT — Event Driven Architectures by prashun javeri](https://link.medium.com/9bqmn54A9bb)
    - **`Highly decoupled event processors`**
    - High scalability
    - High responsiveness
    - High performance
    - High fault tolerance 
  - Pros of Mediator
    - ![](https://i.imgur.com/hS8p6yU.png =400x)
      Sources: [同上](https://link.medium.com/9bqmn54A9bb) 
    - Workflow control
    - **`Error handling`**
    - Recoverability
    - Restart capabilities
    - Better data consistency

- My opinion is as folows:
  - Use Broker for a decoupled design, or use Mediator for a error handling.
  - Q. AWS SQS/Step Functions incorporating Broker/Mediator functionality? Do we need to think about how to incorporate it?
    - That's not true; you need to think about it even if you use AWS services.
    - ![](https://i.imgur.com/WImxNbQ.png)
      - Sources: [AWS Black Belt Online Seminar](https://d1.awsstatic.com/webinars/jp/pdf/services/20200610_AWS_BlackBelt_Building_Event_driven_Architectures_on_AWS.pdf)
