# 20230214 08:36:07

## /root/FIL/strategy/amihud/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=993672.4896432, self.flagDict['side']='sell', self.tradeCount=2, self.count=22686
self.closeSec=1676334599, self.tradeDate='20230214', self.openTime='082500', self.closeTime='082959', self.symbol='BTCUSDT', self.open=21801.7, self.close=21748.8, self.high=21802.3, self.low=21747.8, self.vol=1118.41, self.amt=24356254.799 
127.0.0.1 - - [14/Feb/2023 08:30:02] "POST / HTTP/1.1" 200 -
2023-02-14 08:30:03,094:INFO:amihud:main.py:172:handleKline:200676: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5857  20230214   080500    080959  ...         0.0        0.0       0
5858  20230214   081000    081459  ...         0.0        0.0       0
5859  20230214   081500    081959  ...         0.0        0.0       0
5860  20230214   082000    082459  ...         0.0        0.0       0
5861  20230214   082500    082959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-02-14 08:30:03,104:INFO:amihud:main.py:175:handleKline:200676: self.closeSec=1676334599, self.tradeDate='20230214', self.openTime='082500', self.closeTime='082959',self.symbol='BTCUSDT',self.open=21801.7, self.close=21748.8, self.high=21802.3, self.low=21747.8, self.vol=1118.41, self.amt=24356254.799, ukdf['pct'].iloc[-1]=-0.002426 , ukdf['amount'].iloc[-1]=24356254.799, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5861, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '60.176', 'enterprice': '16529.3', 'countrevence': '0', 'unrealprofit': '-314091.53596558512', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '21748.84825787', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1
--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=993672.4896432, self.flagDict['side']='sell', self.tradeCount=2, self.count=22687
self.closeSec=1676334899, self.tradeDate='20230214', self.openTime='083000', self.closeTime='083459', self.symbol='BTCUSDT', self.open=21748.9, self.close=21758.4, self.high=21765.6, self.low=21745.0, self.vol=486.845, self.amt=10590541.9183 
127.0.0.1 - - [14/Feb/2023 08:35:01] "POST / HTTP/1.1" 200 -
2023-02-14 08:35:01,660:INFO:amihud:main.py:172:handleKline:200676: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5858  20230214   081000    081459  ...         0.0        0.0       0
5859  20230214   081500    081959  ...         0.0        0.0       0
5860  20230214   082000    082459  ...         0.0        0.0       0
5861  20230214   082500    082959  ...         0.0        0.0       0
5862  20230214   083000    083459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-02-14 08:35:01,661:INFO:amihud:main.py:175:handleKline:200676: self.closeSec=1676334899, self.tradeDate='20230214', self.openTime='083000', self.closeTime='083459',self.symbol='BTCUSDT',self.open=21748.9, self.close=21758.4, self.high=21765.6, self.low=21745.0, self.vol=486.845, self.amt=10590541.9183, ukdf['pct'].iloc[-1]=0.000441 , ukdf['amount'].iloc[-1]=10590541.9183, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5862, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '60.176', 'enterprice': '16529.3', 'countrevence': '0', 'unrealprofit': '-314666.3216', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '21758.4', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1


## /root/FIL/strategy/factorcheck/log.txt ----- -----

1540  20230214   082000    082459  1676334299  ...  21747.3  0.002008   1540    4
1541  20230214   082500    082959  1676334599  ...  21747.8 -0.002426   1541    5

[5 rows x 11 columns]
2023-02-14 08:30:01,942:INFO:factorcheck2:main.py:128:handleKline:185239: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': False, 'isOpen': True, 'isClose': False, 'isTrig': True}
2023-02-14 08:30:02,116:INFO:factorcheck2:main.py:145:handleKline:185239: df_panel.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec  ...       pct  index  idx    factor
213  20230214   062500    062959  1676327399  ...  0.000333   1517    5  0.586771
214  20230214   065500    065959  1676329199  ... -0.000933   1523    5  0.583573
215  20230214   072500    072959  1676330999  ...  0.001714   1529    5  0.572578
216  20230214   075500    075959  1676332799  ... -0.002004   1535    5  0.563329
217  20230214   082500    082959  1676334599  ... -0.002426   1541    5  0.555121

