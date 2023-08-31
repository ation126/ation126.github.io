# 20230831 16:26:01

## /root/FIL/strategy/amihud/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=373746.4768026, self.flagDict['side']='sell', self.tradeCount=2, self.count=31444
self.closeSec=1693469999, self.tradeDate='20230831', self.openTime='161500', self.closeTime='161959', self.symbol='BTCUSDT', self.open=27236.2, self.close=27254.0, self.high=27255.6, self.low=27236.2, self.vol=248.679, self.amt=6775411.5284 
127.0.0.1 - - [31/Aug/2023 16:20:01] "POST / HTTP/1.1" 200 -
2023-08-31 16:20:05,151:INFO:amihud:main.py:172:handleKline:2219019: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5939  20230831   155500    155959  ...         0.0        0.0       0
5940  20230831   160000    160459  ...         0.0        0.0       0
5941  20230831   160500    160959  ...         0.0        0.0       0
5942  20230831   161000    161459  ...         0.0        0.0       0
5943  20230831   161500    161959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-08-31 16:20:05,152:INFO:amihud:main.py:175:handleKline:2219019: self.closeSec=1693469999, self.tradeDate='20230831', self.openTime='161500', self.closeTime='161959',self.symbol='BTCUSDT',self.open=27236.2, self.close=27254.0, self.high=27255.6, self.low=27236.2, self.vol=248.679, self.amt=6775411.5284, ukdf['pct'].iloc[-1]=0.000654 , ukdf['amount'].iloc[-1]=6775411.5284, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5943, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '13.926', 'enterprice': '26864.9', 'countrevence': '0', 'unrealprofit': '-5406.03703320318', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '27253.09740293', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1
127.0.0.1 - - [31/Aug/2023 16:25:00] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=373746.4768026, self.flagDict['side']='sell', self.tradeCount=2, self.count=31445
self.closeSec=1693470299, self.tradeDate='20230831', self.openTime='162000', self.closeTime='162459', self.symbol='BTCUSDT', self.open=27253.9, self.close=27232.1, self.high=27255.0, self.low=27225.4, self.vol=193.365, self.amt=5266167.4355 
2023-08-31 16:25:00,776:INFO:amihud:main.py:172:handleKline:2219019: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5940  20230831   160000    160459  ...         0.0        0.0       0
5941  20230831   160500    160959  ...         0.0        0.0       0
5942  20230831   161000    161459  ...         0.0        0.0       0
5943  20230831   161500    161959  ...         0.0        0.0       0
5944  20230831   162000    162459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-08-31 16:25:00,776:INFO:amihud:main.py:175:handleKline:2219019: self.closeSec=1693470299, self.tradeDate='20230831', self.openTime='162000', self.closeTime='162459',self.symbol='BTCUSDT',self.open=27253.9, self.close=27232.1, self.high=27255.0, self.low=27225.4, self.vol=193.365, self.amt=5266167.4355, ukdf['pct'].iloc[-1]=-0.000804 , ukdf['amount'].iloc[-1]=5266167.4355, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5944, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '13.926', 'enterprice': '26864.9', 'countrevence': '0', 'unrealprofit': '-5113.6272', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '27232.1', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1


## /root/FIL/strategy/factorcheck/log.txt ----- -----


--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.714181719035411, self.count=31442 

self.closeSec=1693468799, self.tradeDate='20230831', self.openTime='155500', self.closeTime='155959', self.symbol='BTCUSDT', self.open=27232.6, self.close=27249.1, self.high=27250.3, self.low=27232.6 
127.0.0.1 - - [31/Aug/2023 16:00:00] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [31/Aug/2023 16:05:00] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.714181719035411, self.count=31443 

self.closeSec=1693469099, self.tradeDate='20230831', self.openTime='160000', self.closeTime='160459', self.symbol='BTCUSDT', self.open=27249.2, self.close=27253.3, self.high=27263.1, self.low=27249.1 
127.0.0.1 - - [31/Aug/2023 16:10:00] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.714181719035411, self.count=31444 

self.closeSec=1693469399, self.tradeDate='20230831', self.openTime='160500', self.closeTime='160959', self.symbol='BTCUSDT', self.open=27251.7, self.close=27231.4, self.high=27251.7, self.low=27227.3 
127.0.0.1 - - [31/Aug/2023 16:15:00] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.714181719035411, self.count=31445 

self.closeSec=1693469699, self.tradeDate='20230831', self.openTime='161000', self.closeTime='161459', self.symbol='BTCUSDT', self.open=27231.4, self.close=27236.2, self.high=27239.4, self.low=27223.6 

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.714181719035411, self.count=31446 

