# 20230905 16:26:02

## /root/FIL/strategy/amihud/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=373746.4768026, self.flagDict['side']='sell', self.tradeCount=2, self.count=32884
self.closeSec=1693901999, self.tradeDate='20230905', self.openTime='161500', self.closeTime='161959', self.symbol='BTCUSDT', self.open=25729.0, self.close=25712.4, self.high=25742.2, self.low=25711.7, self.vol=725.646, self.amt=18665588.6895 
127.0.0.1 - - [05/Sep/2023 16:20:02] "POST / HTTP/1.1" 200 -
2023-09-05 16:20:05,973:INFO:amihud:main.py:172:handleKline:2219019: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5939  20230905   155500    155959  ...         0.0        0.0       0
5940  20230905   160000    160459  ...         0.0        0.0       0
5941  20230905   160500    160959  ...         0.0        0.0       0
5942  20230905   161000    161459  ...         0.0        0.0       0
5943  20230905   161500    161959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-09-05 16:20:05,984:INFO:amihud:main.py:175:handleKline:2219019: self.closeSec=1693901999, self.tradeDate='20230905', self.openTime='161500', self.closeTime='161959',self.symbol='BTCUSDT',self.open=25729.0, self.close=25712.4, self.high=25742.2, self.low=25711.7, self.vol=725.646, self.amt=18665588.6895, ukdf['pct'].iloc[-1]=-0.000645 , ukdf['amount'].iloc[-1]=18665588.6895, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5943, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '13.926', 'enterprice': '26864.9', 'countrevence': '0', 'unrealprofit': '16027.4334', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '25714', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1
--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=373746.4768026, self.flagDict['side']='sell', self.tradeCount=2, self.count=32885
self.closeSec=1693902299, self.tradeDate='20230905', self.openTime='162000', self.closeTime='162459', self.symbol='BTCUSDT', self.open=25712.4, self.close=25701.7, self.high=25717.2, self.low=25700.2, self.vol=521.279, self.amt=13400235.318 
127.0.0.1 - - [05/Sep/2023 16:25:00] "POST / HTTP/1.1" 200 -
2023-09-05 16:25:00,818:INFO:amihud:main.py:172:handleKline:2219019: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5940  20230905   160000    160459  ...         0.0        0.0       0
5941  20230905   160500    160959  ...         0.0        0.0       0
5942  20230905   161000    161459  ...         0.0        0.0       0
5943  20230905   161500    161959  ...         0.0        0.0       0
5944  20230905   162000    162459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-09-05 16:25:00,819:INFO:amihud:main.py:175:handleKline:2219019: self.closeSec=1693902299, self.tradeDate='20230905', self.openTime='162000', self.closeTime='162459',self.symbol='BTCUSDT',self.open=25712.4, self.close=25701.7, self.high=25717.2, self.low=25700.2, self.vol=521.279, self.amt=13400235.318, ukdf['pct'].iloc[-1]=-0.000416 , ukdf['amount'].iloc[-1]=13400235.318, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5944, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '13.926', 'enterprice': '26864.9', 'countrevence': '0', 'unrealprofit': '16193.14383068118', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '25702.10064407', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1


## /root/FIL/strategy/factorcheck/log.txt ----- -----

127.0.0.1 - - [05/Sep/2023 16:00:00] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.714181719035411, self.count=32882 

self.closeSec=1693900799, self.tradeDate='20230905', self.openTime='155500', self.closeTime='155959', self.symbol='BTCUSDT', self.open=25718.1, self.close=25724.6, self.high=25727.8, self.low=25707.7 

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.714181719035411, self.count=32883 

self.closeSec=1693901099, self.tradeDate='20230905', self.openTime='160000', self.closeTime='160459', self.symbol='BTCUSDT', self.open=25724.7, self.close=25731.5, self.high=25733.8, self.low=25720.2 
127.0.0.1 - - [05/Sep/2023 16:05:00] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [05/Sep/2023 16:10:00] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.714181719035411, self.count=32884 

self.closeSec=1693901399, self.tradeDate='20230905', self.openTime='160500', self.closeTime='160959', self.symbol='BTCUSDT', self.open=25731.6, self.close=25754.2, self.high=25800.0, self.low=25731.6 

--handleKline--: 127.0.0.1 - - [05/Sep/2023 16:15:00] "POST / HTTP/1.1" 200 -
 version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.714181719035411, self.count=32885 

self.closeSec=1693901699, self.tradeDate='20230905', self.openTime='161000', self.closeTime='161459', self.symbol='BTCUSDT', self.open=25754.2, self.close=25729.0, self.high=25754.5, self.low=25727.2 

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.714181719035411, self.count=32886 

