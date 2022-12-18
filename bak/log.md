# 20221219 00:16:02

## /root/FIL/strategy/amihud/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=993672.4896432, self.flagDict['side']='sell', self.tradeCount=2, self.count=6170
self.closeSec=1671379799, self.tradeDate='20221219', self.openTime='000500', self.closeTime='000959', self.symbol='BTCUSDT', self.open=16681.9, self.close=16685.7, self.high=16685.7, self.low=16681.8, self.vol=212.88, self.amt=3551557.4843 
127.0.0.1 - - [19/Dec/2022 00:10:01] "POST / HTTP/1.1" 200 -
2022-12-19 00:10:01,723:INFO:amihud:main.py:172:handleKline:200676: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5757  20221218   234500    234959  ...         0.0        0.0       0
5758  20221218   235000    235459  ...         0.0        0.0       0
5759  20221218   235500    235959  ...         0.0        0.0       0
5760  20221219   000000    000459  ...         0.0        0.0       0
5761  20221219   000500    000959  ...         0.0        0.0       0

[5 rows x 18 columns]
2022-12-19 00:10:01,723:INFO:amihud:main.py:175:handleKline:200676: self.closeSec=1671379799, self.tradeDate='20221219', self.openTime='000500', self.closeTime='000959',self.symbol='BTCUSDT',self.open=16681.9, self.close=16685.7, self.high=16685.7, self.low=16681.8, self.vol=212.88, self.amt=3551557.4843, ukdf['pct'].iloc[-1]=0.000234 , ukdf['amount'].iloc[-1]=3551557.4843, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5761, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '60.176', 'enterprice': '16529.3', 'countrevence': '0', 'unrealprofit': '-9433.13700731136', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '16686.05912336', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1
127.0.0.1 - - [19/Dec/2022 00:15:00] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=993672.4896432, self.flagDict['side']='sell', self.tradeCount=2, self.count=6171
self.closeSec=1671380099, self.tradeDate='20221219', self.openTime='001000', self.closeTime='001459', self.symbol='BTCUSDT', self.open=16685.6, self.close=16688.7, self.high=16690.0, self.low=16684.3, self.vol=400.365, self.amt=6681057.5348 
2022-12-19 00:15:00,654:INFO:amihud:main.py:172:handleKline:200676: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5758  20221218   235000    235459  ...         0.0        0.0       0
5759  20221218   235500    235959  ...         0.0        0.0       0
5760  20221219   000000    000459  ...         0.0        0.0       0
5761  20221219   000500    000959  ...         0.0        0.0       0
5762  20221219   001000    001459  ...         0.0        0.0       0

[5 rows x 18 columns]
2022-12-19 00:15:00,655:INFO:amihud:main.py:175:handleKline:200676: self.closeSec=1671380099, self.tradeDate='20221219', self.openTime='001000', self.closeTime='001459',self.symbol='BTCUSDT',self.open=16685.6, self.close=16688.7, self.high=16690.0, self.low=16684.3, self.vol=400.365, self.amt=6681057.5348, ukdf['pct'].iloc[-1]=0.00018 , ukdf['amount'].iloc[-1]=6681057.5348, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5762, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '60.176', 'enterprice': '16529.3', 'countrevence': '0', 'unrealprofit': '-9598.072', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '16688.8', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1


## /root/FIL/strategy/factorcheck/log.txt ----- -----


