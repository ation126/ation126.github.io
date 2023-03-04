# 20230304 16:26:01

## /root/FIL/strategy/amihud/log.txt ----- -----

127.0.0.1 - - [04/Mar/2023 16:20:01] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=993672.4896432, self.flagDict['side']='sell', self.tradeCount=2, self.count=27964
self.closeSec=1677917999, self.tradeDate='20230304', self.openTime='161500', self.closeTime='161959', self.symbol='BTCUSDT', self.open=22334.4, self.close=22338.4, self.high=22338.5, self.low=22334.3, self.vol=244.314, self.amt=5456850.5753 
2023-03-04 16:20:01,732:INFO:amihud:main.py:172:handleKline:200676: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5951  20230304   155500    155959  ...         0.0        0.0       0
5952  20230304   160000    160459  ...         0.0        0.0       0
5953  20230304   160500    160959  ...         0.0        0.0       0
5954  20230304   161000    161459  ...         0.0        0.0       0
5955  20230304   161500    161959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-03-04 16:20:01,733:INFO:amihud:main.py:175:handleKline:200676: self.closeSec=1677917999, self.tradeDate='20230304', self.openTime='161500', self.closeTime='161959',self.symbol='BTCUSDT',self.open=22334.4, self.close=22338.4, self.high=22338.5, self.low=22334.3, self.vol=244.314, self.amt=5456850.5753, ukdf['pct'].iloc[-1]=0.000184 , ukdf['amount'].iloc[-1]=5456850.5753, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5955, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '60.176', 'enterprice': '16529.3', 'countrevence': '0', 'unrealprofit': '-349613.13627833184', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '22339.14339734', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1
127.0.0.1 - - [04/Mar/2023 16:25:01] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=993672.4896432, self.flagDict['side']='sell', self.tradeCount=2, self.count=27965
self.closeSec=1677918299, self.tradeDate='20230304', self.openTime='162000', self.closeTime='162459', self.symbol='BTCUSDT', self.open=22338.5, self.close=22335.4, self.high=22338.5, self.low=22331.1, self.vol=277.649, self.amt=6201344.6374 
2023-03-04 16:25:01,725:INFO:amihud:main.py:172:handleKline:200676: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5952  20230304   160000    160459  ...         0.0        0.0       0
5953  20230304   160500    160959  ...         0.0        0.0       0
5954  20230304   161000    161459  ...         0.0        0.0       0
5955  20230304   161500    161959  ...         0.0        0.0       0
5956  20230304   162000    162459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-03-04 16:25:01,726:INFO:amihud:main.py:175:handleKline:200676: self.closeSec=1677918299, self.tradeDate='20230304', self.openTime='162000', self.closeTime='162459',self.symbol='BTCUSDT',self.open=22338.5, self.close=22335.4, self.high=22338.5, self.low=22331.1, self.vol=277.649, self.amt=6201344.6374, ukdf['pct'].iloc[-1]=-0.000134 , ukdf['amount'].iloc[-1]=6201344.6374, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5956, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '60.176', 'enterprice': '16529.3', 'countrevence': '0', 'unrealprofit': '-349450.34026443008', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '22336.43806608', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1


## /root/FIL/strategy/factorcheck/log.txt ----- -----


self.closeSec=1677917999, self.tradeDate='20230304', self.openTime='161500', self.closeTime='161959', self.symbol='BTCUSDT', self.open=22334.4, self.close=22338.4, self.high=22338.5, self.low=22334.3 
2023-03-04 16:20:01,631:INFO:factorcheck2:main.py:126:handleKline:185239: self.closeSec=1677917999, self.tradeDate='20230304', self.openTime='161500', self.closeTime='161959',self.symbol='BTCUSDT',self.open=22334.4, self.close=22338.4, self.high=22338.5, self.low=22334.3   
127.0.0.1 - - [04/Mar/2023 16:20:01] "POST / HTTP/1.1" 200 -
2023-03-04 16:20:01,669:INFO:factorcheck2:main.py:127:handleKline:185239: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1631  20230304   155500    155959  1677916799  ...  22345.1  0.000072   1631    5
1632  20230304   160000    160459  1677917099  ...  22343.7  0.000063   1632    0
1633  20230304   160500    160959  1677917399  ...  22339.4 -0.000385   1633    1
1634  20230304   161000    161459  1677917699  ...  22332.1 -0.000233   1634    2
1635  20230304   161500    161959  1677917999  ...  22334.3  0.000184   1635    3

