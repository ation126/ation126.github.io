# 20230315 00:26:02

## /root/FIL/strategy/amihud/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=993672.4896432, self.flagDict['side']='sell', self.tradeCount=2, self.count=30940
self.closeSec=1678810799, self.tradeDate='20230315', self.openTime='001500', self.closeTime='001959', self.symbol='BTCUSDT', self.open=26013.5, self.close=25926.4, self.high=26016.9, self.low=25910.3, self.vol=2964.359, self.amt=76973024.9246 
127.0.0.1 - - [15/Mar/2023 00:20:02] "POST / HTTP/1.1" 200 -
2023-03-15 00:20:05,362:INFO:amihud:main.py:172:handleKline:200676: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5759  20230314   235500    235959  ...         0.0        0.0       0
5760  20230315   000000    000459  ...         0.0        0.0       0
5761  20230315   000500    000959  ...         0.0        0.0       0
5762  20230315   001000    001459  ...         0.0        0.0       0
5763  20230315   001500    001959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-03-15 00:20:05,372:INFO:amihud:main.py:175:handleKline:200676: self.closeSec=1678810799, self.tradeDate='20230315', self.openTime='001500', self.closeTime='001959',self.symbol='BTCUSDT',self.open=26013.5, self.close=25926.4, self.high=26016.9, self.low=25910.3, self.vol=2964.359, self.amt=76973024.9246, ukdf['pct'].iloc[-1]=-0.003352 , ukdf['amount'].iloc[-1]=76973024.9246, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5763, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '60.176', 'enterprice': '16529.3', 'countrevence': '0', 'unrealprofit': '-566013.10448018288', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '25935.26092263', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1
127.0.0.1 - - [15/Mar/2023 00:25:01] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=993672.4896432, self.flagDict['side']='sell', self.tradeCount=2, self.count=30941
self.closeSec=1678811099, self.tradeDate='20230315', self.openTime='002000', self.closeTime='002459', self.symbol='BTCUSDT', self.open=25926.4, self.close=25843.7, self.high=25943.6, self.low=25809.8, self.vol=6885.646, self.amt=178054322.2388 
2023-03-15 00:25:01,736:INFO:amihud:main.py:172:handleKline:200676: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5760  20230315   000000    000459  ...         0.0        0.0       0
5761  20230315   000500    000959  ...         0.0        0.0       0
5762  20230315   001000    001459  ...         0.0        0.0       0
5763  20230315   001500    001959  ...         0.0        0.0       0
5764  20230315   002000    002459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-03-15 00:25:01,737:INFO:amihud:main.py:175:handleKline:200676: self.closeSec=1678811099, self.tradeDate='20230315', self.openTime='002000', self.closeTime='002459',self.symbol='BTCUSDT',self.open=25926.4, self.close=25843.7, self.high=25943.6, self.low=25809.8, self.vol=6885.646, self.amt=178054322.2388, ukdf['pct'].iloc[-1]=-0.00319 , ukdf['amount'].iloc[-1]=178054322.2388, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5764, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '60.176', 'enterprice': '16529.3', 'countrevence': '0', 'unrealprofit': '-560669.92916952768', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '25846.46845868', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1


## /root/FIL/strategy/factorcheck/log.txt ----- -----


self.closeSec=1678810799, self.tradeDate='20230315', self.openTime='001500', self.closeTime='001959', self.symbol='BTCUSDT', self.open=26013.5, self.close=25926.4, self.high=26016.9, self.low=25910.3 
127.0.0.1 - - [15/Mar/2023 00:20:01] "POST / HTTP/1.1" 200 -
2023-03-15 00:20:03,304:INFO:factorcheck2:main.py:126:handleKline:185239: self.closeSec=1678810799, self.tradeDate='20230315', self.openTime='001500', self.closeTime='001959',self.symbol='BTCUSDT',self.open=26013.5, self.close=25926.4, self.high=26016.9, self.low=25910.3   
2023-03-15 00:20:04,332:INFO:factorcheck2:main.py:127:handleKline:185239: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1439  20230314   235500    235959  1678809599  ...  25877.6  0.000042   1727    5
1440  20230315   000000    000459  1678809899  ...  25885.2  0.001220   1440    0
1441  20230315   000500    000959  1678810199  ...  25870.6  0.001021   1441    1
1442  20230315   001000    001459  1678810499  ...  25967.1  0.001702   1442    2
1443  20230315   001500    001959  1678810799  ...  25910.3 -0.003352   1443    3

