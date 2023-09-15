# 20230915 16:26:02

## /root/FIL/strategy/amihud/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=373746.4768026, self.flagDict['side']='sell', self.tradeCount=2, self.count=35764
self.closeSec=1694765999, self.tradeDate='20230915', self.openTime='161500', self.closeTime='161959', self.symbol='BTCUSDT', self.open=26532.0, self.close=26530.0, self.high=26535.9, self.low=26530.0, self.vol=330.996, self.amt=8781992.0527 
127.0.0.1 - - [15/Sep/2023 16:20:02] "POST / HTTP/1.1" 200 -
2023-09-15 16:20:06,756:INFO:amihud:main.py:172:handleKline:2219019: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5951  20230915   155500    155959  ...         0.0        0.0       0
5952  20230915   160000    160459  ...         0.0        0.0       0
5953  20230915   160500    160959  ...         0.0        0.0       0
5954  20230915   161000    161459  ...         0.0        0.0       0
5955  20230915   161500    161959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-09-15 16:20:06,773:INFO:amihud:main.py:175:handleKline:2219019: self.closeSec=1694765999, self.tradeDate='20230915', self.openTime='161500', self.closeTime='161959',self.symbol='BTCUSDT',self.open=26532.0, self.close=26530.0, self.high=26535.9, self.low=26530.0, self.vol=330.996, self.amt=8781992.0527, ukdf['pct'].iloc[-1]=-7.2e-05 , ukdf['amount'].iloc[-1]=8781992.0527, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5955, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '13.926', 'enterprice': '26864.9', 'countrevence': '0', 'unrealprofit': '4695.05923321908', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '26527.75658242', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1
127.0.0.1 - - [15/Sep/2023 16:25:00] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=373746.4768026, self.flagDict['side']='sell', self.tradeCount=2, self.count=35765
self.closeSec=1694766299, self.tradeDate='20230915', self.openTime='162000', self.closeTime='162459', self.symbol='BTCUSDT', self.open=26529.9, self.close=26555.0, self.high=26555.0, self.low=26523.2, self.vol=517.681, self.amt=13739189.9694 
2023-09-15 16:25:00,783:INFO:amihud:main.py:172:handleKline:2219019: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5952  20230915   160000    160459  ...         0.0        0.0       0
5953  20230915   160500    160959  ...         0.0        0.0       0
5954  20230915   161000    161459  ...         0.0        0.0       0
5955  20230915   161500    161959  ...         0.0        0.0       0
5956  20230915   162000    162459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-09-15 16:25:00,786:INFO:amihud:main.py:175:handleKline:2219019: self.closeSec=1694766299, self.tradeDate='20230915', self.openTime='162000', self.closeTime='162459',self.symbol='BTCUSDT',self.open=26529.9, self.close=26555.0, self.high=26555.0, self.low=26523.2, self.vol=517.681, self.amt=13739189.9694, ukdf['pct'].iloc[-1]=0.000942 , ukdf['amount'].iloc[-1]=13739189.9694, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5956, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '13.926', 'enterprice': '26864.9', 'countrevence': '0', 'unrealprofit': '4315.6674', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '26555', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1


## /root/FIL/strategy/factorcheck/log.txt ----- -----


--handleKline--: 127.0.0.1 - - [15/Sep/2023 16:00:00] "POST / HTTP/1.1" 200 -
 version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.714181719035411, self.count=35762 

self.closeSec=1694764799, self.tradeDate='20230915', self.openTime='155500', self.closeTime='155959', self.symbol='BTCUSDT', self.open=26549.6, self.close=26554.4, self.high=26554.5, self.low=26544.4 

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.714181719035411, self.count=35763 

self.closeSec=1694765099, self.tradeDate='20230915', self.openTime='160000', self.closeTime='160459', self.symbol='BTCUSDT', self.open=26554.4, self.close=26541.8, self.high=26554.5, self.low=26538.5 
127.0.0.1 - - [15/Sep/2023 16:05:00] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.714181719035411, self.count=35764 

self.closeSec=1694765399, self.tradeDate='20230915', self.openTime='160500', self.closeTime='160959', self.symbol='BTCUSDT', self.open=26541.8, self.close=26550.8, self.high=26552.1, self.low=26530.7 
127.0.0.1 - - [15/Sep/2023 16:10:00] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.714181719035411, self.count=35765 

self.closeSec=1694765699, self.tradeDate='20230915', self.openTime='161000', self.closeTime='161459', self.symbol='BTCUSDT', self.open=26550.8, self.close=26531.9, self.high=26552.9, self.low=26530.7 
127.0.0.1 - - [15/Sep/2023 16:15:00] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.714181719035411, self.count=35766 

