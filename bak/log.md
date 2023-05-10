# 20230510 16:26:01

## /root/FIL/strategy/amihud/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=993672.4896432, self.flagDict['side']='sell', self.tradeCount=2, self.count=47253
self.closeSec=1683706799, self.tradeDate='20230510', self.openTime='161500', self.closeTime='161959', self.symbol='BTCUSDT', self.open=27553.8, self.close=27574.0, self.high=27585.0, self.low=27548.0, self.vol=1927.872, self.amt=53148666.9047 
127.0.0.1 - - [10/May/2023 16:20:02] "POST / HTTP/1.1" 200 -
2023-05-10 16:20:06,007:INFO:amihud:main.py:172:handleKline:200676: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5951  20230510   155500    155959  ...         0.0        0.0       0
5952  20230510   160000    160459  ...         0.0        0.0       0
5953  20230510   160500    160959  ...         0.0        0.0       0
5954  20230510   161000    161459  ...         0.0        0.0       0
5955  20230510   161500    161959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-05-10 16:20:06,013:INFO:amihud:main.py:175:handleKline:200676: self.closeSec=1683706799, self.tradeDate='20230510', self.openTime='161500', self.closeTime='161959',self.symbol='BTCUSDT',self.open=27553.8, self.close=27574.0, self.high=27585.0, self.low=27548.0, self.vol=1927.872, self.amt=53148666.9047, ukdf['pct'].iloc[-1]=0.000737 , ukdf['amount'].iloc[-1]=53148666.9047, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5955, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '60.176', 'enterprice': '16529.3', 'countrevence': '0', 'unrealprofit': '-664818.6118095784', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '27577.20301465', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1
127.0.0.1 - - [10/May/2023 16:25:02] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=993672.4896432, self.flagDict['side']='sell', self.tradeCount=2, self.count=47254
self.closeSec=1683707099, self.tradeDate='20230510', self.openTime='162000', self.closeTime='162459', self.symbol='BTCUSDT', self.open=27574.0, self.close=27547.2, self.high=27574.1, self.low=27542.2, self.vol=694.856, self.amt=19148356.9471 
2023-05-10 16:25:02,158:INFO:amihud:main.py:172:handleKline:200676: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5952  20230510   160000    160459  ...         0.0        0.0       0
5953  20230510   160500    160959  ...         0.0        0.0       0
5954  20230510   161000    161459  ...         0.0        0.0       0
5955  20230510   161500    161959  ...         0.0        0.0       0
5956  20230510   162000    162459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-05-10 16:25:02,158:INFO:amihud:main.py:175:handleKline:200676: self.closeSec=1683707099, self.tradeDate='20230510', self.openTime='162000', self.closeTime='162459',self.symbol='BTCUSDT',self.open=27574.0, self.close=27547.2, self.high=27574.1, self.low=27542.2, self.vol=694.856, self.amt=19148356.9471, ukdf['pct'].iloc[-1]=-0.000972 , ukdf['amount'].iloc[-1]=19148356.9471, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5956, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '60.176', 'enterprice': '16529.3', 'countrevence': '0', 'unrealprofit': '-663007.1328', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '27547.1', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1


## /root/FIL/strategy/factorcheck/log.txt ----- -----

127.0.0.1 - - [10/May/2023 16:00:02] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=23, self.factor=0.43541661550691446, self.count=47815 

self.closeSec=1683705599, self.tradeDate='20230510', self.openTime='155500', self.closeTime='155959', self.symbol='BTCUSDT', self.open=27553.3, self.close=27532.4, self.high=27554.9, self.low=27525.5 

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=23, self.factor=0.43541661550691446, self.count=47816 

self.closeSec=1683705899, self.tradeDate='20230510', self.openTime='160000', self.closeTime='160459', self.symbol='BTCUSDT', self.open=27532.3, self.close=27521.7, self.high=27543.7, self.low=27521.7 
127.0.0.1 - - [10/May/2023 16:05:02] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=23, self.factor=0.43541661550691446, self.count=47817 

self.closeSec=1683706199, self.tradeDate='20230510', self.openTime='160500', self.closeTime='160959', self.symbol='BTCUSDT', self.open=27521.7, self.close=27530.0, self.high=27532.4, self.low=27457.8 
127.0.0.1 - - [10/May/2023 16:10:02] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=23, self.factor=0.43541661550691446, self.count=47818 

self.closeSec=1683706499, self.tradeDate='20230510', self.openTime='161000', self.closeTime='161459', self.symbol='BTCUSDT', self.open=27530.0, self.close=27553.7, self.high=27558.0, self.low=27515.5 
127.0.0.1 - - [10/May/2023 16:15:03] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=23, self.factor=0.43541661550691446, self.count=47819 

