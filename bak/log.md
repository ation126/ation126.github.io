# 20230929 08:26:01

## /root/FIL/strategy/amihud/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=373746.4768026, self.flagDict['side']='sell', self.tradeCount=2, self.count=39700
self.closeSec=1695946799, self.tradeDate='20230929', self.openTime='081500', self.closeTime='081959', self.symbol='BTCUSDT', self.open=27059.1, self.close=27084.8, self.high=27087.3, self.low=27053.2, self.vol=1262.089, self.amt=34167186.0781 
127.0.0.1 - - [29/Sep/2023 08:20:02] "POST / HTTP/1.1" 200 -
2023-09-29 08:20:06,530:INFO:amihud:main.py:172:handleKline:2219019: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5855  20230929   075500    075959  ...         0.0        0.0       0
5856  20230929   080000    080459  ...         0.0        0.0       0
5857  20230929   080500    080959  ...         0.0        0.0       0
5858  20230929   081000    081459  ...         0.0        0.0       0
5859  20230929   081500    081959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-09-29 08:20:06,538:INFO:amihud:main.py:175:handleKline:2219019: self.closeSec=1695946799, self.tradeDate='20230929', self.openTime='081500', self.closeTime='081959',self.symbol='BTCUSDT',self.open=27059.1, self.close=27084.8, self.high=27087.3, self.low=27053.2, self.vol=1262.089, self.amt=34167186.0781, ukdf['pct'].iloc[-1]=0.000965 , ukdf['amount'].iloc[-1]=34167186.0781, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5859, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '13.926', 'enterprice': '26864.9', 'countrevence': '0', 'unrealprofit': '-3021.47104106232', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '27081.86618132', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1
--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=373746.4768026, self.flagDict['side']='sell', self.tradeCount=2, self.count=39701
self.closeSec=1695947099, self.tradeDate='20230929', self.openTime='082000', self.closeTime='082459', self.symbol='BTCUSDT', self.open=27084.7, self.close=27063.2, self.high=27088.3, self.low=27054.8, self.vol=627.082, self.amt=16975135.226 
127.0.0.1 - - [29/Sep/2023 08:25:00] "POST / HTTP/1.1" 200 -
2023-09-29 08:25:00,818:INFO:amihud:main.py:172:handleKline:2219019: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5856  20230929   080000    080459  ...         0.0        0.0       0
5857  20230929   080500    080959  ...         0.0        0.0       0
5858  20230929   081000    081459  ...         0.0        0.0       0
5859  20230929   081500    081959  ...         0.0        0.0       0
5860  20230929   082000    082459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-09-29 08:25:00,818:INFO:amihud:main.py:175:handleKline:2219019: self.closeSec=1695947099, self.tradeDate='20230929', self.openTime='082000', self.closeTime='082459',self.symbol='BTCUSDT',self.open=27084.7, self.close=27063.2, self.high=27088.3, self.low=27054.8, self.vol=627.082, self.amt=16975135.226, ukdf['pct'].iloc[-1]=-0.000797 , ukdf['amount'].iloc[-1]=16975135.226, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5860, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '13.926', 'enterprice': '26864.9', 'countrevence': '0', 'unrealprofit': '-2762.13063723498', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '27063.24343223', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1


## /root/FIL/strategy/factorcheck/log.txt ----- -----

127.0.0.1 - - [29/Sep/2023 08:00:00] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.714181719035411, self.count=39698 

self.closeSec=1695945599, self.tradeDate='20230929', self.openTime='075500', self.closeTime='075959', self.symbol='BTCUSDT', self.open=27000.0, self.close=27011.8, self.high=27011.8, self.low=26994.9 
127.0.0.1 - - [29/Sep/2023 08:05:00] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.714181719035411, self.count=39699 

self.closeSec=1695945899, self.tradeDate='20230929', self.openTime='080000', self.closeTime='080459', self.symbol='BTCUSDT', self.open=27011.7, self.close=26997.3, self.high=27026.8, self.low=26997.3 

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.714181719035411, self.count=39700 

self.closeSec=1695946199, self.tradeDate='20230929', self.openTime='080500', self.closeTime='080959', self.symbol='BTCUSDT', self.open=26997.3, self.close=27048.0, self.high=27049.2, self.low=26995.8 
127.0.0.1 - - [29/Sep/2023 08:10:00] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.714181719035411, self.count=39701 

self.closeSec=1695946499, self.tradeDate='20230929', self.openTime='081000', self.closeTime='081459', self.symbol='BTCUSDT', self.open=27048.0, self.close=27058.7, self.high=27058.8, self.low=27039.4 
127.0.0.1 - - [29/Sep/2023 08:15:00] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.714181719035411, self.count=39702 

