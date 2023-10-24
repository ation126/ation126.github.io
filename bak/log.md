# 20231025 00:26:01

## /root/FIL/strategy/amihud/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=373746.4768026, self.flagDict['side']='sell', self.tradeCount=2, self.count=47092
self.closeSec=1698164399, self.tradeDate='20231025', self.openTime='001500', self.closeTime='001959', self.symbol='BTCUSDT', self.open=33881.4, self.close=33858.8, self.high=33954.6, self.low=33789.6, self.vol=3933.403, self.amt=133229011.1182 
127.0.0.1 - - [25/Oct/2023 00:20:03] "POST / HTTP/1.1" 200 -
2023-10-25 00:20:06,361:INFO:amihud:main.py:172:handleKline:2219019: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5759  20231024   235500    235959  ...         0.0        0.0       0
5760  20231025   000000    000459  ...         0.0        0.0       0
5761  20231025   000500    000959  ...         0.0        0.0       0
5762  20231025   001000    001459  ...         0.0        0.0       0
5763  20231025   001500    001959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-10-25 00:20:06,366:INFO:amihud:main.py:175:handleKline:2219019: self.closeSec=1698164399, self.tradeDate='20231025', self.openTime='001500', self.closeTime='001959',self.symbol='BTCUSDT',self.open=33881.4, self.close=33858.8, self.high=33954.6, self.low=33789.6, self.vol=3933.403, self.amt=133229011.1182, ukdf['pct'].iloc[-1]=0.000165 , ukdf['amount'].iloc[-1]=133229011.1182, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5763, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '13.926', 'enterprice': '26864.9', 'countrevence': '0', 'unrealprofit': '-97260.66275751606', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '33849.00618681', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1
--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=373746.4768026, self.flagDict['side']='sell', self.tradeCount=2, self.count=47093
self.closeSec=1698164699, self.tradeDate='20231025', self.openTime='002000', self.closeTime='002459', self.symbol='BTCUSDT', self.open=33856.9, self.close=33880.0, self.high=33940.0, self.low=33812.2, self.vol=2345.654, self.amt=79449616.3739 
127.0.0.1 - - [25/Oct/2023 00:25:01] "POST / HTTP/1.1" 200 -
2023-10-25 00:25:03,278:INFO:amihud:main.py:172:handleKline:2219019: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5760  20231025   000000    000459  ...         0.0        0.0       0
5761  20231025   000500    000959  ...         0.0        0.0       0
5762  20231025   001000    001459  ...         0.0        0.0       0
5763  20231025   001500    001959  ...         0.0        0.0       0
5764  20231025   002000    002459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-10-25 00:25:03,287:INFO:amihud:main.py:175:handleKline:2219019: self.closeSec=1698164699, self.tradeDate='20231025', self.openTime='002000', self.closeTime='002459',self.symbol='BTCUSDT',self.open=33856.9, self.close=33880.0, self.high=33940.0, self.low=33812.2, self.vol=2345.654, self.amt=79449616.3739, ukdf['pct'].iloc[-1]=0.000626 , ukdf['amount'].iloc[-1]=79449616.3739, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5764, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '13.926', 'enterprice': '26864.9', 'countrevence': '0', 'unrealprofit': '-97581.86061692178', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '33872.07080403', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1


## /root/FIL/strategy/factorcheck/log.txt ----- -----

self.closeSec=1698163499, self.tradeDate='20231025', self.openTime='000000', self.closeTime='000459', self.symbol='BTCUSDT', self.open=33673.9, self.close=33565.2, self.high=33734.0, self.low=33565.2 

--ukdf-hist--: overDate='20231020' 
 Empty DataFrame
Columns: [tradeDate, openTime, closeTime, closeSec, open, close, high, low, pct, index, idx]
Index: [] 
 Empty DataFrame
Columns: [tradeDate, openTime, closeTime, closeSec, open, close, high, low, pct, index, idx]
Index: [] 

