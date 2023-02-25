# 20230226 00:26:02

## /root/FIL/strategy/amihud/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=993672.4896432, self.flagDict['side']='sell', self.tradeCount=2, self.count=26044
self.closeSec=1677341999, self.tradeDate='20230226', self.openTime='001500', self.closeTime='001959', self.symbol='BTCUSDT', self.open=23067.0, self.close=23038.2, self.high=23067.0, self.low=23028.0, self.vol=1252.376, self.amt=28869744.7206 
127.0.0.1 - - [26/Feb/2023 00:20:01] "POST / HTTP/1.1" 200 -
2023-02-26 00:20:02,023:INFO:amihud:main.py:172:handleKline:200676: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5759  20230225   235500    235959  ...         0.0        0.0       0
5760  20230226   000000    000459  ...         0.0        0.0       0
5761  20230226   000500    000959  ...         0.0        0.0       0
5762  20230226   001000    001459  ...         0.0        0.0       0
5763  20230226   001500    001959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-02-26 00:20:02,027:INFO:amihud:main.py:175:handleKline:200676: self.closeSec=1677341999, self.tradeDate='20230226', self.openTime='001500', self.closeTime='001959',self.symbol='BTCUSDT',self.open=23067.0, self.close=23038.2, self.high=23067.0, self.low=23028.0, self.vol=1252.376, self.amt=28869744.7206, ukdf['pct'].iloc[-1]=-0.001249 , ukdf['amount'].iloc[-1]=28869744.7206, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5763, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '60.176', 'enterprice': '16529.3', 'countrevence': '0', 'unrealprofit': '-391637.4432', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '23037.5', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1
127.0.0.1 - - [26/Feb/2023 00:25:01] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=993672.4896432, self.flagDict['side']='sell', self.tradeCount=2, self.count=26045
self.closeSec=1677342299, self.tradeDate='20230226', self.openTime='002000', self.closeTime='002459', self.symbol='BTCUSDT', self.open=23038.2, self.close=23019.5, self.high=23049.6, self.low=23011.1, self.vol=880.573, self.amt=20280592.5291 
2023-02-26 00:25:01,628:INFO:amihud:main.py:172:handleKline:200676: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5760  20230226   000000    000459  ...         0.0        0.0       0
5761  20230226   000500    000959  ...         0.0        0.0       0
5762  20230226   001000    001459  ...         0.0        0.0       0
5763  20230226   001500    001959  ...         0.0        0.0       0
5764  20230226   002000    002459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-02-26 00:25:01,628:INFO:amihud:main.py:175:handleKline:200676: self.closeSec=1677342299, self.tradeDate='20230226', self.openTime='002000', self.closeTime='002459',self.symbol='BTCUSDT',self.open=23038.2, self.close=23019.5, self.high=23049.6, self.low=23011.1, self.vol=880.573, self.amt=20280592.5291, ukdf['pct'].iloc[-1]=-0.000812 , ukdf['amount'].iloc[-1]=20280592.5291, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5764, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '60.176', 'enterprice': '16529.3', 'countrevence': '0', 'unrealprofit': '-390651.45299695568', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '23021.11489293', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1


## /root/FIL/strategy/factorcheck/log.txt ----- -----

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.8134770136541749, self.count=26610 

self.closeSec=1677341999, self.tradeDate='20230226', self.openTime='001500', self.closeTime='001959', self.symbol='BTCUSDT', self.open=23067.0, self.close=23038.2, self.high=23067.0, self.low=23028.0 
2023-02-26 00:20:01,698:INFO:factorcheck2:main.py:126:handleKline:185239: self.closeSec=1677341999, self.tradeDate='20230226', self.openTime='001500', self.closeTime='001959',self.symbol='BTCUSDT',self.open=23067.0, self.close=23038.2, self.high=23067.0, self.low=23028.0   
2023-02-26 00:20:01,797:INFO:factorcheck2:main.py:127:handleKline:185239: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1439  20230225   235500    235959  1677340799  ...  22967.0  0.001193   1727    5
1440  20230226   000000    000459  1677341099  ...  22994.9  0.000461   1440    0
1441  20230226   000500    000959  1677341399  ...  23007.0  0.000309   1441    1
1442  20230226   001000    001459  1677341699  ...  23014.2  0.002299   1442    2
1443  20230226   001500    001959  1677341999  ...  23028.0 -0.001249   1443    3

