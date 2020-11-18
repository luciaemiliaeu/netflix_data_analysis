# Netflix data Analysis 

- Oi, meu nome é Lúcia, e eu sou viciada em séries. Mais precisamente em Friends e Grey's Anatomy. 

Essa é a conclusão da análise que eu desempenhei dos meus dados da Netflix. 
A conclusão em si não foi novidade para mim, mas os dados foram: eu não tinha noção do tamanho do meu vício. 

##**Detalhes técnicos **

### Base de dados
Os dados da Netflix podem ser solicitados pelo usuário através da conta e então são disponibilizados via e-mail. 

São várias tabelas em um arquivo zip com informações sobre o usuário, a conta, acessos e etc.  O zip também contém um pdf com as informações necessárias sobre os dados para que o usuário possa analisá-los. 

Por questões de privacidade, apenas o *ViewingActivity* foi utilizado. Essa tabela contém informações sobre "O que foi assistido" (como o nome do perfil do usuário, hora e data que a visualização começou, duração e título) na minha conta da netflix no intevalo de 2017-2020.

### Análise 
A análise dos dados foi desempenhada em Python, usando bibliotecas populares: Pandas, Matplotlib, Seaborn e numpy.

Numa primeira etapa, o relatório descreve variáveis relacionadas ao uso da plataforma de maneira geral: consumo total, horário dos acessos, distribuição dos acessos pelo tempo e pelos dias da semana. Na etapa seguinte,  o relatório apresenta um ranking das séries mais assitidas. Então, analisa-se com mais detalhes informações sobre as séries Friends e Grey's Anatomy, já que estas são as (muito) mais assitidas. Por fim, analisou-se os dados excluindo as duas séries. 

### Resultados 
Os resultados atestam o meu vício em Friends e Grey's Anatomy. 

Em minha defesa (se você está aqui me avaliando e pretende me contratar), eu uso a Netflix como barulho de fundo para absolutamente tudo (fazer tarefas domésticas chatas, programar, preencher o silêncio da madrugada, induzir meu sono...) e tudo começou com o intúito de estudar inglês, nesse quesito eu me saí muito bem. Nessas horas eu uso as duas séries. Mas, quando se trata de realmente assistir, meu consumo é bem pequeno. Isso é mostrado no final da análise. 
