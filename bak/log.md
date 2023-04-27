# 20230427 16:26:01

## /root/FIL/strategy/amihud/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=993672.4896432, self.flagDict['side']='sell', self.tradeCount=2, self.count=43509
self.closeSec=1682583599, self.tradeDate='20230427', self.openTime='161500', self.closeTime='161959', self.symbol='BTCUSDT', self.open=28781.9, self.close=28820.1, self.high=28821.2, self.low=28768.0, self.vol=2492.416, self.amt=71756469.9744 
127.0.0.1 - - [27/Apr/2023 16:20:03] "POST / HTTP/1.1" 200 -
2023-04-27 16:20:05,785:INFO:amihud:main.py:172:handleKline:200676: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5944  20230427   155500    155959  ...         0.0        0.0       0
5945  20230427   160000    160459  ...         0.0        0.0       0
5946  20230427   160500    160959  ...         0.0        0.0       0
5947  20230427   161000    161459  ...         0.0        0.0       0
5948  20230427   161500    161959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-04-27 16:20:05,789:INFO:amihud:main.py:175:handleKline:200676: self.closeSec=1682583599, self.tradeDate='20230427', self.openTime='161500', self.closeTime='161959',self.symbol='BTCUSDT',self.open=28781.9, self.close=28820.1, self.high=28821.2, self.low=28768.0, self.vol=2492.416, self.amt=71756469.9744, ukdf['pct'].iloc[-1]=0.001331 , ukdf['amount'].iloc[-1]=71756469.9744, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5948, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '60.176', 'enterprice': '16529.3', 'countrevence': '0', 'unrealprofit': '-739767.6384', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '28822.7', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1
127.0.0.1 - - [27/Apr/2023 16:25:01] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=993672.4896432, self.flagDict['side']='sell', self.tradeCount=2, self.count=43510
self.closeSec=1682583899, self.tradeDate='20230427', self.openTime='162000', self.closeTime='162459', self.symbol='BTCUSDT', self.open=28820.1, self.close=28939.8, self.high=28957.8, self.low=28817.0, self.vol=4194.372, self.amt=121221808.0034 
2023-04-27 16:25:01,576:INFO:amihud:main.py:172:handleKline:200676: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5945  20230427   160000    160459  ...         0.0        0.0       0
5946  20230427   160500    160959  ...         0.0        0.0       0
5947  20230427   161000    161459  ...         0.0        0.0       0
5948  20230427   161500    161959  ...         0.0        0.0       0
5949  20230427   162000    162459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-04-27 16:25:01,576:INFO:amihud:main.py:175:handleKline:200676: self.closeSec=1682583899, self.tradeDate='20230427', self.openTime='162000', self.closeTime='162459',self.symbol='BTCUSDT',self.open=28820.1, self.close=28939.8, self.high=28957.8, self.low=28817.0, self.vol=4194.372, self.amt=121221808.0034, ukdf['pct'].iloc[-1]=0.004153 , ukdf['amount'].iloc[-1]=121221808.0034, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5949, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '60.176', 'enterprice': '16529.3', 'countrevence': '0', 'unrealprofit': '-747100.56898967552', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '28944.55805952', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1


## /root/FIL/strategy/factorcheck/log.txt ----- -----

127.0.0.1 - - [27/Apr/2023 16:00:01] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=23, self.factor=0.43541661550691446, self.count=44071 

self.closeSec=1682582399, self.tradeDate='20230427', self.openTime='155500', self.closeTime='155959', self.symbol='BTCUSDT', self.open=28906.2, self.close=28880.0, self.high=28915.4, self.low=28880.0 

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=23, self.factor=0.43541661550691446, self.count=44072 

self.closeSec=1682582699, self.tradeDate='20230427', self.openTime='160000', self.closeTime='160459', self.symbol='BTCUSDT', self.open=28880.1, self.close=28866.1, self.high=28885.1, self.low=28854.0 
127.0.0.1 - - [27/Apr/2023 16:05:01] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=23, self.factor=0.43541661550691446, self.count=44073 

self.closeSec=1682582999, self.tradeDate='20230427', self.openTime='160500', self.closeTime='160959', self.symbol='BTCUSDT', self.open=28866.1, self.close=28854.3, self.high=28871.3, self.low=28839.8 
127.0.0.1 - - [27/Apr/2023 16:10:02] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=23, self.factor=0.43541661550691446, self.count=44074 

self.closeSec=1682583299, self.tradeDate='20230427', self.openTime='161000', self.closeTime='161459', self.symbol='BTCUSDT', self.open=28854.3, self.close=28781.8, self.high=28854.3, self.low=28774.1 
127.0.0.1 - - [27/Apr/2023 16:15:03] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=23, self.factor=0.43541661550691446, self.count=44075 

