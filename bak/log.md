# 20231011 08:26:01

## /root/FIL/strategy/amihud/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=373746.4768026, self.flagDict['side']='sell', self.tradeCount=2, self.count=43156
self.closeSec=1696983599, self.tradeDate='20231011', self.openTime='081500', self.closeTime='081959', self.symbol='BTCUSDT', self.open=27395.7, self.close=27383.3, self.high=27404.0, self.low=27383.2, self.vol=365.492, self.amt=10012129.5461 
127.0.0.1 - - [11/Oct/2023 08:20:10] "POST / HTTP/1.1" 200 -
2023-10-11 08:20:17,273:INFO:amihud:main.py:172:handleKline:2219019: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5855  20231011   075500    075959  ...         0.0        0.0       0
5856  20231011   080000    080459  ...         0.0        0.0       0
5857  20231011   080500    080959  ...         0.0        0.0       0
5858  20231011   081000    081459  ...         0.0        0.0       0
5859  20231011   081500    081959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-10-11 08:20:17,291:INFO:amihud:main.py:175:handleKline:2219019: self.closeSec=1696983599, self.tradeDate='20231011', self.openTime='081500', self.closeTime='081959',self.symbol='BTCUSDT',self.open=27395.7, self.close=27383.3, self.high=27404.0, self.low=27383.2, self.vol=365.492, self.amt=10012129.5461, ukdf['pct'].iloc[-1]=-0.000453 , ukdf['amount'].iloc[-1]=10012129.5461, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5859, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '13.926', 'enterprice': '26864.9', 'countrevence': '0', 'unrealprofit': '-7207.1808869313', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '27382.43417255', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1
--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=373746.4768026, self.flagDict['side']='sell', self.tradeCount=2, self.count=43157
self.closeSec=1696983899, self.tradeDate='20231011', self.openTime='082000', self.closeTime='082459', self.symbol='BTCUSDT', self.open=27383.3, self.close=27406.3, self.high=27406.3, self.low=27380.2, self.vol=298.746, self.amt=8183174.5936 
127.0.0.1 - - [11/Oct/2023 08:25:00] "POST / HTTP/1.1" 200 -
2023-10-11 08:25:00,844:INFO:amihud:main.py:172:handleKline:2219019: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5856  20231011   080000    080459  ...         0.0        0.0       0
5857  20231011   080500    080959  ...         0.0        0.0       0
5858  20231011   081000    081459  ...         0.0        0.0       0
5859  20231011   081500    081959  ...         0.0        0.0       0
5860  20231011   082000    082459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-10-11 08:25:00,845:INFO:amihud:main.py:175:handleKline:2219019: self.closeSec=1696983899, self.tradeDate='20231011', self.openTime='082000', self.closeTime='082459',self.symbol='BTCUSDT',self.open=27383.3, self.close=27406.3, self.high=27406.3, self.low=27380.2, self.vol=298.746, self.amt=8183174.5936, ukdf['pct'].iloc[-1]=0.00084 , ukdf['amount'].iloc[-1]=8183174.5936, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5860, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '13.926', 'enterprice': '26864.9', 'countrevence': '0', 'unrealprofit': '-7539.5364', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '27406.3', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1


## /root/FIL/strategy/factorcheck/log.txt ----- -----

127.0.0.1 - - [11/Oct/2023 08:00:00] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.714181719035411, self.count=43154 

self.closeSec=1696982399, self.tradeDate='20231011', self.openTime='075500', self.closeTime='075959', self.symbol='BTCUSDT', self.open=27378.5, self.close=27381.3, self.high=27381.3, self.low=27375.4 
127.0.0.1 - - [11/Oct/2023 08:05:00] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.714181719035411, self.count=43155 

self.closeSec=1696982699, self.tradeDate='20231011', self.openTime='080000', self.closeTime='080459', self.symbol='BTCUSDT', self.open=27381.3, self.close=27380.1, self.high=27398.9, self.low=27375.4 

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.714181719035411, self.count=43156 

self.closeSec=1696982999, self.tradeDate='20231011', self.openTime='080500', self.closeTime='080959', self.symbol='BTCUSDT', self.open=27380.1, self.close=27390.8, self.high=27394.3, self.low=27375.9 
127.0.0.1 - - [11/Oct/2023 08:10:00] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.714181719035411, self.count=43157 

self.closeSec=1696983299, self.tradeDate='20231011', self.openTime='081000', self.closeTime='081459', self.symbol='BTCUSDT', self.open=27390.9, self.close=27395.7, self.high=27398.9, self.low=27387.9 
127.0.0.1 - - [11/Oct/2023 08:15:00] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.714181719035411, self.count=43158 

