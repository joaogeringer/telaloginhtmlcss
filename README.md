<!DOCTYPE html>
    <html lang="pt-br">
        <meta charset="utf-8">
        <head>
            <title>Login</title>
            <rel author="João-Geringer">
            <link rel="stylesheet" type="text/css" href="loginform.css" />
        </head>
        
            <body>
                <div class="container" >
                  <a class="links" id="cadastro"></a>
                  <a class="links" id="login"></a>
                   
                  <div class="content">      
                    
                    <div id="login">
                      <form method="post" action=""> 
                        <h1>Login</h1> 
                        <p> 
                          <label for="nome_login">Nome de usuário ou e-mail</label>
                          <br></br>
                          <input id="nome_login" name="nome_login" required="required" type="text" placeholder="insira aqui"/>
                        </p>
                         
                        <p> 
                          <label for="email_login">Senha</label>
                          <br></br>
                          <input id="email_login" name="email_login" required="required" type="password" placeholder="insira aqui" /> 
                        </p>
                         
                        <p> 
                          <input type="checkbox" name="manterlogado" id="manterlogado" value="" /> 
                          <label for="manterlogado">Mantenha-me logado</label>
                        </p>
                         
                        <p> 
                          <input type="submit" value="Logar" /> 
                        </p>
                         
                        <p class="link">
                          Ainda não tem conta?
                          <a href="#paracadastro">Cadastre-se</a>
                        </p>
                        <p> Selecione sua linguagem
                          <br></br>
                          <input type="text" list="minha-lista">
                          <datalist id="minha-lista">
                            <option value="JavaScript" >  
                                <option value="Flutter" >
                                  <option value="PHP">

                            
                          </datalist>

                        </p>
                      </form>
                    </div>
                </body>
                </html>




html,body{
    background-color: black;
    height: 100%;
    background-image: url("")
}
h1{
    text-align: center;
    border: slateblue;
    padding: 0px;
    margin: 30px;
    font-family: Arial, Helvetica, sans-serif;
    font-size: 50px;
    color: whitesmoke;
}
p{
    text-align: center;
    padding: 0px;
    margin: 30px;
    font-family: Arial, Helvetica, sans-serif
    
;
    font-size: 15px;
    color: slateblue;
    
}
