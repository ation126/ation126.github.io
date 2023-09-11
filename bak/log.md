# 20230911 16:26:01

## /root/FIL/strategy/amihud/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=373746.4768026, self.flagDict['side']='sell', self.tradeCount=2, self.count=34612
self.closeSec=1694420399, self.tradeDate='20230911', self.openTime='161500', self.closeTime='161959', self.symbol='BTCUSDT', self.open=25776.0, self.close=25769.7, self.high=25778.8, self.low=25760.4, self.vol=947.912, self.amt=24427358.4632 
127.0.0.1 - - [11/Sep/2023 16:20:02] "POST / HTTP/1.1" 200 -
2023-09-11 16:20:05,941:INFO:amihud:main.py:172:handleKline:2219019: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5951  20230911   155500    155959  ...         0.0        0.0       0
5952  20230911   160000    160459  ...         0.0        0.0       0
5953  20230911   160500    160959  ...         0.0        0.0       0
5954  20230911   161000    161459  ...         0.0        0.0       0
5955  20230911   161500    161959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-09-11 16:20:05,954:INFO:amihud:main.py:175:handleKline:2219019: self.closeSec=1694420399, self.tradeDate='20230911', self.openTime='161500', self.closeTime='161959',self.symbol='BTCUSDT',self.open=25776.0, self.close=25769.7, self.high=25778.8, self.low=25760.4, self.vol=947.912, self.amt=24427358.4632, ukdf['pct'].iloc[-1]=-0.000244 , ukdf['amount'].iloc[-1]=24427358.4632, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5955, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '13.926', 'enterprice': '26864.9', 'countrevence': '0', 'unrealprofit': '15267.0738', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '25768.6', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1
--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=373746.4768026, self.flagDict['side']='sell', self.tradeCount=2, self.count=34613
self.closeSec=1694420699, self.tradeDate='20230911', self.openTime='162000', self.closeTime='162459', self.symbol='BTCUSDT', self.open=25769.9, self.close=25760.2, self.high=25778.4, self.low=25756.8, self.vol=702.277, self.amt=18096258.2176 
127.0.0.1 - - [11/Sep/2023 16:25:00] "POST / HTTP/1.1" 200 -
2023-09-11 16:25:00,796:INFO:amihud:main.py:172:handleKline:2219019: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5952  20230911   160000    160459  ...         0.0        0.0       0
5953  20230911   160500    160959  ...         0.0        0.0       0
5954  20230911   161000    161459  ...         0.0        0.0       0
5955  20230911   161500    161959  ...         0.0        0.0       0
5956  20230911   162000    162459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-09-11 16:25:00,797:INFO:amihud:main.py:175:handleKline:2219019: self.closeSec=1694420699, self.tradeDate='20230911', self.openTime='162000', self.closeTime='162459',self.symbol='BTCUSDT',self.open=25769.9, self.close=25760.2, self.high=25778.4, self.low=25756.8, self.vol=702.277, self.amt=18096258.2176, ukdf['pct'].iloc[-1]=-0.000369 , ukdf['amount'].iloc[-1]=18096258.2176, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5956, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '13.926', 'enterprice': '26864.9', 'countrevence': '0', 'unrealprofit': '15381.06991910874', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '25760.41415201', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1


## /root/FIL/strategy/factorcheck/log.txt ----- -----


--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.714181719035411, self.count=34610 

self.closeSec=1694419199, self.tradeDate='20230911', self.openTime='155500', self.closeTime='155959', self.symbol='BTCUSDT', self.open=25802.7, self.close=25801.3, self.high=25806.3, self.low=25800.0 
127.0.0.1 - - [11/Sep/2023 16:00:00] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.714181719035411, self.count=34611 

self.closeSec=1694419499, self.tradeDate='20230911', self.openTime='160000', self.closeTime='160459', self.symbol='BTCUSDT', self.open=25801.4, self.close=25813.8, self.high=25813.8, self.low=25801.3 
127.0.0.1 - - [11/Sep/2023 16:05:00] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [11/Sep/2023 16:10:00] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.714181719035411, self.count=34612 

self.closeSec=1694419799, self.tradeDate='20230911', self.openTime='160500', self.closeTime='160959', self.symbol='BTCUSDT', self.open=25813.8, self.close=25795.8, self.high=25817.9, self.low=25795.7 
127.0.0.1 - - [11/Sep/2023 16:15:00] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.714181719035411, self.count=34613 

self.closeSec=1694420099, self.tradeDate='20230911', self.openTime='161000', self.closeTime='161459', self.symbol='BTCUSDT', self.open=25795.8, self.close=25776.0, self.high=25799.1, self.low=25775.1 

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.714181719035411, self.count=34614 

