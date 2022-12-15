# 20221215 16:16:01

## /root/FIL/strategy/amihud/log.txt ----- -----

127.0.0.1 - - [15/Dec/2022 16:10:01] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=993672.4896432, self.flagDict['side']='sell', self.tradeCount=2, self.count=5210
self.closeSec=1671091799, self.tradeDate='20221215', self.openTime='160500', self.closeTime='160959', self.symbol='BTCUSDT', self.open=17694.4, self.close=17698.5, self.high=17702.9, self.low=17691.6, self.vol=603.615, self.amt=10682966.352 
2022-12-15 16:10:01,462:INFO:amihud:main.py:172:handleKline:200676: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5949  20221215   154500    154959  ...         0.0        0.0       0
5950  20221215   155000    155459  ...         0.0        0.0       0
5951  20221215   155500    155959  ...         0.0        0.0       0
5952  20221215   160000    160459  ...         0.0        0.0       0
5953  20221215   160500    160959  ...         0.0        0.0       0

[5 rows x 18 columns]
2022-12-15 16:10:01,462:INFO:amihud:main.py:175:handleKline:200676: self.closeSec=1671091799, self.tradeDate='20221215', self.openTime='160500', self.closeTime='160959',self.symbol='BTCUSDT',self.open=17694.4, self.close=17698.5, self.high=17702.9, self.low=17691.6, self.vol=603.615, self.amt=10682966.352, ukdf['pct'].iloc[-1]=0.000232 , ukdf['amount'].iloc[-1]=10682966.352, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5953, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '60.176', 'enterprice': '16529.3', 'countrevence': '0', 'unrealprofit': '-70357.7792', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '17698.5', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1
--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=993672.4896432, self.flagDict['side']='sell', self.tradeCount=2, self.count=5211
self.closeSec=1671092099, self.tradeDate='20221215', self.openTime='161000', self.closeTime='161459', self.symbol='BTCUSDT', self.open=17698.5, self.close=17670.0, self.high=17705.9, self.low=17661.8, self.vol=1764.892, self.amt=31208458.9385 
127.0.0.1 - - [15/Dec/2022 16:15:00] "POST / HTTP/1.1" 200 -
2022-12-15 16:15:00,557:INFO:amihud:main.py:172:handleKline:200676: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5950  20221215   155000    155459  ...         0.0        0.0       0
5951  20221215   155500    155959  ...         0.0        0.0       0
5952  20221215   160000    160459  ...         0.0        0.0       0
5953  20221215   160500    160959  ...         0.0        0.0       0
5954  20221215   161000    161459  ...         0.0        0.0       0

[5 rows x 18 columns]
2022-12-15 16:15:00,558:INFO:amihud:main.py:175:handleKline:200676: self.closeSec=1671092099, self.tradeDate='20221215', self.openTime='161000', self.closeTime='161459',self.symbol='BTCUSDT',self.open=17698.5, self.close=17670.0, self.high=17705.9, self.low=17661.8, self.vol=1764.892, self.amt=31208458.9385, ukdf['pct'].iloc[-1]=-0.00161 , ukdf['amount'].iloc[-1]=31208458.9385, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5954, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '60.176', 'enterprice': '16529.3', 'countrevence': '0', 'unrealprofit': '-68822.80621874912', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '17672.99194062', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1


## /root/FIL/strategy/factorcheck/log.txt ----- -----


self.closeSec=1671091799, self.tradeDate='20221215', self.openTime='160500', self.closeTime='160959', self.symbol='BTCUSDT', self.open=17694.4, self.close=17698.5, self.high=17702.9, self.low=17691.6 
2022-12-15 16:10:01,424:INFO:factorcheck2:main.py:126:handleKline:185239: self.closeSec=1671091799, self.tradeDate='20221215', self.openTime='160500', self.closeTime='160959',self.symbol='BTCUSDT',self.open=17694.4, self.close=17698.5, self.high=17702.9, self.low=17691.6   
127.0.0.1 - - [15/Dec/2022 16:10:01] "POST / HTTP/1.1" 200 -
2022-12-15 16:10:01,437:INFO:factorcheck2:main.py:127:handleKline:185239: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1629  20221215   154500    154959  1671090599  ...  17724.9  0.000175   1629    3
1630  20221215   155000    155459  1671090899  ...  17697.1 -0.001653   1630    4
1631  20221215   155500    155959  1671091199  ...  17675.9 -0.000706   1631    5
1632  20221215   160000    160459  1671091499  ...  17685.9  0.000475   1632    0
1633  20221215   160500    160959  1671091799  ...  17691.6  0.000232   1633    1

