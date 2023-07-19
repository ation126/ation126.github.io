# 20230719 16:26:01

## /root/FIL/strategy/amihud/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=373746.4768026, self.flagDict['side']='sell', self.tradeCount=2, self.count=19072
self.closeSec=1689754799, self.tradeDate='20230719', self.openTime='161500', self.closeTime='161959', self.symbol='BTCUSDT', self.open=29968.3, self.close=29982.7, self.high=29982.8, self.low=29956.0, self.vol=464.106, self.amt=13908934.4266 
127.0.0.1 - - [19/Jul/2023 16:20:01] "POST / HTTP/1.1" 200 -
2023-07-19 16:20:04,796:INFO:amihud:main.py:172:handleKline:2219019: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5951  20230719   155500    155959  ...         0.0        0.0       0
5952  20230719   160000    160459  ...         0.0        0.0       0
5953  20230719   160500    160959  ...         0.0        0.0       0
5954  20230719   161000    161459  ...         0.0        0.0       0
5955  20230719   161500    161959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-07-19 16:20:04,815:INFO:amihud:main.py:175:handleKline:2219019: self.closeSec=1689754799, self.tradeDate='20230719', self.openTime='161500', self.closeTime='161959',self.symbol='BTCUSDT',self.open=29968.3, self.close=29982.7, self.high=29982.8, self.low=29956.0, self.vol=464.106, self.amt=13908934.4266, ukdf['pct'].iloc[-1]=0.000484 , ukdf['amount'].iloc[-1]=13908934.4266, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5955, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '13.926', 'enterprice': '26864.9', 'countrevence': '0', 'unrealprofit': '-43424.0532', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '29983.1', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1
127.0.0.1 - - [19/Jul/2023 16:25:00] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=373746.4768026, self.flagDict['side']='sell', self.tradeCount=2, self.count=19073
self.closeSec=1689755099, self.tradeDate='20230719', self.openTime='162000', self.closeTime='162459', self.symbol='BTCUSDT', self.open=29982.8, self.close=29993.4, self.high=29996.0, self.low=29977.9, self.vol=622.986, self.amt=18682424.6867 
2023-07-19 16:25:00,778:INFO:amihud:main.py:172:handleKline:2219019: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5952  20230719   160000    160459  ...         0.0        0.0       0
5953  20230719   160500    160959  ...         0.0        0.0       0
5954  20230719   161000    161459  ...         0.0        0.0       0
5955  20230719   161500    161959  ...         0.0        0.0       0
5956  20230719   162000    162459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-07-19 16:25:00,779:INFO:amihud:main.py:175:handleKline:2219019: self.closeSec=1689755099, self.tradeDate='20230719', self.openTime='162000', self.closeTime='162459',self.symbol='BTCUSDT',self.open=29982.8, self.close=29993.4, self.high=29996.0, self.low=29977.9, self.vol=622.986, self.amt=18682424.6867, ukdf['pct'].iloc[-1]=0.000357 , ukdf['amount'].iloc[-1]=18682424.6867, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5956, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '13.926', 'enterprice': '26864.9', 'countrevence': '0', 'unrealprofit': '-43567.491', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '29993.4', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1


## /root/FIL/strategy/factorcheck/log.txt ----- -----


self.closeSec=1689754799, self.tradeDate='20230719', self.openTime='161500', self.closeTime='161959', self.symbol='BTCUSDT', self.open=29968.3, self.close=29982.7, self.high=29982.8, self.low=29956.0 
127.0.0.1 - - [19/Jul/2023 16:20:01] "POST / HTTP/1.1" 200 -
2023-07-19 16:20:02,995:INFO:factorcheck2:main.py:126:handleKline:2218005: self.closeSec=1689754799, self.tradeDate='20230719', self.openTime='161500', self.closeTime='161959',self.symbol='BTCUSDT',self.open=29968.3, self.close=29982.7, self.high=29982.8, self.low=29956.0   
2023-07-19 16:20:03,956:INFO:factorcheck2:main.py:127:handleKline:2218005: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1631  20230719   155500    155959  1689753599  ...  29980.5  0.000003   1631    5
1632  20230719   160000    160459  1689753899  ...  29962.2 -0.000670   1632    0
1633  20230719   160500    160959  1689754199  ...  29941.4 -0.000664   1633    1
1634  20230719   161000    161459  1689754499  ...  29940.5  0.000808   1634    2
1635  20230719   161500    161959  1689754799  ...  29956.0  0.000484   1635    3

