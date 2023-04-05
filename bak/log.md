# 20230405 08:26:02

## /root/FIL/strategy/amihud/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=993672.4896432, self.flagDict['side']='sell', self.tradeCount=2, self.count=37084
self.closeSec=1680653999, self.tradeDate='20230405', self.openTime='081500', self.closeTime='081959', self.symbol='BTCUSDT', self.open=28122.2, self.close=28148.4, self.high=28165.6, self.low=28085.8, self.vol=1319.016, self.amt=37101278.2492 
127.0.0.1 - - [05/Apr/2023 08:20:03] "POST / HTTP/1.1" 200 -
2023-04-05 08:20:08,816:INFO:amihud:main.py:172:handleKline:200676: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5855  20230405   075500    075959  ...         0.0        0.0       0
5856  20230405   080000    080459  ...         0.0        0.0       0
5857  20230405   080500    080959  ...         0.0        0.0       0
5858  20230405   081000    081459  ...         0.0        0.0       0
5859  20230405   081500    081959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-04-05 08:20:08,835:INFO:amihud:main.py:175:handleKline:200676: self.closeSec=1680653999, self.tradeDate='20230405', self.openTime='081500', self.closeTime='081959',self.symbol='BTCUSDT',self.open=28122.2, self.close=28148.4, self.high=28165.6, self.low=28085.8, self.vol=1319.016, self.amt=37101278.2492, ukdf['pct'].iloc[-1]=0.000928 , ukdf['amount'].iloc[-1]=37101278.2492, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5859, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '60.176', 'enterprice': '16529.3', 'countrevence': '0', 'unrealprofit': '-699348.11074620256', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '28151.01149206', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1
127.0.0.1 - - [05/Apr/2023 08:25:01] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=993672.4896432, self.flagDict['side']='sell', self.tradeCount=2, self.count=37085
self.closeSec=1680654299, self.tradeDate='20230405', self.openTime='082000', self.closeTime='082459', self.symbol='BTCUSDT', self.open=28148.4, self.close=28255.0, self.high=28270.0, self.low=28132.1, self.vol=2870.38, self.amt=80963675.5971 
2023-04-05 08:25:01,571:INFO:amihud:main.py:172:handleKline:200676: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5856  20230405   080000    080459  ...         0.0        0.0       0
5857  20230405   080500    080959  ...         0.0        0.0       0
5858  20230405   081000    081459  ...         0.0        0.0       0
5859  20230405   081500    081959  ...         0.0        0.0       0
5860  20230405   082000    082459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-04-05 08:25:01,575:INFO:amihud:main.py:175:handleKline:200676: self.closeSec=1680654299, self.tradeDate='20230405', self.openTime='082000', self.closeTime='082459',self.symbol='BTCUSDT',self.open=28148.4, self.close=28255.0, self.high=28270.0, self.low=28132.1, self.vol=2870.38, self.amt=80963675.5971, ukdf['pct'].iloc[-1]=0.003787 , ukdf['amount'].iloc[-1]=80963675.5971, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5860, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '60.176', 'enterprice': '16529.3', 'countrevence': '0', 'unrealprofit': '-705740.34574764208', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '28257.23714683', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1


## /root/FIL/strategy/factorcheck/log.txt ----- -----


self.closeSec=1680653999, self.tradeDate='20230405', self.openTime='081500', self.closeTime='081959', self.symbol='BTCUSDT', self.open=28122.2, self.close=28148.4, self.high=28165.6, self.low=28085.8 
127.0.0.1 - - [05/Apr/2023 08:20:03] "POST / HTTP/1.1" 200 -
2023-04-05 08:20:05,716:INFO:factorcheck2:main.py:126:handleKline:185239: self.closeSec=1680653999, self.tradeDate='20230405', self.openTime='081500', self.closeTime='081959',self.symbol='BTCUSDT',self.open=28122.2, self.close=28148.4, self.high=28165.6, self.low=28085.8   
2023-04-05 08:20:06,685:INFO:factorcheck2:main.py:127:handleKline:185239: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1535  20230405   075500    075959  1680652799  ...  28140.5 -0.000028   1535    5
1536  20230405   080000    080459  1680653099  ...  28140.0 -0.000519   1536    0
1537  20230405   080500    080959  1680653399  ...  28129.8 -0.000334   1537    1
1538  20230405   081000    081459  1680653699  ...  28122.2 -0.000316   1538    2
1539  20230405   081500    081959  1680653999  ...  28085.8  0.000928   1539    3

