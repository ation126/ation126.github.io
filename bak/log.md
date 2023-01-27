# 20230127 16:16:02

## /root/FIL/strategy/amihud/log.txt ----- -----

127.0.0.1 - - [27/Jan/2023 16:10:01] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=993672.4896432, self.flagDict['side']='sell', self.tradeCount=2, self.count=17594
self.closeSec=1674806999, self.tradeDate='20230127', self.openTime='160500', self.closeTime='160959', self.symbol='BTCUSDT', self.open=23044.9, self.close=23026.7, self.high=23048.3, self.low=23020.4, self.vol=1003.075, self.amt=23106669.4528 
2023-01-27 16:10:01,488:INFO:amihud:main.py:172:handleKline:200676: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5949  20230127   154500    154959  ...         0.0        0.0       0
5950  20230127   155000    155459  ...         0.0        0.0       0
5951  20230127   155500    155959  ...         0.0        0.0       0
5952  20230127   160000    160459  ...         0.0        0.0       0
5953  20230127   160500    160959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-01-27 16:10:01,489:INFO:amihud:main.py:175:handleKline:200676: self.closeSec=1674806999, self.tradeDate='20230127', self.openTime='160500', self.closeTime='160959',self.symbol='BTCUSDT',self.open=23044.9, self.close=23026.7, self.high=23048.3, self.low=23020.4, self.vol=1003.075, self.amt=23106669.4528, ukdf['pct'].iloc[-1]=-0.00079 , ukdf['amount'].iloc[-1]=23106669.4528, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5953, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '60.176', 'enterprice': '16529.3', 'countrevence': '0', 'unrealprofit': '-391139.18803939872', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '23029.22003522', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1
--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=993672.4896432, self.flagDict['side']='sell', self.tradeCount=2, self.count=17595
self.closeSec=1674807299, self.tradeDate='20230127', self.openTime='161000', self.closeTime='161459', self.symbol='BTCUSDT', self.open=23026.6, self.close=22994.6, self.high=23032.5, self.low=22991.0, self.vol=1289.907, self.amt=29680225.105 
127.0.0.1 - - [27/Jan/2023 16:15:00] "POST / HTTP/1.1" 200 -
2023-01-27 16:15:00,672:INFO:amihud:main.py:172:handleKline:200676: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5950  20230127   155000    155459  ...         0.0        0.0       0
5951  20230127   155500    155959  ...         0.0        0.0       0
5952  20230127   160000    160459  ...         0.0        0.0       0
5953  20230127   160500    160959  ...         0.0        0.0       0
5954  20230127   161000    161459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-01-27 16:15:00,672:INFO:amihud:main.py:175:handleKline:200676: self.closeSec=1674807299, self.tradeDate='20230127', self.openTime='161000', self.closeTime='161459',self.symbol='BTCUSDT',self.open=23026.6, self.close=22994.6, self.high=23032.5, self.low=22991.0, self.vol=1289.907, self.amt=29680225.105, ukdf['pct'].iloc[-1]=-0.001394 , ukdf['amount'].iloc[-1]=29680225.105, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5954, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '60.176', 'enterprice': '16529.3', 'countrevence': '0', 'unrealprofit': '-389204.14652708944', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '22997.06366869', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1


## /root/FIL/strategy/factorcheck/log.txt ----- -----


self.closeSec=1674806999, self.tradeDate='20230127', self.openTime='160500', self.closeTime='160959', self.symbol='BTCUSDT', self.open=23044.9, self.close=23026.7, self.high=23048.3, self.low=23020.4 
2023-01-27 16:10:01,441:INFO:factorcheck2:main.py:126:handleKline:185239: self.closeSec=1674806999, self.tradeDate='20230127', self.openTime='160500', self.closeTime='160959',self.symbol='BTCUSDT',self.open=23044.9, self.close=23026.7, self.high=23048.3, self.low=23020.4   
127.0.0.1 - - [27/Jan/2023 16:10:01] "POST / HTTP/1.1" 200 -
2023-01-27 16:10:01,455:INFO:factorcheck2:main.py:127:handleKline:185239: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1629  20230127   154500    154959  1674805799  ...  23002.3  0.000200   1629    3
1630  20230127   155000    155459  1674806099  ...  23030.3  0.001250   1630    4
1631  20230127   155500    155959  1674806399  ...  23044.0  0.000286   1631    5
1632  20230127   160000    160459  1674806699  ...  23044.0 -0.001006   1632    0
1633  20230127   160500    160959  1674806999  ...  23020.4 -0.000790   1633    1

