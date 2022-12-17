# 20221218 00:16:01

## /root/FIL/strategy/amihud/log.txt ----- -----

127.0.0.1 - - [18/Dec/2022 00:10:01] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=993672.4896432, self.flagDict['side']='sell', self.tradeCount=2, self.count=5882
self.closeSec=1671293399, self.tradeDate='20221218', self.openTime='000500', self.closeTime='000959', self.symbol='BTCUSDT', self.open=16687.4, self.close=16684.6, self.high=16688.3, self.low=16683.9, self.vol=368.606, self.amt=6150360.716 
2022-12-18 00:10:01,473:INFO:amihud:main.py:172:handleKline:200676: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5757  20221217   234500    234959  ...         0.0        0.0       0
5758  20221217   235000    235459  ...         0.0        0.0       0
5759  20221217   235500    235959  ...         0.0        0.0       0
5760  20221218   000000    000459  ...         0.0        0.0       0
5761  20221218   000500    000959  ...         0.0        0.0       0

[5 rows x 18 columns]
2022-12-18 00:10:01,474:INFO:amihud:main.py:175:handleKline:200676: self.closeSec=1671293399, self.tradeDate='20221218', self.openTime='000500', self.closeTime='000959',self.symbol='BTCUSDT',self.open=16687.4, self.close=16684.6, self.high=16688.3, self.low=16683.9, self.vol=368.606, self.amt=6150360.716, ukdf['pct'].iloc[-1]=-0.000168 , ukdf['amount'].iloc[-1]=6150360.716, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5761, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '60.176', 'enterprice': '16529.3', 'countrevence': '0', 'unrealprofit': '-9380.41399025344', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '16685.18297644', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1
127.0.0.1 - - [18/Dec/2022 00:15:00] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=993672.4896432, self.flagDict['side']='sell', self.tradeCount=2, self.count=5883
self.closeSec=1671293699, self.tradeDate='20221218', self.openTime='001000', self.closeTime='001459', self.symbol='BTCUSDT', self.open=16684.7, self.close=16680.8, self.high=16686.6, self.low=16680.8, self.vol=368.44, self.amt=6146832.5243 
2022-12-18 00:15:00,646:INFO:amihud:main.py:172:handleKline:200676: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5758  20221217   235000    235459  ...         0.0        0.0       0
5759  20221217   235500    235959  ...         0.0        0.0       0
5760  20221218   000000    000459  ...         0.0        0.0       0
5761  20221218   000500    000959  ...         0.0        0.0       0
5762  20221218   001000    001459  ...         0.0        0.0       0

[5 rows x 18 columns]
2022-12-18 00:15:00,648:INFO:amihud:main.py:175:handleKline:200676: self.closeSec=1671293699, self.tradeDate='20221218', self.openTime='001000', self.closeTime='001459',self.symbol='BTCUSDT',self.open=16684.7, self.close=16680.8, self.high=16686.6, self.low=16680.8, self.vol=368.44, self.amt=6146832.5243, ukdf['pct'].iloc[-1]=-0.000228 , ukdf['amount'].iloc[-1]=6146832.5243, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5762, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '60.176', 'enterprice': '16529.3', 'countrevence': '0', 'unrealprofit': '-9126.23747987408', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '16680.95909133', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1


## /root/FIL/strategy/factorcheck/log.txt ----- -----


