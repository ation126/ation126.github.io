# 20230404 16:26:02

## /root/FIL/strategy/amihud/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=993672.4896432, self.flagDict['side']='sell', self.tradeCount=2, self.count=36892
self.closeSec=1680596399, self.tradeDate='20230404', self.openTime='161500', self.closeTime='161959', self.symbol='BTCUSDT', self.open=27982.4, self.close=27959.1, self.high=27994.0, self.low=27950.6, self.vol=845.119, self.amt=23640757.252 
127.0.0.1 - - [04/Apr/2023 16:20:03] "POST / HTTP/1.1" 200 -
2023-04-04 16:20:09,060:INFO:amihud:main.py:172:handleKline:200676: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5951  20230404   155500    155959  ...         0.0        0.0       0
5952  20230404   160000    160459  ...         0.0        0.0       0
5953  20230404   160500    160959  ...         0.0        0.0       0
5954  20230404   161000    161459  ...         0.0        0.0       0
5955  20230404   161500    161959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-04-04 16:20:09,080:INFO:amihud:main.py:175:handleKline:200676: self.closeSec=1680596399, self.tradeDate='20230404', self.openTime='161500', self.closeTime='161959',self.symbol='BTCUSDT',self.open=27982.4, self.close=27959.1, self.high=27994.0, self.low=27950.6, self.vol=845.119, self.amt=23640757.252, ukdf['pct'].iloc[-1]=-0.000833 , ukdf['amount'].iloc[-1]=23640757.252, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5955, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '60.176', 'enterprice': '16529.3', 'countrevence': '0', 'unrealprofit': '-687701.42586737856', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '27957.46780556', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1
127.0.0.1 - - [04/Apr/2023 16:25:01] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=993672.4896432, self.flagDict['side']='sell', self.tradeCount=2, self.count=36893
self.closeSec=1680596699, self.tradeDate='20230404', self.openTime='162000', self.closeTime='162459', self.symbol='BTCUSDT', self.open=27959.1, self.close=27955.0, self.high=27973.4, self.low=27909.3, self.vol=1919.508, self.amt=53636507.73028 
2023-04-04 16:25:01,563:INFO:amihud:main.py:172:handleKline:200676: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5952  20230404   160000    160459  ...         0.0        0.0       0
5953  20230404   160500    160959  ...         0.0        0.0       0
5954  20230404   161000    161459  ...         0.0        0.0       0
5955  20230404   161500    161959  ...         0.0        0.0       0
5956  20230404   162000    162459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-04-04 16:25:01,563:INFO:amihud:main.py:175:handleKline:200676: self.closeSec=1680596699, self.tradeDate='20230404', self.openTime='162000', self.closeTime='162459',self.symbol='BTCUSDT',self.open=27959.1, self.close=27955.0, self.high=27973.4, self.low=27909.3, self.vol=1919.508, self.amt=53636507.73028, ukdf['pct'].iloc[-1]=-0.000147 , ukdf['amount'].iloc[-1]=53636507.73028, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5956, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '60.176', 'enterprice': '16529.3', 'countrevence': '0', 'unrealprofit': '-687577.0466120472', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '27955.40088095', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1


## /root/FIL/strategy/factorcheck/log.txt ----- -----


self.closeSec=1680596399, self.tradeDate='20230404', self.openTime='161500', self.closeTime='161959', self.symbol='BTCUSDT', self.open=27982.4, self.close=27959.1, self.high=27994.0, self.low=27950.6 
127.0.0.1 - - [04/Apr/2023 16:20:02] "POST / HTTP/1.1" 200 -
2023-04-04 16:20:06,418:INFO:factorcheck2:main.py:126:handleKline:185239: self.closeSec=1680596399, self.tradeDate='20230404', self.openTime='161500', self.closeTime='161959',self.symbol='BTCUSDT',self.open=27982.4, self.close=27959.1, self.high=27994.0, self.low=27950.6   
2023-04-04 16:20:07,769:INFO:factorcheck2:main.py:127:handleKline:185239: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1631  20230404   155500    155959  1680595199  ...  27995.2 -0.000667   1631    5
1632  20230404   160000    160459  1680595499  ...  28008.9  0.000246   1632    0
1633  20230404   160500    160959  1680595799  ...  27995.6 -0.000471   1633    1
1634  20230404   161000    161459  1680596099  ...  27981.6 -0.000875   1634    2
1635  20230404   161500    161959  1680596399  ...  27950.6 -0.000833   1635    3

