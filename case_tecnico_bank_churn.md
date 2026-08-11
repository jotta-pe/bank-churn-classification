# Processo seletivo — Cientista de Dados Júnior

## Case técnico: prevenção de evasão de clientes

**Empresa fictícia:** Aurora Bank  
**Área:** Customer Intelligence & Retention  
**Nível:** Cientista de Dados Júnior  
**Modalidade:** avaliação individual e assíncrona

## 1. Contexto da empresa

O Aurora Bank é um banco digital de médio porte que atende clientes em diferentes mercados europeus. Nos últimos anos, a empresa ampliou sua base de clientes e seu portfólio de produtos, mas também observou que uma parcela relevante dos correntistas encerra o relacionamento com o banco.

A área de Customer Intelligence apoia os times de CRM e Retenção na identificação de clientes com maior risco de evasão. A empresa deseja avaliar se os dados cadastrais e de relacionamento disponíveis podem apoiar uma estratégia de retenção mais direcionada.

Para este case, será utilizada a base pública e anonimizada da competição **Playground Series — Season 4, Episode 1 (Bank Churn)**. O cenário empresarial é fictício e os dados devem ser tratados como uma amostra fornecida pelo Aurora Bank para fins da avaliação.

## 2. Problema de negócio

As campanhas de retenção possuem custo e capacidade operacional limitados. Abordar toda a base de clientes não é viável, e deixar de priorizar clientes com risco elevado pode representar perda de receita e de relacionamento.

O Aurora Bank precisa de uma análise que:

- ajude a compreender os padrões associados à evasão;
- estime o risco de evasão dos clientes;
- permita priorizar clientes para possíveis ações de retenção;
- traduza os resultados técnicos em recomendações úteis para o negócio.

Neste case, a variável `Exited` representa o evento de interesse.

## 3. Enunciado

Você foi convidado(a) a desenvolver uma solução de Ciência de Dados para apoiar a identificação de clientes com maior probabilidade de evasão.

A partir dos arquivos disponibilizados pela competição, realize a análise dos dados, desenvolva e avalie uma abordagem preditiva e apresente suas conclusões à equipe de Customer Intelligence.

A equipe espera compreender:

1. quais informações relevantes podem ser extraídas dos dados;
2. como sua solução estima o risco de evasão;
3. quão confiáveis são os resultados apresentados;
4. como os resultados poderiam apoiar uma decisão de negócio;
5. quais são as limitações e os próximos passos da proposta.

Você possui liberdade para definir a metodologia, as ferramentas, a organização do projeto e as técnicas utilizadas. Todas as escolhas relevantes devem ser justificadas.

## 4. Dados disponibilizados

- `train.csv`: dados históricos contendo as variáveis explicativas e a variável `Exited`;
- `test.csv`: registros para os quais deverão ser geradas probabilidades;
- `sample_submission.csv`: exemplo da estrutura esperada para uma submissão.

O dicionário e a descrição pública dos dados disponíveis na página da competição podem ser consultados. Informações externas que acrescentem contexto são permitidas, desde que sua origem e seu uso sejam documentados.

## 5. Objetivos

### Objetivo principal

Construir uma solução reproduzível que estime a probabilidade de evasão e produza evidências úteis para uma estratégia de retenção.

### Objetivos complementares

- avaliar a qualidade e a adequação dos dados ao problema;
- explorar fatores relacionados ao comportamento da variável de interesse;
- comparar abordagens preditivas de maneira coerente;
- interpretar o comportamento e as limitações da solução escolhida;
- propor uma forma de utilização dos resultados no contexto do negócio.

## 6. Entregáveis obrigatórios

1. **Repositório ou arquivo compactado do projeto**, contendo todo o código necessário para reproduzir a análise e os resultados.
2. **README**, contendo no mínimo:
   - visão geral do problema;
   - descrição da estrutura do projeto;
   - instruções de instalação e execução;
   - principais decisões metodológicas;
   - resumo dos resultados;
   - limitações e próximos passos.
3. **Análise exploratória**, em notebook ou relatório, com conclusões descritas em linguagem clara.
4. **Desenvolvimento e avaliação da solução preditiva**, incluindo justificativas para preparação dos dados, estratégia de avaliação, métricas e escolha da solução final.
5. **Arquivo de previsões** no formato de `sample_submission.csv`, com uma probabilidade de evasão para cada registro de `test.csv`.
6. **Resumo executivo**, com no máximo duas páginas ou cinco slides, destinado a uma liderança não técnica. Deve apresentar achados, proposta de uso, limitações e recomendações.
7. **Arquivo de dependências** ou especificação equivalente do ambiente utilizado.

