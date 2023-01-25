# 20230126 00:16:01

## /root/FIL/strategy/amihud/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=993672.4896432, self.flagDict['side']='sell', self.tradeCount=2, self.count=17114
self.closeSec=1674662999, self.tradeDate='20230126', self.openTime='000500', self.closeTime='000959', self.symbol='BTCUSDT', self.open=22589.4, self.close=22538.1, self.high=22589.5, self.low=22516.2, self.vol=1954.996, self.amt=44070726.5697 
127.0.0.1 - - [26/Jan/2023 00:10:01] "POST / HTTP/1.1" 200 -
2023-01-26 00:10:01,481:INFO:amihud:main.py:172:handleKline:200676: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5757  20230125   234500    234959  ...         0.0        0.0       0
5758  20230125   235000    235459  ...         0.0        0.0       0
5759  20230125   235500    235959  ...         0.0        0.0       0
5760  20230126   000000    000459  ...         0.0        0.0       0
5761  20230126   000500    000959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-01-26 00:10:01,481:INFO:amihud:main.py:175:handleKline:200676: self.closeSec=1674662999, self.tradeDate='20230126', self.openTime='000500', self.closeTime='000959',self.symbol='BTCUSDT',self.open=22589.4, self.close=22538.1, self.high=22589.5, self.low=22516.2, self.vol=1954.996, self.amt=44070726.5697, ukdf['pct'].iloc[-1]=-0.002275 , ukdf['amount'].iloc[-1]=44070726.5697, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5761, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '60.176', 'enterprice': '16529.3', 'countrevence': '0', 'unrealprofit': '-361609.6192', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '22538.5', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1
127.0.0.1 - - [26/Jan/2023 00:15:00] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=993672.4896432, self.flagDict['side']='sell', self.tradeCount=2, self.count=17115
self.closeSec=1674663299, self.tradeDate='20230126', self.openTime='001000', self.closeTime='001459', self.symbol='BTCUSDT', self.open=22538.1, self.close=22618.0, self.high=22618.0, self.low=22537.9, self.vol=2589.169, self.amt=58485190.7163 
2023-01-26 00:15:00,876:INFO:amihud:main.py:172:handleKline:200676: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5758  20230125   235000    235459  ...         0.0        0.0       0
5759  20230125   235500    235959  ...         0.0        0.0       0
5760  20230126   000000    000459  ...         0.0        0.0       0
5761  20230126   000500    000959  ...         0.0        0.0       0
5762  20230126   001000    001459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-01-26 00:15:00,876:INFO:amihud:main.py:175:handleKline:200676: self.closeSec=1674663299, self.tradeDate='20230126', self.openTime='001000', self.closeTime='001459',self.symbol='BTCUSDT',self.open=22538.1, self.close=22618.0, self.high=22618.0, self.low=22537.9, self.vol=2589.169, self.amt=58485190.7163, ukdf['pct'].iloc[-1]=0.003545 , ukdf['amount'].iloc[-1]=58485190.7163, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5762, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '60.176', 'enterprice': '16529.3', 'countrevence': '0', 'unrealprofit': '-366405.6464', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '22618.2', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1


## /root/FIL/strategy/factorcheck/log.txt ----- -----

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=237, self.factor=0.5323228993773417, self.count=17680 

self.closeSec=1674662999, self.tradeDate='20230126', self.openTime='000500', self.closeTime='000959', self.symbol='BTCUSDT', self.open=22589.4, self.close=22538.1, self.high=22589.5, self.low=22516.2 
2023-01-26 00:10:01,427:INFO:factorcheck2:main.py:126:handleKline:185239: self.closeSec=1674662999, self.tradeDate='20230126', self.openTime='000500', self.closeTime='000959',self.symbol='BTCUSDT',self.open=22589.4, self.close=22538.1, self.high=22589.5, self.low=22516.2   
2023-01-26 00:10:01,456:INFO:factorcheck2:main.py:127:handleKline:185239: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1437  20230125   234500    234959  1674661799  ...  22539.5  0.001482   1725    3
1438  20230125   235000    235459  1674662099  ...  22545.6 -0.000346   1726    4
1439  20230125   235500    235959  1674662399  ...  22558.1  0.000284   1727    5
1440  20230126   000000    000459  1674662699  ...  22563.0  0.000718   1440    0
1441  20230126   000500    000959  1674662999  ...  22516.2 -0.002275   1441    1

