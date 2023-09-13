# 20230913 08:26:01

## /root/FIL/strategy/amihud/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=373746.4768026, self.flagDict['side']='sell', self.tradeCount=2, self.count=35092
self.closeSec=1694564399, self.tradeDate='20230913', self.openTime='081500', self.closeTime='081959', self.symbol='BTCUSDT', self.open=25850.5, self.close=25864.3, self.high=25880.0, self.low=25850.5, self.vol=913.206, self.amt=23624931.948 
127.0.0.1 - - [13/Sep/2023 08:20:02] "POST / HTTP/1.1" 200 -
2023-09-13 08:20:06,242:INFO:amihud:main.py:172:handleKline:2219019: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5855  20230913   075500    075959  ...         0.0        0.0       0
5856  20230913   080000    080459  ...         0.0        0.0       0
5857  20230913   080500    080959  ...         0.0        0.0       0
5858  20230913   081000    081459  ...         0.0        0.0       0
5859  20230913   081500    081959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-09-13 08:20:06,245:INFO:amihud:main.py:175:handleKline:2219019: self.closeSec=1694564399, self.tradeDate='20230913', self.openTime='081500', self.closeTime='081959',self.symbol='BTCUSDT',self.open=25850.5, self.close=25864.3, self.high=25880.0, self.low=25850.5, self.vol=913.206, self.amt=23624931.948, ukdf['pct'].iloc[-1]=0.000534 , ukdf['amount'].iloc[-1]=23624931.948, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5859, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '13.926', 'enterprice': '26864.9', 'countrevence': '0', 'unrealprofit': '13899.93111456312', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '25866.77195788', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1
127.0.0.1 - - [13/Sep/2023 08:25:00] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=373746.4768026, self.flagDict['side']='sell', self.tradeCount=2, self.count=35093
self.closeSec=1694564699, self.tradeDate='20230913', self.openTime='082000', self.closeTime='082459', self.symbol='BTCUSDT', self.open=25864.2, self.close=25881.3, self.high=25881.3, self.low=25853.4, self.vol=584.223, self.amt=15113176.5341 
2023-09-13 08:25:00,806:INFO:amihud:main.py:172:handleKline:2219019: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5856  20230913   080000    080459  ...         0.0        0.0       0
5857  20230913   080500    080959  ...         0.0        0.0       0
5858  20230913   081000    081459  ...         0.0        0.0       0
5859  20230913   081500    081959  ...         0.0        0.0       0
5860  20230913   082000    082459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-09-13 08:25:00,807:INFO:amihud:main.py:175:handleKline:2219019: self.closeSec=1694564699, self.tradeDate='20230913', self.openTime='082000', self.closeTime='082459',self.symbol='BTCUSDT',self.open=25864.2, self.close=25881.3, self.high=25881.3, self.low=25853.4, self.vol=584.223, self.amt=15113176.5341, ukdf['pct'].iloc[-1]=0.000657 , ukdf['amount'].iloc[-1]=15113176.5341, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5860, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '13.926', 'enterprice': '26864.9', 'countrevence': '0', 'unrealprofit': '13694.8284', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '25881.5', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1


## /root/FIL/strategy/factorcheck/log.txt ----- -----

127.0.0.1 - - [13/Sep/2023 08:00:00] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.714181719035411, self.count=35090 

self.closeSec=1694563199, self.tradeDate='20230913', self.openTime='075500', self.closeTime='075959', self.symbol='BTCUSDT', self.open=25838.2, self.close=25825.9, self.high=25846.9, self.low=25802.0 
127.0.0.1 - - [13/Sep/2023 08:05:00] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.714181719035411, self.count=35091 

self.closeSec=1694563499, self.tradeDate='20230913', self.openTime='080000', self.closeTime='080459', self.symbol='BTCUSDT', self.open=25825.8, self.close=25782.1, self.high=25840.0, self.low=25780.0 
127.0.0.1 - - [13/Sep/2023 08:10:00] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.714181719035411, self.count=35092 

self.closeSec=1694563799, self.tradeDate='20230913', self.openTime='080500', self.closeTime='080959', self.symbol='BTCUSDT', self.open=25763.4, self.close=25831.7, self.high=25831.7, self.low=25750.0 
127.0.0.1 - - [13/Sep/2023 08:15:00] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.714181719035411, self.count=35093 

self.closeSec=1694564099, self.tradeDate='20230913', self.openTime='081000', self.closeTime='081459', self.symbol='BTCUSDT', self.open=25832.3, self.close=25850.5, self.high=25868.2, self.low=25820.7 

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.714181719035411, self.count=35094 

