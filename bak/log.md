# 20230606 16:26:02

## /root/FIL/strategy/amihud/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=373746.4768026, self.flagDict['side']='sell', self.tradeCount=2, self.count=6688
self.closeSec=1686039599, self.tradeDate='20230606', self.openTime='161500', self.closeTime='161959', self.symbol='BTCUSDT', self.open=25690.5, self.close=25667.9, self.high=25694.7, self.low=25667.0, self.vol=1663.188, self.amt=42707043.4065 
127.0.0.1 - - [06/Jun/2023 16:20:02] "POST / HTTP/1.1" 200 -
2023-06-06 16:20:08,400:INFO:amihud:main.py:172:handleKline:2219019: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5951  20230606   155500    155959  ...         0.0        0.0       0
5952  20230606   160000    160459  ...         0.0        0.0       0
5953  20230606   160500    160959  ...         0.0        0.0       0
5954  20230606   161000    161459  ...         0.0        0.0       0
5955  20230606   161500    161959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-06-06 16:20:08,422:INFO:amihud:main.py:175:handleKline:2219019: self.closeSec=1686039599, self.tradeDate='20230606', self.openTime='161500', self.closeTime='161959',self.symbol='BTCUSDT',self.open=25690.5, self.close=25667.9, self.high=25694.7, self.low=25667.0, self.vol=1663.188, self.amt=42707043.4065, ukdf['pct'].iloc[-1]=-0.00088 , ukdf['amount'].iloc[-1]=42707043.4065, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5955, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '13.926', 'enterprice': '26864.9', 'countrevence': '0', 'unrealprofit': '16648.20135495594', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '25669.42381481', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1
--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=373746.4768026, self.flagDict['side']='sell', self.tradeCount=2, self.count=6689
self.closeSec=1686039899, self.tradeDate='20230606', self.openTime='162000', self.closeTime='162459', self.symbol='BTCUSDT', self.open=25667.9, self.close=25663.1, self.high=25688.7, self.low=25659.9, self.vol=1307.081, self.amt=33556918.514 
127.0.0.1 - - [06/Jun/2023 16:25:00] "POST / HTTP/1.1" 200 -
2023-06-06 16:25:00,823:INFO:amihud:main.py:172:handleKline:2219019: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5952  20230606   160000    160459  ...         0.0        0.0       0
5953  20230606   160500    160959  ...         0.0        0.0       0
5954  20230606   161000    161459  ...         0.0        0.0       0
5955  20230606   161500    161959  ...         0.0        0.0       0
5956  20230606   162000    162459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-06-06 16:25:00,823:INFO:amihud:main.py:175:handleKline:2219019: self.closeSec=1686039899, self.tradeDate='20230606', self.openTime='162000', self.closeTime='162459',self.symbol='BTCUSDT',self.open=25667.9, self.close=25663.1, self.high=25688.7, self.low=25659.9, self.vol=1307.081, self.amt=33556918.514, ukdf['pct'].iloc[-1]=-0.000187 , ukdf['amount'].iloc[-1]=33556918.514, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5956, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '13.926', 'enterprice': '26864.9', 'countrevence': '0', 'unrealprofit': '16734.8742', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '25663.2', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1


## /root/FIL/strategy/factorcheck/log.txt ----- -----


self.closeSec=1686039599, self.tradeDate='20230606', self.openTime='161500', self.closeTime='161959', self.symbol='BTCUSDT', self.open=25690.5, self.close=25667.9, self.high=25694.7, self.low=25667.0 
127.0.0.1 - - [06/Jun/2023 16:20:02] "POST / HTTP/1.1" 200 -
2023-06-06 16:20:05,584:INFO:factorcheck2:main.py:126:handleKline:2218005: self.closeSec=1686039599, self.tradeDate='20230606', self.openTime='161500', self.closeTime='161959',self.symbol='BTCUSDT',self.open=25690.5, self.close=25667.9, self.high=25694.7, self.low=25667.0   
2023-06-06 16:20:07,273:INFO:factorcheck2:main.py:127:handleKline:2218005: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1631  20230606   155500    155959  1686038399  ...  25701.9 -0.000894   1631    5
1632  20230606   160000    160459  1686038699  ...  25706.3  0.000692   1632    0
1633  20230606   160500    160959  1686038999  ...  25724.1  0.000152   1633    1
1634  20230606   161000    161459  1686039299  ...  25681.0 -0.001461   1634    2
1635  20230606   161500    161959  1686039599  ...  25667.0 -0.000880   1635    3

