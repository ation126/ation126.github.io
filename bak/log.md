# 20230124 00:16:01

## /root/FIL/strategy/amihud/log.txt ----- -----

127.0.0.1 - - [24/Jan/2023 00:10:01] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=993672.4896432, self.flagDict['side']='sell', self.tradeCount=2, self.count=16538
self.closeSec=1674490199, self.tradeDate='20230124', self.openTime='000500', self.closeTime='000959', self.symbol='BTCUSDT', self.open=22909.0, self.close=22897.7, self.high=22929.3, self.low=22876.0, self.vol=2078.298, self.amt=47600281.7784 
2023-01-24 00:10:01,492:INFO:amihud:main.py:172:handleKline:200676: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5757  20230123   234500    234959  ...         0.0        0.0       0
5758  20230123   235000    235459  ...         0.0        0.0       0
5759  20230123   235500    235959  ...         0.0        0.0       0
5760  20230124   000000    000459  ...         0.0        0.0       0
5761  20230124   000500    000959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-01-24 00:10:01,493:INFO:amihud:main.py:175:handleKline:200676: self.closeSec=1674490199, self.tradeDate='20230124', self.openTime='000500', self.closeTime='000959',self.symbol='BTCUSDT',self.open=22909.0, self.close=22897.7, self.high=22929.3, self.low=22876.0, self.vol=2078.298, self.amt=47600281.7784, ukdf['pct'].iloc[-1]=-0.000672 , ukdf['amount'].iloc[-1]=47600281.7784, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5761, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '60.176', 'enterprice': '16529.3', 'countrevence': '0', 'unrealprofit': '-383378.75986563072', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '22900.25785472', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1
127.0.0.1 - - [24/Jan/2023 00:15:00] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=993672.4896432, self.flagDict['side']='sell', self.tradeCount=2, self.count=16539
self.closeSec=1674490499, self.tradeDate='20230124', self.openTime='001000', self.closeTime='001459', self.symbol='BTCUSDT', self.open=22897.7, self.close=22870.9, self.high=22908.7, self.low=22870.9, self.vol=998.273, self.amt=22851170.4645 
2023-01-24 00:15:00,901:INFO:amihud:main.py:172:handleKline:200676: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5758  20230123   235000    235459  ...         0.0        0.0       0
5759  20230123   235500    235959  ...         0.0        0.0       0
5760  20230124   000000    000459  ...         0.0        0.0       0
5761  20230124   000500    000959  ...         0.0        0.0       0
5762  20230124   001000    001459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-01-24 00:15:00,901:INFO:amihud:main.py:175:handleKline:200676: self.closeSec=1674490499, self.tradeDate='20230124', self.openTime='001000', self.closeTime='001459',self.symbol='BTCUSDT',self.open=22897.7, self.close=22870.9, self.high=22908.7, self.low=22870.9, self.vol=998.273, self.amt=22851170.4645, ukdf['pct'].iloc[-1]=-0.00117 , ukdf['amount'].iloc[-1]=22851170.4645, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5762, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '60.176', 'enterprice': '16529.3', 'countrevence': '0', 'unrealprofit': '-381863.70873409056', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '22875.08085506', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1


## /root/FIL/strategy/factorcheck/log.txt ----- -----


self.closeSec=1674490199, self.tradeDate='20230124', self.openTime='000500', self.closeTime='000959', self.symbol='BTCUSDT', self.open=22909.0, self.close=22897.7, self.high=22929.3, self.low=22876.0 
2023-01-24 00:10:01,401:INFO:factorcheck2:main.py:126:handleKline:185239: self.closeSec=1674490199, self.tradeDate='20230124', self.openTime='000500', self.closeTime='000959',self.symbol='BTCUSDT',self.open=22909.0, self.close=22897.7, self.high=22929.3, self.low=22876.0   
127.0.0.1 - - [24/Jan/2023 00:10:01] "POST / HTTP/1.1" 200 -
2023-01-24 00:10:01,463:INFO:factorcheck2:main.py:127:handleKline:185239: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1437  20230123   234500    234959  1674488999  ...  22833.6  0.001719   1725    3
1438  20230123   235000    235459  1674489299  ...  22853.7 -0.001345   1726    4
1439  20230123   235500    235959  1674489599  ...  22848.1 -0.001141   1727    5
1440  20230124   000000    000459  1674489899  ...  22851.8  0.002814   1440    0
1441  20230124   000500    000959  1674490199  ...  22876.0 -0.000672   1441    1

