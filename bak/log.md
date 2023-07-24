# 20230725 00:26:02

## /root/FIL/strategy/amihud/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=373746.4768026, self.flagDict['side']='sell', self.tradeCount=2, self.count=20608
self.closeSec=1690215599, self.tradeDate='20230725', self.openTime='001500', self.closeTime='001959', self.symbol='BTCUSDT', self.open=29060.3, self.close=29028.1, self.high=29063.3, self.low=29014.0, self.vol=2236.211, self.amt=64914313.3077 
127.0.0.1 - - [25/Jul/2023 00:20:01] "POST / HTTP/1.1" 200 -
2023-07-25 00:20:05,268:INFO:amihud:main.py:172:handleKline:2219019: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5759  20230724   235500    235959  ...         0.0        0.0       0
5760  20230725   000000    000459  ...         0.0        0.0       0
5761  20230725   000500    000959  ...         0.0        0.0       0
5762  20230725   001000    001459  ...         0.0        0.0       0
5763  20230725   001500    001959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-07-25 00:20:05,288:INFO:amihud:main.py:175:handleKline:2219019: self.closeSec=1690215599, self.tradeDate='20230725', self.openTime='001500', self.closeTime='001959',self.symbol='BTCUSDT',self.open=29060.3, self.close=29028.1, self.high=29063.3, self.low=29014.0, self.vol=2236.211, self.amt=64914313.3077, ukdf['pct'].iloc[-1]=-0.001156 , ukdf['amount'].iloc[-1]=64914313.3077, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5763, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '13.926', 'enterprice': '26864.9', 'countrevence': '0', 'unrealprofit': '-30069.0192', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '29024.1', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1
127.0.0.1 - - [25/Jul/2023 00:25:00] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=373746.4768026, self.flagDict['side']='sell', self.tradeCount=2, self.count=20609
self.closeSec=1690215899, self.tradeDate='20230725', self.openTime='002000', self.closeTime='002459', self.symbol='BTCUSDT', self.open=29028.2, self.close=29078.1, self.high=29097.7, self.low=29023.9, self.vol=1688.616, self.amt=49089367.8877 
2023-07-25 00:25:00,806:INFO:amihud:main.py:172:handleKline:2219019: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5760  20230725   000000    000459  ...         0.0        0.0       0
5761  20230725   000500    000959  ...         0.0        0.0       0
5762  20230725   001000    001459  ...         0.0        0.0       0
5763  20230725   001500    001959  ...         0.0        0.0       0
5764  20230725   002000    002459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-07-25 00:25:00,807:INFO:amihud:main.py:175:handleKline:2219019: self.closeSec=1690215899, self.tradeDate='20230725', self.openTime='002000', self.closeTime='002459',self.symbol='BTCUSDT',self.open=29028.2, self.close=29078.1, self.high=29097.7, self.low=29023.9, self.vol=1688.616, self.amt=49089367.8877, ukdf['pct'].iloc[-1]=0.001722 , ukdf['amount'].iloc[-1]=49089367.8877, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5764, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '13.926', 'enterprice': '26864.9', 'countrevence': '0', 'unrealprofit': '-30831.74948815368', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '29078.87023468', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1


## /root/FIL/strategy/factorcheck/log.txt ----- -----


self.closeSec=1690215599, self.tradeDate='20230725', self.openTime='001500', self.closeTime='001959', self.symbol='BTCUSDT', self.open=29060.3, self.close=29028.1, self.high=29063.3, self.low=29014.0 
127.0.0.1 - - [25/Jul/2023 00:20:01] "POST / HTTP/1.1" 200 -
2023-07-25 00:20:03,649:INFO:factorcheck2:main.py:126:handleKline:2218005: self.closeSec=1690215599, self.tradeDate='20230725', self.openTime='001500', self.closeTime='001959',self.symbol='BTCUSDT',self.open=29060.3, self.close=29028.1, self.high=29063.3, self.low=29014.0   
2023-07-25 00:20:04,648:INFO:factorcheck2:main.py:127:handleKline:2218005: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1439  20230724   235500    235959  1690214399  ...  29044.8  0.001184   1727    5
1440  20230725   000000    000459  1690214699  ...  29068.6  0.001375   1440    0
1441  20230725   000500    000959  1690214999  ...  29065.5 -0.001600   1441    1
1442  20230725   001000    001459  1690215299  ...  29054.9 -0.000574   1442    2
1443  20230725   001500    001959  1690215599  ...  29014.0 -0.001156   1443    3

