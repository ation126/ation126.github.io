# 20230823 08:26:02

## /root/FIL/strategy/amihud/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=373746.4768026, self.flagDict['side']='sell', self.tradeCount=2, self.count=29044
self.closeSec=1692749999, self.tradeDate='20230823', self.openTime='081500', self.closeTime='081959', self.symbol='BTCUSDT', self.open=26150.0, self.close=26110.1, self.high=26177.0, self.low=26100.1, self.vol=2865.541, self.amt=74906372.81067 
127.0.0.1 - - [23/Aug/2023 08:20:01] "POST / HTTP/1.1" 200 -
2023-08-23 08:20:04,915:INFO:amihud:main.py:172:handleKline:2219019: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5843  20230823   075500    075959  ...         0.0        0.0       0
5844  20230823   080000    080459  ...         0.0        0.0       0
5845  20230823   080500    080959  ...         0.0        0.0       0
5846  20230823   081000    081459  ...         0.0        0.0       0
5847  20230823   081500    081959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-08-23 08:20:04,919:INFO:amihud:main.py:175:handleKline:2219019: self.closeSec=1692749999, self.tradeDate='20230823', self.openTime='081500', self.closeTime='081959',self.symbol='BTCUSDT',self.open=26150.0, self.close=26110.1, self.high=26177.0, self.low=26100.1, self.vol=2865.541, self.amt=74906372.81067, ukdf['pct'].iloc[-1]=-0.001522 , ukdf['amount'].iloc[-1]=74906372.81067, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5847, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '13.926', 'enterprice': '26864.9', 'countrevence': '0', 'unrealprofit': '10372.0848', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '26120.1', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1
--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=373746.4768026, self.flagDict['side']='sell', self.tradeCount=2, self.count=29045
self.closeSec=1692750299, self.tradeDate='20230823', self.openTime='082000', self.closeTime='082459', self.symbol='BTCUSDT', self.open=26110.1, self.close=26078.4, self.high=26120.1, self.low=26078.2, self.vol=1677.108, self.amt=43765834.2314 
127.0.0.1 - - [23/Aug/2023 08:25:00] "POST / HTTP/1.1" 200 -
2023-08-23 08:25:00,822:INFO:amihud:main.py:172:handleKline:2219019: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5844  20230823   080000    080459  ...         0.0        0.0       0
5845  20230823   080500    080959  ...         0.0        0.0       0
5846  20230823   081000    081459  ...         0.0        0.0       0
5847  20230823   081500    081959  ...         0.0        0.0       0
5848  20230823   082000    082459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-08-23 08:25:00,822:INFO:amihud:main.py:175:handleKline:2219019: self.closeSec=1692750299, self.tradeDate='20230823', self.openTime='082000', self.closeTime='082459',self.symbol='BTCUSDT',self.open=26110.1, self.close=26078.4, self.high=26120.1, self.low=26078.2, self.vol=1677.108, self.amt=43765834.2314, ukdf['pct'].iloc[-1]=-0.001214 , ukdf['amount'].iloc[-1]=43765834.2314, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5848, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '13.926', 'enterprice': '26864.9', 'countrevence': '0', 'unrealprofit': '10882.10177360922', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '26083.47663553', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1


## /root/FIL/strategy/factorcheck/log.txt ----- -----

127.0.0.1 - - [23/Aug/2023 08:00:00] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.714181719035411, self.count=29042 

self.closeSec=1692748799, self.tradeDate='20230823', self.openTime='075500', self.closeTime='075959', self.symbol='BTCUSDT', self.open=26038.9, self.close=26044.4, self.high=26060.0, self.low=26016.5 

--handleKline--: 127.0.0.1 - - [23/Aug/2023 08:05:00] "POST / HTTP/1.1" 200 -
 version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.714181719035411, self.count=29043 

self.closeSec=1692749099, self.tradeDate='20230823', self.openTime='080000', self.closeTime='080459', self.symbol='BTCUSDT', self.open=26044.5, self.close=26106.6, self.high=26112.0, self.low=26016.6 
127.0.0.1 - - [23/Aug/2023 08:10:00] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.714181719035411, self.count=29044 

self.closeSec=1692749399, self.tradeDate='20230823', self.openTime='080500', self.closeTime='080959', self.symbol='BTCUSDT', self.open=26105.0, self.close=26103.8, self.high=26136.6, self.low=26083.3 

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.714181719035411, self.count=29045 

self.closeSec=1692749699, self.tradeDate='20230823', self.openTime='081000', self.closeTime='081459', self.symbol='BTCUSDT', self.open=26103.5, self.close=26149.9, self.high=26160.0, self.low=26100.0 
127.0.0.1 - - [23/Aug/2023 08:15:00] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.714181719035411, self.count=29046 

