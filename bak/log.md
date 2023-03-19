# 20230319 08:26:01

## /root/FIL/strategy/amihud/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=993672.4896432, self.flagDict['side']='sell', self.tradeCount=2, self.count=32188
self.closeSec=1679185199, self.tradeDate='20230319', self.openTime='081500', self.closeTime='081959', self.symbol='BTCUSDT', self.open=27053.0, self.close=26998.6, self.high=27053.0, self.low=26980.1, self.vol=2374.072, self.amt=64128792.4291 
127.0.0.1 - - [19/Mar/2023 08:20:01] "POST / HTTP/1.1" 200 -
2023-03-19 08:20:02,010:INFO:amihud:main.py:172:handleKline:200676: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5855  20230319   075500    075959  ...         0.0        0.0       0
5856  20230319   080000    080459  ...         0.0        0.0       0
5857  20230319   080500    080959  ...         0.0        0.0       0
5858  20230319   081000    081459  ...         0.0        0.0       0
5859  20230319   081500    081959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-03-19 08:20:02,020:INFO:amihud:main.py:175:handleKline:200676: self.closeSec=1679185199, self.tradeDate='20230319', self.openTime='081500', self.closeTime='081959',self.symbol='BTCUSDT',self.open=27053.0, self.close=26998.6, self.high=27053.0, self.low=26980.1, self.vol=2374.072, self.amt=64128792.4291, ukdf['pct'].iloc[-1]=-0.002011 , ukdf['amount'].iloc[-1]=64128792.4291, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5859, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '60.176', 'enterprice': '16529.3', 'countrevence': '0', 'unrealprofit': '-630155.50862960176', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '27001.17431251', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1
--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=993672.4896432, self.flagDict['side']='sell', self.tradeCount=2, self.count=32189
self.closeSec=1679185499, self.tradeDate='20230319', self.openTime='082000', self.closeTime='082459', self.symbol='BTCUSDT', self.open=26998.7, self.close=27029.3, self.high=27043.2, self.low=26986.4, self.vol=1156.721, self.amt=31245323.0745 
127.0.0.1 - - [19/Mar/2023 08:25:01] "POST / HTTP/1.1" 200 -
2023-03-19 08:25:01,612:INFO:amihud:main.py:172:handleKline:200676: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5856  20230319   080000    080459  ...         0.0        0.0       0
5857  20230319   080500    080959  ...         0.0        0.0       0
5858  20230319   081000    081459  ...         0.0        0.0       0
5859  20230319   081500    081959  ...         0.0        0.0       0
5860  20230319   082000    082459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-03-19 08:25:01,613:INFO:amihud:main.py:175:handleKline:200676: self.closeSec=1679185499, self.tradeDate='20230319', self.openTime='082000', self.closeTime='082459',self.symbol='BTCUSDT',self.open=26998.7, self.close=27029.3, self.high=27043.2, self.low=26986.4, self.vol=1156.721, self.amt=31245323.0745, ukdf['pct'].iloc[-1]=0.001137 , ukdf['amount'].iloc[-1]=31245323.0745, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5860, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '60.176', 'enterprice': '16529.3', 'countrevence': '0', 'unrealprofit': '-632059.0328301256', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '27032.80692685', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1


## /root/FIL/strategy/factorcheck/log.txt ----- -----


self.closeSec=1679185199, self.tradeDate='20230319', self.openTime='081500', self.closeTime='081959', self.symbol='BTCUSDT', self.open=27053.0, self.close=26998.6, self.high=27053.0, self.low=26980.1 
127.0.0.1 - - [19/Mar/2023 08:20:01] "POST / HTTP/1.1" 200 -
2023-03-19 08:20:01,744:INFO:factorcheck2:main.py:126:handleKline:185239: self.closeSec=1679185199, self.tradeDate='20230319', self.openTime='081500', self.closeTime='081959',self.symbol='BTCUSDT',self.open=27053.0, self.close=26998.6, self.high=27053.0, self.low=26980.1   
2023-03-19 08:20:01,829:INFO:factorcheck2:main.py:127:handleKline:185239: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1535  20230319   075500    075959  1679183999  ...  26847.2 -0.000568   1535    5
1536  20230319   080000    080459  1679184299  ...  26901.6  0.001884   1536    0
1537  20230319   080500    080959  1679184599  ...  26908.9  0.001569   1537    1
1538  20230319   081000    081459  1679184899  ...  26990.5  0.001963   1538    2
1539  20230319   081500    081959  1679185199  ...  26980.1 -0.002011   1539    3

