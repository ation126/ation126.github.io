# 20230709 00:26:01

## /root/FIL/strategy/amihud/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=373746.4768026, self.flagDict['side']='sell', self.tradeCount=2, self.count=16000
self.closeSec=1688833199, self.tradeDate='20230709', self.openTime='001500', self.closeTime='001959', self.symbol='BTCUSDT', self.open=30218.0, self.close=30232.2, self.high=30239.8, self.low=30217.9, self.vol=654.573, self.amt=19789055.9149 
127.0.0.1 - - [09/Jul/2023 00:20:01] "POST / HTTP/1.1" 200 -
2023-07-09 00:20:07,237:INFO:amihud:main.py:172:handleKline:2219019: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5759  20230708   235500    235959  ...         0.0        0.0       0
5760  20230709   000000    000459  ...         0.0        0.0       0
5761  20230709   000500    000959  ...         0.0        0.0       0
5762  20230709   001000    001459  ...         0.0        0.0       0
5763  20230709   001500    001959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-07-09 00:20:07,268:INFO:amihud:main.py:175:handleKline:2219019: self.closeSec=1688833199, self.tradeDate='20230709', self.openTime='001500', self.closeTime='001959',self.symbol='BTCUSDT',self.open=30218.0, self.close=30232.2, self.high=30239.8, self.low=30217.9, self.vol=654.573, self.amt=19789055.9149, ukdf['pct'].iloc[-1]=0.00047 , ukdf['amount'].iloc[-1]=19789055.9149, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5763, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '13.926', 'enterprice': '26864.9', 'countrevence': '0', 'unrealprofit': '-46922.05691276598', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '30234.28510073', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1
127.0.0.1 - - [09/Jul/2023 00:25:00] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=373746.4768026, self.flagDict['side']='sell', self.tradeCount=2, self.count=16001
self.closeSec=1688833499, self.tradeDate='20230709', self.openTime='002000', self.closeTime='002459', self.symbol='BTCUSDT', self.open=30232.2, self.close=30216.1, self.high=30232.2, self.low=30215.3, self.vol=343.973, self.amt=10396379.7186 
2023-07-09 00:25:00,764:INFO:amihud:main.py:172:handleKline:2219019: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5760  20230709   000000    000459  ...         0.0        0.0       0
5761  20230709   000500    000959  ...         0.0        0.0       0
5762  20230709   001000    001459  ...         0.0        0.0       0
5763  20230709   001500    001959  ...         0.0        0.0       0
5764  20230709   002000    002459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-07-09 00:25:00,765:INFO:amihud:main.py:175:handleKline:2219019: self.closeSec=1688833499, self.tradeDate='20230709', self.openTime='002000', self.closeTime='002459',self.symbol='BTCUSDT',self.open=30232.2, self.close=30216.1, self.high=30232.2, self.low=30215.3, self.vol=343.973, self.amt=10396379.7186, ukdf['pct'].iloc[-1]=-0.000533 , ukdf['amount'].iloc[-1]=10396379.7186, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5764, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '13.926', 'enterprice': '26864.9', 'countrevence': '0', 'unrealprofit': '-46687.49486735994', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '30217.44163919', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1


## /root/FIL/strategy/factorcheck/log.txt ----- -----


self.closeSec=1688833199, self.tradeDate='20230709', self.openTime='001500', self.closeTime='001959', self.symbol='BTCUSDT', self.open=30218.0, self.close=30232.2, self.high=30239.8, self.low=30217.9 
127.0.0.1 - - [09/Jul/2023 00:20:01] "POST / HTTP/1.1" 200 -
2023-07-09 00:20:05,028:INFO:factorcheck2:main.py:126:handleKline:2218005: self.closeSec=1688833199, self.tradeDate='20230709', self.openTime='001500', self.closeTime='001959',self.symbol='BTCUSDT',self.open=30218.0, self.close=30232.2, self.high=30239.8, self.low=30217.9   
2023-07-09 00:20:06,528:INFO:factorcheck2:main.py:127:handleKline:2218005: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1439  20230708   235500    235959  1688831999  ...  30192.6  0.000132   1727    5
1440  20230709   000000    000459  1688832299  ...  30196.7  0.001070   1440    0
1441  20230709   000500    000959  1688832599  ...  30212.4 -0.000539   1441    1
1442  20230709   001000    001459  1688832899  ...  30212.7  0.000175   1442    2
1443  20230709   001500    001959  1688833199  ...  30217.9  0.000470   1443    3

