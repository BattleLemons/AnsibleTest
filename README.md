# AnsibleTest

A simple repository for testing and experimenting with Ansible playbooks, roles, and configurations.

## Project Structure

- **logs/**  
  A directory reserved for log files generated during playbook runs (e.g., output logs).

- **playbooks/**  
  Contains Ansible playbooks. For example, there’s a simple `ping.yml` file to test connectivity.

- **roles/**  
  Houses various Ansible roles. Each role can have its own structure including tasks, handlers, defaults, etc.

- **venv/**  
  This directory contains the Python virtual environment used to manage dependencies and isolate project-specific Python packages.

- **.gitignore**  
  A file specifying which files and directories should be ignored by Git.

## Requirements

- **Ansible**: Install Ansible (version 2.9 or later recommended)  
- **Python**: If you are using the provided virtual environment, ensure you have Python installed

## Setup

1. **Clone the repository:**
   ```bash
   git clone https://github.com/BattleLemons/AnsibleTest.git
   cd AnsibleTest