# 20230706 16:26:01

## /root/FIL/strategy/amihud/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=373746.4768026, self.flagDict['side']='sell', self.tradeCount=2, self.count=15328
self.closeSec=1688631599, self.tradeDate='20230706', self.openTime='161500', self.closeTime='161959', self.symbol='BTCUSDT', self.open=30782.8, self.close=30795.9, self.high=30810.0, self.low=30782.8, self.vol=664.042, self.amt=20453342.6316 
127.0.0.1 - - [06/Jul/2023 16:20:01] "POST / HTTP/1.1" 200 -
2023-07-06 16:20:06,906:INFO:amihud:main.py:172:handleKline:2219019: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5951  20230706   155500    155959  ...         0.0        0.0       0
5952  20230706   160000    160459  ...         0.0        0.0       0
5953  20230706   160500    160959  ...         0.0        0.0       0
5954  20230706   161000    161459  ...         0.0        0.0       0
5955  20230706   161500    161959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-07-06 16:20:06,937:INFO:amihud:main.py:175:handleKline:2219019: self.closeSec=1688631599, self.tradeDate='20230706', self.openTime='161500', self.closeTime='161959',self.symbol='BTCUSDT',self.open=30782.8, self.close=30795.9, self.high=30810.0, self.low=30782.8, self.vol=664.042, self.amt=20453342.6316, ukdf['pct'].iloc[-1]=0.000422 , ukdf['amount'].iloc[-1]=20453342.6316, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5955, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '13.926', 'enterprice': '26864.9', 'countrevence': '0', 'unrealprofit': '-54775.79519359332', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '30798.24734982', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1
--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=373746.4768026, self.flagDict['side']='sell', self.tradeCount=2, self.count=15329
self.closeSec=1688631899, self.tradeDate='20230706', self.openTime='162000', self.closeTime='162459', self.symbol='BTCUSDT', self.open=30796.0, self.close=30793.3, self.high=30802.2, self.low=30784.9, self.vol=655.536, self.amt=20187827.0749 
127.0.0.1 - - [06/Jul/2023 16:25:00] "POST / HTTP/1.1" 200 -
2023-07-06 16:25:00,793:INFO:amihud:main.py:172:handleKline:2219019: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5952  20230706   160000    160459  ...         0.0        0.0       0
5953  20230706   160500    160959  ...         0.0        0.0       0
5954  20230706   161000    161459  ...         0.0        0.0       0
5955  20230706   161500    161959  ...         0.0        0.0       0
5956  20230706   162000    162459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-07-06 16:25:00,793:INFO:amihud:main.py:175:handleKline:2219019: self.closeSec=1688631899, self.tradeDate='20230706', self.openTime='162000', self.closeTime='162459',self.symbol='BTCUSDT',self.open=30796.0, self.close=30793.3, self.high=30802.2, self.low=30784.9, self.vol=655.536, self.amt=20187827.0749, ukdf['pct'].iloc[-1]=-8.4e-05 , ukdf['amount'].iloc[-1]=20187827.0749, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5956, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '13.926', 'enterprice': '26864.9', 'countrevence': '0', 'unrealprofit': '-54748.7545742973', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '30796.30561355', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1


## /root/FIL/strategy/factorcheck/log.txt ----- -----


