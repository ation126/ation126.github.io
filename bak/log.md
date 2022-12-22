# 20221223 00:16:01

## /root/FIL/strategy/amihud/log.txt ----- -----

127.0.0.1 - - [23/Dec/2022 00:10:01] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=993672.4896432, self.flagDict['side']='sell', self.tradeCount=2, self.count=7322
self.closeSec=1671725399, self.tradeDate='20221223', self.openTime='000500', self.closeTime='000959', self.symbol='BTCUSDT', self.open=16638.6, self.close=16630.8, self.high=16644.9, self.low=16630.7, self.vol=1376.782, self.amt=22909563.6737 
2022-12-23 00:10:01,488:INFO:amihud:main.py:172:handleKline:200676: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5757  20221222   234500    234959  ...         0.0        0.0       0
5758  20221222   235000    235459  ...         0.0        0.0       0
5759  20221222   235500    235959  ...         0.0        0.0       0
5760  20221223   000000    000459  ...         0.0        0.0       0
5761  20221223   000500    000959  ...         0.0        0.0       0

[5 rows x 18 columns]
2022-12-23 00:10:01,489:INFO:amihud:main.py:175:handleKline:200676: self.closeSec=1671725399, self.tradeDate='20221223', self.openTime='000500', self.closeTime='000959',self.symbol='BTCUSDT',self.open=16638.6, self.close=16630.8, self.high=16644.9, self.low=16630.7, self.vol=1376.782, self.amt=22909563.6737, ukdf['pct'].iloc[-1]=-0.000511 , ukdf['amount'].iloc[-1]=22909563.6737, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5761, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '60.176', 'enterprice': '16529.3', 'countrevence': '0', 'unrealprofit': '-6150.48345161392', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '16631.50824667', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1
--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=993672.4896432, self.flagDict['side']='sell', self.tradeCount=2, self.count=7323
self.closeSec=1671725699, self.tradeDate='20221223', self.openTime='001000', self.closeTime='001459', self.symbol='BTCUSDT', self.open=16630.8, self.close=16626.6, self.high=16630.8, self.low=16615.5, self.vol=2136.69, self.amt=35514837.8104 
127.0.0.1 - - [23/Dec/2022 00:15:00] "POST / HTTP/1.1" 200 -
2022-12-23 00:15:00,590:INFO:amihud:main.py:172:handleKline:200676: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5758  20221222   235000    235459  ...         0.0        0.0       0
5759  20221222   235500    235959  ...         0.0        0.0       0
5760  20221223   000000    000459  ...         0.0        0.0       0
5761  20221223   000500    000959  ...         0.0        0.0       0
5762  20221223   001000    001459  ...         0.0        0.0       0

[5 rows x 18 columns]
2022-12-23 00:15:00,590:INFO:amihud:main.py:175:handleKline:200676: self.closeSec=1671725699, self.tradeDate='20221223', self.openTime='001000', self.closeTime='001459',self.symbol='BTCUSDT',self.open=16630.8, self.close=16626.6, self.high=16630.8, self.low=16615.5, self.vol=2136.69, self.amt=35514837.8104, ukdf['pct'].iloc[-1]=-0.000253 , ukdf['amount'].iloc[-1]=35514837.8104, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5762, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '60.176', 'enterprice': '16529.3', 'countrevence': '0', 'unrealprofit': '-5939.3712', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '16628', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1


## /root/FIL/strategy/factorcheck/log.txt ----- -----

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=70, self.factor=0.4426323963448493, self.count=7888 