[5 rows x 11 columns]
2023-01-24 00:10:01,464:INFO:factorcheck2:main.py:128:handleKline:185239: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}
127.0.0.1 - - [24/Jan/2023 00:15:00] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=141, self.factor=0.45139076830518254, self.count=17105 

self.closeSec=1674490499, self.tradeDate='20230124', self.openTime='001000', self.closeTime='001459', self.symbol='BTCUSDT', self.open=22897.7, self.close=22870.9, self.high=22908.7, self.low=22870.9 
2023-01-24 00:15:00,862:INFO:factorcheck2:main.py:126:handleKline:185239: self.closeSec=1674490499, self.tradeDate='20230124', self.openTime='001000', self.closeTime='001459',self.symbol='BTCUSDT',self.open=22897.7, self.close=22870.9, self.high=22908.7, self.low=22870.9   
2023-01-24 00:15:00,893:INFO:factorcheck2:main.py:127:handleKline:185239: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1438  20230123   235000    235459  1674489299  ...  22853.7 -0.001345   1726    4
1439  20230123   235500    235959  1674489599  ...  22848.1 -0.001141   1727    5
1440  20230124   000000    000459  1674489899  ...  22851.8  0.002814   1440    0
1441  20230124   000500    000959  1674490199  ...  22876.0 -0.000672   1441    1
1442  20230124   001000    001459  1674490499  ...  22870.9 -0.001170   1442    2

[5 rows x 11 columns]
2023-01-24 00:15:00,893:INFO:factorcheck2:main.py:128:handleKline:185239: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}


## /root/FIL/strategy/logic/log.txt ----- -----

2023-01-24 00:00:22,142:DEBUG:logic:main.py:463:getModel:885513: df_s.iloc[-5:,:] :
          date closeTime     open  ...    alpha58   alpha67   alpha72
5802  20230123    212959  22909.9  ...  55.416667  0.538650  0.358185
5803  20230123    215959  22871.9  ...  55.000000  0.523534  0.352401
5804  20230123    222959  22797.1  ...  55.000000  0.522847  0.347327
5805  20230123    225959  22793.6  ...  54.583333  0.491092  0.364691
5806  20230123    232959  22635.8  ...  54.583333  0.532018  0.363204

[5 rows x 33 columns]
0.5238970588235294
acc is : 0.5238970588235294
2023-01-24 00:00:22,231:INFO:logic:main.py:468:getModel:885513: df_pred.iloc[-5:,:] :
     pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
539     0  0.510957  0.489043       0  ...  0.999952   1.0    0.0  1.257467
540     0  0.501085  0.498915       0  ...  0.999803   1.0    0.0  1.257280
541     0  0.506366  0.493634       0  ...  0.992600   1.0    0.0  1.248222
542     1  0.462327  0.537673       1  ...  1.002763   1.0    0.0  1.261003
543     0  0.555573  0.444427       0  ...  1.002224   1.0    0.0  1.260324

[5 rows x 10 columns]
2023-01-24 00:00:22,246:INFO:logic:main.py:478:getModel:885513: df_panel.iloc[-5:,:] :
    pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
45     0  0.509937  0.490063       0  ...  1.009671   1.0    0.0  1.258002
46     1  0.499979  0.500021       0  ...  0.999803   1.0    0.0  1.256400
47     0  0.506386  0.493614       0  ...  0.992600   1.0    0.0  1.247349
48     1  0.462197  0.537803       1  ...  1.002763   1.0    0.0  1.259454
49     0  0.555573  0.444427       0  ...  1.002224   1.0    0.0  1.260324

[5 rows x 10 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '32.288', 'enterprice': '22918.2', 'countrevence': '0', 'unrealprofit': '-1562.7392', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '22869.8', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}


## /root/FIL/strategy/modifiedmom/log.txt ----- -----

