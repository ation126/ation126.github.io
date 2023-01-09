# 20230110 00:16:01

## /root/FIL/strategy/amihud/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=993672.4896432, self.flagDict['side']='sell', self.tradeCount=2, self.count=12506
self.closeSec=1673280599, self.tradeDate='20230110', self.openTime='000500', self.closeTime='000959', self.symbol='BTCUSDT', self.open=17269.9, self.close=17278.8, self.high=17293.1, self.low=17259.6, self.vol=2078.872, self.amt=35911940.0812 
127.0.0.1 - - [10/Jan/2023 00:10:01] "POST / HTTP/1.1" 200 -
2023-01-10 00:10:01,443:INFO:amihud:main.py:172:handleKline:200676: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5757  20230109   234500    234959  ...         0.0        0.0       0
5758  20230109   235000    235459  ...         0.0        0.0       0
5759  20230109   235500    235959  ...         0.0        0.0       0
5760  20230110   000000    000459  ...         0.0        0.0       0
5761  20230110   000500    000959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-01-10 00:10:01,444:INFO:amihud:main.py:175:handleKline:200676: self.closeSec=1673280599, self.tradeDate='20230110', self.openTime='000500', self.closeTime='000959',self.symbol='BTCUSDT',self.open=17269.9, self.close=17278.8, self.high=17293.1, self.low=17259.6, self.vol=2078.872, self.amt=35911940.0812, ukdf['pct'].iloc[-1]=0.000556 , ukdf['amount'].iloc[-1]=35911940.0812, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5761, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '60.176', 'enterprice': '16529.3', 'countrevence': '0', 'unrealprofit': '-45294.4752', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '17282', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1
127.0.0.1 - - [10/Jan/2023 00:15:00] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=993672.4896432, self.flagDict['side']='sell', self.tradeCount=2, self.count=12507
self.closeSec=1673280899, self.tradeDate='20230110', self.openTime='001000', self.closeTime='001459', self.symbol='BTCUSDT', self.open=17282.0, self.close=17293.0, self.high=17293.7, self.low=17275.2, self.vol=900.413, self.amt=15563748.2793 
2023-01-10 00:15:00,620:INFO:amihud:main.py:172:handleKline:200676: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5758  20230109   235000    235459  ...         0.0        0.0       0
5759  20230109   235500    235959  ...         0.0        0.0       0
5760  20230110   000000    000459  ...         0.0        0.0       0
5761  20230110   000500    000959  ...         0.0        0.0       0
5762  20230110   001000    001459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-01-10 00:15:00,621:INFO:amihud:main.py:175:handleKline:200676: self.closeSec=1673280899, self.tradeDate='20230110', self.openTime='001000', self.closeTime='001459',self.symbol='BTCUSDT',self.open=17282.0, self.close=17293.0, self.high=17293.7, self.low=17275.2, self.vol=900.413, self.amt=15563748.2793, ukdf['pct'].iloc[-1]=0.000822 , ukdf['amount'].iloc[-1]=15563748.2793, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5762, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '60.176', 'enterprice': '16529.3', 'countrevence': '0', 'unrealprofit': '-45956.4112', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '17293', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1


## /root/FIL/strategy/factorcheck/log.txt ----- -----

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=95, self.factor=0.2635902028372188, self.count=13072 

self.closeSec=1673280599, self.tradeDate='20230110', self.openTime='000500', self.closeTime='000959', self.symbol='BTCUSDT', self.open=17269.9, self.close=17278.8, self.high=17293.1, self.low=17259.6 
2023-01-10 00:10:01,437:INFO:factorcheck2:main.py:126:handleKline:185239: self.closeSec=1673280599, self.tradeDate='20230110', self.openTime='000500', self.closeTime='000959',self.symbol='BTCUSDT',self.open=17269.9, self.close=17278.8, self.high=17293.1, self.low=17259.6   
2023-01-10 00:10:01,472:INFO:factorcheck2:main.py:127:handleKline:185239: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1437  20230109   234500    234959  1673279399  ...  17276.4  0.001169   1725    3
1438  20230109   235000    235459  1673279699  ...  17291.2  0.000538   1726    4
1439  20230109   235500    235959  1673279999  ...  17257.3 -0.002502   1727    5
1440  20230110   000000    000459  1673280299  ...  17260.4  0.000406   1440    0
1441  20230110   000500    000959  1673280599  ...  17259.6  0.000556   1441    1

