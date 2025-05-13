# Weight Lifting Exercise Prediction

This project is part of the Coursera [Practical Machine Learning](https://www.coursera.org/learn/practical-machine-learning) course. It uses data from accelerometers placed on different body parts (belt, forearm, arm, dumbbell) to classify the quality of barbell lifts performed by participants.

## 📂 Files Included

- `project.Rmd`: R Markdown file containing the full analysis, model building, and predictions.
- `project.html`: Compiled HTML output of the R Markdown file.

## 📊 Project Goal

The objective is to predict the "classe" variable (representing the manner in which the exercise was performed) using sensor data. The dataset comes from the [PUC-Rio Human Activity Recognition project](http://groupware.les.inf.puc-rio.br/har).

## 🧠 Approach

- Cleaned and filtered noisy/missing data
- Partitioned training set (70/30 split)
- Trained a Random Forest model using 5-fold cross-validation
- Evaluated model with a confusion matrix
- Estimated out-of-sample error
- Made predictions on a test set

## 📈 Performance

The final model achieved high accuracy with an estimated out-of-sample error of approximately **1.2%**.

## 🔗 Live Report (Optional)

If GitHub Pages is enabled, the compiled report can be viewed at:  
`https://<your-username>.github.io/<your-repo-name>/project.html`

---

## 📜 Citation

Please cite the original data source:  
Velloso, E. et al. (2013). *Qualitative Activity Recognition of Weight Lifting Exercises*. PUC-Rio.

