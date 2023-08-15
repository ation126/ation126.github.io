# 20230816 00:26:02

## /root/FIL/strategy/amihud/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=373746.4768026, self.flagDict['side']='sell', self.tradeCount=2, self.count=26944
self.closeSec=1692116399, self.tradeDate='20230816', self.openTime='001500', self.closeTime='001959', self.symbol='BTCUSDT', self.open=29326.6, self.close=29344.7, self.high=29358.0, self.low=29314.6, self.vol=1374.953, self.amt=40339298.3781 
127.0.0.1 - - [16/Aug/2023 00:20:01] "POST / HTTP/1.1" 200 -
2023-08-16 00:20:06,975:INFO:amihud:main.py:172:handleKline:2219019: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5759  20230815   235500    235959  ...         0.0        0.0       0
5760  20230816   000000    000459  ...         0.0        0.0       0
5761  20230816   000500    000959  ...         0.0        0.0       0
5762  20230816   001000    001459  ...         0.0        0.0       0
5763  20230816   001500    001959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-08-16 00:20:06,986:INFO:amihud:main.py:175:handleKline:2219019: self.closeSec=1692116399, self.tradeDate='20230816', self.openTime='001500', self.closeTime='001959',self.symbol='BTCUSDT',self.open=29326.6, self.close=29344.7, self.high=29358.0, self.low=29314.6, self.vol=1374.953, self.amt=40339298.3781, ukdf['pct'].iloc[-1]=0.000617 , ukdf['amount'].iloc[-1]=40339298.3781, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5763, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '13.926', 'enterprice': '26864.9', 'countrevence': '0', 'unrealprofit': '-34569.28307554722', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '29347.25552747', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1
--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=373746.4768026, self.flagDict['side']='sell', self.tradeCount=2, self.count=26945
self.closeSec=1692116699, self.tradeDate='20230816', self.openTime='002000', self.closeTime='002459', self.symbol='BTCUSDT', self.open=29344.6, self.close=29354.1, self.high=29358.9, self.low=29336.4, self.vol=902.706, self.amt=26493229.7578 
127.0.0.1 - - [16/Aug/2023 00:25:00] "POST / HTTP/1.1" 200 -
2023-08-16 00:25:00,832:INFO:amihud:main.py:172:handleKline:2219019: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5760  20230816   000000    000459  ...         0.0        0.0       0
5761  20230816   000500    000959  ...         0.0        0.0       0
5762  20230816   001000    001459  ...         0.0        0.0       0
5763  20230816   001500    001959  ...         0.0        0.0       0
5764  20230816   002000    002459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-08-16 00:25:00,832:INFO:amihud:main.py:175:handleKline:2219019: self.closeSec=1692116699, self.tradeDate='20230816', self.openTime='002000', self.closeTime='002459',self.symbol='BTCUSDT',self.open=29344.6, self.close=29354.1, self.high=29358.9, self.low=29336.4, self.vol=902.706, self.amt=26493229.7578, ukdf['pct'].iloc[-1]=0.00032 , ukdf['amount'].iloc[-1]=26493229.7578, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5764, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '13.926', 'enterprice': '26864.9', 'countrevence': '0', 'unrealprofit': '-34665.9918', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '29354.2', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1


## /root/FIL/strategy/factorcheck/log.txt ----- -----


self.closeSec=1692116399, self.tradeDate='20230816', self.openTime='001500', self.closeTime='001959', self.symbol='BTCUSDT', self.open=29326.6, self.close=29344.7, self.high=29358.0, self.low=29314.6 
127.0.0.1 - - [16/Aug/2023 00:20:01] "POST / HTTP/1.1" 200 -
2023-08-16 00:20:04,635:INFO:factorcheck2:main.py:126:handleKline:2218005: self.closeSec=1692116399, self.tradeDate='20230816', self.openTime='001500', self.closeTime='001959',self.symbol='BTCUSDT',self.open=29326.6, self.close=29344.7, self.high=29358.0, self.low=29314.6   
2023-08-16 00:20:05,846:INFO:factorcheck2:main.py:127:handleKline:2218005: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1439  20230815   235500    235959  1692115199  ...  29294.9 -0.000164   1727    5
1440  20230816   000000    000459  1692115499  ...  29297.0  0.000849   1440    0
1441  20230816   000500    000959  1692115799  ...  29315.0 -0.000699   1441    1
1442  20230816   001000    001459  1692116099  ...  29305.7  0.000242   1442    2
1443  20230816   001500    001959  1692116399  ...  29314.6  0.000617   1443    3

