# 20230711 00:26:01

## /root/FIL/strategy/amihud/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=373746.4768026, self.flagDict['side']='sell', self.tradeCount=2, self.count=16576
self.closeSec=1689005999, self.tradeDate='20230711', self.openTime='001500', self.closeTime='001959', self.symbol='BTCUSDT', self.open=30232.2, self.close=30260.4, self.high=30262.5, self.low=30223.5, self.vol=747.299, self.amt=22603991.3994 
127.0.0.1 - - [11/Jul/2023 00:20:01] "POST / HTTP/1.1" 200 -
2023-07-11 00:20:07,245:INFO:amihud:main.py:172:handleKline:2219019: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5759  20230710   235500    235959  ...         0.0        0.0       0
5760  20230711   000000    000459  ...         0.0        0.0       0
5761  20230711   000500    000959  ...         0.0        0.0       0
5762  20230711   001000    001459  ...         0.0        0.0       0
5763  20230711   001500    001959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-07-11 00:20:07,276:INFO:amihud:main.py:175:handleKline:2219019: self.closeSec=1689005999, self.tradeDate='20230711', self.openTime='001500', self.closeTime='001959',self.symbol='BTCUSDT',self.open=30232.2, self.close=30260.4, self.high=30262.5, self.low=30223.5, self.vol=747.299, self.amt=22603991.3994, ukdf['pct'].iloc[-1]=0.000929 , ukdf['amount'].iloc[-1]=22603991.3994, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5763, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '13.926', 'enterprice': '26864.9', 'countrevence': '0', 'unrealprofit': '-47313.31907968776', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '30262.38090476', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1
127.0.0.1 - - [11/Jul/2023 00:25:00] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=373746.4768026, self.flagDict['side']='sell', self.tradeCount=2, self.count=16577
self.closeSec=1689006299, self.tradeDate='20230711', self.openTime='002000', self.closeTime='002459', self.symbol='BTCUSDT', self.open=30260.3, self.close=30259.0, self.high=30294.1, self.low=30254.7, self.vol=927.161, self.amt=28071520.5192 
2023-07-11 00:25:00,765:INFO:amihud:main.py:172:handleKline:2219019: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5760  20230711   000000    000459  ...         0.0        0.0       0
5761  20230711   000500    000959  ...         0.0        0.0       0
5762  20230711   001000    001459  ...         0.0        0.0       0
5763  20230711   001500    001959  ...         0.0        0.0       0
5764  20230711   002000    002459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-07-11 00:25:00,765:INFO:amihud:main.py:175:handleKline:2219019: self.closeSec=1689006299, self.tradeDate='20230711', self.openTime='002000', self.closeTime='002459',self.symbol='BTCUSDT',self.open=30260.3, self.close=30259.0, self.high=30294.1, self.low=30254.7, self.vol=927.161, self.amt=28071520.5192, ukdf['pct'].iloc[-1]=-4.6e-05 , ukdf['amount'].iloc[-1]=28071520.5192, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5764, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '13.926', 'enterprice': '26864.9', 'countrevence': '0', 'unrealprofit': '-47276.65378359396', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '30259.74803846', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1


## /root/FIL/strategy/factorcheck/log.txt ----- -----


self.closeSec=1689005999, self.tradeDate='20230711', self.openTime='001500', self.closeTime='001959', self.symbol='BTCUSDT', self.open=30232.2, self.close=30260.4, self.high=30262.5, self.low=30223.5 
127.0.0.1 - - [11/Jul/2023 00:20:01] "POST / HTTP/1.1" 200 -
2023-07-11 00:20:04,800:INFO:factorcheck2:main.py:126:handleKline:2218005: self.closeSec=1689005999, self.tradeDate='20230711', self.openTime='001500', self.closeTime='001959',self.symbol='BTCUSDT',self.open=30232.2, self.close=30260.4, self.high=30262.5, self.low=30223.5   
2023-07-11 00:20:06,325:INFO:factorcheck2:main.py:127:handleKline:2218005: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1439  20230710   235500    235959  1689004799  ...  30266.4  0.001028   1727    5
1440  20230711   000000    000459  1689005099  ...  30256.7 -0.000406   1440    0
1441  20230711   000500    000959  1689005399  ...  30250.0 -0.001047   1441    1
1442  20230711   001000    001459  1689005699  ...  30225.4 -0.000704   1442    2
1443  20230711   001500    001959  1689005999  ...  30223.5  0.000929   1443    3

