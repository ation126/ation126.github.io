# 20230107 00:16:01

## /root/FIL/strategy/amihud/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=993672.4896432, self.flagDict['side']='sell', self.tradeCount=2, self.count=11642
self.closeSec=1673021399, self.tradeDate='20230107', self.openTime='000500', self.closeTime='000959', self.symbol='BTCUSDT', self.open=16823.4, self.close=16822.2, self.high=16825.4, self.low=16816.1, self.vol=1163.058, self.amt=19564829.1678 
127.0.0.1 - - [07/Jan/2023 00:10:01] "POST / HTTP/1.1" 200 -
2023-01-07 00:10:01,448:INFO:amihud:main.py:172:handleKline:200676: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5757  20230106   234500    234959  ...         0.0        0.0       0
5758  20230106   235000    235459  ...         0.0        0.0       0
5759  20230106   235500    235959  ...         0.0        0.0       0
5760  20230107   000000    000459  ...         0.0        0.0       0
5761  20230107   000500    000959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-01-07 00:10:01,448:INFO:amihud:main.py:175:handleKline:200676: self.closeSec=1673021399, self.tradeDate='20230107', self.openTime='000500', self.closeTime='000959',self.symbol='BTCUSDT',self.open=16823.4, self.close=16822.2, self.high=16825.4, self.low=16816.1, self.vol=1163.058, self.amt=19564829.1678, ukdf['pct'].iloc[-1]=-7.7e-05 , ukdf['amount'].iloc[-1]=19564829.1678, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5761, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '60.176', 'enterprice': '16529.3', 'countrevence': '0', 'unrealprofit': '-17625.5504', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '16822.2', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1
127.0.0.1 - - [07/Jan/2023 00:15:00] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=993672.4896432, self.flagDict['side']='sell', self.tradeCount=2, self.count=11643
self.closeSec=1673021699, self.tradeDate='20230107', self.openTime='001000', self.closeTime='001459', self.symbol='BTCUSDT', self.open=16822.2, self.close=16810.8, self.high=16822.2, self.low=16810.8, self.vol=967.491, self.amt=16269617.5971 
2023-01-07 00:15:00,569:INFO:amihud:main.py:172:handleKline:200676: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5758  20230106   235000    235459  ...         0.0        0.0       0
5759  20230106   235500    235959  ...         0.0        0.0       0
5760  20230107   000000    000459  ...         0.0        0.0       0
5761  20230107   000500    000959  ...         0.0        0.0       0
5762  20230107   001000    001459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-01-07 00:15:00,569:INFO:amihud:main.py:175:handleKline:200676: self.closeSec=1673021699, self.tradeDate='20230107', self.openTime='001000', self.closeTime='001459',self.symbol='BTCUSDT',self.open=16822.2, self.close=16810.8, self.high=16822.2, self.low=16810.8, self.vol=967.491, self.amt=16269617.5971, ukdf['pct'].iloc[-1]=-0.000678 , ukdf['amount'].iloc[-1]=16269617.5971, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5762, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '60.176', 'enterprice': '16529.3', 'countrevence': '0', 'unrealprofit': '-16983.75002314544', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '16811.53461219', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1


## /root/FIL/strategy/factorcheck/log.txt ----- -----


self.closeSec=1673021399, self.tradeDate='20230107', self.openTime='000500', self.closeTime='000959', self.symbol='BTCUSDT', self.open=16823.4, self.close=16822.2, self.high=16825.4, self.low=16816.1 
2023-01-07 00:10:01,408:INFO:factorcheck2:main.py:126:handleKline:185239: self.closeSec=1673021399, self.tradeDate='20230107', self.openTime='000500', self.closeTime='000959',self.symbol='BTCUSDT',self.open=16823.4, self.close=16822.2, self.high=16825.4, self.low=16816.1   
127.0.0.1 - - [07/Jan/2023 00:10:01] "POST / HTTP/1.1" 200 -
2023-01-07 00:10:01,437:INFO:factorcheck2:main.py:127:handleKline:185239: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1437  20230106   234500    234959  1673020199  ...  16807.2  0.000541   1725    3
1438  20230106   235000    235459  1673020499  ...  16814.4 -0.000059   1726    4
1439  20230106   235500    235959  1673020799  ...  16821.6  0.000547   1727    5
1440  20230107   000000    000459  1673021099  ...  16820.4 -0.000636   1440    0
1441  20230107   000500    000959  1673021399  ...  16816.1 -0.000077   1441    1

