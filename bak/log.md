# 20230304 08:26:02

## /root/FIL/strategy/amihud/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=993672.4896432, self.flagDict['side']='sell', self.tradeCount=2, self.count=27868127.0.0.1 - - [04/Mar/2023 08:20:01] "POST / HTTP/1.1" 200 -

self.closeSec=1677889199, self.tradeDate='20230304', self.openTime='081500', self.closeTime='081959', self.symbol='BTCUSDT', self.open=22327.8, self.close=22326.5, self.high=22335.9, self.low=22320.5, self.vol=468.092, self.amt=10452611.8302 
2023-03-04 08:20:02,196:INFO:amihud:main.py:172:handleKline:200676: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5855  20230304   075500    075959  ...         0.0        0.0       0
5856  20230304   080000    080459  ...         0.0        0.0       0
5857  20230304   080500    080959  ...         0.0        0.0       0
5858  20230304   081000    081459  ...         0.0        0.0       0
5859  20230304   081500    081959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-03-04 08:20:02,205:INFO:amihud:main.py:175:handleKline:200676: self.closeSec=1677889199, self.tradeDate='20230304', self.openTime='081500', self.closeTime='081959',self.symbol='BTCUSDT',self.open=22327.8, self.close=22326.5, self.high=22335.9, self.low=22320.5, self.vol=468.092, self.amt=10452611.8302, ukdf['pct'].iloc[-1]=-5.8e-05 , ukdf['amount'].iloc[-1]=10452611.8302, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5859, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '60.176', 'enterprice': '16529.3', 'countrevence': '0', 'unrealprofit': '-348911.33332870928', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '22327.48089153', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1
--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=993672.4896432, self.flagDict['side']='sell', self.tradeCount=2, self.count=27869
self.closeSec=1677889499, self.tradeDate='20230304', self.openTime='082000', self.closeTime='082459', self.symbol='BTCUSDT', self.open=22326.5, self.close=22355.0, self.high=22364.2, self.low=22326.5, self.vol=958.64, self.amt=21426436.2181 
127.0.0.1 - - [04/Mar/2023 08:25:01] "POST / HTTP/1.1" 200 -
2023-03-04 08:25:01,589:INFO:amihud:main.py:172:handleKline:200676: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5856  20230304   080000    080459  ...         0.0        0.0       0
5857  20230304   080500    080959  ...         0.0        0.0       0
5858  20230304   081000    081459  ...         0.0        0.0       0
5859  20230304   081500    081959  ...         0.0        0.0       0
5860  20230304   082000    082459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-03-04 08:25:01,589:INFO:amihud:main.py:175:handleKline:200676: self.closeSec=1677889499, self.tradeDate='20230304', self.openTime='082000', self.closeTime='082459',self.symbol='BTCUSDT',self.open=22326.5, self.close=22355.0, self.high=22364.2, self.low=22326.5, self.vol=958.64, self.amt=21426436.2181, ukdf['pct'].iloc[-1]=0.001277 , ukdf['amount'].iloc[-1]=21426436.2181, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5860, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '60.176', 'enterprice': '16529.3', 'countrevence': '0', 'unrealprofit': '-350567.3232', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '22355', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1


## /root/FIL/strategy/factorcheck/log.txt ----- -----

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.6569067793066105, self.count=28434 

self.closeSec=1677889199, self.tradeDate='20230304', self.openTime='081500', self.closeTime='081959', self.symbol='BTCUSDT', self.open=22327.8, self.close=22326.5, self.high=22335.9, self.low=22320.5 
2023-03-04 08:20:01,774:INFO:factorcheck2:main.py:126:handleKline:185239: self.closeSec=1677889199, self.tradeDate='20230304', self.openTime='081500', self.closeTime='081959',self.symbol='BTCUSDT',self.open=22327.8, self.close=22326.5, self.high=22335.9, self.low=22320.5   
2023-03-04 08:20:01,851:INFO:factorcheck2:main.py:127:handleKline:185239: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1535  20230304   075500    075959  1677887999  ...  22323.5  0.000860   1535    5
1536  20230304   080000    080459  1677888299  ...  22322.2 -0.000515   1536    0
1537  20230304   080500    080959  1677888599  ...  22320.9 -0.000434   1537    1
1538  20230304   081000    081459  1677888899  ...  22321.5  0.000278   1538    2
1539  20230304   081500    081959  1677889199  ...  22320.5 -0.000058   1539    3