[5 rows x 11 columns]
2023-01-10 00:10:01,472:INFO:factorcheck2:main.py:128:handleKline:185239: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=95, self.factor=0.2635902028372188, self.count=13073 

self.closeSec=1673280899, self.tradeDate='20230110', self.openTime='001000', self.closeTime='001459', self.symbol='BTCUSDT', self.open=17282.0, self.close=17293.0, self.high=17293.7, self.low=17275.2 
2023-01-10 00:15:00,535:INFO:factorcheck2:main.py:126:handleKline:185239: self.closeSec=1673280899, self.tradeDate='20230110', self.openTime='001000', self.closeTime='001459',self.symbol='BTCUSDT',self.open=17282.0, self.close=17293.0, self.high=17293.7, self.low=17275.2   
127.0.0.1 - - [10/Jan/2023 00:15:00] "POST / HTTP/1.1" 200 -
2023-01-10 00:15:00,571:INFO:factorcheck2:main.py:127:handleKline:185239: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1438  20230109   235000    235459  1673279699  ...  17291.2  0.000538   1726    4
1439  20230109   235500    235959  1673279999  ...  17257.3 -0.002502   1727    5
1440  20230110   000000    000459  1673280299  ...  17260.4  0.000406   1440    0
1441  20230110   000500    000959  1673280599  ...  17259.6  0.000556   1441    1
1442  20230110   001000    001459  1673280899  ...  17275.2  0.000822   1442    2

[5 rows x 11 columns]
2023-01-10 00:15:00,571:INFO:factorcheck2:main.py:128:handleKline:185239: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}


## /root/FIL/strategy/logic/log.txt ----- -----

2023-01-10 00:00:21,171:DEBUG:logic:main.py:456:getModel:726423: df_s.iloc[-5:,:] :
          date closeTime     open  ...    alpha58   alpha67   alpha72
5802  20230109    212959  17242.6  ...  52.916667  0.650940  0.180302
5803  20230109    215959  17259.4  ...  52.500000  0.615714  0.180731
5804  20230109    222959  17218.5  ...  52.916667  0.626285  0.177506
5805  20230109    225959  17239.1  ...  52.916667  0.633376  0.171940
5806  20230109    232959  17255.3  ...  52.916667  0.616064  0.173083

[5 rows x 33 columns]
0.5533088235294118
acc is : 0.5533088235294118
2023-01-10 00:00:21,266:INFO:logic:main.py:461:getModel:726423: df_pred.iloc[-5:,:] :
     pred    prob_0    prob_1  actual  ...  nav  sign   cost_        bm
539     0  0.510992  0.489008       0  ...  NaN   NaN -0.0016  1.040210
540     1  0.493427  0.506573       1  ...  NaN   NaN -0.0016  1.041473
541     0  0.509790  0.490210       1  ...  NaN   NaN -0.0016  1.042343
542     0  0.509372  0.490628       0  ...  NaN   NaN -0.0016  1.041080
543     1  0.498605  0.501395       1  ...  NaN   NaN -0.0016  1.042844

[5 rows x 10 columns]
2023-01-10 00:00:21,279:INFO:logic:main.py:471:getModel:726423: df_panel.iloc[-5:,:] :
    pred    prob_0    prob_1  actual  ...  nav  sign   cost_        bm
45     0  0.510918  0.489082       0  ...  NaN   NaN -0.0016  1.039997
46     1  0.493426  0.506574       1  ...  NaN   NaN -0.0016  1.041020
47     0  0.509792  0.490208       1  ...  NaN   NaN -0.0016  1.041890
48     0  0.509531  0.490469       0  ...  NaN   NaN -0.0016  1.042352
49     1  0.498605  0.501395       1  ...  NaN   NaN -0.0016  1.042844

[5 rows x 10 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '42.528', 'enterprice': '16701.5', 'countrevence': '0', 'unrealprofit': '23927.97059480352', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '17264.14039209', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}


## /root/FIL/strategy/modifiedmom/log.txt ----- -----

