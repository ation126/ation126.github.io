# 20230306 00:26:02

## /root/FIL/strategy/amihud/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=993672.4896432, self.flagDict['side']='sell', self.tradeCount=2, self.count=28348
self.closeSec=1678033199, self.tradeDate='20230306', self.openTime='001500', self.closeTime='001959', self.symbol='BTCUSDT', self.open=22421.6, self.close=22415.7, self.high=22428.3, self.low=22415.7, self.vol=356.899, self.amt=8002556.1063 
127.0.0.1 - - [06/Mar/2023 00:20:01] "POST / HTTP/1.1" 200 -
2023-03-06 00:20:01,595:INFO:amihud:main.py:172:handleKline:200676: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5759  20230305   235500    235959  ...         0.0        0.0       0
5760  20230306   000000    000459  ...         0.0        0.0       0
5761  20230306   000500    000959  ...         0.0        0.0       0
5762  20230306   001000    001459  ...         0.0        0.0       0
5763  20230306   001500    001959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-03-06 00:20:01,601:INFO:amihud:main.py:175:handleKline:200676: self.closeSec=1678033199, self.tradeDate='20230306', self.openTime='001500', self.closeTime='001959',self.symbol='BTCUSDT',self.open=22421.6, self.close=22415.7, self.high=22428.3, self.low=22415.7, self.vol=356.899, self.amt=8002556.1063, ukdf['pct'].iloc[-1]=-0.000263 , ukdf['amount'].iloc[-1]=8002556.1063, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5763, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '60.176', 'enterprice': '16529.3', 'countrevence': '0', 'unrealprofit': '-354276.8359765344', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '22416.6443894', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1
--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=993672.4896432, self.flagDict['side']='sell', self.tradeCount=2, self.count=28349
self.closeSec=1678033499, self.tradeDate='20230306', self.openTime='002000', self.closeTime='002459', self.symbol='BTCUSDT', self.open=22415.8, self.close=22426.9, self.high=22426.9, self.low=22415.1, self.vol=366.54, self.amt=8217285.8215 
127.0.0.1 - - [06/Mar/2023 00:25:01] "POST / HTTP/1.1" 200 -
2023-03-06 00:25:01,607:INFO:amihud:main.py:172:handleKline:200676: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5760  20230306   000000    000459  ...         0.0        0.0       0
5761  20230306   000500    000959  ...         0.0        0.0       0
5762  20230306   001000    001459  ...         0.0        0.0       0
5763  20230306   001500    001959  ...         0.0        0.0       0
5764  20230306   002000    002459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-03-06 00:25:01,607:INFO:amihud:main.py:175:handleKline:200676: self.closeSec=1678033499, self.tradeDate='20230306', self.openTime='002000', self.closeTime='002459',self.symbol='BTCUSDT',self.open=22415.8, self.close=22426.9, self.high=22426.9, self.low=22415.1, self.vol=366.54, self.amt=8217285.8215, ukdf['pct'].iloc[-1]=0.0005 , ukdf['amount'].iloc[-1]=8217285.8215, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5764, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '60.176', 'enterprice': '16529.3', 'countrevence': '0', 'unrealprofit': '-354887.96', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '22426.8', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1


## /root/FIL/strategy/factorcheck/log.txt ----- -----


self.closeSec=1678033199, self.tradeDate='20230306', self.openTime='001500', self.closeTime='001959', self.symbol='BTCUSDT', self.open=22421.6, self.close=22415.7, self.high=22428.3, self.low=22415.7 
127.0.0.1 - - [06/Mar/2023 00:20:01] "POST / HTTP/1.1" 200 -
2023-03-06 00:20:01,500:INFO:factorcheck2:main.py:126:handleKline:185239: self.closeSec=1678033199, self.tradeDate='20230306', self.openTime='001500', self.closeTime='001959',self.symbol='BTCUSDT',self.open=22421.6, self.close=22415.7, self.high=22428.3, self.low=22415.7   
2023-03-06 00:20:01,559:INFO:factorcheck2:main.py:127:handleKline:185239: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1439  20230305   235500    235959  1678031999  ...  22424.1 -0.000192   1727    5
1440  20230306   000000    000459  1678032299  ...  22423.9  0.000223   1440    0
1441  20230306   000500    000959  1678032599  ...  22421.9 -0.000241   1441    1
1442  20230306   001000    001459  1678032899  ...  22421.2 -0.000107   1442    2
1443  20230306   001500    001959  1678033199  ...  22415.7 -0.000263   1443    3

