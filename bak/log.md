# 20230817 08:26:01

## /root/FIL/strategy/amihud/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=373746.4768026, self.flagDict['side']='sell', self.tradeCount=2, self.count=27316
self.closeSec=1692231599, self.tradeDate='20230817', self.openTime='081500', self.closeTime='081959', self.symbol='BTCUSDT', self.open=28770.1, self.close=28720.9, self.high=28775.9, self.low=28720.8, self.vol=1156.887, self.amt=33256994.4174 
127.0.0.1 - - [17/Aug/2023 08:20:01] "POST / HTTP/1.1" 200 -
2023-08-17 08:20:04,716:INFO:amihud:main.py:172:handleKline:2219019: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5843  20230817   075500    075959  ...         0.0        0.0       0
5844  20230817   080000    080459  ...         0.0        0.0       0
5845  20230817   080500    080959  ...         0.0        0.0       0
5846  20230817   081000    081459  ...         0.0        0.0       0
5847  20230817   081500    081959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-08-17 08:20:04,719:INFO:amihud:main.py:175:handleKline:2219019: self.closeSec=1692231599, self.tradeDate='20230817', self.openTime='081500', self.closeTime='081959',self.symbol='BTCUSDT',self.open=28770.1, self.close=28720.9, self.high=28775.9, self.low=28720.8, self.vol=1156.887, self.amt=33256994.4174, ukdf['pct'].iloc[-1]=-0.00171 , ukdf['amount'].iloc[-1]=33256994.4174, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5847, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '13.926', 'enterprice': '26864.9', 'countrevence': '0', 'unrealprofit': '-25845.2634', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '28720.8', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1
127.0.0.1 - - [17/Aug/2023 08:25:00] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=373746.4768026, self.flagDict['side']='sell', self.tradeCount=2, self.count=27317
self.closeSec=1692231899, self.tradeDate='20230817', self.openTime='082000', self.closeTime='082459', self.symbol='BTCUSDT', self.open=28720.9, self.close=28711.1, self.high=28728.1, self.low=28680.3, self.vol=1881.491, self.amt=54008734.0054 
2023-08-17 08:25:00,753:INFO:amihud:main.py:172:handleKline:2219019: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5844  20230817   080000    080459  ...         0.0        0.0       0
5845  20230817   080500    080959  ...         0.0        0.0       0
5846  20230817   081000    081459  ...         0.0        0.0       0
5847  20230817   081500    081959  ...         0.0        0.0       0
5848  20230817   082000    082459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-08-17 08:25:00,753:INFO:amihud:main.py:175:handleKline:2219019: self.closeSec=1692231899, self.tradeDate='20230817', self.openTime='082000', self.closeTime='082459',self.symbol='BTCUSDT',self.open=28720.9, self.close=28711.1, self.high=28728.1, self.low=28680.3, self.vol=1881.491, self.amt=54008734.0054, ukdf['pct'].iloc[-1]=-0.000341 , ukdf['amount'].iloc[-1]=54008734.0054, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5848, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '13.926', 'enterprice': '26864.9', 'countrevence': '0', 'unrealprofit': '-25726.02426945342', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '28712.23766117', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1


## /root/FIL/strategy/factorcheck/log.txt ----- -----

127.0.0.1 - - [17/Aug/2023 08:00:00] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.714181719035411, self.count=27314 

self.closeSec=1692230399, self.tradeDate='20230817', self.openTime='075500', self.closeTime='075959', self.symbol='BTCUSDT', self.open=28720.9, self.close=28714.4, self.high=28741.9, self.low=28705.1 

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.714181719035411, self.count=27315 

self.closeSec=1692230699, self.tradeDate='20230817', self.openTime='080000', self.closeTime='080459', self.symbol='BTCUSDT', self.open=28714.4, self.close=28751.3, self.high=28759.6, self.low=28657.0 
127.0.0.1 - - [17/Aug/2023 08:05:00] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [17/Aug/2023 08:10:00] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.714181719035411, self.count=27316 

self.closeSec=1692230999, self.tradeDate='20230817', self.openTime='080500', self.closeTime='080959', self.symbol='BTCUSDT', self.open=28751.2, self.close=28759.9, self.high=28761.9, self.low=28721.7 
127.0.0.1 - - [17/Aug/2023 08:15:00] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.714181719035411, self.count=27317 

self.closeSec=1692231299, self.tradeDate='20230817', self.openTime='081000', self.closeTime='081459', self.symbol='BTCUSDT', self.open=28760.0, self.close=28770.1, self.high=28774.0, self.low=28737.1 

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.714181719035411, self.count=27318 

