java.net.UnknownHostException: rollbar.co
    at java.base/sun.nio.ch.NioSocketImpl.connect(NioSocketImpl.java:567)
    at java.base/java.net.SocksSocketImpl.connect(SocksSocketImpl.java:333)
    at java.base/java.net.Socket.connect(Socket.java:648)
    at java.base/sun.security.ssl.SSLSocketImpl.connect(SSLSocketImpl.java:290)
    at java.base/sun.security.ssl.BaseSSLSocketImpl.connect(BaseSSLSocketImpl.java:173)
    at java.base/sun.net.NetworkClient.doConnect(NetworkClient.java:182)
    at java.base/sun.net.www.http.HttpClient.openServer(HttpClient.java:474)
    at java.base/sun.net.www.http.HttpClient.openServer(HttpClient.java:569)
    at java.base/sun.net.www.protocol.https.HttpsClient.<init>(HttpsClient.java:265)
    at java.base/sun.net.www.protocol.https.HttpsClient.New(HttpsClient.java:372)
    at java.base/sun.net.www.protocol.https.AbstractDelegateHttpsURLConnection.getNewHttpClient(AbstractDelegateHttpsURLConnection.java:177)
    at java.base/sun.net.www.protocol.http.HttpURLConnection.plainConnect0(HttpURLConnection.java:1194)
    at java.base/sun.net.www.protocol.http.HttpURLConnection.plainConnect(HttpURLConnection.java:1082)
    at java.base/sun.net.www.protocol.https.AbstractDelegateHttpsURLConnection.connect(AbstractDelegateHttpsURLConnection.java:163)
    at java.base/sun.net.www.protocol.http.HttpURLConnection.getInputStream0(HttpURLConnection.java:1600)
    at java.base/sun.net.www.protocol.http.HttpURLConnection.getInputStream(HttpURLConnection.java:1528)
    at java.base/java.net.HttpURLConnection.getResponseCode(HttpURLConnection.java:527)
    at java.base/sun.net.www.protocol.https.HttpsURLConnectionImpl.getResponseCode(HttpsURLConnectionImpl.java:308)
    at UnknownHostExceptionExample.main(UnknownHostExceptionExample.java:14)