self.closeSec=1671293399, self.tradeDate='20221218', self.openTime='000500', self.closeTime='000959', self.symbol='BTCUSDT', self.open=16687.4, self.close=16684.6, self.high=16688.3, self.low=16683.9 
2022-12-18 00:10:01,408:INFO:factorcheck2:main.py:126:handleKline:185239: self.closeSec=1671293399, self.tradeDate='20221218', self.openTime='000500', self.closeTime='000959',self.symbol='BTCUSDT',self.open=16687.4, self.close=16684.6, self.high=16688.3, self.low=16683.9   
127.0.0.1 - - [18/Dec/2022 00:10:01] "POST / HTTP/1.1" 200 -
2022-12-18 00:10:01,433:INFO:factorcheck2:main.py:127:handleKline:185239: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1437  20221217   234500    234959  1671292199  ...  16676.6 -0.000456   1725    3
1438  20221217   235000    235459  1671292499  ...  16675.0  0.001061   1726    4
1439  20221217   235500    235959  1671292799  ...  16677.8 -0.000156   1727    5
1440  20221218   000000    000459  1671293099  ...  16685.6 -0.000300   1440    0
1441  20221218   000500    000959  1671293399  ...  16683.9 -0.000168   1441    1

[5 rows x 11 columns]
2022-12-18 00:10:01,434:INFO:factorcheck2:main.py:128:handleKline:185239: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': False, 'isOpen': True, 'isClose': False, 'isTrig': True}

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.7834646795388475, self.count=6449 

self.closeSec=1671293699, self.tradeDate='20221218', self.openTime='001000', self.closeTime='001459', self.symbol='BTCUSDT', self.open=16684.7, self.close=16680.8, self.high=16686.6, self.low=16680.8 
2022-12-18 00:15:00,516:INFO:factorcheck2:main.py:126:handleKline:185239: self.closeSec=1671293699, self.tradeDate='20221218', self.openTime='001000', self.closeTime='001459',self.symbol='BTCUSDT',self.open=16684.7, self.close=16680.8, self.high=16686.6, self.low=16680.8   
127.0.0.1 - - [18/Dec/2022 00:15:00] "POST / HTTP/1.1" 200 -
2022-12-18 00:15:00,600:INFO:factorcheck2:main.py:127:handleKline:185239: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1438  20221217   235000    235459  1671292499  ...  16675.0  0.001061   1726    4
1439  20221217   235500    235959  1671292799  ...  16677.8 -0.000156   1727    5
1440  20221218   000000    000459  1671293099  ...  16685.6 -0.000300   1440    0
1441  20221218   000500    000959  1671293399  ...  16683.9 -0.000168   1441    1
1442  20221218   001000    001459  1671293699  ...  16680.8 -0.000228   1442    2

[5 rows x 11 columns]
2022-12-18 00:15:00,600:INFO:factorcheck2:main.py:128:handleKline:185239: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': False, 'isOpen': True, 'isClose': False, 'isTrig': True}


## /root/FIL/strategy/logic/log.txt ----- -----

2022-12-18 00:00:18,811:DEBUG:logic:main.py:454:getModel:174970: df_s.iloc[-5:,:] :
          date closeTime     open  ...    alpha58   alpha67   alpha72
5802  20221217    212959  16685.9  ...  47.500000  0.388974  0.705827
5803  20221217    215959  16656.6  ...  47.916667  0.390883  0.703405
5804  20221217    222959  16661.3  ...  47.916667  0.398280  0.698176
5805  20221217    225959  16680.3  ...  47.500000  0.388971  0.699028
5806  20221217    232959  16643.8  ...  47.500000  0.401715  0.694703

[5 rows x 33 columns]
0.5533088235294118
acc is : 0.5533088235294118
2022-12-18 00:00:18,925:INFO:logic:main.py:459:getModel:174970: df_pred.iloc[-5:,:] :
     pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
539     1  0.492611  0.507389       1  ...  1.080023  -1.0    0.0  0.980446
540     0  0.503922  0.496078       1  ...  1.078798  -1.0    0.0  0.981558
541     0  0.510990  0.489010       0  ...  1.081158  -1.0    0.0  0.979410
542     1  0.492995  0.507005       1  ...  1.079041  -1.0    0.0  0.981328
543     0  0.510698  0.489302       1  ...  1.078005  -1.0    0.0  0.982270

[5 rows x 10 columns]
2022-12-18 00:00:18,946:INFO:logic:main.py:469:getModel:174970: df_panel.iloc[-5:,:] :
    pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
