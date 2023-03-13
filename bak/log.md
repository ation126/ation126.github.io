# 20230313 08:26:01

## /root/FIL/strategy/amihud/log.txt ----- -----

--handleKline--: 127.0.0.1 - - [13/Mar/2023 08:20:01] "POST / HTTP/1.1" 200 -
 version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=993672.4896432, self.flagDict['side']='sell', self.tradeCount=2, self.count=30460
self.closeSec=1678666799, self.tradeDate='20230313', self.openTime='081500', self.closeTime='081959', self.symbol='BTCUSDT', self.open=21919.9, self.close=22074.5, self.high=22083.2, self.low=21900.0, self.vol=5797.736, self.amt=127476974.9911 
2023-03-13 08:20:02,200:INFO:amihud:main.py:172:handleKline:200676: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5855  20230313   075500    075959  ...         0.0        0.0       0
5856  20230313   080000    080459  ...         0.0        0.0       0
5857  20230313   080500    080959  ...         0.0        0.0       0
5858  20230313   081000    081459  ...         0.0        0.0       0
5859  20230313   081500    081959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-03-13 08:20:02,211:INFO:amihud:main.py:175:handleKline:200676: self.closeSec=1678666799, self.tradeDate='20230313', self.openTime='081500', self.closeTime='081959',self.symbol='BTCUSDT',self.open=21919.9, self.close=22074.5, self.high=22083.2, self.low=21900.0, self.vol=5797.736, self.amt=127476974.9911, ukdf['pct'].iloc[-1]=0.007053 , ukdf['amount'].iloc[-1]=127476974.9911, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5859, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '60.176', 'enterprice': '16529.3', 'countrevence': '0', 'unrealprofit': '-333160.3819299392', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '22065.7328292', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1
--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=993672.4896432, self.flagDict['side']='sell', self.tradeCount=2, self.count=30461
self.closeSec=1678667099, self.tradeDate='20230313', self.openTime='082000', self.closeTime='082459', self.symbol='BTCUSDT', self.open=22062.8, self.close=22064.5, self.high=22269.0, self.low=21996.4, self.vol=15784.276, self.amt=349337356.2945 
127.0.0.1 - - [13/Mar/2023 08:25:01] "POST / HTTP/1.1" 200 -
2023-03-13 08:25:01,591:INFO:amihud:main.py:172:handleKline:200676: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5856  20230313   080000    080459  ...         0.0        0.0       0
5857  20230313   080500    080959  ...         0.0        0.0       0
5858  20230313   081000    081459  ...         0.0        0.0       0
5859  20230313   081500    081959  ...         0.0        0.0       0
5860  20230313   082000    082459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-03-13 08:25:01,595:INFO:amihud:main.py:175:handleKline:200676: self.closeSec=1678667099, self.tradeDate='20230313', self.openTime='082000', self.closeTime='082459',self.symbol='BTCUSDT',self.open=22062.8, self.close=22064.5, self.high=22269.0, self.low=21996.4, self.vol=15784.276, self.amt=349337356.2945, ukdf['pct'].iloc[-1]=-0.000453 , ukdf['amount'].iloc[-1]=349337356.2945, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5860, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '60.176', 'enterprice': '16529.3', 'countrevence': '0', 'unrealprofit': '-333607.94739524864', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '22073.17043664', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1


## /root/FIL/strategy/factorcheck/log.txt ----- -----


self.closeSec=1678666799, self.tradeDate='20230313', self.openTime='081500', self.closeTime='081959', self.symbol='BTCUSDT', self.open=21919.9, self.close=22074.5, self.high=22083.2, self.low=21900.0 
127.0.0.1 - - [13/Mar/2023 08:20:01] "POST / HTTP/1.1" 200 -
2023-03-13 08:20:03,141:INFO:factorcheck2:main.py:126:handleKline:185239: self.closeSec=1678666799, self.tradeDate='20230313', self.openTime='081500', self.closeTime='081959',self.symbol='BTCUSDT',self.open=21919.9, self.close=22074.5, self.high=22083.2, self.low=21900.0   
2023-03-13 08:20:04,022:INFO:factorcheck2:main.py:127:handleKline:185239: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1535  20230313   075500    075959  1678665599  ...  21928.0  0.001490   1535    5
1536  20230313   080000    080459  1678665899  ...  21962.0 -0.000887   1536    0
1537  20230313   080500    080959  1678666199  ...  21856.0 -0.002176   1537    1
1538  20230313   081000    081459  1678666499  ...  21918.0  0.000046   1538    2
1539  20230313   081500    081959  1678666799  ...  21900.0  0.007053   1539    3

