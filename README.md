# Ubuntu + Wine VPS Setup on Replit (PC Only)

This repository contains a script to set up an Ubuntu VPS with Wine on Replit for running Windows applications. The script is designed for use on Replit and is intended for PC users.

**Warning: This is not a 24/7 VPS. However, if you have a method to make it 24/7 or have a premium Replit account, it is possible to make it 24/7.**

## How to Use on Replit

### Step 1: Create a Replit Project

1. Go to [Replit](https://replit.com/) and create a new project.
2. Choose "Python" as the template for your project.

### Step 2: Open the Replit Shell

Open the Replit shell by clicking on the "Shell" tab at the bottom of the screen.

### Step 3: Download the Python Script

To download the python script, use the following `curl` command in the Replit shell:

```bash
curl -o main.py https://raw.githubusercontent.com/muhammadkhoidre/Free-Ubuntu-VPS-On-Replit/main/main.py
```

### Step 4: Download the Nix Script

To download the nix script, use the following `curl` command in the Replit shell:

```bash
curl -o replit.nix https://raw.githubusercontent.com/muhammadkhoidre/Free-Ubuntu-VPS-On-Replit/main/replit.nix
```

### Step 5: Run the Script

Run the script using the run button or the following command in the Replit shell:

```bash
python3 main.py
```

### Step 6: Follow On-Screen Instructions

The website will guide you.

## Requirements

- **Replit Account**: Ensure you have a Replit account and access to create a new project.
- **Python 3**: The Replit Python template comes with Python 3 pre-installed.
- **Curl**: `curl` is available in the Replit shell by default.

## Contact

For any questions or support, please join this [discord server](https://dsc.gg/madkung) and open a ticket.