[5 rows x 11 columns]
2023-01-27 16:10:01,455:INFO:factorcheck2:main.py:128:handleKline:185239: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=317, self.factor=0.5493082872826138, self.count=18161 

self.closeSec=1674807299, self.tradeDate='20230127', self.openTime='161000', self.closeTime='161459', self.symbol='BTCUSDT', self.open=23026.6, self.close=22994.6, self.high=23032.5, self.low=22991.0 
2023-01-27 16:15:00,624:INFO:factorcheck2:main.py:126:handleKline:185239: self.closeSec=1674807299, self.tradeDate='20230127', self.openTime='161000', self.closeTime='161459',self.symbol='BTCUSDT',self.open=23026.6, self.close=22994.6, self.high=23032.5, self.low=22991.0   
127.0.0.1 - - [27/Jan/2023 16:15:00] "POST / HTTP/1.1" 200 -
2023-01-27 16:15:00,656:INFO:factorcheck2:main.py:127:handleKline:185239: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1630  20230127   155000    155459  1674806099  ...  23030.3  0.001250   1630    4
1631  20230127   155500    155959  1674806399  ...  23044.0  0.000286   1631    5
1632  20230127   160000    160459  1674806699  ...  23044.0 -0.001006   1632    0
1633  20230127   160500    160959  1674806999  ...  23020.4 -0.000790   1633    1
1634  20230127   161000    161459  1674807299  ...  22991.0 -0.001394   1634    2

[5 rows x 11 columns]
2023-01-27 16:15:00,656:INFO:factorcheck2:main.py:128:handleKline:185239: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}


## /root/FIL/strategy/logic/log.txt ----- -----

2023-01-27 16:00:17,961:DEBUG:logic:main.py:463:getModel:885513: df_s.iloc[-5:,:] :
          date closeTime     open  ...    alpha58   alpha67   alpha72
5786  20230127    132959  22790.1  ...  52.500000  0.483218  0.626358
5787  20230127    135959  22827.0  ...  52.500000  0.517094  0.604197
5788  20230127    142959  23028.7  ...  52.500000  0.517798  0.583109
5789  20230127    145959  23033.2  ...  52.083333  0.510790  0.567159
5790  20230127    152959  22992.5  ...  52.083333  0.508335  0.553577

[5 rows x 33 columns]
0.514760147601476
acc is : 0.514760147601476
2023-01-27 16:00:18,047:INFO:logic:main.py:468:getModel:885513: df_pred.iloc[-5:,:] :
     pred    prob_0    prob_1  actual  ...       nav  sign   cost_        bm
537     0  0.529480  0.470520       1  ...  0.941537  -1.0  0.0000  1.097577
538     0  0.577508  0.422492       1  ...  0.940211   1.0 -0.0016  1.097787
539     0  0.545827  0.454173       0  ...  0.938554   1.0  0.0000  1.095852
540     0  0.529954  0.470046       0  ...  0.937974   1.0  0.0000  1.095175
541     0  0.535614  0.464386       1  ...  0.941640   1.0  0.0000  1.099455

[5 rows x 10 columns]
2023-01-27 16:00:18,058:INFO:logic:main.py:478:getModel:885513: df_panel.iloc[-5:,:] :
    pred    prob_0    prob_1  actual  ...       nav  sign   cost_        bm
45     0  0.527960  0.472040       1  ...  0.941537  -1.0  0.0000  1.100425
46     0  0.577316  0.422684       1  ...  0.940211   1.0 -0.0016  1.102648
47     0  0.545765  0.454235       0  ...  0.938554   1.0  0.0000  1.101031
48     0  0.530704  0.469296       0  ...  0.937974   1.0  0.0000  1.104036
49     0  0.535614  0.464386       1  ...  0.941640   1.0  0.0000  1.099455

[5 rows x 10 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '30.8', 'enterprice': '23035.8', 'countrevence': '0', 'unrealprofit': '1287.44', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '23077.6', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}


## /root/FIL/strategy/modifiedmom/log.txt ----- -----

526  20230127   154000    154959  1674805799  22997.6  23032.7  0.001526
2023-01-27 15:50:00,759:INFO:modifiedmom:main.py:146:handleKline:185213: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True}

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=9079 