self.closeSec=1693469999, self.tradeDate='20230831', self.openTime='161500', self.closeTime='161959', self.symbol='BTCUSDT', self.open=27236.2, self.close=27254.0, self.high=27255.6, self.low=27236.2 
127.0.0.1 - - [31/Aug/2023 16:20:01] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [31/Aug/2023 16:25:00] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.714181719035411, self.count=31447 

self.closeSec=1693470299, self.tradeDate='20230831', self.openTime='162000', self.closeTime='162459', self.symbol='BTCUSDT', self.open=27253.9, self.close=27232.1, self.high=27255.0, self.low=27225.4 


## /root/FIL/strategy/logic/log.txt ----- -----

2023-08-31 16:00:17,543:DEBUG:logic:main.py:463:getModel:2218526: df_s.iloc[-5:,:] :
          date closeTime     open  ...    alpha58   alpha67   alpha72
5785  20230831    132959  27240.2  ...  49.583333  0.534291  0.537884
5786  20230831    135959  27234.9  ...  49.583333  0.534797  0.530358
5787  20230831    142959  27237.6  ...  49.583333  0.532029  0.524961
5788  20230831    145959  27225.4  ...  49.583333  0.535887  0.517364
5789  20230831    152959  27244.5  ...  50.000000  0.542640  0.505779

[5 rows x 33 columns]
0.5424354243542435
acc is : 0.5424354243542435
2023-08-31 16:00:17,603:INFO:logic:main.py:468:getModel:2218526: df_pred.iloc[-5:,:] :
     pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
537     1  0.484834  0.515166       1  ...  0.980536   1.0    0.0  1.040835
538     1  0.483491  0.516509       0  ...  0.980097   1.0    0.0  1.040369
539     1  0.477405  0.522595       1  ...  0.980788   1.0    0.0  1.041102
540     1  0.486704  0.513296       1  ...  0.982001   1.0    0.0  1.042390
541     1  0.495839  0.504161       0  ...  0.980953   1.0    0.0  1.041278

[5 rows x 10 columns]
2023-08-31 16:00:17,614:INFO:logic:main.py:478:getModel:2218526: df_panel.iloc[-5:,:] :
    pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
45     1  0.484749  0.515251       1  ...  0.980536   1.0    0.0  1.046091
46     1  0.483733  0.516267       0  ...  0.980097   1.0    0.0  1.043051
47     1  0.477315  0.522685       1  ...  0.980788   1.0    0.0  1.044315
48     1  0.486833  0.513167       1  ...  0.982001   1.0    0.0  1.044697
49     1  0.495839  0.504161       0  ...  0.980953   1.0    0.0  1.041278

[5 rows x 10 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '26.311', 'enterprice': '27227', 'countrevence': '0', 'unrealprofit': '718.2903', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '27254.3', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}


## /root/FIL/strategy/modifiedmom/log.txt ----- -----

