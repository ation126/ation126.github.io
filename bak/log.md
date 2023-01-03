# 20230103 16:16:01

## /root/FIL/strategy/amihud/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=993672.4896432, self.flagDict['side']='sell', self.tradeCount=2, self.count=10682
self.closeSec=1672733399, self.tradeDate='20230103', self.openTime='160500', self.closeTime='160959', self.symbol='BTCUSDT', self.open=16725.5, self.close=16715.6, self.high=16725.6, self.low=16715.6, self.vol=809.477, self.amt=13534482.2311 
127.0.0.1 - - [03/Jan/2023 16:10:01] "POST / HTTP/1.1" 200 -
2023-01-03 16:10:01,684:INFO:amihud:main.py:172:handleKline:200676: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5949  20230103   154500    154959  ...         0.0        0.0       0
5950  20230103   155000    155459  ...         0.0        0.0       0
5951  20230103   155500    155959  ...         0.0        0.0       0
5952  20230103   160000    160459  ...         0.0        0.0       0
5953  20230103   160500    160959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-01-03 16:10:01,684:INFO:amihud:main.py:175:handleKline:200676: self.closeSec=1672733399, self.tradeDate='20230103', self.openTime='160500', self.closeTime='160959',self.symbol='BTCUSDT',self.open=16725.5, self.close=16715.6, self.high=16725.6, self.low=16715.6, self.vol=809.477, self.amt=13534482.2311, ukdf['pct'].iloc[-1]=-0.000592 , ukdf['amount'].iloc[-1]=13534482.2311, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5953, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '60.176', 'enterprice': '16529.3', 'countrevence': '0', 'unrealprofit': '-11210.7888', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '16715.6', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1
127.0.0.1 - - [03/Jan/2023 16:15:00] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=993672.4896432, self.flagDict['side']='sell', self.tradeCount=2, self.count=10683
self.closeSec=1672733699, self.tradeDate='20230103', self.openTime='161000', self.closeTime='161459', self.symbol='BTCUSDT', self.open=16715.6, self.close=16711.7, self.high=16715.7, self.low=16711.7, self.vol=367.099, self.amt=6135446.4509 
2023-01-03 16:15:00,650:INFO:amihud:main.py:172:handleKline:200676: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5950  20230103   155000    155459  ...         0.0        0.0       0
5951  20230103   155500    155959  ...         0.0        0.0       0
5952  20230103   160000    160459  ...         0.0        0.0       0
5953  20230103   160500    160959  ...         0.0        0.0       0
5954  20230103   161000    161459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-01-03 16:15:00,651:INFO:amihud:main.py:175:handleKline:200676: self.closeSec=1672733699, self.tradeDate='20230103', self.openTime='161000', self.closeTime='161459',self.symbol='BTCUSDT',self.open=16715.6, self.close=16711.7, self.high=16715.7, self.low=16711.7, self.vol=367.099, self.amt=6135446.4509, ukdf['pct'].iloc[-1]=-0.000233 , ukdf['amount'].iloc[-1]=6135446.4509, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5954, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '60.176', 'enterprice': '16529.3', 'countrevence': '0', 'unrealprofit': '-11029.08522994672', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '16712.58046447', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1


## /root/FIL/strategy/factorcheck/log.txt ----- -----


self.closeSec=1672733399, self.tradeDate='20230103', self.openTime='160500', self.closeTime='160959', self.symbol='BTCUSDT', self.open=16725.5, self.close=16715.6, self.high=16725.6, self.low=16715.6 
2023-01-03 16:10:01,655:INFO:factorcheck2:main.py:126:handleKline:185239: self.closeSec=1672733399, self.tradeDate='20230103', self.openTime='160500', self.closeTime='160959',self.symbol='BTCUSDT',self.open=16725.5, self.close=16715.6, self.high=16725.6, self.low=16715.6   
127.0.0.1 - - [03/Jan/2023 16:10:01] "POST / HTTP/1.1" 200 -
2023-01-03 16:10:01,721:INFO:factorcheck2:main.py:127:handleKline:185239: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1629  20230103   154500    154959  1672732199  ...  16714.7  0.000401   1629    3
1630  20230103   155000    155459  1672732499  ...  16720.0  0.000048   1630    4
1631  20230103   155500    155959  1672732799  ...  16721.5  0.000048   1631    5
1632  20230103   160000    160459  1672733099  ...  16723.0  0.000149   1632    0
1633  20230103   160500    160959  1672733399  ...  16715.6 -0.000592   1633    1

