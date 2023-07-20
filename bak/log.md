# 20230721 00:26:01

## /root/FIL/strategy/amihud/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=373746.4768026, self.flagDict['side']='sell', self.tradeCount=2, self.count=19456
self.closeSec=1689869999, self.tradeDate='20230721', self.openTime='001500', self.closeTime='001959', self.symbol='BTCUSDT', self.open=29829.7, self.close=29776.0, self.high=29835.9, self.low=29773.4, self.vol=1331.007, self.amt=39665400.8048 
127.0.0.1 - - [21/Jul/2023 00:20:01] "POST / HTTP/1.1" 200 -
2023-07-21 00:20:05,519:INFO:amihud:main.py:172:handleKline:2219019: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5759  20230720   235500    235959  ...         0.0        0.0       0
5760  20230721   000000    000459  ...         0.0        0.0       0
5761  20230721   000500    000959  ...         0.0        0.0       0
5762  20230721   001000    001459  ...         0.0        0.0       0
5763  20230721   001500    001959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-07-21 00:20:05,549:INFO:amihud:main.py:175:handleKline:2219019: self.closeSec=1689869999, self.tradeDate='20230721', self.openTime='001500', self.closeTime='001959',self.symbol='BTCUSDT',self.open=29829.7, self.close=29776.0, self.high=29835.9, self.low=29773.4, self.vol=1331.007, self.amt=39665400.8048, ukdf['pct'].iloc[-1]=-0.00175 , ukdf['amount'].iloc[-1]=39665400.8048, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5763, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '13.926', 'enterprice': '26864.9', 'countrevence': '0', 'unrealprofit': '-40656.957', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '29784.4', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1
--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=373746.4768026, self.flagDict['side']='sell', self.tradeCount=2, self.count=19457
self.closeSec=1689870299, self.tradeDate='20230721', self.openTime='002000', self.closeTime='002459', self.symbol='BTCUSDT', self.open=29776.0, self.close=29739.9, self.high=29798.3, self.low=29722.0, self.vol=4628.731, self.amt=137710946.6261 
127.0.0.1 - - [21/Jul/2023 00:25:00] "POST / HTTP/1.1" 200 -
2023-07-21 00:25:00,805:INFO:amihud:main.py:172:handleKline:2219019: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5760  20230721   000000    000459  ...         0.0        0.0       0
5761  20230721   000500    000959  ...         0.0        0.0       0
5762  20230721   001000    001459  ...         0.0        0.0       0
5763  20230721   001500    001959  ...         0.0        0.0       0
5764  20230721   002000    002459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-07-21 00:25:00,805:INFO:amihud:main.py:175:handleKline:2219019: self.closeSec=1689870299, self.tradeDate='20230721', self.openTime='002000', self.closeTime='002459',self.symbol='BTCUSDT',self.open=29776.0, self.close=29739.9, self.high=29798.3, self.low=29722.0, self.vol=4628.731, self.amt=137710946.6261, ukdf['pct'].iloc[-1]=-0.001212 , ukdf['amount'].iloc[-1]=137710946.6261, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5764, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '13.926', 'enterprice': '26864.9', 'countrevence': '0', 'unrealprofit': '-40037.25', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '29739.9', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1


## /root/FIL/strategy/factorcheck/log.txt ----- -----


self.closeSec=1689869999, self.tradeDate='20230721', self.openTime='001500', self.closeTime='001959', self.symbol='BTCUSDT', self.open=29829.7, self.close=29776.0, self.high=29835.9, self.low=29773.4 
127.0.0.1 - - [21/Jul/2023 00:20:01] "POST / HTTP/1.1" 200 -
2023-07-21 00:20:03,929:INFO:factorcheck2:main.py:126:handleKline:2218005: self.closeSec=1689869999, self.tradeDate='20230721', self.openTime='001500', self.closeTime='001959',self.symbol='BTCUSDT',self.open=29829.7, self.close=29776.0, self.high=29835.9, self.low=29773.4   
2023-07-21 00:20:04,909:INFO:factorcheck2:main.py:127:handleKline:2218005: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1439  20230720   235500    235959  1689868799  ...  29758.0  0.001038   1727    5
1440  20230721   000000    000459  1689869099  ...  29755.9  0.000702   1440    0
1441  20230721   000500    000959  1689869399  ...  29803.2  0.001030   1441    1
1442  20230721   001000    001459  1689869699  ...  29819.8 -0.000543   1442    2
1443  20230721   001500    001959  1689869999  ...  29773.4 -0.001750   1443    3

