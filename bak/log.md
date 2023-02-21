# 20230221 08:26:01

## /root/FIL/strategy/amihud/log.txt ----- -----

127.0.0.1 - - [21/Feb/2023 08:20:01] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=993672.4896432, self.flagDict['side']='sell', self.tradeCount=2, self.count=24700
self.closeSec=1676938799, self.tradeDate='20230221', self.openTime='081500', self.closeTime='081959', self.symbol='BTCUSDT', self.open=24827.0, self.close=24789.1, self.high=24831.2, self.low=24787.2, self.vol=766.858, self.amt=19018027.6671 
2023-02-21 08:20:01,708:INFO:amihud:main.py:172:handleKline:200676: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5855  20230221   075500    075959  ...         0.0        0.0       0
5856  20230221   080000    080459  ...         0.0        0.0       0
5857  20230221   080500    080959  ...         0.0        0.0       0
5858  20230221   081000    081459  ...         0.0        0.0       0
5859  20230221   081500    081959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-02-21 08:20:01,708:INFO:amihud:main.py:175:handleKline:200676: self.closeSec=1676938799, self.tradeDate='20230221', self.openTime='081500', self.closeTime='081959',self.symbol='BTCUSDT',self.open=24827.0, self.close=24789.1, self.high=24831.2, self.low=24787.2, self.vol=766.858, self.amt=19018027.6671, ukdf['pct'].iloc[-1]=-0.001523 , ukdf['amount'].iloc[-1]=19018027.6671, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5859, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '60.176', 'enterprice': '16529.3', 'countrevence': '0', 'unrealprofit': '-497059.15544214128', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '24789.38966103', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1
127.0.0.1 - - [21/Feb/2023 08:25:01] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=993672.4896432, self.flagDict['side']='sell', self.tradeCount=2, self.count=24701
self.closeSec=1676939099, self.tradeDate='20230221', self.openTime='082000', self.closeTime='082459', self.symbol='BTCUSDT', self.open=24789.2, self.close=24820.2, self.high=24829.9, self.low=24789.1, self.vol=488.5, self.amt=12121695.9544 
2023-02-21 08:25:01,562:INFO:amihud:main.py:172:handleKline:200676: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5856  20230221   080000    080459  ...         0.0        0.0       0
5857  20230221   080500    080959  ...         0.0        0.0       0
5858  20230221   081000    081459  ...         0.0        0.0       0
5859  20230221   081500    081959  ...         0.0        0.0       0
5860  20230221   082000    082459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-02-21 08:25:01,562:INFO:amihud:main.py:175:handleKline:200676: self.closeSec=1676939099, self.tradeDate='20230221', self.openTime='082000', self.closeTime='082459',self.symbol='BTCUSDT',self.open=24789.2, self.close=24820.2, self.high=24829.9, self.low=24789.1, self.vol=488.5, self.amt=12121695.9544, ukdf['pct'].iloc[-1]=0.001255 , ukdf['amount'].iloc[-1]=12121695.9544, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5860, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '60.176', 'enterprice': '16529.3', 'countrevence': '0', 'unrealprofit': '-498913.1984', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '24820.2', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1


## /root/FIL/strategy/factorcheck/log.txt ----- -----


self.closeSec=1676938799, self.tradeDate='20230221', self.openTime='081500', self.closeTime='081959', self.symbol='BTCUSDT', self.open=24827.0, self.close=24789.1, self.high=24831.2, self.low=24787.2 
2023-02-21 08:20:01,642:INFO:factorcheck2:main.py:126:handleKline:185239: self.closeSec=1676938799, self.tradeDate='20230221', self.openTime='081500', self.closeTime='081959',self.symbol='BTCUSDT',self.open=24827.0, self.close=24789.1, self.high=24831.2, self.low=24787.2   
127.0.0.1 - - [21/Feb/2023 08:20:01] "POST / HTTP/1.1" 200 -
2023-02-21 08:20:01,687:INFO:factorcheck2:main.py:127:handleKline:185239: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1535  20230221   075500    075959  1676937599  ...  24810.7  0.001467   1535    5
1536  20230221   080000    080459  1676937899  ...  24824.3 -0.001030   1536    0
1537  20230221   080500    080959  1676938199  ...  24817.1 -0.000032   1537    1
1538  20230221   081000    081459  1676938499  ...  24793.2  0.000137   1538    2
1539  20230221   081500    081959  1676938799  ...  24787.2 -0.001523   1539    3

