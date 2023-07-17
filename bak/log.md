# 20230717 16:26:01

## /root/FIL/strategy/amihud/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=373746.4768026, self.flagDict['side']='sell', self.tradeCount=2, self.count=18496
self.closeSec=1689581999, self.tradeDate='20230717', self.openTime='161500', self.closeTime='161959', self.symbol='BTCUSDT', self.open=30274.0, self.close=30275.3, self.high=30275.3, self.low=30270.1, self.vol=281.515, self.amt=8522322.8303 
127.0.0.1 - - [17/Jul/2023 16:20:01] "POST / HTTP/1.1" 200 -
2023-07-17 16:20:06,221:INFO:amihud:main.py:172:handleKline:2219019: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5951  20230717   155500    155959  ...         0.0        0.0       0
5952  20230717   160000    160459  ...         0.0        0.0       0
5953  20230717   160500    160959  ...         0.0        0.0       0
5954  20230717   161000    161459  ...         0.0        0.0       0
5955  20230717   161500    161959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-07-17 16:20:06,241:INFO:amihud:main.py:175:handleKline:2219019: self.closeSec=1689581999, self.tradeDate='20230717', self.openTime='161500', self.closeTime='161959',self.symbol='BTCUSDT',self.open=30274.0, self.close=30275.3, self.high=30275.3, self.low=30270.1, self.vol=281.515, self.amt=8522322.8303, ukdf['pct'].iloc[-1]=4.6e-05 , ukdf['amount'].iloc[-1]=8522322.8303, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5955, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '13.926', 'enterprice': '26864.9', 'countrevence': '0', 'unrealprofit': '-47514.1194', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '30276.8', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1
--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=373746.4768026, self.flagDict['side']='sell', self.tradeCount=2, self.count=18497
self.closeSec=1689582299, self.tradeDate='20230717', self.openTime='162000', self.closeTime='162459', self.symbol='BTCUSDT', self.open=30275.3, self.close=30284.1, self.high=30284.1, self.low=30275.2, self.vol=285.08, self.amt=8632577.4868 
127.0.0.1 - - [17/Jul/2023 16:25:00] "POST / HTTP/1.1" 200 -
2023-07-17 16:25:00,817:INFO:amihud:main.py:172:handleKline:2219019: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5952  20230717   160000    160459  ...         0.0        0.0       0
5953  20230717   160500    160959  ...         0.0        0.0       0
5954  20230717   161000    161459  ...         0.0        0.0       0
5955  20230717   161500    161959  ...         0.0        0.0       0
5956  20230717   162000    162459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-07-17 16:25:00,817:INFO:amihud:main.py:175:handleKline:2219019: self.closeSec=1689582299, self.tradeDate='20230717', self.openTime='162000', self.closeTime='162459',self.symbol='BTCUSDT',self.open=30275.3, self.close=30284.1, self.high=30284.1, self.low=30275.2, self.vol=285.08, self.amt=8632577.4868, ukdf['pct'].iloc[-1]=0.000291 , ukdf['amount'].iloc[-1]=8632577.4868, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5956, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '13.926', 'enterprice': '26864.9', 'countrevence': '0', 'unrealprofit': '-47615.7792', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '30284.1', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1


## /root/FIL/strategy/factorcheck/log.txt ----- -----


self.closeSec=1689581999, self.tradeDate='20230717', self.openTime='161500', self.closeTime='161959', self.symbol='BTCUSDT', self.open=30274.0, self.close=30275.3, self.high=30275.3, self.low=30270.1 
127.0.0.1 - - [17/Jul/2023 16:20:01] "POST / HTTP/1.1" 200 -
2023-07-17 16:20:04,091:INFO:factorcheck2:main.py:126:handleKline:2218005: self.closeSec=1689581999, self.tradeDate='20230717', self.openTime='161500', self.closeTime='161959',self.symbol='BTCUSDT',self.open=30274.0, self.close=30275.3, self.high=30275.3, self.low=30270.1   
2023-07-17 16:20:05,191:INFO:factorcheck2:main.py:127:handleKline:2218005: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1631  20230717   155500    155959  1689580799  ...  30253.4  0.000241   1631    5
1632  20230717   160000    160459  1689581099  ...  30256.3 -0.000294   1632    0
1633  20230717   160500    160959  1689581399  ...  30249.8  0.000466   1633    1
1634  20230717   161000    161459  1689581699  ...  30265.6  0.000116   1634    2
1635  20230717   161500    161959  1689581999  ...  30270.1  0.000046   1635    3

