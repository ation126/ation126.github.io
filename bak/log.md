# 20230831 00:26:01

## /root/FIL/strategy/amihud/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=373746.4768026, self.flagDict['side']='sell', self.tradeCount=2, self.count=31252
self.closeSec=1693412399, self.tradeDate='20230831', self.openTime='001500', self.closeTime='001959', self.symbol='BTCUSDT', self.open=27141.4, self.close=27097.3, self.high=27154.5, self.low=27096.6, self.vol=2714.245, self.amt=73627618.2928 
127.0.0.1 - - [31/Aug/2023 00:20:01] "POST / HTTP/1.1" 200 -
2023-08-31 00:20:04,918:INFO:amihud:main.py:172:handleKline:2219019: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5747  20230830   235500    235959  ...         0.0        0.0       0
5748  20230831   000000    000459  ...         0.0        0.0       0
5749  20230831   000500    000959  ...         0.0        0.0       0
5750  20230831   001000    001459  ...         0.0        0.0       0
5751  20230831   001500    001959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-08-31 00:20:04,921:INFO:amihud:main.py:175:handleKline:2219019: self.closeSec=1693412399, self.tradeDate='20230831', self.openTime='001500', self.closeTime='001959',self.symbol='BTCUSDT',self.open=27141.4, self.close=27097.3, self.high=27154.5, self.low=27096.6, self.vol=2714.245, self.amt=73627618.2928, ukdf['pct'].iloc[-1]=-0.001625 , ukdf['amount'].iloc[-1]=73627618.2928, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5751, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '13.926', 'enterprice': '26864.9', 'countrevence': '0', 'unrealprofit': '-3308.40474256248', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '27102.47035348', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1
127.0.0.1 - - [31/Aug/2023 00:25:00] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=373746.4768026, self.flagDict['side']='sell', self.tradeCount=2, self.count=31253
self.closeSec=1693412699, self.tradeDate='20230831', self.openTime='002000', self.closeTime='002459', self.symbol='BTCUSDT', self.open=27097.2, self.close=27144.2, self.high=27151.4, self.low=27066.0, self.vol=2168.073, self.amt=58777286.2031 
2023-08-31 00:25:00,815:INFO:amihud:main.py:172:handleKline:2219019: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5748  20230831   000000    000459  ...         0.0        0.0       0
5749  20230831   000500    000959  ...         0.0        0.0       0
5750  20230831   001000    001459  ...         0.0        0.0       0
5751  20230831   001500    001959  ...         0.0        0.0       0
5752  20230831   002000    002459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-08-31 00:25:00,815:INFO:amihud:main.py:175:handleKline:2219019: self.closeSec=1693412699, self.tradeDate='20230831', self.openTime='002000', self.closeTime='002459',self.symbol='BTCUSDT',self.open=27097.2, self.close=27144.2, self.high=27151.4, self.low=27066.0, self.vol=2168.073, self.amt=58777286.2031, ukdf['pct'].iloc[-1]=0.001731 , ukdf['amount'].iloc[-1]=58777286.2031, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5752, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '13.926', 'enterprice': '26864.9', 'countrevence': '0', 'unrealprofit': '-3812.54808128172', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '27138.67194322', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1


## /root/FIL/strategy/factorcheck/log.txt ----- -----

127.0.0.1 - - [31/Aug/2023 00:05:00] "POST / HTTP/1.1" 200 -

--ukdf-hist--: overDate='20230826' 
 Empty DataFrame
Columns: [tradeDate, openTime, closeTime, closeSec, open, close, high, low, pct, index, idx]
Index: [] 
 Empty DataFrame
Columns: [tradeDate, openTime, closeTime, closeSec, open, close, high, low, pct, index, idx]
Index: [] 


--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.714181719035411, self.count=31252 

self.closeSec=1693411799, self.tradeDate='20230831', self.openTime='000500', self.closeTime='000959', self.symbol='BTCUSDT', self.open=27186.2, self.close=27166.6, self.high=27202.5, self.low=27143.3 
127.0.0.1 - - [31/Aug/2023 00:10:00] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [31/Aug/2023 00:15:00] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.714181719035411, self.count=31253 

self.closeSec=1693412099, self.tradeDate='20230831', self.openTime='001000', self.closeTime='001459', self.symbol='BTCUSDT', self.open=27164.5, self.close=27141.4, self.high=27167.4, self.low=27134.2 

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.714181719035411, self.count=31254 

