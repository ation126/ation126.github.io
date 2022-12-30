# 20221231 00:16:01

## /root/FIL/strategy/amihud/log.txt ----- -----

127.0.0.1 - - [31/Dec/2022 00:10:01] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=993672.4896432, self.flagDict['side']='sell', self.tradeCount=2, self.count=9626
self.closeSec=1672416599, self.tradeDate='20221231', self.openTime='000500', self.closeTime='000959', self.symbol='BTCUSDT', self.open=16553.5, self.close=16552.1, self.high=16559.6, self.low=16540.9, self.vol=1678.726, self.amt=27783336.522 
2022-12-31 00:10:01,501:INFO:amihud:main.py:172:handleKline:200676: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5757  20221230   234500    234959  ...         0.0        0.0       0
5758  20221230   235000    235459  ...         0.0        0.0       0
5759  20221230   235500    235959  ...         0.0        0.0       0
5760  20221231   000000    000459  ...         0.0        0.0       0
5761  20221231   000500    000959  ...         0.0        0.0       0

[5 rows x 18 columns]
2022-12-31 00:10:01,502:INFO:amihud:main.py:175:handleKline:200676: self.closeSec=1672416599, self.tradeDate='20221231', self.openTime='000500', self.closeTime='000959',self.symbol='BTCUSDT',self.open=16553.5, self.close=16552.1, self.high=16559.6, self.low=16540.9, self.vol=1678.726, self.amt=27783336.522, ukdf['pct'].iloc[-1]=-7.9e-05 , ukdf['amount'].iloc[-1]=27783336.522, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5761, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '60.176', 'enterprice': '16529.3', 'countrevence': '0', 'unrealprofit': '-1372.0128', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '16552.1', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1
127.0.0.1 - - [31/Dec/2022 00:15:00] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=993672.4896432, self.flagDict['side']='sell', self.tradeCount=2, self.count=9627
self.closeSec=1672416899, self.tradeDate='20221231', self.openTime='001000', self.closeTime='001459', self.symbol='BTCUSDT', self.open=16552.1, self.close=16527.9, self.high=16555.5, self.low=16526.8, self.vol=2041.856, self.amt=33765356.4249 
2022-12-31 00:15:00,728:INFO:amihud:main.py:172:handleKline:200676: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5758  20221230   235000    235459  ...         0.0        0.0       0
5759  20221230   235500    235959  ...         0.0        0.0       0
5760  20221231   000000    000459  ...         0.0        0.0       0
5761  20221231   000500    000959  ...         0.0        0.0       0
5762  20221231   001000    001459  ...         0.0        0.0       0

[5 rows x 18 columns]
2022-12-31 00:15:00,729:INFO:amihud:main.py:175:handleKline:200676: self.closeSec=1672416899, self.tradeDate='20221231', self.openTime='001000', self.closeTime='001459',self.symbol='BTCUSDT',self.open=16552.1, self.close=16527.9, self.high=16555.5, self.low=16526.8, self.vol=2041.856, self.amt=33765356.4249, ukdf['pct'].iloc[-1]=-0.001462 , ukdf['amount'].iloc[-1]=33765356.4249, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5762, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '60.176', 'enterprice': '16529.3', 'countrevence': '0', 'unrealprofit': '42.0182019064', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '16528.60174485', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1


## /root/FIL/strategy/factorcheck/log.txt ----- -----


