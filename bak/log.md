# 20230624 16:26:01

## /root/FIL/strategy/amihud/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=373746.4768026, self.flagDict['side']='sell', self.tradeCount=2, self.count=11872
self.closeSec=1687594799, self.tradeDate='20230624', self.openTime='161500', self.closeTime='161959', self.symbol='BTCUSDT', self.open=30620.8, self.close=30630.5, self.high=30645.3, self.low=30620.7, self.vol=776.226, self.amt=23778302.4259 
127.0.0.1 - - [24/Jun/2023 16:20:01] "POST / HTTP/1.1" 200 -
2023-06-24 16:20:07,602:INFO:amihud:main.py:172:handleKline:2219019: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5951  20230624   155500    155959  ...         0.0        0.0       0
5952  20230624   160000    160459  ...         0.0        0.0       0
5953  20230624   160500    160959  ...         0.0        0.0       0
5954  20230624   161000    161459  ...         0.0        0.0       0
5955  20230624   161500    161959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-06-24 16:20:07,622:INFO:amihud:main.py:175:handleKline:2219019: self.closeSec=1687594799, self.tradeDate='20230624', self.openTime='161500', self.closeTime='161959',self.symbol='BTCUSDT',self.open=30620.8, self.close=30630.5, self.high=30645.3, self.low=30620.7, self.vol=776.226, self.amt=23778302.4259, ukdf['pct'].iloc[-1]=0.000317 , ukdf['amount'].iloc[-1]=23778302.4259, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5955, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '13.926', 'enterprice': '26864.9', 'countrevence': '0', 'unrealprofit': '-52516.3386', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '30636', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1
127.0.0.1 - - [24/Jun/2023 16:25:00] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=373746.4768026, self.flagDict['side']='sell', self.tradeCount=2, self.count=11873
self.closeSec=1687595099, self.tradeDate='20230624', self.openTime='162000', self.closeTime='162459', self.symbol='BTCUSDT', self.open=30630.4, self.close=30613.4, self.high=30636.2, self.low=30600.9, self.vol=556.51, self.amt=17039808.8447 
2023-06-24 16:25:00,791:INFO:amihud:main.py:172:handleKline:2219019: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5952  20230624   160000    160459  ...         0.0        0.0       0
5953  20230624   160500    160959  ...         0.0        0.0       0
5954  20230624   161000    161459  ...         0.0        0.0       0
5955  20230624   161500    161959  ...         0.0        0.0       0
5956  20230624   162000    162459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-06-24 16:25:00,792:INFO:amihud:main.py:175:handleKline:2219019: self.closeSec=1687595099, self.tradeDate='20230624', self.openTime='162000', self.closeTime='162459',self.symbol='BTCUSDT',self.open=30630.4, self.close=30613.4, self.high=30636.2, self.low=30600.9, self.vol=556.51, self.amt=17039808.8447, ukdf['pct'].iloc[-1]=-0.000558 , ukdf['amount'].iloc[-1]=17039808.8447, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5956, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '13.926', 'enterprice': '26864.9', 'countrevence': '0', 'unrealprofit': '-52201.611', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '30613.4', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1


## /root/FIL/strategy/factorcheck/log.txt ----- -----


self.closeSec=1687594799, self.tradeDate='20230624', self.openTime='161500', self.closeTime='161959', self.symbol='BTCUSDT', self.open=30620.8, self.close=30630.5, self.high=30645.3, self.low=30620.7 
127.0.0.1 - - [24/Jun/2023 16:20:01] "POST / HTTP/1.1" 200 -
2023-06-24 16:20:05,052:INFO:factorcheck2:main.py:126:handleKline:2218005: self.closeSec=1687594799, self.tradeDate='20230624', self.openTime='161500', self.closeTime='161959',self.symbol='BTCUSDT',self.open=30620.8, self.close=30630.5, self.high=30645.3, self.low=30620.7   
2023-06-24 16:20:06,642:INFO:factorcheck2:main.py:127:handleKline:2218005: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1631  20230624   155500    155959  1687593599  ...  30550.0 -0.000350   1631    5
1632  20230624   160000    160459  1687593899  ...  30555.1  0.000926   1632    0
1633  20230624   160500    160959  1687594199  ...  30587.1  0.000526   1633    1
1634  20230624   161000    161459  1687594499  ...  30599.3  0.000461   1634    2
1635  20230624   161500    161959  1687594799  ...  30620.7  0.000317   1635    3

