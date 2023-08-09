# 20230810 00:26:01

## /root/FIL/strategy/amihud/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=373746.4768026, self.flagDict['side']='sell', self.tradeCount=2, self.count=25216
self.closeSec=1691597999, self.tradeDate='20230810', self.openTime='001500', self.closeTime='001959', self.symbol='BTCUSDT', self.open=29745.9, self.close=29735.0, self.high=29759.9, self.low=29731.6, self.vol=797.797, self.amt=23731691.4526 
127.0.0.1 - - [10/Aug/2023 00:20:01] "POST / HTTP/1.1" 200 -
2023-08-10 00:20:06,353:INFO:amihud:main.py:172:handleKline:2219019: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5759  20230809   235500    235959  ...         0.0        0.0       0
5760  20230810   000000    000459  ...         0.0        0.0       0
5761  20230810   000500    000959  ...         0.0        0.0       0
5762  20230810   001000    001459  ...         0.0        0.0       0
5763  20230810   001500    001959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-08-10 00:20:06,383:INFO:amihud:main.py:175:handleKline:2219019: self.closeSec=1691597999, self.tradeDate='20230810', self.openTime='001500', self.closeTime='001959',self.symbol='BTCUSDT',self.open=29745.9, self.close=29735.0, self.high=29759.9, self.low=29731.6, self.vol=797.797, self.amt=23731691.4526, ukdf['pct'].iloc[-1]=-0.000319 , ukdf['amount'].iloc[-1]=23731691.4526, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5763, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '13.926', 'enterprice': '26864.9', 'countrevence': '0', 'unrealprofit': '-39961.55086551606', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '29734.46418681', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1
--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=373746.4768026, self.flagDict['side']='sell', self.tradeCount=2, self.count=25217
self.closeSec=1691598299, self.tradeDate='20230810', self.openTime='002000', self.closeTime='002459', self.symbol='BTCUSDT', self.open=29735.0, self.close=29725.8, self.high=29735.1, self.low=29709.8, self.vol=549.453, self.amt=16329370.3893 
127.0.0.1 - - [10/Aug/2023 00:25:00] "POST / HTTP/1.1" 200 -
2023-08-10 00:25:00,766:INFO:amihud:main.py:172:handleKline:2219019: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5760  20230810   000000    000459  ...         0.0        0.0       0
5761  20230810   000500    000959  ...         0.0        0.0       0
5762  20230810   001000    001459  ...         0.0        0.0       0
5763  20230810   001500    001959  ...         0.0        0.0       0
5764  20230810   002000    002459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-08-10 00:25:00,766:INFO:amihud:main.py:175:handleKline:2219019: self.closeSec=1691598299, self.tradeDate='20230810', self.openTime='002000', self.closeTime='002459',self.symbol='BTCUSDT',self.open=29735.0, self.close=29725.8, self.high=29735.1, self.low=29709.8, self.vol=549.453, self.amt=16329370.3893, ukdf['pct'].iloc[-1]=-0.000309 , ukdf['amount'].iloc[-1]=16329370.3893, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5764, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '13.926', 'enterprice': '26864.9', 'countrevence': '0', 'unrealprofit': '-39840.8934', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '29725.8', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1


## /root/FIL/strategy/factorcheck/log.txt ----- -----


self.closeSec=1691597999, self.tradeDate='20230810', self.openTime='001500', self.closeTime='001959', self.symbol='BTCUSDT', self.open=29745.9, self.close=29735.0, self.high=29759.9, self.low=29731.6 
127.0.0.1 - - [10/Aug/2023 00:20:01] "POST / HTTP/1.1" 200 -
2023-08-10 00:20:04,273:INFO:factorcheck2:main.py:126:handleKline:2218005: self.closeSec=1691597999, self.tradeDate='20230810', self.openTime='001500', self.closeTime='001959',self.symbol='BTCUSDT',self.open=29745.9, self.close=29735.0, self.high=29759.9, self.low=29731.6   
2023-08-10 00:20:05,402:INFO:factorcheck2:main.py:127:handleKline:2218005: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1439  20230809   235500    235959  1691596799  ...  29741.6 -0.000380   1727    5
1440  20230810   000000    000459  1691597099  ...  29744.9  0.000343   1440    0
1441  20230810   000500    000959  1691597399  ...  29706.3 -0.001351   1441    1
1442  20230810   001000    001459  1691597699  ...  29719.4  0.000845   1442    2
1443  20230810   001500    001959  1691597999  ...  29731.6 -0.000319   1443    3

