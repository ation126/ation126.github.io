# 20230415 00:26:02

## /root/FIL/strategy/amihud/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=993672.4896432, self.flagDict['side']='sell', self.tradeCount=2, self.count=39861
self.closeSec=1681489199, self.tradeDate='20230415', self.openTime='001500', self.closeTime='001959', self.symbol='BTCUSDT', self.open=30262.8, self.close=30197.5, self.high=30264.3, self.low=30181.1, self.vol=1893.884, self.amt=57228609.706 
127.0.0.1 - - [15/Apr/2023 00:20:04] "POST / HTTP/1.1" 200 -
2023-04-15 00:20:07,389:INFO:amihud:main.py:172:handleKline:200676: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5752  20230414   235500    235959  ...         0.0        0.0       0
5753  20230415   000000    000459  ...         0.0        0.0       0
5754  20230415   000500    000959  ...         0.0        0.0       0
5755  20230415   001000    001459  ...         0.0        0.0       0
5756  20230415   001500    001959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-04-15 00:20:07,399:INFO:amihud:main.py:175:handleKline:200676: self.closeSec=1681489199, self.tradeDate='20230415', self.openTime='001500', self.closeTime='001959',self.symbol='BTCUSDT',self.open=30262.8, self.close=30197.5, self.high=30264.3, self.low=30181.1, self.vol=1893.884, self.amt=57228609.706, ukdf['pct'].iloc[-1]=-0.002115 , ukdf['amount'].iloc[-1]=57228609.706, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5756, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '60.176', 'enterprice': '16529.3', 'countrevence': '0', 'unrealprofit': '-822032.37705173648', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '30189.76890873', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1
--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=993672.4896432, self.flagDict['side']='sell', self.tradeCount=2, self.count=39862
self.closeSec=1681489499, self.tradeDate='20230415', self.openTime='002000', self.closeTime='002459', self.symbol='BTCUSDT', self.open=30197.6, self.close=30158.2, self.high=30200.1, self.low=30114.4, self.vol=3433.222, self.amt=103532295.6266 
127.0.0.1 - - [15/Apr/2023 00:25:01] "POST / HTTP/1.1" 200 -
2023-04-15 00:25:01,633:INFO:amihud:main.py:172:handleKline:200676: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5753  20230415   000000    000459  ...         0.0        0.0       0
5754  20230415   000500    000959  ...         0.0        0.0       0
5755  20230415   001000    001459  ...         0.0        0.0       0
5756  20230415   001500    001959  ...         0.0        0.0       0
5757  20230415   002000    002459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-04-15 00:25:01,636:INFO:amihud:main.py:175:handleKline:200676: self.closeSec=1681489499, self.tradeDate='20230415', self.openTime='002000', self.closeTime='002459',self.symbol='BTCUSDT',self.open=30197.6, self.close=30158.2, self.high=30200.1, self.low=30114.4, self.vol=3433.222, self.amt=103532295.6266, ukdf['pct'].iloc[-1]=-0.001301 , ukdf['amount'].iloc[-1]=103532295.6266, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5757, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '60.176', 'enterprice': '16529.3', 'countrevence': '0', 'unrealprofit': '-820251.1180213648', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '30160.1680873', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1


## /root/FIL/strategy/factorcheck/log.txt ----- -----

[5 rows x 11 columns] 
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
163  20230410   133500    133959  1681105199  ...  28220.3  0.000011   1603    1
164  20230410   134000    134459  1681105499  ...  28232.1  0.001654   1604    2
165  20230410   134500    134959  1681105799  ...  28265.5 -0.000453   1605    3
166  20230410   135000    135459  1681106099  ...  28251.1  0.000340   1606    4
167  20230410   135500    135959  1681106399  ...  28268.0 -0.000141   1607    5

[5 rows x 11 columns] 

