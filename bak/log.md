# 20230326 00:26:02

## /root/FIL/strategy/amihud/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=993672.4896432, self.flagDict['side']='sell', self.tradeCount=2, self.count=34108
self.closeSec=1679761199, self.tradeDate='20230326', self.openTime='001500', self.closeTime='001959', self.symbol='BTCUSDT', self.open=27638.0, self.close=27614.3, self.high=27646.4, self.low=27607.1, self.vol=1525.915, self.amt=42145530.2031 
127.0.0.1 - - [26/Mar/2023 00:20:04] "POST / HTTP/1.1" 200 -
2023-03-26 00:20:09,924:INFO:amihud:main.py:172:handleKline:200676: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5759  20230325   235500    235959  ...         0.0        0.0       0
5760  20230326   000000    000459  ...         0.0        0.0       0
5761  20230326   000500    000959  ...         0.0        0.0       0
5762  20230326   001000    001459  ...         0.0        0.0       0
5763  20230326   001500    001959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-03-26 00:20:09,944:INFO:amihud:main.py:175:handleKline:200676: self.closeSec=1679761199, self.tradeDate='20230326', self.openTime='001500', self.closeTime='001959',self.symbol='BTCUSDT',self.open=27638.0, self.close=27614.3, self.high=27646.4, self.low=27607.1, self.vol=1525.915, self.amt=42145530.2031, ukdf['pct'].iloc[-1]=-0.000858 , ukdf['amount'].iloc[-1]=42145530.2031, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5763, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '60.176', 'enterprice': '16529.3', 'countrevence': '0', 'unrealprofit': '-667502.28', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '27621.8', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1
--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=993672.4896432, self.flagDict['side']='sell', self.tradeCount=2, self.count=34109
self.closeSec=1679761499, self.tradeDate='20230326', self.openTime='002000', self.closeTime='002459', self.symbol='BTCUSDT', self.open=27614.4, self.close=27636.4, self.high=27638.4, self.low=27614.3, self.vol=440.405, self.amt=12166345.6088 
127.0.0.1 - - [26/Mar/2023 00:25:01] "POST / HTTP/1.1" 200 -
2023-03-26 00:25:01,614:INFO:amihud:main.py:172:handleKline:200676: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5760  20230326   000000    000459  ...         0.0        0.0       0
5761  20230326   000500    000959  ...         0.0        0.0       0
5762  20230326   001000    001459  ...         0.0        0.0       0
5763  20230326   001500    001959  ...         0.0        0.0       0
5764  20230326   002000    002459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-03-26 00:25:01,615:INFO:amihud:main.py:175:handleKline:200676: self.closeSec=1679761499, self.tradeDate='20230326', self.openTime='002000', self.closeTime='002459',self.symbol='BTCUSDT',self.open=27614.4, self.close=27636.4, self.high=27638.4, self.low=27614.3, self.vol=440.405, self.amt=12166345.6088, ukdf['pct'].iloc[-1]=0.0008 , ukdf['amount'].iloc[-1]=12166345.6088, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5764, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '60.176', 'enterprice': '16529.3', 'countrevence': '0', 'unrealprofit': '-668477.1312', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '27638', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1


## /root/FIL/strategy/factorcheck/log.txt ----- -----


self.closeSec=1679761199, self.tradeDate='20230326', self.openTime='001500', self.closeTime='001959', self.symbol='BTCUSDT', self.open=27638.0, self.close=27614.3, self.high=27646.4, self.low=27607.1 
127.0.0.1 - - [26/Mar/2023 00:20:03] "POST / HTTP/1.1" 200 -
2023-03-26 00:20:07,174:INFO:factorcheck2:main.py:126:handleKline:185239: self.closeSec=1679761199, self.tradeDate='20230326', self.openTime='001500', self.closeTime='001959',self.symbol='BTCUSDT',self.open=27638.0, self.close=27614.3, self.high=27646.4, self.low=27607.1   
2023-03-26 00:20:08,313:INFO:factorcheck2:main.py:127:handleKline:185239: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1439  20230325   235500    235959  1679759999  ...  27630.0 -0.003498   1727    5
1440  20230326   000000    000459  1679760299  ...  27616.5  0.000503   1440    0
1441  20230326   000500    000959  1679760599  ...  27606.3 -0.000760   1441    1
1442  20230326   001000    001459  1679760899  ...  27626.8  0.000434   1442    2
1443  20230326   001500    001959  1679761199  ...  27607.1 -0.000858   1443    3

