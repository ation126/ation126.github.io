# 20230512 16:26:02

## /root/FIL/strategy/amihud/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=993672.4896432, self.flagDict['side']='sell', self.tradeCount=2, self.count=47829
self.closeSec=1683879599, self.tradeDate='20230512', self.openTime='161500', self.closeTime='161959', self.symbol='BTCUSDT', self.open=26351.0, self.close=26296.0, self.high=26355.1, self.low=26290.7, self.vol=1559.44, self.amt=41050504.9111 
127.0.0.1 - - [12/May/2023 16:20:02] "POST / HTTP/1.1" 200 -
2023-05-12 16:20:06,318:INFO:amihud:main.py:172:handleKline:200676: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5951  20230512   155500    155959  ...         0.0        0.0       0
5952  20230512   160000    160459  ...         0.0        0.0       0
5953  20230512   160500    160959  ...         0.0        0.0       0
5954  20230512   161000    161459  ...         0.0        0.0       0
5955  20230512   161500    161959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-05-12 16:20:06,320:INFO:amihud:main.py:175:handleKline:200676: self.closeSec=1683879599, self.tradeDate='20230512', self.openTime='161500', self.closeTime='161959',self.symbol='BTCUSDT',self.open=26351.0, self.close=26296.0, self.high=26355.1, self.low=26290.7, self.vol=1559.44, self.amt=41050504.9111, ukdf['pct'].iloc[-1]=-0.002087 , ukdf['amount'].iloc[-1]=41050504.9111, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5955, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '60.176', 'enterprice': '16529.3', 'countrevence': '0', 'unrealprofit': '-587742.17884995232', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '26296.35295882', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1
--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=993672.4896432, self.flagDict['side']='sell', self.tradeCount=2, self.count=47830
self.closeSec=1683879899, self.tradeDate='20230512', self.openTime='162000', self.closeTime='162459', self.symbol='BTCUSDT', self.open=26296.0, self.close=26286.4, self.high=26328.0, self.low=26268.0, self.vol=1335.197, self.amt=35099867.3732 
127.0.0.1 - - [12/May/2023 16:25:02] "POST / HTTP/1.1" 200 -
2023-05-12 16:25:02,210:INFO:amihud:main.py:172:handleKline:200676: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5952  20230512   160000    160459  ...         0.0        0.0       0
5953  20230512   160500    160959  ...         0.0        0.0       0
5954  20230512   161000    161459  ...         0.0        0.0       0
5955  20230512   161500    161959  ...         0.0        0.0       0
5956  20230512   162000    162459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-05-12 16:25:02,211:INFO:amihud:main.py:175:handleKline:200676: self.closeSec=1683879899, self.tradeDate='20230512', self.openTime='162000', self.closeTime='162459',self.symbol='BTCUSDT',self.open=26296.0, self.close=26286.4, self.high=26328.0, self.low=26268.0, self.vol=1335.197, self.amt=35099867.3732, ukdf['pct'].iloc[-1]=-0.000365 , ukdf['amount'].iloc[-1]=35099867.3732, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5956, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '60.176', 'enterprice': '16529.3', 'countrevence': '0', 'unrealprofit': '-587143.2496', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '26286.4', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1


## /root/FIL/strategy/factorcheck/log.txt ----- -----


--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=23, self.factor=0.43541661550691446, self.count=48391 

self.closeSec=1683878399, self.tradeDate='20230512', self.openTime='155500', self.closeTime='155959', self.symbol='BTCUSDT', self.open=26310.1, self.close=26294.1, self.high=26333.6, self.low=26285.0 
127.0.0.1 - - [12/May/2023 16:00:02] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=23, self.factor=0.43541661550691446, self.count=48392 

self.closeSec=1683878699, self.tradeDate='20230512', self.openTime='160000', self.closeTime='160459', self.symbol='BTCUSDT', self.open=26294.0, self.close=26329.2, self.high=26331.8, self.low=26285.6 
127.0.0.1 - - [12/May/2023 16:05:02] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [12/May/2023 16:10:02] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=23, self.factor=0.43541661550691446, self.count=48393 

self.closeSec=1683878999, self.tradeDate='20230512', self.openTime='160500', self.closeTime='160959', self.symbol='BTCUSDT', self.open=26329.3, self.close=26331.1, self.high=26344.9, self.low=26322.1 

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=23, self.factor=0.43541661550691446, self.count=48394 

self.closeSec=1683879299, self.tradeDate='20230512', self.openTime='161000', self.closeTime='161459', self.symbol='BTCUSDT', self.open=26331.2, self.close=26351.0, self.high=26362.7, self.low=26331.1 
127.0.0.1 - - [12/May/2023 16:15:03] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=23, self.factor=0.43541661550691446, self.count=48395 