[5 rows x 11 columns]
2023-08-16 00:20:05,856:INFO:factorcheck2:main.py:128:handleKline:2218005: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}
127.0.0.1 - - [16/Aug/2023 00:25:00] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=20, self.factor=0.5843233917205718, self.count=26947 

self.closeSec=1692116699, self.tradeDate='20230816', self.openTime='002000', self.closeTime='002459', self.symbol='BTCUSDT', self.open=29344.6, self.close=29354.1, self.high=29358.9, self.low=29336.4 
2023-08-16 00:25:00,793:INFO:factorcheck2:main.py:126:handleKline:2218005: self.closeSec=1692116699, self.tradeDate='20230816', self.openTime='002000', self.closeTime='002459',self.symbol='BTCUSDT',self.open=29344.6, self.close=29354.1, self.high=29358.9, self.low=29336.4   
2023-08-16 00:25:00,821:INFO:factorcheck2:main.py:127:handleKline:2218005: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1440  20230816   000000    000459  1692115499  ...  29297.0  0.000849   1440    0
1441  20230816   000500    000959  1692115799  ...  29315.0 -0.000699   1441    1
1442  20230816   001000    001459  1692116099  ...  29305.7  0.000242   1442    2
1443  20230816   001500    001959  1692116399  ...  29314.6  0.000617   1443    3
1444  20230816   002000    002459  1692116699  ...  29336.4  0.000320   1444    4

[5 rows x 11 columns]
2023-08-16 00:25:00,821:INFO:factorcheck2:main.py:128:handleKline:2218005: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}


## /root/FIL/strategy/logic/log.txt ----- -----

2023-08-16 00:00:17,839:DEBUG:logic:main.py:463:getModel:2218526: df_s.iloc[-5:,:] :
          date closeTime     open  ...    alpha58   alpha67   alpha72
5802  20230815    212959  29352.9  ...  45.833333  0.498488  0.616037
5803  20230815    215959  29395.9  ...  45.416667  0.482106  0.608718
5804  20230815    222959  29359.2  ...  45.833333  0.506306  0.588824
5805  20230815    225959  29412.8  ...  46.250000  0.519078  0.559377
5806  20230815    232959  29442.5  ...  46.250000  0.489626  0.568424

[5 rows x 33 columns]
0.5422794117647058
acc is : 0.5422794117647058
2023-08-16 00:00:17,906:INFO:logic:main.py:468:getModel:2218526: df_pred.iloc[-5:,:] :
     pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
539     0  0.514914  0.485086       0  ...  1.013999  -1.0    0.0  1.005400
540     1  0.491203  0.508797       1  ...  1.012151  -1.0    0.0  1.007232
541     0  0.518819  0.481181       1  ...  1.011126  -1.0    0.0  1.008253
542     0  0.516441  0.483559       0  ...  1.013457  -1.0    0.0  1.005928
543     1  0.486895  0.513105       0  ...  1.015514  -1.0    0.0  1.003887

[5 rows x 10 columns]
2023-08-16 00:00:17,918:INFO:logic:main.py:478:getModel:2218526: df_panel.iloc[-5:,:] :
    pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
45     0  0.515148  0.484852       0  ...  1.013999  -1.0    0.0  1.004647
46     1  0.491309  0.508691       1  ...  1.012151  -1.0    0.0  1.007812
47     0  0.518895  0.481105       1  ...  1.011126  -1.0    0.0  1.008833
48     0  0.516601  0.483399       0  ...  1.013457  -1.0    0.0  1.007114
49     1  0.486895  0.513105       0  ...  1.015514  -1.0    0.0  1.003887