[5 rows x 11 columns]
2023-03-06 00:20:01,562:INFO:factorcheck2:main.py:128:handleKline:185239: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}
127.0.0.1 - - [06/Mar/2023 00:25:01] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=20, self.factor=0.48578526370472624, self.count=28915 

self.closeSec=1678033499, self.tradeDate='20230306', self.openTime='002000', self.closeTime='002459', self.symbol='BTCUSDT', self.open=22415.8, self.close=22426.9, self.high=22426.9, self.low=22415.1 
2023-03-06 00:25:01,501:INFO:factorcheck2:main.py:126:handleKline:185239: self.closeSec=1678033499, self.tradeDate='20230306', self.openTime='002000', self.closeTime='002459',self.symbol='BTCUSDT',self.open=22415.8, self.close=22426.9, self.high=22426.9, self.low=22415.1   
2023-03-06 00:25:01,580:INFO:factorcheck2:main.py:127:handleKline:185239: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1440  20230306   000000    000459  1678032299  ...  22423.9  0.000223   1440    0
1441  20230306   000500    000959  1678032599  ...  22421.9 -0.000241   1441    1
1442  20230306   001000    001459  1678032899  ...  22421.2 -0.000107   1442    2
1443  20230306   001500    001959  1678033199  ...  22415.7 -0.000263   1443    3
1444  20230306   002000    002459  1678033499  ...  22415.1  0.000500   1444    4

[5 rows x 11 columns]
2023-03-06 00:25:01,580:INFO:factorcheck2:main.py:128:handleKline:185239: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}


## /root/FIL/strategy/logic/log.txt ----- -----

2023-03-06 00:00:39,313:DEBUG:logic:main.py:463:getModel:885513: df_s.iloc[-5:,:] :
          date closeTime     open  ...    alpha58   alpha67   alpha72
5802  20230305    212959  22410.2  ...  47.083333  0.489386  0.492798
5803  20230305    215959  22423.0  ...  47.500000  0.500903  0.485828
5804  20230305    222959  22454.9  ...  47.500000  0.494905  0.481553
5805  20230305    225959  22438.1  ...  47.083333  0.488438  0.479976
5806  20230305    232959  22419.9  ...  47.083333  0.498432  0.474897

[5 rows x 33 columns]
0.5422794117647058
acc is : 0.5422794117647058
2023-03-06 00:00:39,504:INFO:logic:main.py:468:getModel:885513: df_pred.iloc[-5:,:] :
     pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
539     0  0.511428  0.488572       1  ...  0.938263  -1.0    0.0  0.933303
540     0  0.523323  0.476677       0  ...  0.938965  -1.0    0.0  0.932605
541     0  0.506282  0.493718       0  ...  0.939727  -1.0    0.0  0.931848
542     0  0.502692  0.497308       1  ...  0.938587  -1.0    0.0  0.932979
543     0  0.518478  0.481522       0  ...  0.939536  -1.0    0.0  0.932035

[5 rows x 10 columns]
2023-03-06 00:00:39,544:INFO:logic:main.py:478:getModel:885513: df_panel.iloc[-5:,:] :
    pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
45     0  0.511798  0.488202       1  ...  0.898423  -1.0    0.0  0.934134
46     0  0.523929  0.476071       0  ...  0.899095  -1.0    0.0  0.936947
47     0  0.506887  0.493113       0  ...  0.899824  -1.0    0.0  0.936187
48     0  0.502991  0.497009       1  ...  0.898733  -1.0    0.0  0.936076
49     0  0.518478  0.481522       0  ...  0.939536  -1.0    0.0  0.932035

