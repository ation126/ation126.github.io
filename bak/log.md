# 20230411 16:26:02

## /root/FIL/strategy/amihud/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=993672.4896432, self.flagDict['side']='sell', self.tradeCount=2, self.count=38901
self.closeSec=1681201199, self.tradeDate='20230411', self.openTime='161500', self.closeTime='161959', self.symbol='BTCUSDT', self.open=30072.3, self.close=30061.2, self.high=30092.3, self.low=30061.2, self.vol=602.936, self.amt=18134139.7893 
127.0.0.1 - - [11/Apr/2023 16:20:04] "POST / HTTP/1.1" 200 -
2023-04-11 16:20:07,093:INFO:amihud:main.py:172:handleKline:200676: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5944  20230411   155500    155959  ...         0.0        0.0       0
5945  20230411   160000    160459  ...         0.0        0.0       0
5946  20230411   160500    160959  ...         0.0        0.0       0
5947  20230411   161000    161459  ...         0.0        0.0       0
5948  20230411   161500    161959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-04-11 16:20:07,109:INFO:amihud:main.py:175:handleKline:200676: self.closeSec=1681201199, self.tradeDate='20230411', self.openTime='161500', self.closeTime='161959',self.symbol='BTCUSDT',self.open=30072.3, self.close=30061.2, self.high=30092.3, self.low=30061.2, self.vol=602.936, self.amt=18134139.7893, ukdf['pct'].iloc[-1]=-0.000369 , ukdf['amount'].iloc[-1]=18134139.7893, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5948, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '60.176', 'enterprice': '16529.3', 'countrevence': '0', 'unrealprofit': '-814496.40045964208', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '30064.53664683', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1
127.0.0.1 - - [11/Apr/2023 16:25:01] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=993672.4896432, self.flagDict['side']='sell', self.tradeCount=2, self.count=38902
self.closeSec=1681201499, self.tradeDate='20230411', self.openTime='162000', self.closeTime='162459', self.symbol='BTCUSDT', self.open=30061.2, self.close=30068.7, self.high=30075.4, self.low=30056.1, self.vol=569.853, self.amt=17132471.938 
2023-04-11 16:25:01,633:INFO:amihud:main.py:172:handleKline:200676: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5945  20230411   160000    160459  ...         0.0        0.0       0
5946  20230411   160500    160959  ...         0.0        0.0       0
5947  20230411   161000    161459  ...         0.0        0.0       0
5948  20230411   161500    161959  ...         0.0        0.0       0
5949  20230411   162000    162459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-04-11 16:25:01,633:INFO:amihud:main.py:175:handleKline:200676: self.closeSec=1681201499, self.tradeDate='20230411', self.openTime='162000', self.closeTime='162459',self.symbol='BTCUSDT',self.open=30061.2, self.close=30068.7, self.high=30075.4, self.low=30056.1, self.vol=569.853, self.amt=17132471.938, ukdf['pct'].iloc[-1]=0.000249 , ukdf['amount'].iloc[-1]=17132471.938, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5949, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '60.176', 'enterprice': '16529.3', 'countrevence': '0', 'unrealprofit': '-814740.9168', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '30068.6', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1


## /root/FIL/strategy/factorcheck/log.txt ----- -----


--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=23, self.factor=0.43541661550691446, self.count=39463 

self.closeSec=1681199999, self.tradeDate='20230411', self.openTime='155500', self.closeTime='155959', self.symbol='BTCUSDT', self.open=30112.5, self.close=30095.3, self.high=30112.5, self.low=30088.0 
127.0.0.1 - - [11/Apr/2023 16:00:01] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=23, self.factor=0.43541661550691446, self.count=39464 

