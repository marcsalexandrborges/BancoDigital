
## Validações:

Adicionei validações nos métodos `sacar`, `depositar` e `transferir` para garantir que o saldo não fique negativo. Por exemplo, verifique se o valor a ser sacado não excede o saldo disponível.
   
![BancoDigital](https://raw.githubusercontent.com/marcsalexandrborges/BancoDigital/main/1.png)


## Encapsulamento:

Considere tornar os atributos privados e fornecer métodos getters e setters para acessá-los. Isso ajuda a controlar o acesso aos dados e a manter a coesão.

Vamos aplicar o encapsulamento ao código. Primeiro, tornaremos os atributos privados e, em seguida, criaremos os métodos getters e setters para acessá-los.

![BancoDigital](https://raw.githubusercontent.com/marcsalexandrborges/BancoDigital/main/2.png)
    

## Implementação da Classe Banco

Aqui está uma implementação básica da classe Banco:
Nessa implementação, a classe Banco possui um nome e uma lista de contas. Ela tem métodos para adicionar contas e buscar contas pelo número.

![BancoDigital](https://raw.githubusercontent.com/marcsalexandrborges/BancoDigital/main/3.png)


## Metodo para calcular o saldo total do banco, você pode percorrer todas as contas e somar os saldos individuais de cada uma delas. Aqui está uma implementação básica desse cálculo na classe Banco:

Nesse método calcularSaldoTotal(), percorremos todas as contas no banco e somamos os saldos individuais. O resultado é o saldo total do banco.

![BancoDigital](https://raw.githubusercontent.com/marcsalexandrborges/BancoDigital/main/4.png)

   