self.closeSec=1671379799, self.tradeDate='20221219', self.openTime='000500', self.closeTime='000959', self.symbol='BTCUSDT', self.open=16681.9, self.close=16685.7, self.high=16685.7, self.low=16681.8 
2022-12-19 00:10:01,675:INFO:factorcheck2:main.py:126:handleKline:185239: self.closeSec=1671379799, self.tradeDate='20221219', self.openTime='000500', self.closeTime='000959',self.symbol='BTCUSDT',self.open=16681.9, self.close=16685.7, self.high=16685.7, self.low=16681.8   
127.0.0.1 - - [19/Dec/2022 00:10:01] "POST / HTTP/1.1" 200 -
2022-12-19 00:10:01,710:INFO:factorcheck2:main.py:127:handleKline:185239: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1437  20221218   234500    234959  1671378599  ...  16683.1 -0.000054   1725    3
1438  20221218   235000    235459  1671378899  ...  16671.4 -0.000869   1726    4
1439  20221218   235500    235959  1671379199  ...  16671.4  0.000300   1727    5
1440  20221219   000000    000459  1671379499  ...  16674.5  0.000324   1440    0
1441  20221219   000500    000959  1671379799  ...  16681.8  0.000234   1441    1

[5 rows x 11 columns]
2022-12-19 00:10:01,710:INFO:factorcheck2:main.py:128:handleKline:185239: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': False, 'isOpen': True, 'isClose': False, 'isTrig': True}

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=25, self.factor=0.5923825249113455, self.count=6737 

self.closeSec=1671380099, self.tradeDate='20221219', self.openTime='001000', self.closeTime='001459', self.symbol='BTCUSDT', self.open=16685.6, self.close=16688.7, self.high=16690.0, self.low=16684.3 
2022-12-19 00:15:00,541:INFO:factorcheck2:main.py:126:handleKline:185239: self.closeSec=1671380099, self.tradeDate='20221219', self.openTime='001000', self.closeTime='001459',self.symbol='BTCUSDT',self.open=16685.6, self.close=16688.7, self.high=16690.0, self.low=16684.3   
127.0.0.1 - - [19/Dec/2022 00:15:00] "POST / HTTP/1.1" 200 -
2022-12-19 00:15:00,597:INFO:factorcheck2:main.py:127:handleKline:185239: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1438  20221218   235000    235459  1671378899  ...  16671.4 -0.000869   1726    4
1439  20221218   235500    235959  1671379199  ...  16671.4  0.000300   1727    5
1440  20221219   000000    000459  1671379499  ...  16674.5  0.000324   1440    0
1441  20221219   000500    000959  1671379799  ...  16681.8  0.000234   1441    1
1442  20221219   001000    001459  1671380099  ...  16684.3  0.000180   1442    2

[5 rows x 11 columns]
2022-12-19 00:15:00,597:INFO:factorcheck2:main.py:128:handleKline:185239: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': False, 'isOpen': True, 'isClose': False, 'isTrig': True}


## /root/FIL/strategy/logic/log.txt ----- -----

2022-12-19 00:00:22,865:DEBUG:logic:main.py:454:getModel:174970: df_s.iloc[-5:,:] :
          date closeTime     open  ...    alpha58   alpha67   alpha72
5802  20221218    212959  16716.0  ...  47.500000  0.444118  0.482420
5803  20221218    215959  16710.4  ...  47.083333  0.441534  0.493415
5804  20221218    222959  16704.2  ...  46.666667  0.437658  0.508147
5805  20221218    225959  16695.7  ...  46.666667  0.429054  0.531345
5806  20221218    232959  16676.0  ...  47.083333  0.432521  0.550118

[5 rows x 33 columns]
0.5661764705882353
acc is : 0.5661764705882353
2022-12-19 00:00:22,961:INFO:logic:main.py:459:getModel:174970: df_pred.iloc[-5:,:] :
     pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
539     0  0.501091  0.498909       0  ...  1.107002  -1.0    0.0  0.996944
540     1  0.499511  0.500489       0  ...  1.107585  -1.0    0.0  0.996419
541     1  0.497940  0.502060       0  ...  1.108892  -1.0    0.0  0.995243
542     1  0.493416  0.506584       1  ...  1.108493  -1.0    0.0  0.995601
543     1  0.499126  0.500874       0  ...  1.108865  -1.0    0.0  0.995267