[5 rows x 11 columns]
2023-03-15 00:20:04,333:INFO:factorcheck2:main.py:128:handleKline:185239: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=87, self.factor=0.12485758619853413, self.count=31507 

self.closeSec=1678811099, self.tradeDate='20230315', self.openTime='002000', self.closeTime='002459', self.symbol='BTCUSDT', self.open=25926.4, self.close=25843.7, self.high=25943.6, self.low=25809.8 
127.0.0.1 - - [15/Mar/2023 00:25:01] "POST / HTTP/1.1" 200 -
2023-03-15 00:25:01,624:INFO:factorcheck2:main.py:126:handleKline:185239: self.closeSec=1678811099, self.tradeDate='20230315', self.openTime='002000', self.closeTime='002459',self.symbol='BTCUSDT',self.open=25926.4, self.close=25843.7, self.high=25943.6, self.low=25809.8   
2023-03-15 00:25:01,642:INFO:factorcheck2:main.py:127:handleKline:185239: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1440  20230315   000000    000459  1678809899  ...  25885.2  0.001220   1440    0
1441  20230315   000500    000959  1678810199  ...  25870.6  0.001021   1441    1
1442  20230315   001000    001459  1678810499  ...  25967.1  0.001702   1442    2
1443  20230315   001500    001959  1678810799  ...  25910.3 -0.003352   1443    3
1444  20230315   002000    002459  1678811099  ...  25809.8 -0.003190   1444    4

[5 rows x 11 columns]
2023-03-15 00:25:01,642:INFO:factorcheck2:main.py:128:handleKline:185239: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}


## /root/FIL/strategy/logic/log.txt ----- -----

     pred    prob_0    prob_1  actual  ...       nav  sign   cost_        bm
539     0  0.621886  0.378114       0  ...  1.126503   1.0  0.0000  1.154149
540     0  0.549101  0.450899       1  ...  1.135583   1.0  0.0000  1.163452
541     0  0.657953  0.342047       0  ...  1.129443   1.0  0.0000  1.157161
542     0  0.542788  0.457212       0  ...  1.127224   1.0  0.0000  1.154888
543     1  0.421545  0.578455       1  ...  1.120961  -1.0 -0.0016  1.159456

[5 rows x 10 columns]
2023-03-15 00:00:35,788:INFO:logic:main.py:478:getModel:885513: df_panel.iloc[-5:,:] :
    pred    prob_0    prob_1  actual  ...       nav  sign   cost_        bm
45     0  0.621774  0.378226       0  ...  1.126146   1.0  0.0000  1.152149
46     0  0.548723  0.451277       1  ...  1.135583   1.0  0.0000  1.162558
47     0  0.657520  0.342480       0  ...  1.129443   1.0  0.0000  1.156271
48     0  0.542148  0.457852       0  ...  1.127224   1.0  0.0000  1.155250
49     1  0.421545  0.578455       1  ...  1.120961  -1.0 -0.0016  1.159456

