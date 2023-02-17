# 20230218 00:26:02

## /root/FIL/strategy/amihud/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=993672.4896432, self.flagDict['side']='sell', self.tradeCount=2, self.count=23740
self.closeSec=1676650799, self.tradeDate='20230218', self.openTime='001500', self.closeTime='001959', self.symbol='BTCUSDT', self.open=24265.8, self.close=24143.6, self.high=24274.8, self.low=24138.7, self.vol=5290.019, self.amt=127983381.1306 
127.0.0.1 - - [18/Feb/2023 00:20:01] "POST / HTTP/1.1" 200 -
2023-02-18 00:20:01,754:INFO:amihud:main.py:172:handleKline:200676: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5759  20230217   235500    235959  ...         0.0        0.0       0
5760  20230218   000000    000459  ...         0.0        0.0       0
5761  20230218   000500    000959  ...         0.0        0.0       0
5762  20230218   001000    001459  ...         0.0        0.0       0
5763  20230218   001500    001959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-02-18 00:20:01,756:INFO:amihud:main.py:175:handleKline:200676: self.closeSec=1676650799, self.tradeDate='20230218', self.openTime='001500', self.closeTime='001959',self.symbol='BTCUSDT',self.open=24265.8, self.close=24143.6, self.high=24274.8, self.low=24138.7, self.vol=5290.019, self.amt=127983381.1306, ukdf['pct'].iloc[-1]=-0.005036 , ukdf['amount'].iloc[-1]=127983381.1306, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5763, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '60.176', 'enterprice': '16529.3', 'countrevence': '0', 'unrealprofit': '-458017.54282794304', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '24140.59923604', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1
127.0.0.1 - - [18/Feb/2023 00:25:01] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=993672.4896432, self.flagDict['side']='sell', self.tradeCount=2, self.count=23741
self.closeSec=1676651099, self.tradeDate='20230218', self.openTime='002000', self.closeTime='002459', self.symbol='BTCUSDT', self.open=24143.6, self.close=24034.2, self.high=24143.7, self.low=23992.0, self.vol=10600.482, self.amt=255048559.2022 
2023-02-18 00:25:01,722:INFO:amihud:main.py:172:handleKline:200676: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5760  20230218   000000    000459  ...         0.0        0.0       0
5761  20230218   000500    000959  ...         0.0        0.0       0
5762  20230218   001000    001459  ...         0.0        0.0       0
5763  20230218   001500    001959  ...         0.0        0.0       0
5764  20230218   002000    002459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-02-18 00:25:01,723:INFO:amihud:main.py:175:handleKline:200676: self.closeSec=1676651099, self.tradeDate='20230218', self.openTime='002000', self.closeTime='002459',self.symbol='BTCUSDT',self.open=24143.6, self.close=24034.2, self.high=24143.7, self.low=23992.0, self.vol=10600.482, self.amt=255048559.2022, ukdf['pct'].iloc[-1]=-0.004531 , ukdf['amount'].iloc[-1]=255048559.2022, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5764, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '60.176', 'enterprice': '16529.3', 'countrevence': '0', 'unrealprofit': '-451894.14814672016', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '24038.84114841', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1


## /root/FIL/strategy/factorcheck/log.txt ----- -----


self.closeSec=1676650799, self.tradeDate='20230218', self.openTime='001500', self.closeTime='001959', self.symbol='BTCUSDT', self.open=24265.8, self.close=24143.6, self.high=24274.8, self.low=24138.7 
127.0.0.1 - - [18/Feb/2023 00:20:01] "POST / HTTP/1.1" 200 -
2023-02-18 00:20:01,559:INFO:factorcheck2:main.py:126:handleKline:185239: self.closeSec=1676650799, self.tradeDate='20230218', self.openTime='001500', self.closeTime='001959',self.symbol='BTCUSDT',self.open=24265.8, self.close=24143.6, self.high=24274.8, self.low=24138.7   
2023-02-18 00:20:01,595:INFO:factorcheck2:main.py:127:handleKline:185239: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1439  20230217   235500    235959  1676649599  ...  24105.0  0.000191   1727    5
1440  20230218   000000    000459  1676649899  ...  24100.0 -0.001019   1440    0
1441  20230218   000500    000959  1676650199  ...  24104.1  0.005455   1441    1
1442  20230218   001000    001459  1676650499  ...  24228.9  0.001135   1442    2
1443  20230218   001500    001959  1676650799  ...  24138.7 -0.005036   1443    3

