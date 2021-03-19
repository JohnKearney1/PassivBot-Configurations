# PassivBot-Configurations

Repository of PassivBot configurations, given by the community for public use.
Use at your own risk! Some configurations may have backtest data, some may not.

This repository depends upon [Passivbot_futures](https://github.com/enarjord/passivbot_futures) by [@enarjord](https://github.com/enarjord/passivbot_futures/wiki).

Message me on [Telegram](https://t.me/JohnKearney1) or [Email Me](mailto:john@kearneyjohn.com) for repository access or to submit backtest data / live results. Please see the Formatting section for information on how to submit information.

Thanks to [@bingining](https://github.com/bingining) and [@enarjord](https://github.com/enarjord) for contributing and helping maintain this repository!


# Formatting

Files are stored correspondent to their version. Each sub-folder represents a single backtest and / or live_settings file. Configurations are compatible with their major version number, and may be forwards compatible. More information on versioning can be found at the [passivbot_futures Wiki](https://github.com/enarjord/passivbot_futures/wiki/Versions).

### Backtest Results

When submitting backtest results, you should commit the raw folder or [Email Me](mailto:john@kearneyjohn.com) a .zip archive of the information. These are some of the files we like you to include:

- `average_daily_gain_plot.png` (**Required**)
- `backtest_1of7.png` (Suggested)
- `backtest_2of7.png` (Suggested)
- `backtest_3of7.png` (Suggested)
- `backtest_4of7.png` (Suggested)
- `backtest_5of7.png` (Suggested)
- `backtest_6of7.png` (Suggested)
- `backtest_7of7.png` (Suggested)
- `backtest_result.txt` (Suggested)
- `best_result.json` (**Required**)
- `live_config.json` (**Required**)
- `market_specific_settings` (Optional)
- `pnlcumsum_plot.png` (**Required**)
- `pos_sizes_plot.png` (**Required**)
- `whole_backtest.png` (**Required**)
- `/backtest_trades/` (Do Not Include)

To find configurations for your version of PassivBot, check the associated *major* version number, and find the subfolder for your exchange. Configurations are in folders labeled by the traded asset or symbol, and subfolders contain individual backtests. These backtest subfolders can be named anything you like, so long as it is descriptive. Example: `dot_20210309_20_days_liq_10%_adg_8%`.

### Live Results

To submit the live performance results of a backtested configuration, utilize [this template spreadsheet](https://docs.google.com/spreadsheets/d/1CulOl_UiXZWFxZi4FX844FBmdeonEzYK7hqiKxFtDc8/edit?usp=sharing). Please submit the completed `.xlsx`, and optionally include a link to a [Google Sheets](https://docs.google.com/spreadsheets/d/1CulOl_UiXZWFxZi4FX844FBmdeonEzYK7hqiKxFtDc8/edit?usp=sharing) view.

For an example of what the functioning spreadsheet looks like, [click here!](https://docs.google.com/spreadsheets/u/1/d/e/2PACX-1vRHWbAfI-XeOPhtyz84ifIIh76q4qlbSb1FdmITiC_Z2txaH-LiiEqvOfwBgEOTOPYSa_l9hA8_tYoi/pubhtml#)

If you would like to simply upload the end result of your test, not the entire test data, use the formatting below, or share the appropriate data with us!

**Note 1:** *The details of each live run can be found on the corresponding configuration links.*

**Note 2:** *These live results make no guarantee of profit or loss. Use at your own discretion and liability.*

#### Binance Live Results
|    Config        |  Start balance |   End balance  |   Comment   |
|------------------|:--------------:|-----------------:|-----------------:|
| [ada_20210309_20_days_liq_18%_adg_8%](https://github.com/JohnKearney1/PassivBot-Configurations/blob/main/v2.0.0/binance/ADAUSDT/ada_20210309_20_days_liq_18%25_adg_8%25) |    2021-03-10T16:46 start with	107.67      | 2021-03-19T17:45 end with 58.04 | drawdown too high |
| [ltc_20210309_20_days_liq_10.5%_adg_15.5%](https://github.com/JohnKearney1/PassivBot-Configurations/blob/main/v2.0.0/binance/LTCUSDT/ltc_20210309_20_days_liq_10.5%25_adg_15.5%25) |    2021-03-11T22:30 start with	100.00    |  | |
| [dot_20210309_20_days_liq_10%_adg_8%](https://github.com/JohnKearney1/PassivBot-Configurations/blob/main/v2.0.0/binance/DOTUSDT/dot_20210309_20_days_liq_10%25_adg_8%25) |    2021-03-10T12:31 start with	110.62   |  | |
| [sxp_20210309_20_days_liq_10%_adg_21%](https://github.com/JohnKearney1/PassivBot-Configurations/blob/main/v2.0.0/binance/SXPUSDT/sxp_20210309_20_days_liq_10%25_adg_21%25) |    2021-03-10T17:30 start with	100.00   |  | |
| [19_day_nostops_closest_liq_10%_adg_36%](https://github.com/JohnKearney1/PassivBot-Configurations/tree/main/v2.0.0/binance/LITUSDT/19_day_nostops_closest_liq_10%25_adg_36%25) |    2021-03-11T22:30 start with	100.00   |  | |

#### Bybit Live Results
|    Config        |  Start balance |   End balance   |   Comment   |
|------------------|:--------------:|-----------------:|-----------------:|
| [eos_20210310_10_days_liq_12%_adg_5%](https://github.com/JohnKearney1/PassivBot-Configurations/tree/main/v2.0.0/bybit/EOSUSD/eos_20210310_10_days_liq_12%25_adg_5%25) |    2021-03-11T10:00 start with	12.11   | 2021-03-14T09:53 end with 9.07 | Not stable |
| [btc_20210312_60_days_liq_12.9%_adg_3.7%](https://github.com/JohnKearney1/PassivBot-Configurations/blob/main/v2.0.0/bybit/BTCUSD/btc_20210312_60_days_liq_12.9%25_adg_3.7%25) |    2021-03-13T10:12 start with	0.00100037   | 2021-03-16T10:00 end with	0.00097793 | profit too low  |
