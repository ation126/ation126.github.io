# 20230218 08:26:02

## /root/FIL/strategy/amihud/log.txt ----- -----

127.0.0.1 - - [18/Feb/2023 08:20:01] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=993672.4896432, self.flagDict['side']='sell', self.tradeCount=2, self.count=23836
self.closeSec=1676679599, self.tradeDate='20230218', self.openTime='081500', self.closeTime='081959', self.symbol='BTCUSDT', self.open=24635.0, self.close=24700.0, self.high=24738.2, self.low=24627.2, self.vol=2881.934, self.amt=71167748.8518 
2023-02-18 08:20:01,564:INFO:amihud:main.py:172:handleKline:200676: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5855  20230218   075500    075959  ...         0.0        0.0       0
5856  20230218   080000    080459  ...         0.0        0.0       0
5857  20230218   080500    080959  ...         0.0        0.0       0
5858  20230218   081000    081459  ...         0.0        0.0       0
5859  20230218   081500    081959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-02-18 08:20:01,567:INFO:amihud:main.py:175:handleKline:200676: self.closeSec=1676679599, self.tradeDate='20230218', self.openTime='081500', self.closeTime='081959',self.symbol='BTCUSDT',self.open=24635.0, self.close=24700.0, self.high=24738.2, self.low=24627.2, self.vol=2881.934, self.amt=71167748.8518, ukdf['pct'].iloc[-1]=0.002643 , ukdf['amount'].iloc[-1]=71167748.8518, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5859, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '60.176', 'enterprice': '16529.3', 'countrevence': '0', 'unrealprofit': '-491686.0608', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '24700.1', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1
127.0.0.1 - - [18/Feb/2023 08:25:01] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=993672.4896432, self.flagDict['side']='sell', self.tradeCount=2, self.count=23837
self.closeSec=1676679899, self.tradeDate='20230218', self.openTime='082000', self.closeTime='082459', self.symbol='BTCUSDT', self.open=24700.0, self.close=24724.6, self.high=24743.0, self.low=24682.0, self.vol=1851.879, self.amt=45763982.3408 
2023-02-18 08:25:01,747:INFO:amihud:main.py:172:handleKline:200676: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5856  20230218   080000    080459  ...         0.0        0.0       0
5857  20230218   080500    080959  ...         0.0        0.0       0
5858  20230218   081000    081459  ...         0.0        0.0       0
5859  20230218   081500    081959  ...         0.0        0.0       0
5860  20230218   082000    082459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-02-18 08:25:01,747:INFO:amihud:main.py:175:handleKline:200676: self.closeSec=1676679899, self.tradeDate='20230218', self.openTime='082000', self.closeTime='082459',self.symbol='BTCUSDT',self.open=24700.0, self.close=24724.6, self.high=24743.0, self.low=24682.0, self.vol=1851.879, self.amt=45763982.3408, ukdf['pct'].iloc[-1]=0.000996 , ukdf['amount'].iloc[-1]=45763982.3408, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5860, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '60.176', 'enterprice': '16529.3', 'countrevence': '0', 'unrealprofit': '-493160.3728', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '24724.6', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1


## /root/FIL/strategy/factorcheck/log.txt ----- -----


self.closeSec=1676679599, self.tradeDate='20230218', self.openTime='081500', self.closeTime='081959', self.symbol='BTCUSDT', self.open=24635.0, self.close=24700.0, self.high=24738.2, self.low=24627.2 
127.0.0.1 - - [18/Feb/2023 08:20:01] "POST / HTTP/1.1" 200 -
2023-02-18 08:20:01,501:INFO:factorcheck2:main.py:126:handleKline:185239: self.closeSec=1676679599, self.tradeDate='20230218', self.openTime='081500', self.closeTime='081959',self.symbol='BTCUSDT',self.open=24635.0, self.close=24700.0, self.high=24738.2, self.low=24627.2   
2023-02-18 08:20:01,524:INFO:factorcheck2:main.py:127:handleKline:185239: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1535  20230218   075500    075959  1676678399  ...  24551.2  0.000753   1535    5
1536  20230218   080000    080459  1676678699  ...  24546.7  0.000260   1536    0
1537  20230218   080500    080959  1676678999  ...  24580.0 -0.000321   1537    1
1538  20230218   081000    081459  1676679299  ...  24575.0  0.002234   1538    2
1539  20230218   081500    081959  1676679599  ...  24627.2  0.002643   1539    3

