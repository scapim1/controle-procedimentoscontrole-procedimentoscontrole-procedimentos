# Informativo Diário de Clipping Jurídico-Policial — Região do Xingu/PA

Pasta com os informativos diários gerados automaticamente, cobrindo o recorte
geográfico e temático definido pelo usuário (titular: thiago.scapim@gmail.com).

## Recorte geográfico prioritário
Altamira, Anapu, Brasil Novo, Medicilândia, Pacajá, Porto de Moz, Senador José
Porfírio e Vitória do Xingu — além de cobertura estadual (Pará) para operações
da Polícia Federal e órgãos de controle.

## Temas monitorados
- Crimes contra a administração pública (corrupção, peculato, fraude em
  licitação, desvio de verbas, improbidade, lavagem de capitais).
- Atuação política com reflexo criminal (denúncias contra prefeitos/vereadores,
  afastamentos, cassações, CPIs).
- Crimes ambientais (desmatamento, garimpo, grilagem, extração ilegal de
  madeira, invasão de terras indígenas/UCs).
- Atribuições da Polícia Federal (crimes federais, terras indígenas, recursos
  da União, tráfico interestadual, fraudes bancárias).
- Operações da PF em todo o Pará.
- Ações de CGU, MPF, MPPA, GAECO, TCU, TCE-PA, TCM-PA, Ibama, ICMBio e Receita
  Federal.

## Regras de rigor aplicadas em cada edição
- Nenhum fato, nome, número ou link é inventado.
- Seção sem notícia confirmada recebe "Sem registros nas últimas 24h".
- Fato confirmado oficialmente é distinguido de alegação/denúncia não apurada.
- Presunção de inocência: usa-se "investigado"/"suspeito", nunca "criminoso".
- Nenhum dado pessoal além do publicado pela fonte original.
- Fontes de baixa confiabilidade ou sem confirmação oficial são sinalizadas.
- Desdobramentos de informativos anteriores são indicados como tais; fatos já
  publicados não são repetidos sem novidade.

## Limitação conhecida
Buscas automatizadas têm cobertura limitada de redes sociais (ex.: Reels do
Instagram não são indexados). A base do informativo são portais de notícia e
sites oficiais (gov.br/pf, MPF, CGU, TCM-PA, TCE-PA, TJPA, TRF1, G1 Pará, O
Liberal, Diário do Pará, Agência Pará, Confirma Notícia, DOL, A Voz do Xingu
(avozdoxingu.com.br — portal local com cobertura por município da Região do
Xingu) e similares).

## Geração automática
Um gatilho diário (horário de referência: ~07:00, horário de Brasília) executa
a pesquisa e grava um novo arquivo `AAAA-MM-DD.md` nesta pasta, com commit e
push para a branch `claude/optimistic-archimedes-ul2lwb`. Cada edição também é
publicada como documento Claude, com o link registrado no próprio arquivo.
