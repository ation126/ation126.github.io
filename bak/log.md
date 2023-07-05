# 20230705 16:26:01

## /root/FIL/strategy/amihud/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=373746.4768026, self.flagDict['side']='sell', self.tradeCount=2, self.count=15040
self.closeSec=1688545199, self.tradeDate='20230705', self.openTime='161500', self.closeTime='161959', self.symbol='BTCUSDT', self.open=30758.0, self.close=30691.6, self.high=30758.0, self.low=30637.5, self.vol=4902.723, self.amt=150477730.5852 
127.0.0.1 - - [05/Jul/2023 16:20:01] "POST / HTTP/1.1" 200 -
2023-07-05 16:20:07,494:INFO:amihud:main.py:172:handleKline:2219019: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5951  20230705   155500    155959  ...         0.0        0.0       0
5952  20230705   160000    160459  ...         0.0        0.0       0
5953  20230705   160500    160959  ...         0.0        0.0       0
5954  20230705   161000    161459  ...         0.0        0.0       0
5955  20230705   161500    161959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-07-05 16:20:07,516:INFO:amihud:main.py:175:handleKline:2219019: self.closeSec=1688545199, self.tradeDate='20230705', self.openTime='161500', self.closeTime='161959',self.symbol='BTCUSDT',self.open=30758.0, self.close=30691.6, self.high=30758.0, self.low=30637.5, self.vol=4902.723, self.amt=150477730.5852, ukdf['pct'].iloc[-1]=-0.002162 , ukdf['amount'].iloc[-1]=150477730.5852, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5955, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '13.926', 'enterprice': '26864.9', 'countrevence': '0', 'unrealprofit': '-53231.83840349496', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '30687.37870196', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1
127.0.0.1 - - [05/Jul/2023 16:25:00] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=373746.4768026, self.flagDict['side']='sell', self.tradeCount=2, self.count=15041
self.closeSec=1688545499, self.tradeDate='20230705', self.openTime='162000', self.closeTime='162459', self.symbol='BTCUSDT', self.open=30694.8, self.close=30699.9, self.high=30709.9, self.low=30675.1, self.vol=1539.895, self.amt=47267338.3451 
2023-07-05 16:25:00,789:INFO:amihud:main.py:172:handleKline:2219019: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5952  20230705   160000    160459  ...         0.0        0.0       0
5953  20230705   160500    160959  ...         0.0        0.0       0
5954  20230705   161000    161459  ...         0.0        0.0       0
5955  20230705   161500    161959  ...         0.0        0.0       0
5956  20230705   162000    162459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-07-05 16:25:00,790:INFO:amihud:main.py:175:handleKline:2219019: self.closeSec=1688545499, self.tradeDate='20230705', self.openTime='162000', self.closeTime='162459',self.symbol='BTCUSDT',self.open=30694.8, self.close=30699.9, self.high=30709.9, self.low=30675.1, self.vol=1539.895, self.amt=47267338.3451, ukdf['pct'].iloc[-1]=0.00027 , ukdf['amount'].iloc[-1]=47267338.3451, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5956, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '13.926', 'enterprice': '26864.9', 'countrevence': '0', 'unrealprofit': '-53407.6026', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '30700', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1


## /root/FIL/strategy/factorcheck/log.txt ----- -----


self.closeSec=1688545199, self.tradeDate='20230705', self.openTime='161500', self.closeTime='161959', self.symbol='BTCUSDT', self.open=30758.0, self.close=30691.6, self.high=30758.0, self.low=30637.5 
127.0.0.1 - - [05/Jul/2023 16:20:01] "POST / HTTP/1.1" 200 -
2023-07-05 16:20:05,024:INFO:factorcheck2:main.py:126:handleKline:2218005: self.closeSec=1688545199, self.tradeDate='20230705', self.openTime='161500', self.closeTime='161959',self.symbol='BTCUSDT',self.open=30758.0, self.close=30691.6, self.high=30758.0, self.low=30637.5   
2023-07-05 16:20:06,554:INFO:factorcheck2:main.py:127:handleKline:2218005: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1631  20230705   155500    155959  1688543999  ...  30753.0  0.000169   1631    5
1632  20230705   160000    160459  1688544299  ...  30740.0 -0.000234   1632    0
1633  20230705   160500    160959  1688544599  ...  30758.0  0.000010   1633    1
1634  20230705   161000    161459  1688544899  ...  30758.0 -0.000029   1634    2
1635  20230705   161500    161959  1688545199  ...  30637.5 -0.002162   1635    3

