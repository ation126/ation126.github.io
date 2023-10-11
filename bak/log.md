# 20231011 16:26:01

## /root/FIL/strategy/amihud/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=373746.4768026, self.flagDict['side']='sell', self.tradeCount=2, self.count=43252
self.closeSec=1697012399, self.tradeDate='20231011', self.openTime='161500', self.closeTime='161959', self.symbol='BTCUSDT', self.open=27048.3, self.close=27054.4, self.high=27060.0, self.low=27040.9, self.vol=565.824, self.amt=15306882.5995 
127.0.0.1 - - [11/Oct/2023 16:20:05] "POST / HTTP/1.1" 200 -
2023-10-11 16:20:08,540:INFO:amihud:main.py:172:handleKline:2219019: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5951  20231011   155500    155959  ...         0.0        0.0       0
5952  20231011   160000    160459  ...         0.0        0.0       0
5953  20231011   160500    160959  ...         0.0        0.0       0
5954  20231011   161000    161459  ...         0.0        0.0       0
5955  20231011   161500    161959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-10-11 16:20:08,543:INFO:amihud:main.py:175:handleKline:2219019: self.closeSec=1697012399, self.tradeDate='20231011', self.openTime='161500', self.closeTime='161959',self.symbol='BTCUSDT',self.open=27048.3, self.close=27054.4, self.high=27060.0, self.low=27040.9, self.vol=565.824, self.amt=15306882.5995, ukdf['pct'].iloc[-1]=0.000226 , ukdf['amount'].iloc[-1]=15306882.5995, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5955, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '13.926', 'enterprice': '26864.9', 'countrevence': '0', 'unrealprofit': '-2638.977', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '27054.4', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1
--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=373746.4768026, self.flagDict['side']='sell', self.tradeCount=2, self.count=43253
self.closeSec=1697012699, self.tradeDate='20231011', self.openTime='162000', self.closeTime='162459', self.symbol='BTCUSDT', self.open=27054.3, self.close=27036.6, self.high=27055.2, self.low=27036.5, self.vol=394.181, self.amt=10661907.4616 
127.0.0.1 - - [11/Oct/2023 16:25:01] "POST / HTTP/1.1" 200 -
2023-10-11 16:25:03,202:INFO:amihud:main.py:172:handleKline:2219019: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5952  20231011   160000    160459  ...         0.0        0.0       0
5953  20231011   160500    160959  ...         0.0        0.0       0
5954  20231011   161000    161459  ...         0.0        0.0       0
5955  20231011   161500    161959  ...         0.0        0.0       0
5956  20231011   162000    162459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-10-11 16:25:03,220:INFO:amihud:main.py:175:handleKline:2219019: self.closeSec=1697012699, self.tradeDate='20231011', self.openTime='162000', self.closeTime='162459',self.symbol='BTCUSDT',self.open=27054.3, self.close=27036.6, self.high=27055.2, self.low=27036.5, self.vol=394.181, self.amt=10661907.4616, ukdf['pct'].iloc[-1]=-0.000658 , ukdf['amount'].iloc[-1]=10661907.4616, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5956, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '13.926', 'enterprice': '26864.9', 'countrevence': '0', 'unrealprofit': '-2408.01209651574', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '27037.81484249', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1


## /root/FIL/strategy/factorcheck/log.txt ----- -----

127.0.0.1 - - [11/Oct/2023 16:00:00] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.714181719035411, self.count=43250 

self.closeSec=1697011199, self.tradeDate='20231011', self.openTime='155500', self.closeTime='155959', self.symbol='BTCUSDT', self.open=27021.6, self.close=27012.8, self.high=27023.6, self.low=27005.0 

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.714181719035411, self.count=43251 

self.closeSec=1697011499, self.tradeDate='20231011', self.openTime='160000', self.closeTime='160459', self.symbol='BTCUSDT', self.open=27012.7, self.close=27036.9, self.high=27036.9, self.low=27002.9 
127.0.0.1 - - [11/Oct/2023 16:05:00] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [11/Oct/2023 16:10:00] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.714181719035411, self.count=43252 

self.closeSec=1697011799, self.tradeDate='20231011', self.openTime='160500', self.closeTime='160959', self.symbol='BTCUSDT', self.open=27036.9, self.close=27036.4, self.high=27044.9, self.low=27016.4 

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.714181719035411, self.count=43253 

self.closeSec=1697012099, self.tradeDate='20231011', self.openTime='161000', self.closeTime='161459', self.symbol='BTCUSDT', self.open=27036.4, self.close=27048.3, self.high=27053.9, self.low=27030.5 
127.0.0.1 - - [11/Oct/2023 16:15:00] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.714181719035411, self.count=43254 

