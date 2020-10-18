<img id="cover" align="center" src="https://ik.imagekit.io/ocq8ayf2ug/happy-cover_NoPuC3-3C.png" alt="Cover" />

<h1 id="title" align="center">Happy</h1>

<div align="center">
  <a href="#description">Descrição</a> |
  <a href="#preview">Demonstração</a> |
  <a href="#technologies">Tecnologias</a> |
  <a href="#how-to-use">Como utilizar</a> |
  <a href="#info">Informações adicionais</a> |
  <a href="#license">Licença</a>
</div>

<h2 id="description">📑️ Descrição</h2>
<p>
  A Happy é uma plataforma de conexão entre crianças que residem em orfanatos e pessoas que desejam fazer uma visita a algum orfanato. Tanto na versão web, quanto na versão mobile um orfanato pode se cadastrar na plataforma informando vários dados importantes, dentre eles a localização do orfanato no mapa, horários de funcionamento e instruções para a visita. O usuário que deseja visitar um orfanato pode visualizar no mapa os que estão mais próximos da sua localização e clicar no ícone do orfanato no mapa para acessar todas as informações deste para poder realizar uma visita.
</p>

<h2 id="preview">📽️ Demonstração</h2>

<h3 align="center">WEB</h3>

<div align="center">
  <img src="https://ik.imagekit.io/ocq8ayf2ug/happy-web_b7RrCmoqH.gif" alt="Happy web"/>
</div>

<h3 align="center">MOBILE</h3>

<div align="center">
  <img src="https://ik.imagekit.io/ocq8ayf2ug/happy-mobile_jJmkvxd9s.gif" alt="Happy mobile"/>
</div>

<h2 id="technologies">💻️ Tecnologias</h2>
<ul>
  <li>🌐️ Web:</li>
  <div>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;- Frontend: React</li></div>
  <div>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;- Backend: NodeJs</li></div>
  <li>📱️ Aplicativo: React Native</li>
  <li>💾️ Banco de dados: Typeorm e Sqlite3</li>
  <li>⌨️ Linguagem de programação: Typescript</li>
</ul>

<h2 id="how-to-use">👨🏽‍💻️ Como utilizar</h2>

<h3>1. Baixe o projeto:</h3>

```
  # Se você usa HTTPS
  git clone https://github.com/MisaelAugusto/next-level-week-3.0.git

  # Se você usa SSH
  git clone git@github.com:MisaelAugusto/next-level-week-3.0.git
```

<h3>2. Instale as dependências:</h3>

```
  # vá para o diretório do projeto
  cd next-level-week-3.0

  # vá para cada pasta do projeto e instale as depedências
  cd server
  yarn install

  cd ../web
  yarn install

  cd ../mobile
  yarn install
```

<h3>3. Configure o banco de dados:</h3>

```
  # vá para o diretório do backend
  cd server

  # execute as migrations
  yarn typeorm migration:run
```

<h3>4. Execute o backend:</h3>

```
  # vá para o diretório do backend
  cd server

  # inicie o backend
  yarn start

  # mantenha em execução em uma aba do terminal separada
```

<h3>5. Execute o projeto:</h3>

<h4>5.1. Web</h4>

```
  # vá para o diretório do frontend
  cd web

  # inicie o frontend
  yarn start

  # acesse http://localhost:3000 no seu navegador
```

<h4>5.2. Mobile</h4>

<h5>Nota: Para testar o aplicativo mobile é necessário ter o expo instalado globalmente na sua máquina e o aplicativo expo no seu dispositivo móvel.</h5>

```
  # vá para o diretório do mobile
  cd mobile

  # abra o arquivo 'api.ts' na pasta services e modifique o
  # atributo 'baseURL' de acordo com o ip da sua rede

  # inicie o aplicativo
  yarn start

  # Utilize o aplicativo do expo para ler o QRcode
```

<h2 id="info">📌️ Informações adicionais</h2>
<h3 id="status">&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;🔎️ Status do projeto</h3>
<p>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;O projeto está finalizado. ✔️</p>

<h3 id="contributing">&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;📊️ Contribuição</h3>
<p>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Para contribuir com o projeto de qualquer forma, é necessário realizar um 'fork' do repositório e seguir as instruções da seção acima, fazer suas alterações e / ou atualizações e enviar um 'pull request'. Estou aberto a todas as sugestões!</p>

<h3 id="feedback-support">&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;💬️ Comentários e Suporte</h3>
<p>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Se você tiver alguma dúvida sobre o projeto, como contribuir ou quiser me enviar algum comentário, não hesite em entrar em contato comigo através do meu endereço de e-mail clicando <a href="https://mail.google.com/mail/u/0/?view=cm&fs=1&to=misael.costa@ccc.ufcg.edu.br&su=(Comentário ou Suporte) para 'Happy'&tf=1">aqui</a>.</p>

<h2 id="license">📜️ Licença</h2>
<div>
  <div>
    Esse projeto está sob a licença MIT. Veja o arquivo <a href="LICENSE">LICENSE</a> para mais detalhes.
  </div>
  <div align="right">
    <a href="#cover">Voltar ao topo ⬆️</a>
  </div>
</div>

---
<p>Desenvolvido com 💙️ por Misael Augusto</p>
