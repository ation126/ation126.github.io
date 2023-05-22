# 20230522 08:26:01

## /root/FIL/strategy/amihud/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=373746.4768026, self.flagDict['side']='sell', self.tradeCount=2, self.count=2272
self.closeSec=1684714799, self.tradeDate='20230522', self.openTime='081500', self.closeTime='081959', self.symbol='BTCUSDT', self.open=26771.2, self.close=26755.4, self.high=26771.3, self.low=26750.7, self.vol=437.34, self.amt=11703819.7318 
127.0.0.1 - - [22/May/2023 08:20:01] "POST / HTTP/1.1" 200 -
2023-05-22 08:20:04,846:INFO:amihud:main.py:172:handleKline:2219019: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5855  20230522   075500    075959  ...    0.243464   0.319934       0
5856  20230522   080000    080459  ...    0.243268   0.319867       0
5857  20230522   080500    080959  ...    0.243072   0.319800       0
5858  20230522   081000    081459  ...    0.242879   0.319737       0
5859  20230522   081500    081959  ...    0.242697   0.319687       0

[5 rows x 18 columns]
2023-05-22 08:20:04,876:INFO:amihud:main.py:175:handleKline:2219019: self.closeSec=1684714799, self.tradeDate='20230522', self.openTime='081500', self.closeTime='081959',self.symbol='BTCUSDT',self.open=26771.2, self.close=26755.4, self.high=26771.3, self.low=26750.7, self.vol=437.34, self.amt=11703819.7318, ukdf['pct'].iloc[-1]=-0.000594 , ukdf['amount'].iloc[-1]=11703819.7318, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5859, value=0.0, value_mean=0.24269656883058316, signal=0, value_std=0.3196874932788437 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '13.926', 'enterprice': '26864.9', 'countrevence': '0', 'unrealprofit': '1524.897', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '26755.4', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1
--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=373746.4768026, self.flagDict['side']='sell', self.tradeCount=2, self.count=2273
self.closeSec=1684715099, self.tradeDate='20230522', self.openTime='082000', self.closeTime='082459', self.symbol='BTCUSDT', self.open=26755.4, self.close=26729.3, self.high=26755.5, self.low=26728.0, self.vol=771.651, self.amt=20634396.8766 
127.0.0.1 - - [22/May/2023 08:25:00] "POST / HTTP/1.1" 200 -
2023-05-22 08:25:00,380:INFO:amihud:main.py:172:handleKline:2219019: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5856  20230522   080000    080459  ...    0.243268   0.319867       0
5857  20230522   080500    080959  ...    0.243072   0.319800       0
5858  20230522   081000    081459  ...    0.242879   0.319737       0
5859  20230522   081500    081959  ...    0.242697   0.319687       0
5860  20230522   082000    082459  ...    0.242516   0.319641       0

[5 rows x 18 columns]
2023-05-22 08:25:00,380:INFO:amihud:main.py:175:handleKline:2219019: self.closeSec=1684715099, self.tradeDate='20230522', self.openTime='082000', self.closeTime='082459',self.symbol='BTCUSDT',self.open=26755.4, self.close=26729.3, self.high=26755.5, self.low=26728.0, self.vol=771.651, self.amt=20634396.8766, ukdf['pct'].iloc[-1]=-0.000976 , ukdf['amount'].iloc[-1]=20634396.8766, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5860, value=0.0, value_mean=0.24251604281823713, signal=0, value_std=0.319640992597556 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '13.926', 'enterprice': '26864.9', 'countrevence': '0', 'unrealprofit': '1886.11511425458', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '26729.46160317', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1


## /root/FIL/strategy/factorcheck/log.txt ----- -----