[5 rows x 11 columns]
2023-01-07 00:10:01,437:INFO:factorcheck2:main.py:128:handleKline:185239: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': False, 'isOpen': True, 'isClose': False, 'isTrig': True}
127.0.0.1 - - [07/Jan/2023 00:15:00] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.6019989606588494, self.count=12209 

self.closeSec=1673021699, self.tradeDate='20230107', self.openTime='001000', self.closeTime='001459', self.symbol='BTCUSDT', self.open=16822.2, self.close=16810.8, self.high=16822.2, self.low=16810.8 
2023-01-07 00:15:00,515:INFO:factorcheck2:main.py:126:handleKline:185239: self.closeSec=1673021699, self.tradeDate='20230107', self.openTime='001000', self.closeTime='001459',self.symbol='BTCUSDT',self.open=16822.2, self.close=16810.8, self.high=16822.2, self.low=16810.8   
2023-01-07 00:15:00,552:INFO:factorcheck2:main.py:127:handleKline:185239: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1438  20230106   235000    235459  1673020499  ...  16814.4 -0.000059   1726    4
1439  20230106   235500    235959  1673020799  ...  16821.6  0.000547   1727    5
1440  20230107   000000    000459  1673021099  ...  16820.4 -0.000636   1440    0
1441  20230107   000500    000959  1673021399  ...  16816.1 -0.000077   1441    1
1442  20230107   001000    001459  1673021699  ...  16810.8 -0.000678   1442    2

[5 rows x 11 columns]
2023-01-07 00:15:00,553:INFO:factorcheck2:main.py:128:handleKline:185239: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': False, 'isOpen': True, 'isClose': False, 'isTrig': True}


## /root/FIL/strategy/logic/log.txt ----- -----

2023-01-07 00:00:18,243:DEBUG:logic:main.py:456:getModel:726423: df_s.iloc[-5:,:] :
          date closeTime     open  ...    alpha58   alpha67   alpha72
5802  20230106    212959  16724.3  ...  48.333333  0.418109  0.632329
5803  20230106    215959  16684.0  ...  48.750000  0.481167  0.623310
5804  20230106    222959  16766.9  ...  48.333333  0.475503  0.617684
5805  20230106    225959  16758.3  ...  48.333333  0.465374  0.617490
5806  20230106    232959  16743.0  ...  48.333333  0.476168  0.612514

[5 rows x 33 columns]
0.5514705882352942
acc is : 0.5514705882352942
2023-01-07 00:00:18,352:INFO:logic:main.py:461:getModel:726423: df_pred.iloc[-5:,:] :
     pred    prob_0    prob_1  actual  ...  nav  sign   cost_        bm
539     1  0.479395  0.520605       1  ...  NaN   NaN -0.0016  0.995860
540     0  0.517174  0.482826       0  ...  NaN   NaN -0.0016  0.995355
541     1  0.498719  0.501281       0  ...  NaN   NaN -0.0016  0.994441
542     1  0.496964  0.503036       1  ...  NaN   NaN -0.0016  0.995308
543     0  0.504088  0.495912       1  ...  NaN   NaN -0.0016  0.999852

[5 rows x 10 columns]
2023-01-07 00:00:18,374:INFO:logic:main.py:471:getModel:726423: df_panel.iloc[-5:,:] :
    pred    prob_0    prob_1  actual  ...  nav  sign   cost_        bm
