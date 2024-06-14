
# TinderCat

TinderCat é um aplicativo de demonstração desenvolvido em Swift utilizando UIKit. Ele permite que os usuários deslizem para "curtir" gatos, vejam perfis detalhados dos gatos, e mantenham uma lista dos gatos curtidos.


https://github.com/FelipeAngeli/TinderCat/assets/59125006/2dd17beb-0bda-418d-96da-1e9755b0ec9d




## Funcionalidades

- Deslizar para curtir gatos
- Exibir perfil detalhado dos gatos
- Lista de gatos curtidos
- Confirmação de remoção de gatos curtidos da lista
- Regra especial de "like" a cada três gatos curtidos

## Estrutura do Projeto

O projeto segue a arquitetura MVVM (Model-View-ViewModel) para organizar o código de maneira limpa e modular.

## Instalação

Para clonar e executar este projeto, você precisará do [Git](https://git-scm.com) e do [Xcode](https://developer.apple.com/xcode/) instalados no seu computador.

### Passos

1. Clone este repositório:
   ```sh
   git clone https://github.com/seu_usuario/TinderCat.git
   ```
2. Abra o projeto no Xcode:
   ```sh
   open TinderCat.xcodeproj
   ```
3. Instale as dependências (se houver).
4. Execute o projeto no simulador ou em um dispositivo.

## Uso

1. Abra o aplicativo.
2. Na tela inicial (Home), deslize para a direita para curtir os gatos.
3. Após curtir três gatos, uma página especial será exibida mostrando os gatos curtidos.
4. Acesse a aba "Likes" para ver a lista de gatos curtidos.
5. No perfil do gato, clique em "Like" para curtir o gato ou em "Edit" para editar o perfil (função placeholder).
6. Na lista de "Likes", deslize para a esquerda para remover um gato. Um alerta de confirmação será exibido.

## Lógica de Like Especial

A cada três gatos curtidos, uma página especial é exibida mostrando os gatos curtidos.

## Arquitetura

O projeto é estruturado utilizando a arquitetura MVVM (Model-View-ViewModel), que ajuda a separar a lógica de negócios da lógica de apresentação.

## Licença

Este projeto está licenciado sob os termos da licença MIT. Veja o arquivo [LICENSE](LICENSE) para mais detalhes.
