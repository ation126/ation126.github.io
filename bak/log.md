# 20230705 00:26:01

## /root/FIL/strategy/amihud/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=373746.4768026, self.flagDict['side']='sell', self.tradeCount=2, self.count=14848
self.closeSec=1688487599, self.tradeDate='20230705', self.openTime='001500', self.closeTime='001959', self.symbol='BTCUSDT', self.open=30951.6, self.close=31022.0, self.high=31023.5, self.low=30934.2, self.vol=2613.183, self.amt=81001124.2258 
127.0.0.1 - - [05/Jul/2023 00:20:01] "POST / HTTP/1.1" 200 -
2023-07-05 00:20:06,752:INFO:amihud:main.py:172:handleKline:2219019: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5759  20230704   235500    235959  ...         0.0        0.0       0
5760  20230705   000000    000459  ...         0.0        0.0       0
5761  20230705   000500    000959  ...         0.0        0.0       0
5762  20230705   001000    001459  ...         0.0        0.0       0
5763  20230705   001500    001959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-07-05 00:20:06,793:INFO:amihud:main.py:175:handleKline:2219019: self.closeSec=1688487599, self.tradeDate='20230705', self.openTime='001500', self.closeTime='001959',self.symbol='BTCUSDT',self.open=30951.6, self.close=31022.0, self.high=31023.5, self.low=30934.2, self.vol=2613.183, self.amt=81001124.2258, ukdf['pct'].iloc[-1]=0.002275 , ukdf['amount'].iloc[-1]=81001124.2258, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5763, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '13.926', 'enterprice': '26864.9', 'countrevence': '0', 'unrealprofit': '-57817.90015420254', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '31016.69521429', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1
127.0.0.1 - - [05/Jul/2023 00:25:00] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=373746.4768026, self.flagDict['side']='sell', self.tradeCount=2, self.count=14849
self.closeSec=1688487899, self.tradeDate='20230705', self.openTime='002000', self.closeTime='002459', self.symbol='BTCUSDT', self.open=31019.9, self.close=31044.0, self.high=31055.0, self.low=31016.2, self.vol=1681.593, self.amt=52192100.0358 
2023-07-05 00:25:00,797:INFO:amihud:main.py:172:handleKline:2219019: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5760  20230705   000000    000459  ...         0.0        0.0       0
5761  20230705   000500    000959  ...         0.0        0.0       0
5762  20230705   001000    001459  ...         0.0        0.0       0
5763  20230705   001500    001959  ...         0.0        0.0       0
5764  20230705   002000    002459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-07-05 00:25:00,797:INFO:amihud:main.py:175:handleKline:2219019: self.closeSec=1688487899, self.tradeDate='20230705', self.openTime='002000', self.closeTime='002459',self.symbol='BTCUSDT',self.open=31019.9, self.close=31044.0, self.high=31055.0, self.low=31016.2, self.vol=1681.593, self.amt=52192100.0358, ukdf['pct'].iloc[-1]=0.000709 , ukdf['amount'].iloc[-1]=52192100.0358, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5764, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '13.926', 'enterprice': '26864.9', 'countrevence': '0', 'unrealprofit': '-58220.01136376502', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '31045.57006777', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1


## /root/FIL/strategy/factorcheck/log.txt ----- -----


self.closeSec=1688487599, self.tradeDate='20230705', self.openTime='001500', self.closeTime='001959', self.symbol='BTCUSDT', self.open=30951.6, self.close=31022.0, self.high=31023.5, self.low=30934.2 
127.0.0.1 - - [05/Jul/2023 00:20:01] "POST / HTTP/1.1" 200 -
2023-07-05 00:20:04,642:INFO:factorcheck2:main.py:126:handleKline:2218005: self.closeSec=1688487599, self.tradeDate='20230705', self.openTime='001500', self.closeTime='001959',self.symbol='BTCUSDT',self.open=30951.6, self.close=31022.0, self.high=31023.5, self.low=30934.2   
2023-07-05 00:20:06,011:INFO:factorcheck2:main.py:127:handleKline:2218005: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1439  20230704   235500    235959  1688486399  ...  30931.7  0.000333   1727    5
1440  20230705   000000    000459  1688486699  ...  30950.7 -0.000094   1440    0
1441  20230705   000500    000959  1688486999  ...  30931.8 -0.000003   1441    1
1442  20230705   001000    001459  1688487299  ...  30941.2 -0.000155   1442    2
1443  20230705   001500    001959  1688487599  ...  30934.2  0.002275   1443    3