self.closeSec=1694765999, self.tradeDate='20230915', self.openTime='161500', self.closeTime='161959', self.symbol='BTCUSDT', self.open=26532.0, self.close=26530.0, self.high=26535.9, self.low=26530.0 
127.0.0.1 - - [15/Sep/2023 16:20:02] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [15/Sep/2023 16:25:00] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.714181719035411, self.count=35767 

self.closeSec=1694766299, self.tradeDate='20230915', self.openTime='162000', self.closeTime='162459', self.symbol='BTCUSDT', self.open=26529.9, self.close=26555.0, self.high=26555.0, self.low=26523.2 


## /root/FIL/strategy/logic/log.txt ----- -----

2023-09-15 16:00:18,301:DEBUG:logic:main.py:463:getModel:2218526: df_s.iloc[-5:,:] :
          date closeTime     open  ...    alpha58   alpha67   alpha72
5785  20230915    132959  26626.0  ...  48.333333  0.551536  0.422762
5786  20230915    135959  26595.9  ...  48.333333  0.547374  0.427617
5787  20230915    142959  26577.3  ...  48.333333  0.548601  0.431732
5788  20230915    145959  26584.0  ...  48.333333  0.543545  0.440381
5789  20230915    152959  26561.8  ...  48.333333  0.543777  0.449181

[5 rows x 33 columns]
0.5535055350553506
acc is : 0.5535055350553506
2023-09-15 16:00:18,385:INFO:logic:main.py:468:getModel:2218526: df_pred.iloc[-5:,:] :
     pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
537     1  0.491034  0.508966       0  ...  0.945285   1.0    0.0  1.026139
538     1  0.494367  0.505633       1  ...  0.945520   1.0    0.0  1.026394
539     1  0.497874  0.502126       0  ...  0.944731   1.0    0.0  1.025536
540     1  0.485211  0.514789       1  ...  0.944773   1.0    0.0  1.025583
541     1  0.494946  0.505054       0  ...  0.944471   1.0    0.0  1.025255

[5 rows x 10 columns]
2023-09-15 16:00:18,398:INFO:logic:main.py:478:getModel:2218526: df_panel.iloc[-5:,:] :
    pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
45     1  0.490649  0.509351       0  ...  0.945285   1.0    0.0  1.024627
46     1  0.493744  0.506256       1  ...  0.945520   1.0    0.0  1.024617
47     1  0.497258  0.502742       0  ...  0.944731   1.0    0.0  1.023095
48     1  0.484895  0.515105       1  ...  0.944773   1.0    0.0  1.024487
49     1  0.494946  0.505054       0  ...  0.944471   1.0    0.0  1.025255

[5 rows x 10 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '26.865', 'enterprice': '26592', 'countrevence': '0', 'unrealprofit': '-1044.35424150615', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '26553.12584249', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}


## /root/FIL/strategy/modifiedmom/log.txt ----- -----


--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=17879 

