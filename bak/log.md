# 20221225 00:16:01

## /root/FIL/strategy/amihud/log.txt ----- -----

127.0.0.1 - - [25/Dec/2022 00:10:01] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=993672.4896432, self.flagDict['side']='sell', self.tradeCount=2, self.count=7898
self.closeSec=1671898199, self.tradeDate='20221225', self.openTime='000500', self.closeTime='000959', self.symbol='BTCUSDT', self.open=16832.0, self.close=16815.3, self.high=16832.1, self.low=16815.2, self.vol=617.906, self.amt=10394861.3025 
2022-12-25 00:10:01,469:INFO:amihud:main.py:172:handleKline:200676: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5757  20221224   234500    234959  ...         0.0        0.0       0
5758  20221224   235000    235459  ...         0.0        0.0       0
5759  20221224   235500    235959  ...         0.0        0.0       0
5760  20221225   000000    000459  ...         0.0        0.0       0
5761  20221225   000500    000959  ...         0.0        0.0       0

[5 rows x 18 columns]
2022-12-25 00:10:01,469:INFO:amihud:main.py:175:handleKline:200676: self.closeSec=1671898199, self.tradeDate='20221225', self.openTime='000500', self.closeTime='000959',self.symbol='BTCUSDT',self.open=16832.0, self.close=16815.3, self.high=16832.1, self.low=16815.2, self.vol=617.906, self.amt=10394861.3025, ukdf['pct'].iloc[-1]=-0.000998 , ukdf['amount'].iloc[-1]=10394861.3025, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5761, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '60.176', 'enterprice': '16529.3', 'countrevence': '0', 'unrealprofit': '-17300.21616858752', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '16816.79362152', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1
--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=993672.4896432, self.flagDict['side']='sell', self.tradeCount=2, self.count=7899
self.closeSec=1671898499, self.tradeDate='20221225', self.openTime='001000', self.closeTime='001459', self.symbol='BTCUSDT', self.open=16815.3, self.close=16820.7, self.high=16823.4, self.low=16815.2, self.vol=443.65, self.amt=7461692.0754 
127.0.0.1 - - [25/Dec/2022 00:15:00] "POST / HTTP/1.1" 200 -
2022-12-25 00:15:00,571:INFO:amihud:main.py:172:handleKline:200676: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5758  20221224   235000    235459  ...         0.0        0.0       0
5759  20221224   235500    235959  ...         0.0        0.0       0
5760  20221225   000000    000459  ...         0.0        0.0       0
5761  20221225   000500    000959  ...         0.0        0.0       0
5762  20221225   001000    001459  ...         0.0        0.0       0

[5 rows x 18 columns]
2022-12-25 00:15:00,571:INFO:amihud:main.py:175:handleKline:200676: self.closeSec=1671898499, self.tradeDate='20221225', self.openTime='001000', self.closeTime='001459',self.symbol='BTCUSDT',self.open=16815.3, self.close=16820.7, self.high=16823.4, self.low=16815.2, self.vol=443.65, self.amt=7461692.0754, ukdf['pct'].iloc[-1]=0.000321 , ukdf['amount'].iloc[-1]=7461692.0754, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5762, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '60.176', 'enterprice': '16529.3', 'countrevence': '0', 'unrealprofit': '-17535.2864', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '16820.7', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1


## /root/FIL/strategy/factorcheck/log.txt ----- -----


