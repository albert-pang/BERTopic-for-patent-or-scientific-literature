# BERTopic-for-Patent-or-Scientific-Literature

1. Open Anaconda prompt

2. Change directory to project folder (where the environment.yml is):
cd <PATH_TO_FOLDER>

4. Create the new environment and install dependencies:
conda env create -f environment.yml

6. Activate the newly created environment:
conda activate bertopicnew

8. Install kernel so that the environment can be accessed by the jupyter notebook:
python -m ipykernel install --user --name bertopicnew

Note: You can change the name "bertopicnew" by changing environment name inside the .yml as well

6. Go back to base environment:
conda deactivate

8. Open jupyter notebook:
jupyter notebook

10. Open the .ipynb file

11. Menu Kernel -> Change kernel -> bertopicnew
