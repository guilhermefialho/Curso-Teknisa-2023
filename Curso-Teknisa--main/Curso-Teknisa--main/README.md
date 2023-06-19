
# Validador de CPF
Este é um código em JavaScript que implementa um validador de CPF (Cadastro de Pessoa Física). O validador verifica se um CPF inserido é válido ou não, seguindo algumas regras de formatação e cálculo de dígitos verificadores.

Pré-requisitos
Antes de executar o código, certifique-se de ter as seguintes dependências incluídas em seu projeto:

jQuery: Uma biblioteca JavaScript que simplifica a manipulação do HTML e interações com o servidor.
jQuery Inputmask: Um plugin jQuery que fornece máscaras de entrada para campos de texto.
Certifique-se de incluir as seguintes bibliotecas em seu projeto:


<script src="https://cdnjs.cloudflare.com/ajax/libs/jquery/3.3.1/jquery.min.js"></script>
<script src="https://cdnjs.cloudflare.com/ajax/libs/jquery.inputmask/3.3.4/jquery.inputmask.bundle.min.js"></script>
# Funcionalidades
O código apresenta as seguintes funcionalidades:

O campo de entrada de texto #cpf é formatado automaticamente com a máscara "999.999.999-99" usando o plugin jQuery Inputmask.
A função validarCPF() é chamada quando o botão "Validar" é clicado.
A função validarCPF() realiza as seguintes etapas de validação do CPF:
Remove a formatação do CPF inserido.
Verifica se o CPF tem 11 dígitos. Caso contrário, exibe uma mensagem de erro.
Verifica se o CPF contém repetição do mesmo dígito. Caso positivo, exibe uma mensagem de erro.
Calcula os dígitos verificadores do CPF.
Verifica se os dígitos verificadores calculados são iguais aos dígitos informados. Caso contrário, exibe uma mensagem de erro.
Se todas as etapas forem bem-sucedidas, exibe uma mensagem de sucesso indicando que o CPF é válido.
Estilização
O código também inclui estilos CSS para a aparência da página. Aqui estão algumas características da estilização:

O plano de fundo do corpo (body) é definido como #212121.
O elemento com a classe .container é centralizado verticalmente na página.
O elemento .card representa um cartão com um formulário.
O elemento .body contém os elementos do formulário, como o campo de entrada de CPF e o botão de validação.
O elemento .footer exibe o resultado da validação do CPF.
Utilização
Para utilizar o validador de CPF, você pode adicionar o código fornecido em seu projeto HTML. Certifique-se de ter as dependências do jQuery e jQuery Inputmask incluídas. Em seguida, você pode inserir um CPF válido ou inválido no campo de entrada de texto e clicar no botão "Validar" para ver o resultado da validação exibido no elemento #resultado.
