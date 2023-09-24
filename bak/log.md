# 20230924 08:26:02

## /root/FIL/strategy/amihud/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=373746.4768026, self.flagDict['side']='sell', self.tradeCount=2, self.count=38260
self.closeSec=1695514799, self.tradeDate='20230924', self.openTime='081500', self.closeTime='081959', self.symbol='BTCUSDT', self.open=26559.4, self.close=26557.5, self.high=26559.5, self.low=26555.3, self.vol=98.446, self.amt=2614413.5278 
127.0.0.1 - - [24/Sep/2023 08:20:02] "POST / HTTP/1.1" 200 -
2023-09-24 08:20:05,794:INFO:amihud:main.py:172:handleKline:2219019: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5855  20230924   075500    075959  ...         0.0        0.0       0
5856  20230924   080000    080459  ...         0.0        0.0       0
5857  20230924   080500    080959  ...         0.0        0.0       0
5858  20230924   081000    081459  ...         0.0        0.0       0
5859  20230924   081500    081959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-09-24 08:20:05,798:INFO:amihud:main.py:175:handleKline:2219019: self.closeSec=1695514799, self.tradeDate='20230924', self.openTime='081500', self.closeTime='081959',self.symbol='BTCUSDT',self.open=26559.4, self.close=26557.5, self.high=26559.5, self.low=26555.3, self.vol=98.446, self.amt=2614413.5278, ukdf['pct'].iloc[-1]=-7.5e-05 , ukdf['amount'].iloc[-1]=2614413.5278, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5859, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '13.926', 'enterprice': '26864.9', 'countrevence': '0', 'unrealprofit': '4280.8524', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '26557.5', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1
--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=373746.4768026, self.flagDict['side']='sell', self.tradeCount=2, self.count=38261
self.closeSec=1695515099, self.tradeDate='20230924', self.openTime='082000', self.closeTime='082459', self.symbol='BTCUSDT', self.open=26557.5, self.close=26557.0, self.high=26559.8, self.low=26556.9, self.vol=86.588, self.amt=2299695.894 
127.0.0.1 - - [24/Sep/2023 08:25:00] "POST / HTTP/1.1" 200 -
2023-09-24 08:25:00,780:INFO:amihud:main.py:172:handleKline:2219019: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5856  20230924   080000    080459  ...         0.0        0.0       0
5857  20230924   080500    080959  ...         0.0        0.0       0
5858  20230924   081000    081459  ...         0.0        0.0       0
5859  20230924   081500    081959  ...         0.0        0.0       0
5860  20230924   082000    082459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-09-24 08:25:00,780:INFO:amihud:main.py:175:handleKline:2219019: self.closeSec=1695515099, self.tradeDate='20230924', self.openTime='082000', self.closeTime='082459',self.symbol='BTCUSDT',self.open=26557.5, self.close=26557.0, self.high=26559.8, self.low=26556.9, self.vol=86.588, self.amt=2299695.894, ukdf['pct'].iloc[-1]=-1.9e-05 , ukdf['amount'].iloc[-1]=2299695.894, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5860, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '13.926', 'enterprice': '26864.9', 'countrevence': '0', 'unrealprofit': '4257.01894198548', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '26559.21143602', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1


## /root/FIL/strategy/factorcheck/log.txt ----- -----

127.0.0.1 - - [24/Sep/2023 08:00:00] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.714181719035411, self.count=38258 

self.closeSec=1695513599, self.tradeDate='20230924', self.openTime='075500', self.closeTime='075959', self.symbol='BTCUSDT', self.open=26563.8, self.close=26563.0, self.high=26563.8, self.low=26563.0 
127.0.0.1 - - [24/Sep/2023 08:05:00] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.714181719035411, self.count=38259 

self.closeSec=1695513899, self.tradeDate='20230924', self.openTime='080000', self.closeTime='080459', self.symbol='BTCUSDT', self.open=26563.0, self.close=26558.7, self.high=26563.1, self.low=26555.8 

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.714181719035411, self.count=38260 

self.closeSec=1695514199, self.tradeDate='20230924', self.openTime='080500', self.closeTime='080959', self.symbol='BTCUSDT', self.open=26558.6, self.close=26558.9, self.high=26561.0, self.low=26558.6 
127.0.0.1 - - [24/Sep/2023 08:10:00] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.714181719035411, self.count=38261 

self.closeSec=1695514499, self.tradeDate='20230924', self.openTime='081000', self.closeTime='081459', self.symbol='BTCUSDT', self.open=26558.9, self.close=26559.5, self.high=26559.5, self.low=26556.1 
127.0.0.1 - - [24/Sep/2023 08:15:00] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.714181719035411, self.count=38262 

