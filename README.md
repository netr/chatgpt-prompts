# ChatGPT Prompts for Developers
ChatGPT prompts to help developers be more productive

### Help design a cloud based system architecture
```
Act as a software engineer with experience of system design and architecture.

Your task is to design a system that does the following:
1. [Task]
2. [Task]

Design the system to run on [Cloud platform].
```

Follow up:
`Write a step by step tutorial for setting up task #[number]. Explain it to a junior developer.`

### Setup a docker + docker compose file for application
```
Act as a dev ops engineer. 

Your task is to write a dockerfile and docker compose file that has the following features:
- Does a multi-stage build for a [programming language] app.
- Uses docker secrets to store two environment variables: [list env variables]
- Limits container priviledges that follows the best practices.
- Uses a secure base image.
```