[5 rows x 11 columns]
2023-07-11 00:20:06,335:INFO:factorcheck2:main.py:128:handleKline:2218005: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}
127.0.0.1 - - [11/Jul/2023 00:25:00] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=95, self.factor=0.4986142616125643, self.count=16579 

self.closeSec=1689006299, self.tradeDate='20230711', self.openTime='002000', self.closeTime='002459', self.symbol='BTCUSDT', self.open=30260.3, self.close=30259.0, self.high=30294.1, self.low=30254.7 
2023-07-11 00:25:00,701:INFO:factorcheck2:main.py:126:handleKline:2218005: self.closeSec=1689006299, self.tradeDate='20230711', self.openTime='002000', self.closeTime='002459',self.symbol='BTCUSDT',self.open=30260.3, self.close=30259.0, self.high=30294.1, self.low=30254.7   
2023-07-11 00:25:00,727:INFO:factorcheck2:main.py:127:handleKline:2218005: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1440  20230711   000000    000459  1689005099  ...  30256.7 -0.000406   1440    0
1441  20230711   000500    000959  1689005399  ...  30250.0 -0.001047   1441    1
1442  20230711   001000    001459  1689005699  ...  30225.4 -0.000704   1442    2
1443  20230711   001500    001959  1689005999  ...  30223.5  0.000929   1443    3
1444  20230711   002000    002459  1689006299  ...  30254.7 -0.000046   1444    4

[5 rows x 11 columns]
2023-07-11 00:25:00,727:INFO:factorcheck2:main.py:128:handleKline:2218005: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}


## /root/FIL/strategy/logic/log.txt ----- -----

539     0  0.512292  0.487708       1  ...  0.973393   1.0    0.0  0.995421
540     0  0.515542  0.484458       1  ...  0.975630   1.0    0.0  0.997709
541     0  0.527987  0.472013       1  ...  0.976674   1.0    0.0  0.998777
542     0  0.522231  0.477769       0  ...  0.975456   1.0    0.0  0.997531
543     0  0.509627  0.490373       1  ...  0.976700   1.0    0.0  0.998803

[5 rows x 10 columns]
2023-07-11 00:00:19,597:INFO:logic:main.py:478:getModel:2218526: df_panel.iloc[-5:,:] :
    pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
45     0  0.512715  0.487285       1  ...  0.975073   1.0    0.0  1.000096
46     0  0.515423  0.484577       1  ...  0.977314   1.0    0.0  1.001416
47     0  0.528025  0.471975       1  ...  0.978360   1.0    0.0  1.002488
48     0  0.521786  0.478214       0  ...  0.966920  -1.0    0.0  0.996325
49     0  0.509627  0.490373       1  ...  0.976700   1.0    0.0  0.998803