self.closeSec=1684714799, self.tradeDate='20230522', self.openTime='081500', self.closeTime='081959', self.symbol='BTCUSDT', self.open=26771.2, self.close=26755.4, self.high=26771.3, self.low=26750.7 
127.0.0.1 - - [22/May/2023 08:20:01] "POST / HTTP/1.1" 200 -
2023-05-22 08:20:03,265:INFO:factorcheck2:main.py:126:handleKline:2218005: self.closeSec=1684714799, self.tradeDate='20230522', self.openTime='081500', self.closeTime='081959',self.symbol='BTCUSDT',self.open=26771.2, self.close=26755.4, self.high=26771.3, self.low=26750.7   
2023-05-22 08:20:04,067:INFO:factorcheck2:main.py:127:handleKline:2218005: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1535  20230522   075500    075959  1684713599  ...  26707.0 -0.000273   1535    5
1536  20230522   080000    080459  1684713899  ...  26720.4  0.000640   1536    0
1537  20230522   080500    080959  1684714199  ...  26749.9  0.000751   1537    1
1538  20230522   081000    081459  1684714499  ...  26767.5  0.000049   1538    2
1539  20230522   081500    081959  1684714799  ...  26750.7 -0.000594   1539    3

[5 rows x 11 columns]
2023-05-22 08:20:04,075:INFO:factorcheck2:main.py:128:handleKline:2218005: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': False, 'isOpen': True, 'isClose': False, 'isTrig': True}

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.6318504218449407, self.count=2275 

self.closeSec=1684715099, self.tradeDate='20230522', self.openTime='082000', self.closeTime='082459', self.symbol='BTCUSDT', self.open=26755.4, self.close=26729.3, self.high=26755.5, self.low=26728.0 
127.0.0.1 - - [22/May/2023 08:25:00] "POST / HTTP/1.1" 200 -
2023-05-22 08:25:00,349:INFO:factorcheck2:main.py:126:handleKline:2218005: self.closeSec=1684715099, self.tradeDate='20230522', self.openTime='082000', self.closeTime='082459',self.symbol='BTCUSDT',self.open=26755.4, self.close=26729.3, self.high=26755.5, self.low=26728.0   
2023-05-22 08:25:00,423:INFO:factorcheck2:main.py:127:handleKline:2218005: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1536  20230522   080000    080459  1684713899  ...  26720.4  0.000640   1536    0
1537  20230522   080500    080959  1684714199  ...  26749.9  0.000751   1537    1
1538  20230522   081000    081459  1684714499  ...  26767.5  0.000049   1538    2
1539  20230522   081500    081959  1684714799  ...  26750.7 -0.000594   1539    3
1540  20230522   082000    082459  1684715099  ...  26728.0 -0.000976   1540    4

[5 rows x 11 columns]
2023-05-22 08:25:00,423:INFO:factorcheck2:main.py:128:handleKline:2218005: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': False, 'isOpen': True, 'isClose': False, 'isTrig': True}


## /root/FIL/strategy/logic/log.txt ----- -----

     pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
536     1  0.461899  0.538101       1  ...  0.937852  -1.0    0.0  0.985448
537     1  0.497149  0.502851       1  ...  0.937666  -1.0    0.0  0.985643
538     1  0.488185  0.511815       0  ...  0.937687  -1.0    0.0  0.985621
539     1  0.488030  0.511970       1  ...  0.936645  -1.0    0.0  0.986716
540     0  0.500465  0.499535       0  ...  0.937936  -1.0    0.0  0.985356

[5 rows x 10 columns]
2023-05-22 08:00:33,314:INFO:logic:main.py:478:getModel:2218526: df_panel.iloc[-5:,:] :
    pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
45     1  0.461785  0.538215       1  ...  0.937852  -1.0    0.0  0.950041
46     1  0.497223  0.502777       1  ...  0.937666  -1.0    0.0  0.945626
47     1  0.488378  0.511622       0  ...  0.909596   1.0    0.0  0.949351
48     1  0.488280  0.511720       1  ...  0.910607   1.0    0.0  0.986716
49     0  0.500465  0.499535       0  ...  0.937936  -1.0    0.0  0.985356

