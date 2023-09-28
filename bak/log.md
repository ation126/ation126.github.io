# 20230929 00:26:01

## /root/FIL/strategy/amihud/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=373746.4768026, self.flagDict['side']='sell', self.tradeCount=2, self.count=39604
self.closeSec=1695917999, self.tradeDate='20230929', self.openTime='001500', self.closeTime='001959', self.symbol='BTCUSDT', self.open=27064.4, self.close=27103.5, self.high=27138.7, self.low=27064.3, self.vol=3319.742, self.amt=89997085.0049 
127.0.0.1 - - [29/Sep/2023 00:20:02] "POST / HTTP/1.1" 200 -
2023-09-29 00:20:06,358:INFO:amihud:main.py:172:handleKline:2219019: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5759  20230928   235500    235959  ...         0.0        0.0       0
5760  20230929   000000    000459  ...         0.0        0.0       0
5761  20230929   000500    000959  ...         0.0        0.0       0
5762  20230929   001000    001459  ...         0.0        0.0       0
5763  20230929   001500    001959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-09-29 00:20:06,371:INFO:amihud:main.py:175:handleKline:2219019: self.closeSec=1695917999, self.tradeDate='20230929', self.openTime='001500', self.closeTime='001959',self.symbol='BTCUSDT',self.open=27064.4, self.close=27103.5, self.high=27138.7, self.low=27064.3, self.vol=3319.742, self.amt=89997085.0049, ukdf['pct'].iloc[-1]=0.001567 , ukdf['amount'].iloc[-1]=89997085.0049, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5763, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '13.926', 'enterprice': '26864.9', 'countrevence': '0', 'unrealprofit': '-3373.75907801526', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '27107.16332601', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1
127.0.0.1 - - [29/Sep/2023 00:25:00] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=373746.4768026, self.flagDict['side']='sell', self.tradeCount=2, self.count=39605
self.closeSec=1695918299, self.tradeDate='20230929', self.openTime='002000', self.closeTime='002459', self.symbol='BTCUSDT', self.open=27105.2, self.close=27162.8, self.high=27170.0, self.low=27103.5, self.vol=3474.035, self.amt=94304719.409 
2023-09-29 00:25:00,824:INFO:amihud:main.py:172:handleKline:2219019: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5760  20230929   000000    000459  ...         0.0        0.0       0
5761  20230929   000500    000959  ...         0.0        0.0       0
5762  20230929   001000    001459  ...         0.0        0.0       0
5763  20230929   001500    001959  ...         0.0        0.0       0
5764  20230929   002000    002459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-09-29 00:25:00,825:INFO:amihud:main.py:175:handleKline:2219019: self.closeSec=1695918299, self.tradeDate='20230929', self.openTime='002000', self.closeTime='002459',self.symbol='BTCUSDT',self.open=27105.2, self.close=27162.8, self.high=27170.0, self.low=27103.5, self.vol=3474.035, self.amt=94304719.409, ukdf['pct'].iloc[-1]=0.002188 , ukdf['amount'].iloc[-1]=94304719.409, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5764, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '13.926', 'enterprice': '26864.9', 'countrevence': '0', 'unrealprofit': '-4163.08496203116', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '27163.84334066', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1


## /root/FIL/strategy/factorcheck/log.txt ----- -----

self.closeSec=1695917099, self.tradeDate='20230929', self.openTime='000000', self.closeTime='000459', self.symbol='BTCUSDT', self.open=27012.3, self.close=27129.7, self.high=27146.9, self.low=27008.0 

--ukdf-hist--: overDate='20230924' 
 Empty DataFrame
Columns: [tradeDate, openTime, closeTime, closeSec, open, close, high, low, pct, index, idx]
Index: [] 
 Empty DataFrame
Columns: [tradeDate, openTime, closeTime, closeSec, open, close, high, low, pct, index, idx]
Index: [] 

127.0.0.1 - - [29/Sep/2023 00:10:00] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.714181719035411, self.count=39604 

self.closeSec=1695917399, self.tradeDate='20230929', self.openTime='000500', self.closeTime='000959', self.symbol='BTCUSDT', self.open=27131.2, self.close=27056.1, self.high=27200.0, self.low=27036.0 

--handleKline--:  127.0.0.1 - - [29/Sep/2023 00:15:00] "POST / HTTP/1.1" 200 -
version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.714181719035411, self.count=39605 

self.closeSec=1695917699, self.tradeDate='20230929', self.openTime='001000', self.closeTime='001459', self.symbol='BTCUSDT', self.open=27056.7, self.close=27061.1, self.high=27099.9, self.low=27056.7 

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.714181719035411, self.count=39606 

