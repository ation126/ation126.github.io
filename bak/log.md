# 20230513 08:26:01

## /root/FIL/strategy/amihud/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=993672.4896432, self.flagDict['side']='sell', self.tradeCount=2, self.count=48021
self.closeSec=1683937199, self.tradeDate='20230513', self.openTime='081500', self.closeTime='081959', self.symbol='BTCUSDT', self.open=26741.0, self.close=26725.3, self.high=26752.2, self.low=26717.0, self.vol=1152.596, self.amt=30808385.8156 
127.0.0.1 - - [13/May/2023 08:20:03] "POST / HTTP/1.1" 200 -
2023-05-13 08:20:06,396:INFO:amihud:main.py:172:handleKline:200676: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5855  20230513   075500    075959  ...         0.0        0.0       0
5856  20230513   080000    080459  ...         0.0        0.0       0
5857  20230513   080500    080959  ...         0.0        0.0       0
5858  20230513   081000    081459  ...         0.0        0.0       0
5859  20230513   081500    081959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-05-13 08:20:06,407:INFO:amihud:main.py:175:handleKline:200676: self.closeSec=1683937199, self.tradeDate='20230513', self.openTime='081500', self.closeTime='081959',self.symbol='BTCUSDT',self.open=26741.0, self.close=26725.3, self.high=26752.2, self.low=26717.0, self.vol=1152.596, self.amt=30808385.8156, ukdf['pct'].iloc[-1]=-0.000587 , ukdf['amount'].iloc[-1]=30808385.8156, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5859, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '60.176', 'enterprice': '16529.3', 'countrevence': '0', 'unrealprofit': '-613398.0384', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '26722.7', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1
--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=993672.4896432, self.flagDict['side']='sell', self.tradeCount=2, self.count=48022
self.closeSec=1683937499, self.tradeDate='20230513', self.openTime='082000', self.closeTime='082459', self.symbol='BTCUSDT', self.open=26725.3, self.close=26711.9, self.high=26737.0, self.low=26711.9, self.vol=754.265, self.amt=20156664.579 
127.0.0.1 - - [13/May/2023 08:25:02] "POST / HTTP/1.1" 200 -
2023-05-13 08:25:02,201:INFO:amihud:main.py:172:handleKline:200676: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5856  20230513   080000    080459  ...         0.0        0.0       0
5857  20230513   080500    080959  ...         0.0        0.0       0
5858  20230513   081000    081459  ...         0.0        0.0       0
5859  20230513   081500    081959  ...         0.0        0.0       0
5860  20230513   082000    082459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-05-13 08:25:02,201:INFO:amihud:main.py:175:handleKline:200676: self.closeSec=1683937499, self.tradeDate='20230513', self.openTime='082000', self.closeTime='082459',self.symbol='BTCUSDT',self.open=26725.3, self.close=26711.9, self.high=26737.0, self.low=26711.9, self.vol=754.265, self.amt=20156664.579, ukdf['pct'].iloc[-1]=-0.000501 , ukdf['amount'].iloc[-1]=20156664.579, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5860, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '60.176', 'enterprice': '16529.3', 'countrevence': '0', 'unrealprofit': '-612852.34733263808', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '26713.63174908', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1


## /root/FIL/strategy/factorcheck/log.txt ----- -----

127.0.0.1 - - [13/May/2023 08:00:02] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=23, self.factor=0.43541661550691446, self.count=48583 

self.closeSec=1683935999, self.tradeDate='20230513', self.openTime='075500', self.closeTime='075959', self.symbol='BTCUSDT', self.open=26790.0, self.close=26785.1, self.high=26793.8, self.low=26763.6 

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=23, self.factor=0.43541661550691446, self.count=48584 

self.closeSec=1683936299, self.tradeDate='20230513', self.openTime='080000', self.closeTime='080459', self.symbol='BTCUSDT', self.open=26785.2, self.close=26763.1, self.high=26790.1, self.low=26763.0 
127.0.0.1 - - [13/May/2023 08:05:02] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=23, self.factor=0.43541661550691446, self.count=48585 

self.closeSec=1683936599, self.tradeDate='20230513', self.openTime='080500', self.closeTime='080959', self.symbol='BTCUSDT', self.open=26763.1, self.close=26770.7, self.high=26794.1, self.low=26748.5 
127.0.0.1 - - [13/May/2023 08:10:02] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=23, self.factor=0.43541661550691446, self.count=48586 

self.closeSec=1683936899, self.tradeDate='20230513', self.openTime='081000', self.closeTime='081459', self.symbol='BTCUSDT', self.open=26770.6, self.close=26741.0, self.high=26772.4, self.low=26724.9 
127.0.0.1 - - [13/May/2023 08:15:03] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=23, self.factor=0.43541661550691446, self.count=48587 