[5 rows x 11 columns]
2023-07-09 00:20:06,537:INFO:factorcheck2:main.py:128:handleKline:2218005: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': False, 'isOpen': True, 'isClose': False, 'isTrig': True}

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=48, self.factor=0.5516738773334022, self.count=16003 

self.closeSec=1688833499, self.tradeDate='20230709', self.openTime='002000', self.closeTime='002459', self.symbol='BTCUSDT', self.open=30232.2, self.close=30216.1, self.high=30232.2, self.low=30215.3 
127.0.0.1 - - [09/Jul/2023 00:25:00] "POST / HTTP/1.1" 200 -
2023-07-09 00:25:00,746:INFO:factorcheck2:main.py:126:handleKline:2218005: self.closeSec=1688833499, self.tradeDate='20230709', self.openTime='002000', self.closeTime='002459',self.symbol='BTCUSDT',self.open=30232.2, self.close=30216.1, self.high=30232.2, self.low=30215.3   
2023-07-09 00:25:00,781:INFO:factorcheck2:main.py:127:handleKline:2218005: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1440  20230709   000000    000459  1688832299  ...  30196.7  0.001070   1440    0
1441  20230709   000500    000959  1688832599  ...  30212.4 -0.000539   1441    1
1442  20230709   001000    001459  1688832899  ...  30212.7  0.000175   1442    2
1443  20230709   001500    001959  1688833199  ...  30217.9  0.000470   1443    3
1444  20230709   002000    002459  1688833499  ...  30215.3 -0.000533   1444    4

[5 rows x 11 columns]
2023-07-09 00:25:00,783:INFO:factorcheck2:main.py:128:handleKline:2218005: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': False, 'isOpen': True, 'isClose': False, 'isTrig': True}


## /root/FIL/strategy/logic/log.txt ----- -----

2023-07-09 00:00:19,725:DEBUG:logic:main.py:463:getModel:2218526: df_s.iloc[-5:,:] :
          date closeTime     open  ...    alpha58   alpha67   alpha72
5802  20230708    212959  30154.7  ...  46.250000  0.479503  0.549163
5803  20230708    215959  30205.8  ...  45.833333  0.476154  0.557338
5804  20230708    222959  30191.9  ...  45.833333  0.479012  0.562420
5805  20230708    225959  30202.7  ...  45.416667  0.476582  0.572926
5806  20230708    232959  30192.8  ...  45.416667  0.478263  0.581527

[5 rows x 33 columns]
0.5551470588235294
acc is : 0.5551470588235294
2023-07-09 00:00:19,832:INFO:logic:main.py:468:getModel:2218526: df_pred.iloc[-5:,:] :
     pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
539     0  0.526607  0.473393       0  ...  0.966670   1.0    0.0  0.993008
540     0  0.516704  0.483296       1  ...  0.967012   1.0    0.0  0.993360
541     0  0.522520  0.477480       0  ...  0.966699   1.0    0.0  0.993037
542     0  0.517390  0.482610       1  ...  0.966894   1.0    0.0  0.993238
543     0  0.521063  0.478937       0  ...  0.966824   1.0    0.0  0.993165

[5 rows x 10 columns]
2023-07-09 00:00:19,855:INFO:logic:main.py:478:getModel:2218526: df_panel.iloc[-5:,:] :
    pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
45     0  0.528298  0.471702       0  ...  0.984076   1.0    0.0  0.998327
46     0  0.518174  0.481826       1  ...  0.984424   1.0    0.0  0.996486
47     0  0.523749  0.476251       0  ...  0.984105   1.0    0.0  0.996163
48     0  0.517999  0.482001       1  ...  0.971458   1.0    0.0  0.995481
49     0  0.521063  0.478937       0  ...  0.966824   1.0    0.0  0.993165