[5 rows x 10 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '31.887', 'enterprice': '22396.9', 'countrevence': '0', 'unrealprofit': '-984.90619982808', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '22427.78738984', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}


## /root/FIL/strategy/modifiedmom/log.txt ----- -----

2023-03-06 00:00:03,207:INFO:modifiedmom:main.py:319:handleOrderFilled:185213: handleOrderFilled: data=OrderType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'clientorderid': '41892F1678032002779I0L59', 'symbol': 'BTCUSDT', 'gatewayorderid': 1678032002885455, 'quantity': '46.07', 'price': '22424.5', 'stopprice': '0', 'ordertype': '', 'side': 'BUY', 'status': 'FILLED', 'positionside': 'LONG', 'createtime': 1678032002256, 'updatetime': 1678032002885, 'tradetype': 'usdt', 'selfid': 41892, 'filltrades': [TradeType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'tradeid': 1678032002885, 'clientorderid': '41892F1678032002779I0L59', 'price': '22424.5', 'quantity': '46.07', 'commission': '1033.096715', 'commissionasset': 'USDT', 'tradetime': 1678032002885, 'tradetype': 'usdt', 'gatetype': 'simulator', 'handletime': 1678032002885}], 'gatetype': 'simulator', 'handletime': 0}
127.0.0.1 - - [06/Mar/2023 00:00:03] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=14456 

self.closeSec=1678032599, self.tradeDate='20230306', self.openTime='000000', self.closeTime='000959', self.symbol='BTCUSDT', self.open='22424.5', self.close='22424'
2023-03-06 00:10:01,660:INFO:modifiedmom:main.py:144:handleKline:185213: self.closeSec=1678032599, self.tradeDate='20230306', self.openTime='000000', self.closeTime='000959',self.symbol='BTCUSDT',self.open='22424.5', self.close='22424'
127.0.0.1 - - [06/Mar/2023 00:10:01] "POST / HTTP/1.1" 200 -
2023-03-06 00:10:01,683:INFO:modifiedmom:main.py:145:handleKline:185213: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
572  20230305   232000    232959  1678030199  22434.6  22447.1  0.000557
573  20230305   233000    233959  1678030799  22447.1  22442.1 -0.000223
574  20230305   234000    234959  1678031399    22442    22429 -0.000584
575  20230305   235000    235959  1678031999  22428.9  22424.4 -0.000205
576  20230306   000000    000959  1678032599  22424.5    22424 -0.000018
2023-03-06 00:10:01,685:INFO:modifiedmom:main.py:146:handleKline:185213: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False}
127.0.0.1 - - [06/Mar/2023 00:20:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=14457 

self.closeSec=1678033199, self.tradeDate='20230306', self.openTime='001000', self.closeTime='001959', self.symbol='BTCUSDT', self.open='22424', self.close='22415.7'
2023-03-06 00:20:01,628:INFO:modifiedmom:main.py:144:handleKline:185213: self.closeSec=1678033199, self.tradeDate='20230306', self.openTime='001000', self.closeTime='001959',self.symbol='BTCUSDT',self.open='22424', self.close='22415.7'
2023-03-06 00:20:01,672:INFO:modifiedmom:main.py:145:handleKline:185213: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
573  20230305   233000    233959  1678030799  22447.1  22442.1 -0.000223
574  20230305   234000    234959  1678031399    22442    22429 -0.000584
575  20230305   235000    235959  1678031999  22428.9  22424.4 -0.000205
576  20230306   000000    000959  1678032599  22424.5    22424 -0.000018
577  20230306   001000    001959  1678033199    22424  22415.7 -0.000370
2023-03-06 00:20:01,672:INFO:modifiedmom:main.py:146:handleKline:185213: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False}


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

