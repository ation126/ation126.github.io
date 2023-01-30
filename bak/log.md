# 20230131 00:16:02

## /root/FIL/strategy/amihud/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=993672.4896432, self.flagDict['side']='sell', self.tradeCount=2, self.count=18554
self.closeSec=1675094999, self.tradeDate='20230131', self.openTime='000500', self.closeTime='000959', self.symbol='BTCUSDT', self.open=23147.3, self.close=23173.4, self.high=23175.0, self.low=23139.6, self.vol=1139.852, self.amt=26396354.9774 
127.0.0.1 - - [31/Jan/2023 00:10:01] "POST / HTTP/1.1" 200 -
2023-01-31 00:10:01,496:INFO:amihud:main.py:172:handleKline:200676: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5757  20230130   234500    234959  ...         0.0        0.0       0
5758  20230130   235000    235459  ...         0.0        0.0       0
5759  20230130   235500    235959  ...         0.0        0.0       0
5760  20230131   000000    000459  ...         0.0        0.0       0
5761  20230131   000500    000959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-01-31 00:10:01,497:INFO:amihud:main.py:175:handleKline:200676: self.closeSec=1675094999, self.tradeDate='20230131', self.openTime='000500', self.closeTime='000959',self.symbol='BTCUSDT',self.open=23147.3, self.close=23173.4, self.high=23175.0, self.low=23139.6, self.vol=1139.852, self.amt=26396354.9774, ukdf['pct'].iloc[-1]=0.001128 , ukdf['amount'].iloc[-1]=26396354.9774, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5761, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '60.176', 'enterprice': '16529.3', 'countrevence': '0', 'unrealprofit': '-399767.2208', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '23172.6', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1
--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=993672.4896432, self.flagDict['side']='sell', self.tradeCount=2, self.count=18555
self.closeSec=1675095299, self.tradeDate='20230131', self.openTime='001000', self.closeTime='001459', self.symbol='BTCUSDT', self.open=23172.5, self.close=23215.6, self.high=23247.0, self.low=23172.5, self.vol=3199.346, self.amt=74282759.018 
127.0.0.1 - - [31/Jan/2023 00:15:00] "POST / HTTP/1.1" 200 -
2023-01-31 00:15:00,729:INFO:amihud:main.py:172:handleKline:200676: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5758  20230130   235000    235459  ...         0.0        0.0       0
5759  20230130   235500    235959  ...         0.0        0.0       0
5760  20230131   000000    000459  ...         0.0        0.0       0
5761  20230131   000500    000959  ...         0.0        0.0       0
5762  20230131   001000    001459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-01-31 00:15:00,734:INFO:amihud:main.py:175:handleKline:200676: self.closeSec=1675095299, self.tradeDate='20230131', self.openTime='001000', self.closeTime='001459',self.symbol='BTCUSDT',self.open=23172.5, self.close=23215.6, self.high=23247.0, self.low=23172.5, self.vol=3199.346, self.amt=74282759.018, ukdf['pct'].iloc[-1]=0.001821 , ukdf['amount'].iloc[-1]=74282759.018, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5762, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '60.176', 'enterprice': '16529.3', 'countrevence': '0', 'unrealprofit': '-402565.49224054208', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '23219.10145308', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1


## /root/FIL/strategy/factorcheck/log.txt ----- -----

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=477, self.factor=0.500426260519102, self.count=19120 

self.closeSec=1675094999, self.tradeDate='20230131', self.openTime='000500', self.closeTime='000959', self.symbol='BTCUSDT', self.open=23147.3, self.close=23173.4, self.high=23175.0, self.low=23139.6 
2023-01-31 00:10:01,434:INFO:factorcheck2:main.py:126:handleKline:185239: self.closeSec=1675094999, self.tradeDate='20230131', self.openTime='000500', self.closeTime='000959',self.symbol='BTCUSDT',self.open=23147.3, self.close=23173.4, self.high=23175.0, self.low=23139.6   
2023-01-31 00:10:01,476:INFO:factorcheck2:main.py:127:handleKline:185239: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1437  20230130   234500    234959  1675093799  ...  23061.4  0.001268   1725    3
1438  20230130   235000    235459  1675094099  ...  23134.1  0.000372   1726    4
1439  20230130   235500    235959  1675094399  ...  23140.1  0.001331   1727    5
1440  20230131   000000    000459  1675094699  ...  23146.5 -0.001350   1440    0
1441  20230131   000500    000959  1675094999  ...  23139.6  0.001128   1441    1

