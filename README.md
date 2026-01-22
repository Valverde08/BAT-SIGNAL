

🦇 Bat Signal App
Este projeto é uma aplicação móvel desenvolvida com React Native e Expo

O objetivo é criar uma interface interativa que simula o acionamento do "Bat Sinal", alternando entre uma tela de apresentação e um formulário de cadastro de emergência.

📱 Telas e Funcionalidades
O aplicativo conta com uma lógica de renderização condicional para alternar entre dois estados principais:

1. Tela Inicial (Home) 

A tela de boas-vindas apresenta:

Logo do Batman: Uma imagem destacada centralizada.


Botão de Ativação: Um botão estilizado com o texto "Activate Bat Signal".


Ação: Ao clicar neste botão, a interface muda para o formulário.

2. Formulário de Chamado 

Após a ativação, a tela exibe um formulário para coleta de dados. Os campos sugeridos para preenchimento incluem:

Nome

Telefone para contato

Localização atual

Observação (Campo de texto multiline/textarea)


Botão de Envio: Um botão "Enviar" para processar os dados.

🛠 Tecnologias Utilizadas
React Native (Framework principal)

Expo (Ferramenta de build e execução)

React Hooks (useState para controle da renderização condicional entre as views)

StyleSheet (Estilização dos componentes)

🚀 Como rodar o projeto
Pré-requisitos: Tenha o Node.js instalado.

Clone o repositório

Bash
git clone https://github.com/SEU-USUARIO/NOME-DO-REPO.git
cd NOME-DO-REPO
Instale as dependências

Bash
npm install
# ou
yarn install
Execute o projeto

Bash
npx expo start
Teste no dispositivo

Baixe o aplicativo Expo Go no seu celular (Android ou iOS).

Escaneie o QR Code gerado no terminal.

🎨 Layout e Estilização
O layout foi construído seguindo os requisitos visuais do desafio:

Uso de TextInput customizado para os campos do formulário (com suporte a hints e labels).

Botões com feedback visual e dimensões responsivas.

Logotipo adaptado para versões grandes (Tela 1) e versões menores ou ocultas (Tela 2), conforme a necessidade de espaço.

📝 Sobre o Desafio
Este projeto foi desenvolvido para praticar conceitos fundamentais do React Native, incluindo:

Criação de Componentes Funcionais.

Manipulação de Estados (useState).

Estilização com Flexbox.

Renderização Condicional (Ternary Operator).

Made with 🦇 by @Valverde08