[5 rows x 10 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '29.359', 'enterprice': '24669', 'countrevence': '0', 'unrealprofit': '36695.8141', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '25918.9', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
handlebackTrade > queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '29.359', 'enterprice': '24669', 'countrevence': '0', 'unrealprofit': '36695.8141', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '25918.9', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
2023-03-15 00:00:41,466:INFO:logic:main.py:500:queryContractAssets:885513: queryContractAssets: assets=ContractAssetReturn{'result': [ContractAsset{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'asset': 'USDT', 'free': '761327.3117233', 'total': '761327.3117233', 'margin': '0', 'unreal': '0', 'type': 'AssetType_ucontract'}]}
2023-03-15 00:00:41,694:INFO:logic:main.py:587:openSell:885513: ret = self.client.insertMarketUOrder("simulator", "BTCUSDT", 29.293, "sell"), ret=InsertOrderReturn{'result': 'success', 'clientorderid': '41986F1678809641694I0L64'}
2023-03-15 00:00:41,714:INFO:logic:main.py:494:insertFactor:885513: curDateTime:3150000, name:logic, symbol:BTCUSDT, tradeDate:20230314, closeTime:235959, close:25911.3, sign:-1, total:761327.3117233, side:sell  
127.0.0.1 - - [15/Mar/2023 00:00:41] "POST / HTTP/1.1" 200 -
2023-03-15 00:00:41,715:INFO:logic:main.py:661:handleOrderNew:885513: handleOrderNew: data=OrderType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'clientorderid': '41985F1678809636356I0L64', 'symbol': 'BTCUSDT', 'gatewayorderid': 1678809636445516, 'quantity': '29.359', 'price': '25918.9', 'stopprice': '0', 'ordertype': '', 'side': 'SELL', 'status': 'FILLED', 'positionside': 'SHORT', 'createtime': 1678809636090, 'updatetime': 1678809636445, 'tradetype': 'usdt', 'selfid': 41985, 'filltrades': [TradeType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'tradeid': 1678809636445, 'clientorderid': '41985F1678809636356I0L64', 'price': '25918.9', 'quantity': '29.359', 'commission': '760.9529851', 'commissionasset': 'USDT', 'tradetime': 1678809636445, 'tradetype': 'usdt', 'gatetype': 'simulator', 'handletime': 1678809636445}], 'gatetype': 'simulator', 'handletime': 0}
127.0.0.1 - - [15/Mar/2023 00:00:41] "POST / HTTP/1.1" 200 -
2023-03-15 00:00:41,716:INFO:logic:main.py:664:handleOrderFilled:885513: handleOrderFilled: data=OrderType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'clientorderid': '41985F1678809636356I0L64', 'symbol': 'BTCUSDT', 'gatewayorderid': 1678809636445516, 'quantity': '29.359', 'price': '25918.9', 'stopprice': '0', 'ordertype': '', 'side': 'SELL', 'status': 'FILLED', 'positionside': 'SHORT', 'createtime': 1678809636090, 'updatetime': 1678809636445, 'tradetype': 'usdt', 'selfid': 41985, 'filltrades': [TradeType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'tradeid': 1678809636445, 'clientorderid': '41985F1678809636356I0L64', 'price': '25918.9', 'quantity': '29.359', 'commission': '760.9529851', 'commissionasset': 'USDT', 'tradetime': 1678809636445, 'tradetype': 'usdt', 'gatetype': 'simulator', 'handletime': 1678809636445}], 'gatetype': 'simulator', 'handletime': 0}
127.0.0.1 - - [15/Mar/2023 00:00:41] "POST / HTTP/1.1" 200 -
2023-03-15 00:00:41,845:INFO:logic:main.py:661:handleOrderNew:885513: handleOrderNew: data=OrderType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'clientorderid': '41986F1678809641694I0L64', 'symbol': 'BTCUSDT', 'gatewayorderid': 1678809641819014, 'quantity': '29.293', 'price': '25912.4', 'stopprice': '0', 'ordertype': '', 'side': 'SELL', 'status': 'FILLED', 'positionside': 'SHORT', 'createtime': 1678809641491, 'updatetime': 1678809641819, 'tradetype': 'usdt', 'selfid': 41986, 'filltrades': [TradeType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'tradeid': 1678809641819, 'clientorderid': '41986F1678809641694I0L64', 'price': '25912.4', 'quantity': '29.293', 'commission': '759.0519332', 'commissionasset': 'USDT', 'tradetime': 1678809641819, 'tradetype': 'usdt', 'gatetype': 'simulator', 'handletime': 1678809641819}], 'gatetype': 'simulator', 'handletime': 0}
2023-03-15 00:00:42,092:INFO:logic:main.py:664:handleOrderFilled:885513: handleOrderFilled: data=OrderType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'clientorderid': '41986F1678809641694I0L64', 'symbol': 'BTCUSDT', 'gatewayorderid': 1678809641819014, 'quantity': '29.293', 'price': '25912.4', 'stopprice': '0', 'ordertype': '', 'side': 'SELL', 'status': 'FILLED', 'positionside': 'SHORT', 'createtime': 1678809641491, 'updatetime': 1678809641819, 'tradetype': 'usdt', 'selfid': 41986, 'filltrades': [TradeType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'tradeid': 1678809641819, 'clientorderid': '41986F1678809641694I0L64', 'price': '25912.4', 'quantity': '29.293', 'commission': '759.0519332', 'commissionasset': 'USDT', 'tradetime': 1678809641819, 'tradetype': 'usdt', 'gatetype': 'simulator', 'handletime': 1678809641819}], 'gatetype': 'simulator', 'handletime': 0}
127.0.0.1 - - [15/Mar/2023 00:00:42] "POST / HTTP/1.1" 200 -


