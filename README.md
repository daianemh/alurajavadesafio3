
# 💳 Aplicação de Compras & Cartão de Crédito

Este é um projeto console em Java desenvolvido como parte do treinamento da **Alura**. A aplicação simula o funcionamento de um cartão de crédito, onde o usuário pode lançar compras, verificar o saldo disponível em tempo real e visualizar o extrato final ordenado pelo valor dos itens.

## 🚀 Funcionalidades

* **Definição de Limite:** Permite definir o limite inicial do cartão.
* **Controle de Saldo:** Valida se há saldo suficiente antes de aprovar cada compra.
* **Histórico de Compras:** Registra todas as compras aprovadas.
* **Ordenação Automática:** Exibe o extrato final de compras ordenado de forma crescente pelo **valor** (do menor para o maior).

---

## 🛠️ Tecnologias e Conceitos Utilizados

* **Java 8+**
* **Orientação a Objetos (OO):** Encapsulamento, construtores e métodos de classe.
* **Coleções (`List` e `ArrayList`):** Para o armazenamento dinâmico das compras.
* **Interface `Comparable`:** Implementada na classe `Compra` para permitir a ordenação customizada através do método `Collections.sort()`.

---

## 📦 Estrutura do Código

O projeto é composto por três classes principais:

1.  **`Principal.java`**: Contém o método `main`, gerencia a interação com o usuário via terminal (`Scanner`) e exibe o extrato final.
2.  **`CartaoDeCredito.java`**: Responsável por armazenar os dados do cartão (limite, saldo e lista de compras) e validar a lógica de novos lançamentos.
3.  **`Compra.java`**: Modela os itens comprados (descrição e valor) e implementa a ordenação baseada no preço do item.

---

## 💻 Como Executar

### Pré-requisitos
* Possuir o Java JDK instalado (versão 8 ou superior).

### Passo a Passo
1. Clone o repositório ou baixe os arquivos de código.
2. Abra o terminal na pasta onde os arquivos `.java` estão salvos.
3. Compile as classes:
   ```bash
   javac Principal.java CartaoDeCredito.java Compra.java

```

4. Execute o programa:
```bash
java Principal

```



---

## 📝 Exemplo de Uso

```text
Digite o limite do cartão: 
1000
Digite a descrição da compra:
Teclado
Digite o valor da compra:
150
Compra realizada!
Digite 0 para sair ou 1 para continuar
1
Digite a descrição da compra:
Monitor
Digite o valor da compra:
700
Compra realizada!
Digite 0 para sair ou 1 para continuar
0

***********************
COMPRAS REALIZADAS:

Teclado - 150.0
Monitor - 700.0

***********************

Saldo do cartão: 150.0

```

---

💡 *Projeto desenvolvido para fins didáticos durante os estudos de Java na Alura.*

```

```