[5 rows x 10 columns]
2022-12-19 00:00:22,986:INFO:logic:main.py:469:getModel:174970: df_panel.iloc[-5:,:] :
    pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
45     0  0.500572  0.499428       0  ...  1.077168  -1.0    0.0  0.983549
46     1  0.499075  0.500925       0  ...  1.077736  -1.0    0.0  0.985253
47     1  0.497509  0.502491       0  ...  1.079008  -1.0    0.0  0.984090
48     1  0.493045  0.506955       1  ...  1.078619  -1.0    0.0  0.992551
49     1  0.499126  0.500874       0  ...  1.108865  -1.0    0.0  0.995267

[5 rows x 10 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '37.704', 'enterprice': '17770', 'countrevence': '0', 'unrealprofit': '41265.96411980544', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '16675.52821664', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}


## /root/FIL/strategy/modifiedmom/log.txt ----- -----

2022-12-19 00:00:01,476:INFO:modifiedmom:main.py:145:handleKline:185213: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
571  20221218   231000    231959  1671376799  16675.1  16684.6  0.000564
572  20221218   232000    232959  1671377399  16684.5    16682 -0.000156
573  20221218   233000    233959  1671377999    16682  16682.8  0.000048
574  20221218   234000    234959  1671378599  16682.8    16686  0.000192
575  20221218   235000    235959  1671379199    16686  16676.4 -0.000575
2022-12-19 00:00:01,476:INFO:modifiedmom:main.py:146:handleKline:185213: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': True, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True}
closeSell: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '57.3', 'enterprice': '16727.5', 'countrevence': '0', 'unrealprofit': '2928.03', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '16676.4', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
2022-12-19 00:00:02,270:INFO:modifiedmom:main.py:287:closeSell:185213: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False}
2022-12-19 00:00:02,270:INFO:modifiedmom:main.py:288:closeSell:185213: ret = self.client.insertMarketUOrder("simulator",  BTCUSDT, 57.3, buy ), ret=InsertOrderReturn{'result': 'success', 'clientorderid': '41379F1671379202268I0L59'}
2022-12-19 00:00:02,304:INFO:modifiedmom:main.py:206:insertFactor:185213: curDateTime:12190000, name:modifiedmom, symbol:BTCUSDT, tradeDate:20221218, closeTime:235959, close:16676.4, total:957527.26425, mom:-0.002458165746288654, thd:0.0, side:buy 
127.0.0.1 - - [19/Dec/2022 00:00:02] "POST / HTTP/1.1" 200 -
2022-12-19 00:00:02,466:INFO:modifiedmom:main.py:316:handleOrderNew:185213: handleOrderNew: data=OrderType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'clientorderid': '41379F1671379202268I0L59', 'symbol': 'BTCUSDT', 'gatewayorderid': 1671379202402354, 'quantity': '57.3', 'price': '16676.4', 'stopprice': '0', 'ordertype': '', 'side': 'BUY', 'status': 'FILLED', 'positionside': 'LONG', 'createtime': 1671379201692, 'updatetime': 1671379202402, 'tradetype': 'usdt', 'selfid': 41379, 'filltrades': [TradeType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'tradeid': 1671379202402, 'clientorderid': '41379F1671379202268I0L59', 'price': '16676.4', 'quantity': '57.3', 'commission': '955.55772', 'commissionasset': 'USDT', 'tradetime': 1671379202402, 'tradetype': 'usdt', 'gatetype': 'simulator', 'handletime': 1671379202402}], 'gatetype': 'simulator', 'handletime': 0}
2022-12-19 00:00:02,686:INFO:modifiedmom:main.py:319:handleOrderFilled:185213: handleOrderFilled: data=OrderType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'clientorderid': '41379F1671379202268I0L59', 'symbol': 'BTCUSDT', 'gatewayorderid': 1671379202402354, 'quantity': '57.3', 'price': '16676.4', 'stopprice': '0', 'ordertype': '', 'side': 'BUY', 'status': 'FILLED', 'positionside': 'LONG', 'createtime': 1671379201692, 'updatetime': 1671379202402, 'tradetype': 'usdt', 'selfid': 41379, 'filltrades': [TradeType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'tradeid': 1671379202402, 'clientorderid': '41379F1671379202268I0L59', 'price': '16676.4', 'quantity': '57.3', 'commission': '955.55772', 'commissionasset': 'USDT', 'tradetime': 1671379202402, 'tradetype': 'usdt', 'gatetype': 'simulator', 'handletime': 1671379202402}], 'gatetype': 'simulator', 'handletime': 0}
127.0.0.1 - - [19/Dec/2022 00:00:02] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=3368 

