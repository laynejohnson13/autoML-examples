# autoML-examples

1. Two dependent variable for experiment 1 and experiment 2
   Experiment 1 - APR Risk of Mortality
   Experiment 2 - Total Charges
2. What was the best performing model (please interpret (a) log-loss or RMSE between models, and (b) AUC)
   Experiment 1 - Best performing model was Ensemble
   Experiment 2 - Best performing model was Ensemble
3. How much better (? if any) did the model perform compared to baseline?

   Metric Value Data (EXPERIMENT 1):

   1. [1_Baseline]()  1.20244
   2. [2_DecisionTree]()  0.66366
   3. [3_Linear]()   0.621415
   4. [4_Default_Xgboost]()   0.614364
   5. [5_Default_NeuralNetwork]() 0.69787
   6. [6_Default_RandomForest]() 0.624269
   7. [Ensemble]() 0.596263

Metric Value Date (EXPERIMENT 2)

1. **1_Baseline 1.20150**
2. **2_DecisionTree 0.69614**
3. **3_Linear 0.63816**
4. **4_Default_Xgboost 0.63194**
5. **5_Default_NeuralNetwork 0.7777**
6. **6_Default_RandomForest 0.64472**
7. **Ensemble 0.61732**