[5 rows x 11 columns]
2023-02-18 08:20:01,524:INFO:factorcheck2:main.py:128:handleKline:185239: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}
127.0.0.1 - - [18/Feb/2023 08:25:01] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=151, self.factor=0.46280697500769935, self.count=24403 

self.closeSec=1676679899, self.tradeDate='20230218', self.openTime='082000', self.closeTime='082459', self.symbol='BTCUSDT', self.open=24700.0, self.close=24724.6, self.high=24743.0, self.low=24682.0 
2023-02-18 08:25:01,626:INFO:factorcheck2:main.py:126:handleKline:185239: self.closeSec=1676679899, self.tradeDate='20230218', self.openTime='082000', self.closeTime='082459',self.symbol='BTCUSDT',self.open=24700.0, self.close=24724.6, self.high=24743.0, self.low=24682.0   
2023-02-18 08:25:01,709:INFO:factorcheck2:main.py:127:handleKline:185239: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1536  20230218   080000    080459  1676678699  ...  24546.7  0.000260   1536    0
1537  20230218   080500    080959  1676678999  ...  24580.0 -0.000321   1537    1
1538  20230218   081000    081459  1676679299  ...  24575.0  0.002234   1538    2
1539  20230218   081500    081959  1676679599  ...  24627.2  0.002643   1539    3
1540  20230218   082000    082459  1676679899  ...  24682.0  0.000996   1540    4

[5 rows x 11 columns]
2023-02-18 08:25:01,709:INFO:factorcheck2:main.py:128:handleKline:185239: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}


## /root/FIL/strategy/logic/log.txt ----- -----

2023-02-18 08:00:36,741:DEBUG:logic:main.py:463:getModel:885513: df_s.iloc[-5:,:] :
          date closeTime     open  ...    alpha58   alpha67   alpha72
5770  20230218    052959  24835.2  ...  52.083333  0.591412  0.423956
5771  20230218    055959  24708.9  ...  52.083333  0.563336  0.419598
5772  20230218    062959  24483.7  ...  51.666667  0.548393  0.420748
5773  20230218    065959  24377.7  ...  52.083333  0.577690  0.408450
5774  20230218    072959  24683.3  ...  52.083333  0.567653  0.400543

[5 rows x 33 columns]
0.5175600739371534
acc is : 0.5175600739371534
2023-02-18 08:00:36,922:INFO:logic:main.py:468:getModel:885513: df_pred.iloc[-5:,:] :
     pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
536     0  0.539333  0.460667       0  ...  1.042197   1.0    0.0  1.065152
537     0  0.509966  0.490034       0  ...  1.037126   1.0    0.0  1.059969
538     1  0.496124  0.503876       1  ...  1.050123   1.0    0.0  1.073252
539     0  0.567139  0.432861       0  ...  1.046651   1.0    0.0  1.069704
540     0  0.501284  0.498716       0  ...  1.045792   1.0    0.0  1.068826

[5 rows x 10 columns]
2023-02-18 08:00:36,957:INFO:logic:main.py:478:getModel:885513: df_panel.iloc[-5:,:] :
    pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
45     0  0.539911  0.460089       0  ...  1.052678   1.0    0.0  1.063049
46     0  0.510261  0.489739       0  ...  1.037126   1.0    0.0  1.056432
47     1  0.496785  0.503215       1  ...  1.050123   1.0    0.0  1.073327
48     0  0.567139  0.432861       0  ...  1.046651   1.0    0.0  1.069704
49     0  0.501284  0.498716       0  ...  1.045792   1.0    0.0  1.068826

[5 rows x 10 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '35.459', 'enterprice': '24163.6', 'countrevence': '0', 'unrealprofit': '14502.731', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '24572.6', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}


