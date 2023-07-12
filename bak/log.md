# 20230713 00:26:02

## /root/FIL/strategy/amihud/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=373746.4768026, self.flagDict['side']='sell', self.tradeCount=2, self.count=17152
self.closeSec=1689178799, self.tradeDate='20230713', self.openTime='001500', self.closeTime='001959', self.symbol='BTCUSDT', self.open=30478.9, self.close=30512.0, self.high=30521.9, self.low=30440.7, self.vol=3121.93, self.amt=95183497.4191 
127.0.0.1 - - [13/Jul/2023 00:20:01] "POST / HTTP/1.1" 200 -
2023-07-13 00:20:06,359:INFO:amihud:main.py:172:handleKline:2219019: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5759  20230712   235500    235959  ...         0.0        0.0       0
5760  20230713   000000    000459  ...         0.0        0.0       0
5761  20230713   000500    000959  ...         0.0        0.0       0
5762  20230713   001000    001459  ...         0.0        0.0       0
5763  20230713   001500    001959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-07-13 00:20:06,389:INFO:amihud:main.py:175:handleKline:2219019: self.closeSec=1689178799, self.tradeDate='20230713', self.openTime='001500', self.closeTime='001959',self.symbol='BTCUSDT',self.open=30478.9, self.close=30512.0, self.high=30521.9, self.low=30440.7, self.vol=3121.93, self.amt=95183497.4191, ukdf['pct'].iloc[-1]=0.001083 , ukdf['amount'].iloc[-1]=95183497.4191, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5763, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '13.926', 'enterprice': '26864.9', 'countrevence': '0', 'unrealprofit': '-51019.2936', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '30528.5', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1
127.0.0.1 - - [13/Jul/2023 00:25:00] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=373746.4768026, self.flagDict['side']='sell', self.tradeCount=2, self.count=17153
self.closeSec=1689179099, self.tradeDate='20230713', self.openTime='002000', self.closeTime='002459', self.symbol='BTCUSDT', self.open=30512.1, self.close=30487.1, self.high=30529.0, self.low=30487.0, self.vol=2114.201, self.amt=64480913.3475 
2023-07-13 00:25:00,857:INFO:amihud:main.py:172:handleKline:2219019: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5760  20230713   000000    000459  ...         0.0        0.0       0
5761  20230713   000500    000959  ...         0.0        0.0       0
5762  20230713   001000    001459  ...         0.0        0.0       0
5763  20230713   001500    001959  ...         0.0        0.0       0
5764  20230713   002000    002459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-07-13 00:25:00,858:INFO:amihud:main.py:175:handleKline:2219019: self.closeSec=1689179099, self.tradeDate='20230713', self.openTime='002000', self.closeTime='002459',self.symbol='BTCUSDT',self.open=30512.1, self.close=30487.1, self.high=30529.0, self.low=30487.0, self.vol=2114.201, self.amt=64480913.3475, ukdf['pct'].iloc[-1]=-0.000816 , ukdf['amount'].iloc[-1]=64480913.3475, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5764, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '13.926', 'enterprice': '26864.9', 'countrevence': '0', 'unrealprofit': '-50452.76475963438', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '30487.81862413', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1


## /root/FIL/strategy/factorcheck/log.txt ----- -----


self.closeSec=1689178799, self.tradeDate='20230713', self.openTime='001500', self.closeTime='001959', self.symbol='BTCUSDT', self.open=30478.9, self.close=30512.0, self.high=30521.9, self.low=30440.7 
127.0.0.1 - - [13/Jul/2023 00:20:01] "POST / HTTP/1.1" 200 -
2023-07-13 00:20:04,084:INFO:factorcheck2:main.py:126:handleKline:2218005: self.closeSec=1689178799, self.tradeDate='20230713', self.openTime='001500', self.closeTime='001959',self.symbol='BTCUSDT',self.open=30478.9, self.close=30512.0, self.high=30521.9, self.low=30440.7   
2023-07-13 00:20:05,414:INFO:factorcheck2:main.py:127:handleKline:2218005: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1439  20230712   235500    235959  1689177599  ...  30464.0  0.000587   1727    5
1440  20230713   000000    000459  1689177899  ...  30483.4 -0.000626   1440    0
1441  20230713   000500    000959  1689178199  ...  30411.0 -0.002148   1441    1
1442  20230713   001000    001459  1689178499  ...  30406.0  0.001758   1442    2
1443  20230713   001500    001959  1689178799  ...  30440.7  0.001083   1443    3

