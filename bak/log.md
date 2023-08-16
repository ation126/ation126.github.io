# 20230817 00:26:01

## /root/FIL/strategy/amihud/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=373746.4768026, self.flagDict['side']='sell', self.tradeCount=2, self.count=27220
self.closeSec=1692202799, self.tradeDate='20230817', self.openTime='001500', self.closeTime='001959', self.symbol='BTCUSDT', self.open=29013.2, self.close=28967.6, self.high=29036.3, self.low=28940.0, self.vol=5507.233, self.amt=159649207.9305 
127.0.0.1 - - [17/Aug/2023 00:20:01] "POST / HTTP/1.1" 200 -
2023-08-17 00:20:05,565:INFO:amihud:main.py:172:handleKline:2219019: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5747  20230816   235000    235459  ...         0.0        0.0       0
5748  20230817   000000    000459  ...         0.0        0.0       0
5749  20230817   000500    000959  ...         0.0        0.0       0
5750  20230817   001000    001459  ...         0.0        0.0       0
5751  20230817   001500    001959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-08-17 00:20:05,577:INFO:amihud:main.py:175:handleKline:2219019: self.closeSec=1692202799, self.tradeDate='20230817', self.openTime='001500', self.closeTime='001959',self.symbol='BTCUSDT',self.open=29013.2, self.close=28967.6, self.high=29036.3, self.low=28940.0, self.vol=5507.233, self.amt=159649207.9305, ukdf['pct'].iloc[-1]=-0.001554 , ukdf['amount'].iloc[-1]=159649207.9305, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5751, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '13.926', 'enterprice': '26864.9', 'countrevence': '0', 'unrealprofit': '-29470.2012', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '28981.1', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1
127.0.0.1 - - [17/Aug/2023 00:25:00] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=373746.4768026, self.flagDict['side']='sell', self.tradeCount=2, self.count=27221
self.closeSec=1692203099, self.tradeDate='20230817', self.openTime='002000', self.closeTime='002459', self.symbol='BTCUSDT', self.open=28976.1, self.close=28996.0, self.high=29008.9, self.low=28955.6, self.vol=3261.399, self.amt=94525304.4867 
2023-08-17 00:25:00,803:INFO:amihud:main.py:172:handleKline:2219019: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5748  20230817   000000    000459  ...         0.0        0.0       0
5749  20230817   000500    000959  ...         0.0        0.0       0
5750  20230817   001000    001459  ...         0.0        0.0       0
5751  20230817   001500    001959  ...         0.0        0.0       0
5752  20230817   002000    002459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-08-17 00:25:00,804:INFO:amihud:main.py:175:handleKline:2219019: self.closeSec=1692203099, self.tradeDate='20230817', self.openTime='002000', self.closeTime='002459',self.symbol='BTCUSDT',self.open=28976.1, self.close=28996.0, self.high=29008.9, self.low=28955.6, self.vol=3261.399, self.amt=94525304.4867, ukdf['pct'].iloc[-1]=0.00098 , ukdf['amount'].iloc[-1]=94525304.4867, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5752, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '13.926', 'enterprice': '26864.9', 'countrevence': '0', 'unrealprofit': '-29755.6842', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '29001.6', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1


## /root/FIL/strategy/factorcheck/log.txt ----- -----

[5 rows x 11 columns] 
      tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1353  20230816   164500    164959  1692175799  ...  29182.4 -0.000524   1641    3
1354  20230816   165000    165459  1692176099  ...  29171.7 -0.000164   1642    4
1355  20230816   165500    165959  1692176399  ...  29171.0 -0.000288   1643    5
1356  20230816   170000    170459  1692176699  ...  29165.1 -0.000120   1644    0
1357  20230816   170500    170959  1692176999  ...  29150.7 -0.000576   1645    1

[5 rows x 11 columns] 


--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.714181719035411, self.count=27220 

self.closeSec=1692202199, self.tradeDate='20230817', self.openTime='000500', self.closeTime='000959', self.symbol='BTCUSDT', self.open=29071.4, self.close=29058.2, self.high=29088.2, self.low=29042.0 
127.0.0.1 - - [17/Aug/2023 00:10:00] "POST / HTTP/1.1" 200 -

--handleKline--:  127.0.0.1 - - [17/Aug/2023 00:15:00] "POST / HTTP/1.1" 200 -
version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.714181719035411, self.count=27221 

self.closeSec=1692202499, self.tradeDate='20230817', self.openTime='001000', self.closeTime='001459', self.symbol='BTCUSDT', self.open=29058.2, self.close=29012.7, self.high=29070.9, self.low=28950.0 

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.714181719035411, self.count=27222 