self.closeSec=1671725399, self.tradeDate='20221223', self.openTime='000500', self.closeTime='000959', self.symbol='BTCUSDT', self.open=16638.6, self.close=16630.8, self.high=16644.9, self.low=16630.7 
2022-12-23 00:10:01,434:INFO:factorcheck2:main.py:126:handleKline:185239: self.closeSec=1671725399, self.tradeDate='20221223', self.openTime='000500', self.closeTime='000959',self.symbol='BTCUSDT',self.open=16638.6, self.close=16630.8, self.high=16644.9, self.low=16630.7   
2022-12-23 00:10:01,450:INFO:factorcheck2:main.py:127:handleKline:185239: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1437  20221222   234500    234959  1671724199  ...  16643.6  0.000534   1725    3
1438  20221222   235000    235459  1671724499  ...  16640.0 -0.001206   1726    4
1439  20221222   235500    235959  1671724799  ...  16600.0 -0.000517   1727    5
1440  20221223   000000    000459  1671725099  ...  16621.0  0.000469   1440    0
1441  20221223   000500    000959  1671725399  ...  16630.7 -0.000511   1441    1

[5 rows x 11 columns]
2022-12-23 00:10:01,450:INFO:factorcheck2:main.py:128:handleKline:185239: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}
127.0.0.1 - - [23/Dec/2022 00:15:00] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=70, self.factor=0.4426323963448493, self.count=7889 

self.closeSec=1671725699, self.tradeDate='20221223', self.openTime='001000', self.closeTime='001459', self.symbol='BTCUSDT', self.open=16630.8, self.close=16626.6, self.high=16630.8, self.low=16615.5 
2022-12-23 00:15:00,511:INFO:factorcheck2:main.py:126:handleKline:185239: self.closeSec=1671725699, self.tradeDate='20221223', self.openTime='001000', self.closeTime='001459',self.symbol='BTCUSDT',self.open=16630.8, self.close=16626.6, self.high=16630.8, self.low=16615.5   
2022-12-23 00:15:00,539:INFO:factorcheck2:main.py:127:handleKline:185239: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1438  20221222   235000    235459  1671724499  ...  16640.0 -0.001206   1726    4
1439  20221222   235500    235959  1671724799  ...  16600.0 -0.000517   1727    5
1440  20221223   000000    000459  1671725099  ...  16621.0  0.000469   1440    0
1441  20221223   000500    000959  1671725399  ...  16630.7 -0.000511   1441    1
1442  20221223   001000    001459  1671725699  ...  16615.5 -0.000253   1442    2

[5 rows x 11 columns]
2022-12-23 00:15:00,539:INFO:factorcheck2:main.py:128:handleKline:185239: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}


## /root/FIL/strategy/logic/log.txt ----- -----

2022-12-23 00:00:17,301:DEBUG:logic:main.py:454:getModel:174970: df_s.iloc[-5:,:] :
          date closeTime     open  ...    alpha58   alpha67   alpha72
5802  20221222    212959  16808.3  ...  50.833333  0.493089  0.427336
5803  20221222    215959  16793.2  ...  50.416667  0.482312  0.438690
5804  20221222    222959  16775.3  ...  50.000000  0.473304  0.456787
5805  20221222    225959  16759.0  ...  50.000000  0.427472  0.481144
5806  20221222    232959  16667.3  ...  50.000000  0.433756  0.499965

[5 rows x 33 columns]
0.5202205882352942
acc is : 0.5202205882352942
2022-12-23 00:00:17,406:INFO:logic:main.py:459:getModel:174970: df_pred.iloc[-5:,:] :
     pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
539     1  0.490686  0.509314       0  ...  1.096307   1.0    0.0  0.976819
540     1  0.487913  0.512087       0  ...  1.095242   1.0    0.0  0.975870
541     1  0.484681  0.515319       0  ...  1.089249   1.0    0.0  0.970530
542     1  0.457973  0.542027       1  ...  1.089922   1.0    0.0  0.971130
543     1  0.483365  0.516635       0  ...  1.086910   1.0    0.0  0.968445

[5 rows x 10 columns]
2022-12-23 00:00:17,429:INFO:logic:main.py:469:getModel:174970: df_panel.iloc[-5:,:] :
    pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
