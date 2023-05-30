# 20230531 00:26:01

## /root/FIL/strategy/amihud/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=373746.4768026, self.flagDict['side']='sell', self.tradeCount=2, self.count=4768
self.closeSec=1685463599, self.tradeDate='20230531', self.openTime='001500', self.closeTime='001959', self.symbol='BTCUSDT', self.open=27617.5, self.close=27593.9, self.high=27636.6, self.low=27530.0, self.vol=6706.534, self.amt=184958869.37968 
127.0.0.1 - - [31/May/2023 00:20:01] "POST / HTTP/1.1" 200 -
2023-05-31 00:20:06,962:INFO:amihud:main.py:172:handleKline:2219019: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5759  20230530   235500    235959  ...         0.0        0.0       0
5760  20230531   000000    000459  ...         0.0        0.0       0
5761  20230531   000500    000959  ...         0.0        0.0       0
5762  20230531   001000    001459  ...         0.0        0.0       0
5763  20230531   001500    001959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-05-31 00:20:06,988:INFO:amihud:main.py:175:handleKline:2219019: self.closeSec=1685463599, self.tradeDate='20230531', self.openTime='001500', self.closeTime='001959',self.symbol='BTCUSDT',self.open=27617.5, self.close=27593.9, self.high=27636.6, self.low=27530.0, self.vol=6706.534, self.amt=184958869.37968, ukdf['pct'].iloc[-1]=-0.000851 , ukdf['amount'].iloc[-1]=184958869.37968, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5763, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '13.926', 'enterprice': '26864.9', 'countrevence': '0', 'unrealprofit': '-10214.721', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '27598.4', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1
--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=373746.4768026, self.flagDict['side']='sell', self.tradeCount=2, self.count=4769
self.closeSec=1685463899, self.tradeDate='20230531', self.openTime='002000', self.closeTime='002459', self.symbol='BTCUSDT', self.open=27593.8, self.close=27681.4, self.high=27684.0, self.low=27593.8, self.vol=2396.17, self.amt=66240505.6029 
127.0.0.1 - - [31/May/2023 00:25:00] "POST / HTTP/1.1" 200 -
2023-05-31 00:25:00,756:INFO:amihud:main.py:172:handleKline:2219019: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5760  20230531   000000    000459  ...         0.0        0.0       0
5761  20230531   000500    000959  ...         0.0        0.0       0
5762  20230531   001000    001459  ...         0.0        0.0       0
5763  20230531   001500    001959  ...         0.0        0.0       0
5764  20230531   002000    002459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-05-31 00:25:00,756:INFO:amihud:main.py:175:handleKline:2219019: self.closeSec=1685463899, self.tradeDate='20230531', self.openTime='002000', self.closeTime='002459',self.symbol='BTCUSDT',self.open=27593.8, self.close=27681.4, self.high=27684.0, self.low=27593.8, self.vol=2396.17, self.amt=66240505.6029, ukdf['pct'].iloc[-1]=0.003171 , ukdf['amount'].iloc[-1]=66240505.6029, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5764, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '13.926', 'enterprice': '26864.9', 'countrevence': '0', 'unrealprofit': '-11371.82842010952', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '27681.48971852', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1


## /root/FIL/strategy/factorcheck/log.txt ----- -----


self.closeSec=1685463599, self.tradeDate='20230531', self.openTime='001500', self.closeTime='001959', self.symbol='BTCUSDT', self.open=27617.5, self.close=27593.9, self.high=27636.6, self.low=27530.0 
127.0.0.1 - - [31/May/2023 00:20:01] "POST / HTTP/1.1" 200 -
2023-05-31 00:20:04,338:INFO:factorcheck2:main.py:126:handleKline:2218005: self.closeSec=1685463599, self.tradeDate='20230531', self.openTime='001500', self.closeTime='001959',self.symbol='BTCUSDT',self.open=27617.5, self.close=27593.9, self.high=27636.6, self.low=27530.0   
2023-05-31 00:20:05,778:INFO:factorcheck2:main.py:127:handleKline:2218005: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1439  20230530   235500    235959  1685462399  ...  27657.4 -0.000499   1727    5
1440  20230531   000000    000459  1685462699  ...  27620.2 -0.000687   1440    0
1441  20230531   000500    000959  1685462999  ...  27630.0  0.001736   1441    1
1442  20230531   001000    001459  1685463299  ...  27611.6 -0.002762   1442    2
1443  20230531   001500    001959  1685463599  ...  27530.0 -0.000851   1443    3