self.closeSec=1695917999, self.tradeDate='20230929', self.openTime='001500', self.closeTime='001959', self.symbol='BTCUSDT', self.open=27064.4, self.close=27103.5, self.high=27138.7, self.low=27064.3 
127.0.0.1 - - [29/Sep/2023 00:20:02] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [29/Sep/2023 00:25:00] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.714181719035411, self.count=39607 

self.closeSec=1695918299, self.tradeDate='20230929', self.openTime='002000', self.closeTime='002459', self.symbol='BTCUSDT', self.open=27105.2, self.close=27162.8, self.high=27170.0, self.low=27103.5 


## /root/FIL/strategy/logic/log.txt ----- -----

2023-09-29 00:00:18,038:DEBUG:logic:main.py:463:getModel:2218526: df_s.iloc[-5:,:] :
          date closeTime     open  ...    alpha58   alpha67   alpha72
5801  20230928    212959  26464.2  ...  49.166667  0.546528  0.424726
5802  20230928    215959  26533.7  ...  49.166667  0.554485  0.403155
5803  20230928    222959  26566.1  ...  49.583333  0.562937  0.386642
5804  20230928    225959  26603.7  ...  50.000000  0.600386  0.372487
5805  20230928    232959  26780.0  ...  50.416667  0.613560  0.352623

[5 rows x 33 columns]
0.5275735294117647
acc is : 0.5275735294117647
2023-09-29 00:00:18,096:INFO:logic:main.py:468:getModel:2218526: df_pred.iloc[-5:,:] :
     pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
539     0  0.511816  0.488184       1  ...  0.948378   1.0    0.0  1.003206
540     0  0.507511  0.492489       1  ...  0.949677   1.0    0.0  1.004580
541     0  0.511237  0.488763       1  ...  0.955967   1.0    0.0  1.011234
542     0  0.562884  0.437116       1  ...  0.958419   1.0    0.0  1.013828
543     0  0.537981  0.462019       1  ...  0.964474   1.0    0.0  1.020232

[5 rows x 10 columns]
2023-09-29 00:00:18,107:INFO:logic:main.py:478:getModel:2218526: df_panel.iloc[-5:,:] :
    pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
45     0  0.511624  0.488376       1  ...  0.948378   1.0    0.0  1.001621
46     0  0.507272  0.492728       1  ...  0.949677   1.0    0.0  1.002619
47     0  0.511244  0.488756       1  ...  0.955967   1.0    0.0  1.009381
48     0  0.562987  0.437013       1  ...  0.958419   1.0    0.0  1.011971
49     0  0.537981  0.462019       1  ...  0.964474   1.0    0.0  1.020232

[5 rows x 10 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '25.704', 'enterprice': '26435.2', 'countrevence': '0', 'unrealprofit': '15891.69998742984', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '27053.45785821', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}


## /root/FIL/strategy/modifiedmom/log.txt ----- -----


--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=19799 