self.closeSec=1688631599, self.tradeDate='20230706', self.openTime='161500', self.closeTime='161959', self.symbol='BTCUSDT', self.open=30782.8, self.close=30795.9, self.high=30810.0, self.low=30782.8 
127.0.0.1 - - [06/Jul/2023 16:20:01] "POST / HTTP/1.1" 200 -
2023-07-06 16:20:04,607:INFO:factorcheck2:main.py:126:handleKline:2218005: self.closeSec=1688631599, self.tradeDate='20230706', self.openTime='161500', self.closeTime='161959',self.symbol='BTCUSDT',self.open=30782.8, self.close=30795.9, self.high=30810.0, self.low=30782.8   
2023-07-06 16:20:06,057:INFO:factorcheck2:main.py:127:handleKline:2218005: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1631  20230706   155500    155959  1688630399  ...  30775.8  0.000533   1631    5
1632  20230706   160000    160459  1688630699  ...  30792.2  0.000672   1632    0
1633  20230706   160500    160959  1688630999  ...  30775.2 -0.001194   1633    1
1634  20230706   161000    161459  1688631299  ...  30771.0  0.000218   1634    2
1635  20230706   161500    161959  1688631599  ...  30782.8  0.000422   1635    3

[5 rows x 11 columns]
2023-07-06 16:20:06,067:INFO:factorcheck2:main.py:128:handleKline:2218005: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': False, 'isOpen': True, 'isClose': False, 'isTrig': True}
127.0.0.1 - - [06/Jul/2023 16:25:00] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=2, self.factor=0.5759211745490451, self.count=15331 

self.closeSec=1688631899, self.tradeDate='20230706', self.openTime='162000', self.closeTime='162459', self.symbol='BTCUSDT', self.open=30796.0, self.close=30793.3, self.high=30802.2, self.low=30784.9 
2023-07-06 16:25:00,737:INFO:factorcheck2:main.py:126:handleKline:2218005: self.closeSec=1688631899, self.tradeDate='20230706', self.openTime='162000', self.closeTime='162459',self.symbol='BTCUSDT',self.open=30796.0, self.close=30793.3, self.high=30802.2, self.low=30784.9   
2023-07-06 16:25:00,777:INFO:factorcheck2:main.py:127:handleKline:2218005: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1632  20230706   160000    160459  1688630699  ...  30792.2  0.000672   1632    0
1633  20230706   160500    160959  1688630999  ...  30775.2 -0.001194   1633    1
1634  20230706   161000    161459  1688631299  ...  30771.0  0.000218   1634    2
1635  20230706   161500    161959  1688631599  ...  30782.8  0.000422   1635    3
1636  20230706   162000    162459  1688631899  ...  30784.9 -0.000084   1636    4

[5 rows x 11 columns]
2023-07-06 16:25:00,777:INFO:factorcheck2:main.py:128:handleKline:2218005: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': False, 'isOpen': True, 'isClose': False, 'isTrig': True}


## /root/FIL/strategy/logic/log.txt ----- -----

537     0  0.509628  0.490372       1  ...  0.902693  -1.0  0.0000  1.002180
538     0  0.534516  0.465484       1  ...  0.902081  -1.0  0.0000  1.002858
539     0  0.520646  0.479354       1  ...  0.899614  -1.0  0.0000  1.005602
540     0  0.539877  0.460123       1  ...  0.897356  -1.0  0.0000  1.008125
541     0  0.551144  0.448856       1  ...  0.896953   1.0 -0.0016  1.009286

[5 rows x 10 columns]
2023-07-06 16:00:18,464:INFO:logic:main.py:478:getModel:2218526: df_panel.iloc[-5:,:] :
    pred    prob_0    prob_1  actual  ...       nav  sign   cost_        bm
45     0  0.509582  0.490418       1  ...  0.902693  -1.0  0.0000  1.002226
46     0  0.533820  0.466180       1  ...  0.902081  -1.0  0.0000  1.001598
47     0  0.520458  0.479542       1  ...  0.899614  -1.0  0.0000  1.005104
48     0  0.540436  0.459564       1  ...  0.897356  -1.0  0.0000  1.009555
49     0  0.551144  0.448856       1  ...  0.896953   1.0 -0.0016  1.009286

