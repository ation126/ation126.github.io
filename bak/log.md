# 20230912 00:26:01

## /root/FIL/strategy/amihud/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=373746.4768026, self.flagDict['side']='sell', self.tradeCount=2, self.count=34708
self.closeSec=1694449199, self.tradeDate='20230912', self.openTime='001500', self.closeTime='001959', self.symbol='BTCUSDT', self.open=25154.9, self.close=25132.1, self.high=25155.5, self.low=25109.6, self.vol=1789.459, self.amt=44975863.6731 
127.0.0.1 - - [12/Sep/2023 00:20:02] "POST / HTTP/1.1" 200 -
2023-09-12 00:20:06,206:INFO:amihud:main.py:172:handleKline:2219019: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5759  20230911   235500    235959  ...         0.0        0.0       0
5760  20230912   000000    000459  ...         0.0        0.0       0
5761  20230912   000500    000959  ...         0.0        0.0       0
5762  20230912   001000    001459  ...         0.0        0.0       0
5763  20230912   001500    001959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-09-12 00:20:06,210:INFO:amihud:main.py:175:handleKline:2219019: self.closeSec=1694449199, self.tradeDate='20230912', self.openTime='001500', self.closeTime='001959',self.symbol='BTCUSDT',self.open=25154.9, self.close=25132.1, self.high=25155.5, self.low=25109.6, self.vol=1789.459, self.amt=44975863.6731, ukdf['pct'].iloc[-1]=-0.000906 , ukdf['amount'].iloc[-1]=44975863.6731, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5763, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '13.926', 'enterprice': '26864.9', 'countrevence': '0', 'unrealprofit': '24130.07503214022', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '25132.16446703', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1
127.0.0.1 - - [12/Sep/2023 00:25:00] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=373746.4768026, self.flagDict['side']='sell', self.tradeCount=2, self.count=34709
self.closeSec=1694449499, self.tradeDate='20230912', self.openTime='002000', self.closeTime='002459', self.symbol='BTCUSDT', self.open=25132.0, self.close=25119.2, self.high=25143.7, self.low=25101.0, self.vol=1245.106, self.amt=31280381.3025 
2023-09-12 00:25:00,818:INFO:amihud:main.py:172:handleKline:2219019: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5760  20230912   000000    000459  ...         0.0        0.0       0
5761  20230912   000500    000959  ...         0.0        0.0       0
5762  20230912   001000    001459  ...         0.0        0.0       0
5763  20230912   001500    001959  ...         0.0        0.0       0
5764  20230912   002000    002459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-09-12 00:25:00,818:INFO:amihud:main.py:175:handleKline:2219019: self.closeSec=1694449499, self.tradeDate='20230912', self.openTime='002000', self.closeTime='002459',self.symbol='BTCUSDT',self.open=25132.0, self.close=25119.2, self.high=25143.7, self.low=25101.0, self.vol=1245.106, self.amt=31280381.3025, ukdf['pct'].iloc[-1]=-0.000513 , ukdf['amount'].iloc[-1]=31280381.3025, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5764, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '13.926', 'enterprice': '26864.9', 'countrevence': '0', 'unrealprofit': '24290.33413931256', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '25120.65656044', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1


## /root/FIL/strategy/factorcheck/log.txt ----- -----

self.closeSec=1694448299, self.tradeDate='20230912', self.openTime='000000', self.closeTime='000459', self.symbol='BTCUSDT', self.open=25102.4, self.close=25181.9, self.high=25193.2, self.low=25087.8 

--ukdf-hist--: overDate='20230907' 
 Empty DataFrame
Columns: [tradeDate, openTime, closeTime, closeSec, open, close, high, low, pct, index, idx]
Index: [] 
 Empty DataFrame
Columns: [tradeDate, openTime, closeTime, closeSec, open, close, high, low, pct, index, idx]
Index: [] 

127.0.0.1 - - [12/Sep/2023 00:10:00] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.714181719035411, self.count=34708 

self.closeSec=1694448599, self.tradeDate='20230912', self.openTime='000500', self.closeTime='000959', self.symbol='BTCUSDT', self.open=25181.8, self.close=25193.2, self.high=25193.2, self.low=25136.5 

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.714181719035411, self.count=34709 

self.closeSec=1694448899, self.tradeDate='20230912', self.openTime='001000', self.closeTime='001459', self.symbol='BTCUSDT', self.open=25193.2, self.close=25154.9, self.high=25240.6, self.low=25150.9 
127.0.0.1 - - [12/Sep/2023 00:15:00] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.714181719035411, self.count=34710 