[5 rows x 11 columns]
2023-03-04 08:20:01,856:INFO:factorcheck2:main.py:128:handleKline:185239: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': False, 'isOpen': True, 'isClose': False, 'isTrig': True}
127.0.0.1 - - [04/Mar/2023 08:25:01] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.6569067793066105, self.count=28435 

self.closeSec=1677889499, self.tradeDate='20230304', self.openTime='082000', self.closeTime='082459', self.symbol='BTCUSDT', self.open=22326.5, self.close=22355.0, self.high=22364.2, self.low=22326.5 
2023-03-04 08:25:01,500:INFO:factorcheck2:main.py:126:handleKline:185239: self.closeSec=1677889499, self.tradeDate='20230304', self.openTime='082000', self.closeTime='082459',self.symbol='BTCUSDT',self.open=22326.5, self.close=22355.0, self.high=22364.2, self.low=22326.5   
2023-03-04 08:25:01,584:INFO:factorcheck2:main.py:127:handleKline:185239: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1536  20230304   080000    080459  1677888299  ...  22322.2 -0.000515   1536    0
1537  20230304   080500    080959  1677888599  ...  22320.9 -0.000434   1537    1
1538  20230304   081000    081459  1677888899  ...  22321.5  0.000278   1538    2
1539  20230304   081500    081959  1677889199  ...  22320.5 -0.000058   1539    3
1540  20230304   082000    082459  1677889499  ...  22326.5  0.001277   1540    4

[5 rows x 11 columns]
2023-03-04 08:25:01,584:INFO:factorcheck2:main.py:128:handleKline:185239: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': False, 'isOpen': True, 'isClose': False, 'isTrig': True}


## /root/FIL/strategy/logic/log.txt ----- -----

2023-03-04 08:00:33,864:DEBUG:logic:main.py:463:getModel:885513: df_s.iloc[-5:,:] :
          date closeTime     open  ...    alpha58   alpha67   alpha72
5770  20230304    052959  22295.0  ...  49.166667  0.371961  0.699496
5771  20230304    055959  22274.1  ...  49.166667  0.364309  0.696511
5772  20230304    062959  22228.6  ...  49.583333  0.371370  0.693123
5773  20230304    065959  22253.0  ...  49.583333  0.387280  0.680026
5774  20230304    072959  22308.9  ...  49.583333  0.397414  0.661333

[5 rows x 33 columns]
0.5471349353049908
acc is : 0.5471349353049908
2023-03-04 08:00:34,053:INFO:logic:main.py:468:getModel:885513: df_pred.iloc[-5:,:] :
     pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
536     0  0.509931  0.490069       0  ...  0.853268   1.0    0.0  0.894889
537     1  0.496320  0.503680       1  ...  0.854205   1.0    0.0  0.895871
538     0  0.510439  0.489561       1  ...  0.856351   1.0    0.0  0.898122
539     0  0.528052  0.471948       1  ...  0.857748   1.0    0.0  0.899587
540     0  0.536374  0.463626       0  ...  0.857652   1.0    0.0  0.899487

[5 rows x 10 columns]
2023-03-04 08:00:34,088:INFO:logic:main.py:478:getModel:885513: df_panel.iloc[-5:,:] :
    pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
45     0  0.509491  0.490509       0  ...  0.853268   1.0    0.0  0.891119
46     1  0.496584  0.503416       1  ...  0.854205   1.0    0.0  0.897588
47     0  0.509834  0.490166       1  ...  0.856351   1.0    0.0  0.896512
48     0  0.528138  0.471862       1  ...  0.857748   1.0    0.0  0.899587
49     0  0.536374  0.463626       0  ...  0.857652   1.0    0.0  0.899487

[5 rows x 10 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '31.837', 'enterprice': '22365.6', 'countrevence': '0', 'unrealprofit': '-1225.7245', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '22327.1', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}


## /root/FIL/strategy/modifiedmom/log.txt ----- -----

623  20230304   075000    075959  1677887999  22338.2  22342.8  0.000210
2023-03-04 08:00:02,055:INFO:modifiedmom:main.py:146:handleKline:185213: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=14216 

