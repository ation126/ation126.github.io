# 20230308 16:26:02

## /root/FIL/strategy/amihud/log.txt ----- -----

--handleKline--: 127.0.0.1 - - [08/Mar/2023 16:20:01] "POST / HTTP/1.1" 200 -
 version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=993672.4896432, self.flagDict['side']='sell', self.tradeCount=2, self.count=29116
self.closeSec=1678263599, self.tradeDate='20230308', self.openTime='161500', self.closeTime='161959', self.symbol='BTCUSDT', self.open=21951.8, self.close=21959.6, self.high=21970.8, self.low=21948.6, self.vol=849.239, self.amt=18647071.583 
2023-03-08 16:20:01,765:INFO:amihud:main.py:172:handleKline:200676: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5951  20230308   155500    155959  ...         0.0        0.0       0
5952  20230308   160000    160459  ...         0.0        0.0       0
5953  20230308   160500    160959  ...         0.0        0.0       0
5954  20230308   161000    161459  ...         0.0        0.0       0
5955  20230308   161500    161959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-03-08 16:20:01,769:INFO:amihud:main.py:175:handleKline:200676: self.closeSec=1678263599, self.tradeDate='20230308', self.openTime='161500', self.closeTime='161959',self.symbol='BTCUSDT',self.open=21951.8, self.close=21959.6, self.high=21970.8, self.low=21948.6, self.vol=849.239, self.amt=18647071.583, ukdf['pct'].iloc[-1]=0.000355 , ukdf['amount'].iloc[-1]=18647071.583, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5955, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '60.176', 'enterprice': '16529.3', 'countrevence': '0', 'unrealprofit': '-326914.85404031984', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '21961.94514159', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1
127.0.0.1 - - [08/Mar/2023 16:25:01] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=993672.4896432, self.flagDict['side']='sell', self.tradeCount=2, self.count=29117
self.closeSec=1678263899, self.tradeDate='20230308', self.openTime='162000', self.closeTime='162459', self.symbol='BTCUSDT', self.open=21959.7, self.close=22001.4, self.high=22008.0, self.low=21955.6, self.vol=2342.707, self.amt=51513772.2687 
2023-03-08 16:25:01,555:INFO:amihud:main.py:172:handleKline:200676: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5952  20230308   160000    160459  ...         0.0        0.0       0
5953  20230308   160500    160959  ...         0.0        0.0       0
5954  20230308   161000    161459  ...         0.0        0.0       0
5955  20230308   161500    161959  ...         0.0        0.0       0
5956  20230308   162000    162459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-03-08 16:25:01,555:INFO:amihud:main.py:175:handleKline:200676: self.closeSec=1678263899, self.tradeDate='20230308', self.openTime='162000', self.closeTime='162459',self.symbol='BTCUSDT',self.open=21959.7, self.close=22001.4, self.high=22008.0, self.low=21955.6, self.vol=2342.707, self.amt=51513772.2687, ukdf['pct'].iloc[-1]=0.001903 , ukdf['amount'].iloc[-1]=51513772.2687, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5956, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '60.176', 'enterprice': '16529.3', 'countrevence': '0', 'unrealprofit': '-329300.25514066032', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '22001.58554807', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1


## /root/FIL/strategy/factorcheck/log.txt ----- -----


self.closeSec=1678263599, self.tradeDate='20230308', self.openTime='161500', self.closeTime='161959', self.symbol='BTCUSDT', self.open=21951.8, self.close=21959.6, self.high=21970.8, self.low=21948.6 
127.0.0.1 - - [08/Mar/2023 16:20:01] "POST / HTTP/1.1" 200 -
2023-03-08 16:20:01,618:INFO:factorcheck2:main.py:126:handleKline:185239: self.closeSec=1678263599, self.tradeDate='20230308', self.openTime='161500', self.closeTime='161959',self.symbol='BTCUSDT',self.open=21951.8, self.close=21959.6, self.high=21970.8, self.low=21948.6   
2023-03-08 16:20:01,724:INFO:factorcheck2:main.py:127:handleKline:185239: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1631  20230308   155500    155959  1678262399  ...  21951.3 -0.001364   1631    5
1632  20230308   160000    160459  1678262699  ...  21932.8 -0.000838   1632    0
1633  20230308   160500    160959  1678262999  ...  21936.0  0.001568   1633    1
1634  20230308   161000    161459  1678263299  ...  21949.6 -0.001201   1634    2
1635  20230308   161500    161959  1678263599  ...  21948.6  0.000355   1635    3