self.closeSec=1672416599, self.tradeDate='20221231', self.openTime='000500', self.closeTime='000959', self.symbol='BTCUSDT', self.open=16553.5, self.close=16552.1, self.high=16559.6, self.low=16540.9 
2022-12-31 00:10:01,453:INFO:factorcheck2:main.py:126:handleKline:185239: self.closeSec=1672416599, self.tradeDate='20221231', self.openTime='000500', self.closeTime='000959',self.symbol='BTCUSDT',self.open=16553.5, self.close=16552.1, self.high=16559.6, self.low=16540.9   
127.0.0.1 - - [31/Dec/2022 00:10:01] "POST / HTTP/1.1" 200 -
2022-12-31 00:10:01,489:INFO:factorcheck2:main.py:127:handleKline:185239: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1437  20221230   234500    234959  1672415399  ...  16545.9  0.000163   1725    3
1438  20221230   235000    235459  1672415699  ...  16533.4 -0.000882   1726    4
1439  20221230   235500    235959  1672415999  ...  16534.4  0.000792   1727    5
1440  20221231   000000    000459  1672416299  ...  16547.6  0.000351   1440    0
1441  20221231   000500    000959  1672416599  ...  16540.9 -0.000079   1441    1

[5 rows x 11 columns]
2022-12-31 00:10:01,490:INFO:factorcheck2:main.py:128:handleKline:185239: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=3, self.factor=0.5279262573543441, self.count=10193 

self.closeSec=1672416899, self.tradeDate='20221231', self.openTime='001000', self.closeTime='001459', self.symbol='BTCUSDT', self.open=16552.1, self.close=16527.9, self.high=16555.5, self.low=16526.8 
2022-12-31 00:15:00,575:INFO:factorcheck2:main.py:126:handleKline:185239: self.closeSec=1672416899, self.tradeDate='20221231', self.openTime='001000', self.closeTime='001459',self.symbol='BTCUSDT',self.open=16552.1, self.close=16527.9, self.high=16555.5, self.low=16526.8   
127.0.0.1 - - [31/Dec/2022 00:15:00] "POST / HTTP/1.1" 200 -
2022-12-31 00:15:00,700:INFO:factorcheck2:main.py:127:handleKline:185239: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1438  20221230   235000    235459  1672415699  ...  16533.4 -0.000882   1726    4
1439  20221230   235500    235959  1672415999  ...  16534.4  0.000792   1727    5
1440  20221231   000000    000459  1672416299  ...  16547.6  0.000351   1440    0
1441  20221231   000500    000959  1672416599  ...  16540.9 -0.000079   1441    1
1442  20221231   001000    001459  1672416899  ...  16526.8 -0.001462   1442    2

[5 rows x 11 columns]
2022-12-31 00:15:00,702:INFO:factorcheck2:main.py:128:handleKline:185239: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}


## /root/FIL/strategy/logic/log.txt ----- -----

2022-12-31 00:00:22,341:DEBUG:logic:main.py:454:getModel:174970: df_s.iloc[-5:,:] :
          date closeTime     open  ...    alpha58   alpha67   alpha72
5802  20221230    212959  16490.9  ...  42.916667  0.423776  0.583338
5803  20221230    215959  16478.4  ...  42.916667  0.414278  0.596611
5804  20221230    222959  16462.1  ...  43.333333  0.423390  0.605819
5805  20221230    225959  16473.4  ...  42.916667  0.387510  0.614488
5806  20221230    232959  16407.0  ...  43.333333  0.452382  0.604120

[5 rows x 33 columns]
0.5147058823529411
acc is : 0.5147058823529411
2022-12-31 00:00:22,459:INFO:logic:main.py:459:getModel:174970: df_pred.iloc[-5:,:] :
     pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
539     1  0.494396  0.505604       0  ...  0.983411   1.0    0.0  0.984899
540     1  0.489442  0.510558       1  ...  0.984092   1.0    0.0  0.985581
541     1  0.497761  0.502239       0  ...  0.980119   1.0    0.0  0.981603
542     1  0.475765  0.524235       1  ...  0.985561   1.0    0.0  0.987053
543     0  0.516729  0.483271       1  ...  0.988530   1.0    0.0  0.990027

[5 rows x 10 columns]
2022-12-31 00:00:22,488:INFO:logic:main.py:469:getModel:174970: df_panel.iloc[-5:,:] :
    pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
