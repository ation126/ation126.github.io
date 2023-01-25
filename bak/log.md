# 20230125 16:16:01

## /root/FIL/strategy/amihud/log.txt ----- -----

127.0.0.1 - - [25/Jan/2023 16:10:01] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=993672.4896432, self.flagDict['side']='sell', self.tradeCount=2, self.count=17018
self.closeSec=1674634199, self.tradeDate='20230125', self.openTime='160500', self.closeTime='160959', self.symbol='BTCUSDT', self.open=22726.0, self.close=22706.9, self.high=22730.0, self.low=22695.7, self.vol=803.073, self.amt=18236094.825 
2023-01-25 16:10:01,504:INFO:amihud:main.py:172:handleKline:200676: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5949  20230125   154500    154959  ...         0.0        0.0       0
5950  20230125   155000    155459  ...         0.0        0.0       0
5951  20230125   155500    155959  ...         0.0        0.0       0
5952  20230125   160000    160459  ...         0.0        0.0       0
5953  20230125   160500    160959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-01-25 16:10:01,505:INFO:amihud:main.py:175:handleKline:200676: self.closeSec=1674634199, self.tradeDate='20230125', self.openTime='160500', self.closeTime='160959',self.symbol='BTCUSDT',self.open=22726.0, self.close=22706.9, self.high=22730.0, self.low=22695.7, self.vol=803.073, self.amt=18236094.825, ukdf['pct'].iloc[-1]=-0.000836 , ukdf['amount'].iloc[-1]=18236094.825, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5953, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '60.176', 'enterprice': '16529.3', 'countrevence': '0', 'unrealprofit': '-371766.82236273536', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '22707.29159736', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1
--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=993672.4896432, self.flagDict['side']='sell', self.tradeCount=2, self.count=17019
self.closeSec=1674634499, self.tradeDate='20230125', self.openTime='161000', self.closeTime='161459', self.symbol='BTCUSDT', self.open=22707.0, self.close=22688.8, self.high=22714.0, self.low=22687.6, self.vol=774.527, self.amt=17580331.3002 
127.0.0.1 - - [25/Jan/2023 16:15:00] "POST / HTTP/1.1" 200 -
2023-01-25 16:15:00,897:INFO:amihud:main.py:172:handleKline:200676: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5950  20230125   155000    155459  ...         0.0        0.0       0
5951  20230125   155500    155959  ...         0.0        0.0       0
5952  20230125   160000    160459  ...         0.0        0.0       0
5953  20230125   160500    160959  ...         0.0        0.0       0
5954  20230125   161000    161459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-01-25 16:15:00,897:INFO:amihud:main.py:175:handleKline:200676: self.closeSec=1674634499, self.tradeDate='20230125', self.openTime='161000', self.closeTime='161459',self.symbol='BTCUSDT',self.open=22707.0, self.close=22688.8, self.high=22714.0, self.low=22687.6, self.vol=774.527, self.amt=17580331.3002, ukdf['pct'].iloc[-1]=-0.000797 , ukdf['amount'].iloc[-1]=17580331.3002, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5954, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '60.176', 'enterprice': '16529.3', 'countrevence': '0', 'unrealprofit': '-370769.79795736304', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '22690.72312479', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1


## /root/FIL/strategy/factorcheck/log.txt ----- -----

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=221, self.factor=0.5033871081561616, self.count=17584 

self.closeSec=1674634199, self.tradeDate='20230125', self.openTime='160500', self.closeTime='160959', self.symbol='BTCUSDT', self.open=22726.0, self.close=22706.9, self.high=22730.0, self.low=22695.7 
2023-01-25 16:10:01,440:INFO:factorcheck2:main.py:126:handleKline:185239: self.closeSec=1674634199, self.tradeDate='20230125', self.openTime='160500', self.closeTime='160959',self.symbol='BTCUSDT',self.open=22726.0, self.close=22706.9, self.high=22730.0, self.low=22695.7   
2023-01-25 16:10:01,472:INFO:factorcheck2:main.py:127:handleKline:185239: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1629  20230125   154500    154959  1674632999  ...  22712.6 -0.000488   1629    3
1630  20230125   155000    155459  1674633299  ...  22713.3  0.000040   1630    4
1631  20230125   155500    155959  1674633599  ...  22699.5 -0.000458   1631    5
1632  20230125   160000    160459  1674633899  ...  22703.9  0.000969   1632    0
1633  20230125   160500    160959  1674634199  ...  22695.7 -0.000836   1633    1

