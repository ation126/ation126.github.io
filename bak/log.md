# 20231023 16:26:07

## /root/FIL/strategy/amihud/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=373746.4768026, self.flagDict['side']='sell', self.tradeCount=2, self.count=46708
self.closeSec=1698049199, self.tradeDate='20231023', self.openTime='161500', self.closeTime='161959', self.symbol='BTCUSDT', self.open=30535.0, self.close=30517.2, self.high=30537.1, self.low=30508.3, self.vol=814.359, self.amt=24855071.796 
127.0.0.1 - - [23/Oct/2023 16:20:10] "POST / HTTP/1.1" 200 -
2023-10-23 16:20:17,659:INFO:amihud:main.py:172:handleKline:2219019: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5951  20231023   155500    155959  ...         0.0        0.0       0
5952  20231023   160000    160459  ...         0.0        0.0       0
5953  20231023   160500    160959  ...         0.0        0.0       0
5954  20231023   161000    161459  ...         0.0        0.0       0
5955  20231023   161500    161959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-10-23 16:20:17,669:INFO:amihud:main.py:175:handleKline:2219019: self.closeSec=1698049199, self.tradeDate='20231023', self.openTime='161500', self.closeTime='161959',self.symbol='BTCUSDT',self.open=30535.0, self.close=30517.2, self.high=30537.1, self.low=30508.3, self.vol=814.359, self.amt=24855071.796, ukdf['pct'].iloc[-1]=-0.000648 , ukdf['amount'].iloc[-1]=24855071.796, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5955, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '13.926', 'enterprice': '26864.9', 'countrevence': '0', 'unrealprofit': '-50810.54742549984', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '30513.51032784', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1
--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=373746.4768026, self.flagDict['side']='sell', self.tradeCount=2, self.count=46709
self.closeSec=1698049499, self.tradeDate='20231023', self.openTime='162000', self.closeTime='162459', self.symbol='BTCUSDT', self.open=30517.2, self.close=30509.1, self.high=30521.2, self.low=30482.9, self.vol=789.282, self.amt=24073848.0241 
127.0.0.1 - - [23/Oct/2023 16:25:01] "POST / HTTP/1.1" 200 -
2023-10-23 16:25:02,889:INFO:amihud:main.py:172:handleKline:2219019: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5952  20231023   160000    160459  ...         0.0        0.0       0
5953  20231023   160500    160959  ...         0.0        0.0       0
5954  20231023   161000    161459  ...         0.0        0.0       0
5955  20231023   161500    161959  ...         0.0        0.0       0
5956  20231023   162000    162459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-10-23 16:25:02,899:INFO:amihud:main.py:175:handleKline:2219019: self.closeSec=1698049499, self.tradeDate='20231023', self.openTime='162000', self.closeTime='162459',self.symbol='BTCUSDT',self.open=30517.2, self.close=30509.1, self.high=30521.2, self.low=30482.9, self.vol=789.282, self.amt=24073848.0241, ukdf['pct'].iloc[-1]=-0.000265 , ukdf['amount'].iloc[-1]=24073848.0241, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5956, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '13.926', 'enterprice': '26864.9', 'countrevence': '0', 'unrealprofit': '-50739.26140476534', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '30508.39141209', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1


## /root/FIL/strategy/factorcheck/log.txt ----- -----


--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.714181719035411, self.count=46706 

self.closeSec=1698047999, self.tradeDate='20231023', self.openTime='155500', self.closeTime='155959', self.symbol='BTCUSDT', self.open=30435.4, self.close=30508.6, self.high=30540.5, self.low=30414.6 
127.0.0.1 - - [23/Oct/2023 16:00:00] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.714181719035411, self.count=46707 

self.closeSec=1698048299, self.tradeDate='20231023', self.openTime='160000', self.closeTime='160459', self.symbol='BTCUSDT', self.open=30508.0, self.close=30491.0, self.high=30542.3, self.low=30455.0 
127.0.0.1 - - [23/Oct/2023 16:05:00] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.714181719035411, self.count=46708 

self.closeSec=1698048599, self.tradeDate='20231023', self.openTime='160500', self.closeTime='160959', self.symbol='BTCUSDT', self.open=30497.5, self.close=30530.1, self.high=30544.8, self.low=30497.4 
127.0.0.1 - - [23/Oct/2023 16:10:00] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [23/Oct/2023 16:15:00] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.714181719035411, self.count=46709 

self.closeSec=1698048899, self.tradeDate='20231023', self.openTime='161000', self.closeTime='161459', self.symbol='BTCUSDT', self.open=30530.1, self.close=30537.0, self.high=30548.6, self.low=30515.2 

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.714181719035411, self.count=46710 

