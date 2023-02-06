# 20230207 00:35:51

## /root/FIL/strategy/amihud/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=993672.4896432, self.flagDict['side']='sell', self.tradeCount=2, self.count=20574
self.closeSec=1675700999, self.tradeDate='20230207', self.openTime='002500', self.closeTime='002959', self.symbol='BTCUSDT', self.open=23100.9, self.close=23075.6, self.high=23127.5, self.low=23074.0, self.vol=2752.025, self.amt=63576462.3707 
127.0.0.1 - - [07/Feb/2023 00:30:00] "POST / HTTP/1.1" 200 -
2023-02-07 00:30:00,890:INFO:amihud:main.py:172:handleKline:200676: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5761  20230207   000500    000959  ...         0.0        0.0       0
5762  20230207   001000    001459  ...         0.0        0.0       0
5763  20230207   001500    001959  ...         0.0        0.0       0
5764  20230207   002000    002459  ...         0.0        0.0       0
5765  20230207   002500    002959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-02-07 00:30:00,895:INFO:amihud:main.py:175:handleKline:200676: self.closeSec=1675700999, self.tradeDate='20230207', self.openTime='002500', self.closeTime='002959',self.symbol='BTCUSDT',self.open=23100.9, self.close=23075.6, self.high=23127.5, self.low=23074.0, self.vol=2752.025, self.amt=63576462.3707, ukdf['pct'].iloc[-1]=-0.001091 , ukdf['amount'].iloc[-1]=63576462.3707, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5765, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '60.176', 'enterprice': '16529.3', 'countrevence': '0', 'unrealprofit': '-394051.56377473968', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '23077.61766443', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1
127.0.0.1 - - [07/Feb/2023 00:35:00] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=993672.4896432, self.flagDict['side']='sell', self.tradeCount=2, self.count=20575
self.closeSec=1675701299, self.tradeDate='20230207', self.openTime='003000', self.closeTime='003459', self.symbol='BTCUSDT', self.open=23074.1, self.close=23040.2, self.high=23090.0, self.low=23040.0, self.vol=3151.669, self.amt=72690898.1775 
2023-02-07 00:35:00,788:INFO:amihud:main.py:172:handleKline:200676: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5762  20230207   001000    001459  ...         0.0        0.0       0
5763  20230207   001500    001959  ...         0.0        0.0       0
5764  20230207   002000    002459  ...         0.0        0.0       0
5765  20230207   002500    002959  ...         0.0        0.0       0
5766  20230207   003000    003459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-02-07 00:35:00,789:INFO:amihud:main.py:175:handleKline:200676: self.closeSec=1675701299, self.tradeDate='20230207', self.openTime='003000', self.closeTime='003459',self.symbol='BTCUSDT',self.open=23074.1, self.close=23040.2, self.high=23090.0, self.low=23040.0, self.vol=3151.669, self.amt=72690898.1775, ukdf['pct'].iloc[-1]=-0.001534 , ukdf['amount'].iloc[-1]=72690898.1775, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5766, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '60.176', 'enterprice': '16529.3', 'countrevence': '0', 'unrealprofit': '-391674.57284026592', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '23038.11701742', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1


## /root/FIL/strategy/factorcheck/log.txt ----- -----

1445  20230207   002500    002959  1675700999  ...  23074.0 -0.001091   1445    5

[5 rows x 11 columns]
2023-02-07 00:30:00,813:INFO:factorcheck2:main.py:128:handleKline:185239: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': False, 'isOpen': True, 'isClose': False, 'isTrig': True}
2023-02-07 00:30:00,864:INFO:factorcheck2:main.py:145:handleKline:185239: df_panel.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec  ...       pct  index  idx    factor
197  20230206   222500    222959  1675693799  ... -0.000793   1709    5  0.632480
198  20230206   225500    225959  1675695599  ...  0.001697   1715    5  0.628794
199  20230206   232500    232959  1675697399  ...  0.000220   1721    5  0.628771
200  20230206   235500    235959  1675699199  ...  0.006301   1727    5  0.614031
201  20230207   002500    002959  1675700999  ... -0.001091   1445    5  0.601140

[5 rows x 12 columns]
2023-02-07 00:30:00,917:INFO:factorcheck2:main.py:201:insertFactor:185239: curDateTime:2070030, name:factorcheck2, symbol:BTCUSDT, tradeDate:20230207, closeTime:002959, close:23075.6, total:928613.5591976999, factor:0.6011398540867537, factorCnt:0, side:buy 
127.0.0.1 - - [07/Feb/2023 00:35:00] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.6011398540867537, self.count=21141 