[5 rows x 11 columns]
2023-06-24 16:20:06,652:INFO:factorcheck2:main.py:128:handleKline:2218005: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=357, self.factor=0.42390384837639294, self.count=11875 

self.closeSec=1687595099, self.tradeDate='20230624', self.openTime='162000', self.closeTime='162459', self.symbol='BTCUSDT', self.open=30630.4, self.close=30613.4, self.high=30636.2, self.low=30600.9 
127.0.0.1 - - [24/Jun/2023 16:25:00] "POST / HTTP/1.1" 200 -
2023-06-24 16:25:00,727:INFO:factorcheck2:main.py:126:handleKline:2218005: self.closeSec=1687595099, self.tradeDate='20230624', self.openTime='162000', self.closeTime='162459',self.symbol='BTCUSDT',self.open=30630.4, self.close=30613.4, self.high=30636.2, self.low=30600.9   
2023-06-24 16:25:00,766:INFO:factorcheck2:main.py:127:handleKline:2218005: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1632  20230624   160000    160459  1687593899  ...  30555.1  0.000926   1632    0
1633  20230624   160500    160959  1687594199  ...  30587.1  0.000526   1633    1
1634  20230624   161000    161459  1687594499  ...  30599.3  0.000461   1634    2
1635  20230624   161500    161959  1687594799  ...  30620.7  0.000317   1635    3
1636  20230624   162000    162459  1687595099  ...  30600.9 -0.000558   1636    4

[5 rows x 11 columns]
2023-06-24 16:25:00,769:INFO:factorcheck2:main.py:128:handleKline:2218005: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}


## /root/FIL/strategy/logic/log.txt ----- -----

2023-06-24 16:00:19,492:DEBUG:logic:main.py:463:getModel:2218526: df_s.iloc[-5:,:] :
          date closeTime     open  ...    alpha58   alpha67   alpha72
5786  20230624    132959  30693.7  ...  54.583333  0.562951  0.464583
5787  20230624    135959  30732.5  ...  54.166667  0.560959  0.466246
5788  20230624    142959  30717.3  ...  54.166667  0.553476  0.470170
5789  20230624    145959  30660.5  ...  54.583333  0.556637  0.472590
5790  20230624    152959  30690.2  ...  54.583333  0.555801  0.475108

[5 rows x 33 columns]
0.559040590405904
acc is : 0.559040590405904
2023-06-24 16:00:19,579:INFO:logic:main.py:468:getModel:2218526: df_pred.iloc[-5:,:] :
     pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
537     1  0.488921  0.511079       0  ...  1.179489  -1.0    0.0  1.187904
538     1  0.483082  0.516918       0  ...  1.181674  -1.0    0.0  1.185704
539     1  0.479680  0.520320       1  ...  1.180526  -1.0    0.0  1.186856
540     0  0.502577  0.497423       0  ...  1.180764  -1.0    0.0  1.186616
541     1  0.494134  0.505866       0  ...  1.185405  -1.0    0.0  1.181952

[5 rows x 10 columns]
2023-06-24 16:00:19,590:INFO:logic:main.py:478:getModel:2218526: df_panel.iloc[-5:,:] :
    pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
45     1  0.489100  0.510900       0  ...  1.179489  -1.0    0.0  1.185017
46     1  0.483370  0.516630       0  ...  1.181674  -1.0    0.0  1.183575
47     1  0.479733  0.520267       1  ...  1.180526  -1.0    0.0  1.185192
48     0  0.502456  0.497544       0  ...  1.180764  -1.0    0.0  1.181872
49     1  0.494134  0.505866       0  ...  1.185405  -1.0    0.0  1.181952

[5 rows x 10 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '26.697', 'enterprice': '30938.2', 'countrevence': '0', 'unrealprofit': '10136.8509', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '30558.5', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}


## /root/FIL/strategy/modifiedmom/log.txt ----- -----

527  20230624   155000    155959  1687593599  30612.9  30563.4 -0.001617
2023-06-24 16:00:02,082:INFO:modifiedmom:main.py:146:handleKline:2218259: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': True, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True}

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=5936 

