# 20230222 16:26:01

## /root/FIL/strategy/amihud/log.txt ----- -----

127.0.0.1 - - [22/Feb/2023 16:20:01] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=993672.4896432, self.flagDict['side']='sell', self.tradeCount=2, self.count=25084
self.closeSec=1677053999, self.tradeDate='20230222', self.openTime='161500', self.closeTime='161959', self.symbol='BTCUSDT', self.open=23999.3, self.close=23978.3, self.high=24017.4, self.low=23975.0, self.vol=1037.611, self.amt=24896809.7871 
2023-02-22 16:20:01,670:INFO:amihud:main.py:172:handleKline:200676: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5951  20230222   155500    155959  ...         0.0        0.0       0
5952  20230222   160000    160459  ...         0.0        0.0       0
5953  20230222   160500    160959  ...         0.0        0.0       0
5954  20230222   161000    161459  ...         0.0        0.0       0
5955  20230222   161500    161959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-02-22 16:20:01,674:INFO:amihud:main.py:175:handleKline:200676: self.closeSec=1677053999, self.tradeDate='20230222', self.openTime='161500', self.closeTime='161959',self.symbol='BTCUSDT',self.open=23999.3, self.close=23978.3, self.high=24017.4, self.low=23975.0, self.vol=1037.611, self.amt=24896809.7871, ukdf['pct'].iloc[-1]=-0.000875 , ukdf['amount'].iloc[-1]=24896809.7871, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5955, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '60.176', 'enterprice': '16529.3', 'countrevence': '0', 'unrealprofit': '-448226.99629366848', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '23977.90070948', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1
127.0.0.1 - - [22/Feb/2023 16:25:01] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=993672.4896432, self.flagDict['side']='sell', self.tradeCount=2, self.count=25085
self.closeSec=1677054299, self.tradeDate='20230222', self.openTime='162000', self.closeTime='162459', self.symbol='BTCUSDT', self.open=23976.4, self.close=24030.4, self.high=24030.4, self.low=23951.2, self.vol=1940.172, self.amt=46553330.9457 
2023-02-22 16:25:01,718:INFO:amihud:main.py:172:handleKline:200676: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5952  20230222   160000    160459  ...         0.0        0.0       0
5953  20230222   160500    160959  ...         0.0        0.0       0
5954  20230222   161000    161459  ...         0.0        0.0       0
5955  20230222   161500    161959  ...         0.0        0.0       0
5956  20230222   162000    162459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-02-22 16:25:01,720:INFO:amihud:main.py:175:handleKline:200676: self.closeSec=1677054299, self.tradeDate='20230222', self.openTime='162000', self.closeTime='162459',self.symbol='BTCUSDT',self.open=23976.4, self.close=24030.4, self.high=24030.4, self.low=23951.2, self.vol=1940.172, self.amt=46553330.9457, ukdf['pct'].iloc[-1]=0.002173 , ukdf['amount'].iloc[-1]=46553330.9457, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5956, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '60.176', 'enterprice': '16529.3', 'countrevence': '0', 'unrealprofit': '-451380.176', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '24030.3', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1


## /root/FIL/strategy/factorcheck/log.txt ----- -----

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.6985464299865545, self.count=25650 

self.closeSec=1677053999, self.tradeDate='20230222', self.openTime='161500', self.closeTime='161959', self.symbol='BTCUSDT', self.open=23999.3, self.close=23978.3, self.high=24017.4, self.low=23975.0 
2023-02-22 16:20:01,520:INFO:factorcheck2:main.py:126:handleKline:185239: self.closeSec=1677053999, self.tradeDate='20230222', self.openTime='161500', self.closeTime='161959',self.symbol='BTCUSDT',self.open=23999.3, self.close=23978.3, self.high=24017.4, self.low=23975.0   
2023-02-22 16:20:01,611:INFO:factorcheck2:main.py:127:handleKline:185239: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1631  20230222   155500    155959  1677052799  ...  24028.6 -0.000723   1631    5
1632  20230222   160000    160459  1677053099  ...  24021.1 -0.001106   1632    0
1633  20230222   160500    160959  1677053399  ...  24024.5  0.000104   1633    1
1634  20230222   161000    161459  1677053699  ...  23987.0 -0.001506   1634    2
1635  20230222   161500    161959  1677053999  ...  23975.0 -0.000875   1635    3