[5 rows x 11 columns]
2023-05-31 00:20:05,788:INFO:factorcheck2:main.py:128:handleKline:2218005: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}
127.0.0.1 - - [31/May/2023 00:25:00] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=195, self.factor=0.4454920678899192, self.count=4771 

self.closeSec=1685463899, self.tradeDate='20230531', self.openTime='002000', self.closeTime='002459', self.symbol='BTCUSDT', self.open=27593.8, self.close=27681.4, self.high=27684.0, self.low=27593.8 
2023-05-31 00:25:00,726:INFO:factorcheck2:main.py:126:handleKline:2218005: self.closeSec=1685463899, self.tradeDate='20230531', self.openTime='002000', self.closeTime='002459',self.symbol='BTCUSDT',self.open=27593.8, self.close=27681.4, self.high=27684.0, self.low=27593.8   
2023-05-31 00:25:00,812:INFO:factorcheck2:main.py:127:handleKline:2218005: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1440  20230531   000000    000459  1685462699  ...  27620.2 -0.000687   1440    0
1441  20230531   000500    000959  1685462999  ...  27630.0  0.001736   1441    1
1442  20230531   001000    001459  1685463299  ...  27611.6 -0.002762   1442    2
1443  20230531   001500    001959  1685463599  ...  27530.0 -0.000851   1443    3
1444  20230531   002000    002459  1685463899  ...  27593.8  0.003171   1444    4

[5 rows x 11 columns]
2023-05-31 00:25:00,813:INFO:factorcheck2:main.py:128:handleKline:2218005: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}


## /root/FIL/strategy/logic/log.txt ----- -----

2023-05-31 00:00:33,053:DEBUG:logic:main.py:463:getModel:2218526: df_s.iloc[-5:,:] :
          date closeTime     open  ...    alpha58   alpha67   alpha72
5802  20230530    212959  27887.1  ...  51.666667  0.566372  0.376946
5803  20230530    215959  27937.6  ...  51.666667  0.529048  0.384925
5804  20230530    222959  27787.9  ...  51.250000  0.522647  0.395951
5805  20230530    225959  27760.9  ...  51.250000  0.488946  0.426223
5806  20230530    232959  27609.5  ...  51.666667  0.500184  0.447650

[5 rows x 33 columns]
0.5294117647058824
acc is : 0.5294117647058824
2023-05-31 00:00:33,213:INFO:logic:main.py:468:getModel:2218526: df_pred.iloc[-5:,:] :
     pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
539     0  0.504209  0.495791       0  ...  1.001649  -1.0    0.0  1.035243
540     1  0.456828  0.543172       0  ...  1.002626  -1.0    0.0  1.034234
541     1  0.470357  0.529643       0  ...  1.008090  -1.0    0.0  1.028597
542     1  0.448142  0.551858       1  ...  1.006203  -1.0    0.0  1.030523
543     1  0.485075  0.514925       1  ...  1.006068  -1.0    0.0  1.030661

[5 rows x 10 columns]
2023-05-31 00:00:33,249:INFO:logic:main.py:478:getModel:2218526: df_panel.iloc[-5:,:] :
    pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
45     0  0.504007  0.495993       0  ...  1.001649  -1.0    0.0  1.033480
46     1  0.456636  0.543364       0  ...  1.002626  -1.0    0.0  1.032345
47     1  0.470402  0.529598       0  ...  1.008090  -1.0    0.0  1.026719
48     1  0.448085  0.551915       1  ...  1.006203  -1.0    0.0  1.029105
49     1  0.485075  0.514925       1  ...  1.006068  -1.0    0.0  1.030661

