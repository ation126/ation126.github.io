# 20231009 00:26:02

## /root/FIL/strategy/amihud/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=373746.4768026, self.flagDict['side']='sell', self.tradeCount=2, self.count=42484
self.closeSec=1696781999, self.tradeDate='20231009', self.openTime='001500', self.closeTime='001959', self.symbol='BTCUSDT', self.open=27880.0, self.close=27888.4, self.high=27896.4, self.low=27875.3, self.vol=365.319, self.amt=10186407.6797 
127.0.0.1 - - [09/Oct/2023 00:20:02] "POST / HTTP/1.1" 200 -
2023-10-09 00:20:06,683:INFO:amihud:main.py:172:handleKline:2219019: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5759  20231008   235500    235959  ...         0.0        0.0       0
5760  20231009   000000    000459  ...         0.0        0.0       0
5761  20231009   000500    000959  ...         0.0        0.0       0
5762  20231009   001000    001459  ...         0.0        0.0       0
5763  20231009   001500    001959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-10-09 00:20:06,702:INFO:amihud:main.py:175:handleKline:2219019: self.closeSec=1696781999, self.tradeDate='20231009', self.openTime='001500', self.closeTime='001959',self.symbol='BTCUSDT',self.open=27880.0, self.close=27888.4, self.high=27896.4, self.low=27875.3, self.vol=365.319, self.amt=10186407.6797, ukdf['pct'].iloc[-1]=0.000301 , ukdf['amount'].iloc[-1]=10186407.6797, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5763, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '13.926', 'enterprice': '26864.9', 'countrevence': '0', 'unrealprofit': '-14271.43891890684', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '27889.70532234', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1
127.0.0.1 - - [09/Oct/2023 00:25:00] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=373746.4768026, self.flagDict['side']='sell', self.tradeCount=2, self.count=42485
self.closeSec=1696782299, self.tradeDate='20231009', self.openTime='002000', self.closeTime='002459', self.symbol='BTCUSDT', self.open=27888.4, self.close=27863.9, self.high=27895.0, self.low=27863.9, self.vol=810.842, self.amt=22600875.33 
2023-10-09 00:25:00,803:INFO:amihud:main.py:172:handleKline:2219019: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5760  20231009   000000    000459  ...         0.0        0.0       0
5761  20231009   000500    000959  ...         0.0        0.0       0
5762  20231009   001000    001459  ...         0.0        0.0       0
5763  20231009   001500    001959  ...         0.0        0.0       0
5764  20231009   002000    002459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-10-09 00:25:00,804:INFO:amihud:main.py:175:handleKline:2219019: self.closeSec=1696782299, self.tradeDate='20231009', self.openTime='002000', self.closeTime='002459',self.symbol='BTCUSDT',self.open=27888.4, self.close=27863.9, self.high=27895.0, self.low=27863.9, self.vol=810.842, self.amt=22600875.33, ukdf['pct'].iloc[-1]=-0.000879 , ukdf['amount'].iloc[-1]=22600875.33, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5764, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '13.926', 'enterprice': '26864.9', 'countrevence': '0', 'unrealprofit': '-13930.77393989094', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '27865.24280769', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1


## /root/FIL/strategy/factorcheck/log.txt ----- -----

127.0.0.1 - - [09/Oct/2023 00:05:00] "POST / HTTP/1.1" 200 -

--ukdf-hist--: overDate='20231004' 
 Empty DataFrame
Columns: [tradeDate, openTime, closeTime, closeSec, open, close, high, low, pct, index, idx]
Index: [] 
 Empty DataFrame
Columns: [tradeDate, openTime, closeTime, closeSec, open, close, high, low, pct, index, idx]
Index: [] 


--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.714181719035411, self.count=42484 

self.closeSec=1696781399, self.tradeDate='20231009', self.openTime='000500', self.closeTime='000959', self.symbol='BTCUSDT', self.open=27907.3, self.close=27904.9, self.high=27928.8, self.low=27901.5 
127.0.0.1 - - [09/Oct/2023 00:10:00] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.714181719035411, self.count=42485 

self.closeSec=1696781699, self.tradeDate='20231009', self.openTime='001000', self.closeTime='001459', self.symbol='BTCUSDT', self.open=27904.8, self.close=27880.0, self.high=27924.8, self.low=27880.0 
127.0.0.1 - - [09/Oct/2023 00:15:01] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.714181719035411, self.count=42486 

