# api documentation for  [homebridge-harmonyhub (v0.2.0)](https://github.com/kraigm/homebridge-harmonyhub#readme)  [![npm package](https://img.shields.io/npm/v/npmdoc-homebridge-harmonyhub.svg?style=flat-square)](https://www.npmjs.org/package/npmdoc-homebridge-harmonyhub) [![travis-ci.org build-status](https://api.travis-ci.org/npmdoc/node-npmdoc-homebridge-harmonyhub.svg)](https://travis-ci.org/npmdoc/node-npmdoc-homebridge-harmonyhub)
#### Logitech Harmony Hub plugin for HomeBridge

[![NPM](https://nodei.co/npm/homebridge-harmonyhub.png?downloads=true)](https://www.npmjs.com/package/homebridge-harmonyhub)

[![apidoc](https://npmdoc.github.io/node-npmdoc-homebridge-harmonyhub/build/screenCapture.buildNpmdoc.browser._2Fhome_2Ftravis_2Fbuild_2Fnpmdoc_2Fnode-npmdoc-homebridge-harmonyhub_2Ftmp_2Fbuild_2Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-homebridge-harmonyhub/build/apidoc.html)

![npmPackageListing](https://npmdoc.github.io/node-npmdoc-homebridge-harmonyhub/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmdoc.github.io/node-npmdoc-homebridge-harmonyhub/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "bugs": {
        "url": "https://github.com/kraigm/homebridge-harmonyhub/issues"
    },
    "dependencies": {
        "bluebird": "^3.3.4",
        "debug": "^2.2.0",
        "harmonyhubjs-client": "^1.1.6",
        "harmonyhubjs-discover": "^1.0.2",
        "inherits": "^2.0.1",
        "lodash": "^4.6",
        "queue": "^3.1.0"
    },
    "description": "Logitech Harmony Hub plugin for HomeBridge",
    "devDependencies": {},
    "directories": {},
    "dist": {
        "shasum": "db0c3aee807c2232b48fc0c8b4c1a0d17467f443",
        "tarball": "https://registry.npmjs.org/homebridge-harmonyhub/-/homebridge-harmonyhub-0.2.0.tgz"
    },
    "engines": {
        "homebridge": ">=0.3.1",
        "node": ">=0.12.0"
    },
    "gitHead": "01622ead3054da7e0afdb94f10dbaba1d35cffcb",
    "homepage": "https://github.com/kraigm/homebridge-harmonyhub#readme",
    "keywords": [
        "homebridge-plugin"
    ],
    "license": "ISC",
    "maintainers": [
        {
            "name": "kraigm",
            "email": "kraigm@enferra.com"
        }
    ],
    "name": "homebridge-harmonyhub",
    "optionalDependencies": {},
    "preferGlobal": true,
    "readme": "ERROR: No README data found!",
    "repository": {
        "type": "git",
        "url": "git://github.com/kraigm/homebridge-harmonyhub.git"
    },
    "scripts": {},
    "version": "0.2.0"
}
```



# <a name="apidoc.tableOfContents"></a>[table of contents](#apidoc.tableOfContents)

#### [module homebridge-harmonyhub](#apidoc.module.homebridge-harmonyhub)
1.  [function <span class="apidocSignatureSpan">homebridge-harmonyhub.</span>accessory_base (exportedTypes)](#apidoc.element.homebridge-harmonyhub.accessory_base)
1.  [function <span class="apidocSignatureSpan">homebridge-harmonyhub.</span>activity_accessory (exportedTypes)](#apidoc.element.homebridge-harmonyhub.activity_accessory)
1.  [function <span class="apidocSignatureSpan">homebridge-harmonyhub.</span>home_platform ()](#apidoc.element.homebridge-harmonyhub.home_platform)
1.  [function <span class="apidocSignatureSpan">homebridge-harmonyhub.</span>hub (exportedTypes)](#apidoc.element.homebridge-harmonyhub.hub)
1.  [function <span class="apidocSignatureSpan">homebridge-harmonyhub.</span>hub_accessory_base (exportedTypes)](#apidoc.element.homebridge-harmonyhub.hub_accessory_base)
1.  [function <span class="apidocSignatureSpan">homebridge-harmonyhub.</span>hub_connection (hubInfo, log, discover)](#apidoc.element.homebridge-harmonyhub.hub_connection)
1.  object <span class="apidocSignatureSpan">homebridge-harmonyhub.</span>bluebird_ext
1.  object <span class="apidocSignatureSpan">homebridge-harmonyhub.</span>hub_connection.prototype
1.  object <span class="apidocSignatureSpan">homebridge-harmonyhub.</span>inherit

#### [module homebridge-harmonyhub.accessory_base](#apidoc.module.homebridge-harmonyhub.accessory_base)
1.  [function <span class="apidocSignatureSpan">homebridge-harmonyhub.</span>accessory_base (exportedTypes)](#apidoc.element.homebridge-harmonyhub.accessory_base.accessory_base)
1.  [function <span class="apidocSignatureSpan">homebridge-harmonyhub.accessory_base.</span>AccessoryBase (accessory, idKey, name, log)](#apidoc.element.homebridge-harmonyhub.accessory_base.AccessoryBase)

#### [module homebridge-harmonyhub.activity_accessory](#apidoc.module.homebridge-harmonyhub.activity_accessory)
1.  [function <span class="apidocSignatureSpan">homebridge-harmonyhub.</span>activity_accessory (exportedTypes)](#apidoc.element.homebridge-harmonyhub.activity_accessory.activity_accessory)
1.  [function <span class="apidocSignatureSpan">homebridge-harmonyhub.activity_accessory.</span>ActivityAccessory (accessory, log, connection)](#apidoc.element.homebridge-harmonyhub.activity_accessory.ActivityAccessory)
1.  object <span class="apidocSignatureSpan">homebridge-harmonyhub.activity_accessory.</span>ActivityStatus

#### [module homebridge-harmonyhub.bluebird_ext](#apidoc.module.homebridge-harmonyhub.bluebird_ext)
1.  [function <span class="apidocSignatureSpan">homebridge-harmonyhub.bluebird_ext.</span>asBlueBird (func)](#apidoc.element.homebridge-harmonyhub.bluebird_ext.asBlueBird)
1.  [function <span class="apidocSignatureSpan">homebridge-harmonyhub.bluebird_ext.</span>toBlueBird (promise)](#apidoc.element.homebridge-harmonyhub.bluebird_ext.toBlueBird)

#### [module homebridge-harmonyhub.home_platform](#apidoc.module.homebridge-harmonyhub.home_platform)
1.  [function <span class="apidocSignatureSpan">homebridge-harmonyhub.</span>home_platform ()](#apidoc.element.homebridge-harmonyhub.home_platform.home_platform)
1.  [function <span class="apidocSignatureSpan">homebridge-harmonyhub.home_platform.</span>HomePlatform (log, config, api)](#apidoc.element.homebridge-harmonyhub.home_platform.HomePlatform)
1.  object <span class="apidocSignatureSpan">homebridge-harmonyhub.home_platform.</span>Events

#### [module homebridge-harmonyhub.hub](#apidoc.module.homebridge-harmonyhub.hub)
1.  [function <span class="apidocSignatureSpan">homebridge-harmonyhub.</span>hub (exportedTypes)](#apidoc.element.homebridge-harmonyhub.hub.hub)
1.  [function <span class="apidocSignatureSpan">homebridge-harmonyhub.hub.</span>Hub (log, connection)](#apidoc.element.homebridge-harmonyhub.hub.Hub)

#### [module homebridge-harmonyhub.hub_accessory_base](#apidoc.module.homebridge-harmonyhub.hub_accessory_base)
1.  [function <span class="apidocSignatureSpan">homebridge-harmonyhub.</span>hub_accessory_base (exportedTypes)](#apidoc.element.homebridge-harmonyhub.hub_accessory_base.hub_accessory_base)
1.  [function <span class="apidocSignatureSpan">homebridge-harmonyhub.hub_accessory_base.</span>HubAccessoryBase (accessory, connection, idKey, name, log)](#apidoc.element.homebridge-harmonyhub.hub_accessory_base.HubAccessoryBase)

#### [module homebridge-harmonyhub.hub_connection](#apidoc.module.homebridge-harmonyhub.hub_connection)
1.  [function <span class="apidocSignatureSpan">homebridge-harmonyhub.</span>hub_connection (hubInfo, log, discover)](#apidoc.element.homebridge-harmonyhub.hub_connection.hub_connection)
1.  [function <span class="apidocSignatureSpan">homebridge-harmonyhub.hub_connection.</span>HubConnection (hubInfo, log, discover)](#apidoc.element.homebridge-harmonyhub.hub_connection.HubConnection)
1.  [function <span class="apidocSignatureSpan">homebridge-harmonyhub.hub_connection.</span>createAsync (hubInfo, log, discover)](#apidoc.element.homebridge-harmonyhub.hub_connection.createAsync)
1.  [function <span class="apidocSignatureSpan">homebridge-harmonyhub.hub_connection.</span>super_ ()](#apidoc.element.homebridge-harmonyhub.hub_connection.super_)
1.  object <span class="apidocSignatureSpan">homebridge-harmonyhub.hub_connection.</span>ConnectionStatus
1.  object <span class="apidocSignatureSpan">homebridge-harmonyhub.hub_connection.</span>Events

#### [module homebridge-harmonyhub.hub_connection.prototype](#apidoc.module.homebridge-harmonyhub.hub_connection.prototype)
1.  [function <span class="apidocSignatureSpan">homebridge-harmonyhub.hub_connection.prototype.</span>_HandleConnectionOffline ()](#apidoc.element.homebridge-harmonyhub.hub_connection.prototype._HandleConnectionOffline)
1.  [function <span class="apidocSignatureSpan">homebridge-harmonyhub.hub_connection.prototype.</span>_HandleConnectionOnline ()](#apidoc.element.homebridge-harmonyhub.hub_connection.prototype._HandleConnectionOnline)
1.  [function <span class="apidocSignatureSpan">homebridge-harmonyhub.hub_connection.prototype.</span>_OnConnectionChanged ()](#apidoc.element.homebridge-harmonyhub.hub_connection.prototype._OnConnectionChanged)
1.  [function <span class="apidocSignatureSpan">homebridge-harmonyhub.hub_connection.prototype.</span>_getClientAsync ()](#apidoc.element.homebridge-harmonyhub.hub_connection.prototype._getClientAsync)
1.  [function <span class="apidocSignatureSpan">homebridge-harmonyhub.hub_connection.prototype.</span>connectAsync (hubInfo)](#apidoc.element.homebridge-harmonyhub.hub_connection.prototype.connectAsync)
1.  [function <span class="apidocSignatureSpan">homebridge-harmonyhub.hub_connection.prototype.</span>disconnectAsync ()](#apidoc.element.homebridge-harmonyhub.hub_connection.prototype.disconnectAsync)
1.  [function <span class="apidocSignatureSpan">homebridge-harmonyhub.hub_connection.prototype.</span>invokeAsync (func)](#apidoc.element.homebridge-harmonyhub.hub_connection.prototype.invokeAsync)
1.  [function <span class="apidocSignatureSpan">homebridge-harmonyhub.hub_connection.prototype.</span>refresh ()](#apidoc.element.homebridge-harmonyhub.hub_connection.prototype.refresh)
1.  [function <span class="apidocSignatureSpan">homebridge-harmonyhub.hub_connection.prototype.</span>refreshAsync ()](#apidoc.element.homebridge-harmonyhub.hub_connection.prototype.refreshAsync)

#### [module homebridge-harmonyhub.inherit](#apidoc.module.homebridge-harmonyhub.inherit)
1.  [function <span class="apidocSignatureSpan">homebridge-harmonyhub.inherit.</span>changeBase (Class, BaseClass)](#apidoc.element.homebridge-harmonyhub.inherit.changeBase)
1.  [function <span class="apidocSignatureSpan">homebridge-harmonyhub.inherit.</span>fromInstance (inst, Class)](#apidoc.element.homebridge-harmonyhub.inherit.fromInstance)
1.  [function <span class="apidocSignatureSpan">homebridge-harmonyhub.inherit.</span>mixin (Class, MixinClass, doOverride)](#apidoc.element.homebridge-harmonyhub.inherit.mixin)



# <a name="apidoc.module.homebridge-harmonyhub"></a>[module homebridge-harmonyhub](#apidoc.module.homebridge-harmonyhub)

#### <a name="apidoc.element.homebridge-harmonyhub.accessory_base"></a>[function <span class="apidocSignatureSpan">homebridge-harmonyhub.</span>accessory_base (exportedTypes)](#apidoc.element.homebridge-harmonyhub.accessory_base)
- description and source-code
```javascript
accessory_base = function (exportedTypes) {
	if (exportedTypes && !Accessory) {
		Accessory = exportedTypes.PlatformAccessory || exportedTypes.Accessory;
		Service = exportedTypes.Service;
		Characteristic = exportedTypes.Characteristic;
		uuid = exportedTypes.uuid;
	}
	return AccessoryBase;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.homebridge-harmonyhub.activity_accessory"></a>[function <span class="apidocSignatureSpan">homebridge-harmonyhub.</span>activity_accessory (exportedTypes)](#apidoc.element.homebridge-harmonyhub.activity_accessory)
- description and source-code
```javascript
activity_accessory = function (exportedTypes) {
	if (exportedTypes && !Service) {
		Service = exportedTypes.Service;
		Characteristic = exportedTypes.Characteristic;
		inherit.changeBase(ActivityService, Service.Switch);
		ActivityService.UUID = Service.Switch.UUID;
	}
	return ActivityAccessory;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.homebridge-harmonyhub.home_platform"></a>[function <span class="apidocSignatureSpan">homebridge-harmonyhub.</span>home_platform ()](#apidoc.element.homebridge-harmonyhub.home_platform)
- description and source-code
```javascript
home_platform = function () {
	return HomePlatform;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.homebridge-harmonyhub.hub"></a>[function <span class="apidocSignatureSpan">homebridge-harmonyhub.</span>hub (exportedTypes)](#apidoc.element.homebridge-harmonyhub.hub)
- description and source-code
```javascript
hub = function (exportedTypes) {
	return Hub;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.homebridge-harmonyhub.hub_accessory_base"></a>[function <span class="apidocSignatureSpan">homebridge-harmonyhub.</span>hub_accessory_base (exportedTypes)](#apidoc.element.homebridge-harmonyhub.hub_accessory_base)
- description and source-code
```javascript
hub_accessory_base = function (exportedTypes) {
	if (exportedTypes && !Service) {
		Service = exportedTypes.Service;
		Characteristic = exportedTypes.Characteristic;
	}
	return HubAccessoryBase;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.homebridge-harmonyhub.hub_connection"></a>[function <span class="apidocSignatureSpan">homebridge-harmonyhub.</span>hub_connection (hubInfo, log, discover)](#apidoc.element.homebridge-harmonyhub.hub_connection)
- description and source-code
```javascript
function HubConnection(hubInfo, log, discover) {
	EventEmitter.call(this);
	this.hubId = hubInfo.uuid;
	this.hubInfo = hubInfo;
	this.log = log;
	this._discover = discover;

	var self = this;
	self._discover.on('online', function (info) {
		if (!info || info.uuid != self.hubId) return;
		self._HandleConnectionOnline();
	});

	self._discover.on('offline', function (info) {
		if (!info || info.uuid != self.hubId) return;
		self._HandleConnectionOffline();
	});
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.homebridge-harmonyhub.accessory_base"></a>[module homebridge-harmonyhub.accessory_base](#apidoc.module.homebridge-harmonyhub.accessory_base)

#### <a name="apidoc.element.homebridge-harmonyhub.accessory_base.accessory_base"></a>[function <span class="apidocSignatureSpan">homebridge-harmonyhub.</span>accessory_base (exportedTypes)](#apidoc.element.homebridge-harmonyhub.accessory_base.accessory_base)
- description and source-code
```javascript
accessory_base = function (exportedTypes) {
	if (exportedTypes && !Accessory) {
		Accessory = exportedTypes.PlatformAccessory || exportedTypes.Accessory;
		Service = exportedTypes.Service;
		Characteristic = exportedTypes.Characteristic;
		uuid = exportedTypes.uuid;
	}
	return AccessoryBase;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.homebridge-harmonyhub.accessory_base.AccessoryBase"></a>[function <span class="apidocSignatureSpan">homebridge-harmonyhub.accessory_base.</span>AccessoryBase (accessory, idKey, name, log)](#apidoc.element.homebridge-harmonyhub.accessory_base.AccessoryBase)
- description and source-code
```javascript
function AccessoryBase(accessory, idKey, name, log) {
	this.log = log;

	if (!accessory) {
		var id = uuid.generate(idKey);
		accessory = new Accessory(name, id);
		accessory.name = name;
		accessory.uuid_base = id;
		if (!accessory.getServices) accessory.getServices = getServices.bind(accessory);
	}
	this.accessory = accessory;

	this.accessory.getService(Service.AccessoryInformation)
		.setCharacteristic(Characteristic.Manufacturer, "Logitech")
		.setCharacteristic(Characteristic.Model, "Harmony");
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.homebridge-harmonyhub.activity_accessory"></a>[module homebridge-harmonyhub.activity_accessory](#apidoc.module.homebridge-harmonyhub.activity_accessory)

#### <a name="apidoc.element.homebridge-harmonyhub.activity_accessory.activity_accessory"></a>[function <span class="apidocSignatureSpan">homebridge-harmonyhub.</span>activity_accessory (exportedTypes)](#apidoc.element.homebridge-harmonyhub.activity_accessory.activity_accessory)
- description and source-code
```javascript
activity_accessory = function (exportedTypes) {
	if (exportedTypes && !Service) {
		Service = exportedTypes.Service;
		Characteristic = exportedTypes.Characteristic;
		inherit.changeBase(ActivityService, Service.Switch);
		ActivityService.UUID = Service.Switch.UUID;
	}
	return ActivityAccessory;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.homebridge-harmonyhub.activity_accessory.ActivityAccessory"></a>[function <span class="apidocSignatureSpan">homebridge-harmonyhub.activity_accessory.</span>ActivityAccessory (accessory, log, connection)](#apidoc.element.homebridge-harmonyhub.activity_accessory.ActivityAccessory)
- description and source-code
```javascript
function ActivityAccessory(accessory, log, connection) {
	this._onConnectionChanged = onConnectionChanged.bind(this);
	this._onStateChanged = onStateChanged.bind(this);
	HubAccessoryBase.call(this, accessory, connection, ActivityAccessory.typeKey, null, log);
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.homebridge-harmonyhub.bluebird_ext"></a>[module homebridge-harmonyhub.bluebird_ext](#apidoc.module.homebridge-harmonyhub.bluebird_ext)

#### <a name="apidoc.element.homebridge-harmonyhub.bluebird_ext.asBlueBird"></a>[function <span class="apidocSignatureSpan">homebridge-harmonyhub.bluebird_ext.</span>asBlueBird (func)](#apidoc.element.homebridge-harmonyhub.bluebird_ext.asBlueBird)
- description and source-code
```javascript
asBlueBird = function (func) {
	return function() {
		return toBlueBird(func.apply(this, arguments));
	};
}
```
- example usage
```shell
...
	var self = this;
	return new Promise(function(resolve, reject) {
		self.queue.push(resolve);
		startQueueInBackground(self.queue);
	})
	.then(function(cb){
		return self._getClientAsync()
			.then(BluebirdExt.asBlueBird(func))
			.finally(function(){
				setTimeout(cb, 0);
			})
			.catch(function(err){
				throw err;
			});
	});
...
```

#### <a name="apidoc.element.homebridge-harmonyhub.bluebird_ext.toBlueBird"></a>[function <span class="apidocSignatureSpan">homebridge-harmonyhub.bluebird_ext.</span>toBlueBird (promise)](#apidoc.element.homebridge-harmonyhub.bluebird_ext.toBlueBird)
- description and source-code
```javascript
toBlueBird = function (promise) {
	if (!promise || promise instanceof Promise ||
		!promise.then || typeof promise.then !== "function") {
		return promise;
	}
	return new Promise(function(resolve, reject){
		return promise.then(resolve, reject);
	});
}
```
- example usage
```shell
...
	var lastClient = this.client;
	var lastQueue = this.queue;
	this.queue = null;
	this.client = null;
	this._OnConnectionChanged();
	//TODO: Properly cancel running tasks
	if (lastQueue) lastQueue.end();
	if (lastClient) return BluebirdExt.toBlueBird(lastClient.end());
	return Promise.resolve();
};

HubConnection.prototype._getClientAsync = function() {
	var client = this.client;
	if (client) {
		return Promise.resolve(client);
...
```



# <a name="apidoc.module.homebridge-harmonyhub.home_platform"></a>[module homebridge-harmonyhub.home_platform](#apidoc.module.homebridge-harmonyhub.home_platform)

#### <a name="apidoc.element.homebridge-harmonyhub.home_platform.home_platform"></a>[function <span class="apidocSignatureSpan">homebridge-harmonyhub.</span>home_platform ()](#apidoc.element.homebridge-harmonyhub.home_platform.home_platform)
- description and source-code
```javascript
home_platform = function () {
	return HomePlatform;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.homebridge-harmonyhub.home_platform.HomePlatform"></a>[function <span class="apidocSignatureSpan">homebridge-harmonyhub.home_platform.</span>HomePlatform (log, config, api)](#apidoc.element.homebridge-harmonyhub.home_platform.HomePlatform)
- description and source-code
```javascript
function HomePlatform(log, config, api) {
	EventEmitter.call(this);

	this.log = log;

	if (!config) {
		log.warn("Ignoring Harmony Platform setup because it is not configured");
		this.disabled = true;
		return;
	}

	if (singleton) {
		log.warn("Ignoring duplicate Harmony Platform.  Only one platform can be defined.  Multi-Hub support is now built into the platform
, so multiple definitions are no longer required.");
		this.disabled = true;
		return;
	}
	singleton = this;

	if (config.ip_address) {
		log.warn("Specifying ip_address is no longer supported in the platform, so the specified ip_address will be ignored. The platform
 is designed for auto discovery of all hubs on the network.");
	}

	var self = this;

	self._discoveredHubs = [];
	self._cachedAccessories = [];
	self._hubs = {};
	self._hubIndex = [];
	self._isInitialized = false;
	self._autoAddNewHubs = false;

	self._discover = new Discover(61991);

	self._discover.on('update', function (hubs) {
		self.log.debug('received update event from harmonyhubjs-discover. there are ' + hubs.length + ' hubs');
		self._discoveredHubs = hubs;
		_.forEach(self._discoveredHubs, self._handleDiscoveredHubAsync.bind(self));
		self.emit(Events.DiscoveredHubs, hubs);
	});
	
	self._discover.start();

	if (api) {
		// Save the API object as plugin needs to register new accessory via this object.
		self._api = api;

		// Listen to event "didFinishLaunching", this means homebridge already finished loading cached accessories
		// Platform Plugin should only register new accessory that doesn't exist in homebridge after this event.
		// Or start discover new accessories
		self._api.on('didFinishLaunching', self._finishInitialization.bind(self));
	}
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.homebridge-harmonyhub.hub"></a>[module homebridge-harmonyhub.hub](#apidoc.module.homebridge-harmonyhub.hub)

#### <a name="apidoc.element.homebridge-harmonyhub.hub.hub"></a>[function <span class="apidocSignatureSpan">homebridge-harmonyhub.</span>hub (exportedTypes)](#apidoc.element.homebridge-harmonyhub.hub.hub)
- description and source-code
```javascript
hub = function (exportedTypes) {
	return Hub;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.homebridge-harmonyhub.hub.Hub"></a>[function <span class="apidocSignatureSpan">homebridge-harmonyhub.hub.</span>Hub (log, connection)](#apidoc.element.homebridge-harmonyhub.hub.Hub)
- description and source-code
```javascript
function Hub(log, connection) {
	this.connection = connection;
	this.log = log;
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.homebridge-harmonyhub.hub_accessory_base"></a>[module homebridge-harmonyhub.hub_accessory_base](#apidoc.module.homebridge-harmonyhub.hub_accessory_base)

#### <a name="apidoc.element.homebridge-harmonyhub.hub_accessory_base.hub_accessory_base"></a>[function <span class="apidocSignatureSpan">homebridge-harmonyhub.</span>hub_accessory_base (exportedTypes)](#apidoc.element.homebridge-harmonyhub.hub_accessory_base.hub_accessory_base)
- description and source-code
```javascript
hub_accessory_base = function (exportedTypes) {
	if (exportedTypes && !Service) {
		Service = exportedTypes.Service;
		Characteristic = exportedTypes.Characteristic;
	}
	return HubAccessoryBase;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.homebridge-harmonyhub.hub_accessory_base.HubAccessoryBase"></a>[function <span class="apidocSignatureSpan">homebridge-harmonyhub.hub_accessory_base.</span>HubAccessoryBase (accessory, connection, idKey, name, log)](#apidoc.element.homebridge-harmonyhub.hub_accessory_base.HubAccessoryBase)
- description and source-code
```javascript
function HubAccessoryBase(accessory, connection, idKey, name, log) {
	var hubId, hubInfo;
	if (connection) {
		hubId = connection.hubId;
		hubInfo = connection.hubInfo;
	} else if (accessory && accessory.context) {
		hubId = accessory.context.hubId;
		hubInfo = accessory.context.hubInfo;
	}
	AccessoryBase.call(this, accessory, hubId + idKey, name || (hubInfo && hubInfo.friendlyName), log);
	this._refreshConnection = refreshConnection.bind(this);
	this.updateConnection(connection);
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.homebridge-harmonyhub.hub_connection"></a>[module homebridge-harmonyhub.hub_connection](#apidoc.module.homebridge-harmonyhub.hub_connection)

#### <a name="apidoc.element.homebridge-harmonyhub.hub_connection.hub_connection"></a>[function <span class="apidocSignatureSpan">homebridge-harmonyhub.</span>hub_connection (hubInfo, log, discover)](#apidoc.element.homebridge-harmonyhub.hub_connection.hub_connection)
- description and source-code
```javascript
function HubConnection(hubInfo, log, discover) {
	EventEmitter.call(this);
	this.hubId = hubInfo.uuid;
	this.hubInfo = hubInfo;
	this.log = log;
	this._discover = discover;

	var self = this;
	self._discover.on('online', function (info) {
		if (!info || info.uuid != self.hubId) return;
		self._HandleConnectionOnline();
	});

	self._discover.on('offline', function (info) {
		if (!info || info.uuid != self.hubId) return;
		self._HandleConnectionOffline();
	});
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.homebridge-harmonyhub.hub_connection.HubConnection"></a>[function <span class="apidocSignatureSpan">homebridge-harmonyhub.hub_connection.</span>HubConnection (hubInfo, log, discover)](#apidoc.element.homebridge-harmonyhub.hub_connection.HubConnection)
- description and source-code
```javascript
function HubConnection(hubInfo, log, discover) {
	EventEmitter.call(this);
	this.hubId = hubInfo.uuid;
	this.hubInfo = hubInfo;
	this.log = log;
	this._discover = discover;

	var self = this;
	self._discover.on('online', function (info) {
		if (!info || info.uuid != self.hubId) return;
		self._HandleConnectionOnline();
	});

	self._discover.on('offline', function (info) {
		if (!info || info.uuid != self.hubId) return;
		self._HandleConnectionOffline();
	});
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.homebridge-harmonyhub.hub_connection.createAsync"></a>[function <span class="apidocSignatureSpan">homebridge-harmonyhub.hub_connection.</span>createAsync (hubInfo, log, discover)](#apidoc.element.homebridge-harmonyhub.hub_connection.createAsync)
- description and source-code
```javascript
createAsync = function (hubInfo, log, discover) {
	var conn = new HubConnection(hubInfo, log, discover);
	return conn.connectAsync(hubInfo)
		.return(conn);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.homebridge-harmonyhub.hub_connection.super_"></a>[function <span class="apidocSignatureSpan">homebridge-harmonyhub.hub_connection.</span>super_ ()](#apidoc.element.homebridge-harmonyhub.hub_connection.super_)
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



# <a name="apidoc.module.homebridge-harmonyhub.hub_connection.prototype"></a>[module homebridge-harmonyhub.hub_connection.prototype](#apidoc.module.homebridge-harmonyhub.hub_connection.prototype)

#### <a name="apidoc.element.homebridge-harmonyhub.hub_connection.prototype._HandleConnectionOffline"></a>[function <span class="apidocSignatureSpan">homebridge-harmonyhub.hub_connection.prototype.</span>_HandleConnectionOffline ()](#apidoc.element.homebridge-harmonyhub.hub_connection.prototype._HandleConnectionOffline)
- description and source-code
```javascript
_HandleConnectionOffline = function () {
	this.log.debug('client for hub ' + this.hubInfo.uuid + ' went offline. re-establish.');
	this.client = undefined;
	return this.refresh();
}
```
- example usage
```shell
...
	self._discover.on('online', function (info) {
		if (!info || info.uuid != self.hubId) return;
		self._HandleConnectionOnline();
	});

	self._discover.on('offline', function (info) {
		if (!info || info.uuid != self.hubId) return;
		self._HandleConnectionOffline();
	});
}

util.inherits(HubConnection, EventEmitter);

HubConnection.createAsync = function(hubInfo, log, discover) {
	var conn = new HubConnection(hubInfo, log, discover);
...
```

#### <a name="apidoc.element.homebridge-harmonyhub.hub_connection.prototype._HandleConnectionOnline"></a>[function <span class="apidocSignatureSpan">homebridge-harmonyhub.hub_connection.prototype.</span>_HandleConnectionOnline ()](#apidoc.element.homebridge-harmonyhub.hub_connection.prototype._HandleConnectionOnline)
- description and source-code
```javascript
_HandleConnectionOnline = function () {
	this.log.debug("Hub went online: " + this.hubId);
	return this.refresh();
}
```
- example usage
```shell
...
	this.hubInfo = hubInfo;
	this.log = log;
	this._discover = discover;

	var self = this;
	self._discover.on('online', function (info) {
		if (!info || info.uuid != self.hubId) return;
		self._HandleConnectionOnline();
	});

	self._discover.on('offline', function (info) {
		if (!info || info.uuid != self.hubId) return;
		self._HandleConnectionOffline();
	});
}
...
```

#### <a name="apidoc.element.homebridge-harmonyhub.hub_connection.prototype._OnConnectionChanged"></a>[function <span class="apidocSignatureSpan">homebridge-harmonyhub.hub_connection.prototype.</span>_OnConnectionChanged ()](#apidoc.element.homebridge-harmonyhub.hub_connection.prototype._OnConnectionChanged)
- description and source-code
```javascript
_OnConnectionChanged = function () {
	var last = this._lastStatus;
	var status = this.status;
	if (last == status) return;
	this._lastStatus = status;
	this.emit(Events.ConnectionChanged, status);
}
```
- example usage
```shell
...
};

HubConnection.prototype.disconnectAsync = function() {
	var lastClient = this.client;
	var lastQueue = this.queue;
	this.queue = null;
	this.client = null;
	this._OnConnectionChanged();
	//TODO: Properly cancel running tasks
	if (lastQueue) lastQueue.end();
	if (lastClient) return BluebirdExt.toBlueBird(lastClient.end());
	return Promise.resolve();
};

HubConnection.prototype._getClientAsync = function() {
...
```

#### <a name="apidoc.element.homebridge-harmonyhub.hub_connection.prototype._getClientAsync"></a>[function <span class="apidocSignatureSpan">homebridge-harmonyhub.hub_connection.prototype.</span>_getClientAsync ()](#apidoc.element.homebridge-harmonyhub.hub_connection.prototype._getClientAsync)
- description and source-code
```javascript
_getClientAsync = function () {
	var client = this.client;
	if (client) {
		return Promise.resolve(client);
	}
	var connTask = this._connTask;
	if (connTask) {
		return connTask;
	}
	var self = this;
	connTask = BluebirdExt.toBlueBird(Client(self.hubInfo.ip))
		.then(function (client) {
			self.log.debug('created new client for hub with uuid ' + self.hubId);

			client._xmppClient.on('offline', self._HandleConnectionOffline.bind(self));

			client.on('stateDigest', function (stateDigest) {
				self.log.debug('got state digest. reemit it');
				self.emit(Events.StateDigest, {
					stateDigest: stateDigest
				});
			});
			self.client = client;
			return client;
		});
	this._connTask = connTask;
	this._OnConnectionChanged();
	return connTask
		.timeout(30 * 1000)
		.finally(function() {
			if (self._connTask == connTask) {
				self._connTask = null;
			}
			self._OnConnectionChanged();
		});
}
```
- example usage
```shell
...
HubConnection.prototype.invokeAsync = function(func) {
	var self = this;
	return new Promise(function(resolve, reject) {
		self.queue.push(resolve);
		startQueueInBackground(self.queue);
	})
	.then(function(cb){
		return self._getClientAsync()
			.then(BluebirdExt.asBlueBird(func))
			.finally(function(){
				setTimeout(cb, 0);
			})
			.catch(function(err){
				throw err;
			});
...
```

#### <a name="apidoc.element.homebridge-harmonyhub.hub_connection.prototype.connectAsync"></a>[function <span class="apidocSignatureSpan">homebridge-harmonyhub.hub_connection.prototype.</span>connectAsync (hubInfo)](#apidoc.element.homebridge-harmonyhub.hub_connection.prototype.connectAsync)
- description and source-code
```javascript
connectAsync = function (hubInfo) {
	this.hubInfo = hubInfo;
	this.client = null;
	this.queue = new Queue();
	this.queue.concurrency = 1;
	return this.refreshAsync();
}
```
- example usage
```shell
...
		hub = new Hub(this.log, conn);
		this._hubs[hubId] = hub;
		this._hubIndex.push(hubId);
	} else {
		hub.updateConnection(conn);
	}

	return conn.connectAsync(hubInfo)
		.then(this._refreshHubAccessoriesAsync.bind(this, hubId, hub, true));
};

HomePlatform.prototype._refreshHubAccessoriesAsync = function(hubId, hub, doRegister) {
	var self = this;
	var cachedAccList = _.filter(self._cachedAccessories, function(acc) {
		return acc && acc.context && acc.context.hubId == hubId;
...
```

#### <a name="apidoc.element.homebridge-harmonyhub.hub_connection.prototype.disconnectAsync"></a>[function <span class="apidocSignatureSpan">homebridge-harmonyhub.hub_connection.prototype.</span>disconnectAsync ()](#apidoc.element.homebridge-harmonyhub.hub_connection.prototype.disconnectAsync)
- description and source-code
```javascript
disconnectAsync = function () {
	var lastClient = this.client;
	var lastQueue = this.queue;
	this.queue = null;
	this.client = null;
	this._OnConnectionChanged();
	//TODO: Properly cancel running tasks
	if (lastQueue) lastQueue.end();
	if (lastClient) return BluebirdExt.toBlueBird(lastClient.end());
	return Promise.resolve();
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.homebridge-harmonyhub.hub_connection.prototype.invokeAsync"></a>[function <span class="apidocSignatureSpan">homebridge-harmonyhub.hub_connection.prototype.</span>invokeAsync (func)](#apidoc.element.homebridge-harmonyhub.hub_connection.prototype.invokeAsync)
- description and source-code
```javascript
invokeAsync = function (func) {
	var self = this;
	return new Promise(function(resolve, reject) {
		self.queue.push(resolve);
		startQueueInBackground(self.queue);
	})
	.then(function(cb){
		return self._getClientAsync()
			.then(BluebirdExt.asBlueBird(func))
			.finally(function(){
				setTimeout(cb, 0);
			})
			.catch(function(err){
				throw err;
			});
	});
}
```
- example usage
```shell
...

ActivityAccessory.prototype.initAsync = function() {
	if (!this.connection) return Promise.resolve();

	this.log("Fetching Logitech Harmony activities...");
	var self = this;
	return Promise.all([
			this.connection.invokeAsync(function(client){
				return client.getActivities();
			}),
			this.connection.invokeAsync(function(client){
				return client.getCurrentActivity();
			})
		])
		.bind(this)
...
```

#### <a name="apidoc.element.homebridge-harmonyhub.hub_connection.prototype.refresh"></a>[function <span class="apidocSignatureSpan">homebridge-harmonyhub.hub_connection.prototype.</span>refresh ()](#apidoc.element.homebridge-harmonyhub.hub_connection.prototype.refresh)
- description and source-code
```javascript
refresh = function () {
	var self = this;
	this.refreshAsync()
		.catch(function(err) {
			self.log.debug(err);
			self._OnConnectionChanged();
		});
}
```
- example usage
```shell
...
		if (this.hubInfo) return ConnectionStatus.Disconnected;
		return ConnectionStatus.Unknown;
	}
});

HubConnection.prototype._HandleConnectionOnline = function() {
	this.log.debug("Hub went online: " + this.hubId);
	return this.refresh();
};

HubConnection.prototype._HandleConnectionOffline = function() {
	this.log.debug('client for hub ' + this.hubInfo.uuid + ' went offline. re-establish.');
	this.client = undefined;
	return this.refresh();
};
...
```

#### <a name="apidoc.element.homebridge-harmonyhub.hub_connection.prototype.refreshAsync"></a>[function <span class="apidocSignatureSpan">homebridge-harmonyhub.hub_connection.prototype.</span>refreshAsync ()](#apidoc.element.homebridge-harmonyhub.hub_connection.prototype.refreshAsync)
- description and source-code
```javascript
refreshAsync = function () {
	this._OnConnectionChanged();
	return this.invokeAsync(function(client){
		return client;
	});
}
```
- example usage
```shell
...
};

HubConnection.prototype.connectAsync = function(hubInfo) {
	this.hubInfo = hubInfo;
	this.client = null;
	this.queue = new Queue();
	this.queue.concurrency = 1;
	return this.refreshAsync();
};

HubConnection.prototype.disconnectAsync = function() {
	var lastClient = this.client;
	var lastQueue = this.queue;
	this.queue = null;
	this.client = null;
...
```



# <a name="apidoc.module.homebridge-harmonyhub.inherit"></a>[module homebridge-harmonyhub.inherit](#apidoc.module.homebridge-harmonyhub.inherit)

#### <a name="apidoc.element.homebridge-harmonyhub.inherit.changeBase"></a>[function <span class="apidocSignatureSpan">homebridge-harmonyhub.inherit.</span>changeBase (Class, BaseClass)](#apidoc.element.homebridge-harmonyhub.inherit.changeBase)
- description and source-code
```javascript
changeBase = function (Class, BaseClass) {
	var orig = Class.prototype;
	util.inherits(Class, BaseClass);
	Class.prototype.parent = BaseClass.prototype;
	mixin(Class, orig, true);
}
```
- example usage
```shell
...

var Service, Characteristic;

module.exports = function(exportedTypes) {
	if (exportedTypes && !Service) {
		Service = exportedTypes.Service;
		Characteristic = exportedTypes.Characteristic;
		inherit.changeBase(ActivityService, Service.Switch);
		ActivityService.UUID = Service.Switch.UUID;
	}
	return ActivityAccessory;
};
module.exports.ActivityAccessory = ActivityAccessory;

const ActivityStatus = {
...
```

#### <a name="apidoc.element.homebridge-harmonyhub.inherit.fromInstance"></a>[function <span class="apidocSignatureSpan">homebridge-harmonyhub.inherit.</span>fromInstance (inst, Class)](#apidoc.element.homebridge-harmonyhub.inherit.fromInstance)
- description and source-code
```javascript
fromInstance = function (inst, Class) {
	if (inst == null) {
		return null;
	}
	if (!(inst instanceof Class)) {
		throw new Error("Incorrect type. Expected " + Class);
	}
	mixin(inst, Class, false);
	return inst;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.homebridge-harmonyhub.inherit.mixin"></a>[function <span class="apidocSignatureSpan">homebridge-harmonyhub.inherit.</span>mixin (Class, MixinClass, doOverride)](#apidoc.element.homebridge-harmonyhub.inherit.mixin)
- description and source-code
```javascript
mixin = function (Class, MixinClass, doOverride) {
	var mixinMethods = MixinClass.prototype || MixinClass;
	var cls = Class.prototype || Class;
	for (var mn in mixinMethods) {
		if (!doOverride && cls[mn] != undefined) return;
		cls[mn] = mixinMethods[mn];
	}
}
```
- example usage
```shell
n/a
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