[5 rows x 11 columns]
2023-03-19 08:20:01,830:INFO:factorcheck2:main.py:128:handleKline:185239: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=76, self.factor=0.37898350291622007, self.count=32755 

self.closeSec=1679185499, self.tradeDate='20230319', self.openTime='082000', self.closeTime='082459', self.symbol='BTCUSDT', self.open=26998.7, self.close=27029.3, self.high=27043.2, self.low=26986.4 
127.0.0.1 - - [19/Mar/2023 08:25:01] "POST / HTTP/1.1" 200 -
2023-03-19 08:25:01,490:INFO:factorcheck2:main.py:126:handleKline:185239: self.closeSec=1679185499, self.tradeDate='20230319', self.openTime='082000', self.closeTime='082459',self.symbol='BTCUSDT',self.open=26998.7, self.close=27029.3, self.high=27043.2, self.low=26986.4   
2023-03-19 08:25:01,524:INFO:factorcheck2:main.py:127:handleKline:185239: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1536  20230319   080000    080459  1679184299  ...  26901.6  0.001884   1536    0
1537  20230319   080500    080959  1679184599  ...  26908.9  0.001569   1537    1
1538  20230319   081000    081459  1679184899  ...  26990.5  0.001963   1538    2
1539  20230319   081500    081959  1679185199  ...  26980.1 -0.002011   1539    3
1540  20230319   082000    082459  1679185499  ...  26986.4  0.001137   1540    4

[5 rows x 11 columns]
2023-03-19 08:25:01,524:INFO:factorcheck2:main.py:128:handleKline:185239: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}


## /root/FIL/strategy/logic/log.txt ----- -----

2023-03-19 08:00:37,701:DEBUG:logic:main.py:463:getModel:885513: df_s.iloc[-5:,:] :
          date closeTime     open  ...    alpha58   alpha67   alpha72
5770  20230319    052959  27313.0  ...  49.166667  0.566542  0.312102
5771  20230319    055959  27295.6  ...  48.750000  0.553869  0.319711
5772  20230319    062959  27188.3  ...  48.333333  0.550426  0.328590
5773  20230319    065959  27158.9  ...  48.333333  0.521512  0.352412
5774  20230319    072959  26902.0  ...  48.333333  0.516311  0.377566

[5 rows x 33 columns]
0.5582255083179297
acc is : 0.5582255083179297
2023-03-19 08:00:37,897:INFO:logic:main.py:468:getModel:885513: df_pred.iloc[-5:,:] :
     pred    prob_0    prob_1  actual  ...       nav  sign   cost_        bm
536     1  0.486767  0.513233       0  ...  1.106096   1.0  0.0000  1.218632
537     1  0.442817  0.557183       0  ...  1.105522  -1.0 -0.0016  1.217315
538     1  0.471506  0.528494       0  ...  1.115983  -1.0  0.0000  1.205795
539     1  0.378830  0.621170       0  ...  1.117987  -1.0  0.0000  1.203631
540     1  0.439358  0.560642       1  ...  1.115764  -1.0  0.0000  1.206024

[5 rows x 10 columns]
2023-03-19 08:00:37,935:INFO:logic:main.py:478:getModel:885513: df_panel.iloc[-5:,:] :
    pred    prob_0    prob_1  actual  ...       nav  sign   cost_        bm
45     1  0.486630  0.513370       0  ...  1.115761   1.0  0.0000  1.218796
46     1  0.443579  0.556421       0  ...  1.105522  -1.0 -0.0016  1.222069
47     1  0.471244  0.528756       0  ...  1.115983  -1.0  0.0000  1.210287
48     1  0.378830  0.621170       0  ...  1.117987  -1.0  0.0000  1.203631
49     1  0.439358  0.560642       1  ...  1.115764  -1.0  0.0000  1.206024

