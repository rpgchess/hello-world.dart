# Hello World - Flutter

Um projeto Flutter básico demonstrando a estrutura inicial de uma aplicação Flutter com um contador simples.

## 📋 Descrição

Este é um projeto de demonstração Flutter que implementa o template padrão de contador. A aplicação exibe um número que incrementa cada vez que o botão flutuante é pressionado, demonstrando conceitos básicos de gerenciamento de estado no Flutter.

## 🚀 Tecnologias

- **Flutter SDK** >= 2.19.4 < 3.0.0
- **Dart**
- Cupertino Icons ^1.0.2

## 📱 Plataformas Suportadas

- ✅ Android
- ✅ iOS
- ✅ Web
- ✅ Windows
- ✅ Linux
- ✅ macOS

## 🔧 Instalação e Execução

### Pré-requisitos

- **Flutter SDK** instalado ([Guia de instalação](https://docs.flutter.dev/get-started/install))
- **Editor de código** (VS Code com extensão Flutter, Android Studio, ou IntelliJ)
- Para desenvolvimento mobile:
  - **Android Studio** com Android SDK (para Android)
  - **Xcode** (para iOS - apenas macOS)

### Verificar Instalação

```bash
# Verificar se Flutter está instalado corretamente
flutter doctor

# Ver dispositivos disponíveis
flutter devices
```

### Passos de Instalação

1. **Clone o repositório**
   ```bash
   git clone <repository-url>
   cd hello-world.dart
   ```

2. **Instale as dependências**
   ```bash
   flutter pub get
   ```

3. **Execute o aplicativo**
   
   ```bash
   # No dispositivo/emulador conectado
   flutter run
   
   # Especificar plataforma
   flutter run -d chrome        # Web (Chrome)
   flutter run -d windows       # Windows desktop
   flutter run -d macos         # macOS desktop
   flutter run -d linux         # Linux desktop
   flutter run -d android       # Android
   flutter run -d ios           # iOS
   ```

### Build para Produção

```bash
# Android APK
flutter build apk --release

# Android App Bundle (recomendado para Play Store)
flutter build appbundle --release

# iOS
flutter build ios --release

# Web
flutter build web --release

# Windows
flutter build windows --release

# macOS
flutter build macos --release

# Linux
flutter build linux --release
```

## 📚 Recursos Úteis

- [Lab: Write your first Flutter app](https://docs.flutter.dev/get-started/codelab)
- [Cookbook: Useful Flutter samples](https://docs.flutter.dev/cookbook)
- [Documentação oficial do Flutter](https://docs.flutter.dev/)
- [Flutter packages](https://pub.dev/)
- [Dart language tour](https://dart.dev/guides/language/language-tour)

## 🏗️ Estrutura do Projeto

```
hello-world.dart/
├── android/              # Código específico Android
├── ios/                  # Código específico iOS
├── web/                  # Código específico Web
├── windows/              # Código específico Windows
├── linux/                # Código específico Linux
├── macos/                # Código específico macOS
├── lib/
│   └── main.dart        # Código principal da aplicação
├── test/                 # Testes unitários
├── pubspec.yaml         # Dependências e configuração
├── analysis_options.yaml # Regras de análise de código
└── README.md
```

## 💡 Conceitos Demonstrados

Este projeto simples demonstra:

- **StatefulWidget**: Widget com estado mutável
- **setState()**: Atualização de estado e re-renderização
- **Material Design**: Widgets seguindo Material Design
- **Scaffold**: Estrutura básica de uma página
- **AppBar**: Barra superior da aplicação
- **FloatingActionButton**: Botão flutuante de ação
- **Column & Center**: Layout widgets
- **Text & Theme**: Estilização de texto

## 🔧 Comandos Úteis

```bash
# Analisar código (linting)
flutter analyze

# Formatar código
flutter format lib/

# Executar testes
flutter test

# Limpar build cache
flutter clean

# Atualizar dependências
flutter pub upgrade

# Ver informações do projeto
flutter pub deps

# Hot reload (durante execução)
# Pressione 'r' no terminal

# Hot restart (durante execução)
# Pressione 'R' no terminal
```

## ⚙️ Melhorias Implementadas

### ✅ Configuração
- **EditorConfig** adicionado para encoding UTF-8
- Indentação consistente (2 espaços para Dart/YAML)
- Line endings Unix (LF) configurados

### ✅ Documentação
- README expandido com múltiplas plataformas
- Comandos de build para todas as plataformas
- Estrutura do projeto documentada
- Conceitos Flutter explicados
- Comandos úteis listados

### 🚀 Próximas Melhorias Sugeridas

- [ ] Adicionar navegação entre telas (routing)
- [ ] Implementar gerenciamento de estado (Provider, Riverpod, BLoC)
- [ ] Adicionar testes unitários e de widget
- [ ] Integração com API REST
- [ ] Persistência local (SharedPreferences, SQLite)
- [ ] Tema escuro/claro
- [ ] Internacionalização (i18n)
- [ ] Animações e transições
- [ ] CI/CD para builds automatizados

## 🎯 Desenvolvimento

### Hot Reload vs Hot Restart

- **Hot Reload (r)**: Atualiza mudanças no código mantendo o estado
- **Hot Restart (R)**: Reinicia a aplicação do zero

### Debugging

```bash
# Executar em modo debug
flutter run

# Executar em modo profile (performance)
flutter run --profile

# Executar em modo release
flutter run --release

# Habilitar DevTools
flutter pub global activate devtools
flutter pub global run devtools
```

## 👤 Autor

Claudio Almeida Martins

## 📄 Licença

Projeto educacional/demonstrativo

---

> **Dica**: Use `flutter create --help` para ver todas as opções ao criar novos projetos Flutter.