self.closeSec=1692202799, self.tradeDate='20230817', self.openTime='001500', self.closeTime='001959', self.symbol='BTCUSDT', self.open=29013.2, self.close=28967.6, self.high=29036.3, self.low=28940.0 
127.0.0.1 - - [17/Aug/2023 00:20:01] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [17/Aug/2023 00:25:00] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.714181719035411, self.count=27223 

self.closeSec=1692203099, self.tradeDate='20230817', self.openTime='002000', self.closeTime='002459', self.symbol='BTCUSDT', self.open=28976.1, self.close=28996.0, self.high=29008.9, self.low=28955.6 


## /root/FIL/strategy/logic/log.txt ----- -----

2023-08-17 00:00:17,257:DEBUG:logic:main.py:463:getModel:2218526: df_s.iloc[-5:,:] :
          date closeTime     open  ...    alpha58   alpha67   alpha72
5801  20230816    212959  29151.1  ...  47.916667  0.433229  0.696396
5802  20230816    215959  29118.1  ...  47.500000  0.420133  0.705931
5803  20230816    222959  29077.6  ...  47.500000  0.440787  0.705109
5804  20230816    225959  29125.6  ...  47.500000  0.453575  0.698080
5805  20230816    232959  29154.9  ...  47.500000  0.452494  0.689653

[5 rows x 33 columns]
0.5533088235294118
acc is : 0.5533088235294118
2023-08-17 00:00:17,323:INFO:logic:main.py:468:getModel:2218526: df_pred.iloc[-5:,:] :
     pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
539     1  0.485581  0.514419       0  ...  1.023652  -1.0    0.0  1.001540
540     1  0.483142  0.516858       1  ...  1.022050  -1.0    0.0  1.003107
541     0  0.506067  0.493933       1  ...  1.021022  -1.0    0.0  1.004116
542     0  0.507490  0.492510       0  ...  1.021127  -1.0    0.0  1.004012
543     1  0.496135  0.503865       0  ...  1.021754  -1.0    0.0  1.003396

[5 rows x 10 columns]
2023-08-17 00:00:17,335:INFO:logic:main.py:478:getModel:2218526: df_panel.iloc[-5:,:] :
    pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
45     1  0.485375  0.514625       0  ...  1.023652  -1.0    0.0  0.999766
46     1  0.483317  0.516683       1  ...  1.022050  -1.0    0.0  1.002057
47     0  0.506359  0.493641       1  ...  1.021022  -1.0    0.0  1.003404
48     0  0.507632  0.492368       0  ...  1.021127  -1.0    0.0  1.003301
49     1  0.496135  0.503865       0  ...  1.021754  -1.0    0.0  1.003396

[5 rows x 10 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '23.521', 'enterprice': '29410.3', 'countrevence': '0', 'unrealprofit': '7298.5663', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '29100', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}


## /root/FIL/strategy/modifiedmom/log.txt ----- -----


--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=13607 