[5 rows x 11 columns]
2023-02-26 00:20:01,797:INFO:factorcheck2:main.py:128:handleKline:185239: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': False, 'isOpen': True, 'isClose': False, 'isTrig': True}
127.0.0.1 - - [26/Feb/2023 00:25:01] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.8134770136541749, self.count=26611 

self.closeSec=1677342299, self.tradeDate='20230226', self.openTime='002000', self.closeTime='002459', self.symbol='BTCUSDT', self.open=23038.2, self.close=23019.5, self.high=23049.6, self.low=23011.1 
2023-02-26 00:25:01,530:INFO:factorcheck2:main.py:126:handleKline:185239: self.closeSec=1677342299, self.tradeDate='20230226', self.openTime='002000', self.closeTime='002459',self.symbol='BTCUSDT',self.open=23038.2, self.close=23019.5, self.high=23049.6, self.low=23011.1   
2023-02-26 00:25:01,593:INFO:factorcheck2:main.py:127:handleKline:185239: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1440  20230226   000000    000459  1677341099  ...  22994.9  0.000461   1440    0
1441  20230226   000500    000959  1677341399  ...  23007.0  0.000309   1441    1
1442  20230226   001000    001459  1677341699  ...  23014.2  0.002299   1442    2
1443  20230226   001500    001959  1677341999  ...  23028.0 -0.001249   1443    3
1444  20230226   002000    002459  1677342299  ...  23011.1 -0.000812   1444    4

[5 rows x 11 columns]
2023-02-26 00:25:01,593:INFO:factorcheck2:main.py:128:handleKline:185239: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': False, 'isOpen': True, 'isClose': False, 'isTrig': True}


## /root/FIL/strategy/logic/log.txt ----- -----

     pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
539     0  0.541435  0.458565       0  ...  1.030757  -1.0    0.0  1.056609
540     0  0.523652  0.476348       1  ...  1.028677  -1.0    0.0  1.058741
541     0  0.542150  0.457850       0  ...  1.030802  -1.0    0.0  1.056554
542     0  0.525672  0.474328       1  ...  1.029995  -1.0    0.0  1.057381
543     0  0.531061  0.468939       0  ...  1.030537  -1.0    0.0  1.056825

[5 rows x 10 columns]
2023-02-26 00:00:34,106:INFO:logic:main.py:478:getModel:885513: df_panel.iloc[-5:,:] :
    pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
45     0  0.541896  0.458104       0  ...  1.005648   1.0    0.0  1.057620
46     0  0.524471  0.475529       1  ...  1.007677   1.0    0.0  1.059871
47     0  0.542947  0.457053       0  ...  1.005595   1.0    0.0  1.057681
48     0  0.526072  0.473928       1  ...  1.006383   1.0    0.0  1.058164
49     0  0.531061  0.468939       0  ...  1.030537  -1.0    0.0  1.056825

[5 rows x 10 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '32.95', 'enterprice': '23067.1', 'countrevence': '0', 'unrealprofit': '-2145.045', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '23002', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
handlebackTrade > queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '32.95', 'enterprice': '23067.1', 'countrevence': '0', 'unrealprofit': '-2145.045', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '23002', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
2023-02-26 00:00:39,741:INFO:logic:main.py:500:queryContractAssets:885513: queryContractAssets: assets=ContractAssetReturn{'result': [ContractAsset{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'asset': 'USDT', 'free': '759385.464221', 'total': '759385.464221', 'margin': '0', 'unreal': '0', 'type': 'AssetType_ucontract'}]}
2023-02-26 00:00:39,924:INFO:logic:main.py:587:openSell:885513: ret = self.client.insertMarketUOrder("simulator", "BTCUSDT", 32.922, "sell"), ret=InsertOrderReturn{'result': 'success', 'clientorderid': '41836F1677340839923I0L64'}
2023-02-26 00:00:39,938:INFO:logic:main.py:494:insertFactor:885513: curDateTime:2260000, name:logic, symbol:BTCUSDT, tradeDate:20230225, closeTime:235959, close:22996.4, sign:-1, total:759385.464221, side:sell  
127.0.0.1 - - [26/Feb/2023 00:00:39] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [26/Feb/2023 00:00:39] "POST / HTTP/1.1" 200 -
2023-02-26 00:00:39,939:INFO:logic:main.py:661:handleOrderNew:885513: handleOrderNew: data=OrderType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'clientorderid': '41835F1677340834651I0L64', 'symbol': 'BTCUSDT', 'gatewayorderid': 1677340834751365, 'quantity': '32.95', 'price': '23001.9', 'stopprice': '0', 'ordertype': '', 'side': 'SELL', 'status': 'FILLED', 'positionside': 'SHORT', 'createtime': 1677340834381, 'updatetime': 1677340834751, 'tradetype': 'usdt', 'selfid': 41835, 'filltrades': [TradeType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'tradeid': 1677340834751, 'clientorderid': '41835F1677340834651I0L64', 'price': '23001.9', 'quantity': '32.95', 'commission': '757.912605', 'commissionasset': 'USDT', 'tradetime': 1677340834751, 'tradetype': 'usdt', 'gatetype': 'simulator', 'handletime': 1677340834751}], 'gatetype': 'simulator', 'handletime': 0}
2023-02-26 00:00:39,940:INFO:logic:main.py:664:handleOrderFilled:885513: handleOrderFilled: data=OrderType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'clientorderid': '41835F1677340834651I0L64', 'symbol': 'BTCUSDT', 'gatewayorderid': 1677340834751365, 'quantity': '32.95', 'price': '23001.9', 'stopprice': '0', 'ordertype': '', 'side': 'SELL', 'status': 'FILLED', 'positionside': 'SHORT', 'createtime': 1677340834381, 'updatetime': 1677340834751, 'tradetype': 'usdt', 'selfid': 41835, 'filltrades': [TradeType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'tradeid': 1677340834751, 'clientorderid': '41835F1677340834651I0L64', 'price': '23001.9', 'quantity': '32.95', 'commission': '757.912605', 'commissionasset': 'USDT', 'tradetime': 1677340834751, 'tradetype': 'usdt', 'gatetype': 'simulator', 'handletime': 1677340834751}], 'gatetype': 'simulator', 'handletime': 0}
2023-02-26 00:00:40,034:INFO:logic:main.py:661:handleOrderNew:885513: handleOrderNew: data=OrderType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'clientorderid': '41836F1677340839923I0L64', 'symbol': 'BTCUSDT', 'gatewayorderid': 1677340840017290, 'quantity': '32.922', 'price': '23001.3', 'stopprice': '0', 'ordertype': '', 'side': 'SELL', 'status': 'FILLED', 'positionside': 'SHORT', 'createtime': 1677340839752, 'updatetime': 1677340840017, 'tradetype': 'usdt', 'selfid': 41836, 'filltrades': [TradeType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'tradeid': 1677340840017, 'clientorderid': '41836F1677340839923I0L64', 'price': '23001.3', 'quantity': '32.922', 'commission': '757.2487986', 'commissionasset': 'USDT', 'tradetime': 1677340840017, 'tradetype': 'usdt', 'gatetype': 'simulator', 'handletime': 1677340840017}], 'gatetype': 'simulator', 'handletime': 0}
127.0.0.1 - - [26/Feb/2023 00:00:40] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [26/Feb/2023 00:00:40] "POST / HTTP/1.1" 200 -
2023-02-26 00:00:40,276:INFO:logic:main.py:664:handleOrderFilled:885513: handleOrderFilled: data=OrderType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'clientorderid': '41836F1677340839923I0L64', 'symbol': 'BTCUSDT', 'gatewayorderid': 1677340840017290, 'quantity': '32.922', 'price': '23001.3', 'stopprice': '0', 'ordertype': '', 'side': 'SELL', 'status': 'FILLED', 'positionside': 'SHORT', 'createtime': 1677340839752, 'updatetime': 1677340840017, 'tradetype': 'usdt', 'selfid': 41836, 'filltrades': [TradeType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'tradeid': 1677340840017, 'clientorderid': '41836F1677340839923I0L64', 'price': '23001.3', 'quantity': '32.922', 'commission': '757.2487986', 'commissionasset': 'USDT', 'tradetime': 1677340840017, 'tradetype': 'usdt', 'gatetype': 'simulator', 'handletime': 1677340840017}], 'gatetype': 'simulator', 'handletime': 0}


