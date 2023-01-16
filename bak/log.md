# 20230117 00:16:01

## /root/FIL/strategy/amihud/log.txt ----- -----

127.0.0.1 - - [17/Jan/2023 00:10:01] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=993672.4896432, self.flagDict['side']='sell', self.tradeCount=2, self.count=14522
self.closeSec=1673885399, self.tradeDate='20230117', self.openTime='000500', self.closeTime='000959', self.symbol='BTCUSDT', self.open=20970.9, self.close=20976.1, self.high=20991.6, self.low=20953.2, self.vol=1992.206, self.amt=41776301.3363 
2023-01-17 00:10:01,534:INFO:amihud:main.py:172:handleKline:200676: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5757  20230116   234500    234959  ...         0.0        0.0       0
5758  20230116   235000    235459  ...         0.0        0.0       0
5759  20230116   235500    235959  ...         0.0        0.0       0
5760  20230117   000000    000459  ...         0.0        0.0       0
5761  20230117   000500    000959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-01-17 00:10:01,538:INFO:amihud:main.py:175:handleKline:200676: self.closeSec=1673885399, self.tradeDate='20230117', self.openTime='000500', self.closeTime='000959',self.symbol='BTCUSDT',self.open=20970.9, self.close=20976.1, self.high=20991.6, self.low=20953.2, self.vol=1992.206, self.amt=41776301.3363, ukdf['pct'].iloc[-1]=0.000463 , ukdf['amount'].iloc[-1]=41776301.3363, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5761, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '60.176', 'enterprice': '16529.3', 'countrevence': '0', 'unrealprofit': '-267556.93952957168', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '20975.54002143', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1
--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=993672.4896432, self.flagDict['side']='sell', self.tradeCount=2, self.count=14523
self.closeSec=1673885699, self.tradeDate='20230117', self.openTime='001000', self.closeTime='001459', self.symbol='BTCUSDT', self.open=20976.2, self.close=21039.1, self.high=21044.7, self.low=20972.7, self.vol=3129.06, self.amt=65753146.8564 
127.0.0.1 - - [17/Jan/2023 00:15:00] "POST / HTTP/1.1" 200 -
2023-01-17 00:15:00,929:INFO:amihud:main.py:172:handleKline:200676: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5758  20230116   235000    235459  ...         0.0        0.0       0
5759  20230116   235500    235959  ...         0.0        0.0       0
5760  20230117   000000    000459  ...         0.0        0.0       0
5761  20230117   000500    000959  ...         0.0        0.0       0
5762  20230117   001000    001459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-01-17 00:15:00,933:INFO:amihud:main.py:175:handleKline:200676: self.closeSec=1673885699, self.tradeDate='20230117', self.openTime='001000', self.closeTime='001459',self.symbol='BTCUSDT',self.open=20976.2, self.close=21039.1, self.high=21044.7, self.low=20972.7, self.vol=3129.06, self.amt=65753146.8564, ukdf['pct'].iloc[-1]=0.003003 , ukdf['amount'].iloc[-1]=65753146.8564, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5762, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '60.176', 'enterprice': '16529.3', 'countrevence': '0', 'unrealprofit': '-271500.90399623744', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '21041.08051044', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1


## /root/FIL/strategy/factorcheck/log.txt ----- -----

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=431, self.factor=0.525994869565364, self.count=15088 

self.closeSec=1673885399, self.tradeDate='20230117', self.openTime='000500', self.closeTime='000959', self.symbol='BTCUSDT', self.open=20970.9, self.close=20976.1, self.high=20991.6, self.low=20953.2 
2023-01-17 00:10:01,438:INFO:factorcheck2:main.py:126:handleKline:185239: self.closeSec=1673885399, self.tradeDate='20230117', self.openTime='000500', self.closeTime='000959',self.symbol='BTCUSDT',self.open=20970.9, self.close=20976.1, self.high=20991.6, self.low=20953.2   
2023-01-17 00:10:01,495:INFO:factorcheck2:main.py:127:handleKline:185239: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1437  20230116   234500    234959  1673884199  ...  20964.8  0.001869   1725    3
1438  20230116   235000    235459  1673884499  ...  20942.1 -0.001656   1726    4
1439  20230116   235500    235959  1673884799  ...  20960.3  0.000886   1727    5
1440  20230117   000000    000459  1673885099  ...  20965.3 -0.001629   1440    0
1441  20230117   000500    000959  1673885399  ...  20953.2  0.000463   1441    1

