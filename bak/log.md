# 20230512 00:26:02

## /root/FIL/strategy/amihud/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=993672.4896432, self.flagDict['side']='sell', self.tradeCount=2, self.count=47637
self.closeSec=1683821999, self.tradeDate='20230512', self.openTime='001500', self.closeTime='001959', self.symbol='BTCUSDT', self.open=27145.0, self.close=27147.8, self.high=27156.2, self.low=27088.3, self.vol=2531.662, self.amt=68653429.7124 
127.0.0.1 - - [12/May/2023 00:20:02] "POST / HTTP/1.1" 200 -
2023-05-12 00:20:06,614:INFO:amihud:main.py:172:handleKline:200676: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5759  20230511   235500    235959  ...         0.0        0.0       0
5760  20230512   000000    000459  ...         0.0        0.0       0
5761  20230512   000500    000959  ...         0.0        0.0       0
5762  20230512   001000    001459  ...         0.0        0.0       0
5763  20230512   001500    001959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-05-12 00:20:06,628:INFO:amihud:main.py:175:handleKline:200676: self.closeSec=1683821999, self.tradeDate='20230512', self.openTime='001500', self.closeTime='001959',self.symbol='BTCUSDT',self.open=27145.0, self.close=27147.8, self.high=27156.2, self.low=27088.3, self.vol=2531.662, self.amt=68653429.7124, ukdf['pct'].iloc[-1]=0.000107 , ukdf['amount'].iloc[-1]=68653429.7124, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5763, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '60.176', 'enterprice': '16529.3', 'countrevence': '0', 'unrealprofit': '-639797.2496', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '27161.4', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1
--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=993672.4896432, self.flagDict['side']='sell', self.tradeCount=2, self.count=47638
self.closeSec=1683822299, self.tradeDate='20230512', self.openTime='002000', self.closeTime='002459', self.symbol='BTCUSDT', self.open=27147.7, self.close=27189.0, self.high=27214.4, self.low=27147.7, self.vol=2102.672, self.amt=57169277.2064 
127.0.0.1 - - [12/May/2023 00:25:02] "POST / HTTP/1.1" 200 -
2023-05-12 00:25:02,164:INFO:amihud:main.py:172:handleKline:200676: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5760  20230512   000000    000459  ...         0.0        0.0       0
5761  20230512   000500    000959  ...         0.0        0.0       0
5762  20230512   001000    001459  ...         0.0        0.0       0
5763  20230512   001500    001959  ...         0.0        0.0       0
5764  20230512   002000    002459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-05-12 00:25:02,165:INFO:amihud:main.py:175:handleKline:200676: self.closeSec=1683822299, self.tradeDate='20230512', self.openTime='002000', self.closeTime='002459',self.symbol='BTCUSDT',self.open=27147.7, self.close=27189.0, self.high=27214.4, self.low=27147.7, self.vol=2102.672, self.amt=57169277.2064, ukdf['pct'].iloc[-1]=0.001518 , ukdf['amount'].iloc[-1]=57169277.2064, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5764, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '60.176', 'enterprice': '16529.3', 'countrevence': '0', 'unrealprofit': '-641533.89247950352', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '27190.25939377', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1


## /root/FIL/strategy/factorcheck/log.txt ----- -----

self.closeSec=1683821099, self.tradeDate='20230512', self.openTime='000000', self.closeTime='000459', self.symbol='BTCUSDT', self.open=27166.3, self.close=27123.7, self.high=27174.5, self.low=27095.1 

--ukdf-hist--: overDate='20230507' 
 Empty DataFrame
Columns: [tradeDate, openTime, closeTime, closeSec, open, close, high, low, pct, index, idx]
Index: [] 
 Empty DataFrame
Columns: [tradeDate, openTime, closeTime, closeSec, open, close, high, low, pct, index, idx]
Index: [] 

127.0.0.1 - - [12/May/2023 00:10:02] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=23, self.factor=0.43541661550691446, self.count=48201 

self.closeSec=1683821399, self.tradeDate='20230512', self.openTime='000500', self.closeTime='000959', self.symbol='BTCUSDT', self.open=27123.6, self.close=27186.7, self.high=27188.0, self.low=27118.6 

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=23, self.factor=0.43541661550691446, self.count=48202 

self.closeSec=1683821699, self.tradeDate='20230512', self.openTime='001000', self.closeTime='001459', self.symbol='BTCUSDT', self.open=27186.7, self.close=27144.9, self.high=27193.5, self.low=27136.8 
127.0.0.1 - - [12/May/2023 00:15:03] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=23, self.factor=0.43541661550691446, self.count=48203 

