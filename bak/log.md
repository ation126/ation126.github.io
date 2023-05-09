# 20230509 16:26:01

## /root/FIL/strategy/amihud/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=993672.4896432, self.flagDict['side']='sell', self.tradeCount=2, self.count=46965
self.closeSec=1683620399, self.tradeDate='20230509', self.openTime='161500', self.closeTime='161959', self.symbol='BTCUSDT', self.open=27611.2, self.close=27596.2, self.high=27611.2, self.low=27580.0, self.vol=872.722, self.amt=24079712.3197 
127.0.0.1 - - [09/May/2023 16:20:02] "POST / HTTP/1.1" 200 -
2023-05-09 16:20:05,941:INFO:amihud:main.py:172:handleKline:200676: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5951  20230509   155500    155959  ...         0.0        0.0       0
5952  20230509   160000    160459  ...         0.0        0.0       0
5953  20230509   160500    160959  ...         0.0        0.0       0
5954  20230509   161000    161459  ...         0.0        0.0       0
5955  20230509   161500    161959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-05-09 16:20:05,944:INFO:amihud:main.py:175:handleKline:200676: self.closeSec=1683620399, self.tradeDate='20230509', self.openTime='161500', self.closeTime='161959',self.symbol='BTCUSDT',self.open=27611.2, self.close=27596.2, self.high=27611.2, self.low=27580.0, self.vol=872.722, self.amt=24079712.3197, ukdf['pct'].iloc[-1]=-0.000543 , ukdf['amount'].iloc[-1]=24079712.3197, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5955, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '60.176', 'enterprice': '16529.3', 'countrevence': '0', 'unrealprofit': '-665889.5632', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '27595', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1
127.0.0.1 - - [09/May/2023 16:25:02] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=993672.4896432, self.flagDict['side']='sell', self.tradeCount=2, self.count=46966
self.closeSec=1683620699, self.tradeDate='20230509', self.openTime='162000', self.closeTime='162459', self.symbol='BTCUSDT', self.open=27596.1, self.close=27599.9, self.high=27607.4, self.low=27580.1, self.vol=596.265, self.amt=16452032.6354 
2023-05-09 16:25:02,103:INFO:amihud:main.py:172:handleKline:200676: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5952  20230509   160000    160459  ...         0.0        0.0       0
5953  20230509   160500    160959  ...         0.0        0.0       0
5954  20230509   161000    161459  ...         0.0        0.0       0
5955  20230509   161500    161959  ...         0.0        0.0       0
5956  20230509   162000    162459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-05-09 16:25:02,103:INFO:amihud:main.py:175:handleKline:200676: self.closeSec=1683620699, self.tradeDate='20230509', self.openTime='162000', self.closeTime='162459',self.symbol='BTCUSDT',self.open=27596.1, self.close=27599.9, self.high=27607.4, self.low=27580.1, self.vol=596.265, self.amt=16452032.6354, ukdf['pct'].iloc[-1]=0.000134 , ukdf['amount'].iloc[-1]=16452032.6354, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5956, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '60.176', 'enterprice': '16529.3', 'countrevence': '0', 'unrealprofit': '-666131.70823286672', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '27599.02394697', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1


## /root/FIL/strategy/factorcheck/log.txt ----- -----


--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=23, self.factor=0.43541661550691446, self.count=47527 

self.closeSec=1683619199, self.tradeDate='20230509', self.openTime='155500', self.closeTime='155959', self.symbol='BTCUSDT', self.open=27609.6, self.close=27649.3, self.high=27661.7, self.low=27609.4 
127.0.0.1 - - [09/May/2023 16:00:02] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=23, self.factor=0.43541661550691446, self.count=47528 

self.closeSec=1683619499, self.tradeDate='20230509', self.openTime='160000', self.closeTime='160459', self.symbol='BTCUSDT', self.open=27649.3, self.close=27622.5, self.high=27655.1, self.low=27619.9 
127.0.0.1 - - [09/May/2023 16:05:02] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=23, self.factor=0.43541661550691446, self.count=47529 

self.closeSec=1683619799, self.tradeDate='20230509', self.openTime='160500', self.closeTime='160959', self.symbol='BTCUSDT', self.open=27622.4, self.close=27614.1, self.high=27633.1, self.low=27603.3 
127.0.0.1 - - [09/May/2023 16:10:02] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=23, self.factor=0.43541661550691446, self.count=47530 
127.0.0.1 - - [09/May/2023 16:15:02] "POST / HTTP/1.1" 200 -