[5 rows x 11 columns]
2023-02-22 16:20:01,611:INFO:factorcheck2:main.py:128:handleKline:185239: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': False, 'isOpen': True, 'isClose': False, 'isTrig': True}
127.0.0.1 - - [22/Feb/2023 16:25:01] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.6985464299865545, self.count=25651 

self.closeSec=1677054299, self.tradeDate='20230222', self.openTime='162000', self.closeTime='162459', self.symbol='BTCUSDT', self.open=23976.4, self.close=24030.4, self.high=24030.4, self.low=23951.2 
2023-02-22 16:25:01,580:INFO:factorcheck2:main.py:126:handleKline:185239: self.closeSec=1677054299, self.tradeDate='20230222', self.openTime='162000', self.closeTime='162459',self.symbol='BTCUSDT',self.open=23976.4, self.close=24030.4, self.high=24030.4, self.low=23951.2   
2023-02-22 16:25:01,681:INFO:factorcheck2:main.py:127:handleKline:185239: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1632  20230222   160000    160459  1677053099  ...  24021.1 -0.001106   1632    0
1633  20230222   160500    160959  1677053399  ...  24024.5  0.000104   1633    1
1634  20230222   161000    161459  1677053699  ...  23987.0 -0.001506   1634    2
1635  20230222   161500    161959  1677053999  ...  23975.0 -0.000875   1635    3
1636  20230222   162000    162459  1677054299  ...  23951.2  0.002173   1636    4

[5 rows x 11 columns]
2023-02-22 16:25:01,681:INFO:factorcheck2:main.py:128:handleKline:185239: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': False, 'isOpen': True, 'isClose': False, 'isTrig': True}


## /root/FIL/strategy/logic/log.txt ----- -----

2023-02-22 16:00:34,347:DEBUG:logic:main.py:463:getModel:885513: df_s.iloc[-5:,:] :
          date closeTime     open  ...    alpha58   alpha67   alpha72
5786  20230222    132959  24155.4  ...  49.166667  0.421498  0.776613
5787  20230222    135959  24016.5  ...  49.583333  0.436135  0.773811
5788  20230222    142959  24104.2  ...  49.166667  0.427817  0.775579
5789  20230222    145959  24038.3  ...  49.166667  0.416776  0.783654
5790  20230222    152959  23948.4  ...  49.166667  0.422164  0.788916

[5 rows x 33 columns]
0.525830258302583
acc is : 0.525830258302583
2023-02-22 16:00:34,511:INFO:logic:main.py:468:getModel:885513: df_pred.iloc[-5:,:] :
     pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
537     1  0.479675  0.520325       1  ...  1.055560   1.0    0.0  1.113244
538     0  0.520632  0.479368       0  ...  1.052661   1.0    0.0  1.110186
539     1  0.493421  0.506579       0  ...  1.048715   1.0    0.0  1.106025
540     1  0.485796  0.514204       1  ...  1.050112   1.0    0.0  1.107498
541     0  0.510112  0.489888       1  ...  1.053598   1.0    0.0  1.111175

[5 rows x 10 columns]
2023-02-22 16:00:34,550:INFO:logic:main.py:478:getModel:885513: df_panel.iloc[-5:,:] :
    pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
45     1  0.481930  0.518070       1  ...  1.021301   1.0    0.0  1.117989
46     0  0.522402  0.477598       0  ...  1.052661   1.0    0.0  1.113756
47     1  0.494590  0.505410       0  ...  1.048715   1.0    0.0  1.107754
48     1  0.486208  0.513792       1  ...  1.050112   1.0    0.0  1.108748
49     0  0.510112  0.489888       1  ...  1.053598   1.0    0.0  1.111175

[5 rows x 10 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '33.816', 'enterprice': '24407.9', 'countrevence': '0', 'unrealprofit': '-11687.15367881448', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '24062.28982497', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}


## /root/FIL/strategy/modifiedmom/log.txt ----- -----

