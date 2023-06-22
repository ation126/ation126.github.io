# 20230622 16:26:01

## /root/FIL/strategy/amihud/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=373746.4768026, self.flagDict['side']='sell', self.tradeCount=2, self.count=11296
self.closeSec=1687421999, self.tradeDate='20230622', self.openTime='161500', self.closeTime='161959', self.symbol='BTCUSDT', self.open=30111.0, self.close=30079.1, self.high=30119.0, self.low=30074.8, self.vol=812.152, self.amt=24442227.0532 
127.0.0.1 - - [22/Jun/2023 16:20:02] "POST / HTTP/1.1" 200 -
2023-06-22 16:20:07,683:INFO:amihud:main.py:172:handleKline:2219019: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5951  20230622   155500    155959  ...         0.0        0.0       0
5952  20230622   160000    160459  ...         0.0        0.0       0
5953  20230622   160500    160959  ...         0.0        0.0       0
5954  20230622   161000    161459  ...         0.0        0.0       0
5955  20230622   161500    161959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-06-22 16:20:07,714:INFO:amihud:main.py:175:handleKline:2219019: self.closeSec=1687421999, self.tradeDate='20230622', self.openTime='161500', self.closeTime='161959',self.symbol='BTCUSDT',self.open=30111.0, self.close=30079.1, self.high=30119.0, self.low=30074.8, self.vol=812.152, self.amt=24442227.0532, ukdf['pct'].iloc[-1]=-0.001059 , ukdf['amount'].iloc[-1]=24442227.0532, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5955, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '13.926', 'enterprice': '26864.9', 'countrevence': '0', 'unrealprofit': '-44784.54356349534', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '30080.79426709', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1
127.0.0.1 - - [22/Jun/2023 16:25:00] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=373746.4768026, self.flagDict['side']='sell', self.tradeCount=2, self.count=11297
self.closeSec=1687422299, self.tradeDate='20230622', self.openTime='162000', self.closeTime='162459', self.symbol='BTCUSDT', self.open=30079.2, self.close=30086.3, self.high=30088.5, self.low=30062.0, self.vol=595.122, self.amt=17898996.4724 
2023-06-22 16:25:00,732:INFO:amihud:main.py:172:handleKline:2219019: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5952  20230622   160000    160459  ...         0.0        0.0       0
5953  20230622   160500    160959  ...         0.0        0.0       0
5954  20230622   161000    161459  ...         0.0        0.0       0
5955  20230622   161500    161959  ...         0.0        0.0       0
5956  20230622   162000    162459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-06-22 16:25:00,732:INFO:amihud:main.py:175:handleKline:2219019: self.closeSec=1687422299, self.tradeDate='20230622', self.openTime='162000', self.closeTime='162459',self.symbol='BTCUSDT',self.open=30079.2, self.close=30086.3, self.high=30088.5, self.low=30062.0, self.vol=595.122, self.amt=17898996.4724, ukdf['pct'].iloc[-1]=0.000239 , ukdf['amount'].iloc[-1]=17898996.4724, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5956, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '13.926', 'enterprice': '26864.9', 'countrevence': '0', 'unrealprofit': '-44868.20620629666', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '30086.80192491', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1


## /root/FIL/strategy/factorcheck/log.txt ----- -----


self.closeSec=1687421999, self.tradeDate='20230622', self.openTime='161500', self.closeTime='161959', self.symbol='BTCUSDT', self.open=30111.0, self.close=30079.1, self.high=30119.0, self.low=30074.8 
127.0.0.1 - - [22/Jun/2023 16:20:01] "POST / HTTP/1.1" 200 -
2023-06-22 16:20:04,993:INFO:factorcheck2:main.py:126:handleKline:2218005: self.closeSec=1687421999, self.tradeDate='20230622', self.openTime='161500', self.closeTime='161959',self.symbol='BTCUSDT',self.open=30111.0, self.close=30079.1, self.high=30119.0, self.low=30074.8   
2023-06-22 16:20:06,473:INFO:factorcheck2:main.py:127:handleKline:2218005: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1631  20230622   155500    155959  1687420799  ...  30068.1 -0.000020   1631    5
1632  20230622   160000    160459  1687421099  ...  30085.5  0.001043   1632    0
1633  20230622   160500    160959  1687421399  ...  30067.4 -0.001826   1633    1
1634  20230622   161000    161459  1687421699  ...  30069.8  0.001334   1634    2
1635  20230622   161500    161959  1687421999  ...  30074.8 -0.001059   1635    3

