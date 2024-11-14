# actl


Control tool for different scripts and CLI tasks.

## Prerequisites

`task`: Install task from [here](https://taskfile.dev/installation/)

## Installation

Clone this repo:
  ```
  git clone https://github.com/agonza05/actl ~/actl
  ```

Set up the `actl` alias. For ZSH:
  ```
  echo 'alias actl="task -t ~/actl/Taskfile.yaml"' >> ~/.zshrc
  ```

## Usage

List all available commands:
  ```
  actl
  ```

Run available command:
  ```
  actl os:show
  ```

Show command details:
  ```
  actl --summary os:show
  ```