self.closeSec=1695514799, self.tradeDate='20230924', self.openTime='081500', self.closeTime='081959', self.symbol='BTCUSDT', self.open=26559.4, self.close=26557.5, self.high=26559.5, self.low=26555.3 
127.0.0.1 - - [24/Sep/2023 08:20:01] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [24/Sep/2023 08:25:00] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.714181719035411, self.count=38263 

self.closeSec=1695515099, self.tradeDate='20230924', self.openTime='082000', self.closeTime='082459', self.symbol='BTCUSDT', self.open=26557.5, self.close=26557.0, self.high=26559.8, self.low=26556.9 


## /root/FIL/strategy/logic/log.txt ----- -----

2023-09-24 08:00:17,279:DEBUG:logic:main.py:463:getModel:2218526: df_s.iloc[-5:,:] :
          date closeTime     open  ...    alpha58   alpha67   alpha72
5769  20230924    052959  26572.6  ...  45.416667  0.482694  0.369979
5770  20230924    055959  26581.6  ...  45.000000  0.469377  0.380101
5771  20230924    062959  26553.6  ...  45.416667  0.474240  0.384771
5772  20230924    065959  26562.8  ...  45.000000  0.468008  0.395932
5773  20230924    072959  26549.7  ...  45.416667  0.470123  0.404323

[5 rows x 33 columns]
0.5388888888888889
acc is : 0.5388888888888889
2023-09-24 08:00:17,341:INFO:logic:main.py:468:getModel:2218526: df_pred.iloc[-5:,:] :
     pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
535     1  0.496459  0.503541       0  ...  0.936346  -1.0    0.0  1.025584
536     1  0.486145  0.513855       1  ...  0.936022  -1.0    0.0  1.025939
537     1  0.496261  0.503739       0  ...  0.936483  -1.0    0.0  1.025433
538     1  0.490613  0.509387       1  ...  0.936346  -1.0    0.0  1.025584
539     1  0.495542  0.504458       1  ...  0.936014  -1.0    0.0  1.025947

[5 rows x 10 columns]
2023-09-24 08:00:17,352:INFO:logic:main.py:478:getModel:2218526: df_panel.iloc[-5:,:] :
    pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
45     1  0.495940  0.504060       0  ...  0.943957  -1.0    0.0  1.013794
46     1  0.485326  0.514674       1  ...  0.943630  -1.0    0.0  1.010211
47     1  0.495875  0.504125       0  ...  0.944096  -1.0    0.0  1.017140
48     1  0.490350  0.509650       1  ...  0.936346  -1.0    0.0  1.020566
49     1  0.495542  0.504458       1  ...  0.936014  -1.0    0.0  1.025947

[5 rows x 10 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '25.67', 'enterprice': '27131.4', 'countrevence': '0', 'unrealprofit': '14572.8154030988', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '26563.70169836', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}


## /root/FIL/strategy/modifiedmom/log.txt ----- -----

