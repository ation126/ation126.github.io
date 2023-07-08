# 20230708 16:26:01

## /root/FIL/strategy/amihud/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=373746.4768026, self.flagDict['side']='sell', self.tradeCount=2, self.count=15904
self.closeSec=1688804399, self.tradeDate='20230708', self.openTime='161500', self.closeTime='161959', self.symbol='BTCUSDT', self.open=30208.4, self.close=30260.7, self.high=30315.0, self.low=30208.4, self.vol=5669.825, self.amt=171632671.688 
127.0.0.1 - - [08/Jul/2023 16:20:01] "POST / HTTP/1.1" 200 -
2023-07-08 16:20:07,180:INFO:amihud:main.py:172:handleKline:2219019: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5951  20230708   155500    155959  ...         0.0        0.0       0
5952  20230708   160000    160459  ...         0.0        0.0       0
5953  20230708   160500    160959  ...         0.0        0.0       0
5954  20230708   161000    161459  ...         0.0        0.0       0
5955  20230708   161500    161959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-07-08 16:20:07,219:INFO:amihud:main.py:175:handleKline:2219019: self.closeSec=1688804399, self.tradeDate='20230708', self.openTime='161500', self.closeTime='161959',self.symbol='BTCUSDT',self.open=30208.4, self.close=30260.7, self.high=30315.0, self.low=30208.4, self.vol=5669.825, self.amt=171632671.688, ukdf['pct'].iloc[-1]=0.001728 , ukdf['amount'].iloc[-1]=171632671.688, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5955, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '13.926', 'enterprice': '26864.9', 'countrevence': '0', 'unrealprofit': '-47326.62029707854', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '30263.33604029', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1
127.0.0.1 - - [08/Jul/2023 16:25:00] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=373746.4768026, self.flagDict['side']='sell', self.tradeCount=2, self.count=15905
self.closeSec=1688804699, self.tradeDate='20230708', self.openTime='162000', self.closeTime='162459', self.symbol='BTCUSDT', self.open=30260.7, self.close=30250.0, self.high=30263.5, self.low=30241.0, self.vol=626.351, self.amt=18946861.8599 
2023-07-08 16:25:00,805:INFO:amihud:main.py:172:handleKline:2219019: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5952  20230708   160000    160459  ...         0.0        0.0       0
5953  20230708   160500    160959  ...         0.0        0.0       0
5954  20230708   161000    161459  ...         0.0        0.0       0
5955  20230708   161500    161959  ...         0.0        0.0       0
5956  20230708   162000    162459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-07-08 16:25:00,807:INFO:amihud:main.py:175:handleKline:2219019: self.closeSec=1688804699, self.tradeDate='20230708', self.openTime='162000', self.closeTime='162459',self.symbol='BTCUSDT',self.open=30260.7, self.close=30250.0, self.high=30263.5, self.low=30241.0, self.vol=626.351, self.amt=18946861.8599, ukdf['pct'].iloc[-1]=-0.000354 , ukdf['amount'].iloc[-1]=18946861.8599, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5956, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '13.926', 'enterprice': '26864.9', 'countrevence': '0', 'unrealprofit': '-47140.9026', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '30250', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1


## /root/FIL/strategy/factorcheck/log.txt ----- -----


self.closeSec=1688804399, self.tradeDate='20230708', self.openTime='161500', self.closeTime='161959', self.symbol='BTCUSDT', self.open=30208.4, self.close=30260.7, self.high=30315.0, self.low=30208.4 
127.0.0.1 - - [08/Jul/2023 16:20:01] "POST / HTTP/1.1" 200 -
2023-07-08 16:20:04,801:INFO:factorcheck2:main.py:126:handleKline:2218005: self.closeSec=1688804399, self.tradeDate='20230708', self.openTime='161500', self.closeTime='161959',self.symbol='BTCUSDT',self.open=30208.4, self.close=30260.7, self.high=30315.0, self.low=30208.4   
2023-07-08 16:20:06,371:INFO:factorcheck2:main.py:127:handleKline:2218005: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1631  20230708   155500    155959  1688803199  ...  30169.4  0.000176   1631    5
1632  20230708   160000    160459  1688803499  ...  30172.7  0.000229   1632    0
1633  20230708   160500    160959  1688803799  ...  30181.7  0.000451   1633    1
1634  20230708   161000    161459  1688804099  ...  30195.3  0.000437   1634    2
1635  20230708   161500    161959  1688804399  ...  30208.4  0.001728   1635    3

