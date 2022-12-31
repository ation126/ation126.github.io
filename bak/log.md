# 20221231 16:16:01

## /root/FIL/strategy/amihud/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=993672.4896432, self.flagDict['side']='sell', self.tradeCount=2, self.count=9818
self.closeSec=1672474199, self.tradeDate='20221231', self.openTime='160500', self.closeTime='160959', self.symbol='BTCUSDT', self.open=16560.1, self.close=16557.9, self.high=16560.2, self.low=16557.9, self.vol=286.48, self.amt=4744057.9233 
127.0.0.1 - - [31/Dec/2022 16:10:01] "POST / HTTP/1.1" 200 -
2022-12-31 16:10:01,687:INFO:amihud:main.py:172:handleKline:200676: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5949  20221231   154500    154959  ...         0.0        0.0       0
5950  20221231   155000    155459  ...         0.0        0.0       0
5951  20221231   155500    155959  ...         0.0        0.0       0
5952  20221231   160000    160459  ...         0.0        0.0       0
5953  20221231   160500    160959  ...         0.0        0.0       0

[5 rows x 18 columns]
2022-12-31 16:10:01,688:INFO:amihud:main.py:175:handleKline:200676: self.closeSec=1672474199, self.tradeDate='20221231', self.openTime='160500', self.closeTime='160959',self.symbol='BTCUSDT',self.open=16560.1, self.close=16557.9, self.high=16560.2, self.low=16557.9, self.vol=286.48, self.amt=4744057.9233, ukdf['pct'].iloc[-1]=-0.000139 , ukdf['amount'].iloc[-1]=4744057.9233, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5953, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '60.176', 'enterprice': '16529.3', 'countrevence': '0', 'unrealprofit': '-1807.53908346352', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '16559.33754127', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1
--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=993672.4896432, self.flagDict['side']='sell', self.tradeCount=2, self.count=9819
self.closeSec=1672474499, self.tradeDate='20221231', self.openTime='161000', self.closeTime='161459', self.symbol='BTCUSDT', self.open=16557.9, self.close=16558.4, self.high=16560.7, self.low=16557.8, self.vol=223.929, self.amt=3707996.7297 
127.0.0.1 - - [31/Dec/2022 16:15:00] "POST / HTTP/1.1" 200 -
2022-12-31 16:15:00,601:INFO:amihud:main.py:172:handleKline:200676: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5950  20221231   155000    155459  ...         0.0        0.0       0
5951  20221231   155500    155959  ...         0.0        0.0       0
5952  20221231   160000    160459  ...         0.0        0.0       0
5953  20221231   160500    160959  ...         0.0        0.0       0
5954  20221231   161000    161459  ...         0.0        0.0       0

[5 rows x 18 columns]
2022-12-31 16:15:00,601:INFO:amihud:main.py:175:handleKline:200676: self.closeSec=1672474499, self.tradeDate='20221231', self.openTime='161000', self.closeTime='161459',self.symbol='BTCUSDT',self.open=16557.9, self.close=16558.4, self.high=16560.7, self.low=16557.8, self.vol=223.929, self.amt=3707996.7297, ukdf['pct'].iloc[-1]=3e-05 , ukdf['amount'].iloc[-1]=3707996.7297, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5954, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '60.176', 'enterprice': '16529.3', 'countrevence': '0', 'unrealprofit': '-1751.1216', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '16558.4', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1


## /root/FIL/strategy/factorcheck/log.txt ----- -----

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=35, self.factor=0.369752110354161, self.count=10384 

self.closeSec=1672474199, self.tradeDate='20221231', self.openTime='160500', self.closeTime='160959', self.symbol='BTCUSDT', self.open=16560.1, self.close=16557.9, self.high=16560.2, self.low=16557.9 
2022-12-31 16:10:01,740:INFO:factorcheck2:main.py:126:handleKline:185239: self.closeSec=1672474199, self.tradeDate='20221231', self.openTime='160500', self.closeTime='160959',self.symbol='BTCUSDT',self.open=16560.1, self.close=16557.9, self.high=16560.2, self.low=16557.9   
2022-12-31 16:10:01,766:INFO:factorcheck2:main.py:127:handleKline:185239: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1629  20221231   154500    154959  1672472999  ...  16552.5 -0.000254   1629    3
1630  20221231   155000    155459  1672473299  ...  16553.6  0.000501   1630    4
1631  20221231   155500    155959  1672473599  ...  16561.9  0.000145   1631    5
1632  20221231   160000    160459  1672473899  ...  16560.1 -0.000254   1632    0
1633  20221231   160500    160959  1672474199  ...  16557.9 -0.000139   1633    1

