# 20230629 16:26:02

## /root/FIL/strategy/amihud/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=373746.4768026, self.flagDict['side']='sell', self.tradeCount=2, self.count=13312
self.closeSec=1688026799, self.tradeDate='20230629', self.openTime='161500', self.closeTime='161959', self.symbol='BTCUSDT', self.open=30365.6, self.close=30385.4, self.high=30389.5, self.low=30347.8, self.vol=674.155, self.amt=20473423.919 
127.0.0.1 - - [29/Jun/2023 16:20:02] "POST / HTTP/1.1" 200 -
2023-06-29 16:20:07,874:INFO:amihud:main.py:172:handleKline:2219019: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5951  20230629   155500    155959  ...         0.0        0.0       0
5952  20230629   160000    160459  ...         0.0        0.0       0
5953  20230629   160500    160959  ...         0.0        0.0       0
5954  20230629   161000    161459  ...         0.0        0.0       0
5955  20230629   161500    161959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-06-29 16:20:07,905:INFO:amihud:main.py:175:handleKline:2219019: self.closeSec=1688026799, self.tradeDate='20230629', self.openTime='161500', self.closeTime='161959',self.symbol='BTCUSDT',self.open=30365.6, self.close=30385.4, self.high=30389.5, self.low=30347.8, self.vol=674.155, self.amt=20473423.919, ukdf['pct'].iloc[-1]=0.000652 , ukdf['amount'].iloc[-1]=20473423.919, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5955, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '13.926', 'enterprice': '26864.9', 'countrevence': '0', 'unrealprofit': '-49058.5128', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '30387.7', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1
--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=373746.4768026, self.flagDict['side']='sell', self.tradeCount=2, self.count=13313
self.closeSec=1688027099, self.tradeDate='20230629', self.openTime='162000', self.closeTime='162459', self.symbol='BTCUSDT', self.open=30385.4, self.close=30390.3, self.high=30397.0, self.low=30364.8, self.vol=1156.24, self.amt=35131194.5139 
127.0.0.1 - - [29/Jun/2023 16:25:00] "POST / HTTP/1.1" 200 -
2023-06-29 16:25:00,827:INFO:amihud:main.py:172:handleKline:2219019: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5952  20230629   160000    160459  ...         0.0        0.0       0
5953  20230629   160500    160959  ...         0.0        0.0       0
5954  20230629   161000    161459  ...         0.0        0.0       0
5955  20230629   161500    161959  ...         0.0        0.0       0
5956  20230629   162000    162459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-06-29 16:25:00,828:INFO:amihud:main.py:175:handleKline:2219019: self.closeSec=1688027099, self.tradeDate='20230629', self.openTime='162000', self.closeTime='162459',self.symbol='BTCUSDT',self.open=30385.4, self.close=30390.3, self.high=30397.0, self.low=30364.8, self.vol=1156.24, self.amt=35131194.5139, ukdf['pct'].iloc[-1]=0.000161 , ukdf['amount'].iloc[-1]=35131194.5139, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5956, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '13.926', 'enterprice': '26864.9', 'countrevence': '0', 'unrealprofit': '-49094.7204', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '30390.3', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1


## /root/FIL/strategy/factorcheck/log.txt ----- -----


self.closeSec=1688026799, self.tradeDate='20230629', self.openTime='161500', self.closeTime='161959', self.symbol='BTCUSDT', self.open=30365.6, self.close=30385.4, self.high=30389.5, self.low=30347.8 
127.0.0.1 - - [29/Jun/2023 16:20:01] "POST / HTTP/1.1" 200 -
2023-06-29 16:20:05,219:INFO:factorcheck2:main.py:126:handleKline:2218005: self.closeSec=1688026799, self.tradeDate='20230629', self.openTime='161500', self.closeTime='161959',self.symbol='BTCUSDT',self.open=30365.6, self.close=30385.4, self.high=30389.5, self.low=30347.8   
2023-06-29 16:20:06,860:INFO:factorcheck2:main.py:127:handleKline:2218005: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1631  20230629   155500    155959  1688025599  ...  30323.2  0.000178   1631    5
1632  20230629   160000    160459  1688025899  ...  30320.3  0.000679   1632    0
1633  20230629   160500    160959  1688026199  ...  30342.0  0.000329   1633    1
1634  20230629   161000    161459  1688026499  ...  30361.3  0.000033   1634    2
1635  20230629   161500    161959  1688026799  ...  30347.8  0.000652   1635    3

