# 20230802 00:26:02

## /root/FIL/strategy/amihud/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=373746.4768026, self.flagDict['side']='sell', self.tradeCount=2, self.count=22912
self.closeSec=1690906799, self.tradeDate='20230802', self.openTime='001500', self.closeTime='001959', self.symbol='BTCUSDT', self.open=29001.8, self.close=28951.8, self.high=29014.8, self.low=28951.8, self.vol=2377.534, self.amt=68906624.0791 
127.0.0.1 - - [02/Aug/2023 00:20:01] "POST / HTTP/1.1" 200 -
2023-08-02 00:20:05,856:INFO:amihud:main.py:172:handleKline:2219019: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5759  20230801   235500    235959  ...         0.0        0.0       0
5760  20230802   000000    000459  ...         0.0        0.0       0
5761  20230802   000500    000959  ...         0.0        0.0       0
5762  20230802   001000    001459  ...         0.0        0.0       0
5763  20230802   001500    001959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-08-02 00:20:05,885:INFO:amihud:main.py:175:handleKline:2219019: self.closeSec=1690906799, self.tradeDate='20230802', self.openTime='001500', self.closeTime='001959',self.symbol='BTCUSDT',self.open=29001.8, self.close=28951.8, self.high=29014.8, self.low=28951.8, self.vol=2377.534, self.amt=68906624.0791, ukdf['pct'].iloc[-1]=-0.001721 , ukdf['amount'].iloc[-1]=68906624.0791, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5763, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '13.926', 'enterprice': '26864.9', 'countrevence': '0', 'unrealprofit': '-29082.64347315888', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '28953.27020488', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1
127.0.0.1 - - [02/Aug/2023 00:25:00] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=373746.4768026, self.flagDict['side']='sell', self.tradeCount=2, self.count=22913
self.closeSec=1690907099, self.tradeDate='20230802', self.openTime='002000', self.closeTime='002459', self.symbol='BTCUSDT', self.open=28951.9, self.close=28939.8, self.high=28952.0, self.low=28926.4, self.vol=1644.005, self.amt=47575923.9674 
2023-08-02 00:25:00,761:INFO:amihud:main.py:172:handleKline:2219019: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5760  20230802   000000    000459  ...         0.0        0.0       0
5761  20230802   000500    000959  ...         0.0        0.0       0
5762  20230802   001000    001459  ...         0.0        0.0       0
5763  20230802   001500    001959  ...         0.0        0.0       0
5764  20230802   002000    002459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-08-02 00:25:00,762:INFO:amihud:main.py:175:handleKline:2219019: self.closeSec=1690907099, self.tradeDate='20230802', self.openTime='002000', self.closeTime='002459',self.symbol='BTCUSDT',self.open=28951.9, self.close=28939.8, self.high=28952.0, self.low=28926.4, self.vol=1644.005, self.amt=47575923.9674, ukdf['pct'].iloc[-1]=-0.000414 , ukdf['amount'].iloc[-1]=47575923.9674, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5764, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '13.926', 'enterprice': '26864.9', 'countrevence': '0', 'unrealprofit': '-28895.0574', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '28939.8', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1


## /root/FIL/strategy/factorcheck/log.txt ----- -----


self.closeSec=1690906799, self.tradeDate='20230802', self.openTime='001500', self.closeTime='001959', self.symbol='BTCUSDT', self.open=29001.8, self.close=28951.8, self.high=29014.8, self.low=28951.8 
127.0.0.1 - - [02/Aug/2023 00:20:01] "POST / HTTP/1.1" 200 -
2023-08-02 00:20:03,646:INFO:factorcheck2:main.py:126:handleKline:2218005: self.closeSec=1690906799, self.tradeDate='20230802', self.openTime='001500', self.closeTime='001959',self.symbol='BTCUSDT',self.open=29001.8, self.close=28951.8, self.high=29014.8, self.low=28951.8   
2023-08-02 00:20:04,895:INFO:factorcheck2:main.py:127:handleKline:2218005: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1439  20230801   235500    235959  1690905599  ...  28902.0  0.001273   1727    5
1440  20230802   000000    000459  1690905899  ...  28902.1  0.000193   1440    0
1441  20230802   000500    000959  1690906199  ...  28943.4  0.002079   1441    1
1442  20230802   001000    001459  1690906499  ...  28964.0 -0.000283   1442    2
1443  20230802   001500    001959  1690906799  ...  28951.8 -0.001721   1443    3