[5 rows x 11 columns]
2022-12-31 16:10:01,766:INFO:factorcheck2:main.py:128:handleKline:185239: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}
127.0.0.1 - - [31/Dec/2022 16:15:00] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=35, self.factor=0.369752110354161, self.count=10385 

self.closeSec=1672474499, self.tradeDate='20221231', self.openTime='161000', self.closeTime='161459', self.symbol='BTCUSDT', self.open=16557.9, self.close=16558.4, self.high=16560.7, self.low=16557.8 
2022-12-31 16:15:00,534:INFO:factorcheck2:main.py:126:handleKline:185239: self.closeSec=1672474499, self.tradeDate='20221231', self.openTime='161000', self.closeTime='161459',self.symbol='BTCUSDT',self.open=16557.9, self.close=16558.4, self.high=16560.7, self.low=16557.8   
2022-12-31 16:15:00,583:INFO:factorcheck2:main.py:127:handleKline:185239: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1630  20221231   155000    155459  1672473299  ...  16553.6  0.000501   1630    4
1631  20221231   155500    155959  1672473599  ...  16561.9  0.000145   1631    5
1632  20221231   160000    160459  1672473899  ...  16560.1 -0.000254   1632    0
1633  20221231   160500    160959  1672474199  ...  16557.9 -0.000139   1633    1
1634  20221231   161000    161459  1672474499  ...  16557.8  0.000030   1634    2

[5 rows x 11 columns]
2022-12-31 16:15:00,583:INFO:factorcheck2:main.py:128:handleKline:185239: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}


## /root/FIL/strategy/logic/log.txt ----- -----

2022-12-31 16:00:19,851:DEBUG:logic:main.py:454:getModel:174970: df_s.iloc[-5:,:] :
          date closeTime     open  ...    alpha58   alpha67   alpha72
5786  20221231    132959  16545.9  ...  44.166667  0.481794  0.343685
5787  20221231    135959  16541.7  ...  44.166667  0.478328  0.345873
5788  20221231    142959  16536.1  ...  44.166667  0.484744  0.346089
5789  20221231    145959  16545.5  ...  44.166667  0.482323  0.347021
5790  20221231    152959  16541.8  ...  44.166667  0.484122  0.347391

[5 rows x 33 columns]
0.5313653136531366
acc is : 0.5313653136531366
2022-12-31 16:00:19,970:INFO:logic:main.py:459:getModel:174970: df_pred.iloc[-5:,:] :
     pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
537     1  0.495557  0.504443       0  ...  0.987837   1.0    0.0  1.004941
538     1  0.496505  0.503495       1  ...  0.988405   1.0    0.0  1.005518
539     0  0.501185  0.498815       0  ...  0.988178   1.0    0.0  1.005287
540     1  0.498265  0.501735       1  ...  0.988333   1.0    0.0  1.005445
541     1  0.499725  0.500275       1  ...  0.989528   1.0    0.0  1.006661

[5 rows x 10 columns]
2022-12-31 16:00:19,989:INFO:logic:main.py:469:getModel:174970: df_panel.iloc[-5:,:] :
    pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
45     1  0.496765  0.503235       0  ...  0.987837   1.0    0.0  1.007844
46     1  0.497453  0.502547       1  ...  0.988405   1.0    0.0  1.008134
47     0  0.501886  0.498114       0  ...  0.988178   1.0    0.0  1.006774
48     1  0.498541  0.501459       1  ...  0.988333   1.0    0.0  1.006161
49     1  0.499725  0.500275       1  ...  0.989528   1.0    0.0  1.006661

[5 rows x 10 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '42.528', 'enterprice': '16701.5', 'countrevence': '0', 'unrealprofit': '-5819.58188038176', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '16564.65881583', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}


## /root/FIL/strategy/modifiedmom/log.txt ----- -----

526  20221231   154000    154959  1672472999  16554.2  16553.6 -0.000036
2022-12-31 15:50:00,572:INFO:modifiedmom:main.py:146:handleKline:185213: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': True, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True}
127.0.0.1 - - [31/Dec/2022 16:00:00] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=5191 