[5 rows x 10 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '27.414', 'enterprice': '26741.6', 'countrevence': '0', 'unrealprofit': '-310.32985247028', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '26730.27987698', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
handlebackTrade > queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '27.414', 'enterprice': '26741.6', 'countrevence': '0', 'unrealprofit': '-310.32985247028', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '26730.27987698', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
2023-05-22 08:00:40,311:INFO:logic:main.py:500:queryContractAssets:2218526: queryContractAssets: assets=ContractAssetReturn{'result': [ContractAsset{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'asset': 'USDT', 'free': '734172.8990251', 'total': '734172.8990251', 'margin': '0', 'unreal': '0', 'type': 'AssetType_ucontract'}]}
2023-05-22 08:00:40,854:INFO:logic:main.py:587:openSell:2218526: ret = self.client.insertMarketUOrder("simulator", "BTCUSDT", 27.380, "sell"), ret=InsertOrderReturn{'result': 'success', 'clientorderid': '42215F1684713640853I0L64'}
2023-05-22 08:00:40,871:INFO:logic:main.py:494:insertFactor:2218526: curDateTime:5220800, name:logic, symbol:BTCUSDT, tradeDate:20230522, closeTime:075959, close:26732.8, sign:-1, total:734172.8990251, side:sell  
127.0.0.1 - - [22/May/2023 08:00:40] "POST / HTTP/1.1" 200 -
2023-05-22 08:00:40,872:INFO:logic:main.py:661:handleOrderNew:2218526: handleOrderNew: data=OrderType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'clientorderid': '42214F1684713635222I0L64', 'symbol': 'BTCUSDT', 'gatewayorderid': 1684713635631892, 'quantity': '27.414', 'price': '26728.8', 'stopprice': '0', 'ordertype': '', 'side': 'SELL', 'status': 'FILLED', 'positionside': 'SHORT', 'createtime': 1684713634230, 'updatetime': 1684713635631, 'tradetype': 'usdt', 'selfid': 42214, 'filltrades': [TradeType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'tradeid': 1684713635631, 'clientorderid': '42214F1684713635222I0L64', 'price': '26728.8', 'quantity': '27.414', 'commission': '732.7433232', 'commissionasset': 'USDT', 'tradetime': 1684713635631, 'tradetype': 'usdt', 'gatetype': 'simulator', 'handletime': 1684713635631}], 'gatetype': 'simulator', 'handletime': 0}
127.0.0.1 - - [22/May/2023 08:00:40] "POST / HTTP/1.1" 200 -
2023-05-22 08:00:40,872:INFO:logic:main.py:664:handleOrderFilled:2218526: handleOrderFilled: data=OrderType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'clientorderid': '42214F1684713635222I0L64', 'symbol': 'BTCUSDT', 'gatewayorderid': 1684713635631892, 'quantity': '27.414', 'price': '26728.8', 'stopprice': '0', 'ordertype': '', 'side': 'SELL', 'status': 'FILLED', 'positionside': 'SHORT', 'createtime': 1684713634230, 'updatetime': 1684713635631, 'tradetype': 'usdt', 'selfid': 42214, 'filltrades': [TradeType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'tradeid': 1684713635631, 'clientorderid': '42214F1684713635222I0L64', 'price': '26728.8', 'quantity': '27.414', 'commission': '732.7433232', 'commissionasset': 'USDT', 'tradetime': 1684713635631, 'tradetype': 'usdt', 'gatetype': 'simulator', 'handletime': 1684713635631}], 'gatetype': 'simulator', 'handletime': 0}
2023-05-22 08:00:41,299:INFO:logic:main.py:661:handleOrderNew:2218526: handleOrderNew: data=OrderType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'clientorderid': '42215F1684713640853I0L64', 'symbol': 'BTCUSDT', 'gatewayorderid': 1684713641268158, 'quantity': '27.38', 'price': '26729', 'stopprice': '0', 'ordertype': '', 'side': 'SELL', 'status': 'FILLED', 'positionside': 'SHORT', 'createtime': 1684713640322, 'updatetime': 1684713641268, 'tradetype': 'usdt', 'selfid': 42215, 'filltrades': [TradeType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'tradeid': 1684713641268, 'clientorderid': '42215F1684713640853I0L64', 'price': '26729', 'quantity': '27.38', 'commission': '731.84002', 'commissionasset': 'USDT', 'tradetime': 1684713641268, 'tradetype': 'usdt', 'gatetype': 'simulator', 'handletime': 1684713641268}], 'gatetype': 'simulator', 'handletime': 0}
127.0.0.1 - - [22/May/2023 08:00:41] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [22/May/2023 08:00:41] "POST / HTTP/1.1" 200 -
2023-05-22 08:00:41,511:INFO:logic:main.py:664:handleOrderFilled:2218526: handleOrderFilled: data=OrderType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'clientorderid': '42215F1684713640853I0L64', 'symbol': 'BTCUSDT', 'gatewayorderid': 1684713641268158, 'quantity': '27.38', 'price': '26729', 'stopprice': '0', 'ordertype': '', 'side': 'SELL', 'status': 'FILLED', 'positionside': 'SHORT', 'createtime': 1684713640322, 'updatetime': 1684713641268, 'tradetype': 'usdt', 'selfid': 42215, 'filltrades': [TradeType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'tradeid': 1684713641268, 'clientorderid': '42215F1684713640853I0L64', 'price': '26729', 'quantity': '27.38', 'commission': '731.84002', 'commissionasset': 'USDT', 'tradetime': 1684713641268, 'tradetype': 'usdt', 'gatetype': 'simulator', 'handletime': 1684713641268}], 'gatetype': 'simulator', 'handletime': 0}


