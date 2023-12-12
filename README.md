# Resumo da aplicação

Este pequeno projeto faz parte da avaliação da Sprint de Qualidade de Software, Segurança e Sistemas inteligentes.

Teve por objetivo realizar o treinamento de um modelo de machine learn para um problema de classificação. Neste trabalho, foi escolhido o dataset de passageiros do navio Titanic, a fim de realizar a predição de sobrevivência à tragédia.
Após a construção do modelo no Google Colab, o mesmo foi embarcado no backend. O usuário, assim, poderá realizar as predições
por meio do preenchimento dos campos disponíveis na aplicação frontend, devendo atentar para que todos os campos sejam preenchidos. Criou-se, ainda, um teste automatizado, utiizando-se o Pytest, visando verificar se o modelo criado irá atender aos requisitos de desempenho definidos.

Obs1: Ao preencher as informações dos campos referentes ao Porto de Embarque, escolher 'SIM' para apenas uma opção, devendo as demais serem selecionadas como 'NÃO'.

Obs2: Caso o valor retornado na coluna "Verificar" for igual a 0, significa que o passageiro não sobreviveu. Retornando o valor 1,
o passageiro terá sobrevivido.