[5 rows x 11 columns]
2023-02-21 08:20:01,687:INFO:factorcheck2:main.py:128:handleKline:185239: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}
127.0.0.1 - - [21/Feb/2023 08:25:01] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=295, self.factor=0.3858963304274236, self.count=25267 

self.closeSec=1676939099, self.tradeDate='20230221', self.openTime='082000', self.closeTime='082459', self.symbol='BTCUSDT', self.open=24789.2, self.close=24820.2, self.high=24829.9, self.low=24789.1 
2023-02-21 08:25:01,486:INFO:factorcheck2:main.py:126:handleKline:185239: self.closeSec=1676939099, self.tradeDate='20230221', self.openTime='082000', self.closeTime='082459',self.symbol='BTCUSDT',self.open=24789.2, self.close=24820.2, self.high=24829.9, self.low=24789.1   
2023-02-21 08:25:01,521:INFO:factorcheck2:main.py:127:handleKline:185239: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1536  20230221   080000    080459  1676937899  ...  24824.3 -0.001030   1536    0
1537  20230221   080500    080959  1676938199  ...  24817.1 -0.000032   1537    1
1538  20230221   081000    081459  1676938499  ...  24793.2  0.000137   1538    2
1539  20230221   081500    081959  1676938799  ...  24787.2 -0.001523   1539    3
1540  20230221   082000    082459  1676939099  ...  24789.1  0.001255   1540    4

[5 rows x 11 columns]
2023-02-21 08:25:01,521:INFO:factorcheck2:main.py:128:handleKline:185239: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}


## /root/FIL/strategy/logic/log.txt ----- -----

2023-02-21 08:00:35,147:DEBUG:logic:main.py:463:getModel:885513: df_s.iloc[-5:,:] :
          date closeTime     open  ...    alpha58   alpha67   alpha72
5770  20230221    052959  24807.3  ...  50.000000  0.527485  0.290389
5771  20230221    055959  24793.6  ...  49.583333  0.523373  0.296097
5772  20230221    062959  24770.0  ...  49.166667  0.510433  0.309508
5773  20230221    065959  24695.2  ...  49.583333  0.512011  0.323842
5774  20230221    072959  24704.7  ...  49.583333  0.526670  0.331777

[5 rows x 33 columns]
0.5027726432532348
acc is : 0.5027726432532348
2023-02-21 08:00:35,302:INFO:logic:main.py:468:getModel:885513: df_pred.iloc[-5:,:] :
     pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
536     0  0.511705  0.488295       0  ...  1.053345   1.0    0.0  1.097723
537     0  0.505924  0.494076       0  ...  1.050159   1.0    0.0  1.094403
538     1  0.490319  0.509681       1  ...  1.050568   1.0    0.0  1.094829
539     0  0.506229  0.493771       1  ...  1.054412   1.0    0.0  1.098835
540     0  0.527483  0.472517       1  ...  1.056742   1.0    0.0  1.101263

[5 rows x 10 columns]
2023-02-21 08:00:35,338:INFO:logic:main.py:478:getModel:885513: df_panel.iloc[-5:,:] :
    pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
45     0  0.511180  0.488820       0  ...  1.053345   1.0    0.0  1.095833
46     0  0.505902  0.494098       0  ...  1.050159   1.0    0.0  1.095194
47     1  0.490893  0.509107       1  ...  1.050568   1.0    0.0  1.097840
48     0  0.506229  0.493771       1  ...  1.054412   1.0    0.0  1.098835
49     0  0.527483  0.472517       1  ...  1.056742   1.0    0.0  1.101263