[5 rows x 10 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '25.849', 'enterprice': '27935.3', 'countrevence': '0', 'unrealprofit': '7147.09723552935', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '27658.80585185', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}


## /root/FIL/strategy/modifiedmom/log.txt ----- -----

127.0.0.1 - - [31/May/2023 00:00:04] "POST / HTTP/1.1" 200 -
2023-05-31 00:00:04,404:INFO:modifiedmom:main.py:319:handleOrderFilled:2218259: handleOrderFilled: data=OrderType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'clientorderid': '42290F1685462403741I0L59', 'symbol': 'BTCUSDT', 'gatewayorderid': 1685462404141967, 'quantity': '25.174', 'price': '27664.9', 'stopprice': '0', 'ordertype': '', 'side': 'SELL', 'status': 'FILLED', 'positionside': 'SHORT', 'createtime': 1685462402828, 'updatetime': 1685462404141, 'tradetype': 'usdt', 'selfid': 42290, 'filltrades': [TradeType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'tradeid': 1685462404141, 'clientorderid': '42290F1685462403741I0L59', 'price': '27664.9', 'quantity': '25.174', 'commission': '696.4361926', 'commissionasset': 'USDT', 'tradetime': 1685462404141, 'tradetype': 'usdt', 'gatetype': 'simulator', 'handletime': 1685462404141}], 'gatetype': 'simulator', 'handletime': 0}
127.0.0.1 - - [31/May/2023 00:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=2384 

self.closeSec=1685462999, self.tradeDate='20230531', self.openTime='000000', self.closeTime='000959', self.symbol='BTCUSDT', self.open='27665', self.close='27693.9'
2023-05-31 00:10:01,152:INFO:modifiedmom:main.py:144:handleKline:2218259: self.closeSec=1685462999, self.tradeDate='20230531', self.openTime='000000', self.closeTime='000959',self.symbol='BTCUSDT',self.open='27665', self.close='27693.9'
2023-05-31 00:10:01,168:INFO:modifiedmom:main.py:145:handleKline:2218259: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
572  20230530   232000    232959  1685460599  27703.5  27661.2 -0.001527
573  20230530   233000    233959  1685461199  27661.2    27700  0.001403
574  20230530   234000    234959  1685461799  27699.4  27695.5 -0.000162
575  20230530   235000    235959  1685462399  27697.8    27665 -0.001101
576  20230531   000000    000959  1685462999    27665  27693.9  0.001045
2023-05-31 00:10:01,168:INFO:modifiedmom:main.py:146:handleKline:2218259: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=2385 

self.closeSec=1685463599, self.tradeDate='20230531', self.openTime='001000', self.closeTime='001959', self.symbol='BTCUSDT', self.open='27689.3', self.close='27593.9'
127.0.0.1 - - [31/May/2023 00:20:04] "POST / HTTP/1.1" 200 -
2023-05-31 00:20:07,128:INFO:modifiedmom:main.py:144:handleKline:2218259: self.closeSec=1685463599, self.tradeDate='20230531', self.openTime='001000', self.closeTime='001959',self.symbol='BTCUSDT',self.open='27689.3', self.close='27593.9'
2023-05-31 00:20:07,848:INFO:modifiedmom:main.py:145:handleKline:2218259: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
573  20230530   233000    233959  1685461199  27661.2    27700  0.001403
574  20230530   234000    234959  1685461799  27699.4  27695.5 -0.000162
575  20230530   235000    235959  1685462399  27697.8    27665 -0.001101
576  20230531   000000    000959  1685462999    27665  27693.9  0.001045
577  20230531   001000    001959  1685463599  27689.3  27593.9 -0.003611
2023-05-31 00:20:07,849:INFO:modifiedmom:main.py:146:handleKline:2218259: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False}


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

