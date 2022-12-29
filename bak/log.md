# 20221230 00:16:01

## /root/FIL/strategy/amihud/log.txt ----- -----

127.0.0.1 - - [30/Dec/2022 00:10:01] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=993672.4896432, self.flagDict['side']='sell', self.tradeCount=2, self.count=9338
self.closeSec=1672330199, self.tradeDate='20221230', self.openTime='000500', self.closeTime='000959', self.symbol='BTCUSDT', self.open=16609.3, self.close=16608.2, self.high=16612.0, self.low=16605.2, self.vol=1134.194, self.amt=18838422.098 
2022-12-30 00:10:01,452:INFO:amihud:main.py:172:handleKline:200676: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5757  20221229   234500    234959  ...         0.0        0.0       0
5758  20221229   235000    235459  ...         0.0        0.0       0
5759  20221229   235500    235959  ...         0.0        0.0       0
5760  20221230   000000    000459  ...         0.0        0.0       0
5761  20221230   000500    000959  ...         0.0        0.0       0

[5 rows x 18 columns]
2022-12-30 00:10:01,452:INFO:amihud:main.py:175:handleKline:200676: self.closeSec=1672330199, self.tradeDate='20221230', self.openTime='000500', self.closeTime='000959',self.symbol='BTCUSDT',self.open=16609.3, self.close=16608.2, self.high=16612.0, self.low=16605.2, self.vol=1134.194, self.amt=18838422.098, ukdf['pct'].iloc[-1]=-6.6e-05 , ukdf['amount'].iloc[-1]=18838422.098, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5761, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '60.176', 'enterprice': '16529.3', 'countrevence': '0', 'unrealprofit': '-4840.14004783056', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '16609.73306381', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1
127.0.0.1 - - [30/Dec/2022 00:15:00] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=993672.4896432, self.flagDict['side']='sell', self.tradeCount=2, self.count=9339
self.closeSec=1672330499, self.tradeDate='20221230', self.openTime='001000', self.closeTime='001459', self.symbol='BTCUSDT', self.open=16608.1, self.close=16606.0, self.high=16608.2, self.low=16600.2, self.vol=667.812, self.amt=11087801.9082 
2022-12-30 00:15:00,608:INFO:amihud:main.py:172:handleKline:200676: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5758  20221229   235000    235459  ...         0.0        0.0       0
5759  20221229   235500    235959  ...         0.0        0.0       0
5760  20221230   000000    000459  ...         0.0        0.0       0
5761  20221230   000500    000959  ...         0.0        0.0       0
5762  20221230   001000    001459  ...         0.0        0.0       0

[5 rows x 18 columns]
2022-12-30 00:15:00,608:INFO:amihud:main.py:175:handleKline:200676: self.closeSec=1672330499, self.tradeDate='20221230', self.openTime='001000', self.closeTime='001459',self.symbol='BTCUSDT',self.open=16608.1, self.close=16606.0, self.high=16608.2, self.low=16600.2, self.vol=667.812, self.amt=11087801.9082, ukdf['pct'].iloc[-1]=-0.000132 , ukdf['amount'].iloc[-1]=11087801.9082, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5762, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '60.176', 'enterprice': '16529.3', 'countrevence': '0', 'unrealprofit': '-4668.60683136016', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '16606.88253841', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1


## /root/FIL/strategy/factorcheck/log.txt ----- -----

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=4, self.factor=0.5604464953335679, self.count=9904 

self.closeSec=1672330199, self.tradeDate='20221230', self.openTime='000500', self.closeTime='000959', self.symbol='BTCUSDT', self.open=16609.3, self.close=16608.2, self.high=16612.0, self.low=16605.2 
2022-12-30 00:10:01,441:INFO:factorcheck2:main.py:126:handleKline:185239: self.closeSec=1672330199, self.tradeDate='20221230', self.openTime='000500', self.closeTime='000959',self.symbol='BTCUSDT',self.open=16609.3, self.close=16608.2, self.high=16612.0, self.low=16605.2   
2022-12-30 00:10:01,491:INFO:factorcheck2:main.py:127:handleKline:185239: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1437  20221229   234500    234959  1672328999  ...  16604.6 -0.001077   1725    3
1438  20221229   235000    235459  1672329299  ...  16604.0  0.000072   1726    4
1439  20221229   235500    235959  1672329599  ...  16610.0 -0.000066   1727    5
1440  20221230   000000    000459  1672329899  ...  16609.3 -0.000048   1440    0
1441  20221230   000500    000959  1672330199  ...  16605.2 -0.000066   1441    1

