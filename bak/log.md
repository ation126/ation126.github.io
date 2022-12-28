# 20221228 16:16:01

## /root/FIL/strategy/amihud/log.txt ----- -----

127.0.0.1 - - [28/Dec/2022 16:10:01] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=993672.4896432, self.flagDict['side']='sell', self.tradeCount=2, self.count=8954
self.closeSec=1672214999, self.tradeDate='20221228', self.openTime='160500', self.closeTime='160959', self.symbol='BTCUSDT', self.open=16649.5, self.close=16637.7, self.high=16649.5, self.low=16636.2, self.vol=616.669, self.amt=10262787.2863 
2022-12-28 16:10:01,476:INFO:amihud:main.py:172:handleKline:200676: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5949  20221228   154500    154959  ...         0.0        0.0       0
5950  20221228   155000    155459  ...         0.0        0.0       0
5951  20221228   155500    155959  ...         0.0        0.0       0
5952  20221228   160000    160459  ...         0.0        0.0       0
5953  20221228   160500    160959  ...         0.0        0.0       0

[5 rows x 18 columns]
2022-12-28 16:10:01,477:INFO:amihud:main.py:175:handleKline:200676: self.closeSec=1672214999, self.tradeDate='20221228', self.openTime='160500', self.closeTime='160959',self.symbol='BTCUSDT',self.open=16649.5, self.close=16637.7, self.high=16649.5, self.low=16636.2, self.vol=616.669, self.amt=10262787.2863, ukdf['pct'].iloc[-1]=-0.000643 , ukdf['amount'].iloc[-1]=10262787.2863, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5953, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '60.176', 'enterprice': '16529.3', 'countrevence': '0', 'unrealprofit': '-6582.7090188944', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '16638.6909369', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1
127.0.0.1 - - [28/Dec/2022 16:15:00] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=993672.4896432, self.flagDict['side']='sell', self.tradeCount=2, self.count=8955
self.closeSec=1672215299, self.tradeDate='20221228', self.openTime='161000', self.closeTime='161459', self.symbol='BTCUSDT', self.open=16637.7, self.close=16636.0, self.high=16648.4, self.low=16633.0, self.vol=459.136, self.amt=7640614.4113 
2022-12-28 16:15:00,579:INFO:amihud:main.py:172:handleKline:200676: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5950  20221228   155000    155459  ...         0.0        0.0       0
5951  20221228   155500    155959  ...         0.0        0.0       0
5952  20221228   160000    160459  ...         0.0        0.0       0
5953  20221228   160500    160959  ...         0.0        0.0       0
5954  20221228   161000    161459  ...         0.0        0.0       0

[5 rows x 18 columns]
2022-12-28 16:15:00,579:INFO:amihud:main.py:175:handleKline:200676: self.closeSec=1672215299, self.tradeDate='20221228', self.openTime='161000', self.closeTime='161459',self.symbol='BTCUSDT',self.open=16637.7, self.close=16636.0, self.high=16648.4, self.low=16633.0, self.vol=459.136, self.amt=7640614.4113, ukdf['pct'].iloc[-1]=-0.000102 , ukdf['amount'].iloc[-1]=7640614.4113, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5954, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '60.176', 'enterprice': '16529.3', 'countrevence': '0', 'unrealprofit': '-6508.58248541504', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '16637.45910804', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1


## /root/FIL/strategy/factorcheck/log.txt ----- -----

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.7026338027285258, self.count=9520 

self.closeSec=1672214999, self.tradeDate='20221228', self.openTime='160500', self.closeTime='160959', self.symbol='BTCUSDT', self.open=16649.5, self.close=16637.7, self.high=16649.5, self.low=16636.2 
2022-12-28 16:10:01,412:INFO:factorcheck2:main.py:126:handleKline:185239: self.closeSec=1672214999, self.tradeDate='20221228', self.openTime='160500', self.closeTime='160959',self.symbol='BTCUSDT',self.open=16649.5, self.close=16637.7, self.high=16649.5, self.low=16636.2   
2022-12-28 16:10:01,433:INFO:factorcheck2:main.py:127:handleKline:185239: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1629  20221228   154500    154959  1672213799  ...  16637.8  0.000000   1629    3
1630  20221228   155000    155459  1672214099  ...  16633.2  0.000090   1630    4
1631  20221228   155500    155959  1672214399  ...  16638.0 -0.000024   1631    5
1632  20221228   160000    160459  1672214699  ...  16623.3  0.000565   1632    0
1633  20221228   160500    160959  1672214999  ...  16636.2 -0.000643   1633    1

