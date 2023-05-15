# 20230515 16:26:02

## /root/FIL/strategy/amihud/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=373746.4768026, self.flagDict['side']='sell', self.tradeCount=2, self.count=352
self.closeSec=1684138799, self.tradeDate='20230515', self.openTime='161500', self.closeTime='161959', self.symbol='BTCUSDT', self.open=27384.6, self.close=27370.1, self.high=27394.8, self.low=27370.0, self.vol=726.727, self.amt=19900760.3811 
127.0.0.1 - - [15/May/2023 16:20:00] "POST / HTTP/1.1" 200 -
2023-05-15 16:20:00,534:INFO:amihud:main.py:172:handleKline:2219019: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5951  20230515   155500    155959  ...    0.517479   0.208767       0
5952  20230515   160000    160459  ...    0.517369   0.208936       0
5953  20230515   160500    160959  ...    0.517260   0.209103       0
5954  20230515   161000    161459  ...    0.517152   0.209270       0
5955  20230515   161500    161959  ...    0.517043   0.209437       0

[5 rows x 18 columns]
2023-05-15 16:20:00,538:INFO:amihud:main.py:175:handleKline:2219019: self.closeSec=1684138799, self.tradeDate='20230515', self.openTime='161500', self.closeTime='161959',self.symbol='BTCUSDT',self.open=27384.6, self.close=27370.1, self.high=27394.8, self.low=27370.0, self.vol=726.727, self.amt=19900760.3811, ukdf['pct'].iloc[-1]=-0.000529 , ukdf['amount'].iloc[-1]=19900760.3811, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5955, value=0.0, value_mean=0.5170430207612733, signal=0, value_std=0.2094366822080064 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '13.926', 'enterprice': '26864.9', 'countrevence': '0', 'unrealprofit': '-7116.49191285978', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '27375.92196703', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1
--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=373746.4768026, self.flagDict['side']='sell', self.tradeCount=2, self.count=353
self.closeSec=1684139099, self.tradeDate='20230515', self.openTime='162000', self.closeTime='162459', self.symbol='BTCUSDT', self.open=27370.1, self.close=27388.0, self.high=27407.7, self.low=27370.0, self.vol=917.938, self.amt=25142911.3187 
127.0.0.1 - - [15/May/2023 16:25:00] "POST / HTTP/1.1" 200 -
2023-05-15 16:25:00,420:INFO:amihud:main.py:172:handleKline:2219019: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5952  20230515   160000    160459  ...    0.517369   0.208936       0
5953  20230515   160500    160959  ...    0.517260   0.209103       0
5954  20230515   161000    161459  ...    0.517152   0.209270       0
5955  20230515   161500    161959  ...    0.517043   0.209437       0
5956  20230515   162000    162459  ...    0.516935   0.209603       0

[5 rows x 18 columns]
2023-05-15 16:25:00,421:INFO:amihud:main.py:175:handleKline:2219019: self.closeSec=1684139099, self.tradeDate='20230515', self.openTime='162000', self.closeTime='162459',self.symbol='BTCUSDT',self.open=27370.1, self.close=27388.0, self.high=27407.7, self.low=27370.0, self.vol=917.938, self.amt=25142911.3187, ukdf['pct'].iloc[-1]=0.000654 , ukdf['amount'].iloc[-1]=25142911.3187, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5956, value=0.0, value_mean=0.5169346289864662, signal=0, value_std=0.20960320353043144 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '13.926', 'enterprice': '26864.9', 'countrevence': '0', 'unrealprofit': '-7326.7434727806', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '27391.0197381', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1


## /root/FIL/strategy/factorcheck/log.txt ----- -----


