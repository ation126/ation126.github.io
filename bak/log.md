# 20230606 08:26:01

## /root/FIL/strategy/amihud/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=373746.4768026, self.flagDict['side']='sell', self.tradeCount=2, self.count=6592
self.closeSec=1686010799, self.tradeDate='20230606', self.openTime='081500', self.closeTime='081959', self.symbol='BTCUSDT', self.open=25715.7, self.close=25734.8, self.high=25740.2, self.low=25715.6, self.vol=1472.723, self.amt=37890661.2181 
127.0.0.1 - - [06/Jun/2023 08:20:02] "POST / HTTP/1.1" 200 -
2023-06-06 08:20:07,452:INFO:amihud:main.py:172:handleKline:2219019: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5855  20230606   075500    075959  ...         0.0        0.0       0
5856  20230606   080000    080459  ...         0.0        0.0       0
5857  20230606   080500    080959  ...         0.0        0.0       0
5858  20230606   081000    081459  ...         0.0        0.0       0
5859  20230606   081500    081959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-06-06 08:20:07,482:INFO:amihud:main.py:175:handleKline:2219019: self.closeSec=1686010799, self.tradeDate='20230606', self.openTime='081500', self.closeTime='081959',self.symbol='BTCUSDT',self.open=25715.7, self.close=25734.8, self.high=25740.2, self.low=25715.6, self.vol=1472.723, self.amt=37890661.2181, ukdf['pct'].iloc[-1]=0.000747 , ukdf['amount'].iloc[-1]=37890661.2181, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5859, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '13.926', 'enterprice': '26864.9', 'countrevence': '0', 'unrealprofit': '15731.75491749048', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '25735.23211852', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1
--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=373746.4768026, self.flagDict['side']='sell', self.tradeCount=2, self.count=6593
self.closeSec=1686011099, self.tradeDate='20230606', self.openTime='082000', self.closeTime='082459', self.symbol='BTCUSDT', self.open=25734.7, self.close=25735.0, self.high=25741.7, self.low=25730.2, self.vol=514.999, self.amt=13253541.1124 
127.0.0.1 - - [06/Jun/2023 08:25:00] "POST / HTTP/1.1" 200 -
2023-06-06 08:25:00,785:INFO:amihud:main.py:172:handleKline:2219019: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5856  20230606   080000    080459  ...         0.0        0.0       0
5857  20230606   080500    080959  ...         0.0        0.0       0
5858  20230606   081000    081459  ...         0.0        0.0       0
5859  20230606   081500    081959  ...         0.0        0.0       0
5860  20230606   082000    082459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-06-06 08:25:00,785:INFO:amihud:main.py:175:handleKline:2219019: self.closeSec=1686011099, self.tradeDate='20230606', self.openTime='082000', self.closeTime='082459',self.symbol='BTCUSDT',self.open=25734.7, self.close=25735.0, self.high=25741.7, self.low=25730.2, self.vol=514.999, self.amt=13253541.1124, ukdf['pct'].iloc[-1]=8e-06 , ukdf['amount'].iloc[-1]=13253541.1124, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5860, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '13.926', 'enterprice': '26864.9', 'countrevence': '0', 'unrealprofit': '15727.89055568214', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '25735.50961111', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1


## /root/FIL/strategy/factorcheck/log.txt ----- -----