[5 rows x 11 columns]
2023-08-10 00:20:05,403:INFO:factorcheck2:main.py:128:handleKline:2218005: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=251, self.factor=0.387167470161936, self.count=25219 

self.closeSec=1691598299, self.tradeDate='20230810', self.openTime='002000', self.closeTime='002459', self.symbol='BTCUSDT', self.open=29735.0, self.close=29725.8, self.high=29735.1, self.low=29709.8 
127.0.0.1 - - [10/Aug/2023 00:25:00] "POST / HTTP/1.1" 200 -
2023-08-10 00:25:00,735:INFO:factorcheck2:main.py:126:handleKline:2218005: self.closeSec=1691598299, self.tradeDate='20230810', self.openTime='002000', self.closeTime='002459',self.symbol='BTCUSDT',self.open=29735.0, self.close=29725.8, self.high=29735.1, self.low=29709.8   
2023-08-10 00:25:00,753:INFO:factorcheck2:main.py:127:handleKline:2218005: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1440  20230810   000000    000459  1691597099  ...  29744.9  0.000343   1440    0
1441  20230810   000500    000959  1691597399  ...  29706.3 -0.001351   1441    1
1442  20230810   001000    001459  1691597699  ...  29719.4  0.000845   1442    2
1443  20230810   001500    001959  1691597999  ...  29731.6 -0.000319   1443    3
1444  20230810   002000    002459  1691598299  ...  29709.8 -0.000309   1444    4

[5 rows x 11 columns]
2023-08-10 00:25:00,753:INFO:factorcheck2:main.py:128:handleKline:2218005: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}


## /root/FIL/strategy/logic/log.txt ----- -----

2023-08-10 00:00:18,305:DEBUG:logic:main.py:463:getModel:2218526: df_s.iloc[-5:,:] :
          date closeTime     open  ...    alpha58   alpha67   alpha72
5802  20230809    212959  30064.6  ...  51.250000  0.592074  0.455847
5803  20230809    215959  29952.3  ...  50.833333  0.570249  0.466443
5804  20230809    222959  29867.6  ...  50.833333  0.570497  0.476193
5805  20230809    225959  29869.0  ...  50.416667  0.540103  0.498627
5806  20230809    232959  29744.9  ...  50.000000  0.538573  0.520262

[5 rows x 33 columns]
0.5330882352941176
acc is : 0.5330882352941176
2023-08-10 00:00:18,368:INFO:logic:main.py:468:getModel:2218526: df_pred.iloc[-5:,:] :
     pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
539     0  0.503229  0.496771       0  ...  0.974158   1.0    0.0  1.019964
540     0  0.503492  0.496508       1  ...  0.974200   1.0    0.0  1.020008
541     0  0.520883  0.479117       0  ...  0.970143   1.0    0.0  1.015760
542     1  0.478689  0.521311       0  ...  0.969931   1.0    0.0  1.015538
543     1  0.496969  0.503031       1  ...  0.970302   1.0    0.0  1.015927

[5 rows x 10 columns]
2023-08-10 00:00:18,379:INFO:logic:main.py:478:getModel:2218526: df_panel.iloc[-5:,:] :
    pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
45     0  0.503575  0.496425       0  ...  0.974158   1.0    0.0  1.018024
46     0  0.503511  0.496489       1  ...  0.974200   1.0    0.0  1.018145
47     0  0.520752  0.479248       0  ...  0.970143   1.0    0.0  1.013904
48     1  0.478461  0.521539       0  ...  0.969931   1.0    0.0  1.014346
49     1  0.496969  0.503031       1  ...  0.970302   1.0    0.0  1.015927

[5 rows x 10 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '24.06', 'enterprice': '29131.5', 'countrevence': '0', 'unrealprofit': '14791.307944725', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '29746.26757875', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}


