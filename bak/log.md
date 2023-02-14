# 20230214 16:36:08

## /root/FIL/strategy/amihud/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=993672.4896432, self.flagDict['side']='sell', self.tradeCount=2, self.count=22782
self.closeSec=1676363399, self.tradeDate='20230214', self.openTime='162500', self.closeTime='162959', self.symbol='BTCUSDT', self.open=21713.1, self.close=21706.4, self.high=21720.6, self.low=21704.6, self.vol=545.811, self.amt=11851043.1173 
127.0.0.1 - - [14/Feb/2023 16:30:02] "POST / HTTP/1.1" 200 -
2023-02-14 16:30:02,152:INFO:amihud:main.py:172:handleKline:200676: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5953  20230214   160500    160959  ...         0.0        0.0       0
5954  20230214   161000    161459  ...         0.0        0.0       0
5955  20230214   161500    161959  ...         0.0        0.0       0
5956  20230214   162000    162459  ...         0.0        0.0       0
5957  20230214   162500    162959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-02-14 16:30:02,154:INFO:amihud:main.py:175:handleKline:200676: self.closeSec=1676363399, self.tradeDate='20230214', self.openTime='162500', self.closeTime='162959',self.symbol='BTCUSDT',self.open=21713.1, self.close=21706.4, self.high=21720.6, self.low=21704.6, self.vol=545.811, self.amt=11851043.1173, ukdf['pct'].iloc[-1]=-0.000313 , ukdf['amount'].iloc[-1]=11851043.1173, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5957, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '60.176', 'enterprice': '16529.3', 'countrevence': '0', 'unrealprofit': '-311621.30082193248', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '21707.79808598', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1
--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=993672.4896432, self.flagDict['side']='sell', self.tradeCount=2, self.count=22783
self.closeSec=1676363699, self.tradeDate='20230214', self.openTime='163000', self.closeTime='163459', self.symbol='BTCUSDT', self.open=21706.4, self.close=21684.8, self.high=21707.8, self.low=21683.1, self.vol=1396.195, self.amt=30291784.6814 
127.0.0.1 - - [14/Feb/2023 16:35:01] "POST / HTTP/1.1" 200 -
2023-02-14 16:35:01,685:INFO:amihud:main.py:172:handleKline:200676: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5954  20230214   161000    161459  ...         0.0        0.0       0
5955  20230214   161500    161959  ...         0.0        0.0       0
5956  20230214   162000    162459  ...         0.0        0.0       0
5957  20230214   162500    162959  ...         0.0        0.0       0
5958  20230214   163000    163459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-02-14 16:35:01,685:INFO:amihud:main.py:175:handleKline:200676: self.closeSec=1676363699, self.tradeDate='20230214', self.openTime='163000', self.closeTime='163459',self.symbol='BTCUSDT',self.open=21706.4, self.close=21684.8, self.high=21707.8, self.low=21683.1, self.vol=1396.195, self.amt=30291784.6814, ukdf['pct'].iloc[-1]=-0.000995 , ukdf['amount'].iloc[-1]=30291784.6814, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5958, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '60.176', 'enterprice': '16529.3', 'countrevence': '0', 'unrealprofit': '-310265.46144180784', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '21685.26685459', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1


## /root/FIL/strategy/factorcheck/log.txt ----- -----

1636  20230214   162000    162459  1676363099  ...  21700.0  0.000267   1636    4
1637  20230214   162500    162959  1676363399  ...  21704.6 -0.000313   1637    5

[5 rows x 11 columns]
2023-02-14 16:30:02,116:INFO:factorcheck2:main.py:128:handleKline:185239: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': False, 'isOpen': True, 'isClose': False, 'isTrig': True}
2023-02-14 16:30:02,192:INFO:factorcheck2:main.py:145:handleKline:185239: df_panel.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec  ...       pct  index  idx    factor
229  20230214   142500    142959  1676356199  ... -0.000501   1613    5  0.476849
230  20230214   145500    145959  1676357999  ...  0.000083   1619    5  0.468877
231  20230214   152500    152959  1676359799  ...  0.000005   1625    5  0.460730
232  20230214   155500    155959  1676361599  ...  0.000354   1631    5  0.451936
233  20230214   162500    162959  1676363399  ... -0.000313   1637    5  0.446186

