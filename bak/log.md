# 20230126 08:16:01

## /root/FIL/strategy/amihud/log.txt ----- -----

127.0.0.1 - - [26/Jan/2023 08:10:01] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=993672.4896432, self.flagDict['side']='sell', self.tradeCount=2, self.count=17210
self.closeSec=1674691799, self.tradeDate='20230126', self.openTime='080500', self.closeTime='080959', self.symbol='BTCUSDT', self.open=23134.7, self.close=23096.7, self.high=23144.6, self.low=23072.0, self.vol=1957.348, self.amt=45241025.024 
2023-01-26 08:10:01,761:INFO:amihud:main.py:172:handleKline:200676: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5853  20230126   074500    074959  ...         0.0        0.0       0
5854  20230126   075000    075459  ...         0.0        0.0       0
5855  20230126   075500    075959  ...         0.0        0.0       0
5856  20230126   080000    080459  ...         0.0        0.0       0
5857  20230126   080500    080959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-01-26 08:10:01,761:INFO:amihud:main.py:175:handleKline:200676: self.closeSec=1674691799, self.tradeDate='20230126', self.openTime='080500', self.closeTime='080959',self.symbol='BTCUSDT',self.open=23134.7, self.close=23096.7, self.high=23144.6, self.low=23072.0, self.vol=1957.348, self.amt=45241025.024, ukdf['pct'].iloc[-1]=-0.001643 , ukdf['amount'].iloc[-1]=45241025.024, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5857, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '60.176', 'enterprice': '16529.3', 'countrevence': '0', 'unrealprofit': '-395398.76029622848', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '23100.00526948', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1
--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=993672.4896432, self.flagDict['side']='sell', self.tradeCount=2, self.count=17211
self.closeSec=1674692099, self.tradeDate='20230126', self.openTime='081000', self.closeTime='081459', self.symbol='BTCUSDT', self.open=23096.8, self.close=23096.3, self.high=23128.0, self.low=23092.2, self.vol=933.43, self.amt=21569684.755 
127.0.0.1 - - [26/Jan/2023 08:15:00] "POST / HTTP/1.1" 200 -
2023-01-26 08:15:00,727:INFO:amihud:main.py:172:handleKline:200676: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5854  20230126   075000    075459  ...         0.0        0.0       0
5855  20230126   075500    075959  ...         0.0        0.0       0
5856  20230126   080000    080459  ...         0.0        0.0       0
5857  20230126   080500    080959  ...         0.0        0.0       0
5858  20230126   081000    081459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-01-26 08:15:00,729:INFO:amihud:main.py:175:handleKline:200676: self.closeSec=1674692099, self.tradeDate='20230126', self.openTime='081000', self.closeTime='081459',self.symbol='BTCUSDT',self.open=23096.8, self.close=23096.3, self.high=23128.0, self.low=23092.2, self.vol=933.43, self.amt=21569684.755, ukdf['pct'].iloc[-1]=-1.7e-05 , ukdf['amount'].iloc[-1]=21569684.755, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5858, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '60.176', 'enterprice': '16529.3', 'countrevence': '0', 'unrealprofit': '-395329.27645668704', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '23098.85059254', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1


## /root/FIL/strategy/factorcheck/log.txt ----- -----

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=253, self.factor=0.4535673976759502, self.count=17776 

self.closeSec=1674691799, self.tradeDate='20230126', self.openTime='080500', self.closeTime='080959', self.symbol='BTCUSDT', self.open=23134.7, self.close=23096.7, self.high=23144.6, self.low=23072.0 
2023-01-26 08:10:01,659:INFO:factorcheck2:main.py:126:handleKline:185239: self.closeSec=1674691799, self.tradeDate='20230126', self.openTime='080500', self.closeTime='080959',self.symbol='BTCUSDT',self.open=23134.7, self.close=23096.7, self.high=23144.6, self.low=23072.0   
2023-01-26 08:10:01,736:INFO:factorcheck2:main.py:127:handleKline:185239: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1533  20230126   074500    074959  1674690599  ...  23119.8 -0.003534   1533    3
1534  20230126   075000    075459  1674690899  ...  23089.4  0.000502   1534    4
1535  20230126   075500    075959  1674691199  ...  23028.8 -0.003212   1535    5
1536  20230126   080000    080459  1674691499  ...  23060.5  0.003257   1536    0
1537  20230126   080500    080959  1674691799  ...  23072.0 -0.001643   1537    1