[5 rows x 11 columns]
2023-07-25 00:20:04,658:INFO:factorcheck2:main.py:128:handleKline:2218005: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': False, 'isOpen': True, 'isClose': False, 'isTrig': True}
127.0.0.1 - - [25/Jul/2023 00:25:00] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.6616822444886471, self.count=20611 

self.closeSec=1690215899, self.tradeDate='20230725', self.openTime='002000', self.closeTime='002459', self.symbol='BTCUSDT', self.open=29028.2, self.close=29078.1, self.high=29097.7, self.low=29023.9 
2023-07-25 00:25:00,789:INFO:factorcheck2:main.py:126:handleKline:2218005: self.closeSec=1690215899, self.tradeDate='20230725', self.openTime='002000', self.closeTime='002459',self.symbol='BTCUSDT',self.open=29028.2, self.close=29078.1, self.high=29097.7, self.low=29023.9   
2023-07-25 00:25:00,812:INFO:factorcheck2:main.py:127:handleKline:2218005: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1440  20230725   000000    000459  1690214699  ...  29068.6  0.001375   1440    0
1441  20230725   000500    000959  1690214999  ...  29065.5 -0.001600   1441    1
1442  20230725   001000    001459  1690215299  ...  29054.9 -0.000574   1442    2
1443  20230725   001500    001959  1690215599  ...  29014.0 -0.001156   1443    3
1444  20230725   002000    002459  1690215899  ...  29023.9  0.001722   1444    4

[5 rows x 11 columns]
2023-07-25 00:25:00,812:INFO:factorcheck2:main.py:128:handleKline:2218005: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': False, 'isOpen': True, 'isClose': False, 'isTrig': True}


## /root/FIL/strategy/logic/log.txt ----- -----

2023-07-25 00:00:17,694:DEBUG:logic:main.py:463:getModel:2218526: df_s.iloc[-5:,:] :
          date closeTime     open  ...    alpha58   alpha67   alpha72
5802  20230724    212959  29223.5  ...  50.000000  0.372320  0.735169
5803  20230724    215959  29201.2  ...  49.583333  0.367568  0.740665
5804  20230724    222959  29171.4  ...  49.583333  0.353169  0.750043
5805  20230724    225959  29078.0  ...  49.583333  0.346372  0.760881
5806  20230724    232959  29032.3  ...  49.583333  0.363803  0.764100

[5 rows x 33 columns]
0.5367647058823529
acc is : 0.5367647058823529
2023-07-25 00:00:17,760:INFO:logic:main.py:468:getModel:2218526: df_pred.iloc[-5:,:] :
     pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
539     1  0.488718  0.511282       0  ...  0.946549  -1.0    0.0  0.961008
540     1  0.488071  0.511929       0  ...  0.949576  -1.0    0.0  0.957934
541     1  0.465275  0.534725       0  ...  0.951072  -1.0    0.0  0.956426
542     1  0.479845  0.520155       1  ...  0.948978  -1.0    0.0  0.958531
543     0  0.507166  0.492834       0  ...  0.949344  -1.0    0.0  0.958162

[5 rows x 10 columns]
2023-07-25 00:00:17,772:INFO:logic:main.py:478:getModel:2218526: df_panel.iloc[-5:,:] :
    pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
45     1  0.488932  0.511068       0  ...  0.946549  -1.0    0.0  0.961154
46     1  0.487856  0.512144       0  ...  0.949576  -1.0    0.0  0.957297
47     1  0.465263  0.534737       0  ...  0.951072  -1.0    0.0  0.955790
48     1  0.479483  0.520517       1  ...  0.948978  -1.0    0.0  0.957213
49     0  0.507166  0.492834       0  ...  0.949344  -1.0    0.0  0.958162

