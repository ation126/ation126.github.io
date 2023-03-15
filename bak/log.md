# 20230315 08:26:01

## /root/FIL/strategy/amihud/log.txt ----- -----

127.0.0.1 - - [15/Mar/2023 08:20:01] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=993672.4896432, self.flagDict['side']='sell', self.tradeCount=2, self.count=31036
self.closeSec=1678839599, self.tradeDate='20230315', self.openTime='081500', self.closeTime='081959', self.symbol='BTCUSDT', self.open=24582.1, self.close=24591.8, self.high=24658.0, self.low=24536.9, self.vol=2746.229, self.amt=67566404.8082 
2023-03-15 08:20:01,883:INFO:amihud:main.py:172:handleKline:200676: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5855  20230315   075500    075959  ...         0.0        0.0       0
5856  20230315   080000    080459  ...         0.0        0.0       0
5857  20230315   080500    080959  ...         0.0        0.0       0
5858  20230315   081000    081459  ...         0.0        0.0       0
5859  20230315   081500    081959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-03-15 08:20:01,886:INFO:amihud:main.py:175:handleKline:200676: self.closeSec=1678839599, self.tradeDate='20230315', self.openTime='081500', self.closeTime='081959',self.symbol='BTCUSDT',self.open=24582.1, self.close=24591.8, self.high=24658.0, self.low=24536.9, self.vol=2746.229, self.amt=67566404.8082, ukdf['pct'].iloc[-1]=0.000395 , ukdf['amount'].iloc[-1]=67566404.8082, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5859, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '60.176', 'enterprice': '16529.3', 'countrevence': '0', 'unrealprofit': '-484958.384', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '24588.3', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1
--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=993672.4896432, self.flagDict['side']='sell', self.tradeCount=2, self.count=31037
self.closeSec=1678839899, self.tradeDate='20230315', self.openTime='082000', self.closeTime='082459', self.symbol='BTCUSDT', self.open=24591.8, self.close=24563.5, self.high=24620.0, self.low=24522.5, self.vol=2703.762, self.amt=66420390.5498 
127.0.0.1 - - [15/Mar/2023 08:25:01] "POST / HTTP/1.1" 200 -
2023-03-15 08:25:01,616:INFO:amihud:main.py:172:handleKline:200676: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5856  20230315   080000    080459  ...         0.0        0.0       0
5857  20230315   080500    080959  ...         0.0        0.0       0
5858  20230315   081000    081459  ...         0.0        0.0       0
5859  20230315   081500    081959  ...         0.0        0.0       0
5860  20230315   082000    082459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-03-15 08:25:01,617:INFO:amihud:main.py:175:handleKline:200676: self.closeSec=1678839899, self.tradeDate='20230315', self.openTime='082000', self.closeTime='082459',self.symbol='BTCUSDT',self.open=24591.8, self.close=24563.5, self.high=24620.0, self.low=24522.5, self.vol=2703.762, self.amt=66420390.5498, ukdf['pct'].iloc[-1]=-0.001151 , ukdf['amount'].iloc[-1]=66420390.5498, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5860, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '60.176', 'enterprice': '16529.3', 'countrevence': '0', 'unrealprofit': '-483423.896', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '24562.8', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1


## /root/FIL/strategy/factorcheck/log.txt ----- -----

 version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=103, self.factor=0.2763793143309365, self.count=31602 

self.closeSec=1678839599, self.tradeDate='20230315', self.openTime='081500', self.closeTime='081959', self.symbol='BTCUSDT', self.open=24582.1, self.close=24591.8, self.high=24658.0, self.low=24536.9 
2023-03-15 08:20:01,565:INFO:factorcheck2:main.py:126:handleKline:185239: self.closeSec=1678839599, self.tradeDate='20230315', self.openTime='081500', self.closeTime='081959',self.symbol='BTCUSDT',self.open=24582.1, self.close=24591.8, self.high=24658.0, self.low=24536.9   
2023-03-15 08:20:01,634:INFO:factorcheck2:main.py:127:handleKline:185239: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1535  20230315   075500    075959  1678838399  ...  24669.6 -0.000935   1535    5
1536  20230315   080000    080459  1678838699  ...  24666.6  0.001228   1536    0
1537  20230315   080500    080959  1678838999  ...  24635.0 -0.001825   1537    1
1538  20230315   081000    081459  1678839299  ...  24577.7 -0.003470   1538    2
1539  20230315   081500    081959  1678839599  ...  24536.9  0.000395   1539    3