[5 rows x 11 columns]
2023-02-18 00:20:01,596:INFO:factorcheck2:main.py:128:handleKline:185239: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}
127.0.0.1 - - [18/Feb/2023 00:25:01] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=135, self.factor=0.5765130249790025, self.count=24307 

self.closeSec=1676651099, self.tradeDate='20230218', self.openTime='002000', self.closeTime='002459', self.symbol='BTCUSDT', self.open=24143.6, self.close=24034.2, self.high=24143.7, self.low=23992.0 
2023-02-18 00:25:01,618:INFO:factorcheck2:main.py:126:handleKline:185239: self.closeSec=1676651099, self.tradeDate='20230218', self.openTime='002000', self.closeTime='002459',self.symbol='BTCUSDT',self.open=24143.6, self.close=24034.2, self.high=24143.7, self.low=23992.0   
2023-02-18 00:25:01,651:INFO:factorcheck2:main.py:127:handleKline:185239: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1440  20230218   000000    000459  1676649899  ...  24100.0 -0.001019   1440    0
1441  20230218   000500    000959  1676650199  ...  24104.1  0.005455   1441    1
1442  20230218   001000    001459  1676650499  ...  24228.9  0.001135   1442    2
1443  20230218   001500    001959  1676650799  ...  24138.7 -0.005036   1443    3
1444  20230218   002000    002459  1676651099  ...  23992.0 -0.004531   1444    4

[5 rows x 11 columns]
2023-02-18 00:25:01,651:INFO:factorcheck2:main.py:128:handleKline:185239: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}


## /root/FIL/strategy/logic/log.txt ----- -----

539     1  0.499724  0.500276       0  ...  1.120816  -1.0  0.0000  1.039729
540     0  0.505605  0.494395       1  ...  1.116244  -1.0  0.0000  1.043969
541     0  0.542304  0.457696       0  ...  1.117221  -1.0  0.0000  1.043056
542     0  0.522416  0.477584       1  ...  1.109153  -1.0  0.0000  1.050589
543     0  0.567633  0.432367       1  ...  1.112068   1.0 -0.0016  1.055031

[5 rows x 10 columns]
2023-02-18 00:00:33,553:INFO:logic:main.py:478:getModel:885513: df_panel.iloc[-5:,:] :
    pred    prob_0    prob_1  actual  ...       nav  sign   cost_        bm
45     0  0.500226  0.499774       0  ...  1.065104  -1.0  0.0000  1.043767
46     0  0.506687  0.493313       1  ...  1.060760  -1.0  0.0000  1.048393
47     0  0.543398  0.456602       0  ...  1.061688  -1.0  0.0000  1.047475
48     0  0.522904  0.477096       1  ...  1.054021  -1.0  0.0000  1.052996
49     0  0.567633  0.432367       1  ...  1.112068   1.0 -0.0016  1.055031

