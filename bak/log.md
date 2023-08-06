# 20230807 00:26:01

## /root/FIL/strategy/amihud/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=373746.4768026, self.flagDict['side']='sell', self.tradeCount=2, self.count=24352
self.closeSec=1691338799, self.tradeDate='20230807', self.openTime='001500', self.closeTime='001959', self.symbol='BTCUSDT', self.open=29012.8, self.close=29003.7, self.high=29012.8, self.low=29003.6, self.vol=289.021, self.amt=8383809.8899 
127.0.0.1 - - [07/Aug/2023 00:20:01] "POST / HTTP/1.1" 200 -
2023-08-07 00:20:06,575:INFO:amihud:main.py:172:handleKline:2219019: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5759  20230806   235500    235959  ...         0.0        0.0       0
5760  20230807   000000    000459  ...         0.0        0.0       0
5761  20230807   000500    000959  ...         0.0        0.0       0
5762  20230807   001000    001459  ...         0.0        0.0       0
5763  20230807   001500    001959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-08-07 00:20:06,595:INFO:amihud:main.py:175:handleKline:2219019: self.closeSec=1691338799, self.tradeDate='20230807', self.openTime='001500', self.closeTime='001959',self.symbol='BTCUSDT',self.open=29012.8, self.close=29003.7, self.high=29012.8, self.low=29003.6, self.vol=289.021, self.amt=8383809.8899, ukdf['pct'].iloc[-1]=-0.000314 , ukdf['amount'].iloc[-1]=8383809.8899, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5763, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '13.926', 'enterprice': '26864.9', 'countrevence': '0', 'unrealprofit': '-29793.89905687536', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '29004.34413736', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1
--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=373746.4768026, self.flagDict['side']='sell', self.tradeCount=2, self.count=24353
self.closeSec=1691339099, self.tradeDate='20230807', self.openTime='002000', self.closeTime='002459', self.symbol='BTCUSDT', self.open=29003.7, self.close=29010.5, self.high=29010.6, self.low=29003.6, self.vol=177.422, self.amt=5146440.9954 
127.0.0.1 - - [07/Aug/2023 00:25:00] "POST / HTTP/1.1" 200 -
2023-08-07 00:25:00,802:INFO:amihud:main.py:172:handleKline:2219019: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5760  20230807   000000    000459  ...         0.0        0.0       0
5761  20230807   000500    000959  ...         0.0        0.0       0
5762  20230807   001000    001459  ...         0.0        0.0       0
5763  20230807   001500    001959  ...         0.0        0.0       0
5764  20230807   002000    002459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-08-07 00:25:00,802:INFO:amihud:main.py:175:handleKline:2219019: self.closeSec=1691339099, self.tradeDate='20230807', self.openTime='002000', self.closeTime='002459',self.symbol='BTCUSDT',self.open=29003.7, self.close=29010.5, self.high=29010.6, self.low=29003.6, self.vol=177.422, self.amt=5146440.9954, ukdf['pct'].iloc[-1]=0.000234 , ukdf['amount'].iloc[-1]=5146440.9954, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5764, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '13.926', 'enterprice': '26864.9', 'countrevence': '0', 'unrealprofit': '-29879.6256', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '29010.5', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1


## /root/FIL/strategy/factorcheck/log.txt ----- -----


self.closeSec=1691338799, self.tradeDate='20230807', self.openTime='001500', self.closeTime='001959', self.symbol='BTCUSDT', self.open=29012.8, self.close=29003.7, self.high=29012.8, self.low=29003.6 
127.0.0.1 - - [07/Aug/2023 00:20:01] "POST / HTTP/1.1" 200 -
2023-08-07 00:20:04,579:INFO:factorcheck2:main.py:126:handleKline:2218005: self.closeSec=1691338799, self.tradeDate='20230807', self.openTime='001500', self.closeTime='001959',self.symbol='BTCUSDT',self.open=29012.8, self.close=29003.7, self.high=29012.8, self.low=29003.6   
2023-08-07 00:20:05,847:INFO:factorcheck2:main.py:127:handleKline:2218005: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1439  20230806   235500    235959  1691337599  ...  28999.9  0.000038   1727    5
1440  20230807   000000    000459  1691337899  ...  28983.7  0.000121   1440    0
1441  20230807   000500    000959  1691338199  ...  28992.4 -0.000417   1441    1
1442  20230807   001000    001459  1691338499  ...  28992.4  0.000704   1442    2
1443  20230807   001500    001959  1691338799  ...  29003.6 -0.000314   1443    3

