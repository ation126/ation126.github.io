# 20230511 00:26:01

## /root/FIL/strategy/amihud/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=993672.4896432, self.flagDict['side']='sell', self.tradeCount=2, self.count=47349
self.closeSec=1683735599, self.tradeDate='20230511', self.openTime='001500', self.closeTime='001959', self.symbol='BTCUSDT', self.open=28209.9, self.close=28253.4, self.high=28280.0, self.low=28170.2, self.vol=5073.078, self.amt=143256492.4851 
127.0.0.1 - - [11/May/2023 00:20:02] "POST / HTTP/1.1" 200 -
2023-05-11 00:20:06,617:INFO:amihud:main.py:172:handleKline:200676: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5759  20230510   235500    235959  ...         0.0        0.0       0
5760  20230511   000000    000459  ...         0.0        0.0       0
5761  20230511   000500    000959  ...         0.0        0.0       0
5762  20230511   001000    001459  ...         0.0        0.0       0
5763  20230511   001500    001959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-05-11 00:20:06,626:INFO:amihud:main.py:175:handleKline:200676: self.closeSec=1683735599, self.tradeDate='20230511', self.openTime='001500', self.closeTime='001959',self.symbol='BTCUSDT',self.open=28209.9, self.close=28253.4, self.high=28280.0, self.low=28170.2, self.vol=5073.078, self.amt=143256492.4851, ukdf['pct'].iloc[-1]=0.001538 , ukdf['amount'].iloc[-1]=143256492.4851, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5763, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '60.176', 'enterprice': '16529.3', 'countrevence': '0', 'unrealprofit': '-705196.86916069072', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '28248.20569597', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1
--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=993672.4896432, self.flagDict['side']='sell', self.tradeCount=2, self.count=47350
self.closeSec=1683735899, self.tradeDate='20230511', self.openTime='002000', self.closeTime='002459', self.symbol='BTCUSDT', self.open=28253.4, self.close=28232.9, self.high=28253.5, self.low=28176.3, self.vol=3621.794, self.amt=102210472.9184 
127.0.0.1 - - [11/May/2023 00:25:02] "POST / HTTP/1.1" 200 -
2023-05-11 00:25:02,157:INFO:amihud:main.py:172:handleKline:200676: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5760  20230511   000000    000459  ...         0.0        0.0       0
5761  20230511   000500    000959  ...         0.0        0.0       0
5762  20230511   001000    001459  ...         0.0        0.0       0
5763  20230511   001500    001959  ...         0.0        0.0       0
5764  20230511   002000    002459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-05-11 00:25:02,157:INFO:amihud:main.py:175:handleKline:200676: self.closeSec=1683735899, self.tradeDate='20230511', self.openTime='002000', self.closeTime='002459',self.symbol='BTCUSDT',self.open=28253.4, self.close=28232.9, self.high=28253.5, self.low=28176.3, self.vol=3621.794, self.amt=102210472.9184, ukdf['pct'].iloc[-1]=-0.000726 , ukdf['amount'].iloc[-1]=102210472.9184, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5764, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '60.176', 'enterprice': '16529.3', 'countrevence': '0', 'unrealprofit': '-704269.816', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '28232.8', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1


## /root/FIL/strategy/factorcheck/log.txt ----- -----

127.0.0.1 - - [11/May/2023 00:05:02] "POST / HTTP/1.1" 200 -

--ukdf-hist--: overDate='20230506' 
 Empty DataFrame
Columns: [tradeDate, openTime, closeTime, closeSec, open, close, high, low, pct, index, idx]
Index: [] 
 Empty DataFrame
Columns: [tradeDate, openTime, closeTime, closeSec, open, close, high, low, pct, index, idx]
Index: [] 

127.0.0.1 - - [11/May/2023 00:10:02] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=23, self.factor=0.43541661550691446, self.count=47913 

self.closeSec=1683734999, self.tradeDate='20230511', self.openTime='000500', self.closeTime='000959', self.symbol='BTCUSDT', self.open=28159.1, self.close=28145.0, self.high=28160.8, self.low=28132.1 

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=23, self.factor=0.43541661550691446, self.count=47914 

self.closeSec=1683735299, self.tradeDate='20230511', self.openTime='001000', self.closeTime='001459', self.symbol='BTCUSDT', self.open=28145.0, self.close=28210.0, self.high=28240.0, self.low=28134.2 
127.0.0.1 - - [11/May/2023 00:15:03] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=23, self.factor=0.43541661550691446, self.count=47915 

