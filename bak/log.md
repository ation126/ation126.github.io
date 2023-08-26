# 20230826 16:26:02

## /root/FIL/strategy/amihud/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=373746.4768026, self.flagDict['side']='sell', self.tradeCount=2, self.count=30004
self.closeSec=1693037999, self.tradeDate='20230826', self.openTime='161500', self.closeTime='161959', self.symbol='BTCUSDT', self.open=26048.6, self.close=26047.9, self.high=26048.6, self.low=26040.3, self.vol=124.033, self.amt=3230361.9646 
127.0.0.1 - - [26/Aug/2023 16:20:01] "POST / HTTP/1.1" 200 -
2023-08-26 16:20:05,341:INFO:amihud:main.py:172:handleKline:2219019: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5939  20230826   155500    155959  ...         0.0        0.0       0
5940  20230826   160000    160459  ...         0.0        0.0       0
5941  20230826   160500    160959  ...         0.0        0.0       0
5942  20230826   161000    161459  ...         0.0        0.0       0
5943  20230826   161500    161959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-08-26 16:20:05,350:INFO:amihud:main.py:175:handleKline:2219019: self.closeSec=1693037999, self.tradeDate='20230826', self.openTime='161500', self.closeTime='161959',self.symbol='BTCUSDT',self.open=26048.6, self.close=26047.9, self.high=26048.6, self.low=26040.3, self.vol=124.033, self.amt=3230361.9646, ukdf['pct'].iloc[-1]=-2.7e-05 , ukdf['amount'].iloc[-1]=3230361.9646, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5943, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '13.926', 'enterprice': '26864.9', 'countrevence': '0', 'unrealprofit': '11376.1494', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '26048', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1
--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=373746.4768026, self.flagDict['side']='sell', self.tradeCount=2, self.count=30005
self.closeSec=1693038299, self.tradeDate='20230826', self.openTime='162000', self.closeTime='162459', self.symbol='BTCUSDT', self.open=26048.0, self.close=26045.0, self.high=26048.7, self.low=26045.0, self.vol=79.527, self.amt=2071539.3363 
127.0.0.1 - - [26/Aug/2023 16:25:00] "POST / HTTP/1.1" 200 -
2023-08-26 16:25:00,818:INFO:amihud:main.py:172:handleKline:2219019: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5940  20230826   160000    160459  ...         0.0        0.0       0
5941  20230826   160500    160959  ...         0.0        0.0       0
5942  20230826   161000    161459  ...         0.0        0.0       0
5943  20230826   161500    161959  ...         0.0        0.0       0
5944  20230826   162000    162459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-08-26 16:25:00,818:INFO:amihud:main.py:175:handleKline:2219019: self.closeSec=1693038299, self.tradeDate='20230826', self.openTime='162000', self.closeTime='162459',self.symbol='BTCUSDT',self.open=26048.0, self.close=26045.0, self.high=26048.7, self.low=26045.0, self.vol=79.527, self.amt=2071539.3363, ukdf['pct'].iloc[-1]=-0.000111 , ukdf['amount'].iloc[-1]=2071539.3363, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5944, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '13.926', 'enterprice': '26864.9', 'countrevence': '0', 'unrealprofit': '11394.94934110434', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '26046.65001141', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1


## /root/FIL/strategy/factorcheck/log.txt ----- -----


--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.714181719035411, self.count=30002 

self.closeSec=1693036799, self.tradeDate='20230826', self.openTime='155500', self.closeTime='155959', self.symbol='BTCUSDT', self.open=26054.0, self.close=26039.7, self.high=26054.0, self.low=26033.7 
127.0.0.1 - - [26/Aug/2023 16:00:00] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.714181719035411, self.count=30003 

self.closeSec=1693037099, self.tradeDate='20230826', self.openTime='160000', self.closeTime='160459', self.symbol='BTCUSDT', self.open=26039.8, self.close=26037.0, self.high=26039.8, self.low=26028.2 
127.0.0.1 - - [26/Aug/2023 16:05:00] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [26/Aug/2023 16:10:00] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.714181719035411, self.count=30004 

self.closeSec=1693037399, self.tradeDate='20230826', self.openTime='160500', self.closeTime='160959', self.symbol='BTCUSDT', self.open=26037.0, self.close=26043.7, self.high=26043.8, self.low=26036.9 

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.714181719035411, self.count=30005 

self.closeSec=1693037699, self.tradeDate='20230826', self.openTime='161000', self.closeTime='161459', self.symbol='BTCUSDT', self.open=26043.7, self.close=26048.6, self.high=26048.6, self.low=26043.7 
127.0.0.1 - - [26/Aug/2023 16:15:00] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.714181719035411, self.count=30006 

