# 20230111 00:16:02

## /root/FIL/strategy/amihud/log.txt ----- -----

127.0.0.1 - - [11/Jan/2023 00:10:01] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=993672.4896432, self.flagDict['side']='sell', self.tradeCount=2, self.count=12794
self.closeSec=1673366999, self.tradeDate='20230111', self.openTime='000500', self.closeTime='000959', self.symbol='BTCUSDT', self.open=17324.1, self.close=17317.7, self.high=17324.3, self.low=17312.8, self.vol=801.25, self.amt=13877301.0191 
2023-01-11 00:10:01,481:INFO:amihud:main.py:172:handleKline:200676: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5757  20230110   234500    234959  ...         0.0        0.0       0
5758  20230110   235000    235459  ...         0.0        0.0       0
5759  20230110   235500    235959  ...         0.0        0.0       0
5760  20230111   000000    000459  ...         0.0        0.0       0
5761  20230111   000500    000959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-01-11 00:10:01,481:INFO:amihud:main.py:175:handleKline:200676: self.closeSec=1673366999, self.tradeDate='20230111', self.openTime='000500', self.closeTime='000959',self.symbol='BTCUSDT',self.open=17324.1, self.close=17317.7, self.high=17324.3, self.low=17312.8, self.vol=801.25, self.amt=13877301.0191, ukdf['pct'].iloc[-1]=-0.000369 , ukdf['amount'].iloc[-1]=13877301.0191, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5761, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '60.176', 'enterprice': '16529.3', 'countrevence': '0', 'unrealprofit': '-47346.4768', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '17316.1', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1
127.0.0.1 - - [11/Jan/2023 00:15:00] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=993672.4896432, self.flagDict['side']='sell', self.tradeCount=2, self.count=12795
self.closeSec=1673367299, self.tradeDate='20230111', self.openTime='001000', self.closeTime='001459', self.symbol='BTCUSDT', self.open=17317.2, self.close=17324.8, self.high=17324.8, self.low=17308.0, self.vol=903.347, self.amt=15642632.1947 
2023-01-11 00:15:00,616:INFO:amihud:main.py:172:handleKline:200676: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5758  20230110   235000    235459  ...         0.0        0.0       0
5759  20230110   235500    235959  ...         0.0        0.0       0
5760  20230111   000000    000459  ...         0.0        0.0       0
5761  20230111   000500    000959  ...         0.0        0.0       0
5762  20230111   001000    001459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-01-11 00:15:00,616:INFO:amihud:main.py:175:handleKline:200676: self.closeSec=1673367299, self.tradeDate='20230111', self.openTime='001000', self.closeTime='001459',self.symbol='BTCUSDT',self.open=17317.2, self.close=17324.8, self.high=17324.8, self.low=17308.0, self.vol=903.347, self.amt=15642632.1947, ukdf['pct'].iloc[-1]=0.00041 , ukdf['amount'].iloc[-1]=15642632.1947, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5762, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '60.176', 'enterprice': '16529.3', 'countrevence': '0', 'unrealprofit': '-47870.008', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '17324.8', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1


## /root/FIL/strategy/factorcheck/log.txt ----- -----

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=143, self.factor=0.512980873322407, self.count=13360 

self.closeSec=1673366999, self.tradeDate='20230111', self.openTime='000500', self.closeTime='000959', self.symbol='BTCUSDT', self.open=17324.1, self.close=17317.7, self.high=17324.3, self.low=17312.8 
2023-01-11 00:10:01,413:INFO:factorcheck2:main.py:126:handleKline:185239: self.closeSec=1673366999, self.tradeDate='20230111', self.openTime='000500', self.closeTime='000959',self.symbol='BTCUSDT',self.open=17324.1, self.close=17317.7, self.high=17324.3, self.low=17312.8   
2023-01-11 00:10:01,438:INFO:factorcheck2:main.py:127:handleKline:185239: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1437  20230110   234500    234959  1673365799  ...  17263.3  0.000927   1725    3
1438  20230110   235000    235459  1673366099  ...  17282.5  0.001348   1726    4
1439  20230110   235500    235959  1673366399  ...  17304.1  0.000647   1727    5
1440  20230111   000000    000459  1673366699  ...  17312.5  0.000410   1440    0
1441  20230111   000500    000959  1673366999  ...  17312.8 -0.000369   1441    1