[5 rows x 11 columns]
2023-07-19 16:20:03,965:INFO:factorcheck2:main.py:128:handleKline:2218005: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': False, 'isOpen': True, 'isClose': False, 'isTrig': True}

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=13, self.factor=0.4793947925810471, self.count=19075 

self.closeSec=1689755099, self.tradeDate='20230719', self.openTime='162000', self.closeTime='162459', self.symbol='BTCUSDT', self.open=29982.8, self.close=29993.4, self.high=29996.0, self.low=29977.9 
127.0.0.1 - - [19/Jul/2023 16:25:00] "POST / HTTP/1.1" 200 -
2023-07-19 16:25:00,765:INFO:factorcheck2:main.py:126:handleKline:2218005: self.closeSec=1689755099, self.tradeDate='20230719', self.openTime='162000', self.closeTime='162459',self.symbol='BTCUSDT',self.open=29982.8, self.close=29993.4, self.high=29996.0, self.low=29977.9   
2023-07-19 16:25:00,791:INFO:factorcheck2:main.py:127:handleKline:2218005: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1632  20230719   160000    160459  1689753899  ...  29962.2 -0.000670   1632    0
1633  20230719   160500    160959  1689754199  ...  29941.4 -0.000664   1633    1
1634  20230719   161000    161459  1689754499  ...  29940.5  0.000808   1634    2
1635  20230719   161500    161959  1689754799  ...  29956.0  0.000484   1635    3
1636  20230719   162000    162459  1689755099  ...  29977.9  0.000357   1636    4

[5 rows x 11 columns]
2023-07-19 16:25:00,792:INFO:factorcheck2:main.py:128:handleKline:2218005: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': False, 'isOpen': True, 'isClose': False, 'isTrig': True}


## /root/FIL/strategy/logic/log.txt ----- -----

2023-07-19 16:00:17,467:DEBUG:logic:main.py:463:getModel:2218526: df_s.iloc[-5:,:] :
          date closeTime     open  ...    alpha58   alpha67   alpha72
5786  20230719    132959  30085.9  ...  48.750000  0.510502  0.310020
5787  20230719    135959  30069.3  ...  49.166667  0.513915  0.297359
5788  20230719    142959  30085.0  ...  49.166667  0.502082  0.289995
5789  20230719    145959  30033.1  ...  49.166667  0.500950  0.283550
5790  20230719    152959  30028.1  ...  49.583333  0.502575  0.276927

[5 rows x 33 columns]
0.518450184501845
acc is : 0.518450184501845
2023-07-19 16:00:17,538:INFO:logic:main.py:468:getModel:2218526: df_pred.iloc[-5:,:] :
     pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
537     0  0.507164  0.492836       1  ...  0.954211   1.0    0.0  0.993731
538     0  0.513317  0.486683       0  ...  0.952562   1.0    0.0  0.992013
539     1  0.487546  0.512454       0  ...  0.952403   1.0    0.0  0.991848
540     1  0.492557  0.507443       1  ...  0.952629   1.0    0.0  0.992083
541     1  0.499370  0.500630       0  ...  0.951008   1.0    0.0  0.990395

[5 rows x 10 columns]
2023-07-19 16:00:17,551:INFO:logic:main.py:478:getModel:2218526: df_panel.iloc[-5:,:] :
    pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
45     0  0.507228  0.492772       1  ...  0.954211   1.0    0.0  0.993147
46     0  0.513097  0.486903       0  ...  0.952562   1.0    0.0  0.990649
47     1  0.486778  0.513222       0  ...  0.952403   1.0    0.0  0.990111
48     1  0.492198  0.507802       1  ...  0.952629   1.0    0.0  0.991418
49     1  0.499370  0.500630       0  ...  0.951008   1.0    0.0  0.990395

[5 rows x 10 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '23.547', 'enterprice': '29974.9', 'countrevence': '0', 'unrealprofit': '303.51405906015', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '29987.78971245', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}


## /root/FIL/strategy/modifiedmom/log.txt ----- -----

