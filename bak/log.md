# 20231007 00:26:02

## /root/FIL/strategy/amihud/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=373746.4768026, self.flagDict['side']='sell', self.tradeCount=2, self.count=41908
self.closeSec=1696609199, self.tradeDate='20231007', self.openTime='001500', self.closeTime='001959', self.symbol='BTCUSDT', self.open=27899.9, self.close=27845.9, self.high=27928.1, self.low=27790.0, self.vol=9521.892, self.amt=265139688.4161 
127.0.0.1 - - [07/Oct/2023 00:20:02] "POST / HTTP/1.1" 200 -
2023-10-07 00:20:06,394:INFO:amihud:main.py:172:handleKline:2219019: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5759  20231006   235500    235959  ...         0.0        0.0       0
5760  20231007   000000    000459  ...         0.0        0.0       0
5761  20231007   000500    000959  ...         0.0        0.0       0
5762  20231007   001000    001459  ...         0.0        0.0       0
5763  20231007   001500    001959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-10-07 00:20:06,396:INFO:amihud:main.py:175:handleKline:2219019: self.closeSec=1696609199, self.tradeDate='20231007', self.openTime='001500', self.closeTime='001959',self.symbol='BTCUSDT',self.open=27899.9, self.close=27845.9, self.high=27928.1, self.low=27790.0, self.vol=9521.892, self.amt=265139688.4161, ukdf['pct'].iloc[-1]=-0.002132 , ukdf['amount'].iloc[-1]=265139688.4161, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5763, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '13.926', 'enterprice': '26864.9', 'countrevence': '0', 'unrealprofit': '-13703.184', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '27848.9', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1
127.0.0.1 - - [07/Oct/2023 00:25:00] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=373746.4768026, self.flagDict['side']='sell', self.tradeCount=2, self.count=41909
self.closeSec=1696609499, self.tradeDate='20231007', self.openTime='002000', self.closeTime='002459', self.symbol='BTCUSDT', self.open=27845.9, self.close=27864.2, self.high=27887.5, self.low=27843.0, self.vol=2566.898, self.amt=71521072.6728 
2023-10-07 00:25:00,818:INFO:amihud:main.py:172:handleKline:2219019: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5760  20231007   000000    000459  ...         0.0        0.0       0
5761  20231007   000500    000959  ...         0.0        0.0       0
5762  20231007   001000    001459  ...         0.0        0.0       0
5763  20231007   001500    001959  ...         0.0        0.0       0
5764  20231007   002000    002459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-10-07 00:25:00,818:INFO:amihud:main.py:175:handleKline:2219019: self.closeSec=1696609499, self.tradeDate='20231007', self.openTime='002000', self.closeTime='002459',self.symbol='BTCUSDT',self.open=27845.9, self.close=27864.2, self.high=27887.5, self.low=27843.0, self.vol=2566.898, self.amt=71521072.6728, ukdf['pct'].iloc[-1]=0.000657 , ukdf['amount'].iloc[-1]=71521072.6728, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5764, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '13.926', 'enterprice': '26864.9', 'countrevence': '0', 'unrealprofit': '-13899.74785759428', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '27863.01488278', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1


## /root/FIL/strategy/factorcheck/log.txt ----- -----

127.0.0.1 - - [07/Oct/2023 00:05:00] "POST / HTTP/1.1" 200 -

--ukdf-hist--: overDate='20231002' 
 Empty DataFrame
Columns: [tradeDate, openTime, closeTime, closeSec, open, close, high, low, pct, index, idx]
Index: [] 
 Empty DataFrame
Columns: [tradeDate, openTime, closeTime, closeSec, open, close, high, low, pct, index, idx]
Index: [] 


--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.714181719035411, self.count=41908 

self.closeSec=1696608599, self.tradeDate='20231007', self.openTime='000500', self.closeTime='000959', self.symbol='BTCUSDT', self.open=27941.0, self.close=27971.6, self.high=28012.0, self.low=27913.3 
127.0.0.1 - - [07/Oct/2023 00:10:00] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.714181719035411, self.count=41909 

