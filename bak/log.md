# 20231027 00:26:02

## /root/FIL/strategy/amihud/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=373746.4768026, self.flagDict['side']='sell', self.tradeCount=2, self.count=47668
self.closeSec=1698337199, self.tradeDate='20231027', self.openTime='001500', self.closeTime='001959', self.symbol='BTCUSDT', self.open=33996.6, self.close=34017.3, self.high=34067.5, self.low=33984.6, self.vol=1157.799, self.amt=39397677.9418 
127.0.0.1 - - [27/Oct/2023 00:20:04] "POST / HTTP/1.1" 200 -
2023-10-27 00:20:07,693:INFO:amihud:main.py:172:handleKline:2219019: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5759  20231026   235500    235959  ...         0.0        0.0       0
5760  20231027   000000    000459  ...         0.0        0.0       0
5761  20231027   000500    000959  ...         0.0        0.0       0
5762  20231027   001000    001459  ...         0.0        0.0       0
5763  20231027   001500    001959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-10-27 00:20:07,705:INFO:amihud:main.py:175:handleKline:2219019: self.closeSec=1698337199, self.tradeDate='20231027', self.openTime='001500', self.closeTime='001959',self.symbol='BTCUSDT',self.open=33996.6, self.close=34017.3, self.high=34067.5, self.low=33984.6, self.vol=1157.799, self.amt=39397677.9418, ukdf['pct'].iloc[-1]=0.000609 , ukdf['amount'].iloc[-1]=39397677.9418, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5763, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '13.926', 'enterprice': '26864.9', 'countrevence': '0', 'unrealprofit': '-99677.1064656213', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '34022.52648755', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1
--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=373746.4768026, self.flagDict['side']='sell', self.tradeCount=2, self.count=47669
self.closeSec=1698337499, self.tradeDate='20231027', self.openTime='002000', self.closeTime='002459', self.symbol='BTCUSDT', self.open=34017.3, self.close=33980.2, self.high=34036.8, self.low=33975.3, self.vol=1126.436, self.amt=38292824.2832 
127.0.0.1 - - [27/Oct/2023 00:25:01] "POST / HTTP/1.1" 200 -
2023-10-27 00:25:03,176:INFO:amihud:main.py:172:handleKline:2219019: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5760  20231027   000000    000459  ...         0.0        0.0       0
5761  20231027   000500    000959  ...         0.0        0.0       0
5762  20231027   001000    001459  ...         0.0        0.0       0
5763  20231027   001500    001959  ...         0.0        0.0       0
5764  20231027   002000    002459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-10-27 00:25:03,185:INFO:amihud:main.py:175:handleKline:2219019: self.closeSec=1698337499, self.tradeDate='20231027', self.openTime='002000', self.closeTime='002459',self.symbol='BTCUSDT',self.open=34017.3, self.close=33980.2, self.high=34036.8, self.low=33975.3, self.vol=1126.436, self.amt=38292824.2832, ukdf['pct'].iloc[-1]=-0.001091 , ukdf['amount'].iloc[-1]=38292824.2832, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5764, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '13.926', 'enterprice': '26864.9', 'countrevence': '0', 'unrealprofit': '-99069.48023538852', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '33978.89398502', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1


## /root/FIL/strategy/factorcheck/log.txt ----- -----

127.0.0.1 - - [27/Oct/2023 00:05:00] "POST / HTTP/1.1" 200 -

--ukdf-hist--: overDate='20231022' 
 Empty DataFrame
Columns: [tradeDate, openTime, closeTime, closeSec, open, close, high, low, pct, index, idx]
Index: [] 
 Empty DataFrame
Columns: [tradeDate, openTime, closeTime, closeSec, open, close, high, low, pct, index, idx]
Index: [] 

127.0.0.1 - - [27/Oct/2023 00:10:00] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.714181719035411, self.count=47668 