2023-03-06 00:00:03,771:INFO:pyemd2:main.py:303:handleOrderFilled:185189: handleOrderFilled: data=OrderType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'clientorderid': '41894F1678032002908I0L57', 'symbol': 'BTCUSDT', 'gatewayorderid': 1678032003435264, 'quantity': '43.883', 'price': '22424.4', 'stopprice': '0', 'ordertype': '', 'side': 'SELL', 'status': 'FILLED', 'positionside': 'SHORT', 'createtime': 1678032002344, 'updatetime': 1678032003435, 'tradetype': 'usdt', 'selfid': 41894, 'filltrades': [TradeType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'tradeid': 1678032003435, 'clientorderid': '41894F1678032002908I0L57', 'price': '22424.4', 'quantity': '43.883', 'commission': '984.0499452', 'commissionasset': 'USDT', 'tradetime': 1678032003435, 'tradetype': 'usdt', 'gatetype': 'simulator', 'handletime': 1678032003435}], 'gatetype': 'simulator', 'handletime': 0}
127.0.0.1 - - [06/Mar/2023 00:00:03] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=14457 

self.closeSec=1678032599, self.tradeDate='20230306', self.openTime='000000', self.closeTime='000959', self.symbol='BTCUSDT', self.open='22424.5', self.close='22424'
2023-03-06 00:10:01,645:INFO:pyemd2:main.py:125:handleKline:185189: self.closeSec=1678032599, self.tradeDate='20230306', self.openTime='000000', self.closeTime='000959',self.symbol='BTCUSDT',self.open='22424.5', self.close='22424'
127.0.0.1 - - [06/Mar/2023 00:10:01] "POST / HTTP/1.1" 200 -
2023-03-06 00:10:01,709:INFO:pyemd2:main.py:126:handleKline:185189: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17420  20230305   232000    232959  1678030199  22434.6  22447.1
17421  20230305   233000    233959  1678030799  22447.1  22442.1
17422  20230305   234000    234959  1678031399    22442    22429
17423  20230305   235000    235959  1678031999  22428.9  22424.4
17424  20230306   000000    000959  1678032599  22424.5    22424
2023-03-06 00:10:01,709:INFO:pyemd2:main.py:127:handleKline:185189: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}
127.0.0.1 - - [06/Mar/2023 00:20:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=14458 

self.closeSec=1678033199, self.tradeDate='20230306', self.openTime='001000', self.closeTime='001959', self.symbol='BTCUSDT', self.open='22424', self.close='22415.7'
2023-03-06 00:20:01,668:INFO:pyemd2:main.py:125:handleKline:185189: self.closeSec=1678033199, self.tradeDate='20230306', self.openTime='001000', self.closeTime='001959',self.symbol='BTCUSDT',self.open='22424', self.close='22415.7'
2023-03-06 00:20:01,703:INFO:pyemd2:main.py:126:handleKline:185189: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17421  20230305   233000    233959  1678030799  22447.1  22442.1
17422  20230305   234000    234959  1678031399    22442    22429
17423  20230305   235000    235959  1678031999  22428.9  22424.4
17424  20230306   000000    000959  1678032599  22424.5    22424
17425  20230306   001000    001959  1678033199    22424  22415.7
2023-03-06 00:20:01,703:INFO:pyemd2:main.py:127:handleKline:185189: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}


## /root/FIL/strategy/similarity/log.txt ----- -----