[5 rows x 11 columns]
2023-03-26 00:20:08,314:INFO:factorcheck2:main.py:128:handleKline:185239: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}
127.0.0.1 - - [26/Mar/2023 00:25:01] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=396, self.factor=0.5444005061451681, self.count=34675 

self.closeSec=1679761499, self.tradeDate='20230326', self.openTime='002000', self.closeTime='002459', self.symbol='BTCUSDT', self.open=27614.4, self.close=27636.4, self.high=27638.4, self.low=27614.3 
2023-03-26 00:25:01,495:INFO:factorcheck2:main.py:126:handleKline:185239: self.closeSec=1679761499, self.tradeDate='20230326', self.openTime='002000', self.closeTime='002459',self.symbol='BTCUSDT',self.open=27614.4, self.close=27636.4, self.high=27638.4, self.low=27614.3   
2023-03-26 00:25:01,530:INFO:factorcheck2:main.py:127:handleKline:185239: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1440  20230326   000000    000459  1679760299  ...  27616.5  0.000503   1440    0
1441  20230326   000500    000959  1679760599  ...  27606.3 -0.000760   1441    1
1442  20230326   001000    001459  1679760899  ...  27626.8  0.000434   1442    2
1443  20230326   001500    001959  1679761199  ...  27607.1 -0.000858   1443    3
1444  20230326   002000    002459  1679761499  ...  27614.3  0.000800   1444    4

[5 rows x 11 columns]
2023-03-26 00:25:01,532:INFO:factorcheck2:main.py:128:handleKline:185239: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}


## /root/FIL/strategy/logic/log.txt ----- -----

2023-03-26 00:00:36,461:DEBUG:logic:main.py:463:getModel:885513: df_s.iloc[-5:,:] :
          date closeTime     open  ...    alpha58   alpha67   alpha72
5802  20230325    212959  27438.6  ...  49.583333  0.462668  0.576357
5803  20230325    215959  27414.6  ...  50.000000  0.480880  0.561416
5804  20230325    222959  27550.1  ...  50.000000  0.485464  0.544918
5805  20230325    225959  27584.9  ...  49.583333  0.476460  0.534876
5806  20230325    232959  27511.7  ...  50.000000  0.480822  0.523125

[5 rows x 33 columns]
0.5238970588235294
acc is : 0.5238970588235294
2023-03-26 00:00:36,655:INFO:logic:main.py:468:getModel:885513: df_pred.iloc[-5:,:] :
     pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
539     0  0.533234  0.466766       1  ...  0.944470   1.0    0.0  1.136044
540     0  0.586586  0.413414       1  ...  0.945667   1.0    0.0  1.137484
541     0  0.561986  0.438014       0  ...  0.943157   1.0    0.0  1.134465
542     0  0.529706  0.470294       1  ...  0.944271   1.0    0.0  1.135805
543     0  0.558614  0.441386       1  ...  0.947316   1.0    0.0  1.139467

[5 rows x 10 columns]
2023-03-26 00:00:36,690:INFO:logic:main.py:478:getModel:885513: df_panel.iloc[-5:,:] :
    pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
45     0  0.534171  0.465829       1  ...  0.947646   1.0    0.0  1.129802
46     0  0.587370  0.412630       1  ...  0.981466   1.0    0.0  1.133660
47     0  0.562629  0.437371       0  ...  0.978862   1.0    0.0  1.130651
48     0  0.529604  0.470396       1  ...  0.943612   1.0    0.0  1.136597
49     0  0.558614  0.441386       1  ...  0.947316   1.0    0.0  1.139467