self.closeSec=1671898199, self.tradeDate='20221225', self.openTime='000500', self.closeTime='000959', self.symbol='BTCUSDT', self.open=16832.0, self.close=16815.3, self.high=16832.1, self.low=16815.2 
2022-12-25 00:10:01,403:INFO:factorcheck2:main.py:126:handleKline:185239: self.closeSec=1671898199, self.tradeDate='20221225', self.openTime='000500', self.closeTime='000959',self.symbol='BTCUSDT',self.open=16832.0, self.close=16815.3, self.high=16832.1, self.low=16815.2   
127.0.0.1 - - [25/Dec/2022 00:10:01] "POST / HTTP/1.1" 200 -
2022-12-25 00:10:01,453:INFO:factorcheck2:main.py:127:handleKline:185239: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1437  20221224   234500    234959  1671896999  ...  16826.7 -0.000012   1725    3
1438  20221224   235000    235459  1671897299  ...  16826.7  0.000285   1726    4
1439  20221224   235500    235959  1671897599  ...  16830.2 -0.000077   1727    5
1440  20221225   000000    000459  1671897899  ...  16830.2  0.000113   1440    0
1441  20221225   000500    000959  1671898199  ...  16815.2 -0.000998   1441    1

[5 rows x 11 columns]
2022-12-25 00:10:01,457:INFO:factorcheck2:main.py:128:handleKline:185239: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=166, self.factor=0.43734717045305743, self.count=8465 

self.closeSec=1671898499, self.tradeDate='20221225', self.openTime='001000', self.closeTime='001459', self.symbol='BTCUSDT', self.open=16815.3, self.close=16820.7, self.high=16823.4, self.low=16815.2 
2022-12-25 00:15:00,506:INFO:factorcheck2:main.py:126:handleKline:185239: self.closeSec=1671898499, self.tradeDate='20221225', self.openTime='001000', self.closeTime='001459',self.symbol='BTCUSDT',self.open=16815.3, self.close=16820.7, self.high=16823.4, self.low=16815.2   
127.0.0.1 - - [25/Dec/2022 00:15:00] "POST / HTTP/1.1" 200 -
2022-12-25 00:15:00,528:INFO:factorcheck2:main.py:127:handleKline:185239: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1438  20221224   235000    235459  1671897299  ...  16826.7  0.000285   1726    4
1439  20221224   235500    235959  1671897599  ...  16830.2 -0.000077   1727    5
1440  20221225   000000    000459  1671897899  ...  16830.2  0.000113   1440    0
1441  20221225   000500    000959  1671898199  ...  16815.2 -0.000998   1441    1
1442  20221225   001000    001459  1671898499  ...  16815.2  0.000321   1442    2

[5 rows x 11 columns]
2022-12-25 00:15:00,528:INFO:factorcheck2:main.py:128:handleKline:185239: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}


## /root/FIL/strategy/logic/log.txt ----- -----

2022-12-25 00:00:25,091:DEBUG:logic:main.py:454:getModel:174970: df_s.iloc[-5:,:] :
          date closeTime     open  ...    alpha58   alpha67   alpha72
5802  20221224    212959  16816.2  ...  49.166667  0.510901  0.470686
5803  20221224    215959  16822.9  ...  49.166667  0.499946  0.470936
5804  20221224    222959  16809.7  ...  49.583333  0.504627  0.466948
5805  20221224    225959  16815.4  ...  49.583333  0.511583  0.456929
5806  20221224    232959  16824.0  ...  50.000000  0.514854  0.444616

[5 rows x 33 columns]
0.53125
acc is : 0.53125
2022-12-25 00:00:25,214:INFO:logic:main.py:459:getModel:174970: df_pred.iloc[-5:,:] :
     pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
539     1  0.498105  0.501895       0  ...  1.098562   1.0    0.0  0.979763
540     1  0.491940  0.508060       1  ...  1.098934   1.0    0.0  0.980096
541     1  0.496918  0.503082       1  ...  1.099490   1.0    0.0  0.980591
542     1  0.498951  0.501049       1  ...  1.099751   1.0    0.0  0.980824
543     1  0.498141  0.501859       1  ...  1.099895   1.0    0.0  0.980952

[5 rows x 10 columns]
2022-12-25 00:00:25,244:INFO:logic:main.py:469:getModel:174970: df_panel.iloc[-5:,:] :
    pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