[5 rows x 11 columns]
2023-03-15 08:20:01,634:INFO:factorcheck2:main.py:128:handleKline:185239: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}
127.0.0.1 - - [15/Mar/2023 08:25:01] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=103, self.factor=0.2763793143309365, self.count=31603 

self.closeSec=1678839899, self.tradeDate='20230315', self.openTime='082000', self.closeTime='082459', self.symbol='BTCUSDT', self.open=24591.8, self.close=24563.5, self.high=24620.0, self.low=24522.5 
2023-03-15 08:25:01,508:INFO:factorcheck2:main.py:126:handleKline:185239: self.closeSec=1678839899, self.tradeDate='20230315', self.openTime='082000', self.closeTime='082459',self.symbol='BTCUSDT',self.open=24591.8, self.close=24563.5, self.high=24620.0, self.low=24522.5   
2023-03-15 08:25:01,553:INFO:factorcheck2:main.py:127:handleKline:185239: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1536  20230315   080000    080459  1678838699  ...  24666.6  0.001228   1536    0
1537  20230315   080500    080959  1678838999  ...  24635.0 -0.001825   1537    1
1538  20230315   081000    081459  1678839299  ...  24577.7 -0.003470   1538    2
1539  20230315   081500    081959  1678839599  ...  24536.9  0.000395   1539    3
1540  20230315   082000    082459  1678839899  ...  24522.5 -0.001151   1540    4

[5 rows x 11 columns]
2023-03-15 08:25:01,553:INFO:factorcheck2:main.py:128:handleKline:185239: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}


## /root/FIL/strategy/logic/log.txt ----- -----

2023-03-15 08:00:34,683:DEBUG:logic:main.py:463:getModel:885513: df_s.iloc[-5:,:] :
          date closeTime     open  ...    alpha58   alpha67   alpha72
5770  20230315    052959  24583.1  ...  54.166667  0.542799  0.388343
5771  20230315    055959  24390.5  ...  54.583333  0.552791  0.413431
5772  20230315    062959  24544.9  ...  54.583333  0.555869  0.435557
5773  20230315    065959  24597.6  ...  55.000000  0.563872  0.452839
5774  20230315    072959  24725.7  ...  54.583333  0.559725  0.470327

[5 rows x 33 columns]
0.5600739371534196
acc is : 0.5600739371534196
2023-03-15 08:00:34,845:INFO:logic:main.py:468:getModel:885513: df_pred.iloc[-5:,:] :
     pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
536     1  0.366095  0.633905       1  ...  1.144396  -1.0    0.0  1.095773
537     0  0.546355  0.453645       1  ...  1.142107  -1.0    0.0  1.097965
538     1  0.454987  0.545013       1  ...  1.136150  -1.0    0.0  1.103692
539     0  0.511709  0.488291       0  ...  1.138526  -1.0    0.0  1.101384
540     1  0.483991  0.516009       1  ...  1.138014  -1.0    0.0  1.101880

[5 rows x 10 columns]
2023-03-15 08:00:34,885:INFO:logic:main.py:478:getModel:885513: df_panel.iloc[-5:,:] :
    pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
45     1  0.365732  0.634268       1  ...  1.122995  -1.0    0.0  1.099651
46     0  0.545910  0.454090       1  ...  1.128952  -1.0    0.0  1.101402
47     1  0.455489  0.544511       1  ...  1.136150  -1.0    0.0  1.105557
48     0  0.511709  0.488291       0  ...  1.138526  -1.0    0.0  1.101384
49     1  0.483991  0.516009       1  ...  1.138014  -1.0    0.0  1.101880

[5 rows x 10 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '31.639', 'enterprice': '24625.7', 'countrevence': '0', 'unrealprofit': '-2288.61644533072', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '24698.03529648', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}


## /root/FIL/strategy/modifiedmom/log.txt ----- -----

623  20230315   075000    075959  1678838399    24704  24682.5 -0.000874
2023-03-15 08:00:02,203:INFO:modifiedmom:main.py:146:handleKline:185213: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=15800 