[5 rows x 11 columns]
2023-07-05 16:20:06,556:INFO:factorcheck2:main.py:128:handleKline:2218005: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': False, 'isOpen': True, 'isClose': False, 'isTrig': True}
127.0.0.1 - - [05/Jul/2023 16:25:00] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.6162111108866298, self.count=15043 

self.closeSec=1688545499, self.tradeDate='20230705', self.openTime='162000', self.closeTime='162459', self.symbol='BTCUSDT', self.open=30694.8, self.close=30699.9, self.high=30709.9, self.low=30675.1 
2023-07-05 16:25:00,738:INFO:factorcheck2:main.py:126:handleKline:2218005: self.closeSec=1688545499, self.tradeDate='20230705', self.openTime='162000', self.closeTime='162459',self.symbol='BTCUSDT',self.open=30694.8, self.close=30699.9, self.high=30709.9, self.low=30675.1   
2023-07-05 16:25:00,776:INFO:factorcheck2:main.py:127:handleKline:2218005: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1632  20230705   160000    160459  1688544299  ...  30740.0 -0.000234   1632    0
1633  20230705   160500    160959  1688544599  ...  30758.0  0.000010   1633    1
1634  20230705   161000    161459  1688544899  ...  30758.0 -0.000029   1634    2
1635  20230705   161500    161959  1688545199  ...  30637.5 -0.002162   1635    3
1636  20230705   162000    162459  1688545499  ...  30675.1  0.000270   1636    4

[5 rows x 11 columns]
2023-07-05 16:25:00,776:INFO:factorcheck2:main.py:128:handleKline:2218005: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': False, 'isOpen': True, 'isClose': False, 'isTrig': True}


## /root/FIL/strategy/logic/log.txt ----- -----

  File "/usr/lib/python3/dist-packages/urllib3/connectionpool.py", line 423, in _make_request
    self._raise_timeout(err=e, url=url, timeout_value=read_timeout)
  File "/usr/lib/python3/dist-packages/urllib3/connectionpool.py", line 330, in _raise_timeout
    raise ReadTimeoutError(
urllib3.exceptions.ReadTimeoutError: HTTPConnectionPool(host='127.0.0.1', port=8808): Read timed out. (read timeout=5)

During handling of the above exception, another exception occurred:

Traceback (most recent call last):
  File "/root/FIL/strategy/logic/FIL_lib/client.py", line 95, in __start_handle
    handle_call(handle_data)
  File "main.py", line 436, in handleKline
    self.queryPositions()
  File "main.py", line 511, in queryPositions
    positions = self.client.queryPositions(self.symbol)
  File "/root/FIL/strategy/logic/FIL_lib/client.py", line 323, in queryPositions
    return self.__post(data, PositionsReturn)
  File "/root/FIL/strategy/logic/FIL_lib/client.py", line 121, in __post
    res = requests.post(self.server_url, json=data, timeout=self.timeout)
  File "/usr/local/lib/python3.8/dist-packages/requests/api.py", line 119, in post
    return request('post', url, data=data, json=json, **kwargs)
  File "/usr/local/lib/python3.8/dist-packages/requests/api.py", line 61, in request
    return session.request(method=method, url=url, **kwargs)
  File "/usr/local/lib/python3.8/dist-packages/requests/sessions.py", line 530, in request
    resp = self.send(prep, **send_kwargs)
  File "/usr/local/lib/python3.8/dist-packages/requests/sessions.py", line 643, in send
    r = adapter.send(request, **kwargs)
  File "/usr/local/lib/python3.8/dist-packages/requests/adapters.py", line 529, in send
    raise ReadTimeout(e, request=request)
requests.exceptions.ReadTimeout: HTTPConnectionPool(host='127.0.0.1', port=8808): Read timed out. (read timeout=5)


## /root/FIL/strategy/modifiedmom/log.txt ----- -----

527  20230705   155000    155959  1688543999  30768.8  30765.9 -0.000091
2023-07-05 16:00:02,034:INFO:modifiedmom:main.py:146:handleKline:2218259: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True}

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=7520 

