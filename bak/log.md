# 20230130 00:16:01

## /root/FIL/strategy/amihud/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=993672.4896432, self.flagDict['side']='sell', self.tradeCount=2, self.count=18266
self.closeSec=1675008599, self.tradeDate='20230130', self.openTime='000500', self.closeTime='000959', self.symbol='BTCUSDT', self.open=23564.9, self.close=23500.3, self.high=23569.9, self.low=23484.5, self.vol=2224.088, self.amt=52291807.076 
127.0.0.1 - - [30/Jan/2023 00:10:01] "POST / HTTP/1.1" 200 -
2023-01-30 00:10:01,503:INFO:amihud:main.py:172:handleKline:200676: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5757  20230129   234500    234959  ...         0.0        0.0       0
5758  20230129   235000    235459  ...         0.0        0.0       0
5759  20230129   235500    235959  ...         0.0        0.0       0
5760  20230130   000000    000459  ...         0.0        0.0       0
5761  20230130   000500    000959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-01-30 00:10:01,503:INFO:amihud:main.py:175:handleKline:200676: self.closeSec=1675008599, self.tradeDate='20230130', self.openTime='000500', self.closeTime='000959',self.symbol='BTCUSDT',self.open=23564.9, self.close=23500.3, self.high=23569.9, self.low=23484.5, self.vol=2224.088, self.amt=52291807.076, ukdf['pct'].iloc[-1]=-0.002657 , ukdf['amount'].iloc[-1]=52291807.076, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5761, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '60.176', 'enterprice': '16529.3', 'countrevence': '0', 'unrealprofit': '-419536.67553269008', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '23501.12723233', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1
127.0.0.1 - - [30/Jan/2023 00:15:00] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=993672.4896432, self.flagDict['side']='sell', self.tradeCount=2, self.count=18267
self.closeSec=1675008899, self.tradeDate='20230130', self.openTime='001000', self.closeTime='001459', self.symbol='BTCUSDT', self.open=23500.2, self.close=23529.2, self.high=23529.3, self.low=23473.7, self.vol=1872.473, self.amt=43999143.6903 
2023-01-30 00:15:00,792:INFO:amihud:main.py:172:handleKline:200676: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5758  20230129   235000    235459  ...         0.0        0.0       0
5759  20230129   235500    235959  ...         0.0        0.0       0
5760  20230130   000000    000459  ...         0.0        0.0       0
5761  20230130   000500    000959  ...         0.0        0.0       0
5762  20230130   001000    001459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-01-30 00:15:00,793:INFO:amihud:main.py:175:handleKline:200676: self.closeSec=1675008899, self.tradeDate='20230130', self.openTime='001000', self.closeTime='001459',self.symbol='BTCUSDT',self.open=23500.2, self.close=23529.2, self.high=23529.3, self.low=23473.7, self.vol=1872.473, self.amt=43999143.6903, ukdf['pct'].iloc[-1]=0.00123 , ukdf['amount'].iloc[-1]=43999143.6903, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5762, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '60.176', 'enterprice': '16529.3', 'countrevence': '0', 'unrealprofit': '-421083.73523542864', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '23526.83614789', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1


## /root/FIL/strategy/factorcheck/log.txt ----- -----

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=429, self.factor=0.3880681613307652, self.count=18832 

self.closeSec=1675008599, self.tradeDate='20230130', self.openTime='000500', self.closeTime='000959', self.symbol='BTCUSDT', self.open=23564.9, self.close=23500.3, self.high=23569.9, self.low=23484.5 
2023-01-30 00:10:01,424:INFO:factorcheck2:main.py:126:handleKline:185239: self.closeSec=1675008599, self.tradeDate='20230130', self.openTime='000500', self.closeTime='000959',self.symbol='BTCUSDT',self.open=23564.9, self.close=23500.3, self.high=23569.9, self.low=23484.5   
2023-01-30 00:10:01,456:INFO:factorcheck2:main.py:127:handleKline:185239: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1437  20230129   234500    234959  1675007399  ...  23530.0 -0.000488   1725    3
1438  20230129   235000    235459  1675007699  ...  23519.8 -0.000119   1726    4
1439  20230129   235500    235959  1675007999  ...  23518.3 -0.000310   1727    5
1440  20230130   000000    000459  1675008299  ...  23522.7  0.001709   1440    0
1441  20230130   000500    000959  1675008599  ...  23484.5 -0.002657   1441    1