527  20230719   155000    155959  1689753599  29972.9    29984  0.000367
2023-07-19 16:00:02,317:INFO:modifiedmom:main.py:146:handleKline:2218259: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True}
127.0.0.1 - - [19/Jul/2023 16:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=9536 

self.closeSec=1689754199, self.tradeDate='20230719', self.openTime='160000', self.closeTime='160959', self.symbol='BTCUSDT', self.open='29984.1', self.close='29944'
2023-07-19 16:10:01,134:INFO:modifiedmom:main.py:144:handleKline:2218259: self.closeSec=1689754199, self.tradeDate='20230719', self.openTime='160000', self.closeTime='160959',self.symbol='BTCUSDT',self.open='29984.1', self.close='29944'
2023-07-19 16:10:01,149:INFO:modifiedmom:main.py:145:handleKline:2218259: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
524  20230719   152000    152959  1689751799  30030.7  30035.1  0.000150
525  20230719   153000    153959  1689752399  30035.2  30011.7 -0.000779
526  20230719   154000    154959  1689752999  30011.7    29973 -0.001289
527  20230719   155000    155959  1689753599  29972.9    29984  0.000367
528  20230719   160000    160959  1689754199  29984.1    29944 -0.001334
2023-07-19 16:10:01,149:INFO:modifiedmom:main.py:146:handleKline:2218259: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True}

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=9537 

self.closeSec=1689754799, self.tradeDate='20230719', self.openTime='161000', self.closeTime='161959', self.symbol='BTCUSDT', self.open='29943.9', self.close='29982.7'
127.0.0.1 - - [19/Jul/2023 16:20:04] "POST / HTTP/1.1" 200 -
2023-07-19 16:20:05,826:INFO:modifiedmom:main.py:144:handleKline:2218259: self.closeSec=1689754799, self.tradeDate='20230719', self.openTime='161000', self.closeTime='161959',self.symbol='BTCUSDT',self.open='29943.9', self.close='29982.7'
2023-07-19 16:20:06,256:INFO:modifiedmom:main.py:145:handleKline:2218259: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
525  20230719   153000    153959  1689752399  30035.2  30011.7 -0.000779
526  20230719   154000    154959  1689752999  30011.7    29973 -0.001289
527  20230719   155000    155959  1689753599  29972.9    29984  0.000367
528  20230719   160000    160959  1689754199  29984.1    29944 -0.001334
529  20230719   161000    161959  1689754799  29943.9  29982.7  0.001292
2023-07-19 16:20:06,256:INFO:modifiedmom:main.py:146:handleKline:2218259: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True}


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

17519  20230719   155000    155959  1689753599  29972.9    29984
2023-07-19 16:00:02,323:INFO:pyemd2:main.py:127:handleKline:2217508: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=9539 

self.closeSec=1689754199, self.tradeDate='20230719', self.openTime='160000', self.closeTime='160959', self.symbol='BTCUSDT', self.open='29984.1', self.close='29944'
2023-07-19 16:10:01,129:INFO:pyemd2:main.py:125:handleKline:2217508: self.closeSec=1689754199, self.tradeDate='20230719', self.openTime='160000', self.closeTime='160959',self.symbol='BTCUSDT',self.open='29984.1', self.close='29944'
127.0.0.1 - - [19/Jul/2023 16:10:01] "POST / HTTP/1.1" 200 -
2023-07-19 16:10:01,143:INFO:pyemd2:main.py:126:handleKline:2217508: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17516  20230719   152000    152959  1689751799  30030.7  30035.1
17517  20230719   153000    153959  1689752399  30035.2  30011.7
17518  20230719   154000    154959  1689752999  30011.7    29973
17519  20230719   155000    155959  1689753599  29972.9    29984
17520  20230719   160000    160959  1689754199  29984.1    29944
2023-07-19 16:10:01,143:INFO:pyemd2:main.py:127:handleKline:2217508: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=9540 

self.closeSec=1689754799, self.tradeDate='20230719', self.openTime='161000', self.closeTime='161959', self.symbol='BTCUSDT', self.open='29943.9', self.close='29982.7'
127.0.0.1 - - [19/Jul/2023 16:20:04] "POST / HTTP/1.1" 200 -
2023-07-19 16:20:06,817:INFO:pyemd2:main.py:125:handleKline:2217508: self.closeSec=1689754799, self.tradeDate='20230719', self.openTime='161000', self.closeTime='161959',self.symbol='BTCUSDT',self.open='29943.9', self.close='29982.7'
2023-07-19 16:20:06,998:INFO:pyemd2:main.py:126:handleKline:2217508: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17517  20230719   153000    153959  1689752399  30035.2  30011.7
17518  20230719   154000    154959  1689752999  30011.7    29973
17519  20230719   155000    155959  1689753599  29972.9    29984
17520  20230719   160000    160959  1689754199  29984.1    29944
17521  20230719   161000    161959  1689754799  29943.9  29982.7
2023-07-19 16:20:06,999:INFO:pyemd2:main.py:127:handleKline:2217508: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}