45     1  0.497986  0.502014       0  ...  1.098562   1.0    0.0  0.978150
46     1  0.492031  0.507969       1  ...  1.098934   1.0    0.0  0.980856
47     1  0.497039  0.502961       1  ...  1.099490   1.0    0.0  0.981352
48     1  0.499194  0.500806       1  ...  1.099751   1.0    0.0  0.982301
49     1  0.498141  0.501859       1  ...  1.099895   1.0    0.0  0.980952

[5 rows x 10 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '42.528', 'enterprice': '16701.5', 'countrevence': '0', 'unrealprofit': '5530.24732194432', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '16831.53779444', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}


## /root/FIL/strategy/modifiedmom/log.txt ----- -----

2022-12-25 00:00:01,459:INFO:modifiedmom:main.py:145:handleKline:185213: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
571  20221224   231000    231959  1671895199  16829.9    16825 -0.000291
572  20221224   232000    232959  1671895799    16825    16828  0.000178
573  20221224   233000    233959  1671896399    16828    16832  0.000238
574  20221224   234000    234959  1671896999    16832  16826.7 -0.000315
575  20221224   235000    235959  1671897599  16826.8  16830.2  0.000208
2022-12-25 00:00:01,459:INFO:modifiedmom:main.py:146:handleKline:185213: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': True, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True}
closeSell: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '55.391', 'enterprice': '16833.7', 'countrevence': '0', 'unrealprofit': '153.36416248818', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '16830.93124402', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
2022-12-25 00:00:02,194:INFO:modifiedmom:main.py:287:closeSell:185213: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False}
2022-12-25 00:00:02,194:INFO:modifiedmom:main.py:288:closeSell:185213: ret = self.client.insertMarketUOrder("simulator",  BTCUSDT, 55.391, buy ), ret=InsertOrderReturn{'result': 'success', 'clientorderid': '41412F1671897602192I0L59'}
2022-12-25 00:00:02,258:INFO:modifiedmom:main.py:206:insertFactor:185213: curDateTime:12250000, name:modifiedmom, symbol:BTCUSDT, tradeDate:20221224, closeTime:235959, close:16830.2, total:931503.0412233, mom:-0.001723171296502013, thd:0.0, side:buy 
2022-12-25 00:00:02,374:INFO:modifiedmom:main.py:316:handleOrderNew:185213: handleOrderNew: data=OrderType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'clientorderid': '41412F1671897602192I0L59', 'symbol': 'BTCUSDT', 'gatewayorderid': 1671897602311348, 'quantity': '55.391', 'price': '16830.3', 'stopprice': '0', 'ordertype': '', 'side': 'BUY', 'status': 'FILLED', 'positionside': 'LONG', 'createtime': 1671897601691, 'updatetime': 1671897602311, 'tradetype': 'usdt', 'selfid': 41412, 'filltrades': [TradeType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'tradeid': 1671897602311, 'clientorderid': '41412F1671897602192I0L59', 'price': '16830.3', 'quantity': '55.391', 'commission': '932.2471473', 'commissionasset': 'USDT', 'tradetime': 1671897602311, 'tradetype': 'usdt', 'gatetype': 'simulator', 'handletime': 1671897602311}], 'gatetype': 'simulator', 'handletime': 0}
127.0.0.1 - - [25/Dec/2022 00:00:02] "POST / HTTP/1.1" 200 -
2022-12-25 00:00:02,831:INFO:modifiedmom:main.py:319:handleOrderFilled:185213: handleOrderFilled: data=OrderType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'clientorderid': '41412F1671897602192I0L59', 'symbol': 'BTCUSDT', 'gatewayorderid': 1671897602311348, 'quantity': '55.391', 'price': '16830.3', 'stopprice': '0', 'ordertype': '', 'side': 'BUY', 'status': 'FILLED', 'positionside': 'LONG', 'createtime': 1671897601691, 'updatetime': 1671897602311, 'tradetype': 'usdt', 'selfid': 41412, 'filltrades': [TradeType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'tradeid': 1671897602311, 'clientorderid': '41412F1671897602192I0L59', 'price': '16830.3', 'quantity': '55.391', 'commission': '932.2471473', 'commissionasset': 'USDT', 'tradetime': 1671897602311, 'tradetype': 'usdt', 'gatetype': 'simulator', 'handletime': 1671897602311}], 'gatetype': 'simulator', 'handletime': 0}
127.0.0.1 - - [25/Dec/2022 00:00:02] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=4232 

