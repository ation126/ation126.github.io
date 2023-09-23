# 20230923 16:26:01

## /root/FIL/strategy/amihud/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=373746.4768026, self.flagDict['side']='sell', self.tradeCount=2, self.count=38068
self.closeSec=1695457199, self.tradeDate='20230923', self.openTime='161500', self.closeTime='161959', self.symbol='BTCUSDT', self.open=26567.7, self.close=26561.7, self.high=26572.5, self.low=26558.3, self.vol=207.199, self.amt=5504318.4348 
127.0.0.1 - - [23/Sep/2023 16:20:02] "POST / HTTP/1.1" 200 -
2023-09-23 16:20:07,347:INFO:amihud:main.py:172:handleKline:2219019: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5951  20230923   155500    155959  ...         0.0        0.0       0
5952  20230923   160000    160459  ...         0.0        0.0       0
5953  20230923   160500    160959  ...         0.0        0.0       0
5954  20230923   161000    161459  ...         0.0        0.0       0
5955  20230923   161500    161959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-09-23 16:20:07,358:INFO:amihud:main.py:175:handleKline:2219019: self.closeSec=1695457199, self.tradeDate='20230923', self.openTime='161500', self.closeTime='161959',self.symbol='BTCUSDT',self.open=26567.7, self.close=26561.7, self.high=26572.5, self.low=26558.3, self.vol=207.199, self.amt=5504318.4348, ukdf['pct'].iloc[-1]=-0.000226 , ukdf['amount'].iloc[-1]=5504318.4348, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5955, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '13.926', 'enterprice': '26864.9', 'countrevence': '0', 'unrealprofit': '4202.8668', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '26563.1', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1
127.0.0.1 - - [23/Sep/2023 16:25:00] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=373746.4768026, self.flagDict['side']='sell', self.tradeCount=2, self.count=38069
self.closeSec=1695457499, self.tradeDate='20230923', self.openTime='162000', self.closeTime='162459', self.symbol='BTCUSDT', self.open=26561.7, self.close=26554.9, self.high=26563.7, self.low=26548.7, self.vol=260.606, self.amt=6920539.4187 
2023-09-23 16:25:00,818:INFO:amihud:main.py:172:handleKline:2219019: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5952  20230923   160000    160459  ...         0.0        0.0       0
5953  20230923   160500    160959  ...         0.0        0.0       0
5954  20230923   161000    161459  ...         0.0        0.0       0
5955  20230923   161500    161959  ...         0.0        0.0       0
5956  20230923   162000    162459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-09-23 16:25:00,819:INFO:amihud:main.py:175:handleKline:2219019: self.closeSec=1695457499, self.tradeDate='20230923', self.openTime='162000', self.closeTime='162459',self.symbol='BTCUSDT',self.open=26561.7, self.close=26554.9, self.high=26563.7, self.low=26548.7, self.vol=260.606, self.amt=6920539.4187, ukdf['pct'].iloc[-1]=-0.000256 , ukdf['amount'].iloc[-1]=6920539.4187, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5956, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '13.926', 'enterprice': '26864.9', 'countrevence': '0', 'unrealprofit': '4318.4526', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '26554.8', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1


## /root/FIL/strategy/factorcheck/log.txt ----- -----


--handleKline--: 127.0.0.1 - - [23/Sep/2023 16:00:00] "POST / HTTP/1.1" 200 -
 version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.714181719035411, self.count=38066 

self.closeSec=1695455999, self.tradeDate='20230923', self.openTime='155500', self.closeTime='155959', self.symbol='BTCUSDT', self.open=26551.9, self.close=26571.5, self.high=26571.6, self.low=26548.9 
127.0.0.1 - - [23/Sep/2023 16:05:00] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.714181719035411, self.count=38067 

self.closeSec=1695456299, self.tradeDate='20230923', self.openTime='160000', self.closeTime='160459', self.symbol='BTCUSDT', self.open=26571.9, self.close=26568.1, self.high=26583.7, self.low=26567.1 
127.0.0.1 - - [23/Sep/2023 16:10:00] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.714181719035411, self.count=38068 

self.closeSec=1695456599, self.tradeDate='20230923', self.openTime='160500', self.closeTime='160959', self.symbol='BTCUSDT', self.open=26568.0, self.close=26568.0, self.high=26568.5, self.low=26560.1 
127.0.0.1 - - [23/Sep/2023 16:15:00] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.714181719035411, self.count=38069 

self.closeSec=1695456899, self.tradeDate='20230923', self.openTime='161000', self.closeTime='161459', self.symbol='BTCUSDT', self.open=26567.9, self.close=26567.7, self.high=26573.7, self.low=26564.6 

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.714181719035411, self.count=38070 