45     1  0.490934  0.509066       0  ...  1.096307   1.0    0.0  0.977001
46     1  0.488461  0.511539       0  ...  1.095242   1.0    0.0  0.976461
47     1  0.485230  0.514770       0  ...  1.089249   1.0    0.0  0.971118
48     1  0.458262  0.541738       1  ...  1.089922   1.0    0.0  0.971492
49     1  0.483365  0.516635       0  ...  1.086910   1.0    0.0  0.968445

[5 rows x 10 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '42.528', 'enterprice': '16701.5', 'countrevence': '0', 'unrealprofit': '-3232.128', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '16625.5', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}


## /root/FIL/strategy/modifiedmom/log.txt ----- -----

2022-12-23 00:00:01,294:INFO:modifiedmom:main.py:145:handleKline:185213: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
571  20221222   231000    231959  1671722399  16655.8  16698.6  0.002570
572  20221222   232000    232959  1671722999  16698.6  16677.6 -0.001258
573  20221222   233000    233959  1671723599  16677.6  16656.3 -0.001277
574  20221222   234000    234959  1671724199  16656.4  16660.2  0.000234
575  20221222   235000    235959  1671724799  16660.1  16631.5 -0.001723
2022-12-23 00:00:01,294:INFO:modifiedmom:main.py:146:handleKline:185213: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True}
closeBuy: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '56.183', 'enterprice': '16834.4', 'countrevence': '0', 'unrealprofit': '-11399.5307', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '16631.5', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
2022-12-23 00:00:01,946:INFO:modifiedmom:main.py:267:closeBuy:185213: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False}
2022-12-23 00:00:01,946:INFO:modifiedmom:main.py:268:closeBuy:185213: ret = self.client.insertMarketUOrder("simulator",  BTCUSDT, 56.183, sell ), ret=InsertOrderReturn{'result': 'success', 'clientorderid': '41405F1671724801937I0L59'}
2022-12-23 00:00:01,976:INFO:modifiedmom:main.py:206:insertFactor:185213: curDateTime:12230000, name:modifiedmom, symbol:BTCUSDT, tradeDate:20221222, closeTime:235959, close:16631.5, total:944861.2881048, mom:0.0007500037861996045, thd:0.0, side:sell 
2022-12-23 00:00:02,090:INFO:modifiedmom:main.py:316:handleOrderNew:185213: handleOrderNew: data=OrderType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'clientorderid': '41405F1671724801937I0L59', 'symbol': 'BTCUSDT', 'gatewayorderid': 1671724802055934, 'quantity': '56.183', 'price': '16631.5', 'stopprice': '0', 'ordertype': '', 'side': 'SELL', 'status': 'FILLED', 'positionside': 'SHORT', 'createtime': 1671724801583, 'updatetime': 1671724802055, 'tradetype': 'usdt', 'selfid': 41405, 'filltrades': [TradeType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'tradeid': 1671724802055, 'clientorderid': '41405F1671724801937I0L59', 'price': '16631.5', 'quantity': '56.183', 'commission': '934.4075645', 'commissionasset': 'USDT', 'tradetime': 1671724802055, 'tradetype': 'usdt', 'gatetype': 'simulator', 'handletime': 1671724802055}], 'gatetype': 'simulator', 'handletime': 0}
127.0.0.1 - - [23/Dec/2022 00:00:02] "POST / HTTP/1.1" 200 -
2022-12-23 00:00:02,320:INFO:modifiedmom:main.py:319:handleOrderFilled:185213: handleOrderFilled: data=OrderType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'clientorderid': '41405F1671724801937I0L59', 'symbol': 'BTCUSDT', 'gatewayorderid': 1671724802055934, 'quantity': '56.183', 'price': '16631.5', 'stopprice': '0', 'ordertype': '', 'side': 'SELL', 'status': 'FILLED', 'positionside': 'SHORT', 'createtime': 1671724801583, 'updatetime': 1671724802055, 'tradetype': 'usdt', 'selfid': 41405, 'filltrades': [TradeType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'tradeid': 1671724802055, 'clientorderid': '41405F1671724801937I0L59', 'price': '16631.5', 'quantity': '56.183', 'commission': '934.4075645', 'commissionasset': 'USDT', 'tradetime': 1671724802055, 'tradetype': 'usdt', 'gatetype': 'simulator', 'handletime': 1671724802055}], 'gatetype': 'simulator', 'handletime': 0}
127.0.0.1 - - [23/Dec/2022 00:00:02] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=3944 

