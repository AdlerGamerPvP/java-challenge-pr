# Desafio Java — Estrutura de Decisão

Bem-vindo(a) ao repositório de desafios Java! Aqui você vai praticar **Estrutura de Decisão** em Java com exercícios práticos e variados.

---

## Como participar

1. Faça um **fork** deste repositório
2. Escolha **um exercício** da lista abaixo que ainda não foi resolvido por outro aluno
3. Leia o enunciado no arquivo `exercicios/XX.md`
4. Crie o arquivo `exercicios/XX.java` com a sua solução
5. Faça o **commit** e abra um **Pull Request**

---

## Lista de Exercícios

| # | Título | Estrutura |
|---|--------|-----------|
| [01](exercicios/01.md) | Par ou Ímpar | if/else |
| [02](exercicios/02.md) | Positivo, Negativo ou Zero | if/else |
| [03](exercicios/03.md) | Maior de Dois Números | if/else |
| [04](exercicios/04.md) | Maior de Três Números | if/else |
| [05](exercicios/05.md) | Aprovado ou Reprovado | if/else |
| [06](exercicios/06.md) | Calculadora Simples | switch |
| [07](exercicios/07.md) | Classificação de Triângulo | if/else |
| [08](exercicios/08.md) | Ano Bissexto | if/else |
| [09](exercicios/09.md) | Categoria por Idade | if/else |
| [10](exercicios/10.md) | Desconto por Valor de Compra | if/else |
| [11](exercicios/11.md) | Dia da Semana | switch |
| [12](exercicios/12.md) | Mês do Ano | switch |
| [13](exercicios/13.md) | Nota e Conceito | if/else |
| [14](exercicios/14.md) | IMC - Índice de Massa Corporal | if/else |
| [15](exercicios/15.md) | Velocidade e Multa | if/else |
| [16](exercicios/16.md) | Estação do Ano | switch |
| [17](exercicios/17.md) | Tipo de Veículo | if/else |
| [18](exercicios/18.md) | Nível de Combustível | if/else |
| [19](exercicios/19.md) | Turno do Funcionário | switch |
| [20](exercicios/20.md) | Validação de Senha Simples | if/else |
| [21](exercicios/21.md) | Tipo de Triângulo pelos Ângulos | if/else |
| [22](exercicios/22.md) | Maior e Menor entre Quatro Números | if/else |
| [23](exercicios/23.md) | Classificação de Temperatura | if/else |
| [24](exercicios/24.md) | Tarifas de Energia Elétrica | if/else |
| [25](exercicios/25.md) | Jogo Pedra, Papel e Tesoura | if/else |
| [26](exercicios/26.md) | Nível de Experiência de Jogador | if/else |
| [27](exercicios/27.md) | Tipo Sanguíneo e Doação | switch |
| [28](exercicios/28.md) | Placar de Futebol | if/else |
| [29](exercicios/29.md) | Calculadora de Gorjeta | switch |
| [30](exercicios/30.md) | Categoria de Produto | switch |
| [31](exercicios/31.md) | Validade de Data Simples | if/else |
| [32](exercicios/32.md) | Tipo de Conta Bancária | switch |
| [33](exercicios/33.md) | Faixa de Renda e Imposto | if/else |
| [34](exercicios/34.md) | Classificação de Filmes por Faixa Etária | if/else |
| [35](exercicios/35.md) | Resultado de Operação Bancária | switch |
| [36](exercicios/36.md) | Tipo de Clima por Temperatura e Umidade | if/else |
| [37](exercicios/37.md) | Pontuação e Medalha | if/else |
| [38](exercicios/38.md) | Verificação de Intervalo | if/else |

---

## Estrutura do Repositório

```
desafio-java/
├── README.md
└── exercicios/
    ├── 01.md       ← enunciado
    ├── 01.java     ← sua solução (você cria!)
    ├── 02.md
    ├── 02.java
    └── ...
```

---

## Exemplo de solução

```java
import java.util.Scanner;

public class Main {
    public static void main(String[] args) {
        Scanner sc = new Scanner(System.in);
        int numero = sc.nextInt();

        if (numero % 2 == 0) {
            System.out.println("O número " + numero + " é par.");
        } else {
            System.out.println("O número " + numero + " é ímpar.");
        }
    }
}
```

---

Bons estudos! ☕
