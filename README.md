# Designer-Artifact-User: Installation Instructions

This guide provides step-by-step instructions to install and set up the **Designer-Artifact-User** application on an Ubuntu 24.04 Linux server.

---

## Installation Steps

Follow these steps in sequence:

1. Install python tools:
   ```bash
   sudo apt install -y python3-pip python3-virtualenv

2. Clone and change directory into Designer-Artifact-User directory:
   ```bash
   git clone https://github.com/LearnableLoopAI/Designer-Artifact-User && cd Designer-Artifact-User

3. Create python virtualenv (.venv) and activate from inside Designer-Artifact-User directory:
   ```bash
   virtualenv .venv && source .venv/bin/activate

4. Install dau-active-inference package and dependencies from requirements.txt:
   ```bash
   pip install --no-cache-dir -r requirements.txt

5. Run dau-active-inference package with --help flag to see switch options:
   ```bash
   dau-active-inference --help or dau-active-inference --duration 20
