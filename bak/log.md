# 20230118 00:16:02

## /root/FIL/strategy/amihud/log.txt ----- -----

127.0.0.1 - - [18/Jan/2023 00:10:01] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=993672.4896432, self.flagDict['side']='sell', self.tradeCount=2, self.count=14810
self.closeSec=1673971799, self.tradeDate='20230118', self.openTime='000500', self.closeTime='000959', self.symbol='BTCUSDT', self.open=21203.9, self.close=21144.9, self.high=21205.4, self.low=21106.3, self.vol=2472.416, self.amt=52268642.3006 
2023-01-18 00:10:01,505:INFO:amihud:main.py:172:handleKline:200676: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5757  20230117   234500    234959  ...         0.0        0.0       0
5758  20230117   235000    235459  ...         0.0        0.0       0
5759  20230117   235500    235959  ...         0.0        0.0       0
5760  20230118   000000    000459  ...         0.0        0.0       0
5761  20230118   000500    000959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-01-18 00:10:01,505:INFO:amihud:main.py:175:handleKline:200676: self.closeSec=1673971799, self.tradeDate='20230118', self.openTime='000500', self.closeTime='000959',self.symbol='BTCUSDT',self.open=21203.9, self.close=21144.9, self.high=21205.4, self.low=21106.3, self.vol=2472.416, self.amt=52268642.3006, ukdf['pct'].iloc[-1]=-0.002858 , ukdf['amount'].iloc[-1]=52268642.3006, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5761, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '60.176', 'enterprice': '16529.3', 'countrevence': '0', 'unrealprofit': '-277820.5568', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '21146.1', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1
--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=993672.4896432, self.flagDict['side']='sell', self.tradeCount=2, self.count=14811
self.closeSec=1673972099, self.tradeDate='20230118', self.openTime='001000', self.closeTime='001459', self.symbol='BTCUSDT', self.open=21145.9, self.close=21107.0, self.high=21146.3, self.low=21082.3, self.vol=2859.065, self.amt=60338770.4402 
127.0.0.1 - - [18/Jan/2023 00:15:00] "POST / HTTP/1.1" 200 -
2023-01-18 00:15:00,785:INFO:amihud:main.py:172:handleKline:200676: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5758  20230117   235000    235459  ...         0.0        0.0       0
5759  20230117   235500    235959  ...         0.0        0.0       0
5760  20230118   000000    000459  ...         0.0        0.0       0
5761  20230118   000500    000959  ...         0.0        0.0       0
5762  20230118   001000    001459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-01-18 00:15:00,786:INFO:amihud:main.py:175:handleKline:200676: self.closeSec=1673972099, self.tradeDate='20230118', self.openTime='001000', self.closeTime='001459',self.symbol='BTCUSDT',self.open=21145.9, self.close=21107.0, self.high=21146.3, self.low=21082.3, self.vol=2859.065, self.amt=60338770.4402, ukdf['pct'].iloc[-1]=-0.001792 , ukdf['amount'].iloc[-1]=60338770.4402, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5762, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '60.176', 'enterprice': '16529.3', 'countrevence': '0', 'unrealprofit': '-275485.728', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '21107.3', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1


## /root/FIL/strategy/factorcheck/log.txt ----- -----


self.closeSec=1673971799, self.tradeDate='20230118', self.openTime='000500', self.closeTime='000959', self.symbol='BTCUSDT', self.open=21203.9, self.close=21144.9, self.high=21205.4, self.low=21106.3 
2023-01-18 00:10:01,440:INFO:factorcheck2:main.py:126:handleKline:185239: self.closeSec=1673971799, self.tradeDate='20230118', self.openTime='000500', self.closeTime='000959',self.symbol='BTCUSDT',self.open=21203.9, self.close=21144.9, self.high=21205.4, self.low=21106.3   
127.0.0.1 - - [18/Jan/2023 00:10:01] "POST / HTTP/1.1" 200 -
2023-01-18 00:10:01,486:INFO:factorcheck2:main.py:127:handleKline:185239: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1437  20230117   234500    234959  1673970599  ...  21068.3  0.001506   1725    3
1438  20230117   235000    235459  1673970899  ...  21107.1 -0.000052   1726    4
1439  20230117   235500    235959  1673971199  ...  21117.1  0.001078   1727    5
1440  20230118   000000    000459  1673971499  ...  21136.3  0.001407   1440    0
1441  20230118   000500    000959  1673971799  ...  21106.3 -0.002858   1441    1

