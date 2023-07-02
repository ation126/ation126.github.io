# 20230703 00:26:01

## /root/FIL/strategy/amihud/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=373746.4768026, self.flagDict['side']='sell', self.tradeCount=2, self.count=14272
self.closeSec=1688314799, self.tradeDate='20230703', self.openTime='001500', self.closeTime='001959', self.symbol='BTCUSDT', self.open=30550.9, self.close=30621.0, self.high=30709.2, self.low=30549.3, self.vol=8498.596, self.amt=260236070.0641 
127.0.0.1 - - [03/Jul/2023 00:20:01] "POST / HTTP/1.1" 200 -
2023-07-03 00:20:06,896:INFO:amihud:main.py:172:handleKline:2219019: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5759  20230702   235500    235959  ...         0.0        0.0       0
5760  20230703   000000    000459  ...         0.0        0.0       0
5761  20230703   000500    000959  ...         0.0        0.0       0
5762  20230703   001000    001459  ...         0.0        0.0       0
5763  20230703   001500    001959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-07-03 00:20:06,925:INFO:amihud:main.py:175:handleKline:2219019: self.closeSec=1688314799, self.tradeDate='20230703', self.openTime='001500', self.closeTime='001959',self.symbol='BTCUSDT',self.open=30550.9, self.close=30621.0, self.high=30709.2, self.low=30549.3, self.vol=8498.596, self.amt=260236070.0641, ukdf['pct'].iloc[-1]=0.002449 , ukdf['amount'].iloc[-1]=260236070.0641, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5763, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '13.926', 'enterprice': '26864.9', 'countrevence': '0', 'unrealprofit': '-52396.18302404244', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '30627.37185294', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1
127.0.0.1 - - [03/Jul/2023 00:25:00] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=373746.4768026, self.flagDict['side']='sell', self.tradeCount=2, self.count=14273
self.closeSec=1688315099, self.tradeDate='20230703', self.openTime='002000', self.closeTime='002459', self.symbol='BTCUSDT', self.open=30620.1, self.close=30603.1, self.high=30628.3, self.low=30581.6, self.vol=2951.457, self.amt=90321495.7473 
2023-07-03 00:25:00,811:INFO:amihud:main.py:172:handleKline:2219019: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5760  20230703   000000    000459  ...         0.0        0.0       0
5761  20230703   000500    000959  ...         0.0        0.0       0
5762  20230703   001000    001459  ...         0.0        0.0       0
5763  20230703   001500    001959  ...         0.0        0.0       0
5764  20230703   002000    002459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-07-03 00:25:00,812:INFO:amihud:main.py:175:handleKline:2219019: self.closeSec=1688315099, self.tradeDate='20230703', self.openTime='002000', self.closeTime='002459',self.symbol='BTCUSDT',self.open=30620.1, self.close=30603.1, self.high=30628.3, self.low=30581.6, self.vol=2951.457, self.amt=90321495.7473, ukdf['pct'].iloc[-1]=-0.000585 , ukdf['amount'].iloc[-1]=90321495.7473, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5764, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '13.926', 'enterprice': '26864.9', 'countrevence': '0', 'unrealprofit': '-52142.6162945556', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '30609.1637006', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1


## /root/FIL/strategy/factorcheck/log.txt ----- -----


self.closeSec=1688314799, self.tradeDate='20230703', self.openTime='001500', self.closeTime='001959', self.symbol='BTCUSDT', self.open=30550.9, self.close=30621.0, self.high=30709.2, self.low=30549.3 
127.0.0.1 - - [03/Jul/2023 00:20:01] "POST / HTTP/1.1" 200 -
2023-07-03 00:20:04,540:INFO:factorcheck2:main.py:126:handleKline:2218005: self.closeSec=1688314799, self.tradeDate='20230703', self.openTime='001500', self.closeTime='001959',self.symbol='BTCUSDT',self.open=30550.9, self.close=30621.0, self.high=30709.2, self.low=30549.3   
2023-07-03 00:20:06,008:INFO:factorcheck2:main.py:127:handleKline:2218005: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1439  20230702   235500    235959  1688313599  ...  30467.8  0.000627   1727    5
1440  20230703   000000    000459  1688313899  ...  30470.4  0.000003   1440    0
1441  20230703   000500    000959  1688314199  ...  30483.9  0.000138   1441    1
1442  20230703   001000    001459  1688314499  ...  30495.6  0.001636   1442    2
1443  20230703   001500    001959  1688314799  ...  30549.3  0.002449   1443    3