[5 rows x 11 columns]
2023-01-26 00:10:01,457:INFO:factorcheck2:main.py:128:handleKline:185239: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=237, self.factor=0.5323228993773417, self.count=17681 

self.closeSec=1674663299, self.tradeDate='20230126', self.openTime='001000', self.closeTime='001459', self.symbol='BTCUSDT', self.open=22538.1, self.close=22618.0, self.high=22618.0, self.low=22537.9 
2023-01-26 00:15:00,788:INFO:factorcheck2:main.py:126:handleKline:185239: self.closeSec=1674663299, self.tradeDate='20230126', self.openTime='001000', self.closeTime='001459',self.symbol='BTCUSDT',self.open=22538.1, self.close=22618.0, self.high=22618.0, self.low=22537.9   
127.0.0.1 - - [26/Jan/2023 00:15:00] "POST / HTTP/1.1" 200 -
2023-01-26 00:15:00,811:INFO:factorcheck2:main.py:127:handleKline:185239: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1438  20230125   235000    235459  1674662099  ...  22545.6 -0.000346   1726    4
1439  20230125   235500    235959  1674662399  ...  22558.1  0.000284   1727    5
1440  20230126   000000    000459  1674662699  ...  22563.0  0.000718   1440    0
1441  20230126   000500    000959  1674662999  ...  22516.2 -0.002275   1441    1
1442  20230126   001000    001459  1674663299  ...  22537.9  0.003545   1442    2

[5 rows x 11 columns]
2023-01-26 00:15:00,813:INFO:factorcheck2:main.py:128:handleKline:185239: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}


## /root/FIL/strategy/logic/log.txt ----- -----

2023-01-26 00:00:18,962:DEBUG:logic:main.py:463:getModel:885513: df_s.iloc[-5:,:] :
          date closeTime     open  ...    alpha58   alpha67   alpha72
5802  20230125    212959  22692.0  ...  54.583333  0.480573  0.567574
5803  20230125    215959  22678.4  ...  54.583333  0.463015  0.572209
5804  20230125    222959  22591.6  ...  54.166667  0.455668  0.579763
5805  20230125    225959  22558.2  ...  53.750000  0.432936  0.597278
5806  20230125    232959  22432.6  ...  53.750000  0.456769  0.604607

[5 rows x 33 columns]
0.5386029411764706
acc is : 0.5386029411764706
2023-01-26 00:00:19,061:INFO:logic:main.py:468:getModel:885513: df_pred.iloc[-5:,:] :
     pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
539     0  0.524581  0.475419       0  ...  0.983801  -1.0    0.0  1.080261
540     1  0.499650  0.500350       0  ...  0.985434  -1.0    0.0  1.078468
541     0  0.508264  0.491736       0  ...  0.990747  -1.0    0.0  1.072653
542     1  0.472371  0.527629       1  ...  0.986119  -1.0    0.0  1.077664
543     0  0.525163  0.474837       1  ...  0.984544  -1.0    0.0  1.079386

[5 rows x 10 columns]
2023-01-26 00:00:19,083:INFO:logic:main.py:478:getModel:885513: df_panel.iloc[-5:,:] :
    pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
45     0  0.524388  0.475612       0  ...  1.009483  -1.0    0.0  1.079956
46     1  0.499096  0.500904       0  ...  1.011159  -1.0    0.0  1.075300
47     0  0.507383  0.492617       0  ...  1.016611  -1.0    0.0  1.069503
48     1  0.472005  0.527995       1  ...  1.011861  -1.0    0.0  1.076126
49     0  0.525163  0.474837       1  ...  0.984544  -1.0    0.0  1.079386

[5 rows x 10 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '32.198', 'enterprice': '22732.6', 'countrevence': '0', 'unrealprofit': '5242.9940866353', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '22569.76398265', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}


## /root/FIL/strategy/modifiedmom/log.txt ----- -----