[5 rows x 10 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '24.764', 'enterprice': '30087.2', 'countrevence': '0', 'unrealprofit': '2711.658', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '30196.7', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}


## /root/FIL/strategy/modifiedmom/log.txt ----- -----

127.0.0.1 - - [09/Jul/2023 00:00:04] "POST / HTTP/1.1" 200 -
2023-07-09 00:00:04,461:INFO:modifiedmom:main.py:319:handleOrderFilled:2218259: handleOrderFilled: data=OrderType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'clientorderid': '42558F1688832003692I0L59', 'symbol': 'BTCUSDT', 'gatewayorderid': 1688832004090526, 'quantity': '25.19', 'price': '30196.8', 'stopprice': '0', 'ordertype': '', 'side': 'BUY', 'status': 'FILLED', 'positionside': 'LONG', 'createtime': 1688832002730, 'updatetime': 1688832004090, 'tradetype': 'usdt', 'selfid': 42558, 'filltrades': [TradeType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'tradeid': 1688832004090, 'clientorderid': '42558F1688832003692I0L59', 'price': '30196.8', 'quantity': '25.19', 'commission': '760.657392', 'commissionasset': 'USDT', 'tradetime': 1688832004090, 'tradetype': 'usdt', 'gatetype': 'simulator', 'handletime': 1688832004090}], 'gatetype': 'simulator', 'handletime': 0}

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=8000 

self.closeSec=1688832599, self.tradeDate='20230709', self.openTime='000000', self.closeTime='000959', self.symbol='BTCUSDT', self.open='30196.8', self.close='30212.7'
127.0.0.1 - - [09/Jul/2023 00:10:01] "POST / HTTP/1.1" 200 -
2023-07-09 00:10:01,158:INFO:modifiedmom:main.py:144:handleKline:2218259: self.closeSec=1688832599, self.tradeDate='20230709', self.openTime='000000', self.closeTime='000959',self.symbol='BTCUSDT',self.open='30196.8', self.close='30212.7'
2023-07-09 00:10:01,194:INFO:modifiedmom:main.py:145:handleKline:2218259: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
572  20230708   232000    232959  1688830199  30186.5  30198.9  0.000411
573  20230708   233000    233959  1688830799  30198.8  30205.3  0.000212
574  20230708   234000    234959  1688831399  30205.3  30200.3 -0.000166
575  20230708   235000    235959  1688831999  30200.3  30196.7 -0.000119
576  20230709   000000    000959  1688832599  30196.8  30212.7  0.000530
2023-07-09 00:10:01,194:INFO:modifiedmom:main.py:146:handleKline:2218259: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=8001 

self.closeSec=1688833199, self.tradeDate='20230709', self.openTime='001000', self.closeTime='001959', self.symbol='BTCUSDT', self.open='30212.8', self.close='30232.1'
127.0.0.1 - - [09/Jul/2023 00:20:04] "POST / HTTP/1.1" 200 -
2023-07-09 00:20:07,138:INFO:modifiedmom:main.py:144:handleKline:2218259: self.closeSec=1688833199, self.tradeDate='20230709', self.openTime='001000', self.closeTime='001959',self.symbol='BTCUSDT',self.open='30212.8', self.close='30232.1'
2023-07-09 00:20:07,898:INFO:modifiedmom:main.py:145:handleKline:2218259: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
573  20230708   233000    233959  1688830799  30198.8  30205.3  0.000212
574  20230708   234000    234959  1688831399  30205.3  30200.3 -0.000166
575  20230708   235000    235959  1688831999  30200.3  30196.7 -0.000119
576  20230709   000000    000959  1688832599  30196.8  30212.7  0.000530
577  20230709   001000    001959  1688833199  30212.8  30232.1  0.000642
2023-07-09 00:20:07,908:INFO:modifiedmom:main.py:146:handleKline:2218259: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False}


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