self.closeSec=1688544599, self.tradeDate='20230705', self.openTime='160000', self.closeTime='160959', self.symbol='BTCUSDT', self.open='30765.9', self.close='30759'
2023-07-05 16:10:01,137:INFO:modifiedmom:main.py:144:handleKline:2218259: self.closeSec=1688544599, self.tradeDate='20230705', self.openTime='160000', self.closeTime='160959',self.symbol='BTCUSDT',self.open='30765.9', self.close='30759'
127.0.0.1 - - [05/Jul/2023 16:10:01] "POST / HTTP/1.1" 200 -
2023-07-05 16:10:01,163:INFO:modifiedmom:main.py:145:handleKline:2218259: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
524  20230705   152000    152959  1688542199    30789  30773.5 -0.000503
525  20230705   153000    153959  1688542799  30773.4  30775.2  0.000055
526  20230705   154000    154959  1688543399  30775.2  30768.7 -0.000211
527  20230705   155000    155959  1688543999  30768.8  30765.9 -0.000091
528  20230705   160000    160959  1688544599  30765.9    30759 -0.000224
2023-07-05 16:10:01,163:INFO:modifiedmom:main.py:146:handleKline:2218259: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True}

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=7521 

self.closeSec=1688545199, self.tradeDate='20230705', self.openTime='161000', self.closeTime='161959', self.symbol='BTCUSDT', self.open='30759.1', self.close='30691.6'
127.0.0.1 - - [05/Jul/2023 16:20:04] "POST / HTTP/1.1" 200 -
2023-07-05 16:20:07,254:INFO:modifiedmom:main.py:144:handleKline:2218259: self.closeSec=1688545199, self.tradeDate='20230705', self.openTime='161000', self.closeTime='161959',self.symbol='BTCUSDT',self.open='30759.1', self.close='30691.6'
2023-07-05 16:20:07,995:INFO:modifiedmom:main.py:145:handleKline:2218259: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
525  20230705   153000    153959  1688542799  30773.4  30775.2  0.000055
526  20230705   154000    154959  1688543399  30775.2  30768.7 -0.000211
527  20230705   155000    155959  1688543999  30768.8  30765.9 -0.000091
528  20230705   160000    160959  1688544599  30765.9    30759 -0.000224
529  20230705   161000    161959  1688545199  30759.1  30691.6 -0.002191
2023-07-05 16:20:07,995:INFO:modifiedmom:main.py:146:handleKline:2218259: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True}


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

17519  20230705   155000    155959  1688543999  30768.8  30765.9
2023-07-05 16:00:02,056:INFO:pyemd2:main.py:127:handleKline:2217508: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=7523 

self.closeSec=1688544599, self.tradeDate='20230705', self.openTime='160000', self.closeTime='160959', self.symbol='BTCUSDT', self.open='30765.9', self.close='30759'
2023-07-05 16:10:01,147:INFO:pyemd2:main.py:125:handleKline:2217508: self.closeSec=1688544599, self.tradeDate='20230705', self.openTime='160000', self.closeTime='160959',self.symbol='BTCUSDT',self.open='30765.9', self.close='30759'
127.0.0.1 - - [05/Jul/2023 16:10:01] "POST / HTTP/1.1" 200 -
2023-07-05 16:10:01,168:INFO:pyemd2:main.py:126:handleKline:2217508: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17516  20230705   152000    152959  1688542199    30789  30773.5
17517  20230705   153000    153959  1688542799  30773.4  30775.2
17518  20230705   154000    154959  1688543399  30775.2  30768.7
17519  20230705   155000    155959  1688543999  30768.8  30765.9
17520  20230705   160000    160959  1688544599  30765.9    30759
2023-07-05 16:10:01,168:INFO:pyemd2:main.py:127:handleKline:2217508: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=7524 

self.closeSec=1688545199, self.tradeDate='20230705', self.openTime='161000', self.closeTime='161959', self.symbol='BTCUSDT', self.open='30759.1', self.close='30691.6'
127.0.0.1 - - [05/Jul/2023 16:20:04] "POST / HTTP/1.1" 200 -
2023-07-05 16:20:09,029:INFO:pyemd2:main.py:125:handleKline:2217508: self.closeSec=1688545199, self.tradeDate='20230705', self.openTime='161000', self.closeTime='161959',self.symbol='BTCUSDT',self.open='30759.1', self.close='30691.6'
2023-07-05 16:20:09,164:INFO:pyemd2:main.py:126:handleKline:2217508: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17517  20230705   153000    153959  1688542799  30773.4  30775.2
17518  20230705   154000    154959  1688543399  30775.2  30768.7
17519  20230705   155000    155959  1688543999  30768.8  30765.9
17520  20230705   160000    160959  1688544599  30765.9    30759
17521  20230705   161000    161959  1688545199  30759.1  30691.6
2023-07-05 16:20:09,166:INFO:pyemd2:main.py:127:handleKline:2217508: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}