2023-01-24 00:00:01,883:INFO:modifiedmom:main.py:145:handleKline:185213: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
571  20230123   231000    231959  1674487199  22691.5  22795.6  0.004583
572  20230123   232000    232959  1674487799  22793.6  22861.1  0.002873
573  20230123   233000    233959  1674488399  22862.1    22830 -0.001360
574  20230123   234000    234959  1674488999  22834.2  22905.7  0.003316
575  20230123   235000    235959  1674489599  22906.3    22852 -0.002344
2023-01-24 00:00:01,884:INFO:modifiedmom:main.py:146:handleKline:185213: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True}
closeBuy: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '42.014', 'enterprice': '22689.5', 'countrevence': '0', 'unrealprofit': '7009.24855511916', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '22856.33125994', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
2023-01-24 00:00:02,483:INFO:modifiedmom:main.py:267:closeBuy:185213: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False}
2023-01-24 00:00:02,483:INFO:modifiedmom:main.py:268:closeBuy:185213: ret = self.client.insertMarketUOrder("simulator",  BTCUSDT, 42.014, sell ), ret=InsertOrderReturn{'result': 'success', 'clientorderid': '41589F1674489602481I0L59'}
2023-01-24 00:00:02,552:INFO:modifiedmom:main.py:206:insertFactor:185213: curDateTime:1240000, name:modifiedmom, symbol:BTCUSDT, tradeDate:20230123, closeTime:235959, close:22852, total:952323.376347, mom:0.0014284813768841165, thd:0.0, side:sell 
127.0.0.1 - - [24/Jan/2023 00:00:02] "POST / HTTP/1.1" 200 -
2023-01-24 00:00:02,666:INFO:modifiedmom:main.py:316:handleOrderNew:185213: handleOrderNew: data=OrderType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'clientorderid': '41589F1674489602481I0L59', 'symbol': 'BTCUSDT', 'gatewayorderid': 1674489602614159, 'quantity': '42.014', 'price': '22855.7', 'stopprice': '0', 'ordertype': '', 'side': 'SELL', 'status': 'FILLED', 'positionside': 'SHORT', 'createtime': 1674489602067, 'updatetime': 1674489602614, 'tradetype': 'usdt', 'selfid': 41589, 'filltrades': [TradeType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'tradeid': 1674489602614, 'clientorderid': '41589F1674489602481I0L59', 'price': '22855.7', 'quantity': '42.014', 'commission': '960.2593798', 'commissionasset': 'USDT', 'tradetime': 1674489602614, 'tradetype': 'usdt', 'gatetype': 'simulator', 'handletime': 1674489602614}], 'gatetype': 'simulator', 'handletime': 0}
2023-01-24 00:00:02,858:INFO:modifiedmom:main.py:319:handleOrderFilled:185213: handleOrderFilled: data=OrderType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'clientorderid': '41589F1674489602481I0L59', 'symbol': 'BTCUSDT', 'gatewayorderid': 1674489602614159, 'quantity': '42.014', 'price': '22855.7', 'stopprice': '0', 'ordertype': '', 'side': 'SELL', 'status': 'FILLED', 'positionside': 'SHORT', 'createtime': 1674489602067, 'updatetime': 1674489602614, 'tradetype': 'usdt', 'selfid': 41589, 'filltrades': [TradeType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'tradeid': 1674489602614, 'clientorderid': '41589F1674489602481I0L59', 'price': '22855.7', 'quantity': '42.014', 'commission': '960.2593798', 'commissionasset': 'USDT', 'tradetime': 1674489602614, 'tradetype': 'usdt', 'gatetype': 'simulator', 'handletime': 1674489602614}], 'gatetype': 'simulator', 'handletime': 0}
127.0.0.1 - - [24/Jan/2023 00:00:02] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=8552 

