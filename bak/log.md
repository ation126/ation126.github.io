# 20230403 00:26:02

## /root/FIL/strategy/amihud/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=993672.4896432, self.flagDict['side']='sell', self.tradeCount=2, self.count=36412
self.closeSec=1680452399, self.tradeDate='20230403', self.openTime='001500', self.closeTime='001959', self.symbol='BTCUSDT', self.open=28122.0, self.close=28069.9, self.high=28122.2, self.low=28050.0, self.vol=2354.638, self.amt=66097879.1644 
127.0.0.1 - - [03/Apr/2023 00:20:04] "POST / HTTP/1.1" 200 -
2023-04-03 00:20:09,665:INFO:amihud:main.py:172:handleKline:200676: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5759  20230402   235500    235959  ...         0.0        0.0       0
5760  20230403   000000    000459  ...         0.0        0.0       0
5761  20230403   000500    000959  ...         0.0        0.0       0
5762  20230403   001000    001459  ...         0.0        0.0       0
5763  20230403   001500    001959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-04-03 00:20:09,676:INFO:amihud:main.py:175:handleKline:200676: self.closeSec=1680452399, self.tradeDate='20230403', self.openTime='001500', self.closeTime='001959',self.symbol='BTCUSDT',self.open=28122.0, self.close=28069.9, self.high=28122.2, self.low=28050.0, self.vol=2354.638, self.amt=66097879.1644, ukdf['pct'].iloc[-1]=-0.001856 , ukdf['amount'].iloc[-1]=66097879.1644, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5763, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '60.176', 'enterprice': '16529.3', 'countrevence': '0', 'unrealprofit': '-693728.26885283776', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '28057.62140476', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1
--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=993672.4896432, self.flagDict['side']='sell', self.tradeCount=2, self.count=36413
self.closeSec=1680452699, self.tradeDate='20230403', self.openTime='002000', self.closeTime='002459', self.symbol='BTCUSDT', self.open=28070.0, self.close=28039.3, self.high=28106.4, self.low=27981.0, self.vol=4616.787, self.amt=129455296.7753 
127.0.0.1 - - [03/Apr/2023 00:25:01] "POST / HTTP/1.1" 200 -
2023-04-03 00:25:01,591:INFO:amihud:main.py:172:handleKline:200676: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5760  20230403   000000    000459  ...         0.0        0.0       0
5761  20230403   000500    000959  ...         0.0        0.0       0
5762  20230403   001000    001459  ...         0.0        0.0       0
5763  20230403   001500    001959  ...         0.0        0.0       0
5764  20230403   002000    002459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-04-03 00:25:01,593:INFO:amihud:main.py:175:handleKline:200676: self.closeSec=1680452699, self.tradeDate='20230403', self.openTime='002000', self.closeTime='002459',self.symbol='BTCUSDT',self.open=28070.0, self.close=28039.3, self.high=28106.4, self.low=27981.0, self.vol=4616.787, self.amt=129455296.7753, ukdf['pct'].iloc[-1]=-0.00109 , ukdf['amount'].iloc[-1]=129455296.7753, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5764, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '60.176', 'enterprice': '16529.3', 'countrevence': '0', 'unrealprofit': '-692667.8832', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '28040', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1


## /root/FIL/strategy/factorcheck/log.txt ----- -----


self.closeSec=1680452399, self.tradeDate='20230403', self.openTime='001500', self.closeTime='001959', self.symbol='BTCUSDT', self.open=28122.0, self.close=28069.9, self.high=28122.2, self.low=28050.0 
127.0.0.1 - - [03/Apr/2023 00:20:03] "POST / HTTP/1.1" 200 -
2023-04-03 00:20:06,956:INFO:factorcheck2:main.py:126:handleKline:185239: self.closeSec=1680452399, self.tradeDate='20230403', self.openTime='001500', self.closeTime='001959',self.symbol='BTCUSDT',self.open=28122.0, self.close=28069.9, self.high=28122.2, self.low=28050.0   
2023-04-03 00:20:08,086:INFO:factorcheck2:main.py:127:handleKline:185239: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1439  20230402   235500    235959  1680451199  ...  28055.2  0.001607   1727    5
1440  20230403   000000    000459  1680451499  ...  28083.1 -0.000637   1440    0
1441  20230403   000500    000959  1680451799  ...  28088.7  0.001168   1441    1
1442  20230403   001000    001459  1680452099  ...  28101.7 -0.000107   1442    2
1443  20230403   001500    001959  1680452399  ...  28050.0 -0.001856   1443    3