self.closeSec=1684138799, self.tradeDate='20230515', self.openTime='161500', self.closeTime='161959', self.symbol='BTCUSDT', self.open=27384.6, self.close=27370.1, self.high=27394.8, self.low=27370.0 
127.0.0.1 - - [15/May/2023 16:20:00] "POST / HTTP/1.1" 200 -
2023-05-15 16:20:00,444:INFO:factorcheck2:main.py:126:handleKline:2218005: self.closeSec=1684138799, self.tradeDate='20230515', self.openTime='161500', self.closeTime='161959',self.symbol='BTCUSDT',self.open=27384.6, self.close=27370.1, self.high=27394.8, self.low=27370.0   
2023-05-15 16:20:00,506:INFO:factorcheck2:main.py:127:handleKline:2218005: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1630  20230515   155500    155959  1684137599  ...  27371.5  0.000493   1630    4
1631  20230515   160000    160459  1684137899  ...  27386.1  0.000420   1631    5
1632  20230515   160500    160959  1684138199  ...  27376.4 -0.001051   1632    0
1633  20230515   161000    161459  1684138499  ...  27370.6  0.000121   1633    1
1634  20230515   161500    161959  1684138799  ...  27370.0 -0.000529   1634    2

[5 rows x 11 columns]
2023-05-15 16:20:00,507:INFO:factorcheck2:main.py:128:handleKline:2218005: self.flagDict={'side': '', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=58, self.factor=0.37725825669070895, self.count=355 

self.closeSec=1684139099, self.tradeDate='20230515', self.openTime='162000', self.closeTime='162459', self.symbol='BTCUSDT', self.open=27370.1, self.close=27388.0, self.high=27407.7, self.low=27370.0 
2023-05-15 16:25:00,367:INFO:factorcheck2:main.py:126:handleKline:2218005: self.closeSec=1684139099, self.tradeDate='20230515', self.openTime='162000', self.closeTime='162459',self.symbol='BTCUSDT',self.open=27370.1, self.close=27388.0, self.high=27407.7, self.low=27370.0   
127.0.0.1 - - [15/May/2023 16:25:00] "POST / HTTP/1.1" 200 -
2023-05-15 16:25:00,406:INFO:factorcheck2:main.py:127:handleKline:2218005: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1631  20230515   160000    160459  1684137899  ...  27386.1  0.000420   1631    5
1632  20230515   160500    160959  1684138199  ...  27376.4 -0.001051   1632    0
1633  20230515   161000    161459  1684138499  ...  27370.6  0.000121   1633    1
1634  20230515   161500    161959  1684138799  ...  27370.0 -0.000529   1634    2
1635  20230515   162000    162459  1684139099  ...  27370.0  0.000654   1635    3

[5 rows x 11 columns]
2023-05-15 16:25:00,406:INFO:factorcheck2:main.py:128:handleKline:2218005: self.flagDict={'side': '', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}


## /root/FIL/strategy/logic/log.txt ----- -----

2023-05-15 16:00:19,413:DEBUG:logic:main.py:463:getModel:2218526: df_s.iloc[-5:,:] :
          date closeTime     open  ...    alpha58   alpha67   alpha72
5786  20230515    132959  27271.8  ...  51.666667  0.578265  0.372711
5787  20230515    135959  27239.9  ...  52.083333  0.593776  0.352762
5788  20230515    142959  27322.4  ...  52.500000  0.623857  0.333281
5789  20230515    145959  27498.3  ...  52.083333  0.614741  0.317786
5790  20230515    152959  27463.6  ...  52.083333  0.607573  0.305452

[5 rows x 33 columns]
0.540590405904059
acc is : 0.540590405904059
2023-05-15 16:00:19,524:INFO:logic:main.py:468:getModel:2218526: df_pred.iloc[-5:,:] :
     pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
537     1  0.496020  0.503980       1  ...  1.041032   1.0    0.0  0.941178
538     0  0.518133  0.481867       1  ...  1.047731   1.0    0.0  0.947234
539     0  0.545288  0.454712       0  ...  1.046416   1.0    0.0  0.946045
540     0  0.509408  0.490592       0  ...  1.045376   1.0    0.0  0.945105
541     0  0.500339  0.499661       0  ...  1.043936   1.0    0.0  0.943803

[5 rows x 10 columns]
2023-05-15 16:00:19,549:INFO:logic:main.py:478:getModel:2218526: df_panel.iloc[-5:,:] :
    pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
45     1  0.496482  0.503518       1  ...  1.041032   1.0    0.0  0.939043
46     0  0.518714  0.481286       1  ...  1.047731   1.0    0.0  0.947231
47     0  0.545591  0.454409       0  ...  1.046416   1.0    0.0  0.946424
48     0  0.509734  0.490266       0  ...  1.045376   1.0    0.0  0.945313
49     0  0.500339  0.499661       0  ...  1.043936   1.0    0.0  0.943803

[5 rows x 10 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '28.199', 'enterprice': '26801.5', 'countrevence': '0', 'unrealprofit': '16981.13871492023', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '27403.68939377', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}


## /root/FIL/strategy/modifiedmom/log.txt ----- -----

527  20230515   155000    155959  1684137599  27378.7  27398.6  0.000727
2023-05-15 16:00:00,451:INFO:modifiedmom:main.py:146:handleKline:2218259: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': True, 'isCloseBuy': False, 'isCloseSell': False, 'isOpen': True, 'isClose': False, 'isTrig': True}
127.0.0.1 - - [15/May/2023 16:10:00] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=176 

self.closeSec=1684138199, self.tradeDate='20230515', self.openTime='160000', self.closeTime='160959', self.symbol='BTCUSDT', self.open='27398.6', self.close='27381.3'
2023-05-15 16:10:00,394:INFO:modifiedmom:main.py:144:handleKline:2218259: self.closeSec=1684138199, self.tradeDate='20230515', self.openTime='160000', self.closeTime='160959',self.symbol='BTCUSDT',self.open='27398.6', self.close='27381.3'
2023-05-15 16:10:00,473:INFO:modifiedmom:main.py:145:handleKline:2218259: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
524  20230515   152000    152959  1684135799  27428.7  27436.4  0.000281
525  20230515   153000    153959  1684136399  27436.3  27426.2 -0.000372
526  20230515   154000    154959  1684136999  27426.1  27378.7 -0.001732
527  20230515   155000    155959  1684137599  27378.7  27398.6  0.000727
528  20230515   160000    160959  1684138199  27398.6  27381.3 -0.000631
2023-05-15 16:10:00,474:INFO:modifiedmom:main.py:146:handleKline:2218259: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': True, 'isCloseBuy': False, 'isCloseSell': False, 'isOpen': True, 'isClose': False, 'isTrig': True}

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=177 

self.closeSec=1684138799, self.tradeDate='20230515', self.openTime='161000', self.closeTime='161959', self.symbol='BTCUSDT', self.open='27381.3', self.close='27370.1'
127.0.0.1 - - [15/May/2023 16:20:00] "POST / HTTP/1.1" 200 -
2023-05-15 16:20:00,732:INFO:modifiedmom:main.py:144:handleKline:2218259: self.closeSec=1684138799, self.tradeDate='20230515', self.openTime='161000', self.closeTime='161959',self.symbol='BTCUSDT',self.open='27381.3', self.close='27370.1'
2023-05-15 16:20:00,960:INFO:modifiedmom:main.py:145:handleKline:2218259: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
525  20230515   153000    153959  1684136399  27436.3  27426.2 -0.000372
526  20230515   154000    154959  1684136999  27426.1  27378.7 -0.001732
527  20230515   155000    155959  1684137599  27378.7  27398.6  0.000727
528  20230515   160000    160959  1684138199  27398.6  27381.3 -0.000631
529  20230515   161000    161959  1684138799  27381.3  27370.1 -0.000409
2023-05-15 16:20:00,960:INFO:modifiedmom:main.py:146:handleKline:2218259: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': True, 'isCloseBuy': False, 'isCloseSell': False, 'isOpen': True, 'isClose': False, 'isTrig': True}


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

17519  20230515   155000    155959  1684137599  27378.7  27398.6
2023-05-15 16:00:00,465:INFO:pyemd2:main.py:127:handleKline:2217508: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}
127.0.0.1 - - [15/May/2023 16:10:00] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=179 