[5 rows x 11 columns]
2023-01-03 16:10:01,722:INFO:factorcheck2:main.py:128:handleKline:185239: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=38, self.factor=0.416163256730493, self.count=11249 

self.closeSec=1672733699, self.tradeDate='20230103', self.openTime='161000', self.closeTime='161459', self.symbol='BTCUSDT', self.open=16715.6, self.close=16711.7, self.high=16715.7, self.low=16711.7 
2023-01-03 16:15:00,525:INFO:factorcheck2:main.py:126:handleKline:185239: self.closeSec=1672733699, self.tradeDate='20230103', self.openTime='161000', self.closeTime='161459',self.symbol='BTCUSDT',self.open=16715.6, self.close=16711.7, self.high=16715.7, self.low=16711.7   
127.0.0.1 - - [03/Jan/2023 16:15:00] "POST / HTTP/1.1" 200 -
2023-01-03 16:15:00,544:INFO:factorcheck2:main.py:127:handleKline:185239: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1630  20230103   155000    155459  1672732499  ...  16720.0  0.000048   1630    4
1631  20230103   155500    155959  1672732799  ...  16721.5  0.000048   1631    5
1632  20230103   160000    160459  1672733099  ...  16723.0  0.000149   1632    0
1633  20230103   160500    160959  1672733399  ...  16715.6 -0.000592   1633    1
1634  20230103   161000    161459  1672733699  ...  16711.7 -0.000233   1634    2

[5 rows x 11 columns]
2023-01-03 16:15:00,544:INFO:factorcheck2:main.py:128:handleKline:185239: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}


## /root/FIL/strategy/logic/log.txt ----- -----

2023-01-03 16:00:18,275:DEBUG:logic:main.py:456:getModel:726423: df_s.iloc[-5:,:] :
          date closeTime     open  ...    alpha58   alpha67   alpha72
5786  20230103    132959  16677.9  ...  49.166667  0.528463  0.527733
5787  20230103    135959  16685.3  ...  49.166667  0.553265  0.525571
5788  20230103    142959  16720.0  ...  49.583333  0.575584  0.509342
5789  20230103    145959  16754.0  ...  49.166667  0.547429  0.508531
5790  20230103    152959  16719.8  ...  49.166667  0.538188  0.512706

[5 rows x 33 columns]
0.518450184501845
acc is : 0.518450184501845
2023-01-03 16:00:18,370:INFO:logic:main.py:461:getModel:726423: df_pred.iloc[-5:,:] :
     pred    prob_0    prob_1  actual  ...  nav  sign   cost_        bm
537     1  0.498751  0.501249       1  ...  NaN   NaN -0.0016  0.996709
538     0  0.506972  0.493028       1  ...  NaN   NaN -0.0016  0.998736
539     0  0.510022  0.489978       0  ...  NaN   NaN -0.0016  0.996692
540     1  0.491644  0.508356       0  ...  NaN   NaN -0.0016  0.995988
541     1  0.495346  0.504654       1  ...  NaN   NaN -0.0016  0.996888

[5 rows x 10 columns]
2023-01-03 16:00:18,381:INFO:logic:main.py:471:getModel:726423: df_panel.iloc[-5:,:] :
    pred    prob_0    prob_1  actual  ...  nav  sign   cost_        bm
38     1  0.498755  0.501245       1  ...  NaN   NaN -0.0016  0.995523
39     0  0.506446  0.493554       1  ...  NaN   NaN -0.0016  0.996900
40     0  0.509554  0.490446       0  ...  NaN   NaN -0.0016  0.994303
41     1  0.491224  0.508776       0  ...  NaN   NaN -0.0016  0.994921
42     1  0.495346  0.504654       1  ...  NaN   NaN -0.0016  0.996888

[5 rows x 10 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '42.528', 'enterprice': '16701.5', 'countrevence': '0', 'unrealprofit': '1050.66579145536', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '16726.20527162', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}


## /root/FIL/strategy/modifiedmom/log.txt ----- -----

526  20230103   154000    154959  1672732199  16707.1  16721.5  0.000868
2023-01-03 15:50:00,560:INFO:modifiedmom:main.py:146:handleKline:185213: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True}

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=5623 

