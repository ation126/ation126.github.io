# 20230308 00:26:02

## /root/FIL/strategy/amihud/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=993672.4896432, self.flagDict['side']='sell', self.tradeCount=2, self.count=28924
self.closeSec=1678205999, self.tradeDate='20230308', self.openTime='001500', self.closeTime='001959', self.symbol='BTCUSDT', self.open=22287.1, self.close=22296.6, self.high=22303.4, self.low=22261.5, self.vol=4506.315, self.amt=100416002.2763 
127.0.0.1 - - [08/Mar/2023 00:20:01] "POST / HTTP/1.1" 200 -
2023-03-08 00:20:03,534:INFO:amihud:main.py:172:handleKline:200676: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5759  20230307   235500    235959  ...         0.0        0.0       0
5760  20230308   000000    000459  ...         0.0        0.0       0
5761  20230308   000500    000959  ...         0.0        0.0       0
5762  20230308   001000    001459  ...         0.0        0.0       0
5763  20230308   001500    001959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-03-08 00:20:03,554:INFO:amihud:main.py:175:handleKline:200676: self.closeSec=1678205999, self.tradeDate='20230308', self.openTime='001500', self.closeTime='001959',self.symbol='BTCUSDT',self.open=22287.1, self.close=22296.6, self.high=22303.4, self.low=22261.5, self.vol=4506.315, self.amt=100416002.2763, ukdf['pct'].iloc[-1]=0.000426 , ukdf['amount'].iloc[-1]=100416002.2763, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5763, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '60.176', 'enterprice': '16529.3', 'countrevence': '0', 'unrealprofit': '-347209.5024', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '22299.2', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1
--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=993672.4896432, self.flagDict['side']='sell', self.tradeCount=2, self.count=28925
self.closeSec=1678206299, self.tradeDate='20230308', self.openTime='002000', self.closeTime='002459', self.symbol='BTCUSDT', self.open=22296.7, self.close=22284.6, self.high=22315.0, self.low=22280.3, self.vol=1851.05, self.amt=41274689.7832 
127.0.0.1 - - [08/Mar/2023 00:25:01] "POST / HTTP/1.1" 200 -
2023-03-08 00:25:01,757:INFO:amihud:main.py:172:handleKline:200676: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5760  20230308   000000    000459  ...         0.0        0.0       0
5761  20230308   000500    000959  ...         0.0        0.0       0
5762  20230308   001000    001459  ...         0.0        0.0       0
5763  20230308   001500    001959  ...         0.0        0.0       0
5764  20230308   002000    002459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-03-08 00:25:01,759:INFO:amihud:main.py:175:handleKline:200676: self.closeSec=1678206299, self.tradeDate='20230308', self.openTime='002000', self.closeTime='002459',self.symbol='BTCUSDT',self.open=22296.7, self.close=22284.6, self.high=22315.0, self.low=22280.3, self.vol=1851.05, self.amt=41274689.7832, ukdf['pct'].iloc[-1]=-0.000538 , ukdf['amount'].iloc[-1]=41274689.7832, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5764, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '60.176', 'enterprice': '16529.3', 'countrevence': '0', 'unrealprofit': '-346366.19424866496', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '22285.18597196', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1


## /root/FIL/strategy/factorcheck/log.txt ----- -----


self.closeSec=1678205999, self.tradeDate='20230308', self.openTime='001500', self.closeTime='001959', self.symbol='BTCUSDT', self.open=22287.1, self.close=22296.6, self.high=22303.4, self.low=22261.5 
127.0.0.1 - - [08/Mar/2023 00:20:01] "POST / HTTP/1.1" 200 -
2023-03-08 00:20:01,799:INFO:factorcheck2:main.py:126:handleKline:185239: self.closeSec=1678205999, self.tradeDate='20230308', self.openTime='001500', self.closeTime='001959',self.symbol='BTCUSDT',self.open=22287.1, self.close=22296.6, self.high=22303.4, self.low=22261.5   
2023-03-08 00:20:02,128:INFO:factorcheck2:main.py:127:handleKline:185239: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1439  20230307   235500    235959  1678204799  ...  22305.1 -0.000820   1727    5
1440  20230308   000000    000459  1678205099  ...  22301.0  0.002327   1440    0
1441  20230308   000500    000959  1678205399  ...  22325.0 -0.000568   1441    1
1442  20230308   001000    001459  1678205699  ...  22287.0 -0.002667   1442    2
1443  20230308   001500    001959  1678205999  ...  22261.5  0.000426   1443    3