[5 rows x 11 columns]
2023-06-22 16:20:06,474:INFO:factorcheck2:main.py:128:handleKline:2218005: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}
127.0.0.1 - - [22/Jun/2023 16:25:00] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=261, self.factor=0.22746406037206413, self.count=11299 

self.closeSec=1687422299, self.tradeDate='20230622', self.openTime='162000', self.closeTime='162459', self.symbol='BTCUSDT', self.open=30079.2, self.close=30086.3, self.high=30088.5, self.low=30062.0 
2023-06-22 16:25:00,743:INFO:factorcheck2:main.py:126:handleKline:2218005: self.closeSec=1687422299, self.tradeDate='20230622', self.openTime='162000', self.closeTime='162459',self.symbol='BTCUSDT',self.open=30079.2, self.close=30086.3, self.high=30088.5, self.low=30062.0   
2023-06-22 16:25:00,757:INFO:factorcheck2:main.py:127:handleKline:2218005: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1632  20230622   160000    160459  1687421099  ...  30085.5  0.001043   1632    0
1633  20230622   160500    160959  1687421399  ...  30067.4 -0.001826   1633    1
1634  20230622   161000    161459  1687421699  ...  30069.8  0.001334   1634    2
1635  20230622   161500    161959  1687421999  ...  30074.8 -0.001059   1635    3
1636  20230622   162000    162459  1687422299  ...  30062.0  0.000239   1636    4

[5 rows x 11 columns]
2023-06-22 16:25:00,757:INFO:factorcheck2:main.py:128:handleKline:2218005: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}


## /root/FIL/strategy/logic/log.txt ----- -----

2023-06-22 16:00:19,223:DEBUG:logic:main.py:463:getModel:2218526: df_s.iloc[-5:,:] :
          date closeTime     open  ...    alpha58   alpha67   alpha72
5786  20230622    132959  30338.1  ...  57.500000  0.640969  0.265074
5787  20230622    135959  30294.1  ...  57.083333  0.638805  0.265218
5788  20230622    142959  30277.3  ...  57.083333  0.619167  0.270470
5789  20230622    145959  30120.6  ...  57.083333  0.619093  0.275391
5790  20230622    152959  30120.1  ...  57.083333  0.611255  0.282981

[5 rows x 33 columns]
0.5645756457564576
acc is : 0.5645756457564576
2023-06-22 16:00:19,299:INFO:logic:main.py:468:getModel:2218526: df_pred.iloc[-5:,:] :
     pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
537     1  0.462390  0.537610       0  ...  1.136202  -1.0    0.0  1.176299
538     1  0.481554  0.518446       0  ...  1.142075  -1.0    0.0  1.170218
539     1  0.456551  0.543449       0  ...  1.142097  -1.0    0.0  1.170195
540     1  0.482050  0.517950       0  ...  1.144475  -1.0    0.0  1.167759
541     1  0.468029  0.531971       1  ...  1.143059  -1.0    0.0  1.169204

[5 rows x 10 columns]
2023-06-22 16:00:19,310:INFO:logic:main.py:478:getModel:2218526: df_panel.iloc[-5:,:] :
    pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
45     1  0.465450  0.534550       0  ...  1.136202  -1.0    0.0  1.170663
46     1  0.484650  0.515350       0  ...  1.142075  -1.0    0.0  1.165387
47     1  0.458883  0.541117       0  ...  1.142097  -1.0    0.0  1.166239
48     1  0.484157  0.515843       0  ...  1.144475  -1.0    0.0  1.164456
49     1  0.468029  0.531971       1  ...  1.143059  -1.0    0.0  1.169204

[5 rows x 10 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '26.839', 'enterprice': '29991.1', 'countrevence': '0', 'unrealprofit': '-2565.66589779272', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '30086.69469048', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}


## /root/FIL/strategy/modifiedmom/log.txt ----- -----

