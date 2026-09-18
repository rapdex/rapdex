# Política de Privacidade — Rapdex

**Última atualização: 9 de setembro de 2026**

## Resumo

O Rapdex **não coleta, não transmite e não vende nenhum dado pessoal**. Não há
conta, não há servidor, não há rastreamento e não há anúncios. A extensão não
faz nenhuma requisição de rede.

## O que a extensão guarda

Tudo fica no armazenamento do seu próprio navegador, através da API padrão de
extensões do Chrome. Nada é enviado para o desenvolvedor.

### Sincronizado pela sua conta do Google (`chrome.storage.sync`)

- Suas preferências: passo de velocidade, velocidade preferida, preservação de
  tom, atalhos, exibição do painel de atalhos, ajuste por capítulo.
- A velocidade salva por site, junto do domínio correspondente (por exemplo,
  `udemy.com` → `1.75`).

Esses dados usam o mecanismo de sincronização do próprio Chrome, para que suas
preferências acompanhem você entre dispositivos. **Eles trafegam pela sua conta
do Google, não por servidores do Rapdex.** Se a sincronização do Chrome estiver
desligada, ficam apenas no aparelho. O desenvolvedor não tem acesso a eles.

### Somente neste aparelho (`chrome.storage.local`)

- O contador de tempo recuperado, por dia e no total.
- Se você já viu a dica de primeiro uso e quantas vezes ajustou a velocidade.
- Se você dispensou o convite de apoio.

Esses dados nunca saem do aparelho.

## O que a extensão nunca guarda

- Histórico de navegação, URLs completas ou títulos de páginas.
- Conteúdo de vídeos, áudio, legendas ou transcrições.
- Endereço de e-mail, nome, endereço IP ou qualquer identificador pessoal.
- Formulários, senhas ou dados de pagamento.

## Permissões e por quê

| Permissão | Motivo |
|---|---|
| `storage` | Guardar suas preferências e o contador, conforme descrito acima. |
| Acesso a todos os sites | Vídeo existe em qualquer página. A extensão precisa detectar o player para ajustar a velocidade. Ela **lê apenas os elementos de mídia** e o título do capítulo no YouTube; não lê o conteúdo da página, não injeta anúncios e não altera links. |

## Quando você clica em algo

Três ações abrem uma página externa em nova aba. Nenhuma envia dados sozinha.

- **"Avisar que não funciona aqui"** abre o GitHub com um formulário já
  preenchido contendo **apenas o domínio** do site (por exemplo, `udemy.com`),
  a versão da extensão e o nome do navegador. A URL completa da página que você
  estava vendo **nunca** é incluída. Nada é enviado até você revisar e clicar em
  enviar, pela sua própria conta do GitHub.
- **"Apoiar o projeto"** abre um link de pagamento do Mercado Pago. O pagamento
  acontece inteiramente no Mercado Pago, sob a política de privacidade deles.
- **Links de suporte** abrem o repositório no GitHub, sob a política deles.

## Serviços de terceiros

O Rapdex não integra nenhum serviço de análise, publicidade ou telemetria.

## Alterações

Mudanças nesta política aparecem neste arquivo, com a data no topo.

## Contato

Abra uma issue em https://github.com/rapdex/rapdex/issues

---

# Privacy Policy — Rapdex

**Last updated: 9 September 2026**

## Summary

Rapdex **does not collect, transmit or sell any personal data**. There is no
account, no server, no tracking and no ads. The extension makes no network
requests.

## What the extension stores

Everything stays in your own browser's storage, through the standard Chrome
extension API. Nothing is sent to the developer.

### Synced through your Google account (`chrome.storage.sync`)

- Your preferences: speed step, preferred speed, pitch preservation, shortcuts,
  shortcut panel visibility, chapter adjustment.
- The speed saved per site, together with the matching domain (for example,
  `udemy.com` → `1.75`).

These use Chrome's own sync mechanism so your preferences follow you across
devices. **They travel through your Google account, not through Rapdex
servers.** With Chrome sync off, they stay on the device. The developer has no
access to them.

### This device only (`chrome.storage.local`)

- The time-saved counter, per day and in total.
- Whether you have seen the first-run tip and how many times you changed speed.
- Whether you dismissed the support prompt.

This data never leaves the device.

## What the extension never stores

- Browsing history, full URLs or page titles.
- Video content, audio, subtitles or transcripts.
- Email address, name, IP address or any personal identifier.
- Form input, passwords or payment details.

## Permissions and why

| Permission | Reason |
|---|---|
| `storage` | Keep your preferences and the counter, as described above. |
| Access to all sites | Video lives on any page. The extension needs to detect the player to change its speed. It **only reads media elements** and the YouTube chapter title; it does not read page content, inject ads or alter links. |

## When you click something

Three actions open an external page in a new tab. None of them sends data on
its own.

- **"Report that it does not work here"** opens GitHub with a form pre-filled
  with **only the domain** of the site (for example, `udemy.com`), the extension
  version and the browser name. The full URL of the page you were watching is
  **never** included. Nothing is submitted until you review it and click submit,
  under your own GitHub account.
- **"Support the project"** opens a Mercado Pago payment link. Payment happens
  entirely on Mercado Pago, under their privacy policy.
- **Support links** open the GitHub repository, under their policy.

## Third-party services

Rapdex integrates no analytics, advertising or telemetry service.

## Changes

Changes to this policy appear in this file, with the date at the top.

## Contact

Open an issue at https://github.com/rapdex/rapdex/issues