[5 rows x 11 columns]
2023-08-07 00:20:05,859:INFO:factorcheck2:main.py:128:handleKline:2218005: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=107, self.factor=0.5322186160694661, self.count=24355 

self.closeSec=1691339099, self.tradeDate='20230807', self.openTime='002000', self.closeTime='002459', self.symbol='BTCUSDT', self.open=29003.7, self.close=29010.5, self.high=29010.6, self.low=29003.6 
127.0.0.1 - - [07/Aug/2023 00:25:00] "POST / HTTP/1.1" 200 -
2023-08-07 00:25:00,767:INFO:factorcheck2:main.py:126:handleKline:2218005: self.closeSec=1691339099, self.tradeDate='20230807', self.openTime='002000', self.closeTime='002459',self.symbol='BTCUSDT',self.open=29003.7, self.close=29010.5, self.high=29010.6, self.low=29003.6   
2023-08-07 00:25:00,789:INFO:factorcheck2:main.py:127:handleKline:2218005: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1440  20230807   000000    000459  1691337899  ...  28983.7  0.000121   1440    0
1441  20230807   000500    000959  1691338199  ...  28992.4 -0.000417   1441    1
1442  20230807   001000    001459  1691338499  ...  28992.4  0.000704   1442    2
1443  20230807   001500    001959  1691338799  ...  29003.6 -0.000314   1443    3
1444  20230807   002000    002459  1691339099  ...  29003.6  0.000234   1444    4

[5 rows x 11 columns]
2023-08-07 00:25:00,790:INFO:factorcheck2:main.py:128:handleKline:2218005: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}


## /root/FIL/strategy/logic/log.txt ----- -----

2023-08-07 00:00:17,327:DEBUG:logic:main.py:463:getModel:2218526: df_s.iloc[-5:,:] :
          date closeTime     open  ...    alpha58   alpha67   alpha72
5802  20230806    212959  29026.1  ...  49.583333  0.458509  0.441867
5803  20230806    215959  29012.3  ...  49.583333  0.453059  0.479076
5804  20230806    222959  29002.0  ...  50.000000  0.468214  0.493087
5805  20230806    225959  29026.1  ...  50.416667  0.469887  0.504992
5806  20230806    232959  29028.8  ...  50.416667  0.469051  0.516755

[5 rows x 33 columns]
0.5422794117647058
acc is : 0.5422794117647058
2023-08-07 00:00:17,390:INFO:logic:main.py:468:getModel:2218526: df_pred.iloc[-5:,:] :
     pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
539     1  0.495381  0.504619       0  ...  0.961523   1.0    0.0  0.993039
540     1  0.495594  0.504406       1  ...  0.962325   1.0    0.0  0.993868
541     0  0.506035  0.493965       1  ...  0.962415   1.0    0.0  0.993960
542     0  0.500512  0.499488       0  ...  0.962365   1.0    0.0  0.993909
543     0  0.501198  0.498802       0  ...  0.961490   1.0    0.0  0.993005

[5 rows x 10 columns]
2023-08-07 00:00:17,401:INFO:logic:main.py:478:getModel:2218526: df_panel.iloc[-5:,:] :
    pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
45     1  0.495825  0.504175       0  ...  0.982102   1.0    0.0  0.991416
46     1  0.495829  0.504171       1  ...  0.982922   1.0    0.0  0.994096
47     0  0.506249  0.493751       1  ...  0.983013   1.0    0.0  0.994188
48     0  0.500642  0.499358       0  ...  0.962365   1.0    0.0  0.994072
49     0  0.501198  0.498802       0  ...  0.961490   1.0    0.0  0.993005

[5 rows x 10 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '24.06', 'enterprice': '29131.5', 'countrevence': '0', 'unrealprofit': '-3125.394', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '29001.6', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}


