<div align="center">
  <img src="https://theme.zdassets.com/theme_assets/2370142/c8b5137802123ed2a5feb6fa683653ec9520bd67.png" width="600px">
</div>

<br />

<div align="center">
  <h3>Backoffice FindUP</h3>
  <p>
    Sistema de controle geral da FindUP, modulos  de administração geral se encontram aqui.
  </p>
  <p>
</div>

  ## Configuração do Ambiente
  </p>

  <ol>
    <li>Crie o banco de dados</li>
    <li>Faça a configuração do banco criado em /config/app.php</li>
    <li>Verifique no composer.json a versão do PHP mínima para execução do projeto.</li>
    <li>Sabendo da versão, instale as seguintes extensões: mysql, zip, gd, dom, mbstring, intl</li>
    <li>No console, execute o comando: composer install</li>
    <li>Se tiver problema ao tentar acessar alguns modulos (SQLSTATE[42000]: Syntax error or access violation: 1055 Expression #3
of SELECT list is not in GROUP BY clause and contains nonaggregated column), adicione o seguinte comando ao final do seu arquivo de 
    configurações do mysql:
    sql_mode = STRICT_TRANS_TABLES,NO_ZERO_IN_DATE,NO_ZERO_DATE,ERROR_FOR_DIVISION_BY_ZERO,NO_AUTO_CREATE_USER,NO_ENGINE_SUBSTITUTION
    </li>
    <li>
    Salve o arquivo citado acima e reinicie o seu mysql server
    </li>
  </ol>

  ## Observações adicionais
  Não há observações adicionais


<br />

<div align="center">

[![cake-image]][cake-url]

</div>

<div align="center">
  <h3>
    <a href="https://findup.com.br">
      Website
    </a>
    <span> | </span>
    <a href="#">
      Documentação
    </a>    
      <span> | </span>
    <a href="https://admin.findup.com.br">
      Acesso Produção
    </a>    
         <span> | </span>
    <a href="http://admin.findapp.com.br">
      Acesso Dev
    </a>    
  </h3>
</div>

<div align="center">
  <sub>Built with ❤︎ by <a href="https://github.com/findupworks">FindUP</a>
</div>


[cake-image]: https://img.shields.io/badge/CakePHP-PHP-red?logo=cakephp&style=for-the-badge
[cake-url]: https://book.cakephp.org/4/en/index.html "cake"