self.closeSec=1696608899, self.tradeDate='20231007', self.openTime='001000', self.closeTime='001459', self.symbol='BTCUSDT', self.open=27970.1, self.close=27905.4, self.high=28005.0, self.low=27888.0 
127.0.0.1 - - [07/Oct/2023 00:15:00] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.714181719035411, self.count=41910 

self.closeSec=1696609199, self.tradeDate='20231007', self.openTime='001500', self.closeTime='001959', self.symbol='BTCUSDT', self.open=27899.9, self.close=27845.9, self.high=27928.1, self.low=27790.0 
127.0.0.1 - - [07/Oct/2023 00:20:02] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [07/Oct/2023 00:25:00] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.714181719035411, self.count=41911 

self.closeSec=1696609499, self.tradeDate='20231007', self.openTime='002000', self.closeTime='002459', self.symbol='BTCUSDT', self.open=27845.9, self.close=27864.2, self.high=27887.5, self.low=27843.0 


## /root/FIL/strategy/logic/log.txt ----- -----

539     0  0.517863  0.482137       1  ...  0.962214  -1.0  0.0000  1.051026
540     0  0.522900  0.477100       1  ...  0.958185  -1.0  0.0000  1.055427
541     0  0.523814  0.476186       1  ...  0.957207  -1.0  0.0000  1.056504
542     0  0.506163  0.493837       1  ...  0.952064  -1.0  0.0000  1.062181
543     0  0.568368  0.431632       1  ...  0.954722   1.0 -0.0016  1.066846

[5 rows x 10 columns]
2023-10-07 00:00:18,735:INFO:logic:main.py:478:getModel:2218526: df_panel.iloc[-5:,:] :
    pred    prob_0    prob_1  actual  ...       nav  sign   cost_        bm
45     0  0.517678  0.482322       1  ...  0.962214  -1.0  0.0000  1.053417
46     0  0.522674  0.477326       1  ...  0.958185  -1.0  0.0000  1.057483
47     0  0.523714  0.476286       1  ...  0.957207  -1.0  0.0000  1.058701
48     0  0.506119  0.493881       1  ...  0.952064  -1.0  0.0000  1.064389
49     0  0.568368  0.431632       1  ...  0.954722   1.0 -0.0016  1.066846