[5 rows x 11 columns]
2022-12-30 00:10:01,491:INFO:factorcheck2:main.py:128:handleKline:185239: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': False, 'isOpen': True, 'isClose': False, 'isTrig': True}

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=4, self.factor=0.5604464953335679, self.count=9905 

self.closeSec=1672330499, self.tradeDate='20221230', self.openTime='001000', self.closeTime='001459', self.symbol='BTCUSDT', self.open=16608.1, self.close=16606.0, self.high=16608.2, self.low=16600.2 
2022-12-30 00:15:00,512:INFO:factorcheck2:main.py:126:handleKline:185239: self.closeSec=1672330499, self.tradeDate='20221230', self.openTime='001000', self.closeTime='001459',self.symbol='BTCUSDT',self.open=16608.1, self.close=16606.0, self.high=16608.2, self.low=16600.2   
127.0.0.1 - - [30/Dec/2022 00:15:00] "POST / HTTP/1.1" 200 -
2022-12-30 00:15:00,561:INFO:factorcheck2:main.py:127:handleKline:185239: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1438  20221229   235000    235459  1672329299  ...  16604.0  0.000072   1726    4
1439  20221229   235500    235959  1672329599  ...  16610.0 -0.000066   1727    5
1440  20221230   000000    000459  1672329899  ...  16609.3 -0.000048   1440    0
1441  20221230   000500    000959  1672330199  ...  16605.2 -0.000066   1441    1
1442  20221230   001000    001459  1672330499  ...  16600.2 -0.000132   1442    2

[5 rows x 11 columns]
2022-12-30 00:15:00,561:INFO:factorcheck2:main.py:128:handleKline:185239: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': False, 'isOpen': True, 'isClose': False, 'isTrig': True}


## /root/FIL/strategy/logic/log.txt ----- -----

2022-12-30 00:00:19,085:DEBUG:logic:main.py:454:getModel:174970: df_s.iloc[-5:,:] :
          date closeTime     open  ...    alpha58   alpha67   alpha72
5802  20221229    212959  16612.5  ...  43.333333  0.487296  0.569490
5803  20221229    215959  16613.2  ...  43.333333  0.485627  0.547767
5804  20221229    222959  16610.2  ...  43.333333  0.488891  0.523081
5805  20221229    225959  16615.5  ...  43.333333  0.495120  0.499156
5806  20221229    232959  16625.6  ...  43.333333  0.495865  0.476433

[5 rows x 33 columns]
0.5128676470588235
acc is : 0.5128676470588235
2022-12-30 00:00:19,202:INFO:logic:main.py:459:getModel:174970: df_pred.iloc[-5:,:] :
     pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
539     0  0.500202  0.499798       0  ...  0.992264   1.0    0.0  0.992252
540     1  0.499748  0.500252       1  ...  0.992580   1.0    0.0  0.992569
541     0  0.501650  0.498350       1  ...  0.993184   1.0    0.0  0.993172
542     0  0.504248  0.495752       1  ...  0.993255   1.0    0.0  0.993244
543     0  0.500094  0.499906       0  ...  0.992258   1.0    0.0  0.992246

[5 rows x 10 columns]
2022-12-30 00:00:19,224:INFO:logic:main.py:469:getModel:174970: df_panel.iloc[-5:,:] :
    pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
45     0  0.500483  0.499517       0  ...  0.992264   1.0    0.0  0.993189
46     1  0.499603  0.500397       1  ...  0.992580   1.0    0.0  0.993275
47     0  0.501650  0.498350       1  ...  0.993184   1.0    0.0  0.993879
48     0  0.503987  0.496013       1  ...  0.993255   1.0    0.0  0.993060
49     0  0.500094  0.499906       0  ...  0.992258   1.0    0.0  0.992246

[5 rows x 10 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '42.528', 'enterprice': '16701.5', 'countrevence': '0', 'unrealprofit': '-3806.68476389376', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '16611.98991808', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}


