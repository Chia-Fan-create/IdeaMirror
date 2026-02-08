### Idea Mirror 🤯🪞

AI-powered customer simulation for early product validation

#### Background

Idea Mirror was created during the She Innovates 2026 Hackathon as a prototype to help Product Managers validate ideas faster before committing resources.

#### Problem

Product Managers often struggle to answer early-stage questions such as:

- Is this idea worth building?

- How would different customer segments react?

- Can we get directional feedback without running a full research study?

Traditional user research is time-consuming and expensive, especially at the ideation stage.

#### Solution

Idea Mirror introduces AI-generated “shadow customers” that simulate realistic customer reactions based on selected demographics and behavioral traits.

PMs can:

- Upload an idea or document

- Define target customer segments

- Run simulations with hundreds of AI customers

- Receive a synthesized report for decision-making

The goal is to support early hypothesis testing, not to replace real user research.

#### Key Features

**AI customer persona simulation**

**Configurable demographics and behaviors**

**Fast, low-cost idea validation**

**PM-ready insight reports**

#### Prototype

Figma Prototype (Interactive Demo)
Link below:
https://quest-mask-76730639.figma.site/


#### Screens

![Entry Screen](designs/Entry_screen.png)

![Customer selection & simulation setup](designs/Customer_selection_simulation_setup.png)

![Shadow customer preview](designs/preview_report.png)

#### Future Implementation (Conceptual)

While this project is currently a prototype, below is a realistic path for production implementation:

1. Idea Ingestion & Processing

- PM uploads an idea or PRD (text or PDF)

- System sanitizes sensitive information

- Content is parsed and chunked for processing

2. Persona Simulation

- Mock customer personas are generated based on selected criteria

- Prompts are dynamically constructed per persona

- Simulations run in parallel using an LLM

3. Analytics & Reporting

- Simulated feedback is aggregated and analyzed

- Sentiment, acceptance, and key themes are identified

- A summarized insight report is generated for PM review

4. Human-in-the-Loop Review

- PMs review and interpret results

- Insights are used to refine ideas or guide real research

#### Disclaimer

Idea Mirror is designed for early-stage exploration and directional insight.
It does not replace real customer research, but helps teams ask better questions earlier.

#### Team & Role

Hackathon team project

My role: Product ideation, UX design, and AI concept design