[5 rows x 10 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '23.521', 'enterprice': '29410.3', 'countrevence': '0', 'unrealprofit': '2227.67692562741', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '29315.58987179', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}


## /root/FIL/strategy/modifiedmom/log.txt ----- -----

127.0.0.1 - - [16/Aug/2023 00:00:04] "POST / HTTP/1.1" 200 -
2023-08-16 00:00:04,018:INFO:modifiedmom:main.py:319:handleOrderFilled:2218259: handleOrderFilled: data=OrderType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'clientorderid': '42898F1692115203441I0L59', 'symbol': 'BTCUSDT', 'gatewayorderid': 1692115203855241, 'quantity': '24.751', 'price': '29315.2', 'stopprice': '0', 'ordertype': '', 'side': 'BUY', 'status': 'FILLED', 'positionside': 'LONG', 'createtime': 1692115202584, 'updatetime': 1692115203855, 'tradetype': 'usdt', 'selfid': 42898, 'filltrades': [TradeType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'tradeid': 1692115203855, 'clientorderid': '42898F1692115203441I0L59', 'price': '29315.2', 'quantity': '24.751', 'commission': '725.5805152', 'commissionasset': 'USDT', 'tradetime': 1692115203855, 'tradetype': 'usdt', 'gatetype': 'simulator', 'handletime': 1692115203855}], 'gatetype': 'simulator', 'handletime': 0}

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=13472 

self.closeSec=1692115799, self.tradeDate='20230816', self.openTime='000000', self.closeTime='000959', self.symbol='BTCUSDT', self.open='29315.1', self.close='29319.5'
127.0.0.1 - - [16/Aug/2023 00:10:01] "POST / HTTP/1.1" 200 -
2023-08-16 00:10:01,178:INFO:modifiedmom:main.py:144:handleKline:2218259: self.closeSec=1692115799, self.tradeDate='20230816', self.openTime='000000', self.closeTime='000959',self.symbol='BTCUSDT',self.open='29315.1', self.close='29319.5'
2023-08-16 00:10:01,195:INFO:modifiedmom:main.py:145:handleKline:2218259: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
572  20230815   232000    232959  1692113399  29358.9  29374.7  0.000538
573  20230815   233000    233959  1692113999  29374.7  29341.8 -0.001120
574  20230815   234000    234959  1692114599    29342  29340.8 -0.000034
575  20230815   235000    235959  1692115199  29340.8  29315.2 -0.000873
576  20230816   000000    000959  1692115799  29315.1  29319.5  0.000147
2023-08-16 00:10:01,195:INFO:modifiedmom:main.py:146:handleKline:2218259: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=13473 

self.closeSec=1692116399, self.tradeDate='20230816', self.openTime='001000', self.closeTime='001959', self.symbol='BTCUSDT', self.open='29319.5', self.close='29344.6'
127.0.0.1 - - [16/Aug/2023 00:20:04] "POST / HTTP/1.1" 200 -
2023-08-16 00:20:07,016:INFO:modifiedmom:main.py:144:handleKline:2218259: self.closeSec=1692116399, self.tradeDate='20230816', self.openTime='001000', self.closeTime='001959',self.symbol='BTCUSDT',self.open='29319.5', self.close='29344.6'
2023-08-16 00:20:07,627:INFO:modifiedmom:main.py:145:handleKline:2218259: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
573  20230815   233000    233959  1692113999  29374.7  29341.8 -0.001120
574  20230815   234000    234959  1692114599    29342  29340.8 -0.000034
575  20230815   235000    235959  1692115199  29340.8  29315.2 -0.000873
576  20230816   000000    000959  1692115799  29315.1  29319.5  0.000147
577  20230816   001000    001959  1692116399  29319.5  29344.6  0.000856
2023-08-16 00:20:07,636:INFO:modifiedmom:main.py:146:handleKline:2218259: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False}


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

