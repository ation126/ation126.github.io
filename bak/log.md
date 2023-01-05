# 20230106 00:16:01

## /root/FIL/strategy/amihud/log.txt ----- -----

127.0.0.1 - - [06/Jan/2023 00:10:01] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=993672.4896432, self.flagDict['side']='sell', self.tradeCount=2, self.count=11354
self.closeSec=1672934999, self.tradeDate='20230106', self.openTime='000500', self.closeTime='000959', self.symbol='BTCUSDT', self.open=16836.5, self.close=16844.4, self.high=16844.4, self.low=16836.0, self.vol=803.306, self.amt=13527024.1173 
2023-01-06 00:10:01,456:INFO:amihud:main.py:172:handleKline:200676: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5757  20230105   234500    234959  ...         0.0        0.0       0
5758  20230105   235000    235459  ...         0.0        0.0       0
5759  20230105   235500    235959  ...         0.0        0.0       0
5760  20230106   000000    000459  ...         0.0        0.0       0
5761  20230106   000500    000959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-01-06 00:10:01,456:INFO:amihud:main.py:175:handleKline:200676: self.closeSec=1672934999, self.tradeDate='20230106', self.openTime='000500', self.closeTime='000959',self.symbol='BTCUSDT',self.open=16836.5, self.close=16844.4, self.high=16844.4, self.low=16836.0, self.vol=803.306, self.amt=13527024.1173, ukdf['pct'].iloc[-1]=0.000463 , ukdf['amount'].iloc[-1]=13527024.1173, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5761, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '60.176', 'enterprice': '16529.3', 'countrevence': '0', 'unrealprofit': '-18985.528', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '16844.8', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1
127.0.0.1 - - [06/Jan/2023 00:15:00] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=993672.4896432, self.flagDict['side']='sell', self.tradeCount=2, self.count=11355
self.closeSec=1672935299, self.tradeDate='20230106', self.openTime='001000', self.closeTime='001459', self.symbol='BTCUSDT', self.open=16844.5, self.close=16848.1, self.high=16856.8, self.low=16844.5, self.vol=1001.636, self.amt=16876825.7921 
2023-01-06 00:15:01,098:INFO:amihud:main.py:172:handleKline:200676: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5758  20230105   235000    235459  ...         0.0        0.0       0
5759  20230105   235500    235959  ...         0.0        0.0       0
5760  20230106   000000    000459  ...         0.0        0.0       0
5761  20230106   000500    000959  ...         0.0        0.0       0
5762  20230106   001000    001459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-01-06 00:15:01,098:INFO:amihud:main.py:175:handleKline:200676: self.closeSec=1672935299, self.tradeDate='20230106', self.openTime='001000', self.closeTime='001459',self.symbol='BTCUSDT',self.open=16844.5, self.close=16848.1, self.high=16856.8, self.low=16844.5, self.vol=1001.636, self.amt=16876825.7921, ukdf['pct'].iloc[-1]=0.00022 , ukdf['amount'].iloc[-1]=16876825.7921, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5762, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '60.176', 'enterprice': '16529.3', 'countrevence': '0', 'unrealprofit': '-19337.15387741072', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '16850.64329097', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1


## /root/FIL/strategy/factorcheck/log.txt ----- -----

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=150, self.factor=0.5637180793936456, self.count=11920 

self.closeSec=1672934999, self.tradeDate='20230106', self.openTime='000500', self.closeTime='000959', self.symbol='BTCUSDT', self.open=16836.5, self.close=16844.4, self.high=16844.4, self.low=16836.0 
2023-01-06 00:10:01,417:INFO:factorcheck2:main.py:126:handleKline:185239: self.closeSec=1672934999, self.tradeDate='20230106', self.openTime='000500', self.closeTime='000959',self.symbol='BTCUSDT',self.open=16836.5, self.close=16844.4, self.high=16844.4, self.low=16836.0   
2023-01-06 00:10:01,443:INFO:factorcheck2:main.py:127:handleKline:185239: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1437  20230105   234500    234959  1672933799  ...  16852.0 -0.000694   1725    3
1438  20230105   235000    235459  1672934099  ...  16840.0 -0.001038   1726    4
1439  20230105   235500    235959  1672934399  ...  16832.0 -0.000202   1727    5
1440  20230106   000000    000459  1672934699  ...  16824.3  0.000000   1440    0
1441  20230106   000500    000959  1672934999  ...  16836.0  0.000463   1441    1