[5 rows x 10 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': []}


## /root/FIL/strategy/modifiedmom/log.txt ----- -----

127.0.0.1 - - [26/Mar/2023 00:00:03] "POST / HTTP/1.1" 200 -
2023-03-26 00:00:03,339:INFO:modifiedmom:main.py:319:handleOrderFilled:185213: handleOrderFilled: data=OrderType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'clientorderid': '42055F1679760002773I0L59', 'symbol': 'BTCUSDT', 'gatewayorderid': 1679760002910216, 'quantity': '27.096', 'price': '27634.3', 'stopprice': '0', 'ordertype': '', 'side': 'SELL', 'status': 'FILLED', 'positionside': 'SHORT', 'createtime': 1679760002242, 'updatetime': 1679760002910, 'tradetype': 'usdt', 'selfid': 42055, 'filltrades': [TradeType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'tradeid': 1679760002910, 'clientorderid': '42055F1679760002773I0L59', 'price': '27634.3', 'quantity': '27.096', 'commission': '748.7789928', 'commissionasset': 'USDT', 'tradetime': 1679760002910, 'tradetype': 'usdt', 'gatetype': 'simulator', 'handletime': 1679760002910}], 'gatetype': 'simulator', 'handletime': 0}

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=17336 

self.closeSec=1679760599, self.tradeDate='20230326', self.openTime='000000', self.closeTime='000959', self.symbol='BTCUSDT', self.open='27631.4', self.close='27626.8'
127.0.0.1 - - [26/Mar/2023 00:10:01] "POST / HTTP/1.1" 200 -
2023-03-26 00:10:01,618:INFO:modifiedmom:main.py:144:handleKline:185213: self.closeSec=1679760599, self.tradeDate='20230326', self.openTime='000000', self.closeTime='000959',self.symbol='BTCUSDT',self.open='27631.4', self.close='27626.8'
2023-03-26 00:10:01,630:INFO:modifiedmom:main.py:145:handleKline:185213: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
572  20230325   232000    232959  1679758199  27513.7  27544.3  0.001112
573  20230325   233000    233959  1679758799  27544.2  27581.9  0.001365
574  20230325   234000    234959  1679759399  27585.4  27690.5  0.003937
575  20230325   235000    235959  1679759999  27690.5  27633.1 -0.002073
576  20230326   000000    000959  1679760599  27631.4  27626.8 -0.000228
2023-03-26 00:10:01,631:INFO:modifiedmom:main.py:146:handleKline:185213: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=17337 

self.closeSec=1679761199, self.tradeDate='20230326', self.openTime='001000', self.closeTime='001959', self.symbol='BTCUSDT', self.open='27626.8', self.close='27614.3'
127.0.0.1 - - [26/Mar/2023 00:20:05] "POST / HTTP/1.1" 200 -
2023-03-26 00:20:08,283:INFO:modifiedmom:main.py:144:handleKline:185213: self.closeSec=1679761199, self.tradeDate='20230326', self.openTime='001000', self.closeTime='001959',self.symbol='BTCUSDT',self.open='27626.8', self.close='27614.3'
2023-03-26 00:20:09,163:INFO:modifiedmom:main.py:145:handleKline:185213: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
573  20230325   233000    233959  1679758799  27544.2  27581.9  0.001365
574  20230325   234000    234959  1679759399  27585.4  27690.5  0.003937
575  20230325   235000    235959  1679759999  27690.5  27633.1 -0.002073
576  20230326   000000    000959  1679760599  27631.4  27626.8 -0.000228
577  20230326   001000    001959  1679761199  27626.8  27614.3 -0.000452
2023-03-26 00:20:09,163:INFO:modifiedmom:main.py:146:handleKline:185213: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False}


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