45     1  0.494090  0.505910       0  ...  0.983411   1.0    0.0  0.985501
46     1  0.488875  0.511125       1  ...  0.984092   1.0    0.0  0.984692
47     1  0.497726  0.502274       0  ...  0.980119   1.0    0.0  0.980717
48     1  0.475393  0.524607       1  ...  0.985561   1.0    0.0  0.985856
49     0  0.516729  0.483271       1  ...  0.988530   1.0    0.0  0.990027

[5 rows x 10 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '42.528', 'enterprice': '16701.5', 'countrevence': '0', 'unrealprofit': '-6511.0368', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '16548.4', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}


## /root/FIL/strategy/modifiedmom/log.txt ----- -----

2022-12-31 00:00:01,649:INFO:modifiedmom:main.py:145:handleKline:185213: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
571  20221230   231000    231959  1672413599  16417.1  16502.5  0.005196
572  20221230   232000    232959  1672414199  16502.5    16498 -0.000273
573  20221230   233000    233959  1672414799    16498  16535.9  0.002297
574  20221230   234000    234959  1672415399  16535.9  16548.7  0.000774
575  20221230   235000    235959  1672415999  16548.8  16547.6 -0.000066
2022-12-31 00:00:01,653:INFO:modifiedmom:main.py:146:handleKline:185213: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': True, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True}
closeSell: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '55.254', 'enterprice': '16596.7', 'countrevence': '0', 'unrealprofit': '2707.446', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '16547.7', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
2022-12-31 00:00:02,230:INFO:modifiedmom:main.py:287:closeSell:185213: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False}
2022-12-31 00:00:02,230:INFO:modifiedmom:main.py:288:closeSell:185213: ret = self.client.insertMarketUOrder("simulator",  BTCUSDT, 55.254, buy ), ret=InsertOrderReturn{'result': 'success', 'clientorderid': '41444F1672416002227I0L59'}
2022-12-31 00:00:02,262:INFO:modifiedmom:main.py:206:insertFactor:185213: curDateTime:12310000, name:modifiedmom, symbol:BTCUSDT, tradeDate:20221230, closeTime:235959, close:16547.6, total:916117.0277382, mom:-0.0007565167877024992, thd:0.0, side:buy 
127.0.0.1 - - [31/Dec/2022 00:00:02] "POST / HTTP/1.1" 200 -
2022-12-31 00:00:02,370:INFO:modifiedmom:main.py:316:handleOrderNew:185213: handleOrderNew: data=OrderType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'clientorderid': '41444F1672416002227I0L59', 'symbol': 'BTCUSDT', 'gatewayorderid': 1672416002336032, 'quantity': '55.254', 'price': '16547.7', 'stopprice': '0', 'ordertype': '', 'side': 'BUY', 'status': 'FILLED', 'positionside': 'LONG', 'createtime': 1672416001830, 'updatetime': 1672416002336, 'tradetype': 'usdt', 'selfid': 41444, 'filltrades': [TradeType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'tradeid': 1672416002336, 'clientorderid': '41444F1672416002227I0L59', 'price': '16547.7', 'quantity': '55.254', 'commission': '914.3266158', 'commissionasset': 'USDT', 'tradetime': 1672416002336, 'tradetype': 'usdt', 'gatetype': 'simulator', 'handletime': 1672416002336}], 'gatetype': 'simulator', 'handletime': 0}
2022-12-31 00:00:02,688:INFO:modifiedmom:main.py:319:handleOrderFilled:185213: handleOrderFilled: data=OrderType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'clientorderid': '41444F1672416002227I0L59', 'symbol': 'BTCUSDT', 'gatewayorderid': 1672416002336032, 'quantity': '55.254', 'price': '16547.7', 'stopprice': '0', 'ordertype': '', 'side': 'BUY', 'status': 'FILLED', 'positionside': 'LONG', 'createtime': 1672416001830, 'updatetime': 1672416002336, 'tradetype': 'usdt', 'selfid': 41444, 'filltrades': [TradeType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'tradeid': 1672416002336, 'clientorderid': '41444F1672416002227I0L59', 'price': '16547.7', 'quantity': '55.254', 'commission': '914.3266158', 'commissionasset': 'USDT', 'tradetime': 1672416002336, 'tradetype': 'usdt', 'gatetype': 'simulator', 'handletime': 1672416002336}], 'gatetype': 'simulator', 'handletime': 0}
127.0.0.1 - - [31/Dec/2022 00:00:02] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=5096 

