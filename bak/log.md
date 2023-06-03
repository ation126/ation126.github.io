# 20230604 00:26:02

## /root/FIL/strategy/amihud/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=373746.4768026, self.flagDict['side']='sell', self.tradeCount=2, self.count=5920
self.closeSec=1685809199, self.tradeDate='20230604', self.openTime='001500', self.closeTime='001959', self.symbol='BTCUSDT', self.open=27249.0, self.close=27232.8, self.high=27249.0, self.low=27226.4, self.vol=686.387, self.amt=18693805.898 
127.0.0.1 - - [04/Jun/2023 00:20:01] "POST / HTTP/1.1" 200 -
2023-06-04 00:20:06,610:INFO:amihud:main.py:172:handleKline:2219019: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5759  20230603   235500    235959  ...         0.0        0.0       0
5760  20230604   000000    000459  ...         0.0        0.0       0
5761  20230604   000500    000959  ...         0.0        0.0       0
5762  20230604   001000    001459  ...         0.0        0.0       0
5763  20230604   001500    001959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-06-04 00:20:06,639:INFO:amihud:main.py:175:handleKline:2219019: self.closeSec=1685809199, self.tradeDate='20230604', self.openTime='001500', self.closeTime='001959',self.symbol='BTCUSDT',self.open=27249.0, self.close=27232.8, self.high=27249.0, self.low=27226.4, self.vol=686.387, self.amt=18693805.898, ukdf['pct'].iloc[-1]=-0.000591 , ukdf['amount'].iloc[-1]=18693805.898, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5763, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '13.926', 'enterprice': '26864.9', 'countrevence': '0', 'unrealprofit': '-5123.3754', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '27232.8', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1
127.0.0.1 - - [04/Jun/2023 00:25:00] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=373746.4768026, self.flagDict['side']='sell', self.tradeCount=2, self.count=5921
self.closeSec=1685809499, self.tradeDate='20230604', self.openTime='002000', self.closeTime='002459', self.symbol='BTCUSDT', self.open=27232.9, self.close=27274.4, self.high=27277.0, self.low=27232.8, self.vol=875.694, self.amt=23873152.0598 
2023-06-04 00:25:00,839:INFO:amihud:main.py:172:handleKline:2219019: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5760  20230604   000000    000459  ...         0.0        0.0       0
5761  20230604   000500    000959  ...         0.0        0.0       0
5762  20230604   001000    001459  ...         0.0        0.0       0
5763  20230604   001500    001959  ...         0.0        0.0       0
5764  20230604   002000    002459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-06-04 00:25:00,840:INFO:amihud:main.py:175:handleKline:2219019: self.closeSec=1685809499, self.tradeDate='20230604', self.openTime='002000', self.closeTime='002459',self.symbol='BTCUSDT',self.open=27232.9, self.close=27274.4, self.high=27277.0, self.low=27232.8, self.vol=875.694, self.amt=23873152.0598, ukdf['pct'].iloc[-1]=0.001528 , ukdf['amount'].iloc[-1]=23873152.0598, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5764, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '13.926', 'enterprice': '26864.9', 'countrevence': '0', 'unrealprofit': '-5719.7138499369', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '27275.62194815', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1


## /root/FIL/strategy/factorcheck/log.txt ----- -----


self.closeSec=1685809199, self.tradeDate='20230604', self.openTime='001500', self.closeTime='001959', self.symbol='BTCUSDT', self.open=27249.0, self.close=27232.8, self.high=27249.0, self.low=27226.4 
127.0.0.1 - - [04/Jun/2023 00:20:01] "POST / HTTP/1.1" 200 -
2023-06-04 00:20:04,479:INFO:factorcheck2:main.py:126:handleKline:2218005: self.closeSec=1685809199, self.tradeDate='20230604', self.openTime='001500', self.closeTime='001959',self.symbol='BTCUSDT',self.open=27249.0, self.close=27232.8, self.high=27249.0, self.low=27226.4   
2023-06-04 00:20:05,720:INFO:factorcheck2:main.py:127:handleKline:2218005: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1439  20230603   235500    235959  1685807999  ...  27212.1  0.002943   1727    5
1440  20230604   000000    000459  1685808299  ...  27250.6 -0.001660   1440    0
1441  20230604   000500    000959  1685808599  ...  27211.8 -0.001046   1441    1
1442  20230604   001000    001459  1685808899  ...  27215.0  0.000981   1442    2
1443  20230604   001500    001959  1685809199  ...  27226.4 -0.000591   1443    3

