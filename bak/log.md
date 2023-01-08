# 20230108 16:16:01

## /root/FIL/strategy/amihud/log.txt ----- -----

127.0.0.1 - - [08/Jan/2023 16:10:01] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=993672.4896432, self.flagDict['side']='sell', self.tradeCount=2, self.count=12122
self.closeSec=1673165399, self.tradeDate='20230108', self.openTime='160500', self.closeTime='160959', self.symbol='BTCUSDT', self.open=16946.8, self.close=16948.9, self.high=16949.9, self.low=16946.7, self.vol=404.242, self.amt=6851266.8102 
2023-01-08 16:10:01,514:INFO:amihud:main.py:172:handleKline:200676: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5949  20230108   154500    154959  ...         0.0        0.0       0
5950  20230108   155000    155459  ...         0.0        0.0       0
5951  20230108   155500    155959  ...         0.0        0.0       0
5952  20230108   160000    160459  ...         0.0        0.0       0
5953  20230108   160500    160959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-01-08 16:10:01,514:INFO:amihud:main.py:175:handleKline:200676: self.closeSec=1673165399, self.tradeDate='20230108', self.openTime='160500', self.closeTime='160959',self.symbol='BTCUSDT',self.open=16946.8, self.close=16948.9, self.high=16949.9, self.low=16946.7, self.vol=404.242, self.amt=6851266.8102, ukdf['pct'].iloc[-1]=0.000124 , ukdf['amount'].iloc[-1]=6851266.8102, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5953, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '60.176', 'enterprice': '16529.3', 'countrevence': '0', 'unrealprofit': '-25249.8496', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '16948.9', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1
127.0.0.1 - - [08/Jan/2023 16:15:00] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=993672.4896432, self.flagDict['side']='sell', self.tradeCount=2, self.count=12123
self.closeSec=1673165699, self.tradeDate='20230108', self.openTime='161000', self.closeTime='161459', self.symbol='BTCUSDT', self.open=16948.9, self.close=16945.5, self.high=16948.9, self.low=16945.4, self.vol=301.074, self.amt=5102421.7931 
2023-01-08 16:15:00,647:INFO:amihud:main.py:172:handleKline:200676: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5950  20230108   155000    155459  ...         0.0        0.0       0
5951  20230108   155500    155959  ...         0.0        0.0       0
5952  20230108   160000    160459  ...         0.0        0.0       0
5953  20230108   160500    160959  ...         0.0        0.0       0
5954  20230108   161000    161459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-01-08 16:15:00,647:INFO:amihud:main.py:175:handleKline:200676: self.closeSec=1673165699, self.tradeDate='20230108', self.openTime='161000', self.closeTime='161459',self.symbol='BTCUSDT',self.open=16948.9, self.close=16945.5, self.high=16948.9, self.low=16945.4, self.vol=301.074, self.amt=5102421.7931, ukdf['pct'].iloc[-1]=-0.000201 , ukdf['amount'].iloc[-1]=5102421.7931, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5954, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '60.176', 'enterprice': '16529.3', 'countrevence': '0', 'unrealprofit': '-25039.2336', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '16945.4', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1


## /root/FIL/strategy/factorcheck/log.txt ----- -----

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=31, self.factor=0.33547837808582875, self.count=12688 

self.closeSec=1673165399, self.tradeDate='20230108', self.openTime='160500', self.closeTime='160959', self.symbol='BTCUSDT', self.open=16946.8, self.close=16948.9, self.high=16949.9, self.low=16946.7 
2023-01-08 16:10:01,449:INFO:factorcheck2:main.py:126:handleKline:185239: self.closeSec=1673165399, self.tradeDate='20230108', self.openTime='160500', self.closeTime='160959',self.symbol='BTCUSDT',self.open=16946.8, self.close=16948.9, self.high=16949.9, self.low=16946.7   
2023-01-08 16:10:01,580:INFO:factorcheck2:main.py:127:handleKline:185239: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1629  20230108   154500    154959  1673164199  ...  16940.2 -0.000248   1629    3
1630  20230108   155000    155459  1673164499  ...  16941.9  0.000212   1630    4
1631  20230108   155500    155959  1673164799  ...  16942.3 -0.000006   1631    5
1632  20230108   160000    160459  1673165099  ...  16945.4  0.000077   1632    0
1633  20230108   160500    160959  1673165399  ...  16946.7  0.000124   1633    1