[5 rows x 11 columns]
2023-01-31 00:10:01,476:INFO:factorcheck2:main.py:128:handleKline:185239: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}
127.0.0.1 - - [31/Jan/2023 00:15:00] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=477, self.factor=0.500426260519102, self.count=19121 

self.closeSec=1675095299, self.tradeDate='20230131', self.openTime='001000', self.closeTime='001459', self.symbol='BTCUSDT', self.open=23172.5, self.close=23215.6, self.high=23247.0, self.low=23172.5 
2023-01-31 00:15:00,714:INFO:factorcheck2:main.py:126:handleKline:185239: self.closeSec=1675095299, self.tradeDate='20230131', self.openTime='001000', self.closeTime='001459',self.symbol='BTCUSDT',self.open=23172.5, self.close=23215.6, self.high=23247.0, self.low=23172.5   
2023-01-31 00:15:00,762:INFO:factorcheck2:main.py:127:handleKline:185239: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1438  20230130   235000    235459  1675094099  ...  23134.1  0.000372   1726    4
1439  20230130   235500    235959  1675094399  ...  23140.1  0.001331   1727    5
1440  20230131   000000    000459  1675094699  ...  23146.5 -0.001350   1440    0
1441  20230131   000500    000959  1675094999  ...  23139.6  0.001128   1441    1
1442  20230131   001000    001459  1675095299  ...  23172.5  0.001821   1442    2

[5 rows x 11 columns]
2023-01-31 00:15:00,762:INFO:factorcheck2:main.py:128:handleKline:185239: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}


## /root/FIL/strategy/logic/log.txt ----- -----

2023-01-31 00:00:19,353:DEBUG:logic:main.py:463:getModel:885513: df_s.iloc[-5:,:] :
          date closeTime     open  ...    alpha58   alpha67   alpha72
5802  20230130    212959  23075.2  ...  51.666667  0.447059  0.597935
5803  20230130    215959  23125.2  ...  51.666667  0.434484  0.616651
5804  20230130    222959  23055.2  ...  52.083333  0.457538  0.627437
5805  20230130    225959  23158.7  ...  52.500000  0.483053  0.629577
5806  20230130    232959  23281.7  ...  52.083333  0.465707  0.637726

[5 rows x 33 columns]
0.53125
acc is : 0.53125
2023-01-31 00:00:19,451:INFO:logic:main.py:468:getModel:885513: df_pred.iloc[-5:,:] :
     pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
539     0  0.500280  0.499720       0  ...  1.024927  -1.0    0.0  1.107464
540     1  0.473433  0.526567       1  ...  1.020326  -1.0    0.0  1.112436
541     0  0.527165  0.472835       1  ...  1.014915  -1.0    0.0  1.118335
542     0  0.540682  0.459318       0  ...  1.019070  -1.0    0.0  1.113757
543     1  0.498885  0.501115       0  ...  1.019408  -1.0    0.0  1.113387

[5 rows x 10 columns]
2023-01-31 00:00:19,474:INFO:logic:main.py:478:getModel:885513: df_panel.iloc[-5:,:] :
    pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
45     1  0.497790  0.502210       0  ...  1.024927  -1.0    0.0  1.106778
46     1  0.471891  0.528109       1  ...  1.020326  -1.0    0.0  1.111848
47     0  0.525453  0.474547       1  ...  1.014915  -1.0    0.0  1.117744
48     0  0.539962  0.460038       0  ...  1.019070  -1.0    0.0  1.113238
49     1  0.498885  0.501115       0  ...  1.019408  -1.0    0.0  1.113387

[5 rows x 10 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '30.741', 'enterprice': '23173.4', 'countrevence': '0', 'unrealprofit': '-27.6669', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '23174.3', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}


## /root/FIL/strategy/modifiedmom/log.txt ----- -----