[5 rows x 11 columns]
2023-07-21 00:20:04,909:INFO:factorcheck2:main.py:128:handleKline:2218005: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}
127.0.0.1 - - [21/Jul/2023 00:25:00] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=28, self.factor=0.40878157876926413, self.count=19459 

self.closeSec=1689870299, self.tradeDate='20230721', self.openTime='002000', self.closeTime='002459', self.symbol='BTCUSDT', self.open=29776.0, self.close=29739.9, self.high=29798.3, self.low=29722.0 
2023-07-21 00:25:00,773:INFO:factorcheck2:main.py:126:handleKline:2218005: self.closeSec=1689870299, self.tradeDate='20230721', self.openTime='002000', self.closeTime='002459',self.symbol='BTCUSDT',self.open=29776.0, self.close=29739.9, self.high=29798.3, self.low=29722.0   
2023-07-21 00:25:00,787:INFO:factorcheck2:main.py:127:handleKline:2218005: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1440  20230721   000000    000459  1689869099  ...  29755.9  0.000702   1440    0
1441  20230721   000500    000959  1689869399  ...  29803.2  0.001030   1441    1
1442  20230721   001000    001459  1689869699  ...  29819.8 -0.000543   1442    2
1443  20230721   001500    001959  1689869999  ...  29773.4 -0.001750   1443    3
1444  20230721   002000    002459  1689870299  ...  29722.0 -0.001212   1444    4

[5 rows x 11 columns]
2023-07-21 00:25:00,788:INFO:factorcheck2:main.py:128:handleKline:2218005: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}


## /root/FIL/strategy/logic/log.txt ----- -----

2023-07-21 00:00:18,829:DEBUG:logic:main.py:463:getModel:2218526: df_s.iloc[-5:,:] :
          date closeTime     open  ...    alpha58   alpha67   alpha72
5802  20230720    212959  30210.6  ...  50.833333  0.543747  0.279100
5803  20230720    215959  30219.7  ...  50.416667  0.542682  0.282836
5804  20230720    222959  30215.9  ...  50.416667  0.513027  0.298354
5805  20230720    225959  30106.0  ...  50.416667  0.437678  0.331577
5806  20230720    232959  29766.7  ...  50.416667  0.452125  0.357732

[5 rows x 33 columns]
0.5073529411764706
acc is : 0.5073529411764706
2023-07-21 00:00:18,893:INFO:logic:main.py:468:getModel:2218526: df_pred.iloc[-5:,:] :
     pred    prob_0    prob_1  actual  ...       nav  sign   cost_        bm
539     0  0.500222  0.499778       0  ...  0.941770   1.0  0.0000  0.998873
540     1  0.498568  0.501432       0  ...  0.938344   1.0  0.0000  0.995240
541     1  0.460351  0.539649       0  ...  0.927769   1.0  0.0000  0.984023
542     1  0.372660  0.627340       1  ...  0.924424  -1.0 -0.0016  0.985997
543     1  0.477868  0.522132       0  ...  0.925465  -1.0  0.0000  0.984886

[5 rows x 10 columns]
2023-07-21 00:00:18,904:INFO:logic:main.py:478:getModel:2218526: df_panel.iloc[-5:,:] :
    pred    prob_0    prob_1  actual  ...       nav  sign   cost_        bm
45     0  0.500512  0.499488       0  ...  0.941770   1.0  0.0000  0.999246
46     1  0.498511  0.501489       0  ...  0.938344   1.0  0.0000  0.995496
47     1  0.460402  0.539598       0  ...  0.927769   1.0  0.0000  0.984277
48     1  0.372432  0.627568       1  ...  0.912307  -1.0 -0.0016  0.985961
49     1  0.477868  0.522132       0  ...  0.925465  -1.0  0.0000  0.984886

