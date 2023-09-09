# 20230909 08:26:01

## /root/FIL/strategy/amihud/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=373746.4768026, self.flagDict['side']='sell', self.tradeCount=2, self.count=33940
self.closeSec=1694218799, self.tradeDate='20230909', self.openTime='081500', self.closeTime='081959', self.symbol='BTCUSDT', self.open=25887.2, self.close=25883.8, self.high=25887.2, self.low=25877.2, self.vol=338.762, self.amt=8767684.8807 
127.0.0.1 - - [09/Sep/2023 08:20:02] "POST / HTTP/1.1" 200 -
2023-09-09 08:20:05,805:INFO:amihud:main.py:172:handleKline:2219019: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5855  20230909   075500    075959  ...         0.0        0.0       0
5856  20230909   080000    080459  ...         0.0        0.0       0
5857  20230909   080500    080959  ...         0.0        0.0       0
5858  20230909   081000    081459  ...         0.0        0.0       0
5859  20230909   081500    081959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-09-09 08:20:05,825:INFO:amihud:main.py:175:handleKline:2219019: self.closeSec=1694218799, self.tradeDate='20230909', self.openTime='081500', self.closeTime='081959',self.symbol='BTCUSDT',self.open=25887.2, self.close=25883.8, self.high=25887.2, self.low=25877.2, self.vol=338.762, self.amt=8767684.8807, ukdf['pct'].iloc[-1]=-0.000127 , ukdf['amount'].iloc[-1]=8767684.8807, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5859, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '13.926', 'enterprice': '26864.9', 'countrevence': '0', 'unrealprofit': '13664.1912', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '25883.7', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1
127.0.0.1 - - [09/Sep/2023 08:25:00] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=373746.4768026, self.flagDict['side']='sell', self.tradeCount=2, self.count=33941
self.closeSec=1694219099, self.tradeDate='20230909', self.openTime='082000', self.closeTime='082459', self.symbol='BTCUSDT', self.open=25883.7, self.close=25886.8, self.high=25886.9, self.low=25875.8, self.vol=156.053, self.amt=4038868.9366 
2023-09-09 08:25:00,784:INFO:amihud:main.py:172:handleKline:2219019: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5856  20230909   080000    080459  ...         0.0        0.0       0
5857  20230909   080500    080959  ...         0.0        0.0       0
5858  20230909   081000    081459  ...         0.0        0.0       0
5859  20230909   081500    081959  ...         0.0        0.0       0
5860  20230909   082000    082459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-09-09 08:25:00,784:INFO:amihud:main.py:175:handleKline:2219019: self.closeSec=1694219099, self.tradeDate='20230909', self.openTime='082000', self.closeTime='082459',self.symbol='BTCUSDT',self.open=25883.7, self.close=25886.8, self.high=25886.9, self.low=25875.8, self.vol=156.053, self.amt=4038868.9366, ukdf['pct'].iloc[-1]=0.000116 , ukdf['amount'].iloc[-1]=4038868.9366, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5860, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '13.926', 'enterprice': '26864.9', 'countrevence': '0', 'unrealprofit': '13619.628', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '25886.9', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1


## /root/FIL/strategy/factorcheck/log.txt ----- -----

127.0.0.1 - - [09/Sep/2023 08:00:00] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.714181719035411, self.count=33938 

self.closeSec=1694217599, self.tradeDate='20230909', self.openTime='075500', self.closeTime='075959', self.symbol='BTCUSDT', self.open=25899.9, self.close=25899.9, self.high=25899.9, self.low=25899.8 
127.0.0.1 - - [09/Sep/2023 08:05:00] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.714181719035411, self.count=33939 

self.closeSec=1694217899, self.tradeDate='20230909', self.openTime='080000', self.closeTime='080459', self.symbol='BTCUSDT', self.open=25899.9, self.close=25890.7, self.high=25900.1, self.low=25885.6 

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.714181719035411, self.count=33940 

self.closeSec=1694218199, self.tradeDate='20230909', self.openTime='080500', self.closeTime='080959', self.symbol='BTCUSDT', self.open=25890.6, self.close=25883.2, self.high=25890.7, self.low=25883.2 
127.0.0.1 - - [09/Sep/2023 08:10:00] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [09/Sep/2023 08:15:00] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.714181719035411, self.count=33941 

self.closeSec=1694218499, self.tradeDate='20230909', self.openTime='081000', self.closeTime='081459', self.symbol='BTCUSDT', self.open=25883.2, self.close=25887.1, self.high=25888.6, self.low=25883.0 

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.714181719035411, self.count=33942 

