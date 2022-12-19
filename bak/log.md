# 20221220 00:16:01

## /root/FIL/strategy/amihud/log.txt ----- -----

127.0.0.1 - - [20/Dec/2022 00:10:01] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=993672.4896432, self.flagDict['side']='sell', self.tradeCount=2, self.count=6458
self.closeSec=1671466199, self.tradeDate='20221220', self.openTime='000500', self.closeTime='000959', self.symbol='BTCUSDT', self.open=16672.6, self.close=16669.0, self.high=16678.8, self.low=16660.3, self.vol=1045.6, self.amt=17431152.2261 
2022-12-20 00:10:01,553:INFO:amihud:main.py:172:handleKline:200676: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5757  20221219   234500    234959  ...         0.0        0.0       0
5758  20221219   235000    235459  ...         0.0        0.0       0
5759  20221219   235500    235959  ...         0.0        0.0       0
5760  20221220   000000    000459  ...         0.0        0.0       0
5761  20221220   000500    000959  ...         0.0        0.0       0

[5 rows x 18 columns]
2022-12-20 00:10:01,555:INFO:amihud:main.py:175:handleKline:200676: self.closeSec=1671466199, self.tradeDate='20221220', self.openTime='000500', self.closeTime='000959',self.symbol='BTCUSDT',self.open=16672.6, self.close=16669.0, self.high=16678.8, self.low=16660.3, self.vol=1045.6, self.amt=17431152.2261, ukdf['pct'].iloc[-1]=-0.000216 , ukdf['amount'].iloc[-1]=17431152.2261, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5761, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '60.176', 'enterprice': '16529.3', 'countrevence': '0', 'unrealprofit': '-8460.7456', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '16669.9', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1
127.0.0.1 - - [20/Dec/2022 00:15:00] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=993672.4896432, self.flagDict['side']='sell', self.tradeCount=2, self.count=6459
self.closeSec=1671466499, self.tradeDate='20221220', self.openTime='001000', self.closeTime='001459', self.symbol='BTCUSDT', self.open=16669.9, self.close=16679.8, self.high=16683.5, self.low=16665.9, self.vol=1267.132, self.amt=21129022.6588 
2022-12-20 00:15:00,822:INFO:amihud:main.py:172:handleKline:200676: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5758  20221219   235000    235459  ...         0.0        0.0       0
5759  20221219   235500    235959  ...         0.0        0.0       0
5760  20221220   000000    000459  ...         0.0        0.0       0
5761  20221220   000500    000959  ...         0.0        0.0       0
5762  20221220   001000    001459  ...         0.0        0.0       0

[5 rows x 18 columns]
2022-12-20 00:15:00,823:INFO:amihud:main.py:175:handleKline:200676: self.closeSec=1671466499, self.tradeDate='20221220', self.openTime='001000', self.closeTime='001459',self.symbol='BTCUSDT',self.open=16669.9, self.close=16679.8, self.high=16683.5, self.low=16665.9, self.vol=1267.132, self.amt=21129022.6588, ukdf['pct'].iloc[-1]=0.000648 , ukdf['amount'].iloc[-1]=21129022.6588, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5762, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '60.176', 'enterprice': '16529.3', 'countrevence': '0', 'unrealprofit': '-9090.14206165328', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '16680.35926053', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1


## /root/FIL/strategy/factorcheck/log.txt ----- -----


self.closeSec=1671466199, self.tradeDate='20221220', self.openTime='000500', self.closeTime='000959', self.symbol='BTCUSDT', self.open=16672.6, self.close=16669.0, self.high=16678.8, self.low=16660.3 
2022-12-20 00:10:01,449:INFO:factorcheck2:main.py:126:handleKline:185239: self.closeSec=1671466199, self.tradeDate='20221220', self.openTime='000500', self.closeTime='000959',self.symbol='BTCUSDT',self.open=16672.6, self.close=16669.0, self.high=16678.8, self.low=16660.3   
127.0.0.1 - - [20/Dec/2022 00:10:01] "POST / HTTP/1.1" 200 -
2022-12-20 00:10:01,524:INFO:factorcheck2:main.py:127:handleKline:185239: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1437  20221219   234500    234959  1671464999  ...  16692.1  0.000401   1725    3
1438  20221219   235000    235459  1671465299  ...  16666.0 -0.002000   1726    4
1439  20221219   235500    235959  1671465599  ...  16657.0 -0.000402   1727    5
1440  20221220   000000    000459  1671465899  ...  16650.3  0.000744   1440    0
1441  20221220   000500    000959  1671466199  ...  16660.3 -0.000216   1441    1