self.closeSec=1671725399, self.tradeDate='20221223', self.openTime='000000', self.closeTime='000959', self.symbol='BTCUSDT', self.open='16631.5', self.close='16630.8'
2022-12-23 00:10:01,539:INFO:modifiedmom:main.py:144:handleKline:185213: self.closeSec=1671725399, self.tradeDate='20221223', self.openTime='000000', self.closeTime='000959',self.symbol='BTCUSDT',self.open='16631.5', self.close='16630.8'
127.0.0.1 - - [23/Dec/2022 00:10:01] "POST / HTTP/1.1" 200 -
2022-12-23 00:10:01,571:INFO:modifiedmom:main.py:145:handleKline:185213: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
572  20221222   232000    232959  1671722999  16698.6  16677.6 -0.001258
573  20221222   233000    233959  1671723599  16677.6  16656.3 -0.001277
574  20221222   234000    234959  1671724199  16656.4  16660.2  0.000234
575  20221222   235000    235959  1671724799  16660.1  16631.5 -0.001723
576  20221223   000000    000959  1671725399  16631.5  16630.8 -0.000042
2022-12-23 00:10:01,571:INFO:modifiedmom:main.py:146:handleKline:185213: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False}


## /root/FIL/strategy/pyemd/log.txt ----- -----

2022-12-22 23:50:00,588:INFO:pyemd2:main.py:127:handleKline:185189: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}
127.0.0.1 - - [23/Dec/2022 00:00:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=3944 

self.closeSec=1671724799, self.tradeDate='20221222', self.openTime='235000', self.closeTime='235959', self.symbol='BTCUSDT', self.open='16660.1', self.close='16631.5'
2022-12-23 00:00:01,249:INFO:pyemd2:main.py:125:handleKline:185189: self.closeSec=1671724799, self.tradeDate='20221222', self.openTime='235000', self.closeTime='235959',self.symbol='BTCUSDT',self.open='16660.1', self.close='16631.5'
2022-12-23 00:00:01,327:INFO:pyemd2:main.py:126:handleKline:185189: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17419  20221222   231000    231959  1671722399  16655.8  16698.6
17420  20221222   232000    232959  1671722999  16698.6  16677.6
17421  20221222   233000    233959  1671723599  16677.6  16656.3
17422  20221222   234000    234959  1671724199  16656.4  16660.2
17423  20221222   235000    235959  1671724799  16660.1  16631.5
2022-12-23 00:00:01,327:INFO:pyemd2:main.py:127:handleKline:185189: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}
2022-12-23 00:00:01,527:INFO:pyemd2:main.py:190:insertFactor:185189: curDateTime:12230000, name:pyemd2, symbol:BTCUSDT, tradeDate:20221222, closeTime:235959, close:16631.5, total:946635.6384771, pct_pre:-0.00038584369175242994, thd:0.1763722255680359, side:sell 
127.0.0.1 - - [23/Dec/2022 00:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=3945 

self.closeSec=1671725399, self.tradeDate='20221223', self.openTime='000000', self.closeTime='000959', self.symbol='BTCUSDT', self.open='16631.5', self.close='16630.8'
2022-12-23 00:10:01,536:INFO:pyemd2:main.py:125:handleKline:185189: self.closeSec=1671725399, self.tradeDate='20221223', self.openTime='000000', self.closeTime='000959',self.symbol='BTCUSDT',self.open='16631.5', self.close='16630.8'
2022-12-23 00:10:01,551:INFO:pyemd2:main.py:126:handleKline:185189: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17420  20221222   232000    232959  1671722999  16698.6  16677.6
17421  20221222   233000    233959  1671723599  16677.6  16656.3
17422  20221222   234000    234959  1671724199  16656.4  16660.2
17423  20221222   235000    235959  1671724799  16660.1  16631.5
17424  20221223   000000    000959  1671725399  16631.5  16630.8
2022-12-23 00:10:01,552:INFO:pyemd2:main.py:127:handleKline:185189: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}


