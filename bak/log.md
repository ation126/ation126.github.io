# 20230426 08:26:02

## /root/FIL/strategy/amihud/log.txt ----- -----

127.0.0.1 - - [26/Apr/2023 08:20:01] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=993672.4896432, self.flagDict['side']='sell', self.tradeCount=2, self.count=43125
self.closeSec=1682468399, self.tradeDate='20230426', self.openTime='081500', self.closeTime='081959', self.symbol='BTCUSDT', self.open=28359.6, self.close=28404.5, self.high=28415.7, self.low=28338.8, self.vol=3251.23, self.amt=92233926.2238 
2023-04-26 08:20:01,706:INFO:amihud:main.py:172:handleKline:200676: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5848  20230426   075500    075959  ...         0.0        0.0       0
5849  20230426   080000    080459  ...         0.0        0.0       0
5850  20230426   080500    080959  ...         0.0        0.0       0
5851  20230426   081000    081459  ...         0.0        0.0       0
5852  20230426   081500    081959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-04-26 08:20:01,709:INFO:amihud:main.py:175:handleKline:200676: self.closeSec=1682468399, self.tradeDate='20230426', self.openTime='081500', self.closeTime='081959',self.symbol='BTCUSDT',self.open=28359.6, self.close=28404.5, self.high=28415.7, self.low=28338.8, self.vol=3251.23, self.amt=92233926.2238, ukdf['pct'].iloc[-1]=0.001583 , ukdf['amount'].iloc[-1]=92233926.2238, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5852, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '60.176', 'enterprice': '16529.3', 'countrevence': '0', 'unrealprofit': '-715998.1184', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '28427.7', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1
--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=993672.4896432, self.flagDict['side']='sell', self.tradeCount=2, self.count=43126
self.closeSec=1682468699, self.tradeDate='20230426', self.openTime='082000', self.closeTime='082459', self.symbol='BTCUSDT', self.open=28406.2, self.close=28350.6, self.high=28441.5, self.low=28336.0, self.vol=2671.694, self.amt=75816486.9777 
127.0.0.1 - - [26/Apr/2023 08:25:01] "POST / HTTP/1.1" 200 -
2023-04-26 08:25:01,577:INFO:amihud:main.py:172:handleKline:200676: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5849  20230426   080000    080459  ...         0.0        0.0       0
5850  20230426   080500    080959  ...         0.0        0.0       0
5851  20230426   081000    081459  ...         0.0        0.0       0
5852  20230426   081500    081959  ...         0.0        0.0       0
5853  20230426   082000    082459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-04-26 08:25:01,578:INFO:amihud:main.py:175:handleKline:200676: self.closeSec=1682468699, self.tradeDate='20230426', self.openTime='082000', self.closeTime='082459',self.symbol='BTCUSDT',self.open=28406.2, self.close=28350.6, self.high=28441.5, self.low=28336.0, self.vol=2671.694, self.amt=75816486.9777, ukdf['pct'].iloc[-1]=-0.001898 , ukdf['amount'].iloc[-1]=75816486.9777, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5853, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '60.176', 'enterprice': '16529.3', 'countrevence': '0', 'unrealprofit': '-711364.5664', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '28350.7', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1


## /root/FIL/strategy/factorcheck/log.txt ----- -----


--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=23, self.factor=0.43541661550691446, self.count=43687 

self.closeSec=1682467199, self.tradeDate='20230426', self.openTime='075500', self.closeTime='075959', self.symbol='BTCUSDT', self.open=28305.5, self.close=28286.7, self.high=28306.5, self.low=28277.3 
127.0.0.1 - - [26/Apr/2023 08:00:01] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [26/Apr/2023 08:05:01] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=23, self.factor=0.43541661550691446, self.count=43688 

self.closeSec=1682467499, self.tradeDate='20230426', self.openTime='080000', self.closeTime='080459', self.symbol='BTCUSDT', self.open=28286.7, self.close=28264.0, self.high=28305.7, self.low=28252.9 

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=23, self.factor=0.43541661550691446, self.count=43689 