[5 rows x 11 columns]
2023-07-13 00:20:05,424:INFO:factorcheck2:main.py:128:handleKline:2218005: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=191, self.factor=0.36135276213426515, self.count=17155 

self.closeSec=1689179099, self.tradeDate='20230713', self.openTime='002000', self.closeTime='002459', self.symbol='BTCUSDT', self.open=30512.1, self.close=30487.1, self.high=30529.0, self.low=30487.0 
127.0.0.1 - - [13/Jul/2023 00:25:00] "POST / HTTP/1.1" 200 -
2023-07-13 00:25:00,773:INFO:factorcheck2:main.py:126:handleKline:2218005: self.closeSec=1689179099, self.tradeDate='20230713', self.openTime='002000', self.closeTime='002459',self.symbol='BTCUSDT',self.open=30512.1, self.close=30487.1, self.high=30529.0, self.low=30487.0   
2023-07-13 00:25:00,786:INFO:factorcheck2:main.py:127:handleKline:2218005: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1440  20230713   000000    000459  1689177899  ...  30483.4 -0.000626   1440    0
1441  20230713   000500    000959  1689178199  ...  30411.0 -0.002148   1441    1
1442  20230713   001000    001459  1689178499  ...  30406.0  0.001758   1442    2
1443  20230713   001500    001959  1689178799  ...  30440.7  0.001083   1443    3
1444  20230713   002000    002459  1689179099  ...  30487.0 -0.000816   1444    4

[5 rows x 11 columns]
2023-07-13 00:25:00,786:INFO:factorcheck2:main.py:128:handleKline:2218005: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}


## /root/FIL/strategy/logic/log.txt ----- -----

2023-07-13 00:00:21,466:DEBUG:logic:main.py:463:getModel:2218526: df_s.iloc[-5:,:] :
          date closeTime     open  ...    alpha58   alpha67   alpha72
5802  20230712    212959  30709.2  ...  50.416667  0.530864  0.341326
5803  20230712    215959  30645.0  ...  50.416667  0.532121  0.355469
5804  20230712    222959  30650.3  ...  50.833333  0.548110  0.361003
5805  20230712    225959  30718.8  ...  50.833333  0.549598  0.368612
5806  20230712    232959  30725.4  ...  50.833333  0.531597  0.384327

[5 rows x 33 columns]
0.5661764705882353
acc is : 0.5661764705882353
2023-07-13 00:00:21,547:INFO:logic:main.py:468:getModel:2218526: df_pred.iloc[-5:,:] :
     pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
539     1  0.482807  0.517193       1  ...  1.014073   1.0    0.0  1.006641
540     1  0.497002  0.502998       1  ...  1.016343   1.0    0.0  1.008894
541     0  0.516628  0.483372       1  ...  1.016558   1.0    0.0  1.009107
542     0  0.501569  0.498431       0  ...  1.014391   1.0    0.0  1.006956
543     1  0.485403  0.514597       0  ...  1.009435   1.0    0.0  1.002036

[5 rows x 10 columns]
2023-07-13 00:00:21,559:INFO:logic:main.py:478:getModel:2218526: df_panel.iloc[-5:,:] :
    pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
45     1  0.483433  0.516567       1  ...  1.014073   1.0    0.0  1.007783
46     1  0.497004  0.502996       1  ...  1.016343   1.0    0.0  1.009113
47     0  0.516605  0.483395       1  ...  1.016558   1.0    0.0  1.009326
48     0  0.502069  0.497931       0  ...  1.014391   1.0    0.0  1.008006
49     1  0.485403  0.514597       0  ...  1.009435   1.0    0.0  1.002036