self.closeSec=1684138199, self.tradeDate='20230515', self.openTime='160000', self.closeTime='160959', self.symbol='BTCUSDT', self.open='27398.6', self.close='27381.3'
2023-05-15 16:10:00,427:INFO:pyemd2:main.py:125:handleKline:2217508: self.closeSec=1684138199, self.tradeDate='20230515', self.openTime='160000', self.closeTime='160959',self.symbol='BTCUSDT',self.open='27398.6', self.close='27381.3'
2023-05-15 16:10:00,489:INFO:pyemd2:main.py:126:handleKline:2217508: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17516  20230515   152000    152959  1684135799  27428.7  27436.4
17517  20230515   153000    153959  1684136399  27436.3  27426.2
17518  20230515   154000    154959  1684136999  27426.1  27378.7
17519  20230515   155000    155959  1684137599  27378.7  27398.6
17520  20230515   160000    160959  1684138199  27398.6  27381.3
2023-05-15 16:10:00,491:INFO:pyemd2:main.py:127:handleKline:2217508: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=180 

self.closeSec=1684138799, self.tradeDate='20230515', self.openTime='161000', self.closeTime='161959', self.symbol='BTCUSDT', self.open='27381.3', self.close='27370.1'
127.0.0.1 - - [15/May/2023 16:20:00] "POST / HTTP/1.1" 200 -
2023-05-15 16:20:01,213:INFO:pyemd2:main.py:125:handleKline:2217508: self.closeSec=1684138799, self.tradeDate='20230515', self.openTime='161000', self.closeTime='161959',self.symbol='BTCUSDT',self.open='27381.3', self.close='27370.1'
2023-05-15 16:20:01,240:INFO:pyemd2:main.py:126:handleKline:2217508: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17517  20230515   153000    153959  1684136399  27436.3  27426.2
17518  20230515   154000    154959  1684136999  27426.1  27378.7
17519  20230515   155000    155959  1684137599  27378.7  27398.6
17520  20230515   160000    160959  1684138199  27398.6  27381.3
17521  20230515   161000    161959  1684138799  27381.3  27370.1
2023-05-15 16:20:01,240:INFO:pyemd2:main.py:127:handleKline:2217508: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}


