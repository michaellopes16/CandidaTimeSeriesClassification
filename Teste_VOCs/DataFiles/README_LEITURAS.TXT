Foram obtidas junto ao Departamento de Micologia três culturas de Cândias: Albicans, Krusei e Parapsilogis.

Após 24hs de crescimento das culturas as placas de Petri foram analisadas no nariz artificial

A organização dos arquivos segue a seguinte lógica:
---------------------------------------------------
- Os arquivos da albicans (albicans.csv, albicans2.csv e albicans3.csv) possuem leitura de dez ciclos. Cada ciclo possui uma etapa se aspiração do conteúdo da placa de Petri para a câmara de sensores por 20s. Após isso, ocorre uma espera de 60s para estabilização/interação do sinal dos sensores com os voláteis aspirados para dentro da câmara. Por fim, ar filtrado é injetado dentro da câmara por 60s forçando a saída da massa de ar previamente aspirada. Portanto, um ciclo corresponde à 140s e com três leitura por segundo, gerando dez curvas (pois existem dez sensores no nariz) com aproximadamente 420 pontos. Entre a realização de cada ciclo existe uma espera de 60s para que a amostra não sature, ou seja, para que mais VOCs sejam liberados/produzidos pela amostra e esses dados não são armazenados em arquivo, apenas aqueles gerados dentro do ciclo.

- As mesmas quantidades de ciclos foram realizadas para a C. krusei e C. parapsilosis, seguindo a lógica de nomenclatura de arquivo da albicans.csv

ARQUIVOS DE TESTES
- O albicans_dia2.csv possuí leituras de 30 ciclos de C. Albicans, porém realizadas com 48hs após a cultura.
- O krusei_dia2.csv possuí leituras de 20 ciclos C. krusei, porém realizados com 49hs após a cultura
- Os arquivos parapisilosis_dia2.csv e parapsilosis_dia3 possuem leituras de 10 ciclos cada da C. Parapsilosis realizadas após 48hs de cultura.

EXISTEM MARCAÇÕES NOS ARQUIVOS DE INÍCIO E FIM DE LEITURA JUNTO COM UM CONTADOR.