<div align="center">

# SGS Digital

### Presença digital autoral para marcas que não querem parecer comuns.

[![Status](https://img.shields.io/badge/status-online-d6a34a?style=for-the-badge&labelColor=050505)](https://sgsdigital.dev/)
[![Domain](https://img.shields.io/badge/domain-sgsdigital.dev-f0c36a?style=for-the-badge&labelColor=050505)](https://sgsdigital.dev/)
[![Frontend](https://img.shields.io/badge/frontend-HTML%20%2B%20CSS%20%2B%20JS-f3efe6?style=for-the-badge&labelColor=050505)](#stack)
[![Deploy](https://img.shields.io/badge/deploy-Cloudflare%20Pages-d6a34a?style=for-the-badge&labelColor=050505)](#deploy)

<br>

**SGS Digital** é uma experiência web conceitual construída para traduzir autoridade, sofisticação, raridade e presença em uma interface de alto impacto.

Não é apenas uma landing page.  
Não é apenas uma vitrine.  
É uma assinatura digital.

<br>

<a href="https://sgsdigital.dev/"><strong>Entrar no site oficial</strong></a>

</div>

---

## Visão

A **SGS Digital** nasce como uma casa de presença digital seletiva, voltada à criação de sites, landing pages, one pages conceituais e experiências digitais capazes de elevar a percepção de uma marca antes mesmo da primeira conversa.

O projeto foi desenhado para transmitir:

- autoridade silenciosa;
- luxo tech;
- presença seletiva;
- acabamento visual de alto padrão;
- narrativa digital com atmosfera restrita;
- impacto visual sem depender de excesso verbal;
- experiência imersiva com motion, profundidade e intenção.

A interface foi construída para que cada bloco pareça parte de um sistema: estética, estratégia, navegação, percepção e conversão trabalhando juntos.

A SGS Digital não se posiciona como uma agência comum.  
Ela se posiciona como uma estrutura autoral de presença digital para marcas que precisam parecer maiores, mais sólidas, mais raras e mais desejáveis.

---

## Domínio oficial

O domínio institucional da SGS Digital é:

> https://sgsdigital.dev/

Este é o endereço principal da marca, da experiência pública e da presença oficial da SGS Digital.

---

## Preview

> Site oficial  
> https://sgsdigital.dev/

> Subdomínio técnico de deploy  
> https://sgsdigital.pages.dev/

---

## Identidade

A SGS Digital se posiciona acima do ruído comum das agências tradicionais.

A leitura desejada não é:

> “empresa que faz sites”

A leitura desejada é:

> uma estrutura autoral de presença digital para marcas que precisam parecer maiores, mais sólidas, mais raras e mais desejáveis.

A assinatura visual parte de uma atmosfera escura, refinada e seletiva, com uso de preto profundo, dourado controlado, brilho sutil, camadas visuais, tipografia de presença e movimento calculado.

A marca trabalha com a ideia de:

- acesso;
- presença;
- seleção;
- autoridade;
- distinção;
- construção visual de alto valor percebido.

A SGS Digital não busca parecer popular.  
Ela busca parecer precisa, rara e intencional.

---

## Posicionamento

A SGS Digital é uma casa de presença digital premium para marcas que não querem parecer comuns.

A experiência foi construída para sustentar uma percepção de alto padrão em três camadas:

1. **Camada estética**  
   Atmosfera visual, composição, contraste, brilho, profundidade, tipografia, ritmo e direção de arte.

2. **Camada técnica**  
   Estrutura HTML, CSS e JavaScript controlada manualmente, com uso de motion, partículas, assets externos, roteamento por preset e deploy via Cloudflare Pages.

3. **Camada estratégica**  
   Narrativa de marca, percepção de autoridade, condução visual e contato comercial seletivo.

---

## Stack

Este projeto foi construído com uma abordagem direta, controlável e sem dependência de framework principal.

### Base

- HTML5
- CSS3
- JavaScript puro
- SVG
- Canvas
- WebGL
- Three.js
- GSAP
- Cloudflare Pages
- Cloudflare DNS
- Cloudflare CDN
- Domínio próprio `.dev`

### Recursos externos

- Assets visuais hospedados em repositório dedicado
- Fonte customizada Yayusa
- Cursores personalizados
- Favicons e manifest próprios
- Componentes visuais incorporados
- Música ambiente
- Imagens institucionais e banners de apoio

---

## Arquitetura

A estrutura atual da SGS Digital foi organizada para preservar controle visual, roteamento por resolução e uma experiência móvel independente.

```txt
SGS Digital
├── index.html          # base principal da experiência desktop
├── index1280.html      # preset desktop 1280x720
├── index1366.html      # preset desktop 1366x768
├── index1440.html      # preset desktop 1440x900
├── index1536.html      # preset desktop 1536x864
├── index1600.html      # preset desktop 1600x900
├── index1920.html      # preset desktop 1920x1080
├── index2560.html      # preset desktop ultrawide/alta largura
├── mobile.html         # versão móvel dedicada
├── robots.txt          # diretrizes de rastreamento
├── sitemap.xml         # mapa principal do site
└── assets externos     # consumidos via SGS-Digital-Assets
```

O roteamento inicial seleciona a versão mais adequada antes da experiência visual carregar, preservando a intenção estética de cada preset desktop e mantendo uma versão mobile independente, mais leve e fluida.

Este repositório funciona como a base técnica proprietária da experiência oficial da SGS Digital, reunindo versionamento, estrutura HTML, lógica de roteamento, SEO técnico e suporte ao deploy via Cloudflare Pages.

---

## Sistema de presets desktop

A experiência desktop utiliza múltiplas versões preparadas para resoluções específicas.

O objetivo não é depender de responsividade genérica, mas preservar a composição visual com maior controle em diferentes proporções de tela.

Presets atuais:

```txt
1280x720   → index1280.html
1366x768   → index1366.html
1440x900   → index1440.html
1536x864   → index1536.html
1600x900   → index1600.html
1920x1080  → index1920.html
2560x1080  → index2560.html
```

Quando necessário, o sistema utiliza um preset fallback para garantir carregamento controlado em cenários fora dos presets principais.

---

## Versão mobile

A versão mobile é mantida em arquivo próprio:

```txt
mobile.html
```

Ela foi criada para preservar a identidade conceitual da experiência principal, mas com foco em leveza, fluidez e compatibilidade com dispositivos móveis.

A versão mobile evita a dependência do peso visual do desktop e prioriza:

- carregamento mais leve;
- navegação direta;
- leitura clara;
- contato via WhatsApp;
- manutenção da atmosfera premium;
- preservação da narrativa visual da SGS Digital.

---

## SEO técnico

O projeto inclui estrutura técnica voltada para indexação, reconhecimento de entidade e consistência semântica.

Elementos utilizados:

- título otimizado;
- meta description institucional;
- canonical principal;
- Open Graph;
- Twitter Card;
- favicons;
- manifest;
- robots.txt;
- sitemap.xml;
- dados estruturados JSON-LD;
- identificação de organização;
- identificação de site;
- contexto institucional da marca;
- domínio oficial em HTTPS.

O objetivo do SEO técnico da SGS Digital não é parecer genérico ou disputar volume por excesso de palavras-chave.

O objetivo é permitir que mecanismos de busca compreendam com clareza:

- o nome da marca;
- o domínio oficial;
- o posicionamento;
- o fundador;
- a natureza do serviço;
- a relação entre site, identidade e presença digital.

---

## Assets externos

Os arquivos visuais, tipográficos, sonoros e de apoio são consumidos a partir do repositório dedicado:

> https://github.com/SaintSGS-hub/SGS-Digital-Assets

Esse repositório funciona como biblioteca estática oficial da SGS Digital, permitindo organização centralizada dos recursos utilizados pela experiência principal.

Entre os recursos consumidos estão:

- imagens institucionais;
- banners;
- favicons;
- fontes;
- cursores;
- música ambiente;
- componentes visuais;
- arquivos de apoio.

---

## Deploy

O site oficial é publicado via **Cloudflare Pages**, conectado ao repositório principal.

Fluxo geral:

```txt
GitHub Repository
        ↓
Cloudflare Pages
        ↓
Cloudflare CDN
        ↓
https://sgsdigital.dev/
```

A estrutura permite atualização por versionamento, deploy automático e distribuição global através da infraestrutura da Cloudflare.

---

## Repositório técnico

Este repositório não funciona como página pública de aquisição, link de apresentação popular ou ambiente de rede social.

Ele é a base técnica proprietária da SGS Digital.

Sua função é concentrar:

- código principal;
- estrutura da experiência;
- presets desktop;
- versão mobile;
- SEO técnico;
- arquivos de rastreamento;
- versionamento;
- histórico de evolução;
- suporte ao deploy oficial.

O contato com a SGS Digital acontece prioritariamente pelo site oficial.

---

## Relação com a marca

A SGS Digital trabalha com presença, não com excesso.

A estrutura do site foi pensada para causar uma impressão de:

- acesso restrito;
- curadoria;
- sofisticação;
- autoridade visual;
- tecnologia silenciosa;
- experiência rara;
- alto valor percebido.

Cada decisão visual busca reforçar a ideia de que a marca não está competindo no mesmo espaço das soluções comuns.

---

## Status

```txt
Status: online
Domínio: https://sgsdigital.dev/
Deploy: Cloudflare Pages
Base: HTML + CSS + JavaScript
Versão mobile: dedicada
SEO técnico: ativo
Sitemap: ativo
Robots: ativo
```

---

## Licença e uso

Este projeto é parte da base técnica e visual proprietária da SGS Digital.

O uso, cópia, redistribuição, adaptação ou reaproveitamento de sua identidade, estrutura visual, textos, assets, composições, lógica de apresentação ou direção estética não é autorizado sem permissão expressa.

---

<div align="center">

**SGS Digital**  
Presença digital autoral para marcas que não querem parecer comuns.

https://sgsdigital.dev/

</div>
