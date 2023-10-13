# 20231014 00:26:02

## /root/FIL/strategy/amihud/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=373746.4768026, self.flagDict['side']='sell', self.tradeCount=2, self.count=43924
self.closeSec=1697213999, self.tradeDate='20231014', self.openTime='001500', self.closeTime='001959', self.symbol='BTCUSDT', self.open=26727.6, self.close=26736.8, self.high=26748.2, self.low=26727.6, self.vol=564.211, self.amt=15086421.8835 
127.0.0.1 - - [14/Oct/2023 00:20:09] "POST / HTTP/1.1" 200 -
2023-10-14 00:20:15,762:INFO:amihud:main.py:172:handleKline:2219019: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5759  20231013   235500    235959  ...         0.0        0.0       0
5760  20231014   000000    000459  ...         0.0        0.0       0
5761  20231014   000500    000959  ...         0.0        0.0       0
5762  20231014   001000    001459  ...         0.0        0.0       0
5763  20231014   001500    001959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-10-14 00:20:15,792:INFO:amihud:main.py:175:handleKline:2219019: self.closeSec=1697213999, self.tradeDate='20231014', self.openTime='001500', self.closeTime='001959',self.symbol='BTCUSDT',self.open=26727.6, self.close=26736.8, self.high=26748.2, self.low=26727.6, self.vol=564.211, self.amt=15086421.8835, ukdf['pct'].iloc[-1]=0.00034 , ukdf['amount'].iloc[-1]=15086421.8835, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5763, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '13.926', 'enterprice': '26864.9', 'countrevence': '0', 'unrealprofit': '1752.64571160954', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '26739.04579121', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1
--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=373746.4768026, self.flagDict['side']='sell', self.tradeCount=2, self.count=43925
self.closeSec=1697214299, self.tradeDate='20231014', self.openTime='002000', self.closeTime='002459', self.symbol='BTCUSDT', self.open=26736.9, self.close=26759.0, self.high=26764.0, self.low=26736.8, self.vol=661.275, self.amt=17691088.13 
127.0.0.1 - - [14/Oct/2023 00:25:01] "POST / HTTP/1.1" 200 -
2023-10-14 00:25:03,041:INFO:amihud:main.py:172:handleKline:2219019: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5760  20231014   000000    000459  ...         0.0        0.0       0
5761  20231014   000500    000959  ...         0.0        0.0       0
5762  20231014   001000    001459  ...         0.0        0.0       0
5763  20231014   001500    001959  ...         0.0        0.0       0
5764  20231014   002000    002459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-10-14 00:25:03,046:INFO:amihud:main.py:175:handleKline:2219019: self.closeSec=1697214299, self.tradeDate='20231014', self.openTime='002000', self.closeTime='002459',self.symbol='BTCUSDT',self.open=26736.9, self.close=26759.0, self.high=26764.0, self.low=26736.8, self.vol=661.275, self.amt=17691088.13, ukdf['pct'].iloc[-1]=0.00083 , ukdf['amount'].iloc[-1]=17691088.13, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5764, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '13.926', 'enterprice': '26864.9', 'countrevence': '0', 'unrealprofit': '1447.28400976566', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '26760.97324359', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1


## /root/FIL/strategy/factorcheck/log.txt ----- -----

127.0.0.1 - - [14/Oct/2023 00:05:00] "POST / HTTP/1.1" 200 -

--ukdf-hist--: overDate='20231009' 
 Empty DataFrame
Columns: [tradeDate, openTime, closeTime, closeSec, open, close, high, low, pct, index, idx]
Index: [] 
 Empty DataFrame
Columns: [tradeDate, openTime, closeTime, closeSec, open, close, high, low, pct, index, idx]
Index: [] 

127.0.0.1 - - [14/Oct/2023 00:10:00] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.714181719035411, self.count=43924 

self.closeSec=1697213399, self.tradeDate='20231014', self.openTime='000500', self.closeTime='000959', self.symbol='BTCUSDT', self.open=26700.2, self.close=26726.3, self.high=26737.5, self.low=26700.1 

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.714181719035411, self.count=43925 

self.closeSec=1697213699, self.tradeDate='20231014', self.openTime='001000', self.closeTime='001459', self.symbol='BTCUSDT', self.open=26726.3, self.close=26727.7, self.high=26732.4, self.low=26721.9 
127.0.0.1 - - [14/Oct/2023 00:15:00] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.714181719035411, self.count=43926 

