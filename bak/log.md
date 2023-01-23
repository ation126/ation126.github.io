# 20230123 16:16:01

## /root/FIL/strategy/amihud/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=993672.4896432, self.flagDict['side']='sell', self.tradeCount=2, self.count=16442
self.closeSec=1674461399, self.tradeDate='20230123', self.openTime='160500', self.closeTime='160959', self.symbol='BTCUSDT', self.open=22700.5, self.close=22729.8, self.high=22731.6, self.low=22700.5, self.vol=1100.969, self.amt=25012281.4749 
127.0.0.1 - - [23/Jan/2023 16:10:01] "POST / HTTP/1.1" 200 -
2023-01-23 16:10:01,479:INFO:amihud:main.py:172:handleKline:200676: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5949  20230123   154500    154959  ...         0.0        0.0       0
5950  20230123   155000    155459  ...         0.0        0.0       0
5951  20230123   155500    155959  ...         0.0        0.0       0
5952  20230123   160000    160459  ...         0.0        0.0       0
5953  20230123   160500    160959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-01-23 16:10:01,479:INFO:amihud:main.py:175:handleKline:200676: self.closeSec=1674461399, self.tradeDate='20230123', self.openTime='160500', self.closeTime='160959',self.symbol='BTCUSDT',self.open=22700.5, self.close=22729.8, self.high=22731.6, self.low=22700.5, self.vol=1100.969, self.amt=25012281.4749, ukdf['pct'].iloc[-1]=0.001291 , ukdf['amount'].iloc[-1]=25012281.4749, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5953, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '60.176', 'enterprice': '16529.3', 'countrevence': '0', 'unrealprofit': '-373164.63321750064', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '22730.52030739', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1
127.0.0.1 - - [23/Jan/2023 16:15:00] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=993672.4896432, self.flagDict['side']='sell', self.tradeCount=2, self.count=16443
self.closeSec=1674461699, self.tradeDate='20230123', self.openTime='161000', self.closeTime='161459', self.symbol='BTCUSDT', self.open=22729.9, self.close=22740.9, self.high=22752.9, self.low=22728.0, self.vol=1082.287, self.amt=24612829.1949 
2023-01-23 16:15:01,023:INFO:amihud:main.py:172:handleKline:200676: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5950  20230123   155000    155459  ...         0.0        0.0       0
5951  20230123   155500    155959  ...         0.0        0.0       0
5952  20230123   160000    160459  ...         0.0        0.0       0
5953  20230123   160500    160959  ...         0.0        0.0       0
5954  20230123   161000    161459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-01-23 16:15:01,023:INFO:amihud:main.py:175:handleKline:200676: self.closeSec=1674461699, self.tradeDate='20230123', self.openTime='161000', self.closeTime='161459',self.symbol='BTCUSDT',self.open=22729.9, self.close=22740.9, self.high=22752.9, self.low=22728.0, self.vol=1082.287, self.amt=24612829.1949, ukdf['pct'].iloc[-1]=0.000488 , ukdf['amount'].iloc[-1]=24612829.1949, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5954, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '60.176', 'enterprice': '16529.3', 'countrevence': '0', 'unrealprofit': '-373805.5532615984', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '22741.1710659', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1


## /root/FIL/strategy/factorcheck/log.txt ----- -----

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=125, self.factor=0.5288510731499377, self.count=17008 

self.closeSec=1674461399, self.tradeDate='20230123', self.openTime='160500', self.closeTime='160959', self.symbol='BTCUSDT', self.open=22700.5, self.close=22729.8, self.high=22731.6, self.low=22700.5 
2023-01-23 16:10:01,436:INFO:factorcheck2:main.py:126:handleKline:185239: self.closeSec=1674461399, self.tradeDate='20230123', self.openTime='160500', self.closeTime='160959',self.symbol='BTCUSDT',self.open=22700.5, self.close=22729.8, self.high=22731.6, self.low=22700.5   
2023-01-23 16:10:01,475:INFO:factorcheck2:main.py:127:handleKline:185239: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1629  20230123   154500    154959  1674460199  ...  22683.3 -0.000964   1629    3
1630  20230123   155000    155459  1674460499  ...  22680.0  0.000141   1630    4
1631  20230123   155500    155959  1674460799  ...  22669.0  0.000185   1631    5
1632  20230123   160000    160459  1674461099  ...  22661.9  0.000357   1632    0
1633  20230123   160500    160959  1674461399  ...  22700.5  0.001291   1633    1

