# 20230202 00:35:45

## /root/FIL/strategy/amihud/log.txt ----- -----

127.0.0.1 - - [02/Feb/2023 00:30:00] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=993672.4896432, self.flagDict['side']='sell', self.tradeCount=2, self.count=19134
self.closeSec=1675268999, self.tradeDate='20230202', self.openTime='002500', self.closeTime='002959', self.symbol='BTCUSDT', self.open=23030.4, self.close=23014.1, self.high=23033.8, self.low=23003.2, self.vol=812.958, self.amt=18713589.8462 
2023-02-02 00:30:00,972:INFO:amihud:main.py:172:handleKline:200676: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5761  20230202   000500    000959  ...         0.0        0.0       0
5762  20230202   001000    001459  ...         0.0        0.0       0
5763  20230202   001500    001959  ...         0.0        0.0       0
5764  20230202   002000    002459  ...         0.0        0.0       0
5765  20230202   002500    002959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-02-02 00:30:00,978:INFO:amihud:main.py:175:handleKline:200676: self.closeSec=1675268999, self.tradeDate='20230202', self.openTime='002500', self.closeTime='002959',self.symbol='BTCUSDT',self.open=23030.4, self.close=23014.1, self.high=23033.8, self.low=23003.2, self.vol=812.958, self.amt=18713589.8462, ukdf['pct'].iloc[-1]=-0.000712 , ukdf['amount'].iloc[-1]=18713589.8462, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5765, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '60.176', 'enterprice': '16529.3', 'countrevence': '0', 'unrealprofit': '-390199.2368', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '23013.6', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1
127.0.0.1 - - [02/Feb/2023 00:35:00] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=993672.4896432, self.flagDict['side']='sell', self.tradeCount=2, self.count=19135
self.closeSec=1675269299, self.tradeDate='20230202', self.openTime='003000', self.closeTime='003459', self.symbol='BTCUSDT', self.open=23014.1, self.close=23007.3, self.high=23015.6, self.low=22996.0, self.vol=945.086, self.amt=21743369.9866 
2023-02-02 00:35:00,531:INFO:amihud:main.py:172:handleKline:200676: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5762  20230202   001000    001459  ...         0.0        0.0       0
5763  20230202   001500    001959  ...         0.0        0.0       0
5764  20230202   002000    002459  ...         0.0        0.0       0
5765  20230202   002500    002959  ...         0.0        0.0       0
5766  20230202   003000    003459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-02-02 00:35:00,534:INFO:amihud:main.py:175:handleKline:200676: self.closeSec=1675269299, self.tradeDate='20230202', self.openTime='003000', self.closeTime='003459',self.symbol='BTCUSDT',self.open=23014.1, self.close=23007.3, self.high=23015.6, self.low=22996.0, self.vol=945.086, self.amt=21743369.9866, ukdf['pct'].iloc[-1]=-0.000295 , ukdf['amount'].iloc[-1]=21743369.9866, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5766, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '60.176', 'enterprice': '16529.3', 'countrevence': '0', 'unrealprofit': '-389829.40588693744', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '23007.45417919', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1


## /root/FIL/strategy/factorcheck/log.txt ----- -----

1444  20230202   002000    002459  1675268699  ...  23014.0  0.000687   1444    4
1445  20230202   002500    002959  1675268999  ...  23003.2 -0.000712   1445    5

[5 rows x 11 columns]
2023-02-02 00:30:00,953:INFO:factorcheck2:main.py:128:handleKline:185239: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}
2023-02-02 00:30:00,994:INFO:factorcheck2:main.py:145:handleKline:185239: df_panel.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec  ...       pct  index  idx    factor
197  20230201   222500    222959  1675261799  ... -0.001902   1709    5  0.455535
198  20230201   225500    225959  1675263599  ... -0.000662   1715    5  0.454184
199  20230201   232500    232959  1675265399  ...  0.000504   1721    5  0.456664
200  20230201   235500    235959  1675267199  ... -0.000396   1727    5  0.463662
201  20230202   002500    002959  1675268999  ... -0.000712   1445    5  0.467829

[5 rows x 12 columns]

--handleKline--: 127.0.0.1 - - [02/Feb/2023 00:35:00] "POST / HTTP/1.1" 200 -
 version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=3, self.factor=0.46782874510395217, self.count=19701 