## /root/FIL/strategy/modifiedmom/log.txt ----- -----

127.0.0.1 - - [10/Aug/2023 00:00:04] "POST / HTTP/1.1" 200 -
2023-08-10 00:00:04,335:INFO:modifiedmom:main.py:319:handleOrderFilled:2218259: handleOrderFilled: data=OrderType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'clientorderid': '42834F1691596803673I0L59', 'symbol': 'BTCUSDT', 'gatewayorderid': 1691596804066635, 'quantity': '24.425', 'price': '29749.3', 'stopprice': '0', 'ordertype': '', 'side': 'SELL', 'status': 'FILLED', 'positionside': 'SHORT', 'createtime': 1691596802742, 'updatetime': 1691596804066, 'tradetype': 'usdt', 'selfid': 42834, 'filltrades': [TradeType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'tradeid': 1691596804066, 'clientorderid': '42834F1691596803673I0L59', 'price': '29749.3', 'quantity': '24.425', 'commission': '726.6266525', 'commissionasset': 'USDT', 'tradetime': 1691596804066, 'tradetype': 'usdt', 'gatetype': 'simulator', 'handletime': 1691596804066}], 'gatetype': 'simulator', 'handletime': 0}

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=12608 

self.closeSec=1691597399, self.tradeDate='20230810', self.openTime='000000', self.closeTime='000959', self.symbol='BTCUSDT', self.open='29749.3', self.close='29719.4'
127.0.0.1 - - [10/Aug/2023 00:10:01] "POST / HTTP/1.1" 200 -
2023-08-10 00:10:01,130:INFO:modifiedmom:main.py:144:handleKline:2218259: self.closeSec=1691597399, self.tradeDate='20230810', self.openTime='000000', self.closeTime='000959',self.symbol='BTCUSDT',self.open='29749.3', self.close='29719.4'
2023-08-10 00:10:01,158:INFO:modifiedmom:main.py:145:handleKline:2218259: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
572  20230809   232000    232959  1691594999  29748.8  29738.1 -0.000363
573  20230809   233000    233959  1691595599  29738.1  29760.7  0.000760
574  20230809   234000    234959  1691596199  29762.6  29756.6 -0.000138
575  20230809   235000    235959  1691596799  29756.5  29749.4 -0.000242
576  20230810   000000    000959  1691597399  29749.3  29719.4 -0.001008
2023-08-10 00:10:01,158:INFO:modifiedmom:main.py:146:handleKline:2218259: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=12609 

self.closeSec=1691597999, self.tradeDate='20230810', self.openTime='001000', self.closeTime='001959', self.symbol='BTCUSDT', self.open='29719.4', self.close='29735'
127.0.0.1 - - [10/Aug/2023 00:20:04] "POST / HTTP/1.1" 200 -
2023-08-10 00:20:06,823:INFO:modifiedmom:main.py:144:handleKline:2218259: self.closeSec=1691597999, self.tradeDate='20230810', self.openTime='001000', self.closeTime='001959',self.symbol='BTCUSDT',self.open='29719.4', self.close='29735'
2023-08-10 00:20:07,393:INFO:modifiedmom:main.py:145:handleKline:2218259: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
573  20230809   233000    233959  1691595599  29738.1  29760.7  0.000760
574  20230809   234000    234959  1691596199  29762.6  29756.6 -0.000138
575  20230809   235000    235959  1691596799  29756.5  29749.4 -0.000242
576  20230810   000000    000959  1691597399  29749.3  29719.4 -0.001008
577  20230810   001000    001959  1691597999  29719.4    29735  0.000525
2023-08-10 00:20:07,393:INFO:modifiedmom:main.py:146:handleKline:2218259: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False}


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

