# api documentation for  [net-ping (v1.2.0)](https://github.com/stephenwvickers/node-net-ping#readme)  [![npm package](https://img.shields.io/npm/v/npmdoc-net-ping.svg?style=flat-square)](https://www.npmjs.org/package/npmdoc-net-ping) [![travis-ci.org build-status](https://api.travis-ci.org/npmdoc/node-npmdoc-net-ping.svg)](https://travis-ci.org/npmdoc/node-npmdoc-net-ping)
#### Ping and trace route to many hosts at once.

[![NPM](https://nodei.co/npm/net-ping.png?downloads=true)](https://www.npmjs.com/package/net-ping)

[![apidoc](https://npmdoc.github.io/node-npmdoc-net-ping/build/screenCapture.buildNpmdoc.browser._2Fhome_2Ftravis_2Fbuild_2Fnpmdoc_2Fnode-npmdoc-net-ping_2Ftmp_2Fbuild_2Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-net-ping/build/apidoc.html)

![npmPackageListing](https://npmdoc.github.io/node-npmdoc-net-ping/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmdoc.github.io/node-npmdoc-net-ping/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Stephen Vickers",
        "email": "stephen.vickers.sv@gmail.com"
    },
    "bugs": {
        "url": "https://github.com/stephenwvickers/node-net-ping/issues"
    },
    "contributors": [
        {
            "name": "Stephen Vickers",
            "email": "stephen.vickers.sv@gmail.com"
        }
    ],
    "dependencies": {
        "raw-socket": "*"
    },
    "description": "Ping and trace route to many hosts at once.",
    "devDependencies": {},
    "directories": {
        "example": "example"
    },
    "dist": {
        "shasum": "bad1a2361a482884384e4e5ee6c4b6c33763529e",
        "tarball": "https://registry.npmjs.org/net-ping/-/net-ping-1.2.0.tgz"
    },
    "gitHead": "b4c96f136c4995a25db474c9ec8ddb1ce28cb962",
    "homepage": "https://github.com/stephenwvickers/node-net-ping#readme",
    "keywords": [
        "echo",
        "icmp",
        "monitor",
        "monitoring",
        "net",
        "network",
        "ping",
        "trace",
        "trace-route",
        "traceroute",
        "tracert"
    ],
    "license": "MIT",
    "main": "index.js",
    "maintainers": [
        {
            "name": "stephen.vickers",
            "email": "stephen.vickers.sv@gmail.com"
        }
    ],
    "name": "net-ping",
    "optionalDependencies": {},
    "readme": "ERROR: No README data found!",
    "repository": {
        "type": "git",
        "url": "git://github.com/stephenwvickers/node-net-ping.git"
    },
    "scripts": {},
    "version": "1.2.0"
}
```



# <a name="apidoc.tableOfContents"></a>[table of contents](#apidoc.tableOfContents)

#### [module net-ping](#apidoc.module.net-ping)
1.  [function <span class="apidocSignatureSpan">net-ping.</span>DestinationUnreachableError (source)](#apidoc.element.net-ping.DestinationUnreachableError)
1.  [function <span class="apidocSignatureSpan">net-ping.</span>DestinationUnreachableError.super_ ()](#apidoc.element.net-ping.DestinationUnreachableError.super_)
1.  [function <span class="apidocSignatureSpan">net-ping.</span>PacketTooBigError (source)](#apidoc.element.net-ping.PacketTooBigError)
1.  [function <span class="apidocSignatureSpan">net-ping.</span>ParameterProblemError (source)](#apidoc.element.net-ping.ParameterProblemError)
1.  [function <span class="apidocSignatureSpan">net-ping.</span>RedirectReceivedError (source)](#apidoc.element.net-ping.RedirectReceivedError)
1.  [function <span class="apidocSignatureSpan">net-ping.</span>RequestTimedOutError ()](#apidoc.element.net-ping.RequestTimedOutError)
1.  [function <span class="apidocSignatureSpan">net-ping.</span>Session (options)](#apidoc.element.net-ping.Session)
1.  [function <span class="apidocSignatureSpan">net-ping.</span>SourceQuenchError (source)](#apidoc.element.net-ping.SourceQuenchError)
1.  [function <span class="apidocSignatureSpan">net-ping.</span>TimeExceededError (source)](#apidoc.element.net-ping.TimeExceededError)
1.  [function <span class="apidocSignatureSpan">net-ping.</span>createSession (options)](#apidoc.element.net-ping.createSession)
1.  object <span class="apidocSignatureSpan">net-ping.</span>NetworkProtocol
1.  object <span class="apidocSignatureSpan">net-ping.</span>Session.prototype

#### [module net-ping.DestinationUnreachableError](#apidoc.module.net-ping.DestinationUnreachableError)
1.  [function <span class="apidocSignatureSpan">net-ping.</span>DestinationUnreachableError (source)](#apidoc.element.net-ping.DestinationUnreachableError.DestinationUnreachableError)
1.  [function <span class="apidocSignatureSpan">net-ping.DestinationUnreachableError.</span>super_ ()](#apidoc.element.net-ping.DestinationUnreachableError.super_)

#### [module net-ping.DestinationUnreachableError.super_](#apidoc.module.net-ping.DestinationUnreachableError.super_)
1.  [function <span class="apidocSignatureSpan">net-ping.DestinationUnreachableError.</span>super_ ()](#apidoc.element.net-ping.DestinationUnreachableError.super_.super_)
1.  [function <span class="apidocSignatureSpan">net-ping.DestinationUnreachableError.super_.</span>captureStackTrace ()](#apidoc.element.net-ping.DestinationUnreachableError.super_.captureStackTrace)
1.  number <span class="apidocSignatureSpan">net-ping.DestinationUnreachableError.super_.</span>stackTraceLimit

#### [module net-ping.PacketTooBigError](#apidoc.module.net-ping.PacketTooBigError)
1.  [function <span class="apidocSignatureSpan">net-ping.</span>PacketTooBigError (source)](#apidoc.element.net-ping.PacketTooBigError.PacketTooBigError)
1.  [function <span class="apidocSignatureSpan">net-ping.PacketTooBigError.</span>super_ ()](#apidoc.element.net-ping.PacketTooBigError.super_)

#### [module net-ping.ParameterProblemError](#apidoc.module.net-ping.ParameterProblemError)
1.  [function <span class="apidocSignatureSpan">net-ping.</span>ParameterProblemError (source)](#apidoc.element.net-ping.ParameterProblemError.ParameterProblemError)
1.  [function <span class="apidocSignatureSpan">net-ping.ParameterProblemError.</span>super_ ()](#apidoc.element.net-ping.ParameterProblemError.super_)

#### [module net-ping.RedirectReceivedError](#apidoc.module.net-ping.RedirectReceivedError)
1.  [function <span class="apidocSignatureSpan">net-ping.</span>RedirectReceivedError (source)](#apidoc.element.net-ping.RedirectReceivedError.RedirectReceivedError)
1.  [function <span class="apidocSignatureSpan">net-ping.RedirectReceivedError.</span>super_ ()](#apidoc.element.net-ping.RedirectReceivedError.super_)

#### [module net-ping.RequestTimedOutError](#apidoc.module.net-ping.RequestTimedOutError)
1.  [function <span class="apidocSignatureSpan">net-ping.</span>RequestTimedOutError ()](#apidoc.element.net-ping.RequestTimedOutError.RequestTimedOutError)
1.  [function <span class="apidocSignatureSpan">net-ping.RequestTimedOutError.</span>super_ ()](#apidoc.element.net-ping.RequestTimedOutError.super_)

#### [module net-ping.Session](#apidoc.module.net-ping.Session)
1.  [function <span class="apidocSignatureSpan">net-ping.</span>Session (options)](#apidoc.element.net-ping.Session.Session)
1.  [function <span class="apidocSignatureSpan">net-ping.Session.</span>super_ ()](#apidoc.element.net-ping.Session.super_)

#### [module net-ping.Session.prototype](#apidoc.module.net-ping.Session.prototype)
1.  [function <span class="apidocSignatureSpan">net-ping.Session.prototype.</span>_debugRequest (target, req)](#apidoc.element.net-ping.Session.prototype._debugRequest)
1.  [function <span class="apidocSignatureSpan">net-ping.Session.prototype.</span>_debugResponse (source, buffer)](#apidoc.element.net-ping.Session.prototype._debugResponse)
1.  [function <span class="apidocSignatureSpan">net-ping.Session.prototype.</span>_generateId ()](#apidoc.element.net-ping.Session.prototype._generateId)
1.  [function <span class="apidocSignatureSpan">net-ping.Session.prototype.</span>close ()](#apidoc.element.net-ping.Session.prototype.close)
1.  [function <span class="apidocSignatureSpan">net-ping.Session.prototype.</span>flush (error)](#apidoc.element.net-ping.Session.prototype.flush)
1.  [function <span class="apidocSignatureSpan">net-ping.Session.prototype.</span>fromBuffer (buffer)](#apidoc.element.net-ping.Session.prototype.fromBuffer)
1.  [function <span class="apidocSignatureSpan">net-ping.Session.prototype.</span>getSocket ()](#apidoc.element.net-ping.Session.prototype.getSocket)
1.  [function <span class="apidocSignatureSpan">net-ping.Session.prototype.</span>onBeforeSocketSend (req)](#apidoc.element.net-ping.Session.prototype.onBeforeSocketSend)
1.  [function <span class="apidocSignatureSpan">net-ping.Session.prototype.</span>onSocketClose ()](#apidoc.element.net-ping.Session.prototype.onSocketClose)
1.  [function <span class="apidocSignatureSpan">net-ping.Session.prototype.</span>onSocketError (error)](#apidoc.element.net-ping.Session.prototype.onSocketError)
1.  [function <span class="apidocSignatureSpan">net-ping.Session.prototype.</span>onSocketMessage (buffer, source)](#apidoc.element.net-ping.Session.prototype.onSocketMessage)
1.  [function <span class="apidocSignatureSpan">net-ping.Session.prototype.</span>onSocketSend (req, error, bytes)](#apidoc.element.net-ping.Session.prototype.onSocketSend)
1.  [function <span class="apidocSignatureSpan">net-ping.Session.prototype.</span>onTimeout (req)](#apidoc.element.net-ping.Session.prototype.onTimeout)
1.  [function <span class="apidocSignatureSpan">net-ping.Session.prototype.</span>pingHost (target, callback)](#apidoc.element.net-ping.Session.prototype.pingHost)
1.  [function <span class="apidocSignatureSpan">net-ping.Session.prototype.</span>reqQueue (req)](#apidoc.element.net-ping.Session.prototype.reqQueue)
1.  [function <span class="apidocSignatureSpan">net-ping.Session.prototype.</span>reqRemove (id)](#apidoc.element.net-ping.Session.prototype.reqRemove)
1.  [function <span class="apidocSignatureSpan">net-ping.Session.prototype.</span>send (req)](#apidoc.element.net-ping.Session.prototype.send)
1.  [function <span class="apidocSignatureSpan">net-ping.Session.prototype.</span>setTTL (ttl)](#apidoc.element.net-ping.Session.prototype.setTTL)
1.  [function <span class="apidocSignatureSpan">net-ping.Session.prototype.</span>toBuffer (req)](#apidoc.element.net-ping.Session.prototype.toBuffer)
1.  [function <span class="apidocSignatureSpan">net-ping.Session.prototype.</span>traceRoute (target, ttlOrOptions, feedCallback, doneCallback)](#apidoc.element.net-ping.Session.prototype.traceRoute)
1.  [function <span class="apidocSignatureSpan">net-ping.Session.prototype.</span>traceRouteCallback (trace, req, error, target, sent, rcvd)](#apidoc.element.net-ping.Session.prototype.traceRouteCallback)

#### [module net-ping.SourceQuenchError](#apidoc.module.net-ping.SourceQuenchError)
1.  [function <span class="apidocSignatureSpan">net-ping.</span>SourceQuenchError (source)](#apidoc.element.net-ping.SourceQuenchError.SourceQuenchError)
1.  [function <span class="apidocSignatureSpan">net-ping.SourceQuenchError.</span>super_ ()](#apidoc.element.net-ping.SourceQuenchError.super_)

#### [module net-ping.TimeExceededError](#apidoc.module.net-ping.TimeExceededError)
1.  [function <span class="apidocSignatureSpan">net-ping.</span>TimeExceededError (source)](#apidoc.element.net-ping.TimeExceededError.TimeExceededError)
1.  [function <span class="apidocSignatureSpan">net-ping.TimeExceededError.</span>super_ ()](#apidoc.element.net-ping.TimeExceededError.super_)



# <a name="apidoc.module.net-ping"></a>[module net-ping](#apidoc.module.net-ping)

#### <a name="apidoc.element.net-ping.DestinationUnreachableError"></a>[function <span class="apidocSignatureSpan">net-ping.</span>DestinationUnreachableError (source)](#apidoc.element.net-ping.DestinationUnreachableError)
- description and source-code
```javascript
function DestinationUnreachableError(source) {
	this.name = "DestinationUnreachableError";
	this.message = "Destination unreachable (source=" + source + ")";
	this.source = source;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.net-ping.DestinationUnreachableError.super_"></a>[function <span class="apidocSignatureSpan">net-ping.</span>DestinationUnreachableError.super_ ()](#apidoc.element.net-ping.DestinationUnreachableError.super_)
- description and source-code
```javascript
function Error() { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.net-ping.PacketTooBigError"></a>[function <span class="apidocSignatureSpan">net-ping.</span>PacketTooBigError (source)](#apidoc.element.net-ping.PacketTooBigError)
- description and source-code
```javascript
function PacketTooBigError(source) {
	this.name = "PacketTooBigError";
	this.message = "Packet too big (source=" + source + ")";
	this.source = source;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.net-ping.ParameterProblemError"></a>[function <span class="apidocSignatureSpan">net-ping.</span>ParameterProblemError (source)](#apidoc.element.net-ping.ParameterProblemError)
- description and source-code
```javascript
function ParameterProblemError(source) {
	this.name = "ParameterProblemError";
	this.message = "Parameter problem (source=" + source + ")";
	this.source = source;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.net-ping.RedirectReceivedError"></a>[function <span class="apidocSignatureSpan">net-ping.</span>RedirectReceivedError (source)](#apidoc.element.net-ping.RedirectReceivedError)
- description and source-code
```javascript
function RedirectReceivedError(source) {
	this.name = "RedirectReceivedError";
	this.message = "Redirect received (source=" + source + ")";
	this.source = source;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.net-ping.RequestTimedOutError"></a>[function <span class="apidocSignatureSpan">net-ping.</span>RequestTimedOutError ()](#apidoc.element.net-ping.RequestTimedOutError)
- description and source-code
```javascript
function RequestTimedOutError() {
	this.name = "RequestTimedOutError";
	this.message = "Request timed out";
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.net-ping.Session"></a>[function <span class="apidocSignatureSpan">net-ping.</span>Session (options)](#apidoc.element.net-ping.Session)
- description and source-code
```javascript
function Session(options) {
	this.retries = (options && options.retries != undefined) ? options.retries : 1;
	this.timeout = (options && options.timeout) ? options.timeout : 2000;

	this.packetSize = (options && options.packetSize) ? options.packetSize : 16;

	if (this.packetSize < 12)
		this.packetSize = 12;

	this.addressFamily = (options && options.networkProtocol
				&& options.networkProtocol == NetworkProtocol.IPv6)
			? raw.AddressFamily.IPv6
			: raw.AddressFamily.IPv4;

	this._debug = (options && options._debug) ? true : false;
	
	this.defaultTTL = (options && options.ttl) ? options.ttl : 128;
	
	this.sessionId = (options && options.sessionId)
			? options.sessionId
			: process.pid;
	
	this.sessionId = this.sessionId % 65535;
	
	this.nextId = 1;

	this.socket = null;

	this.reqs = {};
	this.reqsPending = 0;

	this.getSocket ();
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.net-ping.SourceQuenchError"></a>[function <span class="apidocSignatureSpan">net-ping.</span>SourceQuenchError (source)](#apidoc.element.net-ping.SourceQuenchError)
- description and source-code
```javascript
function SourceQuenchError(source) {
	this.name = "SourceQuenchError";
	this.message = "Source quench (source=" + source + ")";
	this.source = source;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.net-ping.TimeExceededError"></a>[function <span class="apidocSignatureSpan">net-ping.</span>TimeExceededError (source)](#apidoc.element.net-ping.TimeExceededError)
- description and source-code
```javascript
function TimeExceededError(source) {
	this.name = "TimeExceededError";
	this.message = "Time exceeded (source=" + source + ")";
	this.source = source;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.net-ping.createSession"></a>[function <span class="apidocSignatureSpan">net-ping.</span>createSession (options)](#apidoc.element.net-ping.createSession)
- description and source-code
```javascript
createSession = function (options) {
	return new Session (options || {});
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.net-ping.DestinationUnreachableError"></a>[module net-ping.DestinationUnreachableError](#apidoc.module.net-ping.DestinationUnreachableError)

#### <a name="apidoc.element.net-ping.DestinationUnreachableError.DestinationUnreachableError"></a>[function <span class="apidocSignatureSpan">net-ping.</span>DestinationUnreachableError (source)](#apidoc.element.net-ping.DestinationUnreachableError.DestinationUnreachableError)
- description and source-code
```javascript
function DestinationUnreachableError(source) {
	this.name = "DestinationUnreachableError";
	this.message = "Destination unreachable (source=" + source + ")";
	this.source = source;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.net-ping.DestinationUnreachableError.super_"></a>[function <span class="apidocSignatureSpan">net-ping.DestinationUnreachableError.</span>super_ ()](#apidoc.element.net-ping.DestinationUnreachableError.super_)
- description and source-code
```javascript
function Error() { [native code] }
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.net-ping.DestinationUnreachableError.super_"></a>[module net-ping.DestinationUnreachableError.super_](#apidoc.module.net-ping.DestinationUnreachableError.super_)

#### <a name="apidoc.element.net-ping.DestinationUnreachableError.super_.super_"></a>[function <span class="apidocSignatureSpan">net-ping.DestinationUnreachableError.</span>super_ ()](#apidoc.element.net-ping.DestinationUnreachableError.super_.super_)
- description and source-code
```javascript
function Error() { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.net-ping.DestinationUnreachableError.super_.captureStackTrace"></a>[function <span class="apidocSignatureSpan">net-ping.DestinationUnreachableError.super_.</span>captureStackTrace ()](#apidoc.element.net-ping.DestinationUnreachableError.super_.captureStackTrace)
- description and source-code
```javascript
function captureStackTrace() { [native code] }
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.net-ping.PacketTooBigError"></a>[module net-ping.PacketTooBigError](#apidoc.module.net-ping.PacketTooBigError)

#### <a name="apidoc.element.net-ping.PacketTooBigError.PacketTooBigError"></a>[function <span class="apidocSignatureSpan">net-ping.</span>PacketTooBigError (source)](#apidoc.element.net-ping.PacketTooBigError.PacketTooBigError)
- description and source-code
```javascript
function PacketTooBigError(source) {
	this.name = "PacketTooBigError";
	this.message = "Packet too big (source=" + source + ")";
	this.source = source;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.net-ping.PacketTooBigError.super_"></a>[function <span class="apidocSignatureSpan">net-ping.PacketTooBigError.</span>super_ ()](#apidoc.element.net-ping.PacketTooBigError.super_)
- description and source-code
```javascript
function Error() { [native code] }
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.net-ping.ParameterProblemError"></a>[module net-ping.ParameterProblemError](#apidoc.module.net-ping.ParameterProblemError)

#### <a name="apidoc.element.net-ping.ParameterProblemError.ParameterProblemError"></a>[function <span class="apidocSignatureSpan">net-ping.</span>ParameterProblemError (source)](#apidoc.element.net-ping.ParameterProblemError.ParameterProblemError)
- description and source-code
```javascript
function ParameterProblemError(source) {
	this.name = "ParameterProblemError";
	this.message = "Parameter problem (source=" + source + ")";
	this.source = source;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.net-ping.ParameterProblemError.super_"></a>[function <span class="apidocSignatureSpan">net-ping.ParameterProblemError.</span>super_ ()](#apidoc.element.net-ping.ParameterProblemError.super_)
- description and source-code
```javascript
function Error() { [native code] }
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.net-ping.RedirectReceivedError"></a>[module net-ping.RedirectReceivedError](#apidoc.module.net-ping.RedirectReceivedError)

#### <a name="apidoc.element.net-ping.RedirectReceivedError.RedirectReceivedError"></a>[function <span class="apidocSignatureSpan">net-ping.</span>RedirectReceivedError (source)](#apidoc.element.net-ping.RedirectReceivedError.RedirectReceivedError)
- description and source-code
```javascript
function RedirectReceivedError(source) {
	this.name = "RedirectReceivedError";
	this.message = "Redirect received (source=" + source + ")";
	this.source = source;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.net-ping.RedirectReceivedError.super_"></a>[function <span class="apidocSignatureSpan">net-ping.RedirectReceivedError.</span>super_ ()](#apidoc.element.net-ping.RedirectReceivedError.super_)
- description and source-code
```javascript
function Error() { [native code] }
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.net-ping.RequestTimedOutError"></a>[module net-ping.RequestTimedOutError](#apidoc.module.net-ping.RequestTimedOutError)

#### <a name="apidoc.element.net-ping.RequestTimedOutError.RequestTimedOutError"></a>[function <span class="apidocSignatureSpan">net-ping.</span>RequestTimedOutError ()](#apidoc.element.net-ping.RequestTimedOutError.RequestTimedOutError)
- description and source-code
```javascript
function RequestTimedOutError() {
	this.name = "RequestTimedOutError";
	this.message = "Request timed out";
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.net-ping.RequestTimedOutError.super_"></a>[function <span class="apidocSignatureSpan">net-ping.RequestTimedOutError.</span>super_ ()](#apidoc.element.net-ping.RequestTimedOutError.super_)
- description and source-code
```javascript
function Error() { [native code] }
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.net-ping.Session"></a>[module net-ping.Session](#apidoc.module.net-ping.Session)

#### <a name="apidoc.element.net-ping.Session.Session"></a>[function <span class="apidocSignatureSpan">net-ping.</span>Session (options)](#apidoc.element.net-ping.Session.Session)
- description and source-code
```javascript
function Session(options) {
	this.retries = (options && options.retries != undefined) ? options.retries : 1;
	this.timeout = (options && options.timeout) ? options.timeout : 2000;

	this.packetSize = (options && options.packetSize) ? options.packetSize : 16;

	if (this.packetSize < 12)
		this.packetSize = 12;

	this.addressFamily = (options && options.networkProtocol
				&& options.networkProtocol == NetworkProtocol.IPv6)
			? raw.AddressFamily.IPv6
			: raw.AddressFamily.IPv4;

	this._debug = (options && options._debug) ? true : false;
	
	this.defaultTTL = (options && options.ttl) ? options.ttl : 128;
	
	this.sessionId = (options && options.sessionId)
			? options.sessionId
			: process.pid;
	
	this.sessionId = this.sessionId % 65535;
	
	this.nextId = 1;

	this.socket = null;

	this.reqs = {};
	this.reqsPending = 0;

	this.getSocket ();
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.net-ping.Session.super_"></a>[function <span class="apidocSignatureSpan">net-ping.Session.</span>super_ ()](#apidoc.element.net-ping.Session.super_)
- description and source-code
```javascript
function EventEmitter() {
  EventEmitter.init.call(this);
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.net-ping.Session.prototype"></a>[module net-ping.Session.prototype](#apidoc.module.net-ping.Session.prototype)

#### <a name="apidoc.element.net-ping.Session.prototype._debugRequest"></a>[function <span class="apidocSignatureSpan">net-ping.Session.prototype.</span>_debugRequest (target, req)](#apidoc.element.net-ping.Session.prototype._debugRequest)
- description and source-code
```javascript
_debugRequest = function (target, req) {
	console.log ("request: addressFamily=" + this.addressFamily + " target="
			+ req.target + " id=" + req.id + " buffer="
			+ req.buffer.toString ("hex"));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.net-ping.Session.prototype._debugResponse"></a>[function <span class="apidocSignatureSpan">net-ping.Session.prototype.</span>_debugResponse (source, buffer)](#apidoc.element.net-ping.Session.prototype._debugResponse)
- description and source-code
```javascript
_debugResponse = function (source, buffer) {
	console.log ("response: addressFamily=" + this.addressFamily + " source="
			+ source + " buffer=" + buffer.toString ("hex"));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.net-ping.Session.prototype._generateId"></a>[function <span class="apidocSignatureSpan">net-ping.Session.prototype.</span>_generateId ()](#apidoc.element.net-ping.Session.prototype._generateId)
- description and source-code
```javascript
_generateId = function () {
	var startId = this.nextId++;
	while (1) {
		if (this.nextId > 65535)
			this.nextId = 1;
		if (this.reqs[this.nextId]) {
			this.nextId++;
		} else {
			return this.nextId;
		}
		// No free request IDs
		if (this.nextId == startId)
			return;
	}
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.net-ping.Session.prototype.close"></a>[function <span class="apidocSignatureSpan">net-ping.Session.prototype.</span>close ()](#apidoc.element.net-ping.Session.prototype.close)
- description and source-code
```javascript
close = function () {
	if (this.socket)
		this.socket.close ();
	this.flush (new Error ("Socket forcibly closed"));
	delete this.socket;
	return this;
}
```
- example usage
```shell
...

## Version 1.1.0 - 13/02/2013

* Support IPv6

## Version 1.1.1 - 15/02/2013

* The 'ping.Session.close()' method was not undefining the sessions raw
  socket after closing
* Return self from the 'pingHost()' method to chain method calls

## Version 1.1.2 - 04/03/2013

* Use the 'raw.Socket.pauseRecv()' and 'raw.Socket.resumeRecv()' methods
  instead of closing a socket when there are no more outstanding requests
...
```

#### <a name="apidoc.element.net-ping.Session.prototype.flush"></a>[function <span class="apidocSignatureSpan">net-ping.Session.prototype.</span>flush (error)](#apidoc.element.net-ping.Session.prototype.flush)
- description and source-code
```javascript
flush = function (error) {
	for (id in this.reqs) {
		var req = this.reqRemove (id);
		var sent = req.sent ? req.sent : new Date ();
		req.callback (error, req.target, sent, new Date ());
	}
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.net-ping.Session.prototype.fromBuffer"></a>[function <span class="apidocSignatureSpan">net-ping.Session.prototype.</span>fromBuffer (buffer)](#apidoc.element.net-ping.Session.prototype.fromBuffer)
- description and source-code
```javascript
fromBuffer = function (buffer) {
	var offset, type, code;

	if (this.addressFamily == raw.AddressFamily.IPv6) {
		// IPv6 raw sockets don't pass the IPv6 header back to us
		offset = 0;

		if (buffer.length - offset < 8)
			return;
		
		// We don't believe any IPv6 options will be passed back to us so we
		// don't attempt to pass them here.

		type = buffer.readUInt8 (offset);
		code = buffer.readUInt8 (offset + 1);
	} else {
		// Need at least 20 bytes for an IP header, and it should be IPv4
		if (buffer.length < 20 || (buffer[0] & 0xf0) != 0x40)
			return;

		// The length of the IPv4 header is in mulitples of double words
		var ip_length = (buffer[0] & 0x0f) * 4;

		// ICMP header is 8 bytes, we don't care about the data for now
		if (buffer.length - ip_length < 8)
			return;

		var ip_icmp_offset = ip_length;

		// ICMP message too short
		if (buffer.length - ip_icmp_offset < 8)
			return;

		type = buffer.readUInt8 (ip_icmp_offset);
		code = buffer.readUInt8 (ip_icmp_offset + 1);

		// For error type responses the sequence and identifier cannot be
		// extracted in the same way as echo responses, the data part contains
		// the IP header from our request, followed with at least 8 bytes from
		// the echo request that generated the error, so we first go to the IP
		// header, then skip that to get to the ICMP packet which contains the
		// sequence and identifier.
		if (type == 3 || type == 4 || type == 5 || type == 11) {
			var ip_icmp_ip_offset = ip_icmp_offset + 8;

			// Need at least 20 bytes for an IP header, and it should be IPv4
			if (buffer.length - ip_icmp_ip_offset  < 20
					|| (buffer[ip_icmp_ip_offset] & 0xf0) != 0x40)
				return;

			// The length of the IPv4 header is in mulitples of double words
			var ip_icmp_ip_length = (buffer[ip_icmp_ip_offset] & 0x0f) * 4;

			// ICMP message too short
			if (buffer.length - ip_icmp_ip_offset - ip_icmp_ip_length < 8)
				return;

			offset = ip_icmp_ip_offset + ip_icmp_ip_length;
		} else {
			offset = ip_icmp_offset
		}
	}

	// Response is not for a request we generated
	if (buffer.readUInt16BE (offset + 4) != this.sessionId)
		return;

	buffer[offset + 4] = 0;
	
	var id = buffer.readUInt16BE (offset + 6);
	var req = this.reqs[id];

	if (req) {
		req.type = type;
		req.code = code;
		return req;
	} else {
		return null;
	}
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.net-ping.Session.prototype.getSocket"></a>[function <span class="apidocSignatureSpan">net-ping.Session.prototype.</span>getSocket ()](#apidoc.element.net-ping.Session.prototype.getSocket)
- description and source-code
```javascript
getSocket = function () {
	if (this.socket)
		return this.socket;

	var protocol = this.addressFamily == raw.AddressFamily.IPv6
			? raw.Protocol.ICMPv6
			: raw.Protocol.ICMP;

	var me = this;
	var options = {
		addressFamily: this.addressFamily,
		protocol: protocol
	};

	this.socket = raw.createSocket (options);
	this.socket.on ("error", this.onSocketError.bind (me));
	this.socket.on ("close", this.onSocketClose.bind (me));
	this.socket.on ("message", this.onSocketMessage.bind (me));
	
	this.ttl = null;
	this.setTTL (this.defaultTTL);
	
	return this.socket;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.net-ping.Session.prototype.onBeforeSocketSend"></a>[function <span class="apidocSignatureSpan">net-ping.Session.prototype.</span>onBeforeSocketSend (req)](#apidoc.element.net-ping.Session.prototype.onBeforeSocketSend)
- description and source-code
```javascript
onBeforeSocketSend = function (req) {
	this.setTTL (req.ttl ? req.ttl : this.defaultTTL);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.net-ping.Session.prototype.onSocketClose"></a>[function <span class="apidocSignatureSpan">net-ping.Session.prototype.</span>onSocketClose ()](#apidoc.element.net-ping.Session.prototype.onSocketClose)
- description and source-code
```javascript
onSocketClose = function () {
	this.emit ("close");
	this.flush (new Error ("Socket closed"));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.net-ping.Session.prototype.onSocketError"></a>[function <span class="apidocSignatureSpan">net-ping.Session.prototype.</span>onSocketError (error)](#apidoc.element.net-ping.Session.prototype.onSocketError)
- description and source-code
```javascript
onSocketError = function (error) {
	this.emit ("error", error);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.net-ping.Session.prototype.onSocketMessage"></a>[function <span class="apidocSignatureSpan">net-ping.Session.prototype.</span>onSocketMessage (buffer, source)](#apidoc.element.net-ping.Session.prototype.onSocketMessage)
- description and source-code
```javascript
onSocketMessage = function (buffer, source) {
	if (this._debug)
		this._debugResponse (source, buffer);

	var req = this.fromBuffer (buffer);
	if (req) {
		/**
		 ** If we ping'd ourself (i.e. 127.0.0.1 or ::1) then it is likely we
		 ** will receive the echo request in addition to any corresponding echo
		 ** responses.  We discard the request packets here so that we don't
		 ** delete the request from the from the request queue since we haven't
		 ** actually received a response yet.
		 **/
		if (this.addressFamily == raw.AddressFamily.IPv6) {
			if (req.type == 128)
				return;
		} else {
			if (req.type == 8)
				return;
		}
		
		this.reqRemove (req.id);
		
		if (this.addressFamily == raw.AddressFamily.IPv6) {
			if (req.type == 1) {
				req.callback (new DestinationUnreachableError (source), req.target,
						req.sent, new Date ());
			} else if (req.type == 2) {
				req.callback (new PacketTooBigError (source), req.target,
						req.sent, new Date ());
			} else if (req.type == 3) {
				req.callback (new TimeExceededError (source), req.target,
						req.sent, new Date ());
			} else if (req.type == 4) {
				req.callback (new ParameterProblemError (source), req.target,
						req.sent, new Date ());
			} else if (req.type == 129) {
				req.callback (null, req.target,
						req.sent, new Date ());
			} else {
				req.callback (new Error ("Unknown response type '" + req.type
						+ "' (source=" + source + ")"), req.target,
						req.sent, new Date ());
			}
		} else {
			if (req.type == 0) {
				req.callback (null, req.target,
						req.sent, new Date ());
			} else if (req.type == 3) {
				req.callback (new DestinationUnreachableError (source), req.target,
						req.sent, new Date ());
			} else if (req.type == 4) {
				req.callback (new SourceQuenchError (source), req.target,
						req.sent, new Date ());
			} else if (req.type == 5) {
				req.callback (new RedirectReceivedError (source), req.target,
						req.sent, new Date ());
			} else if (req.type == 11) {
				req.callback (new TimeExceededError (source), req.target,
						req.sent, new Date ());
			} else {
				req.callback (new Error ("Unknown response type '" + req.type
						+ "' (source=" + source + ")"), req.target,
						req.sent, new Date ());
			}
		}
	}
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.net-ping.Session.prototype.onSocketSend"></a>[function <span class="apidocSignatureSpan">net-ping.Session.prototype.</span>onSocketSend (req, error, bytes)](#apidoc.element.net-ping.Session.prototype.onSocketSend)
- description and source-code
```javascript
onSocketSend = function (req, error, bytes) {
	if (! req.sent)
		req.sent = new Date ();
	if (error) {
		this.reqRemove (req.id);
		req.callback (error, req.target, req.sent, req.sent);
	} else {
		var me = this;
		req.timer = setTimeout (this.onTimeout.bind (me, req), req.timeout);
	}
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.net-ping.Session.prototype.onTimeout"></a>[function <span class="apidocSignatureSpan">net-ping.Session.prototype.</span>onTimeout (req)](#apidoc.element.net-ping.Session.prototype.onTimeout)
- description and source-code
```javascript
onTimeout = function (req) {
	if (req.retries > 0) {
		req.retries--;
		this.send (req);
	} else {
		this.reqRemove (req.id);
		req.callback (new RequestTimedOutError ("Request timed out"),
				req.target, req.sent, new Date ());
	}
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.net-ping.Session.prototype.pingHost"></a>[function <span class="apidocSignatureSpan">net-ping.Session.prototype.</span>pingHost (target, callback)](#apidoc.element.net-ping.Session.prototype.pingHost)
- description and source-code
```javascript
pingHost = function (target, callback) {
	var id = this._generateId ();
	if (! id) {
		callback (new Error ("Too many requests outstanding"), target);
		return this;
	}

	var req = {
		id: id,
		retries: this.retries,
		timeout: this.timeout,
		callback: callback,
		target: target
	};

	this.reqQueue (req);

	return this;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.net-ping.Session.prototype.reqQueue"></a>[function <span class="apidocSignatureSpan">net-ping.Session.prototype.</span>reqQueue (req)](#apidoc.element.net-ping.Session.prototype.reqQueue)
- description and source-code
```javascript
reqQueue = function (req) {
	req.buffer = this.toBuffer (req);

	if (this._debug)
		this._debugRequest (req.target, req);

	this.reqs[req.id] = req;
	this.reqsPending++;
	this.send (req);
	
	return this;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.net-ping.Session.prototype.reqRemove"></a>[function <span class="apidocSignatureSpan">net-ping.Session.prototype.</span>reqRemove (id)](#apidoc.element.net-ping.Session.prototype.reqRemove)
- description and source-code
```javascript
reqRemove = function (id) {
	var req = this.reqs[id];
	if (req) {
		clearTimeout (req.timer);
		delete req.timer;
		delete this.reqs[req.id];
		this.reqsPending--;
	}
	// If we have no more outstanding requests pause readable events
	if (this.reqsPending <= 0)
		if (! this.getSocket ().recvPaused)
			this.getSocket ().pauseRecv ();
	return req;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.net-ping.Session.prototype.send"></a>[function <span class="apidocSignatureSpan">net-ping.Session.prototype.</span>send (req)](#apidoc.element.net-ping.Session.prototype.send)
- description and source-code
```javascript
send = function (req) {
	var buffer = req.buffer;
	var me = this;
	// Resume readable events if the raw socket is paused
	if (this.getSocket ().recvPaused)
		this.getSocket ().resumeRecv ();
	this.getSocket ().send (buffer, 0, buffer.length, req.target,
			this.onBeforeSocketSend.bind (me, req),
			this.onSocketSend.bind (me, req));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.net-ping.Session.prototype.setTTL"></a>[function <span class="apidocSignatureSpan">net-ping.Session.prototype.</span>setTTL (ttl)](#apidoc.element.net-ping.Session.prototype.setTTL)
- description and source-code
```javascript
setTTL = function (ttl) {
	if (this.ttl && this.ttl == ttl)
		return;

	var level = this.addressFamily == raw.AddressFamily.IPv6
			? raw.SocketLevel.IPPROTO_IPV6
			: raw.SocketLevel.IPPROTO_IP;
	this.getSocket ().setOption (level, raw.SocketOption.IP_TTL, ttl);
	this.ttl = ttl;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.net-ping.Session.prototype.toBuffer"></a>[function <span class="apidocSignatureSpan">net-ping.Session.prototype.</span>toBuffer (req)](#apidoc.element.net-ping.Session.prototype.toBuffer)
- description and source-code
```javascript
toBuffer = function (req) {
	var buffer = new Buffer (this.packetSize);

	// Since our buffer represents real memory we should initialise it to
	// prevent its previous contents from leaking to the network.
	for (var i = 8; i < this.packetSize; i++)
		buffer[i] = 0;

	var type = this.addressFamily == raw.AddressFamily.IPv6 ? 128 : 8;

	buffer.writeUInt8 (type, 0);
	buffer.writeUInt8 (0, 1);
	buffer.writeUInt16BE (0, 2);
	buffer.writeUInt16BE (this.sessionId, 4);
	buffer.writeUInt16BE (req.id, 6);

	raw.writeChecksum (buffer, 2, raw.createChecksum (buffer));

	return buffer;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.net-ping.Session.prototype.traceRoute"></a>[function <span class="apidocSignatureSpan">net-ping.Session.prototype.</span>traceRoute (target, ttlOrOptions, feedCallback, doneCallback)](#apidoc.element.net-ping.Session.prototype.traceRoute)
- description and source-code
```javascript
traceRoute = function (target, ttlOrOptions, feedCallback, doneCallback) {
	// signature was (target, feedCallback, doneCallback)
	if (! doneCallback) {
		doneCallback = feedCallback;
		feedCallback = ttlOrOptions;
		ttlOrOptions = {ttl: this.ttl};
	}

	var maxHopTimeouts = 3;
	var startTtl = 1;
	var ttl = this.ttl;

	if (typeof ttlOrOptions == "object") {
		if (ttlOrOptions.ttl)
			ttl = ttlOrOptions.ttl;
		if (ttlOrOptions.maxHopTimeouts)
			maxHopTimeouts = ttlOrOptions.maxHopTimeouts;
		if (ttlOrOptions.startTtl)
			startTtl = ttlOrOptions.startTtl;
	} else {
		ttl = ttlOrOptions;
	}

	var id = this._generateId ();
	if (! id) {
		var sent = new Date ();
		doneCallback (new Error ("Too many requests outstanding"), target,
				sent, sent);
		return this;
	}

	var trace = {
		feedCallback: feedCallback,
		doneCallback: doneCallback,
		ttl: ttl,
		maxHopTimeouts: maxHopTimeouts,
		timeouts: 0
	};
	
	var me = this;

	var req = {
		id: id,
		retries: this.retries,
		timeout: this.timeout,
		ttl: startTtl,
		target: target
	};
	req.callback = me.traceRouteCallback.bind (me, trace, req);
	
	this.reqQueue (req);

	return this;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.net-ping.Session.prototype.traceRouteCallback"></a>[function <span class="apidocSignatureSpan">net-ping.Session.prototype.</span>traceRouteCallback (trace, req, error, target, sent, rcvd)](#apidoc.element.net-ping.Session.prototype.traceRouteCallback)
- description and source-code
```javascript
traceRouteCallback = function (trace, req, error, target, sent, rcvd) {
	if (trace.feedCallback (error, target, req.ttl, sent, rcvd)) {
		trace.doneCallback (new Error ("Trace forcibly stopped"), target);
		return;
	}

	if (error) {
		if (req.ttl >= trace.ttl) {
			trace.doneCallback (error, target);
			return;
		}
		
		if ((error instanceof RequestTimedOutError) && ++trace.timeouts >= trace.maxHopTimeouts) {
			trace.doneCallback (new Error ("Too many timeouts"), target);
			return;
		}

		var id = this._generateId ();
		if (! id) {
			trace.doneCallback (new Error ("Too many requests outstanding"),
					target);
			return;
		}

		req.ttl++;
		req.id = id;
		var me = this;
		req.retries = this.retries;
		req.sent = null;
		this.reqQueue (req);
	} else {
		trace.doneCallback (null, target);
	}
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.net-ping.SourceQuenchError"></a>[module net-ping.SourceQuenchError](#apidoc.module.net-ping.SourceQuenchError)

#### <a name="apidoc.element.net-ping.SourceQuenchError.SourceQuenchError"></a>[function <span class="apidocSignatureSpan">net-ping.</span>SourceQuenchError (source)](#apidoc.element.net-ping.SourceQuenchError.SourceQuenchError)
- description and source-code
```javascript
function SourceQuenchError(source) {
	this.name = "SourceQuenchError";
	this.message = "Source quench (source=" + source + ")";
	this.source = source;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.net-ping.SourceQuenchError.super_"></a>[function <span class="apidocSignatureSpan">net-ping.SourceQuenchError.</span>super_ ()](#apidoc.element.net-ping.SourceQuenchError.super_)
- description and source-code
```javascript
function Error() { [native code] }
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.net-ping.TimeExceededError"></a>[module net-ping.TimeExceededError](#apidoc.module.net-ping.TimeExceededError)

#### <a name="apidoc.element.net-ping.TimeExceededError.TimeExceededError"></a>[function <span class="apidocSignatureSpan">net-ping.</span>TimeExceededError (source)](#apidoc.element.net-ping.TimeExceededError.TimeExceededError)
- description and source-code
```javascript
function TimeExceededError(source) {
	this.name = "TimeExceededError";
	this.message = "Time exceeded (source=" + source + ")";
	this.source = source;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.net-ping.TimeExceededError.super_"></a>[function <span class="apidocSignatureSpan">net-ping.TimeExceededError.</span>super_ ()](#apidoc.element.net-ping.TimeExceededError.super_)
- description and source-code
```javascript
function Error() { [native code] }
```
- example usage
```shell
n/a
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