[5 rows x 11 columns]
2022-12-15 16:10:01,437:INFO:factorcheck2:main.py:128:handleKline:185239: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}
127.0.0.1 - - [15/Dec/2022 16:15:00] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=70, self.factor=0.5319210551772867, self.count=5777 

self.closeSec=1671092099, self.tradeDate='20221215', self.openTime='161000', self.closeTime='161459', self.symbol='BTCUSDT', self.open=17698.5, self.close=17670.0, self.high=17705.9, self.low=17661.8 
2022-12-15 16:15:00,547:INFO:factorcheck2:main.py:126:handleKline:185239: self.closeSec=1671092099, self.tradeDate='20221215', self.openTime='161000', self.closeTime='161459',self.symbol='BTCUSDT',self.open=17698.5, self.close=17670.0, self.high=17705.9, self.low=17661.8   
2022-12-15 16:15:00,564:INFO:factorcheck2:main.py:127:handleKline:185239: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1630  20221215   155000    155459  1671090899  ...  17697.1 -0.001653   1630    4
1631  20221215   155500    155959  1671091199  ...  17675.9 -0.000706   1631    5
1632  20221215   160000    160459  1671091499  ...  17685.9  0.000475   1632    0
1633  20221215   160500    160959  1671091799  ...  17691.6  0.000232   1633    1
1634  20221215   161000    161459  1671092099  ...  17661.8 -0.001610   1634    2

[5 rows x 11 columns]
2022-12-15 16:15:00,564:INFO:factorcheck2:main.py:128:handleKline:185239: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}


## /root/FIL/strategy/logic/log.txt ----- -----

2022-12-15 16:00:18,355:DEBUG:logic:main.py:454:getModel:174970: df_s.iloc[-5:,:] :
          date closeTime     open  ...    alpha58   alpha67   alpha72
5786  20221215    132959  17707.9  ...  50.416667  0.506155  0.680771
5787  20221215    135959  17713.0  ...  50.833333  0.506303  0.689879
5788  20221215    142959  17713.4  ...  50.833333  0.509538  0.697522
5789  20221215    145959  17724.1  ...  50.833333  0.506683  0.705377
5790  20221215    152959  17715.0  ...  50.833333  0.509518  0.711979

[5 rows x 33 columns]
0.6070110701107011
acc is : 0.6070110701107011
2022-12-15 16:00:18,465:INFO:logic:main.py:459:getModel:174970: df_pred.iloc[-5:,:] :
     pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
537     1  0.496468  0.503532       1  ...  1.030801  -1.0    0.0  1.045631
538     1  0.494765  0.505235       1  ...  1.030172  -1.0    0.0  1.046268
539     1  0.496814  0.503186       0  ...  1.030701  -1.0    0.0  1.045731
540     1  0.494195  0.505805       1  ...  1.030166  -1.0    0.0  1.046274
541     1  0.497222  0.502778       0  ...  1.032398  -1.0    0.0  1.044007

[5 rows x 10 columns]
2022-12-15 16:00:18,489:INFO:logic:main.py:469:getModel:174970: df_panel.iloc[-5:,:] :
    pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
45     1  0.496605  0.503395       1  ...  1.030801  -1.0    0.0  1.048465
46     1  0.495161  0.504839       1  ...  1.030172  -1.0    0.0  1.049471
47     1  0.497325  0.502675       0  ...  1.030701  -1.0    0.0  1.049597
48     1  0.494446  0.505554       1  ...  1.030166  -1.0    0.0  1.046880
49     1  0.497222  0.502778       0  ...  1.032398  -1.0    0.0  1.044007

[5 rows x 10 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '37.704', 'enterprice': '17770', 'countrevence': '0', 'unrealprofit': '3046.4832', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '17689.2', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}


## /root/FIL/strategy/modifiedmom/log.txt ----- -----

526  20221215   154000    154959  1671090599  17723.8  17727.8  0.000231
2022-12-15 15:50:00,609:INFO:modifiedmom:main.py:146:handleKline:185213: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True}

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=2887 

