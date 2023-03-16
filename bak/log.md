# 20230316 16:26:01

## /root/FIL/strategy/amihud/log.txt ----- -----

--handleKline--: 127.0.0.1 - - [16/Mar/2023 16:20:01] "POST / HTTP/1.1" 200 -
 version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=993672.4896432, self.flagDict['side']='sell', self.tradeCount=2, self.count=31420
self.closeSec=1678954799, self.tradeDate='20230316', self.openTime='161500', self.closeTime='161959', self.symbol='BTCUSDT', self.open=24647.4, self.close=24637.0, self.high=24649.1, self.low=24606.0, self.vol=1232.367, self.amt=30346345.9788 
2023-03-16 16:20:01,880:INFO:amihud:main.py:172:handleKline:200676: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5951  20230316   155500    155959  ...         0.0        0.0       0
5952  20230316   160000    160459  ...         0.0        0.0       0
5953  20230316   160500    160959  ...         0.0        0.0       0
5954  20230316   161000    161459  ...         0.0        0.0       0
5955  20230316   161500    161959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-03-16 16:20:01,882:INFO:amihud:main.py:175:handleKline:200676: self.closeSec=1678954799, self.tradeDate='20230316', self.openTime='161500', self.closeTime='161959',self.symbol='BTCUSDT',self.open=24647.4, self.close=24637.0, self.high=24649.1, self.low=24606.0, self.vol=1232.367, self.amt=30346345.9788, ukdf['pct'].iloc[-1]=-0.000426 , ukdf['amount'].iloc[-1]=30346345.9788, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5955, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '60.176', 'enterprice': '16529.3', 'countrevence': '0', 'unrealprofit': '-487720.4624', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '24634.2', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1
--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=993672.4896432, self.flagDict['side']='sell', self.tradeCount=2, self.count=31421
self.closeSec=1678955099, self.tradeDate='20230316', self.openTime='162000', self.closeTime='162459', self.symbol='BTCUSDT', self.open=24637.0, self.close=24578.0, self.high=24644.8, self.low=24572.3, self.vol=1936.041, self.amt=47630887.1875 
127.0.0.1 - - [16/Mar/2023 16:25:01] "POST / HTTP/1.1" 200 -
2023-03-16 16:25:01,584:INFO:amihud:main.py:172:handleKline:200676: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5952  20230316   160000    160459  ...         0.0        0.0       0
5953  20230316   160500    160959  ...         0.0        0.0       0
5954  20230316   161000    161459  ...         0.0        0.0       0
5955  20230316   161500    161959  ...         0.0        0.0       0
5956  20230316   162000    162459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-03-16 16:25:01,584:INFO:amihud:main.py:175:handleKline:200676: self.closeSec=1678955099, self.tradeDate='20230316', self.openTime='162000', self.closeTime='162459',self.symbol='BTCUSDT',self.open=24637.0, self.close=24578.0, self.high=24644.8, self.low=24572.3, self.vol=1936.041, self.amt=47630887.1875, ukdf['pct'].iloc[-1]=-0.002395 , ukdf['amount'].iloc[-1]=47630887.1875, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5956, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '60.176', 'enterprice': '16529.3', 'countrevence': '0', 'unrealprofit': '-484308.4832', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '24577.5', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1


## /root/FIL/strategy/factorcheck/log.txt ----- -----

 version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.6154408643499563, self.count=31986 

self.closeSec=1678954799, self.tradeDate='20230316', self.openTime='161500', self.closeTime='161959', self.symbol='BTCUSDT', self.open=24647.4, self.close=24637.0, self.high=24649.1, self.low=24606.0 
2023-03-16 16:20:01,744:INFO:factorcheck2:main.py:126:handleKline:185239: self.closeSec=1678954799, self.tradeDate='20230316', self.openTime='161500', self.closeTime='161959',self.symbol='BTCUSDT',self.open=24647.4, self.close=24637.0, self.high=24649.1, self.low=24606.0   
2023-03-16 16:20:01,842:INFO:factorcheck2:main.py:127:handleKline:185239: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1631  20230316   155500    155959  1678953599  ...  24573.3  0.001497   1631    5
1632  20230316   160000    160459  1678953899  ...  24589.6 -0.000833   1632    0
1633  20230316   160500    160959  1678954199  ...  24581.6  0.001919   1633    1
1634  20230316   161000    161459  1678954499  ...  24629.8  0.000256   1634    2
1635  20230316   161500    161959  1678954799  ...  24606.0 -0.000426   1635    3