2023-08-16 00:00:02,064:INFO:pyemd2:main.py:127:handleKline:2217508: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}
2023-08-16 00:00:02,122:INFO:pyemd2:main.py:190:insertFactor:2217508: curDateTime:8160000, name:pyemd2, symbol:BTCUSDT, tradeDate:20230815, closeTime:235959, close:29315.2, total:982611.6118804, pct_pre:-0.007548481361628556, thd:0.2801363586549284, side:sell 
127.0.0.1 - - [16/Aug/2023 00:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=13475 

self.closeSec=1692115799, self.tradeDate='20230816', self.openTime='000000', self.closeTime='000959', self.symbol='BTCUSDT', self.open='29315.1', self.close='29319.5'
2023-08-16 00:10:01,175:INFO:pyemd2:main.py:125:handleKline:2217508: self.closeSec=1692115799, self.tradeDate='20230816', self.openTime='000000', self.closeTime='000959',self.symbol='BTCUSDT',self.open='29315.1', self.close='29319.5'
2023-08-16 00:10:01,183:INFO:pyemd2:main.py:126:handleKline:2217508: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17420  20230815   232000    232959  1692113399  29358.9  29374.7
17421  20230815   233000    233959  1692113999  29374.7  29341.8
17422  20230815   234000    234959  1692114599    29342  29340.8
17423  20230815   235000    235959  1692115199  29340.8  29315.2
17424  20230816   000000    000959  1692115799  29315.1  29319.5
2023-08-16 00:10:01,183:INFO:pyemd2:main.py:127:handleKline:2217508: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=13476 

self.closeSec=1692116399, self.tradeDate='20230816', self.openTime='001000', self.closeTime='001959', self.symbol='BTCUSDT', self.open='29319.5', self.close='29344.6'
127.0.0.1 - - [16/Aug/2023 00:20:04] "POST / HTTP/1.1" 200 -
2023-08-16 00:20:08,866:INFO:pyemd2:main.py:125:handleKline:2217508: self.closeSec=1692116399, self.tradeDate='20230816', self.openTime='001000', self.closeTime='001959',self.symbol='BTCUSDT',self.open='29319.5', self.close='29344.6'
2023-08-16 00:20:08,967:INFO:pyemd2:main.py:126:handleKline:2217508: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17421  20230815   233000    233959  1692113999  29374.7  29341.8
17422  20230815   234000    234959  1692114599    29342  29340.8
17423  20230815   235000    235959  1692115199  29340.8  29315.2
17424  20230816   000000    000959  1692115799  29315.1  29319.5
17425  20230816   001000    001959  1692116399  29319.5  29344.6
2023-08-16 00:20:08,968:INFO:pyemd2:main.py:127:handleKline:2217508: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}


## /root/FIL/strategy/similarity/log.txt ----- -----

127.0.0.1 - - [16/Aug/2023 00:00:04] "POST / HTTP/1.1" 200 -
2023-08-16 00:00:04,194:INFO:testStrategy:main.py:308:handleOrderFilled:2217133: handleOrderFilled: data=OrderType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'clientorderid': '42899F1692115203505I0L2', 'symbol': 'BTCUSDT', 'gatewayorderid': 1692115203934615, 'quantity': '36.082', 'price': '29315.1', 'stopprice': '0', 'ordertype': '', 'side': 'SELL', 'status': 'FILLED', 'positionside': 'SHORT', 'createtime': 1692115202618, 'updatetime': 1692115203934, 'tradetype': 'usdt', 'selfid': 42899, 'filltrades': [TradeType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'tradeid': 1692115203934, 'clientorderid': '42899F1692115203505I0L2', 'price': '29315.1', 'quantity': '36.082', 'commission': '1057.7474382', 'commissionasset': 'USDT', 'tradetime': 1692115203934, 'tradetype': 'usdt', 'gatetype': 'simulator', 'handletime': 1692115203934}], 'gatetype': 'simulator', 'handletime': 0}
127.0.0.1 - - [16/Aug/2023 00:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=13475 

self.closeSec=1692115799, self.tradeDate='20230816', self.openTime='000000', self.closeTime='000959', self.symbol='BTCUSDT', self.open='29315.1', self.close='29319.5'
2023-08-16 00:10:01,188:INFO:testStrategy:main.py:101:handleKline:2217133: self.closeSec=1692115799, self.tradeDate='20230816', self.openTime='000000', self.closeTime='000959',self.symbol='BTCUSDT',self.open='29315.1', self.close='29319.5'
2023-08-16 00:10:01,197:INFO:testStrategy:main.py:102:handleKline:2217133: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12236  20230815   232000    232959  1692113399  29358.9  29374.7
12237  20230815   233000    233959  1692113999  29374.7  29341.8
12238  20230815   234000    234959  1692114599    29342  29340.8
12239  20230815   235000    235959  1692115199  29340.8  29315.2
12240  20230816   000000    000959  1692115799  29315.1  29319.5
2023-08-16 00:10:01,197:INFO:testStrategy:main.py:103:handleKline:2217133: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False, 'isCorr': False}

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=13476 

