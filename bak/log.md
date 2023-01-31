# 20230201 00:16:01

## /root/FIL/strategy/amihud/log.txt ----- -----

127.0.0.1 - - [01/Feb/2023 00:10:01] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=993672.4896432, self.flagDict['side']='sell', self.tradeCount=2, self.count=18842
self.closeSec=1675181399, self.tradeDate='20230201', self.openTime='000500', self.closeTime='000959', self.symbol='BTCUSDT', self.open=23109.2, self.close=23136.4, self.high=23136.5, self.low=23098.7, self.vol=1032.409, self.amt=23867412.2357 
2023-02-01 00:10:01,713:INFO:amihud:main.py:172:handleKline:200676: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5757  20230131   234500    234959  ...         0.0        0.0       0
5758  20230131   235000    235459  ...         0.0        0.0       0
5759  20230131   235500    235959  ...         0.0        0.0       0
5760  20230201   000000    000459  ...         0.0        0.0       0
5761  20230201   000500    000959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-02-01 00:10:01,727:INFO:amihud:main.py:175:handleKline:200676: self.closeSec=1675181399, self.tradeDate='20230201', self.openTime='000500', self.closeTime='000959',self.symbol='BTCUSDT',self.open=23109.2, self.close=23136.4, self.high=23136.5, self.low=23098.7, self.vol=1032.409, self.amt=23867412.2357, ukdf['pct'].iloc[-1]=0.001177 , ukdf['amount'].iloc[-1]=23867412.2357, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5761, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '60.176', 'enterprice': '16529.3', 'countrevence': '0', 'unrealprofit': '-397602.62046419088', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '23136.62884313', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1
127.0.0.1 - - [01/Feb/2023 00:15:00] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=993672.4896432, self.flagDict['side']='sell', self.tradeCount=2, self.count=18843
self.closeSec=1675181699, self.tradeDate='20230201', self.openTime='001000', self.closeTime='001459', self.symbol='BTCUSDT', self.open=23136.5, self.close=23102.0, self.high=23136.5, self.low=23094.7, self.vol=1014.845, self.amt=23452064.2803 
2023-02-01 00:15:01,084:INFO:amihud:main.py:172:handleKline:200676: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5758  20230131   235000    235459  ...         0.0        0.0       0
5759  20230131   235500    235959  ...         0.0        0.0       0
5760  20230201   000000    000459  ...         0.0        0.0       0
5761  20230201   000500    000959  ...         0.0        0.0       0
5762  20230201   001000    001459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-02-01 00:15:01,084:INFO:amihud:main.py:175:handleKline:200676: self.closeSec=1675181699, self.tradeDate='20230201', self.openTime='001000', self.closeTime='001459',self.symbol='BTCUSDT',self.open=23136.5, self.close=23102.0, self.high=23136.5, self.low=23094.7, self.vol=1014.845, self.amt=23452064.2803, ukdf['pct'].iloc[-1]=-0.001487 , ukdf['amount'].iloc[-1]=23452064.2803, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5762, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '60.176', 'enterprice': '16529.3', 'countrevence': '0', 'unrealprofit': '-395524.8128', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '23102.1', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1


## /root/FIL/strategy/factorcheck/log.txt ----- -----


self.closeSec=1675181399, self.tradeDate='20230201', self.openTime='000500', self.closeTime='000959', self.symbol='BTCUSDT', self.open=23109.2, self.close=23136.4, self.high=23136.5, self.low=23098.7 
2023-02-01 00:10:01,689:INFO:factorcheck2:main.py:126:handleKline:185239: self.closeSec=1675181399, self.tradeDate='20230201', self.openTime='000500', self.closeTime='000959',self.symbol='BTCUSDT',self.open=23109.2, self.close=23136.4, self.high=23136.5, self.low=23098.7   
127.0.0.1 - - [01/Feb/2023 00:10:01] "POST / HTTP/1.1" 200 -
2023-02-01 00:10:01,723:INFO:factorcheck2:main.py:127:handleKline:185239: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1437  20230131   234500    234959  1675180199  ...  23120.5 -0.000194   1725    3
1438  20230131   235000    235459  1675180499  ...  23112.0 -0.000847   1726    4
1439  20230131   235500    235959  1675180799  ...  23095.0 -0.000125   1727    5
1440  20230201   000000    000459  1675181099  ...  23093.9 -0.000203   1440    0
1441  20230201   000500    000959  1675181399  ...  23098.7  0.001177   1441    1