self.closeSec=1683879599, self.tradeDate='20230512', self.openTime='161500', self.closeTime='161959', self.symbol='BTCUSDT', self.open=26351.0, self.close=26296.0, self.high=26355.1, self.low=26290.7 
127.0.0.1 - - [12/May/2023 16:20:02] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=23, self.factor=0.43541661550691446, self.count=48396 

self.closeSec=1683879899, self.tradeDate='20230512', self.openTime='162000', self.closeTime='162459', self.symbol='BTCUSDT', self.open=26296.0, self.close=26286.4, self.high=26328.0, self.low=26268.0 
127.0.0.1 - - [12/May/2023 16:25:02] "POST / HTTP/1.1" 200 -


## /root/FIL/strategy/logic/log.txt ----- -----

2023-05-12 16:00:20,623:DEBUG:logic:main.py:463:getModel:885513: df_s.iloc[-5:,:] :
          date closeTime     open  ...    alpha58   alpha67   alpha72
5785  20230512    132959  26644.6  ...  49.583333  0.395560  0.780370
5786  20230512    135959  26616.8  ...  49.166667  0.355567  0.789585
5787  20230512    142959  26261.3  ...  49.166667  0.345474  0.800976
5788  20230512    145959  26160.6  ...  49.166667  0.368471  0.806092
5789  20230512    152959  26287.2  ...  49.583333  0.370344  0.810408

[5 rows x 33 columns]
0.5387453874538746
acc is : 0.5387453874538746
2023-05-12 16:00:20,730:INFO:logic:main.py:468:getModel:885513: df_pred.iloc[-5:,:] :
     pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
537     0  0.502691  0.497309       0  ...  1.027991  -1.0    0.0  0.896189
538     1  0.411487  0.588513       0  ...  1.031933  -1.0    0.0  0.892753
539     1  0.457918  0.542082       1  ...  1.026939  -1.0    0.0  0.897073
540     0  0.503076  0.496924       1  ...  1.026529  -1.0    0.0  0.897431
541     1  0.484075  0.515925       0  ...  1.026669  -1.0    0.0  0.897308

[5 rows x 10 columns]
2023-05-12 16:00:20,742:INFO:logic:main.py:478:getModel:885513: df_panel.iloc[-5:,:] :
    pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
45     0  0.502953  0.497047       0  ...  1.012627  -1.0    0.0  0.894361
46     1  0.411827  0.588173       0  ...  1.043244  -1.0    0.0  0.890471
47     1  0.458447  0.541553       1  ...  1.011590  -1.0    0.0  0.899754
48     0  0.503224  0.496776       1  ...  1.000222  -1.0    0.0  0.897842
49     1  0.484075  0.515925       0  ...  1.026669  -1.0    0.0  0.897308