self.closeSec=1677888599, self.tradeDate='20230304', self.openTime='080000', self.closeTime='080959', self.symbol='BTCUSDT', self.open='22342.8', self.close='22321.6'
2023-03-04 08:10:01,636:INFO:modifiedmom:main.py:144:handleKline:185213: self.closeSec=1677888599, self.tradeDate='20230304', self.openTime='080000', self.closeTime='080959',self.symbol='BTCUSDT',self.open='22342.8', self.close='22321.6'
127.0.0.1 - - [04/Mar/2023 08:10:01] "POST / HTTP/1.1" 200 -
2023-03-04 08:10:01,667:INFO:modifiedmom:main.py:145:handleKline:185213: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
620  20230304   072000    072959  1677886199  22316.1  22345.3  0.001313
621  20230304   073000    073959  1677886799  22345.2  22343.6 -0.000076
622  20230304   074000    074959  1677887399  22343.6  22338.1 -0.000246
623  20230304   075000    075959  1677887999  22338.2  22342.8  0.000210
624  20230304   080000    080959  1677888599  22342.8  22321.6 -0.000949
2023-03-04 08:10:01,667:INFO:modifiedmom:main.py:146:handleKline:185213: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=14217 

self.closeSec=1677889199, self.tradeDate='20230304', self.openTime='081000', self.closeTime='081959', self.symbol='BTCUSDT', self.open='22321.6', self.close='22326.5'
127.0.0.1 - - [04/Mar/2023 08:20:01] "POST / HTTP/1.1" 200 -
2023-03-04 08:20:02,245:INFO:modifiedmom:main.py:144:handleKline:185213: self.closeSec=1677889199, self.tradeDate='20230304', self.openTime='081000', self.closeTime='081959',self.symbol='BTCUSDT',self.open='22321.6', self.close='22326.5'
2023-03-04 08:20:02,312:INFO:modifiedmom:main.py:145:handleKline:185213: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
621  20230304   073000    073959  1677886799  22345.2  22343.6 -0.000076
622  20230304   074000    074959  1677887399  22343.6  22338.1 -0.000246
623  20230304   075000    075959  1677887999  22338.2  22342.8  0.000210
624  20230304   080000    080959  1677888599  22342.8  22321.6 -0.000949
625  20230304   081000    081959  1677889199  22321.6  22326.5  0.000220
2023-03-04 08:20:02,312:INFO:modifiedmom:main.py:146:handleKline:185213: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False}


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

17471  20230304   075000    075959  1677887999  22338.2  22342.8
2023-03-04 08:00:02,087:INFO:pyemd2:main.py:127:handleKline:185189: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}
127.0.0.1 - - [04/Mar/2023 08:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=14217 

self.closeSec=1677888599, self.tradeDate='20230304', self.openTime='080000', self.closeTime='080959', self.symbol='BTCUSDT', self.open='22342.8', self.close='22321.6'
2023-03-04 08:10:01,599:INFO:pyemd2:main.py:125:handleKline:185189: self.closeSec=1677888599, self.tradeDate='20230304', self.openTime='080000', self.closeTime='080959',self.symbol='BTCUSDT',self.open='22342.8', self.close='22321.6'
2023-03-04 08:10:01,659:INFO:pyemd2:main.py:126:handleKline:185189: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17468  20230304   072000    072959  1677886199  22316.1  22345.3
17469  20230304   073000    073959  1677886799  22345.2  22343.6
17470  20230304   074000    074959  1677887399  22343.6  22338.1
17471  20230304   075000    075959  1677887999  22338.2  22342.8
17472  20230304   080000    080959  1677888599  22342.8  22321.6
2023-03-04 08:10:01,660:INFO:pyemd2:main.py:127:handleKline:185189: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=14218 

self.closeSec=1677889199, self.tradeDate='20230304', self.openTime='081000', self.closeTime='081959', self.symbol='BTCUSDT', self.open='22321.6', self.close='22326.5'
127.0.0.1 - - [04/Mar/2023 08:20:01] "POST / HTTP/1.1" 200 -
2023-03-04 08:20:02,686:INFO:pyemd2:main.py:125:handleKline:185189: self.closeSec=1677889199, self.tradeDate='20230304', self.openTime='081000', self.closeTime='081959',self.symbol='BTCUSDT',self.open='22321.6', self.close='22326.5'
2023-03-04 08:20:02,743:INFO:pyemd2:main.py:126:handleKline:185189: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17469  20230304   073000    073959  1677886799  22345.2  22343.6
17470  20230304   074000    074959  1677887399  22343.6  22338.1
17471  20230304   075000    075959  1677887999  22338.2  22342.8
17472  20230304   080000    080959  1677888599  22342.8  22321.6
17473  20230304   081000    081959  1677889199  22321.6  22326.5
2023-03-04 08:20:02,743:INFO:pyemd2:main.py:127:handleKline:185189: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}