[5 rows x 11 columns]
2023-06-06 16:20:07,283:INFO:factorcheck2:main.py:128:handleKline:2218005: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': False, 'isOpen': True, 'isClose': False, 'isTrig': True}
127.0.0.1 - - [06/Jun/2023 16:25:00] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.7614121268639193, self.count=6691 

self.closeSec=1686039899, self.tradeDate='20230606', self.openTime='162000', self.closeTime='162459', self.symbol='BTCUSDT', self.open=25667.9, self.close=25663.1, self.high=25688.7, self.low=25659.9 
2023-06-06 16:25:00,728:INFO:factorcheck2:main.py:126:handleKline:2218005: self.closeSec=1686039899, self.tradeDate='20230606', self.openTime='162000', self.closeTime='162459',self.symbol='BTCUSDT',self.open=25667.9, self.close=25663.1, self.high=25688.7, self.low=25659.9   
2023-06-06 16:25:00,774:INFO:factorcheck2:main.py:127:handleKline:2218005: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1632  20230606   160000    160459  1686038699  ...  25706.3  0.000692   1632    0
1633  20230606   160500    160959  1686038999  ...  25724.1  0.000152   1633    1
1634  20230606   161000    161459  1686039299  ...  25681.0 -0.001461   1634    2
1635  20230606   161500    161959  1686039599  ...  25667.0 -0.000880   1635    3
1636  20230606   162000    162459  1686039899  ...  25659.9 -0.000187   1636    4

[5 rows x 11 columns]
2023-06-06 16:25:00,774:INFO:factorcheck2:main.py:128:handleKline:2218005: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': False, 'isOpen': True, 'isClose': False, 'isTrig': True}


## /root/FIL/strategy/logic/log.txt ----- -----

2023-06-06 16:00:33,942:DEBUG:logic:main.py:463:getModel:2218526: df_s.iloc[-5:,:] :
          date closeTime     open  ...    alpha58   alpha67   alpha72
5786  20230606    132959  25785.0  ...  45.416667  0.362111  0.787100
5787  20230606    135959  25750.1  ...  45.416667  0.363484  0.783116
5788  20230606    142959  25755.5  ...  45.416667  0.362343  0.779747
5789  20230606    145959  25747.9  ...  45.833333  0.363630  0.776382
5790  20230606    152959  25752.7  ...  45.833333  0.371026  0.771982

[5 rows x 33 columns]
0.511070110701107
acc is : 0.511070110701107
2023-06-06 16:00:34,094:INFO:logic:main.py:468:getModel:2218526: df_pred.iloc[-5:,:] :
     pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
537     0  0.513574  0.486426       1  ...  1.065824   1.0    0.0  0.973334
538     0  0.522638  0.477362       0  ...  1.065510   1.0    0.0  0.973047
539     0  0.517665  0.482335       1  ...  1.065708   1.0    0.0  0.973229
540     0  0.509422  0.490578       1  ...  1.066842   1.0    0.0  0.974264
541     0  0.510685  0.489315       0  ...  1.063796   1.0    0.0  0.971483

[5 rows x 10 columns]
2023-06-06 16:00:34,115:INFO:logic:main.py:478:getModel:2218526: df_panel.iloc[-5:,:] :
    pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
45     0  0.513592  0.486408       1  ...  1.065824   1.0    0.0  0.973909
46     0  0.522589  0.477411       0  ...  1.065510   1.0    0.0  0.972187
47     0  0.517663  0.482337       1  ...  1.065708   1.0    0.0  0.973199
48     0  0.509309  0.490691       1  ...  1.066842   1.0    0.0  0.973675
49     0  0.510685  0.489315       0  ...  1.063796   1.0    0.0  0.971483

[5 rows x 10 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '28.054', 'enterprice': '25722.1', 'countrevence': '0', 'unrealprofit': '-244.3700815998', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '25713.3892963', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}


## /root/FIL/strategy/modifiedmom/log.txt ----- -----