[5 rows x 10 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '24.765', 'enterprice': '30270.2', 'countrevence': '0', 'unrealprofit': '-932.4086453136', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '30307.85025824', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
handlebackTrade > queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '24.765', 'enterprice': '30270.2', 'countrevence': '0', 'unrealprofit': '-931.9187881653', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '30307.83047802', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
2023-07-11 00:00:26,398:INFO:logic:main.py:500:queryContractAssets:2218526: queryContractAssets: assets=ContractAssetReturn{'result': [ContractAsset{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'asset': 'USDT', 'free': '749985.6418534', 'total': '749985.6418534', 'margin': '0', 'unreal': '0', 'type': 'AssetType_ucontract'}]}
2023-07-11 00:00:26,849:DEBUG:logic:main.py:571:openBuy:2218526: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': True, 'isCloseBuy': False, 'isCloseSell': False, 'isOpen': True, 'isClose': False, 'isTrig': False}
2023-07-11 00:00:26,849:INFO:logic:main.py:572:openBuy:2218526: ret = self.client.insertMarketUOrder("simulator", "BTCUSDT", 24.679, "buy"), ret=InsertOrderReturn{'result': 'success', 'clientorderid': '42587F1689004826848I0L64'}
2023-07-11 00:00:26,869:INFO:logic:main.py:494:insertFactor:2218526: curDateTime:7110000, name:logic, symbol:BTCUSDT, tradeDate:20230710, closeTime:235959, close:30297.6, sign:1, total:749985.6418534, side:buy  
127.0.0.1 - - [11/Jul/2023 00:00:26] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [11/Jul/2023 00:00:26] "POST / HTTP/1.1" 200 -
2023-07-11 00:00:26,871:INFO:logic:main.py:661:handleOrderNew:2218526: handleOrderNew: data=OrderType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'clientorderid': '42586F1689004821334I0L64', 'symbol': 'BTCUSDT', 'gatewayorderid': 1689004821723972, 'quantity': '24.765', 'price': '30306', 'stopprice': '0', 'ordertype': '', 'side': 'BUY', 'status': 'FILLED', 'positionside': 'LONG', 'createtime': 1689004820469, 'updatetime': 1689004821723, 'tradetype': 'usdt', 'selfid': 42586, 'filltrades': [TradeType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'tradeid': 1689004821723, 'clientorderid': '42586F1689004821334I0L64', 'price': '30306', 'quantity': '24.765', 'commission': '750.52809', 'commissionasset': 'USDT', 'tradetime': 1689004821723, 'tradetype': 'usdt', 'gatetype': 'simulator', 'handletime': 1689004821723}], 'gatetype': 'simulator', 'handletime': 0}
2023-07-11 00:00:26,871:INFO:logic:main.py:664:handleOrderFilled:2218526: handleOrderFilled: data=OrderType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'clientorderid': '42586F1689004821334I0L64', 'symbol': 'BTCUSDT', 'gatewayorderid': 1689004821723972, 'quantity': '24.765', 'price': '30306', 'stopprice': '0', 'ordertype': '', 'side': 'BUY', 'status': 'FILLED', 'positionside': 'LONG', 'createtime': 1689004820469, 'updatetime': 1689004821723, 'tradetype': 'usdt', 'selfid': 42586, 'filltrades': [TradeType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'tradeid': 1689004821723, 'clientorderid': '42586F1689004821334I0L64', 'price': '30306', 'quantity': '24.765', 'commission': '750.52809', 'commissionasset': 'USDT', 'tradetime': 1689004821723, 'tradetype': 'usdt', 'gatetype': 'simulator', 'handletime': 1689004821723}], 'gatetype': 'simulator', 'handletime': 0}
2023-07-11 00:00:27,294:INFO:logic:main.py:661:handleOrderNew:2218526: handleOrderNew: data=OrderType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'clientorderid': '42587F1689004826848I0L64', 'symbol': 'BTCUSDT', 'gatewayorderid': 1689004827256343, 'quantity': '24.679', 'price': '30312.7', 'stopprice': '0', 'ordertype': '', 'side': 'BUY', 'status': 'FILLED', 'positionside': 'LONG', 'createtime': 1689004826410, 'updatetime': 1689004827256, 'tradetype': 'usdt', 'selfid': 42587, 'filltrades': [TradeType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'tradeid': 1689004827256, 'clientorderid': '42587F1689004826848I0L64', 'price': '30312.7', 'quantity': '24.679', 'commission': '748.0871233', 'commissionasset': 'USDT', 'tradetime': 1689004827256, 'tradetype': 'usdt', 'gatetype': 'simulator', 'handletime': 1689004827256}], 'gatetype': 'simulator', 'handletime': 0}
127.0.0.1 - - [11/Jul/2023 00:00:27] "POST / HTTP/1.1" 200 -
2023-07-11 00:00:27,508:INFO:logic:main.py:664:handleOrderFilled:2218526: handleOrderFilled: data=OrderType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'clientorderid': '42587F1689004826848I0L64', 'symbol': 'BTCUSDT', 'gatewayorderid': 1689004827256343, 'quantity': '24.679', 'price': '30312.7', 'stopprice': '0', 'ordertype': '', 'side': 'BUY', 'status': 'FILLED', 'positionside': 'LONG', 'createtime': 1689004826410, 'updatetime': 1689004827256, 'tradetype': 'usdt', 'selfid': 42587, 'filltrades': [TradeType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'tradeid': 1689004827256, 'clientorderid': '42587F1689004826848I0L64', 'price': '30312.7', 'quantity': '24.679', 'commission': '748.0871233', 'commissionasset': 'USDT', 'tradetime': 1689004827256, 'tradetype': 'usdt', 'gatetype': 'simulator', 'handletime': 1689004827256}], 'gatetype': 'simulator', 'handletime': 0}
127.0.0.1 - - [11/Jul/2023 00:00:27] "POST / HTTP/1.1" 200 -


