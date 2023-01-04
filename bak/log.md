# 20230105 00:16:01

## /root/FIL/strategy/amihud/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=993672.4896432, self.flagDict['side']='sell', self.tradeCount=2, self.count=11066
self.closeSec=1672848599, self.tradeDate='20230105', self.openTime='000500', self.closeTime='000959', self.symbol='BTCUSDT', self.open=16836.3, self.close=16844.7, self.high=16845.6, self.low=16824.3, self.vol=1417.718, self.amt=23869757.4666 
127.0.0.1 - - [05/Jan/2023 00:10:01] "POST / HTTP/1.1" 200 -
2023-01-05 00:10:01,482:INFO:amihud:main.py:172:handleKline:200676: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5757  20230104   234500    234959  ...         0.0        0.0       0
5758  20230104   235000    235459  ...         0.0        0.0       0
5759  20230104   235500    235959  ...         0.0        0.0       0
5760  20230105   000000    000459  ...         0.0        0.0       0
5761  20230105   000500    000959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-01-05 00:10:01,483:INFO:amihud:main.py:175:handleKline:200676: self.closeSec=1672848599, self.tradeDate='20230105', self.openTime='000500', self.closeTime='000959',self.symbol='BTCUSDT',self.open=16836.3, self.close=16844.7, self.high=16845.6, self.low=16824.3, self.vol=1417.718, self.amt=23869757.4666, ukdf['pct'].iloc[-1]=0.000487 , ukdf['amount'].iloc[-1]=23869757.4666, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5761, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '60.176', 'enterprice': '16529.3', 'countrevence': '0', 'unrealprofit': '-18973.4928', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '16844.6', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1
127.0.0.1 - - [05/Jan/2023 00:15:00] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=993672.4896432, self.flagDict['side']='sell', self.tradeCount=2, self.count=11067
self.closeSec=1672848899, self.tradeDate='20230105', self.openTime='001000', self.closeTime='001459', self.symbol='BTCUSDT', self.open=16844.6, self.close=16874.0, self.high=16874.0, self.low=16844.6, self.vol=3192.187, self.amt=53820772.3227 
2023-01-05 00:15:00,580:INFO:amihud:main.py:172:handleKline:200676: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5758  20230104   235000    235459  ...         0.0        0.0       0
5759  20230104   235500    235959  ...         0.0        0.0       0
5760  20230105   000000    000459  ...         0.0        0.0       0
5761  20230105   000500    000959  ...         0.0        0.0       0
5762  20230105   001000    001459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-01-05 00:15:00,581:INFO:amihud:main.py:175:handleKline:200676: self.closeSec=1672848899, self.tradeDate='20230105', self.openTime='001000', self.closeTime='001459',self.symbol='BTCUSDT',self.open=16844.6, self.close=16874.0, self.high=16874.0, self.low=16844.6, self.vol=3192.187, self.amt=53820772.3227, ukdf['pct'].iloc[-1]=0.001739 , ukdf['amount'].iloc[-1]=53820772.3227, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5762, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '60.176', 'enterprice': '16529.3', 'countrevence': '0', 'unrealprofit': '-20899.1248', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '16876.6', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1


## /root/FIL/strategy/factorcheck/log.txt ----- -----


self.closeSec=1672848599, self.tradeDate='20230105', self.openTime='000500', self.closeTime='000959', self.symbol='BTCUSDT', self.open=16836.3, self.close=16844.7, self.high=16845.6, self.low=16824.3 
2023-01-05 00:10:01,414:INFO:factorcheck2:main.py:126:handleKline:185239: self.closeSec=1672848599, self.tradeDate='20230105', self.openTime='000500', self.closeTime='000959',self.symbol='BTCUSDT',self.open=16836.3, self.close=16844.7, self.high=16845.6, self.low=16824.3   
127.0.0.1 - - [05/Jan/2023 00:10:01] "POST / HTTP/1.1" 200 -
2023-01-05 00:10:01,445:INFO:factorcheck2:main.py:127:handleKline:185239: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1437  20230104   234500    234959  1672847399  ...  16825.0  0.000749   1725    3
1438  20230104   235000    235459  1672847699  ...  16831.8  0.000309   1726    4
1439  20230104   235500    235959  1672847999  ...  16835.0  0.000226   1727    5
1440  20230105   000000    000459  1672848299  ...  16836.4 -0.000600   1440    0
1441  20230105   000500    000959  1672848599  ...  16824.3  0.000487   1441    1