[5 rows x 11 columns]
2023-04-04 16:20:07,769:INFO:factorcheck2:main.py:128:handleKline:185239: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': False, 'isOpen': True, 'isClose': False, 'isTrig': True}

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=42, self.factor=0.553448650180229, self.count=37459 

self.closeSec=1680596699, self.tradeDate='20230404', self.openTime='162000', self.closeTime='162459', self.symbol='BTCUSDT', self.open=27959.1, self.close=27955.0, self.high=27973.4, self.low=27909.3 
127.0.0.1 - - [04/Apr/2023 16:25:01] "POST / HTTP/1.1" 200 -
2023-04-04 16:25:01,493:INFO:factorcheck2:main.py:126:handleKline:185239: self.closeSec=1680596699, self.tradeDate='20230404', self.openTime='162000', self.closeTime='162459',self.symbol='BTCUSDT',self.open=27959.1, self.close=27955.0, self.high=27973.4, self.low=27909.3   
2023-04-04 16:25:01,506:INFO:factorcheck2:main.py:127:handleKline:185239: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1632  20230404   160000    160459  1680595499  ...  28008.9  0.000246   1632    0
1633  20230404   160500    160959  1680595799  ...  27995.6 -0.000471   1633    1
1634  20230404   161000    161459  1680596099  ...  27981.6 -0.000875   1634    2
1635  20230404   161500    161959  1680596399  ...  27950.6 -0.000833   1635    3
1636  20230404   162000    162459  1680596699  ...  27909.3 -0.000147   1636    4

[5 rows x 11 columns]
2023-04-04 16:25:01,506:INFO:factorcheck2:main.py:128:handleKline:185239: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': False, 'isOpen': True, 'isClose': False, 'isTrig': True}


## /root/FIL/strategy/logic/log.txt ----- -----

2023-04-04 16:00:34,635:DEBUG:logic:main.py:463:getModel:885513: df_s.iloc[-5:,:] :
          date closeTime     open  ...    alpha58   alpha67   alpha72
5786  20230404    132959  27797.7  ...  50.416667  0.477187  0.523421
5787  20230404    135959  27875.9  ...  50.000000  0.477048  0.520797
5788  20230404    142959  27875.0  ...  50.416667  0.479101  0.517707
5789  20230404    145959  27888.1  ...  50.416667  0.505353  0.500192
5790  20230404    152959  28063.1  ...  50.000000  0.499000  0.486243

[5 rows x 33 columns]
0.5461254612546126
acc is : 0.5461254612546126
2023-04-04 16:00:34,798:INFO:logic:main.py:468:getModel:885513: df_pred.iloc[-5:,:] :
     pred    prob_0    prob_1  actual  ...       nav  sign   cost_        bm
537     0  0.533951  0.466049       0  ...  0.887767  -1.0  0.0000  0.988899
538     0  0.516378  0.483622       1  ...  0.887347  -1.0  0.0000  0.989368
539     0  0.524379  0.475621       1  ...  0.881782  -1.0  0.0000  0.995573
540     0  0.564996  0.435004       0  ...  0.879010   1.0 -0.0016  0.994036
541     0  0.524625  0.475375       0  ...  0.878807   1.0  0.0000  0.993806

[5 rows x 10 columns]
2023-04-04 16:00:34,831:INFO:logic:main.py:478:getModel:885513: df_panel.iloc[-5:,:] :
    pred    prob_0    prob_1  actual  ...       nav  sign   cost_        bm
45     0  0.533176  0.466824       0  ...  0.887767  -1.0  0.0000  0.988268
46     0  0.514847  0.485153       1  ...  0.887347  -1.0  0.0000  0.983548
47     0  0.523541  0.476459       1  ...  0.881782  -1.0  0.0000  0.992186
48     0  0.564891  0.435109       0  ...  0.879010   1.0 -0.0016  0.990662
49     0  0.524625  0.475375       0  ...  0.878807   1.0  0.0000  0.993806

