# 20230609 16:26:01

## /root/FIL/strategy/amihud/log.txt ----- -----

--handleKline--: 127.0.0.1 - - [09/Jun/2023 16:20:01] "POST / HTTP/1.1" 200 -
 version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=373746.4768026, self.flagDict['side']='sell', self.tradeCount=2, self.count=7552
self.closeSec=1686298799, self.tradeDate='20230609', self.openTime='161500', self.closeTime='161959', self.symbol='BTCUSDT', self.open=26505.0, self.close=26569.1, self.high=26600.0, self.low=26505.0, self.vol=4174.607, self.amt=110870690.4863 
2023-06-09 16:20:03,014:INFO:amihud:main.py:172:handleKline:2219019: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5951  20230609   155500    155959  ...         0.0        0.0       0
5952  20230609   160000    160459  ...         0.0        0.0       0
5953  20230609   160500    160959  ...         0.0        0.0       0
5954  20230609   161000    161459  ...         0.0        0.0       0
5955  20230609   161500    161959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-06-09 16:20:03,050:INFO:amihud:main.py:175:handleKline:2219019: self.closeSec=1686298799, self.tradeDate='20230609', self.openTime='161500', self.closeTime='161959',self.symbol='BTCUSDT',self.open=26505.0, self.close=26569.1, self.high=26600.0, self.low=26505.0, self.vol=4174.607, self.amt=110870690.4863, ukdf['pct'].iloc[-1]=0.002415 , ukdf['amount'].iloc[-1]=110870690.4863, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5955, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '13.926', 'enterprice': '26864.9', 'countrevence': '0', 'unrealprofit': '4097.0292', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '26570.7', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1
--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=373746.4768026, self.flagDict['side']='sell', self.tradeCount=2, self.count=7553
self.closeSec=1686299099, self.tradeDate='20230609', self.openTime='162000', self.closeTime='162459', self.symbol='BTCUSDT', self.open=26570.8, self.close=26552.1, self.high=26587.7, self.low=26527.6, self.vol=1922.386, self.amt=51047131.8718 
127.0.0.1 - - [09/Jun/2023 16:25:01] "POST / HTTP/1.1" 200 -
2023-06-09 16:25:04,162:INFO:amihud:main.py:172:handleKline:2219019: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5952  20230609   160000    160459  ...         0.0        0.0       0
5953  20230609   160500    160959  ...         0.0        0.0       0
5954  20230609   161000    161459  ...         0.0        0.0       0
5955  20230609   161500    161959  ...         0.0        0.0       0
5956  20230609   162000    162459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-06-09 16:25:04,168:INFO:amihud:main.py:175:handleKline:2219019: self.closeSec=1686299099, self.tradeDate='20230609', self.openTime='162000', self.closeTime='162459',self.symbol='BTCUSDT',self.open=26570.8, self.close=26552.1, self.high=26587.7, self.low=26527.6, self.vol=1922.386, self.amt=51047131.8718, ukdf['pct'].iloc[-1]=-0.00064 , ukdf['amount'].iloc[-1]=51047131.8718, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5956, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '13.926', 'enterprice': '26864.9', 'countrevence': '0', 'unrealprofit': '4354.6602', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '26552.2', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1


## /root/FIL/strategy/factorcheck/log.txt ----- -----


self.closeSec=1686298799, self.tradeDate='20230609', self.openTime='161500', self.closeTime='161959', self.symbol='BTCUSDT', self.open=26505.0, self.close=26569.1, self.high=26600.0, self.low=26505.0 
127.0.0.1 - - [09/Jun/2023 16:20:01] "POST / HTTP/1.1" 200 -
2023-06-09 16:20:01,602:INFO:factorcheck2:main.py:126:handleKline:2218005: self.closeSec=1686298799, self.tradeDate='20230609', self.openTime='161500', self.closeTime='161959',self.symbol='BTCUSDT',self.open=26505.0, self.close=26569.1, self.high=26600.0, self.low=26505.0   
2023-06-09 16:20:02,451:INFO:factorcheck2:main.py:127:handleKline:2218005: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1631  20230609   155500    155959  1686297599  ...  26464.5  0.000555   1631    5
1632  20230609   160000    160459  1686297899  ...  26476.8  0.000400   1632    0
1633  20230609   160500    160959  1686298199  ...  26484.4 -0.000011   1633    1
1634  20230609   161000    161459  1686298499  ...  26487.9  0.000457   1634    2
1635  20230609   161500    161959  1686298799  ...  26505.0  0.002415   1635    3

