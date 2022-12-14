<h1 align="center">Trabalho de Estrutura de Dados</h1>

<h2>⚡1º- No projeto lista implemente um método de busca (search), de forma que a partir de um valor dado, retorne de o valor existe ou não (retornar true no caso de existente, e false no caso de não existente). public boolean search(int value); .</h2>

<p>🪲 Classe List</p>

     🔸public interface List {
     🔸     public void add(int value);
     🔸	
     🔸     public void remove(int value);
     🔸
     🔸     public String show();
     🔸
     🔸     public void update(int position, int value);
     🔸
     🔸     public int size();
     🔸
     🔸     public boolean search(int value);            <----- implementação
     🔸}
  
  
<p>🪲 Adicionando Método search na Classe LinkedList:
	
	
     🔸public boolean search(int value) {
     🔸
     🔸     Node current=this.head;
     🔸	
     🔸     while(current != null && current.content != value) {
     🔸          current = current.next;
     🔸     }
     🔸
     🔸     if(current==null) {
     🔸          return false;
     🔸     }else {
     🔸          return true;
     🔸     }
     🔸}
	

	
</br>
</br>
<h2>💫2º- Explique os seguintes termos e operações, descrevendo o cenário de cada um. </h2>

<p>🪲 a. FIFO:</p>

     💠FIFO = FIRST IN, FIST OUT.
     
     💠O primeiro que entrar, vai ser o primeiro a sair
     
     💠ex: Uma fila bancaria.
         
            🔹A primeira pessoa a chegar na fila será a primeira a ser atendida
        
	
<p>🪲 a. FILO:</p>

     💠FILO = FIRST IN, LAST OUT.
     
     💠O primeiro que entrar, vai ser o ultimo a sair
     
     💠ex: Um balde de roupa suja.
         
            🔹A primeira roupa q vc coloca fica no fundo do balde.
            🔹A segunda roupa dentro do balde ficara em cima da primeira.
            🔹A terceira em cima da segunda e assim continuamente.
	 
            🔹Se eu quiser pegar a primeira roupa que eu coloquei eu tenho q tirar todas as outras colocadas depois do caminho!



</br>
</br>
<h2>💫3º- Pesquise cenários de uso prático das seguintes estruturas de dados. </h2>

<p>🪲 a. Pilha:</p>

     💠Um editor de texto que possui o atalho de "voltar" (crtl + z).
     
     💠Cada "etapa" que vc esta sendo digitado pode ser armazenado em uma pilha.
     
     💠Sendo o ultimo caratere o "topo da pila".
     
  
<p>🪲 a. Fila:</p>

    💠 O software de uma impressora.
    
    💠 Um documento n pode ser impresso ao mesmo tempo que outro.
    
    💠 Com o sistema de fila pode-se controlar a ordem que cada um será impresso.
    
    
<p>🪲 a. árvore:</p>
    
    💠 Sites.
     
    💠 Um "LINK" é um nó da página que vc está atualmente.
     
    💠 Em uma pagina pode ter vários links, dentro de cada link pode ter ou não muitos outros e assim sucessivamente.
     



</br>
<h1></h1>
</br>
<p align="center">
<img src="https://github.com/isonhar/trabalho-estrura-de-dados-faculdade/blob/main/extra/Figura%20quest%C3%A3o%204.png">
</p>
<h2>💲4º- partir a arvore da figura acima:</h2>
</br>
<p>🪲 a. Descreva a saída para exibição em ordem:</p>
	
     🔹4 - 7 - 16 - 18 - 20 - 37 - 38 - 43
	
<p>🪲 b. Descreva a saída para exibição em pós-ordem:</p>
	
     🔹4 - 18 - 16 - 7 - 37 - 43 - 38 - 20
	 
<p>🪲 c. Descreva a saída para exibição em pré-ordem:</p>

     🔹20 - 7 - 4 - 16 - 18 - 38 - 37 - 43
	
<p>🪲 d. Indique o nível o grau de cada um dos nós:</p>
	
     🔹De grau = 2: 20 - 7 - 38
	
     🔹De grau = 1: 16
	
     🔹De grau = 0: 4 - 18 - 37 - 43

	
	
</br>
</br>
<h2>🍀5º- Considere a estrutura de dados do tipo Lista Encadeada, em que os elementos são alocados na memória à medida que são inseridos na lista, e removidos à medida que são dela retirados. Em um dado momento, essa lista possui 5 elementos (E1, E2, E3, E4 e E5), de forma que E1 aponta para E2, E2 aponta para E3, E3 aponta para E4 e E4 aponta para E5. Deseja-se retirar o elemento E3 dessa lista. Com base nas informações apresentadas, descreva a sequencia de passos para remover o elemento</h2>

     💠Para remover o " E3 ":
     
     💠Primeiro ele tem q ser encontrado e deixar ele como "atual".
     
     💠Depois pegar o anterior a ele e dizer que: 
                    🔹"Anterior" recebe o próximo de "Atual"
		
		
<p align="center">
<img src="https://github.com/isonhar/trabalho-estrura-de-dados-faculdade/blob/main/extra/quest%C3%A3o%205.png">
</p>

</br>
</br>
<h2>🔅6º- Abaixo tem-se uma tabela que ilustra o conjunto de nós de uma lista duplamente encadeada, contendo o total de 5 nós.</h2>

<p align="center">
<img src="https://github.com/isonhar/trabalho-estrura-de-dados-faculdade/blob/main/extra/Tabela%20quest%C3%A3o%206.png">
</p>

<h2>❓Ao imprimir a estrutura na ordem correta, o conteúdo apresentado será I – F – S – P – 2019, dessa forma, descreva a sequencia que preenchem, corretamente, a coluna “conteúdo”</h2>
		
<p align="center">
<img src="https://github.com/isonhar/trabalho-estrura-de-dados-faculdade/blob/main/extra/reposta%20quest%C3%A3o%206.png">
</p>


</br>
</br>


<h1 align="center">⭕bônus⭕ </br>Projeto implementado</h1>

➡️[Link Projeto](https://github.com/isonhar/trabalho-estrura-de-dados-faculdade/tree/main/projeto%20Lista/src)



<h1 align="center">〰️〰️〰️〰️〰️〰️〰️〰️〰️〰️</h1>