[5 rows x 11 columns]
2023-01-23 16:10:01,475:INFO:factorcheck2:main.py:128:handleKline:185239: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=125, self.factor=0.5288510731499377, self.count=17009 

self.closeSec=1674461699, self.tradeDate='20230123', self.openTime='161000', self.closeTime='161459', self.symbol='BTCUSDT', self.open=22729.9, self.close=22740.9, self.high=22752.9, self.low=22728.0 
2023-01-23 16:15:00,993:INFO:factorcheck2:main.py:126:handleKline:185239: self.closeSec=1674461699, self.tradeDate='20230123', self.openTime='161000', self.closeTime='161459',self.symbol='BTCUSDT',self.open=22729.9, self.close=22740.9, self.high=22752.9, self.low=22728.0   
127.0.0.1 - - [23/Jan/2023 16:15:00] "POST / HTTP/1.1" 200 -
2023-01-23 16:15:01,028:INFO:factorcheck2:main.py:127:handleKline:185239: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1630  20230123   155000    155459  1674460499  ...  22680.0  0.000141   1630    4
1631  20230123   155500    155959  1674460799  ...  22669.0  0.000185   1631    5
1632  20230123   160000    160459  1674461099  ...  22661.9  0.000357   1632    0
1633  20230123   160500    160959  1674461399  ...  22700.5  0.001291   1633    1
1634  20230123   161000    161459  1674461699  ...  22728.0  0.000488   1634    2

[5 rows x 11 columns]
2023-01-23 16:15:01,028:INFO:factorcheck2:main.py:128:handleKline:185239: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}


## /root/FIL/strategy/logic/log.txt ----- -----

2023-01-23 16:00:18,989:DEBUG:logic:main.py:463:getModel:885513: df_s.iloc[-5:,:] :
          date closeTime     open  ...    alpha58   alpha67   alpha72
5786  20230123    132959  22756.0  ...  55.000000  0.523050  0.519754
5787  20230123    135959  22748.7  ...  54.583333  0.517884  0.515260
5788  20230123    142959  22721.4  ...  55.000000  0.519675  0.510217
5789  20230123    145959  22731.5  ...  55.416667  0.527111  0.501988
5790  20230123    152959  22773.4  ...  55.000000  0.509255  0.502125

[5 rows x 33 columns]
0.5276752767527675
acc is : 0.5276752767527675
2023-01-23 16:00:19,062:INFO:logic:main.py:468:getModel:885513: df_pred.iloc[-5:,:] :
     pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
537     0  0.510077  0.489923       0  ...  1.006372  -1.0    0.0  1.244054
538     0  0.506410  0.493590       1  ...  1.005925  -1.0    0.0  1.244607
539     0  0.522615  0.477385       1  ...  1.004070  -1.0    0.0  1.246901
540     0  0.529845  0.470155       0  ...  1.008171  -1.0    0.0  1.241809
541     1  0.488103  0.511897       1  ...  1.007637  -1.0    0.0  1.242466

[5 rows x 10 columns]
2023-01-23 16:00:19,073:INFO:logic:main.py:478:getModel:885513: df_panel.iloc[-5:,:] :
    pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
45     0  0.508606  0.491394       0  ...  1.093969  -1.0    0.0  1.294814
46     0  0.505532  0.494468       1  ...  1.093483  -1.0    0.0  1.288451
47     0  0.522047  0.477953       1  ...  1.022457  -1.0    0.0  1.269725
48     0  0.529973  0.470027       0  ...  1.025904  -1.0    0.0  1.263609
49     1  0.488103  0.511897       1  ...  1.007637  -1.0    0.0  1.242466

[5 rows x 10 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '33.678', 'enterprice': '22437.6', 'countrevence': '0', 'unrealprofit': '-8668.7172', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '22695', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}


## /root/FIL/strategy/modifiedmom/log.txt ----- -----