[5 rows x 11 columns]
2023-07-03 00:20:06,015:INFO:factorcheck2:main.py:128:handleKline:2218005: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=110, self.factor=0.49804201522493435, self.count=14275 

self.closeSec=1688315099, self.tradeDate='20230703', self.openTime='002000', self.closeTime='002459', self.symbol='BTCUSDT', self.open=30620.1, self.close=30603.1, self.high=30628.3, self.low=30581.6 
127.0.0.1 - - [03/Jul/2023 00:25:00] "POST / HTTP/1.1" 200 -
2023-07-03 00:25:00,751:INFO:factorcheck2:main.py:126:handleKline:2218005: self.closeSec=1688315099, self.tradeDate='20230703', self.openTime='002000', self.closeTime='002459',self.symbol='BTCUSDT',self.open=30620.1, self.close=30603.1, self.high=30628.3, self.low=30581.6   
2023-07-03 00:25:00,794:INFO:factorcheck2:main.py:127:handleKline:2218005: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1440  20230703   000000    000459  1688313899  ...  30470.4  0.000003   1440    0
1441  20230703   000500    000959  1688314199  ...  30483.9  0.000138   1441    1
1442  20230703   001000    001459  1688314499  ...  30495.6  0.001636   1442    2
1443  20230703   001500    001959  1688314799  ...  30549.3  0.002449   1443    3
1444  20230703   002000    002459  1688315099  ...  30581.6 -0.000585   1444    4

[5 rows x 11 columns]
2023-07-03 00:25:00,794:INFO:factorcheck2:main.py:128:handleKline:2218005: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}


## /root/FIL/strategy/logic/log.txt ----- -----

2023-07-03 00:00:19,153:DEBUG:logic:main.py:463:getModel:2218526: df_s.iloc[-5:,:] :
          date closeTime     open  ...    alpha58   alpha67   alpha72
5802  20230702    212959  30518.7  ...  50.833333  0.492624  0.613363
5803  20230702    215959  30488.6  ...  50.833333  0.499112  0.621048
5804  20230702    222959  30510.1  ...  50.833333  0.503411  0.623291
5805  20230702    225959  30524.2  ...  51.250000  0.521760  0.603787
5806  20230702    232959  30586.5  ...  51.250000  0.484519  0.588902

[5 rows x 33 columns]
0.5257352941176471
acc is : 0.5257352941176471
2023-07-03 00:00:19,237:INFO:logic:main.py:468:getModel:2218526: df_pred.iloc[-5:,:] :
     pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
539     0  0.519647  0.480353       1  ...  0.997393   1.0    0.0  1.057161
540     0  0.525532  0.474468       1  ...  0.997857   1.0    0.0  1.057653
541     0  0.525043  0.474957       1  ...  0.999890   1.0    0.0  1.059809
542     0  0.536773  0.463227       0  ...  0.995745   1.0    0.0  1.055415
543     0  0.504820  0.495180       1  ...  0.996784   1.0    0.0  1.056517

[5 rows x 10 columns]
2023-07-03 00:00:19,249:INFO:logic:main.py:478:getModel:2218526: df_panel.iloc[-5:,:] :
    pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
45     0  0.519819  0.480181       1  ...  0.997393   1.0    0.0  1.058647
46     0  0.524938  0.475062       1  ...  0.997857   1.0    0.0  1.058148
47     0  0.525045  0.474955       1  ...  0.999890   1.0    0.0  1.060305
48     0  0.536535  0.463465       0  ...  0.995745   1.0    0.0  1.055042
49     0  0.504820  0.495180       1  ...  0.996784   1.0    0.0  1.056517