[5 rows x 11 columns]
2022-12-20 00:10:01,524:INFO:factorcheck2:main.py:128:handleKline:185239: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': False, 'isOpen': True, 'isClose': False, 'isTrig': True}
127.0.0.1 - - [20/Dec/2022 00:15:00] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=42, self.factor=0.5642123812991663, self.count=7025 

self.closeSec=1671466499, self.tradeDate='20221220', self.openTime='001000', self.closeTime='001459', self.symbol='BTCUSDT', self.open=16669.9, self.close=16679.8, self.high=16683.5, self.low=16665.9 
2022-12-20 00:15:00,804:INFO:factorcheck2:main.py:126:handleKline:185239: self.closeSec=1671466499, self.tradeDate='20221220', self.openTime='001000', self.closeTime='001459',self.symbol='BTCUSDT',self.open=16669.9, self.close=16679.8, self.high=16683.5, self.low=16665.9   
2022-12-20 00:15:00,844:INFO:factorcheck2:main.py:127:handleKline:185239: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1438  20221219   235000    235459  1671465299  ...  16666.0 -0.002000   1726    4
1439  20221219   235500    235959  1671465599  ...  16657.0 -0.000402   1727    5
1440  20221220   000000    000459  1671465899  ...  16650.3  0.000744   1440    0
1441  20221220   000500    000959  1671466199  ...  16660.3 -0.000216   1441    1
1442  20221220   001000    001459  1671466499  ...  16665.9  0.000648   1442    2

[5 rows x 11 columns]
2022-12-20 00:15:00,844:INFO:factorcheck2:main.py:128:handleKline:185239: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': False, 'isOpen': True, 'isClose': False, 'isTrig': True}


## /root/FIL/strategy/logic/log.txt ----- -----

2022-12-20 00:00:18,819:DEBUG:logic:main.py:454:getModel:174970: df_s.iloc[-5:,:] :
          date closeTime     open  ...    alpha58   alpha67   alpha72
5802  20221219    212959  16734.4  ...  47.916667  0.469687  0.557402
5803  20221219    215959  16713.3  ...  47.916667  0.464141  0.564995
5804  20221219    222959  16701.4  ...  47.500000  0.462447  0.572904
5805  20221219    225959  16700.1  ...  47.500000  0.479633  0.572999
5806  20221219    232959  16727.5  ...  47.500000  0.477707  0.573988

[5 rows x 33 columns]
0.5606617647058824
acc is : 0.5606617647058824
2022-12-20 00:00:18,921:INFO:logic:main.py:459:getModel:174970: df_pred.iloc[-5:,:] :
     pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
539     1  0.489168  0.510832       0  ...  1.107010  -1.0    0.0  0.993245
540     1  0.492902  0.507098       0  ...  1.107216  -1.0    0.0  0.993060
541     1  0.494811  0.505189       1  ...  1.105392  -1.0    0.0  0.994696
542     0  0.505816  0.494184       0  ...  1.105617  -1.0    0.0  0.994494
543     1  0.496234  0.503766       0  ...  1.109841  -1.0    0.0  0.990694

[5 rows x 10 columns]
2022-12-20 00:00:18,944:INFO:logic:main.py:469:getModel:174970: df_panel.iloc[-5:,:] :
    pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
45     1  0.490123  0.509877       0  ...  1.107010  -1.0    0.0  0.994688
46     1  0.493437  0.506563       0  ...  1.107216  -1.0    0.0  0.994379
47     1  0.495463  0.504537       1  ...  1.105392  -1.0    0.0  0.996017
48     0  0.506178  0.493822       0  ...  1.105617  -1.0    0.0  0.994831
49     1  0.496234  0.503766       0  ...  1.109841  -1.0    0.0  0.990694

