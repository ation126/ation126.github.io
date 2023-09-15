# 20230916 00:26:01

## /root/FIL/strategy/amihud/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=373746.4768026, self.flagDict['side']='sell', self.tradeCount=2, self.count=35860
self.closeSec=1694794799, self.tradeDate='20230916', self.openTime='001500', self.closeTime='001959', self.symbol='BTCUSDT', self.open=26339.9, self.close=26336.3, self.high=26339.9, self.low=26318.9, self.vol=498.195, self.amt=13116119.7201 
127.0.0.1 - - [16/Sep/2023 00:20:02] "POST / HTTP/1.1" 200 -
2023-09-16 00:20:06,386:INFO:amihud:main.py:172:handleKline:2219019: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5759  20230915   235500    235959  ...         0.0        0.0       0
5760  20230916   000000    000459  ...         0.0        0.0       0
5761  20230916   000500    000959  ...         0.0        0.0       0
5762  20230916   001000    001459  ...         0.0        0.0       0
5763  20230916   001500    001959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-09-16 00:20:06,392:INFO:amihud:main.py:175:handleKline:2219019: self.closeSec=1694794799, self.tradeDate='20230916', self.openTime='001500', self.closeTime='001959',self.symbol='BTCUSDT',self.open=26339.9, self.close=26336.3, self.high=26339.9, self.low=26318.9, self.vol=498.195, self.amt=13116119.7201, ukdf['pct'].iloc[-1]=-0.000137 , ukdf['amount'].iloc[-1]=13116119.7201, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5763, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '13.926', 'enterprice': '26864.9', 'countrevence': '0', 'unrealprofit': '7297.224', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '26340.9', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1
127.0.0.1 - - [16/Sep/2023 00:25:00] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=373746.4768026, self.flagDict['side']='sell', self.tradeCount=2, self.count=35861
self.closeSec=1694795099, self.tradeDate='20230916', self.openTime='002000', self.closeTime='002459', self.symbol='BTCUSDT', self.open=26336.4, self.close=26354.2, self.high=26356.8, self.low=26331.9, self.vol=882.608, self.amt=23253188.3785 
2023-09-16 00:25:00,835:INFO:amihud:main.py:172:handleKline:2219019: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5760  20230916   000000    000459  ...         0.0        0.0       0
5761  20230916   000500    000959  ...         0.0        0.0       0
5762  20230916   001000    001459  ...         0.0        0.0       0
5763  20230916   001500    001959  ...         0.0        0.0       0
5764  20230916   002000    002459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-09-16 00:25:00,835:INFO:amihud:main.py:175:handleKline:2219019: self.closeSec=1694795099, self.tradeDate='20230916', self.openTime='002000', self.closeTime='002459',self.symbol='BTCUSDT',self.open=26336.4, self.close=26354.2, self.high=26356.8, self.low=26331.9, self.vol=882.608, self.amt=23253188.3785, ukdf['pct'].iloc[-1]=0.00068 , ukdf['amount'].iloc[-1]=23253188.3785, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5764, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '13.926', 'enterprice': '26864.9', 'countrevence': '0', 'unrealprofit': '7099.4748', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '26355.1', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1


## /root/FIL/strategy/factorcheck/log.txt ----- -----

self.closeSec=1694793899, self.tradeDate='20230916', self.openTime='000000', self.closeTime='000459', self.symbol='BTCUSDT', self.open=26311.1, self.close=26320.0, self.high=26321.5, self.low=26303.0 

--ukdf-hist--: overDate='20230911' 
 Empty DataFrame
Columns: [tradeDate, openTime, closeTime, closeSec, open, close, high, low, pct, index, idx]
Index: [] 
 Empty DataFrame
Columns: [tradeDate, openTime, closeTime, closeSec, open, close, high, low, pct, index, idx]
Index: [] 

127.0.0.1 - - [16/Sep/2023 00:10:00] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.714181719035411, self.count=35860 

self.closeSec=1694794199, self.tradeDate='20230916', self.openTime='000500', self.closeTime='000959', self.symbol='BTCUSDT', self.open=26320.0, self.close=26317.1, self.high=26344.8, self.low=26317.1 

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.714181719035411, self.count=35861 

self.closeSec=1694794499, self.tradeDate='20230916', self.openTime='001000', self.closeTime='001459', self.symbol='BTCUSDT', self.open=26316.8, self.close=26339.9, self.high=26345.0, self.low=26315.5 
127.0.0.1 - - [16/Sep/2023 00:15:00] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.714181719035411, self.count=35862 

