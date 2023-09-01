# 20230902 00:26:01

## /root/FIL/strategy/amihud/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=373746.4768026, self.flagDict['side']='sell', self.tradeCount=2, self.count=31828
self.closeSec=1693585199, self.tradeDate='20230902', self.openTime='001500', self.closeTime='001959', self.symbol='BTCUSDT', self.open=25795.7, self.close=25807.9, self.high=25809.8, self.low=25766.8, self.vol=1356.83, self.amt=34993980.1172 
127.0.0.1 - - [02/Sep/2023 00:20:01] "POST / HTTP/1.1" 200 -
2023-09-02 00:20:05,141:INFO:amihud:main.py:172:handleKline:2219019: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5747  20230901   235500    235959  ...         0.0        0.0       0
5748  20230902   000000    000459  ...         0.0        0.0       0
5749  20230902   000500    000959  ...         0.0        0.0       0
5750  20230902   001000    001459  ...         0.0        0.0       0
5751  20230902   001500    001959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-09-02 00:20:05,157:INFO:amihud:main.py:175:handleKline:2219019: self.closeSec=1693585199, self.tradeDate='20230902', self.openTime='001500', self.closeTime='001959',self.symbol='BTCUSDT',self.open=25795.7, self.close=25807.9, self.high=25809.8, self.low=25766.8, self.vol=1356.83, self.amt=34993980.1172, ukdf['pct'].iloc[-1]=0.000473 , ukdf['amount'].iloc[-1]=34993980.1172, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5751, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '13.926', 'enterprice': '26864.9', 'countrevence': '0', 'unrealprofit': '14753.2044', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '25805.5', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1
127.0.0.1 - - [02/Sep/2023 00:25:00] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=373746.4768026, self.flagDict['side']='sell', self.tradeCount=2, self.count=31829
self.closeSec=1693585499, self.tradeDate='20230902', self.openTime='002000', self.closeTime='002459', self.symbol='BTCUSDT', self.open=25808.0, self.close=25818.2, self.high=25818.2, self.low=25786.6, self.vol=852.591, self.amt=21995890.8015 
2023-09-02 00:25:00,810:INFO:amihud:main.py:172:handleKline:2219019: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5748  20230902   000000    000459  ...         0.0        0.0       0
5749  20230902   000500    000959  ...         0.0        0.0       0
5750  20230902   001000    001459  ...         0.0        0.0       0
5751  20230902   001500    001959  ...         0.0        0.0       0
5752  20230902   002000    002459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-09-02 00:25:00,810:INFO:amihud:main.py:175:handleKline:2219019: self.closeSec=1693585499, self.tradeDate='20230902', self.openTime='002000', self.closeTime='002459',self.symbol='BTCUSDT',self.open=25808.0, self.close=25818.2, self.high=25818.2, self.low=25786.6, self.vol=852.591, self.amt=21995890.8015, ukdf['pct'].iloc[-1]=0.000399 , ukdf['amount'].iloc[-1]=21995890.8015, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5752, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '13.926', 'enterprice': '26864.9', 'countrevence': '0', 'unrealprofit': '14566.596', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '25818.9', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1


## /root/FIL/strategy/factorcheck/log.txt ----- -----

127.0.0.1 - - [02/Sep/2023 00:05:00] "POST / HTTP/1.1" 200 -

--ukdf-hist--: overDate='20230828' 
 Empty DataFrame
Columns: [tradeDate, openTime, closeTime, closeSec, open, close, high, low, pct, index, idx]
Index: [] 
 Empty DataFrame
Columns: [tradeDate, openTime, closeTime, closeSec, open, close, high, low, pct, index, idx]
Index: [] 

127.0.0.1 - - [02/Sep/2023 00:10:00] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.714181719035411, self.count=31828 

self.closeSec=1693584599, self.tradeDate='20230902', self.openTime='000500', self.closeTime='000959', self.symbol='BTCUSDT', self.open=25792.6, self.close=25751.0, self.high=25811.9, self.low=25748.5 

--handleKline--: 127.0.0.1 - - [02/Sep/2023 00:15:00] "POST / HTTP/1.1" 200 -
 version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.714181719035411, self.count=31829 

self.closeSec=1693584899, self.tradeDate='20230902', self.openTime='001000', self.closeTime='001459', self.symbol='BTCUSDT', self.open=25756.2, self.close=25795.7, self.high=25801.3, self.low=25742.8 

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.714181719035411, self.count=31830 