[5 rows x 11 columns]
2022-12-28 16:10:01,433:INFO:factorcheck2:main.py:128:handleKline:185239: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': False, 'isOpen': True, 'isClose': False, 'isTrig': True}
127.0.0.1 - - [28/Dec/2022 16:15:00] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.7026338027285258, self.count=9521 

self.closeSec=1672215299, self.tradeDate='20221228', self.openTime='161000', self.closeTime='161459', self.symbol='BTCUSDT', self.open=16637.7, self.close=16636.0, self.high=16648.4, self.low=16633.0 
2022-12-28 16:15:00,526:INFO:factorcheck2:main.py:126:handleKline:185239: self.closeSec=1672215299, self.tradeDate='20221228', self.openTime='161000', self.closeTime='161459',self.symbol='BTCUSDT',self.open=16637.7, self.close=16636.0, self.high=16648.4, self.low=16633.0   
2022-12-28 16:15:00,550:INFO:factorcheck2:main.py:127:handleKline:185239: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1630  20221228   155000    155459  1672214099  ...  16633.2  0.000090   1630    4
1631  20221228   155500    155959  1672214399  ...  16638.0 -0.000024   1631    5
1632  20221228   160000    160459  1672214699  ...  16623.3  0.000565   1632    0
1633  20221228   160500    160959  1672214999  ...  16636.2 -0.000643   1633    1
1634  20221228   161000    161459  1672215299  ...  16633.0 -0.000102   1634    2

[5 rows x 11 columns]
2022-12-28 16:15:00,550:INFO:factorcheck2:main.py:128:handleKline:185239: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': False, 'isOpen': True, 'isClose': False, 'isTrig': True}


## /root/FIL/strategy/logic/log.txt ----- -----

2022-12-28 16:00:18,274:DEBUG:logic:main.py:454:getModel:174970: df_s.iloc[-5:,:] :
          date closeTime     open  ...    alpha58   alpha67   alpha72
5786  20221228    132959  16653.7  ...  43.333333  0.412116  0.688454
5787  20221228    135959  16635.8  ...  43.333333  0.393191  0.697843
5788  20221228    142959  16597.2  ...  43.750000  0.401730  0.703728
5789  20221228    145959  16608.5  ...  43.333333  0.399799  0.709925
5790  20221228    152959  16604.8  ...  43.333333  0.426513  0.706509

[5 rows x 33 columns]
0.5276752767527675
acc is : 0.5276752767527675
2022-12-28 16:00:18,350:INFO:logic:main.py:459:getModel:174970: df_pred.iloc[-5:,:] :
     pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
537     1  0.490521  0.509479       0  ...  0.991487   1.0    0.0  0.993981
538     1  0.488451  0.511549       1  ...  0.992162   1.0    0.0  0.994658
539     1  0.497450  0.502550       0  ...  0.991935   1.0    0.0  0.994430
540     1  0.492392  0.507608       1  ...  0.994092   1.0    0.0  0.996592
541     0  0.504839  0.495161       0  ...  0.993984   1.0    0.0  0.996485

[5 rows x 10 columns]
2022-12-28 16:00:18,361:INFO:logic:main.py:469:getModel:174970: df_panel.iloc[-5:,:] :
    pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
45     1  0.490500  0.509500       0  ...  0.982178   1.0    0.0  0.992946
46     1  0.488809  0.511191       1  ...  0.982846   1.0    0.0  1.001061
47     1  0.497372  0.502628       0  ...  0.991935   1.0    0.0  0.998833
48     1  0.492110  0.507890       1  ...  0.994092   1.0    0.0  0.995650
49     0  0.504839  0.495161       0  ...  0.993984   1.0    0.0  0.996485

[5 rows x 10 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '42.528', 'enterprice': '16701.5', 'countrevence': '0', 'unrealprofit': '-2625.68952721536', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '16639.75974588', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}


## /root/FIL/strategy/modifiedmom/log.txt ----- -----