[5 rows x 11 columns]
2023-08-02 00:20:04,905:INFO:factorcheck2:main.py:128:handleKline:2218005: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': False, 'isOpen': True, 'isClose': False, 'isTrig': True}

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.688701010163438, self.count=22915 

self.closeSec=1690907099, self.tradeDate='20230802', self.openTime='002000', self.closeTime='002459', self.symbol='BTCUSDT', self.open=28951.9, self.close=28939.8, self.high=28952.0, self.low=28926.4 
127.0.0.1 - - [02/Aug/2023 00:25:00] "POST / HTTP/1.1" 200 -
2023-08-02 00:25:00,765:INFO:factorcheck2:main.py:126:handleKline:2218005: self.closeSec=1690907099, self.tradeDate='20230802', self.openTime='002000', self.closeTime='002459',self.symbol='BTCUSDT',self.open=28951.9, self.close=28939.8, self.high=28952.0, self.low=28926.4   
2023-08-02 00:25:00,789:INFO:factorcheck2:main.py:127:handleKline:2218005: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1440  20230802   000000    000459  1690905899  ...  28902.1  0.000193   1440    0
1441  20230802   000500    000959  1690906199  ...  28943.4  0.002079   1441    1
1442  20230802   001000    001459  1690906499  ...  28964.0 -0.000283   1442    2
1443  20230802   001500    001959  1690906799  ...  28951.8 -0.001721   1443    3
1444  20230802   002000    002459  1690907099  ...  28926.4 -0.000414   1444    4

[5 rows x 11 columns]
2023-08-02 00:25:00,789:INFO:factorcheck2:main.py:128:handleKline:2218005: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': False, 'isOpen': True, 'isClose': False, 'isTrig': True}


## /root/FIL/strategy/logic/log.txt ----- -----

2023-08-02 00:00:17,079:DEBUG:logic:main.py:463:getModel:2218526: df_s.iloc[-5:,:] :
          date closeTime     open  ...    alpha58   alpha67   alpha72
5802  20230801    212959  28867.9  ...  44.583333  0.420406  0.687176
5803  20230801    215959  28898.3  ...  44.583333  0.409513  0.690429
5804  20230801    222959  28857.0  ...  44.583333  0.407816  0.694130
5805  20230801    225959  28850.4  ...  44.583333  0.398965  0.701067
5806  20230801    232959  28816.4  ...  44.583333  0.387686  0.712119

[5 rows x 33 columns]
0.5790441176470589
acc is : 0.5790441176470589
2023-08-02 00:00:17,138:INFO:logic:main.py:468:getModel:2218526: df_pred.iloc[-5:,:] :
     pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
539     0  0.505400  0.494600       0  ...  0.932900  -1.0    0.0  0.969729
540     1  0.488800  0.511200       0  ...  0.933110  -1.0    0.0  0.969511
541     1  0.497591  0.502409       0  ...  0.934213  -1.0    0.0  0.968365
542     1  0.492656  0.507344       0  ...  0.935666  -1.0    0.0  0.966859
543     1  0.482257  0.517743       1  ...  0.930079  -1.0    0.0  0.972632

[5 rows x 10 columns]
2023-08-02 00:00:17,149:INFO:logic:main.py:478:getModel:2218526: df_panel.iloc[-5:,:] :
    pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
45     0  0.505300  0.494700       0  ...  0.932900  -1.0    0.0  0.967310
46     1  0.488501  0.511499       0  ...  0.933110  -1.0    0.0  0.966872
47     1  0.497438  0.502562       0  ...  0.934213  -1.0    0.0  0.965729
48     1  0.492548  0.507452       0  ...  0.935666  -1.0    0.0  0.965795
49     1  0.482257  0.517743       1  ...  0.930079  -1.0    0.0  0.972632