[5 rows x 11 columns]
2023-01-30 00:10:01,456:INFO:factorcheck2:main.py:128:handleKline:185239: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}
127.0.0.1 - - [30/Jan/2023 00:15:00] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=429, self.factor=0.3880681613307652, self.count=18833 

self.closeSec=1675008899, self.tradeDate='20230130', self.openTime='001000', self.closeTime='001459', self.symbol='BTCUSDT', self.open=23500.2, self.close=23529.2, self.high=23529.3, self.low=23473.7 
2023-01-30 00:15:00,766:INFO:factorcheck2:main.py:126:handleKline:185239: self.closeSec=1675008899, self.tradeDate='20230130', self.openTime='001000', self.closeTime='001459',self.symbol='BTCUSDT',self.open=23500.2, self.close=23529.2, self.high=23529.3, self.low=23473.7   
2023-01-30 00:15:00,804:INFO:factorcheck2:main.py:127:handleKline:185239: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1438  20230129   235000    235459  1675007699  ...  23519.8 -0.000119   1726    4
1439  20230129   235500    235959  1675007999  ...  23518.3 -0.000310   1727    5
1440  20230130   000000    000459  1675008299  ...  23522.7  0.001709   1440    0
1441  20230130   000500    000959  1675008599  ...  23484.5 -0.002657   1441    1
1442  20230130   001000    001459  1675008899  ...  23473.7  0.001230   1442    2

[5 rows x 11 columns]
2023-01-30 00:15:00,806:INFO:factorcheck2:main.py:128:handleKline:185239: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}


## /root/FIL/strategy/logic/log.txt ----- -----

2023-01-30 00:00:18,652:DEBUG:logic:main.py:463:getModel:885513: df_s.iloc[-5:,:] :
          date closeTime     open  ...    alpha58   alpha67   alpha72
5802  20230129    212959  23481.7  ...  54.166667  0.611024  0.413193
5803  20230129    215959  23594.9  ...  54.166667  0.595344  0.398347
5804  20230129    222959  23538.0  ...  54.166667  0.581796  0.389019
5805  20230129    225959  23487.6  ...  54.166667  0.591726  0.375569
5806  20230129    232959  23540.5  ...  53.750000  0.580370  0.366846

[5 rows x 33 columns]
0.5349264705882353
acc is : 0.5349264705882353
2023-01-30 00:00:18,731:INFO:logic:main.py:468:getModel:885513: df_pred.iloc[-5:,:] :
     pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
539     0  0.551528  0.448472       0  ...  1.029087   1.0    0.0  1.104676
540     0  0.522325  0.477675       0  ...  1.026875   1.0    0.0  1.102301
541     0  0.515234  0.484766       1  ...  1.029192   1.0    0.0  1.104788
542     0  0.538585  0.461415       0  ...  1.027321   1.0    0.0  1.102780
543     0  0.512829  0.487171       1  ...  1.028414   1.0    0.0  1.103953

[5 rows x 10 columns]
2023-01-30 00:00:18,742:INFO:logic:main.py:478:getModel:885513: df_panel.iloc[-5:,:] :
    pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
45     0  0.552173  0.447827       0  ...  1.029087   1.0    0.0  1.106124
46     0  0.523965  0.476035       0  ...  0.998362   1.0    0.0  1.104920
47     0  0.516912  0.483088       1  ...  1.000615   1.0    0.0  1.107413
48     0  0.539407  0.460593       0  ...  1.027321   1.0    0.0  1.105015
49     0  0.512829  0.487171       1  ...  1.028414   1.0    0.0  1.103953

[5 rows x 10 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '30.8', 'enterprice': '23035.8', 'countrevence': '0', 'unrealprofit': '15070.604080224', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '23525.10532728', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}


## /root/FIL/strategy/modifiedmom/log.txt ----- -----

