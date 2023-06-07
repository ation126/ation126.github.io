# 20230607 16:26:02

## /root/FIL/strategy/amihud/log.txt ----- -----

127.0.0.1 - - [07/Jun/2023 16:20:00] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=373746.4768026, self.flagDict['side']='sell', self.tradeCount=2, self.count=6976
self.closeSec=1686125999, self.tradeDate='20230607', self.openTime='161500', self.closeTime='161959', self.symbol='BTCUSDT', self.open=26771.3, self.close=26794.3, self.high=26796.5, self.low=26765.8, self.vol=628.159, self.amt=16824019.034 
2023-06-07 16:20:01,078:INFO:amihud:main.py:172:handleKline:2219019: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5951  20230607   155500    155959  ...         0.0        0.0       0
5952  20230607   160000    160459  ...         0.0        0.0       0
5953  20230607   160500    160959  ...         0.0        0.0       0
5954  20230607   161000    161459  ...         0.0        0.0       0
5955  20230607   161500    161959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-06-07 16:20:01,080:INFO:amihud:main.py:175:handleKline:2219019: self.closeSec=1686125999, self.tradeDate='20230607', self.openTime='161500', self.closeTime='161959',self.symbol='BTCUSDT',self.open=26771.3, self.close=26794.3, self.high=26796.5, self.low=26765.8, self.vol=628.159, self.amt=16824019.034, ukdf['pct'].iloc[-1]=0.000859 , ukdf['amount'].iloc[-1]=16824019.034, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5955, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '13.926', 'enterprice': '26864.9', 'countrevence': '0', 'unrealprofit': '965.12839568178', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '26795.59593597', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1
--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=373746.4768026, self.flagDict['side']='sell', self.tradeCount=2, self.count=6977
self.closeSec=1686126299, self.tradeDate='20230607', self.openTime='162000', self.closeTime='162459', self.symbol='BTCUSDT', self.open=26794.2, self.close=26810.0, self.high=26818.3, self.low=26794.2, self.vol=923.255, self.amt=24752369.6942 
127.0.0.1 - - [07/Jun/2023 16:25:01] "POST / HTTP/1.1" 200 -
2023-06-07 16:25:04,002:INFO:amihud:main.py:172:handleKline:2219019: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5952  20230607   160000    160459  ...         0.0        0.0       0
5953  20230607   160500    160959  ...         0.0        0.0       0
5954  20230607   161000    161459  ...         0.0        0.0       0
5955  20230607   161500    161959  ...         0.0        0.0       0
5956  20230607   162000    162459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-06-07 16:25:04,013:INFO:amihud:main.py:175:handleKline:2219019: self.closeSec=1686126299, self.tradeDate='20230607', self.openTime='162000', self.closeTime='162459',self.symbol='BTCUSDT',self.open=26794.2, self.close=26810.0, self.high=26818.3, self.low=26794.2, self.vol=923.255, self.amt=24752369.6942, ukdf['pct'].iloc[-1]=0.000586 , ukdf['amount'].iloc[-1]=24752369.6942, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5956, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '13.926', 'enterprice': '26864.9', 'countrevence': '0', 'unrealprofit': '757.1671104558', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '26810.5292467', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1


## /root/FIL/strategy/factorcheck/log.txt ----- -----

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=28, self.factor=0.38551567292728156, self.count=6978 

self.closeSec=1686125999, self.tradeDate='20230607', self.openTime='161500', self.closeTime='161959', self.symbol='BTCUSDT', self.open=26771.3, self.close=26794.3, self.high=26796.5, self.low=26765.8 
2023-06-07 16:20:00,947:INFO:factorcheck2:main.py:126:handleKline:2218005: self.closeSec=1686125999, self.tradeDate='20230607', self.openTime='161500', self.closeTime='161959',self.symbol='BTCUSDT',self.open=26771.3, self.close=26794.3, self.high=26796.5, self.low=26765.8   
2023-06-07 16:20:01,054:INFO:factorcheck2:main.py:127:handleKline:2218005: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1631  20230607   155500    155959  1686124799  ...  26778.5 -0.001260   1631    5
1632  20230607   160000    160459  1686125099  ...  26777.9  0.000355   1632    0
1633  20230607   160500    160959  1686125399  ...  26785.0 -0.000343   1633    1
1634  20230607   161000    161459  1686125699  ...  26745.5 -0.000586   1634    2
1635  20230607   161500    161959  1686125999  ...  26765.8  0.000859   1635    3

