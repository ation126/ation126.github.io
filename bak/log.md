# 20230707 16:26:01

## /root/FIL/strategy/amihud/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=373746.4768026, self.flagDict['side']='sell', self.tradeCount=2, self.count=15616
self.closeSec=1688717999, self.tradeDate='20230707', self.openTime='161500', self.closeTime='161959', self.symbol='BTCUSDT', self.open=30065.0, self.close=30031.5, self.high=30075.8, self.low=30019.2, self.vol=984.554, self.amt=29575412.4292 
127.0.0.1 - - [07/Jul/2023 16:20:01] "POST / HTTP/1.1" 200 -
2023-07-07 16:20:07,476:INFO:amihud:main.py:172:handleKline:2219019: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5951  20230707   155500    155959  ...         0.0        0.0       0
5952  20230707   160000    160459  ...         0.0        0.0       0
5953  20230707   160500    160959  ...         0.0        0.0       0
5954  20230707   161000    161459  ...         0.0        0.0       0
5955  20230707   161500    161959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-07-07 16:20:07,496:INFO:amihud:main.py:175:handleKline:2219019: self.closeSec=1688717999, self.tradeDate='20230707', self.openTime='161500', self.closeTime='161959',self.symbol='BTCUSDT',self.open=30065.0, self.close=30031.5, self.high=30075.8, self.low=30019.2, self.vol=984.554, self.amt=29575412.4292, ukdf['pct'].iloc[-1]=-0.001068 , ukdf['amount'].iloc[-1]=29575412.4292, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5955, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '13.926', 'enterprice': '26864.9', 'countrevence': '0', 'unrealprofit': '-44126.14810898382', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '30033.51612157', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1
127.0.0.1 - - [07/Jul/2023 16:25:00] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=373746.4768026, self.flagDict['side']='sell', self.tradeCount=2, self.count=15617
self.closeSec=1688718299, self.tradeDate='20230707', self.openTime='162000', self.closeTime='162459', self.symbol='BTCUSDT', self.open=30031.4, self.close=30030.4, self.high=30031.5, self.low=30000.0, self.vol=568.057, self.amt=17051634.3625 
2023-07-07 16:25:00,790:INFO:amihud:main.py:172:handleKline:2219019: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5952  20230707   160000    160459  ...         0.0        0.0       0
5953  20230707   160500    160959  ...         0.0        0.0       0
5954  20230707   161000    161459  ...         0.0        0.0       0
5955  20230707   161500    161959  ...         0.0        0.0       0
5956  20230707   162000    162459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-07-07 16:25:00,790:INFO:amihud:main.py:175:handleKline:2219019: self.closeSec=1688718299, self.tradeDate='20230707', self.openTime='162000', self.closeTime='162459',self.symbol='BTCUSDT',self.open=30031.4, self.close=30030.4, self.high=30031.5, self.low=30000.0, self.vol=568.057, self.amt=17051634.3625, ukdf['pct'].iloc[-1]=-3.7e-05 , ukdf['amount'].iloc[-1]=17051634.3625, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5956, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '13.926', 'enterprice': '26864.9', 'countrevence': '0', 'unrealprofit': '-44085.82360111512', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '30030.62049412', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1


## /root/FIL/strategy/factorcheck/log.txt ----- -----


self.closeSec=1688717999, self.tradeDate='20230707', self.openTime='161500', self.closeTime='161959', self.symbol='BTCUSDT', self.open=30065.0, self.close=30031.5, self.high=30075.8, self.low=30019.2 
127.0.0.1 - - [07/Jul/2023 16:20:01] "POST / HTTP/1.1" 200 -
2023-07-07 16:20:04,958:INFO:factorcheck2:main.py:126:handleKline:2218005: self.closeSec=1688717999, self.tradeDate='20230707', self.openTime='161500', self.closeTime='161959',self.symbol='BTCUSDT',self.open=30065.0, self.close=30031.5, self.high=30075.8, self.low=30019.2   
2023-07-07 16:20:06,526:INFO:factorcheck2:main.py:127:handleKline:2218005: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1631  20230707   155500    155959  1688716799  ...  29904.4 -0.001129   1631    5
1632  20230707   160000    160459  1688717099  ...  29957.6  0.000387   1632    0
1633  20230707   160500    160959  1688717399  ...  30001.7  0.001087   1633    1
1634  20230707   161000    161459  1688717699  ...  30035.1  0.000879   1634    2
1635  20230707   161500    161959  1688717999  ...  30019.2 -0.001068   1635    3

