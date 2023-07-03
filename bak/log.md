# 20230704 00:26:01

## /root/FIL/strategy/amihud/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=373746.4768026, self.flagDict['side']='sell', self.tradeCount=2, self.count=14560
self.closeSec=1688401199, self.tradeDate='20230704', self.openTime='001500', self.closeTime='001959', self.symbol='BTCUSDT', self.open=30949.3, self.close=31018.7, self.high=31036.3, self.low=30938.7, self.vol=3312.961, self.amt=102710489.1183 
127.0.0.1 - - [04/Jul/2023 00:20:01] "POST / HTTP/1.1" 200 -
2023-07-04 00:20:07,167:INFO:amihud:main.py:172:handleKline:2219019: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5759  20230703   235500    235959  ...         0.0        0.0       0
5760  20230704   000000    000459  ...         0.0        0.0       0
5761  20230704   000500    000959  ...         0.0        0.0       0
5762  20230704   001000    001459  ...         0.0        0.0       0
5763  20230704   001500    001959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-07-04 00:20:07,206:INFO:amihud:main.py:175:handleKline:2219019: self.closeSec=1688401199, self.tradeDate='20230704', self.openTime='001500', self.closeTime='001959',self.symbol='BTCUSDT',self.open=30949.3, self.close=31018.7, self.high=31036.3, self.low=30938.7, self.vol=3312.961, self.amt=102710489.1183, ukdf['pct'].iloc[-1]=0.002242 , ukdf['amount'].iloc[-1]=102710489.1183, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5763, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '13.926', 'enterprice': '26864.9', 'countrevence': '0', 'unrealprofit': '-57714.55762785636', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '31009.27438086', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1
127.0.0.1 - - [04/Jul/2023 00:25:00] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=373746.4768026, self.flagDict['side']='sell', self.tradeCount=2, self.count=14561
self.closeSec=1688401499, self.tradeDate='20230704', self.openTime='002000', self.closeTime='002459', self.symbol='BTCUSDT', self.open=31019.2, self.close=30995.7, self.high=31021.6, self.low=30980.1, self.vol=1425.898, self.amt=44206575.2527 
2023-07-04 00:25:00,791:INFO:amihud:main.py:172:handleKline:2219019: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5760  20230704   000000    000459  ...         0.0        0.0       0
5761  20230704   000500    000959  ...         0.0        0.0       0
5762  20230704   001000    001459  ...         0.0        0.0       0
5763  20230704   001500    001959  ...         0.0        0.0       0
5764  20230704   002000    002459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-07-04 00:25:00,791:INFO:amihud:main.py:175:handleKline:2219019: self.closeSec=1688401499, self.tradeDate='20230704', self.openTime='002000', self.closeTime='002459',self.symbol='BTCUSDT',self.open=31019.2, self.close=30995.7, self.high=31021.6, self.low=30980.1, self.vol=1425.898, self.amt=44206575.2527, ukdf['pct'].iloc[-1]=-0.000741 , ukdf['amount'].iloc[-1]=44206575.2527, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5764, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '13.926', 'enterprice': '26864.9', 'countrevence': '0', 'unrealprofit': '-57567.2988', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '30998.7', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1


## /root/FIL/strategy/factorcheck/log.txt ----- -----


self.closeSec=1688401199, self.tradeDate='20230704', self.openTime='001500', self.closeTime='001959', self.symbol='BTCUSDT', self.open=30949.3, self.close=31018.7, self.high=31036.3, self.low=30938.7 
127.0.0.1 - - [04/Jul/2023 00:20:01] "POST / HTTP/1.1" 200 -
2023-07-04 00:20:04,886:INFO:factorcheck2:main.py:126:handleKline:2218005: self.closeSec=1688401199, self.tradeDate='20230704', self.openTime='001500', self.closeTime='001959',self.symbol='BTCUSDT',self.open=30949.3, self.close=31018.7, self.high=31036.3, self.low=30938.7   
2023-07-04 00:20:06,336:INFO:factorcheck2:main.py:127:handleKline:2218005: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1439  20230703   235500    235959  1688399999  ...  31021.0  0.000506   1727    5
1440  20230704   000000    000459  1688400299  ...  31050.8 -0.000068   1440    0
1441  20230704   000500    000959  1688400599  ...  30810.2 -0.003722   1441    1
1442  20230704   001000    001459  1688400899  ...  30925.3  0.000268   1442    2
1443  20230704   001500    001959  1688401199  ...  30938.7  0.002242   1443    3

