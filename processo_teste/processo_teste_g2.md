<!--![Estado de Goiás](./images/sedi.png)-->
<div align=center>
  <img src="./processo_teste/imagens/teste-software.png">
</div>

# <p style="text-align: center;">Processo de Teste de Software</p>
<b>
<p style="text-align: center;">Universidade Federal de Goiás</p>
<p style="text-align: center;">Instituto de Informática</p>
<p style="text-align: center;">Bacharelado em Enenharia de Software</p>
<p style="text-align: center;">INF303 Teste de Software - 2021/2</p>
<p style="text-align: center;">Professor: Gilmar Ferreira Arantes</p>
<p style="text-align: center;">Aluno 1: 201802751 - Alan Brito Barros</p>
<p style="text-align: center;">Aluno 2: 201802753 - Amanda Lobo Gomes</p>

</b>

# Introdução

<p>
    Quando um software vai ser desenvolvido, é essencial que haja um planejamento prévio de tudo o que será realizado a fim de se obter êxito no resultado final. Apesar disso, todo software está sujeito a falhas, bugs e erros que comprometam seu pleno funcionamento, sobretudo quando o software vai se tornando grande e complexo.
    
Para  enfrentar esse problema, se torna imprecindível ter um bom processo de teste de software durante sua elaboração. 
    
Segundo a norma [IEEE 610.12.1990] pode-se definir um teste de software como:
**Teste é o processo de operar um sistema ou componente sob condições específicas, observando e registrando os resultados, avaliando alguns aspectos do sistema ou componente**
    
Pode-se definir um processo como:
    **Ação continuada, realização contínua e prolongada de alguma atividade**
    **Sequência contínua de fatos ou operações que apresentam certa unidade ou que se reproduzem com certa regularidade, andamento, desenvolvimento**
    
Sendo assim, um processo de teste de software visa organizar e moldar as etapas e atividades necessárias a fim de se testar da melhor forma possível o software que está sendo desenvolvido.
    
Dentro de um ciclo de vida de um software que está sendo desenvolvido, primeiramente ocorre a concepção do software em si, seguida as análises para o levantamento dos requisitos e demais especificações para que se possa começar o desenvolvimento. De modo geral, é após as fases listadas anteriormente que se inicia o processo de testagem do software.

</p>



## Papéis
-Coordenador de teste
-Analista de teste
-Testador

## Ambiente de teste
O ambiente de testes deve ser isolado, com processamento independente e características similares ao ambiente de desenvolvimento e produção e deve ser restrito à equipe de testes para garantir a integridade dos testes realizados.



# Planejar
Nesta etapa, os requisitos de negócio são estudados a fim de garantir que os testes serão completos e sem ambiguidades.

O Plano de Teste é elaborado para minimizar os principais riscos do negócio, definir os objetivos e atividades a serem realizadas e fornecer os caminhos para as próximas etapas. Também são definidos a abordagem do teste, os recursos utlizados, a equipe envolvida e as técnicas aplicadas. 

São descritos no plano de teste um ou mais casos de teste, que compreende no mínimo um conjunto de ações a serem executadas e um critério de aceitação, que diz se o teste foi bem-sucedido ou não.

![Fluxograma planejar](./processo_teste/imagens/planejar.png)

## Atividade 1 - Estudar Requisitos de Negócio


### Responsável(eis)
Coordenador de Teste.

### Quando
Fase inicial.

### Como
Identificar todos os tipos de testes que devem ser executados, comunicam-se com as diversas partes interessadas no projeto, definem prioridade e foco das validações e analisam a necessidade de automatizar os testes.


### Prazo

2-5 dias.

### Entradas
Todos os requisitos do projeto relevante aos testes necessários.

### Saídas
Definição de prioridades de validação dos requisitos, bem como as especificações iniciais dos testes.

### Fluxo:

Elaborar Plano de Teste.

## Atividade 2 - Elaborar Plano de Teste

### Responsável

Coordenador de Teste.

### Quando:


### Como:

Identificar componentes de software a serem testados, definir recursos necessários, custos previstos, cronograma de atividades.