self.closeSec=1675701299, self.tradeDate='20230207', self.openTime='003000', self.closeTime='003459', self.symbol='BTCUSDT', self.open=23074.1, self.close=23040.2, self.high=23090.0, self.low=23040.0 
2023-02-07 00:35:00,660:INFO:factorcheck2:main.py:126:handleKline:185239: self.closeSec=1675701299, self.tradeDate='20230207', self.openTime='003000', self.closeTime='003459',self.symbol='BTCUSDT',self.open=23074.1, self.close=23040.2, self.high=23090.0, self.low=23040.0   
2023-02-07 00:35:00,734:INFO:factorcheck2:main.py:127:handleKline:185239: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1442  20230207   001000    001459  1675700099  ...  23038.0  0.000451   1442    2
1443  20230207   001500    001959  1675700399  ...  23079.9  0.001884   1443    3
1444  20230207   002000    002459  1675700699  ...  23091.0 -0.001146   1444    4
1445  20230207   002500    002959  1675700999  ...  23074.0 -0.001091   1445    5
1446  20230207   003000    003459  1675701299  ...  23040.0 -0.001534   1446    0

[5 rows x 11 columns]
2023-02-07 00:35:00,735:INFO:factorcheck2:main.py:128:handleKline:185239: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': False, 'isOpen': True, 'isClose': False, 'isTrig': True}


## /root/FIL/strategy/logic/log.txt ----- -----

534     1  0.495780  0.504220       0  ...  1.030186  -1.0  0.0000  0.994846
535     1  0.489718  0.510282       1  ...  1.029106  -1.0  0.0000  0.995888
536     1  0.498922  0.501078       0  ...  1.032080  -1.0  0.0000  0.993010
537     1  0.475211  0.524789       1  ...  1.019748  -1.0  0.0000  1.004875
538     0  0.559164  0.440836       1  ...  1.019511   1.0 -0.0016  1.006249

[5 rows x 10 columns]
2023-02-07 00:30:31,284:INFO:logic:main.py:478:getModel:885513: df_panel.iloc[-5:,:] :
    pred    prob_0    prob_1  actual  ...       nav  sign   cost_        bm
45     1  0.493787  0.506213       0  ...  1.052683  -1.0  0.0000  0.988287
46     1  0.487673  0.512327       1  ...  1.051580  -1.0  0.0000  0.989322
47     1  0.498006  0.501994       0  ...  1.032080  -1.0  0.0000  0.989089
48     1  0.474759  0.525241       1  ...  1.019748  -1.0  0.0000  1.003606
49     0  0.559164  0.440836       1  ...  1.019511   1.0 -0.0016  1.006249

