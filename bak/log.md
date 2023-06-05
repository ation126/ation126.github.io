# 20230606 00:26:01

## /root/FIL/strategy/amihud/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=373746.4768026, self.flagDict['side']='sell', self.tradeCount=2, self.count=6496
self.closeSec=1685981999, self.tradeDate='20230606', self.openTime='001500', self.closeTime='001959', self.symbol='BTCUSDT', self.open=25891.7, self.close=25839.3, self.high=25943.3, self.low=25785.0, self.vol=12167.266, self.amt=314860864.9335 
127.0.0.1 - - [06/Jun/2023 00:20:01] "POST / HTTP/1.1" 200 -
2023-06-06 00:20:07,427:INFO:amihud:main.py:172:handleKline:2219019: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5759  20230605   235500    235959  ...         0.0        0.0       0
5760  20230606   000000    000459  ...         0.0        0.0       0
5761  20230606   000500    000959  ...         0.0        0.0       0
5762  20230606   001000    001459  ...         0.0        0.0       0
5763  20230606   001500    001959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-06-06 00:20:07,457:INFO:amihud:main.py:175:handleKline:2219019: self.closeSec=1685981999, self.tradeDate='20230606', self.openTime='001500', self.closeTime='001959',self.symbol='BTCUSDT',self.open=25891.7, self.close=25839.3, self.high=25943.3, self.low=25785.0, self.vol=12167.266, self.amt=314860864.9335, ukdf['pct'].iloc[-1]=-0.001769 , ukdf['amount'].iloc[-1]=314860864.9335, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5763, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '13.926', 'enterprice': '26864.9', 'countrevence': '0', 'unrealprofit': '14407.8396', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '25830.3', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1
127.0.0.1 - - [06/Jun/2023 00:25:00] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=373746.4768026, self.flagDict['side']='sell', self.tradeCount=2, self.count=6497
self.closeSec=1685982299, self.tradeDate='20230606', self.openTime='002000', self.closeTime='002459', self.symbol='BTCUSDT', self.open=25837.5, self.close=25830.1, self.high=25848.4, self.low=25740.0, self.vol=8612.436, self.amt=222151308.1398 
2023-06-06 00:25:00,867:INFO:amihud:main.py:172:handleKline:2219019: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5760  20230606   000000    000459  ...         0.0        0.0       0
5761  20230606   000500    000959  ...         0.0        0.0       0
5762  20230606   001000    001459  ...         0.0        0.0       0
5763  20230606   001500    001959  ...         0.0        0.0       0
5764  20230606   002000    002459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-06-06 00:25:00,867:INFO:amihud:main.py:175:handleKline:2219019: self.closeSec=1685982299, self.tradeDate='20230606', self.openTime='002000', self.closeTime='002459',self.symbol='BTCUSDT',self.open=25837.5, self.close=25830.1, self.high=25848.4, self.low=25740.0, self.vol=8612.436, self.amt=222151308.1398, ukdf['pct'].iloc[-1]=-0.000356 , ukdf['amount'].iloc[-1]=222151308.1398, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5764, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '13.926', 'enterprice': '26864.9', 'countrevence': '0', 'unrealprofit': '14410.6248', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '25830.1', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1


## /root/FIL/strategy/factorcheck/log.txt ----- -----


self.closeSec=1685981999, self.tradeDate='20230606', self.openTime='001500', self.closeTime='001959', self.symbol='BTCUSDT', self.open=25891.7, self.close=25839.3, self.high=25943.3, self.low=25785.0 
127.0.0.1 - - [06/Jun/2023 00:20:01] "POST / HTTP/1.1" 200 -
2023-06-06 00:20:04,767:INFO:factorcheck2:main.py:126:handleKline:2218005: self.closeSec=1685981999, self.tradeDate='20230606', self.openTime='001500', self.closeTime='001959',self.symbol='BTCUSDT',self.open=25891.7, self.close=25839.3, self.high=25943.3, self.low=25785.0   
2023-06-06 00:20:06,178:INFO:factorcheck2:main.py:127:handleKline:2218005: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1439  20230605   235500    235959  1685980799  ...  26000.1 -0.010391   1727    5
1440  20230606   000000    000459  1685981099  ...  25382.0 -0.018474   1440    0
1441  20230606   000500    000959  1685981399  ...  25441.2  0.008336   1441    1
1442  20230606   001000    001459  1685981699  ...  25683.1  0.005559   1442    2
1443  20230606   001500    001959  1685981999  ...  25785.0 -0.001769   1443    3