## /root/FIL/strategy/modifiedmom/log.txt ----- -----

2023-02-26 00:00:03,493:INFO:modifiedmom:main.py:319:handleOrderFilled:185213: handleOrderFilled: data=OrderType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'clientorderid': '41833F1677340803132I0L59', 'symbol': 'BTCUSDT', 'gatewayorderid': 1677340803250582, 'quantity': '43.769', 'price': '22996.5', 'stopprice': '0', 'ordertype': '', 'side': 'BUY', 'status': 'FILLED', 'positionside': 'LONG', 'createtime': 1677340802741, 'updatetime': 1677340803250, 'tradetype': 'usdt', 'selfid': 41833, 'filltrades': [TradeType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'tradeid': 1677340803250, 'clientorderid': '41833F1677340803132I0L59', 'price': '22996.5', 'quantity': '43.769', 'commission': '1006.5338085', 'commissionasset': 'USDT', 'tradetime': 1677340803250, 'tradetype': 'usdt', 'gatetype': 'simulator', 'handletime': 1677340803250}], 'gatetype': 'simulator', 'handletime': 0}
127.0.0.1 - - [26/Feb/2023 00:00:03] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=13304 

self.closeSec=1677341399, self.tradeDate='20230226', self.openTime='000000', self.closeTime='000959', self.symbol='BTCUSDT', self.open='22996.4', self.close='23014.1'
2023-02-26 00:10:01,622:INFO:modifiedmom:main.py:144:handleKline:185213: self.closeSec=1677341399, self.tradeDate='20230226', self.openTime='000000', self.closeTime='000959',self.symbol='BTCUSDT',self.open='22996.4', self.close='23014.1'
127.0.0.1 - - [26/Feb/2023 00:10:01] "POST / HTTP/1.1" 200 -
2023-02-26 00:10:01,636:INFO:modifiedmom:main.py:145:handleKline:185213: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
572  20230225   232000    232959  1677338999  22986.5  23008.5  0.000957
573  20230225   233000    233959  1677339599  23008.5  22984.6 -0.001039
574  20230225   234000    234959  1677340199  22984.6  22966.6 -0.000783
575  20230225   235000    235959  1677340799  22966.6  22996.4  0.001298
576  20230226   000000    000959  1677341399  22996.4  23014.1  0.000770
2023-02-26 00:10:01,642:INFO:modifiedmom:main.py:146:handleKline:185213: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=13305 