45     1  0.492283  0.507717       1  ...  1.080023  -1.0    0.0  0.980417
46     0  0.503742  0.496258       1  ...  1.078798  -1.0    0.0  0.981552
47     0  0.510788  0.489212       0  ...  1.081158  -1.0    0.0  0.979404
48     1  0.492675  0.507325       1  ...  1.079041  -1.0    0.0  0.980965
49     0  0.510698  0.489302       1  ...  1.078005  -1.0    0.0  0.982270

[5 rows x 10 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '37.704', 'enterprice': '17770', 'countrevence': '0', 'unrealprofit': '40629.8304', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '16692.4', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}


## /root/FIL/strategy/modifiedmom/log.txt ----- -----

2022-12-18 00:00:01,138:INFO:modifiedmom:main.py:145:handleKline:185213: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
571  20221217   231000    231959  1671290399  16659.8  16661.1  0.000078
572  20221217   232000    232959  1671290999  16661.2  16677.6  0.000990
573  20221217   233000    233959  1671291599  16677.6    16680  0.000144
574  20221217   234000    234959  1671292199  16679.9  16677.4 -0.000156
575  20221217   235000    235959  1671292799  16677.3  16692.4  0.000899
2022-12-18 00:00:01,139:INFO:modifiedmom:main.py:146:handleKline:185213: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True}
closeBuy: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '57.474', 'enterprice': '16688', 'countrevence': '0', 'unrealprofit': '247.1382', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '16692.3', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
2022-12-18 00:00:01,934:INFO:modifiedmom:main.py:267:closeBuy:185213: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False}
2022-12-18 00:00:01,934:INFO:modifiedmom:main.py:268:closeBuy:185213: ret = self.client.insertMarketUOrder("simulator",  BTCUSDT, 57.474, sell ), ret=InsertOrderReturn{'result': 'success', 'clientorderid': '41375F1671292801930I0L59'}
2022-12-18 00:00:01,975:INFO:modifiedmom:main.py:206:insertFactor:185213: curDateTime:12180000, name:modifiedmom, symbol:BTCUSDT, tradeDate:20221217, closeTime:235959, close:16692.4, total:958166.985888, mom:0.0020630308624367544, thd:0.0, side:sell 
127.0.0.1 - - [18/Dec/2022 00:00:02] "POST / HTTP/1.1" 200 -
2022-12-18 00:00:02,105:INFO:modifiedmom:main.py:316:handleOrderNew:185213: handleOrderNew: data=OrderType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'clientorderid': '41375F1671292801930I0L59', 'symbol': 'BTCUSDT', 'gatewayorderid': 1671292802038188, 'quantity': '57.474', 'price': '16692.3', 'stopprice': '0', 'ordertype': '', 'side': 'SELL', 'status': 'FILLED', 'positionside': 'SHORT', 'createtime': 1671292801369, 'updatetime': 1671292802038, 'tradetype': 'usdt', 'selfid': 41375, 'filltrades': [TradeType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'tradeid': 1671292802038, 'clientorderid': '41375F1671292801930I0L59', 'price': '16692.3', 'quantity': '57.474', 'commission': '959.3732502', 'commissionasset': 'USDT', 'tradetime': 1671292802038, 'tradetype': 'usdt', 'gatetype': 'simulator', 'handletime': 1671292802038}], 'gatetype': 'simulator', 'handletime': 0}
2022-12-18 00:00:02,331:INFO:modifiedmom:main.py:319:handleOrderFilled:185213: handleOrderFilled: data=OrderType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'clientorderid': '41375F1671292801930I0L59', 'symbol': 'BTCUSDT', 'gatewayorderid': 1671292802038188, 'quantity': '57.474', 'price': '16692.3', 'stopprice': '0', 'ordertype': '', 'side': 'SELL', 'status': 'FILLED', 'positionside': 'SHORT', 'createtime': 1671292801369, 'updatetime': 1671292802038, 'tradetype': 'usdt', 'selfid': 41375, 'filltrades': [TradeType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'tradeid': 1671292802038, 'clientorderid': '41375F1671292801930I0L59', 'price': '16692.3', 'quantity': '57.474', 'commission': '959.3732502', 'commissionasset': 'USDT', 'tradetime': 1671292802038, 'tradetype': 'usdt', 'gatetype': 'simulator', 'handletime': 1671292802038}], 'gatetype': 'simulator', 'handletime': 0}
127.0.0.1 - - [18/Dec/2022 00:00:02] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=3224 