[5 rows x 10 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': []}


## /root/FIL/strategy/modifiedmom/log.txt ----- -----


--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=24193 

self.closeSec=1683876599, self.tradeDate='20230512', self.openTime='152000', self.closeTime='152959', self.symbol='BTCUSDT', self.open='26281.1', self.close='26297.7'
127.0.0.1 - - [12/May/2023 15:30:03] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=24194 

self.closeSec=1683877199, self.tradeDate='20230512', self.openTime='153000', self.closeTime='153959', self.symbol='BTCUSDT', self.open='26297.7', self.close='26255'
127.0.0.1 - - [12/May/2023 15:40:02] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=24195 

self.closeSec=1683877799, self.tradeDate='20230512', self.openTime='154000', self.closeTime='154959', self.symbol='BTCUSDT', self.open='26255.1', self.close='26298.1'
127.0.0.1 - - [12/May/2023 15:50:02] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=24196 

self.closeSec=1683878399, self.tradeDate='20230512', self.openTime='155000', self.closeTime='155959', self.symbol='BTCUSDT', self.open='26298.1', self.close='26294.1'
127.0.0.1 - - [12/May/2023 16:00:03] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [12/May/2023 16:10:02] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=24197 

self.closeSec=1683878999, self.tradeDate='20230512', self.openTime='160000', self.closeTime='160959', self.symbol='BTCUSDT', self.open='26294', self.close='26331.1'

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=24198 

self.closeSec=1683879599, self.tradeDate='20230512', self.openTime='161000', self.closeTime='161959', self.symbol='BTCUSDT', self.open='26331.2', self.close='26296'
127.0.0.1 - - [12/May/2023 16:20:05] "POST / HTTP/1.1" 200 -


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


--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=24194 

self.closeSec=1683876599, self.tradeDate='20230512', self.openTime='152000', self.closeTime='152959', self.symbol='BTCUSDT', self.open='26281.1', self.close='26297.7'
127.0.0.1 - - [12/May/2023 15:30:03] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [12/May/2023 15:40:02] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=24195 

self.closeSec=1683877199, self.tradeDate='20230512', self.openTime='153000', self.closeTime='153959', self.symbol='BTCUSDT', self.open='26297.7', self.close='26255'
127.0.0.1 - - [12/May/2023 15:50:02] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=24196 

self.closeSec=1683877799, self.tradeDate='20230512', self.openTime='154000', self.closeTime='154959', self.symbol='BTCUSDT', self.open='26255.1', self.close='26298.1'

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=24197 

self.closeSec=1683878399, self.tradeDate='20230512', self.openTime='155000', self.closeTime='155959', self.symbol='BTCUSDT', self.open='26298.1', self.close='26294.1'
127.0.0.1 - - [12/May/2023 16:00:03] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=24198 

self.closeSec=1683878999, self.tradeDate='20230512', self.openTime='160000', self.closeTime='160959', self.symbol='BTCUSDT', self.open='26294', self.close='26331.1'
127.0.0.1 - - [12/May/2023 16:10:02] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=24199 

self.closeSec=1683879599, self.tradeDate='20230512', self.openTime='161000', self.closeTime='161959', self.symbol='BTCUSDT', self.open='26331.2', self.close='26296'
127.0.0.1 - - [12/May/2023 16:20:05] "POST / HTTP/1.1" 200 -


## /root/FIL/strategy/similarity/log.txt ----- -----


--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=24194 

self.closeSec=1683876599, self.tradeDate='20230512', self.openTime='152000', self.closeTime='152959', self.symbol='BTCUSDT', self.open='26281.1', self.close='26297.7'
127.0.0.1 - - [12/May/2023 15:30:03] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [12/May/2023 15:40:02] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=24195 

self.closeSec=1683877199, self.tradeDate='20230512', self.openTime='153000', self.closeTime='153959', self.symbol='BTCUSDT', self.open='26297.7', self.close='26255'
127.0.0.1 - - [12/May/2023 15:50:02] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=24196 

self.closeSec=1683877799, self.tradeDate='20230512', self.openTime='154000', self.closeTime='154959', self.symbol='BTCUSDT', self.open='26255.1', self.close='26298.1'
127.0.0.1 - - [12/May/2023 16:00:03] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=24197 

self.closeSec=1683878399, self.tradeDate='20230512', self.openTime='155000', self.closeTime='155959', self.symbol='BTCUSDT', self.open='26298.1', self.close='26294.1'

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=24198 

self.closeSec=1683878999, self.tradeDate='20230512', self.openTime='160000', self.closeTime='160959', self.symbol='BTCUSDT', self.open='26294', self.close='26331.1'
127.0.0.1 - - [12/May/2023 16:10:02] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=24199 

self.closeSec=1683879599, self.tradeDate='20230512', self.openTime='161000', self.closeTime='161959', self.symbol='BTCUSDT', self.open='26331.2', self.close='26296'
127.0.0.1 - - [12/May/2023 16:20:05] "POST / HTTP/1.1" 200 -


## /root/FIL/strategy/sr_min/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=0, self.total=1000000.0, self.flagDict['side']='', self.tradeCount=0, self.count=43827
self.closeSec=1683879599, self.tradeDate='20230512', self.openTime='161500', self.closeTime='161959', self.symbol='BTCUSDT', self.open=26351.0, self.close=26296.0, self.high=26355.1, self.low=26290.7, self.vol=1559.44, self.amt=41050504.9111 
127.0.0.1 - - [12/May/2023 16:20:02] "POST / HTTP/1.1" 200 -
2023-05-12 16:20:06,264:INFO:sr_min:main.py:172:handleKline:449472: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5951  20230512   155500    155959  ...         0.0        0.0       0
5952  20230512   160000    160459  ...         0.0        0.0       0
5953  20230512   160500    160959  ...         0.0        0.0       0
5954  20230512   161000    161459  ...         0.0        0.0       0
5955  20230512   161500    161959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-05-12 16:20:06,279:INFO:sr_min:main.py:175:handleKline:449472: self.closeSec=1683879599, self.tradeDate='20230512', self.openTime='161500', self.closeTime='161959',self.symbol='BTCUSDT',self.open=26351.0, self.close=26296.0, self.high=26355.1, self.low=26290.7, self.vol=1559.44, self.amt=41050504.9111, ukdf['pct'].iloc[-1]=-0.002087 , ukdf['amount'].iloc[-1]=41050504.9111, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5955, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': []}
type(curSign)=<class 'int'>, curSign=0, self.sign=0
127.0.0.1 - - [12/May/2023 16:25:02] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=0, self.total=1000000.0, self.flagDict['side']='', self.tradeCount=0, self.count=43828
self.closeSec=1683879899, self.tradeDate='20230512', self.openTime='162000', self.closeTime='162459', self.symbol='BTCUSDT', self.open=26296.0, self.close=26286.4, self.high=26328.0, self.low=26268.0, self.vol=1335.197, self.amt=35099867.3732 
2023-05-12 16:25:02,203:INFO:sr_min:main.py:172:handleKline:449472: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5952  20230512   160000    160459  ...         0.0        0.0       0
5953  20230512   160500    160959  ...         0.0        0.0       0
5954  20230512   161000    161459  ...         0.0        0.0       0
5955  20230512   161500    161959  ...         0.0        0.0       0
5956  20230512   162000    162459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-05-12 16:25:02,204:INFO:sr_min:main.py:175:handleKline:449472: self.closeSec=1683879899, self.tradeDate='20230512', self.openTime='162000', self.closeTime='162459',self.symbol='BTCUSDT',self.open=26296.0, self.close=26286.4, self.high=26328.0, self.low=26268.0, self.vol=1335.197, self.amt=35099867.3732, ukdf['pct'].iloc[-1]=-0.000365 , ukdf['amount'].iloc[-1]=35099867.3732, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5956, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': []}
type(curSign)=<class 'int'>, curSign=0, self.sign=0


## /root/FIL/strategy/s_rsrs/log.txt ----- -----

721  20230512   040000    075959  1683849599  ...    721  0.274962 -0.824884    -1.0
722  20230512   080000    115959  1683863999  ...    722  0.178812 -1.164785    -1.0

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '52.436', 'enterprice': '26818.7', 'countrevence': '0', 'unrealprofit': '13133.7915677612', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '26568.2272033', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-1, self.sign=-1
127.0.0.1 - - [12/May/2023 16:00:03] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='s_rsrs', self.symbol='BTCUSDT', interval='4h', intervalSec=14400, wid=25, thd=0.6, self.sign=-1, self.total=1404859.0878468, self.flagDict['side']='sell', self.tradeCount=35, self.count=1008
self.closeSec=1683878399, self.tradeDate='20230512', self.openTime='120000', self.closeTime='155959', self.symbol='BTCUSDT', self.open=26574.7, self.close=26294.1, self.high=26699.2, self.low=26100.1, self.vol=131694.685, self.amt=3469452074.94754 
2023-05-12 16:00:03,480:INFO:s_rsrs:main.py:141:handleKline:185271: self.closeSec=1683878399, self.tradeDate='20230512', self.openTime='120000', self.closeTime='155959',self.symbol='BTCUSDT',self.open=26574.7, self.close=26294.1, self.high=26699.2, self.low=26100.1, self.vol=131694.685, self.amt=3469452074.94754 
2023-05-12 16:00:03,534:INFO:s_rsrs:main.py:142:handleKline:185271: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime  ...         vol           amt       pct
719  20230511   200000    235959  ...  187266.555  5.104507e+09 -0.008283
720  20230512   000000    035959  ...  146708.743  3.948798e+09 -0.012328
721  20230512   040000    075959  ...   53500.320  1.441430e+09  0.004659
722  20230512   080000    115959  ...   90812.315  2.428956e+09 -0.014156
723  20230512   120000    155959  ...  131694.685  3.469452e+09 -0.010563

[5 rows x 11 columns]
2023-05-12 16:00:05,203:INFO:s_rsrs:main.py:151:handleKline:185271: df_s.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec  ...  index      beta    zscore  signal
719  20230511   200000    235959  1683820799  ...    719  0.360522 -0.546813     NaN
720  20230512   000000    035959  1683835199  ...    720  0.316455 -0.690503    -1.0
721  20230512   040000    075959  1683849599  ...    721  0.274962 -0.824884    -1.0
722  20230512   080000    115959  1683863999  ...    722  0.178812 -1.164785    -1.0
723  20230512   120000    155959  1683878399  ...    723  0.214334 -1.014252    -1.0

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '52.436', 'enterprice': '26818.7', 'countrevence': '0', 'unrealprofit': '27513.1692', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '26294', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-1, self.sign=-1


