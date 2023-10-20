# 20231020 16:26:02

## /root/FIL/strategy/amihud/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=373746.4768026, self.flagDict['side']='sell', self.tradeCount=2, self.count=45844
self.closeSec=1697789999, self.tradeDate='20231020', self.openTime='161500', self.closeTime='161959', self.symbol='BTCUSDT', self.open=29344.7, self.close=29427.5, self.high=29491.6, self.low=29317.8, self.vol=7805.025, self.amt=229665987.06997 
127.0.0.1 - - [20/Oct/2023 16:20:05] "POST / HTTP/1.1" 200 -
2023-10-20 16:20:08,952:INFO:amihud:main.py:172:handleKline:2219019: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5951  20231020   155500    155959  ...         0.0        0.0       0
5952  20231020   160000    160459  ...         0.0        0.0       0
5953  20231020   160500    160959  ...         0.0        0.0       0
5954  20231020   161000    161459  ...         0.0        0.0       0
5955  20231020   161500    161959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-10-20 16:20:08,959:INFO:amihud:main.py:175:handleKline:2219019: self.closeSec=1697789999, self.tradeDate='20231020', self.openTime='161500', self.closeTime='161959',self.symbol='BTCUSDT',self.open=29344.7, self.close=29427.5, self.high=29491.6, self.low=29317.8, self.vol=7805.025, self.amt=229665987.06997, ukdf['pct'].iloc[-1]=0.002822 , ukdf['amount'].iloc[-1]=229665987.06997, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5955, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '13.926', 'enterprice': '26864.9', 'countrevence': '0', 'unrealprofit': '-35721.5826', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '29430', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1
--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=373746.4768026, self.flagDict['side']='sell', self.tradeCount=2, self.count=45845
self.closeSec=1697790299, self.tradeDate='20231020', self.openTime='162000', self.closeTime='162459', self.symbol='BTCUSDT', self.open=29422.8, self.close=29420.0, self.high=29430.0, self.low=29376.6, self.vol=1761.689, self.amt=51796578.9595 
127.0.0.1 - - [20/Oct/2023 16:25:01] "POST / HTTP/1.1" 200 -
2023-10-20 16:25:03,188:INFO:amihud:main.py:172:handleKline:2219019: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5952  20231020   160000    160459  ...         0.0        0.0       0
5953  20231020   160500    160959  ...         0.0        0.0       0
5954  20231020   161000    161459  ...         0.0        0.0       0
5955  20231020   161500    161959  ...         0.0        0.0       0
5956  20231020   162000    162459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-10-20 16:25:03,191:INFO:amihud:main.py:175:handleKline:2219019: self.closeSec=1697790299, self.tradeDate='20231020', self.openTime='162000', self.closeTime='162459',self.symbol='BTCUSDT',self.open=29422.8, self.close=29420.0, self.high=29430.0, self.low=29376.6, self.vol=1761.689, self.amt=51796578.9595, ukdf['pct'].iloc[-1]=-0.000255 , ukdf['amount'].iloc[-1]=51796578.9595, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5956, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '13.926', 'enterprice': '26864.9', 'countrevence': '0', 'unrealprofit': '-35586.5004', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '29420.3', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1


## /root/FIL/strategy/factorcheck/log.txt ----- -----

127.0.0.1 - - [20/Oct/2023 16:00:00] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.714181719035411, self.count=45842 

self.closeSec=1697788799, self.tradeDate='20231020', self.openTime='155500', self.closeTime='155959', self.symbol='BTCUSDT', self.open=29244.5, self.close=29228.5, self.high=29244.5, self.low=29205.4 

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.714181719035411, self.count=45843 

self.closeSec=1697789099, self.tradeDate='20231020', self.openTime='160000', self.closeTime='160459', self.symbol='BTCUSDT', self.open=29228.6, self.close=29251.5, self.high=29256.0, self.low=29214.4 
127.0.0.1 - - [20/Oct/2023 16:05:00] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [20/Oct/2023 16:10:00] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.714181719035411, self.count=45844 

self.closeSec=1697789399, self.tradeDate='20231020', self.openTime='160500', self.closeTime='160959', self.symbol='BTCUSDT', self.open=29251.9, self.close=29349.3, self.high=29376.9, self.low=29251.8 
127.0.0.1 - - [20/Oct/2023 16:15:00] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.714181719035411, self.count=45845 

self.closeSec=1697789699, self.tradeDate='20231020', self.openTime='161000', self.closeTime='161459', self.symbol='BTCUSDT', self.open=29349.2, self.close=29344.7, self.high=29390.4, self.low=29328.0 

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.714181719035411, self.count=45846 

