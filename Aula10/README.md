# Digital House - Turma 01 - IOS
## Exercícios de fixação

### Exercício 1:
Crie um app que...
- Tenha uma classe Avião, que tem modelo e cidade.
- Tenha uma classe PessoaFisica que tem nome e CPF.
- Tenha uma classe PessoaJuridica que tem nome e CNPJ.
- Tenha uma classe Cachorro, que tem nome e raça.
- Tenha uma classe Caneta, que tem marca.
Coloque um UISearchBar na tela. Quando o usuário pesquisar, ele pode pesquisar por QUALQUER propriedade de qualquer objeto.
Deve haver uma label com a lista, quando o usuário pesquisar por outro termo, deve continuar pesquisando na lista completa, e nao só no resultado.
* Use protocolos para resolver.
-----------------
### Exercício 2:
Crie um app que...
- Tenha uma classe Calculadora. 
- Essa calculadora deve ser instanciada sem nenhum parametro.
- Não é possível acessar propriedades por fora da classe.
Existem os métodos:
- Somar
- Subtrair
- Dividir 
- Multiplicar
Nesses métodos, será possível passar 2 parametros, e deverá retornar o resultado matemático.
O segundo parametro deve ser opcional, sendo que se eu passar só o primeiro, deve retornar o primeiro numero sem ser alterador por contas.
MAS se eu já tiver feito uma operação antes, ele deve armazenar o total, e quando eu passar só um parametro, deve levar em conta o resultado já existente.
Ex: 
somar(1,1) 
retorna 2
dividir(1,nil)
retorna 2
Ex:
somar(1, nil)
retorna 1
Não deve haver prints na classe da calculadora.
-----------------
### Exercício 3:
Crie um app de locadora...
Nessa locadora é possível fazer locação de DVDs, Livros, CDs e Carros.
Todos eles tem um código e um nome.
Porém o DVD, possui um formato de vídeo.
O Livro tem a quantidade de páginas.
O CD tem o cantor.
E o Carro tem a placa.
Todos eles tem a função de fazerLocação porém:
- O DVD deve avisar ao usuário que deve devolver em 5 dias.
- O CD deve avisar ao usuário que deve devolver em 3 dias.
- O Carro deve avisar ao usuário que deve devolver em 7 dias.
- O Livro deve avisar ao usuário que deve devolver em 15 dias.
* Nesse exercício use POO, aplique Herança e Polimorfismo.
------------------
### Exercício 4:
Um hipódromo quer implementar um sistema para notificar o resultado das corridas a todos os interessados. 
É simples: qualquer interessado no resultado pode assinar o sistema e ser notificado. Quando termina uma corrida, o sistema envia o resultado a todos os assinantes.
Os interessados serão:
1. Apostadores: como esse hipódromo tem fama de trapaceiro, ao receber a notificação, os apostadores imprimirão na tela: "Ladrões, Ladrões, Ladrões".
2. Kronika Tv: esse programa de jornalismo sensacionalista imprimirá na tela "Chegou o verão no hipódromo".
3. Casas de apostas: as casas de apostas têm um patrimônio. Quando são notificadas pelo hipódromo, esse patrimônio aumenta em R$ 1000. E imprimirá na tela "Ganhando grana".
Use protocolos para resolver.
------------------
Exercício 5:
Para aumentar as vendas, a empresa MonroeStreetJournal quer implementar um novo serviço de assinaturas do jornal DigitalNews.
O jornal pode ser assinado por pessoas ou empresas. Para as pessoas, precisamos modelar: nome, RG e o endereço de entrega do jornal. 
Já para as empresas, precisamos modelar: nome comercial, CNPJ e o número de funcionários.
Todas as manhãs, quando o jornal é distribuído, a empresa MonroeStreetJournal quer avisar os clientes que os exemplares já estão disponíveis. 
Também queremos que, ao receber seu jornal, os assinantes mostrem uma mensagem na tela. As pessoas exibirão a mensagem "Muito obrigado, MonroeStreetJournal. 
Vocês são demais!", enquanto as empresas exibirão a mensagem "Agradecemos cordialmente o MonroeStreetJournal pela excelência dos serviços prestados."
* Use protocolos para resolver.
