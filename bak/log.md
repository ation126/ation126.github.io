# 20230224 08:26:02

## /root/FIL/strategy/amihud/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=993672.4896432, self.flagDict['side']='sell', self.tradeCount=2, self.count=25564
self.closeSec=1677197999, self.tradeDate='20230224', self.openTime='081500', self.closeTime='081959', self.symbol='BTCUSDT', self.open=23961.0, self.close=23993.8, self.high=24005.4, self.low=23939.0, self.vol=1674.363, self.amt=40122672.9405 
127.0.0.1 - - [24/Feb/2023 08:20:01] "POST / HTTP/1.1" 200 -
2023-02-24 08:20:01,885:INFO:amihud:main.py:172:handleKline:200676: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5855  20230224   075500    075959  ...         0.0        0.0       0
5856  20230224   080000    080459  ...         0.0        0.0       0
5857  20230224   080500    080959  ...         0.0        0.0       0
5858  20230224   081000    081459  ...         0.0        0.0       0
5859  20230224   081500    081959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-02-24 08:20:01,886:INFO:amihud:main.py:175:handleKline:200676: self.closeSec=1677197999, self.tradeDate='20230224', self.openTime='081500', self.closeTime='081959',self.symbol='BTCUSDT',self.open=23961.0, self.close=23993.8, self.high=24005.4, self.low=23939.0, self.vol=1674.363, self.amt=40122672.9405, ukdf['pct'].iloc[-1]=0.001369 , ukdf['amount'].iloc[-1]=40122672.9405, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5859, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '60.176', 'enterprice': '16529.3', 'countrevence': '0', 'unrealprofit': '-449195.0746349224', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '23993.98815865', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1
--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=993672.4896432, self.flagDict['side']='sell', self.tradeCount=2, self.count=25565
self.closeSec=1677198299, self.tradeDate='20230224', self.openTime='082000', self.closeTime='082459', self.symbol='BTCUSDT', self.open=23993.8, self.close=23938.8, self.high=24000.0, self.low=23933.6, self.vol=1399.798, self.amt=33541110.2707 
127.0.0.1 - - [24/Feb/2023 08:25:01] "POST / HTTP/1.1" 200 -
2023-02-24 08:25:01,592:INFO:amihud:main.py:172:handleKline:200676: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5856  20230224   080000    080459  ...         0.0        0.0       0
5857  20230224   080500    080959  ...         0.0        0.0       0
5858  20230224   081000    081459  ...         0.0        0.0       0
5859  20230224   081500    081959  ...         0.0        0.0       0
5860  20230224   082000    082459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-02-24 08:25:01,592:INFO:amihud:main.py:175:handleKline:200676: self.closeSec=1677198299, self.tradeDate='20230224', self.openTime='082000', self.closeTime='082459',self.symbol='BTCUSDT',self.open=23993.8, self.close=23938.8, self.high=24000.0, self.low=23933.6, self.vol=1399.798, self.amt=33541110.2707, ukdf['pct'].iloc[-1]=-0.002292 , ukdf['amount'].iloc[-1]=33541110.2707, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5860, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '60.176', 'enterprice': '16529.3', 'countrevence': '0', 'unrealprofit': '-445993.71866747584', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '23940.78827884', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1


## /root/FIL/strategy/factorcheck/log.txt ----- -----

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.6085703893686535, self.count=26130 

self.closeSec=1677197999, self.tradeDate='20230224', self.openTime='081500', self.closeTime='081959', self.symbol='BTCUSDT', self.open=23961.0, self.close=23993.8, self.high=24005.4, self.low=23939.0 
2023-02-24 08:20:01,574:INFO:factorcheck2:main.py:126:handleKline:185239: self.closeSec=1677197999, self.tradeDate='20230224', self.openTime='081500', self.closeTime='081959',self.symbol='BTCUSDT',self.open=23961.0, self.close=23993.8, self.high=24005.4, self.low=23939.0   
2023-02-24 08:20:01,600:INFO:factorcheck2:main.py:127:handleKline:185239: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1535  20230224   075500    075959  1677196799  ...  23917.0 -0.000230   1535    5
1536  20230224   080000    080459  1677197099  ...  23904.3  0.000827   1536    0
1537  20230224   080500    080959  1677197399  ...  23930.0  0.001470   1537    1
1538  20230224   081000    081459  1677197699  ...  23946.3 -0.000946   1538    2
1539  20230224   081500    081959  1677197999  ...  23939.0  0.001369   1539    3