[5 rows x 12 columns]
127.0.0.1 - - [14/Feb/2023 16:35:01] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=25, self.factor=0.44618643344512027, self.count=23349 

self.closeSec=1676363699, self.tradeDate='20230214', self.openTime='163000', self.closeTime='163459', self.symbol='BTCUSDT', self.open=21706.4, self.close=21684.8, self.high=21707.8, self.low=21683.1 
2023-02-14 16:35:01,612:INFO:factorcheck2:main.py:126:handleKline:185239: self.closeSec=1676363699, self.tradeDate='20230214', self.openTime='163000', self.closeTime='163459',self.symbol='BTCUSDT',self.open=21706.4, self.close=21684.8, self.high=21707.8, self.low=21683.1   
2023-02-14 16:35:01,667:INFO:factorcheck2:main.py:127:handleKline:185239: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1634  20230214   161000    161459  1676362499  ...  21717.8  0.000424   1634    2
1635  20230214   161500    161959  1676362799  ...  21705.0 -0.000907   1635    3
1636  20230214   162000    162459  1676363099  ...  21700.0  0.000267   1636    4
1637  20230214   162500    162959  1676363399  ...  21704.6 -0.000313   1637    5
1638  20230214   163000    163459  1676363699  ...  21683.1 -0.000995   1638    0

[5 rows x 11 columns]
2023-02-14 16:35:01,667:INFO:factorcheck2:main.py:128:handleKline:185239: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': False, 'isOpen': True, 'isClose': False, 'isTrig': True}


## /root/FIL/strategy/logic/log.txt ----- -----

2023-02-14 16:30:36,337:DEBUG:logic:main.py:463:getModel:885513: df_s.iloc[-5:,:] :
          date closeTime     open  ...    alpha58   alpha67   alpha72
5787  20230214    135959  21711.6  ...  44.583333  0.497803  0.401051
5788  20230214    142959  21717.3  ...  45.000000  0.504119  0.387714
5789  20230214    145959  21739.2  ...  44.583333  0.503408  0.375585
5790  20230214    152959  21736.7  ...  45.000000  0.505514  0.363322
5791  20230214    155959  21743.7  ...  45.000000  0.510319  0.349738

[5 rows x 33 columns]
0.5350553505535055
acc is : 0.5350553505535055
2023-02-14 16:30:36,530:INFO:logic:main.py:468:getModel:885513: df_pred.iloc[-5:,:] :
     pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
537     0  0.504839  0.495161       1  ...  0.975470   1.0    0.0  0.922074
538     0  0.509999  0.490001       0  ...  0.975362   1.0    0.0  0.921972
539     0  0.503951  0.496049       1  ...  0.975681   1.0    0.0  0.922274
540     0  0.508376  0.491624       1  ...  0.976403   1.0    0.0  0.922957
541     0  0.510683  0.489317       0  ...  0.974002   1.0    0.0  0.920687

[5 rows x 10 columns]
2023-02-14 16:30:36,571:INFO:logic:main.py:478:getModel:885513: df_panel.iloc[-5:,:] :
    pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
45     0  0.505458  0.494542       1  ...  0.989004   1.0    0.0  0.925411
46     0  0.510310  0.489690       0  ...  0.975362   1.0    0.0  0.925238
47     0  0.503938  0.496062       1  ...  0.975681   1.0    0.0  0.922841
48     0  0.508733  0.491267       1  ...  0.976403   1.0    0.0  0.923736
49     0  0.510683  0.489317       0  ...  0.974002   1.0    0.0  0.920687

[5 rows x 10 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '35.557', 'enterprice': '21695.5', 'countrevence': '0', 'unrealprofit': '453.59564826352', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '21708.25685936', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}


## /root/FIL/strategy/modifiedmom/log.txt ----- -----

