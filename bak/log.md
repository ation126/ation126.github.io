# 20231020 00:26:03

## /root/FIL/strategy/amihud/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=373746.4768026, self.flagDict['side']='sell', self.tradeCount=2, self.count=45652
self.closeSec=1697732399, self.tradeDate='20231020', self.openTime='001500', self.closeTime='001959', self.symbol='BTCUSDT', self.open=28764.3, self.close=28818.2, self.high=28933.4, self.low=28747.0, self.vol=11670.917, self.amt=336535724.42819 
127.0.0.1 - - [20/Oct/2023 00:20:10] "POST / HTTP/1.1" 200 -
2023-10-20 00:20:17,758:INFO:amihud:main.py:172:handleKline:2219019: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5759  20231019   235500    235959  ...         0.0        0.0       0
5760  20231020   000000    000459  ...         0.0        0.0       0
5761  20231020   000500    000959  ...         0.0        0.0       0
5762  20231020   001000    001459  ...         0.0        0.0       0
5763  20231020   001500    001959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-10-20 00:20:17,779:INFO:amihud:main.py:175:handleKline:2219019: self.closeSec=1697732399, self.tradeDate='20231020', self.openTime='001500', self.closeTime='001959',self.symbol='BTCUSDT',self.open=28764.3, self.close=28818.2, self.high=28933.4, self.low=28747.0, self.vol=11670.917, self.amt=336535724.42819, ukdf['pct'].iloc[-1]=0.001836 , ukdf['amount'].iloc[-1]=336535724.42819, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5763, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '13.926', 'enterprice': '26864.9', 'countrevence': '0', 'unrealprofit': '-26986.01693272122', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '28802.71537647', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1
--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=373746.4768026, self.flagDict['side']='sell', self.tradeCount=2, self.count=45653
self.closeSec=1697732699, self.tradeDate='20231020', self.openTime='002000', self.closeTime='002459', self.symbol='BTCUSDT', self.open=28818.1, self.close=28852.7, self.high=28865.7, self.low=28775.6, self.vol=3437.774, self.amt=99037958.5613 
127.0.0.1 - - [20/Oct/2023 00:25:01] "POST / HTTP/1.1" 200 -
2023-10-20 00:25:03,324:INFO:amihud:main.py:172:handleKline:2219019: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5760  20231020   000000    000459  ...         0.0        0.0       0
5761  20231020   000500    000959  ...         0.0        0.0       0
5762  20231020   001000    001459  ...         0.0        0.0       0
5763  20231020   001500    001959  ...         0.0        0.0       0
5764  20231020   002000    002459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-10-20 00:25:03,329:INFO:amihud:main.py:175:handleKline:2219019: self.closeSec=1697732699, self.tradeDate='20231020', self.openTime='002000', self.closeTime='002459',self.symbol='BTCUSDT',self.open=28818.1, self.close=28852.7, self.high=28865.7, self.low=28775.6, self.vol=3437.774, self.amt=99037958.5613, ukdf['pct'].iloc[-1]=0.001197 , ukdf['amount'].iloc[-1]=99037958.5613, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5764, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '13.926', 'enterprice': '26864.9', 'countrevence': '0', 'unrealprofit': '-28017.7194', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '28876.8', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1


## /root/FIL/strategy/factorcheck/log.txt ----- -----

self.closeSec=1697731499, self.tradeDate='20231020', self.openTime='000000', self.closeTime='000459', self.symbol='BTCUSDT', self.open=28659.5, self.close=28723.2, self.high=28746.5, self.low=28633.0 

--ukdf-hist--: overDate='20231015' 
 Empty DataFrame
Columns: [tradeDate, openTime, closeTime, closeSec, open, close, high, low, pct, index, idx]
Index: [] 
 Empty DataFrame
Columns: [tradeDate, openTime, closeTime, closeSec, open, close, high, low, pct, index, idx]
Index: [] 

127.0.0.1 - - [20/Oct/2023 00:10:00] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.714181719035411, self.count=45652 

self.closeSec=1697731799, self.tradeDate='20231020', self.openTime='000500', self.closeTime='000959', self.symbol='BTCUSDT', self.open=28720.0, self.close=28712.0, self.high=28746.7, self.low=28666.0 

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.714181719035411, self.count=45653 

self.closeSec=1697732099, self.tradeDate='20231020', self.openTime='001000', self.closeTime='001459', self.symbol='BTCUSDT', self.open=28704.0, self.close=28765.4, self.high=28766.6, self.low=28700.1 
127.0.0.1 - - [20/Oct/2023 00:15:00] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.714181719035411, self.count=45654 

