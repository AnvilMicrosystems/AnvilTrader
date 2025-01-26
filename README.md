# AnvilTrader

AnvilTrader is a Windows desktop app for Kalshi traders. It's in alpha and currently has two modules:


### High Temp

<img src="./docs/high temp demo.gif" width="50%" />

All-in-one view for any of Kalshi's *Highest temperature in {city} {today|tomorrow}* markets

* Live readings (METARs) from the underlying station
* Realtime market prices and detailed orderbook data
* Kalshi brackets visually displayed
* Forecasts from various models
* Historical temperature on this day in past years. This is useful for seeing when the high for the day has been in the past and how steeply it can climb.
* 6-hour highs plotted
* Celsius temps (with correct conversion + rounding) overlaid on Kalshi brackets. C-F conversion is one of the traps for new players.


### PnL
<img src="./docs/PnL demo.gif" width="50%" />
Plot, export your complete profit and loss history

* Win\loss ratio
* Includes trades, fees, interest, credits (e.g. rebates), refunds, deposits, withdrawals
* Filter by date
* Plot by year, month, week, day. Plot by Series.
* Export data to clipboard for custom analysis

  
# Download
[AnvilTraderBootstrapper.exe](https://github.com/AnvilMicrosystems/AnvilTrader/releases/download/packages/AnvilTraderBootstrapper.exe)

# Frequently Asked Questions
### Is it free?
Yes. Though I would appreciate any feedback to help me decide whether or not to continue working. See contact options below.
### Windows Defender says I shouldn't run it...?
I'm starting simple and the installer is an unsigned binary without any reputation yet, so Windows makes it difficult to install. If you don't want to click 'Run anyway' that is understandable. If this project takes off then I'll get a cert to make Windows feel better about it.
### It's asking for an API key. How do I create one?
Kalshi requires 3rd-party apps to authenticate with an API key. Creating one is simple. [Here's a guide.](./docs/apikeyhowto.md)
### Why is PnL so slow the first time?
Depending on how many orders you've placed, downloading your entire trading history can take a while. After this initial pull it's much faster since it just needs to get recent data.


# Contact
Email: <anvilmicrosystems@hotmail.com>  
Discord: <https://discord.gg/P29e3BweDW>
