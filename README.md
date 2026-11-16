<p align="center">
  <a href="https://tracksidehq.dev">
    <img src="https://tracksidehq.dev/icon.svg" width="112" alt="Trackside icon: the letter T drawn as a track junction">
  </a>
</p>

<h1 align="center">Trackside</h1>

<p align="center">
  <b>Run AI agents side by side, under your rules.</b><br>
  A desktop workbench for AI coding agents: compare them on the same task, decide what each one may do, and keep a record of every tool call it judges.
</p>

<p align="center">
  <img src="https://img.shields.io/badge/status-demo%20coming%20soon-111111?style=flat-square&labelColor=000000" alt="Status: demo coming soon">
  <img src="https://img.shields.io/badge/platform-macOS%20on%20Apple%20silicon-111111?style=flat-square&labelColor=000000&logo=apple&logoColor=white" alt="Platform: macOS on Apple silicon">
</p>

<p align="center">
  <a href="https://tracksidehq.dev"><b>Website and waitlist</b></a>
</p>

<p align="center">
  <a href="https://tracksidehq.dev">
    <img src="https://tracksidehq.dev/og.png" width="820" alt="The Trackside website: Run AI agents side by side, under your rules">
  </a>
</p>

---

## What it is

Coding agents are good enough to be handed real work, and they run with your shell, your files and your credentials. Trackside is the place where you watch them do it.

- **Compare.** Real terminals in tabs and split panes, one agent in each. Send the same prompt to every pane and read the answers next to each other: Claude Code, Codex, and local models through Ollama.
- **Govern.** One policy file, written by you, says what each agent may do. An MCP gateway sits in front of the tools (allow, ask, deny) and an agent hook covers the shell and the file tools, by tool name and by file path. A denied call does not reach the tool.
- **Audit.** Every decision goes to a hash-chained trail before it takes effect. You can verify the chain and export it.

It runs on your machine. Your code and your prompts do not pass through us, and there is no telemetry. What works today and the limits of each item are on the [website](https://tracksidehq.dev/#status).

## Trying it

There is no public build yet. The first release will be a demo for Macs with Apple silicon, so developers can try it and say what they think. It will be published here, under [Releases](https://github.com/tracksidehq/trackside/releases).

Until then, join the waitlist on the [website](https://tracksidehq.dev) to get one email when the demo is out.

**If Trackside looks useful to you, a star on this repository helps other developers find it.** It is an invitation, not a condition: nothing here is unlocked by a star.

## Feedback

Once the demo is out, [issues](https://github.com/tracksidehq/trackside/issues) are the place for bugs, questions and what you would like it to do. Please do not put secrets, tokens or private code in an issue.

## What this repository is

Trackside is not open source. This repository holds the demo builds and this page; the source code is not published here, and no license to it is granted.