self.closeSec=1682583599, self.tradeDate='20230427', self.openTime='161500', self.closeTime='161959', self.symbol='BTCUSDT', self.open=28781.9, self.close=28820.1, self.high=28821.2, self.low=28768.0 
127.0.0.1 - - [27/Apr/2023 16:20:02] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [27/Apr/2023 16:25:01] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=23, self.factor=0.43541661550691446, self.count=44076 

self.closeSec=1682583899, self.tradeDate='20230427', self.openTime='162000', self.closeTime='162459', self.symbol='BTCUSDT', self.open=28820.1, self.close=28939.8, self.high=28957.8, self.low=28817.0 


## /root/FIL/strategy/logic/log.txt ----- -----

2023-04-27 16:00:25,231:DEBUG:logic:main.py:463:getModel:885513: df_s.iloc[-5:,:] :
          date closeTime     open  ...    alpha58   alpha67   alpha72
5785  20230427    132959  29079.3  ...  55.000000  0.545130  0.371442
5786  20230427    135959  29152.7  ...  54.583333  0.539089  0.369531
5787  20230427    142959  29071.9  ...  54.583333  0.531758  0.370053
5788  20230427    145959  28973.5  ...  54.166667  0.517555  0.375100
5789  20230427    152959  28778.6  ...  54.583333  0.520293  0.378855

[5 rows x 33 columns]
0.5369003690036901
acc is : 0.5369003690036901
2023-04-27 16:00:25,370:INFO:logic:main.py:468:getModel:885513: df_pred.iloc[-5:,:] :
     pred    prob_0    prob_1  actual  ...       nav  sign   cost_        bm
537     0  0.516590  0.483410       0  ...  0.844865   1.0  0.0000  0.960413
538     1  0.490182  0.509818       0  ...  0.842003   1.0  0.0000  0.957159
539     1  0.485846  0.514154       0  ...  0.836342   1.0  0.0000  0.950724
540     1  0.447786  0.552214       1  ...  0.833818  -1.0 -0.0016  0.952072
541     1  0.484900  0.515100       1  ...  0.832064  -1.0  0.0000  0.954074

[5 rows x 10 columns]
2023-04-27 16:00:25,404:INFO:logic:main.py:478:getModel:885513: df_panel.iloc[-5:,:] :
    pred    prob_0    prob_1  actual  ...       nav  sign   cost_        bm
45     0  0.515647  0.484353       0  ...  0.858108   1.0  0.0000  0.958393
46     1  0.489611  0.510389       0  ...  0.855201   1.0  0.0000  0.955697
47     1  0.485744  0.514256       0  ...  0.836342   1.0  0.0000  0.950404
48     1  0.447547  0.552453       1  ...  0.846887  -1.0 -0.0016  0.951911
49     1  0.484900  0.515100       1  ...  0.832064  -1.0  0.0000  0.954074