self.closeSec=1682467799, self.tradeDate='20230426', self.openTime='080500', self.closeTime='080959', self.symbol='BTCUSDT', self.open=28264.0, self.close=28271.8, self.high=28287.1, self.low=28250.1 
127.0.0.1 - - [26/Apr/2023 08:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=23, self.factor=0.43541661550691446, self.count=43690 

self.closeSec=1682468099, self.tradeDate='20230426', self.openTime='081000', self.closeTime='081459', self.symbol='BTCUSDT', self.open=28271.8, self.close=28359.6, self.high=28460.0, self.low=28266.0 
127.0.0.1 - - [26/Apr/2023 08:15:03] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [26/Apr/2023 08:20:01] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=23, self.factor=0.43541661550691446, self.count=43691 

self.closeSec=1682468399, self.tradeDate='20230426', self.openTime='081500', self.closeTime='081959', self.symbol='BTCUSDT', self.open=28359.6, self.close=28404.5, self.high=28415.7, self.low=28338.8 

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=23, self.factor=0.43541661550691446, self.count=43692 

self.closeSec=1682468699, self.tradeDate='20230426', self.openTime='082000', self.closeTime='082459', self.symbol='BTCUSDT', self.open=28406.2, self.close=28350.6, self.high=28441.5, self.low=28336.0 
127.0.0.1 - - [26/Apr/2023 08:25:01] "POST / HTTP/1.1" 200 -


## /root/FIL/strategy/logic/log.txt ----- -----

2023-04-26 08:00:21,209:DEBUG:logic:main.py:463:getModel:885513: df_s.iloc[-5:,:] :
          date closeTime     open  ...    alpha58   alpha67   alpha72
5769  20230426    052959  27961.7  ...  53.333333  0.613316  0.369531
5770  20230426    055959  28219.9  ...  53.333333  0.616790  0.347905
5771  20230426    062959  28249.4  ...  52.916667  0.612440  0.333204
5772  20230426    065959  28226.6  ...  52.916667  0.611026  0.319888
5773  20230426    072959  28219.3  ...  53.333333  0.615371  0.305521

[5 rows x 33 columns]
0.5444444444444444
acc is : 0.5444444444444444
2023-04-26 08:00:21,323:INFO:logic:main.py:468:getModel:885513: df_pred.iloc[-5:,:] :
     pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
535     0  0.600552  0.399448       1  ...  0.873603   1.0    0.0  0.933537
536     0  0.564065  0.435935       0  ...  0.872901   1.0    0.0  0.932787
537     0  0.545168  0.454832       0  ...  0.872676   1.0    0.0  0.932546
538     0  0.520634  0.479366       1  ...  0.873758   1.0    0.0  0.933702
539     0  0.530301  0.469699       1  ...  0.874760   1.0    0.0  0.934773

[5 rows x 10 columns]
2023-04-26 08:00:21,337:INFO:logic:main.py:478:getModel:885513: df_panel.iloc[-5:,:] :
    pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
45     0  0.600636  0.399364       1  ...  0.873603   1.0    0.0  0.934581
46     0  0.563991  0.436009       0  ...  0.872901   1.0    0.0  0.934919
47     0  0.544960  0.455040       0  ...  0.872676   1.0    0.0  0.936507
48     0  0.520280  0.479720       1  ...  0.873758   1.0    0.0  0.934895
49     0  0.530301  0.469699       1  ...  0.874760   1.0    0.0  0.934773

[5 rows x 10 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': []}


## /root/FIL/strategy/modifiedmom/log.txt ----- -----


--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=21841 

self.closeSec=1682465399, self.tradeDate='20230426', self.openTime='072000', self.closeTime='072959', self.symbol='BTCUSDT', self.open='28237.2', self.close='28254.3'
127.0.0.1 - - [26/Apr/2023 07:30:01] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [26/Apr/2023 07:40:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=21842 

self.closeSec=1682465999, self.tradeDate='20230426', self.openTime='073000', self.closeTime='073959', self.symbol='BTCUSDT', self.open='28254.3', self.close='28289.3'
127.0.0.1 - - [26/Apr/2023 07:50:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=21843 

self.closeSec=1682466599, self.tradeDate='20230426', self.openTime='074000', self.closeTime='074959', self.symbol='BTCUSDT', self.open='28289.3', self.close='28332'

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=21844 

self.closeSec=1682467199, self.tradeDate='20230426', self.openTime='075000', self.closeTime='075959', self.symbol='BTCUSDT', self.open='28331.9', self.close='28286.7'
127.0.0.1 - - [26/Apr/2023 08:00:02] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [26/Apr/2023 08:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=21845 

self.closeSec=1682467799, self.tradeDate='20230426', self.openTime='080000', self.closeTime='080959', self.symbol='BTCUSDT', self.open='28286.7', self.close='28271.8'

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=21846 

self.closeSec=1682468399, self.tradeDate='20230426', self.openTime='081000', self.closeTime='081959', self.symbol='BTCUSDT', self.open='28271.8', self.close='28404.5'
127.0.0.1 - - [26/Apr/2023 08:20:03] "POST / HTTP/1.1" 200 -


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


--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=21842 

self.closeSec=1682465399, self.tradeDate='20230426', self.openTime='072000', self.closeTime='072959', self.symbol='BTCUSDT', self.open='28237.2', self.close='28254.3'
127.0.0.1 - - [26/Apr/2023 07:30:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=21843 

self.closeSec=1682465999, self.tradeDate='20230426', self.openTime='073000', self.closeTime='073959', self.symbol='BTCUSDT', self.open='28254.3', self.close='28289.3'
127.0.0.1 - - [26/Apr/2023 07:40:01] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [26/Apr/2023 07:50:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=21844 

self.closeSec=1682466599, self.tradeDate='20230426', self.openTime='074000', self.closeTime='074959', self.symbol='BTCUSDT', self.open='28289.3', self.close='28332'
127.0.0.1 - - [26/Apr/2023 08:00:02] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=21845 

self.closeSec=1682467199, self.tradeDate='20230426', self.openTime='075000', self.closeTime='075959', self.symbol='BTCUSDT', self.open='28331.9', self.close='28286.7'

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=21846 

self.closeSec=1682467799, self.tradeDate='20230426', self.openTime='080000', self.closeTime='080959', self.symbol='BTCUSDT', self.open='28286.7', self.close='28271.8'
127.0.0.1 - - [26/Apr/2023 08:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=21847 

self.closeSec=1682468399, self.tradeDate='20230426', self.openTime='081000', self.closeTime='081959', self.symbol='BTCUSDT', self.open='28271.8', self.close='28404.5'
127.0.0.1 - - [26/Apr/2023 08:20:03] "POST / HTTP/1.1" 200 -


## /root/FIL/strategy/similarity/log.txt ----- -----


--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=21842 

self.closeSec=1682465399, self.tradeDate='20230426', self.openTime='072000', self.closeTime='072959', self.symbol='BTCUSDT', self.open='28237.2', self.close='28254.3'
127.0.0.1 - - [26/Apr/2023 07:30:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=21843 

self.closeSec=1682465999, self.tradeDate='20230426', self.openTime='073000', self.closeTime='073959', self.symbol='BTCUSDT', self.open='28254.3', self.close='28289.3'
127.0.0.1 - - [26/Apr/2023 07:40:01] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [26/Apr/2023 07:50:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=21844 

self.closeSec=1682466599, self.tradeDate='20230426', self.openTime='074000', self.closeTime='074959', self.symbol='BTCUSDT', self.open='28289.3', self.close='28332'
127.0.0.1 - - [26/Apr/2023 08:00:02] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=21845 

self.closeSec=1682467199, self.tradeDate='20230426', self.openTime='075000', self.closeTime='075959', self.symbol='BTCUSDT', self.open='28331.9', self.close='28286.7'
127.0.0.1 - - [26/Apr/2023 08:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=21846 

self.closeSec=1682467799, self.tradeDate='20230426', self.openTime='080000', self.closeTime='080959', self.symbol='BTCUSDT', self.open='28286.7', self.close='28271.8'

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=21847 

self.closeSec=1682468399, self.tradeDate='20230426', self.openTime='081000', self.closeTime='081959', self.symbol='BTCUSDT', self.open='28271.8', self.close='28404.5'
127.0.0.1 - - [26/Apr/2023 08:20:03] "POST / HTTP/1.1" 200 -


## /root/FIL/strategy/sr_min/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=0, self.total=1000000.0, self.flagDict['side']='', self.tradeCount=0, self.count=39123
self.closeSec=1682468399, self.tradeDate='20230426', self.openTime='081500', self.closeTime='081959', self.symbol='BTCUSDT', self.open=28359.6, self.close=28404.5, self.high=28415.7, self.low=28338.8, self.vol=3251.23, self.amt=92233926.2238 
127.0.0.1 - - [26/Apr/2023 08:20:02] "POST / HTTP/1.1" 200 -
2023-04-26 08:20:03,970:INFO:sr_min:main.py:172:handleKline:449472: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5848  20230426   075500    075959  ...         0.0        0.0       0
5849  20230426   080000    080459  ...         0.0        0.0       0
5850  20230426   080500    080959  ...         0.0        0.0       0
5851  20230426   081000    081459  ...         0.0        0.0       0
5852  20230426   081500    081959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-04-26 08:20:03,975:INFO:sr_min:main.py:175:handleKline:449472: self.closeSec=1682468399, self.tradeDate='20230426', self.openTime='081500', self.closeTime='081959',self.symbol='BTCUSDT',self.open=28359.6, self.close=28404.5, self.high=28415.7, self.low=28338.8, self.vol=3251.23, self.amt=92233926.2238, ukdf['pct'].iloc[-1]=0.001583 , ukdf['amount'].iloc[-1]=92233926.2238, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5852, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': []}
type(curSign)=<class 'int'>, curSign=0, self.sign=0
127.0.0.1 - - [26/Apr/2023 08:25:01] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=0, self.total=1000000.0, self.flagDict['side']='', self.tradeCount=0, self.count=39124
self.closeSec=1682468699, self.tradeDate='20230426', self.openTime='082000', self.closeTime='082459', self.symbol='BTCUSDT', self.open=28406.2, self.close=28350.6, self.high=28441.5, self.low=28336.0, self.vol=2671.694, self.amt=75816486.9777 
2023-04-26 08:25:01,576:INFO:sr_min:main.py:172:handleKline:449472: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5849  20230426   080000    080459  ...         0.0        0.0       0
5850  20230426   080500    080959  ...         0.0        0.0       0
5851  20230426   081000    081459  ...         0.0        0.0       0
5852  20230426   081500    081959  ...         0.0        0.0       0
5853  20230426   082000    082459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-04-26 08:25:01,577:INFO:sr_min:main.py:175:handleKline:449472: self.closeSec=1682468699, self.tradeDate='20230426', self.openTime='082000', self.closeTime='082459',self.symbol='BTCUSDT',self.open=28406.2, self.close=28350.6, self.high=28441.5, self.low=28336.0, self.vol=2671.694, self.amt=75816486.9777, ukdf['pct'].iloc[-1]=-0.001898 , ukdf['amount'].iloc[-1]=75816486.9777, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5853, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': []}
type(curSign)=<class 'int'>, curSign=0, self.sign=0


## /root/FIL/strategy/s_rsrs/log.txt ----- -----

719  20230425   200000    235959  1682438399  ...    719  0.399294 -0.928003    -1.0
720  20230426   000000    035959  1682452799  ...    720  0.197066 -1.444367    -1.0

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '52.48', 'enterprice': '27388.7', 'countrevence': '0', 'unrealprofit': '-11687.296', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '27611.4', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-1, self.sign=-1
127.0.0.1 - - [26/Apr/2023 08:00:01] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='s_rsrs', self.symbol='BTCUSDT', interval='4h', intervalSec=14400, wid=25, thd=0.6, self.sign=-1, self.total=1435921.617024, self.flagDict['side']='sell', self.tradeCount=31, self.count=910
self.closeSec=1682467199, self.tradeDate='20230426', self.openTime='040000', self.closeTime='075959', self.symbol='BTCUSDT', self.open=27596.2, self.close=28286.7, self.high=28379.9, self.low=27596.2, self.vol=162175.001, self.amt=4557366505.33031 
2023-04-26 08:00:01,920:INFO:s_rsrs:main.py:141:handleKline:185271: self.closeSec=1682467199, self.tradeDate='20230426', self.openTime='040000', self.closeTime='075959',self.symbol='BTCUSDT',self.open=27596.2, self.close=28286.7, self.high=28379.9, self.low=27596.2, self.vol=162175.001, self.amt=4557366505.33031 
2023-04-26 08:00:01,969:INFO:s_rsrs:main.py:142:handleKline:185271: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime  ...         vol           amt       pct
717  20230425   120000    155959  ...   45282.567  1.238376e+09 -0.003120
718  20230425   160000    195959  ...   66538.637  1.818263e+09  0.004763
719  20230425   200000    235959  ...   74964.782  2.049648e+09 -0.001921
720  20230426   000000    035959  ...  115386.167  3.178022e+09  0.009755
721  20230426   040000    075959  ...  162175.001  4.557367e+09  0.025025

[5 rows x 11 columns]
2023-04-26 08:00:04,013:INFO:s_rsrs:main.py:151:handleKline:185271: df_s.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec  ...  index      beta    zscore  signal
717  20230425   120000    155959  1682409599  ...    717  0.571203 -0.484200     NaN
718  20230425   160000    195959  1682423999  ...    718  0.469231 -0.754624    -1.0
719  20230425   200000    235959  1682438399  ...    719  0.399294 -0.928003    -1.0
720  20230426   000000    035959  1682452799  ...    720  0.197066 -1.444367    -1.0
721  20230426   040000    075959  1682467199  ...    721  0.718385 -0.013986     NaN

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '52.48', 'enterprice': '27388.7', 'countrevence': '0', 'unrealprofit': '-47132.288', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '28286.8', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-9223372036854775808, self.sign=-1