self.closeSec=1698336599, self.tradeDate='20231027', self.openTime='000500', self.closeTime='000959', self.symbol='BTCUSDT', self.open=34070.0, self.close=33990.7, self.high=34071.5, self.low=33971.6 

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.714181719035411, self.count=47669 

self.closeSec=1698336899, self.tradeDate='20231027', self.openTime='001000', self.closeTime='001459', self.symbol='BTCUSDT', self.open=33989.8, self.close=33996.6, self.high=33999.0, self.low=33962.7 
127.0.0.1 - - [27/Oct/2023 00:15:01] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.714181719035411, self.count=47670 

self.closeSec=1698337199, self.tradeDate='20231027', self.openTime='001500', self.closeTime='001959', self.symbol='BTCUSDT', self.open=33996.6, self.close=34017.3, self.high=34067.5, self.low=33984.6 
127.0.0.1 - - [27/Oct/2023 00:20:03] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.714181719035411, self.count=47671 

self.closeSec=1698337499, self.tradeDate='20231027', self.openTime='002000', self.closeTime='002459', self.symbol='BTCUSDT', self.open=34017.3, self.close=33980.2, self.high=34036.8, self.low=33975.3 
127.0.0.1 - - [27/Oct/2023 00:25:01] "POST / HTTP/1.1" 200 -


## /root/FIL/strategy/logic/log.txt ----- -----

     pred    prob_0    prob_1  actual  ...       nav  sign   cost_        bm
539     0  0.531611  0.468389       0  ...  1.068557   1.0  0.0000  1.271205
540     0  0.507076  0.492924       1  ...  1.072070   1.0  0.0000  1.275384
541     0  0.561501  0.438499       0  ...  1.069724   1.0  0.0000  1.272593
542     0  0.512581  0.487419       0  ...  1.060778   1.0  0.0000  1.261950
543     1  0.447140  0.552860       1  ...  1.054764  -1.0 -0.0016  1.267085

[5 rows x 10 columns]
2023-10-27 00:00:19,204:INFO:logic:main.py:478:getModel:2218526: df_panel.iloc[-5:,:] :
    pred    prob_0    prob_1  actual  ...       nav  sign   cost_        bm
45     0  0.531407  0.468593       0  ...  1.068557   1.0  0.0000  1.271616
46     0  0.507050  0.492950       1  ...  1.072070   1.0  0.0000  1.275583
47     0  0.561324  0.438676       0  ...  1.069724   1.0  0.0000  1.272962
48     0  0.512406  0.487594       0  ...  1.060778   1.0  0.0000  1.262316
49     1  0.447140  0.552860       1  ...  1.054764  -1.0 -0.0016  1.267085