[5 rows x 10 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '23.403', 'enterprice': '29752', 'countrevence': '0', 'unrealprofit': '15958.26828381993', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '29070.11014469', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}


## /root/FIL/strategy/modifiedmom/log.txt ----- -----

127.0.0.1 - - [25/Jul/2023 00:00:04] "POST / HTTP/1.1" 200 -
2023-07-25 00:00:04,196:INFO:modifiedmom:main.py:319:handleOrderFilled:2218259: handleOrderFilled: data=OrderType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'clientorderid': '42725F1690214403631I0L59', 'symbol': 'BTCUSDT', 'gatewayorderid': 1690214403999181, 'quantity': '24.895', 'price': '29085.9', 'stopprice': '0', 'ordertype': '', 'side': 'BUY', 'status': 'FILLED', 'positionside': 'LONG', 'createtime': 1690214402802, 'updatetime': 1690214403999, 'tradetype': 'usdt', 'selfid': 42725, 'filltrades': [TradeType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'tradeid': 1690214403999, 'clientorderid': '42725F1690214403631I0L59', 'price': '29085.9', 'quantity': '24.895', 'commission': '724.0934805', 'commissionasset': 'USDT', 'tradetime': 1690214403999, 'tradetype': 'usdt', 'gatetype': 'simulator', 'handletime': 1690214403999}], 'gatetype': 'simulator', 'handletime': 0}
127.0.0.1 - - [25/Jul/2023 00:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=10304 

self.closeSec=1690214999, self.tradeDate='20230725', self.openTime='000000', self.closeTime='000959', self.symbol='BTCUSDT', self.open='29085.9', self.close='29078.5'
2023-07-25 00:10:01,067:INFO:modifiedmom:main.py:144:handleKline:2218259: self.closeSec=1690214999, self.tradeDate='20230725', self.openTime='000000', self.closeTime='000959',self.symbol='BTCUSDT',self.open='29085.9', self.close='29078.5'
2023-07-25 00:10:01,080:INFO:modifiedmom:main.py:145:handleKline:2218259: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
572  20230724   232000    232959  1690212599  29054.1  29096.2  0.001446
573  20230724   233000    233959  1690213199  29096.3  29068.1 -0.000966
574  20230724   234000    234959  1690213799    29068  29072.4  0.000148
575  20230724   235000    235959  1690214399  29072.4    29085  0.000433
576  20230725   000000    000959  1690214999  29085.9  29078.5 -0.000223
2023-07-25 00:10:01,081:INFO:modifiedmom:main.py:146:handleKline:2218259: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=10305 

self.closeSec=1690215599, self.tradeDate='20230725', self.openTime='001000', self.closeTime='001959', self.symbol='BTCUSDT', self.open='29078.4', self.close='29028.1'
127.0.0.1 - - [25/Jul/2023 00:20:04] "POST / HTTP/1.1" 200 -
2023-07-25 00:20:05,678:INFO:modifiedmom:main.py:144:handleKline:2218259: self.closeSec=1690215599, self.tradeDate='20230725', self.openTime='001000', self.closeTime='001959',self.symbol='BTCUSDT',self.open='29078.4', self.close='29028.1'
2023-07-25 00:20:06,028:INFO:modifiedmom:main.py:145:handleKline:2218259: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
573  20230724   233000    233959  1690213199  29096.3  29068.1 -0.000966
574  20230724   234000    234959  1690213799    29068  29072.4  0.000148
575  20230724   235000    235959  1690214399  29072.4    29085  0.000433
576  20230725   000000    000959  1690214999  29085.9  29078.5 -0.000223
577  20230725   001000    001959  1690215599  29078.4  29028.1 -0.001733
2023-07-25 00:20:06,029:INFO:modifiedmom:main.py:146:handleKline:2218259: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False}


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