127.0.0.1 - - [10/Aug/2023 00:00:04] "POST / HTTP/1.1" 200 -
2023-08-10 00:00:04,189:INFO:pyemd2:main.py:303:handleOrderFilled:2217508: handleOrderFilled: data=OrderType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'clientorderid': '42833F1691596803538I0L57', 'symbol': 'BTCUSDT', 'gatewayorderid': 1691596803993935, 'quantity': '32.851', 'price': '29749.3', 'stopprice': '0', 'ordertype': '', 'side': 'SELL', 'status': 'FILLED', 'positionside': 'SHORT', 'createtime': 1691596802652, 'updatetime': 1691596803993, 'tradetype': 'usdt', 'selfid': 42833, 'filltrades': [TradeType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'tradeid': 1691596803993, 'clientorderid': '42833F1691596803538I0L57', 'price': '29749.3', 'quantity': '32.851', 'commission': '977.2942543', 'commissionasset': 'USDT', 'tradetime': 1691596803993, 'tradetype': 'usdt', 'gatetype': 'simulator', 'handletime': 1691596803993}], 'gatetype': 'simulator', 'handletime': 0}
127.0.0.1 - - [10/Aug/2023 00:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=12611 

self.closeSec=1691597399, self.tradeDate='20230810', self.openTime='000000', self.closeTime='000959', self.symbol='BTCUSDT', self.open='29749.3', self.close='29719.4'
2023-08-10 00:10:01,134:INFO:pyemd2:main.py:125:handleKline:2217508: self.closeSec=1691597399, self.tradeDate='20230810', self.openTime='000000', self.closeTime='000959',self.symbol='BTCUSDT',self.open='29749.3', self.close='29719.4'
2023-08-10 00:10:01,163:INFO:pyemd2:main.py:126:handleKline:2217508: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17420  20230809   232000    232959  1691594999  29748.8  29738.1
17421  20230809   233000    233959  1691595599  29738.1  29760.7
17422  20230809   234000    234959  1691596199  29762.6  29756.6
17423  20230809   235000    235959  1691596799  29756.5  29749.4
17424  20230810   000000    000959  1691597399  29749.3  29719.4
2023-08-10 00:10:01,163:INFO:pyemd2:main.py:127:handleKline:2217508: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=12612 

self.closeSec=1691597999, self.tradeDate='20230810', self.openTime='001000', self.closeTime='001959', self.symbol='BTCUSDT', self.open='29719.4', self.close='29735'
127.0.0.1 - - [10/Aug/2023 00:20:04] "POST / HTTP/1.1" 200 -
2023-08-10 00:20:08,489:INFO:pyemd2:main.py:125:handleKline:2217508: self.closeSec=1691597999, self.tradeDate='20230810', self.openTime='001000', self.closeTime='001959',self.symbol='BTCUSDT',self.open='29719.4', self.close='29735'
2023-08-10 00:20:08,621:INFO:pyemd2:main.py:126:handleKline:2217508: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17421  20230809   233000    233959  1691595599  29738.1  29760.7
17422  20230809   234000    234959  1691596199  29762.6  29756.6
17423  20230809   235000    235959  1691596799  29756.5  29749.4
17424  20230810   000000    000959  1691597399  29749.3  29719.4
17425  20230810   001000    001959  1691597999  29719.4    29735
2023-08-10 00:20:08,621:INFO:pyemd2:main.py:127:handleKline:2217508: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}


## /root/FIL/strategy/similarity/log.txt ----- -----

127.0.0.1 - - [10/Aug/2023 00:00:04] "POST / HTTP/1.1" 200 -
2023-08-10 00:00:04,474:INFO:testStrategy:main.py:308:handleOrderFilled:2217133: handleOrderFilled: data=OrderType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'clientorderid': '42835F1691596803685I0L2', 'symbol': 'BTCUSDT', 'gatewayorderid': 1691596804079996, 'quantity': '36.42', 'price': '29749.4', 'stopprice': '0', 'ordertype': '', 'side': 'BUY', 'status': 'FILLED', 'positionside': 'LONG', 'createtime': 1691596802732, 'updatetime': 1691596804079, 'tradetype': 'usdt', 'selfid': 42835, 'filltrades': [TradeType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'tradeid': 1691596804079, 'clientorderid': '42835F1691596803685I0L2', 'price': '29749.4', 'quantity': '36.42', 'commission': '1083.473148', 'commissionasset': 'USDT', 'tradetime': 1691596804079, 'tradetype': 'usdt', 'gatetype': 'simulator', 'handletime': 1691596804079}], 'gatetype': 'simulator', 'handletime': 0}
127.0.0.1 - - [10/Aug/2023 00:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=12611 

self.closeSec=1691597399, self.tradeDate='20230810', self.openTime='000000', self.closeTime='000959', self.symbol='BTCUSDT', self.open='29749.3', self.close='29719.4'
2023-08-10 00:10:01,132:INFO:testStrategy:main.py:101:handleKline:2217133: self.closeSec=1691597399, self.tradeDate='20230810', self.openTime='000000', self.closeTime='000959',self.symbol='BTCUSDT',self.open='29749.3', self.close='29719.4'
2023-08-10 00:10:01,140:INFO:testStrategy:main.py:102:handleKline:2217133: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12236  20230809   232000    232959  1691594999  29748.8  29738.1
12237  20230809   233000    233959  1691595599  29738.1  29760.7
12238  20230809   234000    234959  1691596199  29762.6  29756.6
12239  20230809   235000    235959  1691596799  29756.5  29749.4
12240  20230810   000000    000959  1691597399  29749.3  29719.4
2023-08-10 00:10:01,140:INFO:testStrategy:main.py:103:handleKline:2217133: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False, 'isCorr': False}

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=12612 

