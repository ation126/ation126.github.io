# 20230327 08:26:01

## /root/FIL/strategy/amihud/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=993672.4896432, self.flagDict['side']='sell', self.tradeCount=2, self.count=34492
self.closeSec=1679876399, self.tradeDate='20230327', self.openTime='081500', self.closeTime='081959', self.symbol='BTCUSDT', self.open=27918.9, self.close=27934.5, self.high=27943.0, self.low=27918.7, self.vol=824.51, self.amt=23031028.7016 
127.0.0.1 - - [27/Mar/2023 08:20:04] "POST / HTTP/1.1" 200 -
2023-03-27 08:20:08,683:INFO:amihud:main.py:172:handleKline:200676: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5855  20230327   075500    075959  ...         0.0        0.0       0
5856  20230327   080000    080459  ...         0.0        0.0       0
5857  20230327   080500    080959  ...         0.0        0.0       0
5858  20230327   081000    081459  ...         0.0        0.0       0
5859  20230327   081500    081959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-03-27 08:20:08,702:INFO:amihud:main.py:175:handleKline:200676: self.closeSec=1679876399, self.tradeDate='20230327', self.openTime='081500', self.closeTime='081959',self.symbol='BTCUSDT',self.open=27918.9, self.close=27934.5, self.high=27943.0, self.low=27918.7, self.vol=824.51, self.amt=23031028.7016, ukdf['pct'].iloc[-1]=0.000559 , ukdf['amount'].iloc[-1]=23031028.7016, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5859, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '60.176', 'enterprice': '16529.3', 'countrevence': '0', 'unrealprofit': '-686433.6496', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '27936.4', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1
127.0.0.1 - - [27/Mar/2023 08:25:01] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=993672.4896432, self.flagDict['side']='sell', self.tradeCount=2, self.count=34493
self.closeSec=1679876699, self.tradeDate='20230327', self.openTime='082000', self.closeTime='082459', self.symbol='BTCUSDT', self.open=27934.4, self.close=27935.7, self.high=27955.9, self.low=27930.8, self.vol=769.106, self.amt=21491587.0004 
2023-03-27 08:25:01,616:INFO:amihud:main.py:172:handleKline:200676: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5856  20230327   080000    080459  ...         0.0        0.0       0
5857  20230327   080500    080959  ...         0.0        0.0       0
5858  20230327   081000    081459  ...         0.0        0.0       0
5859  20230327   081500    081959  ...         0.0        0.0       0
5860  20230327   082000    082459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-03-27 08:25:01,616:INFO:amihud:main.py:175:handleKline:200676: self.closeSec=1679876699, self.tradeDate='20230327', self.openTime='082000', self.closeTime='082459',self.symbol='BTCUSDT',self.open=27934.4, self.close=27935.7, self.high=27955.9, self.low=27930.8, self.vol=769.106, self.amt=21491587.0004, ukdf['pct'].iloc[-1]=4.3e-05 , ukdf['amount'].iloc[-1]=21491587.0004, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5860, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '60.176', 'enterprice': '16529.3', 'countrevence': '0', 'unrealprofit': '-686613.352090588', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '27939.38628175', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1


## /root/FIL/strategy/factorcheck/log.txt ----- -----


self.closeSec=1679876399, self.tradeDate='20230327', self.openTime='081500', self.closeTime='081959', self.symbol='BTCUSDT', self.open=27918.9, self.close=27934.5, self.high=27943.0, self.low=27918.7 
127.0.0.1 - - [27/Mar/2023 08:20:04] "POST / HTTP/1.1" 200 -
2023-03-27 08:20:06,963:INFO:factorcheck2:main.py:126:handleKline:185239: self.closeSec=1679876399, self.tradeDate='20230327', self.openTime='081500', self.closeTime='081959',self.symbol='BTCUSDT',self.open=27918.9, self.close=27934.5, self.high=27943.0, self.low=27918.7   
2023-03-27 08:20:07,723:INFO:factorcheck2:main.py:127:handleKline:185239: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1535  20230327   075500    075959  1679875199  ...  27931.5 -0.000483   1535    5
1536  20230327   080000    080459  1679875499  ...  27935.6  0.000061   1536    0
1537  20230327   080500    080959  1679875799  ...  27930.9 -0.000486   1537    1
1538  20230327   081000    081459  1679876099  ...  27917.5 -0.000841   1538    2
1539  20230327   081500    081959  1679876399  ...  27918.7  0.000559   1539    3