self.closeSec=1697732399, self.tradeDate='20231020', self.openTime='001500', self.closeTime='001959', self.symbol='BTCUSDT', self.open=28764.3, self.close=28818.2, self.high=28933.4, self.low=28747.0 
127.0.0.1 - - [20/Oct/2023 00:20:09] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.714181719035411, self.count=45655 

self.closeSec=1697732699, self.tradeDate='20231020', self.openTime='002000', self.closeTime='002459', self.symbol='BTCUSDT', self.open=28818.1, self.close=28852.7, self.high=28865.7, self.low=28775.6 
127.0.0.1 - - [20/Oct/2023 00:25:01] "POST / HTTP/1.1" 200 -


## /root/FIL/strategy/logic/log.txt ----- -----

2023-10-20 00:00:17,582:DEBUG:logic:main.py:463:getModel:2218526: df_s.iloc[-5:,:] :
          date closeTime     open  ...    alpha58   alpha67   alpha72
5801  20231019    212959  28460.6  ...  52.500000  0.550907  0.399473
5802  20231019    215959  28525.3  ...  52.083333  0.536368  0.387896
5803  20231019    222959  28463.4  ...  52.500000  0.541858  0.373713
5804  20231019    225959  28480.0  ...  52.916667  0.575401  0.356016
5805  20231019    232959  28665.5  ...  52.500000  0.557742  0.351310

[5 rows x 33 columns]
0.5735294117647058
acc is : 0.5735294117647058
2023-10-20 00:00:17,644:INFO:logic:main.py:468:getModel:2218526: df_pred.iloc[-5:,:] :
     pred    prob_0    prob_1  actual  ...       nav  sign   cost_        bm
539     0  0.525455  0.474545       0  ...  0.937073  -1.0  0.0000  1.020472
540     1  0.489136  0.510864       1  ...  0.936168  -1.0  0.0000  1.021457
541     0  0.513716  0.486284       1  ...  0.930260  -1.0  0.0000  1.027904
542     0  0.569030  0.430970       0  ...  0.926299   1.0 -0.0016  1.025172
543     1  0.492195  0.507805       1  ...  0.928427   1.0  0.0000  1.027527

[5 rows x 10 columns]
2023-10-20 00:00:17,656:INFO:logic:main.py:478:getModel:2218526: df_panel.iloc[-5:,:] :
    pred    prob_0    prob_1  actual  ...       nav  sign   cost_        bm
45     0  0.525364  0.474636       0  ...  0.937073  -1.0  0.0000  1.018981
46     1  0.489409  0.510591       1  ...  0.936168  -1.0  0.0000  1.021992
47     0  0.513697  0.486303       1  ...  0.930260  -1.0  0.0000  1.027992
48     0  0.569248  0.430752       0  ...  0.926299   1.0 -0.0016  1.025260
49     1  0.492195  0.507805       1  ...  0.928427   1.0  0.0000  1.027527

[5 rows x 10 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '21.528', 'enterprice': '28565.1', 'countrevence': '0', 'unrealprofit': '2019.3264', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '28658.9', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}


## /root/FIL/strategy/modifiedmom/log.txt ----- -----


--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=22823 