527  20230222   155000    155959  1677052799  24076.9  24059.6 -0.000719
2023-02-22 16:00:02,634:INFO:modifiedmom:main.py:146:handleKline:185213: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': True, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True}
127.0.0.1 - - [22/Feb/2023 16:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=12824 

self.closeSec=1677053399, self.tradeDate='20230222', self.openTime='160000', self.closeTime='160959', self.symbol='BTCUSDT', self.open='24059.5', self.close='24035.5'
2023-02-22 16:10:01,686:INFO:modifiedmom:main.py:144:handleKline:185213: self.closeSec=1677053399, self.tradeDate='20230222', self.openTime='160000', self.closeTime='160959',self.symbol='BTCUSDT',self.open='24059.5', self.close='24035.5'
2023-02-22 16:10:01,745:INFO:modifiedmom:main.py:145:handleKline:185213: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
524  20230222   152000    152959  1677050999  24014.5    23980 -0.001441
525  20230222   153000    153959  1677051599  23980.1    24037  0.002377
526  20230222   154000    154959  1677052199    24037  24076.9  0.001660
527  20230222   155000    155959  1677052799  24076.9  24059.6 -0.000719
528  20230222   160000    160959  1677053399  24059.5  24035.5 -0.001002
2023-02-22 16:10:01,745:INFO:modifiedmom:main.py:146:handleKline:185213: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': True, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True}
127.0.0.1 - - [22/Feb/2023 16:20:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=12825 

self.closeSec=1677053999, self.tradeDate='20230222', self.openTime='161000', self.closeTime='161959', self.symbol='BTCUSDT', self.open='24035.4', self.close='23976.3'
2023-02-22 16:20:01,692:INFO:modifiedmom:main.py:144:handleKline:185213: self.closeSec=1677053999, self.tradeDate='20230222', self.openTime='161000', self.closeTime='161959',self.symbol='BTCUSDT',self.open='24035.4', self.close='23976.3'
2023-02-22 16:20:01,752:INFO:modifiedmom:main.py:145:handleKline:185213: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
525  20230222   153000    153959  1677051599  23980.1    24037  0.002377
526  20230222   154000    154959  1677052199    24037  24076.9  0.001660
527  20230222   155000    155959  1677052799  24076.9  24059.6 -0.000719
528  20230222   160000    160959  1677053399  24059.5  24035.5 -0.001002
529  20230222   161000    161959  1677053999  24035.4  23976.3 -0.002463
2023-02-22 16:20:01,752:INFO:modifiedmom:main.py:146:handleKline:185213: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': True, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True}


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

17519  20230222   155000    155959  1677052799  24076.9  24059.6
2023-02-22 16:00:02,604:INFO:pyemd2:main.py:127:handleKline:185189: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}
127.0.0.1 - - [22/Feb/2023 16:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=12825 

self.closeSec=1677053399, self.tradeDate='20230222', self.openTime='160000', self.closeTime='160959', self.symbol='BTCUSDT', self.open='24059.5', self.close='24035.5'
2023-02-22 16:10:01,724:INFO:pyemd2:main.py:125:handleKline:185189: self.closeSec=1677053399, self.tradeDate='20230222', self.openTime='160000', self.closeTime='160959',self.symbol='BTCUSDT',self.open='24059.5', self.close='24035.5'
2023-02-22 16:10:01,767:INFO:pyemd2:main.py:126:handleKline:185189: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17516  20230222   152000    152959  1677050999  24014.5    23980
17517  20230222   153000    153959  1677051599  23980.1    24037
17518  20230222   154000    154959  1677052199    24037  24076.9
17519  20230222   155000    155959  1677052799  24076.9  24059.6
17520  20230222   160000    160959  1677053399  24059.5  24035.5
2023-02-22 16:10:01,768:INFO:pyemd2:main.py:127:handleKline:185189: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}
127.0.0.1 - - [22/Feb/2023 16:20:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=12826 

self.closeSec=1677053999, self.tradeDate='20230222', self.openTime='161000', self.closeTime='161959', self.symbol='BTCUSDT', self.open='24035.4', self.close='23976.3'
2023-02-22 16:20:01,718:INFO:pyemd2:main.py:125:handleKline:185189: self.closeSec=1677053999, self.tradeDate='20230222', self.openTime='161000', self.closeTime='161959',self.symbol='BTCUSDT',self.open='24035.4', self.close='23976.3'
2023-02-22 16:20:01,757:INFO:pyemd2:main.py:126:handleKline:185189: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17517  20230222   153000    153959  1677051599  23980.1    24037
17518  20230222   154000    154959  1677052199    24037  24076.9
17519  20230222   155000    155959  1677052799  24076.9  24059.6
17520  20230222   160000    160959  1677053399  24059.5  24035.5
17521  20230222   161000    161959  1677053999  24035.4  23976.3
2023-02-22 16:20:01,757:INFO:pyemd2:main.py:127:handleKline:185189: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}


## /root/FIL/strategy/similarity/log.txt ----- -----

12191  20230222   155000    155959  1677052799  24076.9  24059.6
2023-02-22 16:00:02,640:INFO:testStrategy:main.py:103:handleKline:185174: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}
127.0.0.1 - - [22/Feb/2023 16:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=12825 

self.closeSec=1677053399, self.tradeDate='20230222', self.openTime='160000', self.closeTime='160959', self.symbol='BTCUSDT', self.open='24059.5', self.close='24035.5'
2023-02-22 16:10:01,714:INFO:testStrategy:main.py:101:handleKline:185174: self.closeSec=1677053399, self.tradeDate='20230222', self.openTime='160000', self.closeTime='160959',self.symbol='BTCUSDT',self.open='24059.5', self.close='24035.5'
2023-02-22 16:10:01,758:INFO:testStrategy:main.py:102:handleKline:185174: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12188  20230222   152000    152959  1677050999  24014.5    23980
12189  20230222   153000    153959  1677051599  23980.1    24037
12190  20230222   154000    154959  1677052199    24037  24076.9
12191  20230222   155000    155959  1677052799  24076.9  24059.6
12192  20230222   160000    160959  1677053399  24059.5  24035.5
2023-02-22 16:10:01,758:INFO:testStrategy:main.py:103:handleKline:185174: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=12826 

self.closeSec=1677053999, self.tradeDate='20230222', self.openTime='161000', self.closeTime='161959', self.symbol='BTCUSDT', self.open='24035.4', self.close='23976.3'
127.0.0.1 - - [22/Feb/2023 16:20:01] "POST / HTTP/1.1" 200 -
2023-02-22 16:20:01,742:INFO:testStrategy:main.py:101:handleKline:185174: self.closeSec=1677053999, self.tradeDate='20230222', self.openTime='161000', self.closeTime='161959',self.symbol='BTCUSDT',self.open='24035.4', self.close='23976.3'
2023-02-22 16:20:01,762:INFO:testStrategy:main.py:102:handleKline:185174: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12189  20230222   153000    153959  1677051599  23980.1    24037
12190  20230222   154000    154959  1677052199    24037  24076.9
12191  20230222   155000    155959  1677052799  24076.9  24059.6
12192  20230222   160000    160959  1677053399  24059.5  24035.5
12193  20230222   161000    161959  1677053999  24035.4  23976.3
2023-02-22 16:20:01,762:INFO:testStrategy:main.py:103:handleKline:185174: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}


