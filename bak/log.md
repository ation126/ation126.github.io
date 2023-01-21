# 20230121 16:16:01

## /root/FIL/strategy/amihud/log.txt ----- -----

127.0.0.1 - - [21/Jan/2023 16:10:01] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=993672.4896432, self.flagDict['side']='sell', self.tradeCount=2, self.count=15866
self.closeSec=1674288599, self.tradeDate='20230121', self.openTime='160500', self.closeTime='160959', self.symbol='BTCUSDT', self.open=22658.4, self.close=22691.6, self.high=22699.4, self.low=22658.3, self.vol=3018.522, self.amt=68467139.2894 
2023-01-21 16:10:01,495:INFO:amihud:main.py:172:handleKline:200676: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5949  20230121   154500    154959  ...         0.0        0.0       0
5950  20230121   155000    155459  ...         0.0        0.0       0
5951  20230121   155500    155959  ...         0.0        0.0       0
5952  20230121   160000    160459  ...         0.0        0.0       0
5953  20230121   160500    160959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-01-21 16:10:01,495:INFO:amihud:main.py:175:handleKline:200676: self.closeSec=1674288599, self.tradeDate='20230121', self.openTime='160500', self.closeTime='160959',self.symbol='BTCUSDT',self.open=22658.4, self.close=22691.6, self.high=22699.4, self.low=22658.3, self.vol=3018.522, self.amt=68467139.2894, ukdf['pct'].iloc[-1]=0.00147 , ukdf['amount'].iloc[-1]=68467139.2894, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5953, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '60.176', 'enterprice': '16529.3', 'countrevence': '0', 'unrealprofit': '-370795.50204971136', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '22691.15027336', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1
127.0.0.1 - - [21/Jan/2023 16:15:00] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=993672.4896432, self.flagDict['side']='sell', self.tradeCount=2, self.count=15867
self.closeSec=1674288899, self.tradeDate='20230121', self.openTime='161000', self.closeTime='161459', self.symbol='BTCUSDT', self.open=22691.7, self.close=22735.8, self.high=22763.9, self.low=22680.3, self.vol=5828.445, self.amt=132437827.9518 
2023-01-21 16:15:00,669:INFO:amihud:main.py:172:handleKline:200676: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5950  20230121   155000    155459  ...         0.0        0.0       0
5951  20230121   155500    155959  ...         0.0        0.0       0
5952  20230121   160000    160459  ...         0.0        0.0       0
5953  20230121   160500    160959  ...         0.0        0.0       0
5954  20230121   161000    161459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-01-21 16:15:00,669:INFO:amihud:main.py:175:handleKline:200676: self.closeSec=1674288899, self.tradeDate='20230121', self.openTime='161000', self.closeTime='161459',self.symbol='BTCUSDT',self.open=22691.7, self.close=22735.8, self.high=22763.9, self.low=22680.3, self.vol=5828.445, self.amt=132437827.9518, ukdf['pct'].iloc[-1]=0.001948 , ukdf['amount'].iloc[-1]=132437827.9518, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5954, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '60.176', 'enterprice': '16529.3', 'countrevence': '0', 'unrealprofit': '-373656.39839409488', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '22738.69242213', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1


## /root/FIL/strategy/factorcheck/log.txt ----- -----

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=29, self.factor=0.21962287270604627, self.count=16432 

self.closeSec=1674288599, self.tradeDate='20230121', self.openTime='160500', self.closeTime='160959', self.symbol='BTCUSDT', self.open=22658.4, self.close=22691.6, self.high=22699.4, self.low=22658.3 
2023-01-21 16:10:01,432:INFO:factorcheck2:main.py:126:handleKline:185239: self.closeSec=1674288599, self.tradeDate='20230121', self.openTime='160500', self.closeTime='160959',self.symbol='BTCUSDT',self.open=22658.4, self.close=22691.6, self.high=22699.4, self.low=22658.3   
2023-01-21 16:10:01,492:INFO:factorcheck2:main.py:127:handleKline:185239: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1629  20230121   154500    154959  1674287399  ...  22628.7 -0.000194   1629    3
1630  20230121   155000    155459  1674287699  ...  22611.9 -0.000835   1630    4
1631  20230121   155500    155959  1674287999  ...  22624.7  0.000336   1631    5
1632  20230121   160000    160459  1674288299  ...  22619.2  0.001180   1632    0
1633  20230121   160500    160959  1674288599  ...  22658.3  0.001470   1633    1