[5 rows x 11 columns]
2023-01-06 00:10:01,443:INFO:factorcheck2:main.py:128:handleKline:185239: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=150, self.factor=0.5637180793936456, self.count=11921 

self.closeSec=1672935299, self.tradeDate='20230106', self.openTime='001000', self.closeTime='001459', self.symbol='BTCUSDT', self.open=16844.5, self.close=16848.1, self.high=16856.8, self.low=16844.5 
2023-01-06 00:15:01,029:INFO:factorcheck2:main.py:126:handleKline:185239: self.closeSec=1672935299, self.tradeDate='20230106', self.openTime='001000', self.closeTime='001459',self.symbol='BTCUSDT',self.open=16844.5, self.close=16848.1, self.high=16856.8, self.low=16844.5   
127.0.0.1 - - [06/Jan/2023 00:15:00] "POST / HTTP/1.1" 200 -
2023-01-06 00:15:01,115:INFO:factorcheck2:main.py:127:handleKline:185239: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1438  20230105   235000    235459  1672934099  ...  16840.0 -0.001038   1726    4
1439  20230105   235500    235959  1672934399  ...  16832.0 -0.000202   1727    5
1440  20230106   000000    000459  1672934699  ...  16824.3  0.000000   1440    0
1441  20230106   000500    000959  1672934999  ...  16836.0  0.000463   1441    1
1442  20230106   001000    001459  1672935299  ...  16844.5  0.000220   1442    2

[5 rows x 11 columns]
2023-01-06 00:15:01,116:INFO:factorcheck2:main.py:128:handleKline:185239: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}


## /root/FIL/strategy/logic/log.txt ----- -----

2023-01-06 00:00:18,303:DEBUG:logic:main.py:456:getModel:726423: df_s.iloc[-5:,:] :
          date closeTime     open  ...    alpha58   alpha67   alpha72
5802  20230105    212959  16813.6  ...  48.750000  0.510207  0.712602
5803  20230105    215959  16801.3  ...  48.333333  0.488439  0.730237
5804  20230105    222959  16771.0  ...  48.333333  0.512266  0.730585
5805  20230105    225959  16804.9  ...  48.750000  0.523261  0.726406
5806  20230105    232959  16822.6  ...  48.750000  0.536383  0.692080

[5 rows x 33 columns]
0.5183823529411765
acc is : 0.5183823529411765
2023-01-06 00:00:18,396:INFO:logic:main.py:461:getModel:726423: df_pred.iloc[-5:,:] :
     pred    prob_0    prob_1  actual  ...  nav  sign   cost_        bm
539     1  0.493325  0.506675       0  ...  NaN   NaN -0.0016  0.997277
540     1  0.485790  0.514210       1  ...  NaN   NaN -0.0016  0.999298
541     0  0.502615  0.497385       1  ...  NaN   NaN -0.0016  1.000279
542     0  0.502899  0.497101       1  ...  NaN   NaN -0.0016  1.001487
543     0  0.506074  0.493926       0  ...  NaN   NaN -0.0016  1.001177

[5 rows x 10 columns]
2023-01-06 00:00:18,419:INFO:logic:main.py:471:getModel:726423: df_panel.iloc[-5:,:] :
    pred    prob_0    prob_1  actual  ...  nav  sign   cost_        bm
45     1  0.493104  0.506896       0  ...  NaN   NaN -0.0016  0.997490
46     1  0.485386  0.514614       1  ...  NaN   NaN -0.0016  0.998930
47     0  0.502040  0.497960       1  ...  NaN   NaN -0.0016  0.999911
48     0  0.502714  0.497286       1  ...  NaN   NaN -0.0016  1.001433
49     0  0.506074  0.493926       0  ...  NaN   NaN -0.0016  1.001177

[5 rows x 10 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '42.528', 'enterprice': '16701.5', 'countrevence': '0', 'unrealprofit': '5761.71968147712', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '16836.98061704', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}


## /root/FIL/strategy/modifiedmom/log.txt ----- -----

