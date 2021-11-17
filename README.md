<html>
  <body>
     <table align="center">
     <tr>
       <td align="center"><a href="https://www.linkedin.com/in/guilhermeftavares/"><img style="border-radius: 50%;" src="https://github.com/GabrielSG20/API4Sem2021/blob/documentation/images/GuilhermeTavares.png" width="25%;" alt=""/><br/><sub><b>Guilherme Tavares</b></sub></a><br/><sub><b>Product Owner</b></sub></td>
     </tr>
    </table>

  <ol>
    <h3><li><b>Descrição do Projeto</b></li></h3>
    <p align="justify">
      <a href="http://vempracasa.herokuapp.com/">#VEMPRACASA</a> é uma parceria entre a Oracle e a FATEC São José dos Campos com a finalidade de desenvolvimento de um Sistema para realização de agendamentos de eventos nos espaços da Casa Oracle, seguindo as normas vigentes de ocupação por conta da Pandemia do Coronavírus, tendo a possibilidade de priorização de acordo com regras de negócio, facilitando a inscrição e cadastro de convidados e aumentando o controle por parte dos organizadores.
    </p>
      <ol>
        <h4><li><b>Objetivo Geral</b></li></h4>
        <p align="justify">
       Desenvolvimento de uma ferramenta para agendamento de eventos da Casa Oracle com a possibilidade de controle de lotação devido à Pandemia do Corana Vírus, garantindo maior seguridade aos convidados, organizadores e fornecedores.
        </p>
        <h4><li><b>Objetivos Específicos</b></li></h4>
        <p align="justify">
        Como objetivos específicos temos:
          <ul>
            <li>Uso de Metodologia Ágil para Planejamento, desenvolvimento de Backlog do Produto e consolidação do Mínimo Produto Viável (MVP) para cada Sprint;</li>
            <li>Aperfeiçoamento do uso de Linguagem de Programação (Java, Typescript, Javascript e SQL) como parte do desenvolvimento acadêmico do curso de Tecnologia em Banco de Dados;</li>
            <li>Uso de conceitos de UX/UI no desenvolvimento do sistema para facilitar o acesso e interação dos usuários;</li>
            <li>Desenvolvimento de Ferramenta com níveis de acesso de usuário como forma de garantia de segurança do sistema;</li>
            <li>Uso de Plataforma Cloud para deploy das aplicações desenvolvidas e garantia de melhor performance da ferramenta.</li>
          </ul>
          </p> 
        </ol>    
        <p align="justify">
        A partir dos objetivos propostos, as Funcionalidades foram definidas de acordo com os usuários mapeados por meio da Metodologia Product Backlog Building (<a href="https://bityli.com/HaSYZr">AGUIAR; CAROLI, 2021</a>), que consiste num método de refinamento colaborativo para o desenvolvimento do backlog do produto. Além disso, o método auxilia na construção de um entendimento compartilhado do negócio, descreve a experiência do usuário com o produto, facilita a escrita de user stories, define o alinhamento e planejamento inicial e, consequentemente, produz um Product Backlog alinhado com as necessidades do cliente.</p> 
    </ol>
    <ol start="2"> 
    <h3><li><b>Tecnologias Utilizadas</b></li></h3>
      <p align="justify">
      As principais tecnologias utilizadas para o desenvolvimento do Sistema, são:
        <ul>
          <li><a href="https://www.figma.com/">Figma</a></li>
          <p align="justify"> Segundo <a href="http://ijistech.org/ijistech/index.php/ijistech/article/view/145/145">Putra et al. (2021)</a>, Figma é uma ferramenta para projetos UI com excelentes ferramentas termos de Design, Prototipagem, Colaboração, Plug-in de Sistema de Projeto etc.Por conta disso, dentro da nossa ferramenta, foi utilizado o plugin FigJam para (i) realização de metodologia de Design thinking para o levantamento das principais dúvidas sobre o projeto e desenvolvimento de um esboço e linha lógica de construção e (ii) uso da metodologia Product Backlog Building para o entendimento das "dores" do cliente, alinhamento das expectativas, levantamento dos usuários e de suas funcionalidades dentro do sistema, criação de user stories, priorização das user stories e construção do Product Backlog com os principais MVPs para cada Sprint.</p>
          <li><a href="https://www.atlassian.com/br/software/jira">Jira</a></li>
          <p align="justify"> De acordo com <a href="https://citeseerx.ist.psu.edu/viewdoc/download?doi=10.1.1.1090.9400&rep=rep1&type=pdf">Fischer et al. (2013)</a>, JIRA é um sistema de rastreamento de problemas comumente usado em bugs de software, entretanto, por conta de seus recursos avançados de personalização, é adequado para uso em diferentes atividades na resolução de tíquetes de suporte, bem como no gerenciamento de projeto. Na ferramenta, o sitema foi utilizado como ferramenta do método Scrum para distribuição das atividades do time e priorização das demandas. Cada user story desenvolvida, foi atribuída a um dos integrantes do time com as informações do que deveria ser desenvolvido e dos critérios de aceitação que deveriam ser seguidos com o objetivo de garantir a possibilidade de teste de cada task.</p>
          <li><a href="https://angular.io/">Angular</a></li>
          <p align="justify">
          É um framework de desenvolvimento web baseado em TypeScript, a ferramenta é uma parceria entre a Google e a Microsoft que faz uso de SPA(Single Page Applications), ou seja, aplicação de uma única página <a href="https://periodicos.unisanta.br/index.php/sat/article/viewFile/801/1215">(FONSECA JUNIOR et al., 2018)</a>.
