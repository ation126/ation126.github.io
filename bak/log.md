# 20231006 00:26:01

## /root/FIL/strategy/amihud/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=373746.4768026, self.flagDict['side']='sell', self.tradeCount=2, self.count=41620
self.closeSec=1696522799, self.tradeDate='20231006', self.openTime='001500', self.closeTime='001959', self.symbol='BTCUSDT', self.open=27473.5, self.close=27475.1, self.high=27506.6, self.low=27431.7, self.vol=2463.56, self.amt=67681147.1176 
127.0.0.1 - - [06/Oct/2023 00:20:02] "POST / HTTP/1.1" 200 -
2023-10-06 00:20:06,091:INFO:amihud:main.py:172:handleKline:2219019: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5759  20231005   235500    235959  ...         0.0        0.0       0
5760  20231006   000000    000459  ...         0.0        0.0       0
5761  20231006   000500    000959  ...         0.0        0.0       0
5762  20231006   001000    001459  ...         0.0        0.0       0
5763  20231006   001500    001959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-10-06 00:20:06,102:INFO:amihud:main.py:175:handleKline:2219019: self.closeSec=1696522799, self.tradeDate='20231006', self.openTime='001500', self.closeTime='001959',self.symbol='BTCUSDT',self.open=27473.5, self.close=27475.1, self.high=27506.6, self.low=27431.7, self.vol=2463.56, self.amt=67681147.1176, ukdf['pct'].iloc[-1]=0.000186 , ukdf['amount'].iloc[-1]=67681147.1176, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5763, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '13.926', 'enterprice': '26864.9', 'countrevence': '0', 'unrealprofit': '-8509.23147895326', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '27475.93198901', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1
127.0.0.1 - - [06/Oct/2023 00:25:00] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=373746.4768026, self.flagDict['side']='sell', self.tradeCount=2, self.count=41621
self.closeSec=1696523099, self.tradeDate='20231006', self.openTime='002000', self.closeTime='002459', self.symbol='BTCUSDT', self.open=27478.6, self.close=27425.3, self.high=27507.0, self.low=27421.3, self.vol=2966.426, self.amt=81472789.1669 
2023-10-06 00:25:00,795:INFO:amihud:main.py:172:handleKline:2219019: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5760  20231006   000000    000459  ...         0.0        0.0       0
5761  20231006   000500    000959  ...         0.0        0.0       0
5762  20231006   001000    001459  ...         0.0        0.0       0
5763  20231006   001500    001959  ...         0.0        0.0       0
5764  20231006   002000    002459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-10-06 00:25:00,795:INFO:amihud:main.py:175:handleKline:2219019: self.closeSec=1696523099, self.tradeDate='20231006', self.openTime='002000', self.closeTime='002459',self.symbol='BTCUSDT',self.open=27478.6, self.close=27425.3, self.high=27507.0, self.low=27421.3, self.vol=2966.426, self.amt=81472789.1669, ukdf['pct'].iloc[-1]=-0.001813 , ukdf['amount'].iloc[-1]=81472789.1669, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5764, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '13.926', 'enterprice': '26864.9', 'countrevence': '0', 'unrealprofit': '-7772.26245785946', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '27423.01162271', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1


## /root/FIL/strategy/factorcheck/log.txt ----- -----

self.closeSec=1696521899, self.tradeDate='20231006', self.openTime='000000', self.closeTime='000459', self.symbol='BTCUSDT', self.open=27540.0, self.close=27519.9, self.high=27609.9, self.low=27509.4 

--ukdf-hist--: overDate='20231001' 
 Empty DataFrame
Columns: [tradeDate, openTime, closeTime, closeSec, open, close, high, low, pct, index, idx]
Index: [] 
 Empty DataFrame
Columns: [tradeDate, openTime, closeTime, closeSec, open, close, high, low, pct, index, idx]
Index: [] 

127.0.0.1 - - [06/Oct/2023 00:10:00] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.714181719035411, self.count=41620 

