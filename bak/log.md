# 20230426 16:26:01

## /root/FIL/strategy/amihud/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=993672.4896432, self.flagDict['side']='sell', self.tradeCount=2, self.count=43221
self.closeSec=1682497199, self.tradeDate='20230426', self.openTime='161500', self.closeTime='161959', self.symbol='BTCUSDT', self.open=28390.8, self.close=28437.7, self.high=28450.0, self.low=28390.7, self.vol=3054.178, self.amt=86833779.2582 
127.0.0.1 - - [26/Apr/2023 16:20:03] "POST / HTTP/1.1" 200 -
2023-04-26 16:20:05,899:INFO:amihud:main.py:172:handleKline:200676: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5944  20230426   155500    155959  ...         0.0        0.0       0
5945  20230426   160000    160459  ...         0.0        0.0       0
5946  20230426   160500    160959  ...         0.0        0.0       0
5947  20230426   161000    161459  ...         0.0        0.0       0
5948  20230426   161500    161959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-04-26 16:20:05,915:INFO:amihud:main.py:175:handleKline:200676: self.closeSec=1682497199, self.tradeDate='20230426', self.openTime='161500', self.closeTime='161959',self.symbol='BTCUSDT',self.open=28390.8, self.close=28437.7, self.high=28450.0, self.low=28390.7, self.vol=3054.178, self.amt=86833779.2582, ukdf['pct'].iloc[-1]=0.001652 , ukdf['amount'].iloc[-1]=86833779.2582, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5948, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '60.176', 'enterprice': '16529.3', 'countrevence': '0', 'unrealprofit': '-716508.4481319528', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '28436.18061905', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1
127.0.0.1 - - [26/Apr/2023 16:25:01] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=993672.4896432, self.flagDict['side']='sell', self.tradeCount=2, self.count=43222
self.closeSec=1682497499, self.tradeDate='20230426', self.openTime='162000', self.closeTime='162459', self.symbol='BTCUSDT', self.open=28437.8, self.close=28487.2, self.high=28578.0, self.low=28432.8, self.vol=8641.259, self.amt=246287347.16956 
2023-04-26 16:25:01,681:INFO:amihud:main.py:172:handleKline:200676: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5945  20230426   160000    160459  ...         0.0        0.0       0
5946  20230426   160500    160959  ...         0.0        0.0       0
5947  20230426   161000    161459  ...         0.0        0.0       0
5948  20230426   161500    161959  ...         0.0        0.0       0
5949  20230426   162000    162459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-04-26 16:25:01,681:INFO:amihud:main.py:175:handleKline:200676: self.closeSec=1682497499, self.tradeDate='20230426', self.openTime='162000', self.closeTime='162459',self.symbol='BTCUSDT',self.open=28437.8, self.close=28487.2, self.high=28578.0, self.low=28432.8, self.vol=8641.259, self.amt=246287347.16956, ukdf['pct'].iloc[-1]=0.001741 , ukdf['amount'].iloc[-1]=246287347.16956, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5949, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '60.176', 'enterprice': '16529.3', 'countrevence': '0', 'unrealprofit': '-719848.92245918624', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '28491.69235674', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1


## /root/FIL/strategy/factorcheck/log.txt ----- -----


--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=23, self.factor=0.43541661550691446, self.count=43783 

self.closeSec=1682495999, self.tradeDate='20230426', self.openTime='155500', self.closeTime='155959', self.symbol='BTCUSDT', self.open=28344.1, self.close=28365.0, self.high=28372.0, self.low=28336.6 
127.0.0.1 - - [26/Apr/2023 16:00:01] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=23, self.factor=0.43541661550691446, self.count=43784 