527  20230622   155000    155959  1687420799  30083.5  30094.5  0.000173
2023-06-22 16:00:02,033:INFO:modifiedmom:main.py:146:handleKline:2218259: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': True, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True}
127.0.0.1 - - [22/Jun/2023 16:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=5648 

self.closeSec=1687421399, self.tradeDate='20230622', self.openTime='160000', self.closeTime='160959', self.symbol='BTCUSDT', self.open='30094.5', self.close='30070.9'
2023-06-22 16:10:01,142:INFO:modifiedmom:main.py:144:handleKline:2218259: self.closeSec=1687421399, self.tradeDate='20230622', self.openTime='160000', self.closeTime='160959',self.symbol='BTCUSDT',self.open='30094.5', self.close='30070.9'
2023-06-22 16:10:01,150:INFO:modifiedmom:main.py:145:handleKline:2218259: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
524  20230622   152000    152959  1687418999  30157.1  30057.3 -0.003309
525  20230622   153000    153959  1687419599  30051.8  30017.6 -0.001321
526  20230622   154000    154959  1687420199  30017.7  30089.3  0.002389
527  20230622   155000    155959  1687420799  30083.5  30094.5  0.000173
528  20230622   160000    160959  1687421399  30094.5  30070.9 -0.000784
2023-06-22 16:10:01,150:INFO:modifiedmom:main.py:146:handleKline:2218259: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': True, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True}

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=5649 

self.closeSec=1687421999, self.tradeDate='20230622', self.openTime='161000', self.closeTime='161959', self.symbol='BTCUSDT', self.open='30071', self.close='30079.1'
127.0.0.1 - - [22/Jun/2023 16:20:04] "POST / HTTP/1.1" 200 -
2023-06-22 16:20:07,402:INFO:modifiedmom:main.py:144:handleKline:2218259: self.closeSec=1687421999, self.tradeDate='20230622', self.openTime='161000', self.closeTime='161959',self.symbol='BTCUSDT',self.open='30071', self.close='30079.1'
2023-06-22 16:20:08,163:INFO:modifiedmom:main.py:145:handleKline:2218259: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
525  20230622   153000    153959  1687419599  30051.8  30017.6 -0.001321
526  20230622   154000    154959  1687420199  30017.7  30089.3  0.002389
527  20230622   155000    155959  1687420799  30083.5  30094.5  0.000173
528  20230622   160000    160959  1687421399  30094.5  30070.9 -0.000784
529  20230622   161000    161959  1687421999    30071  30079.1  0.000273
2023-06-22 16:20:08,165:INFO:modifiedmom:main.py:146:handleKline:2218259: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': True, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True}


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

17519  20230622   155000    155959  1687420799  30083.5  30094.5
2023-06-22 16:00:02,041:INFO:pyemd2:main.py:127:handleKline:2217508: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}
127.0.0.1 - - [22/Jun/2023 16:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=5651 

self.closeSec=1687421399, self.tradeDate='20230622', self.openTime='160000', self.closeTime='160959', self.symbol='BTCUSDT', self.open='30094.5', self.close='30070.9'
2023-06-22 16:10:01,124:INFO:pyemd2:main.py:125:handleKline:2217508: self.closeSec=1687421399, self.tradeDate='20230622', self.openTime='160000', self.closeTime='160959',self.symbol='BTCUSDT',self.open='30094.5', self.close='30070.9'
2023-06-22 16:10:01,131:INFO:pyemd2:main.py:126:handleKline:2217508: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17516  20230622   152000    152959  1687418999  30157.1  30057.3
17517  20230622   153000    153959  1687419599  30051.8  30017.6
17518  20230622   154000    154959  1687420199  30017.7  30089.3
17519  20230622   155000    155959  1687420799  30083.5  30094.5
17520  20230622   160000    160959  1687421399  30094.5  30070.9
2023-06-22 16:10:01,131:INFO:pyemd2:main.py:127:handleKline:2217508: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=5652 

self.closeSec=1687421999, self.tradeDate='20230622', self.openTime='161000', self.closeTime='161959', self.symbol='BTCUSDT', self.open='30071', self.close='30079.1'
127.0.0.1 - - [22/Jun/2023 16:20:04] "POST / HTTP/1.1" 200 -
2023-06-22 16:20:09,545:INFO:pyemd2:main.py:125:handleKline:2217508: self.closeSec=1687421999, self.tradeDate='20230622', self.openTime='161000', self.closeTime='161959',self.symbol='BTCUSDT',self.open='30071', self.close='30079.1'
2023-06-22 16:20:09,684:INFO:pyemd2:main.py:126:handleKline:2217508: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17517  20230622   153000    153959  1687419599  30051.8  30017.6
17518  20230622   154000    154959  1687420199  30017.7  30089.3
17519  20230622   155000    155959  1687420799  30083.5  30094.5
17520  20230622   160000    160959  1687421399  30094.5  30070.9
17521  20230622   161000    161959  1687421999    30071  30079.1
2023-06-22 16:20:09,685:INFO:pyemd2:main.py:127:handleKline:2217508: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}


