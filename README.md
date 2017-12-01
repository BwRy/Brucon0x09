# Browser Exploits? Grab ’em by the Collar!

Presented @ Brucon0x09 2017 (https://2018.brucon.org/i) by Debasish Mandal

# *Talk Abstract:*

APT has become a hot topic in enterprise IT today. One of the softwares that we see becomes victim of APT attack more often is web browsers and the attack surface is becoming bigger and bigger every day.

TCP Live Stream Injection (https://en.wikipedia.org/wiki/Packet_injection) is a technique that we have seen, is being abused by various Internet Service Providers, Router vendors for decades. We have seen in the past, using this technique ISPs, router vendors intercepts HTTP traffic and inject arbitrary data silently into HTTP responses. This is usually done by injecting arbitrary JavaScript code into actual HTTP response body in real time. When the injected JavaScript code reaches client browser it performs various operations such as loading advertisements, information gathering etc.

This paper presents a generic browser exploit detection technique that uses the same Live Network Stream Code Injection technique to reliably catch browser exploits. The detection system can be considered as completely agent less and capable of detecting various techniques, used in modern browser exploitation. Unlike any other Host Based Intrusion Prevention Systems, to be able to generically detect and block browser exploits, no OS API hooking, dll injection or code injection is required in browser process.


https://brucon0x092017.sched.com/event/BEBO/browser-exploits-grab-them-by-the-collar