[5 rows x 11 columns]
2023-06-06 00:20:06,187:INFO:factorcheck2:main.py:128:handleKline:2218005: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': False, 'isOpen': True, 'isClose': False, 'isTrig': True}
127.0.0.1 - - [06/Jun/2023 00:25:00] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.7136991871733849, self.count=6499 

self.closeSec=1685982299, self.tradeDate='20230606', self.openTime='002000', self.closeTime='002459', self.symbol='BTCUSDT', self.open=25837.5, self.close=25830.1, self.high=25848.4, self.low=25740.0 
2023-06-06 00:25:00,732:INFO:factorcheck2:main.py:126:handleKline:2218005: self.closeSec=1685982299, self.tradeDate='20230606', self.openTime='002000', self.closeTime='002459',self.symbol='BTCUSDT',self.open=25837.5, self.close=25830.1, self.high=25848.4, self.low=25740.0   
2023-06-06 00:25:00,864:INFO:factorcheck2:main.py:127:handleKline:2218005: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1440  20230606   000000    000459  1685981099  ...  25382.0 -0.018474   1440    0
1441  20230606   000500    000959  1685981399  ...  25441.2  0.008336   1441    1
1442  20230606   001000    001459  1685981699  ...  25683.1  0.005559   1442    2
1443  20230606   001500    001959  1685981999  ...  25785.0 -0.001769   1443    3
1444  20230606   002000    002459  1685982299  ...  25740.0 -0.000356   1444    4

[5 rows x 11 columns]
2023-06-06 00:25:00,865:INFO:factorcheck2:main.py:128:handleKline:2218005: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': False, 'isOpen': True, 'isClose': False, 'isTrig': True}


## /root/FIL/strategy/logic/log.txt ----- -----

     pred    prob_0    prob_1  actual  ...       nav  sign   cost_        bm
539     0  0.512240  0.487760       1  ...  1.056809   1.0  0.0000  1.022815
540     0  0.503924  0.496076       1  ...  1.058099   1.0  0.0000  1.024063
541     0  0.510657  0.489343       1  ...  1.059780   1.0  0.0000  1.025690
542     0  0.518566  0.481434       0  ...  1.047375   1.0  0.0000  1.013684
543     1  0.434492  0.565508       0  ...  1.064830  -1.0 -0.0016  0.995168

[5 rows x 10 columns]
2023-06-06 00:00:35,047:INFO:logic:main.py:478:getModel:2218526: df_panel.iloc[-5:,:] :
    pred    prob_0    prob_1  actual  ...       nav  sign   cost_        bm
45     0  0.512384  0.487616       1  ...  1.056809   1.0  0.0000  1.017974
46     0  0.503750  0.496250       1  ...  1.058099   1.0  0.0000  1.018824
47     0  0.510649  0.489351       1  ...  1.059780   1.0  0.0000  1.020443
48     0  0.518467  0.481533       0  ...  1.047375   1.0  0.0000  1.010993
49     1  0.434492  0.565508       0  ...  1.064830  -1.0 -0.0016  0.995168