[5 rows x 11 columns]
2023-01-05 00:10:01,445:INFO:factorcheck2:main.py:128:handleKline:185239: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=102, self.factor=0.34383469180157933, self.count=11633 

self.closeSec=1672848899, self.tradeDate='20230105', self.openTime='001000', self.closeTime='001459', self.symbol='BTCUSDT', self.open=16844.6, self.close=16874.0, self.high=16874.0, self.low=16844.6 
2023-01-05 00:15:00,513:INFO:factorcheck2:main.py:126:handleKline:185239: self.closeSec=1672848899, self.tradeDate='20230105', self.openTime='001000', self.closeTime='001459',self.symbol='BTCUSDT',self.open=16844.6, self.close=16874.0, self.high=16874.0, self.low=16844.6   
127.0.0.1 - - [05/Jan/2023 00:15:00] "POST / HTTP/1.1" 200 -
2023-01-05 00:15:00,546:INFO:factorcheck2:main.py:127:handleKline:185239: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1438  20230104   235000    235459  1672847699  ...  16831.8  0.000309   1726    4
1439  20230104   235500    235959  1672847999  ...  16835.0  0.000226   1727    5
1440  20230105   000000    000459  1672848299  ...  16836.4 -0.000600   1440    0
1441  20230105   000500    000959  1672848599  ...  16824.3  0.000487   1441    1
1442  20230105   001000    001459  1672848899  ...  16844.6  0.001739   1442    2

[5 rows x 11 columns]
2023-01-05 00:15:00,546:INFO:factorcheck2:main.py:128:handleKline:185239: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}


## /root/FIL/strategy/logic/log.txt ----- -----

2023-01-05 00:00:18,506:DEBUG:logic:main.py:456:getModel:726423: df_s.iloc[-5:,:] :
          date closeTime     open  ...    alpha58   alpha67   alpha72
5802  20230104    212959  16808.0  ...  48.750000  0.565877  0.311456
5803  20230104    215959  16818.8  ...  49.166667  0.566688  0.311574
5804  20230104    222959  16820.2  ...  48.750000  0.557764  0.314119
5805  20230104    225959  16809.3  ...  49.166667  0.565326  0.313859
5806  20230104    232959  16820.9  ...  48.750000  0.558472  0.315768

[5 rows x 33 columns]
0.5091911764705882
acc is : 0.5091911764705882
2023-01-05 00:00:18,585:INFO:logic:main.py:461:getModel:726423: df_pred.iloc[-5:,:] :
     pred    prob_0    prob_1  actual  ...  nav  sign   cost_        bm
539     1  0.496550  0.503450       1  ...  NaN   NaN -0.0016  0.998800
540     1  0.494595  0.505405       0  ...  NaN   NaN -0.0016  0.998153
541     1  0.492062  0.507938       1  ...  NaN   NaN -0.0016  0.998854
542     1  0.497116  0.502884       0  ...  NaN   NaN -0.0016  0.998361
543     1  0.494856  0.505144       1  ...  NaN   NaN -0.0016  1.000374

[5 rows x 10 columns]
2023-01-05 00:00:18,596:INFO:logic:main.py:471:getModel:726423: df_panel.iloc[-5:,:] :
    pred    prob_0    prob_1  actual  ...  nav  sign   cost_        bm
45     1  0.496849  0.503151       1  ...  NaN   NaN -0.0016  1.000494
46     1  0.495042  0.504958       0  ...  NaN   NaN -0.0016  0.999899
47     1  0.492505  0.507495       1  ...  NaN   NaN -0.0016  1.000601
48     1  0.497328  0.502672       0  ...  NaN   NaN -0.0016  0.999233
49     1  0.494856  0.505144       1  ...  NaN   NaN -0.0016  1.000374

[5 rows x 10 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '42.528', 'enterprice': '16701.5', 'countrevence': '0', 'unrealprofit': '6183.5712', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '16846.9', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}


## /root/FIL/strategy/modifiedmom/log.txt ----- -----

