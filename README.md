
# Exercício para praticar o desenvolvimento com estratégia "Trunk Development"

* Objetivo: exercitar o desenvolvimento em equipe, utilizando uma estratégia conhecida como "Trunk Development".
Neste estratégia, o ramo "Trunk" (ou "master") contém o código principal do sistema. No entanto, os desenvolvedores
não fazer "commit" diretamente neste ramo. Quando vão desenvolver um requisito/componente, criam um ramo temporário
onde fazer suas alterações. Este ramos deve ser de curta duração (1 ou 2 dias, em geral), sendo feito o "merge" com 
o ramo principal frequentemente (quando o desenvolvimento deste elemento está estável o suficiente para ser integrado).
Como o ramo é der curta duração, deve-se escolhar tarefas que possam ser completados neste espaço de tempo.

* Atividades: 
    * definam a equipe, 
    
    * definam a estrutura do sistema a ser desenvolvido (enunciado abaixo), 
    
    * dividam as tarefas,
    
    * definam a estrutura do repositório e 
    
    * iniciem o desenvolvimento, cada membro da equipe em sua máquina
    
    * no desenvolvimento:
       
         * Modele as classes, implemente-as, com os respectivos testes unitários/dublês e testes de integração.

         * O trabalho deve ser em grupos de 3 ou de 4 componentes.
         
         * crie duas pastas no seu projeto:
         
            * pasta "src": seu código java, organizado com preferir
            * pasta "test": ser código de teste unitário, 



---------------------------------------------------------------------------------
## Sistema de catálogo de itens colecionáveis (livros, CDs, DVDs e revistas)

O objetivo deste sistema é manter listas itens colecionáveis, organizadas por tipo. 

O sistema deve permitir cadastrar os dados comuns e os específicos de cada tipo de item. 

Os dados comuns são: identificação única, nome, data de aquisição, lista de autores. 

Para os livros é importante manter também, o nome da editora e o ano de publicação. 

Já para os CDs, é interessante manter o gênero musical e a identificação das faixas de áudio (nomes das músicas). 

Para os DVDs é importante armazenar o tipo (musical, filme ou dados), e uma descrição geral sobre o item ou os extras, por exemplo. 

Por fim, das revistas é interessante manter o ano de publicação, o volume, a editora e os principais assuntos tratados. 

O sistema deve permitir imprimir uma listagem de cada tipo de colecionável. Deve permitir também pesquisa pelos itens específicos de cada tipo. 

Por exemplo, das revistas é interessante pesquisar sobre os assuntos que ela aborda, como a pesquisa por “programação orientada a objetos” poderia mostrar ao usuário uma lista de todos as revistas que tratam deste assunto. 

Deve permitir a consulta de algum item específico através da identificação do mesmo. Por fim, o sistema deve armazenar as informações no disco para recuperá-las em outro momento.