[5 rows x 10 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '37.704', 'enterprice': '17770', 'countrevence': '0', 'unrealprofit': '41978.5778540664', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '16656.6280009', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}


## /root/FIL/strategy/modifiedmom/log.txt ----- -----

2022-12-20 00:00:01,799:INFO:modifiedmom:main.py:145:handleKline:185213: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
571  20221219   231000    231959  1671463199  16706.5  16707.4  0.000054
572  20221219   232000    232959  1671463799  16709.1  16725.2  0.001065
573  20221219   233000    233959  1671464399    16724  16696.4 -0.001722
574  20221219   234000    234959  1671464999  16696.4  16700.3  0.000234
575  20221219   235000    235959  1671465599  16700.3  16660.2 -0.002401
2022-12-20 00:00:01,799:INFO:modifiedmom:main.py:146:handleKline:185213: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': True, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True}
closeSell: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '57.658', 'enterprice': '16656.4', 'countrevence': '0', 'unrealprofit': '-302.92927913642', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '16661.65389849', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
2022-12-20 00:00:02,431:INFO:modifiedmom:main.py:287:closeSell:185213: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False}
2022-12-20 00:00:02,431:INFO:modifiedmom:main.py:288:closeSell:185213: ret = self.client.insertMarketUOrder("simulator",  BTCUSDT, 57.658, buy ), ret=InsertOrderReturn{'result': 'success', 'clientorderid': '41384F1671465602430I0L59'}
2022-12-20 00:00:02,457:INFO:modifiedmom:main.py:206:insertFactor:185213: curDateTime:12200000, name:modifiedmom, symbol:BTCUSDT, tradeDate:20221219, closeTime:235959, close:16660.2, total:959414.3364888001, mom:-0.004954310216456426, thd:0.0, side:buy 
2022-12-20 00:00:02,577:INFO:modifiedmom:main.py:316:handleOrderNew:185213: handleOrderNew: data=OrderType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'clientorderid': '41384F1671465602430I0L59', 'symbol': 'BTCUSDT', 'gatewayorderid': 1671465602532080, 'quantity': '57.658', 'price': '16660.3', 'stopprice': '0', 'ordertype': '', 'side': 'BUY', 'status': 'FILLED', 'positionside': 'LONG', 'createtime': 1671465601957, 'updatetime': 1671465602532, 'tradetype': 'usdt', 'selfid': 41384, 'filltrades': [TradeType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'tradeid': 1671465602532, 'clientorderid': '41384F1671465602430I0L59', 'price': '16660.3', 'quantity': '57.658', 'commission': '960.5995774', 'commissionasset': 'USDT', 'tradetime': 1671465602532, 'tradetype': 'usdt', 'gatetype': 'simulator', 'handletime': 1671465602532}], 'gatetype': 'simulator', 'handletime': 0}
127.0.0.1 - - [20/Dec/2022 00:00:02] "POST / HTTP/1.1" 200 -
2022-12-20 00:00:02,862:INFO:modifiedmom:main.py:319:handleOrderFilled:185213: handleOrderFilled: data=OrderType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'clientorderid': '41384F1671465602430I0L59', 'symbol': 'BTCUSDT', 'gatewayorderid': 1671465602532080, 'quantity': '57.658', 'price': '16660.3', 'stopprice': '0', 'ordertype': '', 'side': 'BUY', 'status': 'FILLED', 'positionside': 'LONG', 'createtime': 1671465601957, 'updatetime': 1671465602532, 'tradetype': 'usdt', 'selfid': 41384, 'filltrades': [TradeType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'tradeid': 1671465602532, 'clientorderid': '41384F1671465602430I0L59', 'price': '16660.3', 'quantity': '57.658', 'commission': '960.5995774', 'commissionasset': 'USDT', 'tradetime': 1671465602532, 'tradetype': 'usdt', 'gatetype': 'simulator', 'handletime': 1671465602532}], 'gatetype': 'simulator', 'handletime': 0}
127.0.0.1 - - [20/Dec/2022 00:00:02] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [20/Dec/2022 00:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=3512 

self.closeSec=1671466199, self.tradeDate='20221220', self.openTime='000000', self.closeTime='000959', self.symbol='BTCUSDT', self.open='16660.3', self.close='16668.9'
2022-12-20 00:10:01,574:INFO:modifiedmom:main.py:144:handleKline:185213: self.closeSec=1671466199, self.tradeDate='20221220', self.openTime='000000', self.closeTime='000959',self.symbol='BTCUSDT',self.open='16660.3', self.close='16668.9'
2022-12-20 00:10:01,605:INFO:modifiedmom:main.py:145:handleKline:185213: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
572  20221219   232000    232959  1671463799  16709.1  16725.2  0.001065
573  20221219   233000    233959  1671464399    16724  16696.4 -0.001722
574  20221219   234000    234959  1671464999  16696.4  16700.3  0.000234
575  20221219   235000    235959  1671465599  16700.3  16660.2 -0.002401
576  20221220   000000    000959  1671466199  16660.3  16668.9  0.000522
2022-12-20 00:10:01,605:INFO:modifiedmom:main.py:146:handleKline:185213: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False}