self.closeSec=1675269299, self.tradeDate='20230202', self.openTime='003000', self.closeTime='003459', self.symbol='BTCUSDT', self.open=23014.1, self.close=23007.3, self.high=23015.6, self.low=22996.0 
2023-02-02 00:35:00,437:INFO:factorcheck2:main.py:126:handleKline:185239: self.closeSec=1675269299, self.tradeDate='20230202', self.openTime='003000', self.closeTime='003459',self.symbol='BTCUSDT',self.open=23014.1, self.close=23007.3, self.high=23015.6, self.low=22996.0   
2023-02-02 00:35:00,507:INFO:factorcheck2:main.py:127:handleKline:185239: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1442  20230202   001000    001459  1675268099  ...  22985.3  0.001027   1442    2
1443  20230202   001500    001959  1675268399  ...  23007.9  0.000026   1443    3
1444  20230202   002000    002459  1675268699  ...  23014.0  0.000687   1444    4
1445  20230202   002500    002959  1675268999  ...  23003.2 -0.000712   1445    5
1446  20230202   003000    003459  1675269299  ...  22996.0 -0.000295   1446    0

[5 rows x 11 columns]
2023-02-02 00:35:00,507:INFO:factorcheck2:main.py:128:handleKline:185239: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}


## /root/FIL/strategy/logic/log.txt ----- -----

2023-02-02 00:30:32,622:DEBUG:logic:main.py:463:getModel:885513: df_s.iloc[-5:,:] :
          date closeTime     open  ...    alpha58   alpha67   alpha72
5755  20230201    215959  23100.1  ...  50.000000  0.502084  0.482080
5756  20230201    222959  23082.5  ...  50.416667  0.503088  0.480791
5757  20230201    225959  23088.3  ...  50.416667  0.505561  0.478295
5758  20230201    232959  23098.1  ...  50.000000  0.492113  0.482923
5759  20230201    235959  23041.8  ...  50.000000  0.476516  0.495633

[5 rows x 33 columns]
0.5380333951762524
acc is : 0.5380333951762524
2023-02-02 00:30:32,777:INFO:logic:main.py:468:getModel:885513: df_pred.iloc[-5:,:] :
     pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
534     1  0.491462  0.508538       1  ...  0.917990   1.0    0.0  1.013508
535     1  0.495904  0.504096       1  ...  0.918395   1.0    0.0  1.013956
536     1  0.496384  0.503616       0  ...  0.916212   1.0    0.0  1.011546
537     1  0.484094  0.515906       0  ...  0.913580   1.0    0.0  1.008640
538     1  0.473732  0.526268       1  ...  0.915107   1.0    0.0  1.010325

[5 rows x 10 columns]
2023-02-02 00:30:32,805:INFO:logic:main.py:478:getModel:885513: df_panel.iloc[-5:,:] :
    pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
45     1  0.490989  0.509011       1  ...  0.915189   1.0    0.0  1.020727
46     1  0.495269  0.504731       1  ...  0.915594   1.0    0.0  1.021178
47     1  0.495053  0.504947       0  ...  0.913417   1.0    0.0  1.018062
48     1  0.483374  0.516626       0  ...  0.910793   1.0    0.0  1.015204
49     1  0.473732  0.526268       1  ...  0.915107   1.0    0.0  1.010325

[5 rows x 10 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '30.955', 'enterprice': '23100.3', 'countrevence': '0', 'unrealprofit': '-3070.736', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '23001.1', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}


## /root/FIL/strategy/modifiedmom/log.txt ----- -----

576  20230202   000000    000959  1675267799  22975.6  22990.5  0.000644
2023-02-02 00:10:01,578:INFO:modifiedmom:main.py:146:handleKline:185213: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=9849 

