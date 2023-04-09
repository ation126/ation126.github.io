# 20230409 08:26:01

## /root/FIL/strategy/amihud/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=993672.4896432, self.flagDict['side']='sell', self.tradeCount=2, self.count=38236
self.closeSec=1680999599, self.tradeDate='20230409', self.openTime='081500', self.closeTime='081959', self.symbol='BTCUSDT', self.open=27942.9, self.close=27950.1, self.high=27956.2, self.low=27942.8, self.vol=520.69, self.amt=14552726.6389 
127.0.0.1 - - [09/Apr/2023 08:20:03] "POST / HTTP/1.1" 200 -
2023-04-09 08:20:09,359:INFO:amihud:main.py:172:handleKline:200676: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5855  20230409   075500    075959  ...         0.0        0.0       0
5856  20230409   080000    080459  ...         0.0        0.0       0
5857  20230409   080500    080959  ...         0.0        0.0       0
5858  20230409   081000    081459  ...         0.0        0.0       0
5859  20230409   081500    081959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-04-09 08:20:09,397:INFO:amihud:main.py:175:handleKline:200676: self.closeSec=1680999599, self.tradeDate='20230409', self.openTime='081500', self.closeTime='081959',self.symbol='BTCUSDT',self.open=27942.9, self.close=27950.1, self.high=27956.2, self.low=27942.8, self.vol=520.69, self.amt=14552726.6389, ukdf['pct'].iloc[-1]=0.000258 , ukdf['amount'].iloc[-1]=14552726.6389, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5859, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '60.176', 'enterprice': '16529.3', 'countrevence': '0', 'unrealprofit': '-687350.80506576736', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '27951.64121686', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1
--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=993672.4896432, self.flagDict['side']='sell', self.tradeCount=2, self.count=38237
self.closeSec=1680999899, self.tradeDate='20230409', self.openTime='082000', self.closeTime='082459', self.symbol='BTCUSDT', self.open=27950.1, self.close=27975.0, self.high=27977.0, self.low=27946.7, self.vol=690.086, self.amt=19296357.8878 
127.0.0.1 - - [09/Apr/2023 08:25:01] "POST / HTTP/1.1" 200 -
2023-04-09 08:25:01,616:INFO:amihud:main.py:172:handleKline:200676: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5856  20230409   080000    080459  ...         0.0        0.0       0
5857  20230409   080500    080959  ...         0.0        0.0       0
5858  20230409   081000    081459  ...         0.0        0.0       0
5859  20230409   081500    081959  ...         0.0        0.0       0
5860  20230409   082000    082459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-04-09 08:25:01,617:INFO:amihud:main.py:175:handleKline:200676: self.closeSec=1680999899, self.tradeDate='20230409', self.openTime='082000', self.closeTime='082459',self.symbol='BTCUSDT',self.open=27950.1, self.close=27975.0, self.high=27977.0, self.low=27946.7, self.vol=690.086, self.amt=19296357.8878, ukdf['pct'].iloc[-1]=0.000891 , ukdf['amount'].iloc[-1]=19296357.8878, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5860, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '60.176', 'enterprice': '16529.3', 'countrevence': '0', 'unrealprofit': '-688756.4432', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '27975', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1


## /root/FIL/strategy/factorcheck/log.txt ----- -----


self.closeSec=1680999599, self.tradeDate='20230409', self.openTime='081500', self.closeTime='081959', self.symbol='BTCUSDT', self.open=27942.9, self.close=27950.1, self.high=27956.2, self.low=27942.8 
127.0.0.1 - - [09/Apr/2023 08:20:03] "POST / HTTP/1.1" 200 -
2023-04-09 08:20:06,757:INFO:factorcheck2:main.py:126:handleKline:185239: self.closeSec=1680999599, self.tradeDate='20230409', self.openTime='081500', self.closeTime='081959',self.symbol='BTCUSDT',self.open=27942.9, self.close=27950.1, self.high=27956.2, self.low=27942.8   
2023-04-09 08:20:08,078:INFO:factorcheck2:main.py:127:handleKline:185239: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1535  20230409   075500    075959  1680998399  ...  27913.3  0.000416   1535    5
1536  20230409   080000    080459  1680998699  ...  27907.7 -0.000372   1536    0
1537  20230409   080500    080959  1680998999  ...  27912.7  0.000974   1537    1
1538  20230409   081000    081459  1680999299  ...  27939.3  0.000043   1538    2
1539  20230409   081500    081959  1680999599  ...  27942.8  0.000258   1539    3