[5 rows x 11 columns]
2023-01-26 08:10:01,736:INFO:factorcheck2:main.py:128:handleKline:185239: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=253, self.factor=0.4535673976759502, self.count=17777 

self.closeSec=1674692099, self.tradeDate='20230126', self.openTime='081000', self.closeTime='081459', self.symbol='BTCUSDT', self.open=23096.8, self.close=23096.3, self.high=23128.0, self.low=23092.2 
127.0.0.1 - - [26/Jan/2023 08:15:00] "POST / HTTP/1.1" 200 -
2023-01-26 08:15:00,694:INFO:factorcheck2:main.py:126:handleKline:185239: self.closeSec=1674692099, self.tradeDate='20230126', self.openTime='081000', self.closeTime='081459',self.symbol='BTCUSDT',self.open=23096.8, self.close=23096.3, self.high=23128.0, self.low=23092.2   
2023-01-26 08:15:00,714:INFO:factorcheck2:main.py:127:handleKline:185239: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1534  20230126   075000    075459  1674690899  ...  23089.4  0.000502   1534    4
1535  20230126   075500    075959  1674691199  ...  23028.8 -0.003212   1535    5
1536  20230126   080000    080459  1674691499  ...  23060.5  0.003257   1536    0
1537  20230126   080500    080959  1674691799  ...  23072.0 -0.001643   1537    1
1538  20230126   081000    081459  1674692099  ...  23092.2 -0.000017   1538    2

[5 rows x 11 columns]
2023-01-26 08:15:00,714:INFO:factorcheck2:main.py:128:handleKline:185239: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}


## /root/FIL/strategy/logic/log.txt ----- -----

536     0  0.557893  0.442107       1  ...  1.026896   1.0  0.0000  1.130418
537     0  0.705175  0.294825       0  ...  1.018300   1.0  0.0000  1.120956
538     0  0.552777  0.447223       0  ...  0.998196   1.0  0.0000  1.098825
539     1  0.446326  0.553674       1  ...  0.989582  -1.0 -0.0016  1.106548
540     0  0.566658  0.433342       0  ...  0.986478   1.0 -0.0016  1.104847

[5 rows x 10 columns]
2023-01-26 08:00:18,403:INFO:logic:main.py:478:getModel:885513: df_panel.iloc[-5:,:] :
    pred    prob_0    prob_1  actual  ...       nav  sign   cost_        bm
45     0  0.557938  0.442062       1  ...  1.026896   1.0  0.0000  1.134462
46     0  0.704793  0.295207       0  ...  1.018300   1.0  0.0000  1.122946
47     0  0.552687  0.447313       0  ...  0.998196   1.0  0.0000  1.101405
48     1  0.446326  0.553674       1  ...  0.989582  -1.0 -0.0016  1.106548
49     0  0.566658  0.433342       0  ...  0.986478   1.0 -0.0016  1.104847