self.closeSec=1675268399, self.tradeDate='20230202', self.openTime='001000', self.closeTime='001959', self.symbol='BTCUSDT', self.open='22990.5', self.close='23014.7'
2023-02-02 00:20:00,529:INFO:modifiedmom:main.py:144:handleKline:185213: self.closeSec=1675268399, self.tradeDate='20230202', self.openTime='001000', self.closeTime='001959',self.symbol='BTCUSDT',self.open='22990.5', self.close='23014.7'
127.0.0.1 - - [02/Feb/2023 00:20:00] "POST / HTTP/1.1" 200 -
2023-02-02 00:20:00,561:INFO:modifiedmom:main.py:145:handleKline:185213: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
573  20230201   233000    233959  1675265999  23041.8    23030 -0.000516
574  20230201   234000    234959  1675266599    23030  22975.2 -0.002380
575  20230201   235000    235959  1675267199  22979.9  22975.7  0.000022
576  20230202   000000    000959  1675267799  22975.6  22990.5  0.000644
577  20230202   001000    001959  1675268399  22990.5  23014.7  0.001053
2023-02-02 00:20:00,561:INFO:modifiedmom:main.py:146:handleKline:185213: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False}
127.0.0.1 - - [02/Feb/2023 00:30:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=9850 

self.closeSec=1675268999, self.tradeDate='20230202', self.openTime='002000', self.closeTime='002959', self.symbol='BTCUSDT', self.open='23014.7', self.close='23014.1'
2023-02-02 00:30:01,538:INFO:modifiedmom:main.py:144:handleKline:185213: self.closeSec=1675268999, self.tradeDate='20230202', self.openTime='002000', self.closeTime='002959',self.symbol='BTCUSDT',self.open='23014.7', self.close='23014.1'
2023-02-02 00:30:01,603:INFO:modifiedmom:main.py:145:handleKline:185213: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
574  20230201   234000    234959  1675266599    23030  22975.2 -0.002380
575  20230201   235000    235959  1675267199  22979.9  22975.7  0.000022
576  20230202   000000    000959  1675267799  22975.6  22990.5  0.000644
577  20230202   001000    001959  1675268399  22990.5  23014.7  0.001053
578  20230202   002000    002959  1675268999  23014.7  23014.1 -0.000026
2023-02-02 00:30:01,603:INFO:modifiedmom:main.py:146:handleKline:185213: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False}


## /root/FIL/strategy/pyemd/log.txt ----- -----

17424  20230202   000000    000959  1675267799  22975.6  22990.5
2023-02-02 00:10:01,577:INFO:pyemd2:main.py:127:handleKline:185189: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}
127.0.0.1 - - [02/Feb/2023 00:20:00] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=9850 

self.closeSec=1675268399, self.tradeDate='20230202', self.openTime='001000', self.closeTime='001959', self.symbol='BTCUSDT', self.open='22990.5', self.close='23014.7'
2023-02-02 00:20:00,551:INFO:pyemd2:main.py:125:handleKline:185189: self.closeSec=1675268399, self.tradeDate='20230202', self.openTime='001000', self.closeTime='001959',self.symbol='BTCUSDT',self.open='22990.5', self.close='23014.7'
2023-02-02 00:20:00,572:INFO:pyemd2:main.py:126:handleKline:185189: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17421  20230201   233000    233959  1675265999  23041.8    23030
17422  20230201   234000    234959  1675266599    23030  22975.2
17423  20230201   235000    235959  1675267199  22979.9  22975.7
17424  20230202   000000    000959  1675267799  22975.6  22990.5
17425  20230202   001000    001959  1675268399  22990.5  23014.7
2023-02-02 00:20:00,591:INFO:pyemd2:main.py:127:handleKline:185189: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=9851 

self.closeSec=1675268999, self.tradeDate='20230202', self.openTime='002000', self.closeTime='002959', self.symbol='BTCUSDT', self.open='23014.7', self.close='23014.1'
127.0.0.1 - - [02/Feb/2023 00:30:01] "POST / HTTP/1.1" 200 -
2023-02-02 00:30:01,570:INFO:pyemd2:main.py:125:handleKline:185189: self.closeSec=1675268999, self.tradeDate='20230202', self.openTime='002000', self.closeTime='002959',self.symbol='BTCUSDT',self.open='23014.7', self.close='23014.1'
2023-02-02 00:30:01,611:INFO:pyemd2:main.py:126:handleKline:185189: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17422  20230201   234000    234959  1675266599    23030  22975.2
17423  20230201   235000    235959  1675267199  22979.9  22975.7
17424  20230202   000000    000959  1675267799  22975.6  22990.5
17425  20230202   001000    001959  1675268399  22990.5  23014.7
17426  20230202   002000    002959  1675268999  23014.7  23014.1
2023-02-02 00:30:01,612:INFO:pyemd2:main.py:127:handleKline:185189: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}