self.closeSec=1696522199, self.tradeDate='20231006', self.openTime='000500', self.closeTime='000959', self.symbol='BTCUSDT', self.open=27519.2, self.close=27419.6, self.high=27524.4, self.low=27380.0 

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.714181719035411, self.count=41621 

self.closeSec=1696522499, self.tradeDate='20231006', self.openTime='001000', self.closeTime='001459', self.symbol='BTCUSDT', self.open=27407.0, self.close=27470.0, self.high=27497.0, self.low=27350.0 
127.0.0.1 - - [06/Oct/2023 00:15:00] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.714181719035411, self.count=41622 

self.closeSec=1696522799, self.tradeDate='20231006', self.openTime='001500', self.closeTime='001959', self.symbol='BTCUSDT', self.open=27473.5, self.close=27475.1, self.high=27506.6, self.low=27431.7 
127.0.0.1 - - [06/Oct/2023 00:20:02] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.714181719035411, self.count=41623127.0.0.1 - - [06/Oct/2023 00:25:00] "POST / HTTP/1.1" 200 -
 

self.closeSec=1696523099, self.tradeDate='20231006', self.openTime='002000', self.closeTime='002459', self.symbol='BTCUSDT', self.open=27478.6, self.close=27425.3, self.high=27507.0, self.low=27421.3 


## /root/FIL/strategy/logic/log.txt ----- -----

     pred    prob_0    prob_1  actual  ...       nav  sign   cost_        bm
539     0  0.586041  0.413959       0  ...  0.956573   1.0 -0.0016  1.053637
540     0  0.506624  0.493376       1  ...  0.958834   1.0  0.0000  1.056127
541     0  0.532796  0.467204       0  ...  0.955445   1.0  0.0000  1.052395
542     1  0.485657  0.514343       0  ...  0.945519   1.0  0.0000  1.041461
543     1  0.419002  0.580998       0  ...  0.947877  -1.0 -0.0016  1.037198

[5 rows x 10 columns]
2023-10-06 00:00:20,931:INFO:logic:main.py:478:getModel:2218526: df_panel.iloc[-5:,:] :
    pred    prob_0    prob_1  actual  ...       nav  sign   cost_        bm
45     0  0.585958  0.414042       0  ...  0.956573   1.0 -0.0016  1.053776
46     0  0.506843  0.493157       1  ...  0.958834   1.0  0.0000  1.056700
47     0  0.532727  0.467273       0  ...  0.955445   1.0  0.0000  1.052593
48     1  0.485830  0.514170       0  ...  0.945519   1.0  0.0000  1.041658
49     1  0.419002  0.580998       0  ...  0.947877  -1.0 -0.0016  1.037198

