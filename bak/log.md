# 20230321 16:26:01

## /root/FIL/strategy/amihud/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=993672.4896432, self.flagDict['side']='sell', self.tradeCount=2, self.count=32860
self.closeSec=1679386799, self.tradeDate='20230321', self.openTime='161500', self.closeTime='161959', self.symbol='BTCUSDT', self.open=27486.7, self.close=27463.3, self.high=27509.3, self.low=27462.0, self.vol=1121.147, self.amt=30811536.2846 
127.0.0.1 - - [21/Mar/2023 16:20:02] "POST / HTTP/1.1" 200 -
2023-03-21 16:20:05,677:INFO:amihud:main.py:172:handleKline:200676: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5951  20230321   155500    155959  ...         0.0        0.0       0
5952  20230321   160000    160459  ...         0.0        0.0       0
5953  20230321   160500    160959  ...         0.0        0.0       0
5954  20230321   161000    161459  ...         0.0        0.0       0
5955  20230321   161500    161959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-03-21 16:20:05,688:INFO:amihud:main.py:175:handleKline:200676: self.closeSec=1679386799, self.tradeDate='20230321', self.openTime='161500', self.closeTime='161959',self.symbol='BTCUSDT',self.open=27486.7, self.close=27463.3, self.high=27509.3, self.low=27462.0, self.vol=1121.147, self.amt=30811536.2846, ukdf['pct'].iloc[-1]=-0.000848 , ukdf['amount'].iloc[-1]=30811536.2846, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5955, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '60.176', 'enterprice': '16529.3', 'countrevence': '0', 'unrealprofit': '-658133.68884262496', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '27466.11349446', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1
127.0.0.1 - - [21/Mar/2023 16:25:01] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=993672.4896432, self.flagDict['side']='sell', self.tradeCount=2, self.count=32861
self.closeSec=1679387099, self.tradeDate='20230321', self.openTime='162000', self.closeTime='162459', self.symbol='BTCUSDT', self.open=27463.3, self.close=27425.1, self.high=27483.5, self.low=27425.0, self.vol=1933.807, self.amt=53094503.8245 
2023-03-21 16:25:01,578:INFO:amihud:main.py:172:handleKline:200676: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5952  20230321   160000    160459  ...         0.0        0.0       0
5953  20230321   160500    160959  ...         0.0        0.0       0
5954  20230321   161000    161459  ...         0.0        0.0       0
5955  20230321   161500    161959  ...         0.0        0.0       0
5956  20230321   162000    162459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-03-21 16:25:01,579:INFO:amihud:main.py:175:handleKline:200676: self.closeSec=1679387099, self.tradeDate='20230321', self.openTime='162000', self.closeTime='162459',self.symbol='BTCUSDT',self.open=27463.3, self.close=27425.1, self.high=27483.5, self.low=27425.0, self.vol=1933.807, self.amt=53094503.8245, ukdf['pct'].iloc[-1]=-0.001391 , ukdf['amount'].iloc[-1]=53094503.8245, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5956, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '60.176', 'enterprice': '16529.3', 'countrevence': '0', 'unrealprofit': '-655387.83708877408', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '27420.48314758', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1


## /root/FIL/strategy/factorcheck/log.txt ----- -----


self.closeSec=1679386799, self.tradeDate='20230321', self.openTime='161500', self.closeTime='161959', self.symbol='BTCUSDT', self.open=27486.7, self.close=27463.3, self.high=27509.3, self.low=27462.0 
127.0.0.1 - - [21/Mar/2023 16:20:01] "POST / HTTP/1.1" 200 -
2023-03-21 16:20:03,867:INFO:factorcheck2:main.py:126:handleKline:185239: self.closeSec=1679386799, self.tradeDate='20230321', self.openTime='161500', self.closeTime='161959',self.symbol='BTCUSDT',self.open=27486.7, self.close=27463.3, self.high=27509.3, self.low=27462.0   
2023-03-21 16:20:04,827:INFO:factorcheck2:main.py:127:handleKline:185239: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1631  20230321   155500    155959  1679385599  ...  27461.8  0.001056   1631    5
1632  20230321   160000    160459  1679385899  ...  27426.6  0.000826   1632    0
1633  20230321   160500    160959  1679386199  ...  27502.4 -0.000167   1633    1
1634  20230321   161000    161459  1679386499  ...  27460.4 -0.000814   1634    2
1635  20230321   161500    161959  1679386799  ...  27462.0 -0.000848   1635    3