528  20230214   160000    160959  1676362199    21760  21717.9 -0.001930
2023-02-14 16:10:01,938:INFO:modifiedmom:main.py:146:handleKline:185213: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': True, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True}
127.0.0.1 - - [14/Feb/2023 16:20:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=11673 

self.closeSec=1676362799, self.tradeDate='20230214', self.openTime='161000', self.closeTime='161959', self.symbol='BTCUSDT', self.open='21717.8', self.close='21707.5'
2023-02-14 16:20:01,699:INFO:modifiedmom:main.py:144:handleKline:185213: self.closeSec=1676362799, self.tradeDate='20230214', self.openTime='161000', self.closeTime='161959',self.symbol='BTCUSDT',self.open='21717.8', self.close='21707.5'
2023-02-14 16:20:01,741:INFO:modifiedmom:main.py:145:handleKline:185213: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
525  20230214   153000    153959  1676360399  21743.7  21760.3  0.000759
526  20230214   154000    154959  1676360999  21760.3    21749 -0.000519
527  20230214   155000    155959  1676361599  21748.9  21759.9  0.000501
528  20230214   160000    160959  1676362199    21760  21717.9 -0.001930
529  20230214   161000    161959  1676362799  21717.8  21707.5 -0.000479
2023-02-14 16:20:01,741:INFO:modifiedmom:main.py:146:handleKline:185213: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': True, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True}

--handleKline--: 127.0.0.1 - - [14/Feb/2023 16:30:02] "POST / HTTP/1.1" 200 -
 self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=11674 

self.closeSec=1676363399, self.tradeDate='20230214', self.openTime='162000', self.closeTime='162959', self.symbol='BTCUSDT', self.open='21707.4', self.close='21706.4'
2023-02-14 16:30:02,588:INFO:modifiedmom:main.py:144:handleKline:185213: self.closeSec=1676363399, self.tradeDate='20230214', self.openTime='162000', self.closeTime='162959',self.symbol='BTCUSDT',self.open='21707.4', self.close='21706.4'
2023-02-14 16:30:02,609:INFO:modifiedmom:main.py:145:handleKline:185213: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
526  20230214   154000    154959  1676360999  21760.3    21749 -0.000519
527  20230214   155000    155959  1676361599  21748.9  21759.9  0.000501
528  20230214   160000    160959  1676362199    21760  21717.9 -0.001930
529  20230214   161000    161959  1676362799  21717.8  21707.5 -0.000479
530  20230214   162000    162959  1676363399  21707.4  21706.4 -0.000051
2023-02-14 16:30:02,610:INFO:modifiedmom:main.py:146:handleKline:185213: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': True, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True}


## /root/FIL/strategy/percentile_regression_step2/log.txt ----- -----

127.0.0.1 - - [14/Feb/2023 15:30:02] "POST / HTTP/1.1" 200 -
2023-02-14 15:30:02,777:DEBUG:percentile_regression_step2:main.py:154:get_signal:1265985: df_id.iloc[-5:,:] :
                 daytime     hms    close  ...  pct_10  pct_20  factor
144  2023/02/14 13:00:00  130000  21711.5  ...     NaN     NaN       0
145  2023/02/14 13:30:00  133000  21717.3  ...     NaN     NaN       0
146  2023/02/14 14:00:00  140000  21739.1  ...     NaN     NaN       0
147  2023/02/14 14:30:00  143000  21736.7  ...     NaN     NaN       0
148  2023/02/14 15:00:00  150000  21743.8  ...     NaN     NaN       0

[5 rows x 10 columns]
127.0.0.1 - - [14/Feb/2023 16:00:02] "POST / HTTP/1.1" 200 -
2023-02-14 16:00:03,310:DEBUG:percentile_regression_step2:main.py:154:get_signal:1265985: df_id.iloc[-5:,:] :
                 daytime     hms    close  ...  pct_10  pct_20  factor
144  2023/02/14 13:30:00  133000  21717.3  ...     NaN     NaN       0
145  2023/02/14 14:00:00  140000  21739.1  ...     NaN     NaN       0
146  2023/02/14 14:30:00  143000  21736.7  ...     NaN     NaN       0
147  2023/02/14 15:00:00  150000  21743.8  ...     NaN     NaN       0
148  2023/02/14 15:30:00  153000  21759.9  ...     NaN     NaN       0

[5 rows x 10 columns]
127.0.0.1 - - [14/Feb/2023 16:30:02] "POST / HTTP/1.1" 200 -
2023-02-14 16:30:03,279:DEBUG:percentile_regression_step2:main.py:154:get_signal:1265985: df_id.iloc[-5:,:] :
                 daytime     hms    close  ...  pct_10  pct_20  factor
144  2023/02/14 14:00:00  140000  21739.1  ...     NaN     NaN       0
145  2023/02/14 14:30:00  143000  21736.7  ...     NaN     NaN       0
146  2023/02/14 15:00:00  150000  21743.8  ...     NaN     NaN       0
147  2023/02/14 15:30:00  153000  21759.9  ...     NaN     NaN       0
148  2023/02/14 16:00:00  160000  21706.4  ...     NaN     NaN       0

[5 rows x 10 columns]


## /root/FIL/strategy/pyemd/log.txt ----- -----

17520  20230214   160000    160959  1676362199    21760  21717.9
2023-02-14 16:10:01,953:INFO:pyemd2:main.py:127:handleKline:185189: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}
127.0.0.1 - - [14/Feb/2023 16:20:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=11674 

self.closeSec=1676362799, self.tradeDate='20230214', self.openTime='161000', self.closeTime='161959', self.symbol='BTCUSDT', self.open='21717.8', self.close='21707.5'
2023-02-14 16:20:01,716:INFO:pyemd2:main.py:125:handleKline:185189: self.closeSec=1676362799, self.tradeDate='20230214', self.openTime='161000', self.closeTime='161959',self.symbol='BTCUSDT',self.open='21717.8', self.close='21707.5'
2023-02-14 16:20:01,746:INFO:pyemd2:main.py:126:handleKline:185189: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17517  20230214   153000    153959  1676360399  21743.7  21760.3
17518  20230214   154000    154959  1676360999  21760.3    21749
17519  20230214   155000    155959  1676361599  21748.9  21759.9
17520  20230214   160000    160959  1676362199    21760  21717.9
17521  20230214   161000    161959  1676362799  21717.8  21707.5
2023-02-14 16:20:01,747:INFO:pyemd2:main.py:127:handleKline:185189: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--: 127.0.0.1 - - [14/Feb/2023 16:30:02] "POST / HTTP/1.1" 200 -
 self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=11675 

self.closeSec=1676363399, self.tradeDate='20230214', self.openTime='162000', self.closeTime='162959', self.symbol='BTCUSDT', self.open='21707.4', self.close='21706.4'
2023-02-14 16:30:02,587:INFO:pyemd2:main.py:125:handleKline:185189: self.closeSec=1676363399, self.tradeDate='20230214', self.openTime='162000', self.closeTime='162959',self.symbol='BTCUSDT',self.open='21707.4', self.close='21706.4'
2023-02-14 16:30:02,620:INFO:pyemd2:main.py:126:handleKline:185189: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17518  20230214   154000    154959  1676360999  21760.3    21749
17519  20230214   155000    155959  1676361599  21748.9  21759.9
17520  20230214   160000    160959  1676362199    21760  21717.9
17521  20230214   161000    161959  1676362799  21717.8  21707.5
17522  20230214   162000    162959  1676363399  21707.4  21706.4
2023-02-14 16:30:02,621:INFO:pyemd2:main.py:127:handleKline:185189: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}


