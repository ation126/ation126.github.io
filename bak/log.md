# 20230411 00:26:01

## /root/FIL/strategy/amihud/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=993672.4896432, self.flagDict['side']='sell', self.tradeCount=2, self.count=38709
self.closeSec=1681143599, self.tradeDate='20230411', self.openTime='001500', self.closeTime='001959', self.symbol='BTCUSDT', self.open=28395.2, self.close=28404.5, self.high=28413.6, self.low=28385.7, self.vol=1041.415, self.amt=29579106.8299 
127.0.0.1 - - [11/Apr/2023 00:20:03] "POST / HTTP/1.1" 200 -
2023-04-11 00:20:06,596:INFO:amihud:main.py:172:handleKline:200676: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5752  20230410   235500    235959  ...         0.0        0.0       0
5753  20230411   000000    000459  ...         0.0        0.0       0
5754  20230411   000500    000959  ...         0.0        0.0       0
5755  20230411   001000    001459  ...         0.0        0.0       0
5756  20230411   001500    001959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-04-11 00:20:06,613:INFO:amihud:main.py:175:handleKline:200676: self.closeSec=1681143599, self.tradeDate='20230411', self.openTime='001500', self.closeTime='001959',self.symbol='BTCUSDT',self.open=28395.2, self.close=28404.5, self.high=28413.6, self.low=28385.7, self.vol=1041.415, self.amt=29579106.8299, ukdf['pct'].iloc[-1]=0.000324 , ukdf['amount'].iloc[-1]=29579106.8299, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5756, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '60.176', 'enterprice': '16529.3', 'countrevence': '0', 'unrealprofit': '-714832.37292900688', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '28408.32773413', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1
127.0.0.1 - - [11/Apr/2023 00:25:01] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=993672.4896432, self.flagDict['side']='sell', self.tradeCount=2, self.count=38710
self.closeSec=1681143899, self.tradeDate='20230411', self.openTime='002000', self.closeTime='002459', self.symbol='BTCUSDT', self.open=28404.6, self.close=28429.0, self.high=28436.0, self.low=28404.5, self.vol=964.969, self.amt=27426338.3469 
2023-04-11 00:25:01,935:INFO:amihud:main.py:172:handleKline:200676: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5753  20230411   000000    000459  ...         0.0        0.0       0
5754  20230411   000500    000959  ...         0.0        0.0       0
5755  20230411   001000    001459  ...         0.0        0.0       0
5756  20230411   001500    001959  ...         0.0        0.0       0
5757  20230411   002000    002459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-04-11 00:25:01,936:INFO:amihud:main.py:175:handleKline:200676: self.closeSec=1681143899, self.tradeDate='20230411', self.openTime='002000', self.closeTime='002459',self.symbol='BTCUSDT',self.open=28404.6, self.close=28429.0, self.high=28436.0, self.low=28404.5, self.vol=964.969, self.amt=27426338.3469, ukdf['pct'].iloc[-1]=0.000863 , ukdf['amount'].iloc[-1]=27426338.3469, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5757, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '60.176', 'enterprice': '16529.3', 'countrevence': '0', 'unrealprofit': '-716193.63189568928', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '28430.94902778', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1


## /root/FIL/strategy/factorcheck/log.txt ----- -----

[5 rows x 11 columns] 
      tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1315  20230410   133500    133959  1681105199  ...  28220.3  0.000011   1603    1
1316  20230410   134000    134459  1681105499  ...  28232.1  0.001654   1604    2
1317  20230410   134500    134959  1681105799  ...  28265.5 -0.000453   1605    3
1318  20230410   135000    135459  1681106099  ...  28251.1  0.000340   1606    4
1319  20230410   135500    135959  1681106399  ...  28268.0 -0.000141   1607    5

[5 rows x 11 columns] 