## /root/FIL/strategy/modifiedmom/log.txt ----- -----

2022-12-30 00:00:01,377:INFO:modifiedmom:main.py:145:handleKline:185213: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
571  20221229   231000    231959  1672327199  16653.8  16639.7 -0.000847
572  20221229   232000    232959  1672327799  16639.8  16626.8 -0.000775
573  20221229   233000    233959  1672328399  16626.7  16629.9  0.000186
574  20221229   234000    234959  1672328999  16629.8  16610.1 -0.001191
575  20221229   235000    235959  1672329599  16610.1  16610.1  0.000000
2022-12-30 00:00:01,377:INFO:modifiedmom:main.py:146:handleKline:185213: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': True, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True}
closeSell: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '55.735', 'enterprice': '16540', 'countrevence': '0', 'unrealprofit': '-4048.1596498231', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '16612.63227146', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
2022-12-30 00:00:02,494:INFO:modifiedmom:main.py:287:closeSell:185213: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False}
2022-12-30 00:00:02,494:INFO:modifiedmom:main.py:288:closeSell:185213: ret = self.client.insertMarketUOrder("simulator",  BTCUSDT, 55.735, buy ), ret=InsertOrderReturn{'result': 'success', 'clientorderid': '41437F1672329602181I0L59'}
2022-12-30 00:00:02,532:INFO:modifiedmom:main.py:206:insertFactor:185213: curDateTime:12300000, name:modifiedmom, symbol:BTCUSDT, tradeDate:20221229, closeTime:235959, close:16610.1, total:920935.0431, mom:-0.000539831148800074, thd:0.0, side:buy 
127.0.0.1 - - [30/Dec/2022 00:00:02] "POST / HTTP/1.1" 200 -
2022-12-30 00:00:02,645:INFO:modifiedmom:main.py:316:handleOrderNew:185213: handleOrderNew: data=OrderType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'clientorderid': '41437F1672329602181I0L59', 'symbol': 'BTCUSDT', 'gatewayorderid': 1672329602600523, 'quantity': '55.735', 'price': '16610.1', 'stopprice': '0', 'ordertype': '', 'side': 'BUY', 'status': 'FILLED', 'positionside': 'LONG', 'createtime': 1672329601780, 'updatetime': 1672329602600, 'tradetype': 'usdt', 'selfid': 41437, 'filltrades': [TradeType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'tradeid': 1672329602600, 'clientorderid': '41437F1672329602181I0L59', 'price': '16610.1', 'quantity': '55.735', 'commission': '925.7639235', 'commissionasset': 'USDT', 'tradetime': 1672329602600, 'tradetype': 'usdt', 'gatetype': 'simulator', 'handletime': 1672329602600}], 'gatetype': 'simulator', 'handletime': 0}
2022-12-30 00:00:02,865:INFO:modifiedmom:main.py:319:handleOrderFilled:185213: handleOrderFilled: data=OrderType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'clientorderid': '41437F1672329602181I0L59', 'symbol': 'BTCUSDT', 'gatewayorderid': 1672329602600523, 'quantity': '55.735', 'price': '16610.1', 'stopprice': '0', 'ordertype': '', 'side': 'BUY', 'status': 'FILLED', 'positionside': 'LONG', 'createtime': 1672329601780, 'updatetime': 1672329602600, 'tradetype': 'usdt', 'selfid': 41437, 'filltrades': [TradeType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'tradeid': 1672329602600, 'clientorderid': '41437F1672329602181I0L59', 'price': '16610.1', 'quantity': '55.735', 'commission': '925.7639235', 'commissionasset': 'USDT', 'tradetime': 1672329602600, 'tradetype': 'usdt', 'gatetype': 'simulator', 'handletime': 1672329602600}], 'gatetype': 'simulator', 'handletime': 0}
127.0.0.1 - - [30/Dec/2022 00:00:02] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [30/Dec/2022 00:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=4952 

self.closeSec=1672330199, self.tradeDate='20221230', self.openTime='000000', self.closeTime='000959', self.symbol='BTCUSDT', self.open='16610.1', self.close='16608.2'
2022-12-30 00:10:01,755:INFO:modifiedmom:main.py:144:handleKline:185213: self.closeSec=1672330199, self.tradeDate='20221230', self.openTime='000000', self.closeTime='000959',self.symbol='BTCUSDT',self.open='16610.1', self.close='16608.2'
2022-12-30 00:10:01,773:INFO:modifiedmom:main.py:145:handleKline:185213: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
572  20221229   232000    232959  1672327799  16639.8  16626.8 -0.000775
573  20221229   233000    233959  1672328399  16626.7  16629.9  0.000186
574  20221229   234000    234959  1672328999  16629.8  16610.1 -0.001191
575  20221229   235000    235959  1672329599  16610.1  16610.1  0.000000
576  20221230   000000    000959  1672330199  16610.1  16608.2 -0.000114
2022-12-30 00:10:01,773:INFO:modifiedmom:main.py:146:handleKline:185213: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False}


