# Equipe `<SHREK>`

# Subgrupo `<CHAVE>`
* `<Gabriel Freitas Pinheiro>` - `<222339>`
* `<Matheus de Mello Barreto Mendes André>` - `<243413>`
* `<Henrique de Lima>` - `<223911>`

## Modelo Conceitual ER Revisado

> Coloque aqui o diagrama entidade-relacionamento original ou revisado para transformação em modelo relacional. O diagrama deve atributos, cardinalidade e entidades fracas.
>
> Indique abaixo do diagrama (como no exemplo), se é o original ou o revisado.
>
> Não é necessário colocar o diagrama UML revisado.

<img src="images/ER.png" width="400px" height="auto">

*Diagrama ER origina;*

## Mapeamento para o Modelo Relacional

> Coloque aqui o modelo relacional que mapeia o modelo ER (original ou revisado). Nesse modelo deve constar o esquema das relações, com as chaves primárias e estrangeiras. A especificação de tipos de atributos é opcional.

> Exemplo de modelo lógico relacional
~~~
INGREDIENTE(_Nome_, Nutrientes)
  Ocupante chave estrangeira -> PRATO(Indredientes)
PRATO(_Nome_, Indredientes, Popularidade)
  Indrediente chave estrangeira -> INGREDIENTE(Nome)
CARDÁPIO(_Período_, Data, PerfilNutricional, Prato)
  Prato chave estrangeira -> PRATO(Nome)
Aluno(_Nome_, consome, compoe)
  consome chave estrangeira -> PRATO(Nome)
  compoe chave estrangeira -> INGREDIENTE(Nome)
~~~
