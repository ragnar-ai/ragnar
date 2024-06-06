# Ragnar
Notes and research augmented by LLM

# Project goal
Use open source LLMs and other open source tools to create a system that can answer questions about the content of my documents and notes.
Each answer can be edited and saved in the system as another note.

# Non functional requirements
- Must use open source LLMs and tools (should not send my data anywhere).
- Should run on a laptop (max consumed 10G RAM, 8 cores, 100G SSD).
- Isolated from the rest of the system 
- One command to bring the system up and start interacting with it
- Support Linux

# As a user of such system, I expect to:
- Feed the system my notes in the form of PDF and Markdown docs. 
- Ask questions about the content of those notes.
- The responses from the system should be based on the documents that I uploaded.
- In its response, the system should provide references to the relevant uploaded documents or notes.
- Edit those responses and save them as new notes in the system.
- Those new notes should be accessible as Markdown files and be accounted for in later queries.

# Research
Explore existing solutions and approaches in the [research section](./research/).
