# 20231004 16:26:02

## /root/FIL/strategy/amihud/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=373746.4768026, self.flagDict['side']='sell', self.tradeCount=2, self.count=41236
self.closeSec=1696407599, self.tradeDate='20231004', self.openTime='161500', self.closeTime='161959', self.symbol='BTCUSDT', self.open=27438.0, self.close=27420.5, self.high=27442.7, self.low=27420.5, self.vol=403.686, self.amt=11072846.7152 
127.0.0.1 - - [04/Oct/2023 16:20:02] "POST / HTTP/1.1" 200 -
2023-10-04 16:20:05,924:INFO:amihud:main.py:172:handleKline:2219019: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5951  20231004   155500    155959  ...         0.0        0.0       0
5952  20231004   160000    160459  ...         0.0        0.0       0
5953  20231004   160500    160959  ...         0.0        0.0       0
5954  20231004   161000    161459  ...         0.0        0.0       0
5955  20231004   161500    161959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-10-04 16:20:05,930:INFO:amihud:main.py:175:handleKline:2219019: self.closeSec=1696407599, self.tradeDate='20231004', self.openTime='161500', self.closeTime='161959',self.symbol='BTCUSDT',self.open=27438.0, self.close=27420.5, self.high=27442.7, self.low=27420.5, self.vol=403.686, self.amt=11072846.7152, ukdf['pct'].iloc[-1]=-0.000634 , ukdf['amount'].iloc[-1]=11072846.7152, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5955, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '13.926', 'enterprice': '26864.9', 'countrevence': '0', 'unrealprofit': '-7772.1006', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '27423', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1
127.0.0.1 - - [04/Oct/2023 16:25:00] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=373746.4768026, self.flagDict['side']='sell', self.tradeCount=2, self.count=41237
self.closeSec=1696407899, self.tradeDate='20231004', self.openTime='162000', self.closeTime='162459', self.symbol='BTCUSDT', self.open=27421.4, self.close=27460.0, self.high=27460.0, self.low=27421.4, self.vol=442.715, self.amt=12151346.4829 
2023-10-04 16:25:00,810:INFO:amihud:main.py:172:handleKline:2219019: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5952  20231004   160000    160459  ...         0.0        0.0       0
5953  20231004   160500    160959  ...         0.0        0.0       0
5954  20231004   161000    161459  ...         0.0        0.0       0
5955  20231004   161500    161959  ...         0.0        0.0       0
5956  20231004   162000    162459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-10-04 16:25:00,811:INFO:amihud:main.py:175:handleKline:2219019: self.closeSec=1696407899, self.tradeDate='20231004', self.openTime='162000', self.closeTime='162459',self.symbol='BTCUSDT',self.open=27421.4, self.close=27460.0, self.high=27460.0, self.low=27421.4, self.vol=442.715, self.amt=12151346.4829, ukdf['pct'].iloc[-1]=0.001441 , ukdf['amount'].iloc[-1]=12151346.4829, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5956, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '13.926', 'enterprice': '26864.9', 'countrevence': '0', 'unrealprofit': '-8302.72007039046', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '27461.10279121', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1


## /root/FIL/strategy/factorcheck/log.txt ----- -----


--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.714181719035411, self.count=41234 

self.closeSec=1696406399, self.tradeDate='20231004', self.openTime='155500', self.closeTime='155959', self.symbol='BTCUSDT', self.open=27431.3, self.close=27441.9, self.high=27441.9, self.low=27431.1 
127.0.0.1 - - [04/Oct/2023 16:00:00] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.714181719035411, self.count=41235 

self.closeSec=1696406699, self.tradeDate='20231004', self.openTime='160000', self.closeTime='160459', self.symbol='BTCUSDT', self.open=27442.0, self.close=27446.0, self.high=27460.0, self.low=27434.1 
127.0.0.1 - - [04/Oct/2023 16:05:00] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.714181719035411, self.count=41236 

self.closeSec=1696406999, self.tradeDate='20231004', self.openTime='160500', self.closeTime='160959', self.symbol='BTCUSDT', self.open=27445.9, self.close=27441.0, self.high=27446.0, self.low=27430.2 
127.0.0.1 - - [04/Oct/2023 16:10:00] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [04/Oct/2023 16:15:00] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.714181719035411, self.count=41237 

self.closeSec=1696407299, self.tradeDate='20231004', self.openTime='161000', self.closeTime='161459', self.symbol='BTCUSDT', self.open=27441.0, self.close=27437.9, self.high=27443.1, self.low=27435.5 

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.714181719035411, self.count=41238 