127.0.0.1 - - [25/Oct/2023 00:10:00] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.714181719035411, self.count=47092 

self.closeSec=1698163799, self.tradeDate='20231025', self.openTime='000500', self.closeTime='000959', self.symbol='BTCUSDT', self.open=33564.9, self.close=33790.0, self.high=33830.0, self.low=33490.0 

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.714181719035411, self.count=47093 

self.closeSec=1698164099, self.tradeDate='20231025', self.openTime='001000', self.closeTime='001459', self.symbol='BTCUSDT', self.open=33803.3, self.close=33853.2, self.high=33980.0, self.low=33773.4 
127.0.0.1 - - [25/Oct/2023 00:15:00] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.714181719035411, self.count=47094 

self.closeSec=1698164399, self.tradeDate='20231025', self.openTime='001500', self.closeTime='001959', self.symbol='BTCUSDT', self.open=33881.4, self.close=33858.8, self.high=33954.6, self.low=33789.6 
127.0.0.1 - - [25/Oct/2023 00:20:03] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.714181719035411, self.count=47095 

self.closeSec=1698164699, self.tradeDate='20231025', self.openTime='002000', self.closeTime='002459', self.symbol='BTCUSDT', self.open=33856.9, self.close=33880.0, self.high=33940.0, self.low=33812.2 
127.0.0.1 - - [25/Oct/2023 00:25:01] "POST / HTTP/1.1" 200 -


## /root/FIL/strategy/logic/log.txt ----- -----

     pred    prob_0    prob_1  actual  ...       nav  sign   cost_        bm
539     0  0.524384  0.475616       0  ...  1.128041   1.0  0.0000  1.282170
540     0  0.533188  0.466812       0  ...  1.122080   1.0  0.0000  1.275395
541     1  0.489656  0.510344       1  ...  1.127360   1.0  0.0000  1.281396
542     0  0.570342  0.429658       0  ...  1.101052   1.0  0.0000  1.251494
543     1  0.323366  0.676634       1  ...  1.097355  -1.0 -0.0016  1.253694

[5 rows x 10 columns]
2023-10-25 00:00:20,611:INFO:logic:main.py:478:getModel:2218526: df_panel.iloc[-5:,:] :
    pred    prob_0    prob_1  actual  ...       nav  sign   cost_        bm
45     0  0.524159  0.475841       0  ...  1.128041   1.0  0.0000  1.285458
46     0  0.533577  0.466423       0  ...  1.122080   1.0  0.0000  1.278469
47     1  0.490381  0.509619       1  ...  1.127360   1.0  0.0000  1.280828
48     0  0.571646  0.428354       0  ...  1.101052   1.0  0.0000  1.250940
49     1  0.323366  0.676634       1  ...  1.097355  -1.0 -0.0016  1.253694

