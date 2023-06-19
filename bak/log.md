# 20230620 00:26:01

## /root/FIL/strategy/amihud/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=373746.4768026, self.flagDict['side']='sell', self.tradeCount=2, self.count=10528
self.closeSec=1687191599, self.tradeDate='20230620', self.openTime='001500', self.closeTime='001959', self.symbol='BTCUSDT', self.open=26411.6, self.close=26424.7, self.high=26426.0, self.low=26409.6, self.vol=245.166, self.amt=6476918.5107 
127.0.0.1 - - [20/Jun/2023 00:20:01] "POST / HTTP/1.1" 200 -
2023-06-20 00:20:07,303:INFO:amihud:main.py:172:handleKline:2219019: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5759  20230619   235500    235959  ...         0.0        0.0       0
5760  20230620   000000    000459  ...         0.0        0.0       0
5761  20230620   000500    000959  ...         0.0        0.0       0
5762  20230620   001000    001459  ...         0.0        0.0       0
5763  20230620   001500    001959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-06-20 00:20:07,343:INFO:amihud:main.py:175:handleKline:2219019: self.closeSec=1687191599, self.tradeDate='20230620', self.openTime='001500', self.closeTime='001959',self.symbol='BTCUSDT',self.open=26411.6, self.close=26424.7, self.high=26426.0, self.low=26409.6, self.vol=245.166, self.amt=6476918.5107, ukdf['pct'].iloc[-1]=0.0005 , ukdf['amount'].iloc[-1]=6476918.5107, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5763, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '13.926', 'enterprice': '26864.9', 'countrevence': '0', 'unrealprofit': '6128.8326', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '26424.8', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1
--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=373746.4768026, self.flagDict['side']='sell', self.tradeCount=2, self.count=10529
self.closeSec=1687191899, self.tradeDate='20230620', self.openTime='002000', self.closeTime='002459', self.symbol='BTCUSDT', self.open=26424.8, self.close=26433.8, self.high=26433.9, self.low=26424.5, self.vol=218.652, self.amt=5778473.3911 
127.0.0.1 - - [20/Jun/2023 00:25:00] "POST / HTTP/1.1" 200 -
2023-06-20 00:25:00,790:INFO:amihud:main.py:172:handleKline:2219019: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5760  20230620   000000    000459  ...         0.0        0.0       0
5761  20230620   000500    000959  ...         0.0        0.0       0
5762  20230620   001000    001459  ...         0.0        0.0       0
5763  20230620   001500    001959  ...         0.0        0.0       0
5764  20230620   002000    002459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-06-20 00:25:00,791:INFO:amihud:main.py:175:handleKline:2219019: self.closeSec=1687191899, self.tradeDate='20230620', self.openTime='002000', self.closeTime='002459',self.symbol='BTCUSDT',self.open=26424.8, self.close=26433.8, self.high=26433.9, self.low=26424.5, self.vol=218.652, self.amt=5778473.3911, ukdf['pct'].iloc[-1]=0.000344 , ukdf['amount'].iloc[-1]=5778473.3911, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5764, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '13.926', 'enterprice': '26864.9', 'countrevence': '0', 'unrealprofit': '6028.5654', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '26432', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1


## /root/FIL/strategy/factorcheck/log.txt ----- -----


self.closeSec=1687191599, self.tradeDate='20230620', self.openTime='001500', self.closeTime='001959', self.symbol='BTCUSDT', self.open=26411.6, self.close=26424.7, self.high=26426.0, self.low=26409.6 
127.0.0.1 - - [20/Jun/2023 00:20:01] "POST / HTTP/1.1" 200 -
2023-06-20 00:20:04,703:INFO:factorcheck2:main.py:126:handleKline:2218005: self.closeSec=1687191599, self.tradeDate='20230620', self.openTime='001500', self.closeTime='001959',self.symbol='BTCUSDT',self.open=26411.6, self.close=26424.7, self.high=26426.0, self.low=26409.6   
2023-06-20 00:20:06,212:INFO:factorcheck2:main.py:127:handleKline:2218005: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1439  20230619   235500    235959  1687190399  ...  26426.0 -0.000257   1727    5
1440  20230620   000000    000459  1687190699  ...  26414.7 -0.000620   1440    0
1441  20230620   000500    000959  1687190999  ...  26414.5  0.000265   1441    1
1442  20230620   001000    001459  1687191299  ...  26403.0 -0.000390   1442    2
1443  20230620   001500    001959  1687191599  ...  26409.6  0.000500   1443    3