## /root/FIL/strategy/similarity/log.txt ----- -----

12143  20230304   075000    075959  1677887999  22338.2  22342.8
2023-03-04 08:00:02,067:INFO:testStrategy:main.py:103:handleKline:185174: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}
127.0.0.1 - - [04/Mar/2023 08:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=14217 

self.closeSec=1677888599, self.tradeDate='20230304', self.openTime='080000', self.closeTime='080959', self.symbol='BTCUSDT', self.open='22342.8', self.close='22321.6'
2023-03-04 08:10:01,581:INFO:testStrategy:main.py:101:handleKline:185174: self.closeSec=1677888599, self.tradeDate='20230304', self.openTime='080000', self.closeTime='080959',self.symbol='BTCUSDT',self.open='22342.8', self.close='22321.6'
2023-03-04 08:10:01,611:INFO:testStrategy:main.py:102:handleKline:185174: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12140  20230304   072000    072959  1677886199  22316.1  22345.3
12141  20230304   073000    073959  1677886799  22345.2  22343.6
12142  20230304   074000    074959  1677887399  22343.6  22338.1
12143  20230304   075000    075959  1677887999  22338.2  22342.8
12144  20230304   080000    080959  1677888599  22342.8  22321.6
2023-03-04 08:10:01,614:INFO:testStrategy:main.py:103:handleKline:185174: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=14218 

self.closeSec=1677889199, self.tradeDate='20230304', self.openTime='081000', self.closeTime='081959', self.symbol='BTCUSDT', self.open='22321.6', self.close='22326.5'
127.0.0.1 - - [04/Mar/2023 08:20:01] "POST / HTTP/1.1" 200 -
2023-03-04 08:20:02,516:INFO:testStrategy:main.py:101:handleKline:185174: self.closeSec=1677889199, self.tradeDate='20230304', self.openTime='081000', self.closeTime='081959',self.symbol='BTCUSDT',self.open='22321.6', self.close='22326.5'
2023-03-04 08:20:02,634:INFO:testStrategy:main.py:102:handleKline:185174: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12141  20230304   073000    073959  1677886799  22345.2  22343.6
12142  20230304   074000    074959  1677887399  22343.6  22338.1
12143  20230304   075000    075959  1677887999  22338.2  22342.8
12144  20230304   080000    080959  1677888599  22342.8  22321.6
12145  20230304   081000    081959  1677889199  22321.6  22326.5
2023-03-04 08:20:02,634:INFO:testStrategy:main.py:103:handleKline:185174: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}


## /root/FIL/strategy/sr_min/log.txt ----- -----

127.0.0.1 - - [04/Mar/2023 08:20:01] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=0, self.total=1000000.0, self.flagDict['side']='', self.tradeCount=0, self.count=23866
self.closeSec=1677889199, self.tradeDate='20230304', self.openTime='081500', self.closeTime='081959', self.symbol='BTCUSDT', self.open=22327.8, self.close=22326.5, self.high=22335.9, self.low=22320.5, self.vol=468.092, self.amt=10452611.8302 
2023-03-04 08:20:01,626:INFO:sr_min:main.py:172:handleKline:449472: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5855  20230304   075500    075959  ...         0.0        0.0       0
5856  20230304   080000    080459  ...         0.0        0.0       0
5857  20230304   080500    080959  ...         0.0        0.0       0
5858  20230304   081000    081459  ...         0.0        0.0       0
5859  20230304   081500    081959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-03-04 08:20:01,627:INFO:sr_min:main.py:175:handleKline:449472: self.closeSec=1677889199, self.tradeDate='20230304', self.openTime='081500', self.closeTime='081959',self.symbol='BTCUSDT',self.open=22327.8, self.close=22326.5, self.high=22335.9, self.low=22320.5, self.vol=468.092, self.amt=10452611.8302, ukdf['pct'].iloc[-1]=-5.8e-05 , ukdf['amount'].iloc[-1]=10452611.8302, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5859, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': []}
type(curSign)=<class 'int'>, curSign=0, self.sign=0
127.0.0.1 - - [04/Mar/2023 08:25:01] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=0, self.total=1000000.0, self.flagDict['side']='', self.tradeCount=0, self.count=23867
self.closeSec=1677889499, self.tradeDate='20230304', self.openTime='082000', self.closeTime='082459', self.symbol='BTCUSDT', self.open=22326.5, self.close=22355.0, self.high=22364.2, self.low=22326.5, self.vol=958.64, self.amt=21426436.2181 
2023-03-04 08:25:01,613:INFO:sr_min:main.py:172:handleKline:449472: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5856  20230304   080000    080459  ...         0.0        0.0       0
5857  20230304   080500    080959  ...         0.0        0.0       0
5858  20230304   081000    081459  ...         0.0        0.0       0
5859  20230304   081500    081959  ...         0.0        0.0       0
5860  20230304   082000    082459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-03-04 08:25:01,613:INFO:sr_min:main.py:175:handleKline:449472: self.closeSec=1677889499, self.tradeDate='20230304', self.openTime='082000', self.closeTime='082459',self.symbol='BTCUSDT',self.open=22326.5, self.close=22355.0, self.high=22364.2, self.low=22326.5, self.vol=958.64, self.amt=21426436.2181, ukdf['pct'].iloc[-1]=0.001277 , ukdf['amount'].iloc[-1]=21426436.2181, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5860, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': []}
type(curSign)=<class 'int'>, curSign=0, self.sign=0