526  20230123   154000    154959  1674460199    22704  22683.1 -0.000925
2023-01-23 15:50:00,558:INFO:modifiedmom:main.py:146:handleKline:185213: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True}
127.0.0.1 - - [23/Jan/2023 16:00:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=8503 

self.closeSec=1674460799, self.tradeDate='20230123', self.openTime='155000', self.closeTime='155959', self.symbol='BTCUSDT', self.open='22683', self.close='22692.4'
2023-01-23 16:00:01,882:INFO:modifiedmom:main.py:144:handleKline:185213: self.closeSec=1674460799, self.tradeDate='20230123', self.openTime='155000', self.closeTime='155959',self.symbol='BTCUSDT',self.open='22683', self.close='22692.4'
2023-01-23 16:00:01,913:INFO:modifiedmom:main.py:145:handleKline:185213: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
523  20230123   151000    151959  1674458399    22754    22755  0.000040
524  20230123   152000    152959  1674458999    22755  22680.4 -0.003278
525  20230123   153000    153959  1674459599  22680.2  22704.1  0.001045
526  20230123   154000    154959  1674460199    22704  22683.1 -0.000925
527  20230123   155000    155959  1674460799    22683  22692.4  0.000410
2023-01-23 16:00:01,913:INFO:modifiedmom:main.py:146:handleKline:185213: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True}

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=8504 

self.closeSec=1674461399, self.tradeDate='20230123', self.openTime='160000', self.closeTime='160959', self.symbol='BTCUSDT', self.open='22692.4', self.close='22729.8'
2023-01-23 16:10:01,521:INFO:modifiedmom:main.py:144:handleKline:185213: self.closeSec=1674461399, self.tradeDate='20230123', self.openTime='160000', self.closeTime='160959',self.symbol='BTCUSDT',self.open='22692.4', self.close='22729.8'
127.0.0.1 - - [23/Jan/2023 16:10:01] "POST / HTTP/1.1" 200 -
2023-01-23 16:10:01,546:INFO:modifiedmom:main.py:145:handleKline:185213: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
524  20230123   152000    152959  1674458999    22755  22680.4 -0.003278
525  20230123   153000    153959  1674459599  22680.2  22704.1  0.001045
526  20230123   154000    154959  1674460199    22704  22683.1 -0.000925
527  20230123   155000    155959  1674460799    22683  22692.4  0.000410
528  20230123   160000    160959  1674461399  22692.4  22729.8  0.001648
2023-01-23 16:10:01,546:INFO:modifiedmom:main.py:146:handleKline:185213: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True}


## /root/FIL/strategy/pyemd/log.txt ----- -----

17518  20230123   154000    154959  1674460199    22704  22683.1
2023-01-23 15:50:00,552:INFO:pyemd2:main.py:127:handleKline:185189: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}
127.0.0.1 - - [23/Jan/2023 16:00:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=8504 

self.closeSec=1674460799, self.tradeDate='20230123', self.openTime='155000', self.closeTime='155959', self.symbol='BTCUSDT', self.open='22683', self.close='22692.4'
2023-01-23 16:00:01,931:INFO:pyemd2:main.py:125:handleKline:185189: self.closeSec=1674460799, self.tradeDate='20230123', self.openTime='155000', self.closeTime='155959',self.symbol='BTCUSDT',self.open='22683', self.close='22692.4'
2023-01-23 16:00:01,974:INFO:pyemd2:main.py:126:handleKline:185189: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17515  20230123   151000    151959  1674458399    22754    22755
17516  20230123   152000    152959  1674458999    22755  22680.4
17517  20230123   153000    153959  1674459599  22680.2  22704.1
17518  20230123   154000    154959  1674460199    22704  22683.1
17519  20230123   155000    155959  1674460799    22683  22692.4
2023-01-23 16:00:01,975:INFO:pyemd2:main.py:127:handleKline:185189: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}
127.0.0.1 - - [23/Jan/2023 16:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=8505 

self.closeSec=1674461399, self.tradeDate='20230123', self.openTime='160000', self.closeTime='160959', self.symbol='BTCUSDT', self.open='22692.4', self.close='22729.8'
2023-01-23 16:10:01,539:INFO:pyemd2:main.py:125:handleKline:185189: self.closeSec=1674461399, self.tradeDate='20230123', self.openTime='160000', self.closeTime='160959',self.symbol='BTCUSDT',self.open='22692.4', self.close='22729.8'
2023-01-23 16:10:01,550:INFO:pyemd2:main.py:126:handleKline:185189: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17516  20230123   152000    152959  1674458999    22755  22680.4
17517  20230123   153000    153959  1674459599  22680.2  22704.1
17518  20230123   154000    154959  1674460199    22704  22683.1
17519  20230123   155000    155959  1674460799    22683  22692.4
17520  20230123   160000    160959  1674461399  22692.4  22729.8
2023-01-23 16:10:01,550:INFO:pyemd2:main.py:127:handleKline:185189: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}