self.closeSec=1697213999, self.tradeDate='20231014', self.openTime='001500', self.closeTime='001959', self.symbol='BTCUSDT', self.open=26727.6, self.close=26736.8, self.high=26748.2, self.low=26727.6 
127.0.0.1 - - [14/Oct/2023 00:20:08] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.714181719035411, self.count=43927 

self.closeSec=1697214299, self.tradeDate='20231014', self.openTime='002000', self.closeTime='002459', self.symbol='BTCUSDT', self.open=26736.9, self.close=26759.0, self.high=26764.0, self.low=26736.8 
127.0.0.1 - - [14/Oct/2023 00:25:01] "POST / HTTP/1.1" 200 -


## /root/FIL/strategy/logic/log.txt ----- -----

2023-10-14 00:00:18,862:DEBUG:logic:main.py:463:getModel:2218526: df_s.iloc[-5:,:] :
          date closeTime     open  ...    alpha58   alpha67   alpha72
5801  20231013    212959  26920.1  ...  48.750000  0.499691  0.312243
5802  20231013    215959  26867.0  ...  48.333333  0.491934  0.313982
5803  20231013    222959  26843.0  ...  48.333333  0.476050  0.327416
5804  20231013    225959  26784.8  ...  47.916667  0.463852  0.347899
5805  20231013    232959  26745.3  ...  47.916667  0.458073  0.378648

[5 rows x 33 columns]
0.5533088235294118
acc is : 0.5533088235294118
2023-10-14 00:00:18,927:INFO:logic:main.py:468:getModel:2218526: df_pred.iloc[-5:,:] :
     pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
539     1  0.489327  0.510673       0  ...  0.995458  -1.0    0.0  0.948466
540     1  0.490897  0.509103       0  ...  0.997442  -1.0    0.0  0.946576
541     1  0.479337  0.520663       0  ...  0.999032  -1.0    0.0  0.945067
542     1  0.475825  0.524175       0  ...  0.999801  -1.0    0.0  0.944339
543     1  0.475006  0.524994       0  ...  1.000995  -1.0    0.0  0.943212

[5 rows x 10 columns]
2023-10-14 00:00:18,938:INFO:logic:main.py:478:getModel:2218526: df_panel.iloc[-5:,:] :
    pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
45     1  0.489644  0.510356       0  ...  0.999601  -1.0    0.0  0.957459
46     1  0.491258  0.508742       0  ...  1.001593  -1.0    0.0  0.953771
47     1  0.479347  0.520653       0  ...  1.003190  -1.0    0.0  0.948997
48     1  0.475957  0.524043       0  ...  1.003962  -1.0    0.0  0.948266
49     1  0.475006  0.524994       0  ...  1.000995  -1.0    0.0  0.943212

[5 rows x 10 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '24.051', 'enterprice': '26768.8', 'countrevence': '0', 'unrealprofit': '1836.88010418846', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '26692.42562454', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}


## /root/FIL/strategy/modifiedmom/log.txt ----- -----