self.closeSec=1694420399, self.tradeDate='20230911', self.openTime='161500', self.closeTime='161959', self.symbol='BTCUSDT', self.open=25776.0, self.close=25769.7, self.high=25778.8, self.low=25760.4 
127.0.0.1 - - [11/Sep/2023 16:20:01] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.714181719035411, self.count=34615 

self.closeSec=1694420699, self.tradeDate='20230911', self.openTime='162000', self.closeTime='162459', self.symbol='BTCUSDT', self.open=25769.9, self.close=25760.2, self.high=25778.4, self.low=25756.8 
127.0.0.1 - - [11/Sep/2023 16:25:00] "POST / HTTP/1.1" 200 -


## /root/FIL/strategy/logic/log.txt ----- -----

2023-09-11 16:00:18,072:DEBUG:logic:main.py:463:getModel:2218526: df_s.iloc[-5:,:] :
          date closeTime     open  ...    alpha58   alpha67   alpha72
5785  20230911    132959  25768.1  ...  52.500000  0.482319  0.515622
5786  20230911    135959  25773.7  ...  52.916667  0.528116  0.500594
5787  20230911    142959  25884.8  ...  52.500000  0.513561  0.490931
5788  20230911    145959  25849.3  ...  52.083333  0.505507  0.484385
5789  20230911    152959  25829.7  ...  51.666667  0.493815  0.481932

[5 rows x 33 columns]
0.5295202952029521
acc is : 0.5295202952029521
2023-09-11 16:00:18,195:INFO:logic:main.py:468:getModel:2218526: df_pred.iloc[-5:,:] :
     pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
537     1  0.494923  0.505077       1  ...  1.028519  -1.0    0.0  0.951268
538     0  0.527285  0.472715       0  ...  1.029894  -1.0    0.0  0.949996
539     1  0.490342  0.509658       0  ...  1.030675  -1.0    0.0  0.949276
540     1  0.491142  0.508858       0  ...  1.031832  -1.0    0.0  0.948210
541     1  0.485838  0.514162       1  ...  1.031808  -1.0    0.0  0.948232

[5 rows x 10 columns]
2023-09-11 16:00:18,207:INFO:logic:main.py:478:getModel:2218526: df_panel.iloc[-5:,:] :
    pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
45     1  0.494310  0.505690       1  ...  1.028519  -1.0    0.0  0.950740
46     0  0.526387  0.473613       0  ...  1.029894  -1.0    0.0  0.947093
47     1  0.489820  0.510180       0  ...  1.030675  -1.0    0.0  0.946472
48     1  0.490881  0.509119       0  ...  1.031832  -1.0    0.0  0.947378
49     1  0.485838  0.514162       1  ...  1.031808  -1.0    0.0  0.948232

[5 rows x 10 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '28.306', 'enterprice': '25771.5', 'countrevence': '0', 'unrealprofit': '-902.9614', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '25803.4', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}


## /root/FIL/strategy/modifiedmom/log.txt ----- -----

