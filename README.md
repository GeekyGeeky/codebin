# CodeBin

## Overview

This is a simple web application written in Go that allows users to quickly share and store snippets of code or text, similar to services like Pastebin and GitHub Gist.

## Features

[x] Snippet Sharing: Easily share code snippets or text with others by pasting them into the application.
Syntax Highlighting: Syntax highlighting for various programming languages, enhancing readability.

[ ] Expiration: Set expiration options for snippets, ensuring they are automatically removed after a specified period.
Anonymous Posting: Option for users to post snippets anonymously without requiring an account.

[ ] User Accounts: Users can create accounts to manage their snippets and access additional features.

[ ] Version Control: Basic version control features, allow users to view previous revisions of their snippets.

[ ] Embedding: Ability to embed snippets into other websites or blogs using provided embed codes.

[ ] Collaboration: Allow other users to contribute & edit the same snippet at the same time.

[ ] Gamification: Allow users to earn badges and achievements, and also have leaderboards to incentivize user participation, encourage contributions, and foster a sense of community.

[ ] API Access: RESTful API for programmatic interaction with the service, enabling integration with other applications.

## Technologies

- Golang
- MySQL
- HTML5 templating

## Installation & Project Setup

Follow the steps below to set up and run the application locally on your machine.

### Clone the project

```bash
git clone https://github.com/yourusername/gopaste.git
```

### Install dependencies

```bash
go mod tidy
```

### Run the project

```bash
sh run.sh
```