[5 rows x 11 columns]
2023-07-05 00:20:06,021:INFO:factorcheck2:main.py:128:handleKline:2218005: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}
127.0.0.1 - - [05/Jul/2023 00:25:00] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=206, self.factor=0.4454718459856118, self.count=14851 

self.closeSec=1688487899, self.tradeDate='20230705', self.openTime='002000', self.closeTime='002459', self.symbol='BTCUSDT', self.open=31019.9, self.close=31044.0, self.high=31055.0, self.low=31016.2 
2023-07-05 00:25:00,743:INFO:factorcheck2:main.py:126:handleKline:2218005: self.closeSec=1688487899, self.tradeDate='20230705', self.openTime='002000', self.closeTime='002459',self.symbol='BTCUSDT',self.open=31019.9, self.close=31044.0, self.high=31055.0, self.low=31016.2   
2023-07-05 00:25:00,783:INFO:factorcheck2:main.py:127:handleKline:2218005: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1440  20230705   000000    000459  1688486699  ...  30950.7 -0.000094   1440    0
1441  20230705   000500    000959  1688486999  ...  30931.8 -0.000003   1441    1
1442  20230705   001000    001459  1688487299  ...  30941.2 -0.000155   1442    2
1443  20230705   001500    001959  1688487599  ...  30934.2  0.002275   1443    3
1444  20230705   002000    002459  1688487899  ...  31016.2  0.000709   1444    4

[5 rows x 11 columns]
2023-07-05 00:25:00,783:INFO:factorcheck2:main.py:128:handleKline:2218005: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}


## /root/FIL/strategy/logic/log.txt ----- -----

2023-07-05 00:00:19,585:DEBUG:logic:main.py:463:getModel:2218526: df_s.iloc[-5:,:] :
          date closeTime     open  ...    alpha58   alpha67   alpha72
5802  20230704    212959  31031.9  ...  51.666667  0.536090  0.480650
5803  20230704    215959  31027.3  ...  51.666667  0.526515  0.498829
5804  20230704    222959  30989.0  ...  51.666667  0.530048  0.513843
5805  20230704    225959  31004.8  ...  51.666667  0.519630  0.532999
5806  20230704    232959  30963.1  ...  51.250000  0.509148  0.556158

[5 rows x 33 columns]
0.5202205882352942
acc is : 0.5202205882352942
2023-07-05 00:00:19,664:INFO:logic:main.py:468:getModel:2218526: df_pred.iloc[-5:,:] :
     pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
539     0  0.524325  0.475675       0  ...  0.950033   1.0    0.0  1.035486
540     0  0.515246  0.484754       1  ...  0.950518   1.0    0.0  1.036014
541     0  0.522691  0.477309       0  ...  0.949242   1.0    0.0  1.034624
542     0  0.514196  0.485804       0  ...  0.947933   1.0    0.0  1.033197
543     0  0.510379  0.489621       1  ...  0.949126   1.0    0.0  1.034497

[5 rows x 10 columns]
2023-07-05 00:00:19,675:INFO:logic:main.py:478:getModel:2218526: df_panel.iloc[-5:,:] :
    pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
45     0  0.523415  0.476585       0  ...  0.950033   1.0    0.0  1.031742
46     0  0.514927  0.485073       1  ...  0.950518   1.0    0.0  1.033276
47     0  0.522392  0.477608       0  ...  0.949242   1.0    0.0  1.031890
48     0  0.513754  0.486246       0  ...  0.947933   1.0    0.0  1.031381
49     0  0.510379  0.489621       1  ...  0.949126   1.0    0.0  1.034497

[5 rows x 10 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '25.53', 'enterprice': '30560', 'countrevence': '0', 'unrealprofit': '10015.419', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '30952.3', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}


## /root/FIL/strategy/modifiedmom/log.txt ----- -----

