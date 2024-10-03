---
layout: post
title: Harnessing Test-Driven Development, Where Design Leads!
description: >
  Ever experienced the “Fragile Test Problem”? It often happens to TDD newcomers or those chasing that elusive 100% test coverage.
categories: [tech]
tags:       [TDD, Testing, CodeQuality, Design]
sitemap: false
image: /assets/tech/HarnessingTDDWhereDesignLeads/label.jpg
comments: false
---
0. this unordered seed list will be replaced by toc as unordered list
{:toc}


Ever experienced the **“Fragile Test Problem”**? It often happens to TDD newcomers or those chasing that elusive 100% test coverage. The moment you make a code change, **Bam !!!** Everything starts breaking — thousands of things, including tests. It’s like a  domino effect of chaos and frustration. `STAY STRONG , MY FRIEND!`

In [last blog](2022-01-12-What%E2%80%99s%20my%20First%20Test%20in%20TDD.md) we discussed about the mindset one need to have before writing the test and See them as Requirement Document.

**You know why it failed ?** We didn’t prioritize design when writing those tests. **The fix ?** We gotta isolate and reduce dependencies between tests, but let’s be real — `IT'S EASIER SAID THAN DONE !` The key is to kick off with a strong design right from the start.

You know what’s a common problem? Forgetting the purpose of what we’re trying to achieve and getting caught up in metrics. Code coverage is great, but it shouldn’t be the sole measure of code quality or a team’s performance. Remember, `low coverage can indicate bad code, but it’s not the whole picture. Conversely, high coverage doesn’t guarantee good design.` Let’s keep our focus on design, folks!


## We all know the Advantages of TDD

1. It Instills high trust in the system by providing rapid feedback, ensuring that code remains functional even after a short interval
2. With these 5 minute systems , you will be able to make sure that code worked a minutes ago. this facilitates the adoption of Trunk-based Development, leading to reduced debugging time
3. TDD enables the generation of invocable code for specific APIs, offering valuable low-level insights while promoting decoupling
4. Consequently, it contributes to the creation of a decoupled codebase
5. Moreover, TDD adds an element of fun to the process of writing unit tests and minimizes the possibility of leaving gaps in the test suite.
---

# Process

## RED
In TDD, the journey begins with writing tests. It’s like sketching the blueprint for your code. You imagine the desired outcome and express it in the form of tests. Forcing us to write Requirements in form of test as we discussed in [last blog](2022-01-12-What%E2%80%99s%20my%20First%20Test%20in%20TDD.md).

Rule

- You write the test , that you know will force you to write the code, that you know should be there as per the Design and Requirement.
- You are not allowed to write any production code, until you have written a test that fails.

## GREEN

As you move to the next step — passing the test — the real magic happens. You breathe life into your code, making it dance to the rhythm of your design. Each line of code is carefully crafted, ensuring it satisfies the test’s criteria.

### Rule

- Not Compiling is failing
- You are not allowed to write any extra production code then is sufficient to pass the currently failing test

## REFACTOR

But wait, there’s more! TDD encourages you to go beyond merely passing the test. 
It challenges you to refactor — enhancing the design while preserving functionality.

---

# Is it a Pain Point

**You know what?** Sometimes, it can feel like a real pain. But here’s the thing: **we should view it as a discipline** — a necessary one! _Just like in accounting’s double entry bookkeeping, where transactions on assets and balances must always equal zero._ It gives us a solid foundation and confidence in the whole system.

# Conclusion

So, dear developers, as you embrace Test-Driven Development, remember that it’s not just about tests — **it’s about envisioning, designing, and refining**.It fosters a symbiotic relationship between design and implementation, encouraging you to think critically and iteratively. TDD takes you on an exhilarating ride where code and design unite, creating a symphony of software craftsmanship.

_Next Blog will be coming up with Different Types of Unit tests_

