# 20221209 00:16:02

## /root/FIL/strategy/amihud/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=993672.4896432, self.flagDict['side']='sell', self.tradeCount=2, self.count=3290
self.closeSec=1670515799, self.tradeDate='20221209', self.openTime='000500', self.closeTime='000959', self.symbol='BTCUSDT', self.open=16907.1, self.close=16904.9, self.high=16915.0, self.low=16903.4, self.vol=916.541, self.amt=15497981.7198 
127.0.0.1 - - [09/Dec/2022 00:10:01] "POST / HTTP/1.1" 200 -
2022-12-09 00:10:01,715:INFO:amihud:main.py:172:handleKline:200676: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5757  20221208   234500    234959  ...    0.086241   0.235188       0
5758  20221208   235000    235459  ...    0.086060   0.235003       0
5759  20221208   235500    235959  ...    0.085879   0.234817       0
5760  20221209   000000    000459  ...    0.085696   0.234629       0
5761  20221209   000500    000959  ...    0.085514   0.234440       0

[5 rows x 18 columns]
2022-12-09 00:10:01,715:INFO:amihud:main.py:175:handleKline:200676: self.closeSec=1670515799, self.tradeDate='20221209', self.openTime='000500', self.closeTime='000959',self.symbol='BTCUSDT',self.open=16907.1, self.close=16904.9, self.high=16915.0, self.low=16903.4, self.vol=916.541, self.amt=15497981.7198, ukdf['pct'].iloc[-1]=-0.000136 , ukdf['amount'].iloc[-1]=15497981.7198, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5761, value=0.0, value_mean=0.08551390364097301, signal=0, value_std=0.23444020814006006 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '60.176', 'enterprice': '16529.3', 'countrevence': '0', 'unrealprofit': '-22710.67868537168', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '16906.70425893', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1
127.0.0.1 - - [09/Dec/2022 00:15:00] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=993672.4896432, self.flagDict['side']='sell', self.tradeCount=2, self.count=3291
self.closeSec=1670516099, self.tradeDate='20221209', self.openTime='001000', self.closeTime='001459', self.symbol='BTCUSDT', self.open=16904.9, self.close=16929.9, self.high=16930.0, self.low=16904.9, self.vol=1597.577, self.amt=27033355.3061 
2022-12-09 00:15:00,566:INFO:amihud:main.py:172:handleKline:200676: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5758  20221208   235000    235459  ...    0.086060   0.235003       0
5759  20221208   235500    235959  ...    0.085879   0.234817       0
5760  20221209   000000    000459  ...    0.085696   0.234629       0
5761  20221209   000500    000959  ...    0.085514   0.234440       0
5762  20221209   001000    001459  ...    0.085331   0.234250       0

[5 rows x 18 columns]
2022-12-09 00:15:00,567:INFO:amihud:main.py:175:handleKline:200676: self.closeSec=1670516099, self.tradeDate='20221209', self.openTime='001000', self.closeTime='001459',self.symbol='BTCUSDT',self.open=16904.9, self.close=16929.9, self.high=16930.0, self.low=16904.9, self.vol=1597.577, self.amt=27033355.3061, ukdf['pct'].iloc[-1]=0.001479 , ukdf['amount'].iloc[-1]=27033355.3061, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5762, value=0.0, value_mean=0.08533104446855241, signal=0, value_std=0.234250030611738 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '60.176', 'enterprice': '16529.3', 'countrevence': '0', 'unrealprofit': '-24160.664', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '16930.8', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1


## /root/FIL/strategy/factorcheck/log.txt ----- -----


