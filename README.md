# Contabilidade TJSP · versões

Pacotes do programa Contabilidade TJSP, que confere as NFS-e recebidas no Emissor Nacional (nfse.gov.br) contra o Relatório-Geral ou o Relatório de Liquidações do sistema do Tribunal de Justiça do Estado de São Paulo. **O programa só lê:** nunca aprova, confirma, rejeita ou altera nada no portal nem nos sistemas do tribunal.

## Instalar
Requisitos: Windows 10/11, Python 3.13 da Microsoft Store, Microsoft Edge e acesso ao Emissor Nacional.
1. Baixe `ContabilidadeTJSP_<versão>.zip` na [versão mais recente](https://github.com/sincevoid/conferencia-notas-versao/releases/latest); em Propriedades, marque **Desbloquear** se aparecer.
2. Extraia e abra `INSTALAR.bat`. O guia de uso é o `LEIA-ME.txt`, que vem no ZIP.

Depois de instalado, o programa se atualiza sozinho: procura a versão nova, baixa em segundo plano e instala ao fechar. Notas, planilhas, histórico e login são mantidos.

## O que tem aqui
| Onde | O que é |
|---|---|
| [Releases](https://github.com/sincevoid/conferencia-notas-versao/releases) | O ZIP de cada versão, assinado pelo suporte, com o que mudou nela |
| `versao.json` | O número da versão atual, que o programa consulta para saber se há uma nova |
| `novidades.json` | As novidades de cada versão, lidas só pelos programas até a 1.5.x |
| Release `teste-rede` | Arquivo de teste de download; não é uma versão do programa |

Os arquivos e as Releases são gravados pelo suporte ao publicar uma versão. O programa instalado recusa qualquer ZIP sem a assinatura do suporte.

---
Desenvolvido por **João V. (@sincevoid)**.