[5 rows x 11 columns]
2023-01-17 00:10:01,495:INFO:factorcheck2:main.py:128:handleKline:185239: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}
127.0.0.1 - - [17/Jan/2023 00:15:00] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=431, self.factor=0.525994869565364, self.count=15089 

self.closeSec=1673885699, self.tradeDate='20230117', self.openTime='001000', self.closeTime='001459', self.symbol='BTCUSDT', self.open=20976.2, self.close=21039.1, self.high=21044.7, self.low=20972.7 
2023-01-17 00:15:00,762:INFO:factorcheck2:main.py:126:handleKline:185239: self.closeSec=1673885699, self.tradeDate='20230117', self.openTime='001000', self.closeTime='001459',self.symbol='BTCUSDT',self.open=20976.2, self.close=21039.1, self.high=21044.7, self.low=20972.7   
2023-01-17 00:15:00,862:INFO:factorcheck2:main.py:127:handleKline:185239: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1438  20230116   235000    235459  1673884499  ...  20942.1 -0.001656   1726    4
1439  20230116   235500    235959  1673884799  ...  20960.3  0.000886   1727    5
1440  20230117   000000    000459  1673885099  ...  20965.3 -0.001629   1440    0
1441  20230117   000500    000959  1673885399  ...  20953.2  0.000463   1441    1
1442  20230117   001000    001459  1673885699  ...  20972.7  0.003003   1442    2

[5 rows x 11 columns]
2023-01-17 00:15:00,862:INFO:factorcheck2:main.py:128:handleKline:185239: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}


## /root/FIL/strategy/logic/log.txt ----- -----

2023-01-17 00:00:35,603:DEBUG:logic:main.py:456:getModel:726423: df_s.iloc[-5:,:] :
          date closeTime     open  ...    alpha58   alpha67   alpha72
5802  20230116    212959  20793.1  ...  55.000000  0.522028  0.577875
5803  20230116    215959  20837.4  ...  55.000000  0.521821  0.588569
5804  20230116    222959  20836.3  ...  55.416667  0.528439  0.595491
5805  20230116    225959  20874.3  ...  55.000000  0.526177  0.602883
5806  20230116    232959  20862.8  ...  55.416667  0.532706  0.606154

[5 rows x 33 columns]
0.5294117647058824
acc is : 0.5294117647058824
2023-01-17 00:00:35,772:INFO:logic:main.py:461:getModel:726423: df_pred.iloc[-5:,:] :
     pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
539     0  0.504053  0.495947       0  ...  1.081866  -1.0    0.0  1.239076
540     1  0.499830  0.500170       1  ...  1.079888  -1.0    0.0  1.241342
541     0  0.510509  0.489491       0  ...  1.080488  -1.0    0.0  1.240652
542     1  0.498443  0.501557       1  ...  1.078567  -1.0    0.0  1.242858
543     0  0.516141  0.483859       1  ...  1.073370  -1.0    0.0  1.248846

[5 rows x 10 columns]
2023-01-17 00:00:35,810:INFO:logic:main.py:471:getModel:726423: df_panel.iloc[-5:,:] :
    pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
45     0  0.504243  0.495757       0  ...  1.081866  -1.0    0.0  1.239142
46     1  0.499828  0.500172       1  ...  1.079888  -1.0    0.0  1.241748
47     0  0.510511  0.489489       0  ...  1.080488  -1.0    0.0  1.241058
48     1  0.498403  0.501597       1  ...  1.078567  -1.0    0.0  1.245027
49     0  0.516141  0.483859       1  ...  1.073370  -1.0    0.0  1.248846