[5 rows x 11 columns]
2023-02-24 08:20:01,600:INFO:factorcheck2:main.py:128:handleKline:185239: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': False, 'isOpen': True, 'isClose': False, 'isTrig': True}

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.6085703893686535, self.count=26131 

self.closeSec=1677198299, self.tradeDate='20230224', self.openTime='082000', self.closeTime='082459', self.symbol='BTCUSDT', self.open=23993.8, self.close=23938.8, self.high=24000.0, self.low=23933.6 
2023-02-24 08:25:01,570:INFO:factorcheck2:main.py:126:handleKline:185239: self.closeSec=1677198299, self.tradeDate='20230224', self.openTime='082000', self.closeTime='082459',self.symbol='BTCUSDT',self.open=23993.8, self.close=23938.8, self.high=24000.0, self.low=23933.6   
127.0.0.1 - - [24/Feb/2023 08:25:01] "POST / HTTP/1.1" 200 -
2023-02-24 08:25:01,651:INFO:factorcheck2:main.py:127:handleKline:185239: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1536  20230224   080000    080459  1677197099  ...  23904.3  0.000827   1536    0
1537  20230224   080500    080959  1677197399  ...  23930.0  0.001470   1537    1
1538  20230224   081000    081459  1677197699  ...  23946.3 -0.000946   1538    2
1539  20230224   081500    081959  1677197999  ...  23939.0  0.001369   1539    3
1540  20230224   082000    082459  1677198299  ...  23933.6 -0.002292   1540    4

[5 rows x 11 columns]
2023-02-24 08:25:01,653:INFO:factorcheck2:main.py:128:handleKline:185239: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': False, 'isOpen': True, 'isClose': False, 'isTrig': True}


## /root/FIL/strategy/logic/log.txt ----- -----

2023-02-24 08:00:34,463:DEBUG:logic:main.py:463:getModel:885513: df_s.iloc[-5:,:] :
          date closeTime     open  ...    alpha58   alpha67   alpha72
5770  20230224    052959  23933.2  ...  49.583333  0.467668  0.582127
5771  20230224    055959  23939.4  ...  49.583333  0.456423  0.591962
5772  20230224    062959  23859.8  ...  49.166667  0.451841  0.603340
5773  20230224    065959  23827.0  ...  49.583333  0.456327  0.612188
5774  20230224    072959  23853.4  ...  49.583333  0.459647  0.618397

[5 rows x 33 columns]
0.5286506469500925
acc is : 0.5286506469500925
2023-02-24 08:00:34,616:INFO:logic:main.py:468:getModel:885513: df_pred.iloc[-5:,:] :
     pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
536     0  0.513884  0.486116       0  ...  0.989941   1.0    0.0  1.083837
537     1  0.478899  0.521101       0  ...  0.988576   1.0    0.0  1.082342
538     1  0.484840  0.515160       1  ...  0.989675   1.0    0.0  1.083546
539     1  0.494519  0.505481       1  ...  0.990484   1.0    0.0  1.084432
540     0  0.501238  0.498762       1  ...  0.992799   1.0    0.0  1.086967

[5 rows x 10 columns]
2023-02-24 08:00:34,653:INFO:logic:main.py:478:getModel:885513: df_panel.iloc[-5:,:] :
    pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
45     0  0.513513  0.486487       0  ...  0.989941   1.0    0.0  1.087934
46     1  0.479522  0.520478       0  ...  0.965863   1.0    0.0  1.086736
47     1  0.484143  0.515857       1  ...  0.989675   1.0    0.0  1.084669
48     1  0.494519  0.505481       1  ...  0.990484   1.0    0.0  1.084432
49     0  0.501238  0.498762       1  ...  0.992799   1.0    0.0  1.086967

[5 rows x 10 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '33.103', 'enterprice': '23978.6', 'countrevence': '0', 'unrealprofit': '-996.4003', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '23948.5', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}


## /root/FIL/strategy/modifiedmom/log.txt ----- -----

623  20230224   075000    075959  1677196799  23917.2  23928.7  0.000485
2023-02-24 08:00:02,096:INFO:modifiedmom:main.py:146:handleKline:185213: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=13064 

