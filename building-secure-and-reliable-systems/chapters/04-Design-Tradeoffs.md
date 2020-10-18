# 4. Design Tradeoffs

Author:
  - [gkz](https://twitter.com/gkzvoice)

See the following, if you want to see the memos of other chapters.
  - [building-secure-and-reliable-systems.md](../building-secure-and-reliable-systems.md)


## 4-1. Overview

This chapter shows us the follwos:

- The connection between system constraints and product features, then provide two examples —a payment processing service and a microservices framework— that demonstrate some common security and reliability tradeoffs
  - The natural tendency to defer security and reliability work
  - How early investment in security and reliability can lead to sustained project velocity

- Feature Requirements
  - also known as functional requirements

- Nonfunctional Requirements
  - system constraints, especially, security and reliability

## 4-1-1. My opinion

- The following is natural:
  - Development efficiency and velocity and Deployment velocity are lost 
    when there is a double burden of functional and non-functional requirements


## 4-2. Notes

`defer`
  - verb
  - meaning: put off (an action or event) to a later time; postpone.
    - e.g.: "they deferred the decision until February"
    - Syn.: postpone, put off, adjourn, delay, hold over/off, put back

`Developer Velocity`
 > Improving business performance through software development comes down to empowering developers, 
 > creating the right environment for them to innovate, and removing points of friction. 
 > Industry leaders refer to this capability as `“Developer Velocity.”` 
 > This goes beyond the definition of velocity as it relates to agile methodologies—meaning 
 > it is about not just speed but also unleashing the full potential of development talent.

 Source: [How software developers can drive business growth | McKinsey](https://www.mckinsey.com/industries/technology-media-and-telecommunications/our-insights/developer-velocity-how-software-excellence-fuels-business-performance#)