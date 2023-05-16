# 20230516 08:26:02

## /root/FIL/strategy/amihud/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=373746.4768026, self.flagDict['side']='sell', self.tradeCount=2, self.count=544
self.closeSec=1684196399, self.tradeDate='20230516', self.openTime='081500', self.closeTime='081959', self.symbol='BTCUSDT', self.open=27208.9, self.close=27242.4, self.high=27250.5, self.low=27190.3, self.vol=1759.44, self.amt=47912171.828 
127.0.0.1 - - [16/May/2023 08:20:00] "POST / HTTP/1.1" 200 -
2023-05-16 08:20:00,499:INFO:amihud:main.py:172:handleKline:2219019: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5855  20230516   075500    075959  ...    0.490017   0.237324       0
5856  20230516   080000    080459  ...    0.489842   0.237453       0
5857  20230516   080500    080959  ...    0.489667   0.237582       0
5858  20230516   081000    081459  ...    0.489492   0.237711       0
5859  20230516   081500    081959  ...    0.489319   0.237840       0

[5 rows x 18 columns]
2023-05-16 08:20:00,501:INFO:amihud:main.py:175:handleKline:2219019: self.closeSec=1684196399, self.tradeDate='20230516', self.openTime='081500', self.closeTime='081959',self.symbol='BTCUSDT',self.open=27208.9, self.close=27242.4, self.high=27250.5, self.low=27190.3, self.vol=1759.44, self.amt=47912171.828, ukdf['pct'].iloc[-1]=0.001231 , ukdf['amount'].iloc[-1]=47912171.828, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5859, value=0.0, value_mean=0.48931924790992726, signal=0, value_std=0.23783996767521506 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '13.926', 'enterprice': '26864.9', 'countrevence': '0', 'unrealprofit': '-5315.6906288442', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '27246.6097967', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1
--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=373746.4768026, self.flagDict['side']='sell', self.tradeCount=2, self.count=545
self.closeSec=1684196699, self.tradeDate='20230516', self.openTime='082000', self.closeTime='082459', self.symbol='BTCUSDT', self.open=27242.3, self.close=27274.2, self.high=27278.0, self.low=27242.3, self.vol=1289.714, self.amt=35158948.2508 
127.0.0.1 - - [16/May/2023 08:25:00] "POST / HTTP/1.1" 200 -
2023-05-16 08:25:00,377:INFO:amihud:main.py:172:handleKline:2219019: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5856  20230516   080000    080459  ...    0.489842   0.237453       0
5857  20230516   080500    080959  ...    0.489667   0.237582       0
5858  20230516   081000    081459  ...    0.489492   0.237711       0
5859  20230516   081500    081959  ...    0.489319   0.237840       0
5860  20230516   082000    082459  ...    0.489147   0.237970       0

[5 rows x 18 columns]
2023-05-16 08:25:00,379:INFO:amihud:main.py:175:handleKline:2219019: self.closeSec=1684196699, self.tradeDate='20230516', self.openTime='082000', self.closeTime='082459',self.symbol='BTCUSDT',self.open=27242.3, self.close=27274.2, self.high=27278.0, self.low=27242.3, self.vol=1289.714, self.amt=35158948.2508, ukdf['pct'].iloc[-1]=0.001167 , ukdf['amount'].iloc[-1]=35158948.2508, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5860, value=0.0, value_mean=0.48914669095768293, signal=0, value_std=0.23796953182638517 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '13.926', 'enterprice': '26864.9', 'countrevence': '0', 'unrealprofit': '-5730.34074767154', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '27276.38504579', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1


## /root/FIL/strategy/factorcheck/log.txt ----- -----


self.closeSec=1684196399, self.tradeDate='20230516', self.openTime='081500', self.closeTime='081959', self.symbol='BTCUSDT', self.open=27208.9, self.close=27242.4, self.high=27250.5, self.low=27190.3 
127.0.0.1 - - [16/May/2023 08:20:00] "POST / HTTP/1.1" 200 -
2023-05-16 08:20:00,427:INFO:factorcheck2:main.py:126:handleKline:2218005: self.closeSec=1684196399, self.tradeDate='20230516', self.openTime='081500', self.closeTime='081959',self.symbol='BTCUSDT',self.open=27208.9, self.close=27242.4, self.high=27250.5, self.low=27190.3   
2023-05-16 08:20:00,478:INFO:factorcheck2:main.py:127:handleKline:2218005: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1534  20230516   075500    075959  1684195199  ...  27142.5 -0.000721   1534    4
1535  20230516   080000    080459  1684195499  ...  27132.5  0.000372   1535    5
1536  20230516   080500    080959  1684195799  ...  27158.7  0.001300   1536    0
1537  20230516   081000    081459  1684196099  ...  27178.3  0.000404   1537    1
1538  20230516   081500    081959  1684196399  ...  27190.3  0.001231   1538    2