self.closeSec=1671379799, self.tradeDate='20221219', self.openTime='000000', self.closeTime='000959', self.symbol='BTCUSDT', self.open='16676.4', self.close='16685.7'
2022-12-19 00:10:01,766:INFO:modifiedmom:main.py:144:handleKline:185213: self.closeSec=1671379799, self.tradeDate='20221219', self.openTime='000000', self.closeTime='000959',self.symbol='BTCUSDT',self.open='16676.4', self.close='16685.7'
127.0.0.1 - - [19/Dec/2022 00:10:01] "POST / HTTP/1.1" 200 -
2022-12-19 00:10:01,788:INFO:modifiedmom:main.py:145:handleKline:185213: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
572  20221218   232000    232959  1671377399  16684.5    16682 -0.000156
573  20221218   233000    233959  1671377999    16682  16682.8  0.000048
574  20221218   234000    234959  1671378599  16682.8    16686  0.000192
575  20221218   235000    235959  1671379199    16686  16676.4 -0.000575
576  20221219   000000    000959  1671379799  16676.4  16685.7  0.000558
2022-12-19 00:10:01,788:INFO:modifiedmom:main.py:146:handleKline:185213: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False}


## /root/FIL/strategy/pyemd/log.txt ----- -----

2022-12-18 23:50:00,575:INFO:pyemd2:main.py:127:handleKline:185189: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=3368 

self.closeSec=1671379199, self.tradeDate='20221218', self.openTime='235000', self.closeTime='235959', self.symbol='BTCUSDT', self.open='16686', self.close='16676.4'
127.0.0.1 - - [19/Dec/2022 00:00:01] "POST / HTTP/1.1" 200 -
2022-12-19 00:00:01,446:INFO:pyemd2:main.py:125:handleKline:185189: self.closeSec=1671379199, self.tradeDate='20221218', self.openTime='235000', self.closeTime='235959',self.symbol='BTCUSDT',self.open='16686', self.close='16676.4'
2022-12-19 00:00:01,523:INFO:pyemd2:main.py:126:handleKline:185189: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17419  20221218   231000    231959  1671376799  16675.1  16684.6
17420  20221218   232000    232959  1671377399  16684.5    16682
17421  20221218   233000    233959  1671377999    16682  16682.8
17422  20221218   234000    234959  1671378599  16682.8    16686
17423  20221218   235000    235959  1671379199    16686  16676.4
2022-12-19 00:00:01,528:INFO:pyemd2:main.py:127:handleKline:185189: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}
2022-12-19 00:00:01,708:INFO:pyemd2:main.py:190:insertFactor:185189: curDateTime:12190000, name:pyemd2, symbol:BTCUSDT, tradeDate:20221218, closeTime:235959, close:16676.4, total:947411.5003109, pct_pre:0.0002996775469594759, thd:-0.08105275281954738, side:sell 
127.0.0.1 - - [19/Dec/2022 00:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=3369 

self.closeSec=1671379799, self.tradeDate='20221219', self.openTime='000000', self.closeTime='000959', self.symbol='BTCUSDT', self.open='16676.4', self.close='16685.7'
2022-12-19 00:10:01,797:INFO:pyemd2:main.py:125:handleKline:185189: self.closeSec=1671379799, self.tradeDate='20221219', self.openTime='000000', self.closeTime='000959',self.symbol='BTCUSDT',self.open='16676.4', self.close='16685.7'
2022-12-19 00:10:01,825:INFO:pyemd2:main.py:126:handleKline:185189: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17420  20221218   232000    232959  1671377399  16684.5    16682
17421  20221218   233000    233959  1671377999    16682  16682.8
17422  20221218   234000    234959  1671378599  16682.8    16686
17423  20221218   235000    235959  1671379199    16686  16676.4
17424  20221219   000000    000959  1671379799  16676.4  16685.7
2022-12-19 00:10:01,828:INFO:pyemd2:main.py:127:handleKline:185189: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}