[5 rows x 11 columns]
2023-03-16 16:20:01,843:INFO:factorcheck2:main.py:128:handleKline:185239: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': False, 'isOpen': True, 'isClose': False, 'isTrig': True}

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.6154408643499563, self.count=31987 

self.closeSec=1678955099, self.tradeDate='20230316', self.openTime='162000', self.closeTime='162459', self.symbol='BTCUSDT', self.open=24637.0, self.close=24578.0, self.high=24644.8, self.low=24572.3 
127.0.0.1 - - [16/Mar/2023 16:25:01] "POST / HTTP/1.1" 200 -
2023-03-16 16:25:01,529:INFO:factorcheck2:main.py:126:handleKline:185239: self.closeSec=1678955099, self.tradeDate='20230316', self.openTime='162000', self.closeTime='162459',self.symbol='BTCUSDT',self.open=24637.0, self.close=24578.0, self.high=24644.8, self.low=24572.3   
2023-03-16 16:25:01,559:INFO:factorcheck2:main.py:127:handleKline:185239: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1632  20230316   160000    160459  1678953899  ...  24589.6 -0.000833   1632    0
1633  20230316   160500    160959  1678954199  ...  24581.6  0.001919   1633    1
1634  20230316   161000    161459  1678954499  ...  24629.8  0.000256   1634    2
1635  20230316   161500    161959  1678954799  ...  24606.0 -0.000426   1635    3
1636  20230316   162000    162459  1678955099  ...  24572.3 -0.002395   1636    4

[5 rows x 11 columns]
2023-03-16 16:25:01,559:INFO:factorcheck2:main.py:128:handleKline:185239: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': False, 'isOpen': True, 'isClose': False, 'isTrig': True}


## /root/FIL/strategy/logic/log.txt ----- -----

2023-03-16 16:00:32,691:DEBUG:logic:main.py:463:getModel:885513: df_s.iloc[-5:,:] :
          date closeTime     open  ...    alpha58   alpha67   alpha72
5786  20230316    132959  24267.0  ...  52.916667  0.507445  0.652248
5787  20230316    135959  24376.6  ...  52.916667  0.504360  0.652210
5788  20230316    142959  24345.1  ...  53.333333  0.513930  0.647144
5789  20230316    145959  24443.8  ...  53.750000  0.525756  0.636049
5790  20230316    152959  24569.4  ...  54.166667  0.530822  0.622924

[5 rows x 33 columns]
0.5571955719557196
acc is : 0.5571955719557196
2023-03-16 16:00:32,871:INFO:logic:main.py:468:getModel:885513: df_pred.iloc[-5:,:] :
     pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
537     0  0.554473  0.445527       0  ...  1.064134   1.0    0.0  1.088278
538     0  0.508840  0.491160       1  ...  1.068461   1.0    0.0  1.092704
539     0  0.568966  0.431034       1  ...  1.073938   1.0    0.0  1.098305
540     0  0.594828  0.405172       1  ...  1.076321   1.0    0.0  1.100741
541     0  0.583613  0.416387       0  ...  1.075914   1.0    0.0  1.100325

[5 rows x 10 columns]
2023-03-16 16:00:32,909:INFO:logic:main.py:478:getModel:885513: df_panel.iloc[-5:,:] :
    pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
45     0  0.555053  0.444947       0  ...  1.064134   1.0    0.0  1.091949
46     0  0.509251  0.490749       1  ...  1.068461   1.0    0.0  1.095937
47     0  0.569030  0.430970       1  ...  1.073938   1.0    0.0  1.100001
48     0  0.594263  0.405737       1  ...  1.076321   1.0    0.0  1.103459
49     0  0.583613  0.416387       0  ...  1.075914   1.0    0.0  1.100325

