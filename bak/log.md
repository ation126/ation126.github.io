# 20230717 00:26:01

## /root/FIL/strategy/amihud/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=373746.4768026, self.flagDict['side']='sell', self.tradeCount=2, self.count=18304
self.closeSec=1689524399, self.tradeDate='20230717', self.openTime='001500', self.closeTime='001959', self.symbol='BTCUSDT', self.open=30349.1, self.close=30331.9, self.high=30349.2, self.low=30319.0, self.vol=1160.026, self.amt=35191501.0868 
127.0.0.1 - - [17/Jul/2023 00:20:01] "POST / HTTP/1.1" 200 -
2023-07-17 00:20:05,921:INFO:amihud:main.py:172:handleKline:2219019: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5759  20230716   235500    235959  ...         0.0        0.0       0
5760  20230717   000000    000459  ...         0.0        0.0       0
5761  20230717   000500    000959  ...         0.0        0.0       0
5762  20230717   001000    001459  ...         0.0        0.0       0
5763  20230717   001500    001959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-07-17 00:20:05,940:INFO:amihud:main.py:175:handleKline:2219019: self.closeSec=1689524399, self.tradeDate='20230717', self.openTime='001500', self.closeTime='001959',self.symbol='BTCUSDT',self.open=30349.1, self.close=30331.9, self.high=30349.2, self.low=30319.0, self.vol=1160.026, self.amt=35191501.0868, ukdf['pct'].iloc[-1]=-0.000563 , ukdf['amount'].iloc[-1]=35191501.0868, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5763, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '13.926', 'enterprice': '26864.9', 'countrevence': '0', 'unrealprofit': '-48282.8346', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '30332', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1
--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=373746.4768026, self.flagDict['side']='sell', self.tradeCount=2, self.count=18305
self.closeSec=1689524699, self.tradeDate='20230717', self.openTime='002000', self.closeTime='002459', self.symbol='BTCUSDT', self.open=30332.0, self.close=30336.4, self.high=30343.6, self.low=30305.5, self.vol=1096.559, self.amt=33252874.1739 
127.0.0.1 - - [17/Jul/2023 00:25:00] "POST / HTTP/1.1" 200 -
2023-07-17 00:25:00,755:INFO:amihud:main.py:172:handleKline:2219019: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5760  20230717   000000    000459  ...         0.0        0.0       0
5761  20230717   000500    000959  ...         0.0        0.0       0
5762  20230717   001000    001459  ...         0.0        0.0       0
5763  20230717   001500    001959  ...         0.0        0.0       0
5764  20230717   002000    002459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-07-17 00:25:00,756:INFO:amihud:main.py:175:handleKline:2219019: self.closeSec=1689524699, self.tradeDate='20230717', self.openTime='002000', self.closeTime='002459',self.symbol='BTCUSDT',self.open=30332.0, self.close=30336.4, self.high=30343.6, self.low=30305.5, self.vol=1096.559, self.amt=33252874.1739, ukdf['pct'].iloc[-1]=0.000148 , ukdf['amount'].iloc[-1]=33252874.1739, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5764, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '13.926', 'enterprice': '26864.9', 'countrevence': '0', 'unrealprofit': '-48397.66551387504', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '30340.24579304', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1


## /root/FIL/strategy/factorcheck/log.txt ----- -----


self.closeSec=1689524399, self.tradeDate='20230717', self.openTime='001500', self.closeTime='001959', self.symbol='BTCUSDT', self.open=30349.1, self.close=30331.9, self.high=30349.2, self.low=30319.0 
127.0.0.1 - - [17/Jul/2023 00:20:01] "POST / HTTP/1.1" 200 -
2023-07-17 00:20:03,750:INFO:factorcheck2:main.py:126:handleKline:2218005: self.closeSec=1689524399, self.tradeDate='20230717', self.openTime='001500', self.closeTime='001959',self.symbol='BTCUSDT',self.open=30349.1, self.close=30331.9, self.high=30349.2, self.low=30319.0   
2023-07-17 00:20:04,950:INFO:factorcheck2:main.py:127:handleKline:2218005: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1439  20230716   235500    235959  1689523199  ...  30363.4 -0.000069   1727    5
1440  20230717   000000    000459  1689523499  ...  30360.0  0.000076   1440    0
1441  20230717   000500    000959  1689523799  ...  30349.0 -0.000408   1441    1
1442  20230717   001000    001459  1689524099  ...  30349.0 -0.000224   1442    2
1443  20230717   001500    001959  1689524399  ...  30319.0 -0.000563   1443    3