[5 rows x 10 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '24.383', 'enterprice': '30486.7', 'countrevence': '0', 'unrealprofit': '473.92390863602', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '30506.13665294', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}


## /root/FIL/strategy/modifiedmom/log.txt ----- -----

127.0.0.1 - - [13/Jul/2023 00:00:04] "POST / HTTP/1.1" 200 -
2023-07-13 00:00:04,672:INFO:modifiedmom:main.py:319:handleOrderFilled:2218259: handleOrderFilled: data=OrderType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'clientorderid': '42601F1689177603718I0L59', 'symbol': 'BTCUSDT', 'gatewayorderid': 1689177604100160, 'quantity': '24.856', 'price': '30508.1', 'stopprice': '0', 'ordertype': '', 'side': 'SELL', 'status': 'FILLED', 'positionside': 'SHORT', 'createtime': 1689177602723, 'updatetime': 1689177604100, 'tradetype': 'usdt', 'selfid': 42601, 'filltrades': [TradeType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'tradeid': 1689177604100, 'clientorderid': '42601F1689177603718I0L59', 'price': '30508.1', 'quantity': '24.856', 'commission': '758.3093336', 'commissionasset': 'USDT', 'tradetime': 1689177604100, 'tradetype': 'usdt', 'gatetype': 'simulator', 'handletime': 1689177604100}], 'gatetype': 'simulator', 'handletime': 0}
127.0.0.1 - - [13/Jul/2023 00:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=8576 

self.closeSec=1689178199, self.tradeDate='20230713', self.openTime='000000', self.closeTime='000959', self.symbol='BTCUSDT', self.open='30510.1', self.close='30425.5'
2023-07-13 00:10:01,094:INFO:modifiedmom:main.py:144:handleKline:2218259: self.closeSec=1689178199, self.tradeDate='20230713', self.openTime='000000', self.closeTime='000959',self.symbol='BTCUSDT',self.open='30510.1', self.close='30425.5'
2023-07-13 00:10:01,108:INFO:modifiedmom:main.py:145:handleKline:2218259: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
572  20230712   232000    232959  1689175799    30693  30659.8 -0.001082
573  20230712   233000    233959  1689176399  30659.9    30574 -0.002798
574  20230712   234000    234959  1689176999  30573.9    30530 -0.001439
575  20230712   235000    235959  1689177599    30533  30510.2 -0.000649
576  20230713   000000    000959  1689178199  30510.1  30425.5 -0.002776
2023-07-13 00:10:01,108:INFO:modifiedmom:main.py:146:handleKline:2218259: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=8577 

self.closeSec=1689178799, self.tradeDate='20230713', self.openTime='001000', self.closeTime='001959', self.symbol='BTCUSDT', self.open='30424.2', self.close='30512'
127.0.0.1 - - [13/Jul/2023 00:20:04] "POST / HTTP/1.1" 200 -
2023-07-13 00:20:06,310:INFO:modifiedmom:main.py:144:handleKline:2218259: self.closeSec=1689178799, self.tradeDate='20230713', self.openTime='001000', self.closeTime='001959',self.symbol='BTCUSDT',self.open='30424.2', self.close='30512'
2023-07-13 00:20:07,070:INFO:modifiedmom:main.py:145:handleKline:2218259: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
573  20230712   233000    233959  1689176399  30659.9    30574 -0.002798
574  20230712   234000    234959  1689176999  30573.9    30530 -0.001439
575  20230712   235000    235959  1689177599    30533  30510.2 -0.000649
576  20230713   000000    000959  1689178199  30510.1  30425.5 -0.002776
577  20230713   001000    001959  1689178799  30424.2    30512  0.002843
2023-07-13 00:20:07,070:INFO:modifiedmom:main.py:146:handleKline:2218259: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False}


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

2023-07-13 00:00:02,192:INFO:pyemd2:main.py:127:handleKline:2217508: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}
2023-07-13 00:00:02,332:INFO:pyemd2:main.py:190:insertFactor:2217508: curDateTime:7130000, name:pyemd2, symbol:BTCUSDT, tradeDate:20230712, closeTime:235959, close:30510.2, total:999016.855404, pct_pre:0.005375534443360586, thd:-0.18691212092234222, side:sell 
127.0.0.1 - - [13/Jul/2023 00:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=8579 

self.closeSec=1689178199, self.tradeDate='20230713', self.openTime='000000', self.closeTime='000959', self.symbol='BTCUSDT', self.open='30510.1', self.close='30425.5'
2023-07-13 00:10:01,097:INFO:pyemd2:main.py:125:handleKline:2217508: self.closeSec=1689178199, self.tradeDate='20230713', self.openTime='000000', self.closeTime='000959',self.symbol='BTCUSDT',self.open='30510.1', self.close='30425.5'
2023-07-13 00:10:01,119:INFO:pyemd2:main.py:126:handleKline:2217508: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17420  20230712   232000    232959  1689175799    30693  30659.8
17421  20230712   233000    233959  1689176399  30659.9    30574
17422  20230712   234000    234959  1689176999  30573.9    30530
17423  20230712   235000    235959  1689177599    30533  30510.2
17424  20230713   000000    000959  1689178199  30510.1  30425.5
2023-07-13 00:10:01,119:INFO:pyemd2:main.py:127:handleKline:2217508: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=8580 

self.closeSec=1689178799, self.tradeDate='20230713', self.openTime='001000', self.closeTime='001959', self.symbol='BTCUSDT', self.open='30424.2', self.close='30512'
127.0.0.1 - - [13/Jul/2023 00:20:04] "POST / HTTP/1.1" 200 -
2023-07-13 00:20:07,943:INFO:pyemd2:main.py:125:handleKline:2217508: self.closeSec=1689178799, self.tradeDate='20230713', self.openTime='001000', self.closeTime='001959',self.symbol='BTCUSDT',self.open='30424.2', self.close='30512'
2023-07-13 00:20:08,115:INFO:pyemd2:main.py:126:handleKline:2217508: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17421  20230712   233000    233959  1689176399  30659.9    30574
17422  20230712   234000    234959  1689176999  30573.9    30530
17423  20230712   235000    235959  1689177599    30533  30510.2
17424  20230713   000000    000959  1689178199  30510.1  30425.5
17425  20230713   001000    001959  1689178799  30424.2    30512
2023-07-13 00:20:08,116:INFO:pyemd2:main.py:127:handleKline:2217508: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}


## /root/FIL/strategy/similarity/log.txt ----- -----

127.0.0.1 - - [13/Jul/2023 00:00:04] "POST / HTTP/1.1" 200 -
2023-07-13 00:00:04,331:INFO:testStrategy:main.py:308:handleOrderFilled:2217133: handleOrderFilled: data=OrderType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'clientorderid': '42600F1689177603641I0L2', 'symbol': 'BTCUSDT', 'gatewayorderid': 1689177604033121, 'quantity': '36.516', 'price': '30508.2', 'stopprice': '0', 'ordertype': '', 'side': 'BUY', 'status': 'FILLED', 'positionside': 'LONG', 'createtime': 1689177602745, 'updatetime': 1689177604033, 'tradetype': 'usdt', 'selfid': 42600, 'filltrades': [TradeType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'tradeid': 1689177604033, 'clientorderid': '42600F1689177603641I0L2', 'price': '30508.2', 'quantity': '36.516', 'commission': '1114.0374312', 'commissionasset': 'USDT', 'tradetime': 1689177604033, 'tradetype': 'usdt', 'gatetype': 'simulator', 'handletime': 1689177604033}], 'gatetype': 'simulator', 'handletime': 0}
127.0.0.1 - - [13/Jul/2023 00:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=8579 

self.closeSec=1689178199, self.tradeDate='20230713', self.openTime='000000', self.closeTime='000959', self.symbol='BTCUSDT', self.open='30510.1', self.close='30425.5'
2023-07-13 00:10:01,091:INFO:testStrategy:main.py:101:handleKline:2217133: self.closeSec=1689178199, self.tradeDate='20230713', self.openTime='000000', self.closeTime='000959',self.symbol='BTCUSDT',self.open='30510.1', self.close='30425.5'
2023-07-13 00:10:01,112:INFO:testStrategy:main.py:102:handleKline:2217133: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12236  20230712   232000    232959  1689175799    30693  30659.8
12237  20230712   233000    233959  1689176399  30659.9    30574
12238  20230712   234000    234959  1689176999  30573.9    30530
12239  20230712   235000    235959  1689177599    30533  30510.2
12240  20230713   000000    000959  1689178199  30510.1  30425.5
2023-07-13 00:10:01,113:INFO:testStrategy:main.py:103:handleKline:2217133: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False, 'isCorr': False}

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=8580 