[5 rows x 11 columns]
2023-06-09 16:20:02,461:INFO:factorcheck2:main.py:128:handleKline:2218005: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=1, self.factor=0.5228193069064868, self.count=7555 

self.closeSec=1686299099, self.tradeDate='20230609', self.openTime='162000', self.closeTime='162459', self.symbol='BTCUSDT', self.open=26570.8, self.close=26552.1, self.high=26587.7, self.low=26527.6 
127.0.0.1 - - [09/Jun/2023 16:25:01] "POST / HTTP/1.1" 200 -
2023-06-09 16:25:03,077:INFO:factorcheck2:main.py:126:handleKline:2218005: self.closeSec=1686299099, self.tradeDate='20230609', self.openTime='162000', self.closeTime='162459',self.symbol='BTCUSDT',self.open=26570.8, self.close=26552.1, self.high=26587.7, self.low=26527.6   
2023-06-09 16:25:03,818:INFO:factorcheck2:main.py:127:handleKline:2218005: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1632  20230609   160000    160459  1686297899  ...  26476.8  0.000400   1632    0
1633  20230609   160500    160959  1686298199  ...  26484.4 -0.000011   1633    1
1634  20230609   161000    161459  1686298499  ...  26487.9  0.000457   1634    2
1635  20230609   161500    161959  1686298799  ...  26505.0  0.002415   1635    3
1636  20230609   162000    162459  1686299099  ...  26527.6 -0.000640   1636    4

[5 rows x 11 columns]
2023-06-09 16:25:03,826:INFO:factorcheck2:main.py:128:handleKline:2218005: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}


## /root/FIL/strategy/logic/log.txt ----- -----

2023-06-09 16:00:42,673:DEBUG:logic:main.py:463:getModel:2218526: df_s.iloc[-5:,:] :
          date closeTime     open  ...    alpha58   alpha67   alpha72
5786  20230609    132959  26479.0  ...  50.416667  0.498619  0.535673
5787  20230609    135959  26477.7  ...  50.416667  0.502243  0.535895
5788  20230609    142959  26495.9  ...  50.416667  0.509633  0.531682
5789  20230609    145959  26533.4  ...  50.000000  0.499258  0.533813
5790  20230609    152959  26482.1  ...  49.583333  0.494651  0.538521

[5 rows x 33 columns]
0.511070110701107
acc is : 0.511070110701107
2023-06-09 16:00:42,867:INFO:logic:main.py:468:getModel:2218526: df_pred.iloc[-5:,:] :
     pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
537     0  0.502466  0.497534       1  ...  1.061414   1.0    0.0  0.939954
538     0  0.508117  0.491883       1  ...  1.062912   1.0    0.0  0.941281
539     0  0.513929  0.486071       0  ...  1.060857   1.0    0.0  0.939461
540     1  0.497972  0.502028       0  ...  1.059936   1.0    0.0  0.938645
541     1  0.495112  0.504888       1  ...  1.060881   1.0    0.0  0.939483

[5 rows x 10 columns]
2023-06-09 16:00:42,905:INFO:logic:main.py:478:getModel:2218526: df_panel.iloc[-5:,:] :
    pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
45     0  0.502283  0.497717       1  ...  1.046399   1.0    0.0  0.943610
46     0  0.508052  0.491948       1  ...  1.047876   1.0    0.0  0.944817
47     0  0.513907  0.486093       0  ...  1.045850   1.0    0.0  0.943912
48     1  0.498142  0.501858       0  ...  1.044941   1.0    0.0  0.934838
49     1  0.495112  0.504888       1  ...  1.060881   1.0    0.0  0.939483

[5 rows x 10 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '28.647', 'enterprice': '26630.1', 'countrevence': '0', 'unrealprofit': '-4308.72816468897', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '26479.69234249', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}


## /root/FIL/strategy/modifiedmom/log.txt ----- -----

