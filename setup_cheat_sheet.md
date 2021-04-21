Cheat Sheet - Python Anaconda Environments

TO CREATE A NEW ENVIRONMENT:
	•	conda create —n <insertname> python=versionnum
	•	Conda activate <insertname>

TO INSTALL PIP
	•	conda install pip
	•	pip install -r filename.txt 
	⁃	NOTE: used when creating a requirements.txt file with your libraries
	⁃	best practice is to create this near where your jupyternote book will be saved

TO INSTALL JUPYTER
	•	pip install jupyter

TO ENSURE YOUR KERNEL APPEARS ON JUPYTER NOTEBOOK
	•	python -m ipykernel install --user --name=<insertname>

TO LAUNCH JUPYTER NOTEBOOK
jupyter notebook