self.closeSec=1672473599, self.tradeDate='20221231', self.openTime='155000', self.closeTime='155959', self.symbol='BTCUSDT', self.open='16553.7', self.close='16564.4'
2022-12-31 16:00:00,865:INFO:modifiedmom:main.py:144:handleKline:185213: self.closeSec=1672473599, self.tradeDate='20221231', self.openTime='155000', self.closeTime='155959',self.symbol='BTCUSDT',self.open='16553.7', self.close='16564.4'
2022-12-31 16:00:00,932:INFO:modifiedmom:main.py:145:handleKline:185213: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
523  20221231   151000    151959  1672471199  16547.3  16543.2 -0.000242
524  20221231   152000    152959  1672471799  16543.2  16544.4  0.000073
525  20221231   153000    153959  1672472399  16544.4  16554.2  0.000592
526  20221231   154000    154959  1672472999  16554.2  16553.6 -0.000036
527  20221231   155000    155959  1672473599  16553.7  16564.4  0.000652
2022-12-31 16:00:00,933:INFO:modifiedmom:main.py:146:handleKline:185213: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': True, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True}
127.0.0.1 - - [31/Dec/2022 16:10:02] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=5192 

self.closeSec=1672474199, self.tradeDate='20221231', self.openTime='160000', self.closeTime='160959', self.symbol='BTCUSDT', self.open='16564.4', self.close='16557.9'
2022-12-31 16:10:02,059:INFO:modifiedmom:main.py:144:handleKline:185213: self.closeSec=1672474199, self.tradeDate='20221231', self.openTime='160000', self.closeTime='160959',self.symbol='BTCUSDT',self.open='16564.4', self.close='16557.9'
2022-12-31 16:10:02,089:INFO:modifiedmom:main.py:145:handleKline:185213: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
524  20221231   152000    152959  1672471799  16543.2  16544.4  0.000073
525  20221231   153000    153959  1672472399  16544.4  16554.2  0.000592
526  20221231   154000    154959  1672472999  16554.2  16553.6 -0.000036
527  20221231   155000    155959  1672473599  16553.7  16564.4  0.000652
528  20221231   160000    160959  1672474199  16564.4  16557.9 -0.000392
2022-12-31 16:10:02,089:INFO:modifiedmom:main.py:146:handleKline:185213: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': True, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True}


## /root/FIL/strategy/pyemd/log.txt ----- -----

17518  20221231   154000    154959  1672472999  16554.2  16553.6
2022-12-31 15:50:00,632:INFO:pyemd2:main.py:127:handleKline:185189: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}
127.0.0.1 - - [31/Dec/2022 16:00:00] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=5192 

self.closeSec=1672473599, self.tradeDate='20221231', self.openTime='155000', self.closeTime='155959', self.symbol='BTCUSDT', self.open='16553.7', self.close='16564.4'
2022-12-31 16:00:00,893:INFO:pyemd2:main.py:125:handleKline:185189: self.closeSec=1672473599, self.tradeDate='20221231', self.openTime='155000', self.closeTime='155959',self.symbol='BTCUSDT',self.open='16553.7', self.close='16564.4'
2022-12-31 16:00:00,956:INFO:pyemd2:main.py:126:handleKline:185189: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17515  20221231   151000    151959  1672471199  16547.3  16543.2
17516  20221231   152000    152959  1672471799  16543.2  16544.4
17517  20221231   153000    153959  1672472399  16544.4  16554.2
17518  20221231   154000    154959  1672472999  16554.2  16553.6
17519  20221231   155000    155959  1672473599  16553.7  16564.4
2022-12-31 16:00:00,956:INFO:pyemd2:main.py:127:handleKline:185189: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=5193 

self.closeSec=1672474199, self.tradeDate='20221231', self.openTime='160000', self.closeTime='160959', self.symbol='BTCUSDT', self.open='16564.4', self.close='16557.9'
127.0.0.1 - - [31/Dec/2022 16:10:02] "POST / HTTP/1.1" 200 -
2022-12-31 16:10:02,096:INFO:pyemd2:main.py:125:handleKline:185189: self.closeSec=1672474199, self.tradeDate='20221231', self.openTime='160000', self.closeTime='160959',self.symbol='BTCUSDT',self.open='16564.4', self.close='16557.9'
2022-12-31 16:10:02,110:INFO:pyemd2:main.py:126:handleKline:185189: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17516  20221231   152000    152959  1672471799  16543.2  16544.4
17517  20221231   153000    153959  1672472399  16544.4  16554.2
17518  20221231   154000    154959  1672472999  16554.2  16553.6
17519  20221231   155000    155959  1672473599  16553.7  16564.4
17520  20221231   160000    160959  1672474199  16564.4  16557.9
2022-12-31 16:10:02,110:INFO:pyemd2:main.py:127:handleKline:185189: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}


