# 20230513 16:26:02

## /root/FIL/strategy/amihud/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=993672.4896432, self.flagDict['side']='sell', self.tradeCount=2, self.count=48117
self.closeSec=1683965999, self.tradeDate='20230513', self.openTime='161500', self.closeTime='161959', self.symbol='BTCUSDT', self.open=26800.7, self.close=26755.9, self.high=26800.8, self.low=26753.1, self.vol=689.16, self.amt=18447939.7816 
127.0.0.1 - - [13/May/2023 16:20:02] "POST / HTTP/1.1" 200 -
2023-05-13 16:20:06,552:INFO:amihud:main.py:172:handleKline:200676: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5951  20230513   155500    155959  ...         0.0        0.0       0
5952  20230513   160000    160459  ...         0.0        0.0       0
5953  20230513   160500    160959  ...         0.0        0.0       0
5954  20230513   161000    161459  ...         0.0        0.0       0
5955  20230513   161500    161959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-05-13 16:20:06,563:INFO:amihud:main.py:175:handleKline:200676: self.closeSec=1683965999, self.tradeDate='20230513', self.openTime='161500', self.closeTime='161959',self.symbol='BTCUSDT',self.open=26800.7, self.close=26755.9, self.high=26800.8, self.low=26753.1, self.vol=689.16, self.amt=18447939.7816, ukdf['pct'].iloc[-1]=-0.001675 , ukdf['amount'].iloc[-1]=18447939.7816, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5955, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '60.176', 'enterprice': '16529.3', 'countrevence': '0', 'unrealprofit': '-615287.5648', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '26754.1', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1
127.0.0.1 - - [13/May/2023 16:25:02] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=993672.4896432, self.flagDict['side']='sell', self.tradeCount=2, self.count=48118
self.closeSec=1683966299, self.tradeDate='20230513', self.openTime='162000', self.closeTime='162459', self.symbol='BTCUSDT', self.open=26755.8, self.close=26742.1, self.high=26757.3, self.low=26741.3, self.vol=755.155, self.amt=20199151.6059 
2023-05-13 16:25:02,221:INFO:amihud:main.py:172:handleKline:200676: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5952  20230513   160000    160459  ...         0.0        0.0       0
5953  20230513   160500    160959  ...         0.0        0.0       0
5954  20230513   161000    161459  ...         0.0        0.0       0
5955  20230513   161500    161959  ...         0.0        0.0       0
5956  20230513   162000    162459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-05-13 16:25:02,222:INFO:amihud:main.py:175:handleKline:200676: self.closeSec=1683966299, self.tradeDate='20230513', self.openTime='162000', self.closeTime='162459',self.symbol='BTCUSDT',self.open=26755.8, self.close=26742.1, self.high=26757.3, self.low=26741.3, self.vol=755.155, self.amt=20199151.6059, ukdf['pct'].iloc[-1]=-0.000516 , ukdf['amount'].iloc[-1]=20199151.6059, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5956, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '60.176', 'enterprice': '16529.3', 'countrevence': '0', 'unrealprofit': '-614576.44726390288', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '26742.28270513', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1


## /root/FIL/strategy/factorcheck/log.txt ----- -----

127.0.0.1 - - [13/May/2023 16:00:02] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=23, self.factor=0.43541661550691446, self.count=48679 

self.closeSec=1683964799, self.tradeDate='20230513', self.openTime='155500', self.closeTime='155959', self.symbol='BTCUSDT', self.open=26760.7, self.close=26759.3, self.high=26767.5, self.low=26756.0 

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=23, self.factor=0.43541661550691446, self.count=48680 

self.closeSec=1683965099, self.tradeDate='20230513', self.openTime='160000', self.closeTime='160459', self.symbol='BTCUSDT', self.open=26759.2, self.close=26758.7, self.high=26764.6, self.low=26750.2 
127.0.0.1 - - [13/May/2023 16:05:02] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=23, self.factor=0.43541661550691446, self.count=48681 

self.closeSec=1683965399, self.tradeDate='20230513', self.openTime='160500', self.closeTime='160959', self.symbol='BTCUSDT', self.open=26758.6, self.close=26774.3, self.high=26774.6, self.low=26751.6 
127.0.0.1 - - [13/May/2023 16:10:02] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=23, self.factor=0.43541661550691446, self.count=48682 

self.closeSec=1683965699, self.tradeDate='20230513', self.openTime='161000', self.closeTime='161459', self.symbol='BTCUSDT', self.open=26774.4, self.close=26800.8, self.high=26806.6, self.low=26774.4 
127.0.0.1 - - [13/May/2023 16:15:03] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=23, self.factor=0.43541661550691446, self.count=48683 