[5 rows x 11 columns]
2023-06-29 16:20:06,871:INFO:factorcheck2:main.py:128:handleKline:2218005: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': False, 'isOpen': True, 'isClose': False, 'isTrig': True}
127.0.0.1 - - [29/Jun/2023 16:25:00] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.622615612281497, self.count=13315 

self.closeSec=1688027099, self.tradeDate='20230629', self.openTime='162000', self.closeTime='162459', self.symbol='BTCUSDT', self.open=30385.4, self.close=30390.3, self.high=30397.0, self.low=30364.8 
2023-06-29 16:25:00,749:INFO:factorcheck2:main.py:126:handleKline:2218005: self.closeSec=1688027099, self.tradeDate='20230629', self.openTime='162000', self.closeTime='162459',self.symbol='BTCUSDT',self.open=30385.4, self.close=30390.3, self.high=30397.0, self.low=30364.8   
2023-06-29 16:25:00,804:INFO:factorcheck2:main.py:127:handleKline:2218005: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1632  20230629   160000    160459  1688025899  ...  30320.3  0.000679   1632    0
1633  20230629   160500    160959  1688026199  ...  30342.0  0.000329   1633    1
1634  20230629   161000    161459  1688026499  ...  30361.3  0.000033   1634    2
1635  20230629   161500    161959  1688026799  ...  30347.8  0.000652   1635    3
1636  20230629   162000    162459  1688027099  ...  30364.8  0.000161   1636    4

[5 rows x 11 columns]
2023-06-29 16:25:00,804:INFO:factorcheck2:main.py:128:handleKline:2218005: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': False, 'isOpen': True, 'isClose': False, 'isTrig': True}


## /root/FIL/strategy/logic/log.txt ----- -----

     pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
537     0  0.509075  0.490925       0  ...  1.060727  -1.0    0.0  1.140933
538     1  0.497159  0.502841       1  ...  1.059999  -1.0    0.0  1.141716
539     0  0.509285  0.490715       1  ...  1.058963  -1.0    0.0  1.142831
540     0  0.513259  0.486741       1  ...  1.053742  -1.0    0.0  1.148466
541     0  0.536466  0.463534       0  ...  1.055016  -1.0    0.0  1.147078

[5 rows x 10 columns]
2023-06-29 16:00:18,852:INFO:logic:main.py:478:getModel:2218526: df_panel.iloc[-5:,:] :
    pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
45     0  0.509097  0.490903       0  ...  1.060727  -1.0    0.0  1.136164
46     1  0.497938  0.502062       1  ...  1.059999  -1.0    0.0  1.139208
47     0  0.509262  0.490738       1  ...  1.058963  -1.0    0.0  1.140059
48     0  0.514053  0.485947       1  ...  1.028821   1.0    0.0  1.147117
49     0  0.536466  0.463534       0  ...  1.055016  -1.0    0.0  1.147078

