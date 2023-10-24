# 20231024 16:26:09

## /root/FIL/strategy/amihud/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=373746.4768026, self.flagDict['side']='sell', self.tradeCount=2, self.count=46996
self.closeSec=1698135599, self.tradeDate='20231024', self.openTime='161500', self.closeTime='161959', self.symbol='BTCUSDT', self.open=34057.0, self.close=34029.8, self.high=34087.7, self.low=34000.0, self.vol=1303.588, self.amt=44366047.569 
127.0.0.1 - - [24/Oct/2023 16:20:05] "POST / HTTP/1.1" 200 -
2023-10-24 16:20:08,800:INFO:amihud:main.py:172:handleKline:2219019: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5951  20231024   155500    155959  ...         0.0        0.0       0
5952  20231024   160000    160459  ...         0.0        0.0       0
5953  20231024   160500    160959  ...         0.0        0.0       0
5954  20231024   161000    161459  ...         0.0        0.0       0
5955  20231024   161500    161959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-10-24 16:20:08,805:INFO:amihud:main.py:175:handleKline:2219019: self.closeSec=1698135599, self.tradeDate='20231024', self.openTime='161500', self.closeTime='161959',self.symbol='BTCUSDT',self.open=34057.0, self.close=34029.8, self.high=34087.7, self.low=34000.0, self.vol=1303.588, self.amt=44366047.569, ukdf['pct'].iloc[-1]=-0.000983 , ukdf['amount'].iloc[-1]=44366047.569, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5955, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '13.926', 'enterprice': '26864.9', 'countrevence': '0', 'unrealprofit': '-99658.6338', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '34021.2', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1
--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=373746.4768026, self.flagDict['side']='sell', self.tradeCount=2, self.count=46997
self.closeSec=1698135899, self.tradeDate='20231024', self.openTime='162000', self.closeTime='162459', self.symbol='BTCUSDT', self.open=34029.8, self.close=34119.1, self.high=34119.9, self.low=34012.8, self.vol=1128.488, self.amt=38457741.2268 
127.0.0.1 - - [24/Oct/2023 16:25:01] "POST / HTTP/1.1" 200 -
2023-10-24 16:25:03,571:INFO:amihud:main.py:172:handleKline:2219019: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5952  20231024   160000    160459  ...         0.0        0.0       0
5953  20231024   160500    160959  ...         0.0        0.0       0
5954  20231024   161000    161459  ...         0.0        0.0       0
5955  20231024   161500    161959  ...         0.0        0.0       0
5956  20231024   162000    162459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-10-24 16:25:03,573:INFO:amihud:main.py:175:handleKline:2219019: self.closeSec=1698135899, self.tradeDate='20231024', self.openTime='162000', self.closeTime='162459',self.symbol='BTCUSDT',self.open=34029.8, self.close=34119.1, self.high=34119.9, self.low=34012.8, self.vol=1128.488, self.amt=38457741.2268, ukdf['pct'].iloc[-1]=0.002624 , ukdf['amount'].iloc[-1]=38457741.2268, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5956, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '13.926', 'enterprice': '26864.9', 'countrevence': '0', 'unrealprofit': '-101033.13', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '34119.9', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1


## /root/FIL/strategy/factorcheck/log.txt ----- -----


--handleKline--: 127.0.0.1 - - [24/Oct/2023 16:00:00] "POST / HTTP/1.1" 200 -
 version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.714181719035411, self.count=46994 

self.closeSec=1698134399, self.tradeDate='20231024', self.openTime='155500', self.closeTime='155959', self.symbol='BTCUSDT', self.open=34005.1, self.close=34025.8, self.high=34034.0, self.low=33992.4 

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.714181719035411, self.count=46995 

self.closeSec=1698134699, self.tradeDate='20231024', self.openTime='160000', self.closeTime='160459', self.symbol='BTCUSDT', self.open=34025.8, self.close=34000.0, self.high=34037.7, self.low=33966.0 
127.0.0.1 - - [24/Oct/2023 16:05:00] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.714181719035411, self.count=46996 

self.closeSec=1698134999, self.tradeDate='20231024', self.openTime='160500', self.closeTime='160959', self.symbol='BTCUSDT', self.open=34011.5, self.close=34082.9, self.high=34138.7, self.low=34011.5 
127.0.0.1 - - [24/Oct/2023 16:10:00] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.714181719035411, self.count=46997 

self.closeSec=1698135299, self.tradeDate='20231024', self.openTime='161000', self.closeTime='161459', self.symbol='BTCUSDT', self.open=34082.9, self.close=34063.3, self.high=34166.3, self.low=34043.1 
127.0.0.1 - - [24/Oct/2023 16:15:00] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.714181719035411, self.count=46998 

