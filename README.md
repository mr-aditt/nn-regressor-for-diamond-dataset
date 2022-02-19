# Neural Net Regressor using Tensorflow
Create a Neural Network to predict `price` (response) of diamond based on predictors like `Carat`, `cut`, `Color` etc.

## Dataset
**Info about dataset**
> [Dataset](https://www.kaggle.com/shivam2503/diamonds/download)

| Column Name | Description | Additional Description |
|    :----:   |    :----    | :--- |
| Carat       | weight of the diamond | |
| cut         | Cut quality of the diamond | Fair (best), Good, Very Good, Premium, Ideal (worst) |
| Color       | Color of the diamond | D (best) & J (worst) |
| Clarity     | How obvious inclusions are within the diamond | FL = flawless (best), IF, VVS1, I3=level 3 inclusions (worst)  |
| Depth %     | Height of a diamond, measured from the culet to the table, divided by its average girdle diameter| |
| Table %     |width of the diamond's table expressed as a percentage of its average diameter||
| Price       |the price of the diamond||
| x           |Length in mm||
| y           |Width in mm||
| z           |Depth in mm||

## Steps
- [x] Get Data
- [ ] Perform Exploratory data analysis (EDA)
- [x] Scale and One-Hot-Encode the Data
- [x] Create and train Model
- [x] Evaluate Model 
