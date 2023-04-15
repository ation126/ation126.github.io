# 20230415 08:26:01

## /root/FIL/strategy/amihud/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=993672.4896432, self.flagDict['side']='sell', self.tradeCount=2, self.count=39957
self.closeSec=1681517999, self.tradeDate='20230415', self.openTime='081500', self.closeTime='081959', self.symbol='BTCUSDT', self.open=30430.2, self.close=30434.4, self.high=30439.4, self.low=30413.0, self.vol=462.434, self.amt=14071438.2713 
127.0.0.1 - - [15/Apr/2023 08:20:05] "POST / HTTP/1.1" 200 -
2023-04-15 08:20:07,889:INFO:amihud:main.py:172:handleKline:200676: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5848  20230415   075500    075959  ...         0.0        0.0       0
5849  20230415   080000    080459  ...         0.0        0.0       0
5850  20230415   080500    080959  ...         0.0        0.0       0
5851  20230415   081000    081459  ...         0.0        0.0       0
5852  20230415   081500    081959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-04-15 08:20:07,900:INFO:amihud:main.py:175:handleKline:200676: self.closeSec=1681517999, self.tradeDate='20230415', self.openTime='081500', self.closeTime='081959',self.symbol='BTCUSDT',self.open=30430.2, self.close=30434.4, self.high=30439.4, self.low=30413.0, self.vol=462.434, self.amt=14071438.2713, ukdf['pct'].iloc[-1]=0.000138 , ukdf['amount'].iloc[-1]=14071438.2713, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5852, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '60.176', 'enterprice': '16529.3', 'countrevence': '0', 'unrealprofit': '-836747.28', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '30434.3', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1
127.0.0.1 - - [15/Apr/2023 08:25:01] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=993672.4896432, self.flagDict['side']='sell', self.tradeCount=2, self.count=39958
self.closeSec=1681518299, self.tradeDate='20230415', self.openTime='082000', self.closeTime='082459', self.symbol='BTCUSDT', self.open=30434.3, self.close=30481.3, self.high=30486.3, self.low=30434.3, self.vol=1273.319, self.amt=38796222.7201 
2023-04-15 08:25:01,680:INFO:amihud:main.py:172:handleKline:200676: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5849  20230415   080000    080459  ...         0.0        0.0       0
5850  20230415   080500    080959  ...         0.0        0.0       0
5851  20230415   081000    081459  ...         0.0        0.0       0
5852  20230415   081500    081959  ...         0.0        0.0       0
5853  20230415   082000    082459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-04-15 08:25:01,683:INFO:amihud:main.py:175:handleKline:200676: self.closeSec=1681518299, self.tradeDate='20230415', self.openTime='082000', self.closeTime='082459',self.symbol='BTCUSDT',self.open=30434.3, self.close=30481.3, self.high=30486.3, self.low=30434.3, self.vol=1273.319, self.amt=38796222.7201, ukdf['pct'].iloc[-1]=0.001541 , ukdf['amount'].iloc[-1]=38796222.7201, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5853, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '60.176', 'enterprice': '16529.3', 'countrevence': '0', 'unrealprofit': '-839701.94309125664', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '30483.40035714', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1


## /root/FIL/strategy/factorcheck/log.txt ----- -----

127.0.0.1 - - [15/Apr/2023 08:00:01] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=23, self.factor=0.43541661550691446, self.count=40519 

self.closeSec=1681516799, self.tradeDate='20230415', self.openTime='075500', self.closeTime='075959', self.symbol='BTCUSDT', self.open=30467.5, self.close=30453.1, self.high=30470.8, self.low=30440.7 

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=23, self.factor=0.43541661550691446, self.count=40520 

self.closeSec=1681517099, self.tradeDate='20230415', self.openTime='080000', self.closeTime='080459', self.symbol='BTCUSDT', self.open=30453.0, self.close=30420.7, self.high=30455.0, self.low=30411.7 
127.0.0.1 - - [15/Apr/2023 08:05:01] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=23, self.factor=0.43541661550691446, self.count=40521 

self.closeSec=1681517399, self.tradeDate='20230415', self.openTime='080500', self.closeTime='080959', self.symbol='BTCUSDT', self.open=30420.7, self.close=30416.8, self.high=30457.6, self.low=30416.1 
127.0.0.1 - - [15/Apr/2023 08:10:01] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [15/Apr/2023 08:15:01] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=23, self.factor=0.43541661550691446, self.count=40522 