[5 rows x 11 columns]
2023-01-08 16:10:01,582:INFO:factorcheck2:main.py:128:handleKline:185239: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=31, self.factor=0.33547837808582875, self.count=12689 

self.closeSec=1673165699, self.tradeDate='20230108', self.openTime='161000', self.closeTime='161459', self.symbol='BTCUSDT', self.open=16948.9, self.close=16945.5, self.high=16948.9, self.low=16945.4 
2023-01-08 16:15:00,526:INFO:factorcheck2:main.py:126:handleKline:185239: self.closeSec=1673165699, self.tradeDate='20230108', self.openTime='161000', self.closeTime='161459',self.symbol='BTCUSDT',self.open=16948.9, self.close=16945.5, self.high=16948.9, self.low=16945.4   
127.0.0.1 - - [08/Jan/2023 16:15:00] "POST / HTTP/1.1" 200 -
2023-01-08 16:15:00,590:INFO:factorcheck2:main.py:127:handleKline:185239: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1630  20230108   155000    155459  1673164499  ...  16941.9  0.000212   1630    4
1631  20230108   155500    155959  1673164799  ...  16942.3 -0.000006   1631    5
1632  20230108   160000    160459  1673165099  ...  16945.4  0.000077   1632    0
1633  20230108   160500    160959  1673165399  ...  16946.7  0.000124   1633    1
1634  20230108   161000    161459  1673165699  ...  16945.4 -0.000201   1634    2

[5 rows x 11 columns]
2023-01-08 16:15:00,591:INFO:factorcheck2:main.py:128:handleKline:185239: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}


## /root/FIL/strategy/logic/log.txt ----- -----

2023-01-08 16:00:16,967:DEBUG:logic:main.py:456:getModel:726423: df_s.iloc[-5:,:] :
          date closeTime     open  ...    alpha58   alpha67   alpha72
5786  20230108    132959  16930.8  ...  51.666667  0.544835  0.427294
5787  20230108    135959  16935.1  ...  51.666667  0.546997  0.415203
5788  20230108    142959  16937.2  ...  51.250000  0.538178  0.413539
5789  20230108    145959  16930.0  ...  51.666667  0.554389  0.390713
5790  20230108    152959  16945.8  ...  52.083333  0.554491  0.369272

[5 rows x 33 columns]
0.5498154981549815
acc is : 0.5498154981549815
2023-01-08 16:00:17,083:INFO:logic:main.py:461:getModel:726423: df_pred.iloc[-5:,:] :
     pred    prob_0    prob_1  actual  ...  nav  sign   cost_        bm
537     0  0.502884  0.497116       1  ...  NaN   NaN -0.0016  1.015377
538     0  0.502554  0.497446       0  ...  NaN   NaN -0.0016  1.014951
539     1  0.498218  0.501782       1  ...  NaN   NaN -0.0016  1.015893
540     0  0.505839  0.494161       1  ...  NaN   NaN -0.0016  1.015899
541     0  0.502927  0.497073       0  ...  NaN   NaN -0.0016  1.015875

[5 rows x 10 columns]
2023-01-08 16:00:17,097:INFO:logic:main.py:471:getModel:726423: df_panel.iloc[-5:,:] :
    pred    prob_0    prob_1  actual  ...  nav  sign   cost_        bm
45     0  0.502470  0.497530       1  ...  NaN   NaN -0.0016  1.015298
46     0  0.501861  0.498139       0  ...  NaN   NaN -0.0016  1.013178
47     1  0.497807  0.502193       1  ...  NaN   NaN -0.0016  1.014828
48     0  0.505626  0.494374       1  ...  NaN   NaN -0.0016  1.015047
49     0  0.502927  0.497073       0  ...  NaN   NaN -0.0016  1.015875

[5 rows x 10 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '42.528', 'enterprice': '16701.5', 'countrevence': '0', 'unrealprofit': '10392.32484067776', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '16945.86429742', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}


## /root/FIL/strategy/modifiedmom/log.txt ----- -----

526  20230108   154000    154959  1673164199  16947.2    16942 -0.000313
2023-01-08 15:50:00,554:INFO:modifiedmom:main.py:146:handleKline:185213: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True}

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=6343 

