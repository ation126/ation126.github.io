# 20230505 16:26:01

## /root/FIL/strategy/amihud/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=993672.4896432, self.flagDict['side']='sell', self.tradeCount=2, self.count=45813
self.closeSec=1683274799, self.tradeDate='20230505', self.openTime='161500', self.closeTime='161959', self.symbol='BTCUSDT', self.open=29085.9, self.close=29091.0, self.high=29109.9, self.low=29070.1, self.vol=1935.301, self.amt=56306645.1413 
127.0.0.1 - - [05/May/2023 16:20:02] "POST / HTTP/1.1" 200 -
2023-05-05 16:20:06,608:INFO:amihud:main.py:172:handleKline:200676: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5951  20230505   155500    155959  ...         0.0        0.0       0
5952  20230505   160000    160459  ...         0.0        0.0       0
5953  20230505   160500    160959  ...         0.0        0.0       0
5954  20230505   161000    161459  ...         0.0        0.0       0
5955  20230505   161500    161959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-05-05 16:20:06,619:INFO:amihud:main.py:175:handleKline:200676: self.closeSec=1683274799, self.tradeDate='20230505', self.openTime='161500', self.closeTime='161959',self.symbol='BTCUSDT',self.open=29085.9, self.close=29091.0, self.high=29109.9, self.low=29070.1, self.vol=1935.301, self.amt=56306645.1413, ukdf['pct'].iloc[-1]=0.000179 , ukdf['amount'].iloc[-1]=56306645.1413, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5955, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '60.176', 'enterprice': '16529.3', 'countrevence': '0', 'unrealprofit': '-755834.6304', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '29089.7', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1
127.0.0.1 - - [05/May/2023 16:25:02] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=993672.4896432, self.flagDict['side']='sell', self.tradeCount=2, self.count=45814
self.closeSec=1683275099, self.tradeDate='20230505', self.openTime='162000', self.closeTime='162459', self.symbol='BTCUSDT', self.open=29091.0, self.close=29098.6, self.high=29109.9, self.low=29088.5, self.vol=803.149, self.amt=23371988.5375 
2023-05-05 16:25:02,194:INFO:amihud:main.py:172:handleKline:200676: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5952  20230505   160000    160459  ...         0.0        0.0       0
5953  20230505   160500    160959  ...         0.0        0.0       0
5954  20230505   161000    161459  ...         0.0        0.0       0
5955  20230505   161500    161959  ...         0.0        0.0       0
5956  20230505   162000    162459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-05-05 16:25:02,195:INFO:amihud:main.py:175:handleKline:200676: self.closeSec=1683275099, self.tradeDate='20230505', self.openTime='162000', self.closeTime='162459',self.symbol='BTCUSDT',self.open=29091.0, self.close=29098.6, self.high=29109.9, self.low=29088.5, self.vol=803.149, self.amt=23371988.5375, ukdf['pct'].iloc[-1]=0.000261 , ukdf['amount'].iloc[-1]=23371988.5375, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5956, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '60.176', 'enterprice': '16529.3', 'countrevence': '0', 'unrealprofit': '-756390.27294639056', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '29098.93362381', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1


## /root/FIL/strategy/factorcheck/log.txt ----- -----

127.0.0.1 - - [05/May/2023 16:00:02] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=23, self.factor=0.43541661550691446, self.count=46375 

self.closeSec=1683273599, self.tradeDate='20230505', self.openTime='155500', self.closeTime='155959', self.symbol='BTCUSDT', self.open=29083.2, self.close=29059.0, self.high=29083.6, self.low=29038.6 

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=23, self.factor=0.43541661550691446, self.count=46376 

self.closeSec=1683273899, self.tradeDate='20230505', self.openTime='160000', self.closeTime='160459', self.symbol='BTCUSDT', self.open=29058.9, self.close=29046.3, self.high=29071.7, self.low=29043.2 
127.0.0.1 - - [05/May/2023 16:05:02] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=23, self.factor=0.43541661550691446, self.count=46377 