self.closeSec=1671898199, self.tradeDate='20221225', self.openTime='000000', self.closeTime='000959', self.symbol='BTCUSDT', self.open='16830.3', self.close='16815.3'
2022-12-25 00:10:01,524:INFO:modifiedmom:main.py:144:handleKline:185213: self.closeSec=1671898199, self.tradeDate='20221225', self.openTime='000000', self.closeTime='000959',self.symbol='BTCUSDT',self.open='16830.3', self.close='16815.3'
127.0.0.1 - - [25/Dec/2022 00:10:01] "POST / HTTP/1.1" 200 -
2022-12-25 00:10:01,542:INFO:modifiedmom:main.py:145:handleKline:185213: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
572  20221224   232000    232959  1671895799    16825    16828  0.000178
573  20221224   233000    233959  1671896399    16828    16832  0.000238
574  20221224   234000    234959  1671896999    16832  16826.7 -0.000315
575  20221224   235000    235959  1671897599  16826.8  16830.2  0.000208
576  20221225   000000    000959  1671898199  16830.3  16815.3 -0.000885
2022-12-25 00:10:01,542:INFO:modifiedmom:main.py:146:handleKline:185213: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False}


## /root/FIL/strategy/pyemd/log.txt ----- -----

2022-12-24 23:50:00,576:INFO:pyemd2:main.py:127:handleKline:185189: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=4232 

self.closeSec=1671897599, self.tradeDate='20221224', self.openTime='235000', self.closeTime='235959', self.symbol='BTCUSDT', self.open='16826.8', self.close='16830.2'
127.0.0.1 - - [25/Dec/2022 00:00:01] "POST / HTTP/1.1" 200 -
2022-12-25 00:00:01,409:INFO:pyemd2:main.py:125:handleKline:185189: self.closeSec=1671897599, self.tradeDate='20221224', self.openTime='235000', self.closeTime='235959',self.symbol='BTCUSDT',self.open='16826.8', self.close='16830.2'
2022-12-25 00:00:01,464:INFO:pyemd2:main.py:126:handleKline:185189: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17419  20221224   231000    231959  1671895199  16829.9    16825
17420  20221224   232000    232959  1671895799    16825    16828
17421  20221224   233000    233959  1671896399    16828    16832
17422  20221224   234000    234959  1671896999    16832  16826.7
17423  20221224   235000    235959  1671897599  16826.8  16830.2
2022-12-25 00:00:01,464:INFO:pyemd2:main.py:127:handleKline:185189: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}
2022-12-25 00:00:01,678:INFO:pyemd2:main.py:190:insertFactor:185189: curDateTime:12250000, name:pyemd2, symbol:BTCUSDT, tradeDate:20221224, closeTime:235959, close:16830.2, total:946635.6384771, pct_pre:-0.0003802778404971008, thd:0.0877530628083194, side:sell 
127.0.0.1 - - [25/Dec/2022 00:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=4233 

self.closeSec=1671898199, self.tradeDate='20221225', self.openTime='000000', self.closeTime='000959', self.symbol='BTCUSDT', self.open='16830.3', self.close='16815.3'
2022-12-25 00:10:01,549:INFO:pyemd2:main.py:125:handleKline:185189: self.closeSec=1671898199, self.tradeDate='20221225', self.openTime='000000', self.closeTime='000959',self.symbol='BTCUSDT',self.open='16830.3', self.close='16815.3'
2022-12-25 00:10:01,566:INFO:pyemd2:main.py:126:handleKline:185189: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17420  20221224   232000    232959  1671895799    16825    16828
17421  20221224   233000    233959  1671896399    16828    16832
17422  20221224   234000    234959  1671896999    16832  16826.7
17423  20221224   235000    235959  1671897599  16826.8  16830.2
17424  20221225   000000    000959  1671898199  16830.3  16815.3
2022-12-25 00:10:01,566:INFO:pyemd2:main.py:127:handleKline:185189: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}


