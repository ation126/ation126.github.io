# 20230602 08:26:02

## /root/FIL/strategy/amihud/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=373746.4768026, self.flagDict['side']='sell', self.tradeCount=2, self.count=5440
self.closeSec=1685665199, self.tradeDate='20230602', self.openTime='081500', self.closeTime='081959', self.symbol='BTCUSDT', self.open=26787.1, self.close=26773.6, self.high=26801.7, self.low=26750.0, self.vol=1625.472, self.amt=43521505.7451 
127.0.0.1 - - [02/Jun/2023 08:20:01] "POST / HTTP/1.1" 200 -
2023-06-02 08:20:07,415:INFO:amihud:main.py:172:handleKline:2219019: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5855  20230602   075500    075959  ...         0.0        0.0       0
5856  20230602   080000    080459  ...         0.0        0.0       0
5857  20230602   080500    080959  ...         0.0        0.0       0
5858  20230602   081000    081459  ...         0.0        0.0       0
5859  20230602   081500    081959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-06-02 08:20:07,435:INFO:amihud:main.py:175:handleKline:2219019: self.closeSec=1685665199, self.tradeDate='20230602', self.openTime='081500', self.closeTime='081959',self.symbol='BTCUSDT',self.open=26787.1, self.close=26773.6, self.high=26801.7, self.low=26750.0, self.vol=1625.472, self.amt=43521505.7451, ukdf['pct'].iloc[-1]=-0.000508 , ukdf['amount'].iloc[-1]=43521505.7451, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5859, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '13.926', 'enterprice': '26864.9', 'countrevence': '0', 'unrealprofit': '1274.229', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '26773.4', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1
127.0.0.1 - - [02/Jun/2023 08:25:00] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=373746.4768026, self.flagDict['side']='sell', self.tradeCount=2, self.count=5441
self.closeSec=1685665499, self.tradeDate='20230602', self.openTime='082000', self.closeTime='082459', self.symbol='BTCUSDT', self.open=26773.5, self.close=26727.1, self.high=26780.2, self.low=26721.9, self.vol=2260.896, self.amt=60483965.7344 
2023-06-02 08:25:00,775:INFO:amihud:main.py:172:handleKline:2219019: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5856  20230602   080000    080459  ...         0.0        0.0       0
5857  20230602   080500    080959  ...         0.0        0.0       0
5858  20230602   081000    081459  ...         0.0        0.0       0
5859  20230602   081500    081959  ...         0.0        0.0       0
5860  20230602   082000    082459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-06-02 08:25:00,776:INFO:amihud:main.py:175:handleKline:2219019: self.closeSec=1685665499, self.tradeDate='20230602', self.openTime='082000', self.closeTime='082459',self.symbol='BTCUSDT',self.open=26773.5, self.close=26727.1, self.high=26780.2, self.low=26721.9, self.vol=2260.896, self.amt=60483965.7344, ukdf['pct'].iloc[-1]=-0.001737 , ukdf['amount'].iloc[-1]=60483965.7344, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5860, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '13.926', 'enterprice': '26864.9', 'countrevence': '0', 'unrealprofit': '1869.83385917262', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '26730.63072963', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1


## /root/FIL/strategy/factorcheck/log.txt ----- -----


self.closeSec=1685665199, self.tradeDate='20230602', self.openTime='081500', self.closeTime='081959', self.symbol='BTCUSDT', self.open=26787.1, self.close=26773.6, self.high=26801.7, self.low=26750.0 
127.0.0.1 - - [02/Jun/2023 08:20:01] "POST / HTTP/1.1" 200 -
2023-06-02 08:20:04,825:INFO:factorcheck2:main.py:126:handleKline:2218005: self.closeSec=1685665199, self.tradeDate='20230602', self.openTime='081500', self.closeTime='081959',self.symbol='BTCUSDT',self.open=26787.1, self.close=26773.6, self.high=26801.7, self.low=26750.0   
2023-06-02 08:20:06,245:INFO:factorcheck2:main.py:127:handleKline:2218005: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1535  20230602   075500    075959  1685663999  ...  26785.2  0.000478   1535    5
1536  20230602   080000    080459  1685664299  ...  26782.6 -0.000011   1536    0
1537  20230602   080500    080959  1685664599  ...  26779.6 -0.000623   1537    1
1538  20230602   081000    081459  1685664899  ...  26786.7 -0.000037   1538    2
1539  20230602   081500    081959  1685665199  ...  26750.0 -0.000508   1539    3

