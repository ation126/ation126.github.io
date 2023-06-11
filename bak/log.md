# 20230611 16:26:02

## /root/FIL/strategy/amihud/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=373746.4768026, self.flagDict['side']='sell', self.tradeCount=2, self.count=8128
self.closeSec=1686471599, self.tradeDate='20230611', self.openTime='161500', self.closeTime='161959', self.symbol='BTCUSDT', self.open=25736.1, self.close=25759.9, self.high=25760.3, self.low=25734.0, self.vol=495.628, self.amt=12762865.2469 
127.0.0.1 - - [11/Jun/2023 16:20:02] "POST / HTTP/1.1" 200 -
2023-06-11 16:20:08,355:INFO:amihud:main.py:172:handleKline:2219019: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5951  20230611   155500    155959  ...         0.0        0.0       0
5952  20230611   160000    160459  ...         0.0        0.0       0
5953  20230611   160500    160959  ...         0.0        0.0       0
5954  20230611   161000    161459  ...         0.0        0.0       0
5955  20230611   161500    161959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-06-11 16:20:08,405:INFO:amihud:main.py:175:handleKline:2219019: self.closeSec=1686471599, self.tradeDate='20230611', self.openTime='161500', self.closeTime='161959',self.symbol='BTCUSDT',self.open=25736.1, self.close=25759.9, self.high=25760.3, self.low=25734.0, self.vol=495.628, self.amt=12762865.2469, ukdf['pct'].iloc[-1]=0.000925 , ukdf['amount'].iloc[-1]=12762865.2469, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5955, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '13.926', 'enterprice': '26864.9', 'countrevence': '0', 'unrealprofit': '15416.9038797939', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '25757.84098235', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1
--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=373746.4768026, self.flagDict['side']='sell', self.tradeCount=2, self.count=8129
self.closeSec=1686471899, self.tradeDate='20230611', self.openTime='162000', self.closeTime='162459', self.symbol='BTCUSDT', self.open=25759.9, self.close=25743.1, self.high=25760.0, self.low=25743.0, self.vol=245.55, self.amt=6322792.4178 
127.0.0.1 - - [11/Jun/2023 16:25:01] "POST / HTTP/1.1" 200 -
2023-06-11 16:25:04,613:INFO:amihud:main.py:172:handleKline:2219019: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5952  20230611   160000    160459  ...         0.0        0.0       0
5953  20230611   160500    160959  ...         0.0        0.0       0
5954  20230611   161000    161459  ...         0.0        0.0       0
5955  20230611   161500    161959  ...         0.0        0.0       0
5956  20230611   162000    162459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-06-11 16:25:04,617:INFO:amihud:main.py:175:handleKline:2219019: self.closeSec=1686471899, self.tradeDate='20230611', self.openTime='162000', self.closeTime='162459',self.symbol='BTCUSDT',self.open=25759.9, self.close=25743.1, self.high=25760.0, self.low=25743.0, self.vol=245.55, self.amt=6322792.4178, ukdf['pct'].iloc[-1]=-0.000652 , ukdf['amount'].iloc[-1]=6322792.4178, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5956, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '13.926', 'enterprice': '26864.9', 'countrevence': '0', 'unrealprofit': '15622.1868', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '25743.1', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1


## /root/FIL/strategy/factorcheck/log.txt ----- -----


self.closeSec=1686471599, self.tradeDate='20230611', self.openTime='161500', self.closeTime='161959', self.symbol='BTCUSDT', self.open=25736.1, self.close=25759.9, self.high=25760.3, self.low=25734.0 
127.0.0.1 - - [11/Jun/2023 16:20:01] "POST / HTTP/1.1" 200 -
2023-06-11 16:20:05,463:INFO:factorcheck2:main.py:126:handleKline:2218005: self.closeSec=1686471599, self.tradeDate='20230611', self.openTime='161500', self.closeTime='161959',self.symbol='BTCUSDT',self.open=25736.1, self.close=25759.9, self.high=25760.3, self.low=25734.0   
2023-06-11 16:20:07,093:INFO:factorcheck2:main.py:127:handleKline:2218005: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1631  20230611   155500    155959  1686470399  ...  25726.2 -0.000470   1631    5
1632  20230611   160000    160459  1686470699  ...  25721.2 -0.000113   1632    0
1633  20230611   160500    160959  1686470999  ...  25727.2  0.000645   1633    1
1634  20230611   161000    161459  1686471299  ...  25734.5 -0.000218   1634    2
1635  20230611   161500    161959  1686471599  ...  25734.0  0.000925   1635    3