self.closeSec=1670515799, self.tradeDate='20221209', self.openTime='000500', self.closeTime='000959', self.symbol='BTCUSDT', self.open=16907.1, self.close=16904.9, self.high=16915.0, self.low=16903.4 
2022-12-09 00:10:01,685:INFO:factorcheck2:main.py:126:handleKline:185239: self.closeSec=1670515799, self.tradeDate='20221209', self.openTime='000500', self.closeTime='000959',self.symbol='BTCUSDT',self.open=16907.1, self.close=16904.9, self.high=16915.0, self.low=16903.4   
127.0.0.1 - - [09/Dec/2022 00:10:01] "POST / HTTP/1.1" 200 -
2022-12-09 00:10:01,707:INFO:factorcheck2:main.py:127:handleKline:185239: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1437  20221208   234500    234959  1670514599  ...  16895.0 -0.000260   1725    3
1438  20221208   235000    235459  1670514899  ...  16904.6  0.000455   1726    4
1439  20221208   235500    235959  1670515199  ...  16905.6 -0.000337   1727    5
1440  20221209   000000    000459  1670515499  ...  16901.0 -0.000030   1440    0
1441  20221209   000500    000959  1670515799  ...  16903.4 -0.000136   1441    1

[5 rows x 11 columns]
2022-12-09 00:10:01,707:INFO:factorcheck2:main.py:128:handleKline:185239: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': False, 'isOpen': True, 'isClose': False, 'isTrig': True}
127.0.0.1 - - [09/Dec/2022 00:15:00] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.6111360983838672, self.count=3857 

self.closeSec=1670516099, self.tradeDate='20221209', self.openTime='001000', self.closeTime='001459', self.symbol='BTCUSDT', self.open=16904.9, self.close=16929.9, self.high=16930.0, self.low=16904.9 
2022-12-09 00:15:00,536:INFO:factorcheck2:main.py:126:handleKline:185239: self.closeSec=1670516099, self.tradeDate='20221209', self.openTime='001000', self.closeTime='001459',self.symbol='BTCUSDT',self.open=16904.9, self.close=16929.9, self.high=16930.0, self.low=16904.9   
2022-12-09 00:15:00,554:INFO:factorcheck2:main.py:127:handleKline:185239: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1438  20221208   235000    235459  1670514899  ...  16904.6  0.000455   1726    4
1439  20221208   235500    235959  1670515199  ...  16905.6 -0.000337   1727    5
1440  20221209   000000    000459  1670515499  ...  16901.0 -0.000030   1440    0
1441  20221209   000500    000959  1670515799  ...  16903.4 -0.000136   1441    1
1442  20221209   001000    001459  1670516099  ...  16904.9  0.001479   1442    2

[5 rows x 11 columns]
2022-12-09 00:15:00,555:INFO:factorcheck2:main.py:128:handleKline:185239: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': False, 'isOpen': True, 'isClose': False, 'isTrig': True}


## /root/FIL/strategy/logic/log.txt ----- -----

2022-12-09 00:00:18,566:DEBUG:logic:main.py:454:getModel:174970: df_s.iloc[-5:,:] :
          date closeTime     open  ...    alpha58   alpha67   alpha72
5802  20221208    212959  16818.8  ...  52.083333  0.468573  0.522723
5803  20221208    215959  16823.8  ...  52.500000  0.484671  0.500100
5804  20221208    222959  16848.9  ...  52.500000  0.480529  0.481736
5805  20221208    225959  16842.0  ...  52.500000  0.510245  0.461557
5806  20221208    232959  16890.5  ...  52.500000  0.522270  0.439033

[5 rows x 33 columns]
0.5367647058823529
acc is : 0.5367647058823529
2022-12-09 00:00:18,642:INFO:logic:main.py:459:getModel:174970: df_pred.iloc[-5:,:] :
     pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
539     1  0.486262  0.513738       1  ...  0.960198  -1.0    0.0  1.017814
540     1  0.492445  0.507555       0  ...  0.960597  -1.0    0.0  1.017392
541     1  0.482207  0.517793       1  ...  0.957819  -1.0    0.0  1.020333
542     0  0.500976  0.499024       1  ...  0.956628  -1.0    0.0  1.021602
543     1  0.498366  0.501634       0  ...  0.956855  -1.0    0.0  1.021360

[5 rows x 10 columns]
2022-12-09 00:00:18,654:INFO:logic:main.py:469:getModel:174970: df_panel.iloc[-5:,:] :
    pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