[5 rows x 12 columns]
127.0.0.1 - - [14/Feb/2023 08:35:01] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=9, self.factor=0.5551205491336428, self.count=23253 

self.closeSec=1676334899, self.tradeDate='20230214', self.openTime='083000', self.closeTime='083459', self.symbol='BTCUSDT', self.open=21748.9, self.close=21758.4, self.high=21765.6, self.low=21745.0 
2023-02-14 08:35:01,536:INFO:factorcheck2:main.py:126:handleKline:185239: self.closeSec=1676334899, self.tradeDate='20230214', self.openTime='083000', self.closeTime='083459',self.symbol='BTCUSDT',self.open=21748.9, self.close=21758.4, self.high=21765.6, self.low=21745.0   
2023-02-14 08:35:01,629:INFO:factorcheck2:main.py:127:handleKline:185239: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1538  20230214   081000    081459  1676333699  ...  21750.9 -0.000009   1538    2
1539  20230214   081500    081959  1676333999  ...  21731.8  0.000037   1539    3
1540  20230214   082000    082459  1676334299  ...  21747.3  0.002008   1540    4
1541  20230214   082500    082959  1676334599  ...  21747.8 -0.002426   1541    5
1542  20230214   083000    083459  1676334899  ...  21745.0  0.000441   1542    0

[5 rows x 11 columns]
2023-02-14 08:35:01,629:INFO:factorcheck2:main.py:128:handleKline:185239: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': False, 'isOpen': True, 'isClose': False, 'isTrig': True}


## /root/FIL/strategy/logic/log.txt ----- -----

2023-02-14 08:30:34,150:DEBUG:logic:main.py:463:getModel:885513: df_s.iloc[-5:,:] :
          date closeTime     open  ...    alpha58   alpha67   alpha72
5771  20230214    055959  21609.7  ...  44.583333  0.466201  0.606564
5772  20230214    062959  21604.1  ...  44.166667  0.465830  0.600720
5773  20230214    065959  21602.6  ...  44.583333  0.473253  0.592115
5774  20230214    072959  21628.6  ...  45.000000  0.517757  0.563574
5775  20230214    075959  21797.8  ...  44.583333  0.509553  0.540766

[5 rows x 33 columns]
0.532347504621072
acc is : 0.532347504621072
2023-02-14 08:30:34,308:INFO:logic:main.py:468:getModel:885513: df_pred.iloc[-5:,:] :
     pred    prob_0    prob_1  actual  ...       nav  sign   cost_        bm
536     1  0.498655  0.501345       0  ...  1.013571  -1.0  0.0000  0.903999
537     1  0.499412  0.500588       1  ...  1.012351  -1.0  0.0000  0.905087
538     0  0.505289  0.494711       1  ...  1.004431  -1.0  0.0000  0.912168
539     0  0.550852  0.449148       0  ...  1.001368   1.0 -0.0016  0.910845
540     0  0.511795  0.488205       0  ...  1.000568   1.0  0.0000  0.910117

[5 rows x 10 columns]
2023-02-14 08:30:34,328:INFO:logic:main.py:478:getModel:885513: df_panel.iloc[-5:,:] :
    pred    prob_0    prob_1  actual  ...       nav  sign   cost_        bm
45     1  0.499023  0.500977       0  ...  1.013571  -1.0  0.0000  0.905469
46     0  0.500209  0.499791       1  ...  1.012351  -1.0  0.0000  0.909116
47     0  0.505679  0.494321       1  ...  1.004431  -1.0  0.0000  0.914917
48     0  0.551221  0.448779       0  ...  1.001368   1.0 -0.0016  0.913590
49     0  0.511795  0.488205       0  ...  1.000568   1.0  0.0000  0.910117