[5 rows x 11 columns]
2023-07-17 00:20:04,960:INFO:factorcheck2:main.py:128:handleKline:2218005: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': False, 'isOpen': True, 'isClose': False, 'isTrig': True}
127.0.0.1 - - [17/Jul/2023 00:25:00] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=20, self.factor=0.44716074973479997, self.count=18307 

self.closeSec=1689524699, self.tradeDate='20230717', self.openTime='002000', self.closeTime='002459', self.symbol='BTCUSDT', self.open=30332.0, self.close=30336.4, self.high=30343.6, self.low=30305.5 
2023-07-17 00:25:00,724:INFO:factorcheck2:main.py:126:handleKline:2218005: self.closeSec=1689524699, self.tradeDate='20230717', self.openTime='002000', self.closeTime='002459',self.symbol='BTCUSDT',self.open=30332.0, self.close=30336.4, self.high=30343.6, self.low=30305.5   
2023-07-17 00:25:00,740:INFO:factorcheck2:main.py:127:handleKline:2218005: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1440  20230717   000000    000459  1689523499  ...  30360.0  0.000076   1440    0
1441  20230717   000500    000959  1689523799  ...  30349.0 -0.000408   1441    1
1442  20230717   001000    001459  1689524099  ...  30349.0 -0.000224   1442    2
1443  20230717   001500    001959  1689524399  ...  30319.0 -0.000563   1443    3
1444  20230717   002000    002459  1689524699  ...  30305.5  0.000148   1444    4

[5 rows x 11 columns]
2023-07-17 00:25:00,741:INFO:factorcheck2:main.py:128:handleKline:2218005: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': False, 'isOpen': True, 'isClose': False, 'isTrig': True}


## /root/FIL/strategy/logic/log.txt ----- -----

539     0  0.511151  0.488849       1  ...  1.010460   1.0    0.0  0.984610
540     0  0.514791  0.485209       1  ...  1.013702   1.0    0.0  0.987769
541     0  0.546528  0.453472       0  ...  1.013669   1.0    0.0  0.987736
542     0  0.522845  0.477155       1  ...  1.013792   1.0    0.0  0.987857
543     0  0.523087  0.476913       0  ...  1.012911   1.0    0.0  0.986999

[5 rows x 10 columns]
2023-07-17 00:00:17,819:INFO:logic:main.py:478:getModel:2218526: df_panel.iloc[-5:,:] :
    pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
45     0  0.511533  0.488467       1  ...  1.010460   1.0    0.0  0.984981
46     0  0.513836  0.486164       1  ...  1.008509  -1.0    0.0  0.986663
47     0  0.546463  0.453537       0  ...  1.008542  -1.0    0.0  0.986630
48     0  0.522438  0.477562       1  ...  1.008419  -1.0    0.0  0.987613
49     0  0.523087  0.476913       0  ...  1.012911   1.0    0.0  0.986999

