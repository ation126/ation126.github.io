# 20231003 00:26:01

## /root/FIL/strategy/amihud/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=373746.4768026, self.flagDict['side']='sell', self.tradeCount=2, self.count=40756
self.closeSec=1696263599, self.tradeDate='20231003', self.openTime='001500', self.closeTime='001959', self.symbol='BTCUSDT', self.open=28048.8, self.close=28084.3, self.high=28098.9, self.low=28017.4, self.vol=6301.841, self.amt=176878673.5985 
127.0.0.1 - - [03/Oct/2023 00:20:02] "POST / HTTP/1.1" 200 -
2023-10-03 00:20:06,101:INFO:amihud:main.py:172:handleKline:2219019: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5759  20231002   235500    235959  ...         0.0        0.0       0
5760  20231003   000000    000459  ...         0.0        0.0       0
5761  20231003   000500    000959  ...         0.0        0.0       0
5762  20231003   001000    001459  ...         0.0        0.0       0
5763  20231003   001500    001959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-10-03 00:20:06,112:INFO:amihud:main.py:175:handleKline:2219019: self.closeSec=1696263599, self.tradeDate='20231003', self.openTime='001500', self.closeTime='001959',self.symbol='BTCUSDT',self.open=28048.8, self.close=28084.3, self.high=28098.9, self.low=28017.4, self.vol=6301.841, self.amt=176878673.5985, ukdf['pct'].iloc[-1]=0.001109 , ukdf['amount'].iloc[-1]=176878673.5985, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5763, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '13.926', 'enterprice': '26864.9', 'countrevence': '0', 'unrealprofit': '-16960.8445754748', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '28082.8265098', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1
--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=373746.4768026, self.flagDict['side']='sell', self.tradeCount=2, self.count=40757
self.closeSec=1696263899, self.tradeDate='20231003', self.openTime='002000', self.closeTime='002459', self.symbol='BTCUSDT', self.open=28085.4, self.close=28072.3, self.high=28111.0, self.low=28045.3, self.vol=3089.764, self.amt=86772407.6628 
127.0.0.1 - - [03/Oct/2023 00:25:00] "POST / HTTP/1.1" 200 -
2023-10-03 00:25:00,826:INFO:amihud:main.py:172:handleKline:2219019: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5760  20231003   000000    000459  ...         0.0        0.0       0
5761  20231003   000500    000959  ...         0.0        0.0       0
5762  20231003   001000    001459  ...         0.0        0.0       0
5763  20231003   001500    001959  ...         0.0        0.0       0
5764  20231003   002000    002459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-10-03 00:25:00,826:INFO:amihud:main.py:175:handleKline:2219019: self.closeSec=1696263899, self.tradeDate='20231003', self.openTime='002000', self.closeTime='002459',self.symbol='BTCUSDT',self.open=28085.4, self.close=28072.3, self.high=28111.0, self.low=28045.3, self.vol=3089.764, self.amt=86772407.6628, ukdf['pct'].iloc[-1]=-0.000427 , ukdf['amount'].iloc[-1]=86772407.6628, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5764, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '13.926', 'enterprice': '26864.9', 'countrevence': '0', 'unrealprofit': '-16825.3932', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '28073.1', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1


## /root/FIL/strategy/factorcheck/log.txt ----- -----

self.closeSec=1696262699, self.tradeDate='20231003', self.openTime='000000', self.closeTime='000459', self.symbol='BTCUSDT', self.open=28015.0, self.close=27902.2, self.high=28044.7, self.low=27890.0 

--ukdf-hist--: overDate='20230928' 
 Empty DataFrame
Columns: [tradeDate, openTime, closeTime, closeSec, open, close, high, low, pct, index, idx]
Index: [] 
 Empty DataFrame
Columns: [tradeDate, openTime, closeTime, closeSec, open, close, high, low, pct, index, idx]
Index: [] 

127.0.0.1 - - [03/Oct/2023 00:10:00] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.714181719035411, self.count=40756 

self.closeSec=1696262999, self.tradeDate='20231003', self.openTime='000500', self.closeTime='000959', self.symbol='BTCUSDT', self.open=27900.1, self.close=27947.5, self.high=27972.0, self.low=27838.5 

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.714181719035411, self.count=40757 

self.closeSec=1696263299, self.tradeDate='20231003', self.openTime='001000', self.closeTime='001459', self.symbol='BTCUSDT', self.open=27949.3, self.close=28053.2, self.high=28056.0, self.low=27900.0 
127.0.0.1 - - [03/Oct/2023 00:15:00] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.714181719035411, self.count=40758 