## /root/FIL/strategy/pyemd/log.txt ----- -----

2022-12-20 00:00:01,801:INFO:pyemd2:main.py:126:handleKline:185189: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17419  20221219   231000    231959  1671463199  16706.5  16707.4
17420  20221219   232000    232959  1671463799  16709.1  16725.2
17421  20221219   233000    233959  1671464399    16724  16696.4
17422  20221219   234000    234959  1671464999  16696.4  16700.3
17423  20221219   235000    235959  1671465599  16700.3  16660.2
2022-12-20 00:00:01,802:INFO:pyemd2:main.py:127:handleKline:185189: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': False, 'isOpen': True, 'isClose': False, 'isTrig': True}
closeBuy: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '56.527', 'enterprice': '16743.6', 'countrevence': '0', 'unrealprofit': '-4632.16728005577', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '16661.65389849', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
2022-12-20 00:00:02,449:INFO:pyemd2:main.py:251:closeBuy:185189: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}
2022-12-20 00:00:02,449:INFO:pyemd2:main.py:252:closeBuy:185189: ret = self.client.insertMarketUOrder("simulator",  BTCUSDT, 56.527, sell ), ret=InsertOrderReturn{'result': 'success', 'clientorderid': '41385F1671465602448I0L57'}
2022-12-20 00:00:02,538:INFO:pyemd2:main.py:190:insertFactor:185189: curDateTime:12200000, name:pyemd2, symbol:BTCUSDT, tradeDate:20221219, closeTime:235959, close:16660.2, total:945519.0117228, pct_pre:0.003464044061681548, thd:0.4055871810688762, side:sell 
2022-12-20 00:00:02,845:INFO:pyemd2:main.py:300:handleOrderNew:185189: handleOrderNew: data=OrderType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'clientorderid': '41385F1671465602448I0L57', 'symbol': 'BTCUSDT', 'gatewayorderid': 1671465602585880, 'quantity': '56.527', 'price': '16660.2', 'stopprice': '0', 'ordertype': '', 'side': 'SELL', 'status': 'FILLED', 'positionside': 'SHORT', 'createtime': 1671465602007, 'updatetime': 1671465602585, 'tradetype': 'usdt', 'selfid': 41385, 'filltrades': [TradeType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'tradeid': 1671465602585, 'clientorderid': '41385F1671465602448I0L57', 'price': '16660.2', 'quantity': '56.527', 'commission': '941.7511254', 'commissionasset': 'USDT', 'tradetime': 1671465602585, 'tradetype': 'usdt', 'gatetype': 'simulator', 'handletime': 1671465602585}], 'gatetype': 'simulator', 'handletime': 0}
127.0.0.1 - - [20/Dec/2022 00:00:02] "POST / HTTP/1.1" 200 -
2022-12-20 00:00:03,036:INFO:pyemd2:main.py:303:handleOrderFilled:185189: handleOrderFilled: data=OrderType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'clientorderid': '41385F1671465602448I0L57', 'symbol': 'BTCUSDT', 'gatewayorderid': 1671465602585880, 'quantity': '56.527', 'price': '16660.2', 'stopprice': '0', 'ordertype': '', 'side': 'SELL', 'status': 'FILLED', 'positionside': 'SHORT', 'createtime': 1671465602007, 'updatetime': 1671465602585, 'tradetype': 'usdt', 'selfid': 41385, 'filltrades': [TradeType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'tradeid': 1671465602585, 'clientorderid': '41385F1671465602448I0L57', 'price': '16660.2', 'quantity': '56.527', 'commission': '941.7511254', 'commissionasset': 'USDT', 'tradetime': 1671465602585, 'tradetype': 'usdt', 'gatetype': 'simulator', 'handletime': 1671465602585}], 'gatetype': 'simulator', 'handletime': 0}
127.0.0.1 - - [20/Dec/2022 00:00:03] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=3513 