[5 rows x 11 columns]
2023-04-09 08:20:08,087:INFO:factorcheck2:main.py:128:handleKline:185239: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=56, self.factor=0.5618633037267947, self.count=38803 

self.closeSec=1680999899, self.tradeDate='20230409', self.openTime='082000', self.closeTime='082459', self.symbol='BTCUSDT', self.open=27950.1, self.close=27975.0, self.high=27977.0, self.low=27946.7 
127.0.0.1 - - [09/Apr/2023 08:25:01] "POST / HTTP/1.1" 200 -
2023-04-09 08:25:01,507:INFO:factorcheck2:main.py:126:handleKline:185239: self.closeSec=1680999899, self.tradeDate='20230409', self.openTime='082000', self.closeTime='082459',self.symbol='BTCUSDT',self.open=27950.1, self.close=27975.0, self.high=27977.0, self.low=27946.7   
2023-04-09 08:25:01,566:INFO:factorcheck2:main.py:127:handleKline:185239: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1536  20230409   080000    080459  1680998699  ...  27907.7 -0.000372   1536    0
1537  20230409   080500    080959  1680998999  ...  27912.7  0.000974   1537    1
1538  20230409   081000    081459  1680999299  ...  27939.3  0.000043   1538    2
1539  20230409   081500    081959  1680999599  ...  27942.8  0.000258   1539    3
1540  20230409   082000    082459  1680999899  ...  27946.7  0.000891   1540    4

[5 rows x 11 columns]
2023-04-09 08:25:01,566:INFO:factorcheck2:main.py:128:handleKline:185239: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}


## /root/FIL/strategy/logic/log.txt ----- -----

2023-04-09 08:00:32,608:DEBUG:logic:main.py:463:getModel:885513: df_s.iloc[-5:,:] :
          date closeTime     open  ...    alpha58   alpha67   alpha72
5770  20230409    052959  27895.5  ...  46.250000  0.478378  0.587400
5771  20230409    055959  27911.9  ...  46.250000  0.481007  0.600529
5772  20230409    062959  27919.5  ...  45.833333  0.465849  0.623521
5773  20230409    065959  27871.2  ...  46.250000  0.483794  0.633371
5774  20230409    072959  27923.3  ...  46.250000  0.490346  0.638210

[5 rows x 33 columns]
0.5600739371534196
acc is : 0.5600739371534196
2023-04-09 08:00:32,767:INFO:logic:main.py:468:getModel:885513: df_pred.iloc[-5:,:] :
     pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
536     0  0.520246  0.479754       1  ...  0.939356   1.0    0.0  1.038641
537     0  0.518095  0.481905       0  ...  0.937737   1.0    0.0  1.036852
538     0  0.503482  0.496518       1  ...  0.939487   1.0    0.0  1.038786
539     0  0.525126  0.474874       1  ...  0.940143   1.0    0.0  1.039512
540     0  0.523170  0.476830       0  ...  0.939541   1.0    0.0  1.038846

[5 rows x 10 columns]
2023-04-09 08:00:32,803:INFO:logic:main.py:478:getModel:885513: df_panel.iloc[-5:,:] :
    pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
45     0  0.519908  0.480092       1  ...  0.939356   1.0    0.0  1.034630
46     0  0.517801  0.482199       0  ...  0.937737   1.0    0.0  1.036316
47     0  0.503933  0.496067       1  ...  0.939487   1.0    0.0  1.039026
48     0  0.525126  0.474874       1  ...  0.940143   1.0    0.0  1.039512
49     0  0.523170  0.476830       0  ...  0.939541   1.0    0.0  1.038846

