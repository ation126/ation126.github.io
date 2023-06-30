# 20230701 00:26:01

## /root/FIL/strategy/amihud/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=373746.4768026, self.flagDict['side']='sell', self.tradeCount=2, self.count=13696
self.closeSec=1688141999, self.tradeDate='20230701', self.openTime='001500', self.closeTime='001959', self.symbol='BTCUSDT', self.open=30006.4, self.close=30039.9, self.high=30060.0, self.low=29992.9, self.vol=2610.738, self.amt=78410118.5167 
127.0.0.1 - - [01/Jul/2023 00:20:01] "POST / HTTP/1.1" 200 -
2023-07-01 00:20:07,204:INFO:amihud:main.py:172:handleKline:2219019: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5759  20230630   235500    235959  ...         0.0        0.0       0
5760  20230701   000000    000459  ...         0.0        0.0       0
5761  20230701   000500    000959  ...         0.0        0.0       0
5762  20230701   001000    001459  ...         0.0        0.0       0
5763  20230701   001500    001959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-07-01 00:20:07,244:INFO:amihud:main.py:175:handleKline:2219019: self.closeSec=1688141999, self.tradeDate='20230701', self.openTime='001500', self.closeTime='001959',self.symbol='BTCUSDT',self.open=30006.4, self.close=30039.9, self.high=30060.0, self.low=29992.9, self.vol=2610.738, self.amt=78410118.5167, ukdf['pct'].iloc[-1]=0.00112 , ukdf['amount'].iloc[-1]=78410118.5167, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5763, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '13.926', 'enterprice': '26864.9', 'countrevence': '0', 'unrealprofit': '-44244.32406309894', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '30042.00211569', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1
--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=373746.4768026, self.flagDict['side']='sell', self.tradeCount=2, self.count=13697
self.closeSec=1688142299, self.tradeDate='20230701', self.openTime='002000', self.closeTime='002459', self.symbol='BTCUSDT', self.open=30040.9, self.close=30094.9, self.high=30100.0, self.low=30036.4, self.vol=1878.166, self.amt=56477108.7186 
127.0.0.1 - - [01/Jul/2023 00:25:00] "POST / HTTP/1.1" 200 -
2023-07-01 00:25:00,768:INFO:amihud:main.py:172:handleKline:2219019: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5760  20230701   000000    000459  ...         0.0        0.0       0
5761  20230701   000500    000959  ...         0.0        0.0       0
5762  20230701   001000    001459  ...         0.0        0.0       0
5763  20230701   001500    001959  ...         0.0        0.0       0
5764  20230701   002000    002459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-07-01 00:25:00,768:INFO:amihud:main.py:175:handleKline:2219019: self.closeSec=1688142299, self.tradeDate='20230701', self.openTime='002000', self.closeTime='002459',self.symbol='BTCUSDT',self.open=30040.9, self.close=30094.9, self.high=30100.0, self.low=30036.4, self.vol=1878.166, self.amt=56477108.7186, ukdf['pct'].iloc[-1]=0.001831 , ukdf['amount'].iloc[-1]=56477108.7186, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5764, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '13.926', 'enterprice': '26864.9', 'countrevence': '0', 'unrealprofit': '-44990.42221681392', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '30095.57802792', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1


## /root/FIL/strategy/factorcheck/log.txt ----- -----


self.closeSec=1688141999, self.tradeDate='20230701', self.openTime='001500', self.closeTime='001959', self.symbol='BTCUSDT', self.open=30006.4, self.close=30039.9, self.high=30060.0, self.low=29992.9 
127.0.0.1 - - [01/Jul/2023 00:20:01] "POST / HTTP/1.1" 200 -
2023-07-01 00:20:04,804:INFO:factorcheck2:main.py:126:handleKline:2218005: self.closeSec=1688141999, self.tradeDate='20230701', self.openTime='001500', self.closeTime='001959',self.symbol='BTCUSDT',self.open=30006.4, self.close=30039.9, self.high=30060.0, self.low=29992.9   
2023-07-01 00:20:06,374:INFO:factorcheck2:main.py:127:handleKline:2218005: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1439  20230630   235500    235959  1688140799  ...  29987.3  0.002271   1727    5
1440  20230701   000000    000459  1688141099  ...  29996.4 -0.001012   1440    0
1441  20230701   000500    000959  1688141399  ...  29911.1 -0.002745   1441    1
1442  20230701   001000    001459  1688141699  ...  29908.3  0.002245   1442    2
1443  20230701   001500    001959  1688141999  ...  29992.9  0.001120   1443    3