[5 rows x 10 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': []}


## /root/FIL/strategy/modifiedmom/log.txt ----- -----

623  20230319   075000    075959  1679183999  26884.5    26907  0.000923
2023-03-19 08:00:02,244:INFO:modifiedmom:main.py:146:handleKline:185213: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False}
127.0.0.1 - - [19/Mar/2023 08:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=16376 

self.closeSec=1679184599, self.tradeDate='20230319', self.openTime='080000', self.closeTime='080959', self.symbol='BTCUSDT', self.open='26907', self.close='27000'
2023-03-19 08:10:01,627:INFO:modifiedmom:main.py:144:handleKline:185213: self.closeSec=1679184599, self.tradeDate='20230319', self.openTime='080000', self.closeTime='080959',self.symbol='BTCUSDT',self.open='26907', self.close='27000'
2023-03-19 08:10:01,672:INFO:modifiedmom:main.py:145:handleKline:185213: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
620  20230319   072000    072959  1679182199  27033.8  26853.6 -0.006666
621  20230319   073000    073959  1679182799  26853.5  26950.8  0.003620
622  20230319   074000    074959  1679183399  26950.9  26882.2 -0.002545
623  20230319   075000    075959  1679183999  26884.5    26907  0.000923
624  20230319   080000    080959  1679184599    26907    27000  0.003456
2023-03-19 08:10:01,673:INFO:modifiedmom:main.py:146:handleKline:185213: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=16377 

self.closeSec=1679185199, self.tradeDate='20230319', self.openTime='081000', self.closeTime='081959', self.symbol='BTCUSDT', self.open='27000.1', self.close='26998.6'
127.0.0.1 - - [19/Mar/2023 08:20:01] "POST / HTTP/1.1" 200 -
2023-03-19 08:20:02,725:INFO:modifiedmom:main.py:144:handleKline:185213: self.closeSec=1679185199, self.tradeDate='20230319', self.openTime='081000', self.closeTime='081959',self.symbol='BTCUSDT',self.open='27000.1', self.close='26998.6'
2023-03-19 08:20:03,000:INFO:modifiedmom:main.py:145:handleKline:185213: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
621  20230319   073000    073959  1679182799  26853.5  26950.8  0.003620
622  20230319   074000    074959  1679183399  26950.9  26882.2 -0.002545
623  20230319   075000    075959  1679183999  26884.5    26907  0.000923
624  20230319   080000    080959  1679184599    26907    27000  0.003456
625  20230319   081000    081959  1679185199  27000.1  26998.6 -0.000052
2023-03-19 08:20:03,001:INFO:modifiedmom:main.py:146:handleKline:185213: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False}


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

17471  20230319   075000    075959  1679183999  26884.5    26907
2023-03-19 08:00:02,270:INFO:pyemd2:main.py:127:handleKline:185189: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=16377 

self.closeSec=1679184599, self.tradeDate='20230319', self.openTime='080000', self.closeTime='080959', self.symbol='BTCUSDT', self.open='26907', self.close='27000'
2023-03-19 08:10:01,615:INFO:pyemd2:main.py:125:handleKline:185189: self.closeSec=1679184599, self.tradeDate='20230319', self.openTime='080000', self.closeTime='080959',self.symbol='BTCUSDT',self.open='26907', self.close='27000'
127.0.0.1 - - [19/Mar/2023 08:10:01] "POST / HTTP/1.1" 200 -
2023-03-19 08:10:01,651:INFO:pyemd2:main.py:126:handleKline:185189: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17468  20230319   072000    072959  1679182199  27033.8  26853.6
17469  20230319   073000    073959  1679182799  26853.5  26950.8
17470  20230319   074000    074959  1679183399  26950.9  26882.2
17471  20230319   075000    075959  1679183999  26884.5    26907
17472  20230319   080000    080959  1679184599    26907    27000
2023-03-19 08:10:01,651:INFO:pyemd2:main.py:127:handleKline:185189: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=16378 

self.closeSec=1679185199, self.tradeDate='20230319', self.openTime='081000', self.closeTime='081959', self.symbol='BTCUSDT', self.open='27000.1', self.close='26998.6'
127.0.0.1 - - [19/Mar/2023 08:20:01] "POST / HTTP/1.1" 200 -
2023-03-19 08:20:03,900:INFO:pyemd2:main.py:125:handleKline:185189: self.closeSec=1679185199, self.tradeDate='20230319', self.openTime='081000', self.closeTime='081959',self.symbol='BTCUSDT',self.open='27000.1', self.close='26998.6'
2023-03-19 08:20:04,022:INFO:pyemd2:main.py:126:handleKline:185189: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17469  20230319   073000    073959  1679182799  26853.5  26950.8
17470  20230319   074000    074959  1679183399  26950.9  26882.2
17471  20230319   075000    075959  1679183999  26884.5    26907
17472  20230319   080000    080959  1679184599    26907    27000
17473  20230319   081000    081959  1679185199  27000.1  26998.6
2023-03-19 08:20:04,023:INFO:pyemd2:main.py:127:handleKline:185189: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}


