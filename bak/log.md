# 20230916 08:26:02

## /root/FIL/strategy/amihud/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=373746.4768026, self.flagDict['side']='sell', self.tradeCount=2, self.count=35956
self.closeSec=1694823599, self.tradeDate='20230916', self.openTime='081500', self.closeTime='081959', self.symbol='BTCUSDT', self.open=26598.1, self.close=26645.4, self.high=26647.5, self.low=26580.4, self.vol=1346.659, self.amt=35842798.393 
127.0.0.1 - - [16/Sep/2023 08:20:02] "POST / HTTP/1.1" 200 -
2023-09-16 08:20:06,204:INFO:amihud:main.py:172:handleKline:2219019: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5855  20230916   075500    075959  ...         0.0        0.0       0
5856  20230916   080000    080459  ...         0.0        0.0       0
5857  20230916   080500    080959  ...         0.0        0.0       0
5858  20230916   081000    081459  ...         0.0        0.0       0
5859  20230916   081500    081959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-09-16 08:20:06,211:INFO:amihud:main.py:175:handleKline:2219019: self.closeSec=1694823599, self.tradeDate='20230916', self.openTime='081500', self.closeTime='081959',self.symbol='BTCUSDT',self.open=26598.1, self.close=26645.4, self.high=26647.5, self.low=26580.4, self.vol=1346.659, self.amt=35842798.393, ukdf['pct'].iloc[-1]=0.001703 , ukdf['amount'].iloc[-1]=35842798.393, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5859, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '13.926', 'enterprice': '26864.9', 'countrevence': '0', 'unrealprofit': '3055.63422265596', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '26645.48062454', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1
127.0.0.1 - - [16/Sep/2023 08:25:00] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=373746.4768026, self.flagDict['side']='sell', self.tradeCount=2, self.count=35957
self.closeSec=1694823899, self.tradeDate='20230916', self.openTime='082000', self.closeTime='082459', self.symbol='BTCUSDT', self.open=26642.4, self.close=26617.1, self.high=26656.4, self.low=26615.0, self.vol=1000.181, self.amt=26640998.101 
2023-09-16 08:25:00,794:INFO:amihud:main.py:172:handleKline:2219019: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5856  20230916   080000    080459  ...         0.0        0.0       0
5857  20230916   080500    080959  ...         0.0        0.0       0
5858  20230916   081000    081459  ...         0.0        0.0       0
5859  20230916   081500    081959  ...         0.0        0.0       0
5860  20230916   082000    082459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-09-16 08:25:00,794:INFO:amihud:main.py:175:handleKline:2219019: self.closeSec=1694823899, self.tradeDate='20230916', self.openTime='082000', self.closeTime='082459',self.symbol='BTCUSDT',self.open=26642.4, self.close=26617.1, self.high=26656.4, self.low=26615.0, self.vol=1000.181, self.amt=26640998.101, ukdf['pct'].iloc[-1]=-0.001062 , ukdf['amount'].iloc[-1]=26640998.101, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5860, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '13.926', 'enterprice': '26864.9', 'countrevence': '0', 'unrealprofit': '3447.80678260986', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '26617.31944689', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1


## /root/FIL/strategy/factorcheck/log.txt ----- -----


--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.714181719035411, self.count=35954 

self.closeSec=1694822399, self.tradeDate='20230916', self.openTime='075500', self.closeTime='075959', self.symbol='BTCUSDT', self.open=26617.1, self.close=26590.8, self.high=26623.8, self.low=26580.0 
127.0.0.1 - - [16/Sep/2023 08:00:00] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.714181719035411, self.count=35955 

self.closeSec=1694822699, self.tradeDate='20230916', self.openTime='080000', self.closeTime='080459', self.symbol='BTCUSDT', self.open=26591.1, self.close=26561.0, self.high=26613.8, self.low=26559.2 
127.0.0.1 - - [16/Sep/2023 08:05:00] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.714181719035411, self.count=35956 

self.closeSec=1694822999, self.tradeDate='20230916', self.openTime='080500', self.closeTime='080959', self.symbol='BTCUSDT', self.open=26560.9, self.close=26618.4, self.high=26634.1, self.low=26558.3 
127.0.0.1 - - [16/Sep/2023 08:10:00] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.714181719035411, self.count=35957 

self.closeSec=1694823299, self.tradeDate='20230916', self.openTime='081000', self.closeTime='081459', self.symbol='BTCUSDT', self.open=26618.3, self.close=26600.1, self.high=26623.1, self.low=26600.0 
127.0.0.1 - - [16/Sep/2023 08:15:00] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.714181719035411, self.count=35958 