2023-01-30 00:00:02,385:INFO:modifiedmom:main.py:145:handleKline:185213: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
571  20230129   231000    231959  1675005599  23522.1  23509.8 -0.000523
572  20230129   232000    232959  1675006199  23509.8  23497.8 -0.000510
573  20230129   233000    233959  1675006799  23497.8  23511.2  0.000570
574  20230129   234000    234959  1675007399  23511.3  23532.8  0.000919
575  20230129   235000    235959  1675007999  23532.9  23522.7 -0.000429
2023-01-30 00:00:02,385:INFO:modifiedmom:main.py:146:handleKline:185213: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True}
closeBuy: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '40.752', 'enterprice': '23165.1', 'countrevence': '0', 'unrealprofit': '14581.92083614272', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '23522.92098636', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
2023-01-30 00:00:02,954:INFO:modifiedmom:main.py:267:closeBuy:185213: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False}
2023-01-30 00:00:02,954:INFO:modifiedmom:main.py:268:closeBuy:185213: ret = self.client.insertMarketUOrder("simulator",  BTCUSDT, 40.752, sell ), ret=InsertOrderReturn{'result': 'success', 'clientorderid': '41631F1675008002951I0L59'}
2023-01-30 00:00:03,025:INFO:modifiedmom:main.py:206:insertFactor:185213: curDateTime:1300000, name:modifiedmom, symbol:BTCUSDT, tradeDate:20230129, closeTime:235959, close:23522.7, total:943080.1310448, mom:0.0031165418347578466, thd:0.0, side:sell 
2023-01-30 00:00:03,355:INFO:modifiedmom:main.py:316:handleOrderNew:185213: handleOrderNew: data=OrderType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'clientorderid': '41631F1675008002951I0L59', 'symbol': 'BTCUSDT', 'gatewayorderid': 1675008003092218, 'quantity': '40.752', 'price': '23522.7', 'stopprice': '0', 'ordertype': '', 'side': 'SELL', 'status': 'FILLED', 'positionside': 'SHORT', 'createtime': 1675008002547, 'updatetime': 1675008003092, 'tradetype': 'usdt', 'selfid': 41631, 'filltrades': [TradeType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'tradeid': 1675008003092, 'clientorderid': '41631F1675008002951I0L59', 'price': '23522.7', 'quantity': '40.752', 'commission': '958.5970704', 'commissionasset': 'USDT', 'tradetime': 1675008003092, 'tradetype': 'usdt', 'gatetype': 'simulator', 'handletime': 1675008003092}], 'gatetype': 'simulator', 'handletime': 0}
127.0.0.1 - - [30/Jan/2023 00:00:03] "POST / HTTP/1.1" 200 -
2023-01-30 00:00:03,616:INFO:modifiedmom:main.py:319:handleOrderFilled:185213: handleOrderFilled: data=OrderType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'clientorderid': '41631F1675008002951I0L59', 'symbol': 'BTCUSDT', 'gatewayorderid': 1675008003092218, 'quantity': '40.752', 'price': '23522.7', 'stopprice': '0', 'ordertype': '', 'side': 'SELL', 'status': 'FILLED', 'positionside': 'SHORT', 'createtime': 1675008002547, 'updatetime': 1675008003092, 'tradetype': 'usdt', 'selfid': 41631, 'filltrades': [TradeType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'tradeid': 1675008003092, 'clientorderid': '41631F1675008002951I0L59', 'price': '23522.7', 'quantity': '40.752', 'commission': '958.5970704', 'commissionasset': 'USDT', 'tradetime': 1675008003092, 'tradetype': 'usdt', 'gatetype': 'simulator', 'handletime': 1675008003092}], 'gatetype': 'simulator', 'handletime': 0}
127.0.0.1 - - [30/Jan/2023 00:00:03] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [30/Jan/2023 00:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=9416 

self.closeSec=1675008599, self.tradeDate='20230130', self.openTime='000000', self.closeTime='000959', self.symbol='BTCUSDT', self.open='23522.7', self.close='23500.3'
2023-01-30 00:10:01,523:INFO:modifiedmom:main.py:144:handleKline:185213: self.closeSec=1675008599, self.tradeDate='20230130', self.openTime='000000', self.closeTime='000959',self.symbol='BTCUSDT',self.open='23522.7', self.close='23500.3'
2023-01-30 00:10:01,537:INFO:modifiedmom:main.py:145:handleKline:185213: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
572  20230129   232000    232959  1675006199  23509.8  23497.8 -0.000510
573  20230129   233000    233959  1675006799  23497.8  23511.2  0.000570
574  20230129   234000    234959  1675007399  23511.3  23532.8  0.000919
575  20230129   235000    235959  1675007999  23532.9  23522.7 -0.000429
576  20230130   000000    000959  1675008599  23522.7  23500.3 -0.000952
2023-01-30 00:10:01,539:INFO:modifiedmom:main.py:146:handleKline:185213: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False}


## /root/FIL/strategy/pyemd/log.txt ----- -----

2023-01-29 23:50:00,813:INFO:pyemd2:main.py:127:handleKline:185189: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}
127.0.0.1 - - [30/Jan/2023 00:00:02] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=9416 

