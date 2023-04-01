# 20230401 08:26:01

## /root/FIL/strategy/amihud/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=993672.4896432, self.flagDict['side']='sell', self.tradeCount=2, self.count=35932
self.closeSec=1680308399, self.tradeDate='20230401', self.openTime='081500', self.closeTime='081959', self.symbol='BTCUSDT', self.open=28491.0, self.close=28537.4, self.high=28543.3, self.low=28491.0, self.vol=1379.705, self.amt=39351587.9344 
127.0.0.1 - - [01/Apr/2023 08:20:03] "POST / HTTP/1.1" 200 -
2023-04-01 08:20:08,207:INFO:amihud:main.py:172:handleKline:200676: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5855  20230401   075500    075959  ...         0.0        0.0       0
5856  20230401   080000    080459  ...         0.0        0.0       0
5857  20230401   080500    080959  ...         0.0        0.0       0
5858  20230401   081000    081459  ...         0.0        0.0       0
5859  20230401   081500    081959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-04-01 08:20:08,218:INFO:amihud:main.py:175:handleKline:200676: self.closeSec=1680308399, self.tradeDate='20230401', self.openTime='081500', self.closeTime='081959',self.symbol='BTCUSDT',self.open=28491.0, self.close=28537.4, self.high=28543.3, self.low=28491.0, self.vol=1379.705, self.amt=39351587.9344, ukdf['pct'].iloc[-1]=0.001625 , ukdf['amount'].iloc[-1]=39351587.9344, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5859, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '60.176', 'enterprice': '16529.3', 'countrevence': '0', 'unrealprofit': '-722376.7744', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '28533.7', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1
127.0.0.1 - - [01/Apr/2023 08:25:01] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=993672.4896432, self.flagDict['side']='sell', self.tradeCount=2, self.count=35933
self.closeSec=1680308699, self.tradeDate='20230401', self.openTime='082000', self.closeTime='082459', self.symbol='BTCUSDT', self.open=28537.4, self.close=28468.0, self.high=28537.4, self.low=28456.9, self.vol=1424.672, self.amt=40597693.7441 
2023-04-01 08:25:01,605:INFO:amihud:main.py:172:handleKline:200676: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5856  20230401   080000    080459  ...         0.0        0.0       0
5857  20230401   080500    080959  ...         0.0        0.0       0
5858  20230401   081000    081459  ...         0.0        0.0       0
5859  20230401   081500    081959  ...         0.0        0.0       0
5860  20230401   082000    082459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-04-01 08:25:01,605:INFO:amihud:main.py:175:handleKline:200676: self.closeSec=1680308699, self.tradeDate='20230401', self.openTime='082000', self.closeTime='082459',self.symbol='BTCUSDT',self.open=28537.4, self.close=28468.0, self.high=28537.4, self.low=28456.9, self.vol=1424.672, self.amt=40597693.7441, ukdf['pct'].iloc[-1]=-0.002432 , ukdf['amount'].iloc[-1]=40597693.7441, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5860, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '60.176', 'enterprice': '16529.3', 'countrevence': '0', 'unrealprofit': '-718531.4501533176', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '28469.79870635', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1


## /root/FIL/strategy/factorcheck/log.txt ----- -----


self.closeSec=1680308399, self.tradeDate='20230401', self.openTime='081500', self.closeTime='081959', self.symbol='BTCUSDT', self.open=28491.0, self.close=28537.4, self.high=28543.3, self.low=28491.0 
127.0.0.1 - - [01/Apr/2023 08:20:02] "POST / HTTP/1.1" 200 -
2023-04-01 08:20:04,407:INFO:factorcheck2:main.py:126:handleKline:185239: self.closeSec=1680308399, self.tradeDate='20230401', self.openTime='081500', self.closeTime='081959',self.symbol='BTCUSDT',self.open=28491.0, self.close=28537.4, self.high=28543.3, self.low=28491.0   
2023-04-01 08:20:05,708:INFO:factorcheck2:main.py:127:handleKline:185239: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1535  20230401   075500    075959  1680307199  ...  28454.8 -0.000004   1535    5
1536  20230401   080000    080459  1680307499  ...  28438.0 -0.000439   1536    0
1537  20230401   080500    080959  1680307799  ...  28439.6  0.001466   1537    1
1538  20230401   081000    081459  1680308099  ...  28467.1  0.000246   1538    2
1539  20230401   081500    081959  1680308399  ...  28491.0  0.001625   1539    3