self.closeSec=1694564399, self.tradeDate='20230913', self.openTime='081500', self.closeTime='081959', self.symbol='BTCUSDT', self.open=25850.5, self.close=25864.3, self.high=25880.0, self.low=25850.5 
127.0.0.1 - - [13/Sep/2023 08:20:01] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [13/Sep/2023 08:25:00] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.714181719035411, self.count=35095 

self.closeSec=1694564699, self.tradeDate='20230913', self.openTime='082000', self.closeTime='082459', self.symbol='BTCUSDT', self.open=25864.2, self.close=25881.3, self.high=25881.3, self.low=25853.4 


## /root/FIL/strategy/logic/log.txt ----- -----

2023-09-13 08:00:17,501:DEBUG:logic:main.py:463:getModel:2218526: df_s.iloc[-5:,:] :
          date closeTime     open  ...    alpha58   alpha67   alpha72
5769  20230913    052959  26066.4  ...  49.166667  0.553836  0.299467
5770  20230913    055959  26119.9  ...  49.166667  0.548814  0.301877
5771  20230913    062959  26090.0  ...  48.750000  0.526156  0.310941
5772  20230913    065959  25955.4  ...  48.750000  0.526393  0.319840
5773  20230913    072959  25957.1  ...  48.750000  0.509278  0.348088

[5 rows x 33 columns]
0.5462962962962963
acc is : 0.5462962962962963
2023-09-13 08:00:17,557:INFO:logic:main.py:468:getModel:2218526: df_pred.iloc[-5:,:] :
     pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
535     0  0.522957  0.477043       0  ...  0.997451  -1.0    0.0  1.024455
536     1  0.495210  0.504790       0  ...  1.002593  -1.0    0.0  1.019174
537     1  0.461833  0.538167       1  ...  1.002531  -1.0    0.0  1.019237
538     1  0.493566  0.506434       0  ...  1.006594  -1.0    0.0  1.015106
539     1  0.463950  0.536050       0  ...  1.007607  -1.0    0.0  1.014085

[5 rows x 10 columns]
2023-09-13 08:00:17,567:INFO:logic:main.py:478:getModel:2218526: df_panel.iloc[-5:,:] :
    pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
45     0  0.523044  0.476956       0  ...  0.976629  -1.0    0.0  1.011319
46     1  0.495539  0.504461       0  ...  0.981664  -1.0    0.0  1.002483
47     1  0.462362  0.537638       1  ...  0.981603  -1.0    0.0  1.006893
48     1  0.493604  0.506396       0  ...  0.985582  -1.0    0.0  1.019373
49     1  0.463950  0.536050       0  ...  1.007607  -1.0    0.0  1.014085

[5 rows x 10 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '28.172', 'enterprice': '26023.2', 'countrevence': '0', 'unrealprofit': '5479.37051594036', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '25828.70296337', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}


## /root/FIL/strategy/modifiedmom/log.txt ----- -----