[5 rows x 11 columns]
2023-02-01 00:10:01,723:INFO:factorcheck2:main.py:128:handleKline:185239: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': False, 'isOpen': True, 'isClose': False, 'isTrig': True}
127.0.0.1 - - [01/Feb/2023 00:15:00] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=2, self.factor=0.5758136816598068, self.count=19409 

self.closeSec=1675181699, self.tradeDate='20230201', self.openTime='001000', self.closeTime='001459', self.symbol='BTCUSDT', self.open=23136.5, self.close=23102.0, self.high=23136.5, self.low=23094.7 
2023-02-01 00:15:00,945:INFO:factorcheck2:main.py:126:handleKline:185239: self.closeSec=1675181699, self.tradeDate='20230201', self.openTime='001000', self.closeTime='001459',self.symbol='BTCUSDT',self.open=23136.5, self.close=23102.0, self.high=23136.5, self.low=23094.7   
2023-02-01 00:15:01,042:INFO:factorcheck2:main.py:127:handleKline:185239: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1438  20230131   235000    235459  1675180499  ...  23112.0 -0.000847   1726    4
1439  20230131   235500    235959  1675180799  ...  23095.0 -0.000125   1727    5
1440  20230201   000000    000459  1675181099  ...  23093.9 -0.000203   1440    0
1441  20230201   000500    000959  1675181399  ...  23098.7  0.001177   1441    1
1442  20230201   001000    001459  1675181699  ...  23094.7 -0.001487   1442    2

[5 rows x 11 columns]
2023-02-01 00:15:01,042:INFO:factorcheck2:main.py:128:handleKline:185239: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': False, 'isOpen': True, 'isClose': False, 'isTrig': True}


## /root/FIL/strategy/logic/log.txt ----- -----

2023-02-01 00:00:34,063:DEBUG:logic:main.py:463:getModel:885513: df_s.iloc[-5:,:] :
          date closeTime     open  ...    alpha58   alpha67   alpha72
5802  20230131    212959  22887.7  ...  51.250000  0.456541  0.578562
5803  20230131    215959  22887.2  ...  51.250000  0.508659  0.546812
5804  20230131    222959  23112.5  ...  50.833333  0.502020  0.519991
5805  20230131    225959  23081.7  ...  51.250000  0.508061  0.492366
5806  20230131    232959  23110.0  ...  51.250000  0.511997  0.464820

[5 rows x 33 columns]
0.5330882352941176
acc is : 0.5330882352941176
2023-02-01 00:00:34,218:INFO:logic:main.py:468:getModel:885513: df_pred.iloc[-5:,:] :
     pred    prob_0    prob_1  actual  ...       nav  sign   cost_        bm
539     0  0.523353  0.476647       1  ...  0.962354  -1.0  0.0000  1.103001
540     0  0.584265  0.415735       0  ...  0.959532   1.0 -0.0016  1.101531
541     0  0.534342  0.465658       1  ...  0.960713   1.0  0.0000  1.102887
542     0  0.543280  0.456720       1  ...  0.961482   1.0  0.0000  1.103770
543     0  0.541541  0.458459       0  ...  0.960875   1.0  0.0000  1.103073

[5 rows x 10 columns]
2023-02-01 00:00:34,253:INFO:logic:main.py:478:getModel:885513: df_panel.iloc[-5:,:] :
    pred    prob_0    prob_1  actual  ...       nav  sign   cost_        bm
