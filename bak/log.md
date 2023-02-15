# 20230215 08:36:07

## /root/FIL/strategy/amihud/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=993672.4896432, self.flagDict['side']='sell', self.tradeCount=2, self.count=22974
self.closeSec=1676420999, self.tradeDate='20230215', self.openTime='082500', self.closeTime='082959', self.symbol='BTCUSDT', self.open=22147.9, self.close=22165.0, self.high=22169.0, self.low=22145.2, self.vol=526.085, self.amt=11655836.4855 
127.0.0.1 - - [15/Feb/2023 08:30:01] "POST / HTTP/1.1" 200 -
2023-02-15 08:30:03,150:INFO:amihud:main.py:172:handleKline:200676: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5857  20230215   080500    080959  ...         0.0        0.0       0
5858  20230215   081000    081459  ...         0.0        0.0       0
5859  20230215   081500    081959  ...         0.0        0.0       0
5860  20230215   082000    082459  ...         0.0        0.0       0
5861  20230215   082500    082959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-02-15 08:30:03,161:INFO:amihud:main.py:175:handleKline:200676: self.closeSec=1676420999, self.tradeDate='20230215', self.openTime='082500', self.closeTime='082959',self.symbol='BTCUSDT',self.open=22147.9, self.close=22165.0, self.high=22169.0, self.low=22145.2, self.vol=526.085, self.amt=11655836.4855, ukdf['pct'].iloc[-1]=0.000772 , ukdf['amount'].iloc[-1]=11655836.4855, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5861, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '60.176', 'enterprice': '16529.3', 'countrevence': '0', 'unrealprofit': '-339162.90461530208', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '22165.48227558', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1
--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=993672.4896432, self.flagDict['side']='sell', self.tradeCount=2, self.count=22975
self.closeSec=1676421299, self.tradeDate='20230215', self.openTime='083000', self.closeTime='083459', self.symbol='BTCUSDT', self.open=22165.1, self.close=22121.7, self.high=22178.0, self.low=22121.7, self.vol=1053.967, self.amt=23341624.9205 
127.0.0.1 - - [15/Feb/2023 08:35:01] "POST / HTTP/1.1" 200 -
2023-02-15 08:35:01,570:INFO:amihud:main.py:172:handleKline:200676: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5858  20230215   081000    081459  ...         0.0        0.0       0
5859  20230215   081500    081959  ...         0.0        0.0       0
5860  20230215   082000    082459  ...         0.0        0.0       0
5861  20230215   082500    082959  ...         0.0        0.0       0
5862  20230215   083000    083459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-02-15 08:35:01,571:INFO:amihud:main.py:175:handleKline:200676: self.closeSec=1676421299, self.tradeDate='20230215', self.openTime='083000', self.closeTime='083459',self.symbol='BTCUSDT',self.open=22165.1, self.close=22121.7, self.high=22178.0, self.low=22121.7, self.vol=1053.967, self.amt=23341624.9205, ukdf['pct'].iloc[-1]=-0.001954 , ukdf['amount'].iloc[-1]=23341624.9205, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5862, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '60.176', 'enterprice': '16529.3', 'countrevence': '0', 'unrealprofit': '-336745.37265469776', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '22125.30792101', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1


## /root/FIL/strategy/factorcheck/log.txt ----- -----

1540  20230215   082000    082459  1676420699  ...  22139.0 -0.000857   1540    4
1541  20230215   082500    082959  1676420999  ...  22145.2  0.000772   1541    5

[5 rows x 11 columns]
2023-02-15 08:30:02,070:INFO:factorcheck2:main.py:128:handleKline:185239: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}
2023-02-15 08:30:02,352:INFO:factorcheck2:main.py:145:handleKline:185239: df_panel.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec  ...       pct  index  idx    factor
213  20230215   062500    062959  1676413799  ... -0.000338   1517    5  0.316684
214  20230215   065500    065959  1676415599  ...  0.000961   1523    5  0.312360
215  20230215   072500    072959  1676417399  ...  0.000077   1529    5  0.307076
216  20230215   075500    075959  1676419199  ... -0.000086   1535    5  0.302601
217  20230215   082500    082959  1676420999  ...  0.000772   1541    5  0.299057

