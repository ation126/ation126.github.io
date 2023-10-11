# 20231012 00:26:02

## /root/FIL/strategy/amihud/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=373746.4768026, self.flagDict['side']='sell', self.tradeCount=2, self.count=43348
self.closeSec=1697041199, self.tradeDate='20231012', self.openTime='001500', self.closeTime='001959', self.symbol='BTCUSDT', self.open=26737.3, self.close=26689.1, self.high=26737.3, self.low=26662.7, self.vol=3779.52, self.amt=100898277.1754 
127.0.0.1 - - [12/Oct/2023 00:20:09] "POST / HTTP/1.1" 200 -
2023-10-12 00:20:15,792:INFO:amihud:main.py:172:handleKline:2219019: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5759  20231011   235500    235959  ...         0.0        0.0       0
5760  20231012   000000    000459  ...         0.0        0.0       0
5761  20231012   000500    000959  ...         0.0        0.0       0
5762  20231012   001000    001459  ...         0.0        0.0       0
5763  20231012   001500    001959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-10-12 00:20:15,802:INFO:amihud:main.py:175:handleKline:2219019: self.closeSec=1697041199, self.tradeDate='20231012', self.openTime='001500', self.closeTime='001959',self.symbol='BTCUSDT',self.open=26737.3, self.close=26689.1, self.high=26737.3, self.low=26662.7, self.vol=3779.52, self.amt=100898277.1754, ukdf['pct'].iloc[-1]=-0.001806 , ukdf['amount'].iloc[-1]=100898277.1754, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5763, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '13.926', 'enterprice': '26864.9', 'countrevence': '0', 'unrealprofit': '2282.4714', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '26701', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1
127.0.0.1 - - [12/Oct/2023 00:25:00] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=373746.4768026, self.flagDict['side']='sell', self.tradeCount=2, self.count=43349
self.closeSec=1697041499, self.tradeDate='20231012', self.openTime='002000', self.closeTime='002459', self.symbol='BTCUSDT', self.open=26689.2, self.close=26687.8, self.high=26712.2, self.low=26643.0, self.vol=2679.846, self.amt=71480353.4613 
2023-10-12 00:25:00,799:INFO:amihud:main.py:172:handleKline:2219019: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5760  20231012   000000    000459  ...         0.0        0.0       0
5761  20231012   000500    000959  ...         0.0        0.0       0
5762  20231012   001000    001459  ...         0.0        0.0       0
5763  20231012   001500    001959  ...         0.0        0.0       0
5764  20231012   002000    002459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-10-12 00:25:00,799:INFO:amihud:main.py:175:handleKline:2219019: self.closeSec=1697041499, self.tradeDate='20231012', self.openTime='002000', self.closeTime='002459',self.symbol='BTCUSDT',self.open=26689.2, self.close=26687.8, self.high=26712.2, self.low=26643.0, self.vol=2679.846, self.amt=71480353.4613, ukdf['pct'].iloc[-1]=-4.9e-05 , ukdf['amount'].iloc[-1]=71480353.4613, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5764, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '13.926', 'enterprice': '26864.9', 'countrevence': '0', 'unrealprofit': '2484.3984', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '26686.5', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1


## /root/FIL/strategy/factorcheck/log.txt ----- -----

127.0.0.1 - - [12/Oct/2023 00:05:00] "POST / HTTP/1.1" 200 -

--ukdf-hist--: overDate='20231007' 
 Empty DataFrame
Columns: [tradeDate, openTime, closeTime, closeSec, open, close, high, low, pct, index, idx]
Index: [] 
 Empty DataFrame
Columns: [tradeDate, openTime, closeTime, closeSec, open, close, high, low, pct, index, idx]
Index: [] 


--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.714181719035411, self.count=43348 

self.closeSec=1697040599, self.tradeDate='20231012', self.openTime='000500', self.closeTime='000959', self.symbol='BTCUSDT', self.open=26734.5, self.close=26764.0, self.high=26777.4, self.low=26715.0 
127.0.0.1 - - [12/Oct/2023 00:10:00] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.714181719035411, self.count=43349 

self.closeSec=1697040899, self.tradeDate='20231012', self.openTime='001000', self.closeTime='001459', self.symbol='BTCUSDT', self.open=26764.1, self.close=26737.4, self.high=26764.1, self.low=26601.6 
127.0.0.1 - - [12/Oct/2023 00:15:01] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.714181719035411, self.count=43350 

self.closeSec=1697041199, self.tradeDate='20231012', self.openTime='001500', self.closeTime='001959', self.symbol='BTCUSDT', self.open=26737.3, self.close=26689.1, self.high=26737.3, self.low=26662.7 
127.0.0.1 - - [12/Oct/2023 00:20:08] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [12/Oct/2023 00:25:00] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.714181719035411, self.count=43351 

