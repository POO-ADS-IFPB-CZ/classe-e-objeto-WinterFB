7) O nome da classe contém espaços e as variáveis tituloDeEleitor e zonaEleitoral deveriam também serem classificadas como String, visto que provavelmente não será realizado nenhuma operação matemática com elas e só ocuparão espaço desnecessário na memória. Além disso, seria bom a classe ter "public" ou "private" na frente.<br />
<br />

8) <br />
1 - As variáveis num1 e num2 não possuem nenhum valor atribuído a elas, e mesmo assim há uma condição as comparando.<br />
2 - A condição (if (num1 > num2)) também deveria ter chaves {} separando seu conteúdo.<br />
3 - O método maior está declarado como int, mas os return da condição abaixo dela retorna valores bool.<br />
4 - Não há como o método menor retornar algo pois é void.
