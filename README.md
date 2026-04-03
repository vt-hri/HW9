# HW9

Dylan Losey, Virginia Tech.

In this homework assignment we will explore different techniques for improving an imitation learning policy.

## Install and Run

```bash

# Download
git clone https://github.com/vt-hri/HW9.git
cd HW9

# Create and source virtual environment
# If you are using Mac or Conda, modify these two lines as shown in [HW0](https://github.com/vt-hri/HW0)
# If you have previously created a virtual environment with torch, you can just source that environment
python3 -m venv venv
source venv/bin/activate

# Install dependencies
# If you are using Mac or Conda, modify this line as shown in [HW0](https://github.com/vt-hri/HW0)
pip install numpy pybullet torch

# Run the script
python get_dataset.py
```

## Expected Output

<img src="env.gif" width="750">

## Assignment

change model size (start with 32, then increase)
add history
add noise to upsample
 