[5 rows x 11 columns]
2023-04-01 08:20:05,708:INFO:factorcheck2:main.py:128:handleKline:185239: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': False, 'isOpen': True, 'isClose': False, 'isTrig': True}
127.0.0.1 - - [01/Apr/2023 08:25:01] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=22, self.factor=0.42136125249579925, self.count=36499 

self.closeSec=1680308699, self.tradeDate='20230401', self.openTime='082000', self.closeTime='082459', self.symbol='BTCUSDT', self.open=28537.4, self.close=28468.0, self.high=28537.4, self.low=28456.9 
2023-04-01 08:25:01,538:INFO:factorcheck2:main.py:126:handleKline:185239: self.closeSec=1680308699, self.tradeDate='20230401', self.openTime='082000', self.closeTime='082459',self.symbol='BTCUSDT',self.open=28537.4, self.close=28468.0, self.high=28537.4, self.low=28456.9   
2023-04-01 08:25:01,579:INFO:factorcheck2:main.py:127:handleKline:185239: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1536  20230401   080000    080459  1680307499  ...  28438.0 -0.000439   1536    0
1537  20230401   080500    080959  1680307799  ...  28439.6  0.001466   1537    1
1538  20230401   081000    081459  1680308099  ...  28467.1  0.000246   1538    2
1539  20230401   081500    081959  1680308399  ...  28491.0  0.001625   1539    3
1540  20230401   082000    082459  1680308699  ...  28456.9 -0.002432   1540    4

[5 rows x 11 columns]
2023-04-01 08:25:01,579:INFO:factorcheck2:main.py:128:handleKline:185239: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': False, 'isOpen': True, 'isClose': False, 'isTrig': True}


## /root/FIL/strategy/logic/log.txt ----- -----

2023-04-01 08:00:33,191:DEBUG:logic:main.py:463:getModel:885513: df_s.iloc[-5:,:] :
          date closeTime     open  ...    alpha58   alpha67   alpha72
5770  20230401    052959  28378.6  ...  52.916667  0.538732  0.348417
5771  20230401    055959  28425.9  ...  52.916667  0.544366  0.336931
5772  20230401    062959  28468.4  ...  52.916667  0.555867  0.321213
5773  20230401    065959  28556.1  ...  52.916667  0.556398  0.306311
5774  20230401    072959  28560.5  ...  52.500000  0.553053  0.293553

[5 rows x 33 columns]
0.5231053604436229
acc is : 0.5231053604436229
2023-04-01 08:00:33,351:INFO:logic:main.py:468:getModel:885513: df_pred.iloc[-5:,:] :
     pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
536     0  0.543344  0.456656       1  ...  1.018272   1.0    0.0  1.029379
537     0  0.538133  0.461867       1  ...  1.021423   1.0    0.0  1.032565
538     0  0.547158  0.452842       1  ...  1.021569   1.0    0.0  1.032713
539     0  0.539976  0.460024       0  ...  1.020843   1.0    0.0  1.031979
540     0  0.530156  0.469844       0  ...  1.017792   1.0    0.0  1.028894

[5 rows x 10 columns]
2023-04-01 08:00:33,388:INFO:logic:main.py:478:getModel:885513: df_panel.iloc[-5:,:] :
    pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
45     0  0.542358  0.457642       1  ...  0.961069   1.0    0.0  1.028490
46     0  0.537685  0.462315       1  ...  1.021423   1.0    0.0  1.033499
47     0  0.547628  0.452372       1  ...  1.021569   1.0    0.0  1.037074
48     0  0.539957  0.460043       0  ...  1.020843   1.0    0.0  1.031979
49     0  0.530156  0.469844       0  ...  1.017792   1.0    0.0  1.028894