## /root/FIL/strategy/similarity/log.txt ----- -----

12143  20230319   075000    075959  1679183999  26884.5    26907
2023-03-19 08:00:02,245:INFO:testStrategy:main.py:103:handleKline:185174: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': True, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=16377 

self.closeSec=1679184599, self.tradeDate='20230319', self.openTime='080000', self.closeTime='080959', self.symbol='BTCUSDT', self.open='26907', self.close='27000'
2023-03-19 08:10:01,598:INFO:testStrategy:main.py:101:handleKline:185174: self.closeSec=1679184599, self.tradeDate='20230319', self.openTime='080000', self.closeTime='080959',self.symbol='BTCUSDT',self.open='26907', self.close='27000'
127.0.0.1 - - [19/Mar/2023 08:10:01] "POST / HTTP/1.1" 200 -
2023-03-19 08:10:01,637:INFO:testStrategy:main.py:102:handleKline:185174: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12140  20230319   072000    072959  1679182199  27033.8  26853.6
12141  20230319   073000    073959  1679182799  26853.5  26950.8
12142  20230319   074000    074959  1679183399  26950.9  26882.2
12143  20230319   075000    075959  1679183999  26884.5    26907
12144  20230319   080000    080959  1679184599    26907    27000
2023-03-19 08:10:01,640:INFO:testStrategy:main.py:103:handleKline:185174: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': True, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=16378 

self.closeSec=1679185199, self.tradeDate='20230319', self.openTime='081000', self.closeTime='081959', self.symbol='BTCUSDT', self.open='27000.1', self.close='26998.6'
127.0.0.1 - - [19/Mar/2023 08:20:01] "POST / HTTP/1.1" 200 -
2023-03-19 08:20:03,520:INFO:testStrategy:main.py:101:handleKline:185174: self.closeSec=1679185199, self.tradeDate='20230319', self.openTime='081000', self.closeTime='081959',self.symbol='BTCUSDT',self.open='27000.1', self.close='26998.6'
2023-03-19 08:20:03,770:INFO:testStrategy:main.py:102:handleKline:185174: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12141  20230319   073000    073959  1679182799  26853.5  26950.8
12142  20230319   074000    074959  1679183399  26950.9  26882.2
12143  20230319   075000    075959  1679183999  26884.5    26907
12144  20230319   080000    080959  1679184599    26907    27000
12145  20230319   081000    081959  1679185199  27000.1  26998.6
2023-03-19 08:20:03,772:INFO:testStrategy:main.py:103:handleKline:185174: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': True, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}


## /root/FIL/strategy/sr_min/log.txt ----- -----