[5 rows x 11 columns]
2023-04-03 00:20:08,095:INFO:factorcheck2:main.py:128:handleKline:185239: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}
127.0.0.1 - - [03/Apr/2023 00:25:01] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=53, self.factor=0.5746020052362315, self.count=36979 

self.closeSec=1680452699, self.tradeDate='20230403', self.openTime='002000', self.closeTime='002459', self.symbol='BTCUSDT', self.open=28070.0, self.close=28039.3, self.high=28106.4, self.low=27981.0 
2023-04-03 00:25:01,540:INFO:factorcheck2:main.py:126:handleKline:185239: self.closeSec=1680452699, self.tradeDate='20230403', self.openTime='002000', self.closeTime='002459',self.symbol='BTCUSDT',self.open=28070.0, self.close=28039.3, self.high=28106.4, self.low=27981.0   
2023-04-03 00:25:01,589:INFO:factorcheck2:main.py:127:handleKline:185239: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1440  20230403   000000    000459  1680451499  ...  28083.1 -0.000637   1440    0
1441  20230403   000500    000959  1680451799  ...  28088.7  0.001168   1441    1
1442  20230403   001000    001459  1680452099  ...  28101.7 -0.000107   1442    2
1443  20230403   001500    001959  1680452399  ...  28050.0 -0.001856   1443    3
1444  20230403   002000    002459  1680452699  ...  27981.0 -0.001090   1444    4

[5 rows x 11 columns]
2023-04-03 00:25:01,589:INFO:factorcheck2:main.py:128:handleKline:185239: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}


## /root/FIL/strategy/logic/log.txt ----- -----

2023-04-03 00:00:32,457:DEBUG:logic:main.py:463:getModel:885513: df_s.iloc[-5:,:] :
          date closeTime     open  ...    alpha58   alpha67   alpha72
5802  20230402    212959  28255.1  ...  52.500000  0.472060  0.555249
5803  20230402    215959  28247.7  ...  52.916667  0.478025  0.562165
5804  20230402    222959  28271.9  ...  52.916667  0.485422  0.564592
5805  20230402    225959  28299.7  ...  52.916667  0.475141  0.572884
5806  20230402    232959  28258.1  ...  52.500000  0.436773  0.593293

[5 rows x 33 columns]
0.5257352941176471
acc is : 0.5257352941176471
2023-04-03 00:00:32,624:INFO:logic:main.py:468:getModel:885513: df_pred.iloc[-5:,:] :
     pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
539     0  0.513062  0.486938       1  ...  0.937701   1.0    0.0  1.006537
540     0  0.519426  0.480574       1  ...  0.938624   1.0    0.0  1.007526
541     0  0.524427  0.475573       0  ...  0.937244   1.0    0.0  1.006045
542     0  0.512664  0.487336       0  ...  0.931635   1.0    0.0  1.000025
543     1  0.481342  0.518658       1  ...  0.932342   1.0    0.0  1.000783

[5 rows x 10 columns]
2023-04-03 00:00:32,660:INFO:logic:main.py:478:getModel:885513: df_panel.iloc[-5:,:] :
    pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
45     0  0.513729  0.486271       1  ...  0.937398   1.0    0.0  1.004213
46     0  0.519964  0.480036       1  ...  0.938320   1.0    0.0  1.003931
47     0  0.524494  0.475506       0  ...  0.937244   1.0    0.0  1.002455
48     0  0.512063  0.487937       0  ...  0.920779   1.0    0.0  0.996449
49     1  0.481342  0.518658       1  ...  0.932342   1.0    0.0  1.000783