self.closeSec=1693585199, self.tradeDate='20230902', self.openTime='001500', self.closeTime='001959', self.symbol='BTCUSDT', self.open=25795.7, self.close=25807.9, self.high=25809.8, self.low=25766.8 
127.0.0.1 - - [02/Sep/2023 00:20:01] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.714181719035411, self.count=31831 

self.closeSec=1693585499, self.tradeDate='20230902', self.openTime='002000', self.closeTime='002459', self.symbol='BTCUSDT', self.open=25808.0, self.close=25818.2, self.high=25818.2, self.low=25786.6 
127.0.0.1 - - [02/Sep/2023 00:25:00] "POST / HTTP/1.1" 200 -


## /root/FIL/strategy/logic/log.txt ----- -----

2023-09-02 00:00:17,592:DEBUG:logic:main.py:463:getModel:2218526: df_s.iloc[-5:,:] :
          date closeTime     open  ...    alpha58   alpha67   alpha72
5801  20230901    212959  26050.5  ...  44.583333  0.392030  0.723597
5802  20230901    215959  26025.8  ...  44.583333  0.385153  0.709639
5803  20230901    222959  25988.5  ...  44.166667  0.371179  0.701613
5804  20230901    225959  25905.3  ...  43.750000  0.340458  0.712897
5805  20230901    232959  25705.0  ...  43.750000  0.378926  0.703951

[5 rows x 33 columns]
0.5275735294117647
acc is : 0.5275735294117647
2023-09-02 00:00:17,656:INFO:logic:main.py:468:getModel:2218526: df_pred.iloc[-5:,:] :
     pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
539     1  0.483018  0.516982       0  ...  1.000632  -1.0    0.0  0.999024
540     1  0.477723  0.522277       0  ...  1.003766  -1.0    0.0  0.995894
541     1  0.451861  0.548139       0  ...  1.011454  -1.0    0.0  0.988267
542     1  0.398763  0.601237       1  ...  1.005729  -1.0    0.0  0.993861
543     0  0.509711  0.490289       0  ...  1.007842  -1.0    0.0  0.991773

[5 rows x 10 columns]
2023-09-02 00:00:17,667:INFO:logic:main.py:478:getModel:2218526: df_panel.iloc[-5:,:] :
    pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
45     1  0.482648  0.517352       0  ...  1.000632  -1.0    0.0  0.996010
46     1  0.477413  0.522587       0  ...  1.003766  -1.0    0.0  0.995515
47     1  0.452150  0.547850       0  ...  1.011454  -1.0    0.0  0.989100
48     1  0.399125  0.600875       1  ...  1.005729  -1.0    0.0  0.994698
49     0  0.509711  0.490289       0  ...  1.007842  -1.0    0.0  0.991773

[5 rows x 10 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '26.263', 'enterprice': '26682.7', 'countrevence': '0', 'unrealprofit': '23316.2914', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '25794.9', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}


## /root/FIL/strategy/modifiedmom/log.txt ----- -----


--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=15911 

