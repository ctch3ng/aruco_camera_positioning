# aruco_camera_positioning

## Prerequisites
[Anaconda](https://www.anaconda.com/) should be installed on your system.

## Installation Steps

**1. Create and Activate the Virtual Environment** 
- Open an Anaconda PowerShell Prompt and run:
```bash
conda create --name aruco-camera-positioning python=3.8 -y
conda activate aruco-camera-positioning
```

**2. Install Required Packages**
- Install the necessary dependencies
```bash
pip install opencv-python numpy matplotlib moviepy tqdm ipython ipykernel
```

**3. Configure IPython Kernel for Jupyter Notebook (If you plan to use Jupyter Notebook)**
```bash
python -m ipykernel install --user --name=aruco-camera-positioning --display-name "Python (aruco-camera-positioning)"
```

**4. Launch Jupyter Notebook**

- In Jupyter Notebook, create a new notebook.
- Select the kernel `Python (aruco-camera-positioning)` by going to `Kernel > Change Kernel` and choosing the correct environment.

**5. Copy and Paste the Code**
- Copy the Python code from the main script (`main.py`) and paste it into a cell in the new notebook.

**6. Run the Notebook**
- Execute the code cell by cell to see the output and interact with the posture corrector project.