127.0.0.1 - - [06/Mar/2023 00:00:03] "POST / HTTP/1.1" 200 -
2023-03-06 00:00:03,468:INFO:testStrategy:main.py:308:handleOrderFilled:185174: handleOrderFilled: data=OrderType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'clientorderid': '41893F1678032002856I0L2', 'symbol': 'BTCUSDT', 'gatewayorderid': 1678032002969002, 'quantity': '52.709', 'price': '22424.4', 'stopprice': '0', 'ordertype': '', 'side': 'SELL', 'status': 'FILLED', 'positionside': 'SHORT', 'createtime': 1678032002372, 'updatetime': 1678032002969, 'tradetype': 'usdt', 'selfid': 41893, 'filltrades': [TradeType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'tradeid': 1678032002969, 'clientorderid': '41893F1678032002856I0L2', 'price': '22424.4', 'quantity': '52.709', 'commission': '1181.9676996', 'commissionasset': 'USDT', 'tradetime': 1678032002969, 'tradetype': 'usdt', 'gatetype': 'simulator', 'handletime': 1678032002969}], 'gatetype': 'simulator', 'handletime': 0}
127.0.0.1 - - [06/Mar/2023 00:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=14457 

self.closeSec=1678032599, self.tradeDate='20230306', self.openTime='000000', self.closeTime='000959', self.symbol='BTCUSDT', self.open='22424.5', self.close='22424'
2023-03-06 00:10:01,643:INFO:testStrategy:main.py:101:handleKline:185174: self.closeSec=1678032599, self.tradeDate='20230306', self.openTime='000000', self.closeTime='000959',self.symbol='BTCUSDT',self.open='22424.5', self.close='22424'
2023-03-06 00:10:01,701:INFO:testStrategy:main.py:102:handleKline:185174: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12236  20230305   232000    232959  1678030199  22434.6  22447.1
12237  20230305   233000    233959  1678030799  22447.1  22442.1
12238  20230305   234000    234959  1678031399    22442    22429
12239  20230305   235000    235959  1678031999  22428.9  22424.4
12240  20230306   000000    000959  1678032599  22424.5    22424
2023-03-06 00:10:01,701:INFO:testStrategy:main.py:103:handleKline:185174: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False, 'isCorr': False}
127.0.0.1 - - [06/Mar/2023 00:20:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=14458 

self.closeSec=1678033199, self.tradeDate='20230306', self.openTime='001000', self.closeTime='001959', self.symbol='BTCUSDT', self.open='22424', self.close='22415.7'
2023-03-06 00:20:01,657:INFO:testStrategy:main.py:101:handleKline:185174: self.closeSec=1678033199, self.tradeDate='20230306', self.openTime='001000', self.closeTime='001959',self.symbol='BTCUSDT',self.open='22424', self.close='22415.7'
2023-03-06 00:20:01,700:INFO:testStrategy:main.py:102:handleKline:185174: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12237  20230305   233000    233959  1678030799  22447.1  22442.1
12238  20230305   234000    234959  1678031399    22442    22429
12239  20230305   235000    235959  1678031999  22428.9  22424.4
12240  20230306   000000    000959  1678032599  22424.5    22424
12241  20230306   001000    001959  1678033199    22424  22415.7
2023-03-06 00:20:01,701:INFO:testStrategy:main.py:103:handleKline:185174: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False, 'isCorr': False}


## /root/FIL/strategy/sr_min/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=0, self.total=1000000.0, self.flagDict['side']='', self.tradeCount=0, self.count=24346
self.closeSec=1678033199, self.tradeDate='20230306', self.openTime='001500', self.closeTime='001959', self.symbol='BTCUSDT', self.open=22421.6, self.close=22415.7, self.high=22428.3, self.low=22415.7, self.vol=356.899, self.amt=8002556.1063 
127.0.0.1 - - [06/Mar/2023 00:20:01] "POST / HTTP/1.1" 200 -
2023-03-06 00:20:01,592:INFO:sr_min:main.py:172:handleKline:449472: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5759  20230305   235500    235959  ...         0.0        0.0       0
5760  20230306   000000    000459  ...         0.0        0.0       0
5761  20230306   000500    000959  ...         0.0        0.0       0
5762  20230306   001000    001459  ...         0.0        0.0       0
5763  20230306   001500    001959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-03-06 00:20:01,593:INFO:sr_min:main.py:175:handleKline:449472: self.closeSec=1678033199, self.tradeDate='20230306', self.openTime='001500', self.closeTime='001959',self.symbol='BTCUSDT',self.open=22421.6, self.close=22415.7, self.high=22428.3, self.low=22415.7, self.vol=356.899, self.amt=8002556.1063, ukdf['pct'].iloc[-1]=-0.000263 , ukdf['amount'].iloc[-1]=8002556.1063, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5763, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': []}
type(curSign)=<class 'int'>, curSign=0, self.sign=0
--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=0, self.total=1000000.0, self.flagDict['side']='', self.tradeCount=0, self.count=24347
self.closeSec=1678033499, self.tradeDate='20230306', self.openTime='002000', self.closeTime='002459', self.symbol='BTCUSDT', self.open=22415.8, self.close=22426.9, self.high=22426.9, self.low=22415.1, self.vol=366.54, self.amt=8217285.8215 
127.0.0.1 - - [06/Mar/2023 00:25:01] "POST / HTTP/1.1" 200 -
2023-03-06 00:25:01,605:INFO:sr_min:main.py:172:handleKline:449472: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5760  20230306   000000    000459  ...         0.0        0.0       0
5761  20230306   000500    000959  ...         0.0        0.0       0
5762  20230306   001000    001459  ...         0.0        0.0       0
5763  20230306   001500    001959  ...         0.0        0.0       0
5764  20230306   002000    002459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-03-06 00:25:01,605:INFO:sr_min:main.py:175:handleKline:449472: self.closeSec=1678033499, self.tradeDate='20230306', self.openTime='002000', self.closeTime='002459',self.symbol='BTCUSDT',self.open=22415.8, self.close=22426.9, self.high=22426.9, self.low=22415.1, self.vol=366.54, self.amt=8217285.8215, ukdf['pct'].iloc[-1]=0.0005 , ukdf['amount'].iloc[-1]=8217285.8215, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5764, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': []}
type(curSign)=<class 'int'>, curSign=0, self.sign=0