[5 rows x 11 columns]
2023-01-18 00:10:01,486:INFO:factorcheck2:main.py:128:handleKline:185239: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=479, self.factor=0.430356056594225, self.count=15377 

self.closeSec=1673972099, self.tradeDate='20230118', self.openTime='001000', self.closeTime='001459', self.symbol='BTCUSDT', self.open=21145.9, self.close=21107.0, self.high=21146.3, self.low=21082.3 
2023-01-18 00:15:00,665:INFO:factorcheck2:main.py:126:handleKline:185239: self.closeSec=1673972099, self.tradeDate='20230118', self.openTime='001000', self.closeTime='001459',self.symbol='BTCUSDT',self.open=21145.9, self.close=21107.0, self.high=21146.3, self.low=21082.3   
127.0.0.1 - - [18/Jan/2023 00:15:00] "POST / HTTP/1.1" 200 -
2023-01-18 00:15:00,743:INFO:factorcheck2:main.py:127:handleKline:185239: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1438  20230117   235000    235459  1673970899  ...  21107.1 -0.000052   1726    4
1439  20230117   235500    235959  1673971199  ...  21117.1  0.001078   1727    5
1440  20230118   000000    000459  1673971499  ...  21136.3  0.001407   1440    0
1441  20230118   000500    000959  1673971799  ...  21106.3 -0.002858   1441    1
1442  20230118   001000    001459  1673972099  ...  21082.3 -0.001792   1442    2

[5 rows x 11 columns]
2023-01-18 00:15:00,743:INFO:factorcheck2:main.py:128:handleKline:185239: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}


## /root/FIL/strategy/logic/log.txt ----- -----

2023-01-18 00:00:36,118:DEBUG:logic:main.py:456:getModel:726423: df_s.iloc[-5:,:] :
          date closeTime     open  ...    alpha58   alpha67   alpha72
5802  20230117    212959  21254.0  ...  54.166667  0.555644  0.400427
5803  20230117    215959  21245.9  ...  53.750000  0.552526  0.400202
5804  20230117    222959  21232.0  ...  54.166667  0.562713  0.402578
5805  20230117    225959  21276.6  ...  54.166667  0.562085  0.405010
5806  20230117    232959  21283.4  ...  53.750000  0.559855  0.408027

[5 rows x 33 columns]
0.5367647058823529
acc is : 0.5367647058823529
2023-01-18 00:00:36,252:INFO:logic:main.py:461:getModel:726423: df_pred.iloc[-5:,:] :
     pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
539     0  0.512563  0.487437       0  ...  1.054577   1.0    0.0  1.264880
540     0  0.505160  0.494840       1  ...  1.057264   1.0    0.0  1.268103
541     0  0.519138  0.480862       0  ...  1.057135   1.0    0.0  1.267948
542     0  0.502302  0.497698       0  ...  1.056683   1.0    0.0  1.267406
543     0  0.503166  0.496834       0  ...  1.051786   1.0    0.0  1.261532

[5 rows x 10 columns]
2023-01-18 00:00:36,292:INFO:logic:main.py:471:getModel:726423: df_panel.iloc[-5:,:] :
    pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
45     0  0.513324  0.486676       0  ...  1.054577   1.0    0.0  1.264458
46     0  0.505241  0.494759       1  ...  1.057264   1.0    0.0  1.268602
47     0  0.519055  0.480945       0  ...  1.057135   1.0    0.0  1.268447
48     0  0.502377  0.497623       0  ...  1.056683   1.0    0.0  1.266825
49     0  0.503166  0.496834       0  ...  1.051786   1.0    0.0  1.261532

