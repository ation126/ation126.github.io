# 20231012 16:26:02

## /root/FIL/strategy/amihud/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=373746.4768026, self.flagDict['side']='sell', self.tradeCount=2, self.count=43540
self.closeSec=1697098799, self.tradeDate='20231012', self.openTime='161500', self.closeTime='161959', self.symbol='BTCUSDT', self.open=26769.3, self.close=26782.6, self.high=26789.0, self.low=26757.2, self.vol=532.865, self.amt=14267416.1671 
127.0.0.1 - - [12/Oct/2023 16:20:05] "POST / HTTP/1.1" 200 -
2023-10-12 16:20:08,286:INFO:amihud:main.py:172:handleKline:2219019: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5951  20231012   155500    155959  ...         0.0        0.0       0
5952  20231012   160000    160459  ...         0.0        0.0       0
5953  20231012   160500    160959  ...         0.0        0.0       0
5954  20231012   161000    161459  ...         0.0        0.0       0
5955  20231012   161500    161959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-10-12 16:20:08,297:INFO:amihud:main.py:175:handleKline:2219019: self.closeSec=1697098799, self.tradeDate='20231012', self.openTime='161500', self.closeTime='161959',self.symbol='BTCUSDT',self.open=26769.3, self.close=26782.6, self.high=26789.0, self.low=26757.2, self.vol=532.865, self.amt=14267416.1671, ukdf['pct'].iloc[-1]=0.000456 , ukdf['amount'].iloc[-1]=14267416.1671, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5955, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '13.926', 'enterprice': '26864.9', 'countrevence': '0', 'unrealprofit': '1109.73368523402', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '26785.21210073', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1
--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=373746.4768026, self.flagDict['side']='sell', self.tradeCount=2, self.count=43541
self.closeSec=1697099099, self.tradeDate='20231012', self.openTime='162000', self.closeTime='162459', self.symbol='BTCUSDT', self.open=26782.5, self.close=26779.4, self.high=26788.4, self.low=26765.0, self.vol=854.734, self.amt=22889312.9303 
127.0.0.1 - - [12/Oct/2023 16:25:01] "POST / HTTP/1.1" 200 -
2023-10-12 16:25:03,142:INFO:amihud:main.py:172:handleKline:2219019: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5952  20231012   160000    160459  ...         0.0        0.0       0
5953  20231012   160500    160959  ...         0.0        0.0       0
5954  20231012   161000    161459  ...         0.0        0.0       0
5955  20231012   161500    161959  ...         0.0        0.0       0
5956  20231012   162000    162459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-10-12 16:25:03,150:INFO:amihud:main.py:175:handleKline:2219019: self.closeSec=1697099099, self.tradeDate='20231012', self.openTime='162000', self.closeTime='162459',self.symbol='BTCUSDT',self.open=26782.5, self.close=26779.4, self.high=26788.4, self.low=26765.0, self.vol=854.734, self.amt=22889312.9303, ukdf['pct'].iloc[-1]=-0.000119 , ukdf['amount'].iloc[-1]=22889312.9303, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5956, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '13.926', 'enterprice': '26864.9', 'countrevence': '0', 'unrealprofit': '1199.41281471924', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '26778.77241026', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1


## /root/FIL/strategy/factorcheck/log.txt ----- -----


--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.714181719035411, self.count=43538 

self.closeSec=1697097599, self.tradeDate='20231012', self.openTime='155500', self.closeTime='155959', self.symbol='BTCUSDT', self.open=26792.9, self.close=26799.3, self.high=26799.4, self.low=26789.5 
127.0.0.1 - - [12/Oct/2023 16:00:00] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.714181719035411, self.count=43539 

self.closeSec=1697097899, self.tradeDate='20231012', self.openTime='160000', self.closeTime='160459', self.symbol='BTCUSDT', self.open=26799.3, self.close=26788.7, self.high=26811.2, self.low=26781.1 
127.0.0.1 - - [12/Oct/2023 16:05:00] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [12/Oct/2023 16:10:00] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.714181719035411, self.count=43540 

self.closeSec=1697098199, self.tradeDate='20231012', self.openTime='160500', self.closeTime='160959', self.symbol='BTCUSDT', self.open=26788.7, self.close=26777.9, self.high=26795.0, self.low=26751.5 
127.0.0.1 - - [12/Oct/2023 16:15:00] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.714181719035411, self.count=43541 

self.closeSec=1697098499, self.tradeDate='20231012', self.openTime='161000', self.closeTime='161459', self.symbol='BTCUSDT', self.open=26777.9, self.close=26770.4, self.high=26780.0, self.low=26766.0 

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.714181719035411, self.count=43542 