self.closeSec=1671091199, self.tradeDate='20221215', self.openTime='155000', self.closeTime='155959', self.symbol='BTCUSDT', self.open='17727.8', self.close='17686'
2022-12-15 16:00:01,392:INFO:modifiedmom:main.py:144:handleKline:185213: self.closeSec=1671091199, self.tradeDate='20221215', self.openTime='155000', self.closeTime='155959',self.symbol='BTCUSDT',self.open='17727.8', self.close='17686'
127.0.0.1 - - [15/Dec/2022 16:00:01] "POST / HTTP/1.1" 200 -
2022-12-15 16:00:01,439:INFO:modifiedmom:main.py:145:handleKline:185213: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
523  20221215   151000    151959  1671088799  17719.2  17711.3 -0.000446
524  20221215   152000    152959  1671089399  17711.3    17725  0.000774
525  20221215   153000    153959  1671089999  17724.9  17723.7 -0.000073
526  20221215   154000    154959  1671090599  17723.8  17727.8  0.000231
527  20221215   155000    155959  1671091199  17727.8    17686 -0.002358
2022-12-15 16:00:01,440:INFO:modifiedmom:main.py:146:handleKline:185213: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True}
127.0.0.1 - - [15/Dec/2022 16:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=2888 

self.closeSec=1671091799, self.tradeDate='20221215', self.openTime='160000', self.closeTime='160959', self.symbol='BTCUSDT', self.open='17685.9', self.close='17698.5'
2022-12-15 16:10:01,505:INFO:modifiedmom:main.py:144:handleKline:185213: self.closeSec=1671091799, self.tradeDate='20221215', self.openTime='160000', self.closeTime='160959',self.symbol='BTCUSDT',self.open='17685.9', self.close='17698.5'
2022-12-15 16:10:01,515:INFO:modifiedmom:main.py:145:handleKline:185213: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
524  20221215   152000    152959  1671089399  17711.3    17725  0.000774
525  20221215   153000    153959  1671089999  17724.9  17723.7 -0.000073
526  20221215   154000    154959  1671090599  17723.8  17727.8  0.000231
527  20221215   155000    155959  1671091199  17727.8    17686 -0.002358
528  20221215   160000    160959  1671091799  17685.9  17698.5  0.000707
2022-12-15 16:10:01,516:INFO:modifiedmom:main.py:146:handleKline:185213: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True}


## /root/FIL/strategy/pyemd/log.txt ----- -----

17518  20221215   154000    154959  1671090599  17723.8  17727.8
2022-12-15 15:50:00,609:INFO:pyemd2:main.py:127:handleKline:185189: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=2888 

self.closeSec=1671091199, self.tradeDate='20221215', self.openTime='155000', self.closeTime='155959', self.symbol='BTCUSDT', self.open='17727.8', self.close='17686'
127.0.0.1 - - [15/Dec/2022 16:00:01] "POST / HTTP/1.1" 200 -
2022-12-15 16:00:01,414:INFO:pyemd2:main.py:125:handleKline:185189: self.closeSec=1671091199, self.tradeDate='20221215', self.openTime='155000', self.closeTime='155959',self.symbol='BTCUSDT',self.open='17727.8', self.close='17686'
2022-12-15 16:00:01,448:INFO:pyemd2:main.py:126:handleKline:185189: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17515  20221215   151000    151959  1671088799  17719.2  17711.3
17516  20221215   152000    152959  1671089399  17711.3    17725
17517  20221215   153000    153959  1671089999  17724.9  17723.7
17518  20221215   154000    154959  1671090599  17723.8  17727.8
17519  20221215   155000    155959  1671091199  17727.8    17686
2022-12-15 16:00:01,448:INFO:pyemd2:main.py:127:handleKline:185189: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}
127.0.0.1 - - [15/Dec/2022 16:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=2889 

self.closeSec=1671091799, self.tradeDate='20221215', self.openTime='160000', self.closeTime='160959', self.symbol='BTCUSDT', self.open='17685.9', self.close='17698.5'
2022-12-15 16:10:01,527:INFO:pyemd2:main.py:125:handleKline:185189: self.closeSec=1671091799, self.tradeDate='20221215', self.openTime='160000', self.closeTime='160959',self.symbol='BTCUSDT',self.open='17685.9', self.close='17698.5'
2022-12-15 16:10:01,543:INFO:pyemd2:main.py:126:handleKline:185189: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17516  20221215   152000    152959  1671089399  17711.3    17725
17517  20221215   153000    153959  1671089999  17724.9  17723.7
17518  20221215   154000    154959  1671090599  17723.8  17727.8
17519  20221215   155000    155959  1671091199  17727.8    17686
17520  20221215   160000    160959  1671091799  17685.9  17698.5
2022-12-15 16:10:01,543:INFO:pyemd2:main.py:127:handleKline:185189: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}


