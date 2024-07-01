Gender Distribution Bar Chart
This script creates a bar chart to visualize the gender distribution with counts for 'Male', 'Female', and 'Others'.

Prerequisites
->Python 3.x

->Matplotlib library

Script:
import matplotlib.pyplot as plt
Genders = ['Male','Female','Others']
Counts = [200,300,40]

#create a bar chart
plt.figure(figsize=(6,4))
plt.bar(Genders,Counts,color=['gray','yellow','pink'])
plt.xlabel('Gender')
plt.ylabel('Counts')
plt.title('Gender Distribution')
plt.show()

Description:
1.Genders: A list of gender categories.
2.Counts: A list of corresponding counts for each gender category.
3.The plt.figure(figsize=(6,4)) function sets the size of the figure.
4.The plt.bar(Genders, Counts, color=['gray', 'yellow', 'pink']) function creates the bar chart with the specified colors.
5.The plt.xlabel('Gender') and plt.ylabel('Counts') functions label the x-axis and y-axis, respectively.
6.The plt.title('Gender Distribution') function sets the title of the chart.
7.The plt.show() function displays the chart.

Output:
Running this script will produce the following bar chart:
![Screenshot 2024-07-01 195226](https://github.com/Lavanya-1234198/PRODIGY_DS_01/assets/174336088/86bd6b8c-2a15-4db5-8c62-19612a836804)