self.closeSec=1694218799, self.tradeDate='20230909', self.openTime='081500', self.closeTime='081959', self.symbol='BTCUSDT', self.open=25887.2, self.close=25883.8, self.high=25887.2, self.low=25877.2 
127.0.0.1 - - [09/Sep/2023 08:20:01] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [09/Sep/2023 08:25:00] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.714181719035411, self.count=33943 

self.closeSec=1694219099, self.tradeDate='20230909', self.openTime='082000', self.closeTime='082459', self.symbol='BTCUSDT', self.open=25883.7, self.close=25886.8, self.high=25886.9, self.low=25875.8 


## /root/FIL/strategy/logic/log.txt ----- -----

2023-09-09 08:00:16,902:DEBUG:logic:main.py:463:getModel:2218526: df_s.iloc[-5:,:] :
          date closeTime     open  ...    alpha58   alpha67   alpha72
5769  20230909    052959  25893.7  ...  50.000000  0.488260  0.646622
5770  20230909    055959  25865.6  ...  50.416667  0.491648  0.648062
5771  20230909    062959  25878.3  ...  50.833333  0.491675  0.649398
5772  20230909    065959  25878.5  ...  51.250000  0.494858  0.649602
5773  20230909    072959  25890.0  ...  51.250000  0.495904  0.649454

[5 rows x 33 columns]
0.5296296296296297
acc is : 0.5296296296296297
2023-09-09 08:00:16,968:INFO:logic:main.py:468:getModel:2218526: df_pred.iloc[-5:,:] :
     pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
535     1  0.497523  0.502477       1  ...  1.020970  -1.0    0.0  0.990402
536     0  0.504815  0.495185       1  ...  1.020966  -1.0    0.0  0.990405
537     1  0.496911  0.503089       1  ...  1.020504  -1.0    0.0  0.990853
538     0  0.503690  0.496310       1  ...  1.020354  -1.0    0.0  0.990999
539     1  0.496967  0.503033       1  ...  1.020118  -1.0    0.0  0.991228

[5 rows x 10 columns]
2023-09-09 08:00:16,979:INFO:logic:main.py:478:getModel:2218526: df_panel.iloc[-5:,:] :
    pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
45     1  0.498440  0.501560       1  ...  1.020970  -1.0    0.0  0.991836
46     0  0.504716  0.495284       1  ...  1.020966  -1.0    0.0  0.990523
47     1  0.497179  0.502821       1  ...  1.020504  -1.0    0.0  0.990720
48     0  0.503665  0.496335       1  ...  1.020354  -1.0    0.0  0.990203
49     1  0.496967  0.503033       1  ...  1.020118  -1.0    0.0  0.991228

[5 rows x 10 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '28.306', 'enterprice': '25771.5', 'countrevence': '0', 'unrealprofit': '-3658.95879451886', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '25900.76442431', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}


## /root/FIL/strategy/modifiedmom/log.txt ----- -----


--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=16967 