self.closeSec=1671293399, self.tradeDate='20221218', self.openTime='000000', self.closeTime='000959', self.symbol='BTCUSDT', self.open='16692.3', self.close='16684.6'
2022-12-18 00:10:01,528:INFO:modifiedmom:main.py:144:handleKline:185213: self.closeSec=1671293399, self.tradeDate='20221218', self.openTime='000000', self.closeTime='000959',self.symbol='BTCUSDT',self.open='16692.3', self.close='16684.6'
127.0.0.1 - - [18/Dec/2022 00:10:01] "POST / HTTP/1.1" 200 -
2022-12-18 00:10:01,569:INFO:modifiedmom:main.py:145:handleKline:185213: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
572  20221217   232000    232959  1671290999  16661.2  16677.6  0.000990
573  20221217   233000    233959  1671291599  16677.6    16680  0.000144
574  20221217   234000    234959  1671292199  16679.9  16677.4 -0.000156
575  20221217   235000    235959  1671292799  16677.3  16692.4  0.000899
576  20221218   000000    000959  1671293399  16692.3  16684.6 -0.000467
2022-12-18 00:10:01,570:INFO:modifiedmom:main.py:146:handleKline:185213: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False}


## /root/FIL/strategy/pyemd/log.txt ----- -----

2022-12-17 23:50:00,553:INFO:pyemd2:main.py:127:handleKline:185189: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}
127.0.0.1 - - [18/Dec/2022 00:00:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=3224 

self.closeSec=1671292799, self.tradeDate='20221217', self.openTime='235000', self.closeTime='235959', self.symbol='BTCUSDT', self.open='16677.3', self.close='16692.4'
2022-12-18 00:00:01,150:INFO:pyemd2:main.py:125:handleKline:185189: self.closeSec=1671292799, self.tradeDate='20221217', self.openTime='235000', self.closeTime='235959',self.symbol='BTCUSDT',self.open='16677.3', self.close='16692.4'
2022-12-18 00:00:01,203:INFO:pyemd2:main.py:126:handleKline:185189: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17419  20221217   231000    231959  1671290399  16659.8  16661.1
17420  20221217   232000    232959  1671290999  16661.2  16677.6
17421  20221217   233000    233959  1671291599  16677.6    16680
17422  20221217   234000    234959  1671292199  16679.9  16677.4
17423  20221217   235000    235959  1671292799  16677.3  16692.4
2022-12-18 00:00:01,203:INFO:pyemd2:main.py:127:handleKline:185189: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}
2022-12-18 00:00:01,347:INFO:pyemd2:main.py:190:insertFactor:185189: curDateTime:12180000, name:pyemd2, symbol:BTCUSDT, tradeDate:20221217, closeTime:235959, close:16692.4, total:947411.5003109, pct_pre:-0.010296315627150165, thd:0.17962209310943145, side:sell 
127.0.0.1 - - [18/Dec/2022 00:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=3225 

self.closeSec=1671293399, self.tradeDate='20221218', self.openTime='000000', self.closeTime='000959', self.symbol='BTCUSDT', self.open='16692.3', self.close='16684.6'
2022-12-18 00:10:01,550:INFO:pyemd2:main.py:125:handleKline:185189: self.closeSec=1671293399, self.tradeDate='20221218', self.openTime='000000', self.closeTime='000959',self.symbol='BTCUSDT',self.open='16692.3', self.close='16684.6'
2022-12-18 00:10:01,577:INFO:pyemd2:main.py:126:handleKline:185189: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17420  20221217   232000    232959  1671290999  16661.2  16677.6
17421  20221217   233000    233959  1671291599  16677.6    16680
17422  20221217   234000    234959  1671292199  16679.9  16677.4
17423  20221217   235000    235959  1671292799  16677.3  16692.4
17424  20221218   000000    000959  1671293399  16692.3  16684.6
2022-12-18 00:10:01,577:INFO:pyemd2:main.py:127:handleKline:185189: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}