self.closeSec=1696263599, self.tradeDate='20231003', self.openTime='001500', self.closeTime='001959', self.symbol='BTCUSDT', self.open=28048.8, self.close=28084.3, self.high=28098.9, self.low=28017.4 
127.0.0.1 - - [03/Oct/2023 00:20:02] "POST / HTTP/1.1" 200 -

--handleKline--: 127.0.0.1 - - [03/Oct/2023 00:25:00] "POST / HTTP/1.1" 200 -
 version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.714181719035411, self.count=40759 

self.closeSec=1696263899, self.tradeDate='20231003', self.openTime='002000', self.closeTime='002459', self.symbol='BTCUSDT', self.open=28085.4, self.close=28072.3, self.high=28111.0, self.low=28045.3 


## /root/FIL/strategy/logic/log.txt ----- -----

2023-10-03 00:00:17,798:DEBUG:logic:main.py:463:getModel:2218526: df_s.iloc[-5:,:] :
          date closeTime     open  ...    alpha58   alpha67   alpha72
5801  20231002    212959  28305.0  ...  55.833333  0.656476  0.204873
5802  20231002    215959  28303.1  ...  56.250000  0.682890  0.191489
5803  20231002    222959  28540.0  ...  56.250000  0.631602  0.192465
5804  20231002    225959  28287.9  ...  56.666667  0.632796  0.193009
5805  20231002    232959  28292.4  ...  56.666667  0.641215  0.190914

[5 rows x 33 columns]
0.5441176470588235
acc is : 0.5441176470588235
2023-10-03 00:00:17,859:INFO:logic:main.py:468:getModel:2218526: df_pred.iloc[-5:,:] :
     pred    prob_0    prob_1  actual  ...       nav  sign   cost_        bm
539     1  0.488738  0.511262       1  ...  0.949928  -1.0  0.0000  1.056063
540     0  0.556158  0.443842       0  ...  0.941497   1.0 -0.0016  1.048379
541     1  0.444188  0.555812       1  ...  0.939698  -1.0 -0.0016  1.048706
542     1  0.495666  0.504334       1  ...  0.937625  -1.0  0.0000  1.051019
543     0  0.512853  0.487147       0  ...  0.948431  -1.0  0.0000  1.038905

[5 rows x 10 columns]
2023-10-03 00:00:17,870:INFO:logic:main.py:478:getModel:2218526: df_panel.iloc[-5:,:] :
    pred    prob_0    prob_1  actual  ...       nav  sign   cost_        bm
45     1  0.488927  0.511073       1  ...  0.949928  -1.0  0.0000  1.055226
46     0  0.556090  0.443910       0  ...  0.941497   1.0 -0.0016  1.045199
47     1  0.444295  0.555705       1  ...  0.939698  -1.0 -0.0016  1.047145
48     1  0.495793  0.504207       1  ...  0.937625  -1.0  0.0000  1.049455
49     0  0.512853  0.487147       0  ...  0.948431  -1.0  0.0000  1.038905

[5 rows x 10 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '23.906', 'enterprice': '28298.9', 'countrevence': '0', 'unrealprofit': '7221.5718700591', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '27996.81801765', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}


## /root/FIL/strategy/modifiedmom/log.txt ----- -----


--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=20375 