self.closeSec=1691597999, self.tradeDate='20230810', self.openTime='001000', self.closeTime='001959', self.symbol='BTCUSDT', self.open='29719.4', self.close='29735'
127.0.0.1 - - [10/Aug/2023 00:20:04] "POST / HTTP/1.1" 200 -
2023-08-10 00:20:08,237:INFO:testStrategy:main.py:101:handleKline:2217133: self.closeSec=1691597999, self.tradeDate='20230810', self.openTime='001000', self.closeTime='001959',self.symbol='BTCUSDT',self.open='29719.4', self.close='29735'
2023-08-10 00:20:08,460:INFO:testStrategy:main.py:102:handleKline:2217133: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12237  20230809   233000    233959  1691595599  29738.1  29760.7
12238  20230809   234000    234959  1691596199  29762.6  29756.6
12239  20230809   235000    235959  1691596799  29756.5  29749.4
12240  20230810   000000    000959  1691597399  29749.3  29719.4
12241  20230810   001000    001959  1691597999  29719.4    29735
2023-08-10 00:20:08,462:INFO:testStrategy:main.py:103:handleKline:2217133: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False, 'isCorr': False}


## /root/FIL/strategy/sr_min/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=1, self.total=996015.990996, self.flagDict['side']='buy', self.tradeCount=1, self.count=25216
self.closeSec=1691597999, self.tradeDate='20230810', self.openTime='001500', self.closeTime='001959', self.symbol='BTCUSDT', self.open=29745.9, self.close=29735.0, self.high=29759.9, self.low=29731.6, self.vol=797.797, self.amt=23731691.4526 
127.0.0.1 - - [10/Aug/2023 00:20:01] "POST / HTTP/1.1" 200 -
2023-08-10 00:20:06,373:INFO:sr_min:main.py:172:handleKline:2219263: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5759  20230809   235500    235959  ...         0.0        0.0       0
5760  20230810   000000    000459  ...         0.0        0.0       0
5761  20230810   000500    000959  ...         0.0        0.0       0
5762  20230810   001000    001459  ...         0.0        0.0       0
5763  20230810   001500    001959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-08-10 00:20:06,393:INFO:sr_min:main.py:175:handleKline:2219263: self.closeSec=1691597999, self.tradeDate='20230810', self.openTime='001500', self.closeTime='001959',self.symbol='BTCUSDT',self.open=29745.9, self.close=29735.0, self.high=29759.9, self.low=29731.6, self.vol=797.797, self.amt=23731691.4526, ukdf['pct'].iloc[-1]=-0.000319 , ukdf['amount'].iloc[-1]=23731691.4526, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5763, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '37.141', 'enterprice': '26844', 'countrevence': '0', 'unrealprofit': '107356.96698515919', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '29734.52440659', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=1
--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=1, self.total=996015.990996, self.flagDict['side']='buy', self.tradeCount=1, self.count=25217
self.closeSec=1691598299, self.tradeDate='20230810', self.openTime='002000', self.closeTime='002459', self.symbol='BTCUSDT', self.open=29735.0, self.close=29725.8, self.high=29735.1, self.low=29709.8, self.vol=549.453, self.amt=16329370.3893 
127.0.0.1 - - [10/Aug/2023 00:25:00] "POST / HTTP/1.1" 200 -
2023-08-10 00:25:00,772:INFO:sr_min:main.py:172:handleKline:2219263: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5760  20230810   000000    000459  ...         0.0        0.0       0
5761  20230810   000500    000959  ...         0.0        0.0       0
5762  20230810   001000    001459  ...         0.0        0.0       0
5763  20230810   001500    001959  ...         0.0        0.0       0
5764  20230810   002000    002459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-08-10 00:25:00,772:INFO:sr_min:main.py:175:handleKline:2219263: self.closeSec=1691598299, self.tradeDate='20230810', self.openTime='002000', self.closeTime='002459',self.symbol='BTCUSDT',self.open=29735.0, self.close=29725.8, self.high=29735.1, self.low=29709.8, self.vol=549.453, self.amt=16329370.3893, ukdf['pct'].iloc[-1]=-0.000309 , ukdf['amount'].iloc[-1]=16329370.3893, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5764, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '37.141', 'enterprice': '26844', 'countrevence': '0', 'unrealprofit': '107032.9338', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '29725.8', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=1


