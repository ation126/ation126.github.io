# 20230829 16:26:01

## /root/FIL/strategy/amihud/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=373746.4768026, self.flagDict['side']='sell', self.tradeCount=2, self.count=30868
self.closeSec=1693297199, self.tradeDate='20230829', self.openTime='161500', self.closeTime='161959', self.symbol='BTCUSDT', self.open=25983.5, self.close=25990.1, self.high=25992.8, self.low=25971.9, self.vol=450.61, self.amt=11707844.9885 
127.0.0.1 - - [29/Aug/2023 16:20:01] "POST / HTTP/1.1" 200 -
2023-08-29 16:20:05,066:INFO:amihud:main.py:172:handleKline:2219019: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5939  20230829   155500    155959  ...         0.0        0.0       0
5940  20230829   160000    160459  ...         0.0        0.0       0
5941  20230829   160500    160959  ...         0.0        0.0       0
5942  20230829   161000    161459  ...         0.0        0.0       0
5943  20230829   161500    161959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-08-29 16:20:05,076:INFO:amihud:main.py:175:handleKline:2219019: self.closeSec=1693297199, self.tradeDate='20230829', self.openTime='161500', self.closeTime='161959',self.symbol='BTCUSDT',self.open=25983.5, self.close=25990.1, self.high=25992.8, self.low=25971.9, self.vol=450.61, self.amt=11707844.9885, ukdf['pct'].iloc[-1]=0.000231 , ukdf['amount'].iloc[-1]=11707844.9885, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5943, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '13.926', 'enterprice': '26864.9', 'countrevence': '0', 'unrealprofit': '12182.4648', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '25990.1', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1
127.0.0.1 - - [29/Aug/2023 16:25:00] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=373746.4768026, self.flagDict['side']='sell', self.tradeCount=2, self.count=30869
self.closeSec=1693297499, self.tradeDate='20230829', self.openTime='162000', self.closeTime='162459', self.symbol='BTCUSDT', self.open=25990.0, self.close=25995.0, self.high=26003.6, self.low=25982.8, self.vol=573.116, self.amt=14898677.6014 
2023-08-29 16:25:00,804:INFO:amihud:main.py:172:handleKline:2219019: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5940  20230829   160000    160459  ...         0.0        0.0       0
5941  20230829   160500    160959  ...         0.0        0.0       0
5942  20230829   161000    161459  ...         0.0        0.0       0
5943  20230829   161500    161959  ...         0.0        0.0       0
5944  20230829   162000    162459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-08-29 16:25:00,805:INFO:amihud:main.py:175:handleKline:2219019: self.closeSec=1693297499, self.tradeDate='20230829', self.openTime='162000', self.closeTime='162459',self.symbol='BTCUSDT',self.open=25990.0, self.close=25995.0, self.high=26003.6, self.low=25982.8, self.vol=573.116, self.amt=14898677.6014, ukdf['pct'].iloc[-1]=0.000189 , ukdf['amount'].iloc[-1]=14898677.6014, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5944, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '13.926', 'enterprice': '26864.9', 'countrevence': '0', 'unrealprofit': '12092.17708384356', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '25996.58339194', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1


## /root/FIL/strategy/factorcheck/log.txt ----- -----


--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.714181719035411, self.count=30866 

self.closeSec=1693295999, self.tradeDate='20230829', self.openTime='155500', self.closeTime='155959', self.symbol='BTCUSDT', self.open=25981.5, self.close=25992.0, self.high=25998.2, self.low=25974.1 
127.0.0.1 - - [29/Aug/2023 16:00:00] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.714181719035411, self.count=30867 

self.closeSec=1693296299, self.tradeDate='20230829', self.openTime='160000', self.closeTime='160459', self.symbol='BTCUSDT', self.open=25992.1, self.close=25967.8, self.high=25992.1, self.low=25949.3 
127.0.0.1 - - [29/Aug/2023 16:05:00] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.714181719035411, self.count=30868 

self.closeSec=1693296599, self.tradeDate='20230829', self.openTime='160500', self.closeTime='160959', self.symbol='BTCUSDT', self.open=25967.9, self.close=25977.7, self.high=25984.8, self.low=25965.6 
127.0.0.1 - - [29/Aug/2023 16:10:00] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.714181719035411, self.count=30869 

self.closeSec=1693296899, self.tradeDate='20230829', self.openTime='161000', self.closeTime='161459', self.symbol='BTCUSDT', self.open=25977.6, self.close=25984.1, self.high=25994.2, self.low=25966.6 
127.0.0.1 - - [29/Aug/2023 16:15:00] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.714181719035411, self.count=30870 