self.closeSec=1695457199, self.tradeDate='20230923', self.openTime='161500', self.closeTime='161959', self.symbol='BTCUSDT', self.open=26567.7, self.close=26561.7, self.high=26572.5, self.low=26558.3 
127.0.0.1 - - [23/Sep/2023 16:20:02] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.714181719035411, self.count=38071 

self.closeSec=1695457499, self.tradeDate='20230923', self.openTime='162000', self.closeTime='162459', self.symbol='BTCUSDT', self.open=26561.7, self.close=26554.9, self.high=26563.7, self.low=26548.7 
127.0.0.1 - - [23/Sep/2023 16:25:00] "POST / HTTP/1.1" 200 -


## /root/FIL/strategy/logic/log.txt ----- -----

2023-09-23 16:00:17,810:DEBUG:logic:main.py:463:getModel:2218526: df_s.iloc[-5:,:] :
          date closeTime     open  ...    alpha58   alpha67   alpha72
5785  20230923    132959  26539.9  ...  47.916667  0.455823  0.643110
5786  20230923    135959  26539.9  ...  47.500000  0.452391  0.648271
5787  20230923    142959  26529.9  ...  47.500000  0.467421  0.641831
5788  20230923    145959  26566.9  ...  47.500000  0.467280  0.635941
5789  20230923    152959  26566.5  ...  47.083333  0.466060  0.631475

[5 rows x 33 columns]
0.540590405904059
acc is : 0.540590405904059
2023-09-23 16:00:17,883:INFO:logic:main.py:468:getModel:2218526: df_pred.iloc[-5:,:] :
     pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
537     1  0.498443  0.501557       0  ...  0.952135  -1.0    0.0  1.053171
538     1  0.496069  0.503931       1  ...  0.950804  -1.0    0.0  1.054644
539     0  0.510897  0.489103       1  ...  0.950818  -1.0    0.0  1.054628
540     1  0.498721  0.501279       0  ...  0.950940  -1.0    0.0  1.054493
541     1  0.497511  0.502489       1  ...  0.950625  -1.0    0.0  1.054842

[5 rows x 10 columns]
2023-09-23 16:00:17,897:INFO:logic:main.py:478:getModel:2218526: df_panel.iloc[-5:,:] :
    pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
45     1  0.498911  0.501089       0  ...  0.952135  -1.0    0.0  1.055303
46     1  0.496867  0.503133       1  ...  0.950804  -1.0    0.0  1.058071
47     0  0.511446  0.488554       1  ...  0.950818  -1.0    0.0  1.056305
48     1  0.498960  0.501040       0  ...  0.950940  -1.0    0.0  1.056098
49     1  0.497511  0.502489       1  ...  0.950625  -1.0    0.0  1.054842

[5 rows x 10 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '25.67', 'enterprice': '27131.4', 'countrevence': '0', 'unrealprofit': '14287.922', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '26574.8', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}


## /root/FIL/strategy/modifiedmom/log.txt ----- -----