[5 rows x 11 columns]
2023-07-17 16:20:05,202:INFO:factorcheck2:main.py:128:handleKline:2218005: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}
127.0.0.1 - - [17/Jul/2023 16:25:00] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=4, self.factor=0.528569792289432, self.count=18499 

self.closeSec=1689582299, self.tradeDate='20230717', self.openTime='162000', self.closeTime='162459', self.symbol='BTCUSDT', self.open=30275.3, self.close=30284.1, self.high=30284.1, self.low=30275.2 
2023-07-17 16:25:00,783:INFO:factorcheck2:main.py:126:handleKline:2218005: self.closeSec=1689582299, self.tradeDate='20230717', self.openTime='162000', self.closeTime='162459',self.symbol='BTCUSDT',self.open=30275.3, self.close=30284.1, self.high=30284.1, self.low=30275.2   
2023-07-17 16:25:00,812:INFO:factorcheck2:main.py:127:handleKline:2218005: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1632  20230717   160000    160459  1689581099  ...  30256.3 -0.000294   1632    0
1633  20230717   160500    160959  1689581399  ...  30249.8  0.000466   1633    1
1634  20230717   161000    161459  1689581699  ...  30265.6  0.000116   1634    2
1635  20230717   161500    161959  1689581999  ...  30270.1  0.000046   1635    3
1636  20230717   162000    162459  1689582299  ...  30275.2  0.000291   1636    4

[5 rows x 11 columns]
2023-07-17 16:25:00,812:INFO:factorcheck2:main.py:128:handleKline:2218005: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}


## /root/FIL/strategy/logic/log.txt ----- -----

2023-07-17 16:00:17,906:DEBUG:logic:main.py:463:getModel:2218526: df_s.iloc[-5:,:] :
          date closeTime     open  ...    alpha58   alpha67   alpha72
5786  20230717    132959  30281.2  ...  52.916667  0.479744  0.464953
5787  20230717    135959  30284.0  ...  52.500000  0.468507  0.472425
5788  20230717    142959  30250.5  ...  52.500000  0.472358  0.477345
5789  20230717    145959  30260.8  ...  52.500000  0.472050  0.482118
5790  20230717    152959  30259.8  ...  52.500000  0.477037  0.483975

[5 rows x 33 columns]
0.5129151291512916
acc is : 0.5129151291512916
2023-07-17 16:00:17,981:INFO:logic:main.py:468:getModel:2218526: df_pred.iloc[-5:,:] :
     pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
537     0  0.516244  0.483756       0  ...  1.008632   1.0    0.0  0.994964
538     0  0.502544  0.497456       1  ...  1.008972   1.0    0.0  0.995300
539     0  0.511230  0.488770       0  ...  1.008942   1.0    0.0  0.995270
540     0  0.508077  0.491923       1  ...  1.009372   1.0    0.0  0.995695
541     0  0.513317  0.486683       0  ...  1.009119   1.0    0.0  0.995445

[5 rows x 10 columns]
2023-07-17 16:00:17,995:INFO:logic:main.py:478:getModel:2218526: df_panel.iloc[-5:,:] :
    pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
45     0  0.516290  0.483710       0  ...  1.008632   1.0    0.0  0.994091
46     0  0.502247  0.497753       1  ...  1.008972   1.0    0.0  0.992486
47     0  0.511196  0.488804       0  ...  1.008942   1.0    0.0  0.992502
48     0  0.507728  0.492272       1  ...  1.009372   1.0    0.0  0.992808
49     0  0.513317  0.486683       0  ...  1.009119   1.0    0.0  0.995445

[5 rows x 10 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '24.219', 'enterprice': '30360.8', 'countrevence': '0', 'unrealprofit': '-2305.6488', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '30265.6', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}


## /root/FIL/strategy/modifiedmom/log.txt ----- -----

527  20230717   155000    155959  1689580799  30249.6  30265.2  0.000512
2023-07-17 16:00:02,071:INFO:modifiedmom:main.py:146:handleKline:2218259: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': True, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True}

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=9248 

