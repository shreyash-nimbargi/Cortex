# Cortex

A simple CLI-based personal finance assistant powered by Groq AI. Interact with "Josh" to manage your expenses, income, and financial balance through natural language commands.

## Features

- Add and track expenses
- Add and track income
- Get total expenses for a period
- Check remaining money balance
- AI-powered conversation for financial planning

## Prerequisites

- [Bun](https://bun.sh) runtime
- GROQ_API_KEY environment variable (get from [Groq](https://groq.com))

## Installation

```bash
bun install
```

## Usage

Create a `.env` file in the root directory with your GROQ_API_KEY:


```

Run the assistant:

```bash
bun run dev
```

Type your financial queries (e.g., "Add expense for coffee $5", "What's my balance?"). Type 'bye' to exit.

This project was created using `bun init` in bun v1.0.25. [Bun](https://bun.sh) is a fast all-in-one JavaScript runtime.