[5 rows x 10 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '34.282', 'enterprice': '24560.5', 'countrevence': '0', 'unrealprofit': '14098.7279454666', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '24149.2425487', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
handlebackTrade > queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '34.282', 'enterprice': '24560.5', 'countrevence': '0', 'unrealprofit': '14098.7279454666', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '24149.2425487', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
2023-02-18 00:00:39,248:INFO:logic:main.py:500:queryContractAssets:885513: queryContractAssets: assets=ContractAssetReturn{'result': [ContractAsset{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'asset': 'USDT', 'free': '858265.4478991', 'total': '858265.4478991', 'margin': '0', 'unreal': '0', 'type': 'AssetType_ucontract'}]}
2023-02-18 00:00:39,443:DEBUG:logic:main.py:571:openBuy:885513: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': True, 'isCloseBuy': False, 'isCloseSell': False, 'isOpen': True, 'isClose': False, 'isTrig': False}
2023-02-18 00:00:39,443:INFO:logic:main.py:572:openBuy:885513: ret = self.client.insertMarketUOrder("simulator", "BTCUSDT", 35.459, "buy"), ret=InsertOrderReturn{'result': 'success', 'clientorderid': '41759F1676649639442I0L64'}
2023-02-18 00:00:39,459:INFO:logic:main.py:494:insertFactor:885513: curDateTime:2180000, name:logic, symbol:BTCUSDT, tradeDate:20230217, closeTime:235959, close:24131.4, sign:1, total:858265.4478991, side:buy  
127.0.0.1 - - [18/Feb/2023 00:00:39] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [18/Feb/2023 00:00:39] "POST / HTTP/1.1" 200 -
2023-02-18 00:00:39,461:INFO:logic:main.py:661:handleOrderNew:885513: handleOrderNew: data=OrderType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'clientorderid': '41758F1676649634128I0L64', 'symbol': 'BTCUSDT', 'gatewayorderid': 1676649634236376, 'quantity': '34.282', 'price': '24153.7', 'stopprice': '0', 'ordertype': '', 'side': 'BUY', 'status': 'FILLED', 'positionside': 'LONG', 'createtime': 1676649633837, 'updatetime': 1676649634236, 'tradetype': 'usdt', 'selfid': 41758, 'filltrades': [TradeType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'tradeid': 1676649634236, 'clientorderid': '41758F1676649634128I0L64', 'price': '24153.7', 'quantity': '34.282', 'commission': '828.0371434', 'commissionasset': 'USDT', 'tradetime': 1676649634236, 'tradetype': 'usdt', 'gatetype': 'simulator', 'handletime': 1676649634236}], 'gatetype': 'simulator', 'handletime': 0}
2023-02-18 00:00:39,461:INFO:logic:main.py:664:handleOrderFilled:885513: handleOrderFilled: data=OrderType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'clientorderid': '41758F1676649634128I0L64', 'symbol': 'BTCUSDT', 'gatewayorderid': 1676649634236376, 'quantity': '34.282', 'price': '24153.7', 'stopprice': '0', 'ordertype': '', 'side': 'BUY', 'status': 'FILLED', 'positionside': 'LONG', 'createtime': 1676649633837, 'updatetime': 1676649634236, 'tradetype': 'usdt', 'selfid': 41758, 'filltrades': [TradeType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'tradeid': 1676649634236, 'clientorderid': '41758F1676649634128I0L64', 'price': '24153.7', 'quantity': '34.282', 'commission': '828.0371434', 'commissionasset': 'USDT', 'tradetime': 1676649634236, 'tradetype': 'usdt', 'gatetype': 'simulator', 'handletime': 1676649634236}], 'gatetype': 'simulator', 'handletime': 0}
127.0.0.1 - - [18/Feb/2023 00:00:39] "POST / HTTP/1.1" 200 -
2023-02-18 00:00:39,583:INFO:logic:main.py:661:handleOrderNew:885513: handleOrderNew: data=OrderType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'clientorderid': '41759F1676649639442I0L64', 'symbol': 'BTCUSDT', 'gatewayorderid': 1676649639556227, 'quantity': '35.459', 'price': '24163.6', 'stopprice': '0', 'ordertype': '', 'side': 'BUY', 'status': 'FILLED', 'positionside': 'LONG', 'createtime': 1676649639269, 'updatetime': 1676649639556, 'tradetype': 'usdt', 'selfid': 41759, 'filltrades': [TradeType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'tradeid': 1676649639556, 'clientorderid': '41759F1676649639442I0L64', 'price': '24163.6', 'quantity': '35.459', 'commission': '856.8170924', 'commissionasset': 'USDT', 'tradetime': 1676649639556, 'tradetype': 'usdt', 'gatetype': 'simulator', 'handletime': 1676649639556}], 'gatetype': 'simulator', 'handletime': 0}
2023-02-18 00:00:39,827:INFO:logic:main.py:664:handleOrderFilled:885513: handleOrderFilled: data=OrderType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'clientorderid': '41759F1676649639442I0L64', 'symbol': 'BTCUSDT', 'gatewayorderid': 1676649639556227, 'quantity': '35.459', 'price': '24163.6', 'stopprice': '0', 'ordertype': '', 'side': 'BUY', 'status': 'FILLED', 'positionside': 'LONG', 'createtime': 1676649639269, 'updatetime': 1676649639556, 'tradetype': 'usdt', 'selfid': 41759, 'filltrades': [TradeType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'tradeid': 1676649639556, 'clientorderid': '41759F1676649639442I0L64', 'price': '24163.6', 'quantity': '35.459', 'commission': '856.8170924', 'commissionasset': 'USDT', 'tradetime': 1676649639556, 'tradetype': 'usdt', 'gatetype': 'simulator', 'handletime': 1676649639556}], 'gatetype': 'simulator', 'handletime': 0}
127.0.0.1 - - [18/Feb/2023 00:00:39] "POST / HTTP/1.1" 200 -


