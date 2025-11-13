# Create a virtual environment
python -m venv venv

# Activate the environment
source venv/bin/activate        # On macOS/Linux
venv\Scripts\activate           # On Windows

# Install dependencies
pip install -r requirements.txt

# Launch Jupyter Lab and open the notebook
jupyter lab path/to/the_notebook.ipynb