## /root/FIL/strategy/modifiedmom/log.txt ----- -----

127.0.0.1 - - [11/Jul/2023 00:00:04] "POST / HTTP/1.1" 200 -
2023-07-11 00:00:04,339:INFO:modifiedmom:main.py:319:handleOrderFilled:2218259: handleOrderFilled: data=OrderType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'clientorderid': '42582F1689004803682I0L59', 'symbol': 'BTCUSDT', 'gatewayorderid': 1689004804095803, 'quantity': '25.245', 'price': '30297.6', 'stopprice': '0', 'ordertype': '', 'side': 'BUY', 'status': 'FILLED', 'positionside': 'LONG', 'createtime': 1689004802758, 'updatetime': 1689004804095, 'tradetype': 'usdt', 'selfid': 42582, 'filltrades': [TradeType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'tradeid': 1689004804095, 'clientorderid': '42582F1689004803682I0L59', 'price': '30297.6', 'quantity': '25.245', 'commission': '764.862912', 'commissionasset': 'USDT', 'tradetime': 1689004804095, 'tradetype': 'usdt', 'gatetype': 'simulator', 'handletime': 1689004804095}], 'gatetype': 'simulator', 'handletime': 0}

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=8288 

self.closeSec=1689005399, self.tradeDate='20230711', self.openTime='000000', self.closeTime='000959', self.symbol='BTCUSDT', self.open='30297.5', self.close='30253.6'
127.0.0.1 - - [11/Jul/2023 00:10:01] "POST / HTTP/1.1" 200 -
2023-07-11 00:10:01,160:INFO:modifiedmom:main.py:144:handleKline:2218259: self.closeSec=1689005399, self.tradeDate='20230711', self.openTime='000000', self.closeTime='000959',self.symbol='BTCUSDT',self.open='30297.5', self.close='30253.6'
2023-07-11 00:10:01,190:INFO:modifiedmom:main.py:145:handleKline:2218259: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
572  20230710   232000    232959  1689002999  30233.9    30259  0.000827
573  20230710   233000    233959  1689003599  30259.1    30300  0.001355
574  20230710   234000    234959  1689004199    30300  30274.4 -0.000845
575  20230710   235000    235959  1689004799  30274.5  30297.6  0.000766
576  20230711   000000    000959  1689005399  30297.5  30253.6 -0.001452
2023-07-11 00:10:01,191:INFO:modifiedmom:main.py:146:handleKline:2218259: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=8289 

self.closeSec=1689005999, self.tradeDate='20230711', self.openTime='001000', self.closeTime='001959', self.symbol='BTCUSDT', self.open='30253.7', self.close='30260.4'
127.0.0.1 - - [11/Jul/2023 00:20:04] "POST / HTTP/1.1" 200 -
2023-07-11 00:20:07,154:INFO:modifiedmom:main.py:144:handleKline:2218259: self.closeSec=1689005999, self.tradeDate='20230711', self.openTime='001000', self.closeTime='001959',self.symbol='BTCUSDT',self.open='30253.7', self.close='30260.4'
2023-07-11 00:20:07,944:INFO:modifiedmom:main.py:145:handleKline:2218259: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
573  20230710   233000    233959  1689003599  30259.1    30300  0.001355
574  20230710   234000    234959  1689004199    30300  30274.4 -0.000845
575  20230710   235000    235959  1689004799  30274.5  30297.6  0.000766
576  20230711   000000    000959  1689005399  30297.5  30253.6 -0.001452
577  20230711   001000    001959  1689005999  30253.7  30260.4  0.000225
2023-07-11 00:20:07,954:INFO:modifiedmom:main.py:146:handleKline:2218259: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False}


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