[5 rows x 10 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': []}


## /root/FIL/strategy/modifiedmom/log.txt ----- -----

527  20230316   155000    155959  1678953599  24596.1  24614.5  0.000744
2023-03-16 16:00:02,091:INFO:modifiedmom:main.py:146:handleKline:185213: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': True, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True}

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=15992 

self.closeSec=1678954199, self.tradeDate='20230316', self.openTime='160000', self.closeTime='160959', self.symbol='BTCUSDT', self.open='24614.5', self.close='24641.2'
2023-03-16 16:10:01,614:INFO:modifiedmom:main.py:144:handleKline:185213: self.closeSec=1678954199, self.tradeDate='20230316', self.openTime='160000', self.closeTime='160959',self.symbol='BTCUSDT',self.open='24614.5', self.close='24641.2'
127.0.0.1 - - [16/Mar/2023 16:10:01] "POST / HTTP/1.1" 200 -
2023-03-16 16:10:01,632:INFO:modifiedmom:main.py:145:handleKline:185213: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
524  20230316   152000    152959  1678951799  24554.1  24623.8  0.002835
525  20230316   153000    153959  1678952399  24626.4  24631.9  0.000329
526  20230316   154000    154959  1678952999  24630.9  24596.2 -0.001449
527  20230316   155000    155959  1678953599  24596.1  24614.5  0.000744
528  20230316   160000    160959  1678954199  24614.5  24641.2  0.001085
2023-03-16 16:10:01,632:INFO:modifiedmom:main.py:146:handleKline:185213: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': True, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True}

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=15993 

self.closeSec=1678954799, self.tradeDate='20230316', self.openTime='161000', self.closeTime='161959', self.symbol='BTCUSDT', self.open='24641.1', self.close='24637'
127.0.0.1 - - [16/Mar/2023 16:20:01] "POST / HTTP/1.1" 200 -
2023-03-16 16:20:02,176:INFO:modifiedmom:main.py:144:handleKline:185213: self.closeSec=1678954799, self.tradeDate='20230316', self.openTime='161000', self.closeTime='161959',self.symbol='BTCUSDT',self.open='24641.1', self.close='24637'
2023-03-16 16:20:02,388:INFO:modifiedmom:main.py:145:handleKline:185213: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
525  20230316   153000    153959  1678952399  24626.4  24631.9  0.000329
526  20230316   154000    154959  1678952999  24630.9  24596.2 -0.001449
527  20230316   155000    155959  1678953599  24596.1  24614.5  0.000744
528  20230316   160000    160959  1678954199  24614.5  24641.2  0.001085
529  20230316   161000    161959  1678954799  24641.1    24637 -0.000170
2023-03-16 16:20:02,394:INFO:modifiedmom:main.py:146:handleKline:185213: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': True, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True}


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

17519  20230316   155000    155959  1678953599  24596.1  24614.5
2023-03-16 16:00:02,110:INFO:pyemd2:main.py:127:handleKline:185189: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}
127.0.0.1 - - [16/Mar/2023 16:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=15993 

self.closeSec=1678954199, self.tradeDate='20230316', self.openTime='160000', self.closeTime='160959', self.symbol='BTCUSDT', self.open='24614.5', self.close='24641.2'
2023-03-16 16:10:01,611:INFO:pyemd2:main.py:125:handleKline:185189: self.closeSec=1678954199, self.tradeDate='20230316', self.openTime='160000', self.closeTime='160959',self.symbol='BTCUSDT',self.open='24614.5', self.close='24641.2'
2023-03-16 16:10:01,640:INFO:pyemd2:main.py:126:handleKline:185189: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17516  20230316   152000    152959  1678951799  24554.1  24623.8
17517  20230316   153000    153959  1678952399  24626.4  24631.9
17518  20230316   154000    154959  1678952999  24630.9  24596.2
17519  20230316   155000    155959  1678953599  24596.1  24614.5
17520  20230316   160000    160959  1678954199  24614.5  24641.2
2023-03-16 16:10:01,640:INFO:pyemd2:main.py:127:handleKline:185189: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=15994 

self.closeSec=1678954799, self.tradeDate='20230316', self.openTime='161000', self.closeTime='161959', self.symbol='BTCUSDT', self.open='24641.1', self.close='24637'
127.0.0.1 - - [16/Mar/2023 16:20:01] "POST / HTTP/1.1" 200 -
2023-03-16 16:20:02,951:INFO:pyemd2:main.py:125:handleKline:185189: self.closeSec=1678954799, self.tradeDate='20230316', self.openTime='161000', self.closeTime='161959',self.symbol='BTCUSDT',self.open='24641.1', self.close='24637'
2023-03-16 16:20:03,006:INFO:pyemd2:main.py:126:handleKline:185189: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17517  20230316   153000    153959  1678952399  24626.4  24631.9
17518  20230316   154000    154959  1678952999  24630.9  24596.2
17519  20230316   155000    155959  1678953599  24596.1  24614.5
17520  20230316   160000    160959  1678954199  24614.5  24641.2
17521  20230316   161000    161959  1678954799  24641.1    24637
2023-03-16 16:20:03,006:INFO:pyemd2:main.py:127:handleKline:185189: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}