## /root/FIL/strategy/similarity/log.txt ----- -----

2022-12-25 00:00:01,471:INFO:testStrategy:main.py:102:handleKline:185174: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12235  20221224   231000    231959  1671895199  16829.9    16825
12236  20221224   232000    232959  1671895799    16825    16828
12237  20221224   233000    233959  1671896399    16828    16832
12238  20221224   234000    234959  1671896999    16832  16826.7
12239  20221224   235000    235959  1671897599  16826.8  16830.2
2022-12-25 00:00:01,472:INFO:testStrategy:main.py:103:handleKline:185174: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}
closeBuy: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '75.093', 'enterprice': '16784.4', 'countrevence': '0', 'unrealprofit': '3494.17070719386', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '16830.93124402', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
2022-12-25 00:00:02,272:INFO:testStrategy:main.py:233:closeBuy:185174: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False, 'isCorr': False}
2022-12-25 00:00:02,272:INFO:testStrategy:main.py:234:closeBuy:185174: ret = self.client.insertMarketUOrder("simulator",  BTCUSDT, 75.093, sell ), ret=InsertOrderReturn{'result': 'success', 'clientorderid': '41413F1671897602270I0L2'}
2022-12-25 00:00:02,294:INFO:testStrategy:main.py:172:insertFactor:185174: curDateTime:12250000, name:testStrategy, symbol:BTCUSDT, tradeDate:20221224, closeTime:235959, close:16830.2, total:1259130.5582508002, corrDate:20221028, corrVal:0.8627161513220728, side:sell 
127.0.0.1 - - [25/Dec/2022 00:00:02] "POST / HTTP/1.1" 200 -
2022-12-25 00:00:02,876:INFO:testStrategy:main.py:305:handleOrderNew:185174: handleOrderNew: data=OrderType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'clientorderid': '41413F1671897602270I0L2', 'symbol': 'BTCUSDT', 'gatewayorderid': 1671897602381184, 'quantity': '75.093', 'price': '16830.2', 'stopprice': '0', 'ordertype': '', 'side': 'SELL', 'status': 'FILLED', 'positionside': 'SHORT', 'createtime': 1671897601734, 'updatetime': 1671897602381, 'tradetype': 'usdt', 'selfid': 41413, 'filltrades': [TradeType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'tradeid': 1671897602381, 'clientorderid': '41413F1671897602270I0L2', 'price': '16830.2', 'quantity': '75.093', 'commission': '1263.8302086', 'commissionasset': 'USDT', 'tradetime': 1671897602381, 'tradetype': 'usdt', 'gatetype': 'simulator', 'handletime': 1671897602381}], 'gatetype': 'simulator', 'handletime': 0}
127.0.0.1 - - [25/Dec/2022 00:00:03] "POST / HTTP/1.1" 200 -
2022-12-25 00:00:03,511:INFO:testStrategy:main.py:308:handleOrderFilled:185174: handleOrderFilled: data=OrderType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'clientorderid': '41413F1671897602270I0L2', 'symbol': 'BTCUSDT', 'gatewayorderid': 1671897602381184, 'quantity': '75.093', 'price': '16830.2', 'stopprice': '0', 'ordertype': '', 'side': 'SELL', 'status': 'FILLED', 'positionside': 'SHORT', 'createtime': 1671897601734, 'updatetime': 1671897602381, 'tradetype': 'usdt', 'selfid': 41413, 'filltrades': [TradeType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'tradeid': 1671897602381, 'clientorderid': '41413F1671897602270I0L2', 'price': '16830.2', 'quantity': '75.093', 'commission': '1263.8302086', 'commissionasset': 'USDT', 'tradetime': 1671897602381, 'tradetype': 'usdt', 'gatetype': 'simulator', 'handletime': 1671897602381}], 'gatetype': 'simulator', 'handletime': 0}
127.0.0.1 - - [25/Dec/2022 00:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=4233 

self.closeSec=1671898199, self.tradeDate='20221225', self.openTime='000000', self.closeTime='000959', self.symbol='BTCUSDT', self.open='16830.3', self.close='16815.3'
2022-12-25 00:10:01,550:INFO:testStrategy:main.py:101:handleKline:185174: self.closeSec=1671898199, self.tradeDate='20221225', self.openTime='000000', self.closeTime='000959',self.symbol='BTCUSDT',self.open='16830.3', self.close='16815.3'
2022-12-25 00:10:01,557:INFO:testStrategy:main.py:102:handleKline:185174: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12236  20221224   232000    232959  1671895799    16825    16828
12237  20221224   233000    233959  1671896399    16828    16832
12238  20221224   234000    234959  1671896999    16832  16826.7
12239  20221224   235000    235959  1671897599  16826.8  16830.2
12240  20221225   000000    000959  1671898199  16830.3  16815.3
2022-12-25 00:10:01,557:INFO:testStrategy:main.py:103:handleKline:185174: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False, 'isCorr': False}


