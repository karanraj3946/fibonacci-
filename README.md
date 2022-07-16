num = int(input("How many fibonaci number you want to generate: "))
      a,b=0,1
      for i in range(num):
      a,b=a+b,a
      print(a,sep=”,”)