self.closeSec=1697041499, self.tradeDate='20231012', self.openTime='002000', self.closeTime='002459', self.symbol='BTCUSDT', self.open=26689.2, self.close=26687.8, self.high=26712.2, self.low=26643.0 


## /root/FIL/strategy/logic/log.txt ----- -----

     pred    prob_0    prob_1  actual  ...       nav  sign   cost_        bm
539     1  0.474732  0.525268       1  ...  1.007002   1.0  0.0000  1.008051
540     1  0.499776  0.500224       0  ...  1.003561   1.0  0.0000  1.004607
541     1  0.462002  0.537998       1  ...  1.005116   1.0  0.0000  1.006164
542     0  0.503416  0.496584       0  ...  0.995158   1.0  0.0000  0.996196
543     1  0.399553  0.600447       0  ...  0.995181  -1.0 -0.0016  0.994579

[5 rows x 10 columns]
2023-10-12 00:00:21,278:INFO:logic:main.py:478:getModel:2218526: df_panel.iloc[-5:,:] :
    pred    prob_0    prob_1  actual  ...       nav  sign   cost_        bm
45     1  0.474337  0.525663       1  ...  1.007002   1.0  0.0000  1.007793
46     1  0.499368  0.500632       0  ...  1.003561   1.0  0.0000  1.004738
47     1  0.461568  0.538432       1  ...  1.005116   1.0  0.0000  1.005753
48     0  0.502677  0.497323       0  ...  0.995158   1.0  0.0000  0.995789
49     1  0.399553  0.600447       0  ...  0.995181  -1.0 -0.0016  0.994579

