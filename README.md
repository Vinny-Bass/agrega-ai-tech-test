# Agrega AI Technical Test Instructions

## Overview

Welcome to our technical assessment! This test is designed to evaluate your ability to research, make informed decisions, and communicate your findings effectively. While implementation is a bonus, it is **not required**.

---

## Tasks

### 1. Understand the Pluggy API

- **Objective**: Familiarize yourself with the [Pluggy API](https://docs.pluggy.ai/docs/quick-pluggy-introduction).
- **Action**: Read the documentation to understand how the API works, focusing on how it handles client transactions.

### 2. Database Selection and Configuration

- **Objective**: Choose an appropriate database to store client transaction data.
- **Scenarios to Consider**:
  - **Scenario A**: Real-time data input.
  - **Scenario B**: Data received three times a day.
- **Requirements**:
  - The database should support **50,000 monthly active users**.
- **Deliverable**:
  - Present your choice and configuration in **Notion** or **Google Docs**.
  - Explain your reasoning for the chosen database and configurations for both scenarios.
- **Bonus**:
  - Implement the database using **Docker** with mock data.

### 3. API Design for Data Transformation

- **Objective**: Design an API to query and transform stored data to provide user insights (e.g., "You are spending too much on restaurants").
- **Considerations**:
  - **User Activity**: 50,000 monthly users opening the app **5 times per day on average**.
  - **Technical Decisions**:
    - Would you use **Redis** for caching?
    - Would you implement a **load balancer**?
    - Would you opt for a **microservices architecture**?
- **Deliverable**:
  - Explain your API design and the reasoning behind your technical choices in **Notion** or **Google Docs**.
- **Bonus**:
  - Implement the API using **Docker**, connecting it to your Dockerized database.

---

## Guidelines

- **Research & Learning**: It's not necessary to have prior knowledge about these topics. Demonstrate your ability to learn and research effectively.
- **Communication**: Clearly articulate your findings, decisions, and thought processes.
- **Technology Stack**:
  - You may use **any programming language** if you choose to implement the API.
  - Utilize tools and technologies you are comfortable with.

---

## Submission

- **Documentation**:
  - Provide your detailed explanations and reasoning in **Notion** or **Google Docs**.
  - Include diagrams or charts if they aid in conveying your ideas.
- **Implementation (Optional Bonus)**:
  - Share your Docker configurations and any code via a Git repository link or include them in your documentation.
  - Ensure instructions are clear for running your Docker containers.

---

## References

- **Pluggy API Documentation**: [https://docs.pluggy.ai/docs/quick-pluggy-introduction](https://docs.pluggy.ai/docs/quick-pluggy-introduction)
- **Docker Documentation**: [https://docs.docker.com/](https://docs.docker.com/)
- **Redis Documentation**: [https://redis.io/documentation](https://redis.io/documentation)
- **Microservices Concepts**: [https://microservices.io/](https://microservices.io/)
- **Load Balancing Basics**: [https://www.nginx.com/resources/glossary/load-balancing/](https://www.nginx.com/resources/glossary/load-balancing/)

---

## Evaluation Criteria

- **Research Skills**: Ability to gather and interpret relevant information.
- **Decision-Making**: Justification of choices based on scenario requirements.
- **Communication**: Clarity and effectiveness in presenting your findings.
- **Bonus Implementation**: Quality and functionality of any provided code or Docker setups.

---

## Final Notes

- **Focus on the Process**: We're more interested in *how* you approach the problem than in a perfect solution.
- **Ask Questions**: If any part of the task is unclear, don't hesitate to reach out for clarification.
- **Enjoy the Challenge**: Use this opportunity to showcase your strengths and learn something new.

Good luck!