self.closeSec=1697789999, self.tradeDate='20231020', self.openTime='161500', self.closeTime='161959', self.symbol='BTCUSDT', self.open=29344.7, self.close=29427.5, self.high=29491.6, self.low=29317.8 
127.0.0.1 - - [20/Oct/2023 16:20:05] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.714181719035411, self.count=45847 

self.closeSec=1697790299, self.tradeDate='20231020', self.openTime='162000', self.closeTime='162459', self.symbol='BTCUSDT', self.open=29422.8, self.close=29420.0, self.high=29430.0, self.low=29376.6 
127.0.0.1 - - [20/Oct/2023 16:25:01] "POST / HTTP/1.1" 200 -


## /root/FIL/strategy/logic/log.txt ----- -----

2023-10-20 16:00:18,246:DEBUG:logic:main.py:463:getModel:2218526: df_s.iloc[-5:,:] :
          date closeTime     open  ...    alpha58   alpha67   alpha72
5785  20231020    132959  29307.0  ...  52.916667  0.605953  0.287525
5786  20231020    135959  29144.0  ...  53.333333  0.614470  0.280532
5787  20231020    142959  29209.6  ...  53.333333  0.609841  0.275820
5788  20231020    145959  29187.3  ...  53.333333  0.620299  0.266208
5789  20231020    152959  29267.3  ...  53.333333  0.612582  0.259672

[5 rows x 33 columns]
0.5756457564575646
acc is : 0.5756457564575646
2023-10-20 16:00:18,345:INFO:logic:main.py:468:getModel:2218526: df_pred.iloc[-5:,:] :
     pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
537     1  0.479930  0.520070       1  ...  0.946228   1.0    0.0  1.050376
538     0  0.524347  0.475653       0  ...  0.945505   1.0    0.0  1.049574
539     0  0.503299  0.496701       1  ...  0.948094   1.0    0.0  1.052447
540     0  0.531848  0.468152       0  ...  0.946902   1.0    0.0  1.051124
541     1  0.498113  0.501887       0  ...  0.946837   1.0    0.0  1.051052

[5 rows x 10 columns]
2023-10-20 16:00:18,365:INFO:logic:main.py:478:getModel:2218526: df_panel.iloc[-5:,:] :
    pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
45     1  0.480119  0.519881       1  ...  0.946228   1.0    0.0  1.046808
46     0  0.524369  0.475631       0  ...  0.945505   1.0    0.0  1.046290
47     0  0.503291  0.496709       1  ...  0.948094   1.0    0.0  1.048958
48     0  0.531848  0.468152       0  ...  0.946902   1.0    0.0  1.051272
49     1  0.498113  0.501887       0  ...  0.946837   1.0    0.0  1.051052

[5 rows x 10 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '21.528', 'enterprice': '28565.1', 'countrevence': '0', 'unrealprofit': '14298.97385475936', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '29229.30354212', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}


## /root/FIL/strategy/modifiedmom/log.txt ----- -----