[5 rows x 10 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': []}


## /root/FIL/strategy/modifiedmom/log.txt ----- -----

127.0.0.1 - - [03/Apr/2023 00:00:03] "POST / HTTP/1.1" 200 -
2023-04-03 00:00:03,239:INFO:modifiedmom:main.py:319:handleOrderFilled:185213: handleOrderFilled: data=OrderType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'clientorderid': '42102F1680451202580I0L59', 'symbol': 'BTCUSDT', 'gatewayorderid': 1680451202819500, 'quantity': '25.257', 'price': '28110.1', 'stopprice': '0', 'ordertype': '', 'side': 'SELL', 'status': 'FILLED', 'positionside': 'SHORT', 'createtime': 1680451202251, 'updatetime': 1680451202819, 'tradetype': 'usdt', 'selfid': 42102, 'filltrades': [TradeType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'tradeid': 1680451202819, 'clientorderid': '42102F1680451202580I0L59', 'price': '28110.1', 'quantity': '25.257', 'commission': '709.9767957', 'commissionasset': 'USDT', 'tradetime': 1680451202819, 'tradetype': 'usdt', 'gatetype': 'simulator', 'handletime': 1680451202819}], 'gatetype': 'simulator', 'handletime': 0}

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=18488 

self.closeSec=1680451799, self.tradeDate='20230403', self.openTime='000000', self.closeTime='000959', self.symbol='BTCUSDT', self.open='28110.1', self.close='28125.1'
127.0.0.1 - - [03/Apr/2023 00:10:01] "POST / HTTP/1.1" 200 -
2023-04-03 00:10:01,615:INFO:modifiedmom:main.py:144:handleKline:185213: self.closeSec=1680451799, self.tradeDate='20230403', self.openTime='000000', self.closeTime='000959',self.symbol='BTCUSDT',self.open='28110.1', self.close='28125.1'
2023-04-03 00:10:01,640:INFO:modifiedmom:main.py:145:handleKline:185213: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
572  20230402   232000    232959  1680449399  28096.6  28088.9 -0.000274
573  20230402   233000    233959  1680449999  28088.8    28114  0.000894
574  20230402   234000    234959  1680450599    28114  28099.8 -0.000505
575  20230402   235000    235959  1680451199  28099.8  28110.2  0.000370
576  20230403   000000    000959  1680451799  28110.1  28125.1  0.000530
2023-04-03 00:10:01,640:INFO:modifiedmom:main.py:146:handleKline:185213: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=18489 

self.closeSec=1680452399, self.tradeDate='20230403', self.openTime='001000', self.closeTime='001959', self.symbol='BTCUSDT', self.open='28125.1', self.close='28069.9'
127.0.0.1 - - [03/Apr/2023 00:20:04] "POST / HTTP/1.1" 200 -
2023-04-03 00:20:08,216:INFO:modifiedmom:main.py:144:handleKline:185213: self.closeSec=1680452399, self.tradeDate='20230403', self.openTime='001000', self.closeTime='001959',self.symbol='BTCUSDT',self.open='28125.1', self.close='28069.9'
2023-04-03 00:20:09,056:INFO:modifiedmom:main.py:145:handleKline:185213: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
573  20230402   233000    233959  1680449999  28088.8    28114  0.000894
574  20230402   234000    234959  1680450599    28114  28099.8 -0.000505
575  20230402   235000    235959  1680451199  28099.8  28110.2  0.000370
576  20230403   000000    000959  1680451799  28110.1  28125.1  0.000530
577  20230403   001000    001959  1680452399  28125.1  28069.9 -0.001963
2023-04-03 00:20:09,057:INFO:modifiedmom:main.py:146:handleKline:185213: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False}


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

127.0.0.1 - - [03/Apr/2023 00:00:02] "POST / HTTP/1.1" 200 -
2023-04-03 00:00:02,958:INFO:pyemd2:main.py:303:handleOrderFilled:185189: handleOrderFilled: data=OrderType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'clientorderid': '42101F1680451202508I0L57', 'symbol': 'BTCUSDT', 'gatewayorderid': 1680451202609306, 'quantity': '35.437', 'price': '28110.1', 'stopprice': '0', 'ordertype': '', 'side': 'SELL', 'status': 'FILLED', 'positionside': 'SHORT', 'createtime': 1680451202170, 'updatetime': 1680451202609, 'tradetype': 'usdt', 'selfid': 42101, 'filltrades': [TradeType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'tradeid': 1680451202609, 'clientorderid': '42101F1680451202508I0L57', 'price': '28110.1', 'quantity': '35.437', 'commission': '996.1376137', 'commissionasset': 'USDT', 'tradetime': 1680451202609, 'tradetype': 'usdt', 'gatetype': 'simulator', 'handletime': 1680451202609}], 'gatetype': 'simulator', 'handletime': 0}

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=18489 