2023-01-31 00:00:02,489:INFO:modifiedmom:main.py:145:handleKline:185213: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
571  20230130   231000    231959  1675091999    23250    23220 -0.001286
572  20230130   232000    232959  1675092599  23219.9  23186.3 -0.001451
573  20230130   233000    233959  1675093199  23186.2    23132 -0.002342
574  20230130   234000    234959  1675093799  23132.1  23139.2  0.000311
575  20230130   235000    235959  1675094399  23139.1  23178.6  0.001703
2023-01-31 00:00:02,489:INFO:modifiedmom:main.py:146:handleKline:185213: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True}
closeBuy: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '40.434', 'enterprice': '23683.2', 'countrevence': '0', 'unrealprofit': '-20568.9001608321', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '23174.49692435', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
2023-01-31 00:00:03,105:INFO:modifiedmom:main.py:267:closeBuy:185213: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False}
2023-01-31 00:00:03,106:INFO:modifiedmom:main.py:268:closeBuy:185213: ret = self.client.insertMarketUOrder("simulator",  BTCUSDT, 40.434, sell ), ret=InsertOrderReturn{'result': 'success', 'clientorderid': '41638F1675094403100I0L59'}
2023-01-31 00:00:03,166:INFO:modifiedmom:main.py:206:insertFactor:185213: curDateTime:1310000, name:modifiedmom, symbol:BTCUSDT, tradeDate:20230130, closeTime:235959, close:23178.6, total:956648.9022912, mom:0.0003885163336667663, thd:0.0, side:sell 
2023-01-31 00:00:03,234:INFO:modifiedmom:main.py:316:handleOrderNew:185213: handleOrderNew: data=OrderType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'clientorderid': '41638F1675094403100I0L59', 'symbol': 'BTCUSDT', 'gatewayorderid': 1675094403205506, 'quantity': '40.434', 'price': '23172.8', 'stopprice': '0', 'ordertype': '', 'side': 'SELL', 'status': 'FILLED', 'positionside': 'SHORT', 'createtime': 1675094402647, 'updatetime': 1675094403205, 'tradetype': 'usdt', 'selfid': 41638, 'filltrades': [TradeType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'tradeid': 1675094403205, 'clientorderid': '41638F1675094403100I0L59', 'price': '23172.8', 'quantity': '40.434', 'commission': '936.9689952', 'commissionasset': 'USDT', 'tradetime': 1675094403205, 'tradetype': 'usdt', 'gatetype': 'simulator', 'handletime': 1675094403205}], 'gatetype': 'simulator', 'handletime': 0}
127.0.0.1 - - [31/Jan/2023 00:00:03] "POST / HTTP/1.1" 200 -
2023-01-31 00:00:03,519:INFO:modifiedmom:main.py:319:handleOrderFilled:185213: handleOrderFilled: data=OrderType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'clientorderid': '41638F1675094403100I0L59', 'symbol': 'BTCUSDT', 'gatewayorderid': 1675094403205506, 'quantity': '40.434', 'price': '23172.8', 'stopprice': '0', 'ordertype': '', 'side': 'SELL', 'status': 'FILLED', 'positionside': 'SHORT', 'createtime': 1675094402647, 'updatetime': 1675094403205, 'tradetype': 'usdt', 'selfid': 41638, 'filltrades': [TradeType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'tradeid': 1675094403205, 'clientorderid': '41638F1675094403100I0L59', 'price': '23172.8', 'quantity': '40.434', 'commission': '936.9689952', 'commissionasset': 'USDT', 'tradetime': 1675094403205, 'tradetype': 'usdt', 'gatetype': 'simulator', 'handletime': 1675094403205}], 'gatetype': 'simulator', 'handletime': 0}
127.0.0.1 - - [31/Jan/2023 00:00:03] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=9560 

self.closeSec=1675094999, self.tradeDate='20230131', self.openTime='000000', self.closeTime='000959', self.symbol='BTCUSDT', self.open='23178.6', self.close='23173.4'
2023-01-31 00:10:01,541:INFO:modifiedmom:main.py:144:handleKline:185213: self.closeSec=1675094999, self.tradeDate='20230131', self.openTime='000000', self.closeTime='000959',self.symbol='BTCUSDT',self.open='23178.6', self.close='23173.4'
127.0.0.1 - - [31/Jan/2023 00:10:01] "POST / HTTP/1.1" 200 -
2023-01-31 00:10:01,593:INFO:modifiedmom:main.py:145:handleKline:185213: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
572  20230130   232000    232959  1675092599  23219.9  23186.3 -0.001451
573  20230130   233000    233959  1675093199  23186.2    23132 -0.002342
574  20230130   234000    234959  1675093799  23132.1  23139.2  0.000311
575  20230130   235000    235959  1675094399  23139.1  23178.6  0.001703
576  20230131   000000    000959  1675094999  23178.6  23173.4 -0.000224
2023-01-31 00:10:01,596:INFO:modifiedmom:main.py:146:handleKline:185213: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False}


## /root/FIL/strategy/pyemd/log.txt ----- -----

2023-01-30 23:50:00,773:INFO:pyemd2:main.py:127:handleKline:185189: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=9560 