[5 rows x 11 columns]
2023-03-08 00:20:02,129:INFO:factorcheck2:main.py:128:handleKline:185239: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': False, 'isOpen': True, 'isClose': False, 'isTrig': True}

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.6172293683033576, self.count=29491 

self.closeSec=1678206299, self.tradeDate='20230308', self.openTime='002000', self.closeTime='002459', self.symbol='BTCUSDT', self.open=22296.7, self.close=22284.6, self.high=22315.0, self.low=22280.3 
2023-03-08 00:25:01,644:INFO:factorcheck2:main.py:126:handleKline:185239: self.closeSec=1678206299, self.tradeDate='20230308', self.openTime='002000', self.closeTime='002459',self.symbol='BTCUSDT',self.open=22296.7, self.close=22284.6, self.high=22315.0, self.low=22280.3   
127.0.0.1 - - [08/Mar/2023 00:25:01] "POST / HTTP/1.1" 200 -
2023-03-08 00:25:01,685:INFO:factorcheck2:main.py:127:handleKline:185239: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1440  20230308   000000    000459  1678205099  ...  22301.0  0.002327   1440    0
1441  20230308   000500    000959  1678205399  ...  22325.0 -0.000568   1441    1
1442  20230308   001000    001459  1678205699  ...  22287.0 -0.002667   1442    2
1443  20230308   001500    001959  1678205999  ...  22261.5  0.000426   1443    3
1444  20230308   002000    002459  1678206299  ...  22280.3 -0.000538   1444    4

[5 rows x 11 columns]
2023-03-08 00:25:01,685:INFO:factorcheck2:main.py:128:handleKline:185239: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': False, 'isOpen': True, 'isClose': False, 'isTrig': True}


## /root/FIL/strategy/logic/log.txt ----- -----

2023-03-08 00:00:39,868:DEBUG:logic:main.py:463:getModel:885513: df_s.iloc[-5:,:] :
          date closeTime     open  ...    alpha58   alpha67   alpha72
5802  20230307    212959  22388.4  ...  45.000000  0.484055  0.638771
5803  20230307    215959  22382.5  ...  45.000000  0.471150  0.649746
5804  20230307    222959  22351.8  ...  45.000000  0.463712  0.656154
5805  20230307    225959  22323.1  ...  44.583333  0.448698  0.658282
5806  20230307    232959  22296.1  ...  44.166667  0.414127  0.650627

[5 rows x 33 columns]
0.5477941176470589
acc is : 0.5477941176470589
2023-03-08 00:00:40,093:INFO:logic:main.py:468:getModel:885513: df_pred.iloc[-5:,:] :
     pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
539     0  0.507819  0.492181       0  ...  0.928942  -1.0    0.0  0.938304
540     1  0.491362  0.508638       0  ...  0.929694  -1.0    0.0  0.937544
541     1  0.499026  0.500974       0  ...  0.931259  -1.0    0.0  0.935965
542     1  0.482899  0.517101       0  ...  0.935227  -1.0    0.0  0.931977
543     1  0.440382  0.559618       1  ...  0.930745  -1.0    0.0  0.936444

[5 rows x 10 columns]
2023-03-08 00:00:40,140:INFO:logic:main.py:478:getModel:885513: df_panel.iloc[-5:,:] :
    pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
