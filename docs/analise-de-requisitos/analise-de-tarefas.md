# Análise de Tarefas

## 1. Introdução
<p align="justify">
  A <b>análise de tarefas</b> é para se ter um entendimento sobre qual é o trabalho dos usuário, como eles o realizam e por quê. Nesse tipo de análise, o trabalho é definido em termos dos objetivos que os usuários querem ou precisam atingir.(Barbosa, S. D. J.; Silva, B. S. da; Silveira, M. S.; Gasparini, I.; Darin, T.; Barbosa, G. D. J. 2021). O método que será utilizado para análise de tarefas nesse projeto será a Análise Hierárquica de Tarefas (AHT).
</p>

## 2. Análise Hierárquica de Tarefas (AHT)
<p align="justify">
A Análise Hierárquica de Tarefas foi desenvolvida na década
de 1960 para entender as competências e habilidades exibidas em tarefas complexas e não repetitivas,
bem como para auxiliar na identificação de problemas de desempenho <i>(Barbosa et al., 2021 apud Annett, 2003; Annett e Duncan,
1967)</i>. Essa técnica ajuda a relacionar o que as pessoas fazem, por que o fazem, quais as consequências caso não o façam corretamente.
</p>
<figure align='center' >
  <img  src="./assets/imagens/elementosHTA.png" width="700px">
  <br>
  <figcaption>Fonte: Barbosa et al. "Interação Humano-Computador e Experiência do Usuário". capitulo 8, página 165</a></figcaption>
</figure>
<p align="justify">
 <ul>
    <li align="justify">
      <b>Objetivo:</b> Um objetivo é um estado específico de coisas, um estado final. Esse estado por ser definido por um ou mais eventos ou por valores fisicamente observáveis de uma ou mais variáveis, que atuam como critério de alcance do objetivo e, em última instância, do desempenho do sistema. (Barbosa et al., 2021)
    </li>
 </ul>
 <ul>
    <li align="justify">
      <b>Operação</b>: Um plano define os sub-objetivos necessários para alcançar um outro objetivo maior, e a ordem em que esses sub-objetivos devem ser alcançados. Os planos podem definir diversas relações entre os sub-objetivos: sequência fixa
      (um objetivo deve ser atingido antes do próximo); regra de seleção ou decisão (quais objetivos que deverão
      ser atingidos dependem das circunstâncias); ou em paralelo (mais de um objetivo deve ser atingido ao
      mesmo tempo). (Barbosa et al., 2021)
    </li>
 </ul>
</p>

## 3. Análise

### 3.1 Realizar uma manifestação na Ouvidoria

|Objetivos/Operações| Problemas e recomendações|
|---|---|
|0. Realizar Manifestação| |
|1. Acessar o site da prefeitura de Itabuna|input: endereço do site|
|2. Selecionar na barra de tarefas ou no menu suspenso de atalhos a opção Ouvidoria Municipal|recomendação: remover o menu suspenso de atalhos ou o posicionar no final da página|
|2.1 Selecionar a opção Nova Manifestação||
|2.1.1 Selecionar qual o tipo de manifestação que deseja realizar||
|2.1.2 Inserir os dados necessários e a manifestação|input: caso seja manifestação aberta ou sigilosa: nome, email, telefone, residente, tipo, meio de resposta e descrição da manifestação|
|2.1.3 Selecionar a opção Enviar||

Tabela 1 - Tabela HTA. Autor: Vinícius Lima.

<figure align='center'>
  <img src="./assets/imagens/analises/diagrama-manifestacao.png">
</figure>
Figura 1 - Diagrama HTA.

### 3.2 Validação de Nota Fiscal Eletrônica

|Objetivos/Operações| Problemas e recomendações|
|---|---|
|0. Validar Nota Fiscal Eletrônica| nenhum|
|1. Acessar o site da prefeitura de Itabuna|input: endereço do site|
|2. Selecionar na barra de tarefas ou no menu suspenso de atalhos a opção Nota Fiscal Eletrônica| recomendação: remover o menu suspenso de atalhos ou o posicionar no final da página|
|2.1 Selecionar a opção Validar NFS-e|nenhum|
|2.1.1 Inserir os dados para realização da busca|input: CPF ou CNPJ, número da NFS-e, Código de verificação|
|2.1.2 Efetuar a verificação do Captcha|nenhum|
|2.1.3 Selecionar a opção Buscar|nenhum|
|3. Realizar login no site|input: credenciais do usuário|

Tabela 2 - Tabela HTA. Autor: Vinícius Lima.

<figure align='center'>
  <img src="./assets/imagens/analises/diagrama-nfe.png">
</figure>
Figura 2 - Diagrama HTA.

## 4. Referência Bibliográfica
    Barbosa, S. D. J.; Silva, B. S. da; Silveira, M. S.; Gasparini, I.; Darin, T.; Barbosa, G. D. J. (2021) Interação
    Humano-Computador e Experiência do usuário. Autopublicação.

## 5. Versionamento 
Versão |  O que foi inserido? | Data | Autor(es)| Revisor
---- |----- | ---- | ---- | ----
1.0 | Criação do documento, introdução e análise hierárquica |26/02/2022| [Alan Marques](https://github.com/alan-ms) | [Ciro](https://github.com/ciro-c)
1.1 | Adição de tabelas e diagramas de análise | 27/02/2022| [Vinícius Lima](https://github.com/vinelime) | [Ciro](https://github.com/ciro-c)
1.2 | Inserção das referências bibliográficas |26/02/2022| [Alan Marques](https://github.com/alan-ms) | [Ciro](https://github.com/ciro-c)|
1.3| Correções sugeridas | 15/03/2022 | [Vinicius Roriz](https://github.com/viniciusroriz)|