[5 rows x 11 columns]
2023-06-20 00:20:06,222:INFO:factorcheck2:main.py:128:handleKline:2218005: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}
127.0.0.1 - - [20/Jun/2023 00:25:00] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=133, self.factor=0.49645203398097115, self.count=10531 

self.closeSec=1687191899, self.tradeDate='20230620', self.openTime='002000', self.closeTime='002459', self.symbol='BTCUSDT', self.open=26424.8, self.close=26433.8, self.high=26433.9, self.low=26424.5 
2023-06-20 00:25:00,743:INFO:factorcheck2:main.py:126:handleKline:2218005: self.closeSec=1687191899, self.tradeDate='20230620', self.openTime='002000', self.closeTime='002459',self.symbol='BTCUSDT',self.open=26424.8, self.close=26433.8, self.high=26433.9, self.low=26424.5   
2023-06-20 00:25:00,777:INFO:factorcheck2:main.py:127:handleKline:2218005: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1440  20230620   000000    000459  1687190699  ...  26414.7 -0.000620   1440    0
1441  20230620   000500    000959  1687190999  ...  26414.5  0.000265   1441    1
1442  20230620   001000    001459  1687191299  ...  26403.0 -0.000390   1442    2
1443  20230620   001500    001959  1687191599  ...  26409.6  0.000500   1443    3
1444  20230620   002000    002459  1687191899  ...  26424.5  0.000344   1444    4

[5 rows x 11 columns]
2023-06-20 00:25:00,777:INFO:factorcheck2:main.py:128:handleKline:2218005: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}


## /root/FIL/strategy/logic/log.txt ----- -----

2023-06-20 00:00:19,500:DEBUG:logic:main.py:463:getModel:2218526: df_s.iloc[-5:,:] :
          date closeTime     open  ...    alpha58   alpha67   alpha72
5802  20230619    212959  26521.4  ...  52.500000  0.540587  0.573503
5803  20230619    215959  26527.0  ...  52.083333  0.538439  0.561546
5804  20230619    222959  26520.8  ...  52.083333  0.511262  0.561713
5805  20230619    225959  26439.5  ...  51.666667  0.503009  0.565478
5806  20230619    232959  26413.7  ...  51.666667  0.496847  0.571708

[5 rows x 33 columns]
0.5716911764705882
acc is : 0.5716911764705882
2023-06-20 00:00:19,597:INFO:logic:main.py:468:getModel:2218526: df_pred.iloc[-5:,:] :
     pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
539     0  0.513613  0.486387       0  ...  1.038169   1.0    0.0  1.003379
540     0  0.508264  0.491736       0  ...  1.034986   1.0    0.0  1.000303
541     1  0.486394  0.513606       0  ...  1.033972   1.0    0.0  0.999323
542     1  0.487122  0.512878       0  ...  1.033209   1.0    0.0  0.998585
543     1  0.486723  0.513277       1  ...  1.034657   1.0    0.0  0.999985

[5 rows x 10 columns]
2023-06-20 00:00:19,618:INFO:logic:main.py:478:getModel:2218526: df_panel.iloc[-5:,:] :
    pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
45     0  0.513777  0.486223       0  ...  1.038169   1.0    0.0  1.006864
46     0  0.508087  0.491913       0  ...  1.034986   1.0    0.0  1.000992
47     1  0.486397  0.513603       0  ...  1.033972   1.0    0.0  1.000011
48     1  0.487012  0.512988       0  ...  1.033209   1.0    0.0  0.996534
49     1  0.486723  0.513277       1  ...  1.034657   1.0    0.0  0.999985

