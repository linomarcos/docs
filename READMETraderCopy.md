![Aegon Logo](https://avatars1.githubusercontent.com/u/50140594?s=200&v=4)

# Aegon Forex Trade Bot Replicator

## Experts

On experts folder you will find 2 scripts that must be installed in the MT4 or MT5. You can run this experts in the same machine, but you need multiple instalations of MT4 or MT5 (one per each slave/client and one per each master/trader).

To install the expert follow thouse steps:
- First of all install the MT platform, open and login with a user account.
- Then access the Navigator window and click with the right mouse button on Expert Adivisors and select the option "Create on MetaEditor".
- 2 new windows will open, the first on the front asks what type of script do you want to create (close this one).
- The MetaTrader Editor window must be opened now.
- The MetaTrader Editor has his own Navigator window, go on the folder Experts and right-click with the mouse, go to open folder option.
- Copy the experts file of this project inside the opened folder.
- Close all windows, return to MetaTrader, and refresh the Navigator.
- Open any Graphic Window of any forex relation, drag and drop the expert you want to execute on this MetaTrader instalation. (TradeCopyMaster) for trader and (TradeCopySlave) for client.
- Insert the client settings on mongodb collections (bots and trading_bots)