## /root/FIL/strategy/similarity/log.txt ----- -----

12191  20230515   155000    155959  1684137599  27378.7  27398.6
2023-05-15 16:00:00,461:INFO:testStrategy:main.py:103:handleKline:2217133: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': False, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}
127.0.0.1 - - [15/May/2023 16:10:00] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=179 

self.closeSec=1684138199, self.tradeDate='20230515', self.openTime='160000', self.closeTime='160959', self.symbol='BTCUSDT', self.open='27398.6', self.close='27381.3'
2023-05-15 16:10:00,418:INFO:testStrategy:main.py:101:handleKline:2217133: self.closeSec=1684138199, self.tradeDate='20230515', self.openTime='160000', self.closeTime='160959',self.symbol='BTCUSDT',self.open='27398.6', self.close='27381.3'
2023-05-15 16:10:00,482:INFO:testStrategy:main.py:102:handleKline:2217133: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12188  20230515   152000    152959  1684135799  27428.7  27436.4
12189  20230515   153000    153959  1684136399  27436.3  27426.2
12190  20230515   154000    154959  1684136999  27426.1  27378.7
12191  20230515   155000    155959  1684137599  27378.7  27398.6
12192  20230515   160000    160959  1684138199  27398.6  27381.3
2023-05-15 16:10:00,487:INFO:testStrategy:main.py:103:handleKline:2217133: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': False, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=180 