## /root/FIL/strategy/similarity/log.txt ----- -----

12191  20230719   155000    155959  1689753599  29972.9    29984
2023-07-19 16:00:02,310:INFO:testStrategy:main.py:103:handleKline:2217133: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=9539 

self.closeSec=1689754199, self.tradeDate='20230719', self.openTime='160000', self.closeTime='160959', self.symbol='BTCUSDT', self.open='29984.1', self.close='29944'
127.0.0.1 - - [19/Jul/2023 16:10:01] "POST / HTTP/1.1" 200 -
2023-07-19 16:10:01,128:INFO:testStrategy:main.py:101:handleKline:2217133: self.closeSec=1689754199, self.tradeDate='20230719', self.openTime='160000', self.closeTime='160959',self.symbol='BTCUSDT',self.open='29984.1', self.close='29944'
2023-07-19 16:10:01,136:INFO:testStrategy:main.py:102:handleKline:2217133: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12188  20230719   152000    152959  1689751799  30030.7  30035.1
12189  20230719   153000    153959  1689752399  30035.2  30011.7
12190  20230719   154000    154959  1689752999  30011.7    29973
12191  20230719   155000    155959  1689753599  29972.9    29984
12192  20230719   160000    160959  1689754199  29984.1    29944
2023-07-19 16:10:01,136:INFO:testStrategy:main.py:103:handleKline:2217133: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=9540 

self.closeSec=1689754799, self.tradeDate='20230719', self.openTime='161000', self.closeTime='161959', self.symbol='BTCUSDT', self.open='29943.9', self.close='29982.7'
127.0.0.1 - - [19/Jul/2023 16:20:04] "POST / HTTP/1.1" 200 -
2023-07-19 16:20:06,669:INFO:testStrategy:main.py:101:handleKline:2217133: self.closeSec=1689754799, self.tradeDate='20230719', self.openTime='161000', self.closeTime='161959',self.symbol='BTCUSDT',self.open='29943.9', self.close='29982.7'
2023-07-19 16:20:06,856:INFO:testStrategy:main.py:102:handleKline:2217133: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12189  20230719   153000    153959  1689752399  30035.2  30011.7
12190  20230719   154000    154959  1689752999  30011.7    29973
12191  20230719   155000    155959  1689753599  29972.9    29984
12192  20230719   160000    160959  1689754199  29984.1    29944
12193  20230719   161000    161959  1689754799  29943.9  29982.7
2023-07-19 16:20:06,857:INFO:testStrategy:main.py:103:handleKline:2217133: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}