[5 rows x 11 columns]
2023-07-01 00:20:06,383:INFO:factorcheck2:main.py:128:handleKline:2218005: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}
127.0.0.1 - - [01/Jul/2023 00:25:00] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=14, self.factor=0.4611554330550819, self.count=13699 

self.closeSec=1688142299, self.tradeDate='20230701', self.openTime='002000', self.closeTime='002459', self.symbol='BTCUSDT', self.open=30040.9, self.close=30094.9, self.high=30100.0, self.low=30036.4 
2023-07-01 00:25:00,708:INFO:factorcheck2:main.py:126:handleKline:2218005: self.closeSec=1688142299, self.tradeDate='20230701', self.openTime='002000', self.closeTime='002459',self.symbol='BTCUSDT',self.open=30040.9, self.close=30094.9, self.high=30100.0, self.low=30036.4   
2023-07-01 00:25:00,748:INFO:factorcheck2:main.py:127:handleKline:2218005: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1440  20230701   000000    000459  1688141099  ...  29996.4 -0.001012   1440    0
1441  20230701   000500    000959  1688141399  ...  29911.1 -0.002745   1441    1
1442  20230701   001000    001459  1688141699  ...  29908.3  0.002245   1442    2
1443  20230701   001500    001959  1688141999  ...  29992.9  0.001120   1443    3
1444  20230701   002000    002459  1688142299  ...  30036.4  0.001831   1444    4

[5 rows x 11 columns]
2023-07-01 00:25:00,748:INFO:factorcheck2:main.py:128:handleKline:2218005: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}


## /root/FIL/strategy/logic/log.txt ----- -----

2023-07-01 00:00:18,640:DEBUG:logic:main.py:463:getModel:2218526: df_s.iloc[-5:,:] :
          date closeTime     open  ...    alpha58   alpha67   alpha72
5802  20230630    212959  31000.1  ...  52.916667  0.584675  0.415741
5803  20230630    215959  31048.7  ...  52.500000  0.444740  0.431729
5804  20230630    222959  30118.1  ...  52.500000  0.451005  0.445043
5805  20230630    225959  30163.5  ...  52.500000  0.441082  0.460611
5806  20230630    232959  30078.6  ...  52.083333  0.440394  0.475359

[5 rows x 33 columns]
0.5569852941176471
acc is : 0.5569852941176471
2023-07-01 00:00:18,739:INFO:logic:main.py:468:getModel:2218526: df_pred.iloc[-5:,:] :
     pred    prob_0    prob_1  actual  ...       nav  sign   cost_        bm
539     0  0.533094  0.466906       0  ...  0.990466   1.0  0.0000  1.140248
540     1  0.335449  0.664551       1  ...  0.987455  -1.0 -0.0016  1.141891
541     1  0.458585  0.541415       0  ...  0.990231  -1.0  0.0000  1.138681
542     1  0.423812  0.576188       0  ...  0.990425  -1.0  0.0000  1.138458
543     1  0.438364  0.561636       0  ...  0.991110  -1.0  0.0000  1.137670

[5 rows x 10 columns]
2023-07-01 00:00:18,766:INFO:logic:main.py:478:getModel:2218526: df_panel.iloc[-5:,:] :
    pred    prob_0    prob_1  actual  ...       nav  sign   cost_        bm
45     0  0.534289  0.465711       0  ...  0.990466   1.0  0.0000  1.139511
46     1  0.336158  0.663842       1  ...  0.987455  -1.0 -0.0016  1.141770
47     1  0.459115  0.540885       0  ...  0.990231  -1.0  0.0000  1.138560
48     1  0.423883  0.576117       0  ...  0.990425  -1.0  0.0000  1.139005
49     1  0.438364  0.561636       0  ...  0.991110  -1.0  0.0000  1.137670