[5 rows x 11 columns]
2023-05-16 08:20:00,479:INFO:factorcheck2:main.py:128:handleKline:2218005: self.flagDict={'side': '', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=90, self.factor=0.332695032676846, self.count=547 

self.closeSec=1684196699, self.tradeDate='20230516', self.openTime='082000', self.closeTime='082459', self.symbol='BTCUSDT', self.open=27242.3, self.close=27274.2, self.high=27278.0, self.low=27242.3 
2023-05-16 08:25:00,407:INFO:factorcheck2:main.py:126:handleKline:2218005: self.closeSec=1684196699, self.tradeDate='20230516', self.openTime='082000', self.closeTime='082459',self.symbol='BTCUSDT',self.open=27242.3, self.close=27274.2, self.high=27278.0, self.low=27242.3   
127.0.0.1 - - [16/May/2023 08:25:00] "POST / HTTP/1.1" 200 -
2023-05-16 08:25:00,433:INFO:factorcheck2:main.py:127:handleKline:2218005: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1535  20230516   080000    080459  1684195499  ...  27132.5  0.000372   1535    5
1536  20230516   080500    080959  1684195799  ...  27158.7  0.001300   1536    0
1537  20230516   081000    081459  1684196099  ...  27178.3  0.000404   1537    1
1538  20230516   081500    081959  1684196399  ...  27190.3  0.001231   1538    2
1539  20230516   082000    082459  1684196699  ...  27242.3  0.001167   1539    3

[5 rows x 11 columns]
2023-05-16 08:25:00,434:INFO:factorcheck2:main.py:128:handleKline:2218005: self.flagDict={'side': '', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}


## /root/FIL/strategy/logic/log.txt ----- -----

2023-05-16 08:00:18,136:DEBUG:logic:main.py:463:getModel:2218526: df_s.iloc[-5:,:] :
          date closeTime     open  ...    alpha58   alpha67   alpha72
5770  20230516    052959  27338.5  ...  49.583333  0.549883  0.255577
5771  20230516    055959  27341.1  ...  50.000000  0.552321  0.274949
5772  20230516    062959  27352.4  ...  50.000000  0.552895  0.294534
5773  20230516    065959  27355.0  ...  49.583333  0.537618  0.321200
5774  20230516    072959  27298.6  ...  49.583333  0.529819  0.352169

[5 rows x 33 columns]
0.5286506469500925
acc is : 0.5286506469500925
2023-05-16 08:00:18,227:INFO:logic:main.py:468:getModel:2218526: df_pred.iloc[-5:,:] :
     pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
536     1  0.485723  0.514277       1  ...  1.002260   1.0    0.0  0.947926
537     1  0.491480  0.508520       1  ...  1.002355   1.0    0.0  0.948016
538     1  0.487504  0.512496       0  ...  1.000285   1.0    0.0  0.946058
539     1  0.478055  0.521945       0  ...  0.999204   1.0    0.0  0.945036
540     1  0.480588  0.519412       0  ...  0.994935   1.0    0.0  0.940998

[5 rows x 10 columns]
2023-05-16 08:00:18,239:INFO:logic:main.py:478:getModel:2218526: df_panel.iloc[-5:,:] :
    pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
45     1  0.485284  0.514716       1  ...  1.002260   1.0    0.0  0.948090
46     1  0.490833  0.509167       1  ...  1.002355   1.0    0.0  0.945751
47     1  0.487100  0.512900       0  ...  1.000285   1.0    0.0  0.944278
48     1  0.477919  0.522081       0  ...  0.999204   1.0    0.0  0.945036
49     1  0.480588  0.519412       0  ...  0.994935   1.0    0.0  0.940998

[5 rows x 10 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '28.199', 'enterprice': '26801.5', 'countrevence': '0', 'unrealprofit': '9834.95923912245', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '27150.26978755', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}


## /root/FIL/strategy/modifiedmom/log.txt ----- -----

623  20230516   075000    075959  1684195199  27176.1  27152.5 -0.000868
2023-05-16 08:00:00,407:INFO:modifiedmom:main.py:146:handleKline:2218259: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False}
127.0.0.1 - - [16/May/2023 08:10:00] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=272 

