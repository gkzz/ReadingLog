# 9. Design for Recovery 

## 9-1. Overview

This chapter says as follows:

> This chapter covers some design principles that we’ve found effective in preparing our systems to facilitate recovery efforts. Many of these principles apply across a range of scales, from planet-scale systems to firmware environments within individual machines.

## 9-2. My questions

- Shouldn't we be designing for "obstacles that rarely happen" so that "those obstacles don't happen? Do you mean it's hard because people say it is?
  > Designing systems for recovery is considered an advanced topic, whose business value is proven only when a system is out of its intended state. But, given that we recommend operating systems use an error budget to maximize cost efficiency,28 we expect such systems to be in an error state regularly.
