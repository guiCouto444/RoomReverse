
|## 1. Introdução

### 1.1. Propósito do Documento de Requisitos
Essa documentação tem como o objetivo simplificar e otimizar o processo de reserva de acomodações para os hospede, proporcionando uma experiência de reserva eficiente e conveniente. Este trabalho de desenvolvimento de software visa cria uma plataforma intuitiva e acessível, que permita aos usuários pesquisar, verificar disponibilidade, selecionar e reserva quartos de hotel de forma fácil e segura.

O site(Software) consta, informações sobre o produto e suas funções detalhadas sobre sua interface e seu funcionamento em seu comportamento.

### 1.2. Público Alvo
 O público alvo pode incluir Agencia de viagens, organizadores de eventos, turistas, proprietário de hotel e empreendedores.

### 1.3. 



## 2. Descrição Geral do Produto

### 2.1. Situação Atual
O software de reservas de hotel vem sofrendo com problemas de abandono durante o processo de reservas online. Estudos indicam que, a cada campo de formulário desnecessário, a taxa de abandono pode aumentar em 10%. Um dos principais problemas é a interface do site quando estão completando os dados, que não é intuitiva e tem alguns problemas como excesso de requisitos para a inscrição ou dificuldades na hora de inserir os dados para a reserva. Dessa forma, a dificuldade na usabilidade do usuário atrapalha a experiência com o software. Esse projeto busca especificamente à criação de uma interface eficiente e prática.

A empresa Booking, que é uma empresa internacional especializada em reserva de hotéis online ao redor do mundo já vêm apresentando obstáculos como, a necessidade da aprovação prévia de outra pessoa este é um problema que podemos solucionar dando mais autonomia ao software, fazendo com que ele leva essas informações de uma forma mais precisa ao gerente (ou o responsável) por monitorar as reservas do hotel. O site possui um longo processo de reservas online, fazendo - os viajantes irem embora sem completá-lo. Além disso, falta opções de pagamento como o cartão de crédito, pix, pic pay, boletos e etc. 

### 2.2. Objetivos do Produto
O principal objetivo proporcionar uma experiência de reserva de quartos de hotel altamente eficiente e segura para os usuários. Com a funcionalidade de disponibilidade de quartos em horários específicos, os clientes podem visualizar instantaneamente quais quartos estão disponíveis, permitindo uma reserva rápida e conveniente. Além disso, oferecemos a possibilidade de os usuários personalizarem suas preferências de quarto, incluindo comodidades, tipo de cama e vista, para uma experiência verdadeiramente individualizada e satisfatória.

Priorizamos a segurança dos dados pessoais e detalhes de pagamento dos nossos clientes, implementando criptografia avançada e medidas anti-fraude para garantir total confidencialidade e proteção contra qualquer ameaça cibernética. Com uma capacidade robusta para lidar com um grande volume de reservas simultâneas, asseguramos um tempo de resposta rápido para consultas e processamento de reservas, garantindo a satisfação do cliente mesmo nos momentos de pico de demanda.

Nossa disponibilidade 24/7 é garantida por meio de um plano de contingência abrangente, que nos permite lidar com falhas de forma eficiente, garantindo a continuidade do serviço sem interrupções. Além disso, nossa plataforma é altamente escalável, capaz de lidar com aumentos repentinos no tráfego de reservas e integrar-se facilmente com sistemas de terceiros, garantindo uma experiência perfeita para nossos clientes.

Com uma interface intuitiva e acessível em diferentes dispositivos, buscamos proporcionar uma experiência amigável tanto para os clientes que fazem as reservas quanto para a equipe de gestão. Priorizamos a confiabilidade do nosso sistema, garantindo a robustez, ausência de erros e realização de backups regulares dos dados para evitar qualquer perda de informações importantes. Além disso, nossa plataforma é compatível com diversos navegadores, sistemas operacionais, idiomas e moedas, visando atender a uma base global de clientes.


### 2.3. Benefícios do Projeto

O software consiste na criação de um sistema que visa agilizar e otimizar o processo de reserva de quartos de hotel para ambos os clientesa equipe de gestão . O sistema busca aumentar a satisfação do cliente, melhorar a eficiência operacional e melhorar a gestão dos recursos do hotel.

Reservas Facilitadas
Controle de Disponibilidade 
Regulando Tarifas e Promoções
Eficiência na 
Gestão de Pagamentos de Check-in e Check-out
Interação com Clientes
Relacionamentos e Análise

### 2.4. Escopo

### 2.5. Atores
1. *Motor de Reservas Online*: Este ator virtual permite que os clientes façam reservas diretamente no site do hotel, verificando a disponibilidade de quartos, preços e ofertas especiais, sem a necessidade de interação humana.

2. *Chatbot de Atendimento ao Cliente*: Um chatbot integrado ao site ou ao aplicativo do hotel que fornece assistência automatizada aos hóspedes, respondendo a perguntas comuns, ajudando na reserva de quartos e fornecendo informações sobre as instalações e serviços.