self.closeSec=1681200299, self.tradeDate='20230411', self.openTime='160000', self.closeTime='160459', self.symbol='BTCUSDT', self.open=30095.3, self.close=30110.1, self.high=30111.0, self.low=30095.3 
127.0.0.1 - - [11/Apr/2023 16:05:01] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [11/Apr/2023 16:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=23, self.factor=0.43541661550691446, self.count=39465 

self.closeSec=1681200599, self.tradeDate='20230411', self.openTime='160500', self.closeTime='160959', self.symbol='BTCUSDT', self.open=30110.0, self.close=30093.1, self.high=30113.7, self.low=30088.7 

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=23, self.factor=0.43541661550691446, self.count=39466 

self.closeSec=1681200899, self.tradeDate='20230411', self.openTime='161000', self.closeTime='161459', self.symbol='BTCUSDT', self.open=30093.1, self.close=30072.3, self.high=30093.2, self.low=30063.4 
127.0.0.1 - - [11/Apr/2023 16:15:01] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=23, self.factor=0.43541661550691446, self.count=39467 

self.closeSec=1681201199, self.tradeDate='20230411', self.openTime='161500', self.closeTime='161959', self.symbol='BTCUSDT', self.open=30072.3, self.close=30061.2, self.high=30092.3, self.low=30061.2 
127.0.0.1 - - [11/Apr/2023 16:20:03] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=23, self.factor=0.43541661550691446, self.count=39468 

self.closeSec=1681201499, self.tradeDate='20230411', self.openTime='162000', self.closeTime='162459', self.symbol='BTCUSDT', self.open=30061.2, self.close=30068.7, self.high=30075.4, self.low=30056.1 
127.0.0.1 - - [11/Apr/2023 16:25:01] "POST / HTTP/1.1" 200 -


## /root/FIL/strategy/logic/log.txt ----- -----

2023-04-11 16:00:32,539:DEBUG:logic:main.py:463:getModel:885513: df_s.iloc[-5:,:] :
          date closeTime     open  ...    alpha58   alpha67   alpha72
5785  20230411    132959  30099.9  ...  51.666667  0.694954  0.181438
5786  20230411    135959  30060.1  ...  51.250000  0.657789  0.187008
5787  20230411    142959  29871.6  ...  51.666667  0.677365  0.186226
5788  20230411    145959  30081.2  ...  51.250000  0.666201  0.187214
5789  20230411    152959  30021.0  ...  51.250000  0.672127  0.186290

[5 rows x 33 columns]
0.551660516605166
acc is : 0.551660516605166
2023-04-11 16:00:32,725:INFO:logic:main.py:468:getModel:885513: df_pred.iloc[-5:,:] :
     pred    prob_0    prob_1  actual  ...       nav  sign   cost_        bm
537     1  0.481402  0.518598       0  ...  1.010381   1.0  0.0000  1.062638
538     1  0.447439  0.552561       1  ...  1.001671  -1.0 -0.0016  1.070098
539     0  0.526581  0.473419       0  ...  1.003676  -1.0  0.0000  1.067956
540     1  0.472116  0.527884       1  ...  1.001513  -1.0  0.0000  1.070258
541     1  0.499305  0.500695       1  ...  1.001196  -1.0  0.0000  1.070596

[5 rows x 10 columns]
2023-04-11 16:00:32,763:INFO:logic:main.py:478:getModel:885513: df_panel.iloc[-5:,:] :
    pred    prob_0    prob_1  actual  ...       nav  sign   cost_        bm
45     1  0.481884  0.518116       0  ...  1.025369   1.0  0.0000  1.063270
46     1  0.448233  0.551767       1  ...  1.016531  -1.0 -0.0016  1.078643
47     0  0.527584  0.472416       0  ...  1.018565  -1.0  0.0000  1.073282
48     1  0.472547  0.527453       1  ...  1.016370  -1.0  0.0000  1.073918
49     1  0.499305  0.500695       1  ...  1.001196  -1.0  0.0000  1.070596

[5 rows x 10 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': []}


## /root/FIL/strategy/modifiedmom/log.txt ----- -----

127.0.0.1 - - [11/Apr/2023 15:30:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=19729 

self.closeSec=1681198199, self.tradeDate='20230411', self.openTime='152000', self.closeTime='152959', self.symbol='BTCUSDT', self.open='30080', self.close='30085.8'

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=19730 

self.closeSec=1681198799, self.tradeDate='20230411', self.openTime='153000', self.closeTime='153959', self.symbol='BTCUSDT', self.open='30085.8', self.close='30062.9'
127.0.0.1 - - [11/Apr/2023 15:40:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=19731 

self.closeSec=1681199399, self.tradeDate='20230411', self.openTime='154000', self.closeTime='154959', self.symbol='BTCUSDT', self.open='30062.9', self.close='30091.1'
127.0.0.1 - - [11/Apr/2023 15:50:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=19732 

self.closeSec=1681199999, self.tradeDate='20230411', self.openTime='155000', self.closeTime='155959', self.symbol='BTCUSDT', self.open='30091', self.close='30095.3'
127.0.0.1 - - [11/Apr/2023 16:00:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=19733 

self.closeSec=1681200599, self.tradeDate='20230411', self.openTime='160000', self.closeTime='160959', self.symbol='BTCUSDT', self.open='30095.3', self.close='30093.2'
127.0.0.1 - - [11/Apr/2023 16:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=19734 

self.closeSec=1681201199, self.tradeDate='20230411', self.openTime='161000', self.closeTime='161959', self.symbol='BTCUSDT', self.open='30093.1', self.close='30061.3'
127.0.0.1 - - [11/Apr/2023 16:20:04] "POST / HTTP/1.1" 200 -


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


--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=19730 

self.closeSec=1681198199, self.tradeDate='20230411', self.openTime='152000', self.closeTime='152959', self.symbol='BTCUSDT', self.open='30080', self.close='30085.8'
127.0.0.1 - - [11/Apr/2023 15:30:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=19731 

self.closeSec=1681198799, self.tradeDate='20230411', self.openTime='153000', self.closeTime='153959', self.symbol='BTCUSDT', self.open='30085.8', self.close='30062.9'
127.0.0.1 - - [11/Apr/2023 15:40:01] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [11/Apr/2023 15:50:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=19732 

self.closeSec=1681199399, self.tradeDate='20230411', self.openTime='154000', self.closeTime='154959', self.symbol='BTCUSDT', self.open='30062.9', self.close='30091.1'
127.0.0.1 - - [11/Apr/2023 16:00:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=19733 

self.closeSec=1681199999, self.tradeDate='20230411', self.openTime='155000', self.closeTime='155959', self.symbol='BTCUSDT', self.open='30091', self.close='30095.3'
127.0.0.1 - - [11/Apr/2023 16:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=19734 

self.closeSec=1681200599, self.tradeDate='20230411', self.openTime='160000', self.closeTime='160959', self.symbol='BTCUSDT', self.open='30095.3', self.close='30093.2'

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=19735 

self.closeSec=1681201199, self.tradeDate='20230411', self.openTime='161000', self.closeTime='161959', self.symbol='BTCUSDT', self.open='30093.1', self.close='30061.3'
127.0.0.1 - - [11/Apr/2023 16:20:04] "POST / HTTP/1.1" 200 -


## /root/FIL/strategy/similarity/log.txt ----- -----


--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=19730 

self.closeSec=1681198199, self.tradeDate='20230411', self.openTime='152000', self.closeTime='152959', self.symbol='BTCUSDT', self.open='30080', self.close='30085.8'
127.0.0.1 - - [11/Apr/2023 15:30:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=19731 

self.closeSec=1681198799, self.tradeDate='20230411', self.openTime='153000', self.closeTime='153959', self.symbol='BTCUSDT', self.open='30085.8', self.close='30062.9'
127.0.0.1 - - [11/Apr/2023 15:40:01] "POST / HTTP/1.1" 200 -

--handleKline--: 127.0.0.1 - - [11/Apr/2023 15:50:01] "POST / HTTP/1.1" 200 -
 self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=19732 

self.closeSec=1681199399, self.tradeDate='20230411', self.openTime='154000', self.closeTime='154959', self.symbol='BTCUSDT', self.open='30062.9', self.close='30091.1'

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=19733 

self.closeSec=1681199999, self.tradeDate='20230411', self.openTime='155000', self.closeTime='155959', self.symbol='BTCUSDT', self.open='30091', self.close='30095.3'
127.0.0.1 - - [11/Apr/2023 16:00:01] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [11/Apr/2023 16:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=19734 

self.closeSec=1681200599, self.tradeDate='20230411', self.openTime='160000', self.closeTime='160959', self.symbol='BTCUSDT', self.open='30095.3', self.close='30093.2'

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=19735 

self.closeSec=1681201199, self.tradeDate='20230411', self.openTime='161000', self.closeTime='161959', self.symbol='BTCUSDT', self.open='30093.1', self.close='30061.3'
127.0.0.1 - - [11/Apr/2023 16:20:04] "POST / HTTP/1.1" 200 -


## /root/FIL/strategy/sr_min/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=0, self.total=1000000.0, self.flagDict['side']='', self.tradeCount=0, self.count=34899
self.closeSec=1681201199, self.tradeDate='20230411', self.openTime='161500', self.closeTime='161959', self.symbol='BTCUSDT', self.open=30072.3, self.close=30061.2, self.high=30092.3, self.low=30061.2, self.vol=602.936, self.amt=18134139.7893 
127.0.0.1 - - [11/Apr/2023 16:20:04] "POST / HTTP/1.1" 200 -
2023-04-11 16:20:06,992:INFO:sr_min:main.py:172:handleKline:449472: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5944  20230411   155500    155959  ...         0.0        0.0       0
5945  20230411   160000    160459  ...         0.0        0.0       0
5946  20230411   160500    160959  ...         0.0        0.0       0
5947  20230411   161000    161459  ...         0.0        0.0       0
5948  20230411   161500    161959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-04-11 16:20:06,997:INFO:sr_min:main.py:175:handleKline:449472: self.closeSec=1681201199, self.tradeDate='20230411', self.openTime='161500', self.closeTime='161959',self.symbol='BTCUSDT',self.open=30072.3, self.close=30061.2, self.high=30092.3, self.low=30061.2, self.vol=602.936, self.amt=18134139.7893, ukdf['pct'].iloc[-1]=-0.000369 , ukdf['amount'].iloc[-1]=18134139.7893, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5948, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': []}
type(curSign)=<class 'int'>, curSign=0, self.sign=0
127.0.0.1 - - [11/Apr/2023 16:25:01] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=0, self.total=1000000.0, self.flagDict['side']='', self.tradeCount=0, self.count=34900
self.closeSec=1681201499, self.tradeDate='20230411', self.openTime='162000', self.closeTime='162459', self.symbol='BTCUSDT', self.open=30061.2, self.close=30068.7, self.high=30075.4, self.low=30056.1, self.vol=569.853, self.amt=17132471.938 
2023-04-11 16:25:01,570:INFO:sr_min:main.py:172:handleKline:449472: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5945  20230411   160000    160459  ...         0.0        0.0       0
5946  20230411   160500    160959  ...         0.0        0.0       0
5947  20230411   161000    161459  ...         0.0        0.0       0
5948  20230411   161500    161959  ...         0.0        0.0       0
5949  20230411   162000    162459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-04-11 16:25:01,570:INFO:sr_min:main.py:175:handleKline:449472: self.closeSec=1681201499, self.tradeDate='20230411', self.openTime='162000', self.closeTime='162459',self.symbol='BTCUSDT',self.open=30061.2, self.close=30068.7, self.high=30075.4, self.low=30056.1, self.vol=569.853, self.amt=17132471.938, ukdf['pct'].iloc[-1]=0.000249 , ukdf['amount'].iloc[-1]=17132471.938, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5949, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': []}
type(curSign)=<class 'int'>, curSign=0, self.sign=0


## /root/FIL/strategy/s_rsrs/log.txt ----- -----

721  20230411   040000    075959  1681171199  ...    721  1.949541  5.398415     1.0
722  20230411   080000    115959  1681185599  ...    722  1.968087  4.680088     1.0

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '52.515', 'enterprice': '28269.9', 'countrevence': '0', 'unrealprofit': '96741.9716265738', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '30112.07788492', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=1, self.sign=1
127.0.0.1 - - [11/Apr/2023 16:00:01] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='s_rsrs', self.symbol='BTCUSDT', interval='4h', intervalSec=14400, wid=25, thd=0.6, self.sign=1, self.total=1483109.2047015, self.flagDict['side']='buy', self.tradeCount=30, self.count=822
self.closeSec=1681199999, self.tradeDate='20230411', self.openTime='120000', self.closeTime='155959', self.symbol='BTCUSDT', self.open=30105.7, self.close=30095.3, self.high=30160.0, self.low=29752.1, self.vol=75212.768, self.amt=2258269707.7827 
2023-04-11 16:00:01,806:INFO:s_rsrs:main.py:141:handleKline:185271: self.closeSec=1681199999, self.tradeDate='20230411', self.openTime='120000', self.closeTime='155959',self.symbol='BTCUSDT',self.open=30105.7, self.close=30095.3, self.high=30160.0, self.low=29752.1, self.vol=75212.768, self.amt=2258269707.7827 
2023-04-11 16:00:01,856:INFO:s_rsrs:main.py:142:handleKline:185271: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime  ...         vol           amt       pct
719  20230410   200000    235959  ...   91955.851  2.606687e+09  0.004715
720  20230411   000000    035959  ...  244253.752  7.086679e+09  0.025932
721  20230411   040000    075959  ...  138521.033  4.086110e+09  0.015711
722  20230411   080000    115959  ...  202989.715  6.097405e+09  0.016295
723  20230411   120000    155959  ...   75212.768  2.258270e+09 -0.000349

[5 rows x 11 columns]
2023-04-11 16:00:04,132:INFO:s_rsrs:main.py:151:handleKline:185271: df_s.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec  ...  index      beta    zscore  signal
719  20230410   200000    235959  1681142399  ...    719  0.635240  1.725680     1.0
720  20230411   000000    035959  1681156799  ...    720  1.632748  5.391564     1.0
721  20230411   040000    075959  1681171199  ...    721  1.949541  5.398415     1.0
722  20230411   080000    115959  1681185599  ...    722  1.968087  4.680088     1.0
723  20230411   120000    155959  1681199999  ...    723  1.576662  3.292181     1.0

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '52.515', 'enterprice': '28269.9', 'countrevence': '0', 'unrealprofit': '95881.887', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '30095.7', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=1, self.sign=1