[5 rows x 10 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': []}


## /root/FIL/strategy/modifiedmom/log.txt ----- -----

623  20230401   075000    075959  1680307199  28494.5  28454.9 -0.001390
2023-04-01 08:00:02,009:INFO:modifiedmom:main.py:146:handleKline:185213: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=18248 

self.closeSec=1680307799, self.tradeDate='20230401', self.openTime='080000', self.closeTime='080959', self.symbol='BTCUSDT', self.open='28454.8', self.close='28484.1'
2023-04-01 08:10:01,631:INFO:modifiedmom:main.py:144:handleKline:185213: self.closeSec=1680307799, self.tradeDate='20230401', self.openTime='080000', self.closeTime='080959',self.symbol='BTCUSDT',self.open='28454.8', self.close='28484.1'
127.0.0.1 - - [01/Apr/2023 08:10:01] "POST / HTTP/1.1" 200 -
2023-04-01 08:10:01,663:INFO:modifiedmom:main.py:145:handleKline:185213: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
620  20230401   072000    072959  1680305399  28508.5  28540.2  0.001119
621  20230401   073000    073959  1680305999  28540.1  28514.9 -0.000886
622  20230401   074000    074959  1680306599  28514.9  28494.5 -0.000715
623  20230401   075000    075959  1680307199  28494.5  28454.9 -0.001390
624  20230401   080000    080959  1680307799  28454.8  28484.1  0.001026
2023-04-01 08:10:01,663:INFO:modifiedmom:main.py:146:handleKline:185213: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=18249 

self.closeSec=1680308399, self.tradeDate='20230401', self.openTime='081000', self.closeTime='081959', self.symbol='BTCUSDT', self.open='28484', self.close='28537.4'
127.0.0.1 - - [01/Apr/2023 08:20:04] "POST / HTTP/1.1" 200 -
2023-04-01 08:20:07,077:INFO:modifiedmom:main.py:144:handleKline:185213: self.closeSec=1680308399, self.tradeDate='20230401', self.openTime='081000', self.closeTime='081959',self.symbol='BTCUSDT',self.open='28484', self.close='28537.4'
2023-04-01 08:20:07,837:INFO:modifiedmom:main.py:145:handleKline:185213: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
621  20230401   073000    073959  1680305999  28540.1  28514.9 -0.000886
622  20230401   074000    074959  1680306599  28514.9  28494.5 -0.000715
623  20230401   075000    075959  1680307199  28494.5  28454.9 -0.001390
624  20230401   080000    080959  1680307799  28454.8  28484.1  0.001026
625  20230401   081000    081959  1680308399    28484  28537.4  0.001871
2023-04-01 08:20:07,837:INFO:modifiedmom:main.py:146:handleKline:185213: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False}


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

17471  20230401   075000    075959  1680307199  28494.5  28454.9
2023-04-01 08:00:01,992:INFO:pyemd2:main.py:127:handleKline:185189: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=18249 

self.closeSec=1680307799, self.tradeDate='20230401', self.openTime='080000', self.closeTime='080959', self.symbol='BTCUSDT', self.open='28454.8', self.close='28484.1'
2023-04-01 08:10:01,658:INFO:pyemd2:main.py:125:handleKline:185189: self.closeSec=1680307799, self.tradeDate='20230401', self.openTime='080000', self.closeTime='080959',self.symbol='BTCUSDT',self.open='28454.8', self.close='28484.1'
127.0.0.1 - - [01/Apr/2023 08:10:01] "POST / HTTP/1.1" 200 -
2023-04-01 08:10:01,730:INFO:pyemd2:main.py:126:handleKline:185189: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17468  20230401   072000    072959  1680305399  28508.5  28540.2
17469  20230401   073000    073959  1680305999  28540.1  28514.9
17470  20230401   074000    074959  1680306599  28514.9  28494.5
17471  20230401   075000    075959  1680307199  28494.5  28454.9
17472  20230401   080000    080959  1680307799  28454.8  28484.1
2023-04-01 08:10:01,730:INFO:pyemd2:main.py:127:handleKline:185189: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=18250 

self.closeSec=1680308399, self.tradeDate='20230401', self.openTime='081000', self.closeTime='081959', self.symbol='BTCUSDT', self.open='28484', self.close='28537.4'
127.0.0.1 - - [01/Apr/2023 08:20:04] "POST / HTTP/1.1" 200 -
2023-04-01 08:20:10,192:INFO:pyemd2:main.py:125:handleKline:185189: self.closeSec=1680308399, self.tradeDate='20230401', self.openTime='081000', self.closeTime='081959',self.symbol='BTCUSDT',self.open='28484', self.close='28537.4'
2023-04-01 08:20:10,345:INFO:pyemd2:main.py:126:handleKline:185189: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17469  20230401   073000    073959  1680305999  28540.1  28514.9
17470  20230401   074000    074959  1680306599  28514.9  28494.5
17471  20230401   075000    075959  1680307199  28494.5  28454.9
17472  20230401   080000    080959  1680307799  28454.8  28484.1
17473  20230401   081000    081959  1680308399    28484  28537.4
2023-04-01 08:20:10,346:INFO:pyemd2:main.py:127:handleKline:185189: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}