[5 rows x 10 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '30.907', 'enterprice': '23688.5', 'countrevence': '0', 'unrealprofit': '18788.18023630168', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '23080.60598776', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
handlebackTrade > queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '30.907', 'enterprice': '23688.5', 'countrevence': '0', 'unrealprofit': '18788.18023630168', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '23080.60598776', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
2023-02-07 00:30:37,150:INFO:logic:main.py:500:queryContractAssets:885513: queryContractAssets: assets=ContractAssetReturn{'result': [ContractAsset{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'asset': 'USDT', 'free': '752192.5890135', 'total': '752192.5890135', 'margin': '0', 'unreal': '0', 'type': 'AssetType_ucontract'}]}
2023-02-07 00:30:37,347:DEBUG:logic:main.py:571:openBuy:885513: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': True, 'isCloseBuy': False, 'isCloseSell': False, 'isOpen': True, 'isClose': False, 'isTrig': False}
2023-02-07 00:30:37,347:INFO:logic:main.py:572:openBuy:885513: ret = self.client.insertMarketUOrder("simulator", "BTCUSDT", 32.499, "buy"), ret=InsertOrderReturn{'result': 'success', 'clientorderid': '41678F1675701037346I0L64'}
2023-02-07 00:30:37,366:INFO:logic:main.py:494:insertFactor:885513: curDateTime:2070030, name:logic, symbol:BTCUSDT, tradeDate:20230207, closeTime:002959, close:23075.6, sign:1, total:752192.5890135, side:buy  
127.0.0.1 - - [07/Feb/2023 00:30:37] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [07/Feb/2023 00:30:37] "POST / HTTP/1.1" 200 -
2023-02-07 00:30:37,368:INFO:logic:main.py:661:handleOrderNew:885513: handleOrderNew: data=OrderType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'clientorderid': '41677F1675701032066I0L64', 'symbol': 'BTCUSDT', 'gatewayorderid': 1675701032214598, 'quantity': '30.907', 'price': '23079.9', 'stopprice': '0', 'ordertype': '', 'side': 'BUY', 'status': 'FILLED', 'positionside': 'LONG', 'createtime': 1675701031554, 'updatetime': 1675701032214, 'tradetype': 'usdt', 'selfid': 41677, 'filltrades': [TradeType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'tradeid': 1675701032214, 'clientorderid': '41677F1675701032066I0L64', 'price': '23079.9', 'quantity': '30.907', 'commission': '713.3304693', 'commissionasset': 'USDT', 'tradetime': 1675701032214, 'tradetype': 'usdt', 'gatetype': 'simulator', 'handletime': 1675701032214}], 'gatetype': 'simulator', 'handletime': 0}
2023-02-07 00:30:37,369:INFO:logic:main.py:664:handleOrderFilled:885513: handleOrderFilled: data=OrderType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'clientorderid': '41677F1675701032066I0L64', 'symbol': 'BTCUSDT', 'gatewayorderid': 1675701032214598, 'quantity': '30.907', 'price': '23079.9', 'stopprice': '0', 'ordertype': '', 'side': 'BUY', 'status': 'FILLED', 'positionside': 'LONG', 'createtime': 1675701031554, 'updatetime': 1675701032214, 'tradetype': 'usdt', 'selfid': 41677, 'filltrades': [TradeType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'tradeid': 1675701032214, 'clientorderid': '41677F1675701032066I0L64', 'price': '23079.9', 'quantity': '30.907', 'commission': '713.3304693', 'commissionasset': 'USDT', 'tradetime': 1675701032214, 'tradetype': 'usdt', 'gatetype': 'simulator', 'handletime': 1675701032214}], 'gatetype': 'simulator', 'handletime': 0}
127.0.0.1 - - [07/Feb/2023 00:30:37] "POST / HTTP/1.1" 200 -
2023-02-07 00:30:37,521:INFO:logic:main.py:661:handleOrderNew:885513: handleOrderNew: data=OrderType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'clientorderid': '41678F1675701037346I0L64', 'symbol': 'BTCUSDT', 'gatewayorderid': 1675701037483429, 'quantity': '32.499', 'price': '23083.4', 'stopprice': '0', 'ordertype': '', 'side': 'BUY', 'status': 'FILLED', 'positionside': 'LONG', 'createtime': 1675701037161, 'updatetime': 1675701037483, 'tradetype': 'usdt', 'selfid': 41678, 'filltrades': [TradeType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'tradeid': 1675701037483, 'clientorderid': '41678F1675701037346I0L64', 'price': '23083.4', 'quantity': '32.499', 'commission': '750.1874166', 'commissionasset': 'USDT', 'tradetime': 1675701037483, 'tradetype': 'usdt', 'gatetype': 'simulator', 'handletime': 1675701037483}], 'gatetype': 'simulator', 'handletime': 0}
2023-02-07 00:30:37,765:INFO:logic:main.py:664:handleOrderFilled:885513: handleOrderFilled: data=OrderType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'clientorderid': '41678F1675701037346I0L64', 'symbol': 'BTCUSDT', 'gatewayorderid': 1675701037483429, 'quantity': '32.499', 'price': '23083.4', 'stopprice': '0', 'ordertype': '', 'side': 'BUY', 'status': 'FILLED', 'positionside': 'LONG', 'createtime': 1675701037161, 'updatetime': 1675701037483, 'tradetype': 'usdt', 'selfid': 41678, 'filltrades': [TradeType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'tradeid': 1675701037483, 'clientorderid': '41678F1675701037346I0L64', 'price': '23083.4', 'quantity': '32.499', 'commission': '750.1874166', 'commissionasset': 'USDT', 'tradetime': 1675701037483, 'tradetype': 'usdt', 'gatetype': 'simulator', 'handletime': 1675701037483}], 'gatetype': 'simulator', 'handletime': 0}
127.0.0.1 - - [07/Feb/2023 00:30:37] "POST / HTTP/1.1" 200 -


## /root/FIL/strategy/modifiedmom/log.txt ----- -----

