# Lambda01-csharp
Exemplo de expressão lambda inline

• Suponha uma classe Product com os atributos name e price. Suponha que precisamos ordenar uma lista de objetos Product.

• Podemos implementar a comparação de produtos por meio da
implementação da interface IComparable<Product>

• Entretanto, desta forma nossa classe Product não fica fechada
para alteração: se o critério de comparação mudar,
precisaremos alterar a classe Product.

• Podemos então usar outra sobrecarga do método "Sort" da classe List:
public void Sort(Comparison<T> comparison)
