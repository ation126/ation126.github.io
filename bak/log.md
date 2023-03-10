# 20230310 08:26:02

## /root/FIL/strategy/amihud/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=993672.4896432, self.flagDict['side']='sell', self.tradeCount=2, self.count=29596
self.closeSec=1678407599, self.tradeDate='20230310', self.openTime='081500', self.closeTime='081959', self.symbol='BTCUSDT', self.open=20195.3, self.close=20147.8, self.high=20230.6, self.low=20100.0, self.vol=11624.42, self.amt=234412664.72527 
127.0.0.1 - - [10/Mar/2023 08:20:01] "POST / HTTP/1.1" 200 -
2023-03-10 08:20:01,571:INFO:amihud:main.py:172:handleKline:200676: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5855  20230310   075500    075959  ...         0.0        0.0       0
5856  20230310   080000    080459  ...         0.0        0.0       0
5857  20230310   080500    080959  ...         0.0        0.0       0
5858  20230310   081000    081459  ...         0.0        0.0       0
5859  20230310   081500    081959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-03-10 08:20:01,571:INFO:amihud:main.py:175:handleKline:200676: self.closeSec=1678407599, self.tradeDate='20230310', self.openTime='081500', self.closeTime='081959',self.symbol='BTCUSDT',self.open=20195.3, self.close=20147.8, self.high=20230.6, self.low=20100.0, self.vol=11624.42, self.amt=234412664.72527, ukdf['pct'].iloc[-1]=-0.002347 , ukdf['amount'].iloc[-1]=234412664.72527, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5859, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '60.176', 'enterprice': '16529.3', 'countrevence': '0', 'unrealprofit': '-217990.28623817616', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '20151.84530441', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1
--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=993672.4896432, self.flagDict['side']='sell', self.tradeCount=2, self.count=29597
self.closeSec=1678407899, self.tradeDate='20230310', self.openTime='082000', self.closeTime='082459', self.symbol='BTCUSDT', self.open=20147.8, self.close=20100.0, self.high=20155.4, self.low=20000.1, self.vol=16302.903, self.amt=327333905.6941 
127.0.0.1 - - [10/Mar/2023 08:25:01] "POST / HTTP/1.1" 200 -
2023-03-10 08:25:01,532:INFO:amihud:main.py:172:handleKline:200676: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5856  20230310   080000    080459  ...         0.0        0.0       0
5857  20230310   080500    080959  ...         0.0        0.0       0
5858  20230310   081000    081459  ...         0.0        0.0       0
5859  20230310   081500    081959  ...         0.0        0.0       0
5860  20230310   082000    082459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-03-10 08:25:01,533:INFO:amihud:main.py:175:handleKline:200676: self.closeSec=1678407899, self.tradeDate='20230310', self.openTime='082000', self.closeTime='082459',self.symbol='BTCUSDT',self.open=20147.8, self.close=20100.0, self.high=20155.4, self.low=20000.1, self.vol=16302.903, self.amt=327333905.6941, ukdf['pct'].iloc[-1]=-0.002372 , ukdf['amount'].iloc[-1]=327333905.6941, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5860, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '60.176', 'enterprice': '16529.3', 'countrevence': '0', 'unrealprofit': '-214864.4256', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '20099.9', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1


## /root/FIL/strategy/factorcheck/log.txt ----- -----

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.8000954209087232, self.count=30162 

self.closeSec=1678407599, self.tradeDate='20230310', self.openTime='081500', self.closeTime='081959', self.symbol='BTCUSDT', self.open=20195.3, self.close=20147.8, self.high=20230.6, self.low=20100.0 
2023-03-10 08:20:01,493:INFO:factorcheck2:main.py:126:handleKline:185239: self.closeSec=1678407599, self.tradeDate='20230310', self.openTime='081500', self.closeTime='081959',self.symbol='BTCUSDT',self.open=20195.3, self.close=20147.8, self.high=20230.6, self.low=20100.0   
2023-03-10 08:20:01,538:INFO:factorcheck2:main.py:127:handleKline:185239: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1535  20230310   075500    075959  1678406399  ...  20324.9  0.000216   1535    5
1536  20230310   080000    080459  1678406699  ...  20311.0 -0.001332   1536    0
1537  20230310   080500    080959  1678406999  ...  20295.1 -0.001279   1537    1
1538  20230310   081000    081459  1678407299  ...  20184.0 -0.004927   1538    2
1539  20230310   081500    081959  1678407599  ...  20100.0 -0.002347   1539    3