## /root/FIL/strategy/modifiedmom/log.txt ----- -----

127.0.0.1 - - [07/Aug/2023 00:00:04] "POST / HTTP/1.1" 200 -
2023-08-07 00:00:04,259:INFO:modifiedmom:main.py:319:handleOrderFilled:2218259: handleOrderFilled: data=OrderType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'clientorderid': '42815F1691337603570I0L59', 'symbol': 'BTCUSDT', 'gatewayorderid': 1691337604037630, 'quantity': '24.992', 'price': '29001.1', 'stopprice': '0', 'ordertype': '', 'side': 'BUY', 'status': 'FILLED', 'positionside': 'LONG', 'createtime': 1691337602635, 'updatetime': 1691337604037, 'tradetype': 'usdt', 'selfid': 42815, 'filltrades': [TradeType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'tradeid': 1691337604037, 'clientorderid': '42815F1691337603570I0L59', 'price': '29001.1', 'quantity': '24.992', 'commission': '724.7954912', 'commissionasset': 'USDT', 'tradetime': 1691337604037, 'tradetype': 'usdt', 'gatetype': 'simulator', 'handletime': 1691337604037}], 'gatetype': 'simulator', 'handletime': 0}
127.0.0.1 - - [07/Aug/2023 00:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=12176 

self.closeSec=1691338199, self.tradeDate='20230807', self.openTime='000000', self.closeTime='000959', self.symbol='BTCUSDT', self.open='29001.1', self.close='28992.4'
2023-08-07 00:10:01,127:INFO:modifiedmom:main.py:144:handleKline:2218259: self.closeSec=1691338199, self.tradeDate='20230807', self.openTime='000000', self.closeTime='000959',self.symbol='BTCUSDT',self.open='29001.1', self.close='28992.4'
2023-08-07 00:10:01,145:INFO:modifiedmom:main.py:145:handleKline:2218259: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
572  20230806   232000    232959  1691335799  29028.7  29027.3 -0.000048
573  20230806   233000    233959  1691336399  29027.4    29022 -0.000183
574  20230806   234000    234959  1691336999    29022  29006.5 -0.000534
575  20230806   235000    235959  1691337599  29006.5    29001 -0.000190
576  20230807   000000    000959  1691338199  29001.1  28992.4 -0.000297
2023-08-07 00:10:01,145:INFO:modifiedmom:main.py:146:handleKline:2218259: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=12177 

self.closeSec=1691338799, self.tradeDate='20230807', self.openTime='001000', self.closeTime='001959', self.symbol='BTCUSDT', self.open='28992.5', self.close='29003.7'
127.0.0.1 - - [07/Aug/2023 00:20:04] "POST / HTTP/1.1" 200 -
2023-08-07 00:20:07,155:INFO:modifiedmom:main.py:144:handleKline:2218259: self.closeSec=1691338799, self.tradeDate='20230807', self.openTime='001000', self.closeTime='001959',self.symbol='BTCUSDT',self.open='28992.5', self.close='29003.7'
2023-08-07 00:20:07,785:INFO:modifiedmom:main.py:145:handleKline:2218259: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
573  20230806   233000    233959  1691336399  29027.4    29022 -0.000183
574  20230806   234000    234959  1691336999    29022  29006.5 -0.000534
575  20230806   235000    235959  1691337599  29006.5    29001 -0.000190
576  20230807   000000    000959  1691338199  29001.1  28992.4 -0.000297
577  20230807   001000    001959  1691338799  28992.5  29003.7  0.000390
2023-08-07 00:20:07,785:INFO:modifiedmom:main.py:146:handleKline:2218259: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False}


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