## /root/FIL/strategy/sr_min/log.txt ----- -----

127.0.0.1 - - [22/Feb/2023 16:20:01] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=0, self.total=1000000.0, self.flagDict['side']='', self.tradeCount=0, self.count=21082
self.closeSec=1677053999, self.tradeDate='20230222', self.openTime='161500', self.closeTime='161959', self.symbol='BTCUSDT', self.open=23999.3, self.close=23978.3, self.high=24017.4, self.low=23975.0, self.vol=1037.611, self.amt=24896809.7871 
2023-02-22 16:20:01,639:INFO:sr_min:main.py:172:handleKline:449472: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5951  20230222   155500    155959  ...         0.0        0.0       0
5952  20230222   160000    160459  ...         0.0        0.0       0
5953  20230222   160500    160959  ...         0.0        0.0       0
5954  20230222   161000    161459  ...         0.0        0.0       0
5955  20230222   161500    161959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-02-22 16:20:01,641:INFO:sr_min:main.py:175:handleKline:449472: self.closeSec=1677053999, self.tradeDate='20230222', self.openTime='161500', self.closeTime='161959',self.symbol='BTCUSDT',self.open=23999.3, self.close=23978.3, self.high=24017.4, self.low=23975.0, self.vol=1037.611, self.amt=24896809.7871, ukdf['pct'].iloc[-1]=-0.000875 , ukdf['amount'].iloc[-1]=24896809.7871, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5955, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': []}
type(curSign)=<class 'int'>, curSign=0, self.sign=0
127.0.0.1 - - [22/Feb/2023 16:25:01] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=0, self.total=1000000.0, self.flagDict['side']='', self.tradeCount=0, self.count=21083
self.closeSec=1677054299, self.tradeDate='20230222', self.openTime='162000', self.closeTime='162459', self.symbol='BTCUSDT', self.open=23976.4, self.close=24030.4, self.high=24030.4, self.low=23951.2, self.vol=1940.172, self.amt=46553330.9457 
2023-02-22 16:25:01,717:INFO:sr_min:main.py:172:handleKline:449472: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5952  20230222   160000    160459  ...         0.0        0.0       0
5953  20230222   160500    160959  ...         0.0        0.0       0
5954  20230222   161000    161459  ...         0.0        0.0       0
5955  20230222   161500    161959  ...         0.0        0.0       0
5956  20230222   162000    162459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-02-22 16:25:01,717:INFO:sr_min:main.py:175:handleKline:449472: self.closeSec=1677054299, self.tradeDate='20230222', self.openTime='162000', self.closeTime='162459',self.symbol='BTCUSDT',self.open=23976.4, self.close=24030.4, self.high=24030.4, self.low=23951.2, self.vol=1940.172, self.amt=46553330.9457, ukdf['pct'].iloc[-1]=0.002173 , ukdf['amount'].iloc[-1]=46553330.9457, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5956, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': []}
type(curSign)=<class 'int'>, curSign=0, self.sign=0