self.closeSec=1693037999, self.tradeDate='20230826', self.openTime='161500', self.closeTime='161959', self.symbol='BTCUSDT', self.open=26048.6, self.close=26047.9, self.high=26048.6, self.low=26040.3 
127.0.0.1 - - [26/Aug/2023 16:20:01] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [26/Aug/2023 16:25:00] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.714181719035411, self.count=30007 

self.closeSec=1693038299, self.tradeDate='20230826', self.openTime='162000', self.closeTime='162459', self.symbol='BTCUSDT', self.open=26048.0, self.close=26045.0, self.high=26048.7, self.low=26045.0 


## /root/FIL/strategy/logic/log.txt ----- -----

2023-08-26 16:00:18,565:DEBUG:logic:main.py:463:getModel:2218526: df_s.iloc[-5:,:] :
          date closeTime     open  ...    alpha58   alpha67   alpha72
5785  20230826    132959  26065.2  ...  50.833333  0.489841  0.486035
5786  20230826    135959  26049.2  ...  51.250000  0.490337  0.484046
5787  20230826    142959  26051.1  ...  50.833333  0.488957  0.482849
5788  20230826    145959  26045.7  ...  51.250000  0.494631  0.479153
5789  20230826    152959  26066.8  ...  51.250000  0.490914  0.477427

[5 rows x 33 columns]
0.5369003690036901
acc is : 0.5369003690036901
2023-08-26 16:00:18,624:INFO:logic:main.py:468:getModel:2218526: df_pred.iloc[-5:,:] :
     pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
537     1  0.486034  0.513966       1  ...  1.070852  -1.0    0.0  0.885246
538     1  0.481795  0.518205       0  ...  1.071074  -1.0    0.0  0.885062
539     1  0.484817  0.515183       1  ...  1.070206  -1.0    0.0  0.885779
540     1  0.494858  0.505142       0  ...  1.070785  -1.0    0.0  0.885300
541     1  0.484673  0.515327       0  ...  1.071319  -1.0    0.0  0.884858

[5 rows x 10 columns]
2023-08-26 16:00:18,635:INFO:logic:main.py:478:getModel:2218526: df_panel.iloc[-5:,:] :
    pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
45     1  0.486075  0.513925       1  ...  1.070852  -1.0    0.0  0.884563
46     1  0.481786  0.518214       0  ...  1.071074  -1.0    0.0  0.885110
47     1  0.484853  0.515147       1  ...  1.062903  -1.0    0.0  0.886056
48     1  0.495034  0.504966       0  ...  1.070785  -1.0    0.0  0.885559
49     1  0.484673  0.515327       0  ...  1.071319  -1.0    0.0  0.884858

[5 rows x 10 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '28.231', 'enterprice': '26402', 'countrevence': '0', 'unrealprofit': '10332.546', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '26036', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}


## /root/FIL/strategy/modifiedmom/log.txt ----- -----


--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=14999 

