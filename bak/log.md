# 20230409 16:26:02

## /root/FIL/strategy/amihud/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=993672.4896432, self.flagDict['side']='sell', self.tradeCount=2, self.count=38332
self.closeSec=1681028399, self.tradeDate='20230409', self.openTime='161500', self.closeTime='161959', self.symbol='BTCUSDT', self.open=27896.7, self.close=27912.3, self.high=27912.4, self.low=27895.0, self.vol=662.31, self.amt=18481843.5757 
127.0.0.1 - - [09/Apr/2023 16:20:04] "POST / HTTP/1.1" 200 -
2023-04-09 16:20:09,638:INFO:amihud:main.py:172:handleKline:200676: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5951  20230409   155500    155959  ...         0.0        0.0       0
5952  20230409   160000    160459  ...         0.0        0.0       0
5953  20230409   160500    160959  ...         0.0        0.0       0
5954  20230409   161000    161459  ...         0.0        0.0       0
5955  20230409   161500    161959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-04-09 16:20:09,669:INFO:amihud:main.py:175:handleKline:200676: self.closeSec=1681028399, self.tradeDate='20230409', self.openTime='161500', self.closeTime='161959',self.symbol='BTCUSDT',self.open=27896.7, self.close=27912.3, self.high=27912.4, self.low=27895.0, self.vol=662.31, self.amt=18481843.5757, ukdf['pct'].iloc[-1]=0.000559 , ukdf['amount'].iloc[-1]=18481843.5757, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5955, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '60.176', 'enterprice': '16529.3', 'countrevence': '0', 'unrealprofit': '-684875.0912', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '27910.5', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1
--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=993672.4896432, self.flagDict['side']='sell', self.tradeCount=2, self.count=38333
self.closeSec=1681028699, self.tradeDate='20230409', self.openTime='162000', self.closeTime='162459', self.symbol='BTCUSDT', self.open=27912.3, self.close=27890.0, self.high=27912.4, self.low=27890.0, self.vol=487.983, self.amt=13612509.3567 
127.0.0.1 - - [09/Apr/2023 16:25:01] "POST / HTTP/1.1" 200 -
2023-04-09 16:25:01,581:INFO:amihud:main.py:172:handleKline:200676: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5952  20230409   160000    160459  ...         0.0        0.0       0
5953  20230409   160500    160959  ...         0.0        0.0       0
5954  20230409   161000    161459  ...         0.0        0.0       0
5955  20230409   161500    161959  ...         0.0        0.0       0
5956  20230409   162000    162459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-04-09 16:25:01,582:INFO:amihud:main.py:175:handleKline:200676: self.closeSec=1681028699, self.tradeDate='20230409', self.openTime='162000', self.closeTime='162459',self.symbol='BTCUSDT',self.open=27912.3, self.close=27890.0, self.high=27912.4, self.low=27890.0, self.vol=487.983, self.amt=13612509.3567, ukdf['pct'].iloc[-1]=-0.000799 , ukdf['amount'].iloc[-1]=13612509.3567, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5956, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '60.176', 'enterprice': '16529.3', 'countrevence': '0', 'unrealprofit': '-683641.4832', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '27890', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1


## /root/FIL/strategy/factorcheck/log.txt ----- -----


self.closeSec=1681028399, self.tradeDate='20230409', self.openTime='161500', self.closeTime='161959', self.symbol='BTCUSDT', self.open=27896.7, self.close=27912.3, self.high=27912.4, self.low=27895.0 
127.0.0.1 - - [09/Apr/2023 16:20:03] "POST / HTTP/1.1" 200 -
2023-04-09 16:20:07,169:INFO:factorcheck2:main.py:126:handleKline:185239: self.closeSec=1681028399, self.tradeDate='20230409', self.openTime='161500', self.closeTime='161959',self.symbol='BTCUSDT',self.open=27896.7, self.close=27912.3, self.high=27912.4, self.low=27895.0   
2023-04-09 16:20:08,479:INFO:factorcheck2:main.py:127:handleKline:185239: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1631  20230409   155500    155959  1681027199  ...  27882.4 -0.000161   1631    5
1632  20230409   160000    160459  1681027499  ...  27883.8  0.000158   1632    0
1633  20230409   160500    160959  1681027799  ...  27883.6 -0.000118   1633    1
1634  20230409   161000    161459  1681028099  ...  27881.0  0.000265   1634    2
1635  20230409   161500    161959  1681028399  ...  27895.0  0.000559   1635    3