## /root/FIL/strategy/similarity/log.txt ----- -----

2022-12-23 00:00:01,289:INFO:testStrategy:main.py:102:handleKline:185174: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12235  20221222   231000    231959  1671722399  16655.8  16698.6
12236  20221222   232000    232959  1671722999  16698.6  16677.6
12237  20221222   233000    233959  1671723599  16677.6  16656.3
12238  20221222   234000    234959  1671724199  16656.4  16660.2
12239  20221222   235000    235959  1671724799  16660.1  16631.5
2022-12-23 00:00:01,293:INFO:testStrategy:main.py:103:handleKline:185174: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}
closeBuy: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '75.796', 'enterprice': '16758.4', 'countrevence': '0', 'unrealprofit': '-9618.5124', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '16631.5', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
2022-12-23 00:00:01,880:INFO:testStrategy:main.py:233:closeBuy:185174: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False, 'isCorr': False}
2022-12-23 00:00:01,880:INFO:testStrategy:main.py:234:closeBuy:185174: ret = self.client.insertMarketUOrder("simulator",  BTCUSDT, 75.796, sell ), ret=InsertOrderReturn{'result': 'success', 'clientorderid': '41404F1671724801878I0L2'}
2022-12-23 00:00:01,916:INFO:testStrategy:main.py:172:insertFactor:185174: curDateTime:12230000, name:testStrategy, symbol:BTCUSDT, tradeDate:20221222, closeTime:235959, close:16631.5, total:1268949.4667136003, corrDate:20221206, corrVal:0.7697352896760372, side:sell 
127.0.0.1 - - [23/Dec/2022 00:00:02] "POST / HTTP/1.1" 200 -
2022-12-23 00:00:02,335:INFO:testStrategy:main.py:305:handleOrderNew:185174: handleOrderNew: data=OrderType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'clientorderid': '41404F1671724801878I0L2', 'symbol': 'BTCUSDT', 'gatewayorderid': 1671724802257967, 'quantity': '75.796', 'price': '16631.5', 'stopprice': '0', 'ordertype': '', 'side': 'SELL', 'status': 'FILLED', 'positionside': 'SHORT', 'createtime': 1671724801517, 'updatetime': 1671724802257, 'tradetype': 'usdt', 'selfid': 41404, 'filltrades': [TradeType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'tradeid': 1671724802257, 'clientorderid': '41404F1671724801878I0L2', 'price': '16631.5', 'quantity': '75.796', 'commission': '1260.601174', 'commissionasset': 'USDT', 'tradetime': 1671724802257, 'tradetype': 'usdt', 'gatetype': 'simulator', 'handletime': 1671724802257}], 'gatetype': 'simulator', 'handletime': 0}
2022-12-23 00:00:02,557:INFO:testStrategy:main.py:308:handleOrderFilled:185174: handleOrderFilled: data=OrderType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'clientorderid': '41404F1671724801878I0L2', 'symbol': 'BTCUSDT', 'gatewayorderid': 1671724802257967, 'quantity': '75.796', 'price': '16631.5', 'stopprice': '0', 'ordertype': '', 'side': 'SELL', 'status': 'FILLED', 'positionside': 'SHORT', 'createtime': 1671724801517, 'updatetime': 1671724802257, 'tradetype': 'usdt', 'selfid': 41404, 'filltrades': [TradeType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'tradeid': 1671724802257, 'clientorderid': '41404F1671724801878I0L2', 'price': '16631.5', 'quantity': '75.796', 'commission': '1260.601174', 'commissionasset': 'USDT', 'tradetime': 1671724802257, 'tradetype': 'usdt', 'gatetype': 'simulator', 'handletime': 1671724802257}], 'gatetype': 'simulator', 'handletime': 0}
127.0.0.1 - - [23/Dec/2022 00:00:02] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [23/Dec/2022 00:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=3945 

self.closeSec=1671725399, self.tradeDate='20221223', self.openTime='000000', self.closeTime='000959', self.symbol='BTCUSDT', self.open='16631.5', self.close='16630.8'
2022-12-23 00:10:01,533:INFO:testStrategy:main.py:101:handleKline:185174: self.closeSec=1671725399, self.tradeDate='20221223', self.openTime='000000', self.closeTime='000959',self.symbol='BTCUSDT',self.open='16631.5', self.close='16630.8'
2022-12-23 00:10:01,550:INFO:testStrategy:main.py:102:handleKline:185174: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12236  20221222   232000    232959  1671722999  16698.6  16677.6
12237  20221222   233000    233959  1671723599  16677.6  16656.3
12238  20221222   234000    234959  1671724199  16656.4  16660.2
12239  20221222   235000    235959  1671724799  16660.1  16631.5
12240  20221223   000000    000959  1671725399  16631.5  16630.8
2022-12-23 00:10:01,550:INFO:testStrategy:main.py:103:handleKline:185174: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False, 'isCorr': False}