self.closeSec=1673164799, self.tradeDate='20230108', self.openTime='155000', self.closeTime='155959', self.symbol='BTCUSDT', self.open='16941.9', self.close='16945.5'
2023-01-08 16:00:01,094:INFO:modifiedmom:main.py:144:handleKline:185213: self.closeSec=1673164799, self.tradeDate='20230108', self.openTime='155000', self.closeTime='155959',self.symbol='BTCUSDT',self.open='16941.9', self.close='16945.5'
127.0.0.1 - - [08/Jan/2023 16:00:01] "POST / HTTP/1.1" 200 -
2023-01-08 16:00:01,128:INFO:modifiedmom:main.py:145:handleKline:185213: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
523  20230108   151000    151959  1673162399  16940.6  16938.8 -0.000112
524  20230108   152000    152959  1673162999  16938.8  16945.9  0.000419
525  20230108   153000    153959  1673163599  16945.9  16947.3  0.000083
526  20230108   154000    154959  1673164199  16947.2    16942 -0.000313
527  20230108   155000    155959  1673164799  16941.9  16945.5  0.000207
2023-01-08 16:00:01,128:INFO:modifiedmom:main.py:146:handleKline:185213: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True}
127.0.0.1 - - [08/Jan/2023 16:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=6344 

self.closeSec=1673165399, self.tradeDate='20230108', self.openTime='160000', self.closeTime='160959', self.symbol='BTCUSDT', self.open='16945.5', self.close='16948.9'
2023-01-08 16:10:01,521:INFO:modifiedmom:main.py:144:handleKline:185213: self.closeSec=1673165399, self.tradeDate='20230108', self.openTime='160000', self.closeTime='160959',self.symbol='BTCUSDT',self.open='16945.5', self.close='16948.9'
2023-01-08 16:10:01,605:INFO:modifiedmom:main.py:145:handleKline:185213: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
524  20230108   152000    152959  1673162999  16938.8  16945.9  0.000419
525  20230108   153000    153959  1673163599  16945.9  16947.3  0.000083
526  20230108   154000    154959  1673164199  16947.2    16942 -0.000313
527  20230108   155000    155959  1673164799  16941.9  16945.5  0.000207
528  20230108   160000    160959  1673165399  16945.5  16948.9  0.000201
2023-01-08 16:10:01,605:INFO:modifiedmom:main.py:146:handleKline:185213: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True}


## /root/FIL/strategy/pyemd/log.txt ----- -----

17518  20230108   154000    154959  1673164199  16947.2    16942
2023-01-08 15:50:00,613:INFO:pyemd2:main.py:127:handleKline:185189: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=6344 

self.closeSec=1673164799, self.tradeDate='20230108', self.openTime='155000', self.closeTime='155959', self.symbol='BTCUSDT', self.open='16941.9', self.close='16945.5'
127.0.0.1 - - [08/Jan/2023 16:00:01] "POST / HTTP/1.1" 200 -
2023-01-08 16:00:01,112:INFO:pyemd2:main.py:125:handleKline:185189: self.closeSec=1673164799, self.tradeDate='20230108', self.openTime='155000', self.closeTime='155959',self.symbol='BTCUSDT',self.open='16941.9', self.close='16945.5'
2023-01-08 16:00:01,211:INFO:pyemd2:main.py:126:handleKline:185189: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17515  20230108   151000    151959  1673162399  16940.6  16938.8
17516  20230108   152000    152959  1673162999  16938.8  16945.9
17517  20230108   153000    153959  1673163599  16945.9  16947.3
17518  20230108   154000    154959  1673164199  16947.2    16942
17519  20230108   155000    155959  1673164799  16941.9  16945.5
2023-01-08 16:00:01,211:INFO:pyemd2:main.py:127:handleKline:185189: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=6345 