self.closeSec=1692199799, self.tradeDate='20230816', self.openTime='232000', self.closeTime='232959', self.symbol='BTCUSDT', self.open='29145', self.close='29151.9'
127.0.0.1 - - [16/Aug/2023 23:30:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=13608 

self.closeSec=1692200399, self.tradeDate='20230816', self.openTime='233000', self.closeTime='233959', self.symbol='BTCUSDT', self.open='29151.9', self.close='29153.6'
127.0.0.1 - - [16/Aug/2023 23:40:01] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [16/Aug/2023 23:50:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=13609 

self.closeSec=1692200699, self.tradeDate='20230816', self.openTime='234000', self.closeTime='234459', self.symbol='BTCUSDT', self.open='29153.7', self.close='29146.8'

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=13610 

self.closeSec=1692201299, self.tradeDate='20230816', self.openTime='235000', self.closeTime='235459', self.symbol='BTCUSDT', self.open='29141.5', self.close='29134'
127.0.0.1 - - [17/Aug/2023 00:00:02] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=13611 

self.closeSec=1692202199, self.tradeDate='20230817', self.openTime='000000', self.closeTime='000959', self.symbol='BTCUSDT', self.open='29097.9', self.close='29058.1'
127.0.0.1 - - [17/Aug/2023 00:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=13612 

self.closeSec=1692202799, self.tradeDate='20230817', self.openTime='001000', self.closeTime='001959', self.symbol='BTCUSDT', self.open='29058.2', self.close='28976.2'
127.0.0.1 - - [17/Aug/2023 00:20:04] "POST / HTTP/1.1" 200 -


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


--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=13610 

self.closeSec=1692199799, self.tradeDate='20230816', self.openTime='232000', self.closeTime='232959', self.symbol='BTCUSDT', self.open='29145', self.close='29151.9'
127.0.0.1 - - [16/Aug/2023 23:30:01] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [16/Aug/2023 23:40:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=13611 

self.closeSec=1692200399, self.tradeDate='20230816', self.openTime='233000', self.closeTime='233959', self.symbol='BTCUSDT', self.open='29151.9', self.close='29153.6'
127.0.0.1 - - [16/Aug/2023 23:50:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=13612 

self.closeSec=1692200699, self.tradeDate='20230816', self.openTime='234000', self.closeTime='234459', self.symbol='BTCUSDT', self.open='29153.7', self.close='29146.8'

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=13613 

self.closeSec=1692201299, self.tradeDate='20230816', self.openTime='235000', self.closeTime='235459', self.symbol='BTCUSDT', self.open='29141.5', self.close='29134'
127.0.0.1 - - [17/Aug/2023 00:00:02] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=13614 

self.closeSec=1692202199, self.tradeDate='20230817', self.openTime='000000', self.closeTime='000959', self.symbol='BTCUSDT', self.open='29097.9', self.close='29058.1'
127.0.0.1 - - [17/Aug/2023 00:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=13615 

self.closeSec=1692202799, self.tradeDate='20230817', self.openTime='001000', self.closeTime='001959', self.symbol='BTCUSDT', self.open='29058.2', self.close='28976.2'
127.0.0.1 - - [17/Aug/2023 00:20:04] "POST / HTTP/1.1" 200 -


## /root/FIL/strategy/similarity/log.txt ----- -----


--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=13610 

self.closeSec=1692199799, self.tradeDate='20230816', self.openTime='232000', self.closeTime='232959', self.symbol='BTCUSDT', self.open='29145', self.close='29151.9'
127.0.0.1 - - [16/Aug/2023 23:30:01] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [16/Aug/2023 23:40:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=13611 

self.closeSec=1692200399, self.tradeDate='20230816', self.openTime='233000', self.closeTime='233959', self.symbol='BTCUSDT', self.open='29151.9', self.close='29153.6'
127.0.0.1 - - [16/Aug/2023 23:50:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=13612 

self.closeSec=1692200699, self.tradeDate='20230816', self.openTime='234000', self.closeTime='234459', self.symbol='BTCUSDT', self.open='29153.7', self.close='29146.8'

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=13613 

self.closeSec=1692201299, self.tradeDate='20230816', self.openTime='235000', self.closeTime='235459', self.symbol='BTCUSDT', self.open='29141.5', self.close='29134'
127.0.0.1 - - [17/Aug/2023 00:00:02] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [17/Aug/2023 00:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=13614 

self.closeSec=1692202199, self.tradeDate='20230817', self.openTime='000000', self.closeTime='000959', self.symbol='BTCUSDT', self.open='29097.9', self.close='29058.1'

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=13615 

self.closeSec=1692202799, self.tradeDate='20230817', self.openTime='001000', self.closeTime='001959', self.symbol='BTCUSDT', self.open='29058.2', self.close='28976.2'
127.0.0.1 - - [17/Aug/2023 00:20:04] "POST / HTTP/1.1" 200 -


## /root/FIL/strategy/sr_min/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=1, self.total=996015.990996, self.flagDict['side']='buy', self.tradeCount=1, self.count=27220
self.closeSec=1692202799, self.tradeDate='20230817', self.openTime='001500', self.closeTime='001959', self.symbol='BTCUSDT', self.open=29013.2, self.close=28967.6, self.high=29036.3, self.low=28940.0, self.vol=5507.233, self.amt=159649207.9305 
127.0.0.1 - - [17/Aug/2023 00:20:01] "POST / HTTP/1.1" 200 -
2023-08-17 00:20:05,537:INFO:sr_min:main.py:172:handleKline:2219263: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5747  20230816   235000    235459  ...         0.0        0.0       0
5748  20230817   000000    000459  ...         0.0        0.0       0
5749  20230817   000500    000959  ...         0.0        0.0       0
5750  20230817   001000    001459  ...         0.0        0.0       0
5751  20230817   001500    001959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-08-17 00:20:05,547:INFO:sr_min:main.py:175:handleKline:2219263: self.closeSec=1692202799, self.tradeDate='20230817', self.openTime='001500', self.closeTime='001959',self.symbol='BTCUSDT',self.open=29013.2, self.close=28967.6, self.high=29036.3, self.low=28940.0, self.vol=5507.233, self.amt=159649207.9305, ukdf['pct'].iloc[-1]=-0.001554 , ukdf['amount'].iloc[-1]=159649207.9305, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5751, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '37.141', 'enterprice': '26844', 'countrevence': '0', 'unrealprofit': '79374.0311', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '28981.1', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=1
127.0.0.1 - - [17/Aug/2023 00:25:00] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=1, self.total=996015.990996, self.flagDict['side']='buy', self.tradeCount=1, self.count=27221
self.closeSec=1692203099, self.tradeDate='20230817', self.openTime='002000', self.closeTime='002459', self.symbol='BTCUSDT', self.open=28976.1, self.close=28996.0, self.high=29008.9, self.low=28955.6, self.vol=3261.399, self.amt=94525304.4867 
2023-08-17 00:25:00,827:INFO:sr_min:main.py:172:handleKline:2219263: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5748  20230817   000000    000459  ...         0.0        0.0       0
5749  20230817   000500    000959  ...         0.0        0.0       0
5750  20230817   001000    001459  ...         0.0        0.0       0
5751  20230817   001500    001959  ...         0.0        0.0       0
5752  20230817   002000    002459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-08-17 00:25:00,827:INFO:sr_min:main.py:175:handleKline:2219263: self.closeSec=1692203099, self.tradeDate='20230817', self.openTime='002000', self.closeTime='002459',self.symbol='BTCUSDT',self.open=28976.1, self.close=28996.0, self.high=29008.9, self.low=28955.6, self.vol=3261.399, self.amt=94525304.4867, ukdf['pct'].iloc[-1]=0.00098 , ukdf['amount'].iloc[-1]=94525304.4867, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5752, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '37.141', 'enterprice': '26844', 'countrevence': '0', 'unrealprofit': '80135.4216', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '29001.6', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=1


## /root/FIL/strategy/s_rsrs/log.txt ----- -----

723  20230816   120000    155959  1692172799  ...    723  0.030721 -1.054429    -1.0
724  20230816   160000    195959  1692187199  ...    724  0.064153 -0.976557    -1.0

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '51.388', 'enterprice': '29432.6', 'countrevence': '0', 'unrealprofit': '14189.69436985068', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '29156.47144139', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-1, self.sign=-1
127.0.0.1 - - [17/Aug/2023 00:00:01] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='s_rsrs', self.symbol='BTCUSDT', interval='4h', intervalSec=14400, wid=25, thd=0.6, self.sign=-1, self.total=1510969.9663512, self.flagDict['side']='sell', self.tradeCount=20, self.count=567
self.closeSec=1692201599, self.tradeDate='20230816', self.openTime='200000', self.closeTime='235959', self.symbol='BTCUSDT', self.open=29154.9, self.close=29134.0, self.high=29206.6, self.low=29030.0, self.vol=52724.95, self.amt=1535489175.5258 
2023-08-17 00:00:01,611:INFO:s_rsrs:main.py:141:handleKline:2218689: self.closeSec=1692201599, self.tradeDate='20230816', self.openTime='200000', self.closeTime='235959',self.symbol='BTCUSDT',self.open=29154.9, self.close=29134.0, self.high=29206.6, self.low=29030.0, self.vol=52724.95, self.amt=1535489175.5258 
2023-08-17 00:00:01,632:INFO:s_rsrs:main.py:142:handleKline:2218689: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime  ...        vol           amt       pct
721  20230816   040000    075959  ...  22102.685  6.452457e+08  0.000562
722  20230816   080000    115959  ...  18146.820  5.302372e+08  0.000952
723  20230816   120000    155959  ...  25778.007  7.518555e+08 -0.001017
724  20230816   160000    195959  ...  10302.574  3.005547e+08 -0.001100
725  20230816   200000    235959  ...  52724.950  1.535489e+09 -0.000717

[5 rows x 11 columns]
2023-08-17 00:00:02,424:INFO:s_rsrs:main.py:151:handleKline:2218689: df_s.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec  ...  index      beta    zscore  signal
721  20230816   040000    075959  1692143999  ...    721  0.002208 -1.120043    -1.0
722  20230816   080000    115959  1692158399  ...    722  0.009182 -1.104510    -1.0
723  20230816   120000    155959  1692172799  ...    723  0.030721 -1.054429    -1.0
724  20230816   160000    195959  1692187199  ...    724  0.064153 -0.976557    -1.0
725  20230816   200000    235959  1692201599  ...    725  0.112624 -0.865000    -1.0

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '51.388', 'enterprice': '29432.6', 'countrevence': '0', 'unrealprofit': '17184.47915157748', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '29098.19354029', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-1, self.sign=-1


