1. sys.argv：获得当前py的所有参数,返回list，第一个参数数是脚本本身，之后是脚本参数。 


####csv  
`import csv`  
1. open file  
2. csv.reader(file,delimiter=';') 读取文件内容，返回一个迭代。  
3. 使用for...in  或者csv.next() 对一行csv内容进行处理。  