self.closeSec=1683821999, self.tradeDate='20230512', self.openTime='001500', self.closeTime='001959', self.symbol='BTCUSDT', self.open=27145.0, self.close=27147.8, self.high=27156.2, self.low=27088.3 
127.0.0.1 - - [12/May/2023 00:20:02] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [12/May/2023 00:25:02] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=23, self.factor=0.43541661550691446, self.count=48204 

self.closeSec=1683822299, self.tradeDate='20230512', self.openTime='002000', self.closeTime='002459', self.symbol='BTCUSDT', self.open=27147.7, self.close=27189.0, self.high=27214.4, self.low=27147.7 


## /root/FIL/strategy/logic/log.txt ----- -----

2023-05-12 00:00:21,345:DEBUG:logic:main.py:463:getModel:885513: df_s.iloc[-5:,:] :
          date closeTime     open  ...    alpha58   alpha67   alpha72
5801  20230511    212959  27385.3  ...  50.000000  0.456563  0.513114
5802  20230511    215959  27345.6  ...  50.000000  0.436633  0.535644
5803  20230511    222959  27197.0  ...  50.416667  0.437862  0.552700
5804  20230511    225959  27204.2  ...  50.416667  0.425772  0.570700
5805  20230511    232959  27111.2  ...  50.833333  0.429158  0.586262

[5 rows x 33 columns]
0.5330882352941176
acc is : 0.5330882352941176
2023-05-12 00:00:21,409:INFO:logic:main.py:468:getModel:885513: df_pred.iloc[-5:,:] :
     pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
539     1  0.484269  0.515731       0  ...  0.965491  -1.0    0.0  0.929748
540     1  0.456301  0.543699       1  ...  0.965232  -1.0    0.0  0.929998
541     1  0.486759  0.513241       0  ...  0.968535  -1.0    0.0  0.926815
542     1  0.452043  0.547957       1  ...  0.967835  -1.0    0.0  0.927485
543     1  0.484270  0.515730       1  ...  0.966568  -1.0    0.0  0.928699

[5 rows x 10 columns]
2023-05-12 00:00:21,421:INFO:logic:main.py:478:getModel:885513: df_panel.iloc[-5:,:] :
    pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
45     1  0.484519  0.515481       0  ...  0.965491  -1.0    0.0  0.930604
46     1  0.456355  0.543645       1  ...  0.965232  -1.0    0.0  0.929744
47     1  0.486529  0.513471       0  ...  0.968535  -1.0    0.0  0.926340
48     1  0.452009  0.547991       1  ...  0.967835  -1.0    0.0  0.927010
49     1  0.484270  0.515730       1  ...  0.966568  -1.0    0.0  0.928699