self.closeSec=1687594199, self.tradeDate='20230624', self.openTime='160000', self.closeTime='160959', self.symbol='BTCUSDT', self.open='30563.3', self.close='30606.7'
2023-06-24 16:10:01,193:INFO:modifiedmom:main.py:144:handleKline:2218259: self.closeSec=1687594199, self.tradeDate='20230624', self.openTime='160000', self.closeTime='160959',self.symbol='BTCUSDT',self.open='30563.3', self.close='30606.7'
127.0.0.1 - - [24/Jun/2023 16:10:01] "POST / HTTP/1.1" 200 -
2023-06-24 16:10:01,215:INFO:modifiedmom:main.py:145:handleKline:2218259: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
524  20230624   152000    152959  1687591799  30659.5    30684  0.000802
525  20230624   153000    153959  1687592399    30684  30624.5 -0.001939
526  20230624   154000    154959  1687592999  30624.4  30612.9 -0.000379
527  20230624   155000    155959  1687593599  30612.9  30563.4 -0.001617
528  20230624   160000    160959  1687594199  30563.3  30606.7  0.001417
2023-06-24 16:10:01,216:INFO:modifiedmom:main.py:146:handleKline:2218259: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': True, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True}

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=5937 

self.closeSec=1687594799, self.tradeDate='20230624', self.openTime='161000', self.closeTime='161959', self.symbol='BTCUSDT', self.open='30610.8', self.close='30630.5'
127.0.0.1 - - [24/Jun/2023 16:20:04] "POST / HTTP/1.1" 200 -
2023-06-24 16:20:07,341:INFO:modifiedmom:main.py:144:handleKline:2218259: self.closeSec=1687594799, self.tradeDate='20230624', self.openTime='161000', self.closeTime='161959',self.symbol='BTCUSDT',self.open='30610.8', self.close='30630.5'
2023-06-24 16:20:08,141:INFO:modifiedmom:main.py:145:handleKline:2218259: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
525  20230624   153000    153959  1687592399    30684  30624.5 -0.001939
526  20230624   154000    154959  1687592999  30624.4  30612.9 -0.000379
527  20230624   155000    155959  1687593599  30612.9  30563.4 -0.001617
528  20230624   160000    160959  1687594199  30563.3  30606.7  0.001417
529  20230624   161000    161959  1687594799  30610.8  30630.5  0.000778
2023-06-24 16:20:08,142:INFO:modifiedmom:main.py:146:handleKline:2218259: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': True, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True}


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

17519  20230624   155000    155959  1687593599  30612.9  30563.4
2023-06-24 16:00:02,165:INFO:pyemd2:main.py:127:handleKline:2217508: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=5939 

self.closeSec=1687594199, self.tradeDate='20230624', self.openTime='160000', self.closeTime='160959', self.symbol='BTCUSDT', self.open='30563.3', self.close='30606.7'
2023-06-24 16:10:01,205:INFO:pyemd2:main.py:125:handleKline:2217508: self.closeSec=1687594199, self.tradeDate='20230624', self.openTime='160000', self.closeTime='160959',self.symbol='BTCUSDT',self.open='30563.3', self.close='30606.7'
127.0.0.1 - - [24/Jun/2023 16:10:01] "POST / HTTP/1.1" 200 -
2023-06-24 16:10:01,220:INFO:pyemd2:main.py:126:handleKline:2217508: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17516  20230624   152000    152959  1687591799  30659.5    30684
17517  20230624   153000    153959  1687592399    30684  30624.5
17518  20230624   154000    154959  1687592999  30624.4  30612.9
17519  20230624   155000    155959  1687593599  30612.9  30563.4
17520  20230624   160000    160959  1687594199  30563.3  30606.7
2023-06-24 16:10:01,220:INFO:pyemd2:main.py:127:handleKline:2217508: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=5940 

self.closeSec=1687594799, self.tradeDate='20230624', self.openTime='161000', self.closeTime='161959', self.symbol='BTCUSDT', self.open='30610.8', self.close='30630.5'
127.0.0.1 - - [24/Jun/2023 16:20:04] "POST / HTTP/1.1" 200 -
2023-06-24 16:20:09,483:INFO:pyemd2:main.py:125:handleKline:2217508: self.closeSec=1687594799, self.tradeDate='20230624', self.openTime='161000', self.closeTime='161959',self.symbol='BTCUSDT',self.open='30610.8', self.close='30630.5'
2023-06-24 16:20:09,625:INFO:pyemd2:main.py:126:handleKline:2217508: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17517  20230624   153000    153959  1687592399    30684  30624.5
17518  20230624   154000    154959  1687592999  30624.4  30612.9
17519  20230624   155000    155959  1687593599  30612.9  30563.4
17520  20230624   160000    160959  1687594199  30563.3  30606.7
17521  20230624   161000    161959  1687594799  30610.8  30630.5
2023-06-24 16:20:09,625:INFO:pyemd2:main.py:127:handleKline:2217508: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}


