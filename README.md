🧠 Trivia Web – Desafio CS50

🎯 Sobre o Projeto
Este projeto é uma página da web interativa que permite aos usuários responder perguntas triviais, tanto de múltipla escolha quanto de resposta aberta. O objetivo é praticar HTML, CSS e JavaScript criando uma interface responsiva que avalia as respostas dos usuários em tempo real.

💻 Tecnologias Utilizadas
HTML5

CSS3

JavaScript

⚙️ Como Executar
Siga os passos abaixo para rodar o projeto no ambiente CS50 (ou localmente):

1️⃣ Crie o diretório:

bash
Copiar
Editar
mkdir pset8
cd pset8
2️⃣ Baixe e descompacte o projeto:

bash
Copiar
Editar
wget https://cdn.cs50.net/2023/fall/psets/8/trivia.zip
unzip trivia.zip
rm trivia.zip
cd trivia
3️⃣ Inicie o servidor local para visualizar sua página:

bash
Copiar
Editar
http-server
Abra o link gerado no navegador para interagir com sua trivia!

📝 Estrutura do Projeto
bash
Copiar
Editar
trivia/
├── index.html    # Estrutura da página (perguntas e interatividade)
├── styles.css    # Estilo visual da página
└── script.js     # Lógica em JavaScript (opcional, se separado)
✨ Funcionalidades
✅ Múltipla escolha:

Resposta correta deixa o botão verde + mensagem “Correto!”

Resposta incorreta deixa o botão vermelho + mensagem “Incorreto!”

✅ Resposta livre:

Campo de input + botão de confirmação.

Resposta correta: campo verde + “Correto!”

Resposta incorreta: campo vermelho + “Incorreto!”

🛠 Personalizações
Você pode:

🎨 Editar o styles.css para mudar as cores, fontes e layout.

➕ Adicionar novas perguntas triviais para deixar o quiz mais completo!

🔄 Melhorar a experiência usando efeitos animados com CSS ou JavaScript.

📸 Preview
Pergunta Múltipla Escolha	Pergunta Resposta Livre

(Imagens acima são ilustrativas – substitua por prints reais depois!)

💡 Dicas Úteis
Use document.querySelector para selecionar elementos únicos.

Use addEventListener para capturar cliques e submissões.

Lembre-se de testar todas as possibilidades (resposta certa e errada).

🚀 Próximos Passos (Opcional)
✅ Adicionar suporte para várias perguntas na mesma página.

✅ Implementar pontuação para mostrar a performance do usuário.

✅ Usar localStorage para salvar o progresso entre sessões.

👩‍💻 Desenvolvido por
Feito com ❤️ para o curso CS50 – Harvard.
