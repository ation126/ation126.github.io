# 20231013 16:26:02

## /root/FIL/strategy/amihud/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=373746.4768026, self.flagDict['side']='sell', self.tradeCount=2, self.count=43828
self.closeSec=1697185199, self.tradeDate='20231013', self.openTime='161500', self.closeTime='161959', self.symbol='BTCUSDT', self.open=26862.5, self.close=26839.3, self.high=26876.7, self.low=26839.2, self.vol=770.378, self.amt=20686327.5816 
127.0.0.1 - - [13/Oct/2023 16:20:03] "POST / HTTP/1.1" 200 -
2023-10-13 16:20:07,274:INFO:amihud:main.py:172:handleKline:2219019: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5951  20231013   155500    155959  ...         0.0        0.0       0
5952  20231013   160000    160459  ...         0.0        0.0       0
5953  20231013   160500    160959  ...         0.0        0.0       0
5954  20231013   161000    161459  ...         0.0        0.0       0
5955  20231013   161500    161959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-10-13 16:20:07,277:INFO:amihud:main.py:175:handleKline:2219019: self.closeSec=1697185199, self.tradeDate='20231013', self.openTime='161500', self.closeTime='161959',self.symbol='BTCUSDT',self.open=26862.5, self.close=26839.3, self.high=26876.7, self.low=26839.2, self.vol=770.378, self.amt=20686327.5816, ukdf['pct'].iloc[-1]=-0.000923 , ukdf['amount'].iloc[-1]=20686327.5816, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5955, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '13.926', 'enterprice': '26864.9', 'countrevence': '0', 'unrealprofit': '330.0462', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '26841.2', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1
--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=373746.4768026, self.flagDict['side']='sell', self.tradeCount=2, self.count=43829
self.closeSec=1697185499, self.tradeDate='20231013', self.openTime='162000', self.closeTime='162459', self.symbol='BTCUSDT', self.open=26840.0, self.close=26850.6, self.high=26858.0, self.low=26832.7, self.vol=589.151, self.amt=15813831.0769 
127.0.0.1 - - [13/Oct/2023 16:25:01] "POST / HTTP/1.1" 200 -
2023-10-13 16:25:03,138:INFO:amihud:main.py:172:handleKline:2219019: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5952  20231013   160000    160459  ...         0.0        0.0       0
5953  20231013   160500    160959  ...         0.0        0.0       0
5954  20231013   161000    161459  ...         0.0        0.0       0
5955  20231013   161500    161959  ...         0.0        0.0       0
5956  20231013   162000    162459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-10-13 16:25:03,147:INFO:amihud:main.py:175:handleKline:2219019: self.closeSec=1697185499, self.tradeDate='20231013', self.openTime='162000', self.closeTime='162459',self.symbol='BTCUSDT',self.open=26840.0, self.close=26850.6, self.high=26858.0, self.low=26832.7, self.vol=589.151, self.amt=15813831.0769, ukdf['pct'].iloc[-1]=0.000421 , ukdf['amount'].iloc[-1]=15813831.0769, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5956, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '13.926', 'enterprice': '26864.9', 'countrevence': '0', 'unrealprofit': '169.92370020318', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '26852.69809707', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1


## /root/FIL/strategy/factorcheck/log.txt ----- -----


--handleKline--: 127.0.0.1 - - [13/Oct/2023 16:00:00] "POST / HTTP/1.1" 200 -
 version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.714181719035411, self.count=43826 

self.closeSec=1697183999, self.tradeDate='20231013', self.openTime='155500', self.closeTime='155959', self.symbol='BTCUSDT', self.open=26847.5, self.close=26861.1, self.high=26862.6, self.low=26844.8 

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.714181719035411, self.count=43827 

self.closeSec=1697184299, self.tradeDate='20231013', self.openTime='160000', self.closeTime='160459', self.symbol='BTCUSDT', self.open=26857.9, self.close=26877.1, self.high=26883.4, self.low=26854.2 
127.0.0.1 - - [13/Oct/2023 16:05:00] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [13/Oct/2023 16:10:00] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.714181719035411, self.count=43828 

self.closeSec=1697184599, self.tradeDate='20231013', self.openTime='160500', self.closeTime='160959', self.symbol='BTCUSDT', self.open=26878.5, self.close=26870.0, self.high=26892.3, self.low=26866.0 

--handleKline--: 127.0.0.1 - - [13/Oct/2023 16:15:00] "POST / HTTP/1.1" 200 -
 version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.714181719035411, self.count=43829 

self.closeSec=1697184899, self.tradeDate='20231013', self.openTime='161000', self.closeTime='161459', self.symbol='BTCUSDT', self.open=26870.1, self.close=26864.1, self.high=26875.9, self.low=26862.0 

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.714181719035411, self.count=43830 

