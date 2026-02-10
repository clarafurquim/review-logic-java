# Entrada e Saída de dados (I/O) em Java

Basicamente é a forma como seu programa recebe **informações (entrada)** e como ele mostra informações **(saída)**

---

## 1) Saída

O objeto **System.out** representa a saída padrão, permitindo exibir dados no console quando executamos uma aplicação em Java. O System.ou possui diversos métodos para gerar saídas, sendo os mais utilizadosos métodos **println**, **printf**, e **print**.

## ✅ Método println()

O método System.out.println() gera uma string de texto, cria uma nova linha abaixo da atual e então posiciona o cursor nesta linha.

**Exemplos**

```
System.out.println("O Inter vai sair campeão);
System.out.println("Meu segunto println em java");
```
## ✅ Método printf()

O método System.out.printf() mostra os dados na saída formatados. Um especificador de formato se inicia com símbolo %, seguido por uma caractere que representa o tipo de dado.

**Exemplos**

```
Double numDecimal = 23.8954;
int minhaIdade = 29;
String Meunome = "Vini Jr";
char inter = "I";

System.out.printf("Número = %.2f%n", NumDecimal);
System.out.printf("Idade = %.2d%n", minhaIdade);
System.out.printf("Meu nome = %.2s%n", meuNome);
System.out.printf("Primeira letra = %C", inter);

```