# Projeto Aplicado: Ciência de Dados para a Inclusão Financeira 💳

## 📑 Sumário
* [Visão Geral](#-visão-geral)
* [🎥 Vídeo de Apresentação (Storytelling)](#-vídeo-de-apresentação-storytelling)
* [A Empresa: Nubank](#-a-empresa-nubank)
* [Ligação com os Objetivos de Desenvolvimento Sustentável (ODS)](#ligação-com-os-objetivos-de-desenvolvimento-sustentável-ods)
* [📊 Principais Descobertas Analíticas (AED)](#-principais-descobertas-analíticas-aed)
* [📈 Propósito do Estudo](#-propósito-do-estudo)
* [📁 Estrutura do Repositório](#-estrutura-do-repositório)
* [👥 Membros do Grupo (Integrantes)](#-membros-do-grupo-integrantes)

---

## 🎯 Visão Geral
Este repositório é dedicado ao desenvolvimento de um estudo focado em como a Ciência de Dados pode atuar como ferramenta de transformação social. O objetivo central é analisar o papel das fintechs na superação de barreiras de acesso e na promoção de uma economia mais justa e inclusiva, utilizando algoritmos para democratizar o acesso ao capital.

## 🎥 Vídeo de Apresentação (Storytelling)
Assista à apresentação completa em vídeo detalhando toda a narrativa estruturada do projeto, as análises exploratórias desenvolvidas e o impacto social gerado em conformidade com as diretrizes da ODS 10:

[![Assista no YouTube](https://img.youtube.com/vi/eR2JQ7C2Rno/0.jpg)](https://youtu.be/eR2JQ7C2Rno)

> 💡 *Clique na imagem acima para assistir à defesa do projeto e ao vídeo do Storytelling diretamente no YouTube.*

## 🏢 A Empresa: Nubank
O Nubank foi selecionado como objeto de estudo por sua abordagem nativa de dados e por sua missão de desafiar o status quo do sistema bancário tradicional. A instituição se destaca por empregar inteligência artificial, Machine Learning e Big Data para processar informações de forma multifatorial, garantindo análises de risco mais humanas e personalizadas.

## 🌍 Ligação com os Objetivos de Desenvolvimento Sustentável (ODS)
O projeto está diretamente conectado ao **ODS 10 – Redução das Desigualdades**. O foco da pesquisa é investigar as **Barreiras à Inclusão e a Precificação Punitiva** do mercado tradicional, provando empiricamente que modelos preditivos éticos conseguem neutralizar vieses históricos e oferecer segundas chances reais de reintegração financeira.

## 📊 Principais Descobertas Analíticas (AED)
A análise exploratória foi realizada em uma base robusta de **32.581 registros** e revelou três grandes pilares empíricos:

1. **Pulverização Democrática do Capital:** Constatou-se que **66,1%** de toda a base de clientes acessa microcréditos de até \$10.000, provando o foco do modelo na democratização e distribuição de recursos.
2. **Mérito Presente vs. Estigma Passado:** O cálculo de Pearson entre o histórico negativo anterior e a inadimplência atual gerou uma correlação fraca de **0,1791**. O cruzamento de dados quebrou a lógica de exclusão automática: a maioria absoluta dos clientes com default anterior (**3.573 pessoas**) mantém suas contas rigorosamente em dia, enquanto um grupo expressivo com histórico totalmente limpo (**4.936 pessoas**) está inadimplente no contrato vigente. Isso prova que o modelo avalia o risco pelo comportamento ativo e mérito atual do usuário.
3. **Neutralização de Juros Punitivos:** As correlações lineares entre Renda Pessoal vs. Taxa de Juros (**0,0008**) e Tempo de Histórico de Crédito vs. Taxa de Juros (**0,0167**) ficaram coladas no zero, com linhas de tendência horizontais. Isso demonstra que o custo do capital não discrimina ou pune perfis vulneráveis ou novos entrantes no sistema.
4. **Qualidade e Ética dos Dados:** Foram identificados e devidamente tratados outliers críticos durante a etapa de higienização, como registros impossíveis de idade (144 anos) e tempo de emprego (123 anos), garantindo a justiça algorítmica.

## 📈 Propósito do Estudo
O estudo visa fornecer sustentação científica para provar que a tecnologia apoia o desenvolvimento social através de:
1. **Modelagem Multifatorial:** Superar as réguas rígidas do mercado tradicional por meio de análise de dados inteligente.
2. **Justiça na Avaliação:** Mitigar a exclusão automatizada e garantir o cumprimento de metas de equidade financeira.
3. **Pensamento Computacional:** Aplicação prática dos pilares de Decomposição, Abstração e Reconhecimento de Padrões em Banco de Dados.

## 📁 Estrutura do Repositório
O repositório está organizado da seguinte forma para garantir rastreabilidade:
* **`data/`**: Contém o *Credit Risk Dataset* utilizado para as análises descritivas e inferenciais.
* **`docs/`**: Relatórios formais do projeto (Proposta e Documentação Final) e o esqueleto de Storytelling.
* **`notebooks/`**: Códigos em Python desenvolvidos com Pandas e Seaborn contendo os cálculos e gráficos estatísticos.
* **`README.md`**: Guia executivo de apresentação do repositório.

## 👥 Membros do Grupo (Integrantes)
* **Marcos Costa Lima Araujo** - RA: 10746213

---
*Trabalho acadêmico desenvolvido para o componente curricular de Projeto Aplicado I do curso de Tecnologia em Banco de Dados da Universidade Presbiteriana Mackenzie (2026).*