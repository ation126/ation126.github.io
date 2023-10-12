# 20231013 00:26:01

## /root/FIL/strategy/amihud/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=373746.4768026, self.flagDict['side']='sell', self.tradeCount=2, self.count=43636
self.closeSec=1697127599, self.tradeDate='20231013', self.openTime='001500', self.closeTime='001959', self.symbol='BTCUSDT', self.open=26689.9, self.close=26696.5, self.high=26705.0, self.low=26686.4, self.vol=536.645, self.amt=14326566.0161 
127.0.0.1 - - [13/Oct/2023 00:20:11] "POST / HTTP/1.1" 200 -
2023-10-13 00:20:17,902:INFO:amihud:main.py:172:handleKline:2219019: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5759  20231012   235500    235959  ...         0.0        0.0       0
5760  20231013   000000    000459  ...         0.0        0.0       0
5761  20231013   000500    000959  ...         0.0        0.0       0
5762  20231013   001000    001459  ...         0.0        0.0       0
5763  20231013   001500    001959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-10-13 00:20:17,913:INFO:amihud:main.py:175:handleKline:2219019: self.closeSec=1697127599, self.tradeDate='20231013', self.openTime='001500', self.closeTime='001959',self.symbol='BTCUSDT',self.open=26689.9, self.close=26696.5, self.high=26705.0, self.low=26686.4, self.vol=536.645, self.amt=14326566.0161, ukdf['pct'].iloc[-1]=0.000247 , ukdf['amount'].iloc[-1]=14326566.0161, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5763, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '13.926', 'enterprice': '26864.9', 'countrevence': '0', 'unrealprofit': '2391.8311047345', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '26693.14708425', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1
127.0.0.1 - - [13/Oct/2023 00:25:00] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=373746.4768026, self.flagDict['side']='sell', self.tradeCount=2, self.count=43637
self.closeSec=1697127899, self.tradeDate='20231013', self.openTime='002000', self.closeTime='002459', self.symbol='BTCUSDT', self.open=26696.5, self.close=26670.1, self.high=26696.6, self.low=26668.7, self.vol=466.833, self.amt=12454100.1451 
2023-10-13 00:25:00,833:INFO:amihud:main.py:172:handleKline:2219019: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5760  20231013   000000    000459  ...         0.0        0.0       0
5761  20231013   000500    000959  ...         0.0        0.0       0
5762  20231013   001000    001459  ...         0.0        0.0       0
5763  20231013   001500    001959  ...         0.0        0.0       0
5764  20231013   002000    002459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-10-13 00:25:00,834:INFO:amihud:main.py:175:handleKline:2219019: self.closeSec=1697127899, self.tradeDate='20231013', self.openTime='002000', self.closeTime='002459',self.symbol='BTCUSDT',self.open=26696.5, self.close=26670.1, self.high=26696.6, self.low=26668.7, self.vol=466.833, self.amt=12454100.1451, ukdf['pct'].iloc[-1]=-0.000989 , ukdf['amount'].iloc[-1]=12454100.1451, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5764, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '13.926', 'enterprice': '26864.9', 'countrevence': '0', 'unrealprofit': '2699.37194510874', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '26671.06315201', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1


## /root/FIL/strategy/factorcheck/log.txt ----- -----

127.0.0.1 - - [13/Oct/2023 00:05:00] "POST / HTTP/1.1" 200 -

--ukdf-hist--: overDate='20231008' 
 Empty DataFrame
Columns: [tradeDate, openTime, closeTime, closeSec, open, close, high, low, pct, index, idx]
Index: [] 
 Empty DataFrame
Columns: [tradeDate, openTime, closeTime, closeSec, open, close, high, low, pct, index, idx]
Index: [] 

127.0.0.1 - - [13/Oct/2023 00:10:00] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.714181719035411, self.count=43636 

self.closeSec=1697126999, self.tradeDate='20231013', self.openTime='000500', self.closeTime='000959', self.symbol='BTCUSDT', self.open=26660.4, self.close=26699.8, self.high=26709.1, self.low=26660.4 

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.714181719035411, self.count=43637 

self.closeSec=1697127299, self.tradeDate='20231013', self.openTime='001000', self.closeTime='001459', self.symbol='BTCUSDT', self.open=26699.8, self.close=26689.9, self.high=26704.4, self.low=26686.3 
127.0.0.1 - - [13/Oct/2023 00:15:01] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.714181719035411, self.count=43638 