127.0.0.1 - - [05/Jul/2023 00:00:04] "POST / HTTP/1.1" 200 -
2023-07-05 00:00:04,892:INFO:modifiedmom:main.py:319:handleOrderFilled:2218259: handleOrderFilled: data=OrderType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'clientorderid': '42526F1688486403903I0L59', 'symbol': 'BTCUSDT', 'gatewayorderid': 1688486404277347, 'quantity': '24.98', 'price': '30959.4', 'stopprice': '0', 'ordertype': '', 'side': 'BUY', 'status': 'FILLED', 'positionside': 'LONG', 'createtime': 1688486402918, 'updatetime': 1688486404277, 'tradetype': 'usdt', 'selfid': 42526, 'filltrades': [TradeType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'tradeid': 1688486404277, 'clientorderid': '42526F1688486403903I0L59', 'price': '30959.4', 'quantity': '24.98', 'commission': '773.365812', 'commissionasset': 'USDT', 'tradetime': 1688486404277, 'tradetype': 'usdt', 'gatetype': 'simulator', 'handletime': 1688486404277}], 'gatetype': 'simulator', 'handletime': 0}

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=7424 

self.closeSec=1688486999, self.tradeDate='20230705', self.openTime='000000', self.closeTime='000959', self.symbol='BTCUSDT', self.open='30959.3', self.close='30956.3'
127.0.0.1 - - [05/Jul/2023 00:10:01] "POST / HTTP/1.1" 200 -
2023-07-05 00:10:01,158:INFO:modifiedmom:main.py:144:handleKline:2218259: self.closeSec=1688486999, self.tradeDate='20230705', self.openTime='000000', self.closeTime='000959',self.symbol='BTCUSDT',self.open='30959.3', self.close='30956.3'
2023-07-05 00:10:01,177:INFO:modifiedmom:main.py:145:handleKline:2218259: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
572  20230704   232000    232959  1688484599  31000.7  30920.5 -0.002587
573  20230704   233000    233959  1688485199  30920.5  30910.2 -0.000333
574  20230704   234000    234959  1688485799  30910.4  30938.3  0.000909
575  20230704   235000    235959  1688486399  30938.2  30959.3  0.000679
576  20230705   000000    000959  1688486999  30959.3  30956.3 -0.000097
2023-07-05 00:10:01,178:INFO:modifiedmom:main.py:146:handleKline:2218259: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=7425 

self.closeSec=1688487599, self.tradeDate='20230705', self.openTime='001000', self.closeTime='001959', self.symbol='BTCUSDT', self.open='30956.2', self.close='31022'
127.0.0.1 - - [05/Jul/2023 00:20:04] "POST / HTTP/1.1" 200 -
2023-07-05 00:20:06,671:INFO:modifiedmom:main.py:144:handleKline:2218259: self.closeSec=1688487599, self.tradeDate='20230705', self.openTime='001000', self.closeTime='001959',self.symbol='BTCUSDT',self.open='30956.2', self.close='31022'
2023-07-05 00:20:07,263:INFO:modifiedmom:main.py:145:handleKline:2218259: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
573  20230704   233000    233959  1688485199  30920.5  30910.2 -0.000333
574  20230704   234000    234959  1688485799  30910.4  30938.3  0.000909
575  20230704   235000    235959  1688486399  30938.2  30959.3  0.000679
576  20230705   000000    000959  1688486999  30959.3  30956.3 -0.000097
577  20230705   001000    001959  1688487599  30956.2    31022  0.002122
2023-07-05 00:20:07,271:INFO:modifiedmom:main.py:146:handleKline:2218259: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False}


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

2023-07-05 00:00:04,705:INFO:pyemd2:main.py:303:handleOrderFilled:2217508: handleOrderFilled: data=OrderType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'clientorderid': '42527F1688486403940I0L57', 'symbol': 'BTCUSDT', 'gatewayorderid': 1688486404311086, 'quantity': '32.082', 'price': '30959.3', 'stopprice': '0', 'ordertype': '', 'side': 'SELL', 'status': 'FILLED', 'positionside': 'SHORT', 'createtime': 1688486402882, 'updatetime': 1688486404311, 'tradetype': 'usdt', 'selfid': 42527, 'filltrades': [TradeType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'tradeid': 1688486404311, 'clientorderid': '42527F1688486403940I0L57', 'price': '30959.3', 'quantity': '32.082', 'commission': '993.2362626', 'commissionasset': 'USDT', 'tradetime': 1688486404311, 'tradetype': 'usdt', 'gatetype': 'simulator', 'handletime': 1688486404311}], 'gatetype': 'simulator', 'handletime': 0}
127.0.0.1 - - [05/Jul/2023 00:00:04] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=7427 