## /root/FIL/strategy/modifiedmom/log.txt ----- -----

623  20230522   075000    075959  1684713599  26762.5  26732.8 -0.001110
2023-05-22 08:00:00,490:INFO:modifiedmom:main.py:146:handleKline:2218259: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=1136 

self.closeSec=1684714199, self.tradeDate='20230522', self.openTime='080000', self.closeTime='080959', self.symbol='BTCUSDT', self.open='26732.8', self.close='26770'
2023-05-22 08:10:00,386:INFO:modifiedmom:main.py:144:handleKline:2218259: self.closeSec=1684714199, self.tradeDate='20230522', self.openTime='080000', self.closeTime='080959',self.symbol='BTCUSDT',self.open='26732.8', self.close='26770'
127.0.0.1 - - [22/May/2023 08:10:00] "POST / HTTP/1.1" 200 -
2023-05-22 08:10:00,436:INFO:modifiedmom:main.py:145:handleKline:2218259: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
620  20230522   072000    072959  1684711799  26762.1  26769.7  0.000284
621  20230522   073000    073959  1684712399  26769.8    26770  0.000011
622  20230522   074000    074959  1684712999    26770  26762.5 -0.000280
623  20230522   075000    075959  1684713599  26762.5  26732.8 -0.001110
624  20230522   080000    080959  1684714199  26732.8    26770  0.001392
2023-05-22 08:10:00,438:INFO:modifiedmom:main.py:146:handleKline:2218259: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=1137 