self.closeSec=1693297199, self.tradeDate='20230829', self.openTime='161500', self.closeTime='161959', self.symbol='BTCUSDT', self.open=25983.5, self.close=25990.1, self.high=25992.8, self.low=25971.9 
127.0.0.1 - - [29/Aug/2023 16:20:01] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [29/Aug/2023 16:25:00] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.714181719035411, self.count=30871 

self.closeSec=1693297499, self.tradeDate='20230829', self.openTime='162000', self.closeTime='162459', self.symbol='BTCUSDT', self.open=25990.0, self.close=25995.0, self.high=26003.6, self.low=25982.8 


## /root/FIL/strategy/logic/log.txt ----- -----

2023-08-29 16:00:17,141:DEBUG:logic:main.py:463:getModel:2218526: df_s.iloc[-5:,:] :
          date closeTime     open  ...    alpha58   alpha67   alpha72
5785  20230829    132959  26046.0  ...  49.166667  0.501837  0.462092
5786  20230829    135959  26057.2  ...  49.166667  0.499035  0.469036
5787  20230829    142959  26050.5  ...  48.750000  0.488292  0.480427
5788  20230829    145959  26025.5  ...  48.333333  0.477346  0.496159
5789  20230829    152959  25999.3  ...  48.333333  0.487503  0.506423

[5 rows x 33 columns]
0.5479704797047971
acc is : 0.5479704797047971
2023-08-29 16:00:17,206:INFO:logic:main.py:468:getModel:2218526: df_pred.iloc[-5:,:] :
     pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
537     1  0.491363  0.508637       0  ...  0.986642  -1.0    0.0  0.974824
538     1  0.487514  0.512486       0  ...  0.987592  -1.0    0.0  0.973884
539     1  0.481810  0.518190       0  ...  0.988586  -1.0    0.0  0.972904
540     1  0.478854  0.521146       1  ...  0.987723  -1.0    0.0  0.973753
541     1  0.495796  0.504204       0  ...  0.988862  -1.0    0.0  0.972631

[5 rows x 10 columns]
2023-08-29 16:00:17,217:INFO:logic:main.py:478:getModel:2218526: df_panel.iloc[-5:,:] :
    pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
45     1  0.490967  0.509033       0  ...  0.988040  -1.0    0.0  0.972284
46     1  0.487567  0.512433       0  ...  0.988992  -1.0    0.0  0.977491
47     1  0.482119  0.517881       0  ...  0.989419  -1.0    0.0  0.977061
48     1  0.479094  0.520906       1  ...  0.987723  -1.0    0.0  0.973885
49     1  0.495796  0.504204       0  ...  0.988862  -1.0    0.0  0.972631

[5 rows x 10 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '28.758', 'enterprice': '25982.3', 'countrevence': '0', 'unrealprofit': '-54.6402', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '25984.2', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}


## /root/FIL/strategy/modifiedmom/log.txt ----- -----


--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=15431 

