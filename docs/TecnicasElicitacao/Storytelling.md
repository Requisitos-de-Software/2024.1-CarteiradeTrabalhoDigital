# Execução do Storytelling

## Sumário
* [Introdução](#Introdução)
* [Coleta de informações](#Coleta-de-informações)
* [Objetivos](#Objetivos)
* [Personas](#Personas)
* [Histórias em quadrinhos](#Histórias-em-quadrinhos)
* [Requisitos encontrados](#Requisitos-encontrados)
* [Conclusão](#Conclusão)
* [Bibliografia](#Bibliografia)
* [Histórico de versão](#Histórico-de-versão)

##  Introdução

Apresentação do documento na imagem 1:

<center>

 **Imagem 1**: Quadrinho de introdução.

<img src="https://raw.githubusercontent.com/Requisitos-de-Software/2024.1-CarteiradeTrabalhoDigital/main/Midia/ImagensStorytelling/quadrinhoIntroducao.png">

  **Fonte:** [Larissa Stéfane](https://github.com/SkywalkerSupreme)
</center>


**Observação:** Os quadrinhos foram criados com a utilização do site [pixton](https://www.pixton.com/welcome) como ferramenta.

## Coleta de informações

Como foi falado em [análise do storytelling](TecnicasElicitacao/AnalisesElicitacoes/AnaliseTecnicaStorytelling.md), o primeiro passo para realizar essa técnica é entender o contexto e as situações em que os usuários encontraram dificuldades de uso. Por isso, um conjunto de informações foram coletadas diretamente dos [comentários do aplicativo na Google Play](https://play.google.com/store/apps/details?id=br.gov.dataprev.carteiradigital&hl=pt_BR&gl=US).

Esses comentários de avaliação servirão como cartões de história, onde os usuários contam as experiências negativas que tiveram.

**Observação:** Como forma de manter a identidade dos autores dos comentário de forma anônima, seus nomes não serão mostrados nas imagens.

Abaixo, de acordo com as imagens 2,3,4,5,6,7,8 e 9, é possível visualizar alguns casos vivenciados.

<center>

 **Imagem 2**: Comentário 1

<img src="https://raw.githubusercontent.com/Requisitos-de-Software/2024.1-CarteiradeTrabalhoDigital/main/Midia/ImagensStorytelling/comentario1.png">

**Fonte:** [Google Play](https://play.google.com/store/apps/details?id=br.gov.dataprev.carteiradigital&hl=pt_BR&gl=US) 
 
</center>

<center>

 **Imagem 3**: Comentário 2

<img src="https://raw.githubusercontent.com/Requisitos-de-Software/2024.1-CarteiradeTrabalhoDigital/main/Midia/ImagensStorytelling/comentario2.png">

**Fonte:** [Google Play](https://play.google.com/store/apps/details?id=br.gov.dataprev.carteiradigital&hl=pt_BR&gl=US) 
 
</center>

<center>

 **Imagem 4**: Comentário 3

<img src="https://raw.githubusercontent.com/Requisitos-de-Software/2024.1-CarteiradeTrabalhoDigital/main/Midia/ImagensStorytelling/comentario3.png">

**Fonte:** [Google Play](https://play.google.com/store/apps/details?id=br.gov.dataprev.carteiradigital&hl=pt_BR&gl=US) 
 
</center>

<center>

 **Imagem 5**: Comentário 4

<img src="https://raw.githubusercontent.com/Requisitos-de-Software/2024.1-CarteiradeTrabalhoDigital/main/Midia/ImagensStorytelling/comentario4.png">

**Fonte:** [Google Play](https://play.google.com/store/apps/details?id=br.gov.dataprev.carteiradigital&hl=pt_BR&gl=US) 
 
</center>

<center>

 **Imagem 6**: Comentário 5

<img src="https://raw.githubusercontent.com/Requisitos-de-Software/2024.1-CarteiradeTrabalhoDigital/main/Midia/ImagensStorytelling/comentario5.png">

**Fonte:** [Google Play](https://play.google.com/store/apps/details?id=br.gov.dataprev.carteiradigital&hl=pt_BR&gl=US) 
 
</center>

<center>

 **Imagem 7**: Comentário 6

<img src="https://raw.githubusercontent.com/Requisitos-de-Software/2024.1-CarteiradeTrabalhoDigital/main/Midia/ImagensStorytelling/comentario6.png">

**Fonte:** [Google Play](https://play.google.com/store/apps/details?id=br.gov.dataprev.carteiradigital&hl=pt_BR&gl=US) 
 
</center>

<center>

 **Imagem 8**: Comentário 7

<img src="https://raw.githubusercontent.com/Requisitos-de-Software/2024.1-CarteiradeTrabalhoDigital/main/Midia/ImagensStorytelling/comentario7.png">

**Fonte:** [Google Play](https://play.google.com/store/apps/details?id=br.gov.dataprev.carteiradigital&hl=pt_BR&gl=US) 
 
</center>

<center>

 **Imagem 9**: Comentário 8

<img src="https://raw.githubusercontent.com/Requisitos-de-Software/2024.1-CarteiradeTrabalhoDigital/main/Midia/ImagensStorytelling/comentario8.png">

**Fonte:** [Google Play](https://play.google.com/store/apps/details?id=br.gov.dataprev.carteiradigital&hl=pt_BR&gl=US) 
 
</center>

Além da Google Play, outros comentários também foram adquiridos por meio da [Apple Store](https://apps.apple.com/br/app/carteira-de-trabalho-digital/id1295257499) 

Abaixo, de acordo com as imagens 10 e 11 é possível visualizar mais alguns casos.

<center>

 **Imagem 10**: Comentário 9

<img src="https://raw.githubusercontent.com/Requisitos-de-Software/2024.1-CarteiradeTrabalhoDigital/main/Midia/ImagensStorytelling/comentario9.png">

**Fonte:** [Google Play](https://play.google.com/store/apps/details?id=br.gov.dataprev.carteiradigital&hl=pt_BR&gl=US) 
 
</center>

<center>

 **Imagem 11**: Comentário 10

<img src="https://raw.githubusercontent.com/Requisitos-de-Software/2024.1-CarteiradeTrabalhoDigital/main/Midia/ImagensStorytelling/comentario10.png">

**Fonte:** [Google Play](https://play.google.com/store/apps/details?id=br.gov.dataprev.carteiradigital&hl=pt_BR&gl=US) 
 
</center>

## Personas

Segundo a [conjuntura e análise do Mercado de trabalho](https://portalantigo.ipea.gov.br/agencia/images/stories/PDFs/mercadodetrabalho/218241_bmt_73_nt_a1.pdf) realizada pelo IPEA em 2022, 62,4% das mulheres brasileiras entre 18 e 59 anos vivendo em áreas urbanas estavam na força de trabalho em 2020; para os homens, essa taxa era de 80,8%. 

Assim, para manter um padrão em relação ao gênero das pessoas que estão no mercado de trabalho e que podem vir a utilizar o aplicativo, das 10 personas criadas para as histórias em quadrinho, 5 serão homens, 4 serão mulheres e 1 será não binário.

Ainda em relação à  [Conjuntura e Análise do Mercado de trabalho](https://portalantigo.ipea.gov.br/agencia/images/stories/PDFs/mercadodetrabalho/218241_bmt_73_nt_a1.pdf), foi mostrado que há uma redução na chance de participar da força de trabalho, à medida que a idade aumenta. Desse modo, entre as personas utilizadas, 4 serão jovens adultos, 4 serão adultos e 2 serão idosos.

As personas foram criadas como personagens de cartoon para as histórias. Elas estão apresentadas na tabela 1 por meio das imagens 12 a 21:

**Tabela 1**: Apresentando as personas utilizadas

<table style="margin-left: auto; margin-right: auto;">
    <tr>
        <td align="center">
                <h5 class="text-center"> Imagem 12: Usuário 1: Jovem 1 </h5>
                <img style="border-radius: 50%;" src="https://raw.githubusercontent.com/Requisitos-de-Software/2024.1-CarteiradeTrabalhoDigital/main/Midia/ImagensStorytelling/usu%C3%A1rio1.png" width="160px;"/>
                <h5 class="text-center"> Fonte: Larissa Stéfane  </h5>
            </a>
        </td>
        <td align="center">
                <h5 class="text-center"> Imagem 13: Usuário 2: Idoso 1 </h5>
                <img style="border-radius: 50%;" src="https://raw.githubusercontent.com/Requisitos-de-Software/2024.1-CarteiradeTrabalhoDigital/main/Midia/ImagensStorytelling/usu%C3%A1rio2.png" width="160px;"/>
                <h5 class="text-center"> Fonte: Larissa Stéfane  </h5>
            </a>
        </td>
        <td align="center">
                <h5 class="text-center"> Imagem 14: Usuário 3: Mulher 1 </h5>
                <img style="border-radius: 50%;" src="https://raw.githubusercontent.com/Requisitos-de-Software/2024.1-CarteiradeTrabalhoDigital/main/Midia/ImagensStorytelling/usu%C3%A1rio3.png" width="160px;"/>
                <h5 class="text-center"> Fonte: Larissa Stéfane  </h5>
            </a>
        </td>
         <td align="center">
                <h5 class="text-center"> Imagem 15: Usuário 4: Homem 1 </h5>
                <img style="border-radius: 50%;" src="https://raw.githubusercontent.com/Requisitos-de-Software/2024.1-CarteiradeTrabalhoDigital/main/Midia/ImagensStorytelling/usuario4.png" width="160px;"/>
                <h5 class="text-center"> Fonte: Larissa Stéfane  </h5>
            </a>
        </td>
      <td align="center">
                <h5 class="text-center"> Imagem 16: Usuário 5: Idosa 1 </h5>
                <img style="border-radius: 50%;" src="https://raw.githubusercontent.com/Requisitos-de-Software/2024.1-CarteiradeTrabalhoDigital/main/Midia/ImagensStorytelling/usu%C3%A1rio5.png" width="160px;"/>
                <h5 class="text-center"> Fonte: Larissa Stéfane  </h5>
            </a>
        </td>
</table>

<table style="margin-left: auto; margin-right: auto;">
    <tr>
        <td align="center">
                <h5 class="text-center"> Imagem 17: Usuário 6: Jovem 2 </h5>
                <img style="border-radius: 50%;" src="https://raw.githubusercontent.com/Requisitos-de-Software/2024.1-CarteiradeTrabalhoDigital/main/Midia/ImagensStorytelling/usuario6.png" width="160px;"/>
                <h5 class="text-center"> Fonte: Larissa Stéfane  </h5>
            </a>
        </td>
        <td align="center">
                <h5 class="text-center"> Imagem 18: Usuário 7: Jovem 3 </h5>
                <img style="border-radius: 50%;" src="https://raw.githubusercontent.com/Requisitos-de-Software/2024.1-CarteiradeTrabalhoDigital/main/Midia/ImagensStorytelling/usu%C3%A1rio7.png" width="160px;"/>
                <h5 class="text-center"> Fonte: Larissa Stéfane  </h5>
            </a>
        </td>
        <td align="center">
                <h5 class="text-center"> Imagem 19: Usuário 8: Homem 2 </h5>
                <img style="border-radius: 50%;" src="https://raw.githubusercontent.com/Requisitos-de-Software/2024.1-CarteiradeTrabalhoDigital/main/Midia/ImagensStorytelling/usuario8.png" width="160px;"/>
                <h5 class="text-center"> Fonte: Larissa Stéfane  </h5>
            </a>
        </td>
         <td align="center">
                <h5 class="text-center"> Imagem 20: Usuário 9: Mulher 2 </h5>
                <img style="border-radius: 50%;" src="https://raw.githubusercontent.com/Requisitos-de-Software/2024.1-CarteiradeTrabalhoDigital/main/Midia/ImagensStorytelling/usu%C3%A1rio9.png" width="160px;"/>
                <h5 class="text-center"> Fonte: Larissa Stéfane  </h5>
            </a>
        </td>
        <td align="center">
                <h5 class="text-center"> Imagem 21: Usuário 10: Jovem 4 </h5>
                <img style="border-radius: 50%;" src="https://raw.githubusercontent.com/Requisitos-de-Software/2024.1-CarteiradeTrabalhoDigital/main/Midia/ImagensStorytelling/usu%C3%A1rio10.png" width="160px;"/>
                <h5 class="text-center"> Fonte: Larissa Stéfane  </h5>
            </a>
        </td>
      
</table>

**Fonte:** [Larissa Stéfane](https://github.com/SkywalkerSupreme)

## Histórias em quadrinhos

### Caso 1: Quando o aplicativo é recusado por empresas.

A imagem 22 mostra o caso:

<center>

 **Imagem 22**: Quadrinho 01

<img src="https://raw.githubusercontent.com/Requisitos-de-Software/2024.1-CarteiradeTrabalhoDigital/main/Midia/ImagensStorytelling/quadrinho1.png">

  **Fonte:** [Larissa Stéfane](https://github.com/SkywalkerSupreme)
</center>

**Requisito**: O aplicativo deve seguir um padrão que é aceito por empresas e outras instituições sem provocar transtornos.


### Caso 2: Erro para abrir o aplicativo.

A imagem 23 mostra o caso:

<center>

 **Imagem 23**: Quadrinho 02

<img src="https://raw.githubusercontent.com/Requisitos-de-Software/2024.1-CarteiradeTrabalhoDigital/main/Midia/ImagensStorytelling/quadrinho2.png">

  **Fonte:** [Larissa Stéfane](https://github.com/SkywalkerSupreme)
</center>

**Requisito:** O aplicativo não deve apresentar erros de abertura e deve ser de fácil acesso para o usuário. 


### Caso 3: Informações erradas e inconsistentes. 

A imagem 24 mostra o caso:

<center>

 **Imagem 24**: Quadrinho 03

<img src="https://raw.githubusercontent.com/Requisitos-de-Software/2024.1-CarteiradeTrabalhoDigital/main/Midia/ImagensStorytelling/quadrinho3.png">

  **Fonte:** [Larissa Stéfane](https://github.com/SkywalkerSupreme)
</center>

**Requisito:** O aplicativo não apresentar dados que sejam coerentes com o usuário e não fazer troca de dados.

### Caso 4: Informações diferentes das disponibilizadas pelo site. 

A imagem 25 mostra o caso:

<center>

 **Imagem 25**: Quadrinho 04

<img src="https://raw.githubusercontent.com/Requisitos-de-Software/2024.1-CarteiradeTrabalhoDigital/main/Midia/ImagensStorytelling/quadrinho4.png">

  **Fonte:** [Larissa Stéfane](https://github.com/SkywalkerSupreme)
</center>

**Requisito:** O aplicativo deve estar sincronizado e coerente com as informações do site da Carteira de Trabalho.

### Caso 5: Dificuldade para atualizar dados e muita burocracia.

A imagem 26 mostra o caso:

<center>

 **Imagem 26**: Quadrinho 05

<img src="https://raw.githubusercontent.com/Requisitos-de-Software/2024.1-CarteiradeTrabalhoDigital/main/Midia/ImagensStorytelling/quadrinho5.png">

  **Fonte:** [Larissa Stéfane](https://github.com/SkywalkerSupreme)
</center>

**Requisito:** O aplicativo deve permitir que o usuário atualize seus dados sem lhe causar transtornos, além de evitar burocracias em diversos pontos.


### Caso 6: Falta de informações essenciais.

A imagem 27 mostra o caso:

<center>

 **Imagem 27**: Quadrinho 06

<img src="https://raw.githubusercontent.com/Requisitos-de-Software/2024.1-CarteiradeTrabalhoDigital/main/Midia/ImagensStorytelling/quadrinho6.png">

  **Fonte:** [Larissa Stéfane](https://github.com/SkywalkerSupreme)
</center>

**Requisito:** Existem informações essenciais para os trabalhadores e, para facilitar o acesso a elas, os aplicativos disponibilizam-nas.


### Caso 7: Problemas com a biometria ou identificação facial.

A imagem 28 mostra o caso:

<center>

 **Imagem 28**: Quadrinho 07

<img src="https://raw.githubusercontent.com/Requisitos-de-Software/2024.1-CarteiradeTrabalhoDigital/main/Midia/ImagensStorytelling/quadrinho7.png">

  **Fonte:** [Larissa Stéfane](https://github.com/SkywalkerSupreme)
</center>

**Requisito:** O acesso a alguns pontos do aplicativo exige a biometria, assim, para evitar transtorno aos usuários, ela deve ser eficiente e prática.


### Caso 8: Alarmes falsos ou notificações erradas.

A imagem 29 mostra o caso:

<center>

 **Imagem 29**: Quadrinho 08

<img src="https://raw.githubusercontent.com/Requisitos-de-Software/2024.1-CarteiradeTrabalhoDigital/main/Midia/ImagensStorytelling/quadrinho8.png">

  **Fonte:** [Larissa Stéfane](https://github.com/SkywalkerSupreme)
</center>

**Requisito:** O aplicativo deve mandar notificações que informem situações verdadeiras e não falsas, ou seja, não deve dar alarmes falsos.


### Caso 9: O aplicativo não está disponível para todos os tipos de sistemas operacionais.

A imagem 30 mostra o caso:

<center>

 **Imagem 30**: Quadrinho 09

<img src="https://raw.githubusercontent.com/Requisitos-de-Software/2024.1-CarteiradeTrabalhoDigital/main/Midia/ImagensStorytelling/quadrinho9.png">

  **Fonte:** [Larissa Stéfane](https://github.com/SkywalkerSupreme)
</center>

**Requisito:** O aplicativo deve estar adaptado para ser instalado em qualquer sistema operacional, como Android ou iOS. Isso facilita a democratização do seu uso.

### Caso 10: Informações e dados desatualizados.

A imagem 31 mostra o caso:

<center>

 **Imagem 31**: Quadrinho 10

<img src="https://raw.githubusercontent.com/Requisitos-de-Software/2024.1-CarteiradeTrabalhoDigital/main/Midia/ImagensStorytelling/quadrinho10.png">

  **Fonte:** [Larissa Stéfane](https://github.com/SkywalkerSupreme)
</center>

**Requisito:** O aplicativo deve atualizar os dados do usuário constantemente e evitar que eles fiquem defasados.

## Requisitos encontrados

Por meio da análise dos histórias realizadas, foi possível elencar os seguintes requisitos:

  1. O aplicativo deve seguir um padrão que é aceito por empresas e outras instituições sem provocar transtornos.
  2. O aplicativo não deve apresentar erros de abertura e deve ser de fácil acesso para o usuário.
  3. O aplicativo não apresentar dados que sejam coerentes com o usuário e não fazer troca de dados.
  4. O aplicativo deve estar sincronizado e coerente com as informações do site da Carteira de Trabalho.
  5. O aplicativo deve permitir que o usuário atualize seus dados sem lhe causar transtornos, além de evitar burocracias em diversos pontos.
  6. Existem informações essenciais para os trabalhadores e, para facilitar o acesso a elas, os aplicativos disponibilizam-nas.
  7. O acesso a alguns pontos do aplicativo exige a biometria, assim, para evitar transtorno aos usuários, ela deve ser eficiente e prática.
  8. O aplicativo deve mandar notificações que informem situações verdadeiras e não falsas, ou seja, não deve dar alarmes falsos.
  9. O aplicativo deve estar adaptado para ser instalado em qualquer sistema operacional, como Android ou iOS. Isso facilita a democratização do seu uso.
  10. O aplicativo deve atualizar os dados do usuário constantemente e evitar que eles fiquem defasados.
    

## Conclusão:

Conclusão do documento na imagem 32:

<center>

 **Imagem 32**: Quadrinho de conclusão.

<img src="https://raw.githubusercontent.com/Requisitos-de-Software/2024.1-CarteiradeTrabalhoDigital/main/Midia/ImagensStorytelling/quadrinhoconclusao.png">

  **Fonte:** [Larissa Stéfane](https://github.com/SkywalkerSupreme)
</center>


##  Bibliografia

1. **Comentários Apple Sote**. Disponível em < https://apps.apple.com/br/app/carteira-de-trabalho-digital/id1295257499 > . Acesso em 12 de abril de 2024.
 
2. **Comentários Google Play**. Disponível em < https://play.google.com/store/apps/details?id=br.gov.dataprev.carteiradigital&hl=pt_BR&gl=US > Acesso em 12 de abril de 2024.

3.  **Conjuntura e análise do Mercado de trabalho**. Disponível em < https://portalantigo.ipea.gov.br/agencia/images/stories/PDFs/mercadodetrabalho/218241_bmt_73_nt_a1.pdf > Acesso em 12 de abril de 2024.

4. **Storytelling - Wiki**. Disponível em < https://requisitos-tinder.github.io/Tinder-2018-1/elicitacao/storytelling/ > Acesso em 12 de abril de 2024.

5. **Pixton**. Disponível em < https://www.pixton.com/welcome >. Acesso em 12 e 13 de abril de 2024.

## Histórico de Versão

| Versão | Alteração | Responsável | Revisor | Data |
| - | - | - | - | - |
| 1.0 | Criação e execução do storytelling | Larissa Stéfane | -  | 13/04 |
