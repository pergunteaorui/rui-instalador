# Instaladores do Pergunte ao Rui

Este repositório só distribui o instalador do **Pergunte ao Rui** (Windows 10/11, 64 bits).
O código-fonte é privado — não está aqui, e nenhuma release deste repo publica fonte.

## URLs canônicas

| Ambiente | URL (nunca muda) |
|---|---|
| STAGE (`uat`) | https://github.com/pergunteaorui/rui-instalador/releases/download/uat-latest/Rui-setup.exe |
| Produção (`prod`) | https://github.com/pergunteaorui/rui-instalador/releases/download/prod-latest/Rui-setup.exe |

`uat-latest` / `prod-latest` são **tags móveis**: cada release troca o asset, a URL do site e do
e-mail de entrega continua a mesma. As releases versionadas (`v1.0.2-uat`, …) ficam ao lado como
histórico.

## Como instalar

1. Abra o `Rui-setup.exe` e aceite a solicitação de administrador (instala em *Program Files*, para todos os usuários da máquina).
2. Abra **Pergunte ao Rui** no menu Iniciar → **Configurações → Licença**.
3. Cole a chave que chegou por e-mail. A chave vale para o número de computadores do plano contratado.

A versão do que está em `uat-latest`/`prod-latest` aparece no corpo da release e em
**Configurações → Licença** dentro do app.
