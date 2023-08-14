# 20230814 08:26:01

## /root/FIL/strategy/amihud/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=373746.4768026, self.flagDict['side']='sell', self.tradeCount=2, self.count=26464
self.closeSec=1691972399, self.tradeDate='20230814', self.openTime='081500', self.closeTime='081959', self.symbol='BTCUSDT', self.open=29319.2, self.close=29285.6, self.high=29319.2, self.low=29285.5, self.vol=446.524, self.amt=13084629.2336 
127.0.0.1 - - [14/Aug/2023 08:20:01] "POST / HTTP/1.1" 200 -
2023-08-14 08:20:07,476:INFO:amihud:main.py:172:handleKline:2219019: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5855  20230814   075500    075959  ...         0.0        0.0       0
5856  20230814   080000    080459  ...         0.0        0.0       0
5857  20230814   080500    080959  ...         0.0        0.0       0
5858  20230814   081000    081459  ...         0.0        0.0       0
5859  20230814   081500    081959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-08-14 08:20:07,504:INFO:amihud:main.py:175:handleKline:2219019: self.closeSec=1691972399, self.tradeDate='20230814', self.openTime='081500', self.closeTime='081959',self.symbol='BTCUSDT',self.open=29319.2, self.close=29285.6, self.high=29319.2, self.low=29285.5, self.vol=446.524, self.amt=13084629.2336, ukdf['pct'].iloc[-1]=-0.001146 , ukdf['amount'].iloc[-1]=13084629.2336, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5859, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '13.926', 'enterprice': '26864.9', 'countrevence': '0', 'unrealprofit': '-33729.80307017772', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '29286.97403922', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1
--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=373746.4768026, self.flagDict['side']='sell', self.tradeCount=2, self.count=26465
self.closeSec=1691972699, self.tradeDate='20230814', self.openTime='082000', self.closeTime='082459', self.symbol='BTCUSDT', self.open=29285.6, self.close=29280.8, self.high=29287.9, self.low=29272.8, self.vol=545.647, self.amt=15976839.1954 
127.0.0.1 - - [14/Aug/2023 08:25:00] "POST / HTTP/1.1" 200 -
2023-08-14 08:25:00,773:INFO:amihud:main.py:172:handleKline:2219019: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5856  20230814   080000    080459  ...         0.0        0.0       0
5857  20230814   080500    080959  ...         0.0        0.0       0
5858  20230814   081000    081459  ...         0.0        0.0       0
5859  20230814   081500    081959  ...         0.0        0.0       0
5860  20230814   082000    082459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-08-14 08:25:00,774:INFO:amihud:main.py:175:handleKline:2219019: self.closeSec=1691972699, self.tradeDate='20230814', self.openTime='082000', self.closeTime='082459',self.symbol='BTCUSDT',self.open=29285.6, self.close=29280.8, self.high=29287.9, self.low=29272.8, self.vol=545.647, self.amt=15976839.1954, ukdf['pct'].iloc[-1]=-0.000164 , ukdf['amount'].iloc[-1]=15976839.1954, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5860, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '13.926', 'enterprice': '26864.9', 'countrevence': '0', 'unrealprofit': '-33660.6899431374', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '29282.0111549', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1


## /root/FIL/strategy/factorcheck/log.txt ----- -----


self.closeSec=1691972399, self.tradeDate='20230814', self.openTime='081500', self.closeTime='081959', self.symbol='BTCUSDT', self.open=29319.2, self.close=29285.6, self.high=29319.2, self.low=29285.5 
127.0.0.1 - - [14/Aug/2023 08:20:01] "POST / HTTP/1.1" 200 -
2023-08-14 08:20:05,104:INFO:factorcheck2:main.py:126:handleKline:2218005: self.closeSec=1691972399, self.tradeDate='20230814', self.openTime='081500', self.closeTime='081959',self.symbol='BTCUSDT',self.open=29319.2, self.close=29285.6, self.high=29319.2, self.low=29285.5   
2023-08-14 08:20:06,405:INFO:factorcheck2:main.py:127:handleKline:2218005: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1535  20230814   075500    075959  1691971199  ...  29292.6  0.000024   1535    5
1536  20230814   080000    080459  1691971499  ...  29278.0 -0.000143   1536    0
1537  20230814   080500    080959  1691971799  ...  29289.1  0.000597   1537    1
1538  20230814   081000    081459  1691972099  ...  29306.6  0.000430   1538    2
1539  20230814   081500    081959  1691972399  ...  29285.5 -0.001146   1539    3