self.closeSec=1686010799, self.tradeDate='20230606', self.openTime='081500', self.closeTime='081959', self.symbol='BTCUSDT', self.open=25715.7, self.close=25734.8, self.high=25740.2, self.low=25715.6 
127.0.0.1 - - [06/Jun/2023 08:20:01] "POST / HTTP/1.1" 200 -
2023-06-06 08:20:04,911:INFO:factorcheck2:main.py:126:handleKline:2218005: self.closeSec=1686010799, self.tradeDate='20230606', self.openTime='081500', self.closeTime='081959',self.symbol='BTCUSDT',self.open=25715.7, self.close=25734.8, self.high=25740.2, self.low=25715.6   
2023-06-06 08:20:06,352:INFO:factorcheck2:main.py:127:handleKline:2218005: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1535  20230606   075500    075959  1686009599  ...  25696.3 -0.000397   1535    5
1536  20230606   080000    080459  1686009899  ...  25694.7  0.000385   1536    0
1537  20230606   080500    080959  1686010199  ...  25677.0 -0.000575   1537    1
1538  20230606   081000    081459  1686010499  ...  25700.7  0.000257   1538    2
1539  20230606   081500    081959  1686010799  ...  25715.6  0.000747   1539    3

[5 rows x 11 columns]
2023-06-06 08:20:06,361:INFO:factorcheck2:main.py:128:handleKline:2218005: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': False, 'isOpen': True, 'isClose': False, 'isTrig': True}
127.0.0.1 - - [06/Jun/2023 08:25:00] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.7639698319809799, self.count=6595 

self.closeSec=1686011099, self.tradeDate='20230606', self.openTime='082000', self.closeTime='082459', self.symbol='BTCUSDT', self.open=25734.7, self.close=25735.0, self.high=25741.7, self.low=25730.2 
2023-06-06 08:25:00,708:INFO:factorcheck2:main.py:126:handleKline:2218005: self.closeSec=1686011099, self.tradeDate='20230606', self.openTime='082000', self.closeTime='082459',self.symbol='BTCUSDT',self.open=25734.7, self.close=25735.0, self.high=25741.7, self.low=25730.2   
2023-06-06 08:25:00,757:INFO:factorcheck2:main.py:127:handleKline:2218005: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1536  20230606   080000    080459  1686009899  ...  25694.7  0.000385   1536    0
1537  20230606   080500    080959  1686010199  ...  25677.0 -0.000575   1537    1
1538  20230606   081000    081459  1686010499  ...  25700.7  0.000257   1538    2
1539  20230606   081500    081959  1686010799  ...  25715.6  0.000747   1539    3
1540  20230606   082000    082459  1686011099  ...  25730.2  0.000008   1540    4

[5 rows x 11 columns]
2023-06-06 08:25:00,757:INFO:factorcheck2:main.py:128:handleKline:2218005: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': False, 'isOpen': True, 'isClose': False, 'isTrig': True}


## /root/FIL/strategy/logic/log.txt ----- -----

536     0  0.512980  0.487020       1  ...  1.079213  -1.0  0.0000  0.974584
537     0  0.544884  0.455116       1  ...  1.077083  -1.0  0.0000  0.976507
538     0  0.532732  0.467268       1  ...  1.076911  -1.0  0.0000  0.976663
539     0  0.524447  0.475553       1  ...  1.070960  -1.0  0.0000  0.982060
540     0  0.561591  0.438409       0  ...  1.064136   1.0 -0.0016  0.977374

[5 rows x 10 columns]
2023-06-06 08:00:33,665:INFO:logic:main.py:478:getModel:2218526: df_panel.iloc[-5:,:] :
    pred    prob_0    prob_1  actual  ...       nav  sign   cost_        bm
45     0  0.512994  0.487006       1  ...  1.079213  -1.0  0.0000  0.978041
46     0  0.544768  0.455232       1  ...  1.077083  -1.0  0.0000  0.979224
47     0  0.532775  0.467225       1  ...  1.076911  -1.0  0.0000  0.978422
48     0  0.524447  0.475553       1  ...  1.070960  -1.0  0.0000  0.982060
49     0  0.561591  0.438409       0  ...  1.064136   1.0 -0.0016  0.977374

