

# Bootcamp Data Science Alura 2021 - Módulo 1
# Internações no Brasil: Uma análise exploratória entre 2010-2020

<img src="https://images.unsplash.com/photo-1576091160550-2173dba999ef?ixlib=rb-1.2.1&ixid=MnwxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8&auto=format&fit=crop&w=1170&q=80" height="600" width="1000"></a>  
Photo by <a href="https://unsplash.com/@nci?utm_source=unsplash&utm_medium=referral&utm_content=creditCopyText">National Cancer Institute</a> on <a href="https://unsplash.com/s/photos/health-data?utm_source=unsplash&utm_medium=referral&utm_content=creditCopyText">Unsplash</a>
  


Elaborado por Francico Foz

<a href="https://img.shields.io/badge/author-gustavolq-blue.svg)](https://www.linkedin.com/in/francisco-tadeu-foz/" target="_blank"><img src="https://img.shields.io/badge/-LinkedIn-%230077B5?style=for-the-badge&logo=linkedin&logoColor=white" target="_blank"></a>  

---

## Introdução

Olá! 

Neste repositório você encontrará o meu projeto do módulo 1 do Bootcamp Data Science 2021 da [Alura](https://www.alura.com.br/).

Durante todo o Bootcamp irei mergulhar no oceano da Ciência de Dados a partir de dados reais da área da saúde em 6 módulos.



## Projeto  - Internações no Brasil: Uma análise exploratória entre 2010-2020

Os dados propostos inicialmente no Bootcamp foi dos de [Produção Hospitalar](https://datasus.saude.gov.br/acesso-a-informacao/producao-hospitalar-sih-sus//)  do [Tabnet - DATASUS](https://datasus.saude.gov.br/informacoes-de-saude-tabnet/).


Você poderá encontrar o notebook completo [aqui](https://colab.research.google.com/drive/1-_KmIfm7T7pHrl8xTwGMnuIsOljGvy4M?usp=sharing)

Resumo

Esta análise pretende explorar os dados de **internações** no Brasil, no período entre 2010-2020.


> *Foi escolhido a delimitação do período, devido a ainda estarmos durante o ano de 2021.*


A análise será realizada através do entendimento dos seguintes dados de **internações**:

1. Internações X Valores gastos em procedimentos hospitalares:
    *   Número total de internações por ano de processamento
    *   Valor total gasto por ano de processamento.
2. Internações por região
    *   Número de internações por região
3. Internações por UF (Unidade Federativa)
    *   Número de internações por UF
    *   Número de internações por UF, proporcional ao número de habitantes.  
4. Internações por complexidade
    *   Número de internações com alta e média complexidade.

### Hipótese

Diante dos dados iniciais de valores gastos, vistos durante a atividade do primeiro módulo. Deduzo inicialmente que o número de internações afeta o valor gasto em procedimentos hospitalares diretamente. 

Buscarei entender como se distribuem as internações para cada região, UF e como foram suas distribuições por complexidade.
   
### **Conclusões:**

Observei que minha hipótese inicial sobre a relação entre o número de internações e os valores gastos em procedimentos hospitalares estava errada.
Mesmo que haja uma relação, ela não é diretamente ligada como havia imaginado.

Consegui observar que as região sudeste, nordeste e sul possuem as maiores quantiades de internações.

Dentre as UF's o estado de SP possui um grande volume a mais do que os demais estados. O que me fez verificar a proporção por habitante. Ao verificar por habitante encontrei uma maior proporcionalidade, com o estado do PR liderando. 

Fica-se um ponto para em uma próxima análise, entender a razão do estado possuir uma maior quantidade de internações por pessoa. Aprofundar nos tipos de especialidades que foram realizadas estas internações, verificar a faixa etária da população e até mesmo fazer uma análise mais detalhada por município.

Dentre o nível de complexidade, também errei ao supor que internações com média complexidade teriam tido uma maior queda no começo do ano de 2020 (devido ao Covid-19) em relação as de alta complexidade.

