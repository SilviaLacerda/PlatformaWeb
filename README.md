# PlatformaWeb
 Sistema Platforma – site institucional chamado platforma.com. O site é uma plataforma que apoia e complementa o trabalho realizado por uma comunidade de projetos de pequenos empreendedores, incentivando a colaboração e o aprendizado online.

Status do projeto: 
em desenvolvimento;

Tecnologias que serão aplicadas: 
- Linguagens de Programação: HTML, CSS, Javascript, Java e MySql (banco de dados);
- Deverá ser utilizada uma plataforma que não restrinja a implantação do sistema a hardwares e/ou sistemas operacionais Windows, Linux, MAC IOS, Androide
- O site deve ser responsivo, para ser acessado em smartphones.
- As configurações necessárias para acesso e desenvolvimento das atividades da Comunidade de Projetos são: 
- Mínimo de 1 GB de memória RAM; - Monitor configurado com resolução mínima de 1024 x 768 pixels. - Softwares: Sistema operacional Windows , Mac OS ou Linux; - Navegadores de internet: Google Chrome, Internet Explorer, Mozilla Firefox ou Safari; - Conexão banda larga com acesso regular à internet.

Time de desenvolvedores: 
Sílvia Lacerda;

Objetivos do software: 
- Divulgar o programa Platforma na internet: missão, visão, apresentação do trabalho, listar instituições que aderiram, parceiros e ações promovidas;
- Ser um ponto de apoio à Comunidade de Projetos;
- Facilitar para que pequenos e médios empreendedores e parceiros desenvolvam projetos colaborativos;
- Promover a prática de metodologias e Ferramentas de projetos. 

Funcionalidades do sistema (requisitos)

O sistema terá as seguintes funcionalidades:
1- Home: Apresentação Institucional (“quem somos” / “missão” / “visão”); Blog com artigos relativos a projetos em rede e assuntos de interesse dos Parceiros e Participantes da comunidade;
2- Comunidade de Projetos: área restrita para participantes cadastrados. Conteúdo: Tutorial – para que o participante conheça o ambiente virtual e obtenha as informações necessárias para o desenvolvimento de projetos; frameworks de Ferramentas e Metodologias de Projetos;    
3- Fale Conosco: FAQ (Frequently Asked Questions) e seção Fale Conosco (contato do público externo com a equipe administrativa do site).
- O Sistema será implantado por módulos. Neste Projeto Integrador, será desenvolvido o Módulo 1.

- Módulo 1: 
- Seção Home (Institucional e blog); 
- Seção Comunidade de Projetos (Cadastro do Gerente de Projeto, incluindo Cadastro de Senha e Login; Cadastro da Equipe, incluindo Cadastro de Senha e Login de participantes e convidados; Cadastro do Projeto); 
- Seção Fale Conosco - FAQ e Fale Conosco (Mensagem do público externo para o Projeto Platforma);

Considerando que o escopo deste trabalho é o Módulo 1, os requisitos funcionais serão: 
[RF001] < Informações Institucionais do Projeto Platforma>
	Ator: <Administrador do Sistema>
	Descrição: < Desenvolver uma página com as informações estratégicas do Projeto Platforma: Quem somos, Missão, Visão; Formas de Contato; Parceiros; Galeria de Fotos; Pessoas envolvidas. >

[RF002] < Blog >
	Ator: <Administrador do Sistema>
	Descrição: < a princípio, neste módulo, será criado um espaço para publicação de artigos relevantes para a Comunidade de Projetos. O blog deverá permitir comentários dos leitores. Deverá constar desta seção um banner para salientar os tópicos mais importantes para conhecimento da comunidade.>

[RF003] < Cadastro do Projeto>
	Ator: <Desenvolvedor>
	Descrição: < Passo 1 – O Gerente de Projetos clica em botão para acessar o formulário de Cadastro preliminar do Projeto;


Passo 2 - O Gerente de Projetos faz o cadastro preliminar do Projeto no sistema. Campos a serem preenchidos:
Campo 1 – Nome do Projeto: identifique o projeto através de um nome. Como o projeto é conhecido pela equipe do Projeto?
Campo 2 – Breve descrição do projeto: Quem são os clientes do projeto? Quais os benefícios que os clientes terão?