576  20230207   000000    000959  1675699799  23040.5  23073.4  0.001271
2023-02-07 00:10:01,535:INFO:modifiedmom:main.py:146:handleKline:185213: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=10569 127.0.0.1 - - [07/Feb/2023 00:20:00] "POST / HTTP/1.1" 200 -


self.closeSec=1675700399, self.tradeDate='20230207', self.openTime='001000', self.closeTime='001959', self.symbol='BTCUSDT', self.open='23073.4', self.close='23127.3'
2023-02-07 00:20:00,659:INFO:modifiedmom:main.py:144:handleKline:185213: self.closeSec=1675700399, self.tradeDate='20230207', self.openTime='001000', self.closeTime='001959',self.symbol='BTCUSDT',self.open='23073.4', self.close='23127.3'
2023-02-07 00:20:00,684:INFO:modifiedmom:main.py:145:handleKline:185213: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
573  20230206   233000    233959  1675697999    22772  22790.6  0.000817
574  20230206   234000    234959  1675698599  22790.6  22818.6  0.001229
575  20230206   235000    235959  1675699199    22820  23044.1  0.009882
576  20230207   000000    000959  1675699799  23040.5  23073.4  0.001271
577  20230207   001000    001959  1675700399  23073.4  23127.3  0.002336
2023-02-07 00:20:00,684:INFO:modifiedmom:main.py:146:handleKline:185213: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=10570 

self.closeSec=1675700999, self.tradeDate='20230207', self.openTime='002000', self.closeTime='002959', self.symbol='BTCUSDT', self.open='23127.2', self.close='23075.6'
127.0.0.1 - - [07/Feb/2023 00:30:00] "POST / HTTP/1.1" 200 -
2023-02-07 00:30:00,981:INFO:modifiedmom:main.py:144:handleKline:185213: self.closeSec=1675700999, self.tradeDate='20230207', self.openTime='002000', self.closeTime='002959',self.symbol='BTCUSDT',self.open='23127.2', self.close='23075.6'
2023-02-07 00:30:01,005:INFO:modifiedmom:main.py:145:handleKline:185213: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
574  20230206   234000    234959  1675698599  22790.6  22818.6  0.001229
575  20230206   235000    235959  1675699199    22820  23044.1  0.009882
576  20230207   000000    000959  1675699799  23040.5  23073.4  0.001271
577  20230207   001000    001959  1675700399  23073.4  23127.3  0.002336
578  20230207   002000    002959  1675700999  23127.2  23075.6 -0.002235
2023-02-07 00:30:01,005:INFO:modifiedmom:main.py:146:handleKline:185213: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False}


## /root/FIL/strategy/pyemd/log.txt ----- -----

17424  20230207   000000    000959  1675699799  23040.5  23073.4
2023-02-07 00:10:01,560:INFO:pyemd2:main.py:127:handleKline:185189: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}
127.0.0.1 - - [07/Feb/2023 00:20:00] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=10570 

self.closeSec=1675700399, self.tradeDate='20230207', self.openTime='001000', self.closeTime='001959', self.symbol='BTCUSDT', self.open='23073.4', self.close='23127.3'
2023-02-07 00:20:00,653:INFO:pyemd2:main.py:125:handleKline:185189: self.closeSec=1675700399, self.tradeDate='20230207', self.openTime='001000', self.closeTime='001959',self.symbol='BTCUSDT',self.open='23073.4', self.close='23127.3'
2023-02-07 00:20:00,675:INFO:pyemd2:main.py:126:handleKline:185189: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17421  20230206   233000    233959  1675697999    22772  22790.6
17422  20230206   234000    234959  1675698599  22790.6  22818.6
17423  20230206   235000    235959  1675699199    22820  23044.1
17424  20230207   000000    000959  1675699799  23040.5  23073.4
17425  20230207   001000    001959  1675700399  23073.4  23127.3
2023-02-07 00:20:00,676:INFO:pyemd2:main.py:127:handleKline:185189: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}
127.0.0.1 - - [07/Feb/2023 00:30:00] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=10571 

self.closeSec=1675700999, self.tradeDate='20230207', self.openTime='002000', self.closeTime='002959', self.symbol='BTCUSDT', self.open='23127.2', self.close='23075.6'
2023-02-07 00:30:00,998:INFO:pyemd2:main.py:125:handleKline:185189: self.closeSec=1675700999, self.tradeDate='20230207', self.openTime='002000', self.closeTime='002959',self.symbol='BTCUSDT',self.open='23127.2', self.close='23075.6'
2023-02-07 00:30:01,022:INFO:pyemd2:main.py:126:handleKline:185189: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17422  20230206   234000    234959  1675698599  22790.6  22818.6
17423  20230206   235000    235959  1675699199    22820  23044.1
17424  20230207   000000    000959  1675699799  23040.5  23073.4
17425  20230207   001000    001959  1675700399  23073.4  23127.3
17426  20230207   002000    002959  1675700999  23127.2  23075.6
2023-02-07 00:30:01,022:INFO:pyemd2:main.py:127:handleKline:185189: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}