[5 rows x 11 columns]
2023-01-21 16:10:01,492:INFO:factorcheck2:main.py:128:handleKline:185239: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}
127.0.0.1 - - [21/Jan/2023 16:15:00] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=29, self.factor=0.21962287270604627, self.count=16433 

self.closeSec=1674288899, self.tradeDate='20230121', self.openTime='161000', self.closeTime='161459', self.symbol='BTCUSDT', self.open=22691.7, self.close=22735.8, self.high=22763.9, self.low=22680.3 
2023-01-21 16:15:00,612:INFO:factorcheck2:main.py:126:handleKline:185239: self.closeSec=1674288899, self.tradeDate='20230121', self.openTime='161000', self.closeTime='161459',self.symbol='BTCUSDT',self.open=22691.7, self.close=22735.8, self.high=22763.9, self.low=22680.3   
2023-01-21 16:15:00,633:INFO:factorcheck2:main.py:127:handleKline:185239: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1630  20230121   155000    155459  1674287699  ...  22611.9 -0.000835   1630    4
1631  20230121   155500    155959  1674287999  ...  22624.7  0.000336   1631    5
1632  20230121   160000    160459  1674288299  ...  22619.2  0.001180   1632    0
1633  20230121   160500    160959  1674288599  ...  22658.3  0.001470   1633    1
1634  20230121   161000    161459  1674288899  ...  22680.3  0.001948   1634    2

[5 rows x 11 columns]
2023-01-21 16:15:00,635:INFO:factorcheck2:main.py:128:handleKline:185239: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}


## /root/FIL/strategy/logic/log.txt ----- -----

2023-01-21 16:00:18,316:DEBUG:logic:main.py:463:getModel:885513: df_s.iloc[-5:,:] :
          date closeTime     open  ...    alpha58   alpha67   alpha72
5786  20230121    132959  22593.1  ...  54.166667  0.716914  0.155951
5787  20230121    135959  22615.6  ...  53.750000  0.704429  0.154029
5788  20230121    142959  22570.5  ...  54.166667  0.708128  0.151114
5789  20230121    145959  22602.7  ...  54.166667  0.709872  0.147939
5790  20230121    152959  22617.7  ...  54.583333  0.711652  0.144486

[5 rows x 33 columns]
0.5350553505535055
acc is : 0.5350553505535055
2023-01-21 16:00:18,409:INFO:logic:main.py:468:getModel:885513: df_pred.iloc[-5:,:] :
     pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
537     0  0.545981  0.454019       0  ...  1.024552   1.0    0.0  1.311405
538     0  0.525208  0.474792       1  ...  1.026009   1.0    0.0  1.313271
539     0  0.542619  0.457381       1  ...  1.026695   1.0    0.0  1.314148
540     0  0.533277  0.466723       1  ...  1.027389   1.0    0.0  1.315037
541     0  0.535788  0.464212       0  ...  1.027321   1.0    0.0  1.314950

[5 rows x 10 columns]
2023-01-21 16:00:18,431:INFO:logic:main.py:478:getModel:885513: df_panel.iloc[-5:,:] :
    pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
45     0  0.545846  0.454154       0  ...  1.022913   1.0    0.0  1.312397
46     0  0.525142  0.474858       1  ...  1.059632   1.0    0.0  1.317020
47     0  0.542475  0.457525       1  ...  1.025052   1.0    0.0  1.317309
48     0  0.533240  0.466760       1  ...  1.025745   1.0    0.0  1.316659
49     0  0.535788  0.464212       0  ...  1.027321   1.0    0.0  1.314950

[5 rows x 10 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '33.709', 'enterprice': '20883.4', 'countrevence': '0', 'unrealprofit': '58793.07766154745', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '22627.53591805', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}


## /root/FIL/strategy/modifiedmom/log.txt ----- -----