self.closeSec=1683706799, self.tradeDate='20230510', self.openTime='161500', self.closeTime='161959', self.symbol='BTCUSDT', self.open=27553.8, self.close=27574.0, self.high=27585.0, self.low=27548.0 
127.0.0.1 - - [10/May/2023 16:20:02] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=23, self.factor=0.43541661550691446, self.count=47820 

self.closeSec=1683707099, self.tradeDate='20230510', self.openTime='162000', self.closeTime='162459', self.symbol='BTCUSDT', self.open=27574.0, self.close=27547.2, self.high=27574.1, self.low=27542.2 
127.0.0.1 - - [10/May/2023 16:25:02] "POST / HTTP/1.1" 200 -


## /root/FIL/strategy/logic/log.txt ----- -----

2023-05-10 16:00:21,827:DEBUG:logic:main.py:463:getModel:885513: df_s.iloc[-5:,:] :
          date closeTime     open  ...    alpha58   alpha67   alpha72
5785  20230510    132959  27673.6  ...  47.916667  0.472078  0.383250
5786  20230510    135959  27662.3  ...  47.916667  0.469152  0.383093
5787  20230510    142959  27646.1  ...  47.916667  0.460329  0.389138
5788  20230510    145959  27596.8  ...  48.333333  0.463808  0.392687
5789  20230510    152959  27613.4  ...  48.333333  0.448698  0.406716

[5 rows x 33 columns]
0.5461254612546126
acc is : 0.5461254612546126
2023-05-10 16:00:21,906:INFO:logic:main.py:468:getModel:885513: df_pred.iloc[-5:,:] :
     pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
537     1  0.495577  0.504423       0  ...  1.014451   1.0    0.0  0.945101
538     1  0.493966  0.506034       0  ...  1.012639   1.0    0.0  0.943412
539     1  0.483051  0.516949       1  ...  1.013251   1.0    0.0  0.943983
540     1  0.496099  0.503901       0  ...  1.010114   1.0    0.0  0.941060
541     1  0.471649  0.528351       1  ...  1.010279   1.0    0.0  0.941214

[5 rows x 10 columns]
2023-05-10 16:00:21,918:INFO:logic:main.py:478:getModel:885513: df_panel.iloc[-5:,:] :
    pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
45     1  0.495098  0.504902       0  ...  1.028394   1.0    0.0  0.942675
46     1  0.493710  0.506290       0  ...  1.012639   1.0    0.0  0.942230
47     1  0.482589  0.517411       1  ...  1.027178   1.0    0.0  0.942437
48     1  0.495864  0.504136       0  ...  1.010114   1.0    0.0  0.939705
49     1  0.471649  0.528351       1  ...  1.010279   1.0    0.0  0.941214