[5 rows x 11 columns]
2023-03-13 08:20:04,024:INFO:factorcheck2:main.py:128:handleKline:185239: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=7, self.factor=0.3245594936493232, self.count=31027 

self.closeSec=1678667099, self.tradeDate='20230313', self.openTime='082000', self.closeTime='082459', self.symbol='BTCUSDT', self.open=22062.8, self.close=22064.5, self.high=22269.0, self.low=21996.4 
127.0.0.1 - - [13/Mar/2023 08:25:01] "POST / HTTP/1.1" 200 -
2023-03-13 08:25:01,494:INFO:factorcheck2:main.py:126:handleKline:185239: self.closeSec=1678667099, self.tradeDate='20230313', self.openTime='082000', self.closeTime='082459',self.symbol='BTCUSDT',self.open=22062.8, self.close=22064.5, self.high=22269.0, self.low=21996.4   
2023-03-13 08:25:01,537:INFO:factorcheck2:main.py:127:handleKline:185239: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1536  20230313   080000    080459  1678665899  ...  21962.0 -0.000887   1536    0
1537  20230313   080500    080959  1678666199  ...  21856.0 -0.002176   1537    1
1538  20230313   081000    081459  1678666499  ...  21918.0  0.000046   1538    2
1539  20230313   081500    081959  1678666799  ...  21900.0  0.007053   1539    3
1540  20230313   082000    082459  1678667099  ...  21996.4 -0.000453   1540    4

[5 rows x 11 columns]
2023-03-13 08:25:01,546:INFO:factorcheck2:main.py:128:handleKline:185239: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}


## /root/FIL/strategy/logic/log.txt ----- -----

2023-03-13 08:00:35,458:DEBUG:logic:main.py:463:getModel:885513: df_s.iloc[-5:,:] :
          date closeTime     open  ...  alpha58   alpha67   alpha72
5770  20230313    052959  21249.0  ...     47.5  0.610703  0.323772
5771  20230313    055959  21174.0  ...     47.5  0.621445  0.307366
5772  20230313    062959  21262.9  ...     47.5  0.674813  0.294571
5773  20230313    065959  21797.2  ...     47.5  0.656247  0.286656
5774  20230313    072959  21694.5  ...     47.5  0.669493  0.273519

[5 rows x 33 columns]
0.5619223659889094
acc is : 0.5619223659889094
2023-03-13 08:00:35,612:INFO:logic:main.py:468:getModel:885513: df_pred.iloc[-5:,:] :
     pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
536     1  0.463107  0.536893       1  ...  0.922481   1.0    0.0  0.898230
537     0  0.582786  0.417214       1  ...  0.945641   1.0    0.0  0.920781
538     0  0.810805  0.189195       0  ...  0.941086   1.0    0.0  0.916346
539     0  0.530565  0.469435       1  ...  0.947589   1.0    0.0  0.922678
540     0  0.621658  0.378342       1  ...  0.953744   1.0    0.0  0.928671

[5 rows x 10 columns]
2023-03-13 08:00:35,646:INFO:logic:main.py:478:getModel:885513: df_panel.iloc[-5:,:] :
    pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
45     1  0.463067  0.536933       1  ...  0.922481   1.0    0.0  0.897172
46     0  0.582785  0.417215       1  ...  0.945641   1.0    0.0  0.923136
47     0  0.810429  0.189571       0  ...  0.941086   1.0    0.0  0.915909
48     0  0.530529  0.469471       1  ...  0.947589   1.0    0.0  0.922678
49     0  0.621658  0.378342       1  ...  0.953744   1.0    0.0  0.928671

[5 rows x 10 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '31.155', 'enterprice': '20772.7', 'countrevence': '0', 'unrealprofit': '41173.4077040181', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '22094.26660902', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}


## /root/FIL/strategy/modifiedmom/log.txt ----- -----

623  20230313   075000    075959  1678665599  21880.6  21986.2  0.004826
2023-03-13 08:00:02,366:INFO:modifiedmom:main.py:146:handleKline:185213: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=15512 