2023-07-11 00:00:02,193:INFO:pyemd2:main.py:127:handleKline:2217508: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}
2023-07-11 00:00:02,290:INFO:pyemd2:main.py:190:insertFactor:2217508: curDateTime:7110000, name:pyemd2, symbol:BTCUSDT, tradeDate:20230710, closeTime:235959, close:30297.6, total:994781.5383624, pct_pre:-0.005991718494811615, thd:-0.12332732113302952, side:sell 

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=8291 

self.closeSec=1689005399, self.tradeDate='20230711', self.openTime='000000', self.closeTime='000959', self.symbol='BTCUSDT', self.open='30297.5', self.close='30253.6'
127.0.0.1 - - [11/Jul/2023 00:10:01] "POST / HTTP/1.1" 200 -
2023-07-11 00:10:01,181:INFO:pyemd2:main.py:125:handleKline:2217508: self.closeSec=1689005399, self.tradeDate='20230711', self.openTime='000000', self.closeTime='000959',self.symbol='BTCUSDT',self.open='30297.5', self.close='30253.6'
2023-07-11 00:10:01,194:INFO:pyemd2:main.py:126:handleKline:2217508: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17420  20230710   232000    232959  1689002999  30233.9    30259
17421  20230710   233000    233959  1689003599  30259.1    30300
17422  20230710   234000    234959  1689004199    30300  30274.4
17423  20230710   235000    235959  1689004799  30274.5  30297.6
17424  20230711   000000    000959  1689005399  30297.5  30253.6
2023-07-11 00:10:01,194:INFO:pyemd2:main.py:127:handleKline:2217508: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=8292 

self.closeSec=1689005999, self.tradeDate='20230711', self.openTime='001000', self.closeTime='001959', self.symbol='BTCUSDT', self.open='30253.7', self.close='30260.4'
127.0.0.1 - - [11/Jul/2023 00:20:04] "POST / HTTP/1.1" 200 -
2023-07-11 00:20:08,868:INFO:pyemd2:main.py:125:handleKline:2217508: self.closeSec=1689005999, self.tradeDate='20230711', self.openTime='001000', self.closeTime='001959',self.symbol='BTCUSDT',self.open='30253.7', self.close='30260.4'
2023-07-11 00:20:09,077:INFO:pyemd2:main.py:126:handleKline:2217508: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17421  20230710   233000    233959  1689003599  30259.1    30300
17422  20230710   234000    234959  1689004199    30300  30274.4
17423  20230710   235000    235959  1689004799  30274.5  30297.6
17424  20230711   000000    000959  1689005399  30297.5  30253.6
17425  20230711   001000    001959  1689005999  30253.7  30260.4
2023-07-11 00:20:09,078:INFO:pyemd2:main.py:127:handleKline:2217508: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}


## /root/FIL/strategy/similarity/log.txt ----- -----