[5 rows x 10 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '25.486', 'enterprice': '30415.6', 'countrevence': '0', 'unrealprofit': '-9939.54', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '30805.6', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
handlebackTrade > queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '25.486', 'enterprice': '30415.6', 'countrevence': '0', 'unrealprofit': '-9832.4988', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '30801.4', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
2023-07-06 16:00:25,274:INFO:logic:main.py:500:queryContractAssets:2218526: queryContractAssets: assets=ContractAssetReturn{'result': [ContractAsset{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'asset': 'USDT', 'free': '766969.0607737', 'total': '766969.0607737', 'margin': '0', 'unreal': '0', 'type': 'AssetType_ucontract'}]}
2023-07-06 16:00:25,734:DEBUG:logic:main.py:571:openBuy:2218526: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': True, 'isCloseBuy': False, 'isCloseSell': False, 'isOpen': True, 'isClose': False, 'isTrig': False}
2023-07-06 16:00:25,734:INFO:logic:main.py:572:openBuy:2218526: ret = self.client.insertMarketUOrder("simulator", "BTCUSDT", 24.833, "buy"), ret=InsertOrderReturn{'result': 'success', 'clientorderid': '42540F1688630425733I0L64'}
2023-07-06 16:00:25,750:INFO:logic:main.py:494:insertFactor:2218526: curDateTime:7061600, name:logic, symbol:BTCUSDT, tradeDate:20230706, closeTime:155959, close:30792.3, sign:1, total:766969.0607737, side:buy  
127.0.0.1 - - [06/Jul/2023 16:00:25] "POST / HTTP/1.1" 200 -
2023-07-06 16:00:25,750:INFO:logic:main.py:661:handleOrderNew:2218526: handleOrderNew: data=OrderType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'clientorderid': '42539F1688630420199I0L64', 'symbol': 'BTCUSDT', 'gatewayorderid': 1688630420635054, 'quantity': '25.486', 'price': '30801.4', 'stopprice': '0', 'ordertype': '', 'side': 'BUY', 'status': 'FILLED', 'positionside': 'LONG', 'createtime': 1688630419307, 'updatetime': 1688630420635, 'tradetype': 'usdt', 'selfid': 42539, 'filltrades': [TradeType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'tradeid': 1688630420635, 'clientorderid': '42539F1688630420199I0L64', 'price': '30801.4', 'quantity': '25.486', 'commission': '785.0044804', 'commissionasset': 'USDT', 'tradetime': 1688630420635, 'tradetype': 'usdt', 'gatetype': 'simulator', 'handletime': 1688630420635}], 'gatetype': 'simulator', 'handletime': 0}
127.0.0.1 - - [06/Jul/2023 16:00:25] "POST / HTTP/1.1" 200 -
2023-07-06 16:00:25,752:INFO:logic:main.py:664:handleOrderFilled:2218526: handleOrderFilled: data=OrderType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'clientorderid': '42539F1688630420199I0L64', 'symbol': 'BTCUSDT', 'gatewayorderid': 1688630420635054, 'quantity': '25.486', 'price': '30801.4', 'stopprice': '0', 'ordertype': '', 'side': 'BUY', 'status': 'FILLED', 'positionside': 'LONG', 'createtime': 1688630419307, 'updatetime': 1688630420635, 'tradetype': 'usdt', 'selfid': 42539, 'filltrades': [TradeType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'tradeid': 1688630420635, 'clientorderid': '42539F1688630420199I0L64', 'price': '30801.4', 'quantity': '25.486', 'commission': '785.0044804', 'commissionasset': 'USDT', 'tradetime': 1688630420635, 'tradetype': 'usdt', 'gatetype': 'simulator', 'handletime': 1688630420635}], 'gatetype': 'simulator', 'handletime': 0}
2023-07-06 16:00:26,174:INFO:logic:main.py:661:handleOrderNew:2218526: handleOrderNew: data=OrderType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'clientorderid': '42540F1688630425733I0L64', 'symbol': 'BTCUSDT', 'gatewayorderid': 1688630426138080, 'quantity': '24.833', 'price': '30808.5', 'stopprice': '0', 'ordertype': '', 'side': 'BUY', 'status': 'FILLED', 'positionside': 'LONG', 'createtime': 1688630425283, 'updatetime': 1688630426138, 'tradetype': 'usdt', 'selfid': 42540, 'filltrades': [TradeType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'tradeid': 1688630426138, 'clientorderid': '42540F1688630425733I0L64', 'price': '30808.5', 'quantity': '24.833', 'commission': '765.0674805', 'commissionasset': 'USDT', 'tradetime': 1688630426138, 'tradetype': 'usdt', 'gatetype': 'simulator', 'handletime': 1688630426138}], 'gatetype': 'simulator', 'handletime': 0}
127.0.0.1 - - [06/Jul/2023 16:00:26] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [06/Jul/2023 16:00:26] "POST / HTTP/1.1" 200 -
2023-07-06 16:00:26,297:INFO:logic:main.py:664:handleOrderFilled:2218526: handleOrderFilled: data=OrderType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'clientorderid': '42540F1688630425733I0L64', 'symbol': 'BTCUSDT', 'gatewayorderid': 1688630426138080, 'quantity': '24.833', 'price': '30808.5', 'stopprice': '0', 'ordertype': '', 'side': 'BUY', 'status': 'FILLED', 'positionside': 'LONG', 'createtime': 1688630425283, 'updatetime': 1688630426138, 'tradetype': 'usdt', 'selfid': 42540, 'filltrades': [TradeType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'tradeid': 1688630426138, 'clientorderid': '42540F1688630425733I0L64', 'price': '30808.5', 'quantity': '24.833', 'commission': '765.0674805', 'commissionasset': 'USDT', 'tradetime': 1688630426138, 'tradetype': 'usdt', 'gatetype': 'simulator', 'handletime': 1688630426138}], 'gatetype': 'simulator', 'handletime': 0}