self.closeSec=1675007999, self.tradeDate='20230129', self.openTime='235000', self.closeTime='235959', self.symbol='BTCUSDT', self.open='23532.9', self.close='23522.7'
2023-01-30 00:00:02,334:INFO:pyemd2:main.py:125:handleKline:185189: self.closeSec=1675007999, self.tradeDate='20230129', self.openTime='235000', self.closeTime='235959',self.symbol='BTCUSDT',self.open='23532.9', self.close='23522.7'
2023-01-30 00:00:02,390:INFO:pyemd2:main.py:126:handleKline:185189: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17419  20230129   231000    231959  1675005599  23522.1  23509.8
17420  20230129   232000    232959  1675006199  23509.8  23497.8
17421  20230129   233000    233959  1675006799  23497.8  23511.2
17422  20230129   234000    234959  1675007399  23511.3  23532.8
17423  20230129   235000    235959  1675007999  23532.9  23522.7
2023-01-30 00:00:02,390:INFO:pyemd2:main.py:127:handleKline:185189: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}
2023-01-30 00:00:02,486:INFO:pyemd2:main.py:190:insertFactor:185189: curDateTime:1300000, name:pyemd2, symbol:BTCUSDT, tradeDate:20230129, closeTime:235959, close:23522.7, total:949628.8116041, pct_pre:0.011815299074757757, thd:-0.10172771323732716, side:sell 
127.0.0.1 - - [30/Jan/2023 00:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=9417 

self.closeSec=1675008599, self.tradeDate='20230130', self.openTime='000000', self.closeTime='000959', self.symbol='BTCUSDT', self.open='23522.7', self.close='23500.3'
2023-01-30 00:10:01,528:INFO:pyemd2:main.py:125:handleKline:185189: self.closeSec=1675008599, self.tradeDate='20230130', self.openTime='000000', self.closeTime='000959',self.symbol='BTCUSDT',self.open='23522.7', self.close='23500.3'
2023-01-30 00:10:01,547:INFO:pyemd2:main.py:126:handleKline:185189: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17420  20230129   232000    232959  1675006199  23509.8  23497.8
17421  20230129   233000    233959  1675006799  23497.8  23511.2
17422  20230129   234000    234959  1675007399  23511.3  23532.8
17423  20230129   235000    235959  1675007999  23532.9  23522.7
17424  20230130   000000    000959  1675008599  23522.7  23500.3
2023-01-30 00:10:01,548:INFO:pyemd2:main.py:127:handleKline:185189: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}


## /root/FIL/strategy/similarity/log.txt ----- -----