[5 rows x 10 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '27.623', 'enterprice': '26988.6', 'countrevence': '0', 'unrealprofit': '-26962.09046506102', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '26012.52605926', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
handlebackTrade > queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '27.623', 'enterprice': '26988.6', 'countrevence': '0', 'unrealprofit': '-26962.09046506102', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '26012.52605926', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
2023-06-06 00:00:41,825:INFO:logic:main.py:500:queryContractAssets:2218526: queryContractAssets: assets=ContractAssetReturn{'result': [ContractAsset{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'asset': 'USDT', 'free': '718129.347643', 'total': '718129.347643', 'margin': '0', 'unreal': '0', 'type': 'AssetType_ucontract'}]}
2023-06-06 00:00:42,390:INFO:logic:main.py:587:openSell:2218526: ret = self.client.insertMarketUOrder("simulator", "BTCUSDT", 27.545, "sell"), ret=InsertOrderReturn{'result': 'success', 'clientorderid': '42328F1685980842390I0L64'}
2023-06-06 00:00:42,414:INFO:logic:main.py:494:insertFactor:2218526: curDateTime:6060000, name:logic, symbol:BTCUSDT, tradeDate:20230605, closeTime:235959, close:25992.7, sign:-1, total:718129.347643, side:sell  
127.0.0.1 - - [06/Jun/2023 00:00:42] "POST / HTTP/1.1" 200 -
2023-06-06 00:00:42,414:INFO:logic:main.py:661:handleOrderNew:2218526: handleOrderNew: data=OrderType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'clientorderid': '42327F1685980836728I0L64', 'symbol': 'BTCUSDT', 'gatewayorderid': 1685980837171264, 'quantity': '27.623', 'price': '25935', 'stopprice': '0', 'ordertype': '', 'side': 'SELL', 'status': 'FILLED', 'positionside': 'SHORT', 'createtime': 1685980835842, 'updatetime': 1685980837171, 'tradetype': 'usdt', 'selfid': 42327, 'filltrades': [TradeType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'tradeid': 1685980837171, 'clientorderid': '42327F1685980836728I0L64', 'price': '25935', 'quantity': '27.623', 'commission': '716.402505', 'commissionasset': 'USDT', 'tradetime': 1685980837171, 'tradetype': 'usdt', 'gatetype': 'simulator', 'handletime': 1685980837171}], 'gatetype': 'simulator', 'handletime': 0}
127.0.0.1 - - [06/Jun/2023 00:00:42] "POST / HTTP/1.1" 200 -
2023-06-06 00:00:42,417:INFO:logic:main.py:664:handleOrderFilled:2218526: handleOrderFilled: data=OrderType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'clientorderid': '42327F1685980836728I0L64', 'symbol': 'BTCUSDT', 'gatewayorderid': 1685980837171264, 'quantity': '27.623', 'price': '25935', 'stopprice': '0', 'ordertype': '', 'side': 'SELL', 'status': 'FILLED', 'positionside': 'SHORT', 'createtime': 1685980835842, 'updatetime': 1685980837171, 'tradetype': 'usdt', 'selfid': 42327, 'filltrades': [TradeType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'tradeid': 1685980837171, 'clientorderid': '42327F1685980836728I0L64', 'price': '25935', 'quantity': '27.623', 'commission': '716.402505', 'commissionasset': 'USDT', 'tradetime': 1685980837171, 'tradetype': 'usdt', 'gatetype': 'simulator', 'handletime': 1685980837171}], 'gatetype': 'simulator', 'handletime': 0}
127.0.0.1 - - [06/Jun/2023 00:00:42] "POST / HTTP/1.1" 200 -
2023-06-06 00:00:42,810:INFO:logic:main.py:661:handleOrderNew:2218526: handleOrderNew: data=OrderType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'clientorderid': '42328F1685980842390I0L64', 'symbol': 'BTCUSDT', 'gatewayorderid': 1685980842791698, 'quantity': '27.545', 'price': '25948.8', 'stopprice': '0', 'ordertype': '', 'side': 'SELL', 'status': 'FILLED', 'positionside': 'SHORT', 'createtime': 1685980841843, 'updatetime': 1685980842791, 'tradetype': 'usdt', 'selfid': 42328, 'filltrades': [TradeType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'tradeid': 1685980842791, 'clientorderid': '42328F1685980842390I0L64', 'price': '25948.8', 'quantity': '27.545', 'commission': '714.759696', 'commissionasset': 'USDT', 'tradetime': 1685980842791, 'tradetype': 'usdt', 'gatetype': 'simulator', 'handletime': 1685980842791}], 'gatetype': 'simulator', 'handletime': 0}
127.0.0.1 - - [06/Jun/2023 00:00:43] "POST / HTTP/1.1" 200 -
2023-06-06 00:00:43,023:INFO:logic:main.py:664:handleOrderFilled:2218526: handleOrderFilled: data=OrderType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'clientorderid': '42328F1685980842390I0L64', 'symbol': 'BTCUSDT', 'gatewayorderid': 1685980842791698, 'quantity': '27.545', 'price': '25948.8', 'stopprice': '0', 'ordertype': '', 'side': 'SELL', 'status': 'FILLED', 'positionside': 'SHORT', 'createtime': 1685980841843, 'updatetime': 1685980842791, 'tradetype': 'usdt', 'selfid': 42328, 'filltrades': [TradeType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'tradeid': 1685980842791, 'clientorderid': '42328F1685980842390I0L64', 'price': '25948.8', 'quantity': '27.545', 'commission': '714.759696', 'commissionasset': 'USDT', 'tradetime': 1685980842791, 'tradetype': 'usdt', 'gatetype': 'simulator', 'handletime': 1685980842791}], 'gatetype': 'simulator', 'handletime': 0}


