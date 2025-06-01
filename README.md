<!DOCTYPE html>

<html>

<!--Descrição do projeto-->
<head>
    <title>Como tomar?</title>
    <meta name="Etiqueta de Posologia para Idosos" content="Etiqueta para facilitar a tomada correta de medicamentos dos idosos ao voltarem para casa."> 
</head>
 <body>
    <main>
        <header>

<!--Tabela para digitação de medicamentos e posologia-->

        <table border="2">
            <thead>
                <tr>
                    <th>
                        <h2>Como tomar meu medicamento?</h2>
                    </th>
                </tr>
            </thead>
            <tbody>
                <section>
                    <form>
                        <tr>
                            <td style="text-align: center;">Nome do Medicamento: <br>
                                <input type="text" id="medicamento" name="medicamento" placeholder="Digite o medicamento..."> </td>
                        </tr>
                        
                        <tr>
                            <td style="text-align: center;">Apresentação:  <br> 
                                <input type="text" id="apresentacao" name="apresentacao" placeholder="Digite a apresentação..."> </td>
                        </tr>

                        <tr>
                            <td style="text-align: center;">Como tomar?: <br> 
                                <input type="text" id="posologia" name="posologia" placeholder="Digite a posologia..."> </td>
                        </tr>

                        <tr>
                            <td style="text-align: center;">Início de tratamento: <br> 
                                <input type="date" id="tratamento1" name="tratamento1"> </td>
                        </tr>

                        <tr>
                            <td style="text-align: center;">Final de tratamento: <br> 
                                <input type="date" id="tratamento2" name="tratamento2"> </td>
                        </tr>
                        <tr>
                            <td style="text-align: center;">Observações: <br> 
                                <input type="text" id="obs" name="obs" placeholder="Digite a observação..."></td>
                        </tr>
                    </form>
                </section>
                </table>

<!--Acessibilidade para não alfabetizados-->
                <section>
                    <details>
                        <summary>Clique aqui, e abra a acessibilidade para não alfabetizados</summary>
                        <table border="2">
            <thead>
                <tr>
                    <th>
                        <h2>Como tomar meu medicamento?</h2>
                    </th>
                </tr>
            </thead>
            <tbody>
                <section>
                <tr>
                    <td style="text-align: center;">Nome do Medicamento:(Cuidador) <br>
                         <input type="text" id="medicamento" name="medicamento" placeholder="Digite o medicamento..."> </td>
                </tr>
                
<!--Tabela de imagens - Apresentação do medicamento-->
                <tr>
                    <form>
                        <td style="text-align: center;">Apresentação: <br>                      
                        <figure>
                            <img src="./assets/Pills.jpg" width="50" style="float: inline-start;" alt="Pílulas">                        
                        </figure>

                        <figure>
                            <img src="./assets/Syrup.jpg" width="50" style="float: inline-start;" alt="Xarope">                        
                        </figure>

                        <figure>
                            <img src="./assets/ointment.jpg" width="50" style="float: inline-start;" alt="Pomada">                        
                        </figure>

                        <figure>
                            <img src="./assets/Syringe.jpg" width="50" style="float: inline-start;" alt="Insulina">                        
                        </figure>

                        <figure>
                            <img src="./assets/eyedrops.jpg" width="50" style="float: inline-start;" alt="Colírio">                        
                        </figure>
                        </td>
                    </form>


                </tr>

<!--Imagens em Como Tomar?-->
                <tr>
                    <td style="text-align: center;">Como tomar?: <br>                      
                        <figure>
                            <img src="./assets/Plate breakfast.png" width="80" style="float: left;" alt="Pílulas">
                                                 
                        </figure>
                                           
                        <figure>
                            <img src="./assets/Plate lunch.png" width="80" style="float: left;" alt="Pílulas">                     
                        </figure>
                       
                    
                        <figure>
                            <img src="./assets/Plate Night.png" width="75" style="float: left;" alt="Pílulas">
                       
                        </figure>
                        
                </form>

                </tr>
                
<!--Observações para os cuidadores-->
                <tr>
                    <td style="text-align: center;">Observações (Cuidador): <br> 
                        <input type="text" id="obs" name="obs" placeholder="Digite a observação..."> </td>
                </tr>
                </section>
                </table>
                    </details>
                </section>
            </tbody>
        
        </header>
    </main>
 </body>
<footer> 
    <tfoot><p>&copy; Todos os direitos reservados. Feito por Jennifer Guedes - 244457</p></tfoot> 
</footer>

</html>
