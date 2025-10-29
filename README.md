### Projeto Final – Braço mecânico.
# ---------------------------------------------------------------------
### Nomes: Ana Mioto, Anthony de Paula, Giovana Generoso, Gulitti Alvez.
# -----------------------------------------------------------------------------------------------------------------------------------------------------------------------------
## O projeto tem como objetivo desenvolver um braço mecânico robusto e acessível, capaz de executar tarefas pesadas e repetitivas em ambientes industriais ou oficinas. Ele foi criado a partir da identificação de problemas comuns em soluções existentes, como baixa capacidade de carga, pouca durabilidade e falta de precisão nos movimentos.
# -----------------------------------------------------------------------------------------------------------------------------------------------------------------------------
## Durante a pesquisa, observou-se que braços robóticos industriais (como os da ABB, FANUC e KUKA) possuem alta eficiência, mas são caros e complexos. Já projetos educacionais e open-source são mais baratos, porém não suportam cargas elevadas nem possuem resistência adequada. Isso revelou uma lacuna no mercado: a necessidade de um braço mecânico modular, resistente e de baixo custo.
# ----------------------------------------------------------------------------------------------------------------------------------------------------------------------------
## A solução proposta utiliza um ESP32 como controlador principal, atuadores potentes (como servos industriais ou servos motores simples para pequenos projetos). nosso projeto ele tem os elementos feitos de materiais de impressão 3d. O sistema do nosso projeto está sendo usado 4 servos motores simples que vão ser comandados pelo esp32 junto de uma placa de driver motor de passa, e uma interface web que permitirá controlar o braço que vai ser a primeira parte para testar se o projeto está funcionando corretamente ele vai ser feito via html no VScode, nossa intenção é programar movimentos e integrar o equipamento a sistemas industriais via Modbus TCP ou OPC UA para essas empresas e para Automação.
# ----------------------------------------------------------------------------------------------------------------------------------------------------------------------------
## A segurança também é prioridade: o braço ele pode ter um botão de emergência (E-STOP), limites de ângulo programáveis e detecção de colisão. O projeto será desenvolvido em fases começando por um protótipo funcional, depois aprimorando controle, sensores e integração industrial, mas como ele ainda vai ser um projeto o nosso foco está sendo na funcionalidade do braço e de suas ações definidas.
# ----------------------------------------------------------------------------------------------------------------------------------------------------------------------------
# Nosso trabalho vai ser feito em Frontend e Mobile, onde o Frontend vai ser a parte mais básica, já a parte do Mobile vamos procurar criar alguns comandos mais elaborados para ser usado de forma mais remota de onde estiver e usar os comandos de uma forma mais simples como por exemplo usar Botões para comandar a direção que o Braço robotico vai se mexer ou apenas definir sua ação.
# --------------------------------------------------------------------------------------------------------------------------------------------------------------------------
# Nosso figma do mobile ja está sendo prototipada e entrando nos estagios intermediarios. Teremos suporte tanto para mobile quanto para web.
# --------------------------------------------------------------------------------------------------------------------------------------------------------------------------
## Ao final, o projeto pretende oferecer uma alternativa econômica e eficiente para pequenas e médias empresas, contribuindo para a democratização da automação industrial e incentivando o uso de tecnologias abertas na Indústria 4.0.
# ------------------------------------------------------------------------------------------------------------------------------
## Fontes: https://autenticaengenharia.com/blog/automacao-industrial-e-robotica-os-robos-kuka-e-fanuc-transformando-sua-fabrica/
# https://new.abb.com/news/pt-br/detail/128456/robotica-inteligente-a-nova-fronteira-da-automacao-industrial

## Função de cada Membro: 
## Mioto - Documentação e ajudante
## Anthony - Documentação e ajudante
## Gulitti - Codigo e Prototipagem
## Giovana - Codigo e Prototipagem
## Espadoni - 