# 20230509 08:26:01

## /root/FIL/strategy/amihud/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=993672.4896432, self.flagDict['side']='sell', self.tradeCount=2, self.count=46869
self.closeSec=1683591599, self.tradeDate='20230509', self.openTime='081500', self.closeTime='081959', self.symbol='BTCUSDT', self.open=27618.9, self.close=27620.9, self.high=27629.6, self.low=27609.3, self.vol=395.757, self.amt=10931258.5754 
127.0.0.1 - - [09/May/2023 08:20:03] "POST / HTTP/1.1" 200 -
2023-05-09 08:20:06,489:INFO:amihud:main.py:172:handleKline:200676: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5855  20230509   075500    075959  ...         0.0        0.0       0
5856  20230509   080000    080459  ...         0.0        0.0       0
5857  20230509   080500    080959  ...         0.0        0.0       0
5858  20230509   081000    081459  ...         0.0        0.0       0
5859  20230509   081500    081959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-05-09 08:20:06,500:INFO:amihud:main.py:175:handleKline:200676: self.closeSec=1683591599, self.tradeDate='20230509', self.openTime='081500', self.closeTime='081959',self.symbol='BTCUSDT',self.open=27618.9, self.close=27620.9, self.high=27629.6, self.low=27609.3, self.vol=395.757, self.amt=10931258.5754, ukdf['pct'].iloc[-1]=6.9e-05 , ukdf['amount'].iloc[-1]=10931258.5754, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5859, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '60.176', 'enterprice': '16529.3', 'countrevence': '0', 'unrealprofit': '-667601.00804083776', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '27623.44065476', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1
127.0.0.1 - - [09/May/2023 08:25:02] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=993672.4896432, self.flagDict['side']='sell', self.tradeCount=2, self.count=46870
self.closeSec=1683591899, self.tradeDate='20230509', self.openTime='082000', self.closeTime='082459', self.symbol='BTCUSDT', self.open=27620.9, self.close=27616.0, self.high=27627.1, self.low=27566.2, self.vol=1405.172, self.amt=38779332.8597 
2023-05-09 08:25:02,098:INFO:amihud:main.py:172:handleKline:200676: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5856  20230509   080000    080459  ...         0.0        0.0       0
5857  20230509   080500    080959  ...         0.0        0.0       0
5858  20230509   081000    081459  ...         0.0        0.0       0
5859  20230509   081500    081959  ...         0.0        0.0       0
5860  20230509   082000    082459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-05-09 08:25:02,098:INFO:amihud:main.py:175:handleKline:200676: self.closeSec=1683591899, self.tradeDate='20230509', self.openTime='082000', self.closeTime='082459',self.symbol='BTCUSDT',self.open=27620.9, self.close=27616.0, self.high=27627.1, self.low=27566.2, self.vol=1405.172, self.amt=38779332.8597, ukdf['pct'].iloc[-1]=-0.000177 , ukdf['amount'].iloc[-1]=38779332.8597, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5860, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '60.176', 'enterprice': '16529.3', 'countrevence': '0', 'unrealprofit': '-667213.4352', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '27617', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1


## /root/FIL/strategy/factorcheck/log.txt ----- -----

127.0.0.1 - - [09/May/2023 08:00:02] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=23, self.factor=0.43541661550691446, self.count=47431 

self.closeSec=1683590399, self.tradeDate='20230509', self.openTime='075500', self.closeTime='075959', self.symbol='BTCUSDT', self.open=27685.9, self.close=27659.8, self.high=27686.0, self.low=27652.5 

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=23, self.factor=0.43541661550691446, self.count=47432 

self.closeSec=1683590699, self.tradeDate='20230509', self.openTime='080000', self.closeTime='080459', self.symbol='BTCUSDT', self.open=27659.8, self.close=27639.8, self.high=27663.5, self.low=27636.6 
127.0.0.1 - - [09/May/2023 08:05:02] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [09/May/2023 08:10:02] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=23, self.factor=0.43541661550691446, self.count=47433 

self.closeSec=1683590999, self.tradeDate='20230509', self.openTime='080500', self.closeTime='080959', self.symbol='BTCUSDT', self.open=27639.6, self.close=27615.2, self.high=27641.6, self.low=27612.6 

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=23, self.factor=0.43541661550691446, self.count=47434 

self.closeSec=1683591299, self.tradeDate='20230509', self.openTime='081000', self.closeTime='081459', self.symbol='BTCUSDT', self.open=27615.1, self.close=27619.0, self.high=27624.7, self.low=27606.8 
127.0.0.1 - - [09/May/2023 08:15:02] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=23, self.factor=0.43541661550691446, self.count=47435 