[5 rows x 10 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '25.53', 'enterprice': '30560', 'countrevence': '0', 'unrealprofit': '-1682.9687366433', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '30494.07878039', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}


## /root/FIL/strategy/modifiedmom/log.txt ----- -----

127.0.0.1 - - [03/Jul/2023 00:00:04] "POST / HTTP/1.1" 200 -
2023-07-03 00:00:04,328:INFO:modifiedmom:main.py:319:handleOrderFilled:2218259: handleOrderFilled: data=OrderType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'clientorderid': '42517F1688313603593I0L59', 'symbol': 'BTCUSDT', 'gatewayorderid': 1688313603962560, 'quantity': '25.394', 'price': '30491.4', 'stopprice': '0', 'ordertype': '', 'side': 'SELL', 'status': 'FILLED', 'positionside': 'SHORT', 'createtime': 1688313602603, 'updatetime': 1688313603962, 'tradetype': 'usdt', 'selfid': 42517, 'filltrades': [TradeType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'tradeid': 1688313603962, 'clientorderid': '42517F1688313603593I0L59', 'price': '30491.4', 'quantity': '25.394', 'commission': '774.2986116', 'commissionasset': 'USDT', 'tradetime': 1688313603962, 'tradetype': 'usdt', 'gatetype': 'simulator', 'handletime': 1688313603962}], 'gatetype': 'simulator', 'handletime': 0}
127.0.0.1 - - [03/Jul/2023 00:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=7136 

self.closeSec=1688314199, self.tradeDate='20230703', self.openTime='000000', self.closeTime='000959', self.symbol='BTCUSDT', self.open='30491.4', self.close='30496.3'
2023-07-03 00:10:01,106:INFO:modifiedmom:main.py:144:handleKline:2218259: self.closeSec=1688314199, self.tradeDate='20230703', self.openTime='000000', self.closeTime='000959',self.symbol='BTCUSDT',self.open='30491.4', self.close='30496.3'
2023-07-03 00:10:01,131:INFO:modifiedmom:main.py:145:handleKline:2218259: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
572  20230702   232000    232959  1688311799  30559.1  30467.8 -0.002988
573  20230702   233000    233959  1688312399  30467.8  30518.9  0.001677
574  20230702   234000    234959  1688312999  30518.9    30496 -0.000750
575  20230702   235000    235959  1688313599    30496  30491.5 -0.000148
576  20230703   000000    000959  1688314199  30491.4  30496.3  0.000157
2023-07-03 00:10:01,131:INFO:modifiedmom:main.py:146:handleKline:2218259: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=7137 

self.closeSec=1688314799, self.tradeDate='20230703', self.openTime='001000', self.closeTime='001959', self.symbol='BTCUSDT', self.open='30496.4', self.close='30621'
127.0.0.1 - - [03/Jul/2023 00:20:04] "POST / HTTP/1.1" 200 -
2023-07-03 00:20:07,025:INFO:modifiedmom:main.py:144:handleKline:2218259: self.closeSec=1688314799, self.tradeDate='20230703', self.openTime='001000', self.closeTime='001959',self.symbol='BTCUSDT',self.open='30496.4', self.close='30621'
2023-07-03 00:20:07,755:INFO:modifiedmom:main.py:145:handleKline:2218259: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
573  20230702   233000    233959  1688312399  30467.8  30518.9  0.001677
574  20230702   234000    234959  1688312999  30518.9    30496 -0.000750
575  20230702   235000    235959  1688313599    30496  30491.5 -0.000148
576  20230703   000000    000959  1688314199  30491.4  30496.3  0.000157
577  20230703   001000    001959  1688314799  30496.4    30621  0.004089
2023-07-03 00:20:07,755:INFO:modifiedmom:main.py:146:handleKline:2218259: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False}


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