[5 rows x 11 columns]
2023-03-04 16:20:01,670:INFO:factorcheck2:main.py:128:handleKline:185239: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': False, 'isOpen': True, 'isClose': False, 'isTrig': True}

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=4, self.factor=0.5759431361186537, self.count=28531 

self.closeSec=1677918299, self.tradeDate='20230304', self.openTime='162000', self.closeTime='162459', self.symbol='BTCUSDT', self.open=22338.5, self.close=22335.4, self.high=22338.5, self.low=22331.1 
127.0.0.1 - - [04/Mar/2023 16:25:01] "POST / HTTP/1.1" 200 -
2023-03-04 16:25:01,622:INFO:factorcheck2:main.py:126:handleKline:185239: self.closeSec=1677918299, self.tradeDate='20230304', self.openTime='162000', self.closeTime='162459',self.symbol='BTCUSDT',self.open=22338.5, self.close=22335.4, self.high=22338.5, self.low=22331.1   
2023-03-04 16:25:01,666:INFO:factorcheck2:main.py:127:handleKline:185239: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1632  20230304   160000    160459  1677917099  ...  22343.7  0.000063   1632    0
1633  20230304   160500    160959  1677917399  ...  22339.4 -0.000385   1633    1
1634  20230304   161000    161459  1677917699  ...  22332.1 -0.000233   1634    2
1635  20230304   161500    161959  1677917999  ...  22334.3  0.000184   1635    3
1636  20230304   162000    162459  1677918299  ...  22331.1 -0.000134   1636    4

[5 rows x 11 columns]
2023-03-04 16:25:01,666:INFO:factorcheck2:main.py:128:handleKline:185239: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': False, 'isOpen': True, 'isClose': False, 'isTrig': True}


## /root/FIL/strategy/logic/log.txt ----- -----

2023-03-04 16:00:34,735:DEBUG:logic:main.py:463:getModel:885513: df_s.iloc[-5:,:] :
          date closeTime     open  ...    alpha58   alpha67   alpha72
5786  20230304    132959  22334.3  ...  49.166667  0.394807  0.528293
5787  20230304    135959  22312.9  ...  49.583333  0.395882  0.524923
5788  20230304    142959  22316.0  ...  50.000000  0.416872  0.510492
5789  20230304    145959  22379.4  ...  49.583333  0.411246  0.501377
5790  20230304    152959  22355.0  ...  49.583333  0.413751  0.491519

[5 rows x 33 columns]
0.5553505535055351
acc is : 0.5553505535055351
2023-03-04 16:00:34,892:INFO:logic:main.py:468:getModel:885513: df_pred.iloc[-5:,:] :
     pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
537     0  0.509739  0.490261       1  ...  0.856623   1.0    0.0  0.897634
538     0  0.517009  0.482991       1  ...  0.859061   1.0    0.0  0.900189
539     0  0.539664  0.460336       0  ...  0.858120   1.0    0.0  0.899203
540     0  0.513708  0.486292       1  ...  0.858412   1.0    0.0  0.899509
541     0  0.520993  0.479007       0  ...  0.857802   1.0    0.0  0.898869

[5 rows x 10 columns]
2023-03-04 16:00:34,920:INFO:logic:main.py:478:getModel:885513: df_panel.iloc[-5:,:] :
    pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
45     0  0.510830  0.489170       1  ...  0.856623   1.0    0.0  0.903310
46     0  0.517599  0.482401       1  ...  0.859061   1.0    0.0  0.902578
47     0  0.539655  0.460345       0  ...  0.858120   1.0    0.0  0.899601
48     0  0.514181  0.485819       1  ...  0.858412   1.0    0.0  0.901027
49     0  0.520993  0.479007       0  ...  0.857802   1.0    0.0  0.898869