[5 rows x 11 columns]
2023-03-21 16:20:04,828:INFO:factorcheck2:main.py:128:handleKline:185239: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=188, self.factor=0.46758506713886777, self.count=33427 

self.closeSec=1679387099, self.tradeDate='20230321', self.openTime='162000', self.closeTime='162459', self.symbol='BTCUSDT', self.open=27463.3, self.close=27425.1, self.high=27483.5, self.low=27425.0 
127.0.0.1 - - [21/Mar/2023 16:25:01] "POST / HTTP/1.1" 200 -
2023-03-21 16:25:01,511:INFO:factorcheck2:main.py:126:handleKline:185239: self.closeSec=1679387099, self.tradeDate='20230321', self.openTime='162000', self.closeTime='162459',self.symbol='BTCUSDT',self.open=27463.3, self.close=27425.1, self.high=27483.5, self.low=27425.0   
2023-03-21 16:25:01,539:INFO:factorcheck2:main.py:127:handleKline:185239: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1632  20230321   160000    160459  1679385899  ...  27426.6  0.000826   1632    0
1633  20230321   160500    160959  1679386199  ...  27502.4 -0.000167   1633    1
1634  20230321   161000    161459  1679386499  ...  27460.4 -0.000814   1634    2
1635  20230321   161500    161959  1679386799  ...  27462.0 -0.000848   1635    3
1636  20230321   162000    162459  1679387099  ...  27425.0 -0.001391   1636    4

[5 rows x 11 columns]
2023-03-21 16:25:01,539:INFO:factorcheck2:main.py:128:handleKline:185239: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}


## /root/FIL/strategy/logic/log.txt ----- -----

2023-03-21 16:00:34,115:DEBUG:logic:main.py:463:getModel:885513: df_s.iloc[-5:,:] :
          date closeTime     open  ...    alpha58   alpha67   alpha72
5786  20230321    132959  27894.6  ...  51.250000  0.523533  0.525862
5787  20230321    135959  27865.9  ...  51.250000  0.514537  0.529332
5788  20230321    142959  27787.4  ...  50.833333  0.503803  0.540418
5789  20230321    145959  27691.8  ...  50.416667  0.495998  0.556568
5790  20230321    152959  27621.2  ...  50.000000  0.482042  0.572084

[5 rows x 33 columns]
0.5479704797047971
acc is : 0.5479704797047971
2023-03-21 16:00:34,283:INFO:logic:main.py:468:getModel:885513: df_pred.iloc[-5:,:] :
     pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
537     0  0.530241  0.469759       0  ...  1.170520   1.0    0.0  1.381853
538     0  0.507799  0.492201       0  ...  1.166497   1.0    0.0  1.377104
539     1  0.489942  0.510058       0  ...  1.163523   1.0    0.0  1.373593
540     1  0.479690  0.520310       0  ...  1.158076   1.0    0.0  1.367163
541     1  0.450141  0.549859       0  ...  1.158030   1.0    0.0  1.367108

[5 rows x 10 columns]
2023-03-21 16:00:34,314:INFO:logic:main.py:478:getModel:885513: df_panel.iloc[-5:,:] :
    pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
45     0  0.530195  0.469805       0  ...  1.176221   1.0    0.0  1.366918
46     0  0.507310  0.492690       0  ...  1.171350   1.0    0.0  1.361377
47     1  0.488917  0.511083       0  ...  1.185093   1.0    0.0  1.357425
48     1  0.479854  0.520146       0  ...  1.162890   1.0    0.0  1.365852
49     1  0.450141  0.549859       0  ...  1.158030   1.0    0.0  1.367108