[5 rows x 10 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '24.386', 'enterprice': '27541.7', 'countrevence': '0', 'unrealprofit': '-9903.1546', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '27947.8', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
handlebackTrade > queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '24.386', 'enterprice': '27541.7', 'countrevence': '0', 'unrealprofit': '-9903.1546', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '27947.8', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
2023-10-07 00:00:25,534:INFO:logic:main.py:500:queryContractAssets:2218526: queryContractAssets: assets=ContractAssetReturn{'result': [ContractAsset{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'asset': 'USDT', 'free': '662989.6424565', 'total': '662989.6424565', 'margin': '0', 'unreal': '0', 'type': 'AssetType_ucontract'}]}
2023-10-07 00:00:26,029:DEBUG:logic:main.py:571:openBuy:2218526: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': True, 'isCloseBuy': False, 'isCloseSell': False, 'isOpen': True, 'isClose': False, 'isTrig': False}
2023-10-07 00:00:26,029:INFO:logic:main.py:572:openBuy:2218526: ret = self.client.insertMarketUOrder("simulator", "BTCUSDT", 23.669, "buy"), ret=InsertOrderReturn{'result': 'success', 'clientorderid': '42996F1696608026027I0L64'}
2023-10-07 00:00:26,047:INFO:logic:main.py:494:insertFactor:2218526: curDateTime:10070000, name:logic, symbol:BTCUSDT, tradeDate:20231006, closeTime:235959, close:27926.5, sign:1, total:662989.6424565, side:buy  
127.0.0.1 - - [07/Oct/2023 00:00:26] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [07/Oct/2023 00:00:26] "POST / HTTP/1.1" 200 -
2023-10-07 00:00:26,048:INFO:logic:main.py:661:handleOrderNew:2218526: handleOrderNew: data=OrderType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'clientorderid': '42995F1696608020472I0L64', 'symbol': 'BTCUSDT', 'gatewayorderid': 1696608020875718, 'quantity': '24.386', 'price': '27949.5', 'stopprice': '0', 'ordertype': '', 'side': 'BUY', 'status': 'FILLED', 'positionside': 'LONG', 'createtime': 1696608019593, 'updatetime': 1696608020875, 'tradetype': 'usdt', 'selfid': 42995, 'filltrades': [TradeType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'tradeid': 1696608020875, 'clientorderid': '42995F1696608020472I0L64', 'price': '27949.5', 'quantity': '24.386', 'commission': '681.576507', 'commissionasset': 'USDT', 'tradetime': 1696608020875, 'tradetype': 'usdt', 'gatetype': 'simulator', 'handletime': 1696608020875}], 'gatetype': 'simulator', 'handletime': 0}
2023-10-07 00:00:26,048:INFO:logic:main.py:664:handleOrderFilled:2218526: handleOrderFilled: data=OrderType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'clientorderid': '42995F1696608020472I0L64', 'symbol': 'BTCUSDT', 'gatewayorderid': 1696608020875718, 'quantity': '24.386', 'price': '27949.5', 'stopprice': '0', 'ordertype': '', 'side': 'BUY', 'status': 'FILLED', 'positionside': 'LONG', 'createtime': 1696608019593, 'updatetime': 1696608020875, 'tradetype': 'usdt', 'selfid': 42995, 'filltrades': [TradeType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'tradeid': 1696608020875, 'clientorderid': '42995F1696608020472I0L64', 'price': '27949.5', 'quantity': '24.386', 'commission': '681.576507', 'commissionasset': 'USDT', 'tradetime': 1696608020875, 'tradetype': 'usdt', 'gatetype': 'simulator', 'handletime': 1696608020875}], 'gatetype': 'simulator', 'handletime': 0}
127.0.0.1 - - [07/Oct/2023 00:00:26] "POST / HTTP/1.1" 200 -
2023-10-07 00:00:26,442:INFO:logic:main.py:661:handleOrderNew:2218526: handleOrderNew: data=OrderType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'clientorderid': '42996F1696608026027I0L64', 'symbol': 'BTCUSDT', 'gatewayorderid': 1696608026421440, 'quantity': '23.669', 'price': '27936.3', 'stopprice': '0', 'ordertype': '', 'side': 'BUY', 'status': 'FILLED', 'positionside': 'LONG', 'createtime': 1696608025545, 'updatetime': 1696608026421, 'tradetype': 'usdt', 'selfid': 42996, 'filltrades': [TradeType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'tradeid': 1696608026421, 'clientorderid': '42996F1696608026027I0L64', 'price': '27936.3', 'quantity': '23.669', 'commission': '661.2242847', 'commissionasset': 'USDT', 'tradetime': 1696608026421, 'tradetype': 'usdt', 'gatetype': 'simulator', 'handletime': 1696608026421}], 'gatetype': 'simulator', 'handletime': 0}
127.0.0.1 - - [07/Oct/2023 00:00:26] "POST / HTTP/1.1" 200 -
2023-10-07 00:00:26,595:INFO:logic:main.py:664:handleOrderFilled:2218526: handleOrderFilled: data=OrderType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'clientorderid': '42996F1696608026027I0L64', 'symbol': 'BTCUSDT', 'gatewayorderid': 1696608026421440, 'quantity': '23.669', 'price': '27936.3', 'stopprice': '0', 'ordertype': '', 'side': 'BUY', 'status': 'FILLED', 'positionside': 'LONG', 'createtime': 1696608025545, 'updatetime': 1696608026421, 'tradetype': 'usdt', 'selfid': 42996, 'filltrades': [TradeType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'tradeid': 1696608026421, 'clientorderid': '42996F1696608026027I0L64', 'price': '27936.3', 'quantity': '23.669', 'commission': '661.2242847', 'commissionasset': 'USDT', 'tradetime': 1696608026421, 'tradetype': 'usdt', 'gatetype': 'simulator', 'handletime': 1696608026421}], 'gatetype': 'simulator', 'handletime': 0}