527  20230606   155000    155959  1686038399  25704.9  25706.4  0.000058
2023-06-06 16:00:02,311:INFO:modifiedmom:main.py:146:handleKline:2218259: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': True, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True}
127.0.0.1 - - [06/Jun/2023 16:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=3344 

self.closeSec=1686038999, self.tradeDate='20230606', self.openTime='160000', self.closeTime='160959', self.symbol='BTCUSDT', self.open='25706.3', self.close='25728.1'
2023-06-06 16:10:01,175:INFO:modifiedmom:main.py:144:handleKline:2218259: self.closeSec=1686038999, self.tradeDate='20230606', self.openTime='160000', self.closeTime='160959',self.symbol='BTCUSDT',self.open='25706.3', self.close='25728.1'
2023-06-06 16:10:01,213:INFO:modifiedmom:main.py:145:handleKline:2218259: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
524  20230606   152000    152959  1686036599  25775.3    25780  0.000182
525  20230606   153000    153959  1686037199  25780.1  25754.5 -0.000989
526  20230606   154000    154959  1686037799  25754.6  25704.9 -0.001926
527  20230606   155000    155959  1686038399  25704.9  25706.4  0.000058
528  20230606   160000    160959  1686038999  25706.3  25728.1  0.000844
2023-06-06 16:10:01,213:INFO:modifiedmom:main.py:146:handleKline:2218259: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': True, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True}

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=3345 

self.closeSec=1686039599, self.tradeDate='20230606', self.openTime='161000', self.closeTime='161959', self.symbol='BTCUSDT', self.open='25728.2', self.close='25667.9'
127.0.0.1 - - [06/Jun/2023 16:20:04] "POST / HTTP/1.1" 200 -
2023-06-06 16:20:07,966:INFO:modifiedmom:main.py:144:handleKline:2218259: self.closeSec=1686039599, self.tradeDate='20230606', self.openTime='161000', self.closeTime='161959',self.symbol='BTCUSDT',self.open='25728.2', self.close='25667.9'
2023-06-06 16:20:08,793:INFO:modifiedmom:main.py:145:handleKline:2218259: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
525  20230606   153000    153959  1686037199  25780.1  25754.5 -0.000989
526  20230606   154000    154959  1686037799  25754.6  25704.9 -0.001926
527  20230606   155000    155959  1686038399  25704.9  25706.4  0.000058
528  20230606   160000    160959  1686038999  25706.3  25728.1  0.000844
529  20230606   161000    161959  1686039599  25728.2  25667.9 -0.002340
2023-06-06 16:20:08,794:INFO:modifiedmom:main.py:146:handleKline:2218259: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': True, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True}


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

17519  20230606   155000    155959  1686038399  25704.9  25706.4
2023-06-06 16:00:02,352:INFO:pyemd2:main.py:127:handleKline:2217508: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}
127.0.0.1 - - [06/Jun/2023 16:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=3347 

self.closeSec=1686038999, self.tradeDate='20230606', self.openTime='160000', self.closeTime='160959', self.symbol='BTCUSDT', self.open='25706.3', self.close='25728.1'
2023-06-06 16:10:01,166:INFO:pyemd2:main.py:125:handleKline:2217508: self.closeSec=1686038999, self.tradeDate='20230606', self.openTime='160000', self.closeTime='160959',self.symbol='BTCUSDT',self.open='25706.3', self.close='25728.1'
2023-06-06 16:10:01,205:INFO:pyemd2:main.py:126:handleKline:2217508: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17516  20230606   152000    152959  1686036599  25775.3    25780
17517  20230606   153000    153959  1686037199  25780.1  25754.5
17518  20230606   154000    154959  1686037799  25754.6  25704.9
17519  20230606   155000    155959  1686038399  25704.9  25706.4
17520  20230606   160000    160959  1686038999  25706.3  25728.1
2023-06-06 16:10:01,205:INFO:pyemd2:main.py:127:handleKline:2217508: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=3348 

self.closeSec=1686039599, self.tradeDate='20230606', self.openTime='161000', self.closeTime='161959', self.symbol='BTCUSDT', self.open='25728.2', self.close='25667.9'
127.0.0.1 - - [06/Jun/2023 16:20:05] "POST / HTTP/1.1" 200 -
2023-06-06 16:20:10,095:INFO:pyemd2:main.py:125:handleKline:2217508: self.closeSec=1686039599, self.tradeDate='20230606', self.openTime='161000', self.closeTime='161959',self.symbol='BTCUSDT',self.open='25728.2', self.close='25667.9'
2023-06-06 16:20:10,251:INFO:pyemd2:main.py:126:handleKline:2217508: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17517  20230606   153000    153959  1686037199  25780.1  25754.5
17518  20230606   154000    154959  1686037799  25754.6  25704.9
17519  20230606   155000    155959  1686038399  25704.9  25706.4
17520  20230606   160000    160959  1686038999  25706.3  25728.1
17521  20230606   161000    161959  1686039599  25728.2  25667.9
2023-06-06 16:20:10,251:INFO:pyemd2:main.py:127:handleKline:2217508: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}