2023-01-10 00:00:01,119:INFO:modifiedmom:main.py:145:handleKline:185213: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
571  20230109   231000    231959  1673277599  17261.8  17237.5 -0.001379
572  20230109   232000    232959  1673278199  17237.5    17233 -0.000261
573  20230109   233000    233959  1673278799    17233  17254.7  0.001259
574  20230109   234000    234959  1673279399  17254.7  17296.2  0.002405
575  20230109   235000    235959  1673279999  17295.8  17262.2 -0.001966
2023-01-10 00:00:01,120:INFO:modifiedmom:main.py:146:handleKline:185213: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True}
closeBuy: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '53.632', 'enterprice': '17189.7', 'countrevence': '0', 'unrealprofit': '3865.72907425536', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '17261.77877898', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
2023-01-10 00:00:01,786:INFO:modifiedmom:main.py:267:closeBuy:185213: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False}
2023-01-10 00:00:01,786:INFO:modifiedmom:main.py:268:closeBuy:185213: ret = self.client.insertMarketUOrder("simulator",  BTCUSDT, 53.632, sell ), ret=InsertOrderReturn{'result': 'success', 'clientorderid': '41501F1673280001785I0L59'}
2023-01-10 00:00:01,821:INFO:modifiedmom:main.py:206:insertFactor:185213: curDateTime:1100000, name:modifiedmom, symbol:BTCUSDT, tradeDate:20230109, closeTime:235959, close:17262.2, total:920996.0724096, mom:0.00023453745047885555, thd:0.0, side:sell 
2023-01-10 00:00:02,191:INFO:modifiedmom:main.py:316:handleOrderNew:185213: handleOrderNew: data=OrderType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'clientorderid': '41501F1673280001785I0L59', 'symbol': 'BTCUSDT', 'gatewayorderid': 1673280001894517, 'quantity': '53.632', 'price': '17261.9', 'stopprice': '0', 'ordertype': '', 'side': 'SELL', 'status': 'FILLED', 'positionside': 'SHORT', 'createtime': 1673280001346, 'updatetime': 1673280001894, 'tradetype': 'usdt', 'selfid': 41501, 'filltrades': [TradeType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'tradeid': 1673280001894, 'clientorderid': '41501F1673280001785I0L59', 'price': '17261.9', 'quantity': '53.632', 'commission': '925.7902208', 'commissionasset': 'USDT', 'tradetime': 1673280001894, 'tradetype': 'usdt', 'gatetype': 'simulator', 'handletime': 1673280001894}], 'gatetype': 'simulator', 'handletime': 0}
127.0.0.1 - - [10/Jan/2023 00:00:02] "POST / HTTP/1.1" 200 -
2023-01-10 00:00:02,352:INFO:modifiedmom:main.py:319:handleOrderFilled:185213: handleOrderFilled: data=OrderType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'clientorderid': '41501F1673280001785I0L59', 'symbol': 'BTCUSDT', 'gatewayorderid': 1673280001894517, 'quantity': '53.632', 'price': '17261.9', 'stopprice': '0', 'ordertype': '', 'side': 'SELL', 'status': 'FILLED', 'positionside': 'SHORT', 'createtime': 1673280001346, 'updatetime': 1673280001894, 'tradetype': 'usdt', 'selfid': 41501, 'filltrades': [TradeType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'tradeid': 1673280001894, 'clientorderid': '41501F1673280001785I0L59', 'price': '17261.9', 'quantity': '53.632', 'commission': '925.7902208', 'commissionasset': 'USDT', 'tradetime': 1673280001894, 'tradetype': 'usdt', 'gatetype': 'simulator', 'handletime': 1673280001894}], 'gatetype': 'simulator', 'handletime': 0}
127.0.0.1 - - [10/Jan/2023 00:00:02] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [10/Jan/2023 00:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=6536 

self.closeSec=1673280599, self.tradeDate='20230110', self.openTime='000000', self.closeTime='000959', self.symbol='BTCUSDT', self.open='17260.4', self.close='17278.8'
2023-01-10 00:10:01,536:INFO:modifiedmom:main.py:144:handleKline:185213: self.closeSec=1673280599, self.tradeDate='20230110', self.openTime='000000', self.closeTime='000959',self.symbol='BTCUSDT',self.open='17260.4', self.close='17278.8'
2023-01-10 00:10:01,591:INFO:modifiedmom:main.py:145:handleKline:185213: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
572  20230109   232000    232959  1673278199  17237.5    17233 -0.000261
573  20230109   233000    233959  1673278799    17233  17254.7  0.001259
574  20230109   234000    234959  1673279399  17254.7  17296.2  0.002405
575  20230109   235000    235959  1673279999  17295.8  17262.2 -0.001966
576  20230110   000000    000959  1673280599  17260.4  17278.8  0.000962
2023-01-10 00:10:01,592:INFO:modifiedmom:main.py:146:handleKline:185213: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False}


## /root/FIL/strategy/pyemd/log.txt ----- -----