45     1  0.479184  0.520816       1  ...  NaN   NaN -0.0016  0.994679
46     0  0.517152  0.482848       0  ...  NaN   NaN -0.0016  0.994889
47     1  0.498713  0.501287       0  ...  NaN   NaN -0.0016  0.993974
48     1  0.496752  0.503248       1  ...  NaN   NaN -0.0016  0.994752
49     0  0.504088  0.495912       1  ...  NaN   NaN -0.0016  0.999852

[5 rows x 10 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '42.528', 'enterprice': '16701.5', 'countrevence': '0', 'unrealprofit': '5941.1616', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '16841.2', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}


## /root/FIL/strategy/modifiedmom/log.txt ----- -----

2023-01-07 00:00:01,013:INFO:modifiedmom:main.py:145:handleKline:185213: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
571  20230106   231000    231959  1673018399  16767.5  16780.6  0.000781
572  20230106   232000    232959  1673018999  16780.6  16757.6 -0.001371
573  20230106   233000    233959  1673019599  16757.6  16799.9  0.002524
574  20230106   234000    234959  1673020199  16799.9    16826  0.001554
575  20230106   235000    235959  1673020799  16823.8  16834.1  0.000481
2023-01-07 00:00:01,013:INFO:modifiedmom:main.py:146:handleKline:185213: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': True, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True}
closeSell: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '54.759', 'enterprice': '16831.6', 'countrevence': '0', 'unrealprofit': '-158.32108041564', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '16834.49123396', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
2023-01-07 00:00:01,644:INFO:modifiedmom:main.py:287:closeSell:185213: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False}
2023-01-07 00:00:01,644:INFO:modifiedmom:main.py:288:closeSell:185213: ret = self.client.insertMarketUOrder("simulator",  BTCUSDT, 54.759, buy ), ret=InsertOrderReturn{'result': 'success', 'clientorderid': '41481F1673020801643I0L59'}
2023-01-07 00:00:01,667:INFO:modifiedmom:main.py:206:insertFactor:185213: curDateTime:1070000, name:modifiedmom, symbol:BTCUSDT, tradeDate:20230106, closeTime:235959, close:16834.1, total:920759.9028155999, mom:-0.0003846009754859825, thd:0.0, side:buy 
127.0.0.1 - - [07/Jan/2023 00:00:01] "POST / HTTP/1.1" 200 -
2023-01-07 00:00:01,812:INFO:modifiedmom:main.py:316:handleOrderNew:185213: handleOrderNew: data=OrderType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'clientorderid': '41481F1673020801643I0L59', 'symbol': 'BTCUSDT', 'gatewayorderid': 1673020801756908, 'quantity': '54.759', 'price': '16834.2', 'stopprice': '0', 'ordertype': '', 'side': 'BUY', 'status': 'FILLED', 'positionside': 'LONG', 'createtime': 1673020801190, 'updatetime': 1673020801756, 'tradetype': 'usdt', 'selfid': 41481, 'filltrades': [TradeType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'tradeid': 1673020801756, 'clientorderid': '41481F1673020801643I0L59', 'price': '16834.2', 'quantity': '54.759', 'commission': '921.8239578', 'commissionasset': 'USDT', 'tradetime': 1673020801756, 'tradetype': 'usdt', 'gatetype': 'simulator', 'handletime': 1673020801756}], 'gatetype': 'simulator', 'handletime': 0}
127.0.0.1 - - [07/Jan/2023 00:00:02] "POST / HTTP/1.1" 200 -
2023-01-07 00:00:02,064:INFO:modifiedmom:main.py:319:handleOrderFilled:185213: handleOrderFilled: data=OrderType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'clientorderid': '41481F1673020801643I0L59', 'symbol': 'BTCUSDT', 'gatewayorderid': 1673020801756908, 'quantity': '54.759', 'price': '16834.2', 'stopprice': '0', 'ordertype': '', 'side': 'BUY', 'status': 'FILLED', 'positionside': 'LONG', 'createtime': 1673020801190, 'updatetime': 1673020801756, 'tradetype': 'usdt', 'selfid': 41481, 'filltrades': [TradeType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'tradeid': 1673020801756, 'clientorderid': '41481F1673020801643I0L59', 'price': '16834.2', 'quantity': '54.759', 'commission': '921.8239578', 'commissionasset': 'USDT', 'tradetime': 1673020801756, 'tradetype': 'usdt', 'gatetype': 'simulator', 'handletime': 1673020801756}], 'gatetype': 'simulator', 'handletime': 0}
127.0.0.1 - - [07/Jan/2023 00:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=6104 

self.closeSec=1673021399, self.tradeDate='20230107', self.openTime='000000', self.closeTime='000959', self.symbol='BTCUSDT', self.open='16834.1', self.close='16822.2'
2023-01-07 00:10:01,532:INFO:modifiedmom:main.py:144:handleKline:185213: self.closeSec=1673021399, self.tradeDate='20230107', self.openTime='000000', self.closeTime='000959',self.symbol='BTCUSDT',self.open='16834.1', self.close='16822.2'
2023-01-07 00:10:01,548:INFO:modifiedmom:main.py:145:handleKline:185213: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
572  20230106   232000    232959  1673018999  16780.6  16757.6 -0.001371
573  20230106   233000    233959  1673019599  16757.6  16799.9  0.002524
574  20230106   234000    234959  1673020199  16799.9    16826  0.001554
575  20230106   235000    235959  1673020799  16823.8  16834.1  0.000481
576  20230107   000000    000959  1673021399  16834.1  16822.2 -0.000707
2023-01-07 00:10:01,550:INFO:modifiedmom:main.py:146:handleKline:185213: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False}