127.0.0.1 - - [19/Mar/2023 08:20:01] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=0, self.total=1000000.0, self.flagDict['side']='', self.tradeCount=0, self.count=28186
self.closeSec=1679185199, self.tradeDate='20230319', self.openTime='081500', self.closeTime='081959', self.symbol='BTCUSDT', self.open=27053.0, self.close=26998.6, self.high=27053.0, self.low=26980.1, self.vol=2374.072, self.amt=64128792.4291 
2023-03-19 08:20:01,581:INFO:sr_min:main.py:172:handleKline:449472: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5855  20230319   075500    075959  ...         0.0        0.0       0
5856  20230319   080000    080459  ...         0.0        0.0       0
5857  20230319   080500    080959  ...         0.0        0.0       0
5858  20230319   081000    081459  ...         0.0        0.0       0
5859  20230319   081500    081959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-03-19 08:20:01,583:INFO:sr_min:main.py:175:handleKline:449472: self.closeSec=1679185199, self.tradeDate='20230319', self.openTime='081500', self.closeTime='081959',self.symbol='BTCUSDT',self.open=27053.0, self.close=26998.6, self.high=27053.0, self.low=26980.1, self.vol=2374.072, self.amt=64128792.4291, ukdf['pct'].iloc[-1]=-0.002011 , ukdf['amount'].iloc[-1]=64128792.4291, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5859, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': []}
type(curSign)=<class 'int'>, curSign=0, self.sign=0
127.0.0.1 - - [19/Mar/2023 08:25:01] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=0, self.total=1000000.0, self.flagDict['side']='', self.tradeCount=0, self.count=28187
self.closeSec=1679185499, self.tradeDate='20230319', self.openTime='082000', self.closeTime='082459', self.symbol='BTCUSDT', self.open=26998.7, self.close=27029.3, self.high=27043.2, self.low=26986.4, self.vol=1156.721, self.amt=31245323.0745 
2023-03-19 08:25:01,543:INFO:sr_min:main.py:172:handleKline:449472: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5856  20230319   080000    080459  ...         0.0        0.0       0
5857  20230319   080500    080959  ...         0.0        0.0       0
5858  20230319   081000    081459  ...         0.0        0.0       0
5859  20230319   081500    081959  ...         0.0        0.0       0
5860  20230319   082000    082459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-03-19 08:25:01,544:INFO:sr_min:main.py:175:handleKline:449472: self.closeSec=1679185499, self.tradeDate='20230319', self.openTime='082000', self.closeTime='082459',self.symbol='BTCUSDT',self.open=26998.7, self.close=27029.3, self.high=27043.2, self.low=26986.4, self.vol=1156.721, self.amt=31245323.0745, ukdf['pct'].iloc[-1]=0.001137 , ukdf['amount'].iloc[-1]=31245323.0745, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5860, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': []}
type(curSign)=<class 'int'>, curSign=0, self.sign=0


## /root/FIL/strategy/s_rsrs/log.txt ----- -----

719  20230318   200000    235959  1679155199  ...    719  0.763519  0.358986     NaN
720  20230319   000000    035959  1679169599  ...    720  0.887375  0.714094     1.0

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '53.795', 'enterprice': '27400', 'countrevence': '0', 'unrealprofit': '-4166.22309147135', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '27322.55371147', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=1, self.sign=1
127.0.0.1 - - [19/Mar/2023 08:00:01] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='s_rsrs', self.symbol='BTCUSDT', interval='4h', intervalSec=14400, wid=25, thd=0.6, self.sign=1, self.total=1472509.017, self.flagDict['side']='buy', self.tradeCount=26, self.count=682
self.closeSec=1679183999, self.tradeDate='20230319', self.openTime='040000', self.closeTime='075959', self.symbol='BTCUSDT', self.open=27322.8, self.close=26907.0, self.high=27453.3, self.low=26790.0, self.vol=95750.566, self.amt=2590727123.97673 
2023-03-19 08:00:01,932:INFO:s_rsrs:main.py:141:handleKline:185271: self.closeSec=1679183999, self.tradeDate='20230319', self.openTime='040000', self.closeTime='075959',self.symbol='BTCUSDT',self.open=27322.8, self.close=26907.0, self.high=27453.3, self.low=26790.0, self.vol=95750.566, self.amt=2590727123.97673 
2023-03-19 08:00:01,999:INFO:s_rsrs:main.py:142:handleKline:185271: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime  ...         vol           amt       pct
717  20230318   120000    155959  ...   67348.417  1.847161e+09  0.002147
718  20230318   160000    195959  ...   87883.227  2.399320e+09  0.003221
719  20230318   200000    235959  ...  147089.406  4.027337e+09 -0.008058
720  20230319   000000    035959  ...  196552.142  5.335799e+09  0.003821
721  20230319   040000    075959  ...   95750.566  2.590727e+09 -0.015222

[5 rows x 11 columns]
2023-03-19 08:00:04,941:INFO:s_rsrs:main.py:151:handleKline:185271: df_s.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec  ...  index      beta    zscore  signal
717  20230318   120000    155959  1679126399  ...    717  0.790757  0.466857     NaN
718  20230318   160000    195959  1679140799  ...    718  0.763908  0.372658     NaN
719  20230318   200000    235959  1679155199  ...    719  0.763519  0.358986     NaN
720  20230319   000000    035959  1679169599  ...    720  0.887375  0.714094     1.0
721  20230319   040000    075959  1679183999  ...    721  0.986827  0.991055     1.0

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '53.795', 'enterprice': '27400', 'countrevence': '0', 'unrealprofit': '-26515.5555', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '26907.1', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=1, self.sign=1