[5 rows x 11 columns]
2023-06-11 16:20:07,112:INFO:factorcheck2:main.py:128:handleKline:2218005: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': False, 'isOpen': True, 'isClose': False, 'isTrig': True}

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.6153503760613465, self.count=8131 

self.closeSec=1686471899, self.tradeDate='20230611', self.openTime='162000', self.closeTime='162459', self.symbol='BTCUSDT', self.open=25759.9, self.close=25743.1, self.high=25760.0, self.low=25743.0 
127.0.0.1 - - [11/Jun/2023 16:25:01] "POST / HTTP/1.1" 200 -
2023-06-11 16:25:03,429:INFO:factorcheck2:main.py:126:handleKline:2218005: self.closeSec=1686471899, self.tradeDate='20230611', self.openTime='162000', self.closeTime='162459',self.symbol='BTCUSDT',self.open=25759.9, self.close=25743.1, self.high=25760.0, self.low=25743.0   
2023-06-11 16:25:04,237:INFO:factorcheck2:main.py:127:handleKline:2218005: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1632  20230611   160000    160459  1686470699  ...  25721.2 -0.000113   1632    0
1633  20230611   160500    160959  1686470999  ...  25727.2  0.000645   1633    1
1634  20230611   161000    161459  1686471299  ...  25734.5 -0.000218   1634    2
1635  20230611   161500    161959  1686471599  ...  25734.0  0.000925   1635    3
1636  20230611   162000    162459  1686471899  ...  25743.0 -0.000652   1636    4

[5 rows x 11 columns]
2023-06-11 16:25:04,246:INFO:factorcheck2:main.py:128:handleKline:2218005: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': False, 'isOpen': True, 'isClose': False, 'isTrig': True}


## /root/FIL/strategy/logic/log.txt ----- -----

2023-06-11 16:00:41,824:DEBUG:logic:main.py:463:getModel:2218526: df_s.iloc[-5:,:] :
          date closeTime     open  ...    alpha58   alpha67   alpha72
5786  20230611    132959  25718.3  ...  50.416667  0.452644  0.570109
5787  20230611    135959  25736.5  ...  50.416667  0.466656  0.558815
5788  20230611    142959  25805.9  ...  50.416667  0.461965  0.550400
5789  20230611    145959  25779.0  ...  50.000000  0.461455  0.542774
5790  20230611    152959  25776.0  ...  49.583333  0.460542  0.536060

[5 rows x 33 columns]
0.5166051660516605
acc is : 0.5166051660516605
2023-06-11 16:00:42,012:INFO:logic:main.py:468:getModel:2218526: df_pred.iloc[-5:,:] :
     pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
537     0  0.505289  0.494711       1  ...  0.984733  -1.0    0.0  0.930103
538     0  0.522771  0.477229       0  ...  0.985759  -1.0    0.0  0.929133
539     0  0.505097  0.494903       0  ...  0.985870  -1.0    0.0  0.929029
540     0  0.512313  0.487687       0  ...  0.986065  -1.0    0.0  0.928845
541     0  0.507432  0.492568       0  ...  0.987707  -1.0    0.0  0.927299

[5 rows x 10 columns]
2023-06-11 16:00:42,034:INFO:logic:main.py:478:getModel:2218526: df_panel.iloc[-5:,:] :
    pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
45     0  0.505304  0.494696       1  ...  0.989867  -1.0    0.0  0.930818
46     0  0.523287  0.476713       0  ...  0.990898  -1.0    0.0  0.930898
47     0  0.505187  0.494813       0  ...  0.991010  -1.0    0.0  0.931211
48     0  0.512546  0.487454       0  ...  0.991206  -1.0    0.0  0.931077
49     0  0.507432  0.492568       0  ...  0.987707  -1.0    0.0  0.927299

[5 rows x 10 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '27.898', 'enterprice': '25555.4', 'countrevence': '0', 'unrealprofit': '-4823.5642', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '25728.3', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}


## /root/FIL/strategy/modifiedmom/log.txt ----- -----

