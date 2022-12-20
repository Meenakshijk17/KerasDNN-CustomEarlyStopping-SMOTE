# Multi-class classification using DNNs & Early Stopping using Custom metric

## Aim

To design and train a deep neural network on a multiclass cutomer segmentation data, and monitor the early stopping logic using f1-score (need to be passed as a custom function). Finally, use upsampling methods like SMOTE to check for any improvement of the model.

## Data
The data was taken from https://www.kaggle.com/datasets/
abisheksudarshan/customer-segmentation. It is a multi-class classification problem. The variable 'var_1' is the target and contains several categories, of which, Cat_6 (~ 65%) & Cat_4 (~ 14%) are used as such. All others are mapped to 'Other' (~ 21%).