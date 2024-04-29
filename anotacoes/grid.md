  display: grid;
  (esse elemento vai dentro de uma teg pai, ele altera a forma do display para gardes)
 
 grid-template-columns: repeat(4,"parametro");
 (esse elemento define em quantas colunas o display sera dividido)

    grid-template-rows: repeat(4,auto);
    (esse elemento define em quantas linhas o display sera dividido)

    grid-template-areas: 

         columns
   rows "elemento elemento elemento"
        "elemento elemento elemento"
        "elemento elemento elemento";

    (aqui desenhamos a nossa pagina usando definindo quantos blocos o elemento ocupara) 

    grap:"parametro";
    (define um espaço em branco entre os blocos)

    rid-auto-flow: column;
    (muda a forma como os itens serao organisados na grade)

    justify-self: "parametro";
    (aplica a alteração apenas no item especifico)