[5 rows x 10 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '31.837', 'enterprice': '22365.6', 'countrevence': '0', 'unrealprofit': '-608.0867', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '22346.5', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}


## /root/FIL/strategy/modifiedmom/log.txt ----- -----

527  20230304   155000    155959  1677916799  22342.6  22346.7  0.000179
2023-03-04 16:00:02,088:INFO:modifiedmom:main.py:146:handleKline:185213: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': True, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True}
127.0.0.1 - - [04/Mar/2023 16:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=14264 

self.closeSec=1677917399, self.tradeDate='20230304', self.openTime='160000', self.closeTime='160959', self.symbol='BTCUSDT', self.open='22346.6', self.close='22339.5'
2023-03-04 16:10:01,865:INFO:modifiedmom:main.py:144:handleKline:185213: self.closeSec=1677917399, self.tradeDate='20230304', self.openTime='160000', self.closeTime='160959',self.symbol='BTCUSDT',self.open='22346.6', self.close='22339.5'
2023-03-04 16:10:01,880:INFO:modifiedmom:main.py:145:handleKline:185213: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
524  20230304   152000    152959  1677914999    22362  22362.6  0.000027
525  20230304   153000    153959  1677915599  22362.5  22357.1 -0.000246
526  20230304   154000    154959  1677916199  22357.1  22342.7 -0.000644
527  20230304   155000    155959  1677916799  22342.6  22346.7  0.000179
528  20230304   160000    160959  1677917399  22346.6  22339.5 -0.000322
2023-03-04 16:10:01,880:INFO:modifiedmom:main.py:146:handleKline:185213: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': True, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True}
127.0.0.1 - - [04/Mar/2023 16:20:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=14265 

self.closeSec=1677917999, self.tradeDate='20230304', self.openTime='161000', self.closeTime='161959', self.symbol='BTCUSDT', self.open='22339.4', self.close='22338.4'
2023-03-04 16:20:01,875:INFO:modifiedmom:main.py:144:handleKline:185213: self.closeSec=1677917999, self.tradeDate='20230304', self.openTime='161000', self.closeTime='161959',self.symbol='BTCUSDT',self.open='22339.4', self.close='22338.4'
2023-03-04 16:20:01,885:INFO:modifiedmom:main.py:145:handleKline:185213: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
525  20230304   153000    153959  1677915599  22362.5  22357.1 -0.000246
526  20230304   154000    154959  1677916199  22357.1  22342.7 -0.000644
527  20230304   155000    155959  1677916799  22342.6  22346.7  0.000179
528  20230304   160000    160959  1677917399  22346.6  22339.5 -0.000322
529  20230304   161000    161959  1677917999  22339.4  22338.4 -0.000049
2023-03-04 16:20:01,885:INFO:modifiedmom:main.py:146:handleKline:185213: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': True, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True}


## /root/FIL/strategy/percentile_regression_step2/log.txt ----- -----

127.0.0.1 - - [21/Feb/2023 09:30:01] "POST / HTTP/1.1" 200 -
2023-02-21 09:30:03,026:DEBUG:percentile_regression_step2:main.py:154:get_signal:1265985: df_id.iloc[-5:,:] :
                 daytime     hms    close  ...  pct_10  pct_20  factor
144  2023/02/21 07:00:00  070000  24795.1  ...     NaN     NaN       0
145  2023/02/21 07:30:00  073000  24849.9  ...     NaN     NaN       0
146  2023/02/21 08:00:00  080000  24819.0  ...     NaN     NaN       0
147  2023/02/21 08:30:00  083000  24860.9  ...     NaN     NaN       0
148  2023/02/21 09:00:00  090000  24831.0  ...     NaN     NaN       0

[5 rows x 10 columns]
127.0.0.1 - - [21/Feb/2023 10:00:02] "POST / HTTP/1.1" 200 -
2023-02-21 10:00:03,553:DEBUG:percentile_regression_step2:main.py:154:get_signal:1265985: df_id.iloc[-5:,:] :
                 daytime     hms    close  ...  pct_10  pct_20  factor
144  2023/02/21 07:30:00  073000  24849.9  ...     NaN     NaN       0
145  2023/02/21 08:00:00  080000  24819.0  ...     NaN     NaN       0
146  2023/02/21 08:30:00  083000  24860.9  ...     NaN     NaN       0
147  2023/02/21 09:00:00  090000  24831.0  ...     NaN     NaN       0
148  2023/02/21 09:30:00  093000  24870.0  ...     NaN     NaN       0

[5 rows x 10 columns]
127.0.0.1 - - [21/Feb/2023 10:30:01] "POST / HTTP/1.1" 200 -
2023-02-21 10:30:03,245:DEBUG:percentile_regression_step2:main.py:154:get_signal:1265985: df_id.iloc[-5:,:] :
                 daytime     hms    close  ...  pct_10  pct_20  factor
144  2023/02/21 08:00:00  080000  24819.0  ...     NaN     NaN       0
145  2023/02/21 08:30:00  083000  24860.9  ...     NaN     NaN       0
146  2023/02/21 09:00:00  090000  24831.0  ...     NaN     NaN       0
147  2023/02/21 09:30:00  093000  24870.0  ...     NaN     NaN       0
148  2023/02/21 10:00:00  100000  24936.1  ...     NaN     NaN       0

[5 rows x 10 columns]


## /root/FIL/strategy/pyemd/log.txt ----- -----

17519  20230304   155000    155959  1677916799  22342.6  22346.7
2023-03-04 16:00:02,112:INFO:pyemd2:main.py:127:handleKline:185189: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}
127.0.0.1 - - [04/Mar/2023 16:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=14265 

self.closeSec=1677917399, self.tradeDate='20230304', self.openTime='160000', self.closeTime='160959', self.symbol='BTCUSDT', self.open='22346.6', self.close='22339.5'
2023-03-04 16:10:01,853:INFO:pyemd2:main.py:125:handleKline:185189: self.closeSec=1677917399, self.tradeDate='20230304', self.openTime='160000', self.closeTime='160959',self.symbol='BTCUSDT',self.open='22346.6', self.close='22339.5'
2023-03-04 16:10:01,884:INFO:pyemd2:main.py:126:handleKline:185189: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17516  20230304   152000    152959  1677914999    22362  22362.6
17517  20230304   153000    153959  1677915599  22362.5  22357.1
17518  20230304   154000    154959  1677916199  22357.1  22342.7
17519  20230304   155000    155959  1677916799  22342.6  22346.7
17520  20230304   160000    160959  1677917399  22346.6  22339.5
2023-03-04 16:10:01,884:INFO:pyemd2:main.py:127:handleKline:185189: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}
127.0.0.1 - - [04/Mar/2023 16:20:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=14266 

self.closeSec=1677917999, self.tradeDate='20230304', self.openTime='161000', self.closeTime='161959', self.symbol='BTCUSDT', self.open='22339.4', self.close='22338.4'
2023-03-04 16:20:01,893:INFO:pyemd2:main.py:125:handleKline:185189: self.closeSec=1677917999, self.tradeDate='20230304', self.openTime='161000', self.closeTime='161959',self.symbol='BTCUSDT',self.open='22339.4', self.close='22338.4'
2023-03-04 16:20:01,923:INFO:pyemd2:main.py:126:handleKline:185189: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17517  20230304   153000    153959  1677915599  22362.5  22357.1
17518  20230304   154000    154959  1677916199  22357.1  22342.7
17519  20230304   155000    155959  1677916799  22342.6  22346.7
17520  20230304   160000    160959  1677917399  22346.6  22339.5
17521  20230304   161000    161959  1677917999  22339.4  22338.4
2023-03-04 16:20:01,923:INFO:pyemd2:main.py:127:handleKline:185189: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}


## /root/FIL/strategy/similarity/log.txt ----- -----

12191  20230304   155000    155959  1677916799  22342.6  22346.7
2023-03-04 16:00:02,096:INFO:testStrategy:main.py:103:handleKline:185174: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}
127.0.0.1 - - [04/Mar/2023 16:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=14265 

self.closeSec=1677917399, self.tradeDate='20230304', self.openTime='160000', self.closeTime='160959', self.symbol='BTCUSDT', self.open='22346.6', self.close='22339.5'
2023-03-04 16:10:01,845:INFO:testStrategy:main.py:101:handleKline:185174: self.closeSec=1677917399, self.tradeDate='20230304', self.openTime='160000', self.closeTime='160959',self.symbol='BTCUSDT',self.open='22346.6', self.close='22339.5'
2023-03-04 16:10:01,882:INFO:testStrategy:main.py:102:handleKline:185174: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12188  20230304   152000    152959  1677914999    22362  22362.6
12189  20230304   153000    153959  1677915599  22362.5  22357.1
12190  20230304   154000    154959  1677916199  22357.1  22342.7
12191  20230304   155000    155959  1677916799  22342.6  22346.7
12192  20230304   160000    160959  1677917399  22346.6  22339.5
2023-03-04 16:10:01,882:INFO:testStrategy:main.py:103:handleKline:185174: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=14266 

self.closeSec=1677917999, self.tradeDate='20230304', self.openTime='161000', self.closeTime='161959', self.symbol='BTCUSDT', self.open='22339.4', self.close='22338.4'
127.0.0.1 - - [04/Mar/2023 16:20:01] "POST / HTTP/1.1" 200 -
2023-03-04 16:20:01,923:INFO:testStrategy:main.py:101:handleKline:185174: self.closeSec=1677917999, self.tradeDate='20230304', self.openTime='161000', self.closeTime='161959',self.symbol='BTCUSDT',self.open='22339.4', self.close='22338.4'
2023-03-04 16:20:01,949:INFO:testStrategy:main.py:102:handleKline:185174: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12189  20230304   153000    153959  1677915599  22362.5  22357.1
12190  20230304   154000    154959  1677916199  22357.1  22342.7
12191  20230304   155000    155959  1677916799  22342.6  22346.7
12192  20230304   160000    160959  1677917399  22346.6  22339.5
12193  20230304   161000    161959  1677917999  22339.4  22338.4
2023-03-04 16:20:01,949:INFO:testStrategy:main.py:103:handleKline:185174: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}