[5 rows x 10 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '23.804', 'enterprice': '28908.8', 'countrevence': '0', 'unrealprofit': '-951.6200502974', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '28948.77731685', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}


## /root/FIL/strategy/modifiedmom/log.txt ----- -----

127.0.0.1 - - [02/Aug/2023 00:00:04] "POST / HTTP/1.1" 200 -
2023-08-02 00:00:04,084:INFO:modifiedmom:main.py:319:handleOrderFilled:2218259: handleOrderFilled: data=OrderType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'clientorderid': '42779F1690905603462I0L59', 'symbol': 'BTCUSDT', 'gatewayorderid': 1690905603894111, 'quantity': '25.615', 'price': '28943', 'stopprice': '0', 'ordertype': '', 'side': 'BUY', 'status': 'FILLED', 'positionside': 'LONG', 'createtime': 1690905602606, 'updatetime': 1690905603894, 'tradetype': 'usdt', 'selfid': 42779, 'filltrades': [TradeType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'tradeid': 1690905603894, 'clientorderid': '42779F1690905603462I0L59', 'price': '28943', 'quantity': '25.615', 'commission': '741.374945', 'commissionasset': 'USDT', 'tradetime': 1690905603894, 'tradetype': 'usdt', 'gatetype': 'simulator', 'handletime': 1690905603894}], 'gatetype': 'simulator', 'handletime': 0}
127.0.0.1 - - [02/Aug/2023 00:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=11456 

self.closeSec=1690906199, self.tradeDate='20230802', self.openTime='000000', self.closeTime='000959', self.symbol='BTCUSDT', self.open='28943', self.close='29009.9'
2023-08-02 00:10:01,121:INFO:modifiedmom:main.py:144:handleKline:2218259: self.closeSec=1690906199, self.tradeDate='20230802', self.openTime='000000', self.closeTime='000959',self.symbol='BTCUSDT',self.open='28943', self.close='29009.9'
2023-08-02 00:10:01,136:INFO:modifiedmom:main.py:145:handleKline:2218259: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
572  20230801   232000    232959  1690903799  28790.1  28771.6 -0.000643
573  20230801   233000    233959  1690904399    28770  28824.1  0.001825
574  20230801   234000    234959  1690904999  28822.6  28881.5  0.001991
575  20230801   235000    235959  1690905599    28880  28942.9  0.002126
576  20230802   000000    000959  1690906199    28943  29009.9  0.002315
2023-08-02 00:10:01,136:INFO:modifiedmom:main.py:146:handleKline:2218259: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=11457 

self.closeSec=1690906799, self.tradeDate='20230802', self.openTime='001000', self.closeTime='001959', self.symbol='BTCUSDT', self.open='29009.1', self.close='28951.8'
127.0.0.1 - - [02/Aug/2023 00:20:04] "POST / HTTP/1.1" 200 -
2023-08-02 00:20:06,385:INFO:modifiedmom:main.py:144:handleKline:2218259: self.closeSec=1690906799, self.tradeDate='20230802', self.openTime='001000', self.closeTime='001959',self.symbol='BTCUSDT',self.open='29009.1', self.close='28951.8'
2023-08-02 00:20:06,776:INFO:modifiedmom:main.py:145:handleKline:2218259: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
573  20230801   233000    233959  1690904399    28770  28824.1  0.001825
574  20230801   234000    234959  1690904999  28822.6  28881.5  0.001991
575  20230801   235000    235959  1690905599    28880  28942.9  0.002126
576  20230802   000000    000959  1690906199    28943  29009.9  0.002315
577  20230802   001000    001959  1690906799  29009.1  28951.8 -0.002003
2023-08-02 00:20:06,784:INFO:modifiedmom:main.py:146:handleKline:2218259: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False}


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

