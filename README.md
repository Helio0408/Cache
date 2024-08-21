# Caches

## Introdução

A memória é um componente importante nos computadores. Ela é uma parte fundamental da arquitetura de von Neumann, uma arquitetura que é base de muitos computadores até hoje. Nela, a função da memória é armazenar instruções que podem ser decodificadas e lidas pela Unidade de Controle e também armazenar dados, como resultados de operações de soma e subtração da Unidade Lógica de Controle (ULA).

O computador possui vários tipos de armazenar dados em memória. Dentre elas, estão:
- **Registradores**: São unidades de memória dentro do próprio processador. São neles que são feitas as operações da ULA do computador, e também são as memórias de mais rápido acesso. Geralmente, o processador os possui em pequena quantidade.
- **RAM (Random Access Memory)**: É uma memória externa ao processador que permite acesso aleatório de dados. Ela é mais lenta que os registradores. Ela pode armazenar bem mais dados do que registradores.
- **Memória em Disco**: É um tipo de memória que permite guardar dados de forma permanente, ou seja, mesmo que o computador seja desligado os seus dados não serão apagados. Ela é a memória mais lenta de acessar. Exemplos são discos rígidos.

Na prática, códigos e programas são armazenados em memória em disco. Quando precisam ser utilizados, são carregados na RAM. O processador lê as instruções armazenadas na RAM, carrega os valores necessários para os registradores, realiza operações com eles e guarda-os na RAM caso necessário.

Porém, com o desenvolvimento computacional, notou-se que a RAM tornou-se um empecilho para a velocidade do processamento. Isso porque a velocidade que o processador é capaz de processar os dados é muito mais rápido do que a velocidade da leitura da RAM. Para resolver esse problema, foi necessário criar uma memória, assim como a RAM, que o processador realizasse o acesso mais rapidamente, onde pudesse guardar dados que fossem utilizados de maneira recorrente.

### Tópico 1

## Memória Cache

### O que é ?

### Características

## Tamanho da Cache

## Tamanho do bloco

## Estrutura da Cache

## Função de mapeamento

### Mapeamento Direto

### Mapeamento Associativo

### Mapeamento Associativo por Conjunto
