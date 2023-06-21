# 20230621 16:26:02

## /root/FIL/strategy/amihud/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=373746.4768026, self.flagDict['side']='sell', self.tradeCount=2, self.count=11008
self.closeSec=1687335599, self.tradeDate='20230621', self.openTime='161500', self.closeTime='161959', self.symbol='BTCUSDT', self.open=28895.5, self.close=28824.0, self.high=28910.2, self.low=28808.0, self.vol=2831.872, self.amt=81702899.1921 
127.0.0.1 - - [21/Jun/2023 16:20:02] "POST / HTTP/1.1" 200 -
2023-06-21 16:20:07,581:INFO:amihud:main.py:172:handleKline:2219019: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5951  20230621   155500    155959  ...         0.0        0.0       0
5952  20230621   160000    160459  ...         0.0        0.0       0
5953  20230621   160500    160959  ...         0.0        0.0       0
5954  20230621   161000    161459  ...         0.0        0.0       0
5955  20230621   161500    161959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-06-21 16:20:07,621:INFO:amihud:main.py:175:handleKline:2219019: self.closeSec=1687335599, self.tradeDate='20230621', self.openTime='161500', self.closeTime='161959',self.symbol='BTCUSDT',self.open=28895.5, self.close=28824.0, self.high=28910.2, self.low=28808.0, self.vol=2831.872, self.amt=81702899.1921, ukdf['pct'].iloc[-1]=-0.002471 , ukdf['amount'].iloc[-1]=81702899.1921, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5955, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '13.926', 'enterprice': '26864.9', 'countrevence': '0', 'unrealprofit': '-27337.4800058283', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '28827.95328205', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1
127.0.0.1 - - [21/Jun/2023 16:25:00] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=373746.4768026, self.flagDict['side']='sell', self.tradeCount=2, self.count=11009
self.closeSec=1687335899, self.tradeDate='20230621', self.openTime='162000', self.closeTime='162459', self.symbol='BTCUSDT', self.open=28824.0, self.close=28846.9, self.high=28858.8, self.low=28809.0, self.vol=1335.891, self.amt=38523049.687 
2023-06-21 16:25:00,768:INFO:amihud:main.py:172:handleKline:2219019: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5952  20230621   160000    160459  ...         0.0        0.0       0
5953  20230621   160500    160959  ...         0.0        0.0       0
5954  20230621   161000    161459  ...         0.0        0.0       0
5955  20230621   161500    161959  ...         0.0        0.0       0
5956  20230621   162000    162459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-06-21 16:25:00,769:INFO:amihud:main.py:175:handleKline:2219019: self.closeSec=1687335899, self.tradeDate='20230621', self.openTime='162000', self.closeTime='162459',self.symbol='BTCUSDT',self.open=28824.0, self.close=28846.9, self.high=28858.8, self.low=28809.0, self.vol=1335.891, self.amt=38523049.687, ukdf['pct'].iloc[-1]=0.000794 , ukdf['amount'].iloc[-1]=38523049.687, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5956, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '13.926', 'enterprice': '26864.9', 'countrevence': '0', 'unrealprofit': '-27624.82528956216', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '28848.58700916', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1


## /root/FIL/strategy/factorcheck/log.txt ----- -----


self.closeSec=1687335599, self.tradeDate='20230621', self.openTime='161500', self.closeTime='161959', self.symbol='BTCUSDT', self.open=28895.5, self.close=28824.0, self.high=28910.2, self.low=28808.0 
127.0.0.1 - - [21/Jun/2023 16:20:01] "POST / HTTP/1.1" 200 -
2023-06-21 16:20:04,911:INFO:factorcheck2:main.py:126:handleKline:2218005: self.closeSec=1687335599, self.tradeDate='20230621', self.openTime='161500', self.closeTime='161959',self.symbol='BTCUSDT',self.open=28895.5, self.close=28824.0, self.high=28910.2, self.low=28808.0   
2023-06-21 16:20:06,411:INFO:factorcheck2:main.py:127:handleKline:2218005: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1631  20230621   155500    155959  1687334399  ...  28850.3 -0.000294   1631    5
1632  20230621   160000    160459  1687334699  ...  28840.0 -0.000534   1632    0
1633  20230621   160500    160959  1687334999  ...  28840.0 -0.000156   1633    1
1634  20230621   161000    161459  1687335299  ...  28840.3  0.001907   1634    2
1635  20230621   161500    161959  1687335599  ...  28808.0 -0.002471   1635    3