[5 rows x 11 columns]
2023-01-25 16:10:01,472:INFO:factorcheck2:main.py:128:handleKline:185239: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=221, self.factor=0.5033871081561616, self.count=17585 

self.closeSec=1674634499, self.tradeDate='20230125', self.openTime='161000', self.closeTime='161459', self.symbol='BTCUSDT', self.open=22707.0, self.close=22688.8, self.high=22714.0, self.low=22687.6 
2023-01-25 16:15:00,826:INFO:factorcheck2:main.py:126:handleKline:185239: self.closeSec=1674634499, self.tradeDate='20230125', self.openTime='161000', self.closeTime='161459',self.symbol='BTCUSDT',self.open=22707.0, self.close=22688.8, self.high=22714.0, self.low=22687.6   
127.0.0.1 - - [25/Jan/2023 16:15:00] "POST / HTTP/1.1" 200 -
2023-01-25 16:15:00,877:INFO:factorcheck2:main.py:127:handleKline:185239: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1630  20230125   155000    155459  1674633299  ...  22713.3  0.000040   1630    4
1631  20230125   155500    155959  1674633599  ...  22699.5 -0.000458   1631    5
1632  20230125   160000    160459  1674633899  ...  22703.9  0.000969   1632    0
1633  20230125   160500    160959  1674634199  ...  22695.7 -0.000836   1633    1
1634  20230125   161000    161459  1674634499  ...  22687.6 -0.000797   1634    2

[5 rows x 11 columns]
2023-01-25 16:15:00,878:INFO:factorcheck2:main.py:128:handleKline:185239: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}


## /root/FIL/strategy/logic/log.txt ----- -----

2023-01-25 16:00:18,122:DEBUG:logic:main.py:463:getModel:885513: df_s.iloc[-5:,:] :
          date closeTime     open  ...    alpha58   alpha67   alpha72
5786  20230125    132959  22620.0  ...  55.000000  0.476486  0.588529
5787  20230125    135959  22681.9  ...  54.583333  0.473607  0.585416
5788  20230125    142959  22665.4  ...  54.583333  0.478498  0.580350
5789  20230125    145959  22690.5  ...  55.000000  0.481767  0.574184
5790  20230125    152959  22707.2  ...  55.000000  0.483567  0.567646

[5 rows x 33 columns]
0.540590405904059
acc is : 0.540590405904059
2023-01-25 16:00:18,199:INFO:logic:main.py:468:getModel:885513: df_pred.iloc[-5:,:] :
     pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
537     0  0.537172  0.462828       0  ...  0.989406  -1.0    0.0  1.084370
538     0  0.515045  0.484955       1  ...  0.988310  -1.0    0.0  1.085571
539     0  0.523778  0.476222       1  ...  0.987583  -1.0    0.0  1.086370
540     0  0.523622  0.476378       1  ...  0.987187  -1.0    0.0  1.086806
541     0  0.524818  0.475182       0  ...  0.987726  -1.0    0.0  1.086212

[5 rows x 10 columns]
2023-01-25 16:00:18,210:INFO:logic:main.py:478:getModel:885513: df_panel.iloc[-5:,:] :
    pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
45     0  0.538237  0.461763       0  ...  1.003244  -1.0    0.0  1.142294
46     0  0.515765  0.484235       1  ...  1.002133  -1.0    0.0  1.145077
47     0  0.524866  0.475134       1  ...  1.001396  -1.0    0.0  1.139679
48     0  0.524032  0.475968       1  ...  0.987048  -1.0    0.0  1.114960
49     0  0.524818  0.475182       0  ...  0.987726  -1.0    0.0  1.086212

[5 rows x 10 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '32.198', 'enterprice': '22732.6', 'countrevence': '0', 'unrealprofit': '672.18487820508', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '22711.72339654', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}


## /root/FIL/strategy/modifiedmom/log.txt ----- -----