self.closeSec=1697098799, self.tradeDate='20231012', self.openTime='161500', self.closeTime='161959', self.symbol='BTCUSDT', self.open=26769.3, self.close=26782.6, self.high=26789.0, self.low=26757.2 
127.0.0.1 - - [12/Oct/2023 16:20:04] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.714181719035411, self.count=43543 

self.closeSec=1697099099, self.tradeDate='20231012', self.openTime='162000', self.closeTime='162459', self.symbol='BTCUSDT', self.open=26782.5, self.close=26779.4, self.high=26788.4, self.low=26765.0 
127.0.0.1 - - [12/Oct/2023 16:25:01] "POST / HTTP/1.1" 200 -


## /root/FIL/strategy/logic/log.txt ----- -----

2023-10-12 16:00:18,878:DEBUG:logic:main.py:463:getModel:2218526: df_s.iloc[-5:,:] :
          date closeTime     open  ...    alpha58   alpha67   alpha72
5785  20231012    132959  26809.4  ...  47.500000  0.422741  0.688559
5786  20231012    135959  26815.5  ...  47.916667  0.437273  0.680810
5787  20231012    142959  26865.9  ...  48.333333  0.441167  0.671098
5788  20231012    145959  26878.3  ...  48.333333  0.435204  0.664313
5789  20231012    152959  26852.4  ...  47.916667  0.427250  0.659910

[5 rows x 33 columns]
0.5479704797047971
acc is : 0.5479704797047971
2023-10-12 16:00:18,948:INFO:logic:main.py:468:getModel:2218526: df_pred.iloc[-5:,:] :
     pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
537     1  0.494170  0.505830       1  ...  0.973890  -1.0    0.0  0.995852
538     0  0.513996  0.486004       1  ...  0.973405  -1.0    0.0  0.996349
539     0  0.508348  0.491652       0  ...  0.974346  -1.0    0.0  0.995385
540     1  0.494789  0.505211       0  ...  0.975620  -1.0    0.0  0.994084
541     1  0.491480  0.508520       0  ...  0.976275  -1.0    0.0  0.993417

[5 rows x 10 columns]
2023-10-12 16:00:18,960:INFO:logic:main.py:478:getModel:2218526: df_panel.iloc[-5:,:] :
    pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
45     1  0.493869  0.506131       1  ...  0.973890  -1.0    0.0  0.995129
46     0  0.513782  0.486218       1  ...  0.973405  -1.0    0.0  0.997343
47     0  0.508144  0.491856       0  ...  0.974346  -1.0    0.0  0.996345
48     1  0.494342  0.505658       0  ...  0.975620  -1.0    0.0  0.994703
49     1  0.491480  0.508520       0  ...  0.976275  -1.0    0.0  0.993417

[5 rows x 10 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '24.051', 'enterprice': '26768.8', 'countrevence': '0', 'unrealprofit': '-733.5555', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '26799.3', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}


## /root/FIL/strategy/modifiedmom/log.txt ----- -----

