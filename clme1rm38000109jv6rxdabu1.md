---
title: "Debunking McKinsey's Software Engineering Productivity Metrics: A Technical Perspective"
seoTitle: "Why McKinsey's Software Engineering Productivity Metrics Don't Align w"
seoDescription: "Explore why McKinsey's software engineering productivity metrics are too simplistic and risk undermining the collaborative ethos of DevOps. Learn about more"
datePublished: Sun Sep 10 2023 22:49:11 GMT+0000 (Coordinated Universal Time)
cuid: clme1rm38000109jv6rxdabu1
slug: debunking-mckinseys-software-engineering-productivity-metrics-a-technical-perspective
cover: https://cdn.hashnode.com/res/hashnode/image/stock/unsplash/AFVwA960LUc/upload/cb43be7ffcb40acc37e001b8822e7488.jpeg
tags: devops, sdlc, engineering-management, dorametrics

---

# Debunking McKinsey's Software Engineering Productivity Metrics: A Technical Perspective

## TL;DR;

McKinsey's software engineering productivity metrics are overly simplistic and misaligned with DevOps principles. They focus too much on individual output, neglecting the complexities and collaborative nature of software engineering. Metrics like DORA's are more effective as they emphasize team outcomes and align with DevOps practices. Adopting McKinsey's approach could lead to reduced collaboration and a focus on gaming the system rather than actual productivity.

## What's this about?

McKinsey has recently [published an article](https://www.mckinsey.com/industries/technology-media-and-telecommunications/our-insights/yes-you-can-measure-software-developer-productivity) on measuring software developer productivity. While some points are agreeable, the core recommendations severely miss the mark, often offering a dangerously simplistic view of productivity metrics. here, I'm sharing my view based on my experience on why McKinsey's recommendations are flawed, particularly from a DevOps and technical management perspective.

![](https://junkyardwisdom.com/wp-content/uploads/2020/07/not-sure-if-dangerously-stupid-or-a-thought-leader.jpg)

## The Wrong Premises

### Table 1: McKinsey's Questionable Assumptions

| Assumption | Critique |
|------------|----------|
| Sales metrics are better than software metrics | Just as measuring sales solely by revenue can be misleading, software productivity isn't just lines of code. |
| Individual productivity matters most | This negates the complexity of software engineering, which is a team effort.|
| Generic metrics can effectively measure productivity | Context matters; what works for one team might not work for another. |

## DORA Metrics vs. McKinsey's Proposal

### Table 2: Comparing Validity of Metrics

| Metrics | Validity | Reasoning |
|---------|----------|-----------|
| [DORA Metrics](https://cloud.google.com/blog/products/devops-sre/using-the-four-keys-to-measure-your-devops-performance) | High | Backed by empirical evidence, focuses on outcomes like deploy frequency, lead time, MTTR, and change failure rate. |
| McKinsey Metrics | Low | Artificially aligned, contextually shallow, and includes individual metrics that are easily gamable. |

![](https://storage.googleapis.com/gweb-cloudblog-publish/original_images/Calculating_the_metrics_frOhcbp.jpg)
Dora metrics - Image by Google

### DORA Metrics and DevOps

DORA metrics align well with [DevOps principles](https://www.atlassian.com/devops/what-is-devops):

![](https://wac-cdn.atlassian.com/dam/jcr:ef9fe684-c6dc-4ba0-a636-4ef7bcfa11f1/New%20DevOps%20Loop%20image.png?cdnVersion=1198)
DevOps Loop - Image by Atlassian

- **Fast feedback loops:** Lead time and deploy frequency give insight into how quickly a team can go from idea to production.
- **Reduced risk:** MTTR (Mean Time to Recover) and change failure rate metrics correlate with system robustness.

## The Problem with Individual Metrics

McKinsey suggests metrics like "velocity index benchmark," "contribution analysis," and "talent capability scores," among others. From a DevOps standpoint, these are counterproductive for several reasons:

- **Reduced Collaboration:** Teams may opt for quick fixes over important tasks like pipeline optimization, which has a long-term impact on productivity.
- **Learned Helplessness:** Engineers become oriented around "gaming the system" rather than focusing on value-added work.
  
## How to Truly Measure Productivity

### Culture and Process Over Individuals

Trust and good organizational practices often have a more significant impact on team success than individual brilliance.

### Real-World DevOps Measures

1. **Pipeline Efficiency:** Time taken from code check-in to deployment.
2. **Rollback Rates:** Frequency of rollbacks as an indicator of code quality.
3. **Incident Metrics:** Time to acknowledge and resolve incidents.

### Benefits of Using DORA Metrics

- **Decision-making Efficiency**: 
  - Focuses on key metrics, filtering out noise.
  - Aids in prioritizing impactful changes.
  
- **Value Delivery**:
  - Directly correlates with product quality.
  - Identifies bottlenecks for targeted improvement.

- **Continuous Improvement**:
  - Serves as a performance baseline.
  - Highlights actionable areas for agile and lean practices.

## Conclusion

I believe that McKinsey's proposals are not only failing to capture what makes a software engineering team productive but can be damaging if misapplied. The research that has been done behind the book [Accelerate](https://www.amazon.co.uk/Accelerate-Software-Performing-Technology-Organizations/dp/1942788339) and the evolution that DevOps has brought us are all telling us that is less about numerical metrics and more about cultivating a culture where smart practices, continual learning, and team collaboration are the yardsticks of success.