self.closeSec=1684714799, self.tradeDate='20230522', self.openTime='081000', self.closeTime='081959', self.symbol='BTCUSDT', self.open='26770', self.close='26755.4'
127.0.0.1 - - [22/May/2023 08:20:01] "POST / HTTP/1.1" 200 -
2023-05-22 08:20:03,246:INFO:modifiedmom:main.py:144:handleKline:2218259: self.closeSec=1684714799, self.tradeDate='20230522', self.openTime='081000', self.closeTime='081959',self.symbol='BTCUSDT',self.open='26770', self.close='26755.4'
2023-05-22 08:20:03,795:INFO:modifiedmom:main.py:145:handleKline:2218259: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
621  20230522   073000    073959  1684712399  26769.8    26770  0.000011
622  20230522   074000    074959  1684712999    26770  26762.5 -0.000280
623  20230522   075000    075959  1684713599  26762.5  26732.8 -0.001110
624  20230522   080000    080959  1684714199  26732.8    26770  0.001392
625  20230522   081000    081959  1684714799    26770  26755.4 -0.000545
2023-05-22 08:20:03,796:INFO:modifiedmom:main.py:146:handleKline:2218259: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False}


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

17471  20230522   075000    075959  1684713599  26762.5  26732.8
2023-05-22 08:00:00,506:INFO:pyemd2:main.py:127:handleKline:2217508: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}
127.0.0.1 - - [22/May/2023 08:10:00] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=1139 

self.closeSec=1684714199, self.tradeDate='20230522', self.openTime='080000', self.closeTime='080959', self.symbol='BTCUSDT', self.open='26732.8', self.close='26770'
2023-05-22 08:10:00,360:INFO:pyemd2:main.py:125:handleKline:2217508: self.closeSec=1684714199, self.tradeDate='20230522', self.openTime='080000', self.closeTime='080959',self.symbol='BTCUSDT',self.open='26732.8', self.close='26770'
2023-05-22 08:10:00,447:INFO:pyemd2:main.py:126:handleKline:2217508: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17468  20230522   072000    072959  1684711799  26762.1  26769.7
17469  20230522   073000    073959  1684712399  26769.8    26770
17470  20230522   074000    074959  1684712999    26770  26762.5
17471  20230522   075000    075959  1684713599  26762.5  26732.8
17472  20230522   080000    080959  1684714199  26732.8    26770
2023-05-22 08:10:00,447:INFO:pyemd2:main.py:127:handleKline:2217508: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=1140 

self.closeSec=1684714799, self.tradeDate='20230522', self.openTime='081000', self.closeTime='081959', self.symbol='BTCUSDT', self.open='26770', self.close='26755.4'
127.0.0.1 - - [22/May/2023 08:20:01] "POST / HTTP/1.1" 200 -
2023-05-22 08:20:05,399:INFO:pyemd2:main.py:125:handleKline:2217508: self.closeSec=1684714799, self.tradeDate='20230522', self.openTime='081000', self.closeTime='081959',self.symbol='BTCUSDT',self.open='26770', self.close='26755.4'
2023-05-22 08:20:05,577:INFO:pyemd2:main.py:126:handleKline:2217508: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17469  20230522   073000    073959  1684712399  26769.8    26770
17470  20230522   074000    074959  1684712999    26770  26762.5
17471  20230522   075000    075959  1684713599  26762.5  26732.8
17472  20230522   080000    080959  1684714199  26732.8    26770
17473  20230522   081000    081959  1684714799    26770  26755.4
2023-05-22 08:20:05,577:INFO:pyemd2:main.py:127:handleKline:2217508: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}


## /root/FIL/strategy/similarity/log.txt ----- -----

12143  20230522   075000    075959  1684713599  26762.5  26732.8
2023-05-22 08:00:00,510:INFO:testStrategy:main.py:103:handleKline:2217133: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=1139 