[5 rows x 11 columns]
2023-07-08 16:20:06,390:INFO:factorcheck2:main.py:128:handleKline:2218005: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': False, 'isOpen': True, 'isClose': False, 'isTrig': True}
127.0.0.1 - - [08/Jul/2023 16:25:00] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=32, self.factor=0.4743065940694948, self.count=15907 

self.closeSec=1688804699, self.tradeDate='20230708', self.openTime='162000', self.closeTime='162459', self.symbol='BTCUSDT', self.open=30260.7, self.close=30250.0, self.high=30263.5, self.low=30241.0 
2023-07-08 16:25:00,762:INFO:factorcheck2:main.py:126:handleKline:2218005: self.closeSec=1688804699, self.tradeDate='20230708', self.openTime='162000', self.closeTime='162459',self.symbol='BTCUSDT',self.open=30260.7, self.close=30250.0, self.high=30263.5, self.low=30241.0   
2023-07-08 16:25:00,780:INFO:factorcheck2:main.py:127:handleKline:2218005: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1632  20230708   160000    160459  1688803499  ...  30172.7  0.000229   1632    0
1633  20230708   160500    160959  1688803799  ...  30181.7  0.000451   1633    1
1634  20230708   161000    161459  1688804099  ...  30195.3  0.000437   1634    2
1635  20230708   161500    161959  1688804399  ...  30208.4  0.001728   1635    3
1636  20230708   162000    162459  1688804699  ...  30241.0 -0.000354   1636    4

[5 rows x 11 columns]
2023-07-08 16:25:00,780:INFO:factorcheck2:main.py:128:handleKline:2218005: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': False, 'isOpen': True, 'isClose': False, 'isTrig': True}


## /root/FIL/strategy/logic/log.txt ----- -----

2023-07-08 16:00:19,545:DEBUG:logic:main.py:463:getModel:2218526: df_s.iloc[-5:,:] :
          date closeTime     open  ...    alpha58   alpha67   alpha72
5786  20230708    132959  30227.0  ...  46.666667  0.476975  0.347219
5787  20230708    135959  30212.5  ...  47.083333  0.479599  0.357984
5788  20230708    142959  30224.0  ...  47.083333  0.471135  0.374319
5789  20230708    145959  30183.4  ...  46.666667  0.466572  0.392980
5790  20230708    152959  30161.3  ...  46.666667  0.472912  0.406241

[5 rows x 33 columns]
0.551660516605166
acc is : 0.551660516605166
2023-07-08 16:00:19,648:INFO:logic:main.py:468:getModel:2218526: df_pred.iloc[-5:,:] :
     pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
537     0  0.504193  0.495807       1  ...  0.986187   1.0    0.0  0.996121
538     0  0.522253  0.477747       0  ...  0.984859   1.0    0.0  0.994779
539     0  0.506256  0.493744       0  ...  0.984138   1.0    0.0  0.994051
540     0  0.507840  0.492160       1  ...  0.985015   1.0    0.0  0.994938
541     0  0.522293  0.477707       0  ...  0.984578   1.0    0.0  0.994496

[5 rows x 10 columns]
2023-07-08 16:00:19,659:INFO:logic:main.py:478:getModel:2218526: df_panel.iloc[-5:,:] :
    pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
45     0  0.506593  0.493407       1  ...  0.986187   1.0    0.0  1.000106
46     0  0.523816  0.476184       0  ...  0.984859   1.0    0.0  0.998521
47     0  0.507417  0.492583       0  ...  0.984138   1.0    0.0  0.996735
48     0  0.508473  0.491527       1  ...  0.985015   1.0    0.0  0.997304
49     0  0.522293  0.477707       0  ...  0.984578   1.0    0.0  0.994496

[5 rows x 10 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '24.764', 'enterprice': '30087.2', 'countrevence': '0', 'unrealprofit': '2278.288', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '30179.2', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}


## /root/FIL/strategy/modifiedmom/log.txt ----- -----

527  20230708   155000    155959  1688803199  30187.3  30174.8 -0.000414
2023-07-08 16:00:02,023:INFO:modifiedmom:main.py:146:handleKline:2218259: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': True, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True}

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=7952 