## /root/FIL/strategy/modifiedmom/log.txt ----- -----

527  20230706   155000    155959  1688630399    30800  30792.3 -0.000247
2023-07-06 16:00:02,159:INFO:modifiedmom:main.py:146:handleKline:2218259: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True}
127.0.0.1 - - [06/Jul/2023 16:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=7664 

self.closeSec=1688630999, self.tradeDate='20230706', self.openTime='160000', self.closeTime='160959', self.symbol='BTCUSDT', self.open='30792.2', self.close='30779.7'
2023-07-06 16:10:01,155:INFO:modifiedmom:main.py:144:handleKline:2218259: self.closeSec=1688630999, self.tradeDate='20230706', self.openTime='160000', self.closeTime='160959',self.symbol='BTCUSDT',self.open='30792.2', self.close='30779.7'
2023-07-06 16:10:01,175:INFO:modifiedmom:main.py:145:handleKline:2218259: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
524  20230706   152000    152959  1688628599  30708.4  30756.8  0.001573
525  20230706   153000    153959  1688629199  30756.8  30842.7  0.002793
526  20230706   154000    154959  1688629799  30837.6  30799.9 -0.001388
527  20230706   155000    155959  1688630399    30800  30792.3 -0.000247
528  20230706   160000    160959  1688630999  30792.2  30779.7 -0.000409
2023-07-06 16:10:01,175:INFO:modifiedmom:main.py:146:handleKline:2218259: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True}

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=7665 