## /root/FIL/strategy/similarity/log.txt ----- -----

2022-12-18 00:00:01,199:INFO:testStrategy:main.py:102:handleKline:185174: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12235  20221217   231000    231959  1671290399  16659.8  16661.1
12236  20221217   232000    232959  1671290999  16661.2  16677.6
12237  20221217   233000    233959  1671291599  16677.6    16680
12238  20221217   234000    234959  1671292199  16679.9  16677.4
12239  20221217   235000    235959  1671292799  16677.3  16692.4
2022-12-18 00:00:01,200:INFO:testStrategy:main.py:103:handleKline:185174: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': True, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}
closeSell: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '73.293', 'enterprice': '16716.6', 'countrevence': '0', 'unrealprofit': '1781.0199', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '16692.3', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
2022-12-18 00:00:01,950:INFO:testStrategy:main.py:253:closeSell:185174: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False, 'isCorr': False}
2022-12-18 00:00:01,950:INFO:testStrategy:main.py:254:closeSell:185174: ret = self.client.insertMarketUOrder("simulator",  BTCUSDT, 73.293, buy ), ret=InsertOrderReturn{'result': 'success', 'clientorderid': '41376F1671292801946I0L2'}
2022-12-18 00:00:02,002:INFO:testStrategy:main.py:172:insertFactor:185174: curDateTime:12180000, name:testStrategy, symbol:BTCUSDT, tradeDate:20221217, closeTime:235959, close:16692.4, total:1223984.5540362, corrDate:20221108, corrVal:0.6319902068619421, side:buy 
127.0.0.1 - - [18/Dec/2022 00:00:02] "POST / HTTP/1.1" 200 -
2022-12-18 00:00:02,357:INFO:testStrategy:main.py:305:handleOrderNew:185174: handleOrderNew: data=OrderType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'clientorderid': '41376F1671292801946I0L2', 'symbol': 'BTCUSDT', 'gatewayorderid': 1671292802052038, 'quantity': '73.293', 'price': '16692.4', 'stopprice': '0', 'ordertype': '', 'side': 'BUY', 'status': 'FILLED', 'positionside': 'LONG', 'createtime': 1671292801403, 'updatetime': 1671292802052, 'tradetype': 'usdt', 'selfid': 41376, 'filltrades': [TradeType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'tradeid': 1671292802052, 'clientorderid': '41376F1671292801946I0L2', 'price': '16692.4', 'quantity': '73.293', 'commission': '1223.4360732', 'commissionasset': 'USDT', 'tradetime': 1671292802052, 'tradetype': 'usdt', 'gatetype': 'simulator', 'handletime': 1671292802052}], 'gatetype': 'simulator', 'handletime': 0}
2022-12-18 00:00:02,556:INFO:testStrategy:main.py:308:handleOrderFilled:185174: handleOrderFilled: data=OrderType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'clientorderid': '41376F1671292801946I0L2', 'symbol': 'BTCUSDT', 'gatewayorderid': 1671292802052038, 'quantity': '73.293', 'price': '16692.4', 'stopprice': '0', 'ordertype': '', 'side': 'BUY', 'status': 'FILLED', 'positionside': 'LONG', 'createtime': 1671292801403, 'updatetime': 1671292802052, 'tradetype': 'usdt', 'selfid': 41376, 'filltrades': [TradeType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'tradeid': 1671292802052, 'clientorderid': '41376F1671292801946I0L2', 'price': '16692.4', 'quantity': '73.293', 'commission': '1223.4360732', 'commissionasset': 'USDT', 'tradetime': 1671292802052, 'tradetype': 'usdt', 'gatetype': 'simulator', 'handletime': 1671292802052}], 'gatetype': 'simulator', 'handletime': 0}
127.0.0.1 - - [18/Dec/2022 00:00:02] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [18/Dec/2022 00:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=3225 

self.closeSec=1671293399, self.tradeDate='20221218', self.openTime='000000', self.closeTime='000959', self.symbol='BTCUSDT', self.open='16692.3', self.close='16684.6'
2022-12-18 00:10:01,546:INFO:testStrategy:main.py:101:handleKline:185174: self.closeSec=1671293399, self.tradeDate='20221218', self.openTime='000000', self.closeTime='000959',self.symbol='BTCUSDT',self.open='16692.3', self.close='16684.6'
2022-12-18 00:10:01,555:INFO:testStrategy:main.py:102:handleKline:185174: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12236  20221217   232000    232959  1671290999  16661.2  16677.6
12237  20221217   233000    233959  1671291599  16677.6    16680
12238  20221217   234000    234959  1671292199  16679.9  16677.4
12239  20221217   235000    235959  1671292799  16677.3  16692.4
12240  20221218   000000    000959  1671293399  16692.3  16684.6
2022-12-18 00:10:01,555:INFO:testStrategy:main.py:103:handleKline:185174: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False, 'isCorr': False}