[5 rows x 11 columns]
2023-06-04 00:20:05,720:INFO:factorcheck2:main.py:128:handleKline:2218005: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=19, self.factor=0.34431959989874683, self.count=5923 

self.closeSec=1685809499, self.tradeDate='20230604', self.openTime='002000', self.closeTime='002459', self.symbol='BTCUSDT', self.open=27232.9, self.close=27274.4, self.high=27277.0, self.low=27232.8 
127.0.0.1 - - [04/Jun/2023 00:25:00] "POST / HTTP/1.1" 200 -
2023-06-04 00:25:00,719:INFO:factorcheck2:main.py:126:handleKline:2218005: self.closeSec=1685809499, self.tradeDate='20230604', self.openTime='002000', self.closeTime='002459',self.symbol='BTCUSDT',self.open=27232.9, self.close=27274.4, self.high=27277.0, self.low=27232.8   
2023-06-04 00:25:00,750:INFO:factorcheck2:main.py:127:handleKline:2218005: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1440  20230604   000000    000459  1685808299  ...  27250.6 -0.001660   1440    0
1441  20230604   000500    000959  1685808599  ...  27211.8 -0.001046   1441    1
1442  20230604   001000    001459  1685808899  ...  27215.0  0.000981   1442    2
1443  20230604   001500    001959  1685809199  ...  27226.4 -0.000591   1443    3
1444  20230604   002000    002459  1685809499  ...  27232.8  0.001528   1444    4

[5 rows x 11 columns]
2023-06-04 00:25:00,751:INFO:factorcheck2:main.py:128:handleKline:2218005: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}


## /root/FIL/strategy/logic/log.txt ----- -----

2023-06-04 00:00:35,247:DEBUG:logic:main.py:463:getModel:2218526: df_s.iloc[-5:,:] :
          date closeTime     open  ...    alpha58   alpha67   alpha72
5802  20230603    212959  27152.9  ...  47.083333  0.513005  0.359387
5803  20230603    215959  27145.5  ...  47.500000  0.516509  0.364486
5804  20230603    222959  27157.2  ...  47.916667  0.522184  0.365179
5805  20230603    225959  27175.7  ...  47.916667  0.516332  0.382117
5806  20230603    232959  27158.2  ...  48.333333  0.537889  0.375453

[5 rows x 33 columns]
0.5183823529411765
acc is : 0.5183823529411765
2023-06-04 00:00:35,441:INFO:logic:main.py:468:getModel:2218526: df_pred.iloc[-5:,:] :
     pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
539     1  0.499454  0.500546       1  ...  1.077999   1.0    0.0  0.994919
540     0  0.502434  0.497566       1  ...  1.078738   1.0    0.0  0.995600
541     0  0.506957  0.493043       0  ...  1.078039   1.0    0.0  0.994955
542     1  0.497235  0.502765       1  ...  1.080889   1.0    0.0  0.997586
543     0  0.517762  0.482238       1  ...  1.083382   1.0    0.0  0.999886

[5 rows x 10 columns]
2023-06-04 00:00:35,476:INFO:logic:main.py:478:getModel:2218526: df_panel.iloc[-5:,:] :
    pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
45     1  0.499741  0.500259       1  ...  1.037942   1.0    0.0  0.993020
46     0  0.502680  0.497320       1  ...  1.038653   1.0    0.0  0.996016
47     0  0.507168  0.492832       0  ...  1.037981   1.0    0.0  0.995371
48     1  0.497348  0.502652       1  ...  1.080889   1.0    0.0  0.999347
49     0  0.517762  0.482238       1  ...  1.083382   1.0    0.0  0.999886

[5 rows x 10 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '27.623', 'enterprice': '26988.6', 'countrevence': '0', 'unrealprofit': '8423.38022997796', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '27293.54081852', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}