## /root/FIL/strategy/similarity/log.txt ----- -----

12191  20230705   155000    155959  1688543999  30768.8  30765.9
2023-07-05 16:00:02,042:INFO:testStrategy:main.py:103:handleKline:2217133: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': True, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=7523 

self.closeSec=1688544599, self.tradeDate='20230705', self.openTime='160000', self.closeTime='160959', self.symbol='BTCUSDT', self.open='30765.9', self.close='30759'
2023-07-05 16:10:01,132:INFO:testStrategy:main.py:101:handleKline:2217133: self.closeSec=1688544599, self.tradeDate='20230705', self.openTime='160000', self.closeTime='160959',self.symbol='BTCUSDT',self.open='30765.9', self.close='30759'
127.0.0.1 - - [05/Jul/2023 16:10:01] "POST / HTTP/1.1" 200 -
2023-07-05 16:10:01,167:INFO:testStrategy:main.py:102:handleKline:2217133: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12188  20230705   152000    152959  1688542199    30789  30773.5
12189  20230705   153000    153959  1688542799  30773.4  30775.2
12190  20230705   154000    154959  1688543399  30775.2  30768.7
12191  20230705   155000    155959  1688543999  30768.8  30765.9
12192  20230705   160000    160959  1688544599  30765.9    30759
2023-07-05 16:10:01,168:INFO:testStrategy:main.py:103:handleKline:2217133: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': True, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=7524 

self.closeSec=1688545199, self.tradeDate='20230705', self.openTime='161000', self.closeTime='161959', self.symbol='BTCUSDT', self.open='30759.1', self.close='30691.6'
127.0.0.1 - - [05/Jul/2023 16:20:04] "POST / HTTP/1.1" 200 -
2023-07-05 16:20:08,658:INFO:testStrategy:main.py:101:handleKline:2217133: self.closeSec=1688545199, self.tradeDate='20230705', self.openTime='161000', self.closeTime='161959',self.symbol='BTCUSDT',self.open='30759.1', self.close='30691.6'
2023-07-05 16:20:08,949:INFO:testStrategy:main.py:102:handleKline:2217133: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12189  20230705   153000    153959  1688542799  30773.4  30775.2
12190  20230705   154000    154959  1688543399  30775.2  30768.7
12191  20230705   155000    155959  1688543999  30768.8  30765.9
12192  20230705   160000    160959  1688544599  30765.9    30759
12193  20230705   161000    161959  1688545199  30759.1  30691.6
2023-07-05 16:20:08,955:INFO:testStrategy:main.py:103:handleKline:2217133: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': True, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}


