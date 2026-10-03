# n8n Simple AI Agent

This project is a simple n8n workflow created for learning and demonstration purposes.

## Workflow

The workflow contains:

- Chat Trigger
- AI Agent
- OpenAI Chat Model
- Simple Memory
- Gmail Tool

## How it works

A user sends a chat message.

The message is passed to the AI Agent, which uses the OpenAI Chat Model and Simple Memory.

The Gmail node is connected as a tool that the AI Agent can use when required.

## Requirements

You need:

- n8n
- OpenAI API access
- Gmail account

## How to Import

1. Download the `.json` workflow file from this repository.
2. Open your n8n instance.
3. Import the JSON workflow.
4. Configure your own OpenAI credentials.
5. Configure your own Gmail credentials.
6. Test the workflow.

## Important

This workflow is shared for learning purposes.

Do not use or share anyone else's API keys, passwords, OAuth credentials, or access tokens.

Users should configure their own credentials in n8n.