## /root/FIL/strategy/modifiedmom/log.txt ----- -----

127.0.0.1 - - [04/Jun/2023 00:00:04] "POST / HTTP/1.1" 200 -
2023-06-04 00:00:04,554:INFO:modifiedmom:main.py:319:handleOrderFilled:2218259: handleOrderFilled: data=OrderType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'clientorderid': '42314F1685808003808I0L59', 'symbol': 'BTCUSDT', 'gatewayorderid': 1685808004206506, 'quantity': '25.095', 'price': '27296', 'stopprice': '0', 'ordertype': '', 'side': 'BUY', 'status': 'FILLED', 'positionside': 'LONG', 'createtime': 1685808002859, 'updatetime': 1685808004206, 'tradetype': 'usdt', 'selfid': 42314, 'filltrades': [TradeType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'tradeid': 1685808004206, 'clientorderid': '42314F1685808003808I0L59', 'price': '27296', 'quantity': '25.095', 'commission': '684.99312', 'commissionasset': 'USDT', 'tradetime': 1685808004206, 'tradetype': 'usdt', 'gatetype': 'simulator', 'handletime': 1685808004206}], 'gatetype': 'simulator', 'handletime': 0}
127.0.0.1 - - [04/Jun/2023 00:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=2960 

self.closeSec=1685808599, self.tradeDate='20230604', self.openTime='000000', self.closeTime='000959', self.symbol='BTCUSDT', self.open='27292.8', self.close='27222.1'
2023-06-04 00:10:01,143:INFO:modifiedmom:main.py:144:handleKline:2218259: self.closeSec=1685808599, self.tradeDate='20230604', self.openTime='000000', self.closeTime='000959',self.symbol='BTCUSDT',self.open='27292.8', self.close='27222.1'
2023-06-04 00:10:01,174:INFO:modifiedmom:main.py:145:handleKline:2218259: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
572  20230603   232000    232959  1685806199    27135  27229.9  0.003494
573  20230603   233000    233959  1685806799  27229.9  27202.9 -0.000992
574  20230603   234000    234959  1685807399  27202.9  27193.7 -0.000338
575  20230603   235000    235959  1685807999  27193.7  27292.7  0.003641
576  20230604   000000    000959  1685808599  27292.8  27222.1 -0.002587
2023-06-04 00:10:01,175:INFO:modifiedmom:main.py:146:handleKline:2218259: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=2961 

self.closeSec=1685809199, self.tradeDate='20230604', self.openTime='001000', self.closeTime='001959', self.symbol='BTCUSDT', self.open='27222.2', self.close='27232.8'
127.0.0.1 - - [04/Jun/2023 00:20:04] "POST / HTTP/1.1" 200 -
2023-06-04 00:20:06,989:INFO:modifiedmom:main.py:144:handleKline:2218259: self.closeSec=1685809199, self.tradeDate='20230604', self.openTime='001000', self.closeTime='001959',self.symbol='BTCUSDT',self.open='27222.2', self.close='27232.8'
2023-06-04 00:20:07,689:INFO:modifiedmom:main.py:145:handleKline:2218259: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
573  20230603   233000    233959  1685806799  27229.9  27202.9 -0.000992
574  20230603   234000    234959  1685807399  27202.9  27193.7 -0.000338
575  20230603   235000    235959  1685807999  27193.7  27292.7  0.003641
576  20230604   000000    000959  1685808599  27292.8  27222.1 -0.002587
577  20230604   001000    001959  1685809199  27222.2  27232.8  0.000393
2023-06-04 00:20:07,690:INFO:modifiedmom:main.py:146:handleKline:2218259: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False}


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