self.closeSec=1694823599, self.tradeDate='20230916', self.openTime='081500', self.closeTime='081959', self.symbol='BTCUSDT', self.open=26598.1, self.close=26645.4, self.high=26647.5, self.low=26580.4 
127.0.0.1 - - [16/Sep/2023 08:20:02] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [16/Sep/2023 08:25:00] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.714181719035411, self.count=35959 

self.closeSec=1694823899, self.tradeDate='20230916', self.openTime='082000', self.closeTime='082459', self.symbol='BTCUSDT', self.open=26642.4, self.close=26617.1, self.high=26656.4, self.low=26615.0 


## /root/FIL/strategy/logic/log.txt ----- -----

2023-09-16 08:00:18,133:DEBUG:logic:main.py:463:getModel:2218526: df_s.iloc[-5:,:] :
          date closeTime     open  ...    alpha58   alpha67   alpha72
5769  20230916    052959  26403.1  ...  50.833333  0.514219  0.671104
5770  20230916    055959  26442.2  ...  50.833333  0.517437  0.658714
5771  20230916    062959  26456.2  ...  50.833333  0.524732  0.642778
5772  20230916    065959  26488.0  ...  51.250000  0.580495  0.609045
5773  20230916    072959  26764.2  ...  51.250000  0.555494  0.590976

[5 rows x 33 columns]
0.5537037037037037
acc is : 0.5537037037037037
2023-09-16 08:00:18,201:INFO:logic:main.py:468:getModel:2218526: df_pred.iloc[-5:,:] :
     pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
535     0  0.509883  0.490117       1  ...  0.940978   1.0    0.0  1.021692
536     1  0.498886  0.501114       1  ...  0.942109   1.0    0.0  1.022920
537     0  0.507134  0.492866       1  ...  0.951855   1.0    0.0  1.033501
538     0  0.580547  0.419453       0  ...  0.948191   1.0    0.0  1.029524
539     1  0.486230  0.513770       0  ...  0.945766   1.0    0.0  1.026890

[5 rows x 10 columns]
2023-09-16 08:00:18,213:INFO:logic:main.py:478:getModel:2218526: df_panel.iloc[-5:,:] :
    pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
45     0  0.510093  0.489907       1  ...  0.940978   1.0    0.0  1.025279
46     1  0.498591  0.501409       1  ...  0.942109   1.0    0.0  1.025375
47     0  0.506899  0.493101       1  ...  0.951855   1.0    0.0  1.035196
48     0  0.580345  0.419655       0  ...  0.948191   1.0    0.0  1.030347
49     1  0.486230  0.513770       0  ...  0.945766   1.0    0.0  1.026890

[5 rows x 10 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '26.865', 'enterprice': '26592', 'countrevence': '0', 'unrealprofit': '300.888', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '26603.2', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}


## /root/FIL/strategy/modifiedmom/log.txt ----- -----


--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=17975 

