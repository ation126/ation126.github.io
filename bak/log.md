# 20230911 08:26:02

## /root/FIL/strategy/amihud/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=373746.4768026, self.flagDict['side']='sell', self.tradeCount=2, self.count=34516
self.closeSec=1694391599, self.tradeDate='20230911', self.openTime='081500', self.closeTime='081959', self.symbol='BTCUSDT', self.open=25861.7, self.close=25833.7, self.high=25864.9, self.low=25831.7, self.vol=1166.964, self.amt=30165300.3936 
127.0.0.1 - - [11/Sep/2023 08:20:02] "POST / HTTP/1.1" 200 -
2023-09-11 08:20:06,075:INFO:amihud:main.py:172:handleKline:2219019: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5855  20230911   075500    075959  ...         0.0        0.0       0
5856  20230911   080000    080459  ...         0.0        0.0       0
5857  20230911   080500    080959  ...         0.0        0.0       0
5858  20230911   081000    081459  ...         0.0        0.0       0
5859  20230911   081500    081959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-09-11 08:20:06,086:INFO:amihud:main.py:175:handleKline:2219019: self.closeSec=1694391599, self.tradeDate='20230911', self.openTime='081500', self.closeTime='081959',self.symbol='BTCUSDT',self.open=25861.7, self.close=25833.7, self.high=25864.9, self.low=25831.7, self.vol=1166.964, self.amt=30165300.3936, ukdf['pct'].iloc[-1]=-0.001079 , ukdf['amount'].iloc[-1]=30165300.3936, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5859, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '13.926', 'enterprice': '26864.9', 'countrevence': '0', 'unrealprofit': '14314.65627015996', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '25836.99132054', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1
127.0.0.1 - - [11/Sep/2023 08:25:00] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=373746.4768026, self.flagDict['side']='sell', self.tradeCount=2, self.count=34517
self.closeSec=1694391899, self.tradeDate='20230911', self.openTime='082000', self.closeTime='082459', self.symbol='BTCUSDT', self.open=25833.8, self.close=25799.9, self.high=25848.0, self.low=25780.0, self.vol=2891.049, self.amt=74611667.7221 
2023-09-11 08:25:00,783:INFO:amihud:main.py:172:handleKline:2219019: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5856  20230911   080000    080459  ...         0.0        0.0       0
5857  20230911   080500    080959  ...         0.0        0.0       0
5858  20230911   081000    081459  ...         0.0        0.0       0
5859  20230911   081500    081959  ...         0.0        0.0       0
5860  20230911   082000    082459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-09-11 08:25:00,784:INFO:amihud:main.py:175:handleKline:2219019: self.closeSec=1694391899, self.tradeDate='20230911', self.openTime='082000', self.closeTime='082459',self.symbol='BTCUSDT',self.open=25833.8, self.close=25799.9, self.high=25848.0, self.low=25780.0, self.vol=2891.049, self.amt=74611667.7221, ukdf['pct'].iloc[-1]=-0.001308 , ukdf['amount'].iloc[-1]=74611667.7221, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5860, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '13.926', 'enterprice': '26864.9', 'countrevence': '0', 'unrealprofit': '14831.19', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '25799.9', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1


## /root/FIL/strategy/factorcheck/log.txt ----- -----

127.0.0.1 - - [11/Sep/2023 08:00:00] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.714181719035411, self.count=34514 

self.closeSec=1694390399, self.tradeDate='20230911', self.openTime='075500', self.closeTime='075959', self.symbol='BTCUSDT', self.open=25829.9, self.close=25828.4, self.high=25834.7, self.low=25826.9 

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.714181719035411, self.count=34515 

self.closeSec=1694390699, self.tradeDate='20230911', self.openTime='080000', self.closeTime='080459', self.symbol='BTCUSDT', self.open=25828.4, self.close=25829.8, self.high=25838.7, self.low=25818.4 
127.0.0.1 - - [11/Sep/2023 08:05:00] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.714181719035411, self.count=34516 

self.closeSec=1694390999, self.tradeDate='20230911', self.openTime='080500', self.closeTime='080959', self.symbol='BTCUSDT', self.open=25831.9, self.close=25849.2, self.high=25853.0, self.low=25830.5 
127.0.0.1 - - [11/Sep/2023 08:10:00] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.714181719035411, self.count=34517 

self.closeSec=1694391299, self.tradeDate='20230911', self.openTime='081000', self.closeTime='081459', self.symbol='BTCUSDT', self.open=25849.3, self.close=25861.6, self.high=25861.9, self.low=25849.2 
127.0.0.1 - - [11/Sep/2023 08:15:00] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.714181719035411, self.count=34518 

