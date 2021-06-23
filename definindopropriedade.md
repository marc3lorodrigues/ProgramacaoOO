# Definindo uma propriedade:
A propriedade é o mecanismo de acesso, ela não armazena o valor e sim os manipulam no atributo.

Exemplo:
```
public class Class1

{
  // Atributos
  public int _Idade;
  public string _Nome;

  // propriedades
  public int Idade
  {
    get { return _Idade; }
    set { _Idade = value; }
  }
  public string Nome
  {
    get { return _Nome; }
    set { _Nome = value; }
  }
}
```
