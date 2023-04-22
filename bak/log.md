# 20230422 16:26:02

## /root/FIL/strategy/amihud/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=993672.4896432, self.flagDict['side']='sell', self.tradeCount=2, self.count=42069
self.closeSec=1682151599, self.tradeDate='20230422', self.openTime='161500', self.closeTime='161959', self.symbol='BTCUSDT', self.open=27254.3, self.close=27267.4, self.high=27268.8, self.low=27240.2, self.vol=857.932, self.amt=23381332.1254 
127.0.0.1 - - [22/Apr/2023 16:20:02] "POST / HTTP/1.1" 200 -
2023-04-22 16:20:04,626:INFO:amihud:main.py:172:handleKline:200676: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5944  20230422   155500    155959  ...         0.0        0.0       0
5945  20230422   160000    160459  ...         0.0        0.0       0
5946  20230422   160500    160959  ...         0.0        0.0       0
5947  20230422   161000    161459  ...         0.0        0.0       0
5948  20230422   161500    161959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-04-22 16:20:04,628:INFO:amihud:main.py:175:handleKline:200676: self.closeSec=1682151599, self.tradeDate='20230422', self.openTime='161500', self.closeTime='161959',self.symbol='BTCUSDT',self.open=27254.3, self.close=27267.4, self.high=27268.8, self.low=27240.2, self.vol=857.932, self.amt=23381332.1254, ukdf['pct'].iloc[-1]=0.000484 , ukdf['amount'].iloc[-1]=23381332.1254, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5948, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '60.176', 'enterprice': '16529.3', 'countrevence': '0', 'unrealprofit': '-646151.8352', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '27267', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1
127.0.0.1 - - [22/Apr/2023 16:25:01] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=993672.4896432, self.flagDict['side']='sell', self.tradeCount=2, self.count=42070
self.closeSec=1682151899, self.tradeDate='20230422', self.openTime='162000', self.closeTime='162459', self.symbol='BTCUSDT', self.open=27267.3, self.close=27284.6, self.high=27299.9, self.low=27266.3, self.vol=1429.091, self.amt=38991504.6093 
2023-04-22 16:25:01,578:INFO:amihud:main.py:172:handleKline:200676: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5945  20230422   160000    160459  ...         0.0        0.0       0
5946  20230422   160500    160959  ...         0.0        0.0       0
5947  20230422   161000    161459  ...         0.0        0.0       0
5948  20230422   161500    161959  ...         0.0        0.0       0
5949  20230422   162000    162459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-04-22 16:25:01,579:INFO:amihud:main.py:175:handleKline:200676: self.closeSec=1682151899, self.tradeDate='20230422', self.openTime='162000', self.closeTime='162459',self.symbol='BTCUSDT',self.open=27267.3, self.close=27284.6, self.high=27299.9, self.low=27266.3, self.vol=1429.091, self.amt=38991504.6093, ukdf['pct'].iloc[-1]=0.000631 , ukdf['amount'].iloc[-1]=38991504.6093, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5949, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '60.176', 'enterprice': '16529.3', 'countrevence': '0', 'unrealprofit': '-647204.9152', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '27284.5', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1


## /root/FIL/strategy/factorcheck/log.txt ----- -----


--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=23, self.factor=0.43541661550691446, self.count=42631 

self.closeSec=1682150399, self.tradeDate='20230422', self.openTime='155500', self.closeTime='155959', self.symbol='BTCUSDT', self.open=27247.6, self.close=27268.3, self.high=27272.1, self.low=27245.4 
127.0.0.1 - - [22/Apr/2023 16:00:01] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=23, self.factor=0.43541661550691446, self.count=42632 