self.closeSec=1675094399, self.tradeDate='20230130', self.openTime='235000', self.closeTime='235959', self.symbol='BTCUSDT', self.open='23139.1', self.close='23178.6'
2023-01-31 00:00:02,479:INFO:pyemd2:main.py:125:handleKline:185189: self.closeSec=1675094399, self.tradeDate='20230130', self.openTime='235000', self.closeTime='235959',self.symbol='BTCUSDT',self.open='23139.1', self.close='23178.6'
127.0.0.1 - - [31/Jan/2023 00:00:02] "POST / HTTP/1.1" 200 -
2023-01-31 00:00:02,523:INFO:pyemd2:main.py:126:handleKline:185189: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17419  20230130   231000    231959  1675091999    23250    23220
17420  20230130   232000    232959  1675092599  23219.9  23186.3
17421  20230130   233000    233959  1675093199  23186.2    23132
17422  20230130   234000    234959  1675093799  23132.1  23139.2
17423  20230130   235000    235959  1675094399  23139.1  23178.6
2023-01-31 00:00:02,523:INFO:pyemd2:main.py:127:handleKline:185189: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}
2023-01-31 00:00:02,623:INFO:pyemd2:main.py:190:insertFactor:185189: curDateTime:1310000, name:pyemd2, symbol:BTCUSDT, tradeDate:20230130, closeTime:235959, close:23178.6, total:949628.8116041, pct_pre:-0.013080684076373417, thd:0.1818592414989072, side:sell 

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=9561 

self.closeSec=1675094999, self.tradeDate='20230131', self.openTime='000000', self.closeTime='000959', self.symbol='BTCUSDT', self.open='23178.6', self.close='23173.4'
2023-01-31 00:10:01,557:INFO:pyemd2:main.py:125:handleKline:185189: self.closeSec=1675094999, self.tradeDate='20230131', self.openTime='000000', self.closeTime='000959',self.symbol='BTCUSDT',self.open='23178.6', self.close='23173.4'
127.0.0.1 - - [31/Jan/2023 00:10:01] "POST / HTTP/1.1" 200 -
2023-01-31 00:10:01,604:INFO:pyemd2:main.py:126:handleKline:185189: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17420  20230130   232000    232959  1675092599  23219.9  23186.3
17421  20230130   233000    233959  1675093199  23186.2    23132
17422  20230130   234000    234959  1675093799  23132.1  23139.2
17423  20230130   235000    235959  1675094399  23139.1  23178.6
17424  20230131   000000    000959  1675094999  23178.6  23173.4
2023-01-31 00:10:01,605:INFO:pyemd2:main.py:127:handleKline:185189: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}


## /root/FIL/strategy/similarity/log.txt ----- -----