45     0  0.508136  0.491864       0  ...  0.928942  -1.0    0.0  0.936986
46     1  0.491393  0.508607       0  ...  0.929694  -1.0    0.0  0.935216
47     1  0.499060  0.500940       0  ...  0.931259  -1.0    0.0  0.933641
48     1  0.483244  0.516756       0  ...  0.935227  -1.0    0.0  0.933270
49     1  0.440382  0.559618       1  ...  0.930745  -1.0    0.0  0.936444

[5 rows x 10 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '31.561', 'enterprice': '22386.6', 'countrevence': '0', 'unrealprofit': '2420.7287', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '22309.9', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}


## /root/FIL/strategy/modifiedmom/log.txt ----- -----

127.0.0.1 - - [08/Mar/2023 00:00:03] "POST / HTTP/1.1" 200 -
2023-03-08 00:00:03,229:INFO:modifiedmom:main.py:319:handleOrderFilled:185213: handleOrderFilled: data=OrderType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'clientorderid': '41906F1678204802588I0L59', 'symbol': 'BTCUSDT', 'gatewayorderid': 1678204802810839, 'quantity': '45.474', 'price': '22308.9', 'stopprice': '0', 'ordertype': '', 'side': 'SELL', 'status': 'FILLED', 'positionside': 'SHORT', 'createtime': 1678204802128, 'updatetime': 1678204802810, 'tradetype': 'usdt', 'selfid': 41906, 'filltrades': [TradeType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'tradeid': 1678204802810, 'clientorderid': '41906F1678204802588I0L59', 'price': '22308.9', 'quantity': '45.474', 'commission': '1014.4749186', 'commissionasset': 'USDT', 'tradetime': 1678204802810, 'tradetype': 'usdt', 'gatetype': 'simulator', 'handletime': 1678204802810}], 'gatetype': 'simulator', 'handletime': 0}
127.0.0.1 - - [08/Mar/2023 00:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=14744 

self.closeSec=1678205399, self.tradeDate='20230308', self.openTime='000000', self.closeTime='000959', self.symbol='BTCUSDT', self.open='22307.6', self.close='22346.7'
2023-03-08 00:10:01,766:INFO:modifiedmom:main.py:144:handleKline:185213: self.closeSec=1678205399, self.tradeDate='20230308', self.openTime='000000', self.closeTime='000959',self.symbol='BTCUSDT',self.open='22307.6', self.close='22346.7'
2023-03-08 00:10:01,803:INFO:modifiedmom:main.py:145:handleKline:185213: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
572  20230307   232000    232959  1678202999    22093  22201.1  0.005029
573  20230307   233000    233959  1678203599  22201.1  22372.4  0.007716
574  20230307   234000    234959  1678204199  22372.9  22353.3 -0.000854
575  20230307   235000    235959  1678204799  22353.3  22307.5 -0.002049
576  20230308   000000    000959  1678205399  22307.6  22346.7  0.001757
2023-03-08 00:10:01,804:INFO:modifiedmom:main.py:146:handleKline:185213: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=14745 

self.closeSec=1678205999, self.tradeDate='20230308', self.openTime='001000', self.closeTime='001959', self.symbol='BTCUSDT', self.open='22346.6', self.close='22296.7'
127.0.0.1 - - [08/Mar/2023 00:20:01] "POST / HTTP/1.1" 200 -
2023-03-08 00:20:02,494:INFO:modifiedmom:main.py:144:handleKline:185213: self.closeSec=1678205999, self.tradeDate='20230308', self.openTime='001000', self.closeTime='001959',self.symbol='BTCUSDT',self.open='22346.6', self.close='22296.7'
2023-03-08 00:20:02,854:INFO:modifiedmom:main.py:145:handleKline:185213: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
573  20230307   233000    233959  1678203599  22201.1  22372.4  0.007716
574  20230307   234000    234959  1678204199  22372.9  22353.3 -0.000854
575  20230307   235000    235959  1678204799  22353.3  22307.5 -0.002049
576  20230308   000000    000959  1678205399  22307.6  22346.7  0.001757
577  20230308   001000    001959  1678205999  22346.6  22296.7 -0.002237
2023-03-08 00:20:02,862:INFO:modifiedmom:main.py:146:handleKline:185213: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False}


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