## /root/FIL/strategy/similarity/log.txt ----- -----

2022-12-19 00:00:01,536:INFO:testStrategy:main.py:102:handleKline:185174: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12235  20221218   231000    231959  1671376799  16675.1  16684.6
12236  20221218   232000    232959  1671377399  16684.5    16682
12237  20221218   233000    233959  1671377999    16682  16682.8
12238  20221218   234000    234959  1671378599  16682.8    16686
12239  20221218   235000    235959  1671379199    16686  16676.4
2022-12-19 00:00:01,539:INFO:testStrategy:main.py:103:handleKline:185174: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': True, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}
closeSell: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '73.25', 'enterprice': '16732.3', 'countrevence': '0', 'unrealprofit': '4094.675', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '16676.4', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
2022-12-19 00:00:02,368:INFO:testStrategy:main.py:253:closeSell:185174: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False, 'isCorr': False}
2022-12-19 00:00:02,368:INFO:testStrategy:main.py:254:closeSell:185174: ret = self.client.insertMarketUOrder("simulator",  BTCUSDT, 73.25, buy ), ret=InsertOrderReturn{'result': 'success', 'clientorderid': '41380F1671379202365I0L2'}
2022-12-19 00:00:02,427:INFO:testStrategy:main.py:172:insertFactor:185174: curDateTime:12190000, name:testStrategy, symbol:BTCUSDT, tradeDate:20221218, closeTime:235959, close:16676.4, total:1224415.3340249998, corrDate:20221203, corrVal:0.7339303100846063, side:buy 
127.0.0.1 - - [19/Dec/2022 00:00:02] "POST / HTTP/1.1" 200 -
2022-12-19 00:00:02,706:INFO:testStrategy:main.py:305:handleOrderNew:185174: handleOrderNew: data=OrderType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'clientorderid': '41380F1671379202365I0L2', 'symbol': 'BTCUSDT', 'gatewayorderid': 1671379202479651, 'quantity': '73.25', 'price': '16676.4', 'stopprice': '0', 'ordertype': '', 'side': 'BUY', 'status': 'FILLED', 'positionside': 'LONG', 'createtime': 1671379201755, 'updatetime': 1671379202479, 'tradetype': 'usdt', 'selfid': 41380, 'filltrades': [TradeType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'tradeid': 1671379202479, 'clientorderid': '41380F1671379202365I0L2', 'price': '16676.4', 'quantity': '73.25', 'commission': '1221.5463', 'commissionasset': 'USDT', 'tradetime': 1671379202479, 'tradetype': 'usdt', 'gatetype': 'simulator', 'handletime': 1671379202479}], 'gatetype': 'simulator', 'handletime': 0}
2022-12-19 00:00:02,984:INFO:testStrategy:main.py:308:handleOrderFilled:185174: handleOrderFilled: data=OrderType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'clientorderid': '41380F1671379202365I0L2', 'symbol': 'BTCUSDT', 'gatewayorderid': 1671379202479651, 'quantity': '73.25', 'price': '16676.4', 'stopprice': '0', 'ordertype': '', 'side': 'BUY', 'status': 'FILLED', 'positionside': 'LONG', 'createtime': 1671379201755, 'updatetime': 1671379202479, 'tradetype': 'usdt', 'selfid': 41380, 'filltrades': [TradeType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'tradeid': 1671379202479, 'clientorderid': '41380F1671379202365I0L2', 'price': '16676.4', 'quantity': '73.25', 'commission': '1221.5463', 'commissionasset': 'USDT', 'tradetime': 1671379202479, 'tradetype': 'usdt', 'gatetype': 'simulator', 'handletime': 1671379202479}], 'gatetype': 'simulator', 'handletime': 0}
127.0.0.1 - - [19/Dec/2022 00:00:02] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=3369 

