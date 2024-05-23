
### Python version 3.10.4

To create a virtual environment and install requirements in Python 3.10.4 on different operating systems, follow the instructions below:

### For Windows:

Change the directory to the desired location for your project:
cd C:\path\to\project

Create a new virtual environment using the venv module:
python -m venv myenv

Activate the virtual environment:
myenv\Scripts\activate

Install the project requirements using pip:
pip install -r requirements.txt

### For Linux/Mac:

Change the directory to the desired location for your project:
cd /path/to/project

Create a new virtual environment using the venv module:
python3.10 -m venv myenv

Activate the virtual environment:
source myenv/bin/activate

Install the project requirements using pip:
pip install -r requirements.txt


To run the streamlit app which is in a foundational level

streamlit run llm_app.py