2023-07-03 00:00:02,096:INFO:pyemd2:main.py:127:handleKline:2217508: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}
2023-07-03 00:00:02,205:INFO:pyemd2:main.py:190:insertFactor:2217508: curDateTime:7030000, name:pyemd2, symbol:BTCUSDT, tradeDate:20230702, closeTime:235959, close:30491.5, total:995666.2287338, pct_pre:-0.0022398869919789677, thd:-0.23831046188252636, side:sell 
127.0.0.1 - - [03/Jul/2023 00:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=7139 

self.closeSec=1688314199, self.tradeDate='20230703', self.openTime='000000', self.closeTime='000959', self.symbol='BTCUSDT', self.open='30491.4', self.close='30496.3'
2023-07-03 00:10:01,118:INFO:pyemd2:main.py:125:handleKline:2217508: self.closeSec=1688314199, self.tradeDate='20230703', self.openTime='000000', self.closeTime='000959',self.symbol='BTCUSDT',self.open='30491.4', self.close='30496.3'
2023-07-03 00:10:01,132:INFO:pyemd2:main.py:126:handleKline:2217508: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17420  20230702   232000    232959  1688311799  30559.1  30467.8
17421  20230702   233000    233959  1688312399  30467.8  30518.9
17422  20230702   234000    234959  1688312999  30518.9    30496
17423  20230702   235000    235959  1688313599    30496  30491.5
17424  20230703   000000    000959  1688314199  30491.4  30496.3
2023-07-03 00:10:01,132:INFO:pyemd2:main.py:127:handleKline:2217508: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=7140 

self.closeSec=1688314799, self.tradeDate='20230703', self.openTime='001000', self.closeTime='001959', self.symbol='BTCUSDT', self.open='30496.4', self.close='30621'
127.0.0.1 - - [03/Jul/2023 00:20:04] "POST / HTTP/1.1" 200 -
2023-07-03 00:20:08,619:INFO:pyemd2:main.py:125:handleKline:2217508: self.closeSec=1688314799, self.tradeDate='20230703', self.openTime='001000', self.closeTime='001959',self.symbol='BTCUSDT',self.open='30496.4', self.close='30621'
2023-07-03 00:20:08,733:INFO:pyemd2:main.py:126:handleKline:2217508: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17421  20230702   233000    233959  1688312399  30467.8  30518.9
17422  20230702   234000    234959  1688312999  30518.9    30496
17423  20230702   235000    235959  1688313599    30496  30491.5
17424  20230703   000000    000959  1688314199  30491.4  30496.3
17425  20230703   001000    001959  1688314799  30496.4    30621
2023-07-03 00:20:08,733:INFO:pyemd2:main.py:127:handleKline:2217508: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}


## /root/FIL/strategy/similarity/log.txt ----- -----

127.0.0.1 - - [03/Jul/2023 00:00:04] "POST / HTTP/1.1" 200 -
2023-07-03 00:00:04,154:INFO:testStrategy:main.py:308:handleOrderFilled:2217133: handleOrderFilled: data=OrderType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'clientorderid': '42516F1688313603558I0L2', 'symbol': 'BTCUSDT', 'gatewayorderid': 1688313603932871, 'quantity': '37.42', 'price': '30491.5', 'stopprice': '0', 'ordertype': '', 'side': 'BUY', 'status': 'FILLED', 'positionside': 'LONG', 'createtime': 1688313602687, 'updatetime': 1688313603932, 'tradetype': 'usdt', 'selfid': 42516, 'filltrades': [TradeType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'tradeid': 1688313603932, 'clientorderid': '42516F1688313603558I0L2', 'price': '30491.5', 'quantity': '37.42', 'commission': '1140.99193', 'commissionasset': 'USDT', 'tradetime': 1688313603932, 'tradetype': 'usdt', 'gatetype': 'simulator', 'handletime': 1688313603932}], 'gatetype': 'simulator', 'handletime': 0}

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=7139 