127.0.0.1 - - [31/Aug/2023 15:30:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=15719 

self.closeSec=1693466999, self.tradeDate='20230831', self.openTime='152000', self.closeTime='152959', self.symbol='BTCUSDT', self.open='27243.7', self.close='27278.2'

--handleKline--:  127.0.0.1 - - [31/Aug/2023 15:40:01] "POST / HTTP/1.1" 200 -
self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=15720 

self.closeSec=1693467599, self.tradeDate='20230831', self.openTime='153000', self.closeTime='153959', self.symbol='BTCUSDT', self.open='27278.2', self.close='27261.4'
127.0.0.1 - - [31/Aug/2023 15:50:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=15721 

self.closeSec=1693468199, self.tradeDate='20230831', self.openTime='154000', self.closeTime='154959', self.symbol='BTCUSDT', self.open='27261.4', self.close='27226.4'
127.0.0.1 - - [31/Aug/2023 16:00:02] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=15722 

self.closeSec=1693468799, self.tradeDate='20230831', self.openTime='155000', self.closeTime='155959', self.symbol='BTCUSDT', self.open='27226.4', self.close='27249.1'
127.0.0.1 - - [31/Aug/2023 16:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=15723 

self.closeSec=1693469399, self.tradeDate='20230831', self.openTime='160000', self.closeTime='160959', self.symbol='BTCUSDT', self.open='27249.2', self.close='27231.5'

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=15724 

self.closeSec=1693469999, self.tradeDate='20230831', self.openTime='161000', self.closeTime='161959', self.symbol='BTCUSDT', self.open='27231.4', self.close='27254'
127.0.0.1 - - [31/Aug/2023 16:20:04] "POST / HTTP/1.1" 200 -


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


--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=15722 

self.closeSec=1693466999, self.tradeDate='20230831', self.openTime='152000', self.closeTime='152959', self.symbol='BTCUSDT', self.open='27243.7', self.close='27278.2'
127.0.0.1 - - [31/Aug/2023 15:30:01] "POST / HTTP/1.1" 200 -

--handleKline--: 127.0.0.1 - - [31/Aug/2023 15:40:01] "POST / HTTP/1.1" 200 -
 self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=15723 

self.closeSec=1693467599, self.tradeDate='20230831', self.openTime='153000', self.closeTime='153959', self.symbol='BTCUSDT', self.open='27278.2', self.close='27261.4'
127.0.0.1 - - [31/Aug/2023 15:50:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=15724 

self.closeSec=1693468199, self.tradeDate='20230831', self.openTime='154000', self.closeTime='154959', self.symbol='BTCUSDT', self.open='27261.4', self.close='27226.4'

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=15725 

self.closeSec=1693468799, self.tradeDate='20230831', self.openTime='155000', self.closeTime='155959', self.symbol='BTCUSDT', self.open='27226.4', self.close='27249.1'
127.0.0.1 - - [31/Aug/2023 16:00:02] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [31/Aug/2023 16:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=15726 

self.closeSec=1693469399, self.tradeDate='20230831', self.openTime='160000', self.closeTime='160959', self.symbol='BTCUSDT', self.open='27249.2', self.close='27231.5'

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=15727 

self.closeSec=1693469999, self.tradeDate='20230831', self.openTime='161000', self.closeTime='161959', self.symbol='BTCUSDT', self.open='27231.4', self.close='27254'
127.0.0.1 - - [31/Aug/2023 16:20:04] "POST / HTTP/1.1" 200 -


## /root/FIL/strategy/similarity/log.txt ----- -----

127.0.0.1 - - [31/Aug/2023 15:30:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=15722 

self.closeSec=1693466999, self.tradeDate='20230831', self.openTime='152000', self.closeTime='152959', self.symbol='BTCUSDT', self.open='27243.7', self.close='27278.2'
127.0.0.1 - - [31/Aug/2023 15:40:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=15723 

self.closeSec=1693467599, self.tradeDate='20230831', self.openTime='153000', self.closeTime='153959', self.symbol='BTCUSDT', self.open='27278.2', self.close='27261.4'
127.0.0.1 - - [31/Aug/2023 15:50:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=15724 

self.closeSec=1693468199, self.tradeDate='20230831', self.openTime='154000', self.closeTime='154959', self.symbol='BTCUSDT', self.open='27261.4', self.close='27226.4'

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=15725 

self.closeSec=1693468799, self.tradeDate='20230831', self.openTime='155000', self.closeTime='155959', self.symbol='BTCUSDT', self.open='27226.4', self.close='27249.1'
127.0.0.1 - - [31/Aug/2023 16:00:02] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=15726 

self.closeSec=1693469399, self.tradeDate='20230831', self.openTime='160000', self.closeTime='160959', self.symbol='BTCUSDT', self.open='27249.2', self.close='27231.5'
127.0.0.1 - - [31/Aug/2023 16:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=15727 

self.closeSec=1693469999, self.tradeDate='20230831', self.openTime='161000', self.closeTime='161959', self.symbol='BTCUSDT', self.open='27231.4', self.close='27254'
127.0.0.1 - - [31/Aug/2023 16:20:04] "POST / HTTP/1.1" 200 -


## /root/FIL/strategy/sr_min/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=1, self.total=996015.990996, self.flagDict['side']='buy', self.tradeCount=1, self.count=31444
self.closeSec=1693469999, self.tradeDate='20230831', self.openTime='161500', self.closeTime='161959', self.symbol='BTCUSDT', self.open=27236.2, self.close=27254.0, self.high=27255.6, self.low=27236.2, self.vol=248.679, self.amt=6775411.5284 
127.0.0.1 - - [31/Aug/2023 16:20:01] "POST / HTTP/1.1" 200 -
2023-08-31 16:20:05,151:INFO:sr_min:main.py:172:handleKline:2219263: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5939  20230831   155500    155959  ...         0.0        0.0       0
5940  20230831   160000    160459  ...         0.0        0.0       0
5941  20230831   160500    160959  ...         0.0        0.0       0
5942  20230831   161000    161459  ...         0.0        0.0       0
5943  20230831   161500    161959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-08-31 16:20:05,153:INFO:sr_min:main.py:175:handleKline:2219263: self.closeSec=1693469999, self.tradeDate='20230831', self.openTime='161500', self.closeTime='161959',self.symbol='BTCUSDT',self.open=27236.2, self.close=27254.0, self.high=27255.6, self.low=27236.2, self.vol=248.679, self.amt=6775411.5284, ukdf['pct'].iloc[-1]=0.000654 , ukdf['amount'].iloc[-1]=6775411.5284, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5943, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '37.141', 'enterprice': '26844', 'countrevence': '0', 'unrealprofit': '15194.28664222313', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '27253.09740293', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=1
127.0.0.1 - - [31/Aug/2023 16:25:00] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=1, self.total=996015.990996, self.flagDict['side']='buy', self.tradeCount=1, self.count=31445
self.closeSec=1693470299, self.tradeDate='20230831', self.openTime='162000', self.closeTime='162459', self.symbol='BTCUSDT', self.open=27253.9, self.close=27232.1, self.high=27255.0, self.low=27225.4, self.vol=193.365, self.amt=5266167.4355 
2023-08-31 16:25:00,777:INFO:sr_min:main.py:172:handleKline:2219263: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5940  20230831   160000    160459  ...         0.0        0.0       0
5941  20230831   160500    160959  ...         0.0        0.0       0
5942  20230831   161000    161459  ...         0.0        0.0       0
5943  20230831   161500    161959  ...         0.0        0.0       0
5944  20230831   162000    162459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-08-31 16:25:00,777:INFO:sr_min:main.py:175:handleKline:2219263: self.closeSec=1693470299, self.tradeDate='20230831', self.openTime='162000', self.closeTime='162459',self.symbol='BTCUSDT',self.open=27253.9, self.close=27232.1, self.high=27255.0, self.low=27225.4, self.vol=193.365, self.amt=5266167.4355, ukdf['pct'].iloc[-1]=-0.000804 , ukdf['amount'].iloc[-1]=5266167.4355, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5944, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '37.141', 'enterprice': '26844', 'countrevence': '0', 'unrealprofit': '14414.4221', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '27232.1', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=1


## /root/FIL/strategy/s_rsrs/log.txt ----- -----

721  20230831   040000    075959  1693439999  ...    721  0.943311  2.238721     1.0
722  20230831   080000    115959  1693454399  ...    722  0.898518  2.013491     1.0

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '57.252', 'enterprice': '27833.8', 'countrevence': '0', 'unrealprofit': '-35834.0268', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '27207.9', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=1, self.sign=1
127.0.0.1 - - [31/Aug/2023 16:00:01] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='s_rsrs', self.symbol='BTCUSDT', interval='4h', intervalSec=14400, wid=25, thd=0.6, self.sign=1, self.total=1591947.1768824002, self.flagDict['side']='buy', self.tradeCount=21, self.count=655
self.closeSec=1693468799, self.tradeDate='20230831', self.openTime='120000', self.closeTime='155959', self.symbol='BTCUSDT', self.open=27207.8, self.close=27249.1, self.high=27285.0, self.low=27200.8, self.vol=16560.471, self.amt=451144468.4109 
2023-08-31 16:00:01,588:INFO:s_rsrs:main.py:141:handleKline:2218689: self.closeSec=1693468799, self.tradeDate='20230831', self.openTime='120000', self.closeTime='155959',self.symbol='BTCUSDT',self.open=27207.8, self.close=27249.1, self.high=27285.0, self.low=27200.8, self.vol=16560.471, self.amt=451144468.4109 
2023-08-31 16:00:01,601:INFO:s_rsrs:main.py:142:handleKline:2218689: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime  ...         vol           amt       pct
719  20230830   200000    235959  ...  125823.008  3.427674e+09 -0.004813
720  20230831   000000    035959  ...   42830.020  1.163731e+09 -0.000908
721  20230831   040000    075959  ...   21666.717  5.907011e+08  0.004535
722  20230831   080000    115959  ...   16078.296  4.374189e+08 -0.003027
723  20230831   120000    155959  ...   16560.471  4.511445e+08  0.001514

[5 rows x 11 columns]
2023-08-31 16:00:02,295:INFO:s_rsrs:main.py:151:handleKline:2218689: df_s.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec  ...  index      beta    zscore  signal
719  20230830   200000    235959  1693411199  ...    719  1.008007  2.675917     1.0
720  20230831   000000    035959  1693425599  ...    720  0.982513  2.467692     1.0
721  20230831   040000    075959  1693439999  ...    721  0.943311  2.238721     1.0
722  20230831   080000    115959  1693454399  ...    722  0.898518  2.013491     1.0
723  20230831   120000    155959  1693468799  ...    723  0.848542  1.788930     1.0

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '57.252', 'enterprice': '27833.8', 'countrevence': '0', 'unrealprofit': '-33440.28712574784', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '27249.71058608', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=1, self.sign=1