self.closeSec=1672732799, self.tradeDate='20230103', self.openTime='155000', self.closeTime='155959', self.symbol='BTCUSDT', self.open='16721.5', self.close='16723.1'
2023-01-03 16:00:00,891:INFO:modifiedmom:main.py:144:handleKline:185213: self.closeSec=1672732799, self.tradeDate='20230103', self.openTime='155000', self.closeTime='155959',self.symbol='BTCUSDT',self.open='16721.5', self.close='16723.1'
127.0.0.1 - - [03/Jan/2023 16:00:00] "POST / HTTP/1.1" 200 -
2023-01-03 16:00:00,928:INFO:modifiedmom:main.py:145:handleKline:185213: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
523  20230103   151000    151959  1672730399    16719  16716.9 -0.000120
524  20230103   152000    152959  1672730999  16716.9  16707.9 -0.000538
525  20230103   153000    153959  1672731599    16708    16707 -0.000054
526  20230103   154000    154959  1672732199  16707.1  16721.5  0.000868
527  20230103   155000    155959  1672732799  16721.5  16723.1  0.000096
2023-01-03 16:00:00,928:INFO:modifiedmom:main.py:146:handleKline:185213: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True}
127.0.0.1 - - [03/Jan/2023 16:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=5624 

self.closeSec=1672733399, self.tradeDate='20230103', self.openTime='160000', self.closeTime='160959', self.symbol='BTCUSDT', self.open='16723.1', self.close='16715.6'
2023-01-03 16:10:01,761:INFO:modifiedmom:main.py:144:handleKline:185213: self.closeSec=1672733399, self.tradeDate='20230103', self.openTime='160000', self.closeTime='160959',self.symbol='BTCUSDT',self.open='16723.1', self.close='16715.6'
2023-01-03 16:10:01,809:INFO:modifiedmom:main.py:145:handleKline:185213: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
524  20230103   152000    152959  1672730999  16716.9  16707.9 -0.000538
525  20230103   153000    153959  1672731599    16708    16707 -0.000054
526  20230103   154000    154959  1672732199  16707.1  16721.5  0.000868
527  20230103   155000    155959  1672732799  16721.5  16723.1  0.000096
528  20230103   160000    160959  1672733399  16723.1  16715.6 -0.000448
2023-01-03 16:10:01,810:INFO:modifiedmom:main.py:146:handleKline:185213: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True}


## /root/FIL/strategy/pyemd/log.txt ----- -----

17518  20230103   154000    154959  1672732199  16707.1  16721.5
2023-01-03 15:50:00,584:INFO:pyemd2:main.py:127:handleKline:185189: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=5624 

self.closeSec=1672732799, self.tradeDate='20230103', self.openTime='155000', self.closeTime='155959', self.symbol='BTCUSDT', self.open='16721.5', self.close='16723.1'
127.0.0.1 - - [03/Jan/2023 16:00:00] "POST / HTTP/1.1" 200 -
2023-01-03 16:00:00,881:INFO:pyemd2:main.py:125:handleKline:185189: self.closeSec=1672732799, self.tradeDate='20230103', self.openTime='155000', self.closeTime='155959',self.symbol='BTCUSDT',self.open='16721.5', self.close='16723.1'
2023-01-03 16:00:00,909:INFO:pyemd2:main.py:126:handleKline:185189: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17515  20230103   151000    151959  1672730399    16719  16716.9
17516  20230103   152000    152959  1672730999  16716.9  16707.9
17517  20230103   153000    153959  1672731599    16708    16707
17518  20230103   154000    154959  1672732199  16707.1  16721.5
17519  20230103   155000    155959  1672732799  16721.5  16723.1
2023-01-03 16:00:00,924:INFO:pyemd2:main.py:127:handleKline:185189: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}
127.0.0.1 - - [03/Jan/2023 16:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=5625 

self.closeSec=1672733399, self.tradeDate='20230103', self.openTime='160000', self.closeTime='160959', self.symbol='BTCUSDT', self.open='16723.1', self.close='16715.6'
2023-01-03 16:10:01,757:INFO:pyemd2:main.py:125:handleKline:185189: self.closeSec=1672733399, self.tradeDate='20230103', self.openTime='160000', self.closeTime='160959',self.symbol='BTCUSDT',self.open='16723.1', self.close='16715.6'
2023-01-03 16:10:01,814:INFO:pyemd2:main.py:126:handleKline:185189: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17516  20230103   152000    152959  1672730999  16716.9  16707.9
17517  20230103   153000    153959  1672731599    16708    16707
17518  20230103   154000    154959  1672732199  16707.1  16721.5
17519  20230103   155000    155959  1672732799  16721.5  16723.1
17520  20230103   160000    160959  1672733399  16723.1  16715.6
2023-01-03 16:10:01,815:INFO:pyemd2:main.py:127:handleKline:185189: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}