2023-01-06 00:00:01,311:INFO:modifiedmom:main.py:145:handleKline:185213: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
571  20230105   231000    231959  1672931999  16845.3  16838.4 -0.000404
572  20230105   232000    232959  1672932599  16838.7  16841.8  0.000202
573  20230105   233000    233959  1672933199  16841.6  16853.8  0.000713
574  20230105   234000    234959  1672933799  16853.8  16857.5  0.000220
575  20230105   235000    235959  1672934399  16857.5  16836.6 -0.001240
2023-01-06 00:00:01,311:INFO:modifiedmom:main.py:146:handleKline:185213: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True}
closeBuy: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '54.797', 'enterprice': '16815.3', 'countrevence': '0', 'unrealprofit': '1172.6558', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '16836.7', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
2023-01-06 00:00:02,073:INFO:modifiedmom:main.py:267:closeBuy:185213: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False}
2023-01-06 00:00:02,073:INFO:modifiedmom:main.py:268:closeBuy:185213: ret = self.client.insertMarketUOrder("simulator",  BTCUSDT, 54.797, sell ), ret=InsertOrderReturn{'result': 'success', 'clientorderid': '41477F1672934402070I0L59'}
2023-01-06 00:00:02,099:INFO:modifiedmom:main.py:206:insertFactor:185213: curDateTime:1060000, name:modifiedmom, symbol:BTCUSDT, tradeDate:20230105, closeTime:235959, close:16836.6, total:920506.5661058999, mom:0.0062927577695901515, thd:0.0, side:sell 
2023-01-06 00:00:02,230:INFO:modifiedmom:main.py:316:handleOrderNew:185213: handleOrderNew: data=OrderType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'clientorderid': '41477F1672934402070I0L59', 'symbol': 'BTCUSDT', 'gatewayorderid': 1672934402175211, 'quantity': '54.797', 'price': '16836.6', 'stopprice': '0', 'ordertype': '', 'side': 'SELL', 'status': 'FILLED', 'positionside': 'SHORT', 'createtime': 1672934401550, 'updatetime': 1672934402175, 'tradetype': 'usdt', 'selfid': 41477, 'filltrades': [TradeType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'tradeid': 1672934402175, 'clientorderid': '41477F1672934402070I0L59', 'price': '16836.6', 'quantity': '54.797', 'commission': '922.5951702', 'commissionasset': 'USDT', 'tradetime': 1672934402175, 'tradetype': 'usdt', 'gatetype': 'simulator', 'handletime': 1672934402175}], 'gatetype': 'simulator', 'handletime': 0}
127.0.0.1 - - [06/Jan/2023 00:00:02] "POST / HTTP/1.1" 200 -
2023-01-06 00:00:02,435:INFO:modifiedmom:main.py:319:handleOrderFilled:185213: handleOrderFilled: data=OrderType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'clientorderid': '41477F1672934402070I0L59', 'symbol': 'BTCUSDT', 'gatewayorderid': 1672934402175211, 'quantity': '54.797', 'price': '16836.6', 'stopprice': '0', 'ordertype': '', 'side': 'SELL', 'status': 'FILLED', 'positionside': 'SHORT', 'createtime': 1672934401550, 'updatetime': 1672934402175, 'tradetype': 'usdt', 'selfid': 41477, 'filltrades': [TradeType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'tradeid': 1672934402175, 'clientorderid': '41477F1672934402070I0L59', 'price': '16836.6', 'quantity': '54.797', 'commission': '922.5951702', 'commissionasset': 'USDT', 'tradetime': 1672934402175, 'tradetype': 'usdt', 'gatetype': 'simulator', 'handletime': 1672934402175}], 'gatetype': 'simulator', 'handletime': 0}
127.0.0.1 - - [06/Jan/2023 00:00:02] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [06/Jan/2023 00:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=5960 

self.closeSec=1672934999, self.tradeDate='20230106', self.openTime='000000', self.closeTime='000959', self.symbol='BTCUSDT', self.open='16836.7', self.close='16844.4'
2023-01-06 00:10:01,495:INFO:modifiedmom:main.py:144:handleKline:185213: self.closeSec=1672934999, self.tradeDate='20230106', self.openTime='000000', self.closeTime='000959',self.symbol='BTCUSDT',self.open='16836.7', self.close='16844.4'
2023-01-06 00:10:01,520:INFO:modifiedmom:main.py:145:handleKline:185213: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
572  20230105   232000    232959  1672932599  16838.7  16841.8  0.000202
573  20230105   233000    233959  1672933199  16841.6  16853.8  0.000713
574  20230105   234000    234959  1672933799  16853.8  16857.5  0.000220
575  20230105   235000    235959  1672934399  16857.5  16836.6 -0.001240
576  20230106   000000    000959  1672934999  16836.7  16844.4  0.000463
2023-01-06 00:10:01,521:INFO:modifiedmom:main.py:146:handleKline:185213: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False}


## /root/FIL/strategy/pyemd/log.txt ----- -----