self.closeSec=1674490199, self.tradeDate='20230124', self.openTime='000000', self.closeTime='000959', self.symbol='BTCUSDT', self.open='22852.1', self.close='22897.7'
2023-01-24 00:10:01,520:INFO:modifiedmom:main.py:144:handleKline:185213: self.closeSec=1674490199, self.tradeDate='20230124', self.openTime='000000', self.closeTime='000959',self.symbol='BTCUSDT',self.open='22852.1', self.close='22897.7'
127.0.0.1 - - [24/Jan/2023 00:10:01] "POST / HTTP/1.1" 200 -
2023-01-24 00:10:01,548:INFO:modifiedmom:main.py:145:handleKline:185213: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
572  20230123   232000    232959  1674487799  22793.6  22861.1  0.002873
573  20230123   233000    233959  1674488399  22862.1    22830 -0.001360
574  20230123   234000    234959  1674488999  22834.2  22905.7  0.003316
575  20230123   235000    235959  1674489599  22906.3    22852 -0.002344
576  20230124   000000    000959  1674490199  22852.1  22897.7  0.002000
2023-01-24 00:10:01,549:INFO:modifiedmom:main.py:146:handleKline:185213: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False}


## /root/FIL/strategy/pyemd/log.txt ----- -----

2023-01-24 00:00:01,869:INFO:pyemd2:main.py:126:handleKline:185189: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17419  20230123   231000    231959  1674487199  22691.5  22795.6
17420  20230123   232000    232959  1674487799  22793.6  22861.1
17421  20230123   233000    233959  1674488399  22862.1    22830
17422  20230123   234000    234959  1674488999  22834.2  22905.7
17423  20230123   235000    235959  1674489599  22906.3    22852
2023-01-24 00:00:01,869:INFO:pyemd2:main.py:127:handleKline:185189: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': False, 'isOpen': True, 'isClose': False, 'isTrig': True}
closeBuy: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '41.571', 'enterprice': '22787', 'countrevence': '0', 'unrealprofit': '2882.16980696574', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '22856.33125994', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
2023-01-24 00:00:02,839:INFO:pyemd2:main.py:251:closeBuy:185189: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}
2023-01-24 00:00:02,839:INFO:pyemd2:main.py:252:closeBuy:185189: ret = self.client.insertMarketUOrder("simulator",  BTCUSDT, 41.571, sell ), ret=InsertOrderReturn{'result': 'success', 'clientorderid': '41591F1674489602731I0L57'}
2023-01-24 00:00:02,879:INFO:pyemd2:main.py:190:insertFactor:185189: curDateTime:1240000, name:pyemd2, symbol:BTCUSDT, tradeDate:20230123, closeTime:235959, close:22852, total:946331.098623, pct_pre:0.002543185758159705, thd:0.48671033281462345, side:sell 
127.0.0.1 - - [24/Jan/2023 00:00:03] "POST / HTTP/1.1" 200 -
2023-01-24 00:00:03,252:INFO:pyemd2:main.py:300:handleOrderNew:185189: handleOrderNew: data=OrderType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'clientorderid': '41591F1674489602731I0L57', 'symbol': 'BTCUSDT', 'gatewayorderid': 1674489602984988, 'quantity': '41.571', 'price': '22855.7', 'stopprice': '0', 'ordertype': '', 'side': 'SELL', 'status': 'FILLED', 'positionside': 'SHORT', 'createtime': 1674489602136, 'updatetime': 1674489602984, 'tradetype': 'usdt', 'selfid': 41591, 'filltrades': [TradeType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'tradeid': 1674489602984, 'clientorderid': '41591F1674489602731I0L57', 'price': '22855.7', 'quantity': '41.571', 'commission': '950.1343047', 'commissionasset': 'USDT', 'tradetime': 1674489602984, 'tradetype': 'usdt', 'gatetype': 'simulator', 'handletime': 1674489602984}], 'gatetype': 'simulator', 'handletime': 0}
2023-01-24 00:00:03,497:INFO:pyemd2:main.py:303:handleOrderFilled:185189: handleOrderFilled: data=OrderType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'clientorderid': '41591F1674489602731I0L57', 'symbol': 'BTCUSDT', 'gatewayorderid': 1674489602984988, 'quantity': '41.571', 'price': '22855.7', 'stopprice': '0', 'ordertype': '', 'side': 'SELL', 'status': 'FILLED', 'positionside': 'SHORT', 'createtime': 1674489602136, 'updatetime': 1674489602984, 'tradetype': 'usdt', 'selfid': 41591, 'filltrades': [TradeType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'tradeid': 1674489602984, 'clientorderid': '41591F1674489602731I0L57', 'price': '22855.7', 'quantity': '41.571', 'commission': '950.1343047', 'commissionasset': 'USDT', 'tradetime': 1674489602984, 'tradetype': 'usdt', 'gatetype': 'simulator', 'handletime': 1674489602984}], 'gatetype': 'simulator', 'handletime': 0}
127.0.0.1 - - [24/Jan/2023 00:00:03] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [24/Jan/2023 00:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=8553 

self.closeSec=1674490199, self.tradeDate='20230124', self.openTime='000000', self.closeTime='000959', self.symbol='BTCUSDT', self.open='22852.1', self.close='22897.7'
2023-01-24 00:10:01,536:INFO:pyemd2:main.py:125:handleKline:185189: self.closeSec=1674490199, self.tradeDate='20230124', self.openTime='000000', self.closeTime='000959',self.symbol='BTCUSDT',self.open='22852.1', self.close='22897.7'
2023-01-24 00:10:01,554:INFO:pyemd2:main.py:126:handleKline:185189: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17420  20230123   232000    232959  1674487799  22793.6  22861.1
17421  20230123   233000    233959  1674488399  22862.1    22830
17422  20230123   234000    234959  1674488999  22834.2  22905.7
17423  20230123   235000    235959  1674489599  22906.3    22852
17424  20230124   000000    000959  1674490199  22852.1  22897.7
2023-01-24 00:10:01,554:INFO:pyemd2:main.py:127:handleKline:185189: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}