[5 rows x 10 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '26.884', 'enterprice': '30370.7', 'countrevence': '0', 'unrealprofit': '-720.4912', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '30343.9', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
handlebackTrade > queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '26.884', 'enterprice': '30370.7', 'countrevence': '0', 'unrealprofit': '-720.4912', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '30343.9', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
2023-06-29 16:00:25,674:INFO:logic:main.py:500:queryContractAssets:2218526: queryContractAssets: assets=ContractAssetReturn{'result': [ContractAsset{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'asset': 'USDT', 'free': '817492.4123972', 'total': '817492.4123972', 'margin': '0', 'unreal': '0', 'type': 'AssetType_ucontract'}]}
2023-06-29 16:00:26,148:INFO:logic:main.py:587:openSell:2218526: ret = self.client.insertMarketUOrder("simulator", "BTCUSDT", 26.868, "sell"), ret=InsertOrderReturn{'result': 'success', 'clientorderid': '42490F1688025626147I0L64'}
2023-06-29 16:00:26,163:INFO:logic:main.py:494:insertFactor:2218526: curDateTime:6291600, name:logic, symbol:BTCUSDT, tradeDate:20230629, closeTime:155959, close:30333.9, sign:-1, total:817492.4123972, side:sell  
127.0.0.1 - - [29/Jun/2023 16:00:26] "POST / HTTP/1.1" 200 -
2023-06-29 16:00:26,164:INFO:logic:main.py:661:handleOrderNew:2218526: handleOrderNew: data=OrderType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'clientorderid': '42489F1688025620603I0L64', 'symbol': 'BTCUSDT', 'gatewayorderid': 1688025620974182, 'quantity': '26.884', 'price': '30346.9', 'stopprice': '0', 'ordertype': '', 'side': 'SELL', 'status': 'FILLED', 'positionside': 'SHORT', 'createtime': 1688025619731, 'updatetime': 1688025620974, 'tradetype': 'usdt', 'selfid': 42489, 'filltrades': [TradeType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'tradeid': 1688025620974, 'clientorderid': '42489F1688025620603I0L64', 'price': '30346.9', 'quantity': '26.884', 'commission': '815.8460596', 'commissionasset': 'USDT', 'tradetime': 1688025620974, 'tradetype': 'usdt', 'gatetype': 'simulator', 'handletime': 1688025620974}], 'gatetype': 'simulator', 'handletime': 0}
127.0.0.1 - - [29/Jun/2023 16:00:26] "POST / HTTP/1.1" 200 -
2023-06-29 16:00:26,164:INFO:logic:main.py:664:handleOrderFilled:2218526: handleOrderFilled: data=OrderType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'clientorderid': '42489F1688025620603I0L64', 'symbol': 'BTCUSDT', 'gatewayorderid': 1688025620974182, 'quantity': '26.884', 'price': '30346.9', 'stopprice': '0', 'ordertype': '', 'side': 'SELL', 'status': 'FILLED', 'positionside': 'SHORT', 'createtime': 1688025619731, 'updatetime': 1688025620974, 'tradetype': 'usdt', 'selfid': 42489, 'filltrades': [TradeType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'tradeid': 1688025620974, 'clientorderid': '42489F1688025620603I0L64', 'price': '30346.9', 'quantity': '26.884', 'commission': '815.8460596', 'commissionasset': 'USDT', 'tradetime': 1688025620974, 'tradetype': 'usdt', 'gatetype': 'simulator', 'handletime': 1688025620974}], 'gatetype': 'simulator', 'handletime': 0}
2023-06-29 16:00:26,557:INFO:logic:main.py:661:handleOrderNew:2218526: handleOrderNew: data=OrderType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'clientorderid': '42490F1688025626147I0L64', 'symbol': 'BTCUSDT', 'gatewayorderid': 1688025626541159, 'quantity': '26.868', 'price': '30338.2', 'stopprice': '0', 'ordertype': '', 'side': 'SELL', 'status': 'FILLED', 'positionside': 'SHORT', 'createtime': 1688025625686, 'updatetime': 1688025626541, 'tradetype': 'usdt', 'selfid': 42490, 'filltrades': [TradeType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'tradeid': 1688025626541, 'clientorderid': '42490F1688025626147I0L64', 'price': '30338.2', 'quantity': '26.868', 'commission': '815.1267576', 'commissionasset': 'USDT', 'tradetime': 1688025626541, 'tradetype': 'usdt', 'gatetype': 'simulator', 'handletime': 1688025626541}], 'gatetype': 'simulator', 'handletime': 0}
127.0.0.1 - - [29/Jun/2023 16:00:26] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [29/Jun/2023 16:00:26] "POST / HTTP/1.1" 200 -
2023-06-29 16:00:26,710:INFO:logic:main.py:664:handleOrderFilled:2218526: handleOrderFilled: data=OrderType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'clientorderid': '42490F1688025626147I0L64', 'symbol': 'BTCUSDT', 'gatewayorderid': 1688025626541159, 'quantity': '26.868', 'price': '30338.2', 'stopprice': '0', 'ordertype': '', 'side': 'SELL', 'status': 'FILLED', 'positionside': 'SHORT', 'createtime': 1688025625686, 'updatetime': 1688025626541, 'tradetype': 'usdt', 'selfid': 42490, 'filltrades': [TradeType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'tradeid': 1688025626541, 'clientorderid': '42490F1688025626147I0L64', 'price': '30338.2', 'quantity': '26.868', 'commission': '815.1267576', 'commissionasset': 'USDT', 'tradetime': 1688025626541, 'tradetype': 'usdt', 'gatetype': 'simulator', 'handletime': 1688025626541}], 'gatetype': 'simulator', 'handletime': 0}


## /root/FIL/strategy/modifiedmom/log.txt ----- -----