[5 rows x 10 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '23.511', 'enterprice': '29815.1', 'countrevence': '0', 'unrealprofit': '771.34966315767', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '29782.29196703', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}


## /root/FIL/strategy/modifiedmom/log.txt ----- -----

127.0.0.1 - - [21/Jul/2023 00:00:04] "POST / HTTP/1.1" 200 -
2023-07-21 00:00:04,187:INFO:modifiedmom:main.py:319:handleOrderFilled:2218259: handleOrderFilled: data=OrderType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'clientorderid': '42700F1689868803496I0L59', 'symbol': 'BTCUSDT', 'gatewayorderid': 1689868803928756, 'quantity': '24.781', 'price': '29792.9', 'stopprice': '0', 'ordertype': '', 'side': 'BUY', 'status': 'FILLED', 'positionside': 'LONG', 'createtime': 1689868802622, 'updatetime': 1689868803928, 'tradetype': 'usdt', 'selfid': 42700, 'filltrades': [TradeType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'tradeid': 1689868803928, 'clientorderid': '42700F1689868803496I0L59', 'price': '29792.9', 'quantity': '24.781', 'commission': '738.2978549', 'commissionasset': 'USDT', 'tradetime': 1689868803928, 'tradetype': 'usdt', 'gatetype': 'simulator', 'handletime': 1689868803928}], 'gatetype': 'simulator', 'handletime': 0}

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=9728 

self.closeSec=1689869399, self.tradeDate='20230721', self.openTime='000000', self.closeTime='000959', self.symbol='BTCUSDT', self.open='29792.9', self.close='29844.4'
127.0.0.1 - - [21/Jul/2023 00:10:01] "POST / HTTP/1.1" 200 -
2023-07-21 00:10:01,162:INFO:modifiedmom:main.py:144:handleKline:2218259: self.closeSec=1689869399, self.tradeDate='20230721', self.openTime='000000', self.closeTime='000959',self.symbol='BTCUSDT',self.open='29792.9', self.close='29844.4'
2023-07-21 00:10:01,170:INFO:modifiedmom:main.py:145:handleKline:2218259: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
572  20230720   232000    232959  1689866999  29805.8  29826.4  0.000691
573  20230720   233000    233959  1689867599  29826.4  29800.8 -0.000858
574  20230720   234000    234959  1689868199  29800.9  29780.1 -0.000695
575  20230720   235000    235959  1689868799    29780  29792.8  0.000426
576  20230721   000000    000959  1689869399  29792.9  29844.4  0.001732
2023-07-21 00:10:01,171:INFO:modifiedmom:main.py:146:handleKline:2218259: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=9729 

self.closeSec=1689869999, self.tradeDate='20230721', self.openTime='001000', self.closeTime='001959', self.symbol='BTCUSDT', self.open='29844', self.close='29776'
127.0.0.1 - - [21/Jul/2023 00:20:04] "POST / HTTP/1.1" 200 -
2023-07-21 00:20:06,239:INFO:modifiedmom:main.py:144:handleKline:2218259: self.closeSec=1689869999, self.tradeDate='20230721', self.openTime='001000', self.closeTime='001959',self.symbol='BTCUSDT',self.open='29844', self.close='29776'
2023-07-21 00:20:06,810:INFO:modifiedmom:main.py:145:handleKline:2218259: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
573  20230720   233000    233959  1689867599  29826.4  29800.8 -0.000858
574  20230720   234000    234959  1689868199  29800.9  29780.1 -0.000695
575  20230720   235000    235959  1689868799    29780  29792.8  0.000426
576  20230721   000000    000959  1689869399  29792.9  29844.4  0.001732
577  20230721   001000    001959  1689869999    29844    29776 -0.002292
2023-07-21 00:20:06,810:INFO:modifiedmom:main.py:146:handleKline:2218259: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False}


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