526  20230125   154000    154959  1674632999  22724.1  22713.4 -0.000471
2023-01-25 15:50:00,569:INFO:modifiedmom:main.py:146:handleKline:185213: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': True, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True}
127.0.0.1 - - [25/Jan/2023 16:00:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=8791 

self.closeSec=1674633599, self.tradeDate='20230125', self.openTime='155000', self.closeTime='155959', self.symbol='BTCUSDT', self.open='22713.4', self.close='22703.9'
2023-01-25 16:00:01,849:INFO:modifiedmom:main.py:144:handleKline:185213: self.closeSec=1674633599, self.tradeDate='20230125', self.openTime='155000', self.closeTime='155959',self.symbol='BTCUSDT',self.open='22713.4', self.close='22703.9'
2023-01-25 16:00:01,894:INFO:modifiedmom:main.py:145:handleKline:185213: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
523  20230125   151000    151959  1674631199  22722.6  22732.3  0.000431
524  20230125   152000    152959  1674631799  22732.3  22716.3 -0.000704
525  20230125   153000    153959  1674632399  22716.3  22724.1  0.000343
526  20230125   154000    154959  1674632999  22724.1  22713.4 -0.000471
527  20230125   155000    155959  1674633599  22713.4  22703.9 -0.000418
2023-01-25 16:00:01,894:INFO:modifiedmom:main.py:146:handleKline:185213: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': True, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True}
127.0.0.1 - - [25/Jan/2023 16:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=8792 

self.closeSec=1674634199, self.tradeDate='20230125', self.openTime='160000', self.closeTime='160959', self.symbol='BTCUSDT', self.open='22703.9', self.close='22706.9'
2023-01-25 16:10:01,525:INFO:modifiedmom:main.py:144:handleKline:185213: self.closeSec=1674634199, self.tradeDate='20230125', self.openTime='160000', self.closeTime='160959',self.symbol='BTCUSDT',self.open='22703.9', self.close='22706.9'
2023-01-25 16:10:01,562:INFO:modifiedmom:main.py:145:handleKline:185213: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
524  20230125   152000    152959  1674631799  22732.3  22716.3 -0.000704
525  20230125   153000    153959  1674632399  22716.3  22724.1  0.000343
526  20230125   154000    154959  1674632999  22724.1  22713.4 -0.000471
527  20230125   155000    155959  1674633599  22713.4  22703.9 -0.000418
528  20230125   160000    160959  1674634199  22703.9  22706.9  0.000132
2023-01-25 16:10:01,562:INFO:modifiedmom:main.py:146:handleKline:185213: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': True, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True}


## /root/FIL/strategy/pyemd/log.txt ----- -----

17518  20230125   154000    154959  1674632999  22724.1  22713.4
2023-01-25 15:50:00,575:INFO:pyemd2:main.py:127:handleKline:185189: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}
127.0.0.1 - - [25/Jan/2023 16:00:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=8792 

self.closeSec=1674633599, self.tradeDate='20230125', self.openTime='155000', self.closeTime='155959', self.symbol='BTCUSDT', self.open='22713.4', self.close='22703.9'
2023-01-25 16:00:01,865:INFO:pyemd2:main.py:125:handleKline:185189: self.closeSec=1674633599, self.tradeDate='20230125', self.openTime='155000', self.closeTime='155959',self.symbol='BTCUSDT',self.open='22713.4', self.close='22703.9'
2023-01-25 16:00:01,906:INFO:pyemd2:main.py:126:handleKline:185189: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17515  20230125   151000    151959  1674631199  22722.6  22732.3
17516  20230125   152000    152959  1674631799  22732.3  22716.3
17517  20230125   153000    153959  1674632399  22716.3  22724.1
17518  20230125   154000    154959  1674632999  22724.1  22713.4
17519  20230125   155000    155959  1674633599  22713.4  22703.9
2023-01-25 16:00:01,906:INFO:pyemd2:main.py:127:handleKline:185189: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}
127.0.0.1 - - [25/Jan/2023 16:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=8793 

self.closeSec=1674634199, self.tradeDate='20230125', self.openTime='160000', self.closeTime='160959', self.symbol='BTCUSDT', self.open='22703.9', self.close='22706.9'
2023-01-25 16:10:01,540:INFO:pyemd2:main.py:125:handleKline:185189: self.closeSec=1674634199, self.tradeDate='20230125', self.openTime='160000', self.closeTime='160959',self.symbol='BTCUSDT',self.open='22703.9', self.close='22706.9'
2023-01-25 16:10:01,573:INFO:pyemd2:main.py:126:handleKline:185189: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17516  20230125   152000    152959  1674631799  22732.3  22716.3
17517  20230125   153000    153959  1674632399  22716.3  22724.1
17518  20230125   154000    154959  1674632999  22724.1  22713.4
17519  20230125   155000    155959  1674633599  22713.4  22703.9
17520  20230125   160000    160959  1674634199  22703.9  22706.9
2023-01-25 16:10:01,573:INFO:pyemd2:main.py:127:handleKline:185189: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}


## /root/FIL/strategy/similarity/log.txt ----- -----

12190  20230125   154000    154959  1674632999  22724.1  22713.4
2023-01-25 15:50:00,570:INFO:testStrategy:main.py:103:handleKline:185174: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': True, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}
127.0.0.1 - - [25/Jan/2023 16:00:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=8792 

self.closeSec=1674633599, self.tradeDate='20230125', self.openTime='155000', self.closeTime='155959', self.symbol='BTCUSDT', self.open='22713.4', self.close='22703.9'
2023-01-25 16:00:01,857:INFO:testStrategy:main.py:101:handleKline:185174: self.closeSec=1674633599, self.tradeDate='20230125', self.openTime='155000', self.closeTime='155959',self.symbol='BTCUSDT',self.open='22713.4', self.close='22703.9'
2023-01-25 16:00:01,900:INFO:testStrategy:main.py:102:handleKline:185174: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12187  20230125   151000    151959  1674631199  22722.6  22732.3
12188  20230125   152000    152959  1674631799  22732.3  22716.3
12189  20230125   153000    153959  1674632399  22716.3  22724.1
12190  20230125   154000    154959  1674632999  22724.1  22713.4
12191  20230125   155000    155959  1674633599  22713.4  22703.9
2023-01-25 16:00:01,901:INFO:testStrategy:main.py:103:handleKline:185174: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': True, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=8793 

self.closeSec=1674634199, self.tradeDate='20230125', self.openTime='160000', self.closeTime='160959', self.symbol='BTCUSDT', self.open='22703.9', self.close='22706.9'
2023-01-25 16:10:01,554:INFO:testStrategy:main.py:101:handleKline:185174: self.closeSec=1674634199, self.tradeDate='20230125', self.openTime='160000', self.closeTime='160959',self.symbol='BTCUSDT',self.open='22703.9', self.close='22706.9'
127.0.0.1 - - [25/Jan/2023 16:10:01] "POST / HTTP/1.1" 200 -
2023-01-25 16:10:01,568:INFO:testStrategy:main.py:102:handleKline:185174: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12188  20230125   152000    152959  1674631799  22732.3  22716.3
12189  20230125   153000    153959  1674632399  22716.3  22724.1
12190  20230125   154000    154959  1674632999  22724.1  22713.4
12191  20230125   155000    155959  1674633599  22713.4  22703.9
12192  20230125   160000    160959  1674634199  22703.9  22706.9
2023-01-25 16:10:01,568:INFO:testStrategy:main.py:103:handleKline:185174: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': True, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}


## /root/FIL/strategy/sr_min/log.txt ----- -----

127.0.0.1 - - [25/Jan/2023 16:10:01] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=0, self.total=1000000.0, self.flagDict['side']='', self.tradeCount=0, self.count=13016
self.closeSec=1674634199, self.tradeDate='20230125', self.openTime='160500', self.closeTime='160959', self.symbol='BTCUSDT', self.open=22726.0, self.close=22706.9, self.high=22730.0, self.low=22695.7, self.vol=803.073, self.amt=18236094.825 
2023-01-25 16:10:01,510:INFO:sr_min:main.py:172:handleKline:449472: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5949  20230125   154500    154959  ...         0.0        0.0       0
5950  20230125   155000    155459  ...         0.0        0.0       0
5951  20230125   155500    155959  ...         0.0        0.0       0
5952  20230125   160000    160459  ...         0.0        0.0       0
5953  20230125   160500    160959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-01-25 16:10:01,510:INFO:sr_min:main.py:175:handleKline:449472: self.closeSec=1674634199, self.tradeDate='20230125', self.openTime='160500', self.closeTime='160959',self.symbol='BTCUSDT',self.open=22726.0, self.close=22706.9, self.high=22730.0, self.low=22695.7, self.vol=803.073, self.amt=18236094.825, ukdf['pct'].iloc[-1]=-0.000836 , ukdf['amount'].iloc[-1]=18236094.825, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5953, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': []}
type(curSign)=<class 'int'>, curSign=0, self.sign=0
--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=0, self.total=1000000.0, self.flagDict['side']='', self.tradeCount=0, self.count=13017
self.closeSec=1674634499, self.tradeDate='20230125', self.openTime='161000', self.closeTime='161459', self.symbol='BTCUSDT', self.open=22707.0, self.close=22688.8, self.high=22714.0, self.low=22687.6, self.vol=774.527, self.amt=17580331.3002 
127.0.0.1 - - [25/Jan/2023 16:15:00] "POST / HTTP/1.1" 200 -
2023-01-25 16:15:00,887:INFO:sr_min:main.py:172:handleKline:449472: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5950  20230125   155000    155459  ...         0.0        0.0       0
5951  20230125   155500    155959  ...         0.0        0.0       0
5952  20230125   160000    160459  ...         0.0        0.0       0
5953  20230125   160500    160959  ...         0.0        0.0       0
5954  20230125   161000    161459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-01-25 16:15:00,888:INFO:sr_min:main.py:175:handleKline:449472: self.closeSec=1674634499, self.tradeDate='20230125', self.openTime='161000', self.closeTime='161459',self.symbol='BTCUSDT',self.open=22707.0, self.close=22688.8, self.high=22714.0, self.low=22687.6, self.vol=774.527, self.amt=17580331.3002, ukdf['pct'].iloc[-1]=-0.000797 , ukdf['amount'].iloc[-1]=17580331.3002, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5954, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': []}
type(curSign)=<class 'int'>, curSign=0, self.sign=0


## /root/FIL/strategy/s_rsrs/log.txt ----- -----

721  20230125   040000    075959  1674604799  ...    721  0.040427 -1.910773    -1.0
722  20230125   080000    115959  1674619199  ...    722  0.162382 -1.576378    -1.0

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '41.738', 'enterprice': '22927.7', 'countrevence': '0', 'unrealprofit': '11970.4584', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '22640.9', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-1, self.sign=-1
--handleKline--:  version='2.0.0', self.name='s_rsrs', self.symbol='BTCUSDT', interval='4h', intervalSec=14400, wid=25, thd=0.6, self.sign=-1, self.total=955999.3862573999, self.flagDict['side']='sell', self.tradeCount=15, self.count=366
self.closeSec=1674633599, self.tradeDate='20230125', self.openTime='120000', self.closeTime='155959', self.symbol='BTCUSDT', self.open=22641.1, self.close=22703.9, self.high=22766.7, self.low=22600.0, self.vol=34838.121, self.amt=790179206.11385 
127.0.0.1 - - [25/Jan/2023 16:00:01] "POST / HTTP/1.1" 200 -
2023-01-25 16:00:01,734:INFO:s_rsrs:main.py:141:handleKline:185271: self.closeSec=1674633599, self.tradeDate='20230125', self.openTime='120000', self.closeTime='155959',self.symbol='BTCUSDT',self.open=22641.1, self.close=22703.9, self.high=22766.7, self.low=22600.0, self.vol=34838.121, self.amt=790179206.11385 
2023-01-25 16:00:01,758:INFO:s_rsrs:main.py:142:handleKline:185271: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime  ...         vol           amt       pct
719  20230124   200000    235959  ...  126440.595  2.891896e+09  0.000524
720  20230125   000000    035959  ...   67270.843  1.543281e+09  0.003970
721  20230125   040000    075959  ...  141871.503  3.229601e+09 -0.016841
722  20230125   080000    115959  ...   97898.966  2.206165e+09  0.000601
723  20230125   120000    155959  ...   34838.121  7.901792e+08  0.002778

[5 rows x 11 columns]
2023-01-25 16:00:03,188:INFO:s_rsrs:main.py:151:handleKline:185271: df_s.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec  ...  index      beta    zscore  signal
719  20230124   200000    235959  1674575999  ...    719  0.566763 -0.712239    -1.0
720  20230125   000000    035959  1674590399  ...    720  0.332173 -1.263201    -1.0
721  20230125   040000    075959  1674604799  ...    721  0.040427 -1.910773    -1.0
722  20230125   080000    115959  1674619199  ...    722  0.162382 -1.576378    -1.0
723  20230125   120000    155959  1674633599  ...    723  0.145590 -1.574237    -1.0

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '41.738', 'enterprice': '22927.7', 'countrevence': '0', 'unrealprofit': '9215.07648948702', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '22706.91614621', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-1, self.sign=-1