[5 rows x 11 columns]
2023-06-02 08:20:06,255:INFO:factorcheck2:main.py:128:handleKline:2218005: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': False, 'isOpen': True, 'isClose': False, 'isTrig': True}

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.6513779371795801, self.count=5443 

self.closeSec=1685665499, self.tradeDate='20230602', self.openTime='082000', self.closeTime='082459', self.symbol='BTCUSDT', self.open=26773.5, self.close=26727.1, self.high=26780.2, self.low=26721.9 
127.0.0.1 - - [02/Jun/2023 08:25:00] "POST / HTTP/1.1" 200 -
2023-06-02 08:25:00,754:INFO:factorcheck2:main.py:126:handleKline:2218005: self.closeSec=1685665499, self.tradeDate='20230602', self.openTime='082000', self.closeTime='082459',self.symbol='BTCUSDT',self.open=26773.5, self.close=26727.1, self.high=26780.2, self.low=26721.9   
2023-06-02 08:25:00,778:INFO:factorcheck2:main.py:127:handleKline:2218005: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1536  20230602   080000    080459  1685664299  ...  26782.6 -0.000011   1536    0
1537  20230602   080500    080959  1685664599  ...  26779.6 -0.000623   1537    1
1538  20230602   081000    081459  1685664899  ...  26786.7 -0.000037   1538    2
1539  20230602   081500    081959  1685665199  ...  26750.0 -0.000508   1539    3
1540  20230602   082000    082459  1685665499  ...  26721.9 -0.001737   1540    4

[5 rows x 11 columns]
2023-06-02 08:25:00,779:INFO:factorcheck2:main.py:128:handleKline:2218005: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': False, 'isOpen': True, 'isClose': False, 'isTrig': True}


## /root/FIL/strategy/logic/log.txt ----- -----

2023-06-02 08:00:35,443:DEBUG:logic:main.py:463:getModel:2218526: df_s.iloc[-5:,:] :
          date closeTime     open  ...    alpha58   alpha67   alpha72
5770  20230602    052959  26850.5  ...  50.000000  0.467890  0.597831
5771  20230602    055959  26931.5  ...  49.583333  0.458309  0.592297
5772  20230602    062959  26881.4  ...  49.166667  0.456899  0.587983
5773  20230602    065959  26874.0  ...  48.750000  0.456009  0.584486
5774  20230602    072959  26869.5  ...  48.333333  0.438376  0.594902

[5 rows x 33 columns]
0.5286506469500925
acc is : 0.5286506469500925
2023-06-02 08:00:35,613:INFO:logic:main.py:468:getModel:2218526: df_pred.iloc[-5:,:] :
     pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
536     0  0.509745  0.490255       0  ...  1.022820   1.0    0.0  1.000447
537     1  0.491173  0.508827       0  ...  1.022539   1.0    0.0  1.000171
538     1  0.499626  0.500374       0  ...  1.022363   1.0    0.0  1.000000
539     0  0.502201  0.497799       0  ...  1.018821   1.0    0.0  0.996535
540     1  0.476956  0.523044       1  ...  1.019925   1.0    0.0  0.997614

[5 rows x 10 columns]
2023-06-02 08:00:35,641:INFO:logic:main.py:478:getModel:2218526: df_panel.iloc[-5:,:] :
    pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
45     0  0.509972  0.490028       0  ...  1.022820   1.0    0.0  0.999866
46     1  0.491247  0.508753       0  ...  1.022539   1.0    0.0  1.000398
47     1  0.499529  0.500471       0  ...  1.022363   1.0    0.0  0.999829
48     0  0.502341  0.497659       0  ...  1.018821   1.0    0.0  0.996535
49     1  0.476956  0.523044       1  ...  1.019925   1.0    0.0  0.997614

[5 rows x 10 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '27.623', 'enterprice': '26988.6', 'countrevence': '0', 'unrealprofit': '-5268.73224334745', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '26797.86285185', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}


## /root/FIL/strategy/modifiedmom/log.txt ----- -----