527  20230629   155000    155959  1688025599  30337.8  30333.9 -0.000132
2023-06-29 16:00:02,200:INFO:modifiedmom:main.py:146:handleKline:2218259: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': True, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True}
127.0.0.1 - - [29/Jun/2023 16:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=6656 

self.closeSec=1688026199, self.tradeDate='20230629', self.openTime='160000', self.closeTime='160959', self.symbol='BTCUSDT', self.open='30333.9', self.close='30364.6'
2023-06-29 16:10:01,139:INFO:modifiedmom:main.py:144:handleKline:2218259: self.closeSec=1688026199, self.tradeDate='20230629', self.openTime='160000', self.closeTime='160959',self.symbol='BTCUSDT',self.open='30333.9', self.close='30364.6'
2023-06-29 16:10:01,169:INFO:modifiedmom:main.py:145:handleKline:2218259: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
524  20230629   152000    152959  1688023799  30344.7  30370.5  0.000850
525  20230629   153000    153959  1688024399  30370.6    30318 -0.001729
526  20230629   154000    154959  1688024999  30317.9  30337.9  0.000656
527  20230629   155000    155959  1688025599  30337.8  30333.9 -0.000132
528  20230629   160000    160959  1688026199  30333.9  30364.6  0.001012
2023-06-29 16:10:01,170:INFO:modifiedmom:main.py:146:handleKline:2218259: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': True, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True}

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=6657 

self.closeSec=1688026799, self.tradeDate='20230629', self.openTime='161000', self.closeTime='161959', self.symbol='BTCUSDT', self.open='30364.7', self.close='30385.3'
127.0.0.1 - - [29/Jun/2023 16:20:04] "POST / HTTP/1.1" 200 -
2023-06-29 16:20:07,684:INFO:modifiedmom:main.py:144:handleKline:2218259: self.closeSec=1688026799, self.tradeDate='20230629', self.openTime='161000', self.closeTime='161959',self.symbol='BTCUSDT',self.open='30364.7', self.close='30385.3'
2023-06-29 16:20:08,575:INFO:modifiedmom:main.py:145:handleKline:2218259: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
525  20230629   153000    153959  1688024399  30370.6    30318 -0.001729
526  20230629   154000    154959  1688024999  30317.9  30337.9  0.000656
527  20230629   155000    155959  1688025599  30337.8  30333.9 -0.000132
528  20230629   160000    160959  1688026199  30333.9  30364.6  0.001012
529  20230629   161000    161959  1688026799  30364.7  30385.3  0.000682
2023-06-29 16:20:08,584:INFO:modifiedmom:main.py:146:handleKline:2218259: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': True, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True}


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

17519  20230629   155000    155959  1688025599  30337.8  30333.9
2023-06-29 16:00:02,216:INFO:pyemd2:main.py:127:handleKline:2217508: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}
127.0.0.1 - - [29/Jun/2023 16:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=6659 

self.closeSec=1688026199, self.tradeDate='20230629', self.openTime='160000', self.closeTime='160959', self.symbol='BTCUSDT', self.open='30333.9', self.close='30364.6'
2023-06-29 16:10:01,149:INFO:pyemd2:main.py:125:handleKline:2217508: self.closeSec=1688026199, self.tradeDate='20230629', self.openTime='160000', self.closeTime='160959',self.symbol='BTCUSDT',self.open='30333.9', self.close='30364.6'
2023-06-29 16:10:01,172:INFO:pyemd2:main.py:126:handleKline:2217508: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17516  20230629   152000    152959  1688023799  30344.7  30370.5
17517  20230629   153000    153959  1688024399  30370.6    30318
17518  20230629   154000    154959  1688024999  30317.9  30337.9
17519  20230629   155000    155959  1688025599  30337.8  30333.9
17520  20230629   160000    160959  1688026199  30333.9  30364.6
2023-06-29 16:10:01,172:INFO:pyemd2:main.py:127:handleKline:2217508: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=6660 

self.closeSec=1688026799, self.tradeDate='20230629', self.openTime='161000', self.closeTime='161959', self.symbol='BTCUSDT', self.open='30364.7', self.close='30385.3'
127.0.0.1 - - [29/Jun/2023 16:20:04] "POST / HTTP/1.1" 200 -
2023-06-29 16:20:09,907:INFO:pyemd2:main.py:125:handleKline:2217508: self.closeSec=1688026799, self.tradeDate='20230629', self.openTime='161000', self.closeTime='161959',self.symbol='BTCUSDT',self.open='30364.7', self.close='30385.3'
2023-06-29 16:20:10,073:INFO:pyemd2:main.py:126:handleKline:2217508: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17517  20230629   153000    153959  1688024399  30370.6    30318
17518  20230629   154000    154959  1688024999  30317.9  30337.9
17519  20230629   155000    155959  1688025599  30337.8  30333.9
17520  20230629   160000    160959  1688026199  30333.9  30364.6
17521  20230629   161000    161959  1688026799  30364.7  30385.3
2023-06-29 16:20:10,077:INFO:pyemd2:main.py:127:handleKline:2217508: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}