self.closeSec=1684195799, self.tradeDate='20230516', self.openTime='080000', self.closeTime='080959', self.symbol='BTCUSDT', self.open='27152.5', self.close='27197.9'
2023-05-16 08:10:00,387:INFO:modifiedmom:main.py:144:handleKline:2218259: self.closeSec=1684195799, self.tradeDate='20230516', self.openTime='080000', self.closeTime='080959',self.symbol='BTCUSDT',self.open='27152.5', self.close='27197.9'
2023-05-16 08:10:00,420:INFO:modifiedmom:main.py:145:handleKline:2218259: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
620  20230516   072000    072959  1684193399  27288.8    27269 -0.000722
621  20230516   073000    073959  1684193999  27269.1  27253.3 -0.000576
622  20230516   074000    074959  1684194599  27253.3  27176.1 -0.002833
623  20230516   075000    075959  1684195199  27176.1  27152.5 -0.000868
624  20230516   080000    080959  1684195799  27152.5  27197.9  0.001672
2023-05-16 08:10:00,420:INFO:modifiedmom:main.py:146:handleKline:2218259: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False}
127.0.0.1 - - [16/May/2023 08:20:00] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=273 

self.closeSec=1684196399, self.tradeDate='20230516', self.openTime='081000', self.closeTime='081959', self.symbol='BTCUSDT', self.open='27198', self.close='27242.4'
2023-05-16 08:20:00,413:INFO:modifiedmom:main.py:144:handleKline:2218259: self.closeSec=1684196399, self.tradeDate='20230516', self.openTime='081000', self.closeTime='081959',self.symbol='BTCUSDT',self.open='27198', self.close='27242.4'
2023-05-16 08:20:00,457:INFO:modifiedmom:main.py:145:handleKline:2218259: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
621  20230516   073000    073959  1684193999  27269.1  27253.3 -0.000576
622  20230516   074000    074959  1684194599  27253.3  27176.1 -0.002833
623  20230516   075000    075959  1684195199  27176.1  27152.5 -0.000868
624  20230516   080000    080959  1684195799  27152.5  27197.9  0.001672
625  20230516   081000    081959  1684196399    27198  27242.4  0.001636
2023-05-16 08:20:00,458:INFO:modifiedmom:main.py:146:handleKline:2218259: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False}


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

17471  20230516   075000    075959  1684195199  27176.1  27152.5
2023-05-16 08:00:00,431:INFO:pyemd2:main.py:127:handleKline:2217508: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}
127.0.0.1 - - [16/May/2023 08:10:00] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=275 

self.closeSec=1684195799, self.tradeDate='20230516', self.openTime='080000', self.closeTime='080959', self.symbol='BTCUSDT', self.open='27152.5', self.close='27197.9'
2023-05-16 08:10:00,396:INFO:pyemd2:main.py:125:handleKline:2217508: self.closeSec=1684195799, self.tradeDate='20230516', self.openTime='080000', self.closeTime='080959',self.symbol='BTCUSDT',self.open='27152.5', self.close='27197.9'
2023-05-16 08:10:00,447:INFO:pyemd2:main.py:126:handleKline:2217508: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17468  20230516   072000    072959  1684193399  27288.8    27269
17469  20230516   073000    073959  1684193999  27269.1  27253.3
17470  20230516   074000    074959  1684194599  27253.3  27176.1
17471  20230516   075000    075959  1684195199  27176.1  27152.5
17472  20230516   080000    080959  1684195799  27152.5  27197.9
2023-05-16 08:10:00,448:INFO:pyemd2:main.py:127:handleKline:2217508: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=276 

self.closeSec=1684196399, self.tradeDate='20230516', self.openTime='081000', self.closeTime='081959', self.symbol='BTCUSDT', self.open='27198', self.close='27242.4'
127.0.0.1 - - [16/May/2023 08:20:00] "POST / HTTP/1.1" 200 -
2023-05-16 08:20:00,400:INFO:pyemd2:main.py:125:handleKline:2217508: self.closeSec=1684196399, self.tradeDate='20230516', self.openTime='081000', self.closeTime='081959',self.symbol='BTCUSDT',self.open='27198', self.close='27242.4'
2023-05-16 08:20:00,464:INFO:pyemd2:main.py:126:handleKline:2217508: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17469  20230516   073000    073959  1684193999  27269.1  27253.3
17470  20230516   074000    074959  1684194599  27253.3  27176.1
17471  20230516   075000    075959  1684195199  27176.1  27152.5
17472  20230516   080000    080959  1684195799  27152.5  27197.9
17473  20230516   081000    081959  1684196399    27198  27242.4
2023-05-16 08:20:00,464:INFO:pyemd2:main.py:127:handleKline:2217508: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}