self.closeSec=1688631599, self.tradeDate='20230706', self.openTime='161000', self.closeTime='161959', self.symbol='BTCUSDT', self.open='30779.7', self.close='30795.9'
127.0.0.1 - - [06/Jul/2023 16:20:04] "POST / HTTP/1.1" 200 -
2023-07-06 16:20:06,937:INFO:modifiedmom:main.py:144:handleKline:2218259: self.closeSec=1688631599, self.tradeDate='20230706', self.openTime='161000', self.closeTime='161959',self.symbol='BTCUSDT',self.open='30779.7', self.close='30795.9'
2023-07-06 16:20:07,706:INFO:modifiedmom:main.py:145:handleKline:2218259: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
525  20230706   153000    153959  1688629199  30756.8  30842.7  0.002793
526  20230706   154000    154959  1688629799  30837.6  30799.9 -0.001388
527  20230706   155000    155959  1688630399    30800  30792.3 -0.000247
528  20230706   160000    160959  1688630999  30792.2  30779.7 -0.000409
529  20230706   161000    161959  1688631599  30779.7  30795.9  0.000526
2023-07-06 16:20:07,706:INFO:modifiedmom:main.py:146:handleKline:2218259: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True}


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

17519  20230706   155000    155959  1688630399    30800  30792.3
2023-07-06 16:00:02,152:INFO:pyemd2:main.py:127:handleKline:2217508: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}
127.0.0.1 - - [06/Jul/2023 16:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=7667 

self.closeSec=1688630999, self.tradeDate='20230706', self.openTime='160000', self.closeTime='160959', self.symbol='BTCUSDT', self.open='30792.2', self.close='30779.7'
2023-07-06 16:10:01,146:INFO:pyemd2:main.py:125:handleKline:2217508: self.closeSec=1688630999, self.tradeDate='20230706', self.openTime='160000', self.closeTime='160959',self.symbol='BTCUSDT',self.open='30792.2', self.close='30779.7'
2023-07-06 16:10:01,154:INFO:pyemd2:main.py:126:handleKline:2217508: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17516  20230706   152000    152959  1688628599  30708.4  30756.8
17517  20230706   153000    153959  1688629199  30756.8  30842.7
17518  20230706   154000    154959  1688629799  30837.6  30799.9
17519  20230706   155000    155959  1688630399    30800  30792.3
17520  20230706   160000    160959  1688630999  30792.2  30779.7
2023-07-06 16:10:01,155:INFO:pyemd2:main.py:127:handleKline:2217508: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=7668 

self.closeSec=1688631599, self.tradeDate='20230706', self.openTime='161000', self.closeTime='161959', self.symbol='BTCUSDT', self.open='30779.7', self.close='30795.9'
127.0.0.1 - - [06/Jul/2023 16:20:04] "POST / HTTP/1.1" 200 -
2023-07-06 16:20:08,580:INFO:pyemd2:main.py:125:handleKline:2217508: self.closeSec=1688631599, self.tradeDate='20230706', self.openTime='161000', self.closeTime='161959',self.symbol='BTCUSDT',self.open='30779.7', self.close='30795.9'
2023-07-06 16:20:08,794:INFO:pyemd2:main.py:126:handleKline:2217508: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17517  20230706   153000    153959  1688629199  30756.8  30842.7
17518  20230706   154000    154959  1688629799  30837.6  30799.9
17519  20230706   155000    155959  1688630399    30800  30792.3
17520  20230706   160000    160959  1688630999  30792.2  30779.7
17521  20230706   161000    161959  1688631599  30779.7  30795.9
2023-07-06 16:20:08,794:INFO:pyemd2:main.py:127:handleKline:2217508: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}


## /root/FIL/strategy/similarity/log.txt ----- -----

