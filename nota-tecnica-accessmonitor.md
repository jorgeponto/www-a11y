---
id: 265
title: Nota técnica AccessMonitor
date: 2012-11-09T10:51:13+00:00
author: equipa acesso
layout: page
guid: http://www.acessibilidade.gov.pt/wordpress/?page_id=265
---
<div class="alert alert-success">
  <h3>
    Índice do documento
  </h3>
  
  <ul>
    <li>
      <a href="#n12"><em lang="en">AccessMonitor</em>: o que é?</a>
    </li>
    <li>
      <a href="#n13">Funcionalidades</a>
    </li>
    <li>
      <a href="#n14">O relatório qualitativo</a>
    </li>
    <li>
      <a href="#n15">Os testes</a> <ul>
        <li>
          <a href="#n151">de tipo verdadeiro</a>
        </li>
        <li>
          <a href="#n152">de tipo falso</a>
        </li>
        <li>
          <a href="#n153">de tipo decrescente</a>
        </li>
        <li>
          <a href="#n154">de tipo proporcional</a>
        </li>
      </ul>
    </li>
    
    <li>
      <a href="#n16">O índice <em lang="en">AccessMonitor</em></a>
    </li>
    <li>
      <a title="Bateria de testes do AccessMonitor" href="#n17">Bateria de testes</a>
    </li>
  </ul>
</div>

### <em lang="en">AccessMonitor</em>: o que é? {#n12}

O <em lang="en">AccessMonitor</em> é um validador automático que verifica a aplicação das directrizes de acessibilidade nos conteúdos <abbr title="Hyper Text Markup Language" lang="en">HTML</abbr> de um sítio web. O <em lang="en">AccessMonitor</em> usa como referência a versão 2.0 das **Directrizes de Acessibilidade para o Conteúdo da Web (<abbr title="Web Content Accessibility Guidelines" lang="en">WCAG</abbr> 2.0)** do <em lang="en">World Wide Web Consortium (W3C)</em>.

O <em lang="en">AccessMonitor</em> funciona integralmente na web e não requer quaisquer tipos de instalação, nem depende de um qualquer <em lang="en">browser</em> ou sistema operativo e também não precisa de qualquer <em lang="en">plug-in</em> adicional para funcionar. **Pode ser utilizado a partir de um qualquer dispositivo que corra um navegador web &#8211; o <em lang="en">AccessMonitor</em> é integralmente universal**.

