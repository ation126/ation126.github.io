# 20230122 16:16:01

## /root/FIL/strategy/amihud/log.txt ----- -----

127.0.0.1 - - [22/Jan/2023 16:10:01] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=993672.4896432, self.flagDict['side']='sell', self.tradeCount=2, self.count=16154
self.closeSec=1674374999, self.tradeDate='20230122', self.openTime='160500', self.closeTime='160959', self.symbol='BTCUSDT', self.open=22884.4, self.close=22871.6, self.high=22884.5, self.low=22846.4, self.vol=1482.938, self.amt=33906185.631 
2023-01-22 16:10:01,510:INFO:amihud:main.py:172:handleKline:200676: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5949  20230122   154500    154959  ...         0.0        0.0       0
5950  20230122   155000    155459  ...         0.0        0.0       0
5951  20230122   155500    155959  ...         0.0        0.0       0
5952  20230122   160000    160459  ...         0.0        0.0       0
5953  20230122   160500    160959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-01-22 16:10:01,510:INFO:amihud:main.py:175:handleKline:200676: self.closeSec=1674374999, self.tradeDate='20230122', self.openTime='160500', self.closeTime='160959',self.symbol='BTCUSDT',self.open=22884.4, self.close=22871.6, self.high=22884.5, self.low=22846.4, self.vol=1482.938, self.amt=33906185.631, ukdf['pct'].iloc[-1]=-0.000564 , ukdf['amount'].iloc[-1]=33906185.631, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5953, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '60.176', 'enterprice': '16529.3', 'countrevence': '0', 'unrealprofit': '-381510.75317047472', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '22869.21546747', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1
127.0.0.1 - - [22/Jan/2023 16:15:00] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=993672.4896432, self.flagDict['side']='sell', self.tradeCount=2, self.count=16155
self.closeSec=1674375299, self.tradeDate='20230122', self.openTime='161000', self.closeTime='161459', self.symbol='BTCUSDT', self.open=22871.7, self.close=22845.6, self.high=22872.7, self.low=22828.0, self.vol=1681.775, self.amt=38418652.1699 
2023-01-22 16:15:00,750:INFO:amihud:main.py:172:handleKline:200676: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5950  20230122   155000    155459  ...         0.0        0.0       0
5951  20230122   155500    155959  ...         0.0        0.0       0
5952  20230122   160000    160459  ...         0.0        0.0       0
5953  20230122   160500    160959  ...         0.0        0.0       0
5954  20230122   161000    161459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-01-22 16:15:00,750:INFO:amihud:main.py:175:handleKline:200676: self.closeSec=1674375299, self.tradeDate='20230122', self.openTime='161000', self.closeTime='161459',self.symbol='BTCUSDT',self.open=22871.7, self.close=22845.6, self.high=22872.7, self.low=22828.0, self.vol=1681.775, self.amt=38418652.1699, ukdf['pct'].iloc[-1]=-0.001137 , ukdf['amount'].iloc[-1]=38418652.1699, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5954, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '60.176', 'enterprice': '16529.3', 'countrevence': '0', 'unrealprofit': '-380089.6688', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '22845.6', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1


## /root/FIL/strategy/factorcheck/log.txt ----- -----

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=77, self.factor=0.3736517494635846, self.count=16720 

self.closeSec=1674374999, self.tradeDate='20230122', self.openTime='160500', self.closeTime='160959', self.symbol='BTCUSDT', self.open=22884.4, self.close=22871.6, self.high=22884.5, self.low=22846.4 
2023-01-22 16:10:01,456:INFO:factorcheck2:main.py:126:handleKline:185239: self.closeSec=1674374999, self.tradeDate='20230122', self.openTime='160500', self.closeTime='160959',self.symbol='BTCUSDT',self.open=22884.4, self.close=22871.6, self.high=22884.5, self.low=22846.4   
2023-01-22 16:10:01,506:INFO:factorcheck2:main.py:127:handleKline:185239: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1629  20230122   154500    154959  1674373799  ...  22886.8 -0.000061   1629    3
1630  20230122   155000    155459  1674374099  ...  22890.4  0.000581   1630    4
1631  20230122   155500    155959  1674374399  ...  22891.5 -0.000581   1631    5
1632  20230122   160000    160459  1674374699  ...  22874.3 -0.000380   1632    0
1633  20230122   160500    160959  1674374999  ...  22846.4 -0.000564   1633    1