623  20230602   075000    075959  1685663999  26787.8  26805.3  0.000653
2023-06-02 08:00:02,297:INFO:modifiedmom:main.py:146:handleKline:2218259: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False}
127.0.0.1 - - [02/Jun/2023 08:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=2720 

self.closeSec=1685664599, self.tradeDate='20230602', self.openTime='080000', self.closeTime='080959', self.symbol='BTCUSDT', self.open='26805.3', self.close='26788.2'
2023-06-02 08:10:01,118:INFO:modifiedmom:main.py:144:handleKline:2218259: self.closeSec=1685664599, self.tradeDate='20230602', self.openTime='080000', self.closeTime='080959',self.symbol='BTCUSDT',self.open='26805.3', self.close='26788.2'
2023-06-02 08:10:01,181:INFO:modifiedmom:main.py:145:handleKline:2218259: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
620  20230602   072000    072959  1685662199  26834.4  26776.3 -0.002169
621  20230602   073000    073959  1685662799  26776.3  26804.2  0.001042
622  20230602   074000    074959  1685663399  26804.3  26787.8 -0.000612
623  20230602   075000    075959  1685663999  26787.8  26805.3  0.000653
624  20230602   080000    080959  1685664599  26805.3  26788.2 -0.000638
2023-06-02 08:10:01,181:INFO:modifiedmom:main.py:146:handleKline:2218259: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=2721 

self.closeSec=1685665199, self.tradeDate='20230602', self.openTime='081000', self.closeTime='081959', self.symbol='BTCUSDT', self.open='26788.3', self.close='26773.6'
127.0.0.1 - - [02/Jun/2023 08:20:04] "POST / HTTP/1.1" 200 -
2023-06-02 08:20:07,265:INFO:modifiedmom:main.py:144:handleKline:2218259: self.closeSec=1685665199, self.tradeDate='20230602', self.openTime='081000', self.closeTime='081959',self.symbol='BTCUSDT',self.open='26788.3', self.close='26773.6'
2023-06-02 08:20:08,030:INFO:modifiedmom:main.py:145:handleKline:2218259: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
621  20230602   073000    073959  1685662799  26776.3  26804.2  0.001042
622  20230602   074000    074959  1685663399  26804.3  26787.8 -0.000612
623  20230602   075000    075959  1685663999  26787.8  26805.3  0.000653
624  20230602   080000    080959  1685664599  26805.3  26788.2 -0.000638
625  20230602   081000    081959  1685665199  26788.3  26773.6 -0.000545
2023-06-02 08:20:08,030:INFO:modifiedmom:main.py:146:handleKline:2218259: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False}


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

17471  20230602   075000    075959  1685663999  26787.8  26805.3
2023-06-02 08:00:02,284:INFO:pyemd2:main.py:127:handleKline:2217508: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=2723 

self.closeSec=1685664599, self.tradeDate='20230602', self.openTime='080000', self.closeTime='080959', self.symbol='BTCUSDT', self.open='26805.3', self.close='26788.2'
127.0.0.1 - - [02/Jun/2023 08:10:01] "POST / HTTP/1.1" 200 -
2023-06-02 08:10:01,151:INFO:pyemd2:main.py:125:handleKline:2217508: self.closeSec=1685664599, self.tradeDate='20230602', self.openTime='080000', self.closeTime='080959',self.symbol='BTCUSDT',self.open='26805.3', self.close='26788.2'
2023-06-02 08:10:01,189:INFO:pyemd2:main.py:126:handleKline:2217508: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17468  20230602   072000    072959  1685662199  26834.4  26776.3
17469  20230602   073000    073959  1685662799  26776.3  26804.2
17470  20230602   074000    074959  1685663399  26804.3  26787.8
17471  20230602   075000    075959  1685663999  26787.8  26805.3
17472  20230602   080000    080959  1685664599  26805.3  26788.2
2023-06-02 08:10:01,189:INFO:pyemd2:main.py:127:handleKline:2217508: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=2724 

self.closeSec=1685665199, self.tradeDate='20230602', self.openTime='081000', self.closeTime='081959', self.symbol='BTCUSDT', self.open='26788.3', self.close='26773.6'
127.0.0.1 - - [02/Jun/2023 08:20:04] "POST / HTTP/1.1" 200 -
2023-06-02 08:20:08,959:INFO:pyemd2:main.py:125:handleKline:2217508: self.closeSec=1685665199, self.tradeDate='20230602', self.openTime='081000', self.closeTime='081959',self.symbol='BTCUSDT',self.open='26788.3', self.close='26773.6'
2023-06-02 08:20:09,102:INFO:pyemd2:main.py:126:handleKline:2217508: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17469  20230602   073000    073959  1685662799  26776.3  26804.2
17470  20230602   074000    074959  1685663399  26804.3  26787.8
17471  20230602   075000    075959  1685663999  26787.8  26805.3
17472  20230602   080000    080959  1685664599  26805.3  26788.2
17473  20230602   081000    081959  1685665199  26788.3  26773.6
2023-06-02 08:20:09,102:INFO:pyemd2:main.py:127:handleKline:2217508: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}