127.0.0.1 - - [12/Oct/2023 15:30:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=21767 

self.closeSec=1697095799, self.tradeDate='20231012', self.openTime='152000', self.closeTime='152959', self.symbol='BTCUSDT', self.open='26815.1', self.close='26817.3'

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=21768 

self.closeSec=1697096399, self.tradeDate='20231012', self.openTime='153000', self.closeTime='153959', self.symbol='BTCUSDT', self.open='26817.3', self.close='26819.1'
127.0.0.1 - - [12/Oct/2023 15:40:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=21769 

self.closeSec=1697096999, self.tradeDate='20231012', self.openTime='154000', self.closeTime='154959', self.symbol='BTCUSDT', self.open='26819.3', self.close='26819.1'
127.0.0.1 - - [12/Oct/2023 15:50:01] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [12/Oct/2023 16:00:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=21770 

self.closeSec=1697097599, self.tradeDate='20231012', self.openTime='155000', self.closeTime='155959', self.symbol='BTCUSDT', self.open='26820.4', self.close='26799.3'

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=21771 

self.closeSec=1697098199, self.tradeDate='20231012', self.openTime='160000', self.closeTime='160959', self.symbol='BTCUSDT', self.open='26799.3', self.close='26777.9'
127.0.0.1 - - [12/Oct/2023 16:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=21772 

self.closeSec=1697098799, self.tradeDate='20231012', self.openTime='161000', self.closeTime='161959', self.symbol='BTCUSDT', self.open='26777.9', self.close='26782.5'
127.0.0.1 - - [12/Oct/2023 16:20:06] "POST / HTTP/1.1" 200 -


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


--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=21770 

self.closeSec=1697095799, self.tradeDate='20231012', self.openTime='152000', self.closeTime='152959', self.symbol='BTCUSDT', self.open='26815.1', self.close='26817.3'
127.0.0.1 - - [12/Oct/2023 15:30:01] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [12/Oct/2023 15:40:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=21771 

self.closeSec=1697096399, self.tradeDate='20231012', self.openTime='153000', self.closeTime='153959', self.symbol='BTCUSDT', self.open='26817.3', self.close='26819.1'

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=21772 

self.closeSec=1697096999, self.tradeDate='20231012', self.openTime='154000', self.closeTime='154959', self.symbol='BTCUSDT', self.open='26819.3', self.close='26819.1'
127.0.0.1 - - [12/Oct/2023 15:50:01] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [12/Oct/2023 16:00:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=21773 

self.closeSec=1697097599, self.tradeDate='20231012', self.openTime='155000', self.closeTime='155959', self.symbol='BTCUSDT', self.open='26820.4', self.close='26799.3'
127.0.0.1 - - [12/Oct/2023 16:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=21774 

self.closeSec=1697098199, self.tradeDate='20231012', self.openTime='160000', self.closeTime='160959', self.symbol='BTCUSDT', self.open='26799.3', self.close='26777.9'

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=21775 

self.closeSec=1697098799, self.tradeDate='20231012', self.openTime='161000', self.closeTime='161959', self.symbol='BTCUSDT', self.open='26777.9', self.close='26782.5'
127.0.0.1 - - [12/Oct/2023 16:20:06] "POST / HTTP/1.1" 200 -


## /root/FIL/strategy/similarity/log.txt ----- -----


--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=21770 

self.closeSec=1697095799, self.tradeDate='20231012', self.openTime='152000', self.closeTime='152959', self.symbol='BTCUSDT', self.open='26815.1', self.close='26817.3'
127.0.0.1 - - [12/Oct/2023 15:30:01] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [12/Oct/2023 15:40:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=21771 

self.closeSec=1697096399, self.tradeDate='20231012', self.openTime='153000', self.closeTime='153959', self.symbol='BTCUSDT', self.open='26817.3', self.close='26819.1'

--handleKline--: 127.0.0.1 - - [12/Oct/2023 15:50:01] "POST / HTTP/1.1" 200 -
 self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=21772 

self.closeSec=1697096999, self.tradeDate='20231012', self.openTime='154000', self.closeTime='154959', self.symbol='BTCUSDT', self.open='26819.3', self.close='26819.1'

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=21773 

self.closeSec=1697097599, self.tradeDate='20231012', self.openTime='155000', self.closeTime='155959', self.symbol='BTCUSDT', self.open='26820.4', self.close='26799.3'
127.0.0.1 - - [12/Oct/2023 16:00:01] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [12/Oct/2023 16:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=21774 

self.closeSec=1697098199, self.tradeDate='20231012', self.openTime='160000', self.closeTime='160959', self.symbol='BTCUSDT', self.open='26799.3', self.close='26777.9'

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=21775 

self.closeSec=1697098799, self.tradeDate='20231012', self.openTime='161000', self.closeTime='161959', self.symbol='BTCUSDT', self.open='26777.9', self.close='26782.5'
127.0.0.1 - - [12/Oct/2023 16:20:06] "POST / HTTP/1.1" 200 -


## /root/FIL/strategy/sr_min/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=1, self.total=996015.990996, self.flagDict['side']='buy', self.tradeCount=1, self.count=43540
self.closeSec=1697098799, self.tradeDate='20231012', self.openTime='161500', self.closeTime='161959', self.symbol='BTCUSDT', self.open=26769.3, self.close=26782.6, self.high=26789.0, self.low=26757.2, self.vol=532.865, self.amt=14267416.1671 
127.0.0.1 - - [12/Oct/2023 16:20:05] "POST / HTTP/1.1" 200 -
2023-10-12 16:20:08,276:INFO:sr_min:main.py:172:handleKline:2219263: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5951  20231012   155500    155959  ...         0.0        0.0       0
5952  20231012   160000    160459  ...         0.0        0.0       0
5953  20231012   160500    160959  ...         0.0        0.0       0
5954  20231012   161000    161459  ...         0.0        0.0       0
5955  20231012   161500    161959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-10-12 16:20:08,285:INFO:sr_min:main.py:175:handleKline:2219263: self.closeSec=1697098799, self.tradeDate='20231012', self.openTime='161500', self.closeTime='161959',self.symbol='BTCUSDT',self.open=26769.3, self.close=26782.6, self.high=26789.0, self.low=26757.2, self.vol=532.865, self.amt=14267416.1671, ukdf['pct'].iloc[-1]=0.000456 , ukdf['amount'].iloc[-1]=14267416.1671, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5955, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '37.141', 'enterprice': '26844', 'countrevence': '0', 'unrealprofit': '-2183.44136678707', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '26785.21210073', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=1
--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=1, self.total=996015.990996, self.flagDict['side']='buy', self.tradeCount=1, self.count=43541
self.closeSec=1697099099, self.tradeDate='20231012', self.openTime='162000', self.closeTime='162459', self.symbol='BTCUSDT', self.open=26782.5, self.close=26779.4, self.high=26788.4, self.low=26765.0, self.vol=854.734, self.amt=22889312.9303 
127.0.0.1 - - [12/Oct/2023 16:25:01] "POST / HTTP/1.1" 200 -
2023-10-12 16:25:03,139:INFO:sr_min:main.py:172:handleKline:2219263: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5952  20231012   160000    160459  ...         0.0        0.0       0
5953  20231012   160500    160959  ...         0.0        0.0       0
5954  20231012   161000    161459  ...         0.0        0.0       0
5955  20231012   161500    161959  ...         0.0        0.0       0
5956  20231012   162000    162459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-10-12 16:25:03,148:INFO:sr_min:main.py:175:handleKline:2219263: self.closeSec=1697099099, self.tradeDate='20231012', self.openTime='162000', self.closeTime='162459',self.symbol='BTCUSDT',self.open=26782.5, self.close=26779.4, self.high=26788.4, self.low=26765.0, self.vol=854.734, self.amt=22889312.9303, ukdf['pct'].iloc[-1]=-0.000119 , ukdf['amount'].iloc[-1]=22889312.9303, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5956, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '37.141', 'enterprice': '26844', 'countrevence': '0', 'unrealprofit': '-2422.61791053334', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '26778.77241026', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=1


## /root/FIL/strategy/s_rsrs/log.txt ----- -----

721  20231012   040000    075959  1697068799  ...    721  0.642365  0.364240     NaN
722  20231012   080000    115959  1697083199  ...    722  0.691669  0.487152     NaN

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '43.597', 'enterprice': '27944.4', 'countrevence': '0', 'unrealprofit': '48318.5551', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '26836.1', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-9223372036854775808, self.sign=-1
127.0.0.1 - - [12/Oct/2023 16:00:01] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='s_rsrs', self.symbol='BTCUSDT', interval='4h', intervalSec=14400, wid=25, thd=0.6, self.sign=-1, self.total=1217073.7147932001, self.flagDict['side']='sell', self.tradeCount=32, self.count=907
self.closeSec=1697097599, self.tradeDate='20231012', self.openTime='120000', self.closeTime='155959', self.symbol='BTCUSDT', self.open=26836.0, self.close=26799.3, self.high=26909.9, self.low=26768.8, self.vol=22534.866, self.amt=604747081.2045 
2023-10-12 16:00:01,557:INFO:s_rsrs:main.py:141:handleKline:2218689: self.closeSec=1697097599, self.tradeDate='20231012', self.openTime='120000', self.closeTime='155959',self.symbol='BTCUSDT',self.open=26836.0, self.close=26799.3, self.high=26909.9, self.low=26768.8, self.vol=22534.866, self.amt=604747081.2045 
2023-10-12 16:00:01,573:INFO:s_rsrs:main.py:142:handleKline:2218689: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime  ...        vol           amt       pct
719  20231011   200000    235959  ...  99764.109  2.690309e+09 -0.015262
720  20231012   000000    035959  ...  92108.235  2.456312e+09 -0.000609
721  20231012   040000    075959  ...  28736.228  7.690963e+08  0.004209
722  20231012   080000    115959  ...  30667.851  8.226242e+08 -0.001128
723  20231012   120000    155959  ...  22534.866  6.047471e+08 -0.001368

[5 rows x 11 columns]
2023-10-12 16:00:02,360:INFO:s_rsrs:main.py:151:handleKline:2218689: df_s.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec  ...  index      beta    zscore  signal
719  20231011   200000    235959  1697039999  ...    719  0.473472 -0.077798     NaN
720  20231012   000000    035959  1697054399  ...    720  0.577880  0.198424     NaN
721  20231012   040000    075959  1697068799  ...    721  0.642365  0.364240     NaN
722  20231012   080000    115959  1697083199  ...    722  0.691669  0.487152     NaN
723  20231012   120000    155959  1697097599  ...    723  0.732357  0.584987     NaN

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '43.597', 'enterprice': '27944.4', 'countrevence': '0', 'unrealprofit': '49922.9247', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '26799.3', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-9223372036854775808, self.sign=-1