127.0.0.1 - - [13/Sep/2023 07:30:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=17543 

self.closeSec=1694561399, self.tradeDate='20230913', self.openTime='072000', self.closeTime='072959', self.symbol='BTCUSDT', self.open='25860.9', self.close='25851.9'

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=17544 

self.closeSec=1694561999, self.tradeDate='20230913', self.openTime='073000', self.closeTime='073959', self.symbol='BTCUSDT', self.open='25851.8', self.close='25867.1'
127.0.0.1 - - [13/Sep/2023 07:40:01] "POST / HTTP/1.1" 200 -

--handleKline--:  127.0.0.1 - - [13/Sep/2023 07:50:01] "POST / HTTP/1.1" 200 -
self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=17545 

self.closeSec=1694562599, self.tradeDate='20230913', self.openTime='074000', self.closeTime='074959', self.symbol='BTCUSDT', self.open='25866.4', self.close='25846.1'
127.0.0.1 - - [13/Sep/2023 08:00:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=17546 

self.closeSec=1694563199, self.tradeDate='20230913', self.openTime='075000', self.closeTime='075959', self.symbol='BTCUSDT', self.open='25846.1', self.close='25825.8'

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=17547 

self.closeSec=1694563799, self.tradeDate='20230913', self.openTime='080000', self.closeTime='080959', self.symbol='BTCUSDT', self.open='25825.8', self.close='25832.4'
127.0.0.1 - - [13/Sep/2023 08:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=17548 

self.closeSec=1694564399, self.tradeDate='20230913', self.openTime='081000', self.closeTime='081959', self.symbol='BTCUSDT', self.open='25832.3', self.close='25864.3'
127.0.0.1 - - [13/Sep/2023 08:20:04] "POST / HTTP/1.1" 200 -


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


--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=17546 

self.closeSec=1694561399, self.tradeDate='20230913', self.openTime='072000', self.closeTime='072959', self.symbol='BTCUSDT', self.open='25860.9', self.close='25851.9'
127.0.0.1 - - [13/Sep/2023 07:30:01] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [13/Sep/2023 07:40:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=17547 

self.closeSec=1694561999, self.tradeDate='20230913', self.openTime='073000', self.closeTime='073959', self.symbol='BTCUSDT', self.open='25851.8', self.close='25867.1'

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=17548 

self.closeSec=1694562599, self.tradeDate='20230913', self.openTime='074000', self.closeTime='074959', self.symbol='BTCUSDT', self.open='25866.4', self.close='25846.1'
127.0.0.1 - - [13/Sep/2023 07:50:01] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [13/Sep/2023 08:00:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=17549 

self.closeSec=1694563199, self.tradeDate='20230913', self.openTime='075000', self.closeTime='075959', self.symbol='BTCUSDT', self.open='25846.1', self.close='25825.8'

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=17550 

self.closeSec=1694563799, self.tradeDate='20230913', self.openTime='080000', self.closeTime='080959', self.symbol='BTCUSDT', self.open='25825.8', self.close='25832.4'
127.0.0.1 - - [13/Sep/2023 08:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=17551 

self.closeSec=1694564399, self.tradeDate='20230913', self.openTime='081000', self.closeTime='081959', self.symbol='BTCUSDT', self.open='25832.3', self.close='25864.3'
127.0.0.1 - - [13/Sep/2023 08:20:04] "POST / HTTP/1.1" 200 -


## /root/FIL/strategy/similarity/log.txt ----- -----

127.0.0.1 - - [13/Sep/2023 07:30:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=17546 

self.closeSec=1694561399, self.tradeDate='20230913', self.openTime='072000', self.closeTime='072959', self.symbol='BTCUSDT', self.open='25860.9', self.close='25851.9'
127.0.0.1 - - [13/Sep/2023 07:40:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=17547 

self.closeSec=1694561999, self.tradeDate='20230913', self.openTime='073000', self.closeTime='073959', self.symbol='BTCUSDT', self.open='25851.8', self.close='25867.1'

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=17548 

self.closeSec=1694562599, self.tradeDate='20230913', self.openTime='074000', self.closeTime='074959', self.symbol='BTCUSDT', self.open='25866.4', self.close='25846.1'
127.0.0.1 - - [13/Sep/2023 07:50:01] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [13/Sep/2023 08:00:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=17549 

self.closeSec=1694563199, self.tradeDate='20230913', self.openTime='075000', self.closeTime='075959', self.symbol='BTCUSDT', self.open='25846.1', self.close='25825.8'

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=17550 

self.closeSec=1694563799, self.tradeDate='20230913', self.openTime='080000', self.closeTime='080959', self.symbol='BTCUSDT', self.open='25825.8', self.close='25832.4'
127.0.0.1 - - [13/Sep/2023 08:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=17551 

self.closeSec=1694564399, self.tradeDate='20230913', self.openTime='081000', self.closeTime='081959', self.symbol='BTCUSDT', self.open='25832.3', self.close='25864.3'
127.0.0.1 - - [13/Sep/2023 08:20:04] "POST / HTTP/1.1" 200 -


## /root/FIL/strategy/sr_min/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=1, self.total=996015.990996, self.flagDict['side']='buy', self.tradeCount=1, self.count=35092
self.closeSec=1694564399, self.tradeDate='20230913', self.openTime='081500', self.closeTime='081959', self.symbol='BTCUSDT', self.open=25850.5, self.close=25864.3, self.high=25880.0, self.low=25850.5, self.vol=913.206, self.amt=23624931.948 
127.0.0.1 - - [13/Sep/2023 08:20:02] "POST / HTTP/1.1" 200 -
2023-09-13 08:20:06,247:INFO:sr_min:main.py:172:handleKline:2219263: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5855  20230913   075500    075959  ...         0.0        0.0       0
5856  20230913   080000    080459  ...         0.0        0.0       0
5857  20230913   080500    080959  ...         0.0        0.0       0
5858  20230913   081000    081459  ...         0.0        0.0       0
5859  20230913   081500    081959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-09-13 08:20:06,256:INFO:sr_min:main.py:175:handleKline:2219263: self.closeSec=1694564399, self.tradeDate='20230913', self.openTime='081500', self.closeTime='081959',self.symbol='BTCUSDT',self.open=25850.5, self.close=25864.3, self.high=25880.0, self.low=25850.5, self.vol=913.206, self.amt=23624931.948, ukdf['pct'].iloc[-1]=0.000534 , ukdf['amount'].iloc[-1]=23624931.948, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5859, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '37.141', 'enterprice': '26844', 'countrevence': '0', 'unrealprofit': '-36295.22671237892', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '25866.77195788', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=1
127.0.0.1 - - [13/Sep/2023 08:25:00] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=1, self.total=996015.990996, self.flagDict['side']='buy', self.tradeCount=1, self.count=35093
self.closeSec=1694564699, self.tradeDate='20230913', self.openTime='082000', self.closeTime='082459', self.symbol='BTCUSDT', self.open=25864.2, self.close=25881.3, self.high=25881.3, self.low=25853.4, self.vol=584.223, self.amt=15113176.5341 
2023-09-13 08:25:00,817:INFO:sr_min:main.py:172:handleKline:2219263: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5856  20230913   080000    080459  ...         0.0        0.0       0
5857  20230913   080500    080959  ...         0.0        0.0       0
5858  20230913   081000    081459  ...         0.0        0.0       0
5859  20230913   081500    081959  ...         0.0        0.0       0
5860  20230913   082000    082459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-09-13 08:25:00,817:INFO:sr_min:main.py:175:handleKline:2219263: self.closeSec=1694564699, self.tradeDate='20230913', self.openTime='082000', self.closeTime='082459',self.symbol='BTCUSDT',self.open=25864.2, self.close=25881.3, self.high=25881.3, self.low=25853.4, self.vol=584.223, self.amt=15113176.5341, ukdf['pct'].iloc[-1]=0.000657 , ukdf['amount'].iloc[-1]=15113176.5341, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5860, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '37.141', 'enterprice': '26844', 'countrevence': '0', 'unrealprofit': '-35748.2125', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '25881.5', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=1


## /root/FIL/strategy/s_rsrs/log.txt ----- -----

719  20230912   200000    235959  1694534399  ...    719  0.154263 -0.664905    -1.0
720  20230913   000000    035959  1694548799  ...    720  0.174697 -0.616181    -1.0

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '57.177', 'enterprice': '25892.3', 'countrevence': '0', 'unrealprofit': '-9240.23653018875', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '26053.90757875', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-1, self.sign=-1
127.0.0.1 - - [13/Sep/2023 08:00:01] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='s_rsrs', self.symbol='BTCUSDT', interval='4h', intervalSec=14400, wid=25, thd=0.6, self.sign=-1, self.total=1478963.5930628998, self.flagDict['side']='sell', self.tradeCount=22, self.count=731
self.closeSec=1694563199, self.tradeDate='20230913', self.openTime='040000', self.closeTime='075959', self.symbol='BTCUSDT', self.open=26052.1, self.close=25825.8, self.high=26150.0, self.low=25762.0, self.vol=40646.871, self.amt=1054920345.93493 
2023-09-13 08:00:01,518:INFO:s_rsrs:main.py:141:handleKline:2218689: self.closeSec=1694563199, self.tradeDate='20230913', self.openTime='040000', self.closeTime='075959',self.symbol='BTCUSDT',self.open=26052.1, self.close=25825.8, self.high=26150.0, self.low=25762.0, self.vol=40646.871, self.amt=1054920345.93493 
2023-09-13 08:00:01,536:INFO:s_rsrs:main.py:142:handleKline:2218689: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime  ...         vol           amt       pct
717  20230912   120000    155959  ...   95929.589  2.472843e+09  0.000857
718  20230912   160000    195959  ...  107772.154  2.806439e+09  0.010709
719  20230912   200000    235959  ...  104596.895  2.736354e+09  0.004052
720  20230913   000000    035959  ...  134082.041  3.505512e+09 -0.005357
721  20230913   040000    075959  ...   40646.871  1.054920e+09 -0.008683

[5 rows x 11 columns]
2023-09-13 08:00:02,259:INFO:s_rsrs:main.py:151:handleKline:2218689: df_s.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec  ...  index      beta    zscore  signal
717  20230912   120000    155959  1694505599  ...    717  0.150643 -0.666047    -1.0
718  20230912   160000    195959  1694519999  ...    718  0.104921 -0.794423    -1.0
719  20230912   200000    235959  1694534399  ...    719  0.154263 -0.664905    -1.0
720  20230913   000000    035959  1694548799  ...    720  0.174697 -0.616181    -1.0
721  20230913   040000    075959  1694563199  ...    721  0.182931 -0.601752    -1.0

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '57.177', 'enterprice': '25892.3', 'countrevence': '0', 'unrealprofit': '3709.89299282769', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '25827.41564103', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-1, self.sign=-1