self.closeSec=1692116399, self.tradeDate='20230816', self.openTime='001000', self.closeTime='001959', self.symbol='BTCUSDT', self.open='29319.5', self.close='29344.6'
127.0.0.1 - - [16/Aug/2023 00:20:04] "POST / HTTP/1.1" 200 -
2023-08-16 00:20:08,649:INFO:testStrategy:main.py:101:handleKline:2217133: self.closeSec=1692116399, self.tradeDate='20230816', self.openTime='001000', self.closeTime='001959',self.symbol='BTCUSDT',self.open='29319.5', self.close='29344.6'
2023-08-16 00:20:08,835:INFO:testStrategy:main.py:102:handleKline:2217133: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12237  20230815   233000    233959  1692113999  29374.7  29341.8
12238  20230815   234000    234959  1692114599    29342  29340.8
12239  20230815   235000    235959  1692115199  29340.8  29315.2
12240  20230816   000000    000959  1692115799  29315.1  29319.5
12241  20230816   001000    001959  1692116399  29319.5  29344.6
2023-08-16 00:20:08,845:INFO:testStrategy:main.py:103:handleKline:2217133: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False, 'isCorr': False}


## /root/FIL/strategy/sr_min/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=1, self.total=996015.990996, self.flagDict['side']='buy', self.tradeCount=1, self.count=26944
self.closeSec=1692116399, self.tradeDate='20230816', self.openTime='001500', self.closeTime='001959', self.symbol='BTCUSDT', self.open=29326.6, self.close=29344.7, self.high=29358.0, self.low=29314.6, self.vol=1374.953, self.amt=40339298.3781 
127.0.0.1 - - [16/Aug/2023 00:20:01] "POST / HTTP/1.1" 200 -
2023-08-16 00:20:06,715:INFO:sr_min:main.py:172:handleKline:2219263: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5759  20230815   235500    235959  ...         0.0        0.0       0
5760  20230816   000000    000459  ...         0.0        0.0       0
5761  20230816   000500    000959  ...         0.0        0.0       0
5762  20230816   001000    001459  ...         0.0        0.0       0
5763  20230816   001500    001959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-08-16 00:20:06,745:INFO:sr_min:main.py:175:handleKline:2219263: self.closeSec=1692116399, self.tradeDate='20230816', self.openTime='001500', self.closeTime='001959',self.symbol='BTCUSDT',self.open=29326.6, self.close=29344.7, self.high=29358.0, self.low=29314.6, self.vol=1374.953, self.amt=40339298.3781, ukdf['pct'].iloc[-1]=0.000617 , ukdf['amount'].iloc[-1]=40339298.3781, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5763, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '37.141', 'enterprice': '26844', 'countrevence': '0', 'unrealprofit': '92967.03427297143', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '29347.08376923', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=1
127.0.0.1 - - [16/Aug/2023 00:25:00] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=1, self.total=996015.990996, self.flagDict['side']='buy', self.tradeCount=1, self.count=26945
self.closeSec=1692116699, self.tradeDate='20230816', self.openTime='002000', self.closeTime='002459', self.symbol='BTCUSDT', self.open=29344.6, self.close=29354.1, self.high=29358.9, self.low=29336.4, self.vol=902.706, self.amt=26493229.7578 
2023-08-16 00:25:00,816:INFO:sr_min:main.py:172:handleKline:2219263: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5760  20230816   000000    000459  ...         0.0        0.0       0
5761  20230816   000500    000959  ...         0.0        0.0       0
5762  20230816   001000    001459  ...         0.0        0.0       0
5763  20230816   001500    001959  ...         0.0        0.0       0
5764  20230816   002000    002459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-08-16 00:25:00,816:INFO:sr_min:main.py:175:handleKline:2219263: self.closeSec=1692116699, self.tradeDate='20230816', self.openTime='002000', self.closeTime='002459',self.symbol='BTCUSDT',self.open=29344.6, self.close=29354.1, self.high=29358.9, self.low=29336.4, self.vol=902.706, self.amt=26493229.7578, ukdf['pct'].iloc[-1]=0.00032 , ukdf['amount'].iloc[-1]=26493229.7578, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5764, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '37.141', 'enterprice': '26844', 'countrevence': '0', 'unrealprofit': '93231.3382', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '29354.2', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=1