2023-01-05 23:50:00,591:INFO:pyemd2:main.py:127:handleKline:185189: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}
127.0.0.1 - - [06/Jan/2023 00:00:00] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=5960 

self.closeSec=1672934399, self.tradeDate='20230105', self.openTime='235000', self.closeTime='235959', self.symbol='BTCUSDT', self.open='16857.5', self.close='16836.6'
2023-01-06 00:00:00,942:INFO:pyemd2:main.py:125:handleKline:185189: self.closeSec=1672934399, self.tradeDate='20230105', self.openTime='235000', self.closeTime='235959',self.symbol='BTCUSDT',self.open='16857.5', self.close='16836.6'
2023-01-06 00:00:00,975:INFO:pyemd2:main.py:126:handleKline:185189: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17419  20230105   231000    231959  1672931999  16845.3  16838.4
17420  20230105   232000    232959  1672932599  16838.7  16841.8
17421  20230105   233000    233959  1672933199  16841.6  16853.8
17422  20230105   234000    234959  1672933799  16853.8  16857.5
17423  20230105   235000    235959  1672934399  16857.5  16836.6
2023-01-06 00:00:00,976:INFO:pyemd2:main.py:127:handleKline:185189: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}
2023-01-06 00:00:01,239:INFO:pyemd2:main.py:190:insertFactor:185189: curDateTime:1060000, name:pyemd2, symbol:BTCUSDT, tradeDate:20230105, closeTime:235959, close:16836.6, total:939357.0753385, pct_pre:-0.0026180341591124368, thd:0.19022648710904477, side:sell 
127.0.0.1 - - [06/Jan/2023 00:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=5961 

self.closeSec=1672934999, self.tradeDate='20230106', self.openTime='000000', self.closeTime='000959', self.symbol='BTCUSDT', self.open='16836.7', self.close='16844.4'
2023-01-06 00:10:01,502:INFO:pyemd2:main.py:125:handleKline:185189: self.closeSec=1672934999, self.tradeDate='20230106', self.openTime='000000', self.closeTime='000959',self.symbol='BTCUSDT',self.open='16836.7', self.close='16844.4'
2023-01-06 00:10:01,527:INFO:pyemd2:main.py:126:handleKline:185189: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17420  20230105   232000    232959  1672932599  16838.7  16841.8
17421  20230105   233000    233959  1672933199  16841.6  16853.8
17422  20230105   234000    234959  1672933799  16853.8  16857.5
17423  20230105   235000    235959  1672934399  16857.5  16836.6
17424  20230106   000000    000959  1672934999  16836.7  16844.4
2023-01-06 00:10:01,527:INFO:pyemd2:main.py:127:handleKline:185189: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}


## /root/FIL/strategy/similarity/log.txt ----- -----