self.closeSec=1694794799, self.tradeDate='20230916', self.openTime='001500', self.closeTime='001959', self.symbol='BTCUSDT', self.open=26339.9, self.close=26336.3, self.high=26339.9, self.low=26318.9 
127.0.0.1 - - [16/Sep/2023 00:20:02] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [16/Sep/2023 00:25:00] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.714181719035411, self.count=35863 

self.closeSec=1694795099, self.tradeDate='20230916', self.openTime='002000', self.closeTime='002459', self.symbol='BTCUSDT', self.open=26336.4, self.close=26354.2, self.high=26356.8, self.low=26331.9 


## /root/FIL/strategy/logic/log.txt ----- -----

2023-09-16 00:00:19,041:DEBUG:logic:main.py:463:getModel:2218526: df_s.iloc[-5:,:] :
          date closeTime     open  ...    alpha58   alpha67   alpha72
5801  20230915    212959  26352.5  ...  49.583333  0.500937  0.613584
5802  20230915    215959  26398.0  ...  49.166667  0.490753  0.635655
5803  20230915    222959  26351.9  ...  49.583333  0.492363  0.655397
5804  20230915    225959  26358.2  ...  49.583333  0.465090  0.675646
5805  20230915    232959  26227.0  ...  50.000000  0.474796  0.688914

[5 rows x 33 columns]
0.5569852941176471
acc is : 0.5569852941176471
2023-09-16 00:00:19,109:INFO:logic:main.py:468:getModel:2218526: df_pred.iloc[-5:,:] :
     pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
539     1  0.495005  0.504995       0  ...  0.937237   1.0    0.0  1.015304
540     1  0.474711  0.525289       1  ...  0.937493   1.0    0.0  1.015582
541     1  0.492583  0.507417       0  ...  0.932837   1.0    0.0  1.010538
542     1  0.451026  0.548974       1  ...  0.934359   1.0    0.0  1.012187
543     1  0.498922  0.501078       1  ...  0.935817   1.0    0.0  1.013767

[5 rows x 10 columns]
2023-09-16 00:00:19,121:INFO:logic:main.py:478:getModel:2218526: df_panel.iloc[-5:,:] :
    pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
45     1  0.494672  0.505328       0  ...  0.937237   1.0    0.0  1.014530
46     1  0.475152  0.524848       1  ...  0.937493   1.0    0.0  1.015640
47     1  0.492315  0.507685       0  ...  0.932837   1.0    0.0  1.009826
48     1  0.451236  0.548764       1  ...  0.934359   1.0    0.0  1.011474
49     1  0.498922  0.501078       1  ...  0.935817   1.0    0.0  1.013767

[5 rows x 10 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '26.865', 'enterprice': '26592', 'countrevence': '0', 'unrealprofit': '-7712.67486729285', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '26304.90992491', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}


## /root/FIL/strategy/modifiedmom/log.txt ----- -----


--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=17927 

