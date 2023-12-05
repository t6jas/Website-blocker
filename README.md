# Website Blocker

## Overview

This Python script allows you to block access to specified websites by modifying the hosts file on your system. It can be useful for limiting access to distracting websites during specific periods.

## Features

- **Blocking:** Automatically blocks access to specified websites during a defined time period.
- **Unblocking:** Restores normal access to the blocked websites when the specified time period ends.

## Requirements

- Python 3.x

## Usage

1. Edit the `site_block` list in the script to include the websites you want to block.
2. Set the `end_time` variable to the time until which the websites should be blocked.
3. Run the script with appropriate permissions to modify the hosts file.

```bash
python website_blocker.py