self.closeSec=1683965999, self.tradeDate='20230513', self.openTime='161500', self.closeTime='161959', self.symbol='BTCUSDT', self.open=26800.7, self.close=26755.9, self.high=26800.8, self.low=26753.1 
127.0.0.1 - - [13/May/2023 16:20:02] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [13/May/2023 16:25:02] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=23, self.factor=0.43541661550691446, self.count=48684 

self.closeSec=1683966299, self.tradeDate='20230513', self.openTime='162000', self.closeTime='162459', self.symbol='BTCUSDT', self.open=26755.8, self.close=26742.1, self.high=26757.3, self.low=26741.3 


## /root/FIL/strategy/logic/log.txt ----- -----

2023-05-13 16:00:19,667:DEBUG:logic:main.py:463:getModel:885513: df_s.iloc[-5:,:] :
          date closeTime     open  ...    alpha58   alpha67   alpha72
5785  20230513    132959  26785.0  ...  50.000000  0.498674  0.318186
5786  20230513    135959  26809.0  ...  49.583333  0.487445  0.310214
5787  20230513    142959  26731.2  ...  50.000000  0.488425  0.302418
5788  20230513    145959  26737.6  ...  50.000000  0.486133  0.295998
5789  20230513    152959  26722.1  ...  50.000000  0.485584  0.290207

[5 rows x 33 columns]
0.518450184501845
acc is : 0.518450184501845
2023-05-13 16:00:19,769:INFO:logic:main.py:468:getModel:885513: df_pred.iloc[-5:,:] :
     pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
537     0  0.510238  0.489762       0  ...  0.963642   1.0    0.0  0.953562
538     1  0.483545  0.516455       1  ...  0.963876   1.0    0.0  0.953794
539     1  0.498815  0.501185       0  ...  0.963310   1.0    0.0  0.953234
540     1  0.492685  0.507315       0  ...  0.963177   1.0    0.0  0.953102
541     1  0.495362  0.504638       1  ...  0.964655   1.0    0.0  0.954564

[5 rows x 10 columns]
2023-05-13 16:00:19,788:INFO:logic:main.py:478:getModel:885513: df_panel.iloc[-5:,:] :
    pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
45     0  0.510353  0.489647       0  ...  0.977501   1.0    0.0  0.954624
46     1  0.483606  0.516394       1  ...  0.977739   1.0    0.0  0.952167
47     1  0.498822  0.501178       0  ...  0.963310   1.0    0.0  0.952507
48     1  0.492475  0.507525       0  ...  0.963177   1.0    0.0  0.952005
49     1  0.495362  0.504638       1  ...  0.964655   1.0    0.0  0.954564