self.closeSec=1689581399, self.tradeDate='20230717', self.openTime='160000', self.closeTime='160959', self.symbol='BTCUSDT', self.open='30265.2', self.close='30270.4'
127.0.0.1 - - [17/Jul/2023 16:10:01] "POST / HTTP/1.1" 200 -
2023-07-17 16:10:01,100:INFO:modifiedmom:main.py:144:handleKline:2218259: self.closeSec=1689581399, self.tradeDate='20230717', self.openTime='160000', self.closeTime='160959',self.symbol='BTCUSDT',self.open='30265.2', self.close='30270.4'
2023-07-17 16:10:01,111:INFO:modifiedmom:main.py:145:handleKline:2218259: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
524  20230717   152000    152959  1689578999  30248.4  30272.8  0.000810
525  20230717   153000    153959  1689579599  30272.8  30254.7 -0.000598
526  20230717   154000    154959  1689580199  30254.6  30249.7 -0.000165
527  20230717   155000    155959  1689580799  30249.6  30265.2  0.000512
528  20230717   160000    160959  1689581399  30265.2  30270.4  0.000172
2023-07-17 16:10:01,111:INFO:modifiedmom:main.py:146:handleKline:2218259: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': True, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True}

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=9249 

self.closeSec=1689581999, self.tradeDate='20230717', self.openTime='161000', self.closeTime='161959', self.symbol='BTCUSDT', self.open='30270.5', self.close='30275.3'
127.0.0.1 - - [17/Jul/2023 16:20:04] "POST / HTTP/1.1" 200 -
2023-07-17 16:20:06,727:INFO:modifiedmom:main.py:144:handleKline:2218259: self.closeSec=1689581999, self.tradeDate='20230717', self.openTime='161000', self.closeTime='161959',self.symbol='BTCUSDT',self.open='30270.5', self.close='30275.3'
2023-07-17 16:20:07,348:INFO:modifiedmom:main.py:145:handleKline:2218259: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
525  20230717   153000    153959  1689579599  30272.8  30254.7 -0.000598
526  20230717   154000    154959  1689580199  30254.6  30249.7 -0.000165
527  20230717   155000    155959  1689580799  30249.6  30265.2  0.000512
528  20230717   160000    160959  1689581399  30265.2  30270.4  0.000172
529  20230717   161000    161959  1689581999  30270.5  30275.3  0.000162
2023-07-17 16:20:07,348:INFO:modifiedmom:main.py:146:handleKline:2218259: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': True, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True}


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

17519  20230717   155000    155959  1689580799  30249.6  30265.2
2023-07-17 16:00:02,076:INFO:pyemd2:main.py:127:handleKline:2217508: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=9251 

self.closeSec=1689581399, self.tradeDate='20230717', self.openTime='160000', self.closeTime='160959', self.symbol='BTCUSDT', self.open='30265.2', self.close='30270.4'
2023-07-17 16:10:01,099:INFO:pyemd2:main.py:125:handleKline:2217508: self.closeSec=1689581399, self.tradeDate='20230717', self.openTime='160000', self.closeTime='160959',self.symbol='BTCUSDT',self.open='30265.2', self.close='30270.4'
127.0.0.1 - - [17/Jul/2023 16:10:01] "POST / HTTP/1.1" 200 -
2023-07-17 16:10:01,117:INFO:pyemd2:main.py:126:handleKline:2217508: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17516  20230717   152000    152959  1689578999  30248.4  30272.8
17517  20230717   153000    153959  1689579599  30272.8  30254.7
17518  20230717   154000    154959  1689580199  30254.6  30249.7
17519  20230717   155000    155959  1689580799  30249.6  30265.2
17520  20230717   160000    160959  1689581399  30265.2  30270.4
2023-07-17 16:10:01,117:INFO:pyemd2:main.py:127:handleKline:2217508: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=9252 

self.closeSec=1689581999, self.tradeDate='20230717', self.openTime='161000', self.closeTime='161959', self.symbol='BTCUSDT', self.open='30270.5', self.close='30275.3'
127.0.0.1 - - [17/Jul/2023 16:20:04] "POST / HTTP/1.1" 200 -
2023-07-17 16:20:08,031:INFO:pyemd2:main.py:125:handleKline:2217508: self.closeSec=1689581999, self.tradeDate='20230717', self.openTime='161000', self.closeTime='161959',self.symbol='BTCUSDT',self.open='30270.5', self.close='30275.3'
2023-07-17 16:20:08,273:INFO:pyemd2:main.py:126:handleKline:2217508: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17517  20230717   153000    153959  1689579599  30272.8  30254.7
17518  20230717   154000    154959  1689580199  30254.6  30249.7
17519  20230717   155000    155959  1689580799  30249.6  30265.2
17520  20230717   160000    160959  1689581399  30265.2  30270.4
17521  20230717   161000    161959  1689581999  30270.5  30275.3
2023-07-17 16:20:08,273:INFO:pyemd2:main.py:127:handleKline:2217508: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}