[5 rows x 11 columns]
2023-06-07 16:20:01,054:INFO:factorcheck2:main.py:128:handleKline:2218005: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': False, 'isOpen': True, 'isClose': False, 'isTrig': True}

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=28, self.factor=0.38551567292728156, self.count=6979 

self.closeSec=1686126299, self.tradeDate='20230607', self.openTime='162000', self.closeTime='162459', self.symbol='BTCUSDT', self.open=26794.2, self.close=26810.0, self.high=26818.3, self.low=26794.2 
127.0.0.1 - - [07/Jun/2023 16:25:01] "POST / HTTP/1.1" 200 -
2023-06-07 16:25:02,931:INFO:factorcheck2:main.py:126:handleKline:2218005: self.closeSec=1686126299, self.tradeDate='20230607', self.openTime='162000', self.closeTime='162459',self.symbol='BTCUSDT',self.open=26794.2, self.close=26810.0, self.high=26818.3, self.low=26794.2   
2023-06-07 16:25:03,632:INFO:factorcheck2:main.py:127:handleKline:2218005: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1632  20230607   160000    160459  1686125099  ...  26777.9  0.000355   1632    0
1633  20230607   160500    160959  1686125399  ...  26785.0 -0.000343   1633    1
1634  20230607   161000    161459  1686125699  ...  26745.5 -0.000586   1634    2
1635  20230607   161500    161959  1686125999  ...  26765.8  0.000859   1635    3
1636  20230607   162000    162459  1686126299  ...  26794.2  0.000586   1636    4

[5 rows x 11 columns]
2023-06-07 16:25:03,635:INFO:factorcheck2:main.py:128:handleKline:2218005: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': False, 'isOpen': True, 'isClose': False, 'isTrig': True}


## /root/FIL/strategy/logic/log.txt ----- -----

2023-06-07 16:00:39,443:DEBUG:logic:main.py:463:getModel:2218526: df_s.iloc[-5:,:] :
          date closeTime     open  ...    alpha58   alpha67   alpha72
5786  20230607    132959  26917.2  ...  47.500000  0.567976  0.218823
5787  20230607    135959  26935.1  ...  47.083333  0.562024  0.220075
5788  20230607    142959  26901.9  ...  47.083333  0.561267  0.221378
5789  20230607    145959  26897.7  ...  47.083333  0.547262  0.225110
5790  20230607    152959  26819.6  ...  47.083333  0.549784  0.228040

[5 rows x 33 columns]
0.5166051660516605
acc is : 0.5166051660516605
2023-06-07 16:00:39,616:INFO:logic:main.py:468:getModel:2218526: df_pred.iloc[-5:,:] :
     pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
537     1  0.485576  0.514424       0  ...  1.105644  -1.0    0.0  1.009679
538     1  0.485778  0.514222       0  ...  1.105817  -1.0    0.0  1.009522
539     1  0.481023  0.518977       0  ...  1.109032  -1.0    0.0  1.006587
540     1  0.461996  0.538004       1  ...  1.108320  -1.0    0.0  1.007232
541     1  0.482143  0.517857       0  ...  1.110385  -1.0    0.0  1.005356

[5 rows x 10 columns]
2023-06-07 16:00:39,637:INFO:logic:main.py:478:getModel:2218526: df_panel.iloc[-5:,:] :
    pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
45     1  0.485530  0.514470       0  ...  1.105644  -1.0    0.0  1.008695
46     1  0.485540  0.514460       0  ...  1.105817  -1.0    0.0  1.007854
47     1  0.480617  0.519383       0  ...  1.109032  -1.0    0.0  1.004856
48     1  0.461936  0.538064       1  ...  1.108320  -1.0    0.0  1.007123
49     1  0.482143  0.517857       0  ...  1.110385  -1.0    0.0  1.005356

[5 rows x 10 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '28.022', 'enterprice': '26938.4', 'countrevence': '0', 'unrealprofit': '4346.34556398372', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '26783.29524074', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}


## /root/FIL/strategy/modifiedmom/log.txt ----- -----