2023-03-26 00:00:01,996:INFO:pyemd2:main.py:127:handleKline:185189: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}
2023-03-26 00:00:02,181:INFO:pyemd2:main.py:190:insertFactor:185189: curDateTime:3260000, name:pyemd2, symbol:BTCUSDT, tradeDate:20230325, closeTime:235959, close:27633.1, total:1055364.7473673, pct_pre:-0.015757962285513627, thd:0.3331534306170557, side:sell 
127.0.0.1 - - [26/Mar/2023 00:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=17337 

self.closeSec=1679760599, self.tradeDate='20230326', self.openTime='000000', self.closeTime='000959', self.symbol='BTCUSDT', self.open='27631.4', self.close='27626.8'
2023-03-26 00:10:01,643:INFO:pyemd2:main.py:125:handleKline:185189: self.closeSec=1679760599, self.tradeDate='20230326', self.openTime='000000', self.closeTime='000959',self.symbol='BTCUSDT',self.open='27631.4', self.close='27626.8'
2023-03-26 00:10:01,669:INFO:pyemd2:main.py:126:handleKline:185189: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17420  20230325   232000    232959  1679758199  27513.7  27544.3
17421  20230325   233000    233959  1679758799  27544.2  27581.9
17422  20230325   234000    234959  1679759399  27585.4  27690.5
17423  20230325   235000    235959  1679759999  27690.5  27633.1
17424  20230326   000000    000959  1679760599  27631.4  27626.8
2023-03-26 00:10:01,669:INFO:pyemd2:main.py:127:handleKline:185189: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=17338 

self.closeSec=1679761199, self.tradeDate='20230326', self.openTime='001000', self.closeTime='001959', self.symbol='BTCUSDT', self.open='27626.8', self.close='27614.3'
127.0.0.1 - - [26/Mar/2023 00:20:05] "POST / HTTP/1.1" 200 -
2023-03-26 00:20:11,378:INFO:pyemd2:main.py:125:handleKline:185189: self.closeSec=1679761199, self.tradeDate='20230326', self.openTime='001000', self.closeTime='001959',self.symbol='BTCUSDT',self.open='27626.8', self.close='27614.3'
2023-03-26 00:20:11,521:INFO:pyemd2:main.py:126:handleKline:185189: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17421  20230325   233000    233959  1679758799  27544.2  27581.9
17422  20230325   234000    234959  1679759399  27585.4  27690.5
17423  20230325   235000    235959  1679759999  27690.5  27633.1
17424  20230326   000000    000959  1679760599  27631.4  27626.8
17425  20230326   001000    001959  1679761199  27626.8  27614.3
2023-03-26 00:20:11,521:INFO:pyemd2:main.py:127:handleKline:185189: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}


## /root/FIL/strategy/similarity/log.txt ----- -----

127.0.0.1 - - [26/Mar/2023 00:00:03] "POST / HTTP/1.1" 200 -
2023-03-26 00:00:03,136:INFO:testStrategy:main.py:308:handleOrderFilled:185174: handleOrderFilled: data=OrderType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'clientorderid': '42054F1679760002639I0L2', 'symbol': 'BTCUSDT', 'gatewayorderid': 1679760002894931, 'quantity': '42.719', 'price': '27634.3', 'stopprice': '0', 'ordertype': '', 'side': 'SELL', 'status': 'FILLED', 'positionside': 'SHORT', 'createtime': 1679760002309, 'updatetime': 1679760002894, 'tradetype': 'usdt', 'selfid': 42054, 'filltrades': [TradeType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'tradeid': 1679760002894, 'clientorderid': '42054F1679760002639I0L2', 'price': '27634.3', 'quantity': '42.719', 'commission': '1180.5096617', 'commissionasset': 'USDT', 'tradetime': 1679760002894, 'tradetype': 'usdt', 'gatetype': 'simulator', 'handletime': 1679760002894}], 'gatetype': 'simulator', 'handletime': 0}
127.0.0.1 - - [26/Mar/2023 00:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=17337 

self.closeSec=1679760599, self.tradeDate='20230326', self.openTime='000000', self.closeTime='000959', self.symbol='BTCUSDT', self.open='27631.4', self.close='27626.8'
2023-03-26 00:10:01,636:INFO:testStrategy:main.py:101:handleKline:185174: self.closeSec=1679760599, self.tradeDate='20230326', self.openTime='000000', self.closeTime='000959',self.symbol='BTCUSDT',self.open='27631.4', self.close='27626.8'
2023-03-26 00:10:01,682:INFO:testStrategy:main.py:102:handleKline:185174: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12236  20230325   232000    232959  1679758199  27513.7  27544.3
12237  20230325   233000    233959  1679758799  27544.2  27581.9
12238  20230325   234000    234959  1679759399  27585.4  27690.5
12239  20230325   235000    235959  1679759999  27690.5  27633.1
12240  20230326   000000    000959  1679760599  27631.4  27626.8
2023-03-26 00:10:01,682:INFO:testStrategy:main.py:103:handleKline:185174: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False, 'isCorr': False}

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=17338 