527  20230609   155000    155959  1686297599  26479.4  26482.7  0.000125
2023-06-09 16:00:02,307:INFO:modifiedmom:main.py:146:handleKline:2218259: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': True, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True}
127.0.0.1 - - [09/Jun/2023 16:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=3776 

self.closeSec=1686298199, self.tradeDate='20230609', self.openTime='160000', self.closeTime='160959', self.symbol='BTCUSDT', self.open='26482.7', self.close='26493'
2023-06-09 16:10:01,115:INFO:modifiedmom:main.py:144:handleKline:2218259: self.closeSec=1686298199, self.tradeDate='20230609', self.openTime='160000', self.closeTime='160959',self.symbol='BTCUSDT',self.open='26482.7', self.close='26493'
2023-06-09 16:10:01,148:INFO:modifiedmom:main.py:145:handleKline:2218259: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
524  20230609   152000    152959  1686295799  26456.7  26459.1  0.000087
525  20230609   153000    153959  1686296399    26459    26463  0.000147
526  20230609   154000    154959  1686296999    26463  26479.4  0.000620
527  20230609   155000    155959  1686297599  26479.4  26482.7  0.000125
528  20230609   160000    160959  1686298199  26482.7    26493  0.000389
2023-06-09 16:10:01,148:INFO:modifiedmom:main.py:146:handleKline:2218259: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': True, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True}

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=3777 

self.closeSec=1686298799, self.tradeDate='20230609', self.openTime='161000', self.closeTime='161959', self.symbol='BTCUSDT', self.open='26493', self.close='26570.8'
127.0.0.1 - - [09/Jun/2023 16:20:02] "POST / HTTP/1.1" 200 -
2023-06-09 16:20:04,740:INFO:modifiedmom:main.py:144:handleKline:2218259: self.closeSec=1686298799, self.tradeDate='20230609', self.openTime='161000', self.closeTime='161959',self.symbol='BTCUSDT',self.open='26493', self.close='26570.8'
2023-06-09 16:20:05,400:INFO:modifiedmom:main.py:145:handleKline:2218259: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
525  20230609   153000    153959  1686296399    26459    26463  0.000147
526  20230609   154000    154959  1686296999    26463  26479.4  0.000620
527  20230609   155000    155959  1686297599  26479.4  26482.7  0.000125
528  20230609   160000    160959  1686298199  26482.7    26493  0.000389
529  20230609   161000    161959  1686298799    26493  26570.8  0.002937
2023-06-09 16:20:05,410:INFO:modifiedmom:main.py:146:handleKline:2218259: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': True, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True}


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

17519  20230609   155000    155959  1686297599  26479.4  26482.7
2023-06-09 16:00:02,315:INFO:pyemd2:main.py:127:handleKline:2217508: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=3779 

self.closeSec=1686298199, self.tradeDate='20230609', self.openTime='160000', self.closeTime='160959', self.symbol='BTCUSDT', self.open='26482.7', self.close='26493'
127.0.0.1 - - [09/Jun/2023 16:10:01] "POST / HTTP/1.1" 200 -
2023-06-09 16:10:01,109:INFO:pyemd2:main.py:125:handleKline:2217508: self.closeSec=1686298199, self.tradeDate='20230609', self.openTime='160000', self.closeTime='160959',self.symbol='BTCUSDT',self.open='26482.7', self.close='26493'
2023-06-09 16:10:01,198:INFO:pyemd2:main.py:126:handleKline:2217508: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17516  20230609   152000    152959  1686295799  26456.7  26459.1
17517  20230609   153000    153959  1686296399    26459    26463
17518  20230609   154000    154959  1686296999    26463  26479.4
17519  20230609   155000    155959  1686297599  26479.4  26482.7
17520  20230609   160000    160959  1686298199  26482.7    26493
2023-06-09 16:10:01,198:INFO:pyemd2:main.py:127:handleKline:2217508: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=3780 

self.closeSec=1686298799, self.tradeDate='20230609', self.openTime='161000', self.closeTime='161959', self.symbol='BTCUSDT', self.open='26493', self.close='26570.8'
127.0.0.1 - - [09/Jun/2023 16:20:03] "POST / HTTP/1.1" 200 -
2023-06-09 16:20:06,056:INFO:pyemd2:main.py:125:handleKline:2217508: self.closeSec=1686298799, self.tradeDate='20230609', self.openTime='161000', self.closeTime='161959',self.symbol='BTCUSDT',self.open='26493', self.close='26570.8'
2023-06-09 16:20:06,108:INFO:pyemd2:main.py:126:handleKline:2217508: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17517  20230609   153000    153959  1686296399    26459    26463
17518  20230609   154000    154959  1686296999    26463  26479.4
17519  20230609   155000    155959  1686297599  26479.4  26482.7
17520  20230609   160000    160959  1686298199  26482.7    26493
17521  20230609   161000    161959  1686298799    26493  26570.8
2023-06-09 16:20:06,111:INFO:pyemd2:main.py:127:handleKline:2217508: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}