[5 rows x 11 columns]
2023-03-27 08:20:07,732:INFO:factorcheck2:main.py:128:handleKline:185239: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=460, self.factor=0.42139861508386023, self.count=35059 

self.closeSec=1679876699, self.tradeDate='20230327', self.openTime='082000', self.closeTime='082459', self.symbol='BTCUSDT', self.open=27934.4, self.close=27935.7, self.high=27955.9, self.low=27930.8 
127.0.0.1 - - [27/Mar/2023 08:25:01] "POST / HTTP/1.1" 200 -
2023-03-27 08:25:01,514:INFO:factorcheck2:main.py:126:handleKline:185239: self.closeSec=1679876699, self.tradeDate='20230327', self.openTime='082000', self.closeTime='082459',self.symbol='BTCUSDT',self.open=27934.4, self.close=27935.7, self.high=27955.9, self.low=27930.8   
2023-03-27 08:25:01,578:INFO:factorcheck2:main.py:127:handleKline:185239: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1536  20230327   080000    080459  1679875499  ...  27935.6  0.000061   1536    0
1537  20230327   080500    080959  1679875799  ...  27930.9 -0.000486   1537    1
1538  20230327   081000    081459  1679876099  ...  27917.5 -0.000841   1538    2
1539  20230327   081500    081959  1679876399  ...  27918.7  0.000559   1539    3
1540  20230327   082000    082459  1679876699  ...  27930.8  0.000043   1540    4

[5 rows x 11 columns]
2023-03-27 08:25:01,579:INFO:factorcheck2:main.py:128:handleKline:185239: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}


## /root/FIL/strategy/logic/log.txt ----- -----

2023-03-27 08:00:32,592:DEBUG:logic:main.py:463:getModel:885513: df_s.iloc[-5:,:] :
          date closeTime     open  ...    alpha58   alpha67   alpha72
5770  20230327    052959  27761.3  ...  50.000000  0.519851  0.412467
5771  20230327    055959  27788.4  ...  50.416667  0.525493  0.417602
5772  20230327    062959  27823.7  ...  50.416667  0.549377  0.408418
5773  20230327    065959  27979.2  ...  50.416667  0.556477  0.395490
5774  20230327    072959  28027.7  ...  50.416667  0.557753  0.382642

[5 rows x 33 columns]
0.5175600739371534
acc is : 0.5175600739371534
2023-03-27 08:00:32,750:INFO:logic:main.py:468:getModel:885513: df_pred.iloc[-5:,:] :
     pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
536     0  0.534410  0.465590       1  ...  1.029217   1.0    0.0  1.142320
537     0  0.541129  0.458871       1  ...  1.034973   1.0    0.0  1.148708
538     0  0.575769  0.424231       1  ...  1.036767   1.0    0.0  1.150699
539     0  0.553800  0.446200       1  ...  1.037089   1.0    0.0  1.151057
540     0  0.548524  0.451476       0  ...  1.034052   1.0    0.0  1.147686

[5 rows x 10 columns]
2023-03-27 08:00:32,781:INFO:logic:main.py:478:getModel:885513: df_panel.iloc[-5:,:] :
    pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
45     0  0.533814  0.466186       1  ...  1.068568   1.0    0.0  1.136580
46     0  0.541079  0.458921       1  ...  1.027300   1.0    0.0  1.150574
47     0  0.575798  0.424202       1  ...  1.054620   1.0    0.0  1.162155
48     0  0.553800  0.446200       1  ...  1.037089   1.0    0.0  1.151057
49     0  0.548524  0.451476       0  ...  1.034052   1.0    0.0  1.147686