## /root/FIL/strategy/modifiedmom/log.txt ----- -----

2023-02-18 00:00:03,652:INFO:modifiedmom:main.py:319:handleOrderFilled:185213: handleOrderFilled: data=OrderType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'clientorderid': '41757F1676649603118I0L59', 'symbol': 'BTCUSDT', 'gatewayorderid': 1676649603234512, 'quantity': '40.499', 'price': '24126.3', 'stopprice': '0', 'ordertype': '', 'side': 'BUY', 'status': 'FILLED', 'positionside': 'LONG', 'createtime': 1676649602770, 'updatetime': 1676649603234, 'tradetype': 'usdt', 'selfid': 41757, 'filltrades': [TradeType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'tradeid': 1676649603234, 'clientorderid': '41757F1676649603118I0L59', 'price': '24126.3', 'quantity': '40.499', 'commission': '977.0910237', 'commissionasset': 'USDT', 'tradetime': 1676649603234, 'tradetype': 'usdt', 'gatetype': 'simulator', 'handletime': 1676649603234}], 'gatetype': 'simulator', 'handletime': 0}
127.0.0.1 - - [18/Feb/2023 00:00:03] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [18/Feb/2023 00:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=12152 

self.closeSec=1676650199, self.tradeDate='20230218', self.openTime='000000', self.closeTime='000959', self.symbol='BTCUSDT', self.open='24131.3', self.close='24238.3'
2023-02-18 00:10:01,636:INFO:modifiedmom:main.py:144:handleKline:185213: self.closeSec=1676650199, self.tradeDate='20230218', self.openTime='000000', self.closeTime='000959',self.symbol='BTCUSDT',self.open='24131.3', self.close='24238.3'
2023-02-18 00:10:01,730:INFO:modifiedmom:main.py:145:handleKline:185213: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
572  20230217   232000    232959  1676647799  24116.2  24029.8 -0.003570
573  20230217   233000    233959  1676648399  24024.5  24142.9  0.004707
574  20230217   234000    234959  1676648999  24152.1  24147.9  0.000207
575  20230217   235000    235959  1676649599  24144.6  24131.4 -0.000683
576  20230218   000000    000959  1676650199  24131.3  24238.3  0.004430
2023-02-18 00:10:01,730:INFO:modifiedmom:main.py:146:handleKline:185213: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=12153 

self.closeSec=1676650799, self.tradeDate='20230218', self.openTime='001000', self.closeTime='001959', self.symbol='BTCUSDT', self.open='24238.3', self.close='24143.6'
127.0.0.1 - - [18/Feb/2023 00:20:01] "POST / HTTP/1.1" 200 -
2023-02-18 00:20:01,824:INFO:modifiedmom:main.py:144:handleKline:185213: self.closeSec=1676650799, self.tradeDate='20230218', self.openTime='001000', self.closeTime='001959',self.symbol='BTCUSDT',self.open='24238.3', self.close='24143.6'
2023-02-18 00:20:01,853:INFO:modifiedmom:main.py:145:handleKline:185213: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
573  20230217   233000    233959  1676648399  24024.5  24142.9  0.004707
574  20230217   234000    234959  1676648999  24152.1  24147.9  0.000207
575  20230217   235000    235959  1676649599  24144.6  24131.4 -0.000683
576  20230218   000000    000959  1676650199  24131.3  24238.3  0.004430
577  20230218   001000    001959  1676650799  24238.3  24143.6 -0.003907
2023-02-18 00:20:01,853:INFO:modifiedmom:main.py:146:handleKline:185213: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False}