45     0  0.522689  0.477311       1  ...  0.962354  -1.0  0.0000  1.101624
46     0  0.584141  0.415859       0  ...  0.959532   1.0 -0.0016  1.102315
47     0  0.534427  0.465573       1  ...  0.960713   1.0  0.0000  1.103672
48     0  0.542672  0.457328       1  ...  0.961482   1.0  0.0000  1.102917
49     0  0.541541  0.458459       0  ...  0.960875   1.0  0.0000  1.103073

[5 rows x 10 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '30.955', 'enterprice': '23100.3', 'countrevence': '0', 'unrealprofit': '705.774', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '23123.1', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}


## /root/FIL/strategy/modifiedmom/log.txt ----- -----

2023-02-01 00:00:02,342:INFO:modifiedmom:main.py:145:handleKline:185213: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
571  20230131   231000    231959  1675178399  23072.7  23144.8  0.003203
572  20230131   232000    232959  1675178999  23144.8  23128.5 -0.000704
573  20230131   233000    233959  1675179599  23128.4  23156.9  0.001228
574  20230131   234000    234959  1675180199  23156.9  23136.4 -0.000885
575  20230131   235000    235959  1675180799  23136.3  23113.9 -0.000972
2023-02-01 00:00:02,342:INFO:modifiedmom:main.py:146:handleKline:185213: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': True, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True}
closeSell: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '40.995', 'enterprice': '22833.6', 'countrevence': '0', 'unrealprofit': '-11586.0530374128', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '23116.22112544', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
2023-02-01 00:00:03,390:INFO:modifiedmom:main.py:287:closeSell:185213: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False}
2023-02-01 00:00:03,390:INFO:modifiedmom:main.py:288:closeSell:185213: ret = self.client.insertMarketUOrder("simulator",  BTCUSDT, 40.995, buy ), ret=InsertOrderReturn{'result': 'success', 'clientorderid': '41646F1675180803227I0L59'}
2023-02-01 00:00:03,408:INFO:modifiedmom:main.py:206:insertFactor:185213: curDateTime:2010000, name:modifiedmom, symbol:BTCUSDT, tradeDate:20230131, closeTime:235959, close:23113.9, total:935127.3685679999, mom:-0.002466507140120422, thd:0.0, side:buy 
127.0.0.1 - - [01/Feb/2023 00:00:03] "POST / HTTP/1.1" 200 -
2023-02-01 00:00:03,552:INFO:modifiedmom:main.py:316:handleOrderNew:185213: handleOrderNew: data=OrderType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'clientorderid': '41646F1675180803227I0L59', 'symbol': 'BTCUSDT', 'gatewayorderid': 1675180803504893, 'quantity': '40.995', 'price': '23115', 'stopprice': '0', 'ordertype': '', 'side': 'BUY', 'status': 'FILLED', 'positionside': 'LONG', 'createtime': 1675180802522, 'updatetime': 1675180803504, 'tradetype': 'usdt', 'selfid': 41646, 'filltrades': [TradeType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'tradeid': 1675180803504, 'clientorderid': '41646F1675180803227I0L59', 'price': '23115', 'quantity': '40.995', 'commission': '947.599425', 'commissionasset': 'USDT', 'tradetime': 1675180803504, 'tradetype': 'usdt', 'gatetype': 'simulator', 'handletime': 1675180803504}], 'gatetype': 'simulator', 'handletime': 0}
2023-02-01 00:00:03,745:INFO:modifiedmom:main.py:319:handleOrderFilled:185213: handleOrderFilled: data=OrderType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'clientorderid': '41646F1675180803227I0L59', 'symbol': 'BTCUSDT', 'gatewayorderid': 1675180803504893, 'quantity': '40.995', 'price': '23115', 'stopprice': '0', 'ordertype': '', 'side': 'BUY', 'status': 'FILLED', 'positionside': 'LONG', 'createtime': 1675180802522, 'updatetime': 1675180803504, 'tradetype': 'usdt', 'selfid': 41646, 'filltrades': [TradeType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'tradeid': 1675180803504, 'clientorderid': '41646F1675180803227I0L59', 'price': '23115', 'quantity': '40.995', 'commission': '947.599425', 'commissionasset': 'USDT', 'tradetime': 1675180803504, 'tradetype': 'usdt', 'gatetype': 'simulator', 'handletime': 1675180803504}], 'gatetype': 'simulator', 'handletime': 0}
127.0.0.1 - - [01/Feb/2023 00:00:03] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=9704 