## /root/FIL/strategy/modifiedmom/log.txt ----- -----

127.0.0.1 - - [15/Mar/2023 00:00:03] "POST / HTTP/1.1" 200 -
2023-03-15 00:00:03,384:INFO:modifiedmom:main.py:319:handleOrderFilled:185213: handleOrderFilled: data=OrderType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'clientorderid': '41983F1678809602750I0L59', 'symbol': 'BTCUSDT', 'gatewayorderid': 1678809602857874, 'quantity': '37.649', 'price': '25910.2', 'stopprice': '0', 'ordertype': '', 'side': 'BUY', 'status': 'FILLED', 'positionside': 'LONG', 'createtime': 1678809602436, 'updatetime': 1678809602857, 'tradetype': 'usdt', 'selfid': 41983, 'filltrades': [TradeType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'tradeid': 1678809602857, 'clientorderid': '41983F1678809602750I0L59', 'price': '25910.2', 'quantity': '37.649', 'commission': '975.4931198', 'commissionasset': 'USDT', 'tradetime': 1678809602857, 'tradetype': 'usdt', 'gatetype': 'simulator', 'handletime': 1678809602857}], 'gatetype': 'simulator', 'handletime': 0}

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=15752 

self.closeSec=1678810199, self.tradeDate='20230315', self.openTime='000000', self.closeTime='000959', self.symbol='BTCUSDT', self.open='25911.3', self.close='25969.4'
127.0.0.1 - - [15/Mar/2023 00:10:01] "POST / HTTP/1.1" 200 -
2023-03-15 00:10:01,619:INFO:modifiedmom:main.py:144:handleKline:185213: self.closeSec=1678810199, self.tradeDate='20230315', self.openTime='000000', self.closeTime='000959',self.symbol='BTCUSDT',self.open='25911.3', self.close='25969.4'
2023-03-15 00:10:01,646:INFO:modifiedmom:main.py:145:handleKline:185213: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
572  20230314   232000    232959  1678807799    25898  25809.2 -0.003429
573  20230314   233000    233959  1678808399  25803.7  25862.2  0.002054
574  20230314   234000    234959  1678808999  25863.6  25909.7  0.001837
575  20230314   235000    235959  1678809599  25909.8  25911.3  0.000062
576  20230315   000000    000959  1678810199  25911.3  25969.4  0.002242
2023-03-15 00:10:01,646:INFO:modifiedmom:main.py:146:handleKline:185213: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=15753 

self.closeSec=1678810799, self.tradeDate='20230315', self.openTime='001000', self.closeTime='001959', self.symbol='BTCUSDT', self.open='25969.4', self.close='25926.4'
127.0.0.1 - - [15/Mar/2023 00:20:02] "POST / HTTP/1.1" 200 -
2023-03-15 00:20:04,470:INFO:modifiedmom:main.py:144:handleKline:185213: self.closeSec=1678810799, self.tradeDate='20230315', self.openTime='001000', self.closeTime='001959',self.symbol='BTCUSDT',self.open='25969.4', self.close='25926.4'
2023-03-15 00:20:04,983:INFO:modifiedmom:main.py:145:handleKline:185213: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
573  20230314   233000    233959  1678808399  25803.7  25862.2  0.002054
574  20230314   234000    234959  1678808999  25863.6  25909.7  0.001837
575  20230314   235000    235959  1678809599  25909.8  25911.3  0.000062
576  20230315   000000    000959  1678810199  25911.3  25969.4  0.002242
577  20230315   001000    001959  1678810799  25969.4  25926.4 -0.001656
2023-03-15 00:20:04,983:INFO:modifiedmom:main.py:146:handleKline:185213: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False}


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