127.0.0.1 - - [07/Aug/2023 00:00:03] "POST / HTTP/1.1" 200 -
2023-08-07 00:00:03,927:INFO:pyemd2:main.py:303:handleOrderFilled:2217508: handleOrderFilled: data=OrderType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'clientorderid': '42813F1691337603372I0L57', 'symbol': 'BTCUSDT', 'gatewayorderid': 1691337603772775, 'quantity': '34.057', 'price': '29001', 'stopprice': '0', 'ordertype': '', 'side': 'SELL', 'status': 'FILLED', 'positionside': 'SHORT', 'createtime': 1691337602501, 'updatetime': 1691337603772, 'tradetype': 'usdt', 'selfid': 42813, 'filltrades': [TradeType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'tradeid': 1691337603772, 'clientorderid': '42813F1691337603372I0L57', 'price': '29001', 'quantity': '34.057', 'commission': '987.687057', 'commissionasset': 'USDT', 'tradetime': 1691337603772, 'tradetype': 'usdt', 'gatetype': 'simulator', 'handletime': 1691337603772}], 'gatetype': 'simulator', 'handletime': 0}
127.0.0.1 - - [07/Aug/2023 00:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=12179 

self.closeSec=1691338199, self.tradeDate='20230807', self.openTime='000000', self.closeTime='000959', self.symbol='BTCUSDT', self.open='29001.1', self.close='28992.4'
2023-08-07 00:10:01,135:INFO:pyemd2:main.py:125:handleKline:2217508: self.closeSec=1691338199, self.tradeDate='20230807', self.openTime='000000', self.closeTime='000959',self.symbol='BTCUSDT',self.open='29001.1', self.close='28992.4'
2023-08-07 00:10:01,148:INFO:pyemd2:main.py:126:handleKline:2217508: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17420  20230806   232000    232959  1691335799  29028.7  29027.3
17421  20230806   233000    233959  1691336399  29027.4    29022
17422  20230806   234000    234959  1691336999    29022  29006.5
17423  20230806   235000    235959  1691337599  29006.5    29001
17424  20230807   000000    000959  1691338199  29001.1  28992.4
2023-08-07 00:10:01,149:INFO:pyemd2:main.py:127:handleKline:2217508: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=12180 

self.closeSec=1691338799, self.tradeDate='20230807', self.openTime='001000', self.closeTime='001959', self.symbol='BTCUSDT', self.open='28992.5', self.close='29003.7'
127.0.0.1 - - [07/Aug/2023 00:20:04] "POST / HTTP/1.1" 200 -
2023-08-07 00:20:08,897:INFO:pyemd2:main.py:125:handleKline:2217508: self.closeSec=1691338799, self.tradeDate='20230807', self.openTime='001000', self.closeTime='001959',self.symbol='BTCUSDT',self.open='28992.5', self.close='29003.7'
2023-08-07 00:20:09,038:INFO:pyemd2:main.py:126:handleKline:2217508: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17421  20230806   233000    233959  1691336399  29027.4    29022
17422  20230806   234000    234959  1691336999    29022  29006.5
17423  20230806   235000    235959  1691337599  29006.5    29001
17424  20230807   000000    000959  1691338199  29001.1  28992.4
17425  20230807   001000    001959  1691338799  28992.5  29003.7
2023-08-07 00:20:09,039:INFO:pyemd2:main.py:127:handleKline:2217508: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}


## /root/FIL/strategy/similarity/log.txt ----- -----

127.0.0.1 - - [07/Aug/2023 00:00:04] "POST / HTTP/1.1" 200 -
2023-08-07 00:00:04,075:INFO:testStrategy:main.py:308:handleOrderFilled:2217133: handleOrderFilled: data=OrderType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'clientorderid': '42814F1691337603442I0L2', 'symbol': 'BTCUSDT', 'gatewayorderid': 1691337603882225, 'quantity': '37.345', 'price': '29001', 'stopprice': '0', 'ordertype': '', 'side': 'SELL', 'status': 'FILLED', 'positionside': 'SHORT', 'createtime': 1691337602573, 'updatetime': 1691337603882, 'tradetype': 'usdt', 'selfid': 42814, 'filltrades': [TradeType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'tradeid': 1691337603882, 'clientorderid': '42814F1691337603442I0L2', 'price': '29001', 'quantity': '37.345', 'commission': '1083.042345', 'commissionasset': 'USDT', 'tradetime': 1691337603882, 'tradetype': 'usdt', 'gatetype': 'simulator', 'handletime': 1691337603882}], 'gatetype': 'simulator', 'handletime': 0}
127.0.0.1 - - [07/Aug/2023 00:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=12179 

self.closeSec=1691338199, self.tradeDate='20230807', self.openTime='000000', self.closeTime='000959', self.symbol='BTCUSDT', self.open='29001.1', self.close='28992.4'
2023-08-07 00:10:01,128:INFO:testStrategy:main.py:101:handleKline:2217133: self.closeSec=1691338199, self.tradeDate='20230807', self.openTime='000000', self.closeTime='000959',self.symbol='BTCUSDT',self.open='29001.1', self.close='28992.4'
2023-08-07 00:10:01,137:INFO:testStrategy:main.py:102:handleKline:2217133: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12236  20230806   232000    232959  1691335799  29028.7  29027.3
12237  20230806   233000    233959  1691336399  29027.4    29022
12238  20230806   234000    234959  1691336999    29022  29006.5
12239  20230806   235000    235959  1691337599  29006.5    29001
12240  20230807   000000    000959  1691338199  29001.1  28992.4
2023-08-07 00:10:01,137:INFO:testStrategy:main.py:103:handleKline:2217133: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False, 'isCorr': False}

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=12180 

