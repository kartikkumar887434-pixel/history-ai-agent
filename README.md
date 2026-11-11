# history-ai-agent
Automated AI History YouTube Video Generator

name: History AI Daily Agent

on:
  workflow_dispatch:
  schedule:
    - cron: "0 18 * * *"
      timezone: "Asia/Kolkata"

jobs:
  agent:
    runs-on: ubuntu-latest
    steps:
      - name: Start AI Agent
        run: echo "History AI Agent started"
