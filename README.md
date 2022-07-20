<h1>Portfólio das APIs - Guilherme Tavares</h1>
<p align="justify">Trabalho de Graduação na modalidade Portfólio das APIs,
apresentado à Faculdade de Tecnologia de São José dos Campos,
como parte dos requisitos necessários para a obtenção do título de Tecnólogo em Banco de Dados.</p>
<hr>
<h2>Sumário</h2>
<p>◻️ <a href="#sobre-mim">Sobre mim</a></p>
<p>◻️ <a href="#meus-projetos">Meus Projetos</a></p>
<div class="semestre1">
<ul>◻️ <a href="#granja-do-futuro">1º Semestre de 2020 • Granja do Futuro</a>
<ul>◻️ <a href="#arquitetura-do-projeto">Arquitetura do Projeto</a></ul>
<ul>◻️ <a href="#prévia-da-solução">Prévia da Solução</a></ul>
<ul>◻️ <a href="#tecnologias-utilizadas">Tecnologias Utilizadas</a></ul>
<ul>◻️ <a href="#contribuições-pessoais">Contribuições Pessoais</a></ul>
<ul>◻️ <a href="#lições-aprendidas">Lições Aprendidas</a>
<ul>◻️ <a href="#hard-skills">Hard Skills</a></ul>
<ul>◻️ <a href="#hard-skills">Soft Skills</a></ul>
</ul>
</ul>
</div>
<div class="semestre2">
<ul>◻️ <a href="#processos-otimizados-de-contas">2º Semestre de 2020 • Processos Otimizados de Contas</a>
<ul>◻️ <a href="#arquitetura-do-projeto-">Arquitetura do Projeto</a></ul>
<ul>◻️ <a href="#prévia-da-solução-">Prévia da Solução</a></ul>
<ul>◻️ <a href="#tecnologias-utilizadas-">Tecnologias Utilizadas</a></ul>
<ul>◻️ <a href="#contribuições-pessoais-">Contribuições Pessoais</a></ul>
<ul>◻️ <a href="#lições-aprendidas-">Lições Aprendidas</a>
<ul>◻️ <a href="#hard-skills-">Hard Skills</a></ul>
<ul>◻️ <a href="#hard-skills-">Soft Skills</a></ul>
</ul>
</ul>
</div>
<hr>
<h2>Sobre mim</h2>
<p align="center"><img src="https://github.com/guiftavares/PorfolioBancoDeDados/blob/main/Resume/GuilhermeTavares.png" width="20%"></p>
<p align="justify">Mestre em Engenharia de Sistemas Agrícolas pela Universidade de São Paulo (USP), bacharel em Engenharia Agrícola e Ambiental 
pela Universidade Federal de Mato Grosso (UFMT) e regularmente matriculado no 6º semestre do curso tecnólogo em Banco de Dados pela Faculdade de 
Tecnologia de São José dos Campos (FATEC).</p>
<p align="justify">Possuo 5 anos de experiência na área de Tecnologia. Durante esse período, tive a oportunidade de desenvolver sistemas inteligentes 
e modelos matemáticos em parceria com o Departamento de Agricultura dos Estados Unidos (USDA). Trabelhei com Gestão de Projetos e Portfólio nas áreas 
de Supply Chain Technology e Construção Civil. Além disso, atuei em análise e governança de dados em system reliability e data quality.</p>
<p align="justify">Atualmente trabalho como analista de tecnologia financeira na Johnson & Johnson, trabalho com Digital Transformation 
automatizando processos na área com ferramentas low-code (Power Platform), estou em desenvolvimento como especialista na plataforma Anaplan 
e atuando como product owner na implementação de metodologia ágil para o time de suporte de finanças e em projetos de business intelligence junto ao 
departamento jurídico.</p>
<p align="center">• <a href="">LinkedIn</a> • <a href="https://github.com/guiftavares">GitHub</a> •</p>
<hr>
<div class="semestre1">
<h2>Meus Projetos</h2>
<h3>Granja do Futuro</h3>
<p align="justify">Parceiro Acadêmico: <a href="https://fatecsjc-prd.azurewebsites.net/">Faculdade de Tecnologia de São José dos Campos</a></p>
<p align="center"><img src="https://github.com/guiftavares/PorfolioBancoDeDados/blob/main/1Sem/images/granja_futuro_img.png" widht="20%"></img>
<p align="justify">Granja do Futuro é um aplicativo de Gestão de Propriedade para Avicultura de Corte focado no desempenho zootécnico, conforto e bem-estar animal. 
Com ele, o produtor tem acesso a dados financeiros – como valor do dólar, do ovo e dos insumos, bem como na geração de relatórios sobre sua propriedade e animais.</p>
<p align="justify">O nome do aplicativo tem referência a Fazenda 4.0 e o uso da tecnologia na administração de propriedade. Além disso, utiliza-se de uma visão holística do negócio, informando e tomando como base de avaliação dados importantes sobre o animal e a propriedade como um todo.</p>
<br>
<h3>Arquitetura do Projeto</h3>
<p align="center"><img src="https://github.com/guiftavares/PorfolioBancoDeDados/blob/main/1Sem/images/GranjaDoFuturo.png" width="100%"></img></p>
<br>
<h3>Prévia da Solução</h3>
<p align="justify">A partir dos objetivos propostos, o aplicativo foi dividido em duas funcionalidades: animal e propriedade.</p>
<p align="justify">Na <b>funcionalidade animal</b>, o usuário pode optar pela obtenção do conforto animal por meio automático, conectado a 
<a href="https://advisor.climatempo.com.br/">API Advisor</a> fornecida pelo site <a href="https://www.climatempo.com.br/">ClimaTempo</a>, 
ou pode utilizar no modo manual, em que necessita de informações provenientes de sensores comumente utilizados em granjas de postura e que 
são de baixo custo, sendo essas informações: temperatura do ar (°C), umidade relativa do ar (%), velocidade do ar (m/s) e pressão atmosférica (mmHg). 
A partir desses valores, calcula-se a entalpia específica (kJ/Kg de ar seco) e esta classifca o estado de conforto em que o animal se encontra.</p>
<details>
  <summary><b>Funcionalidade Animal</b></summary>
  <br>
  <table align="center">
    <tr>
      <td alignt="center"><img src="https://github.com/guiftavares/PorfolioBancoDeDados/blob/main/1Sem/images/2.PNG" alt=""/>
      </td>
      <td alignt="center"><img src="https://github.com/guiftavares/PorfolioBancoDeDados/blob/main/1Sem/images/3.PNG" alt=""/>
      </td>
      <td alignt="center"><img src="https://github.com/guiftavares/PorfolioBancoDeDados/blob/main/1Sem/images/4.PNG" alt=""/>
      </td>
    </tr>
  </table>
