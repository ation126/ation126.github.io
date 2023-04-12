# 20230412 08:26:01

## /root/FIL/strategy/amihud/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=993672.4896432, self.flagDict['side']='sell', self.tradeCount=2, self.count=39093
self.closeSec=1681258799, self.tradeDate='20230412', self.openTime='081500', self.closeTime='081959', self.symbol='BTCUSDT', self.open=30250.5, self.close=30235.0, self.high=30253.7, self.low=30235.0, self.vol=683.652, self.amt=20674231.4709 
127.0.0.1 - - [12/Apr/2023 08:20:04] "POST / HTTP/1.1" 200 -
2023-04-12 08:20:07,035:INFO:amihud:main.py:172:handleKline:200676: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5848  20230412   075500    075959  ...         0.0        0.0       0
5849  20230412   080000    080459  ...         0.0        0.0       0
5850  20230412   080500    080959  ...         0.0        0.0       0
5851  20230412   081000    081459  ...         0.0        0.0       0
5852  20230412   081500    081959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-04-12 08:20:07,049:INFO:amihud:main.py:175:handleKline:200676: self.closeSec=1681258799, self.tradeDate='20230412', self.openTime='081500', self.closeTime='081959',self.symbol='BTCUSDT',self.open=30250.5, self.close=30235.0, self.high=30253.7, self.low=30235.0, self.vol=683.652, self.amt=20674231.4709, ukdf['pct'].iloc[-1]=-0.000509 , ukdf['amount'].iloc[-1]=20674231.4709, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5852, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '60.176', 'enterprice': '16529.3', 'countrevence': '0', 'unrealprofit': '-824886.91253235792', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '30237.20535317', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1
127.0.0.1 - - [12/Apr/2023 08:25:01] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=993672.4896432, self.flagDict['side']='sell', self.tradeCount=2, self.count=39094
self.closeSec=1681259099, self.tradeDate='20230412', self.openTime='082000', self.closeTime='082459', self.symbol='BTCUSDT', self.open=30235.0, self.close=30296.9, self.high=30350.0, self.low=30223.2, self.vol=4193.226, self.amt=127032541.41768 
2023-04-12 08:25:01,646:INFO:amihud:main.py:172:handleKline:200676: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5849  20230412   080000    080459  ...         0.0        0.0       0
5850  20230412   080500    080959  ...         0.0        0.0       0
5851  20230412   081000    081459  ...         0.0        0.0       0
5852  20230412   081500    081959  ...         0.0        0.0       0
5853  20230412   082000    082459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-04-12 08:25:01,647:INFO:amihud:main.py:175:handleKline:200676: self.closeSec=1681259099, self.tradeDate='20230412', self.openTime='082000', self.closeTime='082459',self.symbol='BTCUSDT',self.open=30235.0, self.close=30296.9, self.high=30350.0, self.low=30223.2, self.vol=4193.226, self.amt=127032541.41768, ukdf['pct'].iloc[-1]=0.002047 , ukdf['amount'].iloc[-1]=127032541.41768, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5853, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '60.176', 'enterprice': '16529.3', 'countrevence': '0', 'unrealprofit': '-828633.41728031072', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '30299.46447222', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1


## /root/FIL/strategy/factorcheck/log.txt ----- -----


--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=23, self.factor=0.43541661550691446, self.count=39655 

self.closeSec=1681257599, self.tradeDate='20230412', self.openTime='075500', self.closeTime='075959', self.symbol='BTCUSDT', self.open=30217.0, self.close=30185.0, self.high=30217.1, self.low=30185.0 
127.0.0.1 - - [12/Apr/2023 08:00:01] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=23, self.factor=0.43541661550691446, self.count=39656 