self.closeSec=1688486999, self.tradeDate='20230705', self.openTime='000000', self.closeTime='000959', self.symbol='BTCUSDT', self.open='30959.3', self.close='30956.3'
2023-07-05 00:10:01,173:INFO:pyemd2:main.py:125:handleKline:2217508: self.closeSec=1688486999, self.tradeDate='20230705', self.openTime='000000', self.closeTime='000959',self.symbol='BTCUSDT',self.open='30959.3', self.close='30956.3'
127.0.0.1 - - [05/Jul/2023 00:10:01] "POST / HTTP/1.1" 200 -
2023-07-05 00:10:01,182:INFO:pyemd2:main.py:126:handleKline:2217508: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17420  20230704   232000    232959  1688484599  31000.7  30920.5
17421  20230704   233000    233959  1688485199  30920.5  30910.2
17422  20230704   234000    234959  1688485799  30910.4  30938.3
17423  20230704   235000    235959  1688486399  30938.2  30959.3
17424  20230705   000000    000959  1688486999  30959.3  30956.3
2023-07-05 00:10:01,182:INFO:pyemd2:main.py:127:handleKline:2217508: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=7428 

self.closeSec=1688487599, self.tradeDate='20230705', self.openTime='001000', self.closeTime='001959', self.symbol='BTCUSDT', self.open='30956.2', self.close='31022'
127.0.0.1 - - [05/Jul/2023 00:20:04] "POST / HTTP/1.1" 200 -
2023-07-05 00:20:08,346:INFO:pyemd2:main.py:125:handleKline:2217508: self.closeSec=1688487599, self.tradeDate='20230705', self.openTime='001000', self.closeTime='001959',self.symbol='BTCUSDT',self.open='30956.2', self.close='31022'
2023-07-05 00:20:08,459:INFO:pyemd2:main.py:126:handleKline:2217508: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17421  20230704   233000    233959  1688485199  30920.5  30910.2
17422  20230704   234000    234959  1688485799  30910.4  30938.3
17423  20230704   235000    235959  1688486399  30938.2  30959.3
17424  20230705   000000    000959  1688486999  30959.3  30956.3
17425  20230705   001000    001959  1688487599  30956.2    31022
2023-07-05 00:20:08,460:INFO:pyemd2:main.py:127:handleKline:2217508: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}


## /root/FIL/strategy/similarity/log.txt ----- -----

127.0.0.1 - - [05/Jul/2023 00:00:04] "POST / HTTP/1.1" 200 -
2023-07-05 00:00:04,513:INFO:testStrategy:main.py:308:handleOrderFilled:2217133: handleOrderFilled: data=OrderType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'clientorderid': '42525F1688486403882I0L2', 'symbol': 'BTCUSDT', 'gatewayorderid': 1688486404256509, 'quantity': '36.291', 'price': '30959.4', 'stopprice': '0', 'ordertype': '', 'side': 'BUY', 'status': 'FILLED', 'positionside': 'LONG', 'createtime': 1688486402955, 'updatetime': 1688486404256, 'tradetype': 'usdt', 'selfid': 42525, 'filltrades': [TradeType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'tradeid': 1688486404256, 'clientorderid': '42525F1688486403882I0L2', 'price': '30959.4', 'quantity': '36.291', 'commission': '1123.5475854', 'commissionasset': 'USDT', 'tradetime': 1688486404256, 'tradetype': 'usdt', 'gatetype': 'simulator', 'handletime': 1688486404256}], 'gatetype': 'simulator', 'handletime': 0}
127.0.0.1 - - [05/Jul/2023 00:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=7427 

self.closeSec=1688486999, self.tradeDate='20230705', self.openTime='000000', self.closeTime='000959', self.symbol='BTCUSDT', self.open='30959.3', self.close='30956.3'
2023-07-05 00:10:01,167:INFO:testStrategy:main.py:101:handleKline:2217133: self.closeSec=1688486999, self.tradeDate='20230705', self.openTime='000000', self.closeTime='000959',self.symbol='BTCUSDT',self.open='30959.3', self.close='30956.3'
2023-07-05 00:10:01,188:INFO:testStrategy:main.py:102:handleKline:2217133: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12236  20230704   232000    232959  1688484599  31000.7  30920.5
12237  20230704   233000    233959  1688485199  30920.5  30910.2
12238  20230704   234000    234959  1688485799  30910.4  30938.3
12239  20230704   235000    235959  1688486399  30938.2  30959.3
12240  20230705   000000    000959  1688486999  30959.3  30956.3
2023-07-05 00:10:01,188:INFO:testStrategy:main.py:103:handleKline:2217133: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False, 'isCorr': False}

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=7428 