self.closeSec=1673165399, self.tradeDate='20230108', self.openTime='160000', self.closeTime='160959', self.symbol='BTCUSDT', self.open='16945.5', self.close='16948.9'
2023-01-08 16:10:01,552:INFO:pyemd2:main.py:125:handleKline:185189: self.closeSec=1673165399, self.tradeDate='20230108', self.openTime='160000', self.closeTime='160959',self.symbol='BTCUSDT',self.open='16945.5', self.close='16948.9'
127.0.0.1 - - [08/Jan/2023 16:10:01] "POST / HTTP/1.1" 200 -
2023-01-08 16:10:01,581:INFO:pyemd2:main.py:126:handleKline:185189: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17516  20230108   152000    152959  1673162999  16938.8  16945.9
17517  20230108   153000    153959  1673163599  16945.9  16947.3
17518  20230108   154000    154959  1673164199  16947.2    16942
17519  20230108   155000    155959  1673164799  16941.9  16945.5
17520  20230108   160000    160959  1673165399  16945.5  16948.9
2023-01-08 16:10:01,581:INFO:pyemd2:main.py:127:handleKline:185189: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}


## /root/FIL/strategy/similarity/log.txt ----- -----

12190  20230108   154000    154959  1673164199  16947.2    16942
2023-01-08 15:50:00,618:INFO:testStrategy:main.py:103:handleKline:185174: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': True, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=6344 

self.closeSec=1673164799, self.tradeDate='20230108', self.openTime='155000', self.closeTime='155959', self.symbol='BTCUSDT', self.open='16941.9', self.close='16945.5'
127.0.0.1 - - [08/Jan/2023 16:00:01] "POST / HTTP/1.1" 200 -
2023-01-08 16:00:01,102:INFO:testStrategy:main.py:101:handleKline:185174: self.closeSec=1673164799, self.tradeDate='20230108', self.openTime='155000', self.closeTime='155959',self.symbol='BTCUSDT',self.open='16941.9', self.close='16945.5'
2023-01-08 16:00:01,191:INFO:testStrategy:main.py:102:handleKline:185174: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12187  20230108   151000    151959  1673162399  16940.6  16938.8
12188  20230108   152000    152959  1673162999  16938.8  16945.9
12189  20230108   153000    153959  1673163599  16945.9  16947.3
12190  20230108   154000    154959  1673164199  16947.2    16942
12191  20230108   155000    155959  1673164799  16941.9  16945.5
2023-01-08 16:00:01,193:INFO:testStrategy:main.py:103:handleKline:185174: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': True, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=6345 

self.closeSec=1673165399, self.tradeDate='20230108', self.openTime='160000', self.closeTime='160959', self.symbol='BTCUSDT', self.open='16945.5', self.close='16948.9'
127.0.0.1 - - [08/Jan/2023 16:10:01] "POST / HTTP/1.1" 200 -
2023-01-08 16:10:01,569:INFO:testStrategy:main.py:101:handleKline:185174: self.closeSec=1673165399, self.tradeDate='20230108', self.openTime='160000', self.closeTime='160959',self.symbol='BTCUSDT',self.open='16945.5', self.close='16948.9'
2023-01-08 16:10:01,617:INFO:testStrategy:main.py:102:handleKline:185174: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12188  20230108   152000    152959  1673162999  16938.8  16945.9
12189  20230108   153000    153959  1673163599  16945.9  16947.3
12190  20230108   154000    154959  1673164199  16947.2    16942
12191  20230108   155000    155959  1673164799  16941.9  16945.5
12192  20230108   160000    160959  1673165399  16945.5  16948.9
2023-01-08 16:10:01,617:INFO:testStrategy:main.py:103:handleKline:185174: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': True, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}