[5 rows x 11 columns]
2023-06-21 16:20:06,420:INFO:factorcheck2:main.py:128:handleKline:2218005: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=213, self.factor=0.19771058288181692, self.count=11011 

self.closeSec=1687335899, self.tradeDate='20230621', self.openTime='162000', self.closeTime='162459', self.symbol='BTCUSDT', self.open=28824.0, self.close=28846.9, self.high=28858.8, self.low=28809.0 
127.0.0.1 - - [21/Jun/2023 16:25:00] "POST / HTTP/1.1" 200 -
2023-06-21 16:25:00,706:INFO:factorcheck2:main.py:126:handleKline:2218005: self.closeSec=1687335899, self.tradeDate='20230621', self.openTime='162000', self.closeTime='162459',self.symbol='BTCUSDT',self.open=28824.0, self.close=28846.9, self.high=28858.8, self.low=28809.0   
2023-06-21 16:25:00,747:INFO:factorcheck2:main.py:127:handleKline:2218005: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1632  20230621   160000    160459  1687334699  ...  28840.0 -0.000534   1632    0
1633  20230621   160500    160959  1687334999  ...  28840.0 -0.000156   1633    1
1634  20230621   161000    161459  1687335299  ...  28840.3  0.001907   1634    2
1635  20230621   161500    161959  1687335599  ...  28808.0 -0.002471   1635    3
1636  20230621   162000    162459  1687335899  ...  28809.0  0.000794   1636    4

[5 rows x 11 columns]
2023-06-21 16:25:00,748:INFO:factorcheck2:main.py:128:handleKline:2218005: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}


## /root/FIL/strategy/logic/log.txt ----- -----

2023-06-21 16:00:17,681:DEBUG:logic:main.py:463:getModel:2218526: df_s.iloc[-5:,:] :
          date closeTime     open  ...    alpha58   alpha67   alpha72
5786  20230621    132959  28775.3  ...  57.083333  0.724858  0.154427
5787  20230621    135959  28843.6  ...  57.083333  0.734931  0.147312
5788  20230621    142959  28969.5  ...  56.666667  0.703699  0.144741
5789  20230621    145959  28820.0  ...  57.083333  0.705999  0.141606
5790  20230621    152959  28846.9  ...  57.083333  0.708028  0.138037

[5 rows x 33 columns]
0.551660516605166
acc is : 0.551660516605166
2023-06-21 16:00:17,773:INFO:logic:main.py:468:getModel:2218526: df_pred.iloc[-5:,:] :
     pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
537     1  0.494791  0.505209       1  ...  1.082010   1.0    0.0  1.095218
538     0  0.519295  0.480705       0  ...  1.076419   1.0    0.0  1.089558
539     1  0.465569  0.534431       1  ...  1.077427   1.0    0.0  1.090579
540     1  0.492351  0.507649       1  ...  1.078312   1.0    0.0  1.091475
541     1  0.493744  0.506256       0  ...  1.077931   1.0    0.0  1.091089

[5 rows x 10 columns]
2023-06-21 16:00:17,800:INFO:logic:main.py:478:getModel:2218526: df_panel.iloc[-5:,:] :
    pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
45     1  0.494827  0.505173       1  ...  1.082010   1.0    0.0  1.093985
46     0  0.519492  0.480508       0  ...  1.076419   1.0    0.0  1.089463
47     1  0.465875  0.534125       1  ...  1.077427   1.0    0.0  1.089874
48     1  0.492521  0.507479       1  ...  1.078312   1.0    0.0  1.091178
49     1  0.493744  0.506256       0  ...  1.077931   1.0    0.0  1.091089

[5 rows x 10 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '26.893', 'enterprice': '27229', 'countrevence': '0', 'unrealprofit': '43913.5797', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '28861.9', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}


## /root/FIL/strategy/modifiedmom/log.txt ----- -----

527  20230621   155000    155959  1687334399  28897.1  28860.4 -0.001270
2023-06-21 16:00:02,056:INFO:modifiedmom:main.py:146:handleKline:2218259: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True}

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=5504 

