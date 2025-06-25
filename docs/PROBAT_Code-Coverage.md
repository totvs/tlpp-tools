---
layout: default
title: "Cobertura Código"
parent: "PROBAT"
nav_order: 2
has_children: true
---
<!-- markdownlint-disable MD025 MD013-->
# Cobertura Código

Ao executar um plano de testes com a Cobertura de Código ativada no **PROBAT**, os dados coletados são armazenados no banco de dados.

Essas informações são utilizadas durante a execução para interromper a pipeline de testes caso o percentual mínimo de cobertura definido no produto não seja atingido.

Por meio do tlpp-tools, o desenvolvedor tem acesso a esses dados de forma visual, facilitando a análise da qualidade dos testes. Isso permite aprimorar tanto o código de teste quanto o próprio código-fonte.

Como o PROBAT mantém um histórico das execuções, a visualização da cobertura pode ser feita considerando apenas a **Última Execução** ou **Todas as Execuções** disponíveis.
