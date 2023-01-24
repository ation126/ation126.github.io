# 20230124 16:16:01

## /root/FIL/strategy/amihud/log.txt ----- -----

127.0.0.1 - - [24/Jan/2023 16:10:01] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=993672.4896432, self.flagDict['side']='sell', self.tradeCount=2, self.count=16730
self.closeSec=1674547799, self.tradeDate='20230124', self.openTime='160500', self.closeTime='160959', self.symbol='BTCUSDT', self.open=23063.6, self.close=23033.4, self.high=23063.6, self.low=23033.4, self.vol=811.46, self.amt=18701079.0701 
2023-01-24 16:10:01,803:INFO:amihud:main.py:172:handleKline:200676: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5949  20230124   154500    154959  ...         0.0        0.0       0
5950  20230124   155000    155459  ...         0.0        0.0       0
5951  20230124   155500    155959  ...         0.0        0.0       0
5952  20230124   160000    160459  ...         0.0        0.0       0
5953  20230124   160500    160959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-01-24 16:10:01,804:INFO:amihud:main.py:175:handleKline:200676: self.closeSec=1674547799, self.tradeDate='20230124', self.openTime='160500', self.closeTime='160959',self.symbol='BTCUSDT',self.open=23063.6, self.close=23033.4, self.high=23063.6, self.low=23033.4, self.vol=811.46, self.amt=18701079.0701, ukdf['pct'].iloc[-1]=-0.001305 , ukdf['amount'].iloc[-1]=18701079.0701, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5953, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '60.176', 'enterprice': '16529.3', 'countrevence': '0', 'unrealprofit': '-391447.97124894288', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '23034.35137013', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1
--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=993672.4896432, self.flagDict['side']='sell', self.tradeCount=2, self.count=16731
self.closeSec=1674548099, self.tradeDate='20230124', self.openTime='161000', self.closeTime='161459', self.symbol='BTCUSDT', self.open=23033.4, self.close=23041.1, self.high=23050.1, self.low=23030.2, self.vol=543.962, self.amt=12533527.667 
127.0.0.1 - - [24/Jan/2023 16:15:00] "POST / HTTP/1.1" 200 -
2023-01-24 16:15:00,777:INFO:amihud:main.py:172:handleKline:200676: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5950  20230124   155000    155459  ...         0.0        0.0       0
5951  20230124   155500    155959  ...         0.0        0.0       0
5952  20230124   160000    160459  ...         0.0        0.0       0
5953  20230124   160500    160959  ...         0.0        0.0       0
5954  20230124   161000    161459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-01-24 16:15:00,777:INFO:amihud:main.py:175:handleKline:200676: self.closeSec=1674548099, self.tradeDate='20230124', self.openTime='161000', self.closeTime='161459',self.symbol='BTCUSDT',self.open=23033.4, self.close=23041.1, self.high=23050.1, self.low=23030.2, self.vol=543.962, self.amt=12533527.667, ukdf['pct'].iloc[-1]=0.000334 , ukdf['amount'].iloc[-1]=12533527.667, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5954, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '60.176', 'enterprice': '16529.3', 'countrevence': '0', 'unrealprofit': '-391848.0592', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '23041', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1


## /root/FIL/strategy/factorcheck/log.txt ----- -----

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=173, self.factor=0.30846824882645046, self.count=17296 

self.closeSec=1674547799, self.tradeDate='20230124', self.openTime='160500', self.closeTime='160959', self.symbol='BTCUSDT', self.open=23063.6, self.close=23033.4, self.high=23063.6, self.low=23033.4 
2023-01-24 16:10:01,739:INFO:factorcheck2:main.py:126:handleKline:185239: self.closeSec=1674547799, self.tradeDate='20230124', self.openTime='160500', self.closeTime='160959',self.symbol='BTCUSDT',self.open=23063.6, self.close=23033.4, self.high=23063.6, self.low=23033.4   
2023-01-24 16:10:01,794:INFO:factorcheck2:main.py:127:handleKline:185239: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1629  20230124   154500    154959  1674546599  ...  23000.0 -0.000013   1629    3
1630  20230124   155000    155459  1674546899  ...  23030.9 -0.000273   1630    4
1631  20230124   155500    155959  1674547199  ...  23037.0  0.000174   1631    5
1632  20230124   160000    160459  1674547499  ...  23052.3  0.000482   1632    0
1633  20230124   160500    160959  1674547799  ...  23033.4 -0.001305   1633    1