self.closeSec=1678666199, self.tradeDate='20230313', self.openTime='080000', self.closeTime='080959', self.symbol='BTCUSDT', self.open='21986.2', self.close='21918.9'
2023-03-13 08:10:01,609:INFO:modifiedmom:main.py:144:handleKline:185213: self.closeSec=1678666199, self.tradeDate='20230313', self.openTime='080000', self.closeTime='080959',self.symbol='BTCUSDT',self.open='21986.2', self.close='21918.9'
127.0.0.1 - - [13/Mar/2023 08:10:01] "POST / HTTP/1.1" 200 -
2023-03-13 08:10:01,628:INFO:modifiedmom:main.py:145:handleKline:185213: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
620  20230313   072000    072959  1678663799  21718.5  21844.3  0.005792
621  20230313   073000    073959  1678664399  21844.2  21851.2  0.000316
622  20230313   074000    074959  1678664999  21851.1  21880.6  0.001345
623  20230313   075000    075959  1678665599  21880.6  21986.2  0.004826
624  20230313   080000    080959  1678666199  21986.2  21918.9 -0.003061
2023-03-13 08:10:01,628:INFO:modifiedmom:main.py:146:handleKline:185213: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=15513 

self.closeSec=1678666799, self.tradeDate='20230313', self.openTime='081000', self.closeTime='081959', self.symbol='BTCUSDT', self.open='21918.9', self.close='22074.5'
127.0.0.1 - - [13/Mar/2023 08:20:03] "POST / HTTP/1.1" 200 -
2023-03-13 08:20:04,479:INFO:modifiedmom:main.py:144:handleKline:185213: self.closeSec=1678666799, self.tradeDate='20230313', self.openTime='081000', self.closeTime='081959',self.symbol='BTCUSDT',self.open='21918.9', self.close='22074.5'
2023-03-13 08:20:04,830:INFO:modifiedmom:main.py:145:handleKline:185213: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
621  20230313   073000    073959  1678664399  21844.2  21851.2  0.000316
622  20230313   074000    074959  1678664999  21851.1  21880.6  0.001345
623  20230313   075000    075959  1678665599  21880.6  21986.2  0.004826
624  20230313   080000    080959  1678666199  21986.2  21918.9 -0.003061
625  20230313   081000    081959  1678666799  21918.9  22074.5  0.007099
2023-03-13 08:20:04,830:INFO:modifiedmom:main.py:146:handleKline:185213: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False}


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

17471  20230313   075000    075959  1678665599  21880.6  21986.2
2023-03-13 08:00:02,380:INFO:pyemd2:main.py:127:handleKline:185189: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=15513 

self.closeSec=1678666199, self.tradeDate='20230313', self.openTime='080000', self.closeTime='080959', self.symbol='BTCUSDT', self.open='21986.2', self.close='21918.9'
2023-03-13 08:10:01,622:INFO:pyemd2:main.py:125:handleKline:185189: self.closeSec=1678666199, self.tradeDate='20230313', self.openTime='080000', self.closeTime='080959',self.symbol='BTCUSDT',self.open='21986.2', self.close='21918.9'
127.0.0.1 - - [13/Mar/2023 08:10:01] "POST / HTTP/1.1" 200 -
2023-03-13 08:10:01,633:INFO:pyemd2:main.py:126:handleKline:185189: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17468  20230313   072000    072959  1678663799  21718.5  21844.3
17469  20230313   073000    073959  1678664399  21844.2  21851.2
17470  20230313   074000    074959  1678664999  21851.1  21880.6
17471  20230313   075000    075959  1678665599  21880.6  21986.2
17472  20230313   080000    080959  1678666199  21986.2  21918.9
2023-03-13 08:10:01,634:INFO:pyemd2:main.py:127:handleKline:185189: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=15514 

self.closeSec=1678666799, self.tradeDate='20230313', self.openTime='081000', self.closeTime='081959', self.symbol='BTCUSDT', self.open='21918.9', self.close='22074.5'
127.0.0.1 - - [13/Mar/2023 08:20:03] "POST / HTTP/1.1" 200 -
2023-03-13 08:20:05,907:INFO:pyemd2:main.py:125:handleKline:185189: self.closeSec=1678666799, self.tradeDate='20230313', self.openTime='081000', self.closeTime='081959',self.symbol='BTCUSDT',self.open='21918.9', self.close='22074.5'
2023-03-13 08:20:05,987:INFO:pyemd2:main.py:126:handleKline:185189: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17469  20230313   073000    073959  1678664399  21844.2  21851.2
17470  20230313   074000    074959  1678664999  21851.1  21880.6
17471  20230313   075000    075959  1678665599  21880.6  21986.2
17472  20230313   080000    080959  1678666199  21986.2  21918.9
17473  20230313   081000    081959  1678666799  21918.9  22074.5
2023-03-13 08:20:05,987:INFO:pyemd2:main.py:127:handleKline:185189: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}