## /root/FIL/strategy/similarity/log.txt ----- -----

2023-01-24 00:00:01,851:INFO:testStrategy:main.py:102:handleKline:185174: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12235  20230123   231000    231959  1674487199  22691.5  22795.6
12236  20230123   232000    232959  1674487799  22793.6  22861.1
12237  20230123   233000    233959  1674488399  22862.1    22830
12238  20230123   234000    234959  1674488999  22834.2  22905.7
12239  20230123   235000    235959  1674489599  22906.3    22852
2023-01-24 00:00:01,851:INFO:testStrategy:main.py:103:handleKline:185174: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}
closeBuy: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '49.067', 'enterprice': '22669.4', 'countrevence': '0', 'unrealprofit': '9172.15613147598', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '22856.33125994', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
2023-01-24 00:00:02,551:INFO:testStrategy:main.py:233:closeBuy:185174: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False, 'isCorr': False}
2023-01-24 00:00:02,551:INFO:testStrategy:main.py:234:closeBuy:185174: ret = self.client.insertMarketUOrder("simulator",  BTCUSDT, 49.067, sell ), ret=InsertOrderReturn{'result': 'success', 'clientorderid': '41590F1674489602549I0L2'}
2023-01-24 00:00:02,587:INFO:testStrategy:main.py:172:insertFactor:185174: curDateTime:1240000, name:testStrategy, symbol:BTCUSDT, tradeDate:20230123, closeTime:235959, close:22852, total:1111207.1303502, corrDate:20230110, corrVal:0.8973451517745759, side:sell 
2023-01-24 00:00:02,899:INFO:testStrategy:main.py:305:handleOrderNew:185174: handleOrderNew: data=OrderType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'clientorderid': '41590F1674489602549I0L2', 'symbol': 'BTCUSDT', 'gatewayorderid': 1674489602651128, 'quantity': '49.067', 'price': '22855.7', 'stopprice': '0', 'ordertype': '', 'side': 'SELL', 'status': 'FILLED', 'positionside': 'SHORT', 'createtime': 1674489602127, 'updatetime': 1674489602651, 'tradetype': 'usdt', 'selfid': 41590, 'filltrades': [TradeType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'tradeid': 1674489602651, 'clientorderid': '41590F1674489602549I0L2', 'price': '22855.7', 'quantity': '49.067', 'commission': '1121.4606319', 'commissionasset': 'USDT', 'tradetime': 1674489602651, 'tradetype': 'usdt', 'gatetype': 'simulator', 'handletime': 1674489602651}], 'gatetype': 'simulator', 'handletime': 0}
127.0.0.1 - - [24/Jan/2023 00:00:02] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [24/Jan/2023 00:00:03] "POST / HTTP/1.1" 200 -
2023-01-24 00:00:03,233:INFO:testStrategy:main.py:308:handleOrderFilled:185174: handleOrderFilled: data=OrderType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'clientorderid': '41590F1674489602549I0L2', 'symbol': 'BTCUSDT', 'gatewayorderid': 1674489602651128, 'quantity': '49.067', 'price': '22855.7', 'stopprice': '0', 'ordertype': '', 'side': 'SELL', 'status': 'FILLED', 'positionside': 'SHORT', 'createtime': 1674489602127, 'updatetime': 1674489602651, 'tradetype': 'usdt', 'selfid': 41590, 'filltrades': [TradeType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'tradeid': 1674489602651, 'clientorderid': '41590F1674489602549I0L2', 'price': '22855.7', 'quantity': '49.067', 'commission': '1121.4606319', 'commissionasset': 'USDT', 'tradetime': 1674489602651, 'tradetype': 'usdt', 'gatetype': 'simulator', 'handletime': 1674489602651}], 'gatetype': 'simulator', 'handletime': 0}

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=8553 