[5 rows x 10 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '35.657', 'enterprice': '21765.6', 'countrevence': '0', 'unrealprofit': '-699.47572663519', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '21745.98321433', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}


## /root/FIL/strategy/modifiedmom/log.txt ----- -----

624  20230214   080000    080959  1676333399  21766.1  21757.4 -0.000404
2023-02-14 08:10:01,687:INFO:modifiedmom:main.py:146:handleKline:185213: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=11625 

self.closeSec=1676333999, self.tradeDate='20230214', self.openTime='081000', self.closeTime='081959', self.symbol='BTCUSDT', self.open='21757.4', self.close='21758'
2023-02-14 08:20:01,636:INFO:modifiedmom:main.py:144:handleKline:185213: self.closeSec=1676333999, self.tradeDate='20230214', self.openTime='081000', self.closeTime='081959',self.symbol='BTCUSDT',self.open='21757.4', self.close='21758'
127.0.0.1 - - [14/Feb/2023 08:20:01] "POST / HTTP/1.1" 200 -
2023-02-14 08:20:01,681:INFO:modifiedmom:main.py:145:handleKline:185213: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
621  20230214   073000    073959  1676331599  21797.8  21787.4 -0.000477
622  20230214   074000    074959  1676332199  21787.5  21786.7 -0.000032
623  20230214   075000    075959  1676332799  21786.6  21766.2 -0.000941
624  20230214   080000    080959  1676333399  21766.1  21757.4 -0.000404
625  20230214   081000    081959  1676333999  21757.4    21758  0.000028
2023-02-14 08:20:01,681:INFO:modifiedmom:main.py:146:handleKline:185213: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=11626 

self.closeSec=1676334599, self.tradeDate='20230214', self.openTime='082000', self.closeTime='082959', self.symbol='BTCUSDT', self.open='21757.9', self.close='21748.8'
127.0.0.1 - - [14/Feb/2023 08:30:03] "POST / HTTP/1.1" 200 -
2023-02-14 08:30:05,103:INFO:modifiedmom:main.py:144:handleKline:185213: self.closeSec=1676334599, self.tradeDate='20230214', self.openTime='082000', self.closeTime='082959',self.symbol='BTCUSDT',self.open='21757.9', self.close='21748.8'
2023-02-14 08:30:05,424:INFO:modifiedmom:main.py:145:handleKline:185213: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
622  20230214   074000    074959  1676332199  21787.5  21786.7 -0.000032
623  20230214   075000    075959  1676332799  21786.6  21766.2 -0.000941
624  20230214   080000    080959  1676333399  21766.1  21757.4 -0.000404
625  20230214   081000    081959  1676333999  21757.4    21758  0.000028
626  20230214   082000    082959  1676334599  21757.9  21748.8 -0.000423
2023-02-14 08:30:05,424:INFO:modifiedmom:main.py:146:handleKline:185213: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False}


## /root/FIL/strategy/percentile_regression_step2/log.txt ----- -----

127.0.0.1 - - [14/Feb/2023 07:30:01] "POST / HTTP/1.1" 200 -
2023-02-14 07:30:03,141:DEBUG:percentile_regression_step2:main.py:154:get_signal:1265985: df_id.iloc[-5:,:] :
                 daytime     hms    close  ...  pct_10  pct_20  factor
144  2023/02/14 05:00:00  050000  21609.6  ...     NaN     NaN       0
145  2023/02/14 05:30:00  053000  21604.1  ...     NaN     NaN       0
146  2023/02/14 06:00:00  060000  21602.6  ...     NaN     NaN       0
147  2023/02/14 06:30:00  063000  21628.6  ...     NaN     NaN       0
148  2023/02/14 07:00:00  070000  21797.8  ...     NaN     NaN       0

