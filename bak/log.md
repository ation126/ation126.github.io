# 20230821 00:26:01

## /root/FIL/strategy/amihud/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=373746.4768026, self.flagDict['side']='sell', self.tradeCount=2, self.count=28372
self.closeSec=1692548399, self.tradeDate='20230821', self.openTime='001500', self.closeTime='001959', self.symbol='BTCUSDT', self.open=26073.4, self.close=26065.0, self.high=26073.4, self.low=26055.7, self.vol=384.866, self.amt=10031144.7889 
127.0.0.1 - - [21/Aug/2023 00:20:01] "POST / HTTP/1.1" 200 -
2023-08-21 00:20:05,052:INFO:amihud:main.py:172:handleKline:2219019: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5747  20230820   235500    235959  ...         0.0        0.0       0
5748  20230821   000000    000459  ...         0.0        0.0       0
5749  20230821   000500    000959  ...         0.0        0.0       0
5750  20230821   001000    001459  ...         0.0        0.0       0
5751  20230821   001500    001959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-08-21 00:20:05,056:INFO:amihud:main.py:175:handleKline:2219019: self.closeSec=1692548399, self.tradeDate='20230821', self.openTime='001500', self.closeTime='001959',self.symbol='BTCUSDT',self.open=26073.4, self.close=26065.0, self.high=26073.4, self.low=26055.7, self.vol=384.866, self.amt=10031144.7889, ukdf['pct'].iloc[-1]=-0.000318 , ukdf['amount'].iloc[-1]=10031144.7889, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5751, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '13.926', 'enterprice': '26864.9', 'countrevence': '0', 'unrealprofit': '11138.0148', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '26065.1', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1
--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=373746.4768026, self.flagDict['side']='sell', self.tradeCount=2, self.count=28373
self.closeSec=1692548699, self.tradeDate='20230821', self.openTime='002000', self.closeTime='002459', self.symbol='BTCUSDT', self.open=26065.1, self.close=26055.4, self.high=26065.1, self.low=26029.3, self.vol=1187.981, self.amt=30939889.3676 
127.0.0.1 - - [21/Aug/2023 00:25:00] "POST / HTTP/1.1" 200 -
2023-08-21 00:25:00,821:INFO:amihud:main.py:172:handleKline:2219019: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5748  20230821   000000    000459  ...         0.0        0.0       0
5749  20230821   000500    000959  ...         0.0        0.0       0
5750  20230821   001000    001459  ...         0.0        0.0       0
5751  20230821   001500    001959  ...         0.0        0.0       0
5752  20230821   002000    002459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-08-21 00:25:00,821:INFO:amihud:main.py:175:handleKline:2219019: self.closeSec=1692548699, self.tradeDate='20230821', self.openTime='002000', self.closeTime='002459',self.symbol='BTCUSDT',self.open=26065.1, self.close=26055.4, self.high=26065.1, self.low=26029.3, self.vol=1187.981, self.amt=30939889.3676, ukdf['pct'].iloc[-1]=-0.000368 , ukdf['amount'].iloc[-1]=30939889.3676, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5752, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '13.926', 'enterprice': '26864.9', 'countrevence': '0', 'unrealprofit': '11274.4896', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '26055.3', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1


## /root/FIL/strategy/factorcheck/log.txt ----- -----

[5 rows x 11 columns] 
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
201  20230816   164500    164959  1692175799  ...  29182.4 -0.000524   1641    3
202  20230816   165000    165459  1692176099  ...  29171.7 -0.000164   1642    4
203  20230816   165500    165959  1692176399  ...  29171.0 -0.000288   1643    5
204  20230816   170000    170459  1692176699  ...  29165.1 -0.000120   1644    0
205  20230816   170500    170959  1692176999  ...  29150.7 -0.000576   1645    1

[5 rows x 11 columns] 


--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.714181719035411, self.count=28372 

self.closeSec=1692547799, self.tradeDate='20230821', self.openTime='000500', self.closeTime='000959', self.symbol='BTCUSDT', self.open=26090.4, self.close=26083.7, self.high=26091.1, self.low=26076.0 
127.0.0.1 - - [21/Aug/2023 00:10:00] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [21/Aug/2023 00:15:00] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.714181719035411, self.count=28373 

self.closeSec=1692548099, self.tradeDate='20230821', self.openTime='001000', self.closeTime='001459', self.symbol='BTCUSDT', self.open=26083.8, self.close=26073.3, self.high=26083.8, self.low=26073.0 

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.714181719035411, self.count=28374 