## /root/FIL/strategy/sr_min/log.txt ----- -----

127.0.0.1 - - [04/Mar/2023 16:20:01] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=0, self.total=1000000.0, self.flagDict['side']='', self.tradeCount=0, self.count=23962
self.closeSec=1677917999, self.tradeDate='20230304', self.openTime='161500', self.closeTime='161959', self.symbol='BTCUSDT', self.open=22334.4, self.close=22338.4, self.high=22338.5, self.low=22334.3, self.vol=244.314, self.amt=5456850.5753 
2023-03-04 16:20:01,731:INFO:sr_min:main.py:172:handleKline:449472: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5951  20230304   155500    155959  ...         0.0        0.0       0
5952  20230304   160000    160459  ...         0.0        0.0       0
5953  20230304   160500    160959  ...         0.0        0.0       0
5954  20230304   161000    161459  ...         0.0        0.0       0
5955  20230304   161500    161959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-03-04 16:20:01,733:INFO:sr_min:main.py:175:handleKline:449472: self.closeSec=1677917999, self.tradeDate='20230304', self.openTime='161500', self.closeTime='161959',self.symbol='BTCUSDT',self.open=22334.4, self.close=22338.4, self.high=22338.5, self.low=22334.3, self.vol=244.314, self.amt=5456850.5753, ukdf['pct'].iloc[-1]=0.000184 , ukdf['amount'].iloc[-1]=5456850.5753, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5955, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': []}
type(curSign)=<class 'int'>, curSign=0, self.sign=0
--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=0, self.total=1000000.0, self.flagDict['side']='', self.tradeCount=0, self.count=23963
self.closeSec=1677918299, self.tradeDate='20230304', self.openTime='162000', self.closeTime='162459', self.symbol='BTCUSDT', self.open=22338.5, self.close=22335.4, self.high=22338.5, self.low=22331.1, self.vol=277.649, self.amt=6201344.6374 
127.0.0.1 - - [04/Mar/2023 16:25:01] "POST / HTTP/1.1" 200 -
2023-03-04 16:25:01,673:INFO:sr_min:main.py:172:handleKline:449472: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5952  20230304   160000    160459  ...         0.0        0.0       0
5953  20230304   160500    160959  ...         0.0        0.0       0
5954  20230304   161000    161459  ...         0.0        0.0       0
5955  20230304   161500    161959  ...         0.0        0.0       0
5956  20230304   162000    162459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-03-04 16:25:01,673:INFO:sr_min:main.py:175:handleKline:449472: self.closeSec=1677918299, self.tradeDate='20230304', self.openTime='162000', self.closeTime='162459',self.symbol='BTCUSDT',self.open=22338.5, self.close=22335.4, self.high=22338.5, self.low=22331.1, self.vol=277.649, self.amt=6201344.6374, ukdf['pct'].iloc[-1]=-0.000134 , ukdf['amount'].iloc[-1]=6201344.6374, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5956, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': []}
type(curSign)=<class 'int'>, curSign=0, self.sign=0