127.0.0.1 - - [13/Oct/2023 23:30:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=21959 

self.closeSec=1697210999, self.tradeDate='20231013', self.openTime='232000', self.closeTime='232959', self.symbol='BTCUSDT', self.open='26764.1', self.close='26724.8'
127.0.0.1 - - [13/Oct/2023 23:40:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=21960 

self.closeSec=1697211599, self.tradeDate='20231013', self.openTime='233000', self.closeTime='233959', self.symbol='BTCUSDT', self.open='26721.9', self.close='26707.6'
127.0.0.1 - - [13/Oct/2023 23:50:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=21961 

self.closeSec=1697212199, self.tradeDate='20231013', self.openTime='234000', self.closeTime='234959', self.symbol='BTCUSDT', self.open='26707.5', self.close='26695.1'
127.0.0.1 - - [14/Oct/2023 00:00:02] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=21962 

self.closeSec=1697212799, self.tradeDate='20231013', self.openTime='235000', self.closeTime='235959', self.symbol='BTCUSDT', self.open='26695', self.close='26692.9'

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=21963 

self.closeSec=1697213399, self.tradeDate='20231014', self.openTime='000000', self.closeTime='000959', self.symbol='BTCUSDT', self.open='26692.9', self.close='26726.3'
127.0.0.1 - - [14/Oct/2023 00:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=21964 

self.closeSec=1697213999, self.tradeDate='20231014', self.openTime='001000', self.closeTime='001959', self.symbol='BTCUSDT', self.open='26726.3', self.close='26736.8'
127.0.0.1 - - [14/Oct/2023 00:20:11] "POST / HTTP/1.1" 200 -


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

127.0.0.1 - - [13/Oct/2023 23:30:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=21962 

self.closeSec=1697210999, self.tradeDate='20231013', self.openTime='232000', self.closeTime='232959', self.symbol='BTCUSDT', self.open='26764.1', self.close='26724.8'
127.0.0.1 - - [13/Oct/2023 23:40:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=21963 

self.closeSec=1697211599, self.tradeDate='20231013', self.openTime='233000', self.closeTime='233959', self.symbol='BTCUSDT', self.open='26721.9', self.close='26707.6'
127.0.0.1 - - [13/Oct/2023 23:50:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=21964 

self.closeSec=1697212199, self.tradeDate='20231013', self.openTime='234000', self.closeTime='234959', self.symbol='BTCUSDT', self.open='26707.5', self.close='26695.1'

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=21965 

self.closeSec=1697212799, self.tradeDate='20231013', self.openTime='235000', self.closeTime='235959', self.symbol='BTCUSDT', self.open='26695', self.close='26692.9'
127.0.0.1 - - [14/Oct/2023 00:00:02] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [14/Oct/2023 00:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=21966 

self.closeSec=1697213399, self.tradeDate='20231014', self.openTime='000000', self.closeTime='000959', self.symbol='BTCUSDT', self.open='26692.9', self.close='26726.3'

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=21967 

self.closeSec=1697213999, self.tradeDate='20231014', self.openTime='001000', self.closeTime='001959', self.symbol='BTCUSDT', self.open='26726.3', self.close='26736.8'
127.0.0.1 - - [14/Oct/2023 00:20:11] "POST / HTTP/1.1" 200 -


## /root/FIL/strategy/similarity/log.txt ----- -----

127.0.0.1 - - [13/Oct/2023 23:30:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=21962 

self.closeSec=1697210999, self.tradeDate='20231013', self.openTime='232000', self.closeTime='232959', self.symbol='BTCUSDT', self.open='26764.1', self.close='26724.8'

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=21963 

self.closeSec=1697211599, self.tradeDate='20231013', self.openTime='233000', self.closeTime='233959', self.symbol='BTCUSDT', self.open='26721.9', self.close='26707.6'
127.0.0.1 - - [13/Oct/2023 23:40:01] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [13/Oct/2023 23:50:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=21964 

self.closeSec=1697212199, self.tradeDate='20231013', self.openTime='234000', self.closeTime='234959', self.symbol='BTCUSDT', self.open='26707.5', self.close='26695.1'

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=21965 

self.closeSec=1697212799, self.tradeDate='20231013', self.openTime='235000', self.closeTime='235959', self.symbol='BTCUSDT', self.open='26695', self.close='26692.9'
127.0.0.1 - - [14/Oct/2023 00:00:02] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [14/Oct/2023 00:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=21966 

self.closeSec=1697213399, self.tradeDate='20231014', self.openTime='000000', self.closeTime='000959', self.symbol='BTCUSDT', self.open='26692.9', self.close='26726.3'

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=21967 

self.closeSec=1697213999, self.tradeDate='20231014', self.openTime='001000', self.closeTime='001959', self.symbol='BTCUSDT', self.open='26726.3', self.close='26736.8'
127.0.0.1 - - [14/Oct/2023 00:20:11] "POST / HTTP/1.1" 200 -


## /root/FIL/strategy/sr_min/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=1, self.total=996015.990996, self.flagDict['side']='buy', self.tradeCount=1, self.count=43924
self.closeSec=1697213999, self.tradeDate='20231014', self.openTime='001500', self.closeTime='001959', self.symbol='BTCUSDT', self.open=26727.6, self.close=26736.8, self.high=26748.2, self.low=26727.6, self.vol=564.211, self.amt=15086421.8835 
127.0.0.1 - - [14/Oct/2023 00:20:09] "POST / HTTP/1.1" 200 -
2023-10-14 00:20:15,762:INFO:sr_min:main.py:172:handleKline:2219263: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5759  20231013   235500    235959  ...         0.0        0.0       0
5760  20231014   000000    000459  ...         0.0        0.0       0
5761  20231014   000500    000959  ...         0.0        0.0       0
5762  20231014   001000    001459  ...         0.0        0.0       0
5763  20231014   001500    001959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-10-14 00:20:15,792:INFO:sr_min:main.py:175:handleKline:2219263: self.closeSec=1697213999, self.tradeDate='20231014', self.openTime='001500', self.closeTime='001959',self.symbol='BTCUSDT',self.open=26727.6, self.close=26736.8, self.high=26748.2, self.low=26727.6, self.vol=564.211, self.amt=15086421.8835, ukdf['pct'].iloc[-1]=0.00034 , ukdf['amount'].iloc[-1]=15086421.8835, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5763, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '37.141', 'enterprice': '26844', 'countrevence': '0', 'unrealprofit': '-3896.35333570613', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '26739.09293407', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=1
--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=1, self.total=996015.990996, self.flagDict['side']='buy', self.tradeCount=1, self.count=43925
self.closeSec=1697214299, self.tradeDate='20231014', self.openTime='002000', self.closeTime='002459', self.symbol='BTCUSDT', self.open=26736.9, self.close=26759.0, self.high=26764.0, self.low=26736.8, self.vol=661.275, self.amt=17691088.13 
127.0.0.1 - - [14/Oct/2023 00:25:01] "POST / HTTP/1.1" 200 -
2023-10-14 00:25:03,040:INFO:sr_min:main.py:172:handleKline:2219263: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5760  20231014   000000    000459  ...         0.0        0.0       0
5761  20231014   000500    000959  ...         0.0        0.0       0
5762  20231014   001000    001459  ...         0.0        0.0       0
5763  20231014   001500    001959  ...         0.0        0.0       0
5764  20231014   002000    002459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-10-14 00:25:03,046:INFO:sr_min:main.py:175:handleKline:2219263: self.closeSec=1697214299, self.tradeDate='20231014', self.openTime='002000', self.closeTime='002459',self.symbol='BTCUSDT',self.open=26736.9, self.close=26759.0, self.high=26764.0, self.low=26736.8, self.vol=661.275, self.amt=17691088.13, ukdf['pct'].iloc[-1]=0.00083 , ukdf['amount'].iloc[-1]=17691088.13, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5764, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '37.141', 'enterprice': '26844', 'countrevence': '0', 'unrealprofit': '-3083.69675982381', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '26760.97324359', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=1


## /root/FIL/strategy/s_rsrs/log.txt ----- -----

723  20231013   120000    155959  1697183999  ...    723  0.855994  0.822502     1.0
724  20231013   160000    195959  1697198399  ...    724  0.903855  0.938535     1.0

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '47.147', 'enterprice': '26826.9', 'countrevence': '0', 'unrealprofit': '-622.3404', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '26813.7', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=1, self.sign=1
127.0.0.1 - - [14/Oct/2023 00:00:01] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='s_rsrs', self.symbol='BTCUSDT', interval='4h', intervalSec=14400, wid=25, thd=0.6, self.sign=1, self.total=1263543.0464457, self.flagDict['side']='buy', self.tradeCount=33, self.count=915
self.closeSec=1697212799, self.tradeDate='20231013', self.openTime='200000', self.closeTime='235959', self.symbol='BTCUSDT', self.open=26810.0, self.close=26692.9, self.high=26972.8, self.low=26670.1, self.vol=52873.068, self.amt=1417818001.6707 
2023-10-14 00:00:01,587:INFO:s_rsrs:main.py:141:handleKline:2218689: self.closeSec=1697212799, self.tradeDate='20231013', self.openTime='200000', self.closeTime='235959',self.symbol='BTCUSDT',self.open=26810.0, self.close=26692.9, self.high=26972.8, self.low=26670.1, self.vol=52873.068, self.amt=1417818001.6707 
2023-10-14 00:00:01,603:INFO:s_rsrs:main.py:142:handleKline:2218689: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime  ...        vol           amt       pct
721  20231013   040000    075959  ...  15277.367  4.083113e+08  0.001640
722  20231013   080000    115959  ...  24000.376  6.432579e+08  0.000950
723  20231013   120000    155959  ...  22522.718  6.045876e+08  0.003422
724  20231013   160000    195959  ...  25997.959  6.966675e+08 -0.001902
725  20231013   200000    235959  ...  52873.068  1.417818e+09 -0.004368

[5 rows x 11 columns]
2023-10-14 00:00:02,515:INFO:s_rsrs:main.py:151:handleKline:2218689: df_s.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec  ...  index      beta    zscore  signal
721  20231013   040000    075959  1697155199  ...    721  0.822618  0.766006     1.0
722  20231013   080000    115959  1697169599  ...    722  0.843884  0.807063     1.0
723  20231013   120000    155959  1697183999  ...    723  0.855994  0.822502     1.0
724  20231013   160000    195959  1697198399  ...    724  0.903855  0.938535     1.0
725  20231013   200000    235959  1697212799  ...    725  0.846559  0.756405     1.0

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '47.147', 'enterprice': '26826.9', 'countrevence': '0', 'unrealprofit': '-6101.15295157007', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '26697.49297619', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=1, self.sign=1