Para nossa aplicação, o Agular foi a framework escolhida para o desenvolvimento de too front-end do projeto justamente pelo uso de SPA e por possuir uma arquitetura baseada em componentes, os quais funcionam como blocos e podem ser utilizados de acordo com a necessidade do projeto, permitindo maior flexibilização devido a possibilidade de reutilização de código.
          </p>
          <li><a href="https://spring.io/">Spring Framework</a></li>
          <p align="justify">
          Spring é um framework de código aberto para o desenvolvimento de aplicativos mais produtivos, representando 30% de participação de frameworks utilizadas para JAVA <a href="https://www.researchgate.net/profile/Sinisa-Randic/publication/321757987_Java_Spring_Boot_Rest_WEB_Service_Integration_with_Java_Artificial_Intellgence_Weka_Framework/links/5a305d44aca27271ec8a07f8/Java-Spring-Boot-Rest-WEB-Service-Integration-with-Java-Artificial-Intellgence-Weka-Framework.pdf">(Jovanović et al., 2017)</a>. Já o Spring Boot foi projetado para simplificar e facilitar o desenvolvimento de aplicativos Spring e, segundo <a href="https://www.amazon.com/Introducing-Spring-Framework-Felipe-Gutierrez-ebook-dp-B01HXJIR3C/dp/B01HXJIR3C/ref=mt_other?_encoding=UTF8&me=&qid=">GUTIERREZ (2014)</a>, dentre os conceitos principais, os mais importantes são: (i) configuração automática, (ii) dependências iniciais, (iii) interpretador de linha de comando e (iv) o atuador.
O Spring foi a framework utilizada no desenvolvimento da nossa aplicação, justamente pela facilidade de ser utilizado, bem como a grande quantidade de material desenvolvido para a resolução de problemas de programação.
          </p>
          <li><a href="https://www.oracle.com/tools/downloads/sqldev-downloads.html">Oracle SQL Developer</a></li>
          <p align="justify">
          O Oracle SQL Developer é uma ferramenta gráfica que aumenta a produtividade e simplifica as tarefas de desenvolvimento de banco de dados. O SQL Developer, permie que os usuários naveguem por objetos de banco de dados, executem instruções SQL, ediemr e depurem instruções PL/SQL e executem relatórios <a href="https://www.oracle.com/webfolder/technetwork/tutorials/obe/db/11g/r2/prod/appdev/sqldev/sqldev_mngdb/sqldev_mngdb_otn.htm">(ORACLE, 2021)</a>.