[5 rows x 10 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': []}


## /root/FIL/strategy/modifiedmom/log.txt ----- -----

527  20230404   155000    155959  1680595199  28021.9  28013.2 -0.000314
2023-04-04 16:00:02,086:INFO:modifiedmom:main.py:146:handleKline:185213: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': True, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True}

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=18728 

self.closeSec=1680595799, self.tradeDate='20230404', self.openTime='160000', self.closeTime='160959', self.symbol='BTCUSDT', self.open='28013.2', self.close='28006.9'
2023-04-04 16:10:01,597:INFO:modifiedmom:main.py:144:handleKline:185213: self.closeSec=1680595799, self.tradeDate='20230404', self.openTime='160000', self.closeTime='160959',self.symbol='BTCUSDT',self.open='28013.2', self.close='28006.9'
127.0.0.1 - - [04/Apr/2023 16:10:01] "POST / HTTP/1.1" 200 -
2023-04-04 16:10:01,612:INFO:modifiedmom:main.py:145:handleKline:185213: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
524  20230404   152000    152959  1680593399  28051.1  28019.7 -0.001119
525  20230404   153000    153959  1680593999  28019.7  27987.6 -0.001146
526  20230404   154000    154959  1680594599  27987.6    28022  0.001229
527  20230404   155000    155959  1680595199  28021.9  28013.2 -0.000314
528  20230404   160000    160959  1680595799  28013.2  28006.9 -0.000225
2023-04-04 16:10:01,612:INFO:modifiedmom:main.py:146:handleKline:185213: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': True, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True}

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=18729 

self.closeSec=1680596399, self.tradeDate='20230404', self.openTime='161000', self.closeTime='161959', self.symbol='BTCUSDT', self.open='28006.9', self.close='27959.1'
127.0.0.1 - - [04/Apr/2023 16:20:04] "POST / HTTP/1.1" 200 -
2023-04-04 16:20:07,839:INFO:modifiedmom:main.py:144:handleKline:185213: self.closeSec=1680596399, self.tradeDate='20230404', self.openTime='161000', self.closeTime='161959',self.symbol='BTCUSDT',self.open='28006.9', self.close='27959.1'
2023-04-04 16:20:08,719:INFO:modifiedmom:main.py:145:handleKline:185213: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
525  20230404   153000    153959  1680593999  28019.7  27987.6 -0.001146
526  20230404   154000    154959  1680594599  27987.6    28022  0.001229
527  20230404   155000    155959  1680595199  28021.9  28013.2 -0.000314
528  20230404   160000    160959  1680595799  28013.2  28006.9 -0.000225
529  20230404   161000    161959  1680596399  28006.9  27959.1 -0.001707
2023-04-04 16:20:08,719:INFO:modifiedmom:main.py:146:handleKline:185213: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': True, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True}


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

17519  20230404   155000    155959  1680595199  28021.9  28013.2
2023-04-04 16:00:02,104:INFO:pyemd2:main.py:127:handleKline:185189: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}
127.0.0.1 - - [04/Apr/2023 16:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=18729 

self.closeSec=1680595799, self.tradeDate='20230404', self.openTime='160000', self.closeTime='160959', self.symbol='BTCUSDT', self.open='28013.2', self.close='28006.9'
2023-04-04 16:10:01,585:INFO:pyemd2:main.py:125:handleKline:185189: self.closeSec=1680595799, self.tradeDate='20230404', self.openTime='160000', self.closeTime='160959',self.symbol='BTCUSDT',self.open='28013.2', self.close='28006.9'
2023-04-04 16:10:01,628:INFO:pyemd2:main.py:126:handleKline:185189: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17516  20230404   152000    152959  1680593399  28051.1  28019.7
17517  20230404   153000    153959  1680593999  28019.7  27987.6
17518  20230404   154000    154959  1680594599  27987.6    28022
17519  20230404   155000    155959  1680595199  28021.9  28013.2
17520  20230404   160000    160959  1680595799  28013.2  28006.9
2023-04-04 16:10:01,629:INFO:pyemd2:main.py:127:handleKline:185189: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=18730 

self.closeSec=1680596399, self.tradeDate='20230404', self.openTime='161000', self.closeTime='161959', self.symbol='BTCUSDT', self.open='28006.9', self.close='27959.1'
127.0.0.1 - - [04/Apr/2023 16:20:04] "POST / HTTP/1.1" 200 -
2023-04-04 16:20:10,960:INFO:pyemd2:main.py:125:handleKline:185189: self.closeSec=1680596399, self.tradeDate='20230404', self.openTime='161000', self.closeTime='161959',self.symbol='BTCUSDT',self.open='28006.9', self.close='27959.1'
2023-04-04 16:20:11,109:INFO:pyemd2:main.py:126:handleKline:185189: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17517  20230404   153000    153959  1680593999  28019.7  27987.6
17518  20230404   154000    154959  1680594599  27987.6    28022
17519  20230404   155000    155959  1680595199  28021.9  28013.2
17520  20230404   160000    160959  1680595799  28013.2  28006.9
17521  20230404   161000    161959  1680596399  28006.9  27959.1
2023-04-04 16:20:11,110:INFO:pyemd2:main.py:127:handleKline:185189: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}