self.closeSec=1694791799, self.tradeDate='20230915', self.openTime='232000', self.closeTime='232959', self.symbol='BTCUSDT', self.open='26268.6', self.close='26270.1'
127.0.0.1 - - [15/Sep/2023 23:30:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=17928 

self.closeSec=1694792399, self.tradeDate='20230915', self.openTime='233000', self.closeTime='233959', self.symbol='BTCUSDT', self.open='26270.1', self.close='26311.4'
127.0.0.1 - - [15/Sep/2023 23:40:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=17929 

self.closeSec=1694792999, self.tradeDate='20230915', self.openTime='234000', self.closeTime='234959', self.symbol='BTCUSDT', self.open='26311.9', self.close='26314'
127.0.0.1 - - [15/Sep/2023 23:50:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=17930 

self.closeSec=1694793599, self.tradeDate='20230915', self.openTime='235000', self.closeTime='235959', self.symbol='BTCUSDT', self.open='26313.9', self.close='26311.1'
127.0.0.1 - - [16/Sep/2023 00:00:01] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [16/Sep/2023 00:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=17931 

self.closeSec=1694794199, self.tradeDate='20230916', self.openTime='000000', self.closeTime='000959', self.symbol='BTCUSDT', self.open='26311.1', self.close='26317.1'

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=17932 

self.closeSec=1694794799, self.tradeDate='20230916', self.openTime='001000', self.closeTime='001959', self.symbol='BTCUSDT', self.open='26316.8', self.close='26336.3'
127.0.0.1 - - [16/Sep/2023 00:20:05] "POST / HTTP/1.1" 200 -


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


--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=17930 

self.closeSec=1694791799, self.tradeDate='20230915', self.openTime='232000', self.closeTime='232959', self.symbol='BTCUSDT', self.open='26268.6', self.close='26270.1'
127.0.0.1 - - [15/Sep/2023 23:30:01] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [15/Sep/2023 23:40:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=17931 

self.closeSec=1694792399, self.tradeDate='20230915', self.openTime='233000', self.closeTime='233959', self.symbol='BTCUSDT', self.open='26270.1', self.close='26311.4'
127.0.0.1 - - [15/Sep/2023 23:50:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=17932 

self.closeSec=1694792999, self.tradeDate='20230915', self.openTime='234000', self.closeTime='234959', self.symbol='BTCUSDT', self.open='26311.9', self.close='26314'

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=17933 

self.closeSec=1694793599, self.tradeDate='20230915', self.openTime='235000', self.closeTime='235959', self.symbol='BTCUSDT', self.open='26313.9', self.close='26311.1'
127.0.0.1 - - [16/Sep/2023 00:00:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=17934 

self.closeSec=1694794199, self.tradeDate='20230916', self.openTime='000000', self.closeTime='000959', self.symbol='BTCUSDT', self.open='26311.1', self.close='26317.1'
127.0.0.1 - - [16/Sep/2023 00:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=17935 

self.closeSec=1694794799, self.tradeDate='20230916', self.openTime='001000', self.closeTime='001959', self.symbol='BTCUSDT', self.open='26316.8', self.close='26336.3'
127.0.0.1 - - [16/Sep/2023 00:20:05] "POST / HTTP/1.1" 200 -


## /root/FIL/strategy/similarity/log.txt ----- -----

127.0.0.1 - - [15/Sep/2023 23:30:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=17930 

self.closeSec=1694791799, self.tradeDate='20230915', self.openTime='232000', self.closeTime='232959', self.symbol='BTCUSDT', self.open='26268.6', self.close='26270.1'

--handleKline--: 127.0.0.1 - - [15/Sep/2023 23:40:01] "POST / HTTP/1.1" 200 -
 self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=17931 

self.closeSec=1694792399, self.tradeDate='20230915', self.openTime='233000', self.closeTime='233959', self.symbol='BTCUSDT', self.open='26270.1', self.close='26311.4'

--handleKline--: 127.0.0.1 - - [15/Sep/2023 23:50:01] "POST / HTTP/1.1" 200 -
 self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=17932 

self.closeSec=1694792999, self.tradeDate='20230915', self.openTime='234000', self.closeTime='234959', self.symbol='BTCUSDT', self.open='26311.9', self.close='26314'

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=17933 

self.closeSec=1694793599, self.tradeDate='20230915', self.openTime='235000', self.closeTime='235959', self.symbol='BTCUSDT', self.open='26313.9', self.close='26311.1'
127.0.0.1 - - [16/Sep/2023 00:00:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=17934 

self.closeSec=1694794199, self.tradeDate='20230916', self.openTime='000000', self.closeTime='000959', self.symbol='BTCUSDT', self.open='26311.1', self.close='26317.1'
127.0.0.1 - - [16/Sep/2023 00:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=17935 

self.closeSec=1694794799, self.tradeDate='20230916', self.openTime='001000', self.closeTime='001959', self.symbol='BTCUSDT', self.open='26316.8', self.close='26336.3'
127.0.0.1 - - [16/Sep/2023 00:20:05] "POST / HTTP/1.1" 200 -


## /root/FIL/strategy/sr_min/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=1, self.total=996015.990996, self.flagDict['side']='buy', self.tradeCount=1, self.count=35860
self.closeSec=1694794799, self.tradeDate='20230916', self.openTime='001500', self.closeTime='001959', self.symbol='BTCUSDT', self.open=26339.9, self.close=26336.3, self.high=26339.9, self.low=26318.9, self.vol=498.195, self.amt=13116119.7201 
127.0.0.1 - - [16/Sep/2023 00:20:02] "POST / HTTP/1.1" 200 -
2023-09-16 00:20:06,387:INFO:sr_min:main.py:172:handleKline:2219263: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5759  20230915   235500    235959  ...         0.0        0.0       0
5760  20230916   000000    000459  ...         0.0        0.0       0
5761  20230916   000500    000959  ...         0.0        0.0       0
5762  20230916   001000    001459  ...         0.0        0.0       0
5763  20230916   001500    001959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-09-16 00:20:06,393:INFO:sr_min:main.py:175:handleKline:2219263: self.closeSec=1694794799, self.tradeDate='20230916', self.openTime='001500', self.closeTime='001959',self.symbol='BTCUSDT',self.open=26339.9, self.close=26336.3, self.high=26339.9, self.low=26318.9, self.vol=498.195, self.amt=13116119.7201, ukdf['pct'].iloc[-1]=-0.000137 , ukdf['amount'].iloc[-1]=13116119.7201, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5763, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '37.141', 'enterprice': '26844', 'countrevence': '0', 'unrealprofit': '-18685.6371', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '26340.9', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=1
--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=1, self.total=996015.990996, self.flagDict['side']='buy', self.tradeCount=1, self.count=35861
self.closeSec=1694795099, self.tradeDate='20230916', self.openTime='002000', self.closeTime='002459', self.symbol='BTCUSDT', self.open=26336.4, self.close=26354.2, self.high=26356.8, self.low=26331.9, self.vol=882.608, self.amt=23253188.3785 
127.0.0.1 - - [16/Sep/2023 00:25:00] "POST / HTTP/1.1" 200 -
2023-09-16 00:25:00,840:INFO:sr_min:main.py:172:handleKline:2219263: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5760  20230916   000000    000459  ...         0.0        0.0       0
5761  20230916   000500    000959  ...         0.0        0.0       0
5762  20230916   001000    001459  ...         0.0        0.0       0
5763  20230916   001500    001959  ...         0.0        0.0       0
5764  20230916   002000    002459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-09-16 00:25:00,840:INFO:sr_min:main.py:175:handleKline:2219263: self.closeSec=1694795099, self.tradeDate='20230916', self.openTime='002000', self.closeTime='002459',self.symbol='BTCUSDT',self.open=26336.4, self.close=26354.2, self.high=26356.8, self.low=26331.9, self.vol=882.608, self.amt=23253188.3785, ukdf['pct'].iloc[-1]=0.00068 , ukdf['amount'].iloc[-1]=23253188.3785, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5764, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '37.141', 'enterprice': '26844', 'countrevence': '0', 'unrealprofit': '-18158.2349', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '26355.1', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=1


## /root/FIL/strategy/s_rsrs/log.txt ----- -----

723  20230915   120000    155959  1694764799  ...    723  0.556396  0.737129     1.0
724  20230915   160000    195959  1694779199  ...    724  0.562301  0.782005     1.0

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '53.725', 'enterprice': '26678.4', 'countrevence': '0', 'unrealprofit': '-15038.5803805685', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '26398.48226374', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=1, self.sign=1
--handleKline--:  version='2.0.0', self.name='s_rsrs', self.symbol='BTCUSDT', interval='4h', intervalSec=14400, wid=25, thd=0.6, self.sign=1, self.total=1431863.74296, self.flagDict['side']='buy', self.tradeCount=23, self.count=747
self.closeSec=1694793599, self.tradeDate='20230915', self.openTime='200000', self.closeTime='235959', self.symbol='BTCUSDT', self.open=26415.3, self.close=26311.1, self.high=26520.0, self.low=26206.6, self.vol=69223.358, self.amt=1824085083.92734 
127.0.0.1 - - [16/Sep/2023 00:00:01] "POST / HTTP/1.1" 200 -
2023-09-16 00:00:01,572:INFO:s_rsrs:main.py:141:handleKline:2218689: self.closeSec=1694793599, self.tradeDate='20230915', self.openTime='200000', self.closeTime='235959',self.symbol='BTCUSDT',self.open=26415.3, self.close=26311.1, self.high=26520.0, self.low=26206.6, self.vol=69223.358, self.amt=1824085083.92734 
2023-09-16 00:00:01,586:INFO:s_rsrs:main.py:142:handleKline:2218689: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime  ...        vol           amt       pct
721  20230915   040000    075959  ...  30652.131  8.142160e+08 -0.005690
722  20230915   080000    115959  ...  27708.163  7.349778e+08  0.003485
723  20230915   120000    155959  ...  20708.984  5.506231e+08 -0.001816
724  20230915   160000    195959  ...  43585.648  1.156854e+09 -0.005272
725  20230915   200000    235959  ...  69223.358  1.824085e+09 -0.003911

[5 rows x 11 columns]
2023-09-16 00:00:02,316:INFO:s_rsrs:main.py:151:handleKline:2218689: df_s.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec  ...  index      beta    zscore  signal
721  20230915   040000    075959  1694735999  ...    721  0.598445  0.837164     1.0
722  20230915   080000    115959  1694750399  ...    722  0.586429  0.821026     1.0
723  20230915   120000    155959  1694764799  ...    723  0.556396  0.737129     1.0
724  20230915   160000    195959  1694779199  ...    724  0.562301  0.782005     1.0
725  20230915   200000    235959  1694793599  ...    725  0.548969  0.756718     1.0

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '53.725', 'enterprice': '26678.4', 'countrevence': '0', 'unrealprofit': '-19738.565', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '26311', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=1, self.sign=1


