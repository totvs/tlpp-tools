---
layout: default
title: "Solução de Problemas"
parent: "Primeiros Passos"
nav_order: 7
---
<!-- markdownlint-disable MD025 MD013-->
# Solução de Problemas

## A extensão não carrega

- Verifique se o `tds-vscode` está instalado e ativado.
- Valide se a versão do `tds-vscode` é **2.0.12** ou superior.
- Reinicie o VSCode.

## O Teste de Integração Falha

- Verifique se a extensão `tlpp-tools` está ativada.
- Verifique se você está conectado a um ambiente pelo `tds-vscode`.
- Verifique se a versão do **tlppCore** de seu ambiente conectado é **01.05.08** ou superior.
- Refaça o teste.

## A cobertura não aparece

- Verifique se a extensão `tds-vscode` está conectada em um ambiente válido da aplicação.
- Verifique se há execução válida de PROBAT no ambiente conectado.
- Analise o log do `tlpp-tools` e verifique se tem a informação sobre o fonte solicitado.
- Experimente utilizar os Temas Oficiais do VSCode, pois temas customizados podem não respeitar schemas de decoração.
