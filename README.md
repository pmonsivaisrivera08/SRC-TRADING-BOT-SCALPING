Bot de Trading de Scalping en Python
Python Scalping Trading Bot
This Python script implements a scalping trading bot designed to operate in financial markets, with a focus on assets like Bitcoin (BTC-USD). The bot uses an advanced strategy based on analyzing multiple technical indicators to identify high-frequency trading opportunities.

Key Features
Multi-Indicator Strategy: The strategy logic combines several key technical indicators to generate buy signals:

Moving Averages (MA): It uses a bullish crossover between a short-period moving average (short MA) and a long-period moving average (long MA).

Relative Strength Index (RSI): It ensures the asset is not in an overbought condition.

Moving Average Convergence Divergence (MACD): It confirms the buy signal with a bullish crossover between the MACD line and the signal line.

Bollinger Bands: It includes these bands to provide context on price volatility.

Detailed Backtesting: The bot includes a backtesting engine that allows you to simulate the strategy with historical data. The results report includes metrics such as:

Total return.

Number of trades.

Win rate.

Maximum drawdown.

Risk Management: The strategy incorporates automatic stop-loss and take-profit orders to manage the risk of each trade.

Data Source Options: It allows you to get historical price data from different sources, including Yahoo Finance and the CCXT library to connect to cryptocurrency exchanges.

Simulation and Live Mode: The script can be run in a simulation mode for testing or a live mode for market trading (requires API key configuration).

Important Warning
This code was created for educational purposes and should not be used for trading with real money without thorough validation and testing, as trading in financial markets carries a high risk of loss.

____________________________________________________________________________
Este script de Python implementa un bot de trading de scalping diseñado para operar en mercados financieros, enfocado en activos como Bitcoin (BTC-USD). El bot utiliza una estrategia avanzada basada en el análisis de múltiples indicadores técnicos para identificar oportunidades de trading de alta frecuencia.

Características principales
Estrategia Mult-Indicador: La lógica de la estrategia combina varios indicadores técnicos clave para generar señales de compra:

Medias Móviles (MA): Utiliza un cruce alcista entre una media móvil de período corto (MA corta) y una de período largo (MA larga).

Índice de Fuerza Relativa (RSI): Asegura que el activo no esté en una condición de sobrecompra.

Divergencia de Convergencia de Medias Móviles (MACD): Confirma la señal de compra con un cruce alcista entre la línea MACD y la línea de señal.

Bandas de Bollinger: Incluye estas bandas para proporcionar contexto sobre la volatilidad del precio.

Backtesting Detallado: El bot incluye un motor de backtesting que permite simular la estrategia con datos históricos. El informe de resultados incluye métricas como:

Retorno total.

Número de operaciones.

Tasa de victorias.

Drawdown máximo.

Gestión de Riesgo: La estrategia incorpora stop-loss y take-profit para gestionar el riesgo de cada operación de manera automática.

Opciones de Fuente de Datos: Permite obtener datos de precios históricos de diferentes fuentes, incluyendo Yahoo Finance y la biblioteca CCXT para conectarse a exchanges de criptomonedas.

Modo de Simulación y Real: El script puede ser ejecutado en un modo de simulación para pruebas o en un modo real para operar en el mercado (requiere la configuración de claves de API).

Advertencia Importante
Este código fue creado con fines educativos y no debe ser utilizado para operar con dinero real sin una validación y pruebas exhaustivas, ya que el trading en los mercados financieros conlleva un alto riesgo de pérdida.
