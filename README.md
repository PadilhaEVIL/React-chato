Resumo da Aula
Estrutura Inicial
O aplicativo é constituído por componentes fundamentais, incluindo App.jsx, Header.jsx, Footer.jsx, Home.jsx, Destinos.jsx e Contato.jsx, além de elementos específicos para destinos, como Destino.jsx e FormDestino.jsx. O gerenciamento de estado é implementado utilizando useState para monitorar a página atual e a lista de destinos. Na página inicial, o usuário tem a opção de navegar entre as seções Home, Destinos e Contato.

Regras de Negócio
Distância Calculada a partir do Brasil: Todos os cálculos de distância começam a partir do Brasil.
Destinos Pré-Cadastrados: Existem 10 destinos já cadastrados, cada um com uma distância específica.
Custos de Voo Baseados na Distância:
Até 2000 km: Um voo ao custo de R$ 1.500,00.
Acima de 2000 km: Dois voos, totalizando R$ 3.000,00, mais um adicional de R$ 1,00 por km além dos 2000.
Custos Variáveis pela Data da Viagem:
Menos de 2 meses de antecedência: R$ 1.500,00.
Com 2 meses ou mais de antecedência: R$ 700,00.
Opções de Estadia:
Padrão: R$ 400,00 por semana.
Luxo: R$ 700,00 por semana, com um adicional de 25% por cada participante extra.
Cálculo de Distância e Custos
Os cálculos são baseados nas distâncias pré-definidas (considerando que os voos partem do Brasil), na data de ida e volta, no tipo de acomodação escolhido e no número de participantes. Essas avaliações são guiadas pelas regras de negócio descritas acima. O subtotal dos custos é apresentado em tempo real enquanto o usuário ajusta suas preferências de viagem.

Interface de Seleção e Exibição do Subtotal
Os usuários têm a capacidade de escolher o destino, as datas de viagem, o tipo de hospedagem e o número de participantes, com o subtotal sendo atualizado imediatamente. Após a seleção, os usuários são direcionados para a tela de pagamento, onde podem escolher entre PIX ou cartão de crédito.

Sugestões e Melhorias
Adicionar sugestões de destinos aos usuários.
Incluir um filtro de busca por preço para os destinos.