## /root/FIL/strategy/similarity/log.txt ----- -----

12143  20230602   075000    075959  1685663999  26787.8  26805.3
2023-06-02 08:00:02,344:INFO:testStrategy:main.py:103:handleKline:2217133: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=2723 

self.closeSec=1685664599, self.tradeDate='20230602', self.openTime='080000', self.closeTime='080959', self.symbol='BTCUSDT', self.open='26805.3', self.close='26788.2'
2023-06-02 08:10:01,117:INFO:testStrategy:main.py:101:handleKline:2217133: self.closeSec=1685664599, self.tradeDate='20230602', self.openTime='080000', self.closeTime='080959',self.symbol='BTCUSDT',self.open='26805.3', self.close='26788.2'
127.0.0.1 - - [02/Jun/2023 08:10:01] "POST / HTTP/1.1" 200 -
2023-06-02 08:10:01,128:INFO:testStrategy:main.py:102:handleKline:2217133: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12140  20230602   072000    072959  1685662199  26834.4  26776.3
12141  20230602   073000    073959  1685662799  26776.3  26804.2
12142  20230602   074000    074959  1685663399  26804.3  26787.8
12143  20230602   075000    075959  1685663999  26787.8  26805.3
12144  20230602   080000    080959  1685664599  26805.3  26788.2
2023-06-02 08:10:01,129:INFO:testStrategy:main.py:103:handleKline:2217133: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=2724 

self.closeSec=1685665199, self.tradeDate='20230602', self.openTime='081000', self.closeTime='081959', self.symbol='BTCUSDT', self.open='26788.3', self.close='26773.6'
127.0.0.1 - - [02/Jun/2023 08:20:04] "POST / HTTP/1.1" 200 -
2023-06-02 08:20:08,722:INFO:testStrategy:main.py:101:handleKline:2217133: self.closeSec=1685665199, self.tradeDate='20230602', self.openTime='081000', self.closeTime='081959',self.symbol='BTCUSDT',self.open='26788.3', self.close='26773.6'
2023-06-02 08:20:08,956:INFO:testStrategy:main.py:102:handleKline:2217133: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12141  20230602   073000    073959  1685662799  26776.3  26804.2
12142  20230602   074000    074959  1685663399  26804.3  26787.8
12143  20230602   075000    075959  1685663999  26787.8  26805.3
12144  20230602   080000    080959  1685664599  26805.3  26788.2
12145  20230602   081000    081959  1685665199  26788.3  26773.6
2023-06-02 08:20:08,957:INFO:testStrategy:main.py:103:handleKline:2217133: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}