self.closeSec=1680451799, self.tradeDate='20230403', self.openTime='000000', self.closeTime='000959', self.symbol='BTCUSDT', self.open='28110.1', self.close='28125.1'
2023-04-03 00:10:01,609:INFO:pyemd2:main.py:125:handleKline:185189: self.closeSec=1680451799, self.tradeDate='20230403', self.openTime='000000', self.closeTime='000959',self.symbol='BTCUSDT',self.open='28110.1', self.close='28125.1'
127.0.0.1 - - [03/Apr/2023 00:10:01] "POST / HTTP/1.1" 200 -
2023-04-03 00:10:01,648:INFO:pyemd2:main.py:126:handleKline:185189: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17420  20230402   232000    232959  1680449399  28096.6  28088.9
17421  20230402   233000    233959  1680449999  28088.8    28114
17422  20230402   234000    234959  1680450599    28114  28099.8
17423  20230402   235000    235959  1680451199  28099.8  28110.2
17424  20230403   000000    000959  1680451799  28110.1  28125.1
2023-04-03 00:10:01,648:INFO:pyemd2:main.py:127:handleKline:185189: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=18490 

self.closeSec=1680452399, self.tradeDate='20230403', self.openTime='001000', self.closeTime='001959', self.symbol='BTCUSDT', self.open='28125.1', self.close='28069.9'
127.0.0.1 - - [03/Apr/2023 00:20:05] "POST / HTTP/1.1" 200 -
2023-04-03 00:20:11,259:INFO:pyemd2:main.py:125:handleKline:185189: self.closeSec=1680452399, self.tradeDate='20230403', self.openTime='001000', self.closeTime='001959',self.symbol='BTCUSDT',self.open='28125.1', self.close='28069.9'
2023-04-03 00:20:11,407:INFO:pyemd2:main.py:126:handleKline:185189: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17421  20230402   233000    233959  1680449999  28088.8    28114
17422  20230402   234000    234959  1680450599    28114  28099.8
17423  20230402   235000    235959  1680451199  28099.8  28110.2
17424  20230403   000000    000959  1680451799  28110.1  28125.1
17425  20230403   001000    001959  1680452399  28125.1  28069.9
2023-04-03 00:20:11,407:INFO:pyemd2:main.py:127:handleKline:185189: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}


## /root/FIL/strategy/similarity/log.txt ----- -----

127.0.0.1 - - [03/Apr/2023 00:00:03] "POST / HTTP/1.1" 200 -
2023-04-03 00:00:03,411:INFO:testStrategy:main.py:308:handleOrderFilled:185174: handleOrderFilled: data=OrderType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'clientorderid': '42103F1680451202882I0L2', 'symbol': 'BTCUSDT', 'gatewayorderid': 1680451203055945, 'quantity': '46.202', 'price': '28110.1', 'stopprice': '0', 'ordertype': '', 'side': 'SELL', 'status': 'FILLED', 'positionside': 'SHORT', 'createtime': 1680451202561, 'updatetime': 1680451203055, 'tradetype': 'usdt', 'selfid': 42103, 'filltrades': [TradeType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'tradeid': 1680451203055, 'clientorderid': '42103F1680451202882I0L2', 'price': '28110.1', 'quantity': '46.202', 'commission': '1298.7428402', 'commissionasset': 'USDT', 'tradetime': 1680451203055, 'tradetype': 'usdt', 'gatetype': 'simulator', 'handletime': 1680451203055}], 'gatetype': 'simulator', 'handletime': 0}

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=18489 