self.closeSec=1688487599, self.tradeDate='20230705', self.openTime='001000', self.closeTime='001959', self.symbol='BTCUSDT', self.open='30956.2', self.close='31022'
127.0.0.1 - - [05/Jul/2023 00:20:04] "POST / HTTP/1.1" 200 -
2023-07-05 00:20:07,992:INFO:testStrategy:main.py:101:handleKline:2217133: self.closeSec=1688487599, self.tradeDate='20230705', self.openTime='001000', self.closeTime='001959',self.symbol='BTCUSDT',self.open='30956.2', self.close='31022'
2023-07-05 00:20:08,287:INFO:testStrategy:main.py:102:handleKline:2217133: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12237  20230704   233000    233959  1688485199  30920.5  30910.2
12238  20230704   234000    234959  1688485799  30910.4  30938.3
12239  20230704   235000    235959  1688486399  30938.2  30959.3
12240  20230705   000000    000959  1688486999  30959.3  30956.3
12241  20230705   001000    001959  1688487599  30956.2    31022
2023-07-05 00:20:08,287:INFO:testStrategy:main.py:103:handleKline:2217133: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False, 'isCorr': False}


## /root/FIL/strategy/sr_min/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=1, self.total=996015.990996, self.flagDict['side']='buy', self.tradeCount=1, self.count=14848
self.closeSec=1688487599, self.tradeDate='20230705', self.openTime='001500', self.closeTime='001959', self.symbol='BTCUSDT', self.open=30951.6, self.close=31022.0, self.high=31023.5, self.low=30934.2, self.vol=2613.183, self.amt=81001124.2258 
127.0.0.1 - - [05/Jul/2023 00:20:01] "POST / HTTP/1.1" 200 -
2023-07-05 00:20:06,751:INFO:sr_min:main.py:172:handleKline:2219263: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5759  20230704   235500    235959  ...         0.0        0.0       0
5760  20230705   000000    000459  ...         0.0        0.0       0
5761  20230705   000500    000959  ...         0.0        0.0       0
5762  20230705   001000    001459  ...         0.0        0.0       0
5763  20230705   001500    001959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-07-05 00:20:06,792:INFO:sr_min:main.py:175:handleKline:2219263: self.closeSec=1688487599, self.tradeDate='20230705', self.openTime='001500', self.closeTime='001959',self.symbol='BTCUSDT',self.open=30951.6, self.close=31022.0, self.high=31023.5, self.low=30934.2, self.vol=2613.183, self.amt=81001124.2258, ukdf['pct'].iloc[-1]=0.002275 , ukdf['amount'].iloc[-1]=81001124.2258, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5763, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '37.141', 'enterprice': '26844', 'countrevence': '0', 'unrealprofit': '154978.07295394489', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '31016.69521429', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=1
--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=1, self.total=996015.990996, self.flagDict['side']='buy', self.tradeCount=1, self.count=14849
self.closeSec=1688487899, self.tradeDate='20230705', self.openTime='002000', self.closeTime='002459', self.symbol='BTCUSDT', self.open=31019.9, self.close=31044.0, self.high=31055.0, self.low=31016.2, self.vol=1681.593, self.amt=52192100.0358 
127.0.0.1 - - [05/Jul/2023 00:25:00] "POST / HTTP/1.1" 200 -
2023-07-05 00:25:00,803:INFO:sr_min:main.py:172:handleKline:2219263: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5760  20230705   000000    000459  ...         0.0        0.0       0
5761  20230705   000500    000959  ...         0.0        0.0       0
5762  20230705   001000    001459  ...         0.0        0.0       0
5763  20230705   001500    001959  ...         0.0        0.0       0
5764  20230705   002000    002459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-07-05 00:25:00,803:INFO:sr_min:main.py:175:handleKline:2219263: self.closeSec=1688487899, self.tradeDate='20230705', self.openTime='002000', self.closeTime='002459',self.symbol='BTCUSDT',self.open=31019.9, self.close=31044.0, self.high=31055.0, self.low=31016.2, self.vol=1681.593, self.amt=52192100.0358, ukdf['pct'].iloc[-1]=0.000709 , ukdf['amount'].iloc[-1]=52192100.0358, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5764, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '37.141', 'enterprice': '26844', 'countrevence': '0', 'unrealprofit': '156050.51388704557', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '31045.57006777', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=1


