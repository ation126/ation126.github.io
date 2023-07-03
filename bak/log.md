# 20230703 16:26:01

## /root/FIL/strategy/amihud/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=373746.4768026, self.flagDict['side']='sell', self.tradeCount=2, self.count=14464
self.closeSec=1688372399, self.tradeDate='20230703', self.openTime='161500', self.closeTime='161959', self.symbol='BTCUSDT', self.open=30672.9, self.close=30641.5, self.high=30693.7, self.low=30634.8, self.vol=1368.623, self.amt=41966524.7888 
127.0.0.1 - - [03/Jul/2023 16:20:01] "POST / HTTP/1.1" 200 -
2023-07-03 16:20:07,782:INFO:amihud:main.py:172:handleKline:2219019: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5951  20230703   155500    155959  ...         0.0        0.0       0
5952  20230703   160000    160459  ...         0.0        0.0       0
5953  20230703   160500    160959  ...         0.0        0.0       0
5954  20230703   161000    161459  ...         0.0        0.0       0
5955  20230703   161500    161959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-07-03 16:20:07,804:INFO:amihud:main.py:175:handleKline:2219019: self.closeSec=1688372399, self.tradeDate='20230703', self.openTime='161500', self.closeTime='161959',self.symbol='BTCUSDT',self.open=30672.9, self.close=30641.5, self.high=30693.7, self.low=30634.8, self.vol=1368.623, self.amt=41966524.7888, ukdf['pct'].iloc[-1]=-0.00102 , ukdf['amount'].iloc[-1]=41966524.7888, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5955, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '13.926', 'enterprice': '26864.9', 'countrevence': '0', 'unrealprofit': '-52530.01844653068', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '30636.98232418', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1
127.0.0.1 - - [03/Jul/2023 16:25:00] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=373746.4768026, self.flagDict['side']='sell', self.tradeCount=2, self.count=14465
self.closeSec=1688372699, self.tradeDate='20230703', self.openTime='162000', self.closeTime='162459', self.symbol='BTCUSDT', self.open=30641.6, self.close=30632.4, self.high=30641.6, self.low=30601.7, self.vol=2048.503, self.amt=62733641.319 
2023-07-03 16:25:00,754:INFO:amihud:main.py:172:handleKline:2219019: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5952  20230703   160000    160459  ...         0.0        0.0       0
5953  20230703   160500    160959  ...         0.0        0.0       0
5954  20230703   161000    161459  ...         0.0        0.0       0
5955  20230703   161500    161959  ...         0.0        0.0       0
5956  20230703   162000    162459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-07-03 16:25:00,755:INFO:amihud:main.py:175:handleKline:2219019: self.closeSec=1688372699, self.tradeDate='20230703', self.openTime='162000', self.closeTime='162459',self.symbol='BTCUSDT',self.open=30641.6, self.close=30632.4, self.high=30641.6, self.low=30601.7, self.vol=2048.503, self.amt=62733641.319, ukdf['pct'].iloc[-1]=-0.000297 , ukdf['amount'].iloc[-1]=62733641.319, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5956, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '13.926', 'enterprice': '26864.9', 'countrevence': '0', 'unrealprofit': '-52432.7826', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '30630', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1


## /root/FIL/strategy/factorcheck/log.txt ----- -----


self.closeSec=1688372399, self.tradeDate='20230703', self.openTime='161500', self.closeTime='161959', self.symbol='BTCUSDT', self.open=30672.9, self.close=30641.5, self.high=30693.7, self.low=30634.8 
127.0.0.1 - - [03/Jul/2023 16:20:01] "POST / HTTP/1.1" 200 -
2023-07-03 16:20:05,193:INFO:factorcheck2:main.py:126:handleKline:2218005: self.closeSec=1688372399, self.tradeDate='20230703', self.openTime='161500', self.closeTime='161959',self.symbol='BTCUSDT',self.open=30672.9, self.close=30641.5, self.high=30693.7, self.low=30634.8   
2023-07-03 16:20:06,794:INFO:factorcheck2:main.py:127:handleKline:2218005: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1631  20230703   155500    155959  1688371199  ...  30650.4  0.000186   1631    5
1632  20230703   160000    160459  1688371499  ...  30642.0 -0.000003   1632    0
1633  20230703   160500    160959  1688371799  ...  30656.2  0.000682   1633    1
1634  20230703   161000    161459  1688372099  ...  30667.3 -0.000355   1634    2
1635  20230703   161500    161959  1688372399  ...  30634.8 -0.001020   1635    3