## /root/FIL/strategy/s_rsrs/log.txt ----- -----

723  20230809   120000    155959  1691567999  ...    723  1.152400  2.924316     1.0
724  20230809   160000    195959  1691582399  ...    724  1.097325  2.599960     1.0

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '51.457', 'enterprice': '29884.4', 'countrevence': '0', 'unrealprofit': '-365.97868780361', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '29877.28767927', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=1, self.sign=1
--handleKline--:  version='2.0.0', self.name='s_rsrs', self.symbol='BTCUSDT', interval='4h', intervalSec=14400, wid=25, thd=0.6, self.sign=1, self.total=1536223.8092292, self.flagDict['side']='buy', self.tradeCount=19, self.count=525
self.closeSec=1691596799, self.tradeDate='20230809', self.openTime='200000', self.closeTime='235959', self.symbol='BTCUSDT', self.open=29877.1, self.close=29749.4, self.high=30149.7, self.low=29663.0, self.vol=112574.075, self.amt=3364374864.74632 
127.0.0.1 - - [10/Aug/2023 00:00:01] "POST / HTTP/1.1" 200 -
2023-08-10 00:00:01,707:INFO:s_rsrs:main.py:141:handleKline:2218689: self.closeSec=1691596799, self.tradeDate='20230809', self.openTime='200000', self.closeTime='235959',self.symbol='BTCUSDT',self.open=29877.1, self.close=29749.4, self.high=30149.7, self.low=29663.0, self.vol=112574.075, self.amt=3364374864.74632 
2023-08-10 00:00:01,724:INFO:s_rsrs:main.py:142:handleKline:2218689: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime  ...         vol           amt       pct
721  20230809   040000    075959  ...   94730.676  2.834461e+09 -0.003623
722  20230809   080000    115959  ...   44098.378  1.311623e+09 -0.001647
723  20230809   120000    155959  ...   33679.663  1.001345e+09  0.003295
724  20230809   160000    195959  ...   39109.948  1.165713e+09  0.002322
725  20230809   200000    235959  ...  112574.075  3.364375e+09 -0.004274

[5 rows x 11 columns]
2023-08-10 00:00:02,703:INFO:s_rsrs:main.py:151:handleKline:2218689: df_s.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec  ...  index      beta    zscore  signal
721  20230809   040000    075959  1691539199  ...    721  1.132475  3.295378     1.0
722  20230809   080000    115959  1691553599  ...    722  1.254265  3.491010     1.0
723  20230809   120000    155959  1691567999  ...    723  1.152400  2.924316     1.0
724  20230809   160000    195959  1691582399  ...    724  1.097325  2.599960     1.0
725  20230809   200000    235959  1691596799  ...    725  1.205164  2.821489     1.0

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '51.457', 'enterprice': '29884.4', 'countrevence': '0', 'unrealprofit': '-6914.69656797857', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '29750.02184799', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=1, self.sign=1