## /root/FIL/strategy/similarity/log.txt ----- -----

12191  20230316   155000    155959  1678953599  24596.1  24614.5
2023-03-16 16:00:02,101:INFO:testStrategy:main.py:103:handleKline:185174: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=15993 

self.closeSec=1678954199, self.tradeDate='20230316', self.openTime='160000', self.closeTime='160959', self.symbol='BTCUSDT', self.open='24614.5', self.close='24641.2'
2023-03-16 16:10:01,598:INFO:testStrategy:main.py:101:handleKline:185174: self.closeSec=1678954199, self.tradeDate='20230316', self.openTime='160000', self.closeTime='160959',self.symbol='BTCUSDT',self.open='24614.5', self.close='24641.2'
127.0.0.1 - - [16/Mar/2023 16:10:01] "POST / HTTP/1.1" 200 -
2023-03-16 16:10:01,642:INFO:testStrategy:main.py:102:handleKline:185174: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12188  20230316   152000    152959  1678951799  24554.1  24623.8
12189  20230316   153000    153959  1678952399  24626.4  24631.9
12190  20230316   154000    154959  1678952999  24630.9  24596.2
12191  20230316   155000    155959  1678953599  24596.1  24614.5
12192  20230316   160000    160959  1678954199  24614.5  24641.2
2023-03-16 16:10:01,642:INFO:testStrategy:main.py:103:handleKline:185174: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=15994 

self.closeSec=1678954799, self.tradeDate='20230316', self.openTime='161000', self.closeTime='161959', self.symbol='BTCUSDT', self.open='24641.1', self.close='24637'
127.0.0.1 - - [16/Mar/2023 16:20:01] "POST / HTTP/1.1" 200 -
2023-03-16 16:20:02,798:INFO:testStrategy:main.py:101:handleKline:185174: self.closeSec=1678954799, self.tradeDate='20230316', self.openTime='161000', self.closeTime='161959',self.symbol='BTCUSDT',self.open='24641.1', self.close='24637'
2023-03-16 16:20:02,907:INFO:testStrategy:main.py:102:handleKline:185174: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12189  20230316   153000    153959  1678952399  24626.4  24631.9
12190  20230316   154000    154959  1678952999  24630.9  24596.2
12191  20230316   155000    155959  1678953599  24596.1  24614.5
12192  20230316   160000    160959  1678954199  24614.5  24641.2
12193  20230316   161000    161959  1678954799  24641.1    24637
2023-03-16 16:20:02,907:INFO:testStrategy:main.py:103:handleKline:185174: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}


