#### This project uses orbital element data from Space-Track.org to classify objects as either payloads (satellites) or debris.

## Files

* **generalDataExploration.ipynb**: I used this notebook to gain a general understanding of the data. All of the visuals contrained in the PDF document (the final report) were created using this code. Visualisations include bar charts and pie charts.
* **classifierModels.ipynb**: This is the actual notebook that contains my random forest models which I used for this project.
* **Final Project Report.pdf**: This is a PDF paper about the code in this repository. I used LateX to compille it, but a similar effect can be acheved using IEEE 2026 Word Template as well.
* **requirements.txt**: Contains the names of the dependencies necessary to run the notebooks.


## Dependencies
Ensure you have an environment with `pandas`, `matplotlib`, `scikit-learn`, and `spacetrack`. I used a conda environment, but pip environments should work as well.

## For anyone non-cs referencing this:
After downloading this repository and creating an environment, you could just run this command to install all the necessary dependencies: 

*pip install -r requirements.txt*