[5 rows x 11 columns]
2023-07-07 16:20:06,537:INFO:factorcheck2:main.py:128:handleKline:2218005: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': False, 'isOpen': True, 'isClose': False, 'isTrig': True}
127.0.0.1 - - [07/Jul/2023 16:25:00] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.7231308777055074, self.count=15619 

self.closeSec=1688718299, self.tradeDate='20230707', self.openTime='162000', self.closeTime='162459', self.symbol='BTCUSDT', self.open=30031.4, self.close=30030.4, self.high=30031.5, self.low=30000.0 
2023-07-07 16:25:00,747:INFO:factorcheck2:main.py:126:handleKline:2218005: self.closeSec=1688718299, self.tradeDate='20230707', self.openTime='162000', self.closeTime='162459',self.symbol='BTCUSDT',self.open=30031.4, self.close=30030.4, self.high=30031.5, self.low=30000.0   
2023-07-07 16:25:00,772:INFO:factorcheck2:main.py:127:handleKline:2218005: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1632  20230707   160000    160459  1688717099  ...  29957.6  0.000387   1632    0
1633  20230707   160500    160959  1688717399  ...  30001.7  0.001087   1633    1
1634  20230707   161000    161459  1688717699  ...  30035.1  0.000879   1634    2
1635  20230707   161500    161959  1688717999  ...  30019.2 -0.001068   1635    3
1636  20230707   162000    162459  1688718299  ...  30000.0 -0.000037   1636    4

[5 rows x 11 columns]
2023-07-07 16:25:00,772:INFO:factorcheck2:main.py:128:handleKline:2218005: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': False, 'isOpen': True, 'isClose': False, 'isTrig': True}


## /root/FIL/strategy/logic/log.txt ----- -----

2023-07-07 16:00:24,617:DEBUG:logic:main.py:463:getModel:2218526: df_s.iloc[-5:,:] :
          date closeTime     open  ...    alpha58   alpha67   alpha72
5786  20230707    132959  30076.0  ...  48.750000  0.459339  0.753729
5787  20230707    135959  30184.5  ...  49.166667  0.461300  0.748512
5788  20230707    142959  30196.1  ...  48.750000  0.451320  0.746548
5789  20230707    145959  30126.7  ...  48.750000  0.448378  0.745452
5790  20230707    152959  30106.2  ...  48.333333  0.443664  0.745118

[5 rows x 33 columns]
0.5461254612546126
acc is : 0.5461254612546126
2023-07-07 16:00:24,776:INFO:logic:main.py:468:getModel:2218526: df_pred.iloc[-5:,:] :
     pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
537     0  0.540994  0.459006       1  ...  0.957571   1.0    0.0  0.993888
538     0  0.527768  0.472232       0  ...  0.955373   1.0    0.0  0.991607
539     0  0.502514  0.497486       0  ...  0.954720   1.0    0.0  0.990929
540     0  0.517311  0.482689       0  ...  0.953677   1.0    0.0  0.989846
541     0  0.512318  0.487682       0  ...  0.951133   1.0    0.0  0.987206

[5 rows x 10 columns]
2023-07-07 16:00:24,811:INFO:logic:main.py:478:getModel:2218526: df_panel.iloc[-5:,:] :
    pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
45     0  0.541037  0.458963       1  ...  0.957571   1.0    0.0  0.990345
46     0  0.528561  0.471439       0  ...  0.955373   1.0    0.0  0.989370
47     0  0.502866  0.497134       0  ...  0.954720   1.0    0.0  0.988446
48     0  0.516745  0.483255       0  ...  0.953677   1.0    0.0  0.986599
49     0  0.512318  0.487682       0  ...  0.951133   1.0    0.0  0.987206

[5 rows x 10 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '24.764', 'enterprice': '30087.2', 'countrevence': '0', 'unrealprofit': '-2161.8972', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '29999.9', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}


## /root/FIL/strategy/modifiedmom/log.txt ----- -----