[5 rows x 10 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '26.213', 'enterprice': '30163.4', 'countrevence': '0', 'unrealprofit': '3070.20795606756', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '30046.27460588', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}


## /root/FIL/strategy/modifiedmom/log.txt ----- -----

127.0.0.1 - - [01/Jul/2023 00:00:04] "POST / HTTP/1.1" 200 -
2023-07-01 00:00:04,182:INFO:modifiedmom:main.py:319:handleOrderFilled:2218259: handleOrderFilled: data=OrderType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'clientorderid': '42504F1688140803603I0L59', 'symbol': 'BTCUSDT', 'gatewayorderid': 1688140803972034, 'quantity': '25.977', 'price': '30051.9', 'stopprice': '0', 'ordertype': '', 'side': 'SELL', 'status': 'FILLED', 'positionside': 'SHORT', 'createtime': 1688140802717, 'updatetime': 1688140803972, 'tradetype': 'usdt', 'selfid': 42504, 'filltrades': [TradeType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'tradeid': 1688140803972, 'clientorderid': '42504F1688140803603I0L59', 'price': '30051.9', 'quantity': '25.977', 'commission': '780.6582063', 'commissionasset': 'USDT', 'tradetime': 1688140803972, 'tradetype': 'usdt', 'gatetype': 'simulator', 'handletime': 1688140803972}], 'gatetype': 'simulator', 'handletime': 0}

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=6848 

self.closeSec=1688141399, self.tradeDate='20230701', self.openTime='000000', self.closeTime='000959', self.symbol='BTCUSDT', self.open='30052', self.close='29939.1'
127.0.0.1 - - [01/Jul/2023 00:10:01] "POST / HTTP/1.1" 200 -
2023-07-01 00:10:01,138:INFO:modifiedmom:main.py:144:handleKline:2218259: self.closeSec=1688141399, self.tradeDate='20230701', self.openTime='000000', self.closeTime='000959',self.symbol='BTCUSDT',self.open='30052', self.close='29939.1'
2023-07-01 00:10:01,169:INFO:modifiedmom:main.py:145:handleKline:2218259: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
572  20230630   232000    232959  1688138999  30149.5  30072.7 -0.002547
573  20230630   233000    233959  1688139599  30072.6  30055.3 -0.000579
574  20230630   234000    234959  1688140199  30057.6  30010.8 -0.001481
575  20230630   235000    235959  1688140799  30010.7    30052  0.001373
576  20230701   000000    000959  1688141399    30052  29939.1 -0.003757
2023-07-01 00:10:01,169:INFO:modifiedmom:main.py:146:handleKline:2218259: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=6849 

self.closeSec=1688141999, self.tradeDate='20230701', self.openTime='001000', self.closeTime='001959', self.symbol='BTCUSDT', self.open='29939.1', self.close='30039.9'
127.0.0.1 - - [01/Jul/2023 00:20:04] "POST / HTTP/1.1" 200 -
2023-07-01 00:20:07,044:INFO:modifiedmom:main.py:144:handleKline:2218259: self.closeSec=1688141999, self.tradeDate='20230701', self.openTime='001000', self.closeTime='001959',self.symbol='BTCUSDT',self.open='29939.1', self.close='30039.9'
2023-07-01 00:20:07,863:INFO:modifiedmom:main.py:145:handleKline:2218259: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
573  20230630   233000    233959  1688139599  30072.6  30055.3 -0.000579
574  20230630   234000    234959  1688140199  30057.6  30010.8 -0.001481
575  20230630   235000    235959  1688140799  30010.7    30052  0.001373
576  20230701   000000    000959  1688141399    30052  29939.1 -0.003757
577  20230701   001000    001959  1688141999  29939.1  30039.9  0.003367
2023-07-01 00:20:07,864:INFO:modifiedmom:main.py:146:handleKline:2218259: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False}


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

