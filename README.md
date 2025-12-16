# Low Cost Spec Driven Prompts
This repository aims to provide a set of prompts to faciliate a spec-driven-development flow targetted for low-cost models.

# Problem Statement 
Higher-cost models are often trained to perform development in a more structured format with less prompting. Additionally, higher-cost models often have larger context windows that allow it to be maintain more of the project context at a given point in time.

# Resolution
- Include a easy to follow, structured set of prompts to guide development from both green-field and brown-field projects
- Have the prompts create the required set of documents and collaterals that guide the AI model to the correct files and conventions during coding through small concise prompts to minimize filling of the context

# Target
- Github CoPilot:
    - GPT-5 mini: For planning and design
    - Grok Code Fast 1: For feature implementation

# Development Flow
1. Project Definition Overview
2. Release Version Definition
3. Release Version Development:
    1. High-Level Component / Dataflow Design
    2. Version Architecture Design Decisions
    3. Sprint Planning
    4. Sprint Development:
        1. Plan the acceptance criteria
        2. Plan the high-level design for this sprint
        3. Plan the tasks for this sprint
        4. Begin execution
        5. Execute tests and validate
        6. Perform PR review

# Getting Started
1. Copy the files in the '.github' and 'docs' folder to your project.
2. Begin using the prompts in-order to organize the project and begin development