527  20230707   155000    155959  1688716799  29992.1  29992.9  0.000027
2023-07-07 16:00:02,186:INFO:modifiedmom:main.py:146:handleKline:2218259: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': True, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True}
127.0.0.1 - - [07/Jul/2023 16:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=7808 

self.closeSec=1688717399, self.tradeDate='20230707', self.openTime='160000', self.closeTime='160959', self.symbol='BTCUSDT', self.open='29992.9', self.close='30037.3'
2023-07-07 16:10:01,117:INFO:modifiedmom:main.py:144:handleKline:2218259: self.closeSec=1688717399, self.tradeDate='20230707', self.openTime='160000', self.closeTime='160959',self.symbol='BTCUSDT',self.open='29992.9', self.close='30037.3'
2023-07-07 16:10:01,143:INFO:modifiedmom:main.py:145:handleKline:2218259: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
524  20230707   152000    152959  1688714999  30113.3  30073.2 -0.001335
525  20230707   153000    153959  1688715599  30073.3  30105.2  0.001064
526  20230707   154000    154959  1688716199  30105.3  29992.1 -0.003757
527  20230707   155000    155959  1688716799  29992.1  29992.9  0.000027
528  20230707   160000    160959  1688717399  29992.9  30037.3  0.001480
2023-07-07 16:10:01,144:INFO:modifiedmom:main.py:146:handleKline:2218259: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': True, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True}

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=7809 

self.closeSec=1688717999, self.tradeDate='20230707', self.openTime='161000', self.closeTime='161959', self.symbol='BTCUSDT', self.open='30037.3', self.close='30031.5'
127.0.0.1 - - [07/Jul/2023 16:20:04] "POST / HTTP/1.1" 200 -
2023-07-07 16:20:07,325:INFO:modifiedmom:main.py:144:handleKline:2218259: self.closeSec=1688717999, self.tradeDate='20230707', self.openTime='161000', self.closeTime='161959',self.symbol='BTCUSDT',self.open='30037.3', self.close='30031.5'
2023-07-07 16:20:08,176:INFO:modifiedmom:main.py:145:handleKline:2218259: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
525  20230707   153000    153959  1688715599  30073.3  30105.2  0.001064
526  20230707   154000    154959  1688716199  30105.3  29992.1 -0.003757
527  20230707   155000    155959  1688716799  29992.1  29992.9  0.000027
528  20230707   160000    160959  1688717399  29992.9  30037.3  0.001480
529  20230707   161000    161959  1688717999  30037.3  30031.5 -0.000193
2023-07-07 16:20:08,177:INFO:modifiedmom:main.py:146:handleKline:2218259: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': True, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True}


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

17519  20230707   155000    155959  1688716799  29992.1  29992.9
2023-07-07 16:00:02,180:INFO:pyemd2:main.py:127:handleKline:2217508: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}
127.0.0.1 - - [07/Jul/2023 16:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=7811 

self.closeSec=1688717399, self.tradeDate='20230707', self.openTime='160000', self.closeTime='160959', self.symbol='BTCUSDT', self.open='29992.9', self.close='30037.3'
2023-07-07 16:10:01,106:INFO:pyemd2:main.py:125:handleKline:2217508: self.closeSec=1688717399, self.tradeDate='20230707', self.openTime='160000', self.closeTime='160959',self.symbol='BTCUSDT',self.open='29992.9', self.close='30037.3'
2023-07-07 16:10:01,122:INFO:pyemd2:main.py:126:handleKline:2217508: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17516  20230707   152000    152959  1688714999  30113.3  30073.2
17517  20230707   153000    153959  1688715599  30073.3  30105.2
17518  20230707   154000    154959  1688716199  30105.3  29992.1
17519  20230707   155000    155959  1688716799  29992.1  29992.9
17520  20230707   160000    160959  1688717399  29992.9  30037.3
2023-07-07 16:10:01,122:INFO:pyemd2:main.py:127:handleKline:2217508: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=7812 

self.closeSec=1688717999, self.tradeDate='20230707', self.openTime='161000', self.closeTime='161959', self.symbol='BTCUSDT', self.open='30037.3', self.close='30031.5'
127.0.0.1 - - [07/Jul/2023 16:20:04] "POST / HTTP/1.1" 200 -
2023-07-07 16:20:09,340:INFO:pyemd2:main.py:125:handleKline:2217508: self.closeSec=1688717999, self.tradeDate='20230707', self.openTime='161000', self.closeTime='161959',self.symbol='BTCUSDT',self.open='30037.3', self.close='30031.5'
2023-07-07 16:20:09,543:INFO:pyemd2:main.py:126:handleKline:2217508: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17517  20230707   153000    153959  1688715599  30073.3  30105.2
17518  20230707   154000    154959  1688716199  30105.3  29992.1
17519  20230707   155000    155959  1688716799  29992.1  29992.9
17520  20230707   160000    160959  1688717399  29992.9  30037.3
17521  20230707   161000    161959  1688717999  30037.3  30031.5
2023-07-07 16:20:09,544:INFO:pyemd2:main.py:127:handleKline:2217508: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}