self.closeSec=1683735599, self.tradeDate='20230511', self.openTime='001500', self.closeTime='001959', self.symbol='BTCUSDT', self.open=28209.9, self.close=28253.4, self.high=28280.0, self.low=28170.2 
127.0.0.1 - - [11/May/2023 00:20:02] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=23, self.factor=0.43541661550691446, self.count=47916 

self.closeSec=1683735899, self.tradeDate='20230511', self.openTime='002000', self.closeTime='002459', self.symbol='BTCUSDT', self.open=28253.4, self.close=28232.9, self.high=28253.5, self.low=28176.3 
127.0.0.1 - - [11/May/2023 00:25:02] "POST / HTTP/1.1" 200 -


## /root/FIL/strategy/logic/log.txt ----- -----

2023-05-11 00:00:20,719:DEBUG:logic:main.py:463:getModel:885513: df_s.iloc[-5:,:] :
          date closeTime     open  ...    alpha58   alpha67   alpha72
5801  20230510    212959  28160.2  ...  49.166667  0.557980  0.410326
5802  20230510    215959  28090.0  ...  49.166667  0.567930  0.394355
5803  20230510    222959  28153.8  ...  49.583333  0.572882  0.376890
5804  20230510    225959  28186.0  ...  49.166667  0.551279  0.369162
5805  20230510    232959  28077.9  ...  49.166667  0.553872  0.360654

[5 rows x 33 columns]
0.5459558823529411
acc is : 0.5459558823529411
2023-05-11 00:00:20,810:INFO:logic:main.py:468:getModel:885513: df_pred.iloc[-5:,:] :
     pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
539     0  0.524019  0.475981       1  ...  1.033077   1.0    0.0  0.959767
540     0  0.550081  0.449919       1  ...  1.034259   1.0    0.0  0.960864
541     0  0.540726  0.459274       0  ...  1.030300   1.0    0.0  0.957186
542     0  0.504940  0.495060       1  ...  1.030898   1.0    0.0  0.957742
543     1  0.490674  0.509326       1  ...  1.032619   1.0    0.0  0.959341

[5 rows x 10 columns]
2023-05-11 00:00:20,824:INFO:logic:main.py:478:getModel:885513: df_panel.iloc[-5:,:] :
    pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
45     0  0.524235  0.475765       1  ...  1.033077   1.0    0.0  0.960775
46     0  0.549930  0.450070       1  ...  1.034259   1.0    0.0  0.961448
47     0  0.540869  0.459131       0  ...  1.030300   1.0    0.0  0.958061
48     0  0.505120  0.494880       1  ...  1.030898   1.0    0.0  0.958618
49     1  0.490674  0.509326       1  ...  1.032619   1.0    0.0  0.959341