self.closeSec=1689178799, self.tradeDate='20230713', self.openTime='001000', self.closeTime='001959', self.symbol='BTCUSDT', self.open='30424.2', self.close='30512'
127.0.0.1 - - [13/Jul/2023 00:20:04] "POST / HTTP/1.1" 200 -
2023-07-13 00:20:07,751:INFO:testStrategy:main.py:101:handleKline:2217133: self.closeSec=1689178799, self.tradeDate='20230713', self.openTime='001000', self.closeTime='001959',self.symbol='BTCUSDT',self.open='30424.2', self.close='30512'
2023-07-13 00:20:07,998:INFO:testStrategy:main.py:102:handleKline:2217133: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12237  20230712   233000    233959  1689176399  30659.9    30574
12238  20230712   234000    234959  1689176999  30573.9    30530
12239  20230712   235000    235959  1689177599    30533  30510.2
12240  20230713   000000    000959  1689178199  30510.1  30425.5
12241  20230713   001000    001959  1689178799  30424.2    30512
2023-07-13 00:20:08,000:INFO:testStrategy:main.py:103:handleKline:2217133: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False, 'isCorr': False}


## /root/FIL/strategy/sr_min/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=1, self.total=996015.990996, self.flagDict['side']='buy', self.tradeCount=1, self.count=17152
self.closeSec=1689178799, self.tradeDate='20230713', self.openTime='001500', self.closeTime='001959', self.symbol='BTCUSDT', self.open=30478.9, self.close=30512.0, self.high=30521.9, self.low=30440.7, self.vol=3121.93, self.amt=95183497.4191 
127.0.0.1 - - [13/Jul/2023 00:20:01] "POST / HTTP/1.1" 200 -
2023-07-13 00:20:06,359:INFO:sr_min:main.py:172:handleKline:2219263: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5759  20230712   235500    235959  ...         0.0        0.0       0
5760  20230713   000000    000459  ...         0.0        0.0       0
5761  20230713   000500    000959  ...         0.0        0.0       0
5762  20230713   001000    001459  ...         0.0        0.0       0
5763  20230713   001500    001959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-07-13 00:20:06,380:INFO:sr_min:main.py:175:handleKline:2219263: self.closeSec=1689178799, self.tradeDate='20230713', self.openTime='001500', self.closeTime='001959',self.symbol='BTCUSDT',self.open=30478.9, self.close=30512.0, self.high=30521.9, self.low=30440.7, self.vol=3121.93, self.amt=95183497.4191, ukdf['pct'].iloc[-1]=0.001083 , ukdf['amount'].iloc[-1]=95183497.4191, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5763, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '37.141', 'enterprice': '26844', 'countrevence': '0', 'unrealprofit': '136846.0145', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '30528.5', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=1
127.0.0.1 - - [13/Jul/2023 00:25:00] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=1, self.total=996015.990996, self.flagDict['side']='buy', self.tradeCount=1, self.count=17153
self.closeSec=1689179099, self.tradeDate='20230713', self.openTime='002000', self.closeTime='002459', self.symbol='BTCUSDT', self.open=30512.1, self.close=30487.1, self.high=30529.0, self.low=30487.0, self.vol=2114.201, self.amt=64480913.3475 
2023-07-13 00:25:00,861:INFO:sr_min:main.py:172:handleKline:2219263: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5760  20230713   000000    000459  ...         0.0        0.0       0
5761  20230713   000500    000959  ...         0.0        0.0       0
5762  20230713   001000    001459  ...         0.0        0.0       0
5763  20230713   001500    001959  ...         0.0        0.0       0
5764  20230713   002000    002459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-07-13 00:25:00,861:INFO:sr_min:main.py:175:handleKline:2219263: self.closeSec=1689179099, self.tradeDate='20230713', self.openTime='002000', self.closeTime='002459',self.symbol='BTCUSDT',self.open=30512.1, self.close=30487.1, self.high=30529.0, self.low=30487.0, self.vol=2114.201, self.amt=64480913.3475, ukdf['pct'].iloc[-1]=-0.000816 , ukdf['amount'].iloc[-1]=64480913.3475, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5764, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '37.141', 'enterprice': '26844', 'countrevence': '0', 'unrealprofit': '135335.06751881233', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '30487.81862413', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=1