127.0.0.1 - - [15/Apr/2023 00:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=23, self.factor=0.43541661550691446, self.count=40425 

self.closeSec=1681488599, self.tradeDate='20230415', self.openTime='000500', self.closeTime='000959', self.symbol='BTCUSDT', self.open=30231.8, self.close=30216.5, self.high=30231.8, self.low=30150.1 

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=23, self.factor=0.43541661550691446, self.count=40426 

self.closeSec=1681488899, self.tradeDate='20230415', self.openTime='001000', self.closeTime='001459', self.symbol='BTCUSDT', self.open=30216.5, self.close=30261.5, self.high=30263.4, self.low=30184.0 
127.0.0.1 - - [15/Apr/2023 00:15:01] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=23, self.factor=0.43541661550691446, self.count=40427 

self.closeSec=1681489199, self.tradeDate='20230415', self.openTime='001500', self.closeTime='001959', self.symbol='BTCUSDT', self.open=30262.8, self.close=30197.5, self.high=30264.3, self.low=30181.1 
127.0.0.1 - - [15/Apr/2023 00:20:04] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=23, self.factor=0.43541661550691446, self.count=40428 

self.closeSec=1681489499, self.tradeDate='20230415', self.openTime='002000', self.closeTime='002459', self.symbol='BTCUSDT', self.open=30197.6, self.close=30158.2, self.high=30200.1, self.low=30114.4 
127.0.0.1 - - [15/Apr/2023 00:25:01] "POST / HTTP/1.1" 200 -


## /root/FIL/strategy/logic/log.txt ----- -----

2023-04-15 00:00:36,206:DEBUG:logic:main.py:463:getModel:885513: df_s.iloc[-5:,:] :
          date closeTime     open  ...    alpha58   alpha67   alpha72
5801  20230414    212959  30606.5  ...  56.250000  0.559916  0.333661
5802  20230414    215959  30657.6  ...  56.666667  0.567202  0.338679
5803  20230414    222959  30701.6  ...  56.250000  0.542903  0.352233
5804  20230414    225959  30585.2  ...  56.250000  0.542781  0.364929
5805  20230414    232959  30584.6  ...  55.833333  0.477361  0.401598

[5 rows x 33 columns]
0.5643382352941176
acc is : 0.5643382352941176
2023-04-15 00:00:36,375:INFO:logic:main.py:468:getModel:885513: df_pred.iloc[-5:,:] :
     pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
539     0  0.505334  0.494666       1  ...  1.010153  -1.0    0.0  1.100215
540     0  0.506447  0.493553       0  ...  1.013979  -1.0    0.0  1.096047
541     1  0.465614  0.534386       0  ...  1.013999  -1.0    0.0  1.096025
542     1  0.489177  0.510823       0  ...  1.025848  -1.0    0.0  1.083218
543     1  0.410199  0.589801       0  ...  1.025869  -1.0    0.0  1.083196

[5 rows x 10 columns]
2023-04-15 00:00:36,410:INFO:logic:main.py:478:getModel:885513: df_panel.iloc[-5:,:] :
    pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
45     0  0.505819  0.494181       1  ...  1.037826   1.0    0.0  1.109727
46     0  0.506558  0.493442       0  ...  1.017492  -1.0    0.0  1.104242
47     1  0.465337  0.534663       0  ...  0.996710  -1.0    0.0  1.101596
48     1  0.489620  0.510380       0  ...  1.047259  -1.0    0.0  1.088723
49     1  0.410199  0.589801       0  ...  1.025869  -1.0    0.0  1.083196

[5 rows x 10 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': []}


## /root/FIL/strategy/modifiedmom/log.txt ----- -----


--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=20209 

self.closeSec=1681486199, self.tradeDate='20230414', self.openTime='232000', self.closeTime='232959', self.symbol='BTCUSDT', self.open='30442.7', self.close='30227.3'
127.0.0.1 - - [14/Apr/2023 23:30:01] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [14/Apr/2023 23:40:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=20210 

self.closeSec=1681486799, self.tradeDate='20230414', self.openTime='233000', self.closeTime='233959', self.symbol='BTCUSDT', self.open='30227.3', self.close='30247.9'

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=20211 

self.closeSec=1681487399, self.tradeDate='20230414', self.openTime='234000', self.closeTime='234959', self.symbol='BTCUSDT', self.open='30247.8', self.close='30290.4'
127.0.0.1 - - [14/Apr/2023 23:50:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=20212 

self.closeSec=1681487999, self.tradeDate='20230414', self.openTime='235000', self.closeTime='235959', self.symbol='BTCUSDT', self.open='30290.4', self.close='30226.7'
127.0.0.1 - - [15/Apr/2023 00:00:03] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=20213 

self.closeSec=1681488599, self.tradeDate='20230415', self.openTime='000000', self.closeTime='000959', self.symbol='BTCUSDT', self.open='30226.7', self.close='30216.4'
127.0.0.1 - - [15/Apr/2023 00:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=20214 

self.closeSec=1681489199, self.tradeDate='20230415', self.openTime='001000', self.closeTime='001959', self.symbol='BTCUSDT', self.open='30216.5', self.close='30197.5'
127.0.0.1 - - [15/Apr/2023 00:20:05] "POST / HTTP/1.1" 200 -


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

127.0.0.1 - - [14/Apr/2023 23:30:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=20210 

self.closeSec=1681486199, self.tradeDate='20230414', self.openTime='232000', self.closeTime='232959', self.symbol='BTCUSDT', self.open='30442.7', self.close='30227.3'
127.0.0.1 - - [14/Apr/2023 23:40:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=20211 

self.closeSec=1681486799, self.tradeDate='20230414', self.openTime='233000', self.closeTime='233959', self.symbol='BTCUSDT', self.open='30227.3', self.close='30247.9'

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=20212 

self.closeSec=1681487399, self.tradeDate='20230414', self.openTime='234000', self.closeTime='234959', self.symbol='BTCUSDT', self.open='30247.8', self.close='30290.4'
127.0.0.1 - - [14/Apr/2023 23:50:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=20213 

self.closeSec=1681487999, self.tradeDate='20230414', self.openTime='235000', self.closeTime='235959', self.symbol='BTCUSDT', self.open='30290.4', self.close='30226.7'
127.0.0.1 - - [15/Apr/2023 00:00:03] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=20214 

self.closeSec=1681488599, self.tradeDate='20230415', self.openTime='000000', self.closeTime='000959', self.symbol='BTCUSDT', self.open='30226.7', self.close='30216.4'
127.0.0.1 - - [15/Apr/2023 00:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=20215 

self.closeSec=1681489199, self.tradeDate='20230415', self.openTime='001000', self.closeTime='001959', self.symbol='BTCUSDT', self.open='30216.5', self.close='30197.5'
127.0.0.1 - - [15/Apr/2023 00:20:05] "POST / HTTP/1.1" 200 -


## /root/FIL/strategy/similarity/log.txt ----- -----

127.0.0.1 - - [14/Apr/2023 23:30:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=20210 

self.closeSec=1681486199, self.tradeDate='20230414', self.openTime='232000', self.closeTime='232959', self.symbol='BTCUSDT', self.open='30442.7', self.close='30227.3'
127.0.0.1 - - [14/Apr/2023 23:40:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=20211 

self.closeSec=1681486799, self.tradeDate='20230414', self.openTime='233000', self.closeTime='233959', self.symbol='BTCUSDT', self.open='30227.3', self.close='30247.9'

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=20212 

self.closeSec=1681487399, self.tradeDate='20230414', self.openTime='234000', self.closeTime='234959', self.symbol='BTCUSDT', self.open='30247.8', self.close='30290.4'
127.0.0.1 - - [14/Apr/2023 23:50:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=20213 

self.closeSec=1681487999, self.tradeDate='20230414', self.openTime='235000', self.closeTime='235959', self.symbol='BTCUSDT', self.open='30290.4', self.close='30226.7'
127.0.0.1 - - [15/Apr/2023 00:00:03] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=20214 

self.closeSec=1681488599, self.tradeDate='20230415', self.openTime='000000', self.closeTime='000959', self.symbol='BTCUSDT', self.open='30226.7', self.close='30216.4'
127.0.0.1 - - [15/Apr/2023 00:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=20215 

self.closeSec=1681489199, self.tradeDate='20230415', self.openTime='001000', self.closeTime='001959', self.symbol='BTCUSDT', self.open='30216.5', self.close='30197.5'
127.0.0.1 - - [15/Apr/2023 00:20:05] "POST / HTTP/1.1" 200 -


## /root/FIL/strategy/sr_min/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=0, self.total=1000000.0, self.flagDict['side']='', self.tradeCount=0, self.count=35859
self.closeSec=1681489199, self.tradeDate='20230415', self.openTime='001500', self.closeTime='001959', self.symbol='BTCUSDT', self.open=30262.8, self.close=30197.5, self.high=30264.3, self.low=30181.1, self.vol=1893.884, self.amt=57228609.706 
127.0.0.1 - - [15/Apr/2023 00:20:04] "POST / HTTP/1.1" 200 -
2023-04-15 00:20:07,338:INFO:sr_min:main.py:172:handleKline:449472: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5752  20230414   235500    235959  ...         0.0        0.0       0
5753  20230415   000000    000459  ...         0.0        0.0       0
5754  20230415   000500    000959  ...         0.0        0.0       0
5755  20230415   001000    001459  ...         0.0        0.0       0
5756  20230415   001500    001959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-04-15 00:20:07,347:INFO:sr_min:main.py:175:handleKline:449472: self.closeSec=1681489199, self.tradeDate='20230415', self.openTime='001500', self.closeTime='001959',self.symbol='BTCUSDT',self.open=30262.8, self.close=30197.5, self.high=30264.3, self.low=30181.1, self.vol=1893.884, self.amt=57228609.706, ukdf['pct'].iloc[-1]=-0.002115 , ukdf['amount'].iloc[-1]=57228609.706, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5756, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': []}
type(curSign)=<class 'int'>, curSign=0, self.sign=0
127.0.0.1 - - [15/Apr/2023 00:25:01] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=0, self.total=1000000.0, self.flagDict['side']='', self.tradeCount=0, self.count=35860
self.closeSec=1681489499, self.tradeDate='20230415', self.openTime='002000', self.closeTime='002459', self.symbol='BTCUSDT', self.open=30197.6, self.close=30158.2, self.high=30200.1, self.low=30114.4, self.vol=3433.222, self.amt=103532295.6266 
2023-04-15 00:25:01,628:INFO:sr_min:main.py:172:handleKline:449472: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5753  20230415   000000    000459  ...         0.0        0.0       0
5754  20230415   000500    000959  ...         0.0        0.0       0
5755  20230415   001000    001459  ...         0.0        0.0       0
5756  20230415   001500    001959  ...         0.0        0.0       0
5757  20230415   002000    002459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-04-15 00:25:01,631:INFO:sr_min:main.py:175:handleKline:449472: self.closeSec=1681489499, self.tradeDate='20230415', self.openTime='002000', self.closeTime='002459',self.symbol='BTCUSDT',self.open=30197.6, self.close=30158.2, self.high=30200.1, self.low=30114.4, self.vol=3433.222, self.amt=103532295.6266, ukdf['pct'].iloc[-1]=-0.001301 , ukdf['amount'].iloc[-1]=103532295.6266, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5757, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': []}
type(curSign)=<class 'int'>, curSign=0, self.sign=0


## /root/FIL/strategy/s_rsrs/log.txt ----- -----

723  20230414   120000    155959  1681459199  ...    723  0.818031  0.651874     1.0
724  20230414   160000    195959  1681473599  ...    724  0.681606  0.353538     NaN

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '52.515', 'enterprice': '28269.9', 'countrevence': '0', 'unrealprofit': '132201.19368889875', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '30787.29871825', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-9223372036854775808, self.sign=1
--handleKline--:  version='2.0.0', self.name='s_rsrs', self.symbol='BTCUSDT', interval='4h', intervalSec=14400, wid=25, thd=0.6, self.sign=1, self.total=1483109.2047015, self.flagDict['side']='buy', self.tradeCount=30, self.count=842
self.closeSec=1681487999, self.tradeDate='20230414', self.openTime='200000', self.closeTime='235959', self.symbol='BTCUSDT', self.open=30789.9, self.close=30226.7, self.high=30840.0, self.low=30080.1, self.vol=173876.177, self.amt=5301978811.8097 
127.0.0.1 - - [15/Apr/2023 00:00:02] "POST / HTTP/1.1" 200 -
2023-04-15 00:00:02,975:INFO:s_rsrs:main.py:141:handleKline:185271: self.closeSec=1681487999, self.tradeDate='20230414', self.openTime='200000', self.closeTime='235959',self.symbol='BTCUSDT',self.open=30789.9, self.close=30226.7, self.high=30840.0, self.low=30080.1, self.vol=173876.177, self.amt=5301978811.8097 
2023-04-15 00:00:03,020:INFO:s_rsrs:main.py:142:handleKline:185271: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime  ...         vol           amt       pct
721  20230414   040000    075959  ...   39042.382  1.182256e+09  0.001306
722  20230414   080000    115959  ...  143783.626  4.413223e+09  0.010602
723  20230414   120000    155959  ...   95052.482  2.930392e+09  0.001802
724  20230414   160000    195959  ...   51819.143  1.593152e+09  0.001630
725  20230414   200000    235959  ...  173876.177  5.301979e+09 -0.018295

[5 rows x 11 columns]
2023-04-15 00:00:05,613:INFO:s_rsrs:main.py:151:handleKline:185271: df_s.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec  ...  index      beta    zscore  signal
721  20230414   040000    075959  1681430399  ...    721  0.853519  0.747101     1.0
722  20230414   080000    115959  1681444799  ...    722  0.877030  0.787572     1.0
723  20230414   120000    155959  1681459199  ...    723  0.818031  0.651874     1.0
724  20230414   160000    195959  1681473599  ...    724  0.681606  0.353538     NaN
725  20230414   200000    235959  1681487999  ...    725  0.537512  0.042998     NaN

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '52.515', 'enterprice': '28269.9', 'countrevence': '0', 'unrealprofit': '102764.072056437', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '30226.7517958', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-9223372036854775808, self.sign=1