self.closeSec=1675181399, self.tradeDate='20230201', self.openTime='000000', self.closeTime='000959', self.symbol='BTCUSDT', self.open='23114', self.close='23136.4'
2023-02-01 00:10:01,777:INFO:modifiedmom:main.py:144:handleKline:185213: self.closeSec=1675181399, self.tradeDate='20230201', self.openTime='000000', self.closeTime='000959',self.symbol='BTCUSDT',self.open='23114', self.close='23136.4'
127.0.0.1 - - [01/Feb/2023 00:10:01] "POST / HTTP/1.1" 200 -
2023-02-01 00:10:01,822:INFO:modifiedmom:main.py:145:handleKline:185213: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
572  20230131   232000    232959  1675178999  23144.8  23128.5 -0.000704
573  20230131   233000    233959  1675179599  23128.4  23156.9  0.001228
574  20230131   234000    234959  1675180199  23156.9  23136.4 -0.000885
575  20230131   235000    235959  1675180799  23136.3  23113.9 -0.000972
576  20230201   000000    000959  1675181399    23114  23136.4  0.000973
2023-02-01 00:10:01,822:INFO:modifiedmom:main.py:146:handleKline:185213: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False}


## /root/FIL/strategy/pyemd/log.txt ----- -----

2023-01-31 23:50:00,605:INFO:pyemd2:main.py:127:handleKline:185189: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}
127.0.0.1 - - [01/Feb/2023 00:00:02] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=9704 

self.closeSec=1675180799, self.tradeDate='20230131', self.openTime='235000', self.closeTime='235959', self.symbol='BTCUSDT', self.open='23136.3', self.close='23113.9'
2023-02-01 00:00:02,296:INFO:pyemd2:main.py:125:handleKline:185189: self.closeSec=1675180799, self.tradeDate='20230131', self.openTime='235000', self.closeTime='235959',self.symbol='BTCUSDT',self.open='23136.3', self.close='23113.9'
2023-02-01 00:00:02,372:INFO:pyemd2:main.py:126:handleKline:185189: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17419  20230131   231000    231959  1675178399  23072.7  23144.8
17420  20230131   232000    232959  1675178999  23144.8  23128.5
17421  20230131   233000    233959  1675179599  23128.4  23156.9
17422  20230131   234000    234959  1675180199  23156.9  23136.4
17423  20230131   235000    235959  1675180799  23136.3  23113.9
2023-02-01 00:00:02,373:INFO:pyemd2:main.py:127:handleKline:185189: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}
2023-02-01 00:00:02,547:INFO:pyemd2:main.py:190:insertFactor:185189: curDateTime:2010000, name:pyemd2, symbol:BTCUSDT, tradeDate:20230131, closeTime:235959, close:23113.9, total:949628.8116041, pct_pre:-0.012497087177539834, thd:0.18507188035304234, side:sell 

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=9705 