[5 rows x 11 columns]
2023-01-11 00:10:01,438:INFO:factorcheck2:main.py:128:handleKline:185239: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}
127.0.0.1 - - [11/Jan/2023 00:15:00] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=143, self.factor=0.512980873322407, self.count=13361 

self.closeSec=1673367299, self.tradeDate='20230111', self.openTime='001000', self.closeTime='001459', self.symbol='BTCUSDT', self.open=17317.2, self.close=17324.8, self.high=17324.8, self.low=17308.0 
2023-01-11 00:15:00,560:INFO:factorcheck2:main.py:126:handleKline:185239: self.closeSec=1673367299, self.tradeDate='20230111', self.openTime='001000', self.closeTime='001459',self.symbol='BTCUSDT',self.open=17317.2, self.close=17324.8, self.high=17324.8, self.low=17308.0   
2023-01-11 00:15:00,605:INFO:factorcheck2:main.py:127:handleKline:185239: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1438  20230110   235000    235459  1673366099  ...  17282.5  0.001348   1726    4
1439  20230110   235500    235959  1673366399  ...  17304.1  0.000647   1727    5
1440  20230111   000000    000459  1673366699  ...  17312.5  0.000410   1440    0
1441  20230111   000500    000959  1673366999  ...  17312.8 -0.000369   1441    1
1442  20230111   001000    001459  1673367299  ...  17308.0  0.000410   1442    2

[5 rows x 11 columns]
2023-01-11 00:15:00,605:INFO:factorcheck2:main.py:128:handleKline:185239: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}


## /root/FIL/strategy/logic/log.txt ----- -----

2023-01-11 00:00:18,797:DEBUG:logic:main.py:456:getModel:726423: df_s.iloc[-5:,:] :
          date closeTime     open  ...    alpha58   alpha67   alpha72
5802  20230110    212959  17216.2  ...  52.916667  0.542722  0.568648
5803  20230110    215959  17229.3  ...  53.333333  0.547968  0.567621
5804  20230110    222959  17238.7  ...  53.333333  0.560503  0.560464
5805  20230110    225959  17261.7  ...  53.333333  0.569909  0.541635
5806  20230110    232959  17279.4  ...  53.333333  0.591387  0.517986

[5 rows x 33 columns]
0.5533088235294118
acc is : 0.5533088235294118
2023-01-11 00:00:18,876:INFO:logic:main.py:461:getModel:726423: df_pred.iloc[-5:,:] :
     pred    prob_0    prob_1  actual  ...  nav  sign   cost_        bm
539     0  0.501917  0.498083       1  ...  NaN   NaN -0.0016  1.046832
540     0  0.502147  0.497853       1  ...  NaN   NaN -0.0016  1.048222
541     0  0.510551  0.489449       1  ...  NaN   NaN -0.0016  1.049297
542     0  0.512972  0.487028       1  ...  NaN   NaN -0.0016  1.051884
543     0  0.524625  0.475375       0  ...  NaN   NaN -0.0016  1.051586

[5 rows x 10 columns]
2023-01-11 00:00:18,887:INFO:logic:main.py:471:getModel:726423: df_panel.iloc[-5:,:] :
    pred    prob_0    prob_1  actual  ...  nav  sign   cost_        bm
45     0  0.501713  0.498287       1  ...  NaN   NaN -0.0016  1.041576
46     0  0.502139  0.497861       1  ...  NaN   NaN -0.0016  1.043880
47     0  0.510520  0.489480       1  ...  NaN   NaN -0.0016  1.044950
48     0  0.513164  0.486836       1  ...  NaN   NaN -0.0016  1.052517
49     0  0.524625  0.475375       0  ...  NaN   NaN -0.0016  1.051586

[5 rows x 10 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '42.528', 'enterprice': '16701.5', 'countrevence': '0', 'unrealprofit': '26294.67623470272', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '17319.79091974', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}


## /root/FIL/strategy/modifiedmom/log.txt ----- -----