[5 rows x 10 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '28.127', 'enterprice': '25424', 'countrevence': '0', 'unrealprofit': '28329.5144', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '26431.2', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}


## /root/FIL/strategy/modifiedmom/log.txt ----- -----

127.0.0.1 - - [20/Jun/2023 00:00:04] "POST / HTTP/1.1" 200 -
2023-06-20 00:00:04,247:INFO:modifiedmom:main.py:319:handleOrderFilled:2218259: handleOrderFilled: data=OrderType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'clientorderid': '42419F1687190403637I0L59', 'symbol': 'BTCUSDT', 'gatewayorderid': 1687190404016766, 'quantity': '27.578', 'price': '26431.1', 'stopprice': '0', 'ordertype': '', 'side': 'SELL', 'status': 'FILLED', 'positionside': 'SHORT', 'createtime': 1687190402608, 'updatetime': 1687190404016, 'tradetype': 'usdt', 'selfid': 42419, 'filltrades': [TradeType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'tradeid': 1687190404016, 'clientorderid': '42419F1687190403637I0L59', 'price': '26431.1', 'quantity': '27.578', 'commission': '728.9168758', 'commissionasset': 'USDT', 'tradetime': 1687190404016, 'tradetype': 'usdt', 'gatetype': 'simulator', 'handletime': 1687190404016}], 'gatetype': 'simulator', 'handletime': 0}
127.0.0.1 - - [20/Jun/2023 00:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=5264 

self.closeSec=1687190999, self.tradeDate='20230620', self.openTime='000000', self.closeTime='000959', self.symbol='BTCUSDT', self.open='26431.1', self.close='26421.8'
2023-06-20 00:10:01,079:INFO:modifiedmom:main.py:144:handleKline:2218259: self.closeSec=1687190999, self.tradeDate='20230620', self.openTime='000000', self.closeTime='000959',self.symbol='BTCUSDT',self.open='26431.1', self.close='26421.8'
2023-06-20 00:10:01,104:INFO:modifiedmom:main.py:145:handleKline:2218259: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
572  20230619   232000    232959  1687188599  26386.2  26394.1  0.000296
573  20230619   233000    233959  1687189199  26394.1  26438.6  0.001686
574  20230619   234000    234959  1687189799  26438.6  26434.1 -0.000170
575  20230619   235000    235959  1687190399  26434.1  26431.1 -0.000113
576  20230620   000000    000959  1687190999  26431.1  26421.8 -0.000352
2023-06-20 00:10:01,105:INFO:modifiedmom:main.py:146:handleKline:2218259: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=5265 

self.closeSec=1687191599, self.tradeDate='20230620', self.openTime='001000', self.closeTime='001959', self.symbol='BTCUSDT', self.open='26421.8', self.close='26424.7'
127.0.0.1 - - [20/Jun/2023 00:20:04] "POST / HTTP/1.1" 200 -
2023-06-20 00:20:07,013:INFO:modifiedmom:main.py:144:handleKline:2218259: self.closeSec=1687191599, self.tradeDate='20230620', self.openTime='001000', self.closeTime='001959',self.symbol='BTCUSDT',self.open='26421.8', self.close='26424.7'
2023-06-20 00:20:07,819:INFO:modifiedmom:main.py:145:handleKline:2218259: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
573  20230619   233000    233959  1687189199  26394.1  26438.6  0.001686
574  20230619   234000    234959  1687189799  26438.6  26434.1 -0.000170
575  20230619   235000    235959  1687190399  26434.1  26431.1 -0.000113
576  20230620   000000    000959  1687190999  26431.1  26421.8 -0.000352
577  20230620   001000    001959  1687191599  26421.8  26424.7  0.000110
2023-06-20 00:20:07,827:INFO:modifiedmom:main.py:146:handleKline:2218259: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False}


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