2023-01-05 00:00:01,172:INFO:modifiedmom:main.py:145:handleKline:185213: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
571  20230104   231000    231959  1672845599  16778.1  16801.8  0.001562
572  20230104   232000    232959  1672846199  16801.8  16812.7  0.000649
573  20230104   233000    233959  1672846799  16812.7    16813  0.000018
574  20230104   234000    234959  1672847399    16813  16837.6  0.001463
575  20230104   235000    235959  1672847999  16837.7  16846.6  0.000535
2023-01-05 00:00:01,173:INFO:modifiedmom:main.py:146:handleKline:185213: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True}
closeBuy: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '54.751', 'enterprice': '16810', 'countrevence': '0', 'unrealprofit': '2043.84573531139', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '16847.32983389', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
2023-01-05 00:00:01,946:INFO:modifiedmom:main.py:267:closeBuy:185213: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False}
2023-01-05 00:00:01,946:INFO:modifiedmom:main.py:268:closeBuy:185213: ret = self.client.insertMarketUOrder("simulator",  BTCUSDT, 54.751, sell ), ret=InsertOrderReturn{'result': 'success', 'clientorderid': '41473F1672848001944I0L59'}
2023-01-05 00:00:01,983:INFO:modifiedmom:main.py:206:insertFactor:185213: curDateTime:1050000, name:modifiedmom, symbol:BTCUSDT, tradeDate:20230104, closeTime:235959, close:16846.6, total:919443.94569, mom:0.0016132930577761329, thd:0.0, side:sell 
2023-01-05 00:00:02,444:INFO:modifiedmom:main.py:316:handleOrderNew:185213: handleOrderNew: data=OrderType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'clientorderid': '41473F1672848001944I0L59', 'symbol': 'BTCUSDT', 'gatewayorderid': 1672848002052712, 'quantity': '54.751', 'price': '16846.5', 'stopprice': '0', 'ordertype': '', 'side': 'SELL', 'status': 'FILLED', 'positionside': 'SHORT', 'createtime': 1672848001574, 'updatetime': 1672848002052, 'tradetype': 'usdt', 'selfid': 41473, 'filltrades': [TradeType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'tradeid': 1672848002052, 'clientorderid': '41473F1672848001944I0L59', 'price': '16846.5', 'quantity': '54.751', 'commission': '922.3627215', 'commissionasset': 'USDT', 'tradetime': 1672848002052, 'tradetype': 'usdt', 'gatetype': 'simulator', 'handletime': 1672848002052}], 'gatetype': 'simulator', 'handletime': 0}
127.0.0.1 - - [05/Jan/2023 00:00:02] "POST / HTTP/1.1" 200 -
2023-01-05 00:00:02,664:INFO:modifiedmom:main.py:319:handleOrderFilled:185213: handleOrderFilled: data=OrderType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'clientorderid': '41473F1672848001944I0L59', 'symbol': 'BTCUSDT', 'gatewayorderid': 1672848002052712, 'quantity': '54.751', 'price': '16846.5', 'stopprice': '0', 'ordertype': '', 'side': 'SELL', 'status': 'FILLED', 'positionside': 'SHORT', 'createtime': 1672848001574, 'updatetime': 1672848002052, 'tradetype': 'usdt', 'selfid': 41473, 'filltrades': [TradeType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'tradeid': 1672848002052, 'clientorderid': '41473F1672848001944I0L59', 'price': '16846.5', 'quantity': '54.751', 'commission': '922.3627215', 'commissionasset': 'USDT', 'tradetime': 1672848002052, 'tradetype': 'usdt', 'gatetype': 'simulator', 'handletime': 1672848002052}], 'gatetype': 'simulator', 'handletime': 0}
127.0.0.1 - - [05/Jan/2023 00:00:02] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=5816 

self.closeSec=1672848599, self.tradeDate='20230105', self.openTime='000000', self.closeTime='000959', self.symbol='BTCUSDT', self.open='16846.5', self.close='16844.7'
2023-01-05 00:10:01,504:INFO:modifiedmom:main.py:144:handleKline:185213: self.closeSec=1672848599, self.tradeDate='20230105', self.openTime='000000', self.closeTime='000959',self.symbol='BTCUSDT',self.open='16846.5', self.close='16844.7'
127.0.0.1 - - [05/Jan/2023 00:10:01] "POST / HTTP/1.1" 200 -
2023-01-05 00:10:01,511:INFO:modifiedmom:main.py:145:handleKline:185213: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
572  20230104   232000    232959  1672846199  16801.8  16812.7  0.000649
573  20230104   233000    233959  1672846799  16812.7    16813  0.000018
574  20230104   234000    234959  1672847399    16813  16837.6  0.001463
575  20230104   235000    235959  1672847999  16837.7  16846.6  0.000535
576  20230105   000000    000959  1672848599  16846.5  16844.7 -0.000113
2023-01-05 00:10:01,512:INFO:modifiedmom:main.py:146:handleKline:185213: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False}


## /root/FIL/strategy/pyemd/log.txt ----- -----

