# 20230316 08:26:01

## /root/FIL/strategy/amihud/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=993672.4896432, self.flagDict['side']='sell', self.tradeCount=2, self.count=31324
self.closeSec=1678925999, self.tradeDate='20230316', self.openTime='081500', self.closeTime='081959', self.symbol='BTCUSDT', self.open=24280.5, self.close=24325.9, self.high=24340.0, self.low=24280.4, self.vol=1627.396, self.amt=39566080.1397 
127.0.0.1 - - [16/Mar/2023 08:20:01] "POST / HTTP/1.1" 200 -
2023-03-16 08:20:03,456:INFO:amihud:main.py:172:handleKline:200676: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5855  20230316   075500    075959  ...         0.0        0.0       0
5856  20230316   080000    080459  ...         0.0        0.0       0
5857  20230316   080500    080959  ...         0.0        0.0       0
5858  20230316   081000    081459  ...         0.0        0.0       0
5859  20230316   081500    081959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-03-16 08:20:03,475:INFO:amihud:main.py:175:handleKline:200676: self.closeSec=1678925999, self.tradeDate='20230316', self.openTime='081500', self.closeTime='081959',self.symbol='BTCUSDT',self.open=24280.5, self.close=24325.9, self.high=24340.0, self.low=24280.4, self.vol=1627.396, self.amt=39566080.1397, ukdf['pct'].iloc[-1]=0.001874 , ukdf['amount'].iloc[-1]=39566080.1397, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5859, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '60.176', 'enterprice': '16529.3', 'countrevence': '0', 'unrealprofit': '-469727.8384', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '24335.2', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1
127.0.0.1 - - [16/Mar/2023 08:25:01] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=993672.4896432, self.flagDict['side']='sell', self.tradeCount=2, self.count=31325
self.closeSec=1678926299, self.tradeDate='20230316', self.openTime='082000', self.closeTime='082459', self.symbol='BTCUSDT', self.open=24329.4, self.close=24366.0, self.high=24383.9, self.low=24329.3, self.vol=1899.804, self.amt=46277566.3797 
2023-03-16 08:25:01,872:INFO:amihud:main.py:172:handleKline:200676: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5856  20230316   080000    080459  ...         0.0        0.0       0
5857  20230316   080500    080959  ...         0.0        0.0       0
5858  20230316   081000    081459  ...         0.0        0.0       0
5859  20230316   081500    081959  ...         0.0        0.0       0
5860  20230316   082000    082459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-03-16 08:25:01,872:INFO:amihud:main.py:175:handleKline:200676: self.closeSec=1678926299, self.tradeDate='20230316', self.openTime='082000', self.closeTime='082459',self.symbol='BTCUSDT',self.open=24329.4, self.close=24366.0, self.high=24383.9, self.low=24329.3, self.vol=1899.804, self.amt=46277566.3797, ukdf['pct'].iloc[-1]=0.001648 , ukdf['amount'].iloc[-1]=46277566.3797, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5860, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '60.176', 'enterprice': '16529.3', 'countrevence': '0', 'unrealprofit': '-471565.40540434688', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '24365.73654288', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1


## /root/FIL/strategy/factorcheck/log.txt ----- -----


self.closeSec=1678925999, self.tradeDate='20230316', self.openTime='081500', self.closeTime='081959', self.symbol='BTCUSDT', self.open=24280.5, self.close=24325.9, self.high=24340.0, self.low=24280.4 
127.0.0.1 - - [16/Mar/2023 08:20:01] "POST / HTTP/1.1" 200 -
2023-03-16 08:20:02,914:INFO:factorcheck2:main.py:126:handleKline:185239: self.closeSec=1678925999, self.tradeDate='20230316', self.openTime='081500', self.closeTime='081959',self.symbol='BTCUSDT',self.open=24280.5, self.close=24325.9, self.high=24340.0, self.low=24280.4   
2023-03-16 08:20:03,424:INFO:factorcheck2:main.py:127:handleKline:185239: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1535  20230316   075500    075959  1678924799  ...  24222.6  0.000507   1535    5
1536  20230316   080000    080459  1678925099  ...  24254.0  0.001548   1536    0
1537  20230316   080500    080959  1678925399  ...  24269.7 -0.002183   1537    1
1538  20230316   081000    081459  1678925699  ...  24200.2  0.000325   1538    2
1539  20230316   081500    081959  1678925999  ...  24280.4  0.001874   1539    3