[5 rows x 11 columns]
2023-03-10 08:20:01,538:INFO:factorcheck2:main.py:128:handleKline:185239: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': False, 'isOpen': True, 'isClose': False, 'isTrig': True}
127.0.0.1 - - [10/Mar/2023 08:25:01] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.8000954209087232, self.count=30163 

self.closeSec=1678407899, self.tradeDate='20230310', self.openTime='082000', self.closeTime='082459', self.symbol='BTCUSDT', self.open=20147.8, self.close=20100.0, self.high=20155.4, self.low=20000.1 
2023-03-10 08:25:01,533:INFO:factorcheck2:main.py:126:handleKline:185239: self.closeSec=1678407899, self.tradeDate='20230310', self.openTime='082000', self.closeTime='082459',self.symbol='BTCUSDT',self.open=20147.8, self.close=20100.0, self.high=20155.4, self.low=20000.1   
2023-03-10 08:25:01,554:INFO:factorcheck2:main.py:127:handleKline:185239: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1536  20230310   080000    080459  1678406699  ...  20311.0 -0.001332   1536    0
1537  20230310   080500    080959  1678406999  ...  20295.1 -0.001279   1537    1
1538  20230310   081000    081459  1678407299  ...  20184.0 -0.004927   1538    2
1539  20230310   081500    081959  1678407599  ...  20100.0 -0.002347   1539    3
1540  20230310   082000    082459  1678407899  ...  20000.1 -0.002372   1540    4

[5 rows x 11 columns]
2023-03-10 08:25:01,554:INFO:factorcheck2:main.py:128:handleKline:185239: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': False, 'isOpen': True, 'isClose': False, 'isTrig': True}


## /root/FIL/strategy/logic/log.txt ----- -----

536     0  0.540167  0.459833       0  ...  0.943145  -1.0  0.0000  0.872526
537     1  0.362107  0.637893       1  ...  0.936965  -1.0  0.0000  0.878244
538     0  0.514494  0.485506       0  ...  0.937375  -1.0  0.0000  0.877859
539     1  0.484409  0.515591       1  ...  0.936794  -1.0  0.0000  0.878403
540     0  0.582846  0.417154       1  ...  0.935627   1.0 -0.0016  0.878714

[5 rows x 10 columns]
2023-03-10 08:00:34,669:INFO:logic:main.py:478:getModel:885513: df_panel.iloc[-5:,:] :
    pred    prob_0    prob_1  actual  ...       nav  sign   cost_        bm
45     0  0.540649  0.459351       0  ...  0.943145  -1.0  0.0000  0.869417
46     1  0.362204  0.637796       1  ...  0.936965  -1.0  0.0000  0.876986
47     0  0.515079  0.484921       0  ...  0.937375  -1.0  0.0000  0.877151
48     1  0.484851  0.515149       1  ...  0.936794  -1.0  0.0000  0.878403
49     0  0.582846  0.417154       1  ...  0.935627   1.0 -0.0016  0.878714