## /root/FIL/strategy/similarity/log.txt ----- -----

12190  20221215   154000    154959  1671090599  17723.8  17727.8
2022-12-15 15:50:00,623:INFO:testStrategy:main.py:103:handleKline:185174: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=2888 

self.closeSec=1671091199, self.tradeDate='20221215', self.openTime='155000', self.closeTime='155959', self.symbol='BTCUSDT', self.open='17727.8', self.close='17686'
127.0.0.1 - - [15/Dec/2022 16:00:01] "POST / HTTP/1.1" 200 -
2022-12-15 16:00:01,372:INFO:testStrategy:main.py:101:handleKline:185174: self.closeSec=1671091199, self.tradeDate='20221215', self.openTime='155000', self.closeTime='155959',self.symbol='BTCUSDT',self.open='17727.8', self.close='17686'
2022-12-15 16:00:01,432:INFO:testStrategy:main.py:102:handleKline:185174: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12187  20221215   151000    151959  1671088799  17719.2  17711.3
12188  20221215   152000    152959  1671089399  17711.3    17725
12189  20221215   153000    153959  1671089999  17724.9  17723.7
12190  20221215   154000    154959  1671090599  17723.8  17727.8
12191  20221215   155000    155959  1671091199  17727.8    17686
2022-12-15 16:00:01,435:INFO:testStrategy:main.py:103:handleKline:185174: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}

--handleKline--: 127.0.0.1 - - [15/Dec/2022 16:10:01] "POST / HTTP/1.1" 200 -
 self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=2889 

self.closeSec=1671091799, self.tradeDate='20221215', self.openTime='160000', self.closeTime='160959', self.symbol='BTCUSDT', self.open='17685.9', self.close='17698.5'
2022-12-15 16:10:01,501:INFO:testStrategy:main.py:101:handleKline:185174: self.closeSec=1671091799, self.tradeDate='20221215', self.openTime='160000', self.closeTime='160959',self.symbol='BTCUSDT',self.open='17685.9', self.close='17698.5'
2022-12-15 16:10:01,533:INFO:testStrategy:main.py:102:handleKline:185174: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12188  20221215   152000    152959  1671089399  17711.3    17725
12189  20221215   153000    153959  1671089999  17724.9  17723.7
12190  20221215   154000    154959  1671090599  17723.8  17727.8
12191  20221215   155000    155959  1671091199  17727.8    17686
12192  20221215   160000    160959  1671091799  17685.9  17698.5
2022-12-15 16:10:01,533:INFO:testStrategy:main.py:103:handleKline:185174: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}


## /root/FIL/strategy/sr_min/log.txt ----- -----

127.0.0.1 - - [15/Dec/2022 16:10:01] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=0, self.total=1000000.0, self.flagDict['side']='', self.tradeCount=0, self.count=1208
self.closeSec=1671091799, self.tradeDate='20221215', self.openTime='160500', self.closeTime='160959', self.symbol='BTCUSDT', self.open=17694.4, self.close=17698.5, self.high=17702.9, self.low=17691.6, self.vol=603.615, self.amt=10682966.352 
2022-12-15 16:10:01,477:INFO:sr_min:main.py:172:handleKline:449472: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5949  20221215   154500    154959  ...    0.273312   0.311819       0
5950  20221215   155000    155459  ...    0.273063   0.311846       0
5951  20221215   155500    155959  ...    0.272814   0.311873       0
5952  20221215   160000    160459  ...    0.272567   0.311901       0
5953  20221215   160500    160959  ...    0.272320   0.311929       0

