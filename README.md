<!DOCTYPE html>
<html lang="pt-BR">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Cadastro e Listagem de Produtos</title>
</head>
<body>
  <h1>Cadastro de Produtos</h1>
  
  <!-- Formulário de Cadastro -->
  <form id="produtoForm">
    <label for="nomeProduto">Nome do Produto:</label><br>
    <input type="text" id="nomeProduto" name="nomeProduto" required><br><br>
    
    <label for="descricaoProduto">Descrição do Produto:</label><br>
    <input type="text" id="descricaoProduto" name="descricaoProduto" required><br><br>
    
    <label for="valorProduto">Valor do Produto:</label><br>
    <input type="number" id="valorProduto" name="valorProduto" min="0" step="0.01" required><br><br>
    
    <label for="disponibilidadeProduto">Disponível para venda:</label><br>
    <select id="disponibilidadeProduto" name="disponibilidadeProduto" required>
      <option value="sim">Sim</option>
      <option value="nao">Não</option>
    </select><br><br>
    
    <button type="submit">Cadastrar Produto</button>
  </form>
  
  <hr>
  
  <!-- Listagem de Produtos -->
  <h2>Listagem de Produtos</h2>
  <table id="listaProdutos">
    <thead>
      <tr>
        <th>Nome</th>
        <th>Valor</th>
      </tr>
    </thead>
    <tbody id="corpoListaProdutos">
      <!-- Aqui os produtos serão inseridos dinamicamente -->
    </tbody>
  </table>
  
  <button id="novoProduto">Cadastrar Novo Produto</button>
  
  <script src="script.js"></script>
</body>
</html>

- 👋 Hi, I’m @Leeandromacedo
- 👀 I’m interested in ...
- 🌱 I’m currently learning ...
- 💞️ I’m looking to collaborate on ...
- 📫 How to reach me ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...

<!---
Leeandromacedo/Leeandromacedo is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->