self.closeSec=1696260599, self.tradeDate='20231002', self.openTime='232000', self.closeTime='232959', self.symbol='BTCUSDT', self.open='28250', self.close='28354.8'
127.0.0.1 - - [02/Oct/2023 23:30:01] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [02/Oct/2023 23:40:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=20376 

self.closeSec=1696261199, self.tradeDate='20231002', self.openTime='233000', self.closeTime='233959', self.symbol='BTCUSDT', self.open='28350.8', self.close='28317.8'
127.0.0.1 - - [02/Oct/2023 23:50:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=20377 

self.closeSec=1696261799, self.tradeDate='20231002', self.openTime='234000', self.closeTime='234959', self.symbol='BTCUSDT', self.open='28317.8', self.close='28077.2'
127.0.0.1 - - [03/Oct/2023 00:00:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=20378 

self.closeSec=1696262399, self.tradeDate='20231002', self.openTime='235000', self.closeTime='235959', self.symbol='BTCUSDT', self.open='28074', self.close='28028'

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=20379 

self.closeSec=1696262999, self.tradeDate='20231003', self.openTime='000000', self.closeTime='000959', self.symbol='BTCUSDT', self.open='28015', self.close='27947.5'
127.0.0.1 - - [03/Oct/2023 00:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=20380 

self.closeSec=1696263599, self.tradeDate='20231003', self.openTime='001000', self.closeTime='001959', self.symbol='BTCUSDT', self.open='27949.3', self.close='28084.3'
127.0.0.1 - - [03/Oct/2023 00:20:04] "POST / HTTP/1.1" 200 -


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


--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=20378 

self.closeSec=1696260599, self.tradeDate='20231002', self.openTime='232000', self.closeTime='232959', self.symbol='BTCUSDT', self.open='28250', self.close='28354.8'
127.0.0.1 - - [02/Oct/2023 23:30:01] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [02/Oct/2023 23:40:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=20379 

self.closeSec=1696261199, self.tradeDate='20231002', self.openTime='233000', self.closeTime='233959', self.symbol='BTCUSDT', self.open='28350.8', self.close='28317.8'

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=20380 

self.closeSec=1696261799, self.tradeDate='20231002', self.openTime='234000', self.closeTime='234959', self.symbol='BTCUSDT', self.open='28317.8', self.close='28077.2'
127.0.0.1 - - [02/Oct/2023 23:50:01] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [03/Oct/2023 00:00:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=20381 

self.closeSec=1696262399, self.tradeDate='20231002', self.openTime='235000', self.closeTime='235959', self.symbol='BTCUSDT', self.open='28074', self.close='28028'

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=20382 

self.closeSec=1696262999, self.tradeDate='20231003', self.openTime='000000', self.closeTime='000959', self.symbol='BTCUSDT', self.open='28015', self.close='27947.5'
127.0.0.1 - - [03/Oct/2023 00:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=20383 

self.closeSec=1696263599, self.tradeDate='20231003', self.openTime='001000', self.closeTime='001959', self.symbol='BTCUSDT', self.open='27949.3', self.close='28084.3'
127.0.0.1 - - [03/Oct/2023 00:20:04] "POST / HTTP/1.1" 200 -


## /root/FIL/strategy/similarity/log.txt ----- -----


--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=20378 

self.closeSec=1696260599, self.tradeDate='20231002', self.openTime='232000', self.closeTime='232959', self.symbol='BTCUSDT', self.open='28250', self.close='28354.8'
127.0.0.1 - - [02/Oct/2023 23:30:01] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [02/Oct/2023 23:40:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=20379 

self.closeSec=1696261199, self.tradeDate='20231002', self.openTime='233000', self.closeTime='233959', self.symbol='BTCUSDT', self.open='28350.8', self.close='28317.8'
127.0.0.1 - - [02/Oct/2023 23:50:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=20380 

self.closeSec=1696261799, self.tradeDate='20231002', self.openTime='234000', self.closeTime='234959', self.symbol='BTCUSDT', self.open='28317.8', self.close='28077.2'
127.0.0.1 - - [03/Oct/2023 00:00:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=20381 

self.closeSec=1696262399, self.tradeDate='20231002', self.openTime='235000', self.closeTime='235959', self.symbol='BTCUSDT', self.open='28074', self.close='28028'
127.0.0.1 - - [03/Oct/2023 00:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=20382 

self.closeSec=1696262999, self.tradeDate='20231003', self.openTime='000000', self.closeTime='000959', self.symbol='BTCUSDT', self.open='28015', self.close='27947.5'

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=20383 

self.closeSec=1696263599, self.tradeDate='20231003', self.openTime='001000', self.closeTime='001959', self.symbol='BTCUSDT', self.open='27949.3', self.close='28084.3'
127.0.0.1 - - [03/Oct/2023 00:20:04] "POST / HTTP/1.1" 200 -


## /root/FIL/strategy/sr_min/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=1, self.total=996015.990996, self.flagDict['side']='buy', self.tradeCount=1, self.count=40756
self.closeSec=1696263599, self.tradeDate='20231003', self.openTime='001500', self.closeTime='001959', self.symbol='BTCUSDT', self.open=28048.8, self.close=28084.3, self.high=28098.9, self.low=28017.4, self.vol=6301.841, self.amt=176878673.5985 
127.0.0.1 - - [03/Oct/2023 00:20:02] "POST / HTTP/1.1" 200 -
2023-10-03 00:20:06,092:INFO:sr_min:main.py:172:handleKline:2219263: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5759  20231002   235500    235959  ...         0.0        0.0       0
5760  20231003   000000    000459  ...         0.0        0.0       0
5761  20231003   000500    000959  ...         0.0        0.0       0
5762  20231003   001000    001459  ...         0.0        0.0       0
5763  20231003   001500    001959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-10-03 00:20:06,096:INFO:sr_min:main.py:175:handleKline:2219263: self.closeSec=1696263599, self.tradeDate='20231003', self.openTime='001500', self.closeTime='001959',self.symbol='BTCUSDT',self.open=28048.8, self.close=28084.3, self.high=28098.9, self.low=28017.4, self.vol=6301.841, self.amt=176878673.5985, ukdf['pct'].iloc[-1]=0.001109 , ukdf['amount'].iloc[-1]=176878673.5985, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5763, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '37.141', 'enterprice': '26844', 'countrevence': '0', 'unrealprofit': '46011.2554004818', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '28082.8265098', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=1
--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=1, self.total=996015.990996, self.flagDict['side']='buy', self.tradeCount=1, self.count=40757
self.closeSec=1696263899, self.tradeDate='20231003', self.openTime='002000', self.closeTime='002459', self.symbol='BTCUSDT', self.open=28085.4, self.close=28072.3, self.high=28111.0, self.low=28045.3, self.vol=3089.764, self.amt=86772407.6628 
127.0.0.1 - - [03/Oct/2023 00:25:00] "POST / HTTP/1.1" 200 -
2023-10-03 00:25:00,830:INFO:sr_min:main.py:172:handleKline:2219263: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5760  20231003   000000    000459  ...         0.0        0.0       0
5761  20231003   000500    000959  ...         0.0        0.0       0
5762  20231003   001000    001459  ...         0.0        0.0       0
5763  20231003   001500    001959  ...         0.0        0.0       0
5764  20231003   002000    002459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-10-03 00:25:00,830:INFO:sr_min:main.py:175:handleKline:2219263: self.closeSec=1696263899, self.tradeDate='20231003', self.openTime='002000', self.closeTime='002459',self.symbol='BTCUSDT',self.open=28085.4, self.close=28072.3, self.high=28111.0, self.low=28045.3, self.vol=3089.764, self.amt=86772407.6628, ukdf['pct'].iloc[-1]=-0.000427 , ukdf['amount'].iloc[-1]=86772407.6628, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5764, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '37.141', 'enterprice': '26844', 'countrevence': '0', 'unrealprofit': '45650.0031', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '28073.1', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=1


## /root/FIL/strategy/s_rsrs/log.txt ----- -----

722  20231002   080000    115959  ...   63778.333  1.784399e+09  0.004953
723  20231002   120000    155959  ...   82485.833  2.322852e+09  0.006401
724  20231002   160000    195959  ...   85552.741  2.421877e+09 -0.004131
725  20231002   200000    235959  ...  142170.052  4.021523e+09 -0.005503

[5 rows x 11 columns]
2023-10-03 00:00:02,242:INFO:s_rsrs:main.py:151:handleKline:2218689: df_s.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec  ...  index      beta    zscore  signal
721  20231002   040000    075959  1696204799  ...    721  0.458085 -0.444898     NaN
722  20231002   080000    115959  1696219199  ...    722  0.607722 -0.090302     NaN
723  20231002   120000    155959  1696233599  ...    723  0.815649  0.396154     NaN
724  20231002   160000    195959  1696247999  ...    724  0.807842  0.363571     NaN
725  20231002   200000    235959  1696262399  ...    725  0.947660  0.684216     1.0

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '46.874', 'enterprice': '27094.9', 'countrevence': '0', 'unrealprofit': '-43221.58747854608', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '28016.98020392', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=1, self.sign=-1
handlebackTrade > queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '46.874', 'enterprice': '27094.9', 'countrevence': '0', 'unrealprofit': '-43221.58747854608', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '28016.98020392', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
2023-10-03 00:00:09,042:INFO:s_rsrs:main.py:182:queryContractAssets:2218689: queryContractAssets: assets=ContractAssetReturn{'result': [ContractAsset{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'asset': 'USDT', 'free': '1229416.4214884', 'total': '1229416.4214884', 'margin': '0', 'unreal': '0', 'type': 'AssetType_ucontract'}]}
2023-10-03 00:00:09,521:DEBUG:s_rsrs:main.py:253:openBuy:2218689: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': True, 'isCloseBuy': False, 'isCloseSell': False, 'isOpen': True, 'isClose': False, 'isTrig': False}
2023-10-03 00:00:09,521:INFO:s_rsrs:main.py:254:openBuy:2218689: ret = self.client.insertMarketUOrder("simulator", "BTCUSDT", 43.732, "buy"), ret=InsertOrderReturn{'result': 'success', 'clientorderid': '42984F1696262409519I0L65'}
2023-10-03 00:00:09,538:INFO:s_rsrs:main.py:176:insertFactor:2218689: curDateTime:10030000, name:s_rsrs, symbol:BTCUSDT, tradeDate:20231002, closeTime:235959, close:28028.0, sign:1, total:1229416.4214884, side:buy  
127.0.0.1 - - [03/Oct/2023 00:00:09] "POST / HTTP/1.1" 200 -
2023-10-03 00:00:09,541:INFO:s_rsrs:main.py:343:handleOrderNew:2218689: handleOrderNew: data=OrderType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'clientorderid': '42983F1696262403962I0L65', 'symbol': 'BTCUSDT', 'gatewayorderid': 1696262404363620, 'quantity': '46.874', 'price': '28012.7', 'stopprice': '0', 'ordertype': '', 'side': 'BUY', 'status': 'FILLED', 'positionside': 'LONG', 'createtime': 1696262403070, 'updatetime': 1696262404363, 'tradetype': 'usdt', 'selfid': 42983, 'filltrades': [TradeType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'tradeid': 1696262404363, 'clientorderid': '42983F1696262403962I0L65', 'price': '28012.7', 'quantity': '46.874', 'commission': '1313.0672998', 'commissionasset': 'USDT', 'tradetime': 1696262404363, 'tradetype': 'usdt', 'gatetype': 'simulator', 'handletime': 1696262404363}], 'gatetype': 'simulator', 'handletime': 0}
2023-10-03 00:00:09,542:INFO:s_rsrs:main.py:346:handleOrderFilled:2218689: handleOrderFilled: data=OrderType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'clientorderid': '42983F1696262403962I0L65', 'symbol': 'BTCUSDT', 'gatewayorderid': 1696262404363620, 'quantity': '46.874', 'price': '28012.7', 'stopprice': '0', 'ordertype': '', 'side': 'BUY', 'status': 'FILLED', 'positionside': 'LONG', 'createtime': 1696262403070, 'updatetime': 1696262404363, 'tradetype': 'usdt', 'selfid': 42983, 'filltrades': [TradeType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'tradeid': 1696262404363, 'clientorderid': '42983F1696262403962I0L65', 'price': '28012.7', 'quantity': '46.874', 'commission': '1313.0672998', 'commissionasset': 'USDT', 'tradetime': 1696262404363, 'tradetype': 'usdt', 'gatetype': 'simulator', 'handletime': 1696262404363}], 'gatetype': 'simulator', 'handletime': 0}
127.0.0.1 - - [03/Oct/2023 00:00:09] "POST / HTTP/1.1" 200 -
2023-10-03 00:00:09,998:INFO:s_rsrs:main.py:343:handleOrderNew:2218689: handleOrderNew: data=OrderType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'clientorderid': '42984F1696262409519I0L65', 'symbol': 'BTCUSDT', 'gatewayorderid': 1696262409969355, 'quantity': '43.732', 'price': '28015.5', 'stopprice': '0', 'ordertype': '', 'side': 'BUY', 'status': 'FILLED', 'positionside': 'LONG', 'createtime': 1696262409057, 'updatetime': 1696262409969, 'tradetype': 'usdt', 'selfid': 42984, 'filltrades': [TradeType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'tradeid': 1696262409969, 'clientorderid': '42984F1696262409519I0L65', 'price': '28015.5', 'quantity': '43.732', 'commission': '1225.173846', 'commissionasset': 'USDT', 'tradetime': 1696262409969, 'tradetype': 'usdt', 'gatetype': 'simulator', 'handletime': 1696262409969}], 'gatetype': 'simulator', 'handletime': 0}
127.0.0.1 - - [03/Oct/2023 00:00:09] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [03/Oct/2023 00:00:10] "POST / HTTP/1.1" 200 -
2023-10-03 00:00:10,151:INFO:s_rsrs:main.py:346:handleOrderFilled:2218689: handleOrderFilled: data=OrderType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'clientorderid': '42984F1696262409519I0L65', 'symbol': 'BTCUSDT', 'gatewayorderid': 1696262409969355, 'quantity': '43.732', 'price': '28015.5', 'stopprice': '0', 'ordertype': '', 'side': 'BUY', 'status': 'FILLED', 'positionside': 'LONG', 'createtime': 1696262409057, 'updatetime': 1696262409969, 'tradetype': 'usdt', 'selfid': 42984, 'filltrades': [TradeType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'tradeid': 1696262409969, 'clientorderid': '42984F1696262409519I0L65', 'price': '28015.5', 'quantity': '43.732', 'commission': '1225.173846', 'commissionasset': 'USDT', 'tradetime': 1696262409969, 'tradetype': 'usdt', 'gatetype': 'simulator', 'handletime': 1696262409969}], 'gatetype': 'simulator', 'handletime': 0}