self.closeSec=1675181399, self.tradeDate='20230201', self.openTime='000000', self.closeTime='000959', self.symbol='BTCUSDT', self.open='23114', self.close='23136.4'
2023-02-01 00:10:01,797:INFO:pyemd2:main.py:125:handleKline:185189: self.closeSec=1675181399, self.tradeDate='20230201', self.openTime='000000', self.closeTime='000959',self.symbol='BTCUSDT',self.open='23114', self.close='23136.4'
127.0.0.1 - - [01/Feb/2023 00:10:01] "POST / HTTP/1.1" 200 -
2023-02-01 00:10:01,830:INFO:pyemd2:main.py:126:handleKline:185189: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17420  20230131   232000    232959  1675178999  23144.8  23128.5
17421  20230131   233000    233959  1675179599  23128.4  23156.9
17422  20230131   234000    234959  1675180199  23156.9  23136.4
17423  20230131   235000    235959  1675180799  23136.3  23113.9
17424  20230201   000000    000959  1675181399    23114  23136.4
2023-02-01 00:10:01,831:INFO:pyemd2:main.py:127:handleKline:185189: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}


## /root/FIL/strategy/similarity/log.txt ----- -----

2023-02-01 00:00:02,353:INFO:testStrategy:main.py:102:handleKline:185174: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12235  20230131   231000    231959  1675178399  23072.7  23144.8
12236  20230131   232000    232959  1675178999  23144.8  23128.5
12237  20230131   233000    233959  1675179599  23128.4  23156.9
12238  20230131   234000    234959  1675180199  23156.9  23136.4
12239  20230131   235000    235959  1675180799  23136.3  23113.9
2023-02-01 00:00:02,353:INFO:testStrategy:main.py:103:handleKline:185174: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}
closeBuy: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '49.556', 'enterprice': '22729.2', 'countrevence': '0', 'unrealprofit': '19179.21889230464', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '23116.22112544', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
2023-02-01 00:00:03,030:INFO:testStrategy:main.py:233:closeBuy:185174: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False, 'isCorr': False}
2023-02-01 00:00:03,030:INFO:testStrategy:main.py:234:closeBuy:185174: ret = self.client.insertMarketUOrder("simulator",  BTCUSDT, 49.556, sell ), ret=InsertOrderReturn{'result': 'success', 'clientorderid': '41645F1675180803028I0L2'}
2023-02-01 00:00:03,054:INFO:testStrategy:main.py:172:insertFactor:185174: curDateTime:2010000, name:testStrategy, symbol:BTCUSDT, tradeDate:20230131, closeTime:235959, close:23113.9, total:1125241.8669648, corrDate:20221206, corrVal:0.9500465033512855, side:sell 
2023-02-01 00:00:03,166:INFO:testStrategy:main.py:305:handleOrderNew:185174: handleOrderNew: data=OrderType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'clientorderid': '41645F1675180803028I0L2', 'symbol': 'BTCUSDT', 'gatewayorderid': 1675180803152299, 'quantity': '49.556', 'price': '23114.9', 'stopprice': '0', 'ordertype': '', 'side': 'SELL', 'status': 'FILLED', 'positionside': 'SHORT', 'createtime': 1675180802615, 'updatetime': 1675180803152, 'tradetype': 'usdt', 'selfid': 41645, 'filltrades': [TradeType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'tradeid': 1675180803152, 'clientorderid': '41645F1675180803028I0L2', 'price': '23114.9', 'quantity': '49.556', 'commission': '1145.4819844', 'commissionasset': 'USDT', 'tradetime': 1675180803152, 'tradetype': 'usdt', 'gatetype': 'simulator', 'handletime': 1675180803152}], 'gatetype': 'simulator', 'handletime': 0}
127.0.0.1 - - [01/Feb/2023 00:00:03] "POST / HTTP/1.1" 200 -
2023-02-01 00:00:03,423:INFO:testStrategy:main.py:308:handleOrderFilled:185174: handleOrderFilled: data=OrderType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'clientorderid': '41645F1675180803028I0L2', 'symbol': 'BTCUSDT', 'gatewayorderid': 1675180803152299, 'quantity': '49.556', 'price': '23114.9', 'stopprice': '0', 'ordertype': '', 'side': 'SELL', 'status': 'FILLED', 'positionside': 'SHORT', 'createtime': 1675180802615, 'updatetime': 1675180803152, 'tradetype': 'usdt', 'selfid': 41645, 'filltrades': [TradeType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'tradeid': 1675180803152, 'clientorderid': '41645F1675180803028I0L2', 'price': '23114.9', 'quantity': '49.556', 'commission': '1145.4819844', 'commissionasset': 'USDT', 'tradetime': 1675180803152, 'tradetype': 'usdt', 'gatetype': 'simulator', 'handletime': 1675180803152}], 'gatetype': 'simulator', 'handletime': 0}
127.0.0.1 - - [01/Feb/2023 00:00:03] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=9705 