[5 rows x 10 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': []}


## /root/FIL/strategy/modifiedmom/log.txt ----- -----

2023-01-18 00:00:01,522:INFO:modifiedmom:main.py:145:handleKline:185213: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
571  20230117   231000    231959  1673968799  21315.7  21339.1  0.001098
572  20230117   232000    232959  1673969399  21338.4  21274.3 -0.003037
573  20230117   233000    233959  1673969999  21271.7    21184 -0.004245
574  20230117   234000    234959  1673970599  21184.3    21154 -0.001416
575  20230117   235000    235959  1673971199  21151.6  21175.7  0.001026
2023-01-18 00:00:01,522:INFO:modifiedmom:main.py:146:handleKline:185213: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True}
closeBuy: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '43.834', 'enterprice': '21136.6', 'countrevence': '0', 'unrealprofit': '1696.3758', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '21175.3', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
2023-01-18 00:00:02,279:INFO:modifiedmom:main.py:267:closeBuy:185213: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False}
2023-01-18 00:00:02,279:INFO:modifiedmom:main.py:268:closeBuy:185213: ret = self.client.insertMarketUOrder("simulator",  BTCUSDT, 43.834, sell ), ret=InsertOrderReturn{'result': 'success', 'clientorderid': '41542F1673971202278I0L59'}
2023-01-18 00:00:02,302:INFO:modifiedmom:main.py:206:insertFactor:185213: curDateTime:1180000, name:modifiedmom, symbol:BTCUSDT, tradeDate:20230117, closeTime:235959, close:21175.7, total:925575.2226756, mom:0.01316344332463859, thd:0.0, side:sell 
127.0.0.1 - - [18/Jan/2023 00:00:02] "POST / HTTP/1.1" 200 -
2023-01-18 00:00:02,682:INFO:modifiedmom:main.py:316:handleOrderNew:185213: handleOrderNew: data=OrderType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'clientorderid': '41542F1673971202278I0L59', 'symbol': 'BTCUSDT', 'gatewayorderid': 1673971202401720, 'quantity': '43.834', 'price': '21174.6', 'stopprice': '0', 'ordertype': '', 'side': 'SELL', 'status': 'FILLED', 'positionside': 'SHORT', 'createtime': 1673971201703, 'updatetime': 1673971202401, 'tradetype': 'usdt', 'selfid': 41542, 'filltrades': [TradeType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'tradeid': 1673971202401, 'clientorderid': '41542F1673971202278I0L59', 'price': '21174.6', 'quantity': '43.834', 'commission': '928.1674164', 'commissionasset': 'USDT', 'tradetime': 1673971202401, 'tradetype': 'usdt', 'gatetype': 'simulator', 'handletime': 1673971202401}], 'gatetype': 'simulator', 'handletime': 0}
2023-01-18 00:00:02,924:INFO:modifiedmom:main.py:319:handleOrderFilled:185213: handleOrderFilled: data=OrderType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'clientorderid': '41542F1673971202278I0L59', 'symbol': 'BTCUSDT', 'gatewayorderid': 1673971202401720, 'quantity': '43.834', 'price': '21174.6', 'stopprice': '0', 'ordertype': '', 'side': 'SELL', 'status': 'FILLED', 'positionside': 'SHORT', 'createtime': 1673971201703, 'updatetime': 1673971202401, 'tradetype': 'usdt', 'selfid': 41542, 'filltrades': [TradeType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'tradeid': 1673971202401, 'clientorderid': '41542F1673971202278I0L59', 'price': '21174.6', 'quantity': '43.834', 'commission': '928.1674164', 'commissionasset': 'USDT', 'tradetime': 1673971202401, 'tradetype': 'usdt', 'gatetype': 'simulator', 'handletime': 1673971202401}], 'gatetype': 'simulator', 'handletime': 0}
127.0.0.1 - - [18/Jan/2023 00:00:02] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=7688 