## /root/FIL/strategy/similarity/log.txt ----- -----

12191  20230609   155000    155959  1686297599  26479.4  26482.7
2023-06-09 16:00:02,241:INFO:testStrategy:main.py:103:handleKline:2217133: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': True, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}
127.0.0.1 - - [09/Jun/2023 16:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=3779 

self.closeSec=1686298199, self.tradeDate='20230609', self.openTime='160000', self.closeTime='160959', self.symbol='BTCUSDT', self.open='26482.7', self.close='26493'
2023-06-09 16:10:01,125:INFO:testStrategy:main.py:101:handleKline:2217133: self.closeSec=1686298199, self.tradeDate='20230609', self.openTime='160000', self.closeTime='160959',self.symbol='BTCUSDT',self.open='26482.7', self.close='26493'
2023-06-09 16:10:01,165:INFO:testStrategy:main.py:102:handleKline:2217133: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12188  20230609   152000    152959  1686295799  26456.7  26459.1
12189  20230609   153000    153959  1686296399    26459    26463
12190  20230609   154000    154959  1686296999    26463  26479.4
12191  20230609   155000    155959  1686297599  26479.4  26482.7
12192  20230609   160000    160959  1686298199  26482.7    26493
2023-06-09 16:10:01,166:INFO:testStrategy:main.py:103:handleKline:2217133: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': True, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=3780 

self.closeSec=1686298799, self.tradeDate='20230609', self.openTime='161000', self.closeTime='161959', self.symbol='BTCUSDT', self.open='26493', self.close='26570.8'
127.0.0.1 - - [09/Jun/2023 16:20:02] "POST / HTTP/1.1" 200 -
2023-06-09 16:20:05,772:INFO:testStrategy:main.py:101:handleKline:2217133: self.closeSec=1686298799, self.tradeDate='20230609', self.openTime='161000', self.closeTime='161959',self.symbol='BTCUSDT',self.open='26493', self.close='26570.8'
2023-06-09 16:20:06,100:INFO:testStrategy:main.py:102:handleKline:2217133: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12189  20230609   153000    153959  1686296399    26459    26463
12190  20230609   154000    154959  1686296999    26463  26479.4
12191  20230609   155000    155959  1686297599  26479.4  26482.7
12192  20230609   160000    160959  1686298199  26482.7    26493
12193  20230609   161000    161959  1686298799    26493  26570.8
2023-06-09 16:20:06,102:INFO:testStrategy:main.py:103:handleKline:2217133: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': True, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}


## /root/FIL/strategy/sr_min/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=1, self.total=996015.990996, self.flagDict['side']='buy', self.tradeCount=1, self.count=7552
self.closeSec=1686298799, self.tradeDate='20230609', self.openTime='161500', self.closeTime='161959', self.symbol='BTCUSDT', self.open=26505.0, self.close=26569.1, self.high=26600.0, self.low=26505.0, self.vol=4174.607, self.amt=110870690.4863 
127.0.0.1 - - [09/Jun/2023 16:20:01] "POST / HTTP/1.1" 200 -
2023-06-09 16:20:02,831:INFO:sr_min:main.py:172:handleKline:2219263: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5951  20230609   155500    155959  ...         0.0        0.0       0
5952  20230609   160000    160459  ...         0.0        0.0       0
5953  20230609   160500    160959  ...         0.0        0.0       0
5954  20230609   161000    161459  ...         0.0        0.0       0
5955  20230609   161500    161959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-06-09 16:20:02,842:INFO:sr_min:main.py:175:handleKline:2219263: self.closeSec=1686298799, self.tradeDate='20230609', self.openTime='161500', self.closeTime='161959',self.symbol='BTCUSDT',self.open=26505.0, self.close=26569.1, self.high=26600.0, self.low=26505.0, self.vol=4174.607, self.amt=110870690.4863, ukdf['pct'].iloc[-1]=0.002415 , ukdf['amount'].iloc[-1]=110870690.4863, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5955, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '37.141', 'enterprice': '26844', 'countrevence': '0', 'unrealprofit': '-10150.6353', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '26570.7', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=1
--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=1, self.total=996015.990996, self.flagDict['side']='buy', self.tradeCount=1, self.count=7553
self.closeSec=1686299099, self.tradeDate='20230609', self.openTime='162000', self.closeTime='162459', self.symbol='BTCUSDT', self.open=26570.8, self.close=26552.1, self.high=26587.7, self.low=26527.6, self.vol=1922.386, self.amt=51047131.8718 
127.0.0.1 - - [09/Jun/2023 16:25:01] "POST / HTTP/1.1" 200 -
2023-06-09 16:25:04,151:INFO:sr_min:main.py:172:handleKline:2219263: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5952  20230609   160000    160459  ...         0.0        0.0       0
5953  20230609   160500    160959  ...         0.0        0.0       0
5954  20230609   161000    161459  ...         0.0        0.0       0
5955  20230609   161500    161959  ...         0.0        0.0       0
5956  20230609   162000    162459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-06-09 16:25:04,161:INFO:sr_min:main.py:175:handleKline:2219263: self.closeSec=1686299099, self.tradeDate='20230609', self.openTime='162000', self.closeTime='162459',self.symbol='BTCUSDT',self.open=26570.8, self.close=26552.1, self.high=26587.7, self.low=26527.6, self.vol=1922.386, self.amt=51047131.8718, ukdf['pct'].iloc[-1]=-0.00064 , ukdf['amount'].iloc[-1]=51047131.8718, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5956, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '37.141', 'enterprice': '26844', 'countrevence': '0', 'unrealprofit': '-10837.7438', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '26552.2', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=1


## /root/FIL/strategy/s_rsrs/log.txt ----- -----

721  20230609   040000    075959  1686268799  ...    721  0.576510 -0.112975     NaN
722  20230609   080000    115959  1686283199  ...    722  0.529046 -0.273858     NaN

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '55.166', 'enterprice': '27078.6', 'countrevence': '0', 'unrealprofit': '33423.51575724288', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '26472.72834432', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-9223372036854775808, self.sign=-1
--handleKline--:  version='2.0.0', self.name='s_rsrs', self.symbol='BTCUSDT', interval='4h', intervalSec=14400, wid=25, thd=0.6, self.sign=-1, self.total=1492324.2295523998, self.flagDict['side']='sell', self.tradeCount=4, self.count=157
self.closeSec=1686297599, self.tradeDate='20230609', self.openTime='120000', self.closeTime='155959', self.symbol='BTCUSDT', self.open=26469.6, self.close=26482.7, self.high=26575.5, self.low=26411.4, self.vol=33723.828, self.amt=893017203.9426 
127.0.0.1 - - [09/Jun/2023 16:00:01] "POST / HTTP/1.1" 200 -
2023-06-09 16:00:01,820:INFO:s_rsrs:main.py:141:handleKline:2218689: self.closeSec=1686297599, self.tradeDate='20230609', self.openTime='120000', self.closeTime='155959',self.symbol='BTCUSDT',self.open=26469.6, self.close=26482.7, self.high=26575.5, self.low=26411.4, self.vol=33723.828, self.amt=893017203.9426 
2023-06-09 16:00:01,881:INFO:s_rsrs:main.py:142:handleKline:2218689: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime  ...         vol           amt       pct
719  20230608   200000    235959  ...  127003.344  3.367355e+09  0.010768
720  20230609   000000    035959  ...   56834.492  1.507574e+09 -0.006703
721  20230609   040000    075959  ...   27001.036  7.172898e+08 -0.001546
722  20230609   080000    115959  ...   59149.513  1.563425e+09 -0.000619
723  20230609   120000    155959  ...   33723.828  8.930172e+08  0.000499

[5 rows x 11 columns]
2023-06-09 16:00:04,423:INFO:s_rsrs:main.py:151:handleKline:2218689: df_s.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec  ...  index      beta    zscore  signal
719  20230608   200000    235959  1686239999  ...    719  0.535715 -0.238526     NaN
720  20230609   000000    035959  1686254399  ...    720  0.549805 -0.197611     NaN
721  20230609   040000    075959  1686268799  ...    721  0.576510 -0.112975     NaN
722  20230609   080000    115959  1686283199  ...    722  0.529046 -0.273858     NaN
723  20230609   120000    155959  1686297599  ...    723  0.493077 -0.392767     NaN

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '55.166', 'enterprice': '27078.6', 'countrevence': '0', 'unrealprofit': '32873.4194', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '26482.7', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-9223372036854775808, self.sign=-1


