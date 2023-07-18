# Dicionário de dados

A base de dados de treinamento contém 29 colunas, sendo que 28 delas são colunas de features e uma coluna target. Seus nomes são auto-explicativos, mas, caso haja alguma dúvida, a descrição das colunas é:

| nome | descrição |
| - | - |
| **id**| Contém o identificador único dos veículos cadastrados na base de dados
|**num_fotos**| contém a quantidade de fotos que o anuncio do veículo contém
|**marca**| Contém a marca do veículo anunciado
|**modelo**| Contém o modelo do veículo anunciado
|**versao**| Contém as descrições da versão do veículo anunciando. Sua cilindrada, quantidade de válvulas, se é flex ou não, etc.
|**ano_de_fabricacao**| Contém o ano de fabricação do veículo anunciado
|**ano_modelo**| Contém o modelo do ano de fabricação do veículo anunciado
|**hodometro**| Contém o valor registrado no hodômetro do veículo anunciado
|**cambio**| Contém o tipo de câmbio do veículo anunciado
|**num_portas**| Contém a quantidade de portas do veículo anunciado
|**tipo**| Contém o tipo do veículo anunciado. Se ele é sedã, hatch, esportivo, etc.
|**blindado**| Contém informação se o veículo anunciado é blindado ou não
|**cor**| Contém a cor do veículo anunciado
|**tipo_vendedor**| Contém informações sobre o tipo do vendedor do veículo anunciado. Se é pessoa física (PF) ou se é pessoa jurídica (PJ)
|**cidade_vendedor**| Contém a cidade em que vendedor do veículo anunciado reside
|**estado_vendedor**| Contém o estado em que vendedor do veículo anunciado reside
|**anunciante**| Contém o tipo de anunciante do vendedor do |veículo anunciado. Se ele é pessoa física, loja, concessionário, etc
|**entrega_delivery**| Contém informações se o vendedor faz ou não delivery do veículo anunciado
|**troca**| Contém informações o veículo anunciado já foi trocado anteriormente
|**elegivel_revisao**| Contém informações se o veículo anunciado precisa ou não de revisão
|**dono_aceita_troca**| Contém informações se o vendedor aceita ou não realizar uma troca com o veículo anunciado
|**veiculo_único_dono**| Contém informações o veículo anunciado é de um único dono
|**revisoes_concessionaria**| Contém informações se o veículo anunciado teve suas revisões feitas em concessionárias
|**ipva_pago**| Contém informações se o veículo anunciado está com o IPVA pago ou não
|**veiculo_licenciado**| Contém informações se o veículo anunciado está com o licenciamento pago ou não
|**garantia_de_fábrica**| Contém informações o veículo anunciado possui garantia de fábrica ou não
|**revisoes_dentro_agenda**| Contém informações se as revisões feitas do veículo anunciado foram realizadas dentro da agenda prevista
|**veiculo_alienado**| Contém informações se o veículo anunciado está alienado ou não
|**preco (target)**| Contém as informações do preço do veículo anunciado