## /root/FIL/strategy/sr_min/log.txt ----- -----

127.0.0.1 - - [23/Dec/2022 00:10:01] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=0, self.total=1000000.0, self.flagDict['side']='', self.tradeCount=0, self.count=3320
self.closeSec=1671725399, self.tradeDate='20221223', self.openTime='000500', self.closeTime='000959', self.symbol='BTCUSDT', self.open=16638.6, self.close=16630.8, self.high=16644.9, self.low=16630.7, self.vol=1376.782, self.amt=22909563.6737 
2022-12-23 00:10:01,478:INFO:sr_min:main.py:172:handleKline:449472: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5757  20221222   234500    234959  ...         0.0        0.0       0
5758  20221222   235000    235459  ...         0.0        0.0       0
5759  20221222   235500    235959  ...         0.0        0.0       0
5760  20221223   000000    000459  ...         0.0        0.0       0
5761  20221223   000500    000959  ...         0.0        0.0       0

[5 rows x 18 columns]
2022-12-23 00:10:01,478:INFO:sr_min:main.py:175:handleKline:449472: self.closeSec=1671725399, self.tradeDate='20221223', self.openTime='000500', self.closeTime='000959',self.symbol='BTCUSDT',self.open=16638.6, self.close=16630.8, self.high=16644.9, self.low=16630.7, self.vol=1376.782, self.amt=22909563.6737, ukdf['pct'].iloc[-1]=-0.000511 , ukdf['amount'].iloc[-1]=22909563.6737, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5761, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': []}
type(curSign)=<class 'int'>, curSign=0, self.sign=0
--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=0, self.total=1000000.0, self.flagDict['side']='', self.tradeCount=0, self.count=3321
self.closeSec=1671725699, self.tradeDate='20221223', self.openTime='001000', self.closeTime='001459', self.symbol='BTCUSDT', self.open=16630.8, self.close=16626.6, self.high=16630.8, self.low=16615.5, self.vol=2136.69, self.amt=35514837.8104 
127.0.0.1 - - [23/Dec/2022 00:15:00] "POST / HTTP/1.1" 200 -
2022-12-23 00:15:00,549:INFO:sr_min:main.py:172:handleKline:449472: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5758  20221222   235000    235459  ...         0.0        0.0       0
5759  20221222   235500    235959  ...         0.0        0.0       0
5760  20221223   000000    000459  ...         0.0        0.0       0
5761  20221223   000500    000959  ...         0.0        0.0       0
5762  20221223   001000    001459  ...         0.0        0.0       0