[5 rows x 10 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '24.197', 'enterprice': '30396.2', 'countrevence': '0', 'unrealprofit': '776.54098167784', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '30364.10755128', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
handlebackTrade > queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '24.197', 'enterprice': '30396.2', 'countrevence': '0', 'unrealprofit': '776.54098167784', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '30364.10755128', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
2023-07-17 00:00:24,488:INFO:logic:main.py:500:queryContractAssets:2218526: queryContractAssets: assets=ContractAssetReturn{'result': [ContractAsset{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'asset': 'USDT', 'free': '737673.9874199', 'total': '737673.9874199', 'margin': '0', 'unreal': '0', 'type': 'AssetType_ucontract'}]}
2023-07-17 00:00:24,960:DEBUG:logic:main.py:571:openBuy:2218526: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': True, 'isCloseBuy': False, 'isCloseSell': False, 'isOpen': True, 'isClose': False, 'isTrig': False}
2023-07-17 00:00:24,960:INFO:logic:main.py:572:openBuy:2218526: ret = self.client.insertMarketUOrder("simulator", "BTCUSDT", 24.219, "buy"), ret=InsertOrderReturn{'result': 'success', 'clientorderid': '42664F1689523224959I0L64'}
2023-07-17 00:00:24,975:INFO:logic:main.py:494:insertFactor:2218526: curDateTime:7170000, name:logic, symbol:BTCUSDT, tradeDate:20230716, closeTime:235959, close:30365.9, sign:1, total:737673.9874199, side:buy  
127.0.0.1 - - [17/Jul/2023 00:00:24] "POST / HTTP/1.1" 200 -
2023-07-17 00:00:24,976:INFO:logic:main.py:661:handleOrderNew:2218526: handleOrderNew: data=OrderType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'clientorderid': '42663F1689523219424I0L64', 'symbol': 'BTCUSDT', 'gatewayorderid': 1689523219814039, 'quantity': '24.197', 'price': '30361.6', 'stopprice': '0', 'ordertype': '', 'side': 'BUY', 'status': 'FILLED', 'positionside': 'LONG', 'createtime': 1689523218622, 'updatetime': 1689523219814, 'tradetype': 'usdt', 'selfid': 42663, 'filltrades': [TradeType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'tradeid': 1689523219814, 'clientorderid': '42663F1689523219424I0L64', 'price': '30361.6', 'quantity': '24.197', 'commission': '734.6596352', 'commissionasset': 'USDT', 'tradetime': 1689523219814, 'tradetype': 'usdt', 'gatetype': 'simulator', 'handletime': 1689523219814}], 'gatetype': 'simulator', 'handletime': 0}
127.0.0.1 - - [17/Jul/2023 00:00:24] "POST / HTTP/1.1" 200 -
2023-07-17 00:00:24,977:INFO:logic:main.py:664:handleOrderFilled:2218526: handleOrderFilled: data=OrderType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'clientorderid': '42663F1689523219424I0L64', 'symbol': 'BTCUSDT', 'gatewayorderid': 1689523219814039, 'quantity': '24.197', 'price': '30361.6', 'stopprice': '0', 'ordertype': '', 'side': 'BUY', 'status': 'FILLED', 'positionside': 'LONG', 'createtime': 1689523218622, 'updatetime': 1689523219814, 'tradetype': 'usdt', 'selfid': 42663, 'filltrades': [TradeType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'tradeid': 1689523219814, 'clientorderid': '42663F1689523219424I0L64', 'price': '30361.6', 'quantity': '24.197', 'commission': '734.6596352', 'commissionasset': 'USDT', 'tradetime': 1689523219814, 'tradetype': 'usdt', 'gatetype': 'simulator', 'handletime': 1689523219814}], 'gatetype': 'simulator', 'handletime': 0}
127.0.0.1 - - [17/Jul/2023 00:00:25] "POST / HTTP/1.1" 200 -
2023-07-17 00:00:25,399:INFO:logic:main.py:661:handleOrderNew:2218526: handleOrderNew: data=OrderType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'clientorderid': '42664F1689523224959I0L64', 'symbol': 'BTCUSDT', 'gatewayorderid': 1689523225370283, 'quantity': '24.219', 'price': '30360.8', 'stopprice': '0', 'ordertype': '', 'side': 'BUY', 'status': 'FILLED', 'positionside': 'LONG', 'createtime': 1689523224498, 'updatetime': 1689523225370, 'tradetype': 'usdt', 'selfid': 42664, 'filltrades': [TradeType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'tradeid': 1689523225370, 'clientorderid': '42664F1689523224959I0L64', 'price': '30360.8', 'quantity': '24.219', 'commission': '735.3082152', 'commissionasset': 'USDT', 'tradetime': 1689523225370, 'tradetype': 'usdt', 'gatetype': 'simulator', 'handletime': 1689523225370}], 'gatetype': 'simulator', 'handletime': 0}
127.0.0.1 - - [17/Jul/2023 00:00:25] "POST / HTTP/1.1" 200 -
2023-07-17 00:00:25,522:INFO:logic:main.py:664:handleOrderFilled:2218526: handleOrderFilled: data=OrderType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'clientorderid': '42664F1689523224959I0L64', 'symbol': 'BTCUSDT', 'gatewayorderid': 1689523225370283, 'quantity': '24.219', 'price': '30360.8', 'stopprice': '0', 'ordertype': '', 'side': 'BUY', 'status': 'FILLED', 'positionside': 'LONG', 'createtime': 1689523224498, 'updatetime': 1689523225370, 'tradetype': 'usdt', 'selfid': 42664, 'filltrades': [TradeType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'tradeid': 1689523225370, 'clientorderid': '42664F1689523224959I0L64', 'price': '30360.8', 'quantity': '24.219', 'commission': '735.3082152', 'commissionasset': 'USDT', 'tradetime': 1689523225370, 'tradetype': 'usdt', 'gatetype': 'simulator', 'handletime': 1689523225370}], 'gatetype': 'simulator', 'handletime': 0}