## /root/FIL/strategy/similarity/log.txt ----- -----

12191  20230629   155000    155959  1688025599  30337.8  30333.9
2023-06-29 16:00:02,211:INFO:testStrategy:main.py:103:handleKline:2217133: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=6659 

self.closeSec=1688026199, self.tradeDate='20230629', self.openTime='160000', self.closeTime='160959', self.symbol='BTCUSDT', self.open='30333.9', self.close='30364.6'
2023-06-29 16:10:01,151:INFO:testStrategy:main.py:101:handleKline:2217133: self.closeSec=1688026199, self.tradeDate='20230629', self.openTime='160000', self.closeTime='160959',self.symbol='BTCUSDT',self.open='30333.9', self.close='30364.6'
127.0.0.1 - - [29/Jun/2023 16:10:01] "POST / HTTP/1.1" 200 -
2023-06-29 16:10:01,172:INFO:testStrategy:main.py:102:handleKline:2217133: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12188  20230629   152000    152959  1688023799  30344.7  30370.5
12189  20230629   153000    153959  1688024399  30370.6    30318
12190  20230629   154000    154959  1688024999  30317.9  30337.9
12191  20230629   155000    155959  1688025599  30337.8  30333.9
12192  20230629   160000    160959  1688026199  30333.9  30364.6
2023-06-29 16:10:01,172:INFO:testStrategy:main.py:103:handleKline:2217133: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=6660 

self.closeSec=1688026799, self.tradeDate='20230629', self.openTime='161000', self.closeTime='161959', self.symbol='BTCUSDT', self.open='30364.7', self.close='30385.3'
127.0.0.1 - - [29/Jun/2023 16:20:04] "POST / HTTP/1.1" 200 -
2023-06-29 16:20:09,405:INFO:testStrategy:main.py:101:handleKline:2217133: self.closeSec=1688026799, self.tradeDate='20230629', self.openTime='161000', self.closeTime='161959',self.symbol='BTCUSDT',self.open='30364.7', self.close='30385.3'
2023-06-29 16:20:09,755:INFO:testStrategy:main.py:102:handleKline:2217133: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12189  20230629   153000    153959  1688024399  30370.6    30318
12190  20230629   154000    154959  1688024999  30317.9  30337.9
12191  20230629   155000    155959  1688025599  30337.8  30333.9
12192  20230629   160000    160959  1688026199  30333.9  30364.6
12193  20230629   161000    161959  1688026799  30364.7  30385.3
2023-06-29 16:20:09,757:INFO:testStrategy:main.py:103:handleKline:2217133: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}