self.closeSec=1684714199, self.tradeDate='20230522', self.openTime='080000', self.closeTime='080959', self.symbol='BTCUSDT', self.open='26732.8', self.close='26770'
2023-05-22 08:10:00,342:INFO:testStrategy:main.py:101:handleKline:2217133: self.closeSec=1684714199, self.tradeDate='20230522', self.openTime='080000', self.closeTime='080959',self.symbol='BTCUSDT',self.open='26732.8', self.close='26770'
127.0.0.1 - - [22/May/2023 08:10:00] "POST / HTTP/1.1" 200 -
2023-05-22 08:10:00,433:INFO:testStrategy:main.py:102:handleKline:2217133: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12140  20230522   072000    072959  1684711799  26762.1  26769.7
12141  20230522   073000    073959  1684712399  26769.8    26770
12142  20230522   074000    074959  1684712999    26770  26762.5
12143  20230522   075000    075959  1684713599  26762.5  26732.8
12144  20230522   080000    080959  1684714199  26732.8    26770
2023-05-22 08:10:00,433:INFO:testStrategy:main.py:103:handleKline:2217133: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=1140 

self.closeSec=1684714799, self.tradeDate='20230522', self.openTime='081000', self.closeTime='081959', self.symbol='BTCUSDT', self.open='26770', self.close='26755.4'
127.0.0.1 - - [22/May/2023 08:20:01] "POST / HTTP/1.1" 200 -
2023-05-22 08:20:04,997:INFO:testStrategy:main.py:101:handleKline:2217133: self.closeSec=1684714799, self.tradeDate='20230522', self.openTime='081000', self.closeTime='081959',self.symbol='BTCUSDT',self.open='26770', self.close='26755.4'
2023-05-22 08:20:05,345:INFO:testStrategy:main.py:102:handleKline:2217133: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12141  20230522   073000    073959  1684712399  26769.8    26770
12142  20230522   074000    074959  1684712999    26770  26762.5
12143  20230522   075000    075959  1684713599  26762.5  26732.8
12144  20230522   080000    080959  1684714199  26732.8    26770
12145  20230522   081000    081959  1684714799    26770  26755.4
2023-05-22 08:20:05,346:INFO:testStrategy:main.py:103:handleKline:2217133: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}


## /root/FIL/strategy/sr_min/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=1, self.total=996015.990996, self.flagDict['side']='buy', self.tradeCount=1, self.count=2272
self.closeSec=1684714799, self.tradeDate='20230522', self.openTime='081500', self.closeTime='081959', self.symbol='BTCUSDT', self.open=26771.2, self.close=26755.4, self.high=26771.3, self.low=26750.7, self.vol=437.34, self.amt=11703819.7318 
127.0.0.1 - - [22/May/2023 08:20:01] "POST / HTTP/1.1" 200 -
2023-05-22 08:20:04,646:INFO:sr_min:main.py:172:handleKline:2219263: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5855  20230522   075500    075959  ...         0.0        0.0       0
5856  20230522   080000    080459  ...         0.0        0.0       0
5857  20230522   080500    080959  ...         0.0        0.0       0
5858  20230522   081000    081459  ...         0.0        0.0       0
5859  20230522   081500    081959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-05-22 08:20:04,675:INFO:sr_min:main.py:175:handleKline:2219263: self.closeSec=1684714799, self.tradeDate='20230522', self.openTime='081500', self.closeTime='081959',self.symbol='BTCUSDT',self.open=26771.2, self.close=26755.4, self.high=26771.3, self.low=26750.7, self.vol=437.34, self.amt=11703819.7318, ukdf['pct'].iloc[-1]=-0.000594 , ukdf['amount'].iloc[-1]=11703819.7318, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5859, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '37.141', 'enterprice': '26844', 'countrevence': '0', 'unrealprofit': '-3290.6926', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '26755.4', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=1
127.0.0.1 - - [22/May/2023 08:25:00] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=1, self.total=996015.990996, self.flagDict['side']='buy', self.tradeCount=1, self.count=2273
self.closeSec=1684715099, self.tradeDate='20230522', self.openTime='082000', self.closeTime='082459', self.symbol='BTCUSDT', self.open=26755.4, self.close=26729.3, self.high=26755.5, self.low=26728.0, self.vol=771.651, self.amt=20634396.8766 
2023-05-22 08:25:00,469:INFO:sr_min:main.py:172:handleKline:2219263: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5856  20230522   080000    080459  ...         0.0        0.0       0
5857  20230522   080500    080959  ...         0.0        0.0       0
5858  20230522   081000    081459  ...         0.0        0.0       0
5859  20230522   081500    081959  ...         0.0        0.0       0
5860  20230522   082000    082459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-05-22 08:25:00,470:INFO:sr_min:main.py:175:handleKline:2219263: self.closeSec=1684715099, self.tradeDate='20230522', self.openTime='082000', self.closeTime='082459',self.symbol='BTCUSDT',self.open=26755.4, self.close=26729.3, self.high=26755.5, self.low=26728.0, self.vol=771.651, self.amt=20634396.8766, ukdf['pct'].iloc[-1]=-0.000976 , ukdf['amount'].iloc[-1]=20634396.8766, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5860, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '37.141', 'enterprice': '26844', 'countrevence': '0', 'unrealprofit': '-4254.07059666303', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '26729.46160317', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=1