[5 rows x 11 columns]
2023-01-22 16:10:01,506:INFO:factorcheck2:main.py:128:handleKline:185239: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}
127.0.0.1 - - [22/Jan/2023 16:15:00] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=77, self.factor=0.3736517494635846, self.count=16721 

self.closeSec=1674375299, self.tradeDate='20230122', self.openTime='161000', self.closeTime='161459', self.symbol='BTCUSDT', self.open=22871.7, self.close=22845.6, self.high=22872.7, self.low=22828.0 
2023-01-22 16:15:00,706:INFO:factorcheck2:main.py:126:handleKline:185239: self.closeSec=1674375299, self.tradeDate='20230122', self.openTime='161000', self.closeTime='161459',self.symbol='BTCUSDT',self.open=22871.7, self.close=22845.6, self.high=22872.7, self.low=22828.0   
2023-01-22 16:15:00,728:INFO:factorcheck2:main.py:127:handleKline:185239: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1630  20230122   155000    155459  1674374099  ...  22890.4  0.000581   1630    4
1631  20230122   155500    155959  1674374399  ...  22891.5 -0.000581   1631    5
1632  20230122   160000    160459  1674374699  ...  22874.3 -0.000380   1632    0
1633  20230122   160500    160959  1674374999  ...  22846.4 -0.000564   1633    1
1634  20230122   161000    161459  1674375299  ...  22828.0 -0.001137   1634    2

[5 rows x 11 columns]
2023-01-22 16:15:00,728:INFO:factorcheck2:main.py:128:handleKline:185239: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}


## /root/FIL/strategy/logic/log.txt ----- -----

2023-01-22 16:00:18,623:DEBUG:logic:main.py:463:getModel:885513: df_s.iloc[-5:,:] :
          date closeTime     open  ...    alpha58   alpha67   alpha72
5786  20230122    132959  22849.8  ...  54.583333  0.574959  0.502142
5787  20230122    135959  22860.0  ...  54.583333  0.577585  0.509432
5788  20230122    142959  22879.4  ...  55.000000  0.583138  0.512947
5789  20230122    145959  22920.6  ...  55.416667  0.583233  0.518314
5790  20230122    152959  22921.3  ...  55.000000  0.581919  0.523896

[5 rows x 33 columns]
0.525830258302583
acc is : 0.525830258302583
2023-01-22 16:00:18,712:INFO:logic:main.py:468:getModel:885513: df_pred.iloc[-5:,:] :
     pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
537     0  0.525174  0.474826       1  ...  1.131167  -1.0    0.0  1.310637
538     0  0.523867  0.476133       1  ...  1.129130  -1.0    0.0  1.312997
539     0  0.529318  0.470682       1  ...  1.129096  -1.0    0.0  1.313037
540     0  0.522203  0.477797       0  ...  1.129431  -1.0    0.0  1.312648
541     0  0.513695  0.486305       0  ...  1.130480  -1.0    0.0  1.311428

[5 rows x 10 columns]
2023-01-22 16:00:18,734:INFO:logic:main.py:478:getModel:885513: df_panel.iloc[-5:,:] :
    pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
45     0  0.525176  0.474824       1  ...  1.131167  -1.0    0.0  1.313406
46     0  0.523999  0.476001       1  ...  1.129130  -1.0    0.0  1.315567
47     0  0.529522  0.470478       1  ...  1.129096  -1.0    0.0  1.315139
48     0  0.522789  0.477211       0  ...  1.129431  -1.0    0.0  1.315119
49     0  0.513695  0.486305       0  ...  1.130480  -1.0    0.0  1.311428

[5 rows x 10 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '33.659', 'enterprice': '22798.2', 'countrevence': '0', 'unrealprofit': '-3012.12387784615', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '22887.68940485', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}


## /root/FIL/strategy/modifiedmom/log.txt ----- -----

526  20230122   154000    154959  1674373799  22894.3  22893.2 -0.000100
2023-01-22 15:50:00,581:INFO:modifiedmom:main.py:146:handleKline:185213: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True}

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=8359 

