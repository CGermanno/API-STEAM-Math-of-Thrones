# Math of Thrones

> **Status:** projeto em desenvolvimento.

Projeto criado com Flutter para estudar desenvolvimento multiplataforma. A proposta é evoluir a aplicação para um jogo de cálculos matemáticos e praticar a criação de APIs próprias e o consumo de APIs de terceiros.

## Estado atual

O repositório ainda está na etapa inicial. A aplicação possui a estrutura gerada pelo Flutter e uma tela de exemplo com um contador.

O jogo matemático e as integrações com APIs ainda não foram implementados. Esta documentação deverá ser atualizada conforme essas funcionalidades forem adicionadas.

## Tecnologias

- Flutter;
- Dart 3.10.4 ou versão compatível;
- Material Design;
- Flutter Test;
- Flutter Lints.

## Requisitos

Antes de executar o projeto, tenha instalado:

- [Git](https://git-scm.com/);
- [Flutter SDK](https://docs.flutter.dev/get-started/install);
- um dispositivo, emulador ou navegador configurado para executar aplicações Flutter.

Use o comando abaixo para verificar a configuração do ambiente:

```bash
flutter doctor
```

## Como executar

Clone o repositório:

```bash
git clone https://github.com/CGermanno/API-STEAM-Math-of-Thrones.git
```

Entre na pasta do projeto:

```bash
cd API-STEAM-Math-of-Thrones
```

Instale as dependências:

```bash
flutter pub get
```

Execute a aplicação:

```bash
flutter run
```

## Verificações

Execute a análise estática do código:

```bash
flutter analyze
```

Execute os testes automatizados:

```bash
flutter test
```

## Estrutura principal

```text
lib/
└── main.dart              # Ponto de entrada da aplicação

test/
└── widget_test.dart       # Teste de widget do exemplo inicial

android/                   # Configuração para Android
linux/                     # Configuração para Linux
web/                       # Configuração para Web
windows/                   # Configuração para Windows

pubspec.yaml               # Dependências e configurações do projeto
```

## Próximos passos

- definir as regras do jogo matemático;
- substituir a tela de contador pela interface do jogo;
- definir quais APIs serão criadas ou consumidas;
- organizar o código em modelos, serviços e componentes visuais;
- adicionar testes para as regras e funcionalidades implementadas.

## Contribuições

Sugestões e melhorias podem ser registradas na área de [issues](https://github.com/CGermanno/API-STEAM-Math-of-Thrones/issues). Antes de iniciar uma alteração, verifique se já existe uma issue relacionada ao assunto.
