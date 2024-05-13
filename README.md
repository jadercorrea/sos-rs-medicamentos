# SOS-RS Medicamentos

Repositório para versionar versões da ferramenta captura de informações sobre medicamentos doados
ao estado do Rio Grande do Sul com entradas via Unisinos e Base Aérea de Canoas.

As informações são capturadas via Bot e persistidas usando Planilhas para fácil manipulação e futuro
processamento.

### Funcionamento
Usuários recebem link direto para acesso ao bot. A foto do primeiro medicamento é solicitada, e em seguida, uma foto do lote do medicamento para controle e a quantidade disponível.

As URLs das imagens são disponibilizadas para checagem no google sheets definido como target, junto com a quantidade. Para facilitar o uso, as imagens capturadas são adicionadas no Sheets usando a formula `=image(url)`, de forma a permitir a visualização do nome e do lote sem necessidade de click nas urls, que são peristidas para o caso de serem necessárias.

![image](https://p275.p0.n0.cdn.zight.com/items/qGuboX1m/9ad1984c-a07a-4072-82a0-2de3d85dbbd6.jpg?source=viewer&v=c135270ac9989d9fae847f162a7bbf76)

### Ferramentas
* Typebot: http://typebot.io/
* Google Sheets: https://www.google.com/intl/pt-BR/sheets/about/
