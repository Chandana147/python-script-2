# python-script-2
Transforming the data present in ‘Sample Input’ CSV into ‘Sample Output’ CSV using Python.
import csv
file = open('Sample_input.csv')
file = open('Sample_output.csv')

type(file)
csvreader = csv.reader(file)
header = []
header = next(csvreader)
header
rows = []
for row in csvreader:
        rows.append(row)
rows
Sample_input = Sample_output
file.close()