## /root/FIL/strategy/pyemd/log.txt ----- -----

2023-01-06 23:50:00,818:INFO:pyemd2:main.py:127:handleKline:185189: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=6104 

self.closeSec=1673020799, self.tradeDate='20230106', self.openTime='235000', self.closeTime='235959', self.symbol='BTCUSDT', self.open='16823.8', self.close='16834.1'
127.0.0.1 - - [07/Jan/2023 00:00:00] "POST / HTTP/1.1" 200 -
2023-01-07 00:00:01,003:INFO:pyemd2:main.py:125:handleKline:185189: self.closeSec=1673020799, self.tradeDate='20230106', self.openTime='235000', self.closeTime='235959',self.symbol='BTCUSDT',self.open='16823.8', self.close='16834.1'
2023-01-07 00:00:01,043:INFO:pyemd2:main.py:126:handleKline:185189: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17419  20230106   231000    231959  1673018399  16767.5  16780.6
17420  20230106   232000    232959  1673018999  16780.6  16757.6
17421  20230106   233000    233959  1673019599  16757.6  16799.9
17422  20230106   234000    234959  1673020199  16799.9    16826
17423  20230106   235000    235959  1673020799  16823.8  16834.1
2023-01-07 00:00:01,051:INFO:pyemd2:main.py:127:handleKline:185189: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}
2023-01-07 00:00:01,211:INFO:pyemd2:main.py:190:insertFactor:185189: curDateTime:1070000, name:pyemd2, symbol:BTCUSDT, tradeDate:20230106, closeTime:235959, close:16834.1, total:939357.0753385, pct_pre:-0.003751988791527161, thd:0.055160422237329865, side:sell 

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=6105 