[5 rows x 10 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '31.263', 'enterprice': '21498.6', 'countrevence': '0', 'unrealprofit': '36057.60727317261', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '20345.23636653', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
handlebackTrade > queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '31.263', 'enterprice': '21498.6', 'countrevence': '0', 'unrealprofit': '36057.60727317261', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '20345.23636653', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
2023-03-10 08:00:40,366:INFO:logic:main.py:500:queryContractAssets:885513: queryContractAssets: assets=ContractAssetReturn{'result': [ContractAsset{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'asset': 'USDT', 'free': '709634.0785361', 'total': '709634.0785361', 'margin': '0', 'unreal': '0', 'type': 'AssetType_ucontract'}]}
2023-03-10 08:00:40,561:DEBUG:logic:main.py:571:openBuy:885513: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': True, 'isCloseBuy': False, 'isCloseSell': False, 'isOpen': True, 'isClose': False, 'isTrig': False}
2023-03-10 08:00:40,561:INFO:logic:main.py:572:openBuy:885513: ret = self.client.insertMarketUOrder("simulator", "BTCUSDT", 34.769, "buy"), ret=InsertOrderReturn{'result': 'success', 'clientorderid': '41930F1678406440560I0L64'}
2023-03-10 08:00:40,578:INFO:logic:main.py:494:insertFactor:885513: curDateTime:3100800, name:logic, symbol:BTCUSDT, tradeDate:20230310, closeTime:075959, close:20348.3, sign:1, total:709634.0785361, side:buy  
127.0.0.1 - - [10/Mar/2023 08:00:40] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [10/Mar/2023 08:00:40] "POST / HTTP/1.1" 200 -
2023-03-10 08:00:40,579:INFO:logic:main.py:661:handleOrderNew:885513: handleOrderNew: data=OrderType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'clientorderid': '41929F1678406435256I0L64', 'symbol': 'BTCUSDT', 'gatewayorderid': 1678406435346808, 'quantity': '31.263', 'price': '20342.6', 'stopprice': '0', 'ordertype': '', 'side': 'BUY', 'status': 'FILLED', 'positionside': 'LONG', 'createtime': 1678406434930, 'updatetime': 1678406435346, 'tradetype': 'usdt', 'selfid': 41929, 'filltrades': [TradeType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'tradeid': 1678406435346, 'clientorderid': '41929F1678406435256I0L64', 'price': '20342.6', 'quantity': '31.263', 'commission': '635.9707038', 'commissionasset': 'USDT', 'tradetime': 1678406435346, 'tradetype': 'usdt', 'gatetype': 'simulator', 'handletime': 1678406435346}], 'gatetype': 'simulator', 'handletime': 0}
2023-03-10 08:00:40,579:INFO:logic:main.py:664:handleOrderFilled:885513: handleOrderFilled: data=OrderType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'clientorderid': '41929F1678406435256I0L64', 'symbol': 'BTCUSDT', 'gatewayorderid': 1678406435346808, 'quantity': '31.263', 'price': '20342.6', 'stopprice': '0', 'ordertype': '', 'side': 'BUY', 'status': 'FILLED', 'positionside': 'LONG', 'createtime': 1678406434930, 'updatetime': 1678406435346, 'tradetype': 'usdt', 'selfid': 41929, 'filltrades': [TradeType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'tradeid': 1678406435346, 'clientorderid': '41929F1678406435256I0L64', 'price': '20342.6', 'quantity': '31.263', 'commission': '635.9707038', 'commissionasset': 'USDT', 'tradetime': 1678406435346, 'tradetype': 'usdt', 'gatetype': 'simulator', 'handletime': 1678406435346}], 'gatetype': 'simulator', 'handletime': 0}
127.0.0.1 - - [10/Mar/2023 08:00:40] "POST / HTTP/1.1" 200 -
2023-03-10 08:00:40,671:INFO:logic:main.py:661:handleOrderNew:885513: handleOrderNew: data=OrderType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'clientorderid': '41930F1678406440560I0L64', 'symbol': 'BTCUSDT', 'gatewayorderid': 1678406440645843, 'quantity': '34.769', 'price': '20343.7', 'stopprice': '0', 'ordertype': '', 'side': 'BUY', 'status': 'FILLED', 'positionside': 'LONG', 'createtime': 1678406440376, 'updatetime': 1678406440645, 'tradetype': 'usdt', 'selfid': 41930, 'filltrades': [TradeType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'tradeid': 1678406440645, 'clientorderid': '41930F1678406440560I0L64', 'price': '20343.7', 'quantity': '34.769', 'commission': '707.3301053', 'commissionasset': 'USDT', 'tradetime': 1678406440645, 'tradetype': 'usdt', 'gatetype': 'simulator', 'handletime': 1678406440645}], 'gatetype': 'simulator', 'handletime': 0}
2023-03-10 08:00:40,890:INFO:logic:main.py:664:handleOrderFilled:885513: handleOrderFilled: data=OrderType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'clientorderid': '41930F1678406440560I0L64', 'symbol': 'BTCUSDT', 'gatewayorderid': 1678406440645843, 'quantity': '34.769', 'price': '20343.7', 'stopprice': '0', 'ordertype': '', 'side': 'BUY', 'status': 'FILLED', 'positionside': 'LONG', 'createtime': 1678406440376, 'updatetime': 1678406440645, 'tradetype': 'usdt', 'selfid': 41930, 'filltrades': [TradeType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'tradeid': 1678406440645, 'clientorderid': '41930F1678406440560I0L64', 'price': '20343.7', 'quantity': '34.769', 'commission': '707.3301053', 'commissionasset': 'USDT', 'tradetime': 1678406440645, 'tradetype': 'usdt', 'gatetype': 'simulator', 'handletime': 1678406440645}], 'gatetype': 'simulator', 'handletime': 0}
127.0.0.1 - - [10/Mar/2023 08:00:40] "POST / HTTP/1.1" 200 -


## /root/FIL/strategy/modifiedmom/log.txt ----- -----

