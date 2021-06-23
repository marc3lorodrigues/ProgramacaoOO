# Programação Orientada à Objetos

Hoje em dia a maioria das linguagens de desenvolvimento possuem características de programação orientada a objetos. Algumas dessas características são: reaproveitamento de código, aumento de produtividade e facilitar o desenvolvimento. Para que possamos ter um bom entendimento das características OO no C# vamos ver alguns conceitos básicos.

## Abstração
É a identificação das informações do mundo real que serão definidas como características e comportamentos do objeto.

## Classe
É uma estrutura capaz de representar um modelo de objetos do mundo real, que possuem características e comportamentos comuns. As características poderão ser implementadas através dos atributos/propriedades. Os comportamentos poderão ser implementadas através dos métodos. Cada atributos, propriedade, e método possui a sua respectiva visibilidade.


- [Definindo um atributo](definindoatributo.md)
- [Definindo uma propriedade](definindopropriedade.md)
- [Definindo método construtor]()
- [Definindo métodos gerais]()
- [Sobreposição de Métodos]()
- [Sobrecarga de Métodos]()
 
 
 ## Instância
A instância é ação de se criar um objeto com base na classe. No momento da instanciação é chamado o método construtor implementado na classe que poderá executar algumas tarefas na construção do objeto.

 Exemplo:
 ```
 Class1 obj = new Class1();
```


## Objeto
É uma instância da classe. Quando se cria um objeto ele terá seu espaço na memória com a definição das suas características e comportamentos definidos. Em um sistema desenvolvido utilizando os conceitos de OO será utilizado objetos que através dos métodos interagem entre si com o objetivo de solucionar um determinado problema.

## Herança
É o mecanismo que permite que classes herdeiras (derivada) possa herdar propriedades e e métodos da superclasse (classe base). A classe derivada poderá sofrer alterações em suas propriedades e métodos quando permitidos bem como implementar novas propriedades e características.

#### Exemplo: 
```
class Basica
 {
        public int x;
        private int y;

        public void SomaXY()
        {
            int z;
            z = x + y;
        }
 }
 

class Derivada : Basica
{
    private int w;
}
``` 
 