2023-05-31 00:00:02,327:INFO:pyemd2:main.py:127:handleKline:2217508: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}
2023-05-31 00:00:02,448:INFO:pyemd2:main.py:190:insertFactor:2217508: curDateTime:5310000, name:pyemd2, symbol:BTCUSDT, tradeDate:20230530, closeTime:235959, close:27665, total:971927.4245254, pct_pre:0.007112005035559976, thd:-0.10712702731918217, side:sell 

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=2387 

self.closeSec=1685462999, self.tradeDate='20230531', self.openTime='000000', self.closeTime='000959', self.symbol='BTCUSDT', self.open='27665', self.close='27693.9'
2023-05-31 00:10:01,149:INFO:pyemd2:main.py:125:handleKline:2217508: self.closeSec=1685462999, self.tradeDate='20230531', self.openTime='000000', self.closeTime='000959',self.symbol='BTCUSDT',self.open='27665', self.close='27693.9'
127.0.0.1 - - [31/May/2023 00:10:01] "POST / HTTP/1.1" 200 -
2023-05-31 00:10:01,173:INFO:pyemd2:main.py:126:handleKline:2217508: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17420  20230530   232000    232959  1685460599  27703.5  27661.2
17421  20230530   233000    233959  1685461199  27661.2    27700
17422  20230530   234000    234959  1685461799  27699.4  27695.5
17423  20230530   235000    235959  1685462399  27697.8    27665
17424  20230531   000000    000959  1685462999    27665  27693.9
2023-05-31 00:10:01,173:INFO:pyemd2:main.py:127:handleKline:2217508: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=2388 

self.closeSec=1685463599, self.tradeDate='20230531', self.openTime='001000', self.closeTime='001959', self.symbol='BTCUSDT', self.open='27689.3', self.close='27593.9'
127.0.0.1 - - [31/May/2023 00:20:04] "POST / HTTP/1.1" 200 -
2023-05-31 00:20:08,932:INFO:pyemd2:main.py:125:handleKline:2217508: self.closeSec=1685463599, self.tradeDate='20230531', self.openTime='001000', self.closeTime='001959',self.symbol='BTCUSDT',self.open='27689.3', self.close='27593.9'
2023-05-31 00:20:09,032:INFO:pyemd2:main.py:126:handleKline:2217508: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17421  20230530   233000    233959  1685461199  27661.2    27700
17422  20230530   234000    234959  1685461799  27699.4  27695.5
17423  20230530   235000    235959  1685462399  27697.8    27665
17424  20230531   000000    000959  1685462999    27665  27693.9
17425  20230531   001000    001959  1685463599  27689.3  27593.9
2023-05-31 00:20:09,032:INFO:pyemd2:main.py:127:handleKline:2217508: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}


## /root/FIL/strategy/similarity/log.txt ----- -----

127.0.0.1 - - [31/May/2023 00:00:04] "POST / HTTP/1.1" 200 -
2023-05-31 00:00:04,596:INFO:testStrategy:main.py:308:handleOrderFilled:2217133: handleOrderFilled: data=OrderType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'clientorderid': '42291F1685462403831I0L2', 'symbol': 'BTCUSDT', 'gatewayorderid': 1685462404236276, 'quantity': '44.739', 'price': '27665', 'stopprice': '0', 'ordertype': '', 'side': 'BUY', 'status': 'FILLED', 'positionside': 'LONG', 'createtime': 1685462402864, 'updatetime': 1685462404236, 'tradetype': 'usdt', 'selfid': 42291, 'filltrades': [TradeType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'tradeid': 1685462404236, 'clientorderid': '42291F1685462403831I0L2', 'price': '27665', 'quantity': '44.739', 'commission': '1237.704435', 'commissionasset': 'USDT', 'tradetime': 1685462404236, 'tradetype': 'usdt', 'gatetype': 'simulator', 'handletime': 1685462404236}], 'gatetype': 'simulator', 'handletime': 0}

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=2387 

