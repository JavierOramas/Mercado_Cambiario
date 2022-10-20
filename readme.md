# Simulación del mercado informal de divisas en Cuba

Para la simulacion fueron tomados los datos de eltoque.com

se tomaron los 300 primeros registros como baseline

luego se generaron acorde a distintas distribuciones agentes que seran los encargados de comprar/vender divisas en este mercado

la distribucion es utilizada para definir si un agente es especulador, desesperado o neutral, alterando positiva o negativamente el precio observado en las 2 primeras circunstancias

se simularon un total de 700 dias con 500 agentes, siendo las distribuciones que mejores resultados dieron las distribuciones Nomal con sesgo positivo (skewnorm) y exponencial