2023-07-21 00:00:02,124:INFO:pyemd2:main.py:127:handleKline:2217508: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}
2023-07-21 00:00:02,174:INFO:pyemd2:main.py:190:insertFactor:2217508: curDateTime:7210000, name:pyemd2, symbol:BTCUSDT, tradeDate:20230720, closeTime:235959, close:29792.8, total:1009051.1255403, pct_pre:0.012939458834613449, thd:-0.23599617591756272, side:sell 

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=9731 

self.closeSec=1689869399, self.tradeDate='20230721', self.openTime='000000', self.closeTime='000959', self.symbol='BTCUSDT', self.open='29792.9', self.close='29844.4'
127.0.0.1 - - [21/Jul/2023 00:10:01] "POST / HTTP/1.1" 200 -
2023-07-21 00:10:01,171:INFO:pyemd2:main.py:125:handleKline:2217508: self.closeSec=1689869399, self.tradeDate='20230721', self.openTime='000000', self.closeTime='000959',self.symbol='BTCUSDT',self.open='29792.9', self.close='29844.4'
2023-07-21 00:10:01,177:INFO:pyemd2:main.py:126:handleKline:2217508: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17420  20230720   232000    232959  1689866999  29805.8  29826.4
17421  20230720   233000    233959  1689867599  29826.4  29800.8
17422  20230720   234000    234959  1689868199  29800.9  29780.1
17423  20230720   235000    235959  1689868799    29780  29792.8
17424  20230721   000000    000959  1689869399  29792.9  29844.4
2023-07-21 00:10:01,177:INFO:pyemd2:main.py:127:handleKline:2217508: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=9732 

self.closeSec=1689869999, self.tradeDate='20230721', self.openTime='001000', self.closeTime='001959', self.symbol='BTCUSDT', self.open='29844', self.close='29776'
127.0.0.1 - - [21/Jul/2023 00:20:04] "POST / HTTP/1.1" 200 -
2023-07-21 00:20:07,438:INFO:pyemd2:main.py:125:handleKline:2217508: self.closeSec=1689869999, self.tradeDate='20230721', self.openTime='001000', self.closeTime='001959',self.symbol='BTCUSDT',self.open='29844', self.close='29776'
2023-07-21 00:20:07,632:INFO:pyemd2:main.py:126:handleKline:2217508: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17421  20230720   233000    233959  1689867599  29826.4  29800.8
17422  20230720   234000    234959  1689868199  29800.9  29780.1
17423  20230720   235000    235959  1689868799    29780  29792.8
17424  20230721   000000    000959  1689869399  29792.9  29844.4
17425  20230721   001000    001959  1689869999    29844    29776
2023-07-21 00:20:07,632:INFO:pyemd2:main.py:127:handleKline:2217508: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}


## /root/FIL/strategy/similarity/log.txt ----- -----

127.0.0.1 - - [21/Jul/2023 00:00:04] "POST / HTTP/1.1" 200 -
2023-07-21 00:00:04,065:INFO:testStrategy:main.py:308:handleOrderFilled:2217133: handleOrderFilled: data=OrderType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'clientorderid': '42701F1689868803529I0L2', 'symbol': 'BTCUSDT', 'gatewayorderid': 1689868803897615, 'quantity': '38.038', 'price': '29792.8', 'stopprice': '0', 'ordertype': '', 'side': 'SELL', 'status': 'FILLED', 'positionside': 'SHORT', 'createtime': 1689868802641, 'updatetime': 1689868803897, 'tradetype': 'usdt', 'selfid': 42701, 'filltrades': [TradeType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'tradeid': 1689868803897, 'clientorderid': '42701F1689868803529I0L2', 'price': '29792.8', 'quantity': '38.038', 'commission': '1133.2585264', 'commissionasset': 'USDT', 'tradetime': 1689868803897, 'tradetype': 'usdt', 'gatetype': 'simulator', 'handletime': 1689868803897}], 'gatetype': 'simulator', 'handletime': 0}

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=9731 