## /root/FIL/strategy/similarity/log.txt ----- -----

12191  20230622   155000    155959  1687420799  30083.5  30094.5
2023-06-22 16:00:02,035:INFO:testStrategy:main.py:103:handleKline:2217133: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=5651 

self.closeSec=1687421399, self.tradeDate='20230622', self.openTime='160000', self.closeTime='160959', self.symbol='BTCUSDT', self.open='30094.5', self.close='30070.9'
2023-06-22 16:10:01,109:INFO:testStrategy:main.py:101:handleKline:2217133: self.closeSec=1687421399, self.tradeDate='20230622', self.openTime='160000', self.closeTime='160959',self.symbol='BTCUSDT',self.open='30094.5', self.close='30070.9'
127.0.0.1 - - [22/Jun/2023 16:10:01] "POST / HTTP/1.1" 200 -
2023-06-22 16:10:01,116:INFO:testStrategy:main.py:102:handleKline:2217133: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12188  20230622   152000    152959  1687418999  30157.1  30057.3
12189  20230622   153000    153959  1687419599  30051.8  30017.6
12190  20230622   154000    154959  1687420199  30017.7  30089.3
12191  20230622   155000    155959  1687420799  30083.5  30094.5
12192  20230622   160000    160959  1687421399  30094.5  30070.9
2023-06-22 16:10:01,117:INFO:testStrategy:main.py:103:handleKline:2217133: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=5652 

self.closeSec=1687421999, self.tradeDate='20230622', self.openTime='161000', self.closeTime='161959', self.symbol='BTCUSDT', self.open='30071', self.close='30079.1'
127.0.0.1 - - [22/Jun/2023 16:20:04] "POST / HTTP/1.1" 200 -
2023-06-22 16:20:09,036:INFO:testStrategy:main.py:101:handleKline:2217133: self.closeSec=1687421999, self.tradeDate='20230622', self.openTime='161000', self.closeTime='161959',self.symbol='BTCUSDT',self.open='30071', self.close='30079.1'
2023-06-22 16:20:09,353:INFO:testStrategy:main.py:102:handleKline:2217133: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12189  20230622   153000    153959  1687419599  30051.8  30017.6
12190  20230622   154000    154959  1687420199  30017.7  30089.3
12191  20230622   155000    155959  1687420799  30083.5  30094.5
12192  20230622   160000    160959  1687421399  30094.5  30070.9
12193  20230622   161000    161959  1687421999    30071  30079.1
2023-06-22 16:20:09,354:INFO:testStrategy:main.py:103:handleKline:2217133: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}