## /root/FIL/strategy/similarity/log.txt ----- -----

12240  20230207   000000    000959  1675699799  23040.5  23073.4
2023-02-07 00:10:01,546:INFO:testStrategy:main.py:103:handleKline:185174: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False, 'isCorr': False}
127.0.0.1 - - [07/Feb/2023 00:20:00] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=10570 

self.closeSec=1675700399, self.tradeDate='20230207', self.openTime='001000', self.closeTime='001959', self.symbol='BTCUSDT', self.open='23073.4', self.close='23127.3'
2023-02-07 00:20:00,650:INFO:testStrategy:main.py:101:handleKline:185174: self.closeSec=1675700399, self.tradeDate='20230207', self.openTime='001000', self.closeTime='001959',self.symbol='BTCUSDT',self.open='23073.4', self.close='23127.3'
2023-02-07 00:20:00,671:INFO:testStrategy:main.py:102:handleKline:185174: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12237  20230206   233000    233959  1675697999    22772  22790.6
12238  20230206   234000    234959  1675698599  22790.6  22818.6
12239  20230206   235000    235959  1675699199    22820  23044.1
12240  20230207   000000    000959  1675699799  23040.5  23073.4
12241  20230207   001000    001959  1675700399  23073.4  23127.3
2023-02-07 00:20:00,671:INFO:testStrategy:main.py:103:handleKline:185174: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False, 'isCorr': False}
127.0.0.1 - - [07/Feb/2023 00:30:00] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=10571 

self.closeSec=1675700999, self.tradeDate='20230207', self.openTime='002000', self.closeTime='002959', self.symbol='BTCUSDT', self.open='23127.2', self.close='23075.6'
2023-02-07 00:30:00,996:INFO:testStrategy:main.py:101:handleKline:185174: self.closeSec=1675700999, self.tradeDate='20230207', self.openTime='002000', self.closeTime='002959',self.symbol='BTCUSDT',self.open='23127.2', self.close='23075.6'
2023-02-07 00:30:01,018:INFO:testStrategy:main.py:102:handleKline:185174: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12238  20230206   234000    234959  1675698599  22790.6  22818.6
12239  20230206   235000    235959  1675699199    22820  23044.1
12240  20230207   000000    000959  1675699799  23040.5  23073.4
12241  20230207   001000    001959  1675700399  23073.4  23127.3
12242  20230207   002000    002959  1675700999  23127.2  23075.6
2023-02-07 00:30:01,018:INFO:testStrategy:main.py:103:handleKline:185174: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False, 'isCorr': False}