127.0.0.1 - - [15/Mar/2023 00:00:03] "POST / HTTP/1.1" 200 -
2023-03-15 00:00:03,132:INFO:pyemd2:main.py:303:handleOrderFilled:185189: handleOrderFilled: data=OrderType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'clientorderid': '41982F1678809602698I0L57', 'symbol': 'BTCUSDT', 'gatewayorderid': 1678809602799221, 'quantity': '40.391', 'price': '25910.1', 'stopprice': '0', 'ordertype': '', 'side': 'SELL', 'status': 'FILLED', 'positionside': 'SHORT', 'createtime': 1678809602284, 'updatetime': 1678809602799, 'tradetype': 'usdt', 'selfid': 41982, 'filltrades': [TradeType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'tradeid': 1678809602799, 'clientorderid': '41982F1678809602698I0L57', 'price': '25910.1', 'quantity': '40.391', 'commission': '1046.5348491', 'commissionasset': 'USDT', 'tradetime': 1678809602799, 'tradetype': 'usdt', 'gatetype': 'simulator', 'handletime': 1678809602799}], 'gatetype': 'simulator', 'handletime': 0}

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=15753 

self.closeSec=1678810199, self.tradeDate='20230315', self.openTime='000000', self.closeTime='000959', self.symbol='BTCUSDT', self.open='25911.3', self.close='25969.4'
2023-03-15 00:10:01,613:INFO:pyemd2:main.py:125:handleKline:185189: self.closeSec=1678810199, self.tradeDate='20230315', self.openTime='000000', self.closeTime='000959',self.symbol='BTCUSDT',self.open='25911.3', self.close='25969.4'
127.0.0.1 - - [15/Mar/2023 00:10:01] "POST / HTTP/1.1" 200 -
2023-03-15 00:10:01,657:INFO:pyemd2:main.py:126:handleKline:185189: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17420  20230314   232000    232959  1678807799    25898  25809.2
17421  20230314   233000    233959  1678808399  25803.7  25862.2
17422  20230314   234000    234959  1678808999  25863.6  25909.7
17423  20230314   235000    235959  1678809599  25909.8  25911.3
17424  20230315   000000    000959  1678810199  25911.3  25969.4
2023-03-15 00:10:01,657:INFO:pyemd2:main.py:127:handleKline:185189: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=15754 

self.closeSec=1678810799, self.tradeDate='20230315', self.openTime='001000', self.closeTime='001959', self.symbol='BTCUSDT', self.open='25969.4', self.close='25926.4'
127.0.0.1 - - [15/Mar/2023 00:20:02] "POST / HTTP/1.1" 200 -
2023-03-15 00:20:06,733:INFO:pyemd2:main.py:125:handleKline:185189: self.closeSec=1678810799, self.tradeDate='20230315', self.openTime='001000', self.closeTime='001959',self.symbol='BTCUSDT',self.open='25969.4', self.close='25926.4'
2023-03-15 00:20:06,963:INFO:pyemd2:main.py:126:handleKline:185189: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17421  20230314   233000    233959  1678808399  25803.7  25862.2
17422  20230314   234000    234959  1678808999  25863.6  25909.7
17423  20230314   235000    235959  1678809599  25909.8  25911.3
17424  20230315   000000    000959  1678810199  25911.3  25969.4
17425  20230315   001000    001959  1678810799  25969.4  25926.4
2023-03-15 00:20:06,963:INFO:pyemd2:main.py:127:handleKline:185189: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}


## /root/FIL/strategy/similarity/log.txt ----- -----