[5 rows x 18 columns]
2022-12-15 16:10:01,477:INFO:sr_min:main.py:175:handleKline:449472: self.closeSec=1671091799, self.tradeDate='20221215', self.openTime='160500', self.closeTime='160959',self.symbol='BTCUSDT',self.open=17694.4, self.close=17698.5, self.high=17702.9, self.low=17691.6, self.vol=603.615, self.amt=10682966.352, ukdf['pct'].iloc[-1]=0.000232 , ukdf['amount'].iloc[-1]=10682966.352, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5953, value=0.0, value_mean=0.2723198792572053, signal=0, value_std=0.3119291836415168 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': []}
type(curSign)=<class 'int'>, curSign=0, self.sign=0
127.0.0.1 - - [15/Dec/2022 16:15:00] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=0, self.total=1000000.0, self.flagDict['side']='', self.tradeCount=0, self.count=1209
self.closeSec=1671092099, self.tradeDate='20221215', self.openTime='161000', self.closeTime='161459', self.symbol='BTCUSDT', self.open=17698.5, self.close=17670.0, self.high=17705.9, self.low=17661.8, self.vol=1764.892, self.amt=31208458.9385 
2022-12-15 16:15:00,569:INFO:sr_min:main.py:172:handleKline:449472: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5950  20221215   155000    155459  ...    0.273063   0.311846       0
5951  20221215   155500    155959  ...    0.272814   0.311873       0
5952  20221215   160000    160459  ...    0.272567   0.311901       0
5953  20221215   160500    160959  ...    0.272320   0.311929       0
5954  20221215   161000    161459  ...    0.272074   0.311958       0

[5 rows x 18 columns]
2022-12-15 16:15:00,582:INFO:sr_min:main.py:175:handleKline:449472: self.closeSec=1671092099, self.tradeDate='20221215', self.openTime='161000', self.closeTime='161459',self.symbol='BTCUSDT',self.open=17698.5, self.close=17670.0, self.high=17705.9, self.low=17661.8, self.vol=1764.892, self.amt=31208458.9385, ukdf['pct'].iloc[-1]=-0.00161 , ukdf['amount'].iloc[-1]=31208458.9385, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5954, value=0.0, value_mean=0.2720742588799527, signal=0, value_std=0.311957845727561 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': []}
type(curSign)=<class 'int'>, curSign=0, self.sign=0


## /root/FIL/strategy/s_rsrs/log.txt ----- -----

721  20221215   040000    075959  1671062399  ...    721  1.168074  1.773576     1.0
722  20221215   080000    115959  1671076799  ...    722  1.174786  1.746192     1.0

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '53.436', 'enterprice': '17756.3', 'countrevence': '0', 'unrealprofit': '-1610.02053379128', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '17726.17011502', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=1, self.sign=1
127.0.0.1 - - [15/Dec/2022 16:00:01] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='s_rsrs', self.symbol='BTCUSDT', interval='4h', intervalSec=14400, wid=25, thd=0.6, self.sign=1, self.total=947876.8211532, self.flagDict['side']='buy', self.tradeCount=6, self.count=120
self.closeSec=1671091199, self.tradeDate='20221215', self.openTime='120000', self.closeTime='155959', self.symbol='BTCUSDT', self.open=17724.9, self.close=17686.0, self.high=17744.3, self.low=17675.9, self.vol=27803.765, self.amt=492476321.9003 
2022-12-15 16:00:01,051:INFO:s_rsrs:main.py:141:handleKline:185271: self.closeSec=1671091199, self.tradeDate='20221215', self.openTime='120000', self.closeTime='155959',self.symbol='BTCUSDT',self.open=17724.9, self.close=17686.0, self.high=17744.3, self.low=17675.9, self.vol=27803.765, self.amt=492476321.9003 
2022-12-15 16:00:01,090:INFO:s_rsrs:main.py:142:handleKline:185271: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime  ...         vol           amt       pct
719  20221214   200000    235959  ...  137064.540  2.462616e+09  0.012898
720  20221215   000000    035959  ...  301024.945  5.433787e+09 -0.014634
721  20221215   040000    075959  ...   98675.813  1.756578e+09  0.000809
722  20221215   080000    115959  ...   74507.679  1.318699e+09 -0.004437
723  20221215   120000    155959  ...   27803.765  4.924763e+08 -0.002195

[5 rows x 11 columns]
2022-12-15 16:00:02,640:INFO:s_rsrs:main.py:151:handleKline:185271: df_s.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec  ...  index      beta    zscore  signal
719  20221214   200000    235959  1671033599  ...    719  1.005027  1.339233     1.0
720  20221215   000000    035959  1671047999  ...    720  1.150479  1.769464     1.0
721  20221215   040000    075959  1671062399  ...    721  1.168074  1.773576     1.0
722  20221215   080000    115959  1671076799  ...    722  1.174786  1.746192     1.0
723  20221215   120000    155959  1671091199  ...    723  1.103680  1.479993     1.0

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '53.436', 'enterprice': '17756.3', 'countrevence': '0', 'unrealprofit': '-3682.32127443492', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '17687.38912953', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=1, self.sign=1