self.closeSec=1683274199, self.tradeDate='20230505', self.openTime='160500', self.closeTime='160959', self.symbol='BTCUSDT', self.open=29046.4, self.close=29035.0, self.high=29062.7, self.low=29025.7 
127.0.0.1 - - [05/May/2023 16:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=23, self.factor=0.43541661550691446, self.count=46378 

self.closeSec=1683274499, self.tradeDate='20230505', self.openTime='161000', self.closeTime='161459', self.symbol='BTCUSDT', self.open=29035.0, self.close=29085.8, self.high=29085.9, self.low=29026.0 
127.0.0.1 - - [05/May/2023 16:15:04] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=23, self.factor=0.43541661550691446, self.count=46379 

self.closeSec=1683274799, self.tradeDate='20230505', self.openTime='161500', self.closeTime='161959', self.symbol='BTCUSDT', self.open=29085.9, self.close=29091.0, self.high=29109.9, self.low=29070.1 
127.0.0.1 - - [05/May/2023 16:20:02] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [05/May/2023 16:25:02] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=23, self.factor=0.43541661550691446, self.count=46380 

self.closeSec=1683275099, self.tradeDate='20230505', self.openTime='162000', self.closeTime='162459', self.symbol='BTCUSDT', self.open=29091.0, self.close=29098.6, self.high=29109.9, self.low=29088.5 


## /root/FIL/strategy/logic/log.txt ----- -----

2023-05-05 16:00:20,480:DEBUG:logic:main.py:463:getModel:885513: df_s.iloc[-5:,:] :
          date closeTime     open  ...    alpha58   alpha67   alpha72
5785  20230505    132959  29213.8  ...  52.083333  0.557632  0.504075
5786  20230505    135959  29196.2  ...  51.666667  0.555896  0.497705
5787  20230505    142959  29186.9  ...  51.666667  0.553983  0.492509
5788  20230505    145959  29177.1  ...  51.250000  0.549277  0.489484
5789  20230505    152959  29152.6  ...  50.833333  0.538468  0.490888

[5 rows x 33 columns]
0.5498154981549815
acc is : 0.5498154981549815
2023-05-05 16:00:20,570:INFO:logic:main.py:468:getModel:885513: df_pred.iloc[-5:,:] :
     pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
537     1  0.493015  0.506985       0  ...  0.878473   1.0    0.0  1.050130
538     1  0.493135  0.506865       0  ...  0.878172   1.0    0.0  1.049770
539     1  0.496505  0.503495       0  ...  0.877438   1.0    0.0  1.048892
540     1  0.488524  0.511476       0  ...  0.875737   1.0    0.0  1.046860
541     1  0.479257  0.520743       0  ...  0.874620   1.0    0.0  1.045525

[5 rows x 10 columns]
2023-05-05 16:00:20,595:INFO:logic:main.py:478:getModel:885513: df_panel.iloc[-5:,:] :
    pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
45     1  0.493007  0.506993       0  ...  0.878473   1.0    0.0  1.058282
46     1  0.492917  0.507083       0  ...  0.878172   1.0    0.0  1.056621
47     1  0.496084  0.503916       0  ...  0.877438   1.0    0.0  1.057173
48     1  0.488767  0.511233       0  ...  0.875737   1.0    0.0  1.060597
49     1  0.479257  0.520743       0  ...  0.874620   1.0    0.0  1.045525

[5 rows x 10 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': []}


## /root/FIL/strategy/modifiedmom/log.txt ----- -----


--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=23185 

self.closeSec=1683271799, self.tradeDate='20230505', self.openTime='152000', self.closeTime='152959', self.symbol='BTCUSDT', self.open='29107.2', self.close='29096.1'
127.0.0.1 - - [05/May/2023 15:30:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=23186 

self.closeSec=1683272399, self.tradeDate='20230505', self.openTime='153000', self.closeTime='153959', self.symbol='BTCUSDT', self.open='29096.2', self.close='29074'
127.0.0.1 - - [05/May/2023 15:40:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=23187 

self.closeSec=1683272999, self.tradeDate='20230505', self.openTime='154000', self.closeTime='154959', self.symbol='BTCUSDT', self.open='29073.9', self.close='29063.1'
127.0.0.1 - - [05/May/2023 15:50:02] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [05/May/2023 16:00:03] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=23188 

self.closeSec=1683273599, self.tradeDate='20230505', self.openTime='155000', self.closeTime='155959', self.symbol='BTCUSDT', self.open='29063.1', self.close='29059'
127.0.0.1 - - [05/May/2023 16:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=23189 

self.closeSec=1683274199, self.tradeDate='20230505', self.openTime='160000', self.closeTime='160959', self.symbol='BTCUSDT', self.open='29058.9', self.close='29035'

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=23190 

self.closeSec=1683274799, self.tradeDate='20230505', self.openTime='161000', self.closeTime='161959', self.symbol='BTCUSDT', self.open='29035', self.close='29091'
127.0.0.1 - - [05/May/2023 16:20:05] "POST / HTTP/1.1" 200 -


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

127.0.0.1 - - [05/May/2023 15:30:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=23186 

self.closeSec=1683271799, self.tradeDate='20230505', self.openTime='152000', self.closeTime='152959', self.symbol='BTCUSDT', self.open='29107.2', self.close='29096.1'

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=23187 

self.closeSec=1683272399, self.tradeDate='20230505', self.openTime='153000', self.closeTime='153959', self.symbol='BTCUSDT', self.open='29096.2', self.close='29074'
127.0.0.1 - - [05/May/2023 15:40:01] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [05/May/2023 15:50:02] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=23188 

self.closeSec=1683272999, self.tradeDate='20230505', self.openTime='154000', self.closeTime='154959', self.symbol='BTCUSDT', self.open='29073.9', self.close='29063.1'

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=23189 

self.closeSec=1683273599, self.tradeDate='20230505', self.openTime='155000', self.closeTime='155959', self.symbol='BTCUSDT', self.open='29063.1', self.close='29059'
127.0.0.1 - - [05/May/2023 16:00:03] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=23190 

self.closeSec=1683274199, self.tradeDate='20230505', self.openTime='160000', self.closeTime='160959', self.symbol='BTCUSDT', self.open='29058.9', self.close='29035'
127.0.0.1 - - [05/May/2023 16:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=23191 

self.closeSec=1683274799, self.tradeDate='20230505', self.openTime='161000', self.closeTime='161959', self.symbol='BTCUSDT', self.open='29035', self.close='29091'
127.0.0.1 - - [05/May/2023 16:20:05] "POST / HTTP/1.1" 200 -


## /root/FIL/strategy/similarity/log.txt ----- -----


--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=23186 

self.closeSec=1683271799, self.tradeDate='20230505', self.openTime='152000', self.closeTime='152959', self.symbol='BTCUSDT', self.open='29107.2', self.close='29096.1'
127.0.0.1 - - [05/May/2023 15:30:01] "POST / HTTP/1.1" 200 -

--handleKline--: 127.0.0.1 - - [05/May/2023 15:40:01] "POST / HTTP/1.1" 200 -
 self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=23187 

self.closeSec=1683272399, self.tradeDate='20230505', self.openTime='153000', self.closeTime='153959', self.symbol='BTCUSDT', self.open='29096.2', self.close='29074'

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=23188 

self.closeSec=1683272999, self.tradeDate='20230505', self.openTime='154000', self.closeTime='154959', self.symbol='BTCUSDT', self.open='29073.9', self.close='29063.1'
127.0.0.1 - - [05/May/2023 15:50:02] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=23189 

self.closeSec=1683273599, self.tradeDate='20230505', self.openTime='155000', self.closeTime='155959', self.symbol='BTCUSDT', self.open='29063.1', self.close='29059'
127.0.0.1 - - [05/May/2023 16:00:03] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [05/May/2023 16:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=23190 

self.closeSec=1683274199, self.tradeDate='20230505', self.openTime='160000', self.closeTime='160959', self.symbol='BTCUSDT', self.open='29058.9', self.close='29035'

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=23191 

self.closeSec=1683274799, self.tradeDate='20230505', self.openTime='161000', self.closeTime='161959', self.symbol='BTCUSDT', self.open='29035', self.close='29091'
127.0.0.1 - - [05/May/2023 16:20:05] "POST / HTTP/1.1" 200 -


## /root/FIL/strategy/sr_min/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=0, self.total=1000000.0, self.flagDict['side']='', self.tradeCount=0, self.count=41811
self.closeSec=1683274799, self.tradeDate='20230505', self.openTime='161500', self.closeTime='161959', self.symbol='BTCUSDT', self.open=29085.9, self.close=29091.0, self.high=29109.9, self.low=29070.1, self.vol=1935.301, self.amt=56306645.1413 
127.0.0.1 - - [05/May/2023 16:20:03] "POST / HTTP/1.1" 200 -
2023-05-05 16:20:06,711:INFO:sr_min:main.py:172:handleKline:449472: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5951  20230505   155500    155959  ...         0.0        0.0       0
5952  20230505   160000    160459  ...         0.0        0.0       0
5953  20230505   160500    160959  ...         0.0        0.0       0
5954  20230505   161000    161459  ...         0.0        0.0       0
5955  20230505   161500    161959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-05-05 16:20:06,729:INFO:sr_min:main.py:175:handleKline:449472: self.closeSec=1683274799, self.tradeDate='20230505', self.openTime='161500', self.closeTime='161959',self.symbol='BTCUSDT',self.open=29085.9, self.close=29091.0, self.high=29109.9, self.low=29070.1, self.vol=1935.301, self.amt=56306645.1413, ukdf['pct'].iloc[-1]=0.000179 , ukdf['amount'].iloc[-1]=56306645.1413, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5955, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': []}
type(curSign)=<class 'int'>, curSign=0, self.sign=0
127.0.0.1 - - [05/May/2023 16:25:02] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=0, self.total=1000000.0, self.flagDict['side']='', self.tradeCount=0, self.count=41812
self.closeSec=1683275099, self.tradeDate='20230505', self.openTime='162000', self.closeTime='162459', self.symbol='BTCUSDT', self.open=29091.0, self.close=29098.6, self.high=29109.9, self.low=29088.5, self.vol=803.149, self.amt=23371988.5375 
2023-05-05 16:25:02,195:INFO:sr_min:main.py:172:handleKline:449472: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5952  20230505   160000    160459  ...         0.0        0.0       0
5953  20230505   160500    160959  ...         0.0        0.0       0
5954  20230505   161000    161459  ...         0.0        0.0       0
5955  20230505   161500    161959  ...         0.0        0.0       0
5956  20230505   162000    162459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-05-05 16:25:02,195:INFO:sr_min:main.py:175:handleKline:449472: self.closeSec=1683275099, self.tradeDate='20230505', self.openTime='162000', self.closeTime='162459',self.symbol='BTCUSDT',self.open=29091.0, self.close=29098.6, self.high=29109.9, self.low=29088.5, self.vol=803.149, self.amt=23371988.5375, ukdf['pct'].iloc[-1]=0.000261 , ukdf['amount'].iloc[-1]=23371988.5375, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5956, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': []}
type(curSign)=<class 'int'>, curSign=0, self.sign=0


## /root/FIL/strategy/s_rsrs/log.txt ----- -----

721  20230505   040000    075959  1683244799  ...    721  0.437957 -0.626680    -1.0
722  20230505   080000    115959  1683259199  ...    722  0.462259 -0.551894     NaN

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '46.718', 'enterprice': '29341.3', 'countrevence': '0', 'unrealprofit': '7073.1052', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '29189.9', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-9223372036854775808, self.sign=-1
127.0.0.1 - - [05/May/2023 16:00:03] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='s_rsrs', self.symbol='BTCUSDT', interval='4h', intervalSec=14400, wid=25, thd=0.6, self.sign=-1, self.total=1369396.0865466, self.flagDict['side']='sell', self.tradeCount=33, self.count=966
self.closeSec=1683273599, self.tradeDate='20230505', self.openTime='120000', self.closeTime='155959', self.symbol='BTCUSDT', self.open=29187.0, self.close=29059.0, self.high=29264.3, self.low=29025.0, self.vol=52721.949, self.amt=1537098354.25572 
2023-05-05 16:00:03,156:INFO:s_rsrs:main.py:141:handleKline:185271: self.closeSec=1683273599, self.tradeDate='20230505', self.openTime='120000', self.closeTime='155959',self.symbol='BTCUSDT',self.open=29187.0, self.close=29059.0, self.high=29264.3, self.low=29025.0, self.vol=52721.949, self.amt=1537098354.25572 
2023-05-05 16:00:03,185:INFO:s_rsrs:main.py:142:handleKline:185271: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime  ...         vol           amt       pct
719  20230504   200000    235959  ...  145934.750  4.214657e+09 -0.010122
720  20230505   000000    035959  ...   73790.969  2.126806e+09  0.001151
721  20230505   040000    075959  ...   29440.989  8.483901e+08 -0.001980
722  20230505   080000    115959  ...  115027.039  3.359784e+09  0.012523
723  20230505   120000    155959  ...   52721.949  1.537098e+09 -0.004386

[5 rows x 11 columns]
2023-05-05 16:00:04,571:INFO:s_rsrs:main.py:151:handleKline:185271: df_s.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec  ...  index      beta    zscore  signal
719  20230504   200000    235959  1683215999  ...    719  0.693773  0.177212     NaN
720  20230505   000000    035959  1683230399  ...    720  0.574766 -0.198913     NaN
721  20230505   040000    075959  1683244799  ...    721  0.437957 -0.626680    -1.0
722  20230505   080000    115959  1683259199  ...    722  0.462259 -0.551894     NaN
723  20230505   120000    155959  1683273599  ...    723  0.498481 -0.439408     NaN

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '46.718', 'enterprice': '29341.3', 'countrevence': '0', 'unrealprofit': '13193.1632', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '29058.9', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-9223372036854775808, self.sign=-1