self.closeSec=1698135599, self.tradeDate='20231024', self.openTime='161500', self.closeTime='161959', self.symbol='BTCUSDT', self.open=34057.0, self.close=34029.8, self.high=34087.7, self.low=34000.0 
127.0.0.1 - - [24/Oct/2023 16:20:05] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.714181719035411, self.count=46999 

self.closeSec=1698135899, self.tradeDate='20231024', self.openTime='162000', self.closeTime='162459', self.symbol='BTCUSDT', self.open=34029.8, self.close=34119.1, self.high=34119.9, self.low=34012.8 
127.0.0.1 - - [24/Oct/2023 16:25:01] "POST / HTTP/1.1" 200 -


## /root/FIL/strategy/logic/log.txt ----- -----

2023-10-24 16:00:18,479:DEBUG:logic:main.py:463:getModel:2218526: df_s.iloc[-5:,:] :
          date closeTime     open  ...    alpha58   alpha67   alpha72
5785  20231024    132959  34392.2  ...  57.500000  0.728030  0.278120
5786  20231024    135959  34580.9  ...  57.500000  0.665087  0.284223
5787  20231024    142959  33902.3  ...  57.083333  0.660391  0.290568
5788  20231024    145959  33842.0  ...  57.500000  0.666082  0.294956
5789  20231024    152959  33979.5  ...  57.500000  0.647158  0.301674

[5 rows x 33 columns]
0.5479704797047971
acc is : 0.5479704797047971
2023-10-24 16:00:18,538:INFO:logic:main.py:468:getModel:2218526: df_pred.iloc[-5:,:] :
     pred    prob_0    prob_1  actual  ...       nav  sign   cost_        bm
537     0  0.602075  0.397925       0  ...  1.118918   1.0  0.0000  1.264157
538     1  0.395926  0.604074       0  ...  1.118933  -1.0 -0.0016  1.262118
539     0  0.538838  0.461162       1  ...  1.114655  -1.0  0.0000  1.266943
540     0  0.566315  0.433685       0  ...  1.105612   1.0 -0.0016  1.258691
541     1  0.477088  0.522912       1  ...  1.114458   1.0  0.0000  1.268763

[5 rows x 10 columns]
2023-10-24 16:00:18,550:INFO:logic:main.py:478:getModel:2218526: df_panel.iloc[-5:,:] :
    pred    prob_0    prob_1  actual  ...       nav  sign   cost_        bm
45     0  0.600205  0.399795       0  ...  1.118918   1.0  0.0000  1.267850
46     1  0.394219  0.605781       0  ...  1.118933  -1.0 -0.0016  1.266733
47     0  0.537564  0.462436       1  ...  1.114655  -1.0  0.0000  1.270448
48     0  0.564476  0.435524       0  ...  1.105612   1.0 -0.0016  1.258320
49     1  0.477088  0.522912       1  ...  1.114458   1.0  0.0000  1.268763

[5 rows x 10 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '21.245', 'enterprice': '33811.2', 'countrevence': '0', 'unrealprofit': '4198.012', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '34008.8', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}


## /root/FIL/strategy/modifiedmom/log.txt ----- -----


--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=23495 

