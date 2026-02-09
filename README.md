# adaptive-learning-assistant-369

adaptive-learning-assistant/
│
├── README.md
│
├── agents/
│   ├── learning-agent.md
│   ├── assessment-agent.md
│   ├── feedback-agent.md
│   └── orchestrator-agent.md
│
├── data/
│   ├── training-content/
│   ├── assessments/
│   └── feedback/


# Adaptive Learning Assistant for Enterprise Training

## Project Overview
This project implements a multi-agent AI system using Microsoft Foundry and Azure AI
services to deliver personalized training, assessment, and feedback.

## Architecture
- Azure AI Foundry (Agents)
- Azure AI Search (RAG)
- Azure Blob Storage
- Azure OpenAI Models

## Key Features
- Stateful multi-agent system
- Retrieval-Augmented Generation (RAG)
- Adaptive learning workflows
- Enterprise-ready design

## Demo (Video of user and agent's response)
See demo video link in `https://drive.google.com/file/d/1HKiskCWma1nZZfKhVMqohw3U5gt_Gmxn/view?usp=drive_link`


## Learning Agent

Purpose:
Delivers personalized training content using Retrieval-Augmented Generation (RAG).

Capabilities:
- Retrieves learning materials from Azure AI Search
- Adapts explanations based on learner level
- Provides structured learning paths


## Assessment Agent

Purpose:
Evaluates learner understanding using quizzes and questions.

Capabilities:
- Generates quizzes from indexed assessment content
- Adjusts difficulty based on learner progress
- Supports formative evaluation


## Feedback Agent

Purpose:
Provides constructive feedback and improvement suggestions.

Capabilities:
- Analyzes learner performance
- Suggests targeted improvements
- Encourages continuous learning


## Orchestrator Agent

Purpose:
Coordinates multiple agents to deliver adaptive learning experiences.

Responsibilities:
- Routes learning requests to Learning Agent
- Routes quizzes to Assessment Agent
- Routes improvement queries to Feedback Agent
- Maintains learner context across conversation turns
