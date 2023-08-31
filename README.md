# Melhores-Carros-2023
<!DOCTYPE html>
<html lang="pt-BR">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Elite Automotiva</title>
    <link rel="stylesheet" href="h1 {.css">
</head>
<body>
    
    
    <header>
    
      <h1>Melhores Carros</h1>
      
     
      
     

      <br>
      <section id="secao-menu">
        <div>
      <a href="#" class="botao">Pesquisar</a>
      <a href="#" class="botao">Home</a> 
      <a href="#informacao-carros" class="botao">Informações</a>
      <a href="#" class="botao">Saiba mais</a>
      <a href="#secao-menu" class="botao">Voltar</a>
      <br>
      <p></p>
        </div>
      </section>
      <img src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcSFEUVGXYmsj_yqqrpz_Z1W6rxIEEwpZzMJpA&usqp=CAU.png" alt="">
          
      <br>
      <section id="Informacao-carros">
        <span> Modelo: Polo GTI 2023</span>
      </P>Informações complementares dos modelos listados<P>
      
        
      <img src="https://quatrorodas.abril.com.br/wp-content/uploads/2020/10/003_onix_rs_FLP4958_v2-e1602184840923.jpg?quality=70&strip=info.png" alt="">
     <span>Modelo: Onix Plus 2022</span>
     <P>Informações complementares dos modelos listados</P>
    
    
    
    
    
    </section>
  
    (CSS)
    
:root{
    --primary-color: #aaaaac;
    --font-title: 'Montserrat';
    --font-default: 'inter';
}

h1 {
    color: gold;
    text-shadow: 4px 4px 2px rgba(0, 0, 0, 0.25);
    font-size: 4rem;
    font-family: 'Montserrat';
    font-weight: 700;
}

header {
    height: 100vh;
    position: relative;
    padding-left: 6.8rem;
    padding-top: 16.8rem;
    overflow: hidden;
}
html{
    scroll-behavior: smooth;
}
header::before{
    content: '';
    background-image: url('https://conteudo.imguol.com.br/c/entretenimento/1a/2021/04/14/ford-mustang-mach-1-1618431285090_v2_1170x540.jpg');
    background-size: cover;
    height: 41%;
    width: 70%;
    display: block;
    position: absolute;
    left: 0;
    top: 0;
    z-index: -1;
}

span {
    color: #000000;
    text-shadow: 4px 4px 2px rgba(0, 0, 0, 0.25);
    font-size: 2rem;
}
.botao {
    background-color: #f1f1f5;
    color: rgb(0, 0, 0);
    font-family: 'inter';
    padding: .25rem 1rem;
    border-radius: 4px;
    text-decoration: none;
    transition: opacity 1s;

}



.botao:hover{
 opacity: .5;
 
}
body {
    background-color: #857D75;
    }

    #secao-menu {
        display: flex;
        
    }

    #informacao-carros {
        height: 20%;
        width: 20%;

    }
    
        