self.closeSec=1674374399, self.tradeDate='20230122', self.openTime='155000', self.closeTime='155959', self.symbol='BTCUSDT', self.open='22893.9', self.close='22893.2'
127.0.0.1 - - [22/Jan/2023 16:00:01] "POST / HTTP/1.1" 200 -
2023-01-22 16:00:01,719:INFO:modifiedmom:main.py:144:handleKline:185213: self.closeSec=1674374399, self.tradeDate='20230122', self.openTime='155000', self.closeTime='155959',self.symbol='BTCUSDT',self.open='22893.9', self.close='22893.2'
2023-01-22 16:00:01,771:INFO:modifiedmom:main.py:145:handleKline:185213: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
523  20230122   151000    151959  1674371999  22925.5  22933.7  0.000353
524  20230122   152000    152959  1674372599  22933.7  22914.5 -0.000837
525  20230122   153000    153959  1674373199  22914.6  22895.5 -0.000829
526  20230122   154000    154959  1674373799  22894.3  22893.2 -0.000100
527  20230122   155000    155959  1674374399  22893.9  22893.2  0.000000
2023-01-22 16:00:01,771:INFO:modifiedmom:main.py:146:handleKline:185213: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True}

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=8360 

self.closeSec=1674374999, self.tradeDate='20230122', self.openTime='160000', self.closeTime='160959', self.symbol='BTCUSDT', self.open='22893.2', self.close='22871.6'
127.0.0.1 - - [22/Jan/2023 16:10:01] "POST / HTTP/1.1" 200 -
2023-01-22 16:10:01,525:INFO:modifiedmom:main.py:144:handleKline:185213: self.closeSec=1674374999, self.tradeDate='20230122', self.openTime='160000', self.closeTime='160959',self.symbol='BTCUSDT',self.open='22893.2', self.close='22871.6'
2023-01-22 16:10:01,557:INFO:modifiedmom:main.py:145:handleKline:185213: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
524  20230122   152000    152959  1674372599  22933.7  22914.5 -0.000837
525  20230122   153000    153959  1674373199  22914.6  22895.5 -0.000829
526  20230122   154000    154959  1674373799  22894.3  22893.2 -0.000100
527  20230122   155000    155959  1674374399  22893.9  22893.2  0.000000
528  20230122   160000    160959  1674374999  22893.2  22871.6 -0.000944
2023-01-22 16:10:01,557:INFO:modifiedmom:main.py:146:handleKline:185213: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True}


## /root/FIL/strategy/pyemd/log.txt ----- -----

17518  20230122   154000    154959  1674373799  22894.3  22893.2
2023-01-22 15:50:00,596:INFO:pyemd2:main.py:127:handleKline:185189: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}
127.0.0.1 - - [22/Jan/2023 16:00:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=8360 

self.closeSec=1674374399, self.tradeDate='20230122', self.openTime='155000', self.closeTime='155959', self.symbol='BTCUSDT', self.open='22893.9', self.close='22893.2'
2023-01-22 16:00:01,707:INFO:pyemd2:main.py:125:handleKline:185189: self.closeSec=1674374399, self.tradeDate='20230122', self.openTime='155000', self.closeTime='155959',self.symbol='BTCUSDT',self.open='22893.9', self.close='22893.2'
2023-01-22 16:00:01,776:INFO:pyemd2:main.py:126:handleKline:185189: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17515  20230122   151000    151959  1674371999  22925.5  22933.7
17516  20230122   152000    152959  1674372599  22933.7  22914.5
17517  20230122   153000    153959  1674373199  22914.6  22895.5
17518  20230122   154000    154959  1674373799  22894.3  22893.2
17519  20230122   155000    155959  1674374399  22893.9  22893.2
2023-01-22 16:00:01,776:INFO:pyemd2:main.py:127:handleKline:185189: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}
127.0.0.1 - - [22/Jan/2023 16:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=8361 

self.closeSec=1674374999, self.tradeDate='20230122', self.openTime='160000', self.closeTime='160959', self.symbol='BTCUSDT', self.open='22893.2', self.close='22871.6'
2023-01-22 16:10:01,539:INFO:pyemd2:main.py:125:handleKline:185189: self.closeSec=1674374999, self.tradeDate='20230122', self.openTime='160000', self.closeTime='160959',self.symbol='BTCUSDT',self.open='22893.2', self.close='22871.6'
2023-01-22 16:10:01,566:INFO:pyemd2:main.py:126:handleKline:185189: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17516  20230122   152000    152959  1674372599  22933.7  22914.5
17517  20230122   153000    153959  1674373199  22914.6  22895.5
17518  20230122   154000    154959  1674373799  22894.3  22893.2
17519  20230122   155000    155959  1674374399  22893.9  22893.2
17520  20230122   160000    160959  1674374999  22893.2  22871.6
2023-01-22 16:10:01,566:INFO:pyemd2:main.py:127:handleKline:185189: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}