self.closeSec=1697012399, self.tradeDate='20231011', self.openTime='161500', self.closeTime='161959', self.symbol='BTCUSDT', self.open=27048.3, self.close=27054.4, self.high=27060.0, self.low=27040.9 
127.0.0.1 - - [11/Oct/2023 16:20:04] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.714181719035411, self.count=43255 

self.closeSec=1697012699, self.tradeDate='20231011', self.openTime='162000', self.closeTime='162459', self.symbol='BTCUSDT', self.open=27054.3, self.close=27036.6, self.high=27055.2, self.low=27036.5 
127.0.0.1 - - [11/Oct/2023 16:25:01] "POST / HTTP/1.1" 200 -


## /root/FIL/strategy/logic/log.txt ----- -----

2023-10-11 16:00:18,532:DEBUG:logic:main.py:463:getModel:2218526: df_s.iloc[-5:,:] :
          date closeTime     open  ...    alpha58   alpha67   alpha72
5785  20231011    132959  27111.1  ...  49.166667  0.396895  0.738618
5786  20231011    135959  27097.4  ...  49.166667  0.398512  0.741893
5787  20231011    142959  27102.8  ...  49.166667  0.390901  0.748481
5788  20231011    145959  27065.1  ...  49.166667  0.389793  0.754532
5789  20231011    152959  27059.7  ...  48.750000  0.386339  0.761868

[5 rows x 33 columns]
0.5627306273062731
acc is : 0.5627306273062731
2023-10-11 16:00:18,615:INFO:logic:main.py:468:getModel:2218526: df_pred.iloc[-5:,:] :
     pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
537     1  0.488291  0.511709       1  ...  1.020111  -1.0    0.0  1.006716
538     1  0.495134  0.504866       0  ...  1.021529  -1.0    0.0  1.005315
539     1  0.485628  0.514372       0  ...  1.021737  -1.0    0.0  1.005111
540     1  0.489504  0.510496       0  ...  1.022379  -1.0    0.0  1.004480
541     1  0.484815  0.515185       0  ...  1.023506  -1.0    0.0  1.003373

[5 rows x 10 columns]
2023-10-11 16:00:18,629:INFO:logic:main.py:478:getModel:2218526: df_panel.iloc[-5:,:] :
    pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
45     1  0.488860  0.511140       1  ...  1.020111  -1.0    0.0  1.008476
46     1  0.495677  0.504323       0  ...  1.021529  -1.0    0.0  1.006890
47     1  0.485653  0.514347       0  ...  1.021737  -1.0    0.0  1.006273
48     1  0.489639  0.510361       0  ...  1.022379  -1.0    0.0  1.006019
49     1  0.484815  0.515185       0  ...  1.023506  -1.0    0.0  1.003373

[5 rows x 10 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '23.618', 'enterprice': '27520.8', 'countrevence': '0', 'unrealprofit': '12174.57649020592', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '27005.32127656', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}


## /root/FIL/strategy/modifiedmom/log.txt ----- -----