## /root/FIL/strategy/s_rsrs/log.txt ----- -----

723  20230704   120000    155959  1688457599  ...    723  0.022771 -0.989740    -1.0
724  20230704   160000    195959  1688471999  ...    724  0.024925 -0.965120    -1.0

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '53.268', 'enterprice': '30707', 'countrevence': '0', 'unrealprofit': '-18650.44415865636', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '31057.12473077', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-1, self.sign=-1
--handleKline--:  version='2.0.0', self.name='s_rsrs', self.symbol='BTCUSDT', interval='4h', intervalSec=14400, wid=25, thd=0.6, self.sign=-1, self.total=1634064.775524, self.flagDict['side']='sell', self.tradeCount=8, self.count=309
self.closeSec=1688486399, self.tradeDate='20230704', self.openTime='200000', self.closeTime='235959', self.symbol='BTCUSDT', self.open=31056.4, self.close=30959.4, self.high=31080.0, self.low=30869.1, self.vol=38716.412, self.amt=1199547142.1415 
127.0.0.1 - - [05/Jul/2023 00:00:01] "POST / HTTP/1.1" 200 -
2023-07-05 00:00:01,890:INFO:s_rsrs:main.py:141:handleKline:2218689: self.closeSec=1688486399, self.tradeDate='20230704', self.openTime='200000', self.closeTime='235959',self.symbol='BTCUSDT',self.open=31056.4, self.close=30959.4, self.high=31080.0, self.low=30869.1, self.vol=38716.412, self.amt=1199547142.1415 
2023-07-05 00:00:01,943:INFO:s_rsrs:main.py:142:handleKline:2218689: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime  ...        vol           amt       pct
721  20230704   040000    075959  ...  56721.250  1.764470e+09 -0.003363
722  20230704   080000    115959  ...  43191.597  1.347972e+09  0.001310
723  20230704   120000    155959  ...  53472.779  1.658424e+09 -0.009218
724  20230704   160000    195959  ...  45148.630  1.398908e+09  0.004990
725  20230704   200000    235959  ...  38716.412  1.199547e+09 -0.003127

[5 rows x 11 columns]
2023-07-05 00:00:03,442:INFO:s_rsrs:main.py:151:handleKline:2218689: df_s.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec  ...  index      beta    zscore  signal
721  20230704   040000    075959  1688428799  ...    721  0.003309 -1.078267    -1.0
722  20230704   080000    115959  1688443199  ...    722  0.013331 -1.032518    -1.0
723  20230704   120000    155959  1688457599  ...    723  0.022771 -0.989740    -1.0
724  20230704   160000    195959  1688471999  ...    724  0.024925 -0.965120    -1.0
725  20230704   200000    235959  1688486399  ...    725  0.029170 -0.937501    -1.0

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '53.268', 'enterprice': '30707', 'countrevence': '0', 'unrealprofit': '-13439.5164', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '30959.3', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-1, self.sign=-1