2023-01-04 23:50:00,571:INFO:pyemd2:main.py:127:handleKline:185189: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}
127.0.0.1 - - [05/Jan/2023 00:00:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=5816 

self.closeSec=1672847999, self.tradeDate='20230104', self.openTime='235000', self.closeTime='235959', self.symbol='BTCUSDT', self.open='16837.7', self.close='16846.6'
2023-01-05 00:00:01,136:INFO:pyemd2:main.py:125:handleKline:185189: self.closeSec=1672847999, self.tradeDate='20230104', self.openTime='235000', self.closeTime='235959',self.symbol='BTCUSDT',self.open='16837.7', self.close='16846.6'
2023-01-05 00:00:01,201:INFO:pyemd2:main.py:126:handleKline:185189: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17419  20230104   231000    231959  1672845599  16778.1  16801.8
17420  20230104   232000    232959  1672846199  16801.8  16812.7
17421  20230104   233000    233959  1672846799  16812.7    16813
17422  20230104   234000    234959  1672847399    16813  16837.6
17423  20230104   235000    235959  1672847999  16837.7  16846.6
2023-01-05 00:00:01,201:INFO:pyemd2:main.py:127:handleKline:185189: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}
2023-01-05 00:00:01,459:INFO:pyemd2:main.py:190:insertFactor:185189: curDateTime:1050000, name:pyemd2, symbol:BTCUSDT, tradeDate:20230104, closeTime:235959, close:16846.6, total:939357.0753385, pct_pre:0.01055025775515972, thd:-0.8924904450946792, side:sell 

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=5817 

self.closeSec=1672848599, self.tradeDate='20230105', self.openTime='000000', self.closeTime='000959', self.symbol='BTCUSDT', self.open='16846.5', self.close='16844.7'
127.0.0.1 - - [05/Jan/2023 00:10:01] "POST / HTTP/1.1" 200 -
2023-01-05 00:10:01,514:INFO:pyemd2:main.py:125:handleKline:185189: self.closeSec=1672848599, self.tradeDate='20230105', self.openTime='000000', self.closeTime='000959',self.symbol='BTCUSDT',self.open='16846.5', self.close='16844.7'
2023-01-05 00:10:01,535:INFO:pyemd2:main.py:126:handleKline:185189: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17420  20230104   232000    232959  1672846199  16801.8  16812.7
17421  20230104   233000    233959  1672846799  16812.7    16813
17422  20230104   234000    234959  1672847399    16813  16837.6
17423  20230104   235000    235959  1672847999  16837.7  16846.6
17424  20230105   000000    000959  1672848599  16846.5  16844.7
2023-01-05 00:10:01,535:INFO:pyemd2:main.py:127:handleKline:185189: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}


## /root/FIL/strategy/similarity/log.txt ----- -----