2023-03-08 00:00:01,948:INFO:pyemd2:main.py:127:handleKline:185189: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}
2023-03-08 00:00:02,086:INFO:pyemd2:main.py:190:insertFactor:185189: curDateTime:3080000, name:pyemd2, symbol:BTCUSDT, tradeDate:20230307, closeTime:235959, close:22307.5, total:984062.1980325, pct_pre:-0.006850136070428059, thd:0.3918568057538046, side:sell 
127.0.0.1 - - [08/Mar/2023 00:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=14745 

self.closeSec=1678205399, self.tradeDate='20230308', self.openTime='000000', self.closeTime='000959', self.symbol='BTCUSDT', self.open='22307.6', self.close='22346.7'
2023-03-08 00:10:01,799:INFO:pyemd2:main.py:125:handleKline:185189: self.closeSec=1678205399, self.tradeDate='20230308', self.openTime='000000', self.closeTime='000959',self.symbol='BTCUSDT',self.open='22307.6', self.close='22346.7'
2023-03-08 00:10:01,840:INFO:pyemd2:main.py:126:handleKline:185189: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17420  20230307   232000    232959  1678202999    22093  22201.1
17421  20230307   233000    233959  1678203599  22201.1  22372.4
17422  20230307   234000    234959  1678204199  22372.9  22353.3
17423  20230307   235000    235959  1678204799  22353.3  22307.5
17424  20230308   000000    000959  1678205399  22307.6  22346.7
2023-03-08 00:10:01,840:INFO:pyemd2:main.py:127:handleKline:185189: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=14746 

self.closeSec=1678205999, self.tradeDate='20230308', self.openTime='001000', self.closeTime='001959', self.symbol='BTCUSDT', self.open='22346.6', self.close='22296.7'
127.0.0.1 - - [08/Mar/2023 00:20:01] "POST / HTTP/1.1" 200 -
2023-03-08 00:20:03,447:INFO:pyemd2:main.py:125:handleKline:185189: self.closeSec=1678205999, self.tradeDate='20230308', self.openTime='001000', self.closeTime='001959',self.symbol='BTCUSDT',self.open='22346.6', self.close='22296.7'
2023-03-08 00:20:03,589:INFO:pyemd2:main.py:126:handleKline:185189: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17421  20230307   233000    233959  1678203599  22201.1  22372.4
17422  20230307   234000    234959  1678204199  22372.9  22353.3
17423  20230307   235000    235959  1678204799  22353.3  22307.5
17424  20230308   000000    000959  1678205399  22307.6  22346.7
17425  20230308   001000    001959  1678205999  22346.6  22296.7
2023-03-08 00:20:03,591:INFO:pyemd2:main.py:127:handleKline:185189: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}


## /root/FIL/strategy/similarity/log.txt ----- -----

2023-03-08 00:00:03,031:INFO:testStrategy:main.py:308:handleOrderFilled:185174: handleOrderFilled: data=OrderType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'clientorderid': '41907F1678204802663I0L2', 'symbol': 'BTCUSDT', 'gatewayorderid': 1678204802771811, 'quantity': '52.305', 'price': '22308.9', 'stopprice': '0', 'ordertype': '', 'side': 'SELL', 'status': 'FILLED', 'positionside': 'SHORT', 'createtime': 1678204802367, 'updatetime': 1678204802771, 'tradetype': 'usdt', 'selfid': 41907, 'filltrades': [TradeType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'tradeid': 1678204802771, 'clientorderid': '41907F1678204802663I0L2', 'price': '22308.9', 'quantity': '52.305', 'commission': '1166.8670145', 'commissionasset': 'USDT', 'tradetime': 1678204802771, 'tradetype': 'usdt', 'gatetype': 'simulator', 'handletime': 1678204802771}], 'gatetype': 'simulator', 'handletime': 0}
127.0.0.1 - - [08/Mar/2023 00:00:03] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [08/Mar/2023 00:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=14745 

self.closeSec=1678205399, self.tradeDate='20230308', self.openTime='000000', self.closeTime='000959', self.symbol='BTCUSDT', self.open='22307.6', self.close='22346.7'
2023-03-08 00:10:01,777:INFO:testStrategy:main.py:101:handleKline:185174: self.closeSec=1678205399, self.tradeDate='20230308', self.openTime='000000', self.closeTime='000959',self.symbol='BTCUSDT',self.open='22307.6', self.close='22346.7'
2023-03-08 00:10:01,806:INFO:testStrategy:main.py:102:handleKline:185174: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12236  20230307   232000    232959  1678202999    22093  22201.1
12237  20230307   233000    233959  1678203599  22201.1  22372.4
12238  20230307   234000    234959  1678204199  22372.9  22353.3
12239  20230307   235000    235959  1678204799  22353.3  22307.5
12240  20230308   000000    000959  1678205399  22307.6  22346.7
2023-03-08 00:10:01,806:INFO:testStrategy:main.py:103:handleKline:185174: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False, 'isCorr': False}

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=14746 