127.0.0.1 - - [04/Jun/2023 00:00:04] "POST / HTTP/1.1" 200 -
2023-06-04 00:00:04,714:INFO:pyemd2:main.py:303:handleOrderFilled:2217508: handleOrderFilled: data=OrderType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'clientorderid': '42315F1685808003834I0L57', 'symbol': 'BTCUSDT', 'gatewayorderid': 1685808004250513, 'quantity': '35.743', 'price': '27295.9', 'stopprice': '0', 'ordertype': '', 'side': 'SELL', 'status': 'FILLED', 'positionside': 'SHORT', 'createtime': 1685808002811, 'updatetime': 1685808004250, 'tradetype': 'usdt', 'selfid': 42315, 'filltrades': [TradeType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'tradeid': 1685808004250, 'clientorderid': '42315F1685808003834I0L57', 'price': '27295.9', 'quantity': '35.743', 'commission': '975.6373537', 'commissionasset': 'USDT', 'tradetime': 1685808004250, 'tradetype': 'usdt', 'gatetype': 'simulator', 'handletime': 1685808004250}], 'gatetype': 'simulator', 'handletime': 0}
127.0.0.1 - - [04/Jun/2023 00:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=2963 

self.closeSec=1685808599, self.tradeDate='20230604', self.openTime='000000', self.closeTime='000959', self.symbol='BTCUSDT', self.open='27292.8', self.close='27222.1'
2023-06-04 00:10:01,118:INFO:pyemd2:main.py:125:handleKline:2217508: self.closeSec=1685808599, self.tradeDate='20230604', self.openTime='000000', self.closeTime='000959',self.symbol='BTCUSDT',self.open='27292.8', self.close='27222.1'
2023-06-04 00:10:01,141:INFO:pyemd2:main.py:126:handleKline:2217508: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17420  20230603   232000    232959  1685806199    27135  27229.9
17421  20230603   233000    233959  1685806799  27229.9  27202.9
17422  20230603   234000    234959  1685807399  27202.9  27193.7
17423  20230603   235000    235959  1685807999  27193.7  27292.7
17424  20230604   000000    000959  1685808599  27292.8  27222.1
2023-06-04 00:10:01,141:INFO:pyemd2:main.py:127:handleKline:2217508: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=2964 

self.closeSec=1685809199, self.tradeDate='20230604', self.openTime='001000', self.closeTime='001959', self.symbol='BTCUSDT', self.open='27222.2', self.close='27232.8'
127.0.0.1 - - [04/Jun/2023 00:20:04] "POST / HTTP/1.1" 200 -
2023-06-04 00:20:08,451:INFO:pyemd2:main.py:125:handleKline:2217508: self.closeSec=1685809199, self.tradeDate='20230604', self.openTime='001000', self.closeTime='001959',self.symbol='BTCUSDT',self.open='27222.2', self.close='27232.8'
2023-06-04 00:20:08,566:INFO:pyemd2:main.py:126:handleKline:2217508: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17421  20230603   233000    233959  1685806799  27229.9  27202.9
17422  20230603   234000    234959  1685807399  27202.9  27193.7
17423  20230603   235000    235959  1685807999  27193.7  27292.7
17424  20230604   000000    000959  1685808599  27292.8  27222.1
17425  20230604   001000    001959  1685809199  27222.2  27232.8
2023-06-04 00:20:08,568:INFO:pyemd2:main.py:127:handleKline:2217508: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}


## /root/FIL/strategy/similarity/log.txt ----- -----

127.0.0.1 - - [04/Jun/2023 00:00:04] "POST / HTTP/1.1" 200 -
2023-06-04 00:00:04,351:INFO:testStrategy:main.py:308:handleOrderFilled:2217133: handleOrderFilled: data=OrderType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'clientorderid': '42313F1685808003693I0L2', 'symbol': 'BTCUSDT', 'gatewayorderid': 1685808004109273, 'quantity': '43.817', 'price': '27296', 'stopprice': '0', 'ordertype': '', 'side': 'BUY', 'status': 'FILLED', 'positionside': 'LONG', 'createtime': 1685808002795, 'updatetime': 1685808004109, 'tradetype': 'usdt', 'selfid': 42313, 'filltrades': [TradeType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'tradeid': 1685808004109, 'clientorderid': '42313F1685808003693I0L2', 'price': '27296', 'quantity': '43.817', 'commission': '1196.028832', 'commissionasset': 'USDT', 'tradetime': 1685808004109, 'tradetype': 'usdt', 'gatetype': 'simulator', 'handletime': 1685808004109}], 'gatetype': 'simulator', 'handletime': 0}

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=2963 

