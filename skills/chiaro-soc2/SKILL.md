---
name: chiaro-soc2
description: Use when the user wants to work on SOC 2 with Chiaro, such as starting or continuing a readiness check, collecting evidence, answering a security questionnaire, or seeing what is left before the audit. Uses the Chiaro MCP server that ships with this plugin.
---

# SOC 2 with Chiaro

The Chiaro MCP server carries its own instructions and methodology. This skill covers how to begin
and the few rules that hold everywhere. For everything else, follow the server.

## Begin

1. Call `get_status` first, every time you connect. It says what kind of engagement this is and
   where to pick up.
2. If the user has no Chiaro account, connecting opens Chiaro's sign-in in their browser, and they
   can create one there. Never ask for a password, token or API key in the chat.
3. Follow the next step each tool response names. Do not restart scoping or re-ask questions the
   server already has answers to.

## Always

- The user decides. Ask before running a command against their systems and before submitting or
  uploading anything.
- Submit only this company's own material. If a document names a different company, or people who
  do not work there, stop and ask.
- Keep secrets out of the chat and out of submissions.

## When something goes wrong

Chiaro's refusals usually name the next step, so read the message and do what it names before
retrying. If something on the server still looks broken, `report_problem` tells the Chiaro team.