self.closeSec=1687334999, self.tradeDate='20230621', self.openTime='160000', self.closeTime='160959', self.symbol='BTCUSDT', self.open='28860.4', self.close='28840.4'
2023-06-21 16:10:01,133:INFO:modifiedmom:main.py:144:handleKline:2218259: self.closeSec=1687334999, self.tradeDate='20230621', self.openTime='160000', self.closeTime='160959',self.symbol='BTCUSDT',self.open='28860.4', self.close='28840.4'
127.0.0.1 - - [21/Jun/2023 16:10:01] "POST / HTTP/1.1" 200 -
2023-06-21 16:10:01,154:INFO:modifiedmom:main.py:145:handleKline:2218259: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
524  20230621   152000    152959  1687332599  28828.6  28870.6  0.001547
525  20230621   153000    153959  1687333199  28870.6  28880.1  0.000329
526  20230621   154000    154959  1687333799  28880.1  28897.1  0.000589
527  20230621   155000    155959  1687334399  28897.1  28860.4 -0.001270
528  20230621   160000    160959  1687334999  28860.4  28840.4 -0.000693
2023-06-21 16:10:01,154:INFO:modifiedmom:main.py:146:handleKline:2218259: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True}

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=5505 

self.closeSec=1687335599, self.tradeDate='20230621', self.openTime='161000', self.closeTime='161959', self.symbol='BTCUSDT', self.open='28840.3', self.close='28824'
127.0.0.1 - - [21/Jun/2023 16:20:04] "POST / HTTP/1.1" 200 -
2023-06-21 16:20:07,190:INFO:modifiedmom:main.py:144:handleKline:2218259: self.closeSec=1687335599, self.tradeDate='20230621', self.openTime='161000', self.closeTime='161959',self.symbol='BTCUSDT',self.open='28840.3', self.close='28824'
2023-06-21 16:20:07,970:INFO:modifiedmom:main.py:145:handleKline:2218259: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
525  20230621   153000    153959  1687333199  28870.6  28880.1  0.000329
526  20230621   154000    154959  1687333799  28880.1  28897.1  0.000589
527  20230621   155000    155959  1687334399  28897.1  28860.4 -0.001270
528  20230621   160000    160959  1687334999  28860.4  28840.4 -0.000693
529  20230621   161000    161959  1687335599  28840.3    28824 -0.000569
2023-06-21 16:20:07,971:INFO:modifiedmom:main.py:146:handleKline:2218259: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True}


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

17519  20230621   155000    155959  1687334399  28897.1  28860.4
2023-06-21 16:00:02,079:INFO:pyemd2:main.py:127:handleKline:2217508: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=5507 

self.closeSec=1687334999, self.tradeDate='20230621', self.openTime='160000', self.closeTime='160959', self.symbol='BTCUSDT', self.open='28860.4', self.close='28840.4'
127.0.0.1 - - [21/Jun/2023 16:10:01] "POST / HTTP/1.1" 200 -
2023-06-21 16:10:01,141:INFO:pyemd2:main.py:125:handleKline:2217508: self.closeSec=1687334999, self.tradeDate='20230621', self.openTime='160000', self.closeTime='160959',self.symbol='BTCUSDT',self.open='28860.4', self.close='28840.4'
2023-06-21 16:10:01,161:INFO:pyemd2:main.py:126:handleKline:2217508: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17516  20230621   152000    152959  1687332599  28828.6  28870.6
17517  20230621   153000    153959  1687333199  28870.6  28880.1
17518  20230621   154000    154959  1687333799  28880.1  28897.1
17519  20230621   155000    155959  1687334399  28897.1  28860.4
17520  20230621   160000    160959  1687334999  28860.4  28840.4
2023-06-21 16:10:01,161:INFO:pyemd2:main.py:127:handleKline:2217508: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=5508 

self.closeSec=1687335599, self.tradeDate='20230621', self.openTime='161000', self.closeTime='161959', self.symbol='BTCUSDT', self.open='28840.3', self.close='28824'
127.0.0.1 - - [21/Jun/2023 16:20:04] "POST / HTTP/1.1" 200 -
2023-06-21 16:20:09,132:INFO:pyemd2:main.py:125:handleKline:2217508: self.closeSec=1687335599, self.tradeDate='20230621', self.openTime='161000', self.closeTime='161959',self.symbol='BTCUSDT',self.open='28840.3', self.close='28824'
2023-06-21 16:20:09,270:INFO:pyemd2:main.py:126:handleKline:2217508: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17517  20230621   153000    153959  1687333199  28870.6  28880.1
17518  20230621   154000    154959  1687333799  28880.1  28897.1
17519  20230621   155000    155959  1687334399  28897.1  28860.4
17520  20230621   160000    160959  1687334999  28860.4  28840.4
17521  20230621   161000    161959  1687335599  28840.3    28824
2023-06-21 16:20:09,270:INFO:pyemd2:main.py:127:handleKline:2217508: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}


