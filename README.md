# JS_DAEB_RS

Rotina JavaScript para leitura e tratamento de PDFs da DAEB/RS dentro de uma esteira de automação documental.

## Contexto

Em projetos de RPA com contas de concessionárias, cada estado e cada fornecedor pode ter um layout diferente. Este repositório representa uma das regras específicas dessa esteira: tratar contas DAEB/RS, localizar campos importantes e preparar os dados para uso operacional.

Essa frente fez parte de um conjunto maior de automações envolvendo contas de água, energia elétrica e energia solar, com necessidade de adaptar o parsing para layouts diferentes.

## Responsabilidades

- Processar conteúdo extraído de PDFs
- Localizar campos relevantes em contas DAEB/RS
- Apoiar validação e transformação de dados para automação
- Reduzir tratamento manual de documentos recorrentes

## Stack

- JavaScript
- Parsing de texto
- PDF/OCR
- RPA
- Automação documental

## Arquivo principal

- `DAEB_RS_JS.js`

## Evolução recomendada

- Remover dados sensíveis de massas públicas de teste
- Separar regras de extração por função
- Criar testes automatizados com amostras anonimizadas
- Padronizar saída para JSON, facilitando integração com outros sistemas

## Observação

O valor deste tipo de automação está na adaptação ao mundo real: documentos mudam de layout, a qualidade do PDF varia e o código precisa ser resiliente o suficiente para manter a operação funcionando.