self.closeSec=1696781999, self.tradeDate='20231009', self.openTime='001500', self.closeTime='001959', self.symbol='BTCUSDT', self.open=27880.0, self.close=27888.4, self.high=27896.4, self.low=27875.3 
127.0.0.1 - - [09/Oct/2023 00:20:01] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.714181719035411, self.count=42487 

self.closeSec=1696782299, self.tradeDate='20231009', self.openTime='002000', self.closeTime='002459', self.symbol='BTCUSDT', self.open=27888.4, self.close=27863.9, self.high=27895.0, self.low=27863.9 
127.0.0.1 - - [09/Oct/2023 00:25:00] "POST / HTTP/1.1" 200 -


## /root/FIL/strategy/logic/log.txt ----- -----

2023-10-09 00:00:17,528:DEBUG:logic:main.py:463:getModel:2218526: df_s.iloc[-5:,:] :
          date closeTime     open  ...    alpha58   alpha67   alpha72
5801  20231008    212959  27797.6  ...  51.666667  0.500624  0.666244
5802  20231008    215959  27860.6  ...  51.666667  0.513297  0.651333
5803  20231008    222959  27898.1  ...  51.666667  0.502621  0.642672
5804  20231008    225959  27865.2  ...  52.083333  0.518211  0.626575
5805  20231008    232959  27917.0  ...  51.666667  0.512471  0.614357

[5 rows x 33 columns]
0.5477941176470589
acc is : 0.5477941176470589
2023-10-09 00:00:17,587:INFO:logic:main.py:468:getModel:2218526: df_pred.iloc[-5:,:] :
     pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
539     0  0.516794  0.483206       1  ...  0.954082   1.0    0.0  1.063534
540     0  0.512522  0.487478       0  ...  0.952974   1.0    0.0  1.062298
541     1  0.491553  0.508447       1  ...  0.954663   1.0    0.0  1.064182
542     0  0.515960  0.484040       0  ...  0.954072   1.0    0.0  1.063522
543     1  0.498096  0.501904       0  ...  0.953518   1.0    0.0  1.062905

[5 rows x 10 columns]
2023-10-09 00:00:17,598:INFO:logic:main.py:478:getModel:2218526: df_panel.iloc[-5:,:] :
    pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
45     0  0.516864  0.483136       1  ...  0.954082   1.0    0.0  1.063890
46     0  0.512545  0.487455       0  ...  0.952974   1.0    0.0  1.061813
47     1  0.491694  0.508306       1  ...  0.954663   1.0    0.0  1.064368
48     0  0.516085  0.483915       0  ...  0.954072   1.0    0.0  1.063709
49     1  0.498096  0.501904       0  ...  0.953518   1.0    0.0  1.062905

[5 rows x 10 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '23.669', 'enterprice': '27936.3', 'countrevence': '0', 'unrealprofit': '-1243.55369857926', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '27883.76065746', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}


## /root/FIL/strategy/modifiedmom/log.txt ----- -----


--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=21239 