self.closeSec=1692231599, self.tradeDate='20230817', self.openTime='081500', self.closeTime='081959', self.symbol='BTCUSDT', self.open=28770.1, self.close=28720.9, self.high=28775.9, self.low=28720.8 
127.0.0.1 - - [17/Aug/2023 08:20:01] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.714181719035411, self.count=27319 

self.closeSec=1692231899, self.tradeDate='20230817', self.openTime='082000', self.closeTime='082459', self.symbol='BTCUSDT', self.open=28720.9, self.close=28711.1, self.high=28728.1, self.low=28680.3 
127.0.0.1 - - [17/Aug/2023 08:25:00] "POST / HTTP/1.1" 200 -


## /root/FIL/strategy/logic/log.txt ----- -----

2023-08-17 08:00:17,381:DEBUG:logic:main.py:463:getModel:2218526: df_s.iloc[-5:,:] :
          date closeTime     open  ...    alpha58   alpha67   alpha72
5769  20230817    052959  28961.8  ...  46.666667  0.405251  0.603259
5770  20230817    055959  28910.7  ...  46.666667  0.409993  0.611293
5771  20230817    062959  28924.0  ...  47.083333  0.419890  0.614618
5772  20230817    065959  28952.1  ...  46.666667  0.406111  0.625994
5773  20230817    072959  28896.3  ...  46.250000  0.392885  0.643332

[5 rows x 33 columns]
0.5481481481481482
acc is : 0.5481481481481482
2023-08-17 08:00:17,452:INFO:logic:main.py:468:getModel:2218526: df_pred.iloc[-5:,:] :
     pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
535     1  0.461644  0.538356       1  ...  0.979990  -1.0    0.0  0.995735
536     1  0.484099  0.515901       1  ...  0.979038  -1.0    0.0  0.996702
537     1  0.495088  0.504912       0  ...  0.980922  -1.0    0.0  0.994784
538     1  0.477026  0.522974       0  ...  0.982822  -1.0    0.0  0.992857
539     1  0.473566  0.526434       0  ...  0.987116  -1.0    0.0  0.988519

[5 rows x 10 columns]
2023-08-17 08:00:17,466:INFO:logic:main.py:478:getModel:2218526: df_panel.iloc[-5:,:] :
    pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
45     1  0.461932  0.538068       1  ...  0.979990  -1.0    0.0  0.996981
46     1  0.484176  0.515824       1  ...  0.979038  -1.0    0.0  0.997234
47     1  0.495343  0.504657       0  ...  0.980922  -1.0    0.0  0.995967
48     1  0.476995  0.523005       0  ...  0.982822  -1.0    0.0  0.993753
49     1  0.473566  0.526434       0  ...  0.987116  -1.0    0.0  0.988519

[5 rows x 10 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '24.207', 'enterprice': '29084.9', 'countrevence': '0', 'unrealprofit': '9044.89279108557', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '28711.25217949', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}


## /root/FIL/strategy/modifiedmom/log.txt ----- -----

