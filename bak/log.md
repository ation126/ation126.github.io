# 20230830 16:26:01

## /root/FIL/strategy/amihud/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=373746.4768026, self.flagDict['side']='sell', self.tradeCount=2, self.count=31156
self.closeSec=1693383599, self.tradeDate='20230830', self.openTime='161500', self.closeTime='161959', self.symbol='BTCUSDT', self.open=27404.5, self.close=27414.4, self.high=27414.4, self.low=27397.9, self.vol=283.743, self.amt=7775294.7846 
127.0.0.1 - - [30/Aug/2023 16:20:01] "POST / HTTP/1.1" 200 -
2023-08-30 16:20:04,886:INFO:amihud:main.py:172:handleKline:2219019: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5939  20230830   155500    155959  ...         0.0        0.0       0
5940  20230830   160000    160459  ...         0.0        0.0       0
5941  20230830   160500    160959  ...         0.0        0.0       0
5942  20230830   161000    161459  ...         0.0        0.0       0
5943  20230830   161500    161959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-08-30 16:20:04,891:INFO:amihud:main.py:175:handleKline:2219019: self.closeSec=1693383599, self.tradeDate='20230830', self.openTime='161500', self.closeTime='161959',self.symbol='BTCUSDT',self.open=27404.5, self.close=27414.4, self.high=27414.4, self.low=27397.9, self.vol=283.743, self.amt=7775294.7846, ukdf['pct'].iloc[-1]=0.000361 , ukdf['amount'].iloc[-1]=7775294.7846, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5943, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '13.926', 'enterprice': '26864.9', 'countrevence': '0', 'unrealprofit': '-7652.337', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '27414.4', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1
127.0.0.1 - - [30/Aug/2023 16:25:00] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=373746.4768026, self.flagDict['side']='sell', self.tradeCount=2, self.count=31157
self.closeSec=1693383899, self.tradeDate='20230830', self.openTime='162000', self.closeTime='162459', self.symbol='BTCUSDT', self.open=27414.3, self.close=27407.8, self.high=27422.4, self.low=27400.1, self.vol=414.43, self.amt=11359690.0767 
2023-08-30 16:25:00,825:INFO:amihud:main.py:172:handleKline:2219019: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5940  20230830   160000    160459  ...         0.0        0.0       0
5941  20230830   160500    160959  ...         0.0        0.0       0
5942  20230830   161000    161459  ...         0.0        0.0       0
5943  20230830   161500    161959  ...         0.0        0.0       0
5944  20230830   162000    162459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-08-30 16:25:00,825:INFO:amihud:main.py:175:handleKline:2219019: self.closeSec=1693383899, self.tradeDate='20230830', self.openTime='162000', self.closeTime='162459',self.symbol='BTCUSDT',self.open=27414.3, self.close=27407.8, self.high=27422.4, self.low=27400.1, self.vol=414.43, self.amt=11359690.0767, ukdf['pct'].iloc[-1]=-0.000241 , ukdf['amount'].iloc[-1]=11359690.0767, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5944, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '13.926', 'enterprice': '26864.9', 'countrevence': '0', 'unrealprofit': '-7593.65286148458', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '27410.18600183', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1


## /root/FIL/strategy/factorcheck/log.txt ----- -----


--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.714181719035411, self.count=31154 

self.closeSec=1693382399, self.tradeDate='20230830', self.openTime='155500', self.closeTime='155959', self.symbol='BTCUSDT', self.open=27431.6, self.close=27427.1, self.high=27431.7, self.low=27425.2 
127.0.0.1 - - [30/Aug/2023 16:00:00] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.714181719035411, self.count=31155 

self.closeSec=1693382699, self.tradeDate='20230830', self.openTime='160000', self.closeTime='160459', self.symbol='BTCUSDT', self.open=27427.1, self.close=27401.9, self.high=27435.0, self.low=27395.7 
127.0.0.1 - - [30/Aug/2023 16:05:00] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.714181719035411, self.count=31156 

self.closeSec=1693382999, self.tradeDate='20230830', self.openTime='160500', self.closeTime='160959', self.symbol='BTCUSDT', self.open=27403.7, self.close=27405.7, self.high=27416.8, self.low=27395.6 
127.0.0.1 - - [30/Aug/2023 16:10:00] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [30/Aug/2023 16:15:00] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.714181719035411, self.count=31157 

self.closeSec=1693383299, self.tradeDate='20230830', self.openTime='161000', self.closeTime='161459', self.symbol='BTCUSDT', self.open=27405.7, self.close=27404.5, self.high=27407.8, self.low=27395.6 

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.714181719035411, self.count=31158 