[5 rows x 10 columns]
127.0.0.1 - - [14/Feb/2023 08:00:02] "POST / HTTP/1.1" 200 -
2023-02-14 08:00:03,634:DEBUG:percentile_regression_step2:main.py:154:get_signal:1265985: df_id.iloc[-5:,:] :
                 daytime     hms    close  ...  pct_10  pct_20  factor
144  2023/02/14 05:30:00  053000  21604.1  ...     NaN     NaN       0
145  2023/02/14 06:00:00  060000  21602.6  ...     NaN     NaN       0
146  2023/02/14 06:30:00  063000  21628.6  ...     NaN     NaN       0
147  2023/02/14 07:00:00  070000  21797.8  ...     NaN     NaN       0
148  2023/02/14 07:30:00  073000  21766.2  ...     NaN     NaN       0

[5 rows x 10 columns]
127.0.0.1 - - [14/Feb/2023 08:30:01] "POST / HTTP/1.1" 200 -
2023-02-14 08:30:03,462:DEBUG:percentile_regression_step2:main.py:154:get_signal:1265985: df_id.iloc[-5:,:] :
                 daytime     hms    close  ...  pct_10  pct_20  factor
144  2023/02/14 06:00:00  060000  21602.6  ...     NaN     NaN       0
145  2023/02/14 06:30:00  063000  21628.6  ...     NaN     NaN       0
146  2023/02/14 07:00:00  070000  21797.8  ...     NaN     NaN       0
147  2023/02/14 07:30:00  073000  21766.2  ...     NaN     NaN       0
148  2023/02/14 08:00:00  080000  21748.8  ...     NaN     NaN       0

[5 rows x 10 columns]


## /root/FIL/strategy/pyemd/log.txt ----- -----

17472  20230214   080000    080959  1676333399  21766.1  21757.4
2023-02-14 08:10:01,722:INFO:pyemd2:main.py:127:handleKline:185189: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}
127.0.0.1 - - [14/Feb/2023 08:20:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=11626 

self.closeSec=1676333999, self.tradeDate='20230214', self.openTime='081000', self.closeTime='081959', self.symbol='BTCUSDT', self.open='21757.4', self.close='21758'
2023-02-14 08:20:01,661:INFO:pyemd2:main.py:125:handleKline:185189: self.closeSec=1676333999, self.tradeDate='20230214', self.openTime='081000', self.closeTime='081959',self.symbol='BTCUSDT',self.open='21757.4', self.close='21758'
2023-02-14 08:20:01,683:INFO:pyemd2:main.py:126:handleKline:185189: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17469  20230214   073000    073959  1676331599  21797.8  21787.4
17470  20230214   074000    074959  1676332199  21787.5  21786.7
17471  20230214   075000    075959  1676332799  21786.6  21766.2
17472  20230214   080000    080959  1676333399  21766.1  21757.4
17473  20230214   081000    081959  1676333999  21757.4    21758
2023-02-14 08:20:01,683:INFO:pyemd2:main.py:127:handleKline:185189: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=11627 

self.closeSec=1676334599, self.tradeDate='20230214', self.openTime='082000', self.closeTime='082959', self.symbol='BTCUSDT', self.open='21757.9', self.close='21748.8'
127.0.0.1 - - [14/Feb/2023 08:30:03] "POST / HTTP/1.1" 200 -
2023-02-14 08:30:06,054:INFO:pyemd2:main.py:125:handleKline:185189: self.closeSec=1676334599, self.tradeDate='20230214', self.openTime='082000', self.closeTime='082959',self.symbol='BTCUSDT',self.open='21757.9', self.close='21748.8'
2023-02-14 08:30:06,316:INFO:pyemd2:main.py:126:handleKline:185189: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17470  20230214   074000    074959  1676332199  21787.5  21786.7
17471  20230214   075000    075959  1676332799  21786.6  21766.2
17472  20230214   080000    080959  1676333399  21766.1  21757.4
17473  20230214   081000    081959  1676333999  21757.4    21758
17474  20230214   082000    082959  1676334599  21757.9  21748.8
2023-02-14 08:30:06,317:INFO:pyemd2:main.py:127:handleKline:185189: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}