127.0.0.1 - - [24/Sep/2023 07:30:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=19127 

self.closeSec=1695511799, self.tradeDate='20230924', self.openTime='072000', self.closeTime='072959', self.symbol='BTCUSDT', self.open='26563.6', self.close='26553.6'
127.0.0.1 - - [24/Sep/2023 07:40:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=19128 

self.closeSec=1695512399, self.tradeDate='20230924', self.openTime='073000', self.closeTime='073959', self.symbol='BTCUSDT', self.open='26556.9', self.close='26556.6'

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=19129 

self.closeSec=1695512999, self.tradeDate='20230924', self.openTime='074000', self.closeTime='074959', self.symbol='BTCUSDT', self.open='26556.6', self.close='26555.4'
127.0.0.1 - - [24/Sep/2023 07:50:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=19130 

self.closeSec=1695513599, self.tradeDate='20230924', self.openTime='075000', self.closeTime='075959', self.symbol='BTCUSDT', self.open='26555.4', self.close='26563'
127.0.0.1 - - [24/Sep/2023 08:00:01] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [24/Sep/2023 08:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=19131 

self.closeSec=1695514199, self.tradeDate='20230924', self.openTime='080000', self.closeTime='080959', self.symbol='BTCUSDT', self.open='26563', self.close='26558.9'

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=19132 

self.closeSec=1695514799, self.tradeDate='20230924', self.openTime='081000', self.closeTime='081959', self.symbol='BTCUSDT', self.open='26558.9', self.close='26557.5'
127.0.0.1 - - [24/Sep/2023 08:20:04] "POST / HTTP/1.1" 200 -


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

127.0.0.1 - - [24/Sep/2023 07:30:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=19130 

self.closeSec=1695511799, self.tradeDate='20230924', self.openTime='072000', self.closeTime='072959', self.symbol='BTCUSDT', self.open='26563.6', self.close='26553.6'
127.0.0.1 - - [24/Sep/2023 07:40:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=19131 

self.closeSec=1695512399, self.tradeDate='20230924', self.openTime='073000', self.closeTime='073959', self.symbol='BTCUSDT', self.open='26556.9', self.close='26556.6'
127.0.0.1 - - [24/Sep/2023 07:50:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=19132 

self.closeSec=1695512999, self.tradeDate='20230924', self.openTime='074000', self.closeTime='074959', self.symbol='BTCUSDT', self.open='26556.6', self.close='26555.4'
127.0.0.1 - - [24/Sep/2023 08:00:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=19133 

self.closeSec=1695513599, self.tradeDate='20230924', self.openTime='075000', self.closeTime='075959', self.symbol='BTCUSDT', self.open='26555.4', self.close='26563'

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=19134 

self.closeSec=1695514199, self.tradeDate='20230924', self.openTime='080000', self.closeTime='080959', self.symbol='BTCUSDT', self.open='26563', self.close='26558.9'
127.0.0.1 - - [24/Sep/2023 08:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=19135 

self.closeSec=1695514799, self.tradeDate='20230924', self.openTime='081000', self.closeTime='081959', self.symbol='BTCUSDT', self.open='26558.9', self.close='26557.5'
127.0.0.1 - - [24/Sep/2023 08:20:04] "POST / HTTP/1.1" 200 -


## /root/FIL/strategy/similarity/log.txt ----- -----


--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=19130 

self.closeSec=1695511799, self.tradeDate='20230924', self.openTime='072000', self.closeTime='072959', self.symbol='BTCUSDT', self.open='26563.6', self.close='26553.6'
127.0.0.1 - - [24/Sep/2023 07:30:01] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [24/Sep/2023 07:40:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=19131 

self.closeSec=1695512399, self.tradeDate='20230924', self.openTime='073000', self.closeTime='073959', self.symbol='BTCUSDT', self.open='26556.9', self.close='26556.6'

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=19132 

self.closeSec=1695512999, self.tradeDate='20230924', self.openTime='074000', self.closeTime='074959', self.symbol='BTCUSDT', self.open='26556.6', self.close='26555.4'
127.0.0.1 - - [24/Sep/2023 07:50:01] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [24/Sep/2023 08:00:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=19133 

self.closeSec=1695513599, self.tradeDate='20230924', self.openTime='075000', self.closeTime='075959', self.symbol='BTCUSDT', self.open='26555.4', self.close='26563'
127.0.0.1 - - [24/Sep/2023 08:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=19134 

self.closeSec=1695514199, self.tradeDate='20230924', self.openTime='080000', self.closeTime='080959', self.symbol='BTCUSDT', self.open='26563', self.close='26558.9'

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=19135 

self.closeSec=1695514799, self.tradeDate='20230924', self.openTime='081000', self.closeTime='081959', self.symbol='BTCUSDT', self.open='26558.9', self.close='26557.5'
127.0.0.1 - - [24/Sep/2023 08:20:04] "POST / HTTP/1.1" 200 -


## /root/FIL/strategy/sr_min/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=1, self.total=996015.990996, self.flagDict['side']='buy', self.tradeCount=1, self.count=38260
self.closeSec=1695514799, self.tradeDate='20230924', self.openTime='081500', self.closeTime='081959', self.symbol='BTCUSDT', self.open=26559.4, self.close=26557.5, self.high=26559.5, self.low=26555.3, self.vol=98.446, self.amt=2614413.5278 
127.0.0.1 - - [24/Sep/2023 08:20:02] "POST / HTTP/1.1" 200 -
2023-09-24 08:20:05,793:INFO:sr_min:main.py:172:handleKline:2219263: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5855  20230924   075500    075959  ...         0.0        0.0       0
5856  20230924   080000    080459  ...         0.0        0.0       0
5857  20230924   080500    080959  ...         0.0        0.0       0
5858  20230924   081000    081459  ...         0.0        0.0       0
5859  20230924   081500    081959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-09-24 08:20:05,799:INFO:sr_min:main.py:175:handleKline:2219263: self.closeSec=1695514799, self.tradeDate='20230924', self.openTime='081500', self.closeTime='081959',self.symbol='BTCUSDT',self.open=26559.4, self.close=26557.5, self.high=26559.5, self.low=26555.3, self.vol=98.446, self.amt=2614413.5278, ukdf['pct'].iloc[-1]=-7.5e-05 , ukdf['amount'].iloc[-1]=2614413.5278, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5859, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '37.141', 'enterprice': '26844', 'countrevence': '0', 'unrealprofit': '-10640.8965', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '26557.5', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=1
127.0.0.1 - - [24/Sep/2023 08:25:00] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=1, self.total=996015.990996, self.flagDict['side']='buy', self.tradeCount=1, self.count=38261
self.closeSec=1695515099, self.tradeDate='20230924', self.openTime='082000', self.closeTime='082459', self.symbol='BTCUSDT', self.open=26557.5, self.close=26557.0, self.high=26559.8, self.low=26556.9, self.vol=86.588, self.amt=2299695.894 
2023-09-24 08:25:00,787:INFO:sr_min:main.py:172:handleKline:2219263: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5856  20230924   080000    080459  ...         0.0        0.0       0
5857  20230924   080500    080959  ...         0.0        0.0       0
5858  20230924   081000    081459  ...         0.0        0.0       0
5859  20230924   081500    081959  ...         0.0        0.0       0
5860  20230924   082000    082459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-09-24 08:25:00,787:INFO:sr_min:main.py:175:handleKline:2219263: self.closeSec=1695515099, self.tradeDate='20230924', self.openTime='082000', self.closeTime='082459',self.symbol='BTCUSDT',self.open=26557.5, self.close=26557.0, self.high=26559.8, self.low=26556.9, self.vol=86.588, self.amt=2299695.894, ukdf['pct'].iloc[-1]=-1.9e-05 , ukdf['amount'].iloc[-1]=2299695.894, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5860, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '37.141', 'enterprice': '26844', 'countrevence': '0', 'unrealprofit': '-10577.33205478118', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '26559.21143602', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=1


## /root/FIL/strategy/s_rsrs/log.txt ----- -----

719  20230923   200000    235959  1695484799  ...    719  1.332019  2.020627     1.0
720  20230924   000000    035959  1695499199  ...    720  1.302909  1.884848     1.0

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '50.787', 'enterprice': '27251.4', 'countrevence': '0', 'unrealprofit': '-33458.32977274755', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '26592.60287135', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=1, self.sign=1
127.0.0.1 - - [24/Sep/2023 08:00:01] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='s_rsrs', self.symbol='BTCUSDT', interval='4h', intervalSec=14400, wid=25, thd=0.6, self.sign=1, self.total=1382632.8349482, self.flagDict['side']='buy', self.tradeCount=25, self.count=797
self.closeSec=1695513599, self.tradeDate='20230924', self.openTime='040000', self.closeTime='075959', self.symbol='BTCUSDT', self.open=26594.4, self.close=26563.0, self.high=26600.0, self.low=26542.0, self.vol=7650.769, self.amt=203240734.0643 
2023-09-24 08:00:01,539:INFO:s_rsrs:main.py:141:handleKline:2218689: self.closeSec=1695513599, self.tradeDate='20230924', self.openTime='040000', self.closeTime='075959',self.symbol='BTCUSDT',self.open=26594.4, self.close=26563.0, self.high=26600.0, self.low=26542.0, self.vol=7650.769, self.amt=203240734.0643 
2023-09-24 08:00:01,558:INFO:s_rsrs:main.py:142:handleKline:2218689: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime  ...        vol           amt       pct
717  20230923   120000    155959  ...  10416.599  2.764745e+08  0.001976
718  20230923   160000    195959  ...   6701.253  1.779708e+08 -0.000339
719  20230923   200000    235959  ...   9319.372  2.474898e+08  0.000188
720  20230924   000000    035959  ...  11673.004  3.103720e+08  0.001013
721  20230924   040000    075959  ...   7650.769  2.032407e+08 -0.001181

[5 rows x 11 columns]
2023-09-24 08:00:02,306:INFO:s_rsrs:main.py:151:handleKline:2218689: df_s.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec  ...  index      beta    zscore  signal
717  20230923   120000    155959  1695455999  ...    717  1.246309  1.946445     1.0
718  20230923   160000    195959  1695470399  ...    718  1.314916  2.050083     1.0
719  20230923   200000    235959  1695484799  ...    719  1.332019  2.020627     1.0
720  20230924   000000    035959  1695499199  ...    720  1.302909  1.884848     1.0
721  20230924   040000    075959  1695513599  ...    721  1.214685  1.621132     1.0

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '50.787', 'enterprice': '27251.4', 'countrevence': '0', 'unrealprofit': '-34922.97930240306', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '26563.76380762', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=1, self.sign=1