526  20230121   154000    154959  1674287399  22643.4  22642.9 -0.000022
2023-01-21 15:50:00,561:INFO:modifiedmom:main.py:146:handleKline:185213: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True}
127.0.0.1 - - [21/Jan/2023 16:00:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=8215 

self.closeSec=1674287999, self.tradeDate='20230121', self.openTime='155000', self.closeTime='155959', self.symbol='BTCUSDT', self.open='22643.1', self.close='22631.6'
2023-01-21 16:00:01,371:INFO:modifiedmom:main.py:144:handleKline:185213: self.closeSec=1674287999, self.tradeDate='20230121', self.openTime='155000', self.closeTime='155959',self.symbol='BTCUSDT',self.open='22643.1', self.close='22631.6'
2023-01-21 16:00:01,418:INFO:modifiedmom:main.py:145:handleKline:185213: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
523  20230121   151000    151959  1674285599  22621.5    22622  0.000022
524  20230121   152000    152959  1674286199    22622  22633.1  0.000491
525  20230121   153000    153959  1674286799  22633.2  22643.4  0.000455
526  20230121   154000    154959  1674287399  22643.4  22642.9 -0.000022
527  20230121   155000    155959  1674287999  22643.1  22631.6 -0.000499
2023-01-21 16:00:01,418:INFO:modifiedmom:main.py:146:handleKline:185213: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True}

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=8216 

self.closeSec=1674288599, self.tradeDate='20230121', self.openTime='160000', self.closeTime='160959', self.symbol='BTCUSDT', self.open='22631.6', self.close='22691.6'
2023-01-21 16:10:01,533:INFO:modifiedmom:main.py:144:handleKline:185213: self.closeSec=1674288599, self.tradeDate='20230121', self.openTime='160000', self.closeTime='160959',self.symbol='BTCUSDT',self.open='22631.6', self.close='22691.6'
127.0.0.1 - - [21/Jan/2023 16:10:01] "POST / HTTP/1.1" 200 -
2023-01-21 16:10:01,551:INFO:modifiedmom:main.py:145:handleKline:185213: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
524  20230121   152000    152959  1674286199    22622  22633.1  0.000491
525  20230121   153000    153959  1674286799  22633.2  22643.4  0.000455
526  20230121   154000    154959  1674287399  22643.4  22642.9 -0.000022
527  20230121   155000    155959  1674287999  22643.1  22631.6 -0.000499
528  20230121   160000    160959  1674288599  22631.6  22691.6  0.002651
2023-01-21 16:10:01,551:INFO:modifiedmom:main.py:146:handleKline:185213: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True}


## /root/FIL/strategy/pyemd/log.txt ----- -----

17518  20230121   154000    154959  1674287399  22643.4  22642.9
2023-01-21 15:50:00,565:INFO:pyemd2:main.py:127:handleKline:185189: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=8216 

self.closeSec=1674287999, self.tradeDate='20230121', self.openTime='155000', self.closeTime='155959', self.symbol='BTCUSDT', self.open='22643.1', self.close='22631.6'
127.0.0.1 - - [21/Jan/2023 16:00:01] "POST / HTTP/1.1" 200 -
2023-01-21 16:00:01,392:INFO:pyemd2:main.py:125:handleKline:185189: self.closeSec=1674287999, self.tradeDate='20230121', self.openTime='155000', self.closeTime='155959',self.symbol='BTCUSDT',self.open='22643.1', self.close='22631.6'
2023-01-21 16:00:01,448:INFO:pyemd2:main.py:126:handleKline:185189: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17515  20230121   151000    151959  1674285599  22621.5    22622
17516  20230121   152000    152959  1674286199    22622  22633.1
17517  20230121   153000    153959  1674286799  22633.2  22643.4
17518  20230121   154000    154959  1674287399  22643.4  22642.9
17519  20230121   155000    155959  1674287999  22643.1  22631.6
2023-01-21 16:00:01,448:INFO:pyemd2:main.py:127:handleKline:185189: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=8217 

self.closeSec=1674288599, self.tradeDate='20230121', self.openTime='160000', self.closeTime='160959', self.symbol='BTCUSDT', self.open='22631.6', self.close='22691.6'
2023-01-21 16:10:01,543:INFO:pyemd2:main.py:125:handleKline:185189: self.closeSec=1674288599, self.tradeDate='20230121', self.openTime='160000', self.closeTime='160959',self.symbol='BTCUSDT',self.open='22631.6', self.close='22691.6'
127.0.0.1 - - [21/Jan/2023 16:10:01] "POST / HTTP/1.1" 200 -
2023-01-21 16:10:01,555:INFO:pyemd2:main.py:126:handleKline:185189: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17516  20230121   152000    152959  1674286199    22622  22633.1
17517  20230121   153000    153959  1674286799  22633.2  22643.4
17518  20230121   154000    154959  1674287399  22643.4  22642.9
17519  20230121   155000    155959  1674287999  22643.1  22631.6
17520  20230121   160000    160959  1674288599  22631.6  22691.6
2023-01-21 16:10:01,555:INFO:pyemd2:main.py:127:handleKline:185189: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}


