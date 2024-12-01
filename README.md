# RULES
SEL Project 2: Implementation of Random Forest and Decision Forest with CART
Author: Marc Pascual Roig

Course: Supervised and Experiential Learning

### Folders and files

- `Data`: contains the csv/xlsx/data datasets. 
- `Plots`: contains lineplots and barplots.
- `Source`:  with the scripts `main.py`, `random_forest.py`, `decision_forest.py` and `decision_tree.txt`. 
- `Results`: txt files (one per each classifier and per dataset), with the accuracies, hyperparameters, and feature importance results.
- `Documentation`: contains the report of the project. 
- A `README.md` file.
- `Requirements.txt`

### Execute the code

1. Open the project
2. Create a virtual environment using Python `python -m venv myenv`
3. Open the virtual environment `source myenv/bin/activate` (or '\myenv\Scripts\Activate.ps1').
4. Install the required dependencies `pip install -r requirements.txt`
5. Choose the dataset(datasets) for the execution: datasets = ["iris", "wdbc", "mushroom"]
6. Choose whether to execute Random Forest, Decision Forest, or both: random_forest = True, decision_forest= True
7. Run the main file of the project.
8. Output: .txt files with rules and metrics (in the Source folder).