2023-07-09 00:00:02,173:INFO:pyemd2:main.py:127:handleKline:2217508: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}
2023-07-09 00:00:02,277:INFO:pyemd2:main.py:190:insertFactor:2217508: curDateTime:7090000, name:pyemd2, symbol:BTCUSDT, tradeDate:20230708, closeTime:235959, close:30196.7, total:993267.8008712, pct_pre:-0.004048102925240271, thd:0.37205485755706813, side:sell 
127.0.0.1 - - [09/Jul/2023 00:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=8003 

self.closeSec=1688832599, self.tradeDate='20230709', self.openTime='000000', self.closeTime='000959', self.symbol='BTCUSDT', self.open='30196.8', self.close='30212.7'
2023-07-09 00:10:01,154:INFO:pyemd2:main.py:125:handleKline:2217508: self.closeSec=1688832599, self.tradeDate='20230709', self.openTime='000000', self.closeTime='000959',self.symbol='BTCUSDT',self.open='30196.8', self.close='30212.7'
2023-07-09 00:10:01,187:INFO:pyemd2:main.py:126:handleKline:2217508: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17420  20230708   232000    232959  1688830199  30186.5  30198.9
17421  20230708   233000    233959  1688830799  30198.8  30205.3
17422  20230708   234000    234959  1688831399  30205.3  30200.3
17423  20230708   235000    235959  1688831999  30200.3  30196.7
17424  20230709   000000    000959  1688832599  30196.8  30212.7
2023-07-09 00:10:01,187:INFO:pyemd2:main.py:127:handleKline:2217508: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=8004 

self.closeSec=1688833199, self.tradeDate='20230709', self.openTime='001000', self.closeTime='001959', self.symbol='BTCUSDT', self.open='30212.8', self.close='30232.1'
127.0.0.1 - - [09/Jul/2023 00:20:04] "POST / HTTP/1.1" 200 -
2023-07-09 00:20:08,891:INFO:pyemd2:main.py:125:handleKline:2217508: self.closeSec=1688833199, self.tradeDate='20230709', self.openTime='001000', self.closeTime='001959',self.symbol='BTCUSDT',self.open='30212.8', self.close='30232.1'
2023-07-09 00:20:09,065:INFO:pyemd2:main.py:126:handleKline:2217508: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17421  20230708   233000    233959  1688830799  30198.8  30205.3
17422  20230708   234000    234959  1688831399  30205.3  30200.3
17423  20230708   235000    235959  1688831999  30200.3  30196.7
17424  20230709   000000    000959  1688832599  30196.8  30212.7
17425  20230709   001000    001959  1688833199  30212.8  30232.1
2023-07-09 00:20:09,066:INFO:pyemd2:main.py:127:handleKline:2217508: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}


## /root/FIL/strategy/similarity/log.txt ----- -----

2023-07-09 00:00:04,294:INFO:testStrategy:main.py:308:handleOrderFilled:2217133: handleOrderFilled: data=OrderType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'clientorderid': '42557F1688832003671I0L2', 'symbol': 'BTCUSDT', 'gatewayorderid': 1688832004066434, 'quantity': '37.524', 'price': '30196.8', 'stopprice': '0', 'ordertype': '', 'side': 'BUY', 'status': 'FILLED', 'positionside': 'LONG', 'createtime': 1688832002745, 'updatetime': 1688832004066, 'tradetype': 'usdt', 'selfid': 42557, 'filltrades': [TradeType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'tradeid': 1688832004066, 'clientorderid': '42557F1688832003671I0L2', 'price': '30196.8', 'quantity': '37.524', 'commission': '1133.1047232', 'commissionasset': 'USDT', 'tradetime': 1688832004066, 'tradetype': 'usdt', 'gatetype': 'simulator', 'handletime': 1688832004066}], 'gatetype': 'simulator', 'handletime': 0}
127.0.0.1 - - [09/Jul/2023 00:00:04] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=8003 

