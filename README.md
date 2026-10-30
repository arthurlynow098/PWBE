<p align="center">
  <img src="assets/banner-v2.png" alt="PWBE" width="100%">
</p>

<p align="center">Material de estudo sobre JavaScript no servidor e execução assíncrona com Node.js.</p>

<p align="center"><img src="assets/docs/tags.svg" alt="Node.js · JavaScript · Back-end" width="72%"></p>

<p align="center"><a href="#visão-geral">Visão geral</a> &nbsp;·&nbsp; <a href="#recursos">Recursos</a> &nbsp;·&nbsp; <a href="#como-explorar">Como explorar</a></p>

---

<a id="explore-o-projeto"></a>

![Explore o projeto](assets/docs/section-01.svg)

![Mapa visual dos arquivos e responsabilidades](assets/docs/map.svg)

| Área | O que você encontra | Acesso direto |
|---|---|---|
| **Estudo** | Material introdutório sobre Node.js. | [Abrir estudo →](Node.js) |
| **Material visual** | Imagem de referência presente no repositório. | [Abrir material visual →](Nodejs.png) |
| **Orientações** | Contexto e guia de exploração do material. | [Abrir orientações →](README.md) |

<a id="visão-geral"></a>

![Visão geral](assets/docs/section-02.svg)

O repositório **PWBE (Programação Web Back-End)** registra a introdução ao desenvolvimento de servidores utilizando **Node.js**, compreendendo como o motor V8 do Google e a arquitetura *Event Loop Single-Thread Non-Blocking I/O* permitem processar requisições concorrentes com alto desempenho.

<a id="recursos"></a>

![Recursos](assets/docs/section-03.svg)

| Elemento | Descrição |
|---|---|
| Node.js | Script e anotações fundamentais sobre inicialização e execução no ambiente Node. |
| Nodejs.png | Referência visual de apoio aos conceitos estudados na disciplina de Programação Web Back-End. |

<details>
<summary>Arquitetura do Runtime estudado</summary>

```mermaid
flowchart LR
    A["Código JavaScript · Node.js"] --> B["Motor Google V8"]
    B --> C["Event Loop · libuv"]
    C --> D["Operações Assíncronas Non-Blocking I/O"]
```

</details>

<details>
<summary>Estrutura do repositório</summary>

```text
PWBE/
├── assets/
│   └── banner-v2.png               Banner do projeto
├── Node.js                         Arquivo de estudo e código Node.js
├── Nodejs.png                      Diagrama / imagem de referência
└── README.md
```

</details>

<a id="como-explorar"></a>

![Como explorar](assets/docs/section-04.svg)

1. Clone o repositório:
   ```bash
   git clone https://github.com/arthurlynow098/PWBE.git
   cd PWBE
   ```
2. Consulte o arquivo Node.js e execute-o com o runtime instalado (node Node.js).

---

<p align="center">
  <a href="https://github.com/arthurlynow098">GitHub</a> &nbsp;·&nbsp;
  <a href="https://arthurentsev.vercel.app/">Portfólio</a> &nbsp;·&nbsp;
  <a href="https://www.linkedin.com/in/entsevarthur/">LinkedIn</a>
</p>