self.closeSec=1678838999, self.tradeDate='20230315', self.openTime='080000', self.closeTime='080959', self.symbol='BTCUSDT', self.open='24682.5', self.close='24667.7'
2023-03-15 08:10:01,605:INFO:modifiedmom:main.py:144:handleKline:185213: self.closeSec=1678838999, self.tradeDate='20230315', self.openTime='080000', self.closeTime='080959',self.symbol='BTCUSDT',self.open='24682.5', self.close='24667.7'
127.0.0.1 - - [15/Mar/2023 08:10:01] "POST / HTTP/1.1" 200 -
2023-03-15 08:10:01,624:INFO:modifiedmom:main.py:145:handleKline:185213: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
620  20230315   072000    072959  1678836599  24750.1  24674.2 -0.003067
621  20230315   073000    073959  1678837199  24674.3  24687.3  0.000531
622  20230315   074000    074959  1678837799  24687.2  24704.1  0.000681
623  20230315   075000    075959  1678838399    24704  24682.5 -0.000874
624  20230315   080000    080959  1678838999  24682.5  24667.7 -0.000600
2023-03-15 08:10:01,624:INFO:modifiedmom:main.py:146:handleKline:185213: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--: 127.0.0.1 - - [15/Mar/2023 08:20:01] "POST / HTTP/1.1" 200 -
 self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=15801 

self.closeSec=1678839599, self.tradeDate='20230315', self.openTime='081000', self.closeTime='081959', self.symbol='BTCUSDT', self.open='24667.7', self.close='24591.8'
2023-03-15 08:20:01,884:INFO:modifiedmom:main.py:144:handleKline:185213: self.closeSec=1678839599, self.tradeDate='20230315', self.openTime='081000', self.closeTime='081959',self.symbol='BTCUSDT',self.open='24667.7', self.close='24591.8'
2023-03-15 08:20:02,041:INFO:modifiedmom:main.py:145:handleKline:185213: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
621  20230315   073000    073959  1678837199  24674.3  24687.3  0.000531
622  20230315   074000    074959  1678837799  24687.2  24704.1  0.000681
623  20230315   075000    075959  1678838399    24704  24682.5 -0.000874
624  20230315   080000    080959  1678838999  24682.5  24667.7 -0.000600
625  20230315   081000    081959  1678839599  24667.7  24591.8 -0.003077
2023-03-15 08:20:02,041:INFO:modifiedmom:main.py:146:handleKline:185213: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False}


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

17471  20230315   075000    075959  1678838399    24704  24682.5
2023-03-15 08:00:02,225:INFO:pyemd2:main.py:127:handleKline:185189: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=15801 

self.closeSec=1678838999, self.tradeDate='20230315', self.openTime='080000', self.closeTime='080959', self.symbol='BTCUSDT', self.open='24682.5', self.close='24667.7'
2023-03-15 08:10:01,586:INFO:pyemd2:main.py:125:handleKline:185189: self.closeSec=1678838999, self.tradeDate='20230315', self.openTime='080000', self.closeTime='080959',self.symbol='BTCUSDT',self.open='24682.5', self.close='24667.7'
127.0.0.1 - - [15/Mar/2023 08:10:01] "POST / HTTP/1.1" 200 -
2023-03-15 08:10:01,602:INFO:pyemd2:main.py:126:handleKline:185189: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17468  20230315   072000    072959  1678836599  24750.1  24674.2
17469  20230315   073000    073959  1678837199  24674.3  24687.3
17470  20230315   074000    074959  1678837799  24687.2  24704.1
17471  20230315   075000    075959  1678838399    24704  24682.5
17472  20230315   080000    080959  1678838999  24682.5  24667.7
2023-03-15 08:10:01,603:INFO:pyemd2:main.py:127:handleKline:185189: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=15802 

self.closeSec=1678839599, self.tradeDate='20230315', self.openTime='081000', self.closeTime='081959', self.symbol='BTCUSDT', self.open='24667.7', self.close='24591.8'
127.0.0.1 - - [15/Mar/2023 08:20:01] "POST / HTTP/1.1" 200 -
2023-03-15 08:20:02,512:INFO:pyemd2:main.py:125:handleKline:185189: self.closeSec=1678839599, self.tradeDate='20230315', self.openTime='081000', self.closeTime='081959',self.symbol='BTCUSDT',self.open='24667.7', self.close='24591.8'
2023-03-15 08:20:02,552:INFO:pyemd2:main.py:126:handleKline:185189: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17469  20230315   073000    073959  1678837199  24674.3  24687.3
17470  20230315   074000    074959  1678837799  24687.2  24704.1
17471  20230315   075000    075959  1678838399    24704  24682.5
17472  20230315   080000    080959  1678838999  24682.5  24667.7
17473  20230315   081000    081959  1678839599  24667.7  24591.8
2023-03-15 08:20:02,552:INFO:pyemd2:main.py:127:handleKline:185189: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}