2023-01-31 00:00:02,512:INFO:testStrategy:main.py:102:handleKline:185174: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12235  20230130   231000    231959  1675091999    23250    23220
12236  20230130   232000    232959  1675092599  23219.9  23186.3
12237  20230130   233000    233959  1675093199  23186.2    23132
12238  20230130   234000    234959  1675093799  23132.1  23139.2
12239  20230130   235000    235959  1675094399  23139.1  23178.6
2023-01-31 00:00:02,513:INFO:testStrategy:main.py:103:handleKline:185174: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': True, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}
closeSell: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '46.26', 'enterprice': '23771.5', 'countrevence': '0', 'unrealprofit': '27617.362279569', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '23174.49692435', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
2023-01-31 00:00:03,132:INFO:testStrategy:main.py:253:closeSell:185174: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False, 'isCorr': False}
2023-01-31 00:00:03,132:INFO:testStrategy:main.py:254:closeSell:185174: ret = self.client.insertMarketUOrder("simulator",  BTCUSDT, 46.26, buy ), ret=InsertOrderReturn{'result': 'success', 'clientorderid': '41639F1675094403128I0L2'}
2023-01-31 00:00:03,180:INFO:testStrategy:main.py:172:insertFactor:185174: curDateTime:1310000, name:testStrategy, symbol:BTCUSDT, tradeDate:20230130, closeTime:235959, close:23178.6, total:1098569.9204099998, corrDate:20221209, corrVal:0.9055373764478397, side:buy 
127.0.0.1 - - [31/Jan/2023 00:00:03] "POST / HTTP/1.1" 200 -
2023-01-31 00:00:03,517:INFO:testStrategy:main.py:305:handleOrderNew:185174: handleOrderNew: data=OrderType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'clientorderid': '41639F1675094403128I0L2', 'symbol': 'BTCUSDT', 'gatewayorderid': 1675094403234133, 'quantity': '46.26', 'price': '23172.9', 'stopprice': '0', 'ordertype': '', 'side': 'BUY', 'status': 'FILLED', 'positionside': 'LONG', 'createtime': 1675094402675, 'updatetime': 1675094403234, 'tradetype': 'usdt', 'selfid': 41639, 'filltrades': [TradeType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'tradeid': 1675094403234, 'clientorderid': '41639F1675094403128I0L2', 'price': '23172.9', 'quantity': '46.26', 'commission': '1071.978354', 'commissionasset': 'USDT', 'tradetime': 1675094403234, 'tradetype': 'usdt', 'gatetype': 'simulator', 'handletime': 1675094403234}], 'gatetype': 'simulator', 'handletime': 0}
127.0.0.1 - - [31/Jan/2023 00:00:03] "POST / HTTP/1.1" 200 -
2023-01-31 00:00:03,702:INFO:testStrategy:main.py:308:handleOrderFilled:185174: handleOrderFilled: data=OrderType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'clientorderid': '41639F1675094403128I0L2', 'symbol': 'BTCUSDT', 'gatewayorderid': 1675094403234133, 'quantity': '46.26', 'price': '23172.9', 'stopprice': '0', 'ordertype': '', 'side': 'BUY', 'status': 'FILLED', 'positionside': 'LONG', 'createtime': 1675094402675, 'updatetime': 1675094403234, 'tradetype': 'usdt', 'selfid': 41639, 'filltrades': [TradeType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'tradeid': 1675094403234, 'clientorderid': '41639F1675094403128I0L2', 'price': '23172.9', 'quantity': '46.26', 'commission': '1071.978354', 'commissionasset': 'USDT', 'tradetime': 1675094403234, 'tradetype': 'usdt', 'gatetype': 'simulator', 'handletime': 1675094403234}], 'gatetype': 'simulator', 'handletime': 0}
127.0.0.1 - - [31/Jan/2023 00:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=9561 

self.closeSec=1675094999, self.tradeDate='20230131', self.openTime='000000', self.closeTime='000959', self.symbol='BTCUSDT', self.open='23178.6', self.close='23173.4'
2023-01-31 00:10:01,525:INFO:testStrategy:main.py:101:handleKline:185174: self.closeSec=1675094999, self.tradeDate='20230131', self.openTime='000000', self.closeTime='000959',self.symbol='BTCUSDT',self.open='23178.6', self.close='23173.4'
2023-01-31 00:10:01,599:INFO:testStrategy:main.py:102:handleKline:185174: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12236  20230130   232000    232959  1675092599  23219.9  23186.3
12237  20230130   233000    233959  1675093199  23186.2    23132
12238  20230130   234000    234959  1675093799  23132.1  23139.2
12239  20230130   235000    235959  1675094399  23139.1  23178.6
12240  20230131   000000    000959  1675094999  23178.6  23173.4
2023-01-31 00:10:01,599:INFO:testStrategy:main.py:103:handleKline:185174: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False, 'isCorr': False}


## /root/FIL/strategy/sr_min/log.txt ----- -----