## /root/FIL/strategy/modifiedmom/log.txt ----- -----

623  20230218   075000    075959  1676678399  24590.2  24581.5 -0.000354
2023-02-18 08:00:02,184:INFO:modifiedmom:main.py:146:handleKline:185213: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=12200 

self.closeSec=1676678999, self.tradeDate='20230218', self.openTime='080000', self.closeTime='080959', self.symbol='BTCUSDT', self.open='24581.3', self.close='24580'
2023-02-18 08:10:01,631:INFO:modifiedmom:main.py:144:handleKline:185213: self.closeSec=1676678999, self.tradeDate='20230218', self.openTime='080000', self.closeTime='080959',self.symbol='BTCUSDT',self.open='24581.3', self.close='24580'
127.0.0.1 - - [18/Feb/2023 08:10:01] "POST / HTTP/1.1" 200 -
2023-02-18 08:10:01,650:INFO:modifiedmom:main.py:145:handleKline:185213: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
620  20230218   072000    072959  1676676599  24599.5  24601.7  0.000089
621  20230218   073000    073959  1676677199  24601.7  24632.7  0.001260
622  20230218   074000    074959  1676677799  24632.7  24590.2 -0.001725
623  20230218   075000    075959  1676678399  24590.2  24581.5 -0.000354
624  20230218   080000    080959  1676678999  24581.3    24580 -0.000061
2023-02-18 08:10:01,650:INFO:modifiedmom:main.py:146:handleKline:185213: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=12201 

self.closeSec=1676679599, self.tradeDate='20230218', self.openTime='081000', self.closeTime='081959', self.symbol='BTCUSDT', self.open='24580', self.close='24700'
127.0.0.1 - - [18/Feb/2023 08:20:01] "POST / HTTP/1.1" 200 -
2023-02-18 08:20:01,613:INFO:modifiedmom:main.py:144:handleKline:185213: self.closeSec=1676679599, self.tradeDate='20230218', self.openTime='081000', self.closeTime='081959',self.symbol='BTCUSDT',self.open='24580', self.close='24700'
2023-02-18 08:20:01,653:INFO:modifiedmom:main.py:145:handleKline:185213: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
621  20230218   073000    073959  1676677199  24601.7  24632.7  0.001260
622  20230218   074000    074959  1676677799  24632.7  24590.2 -0.001725
623  20230218   075000    075959  1676678399  24590.2  24581.5 -0.000354
624  20230218   080000    080959  1676678999  24581.3    24580 -0.000061
625  20230218   081000    081959  1676679599    24580    24700  0.004882
2023-02-18 08:20:01,653:INFO:modifiedmom:main.py:146:handleKline:185213: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False}


## /root/FIL/strategy/percentile_regression_step2/log.txt ----- -----

127.0.0.1 - - [18/Feb/2023 07:00:02] "POST / HTTP/1.1" 200 -
2023-02-18 07:00:02,914:DEBUG:percentile_regression_step2:main.py:154:get_signal:1265985: df_id.iloc[-5:,:] :
                 daytime     hms    close  ...  pct_10  pct_20  factor
144  2023/02/18 04:30:00  043000  24835.2  ...     NaN     NaN       0
145  2023/02/18 05:00:00  050000  24708.9  ...     NaN     NaN       0
146  2023/02/18 05:30:00  053000  24497.0  ...     NaN     NaN       0
147  2023/02/18 06:00:00  060000  24377.8  ...     NaN     NaN       0
148  2023/02/18 06:30:00  063000  24683.3  ...     NaN     NaN       0

[5 rows x 10 columns]
127.0.0.1 - - [18/Feb/2023 07:30:01] "POST / HTTP/1.1" 200 -
2023-02-18 07:30:02,738:DEBUG:percentile_regression_step2:main.py:154:get_signal:1265985: df_id.iloc[-5:,:] :
                 daytime     hms    close  ...  pct_10  pct_20  factor