## /root/FIL/strategy/modifiedmom/log.txt ----- -----

127.0.0.1 - - [17/Jul/2023 00:00:04] "POST / HTTP/1.1" 200 -
2023-07-17 00:00:04,360:INFO:modifiedmom:main.py:319:handleOrderFilled:2218259: handleOrderFilled: data=OrderType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'clientorderid': '42662F1689523203589I0L59', 'symbol': 'BTCUSDT', 'gatewayorderid': 1689523203994747, 'quantity': '24.353', 'price': '30365.9', 'stopprice': '0', 'ordertype': '', 'side': 'SELL', 'status': 'FILLED', 'positionside': 'SHORT', 'createtime': 1689523202677, 'updatetime': 1689523203994, 'tradetype': 'usdt', 'selfid': 42662, 'filltrades': [TradeType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'tradeid': 1689523203994, 'clientorderid': '42662F1689523203589I0L59', 'price': '30365.9', 'quantity': '24.353', 'commission': '739.5007627', 'commissionasset': 'USDT', 'tradetime': 1689523203994, 'tradetype': 'usdt', 'gatetype': 'simulator', 'handletime': 1689523203994}], 'gatetype': 'simulator', 'handletime': 0}

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=9152 

self.closeSec=1689523799, self.tradeDate='20230717', self.openTime='000000', self.closeTime='000959', self.symbol='BTCUSDT', self.open='30365.9', self.close='30355.8'
127.0.0.1 - - [17/Jul/2023 00:10:01] "POST / HTTP/1.1" 200 -
2023-07-17 00:10:01,114:INFO:modifiedmom:main.py:144:handleKline:2218259: self.closeSec=1689523799, self.tradeDate='20230717', self.openTime='000000', self.closeTime='000959',self.symbol='BTCUSDT',self.open='30365.9', self.close='30355.8'
2023-07-17 00:10:01,126:INFO:modifiedmom:main.py:145:handleKline:2218259: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
572  20230716   232000    232959  1689521399  30399.8  30392.3 -0.000243
573  20230716   233000    233959  1689521999  30392.3  30373.6 -0.000615
574  20230716   234000    234959  1689522599  30373.6    30369 -0.000151
575  20230716   235000    235959  1689523199    30369    30366 -0.000099
576  20230717   000000    000959  1689523799  30365.9  30355.8 -0.000336
2023-07-17 00:10:01,126:INFO:modifiedmom:main.py:146:handleKline:2218259: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=9153 

self.closeSec=1689524399, self.tradeDate='20230717', self.openTime='001000', self.closeTime='001959', self.symbol='BTCUSDT', self.open='30355.8', self.close='30331.9'
127.0.0.1 - - [17/Jul/2023 00:20:04] "POST / HTTP/1.1" 200 -
2023-07-17 00:20:06,680:INFO:modifiedmom:main.py:144:handleKline:2218259: self.closeSec=1689524399, self.tradeDate='20230717', self.openTime='001000', self.closeTime='001959',self.symbol='BTCUSDT',self.open='30355.8', self.close='30331.9'
2023-07-17 00:20:07,221:INFO:modifiedmom:main.py:145:handleKline:2218259: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
573  20230716   233000    233959  1689521999  30392.3  30373.6 -0.000615
574  20230716   234000    234959  1689522599  30373.6    30369 -0.000151
575  20230716   235000    235959  1689523199    30369    30366 -0.000099
576  20230717   000000    000959  1689523799  30365.9  30355.8 -0.000336
577  20230717   001000    001959  1689524399  30355.8  30331.9 -0.000787
2023-07-17 00:20:07,229:INFO:modifiedmom:main.py:146:handleKline:2218259: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False}


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

