# Matplotlib Challenge

## Prepare the Data
I displayed the number of unique mice IDs in the data, and then checked for any mouse ID with duplicate time points. Once this was done I created a new data frame that displayed the updated number of unique mice IDs and used this cleadned data frame for the rest of the challenge.

## Generate Summary Statistics
Next I created a data frame for summary statistics
<img width="886" alt="Screenshot 2023-08-09 at 12 18 58 AM" src="https://github.com/hmalhi95/matplotlib-challenge/assets/126418725/3abaa9b2-eb2a-4363-a184-92f4dbb1d14f">

## Create Bar Charts and Pie Charts
For this section I created 2 bar charts

<img width="424" alt="Screenshot 2023-08-09 at 12 20 04 AM" src="https://github.com/hmalhi95/matplotlib-challenge/assets/126418725/f05565af-10d9-462b-bbde-0348f76666dd">

<img width="423" alt="Screenshot 2023-08-09 at 12 20 10 AM" src="https://github.com/hmalhi95/matplotlib-challenge/assets/126418725/d82e81dd-cac6-43c8-85ba-e001f7a57707">

As well as 2 pie charts

<img width="294" alt="Screenshot 2023-08-09 at 12 20 52 AM" src="https://github.com/hmalhi95/matplotlib-challenge/assets/126418725/4e1dc839-ae9a-4190-8309-5f9fee2e86ce">

<img width="302" alt="Screenshot 2023-08-09 at 12 21 04 AM" src="https://github.com/hmalhi95/matplotlib-challenge/assets/126418725/998cc63b-d177-459a-97a8-83cc11de652b">

## Calculate Quartiles, Find Outliers, and Create a Box Plot
For this section I calculated the final tumor volume of each mouse across four of the most promising treatment regimens: Capomulin, Ramicane, Infubinol, and Ceftamin. Then, I calculated the quartiles and IQR, and determine if there are any potential outliers across all four treatment regimens. I also used Matplotlib to generate a box plot that shows the distribution of the final tumor volume for all the mice in each treatment group and highlighted any outliers.
<img width="849" alt="Screenshot 2023-08-09 at 12 24 02 AM" src="https://github.com/hmalhi95/matplotlib-challenge/assets/126418725/b20f58da-103f-4b9c-b295-6a6b26f2999b">
<img width="421" alt="Screenshot 2023-08-09 at 12 24 10 AM" src="https://github.com/hmalhi95/matplotlib-challenge/assets/126418725/20c2ab36-4611-4366-8cc1-79d24a94365f">

## Create a Line Plot and a Scatter Plot
I selected a single mouse that was treated with Capomulin, and generated a line plot of tumor volume versus time point for that mouse.
<img width="418" alt="Screenshot 2023-08-09 at 12 26 46 AM" src="https://github.com/hmalhi95/matplotlib-challenge/assets/126418725/952b13f1-1f65-4be7-ab35-bd2455fab934">

I also generated a scatter plot of mouse weight versus average observed tumor volume for the entire Capomulin treatment regimen.
<img width="419" alt="Screenshot 2023-08-09 at 12 26 53 AM" src="https://github.com/hmalhi95/matplotlib-challenge/assets/126418725/0e7b0ad0-9b23-4c42-8d69-cad1b251f3eb">

## Calculate Correlation and Regression
I calculated the correlation coefficient and linear regression model between mouse weight and average observed tumor volume for the entire Capomulin treatment regimen and then plotted the linear regression model on top of the scatter plot.
<img width="640" alt="Screenshot 2023-08-09 at 12 28 54 AM" src="https://github.com/hmalhi95/matplotlib-challenge/assets/126418725/a4e139b0-9278-4320-940e-241c086b7b5e">