## /root/FIL/strategy/similarity/log.txt ----- -----

12143  20230315   075000    075959  1678838399    24704  24682.5
2023-03-15 08:00:02,236:INFO:testStrategy:main.py:103:handleKline:185174: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': True, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}
127.0.0.1 - - [15/Mar/2023 08:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=15801 

self.closeSec=1678838999, self.tradeDate='20230315', self.openTime='080000', self.closeTime='080959', self.symbol='BTCUSDT', self.open='24682.5', self.close='24667.7'
2023-03-15 08:10:01,600:INFO:testStrategy:main.py:101:handleKline:185174: self.closeSec=1678838999, self.tradeDate='20230315', self.openTime='080000', self.closeTime='080959',self.symbol='BTCUSDT',self.open='24682.5', self.close='24667.7'
2023-03-15 08:10:01,629:INFO:testStrategy:main.py:102:handleKline:185174: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12140  20230315   072000    072959  1678836599  24750.1  24674.2
12141  20230315   073000    073959  1678837199  24674.3  24687.3
12142  20230315   074000    074959  1678837799  24687.2  24704.1
12143  20230315   075000    075959  1678838399    24704  24682.5
12144  20230315   080000    080959  1678838999  24682.5  24667.7
2023-03-15 08:10:01,629:INFO:testStrategy:main.py:103:handleKline:185174: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': True, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=15802 

self.closeSec=1678839599, self.tradeDate='20230315', self.openTime='081000', self.closeTime='081959', self.symbol='BTCUSDT', self.open='24667.7', self.close='24591.8'
127.0.0.1 - - [15/Mar/2023 08:20:01] "POST / HTTP/1.1" 200 -
2023-03-15 08:20:02,351:INFO:testStrategy:main.py:101:handleKline:185174: self.closeSec=1678839599, self.tradeDate='20230315', self.openTime='081000', self.closeTime='081959',self.symbol='BTCUSDT',self.open='24667.7', self.close='24591.8'
2023-03-15 08:20:02,491:INFO:testStrategy:main.py:102:handleKline:185174: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12141  20230315   073000    073959  1678837199  24674.3  24687.3
12142  20230315   074000    074959  1678837799  24687.2  24704.1
12143  20230315   075000    075959  1678838399    24704  24682.5
12144  20230315   080000    080959  1678838999  24682.5  24667.7
12145  20230315   081000    081959  1678839599  24667.7  24591.8
2023-03-15 08:20:02,491:INFO:testStrategy:main.py:103:handleKline:185174: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': True, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}


## /root/FIL/strategy/sr_min/log.txt ----- -----

127.0.0.1 - - [15/Mar/2023 08:20:01] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=0, self.total=1000000.0, self.flagDict['side']='', self.tradeCount=0, self.count=27034
self.closeSec=1678839599, self.tradeDate='20230315', self.openTime='081500', self.closeTime='081959', self.symbol='BTCUSDT', self.open=24582.1, self.close=24591.8, self.high=24658.0, self.low=24536.9, self.vol=2746.229, self.amt=67566404.8082 
2023-03-15 08:20:01,610:INFO:sr_min:main.py:172:handleKline:449472: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5855  20230315   075500    075959  ...         0.0        0.0       0
5856  20230315   080000    080459  ...         0.0        0.0       0
5857  20230315   080500    080959  ...         0.0        0.0       0
5858  20230315   081000    081459  ...         0.0        0.0       0
5859  20230315   081500    081959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-03-15 08:20:01,616:INFO:sr_min:main.py:175:handleKline:449472: self.closeSec=1678839599, self.tradeDate='20230315', self.openTime='081500', self.closeTime='081959',self.symbol='BTCUSDT',self.open=24582.1, self.close=24591.8, self.high=24658.0, self.low=24536.9, self.vol=2746.229, self.amt=67566404.8082, ukdf['pct'].iloc[-1]=0.000395 , ukdf['amount'].iloc[-1]=67566404.8082, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5859, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': []}
type(curSign)=<class 'int'>, curSign=0, self.sign=0
127.0.0.1 - - [15/Mar/2023 08:25:01] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=0, self.total=1000000.0, self.flagDict['side']='', self.tradeCount=0, self.count=27035
self.closeSec=1678839899, self.tradeDate='20230315', self.openTime='082000', self.closeTime='082459', self.symbol='BTCUSDT', self.open=24591.8, self.close=24563.5, self.high=24620.0, self.low=24522.5, self.vol=2703.762, self.amt=66420390.5498 
2023-03-15 08:25:01,572:INFO:sr_min:main.py:172:handleKline:449472: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5856  20230315   080000    080459  ...         0.0        0.0       0
5857  20230315   080500    080959  ...         0.0        0.0       0
5858  20230315   081000    081459  ...         0.0        0.0       0
5859  20230315   081500    081959  ...         0.0        0.0       0
5860  20230315   082000    082459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-03-15 08:25:01,572:INFO:sr_min:main.py:175:handleKline:449472: self.closeSec=1678839899, self.tradeDate='20230315', self.openTime='082000', self.closeTime='082459',self.symbol='BTCUSDT',self.open=24591.8, self.close=24563.5, self.high=24620.0, self.low=24522.5, self.vol=2703.762, self.amt=66420390.5498, ukdf['pct'].iloc[-1]=-0.001151 , ukdf['amount'].iloc[-1]=66420390.5498, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5860, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': []}
type(curSign)=<class 'int'>, curSign=0, self.sign=0


## /root/FIL/strategy/s_rsrs/log.txt ----- -----

719  20230314   200000    235959  1678809599  ...    719  1.158051  2.045910     1.0
720  20230315   000000    035959  1678823999  ...    720  1.232075  2.223976     1.0

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '55.825', 'enterprice': '20070', 'countrevence': '0', 'unrealprofit': '280469.08074529575', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '25094.07668151', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=1, self.sign=1
--handleKline--:  version='2.0.0', self.name='s_rsrs', self.symbol='BTCUSDT', interval='4h', intervalSec=14400, wid=25, thd=0.6, self.sign=1, self.total=1119287.34225, self.flagDict['side']='buy', self.tradeCount=24, self.count=658
self.closeSec=1678838399, self.tradeDate='20230315', self.openTime='040000', self.closeTime='075959', self.symbol='BTCUSDT', self.open=25066.4, self.close=24682.5, self.high=25184.0, self.low=23951.0, self.vol=240076.01, self.amt=5904619850.52422 
127.0.0.1 - - [15/Mar/2023 08:00:02] "POST / HTTP/1.1" 200 -
2023-03-15 08:00:02,060:INFO:s_rsrs:main.py:141:handleKline:185271: self.closeSec=1678838399, self.tradeDate='20230315', self.openTime='040000', self.closeTime='075959',self.symbol='BTCUSDT',self.open=25066.4, self.close=24682.5, self.high=25184.0, self.low=23951.0, self.vol=240076.01, self.amt=5904619850.52422 
2023-03-15 08:00:02,091:INFO:s_rsrs:main.py:142:handleKline:185271: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime  ...         vol           amt       pct
717  20230314   120000    155959  ...  154883.625  3.782950e+09 -0.005250
718  20230314   160000    195959  ...  156510.376  3.834140e+09  0.020427
719  20230314   200000    235959  ...  572682.237  1.469777e+10  0.047035
720  20230315   000000    035959  ...  344588.234  8.672309e+09 -0.032854
721  20230315   040000    075959  ...  240076.010  5.904620e+09 -0.015064

[5 rows x 11 columns]
2023-03-15 08:00:04,664:INFO:s_rsrs:main.py:151:handleKline:185271: df_s.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec  ...  index      beta    zscore  signal
717  20230314   120000    155959  1678780799  ...    717  1.056560  1.757535     1.0
718  20230314   160000    195959  1678795199  ...    718  1.049601  1.716673     1.0
719  20230314   200000    235959  1678809599  ...    719  1.158051  2.045910     1.0
720  20230315   000000    035959  1678823999  ...    720  1.232075  2.223976     1.0
721  20230315   040000    075959  1678838399  ...    721  1.246479  2.193121     1.0

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '55.825', 'enterprice': '20070', 'countrevence': '0', 'unrealprofit': '257481.6475', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '24682.3', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=1, self.sign=1