2023-01-05 00:00:01,204:INFO:testStrategy:main.py:102:handleKline:185174: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12235  20230104   231000    231959  1672845599  16778.1  16801.8
12236  20230104   232000    232959  1672846199  16801.8  16812.7
12237  20230104   233000    233959  1672846799  16812.7    16813
12238  20230104   234000    234959  1672847399    16813  16837.6
12239  20230104   235000    235959  1672847999  16837.7  16846.6
2023-01-05 00:00:01,204:INFO:testStrategy:main.py:103:handleKline:185174: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': True, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}
closeSell: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '75.066', 'enterprice': '16670.3', 'countrevence': '0', 'unrealprofit': '-13288.92151078674', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '16847.32983389', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
2023-01-05 00:00:01,905:INFO:testStrategy:main.py:253:closeSell:185174: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False, 'isCorr': False}
2023-01-05 00:00:01,908:INFO:testStrategy:main.py:254:closeSell:185174: ret = self.client.insertMarketUOrder("simulator",  BTCUSDT, 75.066, buy ), ret=InsertOrderReturn{'result': 'success', 'clientorderid': '41472F1672848001902I0L2'}
2023-01-05 00:00:01,953:INFO:testStrategy:main.py:172:insertFactor:185174: curDateTime:1050000, name:testStrategy, symbol:BTCUSDT, tradeDate:20230104, closeTime:235959, close:16846.6, total:1250121.3670602, corrDate:20221128, corrVal:0.8438774439929858, side:buy 
127.0.0.1 - - [05/Jan/2023 00:00:02] "POST / HTTP/1.1" 200 -
2023-01-05 00:00:02,074:INFO:testStrategy:main.py:305:handleOrderNew:185174: handleOrderNew: data=OrderType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'clientorderid': '41472F1672848001902I0L2', 'symbol': 'BTCUSDT', 'gatewayorderid': 1672848002007251, 'quantity': '75.066', 'price': '16846.6', 'stopprice': '0', 'ordertype': '', 'side': 'BUY', 'status': 'FILLED', 'positionside': 'LONG', 'createtime': 1672848001424, 'updatetime': 1672848002007, 'tradetype': 'usdt', 'selfid': 41472, 'filltrades': [TradeType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'tradeid': 1672848002007, 'clientorderid': '41472F1672848001902I0L2', 'price': '16846.6', 'quantity': '75.066', 'commission': '1264.6068756', 'commissionasset': 'USDT', 'tradetime': 1672848002007, 'tradetype': 'usdt', 'gatetype': 'simulator', 'handletime': 1672848002007}], 'gatetype': 'simulator', 'handletime': 0}
127.0.0.1 - - [05/Jan/2023 00:00:02] "POST / HTTP/1.1" 200 -
2023-01-05 00:00:02,414:INFO:testStrategy:main.py:308:handleOrderFilled:185174: handleOrderFilled: data=OrderType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'clientorderid': '41472F1672848001902I0L2', 'symbol': 'BTCUSDT', 'gatewayorderid': 1672848002007251, 'quantity': '75.066', 'price': '16846.6', 'stopprice': '0', 'ordertype': '', 'side': 'BUY', 'status': 'FILLED', 'positionside': 'LONG', 'createtime': 1672848001424, 'updatetime': 1672848002007, 'tradetype': 'usdt', 'selfid': 41472, 'filltrades': [TradeType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'tradeid': 1672848002007, 'clientorderid': '41472F1672848001902I0L2', 'price': '16846.6', 'quantity': '75.066', 'commission': '1264.6068756', 'commissionasset': 'USDT', 'tradetime': 1672848002007, 'tradetype': 'usdt', 'gatetype': 'simulator', 'handletime': 1672848002007}], 'gatetype': 'simulator', 'handletime': 0}

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=5817 

self.closeSec=1672848599, self.tradeDate='20230105', self.openTime='000000', self.closeTime='000959', self.symbol='BTCUSDT', self.open='16846.5', self.close='16844.7'
2023-01-05 00:10:01,522:INFO:testStrategy:main.py:101:handleKline:185174: self.closeSec=1672848599, self.tradeDate='20230105', self.openTime='000000', self.closeTime='000959',self.symbol='BTCUSDT',self.open='16846.5', self.close='16844.7'
127.0.0.1 - - [05/Jan/2023 00:10:01] "POST / HTTP/1.1" 200 -
2023-01-05 00:10:01,533:INFO:testStrategy:main.py:102:handleKline:185174: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12236  20230104   232000    232959  1672846199  16801.8  16812.7
12237  20230104   233000    233959  1672846799  16812.7    16813
12238  20230104   234000    234959  1672847399    16813  16837.6
12239  20230104   235000    235959  1672847999  16837.7  16846.6
12240  20230105   000000    000959  1672848599  16846.5  16844.7
2023-01-05 00:10:01,533:INFO:testStrategy:main.py:103:handleKline:185174: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False, 'isCorr': False}