self.closeSec=1685808599, self.tradeDate='20230604', self.openTime='000000', self.closeTime='000959', self.symbol='BTCUSDT', self.open='27292.8', self.close='27222.1'
127.0.0.1 - - [04/Jun/2023 00:10:01] "POST / HTTP/1.1" 200 -
2023-06-04 00:10:01,129:INFO:testStrategy:main.py:101:handleKline:2217133: self.closeSec=1685808599, self.tradeDate='20230604', self.openTime='000000', self.closeTime='000959',self.symbol='BTCUSDT',self.open='27292.8', self.close='27222.1'
2023-06-04 00:10:01,142:INFO:testStrategy:main.py:102:handleKline:2217133: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12236  20230603   232000    232959  1685806199    27135  27229.9
12237  20230603   233000    233959  1685806799  27229.9  27202.9
12238  20230603   234000    234959  1685807399  27202.9  27193.7
12239  20230603   235000    235959  1685807999  27193.7  27292.7
12240  20230604   000000    000959  1685808599  27292.8  27222.1
2023-06-04 00:10:01,142:INFO:testStrategy:main.py:103:handleKline:2217133: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False, 'isCorr': False}

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=2964 

self.closeSec=1685809199, self.tradeDate='20230604', self.openTime='001000', self.closeTime='001959', self.symbol='BTCUSDT', self.open='27222.2', self.close='27232.8'
127.0.0.1 - - [04/Jun/2023 00:20:04] "POST / HTTP/1.1" 200 -
2023-06-04 00:20:08,211:INFO:testStrategy:main.py:101:handleKline:2217133: self.closeSec=1685809199, self.tradeDate='20230604', self.openTime='001000', self.closeTime='001959',self.symbol='BTCUSDT',self.open='27222.2', self.close='27232.8'
2023-06-04 00:20:08,420:INFO:testStrategy:main.py:102:handleKline:2217133: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12237  20230603   233000    233959  1685806799  27229.9  27202.9
12238  20230603   234000    234959  1685807399  27202.9  27193.7
12239  20230603   235000    235959  1685807999  27193.7  27292.7
12240  20230604   000000    000959  1685808599  27292.8  27222.1
12241  20230604   001000    001959  1685809199  27222.2  27232.8
2023-06-04 00:20:08,420:INFO:testStrategy:main.py:103:handleKline:2217133: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False, 'isCorr': False}


## /root/FIL/strategy/sr_min/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=1, self.total=996015.990996, self.flagDict['side']='buy', self.tradeCount=1, self.count=5920
self.closeSec=1685809199, self.tradeDate='20230604', self.openTime='001500', self.closeTime='001959', self.symbol='BTCUSDT', self.open=27249.0, self.close=27232.8, self.high=27249.0, self.low=27226.4, self.vol=686.387, self.amt=18693805.898 
127.0.0.1 - - [04/Jun/2023 00:20:01] "POST / HTTP/1.1" 200 -
2023-06-04 00:20:06,569:INFO:sr_min:main.py:172:handleKline:2219263: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5759  20230603   235500    235959  ...         0.0        0.0       0
5760  20230604   000000    000459  ...         0.0        0.0       0
5761  20230604   000500    000959  ...         0.0        0.0       0
5762  20230604   001000    001459  ...         0.0        0.0       0
5763  20230604   001500    001959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-06-04 00:20:06,593:INFO:sr_min:main.py:175:handleKline:2219263: self.closeSec=1685809199, self.tradeDate='20230604', self.openTime='001500', self.closeTime='001959',self.symbol='BTCUSDT',self.open=27249.0, self.close=27232.8, self.high=27249.0, self.low=27226.4, self.vol=686.387, self.amt=18693805.898, ukdf['pct'].iloc[-1]=-0.000591 , ukdf['amount'].iloc[-1]=18693805.898, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5763, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '37.141', 'enterprice': '26844', 'countrevence': '0', 'unrealprofit': '14440.4208', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '27232.8', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=1
127.0.0.1 - - [04/Jun/2023 00:25:00] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=1, self.total=996015.990996, self.flagDict['side']='buy', self.tradeCount=1, self.count=5921
self.closeSec=1685809499, self.tradeDate='20230604', self.openTime='002000', self.closeTime='002459', self.symbol='BTCUSDT', self.open=27232.9, self.close=27274.4, self.high=27277.0, self.low=27232.8, self.vol=875.694, self.amt=23873152.0598 
2023-06-04 00:25:00,819:INFO:sr_min:main.py:172:handleKline:2219263: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5760  20230604   000000    000459  ...         0.0        0.0       0
5761  20230604   000500    000959  ...         0.0        0.0       0
5762  20230604   001000    001459  ...         0.0        0.0       0
5763  20230604   001500    001959  ...         0.0        0.0       0
5764  20230604   002000    002459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-06-04 00:25:00,819:INFO:sr_min:main.py:175:handleKline:2219263: self.closeSec=1685809499, self.tradeDate='20230604', self.openTime='002000', self.closeTime='002459',self.symbol='BTCUSDT',self.open=27232.9, self.close=27274.4, self.high=27277.0, self.low=27232.8, self.vol=875.694, self.amt=23873152.0598, ukdf['pct'].iloc[-1]=0.001528 , ukdf['amount'].iloc[-1]=23873152.0598, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5764, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '37.141', 'enterprice': '26844', 'countrevence': '0', 'unrealprofit': '16030.87077623915', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '27275.62194815', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=1