self.closeSec=1697185199, self.tradeDate='20231013', self.openTime='161500', self.closeTime='161959', self.symbol='BTCUSDT', self.open=26862.5, self.close=26839.3, self.high=26876.7, self.low=26839.2 
127.0.0.1 - - [13/Oct/2023 16:20:03] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.714181719035411, self.count=43831 

self.closeSec=1697185499, self.tradeDate='20231013', self.openTime='162000', self.closeTime='162459', self.symbol='BTCUSDT', self.open=26840.0, self.close=26850.6, self.high=26858.0, self.low=26832.7 
127.0.0.1 - - [13/Oct/2023 16:25:01] "POST / HTTP/1.1" 200 -


## /root/FIL/strategy/logic/log.txt ----- -----

2023-10-13 16:00:17,416:DEBUG:logic:main.py:463:getModel:2218526: df_s.iloc[-5:,:] :
          date closeTime     open  ...    alpha58   alpha67   alpha72
5785  20231013    132959  26792.6  ...  48.333333  0.467826  0.413916
5786  20231013    135959  26789.0  ...  48.333333  0.474848  0.398345
5787  20231013    142959  26809.3  ...  47.916667  0.469584  0.387177
5788  20231013    145959  26792.5  ...  48.333333  0.471036  0.375936
5789  20231013    152959  26796.5  ...  48.333333  0.497232  0.355803

[5 rows x 33 columns]
0.544280442804428
acc is : 0.544280442804428
2023-10-13 16:00:17,479:INFO:logic:main.py:468:getModel:2218526: df_pred.iloc[-5:,:] :
     pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
537     1  0.498361  0.501639       1  ...  1.003073  -1.0    0.0  0.960304
538     0  0.506267  0.493733       0  ...  1.003705  -1.0    0.0  0.959699
539     1  0.496277  0.503723       1  ...  1.003552  -1.0    0.0  0.959846
540     0  0.501292  0.498708       1  ...  1.000687  -1.0    0.0  0.962586
541     0  0.527003  0.472997       0  ...  1.001130  -1.0    0.0  0.962160

[5 rows x 10 columns]
2023-10-13 16:00:17,491:INFO:logic:main.py:478:getModel:2218526: df_panel.iloc[-5:,:] :
    pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
45     1  0.498157  0.501843       1  ...  1.007619  -1.0    0.0  0.957711
46     0  0.506132  0.493868       0  ...  1.008680  -1.0    0.0  0.961366
47     1  0.495833  0.504167       1  ...  1.008526  -1.0    0.0  0.957654
48     0  0.501127  0.498873       1  ...  1.007011  -1.0    0.0  0.961691
49     0  0.527003  0.472997       0  ...  1.001130  -1.0    0.0  0.962160

[5 rows x 10 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '24.051', 'enterprice': '26768.8', 'countrevence': '0', 'unrealprofit': '-2217.5022', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '26861', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}


## /root/FIL/strategy/modifiedmom/log.txt ----- -----