127.0.0.1 - - [11/Jul/2023 00:00:04] "POST / HTTP/1.1" 200 -
2023-07-11 00:00:04,520:INFO:testStrategy:main.py:308:handleOrderFilled:2217133: handleOrderFilled: data=OrderType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'clientorderid': '42583F1689004803835I0L2', 'symbol': 'BTCUSDT', 'gatewayorderid': 1689004804272436, 'quantity': '37.578', 'price': '30297.6', 'stopprice': '0', 'ordertype': '', 'side': 'BUY', 'status': 'FILLED', 'positionside': 'LONG', 'createtime': 1689004802842, 'updatetime': 1689004804272, 'tradetype': 'usdt', 'selfid': 42583, 'filltrades': [TradeType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'tradeid': 1689004804272, 'clientorderid': '42583F1689004803835I0L2', 'price': '30297.6', 'quantity': '37.578', 'commission': '1138.5232128', 'commissionasset': 'USDT', 'tradetime': 1689004804272, 'tradetype': 'usdt', 'gatetype': 'simulator', 'handletime': 1689004804272}], 'gatetype': 'simulator', 'handletime': 0}
127.0.0.1 - - [11/Jul/2023 00:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=8291 

self.closeSec=1689005399, self.tradeDate='20230711', self.openTime='000000', self.closeTime='000959', self.symbol='BTCUSDT', self.open='30297.5', self.close='30253.6'
2023-07-11 00:10:01,163:INFO:testStrategy:main.py:101:handleKline:2217133: self.closeSec=1689005399, self.tradeDate='20230711', self.openTime='000000', self.closeTime='000959',self.symbol='BTCUSDT',self.open='30297.5', self.close='30253.6'
2023-07-11 00:10:01,178:INFO:testStrategy:main.py:102:handleKline:2217133: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12236  20230710   232000    232959  1689002999  30233.9    30259
12237  20230710   233000    233959  1689003599  30259.1    30300
12238  20230710   234000    234959  1689004199    30300  30274.4
12239  20230710   235000    235959  1689004799  30274.5  30297.6
12240  20230711   000000    000959  1689005399  30297.5  30253.6
2023-07-11 00:10:01,179:INFO:testStrategy:main.py:103:handleKline:2217133: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False, 'isCorr': False}

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=8292 

self.closeSec=1689005999, self.tradeDate='20230711', self.openTime='001000', self.closeTime='001959', self.symbol='BTCUSDT', self.open='30253.7', self.close='30260.4'
127.0.0.1 - - [11/Jul/2023 00:20:04] "POST / HTTP/1.1" 200 -
2023-07-11 00:20:08,659:INFO:testStrategy:main.py:101:handleKline:2217133: self.closeSec=1689005999, self.tradeDate='20230711', self.openTime='001000', self.closeTime='001959',self.symbol='BTCUSDT',self.open='30253.7', self.close='30260.4'
2023-07-11 00:20:08,946:INFO:testStrategy:main.py:102:handleKline:2217133: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12237  20230710   233000    233959  1689003599  30259.1    30300
12238  20230710   234000    234959  1689004199    30300  30274.4
12239  20230710   235000    235959  1689004799  30274.5  30297.6
12240  20230711   000000    000959  1689005399  30297.5  30253.6
12241  20230711   001000    001959  1689005999  30253.7  30260.4
2023-07-11 00:20:08,954:INFO:testStrategy:main.py:103:handleKline:2217133: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False, 'isCorr': False}


## /root/FIL/strategy/sr_min/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=1, self.total=996015.990996, self.flagDict['side']='buy', self.tradeCount=1, self.count=16576
self.closeSec=1689005999, self.tradeDate='20230711', self.openTime='001500', self.closeTime='001959', self.symbol='BTCUSDT', self.open=30232.2, self.close=30260.4, self.high=30262.5, self.low=30223.5, self.vol=747.299, self.amt=22603991.3994 
127.0.0.1 - - [11/Jul/2023 00:20:01] "POST / HTTP/1.1" 200 -
2023-07-11 00:20:07,254:INFO:sr_min:main.py:172:handleKline:2219263: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5759  20230710   235500    235959  ...         0.0        0.0       0
5760  20230711   000000    000459  ...         0.0        0.0       0
5761  20230711   000500    000959  ...         0.0        0.0       0
5762  20230711   001000    001459  ...         0.0        0.0       0
5763  20230711   001500    001959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-07-11 00:20:07,285:INFO:sr_min:main.py:175:handleKline:2219263: self.closeSec=1689005999, self.tradeDate='20230711', self.openTime='001500', self.closeTime='001959',self.symbol='BTCUSDT',self.open=30232.2, self.close=30260.4, self.high=30262.5, self.low=30223.5, self.vol=747.299, self.amt=22603991.3994, ukdf['pct'].iloc[-1]=0.000929 , ukdf['amount'].iloc[-1]=22603991.3994, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5763, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '37.141', 'enterprice': '26844', 'countrevence': '0', 'unrealprofit': '126962.08518369116', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '30262.38090476', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=1
127.0.0.1 - - [11/Jul/2023 00:25:00] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=1, self.total=996015.990996, self.flagDict['side']='buy', self.tradeCount=1, self.count=16577
self.closeSec=1689006299, self.tradeDate='20230711', self.openTime='002000', self.closeTime='002459', self.symbol='BTCUSDT', self.open=30260.3, self.close=30259.0, self.high=30294.1, self.low=30254.7, self.vol=927.161, self.amt=28071520.5192 
2023-07-11 00:25:00,768:INFO:sr_min:main.py:172:handleKline:2219263: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5760  20230711   000000    000459  ...         0.0        0.0       0
5761  20230711   000500    000959  ...         0.0        0.0       0
5762  20230711   001000    001459  ...         0.0        0.0       0
5763  20230711   001500    001959  ...         0.0        0.0       0
5764  20230711   002000    002459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-07-11 00:25:00,769:INFO:sr_min:main.py:175:handleKline:2219263: self.closeSec=1689006299, self.tradeDate='20230711', self.openTime='002000', self.closeTime='002459',self.symbol='BTCUSDT',self.open=30260.3, self.close=30259.0, self.high=30294.1, self.low=30254.7, self.vol=927.161, self.amt=28071520.5192, ukdf['pct'].iloc[-1]=-4.6e-05 , ukdf['amount'].iloc[-1]=28071520.5192, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5764, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '37.141', 'enterprice': '26844', 'countrevence': '0', 'unrealprofit': '126864.29789644286', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '30259.74803846', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=1


