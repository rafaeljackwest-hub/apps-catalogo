# Catálogo dos apps da casa
`apps.json` é a fonte única da aba "Nossos apps" de todos os apps. Campos: chave, nome, descricao, icone, cor, busca_loja, id_apple, id_android, no_ar_ios, no_ar_android. Só renderizar os `no_ar_*` true da plataforma. Ao aprovar um app numa loja: virar a chave, subir `versao`, commit + push.