2023-07-01 00:00:02,168:INFO:pyemd2:main.py:127:handleKline:2217508: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}
2023-07-01 00:00:02,273:INFO:pyemd2:main.py:190:insertFactor:2217508: curDateTime:7010000, name:pyemd2, symbol:BTCUSDT, tradeDate:20230630, closeTime:235959, close:30052, total:992420.1027844, pct_pre:0.007105109785406016, thd:-0.1393533425797156, side:sell 
127.0.0.1 - - [01/Jul/2023 00:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=6851 

self.closeSec=1688141399, self.tradeDate='20230701', self.openTime='000000', self.closeTime='000959', self.symbol='BTCUSDT', self.open='30052', self.close='29939.1'
2023-07-01 00:10:01,141:INFO:pyemd2:main.py:125:handleKline:2217508: self.closeSec=1688141399, self.tradeDate='20230701', self.openTime='000000', self.closeTime='000959',self.symbol='BTCUSDT',self.open='30052', self.close='29939.1'
2023-07-01 00:10:01,157:INFO:pyemd2:main.py:126:handleKline:2217508: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17420  20230630   232000    232959  1688138999  30149.5  30072.7
17421  20230630   233000    233959  1688139599  30072.6  30055.3
17422  20230630   234000    234959  1688140199  30057.6  30010.8
17423  20230630   235000    235959  1688140799  30010.7    30052
17424  20230701   000000    000959  1688141399    30052  29939.1
2023-07-01 00:10:01,157:INFO:pyemd2:main.py:127:handleKline:2217508: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=6852 

self.closeSec=1688141999, self.tradeDate='20230701', self.openTime='001000', self.closeTime='001959', self.symbol='BTCUSDT', self.open='29939.1', self.close='30039.9'
127.0.0.1 - - [01/Jul/2023 00:20:04] "POST / HTTP/1.1" 200 -
2023-07-01 00:20:09,030:INFO:pyemd2:main.py:125:handleKline:2217508: self.closeSec=1688141999, self.tradeDate='20230701', self.openTime='001000', self.closeTime='001959',self.symbol='BTCUSDT',self.open='29939.1', self.close='30039.9'
2023-07-01 00:20:09,151:INFO:pyemd2:main.py:126:handleKline:2217508: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17421  20230630   233000    233959  1688139599  30072.6  30055.3
17422  20230630   234000    234959  1688140199  30057.6  30010.8
17423  20230630   235000    235959  1688140799  30010.7    30052
17424  20230701   000000    000959  1688141399    30052  29939.1
17425  20230701   001000    001959  1688141999  29939.1  30039.9
2023-07-01 00:20:09,152:INFO:pyemd2:main.py:127:handleKline:2217508: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}


## /root/FIL/strategy/similarity/log.txt ----- -----

127.0.0.1 - - [01/Jul/2023 00:00:04] "POST / HTTP/1.1" 200 -
2023-07-01 00:00:04,398:INFO:testStrategy:main.py:308:handleOrderFilled:2217133: handleOrderFilled: data=OrderType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'clientorderid': '42505F1688140803664I0L2', 'symbol': 'BTCUSDT', 'gatewayorderid': 1688140804042297, 'quantity': '38.026', 'price': '30051.9', 'stopprice': '0', 'ordertype': '', 'side': 'SELL', 'status': 'FILLED', 'positionside': 'SHORT', 'createtime': 1688140802726, 'updatetime': 1688140804042, 'tradetype': 'usdt', 'selfid': 42505, 'filltrades': [TradeType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'tradeid': 1688140804042, 'clientorderid': '42505F1688140803664I0L2', 'price': '30051.9', 'quantity': '38.026', 'commission': '1142.7535494', 'commissionasset': 'USDT', 'tradetime': 1688140804042, 'tradetype': 'usdt', 'gatetype': 'simulator', 'handletime': 1688140804042}], 'gatetype': 'simulator', 'handletime': 0}
127.0.0.1 - - [01/Jul/2023 00:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=6851 

self.closeSec=1688141399, self.tradeDate='20230701', self.openTime='000000', self.closeTime='000959', self.symbol='BTCUSDT', self.open='30052', self.close='29939.1'
2023-07-01 00:10:01,160:INFO:testStrategy:main.py:101:handleKline:2217133: self.closeSec=1688141399, self.tradeDate='20230701', self.openTime='000000', self.closeTime='000959',self.symbol='BTCUSDT',self.open='30052', self.close='29939.1'
2023-07-01 00:10:01,183:INFO:testStrategy:main.py:102:handleKline:2217133: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12236  20230630   232000    232959  1688138999  30149.5  30072.7
12237  20230630   233000    233959  1688139599  30072.6  30055.3
12238  20230630   234000    234959  1688140199  30057.6  30010.8
12239  20230630   235000    235959  1688140799  30010.7    30052
12240  20230701   000000    000959  1688141399    30052  29939.1
2023-07-01 00:10:01,183:INFO:testStrategy:main.py:103:handleKline:2217133: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False, 'isCorr': False}

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=6852 

