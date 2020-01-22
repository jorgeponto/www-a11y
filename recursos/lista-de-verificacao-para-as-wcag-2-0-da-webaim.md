---
id: 751
title: Lista de verificação para as WCAG 2.0 da WebAIM
date: 2014-01-19T22:32:51+00:00
author: equipa acesso
layout: page
guid: http://www.acessibilidade.gov.pt/?page_id=751
---
<div class="alert" style="color:#000;">
  <h3>
    Índice do Artigo
  </h3>
  
  <ol>
    <li>
      <a href="#perceivable">Percetível</a>
    </li>
    <li>
      <a href="#operable">Operável</a>
    </li>
    <li>
      <a href="#understandable">Compreensível (Understandable)</a>
    </li>
    <li>
      <a href="#robust">Robusto</a>
    </li>
  </ol>
</div>

<div class="section">
  <div class="note">
    <p class="title">
      Translations
    </p>
    
    <p>
      Translations of this checklist are available in:
    </p>
    
    <ul>
      <li>
        <a href="http://qweos.net/blog/2009/01/28/guias-practicas-para-profesionales-web-puntos-de-verificacion-de-las-pautas-de-accesibilidad-al-contenido-web-wcag-20/" title="Link to External Site" class="external"><img src="/media/common/flags/es.png" alt="" /> Spanish<span> &#8211; External Link</span></a> &#8211; courtesy of Jos&eacute; Ram&oacute;n Quevedo Santana.
      </li>
      <li>
        <a href="http://www.blindfriendly.cz/wcag20checklist/" title="Link to External Site" class="external"><img src="/media/common/flags/cz.png" alt="" /> Czech<span> &#8211; External Link</span></a> &#8211; courtesy of Radek Pavl&iacute;cek.
      </li>
      <li>
        <a href="http://99vips.de/blog/2012/01/webaims-wcag-2-0-checklist/" title="Link to External Site" class="external"><img src="/media/common/flags/de.png" alt="" /> German<span> &#8211; External Link</span></a> &#8211; courtesy of Anatoli Bauer.
      </li>
    </ul>
  </div>
  
  <div class="important">
    <p class="title">
      Importante!
    </p>
    
    <p>
      Os conteúdos que se seguem <strong>NÂO</strong> são as Diretrizes de Acessibilidade para o Conteúdo da Web (WCAG) 2.0. Contudo, é uma lista simples de verificação que apresenta as recomendações da WebAIM para implementação dos princípios relacionados com HTML e as técnicas para quem procura a conformidade segundo as WCAG 2.0. A linguagem utilizada é um pouco diferente das <a href="http://www.w3.org/TR/WCAG20/"> especificações oficiais das WCAG 2.0 (http://www.w3.org/TR/WCAG20/)</a> a fim de facilitar a implementação e verificação das páginas web.
    </p>
    
    <p>
      <strong>Diretrizes para utilizar nesta lista de verificação: </strong>
    </p>
    
    <ul>
      <li>
        Esta lista de verificação <strong>não pode ser utilizada para verificação da conformidade segundo as WCAG 2.0</strong>. Deve ser referenciada a documentação oficial das WCAG 2.0 para determinar qualquer nível de conformidade ou não-conformidade.
      </li>
      <li>
        Esta lista de verificação <strong>não deve ser referenciada nas políticas ou na adoção de políticas. </strong> Enquanto esta é uma fonte útil para a implementação técnica das WCAG para o conteúdo HTML, não é útil como lista de verificação para políticas. A documentação oficial das WCAG 2.0 oferece melhores mecanismos para implementar a acessibilidade em políticas ou legislação.
      </li>
      <li>
        As WCAG 2.0 cobrem a acessibilidade de todo o conteúdo web e não de uma tecnologia específica. A linguagem desta lista de verificação foi objeto <strong>primeiramente para avaliação do conteúdo HTML</strong>. É, portanto, bastante limitado e está sujeito a mudanças tecnológicas, enquanto com as WCAG 2.0 isto não acontece tão frequentemente.
      </li>
      <li>
        Esta lista de verificação contém <strong>a interpretação da WebAIM sobre as diretrizes WCAG, os critérios de sucesso e as suas próprias técnicas recomendadas para satisfazer esses critérios de sucesso. </strong> A primeira coluna, da tabela em baixo, faz a ligação aos critérios de sucesso oficiais das WCAG 2.0.
      </li>
    </ul>
    
    <p>
      Existe também <a href="/standards/wcag/WCAG2Checklist.pdf">uma versão PDF desta lista de verificação</a>
    </p></p>
  </div>
</div>

<div class="section" id="perceivable">
  <h3>
    Percetível<br /> <span class="sub">O conteúdo Web é disponibilizado para os sentidos &#8211; visão, audição, e/ou tato</sub></h3> 
    
    <div class="section">
      <h4 id="g1.1">
        Diretriz 1.1<br /> <span class="sub">Alternativos em Texto: Forneça alternativos em texto para qualquer conteúdo não textual </span>
      </h4>
      
      <table>
        <tr>
          <th>
            Critério de Successo
          </th>
          
          <th>
            Recomendações da WebAIM
          </th>
        </tr>
        
        <tr id="sc1.1.1">
          <td>
            <strong><a href="http://www.w3.org/TR/WCAG20/#text-equiv-all">1.1.1 Conteúdo Não-textual </a></strong><br /> (Nível A)
          </td>
          
          <td>
            <ul>
              <li>
                Todas as imagens, botões de imagem de formulários, e imagens de mapa de hot spots têm <a href="/techniques/alttext/">texto alternativo</a> equivalente e apropriado.
              </li>
              <li>
                As imagens que não transmitem conteúdo, são decorativas ou contêm conteúdo que já foi transmitido no texto, são fornecidas com texto alternativo nulo (alt="") ou implementadas como fundos de CSS. Todas as imagens que contêm ligações têm texto alternativo descritivo.
              </li>
              <li>
                Equivalentes alternativos para imagens complexas são fornecidas no contexto ou numa página (com ligação e/ou referenciada via descrição longa) em separado.
              </li>
              <li>
                Botões de formulário têm um valor descritivo.
              </li>
              <li>
                As entradas de formulário têm associado <a href="/techniques/forms/controls">etiquetas de texto</a> ou, se as etiquetas não puderem ser usadas, devem ter um atributo title descritivo.
              </li>
              <li>
                Os recursos multimédia incorporados estão identificados via texto acessível.
              </li>
              <li>
                As frames estão <a href="/techniques/frames/">intituladas</a> apropriadamente.
              </li>
            </ul>
          </td>
        </tr>
      </table>
    </div>
    
    <div class="section">
      <h4 id="g1.2">
        Diretriz 1.2<br /> <span class="sub">Multimédia baseada no tempo: Forneça alternativas para multimédia baseada no tempo </span>
      </h4>
      
      <p>
        NOTA: Se o áudio ou o vídeo é designado como alternativa ao conteúdo web (e.g., uma versão áudio ou em língua gestual de uma página web), então o próprio conteúdo web serve como alternativa.
      </p>
      
      <table>
        <tr>
          <th>
            Critérios de Sucesso
          </th>
          
          <th>
            Recomendações da WebAIM
          </th>
        </tr>
        
        <tr id="sc1.2.1">
          <td>
            <strong><a href="http://www.w3.org/TR/WCAG20/#media-equiv-av-only-alt">1.2.1 Apenas Áudio e Apenas Vídeo Pré-gravados </a></strong><br /> (Nível A)
          </td>
          
          <td>
            <ul>
              <li>
                Uma transcrição de texto descritivo (incluindo todas as relevantes pistas e indicadores visuais e auditivos) é fornecida em indireto, com base na web em áudio (podcasts em áudio, ficheiros MP3, etc.).
              </li>
              <li>
                Uma descrição em texto ou áudio é fornecida em indireto, baseada na web com vídeo apenas (e.g., um vídeo sem faixa de áudio).
              </li>
            </ul>
          </td>
        </tr>
        
        <tr id="sc1.2.2">
          <td>
            <strong><a href="http://www.w3.org/TR/WCAG20/#media-equiv-captions">1.2.2 Legendas (Pré-gravadas)</a></strong><br /> (Nível A)
          </td>
          
          <td>
            <ul>
              <li>
                <a href="/techniques/captions/">Legendas</a> sincronizadas são fornecidas em indireto, vídeo com base na web (vídeos do YouTube, etc.)
              </li>
            </ul>
          </td>
        </tr>
        
        <tr id="sc1.2.3">
          <td>
            <strong><a href="http://www.w3.org/TR/WCAG20/#media-equiv-audio-desc">1.2.3 Áudiodescrição ou Multimédia Alternativa (Pré-gravada) </a></strong><br /> (Nível A)
          </td>
          
          <td>
            <ul>
              <li>
                Numa <a href="/techniques/captions/#transcripts">transcrição</a> de texto descritivo OU <a href="/techniques/captions/#ad">áudiodescrição</a> a faixa áudio é fornecida em indireto, vídeo com base na web.
              </li>
            </ul>
          </td>
        </tr>
        
        <tr id="sc1.2.4">
          <td>
            <strong><a href="http://www.w3.org/TR/WCAG20/#media-equiv-real-time-captions">1.2.4 Legendas (Em direto)</a></strong><br /> (Nível AA)
          </td>
          
          <td>
            <ul>
              <li>
                Legendas sincronizadas são fornecidas para a totalidade da multimédia em direto que inclua áudio (transmissões apenas em áudio, difusões web, vídeoconferências, animações em Flash, etc.)
              </li>
            </ul>
          </td>
        </tr>
        
        <tr id="sc1.2.5">
          <td>
            <strong><a href="http://www.w3.org/TR/WCAG20/#media-equiv-audio-desc-only">1.2.5 Áudiodescrição (Pré-gravada) </a></strong><br /> (Nível AA)
          </td>
          
          <td>
            <ul>
              <li>
                As áudiodescrições são fornecidas para todo o conteúdo vídeo <br /> NOTA: Apenas necessário se o vídeo transmitir conteúdo visual que não esteja disponível na faixa áudio por defeito.
              </li>
            </ul>
          </td>
        </tr>
        
        <tr id="sc1.2.6">
          <td>
            <strong><a href="http://www.w3.org/TR/WCAG20/#media-equiv-sign">1.2.6 Língua Gestual (Pré-gravada)</a></strong><br /> (Nível AAA)
          </td>
          
          <td>
            <ul>
              <li>
                Um vídeo com língua gestual é fornecido para a totalidade do conteúdo multimédia que contenha áudio.
              </li>
            </ul>
          </td>
        </tr>
        
        <tr id="sc1.2.7">
          <td>
            <strong><a href="http://www.w3.org/TR/WCAG20/#media-equiv-extended-ad">1.2.7 Áudiodescrição Alargada (Pré-gravada) </a></strong><br /> (Nível AAA)
          </td>
          
          <td>
            <ul>
              <li>
                Quando uma faixa de áudiodescrição não pode ser adicionada ao vídeo devido à temporização do áudio (e.g., não haver pausas no áudio), será fornecida uma versão alternativa do vídeo com pausas que permitam áudiodescrições.
              </li>
            </ul>
          </td>
        </tr>
        
        <tr id="sc1.2.8">
          <td>
            <strong><a href="http://www.w3.org/TR/WCAG20/#media-equiv-text-doc">1.2.8 Alternativa em Multimédia (Pré-gravada) </a></strong><br /> (Nível AAA)
          </td>
          
          <td>
            <ul>
              <li>
                É fornecida uma transcrição de texto descritivo para a totalidade da multimédia pré-gravada que contenha faixa de vídeo.
              </li>
            </ul>
          </td>
        </tr>
        
        <tr id="sc1.2.9">
          <td>
            <strong><a href="http://www.w3.org/TR/WCAG20/#media-equiv-live-audio-only">1.2.9 Apenas Áudio (Em direto) </a></strong><br /> (Nível AAA)
          </td>
          
          <td>
            <ul>
              <li>
                É fornecida uma transcrição de texto descritivo (e.g., o guião/script de um áudio em direto) para a totalidade do conteúdo em direto que contenha áudio.
              </li>
            </ul>
          </td>
        </tr>
      </table>
    </div>
    
    <div class="section">
      <h4 id="g1.3">
        Diretriz 1.3<br /> <span class="sub">Adaptável: Criar conteúdo que pode ser apresentado de diferentes formas (por exemplo um layout mais simples) sem perder informação ou estrutura </span>
      </h4>
      
      <table>
        <tr>
          <th>
            Critérios de Sucesso
          </th>
          
          <th>
            Recomendações da WebAIM
          </th>
        </tr>
        
        <tr id="sc1.3.1">
          <td>
            <strong><a href="http://www.w3.org/TR/WCAG20/#content-structure-separation-programmatic">1.3.1 Informações e Relações </a></strong><br /> (Nível A)
          </td>
          
          <td>
            <ul>
              <li>
                <a href="/techniques/semanticstructure/">Marcação semântica</a> é usada para designar cabeçalhos (<h1>), listas (<ul>, <ol>, e <dl>), texto realçado ou texto especial (<strong>, <code>, <abbr>, <blockquote>, por exemplo), etc. A marcação semântica é utilizada apropriadamente.
              </li>
              <li>
                <a href="/techniques/tables/data">As Tabelas</a> são utilizadas para tabelar dados. Onde é necessário, as células com dados são associadas aos seus cabeçalhos. As legendas da tabela de dados e os resumos são usados convenientemente.
              </li>
              <li>
                As etiquetas de texto são associadas aos elementos de entrada de formulário. Os elementos de formulário relacionados são agrupados com fieldset/legend.
              </li>
            </ul>
          </td>
        </tr>
        
        <tr id="sc1.3.2">
          <td>
            <strong><a href="http://www.w3.org/TR/WCAG20/#content-structure-separation-sequence">1.3.2 Sequência com Significação </a></strong><br /> (Nível A)
          </td>
          
          <td>
            <ul>
              <li>
                A <a href="/techniques/screenreader/#linearization">ordem de leitura e navegação</a> (determinada pela ordem do código) é lógica e intuitiva.
              </li>
            </ul>
          </td>
        </tr>
        
        <tr id="sc1.3.3">
          <td>
            <strong><a href="http://www.w3.org/TR/WCAG20/#content-structure-separation-understanding">1.3.3 Características Sensoriais </a></strong><br /> (Nível A)
          </td>
          
          <td>
            <ul>
              <li>
                As instruções não dependem da forma, tamanho, ou localização visual (e.g., "Clique no ícone quadrado para continuar" ou "As instruções encontram-se na coluna da direita").
              </li>
              <li>
                As instruções não dependem do som (e.g., "Um sinal sonoro indica que pode continuar.").
              </li>
            </ul>
          </td>
        </tr>
      </table>
    </div>
    
    <div class="section">
      <h4 id="g1.4">
        Diretriz 1.4<br /> <span class="sub">Discernível: Facilitar a audição e a visualização de conteúdos aos utilizadores, incluindo a separação do primeiro plano e do plano de fundo. </span>
      </h4>
      
      <table>
        <tr>
          <th>
            Critérios de Sucesso
          </th>
          
          <th>
            Recomendações da WebAIM
          </th>
        </tr>
        
        <tr id="sc1.4.1">
          <td>
            <strong><a href="http://www.w3.org/TR/WCAG20/#visual-audio-contrast-without-color">1.4.1 Utilização da Cor </a></strong><br /> (Nível A)
          </td>
          
          <td>
            <ul>
              <li>
                A cor não é utilizada como único método de transmitir conteúdo ou distinguir elementos visuais.
              </li>
              <li>
                A cor isolada não é utilizada para distinguir <a href="/techniques/hypertext/">links</a> no texto circundante salvo se o contraste da luminância entre o link e o texto circundante é de pelo menos 3:1 e uma diferenciação adicional (e.g., ficar sublinhado) é fornecida quando se paira sobre o link ou recebe o foco.
              </li>
            </ul>
          </td>
        </tr>
        
        <tr id="sc1.4.2">
          <td>
            <strong><a href="http://www.w3.org/TR/WCAG20/#visual-audio-contrast-dis-audio">1.4.2 Controlo Áudio </a></strong><br /> (Nível A)
          </td>
          
          <td>
            <ul>
              <li>
                É fornecido um mecanismo para parar, pausar, silenciar, ou ajustar o volume para o áudio que é accionado automaticamente numa página com a duração superior a 3 segundos.
              </li>
            </ul>
          </td>
        </tr>
        
        <tr id="sc1.4.3">
          <td>
            <strong><a href="http://www.w3.org/TR/WCAG20/#visual-audio-contrast-contrast">1.4.3 Contraste (Mínimo)</a></strong><br /> (Nível AA)
          </td>
          
          <td>
            <ul>
              <li>
                O texto e as imagens de texto têm uma <a href="/resources/contrastchecker/">relação de contraste</a> de pelo menos 4.5:1.
              </li>
              <li>
                O texto ampliado (superior ao tamanho 18 ou tamanho 14 a negrito) tem uma relação de contraste de pelo menos 3:1
              </li>
            </ul>
          </td>
        </tr>
        
        <tr id="sc1.4.4">
          <td>
            <strong><a href="http://www.w3.org/TR/WCAG20/#visual-audio-contrast-scale">1.4.4 Redimensionar o texto </a></strong><br /> (Nível AA)
          </td>
          
          <td>
            <ul>
              <li>
                A página é legível e funcional quando o tamanho do texto passar para o dobro.
              </li>
            </ul>
          </td>
        </tr>
        
        <tr id="sc1.4.5">
          <td>
            <strong><a href="http://www.w3.org/TR/WCAG20/#visual-audio-contrast-text-presentation">1.4.5 Imagens de Texto </a></strong><br /> (Nível AA)
          </td>
          
          <td>
            <ul>
              <li>
                Se a mesma apresentação visual pode ser feita por texto unicamente, não será utilizada uma imagem para apresentar esse texto.
              </li>
            </ul>
          </td>
        </tr>
        
        <tr id="sc1.4.6">
          <td>
            <strong><a href="http://www.w3.org/TR/WCAG20/#visual-audio-contrast7">1.4.6 Contraste (Melhorado)</a></strong><br /> (Nível AAA)
          </td>
          
          <td>
            <ul>
              <li>
                O texto e imagens de texto têm uma <a href="/resources/contrastchecker/">relação de contraste</a> de pelo menos 7:1.
              </li>
              <li>
                O texto ampliado (superior ao tamanho 18 ou tamanho 14 a negrito) tem uma relação de contraste de pelo menos 4.5:1.
              </li>
            </ul>
          </td>
        </tr>
        
        <tr id="sc1.4.7">
          <td>
            <strong><a href="http://www.w3.org/TR/WCAG20/#visual-audio-contrast-noaudio">1.4.7 Som Baixo ou Sem Som de Fundo </a></strong><br /> (Nível AAA)
          </td>
          
          <td>
            <ul>
              <li>
                O áudio de discurso não tem barulho de fundo ou tem muito baixo de forma a que o discurso seja facilmente discernível.
              </li>
            </ul>
          </td>
        </tr>
        
        <tr id="sc1.4.8">
          <td>
            <strong><a href="http://www.w3.org/TR/WCAG20/#visual-audio-contrast-visual-presentation">1.4.8 Apresentação Visual </a></strong><br /> (Nível AAA)
          </td>
          
          <td>
            <ul>
              <li>
                Blocos de texto com tamanho superior a uma frase: <ul>
                  <li>
                    Não têm uma extensão maior do que 80 caracteres.
                  </li>
                  <li>
                    NÃO são totalmente justificados (alinhados em ambas as margens esquerda e direita).
                  </li>
                  <li>
                    Têm um espaçamento entre linhas adequado (pelo menos 1/2 a altura do texto) e o espaçamento entre parágrafos (1.5 linhas de espaço).
                  </li>
                  <li>
                    Têm uma cor específica para o primeiro plano e para o plano de fundo. Esta situação pode ser aplicada a elementos específicos ou à página num todo utilizando CSS (e assim "herdado" por todos os outros elementos).
                  </li>
                  <li>
                    NÂO requerem deslocação horizontal quando o tamanho do texto passar para o dobro.
                  </li>
                </ul>
              </li>
            </ul>
          </td>
        </tr>
        
        <tr id="sc1.4.9">
          <td>
            <strong><a href="http://www.w3.org/TR/WCAG20/#visual-audio-contrast-text-images">1.4.9 Imagens de Texto (Sem Exceção)</a></strong><br /> (Nível AAA)
          </td>
          
          <td>
            <ul>
              <li>
                O texto utilizado numa imagem é apenas decorativo (a imagem não transmite conteúdo) OU quando a informação não pode ser apresentada apenas com texto.
              </li>
            </ul>
          </td>
        </tr>
      </table>
    </div></div> 
    
    <div class="section" id="operable">
      <h3>
        Operável <br /> <span class="sub">Interface de formulários, controlos, e navegação são operáveis </span>
      </h3>
      
      <div class="section">
        <h4 id="g2.1">
          Diretriz 2.1<br /> <span class="sub">Teclado Acessível: Fazer com que todas as funcionalidades fiquem disponíveis a partir do teclado </span>
        </h4>
        
        <table>
          <tr>
            <th>
              Critérios de Sucesso
            </th>
            
            <th>
              Recomendações da WebAIM
            </th>
          </tr>
          
          <tr id="sc2.1.1">
            <td>
              <strong><a href="http://www.w3.org/TR/WCAG20/#keyboard-operation-keyboard-operable">2.1.1 Teclado </a></strong><br /> (Nível A)
            </td>
            
            <td>
              <ul>
                <li>
                  Todas as funcionalidades de uma página estão disponíveis utilizando o teclado, exceto se a funcionalidade não poder de todo ser concluida usando o teclado (e.g., desenho manual livre).
                </li>
                <li>
                  Teclas de atalho e teclas de acesso específicas de uma página (as teclas de acesso devem geralmente ser evitadas) não podem entrar em conflito com os atalhos do navegador existente e do leitor de ecrã.
                </li>
              </ul>
            </td>
          </tr>
          
          <tr id="sc2.1.2">
            <td>
              <strong><a href="http://www.w3.org/TR/WCAG20/#keyboard-operation-trapping">2.1.2 Sem Bloqueio do Teclado</a></strong><br /> (Nível A)
            </td>
            
            <td>
              <ul>
                <li>
                  O foco do <a href="/techniques/keyboard/">teclado</a> nunca está fechado ou bloqueado num elemento particular duma página. O utilizador pode navegar para e a partir de todos os elementos navegáveis de uma página utilizando apenas o teclado.
                </li>
              </ul>
            </td>
          </tr>
          
          <tr id="sc2.1.3">
            <td>
              <strong><a href="http://www.w3.org/TR/WCAG20/#keyboard-operation-all-funcs">2.1.3 Teclado (Sem Exeção)</a></strong><br /> (Nível AAA)
            </td>
            
            <td>
              <ul>
                <li>
                  Todas as funcionalidades de uma página estão disponíveis utilizando o teclado.
                </li>
              </ul>
            </td>
          </tr>
        </table>
      </div>
      
      <div class="section">
        <h4 id="g2.2">
          Diretriz 2.2<br /> <span class="sub">Tempo Suficiente: Fornecer aos utilizadores tempo suficiente para ler e utilizar o conteúdo </span>
        </h4>
        
        <table>
          <tr>
            <th>
              Critérios de Sucesso
            </th>
            
            <th>
              Recomendações da WebAIM
            </th>
          </tr>
          
          <tr id="sc2.2.1">
            <td>
              <strong><a href="http://www.w3.org/TR/WCAG20/#time-limits-required-behaviors">2.2.1 Ajustável por Temporização </a></strong><br /> (Nível A)
            </td>
            
            <td>
              <ul>
                <li>
                  Se uma página ou aplicação tem um limite de tempo, são dadas ao utilizador as opções de desligar, ajustar, ou prolongar esse limite de tempo. Isto não é requisito para eventos em tempo real (e.g., um leilão), onde o limite de tempo é absolutamente exigido, ou se o limite de tempo é superior a 20 horas.
                </li>
              </ul>
            </td>
          </tr>
          
          <tr id="sc2.2.2">
            <td>
              <strong><a href="http://www.w3.org/TR/WCAG20/#time-limits-pause">2.2.2 Colocar em Pausa, Parar, Ocultar</a></strong><br /> (Nível A)
            </td>
            
            <td>
              <ul>
                <li>
                  Movimentos automáticos, intermitentes ou deslocação de conteúdo que durem mais do que 5 segundos podem ser colocados em pausa, parados, ou ocultados pelo utilizador. Mover, piscar, ou deslocar podem ser utilizados para chamar a atenção ou para realçar conteúdo desde que tenha uma duração menor do que 5 segundos.
                </li>
                <li>
                  Atualizações automáticas de conteúdos (e.g., redirecionar automaticamente ou atualizar uma página, uma barra de notícias, campo atualizado AJAX, uma notificação de alerta, etc.) podem ser colocados em pausa, parados, ou ocultados pelo utilizador ou o utilizador pode manualmente controlar a temporização das atualizações.
                </li>
              </ul>
            </td>
          </tr>
          
          <tr id="sc2.2.3">
            <td>
              <strong><a href="http://www.w3.org/TR/WCAG20/#time-limits-no-exceptions">2.2.3 Sem Temporização</a></strong><br /> (Nível AAA)
            </td>
            
            <td>
              <ul>
                <li>
                  O conteúdo e funcionalidade não têm limites ou restrições.
                </li>
              </ul>
            </td>
          </tr>
          
          <tr id="sc2.2.4">
            <td>
              <strong><a href="http://www.w3.org/TR/WCAG20/#time-limits-postponed">2.2.4 Interrupções </a></strong><br /> (Nível AAA)
            </td>
            
            <td>
              <ul>
                <li>
                  Interrupções (alertas, atualizações de página, etc.) podem ser adiadas ou suprimidas pelo utilizador.
                </li>
              </ul>
            </td>
          </tr>
          
          <tr id="sc2.2.5">
            <td>
              <strong><a href="http://www.w3.org/TR/WCAG20/#time-limits-server-timeout">2.2.5 Reautenticação</a></strong><br /> (Nível AAA)
            </td>
            
            <td>
              <ul>
                <li>
                  Se uma sessão com autenticação expirar, o utilizador pode reautenticar-se e continuar a atividade sem perder nenhum dado da página corrente.
                </li>
              </ul>
            </td>
          </tr>
        </table>
      </div>
      
      <div class="section">
        <h4 id="g2.3">
          Diretriz 2.3<br /> <span class="sub">Ataques Epilépticos: Não criar conteúdos de uma forma conhecida por provocar ataques epilépticos </span>
        </h4>
        
        <table>
          <tr>
            <th>
              Critérios de Sucesso
            </th>
            
            <th>
              Recomendações da WebAIM
            </th>
          </tr>
          
          <tr id="sc2.3.1">
            <td>
              <strong><a href="http://www.w3.org/TR/WCAG20/#seizure-does-not-violate">2.3.1 Três Flashes ou Abaixo do Limite</a></strong><br /> (Nível A)
            </td>
            
            <td>
              <ul>
                <li>
                  Nenhum conteúdo de página tem <a href="/articles/seizure/">flashes</a> mais do que 3 vezes por segundo excepto se esse conteúdo flash for suficientemente pequeno e os flashes sejam de baixo contraste e não contenham demasiado a cor vermelha. (<a href="http://www.w3.org/TR/WCAG20/#general-thresholddef">Ver flash em geral e os limites de flash vermelho</a>)
                </li>
              </ul>
            </td>
          </tr>
          
          <tr id="sc2.3.2">
            <td>
              <strong><a href="http://www.w3.org/TR/WCAG20/#seizure-three-times">2.3.2 Três Flashes</a></strong><br /> (Nível AAA)
            </td>
            
            <td>
              <ul>
                <li>
                  Nenhum conteúdo de página tem flashes mais do que 3 vezes por segundo.
                </li>
              </ul>
            </td>
          </tr>
        </table>
      </div>
      
      <div class="section">
        <h4 id="g2.4">
          Diretriz 2.4<br /> <span class="sub">Navegável: Fornecer formas de ajudar os utilizadores a navegar, localizar conteúdo e determinar onde se encontram </span>
        </h4>
        
        <table>
          <tr>
            <th>
              Critérios de Sucesso
            </th>
            
            <th>
              Recomendações da WebAIM
            </th>
          </tr>
          
          <tr id="sc2.4.1">
            <td>
              <strong><a href="http://www.w3.org/TR/WCAG20/#navigation-mechanisms-skip">2.4.1 Ignorar Blocos</a></strong><br /> (Nível A)
            </td>
            
            <td>
              <ul>
                <li>
                  É fornecido um link para <a href="/techniques/skipnav/">saltar a navegação</a> e outros elementos de página que se encontram repetidos transversalmente nas páginas web.
                </li>
                <li>
                  Se a página tiver uma estrutura própria de cabeçalhos, pode ser considerada uma técnica do tipo suficiente ao invés de um link "Saltar para o conteúdo principal". Note que a navegação por cabeçalhos ainda não é suportada em todos os navegadores.
                </li>
                <li>
                  Se uma página utilizar frames e as frames estiverem intituladas propriamente, é considerada uma técnica do tipo suficiente para ignorar frames individualmente.
                </li>
              </ul>
            </td>
          </tr>
          
          <tr id="sc2.4.2">
            <td>
              <strong><a href="http://www.w3.org/TR/WCAG20/#navigation-mechanisms-title">2.4.2 Página com Título</a></strong><br /> (Nível A)
            </td>
            
            <td>
              <ul>
                <li>
                  A página web tem um título descritivo e informativo.
                </li>
              </ul>
            </td>
          </tr>
          
          <tr id="sc2.4.3">
            <td>
              <strong><a href="http://www.w3.org/TR/WCAG20/#navigation-mechanisms-focus-order">2.4.3 Ordem do Foco </a></strong><br /> (Nível A)
            </td>
            
            <td>
              <ul>
                <li>
                  A ordem de navegação de links, elementos de formulários, etc. é lógica e intuitiva.
                </li>
              </ul>
            </td>
          </tr>
          
          <tr id="sc2.4.4">
            <td>
              <strong><a href="http://www.w3.org/TR/WCAG20/#navigation-mechanisms-refs">2.4.4 Finalidade do Link (Em Contexto)</a></strong><br /> (Nível A)
            </td>
            
            <td>
              <ul>
                <li>
                  A finalidade de cada link (ou botão de imagem de um formulário ou mapa de imagem de hotspot) pode ser determinada pelo texto do link sozinho, ou pelo texto do link e o seu contexto (e.g., parágrafos circundantes, itens de lista, células de tabela, ou cabeçalhos de tabela).
                </li>
                <li>
                  Links (ou botões de imagem de formulários) com o mesmo texto que direcionam para diferentes locais são facilmente distinguíveis.
                </li>
              </ul>
            </td>
          </tr>
          
          <tr id="sc2.4.5">
            <td>
              <strong><a href="http://www.w3.org/TR/WCAG20/#navigation-mechanisms-mult-loc">2.4.5 Várias Formas </a></strong><br /> (Nível AA)
            </td>
            
            <td>
              <ul>
                <li>
                  Existem <a href="/techniques/sitetools/">várias formas</a> disponíveis para localizar no sítio web outras páginas &#8211; pelo menos duas das seguintes formas: uma lista de páginas relacionadas, uma tabela de conteúdos, o mapa do sítio web, o campo de pesquisa do sítio, ou a lista de todas as páginas web disponíveis.
                </li>
              </ul>
            </td>
          </tr>
          
          <tr id="sc2.4.6">
            <td>
              <strong><a href="http://www.w3.org/TR/WCAG20/#navigation-mechanisms-descriptive">2.4.6 Cabeçalhos e Etiquetas </a></strong><br /> (Nível AA)
            </td>
            
            <td>
              <ul>
                <li>
                  Cabeçalhos de página e etiquetas para formulário e controlos interativos são informativos. Evitar duplicar cabeçalhos (e.g., "Mais Detalhes") ou texto de etiqueta (e.g., "Primeiro Nome") excepto se a estrutura fornecer uma diferenciação adequada entre os mesmos.
                </li>
              </ul>
            </td>
          </tr>
          
          <tr id="sc2.4.7">
            <td>
              <strong><a href="http://www.w3.org/TR/WCAG20/#navigation-mechanisms-focus-visible">2.4.7 Foco Visível</a></strong><br /> (Nível AA)
            </td>
            
            <td>
              <ul>
                <li>
                  É visualmente perceptível qual o elemento de página que tem o foco do teclado (i.e., conforme se clica na tecla Tab ao longo da página, consegue-se visualizar onde nos encontramos).
                </li>
              </ul>
            </td>
          </tr>
          
          <tr id="sc2.4.8">
            <td>
              <strong><a href="http://www.w3.org/TR/WCAG20/#navigation-mechanisms-location">2.4.8 Localização</a></strong><br /> (Nível AAA)
            </td>
            
            <td>
              <ul>
                <li>
                  Se uma página web faz parte de uma sequência de páginas ou está no seio de uma estrutura complexa de um sítio web, é fornecida uma indicação quanto à localização da página corrente, por exemplo, através de breadcrumbs ou especificando o passo atual numa sequência (e.g., "Passo 2 de 5 &#8211; Endereço de Envio").
                </li>
              </ul>
            </td>
          </tr>
          
          <tr id="sc2.4.9">
            <td>
              <strong><a href="http://www.w3.org/TR/WCAG20/#navigation-mechanisms-link">2.4.9 Finalidade do Link (Apenas o Link)</a></strong><br /> (Nível AAA)
            </td>
            
            <td>
              <ul>
                <li>
                  A finalidade de cada link (ou botão de imagem de um formulário ou mapa de imagem de hotspot) pode ser determinada pelo texto do link sozinho.
                </li>
                <li>
                  Não existem links (ou botões de imagem de um formulário) com o mesmo texto que direcionam para diferentes locais.
                </li>
              </ul>
            </td>
          </tr>
          
          <tr id="sc2.4.10">
            <td>
              <strong><a href="http://www.w3.org/TR/WCAG20/#navigation-mechanisms-headings">2.4.10 Cabeçalhos da Secção </a></strong><br /> (Nível AAA)
            </td>
            
            <td>
              <ul>
                <li>
                  Para além de fornecer uma estrutura na íntegra do documento, as secções individuais do conteúdo são designadas utilizando os cabeçalhos, onde tal se aplicar.
                </li>
              </ul>
            </td>
          </tr>
        </table>
      </div>
    </div>
    
    <div class="section" id="understandable">
      <h3>
        Compreensível <br /> <span class="sub">Conteúdo e interface são compreensíveis </span>
      </h3>
      
      <div class="section">
        <h4 id="g3.1">
          Diretriz 3.1<br /> <span class="sub">Legível: Criar conteúdos textuais legíveis e compreensíveis </span>
        </h4>
        
        <table>
          <tr>
            <th>
              Critérios de Sucesso
            </th>
            
            <th>
              Recomendações da WebAIM
            </th>
          </tr>
          
          <tr id="sc3.1.1">
            <td>
              <strong><a href="http://www.w3.org/TR/WCAG20/#meaning-doc-lang-id">3.1.1 Idioma da Página </a></strong><br /> (Nível A)
            </td>
            
            <td>
              <ul>
                <li>
                  O idioma da página é identificado utilizando o atributo lang em HTML (<html lang="en">, por exemplo).
                </li>
              </ul>
            </td>
          </tr>
          
          <tr id="sc3.1.2">
            <td>
              <strong><a href="http://www.w3.org/TR/WCAG20/#meaning-other-lang-id">3.1.2 Idioma de Partes </a></strong><br /> (Nível AA)
            </td>
            
            <td>
              <ul>
                <li>
                  O conteúdo de uma parte da página que esteja num idioma diferente é identificado utilizando o atributo lang (e.g., <blockquote lang=&#8221;es&#8221;>).
                </li>
              </ul>
            </td>
          </tr>
          
          <tr id="sc3.1.3">
            <td>
              <strong><a href="http://www.w3.org/TR/WCAG20/#meaning-idiom">3.1.3 Palavras Invulgares </a></strong><br /> (Nível AAA)
            </td>
            
            <td>
              <ul>
                <li>
                  <a href="/techniques/writing/">Palavras</a> que possam ser ambíguas, desconhecidas, ou utilizadas de forma muito específica são definidas através de texto adjacente, como uma lista de definições, um glossário, ou outro método adequado.
                </li>
              </ul>
            </td>
          </tr>
          
          <tr id="sc3.1.4">
            <td>
              <strong><a href="http://www.w3.org/TR/WCAG20/#meaning-located">3.1.4 Abreviaturas</a></strong><br /> (Nível AAA)
            </td>
            
            <td>
              <ul>
                <li>
                  As expansões para abreviaturas são fornecidas por extenso ou pela explicação da definição na primeira vez que é utilizada, usando o elemento <abbr>, ou fazendo a ligação para uma definição ou glossário. NOTA: as WCAG 2.0 não abrem exceções para as abreviaturas habitualmente compreendidas (e.g., "HTML" num sítio de design web deve ser sempre expandido).
                </li>
              </ul>
            </td>
          </tr>
          
          <tr id="sc3.1.5">
            <td>
              <strong><a href="http://www.w3.org/TR/WCAG20/#meaning-supplements">3.1.5 Nível de Leitura </a></strong><br /> (Nível AAA)
            </td>
            
            <td>
              <ul>
                <li>
                  É fornecida uma alternativa mais compreensível para o conteúdo mais avançado e que possa ser lido razoavelmente por uma pessoa que tenha fequentado o ensino durante cerca de 9 anos.
                </li>
              </ul>
            </td>
          </tr>
          
          <tr id="sc3.1.6">
            <td>
              <strong><a href="http://www.w3.org/TR/WCAG20/#meaning-pronunciation">3.1.6 Pronúncia</a></strong><br /> (Nível AAA)
            </td>
            
            <td>
              <ul>
                <li>
                  Se a pronúncia de uma palavra for vital para a compreensão dessa mesma palavra, a sua pronúncia é fornecida imediatamente a seguir à palavra ou via link ou glossário.
                </li>
              </ul>
            </td>
          </tr>
        </table>
      </div>
      
      <div class="section">
        <h4 id="g3.2">
          Diretriz 3.2<br /> <span class="sub">Previsível: Fazer com que as páginas Web surjam e funcionem de forma previsível </span>
        </h4>
        
        <table>
          <tr>
            <th>
              Critérios de Sucesso
            </th>
            
            <th>
              Recomendações da WebAIM
            </th>
          </tr>
          
          <tr id="sc3.2.1">
            <td>
              <strong><a href="http://www.w3.org/TR/WCAG20/#consistent-behavior-receive-focus">3.2.1 Em Foco</a></strong><br /> (Nível A)
            </td>
            
            <td>
              <ul>
                <li>
                  Quando um elemento de página recebe o foco, não resulta numa alteração substancial para a página, a reprodução de uma janela pop-up, uma alteração adicional no foco do teclado, ou qualquer outra alteração que possa confundir ou desorientar o utilizador expecto se o utilizador for previamente avisado dessa alteração.
                </li>
              </ul>
            </td>
          </tr>
          
          <tr id="sc3.2.2">
            <td>
              <strong><a href="http://www.w3.org/TR/WCAG20/#consistent-behavior-unpredictable-change">3.2.2 Em Entrada </a></strong><br /> (Nível A)
            </td>
            
            <td>
              <ul>
                <li>
                  Quando um utilizador dá entrada de informação ou interage com um controlo, não resulta numa alteração substancial para a página, a reprodução de uma janela pop-up, uma alteração adicional no foco do teclado, ou qualquer outra alteração que possa confundir ou desorientar o utilizador exceto se o utilizador for previamente avisado dessa alteração.
                </li>
              </ul>
            </td>
          </tr>
          
          <tr id="sc3.2.3">
            <td>
              <strong><a href="http://www.w3.org/TR/WCAG20/#consistent-behavior-consistent-locations">3.2.3 Navegação Consistente </a></strong><br /> (Nível AA)
            </td>
            
            <td>
              <ul>
                <li>
                  A navegação por links que estejam repetidos nas páginas web não alteram a ordem ao navegar-se pelo sítio web.
                </li>
              </ul>
            </td>
          </tr>
          
          <tr id="sc3.2.4">
            <td>
              <strong><a href="http://www.w3.org/TR/WCAG20/#consistent-behavior-consistent-functionality">3.2.4 Identificação Consistente </a></strong><br /> (Nível AA)
            </td>
            
            <td>
              <ul>
                <li>
                  Os elementos que tenham a mesma funcionalidade transversalmente em múltiplas páginas web são consistentemente identificadas. Por exemplo, uma caixa de pesquisa no topo do sítio web deve ser sempre etiquetado de forma igual.
                </li>
              </ul>
            </td>
          </tr>
          
          <tr id="sc3.2.5">
            <td>
              <strong><a href="http://www.w3.org/TR/WCAG20/#consistent-behavior-no-extreme-changes-context">3.2.5 Alteração a Pedido </a></strong><br /> (Nível AAA)
            </td>
            
            <td>
              <ul>
                <li>
                  As alterações substanciais na página, a reprodução de janelas pop-up, alterações incontroláveis no foco do teclado, ou qualquer outra alteração que possa confundir ou desorientar o utilizador devem ser iniciadas pelo utilizador. Em alternativa, é fornecida ao utilizador uma opção para desactivar tais alterações.
                </li>
              </ul>
            </td>
          </tr>
        </table>
      </div>
      
      <div class="section">
        <h4 id="g3.3">
          Diretriz 3.3<br /> <span class="sub">Assistência de Entrada: Ajudar os Utilizadores a evitar e a corrigir erros </span>
        </h4>
        
        <table>
          <tr>
            <th>
              Critérios de Successo
            </th>
            
            <th>
              Recomendações da WebAIM
            </th>
          </tr>
          
          <tr id="sc3.3.1">
            <td>
              <strong><a href="http://www.w3.org/TR/WCAG20/#minimize-error-identified">3.3.1 Identificação de Erro </a></strong><br /> (Nível A)
            </td>
            
            <td>
              <ul>
                <li>
                  Elementos de formulário obrigatórios ou elementos de formulário que obriguem a um formato específico, valor ou extensão deve ser fornecida essa informação dentro do elemento da etiqueta (ou se uma etiqueta não for fornecida, então deverá constar no atributo title do elemento).
                </li>
                <li>
                  Se for utilizada a <a href="/techniques/formvalidation/">validação de formulário</a>, os erros são apresentados de forma eficiente, intuitiva, e acessível. O erro é claramente identificado, é fornecido um acesso rápido ao elemento problemático, e o utilizador é facilmente autorizado a corrigir o erro e a submeter de novo o formulário.
                </li>
              </ul>
            </td>
          </tr>
          
          <tr id="sc3.3.2">
            <td>
              <strong><a href="http://www.w3.org/TR/WCAG20/#minimize-error-cues">3.3.2 Etiquetas ou Instruções </a></strong><br /> (Nível A)
            </td>
            
            <td>
              <ul>
                <li>
                  Etiquetas suficientes, deixas e instruções para elementos interativos obrigatórios são fornecidos por meio de instruções, exemplos, etiquetas de formulários propriamente posicionadas, e/ou os elementos HTML fieldsets/legends.
                </li>
              </ul>
            </td>
          </tr>
          
          <tr id="sc3.3.3">
            <td>
              <strong><a href="http://www.w3.org/TR/WCAG20/#minimize-error-suggestions">3.3.3 Sugestão de Erro</a></strong><br /> (Nível AA)
            </td>
            
            <td>
              <ul>
                <li>
                  Se um erro de entrada é detetado (via pelo lado do cliente ou da validação pelo lado do servidor), forneça sugestões para fixar a entrada de forma oportuna e acessível.
                </li>
              </ul>
            </td>
          </tr>
          
          <tr id="sc3.3.4">
            <td>
              <strong><a href="http://www.w3.org/TR/WCAG20/#minimize-error-reversible">3.3.4 Prevenção de Erros (Legal, Financeiro, Dados)</a></strong><br /> (Nível AA)
            </td>
            
            <td>
              <ul>
                <li>
                  Se o utilizador pode alterar ou apagar dados legais, financeiros ou dados de teste, as alterações/cancelamentos podem ser revertidas, verificadas, ou confirmadas.
                </li>
              </ul>
            </td>
          </tr>
          
          <tr id="sc3.3.5">
            <td>
              <strong><a href="http://www.w3.org/TR/WCAG20/#minimize-error-context-help">3.3.5 Ajuda</a></strong><br /> (Nível AAA)
            </td>
            
            <td>
              <ul>
                <li>
                  Forneça instruções e deixas em contexto para ajudar a completar e a submeter o formulário.
                </li>
              </ul>
            </td>
          </tr>
          
          <tr id="sc3.3.6">
            <td>
              <strong><a href="http://www.w3.org/TR/WCAG20/#minimize-error-reversible-all">3.3.6 Prevenção de Erros (Todos)</a></strong><br /> (Nível AAA)
            </td>
            
            <td>
              <ul>
                <li>
                  Se o utilizador poder submeter informação, a submissão é revertível, verificada, ou confirmada.
                </li>
              </ul>
            </td>
          </tr>
        </table>
      </div>
    </div>
    
    <div class="section" id="robust">
      <h3>
        Robusto<br /> <span class="sub">O conteúdo tem de ser fiável para uma vasta variedade de agentes de utilizador, incluindo tecnologias de apoio </span>
      </h3>
      
      <div class="section">
        <h4 id="g4.1">
          Diretriz 4.1<br /> <span class="sub">Compatível: Maximizar a compatibilidade com os atuais e futuros agentes de utilizador, incluindo tecnologias de apoio</span>
        </h4>
        
        <table>
          <tr>
            <th>
              Critérios de Sucesso
            </th>
            
            <th>
              Recomendações da WebAIM
            </th>
          </tr>
          
          <tr id="sc4.1.1">
            <td>
              <strong><a href="http://www.w3.org/TR/WCAG20/#ensure-compat-parses">4.1.1 Análise</a></strong><br /> (Nível A)
            </td>
            
            <td>
              <ul>
                <li>
                  Devem-se evitar erros significativos de HTML/XHTML assinalados na validação/análise. Verifique em <a href="http://validator.w3.org/">http://validator.w3.org/</a>
                </li>
              </ul>
            </td>
          </tr>
          
          <tr id="sc4.1.2">
            <td>
              <strong><a href="http://www.w3.org/TR/WCAG20/#ensure-compat-rsv">4.1.2 Nome, Função, Valor</a></strong><br />(Level A)
            </td>
            
            <td>
              <ul>
                <li>
                  A linguagem de marcação é utilizada de forma a facilitar a acessibilidade. Isto inclui seguir as especificações de HTML/XHTML e utilizar adequadamente os formulários, as etiquetas de formulários, os títulos das frames, etc. .
                </li>
              </ul>
            </td>
          </tr>
        </table>
      </div>
      
      <p>
        Esta checklist é fornecida como fonte de ajuda a implentar <a href="http://www.w3.org/TR/WCAG20/">Web Content Accessibility Guidelines (WCAG) 2.0</a> (W3C Recommendation 11 December 2008), which is <a href="http://www.w3.org/Consortium/Legal/ipr-notice#Copyright">Copyright</a> &copy; 2008 <a href="http://www.w3.org/"><acronym title="World Wide Web Consortium">W3C</acronym></a><sup>&reg;</sup> (<a href="http://www.csail.mit.edu/"><acronym title="Massachusetts Institute of Technology">MIT</acronym></a>, <a href="http://www.ercim.org/"><acronym title="European Research Consortium for Informatics and Mathematics">ERCIM</acronym></a>, <a href="http://www.keio.ac.jp/">Keio</a>), All Rights Reserved. W3C <a href="http://www.w3.org/Consortium/Legal/ipr-notice#Legal_Disclaimer">liability</a>, <a href="http://www.w3.org/Consortium/Legal/ipr-notice#W3C_Trademarks">trademark</a> and <a href="http://www.w3.org/Consortium/Legal/copyright-documents">document use</a> rules apply.
      </p>