## /root/FIL/strategy/similarity/log.txt ----- -----

12240  20230202   000000    000959  1675267799  22975.6  22990.5
2023-02-02 00:10:01,564:INFO:testStrategy:main.py:103:handleKline:185174: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False, 'isCorr': False}
127.0.0.1 - - [02/Feb/2023 00:20:00] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=9850 

self.closeSec=1675268399, self.tradeDate='20230202', self.openTime='001000', self.closeTime='001959', self.symbol='BTCUSDT', self.open='22990.5', self.close='23014.7'
2023-02-02 00:20:00,537:INFO:testStrategy:main.py:101:handleKline:185174: self.closeSec=1675268399, self.tradeDate='20230202', self.openTime='001000', self.closeTime='001959',self.symbol='BTCUSDT',self.open='22990.5', self.close='23014.7'
2023-02-02 00:20:00,589:INFO:testStrategy:main.py:102:handleKline:185174: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12237  20230201   233000    233959  1675265999  23041.8    23030
12238  20230201   234000    234959  1675266599    23030  22975.2
12239  20230201   235000    235959  1675267199  22979.9  22975.7
12240  20230202   000000    000959  1675267799  22975.6  22990.5
12241  20230202   001000    001959  1675268399  22990.5  23014.7
2023-02-02 00:20:00,589:INFO:testStrategy:main.py:103:handleKline:185174: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False, 'isCorr': False}
127.0.0.1 - - [02/Feb/2023 00:30:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=9851 

self.closeSec=1675268999, self.tradeDate='20230202', self.openTime='002000', self.closeTime='002959', self.symbol='BTCUSDT', self.open='23014.7', self.close='23014.1'
2023-02-02 00:30:01,514:INFO:testStrategy:main.py:101:handleKline:185174: self.closeSec=1675268999, self.tradeDate='20230202', self.openTime='002000', self.closeTime='002959',self.symbol='BTCUSDT',self.open='23014.7', self.close='23014.1'
2023-02-02 00:30:01,534:INFO:testStrategy:main.py:102:handleKline:185174: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12238  20230201   234000    234959  1675266599    23030  22975.2
12239  20230201   235000    235959  1675267199  22979.9  22975.7
12240  20230202   000000    000959  1675267799  22975.6  22990.5
12241  20230202   001000    001959  1675268399  22990.5  23014.7
12242  20230202   002000    002959  1675268999  23014.7  23014.1
2023-02-02 00:30:01,534:INFO:testStrategy:main.py:103:handleKline:185174: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False, 'isCorr': False}


## /root/FIL/strategy/sr_min/log.txt ----- -----

127.0.0.1 - - [02/Feb/2023 00:30:00] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=0, self.total=1000000.0, self.flagDict['side']='', self.tradeCount=0, self.count=15132
self.closeSec=1675268999, self.tradeDate='20230202', self.openTime='002500', self.closeTime='002959', self.symbol='BTCUSDT', self.open=23030.4, self.close=23014.1, self.high=23033.8, self.low=23003.2, self.vol=812.958, self.amt=18713589.8462 
2023-02-02 00:30:01,057:INFO:sr_min:main.py:172:handleKline:449472: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5761  20230202   000500    000959  ...         0.0        0.0       0
5762  20230202   001000    001459  ...         0.0        0.0       0
5763  20230202   001500    001959  ...         0.0        0.0       0
5764  20230202   002000    002459  ...         0.0        0.0       0
5765  20230202   002500    002959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-02-02 00:30:01,059:INFO:sr_min:main.py:175:handleKline:449472: self.closeSec=1675268999, self.tradeDate='20230202', self.openTime='002500', self.closeTime='002959',self.symbol='BTCUSDT',self.open=23030.4, self.close=23014.1, self.high=23033.8, self.low=23003.2, self.vol=812.958, self.amt=18713589.8462, ukdf['pct'].iloc[-1]=-0.000712 , ukdf['amount'].iloc[-1]=18713589.8462, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5765, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': []}
type(curSign)=<class 'int'>, curSign=0, self.sign=0
127.0.0.1 - - [02/Feb/2023 00:35:00] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=0, self.total=1000000.0, self.flagDict['side']='', self.tradeCount=0, self.count=15133
self.closeSec=1675269299, self.tradeDate='20230202', self.openTime='003000', self.closeTime='003459', self.symbol='BTCUSDT', self.open=23014.1, self.close=23007.3, self.high=23015.6, self.low=22996.0, self.vol=945.086, self.amt=21743369.9866 
2023-02-02 00:35:00,506:INFO:sr_min:main.py:172:handleKline:449472: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5762  20230202   001000    001459  ...         0.0        0.0       0
5763  20230202   001500    001959  ...         0.0        0.0       0
5764  20230202   002000    002459  ...         0.0        0.0       0
5765  20230202   002500    002959  ...         0.0        0.0       0
5766  20230202   003000    003459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-02-02 00:35:00,513:INFO:sr_min:main.py:175:handleKline:449472: self.closeSec=1675269299, self.tradeDate='20230202', self.openTime='003000', self.closeTime='003459',self.symbol='BTCUSDT',self.open=23014.1, self.close=23007.3, self.high=23015.6, self.low=22996.0, self.vol=945.086, self.amt=21743369.9866, ukdf['pct'].iloc[-1]=-0.000295 , ukdf['amount'].iloc[-1]=21743369.9866, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5766, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': []}
type(curSign)=<class 'int'>, curSign=0, self.sign=0