[5 rows x 11 columns]
2023-04-05 08:20:06,686:INFO:factorcheck2:main.py:128:handleKline:185239: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=25, self.factor=0.3809243771126813, self.count=37651 

self.closeSec=1680654299, self.tradeDate='20230405', self.openTime='082000', self.closeTime='082459', self.symbol='BTCUSDT', self.open=28148.4, self.close=28255.0, self.high=28270.0, self.low=28132.1 
127.0.0.1 - - [05/Apr/2023 08:25:01] "POST / HTTP/1.1" 200 -
2023-04-05 08:25:01,506:INFO:factorcheck2:main.py:126:handleKline:185239: self.closeSec=1680654299, self.tradeDate='20230405', self.openTime='082000', self.closeTime='082459',self.symbol='BTCUSDT',self.open=28148.4, self.close=28255.0, self.high=28270.0, self.low=28132.1   
2023-04-05 08:25:01,548:INFO:factorcheck2:main.py:127:handleKline:185239: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1536  20230405   080000    080459  1680653099  ...  28140.0 -0.000519   1536    0
1537  20230405   080500    080959  1680653399  ...  28129.8 -0.000334   1537    1
1538  20230405   081000    081459  1680653699  ...  28122.2 -0.000316   1538    2
1539  20230405   081500    081959  1680653999  ...  28085.8  0.000928   1539    3
1540  20230405   082000    082459  1680654299  ...  28132.1  0.003787   1540    4

[5 rows x 11 columns]
2023-04-05 08:25:01,549:INFO:factorcheck2:main.py:128:handleKline:185239: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}


## /root/FIL/strategy/logic/log.txt ----- -----

2023-04-05 08:00:33,869:DEBUG:logic:main.py:463:getModel:885513: df_s.iloc[-5:,:] :
          date closeTime     open  ...    alpha58   alpha67   alpha72
5770  20230405    052959  28236.4  ...  50.833333  0.519926  0.330581
5771  20230405    055959  28198.2  ...  51.250000  0.522686  0.330969
5772  20230405    062959  28215.6  ...  51.250000  0.524345  0.330335
5773  20230405    065959  28225.9  ...  51.250000  0.515851  0.334365
5774  20230405    072959  28177.7  ...  50.833333  0.503363  0.345063

[5 rows x 33 columns]
0.5397412199630314
acc is : 0.5397412199630314
2023-04-05 08:00:34,016:INFO:logic:main.py:468:getModel:885513: df_pred.iloc[-5:,:] :
     pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
536     0  0.516443  0.483557       1  ...  0.943696   1.0    0.0  1.019689
537     0  0.528282  0.471718       1  ...  0.944043   1.0    0.0  1.020064
538     0  0.520451  0.479549       0  ...  0.942428   1.0    0.0  1.018319
539     0  0.505685  0.494315       0  ...  0.940003   1.0    0.0  1.015699
540     1  0.492009  0.507991       1  ...  0.941675   1.0    0.0  1.017506

[5 rows x 10 columns]
2023-04-05 08:00:34,051:INFO:logic:main.py:478:getModel:885513: df_panel.iloc[-5:,:] :
    pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
45     0  0.514589  0.485411       1  ...  0.943696   1.0    0.0  1.007801
46     0  0.526373  0.473627       1  ...  0.944043   1.0    0.0  1.010739
47     0  0.519549  0.480451       0  ...  0.942428   1.0    0.0  1.012956
48     0  0.505314  0.494686       0  ...  0.940003   1.0    0.0  1.015699
49     1  0.492009  0.507991       1  ...  0.941675   1.0    0.0  1.017506