[5 rows x 10 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '27.545', 'enterprice': '25948.8', 'countrevence': '0', 'unrealprofit': '6192.116', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '25724', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
handlebackTrade > queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '27.545', 'enterprice': '25948.8', 'countrevence': '0', 'unrealprofit': '6170.08', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '25724.8', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
2023-06-06 08:00:40,639:INFO:logic:main.py:500:queryContractAssets:2218526: queryContractAssets: assets=ContractAssetReturn{'result': [ContractAsset{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'asset': 'USDT', 'free': '723574.2945', 'total': '723574.2945', 'margin': '0', 'unreal': '0', 'type': 'AssetType_ucontract'}]}
2023-06-06 08:00:41,123:DEBUG:logic:main.py:571:openBuy:2218526: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': True, 'isCloseBuy': False, 'isCloseSell': False, 'isOpen': True, 'isClose': False, 'isTrig': False}
2023-06-06 08:00:41,123:INFO:logic:main.py:572:openBuy:2218526: ret = self.client.insertMarketUOrder("simulator", "BTCUSDT", 28.054, "buy"), ret=InsertOrderReturn{'result': 'success', 'clientorderid': '42331F1686009641122I0L64'}
2023-06-06 08:00:41,144:INFO:logic:main.py:494:insertFactor:2218526: curDateTime:6060800, name:logic, symbol:BTCUSDT, tradeDate:20230606, closeTime:075959, close:25714.6, sign:1, total:723574.2945, side:buy  
127.0.0.1 - - [06/Jun/2023 08:00:41] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [06/Jun/2023 08:00:41] "POST / HTTP/1.1" 200 -
2023-06-06 08:00:41,147:INFO:logic:main.py:661:handleOrderNew:2218526: handleOrderNew: data=OrderType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'clientorderid': '42330F1686009635493I0L64', 'symbol': 'BTCUSDT', 'gatewayorderid': 1686009635923071, 'quantity': '27.545', 'price': '25725.4', 'stopprice': '0', 'ordertype': '', 'side': 'BUY', 'status': 'FILLED', 'positionside': 'LONG', 'createtime': 1686009634557, 'updatetime': 1686009635923, 'tradetype': 'usdt', 'selfid': 42330, 'filltrades': [TradeType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'tradeid': 1686009635923, 'clientorderid': '42330F1686009635493I0L64', 'price': '25725.4', 'quantity': '27.545', 'commission': '708.606143', 'commissionasset': 'USDT', 'tradetime': 1686009635923, 'tradetype': 'usdt', 'gatetype': 'simulator', 'handletime': 1686009635923}], 'gatetype': 'simulator', 'handletime': 0}
2023-06-06 08:00:41,147:INFO:logic:main.py:664:handleOrderFilled:2218526: handleOrderFilled: data=OrderType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'clientorderid': '42330F1686009635493I0L64', 'symbol': 'BTCUSDT', 'gatewayorderid': 1686009635923071, 'quantity': '27.545', 'price': '25725.4', 'stopprice': '0', 'ordertype': '', 'side': 'BUY', 'status': 'FILLED', 'positionside': 'LONG', 'createtime': 1686009634557, 'updatetime': 1686009635923, 'tradetype': 'usdt', 'selfid': 42330, 'filltrades': [TradeType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'tradeid': 1686009635923, 'clientorderid': '42330F1686009635493I0L64', 'price': '25725.4', 'quantity': '27.545', 'commission': '708.606143', 'commissionasset': 'USDT', 'tradetime': 1686009635923, 'tradetype': 'usdt', 'gatetype': 'simulator', 'handletime': 1686009635923}], 'gatetype': 'simulator', 'handletime': 0}
2023-06-06 08:00:41,575:INFO:logic:main.py:661:handleOrderNew:2218526: handleOrderNew: data=OrderType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'clientorderid': '42331F1686009641122I0L64', 'symbol': 'BTCUSDT', 'gatewayorderid': 1686009641528312, 'quantity': '28.054', 'price': '25722.1', 'stopprice': '0', 'ordertype': '', 'side': 'BUY', 'status': 'FILLED', 'positionside': 'LONG', 'createtime': 1686009640654, 'updatetime': 1686009641528, 'tradetype': 'usdt', 'selfid': 42331, 'filltrades': [TradeType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'tradeid': 1686009641528, 'clientorderid': '42331F1686009641122I0L64', 'price': '25722.1', 'quantity': '28.054', 'commission': '721.6077934', 'commissionasset': 'USDT', 'tradetime': 1686009641528, 'tradetype': 'usdt', 'gatetype': 'simulator', 'handletime': 1686009641528}], 'gatetype': 'simulator', 'handletime': 0}
127.0.0.1 - - [06/Jun/2023 08:00:41] "POST / HTTP/1.1" 200 -
2023-06-06 08:00:41,787:INFO:logic:main.py:664:handleOrderFilled:2218526: handleOrderFilled: data=OrderType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'clientorderid': '42331F1686009641122I0L64', 'symbol': 'BTCUSDT', 'gatewayorderid': 1686009641528312, 'quantity': '28.054', 'price': '25722.1', 'stopprice': '0', 'ordertype': '', 'side': 'BUY', 'status': 'FILLED', 'positionside': 'LONG', 'createtime': 1686009640654, 'updatetime': 1686009641528, 'tradetype': 'usdt', 'selfid': 42331, 'filltrades': [TradeType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'tradeid': 1686009641528, 'clientorderid': '42331F1686009641122I0L64', 'price': '25722.1', 'quantity': '28.054', 'commission': '721.6077934', 'commissionasset': 'USDT', 'tradetime': 1686009641528, 'tradetype': 'usdt', 'gatetype': 'simulator', 'handletime': 1686009641528}], 'gatetype': 'simulator', 'handletime': 0}
127.0.0.1 - - [06/Jun/2023 08:00:41] "POST / HTTP/1.1" 200 -