self.closeSec=1675181399, self.tradeDate='20230201', self.openTime='000000', self.closeTime='000959', self.symbol='BTCUSDT', self.open='23114', self.close='23136.4'
2023-02-01 00:10:01,808:INFO:testStrategy:main.py:101:handleKline:185174: self.closeSec=1675181399, self.tradeDate='20230201', self.openTime='000000', self.closeTime='000959',self.symbol='BTCUSDT',self.open='23114', self.close='23136.4'
127.0.0.1 - - [01/Feb/2023 00:10:01] "POST / HTTP/1.1" 200 -
2023-02-01 00:10:01,829:INFO:testStrategy:main.py:102:handleKline:185174: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12236  20230131   232000    232959  1675178999  23144.8  23128.5
12237  20230131   233000    233959  1675179599  23128.4  23156.9
12238  20230131   234000    234959  1675180199  23156.9  23136.4
12239  20230131   235000    235959  1675180799  23136.3  23113.9
12240  20230201   000000    000959  1675181399    23114  23136.4
2023-02-01 00:10:01,829:INFO:testStrategy:main.py:103:handleKline:185174: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False, 'isCorr': False}


## /root/FIL/strategy/sr_min/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=0, self.total=1000000.0, self.flagDict['side']='', self.tradeCount=0, self.count=14840
self.closeSec=1675181399, self.tradeDate='20230201', self.openTime='000500', self.closeTime='000959', self.symbol='BTCUSDT', self.open=23109.2, self.close=23136.4, self.high=23136.5, self.low=23098.7, self.vol=1032.409, self.amt=23867412.2357 
127.0.0.1 - - [01/Feb/2023 00:10:01] "POST / HTTP/1.1" 200 -
2023-02-01 00:10:01,745:INFO:sr_min:main.py:172:handleKline:449472: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5757  20230131   234500    234959  ...         0.0        0.0       0
5758  20230131   235000    235459  ...         0.0        0.0       0
5759  20230131   235500    235959  ...         0.0        0.0       0
5760  20230201   000000    000459  ...         0.0        0.0       0
5761  20230201   000500    000959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-02-01 00:10:01,745:INFO:sr_min:main.py:175:handleKline:449472: self.closeSec=1675181399, self.tradeDate='20230201', self.openTime='000500', self.closeTime='000959',self.symbol='BTCUSDT',self.open=23109.2, self.close=23136.4, self.high=23136.5, self.low=23098.7, self.vol=1032.409, self.amt=23867412.2357, ukdf['pct'].iloc[-1]=0.001177 , ukdf['amount'].iloc[-1]=23867412.2357, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5761, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': []}
type(curSign)=<class 'int'>, curSign=0, self.sign=0
--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=0, self.total=1000000.0, self.flagDict['side']='', self.tradeCount=0, self.count=14841
self.closeSec=1675181699, self.tradeDate='20230201', self.openTime='001000', self.closeTime='001459', self.symbol='BTCUSDT', self.open=23136.5, self.close=23102.0, self.high=23136.5, self.low=23094.7, self.vol=1014.845, self.amt=23452064.2803 
127.0.0.1 - - [01/Feb/2023 00:15:00] "POST / HTTP/1.1" 200 -
2023-02-01 00:15:01,042:INFO:sr_min:main.py:172:handleKline:449472: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5758  20230131   235000    235459  ...         0.0        0.0       0
5759  20230131   235500    235959  ...         0.0        0.0       0
5760  20230201   000000    000459  ...         0.0        0.0       0
5761  20230201   000500    000959  ...         0.0        0.0       0
5762  20230201   001000    001459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-02-01 00:15:01,042:INFO:sr_min:main.py:175:handleKline:449472: self.closeSec=1675181699, self.tradeDate='20230201', self.openTime='001000', self.closeTime='001459',self.symbol='BTCUSDT',self.open=23136.5, self.close=23102.0, self.high=23136.5, self.low=23094.7, self.vol=1014.845, self.amt=23452064.2803, ukdf['pct'].iloc[-1]=-0.001487 , ukdf['amount'].iloc[-1]=23452064.2803, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5762, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': []}
type(curSign)=<class 'int'>, curSign=0, self.sign=0