self.closeSec=1693901999, self.tradeDate='20230905', self.openTime='161500', self.closeTime='161959', self.symbol='BTCUSDT', self.open=25729.0, self.close=25712.4, self.high=25742.2, self.low=25711.7 
127.0.0.1 - - [05/Sep/2023 16:20:01] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [05/Sep/2023 16:25:00] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.714181719035411, self.count=32887 

self.closeSec=1693902299, self.tradeDate='20230905', self.openTime='162000', self.closeTime='162459', self.symbol='BTCUSDT', self.open=25712.4, self.close=25701.7, self.high=25717.2, self.low=25700.2 


## /root/FIL/strategy/logic/log.txt ----- -----

2023-09-05 16:00:18,312:DEBUG:logic:main.py:463:getModel:2218526: df_s.iloc[-5:,:] :
          date closeTime     open  ...    alpha58   alpha67   alpha72
5785  20230905    132959  25683.6  ...  45.416667  0.444206  0.666832
5786  20230905    135959  25705.5  ...  45.416667  0.451640  0.659204
5787  20230905    142959  25723.8  ...  45.416667  0.442208  0.656515
5788  20230905    145959  25695.3  ...  45.000000  0.437191  0.656391
5789  20230905    152959  25679.8  ...  45.000000  0.450532  0.651271

[5 rows x 33 columns]
0.5276752767527675
acc is : 0.5276752767527675
2023-09-05 16:00:18,381:INFO:logic:main.py:468:getModel:2218526: df_pred.iloc[-5:,:] :
     pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
537     1  0.498696  0.501304       1  ...  0.992514  -1.0    0.0  0.984489
538     0  0.502551  0.497449       0  ...  0.993617  -1.0    0.0  0.983394
539     1  0.483820  0.516180       0  ...  0.994213  -1.0    0.0  0.982805
540     1  0.485980  0.514020       1  ...  0.992962  -1.0    0.0  0.984041
541     0  0.501446  0.498554       1  ...  0.992476  -1.0    0.0  0.984523

[5 rows x 10 columns]
2023-09-05 16:00:18,394:INFO:logic:main.py:478:getModel:2218526: df_panel.iloc[-5:,:] :
    pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
45     1  0.497841  0.502159       1  ...  0.992514  -1.0    0.0  0.985284
46     0  0.502126  0.497874       0  ...  0.993617  -1.0    0.0  0.984547
47     1  0.483103  0.516897       0  ...  0.994213  -1.0    0.0  0.981475
48     1  0.485612  0.514388       1  ...  0.992962  -1.0    0.0  0.983890
49     0  0.501446  0.498554       1  ...  0.992476  -1.0    0.0  0.984523

[5 rows x 10 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '26.263', 'enterprice': '26682.7', 'countrevence': '0', 'unrealprofit': '25148.54030610192', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '25725.13459216', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}


## /root/FIL/strategy/modifiedmom/log.txt ----- -----