self.closeSec=1696407599, self.tradeDate='20231004', self.openTime='161500', self.closeTime='161959', self.symbol='BTCUSDT', self.open=27438.0, self.close=27420.5, self.high=27442.7, self.low=27420.5 
127.0.0.1 - - [04/Oct/2023 16:20:01] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.714181719035411, self.count=41239 

self.closeSec=1696407899, self.tradeDate='20231004', self.openTime='162000', self.closeTime='162459', self.symbol='BTCUSDT', self.open=27421.4, self.close=27460.0, self.high=27460.0, self.low=27421.4 
127.0.0.1 - - [04/Oct/2023 16:25:00] "POST / HTTP/1.1" 200 -


## /root/FIL/strategy/logic/log.txt ----- -----

2023-10-04 16:00:18,730:DEBUG:logic:main.py:463:getModel:2218526: df_s.iloc[-5:,:] :
          date closeTime     open  ...  alpha58   alpha67   alpha72
5785  20231004    132959  27378.6  ...     55.0  0.476400  0.567197
5786  20231004    135959  27373.5  ...     55.0  0.480589  0.559487
5787  20231004    142959  27397.4  ...     55.0  0.471210  0.559111
5788  20231004    145959  27347.0  ...     55.0  0.483485  0.550354
5789  20231004    152959  27408.5  ...     55.0  0.482102  0.538944

[5 rows x 33 columns]
0.5719557195571956
acc is : 0.5719557195571956
2023-10-04 16:00:18,820:INFO:logic:main.py:468:getModel:2218526: df_pred.iloc[-5:,:] :
     pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
537     1  0.497300  0.502700       1  ...  0.961717  -1.0    0.0  1.030287
538     0  0.503582  0.496418       0  ...  0.963514  -1.0    0.0  1.028362
539     1  0.482166  0.517834       1  ...  0.961362  -1.0    0.0  1.030659
540     0  0.514648  0.485352       0  ...  0.961621  -1.0    0.0  1.030381
541     1  0.498172  0.501828       1  ...  0.960151  -1.0    0.0  1.031957

[5 rows x 10 columns]
2023-10-04 16:00:18,840:INFO:logic:main.py:478:getModel:2218526: df_panel.iloc[-5:,:] :
    pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
45     1  0.497291  0.502709       1  ...  0.961717  -1.0    0.0  1.031067
46     0  0.503601  0.496399       0  ...  0.963514  -1.0    0.0  1.029306
47     1  0.482520  0.517480       1  ...  0.979892  -1.0    0.0  1.031645
48     0  0.514616  0.485384       0  ...  0.961621  -1.0    0.0  1.030428
49     1  0.498172  0.501828       1  ...  0.960151  -1.0    0.0  1.031957

[5 rows x 10 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '23.906', 'enterprice': '28298.9', 'countrevence': '0', 'unrealprofit': '20511.96916202912', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '27440.87401648', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}


## /root/FIL/strategy/modifiedmom/log.txt ----- -----


--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=20615 