## /root/FIL/strategy/sr_min/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=1, self.total=996015.990996, self.flagDict['side']='buy', self.tradeCount=1, self.count=13312
self.closeSec=1688026799, self.tradeDate='20230629', self.openTime='161500', self.closeTime='161959', self.symbol='BTCUSDT', self.open=30365.6, self.close=30385.4, self.high=30389.5, self.low=30347.8, self.vol=674.155, self.amt=20473423.919 
127.0.0.1 - - [29/Jun/2023 16:20:01] "POST / HTTP/1.1" 200 -
2023-06-29 16:20:07,873:INFO:sr_min:main.py:172:handleKline:2219263: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5951  20230629   155500    155959  ...         0.0        0.0       0
5952  20230629   160000    160459  ...         0.0        0.0       0
5953  20230629   160500    160959  ...         0.0        0.0       0
5954  20230629   161000    161459  ...         0.0        0.0       0
5955  20230629   161500    161959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-06-29 16:20:07,904:INFO:sr_min:main.py:175:handleKline:2219263: self.closeSec=1688026799, self.tradeDate='20230629', self.openTime='161500', self.closeTime='161959',self.symbol='BTCUSDT',self.open=30365.6, self.close=30385.4, self.high=30389.5, self.low=30347.8, self.vol=674.155, self.amt=20473423.919, ukdf['pct'].iloc[-1]=0.000652 , ukdf['amount'].iloc[-1]=20473423.919, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5955, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '37.141', 'enterprice': '26844', 'countrevence': '0', 'unrealprofit': '131616.5617', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '30387.7', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=1
--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=1, self.total=996015.990996, self.flagDict['side']='buy', self.tradeCount=1, self.count=13313
self.closeSec=1688027099, self.tradeDate='20230629', self.openTime='162000', self.closeTime='162459', self.symbol='BTCUSDT', self.open=30385.4, self.close=30390.3, self.high=30397.0, self.low=30364.8, self.vol=1156.24, self.amt=35131194.5139 
127.0.0.1 - - [29/Jun/2023 16:25:00] "POST / HTTP/1.1" 200 -
2023-06-29 16:25:00,828:INFO:sr_min:main.py:172:handleKline:2219263: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5952  20230629   160000    160459  ...         0.0        0.0       0
5953  20230629   160500    160959  ...         0.0        0.0       0
5954  20230629   161000    161459  ...         0.0        0.0       0
5955  20230629   161500    161959  ...         0.0        0.0       0
5956  20230629   162000    162459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-06-29 16:25:00,829:INFO:sr_min:main.py:175:handleKline:2219263: self.closeSec=1688027099, self.tradeDate='20230629', self.openTime='162000', self.closeTime='162459',self.symbol='BTCUSDT',self.open=30385.4, self.close=30390.3, self.high=30397.0, self.low=30364.8, self.vol=1156.24, self.amt=35131194.5139, ukdf['pct'].iloc[-1]=0.000161 , ukdf['amount'].iloc[-1]=35131194.5139, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5956, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '37.141', 'enterprice': '26844', 'countrevence': '0', 'unrealprofit': '131713.1283', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '30390.3', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=1


## /root/FIL/strategy/s_rsrs/log.txt ----- -----

721  20230629   040000    075959  1687996799  ...    721  0.331663 -0.588163     NaN
722  20230629   080000    115959  1688011199  ...    722  0.383382 -0.466988     NaN

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '53.268', 'enterprice': '30707', 'countrevence': '0', 'unrealprofit': '28868.392991487', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '30165.05374725', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-9223372036854775808, self.sign=-1
127.0.0.1 - - [29/Jun/2023 16:00:01] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='s_rsrs', self.symbol='BTCUSDT', interval='4h', intervalSec=14400, wid=25, thd=0.6, self.sign=-1, self.total=1634064.775524, self.flagDict['side']='sell', self.tradeCount=8, self.count=277
self.closeSec=1688025599, self.tradeDate='20230629', self.openTime='120000', self.closeTime='155959', self.symbol='BTCUSDT', self.open=30162.3, self.close=30333.9, self.high=30420.0, self.low=30125.4, self.vol=37925.711, self.amt=1148028294.46104 
2023-06-29 16:00:01,702:INFO:s_rsrs:main.py:141:handleKline:2218689: self.closeSec=1688025599, self.tradeDate='20230629', self.openTime='120000', self.closeTime='155959',self.symbol='BTCUSDT',self.open=30162.3, self.close=30333.9, self.high=30420.0, self.low=30125.4, self.vol=37925.711, self.amt=1148028294.46104 
2023-06-29 16:00:01,746:INFO:s_rsrs:main.py:142:handleKline:2218689: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime  ...         vol           amt       pct
719  20230628   200000    235959  ...  125197.930  3.784724e+09  0.003483
720  20230629   000000    035959  ...  101722.691  3.064347e+09 -0.010507
721  20230629   040000    075959  ...   40288.685  1.211925e+09 -0.000469
722  20230629   080000    115959  ...   34206.224  1.030926e+09  0.003193
723  20230629   120000    155959  ...   37925.711  1.148028e+09  0.005689

[5 rows x 11 columns]
2023-06-29 16:00:03,184:INFO:s_rsrs:main.py:151:handleKline:2218689: df_s.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec  ...  index      beta    zscore  signal
719  20230628   200000    235959  1687967999  ...    719  0.322935 -0.594812     NaN
720  20230629   000000    035959  1687982399  ...    720  0.268669 -0.741625    -1.0
721  20230629   040000    075959  1687996799  ...    721  0.331663 -0.588163     NaN
722  20230629   080000    115959  1688011199  ...    722  0.383382 -0.466988     NaN
723  20230629   120000    155959  1688025599  ...    723  0.380362 -0.491571     NaN

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '53.268', 'enterprice': '30707', 'countrevence': '0', 'unrealprofit': '19874.2908', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '30333.9', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-9223372036854775808, self.sign=-1