[5 rows x 12 columns]

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=8, self.factor=0.29905650462424405, self.count=23541 

self.closeSec=1676421299, self.tradeDate='20230215', self.openTime='083000', self.closeTime='083459', self.symbol='BTCUSDT', self.open=22165.1, self.close=22121.7, self.high=22178.0, self.low=22121.7 
127.0.0.1 - - [15/Feb/2023 08:35:01] "POST / HTTP/1.1" 200 -
2023-02-15 08:35:01,521:INFO:factorcheck2:main.py:126:handleKline:185239: self.closeSec=1676421299, self.tradeDate='20230215', self.openTime='083000', self.closeTime='083459',self.symbol='BTCUSDT',self.open=22165.1, self.close=22121.7, self.high=22178.0, self.low=22121.7   
2023-02-15 08:35:01,544:INFO:factorcheck2:main.py:127:handleKline:185239: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1538  20230215   081000    081459  1676420099  ...  22155.0 -0.000289   1538    2
1539  20230215   081500    081959  1676420399  ...  22152.2  0.000438   1539    3
1540  20230215   082000    082459  1676420699  ...  22139.0 -0.000857   1540    4
1541  20230215   082500    082959  1676420999  ...  22145.2  0.000772   1541    5
1542  20230215   083000    083459  1676421299  ...  22121.7 -0.001954   1542    0

[5 rows x 11 columns]
2023-02-15 08:35:01,545:INFO:factorcheck2:main.py:128:handleKline:185239: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}


## /root/FIL/strategy/logic/log.txt ----- -----

2023-02-15 08:30:32,397:DEBUG:logic:main.py:463:getModel:885513: df_s.iloc[-5:,:] :
          date closeTime     open  ...    alpha58   alpha67   alpha72
5771  20230215    055959  22233.6  ...  47.500000  0.589573  0.234753
5772  20230215    062959  22230.6  ...  47.083333  0.578611  0.229548
5773  20230215    065959  22189.2  ...  47.083333  0.575315  0.225689
5774  20230215    072959  22176.8  ...  47.083333  0.581004  0.219755
5775  20230215    075959  22205.9  ...  47.083333  0.576016  0.215694

[5 rows x 33 columns]
0.5471349353049908
acc is : 0.5471349353049908
2023-02-15 08:30:32,556:INFO:logic:main.py:468:getModel:885513: df_pred.iloc[-5:,:] :
     pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
536     0  0.506877  0.493123       0  ...  0.995666   1.0    0.0  0.944057
537     1  0.492841  0.507159       0  ...  0.995105   1.0    0.0  0.943525
538     1  0.496644  0.503356       1  ...  0.996416   1.0    0.0  0.944767
539     0  0.503261  0.496739       0  ...  0.995586   1.0    0.0  0.943980
540     1  0.493088  0.506912       0  ...  0.994580   1.0    0.0  0.943027

[5 rows x 10 columns]
2023-02-15 08:30:32,592:INFO:logic:main.py:478:getModel:885513: df_panel.iloc[-5:,:] :
    pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
45     0  0.506552  0.493448       0  ...  0.995666   1.0    0.0  0.937416
46     1  0.492916  0.507084       0  ...  0.995105   1.0    0.0  0.943119
47     1  0.496292  0.503708       1  ...  0.996416   1.0    0.0  0.942214
48     0  0.502796  0.497204       0  ...  0.995586   1.0    0.0  0.941429
49     1  0.493088  0.506912       0  ...  0.994580   1.0    0.0  0.943027

[5 rows x 10 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '35.557', 'enterprice': '21695.5', 'countrevence': '0', 'unrealprofit': '17088.6942', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '22176.1', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}


## /root/FIL/strategy/modifiedmom/log.txt ----- -----