## /root/FIL/strategy/similarity/log.txt ----- -----

12190  20230123   154000    154959  1674460199    22704  22683.1
2023-01-23 15:50:00,559:INFO:testStrategy:main.py:103:handleKline:185174: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=8504 

self.closeSec=1674460799, self.tradeDate='20230123', self.openTime='155000', self.closeTime='155959', self.symbol='BTCUSDT', self.open='22683', self.close='22692.4'
127.0.0.1 - - [23/Jan/2023 16:00:01] "POST / HTTP/1.1" 200 -
2023-01-23 16:00:01,903:INFO:testStrategy:main.py:101:handleKline:185174: self.closeSec=1674460799, self.tradeDate='20230123', self.openTime='155000', self.closeTime='155959',self.symbol='BTCUSDT',self.open='22683', self.close='22692.4'
2023-01-23 16:00:01,926:INFO:testStrategy:main.py:102:handleKline:185174: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12187  20230123   151000    151959  1674458399    22754    22755
12188  20230123   152000    152959  1674458999    22755  22680.4
12189  20230123   153000    153959  1674459599  22680.2  22704.1
12190  20230123   154000    154959  1674460199    22704  22683.1
12191  20230123   155000    155959  1674460799    22683  22692.4
2023-01-23 16:00:01,926:INFO:testStrategy:main.py:103:handleKline:185174: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}
127.0.0.1 - - [23/Jan/2023 16:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=8505 

self.closeSec=1674461399, self.tradeDate='20230123', self.openTime='160000', self.closeTime='160959', self.symbol='BTCUSDT', self.open='22692.4', self.close='22729.8'
2023-01-23 16:10:01,546:INFO:testStrategy:main.py:101:handleKline:185174: self.closeSec=1674461399, self.tradeDate='20230123', self.openTime='160000', self.closeTime='160959',self.symbol='BTCUSDT',self.open='22692.4', self.close='22729.8'
2023-01-23 16:10:01,551:INFO:testStrategy:main.py:102:handleKline:185174: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12188  20230123   152000    152959  1674458999    22755  22680.4
12189  20230123   153000    153959  1674459599  22680.2  22704.1
12190  20230123   154000    154959  1674460199    22704  22683.1
12191  20230123   155000    155959  1674460799    22683  22692.4
12192  20230123   160000    160959  1674461399  22692.4  22729.8
2023-01-23 16:10:01,551:INFO:testStrategy:main.py:103:handleKline:185174: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}


## /root/FIL/strategy/sr_min/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=0, self.total=1000000.0, self.flagDict['side']='', self.tradeCount=0, self.count=12440
self.closeSec=1674461399, self.tradeDate='20230123', self.openTime='160500', self.closeTime='160959', self.symbol='BTCUSDT', self.open=22700.5, self.close=22729.8, self.high=22731.6, self.low=22700.5, self.vol=1100.969, self.amt=25012281.4749 
127.0.0.1 - - [23/Jan/2023 16:10:01] "POST / HTTP/1.1" 200 -
2023-01-23 16:10:01,488:INFO:sr_min:main.py:172:handleKline:449472: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5949  20230123   154500    154959  ...         0.0        0.0       0
5950  20230123   155000    155459  ...         0.0        0.0       0
5951  20230123   155500    155959  ...         0.0        0.0       0
5952  20230123   160000    160459  ...         0.0        0.0       0
5953  20230123   160500    160959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-01-23 16:10:01,490:INFO:sr_min:main.py:175:handleKline:449472: self.closeSec=1674461399, self.tradeDate='20230123', self.openTime='160500', self.closeTime='160959',self.symbol='BTCUSDT',self.open=22700.5, self.close=22729.8, self.high=22731.6, self.low=22700.5, self.vol=1100.969, self.amt=25012281.4749, ukdf['pct'].iloc[-1]=0.001291 , ukdf['amount'].iloc[-1]=25012281.4749, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5953, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': []}
type(curSign)=<class 'int'>, curSign=0, self.sign=0
--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=0, self.total=1000000.0, self.flagDict['side']='', self.tradeCount=0, self.count=12441
self.closeSec=1674461699, self.tradeDate='20230123', self.openTime='161000', self.closeTime='161459', self.symbol='BTCUSDT', self.open=22729.9, self.close=22740.9, self.high=22752.9, self.low=22728.0, self.vol=1082.287, self.amt=24612829.1949 
127.0.0.1 - - [23/Jan/2023 16:15:00] "POST / HTTP/1.1" 200 -
2023-01-23 16:15:01,040:INFO:sr_min:main.py:172:handleKline:449472: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5950  20230123   155000    155459  ...         0.0        0.0       0
5951  20230123   155500    155959  ...         0.0        0.0       0
5952  20230123   160000    160459  ...         0.0        0.0       0
5953  20230123   160500    160959  ...         0.0        0.0       0
5954  20230123   161000    161459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-01-23 16:15:01,040:INFO:sr_min:main.py:175:handleKline:449472: self.closeSec=1674461699, self.tradeDate='20230123', self.openTime='161000', self.closeTime='161459',self.symbol='BTCUSDT',self.open=22729.9, self.close=22740.9, self.high=22752.9, self.low=22728.0, self.vol=1082.287, self.amt=24612829.1949, ukdf['pct'].iloc[-1]=0.000488 , ukdf['amount'].iloc[-1]=24612829.1949, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5954, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': []}
type(curSign)=<class 'int'>, curSign=0, self.sign=0