## /root/FIL/strategy/similarity/log.txt ----- -----

12191  20230624   155000    155959  1687593599  30612.9  30563.4
2023-06-24 16:00:02,157:INFO:testStrategy:main.py:103:handleKline:2217133: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}
127.0.0.1 - - [24/Jun/2023 16:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=5939 

self.closeSec=1687594199, self.tradeDate='20230624', self.openTime='160000', self.closeTime='160959', self.symbol='BTCUSDT', self.open='30563.3', self.close='30606.7'
2023-06-24 16:10:01,215:INFO:testStrategy:main.py:101:handleKline:2217133: self.closeSec=1687594199, self.tradeDate='20230624', self.openTime='160000', self.closeTime='160959',self.symbol='BTCUSDT',self.open='30563.3', self.close='30606.7'
2023-06-24 16:10:01,224:INFO:testStrategy:main.py:102:handleKline:2217133: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12188  20230624   152000    152959  1687591799  30659.5    30684
12189  20230624   153000    153959  1687592399    30684  30624.5
12190  20230624   154000    154959  1687592999  30624.4  30612.9
12191  20230624   155000    155959  1687593599  30612.9  30563.4
12192  20230624   160000    160959  1687594199  30563.3  30606.7
2023-06-24 16:10:01,224:INFO:testStrategy:main.py:103:handleKline:2217133: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=5940 

self.closeSec=1687594799, self.tradeDate='20230624', self.openTime='161000', self.closeTime='161959', self.symbol='BTCUSDT', self.open='30610.8', self.close='30630.5'
127.0.0.1 - - [24/Jun/2023 16:20:04] "POST / HTTP/1.1" 200 -
2023-06-24 16:20:08,974:INFO:testStrategy:main.py:101:handleKline:2217133: self.closeSec=1687594799, self.tradeDate='20230624', self.openTime='161000', self.closeTime='161959',self.symbol='BTCUSDT',self.open='30610.8', self.close='30630.5'
2023-06-24 16:20:09,301:INFO:testStrategy:main.py:102:handleKline:2217133: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12189  20230624   153000    153959  1687592399    30684  30624.5
12190  20230624   154000    154959  1687592999  30624.4  30612.9
12191  20230624   155000    155959  1687593599  30612.9  30563.4
12192  20230624   160000    160959  1687594199  30563.3  30606.7
12193  20230624   161000    161959  1687594799  30610.8  30630.5
2023-06-24 16:20:09,302:INFO:testStrategy:main.py:103:handleKline:2217133: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}