## /root/FIL/strategy/similarity/log.txt ----- -----

12144  20230214   080000    080959  1676333399  21766.1  21757.4
2023-02-14 08:10:01,714:INFO:testStrategy:main.py:103:handleKline:185174: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}
127.0.0.1 - - [14/Feb/2023 08:20:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=11626 

self.closeSec=1676333999, self.tradeDate='20230214', self.openTime='081000', self.closeTime='081959', self.symbol='BTCUSDT', self.open='21757.4', self.close='21758'
2023-02-14 08:20:01,659:INFO:testStrategy:main.py:101:handleKline:185174: self.closeSec=1676333999, self.tradeDate='20230214', self.openTime='081000', self.closeTime='081959',self.symbol='BTCUSDT',self.open='21757.4', self.close='21758'
2023-02-14 08:20:01,678:INFO:testStrategy:main.py:102:handleKline:185174: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12141  20230214   073000    073959  1676331599  21797.8  21787.4
12142  20230214   074000    074959  1676332199  21787.5  21786.7
12143  20230214   075000    075959  1676332799  21786.6  21766.2
12144  20230214   080000    080959  1676333399  21766.1  21757.4
12145  20230214   081000    081959  1676333999  21757.4    21758
2023-02-14 08:20:01,678:INFO:testStrategy:main.py:103:handleKline:185174: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=11627 

self.closeSec=1676334599, self.tradeDate='20230214', self.openTime='082000', self.closeTime='082959', self.symbol='BTCUSDT', self.open='21757.9', self.close='21748.8'
127.0.0.1 - - [14/Feb/2023 08:30:03] "POST / HTTP/1.1" 200 -
2023-02-14 08:30:06,042:INFO:testStrategy:main.py:101:handleKline:185174: self.closeSec=1676334599, self.tradeDate='20230214', self.openTime='082000', self.closeTime='082959',self.symbol='BTCUSDT',self.open='21757.9', self.close='21748.8'
2023-02-14 08:30:06,292:INFO:testStrategy:main.py:102:handleKline:185174: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12142  20230214   074000    074959  1676332199  21787.5  21786.7
12143  20230214   075000    075959  1676332799  21786.6  21766.2
12144  20230214   080000    080959  1676333399  21766.1  21757.4
12145  20230214   081000    081959  1676333999  21757.4    21758
12146  20230214   082000    082959  1676334599  21757.9  21748.8
2023-02-14 08:30:06,292:INFO:testStrategy:main.py:103:handleKline:185174: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}


## /root/FIL/strategy/sr_min/log.txt ----- -----