## /root/FIL/strategy/pyemd/log.txt ----- -----

2022-12-30 00:00:01,373:INFO:pyemd2:main.py:126:handleKline:185189: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17419  20221229   231000    231959  1672327199  16653.8  16639.7
17420  20221229   232000    232959  1672327799  16639.8  16626.8
17421  20221229   233000    233959  1672328399  16626.7  16629.9
17422  20221229   234000    234959  1672328999  16629.8  16610.1
17423  20221229   235000    235959  1672329599  16610.1  16610.1
2022-12-30 00:00:01,373:INFO:pyemd2:main.py:127:handleKline:185189: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': False, 'isOpen': True, 'isClose': False, 'isTrig': True}
closeBuy: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '56.821', 'enterprice': '16587.1', 'countrevence': '0', 'unrealprofit': '1450.76919662866', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '16612.63227146', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
2022-12-30 00:00:02,489:INFO:pyemd2:main.py:251:closeBuy:185189: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}
2022-12-30 00:00:02,489:INFO:pyemd2:main.py:252:closeBuy:185189: ret = self.client.insertMarketUOrder("simulator",  BTCUSDT, 56.821, sell ), ret=InsertOrderReturn{'result': 'success', 'clientorderid': '41438F1672329602261I0L57'}
2022-12-30 00:00:02,522:INFO:pyemd2:main.py:190:insertFactor:185189: curDateTime:12300000, name:pyemd2, symbol:BTCUSDT, tradeDate:20221229, closeTime:235959, close:16610.1, total:941553.1134908999, pct_pre:0.0006394633334136923, thd:0.21759911673347693, side:sell 
127.0.0.1 - - [30/Dec/2022 00:00:02] "POST / HTTP/1.1" 200 -
2022-12-30 00:00:02,887:INFO:pyemd2:main.py:300:handleOrderNew:185189: handleOrderNew: data=OrderType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'clientorderid': '41438F1672329602261I0L57', 'symbol': 'BTCUSDT', 'gatewayorderid': 1672329602606605, 'quantity': '56.821', 'price': '16610', 'stopprice': '0', 'ordertype': '', 'side': 'SELL', 'status': 'FILLED', 'positionside': 'SHORT', 'createtime': 1672329601651, 'updatetime': 1672329602606, 'tradetype': 'usdt', 'selfid': 41438, 'filltrades': [TradeType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'tradeid': 1672329602606, 'clientorderid': '41438F1672329602261I0L57', 'price': '16610', 'quantity': '56.821', 'commission': '943.79681', 'commissionasset': 'USDT', 'tradetime': 1672329602606, 'tradetype': 'usdt', 'gatetype': 'simulator', 'handletime': 1672329602606}], 'gatetype': 'simulator', 'handletime': 0}
127.0.0.1 - - [30/Dec/2022 00:00:03] "POST / HTTP/1.1" 200 -
2022-12-30 00:00:03,078:INFO:pyemd2:main.py:303:handleOrderFilled:185189: handleOrderFilled: data=OrderType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'clientorderid': '41438F1672329602261I0L57', 'symbol': 'BTCUSDT', 'gatewayorderid': 1672329602606605, 'quantity': '56.821', 'price': '16610', 'stopprice': '0', 'ordertype': '', 'side': 'SELL', 'status': 'FILLED', 'positionside': 'SHORT', 'createtime': 1672329601651, 'updatetime': 1672329602606, 'tradetype': 'usdt', 'selfid': 41438, 'filltrades': [TradeType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'tradeid': 1672329602606, 'clientorderid': '41438F1672329602261I0L57', 'price': '16610', 'quantity': '56.821', 'commission': '943.79681', 'commissionasset': 'USDT', 'tradetime': 1672329602606, 'tradetype': 'usdt', 'gatetype': 'simulator', 'handletime': 1672329602606}], 'gatetype': 'simulator', 'handletime': 0}
127.0.0.1 - - [30/Dec/2022 00:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=4953 

self.closeSec=1672330199, self.tradeDate='20221230', self.openTime='000000', self.closeTime='000959', self.symbol='BTCUSDT', self.open='16610.1', self.close='16608.2'
2022-12-30 00:10:01,772:INFO:pyemd2:main.py:125:handleKline:185189: self.closeSec=1672330199, self.tradeDate='20221230', self.openTime='000000', self.closeTime='000959',self.symbol='BTCUSDT',self.open='16610.1', self.close='16608.2'
2022-12-30 00:10:01,791:INFO:pyemd2:main.py:126:handleKline:185189: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17420  20221229   232000    232959  1672327799  16639.8  16626.8
17421  20221229   233000    233959  1672328399  16626.7  16629.9
17422  20221229   234000    234959  1672328999  16629.8  16610.1
17423  20221229   235000    235959  1672329599  16610.1  16610.1
17424  20221230   000000    000959  1672330199  16610.1  16608.2
2022-12-30 00:10:01,791:INFO:pyemd2:main.py:127:handleKline:185189: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}