</details>
<p align="justify">Já na <b>funcionalidade propriedade</b>, o usuário consegue ter uma visão geral da produção e produtividade de sua granja fornencendo algumas informações obrigatórios como número de animais em produção, quantidade de ovos produzidos diariamente, número de animais mortos, número de ovos usados para pesagem e o peso da quantidade de ovos utilizados, respectivamente.</p>
<details>
  <summary><b>Funcionalidade Propriedade</b></summary>
  <br>
  <p align="left"><img src="https://github.com/guiftavares/PorfolioBancoDeDados/blob/main/1Sem/images/app_gif.gif" width="50%" alt=""/></p> 
</details>
<p align="justify">Por fim, o aplicativo Granja do Futuro conta com a <b>funcionalidade gerar relatório</b>, na qual o produtor tem a possibilidade de verificar a 
condição de sua propriedade e do bem-estar de seus animais ao longo de determinado período de tempo.</p>
<details>
  <summary><b>Funcionalidade Gerar Relatórios</b></summary>
  <br>
  <table align="center">
    <tr>
      <td alignt="center"><img src="https://github.com/guiftavares/PorfolioBancoDeDados/blob/main/1Sem/images/10.PNG" alt=""/>
      </td>
      <td alignt="center"><img src="https://github.com/guiftavares/PorfolioBancoDeDados/blob/main/1Sem/images/11.PNG" alt=""/>
      </td>
      <td alignt="center"><img src="https://github.com/guiftavares/PorfolioBancoDeDados/blob/main/1Sem/images/12.PNG" alt=""/>
      </td>
    </tr>
  </table>
</details>
<br>
<h3>Tecnologias Utilizadas</h3>
<p align="justify"><a href="https://appinventor.mit.edu/">AppInventor:</a> para desenvolvimento do aplicativo mobile.</p>
<p align="justify"><a href="https://developers.google.com/blockly">Blockly:</a> linguagem de programação para o desenvolvimento back-end.</p>
<p align="justify"><a href="https://firebase.google.com/">Firebase:</a> para integração com o Web Server e armazenamento dos dados dos itens cadastrados</p>
<p align="justify"><a href="https://www.figma.com/">Figma:</a> para o desenvolvimento e prototipação das wireframes.</p>
<br>
<h3>Contribuições Pessoais</h3>
<p align="justify">Desempenhei o papel de Product Owner, realizando o levantamente dos requisitos para construção do backlog do produto, 
fui responsável pela criação e prototipação das wireframes. Além disso, contribuí com o desenvolvimento da lógica matemática por trás da aplicação e do desenvolvimento da funcionalidade animal.</p>
<ul>
  <li>Definição dos requisitos.</li>
  <li>UX/UI design.</li>
  <li>Prototipação das wireframes.</li>
  <li>Arquitetura da aplicação</li>
  <li>Desenvolvimento da funcionalidade animal - front-end e back-end.</li>