## /root/FIL/strategy/modifiedmom/log.txt ----- -----

127.0.0.1 - - [06/Jun/2023 00:00:04] "POST / HTTP/1.1" 200 -
2023-06-06 00:00:04,546:INFO:modifiedmom:main.py:319:handleOrderFilled:2218259: handleOrderFilled: data=OrderType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'clientorderid': '42325F1685980803877I0L59', 'symbol': 'BTCUSDT', 'gatewayorderid': 1685980804297649, 'quantity': '25.041', 'price': '26001.3', 'stopprice': '0', 'ordertype': '', 'side': 'BUY', 'status': 'FILLED', 'positionside': 'LONG', 'createtime': 1685980802885, 'updatetime': 1685980804297, 'tradetype': 'usdt', 'selfid': 42325, 'filltrades': [TradeType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'tradeid': 1685980804297, 'clientorderid': '42325F1685980803877I0L59', 'price': '26001.3', 'quantity': '25.041', 'commission': '651.0985533', 'commissionasset': 'USDT', 'tradetime': 1685980804297, 'tradetype': 'usdt', 'gatetype': 'simulator', 'handletime': 1685980804297}], 'gatetype': 'simulator', 'handletime': 0}

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=3248 

self.closeSec=1685981399, self.tradeDate='20230606', self.openTime='000000', self.closeTime='000959', self.symbol='BTCUSDT', self.open='25991.9', self.close='25742'
127.0.0.1 - - [06/Jun/2023 00:10:01] "POST / HTTP/1.1" 200 -
2023-06-06 00:10:01,152:INFO:modifiedmom:main.py:144:handleKline:2218259: self.closeSec=1685981399, self.tradeDate='20230606', self.openTime='000000', self.closeTime='000959',self.symbol='BTCUSDT',self.open='25991.9', self.close='25742'
2023-06-06 00:10:01,169:INFO:modifiedmom:main.py:145:handleKline:2218259: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
572  20230605   232000    232959  1685978999  26617.5  26476.5 -0.005204
573  20230605   233000    233959  1685979599  26476.4    26461 -0.000585
574  20230605   234000    234959  1685980199  26463.1  26409.1 -0.001961
575  20230605   235000    235959  1685980799  26411.5  25992.7 -0.015767
576  20230606   000000    000959  1685981399  25991.9    25742 -0.009645
2023-06-06 00:10:01,169:INFO:modifiedmom:main.py:146:handleKline:2218259: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=3249 

self.closeSec=1685981999, self.tradeDate='20230606', self.openTime='001000', self.closeTime='001959', self.symbol='BTCUSDT', self.open='25741.6', self.close='25839.3'
127.0.0.1 - - [06/Jun/2023 00:20:04] "POST / HTTP/1.1" 200 -
2023-06-06 00:20:07,367:INFO:modifiedmom:main.py:144:handleKline:2218259: self.closeSec=1685981999, self.tradeDate='20230606', self.openTime='001000', self.closeTime='001959',self.symbol='BTCUSDT',self.open='25741.6', self.close='25839.3'
2023-06-06 00:20:08,168:INFO:modifiedmom:main.py:145:handleKline:2218259: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
573  20230605   233000    233959  1685979599  26476.4    26461 -0.000585
574  20230605   234000    234959  1685980199  26463.1  26409.1 -0.001961
575  20230605   235000    235959  1685980799  26411.5  25992.7 -0.015767
576  20230606   000000    000959  1685981399  25991.9    25742 -0.009645
577  20230606   001000    001959  1685981999  25741.6  25839.3  0.003780
2023-06-06 00:20:08,177:INFO:modifiedmom:main.py:146:handleKline:2218259: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False}


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

