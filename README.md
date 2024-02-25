# PRACT3---Serie-de-Fibonnacci
# Suarez Canche Isaac Moises 3SB

def fibonacci(n):
    a, b = 0, 1
    for _ in range(n):
        print(a)
        a, b = b, a + b

fibonacci(10)

#Conclusion:
La funcion de este codigo es que genera la serie de Fibonacci hasta un número n, en la que cada número es la suma de los dos anteriores, en este caso empezamos desde 0 a 1 siendo a y b, el codigo de repetira n veces, en este caso se repetira 10 y como resultado nos dara 34.