## /root/FIL/strategy/s_rsrs/log.txt ----- -----

721  20230123   040000    075959  1674431999  ...    721  1.092073  0.673076     1.0
722  20230123   080000    115959  1674446399  ...    722  1.069849  0.604791     1.0

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '41.799', 'enterprice': '23284.2', 'countrevence': '0', 'unrealprofit': '-25916.8835392893', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '22664.1640293', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=1, self.sign=1
--handleKline--:  version='2.0.0', self.name='s_rsrs', self.symbol='BTCUSDT', interval='4h', intervalSec=14400, wid=25, thd=0.6, self.sign=1, self.total=972283.0195242, self.flagDict['side']='buy', self.tradeCount=14, self.count=354
self.closeSec=1674460799, self.tradeDate='20230123', self.openTime='120000', self.closeTime='155959', self.symbol='BTCUSDT', self.open=22657.6, self.close=22692.4, self.high=22793.3, self.low=22596.8, self.vol=36713.329, self.amt=833929122.8896 
127.0.0.1 - - [23/Jan/2023 16:00:01] "POST / HTTP/1.1" 200 -
2023-01-23 16:00:01,706:INFO:s_rsrs:main.py:141:handleKline:185271: self.closeSec=1674460799, self.tradeDate='20230123', self.openTime='120000', self.closeTime='155959',self.symbol='BTCUSDT',self.open=22657.6, self.close=22692.4, self.high=22793.3, self.low=22596.8, self.vol=36713.329, self.amt=833929122.8896 
2023-01-23 16:00:01,734:INFO:s_rsrs:main.py:142:handleKline:185271: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime  ...         vol           amt       pct
719  20230122   200000    235959  ...  106357.240  2.431628e+09  0.000325
720  20230123   000000    035959  ...   72710.666  1.660094e+09 -0.003198
721  20230123   040000    075959  ...  139693.559  3.148397e+09 -0.000643
722  20230123   080000    115959  ...   47573.102  1.081411e+09 -0.002105
723  20230123   120000    155959  ...   36713.329  8.339291e+08  0.001536

[5 rows x 11 columns]
2023-01-23 16:00:03,188:INFO:s_rsrs:main.py:151:handleKline:185271: df_s.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec  ...  index      beta    zscore  signal
719  20230122   200000    235959  1674403199  ...    719  0.986552  0.464280     NaN
720  20230123   000000    035959  1674417599  ...    720  1.022171  0.530393     NaN
721  20230123   040000    075959  1674431999  ...    721  1.092073  0.673076     1.0
722  20230123   080000    115959  1674446399  ...    722  1.069849  0.604791     1.0
723  20230123   120000    155959  1674460799  ...    723  1.032809  0.501858     NaN

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '41.799', 'enterprice': '23284.2', 'countrevence': '0', 'unrealprofit': '-24740.8281', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '22692.3', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-9223372036854775808, self.sign=1