## /root/FIL/strategy/sr_min/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=0, self.total=1000000.0, self.flagDict['side']='', self.tradeCount=0, self.count=7064
self.closeSec=1672848599, self.tradeDate='20230105', self.openTime='000500', self.closeTime='000959', self.symbol='BTCUSDT', self.open=16836.3, self.close=16844.7, self.high=16845.6, self.low=16824.3, self.vol=1417.718, self.amt=23869757.4666 
127.0.0.1 - - [05/Jan/2023 00:10:01] "POST / HTTP/1.1" 200 -
2023-01-05 00:10:01,483:INFO:sr_min:main.py:172:handleKline:449472: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5757  20230104   234500    234959  ...         0.0        0.0       0
5758  20230104   235000    235459  ...         0.0        0.0       0
5759  20230104   235500    235959  ...         0.0        0.0       0
5760  20230105   000000    000459  ...         0.0        0.0       0
5761  20230105   000500    000959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-01-05 00:10:01,483:INFO:sr_min:main.py:175:handleKline:449472: self.closeSec=1672848599, self.tradeDate='20230105', self.openTime='000500', self.closeTime='000959',self.symbol='BTCUSDT',self.open=16836.3, self.close=16844.7, self.high=16845.6, self.low=16824.3, self.vol=1417.718, self.amt=23869757.4666, ukdf['pct'].iloc[-1]=0.000487 , ukdf['amount'].iloc[-1]=23869757.4666, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5761, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': []}
type(curSign)=<class 'int'>, curSign=0, self.sign=0
--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=0, self.total=1000000.0, self.flagDict['side']='', self.tradeCount=0, self.count=7065
self.closeSec=1672848899, self.tradeDate='20230105', self.openTime='001000', self.closeTime='001459', self.symbol='BTCUSDT', self.open=16844.6, self.close=16874.0, self.high=16874.0, self.low=16844.6, self.vol=3192.187, self.amt=53820772.3227 
127.0.0.1 - - [05/Jan/2023 00:15:00] "POST / HTTP/1.1" 200 -
2023-01-05 00:15:00,585:INFO:sr_min:main.py:172:handleKline:449472: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5758  20230104   235000    235459  ...         0.0        0.0       0
5759  20230104   235500    235959  ...         0.0        0.0       0
5760  20230105   000000    000459  ...         0.0        0.0       0
5761  20230105   000500    000959  ...         0.0        0.0       0
5762  20230105   001000    001459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-01-05 00:15:00,586:INFO:sr_min:main.py:175:handleKline:449472: self.closeSec=1672848899, self.tradeDate='20230105', self.openTime='001000', self.closeTime='001459',self.symbol='BTCUSDT',self.open=16844.6, self.close=16874.0, self.high=16874.0, self.low=16844.6, self.vol=3192.187, self.amt=53820772.3227, ukdf['pct'].iloc[-1]=0.001739 , ukdf['amount'].iloc[-1]=53820772.3227, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5762, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': []}
type(curSign)=<class 'int'>, curSign=0, self.sign=0


## /root/FIL/strategy/s_rsrs/log.txt ----- -----

723  20230104   120000    155959  1672819199  ...    723  0.877228  2.794820     1.0
724  20230104   160000    195959  1672833599  ...    724  0.874170  2.639039     1.0

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '52.77', 'enterprice': '16723.1', 'countrevence': '0', 'unrealprofit': '5535.70149495', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '16828.002435', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=1, self.sign=1
127.0.0.1 - - [05/Jan/2023 00:00:01] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='s_rsrs', self.symbol='BTCUSDT', interval='4h', intervalSec=14400, wid=25, thd=0.6, self.sign=1, self.total=881595.509013, self.flagDict['side']='buy', self.tradeCount=10, self.count=242
self.closeSec=1672847999, self.tradeDate='20230104', self.openTime='200000', self.closeTime='235959', self.symbol='BTCUSDT', self.open=16826.7, self.close=16846.6, self.high=16852.1, self.low=16759.3, self.vol=60470.868, self.amt=1016581101.7313 
2023-01-05 00:00:01,035:INFO:s_rsrs:main.py:141:handleKline:185271: self.closeSec=1672847999, self.tradeDate='20230104', self.openTime='200000', self.closeTime='235959',self.symbol='BTCUSDT',self.open=16826.7, self.close=16846.6, self.high=16852.1, self.low=16759.3, self.vol=60470.868, self.amt=1016581101.7313 
2023-01-05 00:00:01,177:INFO:s_rsrs:main.py:142:handleKline:185271: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime  ...        vol           amt       pct
721  20230104   040000    075959  ...  20681.239  3.445698e+08  0.001773
722  20230104   080000    115959  ...  70080.094  1.175072e+09  0.011322
723  20230104   120000    155959  ...  44883.639  7.567214e+08  0.000392
724  20230104   160000    195959  ...  34681.883  5.844936e+08 -0.002117
725  20230104   200000    235959  ...  60470.868  1.016581e+09  0.001177

[5 rows x 11 columns]
2023-01-05 00:00:03,010:INFO:s_rsrs:main.py:151:handleKline:185271: df_s.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec  ...  index      beta    zscore  signal
721  20230104   040000    075959  1672790399  ...    721  0.770401  2.618052     1.0
722  20230104   080000    115959  1672804799  ...    722  0.914817  3.093077     1.0
723  20230104   120000    155959  1672819199  ...    723  0.877228  2.794820     1.0
724  20230104   160000    195959  1672833599  ...    724  0.874170  2.639039     1.0
725  20230104   200000    235959  1672847999  ...    725  0.864275  2.479193     1.0

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '52.77', 'enterprice': '16723.1', 'countrevence': '0', 'unrealprofit': '6561.3866630955', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '16847.43933415', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=1, self.sign=1


