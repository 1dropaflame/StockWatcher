# StockWatcher
Learning from GWT tutorial on StockWatcher using maven instead of Eclipse plugin.

I get this error

ConsoleLogger.java:33 ERROR!!! com.google.gwt.user.client.rpc.InvocationException: <!DOCTYPE html>
<html>
<head>
    <meta http-equiv="content-type" content="text/html; charset=UTF-8">
    <link type="text/css" rel="stylesheet" href="StockWatcher.css">
    <title>Stock Watcher UI</title>
    <script type="text/javascript" language="javascript" src="stockwatcher.StockWatcher.nocache.js"></script>
</head>
<body>
<h1>Stock Watcher UI</h1>
<div id="stockList"></div>
<iframe src="javascript:''" id="__gwt_historyFrame" tabIndex='-1' style="position:absolute;width:0;height:0;border:0"></iframe>
<noscript>
    <div style="width: 22em; position: absolute; left: 50%; margin-left: -11em; color: red; background-color: white; border: 1px solid red; padding: 4px; font-family: sans-serif">
        Your web browser must have JavaScript enabled
        in order for this application to display correctly.
    </div>
</noscript>
</body>
</html> from StockPriceService_Proxy.getPrices
Elf_g$ @ ConsoleLogger.java:33
27ConsoleLogger.java:33 ERROR!!! com.google.gwt.user.client.rpc.InvocationException: <!DOCTYPE html>
<html>
<head>
    <meta http-equiv="content-type" content="text/html; charset=UTF-8">
    <link type="text/css" rel="stylesheet" href="StockWatcher.css">
    <title>Stock Watcher UI</title>
    <script type="text/javascript" language="javascript" src="stockwatcher.StockWatcher.nocache.js"></script>
</head>
<body>
<h1>Stock Watcher UI</h1>
<div id="stockList"></div>
<iframe src="javascript:''" id="__gwt_historyFrame" tabIndex='-1' style="position:absolute;width:0;height:0;border:0"></iframe>
<noscript>
    <div style="width: 22em; position: absolute; left: 50%; margin-left: -11em; color: red; background-color: white; border: 1px solid red; padding: 4px; font-family: sans-serif">
        Your web browser must have JavaScript enabled
        in order for this application to display correctly.
    </div>
</noscript>
</body>
</html> from StockPriceService_Proxy.getPrices
Elf_g$ @ ConsoleLogger.java:33
NRe_g$ @ SimpleConsoleLogHandler.java:36
aRe_g$ @ Logger.java:312
_Qe_g$ @ Logger.java:302
wRe_g$ @ Logger.java:236
vRe_g$ @ Logger.java:227
ERe_g$ @ Logger.java:178
jof_g$ @ ResponseFromServerPanel.java:148
T3c_g$ @ RequestCallbackAdapter.java:237
qjc_g$ @ Request.java:250
ykc_g$ @ RequestBuilder.java:412
(anonymous) @ XMLHttpRequest.java:329
xI_g$ @ Impl.java:309
AI_g$ @ Impl.java:368
(anonymous) @ Impl.java:78
XMLHttpRequest.send (async)
$Md_g$ @ XMLHttpRequest.java:305
ckc_g$ @ RequestBuilder.java:418
lkc_g$ @ RequestBuilder.java:242
o3c_g$ @ RemoteServiceProxy.java:372
L3c_g$ @ RemoteServiceProxy.java:74
Dof_g$ @ StockPriceService_Proxy.java:32
Pnf_g$ @ ResponseFromServerPanel.java:157
Vnf_g$ @ ResponseFromServerPanel.java:68
vb_g$ @ Timer.java:135
(anonymous) @ Timer.java:139
xI_g$ @ Impl.java:309
AI_g$ @ Impl.java:368
(anonymous) @ Impl.java:78