2023-01-26 00:00:01,769:INFO:modifiedmom:main.py:145:handleKline:185213: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
571  20230125   231000    231959  1674659999  22491.2  22517.2  0.001205
572  20230125   232000    232959  1674660599  22513.5  22540.6  0.001039
573  20230125   233000    233959  1674661199  22540.6  22486.4 -0.002405
574  20230125   234000    234959  1674661799  22486.4  22574.7  0.003927
575  20230125   235000    235959  1674662399  22574.7  22573.3 -0.000062
2023-01-26 00:00:01,782:INFO:modifiedmom:main.py:146:handleKline:185213: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': True, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True}
closeSell: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '42.138', 'enterprice': '22606.3', 'countrevence': '0', 'unrealprofit': '1252.52725979322', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '22576.57558831', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
2023-01-26 00:00:02,409:INFO:modifiedmom:main.py:287:closeSell:185213: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False}
2023-01-26 00:00:02,409:INFO:modifiedmom:main.py:288:closeSell:185213: ret = self.client.insertMarketUOrder("simulator",  BTCUSDT, 42.138, buy ), ret=InsertOrderReturn{'result': 'success', 'clientorderid': '41602F1674662402408I0L59'}
2023-01-26 00:00:02,451:INFO:modifiedmom:main.py:206:insertFactor:185213: curDateTime:1260000, name:modifiedmom, symbol:BTCUSDT, tradeDate:20230125, closeTime:235959, close:22573.3, total:951631.6851305999, mom:-0.01467264325112616, thd:0.0, side:buy 
127.0.0.1 - - [26/Jan/2023 00:00:02] "POST / HTTP/1.1" 200 -
2023-01-26 00:00:02,565:INFO:modifiedmom:main.py:316:handleOrderNew:185213: handleOrderNew: data=OrderType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'clientorderid': '41602F1674662402408I0L59', 'symbol': 'BTCUSDT', 'gatewayorderid': 1674662402519777, 'quantity': '42.138', 'price': '22575', 'stopprice': '0', 'ordertype': '', 'side': 'BUY', 'status': 'FILLED', 'positionside': 'LONG', 'createtime': 1674662401976, 'updatetime': 1674662402519, 'tradetype': 'usdt', 'selfid': 41602, 'filltrades': [TradeType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'tradeid': 1674662402519, 'clientorderid': '41602F1674662402408I0L59', 'price': '22575', 'quantity': '42.138', 'commission': '951.26535', 'commissionasset': 'USDT', 'tradetime': 1674662402519, 'tradetype': 'usdt', 'gatetype': 'simulator', 'handletime': 1674662402519}], 'gatetype': 'simulator', 'handletime': 0}
127.0.0.1 - - [26/Jan/2023 00:00:02] "POST / HTTP/1.1" 200 -
2023-01-26 00:00:02,865:INFO:modifiedmom:main.py:319:handleOrderFilled:185213: handleOrderFilled: data=OrderType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'clientorderid': '41602F1674662402408I0L59', 'symbol': 'BTCUSDT', 'gatewayorderid': 1674662402519777, 'quantity': '42.138', 'price': '22575', 'stopprice': '0', 'ordertype': '', 'side': 'BUY', 'status': 'FILLED', 'positionside': 'LONG', 'createtime': 1674662401976, 'updatetime': 1674662402519, 'tradetype': 'usdt', 'selfid': 41602, 'filltrades': [TradeType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'tradeid': 1674662402519, 'clientorderid': '41602F1674662402408I0L59', 'price': '22575', 'quantity': '42.138', 'commission': '951.26535', 'commissionasset': 'USDT', 'tradetime': 1674662402519, 'tradetype': 'usdt', 'gatetype': 'simulator', 'handletime': 1674662402519}], 'gatetype': 'simulator', 'handletime': 0}
127.0.0.1 - - [26/Jan/2023 00:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=8840 

self.closeSec=1674662999, self.tradeDate='20230126', self.openTime='000000', self.closeTime='000959', self.symbol='BTCUSDT', self.open='22573.4', self.close='22538.1'
2023-01-26 00:10:01,504:INFO:modifiedmom:main.py:144:handleKline:185213: self.closeSec=1674662999, self.tradeDate='20230126', self.openTime='000000', self.closeTime='000959',self.symbol='BTCUSDT',self.open='22573.4', self.close='22538.1'
2023-01-26 00:10:01,513:INFO:modifiedmom:main.py:145:handleKline:185213: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
572  20230125   232000    232959  1674660599  22513.5  22540.6  0.001039
573  20230125   233000    233959  1674661199  22540.6  22486.4 -0.002405
574  20230125   234000    234959  1674661799  22486.4  22574.7  0.003927
575  20230125   235000    235959  1674662399  22574.7  22573.3 -0.000062
576  20230126   000000    000959  1674662999  22573.4  22538.1 -0.001559
2023-01-26 00:10:01,513:INFO:modifiedmom:main.py:146:handleKline:185213: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False}


## /root/FIL/strategy/pyemd/log.txt ----- -----