[5 rows x 10 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': []}


## /root/FIL/strategy/modifiedmom/log.txt ----- -----

623  20230409   075000    075959  1680998399  27931.3  27924.9 -0.000229
2023-04-09 08:00:01,954:INFO:modifiedmom:main.py:146:handleKline:185213: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False}
127.0.0.1 - - [09/Apr/2023 08:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=19400 

self.closeSec=1680998999, self.tradeDate='20230409', self.openTime='080000', self.closeTime='080959', self.symbol='BTCUSDT', self.open='27924.9', self.close='27941.7'
2023-04-09 08:10:01,587:INFO:modifiedmom:main.py:144:handleKline:185213: self.closeSec=1680998999, self.tradeDate='20230409', self.openTime='080000', self.closeTime='080959',self.symbol='BTCUSDT',self.open='27924.9', self.close='27941.7'
2023-04-09 08:10:01,652:INFO:modifiedmom:main.py:145:handleKline:185213: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
620  20230409   072000    072959  1680996599  27950.3  27942.8 -0.000268
621  20230409   073000    073959  1680997199  27942.8  27931.7 -0.000397
622  20230409   074000    074959  1680997799  27931.7  27931.3 -0.000014
623  20230409   075000    075959  1680998399  27931.3  27924.9 -0.000229
624  20230409   080000    080959  1680998999  27924.9  27941.7  0.000602
2023-04-09 08:10:01,652:INFO:modifiedmom:main.py:146:handleKline:185213: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=19401 

self.closeSec=1680999599, self.tradeDate='20230409', self.openTime='081000', self.closeTime='081959', self.symbol='BTCUSDT', self.open='27941.7', self.close='27950.1'
127.0.0.1 - - [09/Apr/2023 08:20:04] "POST / HTTP/1.1" 200 -
2023-04-09 08:20:07,868:INFO:modifiedmom:main.py:144:handleKline:185213: self.closeSec=1680999599, self.tradeDate='20230409', self.openTime='081000', self.closeTime='081959',self.symbol='BTCUSDT',self.open='27941.7', self.close='27950.1'
2023-04-09 08:20:08,767:INFO:modifiedmom:main.py:145:handleKline:185213: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
621  20230409   073000    073959  1680997199  27942.8  27931.7 -0.000397
622  20230409   074000    074959  1680997799  27931.7  27931.3 -0.000014
623  20230409   075000    075959  1680998399  27931.3  27924.9 -0.000229
624  20230409   080000    080959  1680998999  27924.9  27941.7  0.000602
625  20230409   081000    081959  1680999599  27941.7  27950.1  0.000301
2023-04-09 08:20:08,767:INFO:modifiedmom:main.py:146:handleKline:185213: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False}


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

17471  20230409   075000    075959  1680998399  27931.3  27924.9
2023-04-09 08:00:01,972:INFO:pyemd2:main.py:127:handleKline:185189: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}
127.0.0.1 - - [09/Apr/2023 08:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=19401 

self.closeSec=1680998999, self.tradeDate='20230409', self.openTime='080000', self.closeTime='080959', self.symbol='BTCUSDT', self.open='27924.9', self.close='27941.7'
2023-04-09 08:10:01,625:INFO:pyemd2:main.py:125:handleKline:185189: self.closeSec=1680998999, self.tradeDate='20230409', self.openTime='080000', self.closeTime='080959',self.symbol='BTCUSDT',self.open='27924.9', self.close='27941.7'
2023-04-09 08:10:01,685:INFO:pyemd2:main.py:126:handleKline:185189: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17468  20230409   072000    072959  1680996599  27950.3  27942.8
17469  20230409   073000    073959  1680997199  27942.8  27931.7
17470  20230409   074000    074959  1680997799  27931.7  27931.3
17471  20230409   075000    075959  1680998399  27931.3  27924.9
17472  20230409   080000    080959  1680998999  27924.9  27941.7
2023-04-09 08:10:01,685:INFO:pyemd2:main.py:127:handleKline:185189: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=19402 

self.closeSec=1680999599, self.tradeDate='20230409', self.openTime='081000', self.closeTime='081959', self.symbol='BTCUSDT', self.open='27941.7', self.close='27950.1'
127.0.0.1 - - [09/Apr/2023 08:20:05] "POST / HTTP/1.1" 200 -
2023-04-09 08:20:11,371:INFO:pyemd2:main.py:125:handleKline:185189: self.closeSec=1680999599, self.tradeDate='20230409', self.openTime='081000', self.closeTime='081959',self.symbol='BTCUSDT',self.open='27941.7', self.close='27950.1'
2023-04-09 08:20:11,496:INFO:pyemd2:main.py:126:handleKline:185189: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17469  20230409   073000    073959  1680997199  27942.8  27931.7
17470  20230409   074000    074959  1680997799  27931.7  27931.3
17471  20230409   075000    075959  1680998399  27931.3  27924.9
17472  20230409   080000    080959  1680998999  27924.9  27941.7
17473  20230409   081000    081959  1680999599  27941.7  27950.1
2023-04-09 08:20:11,496:INFO:pyemd2:main.py:127:handleKline:185189: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}