## /root/FIL/strategy/percentile_regression_step2/log.txt ----- -----

127.0.0.1 - - [17/Feb/2023 23:00:01] "POST / HTTP/1.1" 200 -
2023-02-17 23:00:02,852:DEBUG:percentile_regression_step2:main.py:154:get_signal:1265985: df_id.iloc[-5:,:] :
                 daytime     hms    close  ...  pct_10  pct_20  factor
144  2023/02/17 20:30:00  203000  23869.6  ...     NaN     NaN       0
145  2023/02/17 21:00:00  210000  23804.0  ...     NaN     NaN       0
146  2023/02/17 21:30:00  213000  23781.4  ...     NaN     NaN       0
147  2023/02/17 22:00:00  220000  23878.4  ...     NaN     NaN       0
148  2023/02/17 22:30:00  223000  23857.5  ...     NaN     NaN       0

[5 rows x 10 columns]
127.0.0.1 - - [17/Feb/2023 23:30:01] "POST / HTTP/1.1" 200 -
2023-02-17 23:30:02,771:DEBUG:percentile_regression_step2:main.py:154:get_signal:1265985: df_id.iloc[-5:,:] :
                 daytime     hms    close  ...  pct_10  pct_20  factor
144  2023/02/17 21:00:00  210000  23804.0  ...     NaN     NaN       0
145  2023/02/17 21:30:00  213000  23781.4  ...     NaN     NaN       0
146  2023/02/17 22:00:00  220000  23878.4  ...     NaN     NaN       0
147  2023/02/17 22:30:00  223000  23857.5  ...     NaN     NaN       0
148  2023/02/17 23:00:00  230000  24029.8  ...     NaN     NaN       0

[5 rows x 10 columns]
127.0.0.1 - - [18/Feb/2023 00:00:02] "POST / HTTP/1.1" 200 -
2023-02-18 00:00:03,628:DEBUG:percentile_regression_step2:main.py:154:get_signal:1265985: df_id.iloc[-5:,:] :
                 daytime     hms    close  ...  pct_10  pct_20  factor
144  2023/02/17 21:30:00  213000  23781.4  ...     NaN     NaN       0
145  2023/02/17 22:00:00  220000  23878.4  ...     NaN     NaN       0
146  2023/02/17 22:30:00  223000  23857.5  ...     NaN     NaN       0
147  2023/02/17 23:00:00  230000  24029.8  ...     NaN     NaN       0
148  2023/02/17 23:30:00  233000  24131.4  ...     NaN     NaN       0

[5 rows x 10 columns]


## /root/FIL/strategy/pyemd/log.txt ----- -----

