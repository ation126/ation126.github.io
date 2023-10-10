# 20231011 00:26:02

## /root/FIL/strategy/amihud/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=373746.4768026, self.flagDict['side']='sell', self.tradeCount=2, self.count=43060
self.closeSec=1696954799, self.tradeDate='20231011', self.openTime='001500', self.closeTime='001959', self.symbol='BTCUSDT', self.open=27413.0, self.close=27418.2, self.high=27459.0, self.low=27403.6, self.vol=1716.783, self.amt=47104653.1976 
127.0.0.1 - - [11/Oct/2023 00:20:10] "POST / HTTP/1.1" 200 -
2023-10-11 00:20:17,678:INFO:amihud:main.py:172:handleKline:2219019: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5759  20231010   235500    235959  ...         0.0        0.0       0
5760  20231011   000000    000459  ...         0.0        0.0       0
5761  20231011   000500    000959  ...         0.0        0.0       0
5762  20231011   001000    001459  ...         0.0        0.0       0
5763  20231011   001500    001959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-10-11 00:20:17,681:INFO:amihud:main.py:175:handleKline:2219019: self.closeSec=1696954799, self.tradeDate='20231011', self.openTime='001500', self.closeTime='001959',self.symbol='BTCUSDT',self.open=27413.0, self.close=27418.2, self.high=27459.0, self.low=27403.6, self.vol=1716.783, self.amt=47104653.1976, ukdf['pct'].iloc[-1]=0.00019 , ukdf['amount'].iloc[-1]=47104653.1976, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5763, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '13.926', 'enterprice': '26864.9', 'countrevence': '0', 'unrealprofit': '-7741.4634', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '27420.8', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1
--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=373746.4768026, self.flagDict['side']='sell', self.tradeCount=2, self.count=43061
self.closeSec=1696955099, self.tradeDate='20231011', self.openTime='002000', self.closeTime='002459', self.symbol='BTCUSDT', self.open=27418.2, self.close=27392.4, self.high=27421.4, self.low=27321.6, self.vol=4164.14, self.amt=113895233.8267 
127.0.0.1 - - [11/Oct/2023 00:25:00] "POST / HTTP/1.1" 200 -
2023-10-11 00:25:00,844:INFO:amihud:main.py:172:handleKline:2219019: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5760  20231011   000000    000459  ...         0.0        0.0       0
5761  20231011   000500    000959  ...         0.0        0.0       0
5762  20231011   001000    001459  ...         0.0        0.0       0
5763  20231011   001500    001959  ...         0.0        0.0       0
5764  20231011   002000    002459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-10-11 00:25:00,844:INFO:amihud:main.py:175:handleKline:2219019: self.closeSec=1696955099, self.tradeDate='20231011', self.openTime='002000', self.closeTime='002459',self.symbol='BTCUSDT',self.open=27418.2, self.close=27392.4, self.high=27421.4, self.low=27321.6, self.vol=4164.14, self.amt=113895233.8267, ukdf['pct'].iloc[-1]=-0.000941 , ukdf['amount'].iloc[-1]=113895233.8267, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5764, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '13.926', 'enterprice': '26864.9', 'countrevence': '0', 'unrealprofit': '-7372.4244', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '27394.3', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1


## /root/FIL/strategy/factorcheck/log.txt ----- -----

self.closeSec=1696953899, self.tradeDate='20231011', self.openTime='000000', self.closeTime='000459', self.symbol='BTCUSDT', self.open=27395.6, self.close=27398.1, self.high=27416.9, self.low=27383.5 

--ukdf-hist--: overDate='20231006' 
 Empty DataFrame
Columns: [tradeDate, openTime, closeTime, closeSec, open, close, high, low, pct, index, idx]
Index: [] 
 Empty DataFrame
Columns: [tradeDate, openTime, closeTime, closeSec, open, close, high, low, pct, index, idx]
Index: [] 


--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.714181719035411, self.count=43060 

self.closeSec=1696954199, self.tradeDate='20231011', self.openTime='000500', self.closeTime='000959', self.symbol='BTCUSDT', self.open=27398.2, self.close=27396.1, self.high=27398.2, self.low=27359.0 
127.0.0.1 - - [11/Oct/2023 00:10:00] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [11/Oct/2023 00:15:00] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.714181719035411, self.count=43061 

self.closeSec=1696954499, self.tradeDate='20231011', self.openTime='001000', self.closeTime='001459', self.symbol='BTCUSDT', self.open=27396.0, self.close=27413.0, self.high=27418.5, self.low=27382.7 

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.714181719035411, self.count=43062 