self.closeSec=1681517699, self.tradeDate='20230415', self.openTime='081000', self.closeTime='081459', self.symbol='BTCUSDT', self.open=30416.8, self.close=30430.2, self.high=30442.9, self.low=30416.1 

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=23, self.factor=0.43541661550691446, self.count=40523 

self.closeSec=1681517999, self.tradeDate='20230415', self.openTime='081500', self.closeTime='081959', self.symbol='BTCUSDT', self.open=30430.2, self.close=30434.4, self.high=30439.4, self.low=30413.0 
127.0.0.1 - - [15/Apr/2023 08:20:04] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [15/Apr/2023 08:25:01] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=23, self.factor=0.43541661550691446, self.count=40524 

self.closeSec=1681518299, self.tradeDate='20230415', self.openTime='082000', self.closeTime='082459', self.symbol='BTCUSDT', self.open=30434.3, self.close=30481.3, self.high=30486.3, self.low=30434.3 


## /root/FIL/strategy/logic/log.txt ----- -----

2023-04-15 08:00:35,162:DEBUG:logic:main.py:463:getModel:885513: df_s.iloc[-5:,:] :
          date closeTime     open  ...    alpha58   alpha67   alpha72
5769  20230415    052959  30429.8  ...  55.833333  0.519052  0.554638
5770  20230415    055959  30452.4  ...  55.416667  0.515329  0.554534
5771  20230415    062959  30431.8  ...  55.000000  0.510778  0.555884
5772  20230415    065959  30407.2  ...  55.416667  0.512368  0.556620
5773  20230415    072959  30416.2  ...  55.416667  0.509312  0.558254

[5 rows x 33 columns]
0.5555555555555556
acc is : 0.5555555555555556
2023-04-15 08:00:35,321:INFO:logic:main.py:468:getModel:885513: df_pred.iloc[-5:,:] :
     pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
535     0  0.524786  0.475214       0  ...  1.020915  -1.0    0.0  1.088101
536     0  0.516040  0.483960       0  ...  1.021740  -1.0    0.0  1.087222
537     0  0.509317  0.490683       1  ...  1.021441  -1.0    0.0  1.087540
538     0  0.510376  0.489624       0  ...  1.021982  -1.0    0.0  1.086964
539     0  0.503978  0.496022       1  ...  1.020197  -1.0    0.0  1.088863

[5 rows x 10 columns]
2023-04-15 08:00:35,365:INFO:logic:main.py:478:getModel:885513: df_panel.iloc[-5:,:] :
    pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
45     0  0.523574  0.476426       0  ...  1.004957  -1.0    0.0  1.084638
46     0  0.515160  0.484840       0  ...  1.005770  -1.0    0.0  1.084712
47     0  0.509054  0.490946       1  ...  1.021441  -1.0    0.0  1.085111
48     0  0.510718  0.489282       0  ...  1.021982  -1.0    0.0  1.088927
49     0  0.503978  0.496022       1  ...  1.020197  -1.0    0.0  1.088863

