# 20230909 16:26:01

## /root/FIL/strategy/amihud/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=373746.4768026, self.flagDict['side']='sell', self.tradeCount=2, self.count=34036
self.closeSec=1694247599, self.tradeDate='20230909', self.openTime='161500', self.closeTime='161959', self.symbol='BTCUSDT', self.open=25860.0, self.close=25865.5, self.high=25865.6, self.low=25860.0, self.vol=119.916, self.amt=3101269.4704 
127.0.0.1 - - [09/Sep/2023 16:20:02] "POST / HTTP/1.1" 200 -
2023-09-09 16:20:05,606:INFO:amihud:main.py:172:handleKline:2219019: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5951  20230909   155500    155959  ...         0.0        0.0       0
5952  20230909   160000    160459  ...         0.0        0.0       0
5953  20230909   160500    160959  ...         0.0        0.0       0
5954  20230909   161000    161459  ...         0.0        0.0       0
5955  20230909   161500    161959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-09-09 16:20:05,614:INFO:amihud:main.py:175:handleKline:2219019: self.closeSec=1694247599, self.tradeDate='20230909', self.openTime='161500', self.closeTime='161959',self.symbol='BTCUSDT',self.open=25860.0, self.close=25865.5, self.high=25865.6, self.low=25860.0, self.vol=119.916, self.amt=3101269.4704, ukdf['pct'].iloc[-1]=0.000213 , ukdf['amount'].iloc[-1]=3101269.4704, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5955, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '13.926', 'enterprice': '26864.9', 'countrevence': '0', 'unrealprofit': '13912.074', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '25865.9', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1
127.0.0.1 - - [09/Sep/2023 16:25:00] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=373746.4768026, self.flagDict['side']='sell', self.tradeCount=2, self.count=34037
self.closeSec=1694247899, self.tradeDate='20230909', self.openTime='162000', self.closeTime='162459', self.symbol='BTCUSDT', self.open=25865.5, self.close=25879.9, self.high=25880.0, self.low=25865.5, self.vol=283.265, self.amt=7329383.7692 
2023-09-09 16:25:00,787:INFO:amihud:main.py:172:handleKline:2219019: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5952  20230909   160000    160459  ...         0.0        0.0       0
5953  20230909   160500    160959  ...         0.0        0.0       0
5954  20230909   161000    161459  ...         0.0        0.0       0
5955  20230909   161500    161959  ...         0.0        0.0       0
5956  20230909   162000    162459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-09-09 16:25:00,788:INFO:amihud:main.py:175:handleKline:2219019: self.closeSec=1694247899, self.tradeDate='20230909', self.openTime='162000', self.closeTime='162459',self.symbol='BTCUSDT',self.open=25865.5, self.close=25879.9, self.high=25880.0, self.low=25865.5, self.vol=283.265, self.amt=7329383.7692, ukdf['pct'].iloc[-1]=0.000557 , ukdf['amount'].iloc[-1]=7329383.7692, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5956, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '13.926', 'enterprice': '26864.9', 'countrevence': '0', 'unrealprofit': '13715.7174', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '25880', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1


## /root/FIL/strategy/factorcheck/log.txt ----- -----

127.0.0.1 - - [09/Sep/2023 16:00:00] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.714181719035411, self.count=34034 

self.closeSec=1694246399, self.tradeDate='20230909', self.openTime='155500', self.closeTime='155959', self.symbol='BTCUSDT', self.open=25863.7, self.close=25871.0, self.high=25886.6, self.low=25863.7 
127.0.0.1 - - [09/Sep/2023 16:05:00] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.714181719035411, self.count=34035 

self.closeSec=1694246699, self.tradeDate='20230909', self.openTime='160000', self.closeTime='160459', self.symbol='BTCUSDT', self.open=25871.0, self.close=25875.5, self.high=25876.0, self.low=25870.9 
127.0.0.1 - - [09/Sep/2023 16:10:00] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.714181719035411, self.count=34036 

self.closeSec=1694246999, self.tradeDate='20230909', self.openTime='160500', self.closeTime='160959', self.symbol='BTCUSDT', self.open=25875.6, self.close=25865.4, self.high=25875.6, self.low=25865.4 

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.714181719035411, self.count=34037 

self.closeSec=1694247299, self.tradeDate='20230909', self.openTime='161000', self.closeTime='161459', self.symbol='BTCUSDT', self.open=25865.4, self.close=25860.0, self.high=25865.5, self.low=25860.0 
127.0.0.1 - - [09/Sep/2023 16:15:00] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.714181719035411, self.count=34038 