624  20230215   080000    080959  1676419799  22187.4  22163.6 -0.001073
2023-02-15 08:10:01,768:INFO:modifiedmom:main.py:146:handleKline:185213: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=11769 

self.closeSec=1676420399, self.tradeDate='20230215', self.openTime='081000', self.closeTime='081959', self.symbol='BTCUSDT', self.open='22163.6', self.close='22166.9'
2023-02-15 08:20:01,611:INFO:modifiedmom:main.py:144:handleKline:185213: self.closeSec=1676420399, self.tradeDate='20230215', self.openTime='081000', self.closeTime='081959',self.symbol='BTCUSDT',self.open='22163.6', self.close='22166.9'
127.0.0.1 - - [15/Feb/2023 08:20:01] "POST / HTTP/1.1" 200 -
2023-02-15 08:20:01,648:INFO:modifiedmom:main.py:145:handleKline:185213: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
621  20230215   073000    073959  1676417999  22205.9  22214.2  0.000374
622  20230215   074000    074959  1676418599  22214.2  22204.2 -0.000450
623  20230215   075000    075959  1676419199  22204.1  22187.4 -0.000757
624  20230215   080000    080959  1676419799  22187.4  22163.6 -0.001073
625  20230215   081000    081959  1676420399  22163.6  22166.9  0.000149
2023-02-15 08:20:01,649:INFO:modifiedmom:main.py:146:handleKline:185213: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=11770 

self.closeSec=1676420999, self.tradeDate='20230215', self.openTime='082000', self.closeTime='082959', self.symbol='BTCUSDT', self.open='22166.9', self.close='22165'
127.0.0.1 - - [15/Feb/2023 08:30:02] "POST / HTTP/1.1" 200 -
2023-02-15 08:30:03,420:INFO:modifiedmom:main.py:144:handleKline:185213: self.closeSec=1676420999, self.tradeDate='20230215', self.openTime='082000', self.closeTime='082959',self.symbol='BTCUSDT',self.open='22166.9', self.close='22165'
2023-02-15 08:30:03,549:INFO:modifiedmom:main.py:145:handleKline:185213: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
622  20230215   074000    074959  1676418599  22214.2  22204.2 -0.000450
623  20230215   075000    075959  1676419199  22204.1  22187.4 -0.000757
624  20230215   080000    080959  1676419799  22187.4  22163.6 -0.001073
625  20230215   081000    081959  1676420399  22163.6  22166.9  0.000149
626  20230215   082000    082959  1676420999  22166.9    22165 -0.000086
2023-02-15 08:30:03,549:INFO:modifiedmom:main.py:146:handleKline:185213: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False}


## /root/FIL/strategy/percentile_regression_step2/log.txt ----- -----

127.0.0.1 - - [15/Feb/2023 07:30:01] "POST / HTTP/1.1" 200 -
2023-02-15 07:30:02,853:DEBUG:percentile_regression_step2:main.py:154:get_signal:1265985: df_id.iloc[-5:,:] :
                 daytime     hms    close  ...  pct_10  pct_20  factor
144  2023/02/15 05:00:00  050000  22233.6  ...     NaN     NaN       0
145  2023/02/15 05:30:00  053000  22230.6  ...     NaN     NaN       0
146  2023/02/15 06:00:00  060000  22189.2  ...     NaN     NaN       0
147  2023/02/15 06:30:00  063000  22176.7  ...     NaN     NaN       0
148  2023/02/15 07:00:00  070000  22205.9  ...     NaN     NaN       0

[5 rows x 10 columns]
127.0.0.1 - - [15/Feb/2023 08:00:02] "POST / HTTP/1.1" 200 -
2023-02-15 08:00:03,448:DEBUG:percentile_regression_step2:main.py:154:get_signal:1265985: df_id.iloc[-5:,:] :
                 daytime     hms    close  ...  pct_10  pct_20  factor