[5 rows x 10 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': []}


## /root/FIL/strategy/modifiedmom/log.txt ----- -----

623  20230405   075000    075959  1680652799  28115.8  28155.2  0.001401
2023-04-05 08:00:01,965:INFO:modifiedmom:main.py:146:handleKline:185213: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=18824 

self.closeSec=1680653399, self.tradeDate='20230405', self.openTime='080000', self.closeTime='080959', self.symbol='BTCUSDT', self.open='28155.1', self.close='28131.2'
2023-04-05 08:10:01,715:INFO:modifiedmom:main.py:144:handleKline:185213: self.closeSec=1680653399, self.tradeDate='20230405', self.openTime='080000', self.closeTime='080959',self.symbol='BTCUSDT',self.open='28155.1', self.close='28131.2'
127.0.0.1 - - [05/Apr/2023 08:10:01] "POST / HTTP/1.1" 200 -
2023-04-05 08:10:01,729:INFO:modifiedmom:main.py:145:handleKline:185213: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
620  20230405   072000    072959  1680650999  28123.3  28105.2 -0.000644
621  20230405   073000    073959  1680651599  28105.1  28069.1 -0.001284
622  20230405   074000    074959  1680652199  28069.2  28115.8  0.001664
623  20230405   075000    075959  1680652799  28115.8  28155.2  0.001401
624  20230405   080000    080959  1680653399  28155.1  28131.2 -0.000852
2023-04-05 08:10:01,729:INFO:modifiedmom:main.py:146:handleKline:185213: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=18825 

self.closeSec=1680653999, self.tradeDate='20230405', self.openTime='081000', self.closeTime='081959', self.symbol='BTCUSDT', self.open='28131.3', self.close='28148.4'
127.0.0.1 - - [05/Apr/2023 08:20:05] "POST / HTTP/1.1" 200 -
2023-04-05 08:20:08,026:INFO:modifiedmom:main.py:144:handleKline:185213: self.closeSec=1680653999, self.tradeDate='20230405', self.openTime='081000', self.closeTime='081959',self.symbol='BTCUSDT',self.open='28131.3', self.close='28148.4'
2023-04-05 08:20:08,776:INFO:modifiedmom:main.py:145:handleKline:185213: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
621  20230405   073000    073959  1680651599  28105.1  28069.1 -0.001284
622  20230405   074000    074959  1680652199  28069.2  28115.8  0.001664
623  20230405   075000    075959  1680652799  28115.8  28155.2  0.001401
624  20230405   080000    080959  1680653399  28155.1  28131.2 -0.000852
625  20230405   081000    081959  1680653999  28131.3  28148.4  0.000611
2023-04-05 08:20:08,776:INFO:modifiedmom:main.py:146:handleKline:185213: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False}


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

17471  20230405   075000    075959  1680652799  28115.8  28155.2
2023-04-05 08:00:02,020:INFO:pyemd2:main.py:127:handleKline:185189: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}
127.0.0.1 - - [05/Apr/2023 08:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=18825 

self.closeSec=1680653399, self.tradeDate='20230405', self.openTime='080000', self.closeTime='080959', self.symbol='BTCUSDT', self.open='28155.1', self.close='28131.2'
2023-04-05 08:10:01,752:INFO:pyemd2:main.py:125:handleKline:185189: self.closeSec=1680653399, self.tradeDate='20230405', self.openTime='080000', self.closeTime='080959',self.symbol='BTCUSDT',self.open='28155.1', self.close='28131.2'
2023-04-05 08:10:01,764:INFO:pyemd2:main.py:126:handleKline:185189: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17468  20230405   072000    072959  1680650999  28123.3  28105.2
17469  20230405   073000    073959  1680651599  28105.1  28069.1
17470  20230405   074000    074959  1680652199  28069.2  28115.8
17471  20230405   075000    075959  1680652799  28115.8  28155.2
17472  20230405   080000    080959  1680653399  28155.1  28131.2
2023-04-05 08:10:01,764:INFO:pyemd2:main.py:127:handleKline:185189: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=18826 

self.closeSec=1680653999, self.tradeDate='20230405', self.openTime='081000', self.closeTime='081959', self.symbol='BTCUSDT', self.open='28131.3', self.close='28148.4'
127.0.0.1 - - [05/Apr/2023 08:20:05] "POST / HTTP/1.1" 200 -
2023-04-05 08:20:11,067:INFO:pyemd2:main.py:125:handleKline:185189: self.closeSec=1680653999, self.tradeDate='20230405', self.openTime='081000', self.closeTime='081959',self.symbol='BTCUSDT',self.open='28131.3', self.close='28148.4'
2023-04-05 08:20:11,212:INFO:pyemd2:main.py:126:handleKline:185189: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17469  20230405   073000    073959  1680651599  28105.1  28069.1
17470  20230405   074000    074959  1680652199  28069.2  28115.8
17471  20230405   075000    075959  1680652799  28115.8  28155.2
17472  20230405   080000    080959  1680653399  28155.1  28131.2
17473  20230405   081000    081959  1680653999  28131.3  28148.4
2023-04-05 08:20:11,213:INFO:pyemd2:main.py:127:handleKline:185189: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}


