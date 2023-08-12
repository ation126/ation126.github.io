# 20230813 00:26:01

## /root/FIL/strategy/amihud/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=373746.4768026, self.flagDict['side']='sell', self.tradeCount=2, self.count=26080
self.closeSec=1691857199, self.tradeDate='20230813', self.openTime='001500', self.closeTime='001959', self.symbol='BTCUSDT', self.open=29448.4, self.close=29455.7, self.high=29455.7, self.low=29448.3, self.vol=472.852, self.amt=13926164.04 
127.0.0.1 - - [13/Aug/2023 00:20:01] "POST / HTTP/1.1" 200 -
2023-08-13 00:20:06,388:INFO:amihud:main.py:172:handleKline:2219019: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5759  20230812   235500    235959  ...         0.0        0.0       0
5760  20230813   000000    000459  ...         0.0        0.0       0
5761  20230813   000500    000959  ...         0.0        0.0       0
5762  20230813   001000    001459  ...         0.0        0.0       0
5763  20230813   001500    001959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-08-13 00:20:06,408:INFO:amihud:main.py:175:handleKline:2219019: self.closeSec=1691857199, self.tradeDate='20230813', self.openTime='001500', self.closeTime='001959',self.symbol='BTCUSDT',self.open=29448.4, self.close=29455.7, self.high=29455.7, self.low=29448.3, self.vol=472.852, self.amt=13926164.04, ukdf['pct'].iloc[-1]=0.000248 , ukdf['amount'].iloc[-1]=13926164.04, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5763, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '13.926', 'enterprice': '26864.9', 'countrevence': '0', 'unrealprofit': '-36087.01942898184', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '29456.24133484', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1
127.0.0.1 - - [13/Aug/2023 00:25:00] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=373746.4768026, self.flagDict['side']='sell', self.tradeCount=2, self.count=26081
self.closeSec=1691857499, self.tradeDate='20230813', self.openTime='002000', self.closeTime='002459', self.symbol='BTCUSDT', self.open=29455.7, self.close=29455.8, self.high=29459.0, self.low=29453.7, self.vol=493.932, self.amt=14549600.471 
2023-08-13 00:25:00,769:INFO:amihud:main.py:172:handleKline:2219019: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5760  20230813   000000    000459  ...         0.0        0.0       0
5761  20230813   000500    000959  ...         0.0        0.0       0
5762  20230813   001000    001459  ...         0.0        0.0       0
5763  20230813   001500    001959  ...         0.0        0.0       0
5764  20230813   002000    002459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-08-13 00:25:00,769:INFO:amihud:main.py:175:handleKline:2219019: self.closeSec=1691857499, self.tradeDate='20230813', self.openTime='002000', self.closeTime='002459',self.symbol='BTCUSDT',self.open=29455.7, self.close=29455.8, self.high=29459.0, self.low=29453.7, self.vol=493.932, self.amt=14549600.471, ukdf['pct'].iloc[-1]=3e-06 , ukdf['amount'].iloc[-1]=14549600.471, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5764, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '13.926', 'enterprice': '26864.9', 'countrevence': '0', 'unrealprofit': '-36095.34898429812', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '29456.83946462', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1


## /root/FIL/strategy/factorcheck/log.txt ----- -----


self.closeSec=1691857199, self.tradeDate='20230813', self.openTime='001500', self.closeTime='001959', self.symbol='BTCUSDT', self.open=29448.4, self.close=29455.7, self.high=29455.7, self.low=29448.3 
127.0.0.1 - - [13/Aug/2023 00:20:01] "POST / HTTP/1.1" 200 -
2023-08-13 00:20:04,298:INFO:factorcheck2:main.py:126:handleKline:2218005: self.closeSec=1691857199, self.tradeDate='20230813', self.openTime='001500', self.closeTime='001959',self.symbol='BTCUSDT',self.open=29448.4, self.close=29455.7, self.high=29455.7, self.low=29448.3   
2023-08-13 00:20:05,318:INFO:factorcheck2:main.py:127:handleKline:2218005: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1439  20230812   235500    235959  1691855999  ...  29425.4  0.000017   1727    5
1440  20230813   000000    000459  1691856299  ...  29426.0  0.000377   1440    0
1441  20230813   000500    000959  1691856599  ...  29437.1  0.000037   1441    1
1442  20230813   001000    001459  1691856899  ...  29438.1  0.000346   1442    2
1443  20230813   001500    001959  1691857199  ...  29448.3  0.000248   1443    3

