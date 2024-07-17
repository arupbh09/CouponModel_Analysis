# Title: Analysis to find what factors - driver behavior and characteristics can lead to coupon acceptance**

## Description
### In this project, we used data collected via a survey on Amazon Mechanical Turk that captured whether driver accpeted a coupon under different cirumstances.
### For this project, we analyzed driver behavior for two types of coupons, "bar" and "coffee houses," using pandas, numpy and seaborn visualization

## Installation

### The project in the repository will include the following files
#### Readme file: Readme.md
#### Jupyter Notebook: CouponSelectionModel.ipynb
#### Data file: coupon.csv

### Create a project directory and loading the Jupyter notebook
#### Download CouponSelectionModel.ipynb file ont to the project directory
#### Upload file onto the Jupyter Notebook and open it

### Data set up: option 1
#### Create the directory data/ under the root directory of Jupypter Notebook
#### Save the coupon.csv file under this directory

### Data set up: option 2
#### Save the coupon.csv file in a location that is preferable to you
#### Update this line of code in the  CouponSelectionModel.ipynb 
##### data = pd.read_csv('./data/coupons.csv')

## Usage
#### After setting up the data, you can run the Python code in the Jupyter notebook 
#### The code has markdown sections that outline the approach of the analysis and can help you understand the logic
#### Upon running the code, you will generate string outputs and seaborn plots

## Data
### This data comes to us from the UCI Machine Learning repository and was collected via a survey on Amazon Mechanical Turk. The survey describes different driving scenarios including the destination, current time, weather, passenger, etc., and then ask the person whether he will accept the coupon if he is the driver. 
### Answers that the user will drive there ‘right away’ or ‘later before the coupon expires’ are labeled as ‘Y = 1’ and answers ‘no, I do not want the coupon’ are labeled as ‘Y = 0’. 
### There are five different types of coupons -- less expensive restaurants (under \$20), coffee houses, carry out and take away, bar,and more expensive restaurants (\$20 - \$50).

## Contribution
### You can extend the project and add analysis by exploring the three other types of coupons 
#### less expensive restaurants (under \$20),
#### expensive restaurants (\$20 - \$50)
#### carry out and take away coupons
### You can add additional visualization to the "bar" and "coffee house" coupon analysis
### You can save the plots as png files
