# 20230106 16:16:02

## /root/FIL/strategy/amihud/log.txt ----- -----

127.0.0.1 - - [06/Jan/2023 16:10:01] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=993672.4896432, self.flagDict['side']='sell', self.tradeCount=2, self.count=11546
self.closeSec=1672992599, self.tradeDate='20230106', self.openTime='160500', self.closeTime='160959', self.symbol='BTCUSDT', self.open=16788.3, self.close=16792.4, self.high=16792.5, self.low=16788.3, self.vol=567.147, self.amt=9522686.9272 
2023-01-06 16:10:01,480:INFO:amihud:main.py:172:handleKline:200676: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5949  20230106   154500    154959  ...         0.0        0.0       0
5950  20230106   155000    155459  ...         0.0        0.0       0
5951  20230106   155500    155959  ...         0.0        0.0       0
5952  20230106   160000    160459  ...         0.0        0.0       0
5953  20230106   160500    160959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-01-06 16:10:01,481:INFO:amihud:main.py:175:handleKline:200676: self.closeSec=1672992599, self.tradeDate='20230106', self.openTime='160500', self.closeTime='160959',self.symbol='BTCUSDT',self.open=16788.3, self.close=16792.4, self.high=16792.5, self.low=16788.3, self.vol=567.147, self.amt=9522686.9272, ukdf['pct'].iloc[-1]=0.000244 , ukdf['amount'].iloc[-1]=9522686.9272, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5953, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '60.176', 'enterprice': '16529.3', 'countrevence': '0', 'unrealprofit': '-15832.3056', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '16792.4', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1
127.0.0.1 - - [06/Jan/2023 16:15:00] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=993672.4896432, self.flagDict['side']='sell', self.tradeCount=2, self.count=11547
self.closeSec=1672992899, self.tradeDate='20230106', self.openTime='161000', self.closeTime='161459', self.symbol='BTCUSDT', self.open=16792.4, self.close=16794.3, self.high=16796.0, self.low=16790.9, self.vol=452.539, self.amt=7599591.9353 
2023-01-06 16:15:00,654:INFO:amihud:main.py:172:handleKline:200676: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5950  20230106   155000    155459  ...         0.0        0.0       0
5951  20230106   155500    155959  ...         0.0        0.0       0
5952  20230106   160000    160459  ...         0.0        0.0       0
5953  20230106   160500    160959  ...         0.0        0.0       0
5954  20230106   161000    161459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-01-06 16:15:00,654:INFO:amihud:main.py:175:handleKline:200676: self.closeSec=1672992899, self.tradeDate='20230106', self.openTime='161000', self.closeTime='161459',self.symbol='BTCUSDT',self.open=16792.4, self.close=16794.3, self.high=16796.0, self.low=16790.9, self.vol=452.539, self.amt=7599591.9353, ukdf['pct'].iloc[-1]=0.000113 , ukdf['amount'].iloc[-1]=7599591.9353, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5954, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '60.176', 'enterprice': '16529.3', 'countrevence': '0', 'unrealprofit': '-15956.2760340296', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '16794.46013085', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1


## /root/FIL/strategy/factorcheck/log.txt ----- -----

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=182, self.factor=0.5188597200007895, self.count=12112 

self.closeSec=1672992599, self.tradeDate='20230106', self.openTime='160500', self.closeTime='160959', self.symbol='BTCUSDT', self.open=16788.3, self.close=16792.4, self.high=16792.5, self.low=16788.3 
2023-01-06 16:10:01,418:INFO:factorcheck2:main.py:126:handleKline:185239: self.closeSec=1672992599, self.tradeDate='20230106', self.openTime='160500', self.closeTime='160959',self.symbol='BTCUSDT',self.open=16788.3, self.close=16792.4, self.high=16792.5, self.low=16788.3   
2023-01-06 16:10:01,454:INFO:factorcheck2:main.py:127:handleKline:185239: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1629  20230106   154500    154959  1672991399  ...  16782.6 -0.000262   1629    3
1630  20230106   155000    155459  1672991699  ...  16781.9  0.000191   1630    4
1631  20230106   155500    155959  1672991999  ...  16784.9 -0.000012   1631    5
1632  20230106   160000    160459  1672992299  ...  16785.6  0.000155   1632    0
1633  20230106   160500    160959  1672992599  ...  16788.3  0.000244   1633    1