[5 rows x 10 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': []}


## /root/FIL/strategy/modifiedmom/log.txt ----- -----


--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=23953 

self.closeSec=1683732599, self.tradeDate='20230510', self.openTime='232000', self.closeTime='232959', self.symbol='BTCUSDT', self.open='28068.6', self.close='28094.3'
127.0.0.1 - - [10/May/2023 23:30:03] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=23954 

self.closeSec=1683733199, self.tradeDate='20230510', self.openTime='233000', self.closeTime='233959', self.symbol='BTCUSDT', self.open='28094.4', self.close='28169.5'
127.0.0.1 - - [10/May/2023 23:40:02] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [10/May/2023 23:50:02] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=23955 

self.closeSec=1683733799, self.tradeDate='20230510', self.openTime='234000', self.closeTime='234959', self.symbol='BTCUSDT', self.open='28169.6', self.close='28176'

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=23956 

self.closeSec=1683734399, self.tradeDate='20230510', self.openTime='235000', self.closeTime='235959', self.symbol='BTCUSDT', self.open='28176', self.close='28141.2'
127.0.0.1 - - [11/May/2023 00:00:03] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [11/May/2023 00:10:02] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=23957 

self.closeSec=1683734999, self.tradeDate='20230511', self.openTime='000000', self.closeTime='000959', self.symbol='BTCUSDT', self.open='28141.2', self.close='28145'

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=23958 

self.closeSec=1683735599, self.tradeDate='20230511', self.openTime='001000', self.closeTime='001959', self.symbol='BTCUSDT', self.open='28145', self.close='28253.4'
127.0.0.1 - - [11/May/2023 00:20:05] "POST / HTTP/1.1" 200 -


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


--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=23954 

self.closeSec=1683732599, self.tradeDate='20230510', self.openTime='232000', self.closeTime='232959', self.symbol='BTCUSDT', self.open='28068.6', self.close='28094.3'
127.0.0.1 - - [10/May/2023 23:30:03] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=23955 

self.closeSec=1683733199, self.tradeDate='20230510', self.openTime='233000', self.closeTime='233959', self.symbol='BTCUSDT', self.open='28094.4', self.close='28169.5'
127.0.0.1 - - [10/May/2023 23:40:02] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=23956 

self.closeSec=1683733799, self.tradeDate='20230510', self.openTime='234000', self.closeTime='234959', self.symbol='BTCUSDT', self.open='28169.6', self.close='28176'
127.0.0.1 - - [10/May/2023 23:50:02] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=23957 

self.closeSec=1683734399, self.tradeDate='20230510', self.openTime='235000', self.closeTime='235959', self.symbol='BTCUSDT', self.open='28176', self.close='28141.2'
127.0.0.1 - - [11/May/2023 00:00:03] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=23958 

self.closeSec=1683734999, self.tradeDate='20230511', self.openTime='000000', self.closeTime='000959', self.symbol='BTCUSDT', self.open='28141.2', self.close='28145'
127.0.0.1 - - [11/May/2023 00:10:02] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=23959 

self.closeSec=1683735599, self.tradeDate='20230511', self.openTime='001000', self.closeTime='001959', self.symbol='BTCUSDT', self.open='28145', self.close='28253.4'
127.0.0.1 - - [11/May/2023 00:20:05] "POST / HTTP/1.1" 200 -


## /root/FIL/strategy/similarity/log.txt ----- -----


--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=23954 

self.closeSec=1683732599, self.tradeDate='20230510', self.openTime='232000', self.closeTime='232959', self.symbol='BTCUSDT', self.open='28068.6', self.close='28094.3'
127.0.0.1 - - [10/May/2023 23:30:03] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=23955 

self.closeSec=1683733199, self.tradeDate='20230510', self.openTime='233000', self.closeTime='233959', self.symbol='BTCUSDT', self.open='28094.4', self.close='28169.5'
127.0.0.1 - - [10/May/2023 23:40:02] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=23956 

self.closeSec=1683733799, self.tradeDate='20230510', self.openTime='234000', self.closeTime='234959', self.symbol='BTCUSDT', self.open='28169.6', self.close='28176'
127.0.0.1 - - [10/May/2023 23:50:02] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [11/May/2023 00:00:03] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=23957 

self.closeSec=1683734399, self.tradeDate='20230510', self.openTime='235000', self.closeTime='235959', self.symbol='BTCUSDT', self.open='28176', self.close='28141.2'
127.0.0.1 - - [11/May/2023 00:10:02] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=23958 

self.closeSec=1683734999, self.tradeDate='20230511', self.openTime='000000', self.closeTime='000959', self.symbol='BTCUSDT', self.open='28141.2', self.close='28145'

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=23959 

self.closeSec=1683735599, self.tradeDate='20230511', self.openTime='001000', self.closeTime='001959', self.symbol='BTCUSDT', self.open='28145', self.close='28253.4'
127.0.0.1 - - [11/May/2023 00:20:05] "POST / HTTP/1.1" 200 -


## /root/FIL/strategy/sr_min/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=0, self.total=1000000.0, self.flagDict['side']='', self.tradeCount=0, self.count=43347
self.closeSec=1683735599, self.tradeDate='20230511', self.openTime='001500', self.closeTime='001959', self.symbol='BTCUSDT', self.open=28209.9, self.close=28253.4, self.high=28280.0, self.low=28170.2, self.vol=5073.078, self.amt=143256492.4851 
127.0.0.1 - - [11/May/2023 00:20:02] "POST / HTTP/1.1" 200 -
2023-05-11 00:20:06,413:INFO:sr_min:main.py:172:handleKline:449472: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5759  20230510   235500    235959  ...         0.0        0.0       0
5760  20230511   000000    000459  ...         0.0        0.0       0
5761  20230511   000500    000959  ...         0.0        0.0       0
5762  20230511   001000    001459  ...         0.0        0.0       0
5763  20230511   001500    001959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-05-11 00:20:06,425:INFO:sr_min:main.py:175:handleKline:449472: self.closeSec=1683735599, self.tradeDate='20230511', self.openTime='001500', self.closeTime='001959',self.symbol='BTCUSDT',self.open=28209.9, self.close=28253.4, self.high=28280.0, self.low=28170.2, self.vol=5073.078, self.amt=143256492.4851, ukdf['pct'].iloc[-1]=0.001538 , ukdf['amount'].iloc[-1]=143256492.4851, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5763, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': []}
type(curSign)=<class 'int'>, curSign=0, self.sign=0
127.0.0.1 - - [11/May/2023 00:25:02] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=0, self.total=1000000.0, self.flagDict['side']='', self.tradeCount=0, self.count=43348
self.closeSec=1683735899, self.tradeDate='20230511', self.openTime='002000', self.closeTime='002459', self.symbol='BTCUSDT', self.open=28253.4, self.close=28232.9, self.high=28253.5, self.low=28176.3, self.vol=3621.794, self.amt=102210472.9184 
2023-05-11 00:25:02,162:INFO:sr_min:main.py:172:handleKline:449472: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5760  20230511   000000    000459  ...         0.0        0.0       0
5761  20230511   000500    000959  ...         0.0        0.0       0
5762  20230511   001000    001459  ...         0.0        0.0       0
5763  20230511   001500    001959  ...         0.0        0.0       0
5764  20230511   002000    002459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-05-11 00:25:02,162:INFO:sr_min:main.py:175:handleKline:449472: self.closeSec=1683735899, self.tradeDate='20230511', self.openTime='002000', self.closeTime='002459',self.symbol='BTCUSDT',self.open=28253.4, self.close=28232.9, self.high=28253.5, self.low=28176.3, self.vol=3621.794, self.amt=102210472.9184, ukdf['pct'].iloc[-1]=-0.000726 , ukdf['amount'].iloc[-1]=102210472.9184, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5764, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': []}
type(curSign)=<class 'int'>, curSign=0, self.sign=0


## /root/FIL/strategy/s_rsrs/log.txt ----- -----

723  20230510   120000    155959  1683705599  ...    723  0.834112  1.055339     1.0
724  20230510   160000    195959  1683719999  ...    724  0.874225  1.167903     1.0

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '52.501', 'enterprice': '27610.1', 'countrevence': '0', 'unrealprofit': '2929.5558', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '27665.9', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=1, self.sign=1
127.0.0.1 - - [11/May/2023 00:00:03] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='s_rsrs', self.symbol='BTCUSDT', interval='4h', intervalSec=14400, wid=25, thd=0.6, self.sign=1, self.total=1448108.3022399, self.flagDict['side']='buy', self.tradeCount=34, self.count=998
self.closeSec=1683734399, self.tradeDate='20230510', self.openTime='200000', self.closeTime='235959', self.symbol='BTCUSDT', self.open=27660.6, self.close=28141.2, self.high=28297.0, self.low=27623.4, self.vol=213950.08, self.amt=6001231621.83083 
2023-05-11 00:00:03,240:INFO:s_rsrs:main.py:141:handleKline:185271: self.closeSec=1683734399, self.tradeDate='20230510', self.openTime='200000', self.closeTime='235959',self.symbol='BTCUSDT',self.open=27660.6, self.close=28141.2, self.high=28297.0, self.low=27623.4, self.vol=213950.08, self.amt=6001231621.83083 
2023-05-11 00:00:03,282:INFO:s_rsrs:main.py:142:handleKline:185271: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime  ...         vol           amt       pct
721  20230510   040000    075959  ...   33703.303  9.309797e+08 -0.003411
722  20230510   080000    115959  ...   47318.156  1.311215e+09  0.002122
723  20230510   120000    155959  ...   32310.414  8.918974e+08 -0.004930
724  20230510   160000    195959  ...   39879.662  1.099456e+09  0.004660
725  20230510   200000    235959  ...  213950.080  6.001232e+09  0.017371

[5 rows x 11 columns]
2023-05-11 00:00:04,575:INFO:s_rsrs:main.py:151:handleKline:185271: df_s.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec  ...  index      beta    zscore  signal
721  20230510   040000    075959  1683676799  ...    721  0.831298  1.080613     1.0
722  20230510   080000    115959  1683691199  ...    722  0.860986  1.164174     1.0
723  20230510   120000    155959  1683705599  ...    723  0.834112  1.055339     1.0
724  20230510   160000    195959  1683719999  ...    724  0.874225  1.167903     1.0
725  20230510   200000    235959  1683734399  ...    725  0.862802  1.105271     1.0

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '52.501', 'enterprice': '27610.1', 'countrevence': '0', 'unrealprofit': '27883.2811', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '28141.2', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=1, self.sign=1