127.0.0.1 - - [15/Mar/2023 00:00:03] "POST / HTTP/1.1" 200 -
2023-03-15 00:00:03,610:INFO:testStrategy:main.py:308:handleOrderFilled:185174: handleOrderFilled: data=OrderType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'clientorderid': '41984F1678809602996I0L2', 'symbol': 'BTCUSDT', 'gatewayorderid': 1678809603269949, 'quantity': '51.781', 'price': '25910.2', 'stopprice': '0', 'ordertype': '', 'side': 'BUY', 'status': 'FILLED', 'positionside': 'LONG', 'createtime': 1678809602481, 'updatetime': 1678809603269, 'tradetype': 'usdt', 'selfid': 41984, 'filltrades': [TradeType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'tradeid': 1678809603269, 'clientorderid': '41984F1678809602996I0L2', 'price': '25910.2', 'quantity': '51.781', 'commission': '1341.6560662', 'commissionasset': 'USDT', 'tradetime': 1678809603269, 'tradetype': 'usdt', 'gatetype': 'simulator', 'handletime': 1678809603269}], 'gatetype': 'simulator', 'handletime': 0}
127.0.0.1 - - [15/Mar/2023 00:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=15753 

self.closeSec=1678810199, self.tradeDate='20230315', self.openTime='000000', self.closeTime='000959', self.symbol='BTCUSDT', self.open='25911.3', self.close='25969.4'
2023-03-15 00:10:01,625:INFO:testStrategy:main.py:101:handleKline:185174: self.closeSec=1678810199, self.tradeDate='20230315', self.openTime='000000', self.closeTime='000959',self.symbol='BTCUSDT',self.open='25911.3', self.close='25969.4'
2023-03-15 00:10:01,655:INFO:testStrategy:main.py:102:handleKline:185174: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12236  20230314   232000    232959  1678807799    25898  25809.2
12237  20230314   233000    233959  1678808399  25803.7  25862.2
12238  20230314   234000    234959  1678808999  25863.6  25909.7
12239  20230314   235000    235959  1678809599  25909.8  25911.3
12240  20230315   000000    000959  1678810199  25911.3  25969.4
2023-03-15 00:10:01,659:INFO:testStrategy:main.py:103:handleKline:185174: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False, 'isCorr': False}

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=15754 

self.closeSec=1678810799, self.tradeDate='20230315', self.openTime='001000', self.closeTime='001959', self.symbol='BTCUSDT', self.open='25969.4', self.close='25926.4'
127.0.0.1 - - [15/Mar/2023 00:20:02] "POST / HTTP/1.1" 200 -
2023-03-15 00:20:06,125:INFO:testStrategy:main.py:101:handleKline:185174: self.closeSec=1678810799, self.tradeDate='20230315', self.openTime='001000', self.closeTime='001959',self.symbol='BTCUSDT',self.open='25969.4', self.close='25926.4'
2023-03-15 00:20:06,515:INFO:testStrategy:main.py:102:handleKline:185174: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12237  20230314   233000    233959  1678808399  25803.7  25862.2
12238  20230314   234000    234959  1678808999  25863.6  25909.7
12239  20230314   235000    235959  1678809599  25909.8  25911.3
12240  20230315   000000    000959  1678810199  25911.3  25969.4
12241  20230315   001000    001959  1678810799  25969.4  25926.4
2023-03-15 00:20:06,515:INFO:testStrategy:main.py:103:handleKline:185174: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False, 'isCorr': False}


## /root/FIL/strategy/sr_min/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=0, self.total=1000000.0, self.flagDict['side']='', self.tradeCount=0, self.count=26938
self.closeSec=1678810799, self.tradeDate='20230315', self.openTime='001500', self.closeTime='001959', self.symbol='BTCUSDT', self.open=26013.5, self.close=25926.4, self.high=26016.9, self.low=25910.3, self.vol=2964.359, self.amt=76973024.9246 
127.0.0.1 - - [15/Mar/2023 00:20:01] "POST / HTTP/1.1" 200 -
2023-03-15 00:20:01,710:INFO:sr_min:main.py:172:handleKline:449472: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5759  20230314   235500    235959  ...         0.0        0.0       0
5760  20230315   000000    000459  ...         0.0        0.0       0
5761  20230315   000500    000959  ...         0.0        0.0       0
5762  20230315   001000    001459  ...         0.0        0.0       0
5763  20230315   001500    001959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-03-15 00:20:01,712:INFO:sr_min:main.py:175:handleKline:449472: self.closeSec=1678810799, self.tradeDate='20230315', self.openTime='001500', self.closeTime='001959',self.symbol='BTCUSDT',self.open=26013.5, self.close=25926.4, self.high=26016.9, self.low=25910.3, self.vol=2964.359, self.amt=76973024.9246, ukdf['pct'].iloc[-1]=-0.003352 , ukdf['amount'].iloc[-1]=76973024.9246, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5763, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': []}
type(curSign)=<class 'int'>, curSign=0, self.sign=0
127.0.0.1 - - [15/Mar/2023 00:25:01] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=0, self.total=1000000.0, self.flagDict['side']='', self.tradeCount=0, self.count=26939
self.closeSec=1678811099, self.tradeDate='20230315', self.openTime='002000', self.closeTime='002459', self.symbol='BTCUSDT', self.open=25926.4, self.close=25843.7, self.high=25943.6, self.low=25809.8, self.vol=6885.646, self.amt=178054322.2388 
2023-03-15 00:25:01,690:INFO:sr_min:main.py:172:handleKline:449472: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5760  20230315   000000    000459  ...         0.0        0.0       0
5761  20230315   000500    000959  ...         0.0        0.0       0
5762  20230315   001000    001459  ...         0.0        0.0       0
5763  20230315   001500    001959  ...         0.0        0.0       0
5764  20230315   002000    002459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-03-15 00:25:01,690:INFO:sr_min:main.py:175:handleKline:449472: self.closeSec=1678811099, self.tradeDate='20230315', self.openTime='002000', self.closeTime='002459',self.symbol='BTCUSDT',self.open=25926.4, self.close=25843.7, self.high=25943.6, self.low=25809.8, self.vol=6885.646, self.amt=178054322.2388, ukdf['pct'].iloc[-1]=-0.00319 , ukdf['amount'].iloc[-1]=178054322.2388, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5764, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': []}
type(curSign)=<class 'int'>, curSign=0, self.sign=0