## /root/FIL/strategy/similarity/log.txt ----- -----

12143  20230516   075000    075959  1684195199  27176.1  27152.5
2023-05-16 08:00:00,422:INFO:testStrategy:main.py:103:handleKline:2217133: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': True, 'isCloseBuy': False, 'isCloseSell': False, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}
127.0.0.1 - - [16/May/2023 08:10:00] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=275 

self.closeSec=1684195799, self.tradeDate='20230516', self.openTime='080000', self.closeTime='080959', self.symbol='BTCUSDT', self.open='27152.5', self.close='27197.9'
2023-05-16 08:10:00,391:INFO:testStrategy:main.py:101:handleKline:2217133: self.closeSec=1684195799, self.tradeDate='20230516', self.openTime='080000', self.closeTime='080959',self.symbol='BTCUSDT',self.open='27152.5', self.close='27197.9'
2023-05-16 08:10:00,430:INFO:testStrategy:main.py:102:handleKline:2217133: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12140  20230516   072000    072959  1684193399  27288.8    27269
12141  20230516   073000    073959  1684193999  27269.1  27253.3
12142  20230516   074000    074959  1684194599  27253.3  27176.1
12143  20230516   075000    075959  1684195199  27176.1  27152.5
12144  20230516   080000    080959  1684195799  27152.5  27197.9
2023-05-16 08:10:00,430:INFO:testStrategy:main.py:103:handleKline:2217133: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': True, 'isCloseBuy': False, 'isCloseSell': False, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=276 

self.closeSec=1684196399, self.tradeDate='20230516', self.openTime='081000', self.closeTime='081959', self.symbol='BTCUSDT', self.open='27198', self.close='27242.4'
127.0.0.1 - - [16/May/2023 08:20:00] "POST / HTTP/1.1" 200 -
2023-05-16 08:20:00,415:INFO:testStrategy:main.py:101:handleKline:2217133: self.closeSec=1684196399, self.tradeDate='20230516', self.openTime='081000', self.closeTime='081959',self.symbol='BTCUSDT',self.open='27198', self.close='27242.4'
2023-05-16 08:20:00,466:INFO:testStrategy:main.py:102:handleKline:2217133: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12141  20230516   073000    073959  1684193999  27269.1  27253.3
12142  20230516   074000    074959  1684194599  27253.3  27176.1
12143  20230516   075000    075959  1684195199  27176.1  27152.5
12144  20230516   080000    080959  1684195799  27152.5  27197.9
12145  20230516   081000    081959  1684196399    27198  27242.4
2023-05-16 08:20:00,466:INFO:testStrategy:main.py:103:handleKline:2217133: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': True, 'isCloseBuy': False, 'isCloseSell': False, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}


## /root/FIL/strategy/sr_min/log.txt ----- -----

127.0.0.1 - - [16/May/2023 08:20:00] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=1, self.total=996015.990996, self.flagDict['side']='buy', self.tradeCount=1, self.count=544
self.closeSec=1684196399, self.tradeDate='20230516', self.openTime='081500', self.closeTime='081959', self.symbol='BTCUSDT', self.open=27208.9, self.close=27242.4, self.high=27250.5, self.low=27190.3, self.vol=1759.44, self.amt=47912171.828 
2023-05-16 08:20:00,506:INFO:sr_min:main.py:172:handleKline:2219263: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5855  20230516   075500    075959  ...    0.420111   0.243580       0
5856  20230516   080000    080459  ...    0.419852   0.243762       0
5857  20230516   080500    080959  ...    0.419593   0.243943       0
5858  20230516   081000    081459  ...    0.419333   0.244125       0
5859  20230516   081500    081959  ...    0.419074   0.244305       0

