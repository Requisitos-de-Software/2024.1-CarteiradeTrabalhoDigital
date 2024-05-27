# Cartões de Especfiicação de Restrições de Design

## Padrões Tipográficos e de Siglas

<details>
  <summary size="20"><b> Padrões Tipográficos e de Siglas </b></summary> 
 
</center>

**Tabela 2:** Padrões Tipográficos e de Siglas

| **Elemento**               | **Detalhes**                                                                                                                                          |
|----------------------------|-------------------------------------------------------------------------------------------------------------------------------------------------------|
| **Identificador**          | [RNF05](Elicitacao/ResquisitosCorrigidos.md)                                                                                                          |
| **Nome do Requisito**      | Padrões Tipográficos e de Siglas                                                                                                                      |
| **Tipo de Requisito**      | Restrição de Design                                                                                                                                    |
| **Descrição**              | Todos os textos do sistema devem seguir os padrões tipográficos, de ícones e de siglas, abreviações e erros conforme as normas dispostas em [Tipografia](https://www.gov.br/ds/fundamentos-visuais/tipografia), [Iconografia](https://www.gov.br/ds/fundamentos-visuais/iconografia), [Espaçamento](https://www.gov.br/ds/fundamentos-visuais/espacamento),         [Densidade](https://www.gov.br/ds/padroes/design/densidade)                      |
| **Justificativa/Racionalidade** | É necessário garantir consistência e legibilidade em toda a interface do usuário para promover uma experiência de uso mais intuitiva e mais profissional. Para isso, deve-se Seguir os padrões tipográficos adequados que ajudam a evitar ambiguidades e erros de interpretação e são essenciais para a clareza e precisão na comunicação com os usuário.                   |
| **Critérios de Aceitação** |  <li> Em relação a tipografia, as fontes utilizadas devem ser “Raleway” ou “sans-serif” <li> Nenhuma fonte deve estar fora da escala definida no DS: Minor Third <li> O tamanho da fonte base é de 14px (1em) e peso da fonte normal (400). <li> A seleção de ícones deve estar de acordo com a coleção “Font Awesome“(versão 5.10.2) <li> Em relação ao espagamento, o comportamento das dimensões de um objeto é determinada pela regra: box-sizing: border-box, ou seja, as propriedades de largura (width) e de altura (height) incluem o tamanho do padding e do border, mas não incluem a margin. <li> Quando houver dois ou mais elementos posicionados horizontalmente ou verticalmente em sequência, deve-se evitar somar as margens mínimas de segurança destes elementos. <li>  A escala de densidade é uma gradação de valores que varia de 4px em 4px e pode crescer ou diminuir sem limites, de acordo com a necessidade.  <li> Deve ser utilizado Negrito ou itálico para destacar informações importantes <li> Separação de textos muito longos em parágrafos de, no máximo, 4 linhas. <li> Evitar negação de termos em negrito. <li> Na primeira vez, escrever o nome completo e mencione a sigla entre parênteses. <li> Preferência para os numerais ao invés de escrever por extenso. <li> Evitar palavras em inglês. </ul>         |
| **Origem/Fonte**           | [Análise de documentos](Elicitacao/TecnicasElicitacao/Execucao/AnaliseDocumentos.md)                                                                       |
| **Prioridade**             | Média Prioridade                                                                                                                                              |
| **Interdependências**      | RNF06 (Conformidade com manuais de interface gov.br)                                                                                                   |
| **Notas e Comentários**    | Há um conjunto de normas no site do gov para os aplicativos do governo e todas essas normas devem ser consideradas.                                               |

**Fonte:** [Larissa Stéfane](https://github.com/SkywalkerSupreme)

</center>

</details>

<details>
  <summary size="20"><b> Elementos Básicos de Design do Padrão Digital de Governo </b></summary> 
 
</center>

**Tabela 3:** Elementos Básicos de Design do Padrão Digital de Governo

| **Elemento**               | **Detalhes**                                                                                                                                          |
|----------------------------|-------------------------------------------------------------------------------------------------------------------------------------------------------|
| **Identificador**          | RNF07                                                                                                                                                 |
| **Nome do Requisito**      | Elementos básicos de design conforme padrão digital de governo                                                                                                                             |
| **Tipo de Requisito**      | Restrição de Design                                                                                                                                    |
| **Descrição**              | A interface do sistema deve incluir a iconografia de acordo com o definido em [design ajuda e comunicação](https://www.gov.br/ds/padroes/design/ajuda-comunicacao), o elemento flutuante de acordo com o [dropdown](https://www.gov.br/ds/padroes/design/dropdown), os gráficos de acordo com a [anatomia dos gráficos](https://www.gov.br/ds/padroes/design/grafico) e obedecer os [Princípios de UX Writing](https://www.gov.br/ds/padroes/writing/principios-writing). |
| **Justificativa/Racionalidade** | Assegurar consistência com outros serviços digitais do governo, facilitando a navegação e o uso pelos cidadãos, pois eles já estão acostumados com este padrão. |
| **Critérios de Aceitação** | <li>  Para representar um contexto de ajuda, a representação iconográfica deve ser o símbolo de interrogação, por exemplo: question ou question-circle.   <li>   A Superfície Flutuante deve ser posicionada próxima ao Acionador ou centralizada na tela, no caso de dispositivos móveis. Por padrão, a Superfície Flutuante abre abaixo do Acionador;    <li>    Para elementos flutuantes, como Dropdown, usa-se o padrão de Elevação na Camada 2.     <li>   O dropdown deve ter: Acionador, identificador de estado, superfície flutuante.     <li>      Nos gráficos, a fonte deve estar área de rodapé.     <li>  Os gráficos são compostos pelas seguintes áreas: Área de Cabeçalho, Título, Subtítulo, Área Principal, Dados Gráficos, Área de Rodapé, Descrição e Fonte.   <li>   Consistência. Por exemplo, se está sendo utilizado a palavra“Agendar” na página principal, não há motivo para escrever “Programar” em outras páginas.   <li>   Trabalhar com palavras que façam parte do dia a dia das pessoas de acordo com o perfil dos usuários.  <li>  O conteúdo precisa manter consistência quanto ao estilo, tom, voz e terminologias. Isso porque o usuário deve perceber que a forma que os diversos produtos de Governo se comunicam com ele é constante e uniforme.  </ul>     |
| **Origem/Fonte**           | [Análise de documentos](Elicitacao/TecnicasElicitacao/Execucao/AnaliseDocumentos.md)                                                                                                                                   |
| **Prioridade**             | Média Prioridade                                                                                                                                                  |
| **Interdependências**      | RNF06 (Conformidade com manuais de interface gov.br)                                                                                                   |
| **Notas e Comentários**    | Verificações regulares para alinhamento com atualizações do Padrão Digital de Governo.                                                                 |


**Fonte:** [Larissa Stéfane](https://github.com/SkywalkerSupreme)

</center>

</details>
