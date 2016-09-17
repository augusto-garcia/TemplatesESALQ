--- 
title       : Gerenciamento de Referências Bibliográficas
subtitle    : Use seu tempo de forma eficiente!
author      : Antonio Augusto Franco Garcia (http://about.me/augusto.garcia)
job         : Departamento de Genética, ESALQ/USP
framework   : io2012        # {io2012, html5slides, shower, dzslides, ...}
highlighter : prettify  # {highlight.js, prettify, highlight}
hitheme     : solarized_light    # era tomorrow
linenums    : true
widgets     : [mathjax, bootstrap, quiz]   # {mathjax, quiz, bootstrap}
mode        : selfcontained # {standalone, draft}
--- 

## Introdução

- O que faz um estudante/cientista/professor?
- Atividade comum: estudar, ler, produzir conteúdo, *publicar*
- Gerenciamento de uma grande quantidade de informação e conhecimento

---

## Gerenciamento de Referências

- Objetivo: eficiência e produtividade
- Usar os modernos recursos computacionais
- Foco no conteúdo, não nos formatos e regras

--- bg:#fee6ce

# Sumário

## Proposta

- Ideias gerais e conceitos importantes sobre o que são bases de dados
- Atividade prática
- Discussões

---

## Informação

- Livros
- Artigos
- Internet
  - Vídeos
  - Palestras
- Cadernos
- Tablets
- $\ldots$

Cada vez é mais comum armazenarmos informação digital

---

## Formatos

- Pastas suspensas com *separatas*
- Arquivos de diferentes tipos

---

## Padrão atual

- Arquivos (em formato *pdf* para artigos)
- ebooks
- Livros impressos
- Arquivos *.mp4*
- Lista de favoritos no *Youtube*
  - [Youtube](http://www.youtube.com/edu)
  - Exemplo: [Linear Algebra](https://www.youtube.com/results?search_query=gilbert+strang+linear+algebra)


---

## Anotações

- "Marca-texto"
- Anotações
  - Exemplo: [Fermat](http://youtu.be/E7Bqx65liIE)
- Notas de rodapé
- Cadernos
- "Guardanapos"
- $\ldots$

---

## Informação

- Onde guardei?
- Como lembrar?
- Estamos em 2014!

---

## Reprodutibilidade

- Dados experimentais (vídeos, que tal?)
- Web
- Códigos para analisar os dados
  - [FOAS](http://www.foastat.org/)
  - [ggvis](http://ggvis.rstudio.com/)
  - [QTL](http://kbroman.org/qtlcharts/)
  - html5

---

## Bagunça vs Reprodutibilidade

- Você arruma sua casa antes de receber visitas?
- Você gostaria que alguém repetisse as análises que você fez na sua
tese?
- E nos artigos já publicados?
  - (Fiz isso no meu pós-doc)

---

## Docentes/Responsabilidade

- Referências Bibliográficas: um *ótimo* primeiro passo
- Lembre-se, temos o dever ético de citar corretamente o trabalho de
outros autores
- Há outros pontos:
  - Somos funcionários públicos: a sociedade não espera que usemos
    nosso tempo corrigindo se todos os artigos estão citados no texto,
    e vice-versa! (É fácil pensar em vários outros exemplos)
  - Uso eficiente do tempo é bom para todos
- Novas normas para Teses e Dissertações

---

## Tenho algo a dizer?

- Docente
- Editor de periódicos
- Genética Estatística
  - Softwares
  - Colaborações
  - Dados de diferente natureza
- Alunos
- $\LaTeX$
- Páginas pessoais: [about.me](http://about.me/augusto.garcia), [página pessoal](http://augusto-garcia.github.io/), [Lab](http://statgen.esalq.usp.br)

---

## Reprodutibilidade

- Os arquivos estão seguros?
- Vou conseguir abri-los daqui 10 anos?
- Consigo *ter acesso as informações* de forma eficiente?
- Metadados?
- Vários critérios de buscas?
  - Pastas suspensas: classificação unidimensional

---

## Programas

- Uôrdi, Equicél, Pouerpóinti
- SAS
- $\ldots$
- Licenças institucionais (USP)
- Pirataria

---

## Não seja ingênuo!

- iOS vs Android
- Windows Phone (Microsoft)
- Tizen (Samsung)
- Kindle (Amazon)

---

## Portabilidade

- *Arquivos texto* são os melhores!
  - [The Power of Plain Text](http://c2.com/cgi/wiki?PowerOfPlainText)
- Arquivos texto vs binários
- Excel vs .csv
- Linux
- git

---

## Retrógrado? Desatualizado?

- É óbvio que precisamos de *interfaces* para interagir com os
arquivos
- Base de dados é diferente de trabalhar com os arquivos
- (Sim, o Excel abre e grava arquivos em .csv)
- pdf é formato binário, mas é possível facilmente convertê-lo em
texto
- O CV Lattes não permite isso, já que não podemos baixar a base de
  dados, apenas binários

---

## Referências Bibliográficas

- Grande parte do seu tempo (tomara!) será dispendido lendo/escrevendo
publicações
- Será preciso constantemente retornar as anotações e fazer diferentes
buscas
- Logo, qualquer investimento de tempo tem elevado retorno na
produtividade
- O novo formato de Teses e Dissertações prevê o uso de algum
  gerenciador de referências (mas não obriga tal uso)
- (Dica: aprenda também a usar um Editor de Textos decente)


---

## BibTex

- [BibTex](http://www.bibtex.org/)
- Formato texto, portátil, versátil, *lingua franca*
- Associado ao $\LaTeX$, mas não necessariamente

---

## Formato


```r
@misc{ patashnik-bibtexing,
       author = "Oren Patashnik",
       title = "BIBTEXing",
       year = "1988" }
```

---


## Demonstração

- Emacs + R + $BibTex$
- Código fonte destes slides (remover os comentários do código)



---

## Exemplos

-
[library.bib](https://raw.githubusercontent.com/augusto-garcia/Gerenciamento-Referencias/gh-pages/library.bib)

Mais detalhes: [Wikibooks](http://en.wikibooks.org/wiki/LaTeX/Bibliography_Management)


--- .segue .dark .quote

<q class = 'yellow'> Seja esperto. Crie sua base de dados em formato
que não seja dependente de programas específicos. </q>

---

## Gerenciadores de Referências

  1. [Mendeley](http://www.mendeley.com/)
  2. [Zotero](https://www.zotero.org/)
  3. [EndNote](http://endnote.com/) (Permite exportar? CSL?)
  4. [Papers](http://www.papersapp.com/)
  5. [JabRef](http://jabref.sourceforge.net/)
  6. [citeulike](http://www.citeulike.org/)
  7. $\ldots$ (a lista é longa!)

---

## Pontos importantes

  1. Posso importar/exportar para o $BibTex$?
  2. Posso usar o programa para incluir as citações nos meus
  trabalhos?
  3. Quais são os formatos para citação disponíveis?
  4. Posso expandir estes formatos?

---

## Citação vs Base de Dados

- Cuidado para não confundir os conceitos
- Geralmente, os programas não deixam clara esta distinção

---

## Formatos para citação adotados pelas principais revistas

- [Citation Styles, CSL, http://citationstyles.org](http://citationstyles.org/)
  - Mais de 6700 estilos de citação abertos e gratuitos (hoje, 7000)
  - As principais revistas participam e contribuem
  - Tais formatos podem ser importados em vários programas
  gerenciadores de referências

---

## Mendeley

- [Mendeley](http://www.mendeley.com/)
- Uma ótima opção
- Gratuito, com versão paga (espaço para arquivos; coleções compartilhadas)
- Permite exportar para $BibTex$ (caso contrário, eu não
recomendaria)
- Rede Social, compartilhamento
- Plugins para Word e [LibreOffice](https://pt-br.libreoffice.org/)
- Permite fazer anotações e marcações de texto nos pdfs
- Sincronização entre computadores
- App para tablets e celulares
- Fácil inclusão de citações em emails e outros documentos
- Importação de Metadados de pdfs com DOI
- Possibilidade de inclusão manual dos metadados

---

## Mendeley

- Rápida demonstração, usando minha coleção

---

## Tarefas

1. Assista os vídeos disponíveis no site (clique [aqui](http://www.mendeley.com/features/))
2. Abra uma conta
3. Baixe e instale o programa
4. Adicione algum dos seus colegas na sua rede de relacionamentos
5. Adicione a sua coleção os pdfs disponíveis
   [aqui](https://github.com/augusto-garcia/Gerenciamento-Referencias/tree/gh-pages/pdfs);
   corrija os metados se necessário
6. Crie os metadados para um livro para o qual você não possui o pdf,
mas vai citá-lo na tese
7. Abra algum dos artigos e faça anotações e marcações no texto
8. Crie uma coleção particular e inclua estas 3 referências
9. Crie uma coleção compartilhada e inclua as referências

---

## Tarefas

10. **IMPORTANTE**: Crie tags para os artigos
   - Você percebe a importância disso? Um artigo pode ser classificado
   em diferentes assuntos. A ideia de "pastas" é obsoleta!
   
11. No menu "Tools -> Options" do Mendeley, explore as possibilidades
de organizar todos os seus pdfs em algum diretório
   - *IMPORTANTE*: note que isso permitirá que você pode abandonar o
Mendeley a qualquer momento, continuando com a posse dos seus pdfs
organizados

12. Exporte sua coleção para o formato $BibTex$
    - Está mais confiante que sua coleção está segura agora?
    - (Nem tudo é perfeito; onde estão as "marcações" nos pdfs? Note
      que este é um problema típico dos arquivos binários)

---

## Tarefas

13. Explore a opção "View" para entender a diferença entre "Library as
Table" and "Library as Citations"
14. Escreva um email incluindo a citação dos dois artigos no corpo da
mensagem
15. Importe agora um formato de citação que não está incluído
    originalmente no Mendeley, mas faz parte do
    [Citation Styles](http://citationstyles.org/)
    - "View -> Citation Styles -> More Styles"

---

## Agora, a melhor parte!

16. Instale o plugin para fazer comunicação entre o Word e o Mendeley
    - "Tools -> Install Word Plugin"

17. Abra o Word, escreva algum texto e insira a citação dos artigos

18. Solicite que o Word crie a lista de referências no formato
desejado

19. Modifique o formato para outra revista

20. Diga "Uáu!!!!!" só para deixar o professor contente ;o)


---

# CONCLUSÕES

- Esta nova abordagem implica necessariamente na mudança das *Normas
Para Elaboração de Dissertações e Teses*
- O formato atual de citações não está (nem nunca será incluído!) no
[Citation Styles](http://citationstyles.org/)
    - A razão é simples: depende de intervenção humana para saber como
    incluir a citação
- Mesmo usando a ABNT (sem adaptações), teremos problemas: não
  considera os diferentes aspectos da vida acadêmica, que é o que de
  fato importa

--- bg:#fee6ce

<q>OBRIGADO!</q>