[5 rows x 10 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': []}


## /root/FIL/strategy/modifiedmom/log.txt ----- -----

2023-01-17 00:00:01,449:INFO:modifiedmom:main.py:145:handleKline:185213: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
571  20230116   231000    231959  1673882399    20821  20797.4 -0.001133
572  20230116   232000    232959  1673882999  20797.5  20899.9  0.004929
573  20230116   233000    233959  1673883599  20899.3  20952.5  0.002517
574  20230116   234000    234959  1673884199  20950.3  21016.8  0.003069
575  20230116   235000    235959  1673884799    21016  21000.6 -0.000771
2023-01-17 00:00:01,450:INFO:modifiedmom:main.py:146:handleKline:185213: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True}
closeBuy: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '44.18', 'enterprice': '21068.4', 'countrevence': '0', 'unrealprofit': '-3024.2025023804', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '20999.94815522', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
2023-01-17 00:00:02,058:INFO:modifiedmom:main.py:267:closeBuy:185213: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False}
2023-01-17 00:00:02,058:INFO:modifiedmom:main.py:268:closeBuy:185213: ret = self.client.insertMarketUOrder("simulator",  BTCUSDT, 44.18, sell ), ret=InsertOrderReturn{'result': 'success', 'clientorderid': '41535F1673884802056I0L59'}
2023-01-17 00:00:02,074:INFO:modifiedmom:main.py:206:insertFactor:185213: curDateTime:1170000, name:modifiedmom, symbol:BTCUSDT, tradeDate:20230116, closeTime:235959, close:21000.6, total:929871.110088, mom:0.0008611669385143461, thd:0.0, side:sell 
2023-01-17 00:00:02,271:INFO:modifiedmom:main.py:316:handleOrderNew:185213: handleOrderNew: data=OrderType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'clientorderid': '41535F1673884802056I0L59', 'symbol': 'BTCUSDT', 'gatewayorderid': 1673884802233906, 'quantity': '44.18', 'price': '21000.2', 'stopprice': '0', 'ordertype': '', 'side': 'SELL', 'status': 'FILLED', 'positionside': 'SHORT', 'createtime': 1673884801652, 'updatetime': 1673884802233, 'tradetype': 'usdt', 'selfid': 41535, 'filltrades': [TradeType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'tradeid': 1673884802233, 'clientorderid': '41535F1673884802056I0L59', 'price': '21000.2', 'quantity': '44.18', 'commission': '927.788836', 'commissionasset': 'USDT', 'tradetime': 1673884802233, 'tradetype': 'usdt', 'gatetype': 'simulator', 'handletime': 1673884802233}], 'gatetype': 'simulator', 'handletime': 0}
127.0.0.1 - - [17/Jan/2023 00:00:02] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [17/Jan/2023 00:00:02] "POST / HTTP/1.1" 200 -
2023-01-17 00:00:02,493:INFO:modifiedmom:main.py:319:handleOrderFilled:185213: handleOrderFilled: data=OrderType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'clientorderid': '41535F1673884802056I0L59', 'symbol': 'BTCUSDT', 'gatewayorderid': 1673884802233906, 'quantity': '44.18', 'price': '21000.2', 'stopprice': '0', 'ordertype': '', 'side': 'SELL', 'status': 'FILLED', 'positionside': 'SHORT', 'createtime': 1673884801652, 'updatetime': 1673884802233, 'tradetype': 'usdt', 'selfid': 41535, 'filltrades': [TradeType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'tradeid': 1673884802233, 'clientorderid': '41535F1673884802056I0L59', 'price': '21000.2', 'quantity': '44.18', 'commission': '927.788836', 'commissionasset': 'USDT', 'tradetime': 1673884802233, 'tradetype': 'usdt', 'gatetype': 'simulator', 'handletime': 1673884802233}], 'gatetype': 'simulator', 'handletime': 0}

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=7544 

self.closeSec=1673885399, self.tradeDate='20230117', self.openTime='000000', self.closeTime='000959', self.symbol='BTCUSDT', self.open='21000.6', self.close='20976.1'
2023-01-17 00:10:01,523:INFO:modifiedmom:main.py:144:handleKline:185213: self.closeSec=1673885399, self.tradeDate='20230117', self.openTime='000000', self.closeTime='000959',self.symbol='BTCUSDT',self.open='21000.6', self.close='20976.1'
127.0.0.1 - - [17/Jan/2023 00:10:01] "POST / HTTP/1.1" 200 -
2023-01-17 00:10:01,539:INFO:modifiedmom:main.py:145:handleKline:185213: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
572  20230116   232000    232959  1673882999  20797.5  20899.9  0.004929
573  20230116   233000    233959  1673883599  20899.3  20952.5  0.002517
574  20230116   234000    234959  1673884199  20950.3  21016.8  0.003069
575  20230116   235000    235959  1673884799    21016  21000.6 -0.000771
576  20230117   000000    000959  1673885399  21000.6  20976.1 -0.001167
2023-01-17 00:10:01,542:INFO:modifiedmom:main.py:146:handleKline:185213: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False}


## /root/FIL/strategy/pyemd/log.txt ----- -----

2023-01-16 23:50:00,598:INFO:pyemd2:main.py:127:handleKline:185189: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=7544 