[5 rows x 11 columns]
2023-03-16 08:20:03,425:INFO:factorcheck2:main.py:128:handleKline:185239: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}
127.0.0.1 - - [16/Mar/2023 08:25:01] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=151, self.factor=0.5833358419841966, self.count=31891 

self.closeSec=1678926299, self.tradeDate='20230316', self.openTime='082000', self.closeTime='082459', self.symbol='BTCUSDT', self.open=24329.4, self.close=24366.0, self.high=24383.9, self.low=24329.3 
2023-03-16 08:25:01,765:INFO:factorcheck2:main.py:126:handleKline:185239: self.closeSec=1678926299, self.tradeDate='20230316', self.openTime='082000', self.closeTime='082459',self.symbol='BTCUSDT',self.open=24329.4, self.close=24366.0, self.high=24383.9, self.low=24329.3   
2023-03-16 08:25:01,844:INFO:factorcheck2:main.py:127:handleKline:185239: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1536  20230316   080000    080459  1678925099  ...  24254.0  0.001548   1536    0
1537  20230316   080500    080959  1678925399  ...  24269.7 -0.002183   1537    1
1538  20230316   081000    081459  1678925699  ...  24200.2  0.000325   1538    2
1539  20230316   081500    081959  1678925999  ...  24280.4  0.001874   1539    3
1540  20230316   082000    082459  1678926299  ...  24329.3  0.001648   1540    4

[5 rows x 11 columns]
2023-03-16 08:25:01,844:INFO:factorcheck2:main.py:128:handleKline:185239: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}


## /root/FIL/strategy/logic/log.txt ----- -----

2023-03-16 08:00:34,452:DEBUG:logic:main.py:463:getModel:885513: df_s.iloc[-5:,:] :
          date closeTime     open  ...    alpha58   alpha67   alpha72
5770  20230316    052959  24326.2  ...  53.750000  0.502503  0.624436
5771  20230316    055959  24318.2  ...  53.750000  0.511557  0.622090
5772  20230316    062959  24427.0  ...  53.750000  0.514652  0.618001
5773  20230316    065959  24464.2  ...  53.750000  0.505768  0.619347
5774  20230316    072959  24362.7  ...  53.333333  0.505444  0.620790

[5 rows x 33 columns]
0.5545286506469501
acc is : 0.5545286506469501
2023-03-16 08:00:34,614:INFO:logic:main.py:468:getModel:885513: df_pred.iloc[-5:,:] :
     pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
536     0  0.506443  0.493557       1  ...  1.101379   1.0    0.0  1.094950
537     0  0.556059  0.443941       1  ...  1.103065   1.0    0.0  1.096626
538     0  0.543936  0.456064       0  ...  1.098484   1.0    0.0  1.092072
539     1  0.490378  0.509622       0  ...  1.098317   1.0    0.0  1.091906
540     0  0.524266  0.475734       0  ...  1.095116   1.0    0.0  1.088723

[5 rows x 10 columns]
2023-03-16 08:00:34,642:INFO:logic:main.py:478:getModel:885513: df_panel.iloc[-5:,:] :
    pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
45     0  0.506617  0.493383       1  ...  1.101379   1.0    0.0  1.095067
46     0  0.556153  0.443847       1  ...  1.103065   1.0    0.0  1.096292
47     0  0.544131  0.455869       0  ...  1.098484   1.0    0.0  1.091778
48     1  0.490790  0.509210       0  ...  1.098317   1.0    0.0  1.091906
49     0  0.524266  0.475734       0  ...  1.095116   1.0    0.0  1.088723