## /root/FIL/strategy/similarity/log.txt ----- -----

12190  20221231   154000    154959  1672472999  16554.2  16553.6
2022-12-31 15:50:00,628:INFO:testStrategy:main.py:103:handleKline:185174: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}
127.0.0.1 - - [31/Dec/2022 16:00:00] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=5192 

self.closeSec=1672473599, self.tradeDate='20221231', self.openTime='155000', self.closeTime='155959', self.symbol='BTCUSDT', self.open='16553.7', self.close='16564.4'
2022-12-31 16:00:00,880:INFO:testStrategy:main.py:101:handleKline:185174: self.closeSec=1672473599, self.tradeDate='20221231', self.openTime='155000', self.closeTime='155959',self.symbol='BTCUSDT',self.open='16553.7', self.close='16564.4'
2022-12-31 16:00:00,943:INFO:testStrategy:main.py:102:handleKline:185174: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12187  20221231   151000    151959  1672471199  16547.3  16543.2
12188  20221231   152000    152959  1672471799  16543.2  16544.4
12189  20221231   153000    153959  1672472399  16544.4  16554.2
12190  20221231   154000    154959  1672472999  16554.2  16553.6
12191  20221231   155000    155959  1672473599  16553.7  16564.4
2022-12-31 16:00:00,944:INFO:testStrategy:main.py:103:handleKline:185174: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}
127.0.0.1 - - [31/Dec/2022 16:10:02] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=5193 

self.closeSec=1672474199, self.tradeDate='20221231', self.openTime='160000', self.closeTime='160959', self.symbol='BTCUSDT', self.open='16564.4', self.close='16557.9'
2022-12-31 16:10:02,079:INFO:testStrategy:main.py:101:handleKline:185174: self.closeSec=1672474199, self.tradeDate='20221231', self.openTime='160000', self.closeTime='160959',self.symbol='BTCUSDT',self.open='16564.4', self.close='16557.9'
2022-12-31 16:10:02,105:INFO:testStrategy:main.py:102:handleKline:185174: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12188  20221231   152000    152959  1672471799  16543.2  16544.4
12189  20221231   153000    153959  1672472399  16544.4  16554.2
12190  20221231   154000    154959  1672472999  16554.2  16553.6
12191  20221231   155000    155959  1672473599  16553.7  16564.4
12192  20221231   160000    160959  1672474199  16564.4  16557.9
2022-12-31 16:10:02,106:INFO:testStrategy:main.py:103:handleKline:185174: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}


## /root/FIL/strategy/sr_min/log.txt ----- -----

127.0.0.1 - - [31/Dec/2022 16:10:01] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=0, self.total=1000000.0, self.flagDict['side']='', self.tradeCount=0, self.count=5816
self.closeSec=1672474199, self.tradeDate='20221231', self.openTime='160500', self.closeTime='160959', self.symbol='BTCUSDT', self.open=16560.1, self.close=16557.9, self.high=16560.2, self.low=16557.9, self.vol=286.48, self.amt=4744057.9233 
2022-12-31 16:10:01,777:INFO:sr_min:main.py:172:handleKline:449472: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5949  20221231   154500    154959  ...         0.0        0.0       0
5950  20221231   155000    155459  ...         0.0        0.0       0
5951  20221231   155500    155959  ...         0.0        0.0       0
5952  20221231   160000    160459  ...         0.0        0.0       0
5953  20221231   160500    160959  ...         0.0        0.0       0

