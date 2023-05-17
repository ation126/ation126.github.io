# 20230517 16:26:02

## /root/FIL/strategy/amihud/log.txt ----- -----

127.0.0.1 - - [17/May/2023 16:20:00] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=373746.4768026, self.flagDict['side']='sell', self.tradeCount=2, self.count=928
self.closeSec=1684311599, self.tradeDate='20230517', self.openTime='161500', self.closeTime='161959', self.symbol='BTCUSDT', self.open=26800.0, self.close=26786.3, self.high=26809.9, self.low=26775.0, self.vol=1675.769, self.amt=44901120.484 
2023-05-17 16:20:00,590:INFO:amihud:main.py:172:handleKline:2219019: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5951  20230517   155500    155959  ...    0.435210   0.279487       0
5952  20230517   160000    160459  ...    0.435062   0.279576       0
5953  20230517   160500    160959  ...    0.434914   0.279666       0
5954  20230517   161000    161459  ...    0.434767   0.279755       0
5955  20230517   161500    161959  ...    0.434622   0.279845       0

[5 rows x 18 columns]
2023-05-17 16:20:00,592:INFO:amihud:main.py:175:handleKline:2219019: self.closeSec=1684311599, self.tradeDate='20230517', self.openTime='161500', self.closeTime='161959',self.symbol='BTCUSDT',self.open=26800.0, self.close=26786.3, self.high=26809.9, self.low=26775.0, self.vol=1675.769, self.amt=44901120.484, ukdf['pct'].iloc[-1]=-0.000511 , ukdf['amount'].iloc[-1]=44901120.484, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5955, value=0.0, value_mean=0.4346223408434455, signal=0, value_std=0.2798450841844476 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '13.926', 'enterprice': '26864.9', 'countrevence': '0', 'unrealprofit': '1095.9762', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '26786.2', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1
127.0.0.1 - - [17/May/2023 16:25:00] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=373746.4768026, self.flagDict['side']='sell', self.tradeCount=2, self.count=929
self.closeSec=1684311899, self.tradeDate='20230517', self.openTime='162000', self.closeTime='162459', self.symbol='BTCUSDT', self.open=26786.2, self.close=26775.8, self.high=26796.1, self.low=26764.5, self.vol=1608.102, self.amt=43059133.9933 
2023-05-17 16:25:00,426:INFO:amihud:main.py:172:handleKline:2219019: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5952  20230517   160000    160459  ...    0.435062   0.279576       0
5953  20230517   160500    160959  ...    0.434914   0.279666       0
5954  20230517   161000    161459  ...    0.434767   0.279755       0
5955  20230517   161500    161959  ...    0.434622   0.279845       0
5956  20230517   162000    162459  ...    0.434484   0.279937       0

[5 rows x 18 columns]
2023-05-17 16:25:00,426:INFO:amihud:main.py:175:handleKline:2219019: self.closeSec=1684311899, self.tradeDate='20230517', self.openTime='162000', self.closeTime='162459',self.symbol='BTCUSDT',self.open=26786.2, self.close=26775.8, self.high=26796.1, self.low=26764.5, self.vol=1608.102, self.amt=43059133.9933, ukdf['pct'].iloc[-1]=-0.000392 , ukdf['amount'].iloc[-1]=43059133.9933, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5956, value=0.0, value_mean=0.4344843203368141, signal=0, value_std=0.2799368623582656 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '13.926', 'enterprice': '26864.9', 'countrevence': '0', 'unrealprofit': '1236.88281734226', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '26776.08175949', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1


## /root/FIL/strategy/factorcheck/log.txt ----- -----

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=154, self.factor=0.5872293984857252, self.count=930 

self.closeSec=1684311599, self.tradeDate='20230517', self.openTime='161500', self.closeTime='161959', self.symbol='BTCUSDT', self.open=26800.0, self.close=26786.3, self.high=26809.9, self.low=26775.0 
2023-05-17 16:20:00,493:INFO:factorcheck2:main.py:126:handleKline:2218005: self.closeSec=1684311599, self.tradeDate='20230517', self.openTime='161500', self.closeTime='161959',self.symbol='BTCUSDT',self.open=26800.0, self.close=26786.3, self.high=26809.9, self.low=26775.0   
2023-05-17 16:20:00,572:INFO:factorcheck2:main.py:127:handleKline:2218005: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1630  20230517   155500    155959  1684310399  ...  26820.6 -0.000853   1630    4
1631  20230517   160000    160459  1684310699  ...  26805.0 -0.000745   1631    5
1632  20230517   160500    160959  1684310999  ...  26780.7 -0.001108   1632    0
1633  20230517   161000    161459  1684311299  ...  26765.1  0.000665   1633    1
1634  20230517   161500    161959  1684311599  ...  26775.0 -0.000511   1634    2