self.closeSec=1673971799, self.tradeDate='20230118', self.openTime='000000', self.closeTime='000959', self.symbol='BTCUSDT', self.open='21175.7', self.close='21144.9'
2023-01-18 00:10:01,555:INFO:modifiedmom:main.py:144:handleKline:185213: self.closeSec=1673971799, self.tradeDate='20230118', self.openTime='000000', self.closeTime='000959',self.symbol='BTCUSDT',self.open='21175.7', self.close='21144.9'
127.0.0.1 - - [18/Jan/2023 00:10:01] "POST / HTTP/1.1" 200 -
2023-01-18 00:10:01,574:INFO:modifiedmom:main.py:145:handleKline:185213: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
572  20230117   232000    232959  1673969399  21338.4  21274.3 -0.003037
573  20230117   233000    233959  1673969999  21271.7    21184 -0.004245
574  20230117   234000    234959  1673970599  21184.3    21154 -0.001416
575  20230117   235000    235959  1673971199  21151.6  21175.7  0.001026
576  20230118   000000    000959  1673971799  21175.7  21144.9 -0.001454
2023-01-18 00:10:01,574:INFO:modifiedmom:main.py:146:handleKline:185213: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False}


## /root/FIL/strategy/pyemd/log.txt ----- -----

2023-01-18 00:00:01,542:INFO:pyemd2:main.py:126:handleKline:185189: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17419  20230117   231000    231959  1673968799  21315.7  21339.1
17420  20230117   232000    232959  1673969399  21338.4  21274.3
17421  20230117   233000    233959  1673969999  21271.7    21184
17422  20230117   234000    234959  1673970599  21184.3    21154
17423  20230117   235000    235959  1673971199  21151.6  21175.7
2023-01-18 00:00:01,543:INFO:pyemd2:main.py:127:handleKline:185189: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': False, 'isOpen': True, 'isClose': False, 'isTrig': True}
closeBuy: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '44.892', 'enterprice': '21174.3', 'countrevence': '0', 'unrealprofit': '44.892', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '21175.3', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
2023-01-18 00:00:02,260:INFO:pyemd2:main.py:251:closeBuy:185189: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}
2023-01-18 00:00:02,260:INFO:pyemd2:main.py:252:closeBuy:185189: ret = self.client.insertMarketUOrder("simulator",  BTCUSDT, 44.892, sell ), ret=InsertOrderReturn{'result': 'success', 'clientorderid': '41541F1673971202258I0L57'}
2023-01-18 00:00:02,288:INFO:pyemd2:main.py:190:insertFactor:185189: curDateTime:1180000, name:pyemd2, symbol:BTCUSDT, tradeDate:20230117, closeTime:235959, close:21175.7, total:949606.1189244001, pct_pre:0.009458383588941688, thd:0.4361742103150139, side:sell 
2023-01-18 00:00:02,460:INFO:pyemd2:main.py:300:handleOrderNew:185189: handleOrderNew: data=OrderType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'clientorderid': '41541F1673971202258I0L57', 'symbol': 'BTCUSDT', 'gatewayorderid': 1673971202392050, 'quantity': '44.892', 'price': '21174.6', 'stopprice': '0', 'ordertype': '', 'side': 'SELL', 'status': 'FILLED', 'positionside': 'SHORT', 'createtime': 1673971201771, 'updatetime': 1673971202392, 'tradetype': 'usdt', 'selfid': 41541, 'filltrades': [TradeType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'tradeid': 1673971202392, 'clientorderid': '41541F1673971202258I0L57', 'price': '21174.6', 'quantity': '44.892', 'commission': '950.5701432', 'commissionasset': 'USDT', 'tradetime': 1673971202392, 'tradetype': 'usdt', 'gatetype': 'simulator', 'handletime': 1673971202392}], 'gatetype': 'simulator', 'handletime': 0}
127.0.0.1 - - [18/Jan/2023 00:00:02] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [18/Jan/2023 00:00:02] "POST / HTTP/1.1" 200 -
2023-01-18 00:00:02,657:INFO:pyemd2:main.py:303:handleOrderFilled:185189: handleOrderFilled: data=OrderType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'clientorderid': '41541F1673971202258I0L57', 'symbol': 'BTCUSDT', 'gatewayorderid': 1673971202392050, 'quantity': '44.892', 'price': '21174.6', 'stopprice': '0', 'ordertype': '', 'side': 'SELL', 'status': 'FILLED', 'positionside': 'SHORT', 'createtime': 1673971201771, 'updatetime': 1673971202392, 'tradetype': 'usdt', 'selfid': 41541, 'filltrades': [TradeType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'tradeid': 1673971202392, 'clientorderid': '41541F1673971202258I0L57', 'price': '21174.6', 'quantity': '44.892', 'commission': '950.5701432', 'commissionasset': 'USDT', 'tradetime': 1673971202392, 'tradetype': 'usdt', 'gatetype': 'simulator', 'handletime': 1673971202392}], 'gatetype': 'simulator', 'handletime': 0}
127.0.0.1 - - [18/Jan/2023 00:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=7689 

self.closeSec=1673971799, self.tradeDate='20230118', self.openTime='000000', self.closeTime='000959', self.symbol='BTCUSDT', self.open='21175.7', self.close='21144.9'
2023-01-18 00:10:01,585:INFO:pyemd2:main.py:125:handleKline:185189: self.closeSec=1673971799, self.tradeDate='20230118', self.openTime='000000', self.closeTime='000959',self.symbol='BTCUSDT',self.open='21175.7', self.close='21144.9'
2023-01-18 00:10:01,605:INFO:pyemd2:main.py:126:handleKline:185189: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17420  20230117   232000    232959  1673969399  21338.4  21274.3
17421  20230117   233000    233959  1673969999  21271.7    21184
17422  20230117   234000    234959  1673970599  21184.3    21154
17423  20230117   235000    235959  1673971199  21151.6  21175.7
17424  20230118   000000    000959  1673971799  21175.7  21144.9
2023-01-18 00:10:01,606:INFO:pyemd2:main.py:127:handleKline:185189: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}