[5 rows x 11 columns]
2023-07-03 16:20:06,812:INFO:factorcheck2:main.py:128:handleKline:2218005: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=142, self.factor=0.3478192959264593, self.count=14467 

self.closeSec=1688372699, self.tradeDate='20230703', self.openTime='162000', self.closeTime='162459', self.symbol='BTCUSDT', self.open=30641.6, self.close=30632.4, self.high=30641.6, self.low=30601.7 
127.0.0.1 - - [03/Jul/2023 16:25:00] "POST / HTTP/1.1" 200 -
2023-07-03 16:25:00,762:INFO:factorcheck2:main.py:126:handleKline:2218005: self.closeSec=1688372699, self.tradeDate='20230703', self.openTime='162000', self.closeTime='162459',self.symbol='BTCUSDT',self.open=30641.6, self.close=30632.4, self.high=30641.6, self.low=30601.7   
2023-07-03 16:25:00,789:INFO:factorcheck2:main.py:127:handleKline:2218005: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1632  20230703   160000    160459  1688371499  ...  30642.0 -0.000003   1632    0
1633  20230703   160500    160959  1688371799  ...  30656.2  0.000682   1633    1
1634  20230703   161000    161459  1688372099  ...  30667.3 -0.000355   1634    2
1635  20230703   161500    161959  1688372399  ...  30634.8 -0.001020   1635    3
1636  20230703   162000    162459  1688372699  ...  30601.7 -0.000297   1636    4

[5 rows x 11 columns]
2023-07-03 16:25:00,789:INFO:factorcheck2:main.py:128:handleKline:2218005: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}


## /root/FIL/strategy/logic/log.txt ----- -----

2023-07-03 16:00:17,120:DEBUG:logic:main.py:463:getModel:2218526: df_s.iloc[-5:,:] :
          date closeTime     open  ...    alpha58   alpha67   alpha72
5786  20230703    132959  30676.4  ...  53.333333  0.536058  0.253614
5787  20230703    135959  30690.1  ...  52.916667  0.528207  0.250663
5788  20230703    142959  30663.9  ...  52.916667  0.519118  0.251057
5789  20230703    145959  30633.1  ...  53.333333  0.521580  0.250502
5790  20230703    152959  30642.2  ...  53.750000  0.539110  0.243267

[5 rows x 33 columns]
0.5295202952029521
acc is : 0.5295202952029521
2023-07-03 16:00:17,212:INFO:logic:main.py:468:getModel:2218526: df_pred.iloc[-5:,:] :
     pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
537     0  0.512683  0.487317       0  ...  0.979794   1.0    0.0  1.017673
538     0  0.505158  0.494842       0  ...  0.978813   1.0    0.0  1.016654
539     0  0.500407  0.499593       1  ...  0.979100   1.0    0.0  1.016952
540     0  0.509673  0.490327       1  ...  0.981193   1.0    0.0  1.019126
541     0  0.526751  0.473249       0  ...  0.979759   1.0    0.0  1.017636

[5 rows x 10 columns]
2023-07-03 16:00:17,239:INFO:logic:main.py:478:getModel:2218526: df_panel.iloc[-5:,:] :
    pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
45     0  0.512464  0.487536       0  ...  0.979794   1.0    0.0  1.018663
46     0  0.504757  0.495243       0  ...  0.978813   1.0    0.0  1.017039
47     0  0.500667  0.499333       1  ...  0.979100   1.0    0.0  1.021802
48     0  0.509257  0.490743       1  ...  0.981193   1.0    0.0  1.018224
49     0  0.526751  0.473249       0  ...  0.979759   1.0    0.0  1.017636

[5 rows x 10 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '25.53', 'enterprice': '30560', 'countrevence': '0', 'unrealprofit': '2623.2083417241', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '30662.75003297', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}


## /root/FIL/strategy/modifiedmom/log.txt ----- -----

527  20230703   155000    155959  1688371199  30693.8  30662.8 -0.001007
2023-07-03 16:00:02,081:INFO:modifiedmom:main.py:146:handleKline:2218259: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True}

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=7232 

