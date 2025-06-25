# TLPP & tlppCore Tools

A extensão **TOTVS.tlpp-tools** para o VSCode oferece funcionalidades que  
ampliam e facilitam o uso da linguagem **TOTVS TLPP**, além de integrar  
recursos dos módulos do **tlppCore**.

## Manual de Uso

Acesse [totvs.github.io/tlpp-tools/](https://totvs.github.io/tlpp-tools/) para o
guia completo de utilização da extensão.

## Funcionalidades

- Integração com a extensão **TOTVS.tds-vscode**, utilizando o Language Server
  para acessar recursos do TLPP e do tlppCore.

- Validação da integração entre **TOTVS.tlpp-tools** x **TOTVS.tds-vscode** e **tlppCore**.

- **PROBAT**:
  - Visualização da **Cobertura de Código** gerada por execução de planos de teste.
  - Geração de código-fonte a partir de templates de testes PROBAT.

## Requisitos

- Visual Studio Code **v1.88.0** ou superior;

- Extensão **TOTVS.tds-vscode** versão **2.0.12** ou superior;

- **TOTVS tlppCore** versão **01.05.08** ou superior
  > O tlppCore corresponde ao tlpp.rpo fornecido junto ao TOTVS Application  
    Server (AppServer).

## Extensões com incompatibilidade

Devido à dependência da extensão **TOTVS.tds-vscode**, o **TOTVS.tlpp-tools**
compartilha a mesma base de compatibilidade. As extensões abaixo podem causar
conflitos e não devem ser utilizadas simultaneamente:

- [4gl Outline Dxc](https://www.vsixhub.com/vsix/14295/)
- [advpl-vscode](https://github.com/totvs/advpl-vscode)
- flutter e dart

> Se você identificar qualquer outra extensão que cause problemas ao usar o
> **TDS for VS-Code**, por favor, [registre um chamado](https://github.com/totvs/tds-vscode/issues)
> com os detalhes da extensão e do erro observado.

## Disponibilidade

- A extensão será disponibilizada em breve diretamente no
  [Visual Studio Code Marketplace](https://marketplace.visualstudio.com/vscode),
  facilitando sua instalação e atualização automática pelo VSCode.

## Código-Fonte

- Este repositório **não contém o código-fonte da extensão**, que permanecerá
  privado. No entanto, o projeto será mantido no GitHub para:

  - Acesso ao histórico de **Release Notes**;

  - Consulta à **descrição das funcionalidades**;

  - Acesso ao **manual de uso** disponível no
    [Wiki do repositório](https://github.com/totvs/tlpp-tools/wiki);

  - Registro e acompanhamento de **Issues**.

## 🐞 Bugs

Encontrou um bug? Nos ajude a melhorar:
[abra uma issue](https://github.com/totvs/tlpp-tools/issues/new?assignees=&labels=bug&type=Bug&template=bug_report.md&title=)
e informe os detalhes.

## 💡 Melhorias

Tem uma ideia para uma nova funcionalidade? Envie sua sugestão
[por aqui](https://github.com/totvs/tlpp-tools/issues/new?assignees=&labels=enhancement&type=Feature&template=feature_request.md&title=).