[5 rows x 11 columns]
2023-01-24 16:10:01,794:INFO:factorcheck2:main.py:128:handleKline:185239: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=173, self.factor=0.30846824882645046, self.count=17297 

self.closeSec=1674548099, self.tradeDate='20230124', self.openTime='161000', self.closeTime='161459', self.symbol='BTCUSDT', self.open=23033.4, self.close=23041.1, self.high=23050.1, self.low=23030.2 
2023-01-24 16:15:00,756:INFO:factorcheck2:main.py:126:handleKline:185239: self.closeSec=1674548099, self.tradeDate='20230124', self.openTime='161000', self.closeTime='161459',self.symbol='BTCUSDT',self.open=23033.4, self.close=23041.1, self.high=23050.1, self.low=23030.2   
127.0.0.1 - - [24/Jan/2023 16:15:00] "POST / HTTP/1.1" 200 -
2023-01-24 16:15:00,809:INFO:factorcheck2:main.py:127:handleKline:185239: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1630  20230124   155000    155459  1674546899  ...  23030.9 -0.000273   1630    4
1631  20230124   155500    155959  1674547199  ...  23037.0  0.000174   1631    5
1632  20230124   160000    160459  1674547499  ...  23052.3  0.000482   1632    0
1633  20230124   160500    160959  1674547799  ...  23033.4 -0.001305   1633    1
1634  20230124   161000    161459  1674548099  ...  23030.2  0.000334   1634    2

[5 rows x 11 columns]
2023-01-24 16:15:00,811:INFO:factorcheck2:main.py:128:handleKline:185239: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}


## /root/FIL/strategy/logic/log.txt ----- -----

2023-01-24 16:00:18,892:DEBUG:logic:main.py:463:getModel:885513: df_s.iloc[-5:,:] :
          date closeTime     open  ...    alpha58   alpha67   alpha72
5786  20230124    132959  23070.2  ...  53.750000  0.547465  0.277543
5787  20230124    135959  23068.4  ...  54.166667  0.555656  0.266245
5788  20230124    142959  23118.2  ...  54.166667  0.557556  0.254584
5789  20230124    145959  23129.7  ...  54.166667  0.549761  0.247326
5790  20230124    152959  23092.1  ...  54.166667  0.549304  0.240764

[5 rows x 33 columns]
0.533210332103321
acc is : 0.533210332103321
2023-01-24 16:00:18,962:INFO:logic:main.py:468:getModel:885513: df_pred.iloc[-5:,:] :
     pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
537     0  0.517814  0.482186       1  ...  1.066779   1.0    0.0  1.231690
538     0  0.535141  0.464859       1  ...  1.067315   1.0    0.0  1.232308
539     0  0.523365  0.476635       0  ...  1.065575   1.0    0.0  1.230299
540     0  0.508170  0.491830       0  ...  1.065473   1.0    0.0  1.230182
541     0  0.517404  0.482596       0  ...  1.063738   1.0    0.0  1.228179

[5 rows x 10 columns]
2023-01-24 16:00:18,973:INFO:logic:main.py:478:getModel:885513: df_panel.iloc[-5:,:] :
    pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
45     0  0.516983  0.483017       1  ...  1.066779   1.0    0.0  1.222706
46     0  0.534501  0.465499       1  ...  1.067315   1.0    0.0  1.227416
47     0  0.523380  0.476620       0  ...  1.065575   1.0    0.0  1.225825
48     0  0.507864  0.492136       0  ...  1.065473   1.0    0.0  1.225689
49     0  0.517404  0.482596       0  ...  1.063738   1.0    0.0  1.228179

[5 rows x 10 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '32.288', 'enterprice': '22918.2', 'countrevence': '0', 'unrealprofit': '4494.4896', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '23057.4', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}


## /root/FIL/strategy/modifiedmom/log.txt ----- -----

526  20230124   154000    154959  1674546599  23088.1  23054.7 -0.001447
2023-01-24 15:50:00,574:INFO:modifiedmom:main.py:146:handleKline:185213: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True}

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=8647 