## /root/FIL/strategy/similarity/log.txt ----- -----

12191  20230606   155000    155959  1686038399  25704.9  25706.4
2023-06-06 16:00:02,370:INFO:testStrategy:main.py:103:handleKline:2217133: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': True, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=3347 

self.closeSec=1686038999, self.tradeDate='20230606', self.openTime='160000', self.closeTime='160959', self.symbol='BTCUSDT', self.open='25706.3', self.close='25728.1'
2023-06-06 16:10:01,182:INFO:testStrategy:main.py:101:handleKline:2217133: self.closeSec=1686038999, self.tradeDate='20230606', self.openTime='160000', self.closeTime='160959',self.symbol='BTCUSDT',self.open='25706.3', self.close='25728.1'
127.0.0.1 - - [06/Jun/2023 16:10:01] "POST / HTTP/1.1" 200 -
2023-06-06 16:10:01,211:INFO:testStrategy:main.py:102:handleKline:2217133: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12188  20230606   152000    152959  1686036599  25775.3    25780
12189  20230606   153000    153959  1686037199  25780.1  25754.5
12190  20230606   154000    154959  1686037799  25754.6  25704.9
12191  20230606   155000    155959  1686038399  25704.9  25706.4
12192  20230606   160000    160959  1686038999  25706.3  25728.1
2023-06-06 16:10:01,211:INFO:testStrategy:main.py:103:handleKline:2217133: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': True, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=3348 

self.closeSec=1686039599, self.tradeDate='20230606', self.openTime='161000', self.closeTime='161959', self.symbol='BTCUSDT', self.open='25728.2', self.close='25667.9'
127.0.0.1 - - [06/Jun/2023 16:20:04] "POST / HTTP/1.1" 200 -
2023-06-06 16:20:09,745:INFO:testStrategy:main.py:101:handleKline:2217133: self.closeSec=1686039599, self.tradeDate='20230606', self.openTime='161000', self.closeTime='161959',self.symbol='BTCUSDT',self.open='25728.2', self.close='25667.9'
2023-06-06 16:20:10,065:INFO:testStrategy:main.py:102:handleKline:2217133: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12189  20230606   153000    153959  1686037199  25780.1  25754.5
12190  20230606   154000    154959  1686037799  25754.6  25704.9
12191  20230606   155000    155959  1686038399  25704.9  25706.4
12192  20230606   160000    160959  1686038999  25706.3  25728.1
12193  20230606   161000    161959  1686039599  25728.2  25667.9
2023-06-06 16:20:10,065:INFO:testStrategy:main.py:103:handleKline:2217133: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': True, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}


## /root/FIL/strategy/sr_min/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=1, self.total=996015.990996, self.flagDict['side']='buy', self.tradeCount=1, self.count=6688
self.closeSec=1686039599, self.tradeDate='20230606', self.openTime='161500', self.closeTime='161959', self.symbol='BTCUSDT', self.open=25690.5, self.close=25667.9, self.high=25694.7, self.low=25667.0, self.vol=1663.188, self.amt=42707043.4065 
127.0.0.1 - - [06/Jun/2023 16:20:01] "POST / HTTP/1.1" 200 -
2023-06-06 16:20:08,303:INFO:sr_min:main.py:172:handleKline:2219263: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5951  20230606   155500    155959  ...         0.0        0.0       0
5952  20230606   160000    160459  ...         0.0        0.0       0
5953  20230606   160500    160959  ...         0.0        0.0       0
5954  20230606   161000    161459  ...         0.0        0.0       0
5955  20230606   161500    161959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-06-06 16:20:08,343:INFO:sr_min:main.py:175:handleKline:2219263: self.closeSec=1686039599, self.tradeDate='20230606', self.openTime='161500', self.closeTime='161959',self.symbol='BTCUSDT',self.open=25690.5, self.close=25667.9, self.high=25694.7, self.low=25667.0, self.vol=1663.188, self.amt=42707043.4065, ukdf['pct'].iloc[-1]=-0.00088 , ukdf['amount'].iloc[-1]=42707043.4065, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5955, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '37.141', 'enterprice': '26844', 'countrevence': '0', 'unrealprofit': '-43624.93409414179', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '25669.42381481', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=1
127.0.0.1 - - [06/Jun/2023 16:25:00] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=1, self.total=996015.990996, self.flagDict['side']='buy', self.tradeCount=1, self.count=6689
self.closeSec=1686039899, self.tradeDate='20230606', self.openTime='162000', self.closeTime='162459', self.symbol='BTCUSDT', self.open=25667.9, self.close=25663.1, self.high=25688.7, self.low=25659.9, self.vol=1307.081, self.amt=33556918.514 
2023-06-06 16:25:00,828:INFO:sr_min:main.py:172:handleKline:2219263: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5952  20230606   160000    160459  ...         0.0        0.0       0
5953  20230606   160500    160959  ...         0.0        0.0       0
5954  20230606   161000    161459  ...         0.0        0.0       0
5955  20230606   161500    161959  ...         0.0        0.0       0
5956  20230606   162000    162459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-06-06 16:25:00,829:INFO:sr_min:main.py:175:handleKline:2219263: self.closeSec=1686039899, self.tradeDate='20230606', self.openTime='162000', self.closeTime='162459',self.symbol='BTCUSDT',self.open=25667.9, self.close=25663.1, self.high=25688.7, self.low=25659.9, self.vol=1307.081, self.amt=33556918.514, ukdf['pct'].iloc[-1]=-0.000187 , ukdf['amount'].iloc[-1]=33556918.514, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5956, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '37.141', 'enterprice': '26844', 'countrevence': '0', 'unrealprofit': '-43856.0928', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '25663.2', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=1