[5 rows x 11 columns]
2023-03-08 16:20:01,725:INFO:factorcheck2:main.py:128:handleKline:185239: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': False, 'isOpen': True, 'isClose': False, 'isTrig': True}
127.0.0.1 - - [08/Mar/2023 16:25:01] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.6836888034344257, self.count=29683 

self.closeSec=1678263899, self.tradeDate='20230308', self.openTime='162000', self.closeTime='162459', self.symbol='BTCUSDT', self.open=21959.7, self.close=22001.4, self.high=22008.0, self.low=21955.6 
2023-03-08 16:25:01,522:INFO:factorcheck2:main.py:126:handleKline:185239: self.closeSec=1678263899, self.tradeDate='20230308', self.openTime='162000', self.closeTime='162459',self.symbol='BTCUSDT',self.open=21959.7, self.close=22001.4, self.high=22008.0, self.low=21955.6   
2023-03-08 16:25:01,580:INFO:factorcheck2:main.py:127:handleKline:185239: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1632  20230308   160000    160459  1678262699  ...  21932.8 -0.000838   1632    0
1633  20230308   160500    160959  1678262999  ...  21936.0  0.001568   1633    1
1634  20230308   161000    161459  1678263299  ...  21949.6 -0.001201   1634    2
1635  20230308   161500    161959  1678263599  ...  21948.6  0.000355   1635    3
1636  20230308   162000    162459  1678263899  ...  21955.6  0.001903   1636    4

[5 rows x 11 columns]
2023-03-08 16:25:01,581:INFO:factorcheck2:main.py:128:handleKline:185239: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': False, 'isOpen': True, 'isClose': False, 'isTrig': True}


## /root/FIL/strategy/logic/log.txt ----- -----

2023-03-08 16:00:34,170:DEBUG:logic:main.py:463:getModel:885513: df_s.iloc[-5:,:] :
          date closeTime     open  ...    alpha58   alpha67   alpha72
5786  20230308    132959  22133.0  ...  44.583333  0.416642  0.611795
5787  20230308    135959  22030.5  ...  44.166667  0.395461  0.623582
5788  20230308    142959  21944.2  ...  44.166667  0.416892  0.628626
5789  20230308    145959  22005.3  ...  44.583333  0.420261  0.632376
5790  20230308    152959  22015.0  ...  44.583333  0.410723  0.639647

[5 rows x 33 columns]
0.5479704797047971
acc is : 0.5479704797047971
2023-03-08 16:00:34,326:INFO:logic:main.py:468:getModel:885513: df_pred.iloc[-5:,:] :
     pred    prob_0    prob_1  actual  ...       nav  sign   cost_        bm
537     1  0.447180  0.552820       0  ...  0.947140  -1.0 -0.0016  0.947562
538     1  0.452559  0.547441       1  ...  0.944507  -1.0  0.0000  0.950196
539     0  0.519834  0.480166       1  ...  0.944086  -1.0  0.0000  0.950619
540     0  0.502700  0.497300       0  ...  0.945742  -1.0  0.0000  0.948952
541     1  0.473525  0.526475       0  ...  0.946357  -1.0  0.0000  0.948335

[5 rows x 10 columns]
2023-03-08 16:00:34,361:INFO:logic:main.py:478:getModel:885513: df_panel.iloc[-5:,:] :
    pred    prob_0    prob_1  actual  ...       nav  sign   cost_        bm
45     1  0.447269  0.552731       0  ...  0.947140  -1.0 -0.0016  0.949559
46     1  0.452809  0.547191       1  ...  0.944507  -1.0  0.0000  0.949728
47     0  0.519291  0.480709       1  ...  0.936485  -1.0  0.0000  0.949926
48     0  0.502359  0.497641       0  ...  0.945742  -1.0  0.0000  0.947725
49     1  0.473525  0.526475       0  ...  0.946357  -1.0  0.0000  0.948335

[5 rows x 10 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '31.961', 'enterprice': '21930.8', 'countrevence': '0', 'unrealprofit': '-878.51963129655', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '21958.28723855', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}


## /root/FIL/strategy/modifiedmom/log.txt ----- -----

527  20230308   155000    155959  1678262399  21995.5  21962.2 -0.001514
2023-03-08 16:00:02,069:INFO:modifiedmom:main.py:146:handleKline:185213: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': True, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True}

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=14840 