2023-01-09 23:50:00,643:INFO:pyemd2:main.py:127:handleKline:185189: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}
127.0.0.1 - - [10/Jan/2023 00:00:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=6536 

self.closeSec=1673279999, self.tradeDate='20230109', self.openTime='235000', self.closeTime='235959', self.symbol='BTCUSDT', self.open='17295.8', self.close='17262.2'
2023-01-10 00:00:01,132:INFO:pyemd2:main.py:125:handleKline:185189: self.closeSec=1673279999, self.tradeDate='20230109', self.openTime='235000', self.closeTime='235959',self.symbol='BTCUSDT',self.open='17295.8', self.close='17262.2'
2023-01-10 00:00:01,185:INFO:pyemd2:main.py:126:handleKline:185189: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17419  20230109   231000    231959  1673277599  17261.8  17237.5
17420  20230109   232000    232959  1673278199  17237.5    17233
17421  20230109   233000    233959  1673278799    17233  17254.7
17422  20230109   234000    234959  1673279399  17254.7  17296.2
17423  20230109   235000    235959  1673279999  17295.8  17262.2
2023-01-10 00:00:01,185:INFO:pyemd2:main.py:127:handleKline:185189: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}
2023-01-10 00:00:01,361:INFO:pyemd2:main.py:190:insertFactor:185189: curDateTime:1100000, name:pyemd2, symbol:BTCUSDT, tradeDate:20230109, closeTime:235959, close:17262.2, total:942179.1300971, pct_pre:0.015362947423008366, thd:-1.1381476082985056, side:sell 

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=6537 

self.closeSec=1673280599, self.tradeDate='20230110', self.openTime='000000', self.closeTime='000959', self.symbol='BTCUSDT', self.open='17260.4', self.close='17278.8'
127.0.0.1 - - [10/Jan/2023 00:10:01] "POST / HTTP/1.1" 200 -
2023-01-10 00:10:01,562:INFO:pyemd2:main.py:125:handleKline:185189: self.closeSec=1673280599, self.tradeDate='20230110', self.openTime='000000', self.closeTime='000959',self.symbol='BTCUSDT',self.open='17260.4', self.close='17278.8'
2023-01-10 00:10:01,596:INFO:pyemd2:main.py:126:handleKline:185189: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17420  20230109   232000    232959  1673278199  17237.5    17233
17421  20230109   233000    233959  1673278799    17233  17254.7
17422  20230109   234000    234959  1673279399  17254.7  17296.2
17423  20230109   235000    235959  1673279999  17295.8  17262.2
17424  20230110   000000    000959  1673280599  17260.4  17278.8
2023-01-10 00:10:01,596:INFO:pyemd2:main.py:127:handleKline:185189: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}


## /root/FIL/strategy/similarity/log.txt ----- -----

