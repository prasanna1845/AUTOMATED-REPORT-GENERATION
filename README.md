# AUTOMATED-REPORT-GENERATION
COMPANY NAME :CODETECH IT

NAME:PRASANNAKUMAR.M

INTERN ID:CT04DZ1481

DURATION:25-07-2025 TO 25-08-2025

MENTOR:NEELA SANTHOSH KUMAR

PROGRAM: import pandas as pd import matplotlib.pyplot as plt

1. Import Libraries:



import pandas as pd
import matplotlib.pyplot as plt

pandas is used to handle and manipulate data easily.

matplotlib.pyplot is used for creating visual plots.

2. Create a Sample Dataset:



data = {
'Day': ['Mon', 'Tue', 'Wed', 'Thu', 'Fri', 'Sat', 'Sun'],
'Sales': [200, 150, 300, 280, 500, 700, 650]
}

A dictionary containing two keys: 'Day' (days of the week) and 'Sales' (corresponding sales figures).

3. Convert to DataFrame:



df = pd.DataFrame(data)

Converts the dictionary into a pandas DataFrame for easier plotting.

4. Apply a Plot Style (Optional):



plt.style.use('ggplot')

Applies the "ggplot" style for better aesthetics.

5. Create the Plot:



plt.figure(figsize=(10, 6))
plt.plot(df['Day'], df['Sales'], marker='o', linestyle='-', color='blue')

Initializes a figure with size 10x6 inches.

Plots a blue line with circular markers for each data point.

6. Add Labels and Title:



plt.title('Weekly Sales Report', fontsize=16)
plt.xlabel('Day of the Week')
plt.ylabel('Sales')
plt.grid(True)

Sets the title, x-label, y-label, and enables grid lines for better readability.

7. Save the Chart:



plt.savefig("sales_report.pdf")

Saves the chart as a PDF file named sales_report.pdf.

8. Display the Plot:



plt.show()

Displays the plot window.


---

✅ Output:

