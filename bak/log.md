# 20230311 16:26:02

## /root/FIL/strategy/amihud/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=993672.4896432, self.flagDict['side']='sell', self.tradeCount=2, self.count=29980
self.closeSec=1678522799, self.tradeDate='20230311', self.openTime='161500', self.closeTime='161959', self.symbol='BTCUSDT', self.open=19886.6, self.close=19959.1, self.high=19975.0, self.low=19878.0, self.vol=6289.927, self.amt=125403562.1422 
127.0.0.1 - - [11/Mar/2023 16:20:02] "POST / HTTP/1.1" 200 -
2023-03-11 16:20:04,416:INFO:amihud:main.py:172:handleKline:200676: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5951  20230311   155500    155959  ...         0.0        0.0       0
5952  20230311   160000    160459  ...         0.0        0.0       0
5953  20230311   160500    160959  ...         0.0        0.0       0
5954  20230311   161000    161459  ...         0.0        0.0       0
5955  20230311   161500    161959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-03-11 16:20:04,434:INFO:amihud:main.py:175:handleKline:200676: self.closeSec=1678522799, self.tradeDate='20230311', self.openTime='161500', self.closeTime='161959',self.symbol='BTCUSDT',self.open=19886.6, self.close=19959.1, self.high=19975.0, self.low=19878.0, self.vol=6289.927, self.amt=125403562.1422, ukdf['pct'].iloc[-1]=0.003474 , ukdf['amount'].iloc[-1]=125403562.1422, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5955, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '60.176', 'enterprice': '16529.3', 'countrevence': '0', 'unrealprofit': '-206716.45524446448', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '19964.49767423', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1
127.0.0.1 - - [11/Mar/2023 16:25:01] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=993672.4896432, self.flagDict['side']='sell', self.tradeCount=2, self.count=29981
self.closeSec=1678523099, self.tradeDate='20230311', self.openTime='162000', self.closeTime='162459', self.symbol='BTCUSDT', self.open=19959.1, self.close=19977.2, self.high=19999.9, self.low=19930.4, self.vol=3983.993, self.amt=79579013.8708 
2023-03-11 16:25:01,746:INFO:amihud:main.py:172:handleKline:200676: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5952  20230311   160000    160459  ...         0.0        0.0       0
5953  20230311   160500    160959  ...         0.0        0.0       0
5954  20230311   161000    161459  ...         0.0        0.0       0
5955  20230311   161500    161959  ...         0.0        0.0       0
5956  20230311   162000    162459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-03-11 16:25:01,746:INFO:amihud:main.py:175:handleKline:200676: self.closeSec=1678523099, self.tradeDate='20230311', self.openTime='162000', self.closeTime='162459',self.symbol='BTCUSDT',self.open=19959.1, self.close=19977.2, self.high=19999.9, self.low=19930.4, self.vol=3983.993, self.amt=79579013.8708, ukdf['pct'].iloc[-1]=0.000907 , ukdf['amount'].iloc[-1]=79579013.8708, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5956, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '60.176', 'enterprice': '16529.3', 'countrevence': '0', 'unrealprofit': '-207723.1308752976', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '19981.2265301', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1


## /root/FIL/strategy/factorcheck/log.txt ----- -----


self.closeSec=1678522799, self.tradeDate='20230311', self.openTime='161500', self.closeTime='161959', self.symbol='BTCUSDT', self.open=19886.6, self.close=19959.1, self.high=19975.0, self.low=19878.0 
127.0.0.1 - - [11/Mar/2023 16:20:02] "POST / HTTP/1.1" 200 -
2023-03-11 16:20:03,466:INFO:factorcheck2:main.py:126:handleKline:185239: self.closeSec=1678522799, self.tradeDate='20230311', self.openTime='161500', self.closeTime='161959',self.symbol='BTCUSDT',self.open=19886.6, self.close=19959.1, self.high=19975.0, self.low=19878.0   
2023-03-11 16:20:04,165:INFO:factorcheck2:main.py:127:handleKline:185239: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1631  20230311   155500    155959  1678521599  ...  19812.2 -0.002719   1631    5
1632  20230311   160000    160459  1678521899  ...  19773.0 -0.003598   1632    0
1633  20230311   160500    160959  1678522199  ...  19752.5  0.005649   1633    1
1634  20230311   161000    161459  1678522499  ...  19839.7  0.000267   1634    2
1635  20230311   161500    161959  1678522799  ...  19878.0  0.003474   1635    3

[5 rows x 11 columns]
2023-03-11 16:20:04,165:INFO:factorcheck2:main.py:128:handleKline:185239: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': False, 'isOpen': True, 'isClose': False, 'isTrig': True}
127.0.0.1 - - [11/Mar/2023 16:25:01] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=9, self.factor=0.565685051853232, self.count=30547 

self.closeSec=1678523099, self.tradeDate='20230311', self.openTime='162000', self.closeTime='162459', self.symbol='BTCUSDT', self.open=19959.1, self.close=19977.2, self.high=19999.9, self.low=19930.4 
2023-03-11 16:25:01,645:INFO:factorcheck2:main.py:126:handleKline:185239: self.closeSec=1678523099, self.tradeDate='20230311', self.openTime='162000', self.closeTime='162459',self.symbol='BTCUSDT',self.open=19959.1, self.close=19977.2, self.high=19999.9, self.low=19930.4   
2023-03-11 16:25:01,721:INFO:factorcheck2:main.py:127:handleKline:185239: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1632  20230311   160000    160459  1678521899  ...  19773.0 -0.003598   1632    0
1633  20230311   160500    160959  1678522199  ...  19752.5  0.005649   1633    1
1634  20230311   161000    161459  1678522499  ...  19839.7  0.000267   1634    2
1635  20230311   161500    161959  1678522799  ...  19878.0  0.003474   1635    3
1636  20230311   162000    162459  1678523099  ...  19930.4  0.000907   1636    4

[5 rows x 11 columns]
2023-03-11 16:25:01,721:INFO:factorcheck2:main.py:128:handleKline:185239: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': False, 'isOpen': True, 'isClose': False, 'isTrig': True}


## /root/FIL/strategy/logic/log.txt ----- -----

     pred    prob_0    prob_1  actual  ...       nav  sign   cost_        bm
537     0  0.532800  0.467200       0  ...  0.903874   1.0  0.0000  0.870535
538     1  0.495355  0.504645       0  ...  0.900047   1.0  0.0000  0.866849
539     1  0.451110  0.548890       0  ...  0.899222   1.0  0.0000  0.866054
540     1  0.485806  0.514194       0  ...  0.895421   1.0  0.0000  0.862394
541     1  0.441794  0.558206       0  ...  0.909294  -1.0 -0.0016  0.847653

[5 rows x 10 columns]
2023-03-11 16:00:35,593:INFO:logic:main.py:478:getModel:885513: df_panel.iloc[-5:,:] :
    pred    prob_0    prob_1  actual  ...       nav  sign   cost_        bm
45     0  0.532858  0.467142       0  ...  0.892935   1.0  0.0000  0.868339
46     1  0.494894  0.505106       0  ...  0.900047   1.0  0.0000  0.864217
47     1  0.450899  0.549101       0  ...  0.899222   1.0  0.0000  0.863509
48     1  0.485730  0.514270       0  ...  0.895421   1.0  0.0000  0.860101
49     1  0.441794  0.558206       0  ...  0.909294  -1.0 -0.0016  0.847653

[5 rows x 10 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '33.147', 'enterprice': '20165.8', 'countrevence': '0', 'unrealprofit': '-10219.2201', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '19857.5', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
handlebackTrade > queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '33.147', 'enterprice': '20165.8', 'countrevence': '0', 'unrealprofit': '-10219.2201', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '19857.5', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
2023-03-11 16:00:41,222:INFO:logic:main.py:500:queryContractAssets:885513: queryContractAssets: assets=ContractAssetReturn{'result': [ContractAsset{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'asset': 'USDT', 'free': '658222.6916364', 'total': '658222.6916364', 'margin': '0', 'unreal': '0', 'type': 'AssetType_ucontract'}]}
2023-03-11 16:00:41,396:INFO:logic:main.py:587:openSell:885513: ret = self.client.insertMarketUOrder("simulator", "BTCUSDT", 33.069, "sell"), ret=InsertOrderReturn{'result': 'success', 'clientorderid': '41949F1678521641395I0L64'}
2023-03-11 16:00:41,423:INFO:logic:main.py:494:insertFactor:885513: curDateTime:3111600, name:logic, symbol:BTCUSDT, tradeDate:20230311, closeTime:155959, close:19844.4, sign:-1, total:658222.6916364, side:sell  
127.0.0.1 - - [11/Mar/2023 16:00:41] "POST / HTTP/1.1" 200 -
2023-03-11 16:00:41,424:INFO:logic:main.py:661:handleOrderNew:885513: handleOrderNew: data=OrderType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'clientorderid': '41948F1678521636114I0L64', 'symbol': 'BTCUSDT', 'gatewayorderid': 1678521636232342, 'quantity': '33.147', 'price': '19849.8', 'stopprice': '0', 'ordertype': '', 'side': 'SELL', 'status': 'FILLED', 'positionside': 'SHORT', 'createtime': 1678521635838, 'updatetime': 1678521636232, 'tradetype': 'usdt', 'selfid': 41948, 'filltrades': [TradeType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'tradeid': 1678521636232, 'clientorderid': '41948F1678521636114I0L64', 'price': '19849.8', 'quantity': '33.147', 'commission': '657.9613206', 'commissionasset': 'USDT', 'tradetime': 1678521636232, 'tradetype': 'usdt', 'gatetype': 'simulator', 'handletime': 1678521636232}], 'gatetype': 'simulator', 'handletime': 0}
2023-03-11 16:00:41,425:INFO:logic:main.py:664:handleOrderFilled:885513: handleOrderFilled: data=OrderType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'clientorderid': '41948F1678521636114I0L64', 'symbol': 'BTCUSDT', 'gatewayorderid': 1678521636232342, 'quantity': '33.147', 'price': '19849.8', 'stopprice': '0', 'ordertype': '', 'side': 'SELL', 'status': 'FILLED', 'positionside': 'SHORT', 'createtime': 1678521635838, 'updatetime': 1678521636232, 'tradetype': 'usdt', 'selfid': 41948, 'filltrades': [TradeType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'tradeid': 1678521636232, 'clientorderid': '41948F1678521636114I0L64', 'price': '19849.8', 'quantity': '33.147', 'commission': '657.9613206', 'commissionasset': 'USDT', 'tradetime': 1678521636232, 'tradetype': 'usdt', 'gatetype': 'simulator', 'handletime': 1678521636232}], 'gatetype': 'simulator', 'handletime': 0}
127.0.0.1 - - [11/Mar/2023 16:00:41] "POST / HTTP/1.1" 200 -
2023-03-11 16:00:41,520:INFO:logic:main.py:661:handleOrderNew:885513: handleOrderNew: data=OrderType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'clientorderid': '41949F1678521641395I0L64', 'symbol': 'BTCUSDT', 'gatewayorderid': 1678521641493309, 'quantity': '33.069', 'price': '19859.9', 'stopprice': '0', 'ordertype': '', 'side': 'SELL', 'status': 'FILLED', 'positionside': 'SHORT', 'createtime': 1678521641234, 'updatetime': 1678521641493, 'tradetype': 'usdt', 'selfid': 41949, 'filltrades': [TradeType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'tradeid': 1678521641493, 'clientorderid': '41949F1678521641395I0L64', 'price': '19859.9', 'quantity': '33.069', 'commission': '656.7470331', 'commissionasset': 'USDT', 'tradetime': 1678521641493, 'tradetype': 'usdt', 'gatetype': 'simulator', 'handletime': 1678521641493}], 'gatetype': 'simulator', 'handletime': 0}
127.0.0.1 - - [11/Mar/2023 16:00:41] "POST / HTTP/1.1" 200 -
2023-03-11 16:00:41,739:INFO:logic:main.py:664:handleOrderFilled:885513: handleOrderFilled: data=OrderType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'clientorderid': '41949F1678521641395I0L64', 'symbol': 'BTCUSDT', 'gatewayorderid': 1678521641493309, 'quantity': '33.069', 'price': '19859.9', 'stopprice': '0', 'ordertype': '', 'side': 'SELL', 'status': 'FILLED', 'positionside': 'SHORT', 'createtime': 1678521641234, 'updatetime': 1678521641493, 'tradetype': 'usdt', 'selfid': 41949, 'filltrades': [TradeType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'tradeid': 1678521641493, 'clientorderid': '41949F1678521641395I0L64', 'price': '19859.9', 'quantity': '33.069', 'commission': '656.7470331', 'commissionasset': 'USDT', 'tradetime': 1678521641493, 'tradetype': 'usdt', 'gatetype': 'simulator', 'handletime': 1678521641493}], 'gatetype': 'simulator', 'handletime': 0}
127.0.0.1 - - [11/Mar/2023 16:00:41] "POST / HTTP/1.1" 200 -


## /root/FIL/strategy/modifiedmom/log.txt ----- -----

527  20230311   155000    155959  1678521599  20002.4  19844.4 -0.007899
2023-03-11 16:00:02,304:INFO:modifiedmom:main.py:146:handleKline:185213: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True}

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=15272 

self.closeSec=1678522199, self.tradeDate='20230311', self.openTime='160000', self.closeTime='160959', self.symbol='BTCUSDT', self.open='19844.4', self.close='19884.7'
127.0.0.1 - - [11/Mar/2023 16:10:01] "POST / HTTP/1.1" 200 -
2023-03-11 16:10:01,603:INFO:modifiedmom:main.py:144:handleKline:185213: self.closeSec=1678522199, self.tradeDate='20230311', self.openTime='160000', self.closeTime='160959',self.symbol='BTCUSDT',self.open='19844.4', self.close='19884.7'
2023-03-11 16:10:01,659:INFO:modifiedmom:main.py:145:handleKline:185213: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
524  20230311   152000    152959  1678519799  20140.9  20189.5  0.002418
525  20230311   153000    153959  1678520399  20189.5  20023.5 -0.008222
526  20230311   154000    154959  1678520999  20023.6  20002.4 -0.001054
527  20230311   155000    155959  1678521599  20002.4  19844.4 -0.007899
528  20230311   160000    160959  1678522199  19844.4  19884.7  0.002031
2023-03-11 16:10:01,659:INFO:modifiedmom:main.py:146:handleKline:185213: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True}

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=15273 

self.closeSec=1678522799, self.tradeDate='20230311', self.openTime='161000', self.closeTime='161959', self.symbol='BTCUSDT', self.open='19885.2', self.close='19959.1'
127.0.0.1 - - [11/Mar/2023 16:20:02] "POST / HTTP/1.1" 200 -
2023-03-11 16:20:03,764:INFO:modifiedmom:main.py:144:handleKline:185213: self.closeSec=1678522799, self.tradeDate='20230311', self.openTime='161000', self.closeTime='161959',self.symbol='BTCUSDT',self.open='19885.2', self.close='19959.1'
2023-03-11 16:20:04,224:INFO:modifiedmom:main.py:145:handleKline:185213: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
525  20230311   153000    153959  1678520399  20189.5  20023.5 -0.008222
526  20230311   154000    154959  1678520999  20023.6  20002.4 -0.001054
527  20230311   155000    155959  1678521599  20002.4  19844.4 -0.007899
528  20230311   160000    160959  1678522199  19844.4  19884.7  0.002031
529  20230311   161000    161959  1678522799  19885.2  19959.1  0.003742
2023-03-11 16:20:04,225:INFO:modifiedmom:main.py:146:handleKline:185213: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True}


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

17519  20230311   155000    155959  1678521599  20002.4  19844.4
2023-03-11 16:00:02,372:INFO:pyemd2:main.py:127:handleKline:185189: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}
127.0.0.1 - - [11/Mar/2023 16:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=15273 

self.closeSec=1678522199, self.tradeDate='20230311', self.openTime='160000', self.closeTime='160959', self.symbol='BTCUSDT', self.open='19844.4', self.close='19884.7'
2023-03-11 16:10:01,634:INFO:pyemd2:main.py:125:handleKline:185189: self.closeSec=1678522199, self.tradeDate='20230311', self.openTime='160000', self.closeTime='160959',self.symbol='BTCUSDT',self.open='19844.4', self.close='19884.7'
2023-03-11 16:10:01,672:INFO:pyemd2:main.py:126:handleKline:185189: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17516  20230311   152000    152959  1678519799  20140.9  20189.5
17517  20230311   153000    153959  1678520399  20189.5  20023.5
17518  20230311   154000    154959  1678520999  20023.6  20002.4
17519  20230311   155000    155959  1678521599  20002.4  19844.4
17520  20230311   160000    160959  1678522199  19844.4  19884.7
2023-03-11 16:10:01,672:INFO:pyemd2:main.py:127:handleKline:185189: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=15274 

self.closeSec=1678522799, self.tradeDate='20230311', self.openTime='161000', self.closeTime='161959', self.symbol='BTCUSDT', self.open='19885.2', self.close='19959.1'
127.0.0.1 - - [11/Mar/2023 16:20:02] "POST / HTTP/1.1" 200 -
2023-03-11 16:20:05,601:INFO:pyemd2:main.py:125:handleKline:185189: self.closeSec=1678522799, self.tradeDate='20230311', self.openTime='161000', self.closeTime='161959',self.symbol='BTCUSDT',self.open='19885.2', self.close='19959.1'
2023-03-11 16:20:05,681:INFO:pyemd2:main.py:126:handleKline:185189: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17517  20230311   153000    153959  1678520399  20189.5  20023.5
17518  20230311   154000    154959  1678520999  20023.6  20002.4
17519  20230311   155000    155959  1678521599  20002.4  19844.4
17520  20230311   160000    160959  1678522199  19844.4  19884.7
17521  20230311   161000    161959  1678522799  19885.2  19959.1
2023-03-11 16:20:05,682:INFO:pyemd2:main.py:127:handleKline:185189: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}


## /root/FIL/strategy/similarity/log.txt ----- -----

12191  20230311   155000    155959  1678521599  20002.4  19844.4
2023-03-11 16:00:02,363:INFO:testStrategy:main.py:103:handleKline:185174: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}
127.0.0.1 - - [11/Mar/2023 16:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=15273 

self.closeSec=1678522199, self.tradeDate='20230311', self.openTime='160000', self.closeTime='160959', self.symbol='BTCUSDT', self.open='19844.4', self.close='19884.7'
2023-03-11 16:10:01,615:INFO:testStrategy:main.py:101:handleKline:185174: self.closeSec=1678522199, self.tradeDate='20230311', self.openTime='160000', self.closeTime='160959',self.symbol='BTCUSDT',self.open='19844.4', self.close='19884.7'
2023-03-11 16:10:01,678:INFO:testStrategy:main.py:102:handleKline:185174: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12188  20230311   152000    152959  1678519799  20140.9  20189.5
12189  20230311   153000    153959  1678520399  20189.5  20023.5
12190  20230311   154000    154959  1678520999  20023.6  20002.4
12191  20230311   155000    155959  1678521599  20002.4  19844.4
12192  20230311   160000    160959  1678522199  19844.4  19884.7
2023-03-11 16:10:01,687:INFO:testStrategy:main.py:103:handleKline:185174: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=15274 

self.closeSec=1678522799, self.tradeDate='20230311', self.openTime='161000', self.closeTime='161959', self.symbol='BTCUSDT', self.open='19885.2', self.close='19959.1'
127.0.0.1 - - [11/Mar/2023 16:20:02] "POST / HTTP/1.1" 200 -
2023-03-11 16:20:05,268:INFO:testStrategy:main.py:101:handleKline:185174: self.closeSec=1678522799, self.tradeDate='20230311', self.openTime='161000', self.closeTime='161959',self.symbol='BTCUSDT',self.open='19885.2', self.close='19959.1'
2023-03-11 16:20:05,510:INFO:testStrategy:main.py:102:handleKline:185174: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12189  20230311   153000    153959  1678520399  20189.5  20023.5
12190  20230311   154000    154959  1678520999  20023.6  20002.4
12191  20230311   155000    155959  1678521599  20002.4  19844.4
12192  20230311   160000    160959  1678522199  19844.4  19884.7
12193  20230311   161000    161959  1678522799  19885.2  19959.1
2023-03-11 16:20:05,511:INFO:testStrategy:main.py:103:handleKline:185174: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}


## /root/FIL/strategy/sr_min/log.txt ----- -----