self.closeSec=1696404599, self.tradeDate='20231004', self.openTime='152000', self.closeTime='152959', self.symbol='BTCUSDT', self.open='27417.5', self.close='27400'
127.0.0.1 - - [04/Oct/2023 15:30:01] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [04/Oct/2023 15:40:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=20616 

self.closeSec=1696405199, self.tradeDate='20231004', self.openTime='153000', self.closeTime='153959', self.symbol='BTCUSDT', self.open='27400', self.close='27391.8'

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=20617 127.0.0.1 - - [04/Oct/2023 15:50:01] "POST / HTTP/1.1" 200 -


self.closeSec=1696405799, self.tradeDate='20231004', self.openTime='154000', self.closeTime='154959', self.symbol='BTCUSDT', self.open='27391.8', self.close='27430.1'

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=20618 

self.closeSec=1696406399, self.tradeDate='20231004', self.openTime='155000', self.closeTime='155959', self.symbol='BTCUSDT', self.open='27430.2', self.close='27441.9'
127.0.0.1 - - [04/Oct/2023 16:00:01] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [04/Oct/2023 16:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=20619 

self.closeSec=1696406999, self.tradeDate='20231004', self.openTime='160000', self.closeTime='160959', self.symbol='BTCUSDT', self.open='27442', self.close='27441'

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=20620 

self.closeSec=1696407599, self.tradeDate='20231004', self.openTime='161000', self.closeTime='161959', self.symbol='BTCUSDT', self.open='27441', self.close='27420.5'
127.0.0.1 - - [04/Oct/2023 16:20:04] "POST / HTTP/1.1" 200 -


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


--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=20618 

self.closeSec=1696404599, self.tradeDate='20231004', self.openTime='152000', self.closeTime='152959', self.symbol='BTCUSDT', self.open='27417.5', self.close='27400'
127.0.0.1 - - [04/Oct/2023 15:30:01] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [04/Oct/2023 15:40:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=20619 

self.closeSec=1696405199, self.tradeDate='20231004', self.openTime='153000', self.closeTime='153959', self.symbol='BTCUSDT', self.open='27400', self.close='27391.8'

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=20620 

self.closeSec=1696405799, self.tradeDate='20231004', self.openTime='154000', self.closeTime='154959', self.symbol='BTCUSDT', self.open='27391.8', self.close='27430.1'
127.0.0.1 - - [04/Oct/2023 15:50:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=20621 

self.closeSec=1696406399, self.tradeDate='20231004', self.openTime='155000', self.closeTime='155959', self.symbol='BTCUSDT', self.open='27430.2', self.close='27441.9'
127.0.0.1 - - [04/Oct/2023 16:00:01] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [04/Oct/2023 16:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=20622 

self.closeSec=1696406999, self.tradeDate='20231004', self.openTime='160000', self.closeTime='160959', self.symbol='BTCUSDT', self.open='27442', self.close='27441'

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=20623 

self.closeSec=1696407599, self.tradeDate='20231004', self.openTime='161000', self.closeTime='161959', self.symbol='BTCUSDT', self.open='27441', self.close='27420.5'
127.0.0.1 - - [04/Oct/2023 16:20:04] "POST / HTTP/1.1" 200 -


## /root/FIL/strategy/similarity/log.txt ----- -----


--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=20618 

self.closeSec=1696404599, self.tradeDate='20231004', self.openTime='152000', self.closeTime='152959', self.symbol='BTCUSDT', self.open='27417.5', self.close='27400'
127.0.0.1 - - [04/Oct/2023 15:30:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=20619 

self.closeSec=1696405199, self.tradeDate='20231004', self.openTime='153000', self.closeTime='153959', self.symbol='BTCUSDT', self.open='27400', self.close='27391.8'
127.0.0.1 - - [04/Oct/2023 15:40:01] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [04/Oct/2023 15:50:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=20620 

self.closeSec=1696405799, self.tradeDate='20231004', self.openTime='154000', self.closeTime='154959', self.symbol='BTCUSDT', self.open='27391.8', self.close='27430.1'

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=20621 

self.closeSec=1696406399, self.tradeDate='20231004', self.openTime='155000', self.closeTime='155959', self.symbol='BTCUSDT', self.open='27430.2', self.close='27441.9'
127.0.0.1 - - [04/Oct/2023 16:00:01] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [04/Oct/2023 16:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=20622 

self.closeSec=1696406999, self.tradeDate='20231004', self.openTime='160000', self.closeTime='160959', self.symbol='BTCUSDT', self.open='27442', self.close='27441'

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=20623 

self.closeSec=1696407599, self.tradeDate='20231004', self.openTime='161000', self.closeTime='161959', self.symbol='BTCUSDT', self.open='27441', self.close='27420.5'
127.0.0.1 - - [04/Oct/2023 16:20:04] "POST / HTTP/1.1" 200 -


## /root/FIL/strategy/sr_min/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=1, self.total=996015.990996, self.flagDict['side']='buy', self.tradeCount=1, self.count=41236
self.closeSec=1696407599, self.tradeDate='20231004', self.openTime='161500', self.closeTime='161959', self.symbol='BTCUSDT', self.open=27438.0, self.close=27420.5, self.high=27442.7, self.low=27420.5, self.vol=403.686, self.amt=11072846.7152 
127.0.0.1 - - [04/Oct/2023 16:20:02] "POST / HTTP/1.1" 200 -
2023-10-04 16:20:05,931:INFO:sr_min:main.py:172:handleKline:2219263: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5951  20231004   155500    155959  ...         0.0        0.0       0
5952  20231004   160000    160459  ...         0.0        0.0       0
5953  20231004   160500    160959  ...         0.0        0.0       0
5954  20231004   161000    161459  ...         0.0        0.0       0
5955  20231004   161500    161959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-10-04 16:20:05,939:INFO:sr_min:main.py:175:handleKline:2219263: self.closeSec=1696407599, self.tradeDate='20231004', self.openTime='161500', self.closeTime='161959',self.symbol='BTCUSDT',self.open=27438.0, self.close=27420.5, self.high=27442.7, self.low=27420.5, self.vol=403.686, self.amt=11072846.7152, ukdf['pct'].iloc[-1]=-0.000634 , ukdf['amount'].iloc[-1]=11072846.7152, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5955, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '37.141', 'enterprice': '26844', 'countrevence': '0', 'unrealprofit': '21504.639', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '27423', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=1
--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=1, self.total=996015.990996, self.flagDict['side']='buy', self.tradeCount=1, self.count=41237
self.closeSec=1696407899, self.tradeDate='20231004', self.openTime='162000', self.closeTime='162459', self.symbol='BTCUSDT', self.open=27421.4, self.close=27460.0, self.high=27460.0, self.low=27421.4, self.vol=442.715, self.amt=12151346.4829 
127.0.0.1 - - [04/Oct/2023 16:25:00] "POST / HTTP/1.1" 200 -
2023-10-04 16:25:00,820:INFO:sr_min:main.py:172:handleKline:2219263: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5952  20231004   160000    160459  ...         0.0        0.0       0
5953  20231004   160500    160959  ...         0.0        0.0       0
5954  20231004   161000    161459  ...         0.0        0.0       0
5955  20231004   161500    161959  ...         0.0        0.0       0
5956  20231004   162000    162459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-10-04 16:25:00,821:INFO:sr_min:main.py:175:handleKline:2219263: self.closeSec=1696407899, self.tradeDate='20231004', self.openTime='162000', self.closeTime='162459',self.symbol='BTCUSDT',self.open=27421.4, self.close=27460.0, self.high=27460.0, self.low=27421.4, self.vol=442.715, self.amt=12151346.4829, ukdf['pct'].iloc[-1]=0.001441 , ukdf['amount'].iloc[-1]=12151346.4829, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5956, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '37.141', 'enterprice': '26844', 'countrevence': '0', 'unrealprofit': '22919.81476833061', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '27461.10279121', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=1


## /root/FIL/strategy/s_rsrs/log.txt ----- -----

721  20231004   040000    075959  1696377599  ...    721  1.186991  1.095715     1.0
722  20231004   080000    115959  1696391999  ...    722  1.151617  0.991374     1.0

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '43.732', 'enterprice': '28015.5', 'countrevence': '0', 'unrealprofit': '-26120.1266547156', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '27418.2227967', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=1, self.sign=1
--handleKline--:  version='2.0.0', self.name='s_rsrs', self.symbol='BTCUSDT', interval='4h', intervalSec=14400, wid=25, thd=0.6, self.sign=1, self.total=1223948.6721539998, self.flagDict['side']='buy', self.tradeCount=29, self.count=859
self.closeSec=1696406399, self.tradeDate='20231004', self.openTime='120000', self.closeTime='155959', self.symbol='BTCUSDT', self.open=27416.3, self.close=27441.9, self.high=27441.9, self.low=27335.8, self.vol=18070.915, self.amt=494972036.4288 
2023-10-04 16:00:01,537:INFO:s_rsrs:main.py:141:handleKline:2218689: self.closeSec=1696406399, self.tradeDate='20231004', self.openTime='120000', self.closeTime='155959',self.symbol='BTCUSDT',self.open=27416.3, self.close=27441.9, self.high=27441.9, self.low=27335.8, self.vol=18070.915, self.amt=494972036.4288 
127.0.0.1 - - [04/Oct/2023 16:00:01] "POST / HTTP/1.1" 200 -
2023-10-04 16:00:01,556:INFO:s_rsrs:main.py:142:handleKline:2218689: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime  ...        vol           amt       pct
719  20231003   200000    235959  ...  90415.713  2.476740e+09 -0.007877
720  20231004   000000    035959  ...  47928.263  1.311400e+09 -0.002495
721  20231004   040000    075959  ...  48321.199  1.320651e+09  0.005436
722  20231004   080000    115959  ...  57219.623  1.564484e+09  0.000208
723  20231004   120000    155959  ...  18070.915  4.949720e+08  0.000883

[5 rows x 11 columns]
2023-10-04 16:00:02,322:INFO:s_rsrs:main.py:151:handleKline:2218689: df_s.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec  ...  index      beta    zscore  signal
719  20231003   200000    235959  1696348799  ...    719  1.102317  0.925811     1.0
720  20231004   000000    035959  1696363199  ...    720  1.197020  1.140802     1.0
721  20231004   040000    075959  1696377599  ...    721  1.186991  1.095715     1.0
722  20231004   080000    115959  1696391999  ...    722  1.151617  0.991374     1.0
723  20231004   120000    155959  1696406399  ...    723  1.082437  0.808364     1.0

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '43.732', 'enterprice': '28015.5', 'countrevence': '0', 'unrealprofit': '-25080.302', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '27442', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=1, self.sign=1