2023-06-06 00:00:02,313:INFO:pyemd2:main.py:127:handleKline:2217508: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}
2023-06-06 00:00:02,436:INFO:pyemd2:main.py:190:insertFactor:2217508: curDateTime:6060000, name:pyemd2, symbol:BTCUSDT, tradeDate:20230605, closeTime:235959, close:25992.7, total:975635.9291773, pct_pre:-0.015223701588960026, thd:-1.1991893149358412, side:sell 

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=3251 

self.closeSec=1685981399, self.tradeDate='20230606', self.openTime='000000', self.closeTime='000959', self.symbol='BTCUSDT', self.open='25991.9', self.close='25742'
2023-06-06 00:10:01,152:INFO:pyemd2:main.py:125:handleKline:2217508: self.closeSec=1685981399, self.tradeDate='20230606', self.openTime='000000', self.closeTime='000959',self.symbol='BTCUSDT',self.open='25991.9', self.close='25742'
127.0.0.1 - - [06/Jun/2023 00:10:01] "POST / HTTP/1.1" 200 -
2023-06-06 00:10:01,176:INFO:pyemd2:main.py:126:handleKline:2217508: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17420  20230605   232000    232959  1685978999  26617.5  26476.5
17421  20230605   233000    233959  1685979599  26476.4    26461
17422  20230605   234000    234959  1685980199  26463.1  26409.1
17423  20230605   235000    235959  1685980799  26411.5  25992.7
17424  20230606   000000    000959  1685981399  25991.9    25742
2023-06-06 00:10:01,176:INFO:pyemd2:main.py:127:handleKline:2217508: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=3252 

self.closeSec=1685981999, self.tradeDate='20230606', self.openTime='001000', self.closeTime='001959', self.symbol='BTCUSDT', self.open='25741.6', self.close='25839.3'
127.0.0.1 - - [06/Jun/2023 00:20:04] "POST / HTTP/1.1" 200 -
2023-06-06 00:20:09,268:INFO:pyemd2:main.py:125:handleKline:2217508: self.closeSec=1685981999, self.tradeDate='20230606', self.openTime='001000', self.closeTime='001959',self.symbol='BTCUSDT',self.open='25741.6', self.close='25839.3'
2023-06-06 00:20:09,419:INFO:pyemd2:main.py:126:handleKline:2217508: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17421  20230605   233000    233959  1685979599  26476.4    26461
17422  20230605   234000    234959  1685980199  26463.1  26409.1
17423  20230605   235000    235959  1685980799  26411.5  25992.7
17424  20230606   000000    000959  1685981399  25991.9    25742
17425  20230606   001000    001959  1685981999  25741.6  25839.3
2023-06-06 00:20:09,419:INFO:pyemd2:main.py:127:handleKline:2217508: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}


## /root/FIL/strategy/similarity/log.txt ----- -----