## /root/FIL/strategy/similarity/log.txt ----- -----

2023-01-18 00:00:01,528:INFO:testStrategy:main.py:102:handleKline:185174: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12235  20230117   231000    231959  1673968799  21315.7  21339.1
12236  20230117   232000    232959  1673969399  21338.4  21274.3
12237  20230117   233000    233959  1673969999  21271.7    21184
12238  20230117   234000    234959  1673970599  21184.3    21154
12239  20230117   235000    235959  1673971199  21151.6  21175.7
2023-01-18 00:00:01,528:INFO:testStrategy:main.py:103:handleKline:185174: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': True, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}
closeSell: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '53.158', 'enterprice': '21192.5', 'countrevence': '0', 'unrealprofit': '914.3176', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '21175.3', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
2023-01-18 00:00:02,233:INFO:testStrategy:main.py:253:closeSell:185174: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False, 'isCorr': False}
2023-01-18 00:00:02,233:INFO:testStrategy:main.py:254:closeSell:185174: ret = self.client.insertMarketUOrder("simulator",  BTCUSDT, 53.158, buy ), ret=InsertOrderReturn{'result': 'success', 'clientorderid': '41540F1673971202232I0L2'}
2023-01-18 00:00:02,263:INFO:testStrategy:main.py:172:insertFactor:185174: curDateTime:1180000, name:testStrategy, symbol:BTCUSDT, tradeDate:20230117, closeTime:235959, close:21175.7, total:1125424.364085, corrDate:20221209, corrVal:0.8587673955150757, side:buy 
127.0.0.1 - - [18/Jan/2023 00:00:02] "POST / HTTP/1.1" 200 -
2023-01-18 00:00:02,965:INFO:testStrategy:main.py:305:handleOrderNew:185174: handleOrderNew: data=OrderType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'clientorderid': '41540F1673971202232I0L2', 'symbol': 'BTCUSDT', 'gatewayorderid': 1673971202433923, 'quantity': '53.158', 'price': '21174.7', 'stopprice': '0', 'ordertype': '', 'side': 'BUY', 'status': 'FILLED', 'positionside': 'LONG', 'createtime': 1673971201701, 'updatetime': 1673971202433, 'tradetype': 'usdt', 'selfid': 41540, 'filltrades': [TradeType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'tradeid': 1673971202433, 'clientorderid': '41540F1673971202232I0L2', 'price': '21174.7', 'quantity': '53.158', 'commission': '1125.6047026', 'commissionasset': 'USDT', 'tradetime': 1673971202433, 'tradetype': 'usdt', 'gatetype': 'simulator', 'handletime': 1673971202433}], 'gatetype': 'simulator', 'handletime': 0}
2023-01-18 00:00:03,195:INFO:testStrategy:main.py:308:handleOrderFilled:185174: handleOrderFilled: data=OrderType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'clientorderid': '41540F1673971202232I0L2', 'symbol': 'BTCUSDT', 'gatewayorderid': 1673971202433923, 'quantity': '53.158', 'price': '21174.7', 'stopprice': '0', 'ordertype': '', 'side': 'BUY', 'status': 'FILLED', 'positionside': 'LONG', 'createtime': 1673971201701, 'updatetime': 1673971202433, 'tradetype': 'usdt', 'selfid': 41540, 'filltrades': [TradeType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'tradeid': 1673971202433, 'clientorderid': '41540F1673971202232I0L2', 'price': '21174.7', 'quantity': '53.158', 'commission': '1125.6047026', 'commissionasset': 'USDT', 'tradetime': 1673971202433, 'tradetype': 'usdt', 'gatetype': 'simulator', 'handletime': 1673971202433}], 'gatetype': 'simulator', 'handletime': 0}
127.0.0.1 - - [18/Jan/2023 00:00:03] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [18/Jan/2023 00:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=7689 

self.closeSec=1673971799, self.tradeDate='20230118', self.openTime='000000', self.closeTime='000959', self.symbol='BTCUSDT', self.open='21175.7', self.close='21144.9'
2023-01-18 00:10:01,582:INFO:testStrategy:main.py:101:handleKline:185174: self.closeSec=1673971799, self.tradeDate='20230118', self.openTime='000000', self.closeTime='000959',self.symbol='BTCUSDT',self.open='21175.7', self.close='21144.9'
2023-01-18 00:10:01,604:INFO:testStrategy:main.py:102:handleKline:185174: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12236  20230117   232000    232959  1673969399  21338.4  21274.3
12237  20230117   233000    233959  1673969999  21271.7    21184
12238  20230117   234000    234959  1673970599  21184.3    21154
12239  20230117   235000    235959  1673971199  21151.6  21175.7
12240  20230118   000000    000959  1673971799  21175.7  21144.9
2023-01-18 00:10:01,605:INFO:testStrategy:main.py:103:handleKline:185174: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False, 'isCorr': False}