[5 rows x 10 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': []}


## /root/FIL/strategy/modifiedmom/log.txt ----- -----

623  20230316   075000    075959  1678924799  24314.4    24288 -0.001086
2023-03-16 08:00:02,347:INFO:modifiedmom:main.py:146:handleKline:185213: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=15944 

self.closeSec=1678925399, self.tradeDate='20230316', self.openTime='080000', self.closeTime='080959', self.symbol='BTCUSDT', self.open='24287.9', self.close='24272.5'
2023-03-16 08:10:01,640:INFO:modifiedmom:main.py:144:handleKline:185213: self.closeSec=1678925399, self.tradeDate='20230316', self.openTime='080000', self.closeTime='080959',self.symbol='BTCUSDT',self.open='24287.9', self.close='24272.5'
127.0.0.1 - - [16/Mar/2023 08:10:01] "POST / HTTP/1.1" 200 -
2023-03-16 08:10:01,657:INFO:modifiedmom:main.py:145:handleKline:185213: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
620  20230316   072000    072959  1678922999  24357.1    24359  0.000082
621  20230316   073000    073959  1678923599    24359  24329.8 -0.001199
622  20230316   074000    074959  1678924199  24329.8  24314.4 -0.000633
623  20230316   075000    075959  1678924799  24314.4    24288 -0.001086
624  20230316   080000    080959  1678925399  24287.9  24272.5 -0.000638
2023-03-16 08:10:01,657:INFO:modifiedmom:main.py:146:handleKline:185213: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=15945 

self.closeSec=1678925999, self.tradeDate='20230316', self.openTime='081000', self.closeTime='081959', self.symbol='BTCUSDT', self.open='24272.6', self.close='24325.9'
127.0.0.1 - - [16/Mar/2023 08:20:01] "POST / HTTP/1.1" 200 -
2023-03-16 08:20:03,335:INFO:modifiedmom:main.py:144:handleKline:185213: self.closeSec=1678925999, self.tradeDate='20230316', self.openTime='081000', self.closeTime='081959',self.symbol='BTCUSDT',self.open='24272.6', self.close='24325.9'
2023-03-16 08:20:03,667:INFO:modifiedmom:main.py:145:handleKline:185213: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
621  20230316   073000    073959  1678923599    24359  24329.8 -0.001199
622  20230316   074000    074959  1678924199  24329.8  24314.4 -0.000633
623  20230316   075000    075959  1678924799  24314.4    24288 -0.001086
624  20230316   080000    080959  1678925399  24287.9  24272.5 -0.000638
625  20230316   081000    081959  1678925999  24272.6  24325.9  0.002200
2023-03-16 08:20:03,667:INFO:modifiedmom:main.py:146:handleKline:185213: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False}


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

17471  20230316   075000    075959  1678924799  24314.4    24288
2023-03-16 08:00:02,334:INFO:pyemd2:main.py:127:handleKline:185189: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}
127.0.0.1 - - [16/Mar/2023 08:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=15945 

self.closeSec=1678925399, self.tradeDate='20230316', self.openTime='080000', self.closeTime='080959', self.symbol='BTCUSDT', self.open='24287.9', self.close='24272.5'
2023-03-16 08:10:01,573:INFO:pyemd2:main.py:125:handleKline:185189: self.closeSec=1678925399, self.tradeDate='20230316', self.openTime='080000', self.closeTime='080959',self.symbol='BTCUSDT',self.open='24287.9', self.close='24272.5'
2023-03-16 08:10:01,609:INFO:pyemd2:main.py:126:handleKline:185189: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17468  20230316   072000    072959  1678922999  24357.1    24359
17469  20230316   073000    073959  1678923599    24359  24329.8
17470  20230316   074000    074959  1678924199  24329.8  24314.4
17471  20230316   075000    075959  1678924799  24314.4    24288
17472  20230316   080000    080959  1678925399  24287.9  24272.5
2023-03-16 08:10:01,609:INFO:pyemd2:main.py:127:handleKline:185189: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=15946 

self.closeSec=1678925999, self.tradeDate='20230316', self.openTime='081000', self.closeTime='081959', self.symbol='BTCUSDT', self.open='24272.6', self.close='24325.9'
127.0.0.1 - - [16/Mar/2023 08:20:02] "POST / HTTP/1.1" 200 -
2023-03-16 08:20:04,427:INFO:pyemd2:main.py:125:handleKline:185189: self.closeSec=1678925999, self.tradeDate='20230316', self.openTime='081000', self.closeTime='081959',self.symbol='BTCUSDT',self.open='24272.6', self.close='24325.9'
2023-03-16 08:20:04,561:INFO:pyemd2:main.py:126:handleKline:185189: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17469  20230316   073000    073959  1678923599    24359  24329.8
17470  20230316   074000    074959  1678924199  24329.8  24314.4
17471  20230316   075000    075959  1678924799  24314.4    24288
17472  20230316   080000    080959  1678925399  24287.9  24272.5
17473  20230316   081000    081959  1678925999  24272.6  24325.9
2023-03-16 08:20:04,562:INFO:pyemd2:main.py:127:handleKline:185189: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}