## /root/FIL/strategy/similarity/log.txt ----- -----

12190  20230122   154000    154959  1674373799  22894.3  22893.2
2023-01-22 15:50:00,588:INFO:testStrategy:main.py:103:handleKline:185174: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=8360 

self.closeSec=1674374399, self.tradeDate='20230122', self.openTime='155000', self.closeTime='155959', self.symbol='BTCUSDT', self.open='22893.9', self.close='22893.2'
127.0.0.1 - - [22/Jan/2023 16:00:01] "POST / HTTP/1.1" 200 -
2023-01-22 16:00:01,732:INFO:testStrategy:main.py:101:handleKline:185174: self.closeSec=1674374399, self.tradeDate='20230122', self.openTime='155000', self.closeTime='155959',self.symbol='BTCUSDT',self.open='22893.9', self.close='22893.2'
2023-01-22 16:00:01,782:INFO:testStrategy:main.py:102:handleKline:185174: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12187  20230122   151000    151959  1674371999  22925.5  22933.7
12188  20230122   152000    152959  1674372599  22933.7  22914.5
12189  20230122   153000    153959  1674373199  22914.6  22895.5
12190  20230122   154000    154959  1674373799  22894.3  22893.2
12191  20230122   155000    155959  1674374399  22893.9  22893.2
2023-01-22 16:00:01,782:INFO:testStrategy:main.py:103:handleKline:185174: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}
127.0.0.1 - - [22/Jan/2023 16:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=8361 

self.closeSec=1674374999, self.tradeDate='20230122', self.openTime='160000', self.closeTime='160959', self.symbol='BTCUSDT', self.open='22893.2', self.close='22871.6'
2023-01-22 16:10:01,540:INFO:testStrategy:main.py:101:handleKline:185174: self.closeSec=1674374999, self.tradeDate='20230122', self.openTime='160000', self.closeTime='160959',self.symbol='BTCUSDT',self.open='22893.2', self.close='22871.6'
2023-01-22 16:10:01,559:INFO:testStrategy:main.py:102:handleKline:185174: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12188  20230122   152000    152959  1674372599  22933.7  22914.5
12189  20230122   153000    153959  1674373199  22914.6  22895.5
12190  20230122   154000    154959  1674373799  22894.3  22893.2
12191  20230122   155000    155959  1674374399  22893.9  22893.2
12192  20230122   160000    160959  1674374999  22893.2  22871.6
2023-01-22 16:10:01,560:INFO:testStrategy:main.py:103:handleKline:185174: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}