623  20230310   075000    075959  1678406399  20325.8  20348.3  0.001107
2023-03-10 08:00:02,157:INFO:modifiedmom:main.py:146:handleKline:185213: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False}
127.0.0.1 - - [10/Mar/2023 08:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=15080 

self.closeSec=1678406999, self.tradeDate='20230310', self.openTime='080000', self.closeTime='080959', self.symbol='BTCUSDT', self.open='20348.4', self.close='20295.2'
2023-03-10 08:10:01,742:INFO:modifiedmom:main.py:144:handleKline:185213: self.closeSec=1678406999, self.tradeDate='20230310', self.openTime='080000', self.closeTime='080959',self.symbol='BTCUSDT',self.open='20348.4', self.close='20295.2'
2023-03-10 08:10:01,797:INFO:modifiedmom:main.py:145:handleKline:185213: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
620  20230310   072000    072959  1678404599    20325  20341.1  0.000787
621  20230310   073000    073959  1678405199    20341  20344.7  0.000177
622  20230310   074000    074959  1678405799  20344.7  20325.8 -0.000929
623  20230310   075000    075959  1678406399  20325.8  20348.3  0.001107
624  20230310   080000    080959  1678406999  20348.4  20295.2 -0.002610
2023-03-10 08:10:01,797:INFO:modifiedmom:main.py:146:handleKline:185213: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=15081 

self.closeSec=1678407599, self.tradeDate='20230310', self.openTime='081000', self.closeTime='081959', self.symbol='BTCUSDT', self.open='20295.1', self.close='20147.8'
2023-03-10 08:20:01,612:INFO:modifiedmom:main.py:144:handleKline:185213: self.closeSec=1678407599, self.tradeDate='20230310', self.openTime='081000', self.closeTime='081959',self.symbol='BTCUSDT',self.open='20295.1', self.close='20147.8'
127.0.0.1 - - [10/Mar/2023 08:20:01] "POST / HTTP/1.1" 200 -
2023-03-10 08:20:01,633:INFO:modifiedmom:main.py:145:handleKline:185213: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
621  20230310   073000    073959  1678405199    20341  20344.7  0.000177
622  20230310   074000    074959  1678405799  20344.7  20325.8 -0.000929
623  20230310   075000    075959  1678406399  20325.8  20348.3  0.001107
624  20230310   080000    080959  1678406999  20348.4  20295.2 -0.002610
625  20230310   081000    081959  1678407599  20295.1  20147.8 -0.007263
2023-03-10 08:20:01,633:INFO:modifiedmom:main.py:146:handleKline:185213: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False}


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

17471  20230310   075000    075959  1678406399  20325.8  20348.3
2023-03-10 08:00:02,175:INFO:pyemd2:main.py:127:handleKline:185189: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=15081 

self.closeSec=1678406999, self.tradeDate='20230310', self.openTime='080000', self.closeTime='080959', self.symbol='BTCUSDT', self.open='20348.4', self.close='20295.2'
127.0.0.1 - - [10/Mar/2023 08:10:01] "POST / HTTP/1.1" 200 -
2023-03-10 08:10:01,765:INFO:pyemd2:main.py:125:handleKline:185189: self.closeSec=1678406999, self.tradeDate='20230310', self.openTime='080000', self.closeTime='080959',self.symbol='BTCUSDT',self.open='20348.4', self.close='20295.2'
2023-03-10 08:10:01,777:INFO:pyemd2:main.py:126:handleKline:185189: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17468  20230310   072000    072959  1678404599    20325  20341.1
17469  20230310   073000    073959  1678405199    20341  20344.7
17470  20230310   074000    074959  1678405799  20344.7  20325.8
17471  20230310   075000    075959  1678406399  20325.8  20348.3
17472  20230310   080000    080959  1678406999  20348.4  20295.2
2023-03-10 08:10:01,777:INFO:pyemd2:main.py:127:handleKline:185189: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=15082 