self.closeSec=1677341999, self.tradeDate='20230226', self.openTime='001000', self.closeTime='001959', self.symbol='BTCUSDT', self.open='23014.2', self.close='23038.2'
127.0.0.1 - - [26/Feb/2023 00:20:01] "POST / HTTP/1.1" 200 -
2023-02-26 00:20:01,680:INFO:modifiedmom:main.py:144:handleKline:185213: self.closeSec=1677341999, self.tradeDate='20230226', self.openTime='001000', self.closeTime='001959',self.symbol='BTCUSDT',self.open='23014.2', self.close='23038.2'
2023-02-26 00:20:01,708:INFO:modifiedmom:main.py:145:handleKline:185213: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
573  20230225   233000    233959  1677339599  23008.5  22984.6 -0.001039
574  20230225   234000    234959  1677340199  22984.6  22966.6 -0.000783
575  20230225   235000    235959  1677340799  22966.6  22996.4  0.001298
576  20230226   000000    000959  1677341399  22996.4  23014.1  0.000770
577  20230226   001000    001959  1677341999  23014.2  23038.2  0.001047
2023-02-26 00:20:01,709:INFO:modifiedmom:main.py:146:handleKline:185213: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False}


## /root/FIL/strategy/percentile_regression_step2/log.txt ----- -----

127.0.0.1 - - [21/Feb/2023 09:30:01] "POST / HTTP/1.1" 200 -
2023-02-21 09:30:03,026:DEBUG:percentile_regression_step2:main.py:154:get_signal:1265985: df_id.iloc[-5:,:] :
                 daytime     hms    close  ...  pct_10  pct_20  factor
144  2023/02/21 07:00:00  070000  24795.1  ...     NaN     NaN       0
145  2023/02/21 07:30:00  073000  24849.9  ...     NaN     NaN       0
146  2023/02/21 08:00:00  080000  24819.0  ...     NaN     NaN       0
147  2023/02/21 08:30:00  083000  24860.9  ...     NaN     NaN       0
148  2023/02/21 09:00:00  090000  24831.0  ...     NaN     NaN       0

[5 rows x 10 columns]
127.0.0.1 - - [21/Feb/2023 10:00:02] "POST / HTTP/1.1" 200 -
2023-02-21 10:00:03,553:DEBUG:percentile_regression_step2:main.py:154:get_signal:1265985: df_id.iloc[-5:,:] :
                 daytime     hms    close  ...  pct_10  pct_20  factor
144  2023/02/21 07:30:00  073000  24849.9  ...     NaN     NaN       0
145  2023/02/21 08:00:00  080000  24819.0  ...     NaN     NaN       0
146  2023/02/21 08:30:00  083000  24860.9  ...     NaN     NaN       0
147  2023/02/21 09:00:00  090000  24831.0  ...     NaN     NaN       0
148  2023/02/21 09:30:00  093000  24870.0  ...     NaN     NaN       0

[5 rows x 10 columns]
127.0.0.1 - - [21/Feb/2023 10:30:01] "POST / HTTP/1.1" 200 -
2023-02-21 10:30:03,245:DEBUG:percentile_regression_step2:main.py:154:get_signal:1265985: df_id.iloc[-5:,:] :
                 daytime     hms    close  ...  pct_10  pct_20  factor
144  2023/02/21 08:00:00  080000  24819.0  ...     NaN     NaN       0
145  2023/02/21 08:30:00  083000  24860.9  ...     NaN     NaN       0
146  2023/02/21 09:00:00  090000  24831.0  ...     NaN     NaN       0
147  2023/02/21 09:30:00  093000  24870.0  ...     NaN     NaN       0
148  2023/02/21 10:00:00  100000  24936.1  ...     NaN     NaN       0

[5 rows x 10 columns]


## /root/FIL/strategy/pyemd/log.txt ----- -----

2023-02-26 00:00:02,663:INFO:pyemd2:main.py:127:handleKline:185189: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}
2023-02-26 00:00:02,816:INFO:pyemd2:main.py:190:insertFactor:185189: curDateTime:2260000, name:pyemd2, symbol:BTCUSDT, tradeDate:20230225, closeTime:235959, close:22996.4, total:979069.1011917, pct_pre:-0.004677316956245625, thd:0.34805297730696894, side:sell 

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=13305 