## /root/FIL/strategy/sr_min/log.txt ----- -----

127.0.0.1 - - [18/Dec/2022 00:10:01] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=0, self.total=1000000.0, self.flagDict['side']='', self.tradeCount=0, self.count=1880
self.closeSec=1671293399, self.tradeDate='20221218', self.openTime='000500', self.closeTime='000959', self.symbol='BTCUSDT', self.open=16687.4, self.close=16684.6, self.high=16688.3, self.low=16683.9, self.vol=368.606, self.amt=6150360.716 
2022-12-18 00:10:01,455:INFO:sr_min:main.py:172:handleKline:449472: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5757  20221217   234500    234959  ...    0.081224   0.227848       0
5758  20221217   235000    235459  ...    0.080931   0.227591       0
5759  20221217   235500    235959  ...    0.080640   0.227335       0
5760  20221218   000000    000459  ...    0.080350   0.227084       0
5761  20221218   000500    000959  ...    0.080063   0.226837       0

[5 rows x 18 columns]
2022-12-18 00:10:01,455:INFO:sr_min:main.py:175:handleKline:449472: self.closeSec=1671293399, self.tradeDate='20221218', self.openTime='000500', self.closeTime='000959',self.symbol='BTCUSDT',self.open=16687.4, self.close=16684.6, self.high=16688.3, self.low=16683.9, self.vol=368.606, self.amt=6150360.716, ukdf['pct'].iloc[-1]=-0.000168 , ukdf['amount'].iloc[-1]=6150360.716, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5761, value=0.0, value_mean=0.08006345706332427, signal=0, value_std=0.22683695909003604 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': []}
type(curSign)=<class 'int'>, curSign=0, self.sign=0
127.0.0.1 - - [18/Dec/2022 00:15:00] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=0, self.total=1000000.0, self.flagDict['side']='', self.tradeCount=0, self.count=1881
self.closeSec=1671293699, self.tradeDate='20221218', self.openTime='001000', self.closeTime='001459', self.symbol='BTCUSDT', self.open=16684.7, self.close=16680.8, self.high=16686.6, self.low=16680.8, self.vol=368.44, self.amt=6146832.5243 
2022-12-18 00:15:00,647:INFO:sr_min:main.py:172:handleKline:449472: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5758  20221217   235000    235459  ...    0.080931   0.227591       0
5759  20221217   235500    235959  ...    0.080640   0.227335       0
5760  20221218   000000    000459  ...    0.080350   0.227084       0
5761  20221218   000500    000959  ...    0.080063   0.226837       0
5762  20221218   001000    001459  ...    0.079777   0.226590       0