[5 rows x 11 columns]
2023-04-09 16:20:08,480:INFO:factorcheck2:main.py:128:handleKline:185239: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}
127.0.0.1 - - [09/Apr/2023 16:25:01] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=72, self.factor=0.5227532650979445, self.count=38899 

self.closeSec=1681028699, self.tradeDate='20230409', self.openTime='162000', self.closeTime='162459', self.symbol='BTCUSDT', self.open=27912.3, self.close=27890.0, self.high=27912.4, self.low=27890.0 
2023-04-09 16:25:01,497:INFO:factorcheck2:main.py:126:handleKline:185239: self.closeSec=1681028699, self.tradeDate='20230409', self.openTime='162000', self.closeTime='162459',self.symbol='BTCUSDT',self.open=27912.3, self.close=27890.0, self.high=27912.4, self.low=27890.0   
2023-04-09 16:25:01,515:INFO:factorcheck2:main.py:127:handleKline:185239: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1632  20230409   160000    160459  1681027499  ...  27883.8  0.000158   1632    0
1633  20230409   160500    160959  1681027799  ...  27883.6 -0.000118   1633    1
1634  20230409   161000    161459  1681028099  ...  27881.0  0.000265   1634    2
1635  20230409   161500    161959  1681028399  ...  27895.0  0.000559   1635    3
1636  20230409   162000    162459  1681028699  ...  27890.0 -0.000799   1636    4

[5 rows x 11 columns]
2023-04-09 16:25:01,515:INFO:factorcheck2:main.py:128:handleKline:185239: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}


## /root/FIL/strategy/logic/log.txt ----- -----

2023-04-09 16:00:35,850:DEBUG:logic:main.py:463:getModel:885513: df_s.iloc[-5:,:] :
          date closeTime     open  ...    alpha58   alpha67   alpha72
5786  20230409    132959  28024.9  ...  47.500000  0.523781  0.468630
5787  20230409    135959  28049.9  ...  47.500000  0.501707  0.464371
5788  20230409    142959  27987.8  ...  47.083333  0.485632  0.474680
5789  20230409    145959  27939.9  ...  46.666667  0.462116  0.497923
5790  20230409    152959  27865.5  ...  47.083333  0.471246  0.512901

[5 rows x 33 columns]
0.5553505535055351
acc is : 0.5553505535055351
2023-04-09 16:00:36,017:INFO:logic:main.py:468:getModel:885513: df_pred.iloc[-5:,:] :
     pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
537     0  0.522204  0.477796       0  ...  0.939811   1.0    0.0  1.026793
538     1  0.499562  0.500438       0  ...  0.938206   1.0    0.0  1.025039
539     0  0.500557  0.499443       0  ...  0.935708   1.0    0.0  1.022309
540     1  0.489565  0.510435       1  ...  0.936581   1.0    0.0  1.023263
541     0  0.511603  0.488397       0  ...  0.936466   1.0    0.0  1.023139

[5 rows x 10 columns]
2023-04-09 16:00:36,056:INFO:logic:main.py:478:getModel:885513: df_panel.iloc[-5:,:] :
    pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
45     0  0.522568  0.477432       0  ...  0.939811   1.0    0.0  1.028623
46     1  0.499218  0.500782       0  ...  0.938206   1.0    0.0  1.024862
47     0  0.500640  0.499360       0  ...  0.935708   1.0    0.0  1.022602
48     1  0.489191  0.510809       1  ...  0.936581   1.0    0.0  1.021996
49     0  0.511603  0.488397       0  ...  0.936466   1.0    0.0  1.023139