self.closeSec=1692548399, self.tradeDate='20230821', self.openTime='001500', self.closeTime='001959', self.symbol='BTCUSDT', self.open=26073.4, self.close=26065.0, self.high=26073.4, self.low=26055.7 
127.0.0.1 - - [21/Aug/2023 00:20:01] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [21/Aug/2023 00:25:00] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.714181719035411, self.count=28375 

self.closeSec=1692548699, self.tradeDate='20230821', self.openTime='002000', self.closeTime='002459', self.symbol='BTCUSDT', self.open=26065.1, self.close=26055.4, self.high=26065.1, self.low=26029.3 


## /root/FIL/strategy/logic/log.txt ----- -----

2023-08-21 00:00:18,948:DEBUG:logic:main.py:463:getModel:2218526: df_s.iloc[-5:,:] :
          date closeTime     open  ...    alpha58   alpha67   alpha72
5801  20230820    212959  26173.9  ...  45.833333  0.468454  0.423724
5802  20230820    215959  26161.2  ...  45.416667  0.460552  0.423386
5803  20230820    222959  26127.0  ...  45.416667  0.460344  0.424003
5804  20230820    225959  26126.1  ...  45.000000  0.443037  0.450865
5805  20230820    232959  26050.0  ...  44.583333  0.442703  0.461941

[5 rows x 33 columns]
0.5367647058823529
acc is : 0.5367647058823529
2023-08-21 00:00:19,010:INFO:logic:main.py:468:getModel:2218526: df_pred.iloc[-5:,:] :
     pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
539     0  0.502429  0.497571       0  ...  1.067840  -1.0    0.0  0.877425
540     1  0.486829  0.513171       0  ...  1.067877  -1.0    0.0  0.877395
541     1  0.495275  0.504725       0  ...  1.070987  -1.0    0.0  0.874839
542     1  0.465672  0.534328       0  ...  1.071049  -1.0    0.0  0.874789
543     1  0.489164  0.510836       1  ...  1.069137  -1.0    0.0  0.876350

[5 rows x 10 columns]
2023-08-21 00:00:19,021:INFO:logic:main.py:478:getModel:2218526: df_panel.iloc[-5:,:] :
    pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
45     0  0.502402  0.497598       0  ...  1.067840  -1.0    0.0  0.878960
46     1  0.486865  0.513135       0  ...  1.067877  -1.0    0.0  0.880823
47     1  0.494752  0.505248       0  ...  1.070987  -1.0    0.0  0.876744
48     1  0.465614  0.534386       0  ...  1.071049  -1.0    0.0  0.876694
49     1  0.489164  0.510836       1  ...  1.069137  -1.0    0.0  0.876350

[5 rows x 10 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '29.581', 'enterprice': '26067.4', 'countrevence': '0', 'unrealprofit': '-687.89710735534', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '26090.65469414', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}


## /root/FIL/strategy/modifiedmom/log.txt ----- -----

