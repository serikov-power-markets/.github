### Power markets · Mikhail Serikov

Power and gas markets: prices and forecasts, storage and asset valuation, hedging and portfolio risk.
Self-directed research studies on public data by [Mikhail Serikov](https://github.com/michaelserikov) (M.Sc. Ocean and Climate Physics, Universität Hamburg). Each README states what is observed, what is assumed and how the results were checked.

#### Prices, PPAs and hedging
- **[de-power-market-ppa](https://github.com/serikov-power-markets/de-power-market-ppa)** (flagship): German capture prices and PPA valuation, merit-order model, battery arbitrage, day-ahead price forecasting and battery scheduling under price uncertainty (CVaR, EVPI, VSS)
- [energy-hedging-risk](https://github.com/serikov-power-markets/energy-hedging-risk): supplier hedging strategies, structured products (tolling, gas swing, PaP) and VaR/ES backtests on modelled German forward curves
- [energy-book-risk](https://github.com/serikov-power-markets/energy-book-risk): marks, P&L attribution, limits and VaR/ES backtests of an illustrative TTF book through the 2021-2023 crisis

#### Storage and flexibility
- [de-battery-multimarket](https://github.com/serikov-power-markets/de-battery-multimarket): a battery across aFRR capacity, day-ahead and intraday markets (MILP)
- [eu-gas-storage-valuation](https://github.com/serikov-power-markets/eu-gas-storage-valuation): intrinsic and extrinsic value of seasonal gas storage (LP, least-squares Monte Carlo), German storage fundamentals
- [de-site-energy-management](https://github.com/serikov-power-markets/de-site-energy-management): forecast-based energy management of an industrial site (load, cooling and PV forecasts, MPC with a demand charge)

#### Forecasting and asset volume
- [de-weather-to-power](https://github.com/serikov-power-markets/de-weather-to-power): day-ahead wind and solar generation forecasts from ICON, ECMWF and AIFS, priced at imbalance prices
- [de-wind-solar-nowcast](https://github.com/serikov-power-markets/de-wind-solar-nowcast): intraday nowcasts 15 min to 6 h ahead from live generation and station data
- [renewable-asset-yield](https://github.com/serikov-power-markets/renewable-asset-yield): wind and solar asset models from reanalysis to P50/P90 expected volume (PyWake, pvlib)
- [de-price-forecast-service](https://github.com/serikov-power-markets/de-price-forecast-service): day-ahead price forecasts as a service (PyTorch, FastAPI, Docker, CI, drift monitoring); live [page](https://huggingface.co/spaces/michaelserikov/de-price-forecast) and [API](https://de-price-forecast.onrender.com/)

**Related:** adequacy and system planning in [serikov-energy-systems](https://github.com/serikov-energy-systems)