2023-01-06 00:00:01,113:INFO:testStrategy:main.py:102:handleKline:185174: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12235  20230105   231000    231959  1672931999  16845.3  16838.4
12236  20230105   232000    232959  1672932599  16838.7  16841.8
12237  20230105   233000    233959  1672933199  16841.6  16853.8
12238  20230105   234000    234959  1672933799  16853.8  16857.5
12239  20230105   235000    235959  1672934399  16857.5  16836.6
2023-01-06 00:00:01,113:INFO:testStrategy:main.py:103:handleKline:185174: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': True, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}
closeSell: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '73.541', 'enterprice': '16818.7', 'countrevence': '0', 'unrealprofit': '-1323.738', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '16836.7', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
2023-01-06 00:00:02,042:INFO:testStrategy:main.py:253:closeSell:185174: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False, 'isCorr': False}
2023-01-06 00:00:02,042:INFO:testStrategy:main.py:254:closeSell:185174: ret = self.client.insertMarketUOrder("simulator",  BTCUSDT, 73.541, buy ), ret=InsertOrderReturn{'result': 'success', 'clientorderid': '41476F1672934402041I0L2'}
2023-01-06 00:00:02,076:INFO:testStrategy:main.py:172:insertFactor:185174: curDateTime:1060000, name:testStrategy, symbol:BTCUSDT, tradeDate:20230105, closeTime:235959, close:16836.6, total:1235627.1526833, corrDate:20221215, corrVal:0.8601637312594392, side:buy 
2023-01-06 00:00:02,441:INFO:testStrategy:main.py:305:handleOrderNew:185174: handleOrderNew: data=OrderType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'clientorderid': '41476F1672934402041I0L2', 'symbol': 'BTCUSDT', 'gatewayorderid': 1672934402176376, 'quantity': '73.541', 'price': '16836.7', 'stopprice': '0', 'ordertype': '', 'side': 'BUY', 'status': 'FILLED', 'positionside': 'LONG', 'createtime': 1672934401368, 'updatetime': 1672934402176, 'tradetype': 'usdt', 'selfid': 41476, 'filltrades': [TradeType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'tradeid': 1672934402176, 'clientorderid': '41476F1672934402041I0L2', 'price': '16836.7', 'quantity': '73.541', 'commission': '1238.1877547', 'commissionasset': 'USDT', 'tradetime': 1672934402176, 'tradetype': 'usdt', 'gatetype': 'simulator', 'handletime': 1672934402176}], 'gatetype': 'simulator', 'handletime': 0}
127.0.0.1 - - [06/Jan/2023 00:00:02] "POST / HTTP/1.1" 200 -
2023-01-06 00:00:02,607:INFO:testStrategy:main.py:308:handleOrderFilled:185174: handleOrderFilled: data=OrderType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'clientorderid': '41476F1672934402041I0L2', 'symbol': 'BTCUSDT', 'gatewayorderid': 1672934402176376, 'quantity': '73.541', 'price': '16836.7', 'stopprice': '0', 'ordertype': '', 'side': 'BUY', 'status': 'FILLED', 'positionside': 'LONG', 'createtime': 1672934401368, 'updatetime': 1672934402176, 'tradetype': 'usdt', 'selfid': 41476, 'filltrades': [TradeType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'tradeid': 1672934402176, 'clientorderid': '41476F1672934402041I0L2', 'price': '16836.7', 'quantity': '73.541', 'commission': '1238.1877547', 'commissionasset': 'USDT', 'tradetime': 1672934402176, 'tradetype': 'usdt', 'gatetype': 'simulator', 'handletime': 1672934402176}], 'gatetype': 'simulator', 'handletime': 0}
127.0.0.1 - - [06/Jan/2023 00:00:02] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=5961 

self.closeSec=1672934999, self.tradeDate='20230106', self.openTime='000000', self.closeTime='000959', self.symbol='BTCUSDT', self.open='16836.7', self.close='16844.4'
2023-01-06 00:10:01,516:INFO:testStrategy:main.py:101:handleKline:185174: self.closeSec=1672934999, self.tradeDate='20230106', self.openTime='000000', self.closeTime='000959',self.symbol='BTCUSDT',self.open='16836.7', self.close='16844.4'
127.0.0.1 - - [06/Jan/2023 00:10:01] "POST / HTTP/1.1" 200 -
2023-01-06 00:10:01,531:INFO:testStrategy:main.py:102:handleKline:185174: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12236  20230105   232000    232959  1672932599  16838.7  16841.8
12237  20230105   233000    233959  1672933199  16841.6  16853.8
12238  20230105   234000    234959  1672933799  16853.8  16857.5
12239  20230105   235000    235959  1672934399  16857.5  16836.6
12240  20230106   000000    000959  1672934999  16836.7  16844.4
2023-01-06 00:10:01,531:INFO:testStrategy:main.py:103:handleKline:185174: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False, 'isCorr': False}