self.closeSec=1681257899, self.tradeDate='20230412', self.openTime='080000', self.closeTime='080459', self.symbol='BTCUSDT', self.open=30185.1, self.close=30236.5, self.high=30254.0, self.low=30185.0 
127.0.0.1 - - [12/Apr/2023 08:05:01] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [12/Apr/2023 08:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=23, self.factor=0.43541661550691446, self.count=39657 

self.closeSec=1681258199, self.tradeDate='20230412', self.openTime='080500', self.closeTime='080959', self.symbol='BTCUSDT', self.open=30236.5, self.close=30237.7, self.high=30248.5, self.low=30231.6 

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=23, self.factor=0.43541661550691446, self.count=39658 

self.closeSec=1681258499, self.tradeDate='20230412', self.openTime='081000', self.closeTime='081459', self.symbol='BTCUSDT', self.open=30237.6, self.close=30250.4, self.high=30250.5, self.low=30229.5 
127.0.0.1 - - [12/Apr/2023 08:15:01] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=23, self.factor=0.43541661550691446, self.count=39659 

self.closeSec=1681258799, self.tradeDate='20230412', self.openTime='081500', self.closeTime='081959', self.symbol='BTCUSDT', self.open=30250.5, self.close=30235.0, self.high=30253.7, self.low=30235.0 
127.0.0.1 - - [12/Apr/2023 08:20:03] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [12/Apr/2023 08:25:01] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=23, self.factor=0.43541661550691446, self.count=39660 

self.closeSec=1681259099, self.tradeDate='20230412', self.openTime='082000', self.closeTime='082459', self.symbol='BTCUSDT', self.open=30235.0, self.close=30296.9, self.high=30350.0, self.low=30223.2 


## /root/FIL/strategy/logic/log.txt ----- -----

2023-04-12 08:00:36,475:DEBUG:logic:main.py:463:getModel:885513: df_s.iloc[-5:,:] :
          date closeTime     open  ...    alpha58   alpha67   alpha72
5769  20230412    052959  30148.5  ...  51.250000  0.613795  0.287827
5770  20230412    055959  30167.3  ...  51.250000  0.614584  0.300654
5771  20230412    062959  30174.1  ...  51.250000  0.612931  0.313348
5772  20230412    065959  30165.3  ...  51.666667  0.623000  0.318167
5773  20230412    072959  30250.9  ...  51.250000  0.609856  0.328372

[5 rows x 33 columns]
0.562962962962963
acc is : 0.562962962962963
2023-04-12 08:00:36,671:INFO:logic:main.py:468:getModel:885513: df_pred.iloc[-5:,:] :
     pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
535     1  0.481138  0.518862       1  ...  1.013791  -1.0    0.0  1.063363
536     1  0.468131  0.531869       0  ...  1.014087  -1.0    0.0  1.063053
537     1  0.482517  0.517483       1  ...  1.011209  -1.0    0.0  1.066070
538     0  0.516469  0.483531       0  ...  1.013533  -1.0    0.0  1.063620
539     1  0.478536  0.521464       1  ...  1.013408  -1.0    0.0  1.063751

[5 rows x 10 columns]
2023-04-12 08:00:36,711:INFO:logic:main.py:478:getModel:885513: df_panel.iloc[-5:,:] :
    pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
45     1  0.481091  0.518909       1  ...  0.984032  -1.0    0.0  1.063292
46     1  0.467672  0.532328       0  ...  1.014087  -1.0    0.0  1.058859
47     1  0.482510  0.517490       1  ...  1.011209  -1.0    0.0  1.065255
48     0  0.515808  0.484192       0  ...  1.013533  -1.0    0.0  1.062052
49     1  0.478536  0.521464       1  ...  1.013408  -1.0    0.0  1.063751

[5 rows x 10 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': []}


## /root/FIL/strategy/modifiedmom/log.txt ----- -----


--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=19825 

self.closeSec=1681255799, self.tradeDate='20230412', self.openTime='072000', self.closeTime='072959', self.symbol='BTCUSDT', self.open='30211.6', self.close='30181.4'
127.0.0.1 - - [12/Apr/2023 07:30:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=19826 

self.closeSec=1681256399, self.tradeDate='20230412', self.openTime='073000', self.closeTime='073959', self.symbol='BTCUSDT', self.open='30181.4', self.close='30221.7'
127.0.0.1 - - [12/Apr/2023 07:40:01] "POST / HTTP/1.1" 200 -

--handleKline--:  127.0.0.1 - - [12/Apr/2023 07:50:01] "POST / HTTP/1.1" 200 -
self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=19827 

self.closeSec=1681256999, self.tradeDate='20230412', self.openTime='074000', self.closeTime='074959', self.symbol='BTCUSDT', self.open='30221.7', self.close='30227.2'
127.0.0.1 - - [12/Apr/2023 08:00:02] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=19828 

self.closeSec=1681257599, self.tradeDate='20230412', self.openTime='075000', self.closeTime='075959', self.symbol='BTCUSDT', self.open='30227.3', self.close='30185.1'
127.0.0.1 - - [12/Apr/2023 08:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=19829 

self.closeSec=1681258199, self.tradeDate='20230412', self.openTime='080000', self.closeTime='080959', self.symbol='BTCUSDT', self.open='30185.1', self.close='30237.7'

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=19830 

self.closeSec=1681258799, self.tradeDate='20230412', self.openTime='081000', self.closeTime='081959', self.symbol='BTCUSDT', self.open='30237.6', self.close='30235'
127.0.0.1 - - [12/Apr/2023 08:20:04] "POST / HTTP/1.1" 200 -


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


--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=19826 

self.closeSec=1681255799, self.tradeDate='20230412', self.openTime='072000', self.closeTime='072959', self.symbol='BTCUSDT', self.open='30211.6', self.close='30181.4'
127.0.0.1 - - [12/Apr/2023 07:30:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=19827 

self.closeSec=1681256399, self.tradeDate='20230412', self.openTime='073000', self.closeTime='073959', self.symbol='BTCUSDT', self.open='30181.4', self.close='30221.7'
127.0.0.1 - - [12/Apr/2023 07:40:01] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [12/Apr/2023 07:50:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=19828 

self.closeSec=1681256999, self.tradeDate='20230412', self.openTime='074000', self.closeTime='074959', self.symbol='BTCUSDT', self.open='30221.7', self.close='30227.2'

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=19829 

self.closeSec=1681257599, self.tradeDate='20230412', self.openTime='075000', self.closeTime='075959', self.symbol='BTCUSDT', self.open='30227.3', self.close='30185.1'
127.0.0.1 - - [12/Apr/2023 08:00:02] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=19830 

self.closeSec=1681258199, self.tradeDate='20230412', self.openTime='080000', self.closeTime='080959', self.symbol='BTCUSDT', self.open='30185.1', self.close='30237.7'
127.0.0.1 - - [12/Apr/2023 08:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=19831 

self.closeSec=1681258799, self.tradeDate='20230412', self.openTime='081000', self.closeTime='081959', self.symbol='BTCUSDT', self.open='30237.6', self.close='30235'
127.0.0.1 - - [12/Apr/2023 08:20:05] "POST / HTTP/1.1" 200 -


## /root/FIL/strategy/similarity/log.txt ----- -----


--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=19826 

self.closeSec=1681255799, self.tradeDate='20230412', self.openTime='072000', self.closeTime='072959', self.symbol='BTCUSDT', self.open='30211.6', self.close='30181.4'
127.0.0.1 - - [12/Apr/2023 07:30:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=19827 

self.closeSec=1681256399, self.tradeDate='20230412', self.openTime='073000', self.closeTime='073959', self.symbol='BTCUSDT', self.open='30181.4', self.close='30221.7'
127.0.0.1 - - [12/Apr/2023 07:40:01] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [12/Apr/2023 07:50:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=19828 

self.closeSec=1681256999, self.tradeDate='20230412', self.openTime='074000', self.closeTime='074959', self.symbol='BTCUSDT', self.open='30221.7', self.close='30227.2'
127.0.0.1 - - [12/Apr/2023 08:00:02] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=19829 

self.closeSec=1681257599, self.tradeDate='20230412', self.openTime='075000', self.closeTime='075959', self.symbol='BTCUSDT', self.open='30227.3', self.close='30185.1'
127.0.0.1 - - [12/Apr/2023 08:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=19830 

self.closeSec=1681258199, self.tradeDate='20230412', self.openTime='080000', self.closeTime='080959', self.symbol='BTCUSDT', self.open='30185.1', self.close='30237.7'

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=19831 

self.closeSec=1681258799, self.tradeDate='20230412', self.openTime='081000', self.closeTime='081959', self.symbol='BTCUSDT', self.open='30237.6', self.close='30235'
127.0.0.1 - - [12/Apr/2023 08:20:05] "POST / HTTP/1.1" 200 -


## /root/FIL/strategy/sr_min/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=0, self.total=1000000.0, self.flagDict['side']='', self.tradeCount=0, self.count=35091
self.closeSec=1681258799, self.tradeDate='20230412', self.openTime='081500', self.closeTime='081959', self.symbol='BTCUSDT', self.open=30250.5, self.close=30235.0, self.high=30253.7, self.low=30235.0, self.vol=683.652, self.amt=20674231.4709 
127.0.0.1 - - [12/Apr/2023 08:20:04] "POST / HTTP/1.1" 200 -
2023-04-12 08:20:06,983:INFO:sr_min:main.py:172:handleKline:449472: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5848  20230412   075500    075959  ...         0.0        0.0       0
5849  20230412   080000    080459  ...         0.0        0.0       0
5850  20230412   080500    080959  ...         0.0        0.0       0
5851  20230412   081000    081459  ...         0.0        0.0       0
5852  20230412   081500    081959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-04-12 08:20:06,988:INFO:sr_min:main.py:175:handleKline:449472: self.closeSec=1681258799, self.tradeDate='20230412', self.openTime='081500', self.closeTime='081959',self.symbol='BTCUSDT',self.open=30250.5, self.close=30235.0, self.high=30253.7, self.low=30235.0, self.vol=683.652, self.amt=20674231.4709, ukdf['pct'].iloc[-1]=-0.000509 , ukdf['amount'].iloc[-1]=20674231.4709, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5852, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': []}
type(curSign)=<class 'int'>, curSign=0, self.sign=0
--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=0, self.total=1000000.0, self.flagDict['side']='', self.tradeCount=0, self.count=35092
self.closeSec=1681259099, self.tradeDate='20230412', self.openTime='082000', self.closeTime='082459', self.symbol='BTCUSDT', self.open=30235.0, self.close=30296.9, self.high=30350.0, self.low=30223.2, self.vol=4193.226, self.amt=127032541.41768 
127.0.0.1 - - [12/Apr/2023 08:25:01] "POST / HTTP/1.1" 200 -
2023-04-12 08:25:01,633:INFO:sr_min:main.py:172:handleKline:449472: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5849  20230412   080000    080459  ...         0.0        0.0       0
5850  20230412   080500    080959  ...         0.0        0.0       0
5851  20230412   081000    081459  ...         0.0        0.0       0
5852  20230412   081500    081959  ...         0.0        0.0       0
5853  20230412   082000    082459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-04-12 08:25:01,636:INFO:sr_min:main.py:175:handleKline:449472: self.closeSec=1681259099, self.tradeDate='20230412', self.openTime='082000', self.closeTime='082459',self.symbol='BTCUSDT',self.open=30235.0, self.close=30296.9, self.high=30350.0, self.low=30223.2, self.vol=4193.226, self.amt=127032541.41768, ukdf['pct'].iloc[-1]=0.002047 , ukdf['amount'].iloc[-1]=127032541.41768, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5853, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': []}
type(curSign)=<class 'int'>, curSign=0, self.sign=0


## /root/FIL/strategy/s_rsrs/log.txt ----- -----

719  20230411   200000    235959  1681228799  ...    719  1.237339  2.179330     1.0
720  20230412   000000    035959  1681243199  ...    720  1.246563  2.120049     1.0

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '52.515', 'enterprice': '28269.9', 'countrevence': '0', 'unrealprofit': '96927.93345462345', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '30115.61900323', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=1, self.sign=1
--handleKline--:  version='2.0.0', self.name='s_rsrs', self.symbol='BTCUSDT', interval='4h', intervalSec=14400, wid=25, thd=0.6, self.sign=1, self.total=1483109.2047015, self.flagDict['side']='buy', self.tradeCount=30, self.count=826
self.closeSec=1681257599, self.tradeDate='20230412', self.openTime='040000', self.closeTime='075959', self.symbol='BTCUSDT', self.open=30122.0, self.close=30185.1, self.high=30269.9, self.low=29896.0, self.vol=67110.773, self.amt=2021570619.11025 
127.0.0.1 - - [12/Apr/2023 08:00:01] "POST / HTTP/1.1" 200 -
2023-04-12 08:00:01,922:INFO:s_rsrs:main.py:141:handleKline:185271: self.closeSec=1681257599, self.tradeDate='20230412', self.openTime='040000', self.closeTime='075959',self.symbol='BTCUSDT',self.open=30122.0, self.close=30185.1, self.high=30269.9, self.low=29896.0, self.vol=67110.773, self.amt=2021570619.11025 
2023-04-12 08:00:01,978:INFO:s_rsrs:main.py:142:handleKline:185271: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime  ...         vol           amt       pct
717  20230411   120000    155959  ...   75212.768  2.258270e+09 -0.000349
718  20230411   160000    195959  ...   53203.501  1.599732e+09 -0.001671
719  20230411   200000    235959  ...  117522.262  3.540364e+09  0.004473
720  20230412   000000    035959  ...  112939.472  3.416080e+09 -0.001905
721  20230412   040000    075959  ...   67110.773  2.021571e+09  0.002098

[5 rows x 11 columns]
2023-04-12 08:00:05,007:INFO:s_rsrs:main.py:151:handleKline:185271: df_s.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec  ...  index      beta    zscore  signal
717  20230411   120000    155959  1681199999  ...    717  1.576662  3.292181     1.0
718  20230411   160000    195959  1681214399  ...    718  1.306424  2.446208     1.0
719  20230411   200000    235959  1681228799  ...    719  1.237339  2.179330     1.0
720  20230412   000000    035959  1681243199  ...    720  1.246563  2.120049     1.0
721  20230412   040000    075959  1681257599  ...    721  1.211553  1.963309     1.0

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '52.515', 'enterprice': '28269.9', 'countrevence': '0', 'unrealprofit': '100704.2202493524', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '30187.52773016', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=1, self.sign=1