## /root/FIL/strategy/similarity/log.txt ----- -----

12190  20230103   154000    154959  1672732199  16707.1  16721.5
2023-01-03 15:50:00,577:INFO:testStrategy:main.py:103:handleKline:185174: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': True, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=5624 

self.closeSec=1672732799, self.tradeDate='20230103', self.openTime='155000', self.closeTime='155959', self.symbol='BTCUSDT', self.open='16721.5', self.close='16723.1'
127.0.0.1 - - [03/Jan/2023 16:00:00] "POST / HTTP/1.1" 200 -
2023-01-03 16:00:00,897:INFO:testStrategy:main.py:101:handleKline:185174: self.closeSec=1672732799, self.tradeDate='20230103', self.openTime='155000', self.closeTime='155959',self.symbol='BTCUSDT',self.open='16721.5', self.close='16723.1'
2023-01-03 16:00:00,920:INFO:testStrategy:main.py:102:handleKline:185174: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12187  20230103   151000    151959  1672730399    16719  16716.9
12188  20230103   152000    152959  1672730999  16716.9  16707.9
12189  20230103   153000    153959  1672731599    16708    16707
12190  20230103   154000    154959  1672732199  16707.1  16721.5
12191  20230103   155000    155959  1672732799  16721.5  16723.1
2023-01-03 16:00:00,920:INFO:testStrategy:main.py:103:handleKline:185174: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': True, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}
127.0.0.1 - - [03/Jan/2023 16:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=5625 

self.closeSec=1672733399, self.tradeDate='20230103', self.openTime='160000', self.closeTime='160959', self.symbol='BTCUSDT', self.open='16723.1', self.close='16715.6'
2023-01-03 16:10:01,780:INFO:testStrategy:main.py:101:handleKline:185174: self.closeSec=1672733399, self.tradeDate='20230103', self.openTime='160000', self.closeTime='160959',self.symbol='BTCUSDT',self.open='16723.1', self.close='16715.6'
2023-01-03 16:10:01,807:INFO:testStrategy:main.py:102:handleKline:185174: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12188  20230103   152000    152959  1672730999  16716.9  16707.9
12189  20230103   153000    153959  1672731599    16708    16707
12190  20230103   154000    154959  1672732199  16707.1  16721.5
12191  20230103   155000    155959  1672732799  16721.5  16723.1
12192  20230103   160000    160959  1672733399  16723.1  16715.6
2023-01-03 16:10:01,811:INFO:testStrategy:main.py:103:handleKline:185174: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': True, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}


## /root/FIL/strategy/sr_min/log.txt ----- -----

127.0.0.1 - - [03/Jan/2023 16:10:01] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=0, self.total=1000000.0, self.flagDict['side']='', self.tradeCount=0, self.count=6680
self.closeSec=1672733399, self.tradeDate='20230103', self.openTime='160500', self.closeTime='160959', self.symbol='BTCUSDT', self.open=16725.5, self.close=16715.6, self.high=16725.6, self.low=16715.6, self.vol=809.477, self.amt=13534482.2311 
2023-01-03 16:10:01,773:INFO:sr_min:main.py:172:handleKline:449472: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5949  20230103   154500    154959  ...         0.0        0.0       0
5950  20230103   155000    155459  ...         0.0        0.0       0
5951  20230103   155500    155959  ...         0.0        0.0       0
5952  20230103   160000    160459  ...         0.0        0.0       0
5953  20230103   160500    160959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-01-03 16:10:01,773:INFO:sr_min:main.py:175:handleKline:449472: self.closeSec=1672733399, self.tradeDate='20230103', self.openTime='160500', self.closeTime='160959',self.symbol='BTCUSDT',self.open=16725.5, self.close=16715.6, self.high=16725.6, self.low=16715.6, self.vol=809.477, self.amt=13534482.2311, ukdf['pct'].iloc[-1]=-0.000592 , ukdf['amount'].iloc[-1]=13534482.2311, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5953, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': []}
type(curSign)=<class 'int'>, curSign=0, self.sign=0
127.0.0.1 - - [03/Jan/2023 16:15:00] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=0, self.total=1000000.0, self.flagDict['side']='', self.tradeCount=0, self.count=6681
self.closeSec=1672733699, self.tradeDate='20230103', self.openTime='161000', self.closeTime='161459', self.symbol='BTCUSDT', self.open=16715.6, self.close=16711.7, self.high=16715.7, self.low=16711.7, self.vol=367.099, self.amt=6135446.4509 
2023-01-03 16:15:00,664:INFO:sr_min:main.py:172:handleKline:449472: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5950  20230103   155000    155459  ...         0.0        0.0       0
5951  20230103   155500    155959  ...         0.0        0.0       0
5952  20230103   160000    160459  ...         0.0        0.0       0
5953  20230103   160500    160959  ...         0.0        0.0       0
5954  20230103   161000    161459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-01-03 16:15:00,667:INFO:sr_min:main.py:175:handleKline:449472: self.closeSec=1672733699, self.tradeDate='20230103', self.openTime='161000', self.closeTime='161459',self.symbol='BTCUSDT',self.open=16715.6, self.close=16711.7, self.high=16715.7, self.low=16711.7, self.vol=367.099, self.amt=6135446.4509, ukdf['pct'].iloc[-1]=-0.000233 , ukdf['amount'].iloc[-1]=6135446.4509, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5954, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': []}
type(curSign)=<class 'int'>, curSign=0, self.sign=0


## /root/FIL/strategy/s_rsrs/log.txt ----- -----

720  20230103   000000    035959  ...  16546.853  2.766021e+08  0.000078
721  20230103   040000    075959  ...  35222.075  5.888274e+08 -0.003849
722  20230103   080000    115959  ...  22052.463  3.676388e+08  0.001110
723  20230103   120000    155959  ...  29396.023  4.915810e+08  0.002314

[5 rows x 11 columns]
2023-01-03 16:00:02,395:INFO:s_rsrs:main.py:151:handleKline:185271: df_s.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec  ...  index      beta    zscore  signal
719  20230102   200000    235959  1672675199  ...    719  0.216347 -0.038365     NaN
720  20230103   000000    035959  1672689599  ...    720  0.235114  0.060823     NaN
721  20230103   040000    075959  1672703999  ...    721  0.297501  0.321886     NaN
722  20230103   080000    115959  1672718399  ...    722  0.303175  0.384621     NaN
723  20230103   120000    155959  1672732799  ...    723  0.350542  0.614121     1.0

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '53.845', 'enterprice': '16564.2', 'countrevence': '0', 'unrealprofit': '-8676.2313023122', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '16725.33346276', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=1, self.sign=-1
handlebackTrade > queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '53.845', 'enterprice': '16564.2', 'countrevence': '0', 'unrealprofit': '-8676.2313023122', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '16725.33346276', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
2023-01-03 16:00:08,187:INFO:s_rsrs:main.py:182:queryContractAssets:185271: queryContractAssets: assets=ContractAssetReturn{'result': [ContractAsset{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'asset': 'USDT', 'free': '885139.6508322', 'total': '885139.6508322', 'margin': '0', 'unreal': '0', 'type': 'AssetType_ucontract'}]}
2023-01-03 16:00:08,436:DEBUG:s_rsrs:main.py:253:openBuy:185271: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': True, 'isCloseBuy': False, 'isCloseSell': False, 'isOpen': True, 'isClose': False, 'isTrig': False}
2023-01-03 16:00:08,436:INFO:s_rsrs:main.py:254:openBuy:185271: ret = self.client.insertMarketUOrder("simulator", "BTCUSDT", 52.770, "buy"), ret=InsertOrderReturn{'result': 'success', 'clientorderid': '41465F1672732808435I0L65'}
2023-01-03 16:00:08,453:INFO:s_rsrs:main.py:176:insertFactor:185271: curDateTime:1031600, name:s_rsrs, symbol:BTCUSDT, tradeDate:20230103, closeTime:155959, close:16723.1, sign:1, total:885139.6508322, side:buy  
127.0.0.1 - - [03/Jan/2023 16:00:08] "POST / HTTP/1.1" 200 -
2023-01-03 16:00:08,454:INFO:s_rsrs:main.py:343:handleOrderNew:185271: handleOrderNew: data=OrderType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'clientorderid': '41464F1672732803069I0L65', 'symbol': 'BTCUSDT', 'gatewayorderid': 1672732803173210, 'quantity': '53.845', 'price': '16723.1', 'stopprice': '0', 'ordertype': '', 'side': 'BUY', 'status': 'FILLED', 'positionside': 'LONG', 'createtime': 1672732802711, 'updatetime': 1672732803173, 'tradetype': 'usdt', 'selfid': 41464, 'filltrades': [TradeType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'tradeid': 1672732803173, 'clientorderid': '41464F1672732803069I0L65', 'price': '16723.1', 'quantity': '53.845', 'commission': '900.4553195', 'commissionasset': 'USDT', 'tradetime': 1672732803173, 'tradetype': 'usdt', 'gatetype': 'simulator', 'handletime': 1672732803173}], 'gatetype': 'simulator', 'handletime': 0}
127.0.0.1 - - [03/Jan/2023 16:00:08] "POST / HTTP/1.1" 200 -
2023-01-03 16:00:08,455:INFO:s_rsrs:main.py:346:handleOrderFilled:185271: handleOrderFilled: data=OrderType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'clientorderid': '41464F1672732803069I0L65', 'symbol': 'BTCUSDT', 'gatewayorderid': 1672732803173210, 'quantity': '53.845', 'price': '16723.1', 'stopprice': '0', 'ordertype': '', 'side': 'BUY', 'status': 'FILLED', 'positionside': 'LONG', 'createtime': 1672732802711, 'updatetime': 1672732803173, 'tradetype': 'usdt', 'selfid': 41464, 'filltrades': [TradeType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'tradeid': 1672732803173, 'clientorderid': '41464F1672732803069I0L65', 'price': '16723.1', 'quantity': '53.845', 'commission': '900.4553195', 'commissionasset': 'USDT', 'tradetime': 1672732803173, 'tradetype': 'usdt', 'gatetype': 'simulator', 'handletime': 1672732803173}], 'gatetype': 'simulator', 'handletime': 0}
127.0.0.1 - - [03/Jan/2023 16:00:08] "POST / HTTP/1.1" 200 -
2023-01-03 16:00:08,581:INFO:s_rsrs:main.py:343:handleOrderNew:185271: handleOrderNew: data=OrderType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'clientorderid': '41465F1672732808435I0L65', 'symbol': 'BTCUSDT', 'gatewayorderid': 1672732808546550, 'quantity': '52.77', 'price': '16723.1', 'stopprice': '0', 'ordertype': '', 'side': 'BUY', 'status': 'FILLED', 'positionside': 'LONG', 'createtime': 1672732808200, 'updatetime': 1672732808546, 'tradetype': 'usdt', 'selfid': 41465, 'filltrades': [TradeType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'tradeid': 1672732808546, 'clientorderid': '41465F1672732808435I0L65', 'price': '16723.1', 'quantity': '52.77', 'commission': '882.477987', 'commissionasset': 'USDT', 'tradetime': 1672732808546, 'tradetype': 'usdt', 'gatetype': 'simulator', 'handletime': 1672732808546}], 'gatetype': 'simulator', 'handletime': 0}
127.0.0.1 - - [03/Jan/2023 16:00:08] "POST / HTTP/1.1" 200 -
2023-01-03 16:00:08,825:INFO:s_rsrs:main.py:346:handleOrderFilled:185271: handleOrderFilled: data=OrderType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'clientorderid': '41465F1672732808435I0L65', 'symbol': 'BTCUSDT', 'gatewayorderid': 1672732808546550, 'quantity': '52.77', 'price': '16723.1', 'stopprice': '0', 'ordertype': '', 'side': 'BUY', 'status': 'FILLED', 'positionside': 'LONG', 'createtime': 1672732808200, 'updatetime': 1672732808546, 'tradetype': 'usdt', 'selfid': 41465, 'filltrades': [TradeType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'tradeid': 1672732808546, 'clientorderid': '41465F1672732808435I0L65', 'price': '16723.1', 'quantity': '52.77', 'commission': '882.477987', 'commissionasset': 'USDT', 'tradetime': 1672732808546, 'tradetype': 'usdt', 'gatetype': 'simulator', 'handletime': 1672732808546}], 'gatetype': 'simulator', 'handletime': 0}