## /root/FIL/strategy/similarity/log.txt ----- -----

12192  20230214   160000    160959  1676362199    21760  21717.9
2023-02-14 16:10:01,921:INFO:testStrategy:main.py:103:handleKline:185174: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}
127.0.0.1 - - [14/Feb/2023 16:20:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=11674 

self.closeSec=1676362799, self.tradeDate='20230214', self.openTime='161000', self.closeTime='161959', self.symbol='BTCUSDT', self.open='21717.8', self.close='21707.5'
2023-02-14 16:20:01,728:INFO:testStrategy:main.py:101:handleKline:185174: self.closeSec=1676362799, self.tradeDate='20230214', self.openTime='161000', self.closeTime='161959',self.symbol='BTCUSDT',self.open='21717.8', self.close='21707.5'
2023-02-14 16:20:01,735:INFO:testStrategy:main.py:102:handleKline:185174: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12189  20230214   153000    153959  1676360399  21743.7  21760.3
12190  20230214   154000    154959  1676360999  21760.3    21749
12191  20230214   155000    155959  1676361599  21748.9  21759.9
12192  20230214   160000    160959  1676362199    21760  21717.9
12193  20230214   161000    161959  1676362799  21717.8  21707.5
2023-02-14 16:20:01,735:INFO:testStrategy:main.py:103:handleKline:185174: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}
127.0.0.1 - - [14/Feb/2023 16:30:02] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=11675 