144  2023/02/18 05:00:00  050000  24708.9  ...     NaN     NaN       0
145  2023/02/18 05:30:00  053000  24497.0  ...     NaN     NaN       0
146  2023/02/18 06:00:00  060000  24377.8  ...     NaN     NaN       0
147  2023/02/18 06:30:00  063000  24683.3  ...     NaN     NaN       0
148  2023/02/18 07:00:00  070000  24601.7  ...     NaN     NaN       0

[5 rows x 10 columns]
127.0.0.1 - - [18/Feb/2023 08:00:01] "POST / HTTP/1.1" 200 -
2023-02-18 08:00:03,085:DEBUG:percentile_regression_step2:main.py:154:get_signal:1265985: df_id.iloc[-5:,:] :
                 daytime     hms    close  ...  pct_10  pct_20  factor
144  2023/02/18 05:30:00  053000  24497.0  ...     NaN     NaN       0
145  2023/02/18 06:00:00  060000  24377.8  ...     NaN     NaN       0
146  2023/02/18 06:30:00  063000  24683.3  ...     NaN     NaN       0
147  2023/02/18 07:00:00  070000  24601.7  ...     NaN     NaN       0
148  2023/02/18 07:30:00  073000  24581.5  ...     NaN     NaN       0

[5 rows x 10 columns]


## /root/FIL/strategy/pyemd/log.txt ----- -----

17471  20230218   075000    075959  1676678399  24590.2  24581.5
2023-02-18 08:00:02,265:INFO:pyemd2:main.py:127:handleKline:185189: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=12201 

self.closeSec=1676678999, self.tradeDate='20230218', self.openTime='080000', self.closeTime='080959', self.symbol='BTCUSDT', self.open='24581.3', self.close='24580'
2023-02-18 08:10:01,622:INFO:pyemd2:main.py:125:handleKline:185189: self.closeSec=1676678999, self.tradeDate='20230218', self.openTime='080000', self.closeTime='080959',self.symbol='BTCUSDT',self.open='24581.3', self.close='24580'
127.0.0.1 - - [18/Feb/2023 08:10:01] "POST / HTTP/1.1" 200 -
2023-02-18 08:10:01,659:INFO:pyemd2:main.py:126:handleKline:185189: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17468  20230218   072000    072959  1676676599  24599.5  24601.7
17469  20230218   073000    073959  1676677199  24601.7  24632.7
17470  20230218   074000    074959  1676677799  24632.7  24590.2
17471  20230218   075000    075959  1676678399  24590.2  24581.5
17472  20230218   080000    080959  1676678999  24581.3    24580
2023-02-18 08:10:01,659:INFO:pyemd2:main.py:127:handleKline:185189: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=12202 

self.closeSec=1676679599, self.tradeDate='20230218', self.openTime='081000', self.closeTime='081959', self.symbol='BTCUSDT', self.open='24580', self.close='24700'
127.0.0.1 - - [18/Feb/2023 08:20:01] "POST / HTTP/1.1" 200 -
2023-02-18 08:20:01,606:INFO:pyemd2:main.py:125:handleKline:185189: self.closeSec=1676679599, self.tradeDate='20230218', self.openTime='081000', self.closeTime='081959',self.symbol='BTCUSDT',self.open='24580', self.close='24700'
2023-02-18 08:20:01,673:INFO:pyemd2:main.py:126:handleKline:185189: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17469  20230218   073000    073959  1676677199  24601.7  24632.7
17470  20230218   074000    074959  1676677799  24632.7  24590.2
17471  20230218   075000    075959  1676678399  24590.2  24581.5
17472  20230218   080000    080959  1676678999  24581.3    24580
17473  20230218   081000    081959  1676679599    24580    24700
2023-02-18 08:20:01,673:INFO:pyemd2:main.py:127:handleKline:185189: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}


## /root/FIL/strategy/similarity/log.txt ----- -----

12143  20230218   075000    075959  1676678399  24590.2  24581.5
2023-02-18 08:00:02,196:INFO:testStrategy:main.py:103:handleKline:185174: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=12201 