self.closeSec=1678205999, self.tradeDate='20230308', self.openTime='001000', self.closeTime='001959', self.symbol='BTCUSDT', self.open='22346.6', self.close='22296.7'
127.0.0.1 - - [08/Mar/2023 00:20:02] "POST / HTTP/1.1" 200 -
2023-03-08 00:20:03,464:INFO:testStrategy:main.py:101:handleKline:185174: self.closeSec=1678205999, self.tradeDate='20230308', self.openTime='001000', self.closeTime='001959',self.symbol='BTCUSDT',self.open='22346.6', self.close='22296.7'
2023-03-08 00:20:03,591:INFO:testStrategy:main.py:102:handleKline:185174: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12237  20230307   233000    233959  1678203599  22201.1  22372.4
12238  20230307   234000    234959  1678204199  22372.9  22353.3
12239  20230307   235000    235959  1678204799  22353.3  22307.5
12240  20230308   000000    000959  1678205399  22307.6  22346.7
12241  20230308   001000    001959  1678205999  22346.6  22296.7
2023-03-08 00:20:03,592:INFO:testStrategy:main.py:103:handleKline:185174: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False, 'isCorr': False}


## /root/FIL/strategy/sr_min/log.txt ----- -----

127.0.0.1 - - [08/Mar/2023 00:20:01] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=0, self.total=1000000.0, self.flagDict['side']='', self.tradeCount=0, self.count=24922
self.closeSec=1678205999, self.tradeDate='20230308', self.openTime='001500', self.closeTime='001959', self.symbol='BTCUSDT', self.open=22287.1, self.close=22296.6, self.high=22303.4, self.low=22261.5, self.vol=4506.315, self.amt=100416002.2763 
2023-03-08 00:20:01,635:INFO:sr_min:main.py:172:handleKline:449472: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5759  20230307   235500    235959  ...         0.0        0.0       0
5760  20230308   000000    000459  ...         0.0        0.0       0
5761  20230308   000500    000959  ...         0.0        0.0       0
5762  20230308   001000    001459  ...         0.0        0.0       0
5763  20230308   001500    001959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-03-08 00:20:01,636:INFO:sr_min:main.py:175:handleKline:449472: self.closeSec=1678205999, self.tradeDate='20230308', self.openTime='001500', self.closeTime='001959',self.symbol='BTCUSDT',self.open=22287.1, self.close=22296.6, self.high=22303.4, self.low=22261.5, self.vol=4506.315, self.amt=100416002.2763, ukdf['pct'].iloc[-1]=0.000426 , ukdf['amount'].iloc[-1]=100416002.2763, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5763, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': []}
type(curSign)=<class 'int'>, curSign=0, self.sign=0
127.0.0.1 - - [08/Mar/2023 00:25:01] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=0, self.total=1000000.0, self.flagDict['side']='', self.tradeCount=0, self.count=24923
self.closeSec=1678206299, self.tradeDate='20230308', self.openTime='002000', self.closeTime='002459', self.symbol='BTCUSDT', self.open=22296.7, self.close=22284.6, self.high=22315.0, self.low=22280.3, self.vol=1851.05, self.amt=41274689.7832 
2023-03-08 00:25:01,688:INFO:sr_min:main.py:172:handleKline:449472: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5760  20230308   000000    000459  ...         0.0        0.0       0
5761  20230308   000500    000959  ...         0.0        0.0       0
5762  20230308   001000    001459  ...         0.0        0.0       0
5763  20230308   001500    001959  ...         0.0        0.0       0
5764  20230308   002000    002459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-03-08 00:25:01,689:INFO:sr_min:main.py:175:handleKline:449472: self.closeSec=1678206299, self.tradeDate='20230308', self.openTime='002000', self.closeTime='002459',self.symbol='BTCUSDT',self.open=22296.7, self.close=22284.6, self.high=22315.0, self.low=22280.3, self.vol=1851.05, self.amt=41274689.7832, ukdf['pct'].iloc[-1]=-0.000538 , ukdf['amount'].iloc[-1]=41274689.7832, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5764, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': []}
type(curSign)=<class 'int'>, curSign=0, self.sign=0