2023-08-02 00:00:02,105:INFO:pyemd2:main.py:127:handleKline:2217508: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}
2023-08-02 00:00:02,164:INFO:pyemd2:main.py:190:insertFactor:2217508: curDateTime:8020000, name:pyemd2, symbol:BTCUSDT, tradeDate:20230801, closeTime:235959, close:28942.9, total:996515.1559743, pct_pre:-0.0101155673618053, thd:-0.3442550268828279, side:sell 
127.0.0.1 - - [02/Aug/2023 00:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=11459 

self.closeSec=1690906199, self.tradeDate='20230802', self.openTime='000000', self.closeTime='000959', self.symbol='BTCUSDT', self.open='28943', self.close='29009.9'
2023-08-02 00:10:01,113:INFO:pyemd2:main.py:125:handleKline:2217508: self.closeSec=1690906199, self.tradeDate='20230802', self.openTime='000000', self.closeTime='000959',self.symbol='BTCUSDT',self.open='28943', self.close='29009.9'
2023-08-02 00:10:01,122:INFO:pyemd2:main.py:126:handleKline:2217508: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17420  20230801   232000    232959  1690903799  28790.1  28771.6
17421  20230801   233000    233959  1690904399    28770  28824.1
17422  20230801   234000    234959  1690904999  28822.6  28881.5
17423  20230801   235000    235959  1690905599    28880  28942.9
17424  20230802   000000    000959  1690906199    28943  29009.9
2023-08-02 00:10:01,122:INFO:pyemd2:main.py:127:handleKline:2217508: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=11460 

self.closeSec=1690906799, self.tradeDate='20230802', self.openTime='001000', self.closeTime='001959', self.symbol='BTCUSDT', self.open='29009.1', self.close='28951.8'
127.0.0.1 - - [02/Aug/2023 00:20:04] "POST / HTTP/1.1" 200 -
2023-08-02 00:20:07,540:INFO:pyemd2:main.py:125:handleKline:2217508: self.closeSec=1690906799, self.tradeDate='20230802', self.openTime='001000', self.closeTime='001959',self.symbol='BTCUSDT',self.open='29009.1', self.close='28951.8'
2023-08-02 00:20:07,642:INFO:pyemd2:main.py:126:handleKline:2217508: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17421  20230801   233000    233959  1690904399    28770  28824.1
17422  20230801   234000    234959  1690904999  28822.6  28881.5
17423  20230801   235000    235959  1690905599    28880  28942.9
17424  20230802   000000    000959  1690906199    28943  29009.9
17425  20230802   001000    001959  1690906799  29009.1  28951.8
2023-08-02 00:20:07,642:INFO:pyemd2:main.py:127:handleKline:2217508: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}


## /root/FIL/strategy/similarity/log.txt ----- -----

127.0.0.1 - - [02/Aug/2023 00:00:04] "POST / HTTP/1.1" 200 -
2023-08-02 00:00:04,207:INFO:testStrategy:main.py:308:handleOrderFilled:2217133: handleOrderFilled: data=OrderType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'clientorderid': '42780F1690905603538I0L2', 'symbol': 'BTCUSDT', 'gatewayorderid': 1690905603953135, 'quantity': '37.017', 'price': '28943', 'stopprice': '0', 'ordertype': '', 'side': 'BUY', 'status': 'FILLED', 'positionside': 'LONG', 'createtime': 1690905602662, 'updatetime': 1690905603953, 'tradetype': 'usdt', 'selfid': 42780, 'filltrades': [TradeType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'tradeid': 1690905603953, 'clientorderid': '42780F1690905603538I0L2', 'price': '28943', 'quantity': '37.017', 'commission': '1071.383031', 'commissionasset': 'USDT', 'tradetime': 1690905603953, 'tradetype': 'usdt', 'gatetype': 'simulator', 'handletime': 1690905603953}], 'gatetype': 'simulator', 'handletime': 0}
127.0.0.1 - - [02/Aug/2023 00:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=11459 

self.closeSec=1690906199, self.tradeDate='20230802', self.openTime='000000', self.closeTime='000959', self.symbol='BTCUSDT', self.open='28943', self.close='29009.9'
2023-08-02 00:10:01,112:INFO:testStrategy:main.py:101:handleKline:2217133: self.closeSec=1690906199, self.tradeDate='20230802', self.openTime='000000', self.closeTime='000959',self.symbol='BTCUSDT',self.open='28943', self.close='29009.9'
2023-08-02 00:10:01,133:INFO:testStrategy:main.py:102:handleKline:2217133: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12236  20230801   232000    232959  1690903799  28790.1  28771.6
12237  20230801   233000    233959  1690904399    28770  28824.1
12238  20230801   234000    234959  1690904999  28822.6  28881.5
12239  20230801   235000    235959  1690905599    28880  28942.9
12240  20230802   000000    000959  1690906199    28943  29009.9
2023-08-02 00:10:01,133:INFO:testStrategy:main.py:103:handleKline:2217133: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False, 'isCorr': False}

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=11460 

