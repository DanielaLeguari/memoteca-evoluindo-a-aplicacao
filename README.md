# Memoteca

Esse projeto foi criado com [Angular CLI](https://github.com/angular/angular-cli) versão 16.0.1.


## Servidor de desenvolvimento

Para executar a aplicação basta abrir o terminal e digitar o comando `ng serve`. Navegar para `http://localhost:4200/`. 


## Para executar o backend 

- `npm start`


# Sobre o projeto

- Neste curso a aplicação Memoteca foi evoluída. No formulário foram inseridas validações, houve também a implementação de um campo de pesquisa de pensamentos e páginação de dados, além de favoritar pensamentos.


 # Apresentação do Memoteca


 ![]()


# Formulários no Angular

- No Angular existem dois tipos de formulários. Os formulários orientados a template e os formulários orientados a dados, data driven ou também conhecidos como formulários reativos.

# A Classe Validators

 - No projeto utilize a Validators.required(), Validators.minLenght(), Validators.pattern() e o Validators.compose(), mas existem diversos outros tipos de validação presentes na classe Validators. 

1. Validators.min()

- Validador que exige que o valor do controle seja maior ou igual ao número fornecido.

2. Validators.max()

- Validador que exige que o valor do controle seja menor ou igual ao número fornecido.

3. Validators.requiredTrue()

- Validador que exige que o valor do controle seja verdadeiro. Este validador é comumente usado para caixas de seleção obrigatórias.

4. Validators.email()

- Validador que exige que o valor do controle passe em um teste de validação de email.

5. Validators.maxLength()

- Validador que exige que o comprimento do valor do controle seja menor ou igual ao tamanho máximo fornecido.

6. Validators.nullValidator()

- Validador de valores nulos.

7. Validators.composeAsync()

- Compõe vários validadores assíncronos em uma única função que retorna a união dos objetos de erro individuais para o controle fornecido.