self.closeSec=1682150699, self.tradeDate='20230422', self.openTime='160000', self.closeTime='160459', self.symbol='BTCUSDT', self.open=27268.4, self.close=27266.3, self.high=27274.2, self.low=27264.1 
127.0.0.1 - - [22/Apr/2023 16:05:02] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [22/Apr/2023 16:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=23, self.factor=0.43541661550691446, self.count=42633 

self.closeSec=1682150999, self.tradeDate='20230422', self.openTime='160500', self.closeTime='160959', self.symbol='BTCUSDT', self.open=27266.4, self.close=27258.6, self.high=27270.4, self.low=27252.5 

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=23, self.factor=0.43541661550691446, self.count=42634 

self.closeSec=1682151299, self.tradeDate='20230422', self.openTime='161000', self.closeTime='161459', self.symbol='BTCUSDT', self.open=27258.6, self.close=27254.2, self.high=27260.5, self.low=27246.1 
127.0.0.1 - - [22/Apr/2023 16:15:02] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=23, self.factor=0.43541661550691446, self.count=42635 

self.closeSec=1682151599, self.tradeDate='20230422', self.openTime='161500', self.closeTime='161959', self.symbol='BTCUSDT', self.open=27254.3, self.close=27267.4, self.high=27268.8, self.low=27240.2 
127.0.0.1 - - [22/Apr/2023 16:20:02] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [22/Apr/2023 16:25:01] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=23, self.factor=0.43541661550691446, self.count=42636 

self.closeSec=1682151899, self.tradeDate='20230422', self.openTime='162000', self.closeTime='162459', self.symbol='BTCUSDT', self.open=27267.3, self.close=27284.6, self.high=27299.9, self.low=27266.3 


## /root/FIL/strategy/logic/log.txt ----- -----

2023-04-22 16:00:19,670:DEBUG:logic:main.py:463:getModel:885513: df_s.iloc[-5:,:] :
          date closeTime     open  ...    alpha58   alpha67   alpha72
5785  20230422    132959  27334.0  ...  49.583333  0.380916  0.817785
5786  20230422    135959  27325.9  ...  49.583333  0.392134  0.814161
5787  20230422    142959  27384.0  ...  49.583333  0.382334  0.815244
5788  20230422    145959  27303.6  ...  50.000000  0.388386  0.814522
5789  20230422    152959  27334.8  ...  49.583333  0.386405  0.814738

[5 rows x 33 columns]
0.544280442804428
acc is : 0.544280442804428
2023-04-22 16:00:19,758:INFO:logic:main.py:468:getModel:885513: df_pred.iloc[-5:,:] :
     pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
537     0  0.530681  0.469319       1  ...  0.875028  -1.0    0.0  0.915219
538     0  0.545819  0.454181       0  ...  0.877597  -1.0    0.0  0.912532
539     0  0.507268  0.492732       1  ...  0.876594  -1.0    0.0  0.913575
540     0  0.534519  0.465481       0  ...  0.877107  -1.0    0.0  0.913040
541     0  0.521769  0.478231       0  ...  0.878726  -1.0    0.0  0.911355

[5 rows x 10 columns]
2023-04-22 16:00:19,770:INFO:logic:main.py:478:getModel:885513: df_panel.iloc[-5:,:] :
    pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
45     0  0.531261  0.468739       1  ...  0.897659  -1.0    0.0  0.925754
46     0  0.546231  0.453769       0  ...  0.900295  -1.0    0.0  0.920385
47     0  0.507619  0.492381       1  ...  0.891590  -1.0    0.0  0.922749
48     0  0.534990  0.465010       0  ...  0.892112  -1.0    0.0  0.921065
49     0  0.521769  0.478231       0  ...  0.878726  -1.0    0.0  0.911355

[5 rows x 10 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': []}


## /root/FIL/strategy/modifiedmom/log.txt ----- -----


--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=21313 

self.closeSec=1682148599, self.tradeDate='20230422', self.openTime='152000', self.closeTime='152959', self.symbol='BTCUSDT', self.open='27328.2', self.close='27318.3'
127.0.0.1 - - [22/Apr/2023 15:30:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=21314 

self.closeSec=1682149199, self.tradeDate='20230422', self.openTime='153000', self.closeTime='153959', self.symbol='BTCUSDT', self.open='27318.4', self.close='27298.4'
127.0.0.1 - - [22/Apr/2023 15:40:02] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [22/Apr/2023 15:50:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=21315 

self.closeSec=1682149799, self.tradeDate='20230422', self.openTime='154000', self.closeTime='154959', self.symbol='BTCUSDT', self.open='27298.4', self.close='27236.5'

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=21316 

self.closeSec=1682150399, self.tradeDate='20230422', self.openTime='155000', self.closeTime='155959', self.symbol='BTCUSDT', self.open='27236.6', self.close='27268.4'
127.0.0.1 - - [22/Apr/2023 16:00:01] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [22/Apr/2023 16:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=21317 

self.closeSec=1682150999, self.tradeDate='20230422', self.openTime='160000', self.closeTime='160959', self.symbol='BTCUSDT', self.open='27268.4', self.close='27258.6'

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=21318 

self.closeSec=1682151599, self.tradeDate='20230422', self.openTime='161000', self.closeTime='161959', self.symbol='BTCUSDT', self.open='27258.6', self.close='27267.4'
127.0.0.1 - - [22/Apr/2023 16:20:03] "POST / HTTP/1.1" 200 -


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


--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=21314 

self.closeSec=1682148599, self.tradeDate='20230422', self.openTime='152000', self.closeTime='152959', self.symbol='BTCUSDT', self.open='27328.2', self.close='27318.3'
127.0.0.1 - - [22/Apr/2023 15:30:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=21315 

self.closeSec=1682149199, self.tradeDate='20230422', self.openTime='153000', self.closeTime='153959', self.symbol='BTCUSDT', self.open='27318.4', self.close='27298.4'
127.0.0.1 - - [22/Apr/2023 15:40:02] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=21316 

self.closeSec=1682149799, self.tradeDate='20230422', self.openTime='154000', self.closeTime='154959', self.symbol='BTCUSDT', self.open='27298.4', self.close='27236.5'
127.0.0.1 - - [22/Apr/2023 15:50:01] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [22/Apr/2023 16:00:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=21317 

self.closeSec=1682150399, self.tradeDate='20230422', self.openTime='155000', self.closeTime='155959', self.symbol='BTCUSDT', self.open='27236.6', self.close='27268.4'

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=21318 

self.closeSec=1682150999, self.tradeDate='20230422', self.openTime='160000', self.closeTime='160959', self.symbol='BTCUSDT', self.open='27268.4', self.close='27258.6'
127.0.0.1 - - [22/Apr/2023 16:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=21319 

self.closeSec=1682151599, self.tradeDate='20230422', self.openTime='161000', self.closeTime='161959', self.symbol='BTCUSDT', self.open='27258.6', self.close='27267.4'
127.0.0.1 - - [22/Apr/2023 16:20:04] "POST / HTTP/1.1" 200 -


## /root/FIL/strategy/similarity/log.txt ----- -----


--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=21314 

self.closeSec=1682148599, self.tradeDate='20230422', self.openTime='152000', self.closeTime='152959', self.symbol='BTCUSDT', self.open='27328.2', self.close='27318.3'
127.0.0.1 - - [22/Apr/2023 15:30:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=21315 

self.closeSec=1682149199, self.tradeDate='20230422', self.openTime='153000', self.closeTime='153959', self.symbol='BTCUSDT', self.open='27318.4', self.close='27298.4'
127.0.0.1 - - [22/Apr/2023 15:40:02] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=21316 

self.closeSec=1682149799, self.tradeDate='20230422', self.openTime='154000', self.closeTime='154959', self.symbol='BTCUSDT', self.open='27298.4', self.close='27236.5'
127.0.0.1 - - [22/Apr/2023 15:50:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=21317 

self.closeSec=1682150399, self.tradeDate='20230422', self.openTime='155000', self.closeTime='155959', self.symbol='BTCUSDT', self.open='27236.6', self.close='27268.4'
127.0.0.1 - - [22/Apr/2023 16:00:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=21318 

self.closeSec=1682150999, self.tradeDate='20230422', self.openTime='160000', self.closeTime='160959', self.symbol='BTCUSDT', self.open='27268.4', self.close='27258.6'
127.0.0.1 - - [22/Apr/2023 16:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=21319 

self.closeSec=1682151599, self.tradeDate='20230422', self.openTime='161000', self.closeTime='161959', self.symbol='BTCUSDT', self.open='27258.6', self.close='27267.4'
127.0.0.1 - - [22/Apr/2023 16:20:04] "POST / HTTP/1.1" 200 -


## /root/FIL/strategy/sr_min/log.txt ----- -----

--handleKline--: 127.0.0.1 - - [22/Apr/2023 16:20:01] "POST / HTTP/1.1" 200 -
 version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=0, self.total=1000000.0, self.flagDict['side']='', self.tradeCount=0, self.count=38067
self.closeSec=1682151599, self.tradeDate='20230422', self.openTime='161500', self.closeTime='161959', self.symbol='BTCUSDT', self.open=27254.3, self.close=27267.4, self.high=27268.8, self.low=27240.2, self.vol=857.932, self.amt=23381332.1254 
2023-04-22 16:20:02,244:INFO:sr_min:main.py:172:handleKline:449472: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5944  20230422   155500    155959  ...         0.0        0.0       0
5945  20230422   160000    160459  ...         0.0        0.0       0
5946  20230422   160500    160959  ...         0.0        0.0       0
5947  20230422   161000    161459  ...         0.0        0.0       0
5948  20230422   161500    161959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-04-22 16:20:02,275:INFO:sr_min:main.py:175:handleKline:449472: self.closeSec=1682151599, self.tradeDate='20230422', self.openTime='161500', self.closeTime='161959',self.symbol='BTCUSDT',self.open=27254.3, self.close=27267.4, self.high=27268.8, self.low=27240.2, self.vol=857.932, self.amt=23381332.1254, ukdf['pct'].iloc[-1]=0.000484 , ukdf['amount'].iloc[-1]=23381332.1254, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5948, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': []}
type(curSign)=<class 'int'>, curSign=0, self.sign=0
--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=0, self.total=1000000.0, self.flagDict['side']='', self.tradeCount=0, self.count=38068
self.closeSec=1682151899, self.tradeDate='20230422', self.openTime='162000', self.closeTime='162459', self.symbol='BTCUSDT', self.open=27267.3, self.close=27284.6, self.high=27299.9, self.low=27266.3, self.vol=1429.091, self.amt=38991504.6093 
127.0.0.1 - - [22/Apr/2023 16:25:01] "POST / HTTP/1.1" 200 -
2023-04-22 16:25:01,566:INFO:sr_min:main.py:172:handleKline:449472: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5945  20230422   160000    160459  ...         0.0        0.0       0
5946  20230422   160500    160959  ...         0.0        0.0       0
5947  20230422   161000    161459  ...         0.0        0.0       0
5948  20230422   161500    161959  ...         0.0        0.0       0
5949  20230422   162000    162459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-04-22 16:25:01,567:INFO:sr_min:main.py:175:handleKline:449472: self.closeSec=1682151899, self.tradeDate='20230422', self.openTime='162000', self.closeTime='162459',self.symbol='BTCUSDT',self.open=27267.3, self.close=27284.6, self.high=27299.9, self.low=27266.3, self.vol=1429.091, self.amt=38991504.6093, ukdf['pct'].iloc[-1]=0.000631 , ukdf['amount'].iloc[-1]=38991504.6093, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5949, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': []}
type(curSign)=<class 'int'>, curSign=0, self.sign=0


## /root/FIL/strategy/s_rsrs/log.txt ----- -----

721  20230422   040000    075959  1682121599  ...    721  0.820729  0.542145     NaN
722  20230422   080000    115959  1682135999  ...    722  0.887550  0.685065     1.0

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '52.515', 'enterprice': '28269.9', 'countrevence': '0', 'unrealprofit': '-50409.1485', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '27310', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=1, self.sign=1
127.0.0.1 - - [22/Apr/2023 16:00:01] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='s_rsrs', self.symbol='BTCUSDT', interval='4h', intervalSec=14400, wid=25, thd=0.6, self.sign=1, self.total=1483109.2047015, self.flagDict['side']='buy', self.tradeCount=30, self.count=888
self.closeSec=1682150399, self.tradeDate='20230422', self.openTime='120000', self.closeTime='155959', self.symbol='BTCUSDT', self.open=27309.9, self.close=27268.4, self.high=27387.8, self.low=27204.5, self.vol=36075.068, self.amt=985125888.3222 
2023-04-22 16:00:01,807:INFO:s_rsrs:main.py:141:handleKline:185271: self.closeSec=1682150399, self.tradeDate='20230422', self.openTime='120000', self.closeTime='155959',self.symbol='BTCUSDT',self.open=27309.9, self.close=27268.4, self.high=27387.8, self.low=27204.5, self.vol=36075.068, self.amt=985125888.3222 
2023-04-22 16:00:01,866:INFO:s_rsrs:main.py:142:handleKline:185271: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime  ...         vol           amt       pct
719  20230421   200000    235959  ...  126677.763  3.563100e+09 -0.000773
720  20230422   000000    035959  ...  211114.720  5.835342e+09 -0.027083
721  20230422   040000    075959  ...   91017.726  2.482800e+09 -0.000774
722  20230422   080000    115959  ...   45729.471  1.246370e+09  0.002106
723  20230422   120000    155959  ...   36075.068  9.851259e+08 -0.001520

[5 rows x 11 columns]
2023-04-22 16:00:03,971:INFO:s_rsrs:main.py:151:handleKline:185271: df_s.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec  ...  index      beta    zscore  signal
719  20230421   200000    235959  1682092799  ...    719  0.809080  0.543306     NaN
720  20230422   000000    035959  1682107199  ...    720  0.754491  0.399747     NaN
721  20230422   040000    075959  1682121599  ...    721  0.820729  0.542145     NaN
722  20230422   080000    115959  1682135999  ...    722  0.887550  0.685065     1.0
723  20230422   120000    155959  1682150399  ...    723  0.928324  0.765001     1.0

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '52.515', 'enterprice': '28269.9', 'countrevence': '0', 'unrealprofit': '-52589.5066981476', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '27268.48123016', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=1, self.sign=1