2023-06-06 00:00:04,756:INFO:testStrategy:main.py:308:handleOrderFilled:2217133: handleOrderFilled: data=OrderType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'clientorderid': '42326F1685980803891I0L2', 'symbol': 'BTCUSDT', 'gatewayorderid': 1685980804304389, 'quantity': '43.888', 'price': '26001.3', 'stopprice': '0', 'ordertype': '', 'side': 'BUY', 'status': 'FILLED', 'positionside': 'LONG', 'createtime': 1685980802860, 'updatetime': 1685980804304, 'tradetype': 'usdt', 'selfid': 42326, 'filltrades': [TradeType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'tradeid': 1685980804304, 'clientorderid': '42326F1685980803891I0L2', 'price': '26001.3', 'quantity': '43.888', 'commission': '1141.1450544', 'commissionasset': 'USDT', 'tradetime': 1685980804304, 'tradetype': 'usdt', 'gatetype': 'simulator', 'handletime': 1685980804304}], 'gatetype': 'simulator', 'handletime': 0}
127.0.0.1 - - [06/Jun/2023 00:00:04] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [06/Jun/2023 00:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=3251 

self.closeSec=1685981399, self.tradeDate='20230606', self.openTime='000000', self.closeTime='000959', self.symbol='BTCUSDT', self.open='25991.9', self.close='25742'
2023-06-06 00:10:01,139:INFO:testStrategy:main.py:101:handleKline:2217133: self.closeSec=1685981399, self.tradeDate='20230606', self.openTime='000000', self.closeTime='000959',self.symbol='BTCUSDT',self.open='25991.9', self.close='25742'
2023-06-06 00:10:01,171:INFO:testStrategy:main.py:102:handleKline:2217133: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12236  20230605   232000    232959  1685978999  26617.5  26476.5
12237  20230605   233000    233959  1685979599  26476.4    26461
12238  20230605   234000    234959  1685980199  26463.1  26409.1
12239  20230605   235000    235959  1685980799  26411.5  25992.7
12240  20230606   000000    000959  1685981399  25991.9    25742
2023-06-06 00:10:01,171:INFO:testStrategy:main.py:103:handleKline:2217133: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False, 'isCorr': False}

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=3252 

self.closeSec=1685981999, self.tradeDate='20230606', self.openTime='001000', self.closeTime='001959', self.symbol='BTCUSDT', self.open='25741.6', self.close='25839.3'
127.0.0.1 - - [06/Jun/2023 00:20:04] "POST / HTTP/1.1" 200 -
2023-06-06 00:20:08,889:INFO:testStrategy:main.py:101:handleKline:2217133: self.closeSec=1685981999, self.tradeDate='20230606', self.openTime='001000', self.closeTime='001959',self.symbol='BTCUSDT',self.open='25741.6', self.close='25839.3'
2023-06-06 00:20:09,220:INFO:testStrategy:main.py:102:handleKline:2217133: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12237  20230605   233000    233959  1685979599  26476.4    26461
12238  20230605   234000    234959  1685980199  26463.1  26409.1
12239  20230605   235000    235959  1685980799  26411.5  25992.7
12240  20230606   000000    000959  1685981399  25991.9    25742
12241  20230606   001000    001959  1685981999  25741.6  25839.3
2023-06-06 00:20:09,221:INFO:testStrategy:main.py:103:handleKline:2217133: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False, 'isCorr': False}


## /root/FIL/strategy/sr_min/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=1, self.total=996015.990996, self.flagDict['side']='buy', self.tradeCount=1, self.count=6496
self.closeSec=1685981999, self.tradeDate='20230606', self.openTime='001500', self.closeTime='001959', self.symbol='BTCUSDT', self.open=25891.7, self.close=25839.3, self.high=25943.3, self.low=25785.0, self.vol=12167.266, self.amt=314860864.9335 
127.0.0.1 - - [06/Jun/2023 00:20:01] "POST / HTTP/1.1" 200 -
2023-06-06 00:20:07,267:INFO:sr_min:main.py:172:handleKline:2219263: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5759  20230605   235500    235959  ...         0.0        0.0       0
5760  20230606   000000    000459  ...         0.0        0.0       0
5761  20230606   000500    000959  ...         0.0        0.0       0
5762  20230606   001000    001459  ...         0.0        0.0       0
5763  20230606   001500    001959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-06-06 00:20:07,300:INFO:sr_min:main.py:175:handleKline:2219263: self.closeSec=1685981999, self.tradeDate='20230606', self.openTime='001500', self.closeTime='001959',self.symbol='BTCUSDT',self.open=25891.7, self.close=25839.3, self.high=25943.3, self.low=25785.0, self.vol=12167.266, self.amt=314860864.9335, ukdf['pct'].iloc[-1]=-0.001769 , ukdf['amount'].iloc[-1]=314860864.9335, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5763, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '37.141', 'enterprice': '26844', 'countrevence': '0', 'unrealprofit': '-37649.8317', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '25830.3', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=1
127.0.0.1 - - [06/Jun/2023 00:25:00] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=1, self.total=996015.990996, self.flagDict['side']='buy', self.tradeCount=1, self.count=6497
self.closeSec=1685982299, self.tradeDate='20230606', self.openTime='002000', self.closeTime='002459', self.symbol='BTCUSDT', self.open=25837.5, self.close=25830.1, self.high=25848.4, self.low=25740.0, self.vol=8612.436, self.amt=222151308.1398 
2023-06-06 00:25:00,889:INFO:sr_min:main.py:172:handleKline:2219263: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5760  20230606   000000    000459  ...         0.0        0.0       0
5761  20230606   000500    000959  ...         0.0        0.0       0
5762  20230606   001000    001459  ...         0.0        0.0       0
5763  20230606   001500    001959  ...         0.0        0.0       0
5764  20230606   002000    002459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-06-06 00:25:00,891:INFO:sr_min:main.py:175:handleKline:2219263: self.closeSec=1685982299, self.tradeDate='20230606', self.openTime='002000', self.closeTime='002459',self.symbol='BTCUSDT',self.open=25837.5, self.close=25830.1, self.high=25848.4, self.low=25740.0, self.vol=8612.436, self.amt=222151308.1398, ukdf['pct'].iloc[-1]=-0.000356 , ukdf['amount'].iloc[-1]=222151308.1398, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5764, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '37.141', 'enterprice': '26844', 'countrevence': '0', 'unrealprofit': '-37657.2599', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '25830.1', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=1