[5 rows x 10 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': []}


## /root/FIL/strategy/modifiedmom/log.txt ----- -----


--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=23905 

self.closeSec=1683703799, self.tradeDate='20230510', self.openTime='152000', self.closeTime='152959', self.symbol='BTCUSDT', self.open='27597', self.close='27527.9'
127.0.0.1 - - [10/May/2023 15:30:03] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=23906 

self.closeSec=1683704399, self.tradeDate='20230510', self.openTime='153000', self.closeTime='153959', self.symbol='BTCUSDT', self.open='27528', self.close='27539.8'
127.0.0.1 - - [10/May/2023 15:40:02] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [10/May/2023 15:50:02] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=23907 

self.closeSec=1683704999, self.tradeDate='20230510', self.openTime='154000', self.closeTime='154959', self.symbol='BTCUSDT', self.open='27539.7', self.close='27561.1'

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=23908 

self.closeSec=1683705599, self.tradeDate='20230510', self.openTime='155000', self.closeTime='155959', self.symbol='BTCUSDT', self.open='27561.1', self.close='27532.4'
127.0.0.1 - - [10/May/2023 16:00:03] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [10/May/2023 16:10:02] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=23909 

self.closeSec=1683706199, self.tradeDate='20230510', self.openTime='160000', self.closeTime='160959', self.symbol='BTCUSDT', self.open='27532.3', self.close='27530'

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=23910 

self.closeSec=1683706799, self.tradeDate='20230510', self.openTime='161000', self.closeTime='161959', self.symbol='BTCUSDT', self.open='27530', self.close='27574'
127.0.0.1 - - [10/May/2023 16:20:05] "POST / HTTP/1.1" 200 -


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


--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=23906 

self.closeSec=1683703799, self.tradeDate='20230510', self.openTime='152000', self.closeTime='152959', self.symbol='BTCUSDT', self.open='27597', self.close='27527.9'
127.0.0.1 - - [10/May/2023 15:30:03] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [10/May/2023 15:40:02] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=23907 

self.closeSec=1683704399, self.tradeDate='20230510', self.openTime='153000', self.closeTime='153959', self.symbol='BTCUSDT', self.open='27528', self.close='27539.8'
127.0.0.1 - - [10/May/2023 15:50:02] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=23908 

self.closeSec=1683704999, self.tradeDate='20230510', self.openTime='154000', self.closeTime='154959', self.symbol='BTCUSDT', self.open='27539.7', self.close='27561.1'
127.0.0.1 - - [10/May/2023 16:00:03] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=23909 

self.closeSec=1683705599, self.tradeDate='20230510', self.openTime='155000', self.closeTime='155959', self.symbol='BTCUSDT', self.open='27561.1', self.close='27532.4'
127.0.0.1 - - [10/May/2023 16:10:02] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=23910 

self.closeSec=1683706199, self.tradeDate='20230510', self.openTime='160000', self.closeTime='160959', self.symbol='BTCUSDT', self.open='27532.3', self.close='27530'

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=23911 

self.closeSec=1683706799, self.tradeDate='20230510', self.openTime='161000', self.closeTime='161959', self.symbol='BTCUSDT', self.open='27530', self.close='27574'
127.0.0.1 - - [10/May/2023 16:20:05] "POST / HTTP/1.1" 200 -


## /root/FIL/strategy/similarity/log.txt ----- -----


--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=23906 

self.closeSec=1683703799, self.tradeDate='20230510', self.openTime='152000', self.closeTime='152959', self.symbol='BTCUSDT', self.open='27597', self.close='27527.9'
127.0.0.1 - - [10/May/2023 15:30:03] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=23907 

self.closeSec=1683704399, self.tradeDate='20230510', self.openTime='153000', self.closeTime='153959', self.symbol='BTCUSDT', self.open='27528', self.close='27539.8'
127.0.0.1 - - [10/May/2023 15:40:02] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [10/May/2023 15:50:02] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=23908 

self.closeSec=1683704999, self.tradeDate='20230510', self.openTime='154000', self.closeTime='154959', self.symbol='BTCUSDT', self.open='27539.7', self.close='27561.1'

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=23909 

self.closeSec=1683705599, self.tradeDate='20230510', self.openTime='155000', self.closeTime='155959', self.symbol='BTCUSDT', self.open='27561.1', self.close='27532.4'
127.0.0.1 - - [10/May/2023 16:00:03] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=23910 

self.closeSec=1683706199, self.tradeDate='20230510', self.openTime='160000', self.closeTime='160959', self.symbol='BTCUSDT', self.open='27532.3', self.close='27530'
127.0.0.1 - - [10/May/2023 16:10:02] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=23911 

self.closeSec=1683706799, self.tradeDate='20230510', self.openTime='161000', self.closeTime='161959', self.symbol='BTCUSDT', self.open='27530', self.close='27574'
127.0.0.1 - - [10/May/2023 16:20:05] "POST / HTTP/1.1" 200 -


## /root/FIL/strategy/sr_min/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=0, self.total=1000000.0, self.flagDict['side']='', self.tradeCount=0, self.count=43251
self.closeSec=1683706799, self.tradeDate='20230510', self.openTime='161500', self.closeTime='161959', self.symbol='BTCUSDT', self.open=27553.8, self.close=27574.0, self.high=27585.0, self.low=27548.0, self.vol=1927.872, self.amt=53148666.9047 
127.0.0.1 - - [10/May/2023 16:20:02] "POST / HTTP/1.1" 200 -
2023-05-10 16:20:06,005:INFO:sr_min:main.py:172:handleKline:449472: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5951  20230510   155500    155959  ...         0.0        0.0       0
5952  20230510   160000    160459  ...         0.0        0.0       0
5953  20230510   160500    160959  ...         0.0        0.0       0
5954  20230510   161000    161459  ...         0.0        0.0       0
5955  20230510   161500    161959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-05-10 16:20:06,009:INFO:sr_min:main.py:175:handleKline:449472: self.closeSec=1683706799, self.tradeDate='20230510', self.openTime='161500', self.closeTime='161959',self.symbol='BTCUSDT',self.open=27553.8, self.close=27574.0, self.high=27585.0, self.low=27548.0, self.vol=1927.872, self.amt=53148666.9047, ukdf['pct'].iloc[-1]=0.000737 , ukdf['amount'].iloc[-1]=53148666.9047, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5955, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': []}
type(curSign)=<class 'int'>, curSign=0, self.sign=0
127.0.0.1 - - [10/May/2023 16:25:02] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=0, self.total=1000000.0, self.flagDict['side']='', self.tradeCount=0, self.count=43252
self.closeSec=1683707099, self.tradeDate='20230510', self.openTime='162000', self.closeTime='162459', self.symbol='BTCUSDT', self.open=27574.0, self.close=27547.2, self.high=27574.1, self.low=27542.2, self.vol=694.856, self.amt=19148356.9471 
2023-05-10 16:25:02,099:INFO:sr_min:main.py:172:handleKline:449472: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5952  20230510   160000    160459  ...         0.0        0.0       0
5953  20230510   160500    160959  ...         0.0        0.0       0
5954  20230510   161000    161459  ...         0.0        0.0       0
5955  20230510   161500    161959  ...         0.0        0.0       0
5956  20230510   162000    162459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-05-10 16:25:02,100:INFO:sr_min:main.py:175:handleKline:449472: self.closeSec=1683707099, self.tradeDate='20230510', self.openTime='162000', self.closeTime='162459',self.symbol='BTCUSDT',self.open=27574.0, self.close=27547.2, self.high=27574.1, self.low=27542.2, self.vol=694.856, self.amt=19148356.9471, ukdf['pct'].iloc[-1]=-0.000972 , ukdf['amount'].iloc[-1]=19148356.9471, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5956, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': []}
type(curSign)=<class 'int'>, curSign=0, self.sign=0


## /root/FIL/strategy/s_rsrs/log.txt ----- -----

721  20230510   040000    075959  1683676799  ...    721  0.831298  1.080613     1.0
722  20230510   080000    115959  1683691199  ...    722  0.860986  1.164174     1.0

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '52.501', 'enterprice': '27610.1', 'countrevence': '0', 'unrealprofit': '3134.71805172798', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '27669.80777798', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=1, self.sign=1
--handleKline--:  version='2.0.0', self.name='s_rsrs', self.symbol='BTCUSDT', interval='4h', intervalSec=14400, wid=25, thd=0.6, self.sign=1, self.total=1448108.3022399, self.flagDict['side']='buy', self.tradeCount=34, self.count=996
self.closeSec=1683705599, self.tradeDate='20230510', self.openTime='120000', self.closeTime='155959', self.symbol='BTCUSDT', self.open=27668.9, self.close=27532.4, self.high=27712.0, self.low=27507.0, self.vol=32310.414, self.amt=891897397.66168 
2023-05-10 16:00:03,150:INFO:s_rsrs:main.py:141:handleKline:185271: self.closeSec=1683705599, self.tradeDate='20230510', self.openTime='120000', self.closeTime='155959',self.symbol='BTCUSDT',self.open=27668.9, self.close=27532.4, self.high=27712.0, self.low=27507.0, self.vol=32310.414, self.amt=891897397.66168 
127.0.0.1 - - [10/May/2023 16:00:03] "POST / HTTP/1.1" 200 -
2023-05-10 16:00:03,191:INFO:s_rsrs:main.py:142:handleKline:185271: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime  ...         vol           amt       pct
719  20230509   200000    235959  ...  119288.926  3.290036e+09 -0.010053
720  20230510   000000    035959  ...   78744.119  2.170562e+09  0.011645
721  20230510   040000    075959  ...   33703.303  9.309797e+08 -0.003411
722  20230510   080000    115959  ...   47318.156  1.311215e+09  0.002122
723  20230510   120000    155959  ...   32310.414  8.918974e+08 -0.004930

[5 rows x 11 columns]
2023-05-10 16:00:05,365:INFO:s_rsrs:main.py:151:handleKline:185271: df_s.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec  ...  index      beta    zscore  signal
719  20230509   200000    235959  1683647999  ...    719  0.826353  1.084247     1.0
720  20230510   000000    035959  1683662399  ...    720  0.828544  1.085154     1.0
721  20230510   040000    075959  1683676799  ...    721  0.831298  1.080613     1.0
722  20230510   080000    115959  1683691199  ...    722  0.860986  1.164174     1.0
723  20230510   120000    155959  1683705599  ...    723  0.834112  1.055339     1.0

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '52.501', 'enterprice': '27610.1', 'countrevence': '0', 'unrealprofit': '-4079.3277', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '27532.4', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=1, self.sign=1