self.closeSec=1697729399, self.tradeDate='20231019', self.openTime='232000', self.closeTime='232959', self.symbol='BTCUSDT', self.open='28650.4', self.close='28594.5'
127.0.0.1 - - [19/Oct/2023 23:30:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=22824 

self.closeSec=1697729999, self.tradeDate='20231019', self.openTime='233000', self.closeTime='233959', self.symbol='BTCUSDT', self.open='28597.2', self.close='28638.6'
127.0.0.1 - - [19/Oct/2023 23:40:01] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [19/Oct/2023 23:50:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=22825 

self.closeSec=1697730599, self.tradeDate='20231019', self.openTime='234000', self.closeTime='234959', self.symbol='BTCUSDT', self.open='28638.5', self.close='28723.8'
127.0.0.1 - - [20/Oct/2023 00:00:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=22826 

self.closeSec=1697731199, self.tradeDate='20231019', self.openTime='235000', self.closeTime='235959', self.symbol='BTCUSDT', self.open='28710.3', self.close='28660.2'

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=22827 

self.closeSec=1697731799, self.tradeDate='20231020', self.openTime='000000', self.closeTime='000959', self.symbol='BTCUSDT', self.open='28659.5', self.close='28712'
127.0.0.1 - - [20/Oct/2023 00:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=22828 

self.closeSec=1697732399, self.tradeDate='20231020', self.openTime='001000', self.closeTime='001959', self.symbol='BTCUSDT', self.open='28704', self.close='28818.2'
127.0.0.1 - - [20/Oct/2023 00:20:11] "POST / HTTP/1.1" 200 -


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


--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=22826 

self.closeSec=1697729399, self.tradeDate='20231019', self.openTime='232000', self.closeTime='232959', self.symbol='BTCUSDT', self.open='28650.4', self.close='28594.5'
127.0.0.1 - - [19/Oct/2023 23:30:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=22827 

self.closeSec=1697729999, self.tradeDate='20231019', self.openTime='233000', self.closeTime='233959', self.symbol='BTCUSDT', self.open='28597.2', self.close='28638.6'
127.0.0.1 - - [19/Oct/2023 23:40:01] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [19/Oct/2023 23:50:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=22828 

self.closeSec=1697730599, self.tradeDate='20231019', self.openTime='234000', self.closeTime='234959', self.symbol='BTCUSDT', self.open='28638.5', self.close='28723.8'

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=22829 

self.closeSec=1697731199, self.tradeDate='20231019', self.openTime='235000', self.closeTime='235959', self.symbol='BTCUSDT', self.open='28710.3', self.close='28660.2'
127.0.0.1 - - [20/Oct/2023 00:00:01] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [20/Oct/2023 00:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=22830 

self.closeSec=1697731799, self.tradeDate='20231020', self.openTime='000000', self.closeTime='000959', self.symbol='BTCUSDT', self.open='28659.5', self.close='28712'

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=22831 

self.closeSec=1697732399, self.tradeDate='20231020', self.openTime='001000', self.closeTime='001959', self.symbol='BTCUSDT', self.open='28704', self.close='28818.2'
127.0.0.1 - - [20/Oct/2023 00:20:11] "POST / HTTP/1.1" 200 -


## /root/FIL/strategy/similarity/log.txt ----- -----


--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=22826 

self.closeSec=1697729399, self.tradeDate='20231019', self.openTime='232000', self.closeTime='232959', self.symbol='BTCUSDT', self.open='28650.4', self.close='28594.5'
127.0.0.1 - - [19/Oct/2023 23:30:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=22827 

self.closeSec=1697729999, self.tradeDate='20231019', self.openTime='233000', self.closeTime='233959', self.symbol='BTCUSDT', self.open='28597.2', self.close='28638.6'
127.0.0.1 - - [19/Oct/2023 23:40:01] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [19/Oct/2023 23:50:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=22828 

self.closeSec=1697730599, self.tradeDate='20231019', self.openTime='234000', self.closeTime='234959', self.symbol='BTCUSDT', self.open='28638.5', self.close='28723.8'

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=22829 

self.closeSec=1697731199, self.tradeDate='20231019', self.openTime='235000', self.closeTime='235959', self.symbol='BTCUSDT', self.open='28710.3', self.close='28660.2'
127.0.0.1 - - [20/Oct/2023 00:00:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=22830 

self.closeSec=1697731799, self.tradeDate='20231020', self.openTime='000000', self.closeTime='000959', self.symbol='BTCUSDT', self.open='28659.5', self.close='28712'
127.0.0.1 - - [20/Oct/2023 00:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=22831 

self.closeSec=1697732399, self.tradeDate='20231020', self.openTime='001000', self.closeTime='001959', self.symbol='BTCUSDT', self.open='28704', self.close='28818.2'
127.0.0.1 - - [20/Oct/2023 00:20:11] "POST / HTTP/1.1" 200 -


## /root/FIL/strategy/sr_min/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=1, self.total=996015.990996, self.flagDict['side']='buy', self.tradeCount=1, self.count=45652
self.closeSec=1697732399, self.tradeDate='20231020', self.openTime='001500', self.closeTime='001959', self.symbol='BTCUSDT', self.open=28764.3, self.close=28818.2, self.high=28933.4, self.low=28747.0, self.vol=11670.917, self.amt=336535724.42819 
127.0.0.1 - - [20/Oct/2023 00:20:10] "POST / HTTP/1.1" 200 -
2023-10-20 00:20:17,758:INFO:sr_min:main.py:172:handleKline:2219263: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5759  20231019   235500    235959  ...         0.0        0.0       0
5760  20231020   000000    000459  ...         0.0        0.0       0
5761  20231020   000500    000959  ...         0.0        0.0       0
5762  20231020   001000    001459  ...         0.0        0.0       0
5763  20231020   001500    001959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-10-20 00:20:17,780:INFO:sr_min:main.py:175:handleKline:2219263: self.closeSec=1697732399, self.tradeDate='20231020', self.openTime='001500', self.closeTime='001959',self.symbol='BTCUSDT',self.open=28764.3, self.close=28818.2, self.high=28933.4, self.low=28747.0, self.vol=11670.917, self.amt=336535724.42819, ukdf['pct'].iloc[-1]=0.001836 , ukdf['amount'].iloc[-1]=336535724.42819, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5763, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '37.141', 'enterprice': '26844', 'countrevence': '0', 'unrealprofit': '72748.64779747227', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '28802.71537647', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=1
--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=1, self.total=996015.990996, self.flagDict['side']='buy', self.tradeCount=1, self.count=45653
self.closeSec=1697732699, self.tradeDate='20231020', self.openTime='002000', self.closeTime='002459', self.symbol='BTCUSDT', self.open=28818.1, self.close=28852.7, self.high=28865.7, self.low=28775.6, self.vol=3437.774, self.amt=99037958.5613 
127.0.0.1 - - [20/Oct/2023 00:25:01] "POST / HTTP/1.1" 200 -
2023-10-20 00:25:03,325:INFO:sr_min:main.py:172:handleKline:2219263: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5760  20231020   000000    000459  ...         0.0        0.0       0
5761  20231020   000500    000959  ...         0.0        0.0       0
5762  20231020   001000    001459  ...         0.0        0.0       0
5763  20231020   001500    001959  ...         0.0        0.0       0
5764  20231020   002000    002459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-10-20 00:25:03,329:INFO:sr_min:main.py:175:handleKline:2219263: self.closeSec=1697732699, self.tradeDate='20231020', self.openTime='002000', self.closeTime='002459',self.symbol='BTCUSDT',self.open=28818.1, self.close=28852.7, self.high=28865.7, self.low=28775.6, self.vol=3437.774, self.amt=99037958.5613, ukdf['pct'].iloc[-1]=0.001197 , ukdf['amount'].iloc[-1]=99037958.5613, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5764, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '37.141', 'enterprice': '26844', 'countrevence': '0', 'unrealprofit': '75500.2248', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '28876.8', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=1


## /root/FIL/strategy/s_rsrs/log.txt ----- -----

723  20231019   120000    155959  1697702399  ...    723  0.524652 -0.206264     NaN
724  20231019   160000    195959  1697716799  ...    724  0.410138 -0.382959     NaN

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '43.806', 'enterprice': '27840.9', 'countrevence': '0', 'unrealprofit': '26076.58423662642', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '28436.17426007', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-9223372036854775808, self.sign=1
127.0.0.1 - - [20/Oct/2023 00:00:01] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='s_rsrs', self.symbol='BTCUSDT', interval='4h', intervalSec=14400, wid=25, thd=0.6, self.sign=1, self.total=1218378.8669346, self.flagDict['side']='buy', self.tradeCount=35, self.count=951
self.closeSec=1697731199, self.tradeDate='20231019', self.openTime='200000', self.closeTime='235959', self.symbol='BTCUSDT', self.open=28436.1, self.close=28660.2, self.high=28801.6, self.low=28402.2, self.vol=110931.187, self.amt=3171937194.43467 
2023-10-20 00:00:01,569:INFO:s_rsrs:main.py:141:handleKline:2218689: self.closeSec=1697731199, self.tradeDate='20231019', self.openTime='200000', self.closeTime='235959',self.symbol='BTCUSDT',self.open=28436.1, self.close=28660.2, self.high=28801.6, self.low=28402.2, self.vol=110931.187, self.amt=3171937194.43467 
2023-10-20 00:00:01,582:INFO:s_rsrs:main.py:142:handleKline:2218689: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime  ...         vol           amt       pct
721  20231019   040000    075959  ...   20335.057  5.748011e+08  0.002617
722  20231019   080000    115959  ...   37580.898  1.061172e+09 -0.002098
723  20231019   120000    155959  ...   20030.161  5.664727e+08  0.002379
724  20231019   160000    195959  ...   41213.352  1.170375e+09  0.004277
725  20231019   200000    235959  ...  110931.187  3.171937e+09  0.007881

[5 rows x 11 columns]
2023-10-20 00:00:02,309:INFO:s_rsrs:main.py:151:handleKline:2218689: df_s.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec  ...  index      beta    zscore  signal
721  20231019   040000    075959  1697673599  ...    721  0.709252  0.075467     NaN
722  20231019   080000    115959  1697687999  ...    722  0.632386 -0.040189     NaN
723  20231019   120000    155959  1697702399  ...    723  0.524652 -0.206264     NaN
724  20231019   160000    195959  1697716799  ...    724  0.410138 -0.382959     NaN
725  20231019   200000    235959  1697731199  ...    725  0.301781 -0.548275     NaN

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '43.806', 'enterprice': '27840.9', 'countrevence': '0', 'unrealprofit': '35973.4872', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '28662.1', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-9223372036854775808, self.sign=1