## /root/FIL/strategy/s_rsrs/log.txt ----- -----

719  20230303   200000    235959  1677859199  ...    719  0.347434 -0.889416    -1.0
720  20230304   000000    035959  1677873599  ...    720  0.415967 -0.666855    -1.0

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '42.135', 'enterprice': '23350.3', 'countrevence': '0', 'unrealprofit': '42059.157', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '22352.1', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-1, self.sign=-1
--handleKline--:  version='2.0.0', self.name='s_rsrs', self.symbol='BTCUSDT', interval='4h', intervalSec=14400, wid=25, thd=0.6, self.sign=-1, self.total=982881.0256095, self.flagDict['side']='sell', self.tradeCount=23, self.count=592
self.closeSec=1677887999, self.tradeDate='20230304', self.openTime='040000', self.closeTime='075959', self.symbol='BTCUSDT', self.open=22348.3, self.close=22342.8, self.high=22366.0, self.low=22126.0, self.vol=59046.812, self.amt=1314849748.8357 
2023-03-04 08:00:01,908:INFO:s_rsrs:main.py:141:handleKline:185271: self.closeSec=1677887999, self.tradeDate='20230304', self.openTime='040000', self.closeTime='075959',self.symbol='BTCUSDT',self.open=22348.3, self.close=22342.8, self.high=22366.0, self.low=22126.0, self.vol=59046.812, self.amt=1314849748.8357 
127.0.0.1 - - [04/Mar/2023 08:00:01] "POST / HTTP/1.1" 200 -
2023-03-04 08:00:02,031:INFO:s_rsrs:main.py:142:handleKline:185271: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime  ...         vol           amt       pct
717  20230303   120000    155959  ...   58370.469  1.304177e+09  0.001856
718  20230303   160000    195959  ...   48913.566  1.094198e+09 -0.000622
719  20230303   200000    235959  ...  111464.429  2.489669e+09 -0.000448
720  20230304   000000    035959  ...   64926.046  1.450555e+09  0.001093
721  20230304   040000    075959  ...   59046.812  1.314850e+09 -0.000246

[5 rows x 11 columns]
2023-03-04 08:00:04,326:INFO:s_rsrs:main.py:151:handleKline:185271: df_s.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec  ...  index      beta    zscore  signal
717  20230303   120000    155959  1677830399  ...    717  0.128108 -1.587200    -1.0
718  20230303   160000    195959  1677844799  ...    718  0.242193 -1.221520    -1.0
719  20230303   200000    235959  1677859199  ...    719  0.347434 -0.889416    -1.0
720  20230304   000000    035959  1677873599  ...    720  0.415967 -0.666855    -1.0
721  20230304   040000    075959  1677887999  ...    721  0.488592 -0.429537     NaN

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '42.135', 'enterprice': '23350.3', 'countrevence': '0', 'unrealprofit': '42446.799', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '22342.9', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-9223372036854775808, self.sign=-1


