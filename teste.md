# -teste_sistema_desconto
"teste de um código de um sistema de desconto em python"
TESTE01
ENTRADA: -1
RESULTADO_ESPERADO: mensagem de erro sem travar o sistema
RESULTADO_TESTE:
Digite o valor da compra: -1
Digite o percentual de desconto (ex: 10 para 10%): 10

✅ Processado com sucesso!
Valor Final: R$ -1.0
=== SISTEMA DE DESCONTOS v1.0 (QA TEST) ===

Process finished with exit code 0

TESTE02
ENTRADA: A
RESULTADO_ESPERADO:mensagem de erro sem travar o sistema
RESULTADO_TESTE:
Digite o valor da compra: A
Erro no sistema.
=== SISTEMA DE DESCONTOS v1.0 (QA TEST) ===

Process finished with exit code 0

TESTE03
ENTRADA: 1000
RESULTADO_ESPERADO: resultado do desconto aplicado no valor digitado
RESULTADO_TESTE:
Digite o valor da compra: 1000
Digite o percentual de desconto (ex: 10 para 10%): 55

✅ Processado com sucesso!
Valor Final: R$ 1000.0
=== SISTEMA DE DESCONTOS v1.0 (QA TEST) ===

Process finished with exit code 0

O SISTEMA AINDA NÃO ESTÁ CALCULANDO OS DESCONTOS
FAREI ALGUMAS ALTERAÇÕES PARA TENTAR ARRUMAR O CÓDIGO

TESTE04
ENTRADA: 1000
RESULTADO_ESPERADO: resultado do desconto aplicado no valor digitado
RESULTADO_TESTE:
=== SISTEMA DE DESCONTOS v1.0 (QA TEST) ===
Digite o valor da compra: 1000
Digite o percentual de desconto (ex: 10 para 10%): 50

✅ Processado com sucesso!
Valor Final: R$ 500.00

Process finished with exit code 0

APÓS REFAZER O TESTE CONSEGUIMOS O RESULTADO ESPERADO

TESTE05
ENTRADA: -1
RESULTADO_ESPERADO: mensagem de erro sem travar o sistema
RESULTADO_TESTE:
=== SISTEMA DE DESCONTOS v1.0 (QA TEST) ===
Digite o valor da compra: -1
Digite o percentual de desconto (ex: 10 para 10%): 40

✅ Processado com sucesso!
Valor Final: R$ -0.60

Process finished with exit code 0

RESULTADO NÃO FOI O ESPERADO
FAREI MAIS ALTERAÇÕES NO CÓDIGO

TESTE06
ENTRADA: -1
RESULTADO_ESPERADO: mensagem de erro sem travar o sistema
RESULTADO_TESTE:
=== SISTEMA DE DESCONTOS v1.0 (QA TEST) ===
Digite o valor da compra: -1
❌ Erro: O valor da compra deve ser maior que zero!

Process finished with exit code 0