self.closeSec=1688141999, self.tradeDate='20230701', self.openTime='001000', self.closeTime='001959', self.symbol='BTCUSDT', self.open='29939.1', self.close='30039.9'
127.0.0.1 - - [01/Jul/2023 00:20:04] "POST / HTTP/1.1" 200 -
2023-07-01 00:20:08,586:INFO:testStrategy:main.py:101:handleKline:2217133: self.closeSec=1688141999, self.tradeDate='20230701', self.openTime='001000', self.closeTime='001959',self.symbol='BTCUSDT',self.open='29939.1', self.close='30039.9'
2023-07-01 00:20:08,904:INFO:testStrategy:main.py:102:handleKline:2217133: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12237  20230630   233000    233959  1688139599  30072.6  30055.3
12238  20230630   234000    234959  1688140199  30057.6  30010.8
12239  20230630   235000    235959  1688140799  30010.7    30052
12240  20230701   000000    000959  1688141399    30052  29939.1
12241  20230701   001000    001959  1688141999  29939.1  30039.9
2023-07-01 00:20:08,908:INFO:testStrategy:main.py:103:handleKline:2217133: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False, 'isCorr': False}


## /root/FIL/strategy/sr_min/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=1, self.total=996015.990996, self.flagDict['side']='buy', self.tradeCount=1, self.count=13696
self.closeSec=1688141999, self.tradeDate='20230701', self.openTime='001500', self.closeTime='001959', self.symbol='BTCUSDT', self.open=30006.4, self.close=30039.9, self.high=30060.0, self.low=29992.9, self.vol=2610.738, self.amt=78410118.5167 
127.0.0.1 - - [01/Jul/2023 00:20:01] "POST / HTTP/1.1" 200 -
2023-07-01 00:20:07,193:INFO:sr_min:main.py:172:handleKline:2219263: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5759  20230630   235500    235959  ...         0.0        0.0       0
5760  20230701   000000    000459  ...         0.0        0.0       0
5761  20230701   000500    000959  ...         0.0        0.0       0
5762  20230701   001000    001459  ...         0.0        0.0       0
5763  20230701   001500    001959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-07-01 00:20:07,223:INFO:sr_min:main.py:175:handleKline:2219263: self.closeSec=1688141999, self.tradeDate='20230701', self.openTime='001500', self.closeTime='001959',self.symbol='BTCUSDT',self.open=30006.4, self.close=30039.9, self.high=30060.0, self.low=29992.9, self.vol=2610.738, self.amt=78410118.5167, ukdf['pct'].iloc[-1]=0.00112 , ukdf['amount'].iloc[-1]=78410118.5167, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5763, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '37.141', 'enterprice': '26844', 'countrevence': '0', 'unrealprofit': '118776.99657884229', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '30042.00211569', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=1
--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=1, self.total=996015.990996, self.flagDict['side']='buy', self.tradeCount=1, self.count=13697
self.closeSec=1688142299, self.tradeDate='20230701', self.openTime='002000', self.closeTime='002459', self.symbol='BTCUSDT', self.open=30040.9, self.close=30094.9, self.high=30100.0, self.low=30036.4, self.vol=1878.166, self.amt=56477108.7186 
127.0.0.1 - - [01/Jul/2023 00:25:00] "POST / HTTP/1.1" 200 -
2023-07-01 00:25:00,762:INFO:sr_min:main.py:172:handleKline:2219263: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5760  20230701   000000    000459  ...         0.0        0.0       0
5761  20230701   000500    000959  ...         0.0        0.0       0
5762  20230701   001000    001459  ...         0.0        0.0       0
5763  20230701   001500    001959  ...         0.0        0.0       0
5764  20230701   002000    002459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-07-01 00:25:00,763:INFO:sr_min:main.py:175:handleKline:2219263: self.closeSec=1688142299, self.tradeDate='20230701', self.openTime='002000', self.closeTime='002459',self.symbol='BTCUSDT',self.open=30040.9, self.close=30094.9, self.high=30100.0, self.low=30036.4, self.vol=1878.166, self.amt=56477108.7186, ukdf['pct'].iloc[-1]=0.001831 , ukdf['amount'].iloc[-1]=56477108.7186, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5764, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '37.141', 'enterprice': '26844', 'countrevence': '0', 'unrealprofit': '120766.85953497672', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '30095.57802792', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=1


