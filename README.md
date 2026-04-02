# 📄 Facade Pattern (Padrão de Projeto Estrutural)

Resenha e reflexão acadêmica sobre o padrão de projeto Facade, produzida como atividade da disciplina de Projeto de Software.

---

## 👨‍🎓 Informações Acadêmicas

| Campo | Informação |
|---|---|
| **Aluno** | Luiz Fernando Batista Moreira |
| **Curso** | Engenharia de Software |
| **Semestre** | 4º Semestre |
| **Instituição** | PUC Minas |
| **Disciplina** | Projeto de Software |
| **Professor** | João Paulo Aramuni |

---

## 📖 Sobre o Padrão

O **Facade** é um padrão de projeto estrutural que resolve um problema bastante comum no desenvolvimento de software: a necessidade de integrar um projeto a um framework ou biblioteca de terceiros que, por mais robusta que seja, exige a inicialização de dezenas de objetos, o gerenciamento de dependências complexas e a garantia de uma ordem exata de execução. O resultado disso, sem o padrão, é uma regra de negócio fortemente acoplada aos detalhes de implementação da biblioteca externa.

A ideia central é criar uma classe intermediária que esconde toda essa complexidade e entrega ao restante do sistema apenas o que realmente importa. Uma boa analogia é pensar em ligar para uma loja grande para fazer um pedido: o atendente é a fachada. Você não precisa ir até o estoque, processar o pagamento ou coordenar a entrega. Você só fala o que quer, e ele resolve o resto nos bastidores.

Conceitos discutidos neste trabalho:

- O problema do alto acoplamento com bibliotecas externas
- Estrutura do padrão Facade (Cliente x Fachada x Subsistema)
- Organização de sistemas em camadas via fachadas
- Vantagens de manutenção e isolamento
- Riscos do antipadrão God Object
- Diferença entre Facade e Adapter
- Uso combinado com o padrão Singleton

---

## 🔗 Referência Principal

A referência utilizada para este trabalho foi a documentação do Refactoring Guru, uma das fontes mais completas e didáticas sobre padrões de projeto disponíveis na web:

📎 [refactoring.guru/pt-br/design-patterns/facade](https://refactoring.guru/pt-br/design-patterns/facade)

Repositório do professor João Paulo Aramuni:

🐙 [github.com/joaopauloaramuni](https://github.com/joaopauloaramuni)

---

## 💡 Por que você deveria estudar esse padrão?

Se você já teve que integrar seu projeto com uma biblioteca externa e sentiu que o código ficou difícil de manter, cheio de dependências espalhadas por todo lado, o Facade é exatamente o que você precisa conhecer. Ele não resolve a complexidade, mas te dá uma forma elegante e organizada de lidar com ela, concentrando tudo em um único ponto.

Além disso, entender o Facade abre caminho para discussões mais profundas sobre acoplamento, coesão e arquitetura em camadas, temas que aparecem constantemente em projetos reais e em entrevistas técnicas.

---

## ✍️ Sobre o Trabalho

Este repositório acompanha uma análise crítica do padrão Facade, conectando seus conceitos com situações práticas do desenvolvimento de software moderno. O trabalho também traça uma comparação entre o Facade e outros padrões relacionados, como o **Adapter** e o **Singleton**, e discute os limites do padrão, incluindo o risco de transformar a classe Facade em um **God Object** caso não sejam impostos limites adequados de responsabilidade.

---

*Atividade acadêmica — 4º Semestre de Engenharia de Software, PUC Minas, 2025.*
