# 20230516 16:26:01

## /root/FIL/strategy/amihud/log.txt ----- -----

127.0.0.1 - - [16/May/2023 16:20:00] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=373746.4768026, self.flagDict['side']='sell', self.tradeCount=2, self.count=640
self.closeSec=1684225199, self.tradeDate='20230516', self.openTime='161500', self.closeTime='161959', self.symbol='BTCUSDT', self.open=27218.0, self.close=27235.0, self.high=27239.9, self.low=27200.5, self.vol=1543.598, self.amt=42013354.0086 
2023-05-16 16:20:00,527:INFO:amihud:main.py:172:handleKline:2219019: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5951  20230516   155500    155959  ...    0.475096   0.249534       0
5952  20230516   160000    160459  ...    0.474968   0.249660       0
5953  20230516   160500    160959  ...    0.474840   0.249785       0
5954  20230516   161000    161459  ...    0.474711   0.249910       0
5955  20230516   161500    161959  ...    0.474581   0.250035       0

[5 rows x 18 columns]
2023-05-16 16:20:00,531:INFO:amihud:main.py:175:handleKline:2219019: self.closeSec=1684225199, self.tradeDate='20230516', self.openTime='161500', self.closeTime='161959',self.symbol='BTCUSDT',self.open=27218.0, self.close=27235.0, self.high=27239.9, self.low=27200.5, self.vol=1543.598, self.amt=42013354.0086, ukdf['pct'].iloc[-1]=0.000625 , ukdf['amount'].iloc[-1]=42013354.0086, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5955, value=0.0, value_mean=0.47458095530885736, signal=0, value_std=0.2500353924877572 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '13.926', 'enterprice': '26864.9', 'countrevence': '0', 'unrealprofit': '-5154.0126', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '27235', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1
--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=373746.4768026, self.flagDict['side']='sell', self.tradeCount=2, self.count=641
self.closeSec=1684225499, self.tradeDate='20230516', self.openTime='162000', self.closeTime='162459', self.symbol='BTCUSDT', self.open=27234.9, self.close=27246.8, self.high=27274.2, self.low=27230.1, self.vol=2767.475, self.amt=75436954.2238 
127.0.0.1 - - [16/May/2023 16:25:00] "POST / HTTP/1.1" 200 -
2023-05-16 16:25:00,424:INFO:amihud:main.py:172:handleKline:2219019: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5952  20230516   160000    160459  ...    0.474968   0.249660       0
5953  20230516   160500    160959  ...    0.474840   0.249785       0
5954  20230516   161000    161459  ...    0.474711   0.249910       0
5955  20230516   161500    161959  ...    0.474581   0.250035       0
5956  20230516   162000    162459  ...    0.474453   0.250160       0

[5 rows x 18 columns]
2023-05-16 16:25:00,425:INFO:amihud:main.py:175:handleKline:2219019: self.closeSec=1684225499, self.tradeDate='20230516', self.openTime='162000', self.closeTime='162459',self.symbol='BTCUSDT',self.open=27234.9, self.close=27246.8, self.high=27274.2, self.low=27230.1, self.vol=2767.475, self.amt=75436954.2238, ukdf['pct'].iloc[-1]=0.000433 , ukdf['amount'].iloc[-1]=75436954.2238, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5956, value=0.0, value_mean=0.4744534124302984, signal=0, value_std=0.2501603050095751 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '13.926', 'enterprice': '26864.9', 'countrevence': '0', 'unrealprofit': '-5349.29029206264', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '27249.02252564', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1


## /root/FIL/strategy/factorcheck/log.txt ----- -----

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=106, self.factor=0.4457473752233407, self.count=642 

self.closeSec=1684225199, self.tradeDate='20230516', self.openTime='161500', self.closeTime='161959', self.symbol='BTCUSDT', self.open=27218.0, self.close=27235.0, self.high=27239.9, self.low=27200.5 
2023-05-16 16:20:00,416:INFO:factorcheck2:main.py:126:handleKline:2218005: self.closeSec=1684225199, self.tradeDate='20230516', self.openTime='161500', self.closeTime='161959',self.symbol='BTCUSDT',self.open=27218.0, self.close=27235.0, self.high=27239.9, self.low=27200.5   
2023-05-16 16:20:00,487:INFO:factorcheck2:main.py:127:handleKline:2218005: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1630  20230516   155500    155959  1684223999  ...  27206.0  0.000661   1630    4
1631  20230516   160000    160459  1684224299  ...  27198.7 -0.001468   1631    5
1632  20230516   160500    160959  1684224599  ...  27152.4  0.000232   1632    0
1633  20230516   161000    161459  1684224899  ...  27204.7  0.000408   1633    1
1634  20230516   161500    161959  1684225199  ...  27200.5  0.000625   1634    2

