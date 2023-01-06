# Aprendendo-Layout-
Aprendi Layout no ano de 2022 no mês de maio



<!DOCTYPE html>
<html>
  <head>
      <meta charset="utf-8">
      <title>Usando layout semântico com a turma do módulo 1</title>
      <link rel="stylesheet" href="estiloLayout.css">
      <link rel="stylesheet" href="estiloHeader.css">
      <link rel="stylesheet" href="estiloMenu.css">
      <link rel="stylesheet" href="artigo.css">
      <link rel="stylesheet" href="estiloFooter.css">
    
  </head>
  <body>
    <header>Notícias do Mundo</header>
    <aside>
        <h4>Categorias</h4>
        <ul>
            <li><a href="https://ge.globo.com/" target="_blanc">Esportes</a></li>
            <li><a href="https://economia.uol.com.br/" target="_blanc">Economia</a></li>
            <li><a href="https://www.gov.br/mcti/pt-br" target="_blanc">Ciência e Tecnologia</a></li>
            <li><a href="https://www.gov.br/mma/pt-br" target="_blanc">Natureza</a></li>
            <li><a href="https://www.terra.com.br/vida-e-estilo/moda/" target="_blanc">Moda</a></li>
        </ul>
        <hr />
        <h4 >Contato e Redes Sociais</h4>
        <ul>
            <li><a href="#">Facebook</a></li>
            <li><a href="#">Instagram</a></li>
            <li><a href="#">WhatsApp</a></li>
            <li><a href="#">E-mail</a></li>
        </ul>
    </aside> 
    <article>
        <h1 style="font-family: Arial, sans-serif;">O planeta não está conseguindo respirar bem</h1>
        <h6>Data de publicação: 08 de julho de 2020. Exemplo para a turma de WEB I do CSI.</h6>
        
        <p>
            A Organização das Nações Unidas (ONU) alertou que o mundo precisa limitar o aumento da temperatura média global a menos de 1,5 °C em relação aos níveis pré-industriais. 
            Além de preservar as florestas que já existem, a melhor solução para reduzir drasticamente o excesso de dióxido de carbono na atmosfera e conter o aquecimento global é plantar árvores. Em todos os espaços possíveis do planeta que não são ocupados nem por zonas urbanas, nem destinados a agropecuária. 
        </p>

        <figure>
            <img src="https://andersonandre-csi.neocities.org/Imagens/floresta.jpg" alt="Imagem floresta" height="350" />
            <figcaption>Floresta Amazônica</figcaption>
        </figure>

        <p>
            Isso significaria plantar 1,2 trilhão de novas mudas, um número quatro vezes maior do que a totalidade de árvores que vivem na floresta amazônica. Calcula-se que existam no planeta hoje cerca de 3 trilhões de árvores. 
        </p>

        <table>
            <tr>
                <th>Ranking</th>
                <th>País</th>
                <th>Número de árvores plantadas (jul/2019 a jul/2020)</th>
            </tr>
             <tr>
                <td>1º</td>
                <td>Índia</td>
                <td>11.089.276</td>
            </tr>
            <tr>
                <td>2º</td>
                <td>Estados Unidos</td>
                <td>7.746.621</td>
            </tr>
            <tr>
                <td>3º</td>
                <td>Alemanha</td>
                <td>3.139.401</td>
            </tr>
            <tr>
                <td>4º</td>
                <td>Reino Unido</td>
                <td>1.350.492</td>
            </tr>
            <tr>
                <td>5º</td>
                <td>Suíça</td>
                <td>321.644</td>
            </tr>
            <tr>
                <td>13º</td>
                <td>Brasil</td>
                <td>90.557</td>
            </tr>
        </table>

        <hr />
        
            <h4>Fontes:</h4>
            <nav>
            <ul>
                <li><a href =" https://www.bbc.com/portuguese/geral-46424720">BBC News: Aquecimento global: 7 gráficos que mostram em que ponto estamos</a></li>
                <li><a href = "https://www.agrisustentavel.com/floresta/plantio/um-bilhao-de-arvores.html#:~:text=Fale%20Conosco-,Planeta%20precisa%20de%201%2C2%20trilh%C3%A3o%20de%20novas%20%C3%A1rvores%20para,aquecimento%20global%20%C3%A9%20plantar%20%C3%A1rvores." >BBC News: Planeta precisa de 1,2 trilhão de novas árvores para conter o aquecimento</a></li>
                <li><a href ="https://www1.plant-for-the-planet.org/" >Plant for the planet</a></li>
            </ul>            
            </nav>
    </article>
    <br>
    <hr>
  
    <footer>
      <p>Autor:Anderson<br>
        <a href="andersonandersonandre799@gmail.com">anderson@example.com</a>
      </p>        
    </footer>
</body>
</html>