[5 rows x 10 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '24.419', 'enterprice': '27985', 'countrevence': '0', 'unrealprofit': '-10837.1522', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '27541.2', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
handlebackTrade > queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '24.419', 'enterprice': '27985', 'countrevence': '0', 'unrealprofit': '-10837.1522', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '27541.2', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
2023-10-06 00:00:27,690:INFO:logic:main.py:500:queryContractAssets:2218526: queryContractAssets: assets=ContractAssetReturn{'result': [ContractAsset{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'asset': 'USDT', 'free': '673615.8297635', 'total': '673615.8297635', 'margin': '0', 'unreal': '0', 'type': 'AssetType_ucontract'}]}
2023-10-06 00:00:28,153:INFO:logic:main.py:587:openSell:2218526: ret = self.client.insertMarketUOrder("simulator", "BTCUSDT", 24.386, "sell"), ret=InsertOrderReturn{'result': 'success', 'clientorderid': '42990F1696521628152I0L64'}
2023-10-06 00:00:28,170:INFO:logic:main.py:494:insertFactor:2218526: curDateTime:10060000, name:logic, symbol:BTCUSDT, tradeDate:20231005, closeTime:235959, close:27540.1, sign:-1, total:673615.8297635, side:sell  
127.0.0.1 - - [06/Oct/2023 00:00:28] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [06/Oct/2023 00:00:28] "POST / HTTP/1.1" 200 -
2023-10-06 00:00:28,172:INFO:logic:main.py:661:handleOrderNew:2218526: handleOrderNew: data=OrderType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'clientorderid': '42989F1696521622629I0L64', 'symbol': 'BTCUSDT', 'gatewayorderid': 1696521623034285, 'quantity': '24.419', 'price': '27537.3', 'stopprice': '0', 'ordertype': '', 'side': 'SELL', 'status': 'FILLED', 'positionside': 'SHORT', 'createtime': 1696521621779, 'updatetime': 1696521623034, 'tradetype': 'usdt', 'selfid': 42989, 'filltrades': [TradeType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'tradeid': 1696521623034, 'clientorderid': '42989F1696521622629I0L64', 'price': '27537.3', 'quantity': '24.419', 'commission': '672.4333287', 'commissionasset': 'USDT', 'tradetime': 1696521623034, 'tradetype': 'usdt', 'gatetype': 'simulator', 'handletime': 1696521623034}], 'gatetype': 'simulator', 'handletime': 0}
2023-10-06 00:00:28,172:INFO:logic:main.py:664:handleOrderFilled:2218526: handleOrderFilled: data=OrderType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'clientorderid': '42989F1696521622629I0L64', 'symbol': 'BTCUSDT', 'gatewayorderid': 1696521623034285, 'quantity': '24.419', 'price': '27537.3', 'stopprice': '0', 'ordertype': '', 'side': 'SELL', 'status': 'FILLED', 'positionside': 'SHORT', 'createtime': 1696521621779, 'updatetime': 1696521623034, 'tradetype': 'usdt', 'selfid': 42989, 'filltrades': [TradeType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'tradeid': 1696521623034, 'clientorderid': '42989F1696521622629I0L64', 'price': '27537.3', 'quantity': '24.419', 'commission': '672.4333287', 'commissionasset': 'USDT', 'tradetime': 1696521623034, 'tradetype': 'usdt', 'gatetype': 'simulator', 'handletime': 1696521623034}], 'gatetype': 'simulator', 'handletime': 0}
127.0.0.1 - - [06/Oct/2023 00:00:28] "POST / HTTP/1.1" 200 -
2023-10-06 00:00:28,595:INFO:logic:main.py:661:handleOrderNew:2218526: handleOrderNew: data=OrderType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'clientorderid': '42990F1696521628152I0L64', 'symbol': 'BTCUSDT', 'gatewayorderid': 1696521628562218, 'quantity': '24.386', 'price': '27541.7', 'stopprice': '0', 'ordertype': '', 'side': 'SELL', 'status': 'FILLED', 'positionside': 'SHORT', 'createtime': 1696521627701, 'updatetime': 1696521628562, 'tradetype': 'usdt', 'selfid': 42990, 'filltrades': [TradeType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'tradeid': 1696521628562, 'clientorderid': '42990F1696521628152I0L64', 'price': '27541.7', 'quantity': '24.386', 'commission': '671.6318962', 'commissionasset': 'USDT', 'tradetime': 1696521628562, 'tradetype': 'usdt', 'gatetype': 'simulator', 'handletime': 1696521628562}], 'gatetype': 'simulator', 'handletime': 0}
127.0.0.1 - - [06/Oct/2023 00:00:28] "POST / HTTP/1.1" 200 -
2023-10-06 00:00:28,718:INFO:logic:main.py:664:handleOrderFilled:2218526: handleOrderFilled: data=OrderType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'clientorderid': '42990F1696521628152I0L64', 'symbol': 'BTCUSDT', 'gatewayorderid': 1696521628562218, 'quantity': '24.386', 'price': '27541.7', 'stopprice': '0', 'ordertype': '', 'side': 'SELL', 'status': 'FILLED', 'positionside': 'SHORT', 'createtime': 1696521627701, 'updatetime': 1696521628562, 'tradetype': 'usdt', 'selfid': 42990, 'filltrades': [TradeType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'tradeid': 1696521628562, 'clientorderid': '42990F1696521628152I0L64', 'price': '27541.7', 'quantity': '24.386', 'commission': '671.6318962', 'commissionasset': 'USDT', 'tradetime': 1696521628562, 'tradetype': 'usdt', 'gatetype': 'simulator', 'handletime': 1696521628562}], 'gatetype': 'simulator', 'handletime': 0}