2023-01-11 00:00:01,142:INFO:modifiedmom:main.py:145:handleKline:185213: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
571  20230110   231000    231959  1673363999  17293.9  17335.7  0.002423
572  20230110   232000    232959  1673364599  17335.6  17321.9 -0.000796
573  20230110   233000    233959  1673365199  17321.9  17296.8 -0.001449
574  20230110   234000    234959  1673365799  17296.8  17282.5 -0.000827
575  20230110   235000    235959  1673366399  17282.6  17317.5  0.002025
2023-01-11 00:00:01,143:INFO:modifiedmom:main.py:146:handleKline:185213: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': True, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True}
closeSell: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '53.805', 'enterprice': '17189', 'countrevence': '0', 'unrealprofit': '-6926.6329892679', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '17317.73586078', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
2023-01-11 00:00:01,795:INFO:modifiedmom:main.py:287:closeSell:185213: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False}
2023-01-11 00:00:01,795:INFO:modifiedmom:main.py:288:closeSell:185213: ret = self.client.insertMarketUOrder("simulator",  BTCUSDT, 53.805, buy ), ret=InsertOrderReturn{'result': 'success', 'clientorderid': '41504F1673366401792I0L59'}
2023-01-11 00:00:01,848:INFO:modifiedmom:main.py:206:insertFactor:185213: curDateTime:1110000, name:modifiedmom, symbol:BTCUSDT, tradeDate:20230110, closeTime:235959, close:17317.5, total:923929.290855, mom:-0.0011368724584078782, thd:0.0, side:buy 
2023-01-11 00:00:01,959:INFO:modifiedmom:main.py:316:handleOrderNew:185213: handleOrderNew: data=OrderType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'clientorderid': '41504F1673366401792I0L59', 'symbol': 'BTCUSDT', 'gatewayorderid': 1673366401906657, 'quantity': '53.805', 'price': '17317.6', 'stopprice': '0', 'ordertype': '', 'side': 'BUY', 'status': 'FILLED', 'positionside': 'LONG', 'createtime': 1673366401339, 'updatetime': 1673366401906, 'tradetype': 'usdt', 'selfid': 41504, 'filltrades': [TradeType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'tradeid': 1673366401906, 'clientorderid': '41504F1673366401792I0L59', 'price': '17317.6', 'quantity': '53.805', 'commission': '931.773468', 'commissionasset': 'USDT', 'tradetime': 1673366401906, 'tradetype': 'usdt', 'gatetype': 'simulator', 'handletime': 1673366401906}], 'gatetype': 'simulator', 'handletime': 0}
127.0.0.1 - - [11/Jan/2023 00:00:01] "POST / HTTP/1.1" 200 -
2023-01-11 00:00:02,322:INFO:modifiedmom:main.py:319:handleOrderFilled:185213: handleOrderFilled: data=OrderType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'clientorderid': '41504F1673366401792I0L59', 'symbol': 'BTCUSDT', 'gatewayorderid': 1673366401906657, 'quantity': '53.805', 'price': '17317.6', 'stopprice': '0', 'ordertype': '', 'side': 'BUY', 'status': 'FILLED', 'positionside': 'LONG', 'createtime': 1673366401339, 'updatetime': 1673366401906, 'tradetype': 'usdt', 'selfid': 41504, 'filltrades': [TradeType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'tradeid': 1673366401906, 'clientorderid': '41504F1673366401792I0L59', 'price': '17317.6', 'quantity': '53.805', 'commission': '931.773468', 'commissionasset': 'USDT', 'tradetime': 1673366401906, 'tradetype': 'usdt', 'gatetype': 'simulator', 'handletime': 1673366401906}], 'gatetype': 'simulator', 'handletime': 0}
127.0.0.1 - - [11/Jan/2023 00:00:02] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [11/Jan/2023 00:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=6680 

self.closeSec=1673366999, self.tradeDate='20230111', self.openTime='000000', self.closeTime='000959', self.symbol='BTCUSDT', self.open='17317.6', self.close='17317.2'
2023-01-11 00:10:01,536:INFO:modifiedmom:main.py:144:handleKline:185213: self.closeSec=1673366999, self.tradeDate='20230111', self.openTime='000000', self.closeTime='000959',self.symbol='BTCUSDT',self.open='17317.6', self.close='17317.2'
2023-01-11 00:10:01,551:INFO:modifiedmom:main.py:145:handleKline:185213: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
572  20230110   232000    232959  1673364599  17335.6  17321.9 -0.000796
573  20230110   233000    233959  1673365199  17321.9  17296.8 -0.001449
574  20230110   234000    234959  1673365799  17296.8  17282.5 -0.000827
575  20230110   235000    235959  1673366399  17282.6  17317.5  0.002025
576  20230111   000000    000959  1673366999  17317.6  17317.2 -0.000017
2023-01-11 00:10:01,551:INFO:modifiedmom:main.py:146:handleKline:185213: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False}


## /root/FIL/strategy/pyemd/log.txt ----- -----

2023-01-10 23:50:00,593:INFO:pyemd2:main.py:127:handleKline:185189: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=6680 