self.closeSec=1694391599, self.tradeDate='20230911', self.openTime='081500', self.closeTime='081959', self.symbol='BTCUSDT', self.open=25861.7, self.close=25833.7, self.high=25864.9, self.low=25831.7 
127.0.0.1 - - [11/Sep/2023 08:20:01] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [11/Sep/2023 08:25:00] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.714181719035411, self.count=34519 

self.closeSec=1694391899, self.tradeDate='20230911', self.openTime='082000', self.closeTime='082459', self.symbol='BTCUSDT', self.open=25833.8, self.close=25799.9, self.high=25848.0, self.low=25780.0 


## /root/FIL/strategy/logic/log.txt ----- -----

2023-09-11 08:00:17,001:DEBUG:logic:main.py:463:getModel:2218526: df_s.iloc[-5:,:] :
          date closeTime     open  ...    alpha58   alpha67   alpha72
5769  20230911    052959  25807.0  ...  52.500000  0.520775  0.527807
5770  20230911    055959  25880.4  ...  52.916667  0.526505  0.493812
5771  20230911    062959  25893.0  ...  52.916667  0.528796  0.465612
5772  20230911    065959  25898.5  ...  52.500000  0.501681  0.459668
5773  20230911    072959  25838.3  ...  52.083333  0.489555  0.457716

[5 rows x 33 columns]
0.5222222222222223
acc is : 0.5222222222222223
2023-09-11 08:00:17,055:INFO:logic:main.py:468:getModel:2218526: df_pred.iloc[-5:,:] :
     pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
535     0  0.518279  0.481721       1  ...  1.013001  -1.0    0.0  0.953631
536     0  0.505496  0.494504       1  ...  1.012785  -1.0    0.0  0.953834
537     1  0.499312  0.500688       0  ...  1.015140  -1.0    0.0  0.951617
538     1  0.476865  0.523135       0  ...  1.016259  -1.0    0.0  0.950567
539     1  0.483975  0.516025       1  ...  1.015527  -1.0    0.0  0.951252

[5 rows x 10 columns]
2023-09-11 08:00:17,066:INFO:logic:main.py:478:getModel:2218526: df_panel.iloc[-5:,:] :
    pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
45     0  0.517854  0.482146       1  ...  1.013001  -1.0    0.0  0.952229
46     0  0.505292  0.494708       1  ...  1.012785  -1.0    0.0  0.953592
47     1  0.499268  0.500732       0  ...  1.015140  -1.0    0.0  0.951813
48     1  0.476430  0.523570       0  ...  1.016259  -1.0    0.0  0.948112
49     1  0.483975  0.516025       1  ...  1.015527  -1.0    0.0  0.951252

[5 rows x 10 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '28.306', 'enterprice': '25771.5', 'countrevence': '0', 'unrealprofit': '-1701.1906', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '25831.6', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}


## /root/FIL/strategy/modifiedmom/log.txt ----- -----