## /root/FIL/strategy/s_rsrs/log.txt ----- -----

723  20230314   120000    155959  1678780799  ...    723  1.056560  1.757535     1.0
724  20230314   160000    195959  1678795199  ...    724  1.049601  1.716673     1.0

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '55.825', 'enterprice': '20070', 'countrevence': '0', 'unrealprofit': '260926.05', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '24744', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=1, self.sign=1
127.0.0.1 - - [15/Mar/2023 00:00:01] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='s_rsrs', self.symbol='BTCUSDT', interval='4h', intervalSec=14400, wid=25, thd=0.6, self.sign=1, self.total=1119287.34225, self.flagDict['side']='buy', self.tradeCount=24, self.count=656
self.closeSec=1678809599, self.tradeDate='20230314', self.openTime='200000', self.closeTime='235959', self.symbol='BTCUSDT', self.open=24747.4, self.close=25911.3, self.high=26489.9, self.low=24405.0, self.vol=572682.237, self.amt=14697773496.76979 
2023-03-15 00:00:01,947:INFO:s_rsrs:main.py:141:handleKline:185271: self.closeSec=1678809599, self.tradeDate='20230314', self.openTime='200000', self.closeTime='235959',self.symbol='BTCUSDT',self.open=24747.4, self.close=25911.3, self.high=26489.9, self.low=24405.0, self.vol=572682.237, self.amt=14697773496.76979 
2023-03-15 00:00:02,027:INFO:s_rsrs:main.py:142:handleKline:185271: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime  ...         vol           amt       pct
721  20230314   040000    075959  ...   88630.517  2.139523e+09 -0.008090
722  20230314   080000    115959  ...  103809.190  2.519117e+09  0.010863
723  20230314   120000    155959  ...  154883.625  3.782950e+09 -0.005250
724  20230314   160000    195959  ...  156510.376  3.834140e+09  0.020427
725  20230314   200000    235959  ...  572682.237  1.469777e+10  0.047035

[5 rows x 11 columns]
2023-03-15 00:00:04,985:INFO:s_rsrs:main.py:151:handleKline:185271: df_s.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec  ...  index      beta    zscore  signal
721  20230314   040000    075959  1678751999  ...    721  1.073077  1.854290     1.0
722  20230314   080000    115959  1678766399  ...    722  1.051448  1.762806     1.0
723  20230314   120000    155959  1678780799  ...    723  1.056560  1.757535     1.0
724  20230314   160000    195959  1678795199  ...    724  1.049601  1.716673     1.0
725  20230314   200000    235959  1678809599  ...    725  1.158051  2.045910     1.0

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '55.825', 'enterprice': '20070', 'countrevence': '0', 'unrealprofit': '326029.165', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '25910.2', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=1, self.sign=1