## /root/FIL/strategy/sr_min/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=1, self.total=996015.990996, self.flagDict['side']='buy', self.tradeCount=1, self.count=11296
self.closeSec=1687421999, self.tradeDate='20230622', self.openTime='161500', self.closeTime='161959', self.symbol='BTCUSDT', self.open=30111.0, self.close=30079.1, self.high=30119.0, self.low=30074.8, self.vol=812.152, self.amt=24442227.0532 
127.0.0.1 - - [22/Jun/2023 16:20:01] "POST / HTTP/1.1" 200 -
2023-06-22 16:20:07,613:INFO:sr_min:main.py:172:handleKline:2219263: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5951  20230622   155500    155959  ...         0.0        0.0       0
5952  20230622   160000    160459  ...         0.0        0.0       0
5953  20230622   160500    160959  ...         0.0        0.0       0
5954  20230622   161000    161459  ...         0.0        0.0       0
5955  20230622   161500    161959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-06-22 16:20:07,644:INFO:sr_min:main.py:175:handleKline:2219263: self.closeSec=1687421999, self.tradeDate='20230622', self.openTime='161500', self.closeTime='161959',self.symbol='BTCUSDT',self.open=30111.0, self.close=30079.1, self.high=30119.0, self.low=30074.8, self.vol=812.152, self.amt=24442227.0532, ukdf['pct'].iloc[-1]=-0.001059 , ukdf['amount'].iloc[-1]=24442227.0532, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5955, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '37.141', 'enterprice': '26844', 'countrevence': '0', 'unrealprofit': '120217.96361951623', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '30080.79932203', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=1
--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=1, self.total=996015.990996, self.flagDict['side']='buy', self.tradeCount=1, self.count=11297
self.closeSec=1687422299, self.tradeDate='20230622', self.openTime='162000', self.closeTime='162459', self.symbol='BTCUSDT', self.open=30079.2, self.close=30086.3, self.high=30088.5, self.low=30062.0, self.vol=595.122, self.amt=17898996.4724 
127.0.0.1 - - [22/Jun/2023 16:25:00] "POST / HTTP/1.1" 200 -
2023-06-22 16:25:00,775:INFO:sr_min:main.py:172:handleKline:2219263: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5952  20230622   160000    160459  ...         0.0        0.0       0
5953  20230622   160500    160959  ...         0.0        0.0       0
5954  20230622   161000    161459  ...         0.0        0.0       0
5955  20230622   161500    161959  ...         0.0        0.0       0
5956  20230622   162000    162459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-06-22 16:25:00,777:INFO:sr_min:main.py:175:handleKline:2219263: self.closeSec=1687422299, self.tradeDate='20230622', self.openTime='162000', self.closeTime='162459',self.symbol='BTCUSDT',self.open=30079.2, self.close=30086.3, self.high=30088.5, self.low=30062.0, self.vol=595.122, self.amt=17898996.4724, ukdf['pct'].iloc[-1]=0.000239 , ukdf['amount'].iloc[-1]=17898996.4724, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5956, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '37.141', 'enterprice': '26844', 'countrevence': '0', 'unrealprofit': '120440.90629308231', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '30086.80192491', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=1


## /root/FIL/strategy/s_rsrs/log.txt ----- -----

721  20230622   040000    075959  1687391999  ...    721  1.294642  2.812975     1.0
722  20230622   080000    115959  1687406399  ...    722  1.255200  2.543640     1.0

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '53.344', 'enterprice': '27977.7', 'countrevence': '0', 'unrealprofit': '123016.5984', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '30283.8', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=1, self.sign=1
127.0.0.1 - - [22/Jun/2023 16:00:01] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='s_rsrs', self.symbol='BTCUSDT', interval='4h', intervalSec=14400, wid=25, thd=0.6, self.sign=1, self.total=1490949.9863712, self.flagDict['side']='buy', self.tradeCount=7, self.count=235
self.closeSec=1687420799, self.tradeDate='20230622', self.openTime='120000', self.closeTime='155959', self.symbol='BTCUSDT', self.open=30283.7, self.close=30094.5, self.high=30341.5, self.low=30000.0, self.vol=59869.993, self.amt=1805752153.31762 
2023-06-22 16:00:01,618:INFO:s_rsrs:main.py:141:handleKline:2218689: self.closeSec=1687420799, self.tradeDate='20230622', self.openTime='120000', self.closeTime='155959',self.symbol='BTCUSDT',self.open=30283.7, self.close=30094.5, self.high=30341.5, self.low=30000.0, self.vol=59869.993, self.amt=1805752153.31762 
2023-06-22 16:00:01,642:INFO:s_rsrs:main.py:142:handleKline:2218689: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime  ...         vol           amt       pct
719  20230621   200000    235959  ...  322372.247  9.486852e+09  0.031940
720  20230622   000000    035959  ...  365241.928  1.103374e+10  0.008999
721  20230622   040000    075959  ...   81982.531  2.459183e+09 -0.003890
722  20230622   080000    115959  ...   84397.179  2.549850e+09  0.009847
723  20230622   120000    155959  ...   59869.993  1.805752e+09 -0.006248

[5 rows x 11 columns]
2023-06-22 16:00:02,963:INFO:s_rsrs:main.py:151:handleKline:2218689: df_s.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec  ...  index      beta    zscore  signal
719  20230621   200000    235959  1687363199  ...    719  1.341041  3.423802     1.0
720  20230622   000000    035959  1687377599  ...    720  1.404152  3.390565     1.0
721  20230622   040000    075959  1687391999  ...    721  1.294642  2.812975     1.0
722  20230622   080000    115959  1687406399  ...    722  1.255200  2.543640     1.0
723  20230622   120000    155959  1687420799  ...    723  1.187797  2.221400     1.0

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '53.344', 'enterprice': '27977.7', 'countrevence': '0', 'unrealprofit': '112918.5792', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '30094.5', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=1, self.sign=1