45     1  0.486663  0.513337       1  ...  0.946402  -1.0    0.0  1.017292
46     1  0.493237  0.506763       0  ...  0.946795  -1.0    0.0  1.017816
47     1  0.483019  0.516981       1  ...  0.944057  -1.0    0.0  1.020759
48     0  0.501368  0.498632       1  ...  0.942883  -1.0    0.0  1.021614
49     1  0.498366  0.501634       0  ...  0.956855  -1.0    0.0  1.021360

[5 rows x 10 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '38.92', 'enterprice': '16964.2', 'countrevence': '0', 'unrealprofit': '2179.52', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '16908.2', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}


## /root/FIL/strategy/modifiedmom/log.txt ----- -----

2022-12-09 00:00:01,072:INFO:modifiedmom:main.py:145:handleKline:185213: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
571  20221208   231000    231959  1670512799    16911  16895.5 -0.000917
572  20221208   232000    232959  1670513399  16895.5  16911.6  0.000953
573  20221208   233000    233959  1670513999  16911.7  16928.2  0.000982
574  20221208   234000    234959  1670514599  16928.2  16905.7 -0.001329
575  20221208   235000    235959  1670515199  16905.7  16907.7  0.000118
2022-12-09 00:00:01,072:INFO:modifiedmom:main.py:146:handleKline:185213: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': True, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True}
closeSell: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '54.747', 'enterprice': '16825.6', 'countrevence': '0', 'unrealprofit': '-4494.7287', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '16907.7', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
2022-12-09 00:00:01,694:INFO:modifiedmom:main.py:287:closeSell:185213: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False}
2022-12-09 00:00:01,694:INFO:modifiedmom:main.py:288:closeSell:185213: ret = self.client.insertMarketUOrder("simulator",  BTCUSDT, 54.747, buy ), ret=InsertOrderReturn{'result': 'success', 'clientorderid': '41323F1670515201690I0L59'}
2022-12-09 00:00:01,718:INFO:modifiedmom:main.py:206:insertFactor:185213: curDateTime:12090000, name:modifiedmom, symbol:BTCUSDT, tradeDate:20221208, closeTime:235959, close:16907.7, total:920229.9720768, mom:-0.0004018927007427564, thd:0.0, side:buy 
127.0.0.1 - - [09/Dec/2022 00:00:01] "POST / HTTP/1.1" 200 -
2022-12-09 00:00:01,862:INFO:modifiedmom:main.py:316:handleOrderNew:185213: handleOrderNew: data=OrderType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'clientorderid': '41323F1670515201690I0L59', 'symbol': 'BTCUSDT', 'gatewayorderid': 1670515201801899, 'quantity': '54.747', 'price': '16907.7', 'stopprice': '0', 'ordertype': '', 'side': 'BUY', 'status': 'FILLED', 'positionside': 'LONG', 'createtime': 1670515201244, 'updatetime': 1670515201801, 'tradetype': 'usdt', 'selfid': 41323, 'filltrades': [TradeType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'tradeid': 1670515201801, 'clientorderid': '41323F1670515201690I0L59', 'price': '16907.7', 'quantity': '54.747', 'commission': '925.6458519', 'commissionasset': 'USDT', 'tradetime': 1670515201801, 'tradetype': 'usdt', 'gatetype': 'simulator', 'handletime': 1670515201801}], 'gatetype': 'simulator', 'handletime': 0}
127.0.0.1 - - [09/Dec/2022 00:00:02] "POST / HTTP/1.1" 200 -
2022-12-09 00:00:02,150:INFO:modifiedmom:main.py:319:handleOrderFilled:185213: handleOrderFilled: data=OrderType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'clientorderid': '41323F1670515201690I0L59', 'symbol': 'BTCUSDT', 'gatewayorderid': 1670515201801899, 'quantity': '54.747', 'price': '16907.7', 'stopprice': '0', 'ordertype': '', 'side': 'BUY', 'status': 'FILLED', 'positionside': 'LONG', 'createtime': 1670515201244, 'updatetime': 1670515201801, 'tradetype': 'usdt', 'selfid': 41323, 'filltrades': [TradeType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'tradeid': 1670515201801, 'clientorderid': '41323F1670515201690I0L59', 'price': '16907.7', 'quantity': '54.747', 'commission': '925.6458519', 'commissionasset': 'USDT', 'tradetime': 1670515201801, 'tradetype': 'usdt', 'gatetype': 'simulator', 'handletime': 1670515201801}], 'gatetype': 'simulator', 'handletime': 0}
127.0.0.1 - - [09/Dec/2022 00:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=1928 

self.closeSec=1670515799, self.tradeDate='20221209', self.openTime='000000', self.closeTime='000959', self.symbol='BTCUSDT', self.open='16907.7', self.close='16904.9'
2022-12-09 00:10:01,779:INFO:modifiedmom:main.py:144:handleKline:185213: self.closeSec=1670515799, self.tradeDate='20221209', self.openTime='000000', self.closeTime='000959',self.symbol='BTCUSDT',self.open='16907.7', self.close='16904.9'
2022-12-09 00:10:01,793:INFO:modifiedmom:main.py:145:handleKline:185213: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
572  20221208   232000    232959  1670513399  16895.5  16911.6  0.000953
573  20221208   233000    233959  1670513999  16911.7  16928.2  0.000982
574  20221208   234000    234959  1670514599  16928.2  16905.7 -0.001329
575  20221208   235000    235959  1670515199  16905.7  16907.7  0.000118
576  20221209   000000    000959  1670515799  16907.7  16904.9 -0.000166
2022-12-09 00:10:01,793:INFO:modifiedmom:main.py:146:handleKline:185213: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False}


