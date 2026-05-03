# Epidemiological-models-and-epidemic-simulation
Project completed as a pair as part of a course at the University of Technology of Compiègne (UTC)

## Built with
- **Language**: Scilab
- **Interface**: Jupyter Notebook

##  Installation

### 1. Prerequisites
- **Python 3.x** installed.
- **Scilab** installed and added to your system path.

### 2. Environment Setup

```bash
# 1. Clone the repository
git clone https://github.com/Overcraftor/Epidemiological-models.git
cd Epidemiological-models

# 2. Navigate to the project folder:
cd path/to/Epidemiological-models-and-epidemic-simulation
# 3. Create and activate a virtual environment:
python -m venv .venv

# Activate the environment (Windows)
.\.venv\Scripts\activate
# Activate the environment (Linux/macOS)
source .venv/bin/activate

# 4. Install JupyterLab and the Scilab kernel
pip install -r requirements.txt
# Or 
pip install jupyterlab scilab_kernel

# 5. Update the kernel spec for Scilab
python -m scilab_kernel install --user
```

### 3. Running the Project
```bash
# Navigate to the project folder
cd path/to/Epidemiological-models-and-epidemic-simulation
# Activate the virtual environment
source .venv/bin/activate
# Start JupyterLab
jupyter lab
```