self.closeSec=1690906799, self.tradeDate='20230802', self.openTime='001000', self.closeTime='001959', self.symbol='BTCUSDT', self.open='29009.1', self.close='28951.8'
127.0.0.1 - - [02/Aug/2023 00:20:04] "POST / HTTP/1.1" 200 -
2023-08-02 00:20:07,398:INFO:testStrategy:main.py:101:handleKline:2217133: self.closeSec=1690906799, self.tradeDate='20230802', self.openTime='001000', self.closeTime='001959',self.symbol='BTCUSDT',self.open='29009.1', self.close='28951.8'
2023-08-02 00:20:07,565:INFO:testStrategy:main.py:102:handleKline:2217133: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12237  20230801   233000    233959  1690904399    28770  28824.1
12238  20230801   234000    234959  1690904999  28822.6  28881.5
12239  20230801   235000    235959  1690905599    28880  28942.9
12240  20230802   000000    000959  1690906199    28943  29009.9
12241  20230802   001000    001959  1690906799  29009.1  28951.8
2023-08-02 00:20:07,566:INFO:testStrategy:main.py:103:handleKline:2217133: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False, 'isCorr': False}


## /root/FIL/strategy/sr_min/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=1, self.total=996015.990996, self.flagDict['side']='buy', self.tradeCount=1, self.count=22912
self.closeSec=1690906799, self.tradeDate='20230802', self.openTime='001500', self.closeTime='001959', self.symbol='BTCUSDT', self.open=29001.8, self.close=28951.8, self.high=29014.8, self.low=28951.8, self.vol=2377.534, self.amt=68906624.0791 
127.0.0.1 - - [02/Aug/2023 00:20:01] "POST / HTTP/1.1" 200 -
2023-08-02 00:20:05,846:INFO:sr_min:main.py:172:handleKline:2219263: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5759  20230801   235500    235959  ...         0.0        0.0       0
5760  20230802   000000    000459  ...         0.0        0.0       0
5761  20230802   000500    000959  ...         0.0        0.0       0
5762  20230802   001000    001459  ...         0.0        0.0       0
5763  20230802   001500    001959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-08-02 00:20:05,885:INFO:sr_min:main.py:175:handleKline:2219263: self.closeSec=1690906799, self.tradeDate='20230802', self.openTime='001500', self.closeTime='001959',self.symbol='BTCUSDT',self.open=29001.8, self.close=28951.8, self.high=29014.8, self.low=28951.8, self.vol=2377.534, self.amt=68906624.0791, ukdf['pct'].iloc[-1]=-0.001721 , ukdf['amount'].iloc[-1]=68906624.0791, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5763, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '37.141', 'enterprice': '26844', 'countrevence': '0', 'unrealprofit': '78330.89391338159', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '28953.01413299', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=1
--handleKline--: 127.0.0.1 - - [02/Aug/2023 00:25:00] "POST / HTTP/1.1" 200 -
 version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=1, self.total=996015.990996, self.flagDict['side']='buy', self.tradeCount=1, self.count=22913