2023-06-20 00:00:01,975:INFO:pyemd2:main.py:127:handleKline:2217508: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}
2023-06-20 00:00:02,108:INFO:pyemd2:main.py:190:insertFactor:2217508: curDateTime:6200000, name:pyemd2, symbol:BTCUSDT, tradeDate:20230619, closeTime:235959, close:26431.1, total:972975.8716388, pct_pre:-0.006431449335391748, thd:0.029910734042802423, side:sell 

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=5267 

self.closeSec=1687190999, self.tradeDate='20230620', self.openTime='000000', self.closeTime='000959', self.symbol='BTCUSDT', self.open='26431.1', self.close='26421.8'
2023-06-20 00:10:01,091:INFO:pyemd2:main.py:125:handleKline:2217508: self.closeSec=1687190999, self.tradeDate='20230620', self.openTime='000000', self.closeTime='000959',self.symbol='BTCUSDT',self.open='26431.1', self.close='26421.8'
127.0.0.1 - - [20/Jun/2023 00:10:01] "POST / HTTP/1.1" 200 -
2023-06-20 00:10:01,107:INFO:pyemd2:main.py:126:handleKline:2217508: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17420  20230619   232000    232959  1687188599  26386.2  26394.1
17421  20230619   233000    233959  1687189199  26394.1  26438.6
17422  20230619   234000    234959  1687189799  26438.6  26434.1
17423  20230619   235000    235959  1687190399  26434.1  26431.1
17424  20230620   000000    000959  1687190999  26431.1  26421.8
2023-06-20 00:10:01,108:INFO:pyemd2:main.py:127:handleKline:2217508: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=5268 

self.closeSec=1687191599, self.tradeDate='20230620', self.openTime='001000', self.closeTime='001959', self.symbol='BTCUSDT', self.open='26421.8', self.close='26424.7'
127.0.0.1 - - [20/Jun/2023 00:20:04] "POST / HTTP/1.1" 200 -
2023-06-20 00:20:08,972:INFO:pyemd2:main.py:125:handleKline:2217508: self.closeSec=1687191599, self.tradeDate='20230620', self.openTime='001000', self.closeTime='001959',self.symbol='BTCUSDT',self.open='26421.8', self.close='26424.7'
2023-06-20 00:20:09,099:INFO:pyemd2:main.py:126:handleKline:2217508: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17421  20230619   233000    233959  1687189199  26394.1  26438.6
17422  20230619   234000    234959  1687189799  26438.6  26434.1
17423  20230619   235000    235959  1687190399  26434.1  26431.1
17424  20230620   000000    000959  1687190999  26431.1  26421.8
17425  20230620   001000    001959  1687191599  26421.8  26424.7
2023-06-20 00:20:09,100:INFO:pyemd2:main.py:127:handleKline:2217508: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}


## /root/FIL/strategy/similarity/log.txt ----- -----

2023-06-20 00:00:04,406:INFO:testStrategy:main.py:308:handleOrderFilled:2217133: handleOrderFilled: data=OrderType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'clientorderid': '42418F1687190403602I0L2', 'symbol': 'BTCUSDT', 'gatewayorderid': 1687190404043870, 'quantity': '49.413', 'price': '26431.2', 'stopprice': '0', 'ordertype': '', 'side': 'BUY', 'status': 'FILLED', 'positionside': 'LONG', 'createtime': 1687190402665, 'updatetime': 1687190404043, 'tradetype': 'usdt', 'selfid': 42418, 'filltrades': [TradeType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'tradeid': 1687190404043, 'clientorderid': '42418F1687190403602I0L2', 'price': '26431.2', 'quantity': '49.413', 'commission': '1306.0448856', 'commissionasset': 'USDT', 'tradetime': 1687190404043, 'tradetype': 'usdt', 'gatetype': 'simulator', 'handletime': 1687190404043}], 'gatetype': 'simulator', 'handletime': 0}
127.0.0.1 - - [20/Jun/2023 00:00:04] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=5267 