self.closeSec=1678262999, self.tradeDate='20230308', self.openTime='160000', self.closeTime='160959', self.symbol='BTCUSDT', self.open='21962.2', self.close='21978.2'
2023-03-08 16:10:01,729:INFO:modifiedmom:main.py:144:handleKline:185213: self.closeSec=1678262999, self.tradeDate='20230308', self.openTime='160000', self.closeTime='160959',self.symbol='BTCUSDT',self.open='21962.2', self.close='21978.2'
127.0.0.1 - - [08/Mar/2023 16:10:01] "POST / HTTP/1.1" 200 -
2023-03-08 16:10:01,746:INFO:modifiedmom:main.py:145:handleKline:185213: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
524  20230308   152000    152959  1678260599  22003.7  21976.5 -0.001232
525  20230308   153000    153959  1678261199  21976.5  22015.2  0.001761
526  20230308   154000    154959  1678261799  22015.1  21995.5 -0.000895
527  20230308   155000    155959  1678262399  21995.5  21962.2 -0.001514
528  20230308   160000    160959  1678262999  21962.2  21978.2  0.000729
2023-03-08 16:10:01,746:INFO:modifiedmom:main.py:146:handleKline:185213: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': True, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True}
127.0.0.1 - - [08/Mar/2023 16:20:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=14841 

self.closeSec=1678263599, self.tradeDate='20230308', self.openTime='161000', self.closeTime='161959', self.symbol='BTCUSDT', self.open='21978.2', self.close='21959.6'
2023-03-08 16:20:01,953:INFO:modifiedmom:main.py:144:handleKline:185213: self.closeSec=1678263599, self.tradeDate='20230308', self.openTime='161000', self.closeTime='161959',self.symbol='BTCUSDT',self.open='21978.2', self.close='21959.6'
2023-03-08 16:20:02,119:INFO:modifiedmom:main.py:145:handleKline:185213: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
525  20230308   153000    153959  1678261199  21976.5  22015.2  0.001761
526  20230308   154000    154959  1678261799  22015.1  21995.5 -0.000895
527  20230308   155000    155959  1678262399  21995.5  21962.2 -0.001514
528  20230308   160000    160959  1678262999  21962.2  21978.2  0.000729
529  20230308   161000    161959  1678263599  21978.2  21959.6 -0.000846
2023-03-08 16:20:02,119:INFO:modifiedmom:main.py:146:handleKline:185213: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': True, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True}


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

17519  20230308   155000    155959  1678262399  21995.5  21962.2
2023-03-08 16:00:02,126:INFO:pyemd2:main.py:127:handleKline:185189: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}
127.0.0.1 - - [08/Mar/2023 16:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=14841 

self.closeSec=1678262999, self.tradeDate='20230308', self.openTime='160000', self.closeTime='160959', self.symbol='BTCUSDT', self.open='21962.2', self.close='21978.2'
2023-03-08 16:10:01,764:INFO:pyemd2:main.py:125:handleKline:185189: self.closeSec=1678262999, self.tradeDate='20230308', self.openTime='160000', self.closeTime='160959',self.symbol='BTCUSDT',self.open='21962.2', self.close='21978.2'
2023-03-08 16:10:01,806:INFO:pyemd2:main.py:126:handleKline:185189: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17516  20230308   152000    152959  1678260599  22003.7  21976.5
17517  20230308   153000    153959  1678261199  21976.5  22015.2
17518  20230308   154000    154959  1678261799  22015.1  21995.5
17519  20230308   155000    155959  1678262399  21995.5  21962.2
17520  20230308   160000    160959  1678262999  21962.2  21978.2
2023-03-08 16:10:01,806:INFO:pyemd2:main.py:127:handleKline:185189: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=14842 

self.closeSec=1678263599, self.tradeDate='20230308', self.openTime='161000', self.closeTime='161959', self.symbol='BTCUSDT', self.open='21978.2', self.close='21959.6'
127.0.0.1 - - [08/Mar/2023 16:20:01] "POST / HTTP/1.1" 200 -
2023-03-08 16:20:02,145:INFO:pyemd2:main.py:125:handleKline:185189: self.closeSec=1678263599, self.tradeDate='20230308', self.openTime='161000', self.closeTime='161959',self.symbol='BTCUSDT',self.open='21978.2', self.close='21959.6'
2023-03-08 16:20:02,173:INFO:pyemd2:main.py:126:handleKline:185189: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17517  20230308   153000    153959  1678261199  21976.5  22015.2
17518  20230308   154000    154959  1678261799  22015.1  21995.5
17519  20230308   155000    155959  1678262399  21995.5  21962.2
17520  20230308   160000    160959  1678262999  21962.2  21978.2
17521  20230308   161000    161959  1678263599  21978.2  21959.6
2023-03-08 16:20:02,173:INFO:pyemd2:main.py:127:handleKline:185189: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}