self.closeSec=1683937199, self.tradeDate='20230513', self.openTime='081500', self.closeTime='081959', self.symbol='BTCUSDT', self.open=26741.0, self.close=26725.3, self.high=26752.2, self.low=26717.0 
127.0.0.1 - - [13/May/2023 08:20:02] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=23, self.factor=0.43541661550691446, self.count=48588 

self.closeSec=1683937499, self.tradeDate='20230513', self.openTime='082000', self.closeTime='082459', self.symbol='BTCUSDT', self.open=26725.3, self.close=26711.9, self.high=26737.0, self.low=26711.9 
127.0.0.1 - - [13/May/2023 08:25:02] "POST / HTTP/1.1" 200 -


## /root/FIL/strategy/logic/log.txt ----- -----

2023-05-13 08:00:23,873:DEBUG:logic:main.py:463:getModel:885513: df_s.iloc[-5:,:] :
          date closeTime     open  ...    alpha58   alpha67   alpha72
5769  20230513    052959  26425.6  ...  49.166667  0.494493  0.691944
5770  20230513    055959  26790.3  ...  49.166667  0.487167  0.654318
5771  20230513    062959  26733.2  ...  49.166667  0.488049  0.619126
5772  20230513    065959  26739.8  ...  49.166667  0.479754  0.590050
5773  20230513    072959  26675.8  ...  49.166667  0.488255  0.559301

[5 rows x 33 columns]
0.5148148148148148
acc is : 0.5148148148148148
2023-05-13 08:00:24,001:INFO:logic:main.py:468:getModel:885513: df_pred.iloc[-5:,:] :
     pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
535     0  0.614720  0.385280       0  ...  0.961420   1.0    0.0  0.945766
536     0  0.563466  0.436534       1  ...  0.961653   1.0    0.0  0.945996
537     0  0.532588  0.467412       0  ...  0.959352   1.0    0.0  0.943731
538     0  0.518058  0.481942       1  ...  0.961556   1.0    0.0  0.945900
539     0  0.540686  0.459314       1  ...  0.963286   1.0    0.0  0.947602

[5 rows x 10 columns]
2023-05-13 08:00:24,032:INFO:logic:main.py:478:getModel:885513: df_panel.iloc[-5:,:] :
    pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
45     0  0.613615  0.386385       0  ...  0.986705   1.0    0.0  0.949390
46     0  0.563598  0.436402       1  ...  0.961653   1.0    0.0  0.951367
47     0  0.532557  0.467443       0  ...  0.984583   1.0    0.0  0.940925
48     0  0.518343  0.481657       1  ...  0.961556   1.0    0.0  0.949147
49     0  0.540686  0.459314       1  ...  0.963286   1.0    0.0  0.947602

