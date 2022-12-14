#Markdown Tutorial

## Indice

1. Headers
2. Itálicos, Negritos e Negritos Itálicos
3. Parágrafo com destaque
4. Criação de hyperlinks
5. Criando snippets de código

## Headers
Sempre escrevemos headers, devemos deixar linhas em branco entre eles. Os headers são representados pelo simbolo #.

Os headers têm 6 níveis que são representados pela quantidade de símbolos escritos. 
Exemplos:

# h1
## h2
### h3
#### h4
##### h5
###### h6

## Itálicos, Negritos e Negritos Itálicos
Os negritos e itálicos são representados pelo símbolo * ou _.
Uma palvra cercada por 1 asterisco em cada lado terá seu formato modificado para *itálico*.
Uma palvra cercada por 2 asterisco em cada lado terá seu formato modificado para **negrito**.
Uma palvra cercada por 3 asterisco em cada lado terá seu formato modificado para ***negrito/itálico***.

## Parágrafo com destaque
Para escrever um parágrafo com destaque, utilizamos o simbolo >.
>Esse é parágrafo destacado do resto do texto.
>Esse aqui também.
>e assim por diante.
Os parágrafos acima estão destacados do restante do texto escrito.

## Criação de hyperlinks
A criação de hyperlinks é feita através dos símbolos [](). Onde o conteúdo dos colchetes é o texto que será exibido e o conteúdo dos parênteces é o link a ser redirecionado.
Ex: [Google](https://www.google.com.br/)
[Voltar ao Índece](#Indece)

## Criando snippets de código
Para criar snippets de código (parte de código) basta utilizar o símbolo de crase 3 vezes junto com a linguagem do snippet.

```java
public static void main(String[] args){
    System.out.println("Teste de snippet");
}
```

```javascript
    function bla(){
        document.getElementById("teste");
    }
```
```json
{
    "firstName": "Jorge",
    "lastName": "Abreu",
    "Age": 42
}