self.closeSec=1698049199, self.tradeDate='20231023', self.openTime='161500', self.closeTime='161959', self.symbol='BTCUSDT', self.open=30535.0, self.close=30517.2, self.high=30537.1, self.low=30508.3 
127.0.0.1 - - [23/Oct/2023 16:20:10] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.714181719035411, self.count=46711 

self.closeSec=1698049499, self.tradeDate='20231023', self.openTime='162000', self.closeTime='162459', self.symbol='BTCUSDT', self.open=30517.2, self.close=30509.1, self.high=30521.2, self.low=30482.9 
127.0.0.1 - - [23/Oct/2023 16:25:01] "POST / HTTP/1.1" 200 -


## /root/FIL/strategy/logic/log.txt ----- -----

2023-10-23 16:00:21,079:DEBUG:logic:main.py:463:getModel:2218526: df_s.iloc[-5:,:] :
          date closeTime     open  ...    alpha58   alpha67   alpha72
5785  20231023    132959  30643.2  ...  54.166667  0.643496  0.381865
5786  20231023    135959  30845.6  ...  54.166667  0.628677  0.365912
5787  20231023    142959  30771.5  ...  54.166667  0.621422  0.354805
5788  20231023    145959  30732.5  ...  54.166667  0.607644  0.348313
5789  20231023    152959  30657.3  ...  54.583333  0.610670  0.340923

[5 rows x 33 columns]
0.559040590405904
acc is : 0.559040590405904
2023-10-23 16:00:21,149:INFO:logic:main.py:468:getModel:2218526: df_pred.iloc[-5:,:] :
     pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
537     0  0.598539  0.401461       0  ...  0.995402   1.0    0.0  1.148447
538     0  0.525689  0.474311       0  ...  0.994141   1.0    0.0  1.146992
539     0  0.515969  0.484031       0  ...  0.991711   1.0    0.0  1.144189
540     0  0.507110  0.492890       1  ...  0.992546   1.0    0.0  1.145152
541     0  0.529850  0.470150       0  ...  0.986898   1.0    0.0  1.138636

[5 rows x 10 columns]
2023-10-23 16:00:21,163:INFO:logic:main.py:478:getModel:2218526: df_panel.iloc[-5:,:] :
    pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
45     0  0.598350  0.401650       0  ...  0.995402   1.0    0.0  1.149177
46     0  0.525160  0.474840       0  ...  0.994141   1.0    0.0  1.145760
47     0  0.516434  0.483566       0  ...  0.991711   1.0    0.0  1.141110
48     0  0.507283  0.492717       1  ...  0.992546   1.0    0.0  1.144208
49     0  0.529850  0.470150       0  ...  0.986898   1.0    0.0  1.138636

[5 rows x 10 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '21.157', 'enterprice': '29765.1', 'countrevence': '0', 'unrealprofit': '15774.92381017586', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '30510.71250698', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}


## /root/FIL/strategy/modifiedmom/log.txt ----- -----