self.closeSec=1694247599, self.tradeDate='20230909', self.openTime='161500', self.closeTime='161959', self.symbol='BTCUSDT', self.open=25860.0, self.close=25865.5, self.high=25865.6, self.low=25860.0 
127.0.0.1 - - [09/Sep/2023 16:20:01] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [09/Sep/2023 16:25:00] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.714181719035411, self.count=34039 

self.closeSec=1694247899, self.tradeDate='20230909', self.openTime='162000', self.closeTime='162459', self.symbol='BTCUSDT', self.open=25865.5, self.close=25879.9, self.high=25880.0, self.low=25865.5 


## /root/FIL/strategy/logic/log.txt ----- -----

2023-09-09 16:00:17,609:DEBUG:logic:main.py:463:getModel:2218526: df_s.iloc[-5:,:] :
          date closeTime     open  ...    alpha58   alpha67   alpha72
5785  20230909    132959  25861.1  ...  51.250000  0.487303  0.636738
5786  20230909    135959  25860.2  ...  51.250000  0.477869  0.627853
5787  20230909    142959  25828.9  ...  51.250000  0.485873  0.611635
5788  20230909    145959  25854.0  ...  51.666667  0.491488  0.591806
5789  20230909    152959  25870.8  ...  51.250000  0.489928  0.574640

[5 rows x 33 columns]
0.5295202952029521
acc is : 0.5295202952029521
2023-09-09 16:00:17,689:INFO:logic:main.py:468:getModel:2218526: df_pred.iloc[-5:,:] :
     pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
537     1  0.482315  0.517685       0  ...  1.065072  -1.0    0.0  0.988598
538     1  0.470132  0.529868       1  ...  1.064091  -1.0    0.0  0.989509
539     1  0.485683  0.514317       1  ...  1.063399  -1.0    0.0  0.990152
540     1  0.484488  0.515512       0  ...  1.063596  -1.0    0.0  0.989969
541     1  0.479142  0.520858       1  ...  1.063387  -1.0    0.0  0.990164

[5 rows x 10 columns]
2023-09-09 16:00:17,705:INFO:logic:main.py:478:getModel:2218526: df_panel.iloc[-5:,:] :
    pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
45     1  0.482286  0.517714       0  ...  1.065072  -1.0    0.0  0.991707
46     1  0.469765  0.530235       1  ...  1.064091  -1.0    0.0  0.989793
47     1  0.485352  0.514648       1  ...  1.063399  -1.0    0.0  0.990968
48     1  0.485104  0.514896       0  ...  1.063596  -1.0    0.0  0.991684
49     1  0.479142  0.520858       1  ...  1.063387  -1.0    0.0  0.990164

[5 rows x 10 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '28.306', 'enterprice': '25771.5', 'countrevence': '0', 'unrealprofit': '-2955.1464', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '25875.9', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}


## /root/FIL/strategy/modifiedmom/log.txt ----- -----


--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=17015 