self.closeSec=1688371799, self.tradeDate='20230703', self.openTime='160000', self.closeTime='160959', self.symbol='BTCUSDT', self.open='30662.9', self.close='30683.7'
2023-07-03 16:10:01,106:INFO:modifiedmom:main.py:144:handleKline:2218259: self.closeSec=1688371799, self.tradeDate='20230703', self.openTime='160000', self.closeTime='160959',self.symbol='BTCUSDT',self.open='30662.9', self.close='30683.7'
127.0.0.1 - - [03/Jul/2023 16:10:01] "POST / HTTP/1.1" 200 -
2023-07-03 16:10:01,121:INFO:modifiedmom:main.py:145:handleKline:2218259: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
524  20230703   152000    152959  1688369399  30678.9  30707.7  0.000939
525  20230703   153000    153959  1688369999  30707.7  30738.6  0.001006
526  20230703   154000    154959  1688370599  30738.1  30693.7 -0.001461
527  20230703   155000    155959  1688371199  30693.8  30662.8 -0.001007
528  20230703   160000    160959  1688371799  30662.9  30683.7  0.000682
2023-07-03 16:10:01,122:INFO:modifiedmom:main.py:146:handleKline:2218259: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True}

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=7233 

self.closeSec=1688372399, self.tradeDate='20230703', self.openTime='161000', self.closeTime='161959', self.symbol='BTCUSDT', self.open='30683.7', self.close='30641.5'
127.0.0.1 - - [03/Jul/2023 16:20:04] "POST / HTTP/1.1" 200 -
2023-07-03 16:20:07,763:INFO:modifiedmom:main.py:144:handleKline:2218259: self.closeSec=1688372399, self.tradeDate='20230703', self.openTime='161000', self.closeTime='161959',self.symbol='BTCUSDT',self.open='30683.7', self.close='30641.5'
2023-07-03 16:20:08,633:INFO:modifiedmom:main.py:145:handleKline:2218259: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
525  20230703   153000    153959  1688369999  30707.7  30738.6  0.001006
526  20230703   154000    154959  1688370599  30738.1  30693.7 -0.001461
527  20230703   155000    155959  1688371199  30693.8  30662.8 -0.001007
528  20230703   160000    160959  1688371799  30662.9  30683.7  0.000682
529  20230703   161000    161959  1688372399  30683.7  30641.5 -0.001375
2023-07-03 16:20:08,642:INFO:modifiedmom:main.py:146:handleKline:2218259: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True}


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

17519  20230703   155000    155959  1688371199  30693.8  30662.8
2023-07-03 16:00:02,085:INFO:pyemd2:main.py:127:handleKline:2217508: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}
127.0.0.1 - - [03/Jul/2023 16:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=7235 

self.closeSec=1688371799, self.tradeDate='20230703', self.openTime='160000', self.closeTime='160959', self.symbol='BTCUSDT', self.open='30662.9', self.close='30683.7'
2023-07-03 16:10:01,120:INFO:pyemd2:main.py:125:handleKline:2217508: self.closeSec=1688371799, self.tradeDate='20230703', self.openTime='160000', self.closeTime='160959',self.symbol='BTCUSDT',self.open='30662.9', self.close='30683.7'
2023-07-03 16:10:01,130:INFO:pyemd2:main.py:126:handleKline:2217508: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17516  20230703   152000    152959  1688369399  30678.9  30707.7
17517  20230703   153000    153959  1688369999  30707.7  30738.6
17518  20230703   154000    154959  1688370599  30738.1  30693.7
17519  20230703   155000    155959  1688371199  30693.8  30662.8
17520  20230703   160000    160959  1688371799  30662.9  30683.7
2023-07-03 16:10:01,131:INFO:pyemd2:main.py:127:handleKline:2217508: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=7236 

self.closeSec=1688372399, self.tradeDate='20230703', self.openTime='161000', self.closeTime='161959', self.symbol='BTCUSDT', self.open='30683.7', self.close='30641.5'
127.0.0.1 - - [03/Jul/2023 16:20:05] "POST / HTTP/1.1" 200 -
2023-07-03 16:20:09,788:INFO:pyemd2:main.py:125:handleKline:2217508: self.closeSec=1688372399, self.tradeDate='20230703', self.openTime='161000', self.closeTime='161959',self.symbol='BTCUSDT',self.open='30683.7', self.close='30641.5'
2023-07-03 16:20:09,931:INFO:pyemd2:main.py:126:handleKline:2217508: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17517  20230703   153000    153959  1688369999  30707.7  30738.6
17518  20230703   154000    154959  1688370599  30738.1  30693.7
17519  20230703   155000    155959  1688371199  30693.8  30662.8
17520  20230703   160000    160959  1688371799  30662.9  30683.7
17521  20230703   161000    161959  1688372399  30683.7  30641.5
2023-07-03 16:20:09,931:INFO:pyemd2:main.py:127:handleKline:2217508: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}