self.closeSec=1683591599, self.tradeDate='20230509', self.openTime='081500', self.closeTime='081959', self.symbol='BTCUSDT', self.open=27618.9, self.close=27620.9, self.high=27629.6, self.low=27609.3 
127.0.0.1 - - [09/May/2023 08:20:02] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=23, self.factor=0.43541661550691446, self.count=47436 

self.closeSec=1683591899, self.tradeDate='20230509', self.openTime='082000', self.closeTime='082459', self.symbol='BTCUSDT', self.open=27620.9, self.close=27616.0, self.high=27627.1, self.low=27566.2 
127.0.0.1 - - [09/May/2023 08:25:02] "POST / HTTP/1.1" 200 -


## /root/FIL/strategy/logic/log.txt ----- -----

2023-05-09 08:00:24,455:DEBUG:logic:main.py:463:getModel:885513: df_s.iloc[-5:,:] :
          date closeTime     open  ...    alpha58   alpha67   alpha72
5769  20230509    052959  27519.1  ...  49.166667  0.372413  0.814511
5770  20230509    055959  27480.5  ...  49.166667  0.382048  0.808917
5771  20230509    062959  27531.2  ...  49.166667  0.392670  0.800081
5772  20230509    065959  27587.8  ...  49.583333  0.402064  0.787964
5773  20230509    072959  27638.1  ...  50.000000  0.405231  0.775033

[5 rows x 33 columns]
0.5481481481481482
acc is : 0.5481481481481482
2023-05-09 08:00:24,579:INFO:logic:main.py:468:getModel:885513: df_pred.iloc[-5:,:] :
     pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
535     0  0.509185  0.490815       1  ...  0.972954  -1.0    0.0  0.940193
536     0  0.526690  0.473310       1  ...  0.970953  -1.0    0.0  0.942126
537     0  0.544132  0.455868       1  ...  0.969169  -1.0    0.0  0.943857
538     0  0.536663  0.463337       1  ...  0.968569  -1.0    0.0  0.944441
539     0  0.527477  0.472523       1  ...  0.968422  -1.0    0.0  0.944585

[5 rows x 10 columns]
2023-05-09 08:00:24,614:INFO:logic:main.py:478:getModel:885513: df_panel.iloc[-5:,:] :
    pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
45     0  0.509937  0.490063       1  ...  0.972954  -1.0    0.0  0.944898
46     0  0.526915  0.473085       1  ...  0.970953  -1.0    0.0  0.947305
47     0  0.544787  0.455213       1  ...  0.969169  -1.0    0.0  0.949092
48     0  0.536393  0.463607       1  ...  0.968569  -1.0    0.0  0.945529
49     0  0.527477  0.472523       1  ...  0.968422  -1.0    0.0  0.944585