2023-02-18 00:00:02,607:INFO:pyemd2:main.py:127:handleKline:185189: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}
2023-02-18 00:00:02,779:INFO:pyemd2:main.py:190:insertFactor:185189: curDateTime:2180000, name:pyemd2, symbol:BTCUSDT, tradeDate:20230217, closeTime:235959, close:24131.4, total:975512.8470093, pct_pre:-0.04014582314497839, thd:-1.1212197859550743, side:sell 
127.0.0.1 - - [18/Feb/2023 00:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=12153 

self.closeSec=1676650199, self.tradeDate='20230218', self.openTime='000000', self.closeTime='000959', self.symbol='BTCUSDT', self.open='24131.3', self.close='24238.3'
2023-02-18 00:10:01,655:INFO:pyemd2:main.py:125:handleKline:185189: self.closeSec=1676650199, self.tradeDate='20230218', self.openTime='000000', self.closeTime='000959',self.symbol='BTCUSDT',self.open='24131.3', self.close='24238.3'
2023-02-18 00:10:01,739:INFO:pyemd2:main.py:126:handleKline:185189: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17420  20230217   232000    232959  1676647799  24116.2  24029.8
17421  20230217   233000    233959  1676648399  24024.5  24142.9
17422  20230217   234000    234959  1676648999  24152.1  24147.9
17423  20230217   235000    235959  1676649599  24144.6  24131.4
17424  20230218   000000    000959  1676650199  24131.3  24238.3
2023-02-18 00:10:01,739:INFO:pyemd2:main.py:127:handleKline:185189: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}
127.0.0.1 - - [18/Feb/2023 00:20:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=12154 

self.closeSec=1676650799, self.tradeDate='20230218', self.openTime='001000', self.closeTime='001959', self.symbol='BTCUSDT', self.open='24238.3', self.close='24143.6'
2023-02-18 00:20:01,848:INFO:pyemd2:main.py:125:handleKline:185189: self.closeSec=1676650799, self.tradeDate='20230218', self.openTime='001000', self.closeTime='001959',self.symbol='BTCUSDT',self.open='24238.3', self.close='24143.6'
2023-02-18 00:20:01,876:INFO:pyemd2:main.py:126:handleKline:185189: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17421  20230217   233000    233959  1676648399  24024.5  24142.9
17422  20230217   234000    234959  1676648999  24152.1  24147.9
17423  20230217   235000    235959  1676649599  24144.6  24131.4
17424  20230218   000000    000959  1676650199  24131.3  24238.3
17425  20230218   001000    001959  1676650799  24238.3  24143.6
2023-02-18 00:20:01,876:INFO:pyemd2:main.py:127:handleKline:185189: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}


## /root/FIL/strategy/similarity/log.txt ----- -----

2023-02-18 00:00:03,420:INFO:testStrategy:main.py:308:handleOrderFilled:185174: handleOrderFilled: data=OrderType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'clientorderid': '41756F1676649603042I0L2', 'symbol': 'BTCUSDT', 'gatewayorderid': 1676649603143537, 'quantity': '49.536', 'price': '24126.2', 'stopprice': '0', 'ordertype': '', 'side': 'SELL', 'status': 'FILLED', 'positionside': 'SHORT', 'createtime': 1676649602726, 'updatetime': 1676649603143, 'tradetype': 'usdt', 'selfid': 41756, 'filltrades': [TradeType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'tradeid': 1676649603143, 'clientorderid': '41756F1676649603042I0L2', 'price': '24126.2', 'quantity': '49.536', 'commission': '1195.1154432', 'commissionasset': 'USDT', 'tradetime': 1676649603143, 'tradetype': 'usdt', 'gatetype': 'simulator', 'handletime': 1676649603143}], 'gatetype': 'simulator', 'handletime': 0}
127.0.0.1 - - [18/Feb/2023 00:00:03] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=12153 