### Prazo:

2-5 dias.

### Entradas:

Documentação referente ao projeto em desenvolvimento, seus
requisitos funcionais e não funcionais.

### Saídas:

Riscos identificados;
Componentes a serem testados;
Estratégia de testes;
Recursos de equipe, equipamentos e ferramentas necessários;
Prazos previstos;
Custo estimado;
Cronograma de atividades.

### Fluxo:


## Atividade 3 - Elaborar Estratégia de Teste

### Responsável:
Coordenador de Teste.

### Quando:

### Como:

Definir escopo de teste, identificar e definir os tipos de teste, definir critérios de teste, elaborar atividades de teste.

### Prazo:

2-3 dias.

### Entradas:

Documentação referente ao projeto em desenvolvimento, seus
requisitos funcionais e não funcionais.

### Saídas:

Escopo de teste;
Tipos de teste;
Critérios de teste;
Atividades de teste.

### Fluxo:
Definir Equipe e Cronograma.

## Atividade 4 - Definir Equipe e Cronograma

### Responsável:
Coordenador de Teste

### Quando:

### Como:
Cada atividade de teste definida na Estratégia de Teste deve ser agendada levando em consideração os levantamentos de requisitos e custos previstos no Plano de Teste, delegando a equipe disponível para a execução de cada atividade dentro do prazo estabelecido.

### Prazo:

1 dia.

### Entradas:

Plano de Teste e Estratégia de Teste.

### Saídas:
Cronograma de atividades com equipe distribuída.

### Fluxo:
Entregar Plano de Teste.

## Atividade 5 - Entregar Plano de Teste

### Responsável:
Coordenador de Teste.

### Como:
Revisar Estratégia de Teste e Cronograma e concluir o Plano de Teste.

### Prazo:
1-2 dias.

### Entradas:
Estratégia de Teste e Cronograma.

### Saídas:
Plano de Teste revisado.

### Fluxo:
Identificar funcionalidades.

# Projetar

Nesta etapa, é definido as condições dos testes a serem executados e os casos de teste associados. De acordo com o BSTQB, uma condição de teste é um item ou evento de um componente ou sistema que pode ser verificfado por meio de um ou mais casos de teste.

Nessa fase, são elaborados o mínimo de casos de teste para atingir o máximo de cobertura de teste do software.

Um caso de teste pode ser definido como um documento que descreve as etapas a
serem seguidas para realização de um teste. Desde os dados de entrada, a atividade em
execução e o resultado de saída. 

É utilizado para observar se o resultado de saída é realmente o esperado. Em caso positivo o teste foi realizado com êxito.

Suíte de teste o documento que faz o detalhamento final dos testes, nele é identificado o comportamento de cada caso de teste durante a execução. A suíte de teste estabelece a ordem de execução e a maneira que cada caso de teste irá proceder.

![fluxograma projetar](./processo_teste/imagens/proejtar.png)

## Atividade 1 - Identificar Funcionalidades

### Responsável:
Analista de Teste.

### Como:
Analisar Plano de Teste elaborado, identificando requisitos funcionais que podem ser testados e seus possíveis riscos.

### Prazo:
1 dia.

### Entradas:
Plano de Teste.

### Saídas:
Funcionalidades a serem testadas;
Riscos identificados.

### Fluxo:
Elaborar Casos de Teste

## Atividade 2 - Elaborar Casos de Teste

### Responsável:
Analista de Teste.

### Como:

De acordo com a Estratégia de Teste, definir os casos de teste com o objetivo de identificar as condições de teste, detalhando classes de dados de entrada e saída e elaborando a bateria de testes.
### Prazo:

2-5 dias.

### Entradas:
Estratégia de Teste e funcionalidades identificadas.

### Saídas:
Condições de teste;
Casos de teste detalhados;
Bateria de teste definida.

### Fluxo:
Elaborar Suíte de Teste

## Atividade 3 - Elaborar Suíte de Teste

### Responsável:
Analista de Teste.