self.closeSec=1688803799, self.tradeDate='20230708', self.openTime='160000', self.closeTime='160959', self.symbol='BTCUSDT', self.open='30174.8', self.close='30195.3'
2023-07-08 16:10:01,149:INFO:modifiedmom:main.py:144:handleKline:2218259: self.closeSec=1688803799, self.tradeDate='20230708', self.openTime='160000', self.closeTime='160959',self.symbol='BTCUSDT',self.open='30174.8', self.close='30195.3'
127.0.0.1 - - [08/Jul/2023 16:10:01] "POST / HTTP/1.1" 200 -
2023-07-08 16:10:01,163:INFO:modifiedmom:main.py:145:handleKline:2218259: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
524  20230708   152000    152959  1688801399  30196.1  30188.2 -0.000265
525  20230708   153000    153959  1688801999  30188.2  30181.8 -0.000212
526  20230708   154000    154959  1688802599  30181.8  30187.3  0.000182
527  20230708   155000    155959  1688803199  30187.3  30174.8 -0.000414
528  20230708   160000    160959  1688803799  30174.8  30195.3  0.000679
2023-07-08 16:10:01,164:INFO:modifiedmom:main.py:146:handleKline:2218259: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': True, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True}

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=7953 

self.closeSec=1688804399, self.tradeDate='20230708', self.openTime='161000', self.closeTime='161959', self.symbol='BTCUSDT', self.open='30195.4', self.close='30260.7'
127.0.0.1 - - [08/Jul/2023 16:20:04] "POST / HTTP/1.1" 200 -
2023-07-08 16:20:07,049:INFO:modifiedmom:main.py:144:handleKline:2218259: self.closeSec=1688804399, self.tradeDate='20230708', self.openTime='161000', self.closeTime='161959',self.symbol='BTCUSDT',self.open='30195.4', self.close='30260.7'
2023-07-08 16:20:07,842:INFO:modifiedmom:main.py:145:handleKline:2218259: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
525  20230708   153000    153959  1688801999  30188.2  30181.8 -0.000212
526  20230708   154000    154959  1688802599  30181.8  30187.3  0.000182
527  20230708   155000    155959  1688803199  30187.3  30174.8 -0.000414
528  20230708   160000    160959  1688803799  30174.8  30195.3  0.000679
529  20230708   161000    161959  1688804399  30195.4  30260.7  0.002166
2023-07-08 16:20:07,842:INFO:modifiedmom:main.py:146:handleKline:2218259: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': True, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True}


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

17519  20230708   155000    155959  1688803199  30187.3  30174.8
2023-07-08 16:00:01,987:INFO:pyemd2:main.py:127:handleKline:2217508: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}
127.0.0.1 - - [08/Jul/2023 16:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=7955 

self.closeSec=1688803799, self.tradeDate='20230708', self.openTime='160000', self.closeTime='160959', self.symbol='BTCUSDT', self.open='30174.8', self.close='30195.3'
2023-07-08 16:10:01,144:INFO:pyemd2:main.py:125:handleKline:2217508: self.closeSec=1688803799, self.tradeDate='20230708', self.openTime='160000', self.closeTime='160959',self.symbol='BTCUSDT',self.open='30174.8', self.close='30195.3'
2023-07-08 16:10:01,168:INFO:pyemd2:main.py:126:handleKline:2217508: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17516  20230708   152000    152959  1688801399  30196.1  30188.2
17517  20230708   153000    153959  1688801999  30188.2  30181.8
17518  20230708   154000    154959  1688802599  30181.8  30187.3
17519  20230708   155000    155959  1688803199  30187.3  30174.8
17520  20230708   160000    160959  1688803799  30174.8  30195.3
2023-07-08 16:10:01,168:INFO:pyemd2:main.py:127:handleKline:2217508: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=7956 

self.closeSec=1688804399, self.tradeDate='20230708', self.openTime='161000', self.closeTime='161959', self.symbol='BTCUSDT', self.open='30195.4', self.close='30260.7'
127.0.0.1 - - [08/Jul/2023 16:20:04] "POST / HTTP/1.1" 200 -
2023-07-08 16:20:08,764:INFO:pyemd2:main.py:125:handleKline:2217508: self.closeSec=1688804399, self.tradeDate='20230708', self.openTime='161000', self.closeTime='161959',self.symbol='BTCUSDT',self.open='30195.4', self.close='30260.7'
2023-07-08 16:20:08,960:INFO:pyemd2:main.py:126:handleKline:2217508: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17517  20230708   153000    153959  1688801999  30188.2  30181.8
17518  20230708   154000    154959  1688802599  30181.8  30187.3
17519  20230708   155000    155959  1688803199  30187.3  30174.8
17520  20230708   160000    160959  1688803799  30174.8  30195.3
17521  20230708   161000    161959  1688804399  30195.4  30260.7
2023-07-08 16:20:08,961:INFO:pyemd2:main.py:127:handleKline:2217508: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}


