# The Forbidden Knowledge

**Propósito:** apresentar o trabalho público e o método de Kauã Silbershlach Parodes — para quem avalia contratar, colaborar ou auditar.

**Julgamento:** este é o perfil de um analista de Cyber Threat Intelligence (CTI) que constrói software. A prova não está neste texto: está nos dez repositórios abaixo, com código e testes abertos à auditoria.

**Impacto:** quem decide sobre este profissional decide com evidência. Cada afirmação das próximas seções aponta para um artefato público que a sustenta.

Construo sistemas que transformam sinais técnicos em decisões verificáveis. Cada ferramenta segue a mesma cadeia: sinal, evidência, contexto, hipótese, finding, decisão. Nada entra sem provenance; nada sai sem prova.

A IA opera comigo como multiplicador de execução, nunca como substituto de validação. Fontes, evidências e resultados continuam verificados um a um — esse limite mantém o trabalho confiável.

## Áreas: seis frentes, um ofício

- **CTI e Open Source Intelligence (OSINT)** — coleta com método e avaliação de fonte.
- **Digital Forensics and Incident Response (DFIR)** — aquisição e análise: Windows, rede, memória, mobile.
- **Engenharia de detecção** — detecções nascem de evidência, não de intuição.
- **Operações de segurança (SOC) e resposta** — monitoramento, hunting, contenção.
- **Segurança ofensiva e defensiva** — red team e purple team alimentam a defesa.
- **Cloud, DevSecOps e automação** — Python, Elixir e C++ como ferramental diário.

## Projetos: a prova mora no código

| Projeto | O que faz | A prova |
|---|---|---|
| [muse-commander-mcp](https://github.com/the-forbidden-knowledge/muse-commander-mcp) | Agente em Python que expõe arquivos, processos e terminal de uma máquina por API no tailnet, com token por instalação | 25 tools, 60 testes, log de auditoria com cadeia de hashes |
| [cve-monitor](https://github.com/the-forbidden-knowledge/cve-monitor) | Base de CVEs com os críticos traduzidos para pt-br | Repositório público com a base e as traduções |
| [web-vuln-scanner-elixir](https://github.com/the-forbidden-knowledge/web-vuln-scanner-elixir) | Scanner de vulnerabilidades web em Elixir com núcleo nativo em C++ | A BEAM orquestra; o C++ executa o trabalho pesado |
| [cpp-elixir-nif-template](https://github.com/the-forbidden-knowledge/cpp-elixir-nif-template) | Template C++ + Elixir com NIF nativo via CMake | Base reutilizável dos projetos nativos |
| [electron-blank-template](https://github.com/the-forbidden-knowledge/electron-blank-template) | Template Electron mínimo e endurecido, sem `loadURL` | Janela vazia em ~0,23s; `webPreferences` seguras por padrão |
| [speak-spell-voice-synth](https://github.com/the-forbidden-knowledge/speak-spell-voice-synth) | Síntese de voz no estilo dos aparelhos dos anos 70 e 80, operada por IA | A voz robótica lendária reconstruída como software |
| [muse-ida-reversing-pro](https://github.com/the-forbidden-knowledge/muse-ida-reversing-pro) | Laboratório de engenharia reversa com IDA Pro operado pelo Muse via MCP | Stack Elixir; estrutura publicada no padrão |
| [muse-hostinger-console](https://github.com/the-forbidden-knowledge/muse-hostinger-console) | Terminal web da Hostinger operado pelo Muse: comandos no VPS sem sair do chat | Stack Elixir + C++; estrutura publicada no padrão |
| [muse-roblox-studio-mcp](https://github.com/the-forbidden-knowledge/muse-roblox-studio-mcp) | Criação de jogos e scripts Luau para Roblox operada pelo Muse | Estrutura publicada; About e tags aplicados |
| [muse-darkweb-intel-mcp](https://github.com/the-forbidden-knowledge/muse-darkweb-intel-mcp) | Template de CTI: da IOC à TTP, fazendo o adversário subir a pirâmide da dor | Amostra 01 publicada; 30.790 arquivos classificados da matéria-prima 1 |

## Formação: 42 formações aplicadas, não colecionadas

- **SANS Technology Institute** — 42 formações integralmente estudadas e aplicadas: Cybersecurity Engineering, Threat Intelligence, DFIR, arquitetura e operações.
- **GIAC** — GCTI, GCFA, GCDA, GOSI, GPEN, GEIR, GSOC, GSOM, GXPN, GREM, GWEB, GCIA, GNFA, GICSP, GMLE.
- **Outras** — CTIA e SOC Analyst (EC-Council), CEH, Security+ (CompTIA) e dezenas de formações técnicas.

Fonte desta seção: o registro público do próprio autor — fonte única, declarada como tal. A lista completa, com datas e credenciais, está no [meu LinkedIn](https://www.linkedin.com/in/kaua-cyber-investigator/).

## Método: fato, inferência e julgamento nunca se misturam

- **Evidência antes de conclusão.** Cada afirmação carrega o seu rótulo.
- **Números medidos, não estimados.** Sem medição, a afirmação não entra.
- **Incerteza declarada.** O gap aparece escrito; gap disfarçado corrói confiança.
- **Segredos fora do código.** Credenciais vivem em cofre, nunca em repositório.

## A objeção óbvia — e o que este perfil não mostra

A objeção: "são projetos pessoais e uma lista de cursos". A resposta está no desenho: cada projeto publica código, testes e histórico para auditoria de terceiros. Quem duvida não precisa acreditar neste texto; precisa apenas ler os repositórios.

Duas limitações honestas: repositório público prova código e testes — não prova uso em produção nem resultado para cliente. E clientes, operações e sistemas internos não aparecem aqui, por desenho e não por ausência. Este quadro muda por um gatilho declarado: quando um projeto ganha código e testes públicos, ele entra na tabela acima, com a prova ao lado.

## Contato

GitHub: [@the-forbidden-knowledge](https://github.com/the-forbidden-knowledge) · LinkedIn: [kaua-cyber-investigator](https://www.linkedin.com/in/kaua-cyber-investigator/)

*Fontes e método deste perfil: os dez repositórios públicos linkados, verificados nesta data, e o registro do autor no LinkedIn.*
