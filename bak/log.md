# 20221226 16:16:01

## /root/FIL/strategy/amihud/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=993672.4896432, self.flagDict['side']='sell', self.tradeCount=2, self.count=8378
self.closeSec=1672042199, self.tradeDate='20221226', self.openTime='160500', self.closeTime='160959', self.symbol='BTCUSDT', self.open=16833.7, self.close=16830.8, self.high=16833.7, self.low=16830.8, self.vol=375.623, self.amt=6322540.474 
127.0.0.1 - - [26/Dec/2022 16:10:01] "POST / HTTP/1.1" 200 -
2022-12-26 16:10:01,581:INFO:amihud:main.py:172:handleKline:200676: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5949  20221226   154500    154959  ...         0.0        0.0       0
5950  20221226   155000    155459  ...         0.0        0.0       0
5951  20221226   155500    155959  ...         0.0        0.0       0
5952  20221226   160000    160459  ...         0.0        0.0       0
5953  20221226   160500    160959  ...         0.0        0.0       0

[5 rows x 18 columns]
2022-12-26 16:10:01,581:INFO:amihud:main.py:175:handleKline:200676: self.closeSec=1672042199, self.tradeDate='20221226', self.openTime='160500', self.closeTime='160959',self.symbol='BTCUSDT',self.open=16833.7, self.close=16830.8, self.high=16833.7, self.low=16830.8, self.vol=375.623, self.amt=6322540.474, ukdf['pct'].iloc[-1]=-0.000166 , ukdf['amount'].iloc[-1]=6322540.474, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5953, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '60.176', 'enterprice': '16529.3', 'countrevence': '0', 'unrealprofit': '-18165.57080547056', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '16831.17401631', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1
127.0.0.1 - - [26/Dec/2022 16:15:00] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=993672.4896432, self.flagDict['side']='sell', self.tradeCount=2, self.count=8379
self.closeSec=1672042499, self.tradeDate='20221226', self.openTime='161000', self.closeTime='161459', self.symbol='BTCUSDT', self.open=16830.9, self.close=16826.1, self.high=16830.9, self.low=16825.0, self.vol=797.57, self.amt=13421736.5768 
2022-12-26 16:15:00,641:INFO:amihud:main.py:172:handleKline:200676: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5950  20221226   155000    155459  ...         0.0        0.0       0
5951  20221226   155500    155959  ...         0.0        0.0       0
5952  20221226   160000    160459  ...         0.0        0.0       0
5953  20221226   160500    160959  ...         0.0        0.0       0
5954  20221226   161000    161459  ...         0.0        0.0       0

[5 rows x 18 columns]
2022-12-26 16:15:00,642:INFO:amihud:main.py:175:handleKline:200676: self.closeSec=1672042499, self.tradeDate='20221226', self.openTime='161000', self.closeTime='161459',self.symbol='BTCUSDT',self.open=16830.9, self.close=16826.1, self.high=16830.9, self.low=16825.0, self.vol=797.57, self.amt=13421736.5768, ukdf['pct'].iloc[-1]=-0.000279 , ukdf['amount'].iloc[-1]=13421736.5768, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5954, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '60.176', 'enterprice': '16529.3', 'countrevence': '0', 'unrealprofit': '-17863.5260983888', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '16826.1546613', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1


## /root/FIL/strategy/factorcheck/log.txt ----- -----

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=246, self.factor=0.40105581998302003, self.count=8944 

self.closeSec=1672042199, self.tradeDate='20221226', self.openTime='160500', self.closeTime='160959', self.symbol='BTCUSDT', self.open=16833.7, self.close=16830.8, self.high=16833.7, self.low=16830.8 
2022-12-26 16:10:01,420:INFO:factorcheck2:main.py:126:handleKline:185239: self.closeSec=1672042199, self.tradeDate='20221226', self.openTime='160500', self.closeTime='160959',self.symbol='BTCUSDT',self.open=16833.7, self.close=16830.8, self.high=16833.7, self.low=16830.8   
2022-12-26 16:10:01,466:INFO:factorcheck2:main.py:127:handleKline:185239: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1629  20221226   154500    154959  1672040999  ...  16834.5 -0.000119   1629    3
1630  20221226   155000    155459  1672041299  ...  16832.9 -0.000095   1630    4
1631  20221226   155500    155959  1672041599  ...  16834.1  0.000149   1631    5
1632  20221226   160000    160459  1672041899  ...  16833.5 -0.000178   1632    0
1633  20221226   160500    160959  1672042199  ...  16830.8 -0.000166   1633    1