self.closeSec=1683620099, self.tradeDate='20230509', self.openTime='161000', self.closeTime='161459', self.symbol='BTCUSDT', self.open=27614.0, self.close=27611.2, self.high=27620.0, self.low=27603.1 

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=23, self.factor=0.43541661550691446, self.count=47531 

self.closeSec=1683620399, self.tradeDate='20230509', self.openTime='161500', self.closeTime='161959', self.symbol='BTCUSDT', self.open=27611.2, self.close=27596.2, self.high=27611.2, self.low=27580.0 
127.0.0.1 - - [09/May/2023 16:20:02] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [09/May/2023 16:25:02] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=23, self.factor=0.43541661550691446, self.count=47532 

self.closeSec=1683620699, self.tradeDate='20230509', self.openTime='162000', self.closeTime='162459', self.symbol='BTCUSDT', self.open=27596.1, self.close=27599.9, self.high=27607.4, self.low=27580.1 


## /root/FIL/strategy/logic/log.txt ----- -----

2023-05-09 16:00:21,529:DEBUG:logic:main.py:463:getModel:885513: df_s.iloc[-5:,:] :
          date closeTime     open  ...    alpha58   alpha67   alpha72
5785  20230509    132959  27598.0  ...  49.166667  0.405246  0.677483
5786  20230509    135959  27553.3  ...  48.750000  0.403469  0.675531
5787  20230509    142959  27540.3  ...  48.750000  0.394272  0.679229
5788  20230509    145959  27472.0  ...  48.750000  0.407015  0.677580
5789  20230509    152959  27535.1  ...  49.166667  0.416543  0.672163

[5 rows x 33 columns]
0.5461254612546126
acc is : 0.5461254612546126
2023-05-09 16:00:21,641:INFO:logic:main.py:468:getModel:885513: df_pred.iloc[-5:,:] :
     pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
537     1  0.499243  0.500757       0  ...  0.994315  -1.0    0.0  0.932315
538     0  0.505770  0.494230       0  ...  0.996781  -1.0    0.0  0.930002
539     1  0.489048  0.510952       1  ...  0.994491  -1.0    0.0  0.932139
540     0  0.514222  0.485778       1  ...  0.992758  -1.0    0.0  0.933763
541     0  0.517052  0.482948       1  ...  0.990371  -1.0    0.0  0.936008

[5 rows x 10 columns]
2023-05-09 16:00:21,667:INFO:logic:main.py:478:getModel:885513: df_panel.iloc[-5:,:] :
    pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
45     1  0.499227  0.500773       0  ...  0.994315  -1.0    0.0  0.937520
46     0  0.505628  0.494372       0  ...  0.996781  -1.0    0.0  0.932537
47     1  0.489719  0.510281       1  ...  0.973563  -1.0    0.0  0.934689
48     0  0.514446  0.485554       1  ...  0.971866  -1.0    0.0  0.938996
49     0  0.517052  0.482948       1  ...  0.990371  -1.0    0.0  0.936008