self.closeSec=1697127599, self.tradeDate='20231013', self.openTime='001500', self.closeTime='001959', self.symbol='BTCUSDT', self.open=26689.9, self.close=26696.5, self.high=26705.0, self.low=26686.4 
127.0.0.1 - - [13/Oct/2023 00:20:10] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [13/Oct/2023 00:25:00] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.714181719035411, self.count=43639 

self.closeSec=1697127899, self.tradeDate='20231013', self.openTime='002000', self.closeTime='002459', self.symbol='BTCUSDT', self.open=26696.5, self.close=26670.1, self.high=26696.6, self.low=26668.7 


## /root/FIL/strategy/logic/log.txt ----- -----

2023-10-13 00:00:19,294:DEBUG:logic:main.py:463:getModel:2218526: df_s.iloc[-5:,:] :
          date closeTime     open  ...    alpha58   alpha67   alpha72
5801  20231012    212959  26817.0  ...  47.916667  0.425003  0.567633
5802  20231012    215959  26750.5  ...  47.916667  0.423078  0.564771
5803  20231012    222959  26746.7  ...  47.916667  0.407323  0.578311
5804  20231012    225959  26677.1  ...  47.916667  0.411020  0.592015
5805  20231012    232959  26690.3  ...  47.500000  0.400526  0.614488

[5 rows x 33 columns]
0.5551470588235294
acc is : 0.5551470588235294
2023-10-13 00:00:19,359:INFO:logic:main.py:468:getModel:2218526: df_pred.iloc[-5:,:] :
     pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
539     1  0.479617  0.520383       0  ...  0.978166  -1.0    0.0  0.987255
540     1  0.495055  0.504945       0  ...  0.980646  -1.0    0.0  0.984752
541     1  0.465967  0.534033       1  ...  0.980234  -1.0    0.0  0.985165
542     1  0.490071  0.509929       0  ...  0.981927  -1.0    0.0  0.983464
543     1  0.469797  0.530203       1  ...  0.981230  -1.0    0.0  0.984161

[5 rows x 10 columns]
2023-10-13 00:00:19,372:INFO:logic:main.py:478:getModel:2218526: df_panel.iloc[-5:,:] :
    pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
45     1  0.479673  0.520327       0  ...  0.978166  -1.0    0.0  0.987780
46     1  0.495048  0.504952       0  ...  0.980646  -1.0    0.0  0.983986
47     1  0.466214  0.533786       1  ...  0.980234  -1.0    0.0  0.985173
48     1  0.490301  0.509699       0  ...  0.981927  -1.0    0.0  0.983471
49     1  0.469797  0.530203       1  ...  0.981230  -1.0    0.0  0.984161

[5 rows x 10 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '24.051', 'enterprice': '26768.8', 'countrevence': '0', 'unrealprofit': '2537.3805', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '26663.3', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}


## /root/FIL/strategy/modifiedmom/log.txt ----- -----