## /root/FIL/strategy/similarity/log.txt ----- -----

12143  20230405   075000    075959  1680652799  28115.8  28155.2
2023-04-05 08:00:01,988:INFO:testStrategy:main.py:103:handleKline:185174: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}
127.0.0.1 - - [05/Apr/2023 08:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=18825 

self.closeSec=1680653399, self.tradeDate='20230405', self.openTime='080000', self.closeTime='080959', self.symbol='BTCUSDT', self.open='28155.1', self.close='28131.2'
2023-04-05 08:10:01,753:INFO:testStrategy:main.py:101:handleKline:185174: self.closeSec=1680653399, self.tradeDate='20230405', self.openTime='080000', self.closeTime='080959',self.symbol='BTCUSDT',self.open='28155.1', self.close='28131.2'
2023-04-05 08:10:01,770:INFO:testStrategy:main.py:102:handleKline:185174: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12140  20230405   072000    072959  1680650999  28123.3  28105.2
12141  20230405   073000    073959  1680651599  28105.1  28069.1
12142  20230405   074000    074959  1680652199  28069.2  28115.8
12143  20230405   075000    075959  1680652799  28115.8  28155.2
12144  20230405   080000    080959  1680653399  28155.1  28131.2
2023-04-05 08:10:01,770:INFO:testStrategy:main.py:103:handleKline:185174: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=18826 

self.closeSec=1680653999, self.tradeDate='20230405', self.openTime='081000', self.closeTime='081959', self.symbol='BTCUSDT', self.open='28131.3', self.close='28148.4'
127.0.0.1 - - [05/Apr/2023 08:20:05] "POST / HTTP/1.1" 200 -
2023-04-05 08:20:10,538:INFO:testStrategy:main.py:101:handleKline:185174: self.closeSec=1680653999, self.tradeDate='20230405', self.openTime='081000', self.closeTime='081959',self.symbol='BTCUSDT',self.open='28131.3', self.close='28148.4'
2023-04-05 08:20:10,865:INFO:testStrategy:main.py:102:handleKline:185174: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12141  20230405   073000    073959  1680651599  28105.1  28069.1
12142  20230405   074000    074959  1680652199  28069.2  28115.8
12143  20230405   075000    075959  1680652799  28115.8  28155.2
12144  20230405   080000    080959  1680653399  28155.1  28131.2
12145  20230405   081000    081959  1680653999  28131.3  28148.4
2023-04-05 08:20:10,867:INFO:testStrategy:main.py:103:handleKline:185174: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}


## /root/FIL/strategy/sr_min/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=0, self.total=1000000.0, self.flagDict['side']='', self.tradeCount=0, self.count=33082
self.closeSec=1680653999, self.tradeDate='20230405', self.openTime='081500', self.closeTime='081959', self.symbol='BTCUSDT', self.open=28122.2, self.close=28148.4, self.high=28165.6, self.low=28085.8, self.vol=1319.016, self.amt=37101278.2492 
127.0.0.1 - - [05/Apr/2023 08:20:03] "POST / HTTP/1.1" 200 -
2023-04-05 08:20:07,736:INFO:sr_min:main.py:172:handleKline:449472: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5855  20230405   075500    075959  ...         0.0        0.0       0
5856  20230405   080000    080459  ...         0.0        0.0       0
5857  20230405   080500    080959  ...         0.0        0.0       0
5858  20230405   081000    081459  ...         0.0        0.0       0
5859  20230405   081500    081959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-04-05 08:20:07,786:INFO:sr_min:main.py:175:handleKline:449472: self.closeSec=1680653999, self.tradeDate='20230405', self.openTime='081500', self.closeTime='081959',self.symbol='BTCUSDT',self.open=28122.2, self.close=28148.4, self.high=28165.6, self.low=28085.8, self.vol=1319.016, self.amt=37101278.2492, ukdf['pct'].iloc[-1]=0.000928 , ukdf['amount'].iloc[-1]=37101278.2492, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5859, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': []}
type(curSign)=<class 'int'>, curSign=0, self.sign=0
--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=0, self.total=1000000.0, self.flagDict['side']='', self.tradeCount=0, self.count=33083
self.closeSec=1680654299, self.tradeDate='20230405', self.openTime='082000', self.closeTime='082459', self.symbol='BTCUSDT', self.open=28148.4, self.close=28255.0, self.high=28270.0, self.low=28132.1, self.vol=2870.38, self.amt=80963675.5971 
127.0.0.1 - - [05/Apr/2023 08:25:01] "POST / HTTP/1.1" 200 -
2023-04-05 08:25:01,581:INFO:sr_min:main.py:172:handleKline:449472: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5856  20230405   080000    080459  ...         0.0        0.0       0
5857  20230405   080500    080959  ...         0.0        0.0       0
5858  20230405   081000    081459  ...         0.0        0.0       0
5859  20230405   081500    081959  ...         0.0        0.0       0
5860  20230405   082000    082459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-04-05 08:25:01,582:INFO:sr_min:main.py:175:handleKline:449472: self.closeSec=1680654299, self.tradeDate='20230405', self.openTime='082000', self.closeTime='082459',self.symbol='BTCUSDT',self.open=28148.4, self.close=28255.0, self.high=28270.0, self.low=28132.1, self.vol=2870.38, self.amt=80963675.5971, ukdf['pct'].iloc[-1]=0.003787 , ukdf['amount'].iloc[-1]=80963675.5971, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5860, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': []}
type(curSign)=<class 'int'>, curSign=0, self.sign=0