self.closeSec=1674547199, self.tradeDate='20230124', self.openTime='155000', self.closeTime='155959', self.symbol='BTCUSDT', self.open='23053.5', self.close='23052.3'
2023-01-24 16:00:01,752:INFO:modifiedmom:main.py:144:handleKline:185213: self.closeSec=1674547199, self.tradeDate='20230124', self.openTime='155000', self.closeTime='155959',self.symbol='BTCUSDT',self.open='23053.5', self.close='23052.3'
127.0.0.1 - - [24/Jan/2023 16:00:01] "POST / HTTP/1.1" 200 -
2023-01-24 16:00:01,889:INFO:modifiedmom:main.py:145:handleKline:185213: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
523  20230124   151000    151959  1674544799  23084.7  23116.7  0.001399
524  20230124   152000    152959  1674545399  23116.7  23089.9 -0.001159
525  20230124   153000    153959  1674545999  23089.9  23088.1 -0.000078
526  20230124   154000    154959  1674546599  23088.1  23054.7 -0.001447
527  20230124   155000    155959  1674547199  23053.5  23052.3 -0.000104
2023-01-24 16:00:01,889:INFO:modifiedmom:main.py:146:handleKline:185213: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True}
127.0.0.1 - - [24/Jan/2023 16:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=8648 

self.closeSec=1674547799, self.tradeDate='20230124', self.openTime='160000', self.closeTime='160959', self.symbol='BTCUSDT', self.open='23052.3', self.close='23033.4'
2023-01-24 16:10:01,873:INFO:modifiedmom:main.py:144:handleKline:185213: self.closeSec=1674547799, self.tradeDate='20230124', self.openTime='160000', self.closeTime='160959',self.symbol='BTCUSDT',self.open='23052.3', self.close='23033.4'
2023-01-24 16:10:01,891:INFO:modifiedmom:main.py:145:handleKline:185213: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
524  20230124   152000    152959  1674545399  23116.7  23089.9 -0.001159
525  20230124   153000    153959  1674545999  23089.9  23088.1 -0.000078
526  20230124   154000    154959  1674546599  23088.1  23054.7 -0.001447
527  20230124   155000    155959  1674547199  23053.5  23052.3 -0.000104
528  20230124   160000    160959  1674547799  23052.3  23033.4 -0.000820
2023-01-24 16:10:01,891:INFO:modifiedmom:main.py:146:handleKline:185213: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True}


## /root/FIL/strategy/pyemd/log.txt ----- -----

17518  20230124   154000    154959  1674546599  23088.1  23054.7
2023-01-24 15:50:00,578:INFO:pyemd2:main.py:127:handleKline:185189: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=8648 

self.closeSec=1674547199, self.tradeDate='20230124', self.openTime='155000', self.closeTime='155959', self.symbol='BTCUSDT', self.open='23053.5', self.close='23052.3'
127.0.0.1 - - [24/Jan/2023 16:00:01] "POST / HTTP/1.1" 200 -
2023-01-24 16:00:01,778:INFO:pyemd2:main.py:125:handleKline:185189: self.closeSec=1674547199, self.tradeDate='20230124', self.openTime='155000', self.closeTime='155959',self.symbol='BTCUSDT',self.open='23053.5', self.close='23052.3'
2023-01-24 16:00:01,857:INFO:pyemd2:main.py:126:handleKline:185189: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17515  20230124   151000    151959  1674544799  23084.7  23116.7
17516  20230124   152000    152959  1674545399  23116.7  23089.9
17517  20230124   153000    153959  1674545999  23089.9  23088.1
17518  20230124   154000    154959  1674546599  23088.1  23054.7
17519  20230124   155000    155959  1674547199  23053.5  23052.3
2023-01-24 16:00:01,857:INFO:pyemd2:main.py:127:handleKline:185189: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--: 127.0.0.1 - - [24/Jan/2023 16:10:01] "POST / HTTP/1.1" 200 -
 self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=8649 

self.closeSec=1674547799, self.tradeDate='20230124', self.openTime='160000', self.closeTime='160959', self.symbol='BTCUSDT', self.open='23052.3', self.close='23033.4'
2023-01-24 16:10:01,901:INFO:pyemd2:main.py:125:handleKline:185189: self.closeSec=1674547799, self.tradeDate='20230124', self.openTime='160000', self.closeTime='160959',self.symbol='BTCUSDT',self.open='23052.3', self.close='23033.4'
2023-01-24 16:10:01,919:INFO:pyemd2:main.py:126:handleKline:185189: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17516  20230124   152000    152959  1674545399  23116.7  23089.9
17517  20230124   153000    153959  1674545999  23089.9  23088.1
17518  20230124   154000    154959  1674546599  23088.1  23054.7
17519  20230124   155000    155959  1674547199  23053.5  23052.3
17520  20230124   160000    160959  1674547799  23052.3  23033.4
2023-01-24 16:10:01,919:INFO:pyemd2:main.py:127:handleKline:185189: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}