[5 rows x 10 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '34.222', 'enterprice': '24804.7', 'countrevence': '0', 'unrealprofit': '1605.0118', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '24851.6', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}


## /root/FIL/strategy/modifiedmom/log.txt ----- -----

623  20230221   075000    075959  1676937599  24800.6  24849.9  0.001988
2023-02-21 08:00:02,180:INFO:modifiedmom:main.py:146:handleKline:185213: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=12632 

self.closeSec=1676938199, self.tradeDate='20230221', self.openTime='080000', self.closeTime='080959', self.symbol='BTCUSDT', self.open='24849.9', self.close='24823.5'
2023-02-21 08:10:01,589:INFO:modifiedmom:main.py:144:handleKline:185213: self.closeSec=1676938199, self.tradeDate='20230221', self.openTime='080000', self.closeTime='080959',self.symbol='BTCUSDT',self.open='24849.9', self.close='24823.5'
127.0.0.1 - - [21/Feb/2023 08:10:01] "POST / HTTP/1.1" 200 -
2023-02-21 08:10:01,617:INFO:modifiedmom:main.py:145:handleKline:185213: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
620  20230221   072000    072959  1676935799  24795.2    24795 -0.000008
621  20230221   073000    073959  1676936399    24795  24780.5 -0.000585
622  20230221   074000    074959  1676936999  24779.5  24800.6  0.000811
623  20230221   075000    075959  1676937599  24800.6  24849.9  0.001988
624  20230221   080000    080959  1676938199  24849.9  24823.5 -0.001062
2023-02-21 08:10:01,617:INFO:modifiedmom:main.py:146:handleKline:185213: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=12633 

self.closeSec=1676938799, self.tradeDate='20230221', self.openTime='081000', self.closeTime='081959', self.symbol='BTCUSDT', self.open='24823.6', self.close='24789.1'
2023-02-21 08:20:01,763:INFO:modifiedmom:main.py:144:handleKline:185213: self.closeSec=1676938799, self.tradeDate='20230221', self.openTime='081000', self.closeTime='081959',self.symbol='BTCUSDT',self.open='24823.6', self.close='24789.1'
127.0.0.1 - - [21/Feb/2023 08:20:01] "POST / HTTP/1.1" 200 -
2023-02-21 08:20:01,795:INFO:modifiedmom:main.py:145:handleKline:185213: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
621  20230221   073000    073959  1676936399    24795  24780.5 -0.000585
622  20230221   074000    074959  1676936999  24779.5  24800.6  0.000811
623  20230221   075000    075959  1676937599  24800.6  24849.9  0.001988
624  20230221   080000    080959  1676938199  24849.9  24823.5 -0.001062
625  20230221   081000    081959  1676938799  24823.6  24789.1 -0.001386
2023-02-21 08:20:01,798:INFO:modifiedmom:main.py:146:handleKline:185213: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False}


## /root/FIL/strategy/percentile_regression_step2/log.txt ----- -----

127.0.0.1 - - [21/Feb/2023 07:00:02] "POST / HTTP/1.1" 200 -
2023-02-21 07:00:03,197:DEBUG:percentile_regression_step2:main.py:154:get_signal:1265985: df_id.iloc[-5:,:] :
                 daytime     hms    close  ...  pct_10  pct_20  factor
144  2023/02/21 04:30:00  043000  24807.3  ...     NaN     NaN       0
145  2023/02/21 05:00:00  050000  24793.5  ...     NaN     NaN       0
146  2023/02/21 05:30:00  053000  24770.0  ...     NaN     NaN       0
147  2023/02/21 06:00:00  060000  24695.1  ...     NaN     NaN       0
148  2023/02/21 06:30:00  063000  24704.7  ...     NaN     NaN       0

[5 rows x 10 columns]
127.0.0.1 - - [21/Feb/2023 07:30:01] "POST / HTTP/1.1" 200 -
2023-02-21 07:30:02,349:DEBUG:percentile_regression_step2:main.py:154:get_signal:1265985: df_id.iloc[-5:,:] :
                 daytime     hms    close  ...  pct_10  pct_20  factor
