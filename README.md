Este DASHBOARD construido en Power Bi corresponde a una herramienta para ayudar en el análisis de criptomonedas. Los datos se obtuvieron a través de la API de FTX. 

Para la construcción se utilizaron 9 de las monedas más representativas del mercado, adicional a la moneda nativa de FTX. Estas se trabajan con la conversión a USD y corresponden a:
* Bitcoin (BTC/USD)
* Ethereum (ETH/USD)
* Tether (USDT/USD)
* Binance (BNB/USD)
* XRP (XRP/USD)
* Cardano(ADABULL/USD)
* Solana (SOL/USD)
* Dogecoin (DOGE/USD)
* Polkadot (DOT/USD)
* FTX Token (FTT/USD)


Para trabajar con estas monedas se trajo de la API: 
1. Los datos históricos diarios para cada moneda desde el 2019 hasta la fecha actual. Las columnas a trabajar sobre la tabla de consulta son:
* startTime: Fecha de consulta
* open: Precio de apertura
* high: Precio mas alto del día
* low: Precio mas bajo del día
* close: Precio de cierre
* volume: Volumen de ventas

2. La información de market, para buscar el precio actual de la moneda. De esta tabla solo se trabajo con las columnas:
* name: Nombre de la moneda
* price: Precio actual del mercado