## /root/FIL/strategy/similarity/log.txt ----- -----

12190  20230124   154000    154959  1674546599  23088.1  23054.7
2023-01-24 15:50:00,576:INFO:testStrategy:main.py:103:handleKline:185174: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': True, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=8648 

self.closeSec=1674547199, self.tradeDate='20230124', self.openTime='155000', self.closeTime='155959', self.symbol='BTCUSDT', self.open='23053.5', self.close='23052.3'
127.0.0.1 - - [24/Jan/2023 16:00:01] "POST / HTTP/1.1" 200 -
2023-01-24 16:00:01,760:INFO:testStrategy:main.py:101:handleKline:185174: self.closeSec=1674547199, self.tradeDate='20230124', self.openTime='155000', self.closeTime='155959',self.symbol='BTCUSDT',self.open='23053.5', self.close='23052.3'
2023-01-24 16:00:01,892:INFO:testStrategy:main.py:102:handleKline:185174: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12187  20230124   151000    151959  1674544799  23084.7  23116.7
12188  20230124   152000    152959  1674545399  23116.7  23089.9
12189  20230124   153000    153959  1674545999  23089.9  23088.1
12190  20230124   154000    154959  1674546599  23088.1  23054.7
12191  20230124   155000    155959  1674547199  23053.5  23052.3
2023-01-24 16:00:01,894:INFO:testStrategy:main.py:103:handleKline:185174: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': True, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=8649 

self.closeSec=1674547799, self.tradeDate='20230124', self.openTime='160000', self.closeTime='160959', self.symbol='BTCUSDT', self.open='23052.3', self.close='23033.4'
2023-01-24 16:10:01,885:INFO:testStrategy:main.py:101:handleKline:185174: self.closeSec=1674547799, self.tradeDate='20230124', self.openTime='160000', self.closeTime='160959',self.symbol='BTCUSDT',self.open='23052.3', self.close='23033.4'
127.0.0.1 - - [24/Jan/2023 16:10:01] "POST / HTTP/1.1" 200 -
2023-01-24 16:10:01,894:INFO:testStrategy:main.py:102:handleKline:185174: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12188  20230124   152000    152959  1674545399  23116.7  23089.9
12189  20230124   153000    153959  1674545999  23089.9  23088.1
12190  20230124   154000    154959  1674546599  23088.1  23054.7
12191  20230124   155000    155959  1674547199  23053.5  23052.3
12192  20230124   160000    160959  1674547799  23052.3  23033.4
2023-01-24 16:10:01,894:INFO:testStrategy:main.py:103:handleKline:185174: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': True, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}


## /root/FIL/strategy/sr_min/log.txt ----- -----

