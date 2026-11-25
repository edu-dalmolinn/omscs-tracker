# Tasks — Artefatos e achados

Informações relevantes que surgiram ao executar as tasks. A fonte principal continua sendo o `tasks.md`. Este documento guarda o que descobrimos ao longo do caminho.

**Última atualização:** 25/11/2026 (Semana 1)

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
| **CIC0007**, Introdução à Ciência da Computação (60 h) | Histórico e relato sobre a turma | Programação em **Python**: pensamento computacional, variáveis, condicionais, laços, vetores, funções, estruturas heterogêneas e arquivos | Recursão, estruturas de dados, complexidade, OO. |
| **EST0001**, Computação em Estatística 1 (30 h) | Histórico | Programação em **R**: importação e manipulação de dados, estatística descritiva e visualização | Programação de propósito geral |
| **EPR0072**, Sistemas de Informação em Eng. de Produção (60 h) | Histórico | Sistemas de informação, ERP/CRM, DSS e noções de IA empresarial | Programação (o foco é gerencial) |
| **EPR0066**, Pesquisa Operacional em Engenharia 1 (90 h) | Histórico | Programação linear, inteira e não linear, **teoria dos grafos**, modelos estocásticos, teoria da decisão e filas | Implementação em código |
| **EPR0004**, Simulação de Sistemas (60 h) | Histórico | Técnicas de simulação com **implementação de algoritmos** | Linguagem usada |
| **EPR0027**, Tópicos Especiais em PO (60 h, 2025.2) | Slides da aula 1 (PDF do professor) | Introdução à Ciência de Dados: análise univariada e multivariada, dados faltantes e outliers, Machine Learning supervisionado (regressão linear, árvores de decisão, KNN, métricas). Pré-requisito declarado: Python básico | Não é ementa oficial: mostra o que estava previsto, não o que você de fato usou. A ementa no histórico diz só "Variável" |
| **EPR0022**, Sistemas de Suporte à Decisão (60 h, 2026.1) | — | — | Sem ementa no histórico e sem contato com o professor. **Não usar como comprovação** |

**Relato sobre as turmas cursadas**

- [x] **CIC0007:** a turma usou Python e seguiu o conteúdo da ementa. Não houve projeto, recursão nem estudo de estruturas de dados além do conteúdo listado, como vetores e estruturas heterogêneas.
- [x] **EST0001:** a turma usou R e seguiu o conteúdo da ementa, sem projeto, recursão ou estudo de estruturas de dados além do que consta nela.

**Disciplinas de matemática que ficaram fora da lista e valem entrar no mapa da Semana 3:**
- **Cálculo 1, 2 e 3** (MAT0025, MAT0026, MAT0027) e **Álgebra Linear** (MAT0031).
- **Probabilidade e Estatística** (EST0023, 60 h): variáveis aleatórias, distribuições, estimação e testes de hipóteses. É uma base de probabilidade mais forte que a do EST0001.

**Lacuna principal:** o histórico não tem nenhuma disciplina de OO, de estruturas de dados e algoritmos ou de complexidade. Isso justifica a escolha de OOP/Java e DSA como formação complementar (Semana 2).

**Detalhes do EPR0027 (slides):**
- Docente com pós-doutorado em Inteligência Computacional.
- Quatro atividades em aula (50%) e dois relatórios técnicos com apresentação oral (50%).
- Bibliografia: Géron, *Hands-On Machine Learning with Scikit-Learn, Keras, and TensorFlow*.

### 3. Simulado de IELTS Academic

Simulado completo das quatro habilidades, concluído em 25/11/2026.

| Habilidade | Simulado (25/11/2026) | Mínimo da Georgia Tech | Situação |
|---|---|---|---|
| Listening | **6,5** | 6,5 | No limite do mínimo, sem folga |
| Reading | **7,5** | 6,5 | 1,0 acima do mínimo |
| Writing | **5,5** | 5,5 | No limite do mínimo, sem folga |
| Speaking | **5,5** | 6,5 | **1,0 abaixo do mínimo** |
| Geral (média) | **6,5** (6,25 arredondado) | 7,0 (o `tasks.md` registra 7,5; a confirmar) | **0,5 abaixo do mínimo** |