2023-07-25 00:00:02,276:INFO:pyemd2:main.py:127:handleKline:2217508: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}
2023-07-25 00:00:02,330:INFO:pyemd2:main.py:190:insertFactor:2217508: curDateTime:7250000, name:pyemd2, symbol:BTCUSDT, tradeDate:20230724, closeTime:235959, close:29085, total:1006791.0689493, pct_pre:-0.025532554759159942, thd:-0.11588306952787325, side:sell 
127.0.0.1 - - [25/Jul/2023 00:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=10307 

self.closeSec=1690214999, self.tradeDate='20230725', self.openTime='000000', self.closeTime='000959', self.symbol='BTCUSDT', self.open='29085.9', self.close='29078.5'
2023-07-25 00:10:01,060:INFO:pyemd2:main.py:125:handleKline:2217508: self.closeSec=1690214999, self.tradeDate='20230725', self.openTime='000000', self.closeTime='000959',self.symbol='BTCUSDT',self.open='29085.9', self.close='29078.5'
2023-07-25 00:10:01,073:INFO:pyemd2:main.py:126:handleKline:2217508: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17420  20230724   232000    232959  1690212599  29054.1  29096.2
17421  20230724   233000    233959  1690213199  29096.3  29068.1
17422  20230724   234000    234959  1690213799    29068  29072.4
17423  20230724   235000    235959  1690214399  29072.4    29085
17424  20230725   000000    000959  1690214999  29085.9  29078.5
2023-07-25 00:10:01,074:INFO:pyemd2:main.py:127:handleKline:2217508: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=10308 

self.closeSec=1690215599, self.tradeDate='20230725', self.openTime='001000', self.closeTime='001959', self.symbol='BTCUSDT', self.open='29078.4', self.close='29028.1'
127.0.0.1 - - [25/Jul/2023 00:20:04] "POST / HTTP/1.1" 200 -
2023-07-25 00:20:06,669:INFO:pyemd2:main.py:125:handleKline:2217508: self.closeSec=1690215599, self.tradeDate='20230725', self.openTime='001000', self.closeTime='001959',self.symbol='BTCUSDT',self.open='29078.4', self.close='29028.1'
2023-07-25 00:20:06,747:INFO:pyemd2:main.py:126:handleKline:2217508: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17421  20230724   233000    233959  1690213199  29096.3  29068.1
17422  20230724   234000    234959  1690213799    29068  29072.4
17423  20230724   235000    235959  1690214399  29072.4    29085
17424  20230725   000000    000959  1690214999  29085.9  29078.5
17425  20230725   001000    001959  1690215599  29078.4  29028.1
2023-07-25 00:20:06,747:INFO:pyemd2:main.py:127:handleKline:2217508: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}


## /root/FIL/strategy/similarity/log.txt ----- -----

127.0.0.1 - - [25/Jul/2023 00:00:04] "POST / HTTP/1.1" 200 -
2023-07-25 00:00:04,306:INFO:testStrategy:main.py:308:handleOrderFilled:2217133: handleOrderFilled: data=OrderType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'clientorderid': '42726F1690214403696I0L2', 'symbol': 'BTCUSDT', 'gatewayorderid': 1690214404078162, 'quantity': '37.766', 'price': '29085.8', 'stopprice': '0', 'ordertype': '', 'side': 'SELL', 'status': 'FILLED', 'positionside': 'SHORT', 'createtime': 1690214402821, 'updatetime': 1690214404078, 'tradetype': 'usdt', 'selfid': 42726, 'filltrades': [TradeType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'tradeid': 1690214404078, 'clientorderid': '42726F1690214403696I0L2', 'price': '29085.8', 'quantity': '37.766', 'commission': '1098.4543228', 'commissionasset': 'USDT', 'tradetime': 1690214404078, 'tradetype': 'usdt', 'gatetype': 'simulator', 'handletime': 1690214404078}], 'gatetype': 'simulator', 'handletime': 0}
127.0.0.1 - - [25/Jul/2023 00:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=10307 

self.closeSec=1690214999, self.tradeDate='20230725', self.openTime='000000', self.closeTime='000959', self.symbol='BTCUSDT', self.open='29085.9', self.close='29078.5'
2023-07-25 00:10:01,065:INFO:testStrategy:main.py:101:handleKline:2217133: self.closeSec=1690214999, self.tradeDate='20230725', self.openTime='000000', self.closeTime='000959',self.symbol='BTCUSDT',self.open='29085.9', self.close='29078.5'
2023-07-25 00:10:01,076:INFO:testStrategy:main.py:102:handleKline:2217133: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12236  20230724   232000    232959  1690212599  29054.1  29096.2
12237  20230724   233000    233959  1690213199  29096.3  29068.1
12238  20230724   234000    234959  1690213799    29068  29072.4
12239  20230724   235000    235959  1690214399  29072.4    29085
12240  20230725   000000    000959  1690214999  29085.9  29078.5
2023-07-25 00:10:01,076:INFO:testStrategy:main.py:103:handleKline:2217133: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False, 'isCorr': False}

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=10308 

