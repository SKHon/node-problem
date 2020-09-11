## socket hang up
node http server默认超时是2分钟，如果server端2分钟没有响应，或者在请求过程中server端意外退出，client会报这个错。
![demo](/socketHangUp)