## /root/FIL/strategy/sr_min/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=1, self.total=996015.990996, self.flagDict['side']='buy', self.tradeCount=1, self.count=11872
self.closeSec=1687594799, self.tradeDate='20230624', self.openTime='161500', self.closeTime='161959', self.symbol='BTCUSDT', self.open=30620.8, self.close=30630.5, self.high=30645.3, self.low=30620.7, self.vol=776.226, self.amt=23778302.4259 
127.0.0.1 - - [24/Jun/2023 16:20:01] "POST / HTTP/1.1" 200 -
2023-06-24 16:20:07,603:INFO:sr_min:main.py:172:handleKline:2219263: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5951  20230624   155500    155959  ...         0.0        0.0       0
5952  20230624   160000    160459  ...         0.0        0.0       0
5953  20230624   160500    160959  ...         0.0        0.0       0
5954  20230624   161000    161459  ...         0.0        0.0       0
5955  20230624   161500    161959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-06-24 16:20:07,633:INFO:sr_min:main.py:175:handleKline:2219263: self.closeSec=1687594799, self.tradeDate='20230624', self.openTime='161500', self.closeTime='161959',self.symbol='BTCUSDT',self.open=30620.8, self.close=30630.5, self.high=30645.3, self.low=30620.7, self.vol=776.226, self.amt=23778302.4259, ukdf['pct'].iloc[-1]=0.000317 , ukdf['amount'].iloc[-1]=23778302.4259, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5955, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '37.141', 'enterprice': '26844', 'countrevence': '0', 'unrealprofit': '140834.9579', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '30635.9', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=1
127.0.0.1 - - [24/Jun/2023 16:25:00] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=1, self.total=996015.990996, self.flagDict['side']='buy', self.tradeCount=1, self.count=11873
self.closeSec=1687595099, self.tradeDate='20230624', self.openTime='162000', self.closeTime='162459', self.symbol='BTCUSDT', self.open=30630.4, self.close=30613.4, self.high=30636.2, self.low=30600.9, self.vol=556.51, self.amt=17039808.8447 
2023-06-24 16:25:00,793:INFO:sr_min:main.py:172:handleKline:2219263: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5952  20230624   160000    160459  ...         0.0        0.0       0
5953  20230624   160500    160959  ...         0.0        0.0       0
5954  20230624   161000    161459  ...         0.0        0.0       0
5955  20230624   161500    161959  ...         0.0        0.0       0
5956  20230624   162000    162459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-06-24 16:25:00,793:INFO:sr_min:main.py:175:handleKline:2219263: self.closeSec=1687595099, self.tradeDate='20230624', self.openTime='162000', self.closeTime='162459',self.symbol='BTCUSDT',self.open=30630.4, self.close=30613.4, self.high=30636.2, self.low=30600.9, self.vol=556.51, self.amt=17039808.8447, ukdf['pct'].iloc[-1]=-0.000558 , ukdf['amount'].iloc[-1]=17039808.8447, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5956, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '37.141', 'enterprice': '26844', 'countrevence': '0', 'unrealprofit': '139999.2854', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '30613.4', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=1


## /root/FIL/strategy/s_rsrs/log.txt ----- -----

721  20230624   040000    075959  1687564799  ...    721  1.016542  1.251985     1.0
722  20230624   080000    115959  1687579199  ...    722  0.965802  1.084653     1.0

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '53.344', 'enterprice': '27977.7', 'countrevence': '0', 'unrealprofit': '146480.89364173088', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '30723.66756227', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=1, self.sign=1
127.0.0.1 - - [24/Jun/2023 16:00:01] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='s_rsrs', self.symbol='BTCUSDT', interval='4h', intervalSec=14400, wid=25, thd=0.6, self.sign=1, self.total=1490949.9863712, self.flagDict['side']='buy', self.tradeCount=7, self.count=247
self.closeSec=1687593599, self.tradeDate='20230624', self.openTime='120000', self.closeTime='155959', self.symbol='BTCUSDT', self.open=30719.5, self.close=30563.4, self.high=30750.0, self.low=30550.0, self.vol=29137.58, self.amt=893519241.3511 
2023-06-24 16:00:01,653:INFO:s_rsrs:main.py:141:handleKline:2218689: self.closeSec=1687593599, self.tradeDate='20230624', self.openTime='120000', self.closeTime='155959',self.symbol='BTCUSDT',self.open=30719.5, self.close=30563.4, self.high=30750.0, self.low=30550.0, self.vol=29137.58, self.amt=893519241.3511 
2023-06-24 16:00:01,696:INFO:s_rsrs:main.py:142:handleKline:2218689: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime  ...         vol           amt       pct
719  20230623   200000    235959  ...  269745.999  8.259525e+09  0.036939
720  20230624   000000    035959  ...  228949.781  7.104221e+09 -0.011665
721  20230624   040000    075959  ...   66965.089  2.054059e+09 -0.006488
722  20230624   080000    115959  ...   57323.090  1.754468e+09  0.001503
723  20230624   120000    155959  ...   29137.580  8.935192e+08 -0.005081

[5 rows x 11 columns]
2023-06-24 16:00:03,242:INFO:s_rsrs:main.py:151:handleKline:2218689: df_s.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec  ...  index      beta    zscore  signal
719  20230623   200000    235959  1687535999  ...    719  1.006118  1.272443     1.0
720  20230624   000000    035959  1687550399  ...    720  0.997185  1.221229     1.0
721  20230624   040000    075959  1687564799  ...    721  1.016542  1.251985     1.0
722  20230624   080000    115959  1687579199  ...    722  0.965802  1.084653     1.0
723  20230624   120000    155959  1687593599  ...    723  0.910667  0.909653     1.0

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '53.344', 'enterprice': '27977.7', 'countrevence': '0', 'unrealprofit': '137931.5808', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '30563.4', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=1, self.sign=1