[5 rows x 11 columns]
2023-08-14 08:20:06,415:INFO:factorcheck2:main.py:128:handleKline:2218005: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': False, 'isOpen': True, 'isClose': False, 'isTrig': True}
127.0.0.1 - - [14/Aug/2023 08:25:00] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.6554809240157707, self.count=26467 

self.closeSec=1691972699, self.tradeDate='20230814', self.openTime='082000', self.closeTime='082459', self.symbol='BTCUSDT', self.open=29285.6, self.close=29280.8, self.high=29287.9, self.low=29272.8 
2023-08-14 08:25:00,742:INFO:factorcheck2:main.py:126:handleKline:2218005: self.closeSec=1691972699, self.tradeDate='20230814', self.openTime='082000', self.closeTime='082459',self.symbol='BTCUSDT',self.open=29285.6, self.close=29280.8, self.high=29287.9, self.low=29272.8   
2023-08-14 08:25:00,754:INFO:factorcheck2:main.py:127:handleKline:2218005: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1536  20230814   080000    080459  1691971499  ...  29278.0 -0.000143   1536    0
1537  20230814   080500    080959  1691971799  ...  29289.1  0.000597   1537    1
1538  20230814   081000    081459  1691972099  ...  29306.6  0.000430   1538    2
1539  20230814   081500    081959  1691972399  ...  29285.5 -0.001146   1539    3
1540  20230814   082000    082459  1691972699  ...  29272.8 -0.000164   1540    4

[5 rows x 11 columns]
2023-08-14 08:25:00,754:INFO:factorcheck2:main.py:128:handleKline:2218005: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': False, 'isOpen': True, 'isClose': False, 'isTrig': True}


## /root/FIL/strategy/logic/log.txt ----- -----

2023-08-14 08:00:17,364:DEBUG:logic:main.py:463:getModel:2218526: df_s.iloc[-5:,:] :
          date closeTime     open  ...    alpha58   alpha67   alpha72
5770  20230814    052959  29411.9  ...  46.666667  0.500046  0.531236
5771  20230814    055959  29406.2  ...  46.666667  0.464170  0.542596
5772  20230814    062959  29360.0  ...  46.666667  0.457571  0.547942
5773  20230814    065959  29350.2  ...  46.666667  0.427646  0.561800
5774  20230814    072959  29307.0  ...  46.666667  0.444288  0.568371

[5 rows x 33 columns]
0.5304990757855823
acc is : 0.5304990757855823
2023-08-14 08:00:17,427:INFO:logic:main.py:468:getModel:2218526: df_pred.iloc[-5:,:] :
     pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
536     0  0.501127  0.498873       0  ...  1.012618  -1.0    0.0  1.006248
537     1  0.487362  0.512638       0  ...  1.012932  -1.0    0.0  1.005936
538     1  0.494172  0.505828       0  ...  1.014447  -1.0    0.0  1.004431
539     1  0.483695  0.516305       1  ...  1.013765  -1.0    0.0  1.005107
540     0  0.500625  0.499375       0  ...  1.014920  -1.0    0.0  1.003962

[5 rows x 10 columns]
2023-08-14 08:00:17,439:INFO:logic:main.py:478:getModel:2218526: df_panel.iloc[-5:,:] :
    pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
45     0  0.501027  0.498973       0  ...  1.005295  -1.0    0.0  1.001620
46     1  0.487426  0.512574       0  ...  1.005607  -1.0    0.0  1.003282
47     1  0.494356  0.505644       0  ...  1.007111  -1.0    0.0  1.010088
48     1  0.483695  0.516305       1  ...  1.013765  -1.0    0.0  1.005107
49     0  0.500625  0.499375       0  ...  1.014920  -1.0    0.0  1.003962

[5 rows x 10 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '24.049', 'enterprice': '29479.7', 'countrevence': '0', 'unrealprofit': '4499.5679', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '29292.6', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}


## /root/FIL/strategy/modifiedmom/log.txt ----- -----

623  20230814   075000    075959  1691971199  29297.8  29293.3 -0.000154
2023-08-14 08:00:02,108:INFO:modifiedmom:main.py:146:handleKline:2218259: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=13232 

