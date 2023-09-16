# 20230917 00:26:01

## /root/FIL/strategy/amihud/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=373746.4768026, self.flagDict['side']='sell', self.tradeCount=2, self.count=36148
self.closeSec=1694881199, self.tradeDate='20230917', self.openTime='001500', self.closeTime='001959', self.symbol='BTCUSDT', self.open=26510.0, self.close=26508.2, self.high=26517.8, self.low=26508.1, self.vol=263.902, self.amt=6997033.8207 
127.0.0.1 - - [17/Sep/2023 00:20:02] "POST / HTTP/1.1" 200 -
2023-09-17 00:20:06,469:INFO:amihud:main.py:172:handleKline:2219019: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5759  20230916   235500    235959  ...         0.0        0.0       0
5760  20230917   000000    000459  ...         0.0        0.0       0
5761  20230917   000500    000959  ...         0.0        0.0       0
5762  20230917   001000    001459  ...         0.0        0.0       0
5763  20230917   001500    001959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-09-17 00:20:06,472:INFO:amihud:main.py:175:handleKline:2219019: self.closeSec=1694881199, self.tradeDate='20230917', self.openTime='001500', self.closeTime='001959',self.symbol='BTCUSDT',self.open=26510.0, self.close=26508.2, self.high=26517.8, self.low=26508.1, self.vol=263.902, self.amt=6997033.8207, ukdf['pct'].iloc[-1]=-6.8e-05 , ukdf['amount'].iloc[-1]=6997033.8207, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5763, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '13.926', 'enterprice': '26864.9', 'countrevence': '0', 'unrealprofit': '4945.31310057774', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '26509.78632051', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1
127.0.0.1 - - [17/Sep/2023 00:25:00] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=373746.4768026, self.flagDict['side']='sell', self.tradeCount=2, self.count=36149
self.closeSec=1694881499, self.tradeDate='20230917', self.openTime='002000', self.closeTime='002459', self.symbol='BTCUSDT', self.open=26508.1, self.close=26500.6, self.high=26513.9, self.low=26498.1, self.vol=226.599, self.amt=6006500.5032 
2023-09-17 00:25:00,788:INFO:amihud:main.py:172:handleKline:2219019: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5760  20230917   000000    000459  ...         0.0        0.0       0
5761  20230917   000500    000959  ...         0.0        0.0       0
5762  20230917   001000    001459  ...         0.0        0.0       0
5763  20230917   001500    001959  ...         0.0        0.0       0
5764  20230917   002000    002459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-09-17 00:25:00,789:INFO:amihud:main.py:175:handleKline:2219019: self.closeSec=1694881499, self.tradeDate='20230917', self.openTime='002000', self.closeTime='002459',self.symbol='BTCUSDT',self.open=26508.1, self.close=26500.6, self.high=26513.9, self.low=26498.1, self.vol=226.599, self.amt=6006500.5032, ukdf['pct'].iloc[-1]=-0.000287 , ukdf['amount'].iloc[-1]=6006500.5032, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5764, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '13.926', 'enterprice': '26864.9', 'countrevence': '0', 'unrealprofit': '5073.2418', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '26500.6', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1


## /root/FIL/strategy/factorcheck/log.txt ----- -----

self.closeSec=1694880299, self.tradeDate='20230917', self.openTime='000000', self.closeTime='000459', self.symbol='BTCUSDT', self.open=26493.6, self.close=26496.7, self.high=26503.4, self.low=26491.1 

--ukdf-hist--: overDate='20230912' 
 Empty DataFrame
Columns: [tradeDate, openTime, closeTime, closeSec, open, close, high, low, pct, index, idx]
Index: [] 
 Empty DataFrame
Columns: [tradeDate, openTime, closeTime, closeSec, open, close, high, low, pct, index, idx]
Index: [] 

127.0.0.1 - - [17/Sep/2023 00:10:00] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.714181719035411, self.count=36148 

self.closeSec=1694880599, self.tradeDate='20230917', self.openTime='000500', self.closeTime='000959', self.symbol='BTCUSDT', self.open=26496.6, self.close=26507.4, self.high=26507.5, self.low=26491.8 

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.714181719035411, self.count=36149 

self.closeSec=1694880899, self.tradeDate='20230917', self.openTime='001000', self.closeTime='001459', self.symbol='BTCUSDT', self.open=26507.5, self.close=26510.0, self.high=26510.0, self.low=26507.4 
127.0.0.1 - - [17/Sep/2023 00:15:00] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.714181719035411, self.count=36150 