127.0.0.1 - - [31/Jan/2023 00:10:01] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=0, self.total=1000000.0, self.flagDict['side']='', self.tradeCount=0, self.count=14552
self.closeSec=1675094999, self.tradeDate='20230131', self.openTime='000500', self.closeTime='000959', self.symbol='BTCUSDT', self.open=23147.3, self.close=23173.4, self.high=23175.0, self.low=23139.6, self.vol=1139.852, self.amt=26396354.9774 
2023-01-31 00:10:01,495:INFO:sr_min:main.py:172:handleKline:449472: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5757  20230130   234500    234959  ...         0.0        0.0       0
5758  20230130   235000    235459  ...         0.0        0.0       0
5759  20230130   235500    235959  ...         0.0        0.0       0
5760  20230131   000000    000459  ...         0.0        0.0       0
5761  20230131   000500    000959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-01-31 00:10:01,496:INFO:sr_min:main.py:175:handleKline:449472: self.closeSec=1675094999, self.tradeDate='20230131', self.openTime='000500', self.closeTime='000959',self.symbol='BTCUSDT',self.open=23147.3, self.close=23173.4, self.high=23175.0, self.low=23139.6, self.vol=1139.852, self.amt=26396354.9774, ukdf['pct'].iloc[-1]=0.001128 , ukdf['amount'].iloc[-1]=26396354.9774, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5761, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': []}
type(curSign)=<class 'int'>, curSign=0, self.sign=0
127.0.0.1 - - [31/Jan/2023 00:15:00] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=0, self.total=1000000.0, self.flagDict['side']='', self.tradeCount=0, self.count=14553
self.closeSec=1675095299, self.tradeDate='20230131', self.openTime='001000', self.closeTime='001459', self.symbol='BTCUSDT', self.open=23172.5, self.close=23215.6, self.high=23247.0, self.low=23172.5, self.vol=3199.346, self.amt=74282759.018 
2023-01-31 00:15:00,785:INFO:sr_min:main.py:172:handleKline:449472: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5758  20230130   235000    235459  ...         0.0        0.0       0
5759  20230130   235500    235959  ...         0.0        0.0       0
5760  20230131   000000    000459  ...         0.0        0.0       0
5761  20230131   000500    000959  ...         0.0        0.0       0
5762  20230131   001000    001459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-01-31 00:15:00,787:INFO:sr_min:main.py:175:handleKline:449472: self.closeSec=1675095299, self.tradeDate='20230131', self.openTime='001000', self.closeTime='001459',self.symbol='BTCUSDT',self.open=23172.5, self.close=23215.6, self.high=23247.0, self.low=23172.5, self.vol=3199.346, self.amt=74282759.018, ukdf['pct'].iloc[-1]=0.001821 , ukdf['amount'].iloc[-1]=74282759.018, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5762, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': []}
type(curSign)=<class 'int'>, curSign=0, self.sign=0


## /root/FIL/strategy/s_rsrs/log.txt ----- -----

723  20230130   120000    155959  1675065599  ...    723  0.699296  0.560167     NaN
724  20230130   160000    195959  1675079999  ...    724  0.645062  0.429012     NaN

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '38.964', 'enterprice': '23700.1', 'countrevence': '0', 'unrealprofit': '-24230.41982222196', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '23078.23315311', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-9223372036854775808, self.sign=1
127.0.0.1 - - [31/Jan/2023 00:00:02] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='s_rsrs', self.symbol='BTCUSDT', interval='4h', intervalSec=14400, wid=25, thd=0.6, self.sign=1, self.total=922527.2457035999, self.flagDict['side']='buy', self.tradeCount=16, self.count=398
self.closeSec=1675094399, self.tradeDate='20230130', self.openTime='200000', self.closeTime='235959', self.symbol='BTCUSDT', self.open=23075.2, self.close=23178.6, self.high=23295.8, self.low=22930.0, self.vol=114367.727, self.amt=2644438700.0053 
2023-01-31 00:00:02,157:INFO:s_rsrs:main.py:141:handleKline:185271: self.closeSec=1675094399, self.tradeDate='20230130', self.openTime='200000', self.closeTime='235959',self.symbol='BTCUSDT',self.open=23075.2, self.close=23178.6, self.high=23295.8, self.low=22930.0, self.vol=114367.727, self.amt=2644438700.0053 
2023-01-31 00:00:02,194:INFO:s_rsrs:main.py:142:handleKline:185271: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime  ...         vol           amt       pct
721  20230130   040000    075959  ...   71846.477  1.708220e+09 -0.006541
722  20230130   080000    115959  ...   50623.845  1.198734e+09 -0.001664
723  20230130   120000    155959  ...   35817.696  8.486056e+08 -0.002224
724  20230130   160000    195959  ...  178463.464  4.155246e+09 -0.024226
725  20230130   200000    235959  ...  114367.727  2.644439e+09  0.004481

[5 rows x 11 columns]
2023-01-31 00:00:03,696:INFO:s_rsrs:main.py:151:handleKline:185271: df_s.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec  ...  index      beta    zscore  signal
721  20230130   040000    075959  1675036799  ...    721  0.355328 -0.386449     NaN
722  20230130   080000    115959  1675051199  ...    722  0.734259  0.636107     1.0
723  20230130   120000    155959  1675065599  ...    723  0.699296  0.560167     NaN
724  20230130   160000    195959  1675079999  ...    724  0.645062  0.429012     NaN
725  20230130   200000    235959  1675094399  ...    725  0.618886  0.372043     NaN

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '38.964', 'enterprice': '23700.1', 'countrevence': '0', 'unrealprofit': '-20491.25494715736', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '23174.19775826', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-9223372036854775808, self.sign=1