127.0.0.1 - - [17/Jul/2023 00:00:04] "POST / HTTP/1.1" 200 -
2023-07-17 00:00:04,092:INFO:pyemd2:main.py:303:handleOrderFilled:2217508: handleOrderFilled: data=OrderType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'clientorderid': '42660F1689523203510I0L57', 'symbol': 'BTCUSDT', 'gatewayorderid': 1689523203888505, 'quantity': '33.322', 'price': '30365.9', 'stopprice': '0', 'ordertype': '', 'side': 'SELL', 'status': 'FILLED', 'positionside': 'SHORT', 'createtime': 1689523202648, 'updatetime': 1689523203888, 'tradetype': 'usdt', 'selfid': 42660, 'filltrades': [TradeType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'tradeid': 1689523203888, 'clientorderid': '42660F1689523203510I0L57', 'price': '30365.9', 'quantity': '33.322', 'commission': '1011.8525198', 'commissionasset': 'USDT', 'tradetime': 1689523203888, 'tradetype': 'usdt', 'gatetype': 'simulator', 'handletime': 1689523203888}], 'gatetype': 'simulator', 'handletime': 0}

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=9155 

self.closeSec=1689523799, self.tradeDate='20230717', self.openTime='000000', self.closeTime='000959', self.symbol='BTCUSDT', self.open='30365.9', self.close='30355.8'
2023-07-17 00:10:01,122:INFO:pyemd2:main.py:125:handleKline:2217508: self.closeSec=1689523799, self.tradeDate='20230717', self.openTime='000000', self.closeTime='000959',self.symbol='BTCUSDT',self.open='30365.9', self.close='30355.8'
127.0.0.1 - - [17/Jul/2023 00:10:01] "POST / HTTP/1.1" 200 -
2023-07-17 00:10:01,134:INFO:pyemd2:main.py:126:handleKline:2217508: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17420  20230716   232000    232959  1689521399  30399.8  30392.3
17421  20230716   233000    233959  1689521999  30392.3  30373.6
17422  20230716   234000    234959  1689522599  30373.6    30369
17423  20230716   235000    235959  1689523199    30369    30366
17424  20230717   000000    000959  1689523799  30365.9  30355.8
2023-07-17 00:10:01,134:INFO:pyemd2:main.py:127:handleKline:2217508: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=9156 

self.closeSec=1689524399, self.tradeDate='20230717', self.openTime='001000', self.closeTime='001959', self.symbol='BTCUSDT', self.open='30355.8', self.close='30331.9'
127.0.0.1 - - [17/Jul/2023 00:20:04] "POST / HTTP/1.1" 200 -
2023-07-17 00:20:07,943:INFO:pyemd2:main.py:125:handleKline:2217508: self.closeSec=1689524399, self.tradeDate='20230717', self.openTime='001000', self.closeTime='001959',self.symbol='BTCUSDT',self.open='30355.8', self.close='30331.9'
2023-07-17 00:20:08,159:INFO:pyemd2:main.py:126:handleKline:2217508: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17421  20230716   233000    233959  1689521999  30392.3  30373.6
17422  20230716   234000    234959  1689522599  30373.6    30369
17423  20230716   235000    235959  1689523199    30369    30366
17424  20230717   000000    000959  1689523799  30365.9  30355.8
17425  20230717   001000    001959  1689524399  30355.8  30331.9
2023-07-17 00:20:08,160:INFO:pyemd2:main.py:127:handleKline:2217508: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}


## /root/FIL/strategy/similarity/log.txt ----- -----

127.0.0.1 - - [17/Jul/2023 00:00:04] "POST / HTTP/1.1" 200 -
2023-07-17 00:00:04,207:INFO:testStrategy:main.py:308:handleOrderFilled:2217133: handleOrderFilled: data=OrderType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'clientorderid': '42661F1689523203541I0L2', 'symbol': 'BTCUSDT', 'gatewayorderid': 1689523203935295, 'quantity': '37.336', 'price': '30365.9', 'stopprice': '0', 'ordertype': '', 'side': 'SELL', 'status': 'FILLED', 'positionside': 'SHORT', 'createtime': 1689523202703, 'updatetime': 1689523203935, 'tradetype': 'usdt', 'selfid': 42661, 'filltrades': [TradeType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'tradeid': 1689523203935, 'clientorderid': '42661F1689523203541I0L2', 'price': '30365.9', 'quantity': '37.336', 'commission': '1133.7412424', 'commissionasset': 'USDT', 'tradetime': 1689523203935, 'tradetype': 'usdt', 'gatetype': 'simulator', 'handletime': 1689523203935}], 'gatetype': 'simulator', 'handletime': 0}

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=9155 