self.closeSec=1678407599, self.tradeDate='20230310', self.openTime='081000', self.closeTime='081959', self.symbol='BTCUSDT', self.open='20295.1', self.close='20147.8'
127.0.0.1 - - [10/Mar/2023 08:20:01] "POST / HTTP/1.1" 200 -
2023-03-10 08:20:01,632:INFO:pyemd2:main.py:125:handleKline:185189: self.closeSec=1678407599, self.tradeDate='20230310', self.openTime='081000', self.closeTime='081959',self.symbol='BTCUSDT',self.open='20295.1', self.close='20147.8'
2023-03-10 08:20:01,664:INFO:pyemd2:main.py:126:handleKline:185189: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17469  20230310   073000    073959  1678405199    20341  20344.7
17470  20230310   074000    074959  1678405799  20344.7  20325.8
17471  20230310   075000    075959  1678406399  20325.8  20348.3
17472  20230310   080000    080959  1678406999  20348.4  20295.2
17473  20230310   081000    081959  1678407599  20295.1  20147.8
2023-03-10 08:20:01,664:INFO:pyemd2:main.py:127:handleKline:185189: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}


## /root/FIL/strategy/similarity/log.txt ----- -----

12143  20230310   075000    075959  1678406399  20325.8  20348.3
2023-03-10 08:00:02,159:INFO:testStrategy:main.py:103:handleKline:185174: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}
127.0.0.1 - - [10/Mar/2023 08:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=15081 

self.closeSec=1678406999, self.tradeDate='20230310', self.openTime='080000', self.closeTime='080959', self.symbol='BTCUSDT', self.open='20348.4', self.close='20295.2'
2023-03-10 08:10:01,758:INFO:testStrategy:main.py:101:handleKline:185174: self.closeSec=1678406999, self.tradeDate='20230310', self.openTime='080000', self.closeTime='080959',self.symbol='BTCUSDT',self.open='20348.4', self.close='20295.2'
2023-03-10 08:10:01,784:INFO:testStrategy:main.py:102:handleKline:185174: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12140  20230310   072000    072959  1678404599    20325  20341.1
12141  20230310   073000    073959  1678405199    20341  20344.7
12142  20230310   074000    074959  1678405799  20344.7  20325.8
12143  20230310   075000    075959  1678406399  20325.8  20348.3
12144  20230310   080000    080959  1678406999  20348.4  20295.2
2023-03-10 08:10:01,785:INFO:testStrategy:main.py:103:handleKline:185174: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=15082 

self.closeSec=1678407599, self.tradeDate='20230310', self.openTime='081000', self.closeTime='081959', self.symbol='BTCUSDT', self.open='20295.1', self.close='20147.8'
127.0.0.1 - - [10/Mar/2023 08:20:01] "POST / HTTP/1.1" 200 -
2023-03-10 08:20:01,620:INFO:testStrategy:main.py:101:handleKline:185174: self.closeSec=1678407599, self.tradeDate='20230310', self.openTime='081000', self.closeTime='081959',self.symbol='BTCUSDT',self.open='20295.1', self.close='20147.8'
2023-03-10 08:20:01,636:INFO:testStrategy:main.py:102:handleKline:185174: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12141  20230310   073000    073959  1678405199    20341  20344.7
12142  20230310   074000    074959  1678405799  20344.7  20325.8
12143  20230310   075000    075959  1678406399  20325.8  20348.3
12144  20230310   080000    080959  1678406999  20348.4  20295.2
12145  20230310   081000    081959  1678407599  20295.1  20147.8
2023-03-10 08:20:01,636:INFO:testStrategy:main.py:103:handleKline:185174: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}


## /root/FIL/strategy/sr_min/log.txt ----- -----