[5 rows x 18 columns]
2022-12-18 00:15:00,647:INFO:sr_min:main.py:175:handleKline:449472: self.closeSec=1671293699, self.tradeDate='20221218', self.openTime='001000', self.closeTime='001459',self.symbol='BTCUSDT',self.open=16684.7, self.close=16680.8, self.high=16686.6, self.low=16680.8, self.vol=368.44, self.amt=6146832.5243, ukdf['pct'].iloc[-1]=-0.000228 , ukdf['amount'].iloc[-1]=6146832.5243, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5762, value=0.0, value_mean=0.07977660571265996, signal=0, value_std=0.22658965476858517 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': []}
type(curSign)=<class 'int'>, curSign=0, self.sign=0


## /root/FIL/strategy/s_rsrs/log.txt ----- -----

723  20221217   120000    155959  1671263999  ...    723  0.729073  0.174966     NaN
724  20221217   160000    195959  1671278399  ...    724  0.776478  0.319181     NaN

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '53.436', 'enterprice': '17756.3', 'countrevence': '0', 'unrealprofit': '-56417.7288', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '16700.5', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-9223372036854775808, self.sign=1
127.0.0.1 - - [18/Dec/2022 00:00:00] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='s_rsrs', self.symbol='BTCUSDT', interval='4h', intervalSec=14400, wid=25, thd=0.6, self.sign=1, self.total=947876.8211532, self.flagDict['side']='buy', self.tradeCount=6, self.count=134
self.closeSec=1671292799, self.tradeDate='20221217', self.openTime='200000', self.closeTime='235959', self.symbol='BTCUSDT', self.open=16700.6, self.close=16692.4, self.high=16719.4, self.low=16633.1, self.vol=40968.291, self.amt=683087219.7158 
2022-12-18 00:00:01,007:INFO:s_rsrs:main.py:141:handleKline:185271: self.closeSec=1671292799, self.tradeDate='20221217', self.openTime='200000', self.closeTime='235959',self.symbol='BTCUSDT',self.open=16700.6, self.close=16692.4, self.high=16719.4, self.low=16633.1, self.vol=40968.291, self.amt=683087219.7158 
2022-12-18 00:00:01,067:INFO:s_rsrs:main.py:142:handleKline:185271: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime  ...         vol           amt       pct
721  20221217   040000    075959  ...  134056.770  2.240063e+09 -0.013787
722  20221217   080000    115959  ...   66363.998  1.105574e+09  0.002611
723  20221217   120000    155959  ...   45721.150  7.635974e+08  0.004230
724  20221217   160000    195959  ...   37850.072  6.323066e+08 -0.002234
725  20221217   200000    235959  ...   40968.291  6.830872e+08 -0.000491

[5 rows x 11 columns]
2022-12-18 00:00:03,208:INFO:s_rsrs:main.py:151:handleKline:185271: df_s.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec  ...  index      beta    zscore  signal
721  20221217   040000    075959  1671235199  ...    721  0.600340 -0.225650     NaN
722  20221217   080000    115959  1671249599  ...    722  0.673979  0.003568     NaN
723  20221217   120000    155959  1671263999  ...    723  0.729073  0.174966     NaN
724  20221217   160000    195959  1671278399  ...    724  0.776478  0.319181     NaN
725  20221217   200000    235959  1671292799  ...    725  0.839180  0.506705     NaN

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '53.436', 'enterprice': '17756.3', 'countrevence': '0', 'unrealprofit': '-56855.904', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '16692.3', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-9223372036854775808, self.sign=1