self.closeSec=1676650199, self.tradeDate='20230218', self.openTime='000000', self.closeTime='000959', self.symbol='BTCUSDT', self.open='24131.3', self.close='24238.3'
2023-02-18 00:10:01,640:INFO:testStrategy:main.py:101:handleKline:185174: self.closeSec=1676650199, self.tradeDate='20230218', self.openTime='000000', self.closeTime='000959',self.symbol='BTCUSDT',self.open='24131.3', self.close='24238.3'
127.0.0.1 - - [18/Feb/2023 00:10:01] "POST / HTTP/1.1" 200 -
2023-02-18 00:10:01,664:INFO:testStrategy:main.py:102:handleKline:185174: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12236  20230217   232000    232959  1676647799  24116.2  24029.8
12237  20230217   233000    233959  1676648399  24024.5  24142.9
12238  20230217   234000    234959  1676648999  24152.1  24147.9
12239  20230217   235000    235959  1676649599  24144.6  24131.4
12240  20230218   000000    000959  1676650199  24131.3  24238.3
2023-02-18 00:10:01,664:INFO:testStrategy:main.py:103:handleKline:185174: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False, 'isCorr': False}

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=12154 

self.closeSec=1676650799, self.tradeDate='20230218', self.openTime='001000', self.closeTime='001959', self.symbol='BTCUSDT', self.open='24238.3', self.close='24143.6'
127.0.0.1 - - [18/Feb/2023 00:20:01] "POST / HTTP/1.1" 200 -
2023-02-18 00:20:01,846:INFO:testStrategy:main.py:101:handleKline:185174: self.closeSec=1676650799, self.tradeDate='20230218', self.openTime='001000', self.closeTime='001959',self.symbol='BTCUSDT',self.open='24238.3', self.close='24143.6'
2023-02-18 00:20:01,874:INFO:testStrategy:main.py:102:handleKline:185174: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12237  20230217   233000    233959  1676648399  24024.5  24142.9
12238  20230217   234000    234959  1676648999  24152.1  24147.9
12239  20230217   235000    235959  1676649599  24144.6  24131.4
12240  20230218   000000    000959  1676650199  24131.3  24238.3
12241  20230218   001000    001959  1676650799  24238.3  24143.6
2023-02-18 00:20:01,875:INFO:testStrategy:main.py:103:handleKline:185174: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False, 'isCorr': False}


## /root/FIL/strategy/sr_min/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=0, self.total=1000000.0, self.flagDict['side']='', self.tradeCount=0, self.count=19738
self.closeSec=1676650799, self.tradeDate='20230218', self.openTime='001500', self.closeTime='001959', self.symbol='BTCUSDT', self.open=24265.8, self.close=24143.6, self.high=24274.8, self.low=24138.7, self.vol=5290.019, self.amt=127983381.1306 
127.0.0.1 - - [18/Feb/2023 00:20:01] "POST / HTTP/1.1" 200 -
2023-02-18 00:20:01,612:INFO:sr_min:main.py:172:handleKline:449472: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5759  20230217   235500    235959  ...         0.0        0.0       0
5760  20230218   000000    000459  ...         0.0        0.0       0
5761  20230218   000500    000959  ...         0.0        0.0       0
5762  20230218   001000    001459  ...         0.0        0.0       0
5763  20230218   001500    001959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-02-18 00:20:01,615:INFO:sr_min:main.py:175:handleKline:449472: self.closeSec=1676650799, self.tradeDate='20230218', self.openTime='001500', self.closeTime='001959',self.symbol='BTCUSDT',self.open=24265.8, self.close=24143.6, self.high=24274.8, self.low=24138.7, self.vol=5290.019, self.amt=127983381.1306, ukdf['pct'].iloc[-1]=-0.005036 , ukdf['amount'].iloc[-1]=127983381.1306, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5763, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': []}
type(curSign)=<class 'int'>, curSign=0, self.sign=0
--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=0, self.total=1000000.0, self.flagDict['side']='', self.tradeCount=0, self.count=19739
self.closeSec=1676651099, self.tradeDate='20230218', self.openTime='002000', self.closeTime='002459', self.symbol='BTCUSDT', self.open=24143.6, self.close=24034.2, self.high=24143.7, self.low=23992.0, self.vol=10600.482, self.amt=255048559.2022 
127.0.0.1 - - [18/Feb/2023 00:25:01] "POST / HTTP/1.1" 200 -
2023-02-18 00:25:01,678:INFO:sr_min:main.py:172:handleKline:449472: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5760  20230218   000000    000459  ...         0.0        0.0       0
5761  20230218   000500    000959  ...         0.0        0.0       0
5762  20230218   001000    001459  ...         0.0        0.0       0
5763  20230218   001500    001959  ...         0.0        0.0       0
5764  20230218   002000    002459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-02-18 00:25:01,678:INFO:sr_min:main.py:175:handleKline:449472: self.closeSec=1676651099, self.tradeDate='20230218', self.openTime='002000', self.closeTime='002459',self.symbol='BTCUSDT',self.open=24143.6, self.close=24034.2, self.high=24143.7, self.low=23992.0, self.vol=10600.482, self.amt=255048559.2022, ukdf['pct'].iloc[-1]=-0.004531 , ukdf['amount'].iloc[-1]=255048559.2022, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5764, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': []}
type(curSign)=<class 'int'>, curSign=0, self.sign=0