## /root/FIL/strategy/similarity/log.txt ----- -----

12191  20230703   155000    155959  1688371199  30693.8  30662.8
2023-07-03 16:00:02,084:INFO:testStrategy:main.py:103:handleKline:2217133: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': True, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=7235 

self.closeSec=1688371799, self.tradeDate='20230703', self.openTime='160000', self.closeTime='160959', self.symbol='BTCUSDT', self.open='30662.9', self.close='30683.7'
2023-07-03 16:10:01,100:INFO:testStrategy:main.py:101:handleKline:2217133: self.closeSec=1688371799, self.tradeDate='20230703', self.openTime='160000', self.closeTime='160959',self.symbol='BTCUSDT',self.open='30662.9', self.close='30683.7'
127.0.0.1 - - [03/Jul/2023 16:10:01] "POST / HTTP/1.1" 200 -
2023-07-03 16:10:01,122:INFO:testStrategy:main.py:102:handleKline:2217133: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12188  20230703   152000    152959  1688369399  30678.9  30707.7
12189  20230703   153000    153959  1688369999  30707.7  30738.6
12190  20230703   154000    154959  1688370599  30738.1  30693.7
12191  20230703   155000    155959  1688371199  30693.8  30662.8
12192  20230703   160000    160959  1688371799  30662.9  30683.7
2023-07-03 16:10:01,123:INFO:testStrategy:main.py:103:handleKline:2217133: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': True, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=7236 

self.closeSec=1688372399, self.tradeDate='20230703', self.openTime='161000', self.closeTime='161959', self.symbol='BTCUSDT', self.open='30683.7', self.close='30641.5'
127.0.0.1 - - [03/Jul/2023 16:20:05] "POST / HTTP/1.1" 200 -
2023-07-03 16:20:09,354:INFO:testStrategy:main.py:101:handleKline:2217133: self.closeSec=1688372399, self.tradeDate='20230703', self.openTime='161000', self.closeTime='161959',self.symbol='BTCUSDT',self.open='30683.7', self.close='30641.5'
2023-07-03 16:20:09,674:INFO:testStrategy:main.py:102:handleKline:2217133: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12189  20230703   153000    153959  1688369999  30707.7  30738.6
12190  20230703   154000    154959  1688370599  30738.1  30693.7
12191  20230703   155000    155959  1688371199  30693.8  30662.8
12192  20230703   160000    160959  1688371799  30662.9  30683.7
12193  20230703   161000    161959  1688372399  30683.7  30641.5
2023-07-03 16:20:09,682:INFO:testStrategy:main.py:103:handleKline:2217133: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': True, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}