[5 rows x 10 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': []}


## /root/FIL/strategy/modifiedmom/log.txt ----- -----

623  20230327   075000    075959  1679875199  27968.9  27954.3 -0.000522
2023-03-27 08:00:01,903:INFO:modifiedmom:main.py:146:handleKline:185213: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False}
127.0.0.1 - - [27/Mar/2023 08:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=17528 

self.closeSec=1679875799, self.tradeDate='20230327', self.openTime='080000', self.closeTime='080959', self.symbol='BTCUSDT', self.open='27954.3', self.close='27942.4'
2023-03-27 08:10:01,597:INFO:modifiedmom:main.py:144:handleKline:185213: self.closeSec=1679875799, self.tradeDate='20230327', self.openTime='080000', self.closeTime='080959',self.symbol='BTCUSDT',self.open='27954.3', self.close='27942.4'
2023-03-27 08:10:01,646:INFO:modifiedmom:main.py:145:handleKline:185213: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
620  20230327   072000    072959  1679873399  28096.6  28036.4 -0.002143
621  20230327   073000    073959  1679873999  28036.4  28026.2 -0.000364
622  20230327   074000    074959  1679874599  28025.7  27968.9 -0.002045
623  20230327   075000    075959  1679875199  27968.9  27954.3 -0.000522
624  20230327   080000    080959  1679875799  27954.3  27942.4 -0.000426
2023-03-27 08:10:01,646:INFO:modifiedmom:main.py:146:handleKline:185213: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=17529 

self.closeSec=1679876399, self.tradeDate='20230327', self.openTime='081000', self.closeTime='081959', self.symbol='BTCUSDT', self.open='27942.4', self.close='27934.5'
127.0.0.1 - - [27/Mar/2023 08:20:05] "POST / HTTP/1.1" 200 -
2023-03-27 08:20:07,923:INFO:modifiedmom:main.py:144:handleKline:185213: self.closeSec=1679876399, self.tradeDate='20230327', self.openTime='081000', self.closeTime='081959',self.symbol='BTCUSDT',self.open='27942.4', self.close='27934.5'
2023-03-27 08:20:08,572:INFO:modifiedmom:main.py:145:handleKline:185213: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
621  20230327   073000    073959  1679873999  28036.4  28026.2 -0.000364
622  20230327   074000    074959  1679874599  28025.7  27968.9 -0.002045
623  20230327   075000    075959  1679875199  27968.9  27954.3 -0.000522
624  20230327   080000    080959  1679875799  27954.3  27942.4 -0.000426
625  20230327   081000    081959  1679876399  27942.4  27934.5 -0.000283
2023-03-27 08:20:08,573:INFO:modifiedmom:main.py:146:handleKline:185213: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False}


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

17471  20230327   075000    075959  1679875199  27968.9  27954.3
2023-03-27 08:00:01,921:INFO:pyemd2:main.py:127:handleKline:185189: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}
127.0.0.1 - - [27/Mar/2023 08:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=17529 

self.closeSec=1679875799, self.tradeDate='20230327', self.openTime='080000', self.closeTime='080959', self.symbol='BTCUSDT', self.open='27954.3', self.close='27942.4'
2023-03-27 08:10:01,625:INFO:pyemd2:main.py:125:handleKline:185189: self.closeSec=1679875799, self.tradeDate='20230327', self.openTime='080000', self.closeTime='080959',self.symbol='BTCUSDT',self.open='27954.3', self.close='27942.4'
2023-03-27 08:10:01,654:INFO:pyemd2:main.py:126:handleKline:185189: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17468  20230327   072000    072959  1679873399  28096.6  28036.4
17469  20230327   073000    073959  1679873999  28036.4  28026.2
17470  20230327   074000    074959  1679874599  28025.7  27968.9
17471  20230327   075000    075959  1679875199  27968.9  27954.3
17472  20230327   080000    080959  1679875799  27954.3  27942.4
2023-03-27 08:10:01,655:INFO:pyemd2:main.py:127:handleKline:185189: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=17530 

self.closeSec=1679876399, self.tradeDate='20230327', self.openTime='081000', self.closeTime='081959', self.symbol='BTCUSDT', self.open='27942.4', self.close='27934.5'
127.0.0.1 - - [27/Mar/2023 08:20:05] "POST / HTTP/1.1" 200 -
2023-03-27 08:20:10,535:INFO:pyemd2:main.py:125:handleKline:185189: self.closeSec=1679876399, self.tradeDate='20230327', self.openTime='081000', self.closeTime='081959',self.symbol='BTCUSDT',self.open='27942.4', self.close='27934.5'
2023-03-27 08:20:10,671:INFO:pyemd2:main.py:126:handleKline:185189: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17469  20230327   073000    073959  1679873999  28036.4  28026.2
17470  20230327   074000    074959  1679874599  28025.7  27968.9
17471  20230327   075000    075959  1679875199  27968.9  27954.3
17472  20230327   080000    080959  1679875799  27954.3  27942.4
17473  20230327   081000    081959  1679876399  27942.4  27934.5
2023-03-27 08:20:10,672:INFO:pyemd2:main.py:127:handleKline:185189: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}