## /root/FIL/strategy/sr_min/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=1, self.total=996015.990996, self.flagDict['side']='buy', self.tradeCount=1, self.count=19072
self.closeSec=1689754799, self.tradeDate='20230719', self.openTime='161500', self.closeTime='161959', self.symbol='BTCUSDT', self.open=29968.3, self.close=29982.7, self.high=29982.8, self.low=29956.0, self.vol=464.106, self.amt=13908934.4266 
127.0.0.1 - - [19/Jul/2023 16:20:01] "POST / HTTP/1.1" 200 -
2023-07-19 16:20:04,735:INFO:sr_min:main.py:172:handleKline:2219263: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5951  20230719   155500    155959  ...         0.0        0.0       0
5952  20230719   160000    160459  ...         0.0        0.0       0
5953  20230719   160500    160959  ...         0.0        0.0       0
5954  20230719   161000    161459  ...         0.0        0.0       0
5955  20230719   161500    161959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-07-19 16:20:04,757:INFO:sr_min:main.py:175:handleKline:2219263: self.closeSec=1689754799, self.tradeDate='20230719', self.openTime='161500', self.closeTime='161959',self.symbol='BTCUSDT',self.open=29968.3, self.close=29982.7, self.high=29982.8, self.low=29956.0, self.vol=464.106, self.amt=13908934.4266, ukdf['pct'].iloc[-1]=0.000484 , ukdf['amount'].iloc[-1]=13908934.4266, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5955, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '37.141', 'enterprice': '26844', 'countrevence': '0', 'unrealprofit': '116589.3131', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '29983.1', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=1
127.0.0.1 - - [19/Jul/2023 16:25:00] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=1, self.total=996015.990996, self.flagDict['side']='buy', self.tradeCount=1, self.count=19073
self.closeSec=1689755099, self.tradeDate='20230719', self.openTime='162000', self.closeTime='162459', self.symbol='BTCUSDT', self.open=29982.8, self.close=29993.4, self.high=29996.0, self.low=29977.9, self.vol=622.986, self.amt=18682424.6867 
2023-07-19 16:25:00,802:INFO:sr_min:main.py:172:handleKline:2219263: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5952  20230719   160000    160459  ...         0.0        0.0       0
5953  20230719   160500    160959  ...         0.0        0.0       0
5954  20230719   161000    161459  ...         0.0        0.0       0
5955  20230719   161500    161959  ...         0.0        0.0       0
5956  20230719   162000    162459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-07-19 16:25:00,802:INFO:sr_min:main.py:175:handleKline:2219263: self.closeSec=1689755099, self.tradeDate='20230719', self.openTime='162000', self.closeTime='162459',self.symbol='BTCUSDT',self.open=29982.8, self.close=29993.4, self.high=29996.0, self.low=29977.9, self.vol=622.986, self.amt=18682424.6867, ukdf['pct'].iloc[-1]=0.000357 , ukdf['amount'].iloc[-1]=18682424.6867, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5956, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '37.141', 'enterprice': '26844', 'countrevence': '0', 'unrealprofit': '116971.8654', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '29993.4', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=1


## /root/FIL/strategy/s_rsrs/log.txt ----- -----

721  20230719   040000    075959  1689724799  ...    721  0.176731 -1.095059    -1.0
722  20230719   080000    115959  1689739199  ...    722  0.191430 -1.054658    -1.0

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '52.176', 'enterprice': '29870.6', 'countrevence': '0', 'unrealprofit': '-9506.4672', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '30052.8', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-1, self.sign=-1
127.0.0.1 - - [19/Jul/2023 16:00:01] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='s_rsrs', self.symbol='BTCUSDT', interval='4h', intervalSec=14400, wid=25, thd=0.6, self.sign=-1, self.total=1556969.8971744, self.flagDict['side']='sell', self.tradeCount=12, self.count=397
self.closeSec=1689753599, self.tradeDate='20230719', self.openTime='120000', self.closeTime='155959', self.symbol='BTCUSDT', self.open=30048.0, self.close=29984.0, self.high=30178.5, self.low=29950.1, self.vol=41398.75, self.amt=1244758027.84923 
2023-07-19 16:00:01,925:INFO:s_rsrs:main.py:141:handleKline:2218689: self.closeSec=1689753599, self.tradeDate='20230719', self.openTime='120000', self.closeTime='155959',self.symbol='BTCUSDT',self.open=30048.0, self.close=29984.0, self.high=30178.5, self.low=29950.1, self.vol=41398.75, self.amt=1244758027.84923 
2023-07-19 16:00:01,943:INFO:s_rsrs:main.py:142:handleKline:2218689: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime  ...        vol           amt       pct
719  20230718   200000    235959  ...  98912.984  2.951515e+09  0.000773
720  20230719   000000    035959  ...  88550.243  2.633595e+09 -0.006255
721  20230719   040000    075959  ...  27128.255  8.078315e+08  0.004628
722  20230719   080000    115959  ...  46282.264  1.387938e+09  0.006782
723  20230719   120000    155959  ...  41398.750  1.244758e+09 -0.002130

[5 rows x 11 columns]
2023-07-19 16:00:02,619:INFO:s_rsrs:main.py:151:handleKline:2218689: df_s.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec  ...  index      beta    zscore  signal
719  20230718   200000    235959  1689695999  ...    719  0.126414 -1.279727    -1.0
720  20230719   000000    035959  1689710399  ...    720  0.008772 -1.763798    -1.0
721  20230719   040000    075959  1689724799  ...    721  0.176731 -1.095059    -1.0
722  20230719   080000    115959  1689739199  ...    722  0.191430 -1.054658    -1.0
723  20230719   120000    155959  1689753599  ...    723  0.187934 -1.089182    -1.0

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '52.176', 'enterprice': '29870.6', 'countrevence': '0', 'unrealprofit': '-6158.71896186144', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '29988.63739194', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-1, self.sign=-1