self.closeSec=1690215599, self.tradeDate='20230725', self.openTime='001000', self.closeTime='001959', self.symbol='BTCUSDT', self.open='29078.4', self.close='29028.1'
127.0.0.1 - - [25/Jul/2023 00:20:04] "POST / HTTP/1.1" 200 -
2023-07-25 00:20:06,559:INFO:testStrategy:main.py:101:handleKline:2217133: self.closeSec=1690215599, self.tradeDate='20230725', self.openTime='001000', self.closeTime='001959',self.symbol='BTCUSDT',self.open='29078.4', self.close='29028.1'
2023-07-25 00:20:06,689:INFO:testStrategy:main.py:102:handleKline:2217133: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12237  20230724   233000    233959  1690213199  29096.3  29068.1
12238  20230724   234000    234959  1690213799    29068  29072.4
12239  20230724   235000    235959  1690214399  29072.4    29085
12240  20230725   000000    000959  1690214999  29085.9  29078.5
12241  20230725   001000    001959  1690215599  29078.4  29028.1
2023-07-25 00:20:06,690:INFO:testStrategy:main.py:103:handleKline:2217133: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False, 'isCorr': False}


## /root/FIL/strategy/sr_min/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=1, self.total=996015.990996, self.flagDict['side']='buy', self.tradeCount=1, self.count=20608
self.closeSec=1690215599, self.tradeDate='20230725', self.openTime='001500', self.closeTime='001959', self.symbol='BTCUSDT', self.open=29060.3, self.close=29028.1, self.high=29063.3, self.low=29014.0, self.vol=2236.211, self.amt=64914313.3077 
127.0.0.1 - - [25/Jul/2023 00:20:01] "POST / HTTP/1.1" 200 -
2023-07-25 00:20:05,277:INFO:sr_min:main.py:172:handleKline:2219263: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5759  20230724   235500    235959  ...         0.0        0.0       0
5760  20230725   000000    000459  ...         0.0        0.0       0
5761  20230725   000500    000959  ...         0.0        0.0       0
5762  20230725   001000    001459  ...         0.0        0.0       0
5763  20230725   001500    001959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-07-25 00:20:05,297:INFO:sr_min:main.py:175:handleKline:2219263: self.closeSec=1690215599, self.tradeDate='20230725', self.openTime='001500', self.closeTime='001959',self.symbol='BTCUSDT',self.open=29060.3, self.close=29028.1, self.high=29063.3, self.low=29014.0, self.vol=2236.211, self.amt=64914313.3077, ukdf['pct'].iloc[-1]=-0.001156 , ukdf['amount'].iloc[-1]=64914313.3077, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5763, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '37.141', 'enterprice': '26844', 'countrevence': '0', 'unrealprofit': '80974.8082', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '29024.2', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=1
--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=1, self.total=996015.990996, self.flagDict['side']='buy', self.tradeCount=1, self.count=20609
self.closeSec=1690215899, self.tradeDate='20230725', self.openTime='002000', self.closeTime='002459', self.symbol='BTCUSDT', self.open=29028.2, self.close=29078.1, self.high=29097.7, self.low=29023.9, self.vol=1688.616, self.amt=49089367.8877 
127.0.0.1 - - [25/Jul/2023 00:25:00] "POST / HTTP/1.1" 200 -
2023-07-25 00:25:00,820:INFO:sr_min:main.py:172:handleKline:2219263: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5760  20230725   000000    000459  ...         0.0        0.0       0
5761  20230725   000500    000959  ...         0.0        0.0       0
5762  20230725   001000    001459  ...         0.0        0.0       0
5763  20230725   001500    001959  ...         0.0        0.0       0
5764  20230725   002000    002459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-07-25 00:25:00,820:INFO:sr_min:main.py:175:handleKline:2219263: self.closeSec=1690215899, self.tradeDate='20230725', self.openTime='002000', self.closeTime='002459',self.symbol='BTCUSDT',self.open=29028.2, self.close=29078.1, self.high=29097.7, self.low=29023.9, self.vol=1688.616, self.amt=49089367.8877, ukdf['pct'].iloc[-1]=0.001722 , ukdf['amount'].iloc[-1]=49089367.8877, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5764, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '37.141', 'enterprice': '26844', 'countrevence': '0', 'unrealprofit': '83005.31538624988', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '29078.87023468', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=1


