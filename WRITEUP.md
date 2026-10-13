# COMP 440 HW2: Whose Preferences Count?

**Name:** Dino Li
**Date:** October 12, 2026

## Part 0: Set up

### Step B: What an MCP server is and why it's useful

MCP stands for Model Context Protocol. It has three components: the MCP host, the MCP client and
the MCP server. An LLM is also involved, but only as a chatbox that outputs text. The MCP host can
retrieve tools from the MCP server. The LLM outputs text that picks the appropriate tool for the
command and sends it to the MCP host. The MCP host then calls the tool and has the server execute
the command. This is useful because it lets the user execute commands and tasks from a chat with
an LLM. Another example of MCP is VS Code. VS Code itself is the MCP host/client and it can
connect to an MCP server to fetch tools and data.

### Step B: Why not paste code into Colab yourself

Because pasting code into Colab yourself involves many steps and human effort whereas using Claude
and the MCP server is so much easier and you can call on changes directly.

### Step D: How the MCP server connects Claude Code to Colab

There are three parts in this operation: Claude, VS Code and the Google scratchpad. I think VS
Code is the MCP host, and it retrieves toolboxes from the server, Claude, and executes commands
with tools on the Google scratchpad, which is the MCP client.

## Part 1: The tools and the tests

### Step 1: About the model

XXXX

### Step 2: What the model predicts next

XXXX

### Step 3: Your four grades

XXXX

### Step 4: The held-back items

XXXX

### Step 5: Your run folder

XXXX

### Step 6: One question traced, and your diagram

XXXX (type the diagram here, or add an image of it to the repository and link it here)

### Step 7: Your 10 grades and Claude's

XXXX

### Step 8: Three surprising answers

XXXX

## Part 2: Train your two models and decide what changed

### Step 1: Your famous person, and why

XXXX (your passages go in `voice-samples.md`)

### Step 2: Your constitutions

XXXX (your lines go in `constitutions.md`; answer the Step 2 questions here)

### Step 3: Your test family

XXXX (a paragraph on your family, and the Step 3 questions; your items go in `evals/mine/`)

### Step 4: Your map and predictions

XXXX (one table: each line of `constitutions.md`, its family or "not measured", your predictions)

### Step 5: What Claude's answers do

XXXX

### Step 6: Your blind labels

XXXX

### Step 7: What SFT changed

XXXX

### Step 8: Your two reward logs

XXXX

### Step 9: Four models before grading, and your run folder

XXXX

### Step 10: Your review and the audit

XXXX

### Step 11: Whose preferences count

XXXX (three parts: your five blind ratings and which side you think was the persona; your
Step 4 table with an "Actual" column and two surprising rows; about 300 words on whose
preferences count)