self.closeSec=1698132599, self.tradeDate='20231024', self.openTime='152000', self.closeTime='152959', self.symbol='BTCUSDT', self.open='33970.2', self.close='33755.7'
127.0.0.1 - - [24/Oct/2023 15:30:01] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [24/Oct/2023 15:40:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=23496 

self.closeSec=1698133199, self.tradeDate='20231024', self.openTime='153000', self.closeTime='153959', self.symbol='BTCUSDT', self.open='33747.7', self.close='33796.8'

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=23497 

self.closeSec=1698133799, self.tradeDate='20231024', self.openTime='154000', self.closeTime='154959', self.symbol='BTCUSDT', self.open='33800', self.close='33928.1'
127.0.0.1 - - [24/Oct/2023 15:50:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=23498 

self.closeSec=1698134399, self.tradeDate='20231024', self.openTime='155000', self.closeTime='155959', self.symbol='BTCUSDT', self.open='33929.8', self.close='34025.8'
127.0.0.1 - - [24/Oct/2023 16:00:01] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [24/Oct/2023 16:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=23499 

self.closeSec=1698134999, self.tradeDate='20231024', self.openTime='160000', self.closeTime='160959', self.symbol='BTCUSDT', self.open='34025.8', self.close='34082.9'

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=23500 

self.closeSec=1698135599, self.tradeDate='20231024', self.openTime='161000', self.closeTime='161959', self.symbol='BTCUSDT', self.open='34082.9', self.close='34029.8'
127.0.0.1 - - [24/Oct/2023 16:20:06] "POST / HTTP/1.1" 200 -


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


--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=23498 

self.closeSec=1698132599, self.tradeDate='20231024', self.openTime='152000', self.closeTime='152959', self.symbol='BTCUSDT', self.open='33970.2', self.close='33755.7'
127.0.0.1 - - [24/Oct/2023 15:30:01] "POST / HTTP/1.1" 200 -

--handleKline--: 127.0.0.1 - - [24/Oct/2023 15:40:01] "POST / HTTP/1.1" 200 -
 self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=23499 

self.closeSec=1698133199, self.tradeDate='20231024', self.openTime='153000', self.closeTime='153959', self.symbol='BTCUSDT', self.open='33747.7', self.close='33796.8'

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=23500 

self.closeSec=1698133799, self.tradeDate='20231024', self.openTime='154000', self.closeTime='154959', self.symbol='BTCUSDT', self.open='33800', self.close='33928.1'
127.0.0.1 - - [24/Oct/2023 15:50:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=23501 

self.closeSec=1698134399, self.tradeDate='20231024', self.openTime='155000', self.closeTime='155959', self.symbol='BTCUSDT', self.open='33929.8', self.close='34025.8'
127.0.0.1 - - [24/Oct/2023 16:00:01] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [24/Oct/2023 16:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=23502 

self.closeSec=1698134999, self.tradeDate='20231024', self.openTime='160000', self.closeTime='160959', self.symbol='BTCUSDT', self.open='34025.8', self.close='34082.9'

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=23503 

self.closeSec=1698135599, self.tradeDate='20231024', self.openTime='161000', self.closeTime='161959', self.symbol='BTCUSDT', self.open='34082.9', self.close='34029.8'
127.0.0.1 - - [24/Oct/2023 16:20:06] "POST / HTTP/1.1" 200 -


## /root/FIL/strategy/similarity/log.txt ----- -----


--handleKline--: 127.0.0.1 - - [24/Oct/2023 15:30:01] "POST / HTTP/1.1" 200 -
 self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=23498 

self.closeSec=1698132599, self.tradeDate='20231024', self.openTime='152000', self.closeTime='152959', self.symbol='BTCUSDT', self.open='33970.2', self.close='33755.7'
127.0.0.1 - - [24/Oct/2023 15:40:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=23499 

self.closeSec=1698133199, self.tradeDate='20231024', self.openTime='153000', self.closeTime='153959', self.symbol='BTCUSDT', self.open='33747.7', self.close='33796.8'

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=23500 

self.closeSec=1698133799, self.tradeDate='20231024', self.openTime='154000', self.closeTime='154959', self.symbol='BTCUSDT', self.open='33800', self.close='33928.1'
127.0.0.1 - - [24/Oct/2023 15:50:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=23501 

self.closeSec=1698134399, self.tradeDate='20231024', self.openTime='155000', self.closeTime='155959', self.symbol='BTCUSDT', self.open='33929.8', self.close='34025.8'
127.0.0.1 - - [24/Oct/2023 16:00:01] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [24/Oct/2023 16:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=23502 

self.closeSec=1698134999, self.tradeDate='20231024', self.openTime='160000', self.closeTime='160959', self.symbol='BTCUSDT', self.open='34025.8', self.close='34082.9'

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=23503 

self.closeSec=1698135599, self.tradeDate='20231024', self.openTime='161000', self.closeTime='161959', self.symbol='BTCUSDT', self.open='34082.9', self.close='34029.8'
127.0.0.1 - - [24/Oct/2023 16:20:06] "POST / HTTP/1.1" 200 -


## /root/FIL/strategy/sr_min/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=1, self.total=996015.990996, self.flagDict['side']='buy', self.tradeCount=1, self.count=46996
self.closeSec=1698135599, self.tradeDate='20231024', self.openTime='161500', self.closeTime='161959', self.symbol='BTCUSDT', self.open=34057.0, self.close=34029.8, self.high=34087.7, self.low=34000.0, self.vol=1303.588, self.amt=44366047.569 
127.0.0.1 - - [24/Oct/2023 16:20:05] "POST / HTTP/1.1" 200 -
2023-10-24 16:20:08,797:INFO:sr_min:main.py:172:handleKline:2219263: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5951  20231024   155500    155959  ...         0.0        0.0       0
5952  20231024   160000    160459  ...         0.0        0.0       0
5953  20231024   160500    160959  ...         0.0        0.0       0
5954  20231024   161000    161459  ...         0.0        0.0       0
5955  20231024   161500    161959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-10-24 16:20:08,807:INFO:sr_min:main.py:175:handleKline:2219263: self.closeSec=1698135599, self.tradeDate='20231024', self.openTime='161500', self.closeTime='161959',self.symbol='BTCUSDT',self.open=34057.0, self.close=34029.8, self.high=34087.7, self.low=34000.0, self.vol=1303.588, self.amt=44366047.569, ukdf['pct'].iloc[-1]=-0.000983 , ukdf['amount'].iloc[-1]=44366047.569, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5955, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '37.141', 'enterprice': '26844', 'countrevence': '0', 'unrealprofit': '266568.3852', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '34021.2', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=1
--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=1, self.total=996015.990996, self.flagDict['side']='buy', self.tradeCount=1, self.count=46997
self.closeSec=1698135899, self.tradeDate='20231024', self.openTime='162000', self.closeTime='162459', self.symbol='BTCUSDT', self.open=34029.8, self.close=34119.1, self.high=34119.9, self.low=34012.8, self.vol=1128.488, self.amt=38457741.2268 
127.0.0.1 - - [24/Oct/2023 16:25:01] "POST / HTTP/1.1" 200 -
2023-10-24 16:25:03,570:INFO:sr_min:main.py:172:handleKline:2219263: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5952  20231024   160000    160459  ...         0.0        0.0       0
5953  20231024   160500    160959  ...         0.0        0.0       0
5954  20231024   161000    161459  ...         0.0        0.0       0
5955  20231024   161500    161959  ...         0.0        0.0       0
5956  20231024   162000    162459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-10-24 16:25:03,573:INFO:sr_min:main.py:175:handleKline:2219263: self.closeSec=1698135899, self.tradeDate='20231024', self.openTime='162000', self.closeTime='162459',self.symbol='BTCUSDT',self.open=34029.8, self.close=34119.1, self.high=34119.9, self.low=34012.8, self.vol=1128.488, self.amt=38457741.2268, ukdf['pct'].iloc[-1]=0.002624 , ukdf['amount'].iloc[-1]=38457741.2268, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5956, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '37.141', 'enterprice': '26844', 'countrevence': '0', 'unrealprofit': '270234.2019', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '34119.9', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=1


## /root/FIL/strategy/s_rsrs/log.txt ----- -----

721  20231024   040000    075959  1698105599  ...    721  2.431451  2.654970     1.0
722  20231024   080000    115959  1698119999  ...    722  2.469821  2.587041     1.0

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '41.361', 'enterprice': '29539.2', 'countrevence': '0', 'unrealprofit': '186933.11840023113', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '34058.75026233', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=1, self.sign=1
--handleKline--:  version='2.0.0', self.name='s_rsrs', self.symbol='BTCUSDT', interval='4h', intervalSec=14400, wid=25, thd=0.6, self.sign=1, self.total=1220549.0803488, self.flagDict['side']='buy', self.tradeCount=37, self.count=979
self.closeSec=1698134399, self.tradeDate='20231024', self.openTime='120000', self.closeTime='155959', self.symbol='BTCUSDT', self.open=34071.1, self.close=34025.8, self.high=34597.9, self.low=33710.0, self.vol=120908.224, self.amt=4124627273.24655 
127.0.0.1 - - [24/Oct/2023 16:00:01] "POST / HTTP/1.1" 200 -
2023-10-24 16:00:01,536:INFO:s_rsrs:main.py:141:handleKline:2218689: self.closeSec=1698134399, self.tradeDate='20231024', self.openTime='120000', self.closeTime='155959',self.symbol='BTCUSDT',self.open=34071.1, self.close=34025.8, self.high=34597.9, self.low=33710.0, self.vol=120908.224, self.amt=4124627273.24655 
2023-10-24 16:00:01,553:INFO:s_rsrs:main.py:142:handleKline:2218689: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime  ...         vol           amt       pct
719  20231023   200000    235959  ...   89649.140  2.751678e+09  0.007248
720  20231024   000000    035959  ...  214045.310  6.646158e+09  0.015314
721  20231024   040000    075959  ...  377945.899  1.239992e+10  0.055375
722  20231024   080000    115959  ...  281261.831  9.615855e+09  0.030008
723  20231024   120000    155959  ...  120908.224  4.124627e+09 -0.001212

[5 rows x 11 columns]
2023-10-24 16:00:02,313:INFO:s_rsrs:main.py:151:handleKline:2218689: df_s.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec  ...  index      beta    zscore  signal
719  20231023   200000    235959  1698076799  ...    719  0.790494  0.109719     NaN
720  20231024   000000    035959  1698091199  ...    720  0.865805  0.219781     NaN
721  20231024   040000    075959  1698105599  ...    721  2.431451  2.654970     1.0
722  20231024   080000    115959  1698119999  ...    722  2.469821  2.587041     1.0
723  20231024   120000    155959  1698134399  ...    723  1.695636  1.365441     1.0

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '41.361', 'enterprice': '29539.2', 'countrevence': '0', 'unrealprofit': '185519.50835476488', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '34024.57289608', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=1, self.sign=1