526  20221228   154000    154959  1672213799  16646.9  16637.9 -0.000535
2022-12-28 15:50:00,872:INFO:modifiedmom:main.py:146:handleKline:185213: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': True, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True}
127.0.0.1 - - [28/Dec/2022 16:00:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=4759 

self.closeSec=1672214399, self.tradeDate='20221228', self.openTime='155000', self.closeTime='155959', self.symbol='BTCUSDT', self.open='16637.9', self.close='16639'
2022-12-28 16:00:01,429:INFO:modifiedmom:main.py:144:handleKline:185213: self.closeSec=1672214399, self.tradeDate='20221228', self.openTime='155000', self.closeTime='155959',self.symbol='BTCUSDT',self.open='16637.9', self.close='16639'
2022-12-28 16:00:01,463:INFO:modifiedmom:main.py:145:handleKline:185213: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
523  20221228   151000    151959  1672211999  16625.4  16636.6  0.000674
524  20221228   152000    152959  1672212599  16636.6  16640.8  0.000252
525  20221228   153000    153959  1672213199  16640.9  16646.8  0.000361
526  20221228   154000    154959  1672213799  16646.9  16637.9 -0.000535
527  20221228   155000    155959  1672214399  16637.9    16639  0.000066
2022-12-28 16:00:01,464:INFO:modifiedmom:main.py:146:handleKline:185213: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': True, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True}
127.0.0.1 - - [28/Dec/2022 16:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=4760 

self.closeSec=1672214999, self.tradeDate='20221228', self.openTime='160000', self.closeTime='160959', self.symbol='BTCUSDT', self.open='16639.1', self.close='16636.7'
2022-12-28 16:10:01,513:INFO:modifiedmom:main.py:144:handleKline:185213: self.closeSec=1672214999, self.tradeDate='20221228', self.openTime='160000', self.closeTime='160959',self.symbol='BTCUSDT',self.open='16639.1', self.close='16636.7'
2022-12-28 16:10:01,538:INFO:modifiedmom:main.py:145:handleKline:185213: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
524  20221228   152000    152959  1672212599  16636.6  16640.8  0.000252
525  20221228   153000    153959  1672213199  16640.9  16646.8  0.000361
526  20221228   154000    154959  1672213799  16646.9  16637.9 -0.000535
527  20221228   155000    155959  1672214399  16637.9    16639  0.000066
528  20221228   160000    160959  1672214999  16639.1  16636.7 -0.000138
2022-12-28 16:10:01,538:INFO:modifiedmom:main.py:146:handleKline:185213: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': True, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True}


## /root/FIL/strategy/pyemd/log.txt ----- -----

17518  20221228   154000    154959  1672213799  16646.9  16637.9
2022-12-28 15:50:00,842:INFO:pyemd2:main.py:127:handleKline:185189: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=4760 

self.closeSec=1672214399, self.tradeDate='20221228', self.openTime='155000', self.closeTime='155959', self.symbol='BTCUSDT', self.open='16637.9', self.close='16639'
127.0.0.1 - - [28/Dec/2022 16:00:01] "POST / HTTP/1.1" 200 -
2022-12-28 16:00:01,452:INFO:pyemd2:main.py:125:handleKline:185189: self.closeSec=1672214399, self.tradeDate='20221228', self.openTime='155000', self.closeTime='155959',self.symbol='BTCUSDT',self.open='16637.9', self.close='16639'
2022-12-28 16:00:01,489:INFO:pyemd2:main.py:126:handleKline:185189: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17515  20221228   151000    151959  1672211999  16625.4  16636.6
17516  20221228   152000    152959  1672212599  16636.6  16640.8
17517  20221228   153000    153959  1672213199  16640.9  16646.8
17518  20221228   154000    154959  1672213799  16646.9  16637.9
17519  20221228   155000    155959  1672214399  16637.9    16639
2022-12-28 16:00:01,489:INFO:pyemd2:main.py:127:handleKline:185189: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}
127.0.0.1 - - [28/Dec/2022 16:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=4761 

self.closeSec=1672214999, self.tradeDate='20221228', self.openTime='160000', self.closeTime='160959', self.symbol='BTCUSDT', self.open='16639.1', self.close='16636.7'
2022-12-28 16:10:01,530:INFO:pyemd2:main.py:125:handleKline:185189: self.closeSec=1672214999, self.tradeDate='20221228', self.openTime='160000', self.closeTime='160959',self.symbol='BTCUSDT',self.open='16639.1', self.close='16636.7'
2022-12-28 16:10:01,541:INFO:pyemd2:main.py:126:handleKline:185189: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17516  20221228   152000    152959  1672212599  16636.6  16640.8
17517  20221228   153000    153959  1672213199  16640.9  16646.8
17518  20221228   154000    154959  1672213799  16646.9  16637.9
17519  20221228   155000    155959  1672214399  16637.9    16639
17520  20221228   160000    160959  1672214999  16639.1  16636.7
2022-12-28 16:10:01,542:INFO:pyemd2:main.py:127:handleKline:185189: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}


## /root/FIL/strategy/similarity/log.txt ----- -----

12190  20221228   154000    154959  1672213799  16646.9  16637.9
2022-12-28 15:50:00,815:INFO:testStrategy:main.py:103:handleKline:185174: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': True, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=4760 

self.closeSec=1672214399, self.tradeDate='20221228', self.openTime='155000', self.closeTime='155959', self.symbol='BTCUSDT', self.open='16637.9', self.close='16639'
127.0.0.1 - - [28/Dec/2022 16:00:01] "POST / HTTP/1.1" 200 -
2022-12-28 16:00:01,459:INFO:testStrategy:main.py:101:handleKline:185174: self.closeSec=1672214399, self.tradeDate='20221228', self.openTime='155000', self.closeTime='155959',self.symbol='BTCUSDT',self.open='16637.9', self.close='16639'
2022-12-28 16:00:01,482:INFO:testStrategy:main.py:102:handleKline:185174: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12187  20221228   151000    151959  1672211999  16625.4  16636.6
12188  20221228   152000    152959  1672212599  16636.6  16640.8
12189  20221228   153000    153959  1672213199  16640.9  16646.8
12190  20221228   154000    154959  1672213799  16646.9  16637.9
12191  20221228   155000    155959  1672214399  16637.9    16639
2022-12-28 16:00:01,482:INFO:testStrategy:main.py:103:handleKline:185174: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': True, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=4761 

self.closeSec=1672214999, self.tradeDate='20221228', self.openTime='160000', self.closeTime='160959', self.symbol='BTCUSDT', self.open='16639.1', self.close='16636.7'
2022-12-28 16:10:01,527:INFO:testStrategy:main.py:101:handleKline:185174: self.closeSec=1672214999, self.tradeDate='20221228', self.openTime='160000', self.closeTime='160959',self.symbol='BTCUSDT',self.open='16639.1', self.close='16636.7'
127.0.0.1 - - [28/Dec/2022 16:10:01] "POST / HTTP/1.1" 200 -
2022-12-28 16:10:01,539:INFO:testStrategy:main.py:102:handleKline:185174: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12188  20221228   152000    152959  1672212599  16636.6  16640.8
12189  20221228   153000    153959  1672213199  16640.9  16646.8
12190  20221228   154000    154959  1672213799  16646.9  16637.9
12191  20221228   155000    155959  1672214399  16637.9    16639
12192  20221228   160000    160959  1672214999  16639.1  16636.7
2022-12-28 16:10:01,539:INFO:testStrategy:main.py:103:handleKline:185174: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': True, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}


## /root/FIL/strategy/sr_min/log.txt ----- -----

127.0.0.1 - - [28/Dec/2022 16:10:01] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=0, self.total=1000000.0, self.flagDict['side']='', self.tradeCount=0, self.count=4952
self.closeSec=1672214999, self.tradeDate='20221228', self.openTime='160500', self.closeTime='160959', self.symbol='BTCUSDT', self.open=16649.5, self.close=16637.7, self.high=16649.5, self.low=16636.2, self.vol=616.669, self.amt=10262787.2863 
2022-12-28 16:10:01,450:INFO:sr_min:main.py:172:handleKline:449472: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5949  20221228   154500    154959  ...         0.0        0.0       0
5950  20221228   155000    155459  ...         0.0        0.0       0
5951  20221228   155500    155959  ...         0.0        0.0       0
5952  20221228   160000    160459  ...         0.0        0.0       0
5953  20221228   160500    160959  ...         0.0        0.0       0

[5 rows x 18 columns]
2022-12-28 16:10:01,450:INFO:sr_min:main.py:175:handleKline:449472: self.closeSec=1672214999, self.tradeDate='20221228', self.openTime='160500', self.closeTime='160959',self.symbol='BTCUSDT',self.open=16649.5, self.close=16637.7, self.high=16649.5, self.low=16636.2, self.vol=616.669, self.amt=10262787.2863, ukdf['pct'].iloc[-1]=-0.000643 , ukdf['amount'].iloc[-1]=10262787.2863, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5953, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': []}
type(curSign)=<class 'int'>, curSign=0, self.sign=0
--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=0, self.total=1000000.0, self.flagDict['side']='', self.tradeCount=0, self.count=4953
self.closeSec=1672215299, self.tradeDate='20221228', self.openTime='161000', self.closeTime='161459', self.symbol='BTCUSDT', self.open=16637.7, self.close=16636.0, self.high=16648.4, self.low=16633.0, self.vol=459.136, self.amt=7640614.4113 
127.0.0.1 - - [28/Dec/2022 16:15:00] "POST / HTTP/1.1" 200 -
2022-12-28 16:15:00,582:INFO:sr_min:main.py:172:handleKline:449472: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5950  20221228   155000    155459  ...         0.0        0.0       0
5951  20221228   155500    155959  ...         0.0        0.0       0
5952  20221228   160000    160459  ...         0.0        0.0       0
5953  20221228   160500    160959  ...         0.0        0.0       0
5954  20221228   161000    161459  ...         0.0        0.0       0

[5 rows x 18 columns]
2022-12-28 16:15:00,583:INFO:sr_min:main.py:175:handleKline:449472: self.closeSec=1672215299, self.tradeDate='20221228', self.openTime='161000', self.closeTime='161459',self.symbol='BTCUSDT',self.open=16637.7, self.close=16636.0, self.high=16648.4, self.low=16633.0, self.vol=459.136, self.amt=7640614.4113, ukdf['pct'].iloc[-1]=-0.000102 , ukdf['amount'].iloc[-1]=7640614.4113, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5954, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': []}
type(curSign)=<class 'int'>, curSign=0, self.sign=0


## /root/FIL/strategy/s_rsrs/log.txt ----- -----

721  20221228   040000    075959  1672185599  ...    721  0.131348 -0.681255    -1.0
722  20221228   080000    115959  1672199999  ...    722  0.139470 -0.658077    -1.0

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '53.372', 'enterprice': '16723.1', 'countrevence': '0', 'unrealprofit': '4197.86806170556', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '16644.44699727', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-1, self.sign=-1
--handleKline--:  version='2.0.0', self.name='s_rsrs', self.symbol='BTCUSDT', interval='4h', intervalSec=14400, wid=25, thd=0.6, self.sign=-1, self.total=891652.7479068, self.flagDict['side']='sell', self.tradeCount=7, self.count=198
self.closeSec=1672214399, self.tradeDate='20221228', self.openTime='120000', self.closeTime='155959', self.symbol='BTCUSDT', self.open=16643.2, self.close=16639.0, self.high=16672.3, self.low=16580.6, self.vol=40102.069, self.amt=666558151.9986 
2022-12-28 16:00:01,325:INFO:s_rsrs:main.py:141:handleKline:185271: self.closeSec=1672214399, self.tradeDate='20221228', self.openTime='120000', self.closeTime='155959',self.symbol='BTCUSDT',self.open=16643.2, self.close=16639.0, self.high=16672.3, self.low=16580.6, self.vol=40102.069, self.amt=666558151.9986 
127.0.0.1 - - [28/Dec/2022 16:00:01] "POST / HTTP/1.1" 200 -
2022-12-28 16:00:01,387:INFO:s_rsrs:main.py:142:handleKline:185271: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime  ...        vol           amt       pct
719  20221227   200000    235959  ...  66673.069  1.119302e+09 -0.001956
720  20221228   000000    035959  ...  78151.443  1.303535e+09 -0.006516
721  20221228   040000    075959  ...  29295.519  4.886661e+08  0.001013
722  20221228   080000    115959  ...  58603.619  9.755579e+08 -0.003288
723  20221228   120000    155959  ...  40102.069  6.665582e+08 -0.000258

[5 rows x 11 columns]
2022-12-28 16:00:02,873:INFO:s_rsrs:main.py:151:handleKline:185271: df_s.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec  ...  index      beta    zscore  signal
719  20221227   200000    235959  1672156799  ...    719  0.000625 -0.966176    -1.0
720  20221228   000000    035959  1672171199  ...    720  0.052460 -0.853560    -1.0
721  20221228   040000    075959  1672185599  ...    721  0.131348 -0.681255    -1.0
722  20221228   080000    115959  1672199999  ...    722  0.139470 -0.658077    -1.0
723  20221228   120000    155959  1672214399  ...    723  0.220248 -0.486980     NaN

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '53.372', 'enterprice': '16723.1', 'countrevence': '0', 'unrealprofit': '4458.11417411096', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '16639.57091782', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-9223372036854775808, self.sign=-1