self.closeSec=1677341399, self.tradeDate='20230226', self.openTime='000000', self.closeTime='000959', self.symbol='BTCUSDT', self.open='22996.4', self.close='23014.1'
2023-02-26 00:10:01,652:INFO:pyemd2:main.py:125:handleKline:185189: self.closeSec=1677341399, self.tradeDate='20230226', self.openTime='000000', self.closeTime='000959',self.symbol='BTCUSDT',self.open='22996.4', self.close='23014.1'
127.0.0.1 - - [26/Feb/2023 00:10:01] "POST / HTTP/1.1" 200 -
2023-02-26 00:10:01,670:INFO:pyemd2:main.py:126:handleKline:185189: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17420  20230225   232000    232959  1677338999  22986.5  23008.5
17421  20230225   233000    233959  1677339599  23008.5  22984.6
17422  20230225   234000    234959  1677340199  22984.6  22966.6
17423  20230225   235000    235959  1677340799  22966.6  22996.4
17424  20230226   000000    000959  1677341399  22996.4  23014.1
2023-02-26 00:10:01,670:INFO:pyemd2:main.py:127:handleKline:185189: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--: 127.0.0.1 - - [26/Feb/2023 00:20:01] "POST / HTTP/1.1" 200 -
 self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=13306 

self.closeSec=1677341999, self.tradeDate='20230226', self.openTime='001000', self.closeTime='001959', self.symbol='BTCUSDT', self.open='23014.2', self.close='23038.2'
2023-02-26 00:20:01,727:INFO:pyemd2:main.py:125:handleKline:185189: self.closeSec=1677341999, self.tradeDate='20230226', self.openTime='001000', self.closeTime='001959',self.symbol='BTCUSDT',self.open='23014.2', self.close='23038.2'
2023-02-26 00:20:01,770:INFO:pyemd2:main.py:126:handleKline:185189: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17421  20230225   233000    233959  1677339599  23008.5  22984.6
17422  20230225   234000    234959  1677340199  22984.6  22966.6
17423  20230225   235000    235959  1677340799  22966.6  22996.4
17424  20230226   000000    000959  1677341399  22996.4  23014.1
17425  20230226   001000    001959  1677341999  23014.2  23038.2
2023-02-26 00:20:01,773:INFO:pyemd2:main.py:127:handleKline:185189: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}


## /root/FIL/strategy/similarity/log.txt ----- -----

127.0.0.1 - - [26/Feb/2023 00:00:03] "POST / HTTP/1.1" 200 -
2023-02-26 00:00:03,787:INFO:testStrategy:main.py:308:handleOrderFilled:185174: handleOrderFilled: data=OrderType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'clientorderid': '41834F1677340803189I0L2', 'symbol': 'BTCUSDT', 'gatewayorderid': 1677340803333725, 'quantity': '50.639', 'price': '22996.5', 'stopprice': '0', 'ordertype': '', 'side': 'BUY', 'status': 'FILLED', 'positionside': 'LONG', 'createtime': 1677340802856, 'updatetime': 1677340803333, 'tradetype': 'usdt', 'selfid': 41834, 'filltrades': [TradeType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'tradeid': 1677340803333, 'clientorderid': '41834F1677340803189I0L2', 'price': '22996.5', 'quantity': '50.639', 'commission': '1164.5197635', 'commissionasset': 'USDT', 'tradetime': 1677340803333, 'tradetype': 'usdt', 'gatetype': 'simulator', 'handletime': 1677340803333}], 'gatetype': 'simulator', 'handletime': 0}

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=13305 