12191  20230706   155000    155959  1688630399    30800  30792.3
2023-07-06 16:00:02,165:INFO:testStrategy:main.py:103:handleKline:2217133: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}
127.0.0.1 - - [06/Jul/2023 16:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=7667 

self.closeSec=1688630999, self.tradeDate='20230706', self.openTime='160000', self.closeTime='160959', self.symbol='BTCUSDT', self.open='30792.2', self.close='30779.7'
2023-07-06 16:10:01,167:INFO:testStrategy:main.py:101:handleKline:2217133: self.closeSec=1688630999, self.tradeDate='20230706', self.openTime='160000', self.closeTime='160959',self.symbol='BTCUSDT',self.open='30792.2', self.close='30779.7'
2023-07-06 16:10:01,183:INFO:testStrategy:main.py:102:handleKline:2217133: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12188  20230706   152000    152959  1688628599  30708.4  30756.8
12189  20230706   153000    153959  1688629199  30756.8  30842.7
12190  20230706   154000    154959  1688629799  30837.6  30799.9
12191  20230706   155000    155959  1688630399    30800  30792.3
12192  20230706   160000    160959  1688630999  30792.2  30779.7
2023-07-06 16:10:01,183:INFO:testStrategy:main.py:103:handleKline:2217133: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=7668 

self.closeSec=1688631599, self.tradeDate='20230706', self.openTime='161000', self.closeTime='161959', self.symbol='BTCUSDT', self.open='30779.7', self.close='30795.9'
127.0.0.1 - - [06/Jul/2023 16:20:04] "POST / HTTP/1.1" 200 -
2023-07-06 16:20:08,288:INFO:testStrategy:main.py:101:handleKline:2217133: self.closeSec=1688631599, self.tradeDate='20230706', self.openTime='161000', self.closeTime='161959',self.symbol='BTCUSDT',self.open='30779.7', self.close='30795.9'
2023-07-06 16:20:08,579:INFO:testStrategy:main.py:102:handleKline:2217133: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12189  20230706   153000    153959  1688629199  30756.8  30842.7
12190  20230706   154000    154959  1688629799  30837.6  30799.9
12191  20230706   155000    155959  1688630399    30800  30792.3
12192  20230706   160000    160959  1688630999  30792.2  30779.7
12193  20230706   161000    161959  1688631599  30779.7  30795.9
2023-07-06 16:20:08,581:INFO:testStrategy:main.py:103:handleKline:2217133: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}


## /root/FIL/strategy/sr_min/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=1, self.total=996015.990996, self.flagDict['side']='buy', self.tradeCount=1, self.count=15328
self.closeSec=1688631599, self.tradeDate='20230706', self.openTime='161500', self.closeTime='161959', self.symbol='BTCUSDT', self.open=30782.8, self.close=30795.9, self.high=30810.0, self.low=30782.8, self.vol=664.042, self.amt=20453342.6316 
127.0.0.1 - - [06/Jul/2023 16:20:01] "POST / HTTP/1.1" 200 -
2023-07-06 16:20:06,906:INFO:sr_min:main.py:172:handleKline:2219263: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5951  20230706   155500    155959  ...         0.0        0.0       0
5952  20230706   160000    160459  ...         0.0        0.0       0
5953  20230706   160500    160959  ...         0.0        0.0       0
5954  20230706   161000    161459  ...         0.0        0.0       0
5955  20230706   161500    161959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-07-06 16:20:06,936:INFO:sr_min:main.py:175:handleKline:2219263: self.closeSec=1688631599, self.tradeDate='20230706', self.openTime='161500', self.closeTime='161959',self.symbol='BTCUSDT',self.open=30782.8, self.close=30795.9, self.high=30810.0, self.low=30782.8, self.vol=664.042, self.amt=20453342.6316, ukdf['pct'].iloc[-1]=0.000422 , ukdf['amount'].iloc[-1]=20453342.6316, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5955, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '37.141', 'enterprice': '26844', 'countrevence': '0', 'unrealprofit': '146864.70081966462', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '30798.24734982', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=1
--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=1, self.total=996015.990996, self.flagDict['side']='buy', self.tradeCount=1, self.count=15329
self.closeSec=1688631899, self.tradeDate='20230706', self.openTime='162000', self.closeTime='162459', self.symbol='BTCUSDT', self.open=30796.0, self.close=30793.3, self.high=30802.2, self.low=30784.9, self.vol=655.536, self.amt=20187827.0749 
127.0.0.1 - - [06/Jul/2023 16:25:00] "POST / HTTP/1.1" 200 -
2023-07-06 16:25:00,796:INFO:sr_min:main.py:172:handleKline:2219263: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5952  20230706   160000    160459  ...         0.0        0.0       0
5953  20230706   160500    160959  ...         0.0        0.0       0
5954  20230706   161000    161459  ...         0.0        0.0       0
5955  20230706   161500    161959  ...         0.0        0.0       0
5956  20230706   162000    162459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-07-06 16:25:00,796:INFO:sr_min:main.py:175:handleKline:2219263: self.closeSec=1688631899, self.tradeDate='20230706', self.openTime='162000', self.closeTime='162459',self.symbol='BTCUSDT',self.open=30796.0, self.close=30793.3, self.high=30802.2, self.low=30784.9, self.vol=655.536, self.amt=20187827.0749, ukdf['pct'].iloc[-1]=-8.4e-05 , ukdf['amount'].iloc[-1]=20187827.0749, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5956, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '37.141', 'enterprice': '26844', 'countrevence': '0', 'unrealprofit': '146792.58279286055', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '30796.30561355', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=1