self.closeSec=1691971799, self.tradeDate='20230814', self.openTime='080000', self.closeTime='080959', self.symbol='BTCUSDT', self.open='29293.3', self.close='29306.6'
2023-08-14 08:10:01,167:INFO:modifiedmom:main.py:144:handleKline:2218259: self.closeSec=1691971799, self.tradeDate='20230814', self.openTime='080000', self.closeTime='080959',self.symbol='BTCUSDT',self.open='29293.3', self.close='29306.6'
127.0.0.1 - - [14/Aug/2023 08:10:01] "POST / HTTP/1.1" 200 -
2023-08-14 08:10:01,174:INFO:modifiedmom:main.py:145:handleKline:2218259: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
620  20230814   072000    072959  1691969399  29294.6  29326.8  0.001099
621  20230814   073000    073959  1691969999  29326.8  29307.7 -0.000651
622  20230814   074000    074959  1691970599  29307.7  29297.8 -0.000338
623  20230814   075000    075959  1691971199  29297.8  29293.3 -0.000154
624  20230814   080000    080959  1691971799  29293.3  29306.6  0.000454
2023-08-14 08:10:01,175:INFO:modifiedmom:main.py:146:handleKline:2218259: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=13233 

self.closeSec=1691972399, self.tradeDate='20230814', self.openTime='081000', self.closeTime='081959', self.symbol='BTCUSDT', self.open='29306.7', self.close='29285.6'
127.0.0.1 - - [14/Aug/2023 08:20:05] "POST / HTTP/1.1" 200 -
2023-08-14 08:20:07,554:INFO:modifiedmom:main.py:144:handleKline:2218259: self.closeSec=1691972399, self.tradeDate='20230814', self.openTime='081000', self.closeTime='081959',self.symbol='BTCUSDT',self.open='29306.7', self.close='29285.6'
2023-08-14 08:20:08,295:INFO:modifiedmom:main.py:145:handleKline:2218259: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
621  20230814   073000    073959  1691969999  29326.8  29307.7 -0.000651
622  20230814   074000    074959  1691970599  29307.7  29297.8 -0.000338
623  20230814   075000    075959  1691971199  29297.8  29293.3 -0.000154
624  20230814   080000    080959  1691971799  29293.3  29306.6  0.000454
625  20230814   081000    081959  1691972399  29306.7  29285.6 -0.000717
2023-08-14 08:20:08,304:INFO:modifiedmom:main.py:146:handleKline:2218259: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False}


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

17471  20230814   075000    075959  1691971199  29297.8  29293.3
2023-08-14 08:00:02,128:INFO:pyemd2:main.py:127:handleKline:2217508: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=13235 

self.closeSec=1691971799, self.tradeDate='20230814', self.openTime='080000', self.closeTime='080959', self.symbol='BTCUSDT', self.open='29293.3', self.close='29306.6'
2023-08-14 08:10:01,172:INFO:pyemd2:main.py:125:handleKline:2217508: self.closeSec=1691971799, self.tradeDate='20230814', self.openTime='080000', self.closeTime='080959',self.symbol='BTCUSDT',self.open='29293.3', self.close='29306.6'
127.0.0.1 - - [14/Aug/2023 08:10:01] "POST / HTTP/1.1" 200 -
2023-08-14 08:10:01,181:INFO:pyemd2:main.py:126:handleKline:2217508: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17468  20230814   072000    072959  1691969399  29294.6  29326.8
17469  20230814   073000    073959  1691969999  29326.8  29307.7
17470  20230814   074000    074959  1691970599  29307.7  29297.8
17471  20230814   075000    075959  1691971199  29297.8  29293.3
17472  20230814   080000    080959  1691971799  29293.3  29306.6
2023-08-14 08:10:01,181:INFO:pyemd2:main.py:127:handleKline:2217508: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=13236 