self.closeSec=1673884799, self.tradeDate='20230116', self.openTime='235000', self.closeTime='235959', self.symbol='BTCUSDT', self.open='21016', self.close='21000.6'
127.0.0.1 - - [17/Jan/2023 00:00:01] "POST / HTTP/1.1" 200 -
2023-01-17 00:00:01,443:INFO:pyemd2:main.py:125:handleKline:185189: self.closeSec=1673884799, self.tradeDate='20230116', self.openTime='235000', self.closeTime='235959',self.symbol='BTCUSDT',self.open='21016', self.close='21000.6'
2023-01-17 00:00:01,456:INFO:pyemd2:main.py:126:handleKline:185189: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17419  20230116   231000    231959  1673882399    20821  20797.4
17420  20230116   232000    232959  1673882999  20797.5  20899.9
17421  20230116   233000    233959  1673883599  20899.3  20952.5
17422  20230116   234000    234959  1673884199  20950.3  21016.8
17423  20230116   235000    235959  1673884799    21016  21000.6
2023-01-17 00:00:01,457:INFO:pyemd2:main.py:127:handleKline:185189: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}
2023-01-17 00:00:01,588:INFO:pyemd2:main.py:190:insertFactor:185189: curDateTime:1170000, name:pyemd2, symbol:BTCUSDT, tradeDate:20230116, closeTime:235959, close:21000.6, total:951537.2948681, pct_pre:-0.005142652500895295, thd:0.3143083914651598, side:sell 
127.0.0.1 - - [17/Jan/2023 00:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=7545 

self.closeSec=1673885399, self.tradeDate='20230117', self.openTime='000000', self.closeTime='000959', self.symbol='BTCUSDT', self.open='21000.6', self.close='20976.1'
2023-01-17 00:10:01,558:INFO:pyemd2:main.py:125:handleKline:185189: self.closeSec=1673885399, self.tradeDate='20230117', self.openTime='000000', self.closeTime='000959',self.symbol='BTCUSDT',self.open='21000.6', self.close='20976.1'
2023-01-17 00:10:01,592:INFO:pyemd2:main.py:126:handleKline:185189: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17420  20230116   232000    232959  1673882999  20797.5  20899.9
17421  20230116   233000    233959  1673883599  20899.3  20952.5
17422  20230116   234000    234959  1673884199  20950.3  21016.8
17423  20230116   235000    235959  1673884799    21016  21000.6
17424  20230117   000000    000959  1673885399  21000.6  20976.1
2023-01-17 00:10:01,592:INFO:pyemd2:main.py:127:handleKline:185189: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}


## /root/FIL/strategy/similarity/log.txt ----- -----