self.closeSec=1693383599, self.tradeDate='20230830', self.openTime='161500', self.closeTime='161959', self.symbol='BTCUSDT', self.open=27404.5, self.close=27414.4, self.high=27414.4, self.low=27397.9 
127.0.0.1 - - [30/Aug/2023 16:20:01] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [30/Aug/2023 16:25:00] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.714181719035411, self.count=31159 

self.closeSec=1693383899, self.tradeDate='20230830', self.openTime='162000', self.closeTime='162459', self.symbol='BTCUSDT', self.open=27414.3, self.close=27407.8, self.high=27422.4, self.low=27400.1 


## /root/FIL/strategy/logic/log.txt ----- -----

2023-08-30 16:00:17,234:DEBUG:logic:main.py:463:getModel:2218526: df_s.iloc[-5:,:] :
          date closeTime     open  ...    alpha58   alpha67   alpha72
5785  20230830    132959  27427.8  ...  51.666667  0.612549  0.307392
5786  20230830    135959  27455.4  ...  52.083333  0.612675  0.307867
5787  20230830    142959  27456.2  ...  52.083333  0.605685  0.309339
5788  20230830    145959  27421.4  ...  52.083333  0.596238  0.312586
5789  20230830    152959  27371.9  ...  52.083333  0.606393  0.313302

[5 rows x 33 columns]
0.551660516605166
acc is : 0.551660516605166
2023-08-30 16:00:17,292:INFO:logic:main.py:468:getModel:2218526: df_pred.iloc[-5:,:] :
     pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
537     0  0.505254  0.494746       1  ...  0.962144  -1.0    0.0  1.052478
538     0  0.508539  0.491461       0  ...  0.963367  -1.0    0.0  1.051140
539     1  0.491767  0.508233       0  ...  0.965035  -1.0    0.0  1.049319
540     1  0.480951  0.519049       1  ...  0.962321  -1.0    0.0  1.052271
541     0  0.524671  0.475329       0  ...  0.963155  -1.0    0.0  1.051358

[5 rows x 10 columns]
2023-08-30 16:00:17,303:INFO:logic:main.py:478:getModel:2218526: df_panel.iloc[-5:,:] :
    pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
45     0  0.505339  0.494661       1  ...  0.962144  -1.0    0.0  1.053774
46     0  0.507561  0.492439       0  ...  0.963367  -1.0    0.0  1.054045
47     1  0.491728  0.508272       0  ...  0.965035  -1.0    0.0  1.051144
48     1  0.480007  0.519993       1  ...  0.962321  -1.0    0.0  1.055601
49     0  0.524671  0.475329       0  ...  0.963155  -1.0    0.0  1.051358

[5 rows x 10 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '25.499', 'enterprice': '27668.5', 'countrevence': '0', 'unrealprofit': '6132.38198128593', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '27428.00500093', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}


## /root/FIL/strategy/modifiedmom/log.txt ----- -----


--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=15575 