## /root/FIL/strategy/sr_min/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=0, self.total=1000000.0, self.flagDict['side']='', self.tradeCount=0, self.count=7352
self.closeSec=1672934999, self.tradeDate='20230106', self.openTime='000500', self.closeTime='000959', self.symbol='BTCUSDT', self.open=16836.5, self.close=16844.4, self.high=16844.4, self.low=16836.0, self.vol=803.306, self.amt=13527024.1173 
127.0.0.1 - - [06/Jan/2023 00:10:01] "POST / HTTP/1.1" 200 -
2023-01-06 00:10:01,447:INFO:sr_min:main.py:172:handleKline:449472: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5757  20230105   234500    234959  ...         0.0        0.0       0
5758  20230105   235000    235459  ...         0.0        0.0       0
5759  20230105   235500    235959  ...         0.0        0.0       0
5760  20230106   000000    000459  ...         0.0        0.0       0
5761  20230106   000500    000959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-01-06 00:10:01,447:INFO:sr_min:main.py:175:handleKline:449472: self.closeSec=1672934999, self.tradeDate='20230106', self.openTime='000500', self.closeTime='000959',self.symbol='BTCUSDT',self.open=16836.5, self.close=16844.4, self.high=16844.4, self.low=16836.0, self.vol=803.306, self.amt=13527024.1173, ukdf['pct'].iloc[-1]=0.000463 , ukdf['amount'].iloc[-1]=13527024.1173, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5761, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': []}
type(curSign)=<class 'int'>, curSign=0, self.sign=0
127.0.0.1 - - [06/Jan/2023 00:15:00] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=0, self.total=1000000.0, self.flagDict['side']='', self.tradeCount=0, self.count=7353
self.closeSec=1672935299, self.tradeDate='20230106', self.openTime='001000', self.closeTime='001459', self.symbol='BTCUSDT', self.open=16844.5, self.close=16848.1, self.high=16856.8, self.low=16844.5, self.vol=1001.636, self.amt=16876825.7921 
2023-01-06 00:15:01,056:INFO:sr_min:main.py:172:handleKline:449472: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5758  20230105   235000    235459  ...         0.0        0.0       0
5759  20230105   235500    235959  ...         0.0        0.0       0
5760  20230106   000000    000459  ...         0.0        0.0       0
5761  20230106   000500    000959  ...         0.0        0.0       0
5762  20230106   001000    001459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-01-06 00:15:01,057:INFO:sr_min:main.py:175:handleKline:449472: self.closeSec=1672935299, self.tradeDate='20230106', self.openTime='001000', self.closeTime='001459',self.symbol='BTCUSDT',self.open=16844.5, self.close=16848.1, self.high=16856.8, self.low=16844.5, self.vol=1001.636, self.amt=16876825.7921, ukdf['pct'].iloc[-1]=0.00022 , ukdf['amount'].iloc[-1]=16876825.7921, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5762, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': []}
type(curSign)=<class 'int'>, curSign=0, self.sign=0


## /root/FIL/strategy/s_rsrs/log.txt ----- -----

723  20230105   120000    155959  1672905599  ...    723  0.872667  2.061405     1.0
724  20230105   160000    195959  1672919999  ...    724  0.774980  1.685966     1.0

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '52.77', 'enterprice': '16723.1', 'countrevence': '0', 'unrealprofit': '5482.803', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '16827', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=1, self.sign=1
--handleKline--:  version='2.0.0', self.name='s_rsrs', self.symbol='BTCUSDT', interval='4h', intervalSec=14400, wid=25, thd=0.6, self.sign=1, self.total=881595.509013, self.flagDict['side']='buy', self.tradeCount=10, self.count=248
self.closeSec=1672934399, self.tradeDate='20230105', self.openTime='200000', self.closeTime='235959', self.symbol='BTCUSDT', self.open=16827.0, self.close=16836.6, self.high=16872.8, self.low=16740.4, self.vol=68886.393, self.amt=1157974929.4616 
127.0.0.1 - - [06/Jan/2023 00:00:00] "POST / HTTP/1.1" 200 -
2023-01-06 00:00:00,818:INFO:s_rsrs:main.py:141:handleKline:185271: self.closeSec=1672934399, self.tradeDate='20230105', self.openTime='200000', self.closeTime='235959',self.symbol='BTCUSDT',self.open=16827.0, self.close=16836.6, self.high=16872.8, self.low=16740.4, self.vol=68886.393, self.amt=1157974929.4616 
2023-01-06 00:00:00,862:INFO:s_rsrs:main.py:142:handleKline:185271: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime  ...        vol           amt       pct
721  20230105   040000    075959  ...  30171.855  5.073708e+08  0.000374
722  20230105   080000    115959  ...  19519.003  3.285506e+08 -0.001377
723  20230105   120000    155959  ...  16536.782  2.780496e+08 -0.000178
724  20230105   160000    195959  ...  23157.753  3.891926e+08  0.000654
725  20230105   200000    235959  ...  68886.393  1.157975e+09  0.000571

[5 rows x 11 columns]
2023-01-06 00:00:02,759:INFO:s_rsrs:main.py:151:handleKline:185271: df_s.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec  ...  index      beta    zscore  signal
721  20230105   040000    075959  1672876799  ...    721  0.969185  2.583625     1.0
722  20230105   080000    115959  1672891199  ...    722  0.959977  2.435706     1.0
723  20230105   120000    155959  1672905599  ...    723  0.872667  2.061405     1.0
724  20230105   160000    195959  1672919999  ...    724  0.774980  1.685966     1.0
725  20230105   200000    235959  1672934399  ...    725  0.703932  1.416203     1.0

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '52.77', 'enterprice': '16723.1', 'countrevence': '0', 'unrealprofit': '5989.395', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '16836.6', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=1, self.sign=1