## /root/FIL/strategy/s_rsrs/log.txt ----- -----

721  20230706   040000    075959  1688601599  ...    721  0.614850  0.372855     NaN
722  20230706   080000    115959  1688615999  ...    722  0.642712  0.469417     NaN

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '53.05', 'enterprice': '30750.9', 'countrevence': '0', 'unrealprofit': '-14222.705', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '30482.8', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-9223372036854775808, self.sign=1
127.0.0.1 - - [06/Jul/2023 16:00:01] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='s_rsrs', self.symbol='BTCUSDT', interval='4h', intervalSec=14400, wid=25, thd=0.6, self.sign=1, self.total=1629703.909755, self.flagDict['side']='buy', self.tradeCount=9, self.count=319
self.closeSec=1688630399, self.tradeDate='20230706', self.openTime='120000', self.closeTime='155959', self.symbol='BTCUSDT', self.open=30477.6, self.close=30792.3, self.high=30846.8, self.low=30420.6, self.vol=59326.951, self.amt=1819309773.57787 
2023-07-06 16:00:01,684:INFO:s_rsrs:main.py:141:handleKline:2218689: self.closeSec=1688630399, self.tradeDate='20230706', self.openTime='120000', self.closeTime='155959',self.symbol='BTCUSDT',self.open=30477.6, self.close=30792.3, self.high=30846.8, self.low=30420.6, self.vol=59326.951, self.amt=1819309773.57787 
2023-07-06 16:00:01,713:INFO:s_rsrs:main.py:142:handleKline:2218689: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime  ...        vol           amt       pct
719  20230705   200000    235959  ...  93102.558  2.823460e+09 -0.001645
720  20230706   000000    035959  ...  47167.111  1.437322e+09  0.002472
721  20230706   040000    075959  ...  26258.551  7.995880e+08  0.002252
722  20230706   080000    115959  ...  27525.436  8.380867e+08 -0.000354
723  20230706   120000    155959  ...  59326.951  1.819310e+09  0.010322

[5 rows x 11 columns]
2023-07-06 16:00:03,285:INFO:s_rsrs:main.py:151:handleKline:2218689: df_s.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec  ...  index      beta    zscore  signal
719  20230705   200000    235959  1688572799  ...    719  0.568203  0.246937     NaN
720  20230706   000000    035959  1688587199  ...    720  0.578402  0.269805     NaN
721  20230706   040000    075959  1688601599  ...    721  0.614850  0.372855     NaN
722  20230706   080000    115959  1688615999  ...    722  0.642712  0.469417     NaN
723  20230706   120000    155959  1688630399  ...    723  0.604498  0.401745     NaN

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '53.05', 'enterprice': '30750.9', 'countrevence': '0', 'unrealprofit': '2313.0743435895', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '30794.50177839', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-9223372036854775808, self.sign=1