## /root/FIL/strategy/sr_min/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=0, self.total=1000000.0, self.flagDict['side']='', self.tradeCount=0, self.count=8120
self.closeSec=1673165399, self.tradeDate='20230108', self.openTime='160500', self.closeTime='160959', self.symbol='BTCUSDT', self.open=16946.8, self.close=16948.9, self.high=16949.9, self.low=16946.7, self.vol=404.242, self.amt=6851266.8102 
127.0.0.1 - - [08/Jan/2023 16:10:01] "POST / HTTP/1.1" 200 -
2023-01-08 16:10:01,621:INFO:sr_min:main.py:172:handleKline:449472: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5949  20230108   154500    154959  ...         0.0        0.0       0
5950  20230108   155000    155459  ...         0.0        0.0       0
5951  20230108   155500    155959  ...         0.0        0.0       0
5952  20230108   160000    160459  ...         0.0        0.0       0
5953  20230108   160500    160959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-01-08 16:10:01,621:INFO:sr_min:main.py:175:handleKline:449472: self.closeSec=1673165399, self.tradeDate='20230108', self.openTime='160500', self.closeTime='160959',self.symbol='BTCUSDT',self.open=16946.8, self.close=16948.9, self.high=16949.9, self.low=16946.7, self.vol=404.242, self.amt=6851266.8102, ukdf['pct'].iloc[-1]=0.000124 , ukdf['amount'].iloc[-1]=6851266.8102, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5953, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': []}
type(curSign)=<class 'int'>, curSign=0, self.sign=0
127.0.0.1 - - [08/Jan/2023 16:15:00] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=0, self.total=1000000.0, self.flagDict['side']='', self.tradeCount=0, self.count=8121
self.closeSec=1673165699, self.tradeDate='20230108', self.openTime='161000', self.closeTime='161459', self.symbol='BTCUSDT', self.open=16948.9, self.close=16945.5, self.high=16948.9, self.low=16945.4, self.vol=301.074, self.amt=5102421.7931 
2023-01-08 16:15:00,615:INFO:sr_min:main.py:172:handleKline:449472: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5950  20230108   155000    155459  ...         0.0        0.0       0
5951  20230108   155500    155959  ...         0.0        0.0       0
5952  20230108   160000    160459  ...         0.0        0.0       0
5953  20230108   160500    160959  ...         0.0        0.0       0
5954  20230108   161000    161459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-01-08 16:15:00,615:INFO:sr_min:main.py:175:handleKline:449472: self.closeSec=1673165699, self.tradeDate='20230108', self.openTime='161000', self.closeTime='161459',self.symbol='BTCUSDT',self.open=16948.9, self.close=16945.5, self.high=16948.9, self.low=16945.4, self.vol=301.074, self.amt=5102421.7931, ukdf['pct'].iloc[-1]=-0.000201 , ukdf['amount'].iloc[-1]=5102421.7931, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5954, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': []}
type(curSign)=<class 'int'>, curSign=0, self.sign=0


## /root/FIL/strategy/s_rsrs/log.txt ----- -----