[5 rows x 11 columns]
2023-05-16 16:20:00,499:INFO:factorcheck2:main.py:128:handleKline:2218005: self.flagDict={'side': '', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=106, self.factor=0.4457473752233407, self.count=643 

self.closeSec=1684225499, self.tradeDate='20230516', self.openTime='162000', self.closeTime='162459', self.symbol='BTCUSDT', self.open=27234.9, self.close=27246.8, self.high=27274.2, self.low=27230.1 
2023-05-16 16:25:00,354:INFO:factorcheck2:main.py:126:handleKline:2218005: self.closeSec=1684225499, self.tradeDate='20230516', self.openTime='162000', self.closeTime='162459',self.symbol='BTCUSDT',self.open=27234.9, self.close=27246.8, self.high=27274.2, self.low=27230.1   
127.0.0.1 - - [16/May/2023 16:25:00] "POST / HTTP/1.1" 200 -
2023-05-16 16:25:00,382:INFO:factorcheck2:main.py:127:handleKline:2218005: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1631  20230516   160000    160459  1684224299  ...  27198.7 -0.001468   1631    5
1632  20230516   160500    160959  1684224599  ...  27152.4  0.000232   1632    0
1633  20230516   161000    161459  1684224899  ...  27204.7  0.000408   1633    1
1634  20230516   161500    161959  1684225199  ...  27200.5  0.000625   1634    2
1635  20230516   162000    162459  1684225499  ...  27230.1  0.000433   1635    3

[5 rows x 11 columns]
2023-05-16 16:25:00,382:INFO:factorcheck2:main.py:128:handleKline:2218005: self.flagDict={'side': '', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}


## /root/FIL/strategy/logic/log.txt ----- -----

2023-05-16 16:00:17,050:DEBUG:logic:main.py:463:getModel:2218526: df_s.iloc[-5:,:] :
          date closeTime     open  ...    alpha58   alpha67   alpha72
5786  20230516    132959  27100.3  ...  50.833333  0.493301  0.563810
5787  20230516    135959  27105.9  ...  50.416667  0.481809  0.575114
5788  20230516    142959  27050.1  ...  50.416667  0.481788  0.585673
5789  20230516    145959  27050.0  ...  50.416667  0.482058  0.595430
5790  20230516    152959  27051.2  ...  50.416667  0.508883  0.594496

[5 rows x 33 columns]
0.5313653136531366
acc is : 0.5313653136531366
2023-05-16 16:00:17,118:INFO:logic:main.py:468:getModel:2218526: df_pred.iloc[-5:,:] :
     pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
537     1  0.497141  0.502859       0  ...  0.977466  -1.0    0.0  0.935226
538     1  0.481414  0.518586       1  ...  0.977470  -1.0    0.0  0.935222
539     1  0.485952  0.514048       1  ...  0.977426  -1.0    0.0  0.935264
540     1  0.486185  0.513815       1  ...  0.972975  -1.0    0.0  0.939523
541     0  0.521632  0.478368       1  ...  0.970604  -1.0    0.0  0.941812

[5 rows x 10 columns]
2023-05-16 16:00:17,129:INFO:logic:main.py:478:getModel:2218526: df_panel.iloc[-5:,:] :
    pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
45     1  0.497907  0.502093       0  ...  0.977466  -1.0    0.0  0.940454
46     1  0.481857  0.518143       1  ...  0.977470  -1.0    0.0  0.938441
47     1  0.486169  0.513831       1  ...  0.977426  -1.0    0.0  0.938431
48     1  0.486385  0.513615       1  ...  0.972975  -1.0    0.0  0.941030
49     0  0.521632  0.478368       1  ...  0.970604  -1.0    0.0  0.941812

[5 rows x 10 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '28.151', 'enterprice': '26995.7', 'countrevence': '0', 'unrealprofit': '-6542.2924', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '27228.1', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}


## /root/FIL/strategy/modifiedmom/log.txt ----- -----

527  20230516   155000    155959  1684223999  27206.7  27240.6  0.001242
2023-05-16 16:00:00,424:INFO:modifiedmom:main.py:146:handleKline:2218259: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True}

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=320 