## /root/FIL/strategy/sr_min/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=1, self.total=996015.990996, self.flagDict['side']='buy', self.tradeCount=1, self.count=14464
self.closeSec=1688372399, self.tradeDate='20230703', self.openTime='161500', self.closeTime='161959', self.symbol='BTCUSDT', self.open=30672.9, self.close=30641.5, self.high=30693.7, self.low=30634.8, self.vol=1368.623, self.amt=41966524.7888 
127.0.0.1 - - [03/Jul/2023 16:20:01] "POST / HTTP/1.1" 200 -
2023-07-03 16:20:07,774:INFO:sr_min:main.py:172:handleKline:2219263: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5951  20230703   155500    155959  ...         0.0        0.0       0
5952  20230703   160000    160459  ...         0.0        0.0       0
5953  20230703   160500    160959  ...         0.0        0.0       0
5954  20230703   161000    161459  ...         0.0        0.0       0
5955  20230703   161500    161959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-07-03 16:20:07,804:INFO:sr_min:main.py:175:handleKline:2219263: self.closeSec=1688372399, self.tradeDate='20230703', self.openTime='161500', self.closeTime='161959',self.symbol='BTCUSDT',self.open=30672.9, self.close=30641.5, self.high=30693.7, self.low=30634.8, self.vol=1368.623, self.amt=41966524.7888, ukdf['pct'].iloc[-1]=-0.00102 , ukdf['amount'].iloc[-1]=41966524.7888, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5955, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '37.141', 'enterprice': '26844', 'countrevence': '0', 'unrealprofit': '140878.62163510408', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '30637.07562088', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=1
127.0.0.1 - - [03/Jul/2023 16:25:00] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=1, self.total=996015.990996, self.flagDict['side']='buy', self.tradeCount=1, self.count=14465
self.closeSec=1688372699, self.tradeDate='20230703', self.openTime='162000', self.closeTime='162459', self.symbol='BTCUSDT', self.open=30641.6, self.close=30632.4, self.high=30641.6, self.low=30601.7, self.vol=2048.503, self.amt=62733641.319 
2023-07-03 16:25:00,800:INFO:sr_min:main.py:172:handleKline:2219263: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5952  20230703   160000    160459  ...         0.0        0.0       0
5953  20230703   160500    160959  ...         0.0        0.0       0
5954  20230703   161000    161459  ...         0.0        0.0       0
5955  20230703   161500    161959  ...         0.0        0.0       0
5956  20230703   162000    162459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-07-03 16:25:00,801:INFO:sr_min:main.py:175:handleKline:2219263: self.closeSec=1688372699, self.tradeDate='20230703', self.openTime='162000', self.closeTime='162459',self.symbol='BTCUSDT',self.open=30641.6, self.close=30632.4, self.high=30641.6, self.low=30601.7, self.vol=2048.503, self.amt=62733641.319, ukdf['pct'].iloc[-1]=-0.000297 , ukdf['amount'].iloc[-1]=62733641.319, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5956, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '37.141', 'enterprice': '26844', 'countrevence': '0', 'unrealprofit': '140615.826', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '30630', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=1


## /root/FIL/strategy/s_rsrs/log.txt ----- -----

721  20230703   040000    075959  1688342399  ...    721  0.000300 -1.227609    -1.0
722  20230703   080000    115959  1688356799  ...    722  0.000001 -1.203165    -1.0

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '53.268', 'enterprice': '30707', 'countrevence': '0', 'unrealprofit': '-2183.988', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '30748', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-1, self.sign=-1
127.0.0.1 - - [03/Jul/2023 16:00:01] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='s_rsrs', self.symbol='BTCUSDT', interval='4h', intervalSec=14400, wid=25, thd=0.6, self.sign=-1, self.total=1634064.775524, self.flagDict['side']='sell', self.tradeCount=8, self.count=301
self.closeSec=1688371199, self.tradeDate='20230703', self.openTime='120000', self.closeTime='155959', self.symbol='BTCUSDT', self.open=30748.0, self.close=30662.8, self.high=30785.3, self.low=30601.7, self.vol=33689.441, self.amt=1033808647.395 
2023-07-03 16:00:01,643:INFO:s_rsrs:main.py:141:handleKline:2218689: self.closeSec=1688371199, self.tradeDate='20230703', self.openTime='120000', self.closeTime='155959',self.symbol='BTCUSDT',self.open=30748.0, self.close=30662.8, self.high=30785.3, self.low=30601.7, self.vol=33689.441, self.amt=1033808647.395 
2023-07-03 16:00:01,696:INFO:s_rsrs:main.py:142:handleKline:2218689: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime  ...        vol           amt       pct
719  20230702   200000    235959  ...  61816.394  1.882440e+09 -0.001497
720  20230703   000000    035959  ...  47231.098  1.441850e+09  0.002010
721  20230703   040000    075959  ...  65600.069  2.008247e+09  0.001961
722  20230703   080000    115959  ...  35710.618  1.096408e+09  0.004416
723  20230703   120000    155959  ...  33689.441  1.033809e+09 -0.002768

[5 rows x 11 columns]
2023-07-03 16:00:03,070:INFO:s_rsrs:main.py:151:handleKline:2218689: df_s.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec  ...  index      beta    zscore  signal
719  20230702   200000    235959  1688313599  ...    719  0.001147 -1.277853    -1.0
720  20230703   000000    035959  1688327999  ...    720  0.000765 -1.252254    -1.0
721  20230703   040000    075959  1688342399  ...    721  0.000300 -1.227609    -1.0
722  20230703   080000    115959  1688356799  ...    722  0.000001 -1.203165    -1.0
723  20230703   120000    155959  1688371199  ...    723  0.000010 -1.178390    -1.0

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '53.268', 'enterprice': '30707', 'countrevence': '0', 'unrealprofit': '2338.4652', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '30663.1', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-1, self.sign=-1


