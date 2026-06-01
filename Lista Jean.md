# Lista Jean



#### 1\)



**numero = int(input("Digite um numero inteiro: "))**

**primo = True**

**if numero <= 1:**

&#x20;   **primo = False**

**else:**

&#x20;   **for i in range(2, numero):**

&#x20;       **if numero % i == 0:**

&#x20;           **primo = False**



**if primo:**

&#x20;   **print("é primo")**

**else:**

&#x20;   **print("não é primo")**



#### 2\)



**numero = int(input("Digite um numero inteiro: "))**

**primo = True**

**divisores = \[]**

**if numero <= 1:**

&#x20;   **primo = False**

**else:**

&#x20;   **for i in range(2, numero):**

&#x20;       **if numero % i == 0:**

&#x20;           **primo = False**

&#x20;           **divisores.append(i)**



**if primo:**

&#x20;   **print("é primo")**

**else:**

&#x20;   **print("não é primo")**

&#x20;   **if len(divisores) > 0:**

&#x20;       **print("é divisivel por:", divisores)**



#### 3\)



**n = int(input("Digite um numero: "))**

**divisoes = 0**

**print("Numeros primos entre 1 e", n, ":")**

**for num in range(2, n + 1):**

&#x20;   **primo = True**

&#x20;   **for i in range(2, num):**

&#x20;       **divisoes += 1**       

&#x20;       **if num % i == 0:**

&#x20;           **primo = False**

&#x20;           

&#x20;   **if primo:**

&#x20;       **print(num)**

**print("numeros de divisoes feitas:", divisoes)**





#### 4\)



**n = int(input("Quantas notas serao informadas? "))**

**soma = 0**

**for i in range(n):**

&#x20;   **nota = float(input(f"Digite a {i+1}ª nota: "))**

&#x20;   **soma += nota**

**media = soma / n**

**print("Media aritmetica: ", media)**





&#x20;   