144  2023/02/15 05:30:00  053000  22230.6  ...     NaN     NaN       0
145  2023/02/15 06:00:00  060000  22189.2  ...     NaN     NaN       0
146  2023/02/15 06:30:00  063000  22176.7  ...     NaN     NaN       0
147  2023/02/15 07:00:00  070000  22205.9  ...     NaN     NaN       0
148  2023/02/15 07:30:00  073000  22187.4  ...     NaN     NaN       0

[5 rows x 10 columns]
127.0.0.1 - - [15/Feb/2023 08:30:01] "POST / HTTP/1.1" 200 -
2023-02-15 08:30:03,102:DEBUG:percentile_regression_step2:main.py:154:get_signal:1265985: df_id.iloc[-5:,:] :
                 daytime     hms    close  ...  pct_10  pct_20  factor
144  2023/02/15 06:00:00  060000  22189.2  ...     NaN     NaN       0
145  2023/02/15 06:30:00  063000  22176.7  ...     NaN     NaN       0
146  2023/02/15 07:00:00  070000  22205.9  ...     NaN     NaN       0
147  2023/02/15 07:30:00  073000  22187.4  ...     NaN     NaN       0
148  2023/02/15 08:00:00  080000  22165.0  ...     NaN     NaN       0

[5 rows x 10 columns]


## /root/FIL/strategy/pyemd/log.txt ----- -----

17472  20230215   080000    080959  1676419799  22187.4  22163.6
2023-02-15 08:10:01,783:INFO:pyemd2:main.py:127:handleKline:185189: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}
127.0.0.1 - - [15/Feb/2023 08:20:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=11770 

self.closeSec=1676420399, self.tradeDate='20230215', self.openTime='081000', self.closeTime='081959', self.symbol='BTCUSDT', self.open='22163.6', self.close='22166.9'
2023-02-15 08:20:01,619:INFO:pyemd2:main.py:125:handleKline:185189: self.closeSec=1676420399, self.tradeDate='20230215', self.openTime='081000', self.closeTime='081959',self.symbol='BTCUSDT',self.open='22163.6', self.close='22166.9'
2023-02-15 08:20:01,672:INFO:pyemd2:main.py:126:handleKline:185189: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17469  20230215   073000    073959  1676417999  22205.9  22214.2
17470  20230215   074000    074959  1676418599  22214.2  22204.2
17471  20230215   075000    075959  1676419199  22204.1  22187.4
17472  20230215   080000    080959  1676419799  22187.4  22163.6
17473  20230215   081000    081959  1676420399  22163.6  22166.9
2023-02-15 08:20:01,674:INFO:pyemd2:main.py:127:handleKline:185189: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=11771 

self.closeSec=1676420999, self.tradeDate='20230215', self.openTime='082000', self.closeTime='082959', self.symbol='BTCUSDT', self.open='22166.9', self.close='22165'
127.0.0.1 - - [15/Feb/2023 08:30:02] "POST / HTTP/1.1" 200 -
2023-02-15 08:30:03,870:INFO:pyemd2:main.py:125:handleKline:185189: self.closeSec=1676420999, self.tradeDate='20230215', self.openTime='082000', self.closeTime='082959',self.symbol='BTCUSDT',self.open='22166.9', self.close='22165'
2023-02-15 08:30:04,026:INFO:pyemd2:main.py:126:handleKline:185189: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17470  20230215   074000    074959  1676418599  22214.2  22204.2
17471  20230215   075000    075959  1676419199  22204.1  22187.4
17472  20230215   080000    080959  1676419799  22187.4  22163.6
17473  20230215   081000    081959  1676420399  22163.6  22166.9
17474  20230215   082000    082959  1676420999  22166.9    22165
2023-02-15 08:30:04,026:INFO:pyemd2:main.py:127:handleKline:185189: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}


## /root/FIL/strategy/similarity/log.txt ----- -----