[5 rows x 10 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '21.245', 'enterprice': '33811.2', 'countrevence': '0', 'unrealprofit': '-2870.6876943787', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '33676.07702074', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
handlebackTrade > queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '21.245', 'enterprice': '33811.2', 'countrevence': '0', 'unrealprofit': '-2870.6901783441', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '33676.07690382', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
2023-10-25 00:00:27,427:INFO:logic:main.py:500:queryContractAssets:2218526: queryContractAssets: assets=ContractAssetReturn{'result': [ContractAsset{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'asset': 'USDT', 'free': '715775.8815078', 'total': '715775.8815078', 'margin': '0', 'unreal': '0', 'type': 'AssetType_ucontract'}]}
2023-10-25 00:00:27,934:INFO:logic:main.py:587:openSell:2218526: ret = self.client.insertMarketUOrder("simulator", "BTCUSDT", 21.191, "sell"), ret=InsertOrderReturn{'result': 'success', 'clientorderid': '43044F1698163227932I0L64'}
2023-10-25 00:00:27,957:INFO:logic:main.py:494:insertFactor:2218526: curDateTime:10250000, name:logic, symbol:BTCUSDT, tradeDate:20231024, closeTime:235959, close:33675.6, sign:-1, total:715775.8815078, side:sell  
127.0.0.1 - - [25/Oct/2023 00:00:27] "POST / HTTP/1.1" 200 -
2023-10-25 00:00:27,958:INFO:logic:main.py:661:handleOrderNew:2218526: handleOrderNew: data=OrderType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'clientorderid': '43043F1698163222364I0L64', 'symbol': 'BTCUSDT', 'gatewayorderid': 1698163222796685, 'quantity': '21.245', 'price': '33678.8', 'stopprice': '0', 'ordertype': '', 'side': 'SELL', 'status': 'FILLED', 'positionside': 'SHORT', 'createtime': 1698163221466, 'updatetime': 1698163222796, 'tradetype': 'usdt', 'selfid': 43043, 'filltrades': [TradeType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'tradeid': 1698163222796, 'clientorderid': '43043F1698163222364I0L64', 'price': '33678.8', 'quantity': '21.245', 'commission': '715.506106', 'commissionasset': 'USDT', 'tradetime': 1698163222796, 'tradetype': 'usdt', 'gatetype': 'simulator', 'handletime': 1698163222796}], 'gatetype': 'simulator', 'handletime': 0}
127.0.0.1 - - [25/Oct/2023 00:00:27] "POST / HTTP/1.1" 200 -
2023-10-25 00:00:27,961:INFO:logic:main.py:664:handleOrderFilled:2218526: handleOrderFilled: data=OrderType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'clientorderid': '43043F1698163222364I0L64', 'symbol': 'BTCUSDT', 'gatewayorderid': 1698163222796685, 'quantity': '21.245', 'price': '33678.8', 'stopprice': '0', 'ordertype': '', 'side': 'SELL', 'status': 'FILLED', 'positionside': 'SHORT', 'createtime': 1698163221466, 'updatetime': 1698163222796, 'tradetype': 'usdt', 'selfid': 43043, 'filltrades': [TradeType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'tradeid': 1698163222796, 'clientorderid': '43043F1698163222364I0L64', 'price': '33678.8', 'quantity': '21.245', 'commission': '715.506106', 'commissionasset': 'USDT', 'tradetime': 1698163222796, 'tradetype': 'usdt', 'gatetype': 'simulator', 'handletime': 1698163222796}], 'gatetype': 'simulator', 'handletime': 0}
127.0.0.1 - - [25/Oct/2023 00:00:28] "POST / HTTP/1.1" 200 -
2023-10-25 00:00:28,414:INFO:logic:main.py:661:handleOrderNew:2218526: handleOrderNew: data=OrderType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'clientorderid': '43044F1698163227932I0L64', 'symbol': 'BTCUSDT', 'gatewayorderid': 1698163228380512, 'quantity': '21.191', 'price': '33684.9', 'stopprice': '0', 'ordertype': '', 'side': 'SELL', 'status': 'FILLED', 'positionside': 'SHORT', 'createtime': 1698163227440, 'updatetime': 1698163228380, 'tradetype': 'usdt', 'selfid': 43044, 'filltrades': [TradeType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'tradeid': 1698163228380, 'clientorderid': '43044F1698163227932I0L64', 'price': '33684.9', 'quantity': '21.191', 'commission': '713.8167159', 'commissionasset': 'USDT', 'tradetime': 1698163228380, 'tradetype': 'usdt', 'gatetype': 'simulator', 'handletime': 1698163228380}], 'gatetype': 'simulator', 'handletime': 0}
127.0.0.1 - - [25/Oct/2023 00:00:28] "POST / HTTP/1.1" 200 -
2023-10-25 00:00:28,567:INFO:logic:main.py:664:handleOrderFilled:2218526: handleOrderFilled: data=OrderType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'clientorderid': '43044F1698163227932I0L64', 'symbol': 'BTCUSDT', 'gatewayorderid': 1698163228380512, 'quantity': '21.191', 'price': '33684.9', 'stopprice': '0', 'ordertype': '', 'side': 'SELL', 'status': 'FILLED', 'positionside': 'SHORT', 'createtime': 1698163227440, 'updatetime': 1698163228380, 'tradetype': 'usdt', 'selfid': 43044, 'filltrades': [TradeType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'tradeid': 1698163228380, 'clientorderid': '43044F1698163227932I0L64', 'price': '33684.9', 'quantity': '21.191', 'commission': '713.8167159', 'commissionasset': 'USDT', 'tradetime': 1698163228380, 'tradetype': 'usdt', 'gatetype': 'simulator', 'handletime': 1698163228380}], 'gatetype': 'simulator', 'handletime': 0}