self.closeSec=1673021399, self.tradeDate='20230107', self.openTime='000000', self.closeTime='000959', self.symbol='BTCUSDT', self.open='16834.1', self.close='16822.2'
2023-01-07 00:10:01,544:INFO:pyemd2:main.py:125:handleKline:185189: self.closeSec=1673021399, self.tradeDate='20230107', self.openTime='000000', self.closeTime='000959',self.symbol='BTCUSDT',self.open='16834.1', self.close='16822.2'
127.0.0.1 - - [07/Jan/2023 00:10:01] "POST / HTTP/1.1" 200 -
2023-01-07 00:10:01,555:INFO:pyemd2:main.py:126:handleKline:185189: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17420  20230106   232000    232959  1673018999  16780.6  16757.6
17421  20230106   233000    233959  1673019599  16757.6  16799.9
17422  20230106   234000    234959  1673020199  16799.9    16826
17423  20230106   235000    235959  1673020799  16823.8  16834.1
17424  20230107   000000    000959  1673021399  16834.1  16822.2
2023-01-07 00:10:01,555:INFO:pyemd2:main.py:127:handleKline:185189: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}


## /root/FIL/strategy/similarity/log.txt ----- -----

2023-01-07 00:00:01,074:INFO:testStrategy:main.py:102:handleKline:185174: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12235  20230106   231000    231959  1673018399  16767.5  16780.6
12236  20230106   232000    232959  1673018999  16780.6  16757.6
12237  20230106   233000    233959  1673019599  16757.6  16799.9
12238  20230106   234000    234959  1673020199  16799.9    16826
12239  20230106   235000    235959  1673020799  16823.8  16834.1
2023-01-07 00:00:01,074:INFO:testStrategy:main.py:103:handleKline:185174: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': True, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}
closeSell: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '73.34', 'enterprice': '16829.9', 'countrevence': '0', 'unrealprofit': '-336.7210986264', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '16834.49123396', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
2023-01-07 00:00:02,024:INFO:testStrategy:main.py:253:closeSell:185174: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False, 'isCorr': False}
2023-01-07 00:00:02,024:INFO:testStrategy:main.py:254:closeSell:185174: ret = self.client.insertMarketUOrder("simulator",  BTCUSDT, 73.34, buy ), ret=InsertOrderReturn{'result': 'success', 'clientorderid': '41482F1673020801849I0L2'}
2023-01-07 00:00:02,050:INFO:testStrategy:main.py:172:insertFactor:185174: curDateTime:1070000, name:testStrategy, symbol:BTCUSDT, tradeDate:20230106, closeTime:235959, close:16834.1, total:1233070.561134, corrDate:20221221, corrVal:0.7763141625934845, side:buy 
127.0.0.1 - - [07/Jan/2023 00:00:02] "POST / HTTP/1.1" 200 -
2023-01-07 00:00:02,177:INFO:testStrategy:main.py:305:handleOrderNew:185174: handleOrderNew: data=OrderType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'clientorderid': '41482F1673020801849I0L2', 'symbol': 'BTCUSDT', 'gatewayorderid': 1673020802119740, 'quantity': '73.34', 'price': '16834.2', 'stopprice': '0', 'ordertype': '', 'side': 'BUY', 'status': 'FILLED', 'positionside': 'LONG', 'createtime': 1673020801319, 'updatetime': 1673020802119, 'tradetype': 'usdt', 'selfid': 41482, 'filltrades': [TradeType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'tradeid': 1673020802119, 'clientorderid': '41482F1673020801849I0L2', 'price': '16834.2', 'quantity': '73.34', 'commission': '1234.620228', 'commissionasset': 'USDT', 'tradetime': 1673020802119, 'tradetype': 'usdt', 'gatetype': 'simulator', 'handletime': 1673020802119}], 'gatetype': 'simulator', 'handletime': 0}
127.0.0.1 - - [07/Jan/2023 00:00:02] "POST / HTTP/1.1" 200 -
2023-01-07 00:00:02,431:INFO:testStrategy:main.py:308:handleOrderFilled:185174: handleOrderFilled: data=OrderType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'clientorderid': '41482F1673020801849I0L2', 'symbol': 'BTCUSDT', 'gatewayorderid': 1673020802119740, 'quantity': '73.34', 'price': '16834.2', 'stopprice': '0', 'ordertype': '', 'side': 'BUY', 'status': 'FILLED', 'positionside': 'LONG', 'createtime': 1673020801319, 'updatetime': 1673020802119, 'tradetype': 'usdt', 'selfid': 41482, 'filltrades': [TradeType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'tradeid': 1673020802119, 'clientorderid': '41482F1673020801849I0L2', 'price': '16834.2', 'quantity': '73.34', 'commission': '1234.620228', 'commissionasset': 'USDT', 'tradetime': 1673020802119, 'tradetype': 'usdt', 'gatetype': 'simulator', 'handletime': 1673020802119}], 'gatetype': 'simulator', 'handletime': 0}

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=6105 