self.closeSec=1692749999, self.tradeDate='20230823', self.openTime='081500', self.closeTime='081959', self.symbol='BTCUSDT', self.open=26150.0, self.close=26110.1, self.high=26177.0, self.low=26100.1 
127.0.0.1 - - [23/Aug/2023 08:20:01] "POST / HTTP/1.1" 200 -

--handleKline--: 127.0.0.1 - - [23/Aug/2023 08:25:00] "POST / HTTP/1.1" 200 -
 version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.714181719035411, self.count=29047 

self.closeSec=1692750299, self.tradeDate='20230823', self.openTime='082000', self.closeTime='082459', self.symbol='BTCUSDT', self.open=26110.1, self.close=26078.4, self.high=26120.1, self.low=26078.2 


## /root/FIL/strategy/logic/log.txt ----- -----

2023-08-23 08:00:16,263:DEBUG:logic:main.py:463:getModel:2218526: df_s.iloc[-5:,:] :
          date closeTime     open  ...    alpha58   alpha67   alpha72
5769  20230823    052959  25850.7  ...  48.750000  0.395912  0.650943
5770  20230823    055959  25620.2  ...  49.166667  0.402470  0.644255
5771  20230823    062959  25652.4  ...  49.166667  0.429345  0.630796
5772  20230823    065959  25742.1  ...  49.166667  0.445074  0.613779
5773  20230823    072959  25797.5  ...  49.583333  0.474072  0.589159

[5 rows x 33 columns]
0.5370370370370371
acc is : 0.5370370370370371
2023-08-23 08:00:16,322:INFO:logic:main.py:468:getModel:2218526: df_pred.iloc[-5:,:] :
     pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
535     1  0.399417  0.600583       1  ...  1.109667  -1.0    0.0  0.873044
536     1  0.478115  0.521885       1  ...  1.105786  -1.0    0.0  0.876097
537     0  0.515376  0.484624       1  ...  1.103407  -1.0    0.0  0.877983
538     0  0.504912  0.495088       1  ...  1.098762  -1.0    0.0  0.881679
539     0  0.530007  0.469993       1  ...  1.092896  -1.0    0.0  0.886386

[5 rows x 10 columns]
2023-08-23 08:00:16,332:INFO:logic:main.py:478:getModel:2218526: df_panel.iloc[-5:,:] :
    pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
45     1  0.398595  0.601405       1  ...  1.109667  -1.0    0.0  0.872926
46     1  0.477865  0.522135       1  ...  1.076778  -1.0    0.0  0.876088
47     0  0.515054  0.484946       1  ...  1.074461  -1.0    0.0  0.877989
48     0  0.504840  0.495160       1  ...  1.098762  -1.0    0.0  0.882727
49     0  0.530007  0.469993       1  ...  1.092896  -1.0    0.0  0.886386

[5 rows x 10 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '29.581', 'enterprice': '26067.4', 'countrevence': '0', 'unrealprofit': '496.9608', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '26050.6', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}


## /root/FIL/strategy/modifiedmom/log.txt ----- -----


--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=14519 