self.closeSec=1684138799, self.tradeDate='20230515', self.openTime='161000', self.closeTime='161959', self.symbol='BTCUSDT', self.open='27381.3', self.close='27370.1'
127.0.0.1 - - [15/May/2023 16:20:00] "POST / HTTP/1.1" 200 -
2023-05-15 16:20:01,152:INFO:testStrategy:main.py:101:handleKline:2217133: self.closeSec=1684138799, self.tradeDate='20230515', self.openTime='161000', self.closeTime='161959',self.symbol='BTCUSDT',self.open='27381.3', self.close='27370.1'
2023-05-15 16:20:01,201:INFO:testStrategy:main.py:102:handleKline:2217133: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12189  20230515   153000    153959  1684136399  27436.3  27426.2
12190  20230515   154000    154959  1684136999  27426.1  27378.7
12191  20230515   155000    155959  1684137599  27378.7  27398.6
12192  20230515   160000    160959  1684138199  27398.6  27381.3
12193  20230515   161000    161959  1684138799  27381.3  27370.1
2023-05-15 16:20:01,201:INFO:testStrategy:main.py:103:handleKline:2217133: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': False, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}


## /root/FIL/strategy/sr_min/log.txt ----- -----

127.0.0.1 - - [15/May/2023 16:20:00] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=1, self.total=996015.990996, self.flagDict['side']='buy', self.tradeCount=1, self.count=352
self.closeSec=1684138799, self.tradeDate='20230515', self.openTime='161500', self.closeTime='161959', self.symbol='BTCUSDT', self.open=27384.6, self.close=27370.1, self.high=27394.8, self.low=27370.0, self.vol=726.727, self.amt=19900760.3811 
2023-05-15 16:20:00,533:INFO:sr_min:main.py:172:handleKline:2219263: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5951  20230515   155500    155959  ...    0.466854   0.199512       0
5952  20230515   160000    160459  ...    0.466613   0.199796       0
5953  20230515   160500    160959  ...    0.466371   0.200080       0
5954  20230515   161000    161459  ...    0.466126   0.200362       0
5955  20230515   161500    161959  ...    0.465878   0.200644       0

[5 rows x 18 columns]
2023-05-15 16:20:00,536:INFO:sr_min:main.py:175:handleKline:2219263: self.closeSec=1684138799, self.tradeDate='20230515', self.openTime='161500', self.closeTime='161959',self.symbol='BTCUSDT',self.open=27384.6, self.close=27370.1, self.high=27394.8, self.low=27370.0, self.vol=726.727, self.amt=19900760.3811, ukdf['pct'].iloc[-1]=-0.000529 , ukdf['amount'].iloc[-1]=19900760.3811, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5955, value=0.0, value_mean=0.4658776482568249, signal=0, value_std=0.20064418341483628 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '37.141', 'enterprice': '26844', 'countrevence': '0', 'unrealprofit': '19756.11377746123', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '27375.92196703', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=1
--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=1, self.total=996015.990996, self.flagDict['side']='buy', self.tradeCount=1, self.count=353
self.closeSec=1684139099, self.tradeDate='20230515', self.openTime='162000', self.closeTime='162459', self.symbol='BTCUSDT', self.open=27370.1, self.close=27388.0, self.high=27407.7, self.low=27370.0, self.vol=917.938, self.amt=25142911.3187 
127.0.0.1 - - [15/May/2023 16:25:00] "POST / HTTP/1.1" 200 -
2023-05-15 16:25:00,421:INFO:sr_min:main.py:172:handleKline:2219263: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5952  20230515   160000    160459  ...    0.466613   0.199796       0
5953  20230515   160500    160959  ...    0.466371   0.200080       0
5954  20230515   161000    161459  ...    0.466126   0.200362       0
5955  20230515   161500    161959  ...    0.465878   0.200644       0
5956  20230515   162000    162459  ...    0.465646   0.200925       0