127.0.0.1 - - [11/Apr/2023 00:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=23, self.factor=0.43541661550691446, self.count=39273 

self.closeSec=1681142999, self.tradeDate='20230411', self.openTime='000500', self.closeTime='000959', self.symbol='BTCUSDT', self.open=28450.5, self.close=28401.4, self.high=28450.6, self.low=28368.9 

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=23, self.factor=0.43541661550691446, self.count=39274 

self.closeSec=1681143299, self.tradeDate='20230411', self.openTime='001000', self.closeTime='001459', self.symbol='BTCUSDT', self.open=28401.3, self.close=28395.3, self.high=28425.9, self.low=28394.0 
127.0.0.1 - - [11/Apr/2023 00:15:02] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=23, self.factor=0.43541661550691446, self.count=39275 

self.closeSec=1681143599, self.tradeDate='20230411', self.openTime='001500', self.closeTime='001959', self.symbol='BTCUSDT', self.open=28395.2, self.close=28404.5, self.high=28413.6, self.low=28385.7 
127.0.0.1 - - [11/Apr/2023 00:20:03] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=23, self.factor=0.43541661550691446, self.count=39276 

self.closeSec=1681143899, self.tradeDate='20230411', self.openTime='002000', self.closeTime='002459', self.symbol='BTCUSDT', self.open=28404.6, self.close=28429.0, self.high=28436.0, self.low=28404.5 
127.0.0.1 - - [11/Apr/2023 00:25:01] "POST / HTTP/1.1" 200 -


## /root/FIL/strategy/logic/log.txt ----- -----

2023-04-11 00:00:32,829:DEBUG:logic:main.py:463:getModel:885513: df_s.iloc[-5:,:] :
          date closeTime     open  ...    alpha58   alpha67   alpha72
5801  20230410    212959  28266.2  ...  47.500000  0.538745  0.356463
5802  20230410    215959  28242.1  ...  47.500000  0.527207  0.365246
5803  20230410    222959  28207.7  ...  47.916667  0.531758  0.373467
5804  20230410    225959  28223.0  ...  48.333333  0.551400  0.374498
5805  20230410    232959  28291.2  ...  48.750000  0.581818  0.365282

[5 rows x 33 columns]
0.5551470588235294
acc is : 0.5551470588235294
2023-04-11 00:00:33,033:INFO:logic:main.py:468:getModel:885513: df_pred.iloc[-5:,:] :
     pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
539     1  0.492733  0.507267       0  ...  0.929666   1.0    0.0  0.984734
540     1  0.488612  0.511388       1  ...  0.930170   1.0    0.0  0.985268
541     0  0.502004  0.497996       1  ...  0.932418   1.0    0.0  0.987649
542     0  0.519179  0.480821       1  ...  0.936238   1.0    0.0  0.991695
543     0  0.535744  0.464256       1  ...  0.936917   1.0    0.0  0.992414

[5 rows x 10 columns]
2023-04-11 00:00:33,076:INFO:logic:main.py:478:getModel:885513: df_panel.iloc[-5:,:] :
    pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
45     1  0.493716  0.506284       0  ...  0.929666   1.0    0.0  0.986256
46     1  0.489666  0.510334       1  ...  0.930170   1.0    0.0  0.987453
47     0  0.502911  0.497089       1  ...  0.932418   1.0    0.0  0.989030
48     0  0.519713  0.480287       1  ...  0.936238   1.0    0.0  0.993082
49     0  0.535744  0.464256       1  ...  0.936917   1.0    0.0  0.992414

[5 rows x 10 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': []}


## /root/FIL/strategy/modifiedmom/log.txt ----- -----


--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=19633 

self.closeSec=1681140599, self.tradeDate='20230410', self.openTime='232000', self.closeTime='232959', self.symbol='BTCUSDT', self.open='28426.7', self.close='28407.1'
127.0.0.1 - - [10/Apr/2023 23:30:02] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=19634 

self.closeSec=1681141199, self.tradeDate='20230410', self.openTime='233000', self.closeTime='233959', self.symbol='BTCUSDT', self.open='28407.1', self.close='28417.1'
127.0.0.1 - - [10/Apr/2023 23:40:02] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=19635 

self.closeSec=1681141799, self.tradeDate='20230410', self.openTime='234000', self.closeTime='234959', self.symbol='BTCUSDT', self.open='28417.1', self.close='28470.3'
127.0.0.1 - - [10/Apr/2023 23:50:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=19636 

self.closeSec=1681142399, self.tradeDate='20230410', self.openTime='235000', self.closeTime='235959', self.symbol='BTCUSDT', self.open='28470.3', self.close='28427.7'
127.0.0.1 - - [11/Apr/2023 00:00:02] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=19637 

self.closeSec=1681142999, self.tradeDate='20230411', self.openTime='000000', self.closeTime='000959', self.symbol='BTCUSDT', self.open='28427.7', self.close='28401.4'
127.0.0.1 - - [11/Apr/2023 00:10:02] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=19638 

self.closeSec=1681143599, self.tradeDate='20230411', self.openTime='001000', self.closeTime='001959', self.symbol='BTCUSDT', self.open='28401.3', self.close='28404.5'
127.0.0.1 - - [11/Apr/2023 00:20:04] "POST / HTTP/1.1" 200 -


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


--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=19634 

self.closeSec=1681140599, self.tradeDate='20230410', self.openTime='232000', self.closeTime='232959', self.symbol='BTCUSDT', self.open='28426.7', self.close='28407.1'
127.0.0.1 - - [10/Apr/2023 23:30:02] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=19635 

self.closeSec=1681141199, self.tradeDate='20230410', self.openTime='233000', self.closeTime='233959', self.symbol='BTCUSDT', self.open='28407.1', self.close='28417.1'
127.0.0.1 - - [10/Apr/2023 23:40:02] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=19636 

self.closeSec=1681141799, self.tradeDate='20230410', self.openTime='234000', self.closeTime='234959', self.symbol='BTCUSDT', self.open='28417.1', self.close='28470.3'
127.0.0.1 - - [10/Apr/2023 23:50:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=19637 

self.closeSec=1681142399, self.tradeDate='20230410', self.openTime='235000', self.closeTime='235959', self.symbol='BTCUSDT', self.open='28470.3', self.close='28427.7'
127.0.0.1 - - [11/Apr/2023 00:00:02] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [11/Apr/2023 00:10:02] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=19638 

self.closeSec=1681142999, self.tradeDate='20230411', self.openTime='000000', self.closeTime='000959', self.symbol='BTCUSDT', self.open='28427.7', self.close='28401.4'

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=19639 

self.closeSec=1681143599, self.tradeDate='20230411', self.openTime='001000', self.closeTime='001959', self.symbol='BTCUSDT', self.open='28401.3', self.close='28404.5'
127.0.0.1 - - [11/Apr/2023 00:20:05] "POST / HTTP/1.1" 200 -


## /root/FIL/strategy/similarity/log.txt ----- -----


--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=19634 

self.closeSec=1681140599, self.tradeDate='20230410', self.openTime='232000', self.closeTime='232959', self.symbol='BTCUSDT', self.open='28426.7', self.close='28407.1'
127.0.0.1 - - [10/Apr/2023 23:30:02] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=19635 

self.closeSec=1681141199, self.tradeDate='20230410', self.openTime='233000', self.closeTime='233959', self.symbol='BTCUSDT', self.open='28407.1', self.close='28417.1'
127.0.0.1 - - [10/Apr/2023 23:40:02] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=19636 

self.closeSec=1681141799, self.tradeDate='20230410', self.openTime='234000', self.closeTime='234959', self.symbol='BTCUSDT', self.open='28417.1', self.close='28470.3'
127.0.0.1 - - [10/Apr/2023 23:50:01] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [11/Apr/2023 00:00:02] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=19637 

self.closeSec=1681142399, self.tradeDate='20230410', self.openTime='235000', self.closeTime='235959', self.symbol='BTCUSDT', self.open='28470.3', self.close='28427.7'

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=19638 

self.closeSec=1681142999, self.tradeDate='20230411', self.openTime='000000', self.closeTime='000959', self.symbol='BTCUSDT', self.open='28427.7', self.close='28401.4'
127.0.0.1 - - [11/Apr/2023 00:10:02] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=19639 

self.closeSec=1681143599, self.tradeDate='20230411', self.openTime='001000', self.closeTime='001959', self.symbol='BTCUSDT', self.open='28401.3', self.close='28404.5'
127.0.0.1 - - [11/Apr/2023 00:20:05] "POST / HTTP/1.1" 200 -


## /root/FIL/strategy/sr_min/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=0, self.total=1000000.0, self.flagDict['side']='', self.tradeCount=0, self.count=34707
self.closeSec=1681143599, self.tradeDate='20230411', self.openTime='001500', self.closeTime='001959', self.symbol='BTCUSDT', self.open=28395.2, self.close=28404.5, self.high=28413.6, self.low=28385.7, self.vol=1041.415, self.amt=29579106.8299 
127.0.0.1 - - [11/Apr/2023 00:20:03] "POST / HTTP/1.1" 200 -
2023-04-11 00:20:06,567:INFO:sr_min:main.py:172:handleKline:449472: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5752  20230410   235500    235959  ...         0.0        0.0       0
5753  20230411   000000    000459  ...         0.0        0.0       0
5754  20230411   000500    000959  ...         0.0        0.0       0
5755  20230411   001000    001459  ...         0.0        0.0       0
5756  20230411   001500    001959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-04-11 00:20:06,575:INFO:sr_min:main.py:175:handleKline:449472: self.closeSec=1681143599, self.tradeDate='20230411', self.openTime='001500', self.closeTime='001959',self.symbol='BTCUSDT',self.open=28395.2, self.close=28404.5, self.high=28413.6, self.low=28385.7, self.vol=1041.415, self.amt=29579106.8299, ukdf['pct'].iloc[-1]=0.000324 , ukdf['amount'].iloc[-1]=29579106.8299, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5756, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': []}
type(curSign)=<class 'int'>, curSign=0, self.sign=0
--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=0, self.total=1000000.0, self.flagDict['side']='', self.tradeCount=0, self.count=34708
self.closeSec=1681143899, self.tradeDate='20230411', self.openTime='002000', self.closeTime='002459', self.symbol='BTCUSDT', self.open=28404.6, self.close=28429.0, self.high=28436.0, self.low=28404.5, self.vol=964.969, self.amt=27426338.3469 
127.0.0.1 - - [11/Apr/2023 00:25:01] "POST / HTTP/1.1" 200 -
2023-04-11 00:25:01,964:INFO:sr_min:main.py:172:handleKline:449472: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5753  20230411   000000    000459  ...         0.0        0.0       0
5754  20230411   000500    000959  ...         0.0        0.0       0
5755  20230411   001000    001459  ...         0.0        0.0       0
5756  20230411   001500    001959  ...         0.0        0.0       0
5757  20230411   002000    002459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-04-11 00:25:01,966:INFO:sr_min:main.py:175:handleKline:449472: self.closeSec=1681143899, self.tradeDate='20230411', self.openTime='002000', self.closeTime='002459',self.symbol='BTCUSDT',self.open=28404.6, self.close=28429.0, self.high=28436.0, self.low=28404.5, self.vol=964.969, self.amt=27426338.3469, ukdf['pct'].iloc[-1]=0.000863 , ukdf['amount'].iloc[-1]=27426338.3469, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5757, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': []}
type(curSign)=<class 'int'>, curSign=0, self.sign=0


## /root/FIL/strategy/s_rsrs/log.txt ----- -----

723  20230410   120000    155959  1681113599  ...    723  0.421837  0.737938     1.0
724  20230410   160000    195959  1681127999  ...    724  0.428663  0.753419     1.0

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '52.515', 'enterprice': '28269.9', 'countrevence': '0', 'unrealprofit': '1281.366', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '28294.3', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=1, self.sign=1
--handleKline--:  version='2.0.0', self.name='s_rsrs', self.symbol='BTCUSDT', interval='4h', intervalSec=14400, wid=25, thd=0.6, self.sign=1, self.total=1483109.2047015, self.flagDict['side']='buy', self.tradeCount=30, self.count=818
self.closeSec=1681142399, self.tradeDate='20230410', self.openTime='200000', self.closeTime='235959', self.symbol='BTCUSDT', self.open=28294.3, self.close=28427.7, self.high=28590.0, self.low=28153.6, self.vol=91955.851, self.amt=2606686738.02546 
127.0.0.1 - - [11/Apr/2023 00:00:01] "POST / HTTP/1.1" 200 -
2023-04-11 00:00:01,788:INFO:s_rsrs:main.py:141:handleKline:185271: self.closeSec=1681142399, self.tradeDate='20230410', self.openTime='200000', self.closeTime='235959',self.symbol='BTCUSDT',self.open=28294.3, self.close=28427.7, self.high=28590.0, self.low=28153.6, self.vol=91955.851, self.amt=2606686738.02546 
2023-04-11 00:00:01,829:INFO:s_rsrs:main.py:142:handleKline:185271: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime  ...        vol           amt       pct
721  20230410   040000    075959  ...  91999.792  2.607345e+09  0.006292
722  20230410   080000    115959  ...  39158.156  1.108645e+09 -0.001399
723  20230410   120000    155959  ...  32457.910  9.169262e+08  0.000297
724  20230410   160000    195959  ...  33714.023  9.544942e+08  0.000569
725  20230410   200000    235959  ...  91955.851  2.606687e+09  0.004715

[5 rows x 11 columns]
2023-04-11 00:00:04,058:INFO:s_rsrs:main.py:151:handleKline:185271: df_s.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec  ...  index      beta    zscore  signal
721  20230410   040000    075959  1681084799  ...    721  0.359606  0.471012     NaN
722  20230410   080000    115959  1681099199  ...    722  0.436473  0.827504     1.0
723  20230410   120000    155959  1681113599  ...    723  0.421837  0.737938     1.0
724  20230410   160000    195959  1681127999  ...    724  0.428663  0.753419     1.0
725  20230410   200000    235959  1681142399  ...    725  0.635240  1.725680     1.0

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '52.515', 'enterprice': '28269.9', 'countrevence': '0', 'unrealprofit': '8281.6155', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '28427.6', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=1, self.sign=1


