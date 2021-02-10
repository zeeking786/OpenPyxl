# OpenPyxl

This Python code is used to connect python with excel/create the excel sheet with an easy and proper GUI format for understandable usage of it.

You can use it by just installing the module named as :

`pip install openpyxl`

After this create an empty excel file under the project folder and run by giving path of that excel file in your code just like I have give Try it in same manner !

You can also try this basic code for reference :

```from openpyxl import Workbook  
import time  
  
wb = Workbook()  
sheet = wb.active  
  
sheet['A1'] = 87  
sheet['A2'] = "Devansh"  
sheet['A3'] = 41.80  
sheet['A4'] = 10  
  
now = time.strftime("%x")  
sheet['A5'] = now  
  
wb.save("sample_file.xlsx") 
```

You can do anything with excel by using this module this will help you to create your data faster and in efficient manner.