## /root/FIL/strategy/pyemd/log.txt ----- -----

2022-12-08 23:50:00,550:INFO:pyemd2:main.py:127:handleKline:185189: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=1928 

self.closeSec=1670515199, self.tradeDate='20221208', self.openTime='235000', self.closeTime='235959', self.symbol='BTCUSDT', self.open='16905.7', self.close='16907.7'
127.0.0.1 - - [09/Dec/2022 00:00:01] "POST / HTTP/1.1" 200 -
2022-12-09 00:00:01,053:INFO:pyemd2:main.py:125:handleKline:185189: self.closeSec=1670515199, self.tradeDate='20221208', self.openTime='235000', self.closeTime='235959',self.symbol='BTCUSDT',self.open='16905.7', self.close='16907.7'
2022-12-09 00:00:01,150:INFO:pyemd2:main.py:126:handleKline:185189: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17419  20221208   231000    231959  1670512799    16911  16895.5
17420  20221208   232000    232959  1670513399  16895.5  16911.6
17421  20221208   233000    233959  1670513999  16911.7  16928.2
17422  20221208   234000    234959  1670514599  16928.2  16905.7
17423  20221208   235000    235959  1670515199  16905.7  16907.7
2022-12-09 00:00:01,152:INFO:pyemd2:main.py:127:handleKline:185189: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}
2022-12-09 00:00:01,275:INFO:pyemd2:main.py:190:insertFactor:185189: curDateTime:12090000, name:pyemd2, symbol:BTCUSDT, tradeDate:20221208, closeTime:235959, close:16907.7, total:940056.5307028, pct_pre:-0.0017596214436028657, thd:0.37364698875549657, side:sell 
127.0.0.1 - - [09/Dec/2022 00:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=1929 

self.closeSec=1670515799, self.tradeDate='20221209', self.openTime='000000', self.closeTime='000959', self.symbol='BTCUSDT', self.open='16907.7', self.close='16904.9'
2022-12-09 00:10:01,773:INFO:pyemd2:main.py:125:handleKline:185189: self.closeSec=1670515799, self.tradeDate='20221209', self.openTime='000000', self.closeTime='000959',self.symbol='BTCUSDT',self.open='16907.7', self.close='16904.9'
2022-12-09 00:10:01,790:INFO:pyemd2:main.py:126:handleKline:185189: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17420  20221208   232000    232959  1670513399  16895.5  16911.6
17421  20221208   233000    233959  1670513999  16911.7  16928.2
17422  20221208   234000    234959  1670514599  16928.2  16905.7
17423  20221208   235000    235959  1670515199  16905.7  16907.7
17424  20221209   000000    000959  1670515799  16907.7  16904.9
2022-12-09 00:10:01,790:INFO:pyemd2:main.py:127:handleKline:185189: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}