self.closeSec=1673366399, self.tradeDate='20230110', self.openTime='235000', self.closeTime='235959', self.symbol='BTCUSDT', self.open='17282.6', self.close='17317.5'
127.0.0.1 - - [11/Jan/2023 00:00:01] "POST / HTTP/1.1" 200 -
2023-01-11 00:00:01,104:INFO:pyemd2:main.py:125:handleKline:185189: self.closeSec=1673366399, self.tradeDate='20230110', self.openTime='235000', self.closeTime='235959',self.symbol='BTCUSDT',self.open='17282.6', self.close='17317.5'
2023-01-11 00:00:01,151:INFO:pyemd2:main.py:126:handleKline:185189: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17419  20230110   231000    231959  1673363999  17293.9  17335.7
17420  20230110   232000    232959  1673364599  17335.6  17321.9
17421  20230110   233000    233959  1673365199  17321.9  17296.8
17422  20230110   234000    234959  1673365799  17296.8  17282.5
17423  20230110   235000    235959  1673366399  17282.6  17317.5
2023-01-11 00:00:01,152:INFO:pyemd2:main.py:127:handleKline:185189: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}
2023-01-11 00:00:01,312:INFO:pyemd2:main.py:190:insertFactor:185189: curDateTime:1110000, name:pyemd2, symbol:BTCUSDT, tradeDate:20230110, closeTime:235959, close:17317.5, total:942179.1300971, pct_pre:-0.002245526309697432, thd:-0.05844524173489646, side:sell 
127.0.0.1 - - [11/Jan/2023 00:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=6681 

self.closeSec=1673366999, self.tradeDate='20230111', self.openTime='000000', self.closeTime='000959', self.symbol='BTCUSDT', self.open='17317.6', self.close='17317.2'
2023-01-11 00:10:01,542:INFO:pyemd2:main.py:125:handleKline:185189: self.closeSec=1673366999, self.tradeDate='20230111', self.openTime='000000', self.closeTime='000959',self.symbol='BTCUSDT',self.open='17317.6', self.close='17317.2'
2023-01-11 00:10:01,554:INFO:pyemd2:main.py:126:handleKline:185189: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17420  20230110   232000    232959  1673364599  17335.6  17321.9
17421  20230110   233000    233959  1673365199  17321.9  17296.8
17422  20230110   234000    234959  1673365799  17296.8  17282.5
17423  20230110   235000    235959  1673366399  17282.6  17317.5
17424  20230111   000000    000959  1673366999  17317.6  17317.2
2023-01-11 00:10:01,555:INFO:pyemd2:main.py:127:handleKline:185189: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}


## /root/FIL/strategy/similarity/log.txt ----- -----

