# Basic knowledge

## option trading

- trading strategy where traders can speculate on price movement wihtout own the underlying asset

- option contract:
  gives holder the right (but not obligation)
  to buy (call option), before option expries, (when they expect price rise)
  or sell (put option), before option expires, (when they expect price fall)
  a specific amount of crypto
  at predetermined price (strike price)
  within a period of time

- Buying Call Options
  Traders buy call options if they believe the price of an asset will rise.
  If the price does go up above the strike price plus the premium paid, they can profit by selling the option at a higher price or exercising it to buy the asset at a lower price than the current market price.

- Buying Put Options
  Traders buy put options if they believe the price of an asset will fall.
  If the price does drop below the strike price minus the premium paid, they can profit by selling the option at a higher price or exercising it to sell the asset at a higher price than the current market price.

- Selling Call Options
  Traders can sell call options (write calls) if they believe the price of the asset will not rise above the strike price.
  They collect the premium upfront and keep it as profit if the option expires worthless.

- Selling Put Options
  Traders can sell put options (write puts) if they believe the price of the asset will not fall below the strike price.
  They collect the premium and keep it as profit if the option expires worthless.

## future trading

- future contract:
  aggrement
  to buy, (long position)
  or sell, (short position)
  specific amount of crypto, (leverage)
  at predetermined price (future or strike price)
  at a specified time in future (expiration date)

## perpetual trading

- future contract without expiration date
  with funding rate: exchanged between long & short positions (periodically)
  with leverage
  margin & liquidation
  use mark price which is based on average of spot market prices from several exchanges

## Hedging

risk management strategy used to reduce risk of adverse price movement

- Futures Contracts:
  Buying or selling futures contracts to lock in prices for future transactions, thereby protecting against price fluctuations.

- Options Contracts:
  Buying put options to hedge against potential price declines or buying call options to hedge against potential price increases.

- Forward Contracts:
  Similar to futures contracts but customized between two parties, often used in over-the-counter (OTC) markets.

- Swaps:
  Swapping cash flows or assets with another party to manage exposure to fluctuations in interest rates, currencies, or commodity prices.

- Natural Hedges:
  Using operational strategies or diversification to naturally offset risks, such as sourcing materials from multiple suppliers to mitigate supply chain disruptions.

# Spot Trading

- buy or sell crypto assets immediately
- you have direct onwership of cryptocurrency
- based on orderbook

# Margin Trading

- Spot Trading + Leverage

- market: OrderBook (Spot Market)
- BTC/USDT (real 2 asset)
- marketPrice = spot price

# Future Trading

- futures are contracts that represent valut of currency.
- you do not owner underlying cryptocurrency when purchase a future contract.
- instead, you own contract under which you agreed to buy/sell at

- market: spot market
- BTC/USDC (only one USDC asset)
- Liquidation
- marketPrice = index price
- Mark Price = latest ordered price

# Perpetual Trading

- Same with General Future Trading
- But no expiration or settlement of Perpetual Contracts.
- Use `Funding` for convergence between Perpetual Contract and Mark Price.

## Mark Price

To avoid market manipulation & ensure that Perpetual Contract is price-matched to the Spot Price, utilize `Mark Price` to calculate PnL for all traders

## Fundling

- if `FundlyingRate` is positive, long pay to short (and vice in versa)
- calculated based on differecen between perpetual contract price & spot price
- when bull market, fundingRate is positive and tends to rise (and vice in versa)
- formula
  `Funding Amount = Nominal Value of Positions * Funding Rate`
  `(Nominal Value of Positions = Mark Price * Size of a Contract)`

# Spot VS Future

## Leverage

- No levearge on Spot, but support on Future

## Profit

- In spot, you earn when price rises
- In future, use long/short position to get profies when both price goes up or down

## Liquidity

- Future market liquidity > spot market liquidity

## Price

- `Spot Price`: price for all txs in spot market
- Futuer Price: prevailing spot price + future premium (future premium can be positive or negative)

https://www.binance.com/en/support/faq/what-are-the-differences-between-spot-trading-and-futures-trading-360033162052

# Position

- Long: belives will rise & buy now
- Short: believes will drop & sell now

# Order Types

## Take-profit (T/P)

limit orders that are closed when a specified profit level is reached

## TP Order

limit orders that are closed when reached to specific profit level

## Stop Losse:

orders that will buy/sell when reaches to the specific price