## /root/FIL/strategy/sr_min/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=0, self.total=1000000.0, self.flagDict['side']='', self.tradeCount=0, self.count=16572
self.closeSec=1675700999, self.tradeDate='20230207', self.openTime='002500', self.closeTime='002959', self.symbol='BTCUSDT', self.open=23100.9, self.close=23075.6, self.high=23127.5, self.low=23074.0, self.vol=2752.025, self.amt=63576462.3707 
127.0.0.1 - - [07/Feb/2023 00:30:00] "POST / HTTP/1.1" 200 -
2023-02-07 00:30:00,846:INFO:sr_min:main.py:172:handleKline:449472: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5761  20230207   000500    000959  ...         0.0        0.0       0
5762  20230207   001000    001459  ...         0.0        0.0       0
5763  20230207   001500    001959  ...         0.0        0.0       0
5764  20230207   002000    002459  ...         0.0        0.0       0
5765  20230207   002500    002959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-02-07 00:30:00,846:INFO:sr_min:main.py:175:handleKline:449472: self.closeSec=1675700999, self.tradeDate='20230207', self.openTime='002500', self.closeTime='002959',self.symbol='BTCUSDT',self.open=23100.9, self.close=23075.6, self.high=23127.5, self.low=23074.0, self.vol=2752.025, self.amt=63576462.3707, ukdf['pct'].iloc[-1]=-0.001091 , ukdf['amount'].iloc[-1]=63576462.3707, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5765, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': []}
type(curSign)=<class 'int'>, curSign=0, self.sign=0
127.0.0.1 - - [07/Feb/2023 00:35:00] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=0, self.total=1000000.0, self.flagDict['side']='', self.tradeCount=0, self.count=16573
self.closeSec=1675701299, self.tradeDate='20230207', self.openTime='003000', self.closeTime='003459', self.symbol='BTCUSDT', self.open=23074.1, self.close=23040.2, self.high=23090.0, self.low=23040.0, self.vol=3151.669, self.amt=72690898.1775 
2023-02-07 00:35:00,761:INFO:sr_min:main.py:172:handleKline:449472: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5762  20230207   001000    001459  ...         0.0        0.0       0
5763  20230207   001500    001959  ...         0.0        0.0       0
5764  20230207   002000    002459  ...         0.0        0.0       0
5765  20230207   002500    002959  ...         0.0        0.0       0
5766  20230207   003000    003459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-02-07 00:35:00,761:INFO:sr_min:main.py:175:handleKline:449472: self.closeSec=1675701299, self.tradeDate='20230207', self.openTime='003000', self.closeTime='003459',self.symbol='BTCUSDT',self.open=23074.1, self.close=23040.2, self.high=23090.0, self.low=23040.0, self.vol=3151.669, self.amt=72690898.1775, ukdf['pct'].iloc[-1]=-0.001534 , ukdf['amount'].iloc[-1]=72690898.1775, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5766, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': []}
type(curSign)=<class 'int'>, curSign=0, self.sign=0


## /root/FIL/strategy/s_rsrs/log.txt ----- -----

723  20230206   120000    155959  1675670399  ...    723  0.662380  0.457873     NaN
724  20230206   160000    195959  1675684799  ...    724  0.690053  0.573136     NaN

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '38.964', 'enterprice': '23700.1', 'countrevence': '0', 'unrealprofit': '-31863.98388575592', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '22882.31989822', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-9223372036854775808, self.sign=1
--handleKline--:  version='2.0.0', self.name='s_rsrs', self.symbol='BTCUSDT', interval='4h', intervalSec=14400, wid=25, thd=0.6, self.sign=1, self.total=922527.2457035999, self.flagDict['side']='buy', self.tradeCount=16, self.count=440
self.closeSec=1675699199, self.tradeDate='20230206', self.openTime='200000', self.closeTime='235959', self.symbol='BTCUSDT', self.open=22876.1, self.close=23044.1, self.high=23054.9, self.low=22735.0, self.vol=94648.26, self.amt=2164576633.9912 
2023-02-07 00:00:01,194:INFO:s_rsrs:main.py:141:handleKline:185271: self.closeSec=1675699199, self.tradeDate='20230206', self.openTime='200000', self.closeTime='235959',self.symbol='BTCUSDT',self.open=22876.1, self.close=23044.1, self.high=23054.9, self.low=22735.0, self.vol=94648.26, self.amt=2164576633.9912 
127.0.0.1 - - [07/Feb/2023 00:00:01] "POST / HTTP/1.1" 200 -
2023-02-07 00:00:01,240:INFO:s_rsrs:main.py:142:handleKline:185271: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime  ...        vol           amt       pct
721  20230206   040000    075959  ...  47187.259  1.081561e+09  0.001734
722  20230206   080000    115959  ...  41294.353  9.483247e+08 -0.001627
723  20230206   120000    155959  ...  59449.276  1.353709e+09 -0.000839
724  20230206   160000    195959  ...  48624.377  1.110397e+09  0.000162
725  20230206   200000    235959  ...  94648.260  2.164577e+09  0.007331

[5 rows x 11 columns]
2023-02-07 00:00:03,352:INFO:s_rsrs:main.py:151:handleKline:185271: df_s.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec  ...  index      beta    zscore  signal
721  20230206   040000    075959  1675641599  ...    721  0.718608  0.611415     1.0
722  20230206   080000    115959  1675655999  ...    722  0.764930  0.790011     1.0
723  20230206   120000    155959  1675670399  ...    723  0.662380  0.457873     NaN
724  20230206   160000    195959  1675684799  ...    724  0.690053  0.573136     NaN
725  20230206   200000    235959  1675699199  ...    725  0.728452  0.727701     1.0

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '38.964', 'enterprice': '23700.1', 'countrevence': '0', 'unrealprofit': '-25578.41233342584', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '23043.63730794', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=1, self.sign=1


