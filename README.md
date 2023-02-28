from excel import OpenExcel
f = OpenExcel('test.xls')
f.read(sku) # read all
f.read('nombre') # read 'nonbre' row
f.read(piieza) # f.read('pieza'), read 'pieza' column
f.read('producto') # read 'producto' position
write excel: todo
