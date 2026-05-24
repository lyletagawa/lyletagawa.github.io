Beginning in late 2013, we embarked on a four-year research journey to investigate what capabilities and practices are important to accelerate the development and delivery
of software and, in turn, value to companies. These results are seen in their profitability, productivity, and market share. We see similarly strong effects in noncommercial
outcomes of effectiveness, efficiency, and customer satisfaction.

Our research collected over 23,000 survey responses from around the world. We heard from over 2,000 unique organizations, from small startups of under five employees to
large enterprises with over 10,000 employees. We collected data from startups and cutting-edge internet companies as well as highly regulated indus- tries, such as finance,
healthcare, and government. Our data and analysis includes software developed on brand new “greenfield” platforms as well as legacy code maintenance and development.

---

## FOCUS ON CAPABILITIES, NOT MATURITY

- maturity models focus on helping an organization “arrive” at a mature state and then declare themselves done with their journey
- maturity models quite often prescribe a similar set of technologies, tooling, or process for every set of teams and organizations
- capability models focus on key outcomes and how the capabilities drive improvement in those outcomes - that is, they are outcome based

By focusing on a capabilities paradigm, organizations can con- tinuously drive improvement.

---

Our research has yielded insights into what enables both software delivery performance and organizational performance as seen in profitability, productivity, and market share. In fact, our research shows that none of the following often-cited factors predicted performance:

- age and technology used for the application (for example, mainframe “systems of record” vs. greenfield “systems of engagement”)
- whether operations teams or development teams performed deployments
- whether a change approval board (CAB) is implemented

Our research has identified 24 key capabilities that drive improvement in software delivery performance and, in turn, organizational performance:

### CONTINUOUS DELIVERY CAPABILITIES

1. Version control
2. Deployment automation
3. Continuous integration
4. Trunk-based development
5. Test automation
6. Test data management
7. Shift left on security
8. Continuous delivery (CD)

### ARCHITECTURE CAPABILITIES

9. Loosely coupled architecture
10. Empowered teams

### PRODUCT AND PROCESS CAPABILITIES

11. Customer feedback
12. Value stream
13. Working in small batches
14. Team experimentation

### LEAN MANAGEMENT AND MONITORING CAPABILITIES

15. Change approval processes
16. Monitoring
17. Proactive notification
18. WIP limits
19. Visualizing work

### CULTURAL CAPABILITIES

20. Westrum organizational culture
21. Supporting learning
22. Collaboration among teams
23. Job satisfaction
24. Transformational leadership

---

To summarize, in 2017 we found that, when compared to low performers, the high performers have:

- 46 times more frequent code deployments
- 440 times faster lead time from commit to deploy
- 170 times faster mean time to recover from downtime
- 5 times lower change failure rate (1/5 as likely for a change to fail)

---

## THE FLAWS IN PREVIOUS ATTEMPTS TO MEASURE PERFORMANCE

There have been many attempts to measure the performance of software teams. Most of these measurements focus on productivity. In general, they suffer from two drawbacks.

- focus on outputs rather than outcomes
- focus on individual or local measures rather than team or global ones

Three examples (of flawed attempts to measure performance)

- lines of code
  - leads to bloated software that incurs higher maintenance costs and higher cost of change
  - minimizing lines of code isn’t an ideal: accomplishing a task in a single line of code that no one else can understand

- velocity: designed to be used as a capacity planning tool
  - velocity is a relative and team-dependent measure, not an absolute one
  - when velocity is used as a productivity measure, teams inevitably work to game their velocity

- utilization
  - Queue theory in math tells us that as utilization approaches 100%, lead times approach infinity - in other words, once you get to very high levels of utilization, it takes teams exponentially longer to get anything done

---

## MEASURING SOFTWARE DELIVERY PERFORMANCE

A successful measure of performance should have two key characteristics

- focus on a global outcome to ensure teams aren’t pitted against each other
  - anti-pattern: rewarding developers for throughput and operations for stability

- focus on outcomes not output
  - anti-pattern: reward people for putting in large amounts of busywork that doesn’t actually help achieve organizational goals

Four measures of Software Delivery Performance:

- Lead Time
- Deployment Frequency
- Mean Time to Restore (MTTR)
- Change Fail Percentage

The elevation of lead time as a metric is a key element of Lean theory. Lead time is the time it takes to go from a customer making a request to the request being satisfied.  However, in the context of product development, where we aim to satisfy multiple customers in ways they may not anticipate, there are two parts to lead time: the time it takes to design and validate a product or feature, and the time to deliver the feature to customers.

Shorter product delivery lead times are better since they enable faster feedback on what we are building and allow us to course correct more rapidly. Short lead times are also important when there is a defect or outage and we need to deliver a fix rapidly and with high confidence.

Reducing batch size is another central element of the Lean paradigm. Reducing batch sizes reduces cycle times and variability in flow, accelerates feedback, reduces risk and overhead, improves efficiency, increases motivation and urgency, and reduces costs and schedule growth. Deployment frequency is a proxy for batch size since it is easy to measure and typically has low variability.

Delivery lead times and deployment frequency are both mea- sures of software delivery performance _tempo_. However, we wanted to investigate whether teams who improved their performance were doing so at the expense of the stability of the systems they were working on. Traditionally, reliability is measured as time be- tween failures. However, in modern software products and services, which are rapidly changing complex systems, failure is inevitable, so the key question becomes: How quickly can service be restored?

Finally, a key metric when making changes to systems is what percentage of changes to production (including, for example, soft- ware releases and infrastructure configuration changes) fail. In the context of Lean, this is the same as percent complete and accurate for the product delivery process, and is a key quality metric.

---