## /root/FIL/strategy/similarity/log.txt ----- -----

12143  20230409   075000    075959  1680998399  27931.3  27924.9
2023-04-09 08:00:01,943:INFO:testStrategy:main.py:103:handleKline:185174: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': True, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=19401 

self.closeSec=1680998999, self.tradeDate='20230409', self.openTime='080000', self.closeTime='080959', self.symbol='BTCUSDT', self.open='27924.9', self.close='27941.7'
2023-04-09 08:10:01,584:INFO:testStrategy:main.py:101:handleKline:185174: self.closeSec=1680998999, self.tradeDate='20230409', self.openTime='080000', self.closeTime='080959',self.symbol='BTCUSDT',self.open='27924.9', self.close='27941.7'
127.0.0.1 - - [09/Apr/2023 08:10:01] "POST / HTTP/1.1" 200 -
2023-04-09 08:10:01,606:INFO:testStrategy:main.py:102:handleKline:185174: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12140  20230409   072000    072959  1680996599  27950.3  27942.8
12141  20230409   073000    073959  1680997199  27942.8  27931.7
12142  20230409   074000    074959  1680997799  27931.7  27931.3
12143  20230409   075000    075959  1680998399  27931.3  27924.9
12144  20230409   080000    080959  1680998999  27924.9  27941.7
2023-04-09 08:10:01,606:INFO:testStrategy:main.py:103:handleKline:185174: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': True, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=19402 

self.closeSec=1680999599, self.tradeDate='20230409', self.openTime='081000', self.closeTime='081959', self.symbol='BTCUSDT', self.open='27941.7', self.close='27950.1'
127.0.0.1 - - [09/Apr/2023 08:20:05] "POST / HTTP/1.1" 200 -
2023-04-09 08:20:10,828:INFO:testStrategy:main.py:101:handleKline:185174: self.closeSec=1680999599, self.tradeDate='20230409', self.openTime='081000', self.closeTime='081959',self.symbol='BTCUSDT',self.open='27941.7', self.close='27950.1'
2023-04-09 08:20:11,167:INFO:testStrategy:main.py:102:handleKline:185174: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12141  20230409   073000    073959  1680997199  27942.8  27931.7
12142  20230409   074000    074959  1680997799  27931.7  27931.3
12143  20230409   075000    075959  1680998399  27931.3  27924.9
12144  20230409   080000    080959  1680998999  27924.9  27941.7
12145  20230409   081000    081959  1680999599  27941.7  27950.1
2023-04-09 08:20:11,167:INFO:testStrategy:main.py:103:handleKline:185174: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': True, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}


## /root/FIL/strategy/sr_min/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=0, self.total=1000000.0, self.flagDict['side']='', self.tradeCount=0, self.count=34234
self.closeSec=1680999599, self.tradeDate='20230409', self.openTime='081500', self.closeTime='081959', self.symbol='BTCUSDT', self.open=27942.9, self.close=27950.1, self.high=27956.2, self.low=27942.8, self.vol=520.69, self.amt=14552726.6389 
127.0.0.1 - - [09/Apr/2023 08:20:03] "POST / HTTP/1.1" 200 -
2023-04-09 08:20:08,618:INFO:sr_min:main.py:172:handleKline:449472: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5855  20230409   075500    075959  ...         0.0        0.0       0
5856  20230409   080000    080459  ...         0.0        0.0       0
5857  20230409   080500    080959  ...         0.0        0.0       0
5858  20230409   081000    081459  ...         0.0        0.0       0
5859  20230409   081500    081959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-04-09 08:20:08,657:INFO:sr_min:main.py:175:handleKline:449472: self.closeSec=1680999599, self.tradeDate='20230409', self.openTime='081500', self.closeTime='081959',self.symbol='BTCUSDT',self.open=27942.9, self.close=27950.1, self.high=27956.2, self.low=27942.8, self.vol=520.69, self.amt=14552726.6389, ukdf['pct'].iloc[-1]=0.000258 , ukdf['amount'].iloc[-1]=14552726.6389, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5859, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': []}
type(curSign)=<class 'int'>, curSign=0, self.sign=0
--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=0, self.total=1000000.0, self.flagDict['side']='', self.tradeCount=0, self.count=34235
self.closeSec=1680999899, self.tradeDate='20230409', self.openTime='082000', self.closeTime='082459', self.symbol='BTCUSDT', self.open=27950.1, self.close=27975.0, self.high=27977.0, self.low=27946.7, self.vol=690.086, self.amt=19296357.8878 
127.0.0.1 - - [09/Apr/2023 08:25:01] "POST / HTTP/1.1" 200 -
2023-04-09 08:25:01,629:INFO:sr_min:main.py:172:handleKline:449472: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5856  20230409   080000    080459  ...         0.0        0.0       0
5857  20230409   080500    080959  ...         0.0        0.0       0
5858  20230409   081000    081459  ...         0.0        0.0       0
5859  20230409   081500    081959  ...         0.0        0.0       0
5860  20230409   082000    082459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-04-09 08:25:01,629:INFO:sr_min:main.py:175:handleKline:449472: self.closeSec=1680999899, self.tradeDate='20230409', self.openTime='082000', self.closeTime='082459',self.symbol='BTCUSDT',self.open=27950.1, self.close=27975.0, self.high=27977.0, self.low=27946.7, self.vol=690.086, self.amt=19296357.8878, ukdf['pct'].iloc[-1]=0.000891 , ukdf['amount'].iloc[-1]=19296357.8878, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5860, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': []}
type(curSign)=<class 'int'>, curSign=0, self.sign=0