## /root/FIL/strategy/s_rsrs/log.txt ----- -----

719  20230521   200000    235959  1684684799  ...    719  0.170303 -1.343700    -1.0
720  20230522   000000    035959  1684699199  ...    720  0.146344 -1.440392    -1.0

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '51.549', 'enterprice': '27070.5', 'countrevence': '0', 'unrealprofit': '9309.7494', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '26889.9', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-1, self.sign=-1
--handleKline--:  version='2.0.0', self.name='s_rsrs', self.symbol='BTCUSDT', interval='4h', intervalSec=14400, wid=25, thd=0.6, self.sign=-1, self.total=1394061.7472955, self.flagDict['side']='sell', self.tradeCount=2, self.count=47
self.closeSec=1684713599, self.tradeDate='20230522', self.openTime='040000', self.closeTime='075959', self.symbol='BTCUSDT', self.open=26889.1, self.close=26732.8, self.high=26915.0, self.low=26642.0, self.vol=41970.275, self.amt=1122796583.96974 
2023-05-22 08:00:00,452:INFO:s_rsrs:main.py:141:handleKline:2218689: self.closeSec=1684713599, self.tradeDate='20230522', self.openTime='040000', self.closeTime='075959',self.symbol='BTCUSDT',self.open=26889.1, self.close=26732.8, self.high=26915.0, self.low=26642.0, self.vol=41970.275, self.amt=1122796583.96974 
127.0.0.1 - - [22/May/2023 08:00:00] "POST / HTTP/1.1" 200 -
2023-05-22 08:00:00,532:INFO:s_rsrs:main.py:142:handleKline:2218689: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime  ...        vol           amt       pct
717  20230521   120000    155959  ...  23955.740  6.490055e+08 -0.004491
718  20230521   160000    195959  ...  59909.536  1.612987e+09 -0.008371
719  20230521   200000    235959  ...  50401.693  1.354903e+09  0.002495
720  20230522   000000    035959  ...  24421.545  6.562348e+08  0.000156
721  20230522   040000    075959  ...  41970.275  1.122797e+09 -0.005816

[5 rows x 11 columns]
2023-05-22 08:00:02,717:INFO:s_rsrs:main.py:151:handleKline:2218689: df_s.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec  ...  index      beta    zscore  signal
717  20230521   120000    155959  1684655999  ...    717  0.173010 -1.372253    -1.0
718  20230521   160000    195959  1684670399  ...    718  0.177847 -1.320215    -1.0
719  20230521   200000    235959  1684684799  ...    719  0.170303 -1.343700    -1.0
720  20230522   000000    035959  1684699199  ...    720  0.146344 -1.440392    -1.0
721  20230522   040000    075959  1684713599  ...    721  0.231294 -1.012186    -1.0

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '51.549', 'enterprice': '27070.5', 'countrevence': '0', 'unrealprofit': '17327.69886142629', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '26734.35965079', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-1, self.sign=-1