527  20230611   155000    155959  1686470399  25741.4    25728 -0.000521
2023-06-11 16:00:02,314:INFO:modifiedmom:main.py:146:handleKline:2218259: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True}
127.0.0.1 - - [11/Jun/2023 16:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=4064 

self.closeSec=1686470999, self.tradeDate='20230611', self.openTime='160000', self.closeTime='160959', self.symbol='BTCUSDT', self.open='25728', self.close='25741.7'
2023-06-11 16:10:01,200:INFO:modifiedmom:main.py:144:handleKline:2218259: self.closeSec=1686470999, self.tradeDate='20230611', self.openTime='160000', self.closeTime='160959',self.symbol='BTCUSDT',self.open='25728', self.close='25741.7'
2023-06-11 16:10:01,265:INFO:modifiedmom:main.py:145:handleKline:2218259: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
524  20230611   152000    152959  1686468599  25765.4  25770.9  0.000213
525  20230611   153000    153959  1686469199    25771  25751.7 -0.000745
526  20230611   154000    154959  1686469799  25751.6  25741.4 -0.000400
527  20230611   155000    155959  1686470399  25741.4    25728 -0.000521
528  20230611   160000    160959  1686470999    25728  25741.7  0.000532
2023-06-11 16:10:01,265:INFO:modifiedmom:main.py:146:handleKline:2218259: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True}

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=4065 

self.closeSec=1686471599, self.tradeDate='20230611', self.openTime='161000', self.closeTime='161959', self.symbol='BTCUSDT', self.open='25741.7', self.close='25759.9'
127.0.0.1 - - [11/Jun/2023 16:20:05] "POST / HTTP/1.1" 200 -
2023-06-11 16:20:08,814:INFO:modifiedmom:main.py:144:handleKline:2218259: self.closeSec=1686471599, self.tradeDate='20230611', self.openTime='161000', self.closeTime='161959',self.symbol='BTCUSDT',self.open='25741.7', self.close='25759.9'
2023-06-11 16:20:10,035:INFO:modifiedmom:main.py:145:handleKline:2218259: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
525  20230611   153000    153959  1686469199    25771  25751.7 -0.000745
526  20230611   154000    154959  1686469799  25751.6  25741.4 -0.000400
527  20230611   155000    155959  1686470399  25741.4    25728 -0.000521
528  20230611   160000    160959  1686470999    25728  25741.7  0.000532
529  20230611   161000    161959  1686471599  25741.7  25759.9  0.000707
2023-06-11 16:20:10,044:INFO:modifiedmom:main.py:146:handleKline:2218259: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True}


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

17519  20230611   155000    155959  1686470399  25741.4    25728
2023-06-11 16:00:02,312:INFO:pyemd2:main.py:127:handleKline:2217508: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=4067 

self.closeSec=1686470999, self.tradeDate='20230611', self.openTime='160000', self.closeTime='160959', self.symbol='BTCUSDT', self.open='25728', self.close='25741.7'
127.0.0.1 - - [11/Jun/2023 16:10:01] "POST / HTTP/1.1" 200 -
2023-06-11 16:10:01,239:INFO:pyemd2:main.py:125:handleKline:2217508: self.closeSec=1686470999, self.tradeDate='20230611', self.openTime='160000', self.closeTime='160959',self.symbol='BTCUSDT',self.open='25728', self.close='25741.7'
2023-06-11 16:10:01,299:INFO:pyemd2:main.py:126:handleKline:2217508: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17516  20230611   152000    152959  1686468599  25765.4  25770.9
17517  20230611   153000    153959  1686469199    25771  25751.7
17518  20230611   154000    154959  1686469799  25751.6  25741.4
17519  20230611   155000    155959  1686470399  25741.4    25728
17520  20230611   160000    160959  1686470999    25728  25741.7
2023-06-11 16:10:01,299:INFO:pyemd2:main.py:127:handleKline:2217508: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=4068 

self.closeSec=1686471599, self.tradeDate='20230611', self.openTime='161000', self.closeTime='161959', self.symbol='BTCUSDT', self.open='25741.7', self.close='25759.9'
127.0.0.1 - - [11/Jun/2023 16:20:05] "POST / HTTP/1.1" 200 -
2023-06-11 16:20:11,627:INFO:pyemd2:main.py:125:handleKline:2217508: self.closeSec=1686471599, self.tradeDate='20230611', self.openTime='161000', self.closeTime='161959',self.symbol='BTCUSDT',self.open='25741.7', self.close='25759.9'
2023-06-11 16:20:11,838:INFO:pyemd2:main.py:126:handleKline:2217508: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17517  20230611   153000    153959  1686469199    25771  25751.7
17518  20230611   154000    154959  1686469799  25751.6  25741.4
17519  20230611   155000    155959  1686470399  25741.4    25728
17520  20230611   160000    160959  1686470999    25728  25741.7
17521  20230611   161000    161959  1686471599  25741.7  25759.9
2023-06-11 16:20:11,838:INFO:pyemd2:main.py:127:handleKline:2217508: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}