## /root/FIL/strategy/sr_min/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=0, self.total=1000000.0, self.flagDict['side']='', self.tradeCount=0, self.count=12152
self.closeSec=1674374999, self.tradeDate='20230122', self.openTime='160500', self.closeTime='160959', self.symbol='BTCUSDT', self.open=22884.4, self.close=22871.6, self.high=22884.5, self.low=22846.4, self.vol=1482.938, self.amt=33906185.631 
127.0.0.1 - - [22/Jan/2023 16:10:01] "POST / HTTP/1.1" 200 -
2023-01-22 16:10:01,482:INFO:sr_min:main.py:172:handleKline:449472: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5949  20230122   154500    154959  ...         0.0        0.0       0
5950  20230122   155000    155459  ...         0.0        0.0       0
5951  20230122   155500    155959  ...         0.0        0.0       0
5952  20230122   160000    160459  ...         0.0        0.0       0
5953  20230122   160500    160959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-01-22 16:10:01,483:INFO:sr_min:main.py:175:handleKline:449472: self.closeSec=1674374999, self.tradeDate='20230122', self.openTime='160500', self.closeTime='160959',self.symbol='BTCUSDT',self.open=22884.4, self.close=22871.6, self.high=22884.5, self.low=22846.4, self.vol=1482.938, self.amt=33906185.631, ukdf['pct'].iloc[-1]=-0.000564 , ukdf['amount'].iloc[-1]=33906185.631, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5953, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': []}
type(curSign)=<class 'int'>, curSign=0, self.sign=0
--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=0, self.total=1000000.0, self.flagDict['side']='', self.tradeCount=0, self.count=12153
self.closeSec=1674375299, self.tradeDate='20230122', self.openTime='161000', self.closeTime='161459', self.symbol='BTCUSDT', self.open=22871.7, self.close=22845.6, self.high=22872.7, self.low=22828.0, self.vol=1681.775, self.amt=38418652.1699 
127.0.0.1 - - [22/Jan/2023 16:15:00] "POST / HTTP/1.1" 200 -
2023-01-22 16:15:00,737:INFO:sr_min:main.py:172:handleKline:449472: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5950  20230122   155000    155459  ...         0.0        0.0       0
5951  20230122   155500    155959  ...         0.0        0.0       0
5952  20230122   160000    160459  ...         0.0        0.0       0
5953  20230122   160500    160959  ...         0.0        0.0       0
5954  20230122   161000    161459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-01-22 16:15:00,737:INFO:sr_min:main.py:175:handleKline:449472: self.closeSec=1674375299, self.tradeDate='20230122', self.openTime='161000', self.closeTime='161459',self.symbol='BTCUSDT',self.open=22871.7, self.close=22845.6, self.high=22872.7, self.low=22828.0, self.vol=1681.775, self.amt=38418652.1699, ukdf['pct'].iloc[-1]=-0.001137 , ukdf['amount'].iloc[-1]=38418652.1699, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5954, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': []}
type(curSign)=<class 'int'>, curSign=0, self.sign=0


## /root/FIL/strategy/s_rsrs/log.txt ----- -----

721  20230122   040000    075959  1674345599  ...    721  1.060041  0.686393     1.0
722  20230122   080000    115959  1674359999  ...    722  1.049703  0.649054     1.0

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '41.799', 'enterprice': '23284.2', 'countrevence': '0', 'unrealprofit': '-21827.4378', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '22762', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=1, self.sign=1
127.0.0.1 - - [22/Jan/2023 16:00:01] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='s_rsrs', self.symbol='BTCUSDT', interval='4h', intervalSec=14400, wid=25, thd=0.6, self.sign=1, self.total=972283.0195242, self.flagDict['side']='buy', self.tradeCount=14, self.count=348
self.closeSec=1674374399, self.tradeDate='20230122', self.openTime='120000', self.closeTime='155959', self.symbol='BTCUSDT', self.open=22766.0, self.close=22893.2, self.high=22967.0, self.low=22720.0, self.vol=41651.721, self.amt=952898275.7755 
2023-01-22 16:00:01,623:INFO:s_rsrs:main.py:141:handleKline:185271: self.closeSec=1674374399, self.tradeDate='20230122', self.openTime='120000', self.closeTime='155959',self.symbol='BTCUSDT',self.open=22766.0, self.close=22893.2, self.high=22967.0, self.low=22720.0, self.vol=41651.721, self.amt=952898275.7755 
2023-01-22 16:00:01,661:INFO:s_rsrs:main.py:142:handleKline:185271: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime  ...         vol           amt       pct
719  20230121   200000    235959  ...  145710.162  3.357102e+09  0.004047
720  20230122   000000    035959  ...  130707.129  3.031658e+09  0.011989
721  20230122   040000    075959  ...   98007.119  2.253013e+09 -0.021055
722  20230122   080000    115959  ...   77074.221  1.756555e+09 -0.000694
723  20230122   120000    155959  ...   41651.721  9.528983e+08  0.005583

[5 rows x 11 columns]
2023-01-22 16:00:03,287:INFO:s_rsrs:main.py:151:handleKline:185271: df_s.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec  ...  index      beta    zscore  signal
719  20230121   200000    235959  1674316799  ...    719  1.000848  0.581866     NaN
720  20230122   000000    035959  1674331199  ...    720  1.018084  0.606025     1.0
721  20230122   040000    075959  1674345599  ...    721  1.060041  0.686393     1.0
722  20230122   080000    115959  1674359999  ...    722  1.049703  0.649054     1.0
723  20230122   120000    155959  1674374399  ...    723  1.019065  0.565618     NaN

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '41.799', 'enterprice': '23284.2', 'countrevence': '0', 'unrealprofit': '-16262.63276480205', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '22895.13249205', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-9223372036854775808, self.sign=1