[5 rows x 11 columns]
2023-05-17 16:20:00,572:INFO:factorcheck2:main.py:128:handleKline:2218005: self.flagDict={'side': '', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=154, self.factor=0.5872293984857252, self.count=931 

self.closeSec=1684311899, self.tradeDate='20230517', self.openTime='162000', self.closeTime='162459', self.symbol='BTCUSDT', self.open=26786.2, self.close=26775.8, self.high=26796.1, self.low=26764.5 
2023-05-17 16:25:00,362:INFO:factorcheck2:main.py:126:handleKline:2218005: self.closeSec=1684311899, self.tradeDate='20230517', self.openTime='162000', self.closeTime='162459',self.symbol='BTCUSDT',self.open=26786.2, self.close=26775.8, self.high=26796.1, self.low=26764.5   
127.0.0.1 - - [17/May/2023 16:25:00] "POST / HTTP/1.1" 200 -
2023-05-17 16:25:00,407:INFO:factorcheck2:main.py:127:handleKline:2218005: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1631  20230517   160000    160459  1684310699  ...  26805.0 -0.000745   1631    5
1632  20230517   160500    160959  1684310999  ...  26780.7 -0.001108   1632    0
1633  20230517   161000    161459  1684311299  ...  26765.1  0.000665   1633    1
1634  20230517   161500    161959  1684311599  ...  26775.0 -0.000511   1634    2
1635  20230517   162000    162459  1684311899  ...  26764.5 -0.000392   1635    3

[5 rows x 11 columns]
2023-05-17 16:25:00,407:INFO:factorcheck2:main.py:128:handleKline:2218005: self.flagDict={'side': '', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}


## /root/FIL/strategy/logic/log.txt ----- -----

2023-05-17 16:00:18,307:DEBUG:logic:main.py:463:getModel:2218526: df_s.iloc[-5:,:] :
          date closeTime     open  ...    alpha58   alpha67   alpha72
5786  20230517    132959  27059.1  ...  50.833333  0.484140  0.568169
5787  20230517    135959  27010.9  ...  50.833333  0.476911  0.576382
5788  20230517    142959  26978.3  ...  50.833333  0.469646  0.589927
5789  20230517    145959  26944.9  ...  50.833333  0.479612  0.595326
5790  20230517    152959  26985.9  ...  50.416667  0.478602  0.601162

[5 rows x 33 columns]
0.5202952029520295
acc is : 0.5202952029520295
2023-05-17 16:00:18,424:INFO:logic:main.py:468:getModel:2218526: df_pred.iloc[-5:,:] :
     pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
537     1  0.485053  0.514947       0  ...  1.040233  -1.0    0.0  0.909665
538     1  0.478965  0.521035       0  ...  1.041513  -1.0    0.0  0.908545
539     1  0.482210  0.517790       1  ...  1.039932  -1.0    0.0  0.909924
540     1  0.496294  0.503706       0  ...  1.040106  -1.0    0.0  0.909773
541     1  0.486496  0.513504       0  ...  1.045869  -1.0    0.0  0.904732

[5 rows x 10 columns]
2023-05-17 16:00:18,449:INFO:logic:main.py:478:getModel:2218526: df_panel.iloc[-5:,:] :
    pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
45     1  0.485042  0.514958       0  ...  1.040233  -1.0    0.0  0.912045
46     1  0.479473  0.520527       0  ...  1.041513  -1.0    0.0  0.912567
47     1  0.482517  0.517483       1  ...  1.039932  -1.0    0.0  0.915040
48     1  0.496481  0.503519       0  ...  1.040106  -1.0    0.0  0.913271
49     1  0.486496  0.513504       0  ...  1.045869  -1.0    0.0  0.904732

[5 rows x 10 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '28.151', 'enterprice': '26995.7', 'countrevence': '0', 'unrealprofit': '4775.629298377', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '26826.056673', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}


## /root/FIL/strategy/modifiedmom/log.txt ----- -----

527  20230517   155000    155959  1684310399  26816.9  26831.9  0.000559
2023-05-17 16:00:00,424:INFO:modifiedmom:main.py:146:handleKline:2218259: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': True, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True}
127.0.0.1 - - [17/May/2023 16:10:00] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=464 

self.closeSec=1684310999, self.tradeDate='20230517', self.openTime='160000', self.closeTime='160959', self.symbol='BTCUSDT', self.open='26831.8', self.close='26782.2'
2023-05-17 16:10:00,360:INFO:modifiedmom:main.py:144:handleKline:2218259: self.closeSec=1684310999, self.tradeDate='20230517', self.openTime='160000', self.closeTime='160959',self.symbol='BTCUSDT',self.open='26831.8', self.close='26782.2'
2023-05-17 16:10:00,421:INFO:modifiedmom:main.py:145:handleKline:2218259: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
524  20230517   152000    152959  1684308599  26990.3  26981.4 -0.000330
525  20230517   153000    153959  1684309199  26981.3  26958.8 -0.000838
526  20230517   154000    154959  1684309799  26958.8  26816.9 -0.005264
527  20230517   155000    155959  1684310399  26816.9  26831.9  0.000559
528  20230517   160000    160959  1684310999  26831.8  26782.2 -0.001852
2023-05-17 16:10:00,421:INFO:modifiedmom:main.py:146:handleKline:2218259: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': True, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True}
127.0.0.1 - - [17/May/2023 16:20:00] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=465 

self.closeSec=1684311599, self.tradeDate='20230517', self.openTime='161000', self.closeTime='161959', self.symbol='BTCUSDT', self.open='26782.1', self.close='26786.3'
2023-05-17 16:20:00,457:INFO:modifiedmom:main.py:144:handleKline:2218259: self.closeSec=1684311599, self.tradeDate='20230517', self.openTime='161000', self.closeTime='161959',self.symbol='BTCUSDT',self.open='26782.1', self.close='26786.3'
2023-05-17 16:20:00,526:INFO:modifiedmom:main.py:145:handleKline:2218259: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
525  20230517   153000    153959  1684309199  26981.3  26958.8 -0.000838
526  20230517   154000    154959  1684309799  26958.8  26816.9 -0.005264
527  20230517   155000    155959  1684310399  26816.9  26831.9  0.000559
528  20230517   160000    160959  1684310999  26831.8  26782.2 -0.001852
529  20230517   161000    161959  1684311599  26782.1  26786.3  0.000153
2023-05-17 16:20:00,528:INFO:modifiedmom:main.py:146:handleKline:2218259: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': True, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True}


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

17519  20230517   155000    155959  1684310399  26816.9  26831.9
2023-05-17 16:00:00,435:INFO:pyemd2:main.py:127:handleKline:2217508: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}
127.0.0.1 - - [17/May/2023 16:10:00] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=467 