## /root/FIL/strategy/similarity/log.txt ----- -----

2022-12-09 00:00:01,105:INFO:testStrategy:main.py:102:handleKline:185174: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12235  20221208   231000    231959  1670512799    16911  16895.5
12236  20221208   232000    232959  1670513399  16895.5  16911.6
12237  20221208   233000    233959  1670513999  16911.7  16928.2
12238  20221208   234000    234959  1670514599  16928.2  16905.7
12239  20221208   235000    235959  1670515199  16905.7  16907.7
2022-12-09 00:00:01,105:INFO:testStrategy:main.py:103:handleKline:185174: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': True, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}
closeSell: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '78.543', 'enterprice': '16833.3', 'countrevence': '0', 'unrealprofit': '-5843.5992', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '16907.7', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
2022-12-09 00:00:02,116:INFO:testStrategy:main.py:253:closeSell:185174: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False, 'isCorr': False}
2022-12-09 00:00:02,116:INFO:testStrategy:main.py:254:closeSell:185174: ret = self.client.insertMarketUOrder("simulator",  BTCUSDT, 78.543, buy ), ret=InsertOrderReturn{'result': 'success', 'clientorderid': '41324F1670515202115I0L2'}
2022-12-09 00:00:02,143:INFO:testStrategy:main.py:172:insertFactor:185174: curDateTime:12090000, name:testStrategy, symbol:BTCUSDT, tradeDate:20221208, closeTime:235959, close:16907.7, total:1320815.7440181002, corrDate:20220924, corrVal:0.6454705801883388, side:buy 
127.0.0.1 - - [09/Dec/2022 00:00:02] "POST / HTTP/1.1" 200 -
2022-12-09 00:00:02,290:INFO:testStrategy:main.py:305:handleOrderNew:185174: handleOrderNew: data=OrderType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'clientorderid': '41324F1670515202115I0L2', 'symbol': 'BTCUSDT', 'gatewayorderid': 1670515202232373, 'quantity': '78.543', 'price': '16907.7', 'stopprice': '0', 'ordertype': '', 'side': 'BUY', 'status': 'FILLED', 'positionside': 'LONG', 'createtime': 1670515201384, 'updatetime': 1670515202232, 'tradetype': 'usdt', 'selfid': 41324, 'filltrades': [TradeType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'tradeid': 1670515202232, 'clientorderid': '41324F1670515202115I0L2', 'price': '16907.7', 'quantity': '78.543', 'commission': '1327.9814811', 'commissionasset': 'USDT', 'tradetime': 1670515202232, 'tradetype': 'usdt', 'gatetype': 'simulator', 'handletime': 1670515202232}], 'gatetype': 'simulator', 'handletime': 0}
127.0.0.1 - - [09/Dec/2022 00:00:02] "POST / HTTP/1.1" 200 -
2022-12-09 00:00:02,481:INFO:testStrategy:main.py:308:handleOrderFilled:185174: handleOrderFilled: data=OrderType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'clientorderid': '41324F1670515202115I0L2', 'symbol': 'BTCUSDT', 'gatewayorderid': 1670515202232373, 'quantity': '78.543', 'price': '16907.7', 'stopprice': '0', 'ordertype': '', 'side': 'BUY', 'status': 'FILLED', 'positionside': 'LONG', 'createtime': 1670515201384, 'updatetime': 1670515202232, 'tradetype': 'usdt', 'selfid': 41324, 'filltrades': [TradeType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'tradeid': 1670515202232, 'clientorderid': '41324F1670515202115I0L2', 'price': '16907.7', 'quantity': '78.543', 'commission': '1327.9814811', 'commissionasset': 'USDT', 'tradetime': 1670515202232, 'tradetype': 'usdt', 'gatetype': 'simulator', 'handletime': 1670515202232}], 'gatetype': 'simulator', 'handletime': 0}

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=1929 