self.closeSec=1691338799, self.tradeDate='20230807', self.openTime='001000', self.closeTime='001959', self.symbol='BTCUSDT', self.open='28992.5', self.close='29003.7'
127.0.0.1 - - [07/Aug/2023 00:20:04] "POST / HTTP/1.1" 200 -
2023-08-07 00:20:08,598:INFO:testStrategy:main.py:101:handleKline:2217133: self.closeSec=1691338799, self.tradeDate='20230807', self.openTime='001000', self.closeTime='001959',self.symbol='BTCUSDT',self.open='28992.5', self.close='29003.7'
2023-08-07 00:20:08,836:INFO:testStrategy:main.py:102:handleKline:2217133: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12237  20230806   233000    233959  1691336399  29027.4    29022
12238  20230806   234000    234959  1691336999    29022  29006.5
12239  20230806   235000    235959  1691337599  29006.5    29001
12240  20230807   000000    000959  1691338199  29001.1  28992.4
12241  20230807   001000    001959  1691338799  28992.5  29003.7
2023-08-07 00:20:08,845:INFO:testStrategy:main.py:103:handleKline:2217133: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False, 'isCorr': False}


## /root/FIL/strategy/sr_min/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=1, self.total=996015.990996, self.flagDict['side']='buy', self.tradeCount=1, self.count=24352
self.closeSec=1691338799, self.tradeDate='20230807', self.openTime='001500', self.closeTime='001959', self.symbol='BTCUSDT', self.open=29012.8, self.close=29003.7, self.high=29012.8, self.low=29003.6, self.vol=289.021, self.amt=8383809.8899 
127.0.0.1 - - [07/Aug/2023 00:20:01] "POST / HTTP/1.1" 200 -
2023-08-07 00:20:06,604:INFO:sr_min:main.py:172:handleKline:2219263: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5759  20230806   235500    235959  ...         0.0        0.0       0
5760  20230807   000000    000459  ...         0.0        0.0       0
5761  20230807   000500    000959  ...         0.0        0.0       0
5762  20230807   001000    001459  ...         0.0        0.0       0
5763  20230807   001500    001959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-08-07 00:20:06,635:INFO:sr_min:main.py:175:handleKline:2219263: self.closeSec=1691338799, self.tradeDate='20230807', self.openTime='001500', self.closeTime='001959',self.symbol='BTCUSDT',self.open=29012.8, self.close=29003.7, self.high=29012.8, self.low=29003.6, self.vol=289.021, self.amt=8383809.8899, ukdf['pct'].iloc[-1]=-0.000314 , ukdf['amount'].iloc[-1]=8383809.8899, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5763, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '37.141', 'enterprice': '26844', 'countrevence': '0', 'unrealprofit': '80237.34160568776', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '29004.34413736', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=1
--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=1, self.total=996015.990996, self.flagDict['side']='buy', self.tradeCount=1, self.count=24353
self.closeSec=1691339099, self.tradeDate='20230807', self.openTime='002000', self.closeTime='002459', self.symbol='BTCUSDT', self.open=29003.7, self.close=29010.5, self.high=29010.6, self.low=29003.6, self.vol=177.422, self.amt=5146440.9954 
127.0.0.1 - - [07/Aug/2023 00:25:00] "POST / HTTP/1.1" 200 -
2023-08-07 00:25:00,789:INFO:sr_min:main.py:172:handleKline:2219263: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5760  20230807   000000    000459  ...         0.0        0.0       0
5761  20230807   000500    000959  ...         0.0        0.0       0
5762  20230807   001000    001459  ...         0.0        0.0       0
5763  20230807   001500    001959  ...         0.0        0.0       0
5764  20230807   002000    002459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-08-07 00:25:00,789:INFO:sr_min:main.py:175:handleKline:2219263: self.closeSec=1691339099, self.tradeDate='20230807', self.openTime='002000', self.closeTime='002459',self.symbol='BTCUSDT',self.open=29003.7, self.close=29010.5, self.high=29010.6, self.low=29003.6, self.vol=177.422, self.amt=5146440.9954, ukdf['pct'].iloc[-1]=0.000234 , ukdf['amount'].iloc[-1]=5146440.9954, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5764, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '37.141', 'enterprice': '26844', 'countrevence': '0', 'unrealprofit': '80465.9765', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '29010.5', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=1