## /root/FIL/strategy/modifiedmom/log.txt ----- -----

127.0.0.1 - - [06/Oct/2023 23:30:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=20951 

self.closeSec=1696606199, self.tradeDate='20231006', self.openTime='232000', self.closeTime='232959', self.symbol='BTCUSDT', self.open='27626.2', self.close='27804.4'

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=20952127.0.0.1 - - [06/Oct/2023 23:40:01] "POST / HTTP/1.1" 200 -
 

self.closeSec=1696606799, self.tradeDate='20231006', self.openTime='233000', self.closeTime='233959', self.symbol='BTCUSDT', self.open='27813.7', self.close='27888.9'

--handleKline--: 127.0.0.1 - - [06/Oct/2023 23:50:01] "POST / HTTP/1.1" 200 -
 self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=20953 

self.closeSec=1696607399, self.tradeDate='20231006', self.openTime='234000', self.closeTime='234959', self.symbol='BTCUSDT', self.open='27885', self.close='27998.3'

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=20954 

self.closeSec=1696607999, self.tradeDate='20231006', self.openTime='235000', self.closeTime='235959', self.symbol='BTCUSDT', self.open='27997.2', self.close='27926.5'
127.0.0.1 - - [07/Oct/2023 00:00:01] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [07/Oct/2023 00:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=20955 

self.closeSec=1696608599, self.tradeDate='20231007', self.openTime='000000', self.closeTime='000959', self.symbol='BTCUSDT', self.open='27926.6', self.close='27970'

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=20956 

self.closeSec=1696609199, self.tradeDate='20231007', self.openTime='001000', self.closeTime='001959', self.symbol='BTCUSDT', self.open='27970.1', self.close='27845.9'
127.0.0.1 - - [07/Oct/2023 00:20:04] "POST / HTTP/1.1" 200 -


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


--handleKline--: 127.0.0.1 - - [06/Oct/2023 23:30:01] "POST / HTTP/1.1" 200 -
 self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=20954 

self.closeSec=1696606199, self.tradeDate='20231006', self.openTime='232000', self.closeTime='232959', self.symbol='BTCUSDT', self.open='27626.2', self.close='27804.4'

--handleKline--: 127.0.0.1 - - [06/Oct/2023 23:40:01] "POST / HTTP/1.1" 200 -
 self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=20955 

self.closeSec=1696606799, self.tradeDate='20231006', self.openTime='233000', self.closeTime='233959', self.symbol='BTCUSDT', self.open='27813.7', self.close='27888.9'
127.0.0.1 - - [06/Oct/2023 23:50:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=20956 

self.closeSec=1696607399, self.tradeDate='20231006', self.openTime='234000', self.closeTime='234959', self.symbol='BTCUSDT', self.open='27885', self.close='27998.3'
127.0.0.1 - - [07/Oct/2023 00:00:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=20957 

self.closeSec=1696607999, self.tradeDate='20231006', self.openTime='235000', self.closeTime='235959', self.symbol='BTCUSDT', self.open='27997.2', self.close='27926.5'

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=20958 

self.closeSec=1696608599, self.tradeDate='20231007', self.openTime='000000', self.closeTime='000959', self.symbol='BTCUSDT', self.open='27926.6', self.close='27970'
127.0.0.1 - - [07/Oct/2023 00:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=20959 

self.closeSec=1696609199, self.tradeDate='20231007', self.openTime='001000', self.closeTime='001959', self.symbol='BTCUSDT', self.open='27970.1', self.close='27845.9'
127.0.0.1 - - [07/Oct/2023 00:20:04] "POST / HTTP/1.1" 200 -


## /root/FIL/strategy/similarity/log.txt ----- -----

127.0.0.1 - - [06/Oct/2023 23:30:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=20954 

self.closeSec=1696606199, self.tradeDate='20231006', self.openTime='232000', self.closeTime='232959', self.symbol='BTCUSDT', self.open='27626.2', self.close='27804.4'
127.0.0.1 - - [06/Oct/2023 23:40:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=20955 

self.closeSec=1696606799, self.tradeDate='20231006', self.openTime='233000', self.closeTime='233959', self.symbol='BTCUSDT', self.open='27813.7', self.close='27888.9'

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=20956 

self.closeSec=1696607399, self.tradeDate='20231006', self.openTime='234000', self.closeTime='234959', self.symbol='BTCUSDT', self.open='27885', self.close='27998.3'
127.0.0.1 - - [06/Oct/2023 23:50:01] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [07/Oct/2023 00:00:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=20957 

self.closeSec=1696607999, self.tradeDate='20231006', self.openTime='235000', self.closeTime='235959', self.symbol='BTCUSDT', self.open='27997.2', self.close='27926.5'
127.0.0.1 - - [07/Oct/2023 00:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=20958 

self.closeSec=1696608599, self.tradeDate='20231007', self.openTime='000000', self.closeTime='000959', self.symbol='BTCUSDT', self.open='27926.6', self.close='27970'

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=20959 

self.closeSec=1696609199, self.tradeDate='20231007', self.openTime='001000', self.closeTime='001959', self.symbol='BTCUSDT', self.open='27970.1', self.close='27845.9'
127.0.0.1 - - [07/Oct/2023 00:20:04] "POST / HTTP/1.1" 200 -


## /root/FIL/strategy/sr_min/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=1, self.total=996015.990996, self.flagDict['side']='buy', self.tradeCount=1, self.count=41908
self.closeSec=1696609199, self.tradeDate='20231007', self.openTime='001500', self.closeTime='001959', self.symbol='BTCUSDT', self.open=27899.9, self.close=27845.9, self.high=27928.1, self.low=27790.0, self.vol=9521.892, self.amt=265139688.4161 
127.0.0.1 - - [07/Oct/2023 00:20:02] "POST / HTTP/1.1" 200 -
2023-10-07 00:20:06,397:INFO:sr_min:main.py:172:handleKline:2219263: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5759  20231006   235500    235959  ...         0.0        0.0       0
5760  20231007   000000    000459  ...         0.0        0.0       0
5761  20231007   000500    000959  ...         0.0        0.0       0
5762  20231007   001000    001459  ...         0.0        0.0       0
5763  20231007   001500    001959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-10-07 00:20:06,406:INFO:sr_min:main.py:175:handleKline:2219263: self.closeSec=1696609199, self.tradeDate='20231007', self.openTime='001500', self.closeTime='001959',self.symbol='BTCUSDT',self.open=27899.9, self.close=27845.9, self.high=27928.1, self.low=27790.0, self.vol=9521.892, self.amt=265139688.4161, ukdf['pct'].iloc[-1]=-0.002132 , ukdf['amount'].iloc[-1]=265139688.4161, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5763, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '37.141', 'enterprice': '26844', 'countrevence': '0', 'unrealprofit': '37322.9909', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '27848.9', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=1
--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=1, self.total=996015.990996, self.flagDict['side']='buy', self.tradeCount=1, self.count=41909
self.closeSec=1696609499, self.tradeDate='20231007', self.openTime='002000', self.closeTime='002459', self.symbol='BTCUSDT', self.open=27845.9, self.close=27864.2, self.high=27887.5, self.low=27843.0, self.vol=2566.898, self.amt=71521072.6728 
127.0.0.1 - - [07/Oct/2023 00:25:00] "POST / HTTP/1.1" 200 -
2023-10-07 00:25:00,828:INFO:sr_min:main.py:172:handleKline:2219263: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5760  20231007   000000    000459  ...         0.0        0.0       0
5761  20231007   000500    000959  ...         0.0        0.0       0
5762  20231007   001000    001459  ...         0.0        0.0       0
5763  20231007   001500    001959  ...         0.0        0.0       0
5764  20231007   002000    002459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-10-07 00:25:00,829:INFO:sr_min:main.py:175:handleKline:2219263: self.closeSec=1696609499, self.tradeDate='20231007', self.openTime='002000', self.closeTime='002459',self.symbol='BTCUSDT',self.open=27845.9, self.close=27864.2, self.high=27887.5, self.low=27843.0, self.vol=2566.898, self.amt=71521072.6728, ukdf['pct'].iloc[-1]=0.000657 , ukdf['amount'].iloc[-1]=71521072.6728, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5764, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '37.141', 'enterprice': '26844', 'countrevence': '0', 'unrealprofit': '37847.23176133198', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '27863.01488278', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=1


## /root/FIL/strategy/s_rsrs/log.txt ----- -----

721  20231006   040000    075959  ...   22243.134  6.101185e+08 -0.002047
722  20231006   080000    115959  ...   28560.574  7.856097e+08  0.005340
723  20231006   120000    155959  ...   29146.062  8.023779e+08  0.002992
724  20231006   160000    195959  ...   52608.948  1.455988e+09  0.004231
725  20231006   200000    235959  ...  192444.274  5.308505e+09  0.006578

[5 rows x 11 columns]
2023-10-07 00:00:02,536:INFO:s_rsrs:main.py:151:handleKline:2218689: df_s.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec  ...  index      beta    zscore  signal
721  20231006   040000    075959  1696550399  ...    721  0.315995 -0.984895    -1.0
722  20231006   080000    115959  1696564799  ...    722  0.935658  0.670697     1.0
723  20231006   120000    155959  1696579199  ...    723  0.892012  0.555175     NaN
724  20231006   160000    195959  1696593599  ...    724  0.737146  0.143416     NaN
725  20231006   200000    235959  1696607999  ...    725  0.332489 -0.923390    -1.0

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '43.642', 'enterprice': '27544.8', 'countrevence': '0', 'unrealprofit': '16666.20286937442', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '27926.68448901', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-1, self.sign=1
handlebackTrade > queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '43.642', 'enterprice': '27544.8', 'countrevence': '0', 'unrealprofit': '16666.20286937442', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '27926.68448901', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
2023-10-07 00:00:09,406:INFO:s_rsrs:main.py:182:queryContractAssets:2218689: queryContractAssets: assets=ContractAssetReturn{'result': [ContractAsset{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'asset': 'USDT', 'free': '1221181.0040234', 'total': '1221181.0040234', 'margin': '0', 'unreal': '0', 'type': 'AssetType_ucontract'}]}
2023-10-07 00:00:09,881:INFO:s_rsrs:main.py:269:openSell:2218689: ret = self.client.insertMarketUOrder("simulator", "BTCUSDT", 43.597, "sell"), ret=InsertOrderReturn{'result': 'success', 'clientorderid': '42994F1696608009879I0L65'}
2023-10-07 00:00:09,908:INFO:s_rsrs:main.py:176:insertFactor:2218689: curDateTime:10070000, name:s_rsrs, symbol:BTCUSDT, tradeDate:20231006, closeTime:235959, close:27926.5, sign:-1, total:1221181.0040234, side:sell  
127.0.0.1 - - [07/Oct/2023 00:00:09] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [07/Oct/2023 00:00:09] "POST / HTTP/1.1" 200 -
2023-10-07 00:00:09,912:INFO:s_rsrs:main.py:343:handleOrderNew:2218689: handleOrderNew: data=OrderType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'clientorderid': '42993F1696608004338I0L65', 'symbol': 'BTCUSDT', 'gatewayorderid': 1696608004754947, 'quantity': '43.642', 'price': '27926.5', 'stopprice': '0', 'ordertype': '', 'side': 'SELL', 'status': 'FILLED', 'positionside': 'SHORT', 'createtime': 1696608003412, 'updatetime': 1696608004754, 'tradetype': 'usdt', 'selfid': 42993, 'filltrades': [TradeType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'tradeid': 1696608004754, 'clientorderid': '42993F1696608004338I0L65', 'price': '27926.5', 'quantity': '43.642', 'commission': '1218.768313', 'commissionasset': 'USDT', 'tradetime': 1696608004754, 'tradetype': 'usdt', 'gatetype': 'simulator', 'handletime': 1696608004754}], 'gatetype': 'simulator', 'handletime': 0}
2023-10-07 00:00:09,913:INFO:s_rsrs:main.py:346:handleOrderFilled:2218689: handleOrderFilled: data=OrderType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'clientorderid': '42993F1696608004338I0L65', 'symbol': 'BTCUSDT', 'gatewayorderid': 1696608004754947, 'quantity': '43.642', 'price': '27926.5', 'stopprice': '0', 'ordertype': '', 'side': 'SELL', 'status': 'FILLED', 'positionside': 'SHORT', 'createtime': 1696608003412, 'updatetime': 1696608004754, 'tradetype': 'usdt', 'selfid': 42993, 'filltrades': [TradeType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'tradeid': 1696608004754, 'clientorderid': '42993F1696608004338I0L65', 'price': '27926.5', 'quantity': '43.642', 'commission': '1218.768313', 'commissionasset': 'USDT', 'tradetime': 1696608004754, 'tradetype': 'usdt', 'gatetype': 'simulator', 'handletime': 1696608004754}], 'gatetype': 'simulator', 'handletime': 0}
127.0.0.1 - - [07/Oct/2023 00:00:10] "POST / HTTP/1.1" 200 -
2023-10-07 00:00:10,403:INFO:s_rsrs:main.py:343:handleOrderNew:2218689: handleOrderNew: data=OrderType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'clientorderid': '42994F1696608009879I0L65', 'symbol': 'BTCUSDT', 'gatewayorderid': 1696608010354326, 'quantity': '43.597', 'price': '27944.4', 'stopprice': '0', 'ordertype': '', 'side': 'SELL', 'status': 'FILLED', 'positionside': 'SHORT', 'createtime': 1696608009419, 'updatetime': 1696608010354, 'tradetype': 'usdt', 'selfid': 42994, 'filltrades': [TradeType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'tradeid': 1696608010354, 'clientorderid': '42994F1696608009879I0L65', 'price': '27944.4', 'quantity': '43.597', 'commission': '1218.2920068', 'commissionasset': 'USDT', 'tradetime': 1696608010354, 'tradetype': 'usdt', 'gatetype': 'simulator', 'handletime': 1696608010354}], 'gatetype': 'simulator', 'handletime': 0}
2023-10-07 00:00:10,525:INFO:s_rsrs:main.py:346:handleOrderFilled:2218689: handleOrderFilled: data=OrderType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'clientorderid': '42994F1696608009879I0L65', 'symbol': 'BTCUSDT', 'gatewayorderid': 1696608010354326, 'quantity': '43.597', 'price': '27944.4', 'stopprice': '0', 'ordertype': '', 'side': 'SELL', 'status': 'FILLED', 'positionside': 'SHORT', 'createtime': 1696608009419, 'updatetime': 1696608010354, 'tradetype': 'usdt', 'selfid': 42994, 'filltrades': [TradeType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'tradeid': 1696608010354, 'clientorderid': '42994F1696608009879I0L65', 'price': '27944.4', 'quantity': '43.597', 'commission': '1218.2920068', 'commissionasset': 'USDT', 'tradetime': 1696608010354, 'tradetype': 'usdt', 'gatetype': 'simulator', 'handletime': 1696608010354}], 'gatetype': 'simulator', 'handletime': 0}
127.0.0.1 - - [07/Oct/2023 00:00:10] "POST / HTTP/1.1" 200 -