self.closeSec=1696983599, self.tradeDate='20231011', self.openTime='081500', self.closeTime='081959', self.symbol='BTCUSDT', self.open=27395.7, self.close=27383.3, self.high=27404.0, self.low=27383.2 
127.0.0.1 - - [11/Oct/2023 08:20:10] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [11/Oct/2023 08:25:00] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.714181719035411, self.count=43159 

self.closeSec=1696983899, self.tradeDate='20231011', self.openTime='082000', self.closeTime='082459', self.symbol='BTCUSDT', self.open=27383.3, self.close=27406.3, self.high=27406.3, self.low=27380.2 


## /root/FIL/strategy/logic/log.txt ----- -----

2023-10-11 08:00:17,308:DEBUG:logic:main.py:463:getModel:2218526: df_s.iloc[-5:,:] :
          date closeTime     open  ...    alpha58   alpha67   alpha72
5769  20231011    052959  27391.1  ...  50.000000  0.462331  0.656139
5770  20231011    055959  27453.8  ...  50.000000  0.451254  0.659107
5771  20231011    062959  27414.6  ...  50.416667  0.452930  0.661070
5772  20231011    065959  27420.0  ...  50.833333  0.457594  0.660676
5773  20231011    072959  27434.9  ...  50.833333  0.455493  0.661489

[5 rows x 33 columns]
0.5703703703703704
acc is : 0.5703703703703704
2023-10-11 08:00:17,367:INFO:logic:main.py:468:getModel:2218526: df_pred.iloc[-5:,:] :
     pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
535     0  0.521655  0.478345       0  ...  1.008644  -1.0    0.0  1.021960
536     1  0.486992  0.513008       1  ...  1.008445  -1.0    0.0  1.022162
537     1  0.499284  0.500716       1  ...  1.007897  -1.0    0.0  1.022717
538     0  0.503685  0.496315       0  ...  1.008187  -1.0    0.0  1.022423
539     1  0.495932  0.504068       0  ...  1.009867  -1.0    0.0  1.020719

[5 rows x 10 columns]
2023-10-11 08:00:17,378:INFO:logic:main.py:478:getModel:2218526: df_panel.iloc[-5:,:] :
    pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
45     0  0.521222  0.478778       0  ...  1.008644  -1.0    0.0  1.020086
46     1  0.486826  0.513174       1  ...  1.008445  -1.0    0.0  1.021134
47     1  0.498876  0.501124       1  ...  1.007897  -1.0    0.0  1.021236
48     0  0.503476  0.496524       0  ...  1.008187  -1.0    0.0  1.022152
49     1  0.495932  0.504068       0  ...  1.009867  -1.0    0.0  1.020719

[5 rows x 10 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '23.618', 'enterprice': '27520.8', 'countrevence': '0', 'unrealprofit': '3393.9066', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '27377.1', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}


## /root/FIL/strategy/modifiedmom/log.txt ----- -----


--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=21575 