[5 rows x 11 columns]
2023-08-13 00:20:05,328:INFO:factorcheck2:main.py:128:handleKline:2218005: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': False, 'isOpen': True, 'isClose': False, 'isTrig': True}
127.0.0.1 - - [13/Aug/2023 00:25:00] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=6, self.factor=0.5520510166807242, self.count=26083 

self.closeSec=1691857499, self.tradeDate='20230813', self.openTime='002000', self.closeTime='002459', self.symbol='BTCUSDT', self.open=29455.7, self.close=29455.8, self.high=29459.0, self.low=29453.7 
2023-08-13 00:25:00,749:INFO:factorcheck2:main.py:126:handleKline:2218005: self.closeSec=1691857499, self.tradeDate='20230813', self.openTime='002000', self.closeTime='002459',self.symbol='BTCUSDT',self.open=29455.7, self.close=29455.8, self.high=29459.0, self.low=29453.7   
2023-08-13 00:25:00,772:INFO:factorcheck2:main.py:127:handleKline:2218005: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1440  20230813   000000    000459  1691856299  ...  29426.0  0.000377   1440    0
1441  20230813   000500    000959  1691856599  ...  29437.1  0.000037   1441    1
1442  20230813   001000    001459  1691856899  ...  29438.1  0.000346   1442    2
1443  20230813   001500    001959  1691857199  ...  29448.3  0.000248   1443    3
1444  20230813   002000    002459  1691857499  ...  29453.7  0.000003   1444    4

[5 rows x 11 columns]
2023-08-13 00:25:00,773:INFO:factorcheck2:main.py:128:handleKline:2218005: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': False, 'isOpen': True, 'isClose': False, 'isTrig': True}


## /root/FIL/strategy/logic/log.txt ----- -----

2023-08-13 00:00:17,906:DEBUG:logic:main.py:463:getModel:2218526: df_s.iloc[-5:,:] :
          date closeTime     open  ...    alpha58   alpha67   alpha72
5802  20230812    212959  29414.5  ...  49.583333  0.490308  0.398147
5803  20230812    215959  29411.6  ...  49.583333  0.482692  0.398923
5804  20230812    222959  29396.4  ...  50.000000  0.497572  0.386773
5805  20230812    225959  29424.8  ...  50.000000  0.504788  0.367497
5806  20230812    232959  29439.0  ...  50.416667  0.505045  0.350849

[5 rows x 33 columns]
0.5183823529411765
acc is : 0.5183823529411765
2023-08-13 00:00:17,975:INFO:logic:main.py:468:getModel:2218526: df_pred.iloc[-5:,:] :
     pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
539     0  0.502321  0.497679       0  ...  0.994037  -1.0    0.0  1.016431
540     0  0.500147  0.499853       1  ...  0.993077  -1.0    0.0  1.017413
541     0  0.511361  0.488639       1  ...  0.992601  -1.0    0.0  1.017900
542     0  0.510360  0.489640       1  ...  0.992584  -1.0    0.0  1.017918
543     0  0.507629  0.492371       0  ...  0.993036  -1.0    0.0  1.017454

[5 rows x 10 columns]
2023-08-13 00:00:17,988:INFO:logic:main.py:478:getModel:2218526: df_panel.iloc[-5:,:] :
    pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
45     0  0.502440  0.497560       0  ...  0.994037  -1.0    0.0  1.015862
46     0  0.500411  0.499589       1  ...  0.993077  -1.0    0.0  1.018156
47     0  0.511619  0.488381       1  ...  0.992601  -1.0    0.0  1.018644
48     0  0.510479  0.489521       1  ...  0.992584  -1.0    0.0  1.018414
49     0  0.507629  0.492371       0  ...  0.993036  -1.0    0.0  1.017454

[5 rows x 10 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '24.049', 'enterprice': '29479.7', 'countrevence': '0', 'unrealprofit': '1228.9039', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '29428.6', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}


## /root/FIL/strategy/modifiedmom/log.txt ----- -----