self.closeSec=1692746999, self.tradeDate='20230823', self.openTime='072000', self.closeTime='072959', self.symbol='BTCUSDT', self.open='25928', self.close='25906.1'
127.0.0.1 - - [23/Aug/2023 07:30:01] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [23/Aug/2023 07:40:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=14520 

self.closeSec=1692747599, self.tradeDate='20230823', self.openTime='073000', self.closeTime='073959', self.symbol='BTCUSDT', self.open='25906.1', self.close='25988'
127.0.0.1 - - [23/Aug/2023 07:50:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=14521 

self.closeSec=1692748199, self.tradeDate='20230823', self.openTime='074000', self.closeTime='074959', self.symbol='BTCUSDT', self.open='25988', self.close='25991.3'
127.0.0.1 - - [23/Aug/2023 08:00:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=14522 

self.closeSec=1692748799, self.tradeDate='20230823', self.openTime='075000', self.closeTime='075959', self.symbol='BTCUSDT', self.open='25991.2', self.close='26044.4'
127.0.0.1 - - [23/Aug/2023 08:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=14523 

self.closeSec=1692749399, self.tradeDate='20230823', self.openTime='080000', self.closeTime='080959', self.symbol='BTCUSDT', self.open='26044.5', self.close='26103.5'

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=14524 

self.closeSec=1692749999, self.tradeDate='20230823', self.openTime='081000', self.closeTime='081959', self.symbol='BTCUSDT', self.open='26103.5', self.close='26110.1'
127.0.0.1 - - [23/Aug/2023 08:20:03] "POST / HTTP/1.1" 200 -


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

127.0.0.1 - - [23/Aug/2023 07:30:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=14522 

self.closeSec=1692746999, self.tradeDate='20230823', self.openTime='072000', self.closeTime='072959', self.symbol='BTCUSDT', self.open='25928', self.close='25906.1'
127.0.0.1 - - [23/Aug/2023 07:40:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=14523 

self.closeSec=1692747599, self.tradeDate='20230823', self.openTime='073000', self.closeTime='073959', self.symbol='BTCUSDT', self.open='25906.1', self.close='25988'
127.0.0.1 - - [23/Aug/2023 07:50:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=14524 

self.closeSec=1692748199, self.tradeDate='20230823', self.openTime='074000', self.closeTime='074959', self.symbol='BTCUSDT', self.open='25988', self.close='25991.3'

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=14525 

self.closeSec=1692748799, self.tradeDate='20230823', self.openTime='075000', self.closeTime='075959', self.symbol='BTCUSDT', self.open='25991.2', self.close='26044.4'
127.0.0.1 - - [23/Aug/2023 08:00:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=14526 

self.closeSec=1692749399, self.tradeDate='20230823', self.openTime='080000', self.closeTime='080959', self.symbol='BTCUSDT', self.open='26044.5', self.close='26103.5'
127.0.0.1 - - [23/Aug/2023 08:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=14527 

self.closeSec=1692749999, self.tradeDate='20230823', self.openTime='081000', self.closeTime='081959', self.symbol='BTCUSDT', self.open='26103.5', self.close='26110.1'
127.0.0.1 - - [23/Aug/2023 08:20:03] "POST / HTTP/1.1" 200 -


## /root/FIL/strategy/similarity/log.txt ----- -----


--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=14522 

self.closeSec=1692746999, self.tradeDate='20230823', self.openTime='072000', self.closeTime='072959', self.symbol='BTCUSDT', self.open='25928', self.close='25906.1'
127.0.0.1 - - [23/Aug/2023 07:30:01] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [23/Aug/2023 07:40:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=14523 

self.closeSec=1692747599, self.tradeDate='20230823', self.openTime='073000', self.closeTime='073959', self.symbol='BTCUSDT', self.open='25906.1', self.close='25988'

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=14524 

self.closeSec=1692748199, self.tradeDate='20230823', self.openTime='074000', self.closeTime='074959', self.symbol='BTCUSDT', self.open='25988', self.close='25991.3'
127.0.0.1 - - [23/Aug/2023 07:50:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=14525 

self.closeSec=1692748799, self.tradeDate='20230823', self.openTime='075000', self.closeTime='075959', self.symbol='BTCUSDT', self.open='25991.2', self.close='26044.4'
127.0.0.1 - - [23/Aug/2023 08:00:01] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [23/Aug/2023 08:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=14526 

self.closeSec=1692749399, self.tradeDate='20230823', self.openTime='080000', self.closeTime='080959', self.symbol='BTCUSDT', self.open='26044.5', self.close='26103.5'

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=14527 

self.closeSec=1692749999, self.tradeDate='20230823', self.openTime='081000', self.closeTime='081959', self.symbol='BTCUSDT', self.open='26103.5', self.close='26110.1'
127.0.0.1 - - [23/Aug/2023 08:20:03] "POST / HTTP/1.1" 200 -


## /root/FIL/strategy/sr_min/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=1, self.total=996015.990996, self.flagDict['side']='buy', self.tradeCount=1, self.count=29044
self.closeSec=1692749999, self.tradeDate='20230823', self.openTime='081500', self.closeTime='081959', self.symbol='BTCUSDT', self.open=26150.0, self.close=26110.1, self.high=26177.0, self.low=26100.1, self.vol=2865.541, self.amt=74906372.81067 
127.0.0.1 - - [23/Aug/2023 08:20:01] "POST / HTTP/1.1" 200 -
2023-08-23 08:20:04,916:INFO:sr_min:main.py:172:handleKline:2219263: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5843  20230823   075500    075959  ...         0.0        0.0       0
5844  20230823   080000    080459  ...         0.0        0.0       0
5845  20230823   080500    080959  ...         0.0        0.0       0
5846  20230823   081000    081459  ...         0.0        0.0       0
5847  20230823   081500    081959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-08-23 08:20:04,918:INFO:sr_min:main.py:175:handleKline:2219263: self.closeSec=1692749999, self.tradeDate='20230823', self.openTime='081500', self.closeTime='081959',self.symbol='BTCUSDT',self.open=26150.0, self.close=26110.1, self.high=26177.0, self.low=26100.1, self.vol=2865.541, self.amt=74906372.81067, ukdf['pct'].iloc[-1]=-0.001522 , ukdf['amount'].iloc[-1]=74906372.81067, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5847, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '37.141', 'enterprice': '26844', 'countrevence': '0', 'unrealprofit': '-26886.3699', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '26120.1', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=1
--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=1, self.total=996015.990996, self.flagDict['side']='buy', self.tradeCount=1, self.count=29045
self.closeSec=1692750299, self.tradeDate='20230823', self.openTime='082000', self.closeTime='082459', self.symbol='BTCUSDT', self.open=26110.1, self.close=26078.4, self.high=26120.1, self.low=26078.2, self.vol=1677.108, self.amt=43765834.2314 
127.0.0.1 - - [23/Aug/2023 08:25:00] "POST / HTTP/1.1" 200 -
2023-08-23 08:25:00,822:INFO:sr_min:main.py:172:handleKline:2219263: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5844  20230823   080000    080459  ...         0.0        0.0       0
5845  20230823   080500    080959  ...         0.0        0.0       0
5846  20230823   081000    081459  ...         0.0        0.0       0
5847  20230823   081500    081959  ...         0.0        0.0       0
5848  20230823   082000    082459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-08-23 08:25:00,822:INFO:sr_min:main.py:175:handleKline:2219263: self.closeSec=1692750299, self.tradeDate='20230823', self.openTime='082000', self.closeTime='082459',self.symbol='BTCUSDT',self.open=26110.1, self.close=26078.4, self.high=26120.1, self.low=26078.2, self.vol=1677.108, self.amt=43765834.2314, ukdf['pct'].iloc[-1]=-0.001214 , ukdf['amount'].iloc[-1]=43765834.2314, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5848, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '37.141', 'enterprice': '26844', 'countrevence': '0', 'unrealprofit': '-28246.59827978027', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '26083.47663553', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=1


## /root/FIL/strategy/s_rsrs/log.txt ----- -----

719  20230822   200000    235959  1692719999  ...    719  0.000080 -1.102173    -1.0
720  20230823   000000    035959  1692734399  ...    720  0.002444 -1.096267    -1.0

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '51.388', 'enterprice': '29432.6', 'countrevence': '0', 'unrealprofit': '188074.4461434244', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '25772.7096337', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-1, self.sign=-1
127.0.0.1 - - [23/Aug/2023 08:00:01] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='s_rsrs', self.symbol='BTCUSDT', interval='4h', intervalSec=14400, wid=25, thd=0.6, self.sign=-1, self.total=1510969.9663512, self.flagDict['side']='sell', self.tradeCount=20, self.count=605
self.closeSec=1692748799, self.tradeDate='20230823', self.openTime='040000', self.closeTime='075959', self.symbol='BTCUSDT', self.open=25767.1, self.close=26044.4, self.high=26060.0, self.low=25280.0, self.vol=102208.075, self.amt=2627785747.53454 
2023-08-23 08:00:01,540:INFO:s_rsrs:main.py:141:handleKline:2218689: self.closeSec=1692748799, self.tradeDate='20230823', self.openTime='040000', self.closeTime='075959',self.symbol='BTCUSDT',self.open=25767.1, self.close=26044.4, self.high=26060.0, self.low=25280.0, self.vol=102208.075, self.amt=2627785747.53454 
2023-08-23 08:00:01,557:INFO:s_rsrs:main.py:142:handleKline:2218689: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime  ...         vol           amt       pct
717  20230822   120000    155959  ...   18541.356  4.827876e+08  0.001897
718  20230822   160000    195959  ...   15537.931  4.046899e+08 -0.002016
719  20230822   200000    235959  ...   44562.768  1.158462e+09 -0.004455
720  20230823   000000    035959  ...  116546.068  3.015657e+09 -0.006010
721  20230823   040000    075959  ...  102208.075  2.627786e+09  0.010758

[5 rows x 11 columns]
2023-08-23 08:00:02,485:INFO:s_rsrs:main.py:151:handleKline:2218689: df_s.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec  ...  index      beta    zscore  signal
717  20230822   120000    155959  1692691199  ...    717  0.073155 -0.944331    -1.0
718  20230822   160000    195959  1692705599  ...    718  0.030819 -1.035881    -1.0
719  20230822   200000    235959  1692719999  ...    719  0.000080 -1.102173    -1.0
720  20230823   000000    035959  1692734399  ...    720  0.002444 -1.096267    -1.0
721  20230823   040000    075959  1692748799  ...    721  0.020726 -1.055603    -1.0

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '51.388', 'enterprice': '29432.6', 'countrevence': '0', 'unrealprofit': '174040.07190953368', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '26045.81569414', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-1, self.sign=-1