[5 rows x 10 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '31.625', 'enterprice': '23109', 'countrevence': '0', 'unrealprofit': '923.45', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '23079.8', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
handlebackTrade > queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '31.625', 'enterprice': '23109', 'countrevence': '0', 'unrealprofit': '923.45', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '23079.8', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
2023-01-26 08:00:24,656:INFO:logic:main.py:500:queryContractAssets:885513: queryContractAssets: assets=ContractAssetReturn{'result': [ContractAsset{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'asset': 'USDT', 'free': '732776.7975169', 'total': '732776.7975169', 'margin': '0', 'unreal': '0', 'type': 'AssetType_ucontract'}]}
2023-01-26 08:00:24,818:DEBUG:logic:main.py:571:openBuy:885513: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': True, 'isCloseBuy': False, 'isCloseSell': False, 'isOpen': True, 'isClose': False, 'isTrig': False}
2023-01-26 08:00:24,819:INFO:logic:main.py:572:openBuy:885513: ret = self.client.insertMarketUOrder("simulator", "BTCUSDT", 31.682, "buy"), ret=InsertOrderReturn{'result': 'success', 'clientorderid': '41610F1674691224818I0L64'}
2023-01-26 08:00:24,836:INFO:logic:main.py:494:insertFactor:885513: curDateTime:1260800, name:logic, symbol:BTCUSDT, tradeDate:20230126, closeTime:075959, close:23059.6, sign:1, total:732776.7975169, side:buy  
127.0.0.1 - - [26/Jan/2023 08:00:24] "POST / HTTP/1.1" 200 -
2023-01-26 08:00:24,836:INFO:logic:main.py:661:handleOrderNew:885513: handleOrderNew: data=OrderType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'clientorderid': '41609F1674691219590I0L64', 'symbol': 'BTCUSDT', 'gatewayorderid': 1674691219689105, 'quantity': '31.625', 'price': '23080.2', 'stopprice': '0', 'ordertype': '', 'side': 'BUY', 'status': 'FILLED', 'positionside': 'LONG', 'createtime': 1674691218886, 'updatetime': 1674691219689, 'tradetype': 'usdt', 'selfid': 41609, 'filltrades': [TradeType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'tradeid': 1674691219689, 'clientorderid': '41609F1674691219590I0L64', 'price': '23080.2', 'quantity': '31.625', 'commission': '729.911325', 'commissionasset': 'USDT', 'tradetime': 1674691219689, 'tradetype': 'usdt', 'gatetype': 'simulator', 'handletime': 1674691219689}], 'gatetype': 'simulator', 'handletime': 0}
127.0.0.1 - - [26/Jan/2023 08:00:24] "POST / HTTP/1.1" 200 -
2023-01-26 08:00:24,837:INFO:logic:main.py:664:handleOrderFilled:885513: handleOrderFilled: data=OrderType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'clientorderid': '41609F1674691219590I0L64', 'symbol': 'BTCUSDT', 'gatewayorderid': 1674691219689105, 'quantity': '31.625', 'price': '23080.2', 'stopprice': '0', 'ordertype': '', 'side': 'BUY', 'status': 'FILLED', 'positionside': 'LONG', 'createtime': 1674691218886, 'updatetime': 1674691219689, 'tradetype': 'usdt', 'selfid': 41609, 'filltrades': [TradeType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'tradeid': 1674691219689, 'clientorderid': '41609F1674691219590I0L64', 'price': '23080.2', 'quantity': '31.625', 'commission': '729.911325', 'commissionasset': 'USDT', 'tradetime': 1674691219689, 'tradetype': 'usdt', 'gatetype': 'simulator', 'handletime': 1674691219689}], 'gatetype': 'simulator', 'handletime': 0}
127.0.0.1 - - [26/Jan/2023 08:00:24] "POST / HTTP/1.1" 200 -
2023-01-26 08:00:24,959:INFO:logic:main.py:661:handleOrderNew:885513: handleOrderNew: data=OrderType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'clientorderid': '41610F1674691224818I0L64', 'symbol': 'BTCUSDT', 'gatewayorderid': 1674691224921998, 'quantity': '31.682', 'price': '23079.5', 'stopprice': '0', 'ordertype': '', 'side': 'BUY', 'status': 'FILLED', 'positionside': 'LONG', 'createtime': 1674691224666, 'updatetime': 1674691224921, 'tradetype': 'usdt', 'selfid': 41610, 'filltrades': [TradeType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'tradeid': 1674691224921, 'clientorderid': '41610F1674691224818I0L64', 'price': '23079.5', 'quantity': '31.682', 'commission': '731.204719', 'commissionasset': 'USDT', 'tradetime': 1674691224921, 'tradetype': 'usdt', 'gatetype': 'simulator', 'handletime': 1674691224921}], 'gatetype': 'simulator', 'handletime': 0}
2023-01-26 08:00:25,081:INFO:logic:main.py:664:handleOrderFilled:885513: handleOrderFilled: data=OrderType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'clientorderid': '41610F1674691224818I0L64', 'symbol': 'BTCUSDT', 'gatewayorderid': 1674691224921998, 'quantity': '31.682', 'price': '23079.5', 'stopprice': '0', 'ordertype': '', 'side': 'BUY', 'status': 'FILLED', 'positionside': 'LONG', 'createtime': 1674691224666, 'updatetime': 1674691224921, 'tradetype': 'usdt', 'selfid': 41610, 'filltrades': [TradeType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'tradeid': 1674691224921, 'clientorderid': '41610F1674691224818I0L64', 'price': '23079.5', 'quantity': '31.682', 'commission': '731.204719', 'commissionasset': 'USDT', 'tradetime': 1674691224921, 'tradetype': 'usdt', 'gatetype': 'simulator', 'handletime': 1674691224921}], 'gatetype': 'simulator', 'handletime': 0}
127.0.0.1 - - [26/Jan/2023 08:00:25] "POST / HTTP/1.1" 200 -