## /root/FIL/strategy/s_rsrs/log.txt ----- -----

719  20230408   200000    235959  1680969599  ...    719  0.255298  0.032437     NaN
720  20230409   000000    035959  1680983999  ...    720  0.268087  0.080000     NaN

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '52.088', 'enterprice': '28398.8', 'countrevence': '0', 'unrealprofit': '25483.83563095672', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '27909.55419231', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-9223372036854775808, self.sign=-1
127.0.0.1 - - [09/Apr/2023 08:00:01] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='s_rsrs', self.symbol='BTCUSDT', interval='4h', intervalSec=14400, wid=25, thd=0.6, self.sign=-1, self.total=1477757.4577056, self.flagDict['side']='sell', self.tradeCount=29, self.count=808
self.closeSec=1680998399, self.tradeDate='20230409', self.openTime='040000', self.closeTime='075959', self.symbol='BTCUSDT', self.open=27909.2, self.close=27924.9, self.high=27977.1, self.low=27866.4, self.vol=19235.488, self.amt=537094783.2993 
2023-04-09 08:00:01,795:INFO:s_rsrs:main.py:141:handleKline:185271: self.closeSec=1680998399, self.tradeDate='20230409', self.openTime='040000', self.closeTime='075959',self.symbol='BTCUSDT',self.open=27909.2, self.close=27924.9, self.high=27977.1, self.low=27866.4, self.vol=19235.488, self.amt=537094783.2993 
2023-04-09 08:00:01,841:INFO:s_rsrs:main.py:142:handleKline:185271: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime  ...        vol           amt       pct
717  20230408   120000    155959  ...  38189.946  1.072169e+09  0.002424
718  20230408   160000    195959  ...  22421.507  6.284661e+08 -0.002711
719  20230408   200000    235959  ...  23432.442  6.559301e+08  0.000236
720  20230409   000000    035959  ...  29141.062  8.137164e+08 -0.003399
721  20230409   040000    075959  ...  19235.488  5.370948e+08  0.000566

[5 rows x 11 columns]
2023-04-09 08:00:04,140:INFO:s_rsrs:main.py:151:handleKline:185271: df_s.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec  ...  index      beta    zscore  signal
717  20230408   120000    155959  1680940799  ...    717  0.257239  0.065334     NaN
718  20230408   160000    195959  1680955199  ...    718  0.245706 -0.000154     NaN
719  20230408   200000    235959  1680969599  ...    719  0.255298  0.032437     NaN
720  20230409   000000    035959  1680983999  ...    720  0.268087  0.080000     NaN
721  20230409   040000    075959  1680998399  ...    721  0.273751  0.094085     NaN

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '52.088', 'enterprice': '28398.8', 'countrevence': '0', 'unrealprofit': '24622.88109269552', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '27926.08303846', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-9223372036854775808, self.sign=-1