Passo 3 – O Gerente de Projetos envia o formulário de Cadastro do Projeto; 
Passo 4 – O Gerente é direcionado para página onde fará o seu cadastro como participante da comunidade de Projetos>

[RF004] < Cadastro do Gerente de Projetos – incluindo senha e login>
	Ator: <Desenvolvedor>
	Descrição: < a partir do Passo 4 (Cadastro de Projetos – RF003, anterior) ou clicando no link de Cadastrar Gerente de Projetos.
Passo 1 - Preencher o formulário de Cadastro do Gerente de Projetos. Informações necessárias: nome completo; como quer ser chamado; CPF; telefone celular; endereço (rua, número, bairro, cep, cidade); e-mail);
Passo 2 – sistema fornece login: inicial ‘GP’ + número do Projeto (3 algarismos) + ano (2 algarismos)
Passo 3 – Gerente faz a senha (6 números)
Passo 4 – Gerente confirma a senha (6 números definidos no passo anterior)
Passo 5 – Gerente envia cadastro de senha e login;
		Se ok:
Passo 6 – Gerente é encaminhado para a área restrita de Projetos
Senão:
Passo 6 – Gerente é informado das inconsistências encontradas no cadastro;
Passo 7 – Gerente faz acertos
Passo 8 – Gerente envia cadastro de senha e login;
Passo 9 – Gerente é encaminhado para a área restrita de Projetos.>

 [RF005] < Cadastro da equipe – incluindo senha e login >
	Ator: <Desenvolvedor>
	Descrição: < Passo 1 – Gerente de Projeto inclui nome e e-mail do integrante da equipe;
Passo 2 – sistema fornece login: ‘P’ + número auto_increment (2 algarismos) + número do Projeto (3 algarismos) + ano (2 algarismos);
Passo 3 – sistema fornece senha padrão temporária (123456);
Passo 4 – sistema encaminha login, senha e instrução para integrante realizar o cadastro e alterar a senha;
Passo 5 – integrante acessa sistema e preenche o formulário de Cadastro. Informações necessárias: nome completo; como quer ser chamado; CPF; telefone celular; endereço (rua, número, bairro, cep, cidade);
Passo 6 – integrante é encaminhado para fazer nova senha de acesso;
Passo 7 – Integrante faz a senha (6 números);
Passo 8 – Integrante confirma a senha (6 números definidos no passo anterior);
Passo 9 – Integrante envia cadastro de senha e login;
		Se ok:
Passo 10 – Integrante é encaminhado para a área restrita de Projetos;
Senão:
     Passo 11 – Integrante é informado das inconsistências encontradas no
    cadastro;
    Passo 12 – Integrante faz acertos;
   Passo 13 – Integrante envia cadastro de senha e login;

[RF006] < Cadastro de convidados – incluindo senha e login >
	Ator: <Desenvolvedor>
Descrição: < Passo 1 – Gerente de Projeto inclui nome e e-mail do convidado a integrante temporário da equipe;
Passo 2 – sistema fornece login inicial: ‘C’ + número auto_increment (2 algarismos) + número do Projeto (3 algarismos) + ano (2 algarismos);
;
Passo 3 – sistema fornece senha padrão temporária (123456);
Passo 4 – sistema encaminha login, senha e instrução para convidado a integrante temporário da equipe realizar o cadastro;
Passo 5 – convidado a integrante temporário da equipe acessa sistema e preenche o formulário de Cadastro. Informações necessárias: nome completo; como quer ser chamado; CPF; telefone celular; endereço (rua, número, bairro, cep, cidade);
Passo 6 – convidado a integrante temporário da equipe é encaminhado para fazer nova senha de acesso.;
Passo 7 – convidado a integrante temporário da equipe faz a senha (6 números);
Passo 8 – convidado a integrante temporário da equipe confirma a senha (6 números definidos no passo anterior);
Passo 9 – convidado a integrante temporário da equipe envia cadastro de senha e login;
		Se ok:
Passo 10 – convidado a integrante temporário da equipe é encaminhado para   a área restrita de Projetos;
Senão:
Passo 11 – convidado a integrante temporário da equipe é informado das inconsistências encontradas no cadastro;
    Passo 12 – convidado a integrante temporário da equipe faz acertos;
   Passo 13 – convidado a integrante temporário da equipe envia cadastro de  
   senha e login.>

[RF007] < FAQ – Perguntas Frequentes>
	Ator: < Administrador do Sistema >
	Descrição: < Na prática, este framework será uma ferramenta de autoatendimento para dirimir as dúvidas e curiosidades mais frequentes ou normas e regulamentos de funcionamento importantes. A partir das perguntas recorrentes feitas pelos usuários do site, deverá ser criada uma lista com resposta para estas questões. O usuário do site poderá resolver suas dúvidas, curiosidades consultando o material.>

[RF008] < Fale Conosco>
	Ator: < Desenvolvedor >
	Descrição: < Comunicação, via e-mail, do público externo com o Projeto Platforma. 
Passo 1 – O Usuário externo do site registra: nome, e-mail, telefone para contato (opcional) e a mensagem. 
Passo 2 – O Usuário externo encaminha a mensagem. O sistema registra a data em que o usuário encaminhou a mensagem. 
Passo 3 – O usuário administrativo recebe a mensagem. O Sistema registra a entrada da mensagem e aciona tempo de resposta. Ultrapassado o limite de tempo, encaminha lembrete para o responsável pela resposta.
	Se a mensagem:
- tiver resposta pronta na seção de Perguntas Frequentes – o usuário administrativo dispara resposta e conclui demanda;
- for um elogio – o usuário administrativo dispara resposta padrão, encaminha para o Administrador e conclui demanda;
- for crítica, sugestão, ou contiver outros assuntos, encaminha para o Administrador;
- for anônima, ou estiver ininteligível, não será respondida. Será dada como concluída sem procedimentos extras;
Passo 4 – o Administrador registra e dispara mensagem-resposta para o usuário externo. O sistema registra data e conclui a demanda.>

1.	Requisitos não funcionais 
[RNF001] < Acesso restrito ao Sistema administrativo do site >
< Apenas pessoas autorizadas terão acesso ao sistema. Será necessário ter autenticação através de senha e login. O administrador do sistema e o desenvolvedor tem acesso a todas as funcionalidades do sistema; demais usuários terão acesso apenas aos recursos que lhes cabem no desenvolvimento de suas atividades.>

[RNF002] < Acesso restrito a Comunidade de Projetos >
< - O acesso do participante à área de Projetos é feito através de Login e Senha cadastrados no primeiro acesso;
-Há um Login e Senha de Administrador de uso exclusivo do Administrador de Acesso;
- Os acessos são concedidos vinculados ao Projeto do participante ou convidado. O acesso universal aos projetos só pode ser feito com permissão de Administrador de Acesso.
- O Gerente de Projeto pode cadastrar permissões de acesso diferenciados para os Integrantes da Equipe e Convidados (inserir, editar, deletar, visualizar);
- Mediante login, o participante poderá acessar o site em qualquer local que tenha rede internet, a qualquer horário, durante os 7 dias da semana, inclusive feriados.> 

[RNF003] < Identidade Visual >
< Como referência estética, será utilizado o conceito do site https://www.perestroika.com.br/ - porém, adotando as cores da identidade visual do Projeto Platforma.> 
 


[RNF004] < Linguagem >
< A língua oficial do site será o Português do Brasil. Quesitos de acessibilidade serão implantados a partir do módulo IV do Projeto.>

[RNF005] < Coleta e Uso de Dados >
< Deverá ser assegurado que os dados pessoais sejam coletados e processados de acordo com as disposições da lei em vigor: Lei 12.965 / 2014 (Marco Civil da Internet); Lei 13.853 / 2019 (Lei Geral de Proteção de Dados); MP 959 / 2020 (alterações na LGPD). >


[RNF006] < Prazo para realização do trabalho > 
< Data de entrega: 22/01/2024. A partir desta data, o desenvolvedor passará a se responsabilizar pela manutenção do site.>

[RNF007] < Protótipo > 
< Para efeito de entrega do Projeto Integrador, os textos do protótipo serão fictícios.>