144  2023/02/21 05:00:00  050000  24793.5  ...     NaN     NaN       0
145  2023/02/21 05:30:00  053000  24770.0  ...     NaN     NaN       0
146  2023/02/21 06:00:00  060000  24695.1  ...     NaN     NaN       0
147  2023/02/21 06:30:00  063000  24704.7  ...     NaN     NaN       0
148  2023/02/21 07:00:00  070000  24795.1  ...     NaN     NaN       0

[5 rows x 10 columns]
127.0.0.1 - - [21/Feb/2023 08:00:01] "POST / HTTP/1.1" 200 -
2023-02-21 08:00:03,229:DEBUG:percentile_regression_step2:main.py:154:get_signal:1265985: df_id.iloc[-5:,:] :
                 daytime     hms    close  ...  pct_10  pct_20  factor
144  2023/02/21 05:30:00  053000  24770.0  ...     NaN     NaN       0
145  2023/02/21 06:00:00  060000  24695.1  ...     NaN     NaN       0
146  2023/02/21 06:30:00  063000  24704.7  ...     NaN     NaN       0
147  2023/02/21 07:00:00  070000  24795.1  ...     NaN     NaN       0
148  2023/02/21 07:30:00  073000  24849.9  ...     NaN     NaN       0

[5 rows x 10 columns]


## /root/FIL/strategy/pyemd/log.txt ----- -----

17471  20230221   075000    075959  1676937599  24800.6  24849.9
2023-02-21 08:00:02,191:INFO:pyemd2:main.py:127:handleKline:185189: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}
127.0.0.1 - - [21/Feb/2023 08:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=12633 

self.closeSec=1676938199, self.tradeDate='20230221', self.openTime='080000', self.closeTime='080959', self.symbol='BTCUSDT', self.open='24849.9', self.close='24823.5'
2023-02-21 08:10:01,628:INFO:pyemd2:main.py:125:handleKline:185189: self.closeSec=1676938199, self.tradeDate='20230221', self.openTime='080000', self.closeTime='080959',self.symbol='BTCUSDT',self.open='24849.9', self.close='24823.5'
2023-02-21 08:10:01,651:INFO:pyemd2:main.py:126:handleKline:185189: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17468  20230221   072000    072959  1676935799  24795.2    24795
17469  20230221   073000    073959  1676936399    24795  24780.5
17470  20230221   074000    074959  1676936999  24779.5  24800.6
17471  20230221   075000    075959  1676937599  24800.6  24849.9
17472  20230221   080000    080959  1676938199  24849.9  24823.5
2023-02-21 08:10:01,651:INFO:pyemd2:main.py:127:handleKline:185189: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=12634 

self.closeSec=1676938799, self.tradeDate='20230221', self.openTime='081000', self.closeTime='081959', self.symbol='BTCUSDT', self.open='24823.6', self.close='24789.1'
127.0.0.1 - - [21/Feb/2023 08:20:01] "POST / HTTP/1.1" 200 -
2023-02-21 08:20:01,732:INFO:pyemd2:main.py:125:handleKline:185189: self.closeSec=1676938799, self.tradeDate='20230221', self.openTime='081000', self.closeTime='081959',self.symbol='BTCUSDT',self.open='24823.6', self.close='24789.1'
2023-02-21 08:20:01,795:INFO:pyemd2:main.py:126:handleKline:185189: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17469  20230221   073000    073959  1676936399    24795  24780.5
17470  20230221   074000    074959  1676936999  24779.5  24800.6
17471  20230221   075000    075959  1676937599  24800.6  24849.9
17472  20230221   080000    080959  1676938199  24849.9  24823.5
17473  20230221   081000    081959  1676938799  24823.6  24789.1
2023-02-21 08:20:01,795:INFO:pyemd2:main.py:127:handleKline:185189: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}


## /root/FIL/strategy/similarity/log.txt ----- -----

12143  20230221   075000    075959  1676937599  24800.6  24849.9
2023-02-21 08:00:02,187:INFO:testStrategy:main.py:103:handleKline:185174: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=12633 

