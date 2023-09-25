# 20230925 16:26:02

## /root/FIL/strategy/amihud/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=373746.4768026, self.flagDict['side']='sell', self.tradeCount=2, self.count=38644
self.closeSec=1695629999, self.tradeDate='20230925', self.openTime='161500', self.closeTime='161959', self.symbol='BTCUSDT', self.open=26170.1, self.close=26146.9, self.high=26170.1, self.low=26141.5, self.vol=1148.145, self.amt=30026044.8935 
127.0.0.1 - - [25/Sep/2023 16:20:02] "POST / HTTP/1.1" 200 -
2023-09-25 16:20:06,409:INFO:amihud:main.py:172:handleKline:2219019: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5951  20230925   155500    155959  ...         0.0        0.0       0
5952  20230925   160000    160459  ...         0.0        0.0       0
5953  20230925   160500    160959  ...         0.0        0.0       0
5954  20230925   161000    161459  ...         0.0        0.0       0
5955  20230925   161500    161959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-09-25 16:20:06,414:INFO:amihud:main.py:175:handleKline:2219019: self.closeSec=1695629999, self.tradeDate='20230925', self.openTime='161500', self.closeTime='161959',self.symbol='BTCUSDT',self.open=26170.1, self.close=26146.9, self.high=26170.1, self.low=26141.5, self.vol=1148.145, self.amt=30026044.8935, ukdf['pct'].iloc[-1]=-0.000883 , ukdf['amount'].iloc[-1]=30026044.8935, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5955, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '13.926', 'enterprice': '26864.9', 'countrevence': '0', 'unrealprofit': '9994.6902', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '26147.2', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1
--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=373746.4768026, self.flagDict['side']='sell', self.tradeCount=2, self.count=38645
self.closeSec=1695630299, self.tradeDate='20230925', self.openTime='162000', self.closeTime='162459', self.symbol='BTCUSDT', self.open=26147.0, self.close=26141.3, self.high=26147.8, self.low=26129.9, self.vol=556.261, self.amt=14540337.804 
127.0.0.1 - - [25/Sep/2023 16:25:00] "POST / HTTP/1.1" 200 -
2023-09-25 16:25:00,848:INFO:amihud:main.py:172:handleKline:2219019: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5952  20230925   160000    160459  ...         0.0        0.0       0
5953  20230925   160500    160959  ...         0.0        0.0       0
5954  20230925   161000    161459  ...         0.0        0.0       0
5955  20230925   161500    161959  ...         0.0        0.0       0
5956  20230925   162000    162459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-09-25 16:25:00,848:INFO:amihud:main.py:175:handleKline:2219019: self.closeSec=1695630299, self.tradeDate='20230925', self.openTime='162000', self.closeTime='162459',self.symbol='BTCUSDT',self.open=26147.0, self.close=26141.3, self.high=26147.8, self.low=26129.9, self.vol=556.261, self.amt=14540337.804, ukdf['pct'].iloc[-1]=-0.000214 , ukdf['amount'].iloc[-1]=14540337.804, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5956, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '13.926', 'enterprice': '26864.9', 'countrevence': '0', 'unrealprofit': '10076.8536', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '26141.3', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1


## /root/FIL/strategy/factorcheck/log.txt ----- -----


--handleKline--: 127.0.0.1 - - [25/Sep/2023 16:00:00] "POST / HTTP/1.1" 200 -
 version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.714181719035411, self.count=38642 

self.closeSec=1695628799, self.tradeDate='20230925', self.openTime='155500', self.closeTime='155959', self.symbol='BTCUSDT', self.open=26180.9, self.close=26176.7, self.high=26181.9, self.low=26164.5 

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.714181719035411, self.count=38643 

self.closeSec=1695629099, self.tradeDate='20230925', self.openTime='160000', self.closeTime='160459', self.symbol='BTCUSDT', self.open=26176.7, self.close=26183.6, self.high=26223.0, self.low=26176.7 
127.0.0.1 - - [25/Sep/2023 16:05:00] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.714181719035411, self.count=38644 

self.closeSec=1695629399, self.tradeDate='20230925', self.openTime='160500', self.closeTime='160959', self.symbol='BTCUSDT', self.open=26186.9, self.close=26183.2, self.high=26188.3, self.low=26171.4 
127.0.0.1 - - [25/Sep/2023 16:10:00] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [25/Sep/2023 16:15:00] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.714181719035411, self.count=38645 