127.0.0.1 - - [11/Sep/2023 15:30:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=17303 

self.closeSec=1694417399, self.tradeDate='20230911', self.openTime='152000', self.closeTime='152959', self.symbol='BTCUSDT', self.open='25799.7', self.close='25800.7'

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=17304 

self.closeSec=1694417999, self.tradeDate='20230911', self.openTime='153000', self.closeTime='153959', self.symbol='BTCUSDT', self.open='25800.8', self.close='25796.6'
127.0.0.1 - - [11/Sep/2023 15:40:01] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [11/Sep/2023 15:50:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=17305 

self.closeSec=1694418599, self.tradeDate='20230911', self.openTime='154000', self.closeTime='154959', self.symbol='BTCUSDT', self.open='25796.7', self.close='25805.2'

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=17306 

self.closeSec=1694419199, self.tradeDate='20230911', self.openTime='155000', self.closeTime='155959', self.symbol='BTCUSDT', self.open='25805.3', self.close='25801.3'
127.0.0.1 - - [11/Sep/2023 16:00:01] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [11/Sep/2023 16:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=17307 

self.closeSec=1694419799, self.tradeDate='20230911', self.openTime='160000', self.closeTime='160959', self.symbol='BTCUSDT', self.open='25801.4', self.close='25795.8'

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=17308 

self.closeSec=1694420399, self.tradeDate='20230911', self.openTime='161000', self.closeTime='161959', self.symbol='BTCUSDT', self.open='25795.8', self.close='25769.9'
127.0.0.1 - - [11/Sep/2023 16:20:04] "POST / HTTP/1.1" 200 -


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


--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=17306 

self.closeSec=1694417399, self.tradeDate='20230911', self.openTime='152000', self.closeTime='152959', self.symbol='BTCUSDT', self.open='25799.7', self.close='25800.7'
127.0.0.1 - - [11/Sep/2023 15:30:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=17307 

self.closeSec=1694417999, self.tradeDate='20230911', self.openTime='153000', self.closeTime='153959', self.symbol='BTCUSDT', self.open='25800.8', self.close='25796.6'
127.0.0.1 - - [11/Sep/2023 15:40:01] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [11/Sep/2023 15:50:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=17308 

self.closeSec=1694418599, self.tradeDate='20230911', self.openTime='154000', self.closeTime='154959', self.symbol='BTCUSDT', self.open='25796.7', self.close='25805.2'

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=17309 

self.closeSec=1694419199, self.tradeDate='20230911', self.openTime='155000', self.closeTime='155959', self.symbol='BTCUSDT', self.open='25805.3', self.close='25801.3'
127.0.0.1 - - [11/Sep/2023 16:00:01] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [11/Sep/2023 16:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=17310 

self.closeSec=1694419799, self.tradeDate='20230911', self.openTime='160000', self.closeTime='160959', self.symbol='BTCUSDT', self.open='25801.4', self.close='25795.8'

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=17311 

self.closeSec=1694420399, self.tradeDate='20230911', self.openTime='161000', self.closeTime='161959', self.symbol='BTCUSDT', self.open='25795.8', self.close='25769.9'
127.0.0.1 - - [11/Sep/2023 16:20:04] "POST / HTTP/1.1" 200 -


## /root/FIL/strategy/similarity/log.txt ----- -----


--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=17306 

self.closeSec=1694417399, self.tradeDate='20230911', self.openTime='152000', self.closeTime='152959', self.symbol='BTCUSDT', self.open='25799.7', self.close='25800.7'
127.0.0.1 - - [11/Sep/2023 15:30:01] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [11/Sep/2023 15:40:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=17307 

self.closeSec=1694417999, self.tradeDate='20230911', self.openTime='153000', self.closeTime='153959', self.symbol='BTCUSDT', self.open='25800.8', self.close='25796.6'

--handleKline--:  127.0.0.1 - - [11/Sep/2023 15:50:01] "POST / HTTP/1.1" 200 -
self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=17308 

self.closeSec=1694418599, self.tradeDate='20230911', self.openTime='154000', self.closeTime='154959', self.symbol='BTCUSDT', self.open='25796.7', self.close='25805.2'
127.0.0.1 - - [11/Sep/2023 16:00:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=17309 

self.closeSec=1694419199, self.tradeDate='20230911', self.openTime='155000', self.closeTime='155959', self.symbol='BTCUSDT', self.open='25805.3', self.close='25801.3'
127.0.0.1 - - [11/Sep/2023 16:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=17310 

self.closeSec=1694419799, self.tradeDate='20230911', self.openTime='160000', self.closeTime='160959', self.symbol='BTCUSDT', self.open='25801.4', self.close='25795.8'

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=17311 

self.closeSec=1694420399, self.tradeDate='20230911', self.openTime='161000', self.closeTime='161959', self.symbol='BTCUSDT', self.open='25795.8', self.close='25769.9'
127.0.0.1 - - [11/Sep/2023 16:20:04] "POST / HTTP/1.1" 200 -


## /root/FIL/strategy/sr_min/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=1, self.total=996015.990996, self.flagDict['side']='buy', self.tradeCount=1, self.count=34612
self.closeSec=1694420399, self.tradeDate='20230911', self.openTime='161500', self.closeTime='161959', self.symbol='BTCUSDT', self.open=25776.0, self.close=25769.7, self.high=25778.8, self.low=25760.4, self.vol=947.912, self.amt=24427358.4632 
127.0.0.1 - - [11/Sep/2023 16:20:02] "POST / HTTP/1.1" 200 -
2023-09-11 16:20:05,943:INFO:sr_min:main.py:172:handleKline:2219263: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5951  20230911   155500    155959  ...         0.0        0.0       0
5952  20230911   160000    160459  ...         0.0        0.0       0
5953  20230911   160500    160959  ...         0.0        0.0       0
5954  20230911   161000    161459  ...         0.0        0.0       0
5955  20230911   161500    161959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-09-11 16:20:05,956:INFO:sr_min:main.py:175:handleKline:2219263: self.closeSec=1694420399, self.tradeDate='20230911', self.openTime='161500', self.closeTime='161959',self.symbol='BTCUSDT',self.open=25776.0, self.close=25769.7, self.high=25778.8, self.low=25760.4, self.vol=947.912, self.amt=24427358.4632, ukdf['pct'].iloc[-1]=-0.000244 , ukdf['amount'].iloc[-1]=24427358.4632, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5955, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '37.141', 'enterprice': '26844', 'countrevence': '0', 'unrealprofit': '-39941.4314', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '25768.6', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=1
127.0.0.1 - - [11/Sep/2023 16:25:00] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=1, self.total=996015.990996, self.flagDict['side']='buy', self.tradeCount=1, self.count=34613
self.closeSec=1694420699, self.tradeDate='20230911', self.openTime='162000', self.closeTime='162459', self.symbol='BTCUSDT', self.open=25769.9, self.close=25760.2, self.high=25778.4, self.low=25756.8, self.vol=702.277, self.amt=18096258.2176 
2023-09-11 16:25:00,806:INFO:sr_min:main.py:172:handleKline:2219263: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5952  20230911   160000    160459  ...         0.0        0.0       0
5953  20230911   160500    160959  ...         0.0        0.0       0
5954  20230911   161000    161459  ...         0.0        0.0       0
5955  20230911   161500    161959  ...         0.0        0.0       0
5956  20230911   162000    162459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-09-11 16:25:00,807:INFO:sr_min:main.py:175:handleKline:2219263: self.closeSec=1694420699, self.tradeDate='20230911', self.openTime='162000', self.closeTime='162459',self.symbol='BTCUSDT',self.open=25769.9, self.close=25760.2, self.high=25778.4, self.low=25756.8, self.vol=702.277, self.amt=18096258.2176, ukdf['pct'].iloc[-1]=-0.000369 , ukdf['amount'].iloc[-1]=18096258.2176, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5956, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '37.141', 'enterprice': '26844', 'countrevence': '0', 'unrealprofit': '-40245.46198019659', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '25760.41415201', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=1


## /root/FIL/strategy/s_rsrs/log.txt ----- -----

721  20230911   040000    075959  1694390399  ...    721  0.332722 -0.181974     NaN
722  20230911   080000    115959  1694404799  ...    722  0.305950 -0.255287     NaN

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '57.177', 'enterprice': '25892.3', 'countrevence': '0', 'unrealprofit': '9422.7696', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '25727.5', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-9223372036854775808, self.sign=-1
127.0.0.1 - - [11/Sep/2023 16:00:01] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='s_rsrs', self.symbol='BTCUSDT', interval='4h', intervalSec=14400, wid=25, thd=0.6, self.sign=-1, self.total=1478963.5930628998, self.flagDict['side']='sell', self.tradeCount=22, self.count=721
self.closeSec=1694419199, self.tradeDate='20230911', self.openTime='120000', self.closeTime='155959', self.symbol='BTCUSDT', self.open=25727.4, self.close=25801.3, self.high=25895.0, self.low=25707.9, self.vol=25284.435, self.amt=652642346.66298 
2023-09-11 16:00:01,588:INFO:s_rsrs:main.py:141:handleKline:2218689: self.closeSec=1694419199, self.tradeDate='20230911', self.openTime='120000', self.closeTime='155959',self.symbol='BTCUSDT',self.open=25727.4, self.close=25801.3, self.high=25895.0, self.low=25707.9, self.vol=25284.435, self.amt=652642346.66298 
2023-09-11 16:00:01,602:INFO:s_rsrs:main.py:142:handleKline:2218689: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime  ...        vol           amt       pct
719  20230910   200000    235959  ...  23274.670  5.997833e+08 -0.000733
720  20230911   000000    035959  ...  45643.606  1.173217e+09  0.000885
721  20230911   040000    075959  ...  49095.382  1.270014e+09  0.001613
722  20230911   080000    115959  ...  32476.954  8.356556e+08 -0.003910
723  20230911   120000    155959  ...  25284.435  6.526423e+08  0.002872

[5 rows x 11 columns]
2023-09-11 16:00:02,275:INFO:s_rsrs:main.py:151:handleKline:2218689: df_s.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec  ...  index      beta    zscore  signal
719  20230910   200000    235959  1694361599  ...    719  0.105012 -0.813227    -1.0
720  20230911   000000    035959  1694375999  ...    720  0.087417 -0.859435    -1.0
721  20230911   040000    075959  1694390399  ...    721  0.332722 -0.181974     NaN
722  20230911   080000    115959  1694404799  ...    722  0.305950 -0.255287     NaN
723  20230911   120000    155959  1694419199  ...    723  0.297896 -0.276374     NaN

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '57.177', 'enterprice': '25892.3', 'countrevence': '0', 'unrealprofit': '5166.2218657212', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '25801.9451044', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-9223372036854775808, self.sign=-1