self.closeSec=1693034999, self.tradeDate='20230826', self.openTime='152000', self.closeTime='152959', self.symbol='BTCUSDT', self.open='26057.8', self.close='26052.7'
127.0.0.1 - - [26/Aug/2023 15:30:01] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [26/Aug/2023 15:40:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=15000 

self.closeSec=1693035599, self.tradeDate='20230826', self.openTime='153000', self.closeTime='153959', self.symbol='BTCUSDT', self.open='26052.7', self.close='26049.5'
127.0.0.1 - - [26/Aug/2023 15:50:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=15001 

self.closeSec=1693036199, self.tradeDate='20230826', self.openTime='154000', self.closeTime='154959', self.symbol='BTCUSDT', self.open='26049.5', self.close='26041.1'

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=15002 

self.closeSec=1693036799, self.tradeDate='20230826', self.openTime='155000', self.closeTime='155959', self.symbol='BTCUSDT', self.open='26041.2', self.close='26039.7'
127.0.0.1 - - [26/Aug/2023 16:00:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=15003 

self.closeSec=1693037399, self.tradeDate='20230826', self.openTime='160000', self.closeTime='160959', self.symbol='BTCUSDT', self.open='26039.8', self.close='26043.8'
127.0.0.1 - - [26/Aug/2023 16:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=15004 

self.closeSec=1693037999, self.tradeDate='20230826', self.openTime='161000', self.closeTime='161959', self.symbol='BTCUSDT', self.open='26043.7', self.close='26048'
127.0.0.1 - - [26/Aug/2023 16:20:04] "POST / HTTP/1.1" 200 -


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


--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=15002 

self.closeSec=1693034999, self.tradeDate='20230826', self.openTime='152000', self.closeTime='152959', self.symbol='BTCUSDT', self.open='26057.8', self.close='26052.7'
127.0.0.1 - - [26/Aug/2023 15:30:01] "POST / HTTP/1.1" 200 -

--handleKline--:  127.0.0.1 - - [26/Aug/2023 15:40:01] "POST / HTTP/1.1" 200 -
self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=15003 

self.closeSec=1693035599, self.tradeDate='20230826', self.openTime='153000', self.closeTime='153959', self.symbol='BTCUSDT', self.open='26052.7', self.close='26049.5'
127.0.0.1 - - [26/Aug/2023 15:50:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=15004 

self.closeSec=1693036199, self.tradeDate='20230826', self.openTime='154000', self.closeTime='154959', self.symbol='BTCUSDT', self.open='26049.5', self.close='26041.1'

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=15005 

self.closeSec=1693036799, self.tradeDate='20230826', self.openTime='155000', self.closeTime='155959', self.symbol='BTCUSDT', self.open='26041.2', self.close='26039.7'
127.0.0.1 - - [26/Aug/2023 16:00:01] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [26/Aug/2023 16:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=15006 

self.closeSec=1693037399, self.tradeDate='20230826', self.openTime='160000', self.closeTime='160959', self.symbol='BTCUSDT', self.open='26039.8', self.close='26043.8'

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=15007 

self.closeSec=1693037999, self.tradeDate='20230826', self.openTime='161000', self.closeTime='161959', self.symbol='BTCUSDT', self.open='26043.7', self.close='26048'
127.0.0.1 - - [26/Aug/2023 16:20:04] "POST / HTTP/1.1" 200 -


## /root/FIL/strategy/similarity/log.txt ----- -----

127.0.0.1 - - [26/Aug/2023 15:30:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=15002 

self.closeSec=1693034999, self.tradeDate='20230826', self.openTime='152000', self.closeTime='152959', self.symbol='BTCUSDT', self.open='26057.8', self.close='26052.7'

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=15003 

self.closeSec=1693035599, self.tradeDate='20230826', self.openTime='153000', self.closeTime='153959', self.symbol='BTCUSDT', self.open='26052.7', self.close='26049.5'
127.0.0.1 - - [26/Aug/2023 15:40:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=15004 

self.closeSec=1693036199, self.tradeDate='20230826', self.openTime='154000', self.closeTime='154959', self.symbol='BTCUSDT', self.open='26049.5', self.close='26041.1'
127.0.0.1 - - [26/Aug/2023 15:50:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=15005 

self.closeSec=1693036799, self.tradeDate='20230826', self.openTime='155000', self.closeTime='155959', self.symbol='BTCUSDT', self.open='26041.2', self.close='26039.7'
127.0.0.1 - - [26/Aug/2023 16:00:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=15006 

self.closeSec=1693037399, self.tradeDate='20230826', self.openTime='160000', self.closeTime='160959', self.symbol='BTCUSDT', self.open='26039.8', self.close='26043.8'
127.0.0.1 - - [26/Aug/2023 16:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=15007 

self.closeSec=1693037999, self.tradeDate='20230826', self.openTime='161000', self.closeTime='161959', self.symbol='BTCUSDT', self.open='26043.7', self.close='26048'
127.0.0.1 - - [26/Aug/2023 16:20:03] "POST / HTTP/1.1" 200 -


## /root/FIL/strategy/sr_min/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=1, self.total=996015.990996, self.flagDict['side']='buy', self.tradeCount=1, self.count=30004
self.closeSec=1693037999, self.tradeDate='20230826', self.openTime='161500', self.closeTime='161959', self.symbol='BTCUSDT', self.open=26048.6, self.close=26047.9, self.high=26048.6, self.low=26040.3, self.vol=124.033, self.amt=3230361.9646 
127.0.0.1 - - [26/Aug/2023 16:20:01] "POST / HTTP/1.1" 200 -
2023-08-26 16:20:05,331:INFO:sr_min:main.py:172:handleKline:2219263: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5939  20230826   155500    155959  ...         0.0        0.0       0
5940  20230826   160000    160459  ...         0.0        0.0       0
5941  20230826   160500    160959  ...         0.0        0.0       0
5942  20230826   161000    161459  ...         0.0        0.0       0
5943  20230826   161500    161959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-08-26 16:20:05,334:INFO:sr_min:main.py:175:handleKline:2219263: self.closeSec=1693037999, self.tradeDate='20230826', self.openTime='161500', self.closeTime='161959',self.symbol='BTCUSDT',self.open=26048.6, self.close=26047.9, self.high=26048.6, self.low=26040.3, self.vol=124.033, self.amt=3230361.9646, ukdf['pct'].iloc[-1]=-2.7e-05 , ukdf['amount'].iloc[-1]=3230361.9646, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5943, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '37.141', 'enterprice': '26844', 'countrevence': '0', 'unrealprofit': '-29564.236', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '26048', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=1
127.0.0.1 - - [26/Aug/2023 16:25:00] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=1, self.total=996015.990996, self.flagDict['side']='buy', self.tradeCount=1, self.count=30005
self.closeSec=1693038299, self.tradeDate='20230826', self.openTime='162000', self.closeTime='162459', self.symbol='BTCUSDT', self.open=26048.0, self.close=26045.0, self.high=26048.7, self.low=26045.0, self.vol=79.527, self.amt=2071539.3363 
2023-08-26 16:25:00,818:INFO:sr_min:main.py:172:handleKline:2219263: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5940  20230826   160000    160459  ...         0.0        0.0       0
5941  20230826   160500    160959  ...         0.0        0.0       0
5942  20230826   161000    161459  ...         0.0        0.0       0
5943  20230826   161500    161959  ...         0.0        0.0       0
5944  20230826   162000    162459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-08-26 16:25:00,819:INFO:sr_min:main.py:175:handleKline:2219263: self.closeSec=1693038299, self.tradeDate='20230826', self.openTime='162000', self.closeTime='162459',self.symbol='BTCUSDT',self.open=26048.0, self.close=26045.0, self.high=26048.7, self.low=26045.0, self.vol=79.527, self.amt=2071539.3363, ukdf['pct'].iloc[-1]=-0.000111 , ukdf['amount'].iloc[-1]=2071539.3363, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5944, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '37.141', 'enterprice': '26844', 'countrevence': '0', 'unrealprofit': '-29614.37592622119', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '26046.65001141', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=1


## /root/FIL/strategy/s_rsrs/log.txt ----- -----

721  20230826   040000    075959  1693007999  ...    721  0.169228 -0.477095     NaN
722  20230826   080000    115959  1693022399  ...    722  0.162292 -0.480094     NaN

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '51.388', 'enterprice': '29432.6', 'countrevence': '0', 'unrealprofit': '172468.4056', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '26076.4', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-9223372036854775808, self.sign=-1
--handleKline--:  version='2.0.0', self.name='s_rsrs', self.symbol='BTCUSDT', interval='4h', intervalSec=14400, wid=25, thd=0.6, self.sign=-1, self.total=1510969.9663512, self.flagDict['side']='sell', self.tradeCount=20, self.count=625127.0.0.1 - - [26/Aug/2023 16:00:01] "POST / HTTP/1.1" 200 -

self.closeSec=1693036799, self.tradeDate='20230826', self.openTime='120000', self.closeTime='155959', self.symbol='BTCUSDT', self.open=26076.4, self.close=26039.7, self.high=26079.2, self.low=26033.7, self.vol=8045.871, self.amt=209620063.2891 
2023-08-26 16:00:01,564:INFO:s_rsrs:main.py:141:handleKline:2218689: self.closeSec=1693036799, self.tradeDate='20230826', self.openTime='120000', self.closeTime='155959',self.symbol='BTCUSDT',self.open=26076.4, self.close=26039.7, self.high=26079.2, self.low=26033.7, self.vol=8045.871, self.amt=209620063.2891 
2023-08-26 16:00:01,582:INFO:s_rsrs:main.py:142:handleKline:2218689: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime  ...         vol           amt       pct
719  20230825   200000    235959  ...  138297.912  3.598672e+09 -0.006528
720  20230826   000000    035959  ...   45731.022  1.186422e+09  0.001717
721  20230826   040000    075959  ...   17754.194  4.621762e+08  0.003459
722  20230826   080000    115959  ...   13952.931  3.636576e+08  0.000948
723  20230826   120000    155959  ...    8045.871  2.096201e+08 -0.001407

[5 rows x 11 columns]
2023-08-26 16:00:02,324:INFO:s_rsrs:main.py:151:handleKline:2218689: df_s.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec  ...  index      beta    zscore  signal
719  20230825   200000    235959  1692979199  ...    719  0.159068 -0.535499     NaN
720  20230826   000000    035959  1692993599  ...    720  0.172074 -0.485241     NaN
721  20230826   040000    075959  1693007999  ...    721  0.169228 -0.477095     NaN
722  20230826   080000    115959  1693022399  ...    722  0.162292 -0.480094     NaN
723  20230826   120000    155959  1693036799  ...    723  0.154498 -0.485747     NaN

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '51.388', 'enterprice': '29432.6', 'countrevence': '0', 'unrealprofit': '174349.2064', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '26039.8', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-9223372036854775808, self.sign=-1