## /root/FIL/strategy/s_rsrs/log.txt ----- -----

719  20230404   200000    235959  1680623999  ...    719  0.185268 -0.417809     NaN
720  20230405   000000    035959  1680638399  ...    720  0.234090 -0.204340     NaN

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '52.088', 'enterprice': '28398.8', 'countrevence': '0', 'unrealprofit': '11506.2392', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '28177.9', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-9223372036854775808, self.sign=-1
--handleKline--:  version='2.0.0', self.name='s_rsrs', self.symbol='BTCUSDT', interval='4h', intervalSec=14400, wid=25, thd=0.6, self.sign=-1, self.total=1477757.4577056, self.flagDict['side']='sell', self.tradeCount=29, self.count=784
self.closeSec=1680652799, self.tradeDate='20230405', self.openTime='040000', self.closeTime='075959', self.symbol='BTCUSDT', self.open=28171.0, self.close=28155.2, self.high=28300.0, self.low=28061.5, self.vol=40576.232, self.amt=1143864340.3963 
127.0.0.1 - - [05/Apr/2023 08:00:01] "POST / HTTP/1.1" 200 -
2023-04-05 08:00:01,789:INFO:s_rsrs:main.py:141:handleKline:185271: self.closeSec=1680652799, self.tradeDate='20230405', self.openTime='040000', self.closeTime='075959',self.symbol='BTCUSDT',self.open=28171.0, self.close=28155.2, self.high=28300.0, self.low=28061.5, self.vol=40576.232, self.amt=1143864340.3963 
2023-04-05 08:00:01,843:INFO:s_rsrs:main.py:142:handleKline:185271: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime  ...         vol           amt       pct
717  20230404   120000    155959  ...   58199.402  1.627344e+09  0.006088
718  20230404   160000    195959  ...  106225.317  2.997957e+09  0.009331
719  20230404   200000    235959  ...  113740.253  3.202796e+09 -0.009298
720  20230405   000000    035959  ...   56580.848  1.590656e+09  0.005690
721  20230405   040000    075959  ...   40576.232  1.143864e+09 -0.000564

[5 rows x 11 columns]
2023-04-05 08:00:04,633:INFO:s_rsrs:main.py:151:handleKline:185271: df_s.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec  ...  index      beta    zscore  signal
717  20230404   120000    155959  1680595199  ...    717  0.198068 -0.405388     NaN
718  20230404   160000    195959  1680609599  ...    718  0.209935 -0.342453     NaN
719  20230404   200000    235959  1680623999  ...    719  0.185268 -0.417809     NaN
720  20230405   000000    035959  1680638399  ...    720  0.234090 -0.204340     NaN
721  20230405   040000    075959  1680652799  ...    721  0.225672 -0.217109     NaN

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '52.088', 'enterprice': '28398.8', 'countrevence': '0', 'unrealprofit': '12688.6368', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '28155.2', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-9223372036854775808, self.sign=-1