127.0.0.1 - - [23/Oct/2023 15:30:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=23351 

self.closeSec=1698046199, self.tradeDate='20231023', self.openTime='152000', self.closeTime='152959', self.symbol='BTCUSDT', self.open='30676.1', self.close='30683.2'

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=23352 

self.closeSec=1698046799, self.tradeDate='20231023', self.openTime='153000', self.closeTime='153959', self.symbol='BTCUSDT', self.open='30683.3', self.close='30727.3'
127.0.0.1 - - [23/Oct/2023 15:40:01] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [23/Oct/2023 15:50:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=23353 

self.closeSec=1698047399, self.tradeDate='20231023', self.openTime='154000', self.closeTime='154959', self.symbol='BTCUSDT', self.open='30726.4', self.close='30679.5'
127.0.0.1 - - [23/Oct/2023 16:00:02] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=23354 

self.closeSec=1698047999, self.tradeDate='20231023', self.openTime='155000', self.closeTime='155959', self.symbol='BTCUSDT', self.open='30679.5', self.close='30508.6'

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=23355 

self.closeSec=1698048599, self.tradeDate='20231023', self.openTime='160000', self.closeTime='160959', self.symbol='BTCUSDT', self.open='30508', self.close='30530.1'
127.0.0.1 - - [23/Oct/2023 16:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=23356 

self.closeSec=1698049199, self.tradeDate='20231023', self.openTime='161000', self.closeTime='161959', self.symbol='BTCUSDT', self.open='30530.1', self.close='30517.2'
127.0.0.1 - - [23/Oct/2023 16:20:12] "POST / HTTP/1.1" 200 -


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


--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=23354 

self.closeSec=1698046199, self.tradeDate='20231023', self.openTime='152000', self.closeTime='152959', self.symbol='BTCUSDT', self.open='30676.1', self.close='30683.2'
127.0.0.1 - - [23/Oct/2023 15:30:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=23355 

self.closeSec=1698046799, self.tradeDate='20231023', self.openTime='153000', self.closeTime='153959', self.symbol='BTCUSDT', self.open='30683.3', self.close='30727.3'
127.0.0.1 - - [23/Oct/2023 15:40:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=23356 

self.closeSec=1698047399, self.tradeDate='20231023', self.openTime='154000', self.closeTime='154959', self.symbol='BTCUSDT', self.open='30726.4', self.close='30679.5'
127.0.0.1 - - [23/Oct/2023 15:50:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=23357 

self.closeSec=1698047999, self.tradeDate='20231023', self.openTime='155000', self.closeTime='155959', self.symbol='BTCUSDT', self.open='30679.5', self.close='30508.6'
127.0.0.1 - - [23/Oct/2023 16:00:02] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [23/Oct/2023 16:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=23358 

self.closeSec=1698048599, self.tradeDate='20231023', self.openTime='160000', self.closeTime='160959', self.symbol='BTCUSDT', self.open='30508', self.close='30530.1'

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=23359 

self.closeSec=1698049199, self.tradeDate='20231023', self.openTime='161000', self.closeTime='161959', self.symbol='BTCUSDT', self.open='30530.1', self.close='30517.2'
127.0.0.1 - - [23/Oct/2023 16:20:12] "POST / HTTP/1.1" 200 -


## /root/FIL/strategy/similarity/log.txt ----- -----

127.0.0.1 - - [23/Oct/2023 15:30:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=23354 

self.closeSec=1698046199, self.tradeDate='20231023', self.openTime='152000', self.closeTime='152959', self.symbol='BTCUSDT', self.open='30676.1', self.close='30683.2'
127.0.0.1 - - [23/Oct/2023 15:40:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=23355 

self.closeSec=1698046799, self.tradeDate='20231023', self.openTime='153000', self.closeTime='153959', self.symbol='BTCUSDT', self.open='30683.3', self.close='30727.3'
127.0.0.1 - - [23/Oct/2023 15:50:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=23356 

self.closeSec=1698047399, self.tradeDate='20231023', self.openTime='154000', self.closeTime='154959', self.symbol='BTCUSDT', self.open='30726.4', self.close='30679.5'

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=23357 

self.closeSec=1698047999, self.tradeDate='20231023', self.openTime='155000', self.closeTime='155959', self.symbol='BTCUSDT', self.open='30679.5', self.close='30508.6'
127.0.0.1 - - [23/Oct/2023 16:00:02] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=23358 

self.closeSec=1698048599, self.tradeDate='20231023', self.openTime='160000', self.closeTime='160959', self.symbol='BTCUSDT', self.open='30508', self.close='30530.1'
127.0.0.1 - - [23/Oct/2023 16:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=23359 

self.closeSec=1698049199, self.tradeDate='20231023', self.openTime='161000', self.closeTime='161959', self.symbol='BTCUSDT', self.open='30530.1', self.close='30517.2'
127.0.0.1 - - [23/Oct/2023 16:20:12] "POST / HTTP/1.1" 200 -


## /root/FIL/strategy/sr_min/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=1, self.total=996015.990996, self.flagDict['side']='buy', self.tradeCount=1, self.count=46708
self.closeSec=1698049199, self.tradeDate='20231023', self.openTime='161500', self.closeTime='161959', self.symbol='BTCUSDT', self.open=30535.0, self.close=30517.2, self.high=30537.1, self.low=30508.3, self.vol=814.359, self.amt=24855071.796 
127.0.0.1 - - [23/Oct/2023 16:20:10] "POST / HTTP/1.1" 200 -
2023-10-23 16:20:17,619:INFO:sr_min:main.py:172:handleKline:2219263: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5951  20231023   155500    155959  ...         0.0        0.0       0
5952  20231023   160000    160459  ...         0.0        0.0       0
5953  20231023   160500    160959  ...         0.0        0.0       0
5954  20231023   161000    161459  ...         0.0        0.0       0
5955  20231023   161500    161959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-10-23 16:20:17,648:INFO:sr_min:main.py:175:handleKline:2219263: self.closeSec=1698049199, self.tradeDate='20231023', self.openTime='161500', self.closeTime='161959',self.symbol='BTCUSDT',self.open=30535.0, self.close=30517.2, self.high=30537.1, self.low=30508.3, self.vol=814.359, self.amt=24855071.796, ukdf['pct'].iloc[-1]=-0.000648 , ukdf['amount'].iloc[-1]=24855071.796, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5955, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '37.141', 'enterprice': '26844', 'countrevence': '0', 'unrealprofit': '136288.81780354217', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '30513.49780037', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=1
--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=1, self.total=996015.990996, self.flagDict['side']='buy', self.tradeCount=1, self.count=46709
self.closeSec=1698049499, self.tradeDate='20231023', self.openTime='162000', self.closeTime='162459', self.symbol='BTCUSDT', self.open=30517.2, self.close=30509.1, self.high=30521.2, self.low=30482.9, self.vol=789.282, self.amt=24073848.0241 
127.0.0.1 - - [23/Oct/2023 16:25:01] "POST / HTTP/1.1" 200 -
2023-10-23 16:25:02,876:INFO:sr_min:main.py:172:handleKline:2219263: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5952  20231023   160000    160459  ...         0.0        0.0       0
5953  20231023   160500    160959  ...         0.0        0.0       0
5954  20231023   161000    161459  ...         0.0        0.0       0
5955  20231023   161500    161959  ...         0.0        0.0       0
5956  20231023   162000    162459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-10-23 16:25:02,879:INFO:sr_min:main.py:175:handleKline:2219263: self.closeSec=1698049499, self.tradeDate='20231023', self.openTime='162000', self.closeTime='162459',self.symbol='BTCUSDT',self.open=30517.2, self.close=30509.1, self.high=30521.2, self.low=30482.9, self.vol=789.282, self.amt=24073848.0241, ukdf['pct'].iloc[-1]=-0.000265 , ukdf['amount'].iloc[-1]=24073848.0241, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5956, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '37.141', 'enterprice': '26844', 'countrevence': '0', 'unrealprofit': '136099.16143643469', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '30508.39141209', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=1


## /root/FIL/strategy/s_rsrs/log.txt ----- -----

721  20231023   040000    075959  1698019199  ...    721  0.864482  0.277100     NaN
722  20231023   080000    115959  1698033599  ...    722  0.870523  0.275271     NaN

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '41.361', 'enterprice': '29539.2', 'countrevence': '0', 'unrealprofit': '49335.4008', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '30732', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-9223372036854775808, self.sign=1
--handleKline--:  version='2.0.0', self.name='s_rsrs', self.symbol='BTCUSDT', interval='4h', intervalSec=14400, wid=25, thd=0.6, self.sign=1, self.total=1220549.0803488, self.flagDict['side']='buy', self.tradeCount=37, self.count=973
self.closeSec=1698047999, self.tradeDate='20231023', self.openTime='120000', self.closeTime='155959', self.symbol='BTCUSDT', self.open=30723.9, self.close=30508.6, self.high=30990.0, self.low=30414.6, self.vol=109840.976, self.amt=3375396741.76706 
127.0.0.1 - - [23/Oct/2023 16:00:01] "POST / HTTP/1.1" 200 -
2023-10-23 16:00:01,629:INFO:s_rsrs:main.py:141:handleKline:2218689: self.closeSec=1698047999, self.tradeDate='20231023', self.openTime='120000', self.closeTime='155959',self.symbol='BTCUSDT',self.open=30723.9, self.close=30508.6, self.high=30990.0, self.low=30414.6, self.vol=109840.976, self.amt=3375396741.76706 
2023-10-23 16:00:01,644:INFO:s_rsrs:main.py:142:handleKline:2218689: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime  ...         vol           amt       pct
719  20231022   200000    235959  ...   23241.182  6.941179e+08 -0.002696
720  20231023   000000    035959  ...   17704.232  5.288255e+08  0.000490
721  20231023   040000    075959  ...   33501.912  1.001635e+09  0.005082
722  20231023   080000    115959  ...  128693.194  3.906155e+09  0.024765
723  20231023   120000    155959  ...  109840.976  3.375397e+09 -0.007011

[5 rows x 11 columns]
2023-10-23 16:00:02,366:INFO:s_rsrs:main.py:151:handleKline:2218689: df_s.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec  ...  index      beta    zscore  signal
719  20231022   200000    235959  1697990399  ...    719  0.948686  0.433889     NaN
720  20231023   000000    035959  1698004799  ...    720  0.896727  0.339813     NaN
721  20231023   040000    075959  1698019199  ...    721  0.864482  0.277100     NaN
722  20231023   080000    115959  1698033599  ...    722  0.870523  0.275271     NaN
723  20231023   120000    155959  1698047999  ...    723  0.892948  0.299264     NaN

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '41.361', 'enterprice': '29539.2', 'countrevence': '0', 'unrealprofit': '40153.2588', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '30510', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-9223372036854775808, self.sign=1