self.closeSec=1695629699, self.tradeDate='20230925', self.openTime='161000', self.closeTime='161459', self.symbol='BTCUSDT', self.open=26183.3, self.close=26170.0, self.high=26190.6, self.low=26170.0 

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.714181719035411, self.count=38646 

self.closeSec=1695629999, self.tradeDate='20230925', self.openTime='161500', self.closeTime='161959', self.symbol='BTCUSDT', self.open=26170.1, self.close=26146.9, self.high=26170.1, self.low=26141.5 
127.0.0.1 - - [25/Sep/2023 16:20:02] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [25/Sep/2023 16:25:00] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.714181719035411, self.count=38647 

self.closeSec=1695630299, self.tradeDate='20230925', self.openTime='162000', self.closeTime='162459', self.symbol='BTCUSDT', self.open=26147.0, self.close=26141.3, self.high=26147.8, self.low=26129.9 


## /root/FIL/strategy/logic/log.txt ----- -----

2023-09-25 16:00:18,175:DEBUG:logic:main.py:463:getModel:2218526: df_s.iloc[-5:,:] :
          date closeTime     open  ...    alpha58   alpha67   alpha72
5785  20230925    132959  26138.8  ...  44.583333  0.368041  0.671368
5786  20230925    135959  26098.3  ...  45.000000  0.372512  0.681223
5787  20230925    142959  26105.1  ...  45.000000  0.377781  0.689372
5788  20230925    145959  26117.4  ...  45.000000  0.381474  0.696247
5789  20230925    152959  26126.1  ...  44.583333  0.380552  0.702956

[5 rows x 33 columns]
0.540590405904059
acc is : 0.540590405904059
2023-09-25 16:00:18,243:INFO:logic:main.py:468:getModel:2218526: df_pred.iloc[-5:,:] :
     pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
537     1  0.476447  0.523553       1  ...  0.935655  -1.0    0.0  0.984251
538     1  0.492609  0.507391       1  ...  0.935218  -1.0    0.0  0.984711
539     1  0.494817  0.505183       1  ...  0.934913  -1.0    0.0  0.985032
540     1  0.494138  0.505862       0  ...  0.935035  -1.0    0.0  0.984904
541     1  0.491702  0.508298       1  ...  0.933092  -1.0    0.0  0.986951

[5 rows x 10 columns]
2023-09-25 16:00:18,258:INFO:logic:main.py:478:getModel:2218526: df_panel.iloc[-5:,:] :
    pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
45     1  0.476489  0.523511       1  ...  0.935655  -1.0    0.0  0.995329
46     1  0.492767  0.507233       1  ...  0.935218  -1.0    0.0  0.996885
47     1  0.494801  0.505199       1  ...  0.934913  -1.0    0.0  0.996787
48     1  0.494305  0.505695       0  ...  0.935035  -1.0    0.0  0.998090
49     1  0.491702  0.508298       1  ...  0.933092  -1.0    0.0  0.986951

[5 rows x 10 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '25.67', 'enterprice': '27131.4', 'countrevence': '0', 'unrealprofit': '24453.242', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '26178.8', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}


## /root/FIL/strategy/modifiedmom/log.txt ----- -----