[5 rows x 11 columns]
2022-12-26 16:10:01,466:INFO:factorcheck2:main.py:128:handleKline:185239: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=246, self.factor=0.40105581998302003, self.count=8945 

self.closeSec=1672042499, self.tradeDate='20221226', self.openTime='161000', self.closeTime='161459', self.symbol='BTCUSDT', self.open=16830.9, self.close=16826.1, self.high=16830.9, self.low=16825.0 
2022-12-26 16:15:00,538:INFO:factorcheck2:main.py:126:handleKline:185239: self.closeSec=1672042499, self.tradeDate='20221226', self.openTime='161000', self.closeTime='161459',self.symbol='BTCUSDT',self.open=16830.9, self.close=16826.1, self.high=16830.9, self.low=16825.0   
127.0.0.1 - - [26/Dec/2022 16:15:00] "POST / HTTP/1.1" 200 -
2022-12-26 16:15:00,620:INFO:factorcheck2:main.py:127:handleKline:185239: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1630  20221226   155000    155459  1672041299  ...  16832.9 -0.000095   1630    4
1631  20221226   155500    155959  1672041599  ...  16834.1  0.000149   1631    5
1632  20221226   160000    160459  1672041899  ...  16833.5 -0.000178   1632    0
1633  20221226   160500    160959  1672042199  ...  16830.8 -0.000166   1633    1
1634  20221226   161000    161459  1672042499  ...  16825.0 -0.000279   1634    2

[5 rows x 11 columns]
2022-12-26 16:15:00,620:INFO:factorcheck2:main.py:128:handleKline:185239: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}


## /root/FIL/strategy/logic/log.txt ----- -----

2022-12-26 16:00:18,512:DEBUG:logic:main.py:454:getModel:174970: df_s.iloc[-5:,:] :
          date closeTime     open  ...    alpha58   alpha67   alpha72
5786  20221226    132959  16869.6  ...  48.333333  0.531823  0.284966
5787  20221226    135959  16852.8  ...  47.916667  0.522667  0.289080
5788  20221226    142959  16843.6  ...  47.916667  0.534353  0.288977
5789  20221226    145959  16856.6  ...  47.916667  0.522113  0.292581
5790  20221226    152959  16844.5  ...  48.333333  0.523573  0.295460

[5 rows x 33 columns]
0.518450184501845
acc is : 0.518450184501845
2022-12-26 16:00:18,608:INFO:logic:main.py:459:getModel:174970: df_pred.iloc[-5:,:] :
     pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
537     1  0.490161  0.509839       0  ...  1.058431   1.0    0.0  0.946871
538     1  0.491204  0.508796       1  ...  1.059248   1.0    0.0  0.947602
539     1  0.495906  0.504094       0  ...  1.058481   1.0    0.0  0.946916
540     1  0.491867  0.508133       1  ...  1.058582   1.0    0.0  0.947006
541     1  0.494431  0.505569       0  ...  1.057991   1.0    0.0  0.946477

[5 rows x 10 columns]
2022-12-26 16:00:18,620:INFO:logic:main.py:469:getModel:174970: df_panel.iloc[-5:,:] :
    pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
45     1  0.490153  0.509847       0  ...  1.058431   1.0    0.0  0.944693
46     1  0.491398  0.508602       1  ...  1.059248   1.0    0.0  0.946830
47     1  0.495857  0.504143       0  ...  1.058481   1.0    0.0  0.946107
48     1  0.491665  0.508335       1  ...  1.058582   1.0    0.0  0.944087
49     1  0.494431  0.505569       0  ...  1.057991   1.0    0.0  0.946477

[5 rows x 10 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '42.528', 'enterprice': '16701.5', 'countrevence': '0', 'unrealprofit': '5745.5328', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '16836.6', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}


## /root/FIL/strategy/modifiedmom/log.txt ----- -----

526  20221226   154000    154959  1672040999  16840.1  16835.7 -0.000255
2022-12-26 15:50:00,583:INFO:modifiedmom:main.py:146:handleKline:185213: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True}

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=4471 

