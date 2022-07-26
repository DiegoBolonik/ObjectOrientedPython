# ObjectOrientedPython
OO Paradigma

![image](https://user-images.githubusercontent.com/79227339/180915243-56b78843-4ffe-4ae7-a3b1-36f9175bf7f4.png)


Iremos trabalhar com o exemplo de uma conta de banco. Imagine que você tem uma conta e ela possuirá algumas características: 
saldo, número, agência, titular e um limite. Nossa motivação inicial era unir os dados e o comportamento, ou seja, juntarmos os atributos e os métodos. 
Tudo foi agrupado dentro de uma classe.

No caso, os atributos relacionados com a classe Conta são:

        numero
        titular
        saldo
        limite

Os métodos relacionados são:

        extrato(self)
        deposita(self, valor)
        saca(self, valor)

Comandos:

`python3`
`from conta import Conta`

Criando uma conta:

`conta = cria_conta(123, "Diego", 55.0, 1000.0)`

`conta.extrato()
conta.deposita(100.0)
conta.saldo`
