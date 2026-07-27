# 📊 Multi Progress ProITEC (`mod_multiprogress`)

O **Multi Progress ProITEC** é um módulo de atividade para o Moodle desenvolvido para proporcionar aos estudantes uma visualização clara, moderna e consolidada do seu progresso individual nas diversas trilhas de conhecimento do curso ProITEC do IFRN.

---

## 🌐 Documentação Interativa HTML (`docs/`)

Acesse a documentação técnica rica completa em HTML com imagens das pedras de progresso e detalhamento das 4 trilhas:
👉 [**Documentação Técnica em HTML (`docs/index.html`)**](docs/index.html)

---

## 🚀 Funcionalidades

- **Barras de Progresso por Trilha**: Acompanhamento dinâmico do percentual de conclusão em cada uma das 4 disciplinas da oferta:
  - 📐 **Matemática** (`FIC.1196`)
  - ✍️ **Língua Portuguesa** (`FIC.1195`)
  - 🤝 **Ética e Cidadania** (`FIC.1197`)
  - 🎓 **Seminário de Integração** (`FIC.1198`)
- **Visualização Integrada de Pedras/Gemas**: Mostra graficamente a evolução do aluno rumo à conclusão da chave do Codex.
- **Substituto do Bloco Legado**: Projetado como módulo de atividade nativo para substituir o antigo `block_multiprogress`.

---

## 🎨 Recursos Visuais (`pix/`)

- `pedras.png`: Ilustração composta das pedras fundamentais de progresso.
- `livro.png`: Ícone ilustrativo da atividade.
- `monologo.svg`: Marca visual do módulo.

---

## 📥 Instalação

### Opção 1: Via Interface de Administração do Moodle
1. Baixe o arquivo `.zip` da release do módulo.
2. Acesse **Administração do site → Plugins → Instalar plugins** no Moodle.
3. Faça o upload do arquivo `.zip` e conclua a instalação.

### Opção 2: Instalação Manual
1. Clone o repositório no diretório `mod/multiprogress` da sua instalação Moodle:
   ```bash
   cd /caminho/do/seu/moodle/mod
   git clone git@github.com:proitec-moodle-suite/moodle-mod_multiprogress.git multiprogress
   ```
2. Acesse **Administração do site → Notificações** para concluir a atualização no banco de dados.

---

## 👥 Autores e Contribuidores

- **Kelson da Costa Medeiros** (<kelson.medeiros@ifrn.edu.br> / <kelsoncm@gmail.com>)
- **Daniel Berg Lopes Campelo de Morais** (<danielbergmorais@gmail.com>)
- **Matheus Mathias Rocha Lúcio de Moraes** (<mathias.matheus76@gmail.com>)

---

## 📜 Licença

Este plugin é distribuído sob os termos da **GNU General Public License v3.0** (GPL-3.0). Veja o arquivo [LICENSE.md](LICENSE.md) para mais detalhes.
