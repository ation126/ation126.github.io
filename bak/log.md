# 20230618 16:26:01

## /root/FIL/strategy/amihud/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=373746.4768026, self.flagDict['side']='sell', self.tradeCount=2, self.count=10144
self.closeSec=1687076399, self.tradeDate='20230618', self.openTime='161500', self.closeTime='161959', self.symbol='BTCUSDT', self.open=26525.4, self.close=26507.9, self.high=26533.8, self.low=26498.2, self.vol=1397.664, self.amt=37052051.4763 
127.0.0.1 - - [18/Jun/2023 16:20:02] "POST / HTTP/1.1" 200 -
2023-06-18 16:20:07,829:INFO:amihud:main.py:172:handleKline:2219019: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5951  20230618   155500    155959  ...         0.0        0.0       0
5952  20230618   160000    160459  ...         0.0        0.0       0
5953  20230618   160500    160959  ...         0.0        0.0       0
5954  20230618   161000    161459  ...         0.0        0.0       0
5955  20230618   161500    161959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-06-18 16:20:07,860:INFO:amihud:main.py:175:handleKline:2219019: self.closeSec=1687076399, self.tradeDate='20230618', self.openTime='161500', self.closeTime='161959',self.symbol='BTCUSDT',self.open=26525.4, self.close=26507.9, self.high=26533.8, self.low=26498.2, self.vol=1397.664, self.amt=37052051.4763, ukdf['pct'].iloc[-1]=-0.000664 , ukdf['amount'].iloc[-1]=37052051.4763, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5955, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '13.926', 'enterprice': '26864.9', 'countrevence': '0', 'unrealprofit': '4853.211', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '26516.4', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1
--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=373746.4768026, self.flagDict['side']='sell', self.tradeCount=2, self.count=10145
self.closeSec=1687076699, self.tradeDate='20230618', self.openTime='162000', self.closeTime='162459', self.symbol='BTCUSDT', self.open=26508.0, self.close=26528.1, self.high=26536.9, self.low=26508.0, self.vol=564.995, self.amt=14987399.2739 
127.0.0.1 - - [18/Jun/2023 16:25:00] "POST / HTTP/1.1" 200 -
2023-06-18 16:25:00,757:INFO:amihud:main.py:172:handleKline:2219019: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5952  20230618   160000    160459  ...         0.0        0.0       0
5953  20230618   160500    160959  ...         0.0        0.0       0
5954  20230618   161000    161459  ...         0.0        0.0       0
5955  20230618   161500    161959  ...         0.0        0.0       0
5956  20230618   162000    162459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-06-18 16:25:00,758:INFO:amihud:main.py:175:handleKline:2219019: self.closeSec=1687076699, self.tradeDate='20230618', self.openTime='162000', self.closeTime='162459',self.symbol='BTCUSDT',self.open=26508.0, self.close=26528.1, self.high=26536.9, self.low=26508.0, self.vol=564.995, self.amt=14987399.2739, ukdf['pct'].iloc[-1]=0.000762 , ukdf['amount'].iloc[-1]=14987399.2739, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5956, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '13.926', 'enterprice': '26864.9', 'countrevence': '0', 'unrealprofit': '4680.09720260016', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '26528.83097784', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1


## /root/FIL/strategy/factorcheck/log.txt ----- -----


self.closeSec=1687076399, self.tradeDate='20230618', self.openTime='161500', self.closeTime='161959', self.symbol='BTCUSDT', self.open=26525.4, self.close=26507.9, self.high=26533.8, self.low=26498.2 
127.0.0.1 - - [18/Jun/2023 16:20:01] "POST / HTTP/1.1" 200 -
2023-06-18 16:20:05,197:INFO:factorcheck2:main.py:126:handleKline:2218005: self.closeSec=1687076399, self.tradeDate='20230618', self.openTime='161500', self.closeTime='161959',self.symbol='BTCUSDT',self.open=26525.4, self.close=26507.9, self.high=26533.8, self.low=26498.2   
2023-06-18 16:20:06,705:INFO:factorcheck2:main.py:127:handleKline:2218005: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1631  20230618   155500    155959  1687075199  ...  26566.2 -0.000158   1631    5
1632  20230618   160000    160459  1687075499  ...  26535.7 -0.001133   1632    0
1633  20230618   160500    160959  1687075799  ...  26535.0  0.000219   1633    1
1634  20230618   161000    161459  1687076099  ...  26520.0 -0.000836   1634    2
1635  20230618   161500    161959  1687076399  ...  26498.2 -0.000664   1635    3