## /root/FIL/strategy/similarity/log.txt ----- -----

12143  20230313   075000    075959  1678665599  21880.6  21986.2
2023-03-13 08:00:02,387:INFO:testStrategy:main.py:103:handleKline:185174: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=15513 

self.closeSec=1678666199, self.tradeDate='20230313', self.openTime='080000', self.closeTime='080959', self.symbol='BTCUSDT', self.open='21986.2', self.close='21918.9'
2023-03-13 08:10:01,599:INFO:testStrategy:main.py:101:handleKline:185174: self.closeSec=1678666199, self.tradeDate='20230313', self.openTime='080000', self.closeTime='080959',self.symbol='BTCUSDT',self.open='21986.2', self.close='21918.9'
127.0.0.1 - - [13/Mar/2023 08:10:01] "POST / HTTP/1.1" 200 -
2023-03-13 08:10:01,631:INFO:testStrategy:main.py:102:handleKline:185174: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12140  20230313   072000    072959  1678663799  21718.5  21844.3
12141  20230313   073000    073959  1678664399  21844.2  21851.2
12142  20230313   074000    074959  1678664999  21851.1  21880.6
12143  20230313   075000    075959  1678665599  21880.6  21986.2
12144  20230313   080000    080959  1678666199  21986.2  21918.9
2023-03-13 08:10:01,631:INFO:testStrategy:main.py:103:handleKline:185174: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=15514 

self.closeSec=1678666799, self.tradeDate='20230313', self.openTime='081000', self.closeTime='081959', self.symbol='BTCUSDT', self.open='21918.9', self.close='22074.5'
127.0.0.1 - - [13/Mar/2023 08:20:03] "POST / HTTP/1.1" 200 -
2023-03-13 08:20:05,610:INFO:testStrategy:main.py:101:handleKline:185174: self.closeSec=1678666799, self.tradeDate='20230313', self.openTime='081000', self.closeTime='081959',self.symbol='BTCUSDT',self.open='21918.9', self.close='22074.5'
2023-03-13 08:20:05,769:INFO:testStrategy:main.py:102:handleKline:185174: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12141  20230313   073000    073959  1678664399  21844.2  21851.2
12142  20230313   074000    074959  1678664999  21851.1  21880.6
12143  20230313   075000    075959  1678665599  21880.6  21986.2
12144  20230313   080000    080959  1678666199  21986.2  21918.9
12145  20230313   081000    081959  1678666799  21918.9  22074.5
2023-03-13 08:20:05,769:INFO:testStrategy:main.py:103:handleKline:185174: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}


## /root/FIL/strategy/sr_min/log.txt ----- -----

