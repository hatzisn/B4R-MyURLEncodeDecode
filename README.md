# B4R-MyURLEncodeDecode
This library  allows you to UrlEncode and UrlDecode strings in order to use them in URLs. Here is how to use it:

B4X:

<pre>
    Dim sToURLEncode As String = "Αυτή είναι μία πρόταση στα Ελληνικά. Για να δούμε πόσο καλά θα την κωδικοποιήσει"
    Dim bEnc(sToURLEncode.Length * 3) As Byte
    URL.Encode(sToURLEncode, bEnc)
    Log(bEnc)
    Dim bDec(sToURLEncode.Length * 3) As Byte
    URL.Decode(bEnc, bDec)
    Log(bDec)
</pre>
