# 🎮 Zenith 2D - Game Engine

Uma engine profissional para desenvolvimento de jogos 2D multiplataforma, desenvolvida em **Python** com suporte para **PC (Windows, macOS, Linux)** e **Android**.

## ✨ Características

- 🎯 **Multiplataforma**: PC e Android
- 🎨 **Renderização 2D** eficiente com suporte a sprites e animações
- ⚙️ **Sistema de Física 2D** integrado
- 🎬 **Gerenciador de Cenas** profissional
- 🎵 **Sistema de Áudio** completo
- ⌨️ **Input Multiplataforma** (teclado, mouse, touch)
- 📦 **Gerenciador de Recursos** otimizado
- 🎯 **Sistema de Partículas**
- 🎪 **Editor Visual** (em desenvolvimento)

## 🚀 Quick Start

### Instalação

```bash
# Clone o repositório
git clone https://github.com/briandofnf123/Zenith-2D.git
cd Zenith-2D

# Instale as dependências
pip install -r requirements.txt
```

### Seu Primeiro Jogo

```python
from zenith.engine import Engine
from zenith.scene import Scene

class MyScene(Scene):
    def load(self):
        print("Scene loaded!")
    
    def update(self, dt):
        pass
    
    def render(self, screen):
        pass

engine = Engine(width=800, height=600, title="Meu Jogo com Zenith 2D")
engine.add_scene("main", MyScene())
engine.run("main")
```

## 📁 Estrutura do Projeto

```
Zenith-2D/
├── zenith/                 # Engine core
│   ├── engine.py          # Motor principal
│   ├── scene.py           # Sistema de cenas
│   ├── input.py           # Sistema de entrada
│   ├── physics/           # Física 2D
│   ├── graphics/          # Renderização
│   ├── audio/             # Áudio
│   └── resources/         # Gerenciador de recursos
├── examples/              # Exemplos práticos
├── docs/                  # Documentação
├── tests/                 # Testes unitários
└── requirements.txt       # Dependências
```

## 📚 Documentação

- [Guia de Início Rápido](docs/GETTING_STARTED.md)
- [API Reference](docs/API.md)
- [Exemplos](examples/)
- [Roadmap](docs/ROADMAP.md)

## 🛠️ Tecnologias

- **Python 3.8+**
- **Pygame** - Renderização e input
- **Pymunk** - Física 2D
- **Pillow** - Processamento de imagens

## 📄 Licença

MIT License - veja [LICENSE](LICENSE) para detalhes.

## 👨‍💻 Desenvolvedor

Desenvolvido com ❤️ por **briandofnf123**

---

**Status**: 🔨 Em Desenvolvimento Ativo