## /root/FIL/strategy/s_rsrs/log.txt ----- -----

721  20230806   040000    075959  ...   6586.050  1.913999e+08  0.000028
722  20230806   080000    115959  ...   8174.351  2.374513e+08 -0.000145
723  20230806   120000    155959  ...  11457.436  3.330443e+08  0.000957
724  20230806   160000    195959  ...  15861.601  4.612386e+08 -0.000492
725  20230806   200000    235959  ...  18943.151  5.497474e+08 -0.002271

[5 rows x 11 columns]
2023-08-07 00:00:02,457:INFO:s_rsrs:main.py:151:handleKline:2218689: df_s.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec  ...  index      beta    zscore  signal
721  20230806   040000    075959  1691279999  ...    721  0.826976  2.381697     1.0
722  20230806   080000    115959  1691294399  ...    722  0.845992  2.364724     1.0
723  20230806   120000    155959  1691308799  ...    723  0.439198  0.519806     NaN
724  20230806   160000    195959  1691323199  ...    724  0.256337 -0.317274     NaN
725  20230806   200000    235959  1691337599  ...    725  0.119670 -0.943544    -1.0

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '54.775', 'enterprice': '29034.8', 'countrevence': '0', 'unrealprofit': '-1794.7989821195', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '29002.03324542', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-1, self.sign=1
handlebackTrade > queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '54.775', 'enterprice': '29034.8', 'countrevence': '0', 'unrealprofit': '-1798.410520256', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '29001.96731136', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
2023-08-07 00:00:09,324:INFO:s_rsrs:main.py:182:queryContractAssets:2218689: queryContractAssets: assets=ContractAssetReturn{'result': [ContractAsset{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'asset': 'USDT', 'free': '1591691.6868615', 'total': '1591691.6868615', 'margin': '0', 'unreal': '0', 'type': 'AssetType_ucontract'}]}
2023-08-07 00:00:09,799:INFO:s_rsrs:main.py:269:openSell:2218689: ret = self.client.insertMarketUOrder("simulator", "BTCUSDT", 54.719, "sell"), ret=InsertOrderReturn{'result': 'success', 'clientorderid': '42817F1691337609797I0L65'}
2023-08-07 00:00:09,820:INFO:s_rsrs:main.py:176:insertFactor:2218689: curDateTime:8070000, name:s_rsrs, symbol:BTCUSDT, tradeDate:20230806, closeTime:235959, close:29001.0, sign:-1, total:1591691.6868615, side:sell  
127.0.0.1 - - [07/Aug/2023 00:00:09] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [07/Aug/2023 00:00:09] "POST / HTTP/1.1" 200 -
2023-08-07 00:00:09,822:INFO:s_rsrs:main.py:343:handleOrderNew:2218689: handleOrderNew: data=OrderType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'clientorderid': '42816F1691337604251I0L65', 'symbol': 'BTCUSDT', 'gatewayorderid': 1691337604643467, 'quantity': '54.775', 'price': '29001', 'stopprice': '0', 'ordertype': '', 'side': 'SELL', 'status': 'FILLED', 'positionside': 'SHORT', 'createtime': 1691337603354, 'updatetime': 1691337604643, 'tradetype': 'usdt', 'selfid': 42816, 'filltrades': [TradeType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'tradeid': 1691337604643, 'clientorderid': '42816F1691337604251I0L65', 'price': '29001', 'quantity': '54.775', 'commission': '1588.529775', 'commissionasset': 'USDT', 'tradetime': 1691337604643, 'tradetype': 'usdt', 'gatetype': 'simulator', 'handletime': 1691337604643}], 'gatetype': 'simulator', 'handletime': 0}
2023-08-07 00:00:09,825:INFO:s_rsrs:main.py:346:handleOrderFilled:2218689: handleOrderFilled: data=OrderType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'clientorderid': '42816F1691337604251I0L65', 'symbol': 'BTCUSDT', 'gatewayorderid': 1691337604643467, 'quantity': '54.775', 'price': '29001', 'stopprice': '0', 'ordertype': '', 'side': 'SELL', 'status': 'FILLED', 'positionside': 'SHORT', 'createtime': 1691337603354, 'updatetime': 1691337604643, 'tradetype': 'usdt', 'selfid': 42816, 'filltrades': [TradeType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'tradeid': 1691337604643, 'clientorderid': '42816F1691337604251I0L65', 'price': '29001', 'quantity': '54.775', 'commission': '1588.529775', 'commissionasset': 'USDT', 'tradetime': 1691337604643, 'tradetype': 'usdt', 'gatetype': 'simulator', 'handletime': 1691337604643}], 'gatetype': 'simulator', 'handletime': 0}
127.0.0.1 - - [07/Aug/2023 00:00:10] "POST / HTTP/1.1" 200 -
2023-08-07 00:00:10,283:INFO:s_rsrs:main.py:343:handleOrderNew:2218689: handleOrderNew: data=OrderType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'clientorderid': '42817F1691337609797I0L65', 'symbol': 'BTCUSDT', 'gatewayorderid': 1691337610222298, 'quantity': '54.719', 'price': '28996.8', 'stopprice': '0', 'ordertype': '', 'side': 'SELL', 'status': 'FILLED', 'positionside': 'SHORT', 'createtime': 1691337609339, 'updatetime': 1691337610222, 'tradetype': 'usdt', 'selfid': 42817, 'filltrades': [TradeType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'tradeid': 1691337610222, 'clientorderid': '42817F1691337609797I0L65', 'price': '28996.8', 'quantity': '54.719', 'commission': '1586.6758992', 'commissionasset': 'USDT', 'tradetime': 1691337610222, 'tradetype': 'usdt', 'gatetype': 'simulator', 'handletime': 1691337610222}], 'gatetype': 'simulator', 'handletime': 0}
2023-08-07 00:00:10,435:INFO:s_rsrs:main.py:346:handleOrderFilled:2218689: handleOrderFilled: data=OrderType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'clientorderid': '42817F1691337609797I0L65', 'symbol': 'BTCUSDT', 'gatewayorderid': 1691337610222298, 'quantity': '54.719', 'price': '28996.8', 'stopprice': '0', 'ordertype': '', 'side': 'SELL', 'status': 'FILLED', 'positionside': 'SHORT', 'createtime': 1691337609339, 'updatetime': 1691337610222, 'tradetype': 'usdt', 'selfid': 42817, 'filltrades': [TradeType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'tradeid': 1691337610222, 'clientorderid': '42817F1691337609797I0L65', 'price': '28996.8', 'quantity': '54.719', 'commission': '1586.6758992', 'commissionasset': 'USDT', 'tradetime': 1691337610222, 'tradetype': 'usdt', 'gatetype': 'simulator', 'handletime': 1691337610222}], 'gatetype': 'simulator', 'handletime': 0}
127.0.0.1 - - [07/Aug/2023 00:00:10] "POST / HTTP/1.1" 200 -