[5 rows x 10 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': []}


## /root/FIL/strategy/modifiedmom/log.txt ----- -----


--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=23761 

self.closeSec=1683617399, self.tradeDate='20230509', self.openTime='152000', self.closeTime='152959', self.symbol='BTCUSDT', self.open='27561.1', self.close='27583'
127.0.0.1 - - [09/May/2023 15:30:03] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [09/May/2023 15:40:02] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=23762 

self.closeSec=1683617999, self.tradeDate='20230509', self.openTime='153000', self.closeTime='153959', self.symbol='BTCUSDT', self.open='27583', self.close='27564.3'

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=23763 

self.closeSec=1683618599, self.tradeDate='20230509', self.openTime='154000', self.closeTime='154959', self.symbol='BTCUSDT', self.open='27564.2', self.close='27566'
127.0.0.1 - - [09/May/2023 15:50:02] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=23764 

self.closeSec=1683619199, self.tradeDate='20230509', self.openTime='155000', self.closeTime='155959', self.symbol='BTCUSDT', self.open='27566.1', self.close='27649.3'
127.0.0.1 - - [09/May/2023 16:00:03] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [09/May/2023 16:10:02] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=23765 

self.closeSec=1683619799, self.tradeDate='20230509', self.openTime='160000', self.closeTime='160959', self.symbol='BTCUSDT', self.open='27649.3', self.close='27614.1'

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=23766 

self.closeSec=1683620399, self.tradeDate='20230509', self.openTime='161000', self.closeTime='161959', self.symbol='BTCUSDT', self.open='27614', self.close='27596.2'
127.0.0.1 - - [09/May/2023 16:20:05] "POST / HTTP/1.1" 200 -


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

127.0.0.1 - - [09/May/2023 15:30:03] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=23762 

self.closeSec=1683617399, self.tradeDate='20230509', self.openTime='152000', self.closeTime='152959', self.symbol='BTCUSDT', self.open='27561.1', self.close='27583'

--handleKline--: 127.0.0.1 - - [09/May/2023 15:40:02] "POST / HTTP/1.1" 200 -
 self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=23763 

self.closeSec=1683617999, self.tradeDate='20230509', self.openTime='153000', self.closeTime='153959', self.symbol='BTCUSDT', self.open='27583', self.close='27564.3'

--handleKline--: 127.0.0.1 - - [09/May/2023 15:50:02] "POST / HTTP/1.1" 200 -
 self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=23764 

self.closeSec=1683618599, self.tradeDate='20230509', self.openTime='154000', self.closeTime='154959', self.symbol='BTCUSDT', self.open='27564.2', self.close='27566'

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=23765 

self.closeSec=1683619199, self.tradeDate='20230509', self.openTime='155000', self.closeTime='155959', self.symbol='BTCUSDT', self.open='27566.1', self.close='27649.3'
127.0.0.1 - - [09/May/2023 16:00:03] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=23766 

self.closeSec=1683619799, self.tradeDate='20230509', self.openTime='160000', self.closeTime='160959', self.symbol='BTCUSDT', self.open='27649.3', self.close='27614.1'
127.0.0.1 - - [09/May/2023 16:10:02] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=23767 

self.closeSec=1683620399, self.tradeDate='20230509', self.openTime='161000', self.closeTime='161959', self.symbol='BTCUSDT', self.open='27614', self.close='27596.2'
127.0.0.1 - - [09/May/2023 16:20:05] "POST / HTTP/1.1" 200 -


## /root/FIL/strategy/similarity/log.txt ----- -----

127.0.0.1 - - [09/May/2023 15:30:03] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=23762 

self.closeSec=1683617399, self.tradeDate='20230509', self.openTime='152000', self.closeTime='152959', self.symbol='BTCUSDT', self.open='27561.1', self.close='27583'

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=23763 

self.closeSec=1683617999, self.tradeDate='20230509', self.openTime='153000', self.closeTime='153959', self.symbol='BTCUSDT', self.open='27583', self.close='27564.3'
127.0.0.1 - - [09/May/2023 15:40:02] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=23764 

self.closeSec=1683618599, self.tradeDate='20230509', self.openTime='154000', self.closeTime='154959', self.symbol='BTCUSDT', self.open='27564.2', self.close='27566'
127.0.0.1 - - [09/May/2023 15:50:02] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [09/May/2023 16:00:03] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=23765 

self.closeSec=1683619199, self.tradeDate='20230509', self.openTime='155000', self.closeTime='155959', self.symbol='BTCUSDT', self.open='27566.1', self.close='27649.3'

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=23766 

self.closeSec=1683619799, self.tradeDate='20230509', self.openTime='160000', self.closeTime='160959', self.symbol='BTCUSDT', self.open='27649.3', self.close='27614.1'
127.0.0.1 - - [09/May/2023 16:10:02] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=23767 

self.closeSec=1683620399, self.tradeDate='20230509', self.openTime='161000', self.closeTime='161959', self.symbol='BTCUSDT', self.open='27614', self.close='27596.2'
127.0.0.1 - - [09/May/2023 16:20:05] "POST / HTTP/1.1" 200 -


## /root/FIL/strategy/sr_min/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=0, self.total=1000000.0, self.flagDict['side']='', self.tradeCount=0, self.count=42963
self.closeSec=1683620399, self.tradeDate='20230509', self.openTime='161500', self.closeTime='161959', self.symbol='BTCUSDT', self.open=27611.2, self.close=27596.2, self.high=27611.2, self.low=27580.0, self.vol=872.722, self.amt=24079712.3197 
127.0.0.1 - - [09/May/2023 16:20:02] "POST / HTTP/1.1" 200 -
2023-05-09 16:20:05,928:INFO:sr_min:main.py:172:handleKline:449472: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5951  20230509   155500    155959  ...         0.0        0.0       0
5952  20230509   160000    160459  ...         0.0        0.0       0
5953  20230509   160500    160959  ...         0.0        0.0       0
5954  20230509   161000    161459  ...         0.0        0.0       0
5955  20230509   161500    161959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-05-09 16:20:05,933:INFO:sr_min:main.py:175:handleKline:449472: self.closeSec=1683620399, self.tradeDate='20230509', self.openTime='161500', self.closeTime='161959',self.symbol='BTCUSDT',self.open=27611.2, self.close=27596.2, self.high=27611.2, self.low=27580.0, self.vol=872.722, self.amt=24079712.3197, ukdf['pct'].iloc[-1]=-0.000543 , ukdf['amount'].iloc[-1]=24079712.3197, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5955, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': []}
type(curSign)=<class 'int'>, curSign=0, self.sign=0
--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=0, self.total=1000000.0, self.flagDict['side']='', self.tradeCount=0, self.count=42964
self.closeSec=1683620699, self.tradeDate='20230509', self.openTime='162000', self.closeTime='162459', self.symbol='BTCUSDT', self.open=27596.1, self.close=27599.9, self.high=27607.4, self.low=27580.1, self.vol=596.265, self.amt=16452032.6354 
127.0.0.1 - - [09/May/2023 16:25:02] "POST / HTTP/1.1" 200 -
2023-05-09 16:25:02,105:INFO:sr_min:main.py:172:handleKline:449472: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5952  20230509   160000    160459  ...         0.0        0.0       0
5953  20230509   160500    160959  ...         0.0        0.0       0
5954  20230509   161000    161459  ...         0.0        0.0       0
5955  20230509   161500    161959  ...         0.0        0.0       0
5956  20230509   162000    162459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-05-09 16:25:02,105:INFO:sr_min:main.py:175:handleKline:449472: self.closeSec=1683620699, self.tradeDate='20230509', self.openTime='162000', self.closeTime='162459',self.symbol='BTCUSDT',self.open=27596.1, self.close=27599.9, self.high=27607.4, self.low=27580.1, self.vol=596.265, self.amt=16452032.6354, ukdf['pct'].iloc[-1]=0.000134 , ukdf['amount'].iloc[-1]=16452032.6354, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5956, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': []}
type(curSign)=<class 'int'>, curSign=0, self.sign=0


## /root/FIL/strategy/s_rsrs/log.txt ----- -----

2023-05-09 12:00:13,236:INFO:s_rsrs:main.py:343:handleOrderNew:185271: handleOrderNew: data=OrderType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'clientorderid': '42151F1683604807549I0L65', 'symbol': 'BTCUSDT', 'gatewayorderid': 1683604807919586, 'quantity': '46.718', 'price': '27611.9', 'stopprice': '0', 'ordertype': '', 'side': 'BUY', 'status': 'FILLED', 'positionside': 'LONG', 'createtime': 1683604806711, 'updatetime': 1683604807919, 'tradetype': 'usdt', 'selfid': 42151, 'filltrades': [TradeType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'tradeid': 1683604807919, 'clientorderid': '42151F1683604807549I0L65', 'price': '27611.9', 'quantity': '46.718', 'commission': '1289.9727442', 'commissionasset': 'USDT', 'tradetime': 1683604807919, 'tradetype': 'usdt', 'gatetype': 'simulator', 'handletime': 1683604807919}], 'gatetype': 'simulator', 'handletime': 0}
2023-05-09 12:00:13,236:INFO:s_rsrs:main.py:346:handleOrderFilled:185271: handleOrderFilled: data=OrderType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'clientorderid': '42151F1683604807549I0L65', 'symbol': 'BTCUSDT', 'gatewayorderid': 1683604807919586, 'quantity': '46.718', 'price': '27611.9', 'stopprice': '0', 'ordertype': '', 'side': 'BUY', 'status': 'FILLED', 'positionside': 'LONG', 'createtime': 1683604806711, 'updatetime': 1683604807919, 'tradetype': 'usdt', 'selfid': 42151, 'filltrades': [TradeType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'tradeid': 1683604807919, 'clientorderid': '42151F1683604807549I0L65', 'price': '27611.9', 'quantity': '46.718', 'commission': '1289.9727442', 'commissionasset': 'USDT', 'tradetime': 1683604807919, 'tradetype': 'usdt', 'gatetype': 'simulator', 'handletime': 1683604807919}], 'gatetype': 'simulator', 'handletime': 0}
2023-05-09 12:00:13,596:INFO:s_rsrs:main.py:343:handleOrderNew:185271: handleOrderNew: data=OrderType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'clientorderid': '42152F1683604813194I0L65', 'symbol': 'BTCUSDT', 'gatewayorderid': 1683604813551941, 'quantity': '52.501', 'price': '27610.1', 'stopprice': '0', 'ordertype': '', 'side': 'BUY', 'status': 'FILLED', 'positionside': 'LONG', 'createtime': 1683604812720, 'updatetime': 1683604813551, 'tradetype': 'usdt', 'selfid': 42152, 'filltrades': [TradeType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'tradeid': 1683604813551, 'clientorderid': '42152F1683604813194I0L65', 'price': '27610.1', 'quantity': '52.501', 'commission': '1449.5578601', 'commissionasset': 'USDT', 'tradetime': 1683604813551, 'tradetype': 'usdt', 'gatetype': 'simulator', 'handletime': 1683604813551}], 'gatetype': 'simulator', 'handletime': 0}
127.0.0.1 - - [09/May/2023 12:00:13] "POST / HTTP/1.1" 200 -
2023-05-09 12:00:13,839:INFO:s_rsrs:main.py:346:handleOrderFilled:185271: handleOrderFilled: data=OrderType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'clientorderid': '42152F1683604813194I0L65', 'symbol': 'BTCUSDT', 'gatewayorderid': 1683604813551941, 'quantity': '52.501', 'price': '27610.1', 'stopprice': '0', 'ordertype': '', 'side': 'BUY', 'status': 'FILLED', 'positionside': 'LONG', 'createtime': 1683604812720, 'updatetime': 1683604813551, 'tradetype': 'usdt', 'selfid': 42152, 'filltrades': [TradeType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'tradeid': 1683604813551, 'clientorderid': '42152F1683604813194I0L65', 'price': '27610.1', 'quantity': '52.501', 'commission': '1449.5578601', 'commissionasset': 'USDT', 'tradetime': 1683604813551, 'tradetype': 'usdt', 'gatetype': 'simulator', 'handletime': 1683604813551}], 'gatetype': 'simulator', 'handletime': 0}
127.0.0.1 - - [09/May/2023 12:00:13] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='s_rsrs', self.symbol='BTCUSDT', interval='4h', intervalSec=14400, wid=25, thd=0.6, self.sign=1, self.total=1448108.3022399, self.flagDict['side']='buy', self.tradeCount=34, self.count=990
self.closeSec=1683619199, self.tradeDate='20230509', self.openTime='120000', self.closeTime='155959', self.symbol='BTCUSDT', self.open=27612.4, self.close=27649.3, self.high=27661.7, self.low=27423.9, self.vol=47560.102, self.amt=1310025371.6453 
127.0.0.1 - - [09/May/2023 16:00:03] "POST / HTTP/1.1" 200 -
2023-05-09 16:00:03,231:INFO:s_rsrs:main.py:141:handleKline:185271: self.closeSec=1683619199, self.tradeDate='20230509', self.openTime='120000', self.closeTime='155959',self.symbol='BTCUSDT',self.open=27612.4, self.close=27649.3, self.high=27661.7, self.low=27423.9, self.vol=47560.102, self.amt=1310025371.6453 
2023-05-09 16:00:03,258:INFO:s_rsrs:main.py:142:handleKline:185271: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime  ...         vol           amt       pct
719  20230508   200000    235959  ...  110121.512  3.068481e+09 -0.001723
720  20230509   000000    035959  ...  148637.520  4.091222e+09 -0.019552
721  20230509   040000    075959  ...   65257.965  1.794462e+09  0.012101
722  20230509   080000    115959  ...   46056.079  1.272192e+09 -0.001710
723  20230509   120000    155959  ...   47560.102  1.310025e+09  0.001333

[5 rows x 11 columns]
2023-05-09 16:00:04,989:INFO:s_rsrs:main.py:151:handleKline:185271: df_s.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec  ...  index      beta    zscore  signal
719  20230508   200000    235959  1683561599  ...    719  0.588915  0.176150     NaN
720  20230509   000000    035959  1683575999  ...    720  0.604776  0.247013     NaN
721  20230509   040000    075959  1683590399  ...    721  0.663889  0.466367     NaN
722  20230509   080000    115959  1683604799  ...    722  0.727677  0.697560     1.0
723  20230509   120000    155959  1683619199  ...    723  0.764124  0.834596     1.0

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '52.501', 'enterprice': '27610.1', 'countrevence': '0', 'unrealprofit': '2439.55927918571', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '27656.56691071', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=1, self.sign=1