self.closeSec=1672416599, self.tradeDate='20221231', self.openTime='000000', self.closeTime='000959', self.symbol='BTCUSDT', self.open='16547.7', self.close='16552.1'
2022-12-31 00:10:01,525:INFO:modifiedmom:main.py:144:handleKline:185213: self.closeSec=1672416599, self.tradeDate='20221231', self.openTime='000000', self.closeTime='000959',self.symbol='BTCUSDT',self.open='16547.7', self.close='16552.1'
127.0.0.1 - - [31/Dec/2022 00:10:01] "POST / HTTP/1.1" 200 -
2022-12-31 00:10:01,563:INFO:modifiedmom:main.py:145:handleKline:185213: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
572  20221230   232000    232959  1672414199  16502.5    16498 -0.000273
573  20221230   233000    233959  1672414799    16498  16535.9  0.002297
574  20221230   234000    234959  1672415399  16535.9  16548.7  0.000774
575  20221230   235000    235959  1672415999  16548.8  16547.6 -0.000066
576  20221231   000000    000959  1672416599  16547.7  16552.1  0.000272
2022-12-31 00:10:01,563:INFO:modifiedmom:main.py:146:handleKline:185213: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False}


## /root/FIL/strategy/pyemd/log.txt ----- -----

2022-12-30 23:50:00,574:INFO:pyemd2:main.py:127:handleKline:185189: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=5096 

self.closeSec=1672415999, self.tradeDate='20221230', self.openTime='235000', self.closeTime='235959', self.symbol='BTCUSDT', self.open='16548.8', self.close='16547.6'
127.0.0.1 - - [31/Dec/2022 00:00:01] "POST / HTTP/1.1" 200 -
2022-12-31 00:00:01,601:INFO:pyemd2:main.py:125:handleKline:185189: self.closeSec=1672415999, self.tradeDate='20221230', self.openTime='235000', self.closeTime='235959',self.symbol='BTCUSDT',self.open='16548.8', self.close='16547.6'
2022-12-31 00:00:01,632:INFO:pyemd2:main.py:126:handleKline:185189: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17419  20221230   231000    231959  1672413599  16417.1  16502.5
17420  20221230   232000    232959  1672414199  16502.5    16498
17421  20221230   233000    233959  1672414799    16498  16535.9
17422  20221230   234000    234959  1672415399  16535.9  16548.7
17423  20221230   235000    235959  1672415999  16548.8  16547.6
2022-12-31 00:00:01,636:INFO:pyemd2:main.py:127:handleKline:185189: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}
2022-12-31 00:00:01,841:INFO:pyemd2:main.py:190:insertFactor:185189: curDateTime:12310000, name:pyemd2, symbol:BTCUSDT, tradeDate:20221230, closeTime:235959, close:16547.6, total:943801.2083061, pct_pre:-0.00591876302067651, thd:-0.04848076267881135, side:sell 

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=5097 