[5 rows x 10 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': []}


## /root/FIL/strategy/modifiedmom/log.txt ----- -----

527  20230321   155000    155959  1679385599  27533.3  27490.9 -0.001540
2023-03-21 16:00:02,348:INFO:modifiedmom:main.py:146:handleKline:185213: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True}
127.0.0.1 - - [21/Mar/2023 16:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=16712 

self.closeSec=1679386199, self.tradeDate='20230321', self.openTime='160000', self.closeTime='160959', self.symbol='BTCUSDT', self.open='27490.9', self.close='27509'
2023-03-21 16:10:01,706:INFO:modifiedmom:main.py:144:handleKline:185213: self.closeSec=1679386199, self.tradeDate='20230321', self.openTime='160000', self.closeTime='160959',self.symbol='BTCUSDT',self.open='27490.9', self.close='27509'
2023-03-21 16:10:01,754:INFO:modifiedmom:main.py:145:handleKline:185213: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
524  20230321   152000    152959  1679383799  27436.3    27492  0.002034
525  20230321   153000    153959  1679384399  27492.1  27464.6 -0.000997
526  20230321   154000    154959  1679384999  27463.4  27533.3  0.002501
527  20230321   155000    155959  1679385599  27533.3  27490.9 -0.001540
528  20230321   160000    160959  1679386199  27490.9    27509  0.000658
2023-03-21 16:10:01,754:INFO:modifiedmom:main.py:146:handleKline:185213: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True}

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=16713 

self.closeSec=1679386799, self.tradeDate='20230321', self.openTime='161000', self.closeTime='161959', self.symbol='BTCUSDT', self.open='27509.1', self.close='27463.3'
127.0.0.1 - - [21/Mar/2023 16:20:02] "POST / HTTP/1.1" 200 -
2023-03-21 16:20:04,367:INFO:modifiedmom:main.py:144:handleKline:185213: self.closeSec=1679386799, self.tradeDate='20230321', self.openTime='161000', self.closeTime='161959',self.symbol='BTCUSDT',self.open='27509.1', self.close='27463.3'
2023-03-21 16:20:05,077:INFO:modifiedmom:main.py:145:handleKline:185213: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
525  20230321   153000    153959  1679384399  27492.1  27464.6 -0.000997
526  20230321   154000    154959  1679384999  27463.4  27533.3  0.002501
527  20230321   155000    155959  1679385599  27533.3  27490.9 -0.001540
528  20230321   160000    160959  1679386199  27490.9    27509  0.000658
529  20230321   161000    161959  1679386799  27509.1  27463.3 -0.001661
2023-03-21 16:20:05,078:INFO:modifiedmom:main.py:146:handleKline:185213: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True}


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

17519  20230321   155000    155959  1679385599  27533.3  27490.9
2023-03-21 16:00:02,360:INFO:pyemd2:main.py:127:handleKline:185189: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=16713 

self.closeSec=1679386199, self.tradeDate='20230321', self.openTime='160000', self.closeTime='160959', self.symbol='BTCUSDT', self.open='27490.9', self.close='27509'
2023-03-21 16:10:01,720:INFO:pyemd2:main.py:125:handleKline:185189: self.closeSec=1679386199, self.tradeDate='20230321', self.openTime='160000', self.closeTime='160959',self.symbol='BTCUSDT',self.open='27490.9', self.close='27509'
127.0.0.1 - - [21/Mar/2023 16:10:01] "POST / HTTP/1.1" 200 -
2023-03-21 16:10:01,759:INFO:pyemd2:main.py:126:handleKline:185189: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17516  20230321   152000    152959  1679383799  27436.3    27492
17517  20230321   153000    153959  1679384399  27492.1  27464.6
17518  20230321   154000    154959  1679384999  27463.4  27533.3
17519  20230321   155000    155959  1679385599  27533.3  27490.9
17520  20230321   160000    160959  1679386199  27490.9    27509
2023-03-21 16:10:01,759:INFO:pyemd2:main.py:127:handleKline:185189: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=16714 

self.closeSec=1679386799, self.tradeDate='20230321', self.openTime='161000', self.closeTime='161959', self.symbol='BTCUSDT', self.open='27509.1', self.close='27463.3'
127.0.0.1 - - [21/Mar/2023 16:20:02] "POST / HTTP/1.1" 200 -
2023-03-21 16:20:06,839:INFO:pyemd2:main.py:125:handleKline:185189: self.closeSec=1679386799, self.tradeDate='20230321', self.openTime='161000', self.closeTime='161959',self.symbol='BTCUSDT',self.open='27509.1', self.close='27463.3'
2023-03-21 16:20:06,950:INFO:pyemd2:main.py:126:handleKline:185189: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17517  20230321   153000    153959  1679384399  27492.1  27464.6
17518  20230321   154000    154959  1679384999  27463.4  27533.3
17519  20230321   155000    155959  1679385599  27533.3  27490.9
17520  20230321   160000    160959  1679386199  27490.9    27509
17521  20230321   161000    161959  1679386799  27509.1  27463.3
2023-03-21 16:20:06,950:INFO:pyemd2:main.py:127:handleKline:185189: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}