127.0.0.1 - - [11/Oct/2023 15:30:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=21623 

self.closeSec=1697009399, self.tradeDate='20231011', self.openTime='152000', self.closeTime='152959', self.symbol='BTCUSDT', self.open='27046.6', self.close='27042.6'

--handleKline--: 127.0.0.1 - - [11/Oct/2023 15:40:01] "POST / HTTP/1.1" 200 -
 self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=21624 

self.closeSec=1697009999, self.tradeDate='20231011', self.openTime='153000', self.closeTime='153959', self.symbol='BTCUSDT', self.open='27042.7', self.close='27030.9'

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=21625 

self.closeSec=1697010599, self.tradeDate='20231011', self.openTime='154000', self.closeTime='154959', self.symbol='BTCUSDT', self.open='27030.9', self.close='27054.6'
127.0.0.1 - - [11/Oct/2023 15:50:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=21626 

self.closeSec=1697011199, self.tradeDate='20231011', self.openTime='155000', self.closeTime='155959', self.symbol='BTCUSDT', self.open='27054.6', self.close='27012.8'
127.0.0.1 - - [11/Oct/2023 16:00:01] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [11/Oct/2023 16:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=21627 

self.closeSec=1697011799, self.tradeDate='20231011', self.openTime='160000', self.closeTime='160959', self.symbol='BTCUSDT', self.open='27012.7', self.close='27036.4'

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=21628 

self.closeSec=1697012399, self.tradeDate='20231011', self.openTime='161000', self.closeTime='161959', self.symbol='BTCUSDT', self.open='27036.4', self.close='27054.4'
127.0.0.1 - - [11/Oct/2023 16:20:06] "POST / HTTP/1.1" 200 -


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


--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=21626 

self.closeSec=1697009399, self.tradeDate='20231011', self.openTime='152000', self.closeTime='152959', self.symbol='BTCUSDT', self.open='27046.6', self.close='27042.6'
127.0.0.1 - - [11/Oct/2023 15:30:01] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [11/Oct/2023 15:40:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=21627 

self.closeSec=1697009999, self.tradeDate='20231011', self.openTime='153000', self.closeTime='153959', self.symbol='BTCUSDT', self.open='27042.7', self.close='27030.9'

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=21628 

self.closeSec=1697010599, self.tradeDate='20231011', self.openTime='154000', self.closeTime='154959', self.symbol='BTCUSDT', self.open='27030.9', self.close='27054.6'
127.0.0.1 - - [11/Oct/2023 15:50:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=21629 

self.closeSec=1697011199, self.tradeDate='20231011', self.openTime='155000', self.closeTime='155959', self.symbol='BTCUSDT', self.open='27054.6', self.close='27012.8'
127.0.0.1 - - [11/Oct/2023 16:00:01] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [11/Oct/2023 16:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=21630 

self.closeSec=1697011799, self.tradeDate='20231011', self.openTime='160000', self.closeTime='160959', self.symbol='BTCUSDT', self.open='27012.7', self.close='27036.4'

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=21631 

self.closeSec=1697012399, self.tradeDate='20231011', self.openTime='161000', self.closeTime='161959', self.symbol='BTCUSDT', self.open='27036.4', self.close='27054.4'
127.0.0.1 - - [11/Oct/2023 16:20:06] "POST / HTTP/1.1" 200 -


## /root/FIL/strategy/similarity/log.txt ----- -----

127.0.0.1 - - [11/Oct/2023 15:30:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=21626 

self.closeSec=1697009399, self.tradeDate='20231011', self.openTime='152000', self.closeTime='152959', self.symbol='BTCUSDT', self.open='27046.6', self.close='27042.6'

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=21627 

self.closeSec=1697009999, self.tradeDate='20231011', self.openTime='153000', self.closeTime='153959', self.symbol='BTCUSDT', self.open='27042.7', self.close='27030.9'
127.0.0.1 - - [11/Oct/2023 15:40:01] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [11/Oct/2023 15:50:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=21628 

self.closeSec=1697010599, self.tradeDate='20231011', self.openTime='154000', self.closeTime='154959', self.symbol='BTCUSDT', self.open='27030.9', self.close='27054.6'

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=21629 

self.closeSec=1697011199, self.tradeDate='20231011', self.openTime='155000', self.closeTime='155959', self.symbol='BTCUSDT', self.open='27054.6', self.close='27012.8'
127.0.0.1 - - [11/Oct/2023 16:00:01] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [11/Oct/2023 16:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=21630 

self.closeSec=1697011799, self.tradeDate='20231011', self.openTime='160000', self.closeTime='160959', self.symbol='BTCUSDT', self.open='27012.7', self.close='27036.4'

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=21631 

self.closeSec=1697012399, self.tradeDate='20231011', self.openTime='161000', self.closeTime='161959', self.symbol='BTCUSDT', self.open='27036.4', self.close='27054.4'
127.0.0.1 - - [11/Oct/2023 16:20:06] "POST / HTTP/1.1" 200 -


## /root/FIL/strategy/sr_min/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=1, self.total=996015.990996, self.flagDict['side']='buy', self.tradeCount=1, self.count=43252
self.closeSec=1697012399, self.tradeDate='20231011', self.openTime='161500', self.closeTime='161959', self.symbol='BTCUSDT', self.open=27048.3, self.close=27054.4, self.high=27060.0, self.low=27040.9, self.vol=565.824, self.amt=15306882.5995 
127.0.0.1 - - [11/Oct/2023 16:20:05] "POST / HTTP/1.1" 200 -
2023-10-11 16:20:08,527:INFO:sr_min:main.py:172:handleKline:2219263: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5951  20231011   155500    155959  ...         0.0        0.0       0
5952  20231011   160000    160459  ...         0.0        0.0       0
5953  20231011   160500    160959  ...         0.0        0.0       0
5954  20231011   161000    161459  ...         0.0        0.0       0
5955  20231011   161500    161959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-10-11 16:20:08,531:INFO:sr_min:main.py:175:handleKline:2219263: self.closeSec=1697012399, self.tradeDate='20231011', self.openTime='161500', self.closeTime='161959',self.symbol='BTCUSDT',self.open=27048.3, self.close=27054.4, self.high=27060.0, self.low=27040.9, self.vol=565.824, self.amt=15306882.5995, ukdf['pct'].iloc[-1]=0.000226 , ukdf['amount'].iloc[-1]=15306882.5995, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5955, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '37.141', 'enterprice': '26844', 'countrevence': '0', 'unrealprofit': '7814.4664', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '27054.4', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=1
--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=1, self.total=996015.990996, self.flagDict['side']='buy', self.tradeCount=1, self.count=43253
self.closeSec=1697012699, self.tradeDate='20231011', self.openTime='162000', self.closeTime='162459', self.symbol='BTCUSDT', self.open=27054.3, self.close=27036.6, self.high=27055.2, self.low=27036.5, self.vol=394.181, self.amt=10661907.4616 
127.0.0.1 - - [11/Oct/2023 16:25:01] "POST / HTTP/1.1" 200 -
2023-10-11 16:25:03,191:INFO:sr_min:main.py:172:handleKline:2219263: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5952  20231011   160000    160459  ...         0.0        0.0       0
5953  20231011   160500    160959  ...         0.0        0.0       0
5954  20231011   161000    161459  ...         0.0        0.0       0
5955  20231011   161500    161959  ...         0.0        0.0       0
5956  20231011   162000    162459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-10-11 16:25:03,194:INFO:sr_min:main.py:175:handleKline:2219263: self.closeSec=1697012699, self.tradeDate='20231011', self.openTime='162000', self.closeTime='162459',self.symbol='BTCUSDT',self.open=27054.3, self.close=27036.6, self.high=27055.2, self.low=27036.5, self.vol=394.181, self.amt=10661907.4616, ukdf['pct'].iloc[-1]=-0.000658 , ukdf['amount'].iloc[-1]=10661907.4616, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5956, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '37.141', 'enterprice': '26844', 'countrevence': '0', 'unrealprofit': '7198.47706492109', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '27037.81484249', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=1


## /root/FIL/strategy/s_rsrs/log.txt ----- -----

721  20231011   040000    075959  1696982399  ...    721  0.438110 -0.148669     NaN
722  20231011   080000    115959  1696996799  ...    722  0.384416 -0.298334     NaN

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '43.597', 'enterprice': '27944.4', 'countrevence': '0', 'unrealprofit': '40963.7412', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '27004.8', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-9223372036854775808, self.sign=-1
--handleKline--:  version='2.0.0', self.name='s_rsrs', self.symbol='BTCUSDT', interval='4h', intervalSec=14400, wid=25, thd=0.6, self.sign=-1, self.total=1217073.7147932001, self.flagDict['side']='sell', self.tradeCount=32, self.count=901
self.closeSec=1697011199, self.tradeDate='20231011', self.openTime='120000', self.closeTime='155959', self.symbol='BTCUSDT', self.open=27000.7, self.close=27012.8, self.high=27131.1, self.low=26951.7, self.vol=38484.453, self.amt=1041482968.3229 
127.0.0.1 - - [11/Oct/2023 16:00:01] "POST / HTTP/1.1" 200 -
2023-10-11 16:00:01,545:INFO:s_rsrs:main.py:141:handleKline:2218689: self.closeSec=1697011199, self.tradeDate='20231011', self.openTime='120000', self.closeTime='155959',self.symbol='BTCUSDT',self.open=27000.7, self.close=27012.8, self.high=27131.1, self.low=26951.7, self.vol=38484.453, self.amt=1041482968.3229 
2023-10-11 16:00:01,564:INFO:s_rsrs:main.py:142:handleKline:2218689: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime  ...        vol           amt       pct
719  20231010   200000    235959  ...  94338.609  2.588667e+09 -0.003728
720  20231011   000000    035959  ...  54866.291  1.502123e+09 -0.000332
721  20231011   040000    075959  ...  16419.750  4.498894e+08 -0.000186
722  20231011   080000    115959  ...  71624.411  1.945324e+09 -0.013922
723  20231011   120000    155959  ...  38484.453  1.041483e+09  0.000470

[5 rows x 11 columns]
2023-10-11 16:00:02,416:INFO:s_rsrs:main.py:151:handleKline:2218689: df_s.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec  ...  index      beta    zscore  signal
719  20231010   200000    235959  1696953599  ...    719  0.099732 -1.052387    -1.0
720  20231011   000000    035959  1696967999  ...    720  0.381725 -0.295344     NaN
721  20231011   040000    075959  1696982399  ...    721  0.438110 -0.148669     NaN
722  20231011   080000    115959  1696996799  ...    722  0.384416 -0.298334     NaN
723  20231011   120000    155959  1697011199  ...    723  0.492972 -0.010388     NaN

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '43.597', 'enterprice': '27944.4', 'countrevence': '0', 'unrealprofit': '40737.0368', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '27010', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-9223372036854775808, self.sign=-1