2023-01-10 00:00:01,139:INFO:testStrategy:main.py:102:handleKline:185174: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12235  20230109   231000    231959  1673277599  17261.8  17237.5
12236  20230109   232000    232959  1673278199  17237.5    17233
12237  20230109   233000    233959  1673278799    17233  17254.7
12238  20230109   234000    234959  1673279399  17254.7  17296.2
12239  20230109   235000    235959  1673279999  17295.8  17262.2
2023-01-10 00:00:01,140:INFO:testStrategy:main.py:103:handleKline:185174: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}
closeBuy: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '72.205', 'enterprice': '16959.2', 'countrevence': '0', 'unrealprofit': '21847.7007362509', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '17261.77877898', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
2023-01-10 00:00:01,748:INFO:testStrategy:main.py:233:closeBuy:185174: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False, 'isCorr': False}
2023-01-10 00:00:01,748:INFO:testStrategy:main.py:234:closeBuy:185174: ret = self.client.insertMarketUOrder("simulator",  BTCUSDT, 72.205, sell ), ret=InsertOrderReturn{'result': 'success', 'clientorderid': '41500F1673280001745I0L2'}
2023-01-10 00:00:01,792:INFO:testStrategy:main.py:172:insertFactor:185174: curDateTime:1100000, name:testStrategy, symbol:BTCUSDT, tradeDate:20230109, closeTime:235959, close:17262.2, total:1223314.4969640002, corrDate:20221223, corrVal:0.828645889507289, side:sell 
2023-01-10 00:00:01,931:INFO:testStrategy:main.py:305:handleOrderNew:185174: handleOrderNew: data=OrderType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'clientorderid': '41500F1673280001745I0L2', 'symbol': 'BTCUSDT', 'gatewayorderid': 1673280001892986, 'quantity': '72.205', 'price': '17261.9', 'stopprice': '0', 'ordertype': '', 'side': 'SELL', 'status': 'FILLED', 'positionside': 'SHORT', 'createtime': 1673280001382, 'updatetime': 1673280001892, 'tradetype': 'usdt', 'selfid': 41500, 'filltrades': [TradeType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'tradeid': 1673280001892, 'clientorderid': '41500F1673280001745I0L2', 'price': '17261.9', 'quantity': '72.205', 'commission': '1246.3954895', 'commissionasset': 'USDT', 'tradetime': 1673280001892, 'tradetype': 'usdt', 'gatetype': 'simulator', 'handletime': 1673280001892}], 'gatetype': 'simulator', 'handletime': 0}
127.0.0.1 - - [10/Jan/2023 00:00:01] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [10/Jan/2023 00:00:02] "POST / HTTP/1.1" 200 -
2023-01-10 00:00:02,161:INFO:testStrategy:main.py:308:handleOrderFilled:185174: handleOrderFilled: data=OrderType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'clientorderid': '41500F1673280001745I0L2', 'symbol': 'BTCUSDT', 'gatewayorderid': 1673280001892986, 'quantity': '72.205', 'price': '17261.9', 'stopprice': '0', 'ordertype': '', 'side': 'SELL', 'status': 'FILLED', 'positionside': 'SHORT', 'createtime': 1673280001382, 'updatetime': 1673280001892, 'tradetype': 'usdt', 'selfid': 41500, 'filltrades': [TradeType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'tradeid': 1673280001892, 'clientorderid': '41500F1673280001745I0L2', 'price': '17261.9', 'quantity': '72.205', 'commission': '1246.3954895', 'commissionasset': 'USDT', 'tradetime': 1673280001892, 'tradetype': 'usdt', 'gatetype': 'simulator', 'handletime': 1673280001892}], 'gatetype': 'simulator', 'handletime': 0}
127.0.0.1 - - [10/Jan/2023 00:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=6537 

self.closeSec=1673280599, self.tradeDate='20230110', self.openTime='000000', self.closeTime='000959', self.symbol='BTCUSDT', self.open='17260.4', self.close='17278.8'
2023-01-10 00:10:01,556:INFO:testStrategy:main.py:101:handleKline:185174: self.closeSec=1673280599, self.tradeDate='20230110', self.openTime='000000', self.closeTime='000959',self.symbol='BTCUSDT',self.open='17260.4', self.close='17278.8'
2023-01-10 00:10:01,579:INFO:testStrategy:main.py:102:handleKline:185174: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12236  20230109   232000    232959  1673278199  17237.5    17233
12237  20230109   233000    233959  1673278799    17233  17254.7
12238  20230109   234000    234959  1673279399  17254.7  17296.2
12239  20230109   235000    235959  1673279999  17295.8  17262.2
12240  20230110   000000    000959  1673280599  17260.4  17278.8
2023-01-10 00:10:01,579:INFO:testStrategy:main.py:103:handleKline:185174: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False, 'isCorr': False}