## /root/FIL/strategy/similarity/log.txt ----- -----

2022-12-30 00:00:01,369:INFO:testStrategy:main.py:102:handleKline:185174: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12235  20221229   231000    231959  1672327199  16653.8  16639.7
12236  20221229   232000    232959  1672327799  16639.8  16626.8
12237  20221229   233000    233959  1672328399  16626.7  16629.9
12238  20221229   234000    234959  1672328999  16629.8  16610.1
12239  20221229   235000    235959  1672329599  16610.1  16610.1
2022-12-30 00:00:01,369:INFO:testStrategy:main.py:103:handleKline:185174: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': True, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}
closeSell: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '76.697', 'enterprice': '16511.3', 'countrevence': '0', 'unrealprofit': '-7771.88122416762', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '16612.63227146', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
2022-12-30 00:00:02,016:INFO:testStrategy:main.py:253:closeSell:185174: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False, 'isCorr': False}
2022-12-30 00:00:02,016:INFO:testStrategy:main.py:254:closeSell:185174: ret = self.client.insertMarketUOrder("simulator",  BTCUSDT, 76.697, buy ), ret=InsertOrderReturn{'result': 'success', 'clientorderid': '41436F1672329602014I0L2'}
2022-12-30 00:00:02,051:INFO:testStrategy:main.py:172:insertFactor:185174: curDateTime:12300000, name:testStrategy, symbol:BTCUSDT, tradeDate:20221229, closeTime:235959, close:16610.1, total:1265100.8089239001, corrDate:20221121, corrVal:0.901405793998418, side:buy 
2022-12-30 00:00:02,181:INFO:testStrategy:main.py:305:handleOrderNew:185174: handleOrderNew: data=OrderType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'clientorderid': '41436F1672329602014I0L2', 'symbol': 'BTCUSDT', 'gatewayorderid': 1672329602126743, 'quantity': '76.697', 'price': '16610.1', 'stopprice': '0', 'ordertype': '', 'side': 'BUY', 'status': 'FILLED', 'positionside': 'LONG', 'createtime': 1672329601603, 'updatetime': 1672329602126, 'tradetype': 'usdt', 'selfid': 41436, 'filltrades': [TradeType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'tradeid': 1672329602126, 'clientorderid': '41436F1672329602014I0L2', 'price': '16610.1', 'quantity': '76.697', 'commission': '1273.9448397', 'commissionasset': 'USDT', 'tradetime': 1672329602126, 'tradetype': 'usdt', 'gatetype': 'simulator', 'handletime': 1672329602126}], 'gatetype': 'simulator', 'handletime': 0}
127.0.0.1 - - [30/Dec/2022 00:00:02] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [30/Dec/2022 00:00:02] "POST / HTTP/1.1" 200 -
2022-12-30 00:00:02,533:INFO:testStrategy:main.py:308:handleOrderFilled:185174: handleOrderFilled: data=OrderType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'clientorderid': '41436F1672329602014I0L2', 'symbol': 'BTCUSDT', 'gatewayorderid': 1672329602126743, 'quantity': '76.697', 'price': '16610.1', 'stopprice': '0', 'ordertype': '', 'side': 'BUY', 'status': 'FILLED', 'positionside': 'LONG', 'createtime': 1672329601603, 'updatetime': 1672329602126, 'tradetype': 'usdt', 'selfid': 41436, 'filltrades': [TradeType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'tradeid': 1672329602126, 'clientorderid': '41436F1672329602014I0L2', 'price': '16610.1', 'quantity': '76.697', 'commission': '1273.9448397', 'commissionasset': 'USDT', 'tradetime': 1672329602126, 'tradetype': 'usdt', 'gatetype': 'simulator', 'handletime': 1672329602126}], 'gatetype': 'simulator', 'handletime': 0}

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=4953 