self.closeSec=1694244599, self.tradeDate='20230909', self.openTime='152000', self.closeTime='152959', self.symbol='BTCUSDT', self.open='25865.4', self.close='25865.9'
127.0.0.1 - - [09/Sep/2023 15:30:01] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [09/Sep/2023 15:40:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=17016 

self.closeSec=1694245199, self.tradeDate='20230909', self.openTime='153000', self.closeTime='153959', self.symbol='BTCUSDT', self.open='25865.9', self.close='25872.4'
127.0.0.1 - - [09/Sep/2023 15:50:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=17017 

self.closeSec=1694245799, self.tradeDate='20230909', self.openTime='154000', self.closeTime='154959', self.symbol='BTCUSDT', self.open='25872.5', self.close='25858'

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=17018 

self.closeSec=1694246399, self.tradeDate='20230909', self.openTime='155000', self.closeTime='155959', self.symbol='BTCUSDT', self.open='25858', self.close='25870.9'
127.0.0.1 - - [09/Sep/2023 16:00:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=17019 

self.closeSec=1694246999, self.tradeDate='20230909', self.openTime='160000', self.closeTime='160959', self.symbol='BTCUSDT', self.open='25871', self.close='25865.4'
127.0.0.1 - - [09/Sep/2023 16:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=17020 

self.closeSec=1694247599, self.tradeDate='20230909', self.openTime='161000', self.closeTime='161959', self.symbol='BTCUSDT', self.open='25865.4', self.close='25865.5'
127.0.0.1 - - [09/Sep/2023 16:20:04] "POST / HTTP/1.1" 200 -


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

127.0.0.1 - - [09/Sep/2023 15:30:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=17018 

self.closeSec=1694244599, self.tradeDate='20230909', self.openTime='152000', self.closeTime='152959', self.symbol='BTCUSDT', self.open='25865.4', self.close='25865.9'

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=17019 

self.closeSec=1694245199, self.tradeDate='20230909', self.openTime='153000', self.closeTime='153959', self.symbol='BTCUSDT', self.open='25865.9', self.close='25872.4'
127.0.0.1 - - [09/Sep/2023 15:40:01] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [09/Sep/2023 15:50:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=17020 

self.closeSec=1694245799, self.tradeDate='20230909', self.openTime='154000', self.closeTime='154959', self.symbol='BTCUSDT', self.open='25872.5', self.close='25858'

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=17021 

self.closeSec=1694246399, self.tradeDate='20230909', self.openTime='155000', self.closeTime='155959', self.symbol='BTCUSDT', self.open='25858', self.close='25870.9'
127.0.0.1 - - [09/Sep/2023 16:00:01] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [09/Sep/2023 16:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=17022 

self.closeSec=1694246999, self.tradeDate='20230909', self.openTime='160000', self.closeTime='160959', self.symbol='BTCUSDT', self.open='25871', self.close='25865.4'

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=17023 

self.closeSec=1694247599, self.tradeDate='20230909', self.openTime='161000', self.closeTime='161959', self.symbol='BTCUSDT', self.open='25865.4', self.close='25865.5'
127.0.0.1 - - [09/Sep/2023 16:20:04] "POST / HTTP/1.1" 200 -


## /root/FIL/strategy/similarity/log.txt ----- -----


--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=17018 

self.closeSec=1694244599, self.tradeDate='20230909', self.openTime='152000', self.closeTime='152959', self.symbol='BTCUSDT', self.open='25865.4', self.close='25865.9'
127.0.0.1 - - [09/Sep/2023 15:30:01] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [09/Sep/2023 15:40:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=17019 

self.closeSec=1694245199, self.tradeDate='20230909', self.openTime='153000', self.closeTime='153959', self.symbol='BTCUSDT', self.open='25865.9', self.close='25872.4'

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=17020 

self.closeSec=1694245799, self.tradeDate='20230909', self.openTime='154000', self.closeTime='154959', self.symbol='BTCUSDT', self.open='25872.5', self.close='25858'
127.0.0.1 - - [09/Sep/2023 15:50:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=17021 

self.closeSec=1694246399, self.tradeDate='20230909', self.openTime='155000', self.closeTime='155959', self.symbol='BTCUSDT', self.open='25858', self.close='25870.9'
127.0.0.1 - - [09/Sep/2023 16:00:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=17022 

self.closeSec=1694246999, self.tradeDate='20230909', self.openTime='160000', self.closeTime='160959', self.symbol='BTCUSDT', self.open='25871', self.close='25865.4'
127.0.0.1 - - [09/Sep/2023 16:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=17023 

self.closeSec=1694247599, self.tradeDate='20230909', self.openTime='161000', self.closeTime='161959', self.symbol='BTCUSDT', self.open='25865.4', self.close='25865.5'
127.0.0.1 - - [09/Sep/2023 16:20:04] "POST / HTTP/1.1" 200 -


## /root/FIL/strategy/sr_min/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=1, self.total=996015.990996, self.flagDict['side']='buy', self.tradeCount=1, self.count=34036
self.closeSec=1694247599, self.tradeDate='20230909', self.openTime='161500', self.closeTime='161959', self.symbol='BTCUSDT', self.open=25860.0, self.close=25865.5, self.high=25865.6, self.low=25860.0, self.vol=119.916, self.amt=3101269.4704 
127.0.0.1 - - [09/Sep/2023 16:20:01] "POST / HTTP/1.1" 200 -
2023-09-09 16:20:05,614:INFO:sr_min:main.py:172:handleKline:2219263: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5951  20230909   155500    155959  ...         0.0        0.0       0
5952  20230909   160000    160459  ...         0.0        0.0       0
5953  20230909   160500    160959  ...         0.0        0.0       0
5954  20230909   161000    161459  ...         0.0        0.0       0
5955  20230909   161500    161959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-09-09 16:20:05,625:INFO:sr_min:main.py:175:handleKline:2219263: self.closeSec=1694247599, self.tradeDate='20230909', self.openTime='161500', self.closeTime='161959',self.symbol='BTCUSDT',self.open=25860.0, self.close=25865.5, self.high=25865.6, self.low=25860.0, self.vol=119.916, self.amt=3101269.4704, ukdf['pct'].iloc[-1]=0.000213 , ukdf['amount'].iloc[-1]=3101269.4704, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5955, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '37.141', 'enterprice': '26844', 'countrevence': '0', 'unrealprofit': '-36327.6121', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '25865.9', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=1
127.0.0.1 - - [09/Sep/2023 16:25:00] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=1, self.total=996015.990996, self.flagDict['side']='buy', self.tradeCount=1, self.count=34037
self.closeSec=1694247899, self.tradeDate='20230909', self.openTime='162000', self.closeTime='162459', self.symbol='BTCUSDT', self.open=25865.5, self.close=25879.9, self.high=25880.0, self.low=25865.5, self.vol=283.265, self.amt=7329383.7692 
2023-09-09 16:25:00,781:INFO:sr_min:main.py:172:handleKline:2219263: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5952  20230909   160000    160459  ...         0.0        0.0       0
5953  20230909   160500    160959  ...         0.0        0.0       0
5954  20230909   161000    161459  ...         0.0        0.0       0
5955  20230909   161500    161959  ...         0.0        0.0       0
5956  20230909   162000    162459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-09-09 16:25:00,781:INFO:sr_min:main.py:175:handleKline:2219263: self.closeSec=1694247899, self.tradeDate='20230909', self.openTime='162000', self.closeTime='162459',self.symbol='BTCUSDT',self.open=25865.5, self.close=25879.9, self.high=25880.0, self.low=25865.5, self.vol=283.265, self.amt=7329383.7692, ukdf['pct'].iloc[-1]=0.000557 , ukdf['amount'].iloc[-1]=7329383.7692, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5956, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '37.141', 'enterprice': '26844', 'countrevence': '0', 'unrealprofit': '-35803.924', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '25880', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=1


## /root/FIL/strategy/s_rsrs/log.txt ----- -----

721  20230909   040000    075959  1694217599  ...    721  0.196249 -0.573734     NaN
722  20230909   080000    115959  1694231999  ...    722  0.183813 -0.608528    -1.0

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '57.177', 'enterprice': '25892.3', 'countrevence': '0', 'unrealprofit': '1486.602', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '25866.3', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-1, self.sign=-1
--handleKline--:  version='2.0.0', self.name='s_rsrs', self.symbol='BTCUSDT', interval='4h', intervalSec=14400, wid=25, thd=0.6, self.sign=-1, self.total=1478963.5930628998, self.flagDict['side']='sell', self.tradeCount=22, self.count=709
self.closeSec=1694246399, self.tradeDate='20230909', self.openTime='120000', self.closeTime='155959', self.symbol='BTCUSDT', self.open=25866.2, self.close=25870.9, self.high=25886.6, self.low=25820.0, self.vol=10439.267, self.amt=269942381.8594 
127.0.0.1 - - [09/Sep/2023 16:00:01] "POST / HTTP/1.1" 200 -
2023-09-09 16:00:01,582:INFO:s_rsrs:main.py:141:handleKline:2218689: self.closeSec=1694246399, self.tradeDate='20230909', self.openTime='120000', self.closeTime='155959',self.symbol='BTCUSDT',self.open=25866.2, self.close=25870.9, self.high=25886.6, self.low=25820.0, self.vol=10439.267, self.amt=269942381.8594 
2023-09-09 16:00:01,597:INFO:s_rsrs:main.py:142:handleKline:2218689: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime  ...        vol           amt       pct
719  20230908   200000    235959  ...  36852.122  9.532067e+08  0.000035
720  20230909   000000    035959  ...  35345.758  9.117171e+08  0.002087
721  20230909   040000    075959  ...  14213.770  3.678833e+08  0.000626
722  20230909   080000    115959  ...  10539.395  2.725723e+08 -0.001297
723  20230909   120000    155959  ...  10439.267  2.699424e+08  0.000178

[5 rows x 11 columns]
2023-09-09 16:00:02,356:INFO:s_rsrs:main.py:151:handleKline:2218689: df_s.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec  ...  index      beta    zscore  signal
719  20230908   200000    235959  1694188799  ...    719  0.206120 -0.544597     NaN
720  20230909   000000    035959  1694203199  ...    720  0.205611 -0.546965     NaN
721  20230909   040000    075959  1694217599  ...    721  0.196249 -0.573734     NaN
722  20230909   080000    115959  1694231999  ...    722  0.183813 -0.608528    -1.0
723  20230909   120000    155959  1694246399  ...    723  0.172586 -0.639120    -1.0

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '57.177', 'enterprice': '25892.3', 'countrevence': '0', 'unrealprofit': '1050.4634885649', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '25873.9278663', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-1, self.sign=-1