self.closeSec=1689523799, self.tradeDate='20230717', self.openTime='000000', self.closeTime='000959', self.symbol='BTCUSDT', self.open='30365.9', self.close='30355.8'
127.0.0.1 - - [17/Jul/2023 00:10:01] "POST / HTTP/1.1" 200 -
2023-07-17 00:10:01,113:INFO:testStrategy:main.py:101:handleKline:2217133: self.closeSec=1689523799, self.tradeDate='20230717', self.openTime='000000', self.closeTime='000959',self.symbol='BTCUSDT',self.open='30365.9', self.close='30355.8'
2023-07-17 00:10:01,132:INFO:testStrategy:main.py:102:handleKline:2217133: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12236  20230716   232000    232959  1689521399  30399.8  30392.3
12237  20230716   233000    233959  1689521999  30392.3  30373.6
12238  20230716   234000    234959  1689522599  30373.6    30369
12239  20230716   235000    235959  1689523199    30369    30366
12240  20230717   000000    000959  1689523799  30365.9  30355.8
2023-07-17 00:10:01,132:INFO:testStrategy:main.py:103:handleKline:2217133: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False, 'isCorr': False}

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=9156 

self.closeSec=1689524399, self.tradeDate='20230717', self.openTime='001000', self.closeTime='001959', self.symbol='BTCUSDT', self.open='30355.8', self.close='30331.9'
127.0.0.1 - - [17/Jul/2023 00:20:04] "POST / HTTP/1.1" 200 -
2023-07-17 00:20:07,774:INFO:testStrategy:main.py:101:handleKline:2217133: self.closeSec=1689524399, self.tradeDate='20230717', self.openTime='001000', self.closeTime='001959',self.symbol='BTCUSDT',self.open='30355.8', self.close='30331.9'
2023-07-17 00:20:08,031:INFO:testStrategy:main.py:102:handleKline:2217133: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12237  20230716   233000    233959  1689521999  30392.3  30373.6
12238  20230716   234000    234959  1689522599  30373.6    30369
12239  20230716   235000    235959  1689523199    30369    30366
12240  20230717   000000    000959  1689523799  30365.9  30355.8
12241  20230717   001000    001959  1689524399  30355.8  30331.9
2023-07-17 00:20:08,031:INFO:testStrategy:main.py:103:handleKline:2217133: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False, 'isCorr': False}


## /root/FIL/strategy/sr_min/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=1, self.total=996015.990996, self.flagDict['side']='buy', self.tradeCount=1, self.count=18304
self.closeSec=1689524399, self.tradeDate='20230717', self.openTime='001500', self.closeTime='001959', self.symbol='BTCUSDT', self.open=30349.1, self.close=30331.9, self.high=30349.2, self.low=30319.0, self.vol=1160.026, self.amt=35191501.0868 
127.0.0.1 - - [17/Jul/2023 00:20:01] "POST / HTTP/1.1" 200 -
2023-07-17 00:20:05,979:INFO:sr_min:main.py:172:handleKline:2219263: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5759  20230716   235500    235959  ...         0.0        0.0       0
5760  20230717   000000    000459  ...         0.0        0.0       0
5761  20230717   000500    000959  ...         0.0        0.0       0
5762  20230717   001000    001459  ...         0.0        0.0       0
5763  20230717   001500    001959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-07-17 00:20:05,989:INFO:sr_min:main.py:175:handleKline:2219263: self.closeSec=1689524399, self.tradeDate='20230717', self.openTime='001500', self.closeTime='001959',self.symbol='BTCUSDT',self.open=30349.1, self.close=30331.9, self.high=30349.2, self.low=30319.0, self.vol=1160.026, self.amt=35191501.0868, ukdf['pct'].iloc[-1]=-0.000563 , ukdf['amount'].iloc[-1]=35191501.0868, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5763, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '37.141', 'enterprice': '26844', 'countrevence': '0', 'unrealprofit': '129547.808', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '30332', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=1
127.0.0.1 - - [17/Jul/2023 00:25:00] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=1, self.total=996015.990996, self.flagDict['side']='buy', self.tradeCount=1, self.count=18305
self.closeSec=1689524699, self.tradeDate='20230717', self.openTime='002000', self.closeTime='002459', self.symbol='BTCUSDT', self.open=30332.0, self.close=30336.4, self.high=30343.6, self.low=30305.5, self.vol=1096.559, self.amt=33252874.1739 
2023-07-17 00:25:00,760:INFO:sr_min:main.py:172:handleKline:2219263: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5760  20230717   000000    000459  ...         0.0        0.0       0
5761  20230717   000500    000959  ...         0.0        0.0       0
5762  20230717   001000    001459  ...         0.0        0.0       0
5763  20230717   001500    001959  ...         0.0        0.0       0
5764  20230717   002000    002459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-07-17 00:25:00,760:INFO:sr_min:main.py:175:handleKline:2219263: self.closeSec=1689524699, self.tradeDate='20230717', self.openTime='002000', self.closeTime='002459',self.symbol='BTCUSDT',self.open=30332.0, self.close=30336.4, self.high=30343.6, self.low=30305.5, self.vol=1096.559, self.amt=33252874.1739, ukdf['pct'].iloc[-1]=0.000148 , ukdf['amount'].iloc[-1]=33252874.1739, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5764, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '37.141', 'enterprice': '26844', 'countrevence': '0', 'unrealprofit': '129854.06499929864', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '30340.24579304', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=1