## /root/FIL/strategy/s_rsrs/log.txt ----- -----

721  20230222   040000    075959  1677023999  ...    721  0.037081 -1.436210    -1.0
722  20230222   080000    115959  1677038399  ...    722  0.130064 -1.182392    -1.0

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '36.465', 'enterprice': '24934.8', 'countrevence': '0', 'unrealprofit': '26758.110707757', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '24200.9974302', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-1, self.sign=-1
--handleKline--:  version='2.0.0', self.name='s_rsrs', self.symbol='BTCUSDT', interval='4h', intervalSec=14400, wid=25, thd=0.6, self.sign=-1, self.total=908338.234518, self.flagDict['side']='sell', self.tradeCount=21, self.count=534127.0.0.1 - - [22/Feb/2023 16:00:02] "POST / HTTP/1.1" 200 -

self.closeSec=1677052799, self.tradeDate='20230222', self.openTime='120000', self.closeTime='155959', self.symbol='BTCUSDT', self.open=24198.7, self.close=24059.6, self.high=24220.2, self.low=23925.5, self.vol=84541.648, self.amt=2033516340.4865 
2023-02-22 16:00:02,363:INFO:s_rsrs:main.py:141:handleKline:185271: self.closeSec=1677052799, self.tradeDate='20230222', self.openTime='120000', self.closeTime='155959',self.symbol='BTCUSDT',self.open=24198.7, self.close=24059.6, self.high=24220.2, self.low=23925.5, self.vol=84541.648, self.amt=2033516340.4865 
2023-02-22 16:00:02,423:INFO:s_rsrs:main.py:142:handleKline:185271: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime  ...         vol           amt       pct
719  20230221   200000    235959  ...  141571.537  3.482794e+09 -0.000761
720  20230222   000000    035959  ...  140748.886  3.451157e+09  0.002187
721  20230222   040000    075959  ...  105687.690  2.571925e+09 -0.006677
722  20230222   080000    115959  ...  128324.856  3.100163e+09 -0.010007
723  20230222   120000    155959  ...   84541.648  2.033516e+09 -0.005752

[5 rows x 11 columns]
2023-02-22 16:00:04,804:INFO:s_rsrs:main.py:151:handleKline:185271: df_s.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec  ...  index      beta    zscore  signal
719  20230221   200000    235959  1676995199  ...    719  0.092406 -1.360631    -1.0
720  20230222   000000    035959  1677009599  ...    720  0.043129 -1.451441    -1.0
721  20230222   040000    075959  1677023999  ...    721  0.037081 -1.436210    -1.0
722  20230222   080000    115959  1677038399  ...    722  0.130064 -1.182392    -1.0
723  20230222   120000    155959  1677052799  ...    723  0.211909 -0.964276    -1.0

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '36.465', 'enterprice': '24934.8', 'countrevence': '0', 'unrealprofit': '31900.0183759257', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '24059.98803302', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-1, self.sign=-1