self.closeSec=1694881199, self.tradeDate='20230917', self.openTime='001500', self.closeTime='001959', self.symbol='BTCUSDT', self.open=26510.0, self.close=26508.2, self.high=26517.8, self.low=26508.1 
127.0.0.1 - - [17/Sep/2023 00:20:02] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.714181719035411, self.count=36151 

self.closeSec=1694881499, self.tradeDate='20230917', self.openTime='002000', self.closeTime='002459', self.symbol='BTCUSDT', self.open=26508.1, self.close=26500.6, self.high=26513.9, self.low=26498.1 
127.0.0.1 - - [17/Sep/2023 00:25:00] "POST / HTTP/1.1" 200 -


## /root/FIL/strategy/logic/log.txt ----- -----

2023-09-17 00:00:18,073:DEBUG:logic:main.py:463:getModel:2218526: df_s.iloc[-5:,:] :
          date closeTime     open  ...    alpha58   alpha67   alpha72
5801  20230916    212959  26538.0  ...  50.416667  0.518094  0.561279
5802  20230916    215959  26528.6  ...  50.833333  0.519962  0.564923
5803  20230916    222959  26535.9  ...  50.833333  0.517438  0.569485
5804  20230916    225959  26526.9  ...  50.833333  0.506459  0.579020
5805  20230916    232959  26487.6  ...  51.250000  0.511983  0.588213

[5 rows x 33 columns]
0.5533088235294118
acc is : 0.5533088235294118
2023-09-17 00:00:18,148:INFO:logic:main.py:468:getModel:2218526: df_pred.iloc[-5:,:] :
     pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
539     1  0.490915  0.509085       1  ...  0.943813   1.0    0.0  1.031534
540     0  0.502637  0.497363       0  ...  0.943493   1.0    0.0  1.031184
541     1  0.495184  0.504816       0  ...  0.942092   1.0    0.0  1.029652
542     1  0.482887  0.517113       1  ...  0.942824   1.0    0.0  1.030453
543     1  0.499524  0.500476       0  ...  0.942312   1.0    0.0  1.029893

[5 rows x 10 columns]
2023-09-17 00:00:18,163:INFO:logic:main.py:478:getModel:2218526: df_panel.iloc[-5:,:] :
    pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
45     1  0.491079  0.508921       1  ...  0.943813   1.0    0.0  1.032718
46     0  0.503171  0.496829       0  ...  0.943493   1.0    0.0  1.032987
47     1  0.495056  0.504944       0  ...  0.942092   1.0    0.0  1.030157
48     1  0.483101  0.516899       1  ...  0.942824   1.0    0.0  1.030958
49     1  0.499524  0.500476       0  ...  0.942312   1.0    0.0  1.029893

[5 rows x 10 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '26.865', 'enterprice': '26592', 'countrevence': '0', 'unrealprofit': '-2677.6109759625', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '26492.3308775', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}


## /root/FIL/strategy/modifiedmom/log.txt ----- -----