[5 rows x 11 columns]
2023-06-18 16:20:06,714:INFO:factorcheck2:main.py:128:handleKline:2218005: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=69, self.factor=0.36798369962972044, self.count=10147 

self.closeSec=1687076699, self.tradeDate='20230618', self.openTime='162000', self.closeTime='162459', self.symbol='BTCUSDT', self.open=26508.0, self.close=26528.1, self.high=26536.9, self.low=26508.0 
127.0.0.1 - - [18/Jun/2023 16:25:00] "POST / HTTP/1.1" 200 -
2023-06-18 16:25:00,703:INFO:factorcheck2:main.py:126:handleKline:2218005: self.closeSec=1687076699, self.tradeDate='20230618', self.openTime='162000', self.closeTime='162459',self.symbol='BTCUSDT',self.open=26508.0, self.close=26528.1, self.high=26536.9, self.low=26508.0   
2023-06-18 16:25:00,725:INFO:factorcheck2:main.py:127:handleKline:2218005: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1632  20230618   160000    160459  1687075499  ...  26535.7 -0.001133   1632    0
1633  20230618   160500    160959  1687075799  ...  26535.0  0.000219   1633    1
1634  20230618   161000    161459  1687076099  ...  26520.0 -0.000836   1634    2
1635  20230618   161500    161959  1687076399  ...  26498.2 -0.000664   1635    3
1636  20230618   162000    162459  1687076699  ...  26508.0  0.000762   1636    4

[5 rows x 11 columns]
2023-06-18 16:25:00,725:INFO:factorcheck2:main.py:128:handleKline:2218005: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}


## /root/FIL/strategy/logic/log.txt ----- -----

2023-06-18 16:00:18,967:DEBUG:logic:main.py:463:getModel:2218526: df_s.iloc[-5:,:] :
          date closeTime     open  ...    alpha58   alpha67   alpha72
5786  20230618    132959  26527.2  ...  52.916667  0.585689  0.470241
5787  20230618    135959  26588.2  ...  52.500000  0.567250  0.461113
5788  20230618    142959  26524.4  ...  52.500000  0.570719  0.449560
5789  20230618    145959  26540.4  ...  52.500000  0.568236  0.440398
5790  20230618    152959  26531.8  ...  52.500000  0.580472  0.426006

[5 rows x 33 columns]
0.5682656826568265
acc is : 0.5682656826568265
2023-06-18 16:00:19,068:INFO:logic:main.py:468:getModel:2218526: df_pred.iloc[-5:,:] :
     pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
537     0  0.518803  0.481197       0  ...  1.075958   1.0    0.0  0.976141
538     1  0.490859  0.509141       1  ...  1.076611   1.0    0.0  0.976734
539     0  0.502859  0.497141       0  ...  1.076263   1.0    0.0  0.976417
540     1  0.498534  0.501466       1  ...  1.078555   1.0    0.0  0.978497
541     0  0.513250  0.486750       0  ...  1.077893   1.0    0.0  0.977897

[5 rows x 10 columns]
2023-06-18 16:00:19,089:INFO:logic:main.py:478:getModel:2218526: df_panel.iloc[-5:,:] :
    pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
45     0  0.518736  0.481264       0  ...  1.075958   1.0    0.0  0.977361
46     1  0.491015  0.508985       1  ...  1.076611   1.0    0.0  0.972782
47     0  0.503045  0.496955       0  ...  1.076263   1.0    0.0  0.974663
48     1  0.498720  0.501280       1  ...  1.078555   1.0    0.0  0.977644
49     0  0.513250  0.486750       0  ...  1.077893   1.0    0.0  0.977897

[5 rows x 10 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '28.127', 'enterprice': '25424', 'countrevence': '0', 'unrealprofit': '32455.7453', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '26577.9', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}


## /root/FIL/strategy/modifiedmom/log.txt ----- -----

527  20230618   155000    155959  1687075199  26592.8    26572 -0.000786
2023-06-18 16:00:02,152:INFO:modifiedmom:main.py:146:handleKline:2218259: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True}

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=5072 