self.closeSec=1696980599, self.tradeDate='20231011', self.openTime='072000', self.closeTime='072959', self.symbol='BTCUSDT', self.open='27434.7', self.close='27427'
127.0.0.1 - - [11/Oct/2023 07:30:01] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [11/Oct/2023 07:40:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=21576 

self.closeSec=1696981199, self.tradeDate='20231011', self.openTime='073000', self.closeTime='073959', self.symbol='BTCUSDT', self.open='27427', self.close='27417.5'

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=21577 

self.closeSec=1696981799, self.tradeDate='20231011', self.openTime='074000', self.closeTime='074959', self.symbol='BTCUSDT', self.open='27417.7', self.close='27400'
127.0.0.1 - - [11/Oct/2023 07:50:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=21578 

self.closeSec=1696982399, self.tradeDate='20231011', self.openTime='075000', self.closeTime='075959', self.symbol='BTCUSDT', self.open='27399.9', self.close='27381.3'
127.0.0.1 - - [11/Oct/2023 08:00:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=21579 

self.closeSec=1696982999, self.tradeDate='20231011', self.openTime='080000', self.closeTime='080959', self.symbol='BTCUSDT', self.open='27381.3', self.close='27390.8'
127.0.0.1 - - [11/Oct/2023 08:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=21580 

self.closeSec=1696983599, self.tradeDate='20231011', self.openTime='081000', self.closeTime='081959', self.symbol='BTCUSDT', self.open='27390.9', self.close='27383.3'
127.0.0.1 - - [11/Oct/2023 08:20:13] "POST / HTTP/1.1" 200 -


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


--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=21578 

self.closeSec=1696980599, self.tradeDate='20231011', self.openTime='072000', self.closeTime='072959', self.symbol='BTCUSDT', self.open='27434.7', self.close='27427'
127.0.0.1 - - [11/Oct/2023 07:30:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=21579 

self.closeSec=1696981199, self.tradeDate='20231011', self.openTime='073000', self.closeTime='073959', self.symbol='BTCUSDT', self.open='27427', self.close='27417.5'
127.0.0.1 - - [11/Oct/2023 07:40:01] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [11/Oct/2023 07:50:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=21580 

self.closeSec=1696981799, self.tradeDate='20231011', self.openTime='074000', self.closeTime='074959', self.symbol='BTCUSDT', self.open='27417.7', self.close='27400'

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=21581 

self.closeSec=1696982399, self.tradeDate='20231011', self.openTime='075000', self.closeTime='075959', self.symbol='BTCUSDT', self.open='27399.9', self.close='27381.3'
127.0.0.1 - - [11/Oct/2023 08:00:01] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [11/Oct/2023 08:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=21582 

self.closeSec=1696982999, self.tradeDate='20231011', self.openTime='080000', self.closeTime='080959', self.symbol='BTCUSDT', self.open='27381.3', self.close='27390.8'

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=21583 

self.closeSec=1696983599, self.tradeDate='20231011', self.openTime='081000', self.closeTime='081959', self.symbol='BTCUSDT', self.open='27390.9', self.close='27383.3'
127.0.0.1 - - [11/Oct/2023 08:20:12] "POST / HTTP/1.1" 200 -


## /root/FIL/strategy/similarity/log.txt ----- -----


--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=21578 

self.closeSec=1696980599, self.tradeDate='20231011', self.openTime='072000', self.closeTime='072959', self.symbol='BTCUSDT', self.open='27434.7', self.close='27427'
127.0.0.1 - - [11/Oct/2023 07:30:01] "POST / HTTP/1.1" 200 -

--handleKline--:  127.0.0.1 - - [11/Oct/2023 07:40:01] "POST / HTTP/1.1" 200 -
self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=21579 

self.closeSec=1696981199, self.tradeDate='20231011', self.openTime='073000', self.closeTime='073959', self.symbol='BTCUSDT', self.open='27427', self.close='27417.5'

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=21580 127.0.0.1 - - [11/Oct/2023 07:50:01] "POST / HTTP/1.1" 200 -


self.closeSec=1696981799, self.tradeDate='20231011', self.openTime='074000', self.closeTime='074959', self.symbol='BTCUSDT', self.open='27417.7', self.close='27400'
127.0.0.1 - - [11/Oct/2023 08:00:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=21581 

self.closeSec=1696982399, self.tradeDate='20231011', self.openTime='075000', self.closeTime='075959', self.symbol='BTCUSDT', self.open='27399.9', self.close='27381.3'
127.0.0.1 - - [11/Oct/2023 08:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=21582 

self.closeSec=1696982999, self.tradeDate='20231011', self.openTime='080000', self.closeTime='080959', self.symbol='BTCUSDT', self.open='27381.3', self.close='27390.8'

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=21583 

self.closeSec=1696983599, self.tradeDate='20231011', self.openTime='081000', self.closeTime='081959', self.symbol='BTCUSDT', self.open='27390.9', self.close='27383.3'
127.0.0.1 - - [11/Oct/2023 08:20:12] "POST / HTTP/1.1" 200 -


## /root/FIL/strategy/sr_min/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=1, self.total=996015.990996, self.flagDict['side']='buy', self.tradeCount=1, self.count=43156
self.closeSec=1696983599, self.tradeDate='20231011', self.openTime='081500', self.closeTime='081959', self.symbol='BTCUSDT', self.open=27395.7, self.close=27383.3, self.high=27404.0, self.low=27383.2, self.vol=365.492, self.amt=10012129.5461 
127.0.0.1 - - [11/Oct/2023 08:20:10] "POST / HTTP/1.1" 200 -
2023-10-11 08:20:17,273:INFO:sr_min:main.py:172:handleKline:2219263: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5855  20231011   075500    075959  ...         0.0        0.0       0
5856  20231011   080000    080459  ...         0.0        0.0       0
5857  20231011   080500    080959  ...         0.0        0.0       0
5858  20231011   081000    081459  ...         0.0        0.0       0
5859  20231011   081500    081959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-10-11 08:20:17,293:INFO:sr_min:main.py:175:handleKline:2219263: self.closeSec=1696983599, self.tradeDate='20231011', self.openTime='081500', self.closeTime='081959',self.symbol='BTCUSDT',self.open=27395.7, self.close=27383.3, self.high=27404.0, self.low=27383.2, self.vol=365.492, self.amt=10012129.5461, ukdf['pct'].iloc[-1]=-0.000453 , ukdf['amount'].iloc[-1]=10012129.5461, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5859, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '37.141', 'enterprice': '26844', 'countrevence': '0', 'unrealprofit': '19998.15838376863', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '27382.43887843', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=1
--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=1, self.total=996015.990996, self.flagDict['side']='buy', self.tradeCount=1, self.count=43157
self.closeSec=1696983899, self.tradeDate='20231011', self.openTime='082000', self.closeTime='082459', self.symbol='BTCUSDT', self.open=27383.3, self.close=27406.3, self.high=27406.3, self.low=27380.2, self.vol=298.746, self.amt=8183174.5936 127.0.0.1 - - [11/Oct/2023 08:25:00] "POST / HTTP/1.1" 200 -

2023-10-11 08:25:00,847:INFO:sr_min:main.py:172:handleKline:2219263: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5856  20231011   080000    080459  ...         0.0        0.0       0
5857  20231011   080500    080959  ...         0.0        0.0       0
5858  20231011   081000    081459  ...         0.0        0.0       0
5859  20231011   081500    081959  ...         0.0        0.0       0
5860  20231011   082000    082459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-10-11 08:25:00,848:INFO:sr_min:main.py:175:handleKline:2219263: self.closeSec=1696983899, self.tradeDate='20231011', self.openTime='082000', self.closeTime='082459',self.symbol='BTCUSDT',self.open=27383.3, self.close=27406.3, self.high=27406.3, self.low=27380.2, self.vol=298.746, self.amt=8183174.5936, ukdf['pct'].iloc[-1]=0.00084 , ukdf['amount'].iloc[-1]=8183174.5936, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5860, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '37.141', 'enterprice': '26844', 'countrevence': '0', 'unrealprofit': '20884.3843', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '27406.3', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=1


## /root/FIL/strategy/s_rsrs/log.txt ----- -----

719  20231010   200000    235959  1696953599  ...    719  0.099732 -1.052387    -1.0
720  20231011   000000    035959  1696967999  ...    720  0.381725 -0.295344     NaN

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '43.597', 'enterprice': '27944.4', 'countrevence': '0', 'unrealprofit': '24187.6156', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '27389.6', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-9223372036854775808, self.sign=-1
--handleKline--:  version='2.0.0', self.name='s_rsrs', self.symbol='BTCUSDT', interval='4h', intervalSec=14400, wid=25, thd=0.6, self.sign=-1, self.total=1217073.7147932001, self.flagDict['side']='sell', self.tradeCount=32, self.count=899
self.closeSec=1696982399, self.tradeDate='20231011', self.openTime='040000', self.closeTime='075959', self.symbol='BTCUSDT', self.open=27386.3, self.close=27381.3, self.high=27458.2, self.low=27308.1, self.vol=16419.75, self.amt=449889416.3998 
127.0.0.1 - - [11/Oct/2023 08:00:01] "POST / HTTP/1.1" 200 -
2023-10-11 08:00:01,549:INFO:s_rsrs:main.py:141:handleKline:2218689: self.closeSec=1696982399, self.tradeDate='20231011', self.openTime='040000', self.closeTime='075959',self.symbol='BTCUSDT',self.open=27386.3, self.close=27381.3, self.high=27458.2, self.low=27308.1, self.vol=16419.75, self.amt=449889416.3998 
2023-10-11 08:00:01,562:INFO:s_rsrs:main.py:142:handleKline:2218689: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime  ...        vol           amt       pct
717  20231010   120000    155959  ...  18658.552  5.153902e+08  0.000478
718  20231010   160000    195959  ...  30888.027  8.528133e+08 -0.004950
719  20231010   200000    235959  ...  94338.609  2.588667e+09 -0.003728
720  20231011   000000    035959  ...  54866.291  1.502123e+09 -0.000332
721  20231011   040000    075959  ...  16419.750  4.498894e+08 -0.000186

[5 rows x 11 columns]
2023-10-11 08:00:02,249:INFO:s_rsrs:main.py:151:handleKline:2218689: df_s.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec  ...  index      beta    zscore  signal
717  20231010   120000    155959  1696924799  ...    717  0.086998 -1.102367    -1.0
718  20231010   160000    195959  1696939199  ...    718  0.079068 -1.115294    -1.0
719  20231010   200000    235959  1696953599  ...    719  0.099732 -1.052387    -1.0
720  20231011   000000    035959  1696967999  ...    720  0.381725 -0.295344     NaN
721  20231011   040000    075959  1696982399  ...    721  0.438110 -0.148669     NaN

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '43.597', 'enterprice': '27944.4', 'countrevence': '0', 'unrealprofit': '24553.8304', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '27381.2', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-9223372036854775808, self.sign=-1