[5 rows x 11 columns]
2023-01-06 16:10:01,456:INFO:factorcheck2:main.py:128:handleKline:185239: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=182, self.factor=0.5188597200007895, self.count=12113 

self.closeSec=1672992899, self.tradeDate='20230106', self.openTime='161000', self.closeTime='161459', self.symbol='BTCUSDT', self.open=16792.4, self.close=16794.3, self.high=16796.0, self.low=16790.9 
2023-01-06 16:15:00,534:INFO:factorcheck2:main.py:126:handleKline:185239: self.closeSec=1672992899, self.tradeDate='20230106', self.openTime='161000', self.closeTime='161459',self.symbol='BTCUSDT',self.open=16792.4, self.close=16794.3, self.high=16796.0, self.low=16790.9   
127.0.0.1 - - [06/Jan/2023 16:15:00] "POST / HTTP/1.1" 200 -
2023-01-06 16:15:00,627:INFO:factorcheck2:main.py:127:handleKline:185239: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1630  20230106   155000    155459  1672991699  ...  16781.9  0.000191   1630    4
1631  20230106   155500    155959  1672991999  ...  16784.9 -0.000012   1631    5
1632  20230106   160000    160459  1672992299  ...  16785.6  0.000155   1632    0
1633  20230106   160500    160959  1672992599  ...  16788.3  0.000244   1633    1
1634  20230106   161000    161459  1672992899  ...  16790.9  0.000113   1634    2

[5 rows x 11 columns]
2023-01-06 16:15:00,628:INFO:factorcheck2:main.py:128:handleKline:185239: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}


## /root/FIL/strategy/logic/log.txt ----- -----

2023-01-06 16:00:18,468:DEBUG:logic:main.py:456:getModel:726423: df_s.iloc[-5:,:] :
          date closeTime     open  ...    alpha58   alpha67   alpha72
5786  20230106    132959  16814.4  ...  50.000000  0.496052  0.398289
5787  20230106    135959  16801.3  ...  49.583333  0.496052  0.407688
5788  20230106    142959  16801.3  ...  49.166667  0.488321  0.421546
5789  20230106    145959  16791.2  ...  49.166667  0.479117  0.440623
5790  20230106    152959  16779.2  ...  49.583333  0.490601  0.451228

[5 rows x 33 columns]
0.5424354243542435
acc is : 0.5424354243542435
2023-01-06 16:00:18,562:INFO:logic:main.py:461:getModel:726423: df_pred.iloc[-5:,:] :
     pred    prob_0    prob_1  actual  ...  nav  sign   cost_        bm
537     1  0.492651  0.507349       0  ...  NaN   NaN -0.0016  0.998769
538     1  0.494793  0.505207       0  ...  NaN   NaN -0.0016  0.998169
539     1  0.491749  0.508251       0  ...  NaN   NaN -0.0016  0.997444
540     1  0.492112  0.507888       1  ...  NaN   NaN -0.0016  0.998294
541     1  0.498568  0.501432       0  ...  NaN   NaN -0.0016  0.997836

[5 rows x 10 columns]
2023-01-06 16:00:18,574:INFO:logic:main.py:471:getModel:726423: df_panel.iloc[-5:,:] :
    pred    prob_0    prob_1  actual  ...  nav  sign   cost_        bm
45     1  0.493074  0.506926       0  ...  NaN   NaN -0.0016  0.999251
46     1  0.495406  0.504594       0  ...  NaN   NaN -0.0016  0.999048
47     1  0.491732  0.508268       0  ...  NaN   NaN -0.0016  0.997307
48     1  0.492745  0.507255       1  ...  NaN   NaN -0.0016  0.998567
49     1  0.498568  0.501432       0  ...  NaN   NaN -0.0016  0.997836

[5 rows x 10 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '42.528', 'enterprice': '16701.5', 'countrevence': '0', 'unrealprofit': '3576.6048', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '16785.6', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}


## /root/FIL/strategy/modifiedmom/log.txt ----- -----

526  20230106   154000    154959  1672991399  16790.3  16782.7 -0.000459
2023-01-06 15:50:00,552:INFO:modifiedmom:main.py:146:handleKline:185213: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': True, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True}

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=6055 