self.closeSec=1687075799, self.tradeDate='20230618', self.openTime='160000', self.closeTime='160959', self.symbol='BTCUSDT', self.open='26572', self.close='26547.7'
2023-06-18 16:10:01,084:INFO:modifiedmom:main.py:144:handleKline:2218259: self.closeSec=1687075799, self.tradeDate='20230618', self.openTime='160000', self.closeTime='160959',self.symbol='BTCUSDT',self.open='26572', self.close='26547.7'
127.0.0.1 - - [18/Jun/2023 16:10:01] "POST / HTTP/1.1" 200 -
2023-06-18 16:10:01,130:INFO:modifiedmom:main.py:145:handleKline:2218259: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
524  20230618   152000    152959  1687073399  26640.2  26588.3 -0.001944
525  20230618   153000    153959  1687073999  26588.3  26589.6  0.000049
526  20230618   154000    154959  1687074599  26589.5  26592.9  0.000124
527  20230618   155000    155959  1687075199  26592.8    26572 -0.000786
528  20230618   160000    160959  1687075799    26572  26547.7 -0.000914
2023-06-18 16:10:01,130:INFO:modifiedmom:main.py:146:handleKline:2218259: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True}

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=5073 

self.closeSec=1687076399, self.tradeDate='20230618', self.openTime='161000', self.closeTime='161959', self.symbol='BTCUSDT', self.open='26547.8', self.close='26507.9'
127.0.0.1 - - [18/Jun/2023 16:20:04] "POST / HTTP/1.1" 200 -
2023-06-18 16:20:07,409:INFO:modifiedmom:main.py:144:handleKline:2218259: self.closeSec=1687076399, self.tradeDate='20230618', self.openTime='161000', self.closeTime='161959',self.symbol='BTCUSDT',self.open='26547.8', self.close='26507.9'
2023-06-18 16:20:08,209:INFO:modifiedmom:main.py:145:handleKline:2218259: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
525  20230618   153000    153959  1687073999  26588.3  26589.6  0.000049
526  20230618   154000    154959  1687074599  26589.5  26592.9  0.000124
527  20230618   155000    155959  1687075199  26592.8    26572 -0.000786
528  20230618   160000    160959  1687075799    26572  26547.7 -0.000914
529  20230618   161000    161959  1687076399  26547.8  26507.9 -0.001499
2023-06-18 16:20:08,218:INFO:modifiedmom:main.py:146:handleKline:2218259: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True}


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

17519  20230618   155000    155959  1687075199  26592.8    26572
2023-06-18 16:00:02,164:INFO:pyemd2:main.py:127:handleKline:2217508: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=5075 

self.closeSec=1687075799, self.tradeDate='20230618', self.openTime='160000', self.closeTime='160959', self.symbol='BTCUSDT', self.open='26572', self.close='26547.7'
127.0.0.1 - - [18/Jun/2023 16:10:01] "POST / HTTP/1.1" 200 -
2023-06-18 16:10:01,106:INFO:pyemd2:main.py:125:handleKline:2217508: self.closeSec=1687075799, self.tradeDate='20230618', self.openTime='160000', self.closeTime='160959',self.symbol='BTCUSDT',self.open='26572', self.close='26547.7'
2023-06-18 16:10:01,138:INFO:pyemd2:main.py:126:handleKline:2217508: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17516  20230618   152000    152959  1687073399  26640.2  26588.3
17517  20230618   153000    153959  1687073999  26588.3  26589.6
17518  20230618   154000    154959  1687074599  26589.5  26592.9
17519  20230618   155000    155959  1687075199  26592.8    26572
17520  20230618   160000    160959  1687075799    26572  26547.7
2023-06-18 16:10:01,138:INFO:pyemd2:main.py:127:handleKline:2217508: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=5076 

self.closeSec=1687076399, self.tradeDate='20230618', self.openTime='161000', self.closeTime='161959', self.symbol='BTCUSDT', self.open='26547.8', self.close='26507.9'
127.0.0.1 - - [18/Jun/2023 16:20:04] "POST / HTTP/1.1" 200 -
2023-06-18 16:20:09,643:INFO:pyemd2:main.py:125:handleKline:2217508: self.closeSec=1687076399, self.tradeDate='20230618', self.openTime='161000', self.closeTime='161959',self.symbol='BTCUSDT',self.open='26547.8', self.close='26507.9'
2023-06-18 16:20:09,789:INFO:pyemd2:main.py:126:handleKline:2217508: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17517  20230618   153000    153959  1687073999  26588.3  26589.6
17518  20230618   154000    154959  1687074599  26589.5  26592.9
17519  20230618   155000    155959  1687075199  26592.8    26572
17520  20230618   160000    160959  1687075799    26572  26547.7
17521  20230618   161000    161959  1687076399  26547.8  26507.9
2023-06-18 16:20:09,790:INFO:pyemd2:main.py:127:handleKline:2217508: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}