## /root/FIL/strategy/modifiedmom/log.txt ----- -----

622  20230126   074000    074959  1674690599  23131.7  23122.3 -0.000519
2023-01-26 07:50:00,837:INFO:modifiedmom:main.py:146:handleKline:185213: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False}
127.0.0.1 - - [26/Jan/2023 08:00:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=8887 

self.closeSec=1674691199, self.tradeDate='20230126', self.openTime='075000', self.closeTime='075959', self.symbol='BTCUSDT', self.open='23122.3', self.close='23059.6'
2023-01-26 08:00:01,834:INFO:modifiedmom:main.py:144:handleKline:185213: self.closeSec=1674691199, self.tradeDate='20230126', self.openTime='075000', self.closeTime='075959',self.symbol='BTCUSDT',self.open='23122.3', self.close='23059.6'
2023-01-26 08:00:01,859:INFO:modifiedmom:main.py:145:handleKline:185213: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
619  20230126   071000    071959  1674688799    23010  23004.6 -0.000230
620  20230126   072000    072959  1674689399  23003.1  23095.1  0.003934
621  20230126   073000    073959  1674689999  23094.3  23134.3  0.001697
622  20230126   074000    074959  1674690599  23131.7  23122.3 -0.000519
623  20230126   075000    075959  1674691199  23122.3  23059.6 -0.002712
2023-01-26 08:00:01,859:INFO:modifiedmom:main.py:146:handleKline:185213: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False}
127.0.0.1 - - [26/Jan/2023 08:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=8888 

self.closeSec=1674691799, self.tradeDate='20230126', self.openTime='080000', self.closeTime='080959', self.symbol='BTCUSDT', self.open='23060.6', self.close='23096.7'
2023-01-26 08:10:01,780:INFO:modifiedmom:main.py:144:handleKline:185213: self.closeSec=1674691799, self.tradeDate='20230126', self.openTime='080000', self.closeTime='080959',self.symbol='BTCUSDT',self.open='23060.6', self.close='23096.7'
2023-01-26 08:10:01,806:INFO:modifiedmom:main.py:145:handleKline:185213: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
620  20230126   072000    072959  1674689399  23003.1  23095.1  0.003934
621  20230126   073000    073959  1674689999  23094.3  23134.3  0.001697
622  20230126   074000    074959  1674690599  23131.7  23122.3 -0.000519
623  20230126   075000    075959  1674691199  23122.3  23059.6 -0.002712
624  20230126   080000    080959  1674691799  23060.6  23096.7  0.001609
2023-01-26 08:10:01,807:INFO:modifiedmom:main.py:146:handleKline:185213: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False}


## /root/FIL/strategy/pyemd/log.txt ----- -----

17470  20230126   074000    074959  1674690599  23131.7  23122.3
2023-01-26 07:50:00,853:INFO:pyemd2:main.py:127:handleKline:185189: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}
127.0.0.1 - - [26/Jan/2023 08:00:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=8888 

self.closeSec=1674691199, self.tradeDate='20230126', self.openTime='075000', self.closeTime='075959', self.symbol='BTCUSDT', self.open='23122.3', self.close='23059.6'
2023-01-26 08:00:01,841:INFO:pyemd2:main.py:125:handleKline:185189: self.closeSec=1674691199, self.tradeDate='20230126', self.openTime='075000', self.closeTime='075959',self.symbol='BTCUSDT',self.open='23122.3', self.close='23059.6'
2023-01-26 08:00:01,870:INFO:pyemd2:main.py:126:handleKline:185189: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17467  20230126   071000    071959  1674688799    23010  23004.6
17468  20230126   072000    072959  1674689399  23003.1  23095.1
17469  20230126   073000    073959  1674689999  23094.3  23134.3
17470  20230126   074000    074959  1674690599  23131.7  23122.3
17471  20230126   075000    075959  1674691199  23122.3  23059.6
2023-01-26 08:00:01,870:INFO:pyemd2:main.py:127:handleKline:185189: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}
127.0.0.1 - - [26/Jan/2023 08:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=8889 

self.closeSec=1674691799, self.tradeDate='20230126', self.openTime='080000', self.closeTime='080959', self.symbol='BTCUSDT', self.open='23060.6', self.close='23096.7'
2023-01-26 08:10:01,792:INFO:pyemd2:main.py:125:handleKline:185189: self.closeSec=1674691799, self.tradeDate='20230126', self.openTime='080000', self.closeTime='080959',self.symbol='BTCUSDT',self.open='23060.6', self.close='23096.7'
2023-01-26 08:10:01,797:INFO:pyemd2:main.py:126:handleKline:185189: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17468  20230126   072000    072959  1674689399  23003.1  23095.1
17469  20230126   073000    073959  1674689999  23094.3  23134.3
17470  20230126   074000    074959  1674690599  23131.7  23122.3
17471  20230126   075000    075959  1674691199  23122.3  23059.6
17472  20230126   080000    080959  1674691799  23060.6  23096.7
2023-01-26 08:10:01,797:INFO:pyemd2:main.py:127:handleKline:185189: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}