Ao contrário dos validadores para as <abbr title="Web Content Accessibility Guidelines" lang="en">WCAG</abbr> 1.0, a existência de validadores para as <abbr title="Web Content Accessibility Guidelines" lang="en">WCAG</abbr> 2.0 é ainda escassa. Dois dos validadores de referência são o [<abbr title="Test Accesibilidad Web" lang="es">TAW</abbr> (<abbr title="Web Content Accessibility Guidelines" lang="en">WCAG</abbr> 2.0)](http://www.tawdis.net), ainda em versão beta, e o [<em lang="en">TotalValidator v2</em>](http://www.totalvalidator.com/). Da base de dados de ferramentas de validação do <abbr title="World Wide Web Consortium" lang="en">W3C</abbr>, para a versão 2.0 das <abbr title="Web Content Accessibility Guidelines" lang="en">WCAG</abbr>, apenas aparece o [<em lang="en">PEAT &#8211; Photosensitive Epilepsy Analysis Tool (version 0.2 (beta))</em>](http://trace.wisc.edu/peat/), do <em lang="en">Trace R & D Center</em> da Universidade de <em lang="en">Wisconsin-Madison</em>.

O <em lang="en">AccessMonitor</em> resulta da experiência de desenvolvimento e utilização do [validador eXaminator](/webax/examinator.php), ferramenta automática de validação que desde 2005 é usada pela equipa da [Unidade ACESSO](http://www.acessibilidade.gov.pt/), atualmente da _AMA_ na **Administração Pública Portuguesa**. O <em lang="en">AccessMonitor</em> congrega todos os ensinamentos resultantes do eXaminator, aos quais se associam novas formas de recolha de informação e apresentação dos resultados.

### Funcionalidades do <em lang="en">AccessMonitor</em> {#n13}

Assim, no <em lang="en">AccessMonitor</em>, é possível encontrar as seguintes funcionalidades:

  * **submissão de página web ao estilo dos validadores <abbr title="World Wide Web Consortium" lang="en">W3C</abbr>:** à validação por introdução directa de <abbr title="Uniform Resource Identifier" lang="en">URI</abbr>, já existente no eXaminator, o <em lang="en">AccessMonitor</em> disponibiliza ainda a validação por introdução directa do código fonte ou por <em lang="en">upload</em> de ficheiro <abbr title="Extensivel Hyper Text Markup Language or Hyper Text Markup Language " lang="en">(x)HTML</abbr> existente na máquina do utilizador;
  * **validação tripla:** o <em lang="en">AccessMonitor</em> valida, num só passo, a aplicação das <abbr title="Web Content Accessibility Guidelines" lang="en">WCAG</abbr> 2.0, a validação das folhas de estilo (<abbr title="Cascading Style Sheet" lang="en">CSS</abbr> 3.0 e <abbr title="Cascading Style Sheet" lang="en">CSS</abbr> 2.1) externas, das regras de estilo inseridas em linha ou no cabeçalho da página <abbr title="Extensivel Hyper Text Markup Language or Hyper Text Markup Language " lang="en">(x)HTML</abbr> e, ainda, a validação do código <abbr title="Extensivel Hyper Text Markup Language or Hyper Text Markup Language " lang="en">(x)HTML</abbr>;
  * **um relatório de acessibilidade imediato:** um relatório qualitativo, em língua portuguesa, que evita o uso de jargão técnico, em que as práticas de concepção encontradas na página se encontram organizadas pelos 3 níveis de prioridade com que os critérios de sucesso se apresentam nas <abbr title="Web Content Accessibility Guidelines" lang="en">WCAG</abbr> 2.0.
  * **uma escala quantitativa (índice AccessMonitor):** que pontua as práticas de concepção encontradas na página e que, pela rápida e fácil leitura, notabilizou o seu predecessor eXaminator (&#8220;de 1 a 10, quanto valem as práticas que estou a usar na página?&#8221;);
  * **uma síntese de resultados de leitura imediata:** dos testes efectuados, quantos apresentam resultados positivos, quantos assinalam erros e quantos apontam a necessidade de uma validação manual. A síntese apresenta os resultados de forma a pôr em clara evidência os erros encontrados e a orientar os utilizadores para a sua correção;
  * **forte carácter pedagógico:** informação detalhada dos testes efectuados, dividos pelos 3 níveis de prioridade dos critérios de sucesso (prioridade &#8216;A&#8217;, prioridade &#8216;AA&#8217; e prioridade &#8216;AAA&#8217;) de acordo com a nova definição de prioridades constante das <abbr title="Web Content Accessibility Guidelines" lang="en">WCAG</abbr> 2.0;
  * **ajuda contextualizada:** apoiada nos 3 documentos essenciais, produzidos pelo <abbr title="World Wide Web Consortium" lang="en">W3C</abbr> para a correcta implementação das directrizes, a ajuda contextualizada conduz o desenvolvedor dos conteúdos à correção dos problemas encontrados e fundamenta os testes efetuados pelo <em lang="en">AccessMonitor</em>: 
      * [Diretrizes de Acessibilidade para o Conteúdo da Web (<abbr title="Web Content Accessibility Guidelines" lang="en">WCAG</abbr>) 2.0 &#8211; Recomendação <abbr title="World Wide Web Consortium" lang="en">W3C</abbr> de 11 Dezembro de 2008](/w3/TR/WCAG20/);
      * [Noções sobre as <abbr title="Web Content Accessibility Guidelines" lang="en">WCAG</abbr> 2.0 &#8211; Um manual para compreender e implementar as Diretrizes de Acessibilidade para o Conteúdo da Web 2.0](/w3/TR/UNDERSTANDING-WCAG20/);
      * [Técnicas para as <abbr title="Web Content Accessibility Guidelines" lang="en">WCAG</abbr> 2.0 &#8211; Técnicas e Falhas para as Diretrizes de Acessibilidade para o Conteúdo da Web 2.0](/w3/TR/WCAG20-TECHS/).
  * **Verificações manuais mais fáceis:** o relatório disponibiliza 3 tipos de visualizações para análise manual das ocorrências: 
      *<img alt="ícone ver elementos" src="/accessmonitor/notatecnica/seeElem.png" width="20" height="20" /> uma visão por elemento;
      *<img alt="ícone ver DOM" src="/accessmonitor/notatecnica/seeDom.png" width="20" height="20" /> uma visão no código (organizado através do <em lang="en">Document Object Model</em>) e;
      *<img alt="ícone ver página" src="/accessmonitor/notatecnica/seePage.png" width="20" height="20" /> uma visão das ocorrências sobrepostas na página original.

Tal como sucede atualmente com o eXaminator, também com o <em lang="en">AccessMonitor</em> é possível criar diretórios de monitorização de múltiplas páginas de um sítio Web, diretórios de vários sítios de um setor de atividade, bem como proceder à afixação do selo dinâmico de certificação. <span>Se pretende usar o selo dinâmico de certificação, entre em contato com a <a href="mailto:jorge.fernandes@ama.pt; claudia.cardoso@ama.pt"> equipa da ACESSO</a> da <abbr title="Agência para a Modernização Administrativa">AMA</abbr>.</span>

### O relatório qualitativo <em lang="en">AccessMonitor</em> {#n14}

O <em lang="en">AccessMonitor</em> produz automaticamente um relatório qualitativo por cada página que lhe é submetida.

[<img class="aligncenter" style="border: 1px solid black;" alt="Recorte do relatório qualitativo AccessMonitor" src="/accessmonitor/notatecnica/report.png" width="306" height="214" />](/accessmonitor/notatecnica/report100.png)

<p style="text-align: center;">
  Figura 1: Recorte do relatório qualitativo <em lang="en">AccessMonitor</em>.
</p>

O relatório está organizado em duas partes:

  * uma breve descrição da amostra recolhida e;
  * uma apresentação exaustiva dos resultados compilados.

[<img class="aligncenter" style="border: 1px solid black;" alt="Detalhe dos dados da amostra constantes do relatório qualitativo" src="/accessmonitor/notatecnica/amostra.png" width="293" height="98" />](/accessmonitor/notatecnica/amostra100.png)

<p style="text-align: center;">
  Figura 2: detalhe da amostra recolhida fornecida no relatório qualitativo do <em lang="en">AccessMonitor</em>.
</p>

Na primeira parte é possível observar o URI da página, um botão<img alt="botão ver página" src="/accessmonitor/notatecnica/viewPage.png" width="20" height="20" /> &#8220;ver página&#8221; que liga à página que foi alvo da análise e um botão<img alt="botão ver código" src="/acceessmonitor/notatecnica/viewCode.png" width="20" height="20" /> &#8220;ver código&#8221; que permite ver o seu código fonte. É ainda possível consultar o **título da página** (elemento `<title>` da página <abbr title="Hyper Text Markup Language" lang="en">HTML</abbr>), o **tamanho** em KB, o **número de elementos encontrados** e a **data e hora** a que se procedeu à análise. <span>Relativamente ao número de elementos, deixamos aqui uma nota especial, resultante da nossa experiência com o validador eXaminator:</span>

> &#8220;podemos inferir que quanto maior for o número de elementos observados na página, maior é o grau de confiança com que podemos aceitar as indicações fornecidas no relatório. Para um número de elementos inferior a 100 é necessário inspecionar com maior cuidado as afirmações proferidas, aconselhando-se a efectuar sempre uma verificação manual.&#8221;
> 
> <p style="text-align: right;">
>   <cite>&#8212; Jorge Fernandes / Unidade ACESSO da <em><abbr title="Fundação para a Ciência e a Tecnologia">FCT</abbr></em>.</cite>
> </p>

Na segunda parte, os resultados encontram-se igualmente divididos em duas secções: uma primeira apresentando um **sumário dos resultados** e uma segunda apresentando um **detalhe exaustivo dos testes** efectuados.  
[<img class="aligncenter" style="border: 1px solid black;" alt="Pormenor do dados de síntese do relatório AccessMonitor" src="/accessmonitor/notatecnica/resultado.png" width="496" height="135" />](/accessmonitor/notatecnica/resultado100.png)

<p style="text-align: center;">
  Figura 3: pormenor dos dados que compõem a síntese do relatório <em lang="en">AccessMonitor</em>.
</p>

Do sumário faz parte:

  * **o &#8220;índice <em lang="en">AccessMonitor</em>&#8220;**, o qual é uma unidade de valoração utilizada em todos os testes do validador e cujo resultado final sintetiza e quantifica as práticas com vista à acessibilidade expressa nas <abbr title="Web Content Accessibility Guidelines" lang="en">WCAG</abbr> 2.0. O índice <em lang="en">AccessMonitor</em> é uma herança do [índice <em lang="en">web@x</em> do eXaminator](/webax/nota_tecnica_webax.html), o qual inaugurou o uso deste tipo de indicadores quantitativos em validadores de acessibilidade de conteúdos Web. Se em 2005, o eXaminator foi pioneiro no uso de indicadores quantitativos, hoje em dia este tipo de indicador tem sido alvo de discussão académica e é mesmo prática noutros validadores como o [<em lang="en">TAW</em>](http://www.tawdis.net). A escala de 1 a 10, representando o 10 uma boa prática observada automaticamente, acaba por ser uma escala de apreensão mais imediata e fácil do que a gradação usada pelo <abbr title="World Wide Web Consortium" lang="en">W3C</abbr> com os seus 3 níveis de prioridade, pouco sensível a pequenas correções operadas nos conteúdos.
  * **um quadro que sintetiza os resultados dos testes efectuados**, em que se expressa o número de testes que estão **OK**, dos que contêm **erros**, dos que requerem uma validação manual adicional, assinalados como **avisos**. Os 3 tipos de resultados encontram-se estratificados pelos 3 níveis de prioridade dos critérios de sucesso das <abbr title="Web Content Accessibility Guidelines" lang="en">WCAG</abbr> 2.0, ou seja, prioridade &#8216;A&#8217;, prioridade &#8216;AA&#8217; e prioridade &#8216;AAA&#8217;.

[<img class="aligncenter" style="border: 1px solid black;" alt="detalhe fornecido por teste no relatório qualitativo" src="/accessmonitor/notatecnica/detalhe.png" width="465" height="187" />](/accessmonitor/notatecnica/detalhe100.png)

<p style="text-align: center;">
  Figura 4: Informação detalhada por teste fornecida no relatório qualitativo <em lang="en">AccessMonitor</em>.
</p>

Os resultados detalhados apresentam todos os testes efectuados, organizados pelos 3 níveis de prioridade das <abbr title="Web Content Accessibility Guidelines" lang="en">WCAG</abbr> 2.0. Para cada teste é apresentada a seguinte informação:

Um ícone assinalando se o teste deu<img alt="ícone ok" src="/accessmonitor/notatecnica/pass.png" width="32" height="32" /> (**OK**) ou<img alt="ícone erro" src="/accessmonitor/notatecnica/fail.png" width="32" height="32" /> (**Erro**), um **título do teste**, uma frase que sintetiza a ocorrência encontrada, uma ligação que permite observar a ocorrência em detalhe (com uma visão por elemento<img alt="ícone ver elementos" src="/accessmonitor/notatecnica/seeElem.png" width="20" height="20" /> , uma visão através do <abbr title="Document Object Model" lang="en">DOM</abbr><img alt="ícone ver DOM" src="/accessmonitor/notatecnica/seeDom.png" width="20" height="20" /> e uma visão na página original<img alt="ícone ver página" src="/accessmonitor/notatecnica/seePage.png" width="20" height="20" /> ). Surge depois, um pequeno racional que explicita o porquê do teste e qual a orientação geral preconizada nas <abbr title="Web Content Accessibility Guidelines" lang="en" >WCAG</abbr> 2.0.

<span>Dos 86 testes do <em lang="en">AccessMonitor</em>, 78 testes entram no cálculo do índice <em lang="en">AccessMonitor</em>. Os restantes 8 incorporam o relatório qualitativo mas funcionam como <strong>avisos</strong> para validar manualmente. Esses testes surgem identificados no relatório qualitativo pelo símbolo <img alt="Aviso" src="/accessmonitor/notatecnica/warning.png" width="22" height="24" /></span>.

<img class="aligncenter" alt="Pormenor do relatório qualitativo AccessMonitor: Documentos de Referência WCAG 2.0" src="/accessmonitor/notatecnica/referencia.png" width="460" height="125" /> 

<p style="text-align: center;">
  Figura 5: Pormenor do relatório qualitativo &#8211; documentação <abbr title="Web Content Accessibility Guidelines" lang="en">WCAG</abbr> 2.0 de referência.
</p>

Por último, é ainda fornecido um conjunto de documentação <abbr title="Web Content Accessibility Guidelines" lang="en">WCAG</abbr> 2.0 de consulta contextualizada, do qual fazem parte a técnica ou falha <abbr title="Web Content Accessibility Guidelines" lang="en">WCAG</abbr> 2.0 usada como referência principal pelo teste, a sua descrição, bem como os critérios, ou critério, de sucesso aplicáveis, assim como outras técnicas ou falhas relacionadas. <span>Todas as referências mencionadas no relatório qualitativo do <em lang="en">AccessMonitor</em> estão sustentadas, com ligações diretas aos documentos originais, em informação produzida pelo <abbr title="World Wide Web Consortium" lang="en">W3C</abbr> para as <abbr title="Web Content Accessibility Guidelines" lang="en">WCAG</abbr> 2.0</span> e cuja tradução para português esteve a cargo da Unidade ACESSO da _FCT._

### Os testes <em lang="en">AccessMonitor</em> resultam das WCAG 2.0 do W3C. {#n4}

Dos 61 critérios de sucesso das <abbr title="Web Content Accessibility Guidelines" lang="en">WCAG</abbr> 2.0, o <em lang="en">AccessMonitor</em> tem, pelo menos, um teste para 30 deles (ver tabela 1). No caso dos critérios de sucesso de prioridade &#8216;A&#8217; chega mesmo a abranger 64% dos 25 critérios existentes para a conformidade &#8216;A&#8217;.

<div class="tabela" style="width: 80%; margin: auto;">
  <table style="width:100%">
    <caption>Tabela 1: Nº de Critérios de Sucesso <abbr title="Web Content Accessibility Guidelines" lang="en">WCAG</abbr> 2.0 abrangidos pelos testes do <em lang="en">AccessMonitor</em> por níveis de prioridade</caption> <tr>
      <th style="width: 40%;" scope="col">
      </th>
      
      <th style="width: 20%;" scope="col">
        (A) = Total CS abrangidos pelos Testes AccessMonitor
      </th>
      
      <th style="width: 20%;" scope="col">
        (B) = Total CS das WCAG2.0
      </th>
      
      <th style="width: 20%;" scope="col">
        (A) / (B)
      </th>
    </tr>
    
    <tr>
      <th scope="row">
        Prioridade &#8216;A&#8217;
      </th>
      
      <td>
        16
      </td>
      
      <td>
        25
      </td>
      
      <td>
        64%
      </td>
    </tr>
    
    <tr>
      <th scope="row">
        Prioridade &#8216;AA&#8217;
      </th>
      
      <td>
        5
      </td>
      
      <td>
        13
      </td>
      
      <td>
        38%
      </td>
    </tr>
    
    <tr>
      <th scope="row">
        Prioridade &#8216;AAA&#8217;
      </th>
      
      <td>
        9
      </td>
      
      <td>
        23
      </td>
      
      <td>
        39%
      </td>
    </tr>
    
    <tr>
      <th scope="row">
        Total
      </th>
      
      <td>
        30
      </td>
      
      <td>
        61
      </td>
      
      <td>
        50%
      </td>
    </tr>
  </table>
</div>

O <em lang="en">AccessMonitor</em> infere o grau de conformidade para com as <abbr title="Web Content Accessibility Guidelines" lang="en">WCAG</abbr> 2.0, sendo a sua análise transversal aos 3 níveis de prioridade. Os atuais 86 testes do <em lang="en">AccessMonitor</em> não têm uma correspondência biunívoca para com os 61 critérios de sucesso das WCAG 2.0 (i.e. não existe uma relação de um para um). Existem critérios de sucesso para os quais se observa mais do que um teste e há testes que se aplicam a múltiplos critérios de sucesso (ver tabela 2). É importante ter em conta que existem critérios de sucesso para os quais é impossível uma análise automática.

<div class="tabela" style="width: 80%; margin: auto;">
  <table style="width:100%">
    <caption>Tabela 2: Nº de testes <em lang="en">AccessMonitor</em> por critérios de sucesso e níveis de prioridade</caption> <tr>
      <th style="width: 40%;" scope="col">
        Critérios de Sucesso WCAG2.0
      </th>
      
      <th style="width: 10%;" scope="col">
        Testes &#8216;A&#8217;
      </th>
      
      <th style="width: 10%;" scope="col">
        Testes &#8216;AA&#8217;
      </th>
      
      <th style="width: 10%;" scope="col">
        Testes &#8216;AAA&#8217;
      </th>
      
      <th style="width: 10%;" scope="col">
        Total
      </th>
    </tr>
    
    <tr>
      <th scope="row">
        1.1.1
      </th>
      
      <td>
        17
      </td>
      
      <td>
      </td>
      
      <td>
      </td>
      
      <td>
        17
      </td>
    </tr>
    
    <tr>
      <th scope="row">
        1.2.1
      </th>
      
      <td>
        1
      </td>
      
      <td>
      </td>
      
      <td>
      </td>
      
      <td>
        1
      </td>
    </tr>
    
    <tr>
      <th scope="row">
        1.2.8
      </th>
      
      <td>
      </td>
      
      <td>
      </td>
      
      <td>
        1
      </td>
      
      <td>
        1
      </td>
    </tr>
    
    <tr>
      <th scope="row">
        1.3.1
      </th>
      
      <td>
        18
      </td>
      
      <td>
      </td>
      
      <td>
      </td>
      
      <td>
        18
      </td>
    </tr>
    
    <tr>
      <th scope="row">
        1.3.2
      </th>
      
      <td>
        2
      </td>
      
      <td>
      </td>
      
      <td>
      </td>
      
      <td>
        2
      </td>
    </tr>
    
    <tr>
      <th scope="row">
        1.4.3
      </th>
      
      <td>
      </td>
      
      <td>
        2
      </td>
      
      <td>
      </td>
      
      <td>
        2
      </td>
    </tr>
    
    <tr>
      <th scope="row">
        1.4.4
      </th>
      
      <td>
      </td>
      
      <td>
        5
      </td>
      
      <td>
      </td>
      
      <td>
        5
      </td>
    </tr>
    
    <tr>
      <th scope="row">
        1.4.5
      </th>
      
      <td>
      </td>
      
      <td>
        3
      </td>
      
      <td>
      </td>
      
      <td>
        3
      </td>
    </tr>
    
    <tr>
      <th scope="row">
        1.4.6
      </th>
      
      <td>
      </td>
      
      <td>
      </td>
      
      <td>
        1
      </td>
      
      <td>
        1
      </td>
    </tr>
    
    <tr>
      <th scope="row">
        1.4.8
      </th>
      
      <td>
      </td>
      
      <td>
      </td>
      
      <td>
        5
      </td>
      
      <td>
        5
      </td>
    </tr>
    
    <tr>
      <th scope="row">
        1.4.9
      </th>
      
      <td>
      </td>
      
      <td>
      </td>
      
      <td>
        3
      </td>
      
      <td>
        3
      </td>
    </tr>
    
    <tr>
      <th scope="row">
        2.1.1
      </th>
      
      <td>
        3
      </td>
      
      <td>
      </td>
      
      <td>
      </td>
      
      <td>
        3
      </td>
    </tr>
    
    <tr>
      <th scope="row">
        2.1.3
      </th>
      
      <td>
      </td>
      
      <td>
      </td>
      
      <td>
        2
      </td>
      
      <td>
        2
      </td>
    </tr>
    
    <tr>
      <th scope="row">
        2.2.1
      </th>
      
      <td>
        2
      </td>
      
      <td>
      </td>
      
      <td>
      </td>
      
      <td>
        2
      </td>
    </tr>
    
    <tr>
      <th scope="row">
        2.2.2
      </th>
      
      <td>
        2
      </td>
      
      <td>
      </td>
      
      <td>
      </td>
      
      <td>
        2
      </td>
    </tr>
    
    <tr>
      <th scope="row">
        2.2.4
      </th>
      
      <td>
      </td>
      
      <td>
      </td>
      
      <td>
        2
      </td>
      
      <td>
        2
      </td>
    </tr>
    
    <tr>
      <th scope="row">
        2.4.1
      </th>
      
      <td>
        7
      </td>
      
      <td>
      </td>
      
      <td>
      </td>
      
      <td>
        7
      </td>
    </tr>
    
    <tr>
      <th scope="row">
        2.4.2
      </th>
      
      <td>
        7
      </td>
      
      <td>
      </td>
      
      <td>
      </td>
      
      <td>
        7
      </td>
    </tr>
    
    <tr>
      <th scope="row">
        2.4.4
      </th>
      
      <td>
        4
      </td>
      
      <td>
      </td>
      
      <td>
      </td>
      
      <td>
        4
      </td>
    </tr>
    
    <tr>
      <th scope="row">
        2.4.5
      </th>
      
      <td>
      </td>
      
      <td>
        1
      </td>
      
      <td>
      </td>
      
      <td>
        1
      </td>
    </tr>
    
    <tr>
      <th scope="row">
        2.4.6
      </th>
      
      <td>
      </td>
      
      <td>
        1
      </td>
      
      <td>
      </td>
      
      <td>
        1
      </td>
    </tr>
    
    <tr>
      <th scope="row">
        2.4.9
      </th>
      
      <td>
      </td>
      
      <td>
      </td>
      
      <td>
        4
      </td>
      
      <td>
        4
      </td>
    </tr>
    
    <tr>
      <th scope="row">
        2.4.10
      </th>
      
      <td>
      </td>
      
      <td>
      </td>
      
      <td>
        1
      </td>
      
      <td>
        1
      </td>
    </tr>
    
    <tr>
      <th scope="row">
        3.1.1
      </th>
      
      <td>
        4
      </td>
      
      <td>
      </td>
      
      <td>
      </td>
      
      <td>
        4
      </td>
    </tr>
    
    <tr>
      <th scope="row">
        3.2.1
      </th>
      
      <td>
        1
      </td>
      
      <td>
      </td>
      
      <td>
      </td>
      
      <td>
        1
      </td>
    </tr>
    
    <tr>
      <th scope="row">
        3.2.2
      </th>
      
      <td>
        2
      </td>
      
      <td>
      </td>
      
      <td>
      </td>
      
      <td>
        2
      </td>
    </tr>
    
    <tr>
      <th scope="row">
        3.2.5
      </th>
      
      <td>
      </td>
      
      <td>
      </td>
      
      <td>
        1
      </td>
      
      <td>
        1
      </td>
    </tr>
    
    <tr>
      <th scope="row">
        3.3.2
      </th>
      
      <td>
        5
      </td>
      
      <td>
      </td>
      
      <td>
      </td>
      
      <td>
        5
      </td>
    </tr>
    
    <tr>
      <th scope="row">
        4.1.1
      </th>
      
      <td>
        8
      </td>
      
      <td>
      </td>
      
      <td>
      </td>
      
      <td>
        8
      </td>
    </tr>
    
    <tr>
      <th scope="row">
        4.1.2
      </th>
      
      <td>
        10
      </td>
      
      <td>
      </td>
      
      <td>
      </td>
      
      <td>
        10
      </td>
    </tr>
    
    <tr>
      <th scope="row">
        Total (*)
      </th>
      
      <td>
        93
      </td>
      
      <td>
        12
      </td>
      
      <td>
        20
      </td>
      
      <td>
        125
      </td>
    </tr>
  </table>
  
  <p>
    (*) O total de testes não é igual a 86 uma vez que existem testes que se aplicam a vários critérios de sucesso.
  </p>
</div>

Se analisarmos a distribuição dos 30 testes <em lang="en">AccessMonitor</em> (ver tabela 3) pelos 3 níveis de prioridade das <abbr title="Web Content Accessibility Guidelines" lang="en">WCAG</abbr> verifica-se que 53% dos testes estão relacionados com verificações de prioridade A, 17% de prioridade AA e 30% de prioridade AAA. O <em lang="en">AccessMonitor</em> segue os pesos relativos da distribuição existente nas <abbr title="Web Content Accessibility Guidelines" lang="en">WCAG</abbr> 2.0 embora contenha um maior número de testes, em termos relativos, para os critérios de prioridade &#8216;A&#8217;.

<div class="tabela" style="width: 80%; margin: auto;">
  <table style="width:100%">
    <caption>Tabela 3: Distribuição dos critérios de sucesso <em lang="en">AccessMonitor</em> pelos 3 níveis de prioridade das <abbr title="Web Content Accessibility Guidelines" lang="en">WCAG</abbr> 2.0</caption> <tr>
      <th scope="col">
        Níveis de prioridade
      </th>
      
      <th colspan="2" scope="col">
        <abbr title="Critério de Sucesso">CS</abbr> AccessMonitor
      </th>
      
      <th colspan="2" scope="col">
        <abbr title="Critério de Sucesso">CS</abbr> WCAG2.0
      </th>
    </tr>
    
    <tr>
      <th scope="row">
        Prioridade A
      </th>
      
      <td>
        16
      </td>
      
      <td>
        53%
      </td>
      
      <td>
        25
      </td>
      
      <td>
        41%
      </td>
    </tr>
    
    <tr>
      <th scope="row">
        Prioridade AA
      </th>
      
      <td>
        5
      </td>
      
      <td>
        17%
      </td>
      
      <td>
        13
      </td>
      
      <td>
        21%
      </td>
    </tr>
    
    <tr>
      <th scope="row">
        Prioridade AAA
      </th>
      
      <td>
        9
      </td>
      
      <td>
        30%
      </td>
      
      <td>
        23
      </td>
      
      <td>
        38%
      </td>
    </tr>
    
    <tr>
      <th scope="row">
        Total
      </th>
      
      <td>
        30
      </td>
      
      <td>
      </td>
      
      <td>
        61
      </td>
      
      <td>
      </td>
    </tr>
  </table>
</div>

### O índice <em lang="en">AccessMonitor</em> e a fórmula de cálculo {#n16}

O <span lang="en">AcceMonitor</span> dispõe de um índice numérico, numa escala de 1.0 a 10.0, que tem por objectivo sintetizar num só valor o grau de satisfação dos testes automáticos executados pelo validador. O valor 10.0 é indicativo de uma muito elevada satisfação dos testes executados pelo <em lang="en">AccessMonitor</em> aos conteúdos submetidos. O índice sintetiza os resultados verificados numa página ou numa amostra de páginas de um sítio web.

O índice <em lang="en">AccessMonitor</em> de uma página ou de um domínio na Internet é uma média ponderada do grau de satisfação dos diversos testes efectuados. No entanto, a ponderação, e mesmo a fórmula de cálculo, depende do tipo de teste.

A ponderação (P) resulta do produto do grau de confiança (U) e do Peso relativo do teste (W):

<div class="formula">
  <p>
    <span>P=U*W</span>
  </p>
</div>

<p class="paragrafo_salientado">
  O grau de confiança (U) no teste, resulta da experiência de utilização da equipa de desenvolvimento do <em lang="en">AccessMonitor</em>, nomeadamente pela utilização durante os últimos 5 anos do eXaminator. <span>Assim, quando U=1 significa que o teste é 100% confiável. Quando ele é de 0.9 significa que o teste não é totalmente seguro</span>.
</p>

O peso relativo do teste (W) pondera a importância do teste na estrutura organizativa das <abbr title="Web Content Accessibility Guidelines" lang="en">WCAG</abbr>2.0 e nos 3 níveis de prioridade com que esta hierarquiza os critérios de sucesso, ou seja: critérios de sucesso de prioridade A, critérios de sucesso de prioridade AA e critérios de sucesso de prioridade AAA (veja tabela seguinte).

<div class="tabela" style="width: 60%; margin: auto;">
  <table style="width:100%">
    <caption>Tabela 4: Ponderação (W) dos testes consoante os CS das <abbr title="Web Content Accessibility Guidelines" lang="en">WCAG</abbr>2.0 a que pertencem</caption> <tr>
      <th scope="col">
        Critérios de Sucesso
      </th>
      
      <th scope="col">
        Ponderação
      </th>
    </tr>
    
    <tr>
      <td>
        de prioridade A
      </td>
      
      <td>
        0.9
      </td>
    </tr>
    
    <tr>
      <td>
        de prioridade AA
      </td>
      
      <td>
        0.6
      </td>
    </tr>
    
    <tr>
      <td>
        de prioridade AAA
      </td>
      
      <td>
        0.2
      </td>
    </tr>
  </table>
</div>

A ponderação (W) pode ainda ser modificada caso o teste em presença esteja relacionado com mais do que uma técnica do tipo suficiente ou aconselhada, na definição das <abbr title="Web Content Accessibility Guidelines" lang="en">WCAG</abbr> 2.0. Assim, no primeiro caso soma-se, à ponderação que se encontra na tabela anterior, 0.1, e no segundo caso subtrai-se 0.1, dando assim um maior peso às técnicas que o <abbr title="World Wide Web Consortium" lang="en">W3C</abbr> considera suficientes em detrimento das técnicas &#8220;meramente&#8221; aconselhadas.

No <em lang="en">AccessMonitor</em> existem 4 tipos de testes. Esta diversidade de tipos de testes deriva da própria natureza das técnicas e falhas que compõem os critérios de sucesso das <abbr title="Web Content Accessibility Guidelines" lang="en">WCAG</abbr> 2.0.

#### I) Testes de tipo verdadeiro {#n161}

Os testes de tipo verdadeiro consistem na validação de uma determinada condição. Se a condição a verificar é verdadeira [if (C == True)] o valor do teste (R) resulta da fórmula:

<div class="formula">
  <p>
    <span>R=S*P</span>
  </p>
</div>

S é a pontuação &#8220;subjectiva&#8221; atribuída ao teste. A pontuação &#8220;subjectiva&#8221; resulta da experiência da equipa de desenvolvimento do <em lang="en">AccessMonitor</em>. A pontuação &#8220;subjectiva&#8221; é uma variável determinante, atribuída de acordo com a seguinte escala:

  * **Muito má prática:** 1
  * **Má prática:** 2 ou 3
  * **Prática regular:** 4 ou 5
  * **Boa prática:** 6 ou 7
  * **Muito boa prática:** 8 ou 9
  * **Excelente prática:** 10

<p class="paragrafo_salientado">
  <strong>nota</strong>: <span>a conversão de uma apreciação qualitativa em quantitativa (numa escala de 1 a 10) serve de base ao cálculo do índice <em lang="en">AccessMonitor</em></span>. O valor (S) inicialmente atribuído é posteriormente ponderado tendo em conta vários factores: prioridade a que pertence o teste, confiança no teste, existência de uma determinada condição, dimensão do problema encontrado.
</p>

#### II) Testes de tipo falso {#n162}

Tal como nos testes de tipo verdadeiro também os de tipo falso procuram validar a existência de uma condição. Se a condição a verificar é falsa [if (C == False)] o valor do teste (R) resulta da fórmula:

<div class="formula">
  <p>
    <span>R=S*P</span>
  </p>
</div>

Ou seja, a fórmula de cálculo deste tipo de testes é exactamente igual à anterior. A única diferença está na verificação da condição (C). Neste caso, o teste é contabilizado quando a condição é falsa, ao passo que no teste anterior, ele é contabilizado quando a condição é verdadeira.

#### III) Testes de tipo decrescente {#n163}

Nos testes do tipo decrescente, entra-se em linha de conta com a ocorrência da condição mas quantifica-se a sua extensão. Quanto maior for a extensão do problema encontrado menor é o valor obtido no teste.

<div class="formula">
  <p>
    <span>R=(S-(C-T)/Z)*P</span>
  </p>
</div>

Retirando a variável P (ponderação) cuja fórmula de cálculo é comum aos 4 tipos de testes e cuja decomposição se encontra explicitada acima, ficamos com a seguinte parcela da fórmula:

<div class="formula">
  <p>
    <span>S-(C-T)/Z</span>
  </p>
</div>

A origem da definição de teste do tipo decrescente reside nesta parcela da fórmula. Ao contrário dos testes I) e II) em que S (pontuação subjectiva) classifica um teste binário, do tipo verdadeiro ou falso, neste caso há necessidade de atribuir também uma pontuação que é variável de acordo com o número de erros encontrados. Neste caso, quando falamos em ocorrência da condição (C) estamos a falar de &#8220;número de erros&#8221;. Assim, se C > 0 (i.e. existem erros), isto implica, logo à partida, uma determinada pontuação (S), a qual vai decrescendo à medida que o número de erros aumenta. A variável &#8216;T&#8217; é o nível de tolerância máximo ao erro, ou seja, valor a partir do qual é subtraída a primeira unidade à pontuação de partida &#8216;S&#8217;.

Por exemplo, no caso do teste que verifica quantos erros <abbr title="Hyper Text Markup Language" lang="en">HTML</abbr> existem numa página, se tivermos 1 erro, a fórmula tem o seguinte aspecto:

5 &#8211; (1 &#8211; 10)/10 = 5 + 9/10 = 5 + 0 = 5 (i.e. a pontuação seria a inicial &#8216;S&#8217; de 5 pontos dado que a tolerância ao erro de 10 não foi ultrapassada.

Se, em vez de 1 erro, fossem localizados 33 erros, então teriamos:

5 &#8211; (33 -10)/10 = 5 &#8211; 2.2 = 2.8 (i.e., à pontuação inicial &#8216;S&#8217; de 5 pontos iriamos retirar 2.2 pontos.

#### IV) Testes de tipo proporcional {#n164}

<div class="formula">
  <p>
    <span>R=S*(1-C/E)*P</span>
  </p>
</div>

Retirando a variável P (ponderação) cuja fórmula de cálculo é comum aos 4 tipos de testes e cuja decomposição se encontra explicitada acima, ficamos com a seguinte fórmula:

<div class="formula">
  <p>
    <span>S*(1-C/E)</span>
  </p>
</div>

C = nº de elementos de um dado tipo semântico com erro

E = total de elementos de um dado tipo semântico

1-C/E = esta fracção é a que adjectiva o nome do teste, uma vez que ela representa a proporção a subtrair à pontuação subjectiva inicial (S).

Por exemplo, se na recolha forem encontradas 20 imagens das quais 10 não têm legenda, teremos 1-C/E = 1-10/20 = 1-1/2 = 1/2. Se S, pontuação inicial atribuída para a existência de erros deste tipo, for igual a 3, então teremos S\*(1-C/E) = 3\*(1-1/2) = 3/2 = 1.5, ou seja metade da pontuação inicial, o que tem lógica dado o erro estar presente em 50% das imagens encontradas.

<div class="tabela" style="width: 50%; margin: auto;">
  <table style="width:100%">
    <caption>Tabela 5: Tipo de testes AccessMonitor</caption> <tr>
      <th scope="row">
        Tipo de Teste
      </th>
      
      <th>
        Nº de testes
      </th>
    </tr>
    
    <tr>
      <td>
        Verdadeiro
      </td>
      
      <td>
        25
      </td>
    </tr>
    
    <tr>
      <td>
        Falso
      </td>
      
      <td>
        14
      </td>
    </tr>
    
    <tr>
      <td>
        Decrescente
      </td>
      
      <td>
        24
      </td>
    </tr>
    
    <tr>
      <td>
        Proporcional
      </td>
      
      <td>
        23
      </td>
    </tr>
    
    <tr>
      <td>
        Total
      </td>
      
      <td>
        86
      </td>
    </tr>
  </table>
</div>

Por último, a fórmula de cálculo do índice <em lang="en">AccessMonitor</em> resulta da divisão do somatório dos diversos resultados dos 4 tipos de testes pelo somatório das respectivas ponderações (ver fórmula síntese abaixo).

Em síntese, a fórmula de cálculo global do índice <em lang="en">AccessMonitor</em> tem a seguinte notação:  
<img class="aligncenter" alt="Fórmula global do índice AccessMonitor" src="/accessmonitor/notatecnica/formula.png" />  
Os índices das variáveis identificadas por t1, t2, t3 e t4 representam respectivamente os 4 tipos de testes do <em lang="en">AccessMonitor</em>, ou seja: testes do tipo verdadeiro, do tipo falso, do tipo decrescente e do tipo proporcional. A variável P (ponderação) encontra-se explicitada acima.

### Bateria de testes {#n17}

[Bateria de testes](/accessmonitor/bateria.php) | Para uma análise detalhada dos 86 testes consulte a bateria de testes.