self.closeSec=1688314199, self.tradeDate='20230703', self.openTime='000000', self.closeTime='000959', self.symbol='BTCUSDT', self.open='30491.4', self.close='30496.3'
127.0.0.1 - - [03/Jul/2023 00:10:01] "POST / HTTP/1.1" 200 -
2023-07-03 00:10:01,124:INFO:testStrategy:main.py:101:handleKline:2217133: self.closeSec=1688314199, self.tradeDate='20230703', self.openTime='000000', self.closeTime='000959',self.symbol='BTCUSDT',self.open='30491.4', self.close='30496.3'
2023-07-03 00:10:01,140:INFO:testStrategy:main.py:102:handleKline:2217133: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12236  20230702   232000    232959  1688311799  30559.1  30467.8
12237  20230702   233000    233959  1688312399  30467.8  30518.9
12238  20230702   234000    234959  1688312999  30518.9    30496
12239  20230702   235000    235959  1688313599    30496  30491.5
12240  20230703   000000    000959  1688314199  30491.4  30496.3
2023-07-03 00:10:01,140:INFO:testStrategy:main.py:103:handleKline:2217133: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False, 'isCorr': False}

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=7140 

self.closeSec=1688314799, self.tradeDate='20230703', self.openTime='001000', self.closeTime='001959', self.symbol='BTCUSDT', self.open='30496.4', self.close='30621'
127.0.0.1 - - [03/Jul/2023 00:20:04] "POST / HTTP/1.1" 200 -
2023-07-03 00:20:08,228:INFO:testStrategy:main.py:101:handleKline:2217133: self.closeSec=1688314799, self.tradeDate='20230703', self.openTime='001000', self.closeTime='001959',self.symbol='BTCUSDT',self.open='30496.4', self.close='30621'
2023-07-03 00:20:08,505:INFO:testStrategy:main.py:102:handleKline:2217133: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12237  20230702   233000    233959  1688312399  30467.8  30518.9
12238  20230702   234000    234959  1688312999  30518.9    30496
12239  20230702   235000    235959  1688313599    30496  30491.5
12240  20230703   000000    000959  1688314199  30491.4  30496.3
12241  20230703   001000    001959  1688314799  30496.4    30621
2023-07-03 00:20:08,507:INFO:testStrategy:main.py:103:handleKline:2217133: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False, 'isCorr': False}


## /root/FIL/strategy/sr_min/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=1, self.total=996015.990996, self.flagDict['side']='buy', self.tradeCount=1, self.count=14272
self.closeSec=1688314799, self.tradeDate='20230703', self.openTime='001500', self.closeTime='001959', self.symbol='BTCUSDT', self.open=30550.9, self.close=30621.0, self.high=30709.2, self.low=30549.3, self.vol=8498.596, self.amt=260236070.0641 
127.0.0.1 - - [03/Jul/2023 00:20:01] "POST / HTTP/1.1" 200 -
2023-07-03 00:20:06,896:INFO:sr_min:main.py:172:handleKline:2219263: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5759  20230702   235500    235959  ...         0.0        0.0       0
5760  20230703   000000    000459  ...         0.0        0.0       0
5761  20230703   000500    000959  ...         0.0        0.0       0
5762  20230703   001000    001459  ...         0.0        0.0       0
5763  20230703   001500    001959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-07-03 00:20:06,916:INFO:sr_min:main.py:175:handleKline:2219263: self.closeSec=1688314799, self.tradeDate='20230703', self.openTime='001500', self.closeTime='001959',self.symbol='BTCUSDT',self.open=30550.9, self.close=30621.0, self.high=30709.2, self.low=30549.3, self.vol=8498.596, self.amt=260236070.0641, ukdf['pct'].iloc[-1]=0.002449 , ukdf['amount'].iloc[-1]=260236070.0641, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5763, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '37.141', 'enterprice': '26844', 'countrevence': '0', 'unrealprofit': '140518.21399004454', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '30627.37185294', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=1
127.0.0.1 - - [03/Jul/2023 00:25:00] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=1, self.total=996015.990996, self.flagDict['side']='buy', self.tradeCount=1, self.count=14273
self.closeSec=1688315099, self.tradeDate='20230703', self.openTime='002000', self.closeTime='002459', self.symbol='BTCUSDT', self.open=30620.1, self.close=30603.1, self.high=30628.3, self.low=30581.6, self.vol=2951.457, self.amt=90321495.7473 
2023-07-03 00:25:00,812:INFO:sr_min:main.py:172:handleKline:2219263: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5760  20230703   000000    000459  ...         0.0        0.0       0
5761  20230703   000500    000959  ...         0.0        0.0       0
5762  20230703   001000    001459  ...         0.0        0.0       0
5763  20230703   001500    001959  ...         0.0        0.0       0
5764  20230703   002000    002459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-07-03 00:25:00,812:INFO:sr_min:main.py:175:handleKline:2219263: self.closeSec=1688315099, self.tradeDate='20230703', self.openTime='002000', self.closeTime='002459',self.symbol='BTCUSDT',self.open=30620.1, self.close=30603.1, self.high=30628.3, self.low=30581.6, self.vol=2951.457, self.amt=90321495.7473, ukdf['pct'].iloc[-1]=-0.000585 , ukdf['amount'].iloc[-1]=90321495.7473, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5764, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '37.141', 'enterprice': '26844', 'countrevence': '0', 'unrealprofit': '139841.9450039846', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '30609.1637006', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=1