self.closeSec=1695946799, self.tradeDate='20230929', self.openTime='081500', self.closeTime='081959', self.symbol='BTCUSDT', self.open=27059.1, self.close=27084.8, self.high=27087.3, self.low=27053.2 
127.0.0.1 - - [29/Sep/2023 08:20:02] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [29/Sep/2023 08:25:00] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.714181719035411, self.count=39703 

self.closeSec=1695947099, self.tradeDate='20230929', self.openTime='082000', self.closeTime='082459', self.symbol='BTCUSDT', self.open=27084.7, self.close=27063.2, self.high=27088.3, self.low=27054.8 


## /root/FIL/strategy/logic/log.txt ----- -----

2023-09-29 08:00:22,648:DEBUG:logic:main.py:463:getModel:2218526: df_s.iloc[-5:,:] :
          date closeTime     open  ...    alpha58   alpha67   alpha72
5769  20230929    052959  27071.4  ...  51.250000  0.580886  0.281749
5770  20230929    055959  26956.6  ...  51.666667  0.585988  0.284651
5771  20230929    062959  26988.9  ...  51.666667  0.589711  0.285759
5772  20230929    065959  27012.3  ...  51.666667  0.587290  0.287511
5773  20230929    072959  27001.7  ...  51.666667  0.590527  0.287913

[5 rows x 33 columns]
0.5259259259259259
acc is : 0.5259259259259259
2023-09-29 08:00:22,718:INFO:logic:main.py:468:getModel:2218526: df_pred.iloc[-5:,:] :
     pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
535     1  0.459321  0.540679       1  ...  0.958982  -1.0    0.0  1.019769
536     1  0.497768  0.502232       1  ...  0.958144  -1.0    0.0  1.020661
537     1  0.495059  0.504941       0  ...  0.958520  -1.0    0.0  1.020260
538     1  0.482404  0.517596       1  ...  0.957810  -1.0    0.0  1.021016
539     1  0.494741  0.505259       0  ...  0.958164  -1.0    0.0  1.020638

[5 rows x 10 columns]
2023-09-29 08:00:22,731:INFO:logic:main.py:478:getModel:2218526: df_panel.iloc[-5:,:] :
    pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
45     1  0.459099  0.540901       1  ...  0.958982  -1.0    0.0  1.017025
46     1  0.497556  0.502444       1  ...  0.958144  -1.0    0.0  1.018652
47     1  0.494973  0.505027       0  ...  0.958520  -1.0    0.0  1.019194
48     1  0.482036  0.517964       1  ...  0.957810  -1.0    0.0  1.019691
49     1  0.494741  0.505259       0  ...  0.958164  -1.0    0.0  1.020638

[5 rows x 10 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '25.689', 'enterprice': '27080', 'countrevence': '0', 'unrealprofit': '1653.66475766007', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '27015.62751537', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}


## /root/FIL/strategy/modifiedmom/log.txt ----- -----

