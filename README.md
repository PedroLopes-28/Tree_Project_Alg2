# Alg2Project2

Esse projeto consiste na implementação manual dos algoritimos das Arvores 234 e Rubro Negra, explorando suas similaridades e portanto, implementando, seguindo o que é ensinado por Cormen, implementando um código de conversão, que recebe uma Arvore 234 e atravez da analise da estrutura de cada nó, bem como o seu numero de filhos, produz uma Arvore Rubro Negra equivalente, isso funciona pois arvores 234, como dito por Cormen são equivalentes a Rubro Negras, uma vez que Arvores Rubro Negra podem ser usadas para representar uma arvore 234.

Alem disso, o código conta com uma impressão compelta da estrutura da arvore para melhor visualização dos resultados e depuração do código, segue um exempo abaixo de uma estrutura de rubro negra que pode ser impressa pelo codigo:

             P
           /   \
          V     P
         / \   / \
         P  P V   V



---

## Compilando e Executando o Código

### Pré-requisitos

É necessário possuir um compilador C compatível com o padrão ANSI C, como o **GCC**.

#### Windows

Recomenda-se o uso do **MinGW-w64**. Após a instalação, verifique se o compilador está disponível no terminal:

```
gcc --version
````
Linux (Ubuntu/Debian)

````
sudo apt update
sudo apt install build-essential
````

macOS
````
xcode-select --install
````

Compilação

Acesse a pasta raiz do projeto e execute o comando abaixo, incluindo todos os arquivos .c:

````
gcc main.c 234.c RB.c conversao.c -o projeto
````

Para uma compilação com avisos e suporte à depuração, utilize:
````
gcc -Wall -Wextra -g main.c 234.c RB.c conversao.c -o projeto
````
Execução
Linux / macOS
``
./projeto
``
Windows
````
.\projeto
````

# Referências

CORMEN, T. H.; LEISERSON, C. E.; RIVEST, R. L.; STEIN, C.
Introduction to Algorithms. MIT Press.

Os códigos foram desenvolvidos e comentados por:

- Pedro Henrique de Souza Lopes - https://github.com/PedroLopes-28
- Bianca dos Reis Moraes - https://github.com/BiancaReisMoraes
- Silvan da José da Silva Júnior - https://github.com/SilvanJr14