self.closeSec=1696954799, self.tradeDate='20231011', self.openTime='001500', self.closeTime='001959', self.symbol='BTCUSDT', self.open=27413.0, self.close=27418.2, self.high=27459.0, self.low=27403.6 
127.0.0.1 - - [11/Oct/2023 00:20:09] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [11/Oct/2023 00:25:00] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.714181719035411, self.count=43063 

self.closeSec=1696955099, self.tradeDate='20231011', self.openTime='002000', self.closeTime='002459', self.symbol='BTCUSDT', self.open=27418.2, self.close=27392.4, self.high=27421.4, self.low=27321.6 


## /root/FIL/strategy/logic/log.txt ----- -----

2023-10-11 00:00:17,070:DEBUG:logic:main.py:463:getModel:2218526: df_s.iloc[-5:,:] :
          date closeTime     open  ...    alpha58   alpha67   alpha72
5801  20231010    212959  27411.9  ...  49.583333  0.430960  0.424176
5802  20231010    215959  27438.3  ...  49.583333  0.417185  0.452012
5803  20231010    222959  27384.9  ...  49.583333  0.471360  0.451399
5804  20231010    225959  27553.2  ...  49.583333  0.440073  0.470242
5805  20231010    232959  27427.0  ...  49.583333  0.432631  0.493044

[5 rows x 33 columns]
0.5588235294117647
acc is : 0.5588235294117647
2023-10-11 00:00:17,127:INFO:logic:main.py:468:getModel:2218526: df_pred.iloc[-5:,:] :
     pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
539     1  0.495830  0.504170       0  ...  0.950558  -1.0    0.0  1.007943
540     1  0.473433  0.526567       1  ...  0.944723  -1.0    0.0  1.014130
541     0  0.545967  0.454033       0  ...  0.949043  -1.0    0.0  1.009492
542     1  0.458245  0.541755       0  ...  0.950151  -1.0    0.0  1.008315
543     1  0.485168  0.514832       1  ...  0.950133  -1.0    0.0  1.008333

[5 rows x 10 columns]
2023-10-11 00:00:17,138:INFO:logic:main.py:478:getModel:2218526: df_panel.iloc[-5:,:] :
    pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
45     1  0.495931  0.504069       0  ...  0.950558  -1.0    0.0  1.016401
46     1  0.473486  0.526514       1  ...  0.944723  -1.0    0.0  1.018192
47     0  0.545897  0.454103       0  ...  0.949043  -1.0    0.0  1.014541
48     1  0.458345  0.541655       0  ...  0.950151  -1.0    0.0  1.013357
49     1  0.485168  0.514832       1  ...  0.950133  -1.0    0.0  1.008333

[5 rows x 10 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '23.618', 'enterprice': '27520.8', 'countrevence': '0', 'unrealprofit': '3023.104', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '27392.8', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}


## /root/FIL/strategy/modifiedmom/log.txt ----- -----


--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=21527 