self.closeSec=1684310999, self.tradeDate='20230517', self.openTime='160000', self.closeTime='160959', self.symbol='BTCUSDT', self.open='26831.8', self.close='26782.2'
2023-05-17 16:10:00,398:INFO:pyemd2:main.py:125:handleKline:2217508: self.closeSec=1684310999, self.tradeDate='20230517', self.openTime='160000', self.closeTime='160959',self.symbol='BTCUSDT',self.open='26831.8', self.close='26782.2'
2023-05-17 16:10:00,437:INFO:pyemd2:main.py:126:handleKline:2217508: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17516  20230517   152000    152959  1684308599  26990.3  26981.4
17517  20230517   153000    153959  1684309199  26981.3  26958.8
17518  20230517   154000    154959  1684309799  26958.8  26816.9
17519  20230517   155000    155959  1684310399  26816.9  26831.9
17520  20230517   160000    160959  1684310999  26831.8  26782.2
2023-05-17 16:10:00,438:INFO:pyemd2:main.py:127:handleKline:2217508: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}
127.0.0.1 - - [17/May/2023 16:20:00] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=468 

self.closeSec=1684311599, self.tradeDate='20230517', self.openTime='161000', self.closeTime='161959', self.symbol='BTCUSDT', self.open='26782.1', self.close='26786.3'
2023-05-17 16:20:00,494:INFO:pyemd2:main.py:125:handleKline:2217508: self.closeSec=1684311599, self.tradeDate='20230517', self.openTime='161000', self.closeTime='161959',self.symbol='BTCUSDT',self.open='26782.1', self.close='26786.3'
2023-05-17 16:20:00,541:INFO:pyemd2:main.py:126:handleKline:2217508: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17517  20230517   153000    153959  1684309199  26981.3  26958.8
17518  20230517   154000    154959  1684309799  26958.8  26816.9
17519  20230517   155000    155959  1684310399  26816.9  26831.9
17520  20230517   160000    160959  1684310999  26831.8  26782.2
17521  20230517   161000    161959  1684311599  26782.1  26786.3
2023-05-17 16:20:00,544:INFO:pyemd2:main.py:127:handleKline:2217508: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}