## /root/FIL/strategy/s_rsrs/log.txt ----- -----

723  20230307   120000    155959  1678175999  ...    723  0.003245 -2.049317    -1.0
724  20230307   160000    195959  1678190399  ...    724  0.002246 -2.019326    -1.0

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '42.135', 'enterprice': '23350.3', 'countrevence': '0', 'unrealprofit': '42674.328', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '22337.5', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-1, self.sign=-1
127.0.0.1 - - [08/Mar/2023 00:00:01] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='s_rsrs', self.symbol='BTCUSDT', interval='4h', intervalSec=14400, wid=25, thd=0.6, self.sign=-1, self.total=982881.0256095, self.flagDict['side']='sell', self.tradeCount=23, self.count=614
self.closeSec=1678204799, self.tradeDate='20230307', self.openTime='200000', self.closeTime='235959', self.symbol='BTCUSDT', self.open=22339.8, self.close=22307.5, self.high=22482.6, self.low=21908.0, self.vol=241400.179, self.amt=5364880890.25587 
2023-03-08 00:00:01,783:INFO:s_rsrs:main.py:141:handleKline:185271: self.closeSec=1678204799, self.tradeDate='20230307', self.openTime='200000', self.closeTime='235959',self.symbol='BTCUSDT',self.open=22339.8, self.close=22307.5, self.high=22482.6, self.low=21908.0, self.vol=241400.179, self.amt=5364880890.25587 
2023-03-08 00:00:01,853:INFO:s_rsrs:main.py:142:handleKline:185271: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime  ...         vol           amt       pct
721  20230307   040000    075959  ...   34143.090  7.641526e+08  0.000639
722  20230307   080000    115959  ...   38691.872  8.689790e+08  0.002322
723  20230307   120000    155959  ...   18027.295  4.044412e+08 -0.001809
724  20230307   160000    195959  ...   42943.905  9.607982e+08 -0.003066
725  20230307   200000    235959  ...  241400.179  5.364881e+09 -0.001446

[5 rows x 11 columns]
2023-03-08 00:00:04,633:INFO:s_rsrs:main.py:151:handleKline:185271: df_s.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec  ...  index      beta    zscore  signal
721  20230307   040000    075959  1678147199  ...    721  0.054042 -1.859668    -1.0
722  20230307   080000    115959  1678161599  ...    722  0.535163 -0.094572     NaN
723  20230307   120000    155959  1678175999  ...    723  0.003245 -2.049317    -1.0
724  20230307   160000    195959  1678190399  ...    724  0.002246 -2.019326    -1.0
725  20230307   200000    235959  1678204799  ...    725  0.000088 -1.989372    -1.0

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '42.135', 'enterprice': '23350.3', 'countrevence': '0', 'unrealprofit': '43787.1506723403', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '22311.08911422', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-1, self.sign=-1