self.closeSec=1685462999, self.tradeDate='20230531', self.openTime='000000', self.closeTime='000959', self.symbol='BTCUSDT', self.open='27665', self.close='27693.9'
127.0.0.1 - - [31/May/2023 00:10:01] "POST / HTTP/1.1" 200 -
2023-05-31 00:10:01,132:INFO:testStrategy:main.py:101:handleKline:2217133: self.closeSec=1685462999, self.tradeDate='20230531', self.openTime='000000', self.closeTime='000959',self.symbol='BTCUSDT',self.open='27665', self.close='27693.9'
2023-05-31 00:10:01,163:INFO:testStrategy:main.py:102:handleKline:2217133: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12236  20230530   232000    232959  1685460599  27703.5  27661.2
12237  20230530   233000    233959  1685461199  27661.2    27700
12238  20230530   234000    234959  1685461799  27699.4  27695.5
12239  20230530   235000    235959  1685462399  27697.8    27665
12240  20230531   000000    000959  1685462999    27665  27693.9
2023-05-31 00:10:01,163:INFO:testStrategy:main.py:103:handleKline:2217133: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False, 'isCorr': False}

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=2388 

self.closeSec=1685463599, self.tradeDate='20230531', self.openTime='001000', self.closeTime='001959', self.symbol='BTCUSDT', self.open='27689.3', self.close='27593.9'
127.0.0.1 - - [31/May/2023 00:20:04] "POST / HTTP/1.1" 200 -
2023-05-31 00:20:08,611:INFO:testStrategy:main.py:101:handleKline:2217133: self.closeSec=1685463599, self.tradeDate='20230531', self.openTime='001000', self.closeTime='001959',self.symbol='BTCUSDT',self.open='27689.3', self.close='27593.9'
2023-05-31 00:20:08,857:INFO:testStrategy:main.py:102:handleKline:2217133: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12237  20230530   233000    233959  1685461199  27661.2    27700
12238  20230530   234000    234959  1685461799  27699.4  27695.5
12239  20230530   235000    235959  1685462399  27697.8    27665
12240  20230531   000000    000959  1685462999    27665  27693.9
12241  20230531   001000    001959  1685463599  27689.3  27593.9
2023-05-31 00:20:08,857:INFO:testStrategy:main.py:103:handleKline:2217133: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False, 'isCorr': False}


## /root/FIL/strategy/sr_min/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=1, self.total=996015.990996, self.flagDict['side']='buy', self.tradeCount=1, self.count=4768
self.closeSec=1685463599, self.tradeDate='20230531', self.openTime='001500', self.closeTime='001959', self.symbol='BTCUSDT', self.open=27617.5, self.close=27593.9, self.high=27636.6, self.low=27530.0, self.vol=6706.534, self.amt=184958869.37968 
127.0.0.1 - - [31/May/2023 00:20:01] "POST / HTTP/1.1" 200 -
2023-05-31 00:20:06,977:INFO:sr_min:main.py:172:handleKline:2219263: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5759  20230530   235500    235959  ...         0.0        0.0       0
5760  20230531   000000    000459  ...         0.0        0.0       0
5761  20230531   000500    000959  ...         0.0        0.0       0
5762  20230531   001000    001459  ...         0.0        0.0       0
5763  20230531   001500    001959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-05-31 00:20:06,998:INFO:sr_min:main.py:175:handleKline:2219263: self.closeSec=1685463599, self.tradeDate='20230531', self.openTime='001500', self.closeTime='001959',self.symbol='BTCUSDT',self.open=27617.5, self.close=27593.9, self.high=27636.6, self.low=27530.0, self.vol=6706.534, self.amt=184958869.37968, ukdf['pct'].iloc[-1]=-0.000851 , ukdf['amount'].iloc[-1]=184958869.37968, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5763, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '37.141', 'enterprice': '26844', 'countrevence': '0', 'unrealprofit': '28019.1704', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '27598.4', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=1
127.0.0.1 - - [31/May/2023 00:25:00] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=1, self.total=996015.990996, self.flagDict['side']='buy', self.tradeCount=1, self.count=4769
self.closeSec=1685463899, self.tradeDate='20230531', self.openTime='002000', self.closeTime='002459', self.symbol='BTCUSDT', self.open=27593.8, self.close=27681.4, self.high=27684.0, self.low=27593.8, self.vol=2396.17, self.amt=66240505.6029 
2023-05-31 00:25:00,826:INFO:sr_min:main.py:172:handleKline:2219263: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5760  20230531   000000    000459  ...         0.0        0.0       0
5761  20230531   000500    000959  ...         0.0        0.0       0
5762  20230531   001000    001459  ...         0.0        0.0       0
5763  20230531   001500    001959  ...         0.0        0.0       0
5764  20230531   002000    002459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-05-31 00:25:00,827:INFO:sr_min:main.py:175:handleKline:2219263: self.closeSec=1685463899, self.tradeDate='20230531', self.openTime='002000', self.closeTime='002459',self.symbol='BTCUSDT',self.open=27593.8, self.close=27681.4, self.high=27684.0, self.low=27593.8, self.vol=2396.17, self.amt=66240505.6029, ukdf['pct'].iloc[-1]=0.003171 , ukdf['amount'].iloc[-1]=66240505.6029, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5764, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '37.141', 'enterprice': '26844', 'countrevence': '0', 'unrealprofit': '31105.04056423387', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '27681.48527407', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=1