self.closeSec=1677197399, self.tradeDate='20230224', self.openTime='080000', self.closeTime='080959', self.symbol='BTCUSDT', self.open='23928.7', self.close='23983.7'
2023-02-24 08:10:01,868:INFO:modifiedmom:main.py:144:handleKline:185213: self.closeSec=1677197399, self.tradeDate='20230224', self.openTime='080000', self.closeTime='080959',self.symbol='BTCUSDT',self.open='23928.7', self.close='23983.7'
127.0.0.1 - - [24/Feb/2023 08:10:01] "POST / HTTP/1.1" 200 -
2023-02-24 08:10:01,894:INFO:modifiedmom:main.py:145:handleKline:185213: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
620  20230224   072000    072959  1677194999  23832.5  23872.9  0.001699
621  20230224   073000    073959  1677195599    23873  23883.8  0.000457
622  20230224   074000    074959  1677196199  23883.7  23917.1  0.001394
623  20230224   075000    075959  1677196799  23917.2  23928.7  0.000485
624  20230224   080000    080959  1677197399  23928.7  23983.7  0.002298
2023-02-24 08:10:01,894:INFO:modifiedmom:main.py:146:handleKline:185213: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=13065 

self.closeSec=1677197999, self.tradeDate='20230224', self.openTime='081000', self.closeTime='081959', self.symbol='BTCUSDT', self.open='23983.7', self.close='23993.8'
127.0.0.1 - - [24/Feb/2023 08:20:01] "POST / HTTP/1.1" 200 -
2023-02-24 08:20:01,699:INFO:modifiedmom:main.py:144:handleKline:185213: self.closeSec=1677197999, self.tradeDate='20230224', self.openTime='081000', self.closeTime='081959',self.symbol='BTCUSDT',self.open='23983.7', self.close='23993.8'
2023-02-24 08:20:01,742:INFO:modifiedmom:main.py:145:handleKline:185213: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
621  20230224   073000    073959  1677195599    23873  23883.8  0.000457
622  20230224   074000    074959  1677196199  23883.7  23917.1  0.001394
623  20230224   075000    075959  1677196799  23917.2  23928.7  0.000485
624  20230224   080000    080959  1677197399  23928.7  23983.7  0.002298
625  20230224   081000    081959  1677197999  23983.7  23993.8  0.000421
2023-02-24 08:20:01,744:INFO:modifiedmom:main.py:146:handleKline:185213: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False}


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

17471  20230224   075000    075959  1677196799  23917.2  23928.7
2023-02-24 08:00:02,164:INFO:pyemd2:main.py:127:handleKline:185189: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}
127.0.0.1 - - [24/Feb/2023 08:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=13065 

self.closeSec=1677197399, self.tradeDate='20230224', self.openTime='080000', self.closeTime='080959', self.symbol='BTCUSDT', self.open='23928.7', self.close='23983.7'
2023-02-24 08:10:01,855:INFO:pyemd2:main.py:125:handleKline:185189: self.closeSec=1677197399, self.tradeDate='20230224', self.openTime='080000', self.closeTime='080959',self.symbol='BTCUSDT',self.open='23928.7', self.close='23983.7'
2023-02-24 08:10:01,892:INFO:pyemd2:main.py:126:handleKline:185189: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17468  20230224   072000    072959  1677194999  23832.5  23872.9
17469  20230224   073000    073959  1677195599    23873  23883.8
17470  20230224   074000    074959  1677196199  23883.7  23917.1
17471  20230224   075000    075959  1677196799  23917.2  23928.7
17472  20230224   080000    080959  1677197399  23928.7  23983.7
2023-02-24 08:10:01,892:INFO:pyemd2:main.py:127:handleKline:185189: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}
127.0.0.1 - - [24/Feb/2023 08:20:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=13066 

self.closeSec=1677197999, self.tradeDate='20230224', self.openTime='081000', self.closeTime='081959', self.symbol='BTCUSDT', self.open='23983.7', self.close='23993.8'
2023-02-24 08:20:01,718:INFO:pyemd2:main.py:125:handleKline:185189: self.closeSec=1677197999, self.tradeDate='20230224', self.openTime='081000', self.closeTime='081959',self.symbol='BTCUSDT',self.open='23983.7', self.close='23993.8'
2023-02-24 08:20:01,761:INFO:pyemd2:main.py:126:handleKline:185189: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17469  20230224   073000    073959  1677195599    23873  23883.8
17470  20230224   074000    074959  1677196199  23883.7  23917.1
17471  20230224   075000    075959  1677196799  23917.2  23928.7
17472  20230224   080000    080959  1677197399  23928.7  23983.7
17473  20230224   081000    081959  1677197999  23983.7  23993.8
2023-02-24 08:20:01,762:INFO:pyemd2:main.py:127:handleKline:185189: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}


