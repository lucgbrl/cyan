# cyan
Sistema de referenciamento (adição, listagem e busca) em uma árvore binário de busca utilizando Swift


Na Linguagem Swift (Apple) temos o suporte à tipos abstratos de dados, sendo estes definidos de maneira semelhante às linguagens C/C++. Sua declaração é:

**struct** nome_da_estrutura{
  
  **var nome_atributo: Tipo_atributo?
  var nome_atributo2: Tipo_atributo2?**
  
  /* 
  *  *A declarativa '?' indica que o atributo pertencente à Struct ainda não 
  *  foi instanciado ou declarado em outros trechos do código
  *  dados a serem armazenados dentro da estrutura
  *  funções definidas dentro da estrutura
  */
  
  **init**( var nome_atributo: Tipo_atributo?, var nome_atributo2: Tipo_atributo2?, ... ){
    
    //aqui as variáveis serão inicializadas por meio da declaração self.nome_atributo = nome_atributo
      
      self.nome_atributo = nome_atributo
      self.nome_atributo2 = nome_atributo2
      
      }
}   //*Fim da Struct