## /root/FIL/strategy/similarity/log.txt ----- -----

12143  20230327   075000    075959  1679875199  27968.9  27954.3
2023-03-27 08:00:01,914:INFO:testStrategy:main.py:103:handleKline:185174: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': True, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}
127.0.0.1 - - [27/Mar/2023 08:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=17529 

self.closeSec=1679875799, self.tradeDate='20230327', self.openTime='080000', self.closeTime='080959', self.symbol='BTCUSDT', self.open='27954.3', self.close='27942.4'
2023-03-27 08:10:01,624:INFO:testStrategy:main.py:101:handleKline:185174: self.closeSec=1679875799, self.tradeDate='20230327', self.openTime='080000', self.closeTime='080959',self.symbol='BTCUSDT',self.open='27954.3', self.close='27942.4'
2023-03-27 08:10:01,651:INFO:testStrategy:main.py:102:handleKline:185174: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12140  20230327   072000    072959  1679873399  28096.6  28036.4
12141  20230327   073000    073959  1679873999  28036.4  28026.2
12142  20230327   074000    074959  1679874599  28025.7  27968.9
12143  20230327   075000    075959  1679875199  27968.9  27954.3
12144  20230327   080000    080959  1679875799  27954.3  27942.4
2023-03-27 08:10:01,653:INFO:testStrategy:main.py:103:handleKline:185174: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': True, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=17530 

self.closeSec=1679876399, self.tradeDate='20230327', self.openTime='081000', self.closeTime='081959', self.symbol='BTCUSDT', self.open='27942.4', self.close='27934.5'
127.0.0.1 - - [27/Mar/2023 08:20:05] "POST / HTTP/1.1" 200 -
2023-03-27 08:20:10,034:INFO:testStrategy:main.py:101:handleKline:185174: self.closeSec=1679876399, self.tradeDate='20230327', self.openTime='081000', self.closeTime='081959',self.symbol='BTCUSDT',self.open='27942.4', self.close='27934.5'
2023-03-27 08:20:10,335:INFO:testStrategy:main.py:102:handleKline:185174: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12141  20230327   073000    073959  1679873999  28036.4  28026.2
12142  20230327   074000    074959  1679874599  28025.7  27968.9
12143  20230327   075000    075959  1679875199  27968.9  27954.3
12144  20230327   080000    080959  1679875799  27954.3  27942.4
12145  20230327   081000    081959  1679876399  27942.4  27934.5
2023-03-27 08:20:10,342:INFO:testStrategy:main.py:103:handleKline:185174: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': True, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}


## /root/FIL/strategy/sr_min/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=0, self.total=1000000.0, self.flagDict['side']='', self.tradeCount=0, self.count=30490
self.closeSec=1679876399, self.tradeDate='20230327', self.openTime='081500', self.closeTime='081959', self.symbol='BTCUSDT', self.open=27918.9, self.close=27934.5, self.high=27943.0, self.low=27918.7, self.vol=824.51, self.amt=23031028.7016 
127.0.0.1 - - [27/Mar/2023 08:20:02] "POST / HTTP/1.1" 200 -
2023-03-27 08:20:05,513:INFO:sr_min:main.py:172:handleKline:449472: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5855  20230327   075500    075959  ...         0.0        0.0       0
5856  20230327   080000    080459  ...         0.0        0.0       0
5857  20230327   080500    080959  ...         0.0        0.0       0
5858  20230327   081000    081459  ...         0.0        0.0       0
5859  20230327   081500    081959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-03-27 08:20:05,553:INFO:sr_min:main.py:175:handleKline:449472: self.closeSec=1679876399, self.tradeDate='20230327', self.openTime='081500', self.closeTime='081959',self.symbol='BTCUSDT',self.open=27918.9, self.close=27934.5, self.high=27943.0, self.low=27918.7, self.vol=824.51, self.amt=23031028.7016, ukdf['pct'].iloc[-1]=0.000559 , ukdf['amount'].iloc[-1]=23031028.7016, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5859, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': []}
type(curSign)=<class 'int'>, curSign=0, self.sign=0
--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=0, self.total=1000000.0, self.flagDict['side']='', self.tradeCount=0, self.count=30491
self.closeSec=1679876699, self.tradeDate='20230327', self.openTime='082000', self.closeTime='082459', self.symbol='BTCUSDT', self.open=27934.4, self.close=27935.7, self.high=27955.9, self.low=27930.8, self.vol=769.106, self.amt=21491587.0004 
127.0.0.1 - - [27/Mar/2023 08:25:01] "POST / HTTP/1.1" 200 -
2023-03-27 08:25:01,597:INFO:sr_min:main.py:172:handleKline:449472: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5856  20230327   080000    080459  ...         0.0        0.0       0
5857  20230327   080500    080959  ...         0.0        0.0       0
5858  20230327   081000    081459  ...         0.0        0.0       0
5859  20230327   081500    081959  ...         0.0        0.0       0
5860  20230327   082000    082459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-03-27 08:25:01,601:INFO:sr_min:main.py:175:handleKline:449472: self.closeSec=1679876699, self.tradeDate='20230327', self.openTime='082000', self.closeTime='082459',self.symbol='BTCUSDT',self.open=27934.4, self.close=27935.7, self.high=27955.9, self.low=27930.8, self.vol=769.106, self.amt=21491587.0004, ukdf['pct'].iloc[-1]=4.3e-05 , ukdf['amount'].iloc[-1]=21491587.0004, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5860, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': []}
type(curSign)=<class 'int'>, curSign=0, self.sign=0


## /root/FIL/strategy/s_rsrs/log.txt ----- -----

719  20230326   200000    235959  1679846399  ...    719  0.036491 -1.443176    -1.0
720  20230327   000000    035959  1679860799  ...    720  0.013753 -1.460918    -1.0

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '53.706', 'enterprice': '28091.1', 'countrevence': '0', 'unrealprofit': '14942.8391057409', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '27812.86592735', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-1, self.sign=-1
127.0.0.1 - - [27/Mar/2023 08:00:01] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='s_rsrs', self.symbol='BTCUSDT', interval='4h', intervalSec=14400, wid=25, thd=0.6, self.sign=-1, self.total=1507151.9559834, self.flagDict['side']='sell', self.tradeCount=27, self.count=730
self.closeSec=1679875199, self.tradeDate='20230327', self.openTime='040000', self.closeTime='075959', self.symbol='BTCUSDT', self.open=27814.0, self.close=27954.3, self.high=28138.3, self.low=27655.7, self.vol=67164.517, self.amt=1875762747.30362 
2023-03-27 08:00:01,787:INFO:s_rsrs:main.py:141:handleKline:185271: self.closeSec=1679875199, self.tradeDate='20230327', self.openTime='040000', self.closeTime='075959',self.symbol='BTCUSDT',self.open=27814.0, self.close=27954.3, self.high=28138.3, self.low=27655.7, self.vol=67164.517, self.amt=1875762747.30362 
2023-03-27 08:00:01,883:INFO:s_rsrs:main.py:142:handleKline:185271: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime  ...         vol           amt       pct
717  20230326   120000    155959  ...   25075.949  6.894752e+08 -0.000905
718  20230326   160000    195959  ...   73218.713  2.027381e+09  0.013084
719  20230326   200000    235959  ...  146714.908  4.094086e+09 -0.002179
720  20230327   000000    035959  ...   49048.115  1.362723e+09  0.000817
721  20230327   040000    075959  ...   67164.517  1.875763e+09  0.005041

[5 rows x 11 columns]
2023-03-27 08:00:04,245:INFO:s_rsrs:main.py:151:handleKline:185271: df_s.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec  ...  index      beta    zscore  signal
717  20230326   120000    155959  1679817599  ...    717  0.037986 -1.514059    -1.0
718  20230326   160000    195959  1679831999  ...    718  0.035285 -1.482784    -1.0
719  20230326   200000    235959  1679846399  ...    719  0.036491 -1.443176    -1.0
720  20230327   000000    035959  1679860799  ...    720  0.013753 -1.460918    -1.0
721  20230327   040000    075959  1679875199  ...    721  0.210632 -0.969475    -1.0

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '53.706', 'enterprice': '28091.1', 'countrevence': '0', 'unrealprofit': '7164.81665491212', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '27957.69187698', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-1, self.sign=-1