self.closeSec=1670515799, self.tradeDate='20221209', self.openTime='000000', self.closeTime='000959', self.symbol='BTCUSDT', self.open='16907.7', self.close='16904.9'
2022-12-09 00:10:01,769:INFO:testStrategy:main.py:101:handleKline:185174: self.closeSec=1670515799, self.tradeDate='20221209', self.openTime='000000', self.closeTime='000959',self.symbol='BTCUSDT',self.open='16907.7', self.close='16904.9'
2022-12-09 00:10:01,774:INFO:testStrategy:main.py:102:handleKline:185174: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12236  20221208   232000    232959  1670513399  16895.5  16911.6
12237  20221208   233000    233959  1670513999  16911.7  16928.2
12238  20221208   234000    234959  1670514599  16928.2  16905.7
12239  20221208   235000    235959  1670515199  16905.7  16907.7
12240  20221209   000000    000959  1670515799  16907.7  16904.9
2022-12-09 00:10:01,774:INFO:testStrategy:main.py:103:handleKline:185174: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False, 'isCorr': False}
127.0.0.1 - - [09/Dec/2022 00:10:01] "POST / HTTP/1.1" 200 -


## /root/FIL/strategy/s_rsrs/log.txt ----- -----

723  20221208   120000    155959  1670486399  ...    723  0.947182  1.810544     1.0
724  20221208   160000    195959  1670500799  ...    724  0.959713  1.802969     1.0

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '58.622', 'enterprice': '17301.5', 'countrevence': '0', 'unrealprofit': '-26777.74265123736', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '16844.71342412', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=1, self.sign=1
127.0.0.1 - - [09/Dec/2022 00:00:00] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='s_rsrs', self.symbol='BTCUSDT', interval='4h', intervalSec=14400, wid=25, thd=0.6, self.sign=1, self.total=1013234.284467, self.flagDict['side']='buy', self.tradeCount=4, self.count=80
self.closeSec=1670515199, self.tradeDate='20221208', self.openTime='200000', self.closeTime='235959', self.symbol='BTCUSDT', self.open=16842.0, self.close=16907.7, self.high=16948.7, self.low=16792.8, self.vol=88430.186, self.amt=1491771817.1827 
2022-12-09 00:00:00,936:INFO:s_rsrs:main.py:141:handleKline:185271: self.closeSec=1670515199, self.tradeDate='20221208', self.openTime='200000', self.closeTime='235959',self.symbol='BTCUSDT',self.open=16842.0, self.close=16907.7, self.high=16948.7, self.low=16792.8, self.vol=88430.186, self.amt=1491771817.1827 
2022-12-09 00:00:00,953:INFO:s_rsrs:main.py:142:handleKline:185271: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime  ...        vol           amt       pct
721  20221208   040000    075959  ...  24456.653  4.114483e+08  0.001220
722  20221208   080000    115959  ...  38479.151  6.475756e+08 -0.000143
723  20221208   120000    155959  ...  28765.766  4.835081e+08 -0.000529
724  20221208   160000    195959  ...  44048.307  7.401749e+08  0.001499
725  20221208   200000    235959  ...  88430.186  1.491772e+09  0.003907

[5 rows x 11 columns]
2022-12-09 00:00:02,609:INFO:s_rsrs:main.py:151:handleKline:185271: df_s.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec  ...  index      beta    zscore  signal
721  20221208   040000    075959  1670457599  ...    721  0.877063  1.638632     1.0
722  20221208   080000    115959  1670471999  ...    722  0.895266  1.664155     1.0
723  20221208   120000    155959  1670486399  ...    723  0.947182  1.810544     1.0
724  20221208   160000    195959  1670500799  ...    724  0.959713  1.802969     1.0
725  20221208   200000    235959  1670515199  ...    725  0.958119  1.745379     1.0

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '58.622', 'enterprice': '17301.5', 'countrevence': '0', 'unrealprofit': '-23085.3436', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '16907.7', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=1, self.sign=1