self.closeSec=1682496299, self.tradeDate='20230426', self.openTime='160000', self.closeTime='160459', self.symbol='BTCUSDT', self.open=28364.9, self.close=28387.1, self.high=28387.1, self.low=28357.1 
127.0.0.1 - - [26/Apr/2023 16:05:01] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [26/Apr/2023 16:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=23, self.factor=0.43541661550691446, self.count=43785 

self.closeSec=1682496599, self.tradeDate='20230426', self.openTime='160500', self.closeTime='160959', self.symbol='BTCUSDT', self.open=28387.3, self.close=28368.8, self.high=28388.5, self.low=28366.5 

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=23, self.factor=0.43541661550691446, self.count=43786 

self.closeSec=1682496899, self.tradeDate='20230426', self.openTime='161000', self.closeTime='161459', self.symbol='BTCUSDT', self.open=28368.8, self.close=28390.8, self.high=28397.1, self.low=28368.8 
127.0.0.1 - - [26/Apr/2023 16:15:02] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=23, self.factor=0.43541661550691446, self.count=43787 

self.closeSec=1682497199, self.tradeDate='20230426', self.openTime='161500', self.closeTime='161959', self.symbol='BTCUSDT', self.open=28390.8, self.close=28437.7, self.high=28450.0, self.low=28390.7 
127.0.0.1 - - [26/Apr/2023 16:20:02] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [26/Apr/2023 16:25:01] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=23, self.factor=0.43541661550691446, self.count=43788 

self.closeSec=1682497499, self.tradeDate='20230426', self.openTime='162000', self.closeTime='162459', self.symbol='BTCUSDT', self.open=28437.8, self.close=28487.2, self.high=28578.0, self.low=28432.8 


## /root/FIL/strategy/logic/log.txt ----- -----

2023-04-26 16:00:22,106:DEBUG:logic:main.py:463:getModel:885513: df_s.iloc[-5:,:] :
          date closeTime     open  ...    alpha58   alpha67   alpha72
5785  20230426    132959  28315.0  ...  53.750000  0.611977  0.191068
5786  20230426    135959  28378.4  ...  54.166667  0.612173  0.183206
5787  20230426    142959  28380.0  ...  53.750000  0.605598  0.182500
5788  20230426    145959  28348.3  ...  54.166667  0.609565  0.180439
5789  20230426    152959  28377.6  ...  54.166667  0.601636  0.180317

[5 rows x 33 columns]
0.5571955719557196
acc is : 0.5571955719557196
2023-04-26 16:00:22,208:INFO:logic:main.py:468:getModel:885513: df_pred.iloc[-5:,:] :
     pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
537     0  0.512905  0.487095       1  ...  0.873258   1.0    0.0  0.934745
538     0  0.504605  0.495395       0  ...  0.872289   1.0    0.0  0.933708
539     1  0.496907  0.503093       1  ...  0.873187   1.0    0.0  0.934670
540     0  0.506272  0.493728       0  ...  0.872033   1.0    0.0  0.933435
541     1  0.493095  0.506905       1  ...  0.872799   1.0    0.0  0.934255

[5 rows x 10 columns]
2023-04-26 16:00:22,222:INFO:logic:main.py:478:getModel:885513: df_panel.iloc[-5:,:] :
    pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
45     0  0.513312  0.486688       1  ...  0.873258   1.0    0.0  0.933055
46     0  0.505165  0.494835       0  ...  0.872289   1.0    0.0  0.932513
47     1  0.497199  0.502801       1  ...  0.873187   1.0    0.0  0.931846
48     0  0.506301  0.493699       0  ...  0.872033   1.0    0.0  0.928362
49     1  0.493095  0.506905       1  ...  0.872799   1.0    0.0  0.934255

[5 rows x 10 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': []}


## /root/FIL/strategy/modifiedmom/log.txt ----- -----


--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=21889 

self.closeSec=1682494199, self.tradeDate='20230426', self.openTime='152000', self.closeTime='152959', self.symbol='BTCUSDT', self.open='28380.7', self.close='28340.1'
127.0.0.1 - - [26/Apr/2023 15:30:01] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [26/Apr/2023 15:40:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=21890 

self.closeSec=1682494799, self.tradeDate='20230426', self.openTime='153000', self.closeTime='153959', self.symbol='BTCUSDT', self.open='28340', self.close='28321.6'

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=21891 

self.closeSec=1682495399, self.tradeDate='20230426', self.openTime='154000', self.closeTime='154959', self.symbol='BTCUSDT', self.open='28321.7', self.close='28324.6'
127.0.0.1 - - [26/Apr/2023 15:50:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=21892 

self.closeSec=1682495999, self.tradeDate='20230426', self.openTime='155000', self.closeTime='155959', self.symbol='BTCUSDT', self.open='28324.5', self.close='28365'
127.0.0.1 - - [26/Apr/2023 16:00:02] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=21893 

self.closeSec=1682496599, self.tradeDate='20230426', self.openTime='160000', self.closeTime='160959', self.symbol='BTCUSDT', self.open='28364.9', self.close='28368.8'
127.0.0.1 - - [26/Apr/2023 16:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=21894 

self.closeSec=1682497199, self.tradeDate='20230426', self.openTime='161000', self.closeTime='161959', self.symbol='BTCUSDT', self.open='28368.8', self.close='28437.7'
127.0.0.1 - - [26/Apr/2023 16:20:03] "POST / HTTP/1.1" 200 -


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

127.0.0.1 - - [26/Apr/2023 15:30:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=21890 

self.closeSec=1682494199, self.tradeDate='20230426', self.openTime='152000', self.closeTime='152959', self.symbol='BTCUSDT', self.open='28380.7', self.close='28340.1'

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=21891 

self.closeSec=1682494799, self.tradeDate='20230426', self.openTime='153000', self.closeTime='153959', self.symbol='BTCUSDT', self.open='28340', self.close='28321.6'
127.0.0.1 - - [26/Apr/2023 15:40:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=21892 

self.closeSec=1682495399, self.tradeDate='20230426', self.openTime='154000', self.closeTime='154959', self.symbol='BTCUSDT', self.open='28321.7', self.close='28324.6'
127.0.0.1 - - [26/Apr/2023 15:50:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=21893 

self.closeSec=1682495999, self.tradeDate='20230426', self.openTime='155000', self.closeTime='155959', self.symbol='BTCUSDT', self.open='28324.5', self.close='28365'
127.0.0.1 - - [26/Apr/2023 16:00:02] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=21894 

self.closeSec=1682496599, self.tradeDate='20230426', self.openTime='160000', self.closeTime='160959', self.symbol='BTCUSDT', self.open='28364.9', self.close='28368.8'
127.0.0.1 - - [26/Apr/2023 16:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=21895 

self.closeSec=1682497199, self.tradeDate='20230426', self.openTime='161000', self.closeTime='161959', self.symbol='BTCUSDT', self.open='28368.8', self.close='28437.7'
127.0.0.1 - - [26/Apr/2023 16:20:04] "POST / HTTP/1.1" 200 -


## /root/FIL/strategy/similarity/log.txt ----- -----


--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=21890 

self.closeSec=1682494199, self.tradeDate='20230426', self.openTime='152000', self.closeTime='152959', self.symbol='BTCUSDT', self.open='28380.7', self.close='28340.1'
127.0.0.1 - - [26/Apr/2023 15:30:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=21891 

self.closeSec=1682494799, self.tradeDate='20230426', self.openTime='153000', self.closeTime='153959', self.symbol='BTCUSDT', self.open='28340', self.close='28321.6'
127.0.0.1 - - [26/Apr/2023 15:40:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=21892 

self.closeSec=1682495399, self.tradeDate='20230426', self.openTime='154000', self.closeTime='154959', self.symbol='BTCUSDT', self.open='28321.7', self.close='28324.6'
127.0.0.1 - - [26/Apr/2023 15:50:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=21893 

self.closeSec=1682495999, self.tradeDate='20230426', self.openTime='155000', self.closeTime='155959', self.symbol='BTCUSDT', self.open='28324.5', self.close='28365'
127.0.0.1 - - [26/Apr/2023 16:00:02] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=21894 

self.closeSec=1682496599, self.tradeDate='20230426', self.openTime='160000', self.closeTime='160959', self.symbol='BTCUSDT', self.open='28364.9', self.close='28368.8'
127.0.0.1 - - [26/Apr/2023 16:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=21895 

self.closeSec=1682497199, self.tradeDate='20230426', self.openTime='161000', self.closeTime='161959', self.symbol='BTCUSDT', self.open='28368.8', self.close='28437.7'
127.0.0.1 - - [26/Apr/2023 16:20:04] "POST / HTTP/1.1" 200 -


## /root/FIL/strategy/sr_min/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=0, self.total=1000000.0, self.flagDict['side']='', self.tradeCount=0, self.count=39219
self.closeSec=1682497199, self.tradeDate='20230426', self.openTime='161500', self.closeTime='161959', self.symbol='BTCUSDT', self.open=28390.8, self.close=28437.7, self.high=28450.0, self.low=28390.7, self.vol=3054.178, self.amt=86833779.2582 
127.0.0.1 - - [26/Apr/2023 16:20:03] "POST / HTTP/1.1" 200 -
2023-04-26 16:20:06,096:INFO:sr_min:main.py:172:handleKline:449472: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5944  20230426   155500    155959  ...         0.0        0.0       0
5945  20230426   160000    160459  ...         0.0        0.0       0
5946  20230426   160500    160959  ...         0.0        0.0       0
5947  20230426   161000    161459  ...         0.0        0.0       0
5948  20230426   161500    161959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-04-26 16:20:06,108:INFO:sr_min:main.py:175:handleKline:449472: self.closeSec=1682497199, self.tradeDate='20230426', self.openTime='161500', self.closeTime='161959',self.symbol='BTCUSDT',self.open=28390.8, self.close=28437.7, self.high=28450.0, self.low=28390.7, self.vol=3054.178, self.amt=86833779.2582, ukdf['pct'].iloc[-1]=0.001652 , ukdf['amount'].iloc[-1]=86833779.2582, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5948, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': []}
type(curSign)=<class 'int'>, curSign=0, self.sign=0
127.0.0.1 - - [26/Apr/2023 16:25:01] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=0, self.total=1000000.0, self.flagDict['side']='', self.tradeCount=0, self.count=39220
self.closeSec=1682497499, self.tradeDate='20230426', self.openTime='162000', self.closeTime='162459', self.symbol='BTCUSDT', self.open=28437.8, self.close=28487.2, self.high=28578.0, self.low=28432.8, self.vol=8641.259, self.amt=246287347.16956 
2023-04-26 16:25:01,687:INFO:sr_min:main.py:172:handleKline:449472: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5945  20230426   160000    160459  ...         0.0        0.0       0
5946  20230426   160500    160959  ...         0.0        0.0       0
5947  20230426   161000    161459  ...         0.0        0.0       0
5948  20230426   161500    161959  ...         0.0        0.0       0
5949  20230426   162000    162459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-04-26 16:25:01,688:INFO:sr_min:main.py:175:handleKline:449472: self.closeSec=1682497499, self.tradeDate='20230426', self.openTime='162000', self.closeTime='162459',self.symbol='BTCUSDT',self.open=28437.8, self.close=28487.2, self.high=28578.0, self.low=28432.8, self.vol=8641.259, self.amt=246287347.16956, ukdf['pct'].iloc[-1]=0.001741 , ukdf['amount'].iloc[-1]=246287347.16956, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5949, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': []}
type(curSign)=<class 'int'>, curSign=0, self.sign=0


## /root/FIL/strategy/s_rsrs/log.txt ----- -----

721  20230426   040000    075959  1682467199  ...    721  0.718385 -0.013986     NaN
722  20230426   080000    115959  1682481599  ...    722  0.644339 -0.197825     NaN

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '52.48', 'enterprice': '27388.7', 'countrevence': '0', 'unrealprofit': '-47963.2681904512', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '28302.63422619', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-9223372036854775808, self.sign=-1
--handleKline--:  127.0.0.1 - - [26/Apr/2023 16:00:01] "POST / HTTP/1.1" 200 -
version='2.0.0', self.name='s_rsrs', self.symbol='BTCUSDT', interval='4h', intervalSec=14400, wid=25, thd=0.6, self.sign=-1, self.total=1435921.617024, self.flagDict['side']='sell', self.tradeCount=31, self.count=912
self.closeSec=1682495999, self.tradeDate='20230426', self.openTime='120000', self.closeTime='155959', self.symbol='BTCUSDT', self.open=28296.1, self.close=28365.0, self.high=28588.0, self.low=28285.9, self.vol=62803.722, self.amt=1782335834.06983 
2023-04-26 16:00:01,964:INFO:s_rsrs:main.py:141:handleKline:185271: self.closeSec=1682495999, self.tradeDate='20230426', self.openTime='120000', self.closeTime='155959',self.symbol='BTCUSDT',self.open=28296.1, self.close=28365.0, self.high=28588.0, self.low=28285.9, self.vol=62803.722, self.amt=1782335834.06983 
2023-04-26 16:00:02,045:INFO:s_rsrs:main.py:142:handleKline:185271: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime  ...         vol           amt       pct
719  20230425   200000    235959  ...   74964.782  2.049648e+09 -0.001921
720  20230426   000000    035959  ...  115386.167  3.178022e+09  0.009755
721  20230426   040000    075959  ...  162175.001  4.557367e+09  0.025025
722  20230426   080000    115959  ...   71407.185  2.024510e+09  0.000336
723  20230426   120000    155959  ...   62803.722  1.782336e+09  0.002431

[5 rows x 11 columns]
2023-04-26 16:00:04,295:INFO:s_rsrs:main.py:151:handleKline:185271: df_s.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec  ...  index      beta    zscore  signal
719  20230425   200000    235959  1682438399  ...    719  0.399294 -0.928003    -1.0
720  20230426   000000    035959  1682452799  ...    720  0.197066 -1.444367    -1.0
721  20230426   040000    075959  1682467199  ...    721  0.718385 -0.013986     NaN
722  20230426   080000    115959  1682481599  ...    722  0.644339 -0.197825     NaN
723  20230426   120000    155959  1682495999  ...    723  0.687079 -0.037325     NaN

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '52.48', 'enterprice': '27388.7', 'countrevence': '0', 'unrealprofit': '-51430.829003008', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '28368.7081746', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-9223372036854775808, self.sign=-1