127.0.0.1 - - [11/Sep/2023 07:30:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=17255 

self.closeSec=1694388599, self.tradeDate='20230911', self.openTime='072000', self.closeTime='072959', self.symbol='BTCUSDT', self.open='25822.6', self.close='25809.8'

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=17256 

self.closeSec=1694389199, self.tradeDate='20230911', self.openTime='073000', self.closeTime='073959', self.symbol='BTCUSDT', self.open='25809.8', self.close='25833.4'
127.0.0.1 - - [11/Sep/2023 07:40:01] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [11/Sep/2023 07:50:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=17257 

self.closeSec=1694389799, self.tradeDate='20230911', self.openTime='074000', self.closeTime='074959', self.symbol='BTCUSDT', self.open='25833.5', self.close='25837.4'
127.0.0.1 - - [11/Sep/2023 08:00:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=17258 

self.closeSec=1694390399, self.tradeDate='20230911', self.openTime='075000', self.closeTime='075959', self.symbol='BTCUSDT', self.open='25837.5', self.close='25828.4'

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=17259 

self.closeSec=1694390999, self.tradeDate='20230911', self.openTime='080000', self.closeTime='080959', self.symbol='BTCUSDT', self.open='25828.4', self.close='25849.2'
127.0.0.1 - - [11/Sep/2023 08:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=17260 

self.closeSec=1694391599, self.tradeDate='20230911', self.openTime='081000', self.closeTime='081959', self.symbol='BTCUSDT', self.open='25849.3', self.close='25833.7'
127.0.0.1 - - [11/Sep/2023 08:20:04] "POST / HTTP/1.1" 200 -


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


--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=17258 

self.closeSec=1694388599, self.tradeDate='20230911', self.openTime='072000', self.closeTime='072959', self.symbol='BTCUSDT', self.open='25822.6', self.close='25809.8'
127.0.0.1 - - [11/Sep/2023 07:30:01] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [11/Sep/2023 07:40:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=17259 

self.closeSec=1694389199, self.tradeDate='20230911', self.openTime='073000', self.closeTime='073959', self.symbol='BTCUSDT', self.open='25809.8', self.close='25833.4'
127.0.0.1 - - [11/Sep/2023 07:50:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=17260 

self.closeSec=1694389799, self.tradeDate='20230911', self.openTime='074000', self.closeTime='074959', self.symbol='BTCUSDT', self.open='25833.5', self.close='25837.4'

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=17261 

self.closeSec=1694390399, self.tradeDate='20230911', self.openTime='075000', self.closeTime='075959', self.symbol='BTCUSDT', self.open='25837.5', self.close='25828.4'
127.0.0.1 - - [11/Sep/2023 08:00:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=17262 

self.closeSec=1694390999, self.tradeDate='20230911', self.openTime='080000', self.closeTime='080959', self.symbol='BTCUSDT', self.open='25828.4', self.close='25849.2'
127.0.0.1 - - [11/Sep/2023 08:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=17263 

self.closeSec=1694391599, self.tradeDate='20230911', self.openTime='081000', self.closeTime='081959', self.symbol='BTCUSDT', self.open='25849.3', self.close='25833.7'
127.0.0.1 - - [11/Sep/2023 08:20:04] "POST / HTTP/1.1" 200 -


## /root/FIL/strategy/similarity/log.txt ----- -----


--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=17258 

self.closeSec=1694388599, self.tradeDate='20230911', self.openTime='072000', self.closeTime='072959', self.symbol='BTCUSDT', self.open='25822.6', self.close='25809.8'
127.0.0.1 - - [11/Sep/2023 07:30:01] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [11/Sep/2023 07:40:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=17259 

self.closeSec=1694389199, self.tradeDate='20230911', self.openTime='073000', self.closeTime='073959', self.symbol='BTCUSDT', self.open='25809.8', self.close='25833.4'

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=17260 

self.closeSec=1694389799, self.tradeDate='20230911', self.openTime='074000', self.closeTime='074959', self.symbol='BTCUSDT', self.open='25833.5', self.close='25837.4'
127.0.0.1 - - [11/Sep/2023 07:50:01] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [11/Sep/2023 08:00:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=17261 

self.closeSec=1694390399, self.tradeDate='20230911', self.openTime='075000', self.closeTime='075959', self.symbol='BTCUSDT', self.open='25837.5', self.close='25828.4'
127.0.0.1 - - [11/Sep/2023 08:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=17262 

self.closeSec=1694390999, self.tradeDate='20230911', self.openTime='080000', self.closeTime='080959', self.symbol='BTCUSDT', self.open='25828.4', self.close='25849.2'

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=17263 

self.closeSec=1694391599, self.tradeDate='20230911', self.openTime='081000', self.closeTime='081959', self.symbol='BTCUSDT', self.open='25849.3', self.close='25833.7'
127.0.0.1 - - [11/Sep/2023 08:20:04] "POST / HTTP/1.1" 200 -


## /root/FIL/strategy/sr_min/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=1, self.total=996015.990996, self.flagDict['side']='buy', self.tradeCount=1, self.count=34516
self.closeSec=1694391599, self.tradeDate='20230911', self.openTime='081500', self.closeTime='081959', self.symbol='BTCUSDT', self.open=25861.7, self.close=25833.7, self.high=25864.9, self.low=25831.7, self.vol=1166.964, self.amt=30165300.3936 
127.0.0.1 - - [11/Sep/2023 08:20:02] "POST / HTTP/1.1" 200 -
2023-09-11 08:20:06,076:INFO:sr_min:main.py:172:handleKline:2219263: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5855  20230911   075500    075959  ...         0.0        0.0       0
5856  20230911   080000    080459  ...         0.0        0.0       0
5857  20230911   080500    080959  ...         0.0        0.0       0
5858  20230911   081000    081459  ...         0.0        0.0       0
5859  20230911   081500    081959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-09-11 08:20:06,087:INFO:sr_min:main.py:175:handleKline:2219263: self.closeSec=1694391599, self.tradeDate='20230911', self.openTime='081500', self.closeTime='081959',self.symbol='BTCUSDT',self.open=25861.7, self.close=25833.7, self.high=25864.9, self.low=25831.7, self.vol=1166.964, self.amt=30165300.3936, ukdf['pct'].iloc[-1]=-0.001079 , ukdf['amount'].iloc[-1]=30165300.3936, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5859, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '37.141', 'enterprice': '26844', 'countrevence': '0', 'unrealprofit': '-37401.30936382386', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '25836.99132054', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=1
127.0.0.1 - - [11/Sep/2023 08:25:00] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=1, self.total=996015.990996, self.flagDict['side']='buy', self.tradeCount=1, self.count=34517
self.closeSec=1694391899, self.tradeDate='20230911', self.openTime='082000', self.closeTime='082459', self.symbol='BTCUSDT', self.open=25833.8, self.close=25799.9, self.high=25848.0, self.low=25780.0, self.vol=2891.049, self.amt=74611667.7221 
2023-09-11 08:25:00,790:INFO:sr_min:main.py:172:handleKline:2219263: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5856  20230911   080000    080459  ...         0.0        0.0       0
5857  20230911   080500    080959  ...         0.0        0.0       0
5858  20230911   081000    081459  ...         0.0        0.0       0
5859  20230911   081500    081959  ...         0.0        0.0       0
5860  20230911   082000    082459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-09-11 08:25:00,790:INFO:sr_min:main.py:175:handleKline:2219263: self.closeSec=1694391899, self.tradeDate='20230911', self.openTime='082000', self.closeTime='082459',self.symbol='BTCUSDT',self.open=25833.8, self.close=25799.9, self.high=25848.0, self.low=25780.0, self.vol=2891.049, self.amt=74611667.7221, ukdf['pct'].iloc[-1]=-0.001308 , ukdf['amount'].iloc[-1]=74611667.7221, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5860, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '37.141', 'enterprice': '26844', 'countrevence': '0', 'unrealprofit': '-38778.9181', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '25799.9', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=1


## /root/FIL/strategy/s_rsrs/log.txt ----- -----

719  20230910   200000    235959  1694361599  ...    719  0.105012 -0.813227    -1.0
720  20230911   000000    035959  1694375999  ...    720  0.087417 -0.859435    -1.0

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '57.177', 'enterprice': '25892.3', 'countrevence': '0', 'unrealprofit': '6249.4461', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '25783', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-1, self.sign=-1
127.0.0.1 - - [11/Sep/2023 08:00:01] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='s_rsrs', self.symbol='BTCUSDT', interval='4h', intervalSec=14400, wid=25, thd=0.6, self.sign=-1, self.total=1478963.5930628998, self.flagDict['side']='sell', self.tradeCount=22, self.count=719
self.closeSec=1694390399, self.tradeDate='20230911', self.openTime='040000', self.closeTime='075959', self.symbol='BTCUSDT', self.open=25786.7, self.close=25828.4, self.high=26037.3, self.low=25758.0, self.vol=49095.382, self.amt=1270013671.39998 
2023-09-11 08:00:01,511:INFO:s_rsrs:main.py:141:handleKline:2218689: self.closeSec=1694390399, self.tradeDate='20230911', self.openTime='040000', self.closeTime='075959',self.symbol='BTCUSDT',self.open=25786.7, self.close=25828.4, self.high=26037.3, self.low=25758.0, self.vol=49095.382, self.amt=1270013671.39998 
2023-09-11 08:00:01,527:INFO:s_rsrs:main.py:142:handleKline:2218689: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime  ...        vol           amt       pct
717  20230910   120000    155959  ...  21004.581  5.421424e+08 -0.000313
718  20230910   160000    195959  ...  13734.798  3.546014e+08 -0.002326
719  20230910   200000    235959  ...  23274.670  5.997833e+08 -0.000733
720  20230911   000000    035959  ...  45643.606  1.173217e+09  0.000885
721  20230911   040000    075959  ...  49095.382  1.270014e+09  0.001613

[5 rows x 11 columns]
2023-09-11 08:00:02,403:INFO:s_rsrs:main.py:151:handleKline:2218689: df_s.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec  ...  index      beta    zscore  signal
717  20230910   120000    155959  1694332799  ...    717  0.113988 -0.792834    -1.0
718  20230910   160000    195959  1694347199  ...    718  0.106684 -0.811072    -1.0
719  20230910   200000    235959  1694361599  ...    719  0.105012 -0.813227    -1.0
720  20230911   000000    035959  1694375999  ...    720  0.087417 -0.859435    -1.0
721  20230911   040000    075959  1694390399  ...    721  0.332722 -0.181974     NaN

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '57.177', 'enterprice': '25892.3', 'countrevence': '0', 'unrealprofit': '3619.01036116728', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '25829.00513736', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-9223372036854775808, self.sign=-1