## /root/FIL/strategy/modifiedmom/log.txt ----- -----

623  20230606   075000    075959  1686009599  25751.6  25714.7 -0.001429
2023-06-06 08:00:02,264:INFO:modifiedmom:main.py:146:handleKline:2218259: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False}
127.0.0.1 - - [06/Jun/2023 08:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=3296 

self.closeSec=1686010199, self.tradeDate='20230606', self.openTime='080000', self.closeTime='080959', self.symbol='BTCUSDT', self.open='25714.6', self.close='25708.9'
2023-06-06 08:10:01,099:INFO:modifiedmom:main.py:144:handleKline:2218259: self.closeSec=1686010199, self.tradeDate='20230606', self.openTime='080000', self.closeTime='080959',self.symbol='BTCUSDT',self.open='25714.6', self.close='25708.9'
2023-06-06 08:10:01,142:INFO:modifiedmom:main.py:145:handleKline:2218259: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
620  20230606   072000    072959  1686007799  25745.1  25841.7  0.003791
621  20230606   073000    073959  1686008399  25841.8  25795.4 -0.001792
622  20230606   074000    074959  1686008999  25795.4  25751.5 -0.001702
623  20230606   075000    075959  1686009599  25751.6  25714.7 -0.001429
624  20230606   080000    080959  1686010199  25714.6  25708.9 -0.000226
2023-06-06 08:10:01,142:INFO:modifiedmom:main.py:146:handleKline:2218259: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=3297 

self.closeSec=1686010799, self.tradeDate='20230606', self.openTime='081000', self.closeTime='081959', self.symbol='BTCUSDT', self.open='25709', self.close='25734.8'
127.0.0.1 - - [06/Jun/2023 08:20:04] "POST / HTTP/1.1" 200 -
2023-06-06 08:20:07,407:INFO:modifiedmom:main.py:144:handleKline:2218259: self.closeSec=1686010799, self.tradeDate='20230606', self.openTime='081000', self.closeTime='081959',self.symbol='BTCUSDT',self.open='25709', self.close='25734.8'
2023-06-06 08:20:08,231:INFO:modifiedmom:main.py:145:handleKline:2218259: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
621  20230606   073000    073959  1686008399  25841.8  25795.4 -0.001792
622  20230606   074000    074959  1686008999  25795.4  25751.5 -0.001702
623  20230606   075000    075959  1686009599  25751.6  25714.7 -0.001429
624  20230606   080000    080959  1686010199  25714.6  25708.9 -0.000226
625  20230606   081000    081959  1686010799    25709  25734.8  0.001007
2023-06-06 08:20:08,232:INFO:modifiedmom:main.py:146:handleKline:2218259: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False}


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