**Leitura do resultado:**
- **Geral abaixo do mínimo:** a média é 6,25, que o IELTS arredonda para 6,5. Faltam 0,5 para o 7,0 (ou 1,0 para o 7,5 do `tasks.md`).
- **Speaking reprova no critério por habilidade:** 5,5 está 1,0 abaixo do mínimo de 6,5. É o principal ponto a melhorar.
- **Listening e Writing estão exatamente no mínimo,** sem folga: uma pequena oscilação no dia da prova os deixa abaixo. O Reading (7,5) é o único com folga.
- **Prioridade do plano de estudo:** Speaking primeiro, depois Writing e Listening. Subir esses três em 0,5 a 1,0 cada leva a média para perto de 7,0.
- O simulado não é a prova oficial, e a correção de Writing e Speaking pode variar. Vale repetir um simulado depois de algumas semanas de estudo.

### 4. Mensagem de convite aos recomendantes

Modelo de WhatsApp para o supervisor técnico do trabalho, que acompanhou meu trabalho por mais de um ano. O nome fica como `[nome]` porque o repositório é público. Para o orientador do TCC e o professor de Pesquisa Operacional, adaptar a justificativa.

> Boa tarde, [nome]!
>
> Estou preparando minha candidatura para um mestrado em Ciência da Computação na universidade americana Georgia Tech e queria saber se você poderia escrever uma carta de recomendação para mim. Pensei em você porque foi meu gerente por mais de um ano e acompanhou de perto o meu trabalho no BB.
>
> Se topar, vou cadastrar o seu email e a própria universidade vai entrar em contato com você para combinar o envio. Você acha que consegue escrever essa carta até o dia 31 de janeiro de 2027?
>
> Caso ajude, posso te enviar meu currículo e um resumo do que fizemos juntos.
>
> Obrigado desde já!

- [ ] Enviar ao supervisor do trabalho (prazo do convite: 30/11).
- [ ] Adaptar e enviar ao orientador do TCC.

**Modelo para o professor com quem a relação foi menos próxima.** Reforça em quais disciplinas ele foi meu professor e dá uma saída fácil, para ele recusar sem constrangimento se não se sentir à vontade. Preencher `[nome]` e as disciplinas.

> Boa tarde, professor [nome]!
>
> Estou preparando minha candidatura para um mestrado em Ciência da Computação na universidade americana Georgia Tech e queria saber se o senhor poderia escrever uma carta de recomendação para mim. Pensei no senhor porque fui seu aluno em [disciplinas] e as matérias foram importantes na minha preparação para essa área.
>
> Sei que não tivemos um contato muito próximo, então, se preferir não escrever, fique à vontade, sem problema nenhum. Se topar, posso enviar meu currículo, meu histórico e um resumo dos trabalhos que fiz nas disciplinas para facilitar.
>
> Nesse caso, vou cadastrar o seu email e a própria universidade vai entrar em contato com o senhor para combinar o envio. O senhor acha que consegue escrever essa carta até o dia 31 de janeiro de 2027?
>
> Obrigado desde já!

- [ ] Enviar ao professor de Pesquisa Operacional.

---

A carga semanal está confirmada em **18 h** (10 h de computação, 6 h de IELTS e 2 h de documentos).

## Pendências em aberto

- [ ] Lembrar o que foi de fato feito no EPR0027 (linguagem, projetos, relatórios). Esse registro é a evidência de Python e ML para o currículo.
- [ ] Resposta da SAA com os documentos em inglês.
- [ ] Convidar os três recomendantes (modelos no item 4, falta só o do orientador do TCC).

## Para as próximas semanas

- **Semana 2:** usar a lacuna acima (OO, estruturas de dados, algoritmos) para escolher entre a rota universitária e os certificados GTx.
- **Semana 3:** montar o mapa das ementas com a tabela acima e incluir MAT0025/26/27, MAT0031 e EST0023.
- **Currículo e respostas curtas:** citar EPR0066 (grafos e otimização), EPR0004 (simulação) e EPR0027 (ML) com o que você realmente fez.
