# Desafio de Controle de Fluxo - DIO

## ✨ Descrição

Este projeto faz parte da trilha **Java Básico** da **Digital Innovation One (DIO)**. O objetivo é praticar conceitos de **controle de fluxo** em Java por meio de um desafio que envolve manipulação de entrada de dados e laços de repetição.

---

## 💡 Regras do Desafio

1. O programa solicita dois números inteiros via terminal.
2. Se o **primeiro número for maior que o segundo**, o sistema lança uma exceção personalizada `ParametrosInvalidosException`.
3. Caso contrário, o programa imprime a sequência de números da diferença entre os dois valores informados.

---

## 📄 Exemplo de Execução

### ✅ Entrada válida:
```
Digite o primeiro parâmetro:
5
Digite o segundo parâmetro:
10
```
### 📝 Saída esperada:
```
Imprimindo o número 1
Imprimindo o número 2
Imprimindo o número 3
Imprimindo o número 4
Imprimindo o número 5
```

### ❌ Entrada inválida:
```
Digite o primeiro parâmetro:
20
Digite o segundo parâmetro:
10
```
### 📝 Saída esperada:
```
Exceção capturada: O segundo parâmetro deve ser maior que o primeiro
```

---

## 🛠️ Tecnologias Utilizadas
- Java 8+
- Scanner para entrada de dados
- Estruturas de controle (`for`, `if`)
- Tratamento de exceções (`try-catch`)

---

## 📁 Estrutura do Projeto
```
ó DesafioControleFluxo
  ├── Contador.java
  ├── ParametrosInvalidosException.java
  └── README.md
```

### 📝 Explicação dos arquivos:
- **`Contador.java`**: Contém a lógica principal do programa, incluindo a captura de entrada do usuário e a execução do loop de contagem.
- **`ParametrosInvalidosException.java`**: Classe de exceção personalizada para validar a entrada dos parâmetros.
- **`README.md`**: Documentação do desafio e instruções de execução.

---

## 🛠️ Como Executar o Projeto

1. **Clone o repositório** ou baixe os arquivos manualmente:
   ```bash
   git clone https://github.com/seu-usuario/desafio-controle-fluxo
   cd desafio-controle-fluxo
   ```
2. **Compile o projeto**:
   ```bash
   javac Contador.java ParametrosInvalidosException.java
   ```
3. **Execute o programa**:
   ```bash
   java Contador
   ```

---

## 👨‍💻 Autor

Este desafio foi criado por **Gleyson Sampaio** e faz parte da plataforma [DIO](https://www.dio.me/).  

📅 **Modificações e melhorias realizadas por:**  
[Calebe Werneck Couto] - *cwc3d.net* 🚀

---