3. *Sistema de Gerenciamento de E-mails*: Responsável por enviar e-mails automáticos para confirmar reservas, enviar recibos de pagamento, solicitar feedback pós-estadia e oferecer promoções personalizadas aos clientes com base em seu histórico de reservas.

4. Administrador do Sistema*: Responsável por configurar e manter o software, gerenciar usuários e permissões, realizar backups e garantir a segurança do sistema.

5. *Sistema de Análise de Dados*: Coleta e analisa dados sobre reservas, ocupação, taxas de cancelamento, preferências dos hóspedes e outras métricas importantes, fornecendo insights valiosos para a tomada de decisões estratégicas e o aprimoramento da experiência do cliente.

6. *Sistema de Pagamento Online*: Integração com provedores de pagamento para facilitar transações seguras e convenientes, permitindo que os hóspedes paguem por reservas, serviços adicionais e taxas de estadia online, sem a necessidade de contato físico.

### 2.6. Premissas


### 2.7. Itens fora do escopo

- Desenvolvimento de funcionalidades específicas, como funcionalidade X ou módulo Y, que não estão relacionadas à reserva de quartos de hotel.
- Desenvolvimento de interface com sistemas legados da empresa que não estão diretamente ligados à funcionalidade principal do software.
- Desenvolvimento do sistema em idiomas diferentes do português, já que o foco é atender principalmente clientes de língua portuguesa.
- Garantia com relação a problemas advindos de mudanças de regras de negócio, ambiente, linguagem, versões ou banco de dados, que estão além do escopo do projeto.
- Testes específicos, como desempenho, carga e estresse, que não são diretamente relacionados à reserva de quartos de hotel.
- Atendimento de solicitações por equipamentos que são enviadas na mesma solicitação por sala, pois não faz parte do escopo deste projeto.
- Pesquisa por corredor e andar, pois este conceito pode não ser relevante ou existir em todas as unidades de hotel.
- Tratamento diferenciado da Unidade de Belo Horizonte no agendamento e localização das salas, já que isso não está dentro do escopo deste projeto e não se aplica a todas as unidades




### 3.1 


| ID   |DESCRISÃO  |
| ---------------- | ----------|
| REF 1  | O funcionário deve estar autenticado no sistema com as devidas credenciais e permissões, garantindo que apenas pessoal autorizado possa acessar a funcionalidade de reserva de quartos. |
| REF 2  | O funcionário deve ter acesso à lista de quartos disponíveis e suas informações para poder fazer escolhas informadas durante o processo de reserva em nome dos clientes.| 
| REF 3 | O usuário acessa a funcionalidade de reserva de quartos de hotel no sistema. |



 ### 3.4. Restrições de Hardware
 
|n | Descrição|
|---------|---------|
|1 | Só podem ser realizadas 150 reservas ao mesmo tempo|
|2 | Somente funcionários autorizados podem acessar as informações sensíveis dos hóspedes|
|3 | Só hóteis da franquia poderão ser reservados|
|4 | Em situações de alto fluxo de reservas , o sistema precisa apresentar atualizações|
|5 | O sofwtare em forma de aplicativo só podera ser utilizado por android e IOS|
|6 | O software em forma  web funcionara em qualquer navegador|

### 3.5. Restrições de software
|n | Descrição|
|-----|-----|
| 1| Segurança de dados: Deve garantir a segurança dos dados pessoais e financeiros dos usuários.|
| 2|Disponibilidade do sistema: Deve estar disponível 24 horas por dia, 7 dias por semana, para que os usuários possam fazer reservas a qualquer momento.|
| 3| Interface amigável: Deve ser fácil de usar, mesmo para usuários não técnicos, para facilitar o processo de reserva.|
| 4| Integração com sistemas de pagamento: Deve integrar-se perfeitamente com sistemas de pagamento online para processar transações com segurança.|
| 5| Atualização em tempo real: Deve atualizar em tempo real a disponibilidade de quartos e preços para evitar reservas duplicadas ou conflitos de reserva. |
| 6|Compatibilidade com dispositivos: Deve ser compatível com uma variedade de dispositivos, como computadores, tablets e smartphones, para atender às preferências dos usuários.|
| 7  |Suporte ao cliente: Deve oferecer suporte ao cliente eficiente e rápido, seja por meio de chat ao vivo, e-mail ou telefone, para lidar com problemas ou dúvidas dos usuários.| | 8|Gerenciamento de estoque: Deve controlar com precisão o estoque de quartos disponíveis e impedir reservas além da capacidade do hotel.|
| 9|Política de cancelamento: Deve incluir uma política clara de cancelamento e reembolso para garantir a satisfação do cliente e evitar disputas.|
| 10| Conformidade regulatória: Deve cumprir todas as regulamentações e leis locais e internacionais relacionadas à reserva de hotéis e proteção de dados.|