self.closeSec=1672330199, self.tradeDate='20221230', self.openTime='000000', self.closeTime='000959', self.symbol='BTCUSDT', self.open='16610.1', self.close='16608.2'
2022-12-30 00:10:01,767:INFO:testStrategy:main.py:101:handleKline:185174: self.closeSec=1672330199, self.tradeDate='20221230', self.openTime='000000', self.closeTime='000959',self.symbol='BTCUSDT',self.open='16610.1', self.close='16608.2'
127.0.0.1 - - [30/Dec/2022 00:10:01] "POST / HTTP/1.1" 200 -
2022-12-30 00:10:01,778:INFO:testStrategy:main.py:102:handleKline:185174: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12236  20221229   232000    232959  1672327799  16639.8  16626.8
12237  20221229   233000    233959  1672328399  16626.7  16629.9
12238  20221229   234000    234959  1672328999  16629.8  16610.1
12239  20221229   235000    235959  1672329599  16610.1  16610.1
12240  20221230   000000    000959  1672330199  16610.1  16608.2
2022-12-30 00:10:01,778:INFO:testStrategy:main.py:103:handleKline:185174: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False, 'isCorr': False}


## /root/FIL/strategy/sr_min/log.txt ----- -----

127.0.0.1 - - [30/Dec/2022 00:10:01] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=0, self.total=1000000.0, self.flagDict['side']='', self.tradeCount=0, self.count=5336
self.closeSec=1672330199, self.tradeDate='20221230', self.openTime='000500', self.closeTime='000959', self.symbol='BTCUSDT', self.open=16609.3, self.close=16608.2, self.high=16612.0, self.low=16605.2, self.vol=1134.194, self.amt=18838422.098 
2022-12-30 00:10:01,473:INFO:sr_min:main.py:172:handleKline:449472: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5757  20221229   234500    234959  ...         0.0        0.0       0
5758  20221229   235000    235459  ...         0.0        0.0       0
5759  20221229   235500    235959  ...         0.0        0.0       0
5760  20221230   000000    000459  ...         0.0        0.0       0
5761  20221230   000500    000959  ...         0.0        0.0       0

[5 rows x 18 columns]
2022-12-30 00:10:01,473:INFO:sr_min:main.py:175:handleKline:449472: self.closeSec=1672330199, self.tradeDate='20221230', self.openTime='000500', self.closeTime='000959',self.symbol='BTCUSDT',self.open=16609.3, self.close=16608.2, self.high=16612.0, self.low=16605.2, self.vol=1134.194, self.amt=18838422.098, ukdf['pct'].iloc[-1]=-6.6e-05 , ukdf['amount'].iloc[-1]=18838422.098, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5761, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': []}
type(curSign)=<class 'int'>, curSign=0, self.sign=0
127.0.0.1 - - [30/Dec/2022 00:15:00] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=0, self.total=1000000.0, self.flagDict['side']='', self.tradeCount=0, self.count=5337
self.closeSec=1672330499, self.tradeDate='20221230', self.openTime='001000', self.closeTime='001459', self.symbol='BTCUSDT', self.open=16608.1, self.close=16606.0, self.high=16608.2, self.low=16600.2, self.vol=667.812, self.amt=11087801.9082 
2022-12-30 00:15:00,558:INFO:sr_min:main.py:172:handleKline:449472: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5758  20221229   235000    235459  ...         0.0        0.0       0
5759  20221229   235500    235959  ...         0.0        0.0       0
5760  20221230   000000    000459  ...         0.0        0.0       0
5761  20221230   000500    000959  ...         0.0        0.0       0
5762  20221230   001000    001459  ...         0.0        0.0       0