self.closeSec=1671379799, self.tradeDate='20221219', self.openTime='000000', self.closeTime='000959', self.symbol='BTCUSDT', self.open='16676.4', self.close='16685.7'
2022-12-19 00:10:01,790:INFO:testStrategy:main.py:101:handleKline:185174: self.closeSec=1671379799, self.tradeDate='20221219', self.openTime='000000', self.closeTime='000959',self.symbol='BTCUSDT',self.open='16676.4', self.close='16685.7'
127.0.0.1 - - [19/Dec/2022 00:10:01] "POST / HTTP/1.1" 200 -
2022-12-19 00:10:01,813:INFO:testStrategy:main.py:102:handleKline:185174: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12236  20221218   232000    232959  1671377399  16684.5    16682
12237  20221218   233000    233959  1671377999    16682  16682.8
12238  20221218   234000    234959  1671378599  16682.8    16686
12239  20221218   235000    235959  1671379199    16686  16676.4
12240  20221219   000000    000959  1671379799  16676.4  16685.7
2022-12-19 00:10:01,813:INFO:testStrategy:main.py:103:handleKline:185174: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False, 'isCorr': False}


## /root/FIL/strategy/sr_min/log.txt ----- -----

127.0.0.1 - - [19/Dec/2022 00:10:01] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=0, self.total=1000000.0, self.flagDict['side']='', self.tradeCount=0, self.count=2168
self.closeSec=1671379799, self.tradeDate='20221219', self.openTime='000500', self.closeTime='000959', self.symbol='BTCUSDT', self.open=16681.9, self.close=16685.7, self.high=16685.7, self.low=16681.8, self.vol=212.88, self.amt=3551557.4843 
2022-12-19 00:10:01,740:INFO:sr_min:main.py:172:handleKline:449472: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5757  20221218   234500    234959  ...         0.0        0.0       0
5758  20221218   235000    235459  ...         0.0        0.0       0
5759  20221218   235500    235959  ...         0.0        0.0       0
5760  20221219   000000    000459  ...         0.0        0.0       0
5761  20221219   000500    000959  ...         0.0        0.0       0

[5 rows x 18 columns]
2022-12-19 00:10:01,740:INFO:sr_min:main.py:175:handleKline:449472: self.closeSec=1671379799, self.tradeDate='20221219', self.openTime='000500', self.closeTime='000959',self.symbol='BTCUSDT',self.open=16681.9, self.close=16685.7, self.high=16685.7, self.low=16681.8, self.vol=212.88, self.amt=3551557.4843, ukdf['pct'].iloc[-1]=0.000234 , ukdf['amount'].iloc[-1]=3551557.4843, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5761, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': []}
type(curSign)=<class 'int'>, curSign=0, self.sign=0
127.0.0.1 - - [19/Dec/2022 00:15:00] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=0, self.total=1000000.0, self.flagDict['side']='', self.tradeCount=0, self.count=2169
self.closeSec=1671380099, self.tradeDate='20221219', self.openTime='001000', self.closeTime='001459', self.symbol='BTCUSDT', self.open=16685.6, self.close=16688.7, self.high=16690.0, self.low=16684.3, self.vol=400.365, self.amt=6681057.5348 
2022-12-19 00:15:00,628:INFO:sr_min:main.py:172:handleKline:449472: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5758  20221218   235000    235459  ...         0.0        0.0       0
5759  20221218   235500    235959  ...         0.0        0.0       0
5760  20221219   000000    000459  ...         0.0        0.0       0
5761  20221219   000500    000959  ...         0.0        0.0       0
5762  20221219   001000    001459  ...         0.0        0.0       0