self.closeSec=1696778999, self.tradeDate='20231008', self.openTime='232000', self.closeTime='232959', self.symbol='BTCUSDT', self.open='27906.3', self.close='27899.8'
127.0.0.1 - - [08/Oct/2023 23:30:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=21240 

self.closeSec=1696779599, self.tradeDate='20231008', self.openTime='233000', self.closeTime='233959', self.symbol='BTCUSDT', self.open='27899.9', self.close='27895.7'
127.0.0.1 - - [08/Oct/2023 23:40:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=21241 

self.closeSec=1696780199, self.tradeDate='20231008', self.openTime='234000', self.closeTime='234959', self.symbol='BTCUSDT', self.open='27895.7', self.close='27880.6'
127.0.0.1 - - [08/Oct/2023 23:50:01] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [09/Oct/2023 00:00:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=21242 

self.closeSec=1696780799, self.tradeDate='20231008', self.openTime='235000', self.closeTime='235959', self.symbol='BTCUSDT', self.open='27880.6', self.close='27883.6'

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=21243 

self.closeSec=1696781399, self.tradeDate='20231009', self.openTime='000000', self.closeTime='000959', self.symbol='BTCUSDT', self.open='27883.5', self.close='27904.8'
127.0.0.1 - - [09/Oct/2023 00:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=21244 

self.closeSec=1696781999, self.tradeDate='20231009', self.openTime='001000', self.closeTime='001959', self.symbol='BTCUSDT', self.open='27904.8', self.close='27888.4'
127.0.0.1 - - [09/Oct/2023 00:20:05] "POST / HTTP/1.1" 200 -


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


--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=21242 

self.closeSec=1696778999, self.tradeDate='20231008', self.openTime='232000', self.closeTime='232959', self.symbol='BTCUSDT', self.open='27906.3', self.close='27899.8'
127.0.0.1 - - [08/Oct/2023 23:30:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=21243 

self.closeSec=1696779599, self.tradeDate='20231008', self.openTime='233000', self.closeTime='233959', self.symbol='BTCUSDT', self.open='27899.9', self.close='27895.7'
127.0.0.1 - - [08/Oct/2023 23:40:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=21244 

self.closeSec=1696780199, self.tradeDate='20231008', self.openTime='234000', self.closeTime='234959', self.symbol='BTCUSDT', self.open='27895.7', self.close='27880.6'
127.0.0.1 - - [08/Oct/2023 23:50:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=21245 

self.closeSec=1696780799, self.tradeDate='20231008', self.openTime='235000', self.closeTime='235959', self.symbol='BTCUSDT', self.open='27880.6', self.close='27883.6'
127.0.0.1 - - [09/Oct/2023 00:00:01] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [09/Oct/2023 00:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=21246 

self.closeSec=1696781399, self.tradeDate='20231009', self.openTime='000000', self.closeTime='000959', self.symbol='BTCUSDT', self.open='27883.5', self.close='27904.8'

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=21247 

self.closeSec=1696781999, self.tradeDate='20231009', self.openTime='001000', self.closeTime='001959', self.symbol='BTCUSDT', self.open='27904.8', self.close='27888.4'
127.0.0.1 - - [09/Oct/2023 00:20:05] "POST / HTTP/1.1" 200 -


## /root/FIL/strategy/similarity/log.txt ----- -----

127.0.0.1 - - [08/Oct/2023 23:30:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=21242 

self.closeSec=1696778999, self.tradeDate='20231008', self.openTime='232000', self.closeTime='232959', self.symbol='BTCUSDT', self.open='27906.3', self.close='27899.8'
127.0.0.1 - - [08/Oct/2023 23:40:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=21243 

self.closeSec=1696779599, self.tradeDate='20231008', self.openTime='233000', self.closeTime='233959', self.symbol='BTCUSDT', self.open='27899.9', self.close='27895.7'

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=21244 

self.closeSec=1696780199, self.tradeDate='20231008', self.openTime='234000', self.closeTime='234959', self.symbol='BTCUSDT', self.open='27895.7', self.close='27880.6'
127.0.0.1 - - [08/Oct/2023 23:50:01] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [09/Oct/2023 00:00:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=21245 

self.closeSec=1696780799, self.tradeDate='20231008', self.openTime='235000', self.closeTime='235959', self.symbol='BTCUSDT', self.open='27880.6', self.close='27883.6'
127.0.0.1 - - [09/Oct/2023 00:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=21246 

self.closeSec=1696781399, self.tradeDate='20231009', self.openTime='000000', self.closeTime='000959', self.symbol='BTCUSDT', self.open='27883.5', self.close='27904.8'

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=21247 

self.closeSec=1696781999, self.tradeDate='20231009', self.openTime='001000', self.closeTime='001959', self.symbol='BTCUSDT', self.open='27904.8', self.close='27888.4'
127.0.0.1 - - [09/Oct/2023 00:20:05] "POST / HTTP/1.1" 200 -


## /root/FIL/strategy/sr_min/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=1, self.total=996015.990996, self.flagDict['side']='buy', self.tradeCount=1, self.count=42484
self.closeSec=1696781999, self.tradeDate='20231009', self.openTime='001500', self.closeTime='001959', self.symbol='BTCUSDT', self.open=27880.0, self.close=27888.4, self.high=27896.4, self.low=27875.3, self.vol=365.319, self.amt=10186407.6797 
127.0.0.1 - - [09/Oct/2023 00:20:02] "POST / HTTP/1.1" 200 -
2023-10-09 00:20:06,663:INFO:sr_min:main.py:172:handleKline:2219263: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5759  20231008   235500    235959  ...         0.0        0.0       0
5760  20231009   000000    000459  ...         0.0        0.0       0
5761  20231009   000500    000959  ...         0.0        0.0       0
5762  20231009   001000    001459  ...         0.0        0.0       0
5763  20231009   001500    001959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-10-09 00:20:06,691:INFO:sr_min:main.py:175:handleKline:2219263: self.closeSec=1696781999, self.tradeDate='20231009', self.openTime='001500', self.closeTime='001959',self.symbol='BTCUSDT',self.open=27880.0, self.close=27888.4, self.high=27896.4, self.low=27875.3, self.vol=365.319, self.amt=10186407.6797, ukdf['pct'].iloc[-1]=0.000301 , ukdf['amount'].iloc[-1]=10186407.6797, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5763, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '37.141', 'enterprice': '26844', 'countrevence': '0', 'unrealprofit': '38838.54137702994', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '27889.70532234', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=1
127.0.0.1 - - [09/Oct/2023 00:25:00] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=1, self.total=996015.990996, self.flagDict['side']='buy', self.tradeCount=1, self.count=42485
self.closeSec=1696782299, self.tradeDate='20231009', self.openTime='002000', self.closeTime='002459', self.symbol='BTCUSDT', self.open=27888.4, self.close=27863.9, self.high=27895.0, self.low=27863.9, self.vol=810.842, self.amt=22600875.33 
2023-10-09 00:25:00,820:INFO:sr_min:main.py:172:handleKline:2219263: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5760  20231009   000000    000459  ...         0.0        0.0       0
5761  20231009   000500    000959  ...         0.0        0.0       0
5762  20231009   001000    001459  ...         0.0        0.0       0
5763  20231009   001500    001959  ...         0.0        0.0       0
5764  20231009   002000    002459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-10-09 00:25:00,820:INFO:sr_min:main.py:175:handleKline:2219263: self.closeSec=1696782299, self.tradeDate='20231009', self.openTime='002000', self.closeTime='002459',self.symbol='BTCUSDT',self.open=27888.4, self.close=27863.9, self.high=27895.0, self.low=27863.9, self.vol=810.842, self.amt=22600875.33, ukdf['pct'].iloc[-1]=-0.000879 , ukdf['amount'].iloc[-1]=22600875.33, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5764, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '37.141', 'enterprice': '26844', 'countrevence': '0', 'unrealprofit': '37929.97912041429', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '27865.24280769', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=1


## /root/FIL/strategy/s_rsrs/log.txt ----- -----

723  20231008   120000    155959  1696751999  ...    723  0.150071 -1.168478    -1.0
724  20231008   160000    195959  1696766399  ...    724  0.112997 -1.241572    -1.0

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '43.597', 'enterprice': '27944.4', 'countrevence': '0', 'unrealprofit': '6311.10902816511', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '27799.63983237', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-1, self.sign=-1
127.0.0.1 - - [09/Oct/2023 00:00:01] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='s_rsrs', self.symbol='BTCUSDT', interval='4h', intervalSec=14400, wid=25, thd=0.6, self.sign=-1, self.total=1217073.7147932001, self.flagDict['side']='sell', self.tradeCount=32, self.count=885
self.closeSec=1696780799, self.tradeDate='20231008', self.openTime='200000', self.closeTime='235959', self.symbol='BTCUSDT', self.open=27799.2, self.close=27883.6, self.high=27989.8, self.low=27671.0, self.vol=50313.962, self.amt=1401446040.4002 
2023-10-09 00:00:01,510:INFO:s_rsrs:main.py:141:handleKline:2218689: self.closeSec=1696780799, self.tradeDate='20231008', self.openTime='200000', self.closeTime='235959',self.symbol='BTCUSDT',self.open=27799.2, self.close=27883.6, self.high=27989.8, self.low=27671.0, self.vol=50313.962, self.amt=1401446040.4002 
2023-10-09 00:00:01,529:INFO:s_rsrs:main.py:142:handleKline:2218689: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime  ...        vol           amt       pct
721  20231008   040000    075959  ...  10265.905  2.865590e+08  0.003357
722  20231008   080000    115959  ...  23359.950  6.542793e+08  0.003822
723  20231008   120000    155959  ...  28016.932  7.825298e+08 -0.005615
724  20231008   160000    195959  ...  31071.685  8.650403e+08 -0.003345
725  20231008   200000    235959  ...  50313.962  1.401446e+09  0.003040

[5 rows x 11 columns]
2023-10-09 00:00:02,486:INFO:s_rsrs:main.py:151:handleKline:2218689: df_s.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec  ...  index      beta    zscore  signal
721  20231008   040000    075959  1696723199  ...    721  0.187564 -1.120572    -1.0
722  20231008   080000    115959  1696737599  ...    722  0.168992 -1.143476    -1.0
723  20231008   120000    155959  1696751999  ...    723  0.150071 -1.168478    -1.0
724  20231008   160000    195959  1696766399  ...    724  0.112997 -1.241572    -1.0
725  20231008   200000    235959  1696780799  ...    725  0.100098 -1.254552    -1.0

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '43.597', 'enterprice': '27944.4', 'countrevence': '0', 'unrealprofit': '2589.6618', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '27885', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-1, self.sign=-1


