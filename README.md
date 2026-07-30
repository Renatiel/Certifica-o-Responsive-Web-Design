# Certificação Responsive Web Design - freeCodeCamp

Projetos desenvolvidos durante a certificação de Responsive Web Design do freeCodeCamp.

## 📁 Estrutura

```
Certifica-o-Responsive-Web-Design/
├── Survey form.html    # Projeto de formulário de pesquisa
└── web design/         # Demais projetos da certificação
```

## 💻 Projetos

### Survey Form — *Marginalia Reading Survey*

Formulário de pesquisa para leitores, estilizado como um cartão de catálogo de biblioteca/livraria.

**Destaques técnicos:**
- Layout construído com tipografia serifada (`Source Serif 4`) combinada com uma fonte de máquina de escrever (`Special Elite`) para reforçar a identidade visual "vintage"
- Uso de `:root` com variáveis CSS (`--paper`, `--ink`, `--stamp`, `--gold`, etc.) para centralizar a paleta de cores
- Fundo texturizado com `repeating-linear-gradient` simulando linhas de papel, combinado com `radial-gradient` para um leve destaque de luz
- Selo decorativo (`.stamp`) posicionado com `position: absolute` e rotação via `transform: rotate()`
- Campos de formulário completos: texto, e-mail, número (com `min`/`max`), `select`, `radio`, `checkbox` e `textarea`
- Estados de acessibilidade tratados via `:focus-visible` e `:invalid:not(:placeholder-shown)`
- Responsividade com media query `@media (max-width: 480px)` ajustando espaçamentos e tamanho do selo
- Respeito à preferência de movimento reduzido (`@media (prefers-reduced-motion: reduce)`)

### Demais projetos (pasta `web design/`)

> Conteúdo ainda não detalhado. Assim que os arquivos forem revisados, esta seção será atualizada com a descrição de cada projeto.

## ▶️ Como executar

Basta abrir os arquivos `.html` diretamente no navegador — não há dependências externas além das fontes do Google Fonts, carregadas via CDN.

## 📄 Licença

Uso livre para fins de estudo.