## /root/FIL/strategy/similarity/log.txt ----- -----

12191  20230308   155000    155959  1678262399  21995.5  21962.2
2023-03-08 16:00:02,032:INFO:testStrategy:main.py:103:handleKline:185174: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}
127.0.0.1 - - [08/Mar/2023 16:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=14841 

self.closeSec=1678262999, self.tradeDate='20230308', self.openTime='160000', self.closeTime='160959', self.symbol='BTCUSDT', self.open='21962.2', self.close='21978.2'
2023-03-08 16:10:01,759:INFO:testStrategy:main.py:101:handleKline:185174: self.closeSec=1678262999, self.tradeDate='20230308', self.openTime='160000', self.closeTime='160959',self.symbol='BTCUSDT',self.open='21962.2', self.close='21978.2'
2023-03-08 16:10:01,803:INFO:testStrategy:main.py:102:handleKline:185174: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12188  20230308   152000    152959  1678260599  22003.7  21976.5
12189  20230308   153000    153959  1678261199  21976.5  22015.2
12190  20230308   154000    154959  1678261799  22015.1  21995.5
12191  20230308   155000    155959  1678262399  21995.5  21962.2
12192  20230308   160000    160959  1678262999  21962.2  21978.2
2023-03-08 16:10:01,803:INFO:testStrategy:main.py:103:handleKline:185174: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=14842 

self.closeSec=1678263599, self.tradeDate='20230308', self.openTime='161000', self.closeTime='161959', self.symbol='BTCUSDT', self.open='21978.2', self.close='21959.6'
127.0.0.1 - - [08/Mar/2023 16:20:01] "POST / HTTP/1.1" 200 -
2023-03-08 16:20:02,107:INFO:testStrategy:main.py:101:handleKline:185174: self.closeSec=1678263599, self.tradeDate='20230308', self.openTime='161000', self.closeTime='161959',self.symbol='BTCUSDT',self.open='21978.2', self.close='21959.6'
2023-03-08 16:20:02,141:INFO:testStrategy:main.py:102:handleKline:185174: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12189  20230308   153000    153959  1678261199  21976.5  22015.2
12190  20230308   154000    154959  1678261799  22015.1  21995.5
12191  20230308   155000    155959  1678262399  21995.5  21962.2
12192  20230308   160000    160959  1678262999  21962.2  21978.2
12193  20230308   161000    161959  1678263599  21978.2  21959.6
2023-03-08 16:20:02,141:INFO:testStrategy:main.py:103:handleKline:185174: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}


