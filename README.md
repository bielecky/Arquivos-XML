# Arquivos-XML

Trabalho AEDs II - Arquivo XML.

# Objetivos:
Utilizar a estrutura de dados pilha (POR ALOCAÇÃO DINÂMICA) na resolução de um problema de programação.

# Processo:
Leia com atenção o enunciado dos problemas abaixo, desenvolva um algoritmo e implemente o programa em C para resolver o problema descrito. Após a implementação, teste o programa para diferentes sequências de dados de entrada (arquivos XML).

# Problema:
XML, ou eXtensible Markup Language é uma série de especificações que podem ser usadas para criar novas tags (assim com é feito em HTML) a fim de dar significado a um conjunto de dados. Podemos definir, de forma bastante flexível, nossas próprias especificações XML. A importação e exportação de dados é um problema onde podem ser usadas especificações XML. Para evitar os formatos fechados e particulares dos bancos de dados podemos usar uma formatação XML, visto que o arquivo XML é um arquivo ASCII que pode ser gerado e/ou lido por qualquer aplicação.

Exemplo XML:
 <Aluno>
 <Nome>
 FULANO DE TAL
 </Nome>
 <Curso>
 Direito
 </Curso>
 <N1> 2.5 </N1>
 <N2> 6.5 </N2>
 </Aluno>
 (...)
</ESCOLA>

Observe que para tag de abertura existe uma tag de fechamento correspondente , distribuída usando a disciplina de Pilha. Uma aplicação interessante para pilha é a validação de um documento XML. Roteiro:

    Desenvolva um programa que utiliza a estrutura de dados Pilha de tags (usa a implementação de pilha por alocação dinâmica de nós) para resolver este problema. Considere que no documento XML, para cada tag de abertura existe uma tag de fechamento correspondente. As tags aparecem entre chaves angulares '<' e '>'. A tag de fechamento ainda inclui o símbolo '/'.
    O programa deverá solicitar um arquivo XML, fazer a leitura das linhas neste arquivo, procurar as tags, empilhar as tags de abertura e desempilhar e comparar quando for encontrado uma tag de fechamento.
    Ao final, o programa deverá escrever o texto: “Arquivo XML correto” ou “ERRO na linha XX do arquivo XML”, indicando a linha do arquivo onde foi encontrado o erro.
    Experimente o programa para vários arquivos diferentes.