self.closeSec=1689869399, self.tradeDate='20230721', self.openTime='000000', self.closeTime='000959', self.symbol='BTCUSDT', self.open='29792.9', self.close='29844.4'
127.0.0.1 - - [21/Jul/2023 00:10:01] "POST / HTTP/1.1" 200 -
2023-07-21 00:10:01,168:INFO:testStrategy:main.py:101:handleKline:2217133: self.closeSec=1689869399, self.tradeDate='20230721', self.openTime='000000', self.closeTime='000959',self.symbol='BTCUSDT',self.open='29792.9', self.close='29844.4'
2023-07-21 00:10:01,177:INFO:testStrategy:main.py:102:handleKline:2217133: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12236  20230720   232000    232959  1689866999  29805.8  29826.4
12237  20230720   233000    233959  1689867599  29826.4  29800.8
12238  20230720   234000    234959  1689868199  29800.9  29780.1
12239  20230720   235000    235959  1689868799    29780  29792.8
12240  20230721   000000    000959  1689869399  29792.9  29844.4
2023-07-21 00:10:01,177:INFO:testStrategy:main.py:103:handleKline:2217133: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False, 'isCorr': False}

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=9732 

self.closeSec=1689869999, self.tradeDate='20230721', self.openTime='001000', self.closeTime='001959', self.symbol='BTCUSDT', self.open='29844', self.close='29776'
127.0.0.1 - - [21/Jul/2023 00:20:04] "POST / HTTP/1.1" 200 -
2023-07-21 00:20:07,294:INFO:testStrategy:main.py:101:handleKline:2217133: self.closeSec=1689869999, self.tradeDate='20230721', self.openTime='001000', self.closeTime='001959',self.symbol='BTCUSDT',self.open='29844', self.close='29776'
2023-07-21 00:20:07,529:INFO:testStrategy:main.py:102:handleKline:2217133: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12237  20230720   233000    233959  1689867599  29826.4  29800.8
12238  20230720   234000    234959  1689868199  29800.9  29780.1
12239  20230720   235000    235959  1689868799    29780  29792.8
12240  20230721   000000    000959  1689869399  29792.9  29844.4
12241  20230721   001000    001959  1689869999    29844    29776
2023-07-21 00:20:07,530:INFO:testStrategy:main.py:103:handleKline:2217133: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False, 'isCorr': False}


## /root/FIL/strategy/sr_min/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=1, self.total=996015.990996, self.flagDict['side']='buy', self.tradeCount=1, self.count=19456
self.closeSec=1689869999, self.tradeDate='20230721', self.openTime='001500', self.closeTime='001959', self.symbol='BTCUSDT', self.open=29829.7, self.close=29776.0, self.high=29835.9, self.low=29773.4, self.vol=1331.007, self.amt=39665400.8048 
127.0.0.1 - - [21/Jul/2023 00:20:01] "POST / HTTP/1.1" 200 -
2023-07-21 00:20:05,519:INFO:sr_min:main.py:172:handleKline:2219263: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5759  20230720   235500    235959  ...         0.0        0.0       0
5760  20230721   000000    000459  ...         0.0        0.0       0
5761  20230721   000500    000959  ...         0.0        0.0       0
5762  20230721   001000    001459  ...         0.0        0.0       0
5763  20230721   001500    001959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-07-21 00:20:05,540:INFO:sr_min:main.py:175:handleKline:2219263: self.closeSec=1689869999, self.tradeDate='20230721', self.openTime='001500', self.closeTime='001959',self.symbol='BTCUSDT',self.open=29829.7, self.close=29776.0, self.high=29835.9, self.low=29773.4, self.vol=1331.007, self.amt=39665400.8048, ukdf['pct'].iloc[-1]=-0.00175 , ukdf['amount'].iloc[-1]=39665400.8048, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5763, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '37.141', 'enterprice': '26844', 'countrevence': '0', 'unrealprofit': '109209.3964', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '29784.4', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=1
--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=1, self.total=996015.990996, self.flagDict['side']='buy', self.tradeCount=1, self.count=19457
self.closeSec=1689870299, self.tradeDate='20230721', self.openTime='002000', self.closeTime='002459', self.symbol='BTCUSDT', self.open=29776.0, self.close=29739.9, self.high=29798.3, self.low=29722.0, self.vol=4628.731, self.amt=137710946.6261 
127.0.0.1 - - [21/Jul/2023 00:25:00] "POST / HTTP/1.1" 200 -
2023-07-21 00:25:00,808:INFO:sr_min:main.py:172:handleKline:2219263: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5760  20230721   000000    000459  ...         0.0        0.0       0
5761  20230721   000500    000959  ...         0.0        0.0       0
5762  20230721   001000    001459  ...         0.0        0.0       0
5763  20230721   001500    001959  ...         0.0        0.0       0
5764  20230721   002000    002459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-07-21 00:25:00,809:INFO:sr_min:main.py:175:handleKline:2219263: self.closeSec=1689870299, self.tradeDate='20230721', self.openTime='002000', self.closeTime='002459',self.symbol='BTCUSDT',self.open=29776.0, self.close=29739.9, self.high=29798.3, self.low=29722.0, self.vol=4628.731, self.amt=137710946.6261, ukdf['pct'].iloc[-1]=-0.001212 , ukdf['amount'].iloc[-1]=137710946.6261, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5764, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '37.141', 'enterprice': '26844', 'countrevence': '0', 'unrealprofit': '107556.6219', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '29739.9', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=1