2023-01-25 23:50:00,624:INFO:pyemd2:main.py:127:handleKline:185189: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}
127.0.0.1 - - [26/Jan/2023 00:00:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=8840 

self.closeSec=1674662399, self.tradeDate='20230125', self.openTime='235000', self.closeTime='235959', self.symbol='BTCUSDT', self.open='22574.7', self.close='22573.3'
2023-01-26 00:00:01,746:INFO:pyemd2:main.py:125:handleKline:185189: self.closeSec=1674662399, self.tradeDate='20230125', self.openTime='235000', self.closeTime='235959',self.symbol='BTCUSDT',self.open='22574.7', self.close='22573.3'
2023-01-26 00:00:01,753:INFO:pyemd2:main.py:126:handleKline:185189: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17419  20230125   231000    231959  1674659999  22491.2  22517.2
17420  20230125   232000    232959  1674660599  22513.5  22540.6
17421  20230125   233000    233959  1674661199  22540.6  22486.4
17422  20230125   234000    234959  1674661799  22486.4  22574.7
17423  20230125   235000    235959  1674662399  22574.7  22573.3
2023-01-26 00:00:01,753:INFO:pyemd2:main.py:127:handleKline:185189: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}
2023-01-26 00:00:01,886:INFO:pyemd2:main.py:190:insertFactor:185189: curDateTime:1260000, name:pyemd2, symbol:BTCUSDT, tradeDate:20230125, closeTime:235959, close:22573.3, total:950078.9425875, pct_pre:-0.012564767971200763, thd:-0.10513002409219735, side:sell 
127.0.0.1 - - [26/Jan/2023 00:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=8841 

self.closeSec=1674662999, self.tradeDate='20230126', self.openTime='000000', self.closeTime='000959', self.symbol='BTCUSDT', self.open='22573.4', self.close='22538.1'
2023-01-26 00:10:01,528:INFO:pyemd2:main.py:125:handleKline:185189: self.closeSec=1674662999, self.tradeDate='20230126', self.openTime='000000', self.closeTime='000959',self.symbol='BTCUSDT',self.open='22573.4', self.close='22538.1'
2023-01-26 00:10:01,539:INFO:pyemd2:main.py:126:handleKline:185189: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17420  20230125   232000    232959  1674660599  22513.5  22540.6
17421  20230125   233000    233959  1674661199  22540.6  22486.4
17422  20230125   234000    234959  1674661799  22486.4  22574.7
17423  20230125   235000    235959  1674662399  22574.7  22573.3
17424  20230126   000000    000959  1674662999  22573.4  22538.1
2023-01-26 00:10:01,540:INFO:pyemd2:main.py:127:handleKline:185189: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}


## /root/FIL/strategy/similarity/log.txt ----- -----