2023-02-15 08:10:01,753:INFO:testStrategy:main.py:103:handleKline:185174: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}
127.0.0.1 - - [15/Feb/2023 08:10:01] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [15/Feb/2023 08:20:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=11770 

self.closeSec=1676420399, self.tradeDate='20230215', self.openTime='081000', self.closeTime='081959', self.symbol='BTCUSDT', self.open='22163.6', self.close='22166.9'
2023-02-15 08:20:01,653:INFO:testStrategy:main.py:101:handleKline:185174: self.closeSec=1676420399, self.tradeDate='20230215', self.openTime='081000', self.closeTime='081959',self.symbol='BTCUSDT',self.open='22163.6', self.close='22166.9'
2023-02-15 08:20:01,693:INFO:testStrategy:main.py:102:handleKline:185174: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12141  20230215   073000    073959  1676417999  22205.9  22214.2
12142  20230215   074000    074959  1676418599  22214.2  22204.2
12143  20230215   075000    075959  1676419199  22204.1  22187.4
12144  20230215   080000    080959  1676419799  22187.4  22163.6
12145  20230215   081000    081959  1676420399  22163.6  22166.9
2023-02-15 08:20:01,693:INFO:testStrategy:main.py:103:handleKline:185174: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=11771 

self.closeSec=1676420999, self.tradeDate='20230215', self.openTime='082000', self.closeTime='082959', self.symbol='BTCUSDT', self.open='22166.9', self.close='22165'
127.0.0.1 - - [15/Feb/2023 08:30:02] "POST / HTTP/1.1" 200 -
2023-02-15 08:30:03,852:INFO:testStrategy:main.py:101:handleKline:185174: self.closeSec=1676420999, self.tradeDate='20230215', self.openTime='082000', self.closeTime='082959',self.symbol='BTCUSDT',self.open='22166.9', self.close='22165'
2023-02-15 08:30:04,010:INFO:testStrategy:main.py:102:handleKline:185174: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12142  20230215   074000    074959  1676418599  22214.2  22204.2
12143  20230215   075000    075959  1676419199  22204.1  22187.4
12144  20230215   080000    080959  1676419799  22187.4  22163.6
12145  20230215   081000    081959  1676420399  22163.6  22166.9
12146  20230215   082000    082959  1676420999  22166.9    22165
2023-02-15 08:30:04,010:INFO:testStrategy:main.py:103:handleKline:185174: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}


## /root/FIL/strategy/sr_min/log.txt ----- -----

127.0.0.1 - - [15/Feb/2023 08:30:01] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=0, self.total=1000000.0, self.flagDict['side']='', self.tradeCount=0, self.count=18972
self.closeSec=1676420999, self.tradeDate='20230215', self.openTime='082500', self.closeTime='082959', self.symbol='BTCUSDT', self.open=22147.9, self.close=22165.0, self.high=22169.0, self.low=22145.2, self.vol=526.085, self.amt=11655836.4855 
2023-02-15 08:30:01,884:INFO:sr_min:main.py:172:handleKline:449472: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5857  20230215   080500    080959  ...         0.0        0.0       0
5858  20230215   081000    081459  ...         0.0        0.0       0
5859  20230215   081500    081959  ...         0.0        0.0       0
5860  20230215   082000    082459  ...         0.0        0.0       0
5861  20230215   082500    082959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-02-15 08:30:01,891:INFO:sr_min:main.py:175:handleKline:449472: self.closeSec=1676420999, self.tradeDate='20230215', self.openTime='082500', self.closeTime='082959',self.symbol='BTCUSDT',self.open=22147.9, self.close=22165.0, self.high=22169.0, self.low=22145.2, self.vol=526.085, self.amt=11655836.4855, ukdf['pct'].iloc[-1]=0.000772 , ukdf['amount'].iloc[-1]=11655836.4855, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5861, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': []}
type(curSign)=<class 'int'>, curSign=0, self.sign=0
127.0.0.1 - - [15/Feb/2023 08:35:01] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=0, self.total=1000000.0, self.flagDict['side']='', self.tradeCount=0, self.count=18973
self.closeSec=1676421299, self.tradeDate='20230215', self.openTime='083000', self.closeTime='083459', self.symbol='BTCUSDT', self.open=22165.1, self.close=22121.7, self.high=22178.0, self.low=22121.7, self.vol=1053.967, self.amt=23341624.9205 
2023-02-15 08:35:01,528:INFO:sr_min:main.py:172:handleKline:449472: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5858  20230215   081000    081459  ...         0.0        0.0       0
5859  20230215   081500    081959  ...         0.0        0.0       0
5860  20230215   082000    082459  ...         0.0        0.0       0
5861  20230215   082500    082959  ...         0.0        0.0       0
5862  20230215   083000    083459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-02-15 08:35:01,529:INFO:sr_min:main.py:175:handleKline:449472: self.closeSec=1676421299, self.tradeDate='20230215', self.openTime='083000', self.closeTime='083459',self.symbol='BTCUSDT',self.open=22165.1, self.close=22121.7, self.high=22178.0, self.low=22121.7, self.vol=1053.967, self.amt=23341624.9205, ukdf['pct'].iloc[-1]=-0.001954 , ukdf['amount'].iloc[-1]=23341624.9205, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5862, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': []}
type(curSign)=<class 'int'>, curSign=0, self.sign=0