127.0.0.1 - - [24/Jan/2023 16:10:01] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=0, self.total=1000000.0, self.flagDict['side']='', self.tradeCount=0, self.count=12728
self.closeSec=1674547799, self.tradeDate='20230124', self.openTime='160500', self.closeTime='160959', self.symbol='BTCUSDT', self.open=23063.6, self.close=23033.4, self.high=23063.6, self.low=23033.4, self.vol=811.46, self.amt=18701079.0701 
2023-01-24 16:10:01,818:INFO:sr_min:main.py:172:handleKline:449472: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5949  20230124   154500    154959  ...         0.0        0.0       0
5950  20230124   155000    155459  ...         0.0        0.0       0
5951  20230124   155500    155959  ...         0.0        0.0       0
5952  20230124   160000    160459  ...         0.0        0.0       0
5953  20230124   160500    160959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-01-24 16:10:01,818:INFO:sr_min:main.py:175:handleKline:449472: self.closeSec=1674547799, self.tradeDate='20230124', self.openTime='160500', self.closeTime='160959',self.symbol='BTCUSDT',self.open=23063.6, self.close=23033.4, self.high=23063.6, self.low=23033.4, self.vol=811.46, self.amt=18701079.0701, ukdf['pct'].iloc[-1]=-0.001305 , ukdf['amount'].iloc[-1]=18701079.0701, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5953, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': []}
type(curSign)=<class 'int'>, curSign=0, self.sign=0
127.0.0.1 - - [24/Jan/2023 16:15:00] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=0, self.total=1000000.0, self.flagDict['side']='', self.tradeCount=0, self.count=12729
self.closeSec=1674548099, self.tradeDate='20230124', self.openTime='161000', self.closeTime='161459', self.symbol='BTCUSDT', self.open=23033.4, self.close=23041.1, self.high=23050.1, self.low=23030.2, self.vol=543.962, self.amt=12533527.667 
2023-01-24 16:15:00,790:INFO:sr_min:main.py:172:handleKline:449472: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5950  20230124   155000    155459  ...         0.0        0.0       0
5951  20230124   155500    155959  ...         0.0        0.0       0
5952  20230124   160000    160459  ...         0.0        0.0       0
5953  20230124   160500    160959  ...         0.0        0.0       0
5954  20230124   161000    161459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-01-24 16:15:00,790:INFO:sr_min:main.py:175:handleKline:449472: self.closeSec=1674548099, self.tradeDate='20230124', self.openTime='161000', self.closeTime='161459',self.symbol='BTCUSDT',self.open=23033.4, self.close=23041.1, self.high=23050.1, self.low=23030.2, self.vol=543.962, self.amt=12533527.667, ukdf['pct'].iloc[-1]=0.000334 , ukdf['amount'].iloc[-1]=12533527.667, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5954, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': []}
type(curSign)=<class 'int'>, curSign=0, self.sign=0


## /root/FIL/strategy/s_rsrs/log.txt ----- -----

721  20230124   040000    075959  1674518399  ...    721  0.950928  0.242794     NaN
722  20230124   080000    115959  1674532799  ...    722  0.908219  0.128689     NaN

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '41.799', 'enterprice': '23284.2', 'countrevence': '0', 'unrealprofit': '-8614.7739', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '23078.1', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-9223372036854775808, self.sign=1
--handleKline--:  version='2.0.0', self.name='s_rsrs', self.symbol='BTCUSDT', interval='4h', intervalSec=14400, wid=25, thd=0.6, self.sign=1, self.total=972283.0195242, self.flagDict['side']='buy', self.tradeCount=14, self.count=360
self.closeSec=1674547199, self.tradeDate='20230124', self.openTime='120000', self.closeTime='155959', self.symbol='BTCUSDT', self.open=23078.2, self.close=23052.3, self.high=23158.7, self.low=23000.0, self.vol=37575.8, self.amt=867705310.2893 
127.0.0.1 - - [24/Jan/2023 16:00:01] "POST / HTTP/1.1" 200 -
2023-01-24 16:00:01,616:INFO:s_rsrs:main.py:141:handleKline:185271: self.closeSec=1674547199, self.tradeDate='20230124', self.openTime='120000', self.closeTime='155959',self.symbol='BTCUSDT',self.open=23078.2, self.close=23052.3, self.high=23158.7, self.low=23000.0, self.vol=37575.8, self.amt=867705310.2893 
2023-01-24 16:00:01,647:INFO:s_rsrs:main.py:142:handleKline:185271: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime  ...         vol           amt       pct
719  20230123   200000    235959  ...  183939.268  4.198658e+09 -0.002375
720  20230124   000000    035959  ...  135623.970  3.109008e+09 -0.002682
721  20230124   040000    075959  ...   53110.170  1.217507e+09  0.005371
722  20230124   080000    115959  ...   51857.971  1.194127e+09  0.007205
723  20230124   120000    155959  ...   37575.800  8.677053e+08 -0.001122

[5 rows x 11 columns]
2023-01-24 16:00:03,454:INFO:s_rsrs:main.py:151:handleKline:185271: df_s.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec  ...  index      beta    zscore  signal
719  20230123   200000    235959  1674489599  ...    719  0.979369  0.342718     NaN
720  20230124   000000    035959  1674503999  ...    720  0.971922  0.308584     NaN
721  20230124   040000    075959  1674518399  ...    721  0.950928  0.242794     NaN
722  20230124   080000    115959  1674532799  ...    722  0.908219  0.128689     NaN
723  20230124   120000    155959  1674547199  ...    723  0.829119 -0.071439     NaN

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '41.799', 'enterprice': '23284.2', 'countrevence': '0', 'unrealprofit': '-9661.27183277133', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '23053.06356533', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-9223372036854775808, self.sign=1


