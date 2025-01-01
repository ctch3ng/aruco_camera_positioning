# ArUco Camera Positioning

## Acknowledgements
This project is adapted from the original work by [naryua](https://github.com/naruya/aruco/tree/master). The modifications include OpenCV function names updates and enhanced documentation for deployment in a virtual environment.



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

**4. Download the Project Files
- Clone or download this repository (or just the specific files you need):

- `Camera_Position.ipynb` (the main notebook)
- `mtx.npy` and `dist.npy` (camera calibration files)
- Make sure these files are in a folder you can easily access.

**5. Open the Notebook and Select the Kernel
- In the Jupyter interface, navigate to the folder where you downloaded `Camera_Position.ipynb`.
- Click on `Camera_Position.ipynb` to open it.
- In the top menu, go to `Kernel > Change kernel` and select the kernel named `Python (aruco-camera-positioning)`.

**6. Run the Notebook
- Execute each cell in order to:

- Display the generated ArUco marker
- Capture and process video frames
- Estimate the camera pose with respect to the ArUco marker