2023-01-26 00:00:01,842:INFO:testStrategy:main.py:102:handleKline:185174: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12235  20230125   231000    231959  1674659999  22491.2  22517.2
12236  20230125   232000    232959  1674660599  22513.5  22540.6
12237  20230125   233000    233959  1674661199  22540.6  22486.4
12238  20230125   234000    234959  1674661799  22486.4  22574.7
12239  20230125   235000    235959  1674662399  22574.7  22573.3
2023-01-26 00:00:01,842:INFO:testStrategy:main.py:103:handleKline:185174: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': True, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}
closeSell: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '49.217', 'enterprice': '22750.1', 'countrevence': '0', 'unrealprofit': '8540.35097014673', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '22576.57558831', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
2023-01-26 00:00:02,426:INFO:testStrategy:main.py:253:closeSell:185174: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False, 'isCorr': False}
2023-01-26 00:00:02,426:INFO:testStrategy:main.py:254:closeSell:185174: ret = self.client.insertMarketUOrder("simulator",  BTCUSDT, 49.217, buy ), ret=InsertOrderReturn{'result': 'success', 'clientorderid': '41603F1674662402422I0L2'}
2023-01-26 00:00:02,461:INFO:testStrategy:main.py:172:insertFactor:185174: curDateTime:1260000, name:testStrategy, symbol:BTCUSDT, tradeDate:20230125, closeTime:235959, close:22573.3, total:1118571.9800282998, corrDate:20221108, corrVal:0.8145947074186851, side:buy 
2023-01-26 00:00:02,867:INFO:testStrategy:main.py:305:handleOrderNew:185174: handleOrderNew: data=OrderType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'clientorderid': '41603F1674662402422I0L2', 'symbol': 'BTCUSDT', 'gatewayorderid': 1674662402529878, 'quantity': '49.217', 'price': '22575', 'stopprice': '0', 'ordertype': '', 'side': 'BUY', 'status': 'FILLED', 'positionside': 'LONG', 'createtime': 1674662402006, 'updatetime': 1674662402529, 'tradetype': 'usdt', 'selfid': 41603, 'filltrades': [TradeType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'tradeid': 1674662402529, 'clientorderid': '41603F1674662402422I0L2', 'price': '22575', 'quantity': '49.217', 'commission': '1111.073775', 'commissionasset': 'USDT', 'tradetime': 1674662402529, 'tradetype': 'usdt', 'gatetype': 'simulator', 'handletime': 1674662402529}], 'gatetype': 'simulator', 'handletime': 0}
127.0.0.1 - - [26/Jan/2023 00:00:02] "POST / HTTP/1.1" 200 -
2023-01-26 00:00:03,061:INFO:testStrategy:main.py:308:handleOrderFilled:185174: handleOrderFilled: data=OrderType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'clientorderid': '41603F1674662402422I0L2', 'symbol': 'BTCUSDT', 'gatewayorderid': 1674662402529878, 'quantity': '49.217', 'price': '22575', 'stopprice': '0', 'ordertype': '', 'side': 'BUY', 'status': 'FILLED', 'positionside': 'LONG', 'createtime': 1674662402006, 'updatetime': 1674662402529, 'tradetype': 'usdt', 'selfid': 41603, 'filltrades': [TradeType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'tradeid': 1674662402529, 'clientorderid': '41603F1674662402422I0L2', 'price': '22575', 'quantity': '49.217', 'commission': '1111.073775', 'commissionasset': 'USDT', 'tradetime': 1674662402529, 'tradetype': 'usdt', 'gatetype': 'simulator', 'handletime': 1674662402529}], 'gatetype': 'simulator', 'handletime': 0}
127.0.0.1 - - [26/Jan/2023 00:00:03] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=8841 

self.closeSec=1674662999, self.tradeDate='20230126', self.openTime='000000', self.closeTime='000959', self.symbol='BTCUSDT', self.open='22573.4', self.close='22538.1'
2023-01-26 00:10:01,522:INFO:testStrategy:main.py:101:handleKline:185174: self.closeSec=1674662999, self.tradeDate='20230126', self.openTime='000000', self.closeTime='000959',self.symbol='BTCUSDT',self.open='22573.4', self.close='22538.1'
127.0.0.1 - - [26/Jan/2023 00:10:01] "POST / HTTP/1.1" 200 -
2023-01-26 00:10:01,529:INFO:testStrategy:main.py:102:handleKline:185174: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12236  20230125   232000    232959  1674660599  22513.5  22540.6
12237  20230125   233000    233959  1674661199  22540.6  22486.4
12238  20230125   234000    234959  1674661799  22486.4  22574.7
12239  20230125   235000    235959  1674662399  22574.7  22573.3
12240  20230126   000000    000959  1674662999  22573.4  22538.1
2023-01-26 00:10:01,530:INFO:testStrategy:main.py:103:handleKline:185174: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False, 'isCorr': False}


## /root/FIL/strategy/sr_min/log.txt ----- -----