self.closeSec=1672991999, self.tradeDate='20230106', self.openTime='155000', self.closeTime='155959', self.symbol='BTCUSDT', self.open='16782.6', self.close='16785.6'
2023-01-06 16:00:00,902:INFO:modifiedmom:main.py:144:handleKline:185213: self.closeSec=1672991999, self.tradeDate='20230106', self.openTime='155000', self.closeTime='155959',self.symbol='BTCUSDT',self.open='16782.6', self.close='16785.6'
127.0.0.1 - - [06/Jan/2023 16:00:00] "POST / HTTP/1.1" 200 -
2023-01-06 16:00:00,942:INFO:modifiedmom:main.py:145:handleKline:185213: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
523  20230106   151000    151959  1672989599  16782.6  16782.7  0.000000
524  20230106   152000    152959  1672990199  16782.6  16793.4  0.000638
525  20230106   153000    153959  1672990799  16793.4  16790.4 -0.000179
526  20230106   154000    154959  1672991399  16790.3  16782.7 -0.000459
527  20230106   155000    155959  1672991999  16782.6  16785.6  0.000173
2023-01-06 16:00:00,942:INFO:modifiedmom:main.py:146:handleKline:185213: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': True, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True}
127.0.0.1 - - [06/Jan/2023 16:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=6056 

self.closeSec=1672992599, self.tradeDate='20230106', self.openTime='160000', self.closeTime='160959', self.symbol='BTCUSDT', self.open='16785.6', self.close='16792.4'
2023-01-06 16:10:01,532:INFO:modifiedmom:main.py:144:handleKline:185213: self.closeSec=1672992599, self.tradeDate='20230106', self.openTime='160000', self.closeTime='160959',self.symbol='BTCUSDT',self.open='16785.6', self.close='16792.4'
2023-01-06 16:10:01,539:INFO:modifiedmom:main.py:145:handleKline:185213: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
524  20230106   152000    152959  1672990199  16782.6  16793.4  0.000638
525  20230106   153000    153959  1672990799  16793.4  16790.4 -0.000179
526  20230106   154000    154959  1672991399  16790.3  16782.7 -0.000459
527  20230106   155000    155959  1672991999  16782.6  16785.6  0.000173
528  20230106   160000    160959  1672992599  16785.6  16792.4  0.000405
2023-01-06 16:10:01,541:INFO:modifiedmom:main.py:146:handleKline:185213: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': True, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True}


## /root/FIL/strategy/pyemd/log.txt ----- -----

17518  20230106   154000    154959  1672991399  16790.3  16782.7
2023-01-06 15:50:00,572:INFO:pyemd2:main.py:127:handleKline:185189: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}
127.0.0.1 - - [06/Jan/2023 16:00:00] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=6056 

self.closeSec=1672991999, self.tradeDate='20230106', self.openTime='155000', self.closeTime='155959', self.symbol='BTCUSDT', self.open='16782.6', self.close='16785.6'
2023-01-06 16:00:00,923:INFO:pyemd2:main.py:125:handleKline:185189: self.closeSec=1672991999, self.tradeDate='20230106', self.openTime='155000', self.closeTime='155959',self.symbol='BTCUSDT',self.open='16782.6', self.close='16785.6'
2023-01-06 16:00:00,963:INFO:pyemd2:main.py:126:handleKline:185189: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17515  20230106   151000    151959  1672989599  16782.6  16782.7
17516  20230106   152000    152959  1672990199  16782.6  16793.4
17517  20230106   153000    153959  1672990799  16793.4  16790.4
17518  20230106   154000    154959  1672991399  16790.3  16782.7
17519  20230106   155000    155959  1672991999  16782.6  16785.6
2023-01-06 16:00:00,963:INFO:pyemd2:main.py:127:handleKline:185189: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}
127.0.0.1 - - [06/Jan/2023 16:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=6057 

self.closeSec=1672992599, self.tradeDate='20230106', self.openTime='160000', self.closeTime='160959', self.symbol='BTCUSDT', self.open='16785.6', self.close='16792.4'
2023-01-06 16:10:01,509:INFO:pyemd2:main.py:125:handleKline:185189: self.closeSec=1672992599, self.tradeDate='20230106', self.openTime='160000', self.closeTime='160959',self.symbol='BTCUSDT',self.open='16785.6', self.close='16792.4'
2023-01-06 16:10:01,516:INFO:pyemd2:main.py:126:handleKline:185189: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17516  20230106   152000    152959  1672990199  16782.6  16793.4
17517  20230106   153000    153959  1672990799  16793.4  16790.4
17518  20230106   154000    154959  1672991399  16790.3  16782.7
17519  20230106   155000    155959  1672991999  16782.6  16785.6
17520  20230106   160000    160959  1672992599  16785.6  16792.4
2023-01-06 16:10:01,516:INFO:pyemd2:main.py:127:handleKline:185189: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}