self.closeSec=1677341399, self.tradeDate='20230226', self.openTime='000000', self.closeTime='000959', self.symbol='BTCUSDT', self.open='22996.4', self.close='23014.1'
127.0.0.1 - - [26/Feb/2023 00:10:01] "POST / HTTP/1.1" 200 -
2023-02-26 00:10:01,639:INFO:testStrategy:main.py:101:handleKline:185174: self.closeSec=1677341399, self.tradeDate='20230226', self.openTime='000000', self.closeTime='000959',self.symbol='BTCUSDT',self.open='22996.4', self.close='23014.1'
2023-02-26 00:10:01,664:INFO:testStrategy:main.py:102:handleKline:185174: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12236  20230225   232000    232959  1677338999  22986.5  23008.5
12237  20230225   233000    233959  1677339599  23008.5  22984.6
12238  20230225   234000    234959  1677340199  22984.6  22966.6
12239  20230225   235000    235959  1677340799  22966.6  22996.4
12240  20230226   000000    000959  1677341399  22996.4  23014.1
2023-02-26 00:10:01,665:INFO:testStrategy:main.py:103:handleKline:185174: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False, 'isCorr': False}

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=13306 

self.closeSec=1677341999, self.tradeDate='20230226', self.openTime='001000', self.closeTime='001959', self.symbol='BTCUSDT', self.open='23014.2', self.close='23038.2'
127.0.0.1 - - [26/Feb/2023 00:20:01] "POST / HTTP/1.1" 200 -
2023-02-26 00:20:01,726:INFO:testStrategy:main.py:101:handleKline:185174: self.closeSec=1677341999, self.tradeDate='20230226', self.openTime='001000', self.closeTime='001959',self.symbol='BTCUSDT',self.open='23014.2', self.close='23038.2'
2023-02-26 00:20:01,768:INFO:testStrategy:main.py:102:handleKline:185174: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12237  20230225   233000    233959  1677339599  23008.5  22984.6
12238  20230225   234000    234959  1677340199  22984.6  22966.6
12239  20230225   235000    235959  1677340799  22966.6  22996.4
12240  20230226   000000    000959  1677341399  22996.4  23014.1
12241  20230226   001000    001959  1677341999  23014.2  23038.2
2023-02-26 00:20:01,768:INFO:testStrategy:main.py:103:handleKline:185174: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False, 'isCorr': False}


## /root/FIL/strategy/sr_min/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=0, self.total=1000000.0, self.flagDict['side']='', self.tradeCount=0, self.count=22042
self.closeSec=1677341999, self.tradeDate='20230226', self.openTime='001500', self.closeTime='001959', self.symbol='BTCUSDT', self.open=23067.0, self.close=23038.2, self.high=23067.0, self.low=23028.0, self.vol=1252.376, self.amt=28869744.7206 
127.0.0.1 - - [26/Feb/2023 00:20:01] "POST / HTTP/1.1" 200 -
2023-02-26 00:20:01,572:INFO:sr_min:main.py:172:handleKline:449472: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5759  20230225   235500    235959  ...         0.0        0.0       0
5760  20230226   000000    000459  ...         0.0        0.0       0
5761  20230226   000500    000959  ...         0.0        0.0       0
5762  20230226   001000    001459  ...         0.0        0.0       0
5763  20230226   001500    001959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-02-26 00:20:01,575:INFO:sr_min:main.py:175:handleKline:449472: self.closeSec=1677341999, self.tradeDate='20230226', self.openTime='001500', self.closeTime='001959',self.symbol='BTCUSDT',self.open=23067.0, self.close=23038.2, self.high=23067.0, self.low=23028.0, self.vol=1252.376, self.amt=28869744.7206, ukdf['pct'].iloc[-1]=-0.001249 , ukdf['amount'].iloc[-1]=28869744.7206, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5763, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': []}
type(curSign)=<class 'int'>, curSign=0, self.sign=0
127.0.0.1 - - [26/Feb/2023 00:25:01] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=0, self.total=1000000.0, self.flagDict['side']='', self.tradeCount=0, self.count=22043
self.closeSec=1677342299, self.tradeDate='20230226', self.openTime='002000', self.closeTime='002459', self.symbol='BTCUSDT', self.open=23038.2, self.close=23019.5, self.high=23049.6, self.low=23011.1, self.vol=880.573, self.amt=20280592.5291 
2023-02-26 00:25:01,625:INFO:sr_min:main.py:172:handleKline:449472: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5760  20230226   000000    000459  ...         0.0        0.0       0
5761  20230226   000500    000959  ...         0.0        0.0       0
5762  20230226   001000    001459  ...         0.0        0.0       0
5763  20230226   001500    001959  ...         0.0        0.0       0
5764  20230226   002000    002459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-02-26 00:25:01,626:INFO:sr_min:main.py:175:handleKline:449472: self.closeSec=1677342299, self.tradeDate='20230226', self.openTime='002000', self.closeTime='002459',self.symbol='BTCUSDT',self.open=23038.2, self.close=23019.5, self.high=23049.6, self.low=23011.1, self.vol=880.573, self.amt=20280592.5291, ukdf['pct'].iloc[-1]=-0.000812 , ukdf['amount'].iloc[-1]=20280592.5291, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5764, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': []}
type(curSign)=<class 'int'>, curSign=0, self.sign=0