self.closeSec=1679761199, self.tradeDate='20230326', self.openTime='001000', self.closeTime='001959', self.symbol='BTCUSDT', self.open='27626.8', self.close='27614.3'
127.0.0.1 - - [26/Mar/2023 00:20:05] "POST / HTTP/1.1" 200 -
2023-03-26 00:20:10,855:INFO:testStrategy:main.py:101:handleKline:185174: self.closeSec=1679761199, self.tradeDate='20230326', self.openTime='001000', self.closeTime='001959',self.symbol='BTCUSDT',self.open='27626.8', self.close='27614.3'
2023-03-26 00:20:11,193:INFO:testStrategy:main.py:102:handleKline:185174: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12237  20230325   233000    233959  1679758799  27544.2  27581.9
12238  20230325   234000    234959  1679759399  27585.4  27690.5
12239  20230325   235000    235959  1679759999  27690.5  27633.1
12240  20230326   000000    000959  1679760599  27631.4  27626.8
12241  20230326   001000    001959  1679761199  27626.8  27614.3
2023-03-26 00:20:11,193:INFO:testStrategy:main.py:103:handleKline:185174: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False, 'isCorr': False}


## /root/FIL/strategy/sr_min/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=0, self.total=1000000.0, self.flagDict['side']='', self.tradeCount=0, self.count=30106
self.closeSec=1679761199, self.tradeDate='20230326', self.openTime='001500', self.closeTime='001959', self.symbol='BTCUSDT', self.open=27638.0, self.close=27614.3, self.high=27646.4, self.low=27607.1, self.vol=1525.915, self.amt=42145530.2031 
127.0.0.1 - - [26/Mar/2023 00:20:02] "POST / HTTP/1.1" 200 -
2023-03-26 00:20:06,803:INFO:sr_min:main.py:172:handleKline:449472: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5759  20230325   235500    235959  ...         0.0        0.0       0
5760  20230326   000000    000459  ...         0.0        0.0       0
5761  20230326   000500    000959  ...         0.0        0.0       0
5762  20230326   001000    001459  ...         0.0        0.0       0
5763  20230326   001500    001959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-03-26 00:20:06,853:INFO:sr_min:main.py:175:handleKline:449472: self.closeSec=1679761199, self.tradeDate='20230326', self.openTime='001500', self.closeTime='001959',self.symbol='BTCUSDT',self.open=27638.0, self.close=27614.3, self.high=27646.4, self.low=27607.1, self.vol=1525.915, self.amt=42145530.2031, ukdf['pct'].iloc[-1]=-0.000858 , ukdf['amount'].iloc[-1]=42145530.2031, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5763, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': []}
type(curSign)=<class 'int'>, curSign=0, self.sign=0
127.0.0.1 - - [26/Mar/2023 00:25:01] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=0, self.total=1000000.0, self.flagDict['side']='', self.tradeCount=0, self.count=30107
self.closeSec=1679761499, self.tradeDate='20230326', self.openTime='002000', self.closeTime='002459', self.symbol='BTCUSDT', self.open=27614.4, self.close=27636.4, self.high=27638.4, self.low=27614.3, self.vol=440.405, self.amt=12166345.6088 
2023-03-26 00:25:01,622:INFO:sr_min:main.py:172:handleKline:449472: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5760  20230326   000000    000459  ...         0.0        0.0       0
5761  20230326   000500    000959  ...         0.0        0.0       0
5762  20230326   001000    001459  ...         0.0        0.0       0
5763  20230326   001500    001959  ...         0.0        0.0       0
5764  20230326   002000    002459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-03-26 00:25:01,622:INFO:sr_min:main.py:175:handleKline:449472: self.closeSec=1679761499, self.tradeDate='20230326', self.openTime='002000', self.closeTime='002459',self.symbol='BTCUSDT',self.open=27614.4, self.close=27636.4, self.high=27638.4, self.low=27614.3, self.vol=440.405, self.amt=12166345.6088, ukdf['pct'].iloc[-1]=0.0008 , ukdf['amount'].iloc[-1]=12166345.6088, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5764, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': []}
type(curSign)=<class 'int'>, curSign=0, self.sign=0