self.closeSec=1672416599, self.tradeDate='20221231', self.openTime='000000', self.closeTime='000959', self.symbol='BTCUSDT', self.open='16547.7', self.close='16552.1'
127.0.0.1 - - [31/Dec/2022 00:10:01] "POST / HTTP/1.1" 200 -
2022-12-31 00:10:01,535:INFO:pyemd2:main.py:125:handleKline:185189: self.closeSec=1672416599, self.tradeDate='20221231', self.openTime='000000', self.closeTime='000959',self.symbol='BTCUSDT',self.open='16547.7', self.close='16552.1'
2022-12-31 00:10:01,542:INFO:pyemd2:main.py:126:handleKline:185189: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17420  20221230   232000    232959  1672414199  16502.5    16498
17421  20221230   233000    233959  1672414799    16498  16535.9
17422  20221230   234000    234959  1672415399  16535.9  16548.7
17423  20221230   235000    235959  1672415999  16548.8  16547.6
17424  20221231   000000    000959  1672416599  16547.7  16552.1
2022-12-31 00:10:01,543:INFO:pyemd2:main.py:127:handleKline:185189: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}


## /root/FIL/strategy/similarity/log.txt ----- -----

2022-12-31 00:00:01,631:INFO:testStrategy:main.py:102:handleKline:185174: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12235  20221230   231000    231959  1672413599  16417.1  16502.5
12236  20221230   232000    232959  1672414199  16502.5    16498
12237  20221230   233000    233959  1672414799    16498  16535.9
12238  20221230   234000    234959  1672415399  16535.9  16548.7
12239  20221230   235000    235959  1672415999  16548.8  16547.6
2022-12-31 00:00:01,633:INFO:testStrategy:main.py:103:handleKline:185174: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': True, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}
closeSell: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '75.691', 'enterprice': '16614', 'countrevence': '0', 'unrealprofit': '5018.3133', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '16547.7', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
2022-12-31 00:00:02,247:INFO:testStrategy:main.py:253:closeSell:185174: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False, 'isCorr': False}
2022-12-31 00:00:02,250:INFO:testStrategy:main.py:254:closeSell:185174: ret = self.client.insertMarketUOrder("simulator",  BTCUSDT, 75.691, buy ), ret=InsertOrderReturn{'result': 'success', 'clientorderid': '41445F1672416002246I0L2'}
2022-12-31 00:00:02,270:INFO:testStrategy:main.py:172:insertFactor:185174: curDateTime:12310000, name:testStrategy, symbol:BTCUSDT, tradeDate:20221230, closeTime:235959, close:16547.6, total:1256272.743726, corrDate:20221215, corrVal:0.5578197976896403, side:buy 
127.0.0.1 - - [31/Dec/2022 00:00:02] "POST / HTTP/1.1" 200 -
2022-12-31 00:00:02,693:INFO:testStrategy:main.py:305:handleOrderNew:185174: handleOrderNew: data=OrderType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'clientorderid': '41445F1672416002246I0L2', 'symbol': 'BTCUSDT', 'gatewayorderid': 1672416002351793, 'quantity': '75.691', 'price': '16547.7', 'stopprice': '0', 'ordertype': '', 'side': 'BUY', 'status': 'FILLED', 'positionside': 'LONG', 'createtime': 1672416001812, 'updatetime': 1672416002351, 'tradetype': 'usdt', 'selfid': 41445, 'filltrades': [TradeType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'tradeid': 1672416002351, 'clientorderid': '41445F1672416002246I0L2', 'price': '16547.7', 'quantity': '75.691', 'commission': '1252.5119607', 'commissionasset': 'USDT', 'tradetime': 1672416002351, 'tradetype': 'usdt', 'gatetype': 'simulator', 'handletime': 1672416002351}], 'gatetype': 'simulator', 'handletime': 0}
127.0.0.1 - - [31/Dec/2022 00:00:03] "POST / HTTP/1.1" 200 -
2022-12-31 00:00:03,004:INFO:testStrategy:main.py:308:handleOrderFilled:185174: handleOrderFilled: data=OrderType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'clientorderid': '41445F1672416002246I0L2', 'symbol': 'BTCUSDT', 'gatewayorderid': 1672416002351793, 'quantity': '75.691', 'price': '16547.7', 'stopprice': '0', 'ordertype': '', 'side': 'BUY', 'status': 'FILLED', 'positionside': 'LONG', 'createtime': 1672416001812, 'updatetime': 1672416002351, 'tradetype': 'usdt', 'selfid': 41445, 'filltrades': [TradeType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'tradeid': 1672416002351, 'clientorderid': '41445F1672416002246I0L2', 'price': '16547.7', 'quantity': '75.691', 'commission': '1252.5119607', 'commissionasset': 'USDT', 'tradetime': 1672416002351, 'tradetype': 'usdt', 'gatetype': 'simulator', 'handletime': 1672416002351}], 'gatetype': 'simulator', 'handletime': 0}
127.0.0.1 - - [31/Dec/2022 00:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=5097 

self.closeSec=1672416599, self.tradeDate='20221231', self.openTime='000000', self.closeTime='000959', self.symbol='BTCUSDT', self.open='16547.7', self.close='16552.1'
2022-12-31 00:10:01,553:INFO:testStrategy:main.py:101:handleKline:185174: self.closeSec=1672416599, self.tradeDate='20221231', self.openTime='000000', self.closeTime='000959',self.symbol='BTCUSDT',self.open='16547.7', self.close='16552.1'
2022-12-31 00:10:01,566:INFO:testStrategy:main.py:102:handleKline:185174: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12236  20221230   232000    232959  1672414199  16502.5    16498
12237  20221230   233000    233959  1672414799    16498  16535.9
12238  20221230   234000    234959  1672415399  16535.9  16548.7
12239  20221230   235000    235959  1672415999  16548.8  16547.6
12240  20221231   000000    000959  1672416599  16547.7  16552.1
2022-12-31 00:10:01,566:INFO:testStrategy:main.py:103:handleKline:185174: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False, 'isCorr': False}