127.0.0.1 - - [20/Aug/2023 23:30:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=14183 

self.closeSec=1692545399, self.tradeDate='20230820', self.openTime='232000', self.closeTime='232959', self.symbol='BTCUSDT', self.open='26108.7', self.close='26048.5'
127.0.0.1 - - [20/Aug/2023 23:40:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=14184 

self.closeSec=1692545999, self.tradeDate='20230820', self.openTime='233000', self.closeTime='233959', self.symbol='BTCUSDT', self.open='26048.5', self.close='26063.5'
127.0.0.1 - - [20/Aug/2023 23:50:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=14185 

self.closeSec=1692546599, self.tradeDate='20230820', self.openTime='234000', self.closeTime='234959', self.symbol='BTCUSDT', self.open='26063.4', self.close='26044.7'
127.0.0.1 - - [21/Aug/2023 00:00:02] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=14186 

self.closeSec=1692547199, self.tradeDate='20230820', self.openTime='235000', self.closeTime='235959', self.symbol='BTCUSDT', self.open='26044.7', self.close='26095'
127.0.0.1 - - [21/Aug/2023 00:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=14187 

self.closeSec=1692547799, self.tradeDate='20230821', self.openTime='000000', self.closeTime='000959', self.symbol='BTCUSDT', self.open='26095', self.close='26083.7'

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=14188 

self.closeSec=1692548399, self.tradeDate='20230821', self.openTime='001000', self.closeTime='001959', self.symbol='BTCUSDT', self.open='26083.8', self.close='26065.1'
127.0.0.1 - - [21/Aug/2023 00:20:03] "POST / HTTP/1.1" 200 -


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


--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=14186 

self.closeSec=1692545399, self.tradeDate='20230820', self.openTime='232000', self.closeTime='232959', self.symbol='BTCUSDT', self.open='26108.7', self.close='26048.5'
127.0.0.1 - - [20/Aug/2023 23:30:01] "POST / HTTP/1.1" 200 -

--handleKline--: 127.0.0.1 - - [20/Aug/2023 23:40:01] "POST / HTTP/1.1" 200 -
 self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=14187 

self.closeSec=1692545999, self.tradeDate='20230820', self.openTime='233000', self.closeTime='233959', self.symbol='BTCUSDT', self.open='26048.5', self.close='26063.5'

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=14188 

self.closeSec=1692546599, self.tradeDate='20230820', self.openTime='234000', self.closeTime='234959', self.symbol='BTCUSDT', self.open='26063.4', self.close='26044.7'
127.0.0.1 - - [20/Aug/2023 23:50:01] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [21/Aug/2023 00:00:02] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=14189 

self.closeSec=1692547199, self.tradeDate='20230820', self.openTime='235000', self.closeTime='235959', self.symbol='BTCUSDT', self.open='26044.7', self.close='26095'

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=14190 

self.closeSec=1692547799, self.tradeDate='20230821', self.openTime='000000', self.closeTime='000959', self.symbol='BTCUSDT', self.open='26095', self.close='26083.7'
127.0.0.1 - - [21/Aug/2023 00:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=14191 

self.closeSec=1692548399, self.tradeDate='20230821', self.openTime='001000', self.closeTime='001959', self.symbol='BTCUSDT', self.open='26083.8', self.close='26065.1'
127.0.0.1 - - [21/Aug/2023 00:20:04] "POST / HTTP/1.1" 200 -


## /root/FIL/strategy/similarity/log.txt ----- -----


--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=14186 

self.closeSec=1692545399, self.tradeDate='20230820', self.openTime='232000', self.closeTime='232959', self.symbol='BTCUSDT', self.open='26108.7', self.close='26048.5'
127.0.0.1 - - [20/Aug/2023 23:30:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=14187 

self.closeSec=1692545999, self.tradeDate='20230820', self.openTime='233000', self.closeTime='233959', self.symbol='BTCUSDT', self.open='26048.5', self.close='26063.5'
127.0.0.1 - - [20/Aug/2023 23:40:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=14188 

self.closeSec=1692546599, self.tradeDate='20230820', self.openTime='234000', self.closeTime='234959', self.symbol='BTCUSDT', self.open='26063.4', self.close='26044.7'
127.0.0.1 - - [20/Aug/2023 23:50:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=14189 

self.closeSec=1692547199, self.tradeDate='20230820', self.openTime='235000', self.closeTime='235959', self.symbol='BTCUSDT', self.open='26044.7', self.close='26095'
127.0.0.1 - - [21/Aug/2023 00:00:02] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [21/Aug/2023 00:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=14190 

self.closeSec=1692547799, self.tradeDate='20230821', self.openTime='000000', self.closeTime='000959', self.symbol='BTCUSDT', self.open='26095', self.close='26083.7'

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=14191 

self.closeSec=1692548399, self.tradeDate='20230821', self.openTime='001000', self.closeTime='001959', self.symbol='BTCUSDT', self.open='26083.8', self.close='26065.1'
127.0.0.1 - - [21/Aug/2023 00:20:03] "POST / HTTP/1.1" 200 -


## /root/FIL/strategy/sr_min/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=1, self.total=996015.990996, self.flagDict['side']='buy', self.tradeCount=1, self.count=28372
self.closeSec=1692548399, self.tradeDate='20230821', self.openTime='001500', self.closeTime='001959', self.symbol='BTCUSDT', self.open=26073.4, self.close=26065.0, self.high=26073.4, self.low=26055.7, self.vol=384.866, self.amt=10031144.7889 
127.0.0.1 - - [21/Aug/2023 00:20:01] "POST / HTTP/1.1" 200 -
2023-08-21 00:20:05,055:INFO:sr_min:main.py:172:handleKline:2219263: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5747  20230820   235500    235959  ...         0.0        0.0       0
5748  20230821   000000    000459  ...         0.0        0.0       0
5749  20230821   000500    000959  ...         0.0        0.0       0
5750  20230821   001000    001459  ...         0.0        0.0       0
5751  20230821   001500    001959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-08-21 00:20:05,065:INFO:sr_min:main.py:175:handleKline:2219263: self.closeSec=1692548399, self.tradeDate='20230821', self.openTime='001500', self.closeTime='001959',self.symbol='BTCUSDT',self.open=26073.4, self.close=26065.0, self.high=26073.4, self.low=26055.7, self.vol=384.866, self.amt=10031144.7889, ukdf['pct'].iloc[-1]=-0.000318 , ukdf['amount'].iloc[-1]=10031144.7889, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5751, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '37.141', 'enterprice': '26844', 'countrevence': '0', 'unrealprofit': '-28929.1249', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '26065.1', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=1
127.0.0.1 - - [21/Aug/2023 00:25:00] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=1, self.total=996015.990996, self.flagDict['side']='buy', self.tradeCount=1, self.count=28373
self.closeSec=1692548699, self.tradeDate='20230821', self.openTime='002000', self.closeTime='002459', self.symbol='BTCUSDT', self.open=26065.1, self.close=26055.4, self.high=26065.1, self.low=26029.3, self.vol=1187.981, self.amt=30939889.3676 
2023-08-21 00:25:00,821:INFO:sr_min:main.py:172:handleKline:2219263: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5748  20230821   000000    000459  ...         0.0        0.0       0
5749  20230821   000500    000959  ...         0.0        0.0       0
5750  20230821   001000    001459  ...         0.0        0.0       0
5751  20230821   001500    001959  ...         0.0        0.0       0
5752  20230821   002000    002459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-08-21 00:25:00,821:INFO:sr_min:main.py:175:handleKline:2219263: self.closeSec=1692548699, self.tradeDate='20230821', self.openTime='002000', self.closeTime='002459',self.symbol='BTCUSDT',self.open=26065.1, self.close=26055.4, self.high=26065.1, self.low=26029.3, self.vol=1187.981, self.amt=30939889.3676, ukdf['pct'].iloc[-1]=-0.000368 , ukdf['amount'].iloc[-1]=30939889.3676, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5752, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '37.141', 'enterprice': '26844', 'countrevence': '0', 'unrealprofit': '-29293.1067', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '26055.3', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=1


## /root/FIL/strategy/s_rsrs/log.txt ----- -----

723  20230820   120000    155959  1692518399  ...    723  0.548425  0.103157     NaN
724  20230820   160000    195959  1692532799  ...    724  0.543268  0.092481     NaN

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '51.388', 'enterprice': '29432.6', 'countrevence': '0', 'unrealprofit': '167951.95183280876', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '26164.28926923', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-9223372036854775808, self.sign=-1
127.0.0.1 - - [21/Aug/2023 00:00:01] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='s_rsrs', self.symbol='BTCUSDT', interval='4h', intervalSec=14400, wid=25, thd=0.6, self.sign=-1, self.total=1510969.9663512, self.flagDict['side']='sell', self.tradeCount=20, self.count=591
self.closeSec=1692547199, self.tradeDate='20230820', self.openTime='200000', self.closeTime='235959', self.symbol='BTCUSDT', self.open=26163.8, self.close=26095.0, self.high=26209.6, self.low=25948.5, self.vol=40356.224, self.amt=1052823097.6258 
2023-08-21 00:00:01,586:INFO:s_rsrs:main.py:141:handleKline:2218689: self.closeSec=1692547199, self.tradeDate='20230820', self.openTime='200000', self.closeTime='235959',self.symbol='BTCUSDT',self.open=26163.8, self.close=26095.0, self.high=26209.6, self.low=25948.5, self.vol=40356.224, self.amt=1052823097.6258 
2023-08-21 00:00:01,598:INFO:s_rsrs:main.py:142:handleKline:2218689: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime  ...        vol           amt       pct
721  20230820   040000    075959  ...  15244.606  3.974279e+08 -0.000934
722  20230820   080000    115959  ...  17904.105  4.672378e+08  0.000100
723  20230820   120000    155959  ...  13250.553  3.456046e+08 -0.000663
724  20230820   160000    195959  ...  19743.709  5.157573e+08  0.003463
725  20230820   200000    235959  ...  40356.224  1.052823e+09 -0.002633

[5 rows x 11 columns]
2023-08-21 00:00:02,425:INFO:s_rsrs:main.py:151:handleKline:2218689: df_s.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec  ...  index      beta    zscore  signal
721  20230820   040000    075959  1692489599  ...    721  0.541444  0.087172     NaN
722  20230820   080000    115959  1692503999  ...    722  0.546391  0.096314     NaN
723  20230820   120000    155959  1692518399  ...    723  0.548425  0.103157     NaN
724  20230820   160000    195959  1692532799  ...    724  0.543268  0.092481     NaN
725  20230820   200000    235959  1692547199  ...    725  0.535197  0.074747     NaN

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '51.388', 'enterprice': '29432.6', 'countrevence': '0', 'unrealprofit': '171512.5888', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '26095', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-9223372036854775808, self.sign=-1