## /root/FIL/strategy/s_rsrs/log.txt ----- -----

722  20230712   080000    115959  ...   28484.366  8.705943e+08 -0.000885
723  20230712   120000    155959  ...   50264.091  1.543709e+09  0.004889
724  20230712   160000    195959  ...   33657.850  1.033479e+09  0.001123
725  20230712   200000    235959  ...  198941.331  6.108353e+09 -0.008295

[5 rows x 11 columns]
2023-07-13 00:00:03,578:INFO:s_rsrs:main.py:151:handleKline:2218689: df_s.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec  ...  index      beta    zscore  signal
721  20230712   040000    075959  1689119999  ...    721  0.249948 -0.076812     NaN
722  20230712   080000    115959  1689134399  ...    722  0.263795 -0.019669     NaN
723  20230712   120000    155959  1689148799  ...    723  0.355324  0.374296     NaN
724  20230712   160000    195959  1689163199  ...    724  0.347269  0.325733     NaN
725  20230712   200000    235959  1689177599  ...    725  0.413594  0.605172     1.0

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '53.015', 'enterprice': '30303.5', 'countrevence': '0', 'unrealprofit': '-10992.7028698188', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '30510.85080392', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=1, self.sign=-1
handlebackTrade > queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '53.015', 'enterprice': '30303.5', 'countrevence': '0', 'unrealprofit': '-11006.17491703355', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '30511.10492157', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
2023-07-13 00:00:10,445:INFO:s_rsrs:main.py:182:queryContractAssets:2218689: queryContractAssets: assets=ContractAssetReturn{'result': [ContractAsset{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'asset': 'USDT', 'free': '1598682.3100041', 'total': '1598682.3100041', 'margin': '0', 'unreal': '0', 'type': 'AssetType_ucontract'}]}
2023-07-13 00:00:10,992:DEBUG:s_rsrs:main.py:253:openBuy:2218689: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': True, 'isCloseBuy': False, 'isCloseSell': False, 'isOpen': True, 'isClose': False, 'isTrig': False}
2023-07-13 00:00:10,992:INFO:s_rsrs:main.py:254:openBuy:2218689: ret = self.client.insertMarketUOrder("simulator", "BTCUSDT", 52.241, "buy"), ret=InsertOrderReturn{'result': 'success', 'clientorderid': '42603F1689177610990I0L65'}
2023-07-13 00:00:11,033:INFO:s_rsrs:main.py:176:insertFactor:2218689: curDateTime:7130000, name:s_rsrs, symbol:BTCUSDT, tradeDate:20230712, closeTime:235959, close:30510.1, sign:1, total:1598682.3100041, side:buy  
127.0.0.1 - - [13/Jul/2023 00:00:11] "POST / HTTP/1.1" 200 -
2023-07-13 00:00:11,038:INFO:s_rsrs:main.py:343:handleOrderNew:2218689: handleOrderNew: data=OrderType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'clientorderid': '42602F1689177605351I0L65', 'symbol': 'BTCUSDT', 'gatewayorderid': 1689177605803988, 'quantity': '53.015', 'price': '30506.5', 'stopprice': '0', 'ordertype': '', 'side': 'BUY', 'status': 'FILLED', 'positionside': 'LONG', 'createtime': 1689177604449, 'updatetime': 1689177605803, 'tradetype': 'usdt', 'selfid': 42602, 'filltrades': [TradeType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'tradeid': 1689177605803, 'clientorderid': '42602F1689177605351I0L65', 'price': '30506.5', 'quantity': '53.015', 'commission': '1617.3020975', 'commissionasset': 'USDT', 'tradetime': 1689177605803, 'tradetype': 'usdt', 'gatetype': 'simulator', 'handletime': 1689177605803}], 'gatetype': 'simulator', 'handletime': 0}
127.0.0.1 - - [13/Jul/2023 00:00:11] "POST / HTTP/1.1" 200 -
2023-07-13 00:00:11,043:INFO:s_rsrs:main.py:346:handleOrderFilled:2218689: handleOrderFilled: data=OrderType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'clientorderid': '42602F1689177605351I0L65', 'symbol': 'BTCUSDT', 'gatewayorderid': 1689177605803988, 'quantity': '53.015', 'price': '30506.5', 'stopprice': '0', 'ordertype': '', 'side': 'BUY', 'status': 'FILLED', 'positionside': 'LONG', 'createtime': 1689177604449, 'updatetime': 1689177605803, 'tradetype': 'usdt', 'selfid': 42602, 'filltrades': [TradeType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'tradeid': 1689177605803, 'clientorderid': '42602F1689177605351I0L65', 'price': '30506.5', 'quantity': '53.015', 'commission': '1617.3020975', 'commissionasset': 'USDT', 'tradetime': 1689177605803, 'tradetype': 'usdt', 'gatetype': 'simulator', 'handletime': 1689177605803}], 'gatetype': 'simulator', 'handletime': 0}
127.0.0.1 - - [13/Jul/2023 00:00:11] "POST / HTTP/1.1" 200 -
2023-07-13 00:00:11,435:INFO:s_rsrs:main.py:343:handleOrderNew:2218689: handleOrderNew: data=OrderType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'clientorderid': '42603F1689177610990I0L65', 'symbol': 'BTCUSDT', 'gatewayorderid': 1689177611406259, 'quantity': '52.241', 'price': '30511.1', 'stopprice': '0', 'ordertype': '', 'side': 'BUY', 'status': 'FILLED', 'positionside': 'LONG', 'createtime': 1689177610458, 'updatetime': 1689177611406, 'tradetype': 'usdt', 'selfid': 42603, 'filltrades': [TradeType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'tradeid': 1689177611406, 'clientorderid': '42603F1689177610990I0L65', 'price': '30511.1', 'quantity': '52.241', 'commission': '1593.9303751', 'commissionasset': 'USDT', 'tradetime': 1689177611406, 'tradetype': 'usdt', 'gatetype': 'simulator', 'handletime': 1689177611406}], 'gatetype': 'simulator', 'handletime': 0}
127.0.0.1 - - [13/Jul/2023 00:00:11] "POST / HTTP/1.1" 200 -
2023-07-13 00:00:11,802:INFO:s_rsrs:main.py:346:handleOrderFilled:2218689: handleOrderFilled: data=OrderType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'clientorderid': '42603F1689177610990I0L65', 'symbol': 'BTCUSDT', 'gatewayorderid': 1689177611406259, 'quantity': '52.241', 'price': '30511.1', 'stopprice': '0', 'ordertype': '', 'side': 'BUY', 'status': 'FILLED', 'positionside': 'LONG', 'createtime': 1689177610458, 'updatetime': 1689177611406, 'tradetype': 'usdt', 'selfid': 42603, 'filltrades': [TradeType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'tradeid': 1689177611406, 'clientorderid': '42603F1689177610990I0L65', 'price': '30511.1', 'quantity': '52.241', 'commission': '1593.9303751', 'commissionasset': 'USDT', 'tradetime': 1689177611406, 'tradetype': 'usdt', 'gatetype': 'simulator', 'handletime': 1689177611406}], 'gatetype': 'simulator', 'handletime': 0}