## /root/FIL/strategy/sr_min/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=0, self.total=1000000.0, self.flagDict['side']='', self.tradeCount=0, self.count=27418
self.closeSec=1678954799, self.tradeDate='20230316', self.openTime='161500', self.closeTime='161959', self.symbol='BTCUSDT', self.open=24647.4, self.close=24637.0, self.high=24649.1, self.low=24606.0, self.vol=1232.367, self.amt=30346345.9788 
127.0.0.1 - - [16/Mar/2023 16:20:01] "POST / HTTP/1.1" 200 -
2023-03-16 16:20:01,767:INFO:sr_min:main.py:172:handleKline:449472: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5951  20230316   155500    155959  ...         0.0        0.0       0
5952  20230316   160000    160459  ...         0.0        0.0       0
5953  20230316   160500    160959  ...         0.0        0.0       0
5954  20230316   161000    161459  ...         0.0        0.0       0
5955  20230316   161500    161959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-03-16 16:20:01,770:INFO:sr_min:main.py:175:handleKline:449472: self.closeSec=1678954799, self.tradeDate='20230316', self.openTime='161500', self.closeTime='161959',self.symbol='BTCUSDT',self.open=24647.4, self.close=24637.0, self.high=24649.1, self.low=24606.0, self.vol=1232.367, self.amt=30346345.9788, ukdf['pct'].iloc[-1]=-0.000426 , ukdf['amount'].iloc[-1]=30346345.9788, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5955, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': []}
type(curSign)=<class 'int'>, curSign=0, self.sign=0
--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=0, self.total=1000000.0, self.flagDict['side']='', self.tradeCount=0, self.count=27419
self.closeSec=1678955099, self.tradeDate='20230316', self.openTime='162000', self.closeTime='162459', self.symbol='BTCUSDT', self.open=24637.0, self.close=24578.0, self.high=24644.8, self.low=24572.3, self.vol=1936.041, self.amt=47630887.1875 
127.0.0.1 - - [16/Mar/2023 16:25:01] "POST / HTTP/1.1" 200 -
2023-03-16 16:25:01,570:INFO:sr_min:main.py:172:handleKline:449472: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5952  20230316   160000    160459  ...         0.0        0.0       0
5953  20230316   160500    160959  ...         0.0        0.0       0
5954  20230316   161000    161459  ...         0.0        0.0       0
5955  20230316   161500    161959  ...         0.0        0.0       0
5956  20230316   162000    162459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-03-16 16:25:01,570:INFO:sr_min:main.py:175:handleKline:449472: self.closeSec=1678955099, self.tradeDate='20230316', self.openTime='162000', self.closeTime='162459',self.symbol='BTCUSDT',self.open=24637.0, self.close=24578.0, self.high=24644.8, self.low=24572.3, self.vol=1936.041, self.amt=47630887.1875, ukdf['pct'].iloc[-1]=-0.002395 , ukdf['amount'].iloc[-1]=47630887.1875, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5956, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': []}
type(curSign)=<class 'int'>, curSign=0, self.sign=0


## /root/FIL/strategy/s_rsrs/log.txt ----- -----

721  20230316   040000    075959  1678924799  ...    721  1.054196  1.316485     1.0
722  20230316   080000    115959  1678939199  ...    722  0.999147  1.132247     1.0

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '55.825', 'enterprice': '20070', 'countrevence': '0', 'unrealprofit': '234565.485', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '24271.8', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=1, self.sign=1
127.0.0.1 - - [16/Mar/2023 16:00:01] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='s_rsrs', self.symbol='BTCUSDT', interval='4h', intervalSec=14400, wid=25, thd=0.6, self.sign=1, self.total=1119287.34225, self.flagDict['side']='buy', self.tradeCount=24, self.count=666
self.closeSec=1678953599, self.tradeDate='20230316', self.openTime='120000', self.closeTime='155959', self.symbol='BTCUSDT', self.open=24271.9, self.close=24614.5, self.high=24694.9, self.low=24178.0, self.vol=88010.463, self.amt=2152492187.66213 
2023-03-16 16:00:01,943:INFO:s_rsrs:main.py:141:handleKline:185271: self.closeSec=1678953599, self.tradeDate='20230316', self.openTime='120000', self.closeTime='155959',self.symbol='BTCUSDT',self.open=24271.9, self.close=24614.5, self.high=24694.9, self.low=24178.0, self.vol=88010.463, self.amt=2152492187.66213 
2023-03-16 16:00:02,030:INFO:s_rsrs:main.py:142:handleKline:185271: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime  ...         vol           amt       pct
719  20230315   200000    235959  ...  376951.657  9.340376e+09 -0.012206
720  20230316   000000    035959  ...  279276.742  6.776350e+09 -0.004097
721  20230316   040000    075959  ...   78584.034  1.916961e+09 -0.003765
722  20230316   080000    115959  ...   68553.169  1.664733e+09 -0.000663
723  20230316   120000    155959  ...   88010.463  2.152492e+09  0.014115

[5 rows x 11 columns]
2023-03-16 16:00:04,086:INFO:s_rsrs:main.py:151:handleKline:185271: df_s.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec  ...  index      beta    zscore  signal
719  20230315   200000    235959  1678895999  ...    719  1.137514  1.631562     1.0
720  20230316   000000    035959  1678910399  ...    720  1.098944  1.476941     1.0
721  20230316   040000    075959  1678924799  ...    721  1.054196  1.316485     1.0
722  20230316   080000    115959  1678939199  ...    722  0.999147  1.132247     1.0
723  20230316   120000    155959  1678953599  ...    723  0.936352  0.935144     1.0

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '55.825', 'enterprice': '20070', 'countrevence': '0', 'unrealprofit': '253875.3525', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '24617.7', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=1, self.sign=1