[5 rows x 18 columns]
2022-12-23 00:15:00,550:INFO:sr_min:main.py:175:handleKline:449472: self.closeSec=1671725699, self.tradeDate='20221223', self.openTime='001000', self.closeTime='001459',self.symbol='BTCUSDT',self.open=16630.8, self.close=16626.6, self.high=16630.8, self.low=16615.5, self.vol=2136.69, self.amt=35514837.8104, ukdf['pct'].iloc[-1]=-0.000253 , ukdf['amount'].iloc[-1]=35514837.8104, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5762, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': []}
type(curSign)=<class 'int'>, curSign=0, self.sign=0


## /root/FIL/strategy/s_rsrs/log.txt ----- -----

723  20221222   120000    155959  1671695999  ...    723  0.036387 -1.774678    -1.0
724  20221222   160000    195959  1671710399  ...    724  0.037604 -1.720944    -1.0

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '53.372', 'enterprice': '16723.1', 'countrevence': '0', 'unrealprofit': '-5591.51504376256', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '16827.86495248', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-1, self.sign=-1
--handleKline--:  version='2.0.0', self.name='s_rsrs', self.symbol='BTCUSDT', interval='4h', intervalSec=14400, wid=25, thd=0.6, self.sign=-1, self.total=891652.7479068, self.flagDict['side']='sell', self.tradeCount=7, self.count=164
self.closeSec=1671724799, self.tradeDate='20221222', self.openTime='200000', self.closeTime='235959', self.symbol='BTCUSDT', self.open=16827.6, self.close=16631.5, self.high=16837.6, self.low=16600.0, self.vol=98813.975, self.amt=1650437367.7164 
127.0.0.1 - - [23/Dec/2022 00:00:01] "POST / HTTP/1.1" 200 -
2022-12-23 00:00:01,096:INFO:s_rsrs:main.py:141:handleKline:185271: self.closeSec=1671724799, self.tradeDate='20221222', self.openTime='200000', self.closeTime='235959',self.symbol='BTCUSDT',self.open=16827.6, self.close=16631.5, self.high=16837.6, self.low=16600.0, self.vol=98813.975, self.amt=1650437367.7164 
2022-12-23 00:00:01,143:INFO:s_rsrs:main.py:142:handleKline:185271: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime  ...        vol           amt       pct
721  20221222   040000    075959  ...  26341.897  4.417508e+08  0.004646
722  20221222   080000    115959  ...  19468.471  3.276365e+08  0.001183
723  20221222   120000    155959  ...  20542.365  3.453780e+08 -0.001454
724  20221222   160000    195959  ...  27422.375  4.614884e+08  0.000452
725  20221222   200000    235959  ...  98813.975  1.650437e+09 -0.011653

[5 rows x 11 columns]
2022-12-23 00:00:02,824:INFO:s_rsrs:main.py:151:handleKline:185271: df_s.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec  ...  index      beta    zscore  signal
721  20221222   040000    075959  1671667199  ...    721  0.036546 -1.883876    -1.0
722  20221222   080000    115959  1671681599  ...    722  0.035492 -1.830501    -1.0
723  20221222   120000    155959  1671695999  ...    723  0.036387 -1.774678    -1.0
724  20221222   160000    195959  1671710399  ...    724  0.037604 -1.720944    -1.0
725  20221222   200000    235959  1671724799  ...    725  0.035780 -1.677523    -1.0

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '53.372', 'enterprice': '16723.1', 'countrevence': '0', 'unrealprofit': '4888.8752', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '16631.5', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-1, self.sign=-1