## /root/FIL/strategy/s_rsrs/log.txt ----- -----

723  20230201   120000    155959  1675238399  ...    723  0.643037  0.550769     NaN
724  20230201   160000    195959  1675252799  ...    724  0.646420  0.560265     NaN

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '38.964', 'enterprice': '23700.1', 'countrevence': '0', 'unrealprofit': '-24344.7072', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '23075.3', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-9223372036854775808, self.sign=1
--handleKline--:  version='2.0.0', self.name='s_rsrs', self.symbol='BTCUSDT', interval='4h', intervalSec=14400, wid=25, thd=0.6, self.sign=1, self.total=922527.2457035999, self.flagDict['side']='buy', self.tradeCount=16, self.count=410
self.closeSec=1675267199, self.tradeDate='20230201', self.openTime='200000', self.closeTime='235959', self.symbol='BTCUSDT', self.open=23076.1, self.close=22975.7, self.high=23143.6, self.low=22935.3, self.vol=71259.336, self.amt=1643445431.8033 
127.0.0.1 - - [02/Feb/2023 00:00:02] "POST / HTTP/1.1" 200 -
2023-02-02 00:00:02,299:INFO:s_rsrs:main.py:141:handleKline:185271: self.closeSec=1675267199, self.tradeDate='20230201', self.openTime='200000', self.closeTime='235959',self.symbol='BTCUSDT',self.open=23076.1, self.close=22975.7, self.high=23143.6, self.low=22935.3, self.vol=71259.336, self.amt=1643445431.8033 
2023-02-02 00:00:02,351:INFO:s_rsrs:main.py:142:handleKline:185271: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime  ...         vol           amt       pct
721  20230201   040000    075959  ...  105553.545  2.432205e+09 -0.001520
722  20230201   080000    115959  ...   41016.975  9.469843e+08  0.000342
723  20230201   120000    155959  ...   33068.509  7.638194e+08 -0.002434
724  20230201   160000    195959  ...   50557.370  1.163133e+09  0.000221
725  20230201   200000    235959  ...   71259.336  1.643445e+09 -0.004351

[5 rows x 11 columns]
2023-02-02 00:00:04,365:INFO:s_rsrs:main.py:151:handleKline:185271: df_s.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec  ...  index      beta    zscore  signal
721  20230201   040000    075959  1675209599  ...    721  0.611552  0.441319     NaN
722  20230201   080000    115959  1675223999  ...    722  0.640645  0.537671     NaN
723  20230201   120000    155959  1675238399  ...    723  0.643037  0.550769     NaN
724  20230201   160000    195959  1675252799  ...    724  0.646420  0.560265     NaN
725  20230201   200000    235959  1675267199  ...    725  0.637503  0.529206     NaN

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '38.964', 'enterprice': '23700.1', 'countrevence': '0', 'unrealprofit': '-28291.7604', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '22974', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-9223372036854775808, self.sign=1