## /root/FIL/strategy/s_rsrs/log.txt ----- -----

723  20230225   120000    155959  1677311999  ...    723  0.888594  0.642527     1.0
724  20230225   160000    195959  1677326399  ...    724  1.038801  1.007949     1.0

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '42.179', 'enterprice': '23108.8', 'countrevence': '0', 'unrealprofit': '-5715.2545', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '22973.3', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=1, self.sign=1
--handleKline--:  version='2.0.0', self.name='s_rsrs', self.symbol='BTCUSDT', interval='4h', intervalSec=14400, wid=25, thd=0.6, self.sign=1, self.total=973731.3691248, self.flagDict['side']='buy', self.tradeCount=22, self.count=554
self.closeSec=1677340799, self.tradeDate='20230225', self.openTime='200000', self.closeTime='235959', self.symbol='BTCUSDT', self.open=22973.9, self.close=22996.4, self.high=23075.0, self.low=22845.6, self.vol=61274.986, self.amt=1407853644.41567 
2023-02-26 00:00:02,416:INFO:s_rsrs:main.py:141:handleKline:185271: self.closeSec=1677340799, self.tradeDate='20230225', self.openTime='200000', self.closeTime='235959',self.symbol='BTCUSDT',self.open=22973.9, self.close=22996.4, self.high=23075.0, self.low=22845.6, self.vol=61274.986, self.amt=1407853644.41567 
127.0.0.1 - - [26/Feb/2023 00:00:02] "POST / HTTP/1.1" 200 -
2023-02-26 00:00:02,468:INFO:s_rsrs:main.py:142:handleKline:185271: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime  ...        vol           amt       pct
721  20230225   040000    075959  ...  89582.293  2.075756e+09  0.000160
722  20230225   080000    115959  ...  32612.850  7.540489e+08 -0.004777
723  20230225   120000    155959  ...  26914.175  6.208548e+08  0.001899
724  20230225   160000    195959  ...  59947.250  1.379336e+09 -0.005829
725  20230225   200000    235959  ...  61274.986  1.407854e+09  0.000975

[5 rows x 11 columns]
2023-02-26 00:00:05,103:INFO:s_rsrs:main.py:151:handleKline:185271: df_s.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec  ...  index      beta    zscore  signal
721  20230225   040000    075959  1677283199  ...    721  0.698404  0.175532     NaN
722  20230225   080000    115959  1677297599  ...    722  0.799119  0.424163     NaN
723  20230225   120000    155959  1677311999  ...    723  0.888594  0.642527     1.0
724  20230225   160000    195959  1677326399  ...    724  1.038801  1.007949     1.0
725  20230225   200000    235959  1677340799  ...    725  0.975081  0.835976     1.0

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '42.179', 'enterprice': '23108.8', 'countrevence': '0', 'unrealprofit': '-4719.11631195343', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '22996.91692283', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=1, self.sign=1