self.closeSec=1690907099, self.tradeDate='20230802', self.openTime='002000', self.closeTime='002459', self.symbol='BTCUSDT', self.open=28951.9, self.close=28939.8, self.high=28952.0, self.low=28926.4, self.vol=1644.005, self.amt=47575923.9674 
2023-08-02 00:25:00,817:INFO:sr_min:main.py:172:handleKline:2219263: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5760  20230802   000000    000459  ...         0.0        0.0       0
5761  20230802   000500    000959  ...         0.0        0.0       0
5762  20230802   001000    001459  ...         0.0        0.0       0
5763  20230802   001500    001959  ...         0.0        0.0       0
5764  20230802   002000    002459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-08-02 00:25:00,817:INFO:sr_min:main.py:175:handleKline:2219263: self.closeSec=1690907099, self.tradeDate='20230802', self.openTime='002000', self.closeTime='002459',self.symbol='BTCUSDT',self.open=28951.9, self.close=28939.8, self.high=28952.0, self.low=28926.4, self.vol=1644.005, self.amt=47575923.9674, ukdf['pct'].iloc[-1]=-0.000414 , ukdf['amount'].iloc[-1]=47575923.9674, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5764, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '37.141', 'enterprice': '26844', 'countrevence': '0', 'unrealprofit': '77840.1078', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '28939.8', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=1


## /root/FIL/strategy/s_rsrs/log.txt ----- -----

723  20230801   120000    155959  1690876799  ...    723  0.056256 -0.989586    -1.0
724  20230801   160000    195959  1690891199  ...    724  0.111456 -0.720589    -1.0

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '54.024', 'enterprice': '29248', 'countrevence': '0', 'unrealprofit': '21182.8104', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '28855.9', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-1, self.sign=-1
127.0.0.1 - - [02/Aug/2023 00:00:01] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='s_rsrs', self.symbol='BTCUSDT', interval='4h', intervalSec=14400, wid=25, thd=0.6, self.sign=-1, self.total=1578513.8580480001, self.flagDict['side']='sell', self.tradeCount=16, self.count=477
self.closeSec=1690905599, self.tradeDate='20230801', self.openTime='200000', self.closeTime='235959', self.symbol='BTCUSDT', self.open=28852.9, self.close=28943.4, self.high=28973.6, self.low=28550.0, self.vol=92928.505, self.amt=2677331544.91106 
2023-08-02 00:00:01,682:INFO:s_rsrs:main.py:141:handleKline:2218689: self.closeSec=1690905599, self.tradeDate='20230801', self.openTime='200000', self.closeTime='235959',self.symbol='BTCUSDT',self.open=28852.9, self.close=28943.4, self.high=28973.6, self.low=28550.0, self.vol=92928.505, self.amt=2677331544.91106 
2023-08-02 00:00:01,695:INFO:s_rsrs:main.py:142:handleKline:2218689: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime  ...        vol           amt       pct
721  20230801   040000    075959  ...  32949.344  9.621005e+08  0.002590
722  20230801   080000    115959  ...  88466.386  2.563316e+09 -0.013716
723  20230801   120000    155959  ...  38804.577  1.120812e+09  0.003511
724  20230801   160000    195959  ...  26312.292  7.608170e+08 -0.002358
725  20230801   200000    235959  ...  92928.505  2.677332e+09  0.003133

[5 rows x 11 columns]
2023-08-02 00:00:02,445:INFO:s_rsrs:main.py:151:handleKline:2218689: df_s.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec  ...  index      beta    zscore  signal
721  20230801   040000    075959  1690847999  ...    721  0.062756 -0.996077    -1.0
722  20230801   080000    115959  1690862399  ...    722  0.004820 -1.235378    -1.0
723  20230801   120000    155959  1690876799  ...    723  0.056256 -0.989586    -1.0
724  20230801   160000    195959  1690891199  ...    724  0.111456 -0.720589    -1.0
725  20230801   200000    235959  1690905599  ...    725  0.160942 -0.470313     NaN

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '54.024', 'enterprice': '29248', 'countrevence': '0', 'unrealprofit': '16470.67940179416', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '28943.12291941', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-9223372036854775808, self.sign=-1