127.0.0.1 - - [13/Mar/2023 08:20:01] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=0, self.total=1000000.0, self.flagDict['side']='', self.tradeCount=0, self.count=26458
self.closeSec=1678666799, self.tradeDate='20230313', self.openTime='081500', self.closeTime='081959', self.symbol='BTCUSDT', self.open=21919.9, self.close=22074.5, self.high=22083.2, self.low=21900.0, self.vol=5797.736, self.amt=127476974.9911 
2023-03-13 08:20:01,592:INFO:sr_min:main.py:172:handleKline:449472: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5855  20230313   075500    075959  ...         0.0        0.0       0
5856  20230313   080000    080459  ...         0.0        0.0       0
5857  20230313   080500    080959  ...         0.0        0.0       0
5858  20230313   081000    081459  ...         0.0        0.0       0
5859  20230313   081500    081959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-03-13 08:20:01,594:INFO:sr_min:main.py:175:handleKline:449472: self.closeSec=1678666799, self.tradeDate='20230313', self.openTime='081500', self.closeTime='081959',self.symbol='BTCUSDT',self.open=21919.9, self.close=22074.5, self.high=22083.2, self.low=21900.0, self.vol=5797.736, self.amt=127476974.9911, ukdf['pct'].iloc[-1]=0.007053 , ukdf['amount'].iloc[-1]=127476974.9911, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5859, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': []}
type(curSign)=<class 'int'>, curSign=0, self.sign=0
--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=0, self.total=1000000.0, self.flagDict['side']='', self.tradeCount=0, self.count=26459
self.closeSec=1678667099, self.tradeDate='20230313', self.openTime='082000', self.closeTime='082459', self.symbol='BTCUSDT', self.open=22062.8, self.close=22064.5, self.high=22269.0, self.low=21996.4, self.vol=15784.276, self.amt=349337356.2945 
127.0.0.1 - - [13/Mar/2023 08:25:01] "POST / HTTP/1.1" 200 -
2023-03-13 08:25:01,582:INFO:sr_min:main.py:172:handleKline:449472: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5856  20230313   080000    080459  ...         0.0        0.0       0
5857  20230313   080500    080959  ...         0.0        0.0       0
5858  20230313   081000    081459  ...         0.0        0.0       0
5859  20230313   081500    081959  ...         0.0        0.0       0
5860  20230313   082000    082459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-03-13 08:25:01,583:INFO:sr_min:main.py:175:handleKline:449472: self.closeSec=1678667099, self.tradeDate='20230313', self.openTime='082000', self.closeTime='082459',self.symbol='BTCUSDT',self.open=22062.8, self.close=22064.5, self.high=22269.0, self.low=21996.4, self.vol=15784.276, self.amt=349337356.2945, ukdf['pct'].iloc[-1]=-0.000453 , ukdf['amount'].iloc[-1]=349337356.2945, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5860, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': []}
type(curSign)=<class 'int'>, curSign=0, self.sign=0


## /root/FIL/strategy/s_rsrs/log.txt ----- -----

719  20230312   200000    235959  1678636799  ...    719  0.768772  0.738695     1.0
720  20230313   000000    035959  1678651199  ...    720  0.718037  0.579599     NaN

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '55.825', 'enterprice': '20070', 'countrevence': '0', 'unrealprofit': '39669.245', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '20780.6', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-9223372036854775808, self.sign=1
--handleKline--:  version='2.0.0', self.name='s_rsrs', self.symbol='BTCUSDT', interval='4h', intervalSec=14400, wid=25, thd=0.6, self.sign=1, self.total=1119287.34225, self.flagDict['side']='buy', self.tradeCount=24, self.count=646
self.closeSec=1678665599, self.tradeDate='20230313', self.openTime='040000', self.closeTime='075959', self.symbol='BTCUSDT', self.open=20770.6, self.close=21986.2, self.high=22184.0, self.low=20750.8, self.vol=327344.807, self.amt=7038855919.01692 
2023-03-13 08:00:02,071:INFO:s_rsrs:main.py:141:handleKline:185271: self.closeSec=1678665599, self.tradeDate='20230313', self.openTime='040000', self.closeTime='075959',self.symbol='BTCUSDT',self.open=20770.6, self.close=21986.2, self.high=22184.0, self.low=20750.8, self.vol=327344.807, self.amt=7038855919.01692 
127.0.0.1 - - [13/Mar/2023 08:00:02] "POST / HTTP/1.1" 200 -
2023-03-13 08:00:02,132:INFO:s_rsrs:main.py:142:handleKline:185271: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime  ...         vol           amt       pct
717  20230312   120000    155959  ...   39349.368  8.007788e+08 -0.001561
718  20230312   160000    195959  ...   51563.089  1.052004e+09  0.004888
719  20230312   200000    235959  ...   73260.469  1.491894e+09 -0.004262
720  20230313   000000    035959  ...  320423.397  6.686396e+09  0.020769
721  20230313   040000    075959  ...  327344.807  7.038856e+09  0.058530

[5 rows x 11 columns]
2023-03-13 08:00:05,148:INFO:s_rsrs:main.py:151:handleKline:185271: df_s.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec  ...  index      beta    zscore  signal
717  20230312   120000    155959  1678607999  ...    717  0.772872  0.718523     1.0
718  20230312   160000    195959  1678622399  ...    718  0.763021  0.703887     1.0
719  20230312   200000    235959  1678636799  ...    719  0.768772  0.738695     1.0
720  20230313   000000    035959  1678651199  ...    720  0.718037  0.579599     NaN
721  20230313   040000    075959  1678665599  ...    721  0.700134  0.532409     NaN

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '55.825', 'enterprice': '20070', 'countrevence': '0', 'unrealprofit': '106911.809621694', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '21985.12422072', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-9223372036854775808, self.sign=1