self.closeSec=1672041599, self.tradeDate='20221226', self.openTime='155000', self.closeTime='155959', self.symbol='BTCUSDT', self.open='16835.7', self.close='16836.6'
2022-12-26 16:00:01,210:INFO:modifiedmom:main.py:144:handleKline:185213: self.closeSec=1672041599, self.tradeDate='20221226', self.openTime='155000', self.closeTime='155959',self.symbol='BTCUSDT',self.open='16835.7', self.close='16836.6'
127.0.0.1 - - [26/Dec/2022 16:00:01] "POST / HTTP/1.1" 200 -
2022-12-26 16:00:01,262:INFO:modifiedmom:main.py:145:handleKline:185213: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
523  20221226   151000    151959  1672039199  16834.7  16846.6  0.000707
524  20221226   152000    152959  1672039799  16846.6    16846 -0.000036
525  20221226   153000    153959  1672040399    16846    16840 -0.000356
526  20221226   154000    154959  1672040999  16840.1  16835.7 -0.000255
527  20221226   155000    155959  1672041599  16835.7  16836.6  0.000053
2022-12-26 16:00:01,262:INFO:modifiedmom:main.py:146:handleKline:185213: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True}

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=4472 

self.closeSec=1672042199, self.tradeDate='20221226', self.openTime='160000', self.closeTime='160959', self.symbol='BTCUSDT', self.open='16836.7', self.close='16830.8'
2022-12-26 16:10:01,508:INFO:modifiedmom:main.py:144:handleKline:185213: self.closeSec=1672042199, self.tradeDate='20221226', self.openTime='160000', self.closeTime='160959',self.symbol='BTCUSDT',self.open='16836.7', self.close='16830.8'
127.0.0.1 - - [26/Dec/2022 16:10:01] "POST / HTTP/1.1" 200 -
2022-12-26 16:10:01,524:INFO:modifiedmom:main.py:145:handleKline:185213: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
524  20221226   152000    152959  1672039799  16846.6    16846 -0.000036
525  20221226   153000    153959  1672040399    16846    16840 -0.000356
526  20221226   154000    154959  1672040999  16840.1  16835.7 -0.000255
527  20221226   155000    155959  1672041599  16835.7  16836.6  0.000053
528  20221226   160000    160959  1672042199  16836.7  16830.8 -0.000344
2022-12-26 16:10:01,558:INFO:modifiedmom:main.py:146:handleKline:185213: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True}


## /root/FIL/strategy/pyemd/log.txt ----- -----

17518  20221226   154000    154959  1672040999  16840.1  16835.7
2022-12-26 15:50:00,574:INFO:pyemd2:main.py:127:handleKline:185189: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=4472 

self.closeSec=1672041599, self.tradeDate='20221226', self.openTime='155000', self.closeTime='155959', self.symbol='BTCUSDT', self.open='16835.7', self.close='16836.6'
127.0.0.1 - - [26/Dec/2022 16:00:01] "POST / HTTP/1.1" 200 -
2022-12-26 16:00:01,196:INFO:pyemd2:main.py:125:handleKline:185189: self.closeSec=1672041599, self.tradeDate='20221226', self.openTime='155000', self.closeTime='155959',self.symbol='BTCUSDT',self.open='16835.7', self.close='16836.6'
2022-12-26 16:00:01,227:INFO:pyemd2:main.py:126:handleKline:185189: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17515  20221226   151000    151959  1672039199  16834.7  16846.6
17516  20221226   152000    152959  1672039799  16846.6    16846
17517  20221226   153000    153959  1672040399    16846    16840
17518  20221226   154000    154959  1672040999  16840.1  16835.7
17519  20221226   155000    155959  1672041599  16835.7  16836.6
2022-12-26 16:00:01,227:INFO:pyemd2:main.py:127:handleKline:185189: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}
127.0.0.1 - - [26/Dec/2022 16:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=4473 

self.closeSec=1672042199, self.tradeDate='20221226', self.openTime='160000', self.closeTime='160959', self.symbol='BTCUSDT', self.open='16836.7', self.close='16830.8'
2022-12-26 16:10:01,569:INFO:pyemd2:main.py:125:handleKline:185189: self.closeSec=1672042199, self.tradeDate='20221226', self.openTime='160000', self.closeTime='160959',self.symbol='BTCUSDT',self.open='16836.7', self.close='16830.8'
2022-12-26 16:10:01,586:INFO:pyemd2:main.py:126:handleKline:185189: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17516  20221226   152000    152959  1672039799  16846.6    16846
17517  20221226   153000    153959  1672040399    16846    16840
17518  20221226   154000    154959  1672040999  16840.1  16835.7
17519  20221226   155000    155959  1672041599  16835.7  16836.6
17520  20221226   160000    160959  1672042199  16836.7  16830.8
2022-12-26 16:10:01,586:INFO:pyemd2:main.py:127:handleKline:185189: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}