127.0.0.1 - - [26/Jan/2023 00:10:01] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=0, self.total=1000000.0, self.flagDict['side']='', self.tradeCount=0, self.count=13112
self.closeSec=1674662999, self.tradeDate='20230126', self.openTime='000500', self.closeTime='000959', self.symbol='BTCUSDT', self.open=22589.4, self.close=22538.1, self.high=22589.5, self.low=22516.2, self.vol=1954.996, self.amt=44070726.5697 
2023-01-26 00:10:01,467:INFO:sr_min:main.py:172:handleKline:449472: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5757  20230125   234500    234959  ...         0.0        0.0       0
5758  20230125   235000    235459  ...         0.0        0.0       0
5759  20230125   235500    235959  ...         0.0        0.0       0
5760  20230126   000000    000459  ...         0.0        0.0       0
5761  20230126   000500    000959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-01-26 00:10:01,467:INFO:sr_min:main.py:175:handleKline:449472: self.closeSec=1674662999, self.tradeDate='20230126', self.openTime='000500', self.closeTime='000959',self.symbol='BTCUSDT',self.open=22589.4, self.close=22538.1, self.high=22589.5, self.low=22516.2, self.vol=1954.996, self.amt=44070726.5697, ukdf['pct'].iloc[-1]=-0.002275 , ukdf['amount'].iloc[-1]=44070726.5697, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5761, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': []}
type(curSign)=<class 'int'>, curSign=0, self.sign=0
127.0.0.1 - - [26/Jan/2023 00:15:00] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=0, self.total=1000000.0, self.flagDict['side']='', self.tradeCount=0, self.count=13113
self.closeSec=1674663299, self.tradeDate='20230126', self.openTime='001000', self.closeTime='001459', self.symbol='BTCUSDT', self.open=22538.1, self.close=22618.0, self.high=22618.0, self.low=22537.9, self.vol=2589.169, self.amt=58485190.7163 
2023-01-26 00:15:00,875:INFO:sr_min:main.py:172:handleKline:449472: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5758  20230125   235000    235459  ...         0.0        0.0       0
5759  20230125   235500    235959  ...         0.0        0.0       0
5760  20230126   000000    000459  ...         0.0        0.0       0
5761  20230126   000500    000959  ...         0.0        0.0       0
5762  20230126   001000    001459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-01-26 00:15:00,876:INFO:sr_min:main.py:175:handleKline:449472: self.closeSec=1674663299, self.tradeDate='20230126', self.openTime='001000', self.closeTime='001459',self.symbol='BTCUSDT',self.open=22538.1, self.close=22618.0, self.high=22618.0, self.low=22537.9, self.vol=2589.169, self.amt=58485190.7163, ukdf['pct'].iloc[-1]=0.003545 , ukdf['amount'].iloc[-1]=58485190.7163, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5762, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': []}
type(curSign)=<class 'int'>, curSign=0, self.sign=0


## /root/FIL/strategy/s_rsrs/log.txt ----- -----

723  20230125   120000    155959  1674633599  ...    723  0.145590 -1.574237    -1.0
724  20230125   160000    195959  1674647999  ...    724  0.149681 -1.525917    -1.0

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '41.738', 'enterprice': '22927.7', 'countrevence': '0', 'unrealprofit': '13911.2754', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '22594.4', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-1, self.sign=-1
127.0.0.1 - - [26/Jan/2023 00:00:01] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='s_rsrs', self.symbol='BTCUSDT', interval='4h', intervalSec=14400, wid=25, thd=0.6, self.sign=-1, self.total=955999.3862573999, self.flagDict['side']='sell', self.tradeCount=15, self.count=368
self.closeSec=1674662399, self.tradeDate='20230125', self.openTime='200000', self.closeTime='235959', self.symbol='BTCUSDT', self.open=22595.8, self.close=22573.3, self.high=22747.1, self.low=22327.2, self.vol=127913.984, self.amt=2885107677.89743 
2023-01-26 00:00:01,638:INFO:s_rsrs:main.py:141:handleKline:185271: self.closeSec=1674662399, self.tradeDate='20230125', self.openTime='200000', self.closeTime='235959',self.symbol='BTCUSDT',self.open=22595.8, self.close=22573.3, self.high=22747.1, self.low=22327.2, self.vol=127913.984, self.amt=2885107677.89743 
2023-01-26 00:00:01,673:INFO:s_rsrs:main.py:142:handleKline:185271: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime  ...         vol           amt       pct
721  20230125   040000    075959  ...  141871.503  3.229601e+09 -0.016841
722  20230125   080000    115959  ...   97898.966  2.206165e+09  0.000601
723  20230125   120000    155959  ...   34838.121  7.901792e+08  0.002778
724  20230125   160000    195959  ...   57559.621  1.301308e+09 -0.004757
725  20230125   200000    235959  ...  127913.984  2.885108e+09 -0.001000

[5 rows x 11 columns]
2023-01-26 00:00:03,190:INFO:s_rsrs:main.py:151:handleKline:185271: df_s.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec  ...  index      beta    zscore  signal
721  20230125   040000    075959  1674604799  ...    721  0.040427 -1.910773    -1.0
722  20230125   080000    115959  1674619199  ...    722  0.162382 -1.576378    -1.0
723  20230125   120000    155959  1674633599  ...    723  0.145590 -1.574237    -1.0
724  20230125   160000    195959  1674647999  ...    724  0.149681 -1.525917    -1.0
725  20230125   200000    235959  1674662399  ...    725  0.256658 -1.252734    -1.0

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '41.738', 'enterprice': '22927.7', 'countrevence': '0', 'unrealprofit': '14691.97802277188', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '22575.69515974', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-1, self.sign=-1