## /root/FIL/strategy/sr_min/log.txt ----- -----

127.0.0.1 - - [31/Dec/2022 00:10:01] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=0, self.total=1000000.0, self.flagDict['side']='', self.tradeCount=0, self.count=5624
self.closeSec=1672416599, self.tradeDate='20221231', self.openTime='000500', self.closeTime='000959', self.symbol='BTCUSDT', self.open=16553.5, self.close=16552.1, self.high=16559.6, self.low=16540.9, self.vol=1678.726, self.amt=27783336.522 
2022-12-31 00:10:01,500:INFO:sr_min:main.py:172:handleKline:449472: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5757  20221230   234500    234959  ...         0.0        0.0       0
5758  20221230   235000    235459  ...         0.0        0.0       0
5759  20221230   235500    235959  ...         0.0        0.0       0
5760  20221231   000000    000459  ...         0.0        0.0       0
5761  20221231   000500    000959  ...         0.0        0.0       0

[5 rows x 18 columns]
2022-12-31 00:10:01,500:INFO:sr_min:main.py:175:handleKline:449472: self.closeSec=1672416599, self.tradeDate='20221231', self.openTime='000500', self.closeTime='000959',self.symbol='BTCUSDT',self.open=16553.5, self.close=16552.1, self.high=16559.6, self.low=16540.9, self.vol=1678.726, self.amt=27783336.522, ukdf['pct'].iloc[-1]=-7.9e-05 , ukdf['amount'].iloc[-1]=27783336.522, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5761, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': []}
type(curSign)=<class 'int'>, curSign=0, self.sign=0
--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=0, self.total=1000000.0, self.flagDict['side']='', self.tradeCount=0, self.count=5625
self.closeSec=1672416899, self.tradeDate='20221231', self.openTime='001000', self.closeTime='001459', self.symbol='BTCUSDT', self.open=16552.1, self.close=16527.9, self.high=16555.5, self.low=16526.8, self.vol=2041.856, self.amt=33765356.4249 
127.0.0.1 - - [31/Dec/2022 00:15:00] "POST / HTTP/1.1" 200 -
2022-12-31 00:15:00,731:INFO:sr_min:main.py:172:handleKline:449472: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5758  20221230   235000    235459  ...         0.0        0.0       0
5759  20221230   235500    235959  ...         0.0        0.0       0
5760  20221231   000000    000459  ...         0.0        0.0       0
5761  20221231   000500    000959  ...         0.0        0.0       0
5762  20221231   001000    001459  ...         0.0        0.0       0