127.0.0.1 - - [05/Sep/2023 15:30:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=16439 

self.closeSec=1693898999, self.tradeDate='20230905', self.openTime='152000', self.closeTime='152959', self.symbol='BTCUSDT', self.open='25679.8', self.close='25712.1'
127.0.0.1 - - [05/Sep/2023 15:40:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=16440 

self.closeSec=1693899599, self.tradeDate='20230905', self.openTime='153000', self.closeTime='153959', self.symbol='BTCUSDT', self.open='25712.2', self.close='25690.5'
127.0.0.1 - - [05/Sep/2023 15:50:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=16441 

self.closeSec=1693900199, self.tradeDate='20230905', self.openTime='154000', self.closeTime='154959', self.symbol='BTCUSDT', self.open='25690.4', self.close='25714.2'

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=16442 

self.closeSec=1693900799, self.tradeDate='20230905', self.openTime='155000', self.closeTime='155959', self.symbol='BTCUSDT', self.open='25714.2', self.close='25724.7'
127.0.0.1 - - [05/Sep/2023 16:00:02] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [05/Sep/2023 16:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=16443 

self.closeSec=1693901399, self.tradeDate='20230905', self.openTime='160000', self.closeTime='160959', self.symbol='BTCUSDT', self.open='25724.7', self.close='25754.2'

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=16444 

self.closeSec=1693901999, self.tradeDate='20230905', self.openTime='161000', self.closeTime='161959', self.symbol='BTCUSDT', self.open='25754.2', self.close='25712.5'
127.0.0.1 - - [05/Sep/2023 16:20:04] "POST / HTTP/1.1" 200 -


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


--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=16442 

self.closeSec=1693898999, self.tradeDate='20230905', self.openTime='152000', self.closeTime='152959', self.symbol='BTCUSDT', self.open='25679.8', self.close='25712.1'
127.0.0.1 - - [05/Sep/2023 15:30:01] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [05/Sep/2023 15:40:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=16443 

self.closeSec=1693899599, self.tradeDate='20230905', self.openTime='153000', self.closeTime='153959', self.symbol='BTCUSDT', self.open='25712.2', self.close='25690.5'

--handleKline--: 127.0.0.1 - - [05/Sep/2023 15:50:01] "POST / HTTP/1.1" 200 -
 self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=16444 

self.closeSec=1693900199, self.tradeDate='20230905', self.openTime='154000', self.closeTime='154959', self.symbol='BTCUSDT', self.open='25690.4', self.close='25714.2'

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=16445 

self.closeSec=1693900799, self.tradeDate='20230905', self.openTime='155000', self.closeTime='155959', self.symbol='BTCUSDT', self.open='25714.2', self.close='25724.7'
127.0.0.1 - - [05/Sep/2023 16:00:02] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=16446 

self.closeSec=1693901399, self.tradeDate='20230905', self.openTime='160000', self.closeTime='160959', self.symbol='BTCUSDT', self.open='25724.7', self.close='25754.2'
127.0.0.1 - - [05/Sep/2023 16:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=16447 

self.closeSec=1693901999, self.tradeDate='20230905', self.openTime='161000', self.closeTime='161959', self.symbol='BTCUSDT', self.open='25754.2', self.close='25712.5'
127.0.0.1 - - [05/Sep/2023 16:20:04] "POST / HTTP/1.1" 200 -


## /root/FIL/strategy/similarity/log.txt ----- -----


--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=16442 

self.closeSec=1693898999, self.tradeDate='20230905', self.openTime='152000', self.closeTime='152959', self.symbol='BTCUSDT', self.open='25679.8', self.close='25712.1'
127.0.0.1 - - [05/Sep/2023 15:30:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=16443 

self.closeSec=1693899599, self.tradeDate='20230905', self.openTime='153000', self.closeTime='153959', self.symbol='BTCUSDT', self.open='25712.2', self.close='25690.5'
127.0.0.1 - - [05/Sep/2023 15:40:01] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [05/Sep/2023 15:50:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=16444 

self.closeSec=1693900199, self.tradeDate='20230905', self.openTime='154000', self.closeTime='154959', self.symbol='BTCUSDT', self.open='25690.4', self.close='25714.2'
127.0.0.1 - - [05/Sep/2023 16:00:02] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=16445 

self.closeSec=1693900799, self.tradeDate='20230905', self.openTime='155000', self.closeTime='155959', self.symbol='BTCUSDT', self.open='25714.2', self.close='25724.7'
127.0.0.1 - - [05/Sep/2023 16:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=16446 

self.closeSec=1693901399, self.tradeDate='20230905', self.openTime='160000', self.closeTime='160959', self.symbol='BTCUSDT', self.open='25724.7', self.close='25754.2'

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=16447 

self.closeSec=1693901999, self.tradeDate='20230905', self.openTime='161000', self.closeTime='161959', self.symbol='BTCUSDT', self.open='25754.2', self.close='25712.5'
127.0.0.1 - - [05/Sep/2023 16:20:04] "POST / HTTP/1.1" 200 -


## /root/FIL/strategy/sr_min/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=1, self.total=996015.990996, self.flagDict['side']='buy', self.tradeCount=1, self.count=32884
self.closeSec=1693901999, self.tradeDate='20230905', self.openTime='161500', self.closeTime='161959', self.symbol='BTCUSDT', self.open=25729.0, self.close=25712.4, self.high=25742.2, self.low=25711.7, self.vol=725.646, self.amt=18665588.6895 
127.0.0.1 - - [05/Sep/2023 16:20:02] "POST / HTTP/1.1" 200 -
2023-09-05 16:20:05,968:INFO:sr_min:main.py:172:handleKline:2219263: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5939  20230905   155500    155959  ...         0.0        0.0       0
5940  20230905   160000    160459  ...         0.0        0.0       0
5941  20230905   160500    160959  ...         0.0        0.0       0
5942  20230905   161000    161459  ...         0.0        0.0       0
5943  20230905   161500    161959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-09-05 16:20:05,972:INFO:sr_min:main.py:175:handleKline:2219263: self.closeSec=1693901999, self.tradeDate='20230905', self.openTime='161500', self.closeTime='161959',self.symbol='BTCUSDT',self.open=25729.0, self.close=25712.4, self.high=25742.2, self.low=25711.7, self.vol=725.646, self.amt=18665588.6895, ukdf['pct'].iloc[-1]=-0.000645 , ukdf['amount'].iloc[-1]=18665588.6895, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5943, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '37.141', 'enterprice': '26844', 'countrevence': '0', 'unrealprofit': '-41969.33', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '25714', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=1
--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=1, self.total=996015.990996, self.flagDict['side']='buy', self.tradeCount=1, self.count=32885
self.closeSec=1693902299, self.tradeDate='20230905', self.openTime='162000', self.closeTime='162459', self.symbol='BTCUSDT', self.open=25712.4, self.close=25701.7, self.high=25717.2, self.low=25700.2, self.vol=521.279, self.amt=13400235.318 
127.0.0.1 - - [05/Sep/2023 16:25:00] "POST / HTTP/1.1" 200 -
2023-09-05 16:25:00,814:INFO:sr_min:main.py:172:handleKline:2219263: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5940  20230905   160000    160459  ...         0.0        0.0       0
5941  20230905   160500    160959  ...         0.0        0.0       0
5942  20230905   161000    161459  ...         0.0        0.0       0
5943  20230905   161500    161959  ...         0.0        0.0       0
5944  20230905   162000    162459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-09-05 16:25:00,815:INFO:sr_min:main.py:175:handleKline:2219263: self.closeSec=1693902299, self.tradeDate='20230905', self.openTime='162000', self.closeTime='162459',self.symbol='BTCUSDT',self.open=25712.4, self.close=25701.7, self.high=25717.2, self.low=25700.2, self.vol=521.279, self.amt=13400235.318, ukdf['pct'].iloc[-1]=-0.000416 , ukdf['amount'].iloc[-1]=13400235.318, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5944, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '37.141', 'enterprice': '26844', 'countrevence': '0', 'unrealprofit': '-42411.28397859613', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '25702.10064407', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=1


## /root/FIL/strategy/s_rsrs/log.txt ----- -----

721  20230905   040000    075959  1693871999  ...    721  0.000329 -1.127232    -1.0
722  20230905   080000    115959  1693886399  ...    722  0.005837 -1.092392    -1.0

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '57.177', 'enterprice': '25892.3', 'countrevence': '0', 'unrealprofit': '12052.9116', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '25681.5', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-1, self.sign=-1
--handleKline--:  version='2.0.0', self.name='s_rsrs', self.symbol='BTCUSDT', interval='4h', intervalSec=14400, wid=25, thd=0.6, self.sign=-1, self.total=1478963.5930628998, self.flagDict['side']='sell', self.tradeCount=22, self.count=685
self.closeSec=1693900799, self.tradeDate='20230905', self.openTime='120000', self.closeTime='155959', self.symbol='BTCUSDT', self.open=25681.7, self.close=25724.7, self.high=25747.8, self.low=25660.8, self.vol=20015.69, self.amt=514432580.9002 
127.0.0.1 - - [05/Sep/2023 16:00:01] "POST / HTTP/1.1" 200 -
2023-09-05 16:00:01,687:INFO:s_rsrs:main.py:141:handleKline:2218689: self.closeSec=1693900799, self.tradeDate='20230905', self.openTime='120000', self.closeTime='155959',self.symbol='BTCUSDT',self.open=25681.7, self.close=25724.7, self.high=25747.8, self.low=25660.8, self.vol=20015.69, self.amt=514432580.9002 
2023-09-05 16:00:01,703:INFO:s_rsrs:main.py:142:handleKline:2218689: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime  ...        vol           amt       pct
719  20230904   200000    235959  ...  53696.797  1.386592e+09 -0.002863
720  20230905   000000    035959  ...  22170.000  5.734570e+08  0.002988
721  20230905   040000    075959  ...  39711.730  1.022570e+09 -0.002589
722  20230905   080000    115959  ...  30823.803  7.916805e+08 -0.005125
723  20230905   120000    155959  ...  20015.690  5.144326e+08  0.001674

[5 rows x 11 columns]
2023-09-05 16:00:02,470:INFO:s_rsrs:main.py:151:handleKline:2218689: df_s.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec  ...  index      beta    zscore  signal
719  20230904   200000    235959  1693843199  ...    719  0.426232  0.042741     NaN
720  20230905   000000    035959  1693857599  ...    720  0.002563 -1.143484    -1.0
721  20230905   040000    075959  1693871999  ...    721  0.000329 -1.127232    -1.0
722  20230905   080000    115959  1693886399  ...    722  0.005837 -1.092392    -1.0
723  20230905   120000    155959  1693900799  ...    723  0.005918 -1.076044    -1.0

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '57.177', 'enterprice': '25892.3', 'countrevence': '0', 'unrealprofit': '9575.43992547633', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '25724.82986471', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-1, self.sign=-1


