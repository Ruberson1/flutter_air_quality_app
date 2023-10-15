# Medidor de Qualidade do Ar

O **Medidor de Qualidade do Ar** é um aplicativo simples desenvolvido em Dart/Flutter que permite aos usuários monitorar a qualidade do ar em sua localização atual. Ele se comunica com uma API para obter dados em tempo real sobre a qualidade do ar e exibe essas informações de forma visualmente atraente na tela.

## Funcionalidades

O aplicativo oferece as seguintes funcionalidades:

- **Medição de Qualidade do Ar**: Exibe um medidor na tela que representa a qualidade do ar em uma escala visual.
- **Mensagem Descritiva**: Apresenta uma mensagem de texto que descreve a qualidade do ar, ajudando o usuário a entender o significado da medição.
- **Emoji Indicativo**: Mostra um emoji correspondente à qualidade do ar, tornando a informação ainda mais acessível e amigável.

## Uso

1. Antes de usar o aplicativo, é necessário acessar [este link](https://aqicn.org/api/) para obter uma API key.
2. Após obter a API key, adicione-a ao arquivo `api_key.dart` no projeto da seguinte maneira:

```dart
// api_key.dart

  static const String API_KEY = 'SUA_API_KEY_AQUI';

```

Certifique-se de substituir `'SUA_API_KEY_AQUI'` pela API key que você obteve.

3. Ao abrir o aplicativo, o medidor de qualidade do ar é exibido na tela.
4. Os dados são obtidos automaticamente da API e o medidor se ajusta de acordo com a qualidade atual.
5. Uma mensagem descritiva e um emoji são exibidos para fornecer informações adicionais sobre a qualidade do ar.
6. Os usuários podem atualizar manualmente os dados tocando em um botão "Atualizar" ou permitir atualizações automáticas em intervalos definidos nas configurações.

## Tecnologias Utilizadas

- **Dart**: A linguagem de programação usada para o desenvolvimento do aplicativo.
- **Flutter**: O framework de código aberto para criar interfaces de usuário que permite criar aplicativos multiplataforma nativos.
- **API de Qualidade do Ar**: O aplicativo se comunica com uma API externa para obter dados em tempo real sobre a qualidade do ar na localização atual do usuário.

## Configuração

Antes de usar o aplicativo, é necessário configurar a API de qualidade do ar conforme descrito acima.

## Contribuição

Se você deseja contribuir para o desenvolvimento deste aplicativo, fique à vontade para criar pull requests ou relatar problemas (issues) no repositório do projeto no GitHub.
