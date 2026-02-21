AI-Powered LinkedIn Post Automation with Human Approval Loop

This project is an automated LinkedIn content publishing system that generates posts using AI and publishes them only after email approval. It combines intelligent content creation with a human-in-the-loop validation process to ensure quality and control.

#How It Works :

Topic Input (Chat Trigger) :
The user provides a topic or theme through a chat trigger.

AI Content Generation :
An AI agent generates a structured LinkedIn post based on predefined style guidelines and system instructions.

Email Approval System :
The generated draft is sent to the user’s email for review.
Reply with approval → Post is published.
Suggest changes → AI refines the content.

Refinement Loop :
If feedback is provided, the AI updates the post and sends it again for approval.
This continues until confirmation is received.

Automatic Publishing :
Once approved, the workflow automatically publishes the post to LinkedIn.

#Tech Stack:
n8n (Workflow Automation)
AI Language Model (Gemini)
Gmail API (Approval Workflow)
LinkedIn API (Post Publishing)
Conditional Logic Routing