self.closeSec=1671466199, self.tradeDate='20221220', self.openTime='000000', self.closeTime='000959', self.symbol='BTCUSDT', self.open='16660.3', self.close='16668.9'
2022-12-20 00:10:01,594:INFO:pyemd2:main.py:125:handleKline:185189: self.closeSec=1671466199, self.tradeDate='20221220', self.openTime='000000', self.closeTime='000959',self.symbol='BTCUSDT',self.open='16660.3', self.close='16668.9'
127.0.0.1 - - [20/Dec/2022 00:10:01] "POST / HTTP/1.1" 200 -
2022-12-20 00:10:01,608:INFO:pyemd2:main.py:126:handleKline:185189: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17420  20221219   232000    232959  1671463799  16709.1  16725.2
17421  20221219   233000    233959  1671464399    16724  16696.4
17422  20221219   234000    234959  1671464999  16696.4  16700.3
17423  20221219   235000    235959  1671465599  16700.3  16660.2
17424  20221220   000000    000959  1671466199  16660.3  16668.9
2022-12-20 00:10:01,608:INFO:pyemd2:main.py:127:handleKline:185189: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}


## /root/FIL/strategy/similarity/log.txt ----- -----

2022-12-20 00:00:01,817:INFO:testStrategy:main.py:102:handleKline:185174: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12235  20221219   231000    231959  1671463199  16706.5  16707.4
12236  20221219   232000    232959  1671463799  16709.1  16725.2
12237  20221219   233000    233959  1671464399    16724  16696.4
12238  20221219   234000    234959  1671464999  16696.4  16700.3
12239  20221219   235000    235959  1671465599  16700.3  16660.2
2022-12-20 00:00:01,817:INFO:testStrategy:main.py:103:handleKline:185174: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': True, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}
closeSell: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '73.327', 'enterprice': '16754.7', 'countrevence': '0', 'unrealprofit': '6886.55507249289', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '16660.78431993', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
2022-12-20 00:00:03,002:INFO:testStrategy:main.py:253:closeSell:185174: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False, 'isCorr': False}
2022-12-20 00:00:03,002:INFO:testStrategy:main.py:254:closeSell:185174: ret = self.client.insertMarketUOrder("simulator",  BTCUSDT, 73.327, buy ), ret=InsertOrderReturn{'result': 'success', 'clientorderid': '41386F1671465602878I0L2'}
2022-12-20 00:00:03,023:INFO:testStrategy:main.py:172:insertFactor:185174: curDateTime:12200000, name:testStrategy, symbol:BTCUSDT, tradeDate:20221219, closeTime:235959, close:16660.2, total:1227343.3150131, corrDate:20221024, corrVal:0.8887719519746791, side:buy 
2022-12-20 00:00:03,142:INFO:testStrategy:main.py:305:handleOrderNew:185174: handleOrderNew: data=OrderType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'clientorderid': '41386F1671465602878I0L2', 'symbol': 'BTCUSDT', 'gatewayorderid': 1671465603116281, 'quantity': '73.327', 'price': '16660.3', 'stopprice': '0', 'ordertype': '', 'side': 'BUY', 'status': 'FILLED', 'positionside': 'LONG', 'createtime': 1671465602235, 'updatetime': 1671465603116, 'tradetype': 'usdt', 'selfid': 41386, 'filltrades': [TradeType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'tradeid': 1671465603116, 'clientorderid': '41386F1671465602878I0L2', 'price': '16660.3', 'quantity': '73.327', 'commission': '1221.6498181', 'commissionasset': 'USDT', 'tradetime': 1671465603116, 'tradetype': 'usdt', 'gatetype': 'simulator', 'handletime': 1671465603116}], 'gatetype': 'simulator', 'handletime': 0}
127.0.0.1 - - [20/Dec/2022 00:00:03] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [20/Dec/2022 00:00:03] "POST / HTTP/1.1" 200 -
2022-12-20 00:00:03,355:INFO:testStrategy:main.py:308:handleOrderFilled:185174: handleOrderFilled: data=OrderType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'clientorderid': '41386F1671465602878I0L2', 'symbol': 'BTCUSDT', 'gatewayorderid': 1671465603116281, 'quantity': '73.327', 'price': '16660.3', 'stopprice': '0', 'ordertype': '', 'side': 'BUY', 'status': 'FILLED', 'positionside': 'LONG', 'createtime': 1671465602235, 'updatetime': 1671465603116, 'tradetype': 'usdt', 'selfid': 41386, 'filltrades': [TradeType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'tradeid': 1671465603116, 'clientorderid': '41386F1671465602878I0L2', 'price': '16660.3', 'quantity': '73.327', 'commission': '1221.6498181', 'commissionasset': 'USDT', 'tradetime': 1671465603116, 'tradetype': 'usdt', 'gatetype': 'simulator', 'handletime': 1671465603116}], 'gatetype': 'simulator', 'handletime': 0}
127.0.0.1 - - [20/Dec/2022 00:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=3513 

self.closeSec=1671466199, self.tradeDate='20221220', self.openTime='000000', self.closeTime='000959', self.symbol='BTCUSDT', self.open='16660.3', self.close='16668.9'
2022-12-20 00:10:01,581:INFO:testStrategy:main.py:101:handleKline:185174: self.closeSec=1671466199, self.tradeDate='20221220', self.openTime='000000', self.closeTime='000959',self.symbol='BTCUSDT',self.open='16660.3', self.close='16668.9'
2022-12-20 00:10:01,607:INFO:testStrategy:main.py:102:handleKline:185174: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12236  20221219   232000    232959  1671463799  16709.1  16725.2
12237  20221219   233000    233959  1671464399    16724  16696.4
12238  20221219   234000    234959  1671464999  16696.4  16700.3
12239  20221219   235000    235959  1671465599  16700.3  16660.2
12240  20221220   000000    000959  1671466199  16660.3  16668.9
2022-12-20 00:10:01,607:INFO:testStrategy:main.py:103:handleKline:185174: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False, 'isCorr': False}