## /root/FIL/strategy/similarity/log.txt ----- -----

12191  20230621   155000    155959  1687334399  28897.1  28860.4
2023-06-21 16:00:02,071:INFO:testStrategy:main.py:103:handleKline:2217133: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': True, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=5507 

self.closeSec=1687334999, self.tradeDate='20230621', self.openTime='160000', self.closeTime='160959', self.symbol='BTCUSDT', self.open='28860.4', self.close='28840.4'
2023-06-21 16:10:01,117:INFO:testStrategy:main.py:101:handleKline:2217133: self.closeSec=1687334999, self.tradeDate='20230621', self.openTime='160000', self.closeTime='160959',self.symbol='BTCUSDT',self.open='28860.4', self.close='28840.4'
127.0.0.1 - - [21/Jun/2023 16:10:01] "POST / HTTP/1.1" 200 -
2023-06-21 16:10:01,152:INFO:testStrategy:main.py:102:handleKline:2217133: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12188  20230621   152000    152959  1687332599  28828.6  28870.6
12189  20230621   153000    153959  1687333199  28870.6  28880.1
12190  20230621   154000    154959  1687333799  28880.1  28897.1
12191  20230621   155000    155959  1687334399  28897.1  28860.4
12192  20230621   160000    160959  1687334999  28860.4  28840.4
2023-06-21 16:10:01,152:INFO:testStrategy:main.py:103:handleKline:2217133: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': True, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=5508 

self.closeSec=1687335599, self.tradeDate='20230621', self.openTime='161000', self.closeTime='161959', self.symbol='BTCUSDT', self.open='28840.3', self.close='28824'
127.0.0.1 - - [21/Jun/2023 16:20:04] "POST / HTTP/1.1" 200 -
2023-06-21 16:20:08,721:INFO:testStrategy:main.py:101:handleKline:2217133: self.closeSec=1687335599, self.tradeDate='20230621', self.openTime='161000', self.closeTime='161959',self.symbol='BTCUSDT',self.open='28840.3', self.close='28824'
2023-06-21 16:20:09,001:INFO:testStrategy:main.py:102:handleKline:2217133: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12189  20230621   153000    153959  1687333199  28870.6  28880.1
12190  20230621   154000    154959  1687333799  28880.1  28897.1
12191  20230621   155000    155959  1687334399  28897.1  28860.4
12192  20230621   160000    160959  1687334999  28860.4  28840.4
12193  20230621   161000    161959  1687335599  28840.3    28824
2023-06-21 16:20:09,004:INFO:testStrategy:main.py:103:handleKline:2217133: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': True, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}


## /root/FIL/strategy/sr_min/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=1, self.total=996015.990996, self.flagDict['side']='buy', self.tradeCount=1, self.count=11008
self.closeSec=1687335599, self.tradeDate='20230621', self.openTime='161500', self.closeTime='161959', self.symbol='BTCUSDT', self.open=28895.5, self.close=28824.0, self.high=28910.2, self.low=28808.0, self.vol=2831.872, self.amt=81702899.1921 
127.0.0.1 - - [21/Jun/2023 16:20:01] "POST / HTTP/1.1" 200 -
2023-06-21 16:20:07,561:INFO:sr_min:main.py:172:handleKline:2219263: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5951  20230621   155500    155959  ...         0.0        0.0       0
5952  20230621   160000    160459  ...         0.0        0.0       0
5953  20230621   160500    160959  ...         0.0        0.0       0
5954  20230621   161000    161459  ...         0.0        0.0       0
5955  20230621   161500    161959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-06-21 16:20:07,591:INFO:sr_min:main.py:175:handleKline:2219263: self.closeSec=1687335599, self.tradeDate='20230621', self.openTime='161500', self.closeTime='161959',self.symbol='BTCUSDT',self.open=28895.5, self.close=28824.0, self.high=28910.2, self.low=28808.0, self.vol=2831.872, self.amt=81702899.1921, ukdf['pct'].iloc[-1]=-0.002471 , ukdf['amount'].iloc[-1]=81702899.1921, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5955, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '37.141', 'enterprice': '26844', 'countrevence': '0', 'unrealprofit': '73686.00884861905', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '28827.95328205', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=1
127.0.0.1 - - [21/Jun/2023 16:25:00] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=1, self.total=996015.990996, self.flagDict['side']='buy', self.tradeCount=1, self.count=11009
self.closeSec=1687335899, self.tradeDate='20230621', self.openTime='162000', self.closeTime='162459', self.symbol='BTCUSDT', self.open=28824.0, self.close=28846.9, self.high=28858.8, self.low=28809.0, self.vol=1335.891, self.amt=38523049.687 
2023-06-21 16:25:00,769:INFO:sr_min:main.py:172:handleKline:2219263: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5952  20230621   160000    160459  ...         0.0        0.0       0
5953  20230621   160500    160959  ...         0.0        0.0       0
5954  20230621   161000    161459  ...         0.0        0.0       0
5955  20230621   161500    161959  ...         0.0        0.0       0
5956  20230621   162000    162459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-06-21 16:25:00,770:INFO:sr_min:main.py:175:handleKline:2219263: self.closeSec=1687335899, self.tradeDate='20230621', self.openTime='162000', self.closeTime='162459',self.symbol='BTCUSDT',self.open=28824.0, self.close=28846.9, self.high=28858.8, self.low=28809.0, self.vol=1335.891, self.amt=38523049.687, ukdf['pct'].iloc[-1]=0.000794 , ukdf['amount'].iloc[-1]=38523049.687, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5956, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '37.141', 'enterprice': '26844', 'countrevence': '0', 'unrealprofit': '74452.36610721156', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '28848.58700916', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=1