[5 rows x 10 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': []}


## /root/FIL/strategy/modifiedmom/log.txt ----- -----

127.0.0.1 - - [27/Apr/2023 15:30:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=22033 

self.closeSec=1682580599, self.tradeDate='20230427', self.openTime='152000', self.closeTime='152959', self.symbol='BTCUSDT', self.open='28860', self.close='28819.4'
127.0.0.1 - - [27/Apr/2023 15:40:02] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=22034 

self.closeSec=1682581199, self.tradeDate='20230427', self.openTime='153000', self.closeTime='153959', self.symbol='BTCUSDT', self.open='28819.4', self.close='28880.6'
127.0.0.1 - - [27/Apr/2023 15:50:02] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=22035 

self.closeSec=1682581799, self.tradeDate='20230427', self.openTime='154000', self.closeTime='154959', self.symbol='BTCUSDT', self.open='28880.7', self.close='28858.4'

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=22036 

self.closeSec=1682582399, self.tradeDate='20230427', self.openTime='155000', self.closeTime='155959', self.symbol='BTCUSDT', self.open='28856.2', self.close='28880'
127.0.0.1 - - [27/Apr/2023 16:00:02] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=22037 

self.closeSec=1682582999, self.tradeDate='20230427', self.openTime='160000', self.closeTime='160959', self.symbol='BTCUSDT', self.open='28880.1', self.close='28854.3'
127.0.0.1 - - [27/Apr/2023 16:10:02] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=22038 

self.closeSec=1682583599, self.tradeDate='20230427', self.openTime='161000', self.closeTime='161959', self.symbol='BTCUSDT', self.open='28854.3', self.close='28820.1'
127.0.0.1 - - [27/Apr/2023 16:20:04] "POST / HTTP/1.1" 200 -


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


--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=22034 

self.closeSec=1682580599, self.tradeDate='20230427', self.openTime='152000', self.closeTime='152959', self.symbol='BTCUSDT', self.open='28860', self.close='28819.4'
127.0.0.1 - - [27/Apr/2023 15:30:01] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [27/Apr/2023 15:40:02] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=22035 

self.closeSec=1682581199, self.tradeDate='20230427', self.openTime='153000', self.closeTime='153959', self.symbol='BTCUSDT', self.open='28819.4', self.close='28880.6'

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=22036 

self.closeSec=1682581799, self.tradeDate='20230427', self.openTime='154000', self.closeTime='154959', self.symbol='BTCUSDT', self.open='28880.7', self.close='28858.4'
127.0.0.1 - - [27/Apr/2023 15:50:02] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=22037 

self.closeSec=1682582399, self.tradeDate='20230427', self.openTime='155000', self.closeTime='155959', self.symbol='BTCUSDT', self.open='28856.2', self.close='28880'
127.0.0.1 - - [27/Apr/2023 16:00:01] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [27/Apr/2023 16:10:02] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=22038 

self.closeSec=1682582999, self.tradeDate='20230427', self.openTime='160000', self.closeTime='160959', self.symbol='BTCUSDT', self.open='28880.1', self.close='28854.3'

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=22039 

self.closeSec=1682583599, self.tradeDate='20230427', self.openTime='161000', self.closeTime='161959', self.symbol='BTCUSDT', self.open='28854.3', self.close='28820.1'
127.0.0.1 - - [27/Apr/2023 16:20:05] "POST / HTTP/1.1" 200 -


## /root/FIL/strategy/similarity/log.txt ----- -----

127.0.0.1 - - [27/Apr/2023 15:30:02] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=22034 

self.closeSec=1682580599, self.tradeDate='20230427', self.openTime='152000', self.closeTime='152959', self.symbol='BTCUSDT', self.open='28860', self.close='28819.4'
127.0.0.1 - - [27/Apr/2023 15:40:02] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=22035 

self.closeSec=1682581199, self.tradeDate='20230427', self.openTime='153000', self.closeTime='153959', self.symbol='BTCUSDT', self.open='28819.4', self.close='28880.6'

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=22036 

self.closeSec=1682581799, self.tradeDate='20230427', self.openTime='154000', self.closeTime='154959', self.symbol='BTCUSDT', self.open='28880.7', self.close='28858.4'
127.0.0.1 - - [27/Apr/2023 15:50:02] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=22037 

self.closeSec=1682582399, self.tradeDate='20230427', self.openTime='155000', self.closeTime='155959', self.symbol='BTCUSDT', self.open='28856.2', self.close='28880'
127.0.0.1 - - [27/Apr/2023 16:00:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=22038 

self.closeSec=1682582999, self.tradeDate='20230427', self.openTime='160000', self.closeTime='160959', self.symbol='BTCUSDT', self.open='28880.1', self.close='28854.3'
127.0.0.1 - - [27/Apr/2023 16:10:02] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=22039 

self.closeSec=1682583599, self.tradeDate='20230427', self.openTime='161000', self.closeTime='161959', self.symbol='BTCUSDT', self.open='28854.3', self.close='28820.1'
127.0.0.1 - - [27/Apr/2023 16:20:05] "POST / HTTP/1.1" 200 -


## /root/FIL/strategy/sr_min/log.txt ----- -----

--handleKline--: 127.0.0.1 - - [27/Apr/2023 16:20:02] "POST / HTTP/1.1" 200 -
 version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=0, self.total=1000000.0, self.flagDict['side']='', self.tradeCount=0, self.count=39507
self.closeSec=1682583599, self.tradeDate='20230427', self.openTime='161500', self.closeTime='161959', self.symbol='BTCUSDT', self.open=28781.9, self.close=28820.1, self.high=28821.2, self.low=28768.0, self.vol=2492.416, self.amt=71756469.9744 
2023-04-27 16:20:03,904:INFO:sr_min:main.py:172:handleKline:449472: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5944  20230427   155500    155959  ...         0.0        0.0       0
5945  20230427   160000    160459  ...         0.0        0.0       0
5946  20230427   160500    160959  ...         0.0        0.0       0
5947  20230427   161000    161459  ...         0.0        0.0       0
5948  20230427   161500    161959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-04-27 16:20:03,945:INFO:sr_min:main.py:175:handleKline:449472: self.closeSec=1682583599, self.tradeDate='20230427', self.openTime='161500', self.closeTime='161959',self.symbol='BTCUSDT',self.open=28781.9, self.close=28820.1, self.high=28821.2, self.low=28768.0, self.vol=2492.416, self.amt=71756469.9744, ukdf['pct'].iloc[-1]=0.001331 , ukdf['amount'].iloc[-1]=71756469.9744, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5948, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': []}
type(curSign)=<class 'int'>, curSign=0, self.sign=0
127.0.0.1 - - [27/Apr/2023 16:25:01] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=0, self.total=1000000.0, self.flagDict['side']='', self.tradeCount=0, self.count=39508
self.closeSec=1682583899, self.tradeDate='20230427', self.openTime='162000', self.closeTime='162459', self.symbol='BTCUSDT', self.open=28820.1, self.close=28939.8, self.high=28957.8, self.low=28817.0, self.vol=4194.372, self.amt=121221808.0034 
2023-04-27 16:25:01,585:INFO:sr_min:main.py:172:handleKline:449472: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5945  20230427   160000    160459  ...         0.0        0.0       0
5946  20230427   160500    160959  ...         0.0        0.0       0
5947  20230427   161000    161459  ...         0.0        0.0       0
5948  20230427   161500    161959  ...         0.0        0.0       0
5949  20230427   162000    162459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-04-27 16:25:01,585:INFO:sr_min:main.py:175:handleKline:449472: self.closeSec=1682583899, self.tradeDate='20230427', self.openTime='162000', self.closeTime='162459',self.symbol='BTCUSDT',self.open=28820.1, self.close=28939.8, self.high=28957.8, self.low=28817.0, self.vol=4194.372, self.amt=121221808.0034, ukdf['pct'].iloc[-1]=0.004153 , ukdf['amount'].iloc[-1]=121221808.0034, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5949, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': []}
type(curSign)=<class 'int'>, curSign=0, self.sign=0


## /root/FIL/strategy/s_rsrs/log.txt ----- -----

721  20230427   040000    075959  1682553599  ...    721  0.870679  0.595804     NaN
722  20230427   080000    115959  1682567999  ...    722  1.028601  1.137396     1.0

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '46.779', 'enterprice': '28948.5', 'countrevence': '0', 'unrealprofit': '-3330.6648', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '28877.3', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=1, self.sign=1
--handleKline--:  version='2.0.0', self.name='s_rsrs', self.symbol='BTCUSDT', interval='4h', intervalSec=14400, wid=25, thd=0.6, self.sign=1, self.total=1352827.6996185002, self.flagDict['side']='buy', self.tradeCount=32, self.count=918
self.closeSec=1682582399, self.tradeDate='20230427', self.openTime='120000', self.closeTime='155959', self.symbol='BTCUSDT', self.open=28876.6, self.close=28880.0, self.high=29272.6, self.low=28612.7, self.vol=112459.212, self.amt=3256536272.01752 
127.0.0.1 - - [27/Apr/2023 16:00:01] "POST / HTTP/1.1" 200 -
2023-04-27 16:00:01,865:INFO:s_rsrs:main.py:141:handleKline:185271: self.closeSec=1682582399, self.tradeDate='20230427', self.openTime='120000', self.closeTime='155959',self.symbol='BTCUSDT',self.open=28876.6, self.close=28880.0, self.high=29272.6, self.low=28612.7, self.vol=112459.212, self.amt=3256536272.01752 
2023-04-27 16:00:01,929:INFO:s_rsrs:main.py:142:handleKline:185271: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime  ...         vol           amt       pct
719  20230426   200000    235959  ...  306318.812  9.088141e+09  0.029795
720  20230427   000000    035959  ...  297294.343  8.583094e+09 -0.064551
721  20230427   040000    075959  ...  333531.894  9.343430e+09  0.018534
722  20230427   080000    115959  ...  231823.014  6.719884e+09  0.016929
723  20230427   120000    155959  ...  112459.212  3.256536e+09  0.000118

[5 rows x 11 columns]
2023-04-27 16:00:04,402:INFO:s_rsrs:main.py:151:handleKline:185271: df_s.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec  ...  index      beta    zscore  signal
719  20230426   200000    235959  1682524799  ...    719  1.365592  2.168048     1.0
720  20230427   000000    035959  1682539199  ...    720  1.098689  1.319755     1.0
721  20230427   040000    075959  1682553599  ...    721  0.870679  0.595804     NaN
722  20230427   080000    115959  1682567999  ...    722  1.028601  1.137396     1.0
723  20230427   120000    155959  1682582399  ...    723  1.012936  1.100041     1.0

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '46.779', 'enterprice': '28948.5', 'countrevence': '0', 'unrealprofit': '-3188.66844502062', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '28880.33547222', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=1, self.sign=1