2023-01-30 00:00:02,393:INFO:testStrategy:main.py:102:handleKline:185174: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12235  20230129   231000    231959  1675005599  23522.1  23509.8
12236  20230129   232000    232959  1675006199  23509.8  23497.8
12237  20230129   233000    233959  1675006799  23497.8  23511.2
12238  20230129   234000    234959  1675007399  23511.3  23532.8
12239  20230129   235000    235959  1675007999  23532.9  23522.7
2023-01-30 00:00:02,396:INFO:testStrategy:main.py:103:handleKline:185174: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': True, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}
closeSell: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '49.11', 'enterprice': '22969.9', 'countrevence': '0', 'unrealprofit': '-27158.8606401396', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '23522.92098636', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
2023-01-30 00:00:02,933:INFO:testStrategy:main.py:253:closeSell:185174: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False, 'isCorr': False}
2023-01-30 00:00:02,933:INFO:testStrategy:main.py:254:closeSell:185174: ret = self.client.insertMarketUOrder("simulator",  BTCUSDT, 49.11, buy ), ret=InsertOrderReturn{'result': 'success', 'clientorderid': '41630F1675008002930I0L2'}
2023-01-30 00:00:02,969:INFO:testStrategy:main.py:172:insertFactor:185174: curDateTime:1300000, name:testStrategy, symbol:BTCUSDT, tradeDate:20230129, closeTime:235959, close:23522.7, total:1126923.7372110002, corrDate:20221113, corrVal:0.6688150929888589, side:buy 
2023-01-30 00:00:03,094:INFO:testStrategy:main.py:305:handleOrderNew:185174: handleOrderNew: data=OrderType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'clientorderid': '41630F1675008002930I0L2', 'symbol': 'BTCUSDT', 'gatewayorderid': 1675008003044574, 'quantity': '49.11', 'price': '23522.8', 'stopprice': '0', 'ordertype': '', 'side': 'BUY', 'status': 'FILLED', 'positionside': 'LONG', 'createtime': 1675008002580, 'updatetime': 1675008003044, 'tradetype': 'usdt', 'selfid': 41630, 'filltrades': [TradeType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'tradeid': 1675008003044, 'clientorderid': '41630F1675008002930I0L2', 'price': '23522.8', 'quantity': '49.11', 'commission': '1155.204708', 'commissionasset': 'USDT', 'tradetime': 1675008003044, 'tradetype': 'usdt', 'gatetype': 'simulator', 'handletime': 1675008003044}], 'gatetype': 'simulator', 'handletime': 0}
127.0.0.1 - - [30/Jan/2023 00:00:03] "POST / HTTP/1.1" 200 -
2023-01-30 00:00:03,316:INFO:testStrategy:main.py:308:handleOrderFilled:185174: handleOrderFilled: data=OrderType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'clientorderid': '41630F1675008002930I0L2', 'symbol': 'BTCUSDT', 'gatewayorderid': 1675008003044574, 'quantity': '49.11', 'price': '23522.8', 'stopprice': '0', 'ordertype': '', 'side': 'BUY', 'status': 'FILLED', 'positionside': 'LONG', 'createtime': 1675008002580, 'updatetime': 1675008003044, 'tradetype': 'usdt', 'selfid': 41630, 'filltrades': [TradeType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'tradeid': 1675008003044, 'clientorderid': '41630F1675008002930I0L2', 'price': '23522.8', 'quantity': '49.11', 'commission': '1155.204708', 'commissionasset': 'USDT', 'tradetime': 1675008003044, 'tradetype': 'usdt', 'gatetype': 'simulator', 'handletime': 1675008003044}], 'gatetype': 'simulator', 'handletime': 0}
127.0.0.1 - - [30/Jan/2023 00:00:03] "POST / HTTP/1.1" 200 -

--handleKline--: 127.0.0.1 - - [30/Jan/2023 00:10:01] "POST / HTTP/1.1" 200 -
 self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=9417 

self.closeSec=1675008599, self.tradeDate='20230130', self.openTime='000000', self.closeTime='000959', self.symbol='BTCUSDT', self.open='23522.7', self.close='23500.3'
2023-01-30 00:10:01,551:INFO:testStrategy:main.py:101:handleKline:185174: self.closeSec=1675008599, self.tradeDate='20230130', self.openTime='000000', self.closeTime='000959',self.symbol='BTCUSDT',self.open='23522.7', self.close='23500.3'
2023-01-30 00:10:01,573:INFO:testStrategy:main.py:102:handleKline:185174: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12236  20230129   232000    232959  1675006199  23509.8  23497.8
12237  20230129   233000    233959  1675006799  23497.8  23511.2
12238  20230129   234000    234959  1675007399  23511.3  23532.8
12239  20230129   235000    235959  1675007999  23532.9  23522.7
12240  20230130   000000    000959  1675008599  23522.7  23500.3
2023-01-30 00:10:01,573:INFO:testStrategy:main.py:103:handleKline:185174: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False, 'isCorr': False}