[5 rows x 10 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': []}


## /root/FIL/strategy/modifiedmom/log.txt ----- -----

527  20230409   155000    155959  1681027199  27883.9  27888.2  0.000154
2023-04-09 16:00:02,012:INFO:modifiedmom:main.py:146:handleKline:185213: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': True, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True}
127.0.0.1 - - [09/Apr/2023 16:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=19448 

self.closeSec=1681027799, self.tradeDate='20230409', self.openTime='160000', self.closeTime='160959', self.symbol='BTCUSDT', self.open='27888.2', self.close='27889.3'
2023-04-09 16:10:01,620:INFO:modifiedmom:main.py:144:handleKline:185213: self.closeSec=1681027799, self.tradeDate='20230409', self.openTime='160000', self.closeTime='160959',self.symbol='BTCUSDT',self.open='27888.2', self.close='27889.3'
2023-04-09 16:10:01,660:INFO:modifiedmom:main.py:145:handleKline:185213: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
524  20230409   152000    152959  1681025399  27849.9  27891.6  0.001494
525  20230409   153000    153959  1681025999  27891.7  27856.9 -0.001244
526  20230409   154000    154959  1681026599  27856.8  27883.9  0.000969
527  20230409   155000    155959  1681027199  27883.9  27888.2  0.000154
528  20230409   160000    160959  1681027799  27888.2  27889.3  0.000039
2023-04-09 16:10:01,660:INFO:modifiedmom:main.py:146:handleKline:185213: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': True, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True}

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=19449 

self.closeSec=1681028399, self.tradeDate='20230409', self.openTime='161000', self.closeTime='161959', self.symbol='BTCUSDT', self.open='27889.4', self.close='27912.3'
127.0.0.1 - - [09/Apr/2023 16:20:05] "POST / HTTP/1.1" 200 -
2023-04-09 16:20:08,249:INFO:modifiedmom:main.py:144:handleKline:185213: self.closeSec=1681028399, self.tradeDate='20230409', self.openTime='161000', self.closeTime='161959',self.symbol='BTCUSDT',self.open='27889.4', self.close='27912.3'
2023-04-09 16:20:09,149:INFO:modifiedmom:main.py:145:handleKline:185213: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
525  20230409   153000    153959  1681025999  27891.7  27856.9 -0.001244
526  20230409   154000    154959  1681026599  27856.8  27883.9  0.000969
527  20230409   155000    155959  1681027199  27883.9  27888.2  0.000154
528  20230409   160000    160959  1681027799  27888.2  27889.3  0.000039
529  20230409   161000    161959  1681028399  27889.4  27912.3  0.000825
2023-04-09 16:20:09,149:INFO:modifiedmom:main.py:146:handleKline:185213: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': True, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True}


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

17519  20230409   155000    155959  1681027199  27883.9  27888.2
2023-04-09 16:00:02,024:INFO:pyemd2:main.py:127:handleKline:185189: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=19449 

self.closeSec=1681027799, self.tradeDate='20230409', self.openTime='160000', self.closeTime='160959', self.symbol='BTCUSDT', self.open='27888.2', self.close='27889.3'
2023-04-09 16:10:01,604:INFO:pyemd2:main.py:125:handleKline:185189: self.closeSec=1681027799, self.tradeDate='20230409', self.openTime='160000', self.closeTime='160959',self.symbol='BTCUSDT',self.open='27888.2', self.close='27889.3'
127.0.0.1 - - [09/Apr/2023 16:10:01] "POST / HTTP/1.1" 200 -
2023-04-09 16:10:01,627:INFO:pyemd2:main.py:126:handleKline:185189: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17516  20230409   152000    152959  1681025399  27849.9  27891.6
17517  20230409   153000    153959  1681025999  27891.7  27856.9
17518  20230409   154000    154959  1681026599  27856.8  27883.9
17519  20230409   155000    155959  1681027199  27883.9  27888.2
17520  20230409   160000    160959  1681027799  27888.2  27889.3
2023-04-09 16:10:01,627:INFO:pyemd2:main.py:127:handleKline:185189: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=19450 

self.closeSec=1681028399, self.tradeDate='20230409', self.openTime='161000', self.closeTime='161959', self.symbol='BTCUSDT', self.open='27889.4', self.close='27912.3'
127.0.0.1 - - [09/Apr/2023 16:20:05] "POST / HTTP/1.1" 200 -
2023-04-09 16:20:11,463:INFO:pyemd2:main.py:125:handleKline:185189: self.closeSec=1681028399, self.tradeDate='20230409', self.openTime='161000', self.closeTime='161959',self.symbol='BTCUSDT',self.open='27889.4', self.close='27912.3'
2023-04-09 16:20:11,614:INFO:pyemd2:main.py:126:handleKline:185189: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17517  20230409   153000    153959  1681025999  27891.7  27856.9
17518  20230409   154000    154959  1681026599  27856.8  27883.9
17519  20230409   155000    155959  1681027199  27883.9  27888.2
17520  20230409   160000    160959  1681027799  27888.2  27889.3
17521  20230409   161000    161959  1681028399  27889.4  27912.3
2023-04-09 16:20:11,615:INFO:pyemd2:main.py:127:handleKline:185189: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}


## /root/FIL/strategy/similarity/log.txt ----- -----

12191  20230409   155000    155959  1681027199  27883.9  27888.2
2023-04-09 16:00:02,039:INFO:testStrategy:main.py:103:handleKline:185174: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': True, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=19449 

self.closeSec=1681027799, self.tradeDate='20230409', self.openTime='160000', self.closeTime='160959', self.symbol='BTCUSDT', self.open='27888.2', self.close='27889.3'
2023-04-09 16:10:01,573:INFO:testStrategy:main.py:101:handleKline:185174: self.closeSec=1681027799, self.tradeDate='20230409', self.openTime='160000', self.closeTime='160959',self.symbol='BTCUSDT',self.open='27888.2', self.close='27889.3'
127.0.0.1 - - [09/Apr/2023 16:10:01] "POST / HTTP/1.1" 200 -
2023-04-09 16:10:01,588:INFO:testStrategy:main.py:102:handleKline:185174: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12188  20230409   152000    152959  1681025399  27849.9  27891.6
12189  20230409   153000    153959  1681025999  27891.7  27856.9
12190  20230409   154000    154959  1681026599  27856.8  27883.9
12191  20230409   155000    155959  1681027199  27883.9  27888.2
12192  20230409   160000    160959  1681027799  27888.2  27889.3
2023-04-09 16:10:01,588:INFO:testStrategy:main.py:103:handleKline:185174: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': True, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=19450 

self.closeSec=1681028399, self.tradeDate='20230409', self.openTime='161000', self.closeTime='161959', self.symbol='BTCUSDT', self.open='27889.4', self.close='27912.3'
127.0.0.1 - - [09/Apr/2023 16:20:05] "POST / HTTP/1.1" 200 -
2023-04-09 16:20:10,958:INFO:testStrategy:main.py:101:handleKline:185174: self.closeSec=1681028399, self.tradeDate='20230409', self.openTime='161000', self.closeTime='161959',self.symbol='BTCUSDT',self.open='27889.4', self.close='27912.3'
2023-04-09 16:20:11,267:INFO:testStrategy:main.py:102:handleKline:185174: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12189  20230409   153000    153959  1681025999  27891.7  27856.9
12190  20230409   154000    154959  1681026599  27856.8  27883.9
12191  20230409   155000    155959  1681027199  27883.9  27888.2
12192  20230409   160000    160959  1681027799  27888.2  27889.3
12193  20230409   161000    161959  1681028399  27889.4  27912.3
2023-04-09 16:20:11,268:INFO:testStrategy:main.py:103:handleKline:185174: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': True, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}


## /root/FIL/strategy/sr_min/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=0, self.total=1000000.0, self.flagDict['side']='', self.tradeCount=0, self.count=34330
self.closeSec=1681028399, self.tradeDate='20230409', self.openTime='161500', self.closeTime='161959', self.symbol='BTCUSDT', self.open=27896.7, self.close=27912.3, self.high=27912.4, self.low=27895.0, self.vol=662.31, self.amt=18481843.5757 
127.0.0.1 - - [09/Apr/2023 16:20:03] "POST / HTTP/1.1" 200 -
2023-04-09 16:20:08,959:INFO:sr_min:main.py:172:handleKline:449472: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5951  20230409   155500    155959  ...         0.0        0.0       0
5952  20230409   160000    160459  ...         0.0        0.0       0
5953  20230409   160500    160959  ...         0.0        0.0       0
5954  20230409   161000    161459  ...         0.0        0.0       0
5955  20230409   161500    161959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-04-09 16:20:08,989:INFO:sr_min:main.py:175:handleKline:449472: self.closeSec=1681028399, self.tradeDate='20230409', self.openTime='161500', self.closeTime='161959',self.symbol='BTCUSDT',self.open=27896.7, self.close=27912.3, self.high=27912.4, self.low=27895.0, self.vol=662.31, self.amt=18481843.5757, ukdf['pct'].iloc[-1]=0.000559 , ukdf['amount'].iloc[-1]=18481843.5757, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5955, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': []}
type(curSign)=<class 'int'>, curSign=0, self.sign=0
127.0.0.1 - - [09/Apr/2023 16:25:01] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=0, self.total=1000000.0, self.flagDict['side']='', self.tradeCount=0, self.count=34331
self.closeSec=1681028699, self.tradeDate='20230409', self.openTime='162000', self.closeTime='162459', self.symbol='BTCUSDT', self.open=27912.3, self.close=27890.0, self.high=27912.4, self.low=27890.0, self.vol=487.983, self.amt=13612509.3567 
2023-04-09 16:25:01,615:INFO:sr_min:main.py:172:handleKline:449472: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5952  20230409   160000    160459  ...         0.0        0.0       0
5953  20230409   160500    160959  ...         0.0        0.0       0
5954  20230409   161000    161459  ...         0.0        0.0       0
5955  20230409   161500    161959  ...         0.0        0.0       0
5956  20230409   162000    162459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-04-09 16:25:01,616:INFO:sr_min:main.py:175:handleKline:449472: self.closeSec=1681028699, self.tradeDate='20230409', self.openTime='162000', self.closeTime='162459',self.symbol='BTCUSDT',self.open=27912.3, self.close=27890.0, self.high=27912.4, self.low=27890.0, self.vol=487.983, self.amt=13612509.3567, ukdf['pct'].iloc[-1]=-0.000799 , ukdf['amount'].iloc[-1]=13612509.3567, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5956, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': []}
type(curSign)=<class 'int'>, curSign=0, self.sign=0


## /root/FIL/strategy/s_rsrs/log.txt ----- -----

721  20230409   040000    075959  1680998399  ...    721  0.273751  0.094085     NaN
722  20230409   080000    115959  1681012799  ...    722  0.269967  0.063218     NaN

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '52.088', 'enterprice': '28398.8', 'countrevence': '0', 'unrealprofit': '20033.0448', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '28014.2', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-9223372036854775808, self.sign=-1
127.0.0.1 - - [09/Apr/2023 16:00:01] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='s_rsrs', self.symbol='BTCUSDT', interval='4h', intervalSec=14400, wid=25, thd=0.6, self.sign=-1, self.total=1477757.4577056, self.flagDict['side']='sell', self.tradeCount=29, self.count=810
self.closeSec=1681027199, self.tradeDate='20230409', self.openTime='120000', self.closeTime='155959', self.symbol='BTCUSDT', self.open=28011.9, self.close=27888.2, self.high=28055.0, self.low=27820.0, self.vol=47649.419, self.amt=1330187233.9009 
2023-04-09 16:00:01,871:INFO:s_rsrs:main.py:141:handleKline:185271: self.closeSec=1681027199, self.tradeDate='20230409', self.openTime='120000', self.closeTime='155959',self.symbol='BTCUSDT',self.open=28011.9, self.close=27888.2, self.high=28055.0, self.low=27820.0, self.vol=47649.419, self.amt=1330187233.9009 
2023-04-09 16:00:01,946:INFO:s_rsrs:main.py:142:handleKline:185271: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime  ...        vol           amt       pct
719  20230408   200000    235959  ...  23432.442  6.559301e+08  0.000236
720  20230409   000000    035959  ...  29141.062  8.137164e+08 -0.003399
721  20230409   040000    075959  ...  19235.488  5.370948e+08  0.000566
722  20230409   080000    115959  ...  30081.552  8.429432e+08  0.003119
723  20230409   120000    155959  ...  47649.419  1.330187e+09 -0.004420

[5 rows x 11 columns]
2023-04-09 16:00:04,813:INFO:s_rsrs:main.py:151:handleKline:185271: df_s.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec  ...  index      beta    zscore  signal
719  20230408   200000    235959  1680969599  ...    719  0.255298  0.032437     NaN
720  20230409   000000    035959  1680983999  ...    720  0.268087  0.080000     NaN
721  20230409   040000    075959  1680998399  ...    721  0.273751  0.094085     NaN
722  20230409   080000    115959  1681012799  ...    722  0.269967  0.063218     NaN
723  20230409   120000    155959  1681027199  ...    723  0.209839 -0.237609     NaN

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '52.088', 'enterprice': '28398.8', 'countrevence': '0', 'unrealprofit': '26596.1328', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '27888.2', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-9223372036854775808, self.sign=-1


