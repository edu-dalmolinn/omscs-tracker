# Tasks — Artefatos e achados

Informações relevantes que surgiram ao executar as tasks. A fonte principal continua sendo o `tasks.md`. Este documento guarda o que descobrimos ao longo do caminho.

**Última atualização:** 23/11/2026 (Semana 1)

> Este repositório é publicado no GitHub Pages. Por isso o documento **não** traz dados pessoais (matrícula, CPF, data de nascimento, notas).

---

## Semana 1

### 1. Documentos acadêmicos em inglês

**O que a UnB oferece (SAA, saaatendimento@unb.br).** Para quem se formou a partir de 1/2020, a SAA emite em inglês:
- histórico escolar, que traz as disciplinas e o status "formado";
- declaração de tradução do diploma, com os mesmos dizeres do diploma em português.

**Situação:**
- [x] Ler as páginas oficiais da Georgia Tech sobre tradução e envio de documentos.
- [x] Diploma e histórico em português salvos no drive.
- [x] E-mail à SAA pedindo o histórico e a declaração de tradução do diploma em inglês. A primeira tentativa foi bloqueada (23/11/2026) porque o endereço foi digitado errado (`saaantedimento`). Foi reenviado para `saaatendimento@unb.br` com sucesso. Para histórico e diploma, o portal da UnB também cita `rdgsaa@unb.br` (a confirmar), caso não haja resposta.
- [ ] Aguardar a resposta da SAA e conferir se os documentos são oficiais, com código de verificação.

**O que a Georgia Tech pede** (resumo de fontes da web, que complementam o plano):
- Na candidatura, o FAQ do OMSCS pede o histórico no idioma original **e** uma tradução em inglês, que pode ser não oficial. Depois da admissão, pede-se uma cópia oficial para conferência.
- A regra geral da Graduate Education diz: se a instituição emite documentos oficiais em inglês, não é preciso enviar a versão em português nem tradução. Se não emite, é preciso uma tradução juramentada, feita por um serviço profissional e palavra por palavra.
- A página do Brasil lista só a qualificação aceita (Bacharel, com pelo menos 5 anos de estudo). Ela não cita outros documentos nem avaliação de credenciais.
- Na candidatura, anexe o diploma se o histórico não informar o grau concedido e a data da concessão.

**Impacto no plano:**
- Se a UnB emitir os documentos oficialmente em inglês, a tradução juramentada das Semanas 4 e 5 provavelmente não será necessária. Confirmar no portal da candidatura (Semana 10).
- O histórico completo em PDF (37 páginas) traz o código de verificação de autenticidade da UnB, com validação em sig.unb.br.

**Fontes:**
- [OMSCS Prospective Student FAQs](https://omscs.gatech.edu/prospective-student-faqs)
- [Georgia Tech Grad, Before You Apply](https://grad.gatech.edu/admissions/international/before-you-apply)
- [Georgia Tech Grad, Ready to Apply — etapa 4: envio na candidatura](https://grad.gatech.edu/admissions/international/ready-to-apply)
- [Georgia Tech Grad, After You Apply — etapa 9: envio após a admissão](https://grad.gatech.edu/admissions/international/after-you-apply)
- [Country-Specific Requirements](https://grad.gatech.edu/admissions/international/country-specific-requirements)
- [Academic Documents and Credential Evaluations](https://catalog.gatech.edu/admissions/grad/academic-documents-evaluations/) (não consegui abrir esta página)

---

### 2. Ementas das disciplinas de computação e afins

O "histórico completo" da UnB já traz a ementa da maioria das disciplinas. A task foi concluída: 6 das 7 disciplinas listadas têm ementa, e EPR0022 não existe em lugar nenhum.

| Disciplina | Fonte | O que comprova | O que **não** comprova |
|---|---|---|---|
| **CIC0007**, Introdução à Ciência da Computação (60 h) | Histórico | Pensamento computacional, variáveis, condicionais, laços, vetores, funções, estruturas heterogêneas e arquivos | Recursão, estruturas de dados, complexidade, OO. A linguagem não é citada |
| **EST0001**, Computação em Estatística 1 (30 h) | Histórico | Programação em **R**: importação e manipulação de dados, estatística descritiva e visualização | Programação de propósito geral |
| **EPR0072**, Sistemas de Informação em Eng. de Produção (60 h) | Histórico | Sistemas de informação, ERP/CRM, DSS e noções de IA empresarial | Programação (o foco é gerencial) |
| **EPR0066**, Pesquisa Operacional em Engenharia 1 (90 h) | Histórico | Programação linear, inteira e não linear, **teoria dos grafos**, modelos estocásticos, teoria da decisão e filas | Implementação em código |
| **EPR0004**, Simulação de Sistemas (60 h) | Histórico | Técnicas de simulação com **implementação de algoritmos** | Linguagem usada |
| **EPR0027**, Tópicos Especiais em PO (60 h, 2025.2) | Slides da aula 1 (PDF do professor) | Introdução à Ciência de Dados: análise univariada e multivariada, dados faltantes e outliers, Machine Learning supervisionado (regressão linear, árvores de decisão, KNN, métricas). Pré-requisito declarado: Python básico | Não é ementa oficial: mostra o que estava previsto, não o que você de fato usou. A ementa no histórico diz só "Variável" |
| **EPR0022**, Sistemas de Suporte à Decisão (60 h, 2026.1) | — | — | Sem ementa no histórico e sem contato com o professor. **Não usar como comprovação** |

**Disciplinas de matemática que ficaram fora da lista e valem entrar no mapa da Semana 3:**
- **Cálculo 1, 2 e 3** (MAT0025, MAT0026, MAT0027) e **Álgebra Linear** (MAT0031).
- **Probabilidade e Estatística** (EST0023, 60 h): variáveis aleatórias, distribuições, estimação e testes de hipóteses. É uma base de probabilidade mais forte que a do EST0001.

**Lacuna principal:** o histórico não tem nenhuma disciplina de OO, de estruturas de dados e algoritmos ou de complexidade. Isso justifica a escolha de OOP/Java e DSA como formação complementar (Semana 2).

**Detalhes do EPR0027 (slides):**
- Docente com pós-doutorado em Inteligência Computacional.
- Quatro atividades em aula (50%) e dois relatórios técnicos com apresentação oral (50%).
- Bibliografia: Géron, *Hands-On Machine Learning with Scikit-Learn, Keras, and TensorFlow*.

---

## Pendências em aberto

- [ ] Revisar o que você lembra de CIC0007 e EST0001: linguagem, projetos, recursão ou estruturas de dados.
- [ ] Lembrar o que foi de fato feito no EPR0027 (linguagem, projetos, relatórios). Esse registro é a evidência de Python e ML para o currículo.
- [ ] Resposta da SAA com os documentos em inglês.
- [ ] Simulado de IELTS, carga semanal e orçamento, e o e-mail aos recomendantes (os três do `tasks.md`).

## Para as próximas semanas

- **Semana 2:** usar a lacuna acima (OO, estruturas de dados, algoritmos) para escolher entre a rota universitária e os certificados GTx.
- **Semana 3:** montar o mapa das ementas com a tabela acima e incluir MAT0025/26/27, MAT0031 e EST0023.
- **Currículo e respostas curtas:** citar EPR0066 (grafos e otimização), EPR0004 (simulação) e EPR0027 (ML) com o que você realmente fez.
