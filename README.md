<!DOCTYPE html>
<html lang="pt-BR">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Pokédex React - Documentação</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 20px;
            padding: 20px;
            background-color: #f8f8f8;
            color: #333;
        }
        h1, h2 {
            color: #d32f2f;
        }
        code {
            background-color: #eee;
            padding: 2px 4px;
            border-radius: 4px;
            font-family: monospace;
        }
        .container {
            max-width: 800px;
            margin: auto;
            background: white;
            padding: 20px;
            border-radius: 10px;
            box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
        }
        ul {
            padding-left: 20px;
        }
    </style>
</head>
<body>
    <div class="container">
        <h1>Pokédex React</h1>
        <p>Este é um projeto simples de Pokédex feito com React.js, consumindo a PokéAPI para exibir informações sobre qualquer Pokémon.</p>
        
        <h2>📌 Funcionalidades</h2>
        <ul>
            <li>✅ Busca de Pokémon por nome</li>
            <li>✅ Exibição de ID, altura, peso e tipos</li>
            <li>✅ Imagem oficial do Pokémon</li>
        </ul>
        
        <h2>🚀 Como instalar e rodar o projeto</h2>
        <ol>
            <li><strong>Clonar o repositório</strong></li>
            <code>git clone https://github.com/seu-usuario/pokedex-react.git<br>cd pokedex-react</code>
            <li><strong>Instalar dependências</strong></li>
            <code>npm install</code>
            <li><strong>Rodar o projeto</strong></li>
            <code>npm start</code>
            <p>O app será aberto em <code>http://localhost:3000/</code>.</p>
        </ol>
        
        <h2>🛠️ Tecnologias utilizadas</h2>
        <ul>
            <li>⚛️ React.js</li>
            <li>📡 Fetch API</li>
            <li>🎨 CSS3</li>
        </ul>
        
        <h2>📜 Estrutura do projeto</h2>
        <pre>
📂 pokedex-react
 ┣ 📂 src
 ┃ ┣ 📜 App.js       # Componente principal
 ┃ ┣ 📜 style.css    # Estilos da Pokédex
 ┃ ┗ 📜 index.js     # Arquivo de entrada
 ┣ 📜 package.json   # Dependências do projeto
 ┣ 📜 README.md      # Documentação
 ┗ 📜 .gitignore     # Ignorar arquivos desnecessários
        </pre>
    </div>
</body>
</html>