[5 rows x 10 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': []}


## /root/FIL/strategy/modifiedmom/log.txt ----- -----


--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=20257 

self.closeSec=1681514999, self.tradeDate='20230415', self.openTime='072000', self.closeTime='072959', self.symbol='BTCUSDT', self.open='30369.8', self.close='30402.5'
127.0.0.1 - - [15/Apr/2023 07:30:01] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [15/Apr/2023 07:40:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=20258 

self.closeSec=1681515599, self.tradeDate='20230415', self.openTime='073000', self.closeTime='073959', self.symbol='BTCUSDT', self.open='30402.5', self.close='30394.8'

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=20259 

self.closeSec=1681516199, self.tradeDate='20230415', self.openTime='074000', self.closeTime='074959', self.symbol='BTCUSDT', self.open='30394.8', self.close='30416.4'
127.0.0.1 - - [15/Apr/2023 07:50:01] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [15/Apr/2023 08:00:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=20260 

self.closeSec=1681516799, self.tradeDate='20230415', self.openTime='075000', self.closeTime='075959', self.symbol='BTCUSDT', self.open='30416.4', self.close='30453.1'
127.0.0.1 - - [15/Apr/2023 08:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=20261 

self.closeSec=1681517399, self.tradeDate='20230415', self.openTime='080000', self.closeTime='080959', self.symbol='BTCUSDT', self.open='30453', self.close='30416.8'

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=20262 

self.closeSec=1681517999, self.tradeDate='20230415', self.openTime='081000', self.closeTime='081959', self.symbol='BTCUSDT', self.open='30416.8', self.close='30434.4'
127.0.0.1 - - [15/Apr/2023 08:20:05] "POST / HTTP/1.1" 200 -


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


--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=20258 

self.closeSec=1681514999, self.tradeDate='20230415', self.openTime='072000', self.closeTime='072959', self.symbol='BTCUSDT', self.open='30369.8', self.close='30402.5'
127.0.0.1 - - [15/Apr/2023 07:30:01] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [15/Apr/2023 07:40:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=20259 

self.closeSec=1681515599, self.tradeDate='20230415', self.openTime='073000', self.closeTime='073959', self.symbol='BTCUSDT', self.open='30402.5', self.close='30394.8'

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=20260 

self.closeSec=1681516199, self.tradeDate='20230415', self.openTime='074000', self.closeTime='074959', self.symbol='BTCUSDT', self.open='30394.8', self.close='30416.4'
127.0.0.1 - - [15/Apr/2023 07:50:01] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [15/Apr/2023 08:00:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=20261 

self.closeSec=1681516799, self.tradeDate='20230415', self.openTime='075000', self.closeTime='075959', self.symbol='BTCUSDT', self.open='30416.4', self.close='30453.1'

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=20262 

self.closeSec=1681517399, self.tradeDate='20230415', self.openTime='080000', self.closeTime='080959', self.symbol='BTCUSDT', self.open='30453', self.close='30416.8'
127.0.0.1 - - [15/Apr/2023 08:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=20263 

self.closeSec=1681517999, self.tradeDate='20230415', self.openTime='081000', self.closeTime='081959', self.symbol='BTCUSDT', self.open='30416.8', self.close='30434.4'
127.0.0.1 - - [15/Apr/2023 08:20:05] "POST / HTTP/1.1" 200 -


## /root/FIL/strategy/similarity/log.txt ----- -----

127.0.0.1 - - [15/Apr/2023 07:30:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=20258 

self.closeSec=1681514999, self.tradeDate='20230415', self.openTime='072000', self.closeTime='072959', self.symbol='BTCUSDT', self.open='30369.8', self.close='30402.5'

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=20259 

self.closeSec=1681515599, self.tradeDate='20230415', self.openTime='073000', self.closeTime='073959', self.symbol='BTCUSDT', self.open='30402.5', self.close='30394.8'
127.0.0.1 - - [15/Apr/2023 07:40:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=20260 

self.closeSec=1681516199, self.tradeDate='20230415', self.openTime='074000', self.closeTime='074959', self.symbol='BTCUSDT', self.open='30394.8', self.close='30416.4'
127.0.0.1 - - [15/Apr/2023 07:50:01] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [15/Apr/2023 08:00:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=20261 

self.closeSec=1681516799, self.tradeDate='20230415', self.openTime='075000', self.closeTime='075959', self.symbol='BTCUSDT', self.open='30416.4', self.close='30453.1'

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=20262 

self.closeSec=1681517399, self.tradeDate='20230415', self.openTime='080000', self.closeTime='080959', self.symbol='BTCUSDT', self.open='30453', self.close='30416.8'
127.0.0.1 - - [15/Apr/2023 08:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=20263 

self.closeSec=1681517999, self.tradeDate='20230415', self.openTime='081000', self.closeTime='081959', self.symbol='BTCUSDT', self.open='30416.8', self.close='30434.4'
127.0.0.1 - - [15/Apr/2023 08:20:05] "POST / HTTP/1.1" 200 -


## /root/FIL/strategy/sr_min/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=0, self.total=1000000.0, self.flagDict['side']='', self.tradeCount=0, self.count=35955
self.closeSec=1681517999, self.tradeDate='20230415', self.openTime='081500', self.closeTime='081959', self.symbol='BTCUSDT', self.open=30430.2, self.close=30434.4, self.high=30439.4, self.low=30413.0, self.vol=462.434, self.amt=14071438.2713 
127.0.0.1 - - [15/Apr/2023 08:20:04] "POST / HTTP/1.1" 200 -
2023-04-15 08:20:07,611:INFO:sr_min:main.py:172:handleKline:449472: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5848  20230415   075500    075959  ...         0.0        0.0       0
5849  20230415   080000    080459  ...         0.0        0.0       0
5850  20230415   080500    080959  ...         0.0        0.0       0
5851  20230415   081000    081459  ...         0.0        0.0       0
5852  20230415   081500    081959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-04-15 08:20:07,620:INFO:sr_min:main.py:175:handleKline:449472: self.closeSec=1681517999, self.tradeDate='20230415', self.openTime='081500', self.closeTime='081959',self.symbol='BTCUSDT',self.open=30430.2, self.close=30434.4, self.high=30439.4, self.low=30413.0, self.vol=462.434, self.amt=14071438.2713, ukdf['pct'].iloc[-1]=0.000138 , ukdf['amount'].iloc[-1]=14071438.2713, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5852, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': []}
type(curSign)=<class 'int'>, curSign=0, self.sign=0
--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=0, self.total=1000000.0, self.flagDict['side']='', self.tradeCount=0, self.count=35956
self.closeSec=1681518299, self.tradeDate='20230415', self.openTime='082000', self.closeTime='082459', self.symbol='BTCUSDT', self.open=30434.3, self.close=30481.3, self.high=30486.3, self.low=30434.3, self.vol=1273.319, self.amt=38796222.7201 
127.0.0.1 - - [15/Apr/2023 08:25:01] "POST / HTTP/1.1" 200 -
2023-04-15 08:25:01,615:INFO:sr_min:main.py:172:handleKline:449472: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5849  20230415   080000    080459  ...         0.0        0.0       0
5850  20230415   080500    080959  ...         0.0        0.0       0
5851  20230415   081000    081459  ...         0.0        0.0       0
5852  20230415   081500    081959  ...         0.0        0.0       0
5853  20230415   082000    082459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-04-15 08:25:01,616:INFO:sr_min:main.py:175:handleKline:449472: self.closeSec=1681518299, self.tradeDate='20230415', self.openTime='082000', self.closeTime='082459',self.symbol='BTCUSDT',self.open=30434.3, self.close=30481.3, self.high=30486.3, self.low=30434.3, self.vol=1273.319, self.amt=38796222.7201, ukdf['pct'].iloc[-1]=0.001541 , ukdf['amount'].iloc[-1]=38796222.7201, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5853, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': []}
type(curSign)=<class 'int'>, curSign=0, self.sign=0


## /root/FIL/strategy/s_rsrs/log.txt ----- -----

719  20230414   200000    235959  1681487999  ...    719  0.537512  0.042998     NaN
720  20230415   000000    035959  1681502399  ...    720  0.344675 -0.368287     NaN

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '52.515', 'enterprice': '28269.9', 'countrevence': '0', 'unrealprofit': '107003.9369456928', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '30307.48805952', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-9223372036854775808, self.sign=1
127.0.0.1 - - [15/Apr/2023 08:00:01] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='s_rsrs', self.symbol='BTCUSDT', interval='4h', intervalSec=14400, wid=25, thd=0.6, self.sign=1, self.total=1483109.2047015, self.flagDict['side']='buy', self.tradeCount=30, self.count=844
self.closeSec=1681516799, self.tradeDate='20230415', self.openTime='040000', self.closeTime='075959', self.symbol='BTCUSDT', self.open=30311.1, self.close=30453.1, self.high=30500.0, self.low=30260.0, self.vol=48626.219, self.amt=1479057752.21021 
2023-04-15 08:00:01,788:INFO:s_rsrs:main.py:141:handleKline:185271: self.closeSec=1681516799, self.tradeDate='20230415', self.openTime='040000', self.closeTime='075959',self.symbol='BTCUSDT',self.open=30311.1, self.close=30453.1, self.high=30500.0, self.low=30260.0, self.vol=48626.219, self.amt=1479057752.21021 
2023-04-15 08:00:01,853:INFO:s_rsrs:main.py:142:handleKline:185271: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime  ...         vol           amt       pct
717  20230414   120000    155959  ...   95052.482  2.930392e+09  0.001802
718  20230414   160000    195959  ...   51819.143  1.593152e+09  0.001630
719  20230414   200000    235959  ...  173876.177  5.301979e+09 -0.018295
720  20230415   000000    035959  ...  102233.968  3.085413e+09  0.002796
721  20230415   040000    075959  ...   48626.219  1.479058e+09  0.004681

[5 rows x 11 columns]
2023-04-15 08:00:04,463:INFO:s_rsrs:main.py:151:handleKline:185271: df_s.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec  ...  index      beta    zscore  signal
717  20230414   120000    155959  1681459199  ...    717  0.818031  0.651874     1.0
718  20230414   160000    195959  1681473599  ...    718  0.681606  0.353538     NaN
719  20230414   200000    235959  1681487999  ...    719  0.537512  0.042998     NaN
720  20230415   000000    035959  1681502399  ...    720  0.344675 -0.368287     NaN
721  20230415   040000    075959  1681516799  ...    721  0.279484 -0.500986     NaN

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '52.515', 'enterprice': '28269.9', 'countrevence': '0', 'unrealprofit': '114697.7412956208', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '30453.99485472', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-9223372036854775808, self.sign=1