## /root/FIL/strategy/similarity/log.txt ----- -----

12191  20230717   155000    155959  1689580799  30249.6  30265.2
2023-07-17 16:00:02,062:INFO:testStrategy:main.py:103:handleKline:2217133: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}
127.0.0.1 - - [17/Jul/2023 16:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=9251 

self.closeSec=1689581399, self.tradeDate='20230717', self.openTime='160000', self.closeTime='160959', self.symbol='BTCUSDT', self.open='30265.2', self.close='30270.4'
2023-07-17 16:10:01,095:INFO:testStrategy:main.py:101:handleKline:2217133: self.closeSec=1689581399, self.tradeDate='20230717', self.openTime='160000', self.closeTime='160959',self.symbol='BTCUSDT',self.open='30265.2', self.close='30270.4'
2023-07-17 16:10:01,105:INFO:testStrategy:main.py:102:handleKline:2217133: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12188  20230717   152000    152959  1689578999  30248.4  30272.8
12189  20230717   153000    153959  1689579599  30272.8  30254.7
12190  20230717   154000    154959  1689580199  30254.6  30249.7
12191  20230717   155000    155959  1689580799  30249.6  30265.2
12192  20230717   160000    160959  1689581399  30265.2  30270.4
2023-07-17 16:10:01,105:INFO:testStrategy:main.py:103:handleKline:2217133: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=9252 

self.closeSec=1689581999, self.tradeDate='20230717', self.openTime='161000', self.closeTime='161959', self.symbol='BTCUSDT', self.open='30270.5', self.close='30275.3'
127.0.0.1 - - [17/Jul/2023 16:20:04] "POST / HTTP/1.1" 200 -
2023-07-17 16:20:07,860:INFO:testStrategy:main.py:101:handleKline:2217133: self.closeSec=1689581999, self.tradeDate='20230717', self.openTime='161000', self.closeTime='161959',self.symbol='BTCUSDT',self.open='30270.5', self.close='30275.3'
2023-07-17 16:20:08,143:INFO:testStrategy:main.py:102:handleKline:2217133: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12189  20230717   153000    153959  1689579599  30272.8  30254.7
12190  20230717   154000    154959  1689580199  30254.6  30249.7
12191  20230717   155000    155959  1689580799  30249.6  30265.2
12192  20230717   160000    160959  1689581399  30265.2  30270.4
12193  20230717   161000    161959  1689581999  30270.5  30275.3
2023-07-17 16:20:08,144:INFO:testStrategy:main.py:103:handleKline:2217133: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}


## /root/FIL/strategy/sr_min/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=1, self.total=996015.990996, self.flagDict['side']='buy', self.tradeCount=1, self.count=18496
self.closeSec=1689581999, self.tradeDate='20230717', self.openTime='161500', self.closeTime='161959', self.symbol='BTCUSDT', self.open=30274.0, self.close=30275.3, self.high=30275.3, self.low=30270.1, self.vol=281.515, self.amt=8522322.8303 
127.0.0.1 - - [17/Jul/2023 16:20:01] "POST / HTTP/1.1" 200 -
2023-07-17 16:20:06,321:INFO:sr_min:main.py:172:handleKline:2219263: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5951  20230717   155500    155959  ...         0.0        0.0       0
5952  20230717   160000    160459  ...         0.0        0.0       0
5953  20230717   160500    160959  ...         0.0        0.0       0
5954  20230717   161000    161459  ...         0.0        0.0       0
5955  20230717   161500    161959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-07-17 16:20:06,342:INFO:sr_min:main.py:175:handleKline:2219263: self.closeSec=1689581999, self.tradeDate='20230717', self.openTime='161500', self.closeTime='161959',self.symbol='BTCUSDT',self.open=30274.0, self.close=30275.3, self.high=30275.3, self.low=30270.1, self.vol=281.515, self.amt=8522322.8303, ukdf['pct'].iloc[-1]=4.6e-05 , ukdf['amount'].iloc[-1]=8522322.8303, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5955, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '37.141', 'enterprice': '26844', 'countrevence': '0', 'unrealprofit': '127497.6248', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '30276.8', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=1
127.0.0.1 - - [17/Jul/2023 16:25:00] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=1, self.total=996015.990996, self.flagDict['side']='buy', self.tradeCount=1, self.count=18497
self.closeSec=1689582299, self.tradeDate='20230717', self.openTime='162000', self.closeTime='162459', self.symbol='BTCUSDT', self.open=30275.3, self.close=30284.1, self.high=30284.1, self.low=30275.2, self.vol=285.08, self.amt=8632577.4868 
2023-07-17 16:25:00,809:INFO:sr_min:main.py:172:handleKline:2219263: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5952  20230717   160000    160459  ...         0.0        0.0       0
5953  20230717   160500    160959  ...         0.0        0.0       0
5954  20230717   161000    161459  ...         0.0        0.0       0
5955  20230717   161500    161959  ...         0.0        0.0       0
5956  20230717   162000    162459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-07-17 16:25:00,809:INFO:sr_min:main.py:175:handleKline:2219263: self.closeSec=1689582299, self.tradeDate='20230717', self.openTime='162000', self.closeTime='162459',self.symbol='BTCUSDT',self.open=30275.3, self.close=30284.1, self.high=30284.1, self.low=30275.2, self.vol=285.08, self.amt=8632577.4868, ukdf['pct'].iloc[-1]=0.000291 , ukdf['amount'].iloc[-1]=8632577.4868, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5956, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '37.141', 'enterprice': '26844', 'countrevence': '0', 'unrealprofit': '127768.7541', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '30284.1', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=1