self.closeSec=1684224599, self.tradeDate='20230516', self.openTime='160000', self.closeTime='160959', self.symbol='BTCUSDT', self.open='27240.6', self.close='27206.9'
2023-05-16 16:10:00,377:INFO:modifiedmom:main.py:144:handleKline:2218259: self.closeSec=1684224599, self.tradeDate='20230516', self.openTime='160000', self.closeTime='160959',self.symbol='BTCUSDT',self.open='27240.6', self.close='27206.9'
127.0.0.1 - - [16/May/2023 16:10:00] "POST / HTTP/1.1" 200 -
2023-05-16 16:10:00,401:INFO:modifiedmom:main.py:145:handleKline:2218259: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
524  20230516   152000    152959  1684222199    27200  27174.4 -0.000945
525  20230516   153000    153959  1684222799  27174.4  27192.3  0.000659
526  20230516   154000    154959  1684223399  27192.3  27206.8  0.000533
527  20230516   155000    155959  1684223999  27206.7  27240.6  0.001242
528  20230516   160000    160959  1684224599  27240.6  27206.9 -0.001237
2023-05-16 16:10:00,407:INFO:modifiedmom:main.py:146:handleKline:2218259: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True}
127.0.0.1 - - [16/May/2023 16:20:00] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=321 

self.closeSec=1684225199, self.tradeDate='20230516', self.openTime='161000', self.closeTime='161959', self.symbol='BTCUSDT', self.open='27206.9', self.close='27235'
2023-05-16 16:20:00,416:INFO:modifiedmom:main.py:144:handleKline:2218259: self.closeSec=1684225199, self.tradeDate='20230516', self.openTime='161000', self.closeTime='161959',self.symbol='BTCUSDT',self.open='27206.9', self.close='27235'
2023-05-16 16:20:00,469:INFO:modifiedmom:main.py:145:handleKline:2218259: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
525  20230516   153000    153959  1684222799  27174.4  27192.3  0.000659
526  20230516   154000    154959  1684223399  27192.3  27206.8  0.000533
527  20230516   155000    155959  1684223999  27206.7  27240.6  0.001242
528  20230516   160000    160959  1684224599  27240.6  27206.9 -0.001237
529  20230516   161000    161959  1684225199  27206.9    27235  0.001033
2023-05-16 16:20:00,469:INFO:modifiedmom:main.py:146:handleKline:2218259: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True}


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

17519  20230516   155000    155959  1684223999  27206.7  27240.6
2023-05-16 16:00:00,450:INFO:pyemd2:main.py:127:handleKline:2217508: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=323 

self.closeSec=1684224599, self.tradeDate='20230516', self.openTime='160000', self.closeTime='160959', self.symbol='BTCUSDT', self.open='27240.6', self.close='27206.9'
2023-05-16 16:10:00,368:INFO:pyemd2:main.py:125:handleKline:2217508: self.closeSec=1684224599, self.tradeDate='20230516', self.openTime='160000', self.closeTime='160959',self.symbol='BTCUSDT',self.open='27240.6', self.close='27206.9'
127.0.0.1 - - [16/May/2023 16:10:00] "POST / HTTP/1.1" 200 -
2023-05-16 16:10:00,423:INFO:pyemd2:main.py:126:handleKline:2217508: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17516  20230516   152000    152959  1684222199    27200  27174.4
17517  20230516   153000    153959  1684222799  27174.4  27192.3
17518  20230516   154000    154959  1684223399  27192.3  27206.8
17519  20230516   155000    155959  1684223999  27206.7  27240.6
17520  20230516   160000    160959  1684224599  27240.6  27206.9
2023-05-16 16:10:00,427:INFO:pyemd2:main.py:127:handleKline:2217508: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}
127.0.0.1 - - [16/May/2023 16:20:00] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=324 

self.closeSec=1684225199, self.tradeDate='20230516', self.openTime='161000', self.closeTime='161959', self.symbol='BTCUSDT', self.open='27206.9', self.close='27235'
2023-05-16 16:20:00,444:INFO:pyemd2:main.py:125:handleKline:2217508: self.closeSec=1684225199, self.tradeDate='20230516', self.openTime='161000', self.closeTime='161959',self.symbol='BTCUSDT',self.open='27206.9', self.close='27235'
2023-05-16 16:20:00,496:INFO:pyemd2:main.py:126:handleKline:2217508: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17517  20230516   153000    153959  1684222799  27174.4  27192.3
17518  20230516   154000    154959  1684223399  27192.3  27206.8
17519  20230516   155000    155959  1684223999  27206.7  27240.6
17520  20230516   160000    160959  1684224599  27240.6  27206.9
17521  20230516   161000    161959  1684225199  27206.9    27235
2023-05-16 16:20:00,496:INFO:pyemd2:main.py:127:handleKline:2217508: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}