self.closeSec=1696951799, self.tradeDate='20231010', self.openTime='232000', self.closeTime='232959', self.symbol='BTCUSDT', self.open='27433.3', self.close='27395'
127.0.0.1 - - [10/Oct/2023 23:30:01] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [10/Oct/2023 23:40:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=21528 

self.closeSec=1696952399, self.tradeDate='20231010', self.openTime='233000', self.closeTime='233959', self.symbol='BTCUSDT', self.open='27395', self.close='27375.1'
127.0.0.1 - - [10/Oct/2023 23:50:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=21529 

self.closeSec=1696952999, self.tradeDate='20231010', self.openTime='234000', self.closeTime='234959', self.symbol='BTCUSDT', self.open='27375.1', self.close='27411.4'
127.0.0.1 - - [11/Oct/2023 00:00:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=21530 

self.closeSec=1696953599, self.tradeDate='20231010', self.openTime='235000', self.closeTime='235959', self.symbol='BTCUSDT', self.open='27411.3', self.close='27395.5'

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=21531 

self.closeSec=1696954199, self.tradeDate='20231011', self.openTime='000000', self.closeTime='000959', self.symbol='BTCUSDT', self.open='27395.6', self.close='27396.1'
127.0.0.1 - - [11/Oct/2023 00:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=21532 

self.closeSec=1696954799, self.tradeDate='20231011', self.openTime='001000', self.closeTime='001959', self.symbol='BTCUSDT', self.open='27396', self.close='27418.2'
127.0.0.1 - - [11/Oct/2023 00:20:13] "POST / HTTP/1.1" 200 -


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


--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=21530 

self.closeSec=1696951799, self.tradeDate='20231010', self.openTime='232000', self.closeTime='232959', self.symbol='BTCUSDT', self.open='27433.3', self.close='27395'
127.0.0.1 - - [10/Oct/2023 23:30:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=21531 

self.closeSec=1696952399, self.tradeDate='20231010', self.openTime='233000', self.closeTime='233959', self.symbol='BTCUSDT', self.open='27395', self.close='27375.1'
127.0.0.1 - - [10/Oct/2023 23:40:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=21532 

self.closeSec=1696952999, self.tradeDate='20231010', self.openTime='234000', self.closeTime='234959', self.symbol='BTCUSDT', self.open='27375.1', self.close='27411.4'
127.0.0.1 - - [10/Oct/2023 23:50:01] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [11/Oct/2023 00:00:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=21533 

self.closeSec=1696953599, self.tradeDate='20231010', self.openTime='235000', self.closeTime='235959', self.symbol='BTCUSDT', self.open='27411.3', self.close='27395.5'
127.0.0.1 - - [11/Oct/2023 00:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=21534 

self.closeSec=1696954199, self.tradeDate='20231011', self.openTime='000000', self.closeTime='000959', self.symbol='BTCUSDT', self.open='27395.6', self.close='27396.1'

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=21535 

self.closeSec=1696954799, self.tradeDate='20231011', self.openTime='001000', self.closeTime='001959', self.symbol='BTCUSDT', self.open='27396', self.close='27418.2'
127.0.0.1 - - [11/Oct/2023 00:20:12] "POST / HTTP/1.1" 200 -


## /root/FIL/strategy/similarity/log.txt ----- -----


--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=21530 

self.closeSec=1696951799, self.tradeDate='20231010', self.openTime='232000', self.closeTime='232959', self.symbol='BTCUSDT', self.open='27433.3', self.close='27395'
127.0.0.1 - - [10/Oct/2023 23:30:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=21531 

self.closeSec=1696952399, self.tradeDate='20231010', self.openTime='233000', self.closeTime='233959', self.symbol='BTCUSDT', self.open='27395', self.close='27375.1'
127.0.0.1 - - [10/Oct/2023 23:40:01] "POST / HTTP/1.1" 200 -

--handleKline--: 127.0.0.1 - - [10/Oct/2023 23:50:01] "POST / HTTP/1.1" 200 -
 self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=21532 

self.closeSec=1696952999, self.tradeDate='20231010', self.openTime='234000', self.closeTime='234959', self.symbol='BTCUSDT', self.open='27375.1', self.close='27411.4'

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=21533 

self.closeSec=1696953599, self.tradeDate='20231010', self.openTime='235000', self.closeTime='235959', self.symbol='BTCUSDT', self.open='27411.3', self.close='27395.5'
127.0.0.1 - - [11/Oct/2023 00:00:01] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [11/Oct/2023 00:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=21534 

self.closeSec=1696954199, self.tradeDate='20231011', self.openTime='000000', self.closeTime='000959', self.symbol='BTCUSDT', self.open='27395.6', self.close='27396.1'

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=21535 

self.closeSec=1696954799, self.tradeDate='20231011', self.openTime='001000', self.closeTime='001959', self.symbol='BTCUSDT', self.open='27396', self.close='27418.2'
127.0.0.1 - - [11/Oct/2023 00:20:12] "POST / HTTP/1.1" 200 -


## /root/FIL/strategy/sr_min/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=1, self.total=996015.990996, self.flagDict['side']='buy', self.tradeCount=1, self.count=43060
self.closeSec=1696954799, self.tradeDate='20231011', self.openTime='001500', self.closeTime='001959', self.symbol='BTCUSDT', self.open=27413.0, self.close=27418.2, self.high=27459.0, self.low=27403.6, self.vol=1716.783, self.amt=47104653.1976 
127.0.0.1 - - [11/Oct/2023 00:20:10] "POST / HTTP/1.1" 200 -
2023-10-11 00:20:17,669:INFO:sr_min:main.py:172:handleKline:2219263: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5759  20231010   235500    235959  ...         0.0        0.0       0
5760  20231011   000000    000459  ...         0.0        0.0       0
5761  20231011   000500    000959  ...         0.0        0.0       0
5762  20231011   001000    001459  ...         0.0        0.0       0
5763  20231011   001500    001959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-10-11 00:20:17,679:INFO:sr_min:main.py:175:handleKline:2219263: self.closeSec=1696954799, self.tradeDate='20231011', self.openTime='001500', self.closeTime='001959',self.symbol='BTCUSDT',self.open=27413.0, self.close=27418.2, self.high=27459.0, self.low=27403.6, self.vol=1716.783, self.amt=47104653.1976, ukdf['pct'].iloc[-1]=0.00019 , ukdf['amount'].iloc[-1]=47104653.1976, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5763, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '37.141', 'enterprice': '26844', 'countrevence': '0', 'unrealprofit': '21422.9288', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '27420.8', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=1
--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=1, self.total=996015.990996, self.flagDict['side']='buy', self.tradeCount=1, self.count=43061
self.closeSec=1696955099, self.tradeDate='20231011', self.openTime='002000', self.closeTime='002459', self.symbol='BTCUSDT', self.open=27418.2, self.close=27392.4, self.high=27421.4, self.low=27321.6, self.vol=4164.14, self.amt=113895233.8267 
127.0.0.1 - - [11/Oct/2023 00:25:00] "POST / HTTP/1.1" 200 -
2023-10-11 00:25:00,853:INFO:sr_min:main.py:172:handleKline:2219263: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5760  20231011   000000    000459  ...         0.0        0.0       0
5761  20231011   000500    000959  ...         0.0        0.0       0
5762  20231011   001000    001459  ...         0.0        0.0       0
5763  20231011   001500    001959  ...         0.0        0.0       0
5764  20231011   002000    002459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-10-11 00:25:00,853:INFO:sr_min:main.py:175:handleKline:2219263: self.closeSec=1696955099, self.tradeDate='20231011', self.openTime='002000', self.closeTime='002459',self.symbol='BTCUSDT',self.open=27418.2, self.close=27392.4, self.high=27421.4, self.low=27321.6, self.vol=4164.14, self.amt=113895233.8267, ukdf['pct'].iloc[-1]=-0.000941 , ukdf['amount'].iloc[-1]=113895233.8267, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5764, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '37.141', 'enterprice': '26844', 'countrevence': '0', 'unrealprofit': '20438.6923', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '27394.3', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=1


## /root/FIL/strategy/s_rsrs/log.txt ----- -----

723  20231010   120000    155959  1696924799  ...    723  0.086998 -1.102367    -1.0
724  20231010   160000    195959  1696939199  ...    724  0.079068 -1.115294    -1.0

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '43.597', 'enterprice': '27944.4', 'countrevence': '0', 'unrealprofit': '19709.39883224062', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '27492.31846154', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-1, self.sign=-1
--handleKline--:  version='2.0.0', self.name='s_rsrs', self.symbol='BTCUSDT', interval='4h', intervalSec=14400, wid=25, thd=0.6, self.sign=-1, self.total=1217073.7147932001, self.flagDict['side']='sell', self.tradeCount=32, self.count=897
self.closeSec=1696953599, self.tradeDate='20231010', self.openTime='200000', self.closeTime='235959', self.symbol='BTCUSDT', self.open=27494.0, self.close=27395.5, self.high=27622.9, self.low=27318.2, self.vol=94338.609, self.amt=2588667423.7397 
127.0.0.1 - - [11/Oct/2023 00:00:01] "POST / HTTP/1.1" 200 -
2023-10-11 00:00:01,506:INFO:s_rsrs:main.py:141:handleKline:2218689: self.closeSec=1696953599, self.tradeDate='20231010', self.openTime='200000', self.closeTime='235959',self.symbol='BTCUSDT',self.open=27494.0, self.close=27395.5, self.high=27622.9, self.low=27318.2, self.vol=94338.609, self.amt=2588667423.7397 
2023-10-11 00:00:01,520:INFO:s_rsrs:main.py:142:handleKline:2218689: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime  ...        vol           amt       pct
721  20231010   040000    075959  ...  15212.963  4.196862e+08 -0.000837
722  20231010   080000    115959  ...  24569.399  6.778474e+08  0.001566
723  20231010   120000    155959  ...  18658.552  5.153902e+08  0.000478
724  20231010   160000    195959  ...  30888.027  8.528133e+08 -0.004950
725  20231010   200000    235959  ...  94338.609  2.588667e+09 -0.003728

[5 rows x 11 columns]
2023-10-11 00:00:02,229:INFO:s_rsrs:main.py:151:handleKline:2218689: df_s.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec  ...  index      beta    zscore  signal
721  20231010   040000    075959  1696895999  ...    721  0.134666 -0.990590    -1.0
722  20231010   080000    115959  1696910399  ...    722  0.108002 -1.054893    -1.0
723  20231010   120000    155959  1696924799  ...    723  0.086998 -1.102367    -1.0
724  20231010   160000    195959  1696939199  ...    724  0.079068 -1.115294    -1.0
725  20231010   200000    235959  1696953599  ...    725  0.099732 -1.052387    -1.0

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '43.597', 'enterprice': '27944.4', 'countrevence': '0', 'unrealprofit': '23947.8321', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '27395.1', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-1, self.sign=-1