127.0.0.1 - - [23/Sep/2023 15:30:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=19031 

self.closeSec=1695454199, self.tradeDate='20230923', self.openTime='152000', self.closeTime='152959', self.symbol='BTCUSDT', self.open='26563.8', self.close='26563.2'
127.0.0.1 - - [23/Sep/2023 15:40:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=19032 

self.closeSec=1695454799, self.tradeDate='20230923', self.openTime='153000', self.closeTime='153959', self.symbol='BTCUSDT', self.open='26563.1', self.close='26566.1'
127.0.0.1 - - [23/Sep/2023 15:50:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=19033 

self.closeSec=1695455399, self.tradeDate='20230923', self.openTime='154000', self.closeTime='154959', self.symbol='BTCUSDT', self.open='26566', self.close='26561.9'
127.0.0.1 - - [23/Sep/2023 16:00:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=19034 

self.closeSec=1695455999, self.tradeDate='20230923', self.openTime='155000', self.closeTime='155959', self.symbol='BTCUSDT', self.open='26561.8', self.close='26572'

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=19035 

self.closeSec=1695456599, self.tradeDate='20230923', self.openTime='160000', self.closeTime='160959', self.symbol='BTCUSDT', self.open='26571.9', self.close='26568'
127.0.0.1 - - [23/Sep/2023 16:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=19036 

self.closeSec=1695457199, self.tradeDate='20230923', self.openTime='161000', self.closeTime='161959', self.symbol='BTCUSDT', self.open='26567.9', self.close='26561.7'
127.0.0.1 - - [23/Sep/2023 16:20:05] "POST / HTTP/1.1" 200 -


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


--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=19034 

self.closeSec=1695454199, self.tradeDate='20230923', self.openTime='152000', self.closeTime='152959', self.symbol='BTCUSDT', self.open='26563.8', self.close='26563.2'
127.0.0.1 - - [23/Sep/2023 15:30:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=19035 

self.closeSec=1695454799, self.tradeDate='20230923', self.openTime='153000', self.closeTime='153959', self.symbol='BTCUSDT', self.open='26563.1', self.close='26566.1'
127.0.0.1 - - [23/Sep/2023 15:40:01] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [23/Sep/2023 15:50:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=19036 

self.closeSec=1695455399, self.tradeDate='20230923', self.openTime='154000', self.closeTime='154959', self.symbol='BTCUSDT', self.open='26566', self.close='26561.9'

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=19037 

self.closeSec=1695455999, self.tradeDate='20230923', self.openTime='155000', self.closeTime='155959', self.symbol='BTCUSDT', self.open='26561.8', self.close='26572'
127.0.0.1 - - [23/Sep/2023 16:00:01] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [23/Sep/2023 16:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=19038 

self.closeSec=1695456599, self.tradeDate='20230923', self.openTime='160000', self.closeTime='160959', self.symbol='BTCUSDT', self.open='26571.9', self.close='26568'

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=19039 

self.closeSec=1695457199, self.tradeDate='20230923', self.openTime='161000', self.closeTime='161959', self.symbol='BTCUSDT', self.open='26567.9', self.close='26561.7'
127.0.0.1 - - [23/Sep/2023 16:20:05] "POST / HTTP/1.1" 200 -


## /root/FIL/strategy/similarity/log.txt ----- -----

127.0.0.1 - - [23/Sep/2023 15:30:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=19034 

self.closeSec=1695454199, self.tradeDate='20230923', self.openTime='152000', self.closeTime='152959', self.symbol='BTCUSDT', self.open='26563.8', self.close='26563.2'
127.0.0.1 - - [23/Sep/2023 15:40:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=19035 

self.closeSec=1695454799, self.tradeDate='20230923', self.openTime='153000', self.closeTime='153959', self.symbol='BTCUSDT', self.open='26563.1', self.close='26566.1'

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=19036 

self.closeSec=1695455399, self.tradeDate='20230923', self.openTime='154000', self.closeTime='154959', self.symbol='BTCUSDT', self.open='26566', self.close='26561.9'
127.0.0.1 - - [23/Sep/2023 15:50:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=19037 

self.closeSec=1695455999, self.tradeDate='20230923', self.openTime='155000', self.closeTime='155959', self.symbol='BTCUSDT', self.open='26561.8', self.close='26572'
127.0.0.1 - - [23/Sep/2023 16:00:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=19038 

self.closeSec=1695456599, self.tradeDate='20230923', self.openTime='160000', self.closeTime='160959', self.symbol='BTCUSDT', self.open='26571.9', self.close='26568'
127.0.0.1 - - [23/Sep/2023 16:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=19039 

self.closeSec=1695457199, self.tradeDate='20230923', self.openTime='161000', self.closeTime='161959', self.symbol='BTCUSDT', self.open='26567.9', self.close='26561.7'
127.0.0.1 - - [23/Sep/2023 16:20:05] "POST / HTTP/1.1" 200 -


## /root/FIL/strategy/sr_min/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=1, self.total=996015.990996, self.flagDict['side']='buy', self.tradeCount=1, self.count=38068
self.closeSec=1695457199, self.tradeDate='20230923', self.openTime='161500', self.closeTime='161959', self.symbol='BTCUSDT', self.open=26567.7, self.close=26561.7, self.high=26572.5, self.low=26558.3, self.vol=207.199, self.amt=5504318.4348 
127.0.0.1 - - [23/Sep/2023 16:20:02] "POST / HTTP/1.1" 200 -
2023-09-23 16:20:07,359:INFO:sr_min:main.py:172:handleKline:2219263: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5951  20230923   155500    155959  ...         0.0        0.0       0
5952  20230923   160000    160459  ...         0.0        0.0       0
5953  20230923   160500    160959  ...         0.0        0.0       0
5954  20230923   161000    161459  ...         0.0        0.0       0
5955  20230923   161500    161959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-09-23 16:20:07,377:INFO:sr_min:main.py:175:handleKline:2219263: self.closeSec=1695457199, self.tradeDate='20230923', self.openTime='161500', self.closeTime='161959',self.symbol='BTCUSDT',self.open=26567.7, self.close=26561.7, self.high=26572.5, self.low=26558.3, self.vol=207.199, self.amt=5504318.4348, ukdf['pct'].iloc[-1]=-0.000226 , ukdf['amount'].iloc[-1]=5504318.4348, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5955, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '37.141', 'enterprice': '26844', 'countrevence': '0', 'unrealprofit': '-10432.9069', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '26563.1', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=1
127.0.0.1 - - [23/Sep/2023 16:25:00] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=1, self.total=996015.990996, self.flagDict['side']='buy', self.tradeCount=1, self.count=38069
self.closeSec=1695457499, self.tradeDate='20230923', self.openTime='162000', self.closeTime='162459', self.symbol='BTCUSDT', self.open=26561.7, self.close=26554.9, self.high=26563.7, self.low=26548.7, self.vol=260.606, self.amt=6920539.4187 
2023-09-23 16:25:00,849:INFO:sr_min:main.py:172:handleKline:2219263: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5952  20230923   160000    160459  ...         0.0        0.0       0
5953  20230923   160500    160959  ...         0.0        0.0       0
5954  20230923   161000    161459  ...         0.0        0.0       0
5955  20230923   161500    161959  ...         0.0        0.0       0
5956  20230923   162000    162459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-09-23 16:25:00,849:INFO:sr_min:main.py:175:handleKline:2219263: self.closeSec=1695457499, self.tradeDate='20230923', self.openTime='162000', self.closeTime='162459',self.symbol='BTCUSDT',self.open=26561.7, self.close=26554.9, self.high=26563.7, self.low=26548.7, self.vol=260.606, self.amt=6920539.4187, ukdf['pct'].iloc[-1]=-0.000256 , ukdf['amount'].iloc[-1]=6920539.4187, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5956, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '37.141', 'enterprice': '26844', 'countrevence': '0', 'unrealprofit': '-10741.1772', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '26554.8', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=1


## /root/FIL/strategy/s_rsrs/log.txt ----- -----

721  20230923   040000    075959  1695427199  ...    721  1.134255  1.774907     1.0
722  20230923   080000    115959  1695441599  ...    722  1.193795  1.874602     1.0

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '50.787', 'enterprice': '27251.4', 'countrevence': '0', 'unrealprofit': '-37076.18187807567', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '26521.36708059', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=1, self.sign=1
127.0.0.1 - - [23/Sep/2023 16:00:01] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='s_rsrs', self.symbol='BTCUSDT', interval='4h', intervalSec=14400, wid=25, thd=0.6, self.sign=1, self.total=1382632.8349482, self.flagDict['side']='buy', self.tradeCount=25, self.count=793
self.closeSec=1695455999, self.tradeDate='20230923', self.openTime='120000', self.closeTime='155959', self.symbol='BTCUSDT', self.open=26519.0, self.close=26571.5, self.high=26575.0, self.low=26492.2, self.vol=10416.599, self.amt=276474511.3757 
2023-09-23 16:00:01,514:INFO:s_rsrs:main.py:141:handleKline:2218689: self.closeSec=1695455999, self.tradeDate='20230923', self.openTime='120000', self.closeTime='155959',self.symbol='BTCUSDT',self.open=26519.0, self.close=26571.5, self.high=26575.0, self.low=26492.2, self.vol=10416.599, self.amt=276474511.3757 
2023-09-23 16:00:01,528:INFO:s_rsrs:main.py:142:handleKline:2218689: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime  ...        vol           amt       pct
719  20230922   200000    235959  ...  37446.547  9.966943e+08 -0.000383
720  20230923   000000    035959  ...  26686.848  7.092073e+08 -0.003486
721  20230923   040000    075959  ...  20007.182  5.309535e+08  0.001493
722  20230923   080000    115959  ...  12073.366  3.206306e+08 -0.001792
723  20230923   120000    155959  ...  10416.599  2.764745e+08  0.001976

[5 rows x 11 columns]
2023-09-23 16:00:02,165:INFO:s_rsrs:main.py:151:handleKline:2218689: df_s.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec  ...  index      beta    zscore  signal
719  20230922   200000    235959  1695398399  ...    719  0.798307  0.930515     1.0
720  20230923   000000    035959  1695412799  ...    720  0.869762  1.101778     1.0
721  20230923   040000    075959  1695427199  ...    721  1.134255  1.774907     1.0
722  20230923   080000    115959  1695441599  ...    722  1.193795  1.874602     1.0
723  20230923   120000    155959  1695455999  ...    723  1.246309  1.946445     1.0

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '50.787', 'enterprice': '27251.4', 'countrevence': '0', 'unrealprofit': '-34485.00997664844', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '26572.38745788', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=1, self.sign=1