17471  20230606   075000    075959  1686009599  25751.6  25714.7
2023-06-06 08:00:02,274:INFO:pyemd2:main.py:127:handleKline:2217508: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=3299 

self.closeSec=1686010199, self.tradeDate='20230606', self.openTime='080000', self.closeTime='080959', self.symbol='BTCUSDT', self.open='25714.6', self.close='25708.9'
2023-06-06 08:10:01,115:INFO:pyemd2:main.py:125:handleKline:2217508: self.closeSec=1686010199, self.tradeDate='20230606', self.openTime='080000', self.closeTime='080959',self.symbol='BTCUSDT',self.open='25714.6', self.close='25708.9'
127.0.0.1 - - [06/Jun/2023 08:10:01] "POST / HTTP/1.1" 200 -
2023-06-06 08:10:01,133:INFO:pyemd2:main.py:126:handleKline:2217508: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17468  20230606   072000    072959  1686007799  25745.1  25841.7
17469  20230606   073000    073959  1686008399  25841.8  25795.4
17470  20230606   074000    074959  1686008999  25795.4  25751.5
17471  20230606   075000    075959  1686009599  25751.6  25714.7
17472  20230606   080000    080959  1686010199  25714.6  25708.9
2023-06-06 08:10:01,134:INFO:pyemd2:main.py:127:handleKline:2217508: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=3300 

self.closeSec=1686010799, self.tradeDate='20230606', self.openTime='081000', self.closeTime='081959', self.symbol='BTCUSDT', self.open='25709', self.close='25734.8'
127.0.0.1 - - [06/Jun/2023 08:20:04] "POST / HTTP/1.1" 200 -
2023-06-06 08:20:09,283:INFO:pyemd2:main.py:125:handleKline:2217508: self.closeSec=1686010799, self.tradeDate='20230606', self.openTime='081000', self.closeTime='081959',self.symbol='BTCUSDT',self.open='25709', self.close='25734.8'
2023-06-06 08:20:09,464:INFO:pyemd2:main.py:126:handleKline:2217508: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17469  20230606   073000    073959  1686008399  25841.8  25795.4
17470  20230606   074000    074959  1686008999  25795.4  25751.5
17471  20230606   075000    075959  1686009599  25751.6  25714.7
17472  20230606   080000    080959  1686010199  25714.6  25708.9
17473  20230606   081000    081959  1686010799    25709  25734.8
2023-06-06 08:20:09,465:INFO:pyemd2:main.py:127:handleKline:2217508: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}


## /root/FIL/strategy/similarity/log.txt ----- -----

12143  20230606   075000    075959  1686009599  25751.6  25714.7
2023-06-06 08:00:02,204:INFO:testStrategy:main.py:103:handleKline:2217133: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': True, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=3299 