## /root/FIL/strategy/similarity/log.txt ----- -----

12190  20221226   154000    154959  1672040999  16840.1  16835.7
2022-12-26 15:50:00,594:INFO:testStrategy:main.py:103:handleKline:185174: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': True, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}
127.0.0.1 - - [26/Dec/2022 16:00:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=4472 

self.closeSec=1672041599, self.tradeDate='20221226', self.openTime='155000', self.closeTime='155959', self.symbol='BTCUSDT', self.open='16835.7', self.close='16836.6'
2022-12-26 16:00:01,185:INFO:testStrategy:main.py:101:handleKline:185174: self.closeSec=1672041599, self.tradeDate='20221226', self.openTime='155000', self.closeTime='155959',self.symbol='BTCUSDT',self.open='16835.7', self.close='16836.6'
2022-12-26 16:00:01,285:INFO:testStrategy:main.py:102:handleKline:185174: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12187  20221226   151000    151959  1672039199  16834.7  16846.6
12188  20221226   152000    152959  1672039799  16846.6    16846
12189  20221226   153000    153959  1672040399    16846    16840
12190  20221226   154000    154959  1672040999  16840.1  16835.7
12191  20221226   155000    155959  1672041599  16835.7  16836.6
2022-12-26 16:00:01,285:INFO:testStrategy:main.py:103:handleKline:185174: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': True, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}
127.0.0.1 - - [26/Dec/2022 16:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=4473 

self.closeSec=1672042199, self.tradeDate='20221226', self.openTime='160000', self.closeTime='160959', self.symbol='BTCUSDT', self.open='16836.7', self.close='16830.8'
2022-12-26 16:10:01,541:INFO:testStrategy:main.py:101:handleKline:185174: self.closeSec=1672042199, self.tradeDate='20221226', self.openTime='160000', self.closeTime='160959',self.symbol='BTCUSDT',self.open='16836.7', self.close='16830.8'
2022-12-26 16:10:01,560:INFO:testStrategy:main.py:102:handleKline:185174: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12188  20221226   152000    152959  1672039799  16846.6    16846
12189  20221226   153000    153959  1672040399    16846    16840
12190  20221226   154000    154959  1672040999  16840.1  16835.7
12191  20221226   155000    155959  1672041599  16835.7  16836.6
12192  20221226   160000    160959  1672042199  16836.7  16830.8
2022-12-26 16:10:01,560:INFO:testStrategy:main.py:103:handleKline:185174: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': True, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}


## /root/FIL/strategy/sr_min/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=0, self.total=1000000.0, self.flagDict['side']='', self.tradeCount=0, self.count=4376
self.closeSec=1672042199, self.tradeDate='20221226', self.openTime='160500', self.closeTime='160959', self.symbol='BTCUSDT', self.open=16833.7, self.close=16830.8, self.high=16833.7, self.low=16830.8, self.vol=375.623, self.amt=6322540.474 
127.0.0.1 - - [26/Dec/2022 16:10:01] "POST / HTTP/1.1" 200 -
2022-12-26 16:10:01,580:INFO:sr_min:main.py:172:handleKline:449472: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5949  20221226   154500    154959  ...         0.0        0.0       0
5950  20221226   155000    155459  ...         0.0        0.0       0
5951  20221226   155500    155959  ...         0.0        0.0       0
5952  20221226   160000    160459  ...         0.0        0.0       0
5953  20221226   160500    160959  ...         0.0        0.0       0

[5 rows x 18 columns]
2022-12-26 16:10:01,580:INFO:sr_min:main.py:175:handleKline:449472: self.closeSec=1672042199, self.tradeDate='20221226', self.openTime='160500', self.closeTime='160959',self.symbol='BTCUSDT',self.open=16833.7, self.close=16830.8, self.high=16833.7, self.low=16830.8, self.vol=375.623, self.amt=6322540.474, ukdf['pct'].iloc[-1]=-0.000166 , ukdf['amount'].iloc[-1]=6322540.474, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5953, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': []}
type(curSign)=<class 'int'>, curSign=0, self.sign=0
--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=0, self.total=1000000.0, self.flagDict['side']='', self.tradeCount=0, self.count=4377
self.closeSec=1672042499, self.tradeDate='20221226', self.openTime='161000', self.closeTime='161459', self.symbol='BTCUSDT', self.open=16830.9, self.close=16826.1, self.high=16830.9, self.low=16825.0, self.vol=797.57, self.amt=13421736.5768 
127.0.0.1 - - [26/Dec/2022 16:15:00] "POST / HTTP/1.1" 200 -
2022-12-26 16:15:00,595:INFO:sr_min:main.py:172:handleKline:449472: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5950  20221226   155000    155459  ...         0.0        0.0       0
5951  20221226   155500    155959  ...         0.0        0.0       0
5952  20221226   160000    160459  ...         0.0        0.0       0
5953  20221226   160500    160959  ...         0.0        0.0       0
5954  20221226   161000    161459  ...         0.0        0.0       0

[5 rows x 18 columns]
2022-12-26 16:15:00,595:INFO:sr_min:main.py:175:handleKline:449472: self.closeSec=1672042499, self.tradeDate='20221226', self.openTime='161000', self.closeTime='161459',self.symbol='BTCUSDT',self.open=16830.9, self.close=16826.1, self.high=16830.9, self.low=16825.0, self.vol=797.57, self.amt=13421736.5768, ukdf['pct'].iloc[-1]=-0.000279 , ukdf['amount'].iloc[-1]=13421736.5768, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5954, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': []}
type(curSign)=<class 'int'>, curSign=0, self.sign=0


## /root/FIL/strategy/s_rsrs/log.txt ----- -----

721  20221226   040000    075959  1672012799  ...    721  0.014034 -1.099894    -1.0
722  20221226   080000    115959  1672027199  ...    722  0.016435 -1.074848    -1.0

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '53.372', 'enterprice': '16723.1', 'countrevence': '0', 'unrealprofit': '-8774.49051340532', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '16887.50250531', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-1, self.sign=-1
127.0.0.1 - - [26/Dec/2022 16:00:01] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='s_rsrs', self.symbol='BTCUSDT', interval='4h', intervalSec=14400, wid=25, thd=0.6, self.sign=-1, self.total=891652.7479068, self.flagDict['side']='sell', self.tradeCount=7, self.count=186
self.closeSec=1672041599, self.tradeDate='20221226', self.openTime='120000', self.closeTime='155959', self.symbol='BTCUSDT', self.open=16887.2, self.close=16836.6, self.high=16919.8, self.low=16830.0, self.vol=24738.987, self.amt=417202871.7152 
2022-12-26 16:00:01,068:INFO:s_rsrs:main.py:141:handleKline:185271: self.closeSec=1672041599, self.tradeDate='20221226', self.openTime='120000', self.closeTime='155959',self.symbol='BTCUSDT',self.open=16887.2, self.close=16836.6, self.high=16919.8, self.low=16830.0, self.vol=24738.987, self.amt=417202871.7152 
2022-12-26 16:00:01,094:INFO:s_rsrs:main.py:142:handleKline:185271: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime  ...        vol           amt       pct
719  20221225   200000    235959  ...  58570.137  9.834614e+08 -0.001832
720  20221226   000000    035959  ...  29179.332  4.893140e+08  0.000149
721  20221226   040000    075959  ...  24820.079  4.170106e+08  0.002252
722  20221226   080000    115959  ...  28620.905  4.824813e+08  0.003727
723  20221226   120000    155959  ...  24738.987  4.172029e+08 -0.002990

[5 rows x 11 columns]
2022-12-26 16:00:02,597:INFO:s_rsrs:main.py:151:handleKline:185271: df_s.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec  ...  index      beta    zscore  signal
719  20221225   200000    235959  1671983999  ...    719  0.004976 -1.162320    -1.0
720  20221226   000000    035959  1671998399  ...    720  0.012552 -1.123865    -1.0
721  20221226   040000    075959  1672012799  ...    721  0.014034 -1.099894    -1.0
722  20221226   080000    115959  1672027199  ...    722  0.016435 -1.074848    -1.0
723  20221226   120000    155959  1672041599  ...    723  0.023063 -1.041725    -1.0

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '53.372', 'enterprice': '16723.1', 'countrevence': '0', 'unrealprofit': '-6057.722', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '16836.6', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-1, self.sign=-1