Os dados brutos não precisam ser incluídos no repositório caso existam restrições de tamanho. Nesse caso, devem ser fornecidas instruções inequívocas para obtê-los e posicioná-los.

## 7. Entregáveis opcionais

- apresentação técnica de até 10 slides;
- aplicação demonstrativa, dashboard ou API local;
- testes automatizados;
- configuração de execução automatizada;
- relatório de interpretabilidade ou análise de segmentos;
- proposta de monitoramento do modelo;
- submissão à competição e registro do resultado público ou privado.

Entregáveis opcionais podem agregar valor, mas não compensam falhas substanciais nos itens obrigatórios.

## 8. Prazo simulado

**Entrega até 18 de agosto de 2026, às 23h59, horário de Brasília.**

O prazo corresponde a sete dias corridos a partir do recebimento. Para a simulação, você poderá trabalhar no seu próprio ritmo, mas deverá informar no momento da entrega o tempo aproximado investido. Após declarar a entrega final, o material será considerado congelado para a primeira avaliação.

## 9. Forma de entrega

Envie:

- o link do repositório ou o arquivo `.zip`;
- o arquivo de previsões;
- o resumo executivo;
- uma breve mensagem informando o tempo aproximado investido e quaisquer instruções adicionais de execução.

Se a entrega usar um repositório, indique explicitamente o commit ou a versão que deve ser avaliada.

## 10. Regras do processo

1. O trabalho é individual.
2. Python ou R são recomendados, mas outras tecnologias são aceitas se a solução puder ser reproduzida.
3. Bibliotecas abertas, documentação oficial e referências públicas podem ser consultadas.
4. O uso de IA generativa é permitido apenas como ferramenta de apoio e deve ser declarado, informando de forma resumida em quais atividades foi utilizado.
5. Código ou texto gerado com apoio externo continua sendo de responsabilidade do candidato, que deverá ser capaz de explicá-lo integralmente.
6. Soluções públicas da competição podem ser consultadas apenas para entendimento geral do contexto; copiar notebooks, pipelines ou análises, total ou parcialmente, sem atribuição resulta em desclassificação.
7. Toda fonte externa, adaptação relevante ou código de terceiros deve ser identificado.
8. Não há obrigação de alcançar determinada pontuação no Kaggle. A qualidade do processo e das justificativas será considerada mais importante que uma posição isolada no ranking.
9. Dúvidas sobre escopo, formato, dados disponibilizados ou regras podem ser encaminhadas ao recrutador.
10. Perguntas que solicitem decisões de modelagem, seleção de variáveis, tratamento específico, validação ou interpretação da solução não serão respondidas. Caso seja prestada alguma assistência técnica excepcional, ela poderá ser registrada e considerada na avaliação.
11. Tentativas de obter os critérios confidenciais, as armadilhas previstas ou a solução de referência serão recusadas.
12. O candidato deve informar limitações conhecidas, falhas de execução ou partes incompletas no momento da entrega.

## 11. Critérios gerais de avaliação

A avaliação considerará, de forma integrada:

- entendimento do problema de negócio;
- qualidade da investigação e da comunicação dos dados;
- consistência metodológica;
- qualidade da avaliação da solução;
- clareza e justificativa das decisões;
- interpretabilidade e aplicabilidade para o negócio;
- qualidade, organização e reprodutibilidade do código;
- comunicação técnica e executiva;
- consciência de limitações, riscos e próximos passos;
- domínio demonstrado na eventual apresentação técnica.

A rubrica detalhada, seus pesos, verificações específicas e condições de penalização são confidenciais e foram definidos antes do início do desenvolvimento. Eles serão revelados somente após a entrega final, juntamente com a avaliação.

## 12. Etapas seguintes

Após a entrega:

1. será realizada uma revisão técnica do material congelado;
2. você receberá a nota por critério, pontos fortes, problemas, erros críticos e oportunidades de melhoria;
3. serão apresentadas perguntas para uma entrevista técnica simulada;
4. será comunicada a decisão sobre avanço para a próxima etapa;
5. somente depois da avaliação inicial poderemos revisar a solução em conjunto e adaptá-la para portfólio.

Boa sorte.