## /root/FIL/strategy/sr_min/log.txt ----- -----

127.0.0.1 - - [18/Jan/2023 00:10:01] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=0, self.total=1000000.0, self.flagDict['side']='', self.tradeCount=0, self.count=10808
self.closeSec=1673971799, self.tradeDate='20230118', self.openTime='000500', self.closeTime='000959', self.symbol='BTCUSDT', self.open=21203.9, self.close=21144.9, self.high=21205.4, self.low=21106.3, self.vol=2472.416, self.amt=52268642.3006 
2023-01-18 00:10:01,564:INFO:sr_min:main.py:172:handleKline:449472: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5757  20230117   234500    234959  ...         0.0        0.0       0
5758  20230117   235000    235459  ...         0.0        0.0       0
5759  20230117   235500    235959  ...         0.0        0.0       0
5760  20230118   000000    000459  ...         0.0        0.0       0
5761  20230118   000500    000959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-01-18 00:10:01,565:INFO:sr_min:main.py:175:handleKline:449472: self.closeSec=1673971799, self.tradeDate='20230118', self.openTime='000500', self.closeTime='000959',self.symbol='BTCUSDT',self.open=21203.9, self.close=21144.9, self.high=21205.4, self.low=21106.3, self.vol=2472.416, self.amt=52268642.3006, ukdf['pct'].iloc[-1]=-0.002858 , ukdf['amount'].iloc[-1]=52268642.3006, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5761, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': []}
type(curSign)=<class 'int'>, curSign=0, self.sign=0
--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=0, self.total=1000000.0, self.flagDict['side']='', self.tradeCount=0, self.count=10809
self.closeSec=1673972099, self.tradeDate='20230118', self.openTime='001000', self.closeTime='001459', self.symbol='BTCUSDT', self.open=21145.9, self.close=21107.0, self.high=21146.3, self.low=21082.3, self.vol=2859.065, self.amt=60338770.4402 
127.0.0.1 - - [18/Jan/2023 00:15:00] "POST / HTTP/1.1" 200 -
2023-01-18 00:15:00,775:INFO:sr_min:main.py:172:handleKline:449472: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5758  20230117   235000    235459  ...         0.0        0.0       0
5759  20230117   235500    235959  ...         0.0        0.0       0
5760  20230118   000000    000459  ...         0.0        0.0       0
5761  20230118   000500    000959  ...         0.0        0.0       0
5762  20230118   001000    001459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-01-18 00:15:00,775:INFO:sr_min:main.py:175:handleKline:449472: self.closeSec=1673972099, self.tradeDate='20230118', self.openTime='001000', self.closeTime='001459',self.symbol='BTCUSDT',self.open=21145.9, self.close=21107.0, self.high=21146.3, self.low=21082.3, self.vol=2859.065, self.amt=60338770.4402, ukdf['pct'].iloc[-1]=-0.001792 , ukdf['amount'].iloc[-1]=60338770.4402, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5762, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': []}
type(curSign)=<class 'int'>, curSign=0, self.sign=0