[5 rows x 11 columns]
2023-07-04 00:20:06,347:INFO:factorcheck2:main.py:128:handleKline:2218005: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=158, self.factor=0.341978877897214, self.count=14563 

self.closeSec=1688401499, self.tradeDate='20230704', self.openTime='002000', self.closeTime='002459', self.symbol='BTCUSDT', self.open=31019.2, self.close=30995.7, self.high=31021.6, self.low=30980.1 
127.0.0.1 - - [04/Jul/2023 00:25:00] "POST / HTTP/1.1" 200 -
2023-07-04 00:25:00,726:INFO:factorcheck2:main.py:126:handleKline:2218005: self.closeSec=1688401499, self.tradeDate='20230704', self.openTime='002000', self.closeTime='002459',self.symbol='BTCUSDT',self.open=31019.2, self.close=30995.7, self.high=31021.6, self.low=30980.1   
2023-07-04 00:25:00,767:INFO:factorcheck2:main.py:127:handleKline:2218005: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1440  20230704   000000    000459  1688400299  ...  31050.8 -0.000068   1440    0
1441  20230704   000500    000959  1688400599  ...  30810.2 -0.003722   1441    1
1442  20230704   001000    001459  1688400899  ...  30925.3  0.000268   1442    2
1443  20230704   001500    001959  1688401199  ...  30938.7  0.002242   1443    3
1444  20230704   002000    002459  1688401499  ...  30980.1 -0.000741   1444    4

[5 rows x 11 columns]
2023-07-04 00:25:00,767:INFO:factorcheck2:main.py:128:handleKline:2218005: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}


## /root/FIL/strategy/logic/log.txt ----- -----

2023-07-04 00:00:19,019:DEBUG:logic:main.py:463:getModel:2218526: df_s.iloc[-5:,:] :
          date closeTime     open  ...    alpha58   alpha67   alpha72
5802  20230703    212959  30648.0  ...  52.916667  0.510139  0.292986
5803  20230703    215959  30617.6  ...  52.916667  0.517637  0.296999
5804  20230703    222959  30643.9  ...  52.916667  0.521347  0.302604
5805  20230703    225959  30657.7  ...  52.916667  0.541348  0.294892
5806  20230703    232959  30729.8  ...  52.916667  0.590044  0.277417

[5 rows x 33 columns]
0.5220588235294118
acc is : 0.5220588235294118
2023-07-04 00:00:19,119:INFO:logic:main.py:468:getModel:2218526: df_pred.iloc[-5:,:] :
     pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
539     0  0.513393  0.486607       1  ...  0.979158   1.0    0.0  1.018259
540     0  0.521223  0.478777       1  ...  0.979577   1.0    0.0  1.018694
541     0  0.521257  0.478743       1  ...  0.981903   1.0    0.0  1.021113
542     0  0.537859  0.462141       1  ...  0.988383   1.0    0.0  1.027852
543     0  0.565740  0.434260       1  ...  0.992409   1.0    0.0  1.032039

[5 rows x 10 columns]
2023-07-04 00:00:19,141:INFO:logic:main.py:478:getModel:2218526: df_panel.iloc[-5:,:] :
    pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
45     0  0.513893  0.486107       1  ...  0.979158   1.0    0.0  1.017377
46     0  0.521552  0.478448       1  ...  0.979577   1.0    0.0  1.017832
47     0  0.521549  0.478451       1  ...  0.981903   1.0    0.0  1.020249
48     0  0.538345  0.461655       1  ...  0.988383   1.0    0.0  1.029124
49     0  0.565740  0.434260       1  ...  0.992409   1.0    0.0  1.032039