## /root/FIL/strategy/s_rsrs/log.txt ----- -----

721  20230606   040000    075959  1686009599  ...    721  0.439634 -0.336106     NaN
722  20230606   080000    115959  1686023999  ...    722  0.537197 -0.060082     NaN

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '55.166', 'enterprice': '27078.6', 'countrevence': '0', 'unrealprofit': '74952.70325741994', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '25719.92430741', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-9223372036854775808, self.sign=-1
--handleKline--:  version='2.0.0', self.name='s_rsrs', self.symbol='BTCUSDT', interval='4h', intervalSec=14400, wid=25, thd=0.6, self.sign=-1, self.total=1492324.2295523998, self.flagDict['side']='sell', self.tradeCount=4, self.count=139
self.closeSec=1686038399, self.tradeDate='20230606', self.openTime='120000', self.closeTime='155959', self.symbol='BTCUSDT', self.open=25719.8, self.close=25706.4, self.high=25809.9, self.low=25685.3, self.vol=32812.859, self.amt=845178734.3494 
127.0.0.1 - - [06/Jun/2023 16:00:01] "POST / HTTP/1.1" 200 -
2023-06-06 16:00:01,821:INFO:s_rsrs:main.py:141:handleKline:2218689: self.closeSec=1686038399, self.tradeDate='20230606', self.openTime='120000', self.closeTime='155959',self.symbol='BTCUSDT',self.open=25719.8, self.close=25706.4, self.high=25809.9, self.low=25685.3, self.vol=32812.859, self.amt=845178734.3494 
2023-06-06 16:00:01,853:INFO:s_rsrs:main.py:142:handleKline:2218689: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime  ...         vol           amt       pct
719  20230605   200000    235959  ...  190124.033  5.039569e+09 -0.028677
720  20230606   000000    035959  ...  269202.748  6.913467e+09 -0.014396
721  20230606   040000    075959  ...   60134.637  1.543268e+09  0.003751
722  20230606   080000    115959  ...   45585.085  1.171164e+09  0.000202
723  20230606   120000    155959  ...   32812.859  8.451787e+08 -0.000521

[5 rows x 11 columns]
2023-06-06 16:00:03,828:INFO:s_rsrs:main.py:151:handleKline:2218689: df_s.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec  ...  index      beta    zscore  signal
719  20230605   200000    235959  1685980799  ...    719  0.125043 -1.239245    -1.0
720  20230606   000000    035959  1685995199  ...    720  0.293196 -0.757018    -1.0
721  20230606   040000    075959  1686009599  ...    721  0.439634 -0.336106     NaN
722  20230606   080000    115959  1686023999  ...    722  0.537197 -0.060082     NaN
723  20230606   120000    155959  1686038399  ...    723  0.625418  0.187076     NaN

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '55.166', 'enterprice': '27078.6', 'countrevence': '0', 'unrealprofit': '75657.16756081994', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '25707.15440741', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-9223372036854775808, self.sign=-1