self.closeSec=1674806399, self.tradeDate='20230127', self.openTime='155000', self.closeTime='155959', self.symbol='BTCUSDT', self.open='23032.7', self.close='23068.1'
127.0.0.1 - - [27/Jan/2023 16:00:01] "POST / HTTP/1.1" 200 -
2023-01-27 16:00:01,961:INFO:modifiedmom:main.py:144:handleKline:185213: self.closeSec=1674806399, self.tradeDate='20230127', self.openTime='155000', self.closeTime='155959',self.symbol='BTCUSDT',self.open='23032.7', self.close='23068.1'
2023-01-27 16:00:01,988:INFO:modifiedmom:main.py:145:handleKline:185213: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
523  20230127   151000    151959  1674803999  22960.4  22941.9 -0.000827
524  20230127   152000    152959  1674804599  22942.5  22978.3  0.001587
525  20230127   153000    153959  1674805199  22978.5  22997.6  0.000840
526  20230127   154000    154959  1674805799  22997.6  23032.7  0.001526
527  20230127   155000    155959  1674806399  23032.7  23068.1  0.001537
2023-01-27 16:00:01,988:INFO:modifiedmom:main.py:146:handleKline:185213: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True}
127.0.0.1 - - [27/Jan/2023 16:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=9080 

self.closeSec=1674806999, self.tradeDate='20230127', self.openTime='160000', self.closeTime='160959', self.symbol='BTCUSDT', self.open='23068.1', self.close='23026.7'
2023-01-27 16:10:01,551:INFO:modifiedmom:main.py:144:handleKline:185213: self.closeSec=1674806999, self.tradeDate='20230127', self.openTime='160000', self.closeTime='160959',self.symbol='BTCUSDT',self.open='23068.1', self.close='23026.7'
2023-01-27 16:10:01,572:INFO:modifiedmom:main.py:145:handleKline:185213: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
524  20230127   152000    152959  1674804599  22942.5  22978.3  0.001587
525  20230127   153000    153959  1674805199  22978.5  22997.6  0.000840
526  20230127   154000    154959  1674805799  22997.6  23032.7  0.001526
527  20230127   155000    155959  1674806399  23032.7  23068.1  0.001537
528  20230127   160000    160959  1674806999  23068.1  23026.7 -0.001795
2023-01-27 16:10:01,572:INFO:modifiedmom:main.py:146:handleKline:185213: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True}


## /root/FIL/strategy/pyemd/log.txt ----- -----

17518  20230127   154000    154959  1674805799  22997.6  23032.7
2023-01-27 15:50:00,767:INFO:pyemd2:main.py:127:handleKline:185189: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=9080 

self.closeSec=1674806399, self.tradeDate='20230127', self.openTime='155000', self.closeTime='155959', self.symbol='BTCUSDT', self.open='23032.7', self.close='23068.1'
127.0.0.1 - - [27/Jan/2023 16:00:01] "POST / HTTP/1.1" 200 -
2023-01-27 16:00:01,977:INFO:pyemd2:main.py:125:handleKline:185189: self.closeSec=1674806399, self.tradeDate='20230127', self.openTime='155000', self.closeTime='155959',self.symbol='BTCUSDT',self.open='23032.7', self.close='23068.1'
2023-01-27 16:00:01,997:INFO:pyemd2:main.py:126:handleKline:185189: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17515  20230127   151000    151959  1674803999  22960.4  22941.9
17516  20230127   152000    152959  1674804599  22942.5  22978.3
17517  20230127   153000    153959  1674805199  22978.5  22997.6
17518  20230127   154000    154959  1674805799  22997.6  23032.7
17519  20230127   155000    155959  1674806399  23032.7  23068.1
2023-01-27 16:00:01,997:INFO:pyemd2:main.py:127:handleKline:185189: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}
127.0.0.1 - - [27/Jan/2023 16:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=9081 

self.closeSec=1674806999, self.tradeDate='20230127', self.openTime='160000', self.closeTime='160959', self.symbol='BTCUSDT', self.open='23068.1', self.close='23026.7'
2023-01-27 16:10:01,531:INFO:pyemd2:main.py:125:handleKline:185189: self.closeSec=1674806999, self.tradeDate='20230127', self.openTime='160000', self.closeTime='160959',self.symbol='BTCUSDT',self.open='23068.1', self.close='23026.7'
2023-01-27 16:10:01,547:INFO:pyemd2:main.py:126:handleKline:185189: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17516  20230127   152000    152959  1674804599  22942.5  22978.3
17517  20230127   153000    153959  1674805199  22978.5  22997.6
17518  20230127   154000    154959  1674805799  22997.6  23032.7
17519  20230127   155000    155959  1674806399  23032.7  23068.1
17520  20230127   160000    160959  1674806999  23068.1  23026.7
2023-01-27 16:10:01,547:INFO:pyemd2:main.py:127:handleKline:185189: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}