[5 rows x 10 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '25.53', 'enterprice': '30560', 'countrevence': '0', 'unrealprofit': '13564.089', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '31091.3', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}


## /root/FIL/strategy/modifiedmom/log.txt ----- -----

127.0.0.1 - - [04/Jul/2023 00:00:04] "POST / HTTP/1.1" 200 -
2023-07-04 00:00:04,268:INFO:modifiedmom:main.py:319:handleOrderFilled:2218259: handleOrderFilled: data=OrderType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'clientorderid': '42520F1688400003665I0L59', 'symbol': 'BTCUSDT', 'gatewayorderid': 1688400004064537, 'quantity': '25.136', 'price': '31067.9', 'stopprice': '0', 'ordertype': '', 'side': 'SELL', 'status': 'FILLED', 'positionside': 'SHORT', 'createtime': 1688400002722, 'updatetime': 1688400004064, 'tradetype': 'usdt', 'selfid': 42520, 'filltrades': [TradeType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'tradeid': 1688400004064, 'clientorderid': '42520F1688400003665I0L59', 'price': '31067.9', 'quantity': '25.136', 'commission': '780.9227344', 'commissionasset': 'USDT', 'tradetime': 1688400004064, 'tradetype': 'usdt', 'gatetype': 'simulator', 'handletime': 1688400004064}], 'gatetype': 'simulator', 'handletime': 0}

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=7280 

self.closeSec=1688400599, self.tradeDate='20230704', self.openTime='000000', self.closeTime='000959', self.symbol='BTCUSDT', self.open='31068', self.close='30941'
127.0.0.1 - - [04/Jul/2023 00:10:01] "POST / HTTP/1.1" 200 -
2023-07-04 00:10:01,085:INFO:modifiedmom:main.py:144:handleKline:2218259: self.closeSec=1688400599, self.tradeDate='20230704', self.openTime='000000', self.closeTime='000959',self.symbol='BTCUSDT',self.open='31068', self.close='30941'
2023-07-04 00:10:01,150:INFO:modifiedmom:main.py:145:handleKline:2218259: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
572  20230703   232000    232959  1688398199  30839.4  30932.7  0.003025
573  20230703   233000    233959  1688398799  30932.7  30975.2  0.001374
574  20230703   234000    234959  1688399399  30975.1  31093.6  0.003822
575  20230703   235000    235959  1688399999  31093.6  31058.7 -0.001122
576  20230704   000000    000959  1688400599    31068    30941 -0.003790
2023-07-04 00:10:01,150:INFO:modifiedmom:main.py:146:handleKline:2218259: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=7281 

self.closeSec=1688401199, self.tradeDate='20230704', self.openTime='001000', self.closeTime='001959', self.symbol='BTCUSDT', self.open='30944.1', self.close='31019.1'
127.0.0.1 - - [04/Jul/2023 00:20:04] "POST / HTTP/1.1" 200 -
2023-07-04 00:20:07,137:INFO:modifiedmom:main.py:144:handleKline:2218259: self.closeSec=1688401199, self.tradeDate='20230704', self.openTime='001000', self.closeTime='001959',self.symbol='BTCUSDT',self.open='30944.1', self.close='31019.1'
2023-07-04 00:20:07,956:INFO:modifiedmom:main.py:145:handleKline:2218259: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
573  20230703   233000    233959  1688398799  30932.7  30975.2  0.001374
574  20230703   234000    234959  1688399399  30975.1  31093.6  0.003822
575  20230703   235000    235959  1688399999  31093.6  31058.7 -0.001122
576  20230704   000000    000959  1688400599    31068    30941 -0.003790
577  20230704   001000    001959  1688401199  30944.1  31019.1  0.002524
2023-07-04 00:20:07,957:INFO:modifiedmom:main.py:146:handleKline:2218259: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False}


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