self.closeSec=1686010199, self.tradeDate='20230606', self.openTime='080000', self.closeTime='080959', self.symbol='BTCUSDT', self.open='25714.6', self.close='25708.9'
2023-06-06 08:10:01,102:INFO:testStrategy:main.py:101:handleKline:2217133: self.closeSec=1686010199, self.tradeDate='20230606', self.openTime='080000', self.closeTime='080959',self.symbol='BTCUSDT',self.open='25714.6', self.close='25708.9'
127.0.0.1 - - [06/Jun/2023 08:10:01] "POST / HTTP/1.1" 200 -
2023-06-06 08:10:01,123:INFO:testStrategy:main.py:102:handleKline:2217133: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12140  20230606   072000    072959  1686007799  25745.1  25841.7
12141  20230606   073000    073959  1686008399  25841.8  25795.4
12142  20230606   074000    074959  1686008999  25795.4  25751.5
12143  20230606   075000    075959  1686009599  25751.6  25714.7
12144  20230606   080000    080959  1686010199  25714.6  25708.9
2023-06-06 08:10:01,123:INFO:testStrategy:main.py:103:handleKline:2217133: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': True, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=3300 

self.closeSec=1686010799, self.tradeDate='20230606', self.openTime='081000', self.closeTime='081959', self.symbol='BTCUSDT', self.open='25709', self.close='25734.8'
127.0.0.1 - - [06/Jun/2023 08:20:04] "POST / HTTP/1.1" 200 -
2023-06-06 08:20:09,001:INFO:testStrategy:main.py:101:handleKline:2217133: self.closeSec=1686010799, self.tradeDate='20230606', self.openTime='081000', self.closeTime='081959',self.symbol='BTCUSDT',self.open='25709', self.close='25734.8'
2023-06-06 08:20:09,261:INFO:testStrategy:main.py:102:handleKline:2217133: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12141  20230606   073000    073959  1686008399  25841.8  25795.4
12142  20230606   074000    074959  1686008999  25795.4  25751.5
12143  20230606   075000    075959  1686009599  25751.6  25714.7
12144  20230606   080000    080959  1686010199  25714.6  25708.9
12145  20230606   081000    081959  1686010799    25709  25734.8
2023-06-06 08:20:09,261:INFO:testStrategy:main.py:103:handleKline:2217133: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': True, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}


## /root/FIL/strategy/sr_min/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=1, self.total=996015.990996, self.flagDict['side']='buy', self.tradeCount=1, self.count=6592
self.closeSec=1686010799, self.tradeDate='20230606', self.openTime='081500', self.closeTime='081959', self.symbol='BTCUSDT', self.open=25715.7, self.close=25734.8, self.high=25740.2, self.low=25715.6, self.vol=1472.723, self.amt=37890661.2181 
127.0.0.1 - - [06/Jun/2023 08:20:01] "POST / HTTP/1.1" 200 -
2023-06-06 08:20:07,398:INFO:sr_min:main.py:172:handleKline:2219263: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5855  20230606   075500    075959  ...         0.0        0.0       0
5856  20230606   080000    080459  ...         0.0        0.0       0
5857  20230606   080500    080959  ...         0.0        0.0       0
5858  20230606   081000    081459  ...         0.0        0.0       0
5859  20230606   081500    081959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-06-06 08:20:07,432:INFO:sr_min:main.py:175:handleKline:2219263: self.closeSec=1686010799, self.tradeDate='20230606', self.openTime='081500', self.closeTime='081959',self.symbol='BTCUSDT',self.open=25715.7, self.close=25734.8, self.high=25740.2, self.low=25715.6, self.vol=1472.723, self.amt=37890661.2181, ukdf['pct'].iloc[-1]=0.000747 , ukdf['amount'].iloc[-1]=37890661.2181, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5859, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '37.141', 'enterprice': '26844', 'countrevence': '0', 'unrealprofit': '-41180.74788604868', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '25735.23211852', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=1
--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=1, self.total=996015.990996, self.flagDict['side']='buy', self.tradeCount=1, self.count=6593
self.closeSec=1686011099, self.tradeDate='20230606', self.openTime='082000', self.closeTime='082459', self.symbol='BTCUSDT', self.open=25734.7, self.close=25735.0, self.high=25741.7, self.low=25730.2, self.vol=514.999, self.amt=13253541.1124 
127.0.0.1 - - [06/Jun/2023 08:25:00] "POST / HTTP/1.1" 200 -
2023-06-06 08:25:00,791:INFO:sr_min:main.py:172:handleKline:2219263: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5856  20230606   080000    080459  ...         0.0        0.0       0
5857  20230606   080500    080959  ...         0.0        0.0       0
5858  20230606   081000    081459  ...         0.0        0.0       0
5859  20230606   081500    081959  ...         0.0        0.0       0
5860  20230606   082000    082459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-06-06 08:25:00,794:INFO:sr_min:main.py:175:handleKline:2219263: self.closeSec=1686011099, self.tradeDate='20230606', self.openTime='082000', self.closeTime='082459',self.symbol='BTCUSDT',self.open=25734.7, self.close=25735.0, self.high=25741.7, self.low=25730.2, self.vol=514.999, self.amt=13253541.1124, ukdf['pct'].iloc[-1]=8e-06 , ukdf['amount'].iloc[-1]=13253541.1124, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5860, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '37.141', 'enterprice': '26844', 'countrevence': '0', 'unrealprofit': '-41170.44153376349', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '25735.50961111', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=1