## /root/FIL/strategy/similarity/log.txt ----- -----

12191  20230618   155000    155959  1687075199  26592.8    26572
2023-06-18 16:00:02,161:INFO:testStrategy:main.py:103:handleKline:2217133: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': True, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=5075 

self.closeSec=1687075799, self.tradeDate='20230618', self.openTime='160000', self.closeTime='160959', self.symbol='BTCUSDT', self.open='26572', self.close='26547.7'
2023-06-18 16:10:01,094:INFO:testStrategy:main.py:101:handleKline:2217133: self.closeSec=1687075799, self.tradeDate='20230618', self.openTime='160000', self.closeTime='160959',self.symbol='BTCUSDT',self.open='26572', self.close='26547.7'
127.0.0.1 - - [18/Jun/2023 16:10:01] "POST / HTTP/1.1" 200 -
2023-06-18 16:10:01,135:INFO:testStrategy:main.py:102:handleKline:2217133: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12188  20230618   152000    152959  1687073399  26640.2  26588.3
12189  20230618   153000    153959  1687073999  26588.3  26589.6
12190  20230618   154000    154959  1687074599  26589.5  26592.9
12191  20230618   155000    155959  1687075199  26592.8    26572
12192  20230618   160000    160959  1687075799    26572  26547.7
2023-06-18 16:10:01,135:INFO:testStrategy:main.py:103:handleKline:2217133: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': True, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=5076 

self.closeSec=1687076399, self.tradeDate='20230618', self.openTime='161000', self.closeTime='161959', self.symbol='BTCUSDT', self.open='26547.8', self.close='26507.9'
127.0.0.1 - - [18/Jun/2023 16:20:04] "POST / HTTP/1.1" 200 -
2023-06-18 16:20:09,218:INFO:testStrategy:main.py:101:handleKline:2217133: self.closeSec=1687076399, self.tradeDate='20230618', self.openTime='161000', self.closeTime='161959',self.symbol='BTCUSDT',self.open='26547.8', self.close='26507.9'
2023-06-18 16:20:09,519:INFO:testStrategy:main.py:102:handleKline:2217133: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12189  20230618   153000    153959  1687073999  26588.3  26589.6
12190  20230618   154000    154959  1687074599  26589.5  26592.9
12191  20230618   155000    155959  1687075199  26592.8    26572
12192  20230618   160000    160959  1687075799    26572  26547.7
12193  20230618   161000    161959  1687076399  26547.8  26507.9
2023-06-18 16:20:09,520:INFO:testStrategy:main.py:103:handleKline:2217133: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': True, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}