2023-01-11 00:00:01,155:INFO:testStrategy:main.py:102:handleKline:185174: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12235  20230110   231000    231959  1673363999  17293.9  17335.7
12236  20230110   232000    232959  1673364599  17335.6  17321.9
12237  20230110   233000    233959  1673365199  17321.9  17296.8
12238  20230110   234000    234959  1673365799  17296.8  17282.5
12239  20230110   235000    235959  1673366399  17282.6  17317.5
2023-01-11 00:00:01,155:INFO:testStrategy:main.py:103:handleKline:185174: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}
closeBuy: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '72.39', 'enterprice': '17198', 'countrevence': '0', 'unrealprofit': '8667.6789618642', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '17317.73586078', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
2023-01-11 00:00:02,292:INFO:testStrategy:main.py:233:closeBuy:185174: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False, 'isCorr': False}
2023-01-11 00:00:02,292:INFO:testStrategy:main.py:234:closeBuy:185174: ret = self.client.insertMarketUOrder("simulator",  BTCUSDT, 72.39, sell ), ret=InsertOrderReturn{'result': 'success', 'clientorderid': '41505F1673366402132I0L2'}
2023-01-11 00:00:02,336:INFO:testStrategy:main.py:172:insertFactor:185174: curDateTime:1110000, name:testStrategy, symbol:BTCUSDT, tradeDate:20230110, closeTime:235959, close:17317.5, total:1243718.25678, corrDate:20221103, corrVal:0.9009591051978185, side:sell 
127.0.0.1 - - [11/Jan/2023 00:00:02] "POST / HTTP/1.1" 200 -
2023-01-11 00:00:02,434:INFO:testStrategy:main.py:305:handleOrderNew:185174: handleOrderNew: data=OrderType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'clientorderid': '41505F1673366402132I0L2', 'symbol': 'BTCUSDT', 'gatewayorderid': 1673366402398162, 'quantity': '72.39', 'price': '17317.5', 'stopprice': '0', 'ordertype': '', 'side': 'SELL', 'status': 'FILLED', 'positionside': 'SHORT', 'createtime': 1673366401638, 'updatetime': 1673366402398, 'tradetype': 'usdt', 'selfid': 41505, 'filltrades': [TradeType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'tradeid': 1673366402398, 'clientorderid': '41505F1673366402132I0L2', 'price': '17317.5', 'quantity': '72.39', 'commission': '1253.613825', 'commissionasset': 'USDT', 'tradetime': 1673366402398, 'tradetype': 'usdt', 'gatetype': 'simulator', 'handletime': 1673366402398}], 'gatetype': 'simulator', 'handletime': 0}
2023-01-11 00:00:02,624:INFO:testStrategy:main.py:308:handleOrderFilled:185174: handleOrderFilled: data=OrderType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'clientorderid': '41505F1673366402132I0L2', 'symbol': 'BTCUSDT', 'gatewayorderid': 1673366402398162, 'quantity': '72.39', 'price': '17317.5', 'stopprice': '0', 'ordertype': '', 'side': 'SELL', 'status': 'FILLED', 'positionside': 'SHORT', 'createtime': 1673366401638, 'updatetime': 1673366402398, 'tradetype': 'usdt', 'selfid': 41505, 'filltrades': [TradeType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'tradeid': 1673366402398, 'clientorderid': '41505F1673366402132I0L2', 'price': '17317.5', 'quantity': '72.39', 'commission': '1253.613825', 'commissionasset': 'USDT', 'tradetime': 1673366402398, 'tradetype': 'usdt', 'gatetype': 'simulator', 'handletime': 1673366402398}], 'gatetype': 'simulator', 'handletime': 0}
127.0.0.1 - - [11/Jan/2023 00:00:02] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=6681 

self.closeSec=1673366999, self.tradeDate='20230111', self.openTime='000000', self.closeTime='000959', self.symbol='BTCUSDT', self.open='17317.6', self.close='17317.2'
2023-01-11 00:10:01,518:INFO:testStrategy:main.py:101:handleKline:185174: self.closeSec=1673366999, self.tradeDate='20230111', self.openTime='000000', self.closeTime='000959',self.symbol='BTCUSDT',self.open='17317.6', self.close='17317.2'
127.0.0.1 - - [11/Jan/2023 00:10:01] "POST / HTTP/1.1" 200 -
2023-01-11 00:10:01,524:INFO:testStrategy:main.py:102:handleKline:185174: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12236  20230110   232000    232959  1673364599  17335.6  17321.9
12237  20230110   233000    233959  1673365199  17321.9  17296.8
12238  20230110   234000    234959  1673365799  17296.8  17282.5
12239  20230110   235000    235959  1673366399  17282.6  17317.5
12240  20230111   000000    000959  1673366999  17317.6  17317.2
2023-01-11 00:10:01,525:INFO:testStrategy:main.py:103:handleKline:185174: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False, 'isCorr': False}


