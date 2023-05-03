# 20230503 16:26:01

## /root/FIL/strategy/amihud/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=993672.4896432, self.flagDict['side']='sell', self.tradeCount=2, self.count=45237
self.closeSec=1683101999, self.tradeDate='20230503', self.openTime='161500', self.closeTime='161959', self.symbol='BTCUSDT', self.open=28629.8, self.close=28655.2, self.high=28660.0, self.low=28621.7, self.vol=1008.628, self.amt=28892606.2155 
127.0.0.1 - - [03/May/2023 16:20:03] "POST / HTTP/1.1" 200 -
2023-05-03 16:20:06,256:INFO:amihud:main.py:172:handleKline:200676: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5951  20230503   155500    155959  ...         0.0        0.0       0
5952  20230503   160000    160459  ...         0.0        0.0       0
5953  20230503   160500    160959  ...         0.0        0.0       0
5954  20230503   161000    161459  ...         0.0        0.0       0
5955  20230503   161500    161959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-05-03 16:20:06,266:INFO:amihud:main.py:175:handleKline:200676: self.closeSec=1683101999, self.tradeDate='20230503', self.openTime='161500', self.closeTime='161959',self.symbol='BTCUSDT',self.open=28629.8, self.close=28655.2, self.high=28660.0, self.low=28621.7, self.vol=1008.628, self.amt=28892606.2155, ukdf['pct'].iloc[-1]=0.000884 , ukdf['amount'].iloc[-1]=28892606.2155, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5955, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '60.176', 'enterprice': '16529.3', 'countrevence': '0', 'unrealprofit': '-729749.59523041888', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '28656.22095238', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1
--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=993672.4896432, self.flagDict['side']='sell', self.tradeCount=2, self.count=45238
self.closeSec=1683102299, self.tradeDate='20230503', self.openTime='162000', self.closeTime='162459', self.symbol='BTCUSDT', self.open=28655.2, self.close=28598.0, self.high=28655.2, self.low=28580.5, self.vol=1353.831, self.amt=38733866.8827 
127.0.0.1 - - [03/May/2023 16:25:02] "POST / HTTP/1.1" 200 -
2023-05-03 16:25:02,113:INFO:amihud:main.py:172:handleKline:200676: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5952  20230503   160000    160459  ...         0.0        0.0       0
5953  20230503   160500    160959  ...         0.0        0.0       0
5954  20230503   161000    161459  ...         0.0        0.0       0
5955  20230503   161500    161959  ...         0.0        0.0       0
5956  20230503   162000    162459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-05-03 16:25:02,114:INFO:amihud:main.py:175:handleKline:200676: self.closeSec=1683102299, self.tradeDate='20230503', self.openTime='162000', self.closeTime='162459',self.symbol='BTCUSDT',self.open=28655.2, self.close=28598.0, self.high=28655.2, self.low=28580.5, self.vol=1353.831, self.amt=38733866.8827, ukdf['pct'].iloc[-1]=-0.001996 , ukdf['amount'].iloc[-1]=38733866.8827, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5956, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '60.176', 'enterprice': '16529.3', 'countrevence': '0', 'unrealprofit': '-726246.0912', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '28598', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1


## /root/FIL/strategy/factorcheck/log.txt ----- -----

127.0.0.1 - - [03/May/2023 16:00:02] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=23, self.factor=0.43541661550691446, self.count=45799 

self.closeSec=1683100799, self.tradeDate='20230503', self.openTime='155500', self.closeTime='155959', self.symbol='BTCUSDT', self.open=28621.7, self.close=28638.3, self.high=28656.7, self.low=28621.7 

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=23, self.factor=0.43541661550691446, self.count=45800 