self.closeSec=1676938199, self.tradeDate='20230221', self.openTime='080000', self.closeTime='080959', self.symbol='BTCUSDT', self.open='24849.9', self.close='24823.5'
2023-02-21 08:10:01,610:INFO:testStrategy:main.py:101:handleKline:185174: self.closeSec=1676938199, self.tradeDate='20230221', self.openTime='080000', self.closeTime='080959',self.symbol='BTCUSDT',self.open='24849.9', self.close='24823.5'
127.0.0.1 - - [21/Feb/2023 08:10:01] "POST / HTTP/1.1" 200 -
2023-02-21 08:10:01,633:INFO:testStrategy:main.py:102:handleKline:185174: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12140  20230221   072000    072959  1676935799  24795.2    24795
12141  20230221   073000    073959  1676936399    24795  24780.5
12142  20230221   074000    074959  1676936999  24779.5  24800.6
12143  20230221   075000    075959  1676937599  24800.6  24849.9
12144  20230221   080000    080959  1676938199  24849.9  24823.5
2023-02-21 08:10:01,633:INFO:testStrategy:main.py:103:handleKline:185174: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=12634 

self.closeSec=1676938799, self.tradeDate='20230221', self.openTime='081000', self.closeTime='081959', self.symbol='BTCUSDT', self.open='24823.6', self.close='24789.1'
2023-02-21 08:20:01,739:INFO:testStrategy:main.py:101:handleKline:185174: self.closeSec=1676938799, self.tradeDate='20230221', self.openTime='081000', self.closeTime='081959',self.symbol='BTCUSDT',self.open='24823.6', self.close='24789.1'
127.0.0.1 - - [21/Feb/2023 08:20:01] "POST / HTTP/1.1" 200 -
2023-02-21 08:20:01,790:INFO:testStrategy:main.py:102:handleKline:185174: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12141  20230221   073000    073959  1676936399    24795  24780.5
12142  20230221   074000    074959  1676936999  24779.5  24800.6
12143  20230221   075000    075959  1676937599  24800.6  24849.9
12144  20230221   080000    080959  1676938199  24849.9  24823.5
12145  20230221   081000    081959  1676938799  24823.6  24789.1
2023-02-21 08:20:01,790:INFO:testStrategy:main.py:103:handleKline:185174: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}


## /root/FIL/strategy/sr_min/log.txt ----- -----

127.0.0.1 - - [21/Feb/2023 08:20:01] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=0, self.total=1000000.0, self.flagDict['side']='', self.tradeCount=0, self.count=20698
self.closeSec=1676938799, self.tradeDate='20230221', self.openTime='081500', self.closeTime='081959', self.symbol='BTCUSDT', self.open=24827.0, self.close=24789.1, self.high=24831.2, self.low=24787.2, self.vol=766.858, self.amt=19018027.6671 
2023-02-21 08:20:01,798:INFO:sr_min:main.py:172:handleKline:449472: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5855  20230221   075500    075959  ...         0.0        0.0       0
5856  20230221   080000    080459  ...         0.0        0.0       0
5857  20230221   080500    080959  ...         0.0        0.0       0
5858  20230221   081000    081459  ...         0.0        0.0       0
5859  20230221   081500    081959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-02-21 08:20:01,799:INFO:sr_min:main.py:175:handleKline:449472: self.closeSec=1676938799, self.tradeDate='20230221', self.openTime='081500', self.closeTime='081959',self.symbol='BTCUSDT',self.open=24827.0, self.close=24789.1, self.high=24831.2, self.low=24787.2, self.vol=766.858, self.amt=19018027.6671, ukdf['pct'].iloc[-1]=-0.001523 , ukdf['amount'].iloc[-1]=19018027.6671, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5859, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': []}
type(curSign)=<class 'int'>, curSign=0, self.sign=0
127.0.0.1 - - [21/Feb/2023 08:25:01] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=0, self.total=1000000.0, self.flagDict['side']='', self.tradeCount=0, self.count=20699
self.closeSec=1676939099, self.tradeDate='20230221', self.openTime='082000', self.closeTime='082459', self.symbol='BTCUSDT', self.open=24789.2, self.close=24820.2, self.high=24829.9, self.low=24789.1, self.vol=488.5, self.amt=12121695.9544 
2023-02-21 08:25:01,576:INFO:sr_min:main.py:172:handleKline:449472: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5856  20230221   080000    080459  ...         0.0        0.0       0
5857  20230221   080500    080959  ...         0.0        0.0       0
5858  20230221   081000    081459  ...         0.0        0.0       0
5859  20230221   081500    081959  ...         0.0        0.0       0
5860  20230221   082000    082459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-02-21 08:25:01,576:INFO:sr_min:main.py:175:handleKline:449472: self.closeSec=1676939099, self.tradeDate='20230221', self.openTime='082000', self.closeTime='082459',self.symbol='BTCUSDT',self.open=24789.2, self.close=24820.2, self.high=24829.9, self.low=24789.1, self.vol=488.5, self.amt=12121695.9544, ukdf['pct'].iloc[-1]=0.001255 , ukdf['amount'].iloc[-1]=12121695.9544, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5860, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': []}
type(curSign)=<class 'int'>, curSign=0, self.sign=0