[5 rows x 18 columns]
2023-05-15 16:25:00,421:INFO:sr_min:main.py:175:handleKline:2219263: self.closeSec=1684139099, self.tradeDate='20230515', self.openTime='162000', self.closeTime='162459',self.symbol='BTCUSDT',self.open=27370.1, self.close=27388.0, self.high=27407.7, self.low=27370.0, self.vol=917.938, self.amt=25142911.3187, ukdf['pct'].iloc[-1]=0.000654 , ukdf['amount'].iloc[-1]=25142911.3187, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5956, value=0.0, value_mean=0.4656457019972582, signal=0, value_std=0.2009250046304071 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '37.141', 'enterprice': '26844', 'countrevence': '0', 'unrealprofit': '20316.8600927721', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '27391.0197381', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=1


## /root/FIL/strategy/s_rsrs/log.txt ----- -----

721  20230515   040000    075959  1684108799  ...    721  0.488492  0.175305     NaN
722  20230515   080000    115959  1684123199  ...    722  0.397467 -0.263858     NaN

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '52.436', 'enterprice': '26818.7', 'countrevence': '0', 'unrealprofit': '-21011.1052', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '27219.4', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-9223372036854775808, self.sign=-1
--handleKline--:  version='2.0.0', self.name='s_rsrs', self.symbol='BTCUSDT', interval='4h', intervalSec=14400, wid=25, thd=0.6, self.sign=-1, self.total=6897.9369698, self.flagDict['side']='', self.tradeCount=0, self.count=7
self.closeSec=1684137599, self.tradeDate='20230515', self.openTime='120000', self.closeTime='155959', self.symbol='BTCUSDT', self.open=27216.4, self.close=27398.6, self.high=27550.0, self.low=27165.1, self.vol=93928.69, self.amt=2569898482.62797 
127.0.0.1 - - [15/May/2023 16:00:00] "POST / HTTP/1.1" 200 -
2023-05-15 16:00:00,351:INFO:s_rsrs:main.py:141:handleKline:2218689: self.closeSec=1684137599, self.tradeDate='20230515', self.openTime='120000', self.closeTime='155959',self.symbol='BTCUSDT',self.open=27216.4, self.close=27398.6, self.high=27550.0, self.low=27165.1, self.vol=93928.69, self.amt=2569898482.62797 
2023-05-15 16:00:00,368:INFO:s_rsrs:main.py:142:handleKline:2218689: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime  ...         vol           amt       pct
719  20230514   200000    235959  ...   86298.935  2.327455e+09  0.010323
720  20230515   000000    035959  ...   53779.117  1.448718e+09 -0.007624
721  20230515   040000    075959  ...   21451.127  5.768678e+08  0.001374
722  20230515   080000    115959  ...  100134.610  2.707659e+09  0.011687
723  20230515   120000    155959  ...   93928.690  2.569898e+09  0.006698

[5 rows x 11 columns]
2023-05-15 16:00:01,944:INFO:s_rsrs:main.py:151:handleKline:2218689: df_s.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec  ...  index      beta    zscore  signal
719  20230514   200000    235959  1684079999  ...    719  0.492854  0.222064     NaN
720  20230515   000000    035959  1684094399  ...    720  0.333023 -0.499666     NaN
721  20230515   040000    075959  1684108799  ...    721  0.488492  0.175305     NaN
722  20230515   080000    115959  1684123199  ...    722  0.397467 -0.263858     NaN
723  20230515   120000    155959  1684137599  ...    723  0.395800 -0.299161     NaN

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '52.436', 'enterprice': '26818.7', 'countrevence': '0', 'unrealprofit': '-30428.6108', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '27399', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-9223372036854775808, self.sign=-1


