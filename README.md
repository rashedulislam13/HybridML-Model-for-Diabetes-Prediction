# HybridML-Model-for-Diabetes-Prediction   [Published paper.pdf](https://github.com/user-attachments/files/19071414/Published.paper.pdf)

Type 2 diabetes mellitus (T2DM) is a major global health issue that significantly reduces life expectancy and
impairs overall quality of life. Early diagnosis of T2DM is critical, as it can help prevent or delay the
development of associated complications. This study aims to assess the effectiveness of a stacked ensemble
machine learning model, incorporating a meta-model approach, for the early detection of T2DM. In the first
stage of modeling (Level 1), two base models - random forest (RF) and support vector machines (SVM) - are
trained using distinct feature selection, tuning, and optimization strategies. In the second stage, ensemble
methods, such as voting and stacking classifiers, are employed to combine the predictions from these base
models. The final prediction is made by a meta-model, specifically a gradient boosting classifier (GBC),
which classifies individuals as either positive or negative for T2DM. Further classification of positive
instances is based on low-, moderate-, or high-risk levels. The system is designed for deployment to enable
real-time assessment of diabetes risk. The Meta-Model (GBC), with an accuracy of 99.13%, a precision of
100%, specificity of 100%, and an F1 score of 99.25%, consistently outperforms the base models (SVM and
RF) and ensemble models (voting and stacking classifiers), proving highly effective in the early detection of
T2DM. This significant accuracy highlights the enormous promise of machine learning methods for assisting
in the early identification of T2DM. The findings of this study will significantly enhance precision medicine
screening for T2DM, empowering healthcare professionals to diagnose the condition early and ultimately
improve patient outcomes.
