# About project

So we are creating a project that orchestrates multiple AI agents using Microsoft Foundry Agent Service. Designing an AI solution that assists with ticket triage.
The connected agents will assess the ticket's priority, suggest a team assignment, and determine the level of effort required to complete the ticket. 
Let's get started!



## Crrate a .env file and add the below env var

your_project_endpoint 
your_model_deployment 

## To run the code

```
az login
```

```
python3 -m venv .venv
source .venv/bin/activate
python3 agent_traige.py
```

### sample input 

```
Users can't reset their password from the mobile app.
```

### sample output 

```
Creating agent thread.
Processing agent thread. Please wait.

MessageRole.USER:
Users can't reset their password from the mobile app.

MessageRole.AGENT:
### Ticket Assessment

- **Priority:** High — This issue blocks users from resetting their passwords, limiting access to their accounts.
- **Assigned Team:** Frontend Team — The problem lies in the mobile app's user interface or functionality.
- **Effort Required:** Medium — Resolving this problem involves identifying the root cause, potentially updating the mobile app functionality, reviewing API/backend integration, and testing to ensure compatibility across Android/iOS platforms.

Cleaning up agents:
Deleted triage agent.
Deleted priority agent.
Deleted team agent.
Deleted effort agent.
```