[5 rows x 18 columns]
2022-12-31 16:10:01,778:INFO:sr_min:main.py:175:handleKline:449472: self.closeSec=1672474199, self.tradeDate='20221231', self.openTime='160500', self.closeTime='160959',self.symbol='BTCUSDT',self.open=16560.1, self.close=16557.9, self.high=16560.2, self.low=16557.9, self.vol=286.48, self.amt=4744057.9233, ukdf['pct'].iloc[-1]=-0.000139 , ukdf['amount'].iloc[-1]=4744057.9233, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5953, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': []}
type(curSign)=<class 'int'>, curSign=0, self.sign=0
--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=0, self.total=1000000.0, self.flagDict['side']='', self.tradeCount=0, self.count=5817
self.closeSec=1672474499, self.tradeDate='20221231', self.openTime='161000', self.closeTime='161459', self.symbol='BTCUSDT', self.open=16557.9, self.close=16558.4, self.high=16560.7, self.low=16557.8, self.vol=223.929, self.amt=3707996.7297 
127.0.0.1 - - [31/Dec/2022 16:15:00] "POST / HTTP/1.1" 200 -
2022-12-31 16:15:00,602:INFO:sr_min:main.py:172:handleKline:449472: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5950  20221231   155000    155459  ...         0.0        0.0       0
5951  20221231   155500    155959  ...         0.0        0.0       0
5952  20221231   160000    160459  ...         0.0        0.0       0
5953  20221231   160500    160959  ...         0.0        0.0       0
5954  20221231   161000    161459  ...         0.0        0.0       0

[5 rows x 18 columns]
2022-12-31 16:15:00,603:INFO:sr_min:main.py:175:handleKline:449472: self.closeSec=1672474499, self.tradeDate='20221231', self.openTime='161000', self.closeTime='161459',self.symbol='BTCUSDT',self.open=16557.9, self.close=16558.4, self.high=16560.7, self.low=16557.8, self.vol=223.929, self.amt=3707996.7297, ukdf['pct'].iloc[-1]=3e-05 , ukdf['amount'].iloc[-1]=3707996.7297, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5954, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': []}
type(curSign)=<class 'int'>, curSign=0, self.sign=0


## /root/FIL/strategy/s_rsrs/log.txt ----- -----

721  20221231   040000    075959  1672444799  ...    721  0.543605  0.502980     NaN
722  20221231   080000    115959  1672459199  ...    722  0.484071  0.366170     NaN

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '53.898', 'enterprice': '16630.1', 'countrevence': '0', 'unrealprofit': '-4365.738', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '16549.1', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-9223372036854775808, self.sign=1
--handleKline--:  version='2.0.0', self.name='s_rsrs', self.symbol='BTCUSDT', interval='4h', intervalSec=14400, wid=25, thd=0.6, self.sign=1, self.total=895432.8006702, self.flagDict['side']='buy', self.tradeCount=8, self.count=216
self.closeSec=1672473599, self.tradeDate='20221231', self.openTime='120000', self.closeTime='155959', self.symbol='BTCUSDT', self.open=16549.0, self.close=16564.4, self.high=16565.6, self.low=16530.0, self.vol=15302.151, self.amt=253209097.4184 
127.0.0.1 - - [31/Dec/2022 16:00:00] "POST / HTTP/1.1" 200 -
2022-12-31 16:00:00,746:INFO:s_rsrs:main.py:141:handleKline:185271: self.closeSec=1672473599, self.tradeDate='20221231', self.openTime='120000', self.closeTime='155959',self.symbol='BTCUSDT',self.open=16549.0, self.close=16564.4, self.high=16565.6, self.low=16530.0, self.vol=15302.151, self.amt=253209097.4184 
2022-12-31 16:00:00,779:INFO:s_rsrs:main.py:142:handleKline:185271: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime  ...         vol           amt       pct
719  20221230   200000    235959  ...  104487.149  1.719910e+09  0.003530
720  20221231   000000    035959  ...   34830.474  5.759541e+08 -0.001626
721  20221231   040000    075959  ...   34781.545  5.770932e+08  0.004861
722  20221231   080000    115959  ...   15952.362  2.643333e+08 -0.003132
723  20221231   120000    155959  ...   15302.151  2.532091e+08  0.000925

[5 rows x 11 columns]
2022-12-31 16:00:02,425:INFO:s_rsrs:main.py:151:handleKline:185271: df_s.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec  ...  index      beta    zscore  signal
719  20221230   200000    235959  1672415999  ...    719  0.537523  0.446099     NaN
720  20221231   000000    035959  1672430399  ...    720  0.547593  0.492465     NaN
721  20221231   040000    075959  1672444799  ...    721  0.543605  0.502980     NaN
722  20221231   080000    115959  1672459199  ...    722  0.484071  0.366170     NaN
723  20221231   120000    155959  1672473599  ...    723  0.374744  0.093364     NaN

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '53.898', 'enterprice': '16630.1', 'countrevence': '0', 'unrealprofit': '-3541.0986', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '16564.4', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-9223372036854775808, self.sign=1