## /root/FIL/strategy/similarity/log.txt ----- -----

12191  20230404   155000    155959  1680595199  28021.9  28013.2
2023-04-04 16:00:02,096:INFO:testStrategy:main.py:103:handleKline:185174: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}
127.0.0.1 - - [04/Apr/2023 16:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=18729 

self.closeSec=1680595799, self.tradeDate='20230404', self.openTime='160000', self.closeTime='160959', self.symbol='BTCUSDT', self.open='28013.2', self.close='28006.9'
2023-04-04 16:10:01,637:INFO:testStrategy:main.py:101:handleKline:185174: self.closeSec=1680595799, self.tradeDate='20230404', self.openTime='160000', self.closeTime='160959',self.symbol='BTCUSDT',self.open='28013.2', self.close='28006.9'
2023-04-04 16:10:01,677:INFO:testStrategy:main.py:102:handleKline:185174: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12188  20230404   152000    152959  1680593399  28051.1  28019.7
12189  20230404   153000    153959  1680593999  28019.7  27987.6
12190  20230404   154000    154959  1680594599  27987.6    28022
12191  20230404   155000    155959  1680595199  28021.9  28013.2
12192  20230404   160000    160959  1680595799  28013.2  28006.9
2023-04-04 16:10:01,677:INFO:testStrategy:main.py:103:handleKline:185174: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=18730 

self.closeSec=1680596399, self.tradeDate='20230404', self.openTime='161000', self.closeTime='161959', self.symbol='BTCUSDT', self.open='28006.9', self.close='27959.1'
127.0.0.1 - - [04/Apr/2023 16:20:04] "POST / HTTP/1.1" 200 -
2023-04-04 16:20:10,421:INFO:testStrategy:main.py:101:handleKline:185174: self.closeSec=1680596399, self.tradeDate='20230404', self.openTime='161000', self.closeTime='161959',self.symbol='BTCUSDT',self.open='28006.9', self.close='27959.1'
2023-04-04 16:20:10,731:INFO:testStrategy:main.py:102:handleKline:185174: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12189  20230404   153000    153959  1680593999  28019.7  27987.6
12190  20230404   154000    154959  1680594599  27987.6    28022
12191  20230404   155000    155959  1680595199  28021.9  28013.2
12192  20230404   160000    160959  1680595799  28013.2  28006.9
12193  20230404   161000    161959  1680596399  28006.9  27959.1
2023-04-04 16:20:10,738:INFO:testStrategy:main.py:103:handleKline:185174: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}


## /root/FIL/strategy/sr_min/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=0, self.total=1000000.0, self.flagDict['side']='', self.tradeCount=0, self.count=32890
self.closeSec=1680596399, self.tradeDate='20230404', self.openTime='161500', self.closeTime='161959', self.symbol='BTCUSDT', self.open=27982.4, self.close=27959.1, self.high=27994.0, self.low=27950.6, self.vol=845.119, self.amt=23640757.252 
127.0.0.1 - - [04/Apr/2023 16:20:03] "POST / HTTP/1.1" 200 -
2023-04-04 16:20:08,029:INFO:sr_min:main.py:172:handleKline:449472: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5951  20230404   155500    155959  ...         0.0        0.0       0
5952  20230404   160000    160459  ...         0.0        0.0       0
5953  20230404   160500    160959  ...         0.0        0.0       0
5954  20230404   161000    161459  ...         0.0        0.0       0
5955  20230404   161500    161959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-04-04 16:20:08,059:INFO:sr_min:main.py:175:handleKline:449472: self.closeSec=1680596399, self.tradeDate='20230404', self.openTime='161500', self.closeTime='161959',self.symbol='BTCUSDT',self.open=27982.4, self.close=27959.1, self.high=27994.0, self.low=27950.6, self.vol=845.119, self.amt=23640757.252, ukdf['pct'].iloc[-1]=-0.000833 , ukdf['amount'].iloc[-1]=23640757.252, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5955, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': []}
type(curSign)=<class 'int'>, curSign=0, self.sign=0
--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=0, self.total=1000000.0, self.flagDict['side']='', self.tradeCount=0, self.count=32891
self.closeSec=1680596699, self.tradeDate='20230404', self.openTime='162000', self.closeTime='162459', self.symbol='BTCUSDT', self.open=27959.1, self.close=27955.0, self.high=27973.4, self.low=27909.3, self.vol=1919.508, self.amt=53636507.73028 
127.0.0.1 - - [04/Apr/2023 16:25:01] "POST / HTTP/1.1" 200 -
2023-04-04 16:25:01,579:INFO:sr_min:main.py:172:handleKline:449472: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5952  20230404   160000    160459  ...         0.0        0.0       0
5953  20230404   160500    160959  ...         0.0        0.0       0
5954  20230404   161000    161459  ...         0.0        0.0       0
5955  20230404   161500    161959  ...         0.0        0.0       0
5956  20230404   162000    162459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-04-04 16:25:01,579:INFO:sr_min:main.py:175:handleKline:449472: self.closeSec=1680596699, self.tradeDate='20230404', self.openTime='162000', self.closeTime='162459',self.symbol='BTCUSDT',self.open=27959.1, self.close=27955.0, self.high=27973.4, self.low=27909.3, self.vol=1919.508, self.amt=53636507.73028, ukdf['pct'].iloc[-1]=-0.000147 , ukdf['amount'].iloc[-1]=53636507.73028, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5956, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': []}
type(curSign)=<class 'int'>, curSign=0, self.sign=0