self.closeSec=1674490199, self.tradeDate='20230124', self.openTime='000000', self.closeTime='000959', self.symbol='BTCUSDT', self.open='22852.1', self.close='22897.7'
2023-01-24 00:10:01,515:INFO:testStrategy:main.py:101:handleKline:185174: self.closeSec=1674490199, self.tradeDate='20230124', self.openTime='000000', self.closeTime='000959',self.symbol='BTCUSDT',self.open='22852.1', self.close='22897.7'
127.0.0.1 - - [24/Jan/2023 00:10:01] "POST / HTTP/1.1" 200 -
2023-01-24 00:10:01,530:INFO:testStrategy:main.py:102:handleKline:185174: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12236  20230123   232000    232959  1674487799  22793.6  22861.1
12237  20230123   233000    233959  1674488399  22862.1    22830
12238  20230123   234000    234959  1674488999  22834.2  22905.7
12239  20230123   235000    235959  1674489599  22906.3    22852
12240  20230124   000000    000959  1674490199  22852.1  22897.7
2023-01-24 00:10:01,530:INFO:testStrategy:main.py:103:handleKline:185174: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False, 'isCorr': False}


## /root/FIL/strategy/sr_min/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=0, self.total=1000000.0, self.flagDict['side']='', self.tradeCount=0, self.count=12536
self.closeSec=1674490199, self.tradeDate='20230124', self.openTime='000500', self.closeTime='000959', self.symbol='BTCUSDT', self.open=22909.0, self.close=22897.7, self.high=22929.3, self.low=22876.0, self.vol=2078.298, self.amt=47600281.7784 
127.0.0.1 - - [24/Jan/2023 00:10:01] "POST / HTTP/1.1" 200 -
2023-01-24 00:10:01,486:INFO:sr_min:main.py:172:handleKline:449472: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5757  20230123   234500    234959  ...         0.0        0.0       0
5758  20230123   235000    235459  ...         0.0        0.0       0
5759  20230123   235500    235959  ...         0.0        0.0       0
5760  20230124   000000    000459  ...         0.0        0.0       0
5761  20230124   000500    000959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-01-24 00:10:01,486:INFO:sr_min:main.py:175:handleKline:449472: self.closeSec=1674490199, self.tradeDate='20230124', self.openTime='000500', self.closeTime='000959',self.symbol='BTCUSDT',self.open=22909.0, self.close=22897.7, self.high=22929.3, self.low=22876.0, self.vol=2078.298, self.amt=47600281.7784, ukdf['pct'].iloc[-1]=-0.000672 , ukdf['amount'].iloc[-1]=47600281.7784, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5761, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': []}
type(curSign)=<class 'int'>, curSign=0, self.sign=0
--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=0, self.total=1000000.0, self.flagDict['side']='', self.tradeCount=0, self.count=12537
self.closeSec=1674490499, self.tradeDate='20230124', self.openTime='001000', self.closeTime='001459', self.symbol='BTCUSDT', self.open=22897.7, self.close=22870.9, self.high=22908.7, self.low=22870.9, self.vol=998.273, self.amt=22851170.4645 
127.0.0.1 - - [24/Jan/2023 00:15:00] "POST / HTTP/1.1" 200 -
2023-01-24 00:15:00,911:INFO:sr_min:main.py:172:handleKline:449472: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5758  20230123   235000    235459  ...         0.0        0.0       0
5759  20230123   235500    235959  ...         0.0        0.0       0
5760  20230124   000000    000459  ...         0.0        0.0       0
5761  20230124   000500    000959  ...         0.0        0.0       0
5762  20230124   001000    001459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-01-24 00:15:00,911:INFO:sr_min:main.py:175:handleKline:449472: self.closeSec=1674490499, self.tradeDate='20230124', self.openTime='001000', self.closeTime='001459',self.symbol='BTCUSDT',self.open=22897.7, self.close=22870.9, self.high=22908.7, self.low=22870.9, self.vol=998.273, self.amt=22851170.4645, ukdf['pct'].iloc[-1]=-0.00117 , ukdf['amount'].iloc[-1]=22851170.4645, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5762, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': []}
type(curSign)=<class 'int'>, curSign=0, self.sign=0