127.0.0.1 - - [13/Aug/2023 00:00:04] "POST / HTTP/1.1" 200 -
2023-08-13 00:00:04,167:INFO:modifiedmom:main.py:319:handleOrderFilled:2218259: handleOrderFilled: data=OrderType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'clientorderid': '42850F1691856003557I0L59', 'symbol': 'BTCUSDT', 'gatewayorderid': 1691856003977196, 'quantity': '24.56', 'price': '29426', 'stopprice': '0', 'ordertype': '', 'side': 'SELL', 'status': 'FILLED', 'positionside': 'SHORT', 'createtime': 1691856002616, 'updatetime': 1691856003977, 'tradetype': 'usdt', 'selfid': 42850, 'filltrades': [TradeType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'tradeid': 1691856003977, 'clientorderid': '42850F1691856003557I0L59', 'price': '29426', 'quantity': '24.56', 'commission': '722.70256', 'commissionasset': 'USDT', 'tradetime': 1691856003977, 'tradetype': 'usdt', 'gatetype': 'simulator', 'handletime': 1691856003977}], 'gatetype': 'simulator', 'handletime': 0}
127.0.0.1 - - [13/Aug/2023 00:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=13040 

self.closeSec=1691856599, self.tradeDate='20230813', self.openTime='000000', self.closeTime='000959', self.symbol='BTCUSDT', self.open='29426', self.close='29438.2'
2023-08-13 00:10:01,178:INFO:modifiedmom:main.py:144:handleKline:2218259: self.closeSec=1691856599, self.tradeDate='20230813', self.openTime='000000', self.closeTime='000959',self.symbol='BTCUSDT',self.open='29426', self.close='29438.2'
2023-08-13 00:10:01,189:INFO:modifiedmom:main.py:145:handleKline:2218259: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
572  20230812   232000    232959  1691854199    29439  29439.4  0.000017
573  20230812   233000    233959  1691854799  29439.5    29443  0.000122
574  20230812   234000    234959  1691855399  29443.1  29428.8 -0.000482
575  20230812   235000    235959  1691855999  29428.8    29426 -0.000095
576  20230813   000000    000959  1691856599    29426  29438.2  0.000415
2023-08-13 00:10:01,189:INFO:modifiedmom:main.py:146:handleKline:2218259: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=13041 

self.closeSec=1691857199, self.tradeDate='20230813', self.openTime='001000', self.closeTime='001959', self.symbol='BTCUSDT', self.open='29438.1', self.close='29455.7'
127.0.0.1 - - [13/Aug/2023 00:20:04] "POST / HTTP/1.1" 200 -
2023-08-13 00:20:06,567:INFO:modifiedmom:main.py:144:handleKline:2218259: self.closeSec=1691857199, self.tradeDate='20230813', self.openTime='001000', self.closeTime='001959',self.symbol='BTCUSDT',self.open='29438.1', self.close='29455.7'
2023-08-13 00:20:07,276:INFO:modifiedmom:main.py:145:handleKline:2218259: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
573  20230812   233000    233959  1691854799  29439.5    29443  0.000122
574  20230812   234000    234959  1691855399  29443.1  29428.8 -0.000482
575  20230812   235000    235959  1691855999  29428.8    29426 -0.000095
576  20230813   000000    000959  1691856599    29426  29438.2  0.000415
577  20230813   001000    001959  1691857199  29438.1  29455.7  0.000594
2023-08-13 00:20:07,278:INFO:modifiedmom:main.py:146:handleKline:2218259: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False}


## /root/FIL/strategy/percentile_regression_step2/log.txt ----- -----

127.0.0.1 - - [21/Feb/2023 09:30:01] "POST / HTTP/1.1" 200 -
2023-02-21 09:30:03,026:DEBUG:percentile_regression_step2:main.py:154:get_signal:1265985: df_id.iloc[-5:,:] :
                 daytime     hms    close  ...  pct_10  pct_20  factor
144  2023/02/21 07:00:00  070000  24795.1  ...     NaN     NaN       0
145  2023/02/21 07:30:00  073000  24849.9  ...     NaN     NaN       0
146  2023/02/21 08:00:00  080000  24819.0  ...     NaN     NaN       0
147  2023/02/21 08:30:00  083000  24860.9  ...     NaN     NaN       0
148  2023/02/21 09:00:00  090000  24831.0  ...     NaN     NaN       0

[5 rows x 10 columns]
127.0.0.1 - - [21/Feb/2023 10:00:02] "POST / HTTP/1.1" 200 -
2023-02-21 10:00:03,553:DEBUG:percentile_regression_step2:main.py:154:get_signal:1265985: df_id.iloc[-5:,:] :
                 daytime     hms    close  ...  pct_10  pct_20  factor