## /root/FIL/strategy/similarity/log.txt ----- -----

12142  20230126   074000    074959  1674690599  23131.7  23122.3
2023-01-26 07:50:00,847:INFO:testStrategy:main.py:103:handleKline:185174: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}
127.0.0.1 - - [26/Jan/2023 08:00:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=8888 

self.closeSec=1674691199, self.tradeDate='20230126', self.openTime='075000', self.closeTime='075959', self.symbol='BTCUSDT', self.open='23122.3', self.close='23059.6'
2023-01-26 08:00:01,823:INFO:testStrategy:main.py:101:handleKline:185174: self.closeSec=1674691199, self.tradeDate='20230126', self.openTime='075000', self.closeTime='075959',self.symbol='BTCUSDT',self.open='23122.3', self.close='23059.6'
2023-01-26 08:00:01,867:INFO:testStrategy:main.py:102:handleKline:185174: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12139  20230126   071000    071959  1674688799    23010  23004.6
12140  20230126   072000    072959  1674689399  23003.1  23095.1
12141  20230126   073000    073959  1674689999  23094.3  23134.3
12142  20230126   074000    074959  1674690599  23131.7  23122.3
12143  20230126   075000    075959  1674691199  23122.3  23059.6
2023-01-26 08:00:01,867:INFO:testStrategy:main.py:103:handleKline:185174: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}
127.0.0.1 - - [26/Jan/2023 08:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=8889 

self.closeSec=1674691799, self.tradeDate='20230126', self.openTime='080000', self.closeTime='080959', self.symbol='BTCUSDT', self.open='23060.6', self.close='23096.7'
2023-01-26 08:10:01,789:INFO:testStrategy:main.py:101:handleKline:185174: self.closeSec=1674691799, self.tradeDate='20230126', self.openTime='080000', self.closeTime='080959',self.symbol='BTCUSDT',self.open='23060.6', self.close='23096.7'
2023-01-26 08:10:01,808:INFO:testStrategy:main.py:102:handleKline:185174: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12140  20230126   072000    072959  1674689399  23003.1  23095.1
12141  20230126   073000    073959  1674689999  23094.3  23134.3
12142  20230126   074000    074959  1674690599  23131.7  23122.3
12143  20230126   075000    075959  1674691199  23122.3  23059.6
12144  20230126   080000    080959  1674691799  23060.6  23096.7
2023-01-26 08:10:01,808:INFO:testStrategy:main.py:103:handleKline:185174: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}


## /root/FIL/strategy/sr_min/log.txt ----- -----

