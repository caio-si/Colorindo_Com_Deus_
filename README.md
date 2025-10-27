# 🎨 Colorindo com Deus

Um aplicativo mobile educativo e interativo de colorir com histórias bíblicas para crianças de 4 a 10 anos.


<img width="447" height="880" alt="Tela 1" src="https://github.com/user-attachments/assets/98adf738-8dbd-4352-ab30-9b0b637c5dd6" />
<img width="451" height="841" alt="Tela 5" src="https://github.com/user-attachments/assets/5f9c0b83-902c-4e71-85e2-d7564fc92020" />
<img width="448" height="877" alt="Tela 4" src="https://github.com/user-attachments/assets/0b46f61a-76d5-4814-afc2-decf970aeca3" />
<img width="453" height="837" alt="Tela 3" src="https://github.com/user-attachments/assets/084747f0-d6ee-45b3-9e5c-df6849ba5952" />
<img width="444" height="878" alt="Tela 2" src="https://github.com/user-attachments/assets/593c12c0-304a-4a88-9f5d-d71d29493687" />


## 📱 Sobre o Projeto

**Colorindo com Deus** é um aplicativo desenvolvido em Flutter que proporciona uma experiência lúdica e educativa para crianças, permitindo que aprendam passagens bíblicas enquanto se divertem colorindo cenas e personagens da Bíblia.

## ✨ Características Principais

### 🎯 Funcionalidades

- **Livro de Colorir Interativo**: Toque para colorir áreas específicas dos desenhos
- **Histórias Bíblicas**: 10 histórias bíblicas ilustradas com textos adaptados para crianças
- **Paleta de Cores**: 16 cores vibrantes para escolher
- **Controles de Edição**: Desfazer, refazer e apagar cores
- **Galeria Pessoal**: Salve e visualize seus desenhos finalizados
- **Sistema de Recompensas**: Ganhe versículos de prêmio ao completar desenhos
- **Multi-idioma**: Suporte para Português, Inglês e Espanhol
- **Modo Escuro**: Interface adaptável para diferentes momentos do dia
- **Modo Infantil**: Bloqueio parental para maior segurança

### 📖 Histórias Disponíveis

1. A Criação do Mundo (Gênesis 1-2)
2. Noé e a Arca (Gênesis 6-9)
3. Davi e Golias (1 Samuel 17)
4. Jonas e o Grande Peixe (Jonas 1-4)
5. Daniel na Cova dos Leões (Daniel 6)
6. O Nascimento de Jesus (Lucas 2)
7. Jesus Acalma a Tempestade (Marcos 4:35-41)
8. A Multiplicação dos Pães e Peixes (João 6:1-14)
9. O Bom Samaritano (Lucas 10:25-37)
10. Zaqueu na Árvore (Lucas 19:1-10)

## 🛠️ Tecnologias Utilizadas

- **Flutter**: Framework principal para desenvolvimento multiplataforma
- **Provider**: Gerenciamento de estado
- **Hive**: Banco de dados local para persistência
- **SharedPreferences**: Armazenamento de configurações
- **Flutter SVG**: Renderização de imagens vetoriais
- **Intl**: Internacionalização

## 📂 Estrutura do Projeto

```
lib/
├── main.dart                 # Ponto de entrada do aplicativo
├── models/                   # Modelos de dados
│   ├── desenho.dart
│   ├── historia.dart
│   ├── medalha.dart
│   └── progresso_usuario.dart
├── providers/                # Gerenciamento de estado
│   ├── drawing_provider.dart
│   ├── gallery_provider.dart
│   ├── settings_provider.dart
│   └── theme_provider.dart
├── screens/                  # Telas do aplicativo
│   ├── home_screen.dart
│   ├── drawings_selection_screen.dart
│   ├── coloring_screen.dart
│   ├── stories_screen.dart
│   ├── gallery_screen.dart
│   ├── settings_screen.dart
│   └── about_screen.dart
├── widgets/                  # Componentes reutilizáveis
│   ├── animated_button.dart
│   ├── color_palette_widget.dart
│   └── drawing_canvas.dart
├── data/                     # Dados estáticos
│   ├── desenhos_data.dart
│   └── historias_data.dart
├── l10n/                     # Internacionalização
│   └── app_localizations.dart
└── utils/                    # Utilitários
    └── app_colors.dart
```

## 🚀 Como Executar

### Pré-requisitos

- Flutter SDK (>=3.0.0)
- Android Studio / Xcode
- Dispositivo físico ou emulador

### Instalação

1. Clone o repositório:
```bash
git clone [url-do-repositorio]
cd colorindo_com_deus
```

2. Instale as dependências:
```bash
flutter pub get
```

3. Execute o aplicativo:
```bash
flutter run
```

## 🎨 Design

O aplicativo foi projetado com foco em:

- **Interface Infantil**: Ícones grandes, cores suaves e fontes arredondadas
- **Animações Sutis**: Transições suaves e feedback visual
- **Acessibilidade**: Fácil navegação para crianças
- **Responsividade**: Adaptável a diferentes tamanhos de tela

### Paleta de Cores

- **Primária**: #6C63FF (Roxo)
- **Secundária**: #FF6584 (Rosa)
- **Destaque**: #FFD93D (Amarelo)
- **Fundo**: #F8F9FF (Azul Claro)

## 📱 Capturas de Tela

_Em breve: adicionar screenshots das principais telas_

## 🔐 Segurança e Privacidade

- Armazenamento local (funciona offline)
- Modo infantil com bloqueio parental
- Sem coleta de dados pessoais
- Sem anúncios ou compras dentro do app

## 🌍 Internacionalização

Idiomas suportados:
- 🇧🇷 Português (Brasil)
- 🇺🇸 English (United States)
- 🇪🇸 Español (España)

## 🤝 Contribuindo

Contribuições são bem-vindas! Por favor:

1. Faça um Fork do projeto
2. Crie uma branch para sua feature (`git checkout -b feature/MinhaFeature`)
3. Commit suas mudanças (`git commit -m 'Adiciona MinhaFeature'`)
4. Push para a branch (`git push origin feature/MinhaFeature`)
5. Abra um Pull Request

## 📄 Licença

Este projeto está sob a licença MIT. Veja o arquivo [LICENSE](LICENSE) para mais detalhes.

## 👥 Créditos

- **Desenvolvimento**: Caio da Silva Figueredo
- **Conteúdo Bíblico**: Adaptado da Bíblia Sagrada
- **Framework**: Flutter by Google

## 🙏 Versículo de Inspiração

> "Deixai vir a mim as criancinhas e não as impeçais, porque o Reino de Deus pertence aos que são semelhantes a elas."
> 
> **Marcos 10:14**

---

Desenvolvido com ❤️ e fé para ensinar as crianças sobre o amor de Deus.