[5 rows x 10 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '20.978', 'enterprice': '33828.2', 'countrevence': '0', 'unrealprofit': '4359.35607378624', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '34036.00608608', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
handlebackTrade > queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '20.978', 'enterprice': '33828.2', 'countrevence': '0', 'unrealprofit': '4359.35607378624', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '34036.00608608', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
2023-10-27 00:00:26,056:INFO:logic:main.py:500:queryContractAssets:2218526: queryContractAssets: assets=ContractAssetReturn{'result': [ContractAsset{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'asset': 'USDT', 'free': '715702.6190623', 'total': '715702.6190623', 'margin': '0', 'unreal': '0', 'type': 'AssetType_ucontract'}]}
2023-10-27 00:00:26,528:INFO:logic:main.py:587:openSell:2218526: ret = self.client.insertMarketUOrder("simulator", "BTCUSDT", 20.956, "sell"), ret=InsertOrderReturn{'result': 'success', 'clientorderid': '43048F1698336026526I0L64'}
2023-10-27 00:00:26,549:INFO:logic:main.py:494:insertFactor:2218526: curDateTime:10270000, name:logic, symbol:BTCUSDT, tradeDate:20231026, closeTime:235959, close:34050.0, sign:-1, total:715702.6190623, side:sell  
127.0.0.1 - - [27/Oct/2023 00:00:26] "POST / HTTP/1.1" 200 -
2023-10-27 00:00:26,550:INFO:logic:main.py:661:handleOrderNew:2218526: handleOrderNew: data=OrderType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'clientorderid': '43047F1698336020996I0L64', 'symbol': 'BTCUSDT', 'gatewayorderid': 1698336021391908, 'quantity': '20.978', 'price': '34040', 'stopprice': '0', 'ordertype': '', 'side': 'SELL', 'status': 'FILLED', 'positionside': 'SHORT', 'createtime': 1698336020106, 'updatetime': 1698336021391, 'tradetype': 'usdt', 'selfid': 43047, 'filltrades': [TradeType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'tradeid': 1698336021391, 'clientorderid': '43047F1698336020996I0L64', 'price': '34040', 'quantity': '20.978', 'commission': '714.09112', 'commissionasset': 'USDT', 'tradetime': 1698336021391, 'tradetype': 'usdt', 'gatetype': 'simulator', 'handletime': 1698336021391}], 'gatetype': 'simulator', 'handletime': 0}
2023-10-27 00:00:26,550:INFO:logic:main.py:664:handleOrderFilled:2218526: handleOrderFilled: data=OrderType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'clientorderid': '43047F1698336020996I0L64', 'symbol': 'BTCUSDT', 'gatewayorderid': 1698336021391908, 'quantity': '20.978', 'price': '34040', 'stopprice': '0', 'ordertype': '', 'side': 'SELL', 'status': 'FILLED', 'positionside': 'SHORT', 'createtime': 1698336020106, 'updatetime': 1698336021391, 'tradetype': 'usdt', 'selfid': 43047, 'filltrades': [TradeType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'tradeid': 1698336021391, 'clientorderid': '43047F1698336020996I0L64', 'price': '34040', 'quantity': '20.978', 'commission': '714.09112', 'commissionasset': 'USDT', 'tradetime': 1698336021391, 'tradetype': 'usdt', 'gatetype': 'simulator', 'handletime': 1698336021391}], 'gatetype': 'simulator', 'handletime': 0}
127.0.0.1 - - [27/Oct/2023 00:00:26] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [27/Oct/2023 00:00:26] "POST / HTTP/1.1" 200 -
2023-10-27 00:00:26,975:INFO:logic:main.py:661:handleOrderNew:2218526: handleOrderNew: data=OrderType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'clientorderid': '43048F1698336026526I0L64', 'symbol': 'BTCUSDT', 'gatewayorderid': 1698336026946013, 'quantity': '20.956', 'price': '34043.1', 'stopprice': '0', 'ordertype': '', 'side': 'SELL', 'status': 'FILLED', 'positionside': 'SHORT', 'createtime': 1698336026069, 'updatetime': 1698336026946, 'tradetype': 'usdt', 'selfid': 43048, 'filltrades': [TradeType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'tradeid': 1698336026946, 'clientorderid': '43048F1698336026526I0L64', 'price': '34043.1', 'quantity': '20.956', 'commission': '713.4072036', 'commissionasset': 'USDT', 'tradetime': 1698336026946, 'tradetype': 'usdt', 'gatetype': 'simulator', 'handletime': 1698336026946}], 'gatetype': 'simulator', 'handletime': 0}
127.0.0.1 - - [27/Oct/2023 00:00:27] "POST / HTTP/1.1" 200 -
2023-10-27 00:00:27,128:INFO:logic:main.py:664:handleOrderFilled:2218526: handleOrderFilled: data=OrderType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'clientorderid': '43048F1698336026526I0L64', 'symbol': 'BTCUSDT', 'gatewayorderid': 1698336026946013, 'quantity': '20.956', 'price': '34043.1', 'stopprice': '0', 'ordertype': '', 'side': 'SELL', 'status': 'FILLED', 'positionside': 'SHORT', 'createtime': 1698336026069, 'updatetime': 1698336026946, 'tradetype': 'usdt', 'selfid': 43048, 'filltrades': [TradeType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'tradeid': 1698336026946, 'clientorderid': '43048F1698336026526I0L64', 'price': '34043.1', 'quantity': '20.956', 'commission': '713.4072036', 'commissionasset': 'USDT', 'tradetime': 1698336026946, 'tradetype': 'usdt', 'gatetype': 'simulator', 'handletime': 1698336026946}], 'gatetype': 'simulator', 'handletime': 0}