[5 rows x 10 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '24.072', 'enterprice': '27245.4', 'countrevence': '0', 'unrealprofit': '-11467.9008', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '26769', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
handlebackTrade > queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '24.072', 'enterprice': '27245.4', 'countrevence': '0', 'unrealprofit': '-11467.9008', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '26769', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
2023-10-12 00:00:28,043:INFO:logic:main.py:500:queryContractAssets:2218526: queryContractAssets: assets=ContractAssetReturn{'result': [ContractAsset{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'asset': 'USDT', 'free': '645802.5993949', 'total': '645802.5993949', 'margin': '0', 'unreal': '0', 'type': 'AssetType_ucontract'}]}
2023-10-12 00:00:28,540:INFO:logic:main.py:587:openSell:2218526: ret = self.client.insertMarketUOrder("simulator", "BTCUSDT", 24.051, "sell"), ret=InsertOrderReturn{'result': 'success', 'clientorderid': '43002F1697040028539I0L64'}
2023-10-12 00:00:28,558:INFO:logic:main.py:494:insertFactor:2218526: curDateTime:10120000, name:logic, symbol:BTCUSDT, tradeDate:20231011, closeTime:235959, close:26770.0, sign:-1, total:645802.5993949, side:sell  
127.0.0.1 - - [12/Oct/2023 00:00:28] "POST / HTTP/1.1" 200 -
2023-10-12 00:00:28,559:INFO:logic:main.py:661:handleOrderNew:2218526: handleOrderNew: data=OrderType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'clientorderid': '43001F1697040022985I0L64', 'symbol': 'BTCUSDT', 'gatewayorderid': 1697040023414766, 'quantity': '24.072', 'price': '26761.7', 'stopprice': '0', 'ordertype': '', 'side': 'SELL', 'status': 'FILLED', 'positionside': 'SHORT', 'createtime': 1697040022150, 'updatetime': 1697040023414, 'tradetype': 'usdt', 'selfid': 43001, 'filltrades': [TradeType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'tradeid': 1697040023414, 'clientorderid': '43001F1697040022985I0L64', 'price': '26761.7', 'quantity': '24.072', 'commission': '644.2076424', 'commissionasset': 'USDT', 'tradetime': 1697040023414, 'tradetype': 'usdt', 'gatetype': 'simulator', 'handletime': 1697040023414}], 'gatetype': 'simulator', 'handletime': 0}
2023-10-12 00:00:28,559:INFO:logic:main.py:664:handleOrderFilled:2218526: handleOrderFilled: data=OrderType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'clientorderid': '43001F1697040022985I0L64', 'symbol': 'BTCUSDT', 'gatewayorderid': 1697040023414766, 'quantity': '24.072', 'price': '26761.7', 'stopprice': '0', 'ordertype': '', 'side': 'SELL', 'status': 'FILLED', 'positionside': 'SHORT', 'createtime': 1697040022150, 'updatetime': 1697040023414, 'tradetype': 'usdt', 'selfid': 43001, 'filltrades': [TradeType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'tradeid': 1697040023414, 'clientorderid': '43001F1697040022985I0L64', 'price': '26761.7', 'quantity': '24.072', 'commission': '644.2076424', 'commissionasset': 'USDT', 'tradetime': 1697040023414, 'tradetype': 'usdt', 'gatetype': 'simulator', 'handletime': 1697040023414}], 'gatetype': 'simulator', 'handletime': 0}
127.0.0.1 - - [12/Oct/2023 00:00:28] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [12/Oct/2023 00:00:28] "POST / HTTP/1.1" 200 -
2023-10-12 00:00:28,953:INFO:logic:main.py:661:handleOrderNew:2218526: handleOrderNew: data=OrderType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'clientorderid': '43002F1697040028539I0L64', 'symbol': 'BTCUSDT', 'gatewayorderid': 1697040028931014, 'quantity': '24.051', 'price': '26768.8', 'stopprice': '0', 'ordertype': '', 'side': 'SELL', 'status': 'FILLED', 'positionside': 'SHORT', 'createtime': 1697040028053, 'updatetime': 1697040028931, 'tradetype': 'usdt', 'selfid': 43002, 'filltrades': [TradeType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'tradeid': 1697040028931, 'clientorderid': '43002F1697040028539I0L64', 'price': '26768.8', 'quantity': '24.051', 'commission': '643.8164088', 'commissionasset': 'USDT', 'tradetime': 1697040028931, 'tradetype': 'usdt', 'gatetype': 'simulator', 'handletime': 1697040028931}], 'gatetype': 'simulator', 'handletime': 0}
127.0.0.1 - - [12/Oct/2023 00:00:29] "POST / HTTP/1.1" 200 -
2023-10-12 00:00:29,105:INFO:logic:main.py:664:handleOrderFilled:2218526: handleOrderFilled: data=OrderType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'clientorderid': '43002F1697040028539I0L64', 'symbol': 'BTCUSDT', 'gatewayorderid': 1697040028931014, 'quantity': '24.051', 'price': '26768.8', 'stopprice': '0', 'ordertype': '', 'side': 'SELL', 'status': 'FILLED', 'positionside': 'SHORT', 'createtime': 1697040028053, 'updatetime': 1697040028931, 'tradetype': 'usdt', 'selfid': 43002, 'filltrades': [TradeType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'tradeid': 1697040028931, 'clientorderid': '43002F1697040028539I0L64', 'price': '26768.8', 'quantity': '24.051', 'commission': '643.8164088', 'commissionasset': 'USDT', 'tradetime': 1697040028931, 'tradetype': 'usdt', 'gatetype': 'simulator', 'handletime': 1697040028931}], 'gatetype': 'simulator', 'handletime': 0}


## /root/FIL/strategy/modifiedmom/log.txt ----- -----


--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=21671 