## /root/FIL/strategy/sr_min/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=0, self.total=1000000.0, self.flagDict['side']='', self.tradeCount=0, self.count=8504
self.closeSec=1673280599, self.tradeDate='20230110', self.openTime='000500', self.closeTime='000959', self.symbol='BTCUSDT', self.open=17269.9, self.close=17278.8, self.high=17293.1, self.low=17259.6, self.vol=2078.872, self.amt=35911940.0812 
127.0.0.1 - - [10/Jan/2023 00:10:01] "POST / HTTP/1.1" 200 -
2023-01-10 00:10:01,470:INFO:sr_min:main.py:172:handleKline:449472: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5757  20230109   234500    234959  ...         0.0        0.0       0
5758  20230109   235000    235459  ...         0.0        0.0       0
5759  20230109   235500    235959  ...         0.0        0.0       0
5760  20230110   000000    000459  ...         0.0        0.0       0
5761  20230110   000500    000959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-01-10 00:10:01,470:INFO:sr_min:main.py:175:handleKline:449472: self.closeSec=1673280599, self.tradeDate='20230110', self.openTime='000500', self.closeTime='000959',self.symbol='BTCUSDT',self.open=17269.9, self.close=17278.8, self.high=17293.1, self.low=17259.6, self.vol=2078.872, self.amt=35911940.0812, ukdf['pct'].iloc[-1]=0.000556 , ukdf['amount'].iloc[-1]=35911940.0812, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5761, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': []}
type(curSign)=<class 'int'>, curSign=0, self.sign=0
--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=0, self.total=1000000.0, self.flagDict['side']='', self.tradeCount=0, self.count=8505
self.closeSec=1673280899, self.tradeDate='20230110', self.openTime='001000', self.closeTime='001459', self.symbol='BTCUSDT', self.open=17282.0, self.close=17293.0, self.high=17293.7, self.low=17275.2, self.vol=900.413, self.amt=15563748.2793 
127.0.0.1 - - [10/Jan/2023 00:15:00] "POST / HTTP/1.1" 200 -
2023-01-10 00:15:00,602:INFO:sr_min:main.py:172:handleKline:449472: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5758  20230109   235000    235459  ...         0.0        0.0       0
5759  20230109   235500    235959  ...         0.0        0.0       0
5760  20230110   000000    000459  ...         0.0        0.0       0
5761  20230110   000500    000959  ...         0.0        0.0       0
5762  20230110   001000    001459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-01-10 00:15:00,602:INFO:sr_min:main.py:175:handleKline:449472: self.closeSec=1673280899, self.tradeDate='20230110', self.openTime='001000', self.closeTime='001459',self.symbol='BTCUSDT',self.open=17282.0, self.close=17293.0, self.high=17293.7, self.low=17275.2, self.vol=900.413, self.amt=15563748.2793, ukdf['pct'].iloc[-1]=0.000822 , ukdf['amount'].iloc[-1]=15563748.2793, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5762, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': []}
type(curSign)=<class 'int'>, curSign=0, self.sign=0


## /root/FIL/strategy/s_rsrs/log.txt ----- -----

723  20230109   120000    155959  1673251199  ...    723  0.651387  1.049407     1.0
724  20230109   160000    195959  1673265599  ...    724  0.719609  1.262125     1.0

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '51.136', 'enterprice': '17188.2', 'countrevence': '0', 'unrealprofit': '2249.984', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '17232.2', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=1, self.sign=1
127.0.0.1 - - [10/Jan/2023 00:00:00] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='s_rsrs', self.symbol='BTCUSDT', interval='4h', intervalSec=14400, wid=25, thd=0.6, self.sign=1, self.total=878056.8594048, self.flagDict['side']='buy', self.tradeCount=12, self.count=272
self.closeSec=1673279999, self.tradeDate='20230109', self.openTime='200000', self.closeTime='235959', self.symbol='BTCUSDT', self.open=17232.2, self.close=17262.2, self.high=17325.0, self.low=17181.9, self.vol=80348.391, self.amt=1386486539.6969 
2023-01-10 00:00:00,965:INFO:s_rsrs:main.py:141:handleKline:185271: self.closeSec=1673279999, self.tradeDate='20230109', self.openTime='200000', self.closeTime='235959',self.symbol='BTCUSDT',self.open=17232.2, self.close=17262.2, self.high=17325.0, self.low=17181.9, self.vol=80348.391, self.amt=1386486539.6969 
2023-01-10 00:00:01,028:INFO:s_rsrs:main.py:142:handleKline:185271: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime  ...        vol           amt       pct
721  20230109   040000    075959  ...  60866.075  1.036432e+09  0.012015
722  20230109   080000    115959  ...  85195.644  1.463026e+09  0.003767
723  20230109   120000    155959  ...  35863.212  6.170962e+08  0.000087
724  20230109   160000    195959  ...  50754.110  8.747792e+08  0.002467
725  20230109   200000    235959  ...  80348.391  1.386487e+09  0.001747

[5 rows x 11 columns]
2023-01-10 00:00:02,797:INFO:s_rsrs:main.py:151:handleKline:185271: df_s.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec  ...  index      beta    zscore  signal
721  20230109   040000    075959  1673222399  ...    721  0.338125 -0.011355     NaN
722  20230109   080000    115959  1673236799  ...    722  0.565325  0.768820     1.0
723  20230109   120000    155959  1673251199  ...    723  0.651387  1.049407     1.0
724  20230109   160000    195959  1673265599  ...    724  0.719609  1.262125     1.0
725  20230109   200000    235959  1673279999  ...    725  0.801034  1.512647     1.0

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '51.136', 'enterprice': '17188.2', 'countrevence': '0', 'unrealprofit': '3784.6668985536', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '17262.2117901', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=1, self.sign=1