self.closeSec=1688832599, self.tradeDate='20230709', self.openTime='000000', self.closeTime='000959', self.symbol='BTCUSDT', self.open='30196.8', self.close='30212.7'
127.0.0.1 - - [09/Jul/2023 00:10:01] "POST / HTTP/1.1" 200 -
2023-07-09 00:10:01,161:INFO:testStrategy:main.py:101:handleKline:2217133: self.closeSec=1688832599, self.tradeDate='20230709', self.openTime='000000', self.closeTime='000959',self.symbol='BTCUSDT',self.open='30196.8', self.close='30212.7'
2023-07-09 00:10:01,199:INFO:testStrategy:main.py:102:handleKline:2217133: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12236  20230708   232000    232959  1688830199  30186.5  30198.9
12237  20230708   233000    233959  1688830799  30198.8  30205.3
12238  20230708   234000    234959  1688831399  30205.3  30200.3
12239  20230708   235000    235959  1688831999  30200.3  30196.7
12240  20230709   000000    000959  1688832599  30196.8  30212.7
2023-07-09 00:10:01,200:INFO:testStrategy:main.py:103:handleKline:2217133: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False, 'isCorr': False}

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=8004 

self.closeSec=1688833199, self.tradeDate='20230709', self.openTime='001000', self.closeTime='001959', self.symbol='BTCUSDT', self.open='30212.8', self.close='30232.1'
127.0.0.1 - - [09/Jul/2023 00:20:04] "POST / HTTP/1.1" 200 -
2023-07-09 00:20:08,641:INFO:testStrategy:main.py:101:handleKline:2217133: self.closeSec=1688833199, self.tradeDate='20230709', self.openTime='001000', self.closeTime='001959',self.symbol='BTCUSDT',self.open='30212.8', self.close='30232.1'
2023-07-09 00:20:08,918:INFO:testStrategy:main.py:102:handleKline:2217133: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12237  20230708   233000    233959  1688830799  30198.8  30205.3
12238  20230708   234000    234959  1688831399  30205.3  30200.3
12239  20230708   235000    235959  1688831999  30200.3  30196.7
12240  20230709   000000    000959  1688832599  30196.8  30212.7
12241  20230709   001000    001959  1688833199  30212.8  30232.1
2023-07-09 00:20:08,918:INFO:testStrategy:main.py:103:handleKline:2217133: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False, 'isCorr': False}


## /root/FIL/strategy/sr_min/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=1, self.total=996015.990996, self.flagDict['side']='buy', self.tradeCount=1, self.count=16000
self.closeSec=1688833199, self.tradeDate='20230709', self.openTime='001500', self.closeTime='001959', self.symbol='BTCUSDT', self.open=30218.0, self.close=30232.2, self.high=30239.8, self.low=30217.9, self.vol=654.573, self.amt=19789055.9149 
127.0.0.1 - - [09/Jul/2023 00:20:01] "POST / HTTP/1.1" 200 -
2023-07-09 00:20:07,229:INFO:sr_min:main.py:172:handleKline:2219263: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5759  20230708   235500    235959  ...         0.0        0.0       0
5760  20230709   000000    000459  ...         0.0        0.0       0
5761  20230709   000500    000959  ...         0.0        0.0       0
5762  20230709   001000    001459  ...         0.0        0.0       0
5763  20230709   001500    001959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-07-09 00:20:07,278:INFO:sr_min:main.py:175:handleKline:2219263: self.closeSec=1688833199, self.tradeDate='20230709', self.openTime='001500', self.closeTime='001959',self.symbol='BTCUSDT',self.open=30218.0, self.close=30232.2, self.high=30239.8, self.low=30217.9, self.vol=654.573, self.amt=19789055.9149, ukdf['pct'].iloc[-1]=0.00047 , ukdf['amount'].iloc[-1]=19789055.9149, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5763, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '37.141', 'enterprice': '26844', 'countrevence': '0', 'unrealprofit': '125918.57892621293', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '30234.28510073', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=1
127.0.0.1 - - [09/Jul/2023 00:25:00] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=1, self.total=996015.990996, self.flagDict['side']='buy', self.tradeCount=1, self.count=16001
self.closeSec=1688833499, self.tradeDate='20230709', self.openTime='002000', self.closeTime='002459', self.symbol='BTCUSDT', self.open=30232.2, self.close=30216.1, self.high=30232.2, self.low=30215.3, self.vol=343.973, self.amt=10396379.7186 
2023-07-09 00:25:00,798:INFO:sr_min:main.py:172:handleKline:2219263: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5760  20230709   000000    000459  ...         0.0        0.0       0
5761  20230709   000500    000959  ...         0.0        0.0       0
5762  20230709   001000    001459  ...         0.0        0.0       0
5763  20230709   001500    001959  ...         0.0        0.0       0
5764  20230709   002000    002459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-07-09 00:25:00,798:INFO:sr_min:main.py:175:handleKline:2219263: self.closeSec=1688833499, self.tradeDate='20230709', self.openTime='002000', self.closeTime='002459',self.symbol='BTCUSDT',self.open=30232.2, self.close=30216.1, self.high=30232.2, self.low=30215.3, self.vol=343.973, self.amt=10396379.7186, ukdf['pct'].iloc[-1]=-0.000533 , ukdf['amount'].iloc[-1]=10396379.7186, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5764, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '37.141', 'enterprice': '26844', 'countrevence': '0', 'unrealprofit': '125292.99592115579', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '30217.44163919', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=1