## /root/FIL/strategy/modifiedmom/log.txt ----- -----


--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=23543 

self.closeSec=1698161399, self.tradeDate='20231024', self.openTime='232000', self.closeTime='232959', self.symbol='BTCUSDT', self.open='34027.2', self.close='33616.5'
127.0.0.1 - - [24/Oct/2023 23:30:01] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [24/Oct/2023 23:40:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=23544 

self.closeSec=1698161999, self.tradeDate='20231024', self.openTime='233000', self.closeTime='233959', self.symbol='BTCUSDT', self.open='33609.6', self.close='33319.3'

--handleKline--: 127.0.0.1 - - [24/Oct/2023 23:50:01] "POST / HTTP/1.1" 200 -
 self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=23545 

self.closeSec=1698162599, self.tradeDate='20231024', self.openTime='234000', self.closeTime='234959', self.symbol='BTCUSDT', self.open='33292.9', self.close='33786'
127.0.0.1 - - [25/Oct/2023 00:00:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=23546 

self.closeSec=1698163199, self.tradeDate='20231024', self.openTime='235000', self.closeTime='235959', self.symbol='BTCUSDT', self.open='33774.8', self.close='33673.9'

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=23547 

self.closeSec=1698163799, self.tradeDate='20231025', self.openTime='000000', self.closeTime='000959', self.symbol='BTCUSDT', self.open='33673.9', self.close='33790'
127.0.0.1 - - [25/Oct/2023 00:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=23548 

self.closeSec=1698164399, self.tradeDate='20231025', self.openTime='001000', self.closeTime='001959', self.symbol='BTCUSDT', self.open='33803.3', self.close='33858.8'
127.0.0.1 - - [25/Oct/2023 00:20:05] "POST / HTTP/1.1" 200 -


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

127.0.0.1 - - [24/Oct/2023 23:30:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=23546 

self.closeSec=1698161399, self.tradeDate='20231024', self.openTime='232000', self.closeTime='232959', self.symbol='BTCUSDT', self.open='34027.2', self.close='33616.5'

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=23547 

self.closeSec=1698161999, self.tradeDate='20231024', self.openTime='233000', self.closeTime='233959', self.symbol='BTCUSDT', self.open='33609.6', self.close='33319.3'
127.0.0.1 - - [24/Oct/2023 23:40:01] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [24/Oct/2023 23:50:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=23548 

self.closeSec=1698162599, self.tradeDate='20231024', self.openTime='234000', self.closeTime='234959', self.symbol='BTCUSDT', self.open='33292.9', self.close='33786'

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=23549 

self.closeSec=1698163199, self.tradeDate='20231024', self.openTime='235000', self.closeTime='235959', self.symbol='BTCUSDT', self.open='33774.8', self.close='33673.9'
127.0.0.1 - - [25/Oct/2023 00:00:01] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [25/Oct/2023 00:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=23550 

self.closeSec=1698163799, self.tradeDate='20231025', self.openTime='000000', self.closeTime='000959', self.symbol='BTCUSDT', self.open='33673.9', self.close='33790'

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=23551 

self.closeSec=1698164399, self.tradeDate='20231025', self.openTime='001000', self.closeTime='001959', self.symbol='BTCUSDT', self.open='33803.3', self.close='33858.8'
127.0.0.1 - - [25/Oct/2023 00:20:05] "POST / HTTP/1.1" 200 -


## /root/FIL/strategy/similarity/log.txt ----- -----

127.0.0.1 - - [24/Oct/2023 23:30:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=23546 

self.closeSec=1698161399, self.tradeDate='20231024', self.openTime='232000', self.closeTime='232959', self.symbol='BTCUSDT', self.open='34027.2', self.close='33616.5'
127.0.0.1 - - [24/Oct/2023 23:40:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=23547 

self.closeSec=1698161999, self.tradeDate='20231024', self.openTime='233000', self.closeTime='233959', self.symbol='BTCUSDT', self.open='33609.6', self.close='33319.3'

--handleKline--:  127.0.0.1 - - [24/Oct/2023 23:50:01] "POST / HTTP/1.1" 200 -
self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=23548 

self.closeSec=1698162599, self.tradeDate='20231024', self.openTime='234000', self.closeTime='234959', self.symbol='BTCUSDT', self.open='33292.9', self.close='33786'

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=23549 

self.closeSec=1698163199, self.tradeDate='20231024', self.openTime='235000', self.closeTime='235959', self.symbol='BTCUSDT', self.open='33774.8', self.close='33673.9'
127.0.0.1 - - [25/Oct/2023 00:00:01] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [25/Oct/2023 00:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=23550 

self.closeSec=1698163799, self.tradeDate='20231025', self.openTime='000000', self.closeTime='000959', self.symbol='BTCUSDT', self.open='33673.9', self.close='33790'

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=23551 

self.closeSec=1698164399, self.tradeDate='20231025', self.openTime='001000', self.closeTime='001959', self.symbol='BTCUSDT', self.open='33803.3', self.close='33858.8'
127.0.0.1 - - [25/Oct/2023 00:20:05] "POST / HTTP/1.1" 200 -


## /root/FIL/strategy/sr_min/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=1, self.total=996015.990996, self.flagDict['side']='buy', self.tradeCount=1, self.count=47092
self.closeSec=1698164399, self.tradeDate='20231025', self.openTime='001500', self.closeTime='001959', self.symbol='BTCUSDT', self.open=33881.4, self.close=33858.8, self.high=33954.6, self.low=33789.6, self.vol=3933.403, self.amt=133229011.1182 
127.0.0.1 - - [25/Oct/2023 00:20:03] "POST / HTTP/1.1" 200 -
2023-10-25 00:20:06,376:INFO:sr_min:main.py:172:handleKline:2219263: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5759  20231024   235500    235959  ...         0.0        0.0       0
5760  20231025   000000    000459  ...         0.0        0.0       0
5761  20231025   000500    000959  ...         0.0        0.0       0
5762  20231025   001000    001459  ...         0.0        0.0       0
5763  20231025   001500    001959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-10-25 00:20:06,382:INFO:sr_min:main.py:175:handleKline:2219263: self.closeSec=1698164399, self.tradeDate='20231025', self.openTime='001500', self.closeTime='001959',self.symbol='BTCUSDT',self.open=33881.4, self.close=33858.8, self.high=33954.6, self.low=33789.6, self.vol=3933.403, self.amt=133229011.1182, ukdf['pct'].iloc[-1]=0.000165 , ukdf['amount'].iloc[-1]=133229011.1182, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5763, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '37.141', 'enterprice': '26844', 'countrevence': '0', 'unrealprofit': '260172.93478431021', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '33849.00618681', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=1
--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=1, self.total=996015.990996, self.flagDict['side']='buy', self.tradeCount=1, self.count=47093
self.closeSec=1698164699, self.tradeDate='20231025', self.openTime='002000', self.closeTime='002459', self.symbol='BTCUSDT', self.open=33856.9, self.close=33880.0, self.high=33940.0, self.low=33812.2, self.vol=2345.654, self.amt=79449616.3739 
127.0.0.1 - - [25/Oct/2023 00:25:01] "POST / HTTP/1.1" 200 -
2023-10-25 00:25:03,295:INFO:sr_min:main.py:172:handleKline:2219263: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5760  20231025   000000    000459  ...         0.0        0.0       0
5761  20231025   000500    000959  ...         0.0        0.0       0
5762  20231025   001000    001459  ...         0.0        0.0       0
5763  20231025   001500    001959  ...         0.0        0.0       0
5764  20231025   002000    002459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-10-25 00:25:03,305:INFO:sr_min:main.py:175:handleKline:2219263: self.closeSec=1698164699, self.tradeDate='20231025', self.openTime='002000', self.closeTime='002459',self.symbol='BTCUSDT',self.open=33856.9, self.close=33880.0, self.high=33940.0, self.low=33812.2, self.vol=2345.654, self.amt=79449616.3739, ukdf['pct'].iloc[-1]=0.000626 , ukdf['amount'].iloc[-1]=79449616.3739, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5764, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '37.141', 'enterprice': '26844', 'countrevence': '0', 'unrealprofit': '261029.57773247823', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '33872.07080403', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=1


## /root/FIL/strategy/s_rsrs/log.txt ----- -----

723  20231024   120000    155959  1698134399  ...    723  1.695636  1.365441     1.0
724  20231024   160000    195959  1698148799  ...    724  1.405727  0.901744     1.0

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '41.361', 'enterprice': '29539.2', 'countrevence': '0', 'unrealprofit': '207081.05655241527', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '34545.87432007', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=1, self.sign=1
127.0.0.1 - - [25/Oct/2023 00:00:01] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='s_rsrs', self.symbol='BTCUSDT', interval='4h', intervalSec=14400, wid=25, thd=0.6, self.sign=1, self.total=1220549.0803488, self.flagDict['side']='buy', self.tradeCount=37, self.count=981
self.closeSec=1698163199, self.tradeDate='20231024', self.openTime='200000', self.closeTime='235959', self.symbol='BTCUSDT', self.open=34549.9, self.close=33675.6, self.high=34849.4, self.low=33244.0, self.vol=208256.417, self.amt=7087042411.49646 
2023-10-25 00:00:01,576:INFO:s_rsrs:main.py:141:handleKline:2218689: self.closeSec=1698163199, self.tradeDate='20231024', self.openTime='200000', self.closeTime='235959',self.symbol='BTCUSDT',self.open=34549.9, self.close=33675.6, self.high=34849.4, self.low=33244.0, self.vol=208256.417, self.amt=7087042411.49646 
2023-10-25 00:00:01,596:INFO:s_rsrs:main.py:142:handleKline:2218689: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime  ...         vol           amt       pct
721  20231024   040000    075959  ...  377945.899  1.239992e+10  0.055375
722  20231024   080000    115959  ...  281261.831  9.615855e+09  0.030008
723  20231024   120000    155959  ...  120908.224  4.124627e+09 -0.001212
724  20231024   160000    195959  ...  105260.938  3.621561e+09  0.015403
725  20231024   200000    235959  ...  208256.417  7.087042e+09 -0.025305

[5 rows x 11 columns]
2023-10-25 00:00:02,429:INFO:s_rsrs:main.py:151:handleKline:2218689: df_s.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec  ...  index      beta    zscore  signal
721  20231024   040000    075959  1698105599  ...    721  2.431451  2.654970     1.0
722  20231024   080000    115959  1698119999  ...    722  2.469821  2.587041     1.0
723  20231024   120000    155959  1698134399  ...    723  1.695636  1.365441     1.0
724  20231024   160000    195959  1698148799  ...    724  1.405727  0.901744     1.0
725  20231024   200000    235959  1698163199  ...    725  1.481802  0.996100     1.0

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '41.361', 'enterprice': '29539.2', 'countrevence': '0', 'unrealprofit': '170823.33363785043', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '33669.25811363', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=1, self.sign=1