[5 rows x 18 columns]
2023-05-16 08:20:00,507:INFO:sr_min:main.py:175:handleKline:2219263: self.closeSec=1684196399, self.tradeDate='20230516', self.openTime='081500', self.closeTime='081959',self.symbol='BTCUSDT',self.open=27208.9, self.close=27242.4, self.high=27250.5, self.low=27190.3, self.vol=1759.44, self.amt=47912171.828, ukdf['pct'].iloc[-1]=0.001231 , ukdf['amount'].iloc[-1]=47912171.828, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5859, value=0.0, value_mean=0.419073955300578, signal=0, value_std=0.2443052871409783 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '37.141', 'enterprice': '26844', 'countrevence': '0', 'unrealprofit': '14953.3304592347', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '27246.6097967', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=1
--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=1, self.total=996015.990996, self.flagDict['side']='buy', self.tradeCount=1, self.count=545
self.closeSec=1684196699, self.tradeDate='20230516', self.openTime='082000', self.closeTime='082459', self.symbol='BTCUSDT', self.open=27242.3, self.close=27274.2, self.high=27278.0, self.low=27242.3, self.vol=1289.714, self.amt=35158948.2508 
127.0.0.1 - - [16/May/2023 08:25:00] "POST / HTTP/1.1" 200 -
2023-05-16 08:25:00,443:INFO:sr_min:main.py:172:handleKline:2219263: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5856  20230516   080000    080459  ...    0.419852   0.243762       0
5857  20230516   080500    080959  ...    0.419593   0.243943       0
5858  20230516   081000    081459  ...    0.419333   0.244125       0
5859  20230516   081500    081959  ...    0.419074   0.244305       0
5860  20230516   082000    082459  ...    0.418814   0.244485       0

[5 rows x 18 columns]
2023-05-16 08:25:00,443:INFO:sr_min:main.py:175:handleKline:2219263: self.closeSec=1684196699, self.tradeDate='20230516', self.openTime='082000', self.closeTime='082459',self.symbol='BTCUSDT',self.open=27242.3, self.close=27274.2, self.high=27278.0, self.low=27242.3, self.vol=1289.714, self.amt=35158948.2508, ukdf['pct'].iloc[-1]=0.001167 , ukdf['amount'].iloc[-1]=35158948.2508, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5860, value=0.0, value_mean=0.41881386469686305, signal=0, value_std=0.24448541387877115 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '37.141', 'enterprice': '26844', 'countrevence': '0', 'unrealprofit': '16059.21298568639', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '27276.38504579', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=1


## /root/FIL/strategy/s_rsrs/log.txt ----- -----

719  20230515   200000    235959  1684166399  ...    719  0.403817 -0.320462     NaN
720  20230516   000000    035959  1684180799  ...    720  0.441302 -0.161099     NaN

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '52.436', 'enterprice': '26818.7', 'countrevence': '0', 'unrealprofit': '-30840.8249908174', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '27406.86128215', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-9223372036854775808, self.sign=-1
127.0.0.1 - - [16/May/2023 08:00:00] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='s_rsrs', self.symbol='BTCUSDT', interval='4h', intervalSec=14400, wid=25, thd=0.6, self.sign=-1, self.total=6897.9369698, self.flagDict['side']='', self.tradeCount=0, self.count=11
self.closeSec=1684195199, self.tradeDate='20230516', self.openTime='040000', self.closeTime='075959', self.symbol='BTCUSDT', self.open=27410.1, self.close=27152.5, self.high=27410.1, self.low=27100.0, self.vol=38932.072, self.amt=1061730858.85298 
2023-05-16 08:00:00,388:INFO:s_rsrs:main.py:141:handleKline:2218689: self.closeSec=1684195199, self.tradeDate='20230516', self.openTime='040000', self.closeTime='075959',self.symbol='BTCUSDT',self.open=27410.1, self.close=27152.5, self.high=27410.1, self.low=27100.0, self.vol=38932.072, self.amt=1061730858.85298 
2023-05-16 08:00:00,449:INFO:s_rsrs:main.py:142:handleKline:2218689: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime  ...        vol           amt       pct
717  20230515   120000    155959  ...  93928.690  2.569898e+09  0.006698
718  20230515   160000    195959  ...  39961.711  1.094175e+09 -0.002752
719  20230515   200000    235959  ...  79836.823  2.184424e+09  0.002189
720  20230516   000000    035959  ...  97469.170  2.677565e+09  0.000990
721  20230516   040000    075959  ...  38932.072  1.061731e+09 -0.009398

[5 rows x 11 columns]
2023-05-16 08:00:01,973:INFO:s_rsrs:main.py:151:handleKline:2218689: df_s.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec  ...  index      beta    zscore  signal
717  20230515   120000    155959  1684137599  ...    717  0.395800 -0.299161     NaN
718  20230515   160000    195959  1684151999  ...    718  0.390643 -0.353810     NaN
719  20230515   200000    235959  1684166399  ...    719  0.403817 -0.320462     NaN
720  20230516   000000    035959  1684180799  ...    720  0.441302 -0.161099     NaN
721  20230516   040000    075959  1684195199  ...    721  0.467538 -0.050923     NaN

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '52.436', 'enterprice': '26818.7', 'countrevence': '0', 'unrealprofit': '-17053.27391145508', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '27143.92072453', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-9223372036854775808, self.sign=-1