## /root/FIL/strategy/sr_min/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=0, self.total=1000000.0, self.flagDict['side']='', self.tradeCount=0, self.count=14264
self.closeSec=1675008599, self.tradeDate='20230130', self.openTime='000500', self.closeTime='000959', self.symbol='BTCUSDT', self.open=23564.9, self.close=23500.3, self.high=23569.9, self.low=23484.5, self.vol=2224.088, self.amt=52291807.076 
127.0.0.1 - - [30/Jan/2023 00:10:01] "POST / HTTP/1.1" 200 -
2023-01-30 00:10:01,503:INFO:sr_min:main.py:172:handleKline:449472: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5757  20230129   234500    234959  ...         0.0        0.0       0
5758  20230129   235000    235459  ...         0.0        0.0       0
5759  20230129   235500    235959  ...         0.0        0.0       0
5760  20230130   000000    000459  ...         0.0        0.0       0
5761  20230130   000500    000959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-01-30 00:10:01,504:INFO:sr_min:main.py:175:handleKline:449472: self.closeSec=1675008599, self.tradeDate='20230130', self.openTime='000500', self.closeTime='000959',self.symbol='BTCUSDT',self.open=23564.9, self.close=23500.3, self.high=23569.9, self.low=23484.5, self.vol=2224.088, self.amt=52291807.076, ukdf['pct'].iloc[-1]=-0.002657 , ukdf['amount'].iloc[-1]=52291807.076, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5761, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': []}
type(curSign)=<class 'int'>, curSign=0, self.sign=0
127.0.0.1 - - [30/Jan/2023 00:15:00] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=0, self.total=1000000.0, self.flagDict['side']='', self.tradeCount=0, self.count=14265
self.closeSec=1675008899, self.tradeDate='20230130', self.openTime='001000', self.closeTime='001459', self.symbol='BTCUSDT', self.open=23500.2, self.close=23529.2, self.high=23529.3, self.low=23473.7, self.vol=1872.473, self.amt=43999143.6903 
2023-01-30 00:15:00,793:INFO:sr_min:main.py:172:handleKline:449472: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5758  20230129   235000    235459  ...         0.0        0.0       0
5759  20230129   235500    235959  ...         0.0        0.0       0
5760  20230130   000000    000459  ...         0.0        0.0       0
5761  20230130   000500    000959  ...         0.0        0.0       0
5762  20230130   001000    001459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-01-30 00:15:00,794:INFO:sr_min:main.py:175:handleKline:449472: self.closeSec=1675008899, self.tradeDate='20230130', self.openTime='001000', self.closeTime='001459',self.symbol='BTCUSDT',self.open=23500.2, self.close=23529.2, self.high=23529.3, self.low=23473.7, self.vol=1872.473, self.amt=43999143.6903, ukdf['pct'].iloc[-1]=0.00123 , ukdf['amount'].iloc[-1]=43999143.6903, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5762, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': []}
type(curSign)=<class 'int'>, curSign=0, self.sign=0


## /root/FIL/strategy/s_rsrs/log.txt ----- -----

723  20230129   120000    155959  1674979199  ...    723  0.154466 -0.965586    -1.0
724  20230129   160000    195959  1674993599  ...    724  0.191412 -0.857409    -1.0

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '41.738', 'enterprice': '22927.7', 'countrevence': '0', 'unrealprofit': '-21096.84276933468', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '23433.15888086', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-1, self.sign=-1
127.0.0.1 - - [30/Jan/2023 00:00:01] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='s_rsrs', self.symbol='BTCUSDT', interval='4h', intervalSec=14400, wid=25, thd=0.6, self.sign=-1, self.total=955999.3862573999, self.flagDict['side']='sell', self.tradeCount=15, self.count=392
self.closeSec=1675007999, self.tradeDate='20230129', self.openTime='200000', self.closeTime='235959', self.symbol='BTCUSDT', self.open=23430.0, self.close=23522.7, self.high=23675.8, self.low=23351.6, self.vol=88615.332, self.amt=2084092421.5594 
2023-01-30 00:00:01,878:INFO:s_rsrs:main.py:141:handleKline:185271: self.closeSec=1675007999, self.tradeDate='20230129', self.openTime='200000', self.closeTime='235959',self.symbol='BTCUSDT',self.open=23430.0, self.close=23522.7, self.high=23675.8, self.low=23351.6, self.vol=88615.332, self.amt=2084092421.5594 
2023-01-30 00:00:01,926:INFO:s_rsrs:main.py:142:handleKline:185271: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime  ...         vol           amt       pct
721  20230129   040000    075959  ...   20401.518  4.689237e+08 -0.000747
722  20230129   080000    115959  ...  125541.185  2.917320e+09  0.007564
723  20230129   120000    155959  ...   26823.648  6.224532e+08  0.000448
724  20230129   160000    195959  ...  114678.629  2.680838e+09  0.009896
725  20230129   200000    235959  ...   88615.332  2.084092e+09  0.003956

[5 rows x 11 columns]
2023-01-30 00:00:03,668:INFO:s_rsrs:main.py:151:handleKline:185271: df_s.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec  ...  index      beta    zscore  signal
721  20230129   040000    075959  1674950399  ...    721  0.142844 -1.020068    -1.0
722  20230129   080000    115959  1674964799  ...    722  0.220512 -0.822460    -1.0
723  20230129   120000    155959  1674979199  ...    723  0.154466 -0.965586    -1.0
724  20230129   160000    195959  1674993599  ...    724  0.191412 -0.857409    -1.0
725  20230129   200000    235959  1675007999  ...    725  0.200960 -0.816995    -1.0

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '41.738', 'enterprice': '22927.7', 'countrevence': '0', 'unrealprofit': '-24878.39473672836', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '23523.76101722', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-1, self.sign=-1