[5 rows x 18 columns]
2022-12-30 00:15:00,558:INFO:sr_min:main.py:175:handleKline:449472: self.closeSec=1672330499, self.tradeDate='20221230', self.openTime='001000', self.closeTime='001459',self.symbol='BTCUSDT',self.open=16608.1, self.close=16606.0, self.high=16608.2, self.low=16600.2, self.vol=667.812, self.amt=11087801.9082, ukdf['pct'].iloc[-1]=-0.000132 , ukdf['amount'].iloc[-1]=11087801.9082, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5762, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': []}
type(curSign)=<class 'int'>, curSign=0, self.sign=0


## /root/FIL/strategy/s_rsrs/log.txt ----- -----

723  20221229   120000    155959  1672300799  ...    723  0.516441  0.253051     NaN
724  20221229   160000    195959  1672315199  ...    724  0.557166  0.357870     NaN

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '53.372', 'enterprice': '16723.1', 'countrevence': '0', 'unrealprofit': '6885.13214603016', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '16594.09729922', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-9223372036854775808, self.sign=-1
--handleKline--:  version='2.0.0', self.name='s_rsrs', self.symbol='BTCUSDT', interval='4h', intervalSec=14400, wid=25, thd=0.6, self.sign=-1, self.total=891652.7479068, self.flagDict['side']='sell', self.tradeCount=7, self.count=206
self.closeSec=1672329599, self.tradeDate='20221229', self.openTime='200000', self.closeTime='235959', self.symbol='BTCUSDT', self.open=16593.8, self.close=16610.1, self.high=16659.0, self.low=16584.0, self.vol=52351.625, self.amt=870226747.7465 
127.0.0.1 - - [30/Dec/2022 00:00:01] "POST / HTTP/1.1" 200 -
2022-12-30 00:00:01,231:INFO:s_rsrs:main.py:141:handleKline:185271: self.closeSec=1672329599, self.tradeDate='20221229', self.openTime='200000', self.closeTime='235959',self.symbol='BTCUSDT',self.open=16593.8, self.close=16610.1, self.high=16659.0, self.low=16584.0, self.vol=52351.625, self.amt=870226747.7465 
2022-12-30 00:00:01,291:INFO:s_rsrs:main.py:142:handleKline:185271: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime  ...        vol           amt       pct
721  20221229   040000    075959  ...  73829.964  1.219722e+09 -0.003056
722  20221229   080000    115959  ...  34024.879  5.627557e+08  0.000859
723  20221229   120000    155959  ...  22366.398  3.702529e+08 -0.000012
724  20221229   160000    195959  ...  40553.131  6.720861e+08  0.002465
725  20221229   200000    235959  ...  52351.625  8.702267e+08  0.000982

[5 rows x 11 columns]
2022-12-30 00:00:03,026:INFO:s_rsrs:main.py:151:handleKline:185271: df_s.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec  ...  index      beta    zscore  signal
721  20221229   040000    075959  1672271999  ...    721  0.368737 -0.107683     NaN
722  20221229   080000    115959  1672286399  ...    722  0.439850  0.066642     NaN
723  20221229   120000    155959  1672300799  ...    723  0.516441  0.253051     NaN
724  20221229   160000    195959  1672315199  ...    724  0.557166  0.357870     NaN
725  20221229   200000    235959  1672329599  ...    725  0.610035  0.494206     NaN

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '53.372', 'enterprice': '16723.1', 'countrevence': '0', 'unrealprofit': '5925.37035083796', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '16612.07979557', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-9223372036854775808, self.sign=-1


