## SIG ou Softgoal Interdependency Graph

Ainda de acordo com  a dissertação “Um Catálogo de Requisitos Não-Funcionais para Sistemas Embarcados”¹, de Reinaldo Antônio da Silva, o SIG, ou Softgoal Interdependency Graph, é uma representação gráfica das considerações do desenvolvedor sobre os requisitos em formato de softgoals e suas interdependências em um projeto de software. Desse modo, ele serve como uma ferramenta visual  para registrar as decisões de desenvolvimento, incluindo requisitos não funcionais, de alternativas e de justificativas associadas. Portanto, por meio do SIG, é possível construir, elaborar, analisar e revisar a lógica do projeto de forma clara e acessível.

Neste contexto, a equipe irá utilizar o SIG  como uma ferramenta para entender e gerenciar os diversos aspectos dos requisitos não funcionais do sistema. Para isso, será levado em conta alguns campos críticos, como usabilidade, desempenho, restrição de design, interfaces e acessibilidade, que serão mapeados e representados no SIG para permitir uma visualização clara das interdependências entre eles. 

### Os softgoals

De acordo com Chung², Há três tipos de softgoals:

- **Softgoals NFR:** Representam os Requisitos Não-Funcionais.
  - Podem estar interrelacionados, organizados em catálogos e apresentados de forma hierárquica.

- **Softgoals de operacionalização**: Essas soluções incluem operações, processos, representações de dados, estruturações e restrições no sistema.

- **Softgoals de Afirmação:** permitem que as características do domínio (como prioridades e carga de trabalho) sejam consideradas e devidamente refletidas no processo de tomada de decisão.
  - Servem como justificativa para apoiar ou negar a forma como os softgoals são priorizados.
 
A figura 1 mostra a legenda dos softgoals que serão utilizados nos SIG do projeto.

 <center> 
  <font size="2"><p style="text-align: center">Figura 1: Legenda Softgoals. </p></font>
  <img src="https://raw.githubusercontent.com/Requisitos-de-Software/2024.1-CarteiradeTrabalhoDigital/main/docs/ImagensDiagrama/ImagensEntrega4/legenda_nfrframework.drawio.png">
  <font size="2"><p style="text-align: center"> Autora: Larissa Stéfane </p></font>
 </center>

### Contribuições entre Softgoals

Contribuições são formas de descrever como um softgoal (um objetivo não funcional) afeta outro no contexto de um projeto de desenvolvimento de software. Elas indicam se a satisfação de um objetivo contribui de forma positiva, negativa ou neutra para a satisfação de outro objetivo. Desse modo, em “Um Catálogo de Requisitos Não-Funcionais para Sistemas Embarcados”¹, de Reinaldo Antônio da Silva, é citado que Chung definiu as seguintes contribuições para os diagramas:

- **AND**: Determina que se os softgoals descendentes forem satisfeitos os softgoals ascendentes serão satisfeitos.
- **OR**: Determina que, se algum softgoal descendente for satisfeito, o ascendente será satisfeito.
- **MAKE(++):** Fornece uma contribuição suficientemente positiva entre um softgoal descendente e um softgoal ascendente que é concebida no nível mais alto de satisfação. Dessa forma, ao utilizarmos MAKE, se o softgoal descendente for satisfeito o softgoal pai também será satisfeito.
- **BREAK(- -):** Fornece uma contribuição suficientemente negativa entre um softgoal descendente e um softgoal ascendente que é concebida no nível mais alto de negação. Portanto, ao utilizar BREAK, se o softgoal descendente for suficientemente satisfeito o softgoal pai será negado, ou seja, não será satisfeito.
- **HELP(+):** Fornece uma contribuição parcialmente positiva entre um softgoal descendente e um softgoal ascendente. Dessa forma, ao utilizar HELP, se o softgoal descendente for parcialmente satisfeito o softgoal ascendente será parcialmente satisfeito.
- **HURT(-):** Fornece uma contribuição parcialmente negativa entre um softgoal descendente e um softgoal ascendente. Dessa forma, ao utilizar HURT, se o softgoal descendente for satisfeito o softgoal ascendente será parcialmente negado.
- **UNKNOWN(?):** Fornece uma contribuição desconhecida entre um softgoal descendente e um softgoal ascendente, podendo ser tanto positiva quanto negativa.
- **EQUALS:** Determina que o softgoal descendente só será satisfeito se o softgoal ascendente for satisfeito e que o softgoal descendente será negado se o softgoal ascendente for negado.
- **SOME:** É utilizada quando o sinal da contribuição é conhecido (positivo ou negativo), mas a extensão (parcial ou total) não é. Nesses casos, quando há alguma incerteza em se utilizar HELP ou MAKE deve-se utilizar o tipo de contribuição SOME +. Da mesma forma, quando não há certeza em se utilizar HURT ou BREAK deve-se utilizar SOME -.

### Metodologia para o SIG

A metodologia que a equipe irá adotar para elaborar os SIG do projeto se baseará em uma série de etapas. Inicialmente, a partir das diversas formas de elicitação dos requisitos não funcionais e da análise da tabela dos requisitos não elicitados, alguns membros da equipe realizarão um estudo mais profundo sobre alguns tópicos específicos e sobre a própria estrutura e funcionamento do SIG, por exemplo, sobre as restrições de design. Assim, esse estudo proporcionará um entendimento mais completo das necessidades do sistema e, com base nesse conhecimento adquirido, proceder-se-á à elaboração dos SIGs, que consistirão em representações gráficas das interdependências entre os softgoals identificados.

Consequentemente, esses SIGs servirão como ferramentas fundamentais para a descoberta de novos requisitos não funcionais até então não considerados, bem como para o aprofundamento e detalhamento dos requisitos já elicitados.

### Os NFR framework

### NFR - Restrições de Design

Por meio do estudo dos requisitos não funcionais [RNF05](Elicitacao/ResquisitosCorrigidos.md), [RNF07](Elicitacao/ResquisitosCorrigidos.md), [RNF10](Elicitacao/ResquisitosCorrigidos.md) e [RNF12](Elicitacao/ResquisitosCorrigidos.md), foi elaborado um diagrama SIG para o campo de restrições de designe, sendo possível visualizá-lo na figura 2.

<details>
  <summary size="20"><b> Figura 2: NFR - Restrições de Design    </b></summary> 

 <center> 
  <font size="2"><p style="text-align: center">Figura 2: NFR restrições de Design. </p></font>
  <img src="https://raw.githubusercontent.com/Requisitos-de-Software/2024.1-CarteiradeTrabalhoDigital/main/docs/ImagensDiagrama/ImagensEntrega4/RestricoesDesign_NFRframework2.png">
  <font size="2"><p style="text-align: center"> Autora: Larissa Stéfane </p></font>
 </center>

Para visualizar melhor o diagrama, clique em [NFR - Restrições de Design](https://raw.githubusercontent.com/Requisitos-de-Software/2024.1-CarteiradeTrabalhoDigital/main/docs/ImagensDiagrama/ImagensEntrega4/RestricoesDesign_NFRframework2.png) 

</details>