## /root/FIL/strategy/s_rsrs/log.txt ----- -----

723  20230530   120000    155959  1685433599  ...    723  1.104430  2.288963     1.0
724  20230530   160000    195959  1685447999  ...    724  1.101142  2.187779     1.0

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '55.249', 'enterprice': '26128.2', 'countrevence': '0', 'unrealprofit': '104199.614', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '28014.2', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=1, self.sign=1
--handleKline--:  version='2.0.0', self.name='s_rsrs', self.symbol='BTCUSDT', interval='4h', intervalSec=14400, wid=25, thd=0.6, self.sign=1, self.total=1442113.3648782002, self.flagDict['side']='buy', self.tradeCount=3, self.count=99
self.closeSec=1685462399, self.tradeDate='20230530', self.openTime='200000', self.closeTime='235959', self.symbol='BTCUSDT', self.open=28005.8, self.close=27665.0, self.high=28014.9, self.low=27602.0, self.vol=102527.366, self.amt=2848858944.86702 127.0.0.1 - - [31/May/2023 00:00:01] "POST / HTTP/1.1" 200 -

2023-05-31 00:00:01,778:INFO:s_rsrs:main.py:141:handleKline:2218689: self.closeSec=1685462399, self.tradeDate='20230530', self.openTime='200000', self.closeTime='235959',self.symbol='BTCUSDT',self.open=28005.8, self.close=27665.0, self.high=28014.9, self.low=27602.0, self.vol=102527.366, self.amt=2848858944.86702 
2023-05-31 00:00:01,829:INFO:s_rsrs:main.py:142:handleKline:2218689: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime  ...         vol           amt       pct
721  20230530   040000    075959  ...   41577.115  1.150710e+09  0.003548
722  20230530   080000    115959  ...   45946.311  1.275505e+09  0.003355
723  20230530   120000    155959  ...   36390.572  1.010080e+09 -0.003376
724  20230530   160000    195959  ...   63354.986  1.767803e+09  0.010274
725  20230530   200000    235959  ...  102527.366  2.848859e+09 -0.012172

[5 rows x 11 columns]
2023-05-31 00:00:04,004:INFO:s_rsrs:main.py:151:handleKline:2218689: df_s.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec  ...  index      beta    zscore  signal
721  20230530   040000    075959  1685404799  ...    721  1.159886  2.726214     1.0
722  20230530   080000    115959  1685419199  ...    722  1.147408  2.547483     1.0
723  20230530   120000    155959  1685433599  ...    723  1.104430  2.288963     1.0
724  20230530   160000    195959  1685447999  ...    724  1.101142  2.187779     1.0
725  20230530   200000    235959  1685462399  ...    725  1.086280  2.058788     1.0

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '55.249', 'enterprice': '26128.2', 'countrevence': '0', 'unrealprofit': '84906.6632', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '27665', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=1, self.sign=1