## /root/FIL/strategy/s_rsrs/log.txt ----- -----

723  20230131   120000    155959  1675151999  ...    723  0.655813  0.534550     NaN
724  20230131   160000    195959  1675166399  ...    724  0.678704  0.609307     1.0

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '38.964', 'enterprice': '23700.1', 'countrevence': '0', 'unrealprofit': '-32449.2192', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '22867.3', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=1, self.sign=1
--handleKline--:  version='2.0.0', self.name='s_rsrs', self.symbol='BTCUSDT', interval='4h', intervalSec=14400, wid=25, thd=0.6, self.sign=1, self.total=922527.2457035999, self.flagDict['side']='buy', self.tradeCount=16, self.count=404127.0.0.1 - - [01/Feb/2023 00:00:02] "POST / HTTP/1.1" 200 -

self.closeSec=1675180799, self.tradeDate='20230131', self.openTime='200000', self.closeTime='235959', self.symbol='BTCUSDT', self.open=22857.0, self.close=23113.9, self.high=23200.0, self.low=22843.4, self.vol=113354.585, self.amt=2613077933.08604 
2023-02-01 00:00:02,179:INFO:s_rsrs:main.py:141:handleKline:185271: self.closeSec=1675180799, self.tradeDate='20230131', self.openTime='200000', self.closeTime='235959',self.symbol='BTCUSDT',self.open=22857.0, self.close=23113.9, self.high=23200.0, self.low=22843.4, self.vol=113354.585, self.amt=2613077933.08604 
2023-02-01 00:00:02,211:INFO:s_rsrs:main.py:142:handleKline:185271: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime  ...         vol           amt       pct
721  20230131   040000    075959  ...   82595.410  1.875681e+09  0.001589
722  20230131   080000    115959  ...   45917.886  1.048036e+09  0.000298
723  20230131   120000    155959  ...   43431.989  9.923849e+08  0.006177
724  20230131   160000    195959  ...   46060.100  1.054003e+09 -0.004824
725  20230131   200000    235959  ...  113354.585  2.613078e+09  0.011244

[5 rows x 11 columns]
2023-02-01 00:00:04,356:INFO:s_rsrs:main.py:151:handleKline:185271: df_s.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec  ...  index      beta    zscore  signal
721  20230131   040000    075959  1675123199  ...    721  0.537706  0.174729     NaN
722  20230131   080000    115959  1675137599  ...    722  0.569731  0.278332     NaN
723  20230131   120000    155959  1675151999  ...    723  0.655813  0.534550     NaN
724  20230131   160000    195959  1675166399  ...    724  0.678704  0.609307     1.0
725  20230131   200000    235959  1675180799  ...    725  0.665860  0.579371     NaN

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '38.964', 'enterprice': '23700.1', 'countrevence': '0', 'unrealprofit': '-22779.77059099896', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '23115.46365386', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-9223372036854775808, self.sign=1