self.closeSec=1687190999, self.tradeDate='20230620', self.openTime='000000', self.closeTime='000959', self.symbol='BTCUSDT', self.open='26431.1', self.close='26421.8'
127.0.0.1 - - [20/Jun/2023 00:10:01] "POST / HTTP/1.1" 200 -
2023-06-20 00:10:01,103:INFO:testStrategy:main.py:101:handleKline:2217133: self.closeSec=1687190999, self.tradeDate='20230620', self.openTime='000000', self.closeTime='000959',self.symbol='BTCUSDT',self.open='26431.1', self.close='26421.8'
2023-06-20 00:10:01,123:INFO:testStrategy:main.py:102:handleKline:2217133: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12236  20230619   232000    232959  1687188599  26386.2  26394.1
12237  20230619   233000    233959  1687189199  26394.1  26438.6
12238  20230619   234000    234959  1687189799  26438.6  26434.1
12239  20230619   235000    235959  1687190399  26434.1  26431.1
12240  20230620   000000    000959  1687190999  26431.1  26421.8
2023-06-20 00:10:01,123:INFO:testStrategy:main.py:103:handleKline:2217133: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False, 'isCorr': False}

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=5268 

self.closeSec=1687191599, self.tradeDate='20230620', self.openTime='001000', self.closeTime='001959', self.symbol='BTCUSDT', self.open='26421.8', self.close='26424.7'
127.0.0.1 - - [20/Jun/2023 00:20:04] "POST / HTTP/1.1" 200 -
2023-06-20 00:20:08,581:INFO:testStrategy:main.py:101:handleKline:2217133: self.closeSec=1687191599, self.tradeDate='20230620', self.openTime='001000', self.closeTime='001959',self.symbol='BTCUSDT',self.open='26421.8', self.close='26424.7'
2023-06-20 00:20:08,889:INFO:testStrategy:main.py:102:handleKline:2217133: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12237  20230619   233000    233959  1687189199  26394.1  26438.6
12238  20230619   234000    234959  1687189799  26438.6  26434.1
12239  20230619   235000    235959  1687190399  26434.1  26431.1
12240  20230620   000000    000959  1687190999  26431.1  26421.8
12241  20230620   001000    001959  1687191599  26421.8  26424.7
2023-06-20 00:20:08,891:INFO:testStrategy:main.py:103:handleKline:2217133: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False, 'isCorr': False}


## /root/FIL/strategy/sr_min/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=1, self.total=996015.990996, self.flagDict['side']='buy', self.tradeCount=1, self.count=10528
self.closeSec=1687191599, self.tradeDate='20230620', self.openTime='001500', self.closeTime='001959', self.symbol='BTCUSDT', self.open=26411.6, self.close=26424.7, self.high=26426.0, self.low=26409.6, self.vol=245.166, self.amt=6476918.5107 
127.0.0.1 - - [20/Jun/2023 00:20:01] "POST / HTTP/1.1" 200 -
2023-06-20 00:20:07,304:INFO:sr_min:main.py:172:handleKline:2219263: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5759  20230619   235500    235959  ...         0.0        0.0       0
5760  20230620   000000    000459  ...         0.0        0.0       0
5761  20230620   000500    000959  ...         0.0        0.0       0
5762  20230620   001000    001459  ...         0.0        0.0       0
5763  20230620   001500    001959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-06-20 00:20:07,334:INFO:sr_min:main.py:175:handleKline:2219263: self.closeSec=1687191599, self.tradeDate='20230620', self.openTime='001500', self.closeTime='001959',self.symbol='BTCUSDT',self.open=26411.6, self.close=26424.7, self.high=26426.0, self.low=26409.6, self.vol=245.166, self.amt=6476918.5107, ukdf['pct'].iloc[-1]=0.0005 , ukdf['amount'].iloc[-1]=6476918.5107, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5763, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '37.141', 'enterprice': '26844', 'countrevence': '0', 'unrealprofit': '-15569.5072', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '26424.8', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=1
--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=1, self.total=996015.990996, self.flagDict['side']='buy', self.tradeCount=1, self.count=10529
self.closeSec=1687191899, self.tradeDate='20230620', self.openTime='002000', self.closeTime='002459', self.symbol='BTCUSDT', self.open=26424.8, self.close=26433.8, self.high=26433.9, self.low=26424.5, self.vol=218.652, self.amt=5778473.3911 
127.0.0.1 - - [20/Jun/2023 00:25:00] "POST / HTTP/1.1" 200 -
2023-06-20 00:25:00,786:INFO:sr_min:main.py:172:handleKline:2219263: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5760  20230620   000000    000459  ...         0.0        0.0       0
5761  20230620   000500    000959  ...         0.0        0.0       0
5762  20230620   001000    001459  ...         0.0        0.0       0
5763  20230620   001500    001959  ...         0.0        0.0       0
5764  20230620   002000    002459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-06-20 00:25:00,787:INFO:sr_min:main.py:175:handleKline:2219263: self.closeSec=1687191899, self.tradeDate='20230620', self.openTime='002000', self.closeTime='002459',self.symbol='BTCUSDT',self.open=26424.8, self.close=26433.8, self.high=26433.9, self.low=26424.5, self.vol=218.652, self.amt=5778473.3911, ukdf['pct'].iloc[-1]=0.000344 , ukdf['amount'].iloc[-1]=5778473.3911, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5764, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '37.141', 'enterprice': '26844', 'countrevence': '0', 'unrealprofit': '-15302.092', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '26432', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=1