## /root/FIL/strategy/similarity/log.txt ----- -----

12143  20230224   075000    075959  1677196799  23917.2  23928.7
2023-02-24 08:00:02,105:INFO:testStrategy:main.py:103:handleKline:185174: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': True, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=13065 

self.closeSec=1677197399, self.tradeDate='20230224', self.openTime='080000', self.closeTime='080959', self.symbol='BTCUSDT', self.open='23928.7', self.close='23983.7'
2023-02-24 08:10:01,878:INFO:testStrategy:main.py:101:handleKline:185174: self.closeSec=1677197399, self.tradeDate='20230224', self.openTime='080000', self.closeTime='080959',self.symbol='BTCUSDT',self.open='23928.7', self.close='23983.7'
127.0.0.1 - - [24/Feb/2023 08:10:01] "POST / HTTP/1.1" 200 -
2023-02-24 08:10:01,889:INFO:testStrategy:main.py:102:handleKline:185174: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12140  20230224   072000    072959  1677194999  23832.5  23872.9
12141  20230224   073000    073959  1677195599    23873  23883.8
12142  20230224   074000    074959  1677196199  23883.7  23917.1
12143  20230224   075000    075959  1677196799  23917.2  23928.7
12144  20230224   080000    080959  1677197399  23928.7  23983.7
2023-02-24 08:10:01,889:INFO:testStrategy:main.py:103:handleKline:185174: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': True, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}
127.0.0.1 - - [24/Feb/2023 08:20:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=13066 

self.closeSec=1677197999, self.tradeDate='20230224', self.openTime='081000', self.closeTime='081959', self.symbol='BTCUSDT', self.open='23983.7', self.close='23993.8'
2023-02-24 08:20:01,712:INFO:testStrategy:main.py:101:handleKline:185174: self.closeSec=1677197999, self.tradeDate='20230224', self.openTime='081000', self.closeTime='081959',self.symbol='BTCUSDT',self.open='23983.7', self.close='23993.8'
2023-02-24 08:20:01,756:INFO:testStrategy:main.py:102:handleKline:185174: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12141  20230224   073000    073959  1677195599    23873  23883.8
12142  20230224   074000    074959  1677196199  23883.7  23917.1
12143  20230224   075000    075959  1677196799  23917.2  23928.7
12144  20230224   080000    080959  1677197399  23928.7  23983.7
12145  20230224   081000    081959  1677197999  23983.7  23993.8
2023-02-24 08:20:01,756:INFO:testStrategy:main.py:103:handleKline:185174: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': True, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}


## /root/FIL/strategy/sr_min/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=0, self.total=1000000.0, self.flagDict['side']='', self.tradeCount=0, self.count=21562
self.closeSec=1677197999, self.tradeDate='20230224', self.openTime='081500', self.closeTime='081959', self.symbol='BTCUSDT', self.open=23961.0, self.close=23993.8, self.high=24005.4, self.low=23939.0, self.vol=1674.363, self.amt=40122672.9405 
127.0.0.1 - - [24/Feb/2023 08:20:01] "POST / HTTP/1.1" 200 -
2023-02-24 08:20:01,611:INFO:sr_min:main.py:172:handleKline:449472: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5855  20230224   075500    075959  ...         0.0        0.0       0
5856  20230224   080000    080459  ...         0.0        0.0       0
5857  20230224   080500    080959  ...         0.0        0.0       0
5858  20230224   081000    081459  ...         0.0        0.0       0
5859  20230224   081500    081959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-02-24 08:20:01,612:INFO:sr_min:main.py:175:handleKline:449472: self.closeSec=1677197999, self.tradeDate='20230224', self.openTime='081500', self.closeTime='081959',self.symbol='BTCUSDT',self.open=23961.0, self.close=23993.8, self.high=24005.4, self.low=23939.0, self.vol=1674.363, self.amt=40122672.9405, ukdf['pct'].iloc[-1]=0.001369 , ukdf['amount'].iloc[-1]=40122672.9405, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5859, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': []}
type(curSign)=<class 'int'>, curSign=0, self.sign=0
127.0.0.1 - - [24/Feb/2023 08:25:01] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=0, self.total=1000000.0, self.flagDict['side']='', self.tradeCount=0, self.count=21563
self.closeSec=1677198299, self.tradeDate='20230224', self.openTime='082000', self.closeTime='082459', self.symbol='BTCUSDT', self.open=23993.8, self.close=23938.8, self.high=24000.0, self.low=23933.6, self.vol=1399.798, self.amt=33541110.2707 
2023-02-24 08:25:01,692:INFO:sr_min:main.py:172:handleKline:449472: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5856  20230224   080000    080459  ...         0.0        0.0       0
5857  20230224   080500    080959  ...         0.0        0.0       0
5858  20230224   081000    081459  ...         0.0        0.0       0
5859  20230224   081500    081959  ...         0.0        0.0       0
5860  20230224   082000    082459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-02-24 08:25:01,692:INFO:sr_min:main.py:175:handleKline:449472: self.closeSec=1677198299, self.tradeDate='20230224', self.openTime='082000', self.closeTime='082459',self.symbol='BTCUSDT',self.open=23993.8, self.close=23938.8, self.high=24000.0, self.low=23933.6, self.vol=1399.798, self.amt=33541110.2707, ukdf['pct'].iloc[-1]=-0.002292 , ukdf['amount'].iloc[-1]=33541110.2707, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5860, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': []}
type(curSign)=<class 'int'>, curSign=0, self.sign=0


## /root/FIL/strategy/s_rsrs/log.txt ----- -----

719  20230223   200000    235959  1677167999  ...    719  0.487523 -0.279294     NaN
720  20230224   000000    035959  1677182399  ...    720  0.513627 -0.220280     NaN

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '36.465', 'enterprice': '24934.8', 'countrevence': '0', 'unrealprofit': '35294.2379010936', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '23966.90646096', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-9223372036854775808, self.sign=-1
--handleKline--:  version='2.0.0', self.name='s_rsrs', self.symbol='BTCUSDT', interval='4h', intervalSec=14400, wid=25, thd=0.6, self.sign=-1, self.total=908338.234518, self.flagDict['side']='sell', self.tradeCount=21, self.count=544
self.closeSec=1677196799, self.tradeDate='20230224', self.openTime='040000', self.closeTime='075959', self.symbol='BTCUSDT', self.open=23962.3, self.close=23928.7, self.high=24061.6, self.low=23750.0, self.vol=60185.891, self.amt=1438425201.3548 
127.0.0.1 - - [24/Feb/2023 08:00:01] "POST / HTTP/1.1" 200 -
2023-02-24 08:00:01,924:INFO:s_rsrs:main.py:141:handleKline:185271: self.closeSec=1677196799, self.tradeDate='20230224', self.openTime='040000', self.closeTime='075959',self.symbol='BTCUSDT',self.open=23962.3, self.close=23928.7, self.high=24061.6, self.low=23750.0, self.vol=60185.891, self.amt=1438425201.3548 
2023-02-24 08:00:01,942:INFO:s_rsrs:main.py:142:handleKline:185271: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime  ...         vol           amt       pct
717  20230223   120000    155959  ...   53133.370  1.296761e+09 -0.003232
718  20230223   160000    195959  ...  159749.202  3.839201e+09 -0.024547
719  20230223   200000    235959  ...  246653.418  5.911671e+09  0.007271
720  20230224   000000    035959  ...  126451.880  3.018235e+09  0.000927
721  20230224   040000    075959  ...   60185.891  1.438425e+09 -0.001398

[5 rows x 11 columns]
2023-02-24 08:00:04,151:INFO:s_rsrs:main.py:151:handleKline:185271: df_s.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec  ...  index      beta    zscore  signal
717  20230223   120000    155959  1677139199  ...    717  0.515010 -0.206087     NaN
718  20230223   160000    195959  1677153599  ...    718  0.446420 -0.377574     NaN
719  20230223   200000    235959  1677167999  ...    719  0.487523 -0.279294     NaN
720  20230224   000000    035959  1677182399  ...    720  0.513627 -0.220280     NaN
721  20230224   040000    075959  1677196799  ...    721  0.559513 -0.113242     NaN

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '36.465', 'enterprice': '24934.8', 'countrevence': '0', 'unrealprofit': '36687.4365', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '23928.7', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-9223372036854775808, self.sign=-1


