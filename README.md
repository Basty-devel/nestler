---
title: Nestler
emoji: 📊
colorFrom: green
colorTo: green
sdk: static
pinned: false
license: apache-2.0
short_description: Homepage - Vision
---

# Digital Agent of Sebastian Friedrich Nestler

## Overview
This repository contains a simple, static web page that integrates a digital AI agent. The purpose is to provide an interactive, conversational interface for visitors, enhancing the user experience on the site.

The agent is powered by an external service (D-ID in this case) and is embedded directly into the HTML using a single JavaScript <script> tag. The agent was trained using the results of a personal personality test to accurately reflect my persona, along with extensive documentation on IT security, networking, and privacy to give it domain-specific knowledge.

## Features
Interactive AI Agent: A lifelike, conversational agent that can answer questions and engage with users.

**Client-Side Integration:** The agent is fully integrated on the front-end, with no server-side components required for the agent's functionality.

**Easy to Host:** The entire project consists of a single HTML file, making it perfect for static site hosting services like GitHub Pages.

## Setup and Usage
To get this project up and running, follow these simple steps:

Clone the Repository:

git clone [https://github.com/](https://github.com/)Basty-devel/nestler.git

Open index.html: Open the index.html file in your favorite code editor.

Replace Agent Configuration: Locate the <script> tag and replace the placeholder values with your own agent's information from the D-ID Studio.

<script
    type="module"
    src="[https://agent.d-id.com/v1/index.js](https://agent.d-id.com/v1/index.js)"
    data-name="did-agent"
    data-mode="fabio"
    data-client-key="YOUR_CLIENT_KEY"
    data-agent-id="YOUR_AGENT_ID">
</script>

Host on GitHub Pages: Push your changes to GitHub and enable GitHub Pages in your repository's settings to publish your site.

## Repository Structure
index.html: The main and only file for this project, containing all the HTML structure and the embedded agent script.

README.md: This file, providing a guide to the project.

## Contribution
Contributions are not expected for this simple project, but if you have any suggestions, feel free to open an issue or pull request.

License
This project is open-source.