## /root/FIL/strategy/similarity/log.txt ----- -----

12191  20230611   155000    155959  1686470399  25741.4    25728
2023-06-11 16:00:02,312:INFO:testStrategy:main.py:103:handleKline:2217133: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': True, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}
127.0.0.1 - - [11/Jun/2023 16:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=4067 

self.closeSec=1686470999, self.tradeDate='20230611', self.openTime='160000', self.closeTime='160959', self.symbol='BTCUSDT', self.open='25728', self.close='25741.7'
2023-06-11 16:10:01,209:INFO:testStrategy:main.py:101:handleKline:2217133: self.closeSec=1686470999, self.tradeDate='20230611', self.openTime='160000', self.closeTime='160959',self.symbol='BTCUSDT',self.open='25728', self.close='25741.7'
2023-06-11 16:10:01,306:INFO:testStrategy:main.py:102:handleKline:2217133: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12188  20230611   152000    152959  1686468599  25765.4  25770.9
12189  20230611   153000    153959  1686469199    25771  25751.7
12190  20230611   154000    154959  1686469799  25751.6  25741.4
12191  20230611   155000    155959  1686470399  25741.4    25728
12192  20230611   160000    160959  1686470999    25728  25741.7
2023-06-11 16:10:01,309:INFO:testStrategy:main.py:103:handleKline:2217133: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': True, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=4068 

self.closeSec=1686471599, self.tradeDate='20230611', self.openTime='161000', self.closeTime='161959', self.symbol='BTCUSDT', self.open='25741.7', self.close='25759.9'
127.0.0.1 - - [11/Jun/2023 16:20:05] "POST / HTTP/1.1" 200 -
2023-06-11 16:20:11,315:INFO:testStrategy:main.py:101:handleKline:2217133: self.closeSec=1686471599, self.tradeDate='20230611', self.openTime='161000', self.closeTime='161959',self.symbol='BTCUSDT',self.open='25741.7', self.close='25759.9'
2023-06-11 16:20:11,692:INFO:testStrategy:main.py:102:handleKline:2217133: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12189  20230611   153000    153959  1686469199    25771  25751.7
12190  20230611   154000    154959  1686469799  25751.6  25741.4
12191  20230611   155000    155959  1686470399  25741.4    25728
12192  20230611   160000    160959  1686470999    25728  25741.7
12193  20230611   161000    161959  1686471599  25741.7  25759.9
2023-06-11 16:20:11,693:INFO:testStrategy:main.py:103:handleKline:2217133: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': True, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}


## /root/FIL/strategy/sr_min/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=1, self.total=996015.990996, self.flagDict['side']='buy', self.tradeCount=1, self.count=8128
self.closeSec=1686471599, self.tradeDate='20230611', self.openTime='161500', self.closeTime='161959', self.symbol='BTCUSDT', self.open=25736.1, self.close=25759.9, self.high=25760.3, self.low=25734.0, self.vol=495.628, self.amt=12762865.2469 
127.0.0.1 - - [11/Jun/2023 16:20:01] "POST / HTTP/1.1" 200 -
2023-06-11 16:20:08,365:INFO:sr_min:main.py:172:handleKline:2219263: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5951  20230611   155500    155959  ...         0.0        0.0       0
5952  20230611   160000    160459  ...         0.0        0.0       0
5953  20230611   160500    160959  ...         0.0        0.0       0
5954  20230611   161000    161459  ...         0.0        0.0       0
5955  20230611   161500    161959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-06-11 16:20:08,405:INFO:sr_min:main.py:175:handleKline:2219263: self.closeSec=1686471599, self.tradeDate='20230611', self.openTime='161500', self.closeTime='161959',self.symbol='BTCUSDT',self.open=25736.1, self.close=25759.9, self.high=25760.3, self.low=25734.0, self.vol=495.628, self.amt=12762865.2469, ukdf['pct'].iloc[-1]=0.000925 , ukdf['amount'].iloc[-1]=12762865.2469, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5955, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '37.141', 'enterprice': '26844', 'countrevence': '0', 'unrealprofit': '-40340.76990253362', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '25757.84804118', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=1
--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=1, self.total=996015.990996, self.flagDict['side']='buy', self.tradeCount=1, self.count=8129
self.closeSec=1686471899, self.tradeDate='20230611', self.openTime='162000', self.closeTime='162459', self.symbol='BTCUSDT', self.open=25759.9, self.close=25743.1, self.high=25760.0, self.low=25743.0, self.vol=245.55, self.amt=6322792.4178 
127.0.0.1 - - [11/Jun/2023 16:25:01] "POST / HTTP/1.1" 200 -
2023-06-11 16:25:04,616:INFO:sr_min:main.py:172:handleKline:2219263: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5952  20230611   160000    160459  ...         0.0        0.0       0
5953  20230611   160500    160959  ...         0.0        0.0       0
5954  20230611   161000    161459  ...         0.0        0.0       0
5955  20230611   161500    161959  ...         0.0        0.0       0
5956  20230611   162000    162459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-06-11 16:25:04,625:INFO:sr_min:main.py:175:handleKline:2219263: self.closeSec=1686471899, self.tradeDate='20230611', self.openTime='162000', self.closeTime='162459',self.symbol='BTCUSDT',self.open=25759.9, self.close=25743.1, self.high=25760.0, self.low=25743.0, self.vol=245.55, self.amt=6322792.4178, ukdf['pct'].iloc[-1]=-0.000652 , ukdf['amount'].iloc[-1]=6322792.4178, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5956, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '37.141', 'enterprice': '26844', 'countrevence': '0', 'unrealprofit': '-40888.5269', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '25743.1', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=1


## /root/FIL/strategy/s_rsrs/log.txt ----- -----

721  20230611   040000    075959  1686441599  ...    721  0.517683 -0.254692     NaN
722  20230611   080000    115959  1686455999  ...    722  0.496457 -0.320242     NaN

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '55.166', 'enterprice': '27078.6', 'countrevence': '0', 'unrealprofit': '75196.7746', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '25715.5', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-9223372036854775808, self.sign=-1
127.0.0.1 - - [11/Jun/2023 16:00:01] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='s_rsrs', self.symbol='BTCUSDT', interval='4h', intervalSec=14400, wid=25, thd=0.6, self.sign=-1, self.total=1492324.2295523998, self.flagDict['side']='sell', self.tradeCount=4, self.count=169
self.closeSec=1686470399, self.tradeDate='20230611', self.openTime='120000', self.closeTime='155959', self.symbol='BTCUSDT', self.open=25714.7, self.close=25728.0, self.high=25820.1, self.low=25621.3, self.vol=31162.773, self.amt=801835153.2586 
2023-06-11 16:00:01,859:INFO:s_rsrs:main.py:141:handleKline:2218689: self.closeSec=1686470399, self.tradeDate='20230611', self.openTime='120000', self.closeTime='155959',self.symbol='BTCUSDT',self.open=25714.7, self.close=25728.0, self.high=25820.1, self.low=25621.3, self.vol=31162.773, self.amt=801835153.2586 
2023-06-11 16:00:01,934:INFO:s_rsrs:main.py:142:handleKline:2218689: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime  ...         vol           amt       pct
719  20230610   200000    235959  ...   36077.085  9.248559e+08 -0.003838
720  20230611   000000    035959  ...  188175.676  4.844864e+09  0.004614
721  20230611   040000    075959  ...   46686.517  1.203926e+09  0.003435
722  20230611   080000    115959  ...   33043.104  8.513945e+08 -0.004333
723  20230611   120000    155959  ...   31162.773  8.018352e+08  0.000517

[5 rows x 11 columns]
2023-06-11 16:00:04,616:INFO:s_rsrs:main.py:151:handleKline:2218689: df_s.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec  ...  index      beta    zscore  signal
719  20230610   200000    235959  1686412799  ...    719  0.358009 -0.793134    -1.0
720  20230611   000000    035959  1686427199  ...    720  0.349759 -0.808214    -1.0
721  20230611   040000    075959  1686441599  ...    721  0.517683 -0.254692     NaN
722  20230611   080000    115959  1686455999  ...    722  0.496457 -0.320242     NaN
723  20230611   120000    155959  1686470399  ...    723  0.458586 -0.439942     NaN

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '55.166', 'enterprice': '27078.6', 'countrevence': '0', 'unrealprofit': '74507.1996', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '25728', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-9223372036854775808, self.sign=-1