2023-07-04 00:00:02,213:INFO:pyemd2:main.py:127:handleKline:2217508: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}
2023-07-04 00:00:02,302:INFO:pyemd2:main.py:190:insertFactor:2217508: curDateTime:7040000, name:pyemd2, symbol:BTCUSDT, tradeDate:20230703, closeTime:235959, close:31058.7, total:995666.2287338, pct_pre:0.003584041342720168, thd:-0.3379938379459325, side:sell 

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=7283 

self.closeSec=1688400599, self.tradeDate='20230704', self.openTime='000000', self.closeTime='000959', self.symbol='BTCUSDT', self.open='31068', self.close='30941'
2023-07-04 00:10:01,096:INFO:pyemd2:main.py:125:handleKline:2217508: self.closeSec=1688400599, self.tradeDate='20230704', self.openTime='000000', self.closeTime='000959',self.symbol='BTCUSDT',self.open='31068', self.close='30941'
127.0.0.1 - - [04/Jul/2023 00:10:01] "POST / HTTP/1.1" 200 -
2023-07-04 00:10:01,162:INFO:pyemd2:main.py:126:handleKline:2217508: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17420  20230703   232000    232959  1688398199  30839.4  30932.7
17421  20230703   233000    233959  1688398799  30932.7  30975.2
17422  20230703   234000    234959  1688399399  30975.1  31093.6
17423  20230703   235000    235959  1688399999  31093.6  31058.7
17424  20230704   000000    000959  1688400599    31068    30941
2023-07-04 00:10:01,162:INFO:pyemd2:main.py:127:handleKline:2217508: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=7284 

self.closeSec=1688401199, self.tradeDate='20230704', self.openTime='001000', self.closeTime='001959', self.symbol='BTCUSDT', self.open='30944.1', self.close='31019.1'
127.0.0.1 - - [04/Jul/2023 00:20:04] "POST / HTTP/1.1" 200 -
2023-07-04 00:20:09,019:INFO:pyemd2:main.py:125:handleKline:2217508: self.closeSec=1688401199, self.tradeDate='20230704', self.openTime='001000', self.closeTime='001959',self.symbol='BTCUSDT',self.open='30944.1', self.close='31019.1'
2023-07-04 00:20:09,147:INFO:pyemd2:main.py:126:handleKline:2217508: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17421  20230703   233000    233959  1688398799  30932.7  30975.2
17422  20230703   234000    234959  1688399399  30975.1  31093.6
17423  20230703   235000    235959  1688399999  31093.6  31058.7
17424  20230704   000000    000959  1688400599    31068    30941
17425  20230704   001000    001959  1688401199  30944.1  31019.1
2023-07-04 00:20:09,148:INFO:pyemd2:main.py:127:handleKline:2217508: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}


## /root/FIL/strategy/similarity/log.txt ----- -----

2023-07-04 00:00:04,403:INFO:testStrategy:main.py:308:handleOrderFilled:2217133: handleOrderFilled: data=OrderType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'clientorderid': '42521F1688400003708I0L2', 'symbol': 'BTCUSDT', 'gatewayorderid': 1688400004074647, 'quantity': '37.383', 'price': '31068', 'stopprice': '0', 'ordertype': '', 'side': 'BUY', 'status': 'FILLED', 'positionside': 'LONG', 'createtime': 1688400002787, 'updatetime': 1688400004074, 'tradetype': 'usdt', 'selfid': 42521, 'filltrades': [TradeType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'tradeid': 1688400004074, 'clientorderid': '42521F1688400003708I0L2', 'price': '31068', 'quantity': '37.383', 'commission': '1161.415044', 'commissionasset': 'USDT', 'tradetime': 1688400004074, 'tradetype': 'usdt', 'gatetype': 'simulator', 'handletime': 1688400004074}], 'gatetype': 'simulator', 'handletime': 0}
127.0.0.1 - - [04/Jul/2023 00:00:04] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=7283 