## /root/FIL/strategy/sr_min/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=0, self.total=1000000.0, self.flagDict['side']='', self.tradeCount=0, self.count=8792
self.closeSec=1673366999, self.tradeDate='20230111', self.openTime='000500', self.closeTime='000959', self.symbol='BTCUSDT', self.open=17324.1, self.close=17317.7, self.high=17324.3, self.low=17312.8, self.vol=801.25, self.amt=13877301.0191 
127.0.0.1 - - [11/Jan/2023 00:10:01] "POST / HTTP/1.1" 200 -
2023-01-11 00:10:01,493:INFO:sr_min:main.py:172:handleKline:449472: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5757  20230110   234500    234959  ...         0.0        0.0       0
5758  20230110   235000    235459  ...         0.0        0.0       0
5759  20230110   235500    235959  ...         0.0        0.0       0
5760  20230111   000000    000459  ...         0.0        0.0       0
5761  20230111   000500    000959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-01-11 00:10:01,493:INFO:sr_min:main.py:175:handleKline:449472: self.closeSec=1673366999, self.tradeDate='20230111', self.openTime='000500', self.closeTime='000959',self.symbol='BTCUSDT',self.open=17324.1, self.close=17317.7, self.high=17324.3, self.low=17312.8, self.vol=801.25, self.amt=13877301.0191, ukdf['pct'].iloc[-1]=-0.000369 , ukdf['amount'].iloc[-1]=13877301.0191, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5761, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': []}
type(curSign)=<class 'int'>, curSign=0, self.sign=0
127.0.0.1 - - [11/Jan/2023 00:15:00] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=0, self.total=1000000.0, self.flagDict['side']='', self.tradeCount=0, self.count=8793
self.closeSec=1673367299, self.tradeDate='20230111', self.openTime='001000', self.closeTime='001459', self.symbol='BTCUSDT', self.open=17317.2, self.close=17324.8, self.high=17324.8, self.low=17308.0, self.vol=903.347, self.amt=15642632.1947 
2023-01-11 00:15:00,620:INFO:sr_min:main.py:172:handleKline:449472: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5758  20230110   235000    235459  ...         0.0        0.0       0
5759  20230110   235500    235959  ...         0.0        0.0       0
5760  20230111   000000    000459  ...         0.0        0.0       0
5761  20230111   000500    000959  ...         0.0        0.0       0
5762  20230111   001000    001459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-01-11 00:15:00,620:INFO:sr_min:main.py:175:handleKline:449472: self.closeSec=1673367299, self.tradeDate='20230111', self.openTime='001000', self.closeTime='001459',self.symbol='BTCUSDT',self.open=17317.2, self.close=17324.8, self.high=17324.8, self.low=17308.0, self.vol=903.347, self.amt=15642632.1947, ukdf['pct'].iloc[-1]=0.00041 , ukdf['amount'].iloc[-1]=15642632.1947, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5762, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': []}
type(curSign)=<class 'int'>, curSign=0, self.sign=0


## /root/FIL/strategy/s_rsrs/log.txt ----- -----

723  20230110   120000    155959  1673337599  ...    723  0.878976  1.587603     1.0
724  20230110   160000    195959  1673351999  ...    724  0.856784  1.476983     1.0

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '51.136', 'enterprice': '17188.2', 'countrevence': '0', 'unrealprofit': '2873.8432', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '17244.4', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=1, self.sign=1
127.0.0.1 - - [11/Jan/2023 00:00:01] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='s_rsrs', self.symbol='BTCUSDT', interval='4h', intervalSec=14400, wid=25, thd=0.6, self.sign=1, self.total=878056.8594048, self.flagDict['side']='buy', self.tradeCount=12, self.count=278
self.closeSec=1673366399, self.tradeDate='20230110', self.openTime='200000', self.closeTime='235959', self.symbol='BTCUSDT', self.open=17244.3, self.close=17317.0, self.high=17368.7, self.low=17204.4, self.vol=92789.11, self.amt=1603149867.6684 
2023-01-11 00:00:01,008:INFO:s_rsrs:main.py:141:handleKline:185271: self.closeSec=1673366399, self.tradeDate='20230110', self.openTime='200000', self.closeTime='235959',self.symbol='BTCUSDT',self.open=17244.3, self.close=17317.0, self.high=17368.7, self.low=17204.4, self.vol=92789.11, self.amt=1603149867.6684 
2023-01-11 00:00:01,028:INFO:s_rsrs:main.py:142:handleKline:185271: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime  ...        vol           amt       pct
721  20230110   040000    075959  ...  70626.832  1.214984e+09 -0.006711
722  20230110   080000    115959  ...  27484.953  4.723608e+08  0.001759
723  20230110   120000    155959  ...  18254.506  3.140340e+08 -0.000302
724  20230110   160000    195959  ...  37043.962  6.388362e+08  0.002896
725  20230110   200000    235959  ...  92789.110  1.603150e+09  0.004204

[5 rows x 11 columns]
2023-01-11 00:00:02,407:INFO:s_rsrs:main.py:151:handleKline:185271: df_s.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec  ...  index      beta    zscore  signal
721  20230110   040000    075959  1673308799  ...    721  0.950988  1.925823     1.0
722  20230110   080000    115959  1673323199  ...    722  0.929235  1.799425     1.0
723  20230110   120000    155959  1673337599  ...    723  0.878976  1.587603     1.0
724  20230110   160000    195959  1673351999  ...    724  0.856784  1.476983     1.0
725  20230110   200000    235959  1673366399  ...    725  0.916099  1.636005     1.0

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '51.136', 'enterprice': '17188.2', 'countrevence': '0', 'unrealprofit': '6638.20706009088', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '17318.01475008', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=1, self.sign=1


