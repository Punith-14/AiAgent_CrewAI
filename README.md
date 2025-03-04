# AgenticAI Project

Welcome to the AgenticAI project. This repository contains various AI-driven automation flows and tools designed to streamline and enhance different tasks and processes.

## Project Structure

The project is organized into multiple directories, each representing a specific flow or tool. Below is an overview of the main directories and their purposes:

- `azure_model/`: Contains models and scripts for Azure-based AI tasks.
- `CrewAI-LangGraph/`: Implements the CrewAI framework with LangGraph for task automation.
- `email_auto_responder_flow/`: Automates email responses using AI agents.
- `game-builder-crew/`: Tools and scripts for building games with AI.
- `instagram_post/`: Generates Instagram posts using AI.
- `job-posting/`: Automates the creation of job postings.
- `landing_page_generator/`: Generates landing pages from a single idea.
- `lead-score-flow/`: Scores leads based on predefined criteria.
- `markdown_validator/`: Validates markdown files for syntax issues.
- `marketing_strategy/`: Develops marketing strategies using AI.
- `match_profile_to_positions/`: Matches CVs to job proposals.
- `meeting_assistant_flow/`: Assists in managing meetings, including scheduling and follow-up.
- `meta_quest_knowledge/`: Uses PDF knowledge sources to answer questions.
- `nvidia_models/`: Contains models and scripts for NVIDIA-based AI tasks.
- `prep-for-a-meeting/`: Prepares for meetings with AI-generated insights.
- `recruitment/`: Automates the recruitment process.
- `screenplay_writer/`: Tools for writing screenplays with AI.
- `self_evaluation_loop_flow/`: Implements a self-evaluation loop for AI-generated content.
- `starter_template/`: Provides a starter template for new projects.
- `stock_analysis/`: Analyzes stocks using AI.
- `surprise_trip/`: Plans surprise trips with AI.
- `trip_planner/`: Plans trips based on user preferences.
- `write_a_book_with_flows/`: Assists in writing books using AI.

## Installation

Ensure you have Python >=3.10 <=3.13 installed on your system. First, if you haven't already, install CrewAI:

```bash
pip install crewai
```

Next, navigate to your project directory and install the dependencies:

1. First lock the dependencies and then install them:

```bash
crewai install
```

### Customizing & Dependencies

Each directory may have its own `.env.example` file. Copy this file to `.env` and fill in the required environment variables.

## Running the Project

To kickstart your crew of AI agents and begin task execution, run this from the root folder of your project:

```bash
crewai run
```

This command initializes the flow, assembling the agents and assigning them tasks as defined in your configuration.

## Contributing

We welcome contributions to the AgenticAI project. Please follow these steps to contribute:

1. Fork the repository.
2. Create a new branch for your feature or bugfix.
3. Make your changes and commit them with clear messages.
4. Push your changes to your fork.
5. Create a pull request to the main repository.

## License

This project is released under the MIT License.

## Support

For support, questions, or feedback regarding the AgenticAI project:

- Visit our [documentation](https://docs.crewai.com)
- Reach out to us through our [GitHub repository](https://github.com/joaomdmoura/crewai)
- [Join our Discord](https://discord.com/invite/X4JWnZnxPb)
- [Chat with our docs](https://chatg.pt/DWjSBZn)

Let's create wonders together with the power and simplicity of CrewAI.