self.closeSec=1676678999, self.tradeDate='20230218', self.openTime='080000', self.closeTime='080959', self.symbol='BTCUSDT', self.open='24581.3', self.close='24580'
2023-02-18 08:10:01,604:INFO:testStrategy:main.py:101:handleKline:185174: self.closeSec=1676678999, self.tradeDate='20230218', self.openTime='080000', self.closeTime='080959',self.symbol='BTCUSDT',self.open='24581.3', self.close='24580'
127.0.0.1 - - [18/Feb/2023 08:10:01] "POST / HTTP/1.1" 200 -
2023-02-18 08:10:01,647:INFO:testStrategy:main.py:102:handleKline:185174: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12140  20230218   072000    072959  1676676599  24599.5  24601.7
12141  20230218   073000    073959  1676677199  24601.7  24632.7
12142  20230218   074000    074959  1676677799  24632.7  24590.2
12143  20230218   075000    075959  1676678399  24590.2  24581.5
12144  20230218   080000    080959  1676678999  24581.3    24580
2023-02-18 08:10:01,647:INFO:testStrategy:main.py:103:handleKline:185174: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=12202 

self.closeSec=1676679599, self.tradeDate='20230218', self.openTime='081000', self.closeTime='081959', self.symbol='BTCUSDT', self.open='24580', self.close='24700'
127.0.0.1 - - [18/Feb/2023 08:20:01] "POST / HTTP/1.1" 200 -
2023-02-18 08:20:01,601:INFO:testStrategy:main.py:101:handleKline:185174: self.closeSec=1676679599, self.tradeDate='20230218', self.openTime='081000', self.closeTime='081959',self.symbol='BTCUSDT',self.open='24580', self.close='24700'
2023-02-18 08:20:01,655:INFO:testStrategy:main.py:102:handleKline:185174: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12141  20230218   073000    073959  1676677199  24601.7  24632.7
12142  20230218   074000    074959  1676677799  24632.7  24590.2
12143  20230218   075000    075959  1676678399  24590.2  24581.5
12144  20230218   080000    080959  1676678999  24581.3    24580
12145  20230218   081000    081959  1676679599    24580    24700
2023-02-18 08:20:01,655:INFO:testStrategy:main.py:103:handleKline:185174: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}


## /root/FIL/strategy/sr_min/log.txt ----- -----

127.0.0.1 - - [18/Feb/2023 08:20:01] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=0, self.total=1000000.0, self.flagDict['side']='', self.tradeCount=0, self.count=19834
self.closeSec=1676679599, self.tradeDate='20230218', self.openTime='081500', self.closeTime='081959', self.symbol='BTCUSDT', self.open=24635.0, self.close=24700.0, self.high=24738.2, self.low=24627.2, self.vol=2881.934, self.amt=71167748.8518 
2023-02-18 08:20:01,647:INFO:sr_min:main.py:172:handleKline:449472: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5855  20230218   075500    075959  ...         0.0        0.0       0
5856  20230218   080000    080459  ...         0.0        0.0       0
5857  20230218   080500    080959  ...         0.0        0.0       0
5858  20230218   081000    081459  ...         0.0        0.0       0
5859  20230218   081500    081959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-02-18 08:20:01,650:INFO:sr_min:main.py:175:handleKline:449472: self.closeSec=1676679599, self.tradeDate='20230218', self.openTime='081500', self.closeTime='081959',self.symbol='BTCUSDT',self.open=24635.0, self.close=24700.0, self.high=24738.2, self.low=24627.2, self.vol=2881.934, self.amt=71167748.8518, ukdf['pct'].iloc[-1]=0.002643 , ukdf['amount'].iloc[-1]=71167748.8518, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5859, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': []}
type(curSign)=<class 'int'>, curSign=0, self.sign=0
--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=0, self.total=1000000.0, self.flagDict['side']='', self.tradeCount=0, self.count=19835
self.closeSec=1676679899, self.tradeDate='20230218', self.openTime='082000', self.closeTime='082459', self.symbol='BTCUSDT', self.open=24700.0, self.close=24724.6, self.high=24743.0, self.low=24682.0, self.vol=1851.879, self.amt=45763982.3408 
127.0.0.1 - - [18/Feb/2023 08:25:01] "POST / HTTP/1.1" 200 -
2023-02-18 08:25:01,711:INFO:sr_min:main.py:172:handleKline:449472: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5856  20230218   080000    080459  ...         0.0        0.0       0
5857  20230218   080500    080959  ...         0.0        0.0       0
5858  20230218   081000    081459  ...         0.0        0.0       0
5859  20230218   081500    081959  ...         0.0        0.0       0
5860  20230218   082000    082459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-02-18 08:25:01,711:INFO:sr_min:main.py:175:handleKline:449472: self.closeSec=1676679899, self.tradeDate='20230218', self.openTime='082000', self.closeTime='082459',self.symbol='BTCUSDT',self.open=24700.0, self.close=24724.6, self.high=24743.0, self.low=24682.0, self.vol=1851.879, self.amt=45763982.3408, ukdf['pct'].iloc[-1]=0.000996 , ukdf['amount'].iloc[-1]=45763982.3408, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5860, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': []}
type(curSign)=<class 'int'>, curSign=0, self.sign=0