144  2023/02/21 07:30:00  073000  24849.9  ...     NaN     NaN       0
145  2023/02/21 08:00:00  080000  24819.0  ...     NaN     NaN       0
146  2023/02/21 08:30:00  083000  24860.9  ...     NaN     NaN       0
147  2023/02/21 09:00:00  090000  24831.0  ...     NaN     NaN       0
148  2023/02/21 09:30:00  093000  24870.0  ...     NaN     NaN       0

[5 rows x 10 columns]
127.0.0.1 - - [21/Feb/2023 10:30:01] "POST / HTTP/1.1" 200 -
2023-02-21 10:30:03,245:DEBUG:percentile_regression_step2:main.py:154:get_signal:1265985: df_id.iloc[-5:,:] :
                 daytime     hms    close  ...  pct_10  pct_20  factor
144  2023/02/21 08:00:00  080000  24819.0  ...     NaN     NaN       0
145  2023/02/21 08:30:00  083000  24860.9  ...     NaN     NaN       0
146  2023/02/21 09:00:00  090000  24831.0  ...     NaN     NaN       0
147  2023/02/21 09:30:00  093000  24870.0  ...     NaN     NaN       0
148  2023/02/21 10:00:00  100000  24936.1  ...     NaN     NaN       0

[5 rows x 10 columns]


## /root/FIL/strategy/pyemd/log.txt ----- -----

2023-08-13 00:00:02,084:INFO:pyemd2:main.py:127:handleKline:2217508: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}
2023-08-13 00:00:02,145:INFO:pyemd2:main.py:190:insertFactor:2217508: curDateTime:8130000, name:pyemd2, symbol:BTCUSDT, tradeDate:20230812, closeTime:235959, close:29426, total:977345.2184116, pct_pre:0.0005647833749549136, thd:-0.05578373175576434, side:sell 
127.0.0.1 - - [13/Aug/2023 00:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=13043 

self.closeSec=1691856599, self.tradeDate='20230813', self.openTime='000000', self.closeTime='000959', self.symbol='BTCUSDT', self.open='29426', self.close='29438.2'
2023-08-13 00:10:01,183:INFO:pyemd2:main.py:125:handleKline:2217508: self.closeSec=1691856599, self.tradeDate='20230813', self.openTime='000000', self.closeTime='000959',self.symbol='BTCUSDT',self.open='29426', self.close='29438.2'
2023-08-13 00:10:01,190:INFO:pyemd2:main.py:126:handleKline:2217508: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17420  20230812   232000    232959  1691854199    29439  29439.4
17421  20230812   233000    233959  1691854799  29439.5    29443
17422  20230812   234000    234959  1691855399  29443.1  29428.8
17423  20230812   235000    235959  1691855999  29428.8    29426
17424  20230813   000000    000959  1691856599    29426  29438.2
2023-08-13 00:10:01,190:INFO:pyemd2:main.py:127:handleKline:2217508: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=13044 

self.closeSec=1691857199, self.tradeDate='20230813', self.openTime='001000', self.closeTime='001959', self.symbol='BTCUSDT', self.open='29438.1', self.close='29455.7'
127.0.0.1 - - [13/Aug/2023 00:20:04] "POST / HTTP/1.1" 200 -
2023-08-13 00:20:08,408:INFO:pyemd2:main.py:125:handleKline:2217508: self.closeSec=1691857199, self.tradeDate='20230813', self.openTime='001000', self.closeTime='001959',self.symbol='BTCUSDT',self.open='29438.1', self.close='29455.7'
2023-08-13 00:20:08,512:INFO:pyemd2:main.py:126:handleKline:2217508: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17421  20230812   233000    233959  1691854799  29439.5    29443
17422  20230812   234000    234959  1691855399  29443.1  29428.8
17423  20230812   235000    235959  1691855999  29428.8    29426
17424  20230813   000000    000959  1691856599    29426  29438.2
17425  20230813   001000    001959  1691857199  29438.1  29455.7
2023-08-13 00:20:08,513:INFO:pyemd2:main.py:127:handleKline:2217508: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}


## /root/FIL/strategy/similarity/log.txt ----- -----