2023-01-08 12:00:07,803:INFO:s_rsrs:main.py:343:handleOrderNew:185271: handleOrderNew: data=OrderType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'clientorderid': '41490F1673150402537I0L65', 'symbol': 'BTCUSDT', 'gatewayorderid': 1673150402630105, 'quantity': '52.77', 'price': '16938.9', 'stopprice': '0', 'ordertype': '', 'side': 'SELL', 'status': 'FILLED', 'positionside': 'SHORT', 'createtime': 1673150402251, 'updatetime': 1673150402630, 'tradetype': 'usdt', 'selfid': 41490, 'filltrades': [TradeType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'tradeid': 1673150402630, 'clientorderid': '41490F1673150402537I0L65', 'price': '16938.9', 'quantity': '52.77', 'commission': '893.865753', 'commissionasset': 'USDT', 'tradetime': 1673150402630, 'tradetype': 'usdt', 'gatetype': 'simulator', 'handletime': 1673150402630}], 'gatetype': 'simulator', 'handletime': 0}
2023-01-08 12:00:07,804:INFO:s_rsrs:main.py:346:handleOrderFilled:185271: handleOrderFilled: data=OrderType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'clientorderid': '41490F1673150402537I0L65', 'symbol': 'BTCUSDT', 'gatewayorderid': 1673150402630105, 'quantity': '52.77', 'price': '16938.9', 'stopprice': '0', 'ordertype': '', 'side': 'SELL', 'status': 'FILLED', 'positionside': 'SHORT', 'createtime': 1673150402251, 'updatetime': 1673150402630, 'tradetype': 'usdt', 'selfid': 41490, 'filltrades': [TradeType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'tradeid': 1673150402630, 'clientorderid': '41490F1673150402537I0L65', 'price': '16938.9', 'quantity': '52.77', 'commission': '893.865753', 'commissionasset': 'USDT', 'tradetime': 1673150402630, 'tradetype': 'usdt', 'gatetype': 'simulator', 'handletime': 1673150402630}], 'gatetype': 'simulator', 'handletime': 0}
127.0.0.1 - - [08/Jan/2023 12:00:07] "POST / HTTP/1.1" 200 -
2023-01-08 12:00:07,931:INFO:s_rsrs:main.py:343:handleOrderNew:185271: handleOrderNew: data=OrderType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'clientorderid': '41491F1673150407781I0L65', 'symbol': 'BTCUSDT', 'gatewayorderid': 1673150407890859, 'quantity': '52.715', 'price': '16938.9', 'stopprice': '0', 'ordertype': '', 'side': 'SELL', 'status': 'FILLED', 'positionside': 'SHORT', 'createtime': 1673150407622, 'updatetime': 1673150407890, 'tradetype': 'usdt', 'selfid': 41491, 'filltrades': [TradeType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'tradeid': 1673150407890, 'clientorderid': '41491F1673150407781I0L65', 'price': '16938.9', 'quantity': '52.715', 'commission': '892.9341135', 'commissionasset': 'USDT', 'tradetime': 1673150407890, 'tradetype': 'usdt', 'gatetype': 'simulator', 'handletime': 1673150407890}], 'gatetype': 'simulator', 'handletime': 0}
2023-01-08 12:00:08,060:INFO:s_rsrs:main.py:346:handleOrderFilled:185271: handleOrderFilled: data=OrderType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'clientorderid': '41491F1673150407781I0L65', 'symbol': 'BTCUSDT', 'gatewayorderid': 1673150407890859, 'quantity': '52.715', 'price': '16938.9', 'stopprice': '0', 'ordertype': '', 'side': 'SELL', 'status': 'FILLED', 'positionside': 'SHORT', 'createtime': 1673150407622, 'updatetime': 1673150407890, 'tradetype': 'usdt', 'selfid': 41491, 'filltrades': [TradeType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'tradeid': 1673150407890, 'clientorderid': '41491F1673150407781I0L65', 'price': '16938.9', 'quantity': '52.715', 'commission': '892.9341135', 'commissionasset': 'USDT', 'tradetime': 1673150407890, 'tradetype': 'usdt', 'gatetype': 'simulator', 'handletime': 1673150407890}], 'gatetype': 'simulator', 'handletime': 0}
127.0.0.1 - - [08/Jan/2023 12:00:08] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [08/Jan/2023 16:00:00] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='s_rsrs', self.symbol='BTCUSDT', interval='4h', intervalSec=14400, wid=25, thd=0.6, self.sign=-1, self.total=892041.1793865, self.flagDict['side']='sell', self.tradeCount=11, self.count=264
self.closeSec=1673164799, self.tradeDate='20230108', self.openTime='120000', self.closeTime='155959', self.symbol='BTCUSDT', self.open=16938.9, self.close=16945.5, self.high=16947.5, self.low=16927.5, self.vol=7997.895, self.amt=135470691.2096 
2023-01-08 16:00:00,975:INFO:s_rsrs:main.py:141:handleKline:185271: self.closeSec=1673164799, self.tradeDate='20230108', self.openTime='120000', self.closeTime='155959',self.symbol='BTCUSDT',self.open=16938.9, self.close=16945.5, self.high=16947.5, self.low=16927.5, self.vol=7997.895, self.amt=135470691.2096 
2023-01-08 16:00:01,020:INFO:s_rsrs:main.py:142:handleKline:185271: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime  ...        vol           amt       pct
719  20230107   200000    235959  ...  16729.280  2.830697e+08  0.001301
720  20230108   000000    035959  ...   9360.224  1.584223e+08  0.000171
721  20230108   040000    075959  ...   9824.894  1.663814e+08 -0.000047
722  20230108   080000    115959  ...  15067.264  2.550033e+08  0.000148
723  20230108   120000    155959  ...   7997.895  1.354707e+08  0.000384

[5 rows x 11 columns]
2023-01-08 16:00:02,680:INFO:s_rsrs:main.py:151:handleKline:185271: df_s.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec  ...  index      beta    zscore  signal
719  20230107   200000    235959  1673107199  ...    719  0.354376  0.109310     NaN
720  20230108   000000    035959  1673121599  ...    720  0.336979  0.040098     NaN
721  20230108   040000    075959  1673135999  ...    721  0.226620 -0.341427     NaN
722  20230108   080000    115959  1673150399  ...    722  0.135794 -0.657472    -1.0
723  20230108   120000    155959  1673164799  ...    723  0.186551 -0.494174     NaN

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '52.715', 'enterprice': '16938.9', 'countrevence': '0', 'unrealprofit': '-347.919', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '16945.5', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-9223372036854775808, self.sign=-1