2023-01-17 00:00:01,513:INFO:testStrategy:main.py:102:handleKline:185174: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12235  20230116   231000    231959  1673882399    20821  20797.4
12236  20230116   232000    232959  1673882999  20797.5  20899.9
12237  20230116   233000    233959  1673883599  20899.3  20952.5
12238  20230116   234000    234959  1673884199  20950.3  21016.8
12239  20230116   235000    235959  1673884799    21016  21000.6
2023-01-17 00:00:01,516:INFO:testStrategy:main.py:103:handleKline:185174: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': True, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}
closeSell: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '54.063', 'enterprice': '20932.1', 'countrevence': '0', 'unrealprofit': '-3668.07481565886', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '20999.94815522', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
2023-01-17 00:00:02,072:INFO:testStrategy:main.py:253:closeSell:185174: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False, 'isCorr': False}
2023-01-17 00:00:02,073:INFO:testStrategy:main.py:254:closeSell:185174: ret = self.client.insertMarketUOrder("simulator",  BTCUSDT, 54.063, buy ), ret=InsertOrderReturn{'result': 'success', 'clientorderid': '41536F1673884802072I0L2'}
2023-01-17 00:00:02,089:INFO:testStrategy:main.py:172:insertFactor:185174: curDateTime:1170000, name:testStrategy, symbol:BTCUSDT, tradeDate:20230116, closeTime:235959, close:21000.6, total:1130520.4701777, corrDate:20221116, corrVal:0.5285733542967854, side:buy 
2023-01-17 00:00:02,490:INFO:testStrategy:main.py:305:handleOrderNew:185174: handleOrderNew: data=OrderType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'clientorderid': '41536F1673884802072I0L2', 'symbol': 'BTCUSDT', 'gatewayorderid': 1673884802234519, 'quantity': '54.063', 'price': '21000.3', 'stopprice': '0', 'ordertype': '', 'side': 'BUY', 'status': 'FILLED', 'positionside': 'LONG', 'createtime': 1673884801699, 'updatetime': 1673884802234, 'tradetype': 'usdt', 'selfid': 41536, 'filltrades': [TradeType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'tradeid': 1673884802234, 'clientorderid': '41536F1673884802072I0L2', 'price': '21000.3', 'quantity': '54.063', 'commission': '1135.3392189', 'commissionasset': 'USDT', 'tradetime': 1673884802234, 'tradetype': 'usdt', 'gatetype': 'simulator', 'handletime': 1673884802234}], 'gatetype': 'simulator', 'handletime': 0}
127.0.0.1 - - [17/Jan/2023 00:00:02] "POST / HTTP/1.1" 200 -
2023-01-17 00:00:02,717:INFO:testStrategy:main.py:308:handleOrderFilled:185174: handleOrderFilled: data=OrderType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'clientorderid': '41536F1673884802072I0L2', 'symbol': 'BTCUSDT', 'gatewayorderid': 1673884802234519, 'quantity': '54.063', 'price': '21000.3', 'stopprice': '0', 'ordertype': '', 'side': 'BUY', 'status': 'FILLED', 'positionside': 'LONG', 'createtime': 1673884801699, 'updatetime': 1673884802234, 'tradetype': 'usdt', 'selfid': 41536, 'filltrades': [TradeType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'tradeid': 1673884802234, 'clientorderid': '41536F1673884802072I0L2', 'price': '21000.3', 'quantity': '54.063', 'commission': '1135.3392189', 'commissionasset': 'USDT', 'tradetime': 1673884802234, 'tradetype': 'usdt', 'gatetype': 'simulator', 'handletime': 1673884802234}], 'gatetype': 'simulator', 'handletime': 0}
127.0.0.1 - - [17/Jan/2023 00:00:02] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=7545 

self.closeSec=1673885399, self.tradeDate='20230117', self.openTime='000000', self.closeTime='000959', self.symbol='BTCUSDT', self.open='21000.6', self.close='20976.1'
2023-01-17 00:10:01,565:INFO:testStrategy:main.py:101:handleKline:185174: self.closeSec=1673885399, self.tradeDate='20230117', self.openTime='000000', self.closeTime='000959',self.symbol='BTCUSDT',self.open='21000.6', self.close='20976.1'
127.0.0.1 - - [17/Jan/2023 00:10:01] "POST / HTTP/1.1" 200 -
2023-01-17 00:10:01,606:INFO:testStrategy:main.py:102:handleKline:185174: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12236  20230116   232000    232959  1673882999  20797.5  20899.9
12237  20230116   233000    233959  1673883599  20899.3  20952.5
12238  20230116   234000    234959  1673884199  20950.3  21016.8
12239  20230116   235000    235959  1673884799    21016  21000.6
12240  20230117   000000    000959  1673885399  21000.6  20976.1
2023-01-17 00:10:01,607:INFO:testStrategy:main.py:103:handleKline:185174: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False, 'isCorr': False}


## /root/FIL/strategy/sr_min/log.txt ----- -----