## /root/FIL/strategy/s_rsrs/log.txt ----- -----

721  20230117   040000    075959  ...   85257.322  1.810116e+09 -0.005916
722  20230117   080000    115959  ...   81669.204  1.722050e+09 -0.002770
723  20230117   120000    155959  ...   40393.627  8.539123e+08  0.000241
724  20230117   160000    195959  ...   49711.091  1.052226e+09  0.003970
725  20230117   200000    235959  ...  233118.482  4.958880e+09 -0.002022

[5 rows x 11 columns]
2023-01-18 00:00:03,631:INFO:s_rsrs:main.py:151:handleKline:185271: df_s.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec  ...  index      beta    zscore  signal
721  20230117   040000    075959  1673913599  ...    721  0.897750  0.242217     NaN
722  20230117   080000    115959  1673927999  ...    722  0.876839  0.169505     NaN
723  20230117   120000    155959  1673942399  ...    723  0.774235 -0.117167     NaN
724  20230117   160000    195959  1673956799  ...    724  0.635010 -0.505098     NaN
725  20230117   200000    235959  1673971199  ...    725  0.515810 -0.841899    -1.0

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '51.136', 'enterprice': '17188.2', 'countrevence': '0', 'unrealprofit': '203848.5504', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '21174.6', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-1, self.sign=1
handlebackTrade > queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '51.136', 'enterprice': '17188.2', 'countrevence': '0', 'unrealprofit': '203848.5504', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '21174.6', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
2023-01-18 00:00:09,785:INFO:s_rsrs:main.py:182:queryContractAssets:185271: queryContractAssets: assets=ContractAssetReturn{'result': [ContractAsset{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'asset': 'USDT', 'free': '1084351.3916706', 'total': '1084351.3916706', 'margin': '0', 'unreal': '0', 'type': 'AssetType_ucontract'}]}
2023-01-18 00:00:09,974:INFO:s_rsrs:main.py:269:openSell:185271: ret = self.client.insertMarketUOrder("simulator", "BTCUSDT", 51.053, "sell"), ret=InsertOrderReturn{'result': 'success', 'clientorderid': '41544F1673971209972I0L65'}
2023-01-18 00:00:09,989:INFO:s_rsrs:main.py:176:insertFactor:185271: curDateTime:1180000, name:s_rsrs, symbol:BTCUSDT, tradeDate:20230117, closeTime:235959, close:21175.7, sign:-1, total:1084351.3916706, side:sell  
127.0.0.1 - - [18/Jan/2023 00:00:09] "POST / HTTP/1.1" 200 -
2023-01-18 00:00:09,990:INFO:s_rsrs:main.py:343:handleOrderNew:185271: handleOrderNew: data=OrderType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'clientorderid': '41543F1673971204691I0L65', 'symbol': 'BTCUSDT', 'gatewayorderid': 1673971204793597, 'quantity': '51.136', 'price': '21174.6', 'stopprice': '0', 'ordertype': '', 'side': 'SELL', 'status': 'FILLED', 'positionside': 'SHORT', 'createtime': 1673971204014, 'updatetime': 1673971204793, 'tradetype': 'usdt', 'selfid': 41543, 'filltrades': [TradeType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'tradeid': 1673971204793, 'clientorderid': '41543F1673971204691I0L65', 'price': '21174.6', 'quantity': '51.136', 'commission': '1082.7843456', 'commissionasset': 'USDT', 'tradetime': 1673971204793, 'tradetype': 'usdt', 'gatetype': 'simulator', 'handletime': 1673971204793}], 'gatetype': 'simulator', 'handletime': 0}
127.0.0.1 - - [18/Jan/2023 00:00:09] "POST / HTTP/1.1" 200 -
2023-01-18 00:00:09,992:INFO:s_rsrs:main.py:346:handleOrderFilled:185271: handleOrderFilled: data=OrderType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'clientorderid': '41543F1673971204691I0L65', 'symbol': 'BTCUSDT', 'gatewayorderid': 1673971204793597, 'quantity': '51.136', 'price': '21174.6', 'stopprice': '0', 'ordertype': '', 'side': 'SELL', 'status': 'FILLED', 'positionside': 'SHORT', 'createtime': 1673971204014, 'updatetime': 1673971204793, 'tradetype': 'usdt', 'selfid': 41543, 'filltrades': [TradeType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'tradeid': 1673971204793, 'clientorderid': '41543F1673971204691I0L65', 'price': '21174.6', 'quantity': '51.136', 'commission': '1082.7843456', 'commissionasset': 'USDT', 'tradetime': 1673971204793, 'tradetype': 'usdt', 'gatetype': 'simulator', 'handletime': 1673971204793}], 'gatetype': 'simulator', 'handletime': 0}
2023-01-18 00:00:10,126:INFO:s_rsrs:main.py:343:handleOrderNew:185271: handleOrderNew: data=OrderType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'clientorderid': '41544F1673971209972I0L65', 'symbol': 'BTCUSDT', 'gatewayorderid': 1673971210086252, 'quantity': '51.053', 'price': '21166.9', 'stopprice': '0', 'ordertype': '', 'side': 'SELL', 'status': 'FILLED', 'positionside': 'SHORT', 'createtime': 1673971209796, 'updatetime': 1673971210086, 'tradetype': 'usdt', 'selfid': 41544, 'filltrades': [TradeType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'tradeid': 1673971210086, 'clientorderid': '41544F1673971209972I0L65', 'price': '21166.9', 'quantity': '51.053', 'commission': '1080.6337457', 'commissionasset': 'USDT', 'tradetime': 1673971210086, 'tradetype': 'usdt', 'gatetype': 'simulator', 'handletime': 1673971210086}], 'gatetype': 'simulator', 'handletime': 0}
127.0.0.1 - - [18/Jan/2023 00:00:10] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [18/Jan/2023 00:00:10] "POST / HTTP/1.1" 200 -
2023-01-18 00:00:10,309:INFO:s_rsrs:main.py:346:handleOrderFilled:185271: handleOrderFilled: data=OrderType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'clientorderid': '41544F1673971209972I0L65', 'symbol': 'BTCUSDT', 'gatewayorderid': 1673971210086252, 'quantity': '51.053', 'price': '21166.9', 'stopprice': '0', 'ordertype': '', 'side': 'SELL', 'status': 'FILLED', 'positionside': 'SHORT', 'createtime': 1673971209796, 'updatetime': 1673971210086, 'tradetype': 'usdt', 'selfid': 41544, 'filltrades': [TradeType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'tradeid': 1673971210086, 'clientorderid': '41544F1673971209972I0L65', 'price': '21166.9', 'quantity': '51.053', 'commission': '1080.6337457', 'commissionasset': 'USDT', 'tradetime': 1673971210086, 'tradetype': 'usdt', 'gatetype': 'simulator', 'handletime': 1673971210086}], 'gatetype': 'simulator', 'handletime': 0}