## /root/FIL/strategy/s_rsrs/log.txt ----- -----

723  20230720   120000    155959  1689839999  ...    723  0.212172 -0.948531    -1.0
724  20230720   160000    195959  1689854399  ...    724  0.230542 -0.849614    -1.0

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '52.176', 'enterprice': '29870.6', 'countrevence': '0', 'unrealprofit': '-20948.664', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '30272.1', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-1, self.sign=-1
127.0.0.1 - - [21/Jul/2023 00:00:01] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='s_rsrs', self.symbol='BTCUSDT', interval='4h', intervalSec=14400, wid=25, thd=0.6, self.sign=-1, self.total=1556969.8971744, self.flagDict['side']='sell', self.tradeCount=12, self.count=405
self.closeSec=1689868799, self.tradeDate='20230720', self.openTime='200000', self.closeTime='235959', self.symbol='BTCUSDT', self.open=30274.0, self.close=29792.8, self.high=30302.9, self.low=29600.0, self.vol=146334.281, self.amt=4377740188.12032 
2023-07-21 00:00:01,734:INFO:s_rsrs:main.py:141:handleKline:2218689: self.closeSec=1689868799, self.tradeDate='20230720', self.openTime='200000', self.closeTime='235959',self.symbol='BTCUSDT',self.open=30274.0, self.close=29792.8, self.high=30302.9, self.low=29600.0, self.vol=146334.281, self.amt=4377740188.12032 
2023-07-21 00:00:01,753:INFO:s_rsrs:main.py:142:handleKline:2218689: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime  ...         vol           amt       pct
721  20230720   040000    075959  ...   33370.022  9.980314e+08 -0.004558
722  20230720   080000    115959  ...   23383.135  7.005775e+08  0.001388
723  20230720   120000    155959  ...   54428.275  1.638943e+09  0.008638
724  20230720   160000    195959  ...   79217.962  2.400256e+09  0.002596
725  20230720   200000    235959  ...  146334.281  4.377740e+09 -0.015895

[5 rows x 11 columns]
2023-07-21 00:00:02,507:INFO:s_rsrs:main.py:151:handleKline:2218689: df_s.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec  ...  index      beta    zscore  signal
721  20230720   040000    075959  1689811199  ...    721  0.205868 -1.016732    -1.0
722  20230720   080000    115959  1689825599  ...    722  0.220827 -0.931568    -1.0
723  20230720   120000    155959  1689839999  ...    723  0.212172 -0.948531    -1.0
724  20230720   160000    195959  1689854399  ...    724  0.230542 -0.849614    -1.0
725  20230720   200000    235959  1689868799  ...    725  0.143075 -1.207132    -1.0

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '52.176', 'enterprice': '29870.6', 'countrevence': '0', 'unrealprofit': '3977.7347360688', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '29794.3631337', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-1, self.sign=-1