## /root/FIL/strategy/s_rsrs/log.txt ----- -----

723  20230702   120000    155959  1688284799  ...    723  0.002523 -1.329504    -1.0
724  20230702   160000    195959  1688299199  ...    724  0.001655 -1.303934    -1.0

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '53.268', 'enterprice': '30707', 'countrevence': '0', 'unrealprofit': '9002.292', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '30538', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-1, self.sign=-1
--handleKline--:  version='2.0.0', self.name='s_rsrs', self.symbol='BTCUSDT', interval='4h', intervalSec=14400, wid=25, thd=0.6, self.sign=-1, self.total=1634064.775524, self.flagDict['side']='sell', self.tradeCount=8, self.count=297
self.closeSec=1688313599, self.tradeDate='20230702', self.openTime='200000', self.closeTime='235959', self.symbol='BTCUSDT', self.open=30537.2, self.close=30491.5, self.high=30626.2, self.low=30149.9, self.vol=61816.394, self.amt=1882439662.18205 
127.0.0.1 - - [03/Jul/2023 00:00:01] "POST / HTTP/1.1" 200 -
2023-07-03 00:00:01,615:INFO:s_rsrs:main.py:141:handleKline:2218689: self.closeSec=1688313599, self.tradeDate='20230702', self.openTime='200000', self.closeTime='235959',self.symbol='BTCUSDT',self.open=30537.2, self.close=30491.5, self.high=30626.2, self.low=30149.9, self.vol=61816.394, self.amt=1882439662.18205 
2023-07-03 00:00:01,642:INFO:s_rsrs:main.py:142:handleKline:2218689: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime  ...        vol           amt       pct
721  20230702   040000    075959  ...   9534.474  2.915149e+08 -0.000879
722  20230702   080000    115959  ...  27111.402  8.282798e+08 -0.002237
723  20230702   120000    155959  ...  16551.148  5.048320e+08 -0.000016
724  20230702   160000    195959  ...  13555.768  4.136838e+08  0.001065
725  20230702   200000    235959  ...  61816.394  1.882440e+09 -0.001497

[5 rows x 11 columns]
2023-07-03 00:00:03,155:INFO:s_rsrs:main.py:151:handleKline:2218689: df_s.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec  ...  index      beta    zscore  signal
721  20230702   040000    075959  1688255999  ...    721  0.003916 -1.380020    -1.0
722  20230702   080000    115959  1688270399  ...    722  0.003287 -1.355462    -1.0
723  20230702   120000    155959  1688284799  ...    723  0.002523 -1.329504    -1.0
724  20230702   160000    195959  1688299199  ...    724  0.001655 -1.303934    -1.0
725  20230702   200000    235959  1688313599  ...    725  0.001147 -1.277853    -1.0

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '53.268', 'enterprice': '30707', 'countrevence': '0', 'unrealprofit': '11378.87588520528', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '30493.38439804', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-1, self.sign=-1