## /root/FIL/strategy/similarity/log.txt ----- -----

12191  20230517   155000    155959  1684310399  26816.9  26831.9
2023-05-17 16:00:00,432:INFO:testStrategy:main.py:103:handleKline:2217133: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': True, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}
127.0.0.1 - - [17/May/2023 16:10:00] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=467 

self.closeSec=1684310999, self.tradeDate='20230517', self.openTime='160000', self.closeTime='160959', self.symbol='BTCUSDT', self.open='26831.8', self.close='26782.2'
2023-05-17 16:10:00,390:INFO:testStrategy:main.py:101:handleKline:2217133: self.closeSec=1684310999, self.tradeDate='20230517', self.openTime='160000', self.closeTime='160959',self.symbol='BTCUSDT',self.open='26831.8', self.close='26782.2'
2023-05-17 16:10:00,431:INFO:testStrategy:main.py:102:handleKline:2217133: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12188  20230517   152000    152959  1684308599  26990.3  26981.4
12189  20230517   153000    153959  1684309199  26981.3  26958.8
12190  20230517   154000    154959  1684309799  26958.8  26816.9
12191  20230517   155000    155959  1684310399  26816.9  26831.9
12192  20230517   160000    160959  1684310999  26831.8  26782.2
2023-05-17 16:10:00,433:INFO:testStrategy:main.py:103:handleKline:2217133: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': True, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}
127.0.0.1 - - [17/May/2023 16:20:00] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=468 

self.closeSec=1684311599, self.tradeDate='20230517', self.openTime='161000', self.closeTime='161959', self.symbol='BTCUSDT', self.open='26782.1', self.close='26786.3'
2023-05-17 16:20:00,485:INFO:testStrategy:main.py:101:handleKline:2217133: self.closeSec=1684311599, self.tradeDate='20230517', self.openTime='161000', self.closeTime='161959',self.symbol='BTCUSDT',self.open='26782.1', self.close='26786.3'
2023-05-17 16:20:00,536:INFO:testStrategy:main.py:102:handleKline:2217133: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12189  20230517   153000    153959  1684309199  26981.3  26958.8
12190  20230517   154000    154959  1684309799  26958.8  26816.9
12191  20230517   155000    155959  1684310399  26816.9  26831.9
12192  20230517   160000    160959  1684310999  26831.8  26782.2
12193  20230517   161000    161959  1684311599  26782.1  26786.3
2023-05-17 16:20:00,536:INFO:testStrategy:main.py:103:handleKline:2217133: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': True, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}


## /root/FIL/strategy/sr_min/log.txt ----- -----

127.0.0.1 - - [17/May/2023 16:20:00] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=1, self.total=996015.990996, self.flagDict['side']='buy', self.tradeCount=1, self.count=928
self.closeSec=1684311599, self.tradeDate='20230517', self.openTime='161500', self.closeTime='161959', self.symbol='BTCUSDT', self.open=26800.0, self.close=26786.3, self.high=26809.9, self.low=26775.0, self.vol=1675.769, self.amt=44901120.484 
2023-05-17 16:20:00,590:INFO:sr_min:main.py:172:handleKline:2219263: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5951  20230517   155500    155959  ...    0.316148   0.281901       0
5952  20230517   160000    160459  ...    0.315983   0.281993       0
5953  20230517   160500    160959  ...    0.315819   0.282085       0
5954  20230517   161000    161459  ...    0.315656   0.282177       0
5955  20230517   161500    161959  ...    0.315494   0.282269       0

[5 rows x 18 columns]
2023-05-17 16:20:00,592:INFO:sr_min:main.py:175:handleKline:2219263: self.closeSec=1684311599, self.tradeDate='20230517', self.openTime='161500', self.closeTime='161959',self.symbol='BTCUSDT',self.open=26800.0, self.close=26786.3, self.high=26809.9, self.low=26775.0, self.vol=1675.769, self.amt=44901120.484, ukdf['pct'].iloc[-1]=-0.000511 , ukdf['amount'].iloc[-1]=44901120.484, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5955, value=0.0, value_mean=0.3154943892737079, signal=0, value_std=0.28226929883087765 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '37.141', 'enterprice': '26844', 'countrevence': '0', 'unrealprofit': '-2146.7498', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '26786.2', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=1
--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=1, self.total=996015.990996, self.flagDict['side']='buy', self.tradeCount=1, self.count=929
self.closeSec=1684311899, self.tradeDate='20230517', self.openTime='162000', self.closeTime='162459', self.symbol='BTCUSDT', self.open=26786.2, self.close=26775.8, self.high=26796.1, self.low=26764.5, self.vol=1608.102, self.amt=43059133.9933 
127.0.0.1 - - [17/May/2023 16:25:00] "POST / HTTP/1.1" 200 -
2023-05-17 16:25:00,428:INFO:sr_min:main.py:172:handleKline:2219263: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5952  20230517   160000    160459  ...    0.315983   0.281993       0
5953  20230517   160500    160959  ...    0.315819   0.282085       0
5954  20230517   161000    161459  ...    0.315656   0.282177       0
5955  20230517   161500    161959  ...    0.315494   0.282269       0
5956  20230517   162000    162459  ...    0.315333   0.282361       0

