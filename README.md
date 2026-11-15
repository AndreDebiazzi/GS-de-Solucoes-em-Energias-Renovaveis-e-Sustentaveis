# Citizen Assist AI | Módulo de Energia e Sustentabilidade

Contribuição da disciplina Soluções em Energias Renováveis e Sustentáveis (Global Solution, 1CC).

## Integrantes
- André Debiazzi Baldi Negrini - rm569062
- Kaique da Silva Assis - rm572718
- Vinicius Cristal de Oliveira -rm572049

## Público e problema
Famílias de baixa renda ligadas à rede elétrica que sentem o peso da conta de luz. A tarifa residencial deve subir em média 8,6% em 2026 (ANEEL) e a família não sabe onde está o gasto nem se vale a pena investir em energia solar.

## Funcionalidades de energia
O assistente responde, em linguagem simples e com a base do cálculo:
- quais aparelhos mais gastam energia e quanto custam;
- quanto se economiza trocando lâmpadas por LED, reduzindo o banho e eliminando o standby;
- se vale a pena instalar energia solar (com o consumo informado pelo usuário);
- comparação entre eficiência, solar e as duas juntas, em 10 anos;
- bandeiras tarifárias, Tarifa Social, impacto ambiental, fontes e limitações.

## Como executar
1. Abra o arquivo `colab_energia.ipynb` no Google Colab.
2. Execute a célula. A análise aparece e depois o assistente abre uma conversa.
3. Digite perguntas como "quais aparelhos gastam mais?" ou "vale a pena solar? minha conta é 300 kWh". Digite `sair` para encerrar.

## Resultados (casa de referência: 4 pessoas, 276 kWh/mês)
| | Eficiência | Solar | Eficiência + solar |

| Investimento | R$ 89 | R$ 12.375 | R$ 9.989 |
| Economia por mês | R$ 53 | R$ 255 | R$ 260 |
| Retorno | ~2 meses | ~3,9 anos | ~3,1 anos |

## Limitações
Os valores são estimativas baseadas em uma casa hipotética. Dados marcados como "estimado" no código são premissas do nosso grupo. Tarifa, preço do sistema solar, sol local e regras (Fio B, Tarifa Social) mudam o resultado.

## Pastas
- `codigo/` código do assistente
- `docs/` justificativas, referências, resultados e testes com usuários