127.0.0.1 - - [14/Feb/2023 08:30:01] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=0, self.total=1000000.0, self.flagDict['side']='', self.tradeCount=0, self.count=18684
self.closeSec=1676334599, self.tradeDate='20230214', self.openTime='082500', self.closeTime='082959', self.symbol='BTCUSDT', self.open=21801.7, self.close=21748.8, self.high=21802.3, self.low=21747.8, self.vol=1118.41, self.amt=24356254.799 
2023-02-14 08:30:01,874:INFO:sr_min:main.py:172:handleKline:449472: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5857  20230214   080500    080959  ...         0.0        0.0       0
5858  20230214   081000    081459  ...         0.0        0.0       0
5859  20230214   081500    081959  ...         0.0        0.0       0
5860  20230214   082000    082459  ...         0.0        0.0       0
5861  20230214   082500    082959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-02-14 08:30:01,879:INFO:sr_min:main.py:175:handleKline:449472: self.closeSec=1676334599, self.tradeDate='20230214', self.openTime='082500', self.closeTime='082959',self.symbol='BTCUSDT',self.open=21801.7, self.close=21748.8, self.high=21802.3, self.low=21747.8, self.vol=1118.41, self.amt=24356254.799, ukdf['pct'].iloc[-1]=-0.002426 , ukdf['amount'].iloc[-1]=24356254.799, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5861, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': []}
type(curSign)=<class 'int'>, curSign=0, self.sign=0
127.0.0.1 - - [14/Feb/2023 08:35:01] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=0, self.total=1000000.0, self.flagDict['side']='', self.tradeCount=0, self.count=18685
self.closeSec=1676334899, self.tradeDate='20230214', self.openTime='083000', self.closeTime='083459', self.symbol='BTCUSDT', self.open=21748.9, self.close=21758.4, self.high=21765.6, self.low=21745.0, self.vol=486.845, self.amt=10590541.9183 
2023-02-14 08:35:01,667:INFO:sr_min:main.py:172:handleKline:449472: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5858  20230214   081000    081459  ...         0.0        0.0       0
5859  20230214   081500    081959  ...         0.0        0.0       0
5860  20230214   082000    082459  ...         0.0        0.0       0
5861  20230214   082500    082959  ...         0.0        0.0       0
5862  20230214   083000    083459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-02-14 08:35:01,670:INFO:sr_min:main.py:175:handleKline:449472: self.closeSec=1676334899, self.tradeDate='20230214', self.openTime='083000', self.closeTime='083459',self.symbol='BTCUSDT',self.open=21748.9, self.close=21758.4, self.high=21765.6, self.low=21745.0, self.vol=486.845, self.amt=10590541.9183, ukdf['pct'].iloc[-1]=0.000441 , ukdf['amount'].iloc[-1]=10590541.9183, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5862, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': []}
type(curSign)=<class 'int'>, curSign=0, self.sign=0


## /root/FIL/strategy/s_rsrs/log.txt ----- -----