## /root/FIL/strategy/sr_min/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=1, self.total=996015.990996, self.flagDict['side']='buy', self.tradeCount=1, self.count=5440
self.closeSec=1685665199, self.tradeDate='20230602', self.openTime='081500', self.closeTime='081959', self.symbol='BTCUSDT', self.open=26787.1, self.close=26773.6, self.high=26801.7, self.low=26750.0, self.vol=1625.472, self.amt=43521505.7451 
127.0.0.1 - - [02/Jun/2023 08:20:01] "POST / HTTP/1.1" 200 -
2023-06-02 08:20:07,425:INFO:sr_min:main.py:172:handleKline:2219263: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5855  20230602   075500    075959  ...         0.0        0.0       0
5856  20230602   080000    080459  ...         0.0        0.0       0
5857  20230602   080500    080959  ...         0.0        0.0       0
5858  20230602   081000    081459  ...         0.0        0.0       0
5859  20230602   081500    081959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-06-02 08:20:07,455:INFO:sr_min:main.py:175:handleKline:2219263: self.closeSec=1685665199, self.tradeDate='20230602', self.openTime='081500', self.closeTime='081959',self.symbol='BTCUSDT',self.open=26787.1, self.close=26773.6, self.high=26801.7, self.low=26750.0, self.vol=1625.472, self.amt=43521505.7451, ukdf['pct'].iloc[-1]=-0.000508 , ukdf['amount'].iloc[-1]=43521505.7451, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5859, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '37.141', 'enterprice': '26844', 'countrevence': '0', 'unrealprofit': '-2622.1546', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '26773.4', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=1
127.0.0.1 - - [02/Jun/2023 08:25:00] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=1, self.total=996015.990996, self.flagDict['side']='buy', self.tradeCount=1, self.count=5441
self.closeSec=1685665499, self.tradeDate='20230602', self.openTime='082000', self.closeTime='082459', self.symbol='BTCUSDT', self.open=26773.5, self.close=26727.1, self.high=26780.2, self.low=26721.9, self.vol=2260.896, self.amt=60483965.7344 
2023-06-02 08:25:00,813:INFO:sr_min:main.py:172:handleKline:2219263: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5856  20230602   080000    080459  ...         0.0        0.0       0
5857  20230602   080500    080959  ...         0.0        0.0       0
5858  20230602   081000    081459  ...         0.0        0.0       0
5859  20230602   081500    081959  ...         0.0        0.0       0
5860  20230602   082000    082459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-06-02 08:25:00,813:INFO:sr_min:main.py:175:handleKline:2219263: self.closeSec=1685665499, self.tradeDate='20230602', self.openTime='082000', self.closeTime='082459',self.symbol='BTCUSDT',self.open=26773.5, self.close=26727.1, self.high=26780.2, self.low=26721.9, self.vol=2260.896, self.amt=60483965.7344, ukdf['pct'].iloc[-1]=-0.001737 , ukdf['amount'].iloc[-1]=60483965.7344, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5860, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '37.141', 'enterprice': '26844', 'countrevence': '0', 'unrealprofit': '-4210.64807081217', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '26730.63072963', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=1


## /root/FIL/strategy/s_rsrs/log.txt ----- -----

719  20230601   200000    235959  1685635199  ...    719  0.774015  0.749031     1.0
720  20230602   000000    035959  1685649599  ...    720  0.722386  0.586507     NaN

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '55.249', 'enterprice': '26128.2', 'countrevence': '0', 'unrealprofit': '40276.521', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '26857.2', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-9223372036854775808, self.sign=1
127.0.0.1 - - [02/Jun/2023 08:00:01] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='s_rsrs', self.symbol='BTCUSDT', interval='4h', intervalSec=14400, wid=25, thd=0.6, self.sign=1, self.total=1442113.3648782002, self.flagDict['side']='buy', self.tradeCount=3, self.count=113
self.closeSec=1685663999, self.tradeDate='20230602', self.openTime='040000', self.closeTime='075959', self.symbol='BTCUSDT', self.open=26851.6, self.close=26805.3, self.high=26934.0, self.low=26697.1, self.vol=37327.512, self.amt=1001886430.693 
2023-06-02 08:00:01,897:INFO:s_rsrs:main.py:141:handleKline:2218689: self.closeSec=1685663999, self.tradeDate='20230602', self.openTime='040000', self.closeTime='075959',self.symbol='BTCUSDT',self.open=26851.6, self.close=26805.3, self.high=26934.0, self.low=26697.1, self.vol=37327.512, self.amt=1001886430.693 
2023-06-02 08:00:01,926:INFO:s_rsrs:main.py:142:handleKline:2218689: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime  ...         vol           amt       pct
717  20230601   120000    155959  ...   39306.804  1.053711e+09  0.000803
718  20230601   160000    195959  ...   36263.422  9.746964e+08  0.003419
719  20230601   200000    235959  ...   59027.609  1.586971e+09  0.000093
720  20230602   000000    035959  ...  111799.742  3.010613e+09 -0.001213
721  20230602   040000    075959  ...   37327.512  1.001886e+09 -0.001724

[5 rows x 11 columns]
2023-06-02 08:00:03,667:INFO:s_rsrs:main.py:151:handleKline:2218689: df_s.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec  ...  index      beta    zscore  signal
717  20230601   120000    155959  1685606399  ...    717  0.684852  0.484603     NaN
718  20230601   160000    195959  1685620799  ...    718  0.732305  0.626848     1.0
719  20230601   200000    235959  1685635199  ...    719  0.774015  0.749031     1.0
720  20230602   000000    035959  1685649599  ...    720  0.722386  0.586507     NaN
721  20230602   040000    075959  1685663999  ...    721  0.777972  0.742572     1.0

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '55.249', 'enterprice': '26128.2', 'countrevence': '0', 'unrealprofit': '37453.2971', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '26806.1', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=1, self.sign=1