127.0.0.1 - - [12/Oct/2023 23:30:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=21815 

self.closeSec=1697124599, self.tradeDate='20231012', self.openTime='232000', self.closeTime='232959', self.symbol='BTCUSDT', self.open='26715.9', self.close='26644.2'
127.0.0.1 - - [12/Oct/2023 23:40:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=21816 

self.closeSec=1697125199, self.tradeDate='20231012', self.openTime='233000', self.closeTime='233959', self.symbol='BTCUSDT', self.open='26644.2', self.close='26673.6'
127.0.0.1 - - [12/Oct/2023 23:50:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=21817 

self.closeSec=1697125799, self.tradeDate='20231012', self.openTime='234000', self.closeTime='234959', self.symbol='BTCUSDT', self.open='26673.6', self.close='26617.9'
127.0.0.1 - - [13/Oct/2023 00:00:02] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=21818 

self.closeSec=1697126399, self.tradeDate='20231012', self.openTime='235000', self.closeTime='235959', self.symbol='BTCUSDT', self.open='26617', self.close='26663'

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=21819 

self.closeSec=1697126999, self.tradeDate='20231013', self.openTime='000000', self.closeTime='000959', self.symbol='BTCUSDT', self.open='26665.4', self.close='26699.8'
127.0.0.1 - - [13/Oct/2023 00:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=21820 

self.closeSec=1697127599, self.tradeDate='20231013', self.openTime='001000', self.closeTime='001959', self.symbol='BTCUSDT', self.open='26699.8', self.close='26696.5'
127.0.0.1 - - [13/Oct/2023 00:20:13] "POST / HTTP/1.1" 200 -


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


--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=21818 

self.closeSec=1697124599, self.tradeDate='20231012', self.openTime='232000', self.closeTime='232959', self.symbol='BTCUSDT', self.open='26715.9', self.close='26644.2'
127.0.0.1 - - [12/Oct/2023 23:30:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=21819 

self.closeSec=1697125199, self.tradeDate='20231012', self.openTime='233000', self.closeTime='233959', self.symbol='BTCUSDT', self.open='26644.2', self.close='26673.6'
127.0.0.1 - - [12/Oct/2023 23:40:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=21820 

self.closeSec=1697125799, self.tradeDate='20231012', self.openTime='234000', self.closeTime='234959', self.symbol='BTCUSDT', self.open='26673.6', self.close='26617.9'
127.0.0.1 - - [12/Oct/2023 23:50:01] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [13/Oct/2023 00:00:02] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=21821 

self.closeSec=1697126399, self.tradeDate='20231012', self.openTime='235000', self.closeTime='235959', self.symbol='BTCUSDT', self.open='26617', self.close='26663'
127.0.0.1 - - [13/Oct/2023 00:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=21822 

self.closeSec=1697126999, self.tradeDate='20231013', self.openTime='000000', self.closeTime='000959', self.symbol='BTCUSDT', self.open='26665.4', self.close='26699.8'

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=21823 

self.closeSec=1697127599, self.tradeDate='20231013', self.openTime='001000', self.closeTime='001959', self.symbol='BTCUSDT', self.open='26699.8', self.close='26696.5'
127.0.0.1 - - [13/Oct/2023 00:20:13] "POST / HTTP/1.1" 200 -


## /root/FIL/strategy/similarity/log.txt ----- -----

127.0.0.1 - - [12/Oct/2023 23:30:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=21818 

self.closeSec=1697124599, self.tradeDate='20231012', self.openTime='232000', self.closeTime='232959', self.symbol='BTCUSDT', self.open='26715.9', self.close='26644.2'

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=21819 

self.closeSec=1697125199, self.tradeDate='20231012', self.openTime='233000', self.closeTime='233959', self.symbol='BTCUSDT', self.open='26644.2', self.close='26673.6'
127.0.0.1 - - [12/Oct/2023 23:40:01] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [12/Oct/2023 23:50:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=21820 

self.closeSec=1697125799, self.tradeDate='20231012', self.openTime='234000', self.closeTime='234959', self.symbol='BTCUSDT', self.open='26673.6', self.close='26617.9'

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=21821 

self.closeSec=1697126399, self.tradeDate='20231012', self.openTime='235000', self.closeTime='235959', self.symbol='BTCUSDT', self.open='26617', self.close='26663'
127.0.0.1 - - [13/Oct/2023 00:00:02] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=21822 

self.closeSec=1697126999, self.tradeDate='20231013', self.openTime='000000', self.closeTime='000959', self.symbol='BTCUSDT', self.open='26665.4', self.close='26699.8'
127.0.0.1 - - [13/Oct/2023 00:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=21823 

self.closeSec=1697127599, self.tradeDate='20231013', self.openTime='001000', self.closeTime='001959', self.symbol='BTCUSDT', self.open='26699.8', self.close='26696.5'
127.0.0.1 - - [13/Oct/2023 00:20:12] "POST / HTTP/1.1" 200 -


## /root/FIL/strategy/sr_min/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=1, self.total=996015.990996, self.flagDict['side']='buy', self.tradeCount=1, self.count=43636
self.closeSec=1697127599, self.tradeDate='20231013', self.openTime='001500', self.closeTime='001959', self.symbol='BTCUSDT', self.open=26689.9, self.close=26696.5, self.high=26705.0, self.low=26686.4, self.vol=536.645, self.amt=14326566.0161 
127.0.0.1 - - [13/Oct/2023 00:20:10] "POST / HTTP/1.1" 200 -
2023-10-13 00:20:17,903:INFO:sr_min:main.py:172:handleKline:2219263: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5759  20231012   235500    235959  ...         0.0        0.0       0
5760  20231013   000000    000459  ...         0.0        0.0       0
5761  20231013   000500    000959  ...         0.0        0.0       0
5762  20231013   001000    001459  ...         0.0        0.0       0
5763  20231013   001500    001959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-10-13 00:20:17,923:INFO:sr_min:main.py:175:handleKline:2219263: self.closeSec=1697127599, self.tradeDate='20231013', self.openTime='001500', self.closeTime='001959',self.symbol='BTCUSDT',self.open=26689.9, self.close=26696.5, self.high=26705.0, self.low=26686.4, self.vol=536.645, self.amt=14326566.0161, ukdf['pct'].iloc[-1]=0.000247 , ukdf['amount'].iloc[-1]=14326566.0161, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5763, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '37.141', 'enterprice': '26844', 'countrevence': '0', 'unrealprofit': '-5602.82814387075', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '26693.14708425', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=1
127.0.0.1 - - [13/Oct/2023 00:25:00] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=1, self.total=996015.990996, self.flagDict['side']='buy', self.tradeCount=1, self.count=43637
self.closeSec=1697127899, self.tradeDate='20231013', self.openTime='002000', self.closeTime='002459', self.symbol='BTCUSDT', self.open=26696.5, self.close=26670.1, self.high=26696.6, self.low=26668.7, self.vol=466.833, self.amt=12454100.1451 
2023-10-13 00:25:00,841:INFO:sr_min:main.py:172:handleKline:2219263: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5760  20231013   000000    000459  ...         0.0        0.0       0
5761  20231013   000500    000959  ...         0.0        0.0       0
5762  20231013   001000    001459  ...         0.0        0.0       0
5763  20231013   001500    001959  ...         0.0        0.0       0
5764  20231013   002000    002459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-10-13 00:25:00,842:INFO:sr_min:main.py:175:handleKline:2219263: self.closeSec=1697127899, self.tradeDate='20231013', self.openTime='002000', self.closeTime='002459',self.symbol='BTCUSDT',self.open=26696.5, self.close=26670.1, self.high=26696.6, self.low=26668.7, self.vol=466.833, self.amt=12454100.1451, ukdf['pct'].iloc[-1]=-0.000989 , ukdf['amount'].iloc[-1]=12454100.1451, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5764, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '37.141', 'enterprice': '26844', 'countrevence': '0', 'unrealprofit': '-6423.04747119659', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '26671.06315201', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=1


## /root/FIL/strategy/s_rsrs/log.txt ----- -----

2023-10-12 20:00:10,448:INFO:s_rsrs:main.py:343:handleOrderNew:2218689: handleOrderNew: data=OrderType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'clientorderid': '43003F1697112004817I0L65', 'symbol': 'BTCUSDT', 'gatewayorderid': 1697112005226464, 'quantity': '43.597', 'price': '26828.9', 'stopprice': '0', 'ordertype': '', 'side': 'BUY', 'status': 'FILLED', 'positionside': 'LONG', 'createtime': 1697112003899, 'updatetime': 1697112005226, 'tradetype': 'usdt', 'selfid': 43003, 'filltrades': [TradeType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'tradeid': 1697112005226, 'clientorderid': '43003F1697112004817I0L65', 'price': '26828.9', 'quantity': '43.597', 'commission': '1169.6595533', 'commissionasset': 'USDT', 'tradetime': 1697112005226, 'tradetype': 'usdt', 'gatetype': 'simulator', 'handletime': 1697112005226}], 'gatetype': 'simulator', 'handletime': 0}
2023-10-12 20:00:10,448:INFO:s_rsrs:main.py:346:handleOrderFilled:2218689: handleOrderFilled: data=OrderType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'clientorderid': '43003F1697112004817I0L65', 'symbol': 'BTCUSDT', 'gatewayorderid': 1697112005226464, 'quantity': '43.597', 'price': '26828.9', 'stopprice': '0', 'ordertype': '', 'side': 'BUY', 'status': 'FILLED', 'positionside': 'LONG', 'createtime': 1697112003899, 'updatetime': 1697112005226, 'tradetype': 'usdt', 'selfid': 43003, 'filltrades': [TradeType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'tradeid': 1697112005226, 'clientorderid': '43003F1697112004817I0L65', 'price': '26828.9', 'quantity': '43.597', 'commission': '1169.6595533', 'commissionasset': 'USDT', 'tradetime': 1697112005226, 'tradetype': 'usdt', 'gatetype': 'simulator', 'handletime': 1697112005226}], 'gatetype': 'simulator', 'handletime': 0}
2023-10-12 20:00:10,904:INFO:s_rsrs:main.py:343:handleOrderNew:2218689: handleOrderNew: data=OrderType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'clientorderid': '43004F1697112010418I0L65', 'symbol': 'BTCUSDT', 'gatewayorderid': 1697112010862239, 'quantity': '47.147', 'price': '26826.9', 'stopprice': '0', 'ordertype': '', 'side': 'BUY', 'status': 'FILLED', 'positionside': 'LONG', 'createtime': 1697112009918, 'updatetime': 1697112010862, 'tradetype': 'usdt', 'selfid': 43004, 'filltrades': [TradeType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'tradeid': 1697112010862, 'clientorderid': '43004F1697112010418I0L65', 'price': '26826.9', 'quantity': '47.147', 'commission': '1264.8078543', 'commissionasset': 'USDT', 'tradetime': 1697112010862, 'tradetype': 'usdt', 'gatetype': 'simulator', 'handletime': 1697112010862}], 'gatetype': 'simulator', 'handletime': 0}
127.0.0.1 - - [12/Oct/2023 20:00:10] "POST / HTTP/1.1" 200 -
2023-10-12 20:00:11,087:INFO:s_rsrs:main.py:346:handleOrderFilled:2218689: handleOrderFilled: data=OrderType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'clientorderid': '43004F1697112010418I0L65', 'symbol': 'BTCUSDT', 'gatewayorderid': 1697112010862239, 'quantity': '47.147', 'price': '26826.9', 'stopprice': '0', 'ordertype': '', 'side': 'BUY', 'status': 'FILLED', 'positionside': 'LONG', 'createtime': 1697112009918, 'updatetime': 1697112010862, 'tradetype': 'usdt', 'selfid': 43004, 'filltrades': [TradeType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'tradeid': 1697112010862, 'clientorderid': '43004F1697112010418I0L65', 'price': '26826.9', 'quantity': '47.147', 'commission': '1264.8078543', 'commissionasset': 'USDT', 'tradetime': 1697112010862, 'tradetype': 'usdt', 'gatetype': 'simulator', 'handletime': 1697112010862}], 'gatetype': 'simulator', 'handletime': 0}
127.0.0.1 - - [12/Oct/2023 20:00:11] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='s_rsrs', self.symbol='BTCUSDT', interval='4h', intervalSec=14400, wid=25, thd=0.6, self.sign=1, self.total=1263543.0464457, self.flagDict['side']='buy', self.tradeCount=33, self.count=909
self.closeSec=1697126399, self.tradeDate='20231012', self.openTime='200000', self.closeTime='235959', self.symbol='BTCUSDT', self.open=26827.4, self.close=26663.0, self.high=26853.9, self.low=26606.2, self.vol=52334.34, self.amt=1398958475.9855 
127.0.0.1 - - [13/Oct/2023 00:00:01] "POST / HTTP/1.1" 200 -
2023-10-13 00:00:01,602:INFO:s_rsrs:main.py:141:handleKline:2218689: self.closeSec=1697126399, self.tradeDate='20231012', self.openTime='200000', self.closeTime='235959',self.symbol='BTCUSDT',self.open=26827.4, self.close=26663.0, self.high=26853.9, self.low=26606.2, self.vol=52334.34, self.amt=1398958475.9855 
2023-10-13 00:00:01,621:INFO:s_rsrs:main.py:142:handleKline:2218689: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime  ...        vol           amt       pct
721  20231012   040000    075959  ...  28736.228  7.690963e+08  0.004209
722  20231012   080000    115959  ...  30667.851  8.226242e+08 -0.001128
723  20231012   120000    155959  ...  22534.866  6.047471e+08 -0.001368
724  20231012   160000    195959  ...  41185.888  1.101793e+09  0.001049
725  20231012   200000    235959  ...  52334.340  1.398958e+09 -0.006128

[5 rows x 11 columns]
2023-10-13 00:00:02,448:INFO:s_rsrs:main.py:151:handleKline:2218689: df_s.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec  ...  index      beta    zscore  signal
721  20231012   040000    075959  1697068799  ...    721  0.642365  0.364240     NaN
722  20231012   080000    115959  1697083199  ...    722  0.691669  0.487152     NaN
723  20231012   120000    155959  1697097599  ...    723  0.732357  0.584987     NaN
724  20231012   160000    195959  1697111999  ...    724  0.758655  0.641186     1.0
725  20231012   200000    235959  1697126399  ...    725  0.783933  0.693354     1.0

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '47.147', 'enterprice': '26826.9', 'countrevence': '0', 'unrealprofit': '-7468.0848', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '26668.5', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=1, self.sign=1