127.0.0.1 - - [10/Mar/2023 08:20:01] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=0, self.total=1000000.0, self.flagDict['side']='', self.tradeCount=0, self.count=25594
self.closeSec=1678407599, self.tradeDate='20230310', self.openTime='081500', self.closeTime='081959', self.symbol='BTCUSDT', self.open=20195.3, self.close=20147.8, self.high=20230.6, self.low=20100.0, self.vol=11624.42, self.amt=234412664.72527 
2023-03-10 08:20:01,558:INFO:sr_min:main.py:172:handleKline:449472: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5855  20230310   075500    075959  ...         0.0        0.0       0
5856  20230310   080000    080459  ...         0.0        0.0       0
5857  20230310   080500    080959  ...         0.0        0.0       0
5858  20230310   081000    081459  ...         0.0        0.0       0
5859  20230310   081500    081959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-03-10 08:20:01,559:INFO:sr_min:main.py:175:handleKline:449472: self.closeSec=1678407599, self.tradeDate='20230310', self.openTime='081500', self.closeTime='081959',self.symbol='BTCUSDT',self.open=20195.3, self.close=20147.8, self.high=20230.6, self.low=20100.0, self.vol=11624.42, self.amt=234412664.72527, ukdf['pct'].iloc[-1]=-0.002347 , ukdf['amount'].iloc[-1]=234412664.72527, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5859, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': []}
type(curSign)=<class 'int'>, curSign=0, self.sign=0
127.0.0.1 - - [10/Mar/2023 08:25:01] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=0, self.total=1000000.0, self.flagDict['side']='', self.tradeCount=0, self.count=25595
self.closeSec=1678407899, self.tradeDate='20230310', self.openTime='082000', self.closeTime='082459', self.symbol='BTCUSDT', self.open=20147.8, self.close=20100.0, self.high=20155.4, self.low=20000.1, self.vol=16302.903, self.amt=327333905.6941 
2023-03-10 08:25:01,596:INFO:sr_min:main.py:172:handleKline:449472: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5856  20230310   080000    080459  ...         0.0        0.0       0
5857  20230310   080500    080959  ...         0.0        0.0       0
5858  20230310   081000    081459  ...         0.0        0.0       0
5859  20230310   081500    081959  ...         0.0        0.0       0
5860  20230310   082000    082459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-03-10 08:25:01,597:INFO:sr_min:main.py:175:handleKline:449472: self.closeSec=1678407899, self.tradeDate='20230310', self.openTime='082000', self.closeTime='082459',self.symbol='BTCUSDT',self.open=20147.8, self.close=20100.0, self.high=20155.4, self.low=20000.1, self.vol=16302.903, self.amt=327333905.6941, ukdf['pct'].iloc[-1]=-0.002372 , ukdf['amount'].iloc[-1]=327333905.6941, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5860, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': []}
type(curSign)=<class 'int'>, curSign=0, self.sign=0


## /root/FIL/strategy/s_rsrs/log.txt ----- -----

719  20230309   200000    235959  1678377599  ...    719  0.503191 -0.169857     NaN
720  20230310   000000    035959  1678391999  ...    720  0.347579 -0.711117    -1.0

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '42.135', 'enterprice': '23350.3', 'countrevence': '0', 'unrealprofit': '105516.5712101022', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '20846.05006028', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-1, self.sign=-1
--handleKline--:  version='2.0.0', self.name='s_rsrs', self.symbol='BTCUSDT', interval='4h', intervalSec=14400, wid=25, thd=0.6, self.sign=-1, self.total=982881.0256095, self.flagDict['side']='sell', self.tradeCount=23, self.count=628
127.0.0.1 - - [10/Mar/2023 08:00:02] "POST / HTTP/1.1" 200 -
self.closeSec=1678406399, self.tradeDate='20230310', self.openTime='040000', self.closeTime='075959', self.symbol='BTCUSDT', self.open=20845.6, self.close=20348.3, self.high=20858.4, self.low=20003.5, self.vol=336530.824, self.amt=6868830385.17434 
2023-03-10 08:00:02,032:INFO:s_rsrs:main.py:141:handleKline:185271: self.closeSec=1678406399, self.tradeDate='20230310', self.openTime='040000', self.closeTime='075959',self.symbol='BTCUSDT',self.open=20845.6, self.close=20348.3, self.high=20858.4, self.low=20003.5, self.vol=336530.824, self.amt=6868830385.17434 
2023-03-10 08:00:02,117:INFO:s_rsrs:main.py:142:handleKline:185271: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime  ...         vol           amt       pct
717  20230309   120000    155959  ...   30228.722  6.564517e+08 -0.003750
718  20230309   160000    195959  ...   84936.590  1.837361e+09 -0.000766
719  20230309   200000    235959  ...  128925.274  2.797151e+09 -0.001246
720  20230310   000000    035959  ...  317671.191  6.733776e+09 -0.036599
721  20230310   040000    075959  ...  336530.824  6.868830e+09 -0.023852

[5 rows x 11 columns]
2023-03-10 08:00:04,770:INFO:s_rsrs:main.py:151:handleKline:185271: df_s.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec  ...  index      beta    zscore  signal
717  20230309   120000    155959  1678348799  ...    717  0.364721 -0.637468    -1.0
718  20230309   160000    195959  1678363199  ...    718  0.462091 -0.306332     NaN
719  20230309   200000    235959  1678377599  ...    719  0.503191 -0.169857     NaN
720  20230310   000000    035959  1678391999  ...    720  0.347579 -0.711117    -1.0
721  20230310   040000    075959  1678406399  ...    721  0.418595 -0.460593     NaN

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '42.135', 'enterprice': '23350.3', 'countrevence': '0', 'unrealprofit': '126346.8817838202', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '20351.67933348', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-9223372036854775808, self.sign=-1