## /root/FIL/strategy/s_rsrs/log.txt ----- -----

719  20230605   200000    235959  1685980799  ...    719  0.125043 -1.239245    -1.0
720  20230606   000000    035959  1685995199  ...    720  0.293196 -0.757018    -1.0

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '55.166', 'enterprice': '27078.6', 'countrevence': '0', 'unrealprofit': '81204.91612365438', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '25606.58977407', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-1, self.sign=-1
127.0.0.1 - - [06/Jun/2023 08:00:01] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='s_rsrs', self.symbol='BTCUSDT', interval='4h', intervalSec=14400, wid=25, thd=0.6, self.sign=-1, self.total=1492324.2295523998, self.flagDict['side']='sell', self.tradeCount=4, self.count=137
self.closeSec=1686009599, self.tradeDate='20230606', self.openTime='040000', self.closeTime='075959', self.symbol='BTCUSDT', self.open=25618.4, self.close=25714.6, self.high=25850.0, self.low=25496.2, self.vol=60134.637, self.amt=1543268441.78131 
2023-06-06 08:00:01,781:INFO:s_rsrs:main.py:141:handleKline:2218689: self.closeSec=1686009599, self.tradeDate='20230606', self.openTime='040000', self.closeTime='075959',self.symbol='BTCUSDT',self.open=25618.4, self.close=25714.6, self.high=25850.0, self.low=25496.2, self.vol=60134.637, self.amt=1543268441.78131 
2023-06-06 08:00:01,842:INFO:s_rsrs:main.py:142:handleKline:2218689: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime  ...         vol           amt       pct
717  20230605   120000    155959  ...   52410.386  1.404439e+09 -0.000622
718  20230605   160000    195959  ...   48150.374  1.288244e+09 -0.002204
719  20230605   200000    235959  ...  190124.033  5.039569e+09 -0.028677
720  20230606   000000    035959  ...  269202.748  6.913467e+09 -0.014396
721  20230606   040000    075959  ...   60134.637  1.543268e+09  0.003751

[5 rows x 11 columns]
2023-06-06 08:00:03,637:INFO:s_rsrs:main.py:151:handleKline:2218689: df_s.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec  ...  index      beta    zscore  signal
717  20230605   120000    155959  1685951999  ...    717  0.159485 -1.142144    -1.0
718  20230605   160000    195959  1685966399  ...    718  0.179079 -1.084978    -1.0
719  20230605   200000    235959  1685980799  ...    719  0.125043 -1.239245    -1.0
720  20230606   000000    035959  1685995199  ...    720  0.293196 -0.757018    -1.0
721  20230606   040000    075959  1686009599  ...    721  0.439634 -0.336106     NaN

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '55.166', 'enterprice': '27078.6', 'countrevence': '0', 'unrealprofit': '75102.14610556558', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '25717.21534087', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-9223372036854775808, self.sign=-1


