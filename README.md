# Análise de Palíndromos
Este projeto verifica se uma frase é um palíndromo. Para isso, o programa limpa o texto, inverte a sequência e compara os dois resultados.
## Pré-requisitos
É necessário ter o **Python 3** instalado.
Para verificar a versão, execute no terminal:
python3 --version

O código utiliza o módulo *re*, que faz parte da biblioteca padrão do Python.
## Como executar
No terminal, entre na pasta do projeto e execute:
python3 DesafioLogica.py

## Exemplo
**Entrada**

texto1 = "A casa de casada"

texto2 = "Socorram-me, subi no ônibus em Marrocos"

**Saída**

Teste 1: False

Teste 2: True

## Como funciona
A função *analisar()* recebe uma frase e verifica se ela é igual à sua versão invertida.
Primeiro, verifica se a entrada é *None*. Depois, o *re.sub()* remove caracteres que não sejam letras ou números e o *.lower()* transforma as letras em minúsculas.
Em seguida, a string é invertida usando *[::-1]*. Por último, o programa compara as duas strings e retorna *True* se forem iguais ou *False* se forem diferentes.
## Resultado dos testes
**Teste 1 — False**

*"A casa de casada"* não fica igual quando invertida, então o resultado é *False*.

**Teste 2 — True**

*"Socorram-me, subi no ônibus em Marrocos"* fica igual quando invertida após a limpeza feita pelo programa, então o resultado é *True*.

## Sobre os Autores

Alice Fernandes Barbosa - @alicefbarbosa - 326128348

Ana Carolina de Sousa Freitas - @AnaFreitas1 - 325132932

Atividade 1 da disciplina de Gestão e Qualidade de Software.