## /root/FIL/strategy/similarity/log.txt ----- -----

12191  20230321   155000    155959  1679385599  27533.3  27490.9
2023-03-21 16:00:02,359:INFO:testStrategy:main.py:103:handleKline:185174: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': True, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}
127.0.0.1 - - [21/Mar/2023 16:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=16713 

self.closeSec=1679386199, self.tradeDate='20230321', self.openTime='160000', self.closeTime='160959', self.symbol='BTCUSDT', self.open='27490.9', self.close='27509'
2023-03-21 16:10:01,702:INFO:testStrategy:main.py:101:handleKline:185174: self.closeSec=1679386199, self.tradeDate='20230321', self.openTime='160000', self.closeTime='160959',self.symbol='BTCUSDT',self.open='27490.9', self.close='27509'
2023-03-21 16:10:01,736:INFO:testStrategy:main.py:102:handleKline:185174: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12188  20230321   152000    152959  1679383799  27436.3    27492
12189  20230321   153000    153959  1679384399  27492.1  27464.6
12190  20230321   154000    154959  1679384999  27463.4  27533.3
12191  20230321   155000    155959  1679385599  27533.3  27490.9
12192  20230321   160000    160959  1679386199  27490.9    27509
2023-03-21 16:10:01,736:INFO:testStrategy:main.py:103:handleKline:185174: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': True, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=16714 

self.closeSec=1679386799, self.tradeDate='20230321', self.openTime='161000', self.closeTime='161959', self.symbol='BTCUSDT', self.open='27509.1', self.close='27463.3'
127.0.0.1 - - [21/Mar/2023 16:20:02] "POST / HTTP/1.1" 200 -
2023-03-21 16:20:06,378:INFO:testStrategy:main.py:101:handleKline:185174: self.closeSec=1679386799, self.tradeDate='20230321', self.openTime='161000', self.closeTime='161959',self.symbol='BTCUSDT',self.open='27509.1', self.close='27463.3'
2023-03-21 16:20:06,637:INFO:testStrategy:main.py:102:handleKline:185174: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12189  20230321   153000    153959  1679384399  27492.1  27464.6
12190  20230321   154000    154959  1679384999  27463.4  27533.3
12191  20230321   155000    155959  1679385599  27533.3  27490.9
12192  20230321   160000    160959  1679386199  27490.9    27509
12193  20230321   161000    161959  1679386799  27509.1  27463.3
2023-03-21 16:20:06,638:INFO:testStrategy:main.py:103:handleKline:185174: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': True, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}


## /root/FIL/strategy/sr_min/log.txt ----- -----

127.0.0.1 - - [21/Mar/2023 16:20:01] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=0, self.total=1000000.0, self.flagDict['side']='', self.tradeCount=0, self.count=28858
self.closeSec=1679386799, self.tradeDate='20230321', self.openTime='161500', self.closeTime='161959', self.symbol='BTCUSDT', self.open=27486.7, self.close=27463.3, self.high=27509.3, self.low=27462.0, self.vol=1121.147, self.amt=30811536.2846 
2023-03-21 16:20:01,602:INFO:sr_min:main.py:172:handleKline:449472: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5951  20230321   155500    155959  ...         0.0        0.0       0
5952  20230321   160000    160459  ...         0.0        0.0       0
5953  20230321   160500    160959  ...         0.0        0.0       0
5954  20230321   161000    161459  ...         0.0        0.0       0
5955  20230321   161500    161959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-03-21 16:20:01,604:INFO:sr_min:main.py:175:handleKline:449472: self.closeSec=1679386799, self.tradeDate='20230321', self.openTime='161500', self.closeTime='161959',self.symbol='BTCUSDT',self.open=27486.7, self.close=27463.3, self.high=27509.3, self.low=27462.0, self.vol=1121.147, self.amt=30811536.2846, ukdf['pct'].iloc[-1]=-0.000848 , ukdf['amount'].iloc[-1]=30811536.2846, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5955, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': []}
type(curSign)=<class 'int'>, curSign=0, self.sign=0
127.0.0.1 - - [21/Mar/2023 16:25:01] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=0, self.total=1000000.0, self.flagDict['side']='', self.tradeCount=0, self.count=28859
self.closeSec=1679387099, self.tradeDate='20230321', self.openTime='162000', self.closeTime='162459', self.symbol='BTCUSDT', self.open=27463.3, self.close=27425.1, self.high=27483.5, self.low=27425.0, self.vol=1933.807, self.amt=53094503.8245 
2023-03-21 16:25:01,637:INFO:sr_min:main.py:172:handleKline:449472: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5952  20230321   160000    160459  ...         0.0        0.0       0
5953  20230321   160500    160959  ...         0.0        0.0       0
5954  20230321   161000    161459  ...         0.0        0.0       0
5955  20230321   161500    161959  ...         0.0        0.0       0
5956  20230321   162000    162459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-03-21 16:25:01,639:INFO:sr_min:main.py:175:handleKline:449472: self.closeSec=1679387099, self.tradeDate='20230321', self.openTime='162000', self.closeTime='162459',self.symbol='BTCUSDT',self.open=27463.3, self.close=27425.1, self.high=27483.5, self.low=27425.0, self.vol=1933.807, self.amt=53094503.8245, ukdf['pct'].iloc[-1]=-0.001391 , ukdf['amount'].iloc[-1]=53094503.8245, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5956, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': []}
type(curSign)=<class 'int'>, curSign=0, self.sign=0


## /root/FIL/strategy/s_rsrs/log.txt ----- -----

721  20230321   040000    075959  1679356799  ...    721  0.837221  0.400174     NaN
722  20230321   080000    115959  1679371199  ...    722  0.667777 -0.085191     NaN

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '53.795', 'enterprice': '27400', 'countrevence': '0', 'unrealprofit': '20070.9145', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '27773.1', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-9223372036854775808, self.sign=1
--handleKline--:  version='2.0.0', self.name='s_rsrs', self.symbol='BTCUSDT', interval='4h', intervalSec=14400, wid=25, thd=0.6, self.sign=1, self.total=1472509.017, self.flagDict['side']='buy', self.tradeCount=26, self.count=696
self.closeSec=1679385599, self.tradeDate='20230321', self.openTime='120000', self.closeTime='155959', self.symbol='BTCUSDT', self.open=27773.1, self.close=27490.9, self.high=27960.7, self.low=27288.0, self.vol=105693.226, self.amt=2919067485.63537 
127.0.0.1 - - [21/Mar/2023 16:00:02] "POST / HTTP/1.1" 200 -
2023-03-21 16:00:02,142:INFO:s_rsrs:main.py:141:handleKline:185271: self.closeSec=1679385599, self.tradeDate='20230321', self.openTime='120000', self.closeTime='155959',self.symbol='BTCUSDT',self.open=27773.1, self.close=27490.9, self.high=27960.7, self.low=27288.0, self.vol=105693.226, self.amt=2919067485.63537 
2023-03-21 16:00:02,192:INFO:s_rsrs:main.py:142:handleKline:185271: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime  ...         vol           amt       pct
719  20230320   200000    235959  ...  185779.965  5.191857e+09 -0.017642
720  20230321   000000    035959  ...  159672.805  4.423515e+09  0.003064
721  20230321   040000    075959  ...   95371.337  2.659753e+09 -0.002175
722  20230321   080000    115959  ...   53957.050  1.500153e+09  0.002487
723  20230321   120000    155959  ...  105693.226  2.919067e+09 -0.010157

[5 rows x 11 columns]
2023-03-21 16:00:04,727:INFO:s_rsrs:main.py:151:handleKline:185271: df_s.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec  ...  index      beta    zscore  signal
719  20230320   200000    235959  1679327999  ...    719  0.950938  0.740984     1.0
720  20230321   000000    035959  1679342399  ...    720  0.897158  0.578626     NaN
721  20230321   040000    075959  1679356799  ...    721  0.837221  0.400174     NaN
722  20230321   080000    115959  1679371199  ...    722  0.667777 -0.085191     NaN
723  20230321   120000    155959  1679385599  ...    723  0.664354 -0.102804     NaN

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '53.795', 'enterprice': '27400', 'countrevence': '0', 'unrealprofit': '5562.403', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '27503.4', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-9223372036854775808, self.sign=1