## /root/FIL/strategy/s_rsrs/log.txt ----- -----

723  20230619   120000    155959  1687161599  ...    723  0.696930  1.516073     1.0
724  20230619   160000    195959  1687175999  ...    724  0.633896  1.164566     1.0

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '57.175', 'enterprice': '26590', 'countrevence': '0', 'unrealprofit': '-8662.0125', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '26438.5', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=1, self.sign=1
127.0.0.1 - - [20/Jun/2023 00:00:01] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='s_rsrs', self.symbol='BTCUSDT', interval='4h', intervalSec=14400, wid=25, thd=0.6, self.sign=1, self.total=1518762.96675, self.flagDict['side']='buy', self.tradeCount=5, self.count=219
self.closeSec=1687190399, self.tradeDate='20230619', self.openTime='200000', self.closeTime='235959', self.symbol='BTCUSDT', self.open=26438.5, self.close=26431.1, self.high=26569.7, self.low=26328.0, self.vol=65548.161, self.amt=1734847484.3613 
2023-06-20 00:00:01,560:INFO:s_rsrs:main.py:141:handleKline:2218689: self.closeSec=1687190399, self.tradeDate='20230619', self.openTime='200000', self.closeTime='235959',self.symbol='BTCUSDT',self.open=26438.5, self.close=26431.1, self.high=26569.7, self.low=26328.0, self.vol=65548.161, self.amt=1734847484.3613 
2023-06-20 00:00:01,582:INFO:s_rsrs:main.py:142:handleKline:2218689: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime  ...        vol           amt       pct
721  20230619   040000    075959  ...  80903.422  2.137750e+09 -0.011707
722  20230619   080000    115959  ...  32200.784  8.495103e+08  0.002423
723  20230619   120000    155959  ...  19572.100  5.169974e+08  0.000826
724  20230619   160000    195959  ...  24996.502  6.598964e+08  0.000882
725  20230619   200000    235959  ...  65548.161  1.734847e+09 -0.000284

[5 rows x 11 columns]
2023-06-20 00:00:02,975:INFO:s_rsrs:main.py:151:handleKline:2218689: df_s.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec  ...  index      beta    zscore  signal
721  20230619   040000    075959  1687132799  ...    721  0.609595  1.127262     1.0
722  20230619   080000    115959  1687147199  ...    722  0.741899  1.777152     1.0
723  20230619   120000    155959  1687161599  ...    723  0.696930  1.516073     1.0
724  20230619   160000    195959  1687175999  ...    724  0.633896  1.164566     1.0
725  20230619   200000    235959  1687190399  ...    725  0.568553  0.797705     1.0

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '57.175', 'enterprice': '26590', 'countrevence': '0', 'unrealprofit': '-9085.1075', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '26431.1', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=1, self.sign=1