## /root/FIL/strategy/s_rsrs/log.txt ----- -----

721  20230710   040000    075959  ...  32675.435  9.847616e+08 -0.002643
722  20230710   080000    115959  ...  57315.967  1.724260e+09 -0.000096
723  20230710   120000    155959  ...  22884.999  6.887192e+08 -0.001489
724  20230710   160000    195959  ...  37764.713  1.137725e+09  0.004037
725  20230710   200000    235959  ...  62189.014  1.880878e+09  0.002518

[5 rows x 11 columns]
2023-07-11 00:00:03,141:INFO:s_rsrs:main.py:151:handleKline:2218689: df_s.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec  ...  index      beta    zscore  signal
721  20230710   040000    075959  1688947199  ...    721  0.309598  0.140969     NaN
722  20230710   080000    115959  1688961599  ...    722  0.347591  0.320803     NaN
723  20230710   120000    155959  1688975999  ...    723  0.361744  0.391610     NaN
724  20230710   160000    195959  1688990399  ...    724  0.289137  0.062660     NaN
725  20230710   200000    235959  1689004799  ...    725  0.000017 -1.233220    -1.0

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '53.05', 'enterprice': '30750.9', 'countrevence': '0', 'unrealprofit': '-23794.325092417', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '30302.37360806', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-1, self.sign=1
handlebackTrade > queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '53.05', 'enterprice': '30750.9', 'countrevence': '0', 'unrealprofit': '-23794.325092417', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '30302.37360806', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
2023-07-11 00:00:10,031:INFO:s_rsrs:main.py:182:queryContractAssets:2218689: queryContractAssets: assets=ContractAssetReturn{'result': [ContractAsset{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'asset': 'USDT', 'free': '1611061.6571016', 'total': '1611061.6571016', 'margin': '0', 'unreal': '0', 'type': 'AssetType_ucontract'}]}
2023-07-11 00:00:10,578:INFO:s_rsrs:main.py:269:openSell:2218689: ret = self.client.insertMarketUOrder("simulator", "BTCUSDT", 53.015, "sell"), ret=InsertOrderReturn{'result': 'success', 'clientorderid': '42585F1689004810576I0L65'}
2023-07-11 00:00:10,595:INFO:s_rsrs:main.py:176:insertFactor:2218689: curDateTime:7110000, name:s_rsrs, symbol:BTCUSDT, tradeDate:20230710, closeTime:235959, close:30297.6, sign:-1, total:1611061.6571016, side:sell  
127.0.0.1 - - [11/Jul/2023 00:00:10] "POST / HTTP/1.1" 200 -
2023-07-11 00:00:10,597:INFO:s_rsrs:main.py:343:handleOrderNew:2218689: handleOrderNew: data=OrderType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'clientorderid': '42584F1689004804886I0L65', 'symbol': 'BTCUSDT', 'gatewayorderid': 1689004805316585, 'quantity': '53.05', 'price': '30300.8', 'stopprice': '0', 'ordertype': '', 'side': 'SELL', 'status': 'FILLED', 'positionside': 'SHORT', 'createtime': 1689004803967, 'updatetime': 1689004805316, 'tradetype': 'usdt', 'selfid': 42584, 'filltrades': [TradeType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'tradeid': 1689004805316, 'clientorderid': '42584F1689004804886I0L65', 'price': '30300.8', 'quantity': '53.05', 'commission': '1607.45744', 'commissionasset': 'USDT', 'tradetime': 1689004805316, 'tradetype': 'usdt', 'gatetype': 'simulator', 'handletime': 1689004805316}], 'gatetype': 'simulator', 'handletime': 0}
2023-07-11 00:00:10,598:INFO:s_rsrs:main.py:346:handleOrderFilled:2218689: handleOrderFilled: data=OrderType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'clientorderid': '42584F1689004804886I0L65', 'symbol': 'BTCUSDT', 'gatewayorderid': 1689004805316585, 'quantity': '53.05', 'price': '30300.8', 'stopprice': '0', 'ordertype': '', 'side': 'SELL', 'status': 'FILLED', 'positionside': 'SHORT', 'createtime': 1689004803967, 'updatetime': 1689004805316, 'tradetype': 'usdt', 'selfid': 42584, 'filltrades': [TradeType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'tradeid': 1689004805316, 'clientorderid': '42584F1689004804886I0L65', 'price': '30300.8', 'quantity': '53.05', 'commission': '1607.45744', 'commissionasset': 'USDT', 'tradetime': 1689004805316, 'tradetype': 'usdt', 'gatetype': 'simulator', 'handletime': 1689004805316}], 'gatetype': 'simulator', 'handletime': 0}
127.0.0.1 - - [11/Jul/2023 00:00:10] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [11/Jul/2023 00:00:10] "POST / HTTP/1.1" 200 -
2023-07-11 00:00:10,991:INFO:s_rsrs:main.py:343:handleOrderNew:2218689: handleOrderNew: data=OrderType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'clientorderid': '42585F1689004810576I0L65', 'symbol': 'BTCUSDT', 'gatewayorderid': 1689004810966739, 'quantity': '53.015', 'price': '30303.5', 'stopprice': '0', 'ordertype': '', 'side': 'SELL', 'status': 'FILLED', 'positionside': 'SHORT', 'createtime': 1689004810048, 'updatetime': 1689004810966, 'tradetype': 'usdt', 'selfid': 42585, 'filltrades': [TradeType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'tradeid': 1689004810966, 'clientorderid': '42585F1689004810576I0L65', 'price': '30303.5', 'quantity': '53.015', 'commission': '1606.5400525', 'commissionasset': 'USDT', 'tradetime': 1689004810966, 'tradetype': 'usdt', 'gatetype': 'simulator', 'handletime': 1689004810966}], 'gatetype': 'simulator', 'handletime': 0}
127.0.0.1 - - [11/Jul/2023 00:00:11] "POST / HTTP/1.1" 200 -
2023-07-11 00:00:11,205:INFO:s_rsrs:main.py:346:handleOrderFilled:2218689: handleOrderFilled: data=OrderType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'clientorderid': '42585F1689004810576I0L65', 'symbol': 'BTCUSDT', 'gatewayorderid': 1689004810966739, 'quantity': '53.015', 'price': '30303.5', 'stopprice': '0', 'ordertype': '', 'side': 'SELL', 'status': 'FILLED', 'positionside': 'SHORT', 'createtime': 1689004810048, 'updatetime': 1689004810966, 'tradetype': 'usdt', 'selfid': 42585, 'filltrades': [TradeType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'tradeid': 1689004810966, 'clientorderid': '42585F1689004810576I0L65', 'price': '30303.5', 'quantity': '53.015', 'commission': '1606.5400525', 'commissionasset': 'USDT', 'tradetime': 1689004810966, 'tradetype': 'usdt', 'gatetype': 'simulator', 'handletime': 1689004810966}], 'gatetype': 'simulator', 'handletime': 0}