[5 rows x 18 columns]
2022-12-31 00:15:00,731:INFO:sr_min:main.py:175:handleKline:449472: self.closeSec=1672416899, self.tradeDate='20221231', self.openTime='001000', self.closeTime='001459',self.symbol='BTCUSDT',self.open=16552.1, self.close=16527.9, self.high=16555.5, self.low=16526.8, self.vol=2041.856, self.amt=33765356.4249, ukdf['pct'].iloc[-1]=-0.001462 , ukdf['amount'].iloc[-1]=33765356.4249, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5762, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': []}
type(curSign)=<class 'int'>, curSign=0, self.sign=0


## /root/FIL/strategy/s_rsrs/log.txt ----- -----

723  20221230   120000    155959  1672387199  ...    723  0.592312  0.542793     NaN
724  20221230   160000    195959  1672401599  ...    724  0.616368  0.623980     1.0

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '53.898', 'enterprice': '16630.1', 'countrevence': '0', 'unrealprofit': '-7572.669', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '16489.6', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=1, self.sign=1
127.0.0.1 - - [31/Dec/2022 00:00:01] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='s_rsrs', self.symbol='BTCUSDT', interval='4h', intervalSec=14400, wid=25, thd=0.6, self.sign=1, self.total=895432.8006702, self.flagDict['side']='buy', self.tradeCount=8, self.count=212
self.closeSec=1672415999, self.tradeDate='20221230', self.openTime='200000', self.closeTime='235959', self.symbol='BTCUSDT', self.open=16489.6, self.close=16547.7, self.high=16568.5, self.low=16320.0, self.vol=104487.149, self.amt=1719910455.125 
2022-12-31 00:00:01,477:INFO:s_rsrs:main.py:141:handleKline:185271: self.closeSec=1672415999, self.tradeDate='20221230', self.openTime='200000', self.closeTime='235959',self.symbol='BTCUSDT',self.open=16489.6, self.close=16547.7, self.high=16568.5, self.low=16320.0, self.vol=104487.149, self.amt=1719910455.125 
2022-12-31 00:00:01,527:INFO:s_rsrs:main.py:142:handleKline:185271: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime  ...         vol           amt       pct
721  20221230   040000    075959  ...   32491.913  5.394451e+08  0.001337
722  20221230   080000    115959  ...   19882.213  3.302067e+08 -0.002189
723  20221230   120000    155959  ...   62732.710  1.035995e+09 -0.007617
724  20221230   160000    195959  ...   38916.057  6.420308e+08  0.001336
725  20221230   200000    235959  ...  104487.149  1.719910e+09  0.003530

[5 rows x 11 columns]
2022-12-31 00:00:03,103:INFO:s_rsrs:main.py:151:handleKline:185271: df_s.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec  ...  index      beta    zscore  signal
721  20221230   040000    075959  1672358399  ...    721  0.637508  0.605011     1.0
722  20221230   080000    115959  1672372799  ...    722  0.648691  0.657817     1.0
723  20221230   120000    155959  1672387199  ...    723  0.592312  0.542793     NaN
724  20221230   160000    195959  1672401599  ...    724  0.616368  0.623980     1.0
725  20221230   200000    235959  1672415999  ...    725  0.537523  0.446099     NaN

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '53.898', 'enterprice': '16630.1', 'countrevence': '0', 'unrealprofit': '-4441.1952', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '16547.7', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-9223372036854775808, self.sign=1