## /root/FIL/strategy/s_rsrs/log.txt ----- -----

723  20230708   120000    155959  1688803199  ...    723  0.458979  0.419851     NaN
724  20230708   160000    195959  1688817599  ...    724  0.426726  0.341712     NaN

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '53.05', 'enterprice': '30750.9', 'countrevence': '0', 'unrealprofit': '-29939.198118521', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '30186.54188278', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-9223372036854775808, self.sign=1
127.0.0.1 - - [09/Jul/2023 00:00:01] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='s_rsrs', self.symbol='BTCUSDT', interval='4h', intervalSec=14400, wid=25, thd=0.6, self.sign=1, self.total=1629703.909755, self.flagDict['side']='buy', self.tradeCount=9, self.count=333
self.closeSec=1688831999, self.tradeDate='20230708', self.openTime='200000', self.closeTime='235959', self.symbol='BTCUSDT', self.open=30185.3, self.close=30196.7, self.high=30224.5, self.low=30132.5, self.vol=15361.803, self.amt=463704918.8089 
2023-07-09 00:00:01,694:INFO:s_rsrs:main.py:141:handleKline:2218689: self.closeSec=1688831999, self.tradeDate='20230708', self.openTime='200000', self.closeTime='235959',self.symbol='BTCUSDT',self.open=30185.3, self.close=30196.7, self.high=30224.5, self.low=30132.5, self.vol=15361.803, self.amt=463704918.8089 
2023-07-09 00:00:01,723:INFO:s_rsrs:main.py:142:handleKline:2218689: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime  ...        vol           amt       pct
721  20230708   040000    075959  ...  19739.873  5.977132e+08  0.003308
722  20230708   080000    115959  ...  20274.344  6.142538e+08 -0.002239
723  20230708   120000    155959  ...  26594.583  8.031862e+08 -0.002816
724  20230708   160000    195959  ...  25385.741  7.672975e+08  0.000348
725  20230708   200000    235959  ...  15361.803  4.637049e+08  0.000378

[5 rows x 11 columns]
2023-07-09 00:00:03,601:INFO:s_rsrs:main.py:151:handleKline:2218689: df_s.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec  ...  index      beta    zscore  signal
721  20230708   040000    075959  1688774399  ...    721  0.507041  0.506372     NaN
722  20230708   080000    115959  1688788799  ...    722  0.472866  0.432107     NaN
723  20230708   120000    155959  1688803199  ...    723  0.458979  0.419851     NaN
724  20230708   160000    195959  1688817599  ...    724  0.426726  0.341712     NaN
725  20230708   200000    235959  1688831999  ...    725  0.422333  0.360380     NaN

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '53.05', 'enterprice': '30750.9', 'countrevence': '0', 'unrealprofit': '-29395.005', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '30196.8', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-9223372036854775808, self.sign=1