self.closeSec=1693380599, self.tradeDate='20230830', self.openTime='152000', self.closeTime='152959', self.symbol='BTCUSDT', self.open='27427.6', self.close='27450.9'
127.0.0.1 - - [30/Aug/2023 15:30:01] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [30/Aug/2023 15:40:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=15576 

self.closeSec=1693381199, self.tradeDate='20230830', self.openTime='153000', self.closeTime='153959', self.symbol='BTCUSDT', self.open='27450.9', self.close='27449.7'
127.0.0.1 - - [30/Aug/2023 15:50:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=15577 

self.closeSec=1693381799, self.tradeDate='20230830', self.openTime='154000', self.closeTime='154959', self.symbol='BTCUSDT', self.open='27449.7', self.close='27425.9'
127.0.0.1 - - [30/Aug/2023 16:00:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=15578 

self.closeSec=1693382399, self.tradeDate='20230830', self.openTime='155000', self.closeTime='155959', self.symbol='BTCUSDT', self.open='27425.8', self.close='27427.2'

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=15579 

self.closeSec=1693382999, self.tradeDate='20230830', self.openTime='160000', self.closeTime='160959', self.symbol='BTCUSDT', self.open='27427.1', self.close='27405.7'
127.0.0.1 - - [30/Aug/2023 16:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=15580 

self.closeSec=1693383599, self.tradeDate='20230830', self.openTime='161000', self.closeTime='161959', self.symbol='BTCUSDT', self.open='27405.7', self.close='27414.4'
127.0.0.1 - - [30/Aug/2023 16:20:04] "POST / HTTP/1.1" 200 -


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


--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=15578 

self.closeSec=1693380599, self.tradeDate='20230830', self.openTime='152000', self.closeTime='152959', self.symbol='BTCUSDT', self.open='27427.6', self.close='27450.9'
127.0.0.1 - - [30/Aug/2023 15:30:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=15579 

self.closeSec=1693381199, self.tradeDate='20230830', self.openTime='153000', self.closeTime='153959', self.symbol='BTCUSDT', self.open='27450.9', self.close='27449.7'
127.0.0.1 - - [30/Aug/2023 15:40:01] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [30/Aug/2023 15:50:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=15580 

self.closeSec=1693381799, self.tradeDate='20230830', self.openTime='154000', self.closeTime='154959', self.symbol='BTCUSDT', self.open='27449.7', self.close='27425.9'
127.0.0.1 - - [30/Aug/2023 16:00:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=15581 

self.closeSec=1693382399, self.tradeDate='20230830', self.openTime='155000', self.closeTime='155959', self.symbol='BTCUSDT', self.open='27425.8', self.close='27427.2'

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=15582 

self.closeSec=1693382999, self.tradeDate='20230830', self.openTime='160000', self.closeTime='160959', self.symbol='BTCUSDT', self.open='27427.1', self.close='27405.7'
127.0.0.1 - - [30/Aug/2023 16:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=15583 

self.closeSec=1693383599, self.tradeDate='20230830', self.openTime='161000', self.closeTime='161959', self.symbol='BTCUSDT', self.open='27405.7', self.close='27414.4'
127.0.0.1 - - [30/Aug/2023 16:20:04] "POST / HTTP/1.1" 200 -


## /root/FIL/strategy/similarity/log.txt ----- -----


--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=15578 

self.closeSec=1693380599, self.tradeDate='20230830', self.openTime='152000', self.closeTime='152959', self.symbol='BTCUSDT', self.open='27427.6', self.close='27450.9'
127.0.0.1 - - [30/Aug/2023 15:30:01] "POST / HTTP/1.1" 200 -

--handleKline--:  127.0.0.1 - - [30/Aug/2023 15:40:01] "POST / HTTP/1.1" 200 -
self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=15579 

self.closeSec=1693381199, self.tradeDate='20230830', self.openTime='153000', self.closeTime='153959', self.symbol='BTCUSDT', self.open='27450.9', self.close='27449.7'
127.0.0.1 - - [30/Aug/2023 15:50:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=15580 

self.closeSec=1693381799, self.tradeDate='20230830', self.openTime='154000', self.closeTime='154959', self.symbol='BTCUSDT', self.open='27449.7', self.close='27425.9'

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=15581 

self.closeSec=1693382399, self.tradeDate='20230830', self.openTime='155000', self.closeTime='155959', self.symbol='BTCUSDT', self.open='27425.8', self.close='27427.2'
127.0.0.1 - - [30/Aug/2023 16:00:01] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [30/Aug/2023 16:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=15582 

self.closeSec=1693382999, self.tradeDate='20230830', self.openTime='160000', self.closeTime='160959', self.symbol='BTCUSDT', self.open='27427.1', self.close='27405.7'

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=15583 

self.closeSec=1693383599, self.tradeDate='20230830', self.openTime='161000', self.closeTime='161959', self.symbol='BTCUSDT', self.open='27405.7', self.close='27414.4'
127.0.0.1 - - [30/Aug/2023 16:20:04] "POST / HTTP/1.1" 200 -


## /root/FIL/strategy/sr_min/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=1, self.total=996015.990996, self.flagDict['side']='buy', self.tradeCount=1, self.count=31156
self.closeSec=1693383599, self.tradeDate='20230830', self.openTime='161500', self.closeTime='161959', self.symbol='BTCUSDT', self.open=27404.5, self.close=27414.4, self.high=27414.4, self.low=27397.9, self.vol=283.743, self.amt=7775294.7846 
127.0.0.1 - - [30/Aug/2023 16:20:01] "POST / HTTP/1.1" 200 -
2023-08-30 16:20:04,887:INFO:sr_min:main.py:172:handleKline:2219263: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5939  20230830   155500    155959  ...         0.0        0.0       0
5940  20230830   160000    160459  ...         0.0        0.0       0
5941  20230830   160500    160959  ...         0.0        0.0       0
5942  20230830   161000    161459  ...         0.0        0.0       0
5943  20230830   161500    161959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-08-30 16:20:04,892:INFO:sr_min:main.py:175:handleKline:2219263: self.closeSec=1693383599, self.tradeDate='20230830', self.openTime='161500', self.closeTime='161959',self.symbol='BTCUSDT',self.open=27404.5, self.close=27414.4, self.high=27414.4, self.low=27397.9, self.vol=283.743, self.amt=7775294.7846, ukdf['pct'].iloc[-1]=0.000361 , ukdf['amount'].iloc[-1]=7775294.7846, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5943, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '37.141', 'enterprice': '26844', 'countrevence': '0', 'unrealprofit': '21185.2264', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '27414.4', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=1
--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=1, self.total=996015.990996, self.flagDict['side']='buy', self.tradeCount=1, self.count=31157
self.closeSec=1693383899, self.tradeDate='20230830', self.openTime='162000', self.closeTime='162459', self.symbol='BTCUSDT', self.open=27414.3, self.close=27407.8, self.high=27422.4, self.low=27400.1, self.vol=414.43, self.amt=11359690.0767 
127.0.0.1 - - [30/Aug/2023 16:25:00] "POST / HTTP/1.1" 200 -
2023-08-30 16:25:00,840:INFO:sr_min:main.py:172:handleKline:2219263: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5940  20230830   160000    160459  ...         0.0        0.0       0
5941  20230830   160500    160959  ...         0.0        0.0       0
5942  20230830   161000    161459  ...         0.0        0.0       0
5943  20230830   161500    161959  ...         0.0        0.0       0
5944  20230830   162000    162459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-08-30 16:25:00,840:INFO:sr_min:main.py:175:handleKline:2219263: self.closeSec=1693383899, self.tradeDate='20230830', self.openTime='162000', self.closeTime='162459',self.symbol='BTCUSDT',self.open=27414.3, self.close=27407.8, self.high=27422.4, self.low=27400.1, self.vol=414.43, self.amt=11359690.0767, ukdf['pct'].iloc[-1]=-0.000241 , ukdf['amount'].iloc[-1]=11359690.0767, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5944, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '37.141', 'enterprice': '26844', 'countrevence': '0', 'unrealprofit': '21028.71429396803', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '27410.18600183', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=1


## /root/FIL/strategy/s_rsrs/log.txt ----- -----

721  20230830   040000    075959  ...  1.062729e+00  3.723992     1.0
722  20230830   080000    115959  ...  1.137097e+00  3.696823     1.0

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '57.252', 'enterprice': '27833.8', 'countrevence': '0', 'unrealprofit': '-25802.1548892978', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '27383.12308235', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=1, self.sign=1
127.0.0.1 - - [30/Aug/2023 16:00:01] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='s_rsrs', self.symbol='BTCUSDT', interval='4h', intervalSec=14400, wid=25, thd=0.6, self.sign=1, self.total=1591947.1768824002, self.flagDict['side']='buy', self.tradeCount=21, self.count=649
self.closeSec=1693382399, self.tradeDate='20230830', self.openTime='120000', self.closeTime='155959', self.symbol='BTCUSDT', self.open=27379.2, self.close=27427.2, self.high=27464.0, self.low=27360.0, self.vol=23307.828, self.amt=639141770.3697 
2023-08-30 16:00:01,553:INFO:s_rsrs:main.py:141:handleKline:2218689: self.closeSec=1693382399, self.tradeDate='20230830', self.openTime='120000', self.closeTime='155959',self.symbol='BTCUSDT',self.open=27379.2, self.close=27427.2, self.high=27464.0, self.low=27360.0, self.vol=23307.828, self.amt=639141770.3697 
2023-08-30 16:00:01,566:INFO:s_rsrs:main.py:142:handleKline:2218689: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime  ...         vol           amt       pct
719  20230829   200000    235959  ...  362946.286  9.819943e+09  0.055759
720  20230830   000000    035959  ...  200945.529  5.596983e+09  0.014910
721  20230830   040000    075959  ...   60294.869  1.667632e+09 -0.004310
722  20230830   080000    115959  ...   66092.585  1.815526e+09 -0.011585
723  20230830   120000    155959  ...   23307.828  6.391418e+08  0.001753

[5 rows x 11 columns]
2023-08-30 16:00:02,192:INFO:s_rsrs:main.py:151:handleKline:2218689: df_s.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec  ...  index      beta    zscore  signal
719  20230829   200000    235959  1693324799  ...    719  0.000003 -1.102490    -1.0
720  20230830   000000    035959  1693339199  ...    720  1.145245  4.487494     1.0
721  20230830   040000    075959  1693353599  ...    721  1.062729  3.723992     1.0
722  20230830   080000    115959  1693367999  ...    722  1.137097  3.696823     1.0
723  20230830   120000    155959  1693382399  ...    723  1.016004  3.002526     1.0

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '57.252', 'enterprice': '27833.8', 'countrevence': '0', 'unrealprofit': '-23284.3884', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '27427.1', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=1, self.sign=1