self.closeSec=1695914999, self.tradeDate='20230928', self.openTime='232000', self.closeTime='232959', self.symbol='BTCUSDT', self.open='26778.1', self.close='26848.7'
127.0.0.1 - - [28/Sep/2023 23:30:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=19800 

self.closeSec=1695915599, self.tradeDate='20230928', self.openTime='233000', self.closeTime='233959', self.symbol='BTCUSDT', self.open='26848.7', self.close='26864'
127.0.0.1 - - [28/Sep/2023 23:40:01] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [28/Sep/2023 23:50:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=19801 

self.closeSec=1695916199, self.tradeDate='20230928', self.openTime='234000', self.closeTime='234959', self.symbol='BTCUSDT', self.open='26864', self.close='26919.6'
127.0.0.1 - - [29/Sep/2023 00:00:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=19802 

self.closeSec=1695916799, self.tradeDate='20230928', self.openTime='235000', self.closeTime='235959', self.symbol='BTCUSDT', self.open='26919.5', self.close='27012.3'
127.0.0.1 - - [29/Sep/2023 00:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=19803 

self.closeSec=1695917399, self.tradeDate='20230929', self.openTime='000000', self.closeTime='000959', self.symbol='BTCUSDT', self.open='27012.3', self.close='27056.7'

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=19804 

self.closeSec=1695917999, self.tradeDate='20230929', self.openTime='001000', self.closeTime='001959', self.symbol='BTCUSDT', self.open='27056.7', self.close='27103.5'
127.0.0.1 - - [29/Sep/2023 00:20:04] "POST / HTTP/1.1" 200 -


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


--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=19802 

self.closeSec=1695914999, self.tradeDate='20230928', self.openTime='232000', self.closeTime='232959', self.symbol='BTCUSDT', self.open='26778.1', self.close='26848.7'
127.0.0.1 - - [28/Sep/2023 23:30:01] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [28/Sep/2023 23:40:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=19803 

self.closeSec=1695915599, self.tradeDate='20230928', self.openTime='233000', self.closeTime='233959', self.symbol='BTCUSDT', self.open='26848.7', self.close='26864'
127.0.0.1 - - [28/Sep/2023 23:50:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=19804 

self.closeSec=1695916199, self.tradeDate='20230928', self.openTime='234000', self.closeTime='234959', self.symbol='BTCUSDT', self.open='26864', self.close='26919.6'

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=19805 

self.closeSec=1695916799, self.tradeDate='20230928', self.openTime='235000', self.closeTime='235959', self.symbol='BTCUSDT', self.open='26919.5', self.close='27012.3'
127.0.0.1 - - [29/Sep/2023 00:00:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=19806 

self.closeSec=1695917399, self.tradeDate='20230929', self.openTime='000000', self.closeTime='000959', self.symbol='BTCUSDT', self.open='27012.3', self.close='27056.7'
127.0.0.1 - - [29/Sep/2023 00:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=19807 

self.closeSec=1695917999, self.tradeDate='20230929', self.openTime='001000', self.closeTime='001959', self.symbol='BTCUSDT', self.open='27056.7', self.close='27103.5'
127.0.0.1 - - [29/Sep/2023 00:20:05] "POST / HTTP/1.1" 200 -


## /root/FIL/strategy/similarity/log.txt ----- -----


--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=19802 

self.closeSec=1695914999, self.tradeDate='20230928', self.openTime='232000', self.closeTime='232959', self.symbol='BTCUSDT', self.open='26778.1', self.close='26848.7'
127.0.0.1 - - [28/Sep/2023 23:30:01] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [28/Sep/2023 23:40:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=19803 

self.closeSec=1695915599, self.tradeDate='20230928', self.openTime='233000', self.closeTime='233959', self.symbol='BTCUSDT', self.open='26848.7', self.close='26864'
127.0.0.1 - - [28/Sep/2023 23:50:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=19804 

self.closeSec=1695916199, self.tradeDate='20230928', self.openTime='234000', self.closeTime='234959', self.symbol='BTCUSDT', self.open='26864', self.close='26919.6'
127.0.0.1 - - [29/Sep/2023 00:00:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=19805 

self.closeSec=1695916799, self.tradeDate='20230928', self.openTime='235000', self.closeTime='235959', self.symbol='BTCUSDT', self.open='26919.5', self.close='27012.3'

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=19806 

self.closeSec=1695917399, self.tradeDate='20230929', self.openTime='000000', self.closeTime='000959', self.symbol='BTCUSDT', self.open='27012.3', self.close='27056.7'
127.0.0.1 - - [29/Sep/2023 00:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=19807 

self.closeSec=1695917999, self.tradeDate='20230929', self.openTime='001000', self.closeTime='001959', self.symbol='BTCUSDT', self.open='27056.7', self.close='27103.5'
127.0.0.1 - - [29/Sep/2023 00:20:04] "POST / HTTP/1.1" 200 -


## /root/FIL/strategy/sr_min/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=1, self.total=996015.990996, self.flagDict['side']='buy', self.tradeCount=1, self.count=39604
self.closeSec=1695917999, self.tradeDate='20230929', self.openTime='001500', self.closeTime='001959', self.symbol='BTCUSDT', self.open=27064.4, self.close=27103.5, self.high=27138.7, self.low=27064.3, self.vol=3319.742, self.amt=89997085.0049 
127.0.0.1 - - [29/Sep/2023 00:20:02] "POST / HTTP/1.1" 200 -
2023-09-29 00:20:06,353:INFO:sr_min:main.py:172:handleKline:2219263: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5759  20230928   235500    235959  ...         0.0        0.0       0
5760  20230929   000000    000459  ...         0.0        0.0       0
5761  20230929   000500    000959  ...         0.0        0.0       0
5762  20230929   001000    001459  ...         0.0        0.0       0
5763  20230929   001500    001959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-09-29 00:20:06,356:INFO:sr_min:main.py:175:handleKline:2219263: self.closeSec=1695917999, self.tradeDate='20230929', self.openTime='001500', self.closeTime='001959',self.symbol='BTCUSDT',self.open=27064.4, self.close=27103.5, self.high=27138.7, self.low=27064.3, self.vol=3319.742, self.amt=89997085.0049, ukdf['pct'].iloc[-1]=0.001567 , ukdf['amount'].iloc[-1]=89997085.0049, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5763, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '37.141', 'enterprice': '26844', 'countrevence': '0', 'unrealprofit': '9774.14909133741', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '27107.16332601', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=1
--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=1, self.total=996015.990996, self.flagDict['side']='buy', self.tradeCount=1, self.count=39605
self.closeSec=1695918299, self.tradeDate='20230929', self.openTime='002000', self.closeTime='002459', self.symbol='BTCUSDT', self.open=27105.2, self.close=27162.8, self.high=27170.0, self.low=27103.5, self.vol=3474.035, self.amt=94304719.409 
127.0.0.1 - - [29/Sep/2023 00:25:00] "POST / HTTP/1.1" 200 -
2023-09-29 00:25:00,830:INFO:sr_min:main.py:172:handleKline:2219263: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5760  20230929   000000    000459  ...         0.0        0.0       0
5761  20230929   000500    000959  ...         0.0        0.0       0
5762  20230929   001000    001459  ...         0.0        0.0       0
5763  20230929   001500    001959  ...         0.0        0.0       0
5764  20230929   002000    002459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-09-29 00:25:00,830:INFO:sr_min:main.py:175:handleKline:2219263: self.closeSec=1695918299, self.tradeDate='20230929', self.openTime='002000', self.closeTime='002459',self.symbol='BTCUSDT',self.open=27105.2, self.close=27162.8, self.high=27170.0, self.low=27103.5, self.vol=3474.035, self.amt=94304719.409, ukdf['pct'].iloc[-1]=0.002188 , ukdf['amount'].iloc[-1]=94304719.409, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5764, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '37.141', 'enterprice': '26844', 'countrevence': '0', 'unrealprofit': '11879.30151545306', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '27163.84334066', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=1


## /root/FIL/strategy/s_rsrs/log.txt ----- -----

723  20230928   120000    155959  1695887999  ...    723  0.065127 -1.322621    -1.0
724  20230928   160000    195959  1695902399  ...    724  0.083519 -1.267790    -1.0

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '50.756', 'enterprice': '26148.9', 'countrevence': '0', 'unrealprofit': '-15980.17568519744', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '26463.74308624', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-1, self.sign=-1
127.0.0.1 - - [29/Sep/2023 00:00:01] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='s_rsrs', self.symbol='BTCUSDT', interval='4h', intervalSec=14400, wid=25, thd=0.6, self.sign=-1, self.total=1325886.3548316, self.flagDict['side']='sell', self.tradeCount=26, self.count=825
self.closeSec=1695916799, self.tradeDate='20230928', self.openTime='200000', self.closeTime='235959', self.symbol='BTCUSDT', self.open=26464.3, self.close=27018.3, self.high=27075.0, self.low=26450.0, self.vol=132455.69, self.amt=3543541413.57366 
2023-09-29 00:00:01,532:INFO:s_rsrs:main.py:141:handleKline:2218689: self.closeSec=1695916799, self.tradeDate='20230928', self.openTime='200000', self.closeTime='235959',self.symbol='BTCUSDT',self.open=26464.3, self.close=27018.3, self.high=27075.0, self.low=26450.0, self.vol=132455.69, self.amt=3543541413.57366 
2023-09-29 00:00:01,548:INFO:s_rsrs:main.py:142:handleKline:2218689: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime  ...         vol           amt       pct
721  20230928   040000    075959  ...   22069.030  5.802622e+08  0.003965
722  20230928   080000    115959  ...   49939.097  1.319449e+09  0.000156
723  20230928   120000    155959  ...   28672.219  7.578532e+08  0.003107
724  20230928   160000    195959  ...   45294.355  1.199687e+09  0.000707
725  20230928   200000    235959  ...  132455.690  3.543541e+09  0.020930

[5 rows x 11 columns]
2023-09-29 00:00:02,225:INFO:s_rsrs:main.py:151:handleKline:2218689: df_s.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec  ...  index      beta    zscore  signal
721  20230928   040000    075959  1695859199  ...    721  0.066771 -1.337522    -1.0
722  20230928   080000    115959  1695873599  ...    722  0.065406 -1.331945    -1.0
723  20230928   120000    155959  1695887999  ...    723  0.065127 -1.322621    -1.0
724  20230928   160000    195959  1695902399  ...    724  0.083519 -1.267790    -1.0
725  20230928   200000    235959  1695916799  ...    725  0.241155 -0.884063    -1.0

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '50.756', 'enterprice': '26148.9', 'countrevence': '0', 'unrealprofit': '-43827.806', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '27012.4', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-1, self.sign=-1