self.closeSec=1680451799, self.tradeDate='20230403', self.openTime='000000', self.closeTime='000959', self.symbol='BTCUSDT', self.open='28110.1', self.close='28125.1'
127.0.0.1 - - [03/Apr/2023 00:10:01] "POST / HTTP/1.1" 200 -
2023-04-03 00:10:01,595:INFO:testStrategy:main.py:101:handleKline:185174: self.closeSec=1680451799, self.tradeDate='20230403', self.openTime='000000', self.closeTime='000959',self.symbol='BTCUSDT',self.open='28110.1', self.close='28125.1'
2023-04-03 00:10:01,644:INFO:testStrategy:main.py:102:handleKline:185174: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12236  20230402   232000    232959  1680449399  28096.6  28088.9
12237  20230402   233000    233959  1680449999  28088.8    28114
12238  20230402   234000    234959  1680450599    28114  28099.8
12239  20230402   235000    235959  1680451199  28099.8  28110.2
12240  20230403   000000    000959  1680451799  28110.1  28125.1
2023-04-03 00:10:01,644:INFO:testStrategy:main.py:103:handleKline:185174: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False, 'isCorr': False}

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=18490 

self.closeSec=1680452399, self.tradeDate='20230403', self.openTime='001000', self.closeTime='001959', self.symbol='BTCUSDT', self.open='28125.1', self.close='28069.9'
127.0.0.1 - - [03/Apr/2023 00:20:05] "POST / HTTP/1.1" 200 -
2023-04-03 00:20:10,708:INFO:testStrategy:main.py:101:handleKline:185174: self.closeSec=1680452399, self.tradeDate='20230403', self.openTime='001000', self.closeTime='001959',self.symbol='BTCUSDT',self.open='28125.1', self.close='28069.9'
2023-04-03 00:20:11,035:INFO:testStrategy:main.py:102:handleKline:185174: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12237  20230402   233000    233959  1680449999  28088.8    28114
12238  20230402   234000    234959  1680450599    28114  28099.8
12239  20230402   235000    235959  1680451199  28099.8  28110.2
12240  20230403   000000    000959  1680451799  28110.1  28125.1
12241  20230403   001000    001959  1680452399  28125.1  28069.9
2023-04-03 00:20:11,036:INFO:testStrategy:main.py:103:handleKline:185174: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False, 'isCorr': False}


## /root/FIL/strategy/sr_min/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=0, self.total=1000000.0, self.flagDict['side']='', self.tradeCount=0, self.count=32410
self.closeSec=1680452399, self.tradeDate='20230403', self.openTime='001500', self.closeTime='001959', self.symbol='BTCUSDT', self.open=28122.0, self.close=28069.9, self.high=28122.2, self.low=28050.0, self.vol=2354.638, self.amt=66097879.1644 
127.0.0.1 - - [03/Apr/2023 00:20:03] "POST / HTTP/1.1" 200 -
2023-04-03 00:20:08,236:INFO:sr_min:main.py:172:handleKline:449472: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5759  20230402   235500    235959  ...         0.0        0.0       0
5760  20230403   000000    000459  ...         0.0        0.0       0
5761  20230403   000500    000959  ...         0.0        0.0       0
5762  20230403   001000    001459  ...         0.0        0.0       0
5763  20230403   001500    001959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-04-03 00:20:08,267:INFO:sr_min:main.py:175:handleKline:449472: self.closeSec=1680452399, self.tradeDate='20230403', self.openTime='001500', self.closeTime='001959',self.symbol='BTCUSDT',self.open=28122.0, self.close=28069.9, self.high=28122.2, self.low=28050.0, self.vol=2354.638, self.amt=66097879.1644, ukdf['pct'].iloc[-1]=-0.001856 , ukdf['amount'].iloc[-1]=66097879.1644, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5763, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': []}
type(curSign)=<class 'int'>, curSign=0, self.sign=0
--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=0, self.total=1000000.0, self.flagDict['side']='', self.tradeCount=0, self.count=32411
self.closeSec=1680452699, self.tradeDate='20230403', self.openTime='002000', self.closeTime='002459', self.symbol='BTCUSDT', self.open=28070.0, self.close=28039.3, self.high=28106.4, self.low=27981.0, self.vol=4616.787, self.amt=129455296.7753 
127.0.0.1 - - [03/Apr/2023 00:25:01] "POST / HTTP/1.1" 200 -
2023-04-03 00:25:01,612:INFO:sr_min:main.py:172:handleKline:449472: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5760  20230403   000000    000459  ...         0.0        0.0       0
5761  20230403   000500    000959  ...         0.0        0.0       0
5762  20230403   001000    001459  ...         0.0        0.0       0
5763  20230403   001500    001959  ...         0.0        0.0       0
5764  20230403   002000    002459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-04-03 00:25:01,614:INFO:sr_min:main.py:175:handleKline:449472: self.closeSec=1680452699, self.tradeDate='20230403', self.openTime='002000', self.closeTime='002459',self.symbol='BTCUSDT',self.open=28070.0, self.close=28039.3, self.high=28106.4, self.low=27981.0, self.vol=4616.787, self.amt=129455296.7753, ukdf['pct'].iloc[-1]=-0.00109 , ukdf['amount'].iloc[-1]=129455296.7753, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5764, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': []}
type(curSign)=<class 'int'>, curSign=0, self.sign=0