self.closeSec=1694215799, self.tradeDate='20230909', self.openTime='072000', self.closeTime='072959', self.symbol='BTCUSDT', self.open='25893.9', self.close='25893.9'
127.0.0.1 - - [09/Sep/2023 07:30:01] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [09/Sep/2023 07:40:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=16968 

self.closeSec=1694216399, self.tradeDate='20230909', self.openTime='073000', self.closeTime='073959', self.symbol='BTCUSDT', self.open='25893.8', self.close='25898.4'
127.0.0.1 - - [09/Sep/2023 07:50:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=16969 

self.closeSec=1694216999, self.tradeDate='20230909', self.openTime='074000', self.closeTime='074959', self.symbol='BTCUSDT', self.open='25898.4', self.close='25898.4'

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=16970 

self.closeSec=1694217599, self.tradeDate='20230909', self.openTime='075000', self.closeTime='075959', self.symbol='BTCUSDT', self.open='25898.4', self.close='25899.8'
127.0.0.1 - - [09/Sep/2023 08:00:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=16971 

self.closeSec=1694218199, self.tradeDate='20230909', self.openTime='080000', self.closeTime='080959', self.symbol='BTCUSDT', self.open='25899.9', self.close='25883.2'
127.0.0.1 - - [09/Sep/2023 08:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=16972 

self.closeSec=1694218799, self.tradeDate='20230909', self.openTime='081000', self.closeTime='081959', self.symbol='BTCUSDT', self.open='25883.2', self.close='25883.8'
127.0.0.1 - - [09/Sep/2023 08:20:04] "POST / HTTP/1.1" 200 -


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


--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=16970 

self.closeSec=1694215799, self.tradeDate='20230909', self.openTime='072000', self.closeTime='072959', self.symbol='BTCUSDT', self.open='25893.9', self.close='25893.9'
127.0.0.1 - - [09/Sep/2023 07:30:01] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [09/Sep/2023 07:40:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=16971 

self.closeSec=1694216399, self.tradeDate='20230909', self.openTime='073000', self.closeTime='073959', self.symbol='BTCUSDT', self.open='25893.8', self.close='25898.4'

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=16972 

self.closeSec=1694216999, self.tradeDate='20230909', self.openTime='074000', self.closeTime='074959', self.symbol='BTCUSDT', self.open='25898.4', self.close='25898.4'
127.0.0.1 - - [09/Sep/2023 07:50:01] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [09/Sep/2023 08:00:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=16973 

self.closeSec=1694217599, self.tradeDate='20230909', self.openTime='075000', self.closeTime='075959', self.symbol='BTCUSDT', self.open='25898.4', self.close='25899.8'
127.0.0.1 - - [09/Sep/2023 08:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=16974 

self.closeSec=1694218199, self.tradeDate='20230909', self.openTime='080000', self.closeTime='080959', self.symbol='BTCUSDT', self.open='25899.9', self.close='25883.2'

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=16975 

self.closeSec=1694218799, self.tradeDate='20230909', self.openTime='081000', self.closeTime='081959', self.symbol='BTCUSDT', self.open='25883.2', self.close='25883.8'
127.0.0.1 - - [09/Sep/2023 08:20:04] "POST / HTTP/1.1" 200 -


## /root/FIL/strategy/similarity/log.txt ----- -----


--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=16970 

self.closeSec=1694215799, self.tradeDate='20230909', self.openTime='072000', self.closeTime='072959', self.symbol='BTCUSDT', self.open='25893.9', self.close='25893.9'
127.0.0.1 - - [09/Sep/2023 07:30:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=16971 

self.closeSec=1694216399, self.tradeDate='20230909', self.openTime='073000', self.closeTime='073959', self.symbol='BTCUSDT', self.open='25893.8', self.close='25898.4'
127.0.0.1 - - [09/Sep/2023 07:40:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=16972 

self.closeSec=1694216999, self.tradeDate='20230909', self.openTime='074000', self.closeTime='074959', self.symbol='BTCUSDT', self.open='25898.4', self.close='25898.4'
127.0.0.1 - - [09/Sep/2023 07:50:01] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [09/Sep/2023 08:00:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=16973 

self.closeSec=1694217599, self.tradeDate='20230909', self.openTime='075000', self.closeTime='075959', self.symbol='BTCUSDT', self.open='25898.4', self.close='25899.8'
127.0.0.1 - - [09/Sep/2023 08:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=16974 

self.closeSec=1694218199, self.tradeDate='20230909', self.openTime='080000', self.closeTime='080959', self.symbol='BTCUSDT', self.open='25899.9', self.close='25883.2'

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=16975 

self.closeSec=1694218799, self.tradeDate='20230909', self.openTime='081000', self.closeTime='081959', self.symbol='BTCUSDT', self.open='25883.2', self.close='25883.8'
127.0.0.1 - - [09/Sep/2023 08:20:04] "POST / HTTP/1.1" 200 -


## /root/FIL/strategy/sr_min/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=1, self.total=996015.990996, self.flagDict['side']='buy', self.tradeCount=1, self.count=33940
self.closeSec=1694218799, self.tradeDate='20230909', self.openTime='081500', self.closeTime='081959', self.symbol='BTCUSDT', self.open=25887.2, self.close=25883.8, self.high=25887.2, self.low=25877.2, self.vol=338.762, self.amt=8767684.8807 
127.0.0.1 - - [09/Sep/2023 08:20:02] "POST / HTTP/1.1" 200 -
2023-09-09 08:20:05,804:INFO:sr_min:main.py:172:handleKline:2219263: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5855  20230909   075500    075959  ...         0.0        0.0       0
5856  20230909   080000    080459  ...         0.0        0.0       0
5857  20230909   080500    080959  ...         0.0        0.0       0
5858  20230909   081000    081459  ...         0.0        0.0       0
5859  20230909   081500    081959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-09-09 08:20:05,815:INFO:sr_min:main.py:175:handleKline:2219263: self.closeSec=1694218799, self.tradeDate='20230909', self.openTime='081500', self.closeTime='081959',self.symbol='BTCUSDT',self.open=25887.2, self.close=25883.8, self.high=25887.2, self.low=25877.2, self.vol=338.762, self.amt=8767684.8807, ukdf['pct'].iloc[-1]=-0.000127 , ukdf['amount'].iloc[-1]=8767684.8807, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5859, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '37.141', 'enterprice': '26844', 'countrevence': '0', 'unrealprofit': '-35666.5023', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '25883.7', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=1
127.0.0.1 - - [09/Sep/2023 08:25:00] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=1, self.total=996015.990996, self.flagDict['side']='buy', self.tradeCount=1, self.count=33941
self.closeSec=1694219099, self.tradeDate='20230909', self.openTime='082000', self.closeTime='082459', self.symbol='BTCUSDT', self.open=25883.7, self.close=25886.8, self.high=25886.9, self.low=25875.8, self.vol=156.053, self.amt=4038868.9366 
2023-09-09 08:25:00,792:INFO:sr_min:main.py:172:handleKline:2219263: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5856  20230909   080000    080459  ...         0.0        0.0       0
5857  20230909   080500    080959  ...         0.0        0.0       0
5858  20230909   081000    081459  ...         0.0        0.0       0
5859  20230909   081500    081959  ...         0.0        0.0       0
5860  20230909   082000    082459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-09-09 08:25:00,792:INFO:sr_min:main.py:175:handleKline:2219263: self.closeSec=1694219099, self.tradeDate='20230909', self.openTime='082000', self.closeTime='082459',self.symbol='BTCUSDT',self.open=25883.7, self.close=25886.8, self.high=25886.9, self.low=25875.8, self.vol=156.053, self.amt=4038868.9366, ukdf['pct'].iloc[-1]=0.000116 , ukdf['amount'].iloc[-1]=4038868.9366, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5860, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '37.141', 'enterprice': '26844', 'countrevence': '0', 'unrealprofit': '-35547.6511', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '25886.9', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=1


## /root/FIL/strategy/s_rsrs/log.txt ----- -----

719  20230908   200000    235959  1694188799  ...    719  0.206120 -0.544597     NaN
720  20230909   000000    035959  1694203199  ...    720  0.205611 -0.546965     NaN

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '57.177', 'enterprice': '25892.3', 'countrevence': '0', 'unrealprofit': '491.7222', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '25883.7', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-9223372036854775808, self.sign=-1
127.0.0.1 - - [09/Sep/2023 08:00:01] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='s_rsrs', self.symbol='BTCUSDT', interval='4h', intervalSec=14400, wid=25, thd=0.6, self.sign=-1, self.total=1478963.5930628998, self.flagDict['side']='sell', self.tradeCount=22, self.count=707
self.closeSec=1694217599, self.tradeDate='20230909', self.openTime='040000', self.closeTime='075959', self.symbol='BTCUSDT', self.open=25883.6, self.close=25899.9, self.high=25923.1, self.low=25834.5, self.vol=14213.77, self.amt=367883279.9003 
2023-09-09 08:00:01,580:INFO:s_rsrs:main.py:141:handleKline:2218689: self.closeSec=1694217599, self.tradeDate='20230909', self.openTime='040000', self.closeTime='075959',self.symbol='BTCUSDT',self.open=25883.6, self.close=25899.9, self.high=25923.1, self.low=25834.5, self.vol=14213.77, self.amt=367883279.9003 
2023-09-09 08:00:01,602:INFO:s_rsrs:main.py:142:handleKline:2218689: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime  ...        vol           amt       pct
717  20230908   120000    155959  ...  33675.232  8.847911e+08  0.000324
718  20230908   160000    195959  ...  92561.921  2.396823e+09 -0.015821
719  20230908   200000    235959  ...  36852.122  9.532067e+08  0.000035
720  20230909   000000    035959  ...  35345.758  9.117171e+08  0.002087
721  20230909   040000    075959  ...  14213.770  3.678833e+08  0.000626

[5 rows x 11 columns]
2023-09-09 08:00:02,314:INFO:s_rsrs:main.py:151:handleKline:2218689: df_s.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec  ...  index      beta    zscore  signal
717  20230908   120000    155959  1694159999  ...    717  0.269430 -0.364649     NaN
718  20230908   160000    195959  1694174399  ...    718  0.205650 -0.544857     NaN
719  20230908   200000    235959  1694188799  ...    719  0.206120 -0.544597     NaN
720  20230909   000000    035959  1694203199  ...    720  0.205611 -0.546965     NaN
721  20230909   040000    075959  1694217599  ...    721  0.196249 -0.573734     NaN

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '57.177', 'enterprice': '25892.3', 'countrevence': '0', 'unrealprofit': '-437.30163798822', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '25899.94820886', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-9223372036854775808, self.sign=-1