127.0.0.1 - - [17/Jan/2023 00:10:01] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=0, self.total=1000000.0, self.flagDict['side']='', self.tradeCount=0, self.count=10520
self.closeSec=1673885399, self.tradeDate='20230117', self.openTime='000500', self.closeTime='000959', self.symbol='BTCUSDT', self.open=20970.9, self.close=20976.1, self.high=20991.6, self.low=20953.2, self.vol=1992.206, self.amt=41776301.3363 
2023-01-17 00:10:01,535:INFO:sr_min:main.py:172:handleKline:449472: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5757  20230116   234500    234959  ...         0.0        0.0       0
5758  20230116   235000    235459  ...         0.0        0.0       0
5759  20230116   235500    235959  ...         0.0        0.0       0
5760  20230117   000000    000459  ...         0.0        0.0       0
5761  20230117   000500    000959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-01-17 00:10:01,535:INFO:sr_min:main.py:175:handleKline:449472: self.closeSec=1673885399, self.tradeDate='20230117', self.openTime='000500', self.closeTime='000959',self.symbol='BTCUSDT',self.open=20970.9, self.close=20976.1, self.high=20991.6, self.low=20953.2, self.vol=1992.206, self.amt=41776301.3363, ukdf['pct'].iloc[-1]=0.000463 , ukdf['amount'].iloc[-1]=41776301.3363, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5761, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': []}
type(curSign)=<class 'int'>, curSign=0, self.sign=0
127.0.0.1 - - [17/Jan/2023 00:15:00] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=0, self.total=1000000.0, self.flagDict['side']='', self.tradeCount=0, self.count=10521
self.closeSec=1673885699, self.tradeDate='20230117', self.openTime='001000', self.closeTime='001459', self.symbol='BTCUSDT', self.open=20976.2, self.close=21039.1, self.high=21044.7, self.low=20972.7, self.vol=3129.06, self.amt=65753146.8564 
2023-01-17 00:15:00,932:INFO:sr_min:main.py:172:handleKline:449472: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5758  20230116   235000    235459  ...         0.0        0.0       0
5759  20230116   235500    235959  ...         0.0        0.0       0
5760  20230117   000000    000459  ...         0.0        0.0       0
5761  20230117   000500    000959  ...         0.0        0.0       0
5762  20230117   001000    001459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-01-17 00:15:00,933:INFO:sr_min:main.py:175:handleKline:449472: self.closeSec=1673885699, self.tradeDate='20230117', self.openTime='001000', self.closeTime='001459',self.symbol='BTCUSDT',self.open=20976.2, self.close=21039.1, self.high=21044.7, self.low=20972.7, self.vol=3129.06, self.amt=65753146.8564, ukdf['pct'].iloc[-1]=0.003003 , ukdf['amount'].iloc[-1]=65753146.8564, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5762, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': []}
type(curSign)=<class 'int'>, curSign=0, self.sign=0


## /root/FIL/strategy/s_rsrs/log.txt ----- -----

723  20230116   120000    155959  1673855999  ...    723  0.902588  0.320094     NaN
724  20230116   160000    195959  1673870399  ...    724  0.867218  0.219553     NaN

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '51.136', 'enterprice': '17188.2', 'countrevence': '0', 'unrealprofit': '185737.1581296864', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '20820.41914365', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-9223372036854775808, self.sign=1
--handleKline--:  version='2.0.0', self.name='s_rsrs', self.symbol='BTCUSDT', interval='4h', intervalSec=14400, wid=25, thd=0.6, self.sign=1, self.total=878056.8594048, self.flagDict['side']='buy', self.tradeCount=12, self.count=314
self.closeSec=1673884799, self.tradeDate='20230116', self.openTime='200000', self.closeTime='235959', self.symbol='BTCUSDT', self.open=20821.8, self.close=21000.6, self.high=21079.9, self.low=20606.6, self.vol=114395.111, self.amt=2386427403.62526 
127.0.0.1 - - [17/Jan/2023 00:00:01] "POST / HTTP/1.1" 200 -
2023-01-17 00:00:01,312:INFO:s_rsrs:main.py:141:handleKline:185271: self.closeSec=1673884799, self.tradeDate='20230116', self.openTime='200000', self.closeTime='235959',self.symbol='BTCUSDT',self.open=20821.8, self.close=21000.6, self.high=21079.9, self.low=20606.6, self.vol=114395.111, self.amt=2386427403.62526 
2023-01-17 00:00:01,334:INFO:s_rsrs:main.py:142:handleKline:185271: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime  ...         vol           amt       pct
721  20230116   040000    075959  ...   44695.035  9.332903e+08  0.000263
722  20230116   080000    115959  ...  175271.412  3.707107e+09  0.009654
723  20230116   120000    155959  ...   55958.606  1.183353e+09  0.001503
724  20230116   160000    195959  ...  101732.641  2.117565e+09 -0.013937
725  20230116   200000    235959  ...  114395.111  2.386427e+09  0.008592

[5 rows x 11 columns]
2023-01-17 00:00:03,498:INFO:s_rsrs:main.py:151:handleKline:185271: df_s.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec  ...  index      beta    zscore  signal
721  20230116   040000    075959  1673827199  ...    721  0.901201  0.351053     NaN
722  20230116   080000    115959  1673841599  ...    722  0.919980  0.377256     NaN
723  20230116   120000    155959  1673855999  ...    723  0.902588  0.320094     NaN
724  20230116   160000    195959  1673870399  ...    724  0.867218  0.219553     NaN
725  20230116   200000    235959  1673884799  ...    725  0.815950  0.078361     NaN

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '51.136', 'enterprice': '17188.2', 'countrevence': '0', 'unrealprofit': '194930.432', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '21000.2', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-9223372036854775808, self.sign=1