## /root/FIL/strategy/modifiedmom/log.txt ----- -----


--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=23831 

self.closeSec=1698334199, self.tradeDate='20231026', self.openTime='232000', self.closeTime='232959', self.symbol='BTCUSDT', self.open='33908.4', self.close='33912'
127.0.0.1 - - [26/Oct/2023 23:30:01] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [26/Oct/2023 23:40:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=23832 

self.closeSec=1698334799, self.tradeDate='20231026', self.openTime='233000', self.closeTime='233959', self.symbol='BTCUSDT', self.open='33919.2', self.close='33970.1'
127.0.0.1 - - [26/Oct/2023 23:50:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=23833 

self.closeSec=1698335399, self.tradeDate='20231026', self.openTime='234000', self.closeTime='234959', self.symbol='BTCUSDT', self.open='33970.1', self.close='34033.5'

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=23834 

self.closeSec=1698335999, self.tradeDate='20231026', self.openTime='235000', self.closeTime='235959', self.symbol='BTCUSDT', self.open='34035.1', self.close='34050'
127.0.0.1 - - [27/Oct/2023 00:00:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=23835 

self.closeSec=1698336599, self.tradeDate='20231027', self.openTime='000000', self.closeTime='000959', self.symbol='BTCUSDT', self.open='34050.1', self.close='33990.7'
127.0.0.1 - - [27/Oct/2023 00:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=23836 

self.closeSec=1698337199, self.tradeDate='20231027', self.openTime='001000', self.closeTime='001959', self.symbol='BTCUSDT', self.open='33989.8', self.close='34017.3'
127.0.0.1 - - [27/Oct/2023 00:20:05] "POST / HTTP/1.1" 200 -


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

127.0.0.1 - - [26/Oct/2023 23:30:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=23834 

self.closeSec=1698334199, self.tradeDate='20231026', self.openTime='232000', self.closeTime='232959', self.symbol='BTCUSDT', self.open='33908.4', self.close='33912'

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=23835 

self.closeSec=1698334799, self.tradeDate='20231026', self.openTime='233000', self.closeTime='233959', self.symbol='BTCUSDT', self.open='33919.2', self.close='33970.1'
127.0.0.1 - - [26/Oct/2023 23:40:01] "POST / HTTP/1.1" 200 -

--handleKline--: 127.0.0.1 - - [26/Oct/2023 23:50:01] "POST / HTTP/1.1" 200 -
 self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=23836 

self.closeSec=1698335399, self.tradeDate='20231026', self.openTime='234000', self.closeTime='234959', self.symbol='BTCUSDT', self.open='33970.1', self.close='34033.5'
127.0.0.1 - - [27/Oct/2023 00:00:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=23837 

self.closeSec=1698335999, self.tradeDate='20231026', self.openTime='235000', self.closeTime='235959', self.symbol='BTCUSDT', self.open='34035.1', self.close='34050'

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=23838 

self.closeSec=1698336599, self.tradeDate='20231027', self.openTime='000000', self.closeTime='000959', self.symbol='BTCUSDT', self.open='34050.1', self.close='33990.7'
127.0.0.1 - - [27/Oct/2023 00:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=23839 

self.closeSec=1698337199, self.tradeDate='20231027', self.openTime='001000', self.closeTime='001959', self.symbol='BTCUSDT', self.open='33989.8', self.close='34017.3'
127.0.0.1 - - [27/Oct/2023 00:20:05] "POST / HTTP/1.1" 200 -


## /root/FIL/strategy/similarity/log.txt ----- -----


--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=23834 

self.closeSec=1698334199, self.tradeDate='20231026', self.openTime='232000', self.closeTime='232959', self.symbol='BTCUSDT', self.open='33908.4', self.close='33912'
127.0.0.1 - - [26/Oct/2023 23:30:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=23835 

self.closeSec=1698334799, self.tradeDate='20231026', self.openTime='233000', self.closeTime='233959', self.symbol='BTCUSDT', self.open='33919.2', self.close='33970.1'
127.0.0.1 - - [26/Oct/2023 23:40:01] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [26/Oct/2023 23:50:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=23836 

self.closeSec=1698335399, self.tradeDate='20231026', self.openTime='234000', self.closeTime='234959', self.symbol='BTCUSDT', self.open='33970.1', self.close='34033.5'
127.0.0.1 - - [27/Oct/2023 00:00:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=23837 

self.closeSec=1698335999, self.tradeDate='20231026', self.openTime='235000', self.closeTime='235959', self.symbol='BTCUSDT', self.open='34035.1', self.close='34050'
127.0.0.1 - - [27/Oct/2023 00:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=23838 

self.closeSec=1698336599, self.tradeDate='20231027', self.openTime='000000', self.closeTime='000959', self.symbol='BTCUSDT', self.open='34050.1', self.close='33990.7'

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=23839 

self.closeSec=1698337199, self.tradeDate='20231027', self.openTime='001000', self.closeTime='001959', self.symbol='BTCUSDT', self.open='33989.8', self.close='34017.3'
127.0.0.1 - - [27/Oct/2023 00:20:05] "POST / HTTP/1.1" 200 -


## /root/FIL/strategy/sr_min/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=1, self.total=996015.990996, self.flagDict['side']='buy', self.tradeCount=1, self.count=47668
self.closeSec=1698337199, self.tradeDate='20231027', self.openTime='001500', self.closeTime='001959', self.symbol='BTCUSDT', self.open=33996.6, self.close=34017.3, self.high=34067.5, self.low=33984.6, self.vol=1157.799, self.amt=39397677.9418 
127.0.0.1 - - [27/Oct/2023 00:20:04] "POST / HTTP/1.1" 200 -
2023-10-27 00:20:07,697:INFO:sr_min:main.py:172:handleKline:2219263: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5759  20231026   235500    235959  ...         0.0        0.0       0
5760  20231027   000000    000459  ...         0.0        0.0       0
5761  20231027   000500    000959  ...         0.0        0.0       0
5762  20231027   001000    001459  ...         0.0        0.0       0
5763  20231027   001500    001959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-10-27 00:20:07,709:INFO:sr_min:main.py:175:handleKline:2219263: self.closeSec=1698337199, self.tradeDate='20231027', self.openTime='001500', self.closeTime='001959',self.symbol='BTCUSDT',self.open=33996.6, self.close=34017.3, self.high=34067.5, self.low=33984.6, self.vol=1157.799, self.amt=39397677.9418, ukdf['pct'].iloc[-1]=0.000609 , ukdf['amount'].iloc[-1]=39397677.9418, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5763, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '37.141', 'enterprice': '26844', 'countrevence': '0', 'unrealprofit': '266617.65227409455', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '34022.52648755', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=1
--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=1, self.total=996015.990996, self.flagDict['side']='buy', self.tradeCount=1, self.count=47669
self.closeSec=1698337499, self.tradeDate='20231027', self.openTime='002000', self.closeTime='002459', self.symbol='BTCUSDT', self.open=34017.3, self.close=33980.2, self.high=34036.8, self.low=33975.3, self.vol=1126.436, self.amt=38292824.2832 
127.0.0.1 - - [27/Oct/2023 00:25:01] "POST / HTTP/1.1" 200 -
2023-10-27 00:25:03,170:INFO:sr_min:main.py:172:handleKline:2219263: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5760  20231027   000000    000459  ...         0.0        0.0       0
5761  20231027   000500    000959  ...         0.0        0.0       0
5762  20231027   001000    001459  ...         0.0        0.0       0
5763  20231027   001500    001959  ...         0.0        0.0       0
5764  20231027   002000    002459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-10-27 00:25:03,176:INFO:sr_min:main.py:175:handleKline:2219263: self.closeSec=1698337499, self.tradeDate='20231027', self.openTime='002000', self.closeTime='002459',self.symbol='BTCUSDT',self.open=34017.3, self.close=33980.2, self.high=34036.8, self.low=33975.3, self.vol=1126.436, self.amt=38292824.2832, ukdf['pct'].iloc[-1]=-0.001091 , ukdf['amount'].iloc[-1]=38292824.2832, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5764, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '37.141', 'enterprice': '26844', 'countrevence': '0', 'unrealprofit': '264997.09749762782', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '33978.89398502', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=1


## /root/FIL/strategy/s_rsrs/log.txt ----- -----

723  20231026   120000    155959  1698307199  ...    723  0.880106 -0.082705     NaN
724  20231026   160000    195959  1698321599  ...    724  0.853465 -0.131839     NaN

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '41.361', 'enterprice': '29539.2', 'countrevence': '0', 'unrealprofit': '188877.42740648154', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '34105.75853114', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-9223372036854775808, self.sign=1
127.0.0.1 - - [27/Oct/2023 00:00:01] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='s_rsrs', self.symbol='BTCUSDT', interval='4h', intervalSec=14400, wid=25, thd=0.6, self.sign=1, self.total=1220549.0803488, self.flagDict['side']='buy', self.tradeCount=37, self.count=993
self.closeSec=1698335999, self.tradeDate='20231026', self.openTime='200000', self.closeTime='235959', self.symbol='BTCUSDT', self.open=34104.1, self.close=34050.0, self.high=34368.1, self.low=33830.0, self.vol=100680.98, self.amt=3434657878.62267 
2023-10-27 00:00:01,578:INFO:s_rsrs:main.py:141:handleKline:2218689: self.closeSec=1698335999, self.tradeDate='20231026', self.openTime='200000', self.closeTime='235959',self.symbol='BTCUSDT',self.open=34104.1, self.close=34050.0, self.high=34368.1, self.low=33830.0, self.vol=100680.98, self.amt=3434657878.62267 
2023-10-27 00:00:01,595:INFO:s_rsrs:main.py:142:handleKline:2218689: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime  ...         vol           amt       pct
721  20231026   040000    075959  ...   49659.588  1.716450e+09 -0.006871
722  20231026   080000    115959  ...   35395.767  1.226934e+09  0.008571
723  20231026   120000    155959  ...   42890.458  1.484707e+09 -0.003444
724  20231026   160000    195959  ...   78780.151  2.703214e+09 -0.016138
725  20231026   200000    235959  ...  100680.980  3.434658e+09 -0.001589

[5 rows x 11 columns]
2023-10-27 00:00:02,378:INFO:s_rsrs:main.py:151:handleKline:2218689: df_s.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec  ...  index      beta    zscore  signal
721  20231026   040000    075959  1698278399  ...    721  0.998519  0.124421     NaN
722  20231026   080000    115959  1698292799  ...    722  0.940070  0.020946     NaN
723  20231026   120000    155959  1698307199  ...    723  0.880106 -0.082705     NaN
724  20231026   160000    195959  1698321599  ...    724  0.853465 -0.131839     NaN
725  20231026   200000    235959  1698335999  ...    725  0.790856 -0.239494     NaN

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '41.361', 'enterprice': '29539.2', 'countrevence': '0', 'unrealprofit': '186519.2481721227', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '34048.7439707', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-9223372036854775808, self.sign=1