127.0.0.1 - - [17/Aug/2023 07:30:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=13655 

self.closeSec=1692228599, self.tradeDate='20230817', self.openTime='072000', self.closeTime='072959', self.symbol='BTCUSDT', self.open='28871.8', self.close='28840.3'
127.0.0.1 - - [17/Aug/2023 07:40:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=13656 

self.closeSec=1692229199, self.tradeDate='20230817', self.openTime='073000', self.closeTime='073959', self.symbol='BTCUSDT', self.open='28840.3', self.close='28763.9'
127.0.0.1 - - [17/Aug/2023 07:50:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=13657 

self.closeSec=1692229799, self.tradeDate='20230817', self.openTime='074000', self.closeTime='074959', self.symbol='BTCUSDT', self.open='28767.2', self.close='28765.1'

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=13658 

self.closeSec=1692230399, self.tradeDate='20230817', self.openTime='075000', self.closeTime='075959', self.symbol='BTCUSDT', self.open='28765.1', self.close='28714.4'
127.0.0.1 - - [17/Aug/2023 08:00:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=13659 

self.closeSec=1692230999, self.tradeDate='20230817', self.openTime='080000', self.closeTime='080959', self.symbol='BTCUSDT', self.open='28714.4', self.close='28759.9'
127.0.0.1 - - [17/Aug/2023 08:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=13660 

self.closeSec=1692231599, self.tradeDate='20230817', self.openTime='081000', self.closeTime='081959', self.symbol='BTCUSDT', self.open='28760', self.close='28720.9'
127.0.0.1 - - [17/Aug/2023 08:20:03] "POST / HTTP/1.1" 200 -


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


--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=13658 

self.closeSec=1692228599, self.tradeDate='20230817', self.openTime='072000', self.closeTime='072959', self.symbol='BTCUSDT', self.open='28871.8', self.close='28840.3'
127.0.0.1 - - [17/Aug/2023 07:30:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=13659 

self.closeSec=1692229199, self.tradeDate='20230817', self.openTime='073000', self.closeTime='073959', self.symbol='BTCUSDT', self.open='28840.3', self.close='28763.9'
127.0.0.1 - - [17/Aug/2023 07:40:01] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [17/Aug/2023 07:50:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=13660 

self.closeSec=1692229799, self.tradeDate='20230817', self.openTime='074000', self.closeTime='074959', self.symbol='BTCUSDT', self.open='28767.2', self.close='28765.1'

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=13661 

self.closeSec=1692230399, self.tradeDate='20230817', self.openTime='075000', self.closeTime='075959', self.symbol='BTCUSDT', self.open='28765.1', self.close='28714.4'
127.0.0.1 - - [17/Aug/2023 08:00:01] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [17/Aug/2023 08:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=13662 

self.closeSec=1692230999, self.tradeDate='20230817', self.openTime='080000', self.closeTime='080959', self.symbol='BTCUSDT', self.open='28714.4', self.close='28759.9'

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=13663 

self.closeSec=1692231599, self.tradeDate='20230817', self.openTime='081000', self.closeTime='081959', self.symbol='BTCUSDT', self.open='28760', self.close='28720.9'
127.0.0.1 - - [17/Aug/2023 08:20:03] "POST / HTTP/1.1" 200 -


## /root/FIL/strategy/similarity/log.txt ----- -----


--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=13658 

self.closeSec=1692228599, self.tradeDate='20230817', self.openTime='072000', self.closeTime='072959', self.symbol='BTCUSDT', self.open='28871.8', self.close='28840.3'
127.0.0.1 - - [17/Aug/2023 07:30:01] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [17/Aug/2023 07:40:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=13659 

self.closeSec=1692229199, self.tradeDate='20230817', self.openTime='073000', self.closeTime='073959', self.symbol='BTCUSDT', self.open='28840.3', self.close='28763.9'
127.0.0.1 - - [17/Aug/2023 07:50:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=13660 

self.closeSec=1692229799, self.tradeDate='20230817', self.openTime='074000', self.closeTime='074959', self.symbol='BTCUSDT', self.open='28767.2', self.close='28765.1'

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=13661 

self.closeSec=1692230399, self.tradeDate='20230817', self.openTime='075000', self.closeTime='075959', self.symbol='BTCUSDT', self.open='28765.1', self.close='28714.4'
127.0.0.1 - - [17/Aug/2023 08:00:01] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [17/Aug/2023 08:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=13662 

self.closeSec=1692230999, self.tradeDate='20230817', self.openTime='080000', self.closeTime='080959', self.symbol='BTCUSDT', self.open='28714.4', self.close='28759.9'

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=13663 

self.closeSec=1692231599, self.tradeDate='20230817', self.openTime='081000', self.closeTime='081959', self.symbol='BTCUSDT', self.open='28760', self.close='28720.9'
127.0.0.1 - - [17/Aug/2023 08:20:03] "POST / HTTP/1.1" 200 -


## /root/FIL/strategy/sr_min/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=1, self.total=996015.990996, self.flagDict['side']='buy', self.tradeCount=1, self.count=27316
self.closeSec=1692231599, self.tradeDate='20230817', self.openTime='081500', self.closeTime='081959', self.symbol='BTCUSDT', self.open=28770.1, self.close=28720.9, self.high=28775.9, self.low=28720.8, self.vol=1156.887, self.amt=33256994.4174 
127.0.0.1 - - [17/Aug/2023 08:20:01] "POST / HTTP/1.1" 200 -
2023-08-17 08:20:04,709:INFO:sr_min:main.py:172:handleKline:2219263: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5843  20230817   075500    075959  ...         0.0        0.0       0
5844  20230817   080000    080459  ...         0.0        0.0       0
5845  20230817   080500    080959  ...         0.0        0.0       0
5846  20230817   081000    081459  ...         0.0        0.0       0
5847  20230817   081500    081959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-08-17 08:20:04,712:INFO:sr_min:main.py:175:handleKline:2219263: self.closeSec=1692231599, self.tradeDate='20230817', self.openTime='081500', self.closeTime='081959',self.symbol='BTCUSDT',self.open=28770.1, self.close=28720.9, self.high=28775.9, self.low=28720.8, self.vol=1156.887, self.amt=33256994.4174, ukdf['pct'].iloc[-1]=-0.00171 , ukdf['amount'].iloc[-1]=33256994.4174, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5847, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '37.141', 'enterprice': '26844', 'countrevence': '0', 'unrealprofit': '69706.2288', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '28720.8', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=1
--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=1, self.total=996015.990996, self.flagDict['side']='buy', self.tradeCount=1, self.count=27317
self.closeSec=1692231899, self.tradeDate='20230817', self.openTime='082000', self.closeTime='082459', self.symbol='BTCUSDT', self.open=28720.9, self.close=28711.1, self.high=28728.1, self.low=28680.3, self.vol=1881.491, self.amt=54008734.0054 
127.0.0.1 - - [17/Aug/2023 08:25:00] "POST / HTTP/1.1" 200 -
2023-08-17 08:25:00,762:INFO:sr_min:main.py:172:handleKline:2219263: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5844  20230817   080000    080459  ...         0.0        0.0       0
5845  20230817   080500    080959  ...         0.0        0.0       0
5846  20230817   081000    081459  ...         0.0        0.0       0
5847  20230817   081500    081959  ...         0.0        0.0       0
5848  20230817   082000    082459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-08-17 08:25:00,762:INFO:sr_min:main.py:175:handleKline:2219263: self.closeSec=1692231899, self.tradeDate='20230817', self.openTime='082000', self.closeTime='082459',self.symbol='BTCUSDT',self.open=28720.9, self.close=28711.1, self.high=28728.1, self.low=28680.3, self.vol=1881.491, self.amt=54008734.0054, ukdf['pct'].iloc[-1]=-0.000341 , ukdf['amount'].iloc[-1]=54008734.0054, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5848, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '37.141', 'enterprice': '26844', 'countrevence': '0', 'unrealprofit': '69388.21497351497', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '28712.23766117', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=1


## /root/FIL/strategy/s_rsrs/log.txt ----- -----

719  20230816   200000    235959  1692201599  ...    719  0.112624 -0.865000    -1.0
720  20230817   000000    035959  1692215999  ...    720  0.134955 -0.814892    -1.0

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '51.388', 'enterprice': '29432.6', 'countrevence': '0', 'unrealprofit': '16978.5952', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '29102.2', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-1, self.sign=-1
127.0.0.1 - - [17/Aug/2023 08:00:01] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='s_rsrs', self.symbol='BTCUSDT', interval='4h', intervalSec=14400, wid=25, thd=0.6, self.sign=-1, self.total=1510969.9663512, self.flagDict['side']='sell', self.tradeCount=20, self.count=569
self.closeSec=1692230399, self.tradeDate='20230817', self.openTime='040000', self.closeTime='075959', self.symbol='BTCUSDT', self.open=29105.4, self.close=28714.4, self.high=29132.4, self.low=28705.1, self.vol=81121.615, self.amt=2344016757.45944 
2023-08-17 08:00:01,604:INFO:s_rsrs:main.py:141:handleKline:2218689: self.closeSec=1692230399, self.tradeDate='20230817', self.openTime='040000', self.closeTime='075959',self.symbol='BTCUSDT',self.open=29105.4, self.close=28714.4, self.high=29132.4, self.low=28705.1, self.vol=81121.615, self.amt=2344016757.45944 
2023-08-17 08:00:01,617:INFO:s_rsrs:main.py:142:handleKline:2218689: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime  ...        vol           amt       pct
717  20230816   120000    155959  ...  25778.007  7.518555e+08 -0.001017
718  20230816   160000    195959  ...  10302.574  3.005547e+08 -0.001100
719  20230816   200000    235959  ...  52724.950  1.535489e+09 -0.000717
720  20230817   000000    035959  ...  75411.961  2.192964e+09 -0.000978
721  20230817   040000    075959  ...  81121.615  2.344017e+09 -0.013437

[5 rows x 11 columns]
2023-08-17 08:00:02,301:INFO:s_rsrs:main.py:151:handleKline:2218689: df_s.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec  ...  index      beta    zscore  signal
717  20230816   120000    155959  1692172799  ...    717  0.030721 -1.054429    -1.0
718  20230816   160000    195959  1692187199  ...    718  0.064153 -0.976557    -1.0
719  20230816   200000    235959  1692201599  ...    719  0.112624 -0.865000    -1.0
720  20230817   000000    035959  1692215999  ...    720  0.134955 -0.814892    -1.0
721  20230817   040000    075959  1692230399  ...    721  0.147228 -0.788914    -1.0

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '51.388', 'enterprice': '29432.6', 'countrevence': '0', 'unrealprofit': '36702.3594773952', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '28718.3795696', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-1, self.sign=-1