## /root/FIL/strategy/sr_min/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=1, self.total=996015.990996, self.flagDict['side']='buy', self.tradeCount=1, self.count=10144
self.closeSec=1687076399, self.tradeDate='20230618', self.openTime='161500', self.closeTime='161959', self.symbol='BTCUSDT', self.open=26525.4, self.close=26507.9, self.high=26533.8, self.low=26498.2, self.vol=1397.664, self.amt=37052051.4763 
127.0.0.1 - - [18/Jun/2023 16:20:02] "POST / HTTP/1.1" 200 -
2023-06-18 16:20:07,829:INFO:sr_min:main.py:172:handleKline:2219263: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5951  20230618   155500    155959  ...         0.0        0.0       0
5952  20230618   160000    160459  ...         0.0        0.0       0
5953  20230618   160500    160959  ...         0.0        0.0       0
5954  20230618   161000    161459  ...         0.0        0.0       0
5955  20230618   161500    161959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-06-18 16:20:07,861:INFO:sr_min:main.py:175:handleKline:2219263: self.closeSec=1687076399, self.tradeDate='20230618', self.openTime='161500', self.closeTime='161959',self.symbol='BTCUSDT',self.open=26525.4, self.close=26507.9, self.high=26533.8, self.low=26498.2, self.vol=1397.664, self.amt=37052051.4763, ukdf['pct'].iloc[-1]=-0.000664 , ukdf['amount'].iloc[-1]=37052051.4763, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5955, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '37.141', 'enterprice': '26844', 'countrevence': '0', 'unrealprofit': '-12167.3916', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '26516.4', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=1
127.0.0.1 - - [18/Jun/2023 16:25:00] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=1, self.total=996015.990996, self.flagDict['side']='buy', self.tradeCount=1, self.count=10145
self.closeSec=1687076699, self.tradeDate='20230618', self.openTime='162000', self.closeTime='162459', self.symbol='BTCUSDT', self.open=26508.0, self.close=26528.1, self.high=26536.9, self.low=26508.0, self.vol=564.995, self.amt=14987399.2739 
2023-06-18 16:25:00,758:INFO:sr_min:main.py:172:handleKline:2219263: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5952  20230618   160000    160459  ...         0.0        0.0       0
5953  20230618   160500    160959  ...         0.0        0.0       0
5954  20230618   161000    161459  ...         0.0        0.0       0
5955  20230618   161500    161959  ...         0.0        0.0       0
5956  20230618   162000    162459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-06-18 16:25:00,758:INFO:sr_min:main.py:175:handleKline:2219263: self.closeSec=1687076699, self.tradeDate='20230618', self.openTime='162000', self.closeTime='162459',self.symbol='BTCUSDT',self.open=26508.0, self.close=26528.1, self.high=26536.9, self.low=26508.0, self.vol=564.995, self.amt=14987399.2739, ukdf['pct'].iloc[-1]=0.000762 , ukdf['amount'].iloc[-1]=14987399.2739, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5956, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '37.141', 'enterprice': '26844', 'countrevence': '0', 'unrealprofit': '-11705.69265204456', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '26528.83097784', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=1


## /root/FIL/strategy/s_rsrs/log.txt ----- -----

721  20230618   040000    075959  1687046399  ...    721  0.565101  0.945628     1.0
722  20230618   080000    115959  1687060799  ...    722  0.572393  0.992208     1.0

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '57.175', 'enterprice': '26590', 'countrevence': '0', 'unrealprofit': '-2937.83248346025', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '26538.61683457', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=1, self.sign=1
127.0.0.1 - - [18/Jun/2023 16:00:01] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='s_rsrs', self.symbol='BTCUSDT', interval='4h', intervalSec=14400, wid=25, thd=0.6, self.sign=1, self.total=1518762.96675, self.flagDict['side']='buy', self.tradeCount=5, self.count=211
self.closeSec=1687075199, self.tradeDate='20230618', self.openTime='120000', self.closeTime='155959', self.symbol='BTCUSDT', self.open=26538.4, self.close=26572.0, self.high=26675.1, self.low=26457.2, self.vol=40704.717, self.amt=1081643183.6915 
2023-06-18 16:00:01,740:INFO:s_rsrs:main.py:141:handleKline:2218689: self.closeSec=1687075199, self.tradeDate='20230618', self.openTime='120000', self.closeTime='155959',self.symbol='BTCUSDT',self.open=26538.4, self.close=26572.0, self.high=26675.1, self.low=26457.2, self.vol=40704.717, self.amt=1081643183.6915 
2023-06-18 16:00:01,773:INFO:s_rsrs:main.py:142:handleKline:2218689: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime  ...        vol           amt       pct
719  20230617   200000    235959  ...  64566.845  1.708797e+09 -0.003683
720  20230618   000000    035959  ...  31768.742  8.405475e+08  0.002511
721  20230618   040000    075959  ...  21650.496  5.741625e+08  0.001613
722  20230618   080000    115959  ...  27032.825  7.153643e+08  0.001113
723  20230618   120000    155959  ...  40704.717  1.081643e+09  0.001266

[5 rows x 11 columns]
2023-06-18 16:00:03,237:INFO:s_rsrs:main.py:151:handleKline:2218689: df_s.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec  ...  index      beta    zscore  signal
719  20230617   200000    235959  1687017599  ...    719  0.560629  0.902073     1.0
720  20230618   000000    035959  1687031999  ...    720  0.563406  0.926846     1.0
721  20230618   040000    075959  1687046399  ...    721  0.565101  0.945628     1.0
722  20230618   080000    115959  1687060799  ...    722  0.572393  0.992208     1.0
723  20230618   120000    155959  1687075199  ...    723  0.589647  1.084178     1.0

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '57.175', 'enterprice': '26590', 'countrevence': '0', 'unrealprofit': '-1007.68413852675', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '26572.37544139', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=1, self.sign=1