## /root/FIL/strategy/s_rsrs/log.txt ----- -----

723  20230305   120000    155959  1678003199  ...    723  0.723793  0.502248     NaN
724  20230305   160000    195959  1678017599  ...    724  0.704319  0.449658     NaN

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '42.135', 'enterprice': '23350.3', 'countrevence': '0', 'unrealprofit': '40699.08903095775', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '22384.37881735', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-9223372036854775808, self.sign=-1
127.0.0.1 - - [06/Mar/2023 00:00:01] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='s_rsrs', self.symbol='BTCUSDT', interval='4h', intervalSec=14400, wid=25, thd=0.6, self.sign=-1, self.total=982881.0256095, self.flagDict['side']='sell', self.tradeCount=23, self.count=602
self.closeSec=1678031999, self.tradeDate='20230305', self.openTime='200000', self.closeTime='235959', self.symbol='BTCUSDT', self.open=22380.1, self.close=22424.4, self.high=22480.0, self.low=22380.1, self.vol=32096.465, self.amt=719961063.652 
2023-03-06 00:00:01,926:INFO:s_rsrs:main.py:141:handleKline:185271: self.closeSec=1678031999, self.tradeDate='20230305', self.openTime='200000', self.closeTime='235959',self.symbol='BTCUSDT',self.open=22380.1, self.close=22424.4, self.high=22480.0, self.low=22380.1, self.vol=32096.465, self.amt=719961063.652 
2023-03-06 00:00:02,002:INFO:s_rsrs:main.py:142:handleKline:185271: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime  ...         vol           amt       pct
721  20230305   040000    075959  ...   51628.209  1.148461e+09  0.004366
722  20230305   080000    115959  ...  113479.717  2.546072e+09  0.001724
723  20230305   120000    155959  ...   30138.059  6.752701e+08 -0.000407
724  20230305   160000    195959  ...   31592.000  7.067840e+08  0.000671
725  20230305   200000    235959  ...   32096.465  7.199611e+08  0.001979

[5 rows x 11 columns]
2023-03-06 00:00:04,551:INFO:s_rsrs:main.py:151:handleKline:185271: df_s.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec  ...  index      beta    zscore  signal
721  20230305   040000    075959  1677974399  ...    721  0.733079  0.486015     NaN
722  20230305   080000    115959  1677988799  ...    722  0.717200  0.456806     NaN
723  20230305   120000    155959  1678003199  ...    723  0.723793  0.502248     NaN
724  20230305   160000    195959  1678017599  ...    724  0.704319  0.449658     NaN
725  20230305   200000    235959  1678031999  ...    725  0.664683  0.319818     NaN

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '42.135', 'enterprice': '23350.3', 'countrevence': '0', 'unrealprofit': '38947.95923826435', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '22425.93879819', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-9223372036854775808, self.sign=-1