## /root/FIL/strategy/s_rsrs/log.txt ----- -----

723  20230815   120000    155959  1692086399  ...    723  0.000267 -1.136717    -1.0
724  20230815   160000    195959  1692100799  ...    724  0.000333 -1.132243    -1.0

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '51.388', 'enterprice': '29432.6', 'countrevence': '0', 'unrealprofit': '3879.794', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '29357.1', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-1, self.sign=-1
--handleKline--:  version='2.0.0', self.name='s_rsrs', self.symbol='BTCUSDT', interval='4h', intervalSec=14400, wid=25, thd=0.6, self.sign=-1, self.total=1510969.9663512, self.flagDict['side']='sell', self.tradeCount=20, self.count=561
self.closeSec=1692115199, self.tradeDate='20230815', self.openTime='200000', self.closeTime='235959', self.symbol='BTCUSDT', self.open=29357.1, self.close=29315.2, self.high=29492.1, self.low=29294.9, self.vol=46749.748, self.amt=1373551584.4309 
127.0.0.1 - - [16/Aug/2023 00:00:01] "POST / HTTP/1.1" 200 -
2023-08-16 00:00:01,639:INFO:s_rsrs:main.py:141:handleKline:2218689: self.closeSec=1692115199, self.tradeDate='20230815', self.openTime='200000', self.closeTime='235959',self.symbol='BTCUSDT',self.open=29357.1, self.close=29315.2, self.high=29492.1, self.low=29294.9, self.vol=46749.748, self.amt=1373551584.4309 
2023-08-16 00:00:01,654:INFO:s_rsrs:main.py:142:handleKline:2218689: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime  ...        vol           amt       pct
721  20230815   040000    075959  ...  17851.488  5.248545e+08  0.002238
722  20230815   080000    115959  ...  14493.260  4.260585e+08 -0.001108
723  20230815   120000    155959  ...  14399.120  4.229356e+08  0.000337
724  20230815   160000    195959  ...  22179.354  6.520325e+08 -0.001350
725  20230815   200000    235959  ...  46749.748  1.373552e+09 -0.001427

[5 rows x 11 columns]
2023-08-16 00:00:02,467:INFO:s_rsrs:main.py:151:handleKline:2218689: df_s.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec  ...  index      beta    zscore  signal
721  20230815   040000    075959  1692057599  ...    721  0.000146 -1.148049    -1.0
722  20230815   080000    115959  1692071999  ...    722  0.000251 -1.142154    -1.0
723  20230815   120000    155959  1692086399  ...    723  0.000267 -1.136717    -1.0
724  20230815   160000    195959  1692100799  ...    724  0.000333 -1.132243    -1.0
725  20230815   200000    235959  1692115199  ...    725  0.000410 -1.130170    -1.0

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '51.388', 'enterprice': '29432.6', 'countrevence': '0', 'unrealprofit': '5991.48418989072', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '29316.00693956', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-1, self.sign=-1