[5 rows x 10 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': []}


## /root/FIL/strategy/modifiedmom/log.txt ----- -----

127.0.0.1 - - [13/May/2023 15:30:03] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=24337 

self.closeSec=1683962999, self.tradeDate='20230513', self.openTime='152000', self.closeTime='152959', self.symbol='BTCUSDT', self.open='26736.4', self.close='26718.3'

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=24338 

self.closeSec=1683963599, self.tradeDate='20230513', self.openTime='153000', self.closeTime='153959', self.symbol='BTCUSDT', self.open='26718.3', self.close='26749.6'
127.0.0.1 - - [13/May/2023 15:40:02] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [13/May/2023 15:50:02] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=24339 

self.closeSec=1683964199, self.tradeDate='20230513', self.openTime='154000', self.closeTime='154959', self.symbol='BTCUSDT', self.open='26749.7', self.close='26771'

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=24340 

self.closeSec=1683964799, self.tradeDate='20230513', self.openTime='155000', self.closeTime='155959', self.symbol='BTCUSDT', self.open='26771', self.close='26759.3'
127.0.0.1 - - [13/May/2023 16:00:03] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=24341 

self.closeSec=1683965399, self.tradeDate='20230513', self.openTime='160000', self.closeTime='160959', self.symbol='BTCUSDT', self.open='26759.2', self.close='26774.3'
127.0.0.1 - - [13/May/2023 16:10:02] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=24342 

self.closeSec=1683965999, self.tradeDate='20230513', self.openTime='161000', self.closeTime='161959', self.symbol='BTCUSDT', self.open='26774.4', self.close='26755.9'
127.0.0.1 - - [13/May/2023 16:20:05] "POST / HTTP/1.1" 200 -


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

127.0.0.1 - - [13/May/2023 15:30:03] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=24338 

self.closeSec=1683962999, self.tradeDate='20230513', self.openTime='152000', self.closeTime='152959', self.symbol='BTCUSDT', self.open='26736.4', self.close='26718.3'
127.0.0.1 - - [13/May/2023 15:40:02] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=24339 

self.closeSec=1683963599, self.tradeDate='20230513', self.openTime='153000', self.closeTime='153959', self.symbol='BTCUSDT', self.open='26718.3', self.close='26749.6'
127.0.0.1 - - [13/May/2023 15:50:02] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=24340 

self.closeSec=1683964199, self.tradeDate='20230513', self.openTime='154000', self.closeTime='154959', self.symbol='BTCUSDT', self.open='26749.7', self.close='26771'

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=24341 

self.closeSec=1683964799, self.tradeDate='20230513', self.openTime='155000', self.closeTime='155959', self.symbol='BTCUSDT', self.open='26771', self.close='26759.3'
127.0.0.1 - - [13/May/2023 16:00:03] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [13/May/2023 16:10:02] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=24342 

self.closeSec=1683965399, self.tradeDate='20230513', self.openTime='160000', self.closeTime='160959', self.symbol='BTCUSDT', self.open='26759.2', self.close='26774.3'

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=24343 

self.closeSec=1683965999, self.tradeDate='20230513', self.openTime='161000', self.closeTime='161959', self.symbol='BTCUSDT', self.open='26774.4', self.close='26755.9'
127.0.0.1 - - [13/May/2023 16:20:05] "POST / HTTP/1.1" 200 -


## /root/FIL/strategy/similarity/log.txt ----- -----

127.0.0.1 - - [13/May/2023 15:30:03] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=24338 

self.closeSec=1683962999, self.tradeDate='20230513', self.openTime='152000', self.closeTime='152959', self.symbol='BTCUSDT', self.open='26736.4', self.close='26718.3'

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=24339 

self.closeSec=1683963599, self.tradeDate='20230513', self.openTime='153000', self.closeTime='153959', self.symbol='BTCUSDT', self.open='26718.3', self.close='26749.6'
127.0.0.1 - - [13/May/2023 15:40:02] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=24340 

self.closeSec=1683964199, self.tradeDate='20230513', self.openTime='154000', self.closeTime='154959', self.symbol='BTCUSDT', self.open='26749.7', self.close='26771'
127.0.0.1 - - [13/May/2023 15:50:02] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=24341 

self.closeSec=1683964799, self.tradeDate='20230513', self.openTime='155000', self.closeTime='155959', self.symbol='BTCUSDT', self.open='26771', self.close='26759.3'
127.0.0.1 - - [13/May/2023 16:00:03] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=24342 

self.closeSec=1683965399, self.tradeDate='20230513', self.openTime='160000', self.closeTime='160959', self.symbol='BTCUSDT', self.open='26759.2', self.close='26774.3'
127.0.0.1 - - [13/May/2023 16:10:02] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=24343 

self.closeSec=1683965999, self.tradeDate='20230513', self.openTime='161000', self.closeTime='161959', self.symbol='BTCUSDT', self.open='26774.4', self.close='26755.9'
127.0.0.1 - - [13/May/2023 16:20:05] "POST / HTTP/1.1" 200 -


## /root/FIL/strategy/sr_min/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=0, self.total=1000000.0, self.flagDict['side']='', self.tradeCount=0, self.count=44115
self.closeSec=1683965999, self.tradeDate='20230513', self.openTime='161500', self.closeTime='161959', self.symbol='BTCUSDT', self.open=26800.7, self.close=26755.9, self.high=26800.8, self.low=26753.1, self.vol=689.16, self.amt=18447939.7816 
127.0.0.1 - - [13/May/2023 16:20:02] "POST / HTTP/1.1" 200 -
2023-05-13 16:20:06,520:INFO:sr_min:main.py:172:handleKline:449472: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5951  20230513   155500    155959  ...         0.0        0.0       0
5952  20230513   160000    160459  ...         0.0        0.0       0
5953  20230513   160500    160959  ...         0.0        0.0       0
5954  20230513   161000    161459  ...         0.0        0.0       0
5955  20230513   161500    161959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-05-13 16:20:06,525:INFO:sr_min:main.py:175:handleKline:449472: self.closeSec=1683965999, self.tradeDate='20230513', self.openTime='161500', self.closeTime='161959',self.symbol='BTCUSDT',self.open=26800.7, self.close=26755.9, self.high=26800.8, self.low=26753.1, self.vol=689.16, self.amt=18447939.7816, ukdf['pct'].iloc[-1]=-0.001675 , ukdf['amount'].iloc[-1]=18447939.7816, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5955, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': []}
type(curSign)=<class 'int'>, curSign=0, self.sign=0
127.0.0.1 - - [13/May/2023 16:25:02] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=0, self.total=1000000.0, self.flagDict['side']='', self.tradeCount=0, self.count=44116
self.closeSec=1683966299, self.tradeDate='20230513', self.openTime='162000', self.closeTime='162459', self.symbol='BTCUSDT', self.open=26755.8, self.close=26742.1, self.high=26757.3, self.low=26741.3, self.vol=755.155, self.amt=20199151.6059 
2023-05-13 16:25:02,222:INFO:sr_min:main.py:172:handleKline:449472: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5952  20230513   160000    160459  ...         0.0        0.0       0
5953  20230513   160500    160959  ...         0.0        0.0       0
5954  20230513   161000    161459  ...         0.0        0.0       0
5955  20230513   161500    161959  ...         0.0        0.0       0
5956  20230513   162000    162459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-05-13 16:25:02,223:INFO:sr_min:main.py:175:handleKline:449472: self.closeSec=1683966299, self.tradeDate='20230513', self.openTime='162000', self.closeTime='162459',self.symbol='BTCUSDT',self.open=26755.8, self.close=26742.1, self.high=26757.3, self.low=26741.3, self.vol=755.155, self.amt=20199151.6059, ukdf['pct'].iloc[-1]=-0.000516 , ukdf['amount'].iloc[-1]=20199151.6059, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5956, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': []}
type(curSign)=<class 'int'>, curSign=0, self.sign=0


## /root/FIL/strategy/s_rsrs/log.txt ----- -----

721  20230513   040000    075959  1683935999  ...    721  0.430637 -0.094261     NaN
722  20230513   080000    115959  1683950399  ...    722  0.440599 -0.034408     NaN

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '52.436', 'enterprice': '26818.7', 'countrevence': '0', 'unrealprofit': '1164.0792', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '26796.5', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-9223372036854775808, self.sign=-1
127.0.0.1 - - [13/May/2023 16:00:03] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='s_rsrs', self.symbol='BTCUSDT', interval='4h', intervalSec=14400, wid=25, thd=0.6, self.sign=-1, self.total=1404859.0878468, self.flagDict['side']='sell', self.tradeCount=35, self.count=1014
self.closeSec=1683964799, self.tradeDate='20230513', self.openTime='120000', self.closeTime='155959', self.symbol='BTCUSDT', self.open=26794.6, self.close=26759.3, self.high=26862.9, self.low=26674.9, self.vol=32070.296, self.amt=858160352.0566 
2023-05-13 16:00:03,443:INFO:s_rsrs:main.py:141:handleKline:185271: self.closeSec=1683964799, self.tradeDate='20230513', self.openTime='120000', self.closeTime='155959',self.symbol='BTCUSDT',self.open=26794.6, self.close=26759.3, self.high=26862.9, self.low=26674.9, self.vol=32070.296, self.amt=858160352.0566 
2023-05-13 16:00:03,484:INFO:s_rsrs:main.py:142:handleKline:185271: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime  ...         vol           amt       pct
719  20230512   200000    235959  ...   98862.763  2.610546e+09 -0.000961
720  20230513   000000    035959  ...  132224.157  3.458559e+09  0.005227
721  20230513   040000    075959  ...  107072.897  2.850922e+09  0.012853
722  20230513   080000    115959  ...   56653.067  1.519934e+09  0.000355
723  20230513   120000    155959  ...   32070.296  8.581604e+08 -0.001317

[5 rows x 11 columns]
2023-05-13 16:00:04,904:INFO:s_rsrs:main.py:151:handleKline:185271: df_s.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec  ...  index      beta    zscore  signal
719  20230512   200000    235959  1683907199  ...    719  0.400387 -0.259278     NaN
720  20230513   000000    035959  1683921599  ...    720  0.421779 -0.152010     NaN
721  20230513   040000    075959  1683935999  ...    721  0.430637 -0.094261     NaN
722  20230513   080000    115959  1683950399  ...    722  0.440599 -0.034408     NaN
723  20230513   120000    155959  1683964799  ...    723  0.463283  0.076900     NaN

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '52.436', 'enterprice': '26818.7', 'countrevence': '0', 'unrealprofit': '3115.3042953582', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '26759.28844505', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-9223372036854775808, self.sign=-1