O Oracle SQL Developer foi utilizado em nosso projeto devido às suas vantagens, como portabilidade, capacidade de restaurar e recuperar, por suportar múltiplos banco de dados, pela presença no mercado, entre outros.
          </p>
      </ul>
      </p>
    <h3><li><b>Contribuição para o Projeto</b></li></h3>
    <p align="justify">Como Product Owner da nossa equipe, fui responsável pelo contato direto com os colaboradores da Oracle e pelo planejamento do Product Backlog uma vez que o Projeto foi desenvolvido utilizando metodologia Ágil.</p>
  <p align="justify">A primeira prática para o planejamento da aplicação foi um sessão de <a href="https://www.figma.com/file/E0O9WFOCh63ult0YvkEjVs/%23VemPraCasa?node-id=0%3A1">Design Thinking</a> em que se buscou levantar as principais percepções da equipe em relação a reunião de kick off do produto e as principais dúvidas para que pudéssemos tirar com o cliente e, a partir disso, desenvolver o product backlog do projeto.</p>
  <p align="justify">As perguntas foram levantadas e, posterior às respostas do cliente, iniciou-se sessões de Product Backlog Building, uma metodologia para alcançar de forma colaborativa o Product Backlog da aplicação.</p>
  <p align="justify">O primeiro passo foi analisar quais eram as dores e os problemas enfrentados pelo cliente a partir das perguntas realizadas e da sessão de kick off, posteriormente fizemos o levantamento das expectativas que o cliente tinha em relação a ferramenta para que pudéssemos, então, realizar o levantamento dos principais usuários, tendo sido identificados: convidado externo, convidado interno, organizador e administrador.</p>
  <p align="justify">Em seguida, fizemos uma sessão para encontrarmos as funcionalidades que nossa ferramenta deveria ter de acordo com cada usuário, ainda dentro da metodologia PBB e, por fim, fizemos o levantamento dos diversos itens que cada funcionalidade teria dentro do nosso sistema.</p>
  <p align="justify">Alcançados os product backlog itens, foi realizado uma priorização de cada item de acordo com a sua importância dentro do sistema e frequência de uso no formato de somatório, sendo garantido uma nota para cada PBI, a partir dessa classificação foi desenvolvido o product backlog de acordo com a necessidade e importância encontrados, sendo validado pelo cliente.</p>
  <p align="center"><img style="border-radius: 50%" src="https://github.com/guiftavares/MetodologiaCientifica/blob/main/images/vemPraCasa.png" width="50%"></p>
  <p align="justify">Após o product backlog, desenvolvi as wireframes do projeto baseadas em conceitos de UX e UI de acordo com o conteúdo de <a href="https://www.amazon.com.br/N%C3%A3o-fa%C3%A7a-pensar-Steve-Krug/dp/8576088509/ref=asc_df_8576088509/?tag=googleshopp00-20&linkCode=df0&hvadid=379726290955&hvpos=&hvnetw=g&hvrand=17865502529510744382&hvpone=&hvptwo=&hvqmt=&hvdev=c&hvdvcmdl=&hvlocint=&hvlocphy=9100233&hvtargid=pla-811021535400&psc=1">Krug (2014)</a> e do <a href="https://www.w3.org/WAI/standards-guidelines/wcag/">Web Content Accessibility Guideline (WCAG)</a> utilizando o Figma para o design.</p>
  <p aling="justify">Para as <a href="https://www.figma.com/file/1EJaoQ2dnKBf6myfMCjqG6/Wireframes?node-id=0%3A1">wireframes</a> foi utilizada paleta de cores acessíveis para pessoas com daltonismo, por exemplo. Ao acessar nossa aplicação, a pessoa daltônica poderá claramente ver o contraste entre as cores, uma vez que elas possuem comprimentos de ondas que são distinguíveis para elas.</p>
  <p align="center"><img style="border-radius: 50%" src="https://github.com/GabrielSG20/API4Sem2021/blob/documentation/images/home_page.png" width="50%"></p>
  <p align="justify">Além disso, desenhamos a ferramenta para que as pessoas possam navegar por ela de forma intuitiva e facilitada, fazendo jus ao título do livro de Krug: “Não me Faça Pensar”.</p>
  <p align="justify">Em relação a programação, minha responsabilidade foi em suportar o desenvolvimento das telas no front-end utilizando HTML e SCSS no VS Code utilizando o framework Angular. Desenvolvi os designs das telas de Cadastro de usuário, Login, Cadastro como Organizador etc.</p>
  </ol>
  <ol start="3">
     <h3><li><b>Lições Aprendidas</b></li></h3>
     <ol>
      <li>Avancei no entendimento e uso da metodologia ágil;</li>
      <li>Liderei sessão de design thinking baseado nos estudos que realizei sobre a metodologia;</li>
      <li>Liderei as sessões de Product Backlog Building (PBB) baseadas nos estudos realizados sobre o método;</li>
      <li>Aprimorei meus conhecimentos no Figma, utilizando novas ferramentas como a prototipação das wireframes;</li>
      <li>Aumentei meus conhecimentos em relação a UI/UX design, focando o desenvolvimento das wireframes nos usuários do Sistema;</li>
      <li>Iniciei na Programação front-end conhecendo o VS Code e o Angular;</li>
      <li>Aprimorei meus conhecimentos em HTML e SCSS, pois pude desenvolver novas funções que não havia realizado até o momento, bem como não utilizar um padrão já existente, construindo a ferramenta do zero a partir dos estudos realizados e as wireframes construídas.</li>
      </ol>
 </ol>
  </body>
</html>