## /root/FIL/strategy/similarity/log.txt ----- -----

12190  20230127   154000    154959  1674805799  22997.6  23032.7
2023-01-27 15:50:00,772:INFO:testStrategy:main.py:103:handleKline:185174: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': True, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}
127.0.0.1 - - [27/Jan/2023 16:00:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=9080 

self.closeSec=1674806399, self.tradeDate='20230127', self.openTime='155000', self.closeTime='155959', self.symbol='BTCUSDT', self.open='23032.7', self.close='23068.1'
2023-01-27 16:00:01,949:INFO:testStrategy:main.py:101:handleKline:185174: self.closeSec=1674806399, self.tradeDate='20230127', self.openTime='155000', self.closeTime='155959',self.symbol='BTCUSDT',self.open='23032.7', self.close='23068.1'
2023-01-27 16:00:01,984:INFO:testStrategy:main.py:102:handleKline:185174: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12187  20230127   151000    151959  1674803999  22960.4  22941.9
12188  20230127   152000    152959  1674804599  22942.5  22978.3
12189  20230127   153000    153959  1674805199  22978.5  22997.6
12190  20230127   154000    154959  1674805799  22997.6  23032.7
12191  20230127   155000    155959  1674806399  23032.7  23068.1
2023-01-27 16:00:01,985:INFO:testStrategy:main.py:103:handleKline:185174: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': True, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}
127.0.0.1 - - [27/Jan/2023 16:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=9081 

self.closeSec=1674806999, self.tradeDate='20230127', self.openTime='160000', self.closeTime='160959', self.symbol='BTCUSDT', self.open='23068.1', self.close='23026.7'
2023-01-27 16:10:01,525:INFO:testStrategy:main.py:101:handleKline:185174: self.closeSec=1674806999, self.tradeDate='20230127', self.openTime='160000', self.closeTime='160959',self.symbol='BTCUSDT',self.open='23068.1', self.close='23026.7'
2023-01-27 16:10:01,538:INFO:testStrategy:main.py:102:handleKline:185174: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12188  20230127   152000    152959  1674804599  22942.5  22978.3
12189  20230127   153000    153959  1674805199  22978.5  22997.6
12190  20230127   154000    154959  1674805799  22997.6  23032.7
12191  20230127   155000    155959  1674806399  23032.7  23068.1
12192  20230127   160000    160959  1674806999  23068.1  23026.7
2023-01-27 16:10:01,538:INFO:testStrategy:main.py:103:handleKline:185174: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': True, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}


## /root/FIL/strategy/sr_min/log.txt ----- -----

127.0.0.1 - - [27/Jan/2023 16:10:01] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=0, self.total=1000000.0, self.flagDict['side']='', self.tradeCount=0, self.count=13592
self.closeSec=1674806999, self.tradeDate='20230127', self.openTime='160500', self.closeTime='160959', self.symbol='BTCUSDT', self.open=23044.9, self.close=23026.7, self.high=23048.3, self.low=23020.4, self.vol=1003.075, self.amt=23106669.4528 
2023-01-27 16:10:01,465:INFO:sr_min:main.py:172:handleKline:449472: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5949  20230127   154500    154959  ...         0.0        0.0       0
5950  20230127   155000    155459  ...         0.0        0.0       0
5951  20230127   155500    155959  ...         0.0        0.0       0
5952  20230127   160000    160459  ...         0.0        0.0       0
5953  20230127   160500    160959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-01-27 16:10:01,465:INFO:sr_min:main.py:175:handleKline:449472: self.closeSec=1674806999, self.tradeDate='20230127', self.openTime='160500', self.closeTime='160959',self.symbol='BTCUSDT',self.open=23044.9, self.close=23026.7, self.high=23048.3, self.low=23020.4, self.vol=1003.075, self.amt=23106669.4528, ukdf['pct'].iloc[-1]=-0.00079 , ukdf['amount'].iloc[-1]=23106669.4528, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5953, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': []}
type(curSign)=<class 'int'>, curSign=0, self.sign=0
127.0.0.1 - - [27/Jan/2023 16:15:00] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=0, self.total=1000000.0, self.flagDict['side']='', self.tradeCount=0, self.count=13593
self.closeSec=1674807299, self.tradeDate='20230127', self.openTime='161000', self.closeTime='161459', self.symbol='BTCUSDT', self.open=23026.6, self.close=22994.6, self.high=23032.5, self.low=22991.0, self.vol=1289.907, self.amt=29680225.105 
2023-01-27 16:15:00,671:INFO:sr_min:main.py:172:handleKline:449472: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5950  20230127   155000    155459  ...         0.0        0.0       0
5951  20230127   155500    155959  ...         0.0        0.0       0
5952  20230127   160000    160459  ...         0.0        0.0       0
5953  20230127   160500    160959  ...         0.0        0.0       0
5954  20230127   161000    161459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-01-27 16:15:00,671:INFO:sr_min:main.py:175:handleKline:449472: self.closeSec=1674807299, self.tradeDate='20230127', self.openTime='161000', self.closeTime='161459',self.symbol='BTCUSDT',self.open=23026.6, self.close=22994.6, self.high=23032.5, self.low=22991.0, self.vol=1289.907, self.amt=29680225.105, ukdf['pct'].iloc[-1]=-0.001394 , ukdf['amount'].iloc[-1]=29680225.105, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5954, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': []}
type(curSign)=<class 'int'>, curSign=0, self.sign=0


## /root/FIL/strategy/s_rsrs/log.txt ----- -----

721  20230127   040000    075959  1674777599  ...    721  0.194076 -1.155881    -1.0
722  20230127   080000    115959  1674791999  ...    722  0.160359 -1.210508    -1.0

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '41.738', 'enterprice': '22927.7', 'countrevence': '0', 'unrealprofit': '6907.639', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '22762.2', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-1, self.sign=-1
127.0.0.1 - - [27/Jan/2023 16:00:01] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='s_rsrs', self.symbol='BTCUSDT', interval='4h', intervalSec=14400, wid=25, thd=0.6, self.sign=-1, self.total=955999.3862573999, self.flagDict['side']='sell', self.tradeCount=15, self.count=378
self.closeSec=1674806399, self.tradeDate='20230127', self.openTime='120000', self.closeTime='155959', self.symbol='BTCUSDT', self.open=22762.2, self.close=23068.1, self.high=23098.0, self.low=22750.0, self.vol=58836.674, self.amt=1350516048.56213 
2023-01-27 16:00:01,744:INFO:s_rsrs:main.py:141:handleKline:185271: self.closeSec=1674806399, self.tradeDate='20230127', self.openTime='120000', self.closeTime='155959',self.symbol='BTCUSDT',self.open=22762.2, self.close=23068.1, self.high=23098.0, self.low=22750.0, self.vol=58836.674, self.amt=1350516048.56213 
2023-01-27 16:00:01,771:INFO:s_rsrs:main.py:142:handleKline:185271: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime  ...         vol           amt       pct
719  20230126   200000    235959  ...  155447.749  3.585153e+09 -0.001605
720  20230127   000000    035959  ...   64169.464  1.475425e+09  0.005007
721  20230127   040000    075959  ...   42267.061  9.743714e+08 -0.002667
722  20230127   080000    115959  ...   86055.897  1.959346e+09 -0.010421
723  20230127   120000    155959  ...   58836.674  1.350516e+09  0.013439

[5 rows x 11 columns]
2023-01-27 16:00:02,927:INFO:s_rsrs:main.py:151:handleKline:185271: df_s.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec  ...  index      beta    zscore  signal
719  20230126   200000    235959  1674748799  ...    719  0.205563 -1.183238    -1.0
720  20230127   000000    035959  1674763199  ...    720  0.201797 -1.164617    -1.0
721  20230127   040000    075959  1674777599  ...    721  0.194076 -1.155881    -1.0
722  20230127   080000    115959  1674791999  ...    722  0.160359 -1.210508    -1.0
723  20230127   120000    155959  1674806399  ...    723  0.157918 -1.190554    -1.0

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '41.738', 'enterprice': '22927.7', 'countrevence': '0', 'unrealprofit': '-5864.189', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '23068.2', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-1, self.sign=-1