## /root/FIL/strategy/similarity/log.txt ----- -----

12143  20230316   075000    075959  1678924799  24314.4    24288
2023-03-16 08:00:02,373:INFO:testStrategy:main.py:103:handleKline:185174: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}
127.0.0.1 - - [16/Mar/2023 08:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=15945 

self.closeSec=1678925399, self.tradeDate='20230316', self.openTime='080000', self.closeTime='080959', self.symbol='BTCUSDT', self.open='24287.9', self.close='24272.5'
2023-03-16 08:10:01,604:INFO:testStrategy:main.py:101:handleKline:185174: self.closeSec=1678925399, self.tradeDate='20230316', self.openTime='080000', self.closeTime='080959',self.symbol='BTCUSDT',self.open='24287.9', self.close='24272.5'
2023-03-16 08:10:01,643:INFO:testStrategy:main.py:102:handleKline:185174: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12140  20230316   072000    072959  1678922999  24357.1    24359
12141  20230316   073000    073959  1678923599    24359  24329.8
12142  20230316   074000    074959  1678924199  24329.8  24314.4
12143  20230316   075000    075959  1678924799  24314.4    24288
12144  20230316   080000    080959  1678925399  24287.9  24272.5
2023-03-16 08:10:01,643:INFO:testStrategy:main.py:103:handleKline:185174: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=15946 

self.closeSec=1678925999, self.tradeDate='20230316', self.openTime='081000', self.closeTime='081959', self.symbol='BTCUSDT', self.open='24272.6', self.close='24325.9'
127.0.0.1 - - [16/Mar/2023 08:20:02] "POST / HTTP/1.1" 200 -
2023-03-16 08:20:04,320:INFO:testStrategy:main.py:101:handleKline:185174: self.closeSec=1678925999, self.tradeDate='20230316', self.openTime='081000', self.closeTime='081959',self.symbol='BTCUSDT',self.open='24272.6', self.close='24325.9'
2023-03-16 08:20:04,446:INFO:testStrategy:main.py:102:handleKline:185174: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12141  20230316   073000    073959  1678923599    24359  24329.8
12142  20230316   074000    074959  1678924199  24329.8  24314.4
12143  20230316   075000    075959  1678924799  24314.4    24288
12144  20230316   080000    080959  1678925399  24287.9  24272.5
12145  20230316   081000    081959  1678925999  24272.6  24325.9
2023-03-16 08:20:04,447:INFO:testStrategy:main.py:103:handleKline:185174: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}


## /root/FIL/strategy/sr_min/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=0, self.total=1000000.0, self.flagDict['side']='', self.tradeCount=0, self.count=27322
self.closeSec=1678925999, self.tradeDate='20230316', self.openTime='081500', self.closeTime='081959', self.symbol='BTCUSDT', self.open=24280.5, self.close=24325.9, self.high=24340.0, self.low=24280.4, self.vol=1627.396, self.amt=39566080.1397 
127.0.0.1 - - [16/Mar/2023 08:20:01] "POST / HTTP/1.1" 200 -
2023-03-16 08:20:01,601:INFO:sr_min:main.py:172:handleKline:449472: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5855  20230316   075500    075959  ...         0.0        0.0       0
5856  20230316   080000    080459  ...         0.0        0.0       0
5857  20230316   080500    080959  ...         0.0        0.0       0
5858  20230316   081000    081459  ...         0.0        0.0       0
5859  20230316   081500    081959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-03-16 08:20:01,604:INFO:sr_min:main.py:175:handleKline:449472: self.closeSec=1678925999, self.tradeDate='20230316', self.openTime='081500', self.closeTime='081959',self.symbol='BTCUSDT',self.open=24280.5, self.close=24325.9, self.high=24340.0, self.low=24280.4, self.vol=1627.396, self.amt=39566080.1397, ukdf['pct'].iloc[-1]=0.001874 , ukdf['amount'].iloc[-1]=39566080.1397, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5859, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': []}
type(curSign)=<class 'int'>, curSign=0, self.sign=0
127.0.0.1 - - [16/Mar/2023 08:25:01] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=0, self.total=1000000.0, self.flagDict['side']='', self.tradeCount=0, self.count=27323
self.closeSec=1678926299, self.tradeDate='20230316', self.openTime='082000', self.closeTime='082459', self.symbol='BTCUSDT', self.open=24329.4, self.close=24366.0, self.high=24383.9, self.low=24329.3, self.vol=1899.804, self.amt=46277566.3797 
2023-03-16 08:25:01,865:INFO:sr_min:main.py:172:handleKline:449472: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5856  20230316   080000    080459  ...         0.0        0.0       0
5857  20230316   080500    080959  ...         0.0        0.0       0
5858  20230316   081000    081459  ...         0.0        0.0       0
5859  20230316   081500    081959  ...         0.0        0.0       0
5860  20230316   082000    082459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-03-16 08:25:01,873:INFO:sr_min:main.py:175:handleKline:449472: self.closeSec=1678926299, self.tradeDate='20230316', self.openTime='082000', self.closeTime='082459',self.symbol='BTCUSDT',self.open=24329.4, self.close=24366.0, self.high=24383.9, self.low=24329.3, self.vol=1899.804, self.amt=46277566.3797, ukdf['pct'].iloc[-1]=0.001648 , ukdf['amount'].iloc[-1]=46277566.3797, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5860, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': []}
type(curSign)=<class 'int'>, curSign=0, self.sign=0


