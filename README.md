🚀 Quiz de Linguagens de Programação - Angular

Este é um projeto desenvolvido em Angular que apresenta um quiz interativo sobre linguagens de programação. O projeto foi criado para explorar conceitos fundamentais do framework, como estilização de componentes, estruturação do HTML, dinamização de parâmetros, divisão de componentes e simulação de dados de uma API via JSON.

📌 Tecnologias Utilizadas
- Angular (Estruturação e dinamização do app)
 
- TypeScript (Tipagem e lógica)
 
- CSS (Estilização dos componentes)
 
- JSON (Simulação de dados de uma API)

📖 Que conceitos aprendi e pratiquei nesse projeto?

✔ Estruturar um projeto Angular corretamente

✔ Dividir a aplicação em componentes reutilizáveis

✔ Estilizar componentes Angular com CSS

✔ Dinamizar parâmetros utilizando interpolação e data binding

✔ Simular dados vindos de uma API usando um arquivo JSON local

🛠 Como rodar o projeto?

1.	Clone o repositório

 ```
git clone https://github.com/seu-usuario/seu-repositorio.git
cd seu-repositorio
```
	
  2.	Instale as dependências
```
npm install
```
  3.	Inicie o servidor de desenvolvimento
```
ng s -o
```

📂 Estrutura do projeto
```
📂 src/
 ┣ 📂 app/
 ┃ ┣ 📂 components/
 ┃ ┃ ┣ 📂 quiz/  # Componente principal do quiz
 ┃ ┃ ┃ ┣ 📜 quiz.component.html  # Estrutura do quiz
 ┃ ┃ ┃ ┣ 📜 quiz.component.css   # Estilos do quiz
 ┃ ┃ ┃ ┗ 📜 quiz.component.ts    # Lógica do quiz
 ┃ ┗ 📜 app.module.ts  # Configuração do módulo principal
 ┣ 📂 assets/
 ┃ ┣ 📂 imgs/  # Armazena imagens do projeto
 ┃ ┗ 📜 quizz_questions.json  # Simulação dos dados da API
 ┗ 📜 index.html  # Página principal
```


📜 Estrutura do JSON

O quiz utiliza um arquivo quizz_questions.json que contém as perguntas e respostas:
```
{
  "title": "Qual linguagem de programação combina mais com você?",
  "questions": [
    {
      "id": 1,
      "question": "Qual dessas qualidades você valoriza mais em uma linguagem?",
      "options": [
        { "id": 1, "name": "Rapidez e eficiência", "alias": "A" },
        { "id": 2, "name": "Facilidade de aprendizado", "alias": "B" }
      ]
    }
  ],
  "results": {
    "A": "Você combina mais com C/C++!",
    "B": "Você combina mais com Python!"
  }
}

```


🎨 Estilização

A estilização dos componentes foi feita utilizando CSS puro, com foco na responsividade e na experiência do usuário.

✨ Funcionalidades

✅ Perguntas dinâmicas baseadas no JSON
✅ Interpolação de dados no template
✅ Estilização com CSS para uma melhor experiência
✅ Simulação de API com arquivo JSON

📌 Melhorias futuras
-	Adicionar integração real com uma API
-	Criar um sistema de ranking e pontuação