## /root/FIL/strategy/sr_min/log.txt ----- -----

127.0.0.1 - - [20/Dec/2022 00:10:01] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=0, self.total=1000000.0, self.flagDict['side']='', self.tradeCount=0, self.count=2456
self.closeSec=1671466199, self.tradeDate='20221220', self.openTime='000500', self.closeTime='000959', self.symbol='BTCUSDT', self.open=16672.6, self.close=16669.0, self.high=16678.8, self.low=16660.3, self.vol=1045.6, self.amt=17431152.2261 
2022-12-20 00:10:01,554:INFO:sr_min:main.py:172:handleKline:449472: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5757  20221219   234500    234959  ...         0.0        0.0       0
5758  20221219   235000    235459  ...         0.0        0.0       0
5759  20221219   235500    235959  ...         0.0        0.0       0
5760  20221220   000000    000459  ...         0.0        0.0       0
5761  20221220   000500    000959  ...         0.0        0.0       0

[5 rows x 18 columns]
2022-12-20 00:10:01,554:INFO:sr_min:main.py:175:handleKline:449472: self.closeSec=1671466199, self.tradeDate='20221220', self.openTime='000500', self.closeTime='000959',self.symbol='BTCUSDT',self.open=16672.6, self.close=16669.0, self.high=16678.8, self.low=16660.3, self.vol=1045.6, self.amt=17431152.2261, ukdf['pct'].iloc[-1]=-0.000216 , ukdf['amount'].iloc[-1]=17431152.2261, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5761, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': []}
type(curSign)=<class 'int'>, curSign=0, self.sign=0
--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=0, self.total=1000000.0, self.flagDict['side']='', self.tradeCount=0, self.count=2457
self.closeSec=1671466499, self.tradeDate='20221220', self.openTime='001000', self.closeTime='001459', self.symbol='BTCUSDT', self.open=16669.9, self.close=16679.8, self.high=16683.5, self.low=16665.9, self.vol=1267.132, self.amt=21129022.6588 
127.0.0.1 - - [20/Dec/2022 00:15:00] "POST / HTTP/1.1" 200 -
2022-12-20 00:15:00,808:INFO:sr_min:main.py:172:handleKline:449472: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5758  20221219   235000    235459  ...         0.0        0.0       0
5759  20221219   235500    235959  ...         0.0        0.0       0
5760  20221220   000000    000459  ...         0.0        0.0       0
5761  20221220   000500    000959  ...         0.0        0.0       0
5762  20221220   001000    001459  ...         0.0        0.0       0