127.0.0.1 - - [13/Oct/2023 15:30:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=21911 

self.closeSec=1697182199, self.tradeDate='20231013', self.openTime='152000', self.closeTime='152959', self.symbol='BTCUSDT', self.open='26881.7', self.close='26873'
127.0.0.1 - - [13/Oct/2023 15:40:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=21912 

self.closeSec=1697182799, self.tradeDate='20231013', self.openTime='153000', self.closeTime='153959', self.symbol='BTCUSDT', self.open='26872.9', self.close='26879.9'
127.0.0.1 - - [13/Oct/2023 15:50:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=21913 

self.closeSec=1697183399, self.tradeDate='20231013', self.openTime='154000', self.closeTime='154959', self.symbol='BTCUSDT', self.open='26881.6', self.close='26844.4'

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=21914 

self.closeSec=1697183999, self.tradeDate='20231013', self.openTime='155000', self.closeTime='155959', self.symbol='BTCUSDT', self.open='26844.3', self.close='26861.1'
127.0.0.1 - - [13/Oct/2023 16:00:01] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [13/Oct/2023 16:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=21915 

self.closeSec=1697184599, self.tradeDate='20231013', self.openTime='160000', self.closeTime='160959', self.symbol='BTCUSDT', self.open='26857.9', self.close='26870'

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=21916 

self.closeSec=1697185199, self.tradeDate='20231013', self.openTime='161000', self.closeTime='161959', self.symbol='BTCUSDT', self.open='26870.1', self.close='26839.3'
127.0.0.1 - - [13/Oct/2023 16:20:05] "POST / HTTP/1.1" 200 -


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


--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=21914 

self.closeSec=1697182199, self.tradeDate='20231013', self.openTime='152000', self.closeTime='152959', self.symbol='BTCUSDT', self.open='26881.7', self.close='26873'
127.0.0.1 - - [13/Oct/2023 15:30:01] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [13/Oct/2023 15:40:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=21915 

self.closeSec=1697182799, self.tradeDate='20231013', self.openTime='153000', self.closeTime='153959', self.symbol='BTCUSDT', self.open='26872.9', self.close='26879.9'

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=21916 

self.closeSec=1697183399, self.tradeDate='20231013', self.openTime='154000', self.closeTime='154959', self.symbol='BTCUSDT', self.open='26881.6', self.close='26844.4'
127.0.0.1 - - [13/Oct/2023 15:50:01] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [13/Oct/2023 16:00:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=21917 

self.closeSec=1697183999, self.tradeDate='20231013', self.openTime='155000', self.closeTime='155959', self.symbol='BTCUSDT', self.open='26844.3', self.close='26861.1'
127.0.0.1 - - [13/Oct/2023 16:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=21918 

self.closeSec=1697184599, self.tradeDate='20231013', self.openTime='160000', self.closeTime='160959', self.symbol='BTCUSDT', self.open='26857.9', self.close='26870'

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=21919 

self.closeSec=1697185199, self.tradeDate='20231013', self.openTime='161000', self.closeTime='161959', self.symbol='BTCUSDT', self.open='26870.1', self.close='26839.3'
127.0.0.1 - - [13/Oct/2023 16:20:05] "POST / HTTP/1.1" 200 -


## /root/FIL/strategy/similarity/log.txt ----- -----


--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=21914 

self.closeSec=1697182199, self.tradeDate='20231013', self.openTime='152000', self.closeTime='152959', self.symbol='BTCUSDT', self.open='26881.7', self.close='26873'
127.0.0.1 - - [13/Oct/2023 15:30:01] "POST / HTTP/1.1" 200 -

--handleKline--: 127.0.0.1 - - [13/Oct/2023 15:40:01] "POST / HTTP/1.1" 200 -
 self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=21915 

self.closeSec=1697182799, self.tradeDate='20231013', self.openTime='153000', self.closeTime='153959', self.symbol='BTCUSDT', self.open='26872.9', self.close='26879.9'
127.0.0.1 - - [13/Oct/2023 15:50:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=21916 

self.closeSec=1697183399, self.tradeDate='20231013', self.openTime='154000', self.closeTime='154959', self.symbol='BTCUSDT', self.open='26881.6', self.close='26844.4'
127.0.0.1 - - [13/Oct/2023 16:00:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=21917 

self.closeSec=1697183999, self.tradeDate='20231013', self.openTime='155000', self.closeTime='155959', self.symbol='BTCUSDT', self.open='26844.3', self.close='26861.1'

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=21918 

self.closeSec=1697184599, self.tradeDate='20231013', self.openTime='160000', self.closeTime='160959', self.symbol='BTCUSDT', self.open='26857.9', self.close='26870'
127.0.0.1 - - [13/Oct/2023 16:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=21919 

self.closeSec=1697185199, self.tradeDate='20231013', self.openTime='161000', self.closeTime='161959', self.symbol='BTCUSDT', self.open='26870.1', self.close='26839.3'
127.0.0.1 - - [13/Oct/2023 16:20:05] "POST / HTTP/1.1" 200 -


## /root/FIL/strategy/sr_min/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=1, self.total=996015.990996, self.flagDict['side']='buy', self.tradeCount=1, self.count=43828
self.closeSec=1697185199, self.tradeDate='20231013', self.openTime='161500', self.closeTime='161959', self.symbol='BTCUSDT', self.open=26862.5, self.close=26839.3, self.high=26876.7, self.low=26839.2, self.vol=770.378, self.amt=20686327.5816 
127.0.0.1 - - [13/Oct/2023 16:20:03] "POST / HTTP/1.1" 200 -
2023-10-13 16:20:07,275:INFO:sr_min:main.py:172:handleKline:2219263: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5951  20231013   155500    155959  ...         0.0        0.0       0
5952  20231013   160000    160459  ...         0.0        0.0       0
5953  20231013   160500    160959  ...         0.0        0.0       0
5954  20231013   161000    161459  ...         0.0        0.0       0
5955  20231013   161500    161959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-10-13 16:20:07,278:INFO:sr_min:main.py:175:handleKline:2219263: self.closeSec=1697185199, self.tradeDate='20231013', self.openTime='161500', self.closeTime='161959',self.symbol='BTCUSDT',self.open=26862.5, self.close=26839.3, self.high=26876.7, self.low=26839.2, self.vol=770.378, self.amt=20686327.5816, ukdf['pct'].iloc[-1]=-0.000923 , ukdf['amount'].iloc[-1]=20686327.5816, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5955, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '37.141', 'enterprice': '26844', 'countrevence': '0', 'unrealprofit': '-103.9948', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '26841.2', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=1
--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=1, self.total=996015.990996, self.flagDict['side']='buy', self.tradeCount=1, self.count=43829
self.closeSec=1697185499, self.tradeDate='20231013', self.openTime='162000', self.closeTime='162459', self.symbol='BTCUSDT', self.open=26840.0, self.close=26850.6, self.high=26858.0, self.low=26832.7, self.vol=589.151, self.amt=15813831.0769 
127.0.0.1 - - [13/Oct/2023 16:25:01] "POST / HTTP/1.1" 200 -
2023-10-13 16:25:03,147:INFO:sr_min:main.py:172:handleKline:2219263: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5952  20231013   160000    160459  ...         0.0        0.0       0
5953  20231013   160500    160959  ...         0.0        0.0       0
5954  20231013   161000    161459  ...         0.0        0.0       0
5955  20231013   161500    161959  ...         0.0        0.0       0
5956  20231013   162000    162459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-10-13 16:25:03,166:INFO:sr_min:main.py:175:handleKline:2219263: self.closeSec=1697185499, self.tradeDate='20231013', self.openTime='162000', self.closeTime='162459',self.symbol='BTCUSDT',self.open=26840.0, self.close=26850.6, self.high=26858.0, self.low=26832.7, self.vol=589.151, self.amt=15813831.0769, ukdf['pct'].iloc[-1]=0.000421 , ukdf['amount'].iloc[-1]=15813831.0769, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5956, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '37.141', 'enterprice': '26844', 'countrevence': '0', 'unrealprofit': '323.05602327687', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '26852.69809707', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=1


## /root/FIL/strategy/s_rsrs/log.txt ----- -----

721  20231013   040000    075959  1697155199  ...    721  0.822618  0.766006     1.0
722  20231013   080000    115959  1697169599  ...    722  0.843884  0.807063     1.0

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '47.147', 'enterprice': '26826.9', 'countrevence': '0', 'unrealprofit': '-2560.0821', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '26772.6', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=1, self.sign=1
127.0.0.1 - - [13/Oct/2023 16:00:01] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='s_rsrs', self.symbol='BTCUSDT', interval='4h', intervalSec=14400, wid=25, thd=0.6, self.sign=1, self.total=1263543.0464457, self.flagDict['side']='buy', self.tradeCount=33, self.count=913
self.closeSec=1697183999, self.tradeDate='20231013', self.openTime='120000', self.closeTime='155959', self.symbol='BTCUSDT', self.open=26769.5, self.close=26861.1, self.high=26929.0, self.low=26765.3, self.vol=22522.718, self.amt=604587558.5649 
2023-10-13 16:00:01,596:INFO:s_rsrs:main.py:141:handleKline:2218689: self.closeSec=1697183999, self.tradeDate='20231013', self.openTime='120000', self.closeTime='155959',self.symbol='BTCUSDT',self.open=26769.5, self.close=26861.1, self.high=26929.0, self.low=26765.3, self.vol=22522.718, self.amt=604587558.5649 
2023-10-13 16:00:01,608:INFO:s_rsrs:main.py:142:handleKline:2218689: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime  ...        vol           amt       pct
719  20231012   200000    235959  ...  52334.340  1.398958e+09 -0.006128
720  20231013   000000    035959  ...  58269.011  1.553183e+09  0.001399
721  20231013   040000    075959  ...  15277.367  4.083113e+08  0.001640
722  20231013   080000    115959  ...  24000.376  6.432579e+08  0.000950
723  20231013   120000    155959  ...  22522.718  6.045876e+08  0.003422

[5 rows x 11 columns]
2023-10-13 16:00:02,318:INFO:s_rsrs:main.py:151:handleKline:2218689: df_s.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec  ...  index      beta    zscore  signal
719  20231012   200000    235959  1697126399  ...    719  0.783933  0.693354     1.0
720  20231013   000000    035959  1697140799  ...    720  0.777967  0.659623     1.0
721  20231013   040000    075959  1697155199  ...    721  0.822618  0.766006     1.0
722  20231013   080000    115959  1697169599  ...    722  0.843884  0.807063     1.0
723  20231013   120000    155959  1697183999  ...    723  0.855994  0.822502     1.0

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '47.147', 'enterprice': '26826.9', 'countrevence': '0', 'unrealprofit': '1585.82578444483', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '26860.53577289', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=1, self.sign=1