self.closeSec=1673021399, self.tradeDate='20230107', self.openTime='000000', self.closeTime='000959', self.symbol='BTCUSDT', self.open='16834.1', self.close='16822.2'
2023-01-07 00:10:01,534:INFO:testStrategy:main.py:101:handleKline:185174: self.closeSec=1673021399, self.tradeDate='20230107', self.openTime='000000', self.closeTime='000959',self.symbol='BTCUSDT',self.open='16834.1', self.close='16822.2'
127.0.0.1 - - [07/Jan/2023 00:10:01] "POST / HTTP/1.1" 200 -
2023-01-07 00:10:01,539:INFO:testStrategy:main.py:102:handleKline:185174: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12236  20230106   232000    232959  1673018999  16780.6  16757.6
12237  20230106   233000    233959  1673019599  16757.6  16799.9
12238  20230106   234000    234959  1673020199  16799.9    16826
12239  20230106   235000    235959  1673020799  16823.8  16834.1
12240  20230107   000000    000959  1673021399  16834.1  16822.2
2023-01-07 00:10:01,550:INFO:testStrategy:main.py:103:handleKline:185174: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False, 'isCorr': False}


## /root/FIL/strategy/sr_min/log.txt ----- -----

127.0.0.1 - - [07/Jan/2023 00:10:01] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=0, self.total=1000000.0, self.flagDict['side']='', self.tradeCount=0, self.count=7640
self.closeSec=1673021399, self.tradeDate='20230107', self.openTime='000500', self.closeTime='000959', self.symbol='BTCUSDT', self.open=16823.4, self.close=16822.2, self.high=16825.4, self.low=16816.1, self.vol=1163.058, self.amt=19564829.1678 
2023-01-07 00:10:01,488:INFO:sr_min:main.py:172:handleKline:449472: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5757  20230106   234500    234959  ...         0.0        0.0       0
5758  20230106   235000    235459  ...         0.0        0.0       0
5759  20230106   235500    235959  ...         0.0        0.0       0
5760  20230107   000000    000459  ...         0.0        0.0       0
5761  20230107   000500    000959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-01-07 00:10:01,489:INFO:sr_min:main.py:175:handleKline:449472: self.closeSec=1673021399, self.tradeDate='20230107', self.openTime='000500', self.closeTime='000959',self.symbol='BTCUSDT',self.open=16823.4, self.close=16822.2, self.high=16825.4, self.low=16816.1, self.vol=1163.058, self.amt=19564829.1678, ukdf['pct'].iloc[-1]=-7.7e-05 , ukdf['amount'].iloc[-1]=19564829.1678, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5761, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': []}
type(curSign)=<class 'int'>, curSign=0, self.sign=0
127.0.0.1 - - [07/Jan/2023 00:15:00] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=0, self.total=1000000.0, self.flagDict['side']='', self.tradeCount=0, self.count=7641
self.closeSec=1673021699, self.tradeDate='20230107', self.openTime='001000', self.closeTime='001459', self.symbol='BTCUSDT', self.open=16822.2, self.close=16810.8, self.high=16822.2, self.low=16810.8, self.vol=967.491, self.amt=16269617.5971 
2023-01-07 00:15:00,581:INFO:sr_min:main.py:172:handleKline:449472: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5758  20230106   235000    235459  ...         0.0        0.0       0
5759  20230106   235500    235959  ...         0.0        0.0       0
5760  20230107   000000    000459  ...         0.0        0.0       0
5761  20230107   000500    000959  ...         0.0        0.0       0
5762  20230107   001000    001459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-01-07 00:15:00,581:INFO:sr_min:main.py:175:handleKline:449472: self.closeSec=1673021699, self.tradeDate='20230107', self.openTime='001000', self.closeTime='001459',self.symbol='BTCUSDT',self.open=16822.2, self.close=16810.8, self.high=16822.2, self.low=16810.8, self.vol=967.491, self.amt=16269617.5971, ukdf['pct'].iloc[-1]=-0.000678 , ukdf['amount'].iloc[-1]=16269617.5971, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5762, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': []}
type(curSign)=<class 'int'>, curSign=0, self.sign=0