127.0.0.1 - - [13/Aug/2023 00:00:04] "POST / HTTP/1.1" 200 -
2023-08-13 00:00:04,307:INFO:testStrategy:main.py:308:handleOrderFilled:2217133: handleOrderFilled: data=OrderType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'clientorderid': '42849F1691856003547I0L2', 'symbol': 'BTCUSDT', 'gatewayorderid': 1691856004024592, 'quantity': '36.638', 'price': '29426.1', 'stopprice': '0', 'ordertype': '', 'side': 'BUY', 'status': 'FILLED', 'positionside': 'LONG', 'createtime': 1691856002591, 'updatetime': 1691856004024, 'tradetype': 'usdt', 'selfid': 42849, 'filltrades': [TradeType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'tradeid': 1691856004024, 'clientorderid': '42849F1691856003547I0L2', 'price': '29426.1', 'quantity': '36.638', 'commission': '1078.1134518', 'commissionasset': 'USDT', 'tradetime': 1691856004024, 'tradetype': 'usdt', 'gatetype': 'simulator', 'handletime': 1691856004024}], 'gatetype': 'simulator', 'handletime': 0}
127.0.0.1 - - [13/Aug/2023 00:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=13043 

self.closeSec=1691856599, self.tradeDate='20230813', self.openTime='000000', self.closeTime='000959', self.symbol='BTCUSDT', self.open='29426', self.close='29438.2'
2023-08-13 00:10:01,183:INFO:testStrategy:main.py:101:handleKline:2217133: self.closeSec=1691856599, self.tradeDate='20230813', self.openTime='000000', self.closeTime='000959',self.symbol='BTCUSDT',self.open='29426', self.close='29438.2'
2023-08-13 00:10:01,197:INFO:testStrategy:main.py:102:handleKline:2217133: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12236  20230812   232000    232959  1691854199    29439  29439.4
12237  20230812   233000    233959  1691854799  29439.5    29443
12238  20230812   234000    234959  1691855399  29443.1  29428.8
12239  20230812   235000    235959  1691855999  29428.8    29426
12240  20230813   000000    000959  1691856599    29426  29438.2
2023-08-13 00:10:01,197:INFO:testStrategy:main.py:103:handleKline:2217133: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False, 'isCorr': False}

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=13044 

self.closeSec=1691857199, self.tradeDate='20230813', self.openTime='001000', self.closeTime='001959', self.symbol='BTCUSDT', self.open='29438.1', self.close='29455.7'
127.0.0.1 - - [13/Aug/2023 00:20:04] "POST / HTTP/1.1" 200 -
2023-08-13 00:20:08,199:INFO:testStrategy:main.py:101:handleKline:2217133: self.closeSec=1691857199, self.tradeDate='20230813', self.openTime='001000', self.closeTime='001959',self.symbol='BTCUSDT',self.open='29438.1', self.close='29455.7'
2023-08-13 00:20:08,390:INFO:testStrategy:main.py:102:handleKline:2217133: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12237  20230812   233000    233959  1691854799  29439.5    29443
12238  20230812   234000    234959  1691855399  29443.1  29428.8
12239  20230812   235000    235959  1691855999  29428.8    29426
12240  20230813   000000    000959  1691856599    29426  29438.2
12241  20230813   001000    001959  1691857199  29438.1  29455.7
2023-08-13 00:20:08,391:INFO:testStrategy:main.py:103:handleKline:2217133: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False, 'isCorr': False}


