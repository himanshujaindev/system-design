# System-Design
Code and Concepts of System Design


https://www.geeksforgeeks.org/system-design-tutorial/

## HLD
1. Define Functional and Non Functional Requirements
2. Functional: Define the features/functionality of the app
3. Non Functional: Define Availability, Scalability, Latency, Consistency, Load

## LLP
1. Design Patterns
2. Unit test, Integration test, System test
3. OOP
4. DSA Patterns


### Design Patterns
CSB - Creational, Structural and Behavioural
https://refactoring.guru/design-patterns


### SOLID Principles
https://www.geeksforgeeks.org/solid-principle-in-programming-understand-with-real-life-examples/



#### Amazon Principles
1. Learn and Be Curious
Leaders are never done learning and always seek to improve themselves. They are curious about new possibilities and act to explore them.

> Rreviews of new service like service mesh, kafka, argocd, elasticsearch
> Invloved in upgrades -> what is the new paramerter in this version, etc


2. Dive Deep
Leaders operate at all levels, stay connected to the details, audit frequently, and are sceptical when metrics and anecdotes differ. No task is beneath them.

> When migrating from Spinnaker to Argocd, we had to check most of the configuration and tune them for scability and reliability
> There were 150 + microservices, we consolidated all the helm manifest into one master tempate. This requires in deep understanding on how every app is deployed

4. Customer Obsession
Leaders start with the customer and work backwards. They work vigorously to earn and keep customer trust. Although leaders pay attention to competitors, they obsess over their customers.

> During the upgrade, no downtime is expected. We go with the design such that fault tolration is built in and traffic can be switched to overcome downtime, so that no customer gets impacted

6. Deliver Results
Leaders focus on the key inputs for their business and deliver them with the right quality and in a timely manner. Despite setbacks, they rise to the occasion and never settle.

> Getting the right requirements for a project is crucial. Avoid Over-engineering. Deliver feature that are business critical and helps solve the problem. GuardDuty to secure the environment 

7. Ownership
Leaders are owners. They think long term and do not sacrifice long-term value for short-term results. They act on behalf of the entire company, beyond just their own team. They never say, “that’s not my job.”

> Complete end-to-end task. Starting from poc to production. Documentation. Testing.

9. Insist on the Highest Standards
Leaders have relentlessly high standards—many people may think these standards are unreasonably high. Leaders are continually raising the bar and driving their teams to deliver high-quality products, services, and processes. Leaders ensure that defects do not get sent down the line and that problems are resolved so they remain fixed.

> Automating every small detail to avoid any human intervention