self.closeSec=1694820599, self.tradeDate='20230916', self.openTime='072000', self.closeTime='072959', self.symbol='BTCUSDT', self.open='26684', self.close='26659'
127.0.0.1 - - [16/Sep/2023 07:30:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=17976 

self.closeSec=1694821199, self.tradeDate='20230916', self.openTime='073000', self.closeTime='073959', self.symbol='BTCUSDT', self.open='26659', self.close='26700'
127.0.0.1 - - [16/Sep/2023 07:40:01] "POST / HTTP/1.1" 200 -

--handleKline--: 127.0.0.1 - - [16/Sep/2023 07:50:01] "POST / HTTP/1.1" 200 -
 self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=17977 

self.closeSec=1694821799, self.tradeDate='20230916', self.openTime='074000', self.closeTime='074959', self.symbol='BTCUSDT', self.open='26699.9', self.close='26625.3'
127.0.0.1 - - [16/Sep/2023 08:00:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=17978 

self.closeSec=1694822399, self.tradeDate='20230916', self.openTime='075000', self.closeTime='075959', self.symbol='BTCUSDT', self.open='26626', self.close='26591.1'
127.0.0.1 - - [16/Sep/2023 08:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=17979 

self.closeSec=1694822999, self.tradeDate='20230916', self.openTime='080000', self.closeTime='080959', self.symbol='BTCUSDT', self.open='26591.1', self.close='26618.3'

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=17980 

self.closeSec=1694823599, self.tradeDate='20230916', self.openTime='081000', self.closeTime='081959', self.symbol='BTCUSDT', self.open='26618.3', self.close='26645.4'
127.0.0.1 - - [16/Sep/2023 08:20:04] "POST / HTTP/1.1" 200 -


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


--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=17978 

self.closeSec=1694820599, self.tradeDate='20230916', self.openTime='072000', self.closeTime='072959', self.symbol='BTCUSDT', self.open='26684', self.close='26659'
127.0.0.1 - - [16/Sep/2023 07:30:01] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [16/Sep/2023 07:40:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=17979 

self.closeSec=1694821199, self.tradeDate='20230916', self.openTime='073000', self.closeTime='073959', self.symbol='BTCUSDT', self.open='26659', self.close='26700'

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=17980 

self.closeSec=1694821799, self.tradeDate='20230916', self.openTime='074000', self.closeTime='074959', self.symbol='BTCUSDT', self.open='26699.9', self.close='26625.3'
127.0.0.1 - - [16/Sep/2023 07:50:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=17981 

self.closeSec=1694822399, self.tradeDate='20230916', self.openTime='075000', self.closeTime='075959', self.symbol='BTCUSDT', self.open='26626', self.close='26591.1'
127.0.0.1 - - [16/Sep/2023 08:00:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=17982 

self.closeSec=1694822999, self.tradeDate='20230916', self.openTime='080000', self.closeTime='080959', self.symbol='BTCUSDT', self.open='26591.1', self.close='26618.3'
127.0.0.1 - - [16/Sep/2023 08:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=17983 

self.closeSec=1694823599, self.tradeDate='20230916', self.openTime='081000', self.closeTime='081959', self.symbol='BTCUSDT', self.open='26618.3', self.close='26645.4'
127.0.0.1 - - [16/Sep/2023 08:20:04] "POST / HTTP/1.1" 200 -


## /root/FIL/strategy/similarity/log.txt ----- -----


--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=17978 

self.closeSec=1694820599, self.tradeDate='20230916', self.openTime='072000', self.closeTime='072959', self.symbol='BTCUSDT', self.open='26684', self.close='26659'
127.0.0.1 - - [16/Sep/2023 07:30:01] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [16/Sep/2023 07:40:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=17979 

self.closeSec=1694821199, self.tradeDate='20230916', self.openTime='073000', self.closeTime='073959', self.symbol='BTCUSDT', self.open='26659', self.close='26700'
127.0.0.1 - - [16/Sep/2023 07:50:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=17980 

self.closeSec=1694821799, self.tradeDate='20230916', self.openTime='074000', self.closeTime='074959', self.symbol='BTCUSDT', self.open='26699.9', self.close='26625.3'

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=17981 

self.closeSec=1694822399, self.tradeDate='20230916', self.openTime='075000', self.closeTime='075959', self.symbol='BTCUSDT', self.open='26626', self.close='26591.1'
127.0.0.1 - - [16/Sep/2023 08:00:01] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [16/Sep/2023 08:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=17982 

self.closeSec=1694822999, self.tradeDate='20230916', self.openTime='080000', self.closeTime='080959', self.symbol='BTCUSDT', self.open='26591.1', self.close='26618.3'

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=17983 

self.closeSec=1694823599, self.tradeDate='20230916', self.openTime='081000', self.closeTime='081959', self.symbol='BTCUSDT', self.open='26618.3', self.close='26645.4'
127.0.0.1 - - [16/Sep/2023 08:20:04] "POST / HTTP/1.1" 200 -


## /root/FIL/strategy/sr_min/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=1, self.total=996015.990996, self.flagDict['side']='buy', self.tradeCount=1, self.count=35956
self.closeSec=1694823599, self.tradeDate='20230916', self.openTime='081500', self.closeTime='081959', self.symbol='BTCUSDT', self.open=26598.1, self.close=26645.4, self.high=26647.5, self.low=26580.4, self.vol=1346.659, self.amt=35842798.393 
127.0.0.1 - - [16/Sep/2023 08:20:02] "POST / HTTP/1.1" 200 -
2023-09-16 08:20:06,205:INFO:sr_min:main.py:172:handleKline:2219263: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5855  20230916   075500    075959  ...         0.0        0.0       0
5856  20230916   080000    080459  ...         0.0        0.0       0
5857  20230916   080500    080959  ...         0.0        0.0       0
5858  20230916   081000    081459  ...         0.0        0.0       0
5859  20230916   081500    081959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-09-16 08:20:06,211:INFO:sr_min:main.py:175:handleKline:2219263: self.closeSec=1694823599, self.tradeDate='20230916', self.openTime='081500', self.closeTime='081959',self.symbol='BTCUSDT',self.open=26598.1, self.close=26645.4, self.high=26647.5, self.low=26580.4, self.vol=1346.659, self.amt=35842798.393, ukdf['pct'].iloc[-1]=0.001703 , ukdf['amount'].iloc[-1]=35842798.393, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5859, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '37.141', 'enterprice': '26844', 'countrevence': '0', 'unrealprofit': '-7373.20812395986', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '26645.48062454', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=1
--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=1, self.total=996015.990996, self.flagDict['side']='buy', self.tradeCount=1, self.count=35957
self.closeSec=1694823899, self.tradeDate='20230916', self.openTime='082000', self.closeTime='082459', self.symbol='BTCUSDT', self.open=26642.4, self.close=26617.1, self.high=26656.4, self.low=26615.0, self.vol=1000.181, self.amt=26640998.101 
127.0.0.1 - - [16/Sep/2023 08:25:00] "POST / HTTP/1.1" 200 -
2023-09-16 08:25:00,792:INFO:sr_min:main.py:172:handleKline:2219263: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5856  20230916   080000    080459  ...         0.0        0.0       0
5857  20230916   080500    080959  ...         0.0        0.0       0
5858  20230916   081000    081459  ...         0.0        0.0       0
5859  20230916   081500    081959  ...         0.0        0.0       0
5860  20230916   082000    082459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-09-16 08:25:00,793:INFO:sr_min:main.py:175:handleKline:2219263: self.closeSec=1694823899, self.tradeDate='20230916', self.openTime='082000', self.closeTime='082459',self.symbol='BTCUSDT',self.open=26642.4, self.close=26617.1, self.high=26656.4, self.low=26615.0, self.vol=1000.181, self.amt=26640998.101, ukdf['pct'].iloc[-1]=-0.001062 , ukdf['amount'].iloc[-1]=26640998.101, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5860, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '37.141', 'enterprice': '26844', 'countrevence': '0', 'unrealprofit': '-8419.14242305851', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '26617.31944689', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=1


## /root/FIL/strategy/s_rsrs/log.txt ----- -----

719  20230915   200000    235959  1694793599  ...    719  0.548969  0.756718     1.0
720  20230916   000000    035959  1694807999  ...    720  0.613952  1.005085     1.0

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '53.725', 'enterprice': '26678.4', 'countrevence': '0', 'unrealprofit': '-15499.6625', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '26389.9', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=1, self.sign=1
127.0.0.1 - - [16/Sep/2023 08:00:01] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='s_rsrs', self.symbol='BTCUSDT', interval='4h', intervalSec=14400, wid=25, thd=0.6, self.sign=1, self.total=1431863.74296, self.flagDict['side']='buy', self.tradeCount=23, self.count=749
self.closeSec=1694822399, self.tradeDate='20230916', self.openTime='040000', self.closeTime='075959', self.symbol='BTCUSDT', self.open=26386.9, self.close=26590.8, self.high=26890.0, self.low=26357.3, self.vol=66407.988, self.amt=1769890201.68812 
2023-09-16 08:00:01,544:INFO:s_rsrs:main.py:141:handleKline:2218689: self.closeSec=1694822399, self.tradeDate='20230916', self.openTime='040000', self.closeTime='075959',self.symbol='BTCUSDT',self.open=26386.9, self.close=26590.8, self.high=26890.0, self.low=26357.3, self.vol=66407.988, self.amt=1769890201.68812 
2023-09-16 08:00:01,557:INFO:s_rsrs:main.py:142:handleKline:2218689: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime  ...        vol           amt       pct
717  20230915   120000    155959  ...  20708.984  5.506231e+08 -0.001816
718  20230915   160000    195959  ...  43585.648  1.156854e+09 -0.005272
719  20230915   200000    235959  ...  69223.358  1.824085e+09 -0.003911
720  20230916   000000    035959  ...  24017.548  6.329968e+08  0.002885
721  20230916   040000    075959  ...  66407.988  1.769890e+09  0.007724

[5 rows x 11 columns]
2023-09-16 08:00:02,187:INFO:s_rsrs:main.py:151:handleKline:2218689: df_s.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec  ...  index      beta    zscore  signal
717  20230915   120000    155959  1694764799  ...    717  0.556396  0.737129     1.0
718  20230915   160000    195959  1694779199  ...    718  0.562301  0.782005     1.0
719  20230915   200000    235959  1694793599  ...    719  0.548969  0.756718     1.0
720  20230916   000000    035959  1694807999  ...    720  0.613952  1.005085     1.0
721  20230916   040000    075959  1694822399  ...    721  0.530162  0.704080     1.0

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '53.725', 'enterprice': '26678.4', 'countrevence': '0', 'unrealprofit': '-4660.456696742', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '26591.65348168', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=1, self.sign=1