self.closeSec=1694449199, self.tradeDate='20230912', self.openTime='001500', self.closeTime='001959', self.symbol='BTCUSDT', self.open=25154.9, self.close=25132.1, self.high=25155.5, self.low=25109.6 
127.0.0.1 - - [12/Sep/2023 00:20:02] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.714181719035411, self.count=34711 

self.closeSec=1694449499, self.tradeDate='20230912', self.openTime='002000', self.closeTime='002459', self.symbol='BTCUSDT', self.open=25132.0, self.close=25119.2, self.high=25143.7, self.low=25101.0 
127.0.0.1 - - [12/Sep/2023 00:25:00] "POST / HTTP/1.1" 200 -


## /root/FIL/strategy/logic/log.txt ----- -----

2023-09-12 00:00:17,360:DEBUG:logic:main.py:463:getModel:2218526: df_s.iloc[-5:,:] :
          date closeTime     open  ...    alpha58   alpha67   alpha72
5801  20230911    212959  25709.2  ...  52.083333  0.463862  0.590133
5802  20230911    215959  25673.4  ...  51.666667  0.444975  0.605211
5803  20230911    222959  25605.8  ...  51.666667  0.389560  0.617382
5804  20230911    225959  25375.9  ...  51.250000  0.344831  0.631888
5805  20230911    232959  25138.8  ...  51.250000  0.341087  0.644447

[5 rows x 33 columns]
0.5257352941176471
acc is : 0.5257352941176471
2023-09-12 00:00:17,419:INFO:logic:main.py:468:getModel:2218526: df_pred.iloc[-5:,:] :
     pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
539     1  0.482875  0.517125       0  ...  1.039590  -1.0    0.0  0.939693
540     1  0.473480  0.526520       0  ...  1.048973  -1.0    0.0  0.931212
541     1  0.418235  0.581765       0  ...  1.058725  -1.0    0.0  0.922555
542     1  0.398189  0.601811       0  ...  1.059656  -1.0    0.0  0.921744
543     1  0.442435  0.557565       0  ...  1.060213  -1.0    0.0  0.921260

[5 rows x 10 columns]
2023-09-12 00:00:17,430:INFO:logic:main.py:478:getModel:2218526: df_panel.iloc[-5:,:] :
    pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
45     1  0.483116  0.516884       0  ...  1.039590  -1.0    0.0  0.940515
46     1  0.473511  0.526489       0  ...  1.048973  -1.0    0.0  0.931370
47     1  0.418032  0.581968       0  ...  1.058725  -1.0    0.0  0.921571
48     1  0.398044  0.601956       0  ...  1.059656  -1.0    0.0  0.920761
49     1  0.442435  0.557565       0  ...  1.060213  -1.0    0.0  0.921260

[5 rows x 10 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '28.306', 'enterprice': '25771.5', 'countrevence': '0', 'unrealprofit': '19206.43741552194', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '25092.97115751', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}


## /root/FIL/strategy/modifiedmom/log.txt ----- -----