## /root/FIL/strategy/s_rsrs/log.txt ----- -----

723  20230217   120000    155959  1676620799  ...    723  1.188773  1.686635     1.0
724  20230217   160000    195959  1676635199  ...    724  1.163211  1.569360     1.0

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '36.518', 'enterprice': '23318.2', 'countrevence': '0', 'unrealprofit': '17332.50140313854', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '23792.82898853', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=1, self.sign=1
127.0.0.1 - - [18/Feb/2023 00:00:02] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='s_rsrs', self.symbol='BTCUSDT', interval='4h', intervalSec=14400, wid=25, thd=0.6, self.sign=1, self.total=850682.4935724001, self.flagDict['side']='buy', self.tradeCount=20, self.count=506
self.closeSec=1676649599, self.tradeDate='20230217', self.openTime='200000', self.closeTime='235959', self.symbol='BTCUSDT', self.open=23792.6, self.close=24131.4, self.high=24293.6, self.low=23701.1, self.vol=225818.466, self.amt=5419494493.74715 
2023-02-18 00:00:02,408:INFO:s_rsrs:main.py:141:handleKline:185271: self.closeSec=1676649599, self.tradeDate='20230217', self.openTime='200000', self.closeTime='235959',self.symbol='BTCUSDT',self.open=23792.6, self.close=24131.4, self.high=24293.6, self.low=23701.1, self.vol=225818.466, self.amt=5419494493.74715 
2023-02-18 00:00:02,475:INFO:s_rsrs:main.py:142:handleKline:185271: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime  ...         vol           amt       pct
721  20230217   040000    075959  ...  237702.696  5.751313e+09 -0.054359
722  20230217   080000    115959  ...  125666.630  2.975857e+09  0.013283
723  20230217   120000    155959  ...   59676.035  1.416530e+09 -0.008520
724  20230217   160000    195959  ...   80667.332  1.914111e+09  0.006625
725  20230217   200000    235959  ...  225818.466  5.419494e+09  0.014240

[5 rows x 11 columns]
2023-02-18 00:00:04,879:INFO:s_rsrs:main.py:151:handleKline:185271: df_s.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec  ...  index      beta    zscore  signal
721  20230217   040000    075959  1676591999  ...    721  1.208527  1.844319     1.0
722  20230217   080000    115959  1676606399  ...    722  1.216225  1.815670     1.0
723  20230217   120000    155959  1676620799  ...    723  1.188773  1.686635     1.0
724  20230217   160000    195959  1676635199  ...    724  1.163211  1.569360     1.0
725  20230217   200000    235959  1676649599  ...    725  1.179899  1.580532     1.0

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '36.518', 'enterprice': '23318.2', 'countrevence': '0', 'unrealprofit': '29641.03815142036', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '24129.88295502', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=1, self.sign=1