## /root/FIL/strategy/similarity/log.txt ----- -----

12191  20230708   155000    155959  1688803199  30187.3  30174.8
2023-07-08 16:00:02,021:INFO:testStrategy:main.py:103:handleKline:2217133: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': True, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}
127.0.0.1 - - [08/Jul/2023 16:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=7955 

self.closeSec=1688803799, self.tradeDate='20230708', self.openTime='160000', self.closeTime='160959', self.symbol='BTCUSDT', self.open='30174.8', self.close='30195.3'
2023-07-08 16:10:01,154:INFO:testStrategy:main.py:101:handleKline:2217133: self.closeSec=1688803799, self.tradeDate='20230708', self.openTime='160000', self.closeTime='160959',self.symbol='BTCUSDT',self.open='30174.8', self.close='30195.3'
2023-07-08 16:10:01,174:INFO:testStrategy:main.py:102:handleKline:2217133: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12188  20230708   152000    152959  1688801399  30196.1  30188.2
12189  20230708   153000    153959  1688801999  30188.2  30181.8
12190  20230708   154000    154959  1688802599  30181.8  30187.3
12191  20230708   155000    155959  1688803199  30187.3  30174.8
12192  20230708   160000    160959  1688803799  30174.8  30195.3
2023-07-08 16:10:01,174:INFO:testStrategy:main.py:103:handleKline:2217133: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': True, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=7956 

self.closeSec=1688804399, self.tradeDate='20230708', self.openTime='161000', self.closeTime='161959', self.symbol='BTCUSDT', self.open='30195.4', self.close='30260.7'
127.0.0.1 - - [08/Jul/2023 16:20:04] "POST / HTTP/1.1" 200 -
2023-07-08 16:20:08,512:INFO:testStrategy:main.py:101:handleKline:2217133: self.closeSec=1688804399, self.tradeDate='20230708', self.openTime='161000', self.closeTime='161959',self.symbol='BTCUSDT',self.open='30195.4', self.close='30260.7'
2023-07-08 16:20:08,780:INFO:testStrategy:main.py:102:handleKline:2217133: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12189  20230708   153000    153959  1688801999  30188.2  30181.8
12190  20230708   154000    154959  1688802599  30181.8  30187.3
12191  20230708   155000    155959  1688803199  30187.3  30174.8
12192  20230708   160000    160959  1688803799  30174.8  30195.3
12193  20230708   161000    161959  1688804399  30195.4  30260.7
2023-07-08 16:20:08,789:INFO:testStrategy:main.py:103:handleKline:2217133: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': True, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}


## /root/FIL/strategy/sr_min/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=1, self.total=996015.990996, self.flagDict['side']='buy', self.tradeCount=1, self.count=15904
self.closeSec=1688804399, self.tradeDate='20230708', self.openTime='161500', self.closeTime='161959', self.symbol='BTCUSDT', self.open=30208.4, self.close=30260.7, self.high=30315.0, self.low=30208.4, self.vol=5669.825, self.amt=171632671.688 
127.0.0.1 - - [08/Jul/2023 16:20:01] "POST / HTTP/1.1" 200 -
2023-07-08 16:20:07,179:INFO:sr_min:main.py:172:handleKline:2219263: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5951  20230708   155500    155959  ...         0.0        0.0       0
5952  20230708   160000    160459  ...         0.0        0.0       0
5953  20230708   160500    160959  ...         0.0        0.0       0
5954  20230708   161000    161459  ...         0.0        0.0       0
5955  20230708   161500    161959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-07-08 16:20:07,200:INFO:sr_min:main.py:175:handleKline:2219263: self.closeSec=1688804399, self.tradeDate='20230708', self.openTime='161500', self.closeTime='161959',self.symbol='BTCUSDT',self.open=30208.4, self.close=30260.7, self.high=30315.0, self.low=30208.4, self.vol=5669.825, self.amt=171632671.688, ukdf['pct'].iloc[-1]=0.001728 , ukdf['amount'].iloc[-1]=171632671.688, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5955, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '37.141', 'enterprice': '26844', 'countrevence': '0', 'unrealprofit': '126997.55987241089', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '30263.33604029', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=1
--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=1, self.total=996015.990996, self.flagDict['side']='buy', self.tradeCount=1, self.count=15905
self.closeSec=1688804699, self.tradeDate='20230708', self.openTime='162000', self.closeTime='162459', self.symbol='BTCUSDT', self.open=30260.7, self.close=30250.0, self.high=30263.5, self.low=30241.0, self.vol=626.351, self.amt=18946861.8599 
127.0.0.1 - - [08/Jul/2023 16:25:00] "POST / HTTP/1.1" 200 -
2023-07-08 16:25:00,759:INFO:sr_min:main.py:172:handleKline:2219263: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5952  20230708   160000    160459  ...         0.0        0.0       0
5953  20230708   160500    160959  ...         0.0        0.0       0
5954  20230708   161000    161459  ...         0.0        0.0       0
5955  20230708   161500    161959  ...         0.0        0.0       0
5956  20230708   162000    162459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-07-08 16:25:00,759:INFO:sr_min:main.py:175:handleKline:2219263: self.closeSec=1688804699, self.tradeDate='20230708', self.openTime='162000', self.closeTime='162459',self.symbol='BTCUSDT',self.open=30260.7, self.close=30250.0, self.high=30263.5, self.low=30241.0, self.vol=626.351, self.amt=18946861.8599, ukdf['pct'].iloc[-1]=-0.000354 , ukdf['amount'].iloc[-1]=18946861.8599, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5956, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '37.141', 'enterprice': '26844', 'countrevence': '0', 'unrealprofit': '126502.246', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '30250', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=1


## /root/FIL/strategy/s_rsrs/log.txt ----- -----

721  20230708   040000    075959  1688774399  ...    721  0.507041  0.506372     NaN
722  20230708   080000    115959  1688788799  ...    722  0.472866  0.432107     NaN

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '53.05', 'enterprice': '30750.9', 'countrevence': '0', 'unrealprofit': '-26018.162826241', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '30260.45395238', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-9223372036854775808, self.sign=1
--handleKline--:  version='2.0.0', self.name='s_rsrs', self.symbol='BTCUSDT', interval='4h', intervalSec=14400, wid=25, thd=0.6, self.sign=1, self.total=1629703.909755, self.flagDict['side']='buy', self.tradeCount=9, self.count=331
self.closeSec=1688803199, self.tradeDate='20230708', self.openTime='120000', self.closeTime='155959', self.symbol='BTCUSDT', self.open=30260.0, self.close=30174.8, self.high=30269.2, self.low=30122.0, self.vol=26594.583, self.amt=803186213.33642 
127.0.0.1 - - [08/Jul/2023 16:00:01] "POST / HTTP/1.1" 200 -
2023-07-08 16:00:01,561:INFO:s_rsrs:main.py:141:handleKline:2218689: self.closeSec=1688803199, self.tradeDate='20230708', self.openTime='120000', self.closeTime='155959',self.symbol='BTCUSDT',self.open=30260.0, self.close=30174.8, self.high=30269.2, self.low=30122.0, self.vol=26594.583, self.amt=803186213.33642 
2023-07-08 16:00:01,587:INFO:s_rsrs:main.py:142:handleKline:2218689: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime  ...         vol           amt       pct
719  20230707   200000    235959  ...  105396.246  3.188922e+09  0.009015
720  20230708   000000    035959  ...   46214.504  1.398251e+09 -0.004856
721  20230708   040000    075959  ...   19739.873  5.977132e+08  0.003308
722  20230708   080000    115959  ...   20274.344  6.142538e+08 -0.002239
723  20230708   120000    155959  ...   26594.583  8.031862e+08 -0.002816

[5 rows x 11 columns]
2023-07-08 16:00:02,833:INFO:s_rsrs:main.py:151:handleKline:2218689: df_s.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec  ...  index      beta    zscore  signal
719  20230707   200000    235959  1688745599  ...    719  0.530504  0.507898     NaN
720  20230708   000000    035959  1688759999  ...    720  0.537345  0.564885     NaN
721  20230708   040000    075959  1688774399  ...    721  0.507041  0.506372     NaN
722  20230708   080000    115959  1688788799  ...    722  0.472866  0.432107     NaN
723  20230708   120000    155959  1688803199  ...    723  0.458979  0.419851     NaN

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '53.05', 'enterprice': '30750.9', 'countrevence': '0', 'unrealprofit': '-30459.5781991955', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '30176.73264469', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-9223372036854775808, self.sign=1