## /root/FIL/strategy/similarity/log.txt ----- -----

12143  20230401   075000    075959  1680307199  28494.5  28454.9
2023-04-01 08:00:02,002:INFO:testStrategy:main.py:103:handleKline:185174: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': True, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}
127.0.0.1 - - [01/Apr/2023 08:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=18249 

self.closeSec=1680307799, self.tradeDate='20230401', self.openTime='080000', self.closeTime='080959', self.symbol='BTCUSDT', self.open='28454.8', self.close='28484.1'
2023-04-01 08:10:01,635:INFO:testStrategy:main.py:101:handleKline:185174: self.closeSec=1680307799, self.tradeDate='20230401', self.openTime='080000', self.closeTime='080959',self.symbol='BTCUSDT',self.open='28454.8', self.close='28484.1'
2023-04-01 08:10:01,723:INFO:testStrategy:main.py:102:handleKline:185174: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12140  20230401   072000    072959  1680305399  28508.5  28540.2
12141  20230401   073000    073959  1680305999  28540.1  28514.9
12142  20230401   074000    074959  1680306599  28514.9  28494.5
12143  20230401   075000    075959  1680307199  28494.5  28454.9
12144  20230401   080000    080959  1680307799  28454.8  28484.1
2023-04-01 08:10:01,724:INFO:testStrategy:main.py:103:handleKline:185174: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': True, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=18250 

self.closeSec=1680308399, self.tradeDate='20230401', self.openTime='081000', self.closeTime='081959', self.symbol='BTCUSDT', self.open='28484', self.close='28537.4'
127.0.0.1 - - [01/Apr/2023 08:20:04] "POST / HTTP/1.1" 200 -
2023-04-01 08:20:09,640:INFO:testStrategy:main.py:101:handleKline:185174: self.closeSec=1680308399, self.tradeDate='20230401', self.openTime='081000', self.closeTime='081959',self.symbol='BTCUSDT',self.open='28484', self.close='28537.4'
2023-04-01 08:20:09,963:INFO:testStrategy:main.py:102:handleKline:185174: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12141  20230401   073000    073959  1680305999  28540.1  28514.9
12142  20230401   074000    074959  1680306599  28514.9  28494.5
12143  20230401   075000    075959  1680307199  28494.5  28454.9
12144  20230401   080000    080959  1680307799  28454.8  28484.1
12145  20230401   081000    081959  1680308399    28484  28537.4
2023-04-01 08:20:09,964:INFO:testStrategy:main.py:103:handleKline:185174: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': True, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}


## /root/FIL/strategy/sr_min/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=0, self.total=1000000.0, self.flagDict['side']='', self.tradeCount=0, self.count=31930
self.closeSec=1680308399, self.tradeDate='20230401', self.openTime='081500', self.closeTime='081959', self.symbol='BTCUSDT', self.open=28491.0, self.close=28537.4, self.high=28543.3, self.low=28491.0, self.vol=1379.705, self.amt=39351587.9344 
127.0.0.1 - - [01/Apr/2023 08:20:02] "POST / HTTP/1.1" 200 -
2023-04-01 08:20:06,847:INFO:sr_min:main.py:172:handleKline:449472: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5855  20230401   075500    075959  ...         0.0        0.0       0
5856  20230401   080000    080459  ...         0.0        0.0       0
5857  20230401   080500    080959  ...         0.0        0.0       0
5858  20230401   081000    081459  ...         0.0        0.0       0
5859  20230401   081500    081959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-04-01 08:20:06,878:INFO:sr_min:main.py:175:handleKline:449472: self.closeSec=1680308399, self.tradeDate='20230401', self.openTime='081500', self.closeTime='081959',self.symbol='BTCUSDT',self.open=28491.0, self.close=28537.4, self.high=28543.3, self.low=28491.0, self.vol=1379.705, self.amt=39351587.9344, ukdf['pct'].iloc[-1]=0.001625 , ukdf['amount'].iloc[-1]=39351587.9344, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5859, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': []}
type(curSign)=<class 'int'>, curSign=0, self.sign=0
127.0.0.1 - - [01/Apr/2023 08:25:01] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=0, self.total=1000000.0, self.flagDict['side']='', self.tradeCount=0, self.count=31931
self.closeSec=1680308699, self.tradeDate='20230401', self.openTime='082000', self.closeTime='082459', self.symbol='BTCUSDT', self.open=28537.4, self.close=28468.0, self.high=28537.4, self.low=28456.9, self.vol=1424.672, self.amt=40597693.7441 
2023-04-01 08:25:01,602:INFO:sr_min:main.py:172:handleKline:449472: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5856  20230401   080000    080459  ...         0.0        0.0       0
5857  20230401   080500    080959  ...         0.0        0.0       0
5858  20230401   081000    081459  ...         0.0        0.0       0
5859  20230401   081500    081959  ...         0.0        0.0       0
5860  20230401   082000    082459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-04-01 08:25:01,607:INFO:sr_min:main.py:175:handleKline:449472: self.closeSec=1680308699, self.tradeDate='20230401', self.openTime='082000', self.closeTime='082459',self.symbol='BTCUSDT',self.open=28537.4, self.close=28468.0, self.high=28537.4, self.low=28456.9, self.vol=1424.672, self.amt=40597693.7441, ukdf['pct'].iloc[-1]=-0.002432 , ukdf['amount'].iloc[-1]=40597693.7441, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5860, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': []}
type(curSign)=<class 'int'>, curSign=0, self.sign=0


## /root/FIL/strategy/s_rsrs/log.txt ----- -----

719  20230331   200000    235959  1680278399  ...    719  0.648754  0.667380     1.0
720  20230401   000000    035959  1680292799  ...    720  0.851423  1.243553     1.0

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '52.153', 'enterprice': '28496', 'countrevence': '0', 'unrealprofit': '-2044.75454712719', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '28456.79315577', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=1, self.sign=1
127.0.0.1 - - [01/Apr/2023 08:00:01] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='s_rsrs', self.symbol='BTCUSDT', interval='4h', intervalSec=14400, wid=25, thd=0.6, self.sign=1, self.total=1484665.736112, self.flagDict['side']='buy', self.tradeCount=28, self.count=760
self.closeSec=1680307199, self.tradeDate='20230401', self.openTime='040000', self.closeTime='075959', self.symbol='BTCUSDT', self.open=28458.9, self.close=28454.9, self.high=28632.5, self.low=28322.0, self.vol=51498.288, self.amt=1466608462.60412 
2023-04-01 08:00:01,808:INFO:s_rsrs:main.py:141:handleKline:185271: self.closeSec=1680307199, self.tradeDate='20230401', self.openTime='040000', self.closeTime='075959',self.symbol='BTCUSDT',self.open=28458.9, self.close=28454.9, self.high=28632.5, self.low=28322.0, self.vol=51498.288, self.amt=1466608462.60412 
2023-04-01 08:00:01,953:INFO:s_rsrs:main.py:142:handleKline:185271: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime  ...         vol           amt       pct
717  20230331   120000    155959  ...  101966.835  2.840422e+09 -0.014883
718  20230331   160000    195959  ...   76287.669  2.123632e+09  0.006588
719  20230331   200000    235959  ...  217230.739  6.157321e+09  0.020508
720  20230401   000000    035959  ...   81724.628  2.319688e+09 -0.001408
721  20230401   040000    075959  ...   51498.288  1.466608e+09  0.000228

[5 rows x 11 columns]
2023-04-01 08:00:04,343:INFO:s_rsrs:main.py:151:handleKline:185271: df_s.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec  ...  index      beta    zscore  signal
717  20230331   120000    155959  1680249599  ...    717  0.615690  0.553546     NaN
718  20230331   160000    195959  1680263999  ...    718  0.616793  0.568794     NaN
719  20230331   200000    235959  1680278399  ...    719  0.648754  0.667380     1.0
720  20230401   000000    035959  1680292799  ...    720  0.851423  1.243553     1.0
721  20230401   040000    075959  1680307199  ...    721  0.816670  1.124941     1.0

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '52.153', 'enterprice': '28496', 'countrevence': '0', 'unrealprofit': '-1978.86549311637', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '28458.05653571', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=1, self.sign=1


