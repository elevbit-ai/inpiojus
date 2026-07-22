# INPIOJUS 1.0.0 — IA Jurídica e Argumentos Processuais

[![Version](https://img.shields.io/badge/version-1.0.0-blue)](VERSION)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](LICENSE)

**Desenvolvedor:** Joaquim Pedro de Morais Filho  
**Contato:** [zicutake@mail.ru](mailto:zicutake@mail.ru)  
**Assinado:** build-1000 · © 2026  

## Demo

- **App:** https://elevbit-ai.github.io/inpiojus/  
- **Tutorial:** https://elevbit-ai.github.io/inpiojus/docs/tutorial.html  
- **Repo:** https://github.com/elevbit-ai/inpiojus  

## O que é

Aplicação web (HTML/JS) para:

1. Ler decisão/autos (texto ou **PDF**)
2. Enviar à **IA Gemini** com *system prompts* de argumentação jurídica
3. Gerar petições (HC, embargos, recursos, mandados, agravos) ou **resumo**
4. Exportar PDF institucional

## Uso de IA e argumentos

| Camada | Função |
|--------|--------|
| **System instruction** | Define o papel da IA (advocacia técnica, rito, formalismo) |
| **User prompt** | Autos + qualificação + tribunal + tipo de peça |
| **Argumentos** | Estrutura: fatos → direito → pedidos → jurisprudência sugerida |
| **Modelo** | Gemini (configurável; padrão `gemini-2.0-flash`) |

Detalhes: [docs/tutorial.html](docs/tutorial.html)

## Como rodar

1. Abra `index.html` no navegador **ou** use o GitHub Pages  
2. Clique **Configurar API Gemini** e cole a chave de [Google AI Studio](https://aistudio.google.com/apikey)  
3. Cole o texto da decisão ou envie PDF  
4. Escolha o rito e gere a peça  

> A chave fica só no **localStorage** do seu navegador — não vai para o GitHub.

## Aviso legal

Ferramenta **assistiva**. Não substitui advogado. Revise toda peça antes de protocolar. Não use para fraude ou falsidade ideológica.

## Assinatura

```
© 2026 Joaquim Pedro de Morais Filho <zicutake@mail.ru>
INPIOJUS 1.0.0 — IA Jurídica / Argumentos Processuais
```

## Licença

MIT — ver [LICENSE](LICENSE).