127.0.0.1 - - [25/Sep/2023 15:30:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=19319 

self.closeSec=1695626999, self.tradeDate='20230925', self.openTime='152000', self.closeTime='152959', self.symbol='BTCUSDT', self.open='26120', self.close='26122.5'
127.0.0.1 - - [25/Sep/2023 15:40:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=19320 

self.closeSec=1695627599, self.tradeDate='20230925', self.openTime='153000', self.closeTime='153959', self.symbol='BTCUSDT', self.open='26122.5', self.close='26110.4'
127.0.0.1 - - [25/Sep/2023 15:50:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=19321 

self.closeSec=1695628199, self.tradeDate='20230925', self.openTime='154000', self.closeTime='154959', self.symbol='BTCUSDT', self.open='26110.3', self.close='26166.8'
127.0.0.1 - - [25/Sep/2023 16:00:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=19322 

self.closeSec=1695628799, self.tradeDate='20230925', self.openTime='155000', self.closeTime='155959', self.symbol='BTCUSDT', self.open='26172.1', self.close='26176.8'

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=19323 

self.closeSec=1695629399, self.tradeDate='20230925', self.openTime='160000', self.closeTime='160959', self.symbol='BTCUSDT', self.open='26176.7', self.close='26183.2'
127.0.0.1 - - [25/Sep/2023 16:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=19324 

self.closeSec=1695629999, self.tradeDate='20230925', self.openTime='161000', self.closeTime='161959', self.symbol='BTCUSDT', self.open='26183.3', self.close='26146.9'
127.0.0.1 - - [25/Sep/2023 16:20:04] "POST / HTTP/1.1" 200 -


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

127.0.0.1 - - [25/Sep/2023 15:30:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=19322 

self.closeSec=1695626999, self.tradeDate='20230925', self.openTime='152000', self.closeTime='152959', self.symbol='BTCUSDT', self.open='26120', self.close='26122.5'
127.0.0.1 - - [25/Sep/2023 15:40:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=19323 

self.closeSec=1695627599, self.tradeDate='20230925', self.openTime='153000', self.closeTime='153959', self.symbol='BTCUSDT', self.open='26122.5', self.close='26110.4'

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=19324 

self.closeSec=1695628199, self.tradeDate='20230925', self.openTime='154000', self.closeTime='154959', self.symbol='BTCUSDT', self.open='26110.3', self.close='26166.8'
127.0.0.1 - - [25/Sep/2023 15:50:01] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [25/Sep/2023 16:00:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=19325 

self.closeSec=1695628799, self.tradeDate='20230925', self.openTime='155000', self.closeTime='155959', self.symbol='BTCUSDT', self.open='26172.1', self.close='26176.8'
127.0.0.1 - - [25/Sep/2023 16:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=19326 

self.closeSec=1695629399, self.tradeDate='20230925', self.openTime='160000', self.closeTime='160959', self.symbol='BTCUSDT', self.open='26176.7', self.close='26183.2'

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=19327 

self.closeSec=1695629999, self.tradeDate='20230925', self.openTime='161000', self.closeTime='161959', self.symbol='BTCUSDT', self.open='26183.3', self.close='26146.9'
127.0.0.1 - - [25/Sep/2023 16:20:04] "POST / HTTP/1.1" 200 -


## /root/FIL/strategy/similarity/log.txt ----- -----


--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=19322 

self.closeSec=1695626999, self.tradeDate='20230925', self.openTime='152000', self.closeTime='152959', self.symbol='BTCUSDT', self.open='26120', self.close='26122.5'
127.0.0.1 - - [25/Sep/2023 15:30:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=19323 

self.closeSec=1695627599, self.tradeDate='20230925', self.openTime='153000', self.closeTime='153959', self.symbol='BTCUSDT', self.open='26122.5', self.close='26110.4'
127.0.0.1 - - [25/Sep/2023 15:40:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=19324 

self.closeSec=1695628199, self.tradeDate='20230925', self.openTime='154000', self.closeTime='154959', self.symbol='BTCUSDT', self.open='26110.3', self.close='26166.8'
127.0.0.1 - - [25/Sep/2023 15:50:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=19325 

self.closeSec=1695628799, self.tradeDate='20230925', self.openTime='155000', self.closeTime='155959', self.symbol='BTCUSDT', self.open='26172.1', self.close='26176.8'
127.0.0.1 - - [25/Sep/2023 16:00:01] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [25/Sep/2023 16:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=19326 

self.closeSec=1695629399, self.tradeDate='20230925', self.openTime='160000', self.closeTime='160959', self.symbol='BTCUSDT', self.open='26176.7', self.close='26183.2'

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=19327 

self.closeSec=1695629999, self.tradeDate='20230925', self.openTime='161000', self.closeTime='161959', self.symbol='BTCUSDT', self.open='26183.3', self.close='26146.9'
127.0.0.1 - - [25/Sep/2023 16:20:04] "POST / HTTP/1.1" 200 -


## /root/FIL/strategy/sr_min/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=1, self.total=996015.990996, self.flagDict['side']='buy', self.tradeCount=1, self.count=38644
self.closeSec=1695629999, self.tradeDate='20230925', self.openTime='161500', self.closeTime='161959', self.symbol='BTCUSDT', self.open=26170.1, self.close=26146.9, self.high=26170.1, self.low=26141.5, self.vol=1148.145, self.amt=30026044.8935 
127.0.0.1 - - [25/Sep/2023 16:20:02] "POST / HTTP/1.1" 200 -
2023-09-25 16:20:06,412:INFO:sr_min:main.py:172:handleKline:2219263: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5951  20230925   155500    155959  ...         0.0        0.0       0
5952  20230925   160000    160459  ...         0.0        0.0       0
5953  20230925   160500    160959  ...         0.0        0.0       0
5954  20230925   161000    161459  ...         0.0        0.0       0
5955  20230925   161500    161959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-09-25 16:20:06,424:INFO:sr_min:main.py:175:handleKline:2219263: self.closeSec=1695629999, self.tradeDate='20230925', self.openTime='161500', self.closeTime='161959',self.symbol='BTCUSDT',self.open=26170.1, self.close=26146.9, self.high=26170.1, self.low=26141.5, self.vol=1148.145, self.amt=30026044.8935, ukdf['pct'].iloc[-1]=-0.000883 , ukdf['amount'].iloc[-1]=30026044.8935, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5955, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '37.141', 'enterprice': '26844', 'countrevence': '0', 'unrealprofit': '-25879.8488', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '26147.2', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=1
127.0.0.1 - - [25/Sep/2023 16:25:00] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=1, self.total=996015.990996, self.flagDict['side']='buy', self.tradeCount=1, self.count=38645
self.closeSec=1695630299, self.tradeDate='20230925', self.openTime='162000', self.closeTime='162459', self.symbol='BTCUSDT', self.open=26147.0, self.close=26141.3, self.high=26147.8, self.low=26129.9, self.vol=556.261, self.amt=14540337.804 
2023-09-25 16:25:00,843:INFO:sr_min:main.py:172:handleKline:2219263: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5952  20230925   160000    160459  ...         0.0        0.0       0
5953  20230925   160500    160959  ...         0.0        0.0       0
5954  20230925   161000    161459  ...         0.0        0.0       0
5955  20230925   161500    161959  ...         0.0        0.0       0
5956  20230925   162000    162459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-09-25 16:25:00,844:INFO:sr_min:main.py:175:handleKline:2219263: self.closeSec=1695630299, self.tradeDate='20230925', self.openTime='162000', self.closeTime='162459',self.symbol='BTCUSDT',self.open=26147.0, self.close=26141.3, self.high=26147.8, self.low=26129.9, self.vol=556.261, self.amt=14540337.804, ukdf['pct'].iloc[-1]=-0.000214 , ukdf['amount'].iloc[-1]=14540337.804, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5956, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '37.141', 'enterprice': '26844', 'countrevence': '0', 'unrealprofit': '-26098.9807', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '26141.3', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=1


## /root/FIL/strategy/s_rsrs/log.txt ----- -----

2023-09-25 12:00:10,447:INFO:s_rsrs:main.py:343:handleOrderNew:2218689: handleOrderNew: data=OrderType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'clientorderid': '42961F1695614404882I0L65', 'symbol': 'BTCUSDT', 'gatewayorderid': 1695614405298321, 'quantity': '50.787', 'price': '26148.1', 'stopprice': '0', 'ordertype': '', 'side': 'SELL', 'status': 'FILLED', 'positionside': 'SHORT', 'createtime': 1695614403937, 'updatetime': 1695614405298, 'tradetype': 'usdt', 'selfid': 42961, 'filltrades': [TradeType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'tradeid': 1695614405298, 'clientorderid': '42961F1695614404882I0L65', 'price': '26148.1', 'quantity': '50.787', 'commission': '1327.9835547', 'commissionasset': 'USDT', 'tradetime': 1695614405298, 'tradetype': 'usdt', 'gatetype': 'simulator', 'handletime': 1695614405298}], 'gatetype': 'simulator', 'handletime': 0}
2023-09-25 12:00:10,448:INFO:s_rsrs:main.py:346:handleOrderFilled:2218689: handleOrderFilled: data=OrderType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'clientorderid': '42961F1695614404882I0L65', 'symbol': 'BTCUSDT', 'gatewayorderid': 1695614405298321, 'quantity': '50.787', 'price': '26148.1', 'stopprice': '0', 'ordertype': '', 'side': 'SELL', 'status': 'FILLED', 'positionside': 'SHORT', 'createtime': 1695614403937, 'updatetime': 1695614405298, 'tradetype': 'usdt', 'selfid': 42961, 'filltrades': [TradeType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'tradeid': 1695614405298, 'clientorderid': '42961F1695614404882I0L65', 'price': '26148.1', 'quantity': '50.787', 'commission': '1327.9835547', 'commissionasset': 'USDT', 'tradetime': 1695614405298, 'tradetype': 'usdt', 'gatetype': 'simulator', 'handletime': 1695614405298}], 'gatetype': 'simulator', 'handletime': 0}
2023-09-25 12:00:10,872:INFO:s_rsrs:main.py:343:handleOrderNew:2218689: handleOrderNew: data=OrderType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'clientorderid': '42962F1695614410420I0L65', 'symbol': 'BTCUSDT', 'gatewayorderid': 1695614410834210, 'quantity': '50.756', 'price': '26148.9', 'stopprice': '0', 'ordertype': '', 'side': 'SELL', 'status': 'FILLED', 'positionside': 'SHORT', 'createtime': 1695614409964, 'updatetime': 1695614410834, 'tradetype': 'usdt', 'selfid': 42962, 'filltrades': [TradeType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'tradeid': 1695614410834, 'clientorderid': '42962F1695614410420I0L65', 'price': '26148.9', 'quantity': '50.756', 'commission': '1327.2135684', 'commissionasset': 'USDT', 'tradetime': 1695614410834, 'tradetype': 'usdt', 'gatetype': 'simulator', 'handletime': 1695614410834}], 'gatetype': 'simulator', 'handletime': 0}
127.0.0.1 - - [25/Sep/2023 12:00:10] "POST / HTTP/1.1" 200 -
2023-09-25 12:00:11,060:INFO:s_rsrs:main.py:346:handleOrderFilled:2218689: handleOrderFilled: data=OrderType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'clientorderid': '42962F1695614410420I0L65', 'symbol': 'BTCUSDT', 'gatewayorderid': 1695614410834210, 'quantity': '50.756', 'price': '26148.9', 'stopprice': '0', 'ordertype': '', 'side': 'SELL', 'status': 'FILLED', 'positionside': 'SHORT', 'createtime': 1695614409964, 'updatetime': 1695614410834, 'tradetype': 'usdt', 'selfid': 42962, 'filltrades': [TradeType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'tradeid': 1695614410834, 'clientorderid': '42962F1695614410420I0L65', 'price': '26148.9', 'quantity': '50.756', 'commission': '1327.2135684', 'commissionasset': 'USDT', 'tradetime': 1695614410834, 'tradetype': 'usdt', 'gatetype': 'simulator', 'handletime': 1695614410834}], 'gatetype': 'simulator', 'handletime': 0}
127.0.0.1 - - [25/Sep/2023 12:00:11] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='s_rsrs', self.symbol='BTCUSDT', interval='4h', intervalSec=14400, wid=25, thd=0.6, self.sign=-1, self.total=1325886.3548316, self.flagDict['side']='sell', self.tradeCount=26, self.count=805
self.closeSec=1695628799, self.tradeDate='20230925', self.openTime='120000', self.closeTime='155959', self.symbol='BTCUSDT', self.open=26148.5, self.close=26176.8, self.high=26186.0, self.low=26025.0, self.vol=29109.864, self.amt=760256715.54676 
127.0.0.1 - - [25/Sep/2023 16:00:01] "POST / HTTP/1.1" 200 -
2023-09-25 16:00:01,534:INFO:s_rsrs:main.py:141:handleKline:2218689: self.closeSec=1695628799, self.tradeDate='20230925', self.openTime='120000', self.closeTime='155959',self.symbol='BTCUSDT',self.open=26148.5, self.close=26176.8, self.high=26186.0, self.low=26025.0, self.vol=29109.864, self.amt=760256715.54676 
2023-09-25 16:00:01,549:INFO:s_rsrs:main.py:142:handleKline:2218689: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime  ...        vol           amt       pct
719  20230924   200000    235959  ...   9585.642  2.547617e+08 -0.000809
720  20230925   000000    035959  ...  70194.323  1.862757e+09 -0.005029
721  20230925   040000    075959  ...  44285.803  1.165496e+09 -0.007559
722  20230925   080000    115959  ...  70352.779  1.840985e+09 -0.003206
723  20230925   120000    155959  ...  29109.864  7.602567e+08  0.001078

[5 rows x 11 columns]
2023-09-25 16:00:02,285:INFO:s_rsrs:main.py:151:handleKline:2218689: df_s.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec  ...  index      beta    zscore  signal
719  20230924   200000    235959  1695571199  ...    719  1.143992  1.302496     1.0
720  20230925   000000    035959  1695585599  ...    720  0.713147  0.265088     NaN
721  20230925   040000    075959  1695599999  ...    721  0.389653 -0.518665     NaN
722  20230925   080000    115959  1695614399  ...    722  0.259476 -0.839195    -1.0
723  20230925   120000    155959  1695628799  ...    723  0.251184 -0.866226    -1.0

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '50.756', 'enterprice': '26148.9', 'countrevence': '0', 'unrealprofit': '-1416.0924', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '26176.8', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-1, self.sign=-1