## /root/FIL/strategy/sr_min/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=1, self.total=996015.990996, self.flagDict['side']='buy', self.tradeCount=1, self.count=15040
self.closeSec=1688545199, self.tradeDate='20230705', self.openTime='161500', self.closeTime='161959', self.symbol='BTCUSDT', self.open=30758.0, self.close=30691.6, self.high=30758.0, self.low=30637.5, self.vol=4902.723, self.amt=150477730.5852 
127.0.0.1 - - [05/Jul/2023 16:20:01] "POST / HTTP/1.1" 200 -
2023-07-05 16:20:07,485:INFO:sr_min:main.py:172:handleKline:2219263: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5951  20230705   155500    155959  ...         0.0        0.0       0
5952  20230705   160000    160459  ...         0.0        0.0       0
5953  20230705   160500    160959  ...         0.0        0.0       0
5954  20230705   161000    161459  ...         0.0        0.0       0
5955  20230705   161500    161959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-07-05 16:20:07,524:INFO:sr_min:main.py:175:handleKline:2219263: self.closeSec=1688545199, self.tradeDate='20230705', self.openTime='161500', self.closeTime='161959',self.symbol='BTCUSDT',self.open=30758.0, self.close=30691.6, self.high=30758.0, self.low=30637.5, self.vol=4902.723, self.amt=150477730.5852, ukdf['pct'].iloc[-1]=-0.002162 , ukdf['amount'].iloc[-1]=150477730.5852, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5955, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '37.141', 'enterprice': '26844', 'countrevence': '0', 'unrealprofit': '142746.92836949636', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '30687.37870196', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=1
--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=1, self.total=996015.990996, self.flagDict['side']='buy', self.tradeCount=1, self.count=15041
self.closeSec=1688545499, self.tradeDate='20230705', self.openTime='162000', self.closeTime='162459', self.symbol='BTCUSDT', self.open=30694.8, self.close=30699.9, self.high=30709.9, self.low=30675.1, self.vol=1539.895, self.amt=47267338.3451 
127.0.0.1 - - [05/Jul/2023 16:25:00] "POST / HTTP/1.1" 200 -
2023-07-05 16:25:00,803:INFO:sr_min:main.py:172:handleKline:2219263: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5952  20230705   160000    160459  ...         0.0        0.0       0
5953  20230705   160500    160959  ...         0.0        0.0       0
5954  20230705   161000    161459  ...         0.0        0.0       0
5955  20230705   161500    161959  ...         0.0        0.0       0
5956  20230705   162000    162459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-07-05 16:25:00,804:INFO:sr_min:main.py:175:handleKline:2219263: self.closeSec=1688545499, self.tradeDate='20230705', self.openTime='162000', self.closeTime='162459',self.symbol='BTCUSDT',self.open=30694.8, self.close=30699.9, self.high=30709.9, self.low=30675.1, self.vol=1539.895, self.amt=47267338.3451, ukdf['pct'].iloc[-1]=0.00027 , ukdf['amount'].iloc[-1]=47267338.3451, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5956, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '37.141', 'enterprice': '26844', 'countrevence': '0', 'unrealprofit': '143215.696', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '30700', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=1


## /root/FIL/strategy/s_rsrs/log.txt ----- -----

721  20230705   040000    075959  1688515199  ...    721  0.847470  0.903770     1.0
722  20230705   080000    115959  1688529599  ...    722  0.783556  0.750836     1.0

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '53.05', 'enterprice': '30750.9', 'countrevence': '0', 'unrealprofit': '5777.145', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '30859.8', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=1, self.sign=1
127.0.0.1 - - [05/Jul/2023 16:00:01] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='s_rsrs', self.symbol='BTCUSDT', interval='4h', intervalSec=14400, wid=25, thd=0.6, self.sign=1, self.total=1629703.909755, self.flagDict['side']='buy', self.tradeCount=9, self.count=313
self.closeSec=1688543999, self.tradeDate='20230705', self.openTime='120000', self.closeTime='155959', self.symbol='BTCUSDT', self.open=30857.3, self.close=30765.9, self.high=30862.6, self.low=30742.9, self.vol=19242.008, self.amt=592699942.5793 
2023-07-05 16:00:01,555:INFO:s_rsrs:main.py:141:handleKline:2218689: self.closeSec=1688543999, self.tradeDate='20230705', self.openTime='120000', self.closeTime='155959',self.symbol='BTCUSDT',self.open=30857.3, self.close=30765.9, self.high=30862.6, self.low=30742.9, self.vol=19242.008, self.amt=592699942.5793 
2023-07-05 16:00:01,588:INFO:s_rsrs:main.py:142:handleKline:2218689: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime  ...        vol           amt       pct
719  20230704   200000    235959  ...  38716.412  1.199547e+09 -0.003127
720  20230705   000000    035959  ...  94152.133  2.904600e+09 -0.008854
721  20230705   040000    075959  ...  26150.576  8.044804e+08  0.002311
722  20230705   080000    115959  ...  18762.480  5.781087e+08  0.003284
723  20230705   120000    155959  ...  19242.008  5.926999e+08 -0.002959

[5 rows x 11 columns]
2023-07-05 16:00:03,010:INFO:s_rsrs:main.py:151:handleKline:2218689: df_s.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec  ...  index      beta    zscore  signal
719  20230704   200000    235959  1688486399  ...    719  0.029170 -0.937501    -1.0
720  20230705   000000    035959  1688500799  ...    720  0.414172 -0.063960     NaN
721  20230705   040000    075959  1688515199  ...    721  0.847470  0.903770     1.0
722  20230705   080000    115959  1688529599  ...    722  0.783556  0.750836     1.0
723  20230705   120000    155959  1688543999  ...    723  0.702982  0.562522     NaN

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '53.05', 'enterprice': '30750.9', 'countrevence': '0', 'unrealprofit': '790.734070511', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '30765.80544902', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-9223372036854775808, self.sign=1


