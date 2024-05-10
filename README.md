# CodeAlpha_project_task1_fabonacciSeries

def GenerateFibonacci(n):
    FibonacciSeries = []
    a , b = 0 , 1
    for i in range(n):
        FibonacciSeries.append(a)
        a , b = b , a+b
    return  FibonacciSeries

def main ():

    FibonacciSeries = GenerateFibonacci(n)
    print(f"Fibonacci Series : {FibonacciSeries}")

n = int(input("Please Enter The Number Of Fibonacci Numbers to Generate :  "))

if __name__ == "__main__":
    main()