2023-02-14 04:00:10,926:INFO:s_rsrs:main.py:346:handleOrderFilled:185271: handleOrderFilled: data=OrderType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'clientorderid': '41723F1676318405534I0L65', 'symbol': 'BTCUSDT', 'gatewayorderid': 1676318405695173, 'quantity': '42.94', 'price': '21597.8', 'stopprice': '0', 'ordertype': '', 'side': 'SELL', 'status': 'FILLED', 'positionside': 'SHORT', 'createtime': 1676318405197, 'updatetime': 1676318405695, 'tradetype': 'usdt', 'selfid': 41723, 'filltrades': [TradeType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'tradeid': 1676318405695, 'clientorderid': '41723F1676318405534I0L65', 'price': '21597.8', 'quantity': '42.94', 'commission': '927.409532', 'commissionasset': 'USDT', 'tradetime': 1676318405695, 'tradetype': 'usdt', 'gatetype': 'simulator', 'handletime': 1676318405695}], 'gatetype': 'simulator', 'handletime': 0}
127.0.0.1 - - [14/Feb/2023 04:00:10] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [14/Feb/2023 04:00:11] "POST / HTTP/1.1" 200 -
2023-02-14 04:00:11,058:INFO:s_rsrs:main.py:343:handleOrderNew:185271: handleOrderNew: data=OrderType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'clientorderid': '41724F1676318410908I0L65', 'symbol': 'BTCUSDT', 'gatewayorderid': 1676318411014937, 'quantity': '42.891', 'price': '21599.9', 'stopprice': '0', 'ordertype': '', 'side': 'SELL', 'status': 'FILLED', 'positionside': 'SHORT', 'createtime': 1676318410708, 'updatetime': 1676318411014, 'tradetype': 'usdt', 'selfid': 41724, 'filltrades': [TradeType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'tradeid': 1676318411014, 'clientorderid': '41724F1676318410908I0L65', 'price': '21599.9', 'quantity': '42.891', 'commission': '926.4413109', 'commissionasset': 'USDT', 'tradetime': 1676318411014, 'tradetype': 'usdt', 'gatetype': 'simulator', 'handletime': 1676318411014}], 'gatetype': 'simulator', 'handletime': 0}
127.0.0.1 - - [14/Feb/2023 04:00:11] "POST / HTTP/1.1" 200 -
2023-02-14 04:00:11,329:INFO:s_rsrs:main.py:346:handleOrderFilled:185271: handleOrderFilled: data=OrderType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'clientorderid': '41724F1676318410908I0L65', 'symbol': 'BTCUSDT', 'gatewayorderid': 1676318411014937, 'quantity': '42.891', 'price': '21599.9', 'stopprice': '0', 'ordertype': '', 'side': 'SELL', 'status': 'FILLED', 'positionside': 'SHORT', 'createtime': 1676318410708, 'updatetime': 1676318411014, 'tradetype': 'usdt', 'selfid': 41724, 'filltrades': [TradeType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'tradeid': 1676318411014, 'clientorderid': '41724F1676318410908I0L65', 'price': '21599.9', 'quantity': '42.891', 'commission': '926.4413109', 'commissionasset': 'USDT', 'tradetime': 1676318411014, 'tradetype': 'usdt', 'gatetype': 'simulator', 'handletime': 1676318411014}], 'gatetype': 'simulator', 'handletime': 0}
--handleKline--:  version='2.0.0', self.name='s_rsrs', self.symbol='BTCUSDT', interval='4h', intervalSec=14400, wid=25, thd=0.6, self.sign=-1, self.total=925514.8695891, self.flagDict['side']='sell', self.tradeCount=19, self.count=484
self.closeSec=1676332799, self.tradeDate='20230214', self.openTime='040000', self.closeTime='075959', self.symbol='BTCUSDT', self.open=21597.9, self.close=21766.2, self.high=21840.0, self.low=21552.5, self.vol=54964.095, self.amt=1192266278.44206 
2023-02-14 08:00:02,350:INFO:s_rsrs:main.py:141:handleKline:185271: self.closeSec=1676332799, self.tradeDate='20230214', self.openTime='040000', self.closeTime='075959',self.symbol='BTCUSDT',self.open=21597.9, self.close=21766.2, self.high=21840.0, self.low=21552.5, self.vol=54964.095, self.amt=1192266278.44206 
127.0.0.1 - - [14/Feb/2023 08:00:02] "POST / HTTP/1.1" 200 -
2023-02-14 08:00:02,404:INFO:s_rsrs:main.py:142:handleKline:185271: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime  ...         vol           amt       pct
717  20230213   120000    155959  ...   37460.868  8.178804e+08  0.002582
718  20230213   160000    195959  ...  140932.155  3.044415e+09 -0.011955
719  20230213   200000    235959  ...   76257.797  1.648761e+09 -0.001973
720  20230214   000000    035959  ...  134846.671  2.901605e+09  0.002065
721  20230214   040000    075959  ...   54964.095  1.192266e+09  0.007797

[5 rows x 11 columns]
2023-02-14 08:00:04,657:INFO:s_rsrs:main.py:151:handleKline:185271: df_s.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec  ...  index      beta    zscore  signal
717  20230213   120000    155959  1676275199  ...    717  0.793234  0.870017     1.0
718  20230213   160000    195959  1676289599  ...    718  0.624625 -0.005675     NaN
719  20230213   200000    235959  1676303999  ...    719  0.615151 -0.080985     NaN
720  20230214   000000    035959  1676318399  ...    720  0.212528 -2.193015    -1.0
721  20230214   040000    075959  1676332799  ...    721  0.070486 -2.822363    -1.0

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '42.891', 'enterprice': '21599.9', 'countrevence': '0', 'unrealprofit': '-7128.4842', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '21766.1', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-1, self.sign=-1


