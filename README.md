# sherin-Exp-4
from pandas import read_csv
from matplotlib import pyplot
series=read_csv(r'C:\Users\sheri\Downloads\daily-total-female-births.csv')
print(series.head())
series.plot()
pyplot.show()
![Screenshot (67)](https://github.com/user-attachments/assets/43557e17-872e-4a54-96ca-8113141d2a32)
series.plot(style='-.')
pyplot.show()![Screenshot (68)](https://github.com/user-attachments/assets/808f544e-c0b6-42a7-bd4e-5c4eeee01d3d)
series.hist()
pyplot.show()
![Screenshot (69)](https://github.com/user-attachments/assets/d0b814f7-ab6e-43bb-9975-38c1c9a930e9)
series.plot(kind='kde')
pyplot.show()
![Screenshot (71)](https://github.com/user-attachments/assets/d108112f-d9da-4712-b99b-26b83f7532b2)