</ul>
<br>
<h3>Lições Aprendidas</h3>
<p align="justify">Tive o meu primeiro contato com o Scrum e com a função de Product Owner, neste semestre desenhei a primeira arquitetura de software com suas 
integrações. Além disso, iniciei meus estudos em UX design e pude aplicar o que foi aprendido em algoritmos utilizando a linguagem blockly para desenvolvimento 
do aplicativo.</p>
<h3>Hard Skills</h3>
<details>
  <summary><b>Clique para ver a lista de hard skills</b></summary>
  <br>
  <table align="center">
    <tr>
      <th width="300px">Tecnologia/Metodologia</th>
      <th width="300px">Classificação</th>
    </tr>
    <tr>
      <td>AppInventor</td>
      <td>★★★★★★☆☆☆☆</td>
    </tr>
    <tr>
      <td>Blockly</td>
      <td>★★★★☆☆☆☆☆☆</td>
    </tr>
    <tr>
      <td>Firebase</td>
      <td>★★★★☆☆☆☆☆☆</td>
    </tr>
    <tr>
      <td>Figma</td>
      <td>★★★★★★☆☆☆☆</td>
    </tr>
    <tr>
      <td>Scrum - Product Owner</td>
      <td>★★★★★★☆☆☆☆</td>
    </tr>
    <tr>
      <td>Design Thinking</td>
      <td>★★★★★★☆☆☆☆</td>
    </tr>
    <tr>
      <td>UX/UI design</td>
      <td>★★★★★★☆☆☆☆</td>
    </tr>
  </table>
</details>
<h3>Soft Skills</h3>
<details>
<summary><b>Clique para ver a lista de soft skills</b></summary>
  <br>
  <table align="center">
    <tr>
      <th width="300px">Habilidade</th>
      <th width="300px">Classificação</th>
    </tr>
    <tr>
      <td>Proatividade</td>
      <td>★★★★★★☆☆☆☆</td>
    </tr>
    <tr>
      <td>Visão de Negócio</td>
      <td>★★★★★★☆☆☆☆</td>
    </tr>
    <tr>
      <td>Comunicação Assertiva</td>
      <td>★★★★★★☆☆☆☆</td>
    </tr>
    <tr>
      <td>Empatia</td>
      <td>★★★★★★☆☆☆☆</td>
    </tr>
    <tr>
      <td>Inteligência Emocional</td>
      <td>★★★★★★☆☆☆☆</td>
    </tr>
    <tr>
      <td>Organização e Planejamento</td>
      <td>★★★★★★☆☆☆☆</td>
    </tr>
    <tr>
      <td>Resiliência</td>
      <td>★★★★★★☆☆☆☆</td>
    </tr>
  </table>
</details>
</div>
<hr>
<div class="semestre2">
<h3>Processos Otimizados de Contas</h3>
<p align="justify">Parceiro Acadêmico: <a href="https://tecsus.com.br/">TecSUS Tecnologias para a Sustentabilidade</a></p>
<p align="center"><img src="https://github.com/guiftavares/PorfolioBancoDeDados/blob/main/2Sem/poc_img.png" widht="20%"></img>
<p align="justify">POC, <a href="https://github.com/MikeBBatista/pi-fatec-java">Processos Otimizados de Contas</a>, é uma aplicação que facilita e otimiza a inserção de informações de contas despradonizadas de energia e água. Devido a grande diversidade de layouts nas contas de água e energia no Brasil, a digitalização dos dados de interesse para empresa, torna-se uma tarefa árdua e dispendiosa.</p>
<p align="justify">Dessa forma, a aplicação POC tem o objetivo de facilitar o trabalho com a digitação de dados fornecendo uma plataforma simples, objetiva, exclusiva e funcional.</p>
<h3>Arquitetura do Projeto </h3>
<p align="center"><img src="https://github.com/guiftavares/PorfolioBancoDeDados/blob/main/2Sem/arquitetura_poc.png"></img></p>
<br>
<h3>Prévia da Solução </h3>
<h3>Tecnologias Utilizadas </h3>
<h3>Contribuições Pessoais </h3>
<h3>Lições Aprendidas </h3>
<h3>Hard Skills </h3>
<h3>Soft Skills </h3>
</div>
<div class="semestre3">
<h3>Processos Otimizados de Contas</h3>
<p align="justify">Parceiro Acadêmico: <a href="https://tecsus.com.br/">TecSUS Tecnologias para a Sustentabilidade</a></p>
<p align="center"><img src="" widht="20%"></img>
<h3>Arquitetura do Projeto </h3>
<h3>Prévia da Solução </h3>
<h3>Tecnologias Utilizadas </h3>
<h3>Contribuições Pessoais </h3>
<h3>Lições Aprendidas </h3>
<h3>Hard Skills </h3>
<h3>Soft Skills </h3>
</div>