## /root/FIL/strategy/s_rsrs/log.txt ----- -----

723  20230716   120000    155959  1689494399  ...    723  0.655815  1.167779     1.0
724  20230716   160000    195959  1689508799  ...    724  0.677478  1.222248     1.0

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '52.241', 'enterprice': '30511.1', 'countrevence': '0', 'unrealprofit': '-11421.57379057926', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '30292.46762714', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=1, self.sign=1
--handleKline--:  version='2.0.0', self.name='s_rsrs', self.symbol='BTCUSDT', interval='4h', intervalSec=14400, wid=25, thd=0.6, self.sign=1, self.total=1592336.4447248997, self.flagDict['side']='buy', self.tradeCount=11, self.count=381
self.closeSec=1689523199, self.tradeDate='20230716', self.openTime='200000', self.closeTime='235959', self.symbol='BTCUSDT', self.open=30293.6, self.close=30366.0, self.high=30441.6, self.low=30254.1, self.vol=36284.911, self.amt=1101480173.51516 
127.0.0.1 - - [17/Jul/2023 00:00:01] "POST / HTTP/1.1" 200 -
2023-07-17 00:00:01,714:INFO:s_rsrs:main.py:141:handleKline:2218689: self.closeSec=1689523199, self.tradeDate='20230716', self.openTime='200000', self.closeTime='235959',self.symbol='BTCUSDT',self.open=30293.6, self.close=30366.0, self.high=30441.6, self.low=30254.1, self.vol=36284.911, self.amt=1101480173.51516 
2023-07-17 00:00:01,726:INFO:s_rsrs:main.py:142:handleKline:2218689: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime  ...        vol           amt       pct
721  20230716   040000    075959  ...  10464.590  3.168499e+08 -0.001099
722  20230716   080000    115959  ...  43029.584  1.299547e+09 -0.003379
723  20230716   120000    155959  ...  20092.465  6.069392e+08  0.002615
724  20230716   160000    195959  ...  19595.425  5.935232e+08  0.001342
725  20230716   200000    235959  ...  36284.911  1.101480e+09  0.002390

[5 rows x 11 columns]
2023-07-17 00:00:02,510:INFO:s_rsrs:main.py:151:handleKline:2218689: df_s.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec  ...  index      beta    zscore  signal
721  20230716   040000    075959  1689465599  ...    721  0.585894  0.953976     1.0
722  20230716   080000    115959  1689479999  ...    722  0.619016  1.055122     1.0
723  20230716   120000    155959  1689494399  ...    723  0.655815  1.167779     1.0
724  20230716   160000    195959  1689508799  ...    724  0.677478  1.222248     1.0
725  20230716   200000    235959  1689523199  ...    725  0.710944  1.318667     1.0

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '52.241', 'enterprice': '30511.1', 'countrevence': '0', 'unrealprofit': '-7508.67987481745', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '30367.36845055', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=1, self.sign=1