527  20230607   155000    155959  1686124799  26827.8  26786.7 -0.001528
2023-06-07 16:00:02,183:INFO:modifiedmom:main.py:146:handleKline:2218259: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': True, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True}
127.0.0.1 - - [07/Jun/2023 16:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=3488 

self.closeSec=1686125399, self.tradeDate='20230607', self.openTime='160000', self.closeTime='160959', self.symbol='BTCUSDT', self.open='26786.8', self.close='26787'
2023-06-07 16:10:01,085:INFO:modifiedmom:main.py:144:handleKline:2218259: self.closeSec=1686125399, self.tradeDate='20230607', self.openTime='160000', self.closeTime='160959',self.symbol='BTCUSDT',self.open='26786.8', self.close='26787'
2023-06-07 16:10:01,147:INFO:modifiedmom:main.py:145:handleKline:2218259: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
524  20230607   152000    152959  1686122999    26777  26836.7  0.002226
525  20230607   153000    153959  1686123599  26836.7    26850  0.000496
526  20230607   154000    154959  1686124199  26849.9  26827.7 -0.000831
527  20230607   155000    155959  1686124799  26827.8  26786.7 -0.001528
528  20230607   160000    160959  1686125399  26786.8    26787  0.000011
2023-06-07 16:10:01,147:INFO:modifiedmom:main.py:146:handleKline:2218259: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': True, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True}
127.0.0.1 - - [07/Jun/2023 16:20:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=3489 

self.closeSec=1686125999, self.tradeDate='20230607', self.openTime='161000', self.closeTime='161959', self.symbol='BTCUSDT', self.open='26787', self.close='26794.3'
2023-06-07 16:20:01,307:INFO:modifiedmom:main.py:144:handleKline:2218259: self.closeSec=1686125999, self.tradeDate='20230607', self.openTime='161000', self.closeTime='161959',self.symbol='BTCUSDT',self.open='26787', self.close='26794.3'
2023-06-07 16:20:01,356:INFO:modifiedmom:main.py:145:handleKline:2218259: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
525  20230607   153000    153959  1686123599  26836.7    26850  0.000496
526  20230607   154000    154959  1686124199  26849.9  26827.7 -0.000831
527  20230607   155000    155959  1686124799  26827.8  26786.7 -0.001528
528  20230607   160000    160959  1686125399  26786.8    26787  0.000011
529  20230607   161000    161959  1686125999    26787  26794.3  0.000273
2023-06-07 16:20:01,358:INFO:modifiedmom:main.py:146:handleKline:2218259: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': True, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True}


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

17519  20230607   155000    155959  1686124799  26827.8  26786.7
2023-06-07 16:00:02,205:INFO:pyemd2:main.py:127:handleKline:2217508: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=3491 

self.closeSec=1686125399, self.tradeDate='20230607', self.openTime='160000', self.closeTime='160959', self.symbol='BTCUSDT', self.open='26786.8', self.close='26787'
2023-06-07 16:10:01,109:INFO:pyemd2:main.py:125:handleKline:2217508: self.closeSec=1686125399, self.tradeDate='20230607', self.openTime='160000', self.closeTime='160959',self.symbol='BTCUSDT',self.open='26786.8', self.close='26787'
127.0.0.1 - - [07/Jun/2023 16:10:01] "POST / HTTP/1.1" 200 -
2023-06-07 16:10:01,144:INFO:pyemd2:main.py:126:handleKline:2217508: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17516  20230607   152000    152959  1686122999    26777  26836.7
17517  20230607   153000    153959  1686123599  26836.7    26850
17518  20230607   154000    154959  1686124199  26849.9  26827.7
17519  20230607   155000    155959  1686124799  26827.8  26786.7
17520  20230607   160000    160959  1686125399  26786.8    26787
2023-06-07 16:10:01,144:INFO:pyemd2:main.py:127:handleKline:2217508: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}
127.0.0.1 - - [07/Jun/2023 16:20:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=3492 

self.closeSec=1686125999, self.tradeDate='20230607', self.openTime='161000', self.closeTime='161959', self.symbol='BTCUSDT', self.open='26787', self.close='26794.3'
2023-06-07 16:20:01,332:INFO:pyemd2:main.py:125:handleKline:2217508: self.closeSec=1686125999, self.tradeDate='20230607', self.openTime='161000', self.closeTime='161959',self.symbol='BTCUSDT',self.open='26787', self.close='26794.3'
2023-06-07 16:20:01,373:INFO:pyemd2:main.py:126:handleKline:2217508: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17517  20230607   153000    153959  1686123599  26836.7    26850
17518  20230607   154000    154959  1686124199  26849.9  26827.7
17519  20230607   155000    155959  1686124799  26827.8  26786.7
17520  20230607   160000    160959  1686125399  26786.8    26787
17521  20230607   161000    161959  1686125999    26787  26794.3
2023-06-07 16:20:01,374:INFO:pyemd2:main.py:127:handleKline:2217508: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}


## /root/FIL/strategy/similarity/log.txt ----- -----

12191  20230607   155000    155959  1686124799  26827.8  26786.7
2023-06-07 16:00:02,175:INFO:testStrategy:main.py:103:handleKline:2217133: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': True, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}
127.0.0.1 - - [07/Jun/2023 16:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=3491 

self.closeSec=1686125399, self.tradeDate='20230607', self.openTime='160000', self.closeTime='160959', self.symbol='BTCUSDT', self.open='26786.8', self.close='26787'
2023-06-07 16:10:01,108:INFO:testStrategy:main.py:101:handleKline:2217133: self.closeSec=1686125399, self.tradeDate='20230607', self.openTime='160000', self.closeTime='160959',self.symbol='BTCUSDT',self.open='26786.8', self.close='26787'
2023-06-07 16:10:01,141:INFO:testStrategy:main.py:102:handleKline:2217133: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12188  20230607   152000    152959  1686122999    26777  26836.7
12189  20230607   153000    153959  1686123599  26836.7    26850
12190  20230607   154000    154959  1686124199  26849.9  26827.7
12191  20230607   155000    155959  1686124799  26827.8  26786.7
12192  20230607   160000    160959  1686125399  26786.8    26787
2023-06-07 16:10:01,141:INFO:testStrategy:main.py:103:handleKline:2217133: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': True, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=3492 

self.closeSec=1686125999, self.tradeDate='20230607', self.openTime='161000', self.closeTime='161959', self.symbol='BTCUSDT', self.open='26787', self.close='26794.3'
127.0.0.1 - - [07/Jun/2023 16:20:01] "POST / HTTP/1.1" 200 -
2023-06-07 16:20:01,312:INFO:testStrategy:main.py:101:handleKline:2217133: self.closeSec=1686125999, self.tradeDate='20230607', self.openTime='161000', self.closeTime='161959',self.symbol='BTCUSDT',self.open='26787', self.close='26794.3'
2023-06-07 16:20:01,366:INFO:testStrategy:main.py:102:handleKline:2217133: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12189  20230607   153000    153959  1686123599  26836.7    26850
12190  20230607   154000    154959  1686124199  26849.9  26827.7
12191  20230607   155000    155959  1686124799  26827.8  26786.7
12192  20230607   160000    160959  1686125399  26786.8    26787
12193  20230607   161000    161959  1686125999    26787  26794.3
2023-06-07 16:20:01,366:INFO:testStrategy:main.py:103:handleKline:2217133: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': True, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}


## /root/FIL/strategy/sr_min/log.txt ----- -----

--handleKline--:  127.0.0.1 - - [07/Jun/2023 16:20:00] "POST / HTTP/1.1" 200 -
version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=1, self.total=996015.990996, self.flagDict['side']='buy', self.tradeCount=1, self.count=6976
self.closeSec=1686125999, self.tradeDate='20230607', self.openTime='161500', self.closeTime='161959', self.symbol='BTCUSDT', self.open=26771.3, self.close=26794.3, self.high=26796.5, self.low=26765.8, self.vol=628.159, self.amt=16824019.034 
2023-06-07 16:20:01,032:INFO:sr_min:main.py:172:handleKline:2219263: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5951  20230607   155500    155959  ...         0.0        0.0       0
5952  20230607   160000    160459  ...         0.0        0.0       0
5953  20230607   160500    160959  ...         0.0        0.0       0
5954  20230607   161000    161459  ...         0.0        0.0       0
5955  20230607   161500    161959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-06-07 16:20:01,038:INFO:sr_min:main.py:175:handleKline:2219263: self.closeSec=1686125999, self.tradeDate='20230607', self.openTime='161500', self.closeTime='161959',self.symbol='BTCUSDT',self.open=26771.3, self.close=26794.3, self.high=26796.5, self.low=26765.8, self.vol=628.159, self.amt=16824019.034, ukdf['pct'].iloc[-1]=0.000859 , ukdf['amount'].iloc[-1]=16824019.034, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5955, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '37.141', 'enterprice': '26844', 'countrevence': '0', 'unrealprofit': '-1797.77534213823', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '26795.59593597', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=1
--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=1, self.total=996015.990996, self.flagDict['side']='buy', self.tradeCount=1, self.count=6977
self.closeSec=1686126299, self.tradeDate='20230607', self.openTime='162000', self.closeTime='162459', self.symbol='BTCUSDT', self.open=26794.2, self.close=26810.0, self.high=26818.3, self.low=26794.2, self.vol=923.255, self.amt=24752369.6942 
127.0.0.1 - - [07/Jun/2023 16:25:01] "POST / HTTP/1.1" 200 -
2023-06-07 16:25:03,988:INFO:sr_min:main.py:172:handleKline:2219263: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5952  20230607   160000    160459  ...         0.0        0.0       0
5953  20230607   160500    160959  ...         0.0        0.0       0
5954  20230607   161000    161459  ...         0.0        0.0       0
5955  20230607   161500    161959  ...         0.0        0.0       0
5956  20230607   162000    162459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-06-07 16:25:04,001:INFO:sr_min:main.py:175:handleKline:2219263: self.closeSec=1686126299, self.tradeDate='20230607', self.openTime='162000', self.closeTime='162459',self.symbol='BTCUSDT',self.open=26794.2, self.close=26810.0, self.high=26818.3, self.low=26794.2, self.vol=923.255, self.amt=24752369.6942, ukdf['pct'].iloc[-1]=0.000586 , ukdf['amount'].iloc[-1]=24752369.6942, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5956, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '37.141', 'enterprice': '26844', 'countrevence': '0', 'unrealprofit': '-1243.1372483153', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '26810.5292467', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=1


## /root/FIL/strategy/s_rsrs/log.txt ----- -----

721  20230607   040000    075959  1686095999  ...    721  0.501330 -0.266944     NaN
722  20230607   080000    115959  1686110399  ...    722  0.502091 -0.284508     NaN

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '55.166', 'enterprice': '27078.6', 'countrevence': '0', 'unrealprofit': '9598.884', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '26904.6', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-9223372036854775808, self.sign=-1
127.0.0.1 - - [07/Jun/2023 16:00:01] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='s_rsrs', self.symbol='BTCUSDT', interval='4h', intervalSec=14400, wid=25, thd=0.6, self.sign=-1, self.total=1492324.2295523998, self.flagDict['side']='sell', self.tradeCount=4, self.count=145
self.closeSec=1686124799, self.tradeDate='20230607', self.openTime='120000', self.closeTime='155959', self.symbol='BTCUSDT', self.open=26896.9, self.close=26786.7, self.high=26973.9, self.low=26741.0, self.vol=47010.017, self.amt=1263079541.7684 
2023-06-07 16:00:01,716:INFO:s_rsrs:main.py:141:handleKline:2218689: self.closeSec=1686124799, self.tradeDate='20230607', self.openTime='120000', self.closeTime='155959',self.symbol='BTCUSDT',self.open=26896.9, self.close=26786.7, self.high=26973.9, self.low=26741.0, self.vol=47010.017, self.amt=1263079541.7684 
2023-06-07 16:00:01,777:INFO:s_rsrs:main.py:142:handleKline:2218689: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime  ...         vol           amt       pct
719  20230606   200000    235959  ...  252404.577  6.498559e+09  0.014613
720  20230607   000000    035959  ...  249451.290  6.638496e+09  0.039230
721  20230607   040000    075959  ...  113750.962  3.081163e+09  0.005478
722  20230607   080000    115959  ...  114373.103  3.092580e+09 -0.011921
723  20230607   120000    155959  ...   47010.017  1.263080e+09 -0.004101

[5 rows x 11 columns]
2023-06-07 16:00:04,128:INFO:s_rsrs:main.py:151:handleKline:2218689: df_s.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec  ...  index      beta    zscore  signal
719  20230606   200000    235959  1686067199  ...    719  0.604946  0.090038     NaN
720  20230607   000000    035959  1686081599  ...    720  0.498911 -0.255792     NaN
721  20230607   040000    075959  1686095999  ...    721  0.501330 -0.266944     NaN
722  20230607   080000    115959  1686110399  ...    722  0.502091 -0.284508     NaN
723  20230607   120000    155959  1686124799  ...    723  0.503559 -0.291878     NaN

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '55.166', 'enterprice': '27078.6', 'countrevence': '0', 'unrealprofit': '15872.02602907432', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '26790.88608148', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-9223372036854775808, self.sign=-1