self.closeSec=1688400599, self.tradeDate='20230704', self.openTime='000000', self.closeTime='000959', self.symbol='BTCUSDT', self.open='31068', self.close='30941'
127.0.0.1 - - [04/Jul/2023 00:10:01] "POST / HTTP/1.1" 200 -
2023-07-04 00:10:01,107:INFO:testStrategy:main.py:101:handleKline:2217133: self.closeSec=1688400599, self.tradeDate='20230704', self.openTime='000000', self.closeTime='000959',self.symbol='BTCUSDT',self.open='31068', self.close='30941'
2023-07-04 00:10:01,157:INFO:testStrategy:main.py:102:handleKline:2217133: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12236  20230703   232000    232959  1688398199  30839.4  30932.7
12237  20230703   233000    233959  1688398799  30932.7  30975.2
12238  20230703   234000    234959  1688399399  30975.1  31093.6
12239  20230703   235000    235959  1688399999  31093.6  31058.7
12240  20230704   000000    000959  1688400599    31068    30941
2023-07-04 00:10:01,157:INFO:testStrategy:main.py:103:handleKline:2217133: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False, 'isCorr': False}

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=7284 

self.closeSec=1688401199, self.tradeDate='20230704', self.openTime='001000', self.closeTime='001959', self.symbol='BTCUSDT', self.open='30944.1', self.close='31019.1'
127.0.0.1 - - [04/Jul/2023 00:20:04] "POST / HTTP/1.1" 200 -
2023-07-04 00:20:08,601:INFO:testStrategy:main.py:101:handleKline:2217133: self.closeSec=1688401199, self.tradeDate='20230704', self.openTime='001000', self.closeTime='001959',self.symbol='BTCUSDT',self.open='30944.1', self.close='31019.1'
2023-07-04 00:20:08,925:INFO:testStrategy:main.py:102:handleKline:2217133: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12237  20230703   233000    233959  1688398799  30932.7  30975.2
12238  20230703   234000    234959  1688399399  30975.1  31093.6
12239  20230703   235000    235959  1688399999  31093.6  31058.7
12240  20230704   000000    000959  1688400599    31068    30941
12241  20230704   001000    001959  1688401199  30944.1  31019.1
2023-07-04 00:20:08,926:INFO:testStrategy:main.py:103:handleKline:2217133: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False, 'isCorr': False}


## /root/FIL/strategy/sr_min/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=1, self.total=996015.990996, self.flagDict['side']='buy', self.tradeCount=1, self.count=14560
self.closeSec=1688401199, self.tradeDate='20230704', self.openTime='001500', self.closeTime='001959', self.symbol='BTCUSDT', self.open=30949.3, self.close=31018.7, self.high=31036.3, self.low=30938.7, self.vol=3312.961, self.amt=102710489.1183 
127.0.0.1 - - [04/Jul/2023 00:20:01] "POST / HTTP/1.1" 200 -
2023-07-04 00:20:07,165:INFO:sr_min:main.py:172:handleKline:2219263: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5759  20230703   235500    235959  ...         0.0        0.0       0
5760  20230704   000000    000459  ...         0.0        0.0       0
5761  20230704   000500    000959  ...         0.0        0.0       0
5762  20230704   001000    001459  ...         0.0        0.0       0
5763  20230704   001500    001959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-07-04 00:20:07,196:INFO:sr_min:main.py:175:handleKline:2219263: self.closeSec=1688401199, self.tradeDate='20230704', self.openTime='001500', self.closeTime='001959',self.symbol='BTCUSDT',self.open=30949.3, self.close=31018.7, self.high=31036.3, self.low=30938.7, self.vol=3312.961, self.amt=102710489.1183, ukdf['pct'].iloc[-1]=0.002242 , ukdf['amount'].iloc[-1]=102710489.1183, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5763, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '37.141', 'enterprice': '26844', 'countrevence': '0', 'unrealprofit': '154702.45577952126', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '31009.27438086', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=1
--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=1, self.total=996015.990996, self.flagDict['side']='buy', self.tradeCount=1, self.count=14561
self.closeSec=1688401499, self.tradeDate='20230704', self.openTime='002000', self.closeTime='002459', self.symbol='BTCUSDT', self.open=31019.2, self.close=30995.7, self.high=31021.6, self.low=30980.1, self.vol=1425.898, self.amt=44206575.2527 
127.0.0.1 - - [04/Jul/2023 00:25:00] "POST / HTTP/1.1" 200 -
2023-07-04 00:25:00,803:INFO:sr_min:main.py:172:handleKline:2219263: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5760  20230704   000000    000459  ...         0.0        0.0       0
5761  20230704   000500    000959  ...         0.0        0.0       0
5762  20230704   001000    001459  ...         0.0        0.0       0
5763  20230704   001500    001959  ...         0.0        0.0       0
5764  20230704   002000    002459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-07-04 00:25:00,803:INFO:sr_min:main.py:175:handleKline:2219263: self.closeSec=1688401499, self.tradeDate='20230704', self.openTime='002000', self.closeTime='002459',self.symbol='BTCUSDT',self.open=31019.2, self.close=30995.7, self.high=31021.6, self.low=30980.1, self.vol=1425.898, self.amt=44206575.2527, ukdf['pct'].iloc[-1]=-0.000741 , ukdf['amount'].iloc[-1]=44206575.2527, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5764, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '37.141', 'enterprice': '26844', 'countrevence': '0', 'unrealprofit': '154309.7127', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '30998.7', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=1


