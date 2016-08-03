# FileMaker Tools
========
Fuções para formatar e validar diversos números no FileMaker

## FormataTelefone
Formata números de telefone no FileMaker de acordo com o número de dígitos (1234-5678, 12345-6789, (12) 1234-5678 ou (12) 12345-6789).

## FormataCEP
Formata o número do CEP como 00.000-000

## FormataCPF
Formata CPF como 000.000.000-00

##ValidaCPF
Fução para validar número do CPF no FileMaker

## ValidaSUS
Fução para validar número do Cartão Nacional de Saúde (CNS) do SUS no FileMaker

Os números iniciados por 7, 8 ou 9 são números provisórios, iniciados em 1 ou 2 são definitivos.

Não existe máscara para o CNS nem para o número provisório. O número que aparece no cartão de forma separada (898 0000 0004 3208) deverá ser digitado sem as separações.

O 16 dígito que aparece no cartão é o número da via do cartão, e não deverá ser digitado.

Referência: http://cartaonet.datasus.gov.br/Rotina_Delphi.doc