[5 rows x 10 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': []}


## /root/FIL/strategy/modifiedmom/log.txt ----- -----


--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=24097 

self.closeSec=1683818999, self.tradeDate='20230511', self.openTime='232000', self.closeTime='232959', self.symbol='BTCUSDT', self.open='27097.9', self.close='27130.8'
127.0.0.1 - - [11/May/2023 23:30:03] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [11/May/2023 23:40:02] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=24098 

self.closeSec=1683819599, self.tradeDate='20230511', self.openTime='233000', self.closeTime='233959', self.symbol='BTCUSDT', self.open='27130.8', self.close='27167.8'
127.0.0.1 - - [11/May/2023 23:50:02] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=24099 

self.closeSec=1683820199, self.tradeDate='20230511', self.openTime='234000', self.closeTime='234959', self.symbol='BTCUSDT', self.open='27167.8', self.close='27132.8'

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=24100 

self.closeSec=1683820799, self.tradeDate='20230511', self.openTime='235000', self.closeTime='235959', self.symbol='BTCUSDT', self.open='27132.7', self.close='27166.3'
127.0.0.1 - - [12/May/2023 00:00:03] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=24101 

self.closeSec=1683821399, self.tradeDate='20230512', self.openTime='000000', self.closeTime='000959', self.symbol='BTCUSDT', self.open='27166.3', self.close='27186.7'
127.0.0.1 - - [12/May/2023 00:10:02] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=24102 

self.closeSec=1683821999, self.tradeDate='20230512', self.openTime='001000', self.closeTime='001959', self.symbol='BTCUSDT', self.open='27186.7', self.close='27147.8'
127.0.0.1 - - [12/May/2023 00:20:05] "POST / HTTP/1.1" 200 -


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


--handleKline--:  127.0.0.1 - - [11/May/2023 23:30:03] "POST / HTTP/1.1" 200 -
self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=24098 

self.closeSec=1683818999, self.tradeDate='20230511', self.openTime='232000', self.closeTime='232959', self.symbol='BTCUSDT', self.open='27097.9', self.close='27130.8'

--handleKline--: 127.0.0.1 - - [11/May/2023 23:40:02] "POST / HTTP/1.1" 200 -
 self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=24099 

self.closeSec=1683819599, self.tradeDate='20230511', self.openTime='233000', self.closeTime='233959', self.symbol='BTCUSDT', self.open='27130.8', self.close='27167.8'
127.0.0.1 - - [11/May/2023 23:50:02] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=24100 

self.closeSec=1683820199, self.tradeDate='20230511', self.openTime='234000', self.closeTime='234959', self.symbol='BTCUSDT', self.open='27167.8', self.close='27132.8'

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=24101 

self.closeSec=1683820799, self.tradeDate='20230511', self.openTime='235000', self.closeTime='235959', self.symbol='BTCUSDT', self.open='27132.7', self.close='27166.3'
127.0.0.1 - - [12/May/2023 00:00:03] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [12/May/2023 00:10:02] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=24102 

self.closeSec=1683821399, self.tradeDate='20230512', self.openTime='000000', self.closeTime='000959', self.symbol='BTCUSDT', self.open='27166.3', self.close='27186.7'

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=24103 

self.closeSec=1683821999, self.tradeDate='20230512', self.openTime='001000', self.closeTime='001959', self.symbol='BTCUSDT', self.open='27186.7', self.close='27147.8'
127.0.0.1 - - [12/May/2023 00:20:05] "POST / HTTP/1.1" 200 -


## /root/FIL/strategy/similarity/log.txt ----- -----


--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=24098 

self.closeSec=1683818999, self.tradeDate='20230511', self.openTime='232000', self.closeTime='232959', self.symbol='BTCUSDT', self.open='27097.9', self.close='27130.8'
127.0.0.1 - - [11/May/2023 23:30:03] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [11/May/2023 23:40:02] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=24099 

self.closeSec=1683819599, self.tradeDate='20230511', self.openTime='233000', self.closeTime='233959', self.symbol='BTCUSDT', self.open='27130.8', self.close='27167.8'

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=24100 

self.closeSec=1683820199, self.tradeDate='20230511', self.openTime='234000', self.closeTime='234959', self.symbol='BTCUSDT', self.open='27167.8', self.close='27132.8'
127.0.0.1 - - [11/May/2023 23:50:02] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [12/May/2023 00:00:03] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=24101 

self.closeSec=1683820799, self.tradeDate='20230511', self.openTime='235000', self.closeTime='235959', self.symbol='BTCUSDT', self.open='27132.7', self.close='27166.3'

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=24102 

self.closeSec=1683821399, self.tradeDate='20230512', self.openTime='000000', self.closeTime='000959', self.symbol='BTCUSDT', self.open='27166.3', self.close='27186.7'
127.0.0.1 - - [12/May/2023 00:10:02] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=24103 

self.closeSec=1683821999, self.tradeDate='20230512', self.openTime='001000', self.closeTime='001959', self.symbol='BTCUSDT', self.open='27186.7', self.close='27147.8'
127.0.0.1 - - [12/May/2023 00:20:05] "POST / HTTP/1.1" 200 -


## /root/FIL/strategy/sr_min/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=0, self.total=1000000.0, self.flagDict['side']='', self.tradeCount=0, self.count=43635
self.closeSec=1683821999, self.tradeDate='20230512', self.openTime='001500', self.closeTime='001959', self.symbol='BTCUSDT', self.open=27145.0, self.close=27147.8, self.high=27156.2, self.low=27088.3, self.vol=2531.662, self.amt=68653429.7124 
127.0.0.1 - - [12/May/2023 00:20:03] "POST / HTTP/1.1" 200 -
2023-05-12 00:20:06,638:INFO:sr_min:main.py:172:handleKline:449472: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5759  20230511   235500    235959  ...         0.0        0.0       0
5760  20230512   000000    000459  ...         0.0        0.0       0
5761  20230512   000500    000959  ...         0.0        0.0       0
5762  20230512   001000    001459  ...         0.0        0.0       0
5763  20230512   001500    001959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-05-12 00:20:06,644:INFO:sr_min:main.py:175:handleKline:449472: self.closeSec=1683821999, self.tradeDate='20230512', self.openTime='001500', self.closeTime='001959',self.symbol='BTCUSDT',self.open=27145.0, self.close=27147.8, self.high=27156.2, self.low=27088.3, self.vol=2531.662, self.amt=68653429.7124, ukdf['pct'].iloc[-1]=0.000107 , ukdf['amount'].iloc[-1]=68653429.7124, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5763, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': []}
type(curSign)=<class 'int'>, curSign=0, self.sign=0
127.0.0.1 - - [12/May/2023 00:25:02] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=0, self.total=1000000.0, self.flagDict['side']='', self.tradeCount=0, self.count=43636
self.closeSec=1683822299, self.tradeDate='20230512', self.openTime='002000', self.closeTime='002459', self.symbol='BTCUSDT', self.open=27147.7, self.close=27189.0, self.high=27214.4, self.low=27147.7, self.vol=2102.672, self.amt=57169277.2064 
2023-05-12 00:25:02,184:INFO:sr_min:main.py:172:handleKline:449472: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5760  20230512   000000    000459  ...         0.0        0.0       0
5761  20230512   000500    000959  ...         0.0        0.0       0
5762  20230512   001000    001459  ...         0.0        0.0       0
5763  20230512   001500    001959  ...         0.0        0.0       0
5764  20230512   002000    002459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-05-12 00:25:02,184:INFO:sr_min:main.py:175:handleKline:449472: self.closeSec=1683822299, self.tradeDate='20230512', self.openTime='002000', self.closeTime='002459',self.symbol='BTCUSDT',self.open=27147.7, self.close=27189.0, self.high=27214.4, self.low=27147.7, self.vol=2102.672, self.amt=57169277.2064, ukdf['pct'].iloc[-1]=0.001518 , ukdf['amount'].iloc[-1]=57169277.2064, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5764, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': []}
type(curSign)=<class 'int'>, curSign=0, self.sign=0


## /root/FIL/strategy/s_rsrs/log.txt ----- -----

723  20230511   120000    155959  1683791999  ...    723  0.412500 -0.397041     NaN
724  20230511   160000    195959  1683806399  ...    724  0.412517 -0.380556     NaN

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '52.501', 'enterprice': '27610.1', 'countrevence': '0', 'unrealprofit': '-11240.4641', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '27396', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-9223372036854775808, self.sign=1
--handleKline--:  version='2.0.0', self.name='s_rsrs', self.symbol='BTCUSDT', interval='4h', intervalSec=14400, wid=25, thd=0.6, self.sign=1, self.total=1448108.3022399, self.flagDict['side']='buy', self.tradeCount=34, self.count=1004
self.closeSec=1683820799, self.tradeDate='20230511', self.openTime='200000', self.closeTime='235959', self.symbol='BTCUSDT', self.open=27393.2, self.close=27166.3, self.high=27630.0, self.low=26924.0, self.vol=187266.555, self.amt=5104506716.23237 
127.0.0.1 - - [12/May/2023 00:00:03] "POST / HTTP/1.1" 200 -
2023-05-12 00:00:03,455:INFO:s_rsrs:main.py:141:handleKline:185271: self.closeSec=1683820799, self.tradeDate='20230511', self.openTime='200000', self.closeTime='235959',self.symbol='BTCUSDT',self.open=27393.2, self.close=27166.3, self.high=27630.0, self.low=26924.0, self.vol=187266.555, self.amt=5104506716.23237 
2023-05-12 00:00:03,494:INFO:s_rsrs:main.py:142:handleKline:185271: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime  ...         vol           amt       pct
721  20230511   040000    075959  ...   99430.444  2.747766e+09 -0.003638
722  20230511   080000    115959  ...   56879.457  1.563685e+09 -0.005358
723  20230511   120000    155959  ...   39192.274  1.076570e+09  0.000087
724  20230511   160000    195959  ...   55275.014  1.514130e+09 -0.001615
725  20230511   200000    235959  ...  187266.555  5.104507e+09 -0.008283

[5 rows x 11 columns]
2023-05-12 00:00:04,701:INFO:s_rsrs:main.py:151:handleKline:185271: df_s.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec  ...  index      beta    zscore  signal
721  20230511   040000    075959  1683763199  ...    721  0.442410 -0.312865     NaN
722  20230511   080000    115959  1683777599  ...    722  0.447831 -0.287138     NaN
723  20230511   120000    155959  1683791999  ...    723  0.412500 -0.397041     NaN
724  20230511   160000    195959  1683806399  ...    724  0.412517 -0.380556     NaN
725  20230511   200000    235959  1683820799  ...    725  0.360522 -0.546813     NaN

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '52.501', 'enterprice': '27610.1', 'countrevence': '0', 'unrealprofit': '-23094.48940593251', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '27170.21334249', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-9223372036854775808, self.sign=1