127.0.0.1 - - [26/Jan/2023 08:10:01] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=0, self.total=1000000.0, self.flagDict['side']='', self.tradeCount=0, self.count=13208
self.closeSec=1674691799, self.tradeDate='20230126', self.openTime='080500', self.closeTime='080959', self.symbol='BTCUSDT', self.open=23134.7, self.close=23096.7, self.high=23144.6, self.low=23072.0, self.vol=1957.348, self.amt=45241025.024 
2023-01-26 08:10:01,743:INFO:sr_min:main.py:172:handleKline:449472: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5853  20230126   074500    074959  ...         0.0        0.0       0
5854  20230126   075000    075459  ...         0.0        0.0       0
5855  20230126   075500    075959  ...         0.0        0.0       0
5856  20230126   080000    080459  ...         0.0        0.0       0
5857  20230126   080500    080959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-01-26 08:10:01,743:INFO:sr_min:main.py:175:handleKline:449472: self.closeSec=1674691799, self.tradeDate='20230126', self.openTime='080500', self.closeTime='080959',self.symbol='BTCUSDT',self.open=23134.7, self.close=23096.7, self.high=23144.6, self.low=23072.0, self.vol=1957.348, self.amt=45241025.024, ukdf['pct'].iloc[-1]=-0.001643 , ukdf['amount'].iloc[-1]=45241025.024, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5857, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': []}
type(curSign)=<class 'int'>, curSign=0, self.sign=0
127.0.0.1 - - [26/Jan/2023 08:15:00] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=0, self.total=1000000.0, self.flagDict['side']='', self.tradeCount=0, self.count=13209
self.closeSec=1674692099, self.tradeDate='20230126', self.openTime='081000', self.closeTime='081459', self.symbol='BTCUSDT', self.open=23096.8, self.close=23096.3, self.high=23128.0, self.low=23092.2, self.vol=933.43, self.amt=21569684.755 
2023-01-26 08:15:00,741:INFO:sr_min:main.py:172:handleKline:449472: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5854  20230126   075000    075459  ...         0.0        0.0       0
5855  20230126   075500    075959  ...         0.0        0.0       0
5856  20230126   080000    080459  ...         0.0        0.0       0
5857  20230126   080500    080959  ...         0.0        0.0       0
5858  20230126   081000    081459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-01-26 08:15:00,742:INFO:sr_min:main.py:175:handleKline:449472: self.closeSec=1674692099, self.tradeDate='20230126', self.openTime='081000', self.closeTime='081459',self.symbol='BTCUSDT',self.open=23096.8, self.close=23096.3, self.high=23128.0, self.low=23092.2, self.vol=933.43, self.amt=21569684.755, ukdf['pct'].iloc[-1]=-1.7e-05 , ukdf['amount'].iloc[-1]=21569684.755, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5858, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': []}
type(curSign)=<class 'int'>, curSign=0, self.sign=0


## /root/FIL/strategy/s_rsrs/log.txt ----- -----

719  20230125   200000    235959  1674662399  ...    719  0.256658 -1.252734    -1.0
720  20230126   000000    035959  1674676799  ...    720  0.239021 -1.262655    -1.0

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '41.738', 'enterprice': '22927.7', 'countrevence': '0', 'unrealprofit': '7529.5352', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '22747.3', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-1, self.sign=-1
127.0.0.1 - - [26/Jan/2023 08:00:01] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='s_rsrs', self.symbol='BTCUSDT', interval='4h', intervalSec=14400, wid=25, thd=0.6, self.sign=-1, self.total=955999.3862573999, self.flagDict['side']='sell', self.tradeCount=15, self.count=370
self.closeSec=1674691199, self.tradeDate='20230126', self.openTime='040000', self.closeTime='075959', self.symbol='BTCUSDT', self.open=22743.4, self.close=23059.6, self.high=23837.4, self.low=22743.4, self.vol=309662.086, self.amt=7186401947.46093 
2023-01-26 08:00:01,720:INFO:s_rsrs:main.py:141:handleKline:185271: self.closeSec=1674691199, self.tradeDate='20230126', self.openTime='040000', self.closeTime='075959',self.symbol='BTCUSDT',self.open=22743.4, self.close=23059.6, self.high=23837.4, self.low=22743.4, self.vol=309662.086, self.amt=7186401947.46093 
2023-01-26 08:00:01,763:INFO:s_rsrs:main.py:142:handleKline:185271: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime  ...         vol           amt       pct
717  20230125   120000    155959  ...   34838.121  7.901792e+08  0.002778
718  20230125   160000    195959  ...   57559.621  1.301308e+09 -0.004757
719  20230125   200000    235959  ...  127913.984  2.885108e+09 -0.001000
720  20230126   000000    035959  ...   64912.437  1.469489e+09  0.007535
721  20230126   040000    075959  ...  309662.086  7.186402e+09  0.013903

[5 rows x 11 columns]
2023-01-26 08:00:03,079:INFO:s_rsrs:main.py:151:handleKline:185271: df_s.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec  ...  index      beta    zscore  signal
717  20230125   120000    155959  1674633599  ...    717  0.145590 -1.574237    -1.0
718  20230125   160000    195959  1674647999  ...    718  0.149681 -1.525917    -1.0
719  20230125   200000    235959  1674662399  ...    719  0.256658 -1.252734    -1.0
720  20230126   000000    035959  1674676799  ...    720  0.239021 -1.262655    -1.0
721  20230126   040000    075959  1674691199  ...    721  0.164732 -1.395258    -1.0

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '41.738', 'enterprice': '22927.7', 'countrevence': '0', 'unrealprofit': '-5592.892', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '23061.7', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-1, self.sign=-1