## /root/FIL/strategy/sr_min/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=1, self.total=996015.990996, self.flagDict['side']='buy', self.tradeCount=1, self.count=26080
self.closeSec=1691857199, self.tradeDate='20230813', self.openTime='001500', self.closeTime='001959', self.symbol='BTCUSDT', self.open=29448.4, self.close=29455.7, self.high=29455.7, self.low=29448.3, self.vol=472.852, self.amt=13926164.04 
127.0.0.1 - - [13/Aug/2023 00:20:01] "POST / HTTP/1.1" 200 -
2023-08-13 00:20:06,307:INFO:sr_min:main.py:172:handleKline:2219263: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5759  20230812   235500    235959  ...         0.0        0.0       0
5760  20230813   000000    000459  ...         0.0        0.0       0
5761  20230813   000500    000959  ...         0.0        0.0       0
5762  20230813   001000    001459  ...         0.0        0.0       0
5763  20230813   001500    001959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-08-13 00:20:06,337:INFO:sr_min:main.py:175:handleKline:2219263: self.closeSec=1691857199, self.tradeDate='20230813', self.openTime='001500', self.closeTime='001959',self.symbol='BTCUSDT',self.open=29448.4, self.close=29455.7, self.high=29455.7, self.low=29448.3, self.vol=472.852, self.amt=13926164.04, ukdf['pct'].iloc[-1]=0.000248 , ukdf['amount'].iloc[-1]=13926164.04, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5763, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '37.141', 'enterprice': '26844', 'countrevence': '0', 'unrealprofit': '97021.0676717659', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '29456.2362799', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=1
127.0.0.1 - - [13/Aug/2023 00:25:00] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=1, self.total=996015.990996, self.flagDict['side']='buy', self.tradeCount=1, self.count=26081
self.closeSec=1691857499, self.tradeDate='20230813', self.openTime='002000', self.closeTime='002459', self.symbol='BTCUSDT', self.open=29455.7, self.close=29455.8, self.high=29459.0, self.low=29453.7, self.vol=493.932, self.amt=14549600.471 
2023-08-13 00:25:00,784:INFO:sr_min:main.py:172:handleKline:2219263: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5760  20230813   000000    000459  ...         0.0        0.0       0
5761  20230813   000500    000959  ...         0.0        0.0       0
5762  20230813   001000    001459  ...         0.0        0.0       0
5763  20230813   001500    001959  ...         0.0        0.0       0
5764  20230813   002000    002459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-08-13 00:25:00,785:INFO:sr_min:main.py:175:handleKline:2219263: self.closeSec=1691857499, self.tradeDate='20230813', self.openTime='002000', self.closeTime='002459',self.symbol='BTCUSDT',self.open=29455.7, self.close=29455.8, self.high=29459.0, self.low=29453.7, self.vol=493.932, self.amt=14549600.471, ukdf['pct'].iloc[-1]=3e-06 , ukdf['amount'].iloc[-1]=14549600.471, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5764, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '37.141', 'enterprice': '26844', 'countrevence': '0', 'unrealprofit': '97043.47055545142', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '29456.83946462', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=1


## /root/FIL/strategy/s_rsrs/log.txt ----- -----

723  20230812   120000    155959  1691827199  ...    723  1.113365  1.792293     1.0
724  20230812   160000    195959  1691841599  ...    724  1.103626  1.717364     1.0

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '51.457', 'enterprice': '29884.4', 'countrevence': '0', 'unrealprofit': '-24041.58593365102', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '29417.18298514', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=1, self.sign=1
127.0.0.1 - - [13/Aug/2023 00:00:01] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='s_rsrs', self.symbol='BTCUSDT', interval='4h', intervalSec=14400, wid=25, thd=0.6, self.sign=1, self.total=1536223.8092292, self.flagDict['side']='buy', self.tradeCount=19, self.count=543
self.closeSec=1691855999, self.tradeDate='20230812', self.openTime='200000', self.closeTime='235959', self.symbol='BTCUSDT', self.open=29416.7, self.close=29426.0, self.high=29445.3, self.low=29395.7, self.vol=10838.163, self.amt=318872288.3151 
2023-08-13 00:00:01,612:INFO:s_rsrs:main.py:141:handleKline:2218689: self.closeSec=1691855999, self.tradeDate='20230812', self.openTime='200000', self.closeTime='235959',self.symbol='BTCUSDT',self.open=29416.7, self.close=29426.0, self.high=29445.3, self.low=29395.7, self.vol=10838.163, self.amt=318872288.3151 
2023-08-13 00:00:01,626:INFO:s_rsrs:main.py:142:handleKline:2218689: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime  ...        vol           amt       pct
721  20230812   040000    075959  ...  10294.370  3.027534e+08  0.000943
722  20230812   080000    115959  ...  11511.455  3.384544e+08 -0.000935
723  20230812   120000    155959  ...   7457.781  2.192525e+08  0.000755
724  20230812   160000    195959  ...   9821.475  2.888007e+08  0.000221
725  20230812   200000    235959  ...  10838.163  3.188723e+08  0.000316

[5 rows x 11 columns]
2023-08-13 00:00:02,453:INFO:s_rsrs:main.py:151:handleKline:2218689: df_s.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec  ...  index      beta    zscore  signal
721  20230812   040000    075959  1691798399  ...    721  1.177032  2.091827     1.0
722  20230812   080000    115959  1691812799  ...    722  1.171680  2.004801     1.0
723  20230812   120000    155959  1691827199  ...    723  1.113365  1.792293     1.0
724  20230812   160000    195959  1691841599  ...    724  1.103626  1.717364     1.0
725  20230812   200000    235959  1691855999  ...    725  1.313265  2.176949     1.0

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '51.457', 'enterprice': '29884.4', 'countrevence': '0', 'unrealprofit': '-23583.76095239248', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '29426.08021936', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=1, self.sign=1