self.closeSec=1693412399, self.tradeDate='20230831', self.openTime='001500', self.closeTime='001959', self.symbol='BTCUSDT', self.open=27141.4, self.close=27097.3, self.high=27154.5, self.low=27096.6 
127.0.0.1 - - [31/Aug/2023 00:20:01] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.714181719035411, self.count=31255 

self.closeSec=1693412699, self.tradeDate='20230831', self.openTime='002000', self.closeTime='002459', self.symbol='BTCUSDT', self.open=27097.2, self.close=27144.2, self.high=27151.4, self.low=27066.0 
127.0.0.1 - - [31/Aug/2023 00:25:00] "POST / HTTP/1.1" 200 -


## /root/FIL/strategy/logic/log.txt ----- -----

2023-08-31 00:00:17,638:DEBUG:logic:main.py:463:getModel:2218526: df_s.iloc[-5:,:] :
          date closeTime     open  ...    alpha58   alpha67   alpha72
5801  20230830    212959  27342.7  ...  51.666667  0.582738  0.518509
5802  20230830    215959  27415.1  ...  51.666667  0.572537  0.531478
5803  20230830    222959  27363.7  ...  51.250000  0.557407  0.549263
5804  20230830    225959  27285.5  ...  51.250000  0.523246  0.569879
5805  20230830    232959  27096.0  ...  51.250000  0.535249  0.583247

[5 rows x 33 columns]
0.5533088235294118
acc is : 0.5533088235294118
2023-08-31 00:00:17,696:INFO:logic:main.py:468:getModel:2218526: df_pred.iloc[-5:,:] :
     pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
539     0  0.524336  0.475664       0  ...  0.965326  -1.0    0.0  1.056240
540     1  0.492801  0.507199       0  ...  0.968081  -1.0    0.0  1.053226
541     1  0.482144  0.517856       0  ...  0.974790  -1.0    0.0  1.045926
542     1  0.431379  0.568621       1  ...  0.971980  -1.0    0.0  1.048941
543     0  0.513127  0.486873       1  ...  0.971358  -1.0    0.0  1.049613

[5 rows x 10 columns]
2023-08-31 00:00:17,707:INFO:logic:main.py:478:getModel:2218526: df_panel.iloc[-5:,:] :
    pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
45     0  0.524735  0.475265       0  ...  0.965326  -1.0    0.0  1.056656
46     1  0.493345  0.506655       0  ...  0.968081  -1.0    0.0  1.056599
47     1  0.481839  0.518161       0  ...  0.974790  -1.0    0.0  1.049520
48     1  0.431200  0.568800       1  ...  0.971980  -1.0    0.0  1.052545
49     0  0.513127  0.486873       1  ...  0.971358  -1.0    0.0  1.049613

[5 rows x 10 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '25.499', 'enterprice': '27668.5', 'countrevence': '0', 'unrealprofit': '12180.8723', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '27190.8', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}


## /root/FIL/strategy/modifiedmom/log.txt ----- -----


--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=15623 