[5 rows x 18 columns]
2022-12-19 00:15:00,629:INFO:sr_min:main.py:175:handleKline:449472: self.closeSec=1671380099, self.tradeDate='20221219', self.openTime='001000', self.closeTime='001459',self.symbol='BTCUSDT',self.open=16685.6, self.close=16688.7, self.high=16690.0, self.low=16684.3, self.vol=400.365, self.amt=6681057.5348, ukdf['pct'].iloc[-1]=0.00018 , ukdf['amount'].iloc[-1]=6681057.5348, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5762, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': []}
type(curSign)=<class 'int'>, curSign=0, self.sign=0


## /root/FIL/strategy/s_rsrs/log.txt ----- -----

723  20221218   120000    155959  1671350399  ...    723  1.003667  0.955392     1.0
724  20221218   160000    195959  1671364799  ...    724  1.060150  1.102955     1.0

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '53.436', 'enterprice': '17756.3', 'countrevence': '0', 'unrealprofit': '-56214.36961529448', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '16704.30565882', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=1, self.sign=1
--handleKline--:  version='2.0.0', self.name='s_rsrs', self.symbol='BTCUSDT', interval='4h', intervalSec=14400, wid=25, thd=0.6, self.sign=1, self.total=947876.8211532, self.flagDict['side']='buy', self.tradeCount=6, self.count=140
self.closeSec=1671379199, self.tradeDate='20221218', self.openTime='200000', self.closeTime='235959', self.symbol='BTCUSDT', self.open=16702.2, self.close=16676.4, self.high=16727.9, self.low=16663.3, self.vol=25280.386, self.amt=422017873.02 
127.0.0.1 - - [19/Dec/2022 00:00:01] "POST / HTTP/1.1" 200 -
2022-12-19 00:00:01,287:INFO:s_rsrs:main.py:141:handleKline:185271: self.closeSec=1671379199, self.tradeDate='20221218', self.openTime='200000', self.closeTime='235959',self.symbol='BTCUSDT',self.open=16702.2, self.close=16676.4, self.high=16727.9, self.low=16663.3, self.vol=25280.386, self.amt=422017873.02 
2022-12-19 00:00:01,311:INFO:s_rsrs:main.py:142:handleKline:185271: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime  ...        vol           amt       pct
721  20221218   040000    075959  ...  33778.374  5.650731e+08  0.005023
722  20221218   080000    115959  ...  19014.025  3.180544e+08 -0.001879
723  20221218   120000    155959  ...  26928.603  4.510137e+08  0.000203
724  20221218   160000    195959  ...  35341.001  5.903013e+08 -0.002252
725  20221218   200000    235959  ...  25280.386  4.220179e+08 -0.001545

[5 rows x 11 columns]
2022-12-19 00:00:03,340:INFO:s_rsrs:main.py:151:handleKline:185271: df_s.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec  ...  index      beta    zscore  signal
721  20221218   040000    075959  1671321599  ...    721  0.914646  0.718202     1.0
722  20221218   080000    115959  1671335999  ...    722  0.956051  0.829937     1.0
723  20221218   120000    155959  1671350399  ...    723  1.003667  0.955392     1.0
724  20221218   160000    195959  1671364799  ...    724  1.060150  1.102955     1.0
725  20221218   200000    235959  1671379199  ...    725  1.132630  1.292668     1.0

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '53.436', 'enterprice': '17756.3', 'countrevence': '0', 'unrealprofit': '-57708.57648465252', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '16676.34310793', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=1, self.sign=1