## /root/FIL/strategy/s_rsrs/log.txt ----- -----

721  20230717   040000    075959  1689551999  ...    721  0.741507  1.372828     1.0
722  20230717   080000    115959  1689566399  ...    722  0.748426  1.368622     1.0

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '52.241', 'enterprice': '30511.1', 'countrevence': '0', 'unrealprofit': '-11088.98651003745', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '30298.83403055', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=1, self.sign=1
--handleKline--:  version='2.0.0', self.name='s_rsrs', self.symbol='BTCUSDT', interval='4h', intervalSec=14400, wid=25, thd=0.6, self.sign=1, self.total=1592336.4447248997, self.flagDict['side']='buy', self.tradeCount=11, self.count=385127.0.0.1 - - [17/Jul/2023 16:00:01] "POST / HTTP/1.1" 200 -

self.closeSec=1689580799, self.tradeDate='20230717', self.openTime='120000', self.closeTime='155959', self.symbol='BTCUSDT', self.open=30295.9, self.close=30265.2, self.high=30313.9, self.low=30220.2, self.vol=13248.606, self.amt=401011097.5421 
2023-07-17 16:00:01,650:INFO:s_rsrs:main.py:141:handleKline:2218689: self.closeSec=1689580799, self.tradeDate='20230717', self.openTime='120000', self.closeTime='155959',self.symbol='BTCUSDT',self.open=30295.9, self.close=30265.2, self.high=30313.9, self.low=30220.2, self.vol=13248.606, self.amt=401011097.5421 
2023-07-17 16:00:01,663:INFO:s_rsrs:main.py:142:handleKline:2218689: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime  ...        vol           amt       pct
719  20230716   200000    235959  ...  36284.911  1.101480e+09  0.002390
720  20230717   000000    035959  ...  29423.897  8.914104e+08 -0.004166
721  20230717   040000    075959  ...  25379.658  7.674281e+08 -0.000751
722  20230717   080000    115959  ...  22700.198  6.866654e+08  0.002618
723  20230717   120000    155959  ...  13248.606  4.010111e+08 -0.001013

[5 rows x 11 columns]
2023-07-17 16:00:02,405:INFO:s_rsrs:main.py:151:handleKline:2218689: df_s.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec  ...  index      beta    zscore  signal
719  20230716   200000    235959  1689523199  ...    719  0.710944  1.318667     1.0
720  20230717   000000    035959  1689537599  ...    720  0.725889  1.344754     1.0
721  20230717   040000    075959  1689551999  ...    721  0.741507  1.372828     1.0
722  20230717   080000    115959  1689566399  ...    722  0.748426  1.368622     1.0
723  20230717   120000    155959  1689580799  ...    723  0.755479  1.365454     1.0

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '52.241', 'enterprice': '30511.1', 'countrevence': '0', 'unrealprofit': '-12840.8378', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '30265.3', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=1, self.sign=1