## /root/FIL/strategy/s_rsrs/log.txt ----- -----

723  20230402   120000    155959  1680422399  ...    723  0.086417 -0.958243    -1.0
724  20230402   160000    195959  1680436799  ...    724  0.076166 -0.966467    -1.0

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '52.088', 'enterprice': '28398.8', 'countrevence': '0', 'unrealprofit': '2779.0356303256', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '28345.4472963', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-1, self.sign=-1
--handleKline--:  version='2.0.0', self.name='s_rsrs', self.symbol='BTCUSDT', interval='4h', intervalSec=14400, wid=25, thd=0.6, self.sign=-1, self.total=1477757.4577056, self.flagDict['side']='sell', self.tradeCount=29, self.count=770
self.closeSec=1680451199, self.tradeDate='20230402', self.openTime='200000', self.closeTime='235959', self.symbol='BTCUSDT', self.open=28344.9, self.close=28110.2, self.high=28352.5, self.low=28022.0, self.vol=92591.724, self.amt=2610223026.75307 
127.0.0.1 - - [03/Apr/2023 00:00:01] "POST / HTTP/1.1" 200 -
2023-04-03 00:00:01,768:INFO:s_rsrs:main.py:141:handleKline:185271: self.closeSec=1680451199, self.tradeDate='20230402', self.openTime='200000', self.closeTime='235959',self.symbol='BTCUSDT',self.open=28344.9, self.close=28110.2, self.high=28352.5, self.low=28022.0, self.vol=92591.724, self.amt=2610223026.75307 
2023-04-03 00:00:01,808:INFO:s_rsrs:main.py:142:handleKline:185271: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime  ...        vol           amt       pct
721  20230402   040000    075959  ...  36734.183  1.046074e+09  0.002661
722  20230402   080000    115959  ...  28921.926  8.218985e+08  0.000675
723  20230402   120000    155959  ...  21969.846  6.245725e+08 -0.002168
724  20230402   160000    195959  ...  30770.077  8.728521e+08 -0.001986
725  20230402   200000    235959  ...  92591.724  2.610223e+09 -0.008280

[5 rows x 11 columns]
2023-04-03 00:00:04,411:INFO:s_rsrs:main.py:151:handleKline:185271: df_s.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec  ...  index      beta    zscore  signal
721  20230402   040000    075959  1680393599  ...    721  0.388136 -0.118582     NaN
722  20230402   080000    115959  1680407999  ...    722  0.246313 -0.513289     NaN
723  20230402   120000    155959  1680422399  ...    723  0.086417 -0.958243    -1.0
724  20230402   160000    195959  1680436799  ...    724  0.076166 -0.966467    -1.0
725  20230402   200000    235959  1680451199  ...    725  0.088071 -0.911072    -1.0

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '52.088', 'enterprice': '28398.8', 'countrevence': '0', 'unrealprofit': '14794.83967699536', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '28114.76452778', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-1, self.sign=-1


