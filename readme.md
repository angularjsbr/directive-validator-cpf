CPF Validator Directive [![Build Status](https://travis-ci.org/angularjsbr/directive-validator-cpf.svg?branch=master)](https://travis-ci.org/angularjsbr/directive-validator-cpf)
=======================

Diretiva para validação de cpf em AngularJS.

* Coloque a diretiva como dependência do seu projeto
* Um dos requerimentos da diretiva é o angular-messages para lançar na view as mensagens de erro.

As mensagens de erros disparadas são:

* cpfIncomplet -> Quando o cpf tem números de caracteres diferente de 11.
* cpfInvalid -> Quando o cpf inserido for inválido.