127.0.0.1 - - [20/Oct/2023 15:30:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=22919 

self.closeSec=1697786999, self.tradeDate='20231020', self.openTime='152000', self.closeTime='152959', self.symbol='BTCUSDT', self.open='29260', self.close='29230.5'
127.0.0.1 - - [20/Oct/2023 15:40:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=22920 

self.closeSec=1697787599, self.tradeDate='20231020', self.openTime='153000', self.closeTime='153959', self.symbol='BTCUSDT', self.open='29230.6', self.close='29262.6'

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=22921 

self.closeSec=1697788199, self.tradeDate='20231020', self.openTime='154000', self.closeTime='154959', self.symbol='BTCUSDT', self.open='29262.6', self.close='29304.9'
127.0.0.1 - - [20/Oct/2023 15:50:01] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [20/Oct/2023 16:00:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=22922 

self.closeSec=1697788799, self.tradeDate='20231020', self.openTime='155000', self.closeTime='155959', self.symbol='BTCUSDT', self.open='29306.9', self.close='29228.5'

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=22923 

self.closeSec=1697789399, self.tradeDate='20231020', self.openTime='160000', self.closeTime='160959', self.symbol='BTCUSDT', self.open='29228.6', self.close='29349.3'
127.0.0.1 - - [20/Oct/2023 16:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=22924 

self.closeSec=1697789999, self.tradeDate='20231020', self.openTime='161000', self.closeTime='161959', self.symbol='BTCUSDT', self.open='29349.2', self.close='29422.8'
127.0.0.1 - - [20/Oct/2023 16:20:06] "POST / HTTP/1.1" 200 -


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


--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=22922 

self.closeSec=1697786999, self.tradeDate='20231020', self.openTime='152000', self.closeTime='152959', self.symbol='BTCUSDT', self.open='29260', self.close='29230.5'
127.0.0.1 - - [20/Oct/2023 15:30:01] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [20/Oct/2023 15:40:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=22923 

self.closeSec=1697787599, self.tradeDate='20231020', self.openTime='153000', self.closeTime='153959', self.symbol='BTCUSDT', self.open='29230.6', self.close='29262.6'

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=22924 

self.closeSec=1697788199, self.tradeDate='20231020', self.openTime='154000', self.closeTime='154959', self.symbol='BTCUSDT', self.open='29262.6', self.close='29304.9'
127.0.0.1 - - [20/Oct/2023 15:50:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=22925 

self.closeSec=1697788799, self.tradeDate='20231020', self.openTime='155000', self.closeTime='155959', self.symbol='BTCUSDT', self.open='29306.9', self.close='29228.5'
127.0.0.1 - - [20/Oct/2023 16:00:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=22926 

self.closeSec=1697789399, self.tradeDate='20231020', self.openTime='160000', self.closeTime='160959', self.symbol='BTCUSDT', self.open='29228.6', self.close='29349.3'
127.0.0.1 - - [20/Oct/2023 16:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=22927 

self.closeSec=1697789999, self.tradeDate='20231020', self.openTime='161000', self.closeTime='161959', self.symbol='BTCUSDT', self.open='29349.2', self.close='29422.8'
127.0.0.1 - - [20/Oct/2023 16:20:06] "POST / HTTP/1.1" 200 -


## /root/FIL/strategy/similarity/log.txt ----- -----

127.0.0.1 - - [20/Oct/2023 15:30:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=22922 

self.closeSec=1697786999, self.tradeDate='20231020', self.openTime='152000', self.closeTime='152959', self.symbol='BTCUSDT', self.open='29260', self.close='29230.5'
127.0.0.1 - - [20/Oct/2023 15:40:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=22923 

self.closeSec=1697787599, self.tradeDate='20231020', self.openTime='153000', self.closeTime='153959', self.symbol='BTCUSDT', self.open='29230.6', self.close='29262.6'
127.0.0.1 - - [20/Oct/2023 15:50:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=22924 

self.closeSec=1697788199, self.tradeDate='20231020', self.openTime='154000', self.closeTime='154959', self.symbol='BTCUSDT', self.open='29262.6', self.close='29304.9'

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=22925 

self.closeSec=1697788799, self.tradeDate='20231020', self.openTime='155000', self.closeTime='155959', self.symbol='BTCUSDT', self.open='29306.9', self.close='29228.5'
127.0.0.1 - - [20/Oct/2023 16:00:01] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [20/Oct/2023 16:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=22926 

self.closeSec=1697789399, self.tradeDate='20231020', self.openTime='160000', self.closeTime='160959', self.symbol='BTCUSDT', self.open='29228.6', self.close='29349.3'

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=22927 

self.closeSec=1697789999, self.tradeDate='20231020', self.openTime='161000', self.closeTime='161959', self.symbol='BTCUSDT', self.open='29349.2', self.close='29422.8'
127.0.0.1 - - [20/Oct/2023 16:20:06] "POST / HTTP/1.1" 200 -


## /root/FIL/strategy/sr_min/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=1, self.total=996015.990996, self.flagDict['side']='buy', self.tradeCount=1, self.count=45844
self.closeSec=1697789999, self.tradeDate='20231020', self.openTime='161500', self.closeTime='161959', self.symbol='BTCUSDT', self.open=29344.7, self.close=29427.5, self.high=29491.6, self.low=29317.8, self.vol=7805.025, self.amt=229665987.06997 
127.0.0.1 - - [20/Oct/2023 16:20:05] "POST / HTTP/1.1" 200 -
2023-10-20 16:20:08,955:INFO:sr_min:main.py:172:handleKline:2219263: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5951  20231020   155500    155959  ...         0.0        0.0       0
5952  20231020   160000    160459  ...         0.0        0.0       0
5953  20231020   160500    160959  ...         0.0        0.0       0
5954  20231020   161000    161459  ...         0.0        0.0       0
5955  20231020   161500    161959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-10-20 16:20:08,960:INFO:sr_min:main.py:175:handleKline:2219263: self.closeSec=1697789999, self.tradeDate='20231020', self.openTime='161500', self.closeTime='161959',self.symbol='BTCUSDT',self.open=29344.7, self.close=29427.5, self.high=29491.6, self.low=29317.8, self.vol=7805.025, self.amt=229665987.06997, ukdf['pct'].iloc[-1]=0.002822 , ukdf['amount'].iloc[-1]=229665987.06997, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5955, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '37.141', 'enterprice': '26844', 'countrevence': '0', 'unrealprofit': '96046.626', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '29430', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=1
--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=1, self.total=996015.990996, self.flagDict['side']='buy', self.tradeCount=1, self.count=45845
self.closeSec=1697790299, self.tradeDate='20231020', self.openTime='162000', self.closeTime='162459', self.symbol='BTCUSDT', self.open=29422.8, self.close=29420.0, self.high=29430.0, self.low=29376.6, self.vol=1761.689, self.amt=51796578.9595 
127.0.0.1 - - [20/Oct/2023 16:25:01] "POST / HTTP/1.1" 200 -
2023-10-20 16:25:03,191:INFO:sr_min:main.py:172:handleKline:2219263: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5952  20231020   160000    160459  ...         0.0        0.0       0
5953  20231020   160500    160959  ...         0.0        0.0       0
5954  20231020   161000    161459  ...         0.0        0.0       0
5955  20231020   161500    161959  ...         0.0        0.0       0
5956  20231020   162000    162459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-10-20 16:25:03,196:INFO:sr_min:main.py:175:handleKline:2219263: self.closeSec=1697790299, self.tradeDate='20231020', self.openTime='162000', self.closeTime='162459',self.symbol='BTCUSDT',self.open=29422.8, self.close=29420.0, self.high=29430.0, self.low=29376.6, self.vol=1761.689, self.amt=51796578.9595, ukdf['pct'].iloc[-1]=-0.000255 , ukdf['amount'].iloc[-1]=51796578.9595, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5956, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '37.141', 'enterprice': '26844', 'countrevence': '0', 'unrealprofit': '95686.3583', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '29420.3', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=1


## /root/FIL/strategy/s_rsrs/log.txt ----- -----

721  20231020   040000    075959  1697759999  ...    721  0.082168 -0.875769    -1.0
722  20231020   080000    115959  1697774399  ...    722  0.044257 -0.920352    -1.0

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '43.755', 'enterprice': '28761.1', 'countrevence': '0', 'unrealprofit': '-20743.847758299', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '29235.1909098', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-1, self.sign=-1
127.0.0.1 - - [20/Oct/2023 16:00:01] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='s_rsrs', self.symbol='BTCUSDT', interval='4h', intervalSec=14400, wid=25, thd=0.6, self.sign=-1, self.total=1257183.4885695, self.flagDict['side']='sell', self.tradeCount=36, self.count=955
self.closeSec=1697788799, self.tradeDate='20231020', self.openTime='120000', self.closeTime='155959', self.symbol='BTCUSDT', self.open=29222.9, self.close=29228.5, self.high=29405.4, self.low=29110.0, self.vol=65199.235, self.amt=1906397846.791 
2023-10-20 16:00:01,576:INFO:s_rsrs:main.py:141:handleKline:2218689: self.closeSec=1697788799, self.tradeDate='20231020', self.openTime='120000', self.closeTime='155959',self.symbol='BTCUSDT',self.open=29222.9, self.close=29228.5, self.high=29405.4, self.low=29110.0, self.vol=65199.235, self.amt=1906397846.791 
2023-10-20 16:00:01,602:INFO:s_rsrs:main.py:142:handleKline:2218689: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime  ...         vol           amt       pct
719  20231019   200000    235959  ...  110931.187  3.171937e+09  0.007881
720  20231020   000000    035959  ...   87657.153  2.513027e+09  0.002732
721  20231020   040000    075959  ...   36228.044  1.039869e+09 -0.001448
722  20231020   080000    115959  ...  110974.902  3.219885e+09  0.018326
723  20231020   120000    155959  ...   65199.235  1.906398e+09  0.000195

[5 rows x 11 columns]
2023-10-20 16:00:02,415:INFO:s_rsrs:main.py:151:handleKline:2218689: df_s.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec  ...  index      beta    zscore  signal
719  20231019   200000    235959  1697731199  ...    719  0.301781 -0.548275     NaN
720  20231020   000000    035959  1697745599  ...    720  0.190537 -0.715793    -1.0
721  20231020   040000    075959  1697759999  ...    721  0.082168 -0.875769    -1.0
722  20231020   080000    115959  1697774399  ...    722  0.044257 -0.920352    -1.0
723  20231020   120000    155959  1697788799  ...    723  0.008180 -0.962225    -1.0

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '43.755', 'enterprice': '28761.1', 'countrevence': '0', 'unrealprofit': '-20451.087', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '29228.5', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-1, self.sign=-1