## /root/FIL/strategy/s_rsrs/log.txt ----- -----

723  20230630   120000    155959  1688111999  ...    723  0.725928  0.394365     NaN
724  20230630   160000    195959  1688126399  ...    724  0.635276  0.131462     NaN

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '53.268', 'enterprice': '30707', 'countrevence': '0', 'unrealprofit': '-10650.53913868728', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '30906.94253846', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-9223372036854775808, self.sign=-1
--handleKline--:  version='2.0.0', self.name='s_rsrs', self.symbol='BTCUSDT', interval='4h', intervalSec=14400, wid=25, thd=0.6, self.sign=-1, self.total=1634064.775524, self.flagDict['side']='sell', self.tradeCount=8, self.count=285
self.closeSec=1688140799, self.tradeDate='20230630', self.openTime='200000', self.closeTime='235959', self.symbol='BTCUSDT', self.open=30897.7, self.close=30052.0, self.high=31127.3, self.low=29500.0, self.vol=346709.184, self.amt=10490242464.38944 
2023-07-01 00:00:01,667:INFO:s_rsrs:main.py:141:handleKline:2218689: self.closeSec=1688140799, self.tradeDate='20230630', self.openTime='200000', self.closeTime='235959',self.symbol='BTCUSDT',self.open=30897.7, self.close=30052.0, self.high=31127.3, self.low=29500.0, self.vol=346709.184, self.amt=10490242464.38944 
127.0.0.1 - - [01/Jul/2023 00:00:01] "POST / HTTP/1.1" 200 -
2023-07-01 00:00:01,707:INFO:s_rsrs:main.py:142:handleKline:2218689: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime  ...         vol           amt       pct
721  20230630   040000    075959  ...   43576.159  1.324846e+09 -0.004305
722  20230630   080000    115959  ...   74469.724  2.280098e+09  0.009672
723  20230630   120000    155959  ...  144771.236  4.472121e+09  0.000807
724  20230630   160000    195959  ...   52591.102  1.620298e+09  0.004506
725  20230630   200000    235959  ...  346709.184  1.049024e+10 -0.027371

[5 rows x 11 columns]
2023-07-01 00:00:03,170:INFO:s_rsrs:main.py:151:handleKline:2218689: df_s.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec  ...  index      beta    zscore  signal
721  20230630   040000    075959  1688083199  ...    721  0.334840 -0.679149    -1.0
722  20230630   080000    115959  1688097599  ...    722  0.378413 -0.570406     NaN
723  20230630   120000    155959  1688111999  ...    723  0.725928  0.394365     NaN
724  20230630   160000    195959  1688126399  ...    724  0.635276  0.131462     NaN
725  20230630   200000    235959  1688140799  ...    725  0.035999 -1.527750    -1.0

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '53.268', 'enterprice': '30707', 'countrevence': '0', 'unrealprofit': '34890.54', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '30052', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-1, self.sign=-1