## /root/FIL/strategy/s_rsrs/log.txt ----- -----

723  20230703   120000    155959  1688371199  ...    723  0.000010 -1.178390    -1.0
724  20230703   160000    195959  1688385599  ...    724  0.000193 -1.153916    -1.0

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '53.268', 'enterprice': '30707', 'countrevence': '0', 'unrealprofit': '4643.3504871792', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '30619.8303956', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-1, self.sign=-1
127.0.0.1 - - [04/Jul/2023 00:00:01] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='s_rsrs', self.symbol='BTCUSDT', interval='4h', intervalSec=14400, wid=25, thd=0.6, self.sign=-1, self.total=1634064.775524, self.flagDict['side']='sell', self.tradeCount=8, self.count=303
self.closeSec=1688399999, self.tradeDate='20230703', self.openTime='200000', self.closeTime='235959', self.symbol='BTCUSDT', self.open=30619.7, self.close=31058.7, self.high=31179.0, self.low=30559.4, self.vol=104314.045, self.amt=3220393140.27357 
2023-07-04 00:00:01,655:INFO:s_rsrs:main.py:141:handleKline:2218689: self.closeSec=1688399999, self.tradeDate='20230703', self.openTime='200000', self.closeTime='235959',self.symbol='BTCUSDT',self.open=30619.7, self.close=31058.7, self.high=31179.0, self.low=30559.4, self.vol=104314.045, self.amt=3220393140.27357 
2023-07-04 00:00:01,697:INFO:s_rsrs:main.py:142:handleKline:2218689: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime  ...         vol           amt       pct
721  20230703   040000    075959  ...   65600.069  2.008247e+09  0.001961
722  20230703   080000    115959  ...   35710.618  1.096408e+09  0.004416
723  20230703   120000    155959  ...   33689.441  1.033809e+09 -0.002768
724  20230703   160000    195959  ...   24118.202  7.388557e+08 -0.001409
725  20230703   200000    235959  ...  104314.045  3.220393e+09  0.014340

[5 rows x 11 columns]
2023-07-04 00:00:03,313:INFO:s_rsrs:main.py:151:handleKline:2218689: df_s.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec  ...  index      beta    zscore  signal
721  20230703   040000    075959  1688342399  ...    721  0.000300 -1.227609    -1.0
722  20230703   080000    115959  1688356799  ...    722  0.000001 -1.203165    -1.0
723  20230703   120000    155959  1688371199  ...    723  0.000010 -1.178390    -1.0
724  20230703   160000    195959  1688385599  ...    724  0.000193 -1.153916    -1.0
725  20230703   200000    235959  1688399999  ...    725  0.000007 -1.130948    -1.0

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '53.268', 'enterprice': '30707', 'countrevence': '0', 'unrealprofit': '-19279.8489563868', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '31068.9405451', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-1, self.sign=-1