[5 rows x 18 columns]
2023-05-17 16:25:00,428:INFO:sr_min:main.py:175:handleKline:2219263: self.closeSec=1684311899, self.tradeDate='20230517', self.openTime='162000', self.closeTime='162459',self.symbol='BTCUSDT',self.open=26786.2, self.close=26775.8, self.high=26796.1, self.low=26764.5, self.vol=1608.102, self.amt=43059133.9933, ukdf['pct'].iloc[-1]=-0.000392 , ukdf['amount'].iloc[-1]=43059133.9933, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5956, value=0.0, value_mean=0.3153334950487838, signal=0, value_std=0.2823610289662601 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '37.141', 'enterprice': '26844', 'countrevence': '0', 'unrealprofit': '-2522.55137078191', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '26776.08175949', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=1


## /root/FIL/strategy/s_rsrs/log.txt ----- -----

721  20230517   040000    075959  1684281599  ...    721  0.625374  0.766509     1.0
722  20230517   080000    115959  1684295999  ...    722  0.830026  1.936136     1.0

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '51.61', 'enterprice': '27024.7', 'countrevence': '0', 'unrealprofit': '1419.275', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '27052.2', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=1, self.sign=1
--handleKline--:  version='2.0.0', self.name='s_rsrs', self.symbol='BTCUSDT', interval='4h', intervalSec=14400, wid=25, thd=0.6, self.sign=1, self.total=1393350.022233, self.flagDict['side']='buy', self.tradeCount=1, self.count=19
self.closeSec=1684310399, self.tradeDate='20230517', self.openTime='120000', self.closeTime='155959', self.symbol='BTCUSDT', self.open=27052.1, self.close=26831.9, self.high=27092.4, self.low=26700.0, self.vol=53789.861, self.amt=1448160228.37922 
2023-05-17 16:00:00,376:INFO:s_rsrs:main.py:141:handleKline:2218689: self.closeSec=1684310399, self.tradeDate='20230517', self.openTime='120000', self.closeTime='155959',self.symbol='BTCUSDT',self.open=27052.1, self.close=26831.9, self.high=27092.4, self.low=26700.0, self.vol=53789.861, self.amt=1448160228.37922 
127.0.0.1 - - [17/May/2023 16:00:00] "POST / HTTP/1.1" 200 -
2023-05-17 16:00:00,445:INFO:s_rsrs:main.py:142:handleKline:2218689: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime  ...        vol           amt       pct
719  20230516   200000    235959  ...  89162.317  2.408574e+09 -0.000791
720  20230517   000000    035959  ...  53087.558  1.434175e+09 -0.004070
721  20230517   040000    075959  ...  28799.999  7.769224e+08  0.003971
722  20230517   080000    115959  ...  48161.970  1.305342e+09  0.001010
723  20230517   120000    155959  ...  53789.861  1.448160e+09 -0.008140

[5 rows x 11 columns]
2023-05-17 16:00:01,946:INFO:s_rsrs:main.py:151:handleKline:2218689: df_s.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec  ...  index      beta    zscore  signal
719  20230516   200000    235959  1684252799  ...    719  0.485815 -0.056272     NaN
720  20230517   000000    035959  1684267199  ...    720  0.448909 -0.285992     NaN
721  20230517   040000    075959  1684281599  ...    721  0.625374  0.766509     1.0
722  20230517   080000    115959  1684295999  ...    722  0.830026  1.936136     1.0
723  20230517   120000    155959  1684310399  ...    723  0.786628  1.643496     1.0

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '51.61', 'enterprice': '27024.7', 'countrevence': '0', 'unrealprofit': '-9897.6968779416', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '26832.92133544', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=1, self.sign=1