self.closeSec=1694762999, self.tradeDate='20230915', self.openTime='152000', self.closeTime='152959', self.symbol='BTCUSDT', self.open='26540.1', self.close='26562.9'
127.0.0.1 - - [15/Sep/2023 15:30:01] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [15/Sep/2023 15:40:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=17880 

self.closeSec=1694763599, self.tradeDate='20230915', self.openTime='153000', self.closeTime='153959', self.symbol='BTCUSDT', self.open='26563', self.close='26569.1'
127.0.0.1 - - [15/Sep/2023 15:50:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=17881 

self.closeSec=1694764199, self.tradeDate='20230915', self.openTime='154000', self.closeTime='154959', self.symbol='BTCUSDT', self.open='26569.1', self.close='26572.8'
127.0.0.1 - - [15/Sep/2023 16:00:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=17882 

self.closeSec=1694764799, self.tradeDate='20230915', self.openTime='155000', self.closeTime='155959', self.symbol='BTCUSDT', self.open='26572.8', self.close='26554.4'

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=17883 

self.closeSec=1694765399, self.tradeDate='20230915', self.openTime='160000', self.closeTime='160959', self.symbol='BTCUSDT', self.open='26554.4', self.close='26550.8'
127.0.0.1 - - [15/Sep/2023 16:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=17884 

self.closeSec=1694765999, self.tradeDate='20230915', self.openTime='161000', self.closeTime='161959', self.symbol='BTCUSDT', self.open='26550.8', self.close='26530'
127.0.0.1 - - [15/Sep/2023 16:20:05] "POST / HTTP/1.1" 200 -


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


--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=17882 

self.closeSec=1694762999, self.tradeDate='20230915', self.openTime='152000', self.closeTime='152959', self.symbol='BTCUSDT', self.open='26540.1', self.close='26562.9'
127.0.0.1 - - [15/Sep/2023 15:30:01] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [15/Sep/2023 15:40:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=17883 

self.closeSec=1694763599, self.tradeDate='20230915', self.openTime='153000', self.closeTime='153959', self.symbol='BTCUSDT', self.open='26563', self.close='26569.1'
127.0.0.1 - - [15/Sep/2023 15:50:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=17884 

self.closeSec=1694764199, self.tradeDate='20230915', self.openTime='154000', self.closeTime='154959', self.symbol='BTCUSDT', self.open='26569.1', self.close='26572.8'

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=17885 

self.closeSec=1694764799, self.tradeDate='20230915', self.openTime='155000', self.closeTime='155959', self.symbol='BTCUSDT', self.open='26572.8', self.close='26554.4'
127.0.0.1 - - [15/Sep/2023 16:00:01] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [15/Sep/2023 16:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=17886 

self.closeSec=1694765399, self.tradeDate='20230915', self.openTime='160000', self.closeTime='160959', self.symbol='BTCUSDT', self.open='26554.4', self.close='26550.8'

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=17887 

self.closeSec=1694765999, self.tradeDate='20230915', self.openTime='161000', self.closeTime='161959', self.symbol='BTCUSDT', self.open='26550.8', self.close='26530'
127.0.0.1 - - [15/Sep/2023 16:20:05] "POST / HTTP/1.1" 200 -


## /root/FIL/strategy/similarity/log.txt ----- -----


--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=17882 

self.closeSec=1694762999, self.tradeDate='20230915', self.openTime='152000', self.closeTime='152959', self.symbol='BTCUSDT', self.open='26540.1', self.close='26562.9'
127.0.0.1 - - [15/Sep/2023 15:30:01] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [15/Sep/2023 15:40:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=17883 

self.closeSec=1694763599, self.tradeDate='20230915', self.openTime='153000', self.closeTime='153959', self.symbol='BTCUSDT', self.open='26563', self.close='26569.1'
127.0.0.1 - - [15/Sep/2023 15:50:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=17884 

self.closeSec=1694764199, self.tradeDate='20230915', self.openTime='154000', self.closeTime='154959', self.symbol='BTCUSDT', self.open='26569.1', self.close='26572.8'

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=17885 

self.closeSec=1694764799, self.tradeDate='20230915', self.openTime='155000', self.closeTime='155959', self.symbol='BTCUSDT', self.open='26572.8', self.close='26554.4'
127.0.0.1 - - [15/Sep/2023 16:00:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=17886 

self.closeSec=1694765399, self.tradeDate='20230915', self.openTime='160000', self.closeTime='160959', self.symbol='BTCUSDT', self.open='26554.4', self.close='26550.8'
127.0.0.1 - - [15/Sep/2023 16:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=17887 

self.closeSec=1694765999, self.tradeDate='20230915', self.openTime='161000', self.closeTime='161959', self.symbol='BTCUSDT', self.open='26550.8', self.close='26530'
127.0.0.1 - - [15/Sep/2023 16:20:05] "POST / HTTP/1.1" 200 -


## /root/FIL/strategy/sr_min/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=1, self.total=996015.990996, self.flagDict['side']='buy', self.tradeCount=1, self.count=35764
self.closeSec=1694765999, self.tradeDate='20230915', self.openTime='161500', self.closeTime='161959', self.symbol='BTCUSDT', self.open=26532.0, self.close=26530.0, self.high=26535.9, self.low=26530.0, self.vol=330.996, self.amt=8781992.0527 
127.0.0.1 - - [15/Sep/2023 16:20:02] "POST / HTTP/1.1" 200 -
2023-09-15 16:20:06,755:INFO:sr_min:main.py:172:handleKline:2219263: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5951  20230915   155500    155959  ...         0.0        0.0       0
5952  20230915   160000    160459  ...         0.0        0.0       0
5953  20230915   160500    160959  ...         0.0        0.0       0
5954  20230915   161000    161459  ...         0.0        0.0       0
5955  20230915   161500    161959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-09-15 16:20:06,768:INFO:sr_min:main.py:175:handleKline:2219263: self.closeSec=1694765999, self.tradeDate='20230915', self.openTime='161500', self.closeTime='161959',self.symbol='BTCUSDT',self.open=26532.0, self.close=26530.0, self.high=26535.9, self.low=26530.0, self.vol=330.996, self.amt=8781992.0527, ukdf['pct'].iloc[-1]=-7.2e-05 , ukdf['amount'].iloc[-1]=8781992.0527, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5955, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '37.141', 'enterprice': '26844', 'countrevence': '0', 'unrealprofit': '-11745.59677233878', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '26527.75658242', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=1
127.0.0.1 - - [15/Sep/2023 16:25:00] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=1, self.total=996015.990996, self.flagDict['side']='buy', self.tradeCount=1, self.count=35765
self.closeSec=1694766299, self.tradeDate='20230915', self.openTime='162000', self.closeTime='162459', self.symbol='BTCUSDT', self.open=26529.9, self.close=26555.0, self.high=26555.0, self.low=26523.2, self.vol=517.681, self.amt=13739189.9694 
2023-09-15 16:25:00,805:INFO:sr_min:main.py:172:handleKline:2219263: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5952  20230915   160000    160459  ...         0.0        0.0       0
5953  20230915   160500    160959  ...         0.0        0.0       0
5954  20230915   161000    161459  ...         0.0        0.0       0
5955  20230915   161500    161959  ...         0.0        0.0       0
5956  20230915   162000    162459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-09-15 16:25:00,805:INFO:sr_min:main.py:175:handleKline:2219263: self.closeSec=1694766299, self.tradeDate='20230915', self.openTime='162000', self.closeTime='162459',self.symbol='BTCUSDT',self.open=26529.9, self.close=26555.0, self.high=26555.0, self.low=26523.2, self.vol=517.681, self.amt=13739189.9694, ukdf['pct'].iloc[-1]=0.000942 , ukdf['amount'].iloc[-1]=13739189.9694, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5956, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '37.141', 'enterprice': '26844', 'countrevence': '0', 'unrealprofit': '-10733.749', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '26555', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=1


## /root/FIL/strategy/s_rsrs/log.txt ----- -----

721  20230915   040000    075959  1694735999  ...    721  0.598445  0.837164     1.0
722  20230915   080000    115959  1694750399  ...    722  0.586429  0.821026     1.0

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '53.725', 'enterprice': '26678.4', 'countrevence': '0', 'unrealprofit': '-4066.9825', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '26602.7', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=1, self.sign=1
--handleKline--:  version='2.0.0', self.name='s_rsrs', self.symbol='BTCUSDT', interval='4h', intervalSec=14400, wid=25, thd=0.6, self.sign=1, self.total=1431863.74296, self.flagDict['side']='buy', self.tradeCount=23, self.count=745
self.closeSec=1694764799, self.tradeDate='20230915', self.openTime='120000', self.closeTime='155959', self.symbol='BTCUSDT', self.open=26602.7, self.close=26554.4, self.high=26647.0, self.low=26535.0, self.vol=20708.984, self.amt=550623128.3782 
127.0.0.1 - - [15/Sep/2023 16:00:01] "POST / HTTP/1.1" 200 -
2023-09-15 16:00:01,515:INFO:s_rsrs:main.py:141:handleKline:2218689: self.closeSec=1694764799, self.tradeDate='20230915', self.openTime='120000', self.closeTime='155959',self.symbol='BTCUSDT',self.open=26602.7, self.close=26554.4, self.high=26647.0, self.low=26535.0, self.vol=20708.984, self.amt=550623128.3782 
2023-09-15 16:00:01,528:INFO:s_rsrs:main.py:142:handleKline:2218689: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime  ...         vol           amt       pct
719  20230914   200000    235959  ...  143119.371  3.803643e+09  0.009402
720  20230915   000000    035959  ...   62676.122  1.670001e+09 -0.000675
721  20230915   040000    075959  ...   30652.131  8.142160e+08 -0.005690
722  20230915   080000    115959  ...   27708.163  7.349778e+08  0.003485
723  20230915   120000    155959  ...   20708.984  5.506231e+08 -0.001816

[5 rows x 11 columns]
2023-09-15 16:00:02,263:INFO:s_rsrs:main.py:151:handleKline:2218689: df_s.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec  ...  index      beta    zscore  signal
719  20230914   200000    235959  1694707199  ...    719  0.552260  0.623661     1.0
720  20230915   000000    035959  1694721599  ...    720  0.602464  0.822162     1.0
721  20230915   040000    075959  1694735999  ...    721  0.598445  0.837164     1.0
722  20230915   080000    115959  1694750399  ...    722  0.586429  0.821026     1.0
723  20230915   120000    155959  1694764799  ...    723  0.556396  0.737129     1.0

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '53.725', 'enterprice': '26678.4', 'countrevence': '0', 'unrealprofit': '-6661.9', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '26554.4', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=1, self.sign=1