127.0.0.1 - - [11/Sep/2023 23:30:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=17351 

self.closeSec=1694446199, self.tradeDate='20230911', self.openTime='232000', self.closeTime='232959', self.symbol='BTCUSDT', self.open='25074.1', self.close='25116.7'

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=17352 

self.closeSec=1694446799, self.tradeDate='20230911', self.openTime='233000', self.closeTime='233959', self.symbol='BTCUSDT', self.open='25116.7', self.close='25089.4'
127.0.0.1 - - [11/Sep/2023 23:40:01] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [11/Sep/2023 23:50:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=17353 

self.closeSec=1694447399, self.tradeDate='20230911', self.openTime='234000', self.closeTime='234959', self.symbol='BTCUSDT', self.open='25089.3', self.close='25090.7'
127.0.0.1 - - [12/Sep/2023 00:00:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=17354 

self.closeSec=1694447999, self.tradeDate='20230911', self.openTime='235000', self.closeTime='235959', self.symbol='BTCUSDT', self.open='25090.6', self.close='25103.5'

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=17355 

self.closeSec=1694448599, self.tradeDate='20230912', self.openTime='000000', self.closeTime='000959', self.symbol='BTCUSDT', self.open='25102.4', self.close='25193.1'
127.0.0.1 - - [12/Sep/2023 00:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=17356 

self.closeSec=1694449199, self.tradeDate='20230912', self.openTime='001000', self.closeTime='001959', self.symbol='BTCUSDT', self.open='25193.2', self.close='25132.1'
127.0.0.1 - - [12/Sep/2023 00:20:04] "POST / HTTP/1.1" 200 -


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

127.0.0.1 - - [11/Sep/2023 23:30:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=17354 

self.closeSec=1694446199, self.tradeDate='20230911', self.openTime='232000', self.closeTime='232959', self.symbol='BTCUSDT', self.open='25074.1', self.close='25116.7'
127.0.0.1 - - [11/Sep/2023 23:40:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=17355 

self.closeSec=1694446799, self.tradeDate='20230911', self.openTime='233000', self.closeTime='233959', self.symbol='BTCUSDT', self.open='25116.7', self.close='25089.4'
127.0.0.1 - - [11/Sep/2023 23:50:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=17356 

self.closeSec=1694447399, self.tradeDate='20230911', self.openTime='234000', self.closeTime='234959', self.symbol='BTCUSDT', self.open='25089.3', self.close='25090.7'
127.0.0.1 - - [12/Sep/2023 00:00:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=17357 

self.closeSec=1694447999, self.tradeDate='20230911', self.openTime='235000', self.closeTime='235959', self.symbol='BTCUSDT', self.open='25090.6', self.close='25103.5'
127.0.0.1 - - [12/Sep/2023 00:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=17358 

self.closeSec=1694448599, self.tradeDate='20230912', self.openTime='000000', self.closeTime='000959', self.symbol='BTCUSDT', self.open='25102.4', self.close='25193.1'

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=17359 

self.closeSec=1694449199, self.tradeDate='20230912', self.openTime='001000', self.closeTime='001959', self.symbol='BTCUSDT', self.open='25193.2', self.close='25132.1'
127.0.0.1 - - [12/Sep/2023 00:20:05] "POST / HTTP/1.1" 200 -


## /root/FIL/strategy/similarity/log.txt ----- -----

127.0.0.1 - - [11/Sep/2023 23:30:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=17354 

self.closeSec=1694446199, self.tradeDate='20230911', self.openTime='232000', self.closeTime='232959', self.symbol='BTCUSDT', self.open='25074.1', self.close='25116.7'
127.0.0.1 - - [11/Sep/2023 23:40:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=17355 

self.closeSec=1694446799, self.tradeDate='20230911', self.openTime='233000', self.closeTime='233959', self.symbol='BTCUSDT', self.open='25116.7', self.close='25089.4'

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=17356 

self.closeSec=1694447399, self.tradeDate='20230911', self.openTime='234000', self.closeTime='234959', self.symbol='BTCUSDT', self.open='25089.3', self.close='25090.7'
127.0.0.1 - - [11/Sep/2023 23:50:01] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [12/Sep/2023 00:00:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=17357 

self.closeSec=1694447999, self.tradeDate='20230911', self.openTime='235000', self.closeTime='235959', self.symbol='BTCUSDT', self.open='25090.6', self.close='25103.5'
127.0.0.1 - - [12/Sep/2023 00:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=17358 

self.closeSec=1694448599, self.tradeDate='20230912', self.openTime='000000', self.closeTime='000959', self.symbol='BTCUSDT', self.open='25102.4', self.close='25193.1'

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=17359 

self.closeSec=1694449199, self.tradeDate='20230912', self.openTime='001000', self.closeTime='001959', self.symbol='BTCUSDT', self.open='25193.2', self.close='25132.1'
127.0.0.1 - - [12/Sep/2023 00:20:04] "POST / HTTP/1.1" 200 -


## /root/FIL/strategy/sr_min/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=1, self.total=996015.990996, self.flagDict['side']='buy', self.tradeCount=1, self.count=34708
self.closeSec=1694449199, self.tradeDate='20230912', self.openTime='001500', self.closeTime='001959', self.symbol='BTCUSDT', self.open=25154.9, self.close=25132.1, self.high=25155.5, self.low=25109.6, self.vol=1789.459, self.amt=44975863.6731 
127.0.0.1 - - [12/Sep/2023 00:20:02] "POST / HTTP/1.1" 200 -
2023-09-12 00:20:06,208:INFO:sr_min:main.py:172:handleKline:2219263: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5759  20230911   235500    235959  ...         0.0        0.0       0
5760  20230912   000000    000459  ...         0.0        0.0       0
5761  20230912   000500    000959  ...         0.0        0.0       0
5762  20230912   001000    001459  ...         0.0        0.0       0
5763  20230912   001500    001959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-09-12 00:20:06,212:INFO:sr_min:main.py:175:handleKline:2219263: self.closeSec=1694449199, self.tradeDate='20230912', self.openTime='001500', self.closeTime='001959',self.symbol='BTCUSDT',self.open=25154.9, self.close=25132.1, self.high=25155.5, self.low=25109.6, self.vol=1789.459, self.amt=44975863.6731, ukdf['pct'].iloc[-1]=-0.000906 , ukdf['amount'].iloc[-1]=44975863.6731, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5763, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '37.141', 'enterprice': '26844', 'countrevence': '0', 'unrealprofit': '-63579.28353003877', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '25132.16446703', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=1
127.0.0.1 - - [12/Sep/2023 00:25:00] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=1, self.total=996015.990996, self.flagDict['side']='buy', self.tradeCount=1, self.count=34709
self.closeSec=1694449499, self.tradeDate='20230912', self.openTime='002000', self.closeTime='002459', self.symbol='BTCUSDT', self.open=25132.0, self.close=25119.2, self.high=25143.7, self.low=25101.0, self.vol=1245.106, self.amt=31280381.3025 
2023-09-12 00:25:00,819:INFO:sr_min:main.py:172:handleKline:2219263: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5760  20230912   000000    000459  ...         0.0        0.0       0
5761  20230912   000500    000959  ...         0.0        0.0       0
5762  20230912   001000    001459  ...         0.0        0.0       0
5763  20230912   001500    001959  ...         0.0        0.0       0
5764  20230912   002000    002459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-09-12 00:25:00,820:INFO:sr_min:main.py:175:handleKline:2219263: self.closeSec=1694449499, self.tradeDate='20230912', self.openTime='002000', self.closeTime='002459',self.symbol='BTCUSDT',self.open=25132.0, self.close=25119.2, self.high=25143.7, self.low=25101.0, self.vol=1245.106, self.amt=31280381.3025, ukdf['pct'].iloc[-1]=-0.000513 , ukdf['amount'].iloc[-1]=31280381.3025, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5764, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '37.141', 'enterprice': '26844', 'countrevence': '0', 'unrealprofit': '-64006.69868869796', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '25120.65656044', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=1


## /root/FIL/strategy/s_rsrs/log.txt ----- -----

723  20230911   120000    155959  1694419199  ...    723  0.297896 -0.276374     NaN
724  20230911   160000    195959  1694433599  ...    724  0.290906 -0.294575     NaN

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '57.177', 'enterprice': '25892.3', 'countrevence': '0', 'unrealprofit': '17406.94378394835', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '25587.86038645', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-9223372036854775808, self.sign=-1
127.0.0.1 - - [12/Sep/2023 00:00:01] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='s_rsrs', self.symbol='BTCUSDT', interval='4h', intervalSec=14400, wid=25, thd=0.6, self.sign=-1, self.total=1478963.5930628998, self.flagDict['side']='sell', self.tradeCount=22, self.count=723
self.closeSec=1694447999, self.tradeDate='20230911', self.openTime='200000', self.closeTime='235959', self.symbol='BTCUSDT', self.open=25591.8, self.close=25103.5, self.high=25749.7, self.low=24915.0, self.vol=202776.195, self.amt=5125211900.54178 
2023-09-12 00:00:01,518:INFO:s_rsrs:main.py:141:handleKline:2218689: self.closeSec=1694447999, self.tradeDate='20230911', self.openTime='200000', self.closeTime='235959',self.symbol='BTCUSDT',self.open=25591.8, self.close=25103.5, self.high=25749.7, self.low=24915.0, self.vol=202776.195, self.amt=5125211900.54178 
2023-09-12 00:00:01,539:INFO:s_rsrs:main.py:142:handleKline:2218689: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime  ...         vol           amt       pct
721  20230911   040000    075959  ...   49095.382  1.270014e+09  0.001613
722  20230911   080000    115959  ...   32476.954  8.356556e+08 -0.003910
723  20230911   120000    155959  ...   25284.435  6.526423e+08  0.002872
724  20230911   160000    195959  ...   60165.089  1.545312e+09 -0.008116
725  20230911   200000    235959  ...  202776.195  5.125212e+09 -0.019084

[5 rows x 11 columns]
2023-09-12 00:00:02,288:INFO:s_rsrs:main.py:151:handleKline:2218689: df_s.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec  ...  index      beta    zscore  signal
721  20230911   040000    075959  1694390399  ...    721  0.332722 -0.181974     NaN
722  20230911   080000    115959  1694404799  ...    722  0.305950 -0.255287     NaN
723  20230911   120000    155959  1694419199  ...    723  0.297896 -0.276374     NaN
724  20230911   160000    195959  1694433599  ...    724  0.290906 -0.294575     NaN
725  20230911   200000    235959  1694447999  ...    725  0.086707 -0.854904    -1.0

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '57.177', 'enterprice': '25892.3', 'countrevence': '0', 'unrealprofit': '45158.3946', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '25102.5', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-1, self.sign=-1