## /root/FIL/strategy/s_rsrs/log.txt ----- -----

723  20230123   120000    155959  1674460799  ...    723  1.032809  0.501858     NaN
724  20230123   160000    195959  1674475199  ...    724  1.000022  0.408161     NaN

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '41.799', 'enterprice': '23284.2', 'countrevence': '0', 'unrealprofit': '-15806.38662797853', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '22906.04773253', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-9223372036854775808, self.sign=1
127.0.0.1 - - [24/Jan/2023 00:00:01] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='s_rsrs', self.symbol='BTCUSDT', interval='4h', intervalSec=14400, wid=25, thd=0.6, self.sign=1, self.total=972283.0195242, self.flagDict['side']='buy', self.tradeCount=14, self.count=356
self.closeSec=1674489599, self.tradeDate='20230123', self.openTime='200000', self.closeTime='235959', self.symbol='BTCUSDT', self.open=22906.4, self.close=22852.0, self.high=23160.0, self.low=22500.0, self.vol=183939.268, self.amt=4198657531.60359 
2023-01-24 00:00:01,727:INFO:s_rsrs:main.py:141:handleKline:185271: self.closeSec=1674489599, self.tradeDate='20230123', self.openTime='200000', self.closeTime='235959',self.symbol='BTCUSDT',self.open=22906.4, self.close=22852.0, self.high=23160.0, self.low=22500.0, self.vol=183939.268, self.amt=4198657531.60359 
2023-01-24 00:00:01,755:INFO:s_rsrs:main.py:142:handleKline:185271: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime  ...         vol           amt       pct
721  20230123   040000    075959  ...  139693.559  3.148397e+09 -0.000643
722  20230123   080000    115959  ...   47573.102  1.081411e+09 -0.002105
723  20230123   120000    155959  ...   36713.329  8.339291e+08  0.001536
724  20230123   160000    195959  ...   68823.859  1.571893e+09  0.009430
725  20230123   200000    235959  ...  183939.268  4.198658e+09 -0.002375

[5 rows x 11 columns]
2023-01-24 00:00:03,086:INFO:s_rsrs:main.py:151:handleKline:185271: df_s.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec  ...  index      beta    zscore  signal
721  20230123   040000    075959  1674431999  ...    721  1.092073  0.673076     1.0
722  20230123   080000    115959  1674446399  ...    722  1.069849  0.604791     1.0
723  20230123   120000    155959  1674460799  ...    723  1.032809  0.501858     NaN
724  20230123   160000    195959  1674475199  ...    724  1.000022  0.408161     NaN
725  20230123   200000    235959  1674489599  ...    725  0.979369  0.342718     NaN

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '41.799', 'enterprice': '23284.2', 'countrevence': '0', 'unrealprofit': '-17886.1740550821', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '22856.2908621', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-9223372036854775808, self.sign=1