## /root/FIL/strategy/s_rsrs/log.txt ----- -----

721  20230304   040000    075959  1677887999  ...    721  0.488592 -0.429537     NaN
722  20230304   080000    115959  1677902399  ...    722  0.545580 -0.235435     NaN

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '42.135', 'enterprice': '23350.3', 'countrevence': '0', 'unrealprofit': '42623.766', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '22338.7', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-9223372036854775808, self.sign=-1
127.0.0.1 - - [04/Mar/2023 16:00:01] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='s_rsrs', self.symbol='BTCUSDT', interval='4h', intervalSec=14400, wid=25, thd=0.6, self.sign=-1, self.total=982881.0256095, self.flagDict['side']='sell', self.tradeCount=23, self.count=594
self.closeSec=1677916799, self.tradeDate='20230304', self.openTime='120000', self.closeTime='155959', self.symbol='BTCUSDT', self.open=22339.4, self.close=22346.7, self.high=22400.0, self.low=22262.2, self.vol=29929.532, self.amt=668632661.2715 
2023-03-04 16:00:01,935:INFO:s_rsrs:main.py:141:handleKline:185271: self.closeSec=1677916799, self.tradeDate='20230304', self.openTime='120000', self.closeTime='155959',self.symbol='BTCUSDT',self.open=22339.4, self.close=22346.7, self.high=22400.0, self.low=22262.2, self.vol=29929.532, self.amt=668632661.2715 
2023-03-04 16:00:01,985:INFO:s_rsrs:main.py:142:handleKline:185271: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime  ...         vol           amt       pct
719  20230303   200000    235959  ...  111464.429  2.489669e+09 -0.000448
720  20230304   000000    035959  ...   64926.046  1.450555e+09  0.001093
721  20230304   040000    075959  ...   59046.812  1.314850e+09 -0.000246
722  20230304   080000    115959  ...   24078.215  5.380207e+08 -0.000152
723  20230304   120000    155959  ...   29929.532  6.686327e+08  0.000327

[5 rows x 11 columns]
2023-03-04 16:00:04,592:INFO:s_rsrs:main.py:151:handleKline:185271: df_s.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec  ...  index      beta    zscore  signal
719  20230303   200000    235959  1677859199  ...    719  0.347434 -0.889416    -1.0
720  20230304   000000    035959  1677873599  ...    720  0.415967 -0.666855    -1.0
721  20230304   040000    075959  1677887999  ...    721  0.488592 -0.429537     NaN
722  20230304   080000    115959  1677902399  ...    722  0.545580 -0.235435     NaN
723  20230304   120000    155959  1677916799  ...    723  0.598689 -0.049109     NaN

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '42.135', 'enterprice': '23350.3', 'countrevence': '0', 'unrealprofit': '42253.3944690816', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '22347.49011584', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-9223372036854775808, self.sign=-1