### Como:
Realizar o detalhamento final dos testes, identificando o comportamento de cada caso de teste durante a execução.
### Prazo:
1 dia.
### Entradas:
Casos de teste.
### Saídas:
Suíte de teste definida.
### Fluxo:


# Executar

Nesta etapa os casos de teste definidos na etapa anterior são implementados e executados. Os testes realizados serão distintos para cada etapa do ciclo de vida do processo de desenvolvimento de software.

Basicamente, poderão ser executados:

**Testes de Unidade:**  tem por objetivo explorar a menor unidade do projeto, procurando provocar falhas ocasionadas por defeitos de lógica e de implementação em cada módulo, separadamente.

**Testes de Integração:** visa provocar falhas associadas às interfaces entre os módulos quando esses são integrados para construir a estrutura do software que foi estabelecida na fase de projeto.


**Testes de Sistema:** avalia o software em busca de falhas por meio da utilização do mesmo, como se fosse um usuário final. 

**Testes de Aceitação:** são realizados geralmente por um restrito grupo de usuários finais do sistema. 

![Fluxograma executar](./processo_teste/imagens/executar.png)

## Atividade 1 - Prepararar ambiente de Teste

### Responsável
Analista de teste

### Quando:

### como
Preparar os frameworks necessários para a execução do teste, além de preparar todo o hardware e software necessário para a execução dessa etapa.

### Prazo:

1-2 dias

### Entradas:

Especificação do ambiente de teste e ferramentas (frameworks, bibliotecas e softwares auxiliares) que serão utilizados no ambiente de teste.

### Saídas:

Ambiente de teste pronto para a execução dos mesmos.

### Fluxo:

## Atividade 2 - Executar Testes

### Responsável
Testador.

### Quando:

Após o ambiente de teste estar finalizado e pronto para executar os testes.

### como

Seguindo o plano estabelecido nas fases anteriores, cobrindo os casos de testes declarados na fase de planejamento

### Prazo:

Varia de acordo com a quantidade de testes que serão realizados.

### Entradas:

Casos de testes.

### Saídas:

Resultados dos testes.

### Fluxo:



## Atividade 3 - Obter Resultados de Teste

### Responsável

Analista de testes.

### Quando:

Após a realização dos testes.

### Como

Através da saída dos testes, saberemos a situação do código que foi testado.

# Entregar

Nesta etapa, discute-se os resultados obtidos durante o ciclo de vida de teste, com o propósito de reduzir falhas e custos, além de otimizar os processos e cumprir os objetivos do negócio. É importante que seja elaborado um relatório de qualidade com a cobertura dos testes e os detalhes do projeto.

![Fluxograma entregar](./processo_teste/imagens/entregar.png)

## Atividade 1 - Analisar Resultados de Teste

### Responsável

Analista de testes.

### Quando:

Após o relatório dos testes sair, isso ocorre após o final da fase de execução.

### como

Comparar o resultado dos teses com aquilo que se esperava que o sistema desempenhasse.

### Prazo:

2-7 dias.

### Entradas:

Resultados dos testes.

### Saídas:

Itens de melhoria a serem colocados no relatório de qualidade (próxima atividade).

### Fluxo:

## Atividade 2 - Elaborar Relatório de Qualidade

### Responsável

Analista de testes.

### Quando:

Após o término da análise dos resultados do teste.

### como

Utilizando-se dos dados que foram obtidos com a análise de teste deve ser realizado um relatório apontando ao time de desenvolvimento informações que permitam à eles a resolução dos problemas encontrados.

### Prazo:

1-2 dias

### Entradas:

Resultados dos testes com sua respectiva análise.

### Saídas:

Relatório contendo informações a respeito do que foi encontrando a partir dos testes realizados.

### Fluxo:


# Considerações Finais

É importante ressaltar que os testes precisam ser revisados com frequência, pois se os mesmos testes sejam aplicados repetidamente, em determinado momento eles deixaram de ser úteis, com isso não se encontrará mais erros, prejudicando então a eficiência que deverá ter o software. Porém com todos esses princípios é importante sempre que o software atenda sempre as necessidades do usuário, resumindo, um software deve ser testado sempre.