## /root/FIL/strategy/s_rsrs/log.txt ----- -----

723  20230724   120000    155959  1690185599  ...    723  0.125401 -0.842012    -1.0
724  20230724   160000    195959  1690199999  ...    724  0.027101 -1.207360    -1.0

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '52.176', 'enterprice': '29870.6', 'countrevence': '0', 'unrealprofit': '31922.48076589584', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '29258.77692491', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-1, self.sign=-1
--handleKline--:  version='2.0.0', self.name='s_rsrs', self.symbol='BTCUSDT', interval='4h', intervalSec=14400, wid=25, thd=0.6, self.sign=-1, self.total=1556969.8971744, self.flagDict['side']='sell', self.tradeCount=12, self.count=429
self.closeSec=1690214399, self.tradeDate='20230724', self.openTime='200000', self.closeTime='235959', self.symbol='BTCUSDT', self.open=29259.7, self.close=29085.0, self.high=29262.6, self.low=28830.0, self.vol=124594.368, self.amt=3623508489.28393 
127.0.0.1 - - [25/Jul/2023 00:00:01] "POST / HTTP/1.1" 200 -
2023-07-25 00:00:01,791:INFO:s_rsrs:main.py:141:handleKline:2218689: self.closeSec=1690214399, self.tradeDate='20230724', self.openTime='200000', self.closeTime='235959',self.symbol='BTCUSDT',self.open=29259.7, self.close=29085.0, self.high=29262.6, self.low=28830.0, self.vol=124594.368, self.amt=3623508489.28393 
2023-07-25 00:00:01,806:INFO:s_rsrs:main.py:142:handleKline:2218689: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime  ...         vol           amt       pct
721  20230724   040000    075959  ...   37643.416  1.130502e+09 -0.000409
722  20230724   080000    115959  ...   70283.909  2.096249e+09 -0.012141
723  20230724   120000    155959  ...   41872.139  1.246236e+09  0.003727
724  20230724   160000    195959  ...  137130.388  4.018484e+09 -0.018674
725  20230724   200000    235959  ...  124594.368  3.623508e+09 -0.005967

[5 rows x 11 columns]
2023-07-25 00:00:02,634:INFO:s_rsrs:main.py:151:handleKline:2218689: df_s.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec  ...  index      beta    zscore  signal
721  20230724   040000    075959  1690156799  ...    721  0.150437 -0.769752    -1.0
722  20230724   080000    115959  1690171199  ...    722  0.110284 -0.915170    -1.0
723  20230724   120000    155959  1690185599  ...    723  0.125401 -0.842012    -1.0
724  20230724   160000    195959  1690199999  ...    724  0.027101 -1.207360    -1.0
725  20230724   200000    235959  1690214399  ...    725  0.093340 -0.933171    -1.0

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '52.176', 'enterprice': '29870.6', 'countrevence': '0', 'unrealprofit': '40947.7248', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '29085.8', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-1, self.sign=-1