## /root/FIL/strategy/s_rsrs/log.txt ----- -----

723  20230106   120000    155959  1672991999  ...    723  0.397553  0.357165     NaN
724  20230106   160000    195959  1673006399  ...    724  0.430357  0.451420     NaN

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '52.77', 'enterprice': '16723.1', 'countrevence': '0', 'unrealprofit': '437.991', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '16731.4', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-9223372036854775808, self.sign=1
--handleKline--:  version='2.0.0', self.name='s_rsrs', self.symbol='BTCUSDT', interval='4h', intervalSec=14400, wid=25, thd=0.6, self.sign=1, self.total=881595.509013, self.flagDict['side']='buy', self.tradeCount=10, self.count=254
self.closeSec=1673020799, self.tradeDate='20230106', self.openTime='200000', self.closeTime='235959', self.symbol='BTCUSDT', self.open=16731.5, self.close=16834.1, self.high=16843.0, self.low=16664.8, self.vol=102292.442, self.amt=1714160856.7004 
2023-01-07 00:00:00,903:INFO:s_rsrs:main.py:141:handleKline:185271: self.closeSec=1673020799, self.tradeDate='20230106', self.openTime='200000', self.closeTime='235959',self.symbol='BTCUSDT',self.open=16731.5, self.close=16834.1, self.high=16843.0, self.low=16664.8, self.vol=102292.442, self.amt=1714160856.7004 
127.0.0.1 - - [07/Jan/2023 00:00:00] "POST / HTTP/1.1" 200 -
2023-01-07 00:00:00,918:INFO:s_rsrs:main.py:142:handleKline:185271: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime  ...         vol           amt       pct
721  20230106   040000    075959  ...   19079.522  3.212681e+08 -0.001928
722  20230106   080000    115959  ...   21068.083  3.545791e+08  0.000071
723  20230106   120000    155959  ...   23858.140  4.007046e+08 -0.002336
724  20230106   160000    195959  ...   43526.534  7.292327e+08 -0.003229
725  20230106   200000    235959  ...  102292.442  1.714161e+09  0.006132

[5 rows x 11 columns]
2023-01-07 00:00:02,510:INFO:s_rsrs:main.py:151:handleKline:185271: df_s.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec  ...  index      beta    zscore  signal
721  20230106   040000    075959  1672963199  ...    721  0.486126  0.669225     1.0
722  20230106   080000    115959  1672977599  ...    722  0.395637  0.362932     NaN
723  20230106   120000    155959  1672991999  ...    723  0.397553  0.357165     NaN
724  20230106   160000    195959  1673006399  ...    724  0.430357  0.451420     NaN
725  20230106   200000    235959  1673020799  ...    725  0.364248  0.223422     NaN

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '52.77', 'enterprice': '16723.1', 'countrevence': '0', 'unrealprofit': '5904.3726398466', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '16834.98881258', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-9223372036854775808, self.sign=1