## /root/FIL/strategy/s_rsrs/log.txt ----- -----

719  20230220   200000    235959  1676908799  ...    719  0.220485 -1.139201    -1.0
720  20230221   000000    035959  1676923199  ...    720  0.226097 -1.115725    -1.0

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '36.465', 'enterprice': '24934.8', 'countrevence': '0', 'unrealprofit': '1662.804', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '24889.2', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-1, self.sign=-1
127.0.0.1 - - [21/Feb/2023 08:00:01] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='s_rsrs', self.symbol='BTCUSDT', interval='4h', intervalSec=14400, wid=25, thd=0.6, self.sign=-1, self.total=908338.234518, self.flagDict['side']='sell', self.tradeCount=21, self.count=526
self.closeSec=1676937599, self.tradeDate='20230221', self.openTime='040000', self.closeTime='075959', self.symbol='BTCUSDT', self.open=24878.4, self.close=24849.9, self.high=24891.5, self.low=24651.2, self.vol=38879.181, self.amt=963355362.9029 
2023-02-21 08:00:01,927:INFO:s_rsrs:main.py:141:handleKline:185271: self.closeSec=1676937599, self.tradeDate='20230221', self.openTime='040000', self.closeTime='075959',self.symbol='BTCUSDT',self.open=24878.4, self.close=24849.9, self.high=24891.5, self.low=24651.2, self.vol=38879.181, self.amt=963355362.9029 
2023-02-21 08:00:01,958:INFO:s_rsrs:main.py:142:handleKline:185271: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime  ...         vol           amt       pct
717  20230220   120000    155959  ...   50497.845  1.236248e+09  0.003490
718  20230220   160000    195959  ...  159438.885  3.951076e+09  0.016155
719  20230220   200000    235959  ...  167345.352  4.170410e+09  0.001956
720  20230221   000000    035959  ...  102254.274  2.538101e+09 -0.002650
721  20230221   040000    075959  ...   38879.181  9.633554e+08 -0.001150

[5 rows x 11 columns]
2023-02-21 08:00:04,377:INFO:s_rsrs:main.py:151:handleKline:185271: df_s.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec  ...  index      beta    zscore  signal
717  20230220   120000    155959  1676879999  ...    717  0.179914 -1.278394    -1.0
718  20230220   160000    195959  1676894399  ...    718  0.185992 -1.242748    -1.0
719  20230220   200000    235959  1676908799  ...    719  0.220485 -1.139201    -1.0
720  20230221   000000    035959  1676923199  ...    720  0.226097 -1.115725    -1.0
721  20230221   040000    075959  1676937599  ...    721  0.197351 -1.167501    -1.0

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '36.465', 'enterprice': '24934.8', 'countrevence': '0', 'unrealprofit': '3083.61902060355', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '24850.23619853', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-1, self.sign=-1