self.closeSec=1683101099, self.tradeDate='20230503', self.openTime='160000', self.closeTime='160459', self.symbol='BTCUSDT', self.open=28638.4, self.close=28635.7, self.high=28643.6, self.low=28632.2 
127.0.0.1 - - [03/May/2023 16:05:02] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [03/May/2023 16:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=23, self.factor=0.43541661550691446, self.count=45801 

self.closeSec=1683101399, self.tradeDate='20230503', self.openTime='160500', self.closeTime='160959', self.symbol='BTCUSDT', self.open=28635.8, self.close=28608.1, self.high=28635.8, self.low=28608.0 

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=23, self.factor=0.43541661550691446, self.count=45802 

self.closeSec=1683101699, self.tradeDate='20230503', self.openTime='161000', self.closeTime='161459', self.symbol='BTCUSDT', self.open=28608.1, self.close=28629.9, self.high=28629.9, self.low=28608.0 
127.0.0.1 - - [03/May/2023 16:15:02] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=23, self.factor=0.43541661550691446, self.count=45803 

self.closeSec=1683101999, self.tradeDate='20230503', self.openTime='161500', self.closeTime='161959', self.symbol='BTCUSDT', self.open=28629.8, self.close=28655.2, self.high=28660.0, self.low=28621.7 
127.0.0.1 - - [03/May/2023 16:20:02] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=23, self.factor=0.43541661550691446, self.count=45804 

self.closeSec=1683102299, self.tradeDate='20230503', self.openTime='162000', self.closeTime='162459', self.symbol='BTCUSDT', self.open=28655.2, self.close=28598.0, self.high=28655.2, self.low=28580.5 
127.0.0.1 - - [03/May/2023 16:25:02] "POST / HTTP/1.1" 200 -


## /root/FIL/strategy/logic/log.txt ----- -----

2023-05-03 16:00:18,862:DEBUG:logic:main.py:463:getModel:885513: df_s.iloc[-5:,:] :
          date closeTime     open  ...    alpha58   alpha67   alpha72
5785  20230503    132959  28500.0  ...  49.166667  0.499736  0.345927
5786  20230503    135959  28473.9  ...  49.166667  0.498686  0.351218
5787  20230503    142959  28467.9  ...  49.583333  0.507622  0.352730
5788  20230503    145959  28518.6  ...  49.583333  0.519811  0.349356
5789  20230503    152959  28589.5  ...  50.000000  0.528974  0.342523

[5 rows x 33 columns]
0.5369003690036901
acc is : 0.5369003690036901
2023-05-03 16:00:18,971:INFO:logic:main.py:468:getModel:885513: df_pred.iloc[-5:,:] :
     pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
537     1  0.495822  0.504178       0  ...  0.931306   1.0    0.0  1.045968
538     1  0.497676  0.502324       1  ...  0.932968   1.0    0.0  1.047835
539     0  0.512655  0.487345       1  ...  0.935287   1.0    0.0  1.050440
540     0  0.520911  0.479089       1  ...  0.937073   1.0    0.0  1.052446
541     0  0.522106  0.477894       0  ...  0.936884   1.0    0.0  1.052233

[5 rows x 10 columns]
2023-05-03 16:00:18,996:INFO:logic:main.py:478:getModel:885513: df_panel.iloc[-5:,:] :
    pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
45     1  0.495868  0.504132       0  ...  0.931306   1.0    0.0  1.044318
46     1  0.497467  0.502533       1  ...  0.932968   1.0    0.0  1.045062
47     0  0.512647  0.487353       1  ...  0.935287   1.0    0.0  1.049060
48     0  0.520646  0.479354       1  ...  0.937073   1.0    0.0  1.050381
49     0  0.522106  0.477894       0  ...  0.936884   1.0    0.0  1.052233

[5 rows x 10 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': []}


## /root/FIL/strategy/modifiedmom/log.txt ----- -----


--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=22897 

self.closeSec=1683098999, self.tradeDate='20230503', self.openTime='152000', self.closeTime='152959', self.symbol='BTCUSDT', self.open='28605.1', self.close='28644.1'
127.0.0.1 - - [03/May/2023 15:30:03] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=22898 

self.closeSec=1683099599, self.tradeDate='20230503', self.openTime='153000', self.closeTime='153959', self.symbol='BTCUSDT', self.open='28644.1', self.close='28618.9'
127.0.0.1 - - [03/May/2023 15:40:02] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [03/May/2023 15:50:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=22899 

self.closeSec=1683100199, self.tradeDate='20230503', self.openTime='154000', self.closeTime='154959', self.symbol='BTCUSDT', self.open='28618.9', self.close='28617.8'
127.0.0.1 - - [03/May/2023 16:00:03] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=22900 

self.closeSec=1683100799, self.tradeDate='20230503', self.openTime='155000', self.closeTime='155959', self.symbol='BTCUSDT', self.open='28617.9', self.close='28638.3'
127.0.0.1 - - [03/May/2023 16:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=22901 

self.closeSec=1683101399, self.tradeDate='20230503', self.openTime='160000', self.closeTime='160959', self.symbol='BTCUSDT', self.open='28638.4', self.close='28608.1'

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=22902 

self.closeSec=1683101999, self.tradeDate='20230503', self.openTime='161000', self.closeTime='161959', self.symbol='BTCUSDT', self.open='28608.1', self.close='28655.2'
127.0.0.1 - - [03/May/2023 16:20:03] "POST / HTTP/1.1" 200 -


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


--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=22898 

self.closeSec=1683098999, self.tradeDate='20230503', self.openTime='152000', self.closeTime='152959', self.symbol='BTCUSDT', self.open='28605.1', self.close='28644.1'
127.0.0.1 - - [03/May/2023 15:30:03] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [03/May/2023 15:40:02] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=22899 

self.closeSec=1683099599, self.tradeDate='20230503', self.openTime='153000', self.closeTime='153959', self.symbol='BTCUSDT', self.open='28644.1', self.close='28618.9'

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=22900 

self.closeSec=1683100199, self.tradeDate='20230503', self.openTime='154000', self.closeTime='154959', self.symbol='BTCUSDT', self.open='28618.9', self.close='28617.8'
127.0.0.1 - - [03/May/2023 15:50:01] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [03/May/2023 16:00:03] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=22901 

self.closeSec=1683100799, self.tradeDate='20230503', self.openTime='155000', self.closeTime='155959', self.symbol='BTCUSDT', self.open='28617.9', self.close='28638.3'
127.0.0.1 - - [03/May/2023 16:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=22902 

self.closeSec=1683101399, self.tradeDate='20230503', self.openTime='160000', self.closeTime='160959', self.symbol='BTCUSDT', self.open='28638.4', self.close='28608.1'

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=22903 

self.closeSec=1683101999, self.tradeDate='20230503', self.openTime='161000', self.closeTime='161959', self.symbol='BTCUSDT', self.open='28608.1', self.close='28655.2'
127.0.0.1 - - [03/May/2023 16:20:04] "POST / HTTP/1.1" 200 -


## /root/FIL/strategy/similarity/log.txt ----- -----


--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=22898 

self.closeSec=1683098999, self.tradeDate='20230503', self.openTime='152000', self.closeTime='152959', self.symbol='BTCUSDT', self.open='28605.1', self.close='28644.1'
127.0.0.1 - - [03/May/2023 15:30:03] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=22899 

self.closeSec=1683099599, self.tradeDate='20230503', self.openTime='153000', self.closeTime='153959', self.symbol='BTCUSDT', self.open='28644.1', self.close='28618.9'
127.0.0.1 - - [03/May/2023 15:40:02] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=22900 

self.closeSec=1683100199, self.tradeDate='20230503', self.openTime='154000', self.closeTime='154959', self.symbol='BTCUSDT', self.open='28618.9', self.close='28617.8'
127.0.0.1 - - [03/May/2023 15:50:01] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [03/May/2023 16:00:03] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=22901 

self.closeSec=1683100799, self.tradeDate='20230503', self.openTime='155000', self.closeTime='155959', self.symbol='BTCUSDT', self.open='28617.9', self.close='28638.3'

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=22902 

self.closeSec=1683101399, self.tradeDate='20230503', self.openTime='160000', self.closeTime='160959', self.symbol='BTCUSDT', self.open='28638.4', self.close='28608.1'
127.0.0.1 - - [03/May/2023 16:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=22903 

self.closeSec=1683101999, self.tradeDate='20230503', self.openTime='161000', self.closeTime='161959', self.symbol='BTCUSDT', self.open='28608.1', self.close='28655.2'
127.0.0.1 - - [03/May/2023 16:20:04] "POST / HTTP/1.1" 200 -


## /root/FIL/strategy/sr_min/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=0, self.total=1000000.0, self.flagDict['side']='', self.tradeCount=0, self.count=41235
self.closeSec=1683101999, self.tradeDate='20230503', self.openTime='161500', self.closeTime='161959', self.symbol='BTCUSDT', self.open=28629.8, self.close=28655.2, self.high=28660.0, self.low=28621.7, self.vol=1008.628, self.amt=28892606.2155 
127.0.0.1 - - [03/May/2023 16:20:03] "POST / HTTP/1.1" 200 -
2023-05-03 16:20:06,117:INFO:sr_min:main.py:172:handleKline:449472: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5951  20230503   155500    155959  ...         0.0        0.0       0
5952  20230503   160000    160459  ...         0.0        0.0       0
5953  20230503   160500    160959  ...         0.0        0.0       0
5954  20230503   161000    161459  ...         0.0        0.0       0
5955  20230503   161500    161959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-05-03 16:20:06,127:INFO:sr_min:main.py:175:handleKline:449472: self.closeSec=1683101999, self.tradeDate='20230503', self.openTime='161500', self.closeTime='161959',self.symbol='BTCUSDT',self.open=28629.8, self.close=28655.2, self.high=28660.0, self.low=28621.7, self.vol=1008.628, self.amt=28892606.2155, ukdf['pct'].iloc[-1]=0.000884 , ukdf['amount'].iloc[-1]=28892606.2155, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5955, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': []}
type(curSign)=<class 'int'>, curSign=0, self.sign=0
127.0.0.1 - - [03/May/2023 16:25:02] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=0, self.total=1000000.0, self.flagDict['side']='', self.tradeCount=0, self.count=41236
self.closeSec=1683102299, self.tradeDate='20230503', self.openTime='162000', self.closeTime='162459', self.symbol='BTCUSDT', self.open=28655.2, self.close=28598.0, self.high=28655.2, self.low=28580.5, self.vol=1353.831, self.amt=38733866.8827 
2023-05-03 16:25:02,110:INFO:sr_min:main.py:172:handleKline:449472: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5952  20230503   160000    160459  ...         0.0        0.0       0
5953  20230503   160500    160959  ...         0.0        0.0       0
5954  20230503   161000    161459  ...         0.0        0.0       0
5955  20230503   161500    161959  ...         0.0        0.0       0
5956  20230503   162000    162459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-05-03 16:25:02,112:INFO:sr_min:main.py:175:handleKline:449472: self.closeSec=1683102299, self.tradeDate='20230503', self.openTime='162000', self.closeTime='162459',self.symbol='BTCUSDT',self.open=28655.2, self.close=28598.0, self.high=28655.2, self.low=28580.5, self.vol=1353.831, self.amt=38733866.8827, ukdf['pct'].iloc[-1]=-0.001996 , ukdf['amount'].iloc[-1]=38733866.8827, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5956, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': []}
type(curSign)=<class 'int'>, curSign=0, self.sign=0


## /root/FIL/strategy/s_rsrs/log.txt ----- -----

721  20230503   040000    075959  1683071999  ...    721  0.553597 -0.218806     NaN
722  20230503   080000    115959  1683086399  ...    722  0.566359 -0.177206     NaN

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '46.718', 'enterprice': '29341.3', 'countrevence': '0', 'unrealprofit': '38948.4146359679', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '28507.60817595', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-9223372036854775808, self.sign=-1
--handleKline--:  version='2.0.0', self.name='s_rsrs', self.symbol='BTCUSDT', interval='4h', intervalSec=14400, wid=25, thd=0.6, self.sign=-1, self.total=1369396.0865466, self.flagDict['side']='sell', self.tradeCount=33, self.count=954
self.closeSec=1683100799, self.tradeDate='20230503', self.openTime='120000', self.closeTime='155959', self.symbol='BTCUSDT', self.open=28505.5, self.close=28638.3, self.high=28674.0, self.low=28407.3, self.vol=44177.432, self.amt=1261075134.1175 
127.0.0.1 - - [03/May/2023 16:00:03] "POST / HTTP/1.1" 200 -
2023-05-03 16:00:03,232:INFO:s_rsrs:main.py:141:handleKline:185271: self.closeSec=1683100799, self.tradeDate='20230503', self.openTime='120000', self.closeTime='155959',self.symbol='BTCUSDT',self.open=28505.5, self.close=28638.3, self.high=28674.0, self.low=28407.3, self.vol=44177.432, self.amt=1261075134.1175 
2023-05-03 16:00:03,255:INFO:s_rsrs:main.py:142:handleKline:185271: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime  ...         vol           amt       pct
719  20230502   200000    235959  ...  231567.459  6.564339e+09  0.016010
720  20230503   000000    035959  ...  110120.500  3.152380e+09  0.005181
721  20230503   040000    075959  ...   48455.705  1.390300e+09 -0.000589
722  20230503   080000    115959  ...   58108.623  1.656345e+09 -0.005273
723  20230503   120000    155959  ...   44177.432  1.261075e+09  0.004662

[5 rows x 11 columns]
2023-05-03 16:00:04,610:INFO:s_rsrs:main.py:151:handleKline:185271: df_s.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec  ...  index      beta    zscore  signal
719  20230502   200000    235959  1683043199  ...    719  0.567059 -0.178762     NaN
720  20230503   000000    035959  1683057599  ...    720  0.560254 -0.200610     NaN
721  20230503   040000    075959  1683071999  ...    721  0.553597 -0.218806     NaN
722  20230503   080000    115959  1683086399  ...    722  0.566359 -0.177206     NaN
723  20230503   120000    155959  1683100799  ...    723  0.575571 -0.147166     NaN

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '46.718', 'enterprice': '29341.3', 'countrevence': '0', 'unrealprofit': '32838.0822', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '28638.4', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-9223372036854775808, self.sign=-1