## /root/FIL/strategy/similarity/log.txt ----- -----

12191  20230516   155000    155959  1684223999  27206.7  27240.6
2023-05-16 16:00:00,423:INFO:testStrategy:main.py:103:handleKline:2217133: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': True, 'isCloseBuy': False, 'isCloseSell': False, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=323 

self.closeSec=1684224599, self.tradeDate='20230516', self.openTime='160000', self.closeTime='160959', self.symbol='BTCUSDT', self.open='27240.6', self.close='27206.9'
2023-05-16 16:10:00,354:INFO:testStrategy:main.py:101:handleKline:2217133: self.closeSec=1684224599, self.tradeDate='20230516', self.openTime='160000', self.closeTime='160959',self.symbol='BTCUSDT',self.open='27240.6', self.close='27206.9'
127.0.0.1 - - [16/May/2023 16:10:00] "POST / HTTP/1.1" 200 -
2023-05-16 16:10:00,420:INFO:testStrategy:main.py:102:handleKline:2217133: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12188  20230516   152000    152959  1684222199    27200  27174.4
12189  20230516   153000    153959  1684222799  27174.4  27192.3
12190  20230516   154000    154959  1684223399  27192.3  27206.8
12191  20230516   155000    155959  1684223999  27206.7  27240.6
12192  20230516   160000    160959  1684224599  27240.6  27206.9
2023-05-16 16:10:00,420:INFO:testStrategy:main.py:103:handleKline:2217133: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': True, 'isCloseBuy': False, 'isCloseSell': False, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}
127.0.0.1 - - [16/May/2023 16:20:00] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=324 

self.closeSec=1684225199, self.tradeDate='20230516', self.openTime='161000', self.closeTime='161959', self.symbol='BTCUSDT', self.open='27206.9', self.close='27235'
2023-05-16 16:20:00,428:INFO:testStrategy:main.py:101:handleKline:2217133: self.closeSec=1684225199, self.tradeDate='20230516', self.openTime='161000', self.closeTime='161959',self.symbol='BTCUSDT',self.open='27206.9', self.close='27235'
2023-05-16 16:20:00,489:INFO:testStrategy:main.py:102:handleKline:2217133: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12189  20230516   153000    153959  1684222799  27174.4  27192.3
12190  20230516   154000    154959  1684223399  27192.3  27206.8
12191  20230516   155000    155959  1684223999  27206.7  27240.6
12192  20230516   160000    160959  1684224599  27240.6  27206.9
12193  20230516   161000    161959  1684225199  27206.9    27235
2023-05-16 16:20:00,489:INFO:testStrategy:main.py:103:handleKline:2217133: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': True, 'isCloseBuy': False, 'isCloseSell': False, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}


## /root/FIL/strategy/sr_min/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=1, self.total=996015.990996, self.flagDict['side']='buy', self.tradeCount=1, self.count=640
self.closeSec=1684225199, self.tradeDate='20230516', self.openTime='161500', self.closeTime='161959', self.symbol='BTCUSDT', self.open=27218.0, self.close=27235.0, self.high=27239.9, self.low=27200.5, self.vol=1543.598, self.amt=42013354.0086 
127.0.0.1 - - [16/May/2023 16:20:00] "POST / HTTP/1.1" 200 -
2023-05-16 16:20:00,530:INFO:sr_min:main.py:172:handleKline:2219263: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5951  20230516   155500    155959  ...    0.391175   0.256619       0
5952  20230516   160000    160459  ...    0.390914   0.256762       0
5953  20230516   160500    160959  ...    0.390654   0.256905       0
5954  20230516   161000    161459  ...    0.390396   0.257048       0
5955  20230516   161500    161959  ...    0.390139   0.257192       0