## /root/FIL/strategy/similarity/log.txt ----- -----

12190  20230106   154000    154959  1672991399  16790.3  16782.7
2023-01-06 15:50:00,561:INFO:testStrategy:main.py:103:handleKline:185174: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': True, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=6056 

self.closeSec=1672991999, self.tradeDate='20230106', self.openTime='155000', self.closeTime='155959', self.symbol='BTCUSDT', self.open='16782.6', self.close='16785.6'
2023-01-06 16:00:00,915:INFO:testStrategy:main.py:101:handleKline:185174: self.closeSec=1672991999, self.tradeDate='20230106', self.openTime='155000', self.closeTime='155959',self.symbol='BTCUSDT',self.open='16782.6', self.close='16785.6'
127.0.0.1 - - [06/Jan/2023 16:00:00] "POST / HTTP/1.1" 200 -
2023-01-06 16:00:00,953:INFO:testStrategy:main.py:102:handleKline:185174: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12187  20230106   151000    151959  1672989599  16782.6  16782.7
12188  20230106   152000    152959  1672990199  16782.6  16793.4
12189  20230106   153000    153959  1672990799  16793.4  16790.4
12190  20230106   154000    154959  1672991399  16790.3  16782.7
12191  20230106   155000    155959  1672991999  16782.6  16785.6
2023-01-06 16:00:00,953:INFO:testStrategy:main.py:103:handleKline:185174: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': True, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}
127.0.0.1 - - [06/Jan/2023 16:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=6057 

self.closeSec=1672992599, self.tradeDate='20230106', self.openTime='160000', self.closeTime='160959', self.symbol='BTCUSDT', self.open='16785.6', self.close='16792.4'
2023-01-06 16:10:01,518:INFO:testStrategy:main.py:101:handleKline:185174: self.closeSec=1672992599, self.tradeDate='20230106', self.openTime='160000', self.closeTime='160959',self.symbol='BTCUSDT',self.open='16785.6', self.close='16792.4'
2023-01-06 16:10:01,543:INFO:testStrategy:main.py:102:handleKline:185174: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12188  20230106   152000    152959  1672990199  16782.6  16793.4
12189  20230106   153000    153959  1672990799  16793.4  16790.4
12190  20230106   154000    154959  1672991399  16790.3  16782.7
12191  20230106   155000    155959  1672991999  16782.6  16785.6
12192  20230106   160000    160959  1672992599  16785.6  16792.4
2023-01-06 16:10:01,543:INFO:testStrategy:main.py:103:handleKline:185174: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': True, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}


## /root/FIL/strategy/sr_min/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=0, self.total=1000000.0, self.flagDict['side']='', self.tradeCount=0, self.count=7544
self.closeSec=1672992599, self.tradeDate='20230106', self.openTime='160500', self.closeTime='160959', self.symbol='BTCUSDT', self.open=16788.3, self.close=16792.4, self.high=16792.5, self.low=16788.3, self.vol=567.147, self.amt=9522686.9272 
127.0.0.1 - - [06/Jan/2023 16:10:01] "POST / HTTP/1.1" 200 -
2023-01-06 16:10:01,468:INFO:sr_min:main.py:172:handleKline:449472: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5949  20230106   154500    154959  ...         0.0        0.0       0
5950  20230106   155000    155459  ...         0.0        0.0       0
5951  20230106   155500    155959  ...         0.0        0.0       0
5952  20230106   160000    160459  ...         0.0        0.0       0
5953  20230106   160500    160959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-01-06 16:10:01,468:INFO:sr_min:main.py:175:handleKline:449472: self.closeSec=1672992599, self.tradeDate='20230106', self.openTime='160500', self.closeTime='160959',self.symbol='BTCUSDT',self.open=16788.3, self.close=16792.4, self.high=16792.5, self.low=16788.3, self.vol=567.147, self.amt=9522686.9272, ukdf['pct'].iloc[-1]=0.000244 , ukdf['amount'].iloc[-1]=9522686.9272, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5953, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': []}
type(curSign)=<class 'int'>, curSign=0, self.sign=0
--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=0, self.total=1000000.0, self.flagDict['side']='', self.tradeCount=0, self.count=7545
self.closeSec=1672992899, self.tradeDate='20230106', self.openTime='161000', self.closeTime='161459', self.symbol='BTCUSDT', self.open=16792.4, self.close=16794.3, self.high=16796.0, self.low=16790.9, self.vol=452.539, self.amt=7599591.9353 
127.0.0.1 - - [06/Jan/2023 16:15:00] "POST / HTTP/1.1" 200 -
2023-01-06 16:15:00,657:INFO:sr_min:main.py:172:handleKline:449472: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5950  20230106   155000    155459  ...         0.0        0.0       0
5951  20230106   155500    155959  ...         0.0        0.0       0
5952  20230106   160000    160459  ...         0.0        0.0       0
5953  20230106   160500    160959  ...         0.0        0.0       0
5954  20230106   161000    161459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-01-06 16:15:00,657:INFO:sr_min:main.py:175:handleKline:449472: self.closeSec=1672992899, self.tradeDate='20230106', self.openTime='161000', self.closeTime='161459',self.symbol='BTCUSDT',self.open=16792.4, self.close=16794.3, self.high=16796.0, self.low=16790.9, self.vol=452.539, self.amt=7599591.9353, ukdf['pct'].iloc[-1]=0.000113 , ukdf['amount'].iloc[-1]=7599591.9353, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5954, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': []}
type(curSign)=<class 'int'>, curSign=0, self.sign=0


## /root/FIL/strategy/s_rsrs/log.txt ----- -----

721  20230106   040000    075959  1672963199  ...    721  0.486126  0.669225     1.0
722  20230106   080000    115959  1672977599  ...    722  0.395637  0.362932     NaN

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '52.77', 'enterprice': '16723.1', 'countrevence': '0', 'unrealprofit': '5474.7582314418', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '16826.84755034', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-9223372036854775808, self.sign=1
127.0.0.1 - - [06/Jan/2023 16:00:00] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='s_rsrs', self.symbol='BTCUSDT', interval='4h', intervalSec=14400, wid=25, thd=0.6, self.sign=1, self.total=881595.509013, self.flagDict['side']='buy', self.tradeCount=10, self.count=252
self.closeSec=1672991999, self.tradeDate='20230106', self.openTime='120000', self.closeTime='155959', self.symbol='BTCUSDT', self.open=16825.0, self.close=16785.7, self.high=16828.0, self.low=16773.0, self.vol=23858.14, self.amt=400704605.9794 
2023-01-06 16:00:00,812:INFO:s_rsrs:main.py:141:handleKline:185271: self.closeSec=1672991999, self.tradeDate='20230106', self.openTime='120000', self.closeTime='155959',self.symbol='BTCUSDT',self.open=16825.0, self.close=16785.7, self.high=16828.0, self.low=16773.0, self.vol=23858.14, self.amt=400704605.9794 
2023-01-06 16:00:00,833:INFO:s_rsrs:main.py:142:handleKline:185271: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime  ...        vol           amt       pct
719  20230105   200000    235959  ...  68886.393  1.157975e+09  0.000571
720  20230106   000000    035959  ...  29187.231  4.912216e+08  0.001170
721  20230106   040000    075959  ...  19079.522  3.212681e+08 -0.001928
722  20230106   080000    115959  ...  21068.083  3.545791e+08  0.000071
723  20230106   120000    155959  ...  23858.140  4.007046e+08 -0.002336

[5 rows x 11 columns]
2023-01-06 16:00:02,656:INFO:s_rsrs:main.py:151:handleKline:185271: df_s.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec  ...  index      beta    zscore  signal
719  20230105   200000    235959  1672934399  ...    719  0.703932  1.416203     1.0
720  20230106   000000    035959  1672948799  ...    720  0.587124  1.013075     1.0
721  20230106   040000    075959  1672963199  ...    721  0.486126  0.669225     1.0
722  20230106   080000    115959  1672977599  ...    722  0.395637  0.362932     NaN
723  20230106   120000    155959  1672991999  ...    723  0.397553  0.357165     NaN

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '52.77', 'enterprice': '16723.1', 'countrevence': '0', 'unrealprofit': '3333.8367608274', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '16786.27674362', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-9223372036854775808, self.sign=1