127.0.0.1 - - [29/Sep/2023 07:30:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=19847 

self.closeSec=1695943799, self.tradeDate='20230929', self.openTime='072000', self.closeTime='072959', self.symbol='BTCUSDT', self.open='27040.7', self.close='27021.8'

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=19848 

self.closeSec=1695944399, self.tradeDate='20230929', self.openTime='073000', self.closeTime='073959', self.symbol='BTCUSDT', self.open='27021.9', self.close='27020'
127.0.0.1 - - [29/Sep/2023 07:40:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=19849 

self.closeSec=1695944999, self.tradeDate='20230929', self.openTime='074000', self.closeTime='074959', self.symbol='BTCUSDT', self.open='27020', self.close='27015'
127.0.0.1 - - [29/Sep/2023 07:50:01] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [29/Sep/2023 08:00:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=19850 

self.closeSec=1695945599, self.tradeDate='20230929', self.openTime='075000', self.closeTime='075959', self.symbol='BTCUSDT', self.open='27015', self.close='27011.8'

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=19851 

self.closeSec=1695946199, self.tradeDate='20230929', self.openTime='080000', self.closeTime='080959', self.symbol='BTCUSDT', self.open='27011.7', self.close='27048'
127.0.0.1 - - [29/Sep/2023 08:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=19852 

self.closeSec=1695946799, self.tradeDate='20230929', self.openTime='081000', self.closeTime='081959', self.symbol='BTCUSDT', self.open='27048', self.close='27084.8'
127.0.0.1 - - [29/Sep/2023 08:20:05] "POST / HTTP/1.1" 200 -


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

127.0.0.1 - - [29/Sep/2023 07:30:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=19850 

self.closeSec=1695943799, self.tradeDate='20230929', self.openTime='072000', self.closeTime='072959', self.symbol='BTCUSDT', self.open='27040.7', self.close='27021.8'
127.0.0.1 - - [29/Sep/2023 07:40:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=19851 

self.closeSec=1695944399, self.tradeDate='20230929', self.openTime='073000', self.closeTime='073959', self.symbol='BTCUSDT', self.open='27021.9', self.close='27020'
127.0.0.1 - - [29/Sep/2023 07:50:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=19852 

self.closeSec=1695944999, self.tradeDate='20230929', self.openTime='074000', self.closeTime='074959', self.symbol='BTCUSDT', self.open='27020', self.close='27015'
127.0.0.1 - - [29/Sep/2023 08:00:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=19853 

self.closeSec=1695945599, self.tradeDate='20230929', self.openTime='075000', self.closeTime='075959', self.symbol='BTCUSDT', self.open='27015', self.close='27011.8'

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=19854 

self.closeSec=1695946199, self.tradeDate='20230929', self.openTime='080000', self.closeTime='080959', self.symbol='BTCUSDT', self.open='27011.7', self.close='27048'
127.0.0.1 - - [29/Sep/2023 08:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=19855 

self.closeSec=1695946799, self.tradeDate='20230929', self.openTime='081000', self.closeTime='081959', self.symbol='BTCUSDT', self.open='27048', self.close='27084.8'
127.0.0.1 - - [29/Sep/2023 08:20:05] "POST / HTTP/1.1" 200 -


## /root/FIL/strategy/similarity/log.txt ----- -----


--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=19850 

self.closeSec=1695943799, self.tradeDate='20230929', self.openTime='072000', self.closeTime='072959', self.symbol='BTCUSDT', self.open='27040.7', self.close='27021.8'
127.0.0.1 - - [29/Sep/2023 07:30:01] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [29/Sep/2023 07:40:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=19851 

self.closeSec=1695944399, self.tradeDate='20230929', self.openTime='073000', self.closeTime='073959', self.symbol='BTCUSDT', self.open='27021.9', self.close='27020'
127.0.0.1 - - [29/Sep/2023 07:50:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=19852 

self.closeSec=1695944999, self.tradeDate='20230929', self.openTime='074000', self.closeTime='074959', self.symbol='BTCUSDT', self.open='27020', self.close='27015'
127.0.0.1 - - [29/Sep/2023 08:00:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=19853 

self.closeSec=1695945599, self.tradeDate='20230929', self.openTime='075000', self.closeTime='075959', self.symbol='BTCUSDT', self.open='27015', self.close='27011.8'
127.0.0.1 - - [29/Sep/2023 08:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=19854 

self.closeSec=1695946199, self.tradeDate='20230929', self.openTime='080000', self.closeTime='080959', self.symbol='BTCUSDT', self.open='27011.7', self.close='27048'

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=19855 

self.closeSec=1695946799, self.tradeDate='20230929', self.openTime='081000', self.closeTime='081959', self.symbol='BTCUSDT', self.open='27048', self.close='27084.8'
127.0.0.1 - - [29/Sep/2023 08:20:04] "POST / HTTP/1.1" 200 -


## /root/FIL/strategy/sr_min/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=1, self.total=996015.990996, self.flagDict['side']='buy', self.tradeCount=1, self.count=39700
self.closeSec=1695946799, self.tradeDate='20230929', self.openTime='081500', self.closeTime='081959', self.symbol='BTCUSDT', self.open=27059.1, self.close=27084.8, self.high=27087.3, self.low=27053.2, self.vol=1262.089, self.amt=34167186.0781 
127.0.0.1 - - [29/Sep/2023 08:20:02] "POST / HTTP/1.1" 200 -
2023-09-29 08:20:06,527:INFO:sr_min:main.py:172:handleKline:2219263: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5855  20230929   075500    075959  ...         0.0        0.0       0
5856  20230929   080000    080459  ...         0.0        0.0       0
5857  20230929   080500    080959  ...         0.0        0.0       0
5858  20230929   081000    081459  ...         0.0        0.0       0
5859  20230929   081500    081959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-09-29 08:20:06,530:INFO:sr_min:main.py:175:handleKline:2219263: self.closeSec=1695946799, self.tradeDate='20230929', self.openTime='081500', self.closeTime='081959',self.symbol='BTCUSDT',self.open=27059.1, self.close=27084.8, self.high=27087.3, self.low=27053.2, self.vol=1262.089, self.amt=34167186.0781, ukdf['pct'].iloc[-1]=0.000965 , ukdf['amount'].iloc[-1]=34167186.0781, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5859, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '37.141', 'enterprice': '26844', 'countrevence': '0', 'unrealprofit': '8834.58784040612', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '27081.86618132', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=1
--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=1, self.total=996015.990996, self.flagDict['side']='buy', self.tradeCount=1, self.count=39701
self.closeSec=1695947099, self.tradeDate='20230929', self.openTime='082000', self.closeTime='082459', self.symbol='BTCUSDT', self.open=27084.7, self.close=27063.2, self.high=27088.3, self.low=27054.8, self.vol=627.082, self.amt=16975135.226 
127.0.0.1 - - [29/Sep/2023 08:25:00] "POST / HTTP/1.1" 200 -
2023-09-29 08:25:00,842:INFO:sr_min:main.py:172:handleKline:2219263: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5856  20230929   080000    080459  ...         0.0        0.0       0
5857  20230929   080500    080959  ...         0.0        0.0       0
5858  20230929   081000    081459  ...         0.0        0.0       0
5859  20230929   081500    081959  ...         0.0        0.0       0
5860  20230929   082000    082459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-09-29 08:25:00,843:INFO:sr_min:main.py:175:handleKline:2219263: self.closeSec=1695947099, self.tradeDate='20230929', self.openTime='082000', self.closeTime='082459',self.symbol='BTCUSDT',self.open=27084.7, self.close=27063.2, self.high=27088.3, self.low=27054.8, self.vol=627.082, self.amt=16975135.226, ukdf['pct'].iloc[-1]=-0.000797 , ukdf['amount'].iloc[-1]=16975135.226, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5860, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '37.141', 'enterprice': '26844', 'countrevence': '0', 'unrealprofit': '8142.92031645443', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '27063.24343223', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=1


## /root/FIL/strategy/s_rsrs/log.txt ----- -----

719  20230928   200000    235959  1695916799  ...    719  0.241155 -0.884063    -1.0
720  20230929   000000    035959  1695931199  ...    720  0.772181  0.387749     NaN

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '50.756', 'enterprice': '26148.9', 'countrevence': '0', 'unrealprofit': '-47956.73938991992', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '27093.74867582', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-9223372036854775808, self.sign=-1
127.0.0.1 - - [29/Sep/2023 08:00:01] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='s_rsrs', self.symbol='BTCUSDT', interval='4h', intervalSec=14400, wid=25, thd=0.6, self.sign=-1, self.total=1325886.3548316, self.flagDict['side']='sell', self.tradeCount=26, self.count=827
self.closeSec=1695945599, self.tradeDate='20230929', self.openTime='040000', self.closeTime='075959', self.symbol='BTCUSDT', self.open=27088.5, self.close=27011.8, self.high=27157.2, self.low=26880.0, self.vol=38159.338, self.amt=1031163924.2083 
2023-09-29 08:00:01,591:INFO:s_rsrs:main.py:141:handleKline:2218689: self.closeSec=1695945599, self.tradeDate='20230929', self.openTime='040000', self.closeTime='075959',self.symbol='BTCUSDT',self.open=27088.5, self.close=27011.8, self.high=27157.2, self.low=26880.0, self.vol=38159.338, self.amt=1031163924.2083 
2023-09-29 08:00:01,614:INFO:s_rsrs:main.py:142:handleKline:2218689: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime  ...         vol           amt       pct
717  20230928   120000    155959  ...   28672.219  7.578532e+08  0.003107
718  20230928   160000    195959  ...   45294.355  1.199687e+09  0.000707
719  20230928   200000    235959  ...  132455.690  3.543541e+09  0.020930
720  20230929   000000    035959  ...  134967.954  3.657050e+09  0.002598
721  20230929   040000    075959  ...   38159.338  1.031164e+09 -0.002831

[5 rows x 11 columns]
2023-09-29 08:00:02,274:INFO:s_rsrs:main.py:151:handleKline:2218689: df_s.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec  ...  index      beta    zscore  signal
717  20230928   120000    155959  1695887999  ...    717  0.065127 -1.322621    -1.0
718  20230928   160000    195959  1695902399  ...    718  0.083519 -1.267790    -1.0
719  20230928   200000    235959  1695916799  ...    719  0.241155 -0.884063    -1.0
720  20230929   000000    035959  1695931199  ...    720  0.772181  0.387749     NaN
721  20230929   040000    075959  1695945599  ...    721  0.776522  0.387464     NaN

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '50.756', 'enterprice': '26148.9', 'countrevence': '0', 'unrealprofit': '-43797.3524', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '27011.8', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-9223372036854775808, self.sign=-1


