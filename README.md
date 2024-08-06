# Inture

## Overview

Inture is a project focused on developing a framework for **LLM multi-agent programming**, in order to have a better understanding of the capabilities of the agents and the interactions between them.


## Repository Structure

#### t00-initial-tests/
 
Contains the initial tests for the project. The most interesting one is the automatic chess game between two agents.

#### t01-agentcoding/

Contains the **multi-agent programming project** built for the final exam of the course "Deep Learning" at the University of Trieste.

## Setup

To set up the environment, update the environment with the [`conda.yml`](command:_github.copilot.openRelativePath?%5B%7B%22scheme%22%3A%22file%22%2C%22authority%22%3A%22%22%2C%22path%22%3A%22%2FUsers%2Fagustin%2Fprojects%2Finture%2Fconda.yml%22%2C%22query%22%3A%22%22%2C%22fragment%22%3A%22%22%7D%5D "/Users/agustin/projects/inture/conda.yml") file:

```bash
conda env update -f conda.yml
```

Create a `.env` file with the following content:

```bash
GOOGLE_API_KEY=
OPENAI_API_KEY=
```

## License

This project is licensed under the MIT License.