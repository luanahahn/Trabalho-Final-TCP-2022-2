# Trabalho-Final-TCP-2022-2
Trabalho final da disciplina de Técnicas de Construção de Programas, do instituto de informática da Universidade Federal do Rio Grande do Sul.
O objetivo deste trabalho é implementar, testar e depurar um conversor de texto em música, através do seguinte mapeamento de teclas:

|Texto | Informação Musical ou Ação|
--------------------------------
|(Letra A maiúscula)|Nota Lá|
------------------------------
|(Letra B maiúscula)|Nota Si|
--------------------------
|(Letra C maiúscula)|Nota Dó|
-----------------
|(Letra D maiúscula)|Nota Ré|
-----------------
|(Letra E maiúscula)|Nota Mi|
------------------------
|(Letra F maiúscula)|Nota Fá|
-----------------
|(Letra G maiúscula)|Nota Sol|
-----------------
|Letras a,b,c,d,e,f,g minúsculas|Se caractere anterior era NOTA (A a G), repete nota; Caso contrário, Silêncio ou pausa|
|Caractere Espaço|Aumenta volume para o DOBRO do volume; Se não puder aumentar, volta ao volume default (de início)|
-------------------