## /root/FIL/strategy/s_rsrs/log.txt ----- -----

719  20230214   200000    235959  1676390399  ...    719  0.003743 -2.580120    -1.0
720  20230215   000000    035959  1676404799  ...    720  0.032776 -2.354771    -1.0

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '42.891', 'enterprice': '21599.9', 'countrevence': '0', 'unrealprofit': '-25794.6474', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '22201.3', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-1, self.sign=-1
127.0.0.1 - - [15/Feb/2023 08:00:02] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='s_rsrs', self.symbol='BTCUSDT', interval='4h', intervalSec=14400, wid=25, thd=0.6, self.sign=-1, self.total=925514.8695891, self.flagDict['side']='sell', self.tradeCount=19, self.count=490
self.closeSec=1676419199, self.tradeDate='20230215', self.openTime='040000', self.closeTime='075959', self.symbol='BTCUSDT', self.open=22196.8, self.close=22187.4, self.high=22275.0, self.low=22110.4, self.vol=49074.627, self.amt=1089327973.4688 
2023-02-15 08:00:02,117:INFO:s_rsrs:main.py:141:handleKline:185271: self.closeSec=1676419199, self.tradeDate='20230215', self.openTime='040000', self.closeTime='075959',self.symbol='BTCUSDT',self.open=22196.8, self.close=22187.4, self.high=22275.0, self.low=22110.4, self.vol=49074.627, self.amt=1089327973.4688 
2023-02-15 08:00:02,153:INFO:s_rsrs:main.py:142:handleKline:185271: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime  ...         vol           amt       pct
717  20230214   120000    155959  ...   24174.292  5.252535e+08  0.003139
718  20230214   160000    195959  ...   47434.581  1.032453e+09  0.001792
719  20230214   200000    235959  ...  325421.325  7.131807e+09  0.010753
720  20230215   000000    035959  ...  121281.491  2.677237e+09  0.007416
721  20230215   040000    075959  ...   49074.627  1.089328e+09 -0.000419

[5 rows x 11 columns]
2023-02-15 08:00:04,584:INFO:s_rsrs:main.py:151:handleKline:185271: df_s.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec  ...  index      beta    zscore  signal
717  20230214   120000    155959  1676361599  ...    717  0.050675 -2.624902    -1.0
718  20230214   160000    195959  1676375999  ...    718  0.055872 -2.478920    -1.0
719  20230214   200000    235959  1676390399  ...    719  0.003743 -2.580120    -1.0
720  20230215   000000    035959  1676404799  ...    720  0.032776 -2.354771    -1.0
721  20230215   040000    075959  1676419199  ...    721  0.097099 -2.015925    -1.0

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '42.891', 'enterprice': '21599.9', 'countrevence': '0', 'unrealprofit': '-25286.19766735563', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '22189.44553793', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-1, self.sign=-1