## /root/FIL/strategy/sr_min/log.txt ----- -----

127.0.0.1 - - [25/Dec/2022 00:10:01] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=0, self.total=1000000.0, self.flagDict['side']='', self.tradeCount=0, self.count=3896
self.closeSec=1671898199, self.tradeDate='20221225', self.openTime='000500', self.closeTime='000959', self.symbol='BTCUSDT', self.open=16832.0, self.close=16815.3, self.high=16832.1, self.low=16815.2, self.vol=617.906, self.amt=10394861.3025 
2022-12-25 00:10:01,481:INFO:sr_min:main.py:172:handleKline:449472: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5757  20221224   234500    234959  ...         0.0        0.0       0
5758  20221224   235000    235459  ...         0.0        0.0       0
5759  20221224   235500    235959  ...         0.0        0.0       0
5760  20221225   000000    000459  ...         0.0        0.0       0
5761  20221225   000500    000959  ...         0.0        0.0       0

[5 rows x 18 columns]
2022-12-25 00:10:01,481:INFO:sr_min:main.py:175:handleKline:449472: self.closeSec=1671898199, self.tradeDate='20221225', self.openTime='000500', self.closeTime='000959',self.symbol='BTCUSDT',self.open=16832.0, self.close=16815.3, self.high=16832.1, self.low=16815.2, self.vol=617.906, self.amt=10394861.3025, ukdf['pct'].iloc[-1]=-0.000998 , ukdf['amount'].iloc[-1]=10394861.3025, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5761, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': []}
type(curSign)=<class 'int'>, curSign=0, self.sign=0
127.0.0.1 - - [25/Dec/2022 00:15:00] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=0, self.total=1000000.0, self.flagDict['side']='', self.tradeCount=0, self.count=3897
self.closeSec=1671898499, self.tradeDate='20221225', self.openTime='001000', self.closeTime='001459', self.symbol='BTCUSDT', self.open=16815.3, self.close=16820.7, self.high=16823.4, self.low=16815.2, self.vol=443.65, self.amt=7461692.0754 
2022-12-25 00:15:00,595:INFO:sr_min:main.py:172:handleKline:449472: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5758  20221224   235000    235459  ...         0.0        0.0       0
5759  20221224   235500    235959  ...         0.0        0.0       0
5760  20221225   000000    000459  ...         0.0        0.0       0
5761  20221225   000500    000959  ...         0.0        0.0       0
5762  20221225   001000    001459  ...         0.0        0.0       0