## /root/FIL/strategy/s_rsrs/log.txt ----- -----

721  20230404   040000    075959  1680566399  ...    721  0.172701 -0.528990     NaN
722  20230404   080000    115959  1680580799  ...    722  0.188907 -0.456086     NaN

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '52.088', 'enterprice': '28398.8', 'countrevence': '0', 'unrealprofit': '28914.0488', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '27843.7', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-9223372036854775808, self.sign=-1
--handleKline--:  version='2.0.0', self.name='s_rsrs', self.symbol='BTCUSDT', interval='4h', intervalSec=14400, wid=25, thd=0.6, self.sign=-1, self.total=1477757.4577056, self.flagDict['side']='sell', self.tradeCount=29, self.count=780
self.closeSec=1680595199, self.tradeDate='20230404', self.openTime='120000', self.closeTime='155959', self.symbol='BTCUSDT', self.open=27843.6, self.close=28013.2, self.high=28141.6, self.low=27753.2, self.vol=58199.402, self.amt=1627344408.13814 
127.0.0.1 - - [04/Apr/2023 16:00:01] "POST / HTTP/1.1" 200 -
2023-04-04 16:00:01,907:INFO:s_rsrs:main.py:141:handleKline:185271: self.closeSec=1680595199, self.tradeDate='20230404', self.openTime='120000', self.closeTime='155959',self.symbol='BTCUSDT',self.open=27843.6, self.close=28013.2, self.high=28141.6, self.low=27753.2, self.vol=58199.402, self.amt=1627344408.13814 
2023-04-04 16:00:01,952:INFO:s_rsrs:main.py:142:handleKline:185271: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime  ...         vol           amt       pct
719  20230403   200000    235959  ...  141711.342  3.985696e+09 -0.007467
720  20230404   000000    035959  ...   99518.618  2.791907e+09  0.001398
721  20230404   040000    075959  ...  178714.809  4.945557e+09 -0.010174
722  20230404   080000    115959  ...   57048.555  1.586313e+09  0.002073
723  20230404   120000    155959  ...   58199.402  1.627344e+09  0.006088

[5 rows x 11 columns]
2023-04-04 16:00:04,538:INFO:s_rsrs:main.py:151:handleKline:185271: df_s.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec  ...  index      beta    zscore  signal
719  20230403   200000    235959  1680537599  ...    719  0.195187 -0.487681     NaN
720  20230404   000000    035959  1680551999  ...    720  0.195604 -0.468981     NaN
721  20230404   040000    075959  1680566399  ...    721  0.172701 -0.528990     NaN
722  20230404   080000    115959  1680580799  ...    722  0.188907 -0.456086     NaN
723  20230404   120000    155959  1680595199  ...    723  0.198068 -0.405388     NaN

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '52.088', 'enterprice': '28398.8', 'countrevence': '0', 'unrealprofit': '20079.924', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '28013.3', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-9223372036854775808, self.sign=-1