self.closeSec=1693582199, self.tradeDate='20230901', self.openTime='232000', self.closeTime='232959', self.symbol='BTCUSDT', self.open='25841.1', self.close='25852.3'
127.0.0.1 - - [01/Sep/2023 23:30:01] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [01/Sep/2023 23:40:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=15912 

self.closeSec=1693582799, self.tradeDate='20230901', self.openTime='233000', self.closeTime='233959', self.symbol='BTCUSDT', self.open='25852.4', self.close='25882.8'

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=15913 

self.closeSec=1693583399, self.tradeDate='20230901', self.openTime='234000', self.closeTime='234959', self.symbol='BTCUSDT', self.open='25882.8', self.close='25818.9'
127.0.0.1 - - [01/Sep/2023 23:50:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=15914 

self.closeSec=1693583999, self.tradeDate='20230901', self.openTime='235000', self.closeTime='235959', self.symbol='BTCUSDT', self.open='25818.8', self.close='25798'
127.0.0.1 - - [02/Sep/2023 00:00:01] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [02/Sep/2023 00:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=15915 

self.closeSec=1693584599, self.tradeDate='20230902', self.openTime='000000', self.closeTime='000959', self.symbol='BTCUSDT', self.open='25798', self.close='25751'

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=15916 

self.closeSec=1693585199, self.tradeDate='20230902', self.openTime='001000', self.closeTime='001959', self.symbol='BTCUSDT', self.open='25756.2', self.close='25807.9'
127.0.0.1 - - [02/Sep/2023 00:20:04] "POST / HTTP/1.1" 200 -


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


--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=15914 

self.closeSec=1693582199, self.tradeDate='20230901', self.openTime='232000', self.closeTime='232959', self.symbol='BTCUSDT', self.open='25841.1', self.close='25852.3'
127.0.0.1 - - [01/Sep/2023 23:30:01] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [01/Sep/2023 23:40:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=15915 

self.closeSec=1693582799, self.tradeDate='20230901', self.openTime='233000', self.closeTime='233959', self.symbol='BTCUSDT', self.open='25852.4', self.close='25882.8'
127.0.0.1 - - [01/Sep/2023 23:50:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=15916 

self.closeSec=1693583399, self.tradeDate='20230901', self.openTime='234000', self.closeTime='234959', self.symbol='BTCUSDT', self.open='25882.8', self.close='25818.9'

--handleKline--:  127.0.0.1 - - [02/Sep/2023 00:00:01] "POST / HTTP/1.1" 200 -
self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=15917 

self.closeSec=1693583999, self.tradeDate='20230901', self.openTime='235000', self.closeTime='235959', self.symbol='BTCUSDT', self.open='25818.8', self.close='25798'

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=15918 

self.closeSec=1693584599, self.tradeDate='20230902', self.openTime='000000', self.closeTime='000959', self.symbol='BTCUSDT', self.open='25798', self.close='25751'
127.0.0.1 - - [02/Sep/2023 00:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=15919 

self.closeSec=1693585199, self.tradeDate='20230902', self.openTime='001000', self.closeTime='001959', self.symbol='BTCUSDT', self.open='25756.2', self.close='25807.9'
127.0.0.1 - - [02/Sep/2023 00:20:04] "POST / HTTP/1.1" 200 -


## /root/FIL/strategy/similarity/log.txt ----- -----


--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=15914 

self.closeSec=1693582199, self.tradeDate='20230901', self.openTime='232000', self.closeTime='232959', self.symbol='BTCUSDT', self.open='25841.1', self.close='25852.3'
127.0.0.1 - - [01/Sep/2023 23:30:01] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [01/Sep/2023 23:40:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=15915 

self.closeSec=1693582799, self.tradeDate='20230901', self.openTime='233000', self.closeTime='233959', self.symbol='BTCUSDT', self.open='25852.4', self.close='25882.8'
127.0.0.1 - - [01/Sep/2023 23:50:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=15916 

self.closeSec=1693583399, self.tradeDate='20230901', self.openTime='234000', self.closeTime='234959', self.symbol='BTCUSDT', self.open='25882.8', self.close='25818.9'
127.0.0.1 - - [02/Sep/2023 00:00:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=15917 

self.closeSec=1693583999, self.tradeDate='20230901', self.openTime='235000', self.closeTime='235959', self.symbol='BTCUSDT', self.open='25818.8', self.close='25798'
127.0.0.1 - - [02/Sep/2023 00:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=15918 

self.closeSec=1693584599, self.tradeDate='20230902', self.openTime='000000', self.closeTime='000959', self.symbol='BTCUSDT', self.open='25798', self.close='25751'

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=15919 

self.closeSec=1693585199, self.tradeDate='20230902', self.openTime='001000', self.closeTime='001959', self.symbol='BTCUSDT', self.open='25756.2', self.close='25807.9'
127.0.0.1 - - [02/Sep/2023 00:20:04] "POST / HTTP/1.1" 200 -


## /root/FIL/strategy/sr_min/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=1, self.total=996015.990996, self.flagDict['side']='buy', self.tradeCount=1, self.count=31828
self.closeSec=1693585199, self.tradeDate='20230902', self.openTime='001500', self.closeTime='001959', self.symbol='BTCUSDT', self.open=25795.7, self.close=25807.9, self.high=25809.8, self.low=25766.8, self.vol=1356.83, self.amt=34993980.1172 
127.0.0.1 - - [02/Sep/2023 00:20:01] "POST / HTTP/1.1" 200 -
2023-09-02 00:20:05,141:INFO:sr_min:main.py:172:handleKline:2219263: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5747  20230901   235500    235959  ...         0.0        0.0       0
5748  20230902   000000    000459  ...         0.0        0.0       0
5749  20230902   000500    000959  ...         0.0        0.0       0
5750  20230902   001000    001459  ...         0.0        0.0       0
5751  20230902   001500    001959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-09-02 00:20:05,149:INFO:sr_min:main.py:175:handleKline:2219263: self.closeSec=1693585199, self.tradeDate='20230902', self.openTime='001500', self.closeTime='001959',self.symbol='BTCUSDT',self.open=25795.7, self.close=25807.9, self.high=25809.8, self.low=25766.8, self.vol=1356.83, self.amt=34993980.1172, ukdf['pct'].iloc[-1]=0.000473 , ukdf['amount'].iloc[-1]=34993980.1172, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5751, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '37.141', 'enterprice': '26844', 'countrevence': '0', 'unrealprofit': '-38570.9285', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '25805.5', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=1
127.0.0.1 - - [02/Sep/2023 00:25:00] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=1, self.total=996015.990996, self.flagDict['side']='buy', self.tradeCount=1, self.count=31829
self.closeSec=1693585499, self.tradeDate='20230902', self.openTime='002000', self.closeTime='002459', self.symbol='BTCUSDT', self.open=25808.0, self.close=25818.2, self.high=25818.2, self.low=25786.6, self.vol=852.591, self.amt=21995890.8015 
2023-09-02 00:25:00,811:INFO:sr_min:main.py:172:handleKline:2219263: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5748  20230902   000000    000459  ...         0.0        0.0       0
5749  20230902   000500    000959  ...         0.0        0.0       0
5750  20230902   001000    001459  ...         0.0        0.0       0
5751  20230902   001500    001959  ...         0.0        0.0       0
5752  20230902   002000    002459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-09-02 00:25:00,811:INFO:sr_min:main.py:175:handleKline:2219263: self.closeSec=1693585499, self.tradeDate='20230902', self.openTime='002000', self.closeTime='002459',self.symbol='BTCUSDT',self.open=25808.0, self.close=25818.2, self.high=25818.2, self.low=25786.6, self.vol=852.591, self.amt=21995890.8015, ukdf['pct'].iloc[-1]=0.000399 , ukdf['amount'].iloc[-1]=21995890.8015, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5752, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '37.141', 'enterprice': '26844', 'countrevence': '0', 'unrealprofit': '-38073.2391', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '25818.9', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=1


## /root/FIL/strategy/s_rsrs/log.txt ----- -----

723  20230901   120000    155959  1693555199  ...    723  0.673651  1.030149     1.0
724  20230901   160000    195959  1693569599  ...    724  0.671384  1.012377     1.0

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '57.252', 'enterprice': '27833.8', 'countrevence': '0', 'unrealprofit': '-102965.7910360326', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '26035.33372745', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=1, self.sign=1
--handleKline--:  version='2.0.0', self.name='s_rsrs', self.symbol='BTCUSDT', interval='4h', intervalSec=14400, wid=25, thd=0.6, self.sign=1, self.total=1591947.1768824002, self.flagDict['side']='buy', self.tradeCount=21, self.count=663
self.closeSec=1693583999, self.tradeDate='20230901', self.openTime='200000', self.closeTime='235959', self.symbol='BTCUSDT', self.open=26033.6, self.close=25798.0, self.high=26151.6, self.low=25555.0, self.vol=118639.495, self.amt=3069677003.35544 
127.0.0.1 - - [02/Sep/2023 00:00:01] "POST / HTTP/1.1" 200 -
2023-09-02 00:00:01,585:INFO:s_rsrs:main.py:141:handleKline:2218689: self.closeSec=1693583999, self.tradeDate='20230901', self.openTime='200000', self.closeTime='235959',self.symbol='BTCUSDT',self.open=26033.6, self.close=25798.0, self.high=26151.6, self.low=25555.0, self.vol=118639.495, self.amt=3069677003.35544 
2023-09-02 00:00:01,600:INFO:s_rsrs:main.py:142:handleKline:2218689: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime  ...         vol           amt       pct
721  20230901   040000    075959  ...   90168.579  2.339531e+09 -0.008440
722  20230901   080000    115959  ...   27071.631  7.043482e+08  0.005535
723  20230901   120000    155959  ...   18796.654  4.888930e+08 -0.003694
724  20230901   160000    195959  ...   23768.858  6.180220e+08  0.002252
725  20230901   200000    235959  ...  118639.495  3.069677e+09 -0.009054

[5 rows x 11 columns]
2023-09-02 00:00:02,325:INFO:s_rsrs:main.py:151:handleKline:2218689: df_s.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec  ...  index      beta    zscore  signal
721  20230901   040000    075959  1693526399  ...    721  0.671389  1.059724     1.0
722  20230901   080000    115959  1693540799  ...    722  0.673253  1.045144     1.0
723  20230901   120000    155959  1693555199  ...    723  0.673651  1.030149     1.0
724  20230901   160000    195959  1693569599  ...    724  0.671384  1.012377     1.0
725  20230901   200000    235959  1693583999  ...    725  0.627829  0.863870     1.0

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '57.252', 'enterprice': '27833.8', 'countrevence': '0', 'unrealprofit': '-116325.7977059022', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '25801.97931765', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=1, self.sign=1


