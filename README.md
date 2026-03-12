# AI Email Doubt Solver using n8n

This project is an automation built using n8n that answers student questions sent through email.

## How it works

1. A student sends a question via email.
2. Gmail Trigger detects the email.
3. The question is extracted.
4. OpenAI generates an answer.
5. The answer is automatically sent back via email.

## Workflow

Gmail Trigger -> Edit Fields -> OpenAI -> Gmail Send Message

## Technologies Used

- n8n
- Gmail
- OpenAI

## Example

Email sent:
Subject: Question  
What is Python?

AI reply:
Python is a programming language that is easy to learn and widely used for web development, automation, and data science.
