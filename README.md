# **GANCHO PARA AS DROGAS**

O presente trabalho tem por objetivo estudar possíveis ganchos que levam crianças e adolescentes à buscarem drogas ilícitas.

Para acessar o notebook [clique aqui](https://nbviewer.jupyter.org/github/Raoni-Silva/PeNSE_GanchoDrogas/blob/main/PeNSE_GanchoDrogas.ipynb).

## **BASE DE DADOS**

A base de dados escolhida é a **PeNSE 2015 Amostra2** (**Pesquisa Nacional de Saúde do Escolar**) criada pelo IBGE.

A descrição a seguir foi obtida no próprio [site](https://www.ibge.gov.br/estatisticas/sociais/educacao/9134-pesquisa-nacional-de-saude-do-escolar.html?=&t=o-que-e) do governo.

**O que é**

Investiga informações que permitem conhecer e dimensionar os fatores de risco e proteção à saúde dos adolescentes. A pesquisa é realizada por amostragem, utilizando como referência para seleção o cadastro das escolas públicas e privadas do Instituto Nacional de Estudos e Pesquisas Educacionais Anísio Teixeira - INEP.  

A Pesquisa Nacional de Saúde do Escolar - PeNSE teve início em 2009, fruto de parceria com o Ministério da Saúde e apoio do Ministério da Educação. Na primeira edição, os escolares do 9o ano do ensino fundamental (antiga 8a série) das escolas públicas e privadas dos Municípios das Capitais constituíram sua população-alvo. A escolha do 9o ano do ensino fundamental, cabe destacar, teve como justificativa o mínimo da escolarização necessária para responder questionário autoaplicável e também a proximidade da idade de referência preconizada pela Organização Mundial da Saúde - OMS (World Health Organization - WHO), que é de 13 a 15 anos. Em 2012, embora mantida sua população-alvo, a PeNSE passou a abarcar dados para o conjunto do País e as Grandes Regiões, e a investigar, também, algumas características do ambiente escolar e do entorno. Na edição de 2015, importantes inovações foram introduzidas na pesquisa, dentre as quais se destaca a disponibilização de informações oriundas de dois planos amostrais distintos: escolares frequentando o 9o ano do ensino fundamental e escolares de 13 a 17 anos de idade frequentando as etapas do 6o ao 9o ano do ensino fundamental (antigas 5a a 8a séries) e da 1a a 3a série do ensino médio. A primeira amostra, tradicional da PeNSE, não só permite a comparação temporal entre os Municípios das Capitais nas três edições da pesquisa, como também possibilita a desagregação das informações por Unidades da Federação, oferecendo, assim, dados de saúde mais próximos da realidade local desses estudantes. A segunda amostra, por sua vez, proporciona melhor identificação e acompanhamento de fatores relacionados ao desenvolvimento físico-biológico e ao tempo de exposição às condições de risco para o grupo etário considerado, e viabiliza maior comparabilidade com indicadores internacionais, em especial aqueles provenientes da OMS.

A pesquisa fornece informações sobre as características básicas da população de estudo, incluindo aspectos socioeconômicos, como escolaridade dos pais, inserção no mercado de trabalho e posse de bens e serviços; contextos social e familiar; fatores de risco comportamentais relacionados a hábitos alimentares, sedentarismo, tabagismo, consumo de álcool e outras drogas; saúde sexual e reprodutiva; exposição a acidentes e violências; hábitos de higiene; saúde bucal; saúde mental; e percepção da imagem corporal, entre outros tópicos. Características do ambiente escolar e do entorno são também contempladas, incluindo informações relacionadas à infraestrutura disponível para alimentação e atividade física; acessibilidade; saneamento básico; existência de regras e normas de conduta adotadas pelas escolas; políticas de assistência à saúde; e nível de segurança do entorno, entre outros aspectos.

A periodicidade da pesquisa é eventual. Sua abrangência geográfica é nacional: na edição de 2015, realizada com dois planos amostrais distintos, os resultados da amostra 1 estão disponíveis para Brasil, Grandes Regiões, Unidades da Federação e Municípios das Capitais; e para a amostra 2, Brasil e Grandes Regiões.

## **INTRODUÇÃO**

A maioria das pessoas acredita que determinadas drogas causam vícios catastróficos em pessoas que as usam. Esta crença convencional é observada em frases como "quem usa cocaína se vicia instantâneamente" ou "heroína é tão boa, não experimente nem uma única vez". Também está implícito na literatura profissional que rotineiramente descreve certas drogas como "viciantes", "produtoras de dependência" ou "viciadoras". A crença de que as drogas podem induzir ao vício moldou as políticas de drogas por mais de séculos pelo mundo e ainda molda aqui em nosso país.

O conceito vigente sobre dependência química estava muito atrelado à experimentos realizados com ratos em que eram oferecido duas opções de água. Uma primeira pura sem aditivos e uma segunda misturada com morfina. Neste experimento os ratos passaram a procurar apenas a água com morfina até terem uma overdose e virem a óbito.

Na década de 1970 o psicólogo canadense Bruce K. Alexander e seus colegas resolveram questionar essa verdade absoluta repetindo o mesmo experimento com uma pequena diferença. Ao invés de deixarem os ratos em uma gaiola simples eles criaram um ambiente com diversas opções de entretenimento e diversão. O experimento ficou conhecido como "Rat Park experiment". <sup>[1]</sup> O resultado desse experimento foi que nenhum rato escolheu a água com morfina o tempo todo. A maioria optou pela opção com água pura e nenhum teve overdose ou problemas relacionados à dependência. O que leva ao questionamento que faz Johann Hari em sua apresentação no TEDTalk <sup>[2]</sup>: 

<i>"E se o vício não for sobre algum gancho químico? E se o vício for sobre a sua gaiola?"</i>

Feito o questionamento, minha análise consiste em tentar entender se existe alguma relação entre o uso de drogas entre crianças e adolescentes e problemas de "gaiola", ou seja, do contexto social em que vivem, do ambiente familiar, autoestima, entre outros. Algum motivo emocional de gancho que aumente as chances dos jovens entrarem para o mundo das drogas (lícitas ou ilícitas).

A análise não será focada diretamente nas questões relacionadas às drogas, mas em tentar entender o perfil dos entrevistados, baseado em diversas frentes, e a partir daí relacionar com as questões de uso de drogas.

O trabalho é parte do terceiro módulo do Bootcamp de Data Science Aplicada da Alura e utiliza como base de dados a Pesquisa Nacional de Saúde do Escolar - PeNSE 2015 amostra 2. <sup>[3]</sup>

A PeNSE, segundo o próprio site, "Investiga informações que permitem conhecer e dimensionar os fatores de risco e proteção à saúde dos adolescentes. A pesquisa é realizada por amostragem, utilizando como referência para seleção o cadastro das escolas públicas e privadas do Instituto Nacional de Estudos e Pesquisas Educacionais Anísio Teixeira - INEP." <sup>[4]</sup> 

**FONTE:**

[1] [Rat-Park, wikipedia](https://en.wikipedia.org/wiki/Rat_Park)   (acesso em: 16 de dezembro de 2020)

[2] [Johann Hari, TEDTalk](https://www.youtube.com/watch?v=PY9DcIMGxMs)

[3] [PeNSE 2015 Amostra2, IBGE](https://www.ibge.gov.br/estatisticas/downloads-estatisticas.html?caminho=pense/2015/microdados/)    (acesso em: 16 de dezembro de 2020)

[4] [O que é?, PeNSE](https://www.ibge.gov.br/estatisticas/sociais/educacao/9134-pesquisa-nacional-de-saude-do-escolar.html?=&t=o-que-e)   (acesso em: 16 de dezembro de 2020)

## **RESUMO**

Os ganchos analisados que podem levar crianças/adolescentes à procurarem drogas ilícias foram os seguintes:

- Ambiente escolar
- Ambiente doméstico
- Auto estima
- Condição sócio econômica
- Enriquecimento ambiental *
- Drogas lícitas

[*] Ao longo do trabalho utilizarei muito o termo "enriquecimento ambiental" que é um termo muito utilizado com animais em cativeiro, onde são oferecidos brinquedos, desafios e atividades, como por exemplo um picolé de carne congelada ao invés de carne in natura, para que este fique com a atenção voltada para algo evitando o que diz o antigo ditado "cabeça vazia é oficina do diabo".

Exemplos do que poderíamos chamar de "enriquecimento ambiental" no caso dos humanos são os esportes, atividades escolares, trabalho, entre outros. 


**TÓPICOS ANALISADOS**

- 07 - Entendendo o quadro geral das drogas lícitas e ilícitas na base de dados
- 08 - Análise de ganchos do ambiente familiar
- 09 - Análise de ganchos da condição sócio-econômica
- 10 - Análise de ganchos do ambiente escolar
- 11 - Análise de ganchos de auto estima
- 12 - Análise de ganchos das drogas lícitas

**RESULTADOS OBTIDOS**

Os maiores ganchos que levam as crianças/adolescentes a consumirem drogas ilícitas são relacionadas ao ambiente familiar e de proximidade com drogas lícitas.