[5 rows x 10 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': []}


## /root/FIL/strategy/modifiedmom/log.txt ----- -----


--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=23713 

self.closeSec=1683588599, self.tradeDate='20230509', self.openTime='072000', self.closeTime='072959', self.symbol='BTCUSDT', self.open='27604', self.close='27655.6'
127.0.0.1 - - [09/May/2023 07:30:03] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [09/May/2023 07:40:02] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=23714 

self.closeSec=1683589199, self.tradeDate='20230509', self.openTime='073000', self.closeTime='073959', self.symbol='BTCUSDT', self.open='27655.7', self.close='27634.1'
127.0.0.1 - - [09/May/2023 07:50:02] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=23715 

self.closeSec=1683589799, self.tradeDate='20230509', self.openTime='074000', self.closeTime='074959', self.symbol='BTCUSDT', self.open='27634.1', self.close='27637.6'

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=23716 

self.closeSec=1683590399, self.tradeDate='20230509', self.openTime='075000', self.closeTime='075959', self.symbol='BTCUSDT', self.open='27637.6', self.close='27659.8'
127.0.0.1 - - [09/May/2023 08:00:03] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=23717 

self.closeSec=1683590999, self.tradeDate='20230509', self.openTime='080000', self.closeTime='080959', self.symbol='BTCUSDT', self.open='27659.8', self.close='27615.2'
127.0.0.1 - - [09/May/2023 08:10:02] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=23718 

self.closeSec=1683591599, self.tradeDate='20230509', self.openTime='081000', self.closeTime='081959', self.symbol='BTCUSDT', self.open='27615.1', self.close='27620.9'
127.0.0.1 - - [09/May/2023 08:20:05] "POST / HTTP/1.1" 200 -


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


--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=23714 

self.closeSec=1683588599, self.tradeDate='20230509', self.openTime='072000', self.closeTime='072959', self.symbol='BTCUSDT', self.open='27604', self.close='27655.6'
127.0.0.1 - - [09/May/2023 07:30:03] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [09/May/2023 07:40:02] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=23715 

self.closeSec=1683589199, self.tradeDate='20230509', self.openTime='073000', self.closeTime='073959', self.symbol='BTCUSDT', self.open='27655.7', self.close='27634.1'
127.0.0.1 - - [09/May/2023 07:50:02] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=23716 

self.closeSec=1683589799, self.tradeDate='20230509', self.openTime='074000', self.closeTime='074959', self.symbol='BTCUSDT', self.open='27634.1', self.close='27637.6'
127.0.0.1 - - [09/May/2023 08:00:03] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=23717 

self.closeSec=1683590399, self.tradeDate='20230509', self.openTime='075000', self.closeTime='075959', self.symbol='BTCUSDT', self.open='27637.6', self.close='27659.8'

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=23718 

self.closeSec=1683590999, self.tradeDate='20230509', self.openTime='080000', self.closeTime='080959', self.symbol='BTCUSDT', self.open='27659.8', self.close='27615.2'
127.0.0.1 - - [09/May/2023 08:10:02] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=23719 

self.closeSec=1683591599, self.tradeDate='20230509', self.openTime='081000', self.closeTime='081959', self.symbol='BTCUSDT', self.open='27615.1', self.close='27620.9'
127.0.0.1 - - [09/May/2023 08:20:05] "POST / HTTP/1.1" 200 -


## /root/FIL/strategy/similarity/log.txt ----- -----


--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=23714 

self.closeSec=1683588599, self.tradeDate='20230509', self.openTime='072000', self.closeTime='072959', self.symbol='BTCUSDT', self.open='27604', self.close='27655.6'
127.0.0.1 - - [09/May/2023 07:30:03] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [09/May/2023 07:40:02] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=23715 

self.closeSec=1683589199, self.tradeDate='20230509', self.openTime='073000', self.closeTime='073959', self.symbol='BTCUSDT', self.open='27655.7', self.close='27634.1'

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=23716 

self.closeSec=1683589799, self.tradeDate='20230509', self.openTime='074000', self.closeTime='074959', self.symbol='BTCUSDT', self.open='27634.1', self.close='27637.6'
127.0.0.1 - - [09/May/2023 07:50:02] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [09/May/2023 08:00:03] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=23717 

self.closeSec=1683590399, self.tradeDate='20230509', self.openTime='075000', self.closeTime='075959', self.symbol='BTCUSDT', self.open='27637.6', self.close='27659.8'

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=23718 

self.closeSec=1683590999, self.tradeDate='20230509', self.openTime='080000', self.closeTime='080959', self.symbol='BTCUSDT', self.open='27659.8', self.close='27615.2'
127.0.0.1 - - [09/May/2023 08:10:02] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=23719 

self.closeSec=1683591599, self.tradeDate='20230509', self.openTime='081000', self.closeTime='081959', self.symbol='BTCUSDT', self.open='27615.1', self.close='27620.9'
127.0.0.1 - - [09/May/2023 08:20:05] "POST / HTTP/1.1" 200 -


## /root/FIL/strategy/sr_min/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=0, self.total=1000000.0, self.flagDict['side']='', self.tradeCount=0, self.count=42867
self.closeSec=1683591599, self.tradeDate='20230509', self.openTime='081500', self.closeTime='081959', self.symbol='BTCUSDT', self.open=27618.9, self.close=27620.9, self.high=27629.6, self.low=27609.3, self.vol=395.757, self.amt=10931258.5754 
127.0.0.1 - - [09/May/2023 08:20:02] "POST / HTTP/1.1" 200 -
2023-05-09 08:20:06,291:INFO:sr_min:main.py:172:handleKline:449472: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5855  20230509   075500    075959  ...         0.0        0.0       0
5856  20230509   080000    080459  ...         0.0        0.0       0
5857  20230509   080500    080959  ...         0.0        0.0       0
5858  20230509   081000    081459  ...         0.0        0.0       0
5859  20230509   081500    081959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-05-09 08:20:06,314:INFO:sr_min:main.py:175:handleKline:449472: self.closeSec=1683591599, self.tradeDate='20230509', self.openTime='081500', self.closeTime='081959',self.symbol='BTCUSDT',self.open=27618.9, self.close=27620.9, self.high=27629.6, self.low=27609.3, self.vol=395.757, self.amt=10931258.5754, ukdf['pct'].iloc[-1]=6.9e-05 , ukdf['amount'].iloc[-1]=10931258.5754, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5859, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': []}
type(curSign)=<class 'int'>, curSign=0, self.sign=0
127.0.0.1 - - [09/May/2023 08:25:02] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=0, self.total=1000000.0, self.flagDict['side']='', self.tradeCount=0, self.count=42868
self.closeSec=1683591899, self.tradeDate='20230509', self.openTime='082000', self.closeTime='082459', self.symbol='BTCUSDT', self.open=27620.9, self.close=27616.0, self.high=27627.1, self.low=27566.2, self.vol=1405.172, self.amt=38779332.8597 
2023-05-09 08:25:02,098:INFO:sr_min:main.py:172:handleKline:449472: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5856  20230509   080000    080459  ...         0.0        0.0       0
5857  20230509   080500    080959  ...         0.0        0.0       0
5858  20230509   081000    081459  ...         0.0        0.0       0
5859  20230509   081500    081959  ...         0.0        0.0       0
5860  20230509   082000    082459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-05-09 08:25:02,099:INFO:sr_min:main.py:175:handleKline:449472: self.closeSec=1683591899, self.tradeDate='20230509', self.openTime='082000', self.closeTime='082459',self.symbol='BTCUSDT',self.open=27620.9, self.close=27616.0, self.high=27627.1, self.low=27566.2, self.vol=1405.172, self.amt=38779332.8597, ukdf['pct'].iloc[-1]=-0.000177 , ukdf['amount'].iloc[-1]=38779332.8597, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5860, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': []}
type(curSign)=<class 'int'>, curSign=0, self.sign=0


## /root/FIL/strategy/s_rsrs/log.txt ----- -----

719  20230508   200000    235959  1683561599  ...    719  0.588915  0.176150     NaN
720  20230509   000000    035959  1683575999  ...    720  0.604776  0.247013     NaN

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '46.718', 'enterprice': '29341.3', 'countrevence': '0', 'unrealprofit': '94762.7912', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '27312.9', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-9223372036854775808, self.sign=-1
--handleKline--:  version='2.0.0', self.name='s_rsrs', self.symbol='BTCUSDT', interval='4h', intervalSec=14400, wid=25, thd=0.6, self.sign=-1, self.total=1369396.0865466, self.flagDict['side']='sell', self.tradeCount=33, self.count=988
self.closeSec=1683590399, self.tradeDate='20230509', self.openTime='040000', self.closeTime='075959', self.symbol='BTCUSDT', self.open=27329.0, self.close=27659.8, self.high=27686.5, self.low=27250.0, self.vol=65257.965, self.amt=1794462393.31238 
127.0.0.1 - - [09/May/2023 08:00:03] "POST / HTTP/1.1" 200 -
2023-05-09 08:00:03,171:INFO:s_rsrs:main.py:141:handleKline:185271: self.closeSec=1683590399, self.tradeDate='20230509', self.openTime='040000', self.closeTime='075959',self.symbol='BTCUSDT',self.open=27329.0, self.close=27659.8, self.high=27686.5, self.low=27250.0, self.vol=65257.965, self.amt=1794462393.31238 
2023-05-09 08:00:03,199:INFO:s_rsrs:main.py:142:handleKline:185271: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime  ...         vol           amt       pct
717  20230508   120000    155959  ...   82354.151  2.312412e+09 -0.008167
718  20230508   160000    195959  ...  108980.277  3.032535e+09 -0.001273
719  20230508   200000    235959  ...  110121.512  3.068481e+09 -0.001723
720  20230509   000000    035959  ...  148637.520  4.091222e+09 -0.019552
721  20230509   040000    075959  ...   65257.965  1.794462e+09  0.012101

[5 rows x 11 columns]
2023-05-09 08:00:04,392:INFO:s_rsrs:main.py:151:handleKline:185271: df_s.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec  ...  index      beta    zscore  signal
717  20230508   120000    155959  1683532799  ...    717  0.391871 -0.483625     NaN
718  20230508   160000    195959  1683547199  ...    718  0.529717 -0.031896     NaN
719  20230508   200000    235959  1683561599  ...    719  0.588915  0.176150     NaN
720  20230509   000000    035959  1683575999  ...    720  0.604776  0.247013     NaN
721  20230509   040000    075959  1683590399  ...    721  0.663889  0.466367     NaN

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '46.718', 'enterprice': '29341.3', 'countrevence': '0', 'unrealprofit': '78500.2554', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '27661', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-9223372036854775808, self.sign=-1