[5 rows x 10 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': []}


## /root/FIL/strategy/modifiedmom/log.txt ----- -----

127.0.0.1 - - [13/May/2023 07:30:03] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=24289 

self.closeSec=1683934199, self.tradeDate='20230513', self.openTime='072000', self.closeTime='072959', self.symbol='BTCUSDT', self.open='26708.8', self.close='26737'
127.0.0.1 - - [13/May/2023 07:40:02] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=24290 

self.closeSec=1683934799, self.tradeDate='20230513', self.openTime='073000', self.closeTime='073959', self.symbol='BTCUSDT', self.open='26737', self.close='26747.9'

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=24291 

self.closeSec=1683935399, self.tradeDate='20230513', self.openTime='074000', self.closeTime='074959', self.symbol='BTCUSDT', self.open='26747.8', self.close='26740.1'
127.0.0.1 - - [13/May/2023 07:50:02] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=24292 

self.closeSec=1683935999, self.tradeDate='20230513', self.openTime='075000', self.closeTime='075959', self.symbol='BTCUSDT', self.open='26740', self.close='26785.1'
127.0.0.1 - - [13/May/2023 08:00:03] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [13/May/2023 08:10:02] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=24293 

self.closeSec=1683936599, self.tradeDate='20230513', self.openTime='080000', self.closeTime='080959', self.symbol='BTCUSDT', self.open='26785.2', self.close='26770.7'

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=24294 

self.closeSec=1683937199, self.tradeDate='20230513', self.openTime='081000', self.closeTime='081959', self.symbol='BTCUSDT', self.open='26770.6', self.close='26725.3'
127.0.0.1 - - [13/May/2023 08:20:05] "POST / HTTP/1.1" 200 -


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


--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=24290 

self.closeSec=1683934199, self.tradeDate='20230513', self.openTime='072000', self.closeTime='072959', self.symbol='BTCUSDT', self.open='26708.8', self.close='26737'
127.0.0.1 - - [13/May/2023 07:30:03] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [13/May/2023 07:40:02] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=24291 

self.closeSec=1683934799, self.tradeDate='20230513', self.openTime='073000', self.closeTime='073959', self.symbol='BTCUSDT', self.open='26737', self.close='26747.9'
127.0.0.1 - - [13/May/2023 07:50:02] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=24292 

self.closeSec=1683935399, self.tradeDate='20230513', self.openTime='074000', self.closeTime='074959', self.symbol='BTCUSDT', self.open='26747.8', self.close='26740.1'
127.0.0.1 - - [13/May/2023 08:00:03] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=24293 

self.closeSec=1683935999, self.tradeDate='20230513', self.openTime='075000', self.closeTime='075959', self.symbol='BTCUSDT', self.open='26740', self.close='26785.1'

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=24294 

self.closeSec=1683936599, self.tradeDate='20230513', self.openTime='080000', self.closeTime='080959', self.symbol='BTCUSDT', self.open='26785.2', self.close='26770.7'
127.0.0.1 - - [13/May/2023 08:10:02] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=24295 

self.closeSec=1683937199, self.tradeDate='20230513', self.openTime='081000', self.closeTime='081959', self.symbol='BTCUSDT', self.open='26770.6', self.close='26725.3'
127.0.0.1 - - [13/May/2023 08:20:05] "POST / HTTP/1.1" 200 -


## /root/FIL/strategy/similarity/log.txt ----- -----


--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=24290 

self.closeSec=1683934199, self.tradeDate='20230513', self.openTime='072000', self.closeTime='072959', self.symbol='BTCUSDT', self.open='26708.8', self.close='26737'
127.0.0.1 - - [13/May/2023 07:30:03] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=24291 

self.closeSec=1683934799, self.tradeDate='20230513', self.openTime='073000', self.closeTime='073959', self.symbol='BTCUSDT', self.open='26737', self.close='26747.9'
127.0.0.1 - - [13/May/2023 07:40:02] "POST / HTTP/1.1" 200 -

--handleKline--: 127.0.0.1 - - [13/May/2023 07:50:02] "POST / HTTP/1.1" 200 -
 self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=24292 

self.closeSec=1683935399, self.tradeDate='20230513', self.openTime='074000', self.closeTime='074959', self.symbol='BTCUSDT', self.open='26747.8', self.close='26740.1'

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=24293 

self.closeSec=1683935999, self.tradeDate='20230513', self.openTime='075000', self.closeTime='075959', self.symbol='BTCUSDT', self.open='26740', self.close='26785.1'
127.0.0.1 - - [13/May/2023 08:00:03] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=24294 

self.closeSec=1683936599, self.tradeDate='20230513', self.openTime='080000', self.closeTime='080959', self.symbol='BTCUSDT', self.open='26785.2', self.close='26770.7'
127.0.0.1 - - [13/May/2023 08:10:02] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=24295 

self.closeSec=1683937199, self.tradeDate='20230513', self.openTime='081000', self.closeTime='081959', self.symbol='BTCUSDT', self.open='26770.6', self.close='26725.3'
127.0.0.1 - - [13/May/2023 08:20:05] "POST / HTTP/1.1" 200 -


## /root/FIL/strategy/sr_min/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=0, self.total=1000000.0, self.flagDict['side']='', self.tradeCount=0, self.count=44019
self.closeSec=1683937199, self.tradeDate='20230513', self.openTime='081500', self.closeTime='081959', self.symbol='BTCUSDT', self.open=26741.0, self.close=26725.3, self.high=26752.2, self.low=26717.0, self.vol=1152.596, self.amt=30808385.8156 
127.0.0.1 - - [13/May/2023 08:20:02] "POST / HTTP/1.1" 200 -
2023-05-13 08:20:06,195:INFO:sr_min:main.py:172:handleKline:449472: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5855  20230513   075500    075959  ...         0.0        0.0       0
5856  20230513   080000    080459  ...         0.0        0.0       0
5857  20230513   080500    080959  ...         0.0        0.0       0
5858  20230513   081000    081459  ...         0.0        0.0       0
5859  20230513   081500    081959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-05-13 08:20:06,206:INFO:sr_min:main.py:175:handleKline:449472: self.closeSec=1683937199, self.tradeDate='20230513', self.openTime='081500', self.closeTime='081959',self.symbol='BTCUSDT',self.open=26741.0, self.close=26725.3, self.high=26752.2, self.low=26717.0, self.vol=1152.596, self.amt=30808385.8156, ukdf['pct'].iloc[-1]=-0.000587 , ukdf['amount'].iloc[-1]=30808385.8156, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5859, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': []}
type(curSign)=<class 'int'>, curSign=0, self.sign=0
--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=0, self.total=1000000.0, self.flagDict['side']='', self.tradeCount=0, self.count=44020
self.closeSec=1683937499, self.tradeDate='20230513', self.openTime='082000', self.closeTime='082459', self.symbol='BTCUSDT', self.open=26725.3, self.close=26711.9, self.high=26737.0, self.low=26711.9, self.vol=754.265, self.amt=20156664.579 
127.0.0.1 - - [13/May/2023 08:25:02] "POST / HTTP/1.1" 200 -
2023-05-13 08:25:02,206:INFO:sr_min:main.py:172:handleKline:449472: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5856  20230513   080000    080459  ...         0.0        0.0       0
5857  20230513   080500    080959  ...         0.0        0.0       0
5858  20230513   081000    081459  ...         0.0        0.0       0
5859  20230513   081500    081959  ...         0.0        0.0       0
5860  20230513   082000    082459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-05-13 08:25:02,207:INFO:sr_min:main.py:175:handleKline:449472: self.closeSec=1683937499, self.tradeDate='20230513', self.openTime='082000', self.closeTime='082459',self.symbol='BTCUSDT',self.open=26725.3, self.close=26711.9, self.high=26737.0, self.low=26711.9, self.vol=754.265, self.amt=20156664.579, ukdf['pct'].iloc[-1]=-0.000501 , ukdf['amount'].iloc[-1]=20156664.579, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5860, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': []}
type(curSign)=<class 'int'>, curSign=0, self.sign=0


## /root/FIL/strategy/s_rsrs/log.txt ----- -----

719  20230512   200000    235959  1683907199  ...    719  0.400387 -0.259278     NaN
720  20230513   000000    035959  1683921599  ...    720  0.421779 -0.152010     NaN

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '52.436', 'enterprice': '26818.7', 'countrevence': '0', 'unrealprofit': '19821.34253992504', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '26440.68980586', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-9223372036854775808, self.sign=-1
--handleKline--:  version='2.0.0', self.name='s_rsrs', self.symbol='BTCUSDT', interval='4h', intervalSec=14400, wid=25, thd=0.6, self.sign=-1, self.total=1404859.0878468, self.flagDict['side']='sell', self.tradeCount=35, self.count=1012
self.closeSec=1683935999, self.tradeDate='20230513', self.openTime='040000', self.closeTime='075959', self.symbol='BTCUSDT', self.open=26445.1, self.close=26785.1, self.high=26882.8, self.low=26347.5, self.vol=107072.897, self.amt=2850922182.99945 127.0.0.1 - - [13/May/2023 08:00:03] "POST / HTTP/1.1" 200 -

2023-05-13 08:00:03,565:INFO:s_rsrs:main.py:141:handleKline:185271: self.closeSec=1683935999, self.tradeDate='20230513', self.openTime='040000', self.closeTime='075959',self.symbol='BTCUSDT',self.open=26445.1, self.close=26785.1, self.high=26882.8, self.low=26347.5, self.vol=107072.897, self.amt=2850922182.99945 
2023-05-13 08:00:03,601:INFO:s_rsrs:main.py:142:handleKline:185271: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime  ...         vol           amt       pct
717  20230512   120000    155959  ...  131694.685  3.469452e+09 -0.010563
718  20230512   160000    195959  ...   54978.691  1.448095e+09  0.001479
719  20230512   200000    235959  ...   98862.763  2.610546e+09 -0.000961
720  20230513   000000    035959  ...  132224.157  3.458559e+09  0.005227
721  20230513   040000    075959  ...  107072.897  2.850922e+09  0.012853

[5 rows x 11 columns]
2023-05-13 08:00:05,737:INFO:s_rsrs:main.py:151:handleKline:185271: df_s.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec  ...  index      beta    zscore  signal
717  20230512   120000    155959  1683878399  ...    717  0.214334 -1.014252    -1.0
718  20230512   160000    195959  1683892799  ...    718  0.324968 -0.572268     NaN
719  20230512   200000    235959  1683907199  ...    719  0.400387 -0.259278     NaN
720  20230513   000000    035959  1683921599  ...    720  0.421779 -0.152010     NaN
721  20230513   040000    075959  1683935999  ...    721  0.430637 -0.094261     NaN

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '52.436', 'enterprice': '26818.7', 'countrevence': '0', 'unrealprofit': '1756.606', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '26785.2', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-9223372036854775808, self.sign=-1


