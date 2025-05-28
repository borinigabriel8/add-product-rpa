# ProductFormFillerRPA

## Descrição do Projeto

Este projeto automatiza o cadastro de produtos em um formulário HTML, utilizando uma planilha como base de dados. O robô RPA abre o formulário no navegador e uma planilha específica contendo os produtos, depois preenche os campos do formulário com os dados de cada produto e, por fim, submete o cadastro adicionando o produto logo abaixo do formulário. O processo é repetido para cada produto listado na planilha.

## Funcionalidades

- Abre o formulário HTML no navegador.
- Abre a planilha contendo os dados dos produtos.
- Lê os dados de cada linha da planilha, correspondendo a cada produto.
- Preenche os campos do formulário com os dados do produto (ex: codigo, marca, tipo, preço, etc.).
- Submete o formulário para registrar o produto.
- Repete o processo para todos os produtos da planilha.

## Requisitos

- UiPath Studio ou outro ambiente RPA compatível.
- Planilha Excel (.xlsx) formatada corretamente com os dados dos produtos.
- Formulário HTML acessível no navegador.

## Configuração

1. **Planilha de Produtos:**  
   Certifique-se que a planilha está no caminho definido no arquivo principal (Main.xaml). Caso contrário, atualize o caminho da planilha no projeto.

2. **Formulário HTML:**  
   O caminho ou URL do formulário deve estar configurado corretamente na automação para abrir no navegador.

## Uso

1. Execute o robô RPA.
2. O formulário será aberto automaticamente.
3. A planilha será aberta e o robô iniciará o preenchimento.
4. Para cada produto, o robô preencherá os campos do formulário e enviará.
5. Ao final, todos os produtos estarão cadastrados no formulário.

## Observações

- Certifique-se que o layout do formulário HTML e os nomes dos campos não foram alterados, pois isso pode quebrar a automação.
- Atualize os caminhos dos arquivos no projeto conforme necessário para o seu ambiente local.
- A planilha deve ter colunas organizadas e nomeadas para corresponder aos campos do formulário.

## Estrutura do Projeto

- **Main.xaml** - fluxo principal da automação.
- **produtos.xlsx** - planilha usada para leitura dos dados dos produtos.
- **index.html** - formulário HTML utilizado para cadastro, mas um domínio grátis foi criado para facilitar a utilização


---

*Automação desenvolvida para agilizar o cadastro de produtos via formulário HTML a partir de uma planilha.*  