[5 rows x 18 columns]
2023-05-16 16:20:00,532:INFO:sr_min:main.py:175:handleKline:2219263: self.closeSec=1684225199, self.tradeDate='20230516', self.openTime='161500', self.closeTime='161959',self.symbol='BTCUSDT',self.open=27218.0, self.close=27235.0, self.high=27239.9, self.low=27200.5, self.vol=1543.598, self.amt=42013354.0086, ukdf['pct'].iloc[-1]=0.000625 , ukdf['amount'].iloc[-1]=42013354.0086, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5955, value=0.0, value_mean=0.39013871907060554, signal=0, value_std=0.2571915423257147 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '37.141', 'enterprice': '26844', 'countrevence': '0', 'unrealprofit': '14522.131', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '27235', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=1
--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=1, self.total=996015.990996, self.flagDict['side']='buy', self.tradeCount=1, self.count=641
self.closeSec=1684225499, self.tradeDate='20230516', self.openTime='162000', self.closeTime='162459', self.symbol='BTCUSDT', self.open=27234.9, self.close=27246.8, self.high=27274.2, self.low=27230.1, self.vol=2767.475, self.amt=75436954.2238 
127.0.0.1 - - [16/May/2023 16:25:00] "POST / HTTP/1.1" 200 -
2023-05-16 16:25:00,415:INFO:sr_min:main.py:172:handleKline:2219263: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5952  20230516   160000    160459  ...    0.390914   0.256762       0
5953  20230516   160500    160959  ...    0.390654   0.256905       0
5954  20230516   161000    161459  ...    0.390396   0.257048       0
5955  20230516   161500    161959  ...    0.390139   0.257192       0
5956  20230516   162000    162459  ...    0.389883   0.257335       0

[5 rows x 18 columns]
2023-05-16 16:25:00,415:INFO:sr_min:main.py:175:handleKline:2219263: self.closeSec=1684225499, self.tradeDate='20230516', self.openTime='162000', self.closeTime='162459',self.symbol='BTCUSDT',self.open=27234.9, self.close=27246.8, self.high=27274.2, self.low=27230.1, self.vol=2767.475, self.amt=75436954.2238, ukdf['pct'].iloc[-1]=0.000433 , ukdf['amount'].iloc[-1]=75436954.2238, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5956, value=0.0, value_mean=0.3898825603674651, signal=0, value_std=0.2573350219137478 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '37.141', 'enterprice': '26844', 'countrevence': '0', 'unrealprofit': '15042.94162479524', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '27249.02252564', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=1


## /root/FIL/strategy/s_rsrs/log.txt ----- -----

721  20230516   040000    075959  1684195199  ...    721  0.467538 -0.050923     NaN
722  20230516   080000    115959  1684209599  ...    722  0.474729 -0.042116     NaN

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '52.436', 'enterprice': '26818.7', 'countrevence': '0', 'unrealprofit': '-15846.1592', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '27120.9', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-9223372036854775808, self.sign=-1
--handleKline--:  version='2.0.0', self.name='s_rsrs', self.symbol='BTCUSDT', interval='4h', intervalSec=14400, wid=25, thd=0.6, self.sign=-1, self.total=6897.9369698, self.flagDict['side']='', self.tradeCount=0, self.count=13
self.closeSec=1684223999, self.tradeDate='20230516', self.openTime='120000', self.closeTime='155959', self.symbol='BTCUSDT', self.open=27118.7, self.close=27240.6, self.high=27243.6, self.low=26971.0, self.vol=49329.282, self.amt=1337491386.28278 
2023-05-16 16:00:00,379:INFO:s_rsrs:main.py:141:handleKline:2218689: self.closeSec=1684223999, self.tradeDate='20230516', self.openTime='120000', self.closeTime='155959',self.symbol='BTCUSDT',self.open=27118.7, self.close=27240.6, self.high=27243.6, self.low=26971.0, self.vol=49329.282, self.amt=1337491386.28278 
127.0.0.1 - - [16/May/2023 16:00:00] "POST / HTTP/1.1" 200 -
2023-05-16 16:00:00,463:INFO:s_rsrs:main.py:142:handleKline:2218689: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime  ...        vol           amt       pct
719  20230515   200000    235959  ...  79836.823  2.184424e+09  0.002189
720  20230516   000000    035959  ...  97469.170  2.677565e+09  0.000990
721  20230516   040000    075959  ...  38932.072  1.061731e+09 -0.009398
722  20230516   080000    115959  ...  90185.098  2.439151e+09 -0.001245
723  20230516   120000    155959  ...  49329.282  1.337491e+09  0.004495

[5 rows x 11 columns]
2023-05-16 16:00:01,832:INFO:s_rsrs:main.py:151:handleKline:2218689: df_s.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec  ...  index      beta    zscore  signal
719  20230515   200000    235959  1684166399  ...    719  0.403817 -0.320462     NaN
720  20230516   000000    035959  1684180799  ...    720  0.441302 -0.161099     NaN
721  20230516   040000    075959  1684195199  ...    721  0.467538 -0.050923     NaN
722  20230516   080000    115959  1684209599  ...    722  0.474729 -0.042116     NaN
723  20230516   120000    155959  1684223999  ...    723  0.502828  0.089948     NaN

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '52.436', 'enterprice': '26818.7', 'countrevence': '0', 'unrealprofit': '-22117.5048', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '27240.5', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-9223372036854775808, self.sign=-1