self.closeSec=1676363399, self.tradeDate='20230214', self.openTime='162000', self.closeTime='162959', self.symbol='BTCUSDT', self.open='21707.4', self.close='21706.4'
2023-02-14 16:30:02,647:INFO:testStrategy:main.py:101:handleKline:185174: self.closeSec=1676363399, self.tradeDate='20230214', self.openTime='162000', self.closeTime='162959',self.symbol='BTCUSDT',self.open='21707.4', self.close='21706.4'
2023-02-14 16:30:02,676:INFO:testStrategy:main.py:102:handleKline:185174: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12190  20230214   154000    154959  1676360999  21760.3    21749
12191  20230214   155000    155959  1676361599  21748.9  21759.9
12192  20230214   160000    160959  1676362199    21760  21717.9
12193  20230214   161000    161959  1676362799  21717.8  21707.5
12194  20230214   162000    162959  1676363399  21707.4  21706.4
2023-02-14 16:30:02,676:INFO:testStrategy:main.py:103:handleKline:185174: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}


## /root/FIL/strategy/sr_min/log.txt ----- -----

127.0.0.1 - - [14/Feb/2023 16:30:02] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=0, self.total=1000000.0, self.flagDict['side']='', self.tradeCount=0, self.count=18780
self.closeSec=1676363399, self.tradeDate='20230214', self.openTime='162500', self.closeTime='162959', self.symbol='BTCUSDT', self.open=21713.1, self.close=21706.4, self.high=21720.6, self.low=21704.6, self.vol=545.811, self.amt=11851043.1173 
2023-02-14 16:30:02,143:INFO:sr_min:main.py:172:handleKline:449472: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5953  20230214   160500    160959  ...         0.0        0.0       0
5954  20230214   161000    161459  ...         0.0        0.0       0
5955  20230214   161500    161959  ...         0.0        0.0       0
5956  20230214   162000    162459  ...         0.0        0.0       0
5957  20230214   162500    162959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-02-14 16:30:02,144:INFO:sr_min:main.py:175:handleKline:449472: self.closeSec=1676363399, self.tradeDate='20230214', self.openTime='162500', self.closeTime='162959',self.symbol='BTCUSDT',self.open=21713.1, self.close=21706.4, self.high=21720.6, self.low=21704.6, self.vol=545.811, self.amt=11851043.1173, ukdf['pct'].iloc[-1]=-0.000313 , ukdf['amount'].iloc[-1]=11851043.1173, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5957, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': []}
type(curSign)=<class 'int'>, curSign=0, self.sign=0
127.0.0.1 - - [14/Feb/2023 16:35:01] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=0, self.total=1000000.0, self.flagDict['side']='', self.tradeCount=0, self.count=18781
self.closeSec=1676363699, self.tradeDate='20230214', self.openTime='163000', self.closeTime='163459', self.symbol='BTCUSDT', self.open=21706.4, self.close=21684.8, self.high=21707.8, self.low=21683.1, self.vol=1396.195, self.amt=30291784.6814 
2023-02-14 16:35:01,719:INFO:sr_min:main.py:172:handleKline:449472: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5954  20230214   161000    161459  ...         0.0        0.0       0
5955  20230214   161500    161959  ...         0.0        0.0       0
5956  20230214   162000    162459  ...         0.0        0.0       0
5957  20230214   162500    162959  ...         0.0        0.0       0
5958  20230214   163000    163459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-02-14 16:35:01,719:INFO:sr_min:main.py:175:handleKline:449472: self.closeSec=1676363699, self.tradeDate='20230214', self.openTime='163000', self.closeTime='163459',self.symbol='BTCUSDT',self.open=21706.4, self.close=21684.8, self.high=21707.8, self.low=21683.1, self.vol=1396.195, self.amt=30291784.6814, ukdf['pct'].iloc[-1]=-0.000995 , ukdf['amount'].iloc[-1]=30291784.6814, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5958, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': []}
type(curSign)=<class 'int'>, curSign=0, self.sign=0