[5 rows x 18 columns]
2022-12-20 00:15:00,809:INFO:sr_min:main.py:175:handleKline:449472: self.closeSec=1671466499, self.tradeDate='20221220', self.openTime='001000', self.closeTime='001459',self.symbol='BTCUSDT',self.open=16669.9, self.close=16679.8, self.high=16683.5, self.low=16665.9, self.vol=1267.132, self.amt=21129022.6588, ukdf['pct'].iloc[-1]=0.000648 , ukdf['amount'].iloc[-1]=21129022.6588, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5762, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': []}
type(curSign)=<class 'int'>, curSign=0, self.sign=0


## /root/FIL/strategy/s_rsrs/log.txt ----- -----

723  20221219   120000    155959  1671436799  ...    723  0.895413  0.487981     NaN
724  20221219   160000    195959  1671451199  ...    724  0.952799  0.659302     1.0

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '53.436', 'enterprice': '17756.3', 'countrevence': '0', 'unrealprofit': '-55080.16693452204', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '16725.53110011', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=1, self.sign=1
127.0.0.1 - - [20/Dec/2022 00:00:01] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='s_rsrs', self.symbol='BTCUSDT', interval='4h', intervalSec=14400, wid=25, thd=0.6, self.sign=1, self.total=947876.8211532, self.flagDict['side']='buy', self.tradeCount=6, self.count=146
self.closeSec=1671465599, self.tradeDate='20221219', self.openTime='200000', self.closeTime='235959', self.symbol='BTCUSDT', self.open=16725.2, self.close=16660.2, self.high=16757.7, self.low=16656.4, self.vol=54277.784, self.amt=906850244.4844 
2022-12-20 00:00:01,393:INFO:s_rsrs:main.py:141:handleKline:185271: self.closeSec=1671465599, self.tradeDate='20221219', self.openTime='200000', self.closeTime='235959',self.symbol='BTCUSDT',self.open=16725.2, self.close=16660.2, self.high=16757.7, self.low=16656.4, self.vol=54277.784, self.amt=906850244.4844 
2022-12-20 00:00:01,421:INFO:s_rsrs:main.py:142:handleKline:185271: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime  ...        vol           amt       pct
721  20221219   040000    075959  ...  37334.568  6.261975e+08 -0.000914
722  20221219   080000    115959  ...  49601.728  8.289811e+08 -0.003389
723  20221219   120000    155959  ...  28214.603  4.714000e+08  0.002447
724  20221219   160000    195959  ...  27329.823  4.575512e+08  0.000652
725  20221219   200000    235959  ...  54277.784  9.068502e+08 -0.003892

[5 rows x 11 columns]
2022-12-20 00:00:03,055:INFO:s_rsrs:main.py:151:handleKline:185271: df_s.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec  ...  index      beta    zscore  signal
721  20221219   040000    075959  1671407999  ...    721  0.986301  0.804651     1.0
722  20221219   080000    115959  1671422399  ...    722  0.938078  0.640522     1.0
723  20221219   120000    155959  1671436799  ...    723  0.895413  0.487981     NaN
724  20221219   160000    195959  1671451199  ...    724  0.952799  0.659302     1.0
725  20221219   200000    235959  1671465599  ...    725  1.012876  0.847578     1.0

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '53.436', 'enterprice': '17756.3', 'countrevence': '0', 'unrealprofit': '-58518.38033854068', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '16661.18845837', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=1, self.sign=1