self.closeSec=1693294199, self.tradeDate='20230829', self.openTime='152000', self.closeTime='152959', self.symbol='BTCUSDT', self.open='26008.2', self.close='26022'
127.0.0.1 - - [29/Aug/2023 15:30:01] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [29/Aug/2023 15:40:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=15432 

self.closeSec=1693294799, self.tradeDate='20230829', self.openTime='153000', self.closeTime='153959', self.symbol='BTCUSDT', self.open='26022', self.close='26006.1'

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=15433 

self.closeSec=1693295399, self.tradeDate='20230829', self.openTime='154000', self.closeTime='154959', self.symbol='BTCUSDT', self.open='26006', self.close='25992.5'
127.0.0.1 - - [29/Aug/2023 15:50:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=15434 

self.closeSec=1693295999, self.tradeDate='20230829', self.openTime='155000', self.closeTime='155959', self.symbol='BTCUSDT', self.open='25992.4', self.close='25992'
127.0.0.1 - - [29/Aug/2023 16:00:02] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [29/Aug/2023 16:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=15435 

self.closeSec=1693296599, self.tradeDate='20230829', self.openTime='160000', self.closeTime='160959', self.symbol='BTCUSDT', self.open='25992.1', self.close='25977.7'

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=15436 

self.closeSec=1693297199, self.tradeDate='20230829', self.openTime='161000', self.closeTime='161959', self.symbol='BTCUSDT', self.open='25977.6', self.close='25990.1'
127.0.0.1 - - [29/Aug/2023 16:20:04] "POST / HTTP/1.1" 200 -


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


--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=15434 

self.closeSec=1693294199, self.tradeDate='20230829', self.openTime='152000', self.closeTime='152959', self.symbol='BTCUSDT', self.open='26008.2', self.close='26022'
127.0.0.1 - - [29/Aug/2023 15:30:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=15435 

self.closeSec=1693294799, self.tradeDate='20230829', self.openTime='153000', self.closeTime='153959', self.symbol='BTCUSDT', self.open='26022', self.close='26006.1'
127.0.0.1 - - [29/Aug/2023 15:40:01] "POST / HTTP/1.1" 200 -

--handleKline--: 127.0.0.1 - - [29/Aug/2023 15:50:01] "POST / HTTP/1.1" 200 -
 self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=15436 

self.closeSec=1693295399, self.tradeDate='20230829', self.openTime='154000', self.closeTime='154959', self.symbol='BTCUSDT', self.open='26006', self.close='25992.5'

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=15437 

self.closeSec=1693295999, self.tradeDate='20230829', self.openTime='155000', self.closeTime='155959', self.symbol='BTCUSDT', self.open='25992.4', self.close='25992'
127.0.0.1 - - [29/Aug/2023 16:00:02] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [29/Aug/2023 16:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=15438 

self.closeSec=1693296599, self.tradeDate='20230829', self.openTime='160000', self.closeTime='160959', self.symbol='BTCUSDT', self.open='25992.1', self.close='25977.7'

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=15439 

self.closeSec=1693297199, self.tradeDate='20230829', self.openTime='161000', self.closeTime='161959', self.symbol='BTCUSDT', self.open='25977.6', self.close='25990.1'
127.0.0.1 - - [29/Aug/2023 16:20:03] "POST / HTTP/1.1" 200 -


## /root/FIL/strategy/similarity/log.txt ----- -----

127.0.0.1 - - [29/Aug/2023 15:30:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=15434 

self.closeSec=1693294199, self.tradeDate='20230829', self.openTime='152000', self.closeTime='152959', self.symbol='BTCUSDT', self.open='26008.2', self.close='26022'
127.0.0.1 - - [29/Aug/2023 15:40:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=15435 

self.closeSec=1693294799, self.tradeDate='20230829', self.openTime='153000', self.closeTime='153959', self.symbol='BTCUSDT', self.open='26022', self.close='26006.1'
127.0.0.1 - - [29/Aug/2023 15:50:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=15436 

self.closeSec=1693295399, self.tradeDate='20230829', self.openTime='154000', self.closeTime='154959', self.symbol='BTCUSDT', self.open='26006', self.close='25992.5'
127.0.0.1 - - [29/Aug/2023 16:00:02] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=15437 

self.closeSec=1693295999, self.tradeDate='20230829', self.openTime='155000', self.closeTime='155959', self.symbol='BTCUSDT', self.open='25992.4', self.close='25992'
127.0.0.1 - - [29/Aug/2023 16:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=15438 

self.closeSec=1693296599, self.tradeDate='20230829', self.openTime='160000', self.closeTime='160959', self.symbol='BTCUSDT', self.open='25992.1', self.close='25977.7'

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=15439 

self.closeSec=1693297199, self.tradeDate='20230829', self.openTime='161000', self.closeTime='161959', self.symbol='BTCUSDT', self.open='25977.6', self.close='25990.1'
127.0.0.1 - - [29/Aug/2023 16:20:04] "POST / HTTP/1.1" 200 -


## /root/FIL/strategy/sr_min/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=1, self.total=996015.990996, self.flagDict['side']='buy', self.tradeCount=1, self.count=30868
self.closeSec=1693297199, self.tradeDate='20230829', self.openTime='161500', self.closeTime='161959', self.symbol='BTCUSDT', self.open=25983.5, self.close=25990.1, self.high=25992.8, self.low=25971.9, self.vol=450.61, self.amt=11707844.9885 
127.0.0.1 - - [29/Aug/2023 16:20:01] "POST / HTTP/1.1" 200 -
2023-08-29 16:20:05,067:INFO:sr_min:main.py:172:handleKline:2219263: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5939  20230829   155500    155959  ...         0.0        0.0       0
5940  20230829   160000    160459  ...         0.0        0.0       0
5941  20230829   160500    160959  ...         0.0        0.0       0
5942  20230829   161000    161459  ...         0.0        0.0       0
5943  20230829   161500    161959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-08-29 16:20:05,079:INFO:sr_min:main.py:175:handleKline:2219263: self.closeSec=1693297199, self.tradeDate='20230829', self.openTime='161500', self.closeTime='161959',self.symbol='BTCUSDT',self.open=25983.5, self.close=25990.1, self.high=25992.8, self.low=25971.9, self.vol=450.61, self.amt=11707844.9885, ukdf['pct'].iloc[-1]=0.000231 , ukdf['amount'].iloc[-1]=11707844.9885, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5943, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '37.141', 'enterprice': '26844', 'countrevence': '0', 'unrealprofit': '-31714.6999', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '25990.1', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=1
127.0.0.1 - - [29/Aug/2023 16:25:00] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=1, self.total=996015.990996, self.flagDict['side']='buy', self.tradeCount=1, self.count=30869
self.closeSec=1693297499, self.tradeDate='20230829', self.openTime='162000', self.closeTime='162459', self.symbol='BTCUSDT', self.open=25990.0, self.close=25995.0, self.high=26003.6, self.low=25982.8, self.vol=573.116, self.amt=14898677.6014 
2023-08-29 16:25:00,804:INFO:sr_min:main.py:172:handleKline:2219263: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5940  20230829   160000    160459  ...         0.0        0.0       0
5941  20230829   160500    160959  ...         0.0        0.0       0
5942  20230829   161000    161459  ...         0.0        0.0       0
5943  20230829   161500    161959  ...         0.0        0.0       0
5944  20230829   162000    162459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-08-29 16:25:00,805:INFO:sr_min:main.py:175:handleKline:2219263: self.closeSec=1693297499, self.tradeDate='20230829', self.openTime='162000', self.closeTime='162459',self.symbol='BTCUSDT',self.open=25990.0, self.close=25995.0, self.high=26003.6, self.low=25982.8, self.vol=573.116, self.amt=14898677.6014, ukdf['pct'].iloc[-1]=0.000189 , ukdf['amount'].iloc[-1]=14898677.6014, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5944, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '37.141', 'enterprice': '26844', 'countrevence': '0', 'unrealprofit': '-31473.90023995646', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '25996.58339194', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=1


## /root/FIL/strategy/s_rsrs/log.txt ----- -----

721  20230829   040000    075959  ...  1.885711e-04 -1.110704    -1.0
722  20230829   080000    115959  ...  3.378700e-07 -1.105306    -1.0

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '51.388', 'enterprice': '29432.6', 'countrevence': '0', 'unrealprofit': '172676.83327967432', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '26072.34403986', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-1, self.sign=-1
127.0.0.1 - - [29/Aug/2023 16:00:01] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='s_rsrs', self.symbol='BTCUSDT', interval='4h', intervalSec=14400, wid=25, thd=0.6, self.sign=-1, self.total=1510969.9663512, self.flagDict['side']='sell', self.tradeCount=20, self.count=643
self.closeSec=1693295999, self.tradeDate='20230829', self.openTime='120000', self.closeTime='155959', self.symbol='BTCUSDT', self.open=26068.4, self.close=25992.0, self.high=26080.4, self.low=25974.1, self.vol=20248.279, self.amt=527029566.803 
2023-08-29 16:00:01,621:INFO:s_rsrs:main.py:141:handleKline:2218689: self.closeSec=1693295999, self.tradeDate='20230829', self.openTime='120000', self.closeTime='155959',self.symbol='BTCUSDT',self.open=26068.4, self.close=25992.0, self.high=26080.4, self.low=25974.1, self.vol=20248.279, self.amt=527029566.803 
2023-08-29 16:00:01,634:INFO:s_rsrs:main.py:142:handleKline:2218689: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime  ...        vol           amt       pct
719  20230828   200000    235959  ...  68566.281  1.790877e+09  0.003790
720  20230829   000000    035959  ...  41869.582  1.090798e+09 -0.004204
721  20230829   040000    075959  ...  25253.358  6.578352e+08  0.004807
722  20230829   080000    115959  ...  22733.617  5.936283e+08 -0.001463
723  20230829   120000    155959  ...  20248.279  5.270296e+08 -0.002927

[5 rows x 11 columns]
2023-08-29 16:00:02,357:INFO:s_rsrs:main.py:151:handleKline:2218689: df_s.iloc[-5:,:] :
    tradeDate openTime closeTime  ...          beta    zscore  signal
719  20230828   200000    235959  ...  8.892409e-06 -1.132751    -1.0
720  20230829   000000    035959  ...  3.002120e-04 -1.122435    -1.0
721  20230829   040000    075959  ...  1.885711e-04 -1.110704    -1.0
722  20230829   080000    115959  ...  3.378700e-07 -1.105306    -1.0
723  20230829   120000    155959  ...  5.307007e-06 -1.103177    -1.0

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '51.388', 'enterprice': '29432.6', 'countrevence': '0', 'unrealprofit': '176791.71192216392', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '25992.26934066', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-1, self.sign=-1