self.closeSec=1697038199, self.tradeDate='20231011', self.openTime='232000', self.closeTime='232959', self.symbol='BTCUSDT', self.open='26964.8', self.close='26813.5'
127.0.0.1 - - [11/Oct/2023 23:30:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=21672 

self.closeSec=1697038799, self.tradeDate='20231011', self.openTime='233000', self.closeTime='233959', self.symbol='BTCUSDT', self.open='26813.4', self.close='26843'
127.0.0.1 - - [11/Oct/2023 23:40:01] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [11/Oct/2023 23:50:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=21673 

self.closeSec=1697039399, self.tradeDate='20231011', self.openTime='234000', self.closeTime='234959', self.symbol='BTCUSDT', self.open='26844.5', self.close='26797.8'

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=21674 

self.closeSec=1697039999, self.tradeDate='20231011', self.openTime='235000', self.closeTime='235959', self.symbol='BTCUSDT', self.open='26797.8', self.close='26770'
127.0.0.1 - - [12/Oct/2023 00:00:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=21675 

self.closeSec=1697040599, self.tradeDate='20231012', self.openTime='000000', self.closeTime='000959', self.symbol='BTCUSDT', self.open='26769.2', self.close='26764'
127.0.0.1 - - [12/Oct/2023 00:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=21676 

self.closeSec=1697041199, self.tradeDate='20231012', self.openTime='001000', self.closeTime='001959', self.symbol='BTCUSDT', self.open='26764.1', self.close='26689.1'
127.0.0.1 - - [12/Oct/2023 00:20:11] "POST / HTTP/1.1" 200 -


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

127.0.0.1 - - [11/Oct/2023 23:30:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=21674 

self.closeSec=1697038199, self.tradeDate='20231011', self.openTime='232000', self.closeTime='232959', self.symbol='BTCUSDT', self.open='26964.8', self.close='26813.5'

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=21675 

self.closeSec=1697038799, self.tradeDate='20231011', self.openTime='233000', self.closeTime='233959', self.symbol='BTCUSDT', self.open='26813.4', self.close='26843'
127.0.0.1 - - [11/Oct/2023 23:40:01] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [11/Oct/2023 23:50:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=21676 

self.closeSec=1697039399, self.tradeDate='20231011', self.openTime='234000', self.closeTime='234959', self.symbol='BTCUSDT', self.open='26844.5', self.close='26797.8'

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=21677 

self.closeSec=1697039999, self.tradeDate='20231011', self.openTime='235000', self.closeTime='235959', self.symbol='BTCUSDT', self.open='26797.8', self.close='26770'
127.0.0.1 - - [12/Oct/2023 00:00:01] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [12/Oct/2023 00:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=21678 

self.closeSec=1697040599, self.tradeDate='20231012', self.openTime='000000', self.closeTime='000959', self.symbol='BTCUSDT', self.open='26769.2', self.close='26764'

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=21679 

self.closeSec=1697041199, self.tradeDate='20231012', self.openTime='001000', self.closeTime='001959', self.symbol='BTCUSDT', self.open='26764.1', self.close='26689.1'
127.0.0.1 - - [12/Oct/2023 00:20:11] "POST / HTTP/1.1" 200 -


## /root/FIL/strategy/similarity/log.txt ----- -----


--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=21674 

self.closeSec=1697038199, self.tradeDate='20231011', self.openTime='232000', self.closeTime='232959', self.symbol='BTCUSDT', self.open='26964.8', self.close='26813.5'
127.0.0.1 - - [11/Oct/2023 23:30:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=21675 

self.closeSec=1697038799, self.tradeDate='20231011', self.openTime='233000', self.closeTime='233959', self.symbol='BTCUSDT', self.open='26813.4', self.close='26843'
127.0.0.1 - - [11/Oct/2023 23:40:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=21676 

self.closeSec=1697039399, self.tradeDate='20231011', self.openTime='234000', self.closeTime='234959', self.symbol='BTCUSDT', self.open='26844.5', self.close='26797.8'
127.0.0.1 - - [11/Oct/2023 23:50:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=21677 

self.closeSec=1697039999, self.tradeDate='20231011', self.openTime='235000', self.closeTime='235959', self.symbol='BTCUSDT', self.open='26797.8', self.close='26770'
127.0.0.1 - - [12/Oct/2023 00:00:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=21678 

self.closeSec=1697040599, self.tradeDate='20231012', self.openTime='000000', self.closeTime='000959', self.symbol='BTCUSDT', self.open='26769.2', self.close='26764'
127.0.0.1 - - [12/Oct/2023 00:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=21679 

self.closeSec=1697041199, self.tradeDate='20231012', self.openTime='001000', self.closeTime='001959', self.symbol='BTCUSDT', self.open='26764.1', self.close='26689.1'
127.0.0.1 - - [12/Oct/2023 00:20:11] "POST / HTTP/1.1" 200 -


## /root/FIL/strategy/sr_min/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=1, self.total=996015.990996, self.flagDict['side']='buy', self.tradeCount=1, self.count=43348
self.closeSec=1697041199, self.tradeDate='20231012', self.openTime='001500', self.closeTime='001959', self.symbol='BTCUSDT', self.open=26737.3, self.close=26689.1, self.high=26737.3, self.low=26662.7, self.vol=3779.52, self.amt=100898277.1754 
127.0.0.1 - - [12/Oct/2023 00:20:09] "POST / HTTP/1.1" 200 -
2023-10-12 00:20:15,771:INFO:sr_min:main.py:172:handleKline:2219263: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5759  20231011   235500    235959  ...         0.0        0.0       0
5760  20231012   000000    000459  ...         0.0        0.0       0
5761  20231012   000500    000959  ...         0.0        0.0       0
5762  20231012   001000    001459  ...         0.0        0.0       0
5763  20231012   001500    001959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-10-12 00:20:15,791:INFO:sr_min:main.py:175:handleKline:2219263: self.closeSec=1697041199, self.tradeDate='20231012', self.openTime='001500', self.closeTime='001959',self.symbol='BTCUSDT',self.open=26737.3, self.close=26689.1, self.high=26737.3, self.low=26662.7, self.vol=3779.52, self.amt=100898277.1754, ukdf['pct'].iloc[-1]=-0.001806 , ukdf['amount'].iloc[-1]=100898277.1754, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5763, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '37.141', 'enterprice': '26844', 'countrevence': '0', 'unrealprofit': '-5311.163', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '26701', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=1
--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=1, self.total=996015.990996, self.flagDict['side']='buy', self.tradeCount=1, self.count=43349
self.closeSec=1697041499, self.tradeDate='20231012', self.openTime='002000', self.closeTime='002459', self.symbol='BTCUSDT', self.open=26689.2, self.close=26687.8, self.high=26712.2, self.low=26643.0, self.vol=2679.846, self.amt=71480353.4613 
127.0.0.1 - - [12/Oct/2023 00:25:00] "POST / HTTP/1.1" 200 -
2023-10-12 00:25:00,805:INFO:sr_min:main.py:172:handleKline:2219263: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5760  20231012   000000    000459  ...         0.0        0.0       0
5761  20231012   000500    000959  ...         0.0        0.0       0
5762  20231012   001000    001459  ...         0.0        0.0       0
5763  20231012   001500    001959  ...         0.0        0.0       0
5764  20231012   002000    002459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-10-12 00:25:00,805:INFO:sr_min:main.py:175:handleKline:2219263: self.closeSec=1697041499, self.tradeDate='20231012', self.openTime='002000', self.closeTime='002459',self.symbol='BTCUSDT',self.open=26689.2, self.close=26687.8, self.high=26712.2, self.low=26643.0, self.vol=2679.846, self.amt=71480353.4613, ukdf['pct'].iloc[-1]=-4.9e-05 , ukdf['amount'].iloc[-1]=71480353.4613, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5764, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '37.141', 'enterprice': '26844', 'countrevence': '0', 'unrealprofit': '-5849.7075', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '26686.5', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=1


## /root/FIL/strategy/s_rsrs/log.txt ----- -----

723  20231011   120000    155959  1697011199  ...    723  0.492972 -0.010388     NaN
724  20231011   160000    195959  1697025599  ...    724  0.527985  0.077283     NaN

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '43.597', 'enterprice': '27944.4', 'countrevence': '0', 'unrealprofit': '33059.6051', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '27186.1', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-9223372036854775808, self.sign=-1
127.0.0.1 - - [12/Oct/2023 00:00:01] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='s_rsrs', self.symbol='BTCUSDT', interval='4h', intervalSec=14400, wid=25, thd=0.6, self.sign=-1, self.total=1217073.7147932001, self.flagDict['side']='sell', self.tradeCount=32, self.count=903
self.closeSec=1697039999, self.tradeDate='20231011', self.openTime='200000', self.closeTime='235959', self.symbol='BTCUSDT', self.open=27185.0, self.close=26770.0, self.high=27252.6, self.low=26700.0, self.vol=99764.109, self.amt=2690309196.79722 
2023-10-12 00:00:01,509:INFO:s_rsrs:main.py:141:handleKline:2218689: self.closeSec=1697039999, self.tradeDate='20231011', self.openTime='200000', self.closeTime='235959',self.symbol='BTCUSDT',self.open=27185.0, self.close=26770.0, self.high=27252.6, self.low=26700.0, self.vol=99764.109, self.amt=2690309196.79722 
2023-10-12 00:00:01,522:INFO:s_rsrs:main.py:142:handleKline:2218689: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime  ...        vol           amt       pct
721  20231011   040000    075959  ...  16419.750  4.498894e+08 -0.000186
722  20231011   080000    115959  ...  71624.411  1.945324e+09 -0.013922
723  20231011   120000    155959  ...  38484.453  1.041483e+09  0.000470
724  20231011   160000    195959  ...  57422.558  1.561342e+09  0.006371
725  20231011   200000    235959  ...  99764.109  2.690309e+09 -0.015262

[5 rows x 11 columns]
2023-10-12 00:00:02,222:INFO:s_rsrs:main.py:151:handleKline:2218689: df_s.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec  ...  index      beta    zscore  signal
721  20231011   040000    075959  1696982399  ...    721  0.438110 -0.148669     NaN
722  20231011   080000    115959  1696996799  ...    722  0.384416 -0.298334     NaN
723  20231011   120000    155959  1697011199  ...    723  0.492972 -0.010388     NaN
724  20231011   160000    195959  1697025599  ...    724  0.527985  0.077283     NaN
725  20231011   200000    235959  1697039999  ...    725  0.473472 -0.077798     NaN

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '43.597', 'enterprice': '27944.4', 'countrevence': '0', 'unrealprofit': '50999.73299148392', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '26774.60086264', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-9223372036854775808, self.sign=-1