## /root/FIL/strategy/s_rsrs/log.txt ----- -----

723  20230325   120000    155959  1679731199  ...    723  0.025766 -1.811750    -1.0
724  20230325   160000    195959  1679745599  ...    724  0.029472 -1.750828    -1.0

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '53.706', 'enterprice': '28091.1', 'countrevence': '0', 'unrealprofit': '34577.6521788501', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '27447.26779915', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-1, self.sign=-1
127.0.0.1 - - [26/Mar/2023 00:00:01] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='s_rsrs', self.symbol='BTCUSDT', interval='4h', intervalSec=14400, wid=25, thd=0.6, self.sign=-1, self.total=1507151.9559834, self.flagDict['side']='sell', self.tradeCount=27, self.count=722
self.closeSec=1679759999, self.tradeDate='20230325', self.openTime='200000', self.closeTime='235959', self.symbol='BTCUSDT', self.open=27445.7, self.close=27633.1, self.high=27788.0, self.low=27340.0, self.vol=74885.923, self.amt=2063695897.4544 
2023-03-26 00:00:01,865:INFO:s_rsrs:main.py:141:handleKline:185271: self.closeSec=1679759999, self.tradeDate='20230325', self.openTime='200000', self.closeTime='235959',self.symbol='BTCUSDT',self.open=27445.7, self.close=27633.1, self.high=27788.0, self.low=27340.0, self.vol=74885.923, self.amt=2063695897.4544 
2023-03-26 00:00:01,982:INFO:s_rsrs:main.py:142:handleKline:185271: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime  ...         vol           amt       pct
721  20230325   040000    075959  ...  124877.686  3.416321e+09 -0.013390
722  20230325   080000    115959  ...   42513.558  1.170165e+09  0.004727
723  20230325   120000    155959  ...   39018.021  1.072444e+09 -0.003450
724  20230325   160000    195959  ...   49158.275  1.348154e+09 -0.001016
725  20230325   200000    235959  ...   74885.923  2.063696e+09  0.006832

[5 rows x 11 columns]
2023-03-26 00:00:04,673:INFO:s_rsrs:main.py:151:handleKline:185271: df_s.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec  ...  index      beta    zscore  signal
721  20230325   040000    075959  1679702399  ...    721  0.018761 -1.935128    -1.0
722  20230325   080000    115959  1679716799  ...    722  0.020811 -1.877930    -1.0
723  20230325   120000    155959  1679731199  ...    723  0.025766 -1.811750    -1.0
724  20230325   160000    195959  1679745599  ...    724  0.029472 -1.750828    -1.0
725  20230325   200000    235959  1679759999  ...    725  0.033079 -1.693519    -1.0

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '53.706', 'enterprice': '28091.1', 'countrevence': '0', 'unrealprofit': '24549.0126', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '27634', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-1, self.sign=-1