## /root/FIL/strategy/similarity/log.txt ----- -----

12191  20230707   155000    155959  1688716799  29992.1  29992.9
2023-07-07 16:00:02,199:INFO:testStrategy:main.py:103:handleKline:2217133: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': True, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}
127.0.0.1 - - [07/Jul/2023 16:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=7811 

self.closeSec=1688717399, self.tradeDate='20230707', self.openTime='160000', self.closeTime='160959', self.symbol='BTCUSDT', self.open='29992.9', self.close='30037.3'
2023-07-07 16:10:01,098:INFO:testStrategy:main.py:101:handleKline:2217133: self.closeSec=1688717399, self.tradeDate='20230707', self.openTime='160000', self.closeTime='160959',self.symbol='BTCUSDT',self.open='29992.9', self.close='30037.3'
2023-07-07 16:10:01,120:INFO:testStrategy:main.py:102:handleKline:2217133: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12188  20230707   152000    152959  1688714999  30113.3  30073.2
12189  20230707   153000    153959  1688715599  30073.3  30105.2
12190  20230707   154000    154959  1688716199  30105.3  29992.1
12191  20230707   155000    155959  1688716799  29992.1  29992.9
12192  20230707   160000    160959  1688717399  29992.9  30037.3
2023-07-07 16:10:01,120:INFO:testStrategy:main.py:103:handleKline:2217133: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': True, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=7812 

self.closeSec=1688717999, self.tradeDate='20230707', self.openTime='161000', self.closeTime='161959', self.symbol='BTCUSDT', self.open='30037.3', self.close='30031.5'
127.0.0.1 - - [07/Jul/2023 16:20:04] "POST / HTTP/1.1" 200 -
2023-07-07 16:20:09,009:INFO:testStrategy:main.py:101:handleKline:2217133: self.closeSec=1688717999, self.tradeDate='20230707', self.openTime='161000', self.closeTime='161959',self.symbol='BTCUSDT',self.open='30037.3', self.close='30031.5'
2023-07-07 16:20:09,328:INFO:testStrategy:main.py:102:handleKline:2217133: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12189  20230707   153000    153959  1688715599  30073.3  30105.2
12190  20230707   154000    154959  1688716199  30105.3  29992.1
12191  20230707   155000    155959  1688716799  29992.1  29992.9
12192  20230707   160000    160959  1688717399  29992.9  30037.3
12193  20230707   161000    161959  1688717999  30037.3  30031.5
2023-07-07 16:20:09,336:INFO:testStrategy:main.py:103:handleKline:2217133: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': True, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}


## /root/FIL/strategy/sr_min/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=1, self.total=996015.990996, self.flagDict['side']='buy', self.tradeCount=1, self.count=15616
self.closeSec=1688717999, self.tradeDate='20230707', self.openTime='161500', self.closeTime='161959', self.symbol='BTCUSDT', self.open=30065.0, self.close=30031.5, self.high=30075.8, self.low=30019.2, self.vol=984.554, self.amt=29575412.4292 
127.0.0.1 - - [07/Jul/2023 16:20:01] "POST / HTTP/1.1" 200 -
2023-07-07 16:20:07,465:INFO:sr_min:main.py:172:handleKline:2219263: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5951  20230707   155500    155959  ...         0.0        0.0       0
5952  20230707   160000    160459  ...         0.0        0.0       0
5953  20230707   160500    160959  ...         0.0        0.0       0
5954  20230707   161000    161459  ...         0.0        0.0       0
5955  20230707   161500    161959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-07-07 16:20:07,486:INFO:sr_min:main.py:175:handleKline:2219263: self.closeSec=1688717999, self.tradeDate='20230707', self.openTime='161500', self.closeTime='161959',self.symbol='BTCUSDT',self.open=30065.0, self.close=30031.5, self.high=30075.8, self.low=30019.2, self.vol=984.554, self.amt=29575412.4292, ukdf['pct'].iloc[-1]=-0.001068 , ukdf['amount'].iloc[-1]=29575412.4292, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5955, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '37.141', 'enterprice': '26844', 'countrevence': '0', 'unrealprofit': '118461.81827123137', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '30033.51612157', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=1
--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=1, self.total=996015.990996, self.flagDict['side']='buy', self.tradeCount=1, self.count=15617
self.closeSec=1688718299, self.tradeDate='20230707', self.openTime='162000', self.closeTime='162459', self.symbol='BTCUSDT', self.open=30031.4, self.close=30030.4, self.high=30031.5, self.low=30000.0, self.vol=568.057, self.amt=17051634.3625 
127.0.0.1 - - [07/Jul/2023 16:25:00] "POST / HTTP/1.1" 200 -
2023-07-07 16:25:00,794:INFO:sr_min:main.py:172:handleKline:2219263: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5952  20230707   160000    160459  ...         0.0        0.0       0
5953  20230707   160500    160959  ...         0.0        0.0       0
5954  20230707   161000    161459  ...         0.0        0.0       0
5955  20230707   161500    161959  ...         0.0        0.0       0
5956  20230707   162000    162459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-07-07 16:25:00,794:INFO:sr_min:main.py:175:handleKline:2219263: self.closeSec=1688718299, self.tradeDate='20230707', self.openTime='162000', self.closeTime='162459',self.symbol='BTCUSDT',self.open=30031.4, self.close=30030.4, self.high=30031.5, self.low=30000.0, self.vol=568.057, self.amt=17051634.3625, ukdf['pct'].iloc[-1]=-3.7e-05 , ukdf['amount'].iloc[-1]=17051634.3625, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5956, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '37.141', 'enterprice': '26844', 'countrevence': '0', 'unrealprofit': '118354.27177211092', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '30030.62049412', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=1


## /root/FIL/strategy/s_rsrs/log.txt ----- -----

721  20230707   040000    075959  1688687999  ...    721  0.320735 -0.195696     NaN
722  20230707   080000    115959  1688702399  ...    722  0.387131  0.007713     NaN

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '53.05', 'enterprice': '30750.9', 'countrevence': '0', 'unrealprofit': '-33278.077244379', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '30123.60353922', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-9223372036854775808, self.sign=1
127.0.0.1 - - [07/Jul/2023 16:00:01] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='s_rsrs', self.symbol='BTCUSDT', interval='4h', intervalSec=14400, wid=25, thd=0.6, self.sign=1, self.total=1629703.909755, self.flagDict['side']='buy', self.tradeCount=9, self.count=325
self.closeSec=1688716799, self.tradeDate='20230707', self.openTime='120000', self.closeTime='155959', self.symbol='BTCUSDT', self.open=30122.1, self.close=29993.0, self.high=30297.3, self.low=29904.4, self.vol=54675.684, self.amt=1646778162.97014 
2023-07-07 16:00:01,716:INFO:s_rsrs:main.py:141:handleKline:2218689: self.closeSec=1688716799, self.tradeDate='20230707', self.openTime='120000', self.closeTime='155959',self.symbol='BTCUSDT',self.open=30122.1, self.close=29993.0, self.high=30297.3, self.low=29904.4, self.vol=54675.684, self.amt=1646778162.97014 
2023-07-07 16:00:01,748:INFO:s_rsrs:main.py:142:handleKline:2218689: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime  ...         vol           amt       pct
719  20230706   200000    235959  ...  270998.539  8.221109e+09 -0.014294
720  20230707   000000    035959  ...   65824.541  1.993928e+09 -0.003146
721  20230707   040000    075959  ...   69574.823  2.092299e+09 -0.013643
722  20230707   080000    115959  ...   73967.626  2.215445e+09  0.008055
723  20230707   120000    155959  ...   54675.684  1.646778e+09 -0.004286

[5 rows x 11 columns]
2023-07-07 16:00:03,362:INFO:s_rsrs:main.py:151:handleKline:2218689: df_s.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec  ...  index      beta    zscore  signal
719  20230706   200000    235959  1688659199  ...    719  0.249758 -0.418730     NaN
720  20230707   000000    035959  1688673599  ...    720  0.287269 -0.304465     NaN
721  20230707   040000    075959  1688687999  ...    721  0.320735 -0.195696     NaN
722  20230707   080000    115959  1688702399  ...    722  0.387131  0.007713     NaN
723  20230707   120000    155959  1688716799  ...    723  0.431824  0.158499     NaN

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '53.05', 'enterprice': '30750.9', 'countrevence': '0', 'unrealprofit': '-40249.713832044', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '29992.18720392', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-9223372036854775808, self.sign=1