[5 rows x 18 columns]
2022-12-25 00:15:00,596:INFO:sr_min:main.py:175:handleKline:449472: self.closeSec=1671898499, self.tradeDate='20221225', self.openTime='001000', self.closeTime='001459',self.symbol='BTCUSDT',self.open=16815.3, self.close=16820.7, self.high=16823.4, self.low=16815.2, self.vol=443.65, self.amt=7461692.0754, ukdf['pct'].iloc[-1]=0.000321 , ukdf['amount'].iloc[-1]=7461692.0754, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5762, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': []}
type(curSign)=<class 'int'>, curSign=0, self.sign=0


## /root/FIL/strategy/s_rsrs/log.txt ----- -----

723  20221224   120000    155959  1671868799  ...    723  0.005509 -1.369103    -1.0
724  20221224   160000    195959  1671883199  ...    724  0.003998 -1.342539    -1.0

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '53.372', 'enterprice': '16723.1', 'countrevence': '0', 'unrealprofit': '-5129.0492', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '16819.2', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-1, self.sign=-1
--handleKline--:  version='2.0.0', self.name='s_rsrs', self.symbol='BTCUSDT', interval='4h', intervalSec=14400, wid=25, thd=0.6, self.sign=-1, self.total=891652.7479068, self.flagDict['side']='sell', self.tradeCount=7, self.count=176
self.closeSec=1671897599, self.tradeDate='20221224', self.openTime='200000', self.closeTime='235959', self.symbol='BTCUSDT', self.open=16819.3, self.close=16830.2, self.high=16832.1, self.low=16807.7, self.vol=12508.365, self.amt=210386362.7765 
127.0.0.1 - - [25/Dec/2022 00:00:01] "POST / HTTP/1.1" 200 -
2022-12-25 00:00:01,271:INFO:s_rsrs:main.py:141:handleKline:185271: self.closeSec=1671897599, self.tradeDate='20221224', self.openTime='200000', self.closeTime='235959',self.symbol='BTCUSDT',self.open=16819.3, self.close=16830.2, self.high=16832.1, self.low=16807.7, self.vol=12508.365, self.amt=210386362.7765 
2022-12-25 00:00:01,295:INFO:s_rsrs:main.py:142:handleKline:185271: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime  ...        vol           amt       pct
721  20221224   040000    075959  ...  26104.665  4.384509e+08 -0.003688
722  20221224   080000    115959  ...  15312.893  2.573875e+08  0.003392
723  20221224   120000    155959  ...  15969.157  2.686288e+08  0.000410
724  20221224   160000    195959  ...  12975.412  2.183272e+08 -0.001247
725  20221224   200000    235959  ...  12508.365  2.103864e+08  0.000654

[5 rows x 11 columns]
2022-12-25 00:00:03,643:INFO:s_rsrs:main.py:151:handleKline:185271: df_s.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec  ...  index      beta    zscore  signal
721  20221224   040000    075959  1671839999  ...    721  0.026274 -1.387503    -1.0
722  20221224   080000    115959  1671854399  ...    722  0.000549 -1.414485    -1.0
723  20221224   120000    155959  1671868799  ...    723  0.005509 -1.369103    -1.0
724  20221224   160000    195959  1671883199  ...    724  0.003998 -1.342539    -1.0
725  20221224   200000    235959  1671897599  ...    725  0.002641 -1.316021    -1.0

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '53.372', 'enterprice': '16723.1', 'countrevence': '0', 'unrealprofit': '-5749.17914208836', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '16830.81901263', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-1, self.sign=-1


