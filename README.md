# AI_Agent-Automatisation_n8n
Building AI agents and automations in n8n is essential for improving efficiency in enterprise workflows. That’s why I want to share my expertise in these areas with my community. Each automation project addresses a specific business problem and represents a distinct task or use case.

## Job 1 is called Assistant Manager-Email : <br>
🚀 My new AI Agent copilot (built in n8n): from inbox chaos to a smarter calendar—automatically.<br>
Why this matters for Data/AI Engineers: AI Agents are becoming the glue between our tools. Think of it like a lightweight, flexible ops layer—easier to prototype than some traditional stacks (Talend / NiFi / Kafka) for many day-to-day automations. <br>
What this workflow does: <br>
🧹 Cleans the inbox: auto-deletes messages I don’t need <br>
📅 Creates calendar events for emails about meetings or interventions <br>
⏰ Looks ahead 48h for upcoming events and notifies me <br>
✍️ Drafts replies for messages that need an answer and pings me to review <br>
Why I’m excited: it’s fast to build, easy to iterate, and it boosts my execution speed as an AI/Data Engineer. <br>
Thinking of learning AI Agents? Highly recommend. <br>
If you want my n8n template or node settings, drop a “AI Agent” in the comments and I’ll share. 🙌 <br>
<img width="1219" height="872" alt="Image" src="https://github.com/user-attachments/assets/ae59b8d8-47d4-4f96-b10d-6cc82110b674" />

## Job 2 is called AI Agent Scraping Webpages : <br>
This workflow automates the process of scraping a webpage, cleaning its HTML, converting it into structured text (Markdown), and returning a simplified output through an AI Agent or another workflow. <br>
It can be triggered either by: <br>
A chat message (human input to the AI Agent), or <br>
Another workflow execution (via API or automation chain). <br>

### Detailed Task Description
1️⃣ When Chat Message Received <br>
Trigger node: activates when a chat message is sent to the AI Agent. <br>
Starts the process when a user interacts via chat (e.g., “scrape this webpage”). <br>

2️⃣ AI Agent <br>
Connects to OpenAI Chat Model (GPT-based model). <br>
Interprets the message and determines what to scrape or extract. <br>
Can use memory and tools configured in the workflow (e.g., HTTP requests, parsing). <br>

3️⃣ When Executed by Another Workflow <br>
Alternate trigger node for automation. <br>
Allows another n8n workflow to call this one and reuse its scraping capabilities. <br>