## /root/FIL/strategy/s_rsrs/log.txt ----- -----

719  20230315   200000    235959  1678895999  ...    719  1.137514  1.631562     1.0
720  20230316   000000    035959  1678910399  ...    720  1.098944  1.476941     1.0

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '55.825', 'enterprice': '20070', 'countrevence': '0', 'unrealprofit': '239271.5325', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '24356.1', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=1, self.sign=1
--handleKline--:  version='2.0.0', self.name='s_rsrs', self.symbol='BTCUSDT', interval='4h', intervalSec=14400, wid=25, thd=0.6, self.sign=1, self.total=1119287.34225, self.flagDict['side']='buy', self.tradeCount=24, self.count=664
self.closeSec=1678924799, self.tradeDate='20230316', self.openTime='040000', self.closeTime='075959', self.symbol='BTCUSDT', self.open=24379.8, self.close=24288.0, self.high=24645.4, self.low=24222.6, self.vol=78584.034, self.amt=1916961360.43485 
127.0.0.1 - - [16/Mar/2023 08:00:02] "POST / HTTP/1.1" 200 -
2023-03-16 08:00:02,069:INFO:s_rsrs:main.py:141:handleKline:185271: self.closeSec=1678924799, self.tradeDate='20230316', self.openTime='040000', self.closeTime='075959',self.symbol='BTCUSDT',self.open=24379.8, self.close=24288.0, self.high=24645.4, self.low=24222.6, self.vol=78584.034, self.amt=1916961360.43485 
2023-03-16 08:00:02,101:INFO:s_rsrs:main.py:142:handleKline:185271: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime  ...         vol           amt       pct
717  20230315   120000    155959  ...   66779.179  1.654865e+09  0.006079
718  20230315   160000    195959  ...  173691.809  4.270609e+09 -0.004395
719  20230315   200000    235959  ...  376951.657  9.340376e+09 -0.012206
720  20230316   000000    035959  ...  279276.742  6.776350e+09 -0.004097
721  20230316   040000    075959  ...   78584.034  1.916961e+09 -0.003765

[5 rows x 11 columns]
2023-03-16 08:00:04,319:INFO:s_rsrs:main.py:151:handleKline:185271: df_s.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec  ...  index      beta    zscore  signal
717  20230315   120000    155959  1678867199  ...    717  1.161865  1.800504     1.0
718  20230315   160000    195959  1678881599  ...    718  1.150130  1.715110     1.0
719  20230315   200000    235959  1678895999  ...    719  1.137514  1.631562     1.0
720  20230316   000000    035959  1678910399  ...    720  1.098944  1.476941     1.0
721  20230316   040000    075959  1678924799  ...    721  1.054196  1.316485     1.0

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '55.825', 'enterprice': '20070', 'countrevence': '0', 'unrealprofit': '235425.48253360675', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '24287.20524019', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=1, self.sign=1