## /root/FIL/strategy/similarity/log.txt ----- -----

12190  20230121   154000    154959  1674287399  22643.4  22642.9
2023-01-21 15:50:00,571:INFO:testStrategy:main.py:103:handleKline:185174: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': True, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=8216 

self.closeSec=1674287999, self.tradeDate='20230121', self.openTime='155000', self.closeTime='155959', self.symbol='BTCUSDT', self.open='22643.1', self.close='22631.6'
127.0.0.1 - - [21/Jan/2023 16:00:01] "POST / HTTP/1.1" 200 -
2023-01-21 16:00:01,404:INFO:testStrategy:main.py:101:handleKline:185174: self.closeSec=1674287999, self.tradeDate='20230121', self.openTime='155000', self.closeTime='155959',self.symbol='BTCUSDT',self.open='22643.1', self.close='22631.6'
2023-01-21 16:00:01,453:INFO:testStrategy:main.py:102:handleKline:185174: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12187  20230121   151000    151959  1674285599  22621.5    22622
12188  20230121   152000    152959  1674286199    22622  22633.1
12189  20230121   153000    153959  1674286799  22633.2  22643.4
12190  20230121   154000    154959  1674287399  22643.4  22642.9
12191  20230121   155000    155959  1674287999  22643.1  22631.6
2023-01-21 16:00:01,453:INFO:testStrategy:main.py:103:handleKline:185174: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': True, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}
127.0.0.1 - - [21/Jan/2023 16:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=8217 

self.closeSec=1674288599, self.tradeDate='20230121', self.openTime='160000', self.closeTime='160959', self.symbol='BTCUSDT', self.open='22631.6', self.close='22691.6'
2023-01-21 16:10:01,518:INFO:testStrategy:main.py:101:handleKline:185174: self.closeSec=1674288599, self.tradeDate='20230121', self.openTime='160000', self.closeTime='160959',self.symbol='BTCUSDT',self.open='22631.6', self.close='22691.6'
2023-01-21 16:10:01,524:INFO:testStrategy:main.py:102:handleKline:185174: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12188  20230121   152000    152959  1674286199    22622  22633.1
12189  20230121   153000    153959  1674286799  22633.2  22643.4
12190  20230121   154000    154959  1674287399  22643.4  22642.9
12191  20230121   155000    155959  1674287999  22643.1  22631.6
12192  20230121   160000    160959  1674288599  22631.6  22691.6
2023-01-21 16:10:01,524:INFO:testStrategy:main.py:103:handleKline:185174: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': True, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}


## /root/FIL/strategy/sr_min/log.txt ----- -----

127.0.0.1 - - [21/Jan/2023 16:10:01] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=0, self.total=1000000.0, self.flagDict['side']='', self.tradeCount=0, self.count=11864
self.closeSec=1674288599, self.tradeDate='20230121', self.openTime='160500', self.closeTime='160959', self.symbol='BTCUSDT', self.open=22658.4, self.close=22691.6, self.high=22699.4, self.low=22658.3, self.vol=3018.522, self.amt=68467139.2894 
2023-01-21 16:10:01,457:INFO:sr_min:main.py:172:handleKline:449472: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5949  20230121   154500    154959  ...         0.0        0.0       0
5950  20230121   155000    155459  ...         0.0        0.0       0
5951  20230121   155500    155959  ...         0.0        0.0       0
5952  20230121   160000    160459  ...         0.0        0.0       0
5953  20230121   160500    160959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-01-21 16:10:01,457:INFO:sr_min:main.py:175:handleKline:449472: self.closeSec=1674288599, self.tradeDate='20230121', self.openTime='160500', self.closeTime='160959',self.symbol='BTCUSDT',self.open=22658.4, self.close=22691.6, self.high=22699.4, self.low=22658.3, self.vol=3018.522, self.amt=68467139.2894, ukdf['pct'].iloc[-1]=0.00147 , ukdf['amount'].iloc[-1]=68467139.2894, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5953, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': []}
type(curSign)=<class 'int'>, curSign=0, self.sign=0
127.0.0.1 - - [21/Jan/2023 16:15:00] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=0, self.total=1000000.0, self.flagDict['side']='', self.tradeCount=0, self.count=11865
self.closeSec=1674288899, self.tradeDate='20230121', self.openTime='161000', self.closeTime='161459', self.symbol='BTCUSDT', self.open=22691.7, self.close=22735.8, self.high=22763.9, self.low=22680.3, self.vol=5828.445, self.amt=132437827.9518 
2023-01-21 16:15:00,644:INFO:sr_min:main.py:172:handleKline:449472: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5950  20230121   155000    155459  ...         0.0        0.0       0
5951  20230121   155500    155959  ...         0.0        0.0       0
5952  20230121   160000    160459  ...         0.0        0.0       0
5953  20230121   160500    160959  ...         0.0        0.0       0
5954  20230121   161000    161459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-01-21 16:15:00,645:INFO:sr_min:main.py:175:handleKline:449472: self.closeSec=1674288899, self.tradeDate='20230121', self.openTime='161000', self.closeTime='161459',self.symbol='BTCUSDT',self.open=22691.7, self.close=22735.8, self.high=22763.9, self.low=22680.3, self.vol=5828.445, self.amt=132437827.9518, ukdf['pct'].iloc[-1]=0.001948 , ukdf['amount'].iloc[-1]=132437827.9518, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5954, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': []}
type(curSign)=<class 'int'>, curSign=0, self.sign=0


## /root/FIL/strategy/s_rsrs/log.txt ----- -----

721  20230121   040000    075959  1674259199  ...    721  0.730974  0.021872     NaN
722  20230121   080000    115959  1674273599  ...    722  0.824589  0.221529     NaN

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '51.053', 'enterprice': '21166.9', 'countrevence': '0', 'unrealprofit': '-70280.53436245919', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '22543.51908923', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-9223372036854775808, self.sign=-1
--handleKline--:  version='2.0.0', self.name='s_rsrs', self.symbol='BTCUSDT', interval='4h', intervalSec=14400, wid=25, thd=0.6, self.sign=-1, self.total=1079553.1119543002, self.flagDict['side']='sell', self.tradeCount=13, self.count=342
self.closeSec=1674287999, self.tradeDate='20230121', self.openTime='120000', self.closeTime='155959', self.symbol='BTCUSDT', self.open=22541.8, self.close=22631.5, self.high=22678.6, self.low=22511.2, self.vol=32823.977, self.amt=741900083.2391 
127.0.0.1 - - [21/Jan/2023 16:00:01] "POST / HTTP/1.1" 200 -
2023-01-21 16:00:01,228:INFO:s_rsrs:main.py:141:handleKline:185271: self.closeSec=1674287999, self.tradeDate='20230121', self.openTime='120000', self.closeTime='155959',self.symbol='BTCUSDT',self.open=22541.8, self.close=22631.5, self.high=22678.6, self.low=22511.2, self.vol=32823.977, self.amt=741900083.2391 
2023-01-21 16:00:01,250:INFO:s_rsrs:main.py:142:handleKline:185271: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime  ...         vol           amt       pct
719  20230120   200000    235959  ...  103649.390  2.187745e+09  0.008689
720  20230121   000000    035959  ...  157134.305  3.354302e+09  0.016713
721  20230121   040000    075959  ...  326184.044  7.247155e+09  0.054501
722  20230121   080000    115959  ...   91102.531  2.057612e+09 -0.005414
723  20230121   120000    155959  ...   32823.977  7.419001e+08  0.003984

[5 rows x 11 columns]
2023-01-21 16:00:02,668:INFO:s_rsrs:main.py:151:handleKline:185271: df_s.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec  ...  index      beta    zscore  signal
719  20230120   200000    235959  1674230399  ...    719  0.158853 -1.270892    -1.0
720  20230121   000000    035959  1674244799  ...    720  0.194292 -1.172561    -1.0
721  20230121   040000    075959  1674259199  ...    721  0.730974  0.021872     NaN
722  20230121   080000    115959  1674273599  ...    722  0.824589  0.221529     NaN
723  20230121   120000    155959  1674287999  ...    723  0.778042  0.107792     NaN

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '51.053', 'enterprice': '21166.9', 'countrevence': '0', 'unrealprofit': '-74846.05986698112', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '22632.94626304', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-9223372036854775808, self.sign=-1