## /root/FIL/strategy/sr_min/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=0, self.total=1000000.0, self.flagDict['side']='', self.tradeCount=0, self.count=25114
self.closeSec=1678263599, self.tradeDate='20230308', self.openTime='161500', self.closeTime='161959', self.symbol='BTCUSDT', self.open=21951.8, self.close=21959.6, self.high=21970.8, self.low=21948.6, self.vol=849.239, self.amt=18647071.583 
127.0.0.1 - - [08/Mar/2023 16:20:01] "POST / HTTP/1.1" 200 -
2023-03-08 16:20:01,562:INFO:sr_min:main.py:172:handleKline:449472: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5951  20230308   155500    155959  ...         0.0        0.0       0
5952  20230308   160000    160459  ...         0.0        0.0       0
5953  20230308   160500    160959  ...         0.0        0.0       0
5954  20230308   161000    161459  ...         0.0        0.0       0
5955  20230308   161500    161959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-03-08 16:20:01,563:INFO:sr_min:main.py:175:handleKline:449472: self.closeSec=1678263599, self.tradeDate='20230308', self.openTime='161500', self.closeTime='161959',self.symbol='BTCUSDT',self.open=21951.8, self.close=21959.6, self.high=21970.8, self.low=21948.6, self.vol=849.239, self.amt=18647071.583, ukdf['pct'].iloc[-1]=0.000355 , ukdf['amount'].iloc[-1]=18647071.583, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5955, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': []}
type(curSign)=<class 'int'>, curSign=0, self.sign=0
127.0.0.1 - - [08/Mar/2023 16:25:01] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=0, self.total=1000000.0, self.flagDict['side']='', self.tradeCount=0, self.count=25115
self.closeSec=1678263899, self.tradeDate='20230308', self.openTime='162000', self.closeTime='162459', self.symbol='BTCUSDT', self.open=21959.7, self.close=22001.4, self.high=22008.0, self.low=21955.6, self.vol=2342.707, self.amt=51513772.2687 
2023-03-08 16:25:01,618:INFO:sr_min:main.py:172:handleKline:449472: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5952  20230308   160000    160459  ...         0.0        0.0       0
5953  20230308   160500    160959  ...         0.0        0.0       0
5954  20230308   161000    161459  ...         0.0        0.0       0
5955  20230308   161500    161959  ...         0.0        0.0       0
5956  20230308   162000    162459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-03-08 16:25:01,619:INFO:sr_min:main.py:175:handleKline:449472: self.closeSec=1678263899, self.tradeDate='20230308', self.openTime='162000', self.closeTime='162459',self.symbol='BTCUSDT',self.open=21959.7, self.close=22001.4, self.high=22008.0, self.low=21955.6, self.vol=2342.707, self.amt=51513772.2687, ukdf['pct'].iloc[-1]=0.001903 , ukdf['amount'].iloc[-1]=51513772.2687, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5956, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': []}
type(curSign)=<class 'int'>, curSign=0, self.sign=0


## /root/FIL/strategy/s_rsrs/log.txt ----- -----

721  20230308   040000    075959  1678233599  ...    721  0.012961 -1.878141    -1.0
722  20230308   080000    115959  1678247999  ...    722  0.019556 -1.809312    -1.0

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '42.135', 'enterprice': '23350.3', 'countrevence': '0', 'unrealprofit': '50870.9577965004', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '22142.96743096', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-1, self.sign=-1
--handleKline--:  version='2.0.0', self.name='s_rsrs', self.symbol='BTCUSDT', interval='4h', intervalSec=14400, wid=25, thd=0.6, self.sign=-1, self.total=982881.0256095, self.flagDict['side']='sell', self.tradeCount=23, self.count=618
self.closeSec=1678262399, self.tradeDate='20230308', self.openTime='120000', self.closeTime='155959', self.symbol='BTCUSDT', self.open=22141.8, self.close=21962.2, self.high=22155.5, self.low=21800.0, self.vol=89535.701, self.amt=1968240137.6959 
127.0.0.1 - - [08/Mar/2023 16:00:01] "POST / HTTP/1.1" 200 -
2023-03-08 16:00:01,924:INFO:s_rsrs:main.py:141:handleKline:185271: self.closeSec=1678262399, self.tradeDate='20230308', self.openTime='120000', self.closeTime='155959',self.symbol='BTCUSDT',self.open=22141.8, self.close=21962.2, self.high=22155.5, self.low=21800.0, self.vol=89535.701, self.amt=1968240137.6959 
2023-03-08 16:00:01,977:INFO:s_rsrs:main.py:142:handleKline:185271: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime  ...         vol           amt       pct
719  20230307   200000    235959  ...  241400.179  5.364881e+09 -0.001446
720  20230308   000000    035959  ...  111943.438  2.490485e+09 -0.008419
721  20230308   040000    075959  ...   95482.633  2.106800e+09  0.003047
722  20230308   080000    115959  ...   51149.471  1.134599e+09 -0.002042
723  20230308   120000    155959  ...   89535.701  1.968240e+09 -0.008111

[5 rows x 11 columns]
2023-03-08 16:00:04,464:INFO:s_rsrs:main.py:151:handleKline:185271: df_s.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec  ...  index      beta    zscore  signal
719  20230307   200000    235959  1678204799  ...    719  0.000088 -1.989372    -1.0
720  20230308   000000    035959  1678219199  ...    720  0.000843 -1.949908    -1.0
721  20230308   040000    075959  1678233599  ...    721  0.012961 -1.878141    -1.0
722  20230308   080000    115959  1678247999  ...    722  0.019556 -1.809312    -1.0
723  20230308   120000    155959  1678262399  ...    723  0.067822 -1.613690    -1.0

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '42.135', 'enterprice': '23350.3', 'countrevence': '0', 'unrealprofit': '58518.62956164375', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '21961.46341375', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-1, self.sign=-1


