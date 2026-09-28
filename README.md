# SmartBites

## Descrição

O SmartBites é um sistema que funciona como uma despensa digital, permitindo que o usuário cadastre e acompanhe os alimentos que possui em casa. O sistema possibilita o controle das quantidades, categorias, locais de armazenamento e datas de validade dos produtos, além de informar sobre alimentos próximos do vencimento. O projeto tem como objetivo auxiliar no controle dos alimentos disponíveis e contribuir para a redução do desperdício, facilitando a organização da despensa e o acompanhamento dos produtos cadastrados.

## Banco de dados

O banco de dados do SmartBites funciona armazenando as informações dos usuários, produtos, receitas e movimentações dos alimentos.

As principais entidades do banco são:

* **Usuário:** armazena os dados Nome, Email e senha do usuário.
* **Produto:** contém as informações dos alimentos cadastrados, como nome e categoria.
* **Notificação:** registra os avisos relacionados aos produtos, como alimentos próximos do vencimento.
* **Receita:** armazena as receitas disponíveis no sistema e seus ingredientes.
* **Movimentação:** registra alterações realizadas nos alimentos, como consumo e descarte.

## Comandos necessários

* npx expo install expo-font expo-modules-core

* npx expo install react-native-web react-dom @expo/metro-runtime (para rodar web)