## /root/FIL/strategy/s_rsrs/log.txt ----- -----

723  20230605   120000    155959  1685951999  ...    723  0.159485 -1.142144    -1.0
724  20230605   160000    195959  1685966399  ...    724  0.179079 -1.084978    -1.0

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '55.166', 'enterprice': '27078.6', 'countrevence': '0', 'unrealprofit': '17298.26880879874', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '26765.03242561', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-1, self.sign=-1
127.0.0.1 - - [06/Jun/2023 00:00:01] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='s_rsrs', self.symbol='BTCUSDT', interval='4h', intervalSec=14400, wid=25, thd=0.6, self.sign=-1, self.total=1492324.2295523998, self.flagDict['side']='sell', self.tradeCount=4, self.count=135
self.closeSec=1685980799, self.tradeDate='20230605', self.openTime='200000', self.closeTime='235959', self.symbol='BTCUSDT', self.open=26760.2, self.close=25992.7, self.high=26809.9, self.low=25971.0, self.vol=190124.033, self.amt=5039568875.42779 
2023-06-06 00:00:01,854:INFO:s_rsrs:main.py:141:handleKline:2218689: self.closeSec=1685980799, self.tradeDate='20230605', self.openTime='200000', self.closeTime='235959',self.symbol='BTCUSDT',self.open=26760.2, self.close=25992.7, self.high=26809.9, self.low=25971.0, self.vol=190124.033, self.amt=5039568875.42779 
2023-06-06 00:00:01,886:INFO:s_rsrs:main.py:142:handleKline:2218689: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime  ...         vol           amt       pct
721  20230605   040000    075959  ...   83709.147  2.280936e+09 -0.003771
722  20230605   080000    115959  ...   80451.139  2.167862e+09 -0.009833
723  20230605   120000    155959  ...   52410.386  1.404439e+09 -0.000622
724  20230605   160000    195959  ...   48150.374  1.288244e+09 -0.002204
725  20230605   200000    235959  ...  190124.033  5.039569e+09 -0.028677

[5 rows x 11 columns]
2023-06-06 00:00:03,951:INFO:s_rsrs:main.py:151:handleKline:2218689: df_s.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec  ...  index      beta    zscore  signal
721  20230605   040000    075959  1685923199  ...    721  0.045863 -1.488578    -1.0
722  20230605   080000    115959  1685937599  ...    722  0.044106 -1.480460    -1.0
723  20230605   120000    155959  1685951999  ...    723  0.159485 -1.142144    -1.0
724  20230605   160000    195959  1685966399  ...    724  0.179079 -1.084978    -1.0
725  20230605   200000    235959  1685980799  ...    725  0.125043 -1.239245    -1.0

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '55.166', 'enterprice': '27078.6', 'countrevence': '0', 'unrealprofit': '57431.70562330574', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '26037.52931111', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-1, self.sign=-1