## /root/FIL/strategy/modifiedmom/log.txt ----- -----

127.0.0.1 - - [05/Oct/2023 23:30:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=20807 

self.closeSec=1696519799, self.tradeDate='20231005', self.openTime='232000', self.closeTime='232959', self.symbol='BTCUSDT', self.open='27804.2', self.close='27653.3'

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=20808 

self.closeSec=1696520399, self.tradeDate='20231005', self.openTime='233000', self.closeTime='233959', self.symbol='BTCUSDT', self.open='27653.3', self.close='27534.4'
127.0.0.1 - - [05/Oct/2023 23:40:01] "POST / HTTP/1.1" 200 -

--handleKline--:  127.0.0.1 - - [05/Oct/2023 23:50:01] "POST / HTTP/1.1" 200 -
self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=20809 

self.closeSec=1696520999, self.tradeDate='20231005', self.openTime='234000', self.closeTime='234959', self.symbol='BTCUSDT', self.open='27538.3', self.close='27594.8'

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=20810 

self.closeSec=1696521599, self.tradeDate='20231005', self.openTime='235000', self.closeTime='235959', self.symbol='BTCUSDT', self.open='27592.8', self.close='27540.1'
127.0.0.1 - - [06/Oct/2023 00:00:02] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [06/Oct/2023 00:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=20811 

self.closeSec=1696522199, self.tradeDate='20231006', self.openTime='000000', self.closeTime='000959', self.symbol='BTCUSDT', self.open='27540', self.close='27419.6'

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=20812 

self.closeSec=1696522799, self.tradeDate='20231006', self.openTime='001000', self.closeTime='001959', self.symbol='BTCUSDT', self.open='27407', self.close='27475.1'
127.0.0.1 - - [06/Oct/2023 00:20:04] "POST / HTTP/1.1" 200 -


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

127.0.0.1 - - [05/Oct/2023 23:30:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=20810 

self.closeSec=1696519799, self.tradeDate='20231005', self.openTime='232000', self.closeTime='232959', self.symbol='BTCUSDT', self.open='27804.2', self.close='27653.3'
127.0.0.1 - - [05/Oct/2023 23:40:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=20811 

self.closeSec=1696520399, self.tradeDate='20231005', self.openTime='233000', self.closeTime='233959', self.symbol='BTCUSDT', self.open='27653.3', self.close='27534.4'

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=20812 

self.closeSec=1696520999, self.tradeDate='20231005', self.openTime='234000', self.closeTime='234959', self.symbol='BTCUSDT', self.open='27538.3', self.close='27594.8'
127.0.0.1 - - [05/Oct/2023 23:50:01] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [06/Oct/2023 00:00:02] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=20813 

self.closeSec=1696521599, self.tradeDate='20231005', self.openTime='235000', self.closeTime='235959', self.symbol='BTCUSDT', self.open='27592.8', self.close='27540.1'

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=20814 

self.closeSec=1696522199, self.tradeDate='20231006', self.openTime='000000', self.closeTime='000959', self.symbol='BTCUSDT', self.open='27540', self.close='27419.6'
127.0.0.1 - - [06/Oct/2023 00:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=20815 

self.closeSec=1696522799, self.tradeDate='20231006', self.openTime='001000', self.closeTime='001959', self.symbol='BTCUSDT', self.open='27407', self.close='27475.1'
127.0.0.1 - - [06/Oct/2023 00:20:04] "POST / HTTP/1.1" 200 -


## /root/FIL/strategy/similarity/log.txt ----- -----

127.0.0.1 - - [05/Oct/2023 23:30:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=20810 

self.closeSec=1696519799, self.tradeDate='20231005', self.openTime='232000', self.closeTime='232959', self.symbol='BTCUSDT', self.open='27804.2', self.close='27653.3'

--handleKline--: 127.0.0.1 - - [05/Oct/2023 23:40:01] "POST / HTTP/1.1" 200 -
 self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=20811 

self.closeSec=1696520399, self.tradeDate='20231005', self.openTime='233000', self.closeTime='233959', self.symbol='BTCUSDT', self.open='27653.3', self.close='27534.4'
127.0.0.1 - - [05/Oct/2023 23:50:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=20812 

self.closeSec=1696520999, self.tradeDate='20231005', self.openTime='234000', self.closeTime='234959', self.symbol='BTCUSDT', self.open='27538.3', self.close='27594.8'

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=20813 

self.closeSec=1696521599, self.tradeDate='20231005', self.openTime='235000', self.closeTime='235959', self.symbol='BTCUSDT', self.open='27592.8', self.close='27540.1'
127.0.0.1 - - [06/Oct/2023 00:00:02] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=20814 

self.closeSec=1696522199, self.tradeDate='20231006', self.openTime='000000', self.closeTime='000959', self.symbol='BTCUSDT', self.open='27540', self.close='27419.6'
127.0.0.1 - - [06/Oct/2023 00:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=20815 

self.closeSec=1696522799, self.tradeDate='20231006', self.openTime='001000', self.closeTime='001959', self.symbol='BTCUSDT', self.open='27407', self.close='27475.1'
127.0.0.1 - - [06/Oct/2023 00:20:04] "POST / HTTP/1.1" 200 -


## /root/FIL/strategy/sr_min/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=1, self.total=996015.990996, self.flagDict['side']='buy', self.tradeCount=1, self.count=41620
self.closeSec=1696522799, self.tradeDate='20231006', self.openTime='001500', self.closeTime='001959', self.symbol='BTCUSDT', self.open=27473.5, self.close=27475.1, self.high=27506.6, self.low=27431.7, self.vol=2463.56, self.amt=67681147.1176 
127.0.0.1 - - [06/Oct/2023 00:20:02] "POST / HTTP/1.1" 200 -
2023-10-06 00:20:06,099:INFO:sr_min:main.py:172:handleKline:2219263: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5759  20231005   235500    235959  ...         0.0        0.0       0
5760  20231006   000000    000459  ...         0.0        0.0       0
5761  20231006   000500    000959  ...         0.0        0.0       0
5762  20231006   001000    001459  ...         0.0        0.0       0
5763  20231006   001500    001959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-10-06 00:20:06,109:INFO:sr_min:main.py:175:handleKline:2219263: self.closeSec=1696522799, self.tradeDate='20231006', self.openTime='001500', self.closeTime='001959',self.symbol='BTCUSDT',self.open=27473.5, self.close=27475.1, self.high=27506.6, self.low=27431.7, self.vol=2463.56, self.amt=67681147.1176, ukdf['pct'].iloc[-1]=0.000186 , ukdf['amount'].iloc[-1]=67681147.1176, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5763, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '37.141', 'enterprice': '26844', 'countrevence': '0', 'unrealprofit': '23470.58600382041', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '27475.93198901', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=1
127.0.0.1 - - [06/Oct/2023 00:25:00] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=1, self.total=996015.990996, self.flagDict['side']='buy', self.tradeCount=1, self.count=41621
self.closeSec=1696523099, self.tradeDate='20231006', self.openTime='002000', self.closeTime='002459', self.symbol='BTCUSDT', self.open=27478.6, self.close=27425.3, self.high=27507.0, self.low=27421.3, self.vol=2966.426, self.amt=81472789.1669 
2023-10-06 00:25:00,801:INFO:sr_min:main.py:172:handleKline:2219263: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5760  20231006   000000    000459  ...         0.0        0.0       0
5761  20231006   000500    000959  ...         0.0        0.0       0
5762  20231006   001000    001459  ...         0.0        0.0       0
5763  20231006   001500    001959  ...         0.0        0.0       0
5764  20231006   002000    002459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-10-06 00:25:00,802:INFO:sr_min:main.py:175:handleKline:2219263: self.closeSec=1696523099, self.tradeDate='20231006', self.openTime='002000', self.closeTime='002459',self.symbol='BTCUSDT',self.open=27478.6, self.close=27425.3, self.high=27507.0, self.low=27421.3, self.vol=2966.426, self.amt=81472789.1669, ukdf['pct'].iloc[-1]=-0.001813 , ukdf['amount'].iloc[-1]=81472789.1669, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5764, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '37.141', 'enterprice': '26844', 'countrevence': '0', 'unrealprofit': '21505.07067907211', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '27423.01162271', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=1


## /root/FIL/strategy/s_rsrs/log.txt ----- -----

721  20231005   040000    075959  ...   34252.297  9.490155e+08  0.005604
722  20231005   080000    115959  ...   34795.969  9.651662e+08 -0.004373
723  20231005   120000    155959  ...   23302.294  6.435468e+08 -0.001552
724  20231005   160000    195959  ...   26856.381  7.432812e+08  0.004178
725  20231005   200000    235959  ...  182212.597  5.068501e+09 -0.006160

[5 rows x 11 columns]
2023-10-06 00:00:02,326:INFO:s_rsrs:main.py:151:handleKline:2218689: df_s.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec  ...  index      beta    zscore  signal
721  20231005   040000    075959  1696463999  ...    721  0.842262  0.259653     NaN
722  20231005   080000    115959  1696478399  ...    722  0.758658  0.072150     NaN
723  20231005   120000    155959  1696492799  ...    723  0.646229 -0.194907     NaN
724  20231005   160000    195959  1696507199  ...    724  0.553523 -0.416799     NaN
725  20231005   200000    235959  1696521599  ...    725  0.468945 -0.620412    -1.0

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '43.732', 'enterprice': '28015.5', 'countrevence': '0', 'unrealprofit': '-20794.566', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '27540', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-1, self.sign=1
handlebackTrade > queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '43.732', 'enterprice': '28015.5', 'countrevence': '0', 'unrealprofit': '-20886.4032', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '27537.9', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
2023-10-06 00:00:09,111:INFO:s_rsrs:main.py:182:queryContractAssets:2218689: queryContractAssets: assets=ContractAssetReturn{'result': [ContractAsset{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'asset': 'USDT', 'free': '1207312.6243652', 'total': '1207312.6243652', 'margin': '0', 'unreal': '0', 'type': 'AssetType_ucontract'}]}
2023-10-06 00:00:09,616:INFO:s_rsrs:main.py:269:openSell:2218689: ret = self.client.insertMarketUOrder("simulator", "BTCUSDT", 43.706, "sell"), ret=InsertOrderReturn{'result': 'success', 'clientorderid': '42988F1696521609614I0L65'}
2023-10-06 00:00:09,641:INFO:s_rsrs:main.py:176:insertFactor:2218689: curDateTime:10060000, name:s_rsrs, symbol:BTCUSDT, tradeDate:20231005, closeTime:235959, close:27540.0, sign:-1, total:1207312.6243652, side:sell  
127.0.0.1 - - [06/Oct/2023 00:00:09] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [06/Oct/2023 00:00:09] "POST / HTTP/1.1" 200 -
2023-10-06 00:00:09,643:INFO:s_rsrs:main.py:343:handleOrderNew:2218689: handleOrderNew: data=OrderType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'clientorderid': '42987F1696521604033I0L65', 'symbol': 'BTCUSDT', 'gatewayorderid': 1696521604429911, 'quantity': '43.732', 'price': '27537.6', 'stopprice': '0', 'ordertype': '', 'side': 'SELL', 'status': 'FILLED', 'positionside': 'SHORT', 'createtime': 1696521603171, 'updatetime': 1696521604429, 'tradetype': 'usdt', 'selfid': 42987, 'filltrades': [TradeType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'tradeid': 1696521604429, 'clientorderid': '42987F1696521604033I0L65', 'price': '27537.6', 'quantity': '43.732', 'commission': '1204.2743232', 'commissionasset': 'USDT', 'tradetime': 1696521604429, 'tradetype': 'usdt', 'gatetype': 'simulator', 'handletime': 1696521604429}], 'gatetype': 'simulator', 'handletime': 0}
2023-10-06 00:00:09,646:INFO:s_rsrs:main.py:346:handleOrderFilled:2218689: handleOrderFilled: data=OrderType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'clientorderid': '42987F1696521604033I0L65', 'symbol': 'BTCUSDT', 'gatewayorderid': 1696521604429911, 'quantity': '43.732', 'price': '27537.6', 'stopprice': '0', 'ordertype': '', 'side': 'SELL', 'status': 'FILLED', 'positionside': 'SHORT', 'createtime': 1696521603171, 'updatetime': 1696521604429, 'tradetype': 'usdt', 'selfid': 42987, 'filltrades': [TradeType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'tradeid': 1696521604429, 'clientorderid': '42987F1696521604033I0L65', 'price': '27537.6', 'quantity': '43.732', 'commission': '1204.2743232', 'commissionasset': 'USDT', 'tradetime': 1696521604429, 'tradetype': 'usdt', 'gatetype': 'simulator', 'handletime': 1696521604429}], 'gatetype': 'simulator', 'handletime': 0}
127.0.0.1 - - [06/Oct/2023 00:00:10] "POST / HTTP/1.1" 200 -
2023-10-06 00:00:10,083:INFO:s_rsrs:main.py:343:handleOrderNew:2218689: handleOrderNew: data=OrderType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'clientorderid': '42988F1696521609614I0L65', 'symbol': 'BTCUSDT', 'gatewayorderid': 1696521610027120, 'quantity': '43.706', 'price': '27536.4', 'stopprice': '0', 'ordertype': '', 'side': 'SELL', 'status': 'FILLED', 'positionside': 'SHORT', 'createtime': 1696521609131, 'updatetime': 1696521610027, 'tradetype': 'usdt', 'selfid': 42988, 'filltrades': [TradeType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'tradeid': 1696521610027, 'clientorderid': '42988F1696521609614I0L65', 'price': '27536.4', 'quantity': '43.706', 'commission': '1203.5058984', 'commissionasset': 'USDT', 'tradetime': 1696521610027, 'tradetype': 'usdt', 'gatetype': 'simulator', 'handletime': 1696521610027}], 'gatetype': 'simulator', 'handletime': 0}
2023-10-06 00:00:10,237:INFO:s_rsrs:main.py:346:handleOrderFilled:2218689: handleOrderFilled: data=OrderType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'clientorderid': '42988F1696521609614I0L65', 'symbol': 'BTCUSDT', 'gatewayorderid': 1696521610027120, 'quantity': '43.706', 'price': '27536.4', 'stopprice': '0', 'ordertype': '', 'side': 'SELL', 'status': 'FILLED', 'positionside': 'SHORT', 'createtime': 1696521609131, 'updatetime': 1696521610027, 'tradetype': 'usdt', 'selfid': 42988, 'filltrades': [TradeType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'tradeid': 1696521610027, 'clientorderid': '42988F1696521609614I0L65', 'price': '27536.4', 'quantity': '43.706', 'commission': '1203.5058984', 'commissionasset': 'USDT', 'tradetime': 1696521610027, 'tradetype': 'usdt', 'gatetype': 'simulator', 'handletime': 1696521610027}], 'gatetype': 'simulator', 'handletime': 0}
127.0.0.1 - - [06/Oct/2023 00:00:10] "POST / HTTP/1.1" 200 -