127.0.0.1 - - [16/Sep/2023 23:30:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=18071 

self.closeSec=1694878199, self.tradeDate='20230916', self.openTime='232000', self.closeTime='232959', self.symbol='BTCUSDT', self.open='26507.7', self.close='26508.2'
127.0.0.1 - - [16/Sep/2023 23:40:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=18072 

self.closeSec=1694878799, self.tradeDate='20230916', self.openTime='233000', self.closeTime='233959', self.symbol='BTCUSDT', self.open='26508.2', self.close='26524'
127.0.0.1 - - [16/Sep/2023 23:50:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=18073 

self.closeSec=1694879399, self.tradeDate='20230916', self.openTime='234000', self.closeTime='234959', self.symbol='BTCUSDT', self.open='26524', self.close='26510.2'
127.0.0.1 - - [17/Sep/2023 00:00:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=18074 

self.closeSec=1694879999, self.tradeDate='20230916', self.openTime='235000', self.closeTime='235959', self.symbol='BTCUSDT', self.open='26510.1', self.close='26493.6'
127.0.0.1 - - [17/Sep/2023 00:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=18075 

self.closeSec=1694880599, self.tradeDate='20230917', self.openTime='000000', self.closeTime='000959', self.symbol='BTCUSDT', self.open='26493.6', self.close='26507.4'

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=18076 

self.closeSec=1694881199, self.tradeDate='20230917', self.openTime='001000', self.closeTime='001959', self.symbol='BTCUSDT', self.open='26507.5', self.close='26508.2'
127.0.0.1 - - [17/Sep/2023 00:20:04] "POST / HTTP/1.1" 200 -


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


--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=18074 

self.closeSec=1694878199, self.tradeDate='20230916', self.openTime='232000', self.closeTime='232959', self.symbol='BTCUSDT', self.open='26507.7', self.close='26508.2'
127.0.0.1 - - [16/Sep/2023 23:30:01] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [16/Sep/2023 23:40:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=18075 

self.closeSec=1694878799, self.tradeDate='20230916', self.openTime='233000', self.closeTime='233959', self.symbol='BTCUSDT', self.open='26508.2', self.close='26524'

--handleKline--: 127.0.0.1 - - [16/Sep/2023 23:50:01] "POST / HTTP/1.1" 200 -
 self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=18076 

self.closeSec=1694879399, self.tradeDate='20230916', self.openTime='234000', self.closeTime='234959', self.symbol='BTCUSDT', self.open='26524', self.close='26510.2'

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=18077 

self.closeSec=1694879999, self.tradeDate='20230916', self.openTime='235000', self.closeTime='235959', self.symbol='BTCUSDT', self.open='26510.1', self.close='26493.6'
127.0.0.1 - - [17/Sep/2023 00:00:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=18078 

self.closeSec=1694880599, self.tradeDate='20230917', self.openTime='000000', self.closeTime='000959', self.symbol='BTCUSDT', self.open='26493.6', self.close='26507.4'
127.0.0.1 - - [17/Sep/2023 00:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=18079 

self.closeSec=1694881199, self.tradeDate='20230917', self.openTime='001000', self.closeTime='001959', self.symbol='BTCUSDT', self.open='26507.5', self.close='26508.2'
127.0.0.1 - - [17/Sep/2023 00:20:04] "POST / HTTP/1.1" 200 -


## /root/FIL/strategy/similarity/log.txt ----- -----


--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=18074 

self.closeSec=1694878199, self.tradeDate='20230916', self.openTime='232000', self.closeTime='232959', self.symbol='BTCUSDT', self.open='26507.7', self.close='26508.2'
127.0.0.1 - - [16/Sep/2023 23:30:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=18075 

self.closeSec=1694878799, self.tradeDate='20230916', self.openTime='233000', self.closeTime='233959', self.symbol='BTCUSDT', self.open='26508.2', self.close='26524'
127.0.0.1 - - [16/Sep/2023 23:40:01] "POST / HTTP/1.1" 200 -

--handleKline--: 127.0.0.1 - - [16/Sep/2023 23:50:01] "POST / HTTP/1.1" 200 -
 self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=18076 

self.closeSec=1694879399, self.tradeDate='20230916', self.openTime='234000', self.closeTime='234959', self.symbol='BTCUSDT', self.open='26524', self.close='26510.2'
127.0.0.1 - - [17/Sep/2023 00:00:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=18077 

self.closeSec=1694879999, self.tradeDate='20230916', self.openTime='235000', self.closeTime='235959', self.symbol='BTCUSDT', self.open='26510.1', self.close='26493.6'

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=18078 

self.closeSec=1694880599, self.tradeDate='20230917', self.openTime='000000', self.closeTime='000959', self.symbol='BTCUSDT', self.open='26493.6', self.close='26507.4'
127.0.0.1 - - [17/Sep/2023 00:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=18079 

self.closeSec=1694881199, self.tradeDate='20230917', self.openTime='001000', self.closeTime='001959', self.symbol='BTCUSDT', self.open='26507.5', self.close='26508.2'
127.0.0.1 - - [17/Sep/2023 00:20:04] "POST / HTTP/1.1" 200 -


## /root/FIL/strategy/sr_min/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=1, self.total=996015.990996, self.flagDict['side']='buy', self.tradeCount=1, self.count=36148
self.closeSec=1694881199, self.tradeDate='20230917', self.openTime='001500', self.closeTime='001959', self.symbol='BTCUSDT', self.open=26510.0, self.close=26508.2, self.high=26517.8, self.low=26508.1, self.vol=263.902, self.amt=6997033.8207 
127.0.0.1 - - [17/Sep/2023 00:20:02] "POST / HTTP/1.1" 200 -
2023-09-17 00:20:06,473:INFO:sr_min:main.py:172:handleKline:2219263: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5759  20230916   235500    235959  ...         0.0        0.0       0
5760  20230917   000000    000459  ...         0.0        0.0       0
5761  20230917   000500    000959  ...         0.0        0.0       0
5762  20230917   001000    001459  ...         0.0        0.0       0
5763  20230917   001500    001959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-09-17 00:20:06,483:INFO:sr_min:main.py:175:handleKline:2219263: self.closeSec=1694881199, self.tradeDate='20230917', self.openTime='001500', self.closeTime='001959',self.symbol='BTCUSDT',self.open=26510.0, self.close=26508.2, self.high=26517.8, self.low=26508.1, self.vol=263.902, self.amt=6997033.8207, ukdf['pct'].iloc[-1]=-6.8e-05 , ukdf['amount'].iloc[-1]=6997033.8207, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5763, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '37.141', 'enterprice': '26844', 'countrevence': '0', 'unrealprofit': '-12413.03026993809', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '26509.78632051', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=1
--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=1, self.total=996015.990996, self.flagDict['side']='buy', self.tradeCount=1, self.count=36149
self.closeSec=1694881499, self.tradeDate='20230917', self.openTime='002000', self.closeTime='002459', self.symbol='BTCUSDT', self.open=26508.1, self.close=26500.6, self.high=26513.9, self.low=26498.1, self.vol=226.599, self.amt=6006500.5032 
127.0.0.1 - - [17/Sep/2023 00:25:00] "POST / HTTP/1.1" 200 -
2023-09-17 00:25:00,785:INFO:sr_min:main.py:172:handleKline:2219263: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5760  20230917   000000    000459  ...         0.0        0.0       0
5761  20230917   000500    000959  ...         0.0        0.0       0
5762  20230917   001000    001459  ...         0.0        0.0       0
5763  20230917   001500    001959  ...         0.0        0.0       0
5764  20230917   002000    002459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-09-17 00:25:00,785:INFO:sr_min:main.py:175:handleKline:2219263: self.closeSec=1694881499, self.tradeDate='20230917', self.openTime='002000', self.closeTime='002459',self.symbol='BTCUSDT',self.open=26508.1, self.close=26500.6, self.high=26513.9, self.low=26498.1, self.vol=226.599, self.amt=6006500.5032, ukdf['pct'].iloc[-1]=-0.000287 , ukdf['amount'].iloc[-1]=6006500.5032, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5764, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '37.141', 'enterprice': '26844', 'countrevence': '0', 'unrealprofit': '-12754.2194', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '26500.6', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=1


## /root/FIL/strategy/s_rsrs/log.txt ----- -----

723  20230916   120000    155959  1694851199  ...    723  0.426659  0.347395     NaN
724  20230916   160000    195959  1694865599  ...    724  0.357263  0.098166     NaN

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '53.725', 'enterprice': '26678.4', 'countrevence': '0', 'unrealprofit': '-9015.055', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '26510.6', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-9223372036854775808, self.sign=1
--handleKline--:  version='2.0.0', self.name='s_rsrs', self.symbol='BTCUSDT', interval='4h', intervalSec=14400, wid=25, thd=0.6, self.sign=1, self.total=1431863.74296, self.flagDict['side']='buy', self.tradeCount=23, self.count=753
self.closeSec=1694879999, self.tradeDate='20230916', self.openTime='200000', self.closeTime='235959', self.symbol='BTCUSDT', self.open=26510.6, self.close=26493.6, self.high=26566.4, self.low=26470.3, self.vol=15417.259, self.amt=408843973.5938 
127.0.0.1 - - [17/Sep/2023 00:00:01] "POST / HTTP/1.1" 200 -
2023-09-17 00:00:01,518:INFO:s_rsrs:main.py:141:handleKline:2218689: self.closeSec=1694879999, self.tradeDate='20230916', self.openTime='200000', self.closeTime='235959',self.symbol='BTCUSDT',self.open=26510.6, self.close=26493.6, self.high=26566.4, self.low=26470.3, self.vol=15417.259, self.amt=408843973.5938 
2023-09-17 00:00:01,533:INFO:s_rsrs:main.py:142:handleKline:2218689: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime  ...        vol           amt       pct
721  20230916   040000    075959  ...  66407.988  1.769890e+09  0.007724
722  20230916   080000    115959  ...  32987.327  8.790867e+08  0.000436
723  20230916   120000    155959  ...  32167.402  8.531910e+08 -0.004376
724  20230916   160000    195959  ...  31565.807  8.364129e+08  0.000933
725  20230916   200000    235959  ...  15417.259  4.088440e+08 -0.000645

[5 rows x 11 columns]
2023-09-17 00:00:02,294:INFO:s_rsrs:main.py:151:handleKline:2218689: df_s.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec  ...  index      beta    zscore  signal
721  20230916   040000    075959  1694822399  ...    721  0.530162  0.704080     1.0
722  20230916   080000    115959  1694836799  ...    722  0.353228  0.057789     NaN
723  20230916   120000    155959  1694851199  ...    723  0.426659  0.347395     NaN
724  20230916   160000    195959  1694865599  ...    724  0.357263  0.098166     NaN
725  20230916   200000    235959  1694879999  ...    725  0.386956  0.223744     NaN

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '53.725', 'enterprice': '26678.4', 'countrevence': '0', 'unrealprofit': '-9928.38', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '26493.6', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-9223372036854775808, self.sign=1