## /root/FIL/strategy/s_rsrs/log.txt ----- -----

719  20230217   200000    235959  1676649599  ...    719  1.179899  1.580532     1.0
720  20230218   000000    035959  1676663999  ...    720  1.168760  1.513700     1.0

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '36.518', 'enterprice': '23318.2', 'countrevence': '0', 'unrealprofit': '44256.19031146554', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '24530.10071503', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=1, self.sign=1
--handleKline--:  version='2.0.0', self.name='s_rsrs', self.symbol='BTCUSDT', interval='4h', intervalSec=14400, wid=25, thd=0.6, self.sign=1, self.total=850682.4935724001, self.flagDict['side']='buy', self.tradeCount=20, self.count=508
self.closeSec=1676678399, self.tradeDate='20230218', self.openTime='040000', self.closeTime='075959', self.symbol='BTCUSDT', self.open=24526.8, self.close=24581.5, self.high=25043.2, self.low=24031.1, self.vol=225818.499, self.amt=5563054010.99787 
2023-02-18 08:00:02,054:INFO:s_rsrs:main.py:141:handleKline:185271: self.closeSec=1676678399, self.tradeDate='20230218', self.openTime='040000', self.closeTime='075959',self.symbol='BTCUSDT',self.open=24526.8, self.close=24581.5, self.high=25043.2, self.low=24031.1, self.vol=225818.499, self.amt=5563054010.99787 
127.0.0.1 - - [18/Feb/2023 08:00:02] "POST / HTTP/1.1" 200 -
2023-02-18 08:00:02,100:INFO:s_rsrs:main.py:142:handleKline:185271: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime  ...         vol           amt       pct
717  20230217   120000    155959  ...   59676.035  1.416530e+09 -0.008520
718  20230217   160000    195959  ...   80667.332  1.914111e+09  0.006625
719  20230217   200000    235959  ...  225818.466  5.419494e+09  0.014240
720  20230218   000000    035959  ...  205070.186  4.980683e+09  0.016381
721  20230218   040000    075959  ...  225818.499  5.563054e+09  0.002234

[5 rows x 11 columns]
2023-02-18 08:00:04,233:INFO:s_rsrs:main.py:151:handleKline:185271: df_s.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec  ...  index      beta    zscore  signal
717  20230217   120000    155959  1676620799  ...    717  1.188773  1.686635     1.0
718  20230217   160000    195959  1676635199  ...    718  1.163211  1.569360     1.0
719  20230217   200000    235959  1676649599  ...    719  1.179899  1.580532     1.0
720  20230218   000000    035959  1676663999  ...    720  1.168760  1.513700     1.0
721  20230218   040000    075959  1676678399  ...    721  1.199144  1.565452     1.0

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '36.518', 'enterprice': '23318.2', 'countrevence': '0', 'unrealprofit': '46046.4904167116', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '24579.1258562', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=1, self.sign=1