self.closeSec=1691972399, self.tradeDate='20230814', self.openTime='081000', self.closeTime='081959', self.symbol='BTCUSDT', self.open='29306.7', self.close='29285.6'
127.0.0.1 - - [14/Aug/2023 08:20:05] "POST / HTTP/1.1" 200 -
2023-08-14 08:20:09,869:INFO:pyemd2:main.py:125:handleKline:2217508: self.closeSec=1691972399, self.tradeDate='20230814', self.openTime='081000', self.closeTime='081959',self.symbol='BTCUSDT',self.open='29306.7', self.close='29285.6'
2023-08-14 08:20:09,972:INFO:pyemd2:main.py:126:handleKline:2217508: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17469  20230814   073000    073959  1691969999  29326.8  29307.7
17470  20230814   074000    074959  1691970599  29307.7  29297.8
17471  20230814   075000    075959  1691971199  29297.8  29293.3
17472  20230814   080000    080959  1691971799  29293.3  29306.6
17473  20230814   081000    081959  1691972399  29306.7  29285.6
2023-08-14 08:20:09,973:INFO:pyemd2:main.py:127:handleKline:2217508: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}


## /root/FIL/strategy/similarity/log.txt ----- -----

12143  20230814   075000    075959  1691971199  29297.8  29293.3
2023-08-14 08:00:02,124:INFO:testStrategy:main.py:103:handleKline:2217133: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': True, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}
127.0.0.1 - - [14/Aug/2023 08:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=13235 

self.closeSec=1691971799, self.tradeDate='20230814', self.openTime='080000', self.closeTime='080959', self.symbol='BTCUSDT', self.open='29293.3', self.close='29306.6'
2023-08-14 08:10:01,181:INFO:testStrategy:main.py:101:handleKline:2217133: self.closeSec=1691971799, self.tradeDate='20230814', self.openTime='080000', self.closeTime='080959',self.symbol='BTCUSDT',self.open='29293.3', self.close='29306.6'
2023-08-14 08:10:01,188:INFO:testStrategy:main.py:102:handleKline:2217133: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12140  20230814   072000    072959  1691969399  29294.6  29326.8
12141  20230814   073000    073959  1691969999  29326.8  29307.7
12142  20230814   074000    074959  1691970599  29307.7  29297.8
12143  20230814   075000    075959  1691971199  29297.8  29293.3
12144  20230814   080000    080959  1691971799  29293.3  29306.6
2023-08-14 08:10:01,189:INFO:testStrategy:main.py:103:handleKline:2217133: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': True, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=13236 

self.closeSec=1691972399, self.tradeDate='20230814', self.openTime='081000', self.closeTime='081959', self.symbol='BTCUSDT', self.open='29306.7', self.close='29285.6'
127.0.0.1 - - [14/Aug/2023 08:20:04] "POST / HTTP/1.1" 200 -
2023-08-14 08:20:09,618:INFO:testStrategy:main.py:101:handleKline:2217133: self.closeSec=1691972399, self.tradeDate='20230814', self.openTime='081000', self.closeTime='081959',self.symbol='BTCUSDT',self.open='29306.7', self.close='29285.6'
2023-08-14 08:20:09,839:INFO:testStrategy:main.py:102:handleKline:2217133: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12141  20230814   073000    073959  1691969999  29326.8  29307.7
12142  20230814   074000    074959  1691970599  29307.7  29297.8
12143  20230814   075000    075959  1691971199  29297.8  29293.3
12144  20230814   080000    080959  1691971799  29293.3  29306.6
12145  20230814   081000    081959  1691972399  29306.7  29285.6
2023-08-14 08:20:09,846:INFO:testStrategy:main.py:103:handleKline:2217133: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': True, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}


## /root/FIL/strategy/sr_min/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=1, self.total=996015.990996, self.flagDict['side']='buy', self.tradeCount=1, self.count=26464
self.closeSec=1691972399, self.tradeDate='20230814', self.openTime='081500', self.closeTime='081959', self.symbol='BTCUSDT', self.open=29319.2, self.close=29285.6, self.high=29319.2, self.low=29285.5, self.vol=446.524, self.amt=13084629.2336 
127.0.0.1 - - [14/Aug/2023 08:20:01] "POST / HTTP/1.1" 200 -
2023-08-14 08:20:07,416:INFO:sr_min:main.py:172:handleKline:2219263: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5855  20230814   075500    075959  ...         0.0        0.0       0
5856  20230814   080000    080459  ...         0.0        0.0       0
5857  20230814   080500    080959  ...         0.0        0.0       0
5858  20230814   081000    081459  ...         0.0        0.0       0
5859  20230814   081500    081959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-08-14 08:20:07,455:INFO:sr_min:main.py:175:handleKline:2219263: self.closeSec=1691972399, self.tradeDate='20230814', self.openTime='081500', self.closeTime='081959',self.symbol='BTCUSDT',self.open=29319.2, self.close=29285.6, self.high=29319.2, self.low=29285.5, self.vol=446.524, self.amt=13084629.2336, ukdf['pct'].iloc[-1]=-0.001146 , ukdf['amount'].iloc[-1]=13084629.2336, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5859, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '37.141', 'enterprice': '26844', 'countrevence': '0', 'unrealprofit': '90734.49879067002', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '29286.97403922', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=1
127.0.0.1 - - [14/Aug/2023 08:25:00] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=1, self.total=996015.990996, self.flagDict['side']='buy', self.tradeCount=1, self.count=26465
self.closeSec=1691972699, self.tradeDate='20230814', self.openTime='082000', self.closeTime='082459', self.symbol='BTCUSDT', self.open=29285.6, self.close=29280.8, self.high=29287.9, self.low=29272.8, self.vol=545.647, self.amt=15976839.1954 
2023-08-14 08:25:00,777:INFO:sr_min:main.py:172:handleKline:2219263: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5856  20230814   080000    080459  ...         0.0        0.0       0
5857  20230814   080500    080959  ...         0.0        0.0       0
5858  20230814   081000    081459  ...         0.0        0.0       0
5859  20230814   081500    081959  ...         0.0        0.0       0
5860  20230814   082000    082459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-08-14 08:25:00,777:INFO:sr_min:main.py:175:handleKline:2219263: self.closeSec=1691972699, self.tradeDate='20230814', self.openTime='082000', self.closeTime='082459',self.symbol='BTCUSDT',self.open=29285.6, self.close=29280.8, self.high=29287.9, self.low=29272.8, self.vol=545.647, self.amt=15976839.1954, ukdf['pct'].iloc[-1]=-0.000164 , ukdf['amount'].iloc[-1]=15976839.1954, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5860, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '37.141', 'enterprice': '26844', 'countrevence': '0', 'unrealprofit': '90550.1723041409', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '29282.0111549', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=1


## /root/FIL/strategy/s_rsrs/log.txt ----- -----

2023-08-14 04:00:10,920:INFO:s_rsrs:main.py:343:handleOrderNew:2218689: handleOrderNew: data=OrderType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'clientorderid': '42855F1691956805356I0L65', 'symbol': 'BTCUSDT', 'gatewayorderid': 1691956805772213, 'quantity': '51.457', 'price': '29432.1', 'stopprice': '0', 'ordertype': '', 'side': 'SELL', 'status': 'FILLED', 'positionside': 'SHORT', 'createtime': 1691956804446, 'updatetime': 1691956805772, 'tradetype': 'usdt', 'selfid': 42855, 'filltrades': [TradeType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'tradeid': 1691956805772, 'clientorderid': '42855F1691956805356I0L65', 'price': '29432.1', 'quantity': '51.457', 'commission': '1514.4875697', 'commissionasset': 'USDT', 'tradetime': 1691956805772, 'tradetype': 'usdt', 'gatetype': 'simulator', 'handletime': 1691956805772}], 'gatetype': 'simulator', 'handletime': 0}
2023-08-14 04:00:10,921:INFO:s_rsrs:main.py:346:handleOrderFilled:2218689: handleOrderFilled: data=OrderType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'clientorderid': '42855F1691956805356I0L65', 'symbol': 'BTCUSDT', 'gatewayorderid': 1691956805772213, 'quantity': '51.457', 'price': '29432.1', 'stopprice': '0', 'ordertype': '', 'side': 'SELL', 'status': 'FILLED', 'positionside': 'SHORT', 'createtime': 1691956804446, 'updatetime': 1691956805772, 'tradetype': 'usdt', 'selfid': 42855, 'filltrades': [TradeType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'tradeid': 1691956805772, 'clientorderid': '42855F1691956805356I0L65', 'price': '29432.1', 'quantity': '51.457', 'commission': '1514.4875697', 'commissionasset': 'USDT', 'tradetime': 1691956805772, 'tradetype': 'usdt', 'gatetype': 'simulator', 'handletime': 1691956805772}], 'gatetype': 'simulator', 'handletime': 0}
2023-08-14 04:00:11,379:INFO:s_rsrs:main.py:343:handleOrderNew:2218689: handleOrderNew: data=OrderType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'clientorderid': '42856F1691956810899I0L65', 'symbol': 'BTCUSDT', 'gatewayorderid': 1691956811333236, 'quantity': '51.388', 'price': '29432.6', 'stopprice': '0', 'ordertype': '', 'side': 'SELL', 'status': 'FILLED', 'positionside': 'SHORT', 'createtime': 1691956810435, 'updatetime': 1691956811333, 'tradetype': 'usdt', 'selfid': 42856, 'filltrades': [TradeType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'tradeid': 1691956811333, 'clientorderid': '42856F1691956810899I0L65', 'price': '29432.6', 'quantity': '51.388', 'commission': '1512.4824488', 'commissionasset': 'USDT', 'tradetime': 1691956811333, 'tradetype': 'usdt', 'gatetype': 'simulator', 'handletime': 1691956811333}], 'gatetype': 'simulator', 'handletime': 0}
127.0.0.1 - - [14/Aug/2023 04:00:11] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [14/Aug/2023 04:00:11] "POST / HTTP/1.1" 200 -
2023-08-14 04:00:11,622:INFO:s_rsrs:main.py:346:handleOrderFilled:2218689: handleOrderFilled: data=OrderType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'clientorderid': '42856F1691956810899I0L65', 'symbol': 'BTCUSDT', 'gatewayorderid': 1691956811333236, 'quantity': '51.388', 'price': '29432.6', 'stopprice': '0', 'ordertype': '', 'side': 'SELL', 'status': 'FILLED', 'positionside': 'SHORT', 'createtime': 1691956810435, 'updatetime': 1691956811333, 'tradetype': 'usdt', 'selfid': 42856, 'filltrades': [TradeType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'tradeid': 1691956811333, 'clientorderid': '42856F1691956810899I0L65', 'price': '29432.6', 'quantity': '51.388', 'commission': '1512.4824488', 'commissionasset': 'USDT', 'tradetime': 1691956811333, 'tradetype': 'usdt', 'gatetype': 'simulator', 'handletime': 1691956811333}], 'gatetype': 'simulator', 'handletime': 0}
127.0.0.1 - - [14/Aug/2023 08:00:01] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='s_rsrs', self.symbol='BTCUSDT', interval='4h', intervalSec=14400, wid=25, thd=0.6, self.sign=-1, self.total=1510969.9663512, self.flagDict['side']='sell', self.tradeCount=20, self.count=551
self.closeSec=1691971199, self.tradeDate='20230814', self.openTime='040000', self.closeTime='075959', self.symbol='BTCUSDT', self.open=29426.0, self.close=29293.3, self.high=29434.9, self.low=29256.6, self.vol=24677.795, self.amt=723965419.7821 
2023-08-14 08:00:01,698:INFO:s_rsrs:main.py:141:handleKline:2218689: self.closeSec=1691971199, self.tradeDate='20230814', self.openTime='040000', self.closeTime='075959',self.symbol='BTCUSDT',self.open=29426.0, self.close=29293.3, self.high=29434.9, self.low=29256.6, self.vol=24677.795, self.amt=723965419.7821 
2023-08-14 08:00:01,717:INFO:s_rsrs:main.py:142:handleKline:2218689: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime  ...        vol           amt       pct
717  20230813   120000    155959  ...  11731.661  3.446410e+08 -0.000554
718  20230813   160000    195959  ...   7336.398  2.156099e+08 -0.000391
719  20230813   200000    235959  ...   9903.451  2.908476e+08 -0.000378
720  20230814   000000    035959  ...  20860.595  6.130015e+08  0.002152
721  20230814   040000    075959  ...  24677.795  7.239654e+08 -0.004513

[5 rows x 11 columns]
2023-08-14 08:00:02,463:INFO:s_rsrs:main.py:151:handleKline:2218689: df_s.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec  ...  index      beta    zscore  signal
717  20230813   120000    155959  1691913599  ...    717  0.960580  1.105825     1.0
718  20230813   160000    195959  1691927999  ...    718  1.004451  1.181638     1.0
719  20230813   200000    235959  1691942399  ...    719  1.041921  1.239832     1.0
720  20230814   000000    035959  1691956799  ...    720  0.068942 -1.018602    -1.0
721  20230814   040000    075959  1691971199  ...    721  0.104590 -0.935304    -1.0

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '51.388', 'enterprice': '29432.6', 'countrevence': '0', 'unrealprofit': '7140.29689376156', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '29293.65127863', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-1, self.sign=-1