--handleKline--:  127.0.0.1 - - [11/Mar/2023 16:20:01] "POST / HTTP/1.1" 200 -
version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=0, self.total=1000000.0, self.flagDict['side']='', self.tradeCount=0, self.count=25978
self.closeSec=1678522799, self.tradeDate='20230311', self.openTime='161500', self.closeTime='161959', self.symbol='BTCUSDT', self.open=19886.6, self.close=19959.1, self.high=19975.0, self.low=19878.0, self.vol=6289.927, self.amt=125403562.1422 
2023-03-11 16:20:01,557:INFO:sr_min:main.py:172:handleKline:449472: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5951  20230311   155500    155959  ...         0.0        0.0       0
5952  20230311   160000    160459  ...         0.0        0.0       0
5953  20230311   160500    160959  ...         0.0        0.0       0
5954  20230311   161000    161459  ...         0.0        0.0       0
5955  20230311   161500    161959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-03-11 16:20:01,559:INFO:sr_min:main.py:175:handleKline:449472: self.closeSec=1678522799, self.tradeDate='20230311', self.openTime='161500', self.closeTime='161959',self.symbol='BTCUSDT',self.open=19886.6, self.close=19959.1, self.high=19975.0, self.low=19878.0, self.vol=6289.927, self.amt=125403562.1422, ukdf['pct'].iloc[-1]=0.003474 , ukdf['amount'].iloc[-1]=125403562.1422, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5955, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': []}
type(curSign)=<class 'int'>, curSign=0, self.sign=0
127.0.0.1 - - [11/Mar/2023 16:25:01] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=0, self.total=1000000.0, self.flagDict['side']='', self.tradeCount=0, self.count=25979
self.closeSec=1678523099, self.tradeDate='20230311', self.openTime='162000', self.closeTime='162459', self.symbol='BTCUSDT', self.open=19959.1, self.close=19977.2, self.high=19999.9, self.low=19930.4, self.vol=3983.993, self.amt=79579013.8708 
2023-03-11 16:25:01,669:INFO:sr_min:main.py:172:handleKline:449472: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5952  20230311   160000    160459  ...         0.0        0.0       0
5953  20230311   160500    160959  ...         0.0        0.0       0
5954  20230311   161000    161459  ...         0.0        0.0       0
5955  20230311   161500    161959  ...         0.0        0.0       0
5956  20230311   162000    162459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-03-11 16:25:01,669:INFO:sr_min:main.py:175:handleKline:449472: self.closeSec=1678523099, self.tradeDate='20230311', self.openTime='162000', self.closeTime='162459',self.symbol='BTCUSDT',self.open=19959.1, self.close=19977.2, self.high=19999.9, self.low=19930.4, self.vol=3983.993, self.amt=79579013.8708, ukdf['pct'].iloc[-1]=0.000907 , ukdf['amount'].iloc[-1]=79579013.8708, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5956, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': []}
type(curSign)=<class 'int'>, curSign=0, self.sign=0


## /root/FIL/strategy/s_rsrs/log.txt ----- -----

721  20230311   040000    075959  1678492799  ...    721  0.715669  0.541569     NaN
722  20230311   080000    115959  1678507199  ...    722  0.720860  0.553101     NaN

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '42.135', 'enterprice': '23350.3', 'countrevence': '0', 'unrealprofit': '124959.7695', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '20384.6', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-9223372036854775808, self.sign=-1
127.0.0.1 - - [11/Mar/2023 16:00:02] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='s_rsrs', self.symbol='BTCUSDT', interval='4h', intervalSec=14400, wid=25, thd=0.6, self.sign=-1, self.total=982881.0256095, self.flagDict['side']='sell', self.tradeCount=23, self.count=636
self.closeSec=1678521599, self.tradeDate='20230311', self.openTime='120000', self.closeTime='155959', self.symbol='BTCUSDT', self.open=20381.3, self.close=19844.4, self.high=20424.7, self.low=19812.2, self.vol=139731.915, self.amt=2816961022.35732 
2023-03-11 16:00:02,057:INFO:s_rsrs:main.py:141:handleKline:185271: self.closeSec=1678521599, self.tradeDate='20230311', self.openTime='120000', self.closeTime='155959',self.symbol='BTCUSDT',self.open=20381.3, self.close=19844.4, self.high=20424.7, self.low=19812.2, self.vol=139731.915, self.amt=2816961022.35732 
2023-03-11 16:00:02,123:INFO:s_rsrs:main.py:142:handleKline:185271: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime  ...         vol           amt       pct
719  20230310   200000    235959  ...  377610.370  7.536282e+09  0.012405
720  20230311   000000    035959  ...  193610.159  3.871005e+09  0.000810
721  20230311   040000    075959  ...  104598.079  2.097184e+09  0.006451
722  20230311   080000    115959  ...  207973.491  4.246584e+09  0.011961
723  20230311   120000    155959  ...  139731.915  2.816961e+09 -0.026338

[5 rows x 11 columns]
2023-03-11 16:00:05,065:INFO:s_rsrs:main.py:151:handleKline:185271: df_s.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec  ...  index      beta    zscore  signal
719  20230310   200000    235959  1678463999  ...    719  0.685910  0.452372     NaN
720  20230311   000000    035959  1678478399  ...    720  0.698359  0.488105     NaN
721  20230311   040000    075959  1678492799  ...    721  0.715669  0.541569     NaN
722  20230311   080000    115959  1678507199  ...    722  0.720860  0.553101     NaN
723  20230311   120000    155959  1678521599  ...    723  0.719905  0.545570     NaN

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '42.135', 'enterprice': '23350.3', 'countrevence': '0', 'unrealprofit': '147674.6991276135', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '19845.5011599', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-9223372036854775808, self.sign=-1


