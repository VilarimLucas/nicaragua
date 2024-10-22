# Site - Nicarágua - Feira das Nações 3ºA - Solon Borges dos Reis

Este projeto é uma página web dedicada à Nicarágua, destacando sua cultura, geografia, economia, turismo e música, com integração de áudios e modais para apresentação de conteúdo adicional.

## 🔗 **Funcionalidades**

- **Menu de Navegação:** Permite navegar entre diferentes seções, como *Início*, *Sobre*, *Fotografia*, e mais.
- **Playlist de Música:** Integra uma lista de músicas com controle de reprodução (play/pause).
- **Visualização em Tela Cheia:** Modal para visualizar PDFs e apresentações diretamente na página.
- **Notícias:** Exibe uma seção de artigos com links para notícias relevantes da Nicarágua.
- **Design Responsivo:** Adaptável para diferentes tamanhos de tela utilizando **Bootstrap**.

---

## 📂 **Estrutura de Pastas**

```plaintext
/
├── audio/                     # Arquivos de áudio utilizados na playlist
├── css/                       # Arquivos de estilos CSS personalizados
├── images/                    # Imagens utilizadas no site
├── js/                        # Scripts JS usados na página
├── docs/                      # PDFs e documentos para visualização nos modais
└── index.html                 # Página principal do site
```

## 🛠️ **Tecnologias Utilizadas**

- **HTML5:** Estrutura e marcação do site.
- **CSS3:** Estilos e animações.
- **Bootstrap 4:** Layout responsivo e componentes prontos.
- **JavaScript:** Controle das interações, como modais e playlist.
- **Google Fonts:** Tipografia personalizada (Poppins e Montserrat).
- **Bootstrap Icons:** Ícones para botões e interações.
- **jQuery:** Manipulação de DOM e eventos.

---

## 🎵 **Funcionalidade da Playlist**

A playlist permite que os usuários reproduzam músicas específicas. A lista de músicas é definida dinamicamente e controlada por JavaScript.

### Arquivos de áudio disponíveis:
1. **Hino Nacional da Nicarágua**
2. **Los Chicos de Ayer**

Cada item possui botões **play/pause** que alternam automaticamente entre os estados.

---

## 🖼️ **Visualização de PDFs e Documentos**

O site possui um modal que permite abrir PDFs em tela cheia. Para acessar, basta clicar em qualquer item do menu que contenha a classe `.open-modal`.

---

## 🔧 **Como Executar o Projeto Localmente**

1. Clone este repositório:
```bash
   git clone https://github.com/VilarimLucas/nicaragua.git
   ```