## /root/FIL/strategy/s_rsrs/log.txt ----- -----

723  20230603   120000    155959  1685779199  ...    723  0.580259  0.077345     NaN
724  20230603   160000    195959  1685793599  ...    724  0.559322  0.006778     NaN

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '55.249', 'enterprice': '26128.2', 'countrevence': '0', 'unrealprofit': '54859.44897730986', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '27121.14917514', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-9223372036854775808, self.sign=1
127.0.0.1 - - [04/Jun/2023 00:00:01] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='s_rsrs', self.symbol='BTCUSDT', interval='4h', intervalSec=14400, wid=25, thd=0.6, self.sign=1, self.total=1442113.3648782002, self.flagDict['side']='buy', self.tradeCount=3, self.count=123
self.closeSec=1685807999, self.tradeDate='20230603', self.openTime='200000', self.closeTime='235959', self.symbol='BTCUSDT', self.open=27121.0, self.close=27292.7, self.high=27340.2, self.low=27110.0, self.vol=35777.121, self.amt=973189755.4638 
2023-06-04 00:00:01,815:INFO:s_rsrs:main.py:141:handleKline:2218689: self.closeSec=1685807999, self.tradeDate='20230603', self.openTime='200000', self.closeTime='235959',self.symbol='BTCUSDT',self.open=27121.0, self.close=27292.7, self.high=27340.2, self.low=27110.0, self.vol=35777.121, self.amt=973189755.4638 
2023-06-04 00:00:01,874:INFO:s_rsrs:main.py:142:handleKline:2218689: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime  ...        vol           amt       pct
721  20230603   040000    075959  ...  30013.032  8.167713e+08 -0.000140
722  20230603   080000    115959  ...  25058.623  6.803387e+08 -0.003559
723  20230603   120000    155959  ...  17689.692  4.803177e+08  0.001120
724  20230603   160000    195959  ...  16660.540  4.521462e+08 -0.001484
725  20230603   200000    235959  ...  35777.121  9.731898e+08  0.006331

[5 rows x 11 columns]
2023-06-04 00:00:04,001:INFO:s_rsrs:main.py:151:handleKline:2218689: df_s.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec  ...  index      beta    zscore  signal
721  20230603   040000    075959  1685750399  ...    721  0.642910  0.283739     NaN
722  20230603   080000    115959  1685764799  ...    722  0.629723  0.233845     NaN
723  20230603   120000    155959  1685779199  ...    723  0.580259  0.077345     NaN
724  20230603   160000    195959  1685793599  ...    724  0.559322  0.006778     NaN
725  20230603   200000    235959  1685807999  ...    725  0.472565 -0.261938     NaN

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '55.249', 'enterprice': '26128.2', 'countrevence': '0', 'unrealprofit': '64676.00734203444', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '27298.82765556', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-9223372036854775808, self.sign=1