## /root/FIL/strategy/s_rsrs/log.txt ----- -----

721  20230621   040000    075959  1687305599  ...    721  1.222639  4.235218     1.0
722  20230621   080000    115959  1687319999  ...    722  1.430877  4.638883     1.0

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '53.344', 'enterprice': '27977.7', 'countrevence': '0', 'unrealprofit': '38781.088', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '28704.7', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=1, self.sign=1
--handleKline--:  version='2.0.0', self.name='s_rsrs', self.symbol='BTCUSDT', interval='4h', intervalSec=14400, wid=25, thd=0.6, self.sign=1, self.total=1490949.9863712, self.flagDict['side']='buy', self.tradeCount=7, self.count=229
self.closeSec=1687334399, self.tradeDate='20230621', self.openTime='120000', self.closeTime='155959', self.symbol='BTCUSDT', self.open=28704.6, self.close=28860.4, self.high=29000.0, self.low=28668.5, self.vol=75606.358, self.amt=2179678302.0635 
127.0.0.1 - - [21/Jun/2023 16:00:01] "POST / HTTP/1.1" 200 -
2023-06-21 16:00:01,635:INFO:s_rsrs:main.py:141:handleKline:2218689: self.closeSec=1687334399, self.tradeDate='20230621', self.openTime='120000', self.closeTime='155959',self.symbol='BTCUSDT',self.open=28704.6, self.close=28860.4, self.high=29000.0, self.low=28668.5, self.vol=75606.358, self.amt=2179678302.0635 
2023-06-21 16:00:01,661:INFO:s_rsrs:main.py:142:handleKline:2218689: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime  ...         vol           amt       pct
719  20230620   200000    235959  ...  114387.910  3.072620e+09  0.005912
720  20230621   000000    035959  ...  340070.821  9.391812e+09  0.033958
721  20230621   040000    075959  ...  124303.400  3.498796e+09  0.011357
722  20230621   080000    115959  ...  169807.166  4.868144e+09  0.014634
723  20230621   120000    155959  ...   75606.358  2.179678e+09  0.005428

[5 rows x 11 columns]
2023-06-21 16:00:02,934:INFO:s_rsrs:main.py:151:handleKline:2218689: df_s.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec  ...  index      beta    zscore  signal
719  20230620   200000    235959  1687276799  ...    719  0.227191 -1.342353    -1.0
720  20230621   000000    035959  1687291199  ...    720  0.576821  0.801283     1.0
721  20230621   040000    075959  1687305599  ...    721  1.222639  4.235218     1.0
722  20230621   080000    115959  1687319999  ...    722  1.430877  4.638883     1.0
723  20230621   120000    155959  1687334399  ...    723  1.191168  3.252635     1.0

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '53.344', 'enterprice': '27977.7', 'countrevence': '0', 'unrealprofit': '47198.7712', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '28862.5', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=1, self.sign=1