self.closeSec=1693409399, self.tradeDate='20230830', self.openTime='232000', self.closeTime='232959', self.symbol='BTCUSDT', self.open='27204.6', self.close='27174.6'
127.0.0.1 - - [30/Aug/2023 23:30:01] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [30/Aug/2023 23:40:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=15624 

self.closeSec=1693409999, self.tradeDate='20230830', self.openTime='233000', self.closeTime='233959', self.symbol='BTCUSDT', self.open='27174.6', self.close='27246.4'
127.0.0.1 - - [30/Aug/2023 23:50:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=15625 

self.closeSec=1693410599, self.tradeDate='20230830', self.openTime='234000', self.closeTime='234959', self.symbol='BTCUSDT', self.open='27246.3', self.close='27177.6'

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=15626 

self.closeSec=1693411199, self.tradeDate='20230830', self.openTime='235000', self.closeTime='235959', self.symbol='BTCUSDT', self.open='27178.5', self.close='27192'
127.0.0.1 - - [31/Aug/2023 00:00:01] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [31/Aug/2023 00:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=15627 

self.closeSec=1693411799, self.tradeDate='20230831', self.openTime='000000', self.closeTime='000959', self.symbol='BTCUSDT', self.open='27191.9', self.close='27166.6'

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=15628 

self.closeSec=1693412399, self.tradeDate='20230831', self.openTime='001000', self.closeTime='001959', self.symbol='BTCUSDT', self.open='27164.5', self.close='27097.3'
127.0.0.1 - - [31/Aug/2023 00:20:04] "POST / HTTP/1.1" 200 -


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


--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=15626 

self.closeSec=1693409399, self.tradeDate='20230830', self.openTime='232000', self.closeTime='232959', self.symbol='BTCUSDT', self.open='27204.6', self.close='27174.6'
127.0.0.1 - - [30/Aug/2023 23:30:01] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [30/Aug/2023 23:40:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=15627 

self.closeSec=1693409999, self.tradeDate='20230830', self.openTime='233000', self.closeTime='233959', self.symbol='BTCUSDT', self.open='27174.6', self.close='27246.4'
127.0.0.1 - - [30/Aug/2023 23:50:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=15628 

self.closeSec=1693410599, self.tradeDate='20230830', self.openTime='234000', self.closeTime='234959', self.symbol='BTCUSDT', self.open='27246.3', self.close='27177.6'
127.0.0.1 - - [31/Aug/2023 00:00:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=15629 

self.closeSec=1693411199, self.tradeDate='20230830', self.openTime='235000', self.closeTime='235959', self.symbol='BTCUSDT', self.open='27178.5', self.close='27192'
127.0.0.1 - - [31/Aug/2023 00:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=15630 

self.closeSec=1693411799, self.tradeDate='20230831', self.openTime='000000', self.closeTime='000959', self.symbol='BTCUSDT', self.open='27191.9', self.close='27166.6'

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=15631 

self.closeSec=1693412399, self.tradeDate='20230831', self.openTime='001000', self.closeTime='001959', self.symbol='BTCUSDT', self.open='27164.5', self.close='27097.3'
127.0.0.1 - - [31/Aug/2023 00:20:04] "POST / HTTP/1.1" 200 -


## /root/FIL/strategy/similarity/log.txt ----- -----

127.0.0.1 - - [30/Aug/2023 23:30:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=15626 

self.closeSec=1693409399, self.tradeDate='20230830', self.openTime='232000', self.closeTime='232959', self.symbol='BTCUSDT', self.open='27204.6', self.close='27174.6'
127.0.0.1 - - [30/Aug/2023 23:40:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=15627 

self.closeSec=1693409999, self.tradeDate='20230830', self.openTime='233000', self.closeTime='233959', self.symbol='BTCUSDT', self.open='27174.6', self.close='27246.4'

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=15628 

self.closeSec=1693410599, self.tradeDate='20230830', self.openTime='234000', self.closeTime='234959', self.symbol='BTCUSDT', self.open='27246.3', self.close='27177.6'
127.0.0.1 - - [30/Aug/2023 23:50:01] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [31/Aug/2023 00:00:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=15629 

self.closeSec=1693411199, self.tradeDate='20230830', self.openTime='235000', self.closeTime='235959', self.symbol='BTCUSDT', self.open='27178.5', self.close='27192'
127.0.0.1 - - [31/Aug/2023 00:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=15630 

self.closeSec=1693411799, self.tradeDate='20230831', self.openTime='000000', self.closeTime='000959', self.symbol='BTCUSDT', self.open='27191.9', self.close='27166.6'

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=15631 

self.closeSec=1693412399, self.tradeDate='20230831', self.openTime='001000', self.closeTime='001959', self.symbol='BTCUSDT', self.open='27164.5', self.close='27097.3'
127.0.0.1 - - [31/Aug/2023 00:20:04] "POST / HTTP/1.1" 200 -


## /root/FIL/strategy/sr_min/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=1, self.total=996015.990996, self.flagDict['side']='buy', self.tradeCount=1, self.count=31252
self.closeSec=1693412399, self.tradeDate='20230831', self.openTime='001500', self.closeTime='001959', self.symbol='BTCUSDT', self.open=27141.4, self.close=27097.3, self.high=27154.5, self.low=27096.6, self.vol=2714.245, self.amt=73627618.2928 
127.0.0.1 - - [31/Aug/2023 00:20:01] "POST / HTTP/1.1" 200 -
2023-08-31 00:20:04,920:INFO:sr_min:main.py:172:handleKline:2219263: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5747  20230830   235500    235959  ...         0.0        0.0       0
5748  20230831   000000    000459  ...         0.0        0.0       0
5749  20230831   000500    000959  ...         0.0        0.0       0
5750  20230831   001000    001459  ...         0.0        0.0       0
5751  20230831   001500    001959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-08-31 00:20:04,923:INFO:sr_min:main.py:175:handleKline:2219263: self.closeSec=1693412399, self.tradeDate='20230831', self.openTime='001500', self.closeTime='001959',self.symbol='BTCUSDT',self.open=27141.4, self.close=27097.3, self.high=27154.5, self.low=27096.6, self.vol=2714.245, self.amt=73627618.2928, ukdf['pct'].iloc[-1]=-0.001625 , ukdf['amount'].iloc[-1]=73627618.2928, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5751, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '37.141', 'enterprice': '26844', 'countrevence': '0', 'unrealprofit': '9599.84739860068', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '27102.47035348', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=1
127.0.0.1 - - [31/Aug/2023 00:25:00] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=1, self.total=996015.990996, self.flagDict['side']='buy', self.tradeCount=1, self.count=31253
self.closeSec=1693412699, self.tradeDate='20230831', self.openTime='002000', self.closeTime='002459', self.symbol='BTCUSDT', self.open=27097.2, self.close=27144.2, self.high=27151.4, self.low=27066.0, self.vol=2168.073, self.amt=58777286.2031 
2023-08-31 00:25:00,800:INFO:sr_min:main.py:172:handleKline:2219263: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5748  20230831   000000    000459  ...         0.0        0.0       0
5749  20230831   000500    000959  ...         0.0        0.0       0
5750  20230831   001000    001459  ...         0.0        0.0       0
5751  20230831   001500    001959  ...         0.0        0.0       0
5752  20230831   002000    002459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-08-31 00:25:00,801:INFO:sr_min:main.py:175:handleKline:2219263: self.closeSec=1693412699, self.tradeDate='20230831', self.openTime='002000', self.closeTime='002459',self.symbol='BTCUSDT',self.open=27097.2, self.close=27144.2, self.high=27151.4, self.low=27066.0, self.vol=2168.073, self.amt=58777286.2031, ukdf['pct'].iloc[-1]=0.001731 , ukdf['amount'].iloc[-1]=58777286.2031, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5752, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '37.141', 'enterprice': '26844', 'countrevence': '0', 'unrealprofit': '10944.41064313402', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '27138.67194322', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=1


## /root/FIL/strategy/s_rsrs/log.txt ----- -----

723  20230830   120000    155959  1693382399  ...    723  1.016004  3.002526     1.0
724  20230830   160000    195959  1693396799  ...    724  0.980226  2.713822     1.0

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '57.252', 'enterprice': '27833.8', 'countrevence': '0', 'unrealprofit': '-29244.8819568126', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '27322.99021245', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=1, self.sign=1
--handleKline--:  version='2.0.0', self.name='s_rsrs', self.symbol='BTCUSDT', interval='4h', intervalSec=14400, wid=25, thd=0.6, self.sign=1, self.total=1591947.1768824002, self.flagDict['side']='buy', self.tradeCount=21, self.count=651
self.closeSec=1693411199, self.tradeDate='20230830', self.openTime='200000', self.closeTime='235959', self.symbol='BTCUSDT', self.open=27323.4, self.close=27192.0, self.high=27450.0, self.low=26950.0, self.vol=125823.008, self.amt=3427673943.99697 
127.0.0.1 - - [31/Aug/2023 00:00:01] "POST / HTTP/1.1" 200 -
2023-08-31 00:00:01,530:INFO:s_rsrs:main.py:141:handleKline:2218689: self.closeSec=1693411199, self.tradeDate='20230830', self.openTime='200000', self.closeTime='235959',self.symbol='BTCUSDT',self.open=27323.4, self.close=27192.0, self.high=27450.0, self.low=26950.0, self.vol=125823.008, self.amt=3427673943.99697 
2023-08-31 00:00:01,544:INFO:s_rsrs:main.py:142:handleKline:2218689: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime  ...         vol           amt       pct
721  20230830   040000    075959  ...   60294.869  1.667632e+09 -0.004310
722  20230830   080000    115959  ...   66092.585  1.815526e+09 -0.011585
723  20230830   120000    155959  ...   23307.828  6.391418e+08  0.001753
724  20230830   160000    195959  ...   35589.834  9.748422e+08 -0.003781
725  20230830   200000    235959  ...  125823.008  3.427674e+09 -0.004813

[5 rows x 11 columns]
2023-08-31 00:00:02,235:INFO:s_rsrs:main.py:151:handleKline:2218689: df_s.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec  ...  index      beta    zscore  signal
721  20230830   040000    075959  1693353599  ...    721  1.062729  3.723992     1.0
722  20230830   080000    115959  1693367999  ...    722  1.137097  3.696823     1.0
723  20230830   120000    155959  1693382399  ...    723  1.016004  3.002526     1.0
724  20230830   160000    195959  1693396799  ...    724  0.980226  2.713822     1.0
725  20230830   200000    235959  1693411199  ...    725  1.008007  2.675917     1.0

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '57.252', 'enterprice': '27833.8', 'countrevence': '0', 'unrealprofit': '-36750.0588', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '27191.9', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=1, self.sign=1