## /root/FIL/strategy/s_rsrs/log.txt ----- -----

721  20230214   040000    075959  1676332799  ...    721  0.070486 -2.822363    -1.0
722  20230214   080000    115959  1676347199  ...    722  0.062182 -2.710728    -1.0

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '42.891', 'enterprice': '21599.9', 'countrevence': '0', 'unrealprofit': '-3972.21578393778', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '21692.51187158', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-1, self.sign=-1
--handleKline--:  version='2.0.0', self.name='s_rsrs', self.symbol='BTCUSDT', interval='4h', intervalSec=14400, wid=25, thd=0.6, self.sign=-1, self.total=925514.8695891, self.flagDict['side']='sell', self.tradeCount=19, self.count=486
self.closeSec=1676361599, self.tradeDate='20230214', self.openTime='120000', self.closeTime='155959', self.symbol='BTCUSDT', self.open=21691.8, self.close=21759.9, self.high=21780.0, self.low=21676.5, self.vol=24174.292, self.amt=525253522.1147 
127.0.0.1 - - [14/Feb/2023 16:00:02] "POST / HTTP/1.1" 200 -
2023-02-14 16:00:02,733:INFO:s_rsrs:main.py:141:handleKline:185271: self.closeSec=1676361599, self.tradeDate='20230214', self.openTime='120000', self.closeTime='155959',self.symbol='BTCUSDT',self.open=21691.8, self.close=21759.9, self.high=21780.0, self.low=21676.5, self.vol=24174.292, self.amt=525253522.1147 
2023-02-14 16:00:02,799:INFO:s_rsrs:main.py:142:handleKline:185271: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime  ...         vol           amt       pct
719  20230213   200000    235959  ...   76257.797  1.648761e+09 -0.001973
720  20230214   000000    035959  ...  134846.671  2.901605e+09  0.002065
721  20230214   040000    075959  ...   54964.095  1.192266e+09  0.007797
722  20230214   080000    115959  ...   31405.193  6.823670e+08 -0.003418
723  20230214   120000    155959  ...   24174.292  5.252535e+08  0.003139

[5 rows x 11 columns]
2023-02-14 16:00:04,996:INFO:s_rsrs:main.py:151:handleKline:185271: df_s.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec  ...  index      beta    zscore  signal
719  20230213   200000    235959  1676303999  ...    719  0.615151 -0.080985     NaN
720  20230214   000000    035959  1676318399  ...    720  0.212528 -2.193015    -1.0
721  20230214   040000    075959  1676332799  ...    721  0.070486 -2.822363    -1.0
722  20230214   080000    115959  1676347199  ...    722  0.062182 -2.710728    -1.0
723  20230214   120000    155959  1676361599  ...    723  0.050675 -2.624902    -1.0

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '42.891', 'enterprice': '21599.9', 'countrevence': '0', 'unrealprofit': '-6866.8491', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '21760', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-1, self.sign=-1


