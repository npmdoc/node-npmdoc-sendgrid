# api documentation for  [sendgrid (v5.0.0)](https://sendgrid.com)  [![npm package](https://img.shields.io/npm/v/npmdoc-sendgrid.svg?style=flat-square)](https://www.npmjs.org/package/npmdoc-sendgrid) [![travis-ci.org build-status](https://api.travis-ci.org/npmdoc/node-npmdoc-sendgrid.svg)](https://travis-ci.org/npmdoc/node-npmdoc-sendgrid)
#### Official SendGrid NodeJS library.

[![NPM](https://nodei.co/npm/sendgrid.png?downloads=true)](https://www.npmjs.com/package/sendgrid)

[![apidoc](https://npmdoc.github.io/node-npmdoc-sendgrid/build/screenCapture.buildNpmdoc.browser._2Fhome_2Ftravis_2Fbuild_2Fnpmdoc_2Fnode-npmdoc-sendgrid_2Ftmp_2Fbuild_2Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-sendgrid/build/apidoc.html)

![npmPackageListing](https://npmdoc.github.io/node-npmdoc-sendgrid/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmdoc.github.io/node-npmdoc-sendgrid/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "SendGrid",
        "email": "dx@sendgrid.com",
        "url": "sendgrid.com"
    },
    "bugs": {
        "url": "https://github.com/sendgrid/sendgrid-nodejs/issues"
    },
    "contributors": [
        {
            "name": "Kyle Partridge",
            "email": "kyle.partridge@sendgrid.com"
        },
        {
            "name": "David Tomberlin",
            "email": "david.tomberlin@sendgrid.com"
        },
        {
            "name": "Swift",
            "email": "swift@sendgrid.com"
        },
        {
            "name": "Brandon West",
            "email": "brandon.west@sendgrid.com"
        },
        {
            "name": "Scott Motte",
            "email": "scott.motte@sendgrid.com"
        },
        {
            "name": "Robert Acosta",
            "email": "robert.acosta@sendgrid.com"
        },
        {
            "name": "Elmer Thomas",
            "email": "elmer.thomas@sendgrid.com"
        },
        {
            "name": "Adam Buczynski",
            "email": "me@adambuczynski.com"
        }
    ],
    "dependencies": {
        "async.ensureasync": "^0.5.2",
        "async.queue": "^0.5.2",
        "bottleneck": "^1.12.0",
        "debug": "^2.2.0",
        "lodash.chunk": "^4.2.0",
        "mailparser": "^0.6.1",
        "sendgrid-rest": "^2.3.0"
    },
    "description": "Official SendGrid NodeJS library.",
    "devDependencies": {
        "chai": "^3.5.0",
        "eslint": "^3.1.0",
        "mocha": "^2.4.5",
        "mocha-sinon": "^1.1.5",
        "sinon": "^1.17.5",
        "sinon-chai": "^2.8.0",
        "typescript": "^2.0.0"
    },
    "directories": {},
    "dist": {
        "shasum": "4dd1fea1c5d83d875b357659d086c46198d414d0",
        "tarball": "https://registry.npmjs.org/sendgrid/-/sendgrid-5.0.0.tgz"
    },
    "engines": {
        "node": ">= 4.0.0"
    },
    "gitHead": "6291b2058900a85771f6ea986de9b2d8c933b871",
    "homepage": "https://sendgrid.com",
    "license": "MIT",
    "maintainers": [
        {
            "name": "siyegen",
            "email": "siyegen@gmail.com"
        },
        {
            "name": "motdotla",
            "email": "mot@mot.la"
        },
        {
            "name": "eddiezane",
            "email": "eddiezane@gmail.com"
        },
        {
            "name": "elbuo8",
            "email": "yamil.asusta@upr.edu"
        },
        {
            "name": "partkyle",
            "email": "partkyle@gmail.com"
        },
        {
            "name": "theycallmeswift",
            "email": "theycallmeswift@gmail.com"
        },
        {
            "name": "scottmotte",
            "email": "scott@scottmotte.com"
        },
        {
            "name": "nquinlan",
            "email": "nick@nicholasquinlan.com"
        },
        {
            "name": "mkbernier",
            "email": "mkbernier@gmail.com"
        },
        {
            "name": "thinkingserious",
            "email": "elmer@thinkingserious.com"
        }
    ],
    "name": "sendgrid",
    "optionalDependencies": {},
    "readme": "ERROR: No README data found!",
    "repository": {
        "type": "git",
        "url": "git://github.com/sendgrid/sendgrid-nodejs.git"
    },
    "scripts": {
        "lint": "eslint . --fix",
        "test": "mocha",
        "test:typescript": "tsc"
    },
    "tags": [
        "http",
        "rest",
        "api"
    ],
    "typings": "index.d.ts",
    "version": "5.0.0"
}
```



# <a name="apidoc.tableOfContents"></a>[table of contents](#apidoc.tableOfContents)

#### [module sendgrid](#apidoc.module.sendgrid)
1.  [function <span class="apidocSignatureSpan">sendgrid.</span>Promise ()](#apidoc.element.sendgrid.Promise)
1.  [function <span class="apidocSignatureSpan">sendgrid.</span>importer (sg, options)](#apidoc.element.sendgrid.importer)
1.  [function <span class="apidocSignatureSpan">sendgrid.</span>parse (config, request)](#apidoc.element.sendgrid.parse)
1.  object <span class="apidocSignatureSpan">sendgrid.</span>importer.prototype
1.  object <span class="apidocSignatureSpan">sendgrid.</span>mail
1.  object <span class="apidocSignatureSpan">sendgrid.</span>parse.prototype

#### [module sendgrid.importer](#apidoc.module.sendgrid.importer)
1.  [function <span class="apidocSignatureSpan">sendgrid.</span>importer (sg, options)](#apidoc.element.sendgrid.importer.importer)
1.  [function <span class="apidocSignatureSpan">sendgrid.importer.</span>super_ ()](#apidoc.element.sendgrid.importer.super_)

#### [module sendgrid.importer.prototype](#apidoc.module.sendgrid.importer.prototype)
1.  [function <span class="apidocSignatureSpan">sendgrid.importer.prototype.</span>_notify (error, result, batch)](#apidoc.element.sendgrid.importer.prototype._notify)
1.  [function <span class="apidocSignatureSpan">sendgrid.importer.prototype.</span>_sendBatch (context, data, callback)](#apidoc.element.sendgrid.importer.prototype._sendBatch)
1.  [function <span class="apidocSignatureSpan">sendgrid.importer.prototype.</span>_worker (task, callback)](#apidoc.element.sendgrid.importer.prototype._worker)
1.  [function <span class="apidocSignatureSpan">sendgrid.importer.prototype.</span>push (data)](#apidoc.element.sendgrid.importer.prototype.push)

#### [module sendgrid.mail](#apidoc.module.sendgrid.mail)
1.  [function <span class="apidocSignatureSpan">sendgrid.mail.</span>Asm (group_id, groups_to_display)](#apidoc.element.sendgrid.mail.Asm)
1.  [function <span class="apidocSignatureSpan">sendgrid.mail.</span>Attachment ()](#apidoc.element.sendgrid.mail.Attachment)
1.  [function <span class="apidocSignatureSpan">sendgrid.mail.</span>Bcc (enable, email)](#apidoc.element.sendgrid.mail.Bcc)
1.  [function <span class="apidocSignatureSpan">sendgrid.mail.</span>BypassListManagement (enable)](#apidoc.element.sendgrid.mail.BypassListManagement)
1.  [function <span class="apidocSignatureSpan">sendgrid.mail.</span>Category (name)](#apidoc.element.sendgrid.mail.Category)
1.  [function <span class="apidocSignatureSpan">sendgrid.mail.</span>ClickTracking (enable, enable_text)](#apidoc.element.sendgrid.mail.ClickTracking)
1.  [function <span class="apidocSignatureSpan">sendgrid.mail.</span>Content (type, value)](#apidoc.element.sendgrid.mail.Content)
1.  [function <span class="apidocSignatureSpan">sendgrid.mail.</span>CustomArgs (key, value)](#apidoc.element.sendgrid.mail.CustomArgs)
1.  [function <span class="apidocSignatureSpan">sendgrid.mail.</span>Email (email, name)](#apidoc.element.sendgrid.mail.Email)
1.  [function <span class="apidocSignatureSpan">sendgrid.mail.</span>Footer (enable, text, html)](#apidoc.element.sendgrid.mail.Footer)
1.  [function <span class="apidocSignatureSpan">sendgrid.mail.</span>Ganalytics ( enable, utm_source, utm_medium, utm_term, utm_content, utm_campaign )](#apidoc.element.sendgrid.mail.Ganalytics)
1.  [function <span class="apidocSignatureSpan">sendgrid.mail.</span>Header (key, value)](#apidoc.element.sendgrid.mail.Header)
1.  [function <span class="apidocSignatureSpan">sendgrid.mail.</span>Mail (from_email, subject, to_email, content)](#apidoc.element.sendgrid.mail.Mail)
1.  [function <span class="apidocSignatureSpan">sendgrid.mail.</span>MailSettings ()](#apidoc.element.sendgrid.mail.MailSettings)
1.  [function <span class="apidocSignatureSpan">sendgrid.mail.</span>OpenTracking (enable, substitution_tag)](#apidoc.element.sendgrid.mail.OpenTracking)
1.  [function <span class="apidocSignatureSpan">sendgrid.mail.</span>Personalization ()](#apidoc.element.sendgrid.mail.Personalization)
1.  [function <span class="apidocSignatureSpan">sendgrid.mail.</span>SandBoxMode (enable)](#apidoc.element.sendgrid.mail.SandBoxMode)
1.  [function <span class="apidocSignatureSpan">sendgrid.mail.</span>Section (key, value)](#apidoc.element.sendgrid.mail.Section)
1.  [function <span class="apidocSignatureSpan">sendgrid.mail.</span>SpamCheck (enable, threshold, post_to_url)](#apidoc.element.sendgrid.mail.SpamCheck)
1.  [function <span class="apidocSignatureSpan">sendgrid.mail.</span>SubscriptionTracking (enable, text, html, substitution_tag)](#apidoc.element.sendgrid.mail.SubscriptionTracking)
1.  [function <span class="apidocSignatureSpan">sendgrid.mail.</span>Substitution (key, value)](#apidoc.element.sendgrid.mail.Substitution)
1.  [function <span class="apidocSignatureSpan">sendgrid.mail.</span>TrackingSettings ()](#apidoc.element.sendgrid.mail.TrackingSettings)

#### [module sendgrid.parse](#apidoc.module.sendgrid.parse)
1.  [function <span class="apidocSignatureSpan">sendgrid.</span>parse (config, request)](#apidoc.element.sendgrid.parse.parse)

#### [module sendgrid.parse.prototype](#apidoc.module.sendgrid.parse.prototype)
1.  [function <span class="apidocSignatureSpan">sendgrid.parse.prototype.</span>_getAttachments (callback)](#apidoc.element.sendgrid.parse.prototype._getAttachments)
1.  [function <span class="apidocSignatureSpan">sendgrid.parse.prototype.</span>_getAttachmentsRaw (callback)](#apidoc.element.sendgrid.parse.prototype._getAttachmentsRaw)
1.  [function <span class="apidocSignatureSpan">sendgrid.parse.prototype.</span>attachments (callback)](#apidoc.element.sendgrid.parse.prototype.attachments)
1.  [function <span class="apidocSignatureSpan">sendgrid.parse.prototype.</span>getRawEmail (callback)](#apidoc.element.sendgrid.parse.prototype.getRawEmail)
1.  [function <span class="apidocSignatureSpan">sendgrid.parse.prototype.</span>hasRawEmail ()](#apidoc.element.sendgrid.parse.prototype.hasRawEmail)
1.  [function <span class="apidocSignatureSpan">sendgrid.parse.prototype.</span>keyValues ()](#apidoc.element.sendgrid.parse.prototype.keyValues)



# <a name="apidoc.module.sendgrid"></a>[module sendgrid](#apidoc.module.sendgrid)

#### <a name="apidoc.element.sendgrid.Promise"></a>[function <span class="apidocSignatureSpan">sendgrid.</span>Promise ()](#apidoc.element.sendgrid.Promise)
- description and source-code
```javascript
function Promise() { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sendgrid.importer"></a>[function <span class="apidocSignatureSpan">sendgrid.</span>importer (sg, options)](#apidoc.element.sendgrid.importer)
- description and source-code
```javascript
importer = function (sg, options) {
  options = options || {};
  var self = this;
  this.sg = sg;
  this.pendingItems = [];

  // Number of items to send per batch.
  this.batchSize = options.batchSize || 1500;

  // Max number of requests per rate limit period.
  this.rateLimitLimit = options.rateLimitLimit || 3;

  // Length of rate limit period (miliseconds).
  this.rateLimitPeriod = options.rateLimitPeriod || 2000;

  // Create a throttler that will process no more than 'rateLimitLimit' requests every 'rateLimitPeriod' ms.
  this.throttle = new Bottleneck(0, 0);
  this.throttle.changeReservoir(this.rateLimitLimit);

  // Create a queue that wil be used to send batches to the throttler.
  this.queue = queue(ensureAsync(this._worker));

  // When the last batch is removed from the queue, add any incomplete batches.
  this.queue.empty = function() {
    if (self.pendingItems.length) {
      debug('adding %s items from deferrd queue for processing', self.pendingItems.length);
      var batch = self.pendingItems.splice(0);
      self.queue.push({
        data: batch,
        owner: self,
      }, function(error, result) {
        if (error) {
          return self._notify(error, JSON.parse(error.response.body), batch);
        }
        return self._notify(null, JSON.parse(result.body), batch);
      });
    }
  };

  // Emit an event when the queue is drained.
  this.queue.drain = function() {
    self.emit('drain');
  };
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sendgrid.parse"></a>[function <span class="apidocSignatureSpan">sendgrid.</span>parse (config, request)](#apidoc.element.sendgrid.parse)
- description and source-code
```javascript
function Parse(config, request) {
  this.keys = config.keys;
  this.request = request;
  this.payload = request.body || {};
  this.files = request.files || [];
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.sendgrid.importer"></a>[module sendgrid.importer](#apidoc.module.sendgrid.importer)

#### <a name="apidoc.element.sendgrid.importer.importer"></a>[function <span class="apidocSignatureSpan">sendgrid.</span>importer (sg, options)](#apidoc.element.sendgrid.importer.importer)
- description and source-code
```javascript
importer = function (sg, options) {
  options = options || {};
  var self = this;
  this.sg = sg;
  this.pendingItems = [];

  // Number of items to send per batch.
  this.batchSize = options.batchSize || 1500;

  // Max number of requests per rate limit period.
  this.rateLimitLimit = options.rateLimitLimit || 3;

  // Length of rate limit period (miliseconds).
  this.rateLimitPeriod = options.rateLimitPeriod || 2000;

  // Create a throttler that will process no more than 'rateLimitLimit' requests every 'rateLimitPeriod' ms.
  this.throttle = new Bottleneck(0, 0);
  this.throttle.changeReservoir(this.rateLimitLimit);

  // Create a queue that wil be used to send batches to the throttler.
  this.queue = queue(ensureAsync(this._worker));

  // When the last batch is removed from the queue, add any incomplete batches.
  this.queue.empty = function() {
    if (self.pendingItems.length) {
      debug('adding %s items from deferrd queue for processing', self.pendingItems.length);
      var batch = self.pendingItems.splice(0);
      self.queue.push({
        data: batch,
        owner: self,
      }, function(error, result) {
        if (error) {
          return self._notify(error, JSON.parse(error.response.body), batch);
        }
        return self._notify(null, JSON.parse(result.body), batch);
      });
    }
  };

  // Emit an event when the queue is drained.
  this.queue.drain = function() {
    self.emit('drain');
  };
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sendgrid.importer.super_"></a>[function <span class="apidocSignatureSpan">sendgrid.importer.</span>super_ ()](#apidoc.element.sendgrid.importer.super_)
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



# <a name="apidoc.module.sendgrid.importer.prototype"></a>[module sendgrid.importer.prototype](#apidoc.module.sendgrid.importer.prototype)

#### <a name="apidoc.element.sendgrid.importer.prototype._notify"></a>[function <span class="apidocSignatureSpan">sendgrid.importer.prototype.</span>_notify (error, result, batch)](#apidoc.element.sendgrid.importer.prototype._notify)
- description and source-code
```javascript
_notify = function (error, result, batch) {
  if (error) {
    return this.emit('error', error, batch);
  }
  return this.emit('success', result, batch);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sendgrid.importer.prototype._sendBatch"></a>[function <span class="apidocSignatureSpan">sendgrid.importer.prototype.</span>_sendBatch (context, data, callback)](#apidoc.element.sendgrid.importer.prototype._sendBatch)
- description and source-code
```javascript
_sendBatch = function (context, data, callback) {
  debug('sending batch (%s items)', data.length);

  var request = context.sg.emptyRequest();
  request.method = 'POST';
  request.path = '/v3/contactdb/recipients';
  request.body = data;

  context.sg.API(request)
    .then(function(response) {
      debug('got response: %o', response);
      setTimeout(function() {
        context.throttle.incrementReservoir(1);
      }, context.rateLimitPeriod);
      return callback(null, response);
    })
    .catch(function(error) {
      debug('got error, %o', error);
      setTimeout(function() {
        context.throttle.incrementReservoir(1);
      }, context.rateLimitPeriod);
      return callback(error);
    });
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sendgrid.importer.prototype._worker"></a>[function <span class="apidocSignatureSpan">sendgrid.importer.prototype.</span>_worker (task, callback)](#apidoc.element.sendgrid.importer.prototype._worker)
- description and source-code
```javascript
_worker = function (task, callback) {
  var context = task.owner;
  debug('processing batch (%s items)', task.data.length);
  context.throttle.submit(context._sendBatch, context, task.data, callback);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sendgrid.importer.prototype.push"></a>[function <span class="apidocSignatureSpan">sendgrid.importer.prototype.</span>push (data)](#apidoc.element.sendgrid.importer.prototype.push)
- description and source-code
```javascript
push = function (data) {
  var self = this;
  data = Array.isArray(data) ? data : [data];

  // Add the new items onto the pending items.
  var itemsToProcess = this.pendingItems.concat(data);

  // Chunk the pending items into batches and add onto the queue
  var batches = chunk(itemsToProcess, this.batchSize);
  debug('generated batches %s from %s items', batches.length, data.length);

  batches.forEach(function(batch) {
    // If this batch is full or the queue is empty queue it for processing.
    if (batch.length === self.batchSize || !self.queue.length()) {
      self.queue.push({
        data: batch,
        owner: self,
      }, function(error, result) {
        if (error) {
          return self._notify(error, JSON.parse(error.response.body), batch);
        }
        return self._notify(null, JSON.parse(result.body), batch);
      });
    }
    // Otherwise, it store it for later.
    else {
      debug('the last batch with only %s item is deferred (partial batch)', batch.length);
      self.pendingItems = batch;
    }
  });

  debug('batches in queue: %s', this.queue.length());
  debug('items in deferred queue: %s', this.pendingItems.length);
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.sendgrid.mail"></a>[module sendgrid.mail](#apidoc.module.sendgrid.mail)

#### <a name="apidoc.element.sendgrid.mail.Asm"></a>[function <span class="apidocSignatureSpan">sendgrid.mail.</span>Asm (group_id, groups_to_display)](#apidoc.element.sendgrid.mail.Asm)
- description and source-code
```javascript
function Asm(group_id, groups_to_display) {
  this.group_id = group_id;
  this.groups_to_display = groups_to_display;

  var json = {
    group_id: this.group_id,
    groups_to_display: this.groups_to_display,
  };

  return json;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sendgrid.mail.Attachment"></a>[function <span class="apidocSignatureSpan">sendgrid.mail.</span>Attachment ()](#apidoc.element.sendgrid.mail.Attachment)
- description and source-code
```javascript
function Attachment() {
  this.content = undefined;
  this.type = undefined;
  this.filename = undefined;
  this.disposition = undefined;
  this.content_id = undefined;

  this.setContent = function(content) {
    this.content = content;
  };

  this.getContent = function() {
    return this.content;
  };

  this.setType = function(type) {
    this.type = type;
  };

  this.getType = function() {
    return this.type;
  };

  this.setFilename = function(filename) {
    this.filename = filename;
  };

  this.getFilename = function() {
    return this.filename;
  };

  this.setDisposition = function(disposition) {
    this.disposition = disposition;
  };

  this.getDisposition = function() {
    return this.disposition;
  };

  this.setContentId = function(content_id) {
    this.content_id = content_id;
  };

  this.getContentId = function() {
    return this.content_id;
  };

  this.toJSON = function() {
    var json = {
      content: this.getContent(),
      type: this.getType(),
      filename: this.getFilename(),
      disposition: this.getDisposition(),
      content_id: this.getContentId(),
    };
    return json;
  };

  return this;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sendgrid.mail.Bcc"></a>[function <span class="apidocSignatureSpan">sendgrid.mail.</span>Bcc (enable, email)](#apidoc.element.sendgrid.mail.Bcc)
- description and source-code
```javascript
function Bcc(enable, email) {
  this.enable = enable;
  this.email = email;

  this.setEnable = function(enable) {
    this.enable = enable;
  };

  this.getEnable = function() {
    return this.enable;
  };

  this.setEmail = function(email) {
    this.email = email;
  };

  this.getEmail = function() {
    return this.email;
  };

  this.toJSON = function() {
    var json = {
      enable: this.getEnable(),
      email: this.getEmail(),
    };
    return json;
  };

  return this;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sendgrid.mail.BypassListManagement"></a>[function <span class="apidocSignatureSpan">sendgrid.mail.</span>BypassListManagement (enable)](#apidoc.element.sendgrid.mail.BypassListManagement)
- description and source-code
```javascript
function BypassListManagement(enable) {
  this.enable = enable;

  var json = {
    enable: this.enable,
  };

  return json;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sendgrid.mail.Category"></a>[function <span class="apidocSignatureSpan">sendgrid.mail.</span>Category (name)](#apidoc.element.sendgrid.mail.Category)
- description and source-code
```javascript
function Category(name) {
  this.category = name;

  var json = {
    category: this.category,
  };

  return json;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sendgrid.mail.ClickTracking"></a>[function <span class="apidocSignatureSpan">sendgrid.mail.</span>ClickTracking (enable, enable_text)](#apidoc.element.sendgrid.mail.ClickTracking)
- description and source-code
```javascript
function ClickTracking(enable, enable_text) {
  this.enable = enable;
  this.enable_text = enable_text;

  this.setEnable = function(enable) {
    this.enable = enable;
  };

  this.getEnable = function() {
    return this.enable;
  };

  this.setEnableText = function(enable_text) {
    this.enable_text = enable_text;
  };

  this.getEnableText = function() {
    return this.enable_text;
  };

  this.toJSON = function() {
    var json = {
      enable: this.getEnable(),
      enable_text: this.getEnableText(),
    };
    return json;
  };

  return this;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sendgrid.mail.Content"></a>[function <span class="apidocSignatureSpan">sendgrid.mail.</span>Content (type, value)](#apidoc.element.sendgrid.mail.Content)
- description and source-code
```javascript
function Content(type, value) {
  this.type = type;
  this.value = value;

  var json = {
    type: this.type,
    value: this.value,
  };

  return json;
}
```
- example usage
```shell
...
### With Mail Helper Class

'''javascript
var helper = require('sendgrid').mail;
var from_email = new helper.Email('test@example.com');
var to_email = new helper.Email('test@example.com');
var subject = 'Hello World from the SendGrid Node.js Library!';
var content = new helper.Content('text/plain', 'Hello, Email!');
var mail = new helper.Mail(from_email, subject, to_email, content);

var sg = require('sendgrid')(process.env.SENDGRID_API_KEY);
var request = sg.emptyRequest({
method: 'POST',
path: '/v3/mail/send',
body: mail.toJSON(),
...
```

#### <a name="apidoc.element.sendgrid.mail.CustomArgs"></a>[function <span class="apidocSignatureSpan">sendgrid.mail.</span>CustomArgs (key, value)](#apidoc.element.sendgrid.mail.CustomArgs)
- description and source-code
```javascript
function CustomArgs(key, value) {
  this.key = key;
  this.value = value;

  var json = {};
  json[this.key] = this.value;

  return json;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sendgrid.mail.Email"></a>[function <span class="apidocSignatureSpan">sendgrid.mail.</span>Email (email, name)](#apidoc.element.sendgrid.mail.Email)
- description and source-code
```javascript
function Email(email, name) {
  this.name = name;
  this.email = email;

  var json = {
    email: this.email,
    name: this.name,
  };

  return json;
}
```
- example usage
```shell
...

The following is the minimum needed code to send an email with the [/mail/send Helper](https://github.com/sendgrid/sendgrid-nodejs
/tree/master/lib/helpers/mail) ([here](https://github.com/sendgrid/sendgrid-nodejs/blob/master/examples/helpers/mail/example.js#
L15) is a full example):

### With Mail Helper Class

'''javascript
var helper = require('sendgrid').mail;
var from_email = new helper.Email('test@example.com');
var to_email = new helper.Email('test@example.com');
var subject = 'Hello World from the SendGrid Node.js Library!';
var content = new helper.Content('text/plain', 'Hello, Email!');
var mail = new helper.Mail(from_email, subject, to_email, content);

var sg = require('sendgrid')(process.env.SENDGRID_API_KEY);
var request = sg.emptyRequest({
...
```

#### <a name="apidoc.element.sendgrid.mail.Footer"></a>[function <span class="apidocSignatureSpan">sendgrid.mail.</span>Footer (enable, text, html)](#apidoc.element.sendgrid.mail.Footer)
- description and source-code
```javascript
function Footer(enable, text, html) {
  this.enable = enable;
  this.text = text;
  this.html = html;

  this.setEnable = function(enable) {
    this.enable = enable;
  };

  this.getEnable = function() {
    return this.enable;
  };

  this.setText = function(text) {
    this.text = text;
  };

  this.getText = function() {
    return this.text;
  };

  this.setHtml = function(html) {
    this.html = html;
  };

  this.getHtml = function() {
    return this.html;
  };

  this.toJSON = function() {
    var json = {
      enable: this.getEnable(),
      text: this.getText(),
      html: this.getHtml(),
    };
    return json;
  };

  return this;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sendgrid.mail.Ganalytics"></a>[function <span class="apidocSignatureSpan">sendgrid.mail.</span>Ganalytics ( enable, utm_source, utm_medium, utm_term, utm_content, utm_campaign )](#apidoc.element.sendgrid.mail.Ganalytics)
- description and source-code
```javascript
function Ganalytics( enable, utm_source, utm_medium, utm_term, utm_content, utm_campaign ) {
  this.enable = enable;
  this.utm_source = utm_source;
  this.utm_medium = utm_medium;
  this.utm_term = utm_term;
  this.utm_content = utm_content;
  this.utm_campaign = utm_campaign;

  this.setEnable = function(enable) {
    this.enable = enable;
  };

  this.getEnable = function() {
    return this.enable;
  };

  this.setUtmSource = function(utm_source) {
    this.utm_source = utm_source;
  };

  this.getUtmSource = function() {
    return this.utm_source;
  };

  this.setUtmMedium = function(utm_medium) {
    this.utm_medium = utm_medium;
  };

  this.getUtmMedium = function() {
    return this.utm_medium;
  };

  this.setUtmTerm = function(utm_term) {
    this.utm_term = utm_term;
  };

  this.getUtmTerm = function() {
    return this.utm_term;
  };

  this.setUtmContent = function(utm_content) {
    this.utm_content = utm_content;
  };

  this.getUtmContent = function() {
    return this.utm_content;
  };

  this.setUtmCampaign = function(utm_campaign) {
    this.utm_campaign = utm_campaign;
  };

  this.getUtmCampaign = function() {
    return this.utm_campaign;
  };

  this.toJSON = function() {
    var json = {
      enable: this.getEnable(),
      utm_source: this.getUtmSource(),
      utm_medium: this.getUtmMedium(),
      utm_term: this.getUtmTerm(),
      utm_content: this.getUtmContent(),
      utm_campaign: this.getUtmCampaign(),
    };
    return json;
  };

  return this;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sendgrid.mail.Header"></a>[function <span class="apidocSignatureSpan">sendgrid.mail.</span>Header (key, value)](#apidoc.element.sendgrid.mail.Header)
- description and source-code
```javascript
function Header(key, value) {
  this.key = key;
  this.value = value;

  var json = {};
  json[this.key] = this.value;

  return json;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sendgrid.mail.Mail"></a>[function <span class="apidocSignatureSpan">sendgrid.mail.</span>Mail (from_email, subject, to_email, content)](#apidoc.element.sendgrid.mail.Mail)
- description and source-code
```javascript
function Mail(from_email, subject, to_email, content) {
  this.from_email = undefined;
  this.personalizations = undefined;
  this.subject = undefined;
  this.contents = undefined;
  this.attachments = undefined;
  this.template_id = undefined;
  this.sections = undefined;
  this.headers = undefined;
  this.categories = undefined;
  this.send_at = undefined;
  this.batch_id = undefined;
  this.asm = undefined;
  this.ip_pool_name = undefined;
  this.mail_settings = undefined;
  this.reply_to = undefined;

  this.setFrom = function(email) {
    this.from_email = email;
  };

  this.getFrom = function() {
    return this.from_email;
  };

  this.addPersonalization = function(personalization) {
    if (this.personalizations === undefined) {
      this.personalizations = [];
    }
    this.personalizations.push(personalization);
  };

  this.getPersonalizations = function() {
    return this.personalizations;
  };

  this.setSubject = function(subject) {
    this.subject = subject;
  };

  this.getSubject = function() {
    return this.subject;
  };

  this.addContent = function(content) {
    if (this.contents === undefined) {
      this.contents = [];
    }
    this.contents.push(content);
  };

  this.getContents = function() {
    return this.contents;
  };

  this.addAttachment = function(attachment) {
    if (this.attachments === undefined) {
      this.attachments = [];
    }
    this.attachments.push(attachment);
  };

  this.getAttachments = function() {
    return this.attachments;
  };

  this.setTemplateId = function(template_id) {
    this.template_id = template_id;
  };

  this.getTemplateId = function() {
    return this.template_id;
  };

  this.addSection = function(section) {
    if (this.sections === undefined) {
      this.sections = {};
    }
    this.sections[Object.keys(section)[0]] = section[Object.keys(section)[0]];
  };

  this.getSections = function() {
    return this.sections;
  };

  this.addHeader = function(header) {
    if (this.headers === undefined) {
      this.headers = {};
    }
    this.headers[Object.keys(header)[0]] = header[Object.keys(header)[0]];
  };

  this.getHeaders = function() {
    return this.headers;
  };

  this.addCategory = function(category) {
    if (this.categories === undefined) {
      this.categories = [];
    }
    this.categories.push(category.category);
  };

  this.getCategories = function() {
    return this.categories;
  };

  this.addCustomArg = function(custom_arg) {
    if (this.custom_args === undefined) {
      this.custom_args = {};
    }
    this.custom_args[Object.keys(custom_arg)[0]] =
      custom_arg[Object.keys(custom_arg)[0]];
  };

  this.getCustomArgs = function() {
    return this.custom_args;
  };

  this.setSendAt = function(send_at) {
    this.send_at = send_at;
  };

  this.getSendAt = function() {
    return this.send_at;
  };

  this.setBatchId = function(batch_id) {
    this.batch_id = batch_id;
  };

  this.getBatchId = function() {
    return this.batch_id;
  };

  this.setAsm = function(asm) {
    this.asm = asm;
  };

  this.getAsm = function() {
    return this.asm;
  };

  this.setIpPoolName = function(ip_pool_name) {
    this.ip_pool_name = ip_pool_name;
  };

  this.getIpPoolName = function() {
    return this.ip_pool_name;
  };

  this.addMailSettings = function(mail_settings) {
    this.mail_settings = mail_settings;
  };

  this.getMailSettings = function() {
    return this.mail_settings;
  };

  this.addTrackingSettings = function(tracking_settings) {
    this.tracking_settings = tracking_settings;
  };

  this.getTrackingSettings = function() {
    return this.tracking_settings;
  };

  this.setReplyTo = function(reply_to) {
    this.reply_to = reply_to;
  };

  this.getReplyTo = function() {
    return this.reply_to;
  };

  if (from_email && subject && to_email && content) {
    this.setFrom(from_email);
    var personalization = new Personalization();
    personalization.addTo(to_email);
    this.addPersonalization(personalization);
    this.setSubject(subject);
    this.addContent(content);
  }

  this.toJSON = functi ...
```
- example usage
```shell
...

'''javascript
var helper = require('sendgrid').mail;
var from_email = new helper.Email('test@example.com');
var to_email = new helper.Email('test@example.com');
var subject = 'Hello World from the SendGrid Node.js Library!';
var content = new helper.Content('text/plain', 'Hello, Email!');
var mail = new helper.Mail(from_email, subject, to_email, content);

var sg = require('sendgrid')(process.env.SENDGRID_API_KEY);
var request = sg.emptyRequest({
  method: 'POST',
  path: '/v3/mail/send',
  body: mail.toJSON(),
});
...
```

#### <a name="apidoc.element.sendgrid.mail.MailSettings"></a>[function <span class="apidocSignatureSpan">sendgrid.mail.</span>MailSettings ()](#apidoc.element.sendgrid.mail.MailSettings)
- description and source-code
```javascript
function MailSettings() {
  this.bcc = undefined;
  this.bypass_list_management = undefined;
  this.footer = undefined;
  this.sandbox_mode = undefined;
  this.spam_check = undefined;

  this.setBcc = function(bcc) {
    this.bcc = bcc;
  };

  this.getBcc = function() {
    return this.bcc;
  };

  this.setBypassListManagement = function(bypass_list_management) {
    this.bypass_list_management = bypass_list_management;
  };

  this.getBypassListManagement = function() {
    return this.bypass_list_management;
  };

  this.setFooter = function(footer) {
    this.footer = footer;
  };

  this.getFooter = function() {
    return this.footer;
  };

  this.setSandBoxMode = function(sandbox_mode) {
    this.sandbox_mode = sandbox_mode;
  };

  this.getSandBoxMode = function() {
    return this.sandbox_mode;
  };

  this.setSpamCheck = function(spam_check) {
    this.spam_check = spam_check;
  };

  this.getSpamCheck = function() {
    return this.spam_check;
  };

  this.toJSON = function() {
    var json = {
      bcc: this.getBcc(),
      bypass_list_management: this.getBypassListManagement(),
      footer: this.getFooter(),
      sandbox_mode: this.getSandBoxMode(),
      spam_check: this.getSpamCheck(),
    };
    return json;
  };

  return this;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sendgrid.mail.OpenTracking"></a>[function <span class="apidocSignatureSpan">sendgrid.mail.</span>OpenTracking (enable, substitution_tag)](#apidoc.element.sendgrid.mail.OpenTracking)
- description and source-code
```javascript
function OpenTracking(enable, substitution_tag) {
  this.enable = enable;
  this.substitution_tag = substitution_tag;

  this.setEnable = function(enable) {
    this.enable = enable;
  };

  this.getEnable = function() {
    return this.enable;
  };

  this.setSubscriptionTag = function(substitution_tag) {
    this.substitution_tag = substitution_tag;
  };

  this.getSubscriptionTag = function() {
    return this.substitution_tag;
  };

  this.toJSON = function() {
    var json = {
      enable: this.getEnable(),
      substitution_tag: this.getSubscriptionTag(),
    };
    return json;
  };

  return this;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sendgrid.mail.Personalization"></a>[function <span class="apidocSignatureSpan">sendgrid.mail.</span>Personalization ()](#apidoc.element.sendgrid.mail.Personalization)
- description and source-code
```javascript
function Personalization() {
  this.tos = undefined;
  this.ccs = undefined;
  this.bccs = undefined;
  this.subject = undefined;
  this.headers = undefined;
  this.substitutions = undefined;
  this.custom_args = undefined;
  this.send_at = undefined;

  this.addTo = function(email) {
    if (this.tos === undefined) {
      this.tos = [];
    }
    this.tos.push(email);
  };

  this.getTos = function() {
    return this.tos;
  };

  this.addCc = function(email) {
    if (this.ccs === undefined) {
      this.ccs = [];
    }
    this.ccs.push(email);
  };

  this.getCcs = function() {
    return this.ccs;
  };

  this.addBcc = function(email) {
    if (this.bccs === undefined) {
      this.bccs = [];
    }
    this.bccs.push(email);
  };

  this.getBccs = function() {
    return this.bccs;
  };

  this.setSubject = function(subject) {
    this.subject = subject;
  };

  this.getSubject = function() {
    return this.subject;
  };

  this.addHeader = function(header) {
    if (this.headers === undefined) {
      this.headers = {};
    }
    this.headers[Object.keys(header)[0]] = header[Object.keys(header)[0]];
  };

  this.getHeaders = function() {
    return this.headers;
  };

  this.addSubstitution = function(substitution) {
    if (this.substitutions === undefined) {
      this.substitutions = {};
    }
    this.substitutions[Object.keys(substitution)[0]] =
      substitution[Object.keys(substitution)[0]];
  };

  this.getSubstitutions = function() {
    return this.substitutions;
  };

  this.addCustomArg = function(custom_arg) {
    if (this.custom_args === undefined) {
      this.custom_args = {};
    }
    this.custom_args[Object.keys(custom_arg)[0]] =
      custom_arg[Object.keys(custom_arg)[0]];
  };

  this.getCustomArgs = function() {
    return this.custom_args;
  };

  this.setSendAt = function(send_at) {
    this.send_at = send_at;
  };

  this.getSendAt = function() {
    return this.send_at;
  };

  this.toJSON = function() {
    var json = {
      to: this.getTos(),
      cc: this.getCcs(),
      bcc: this.getBccs(),
      subject: this.getSubject(),
      headers: this.getHeaders(),
      substitutions: this.getSubstitutions(),
      custom_args: this.getCustomArgs(),
      send_at: this.getSendAt(),
    };
    return json;
  };

  return this;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sendgrid.mail.SandBoxMode"></a>[function <span class="apidocSignatureSpan">sendgrid.mail.</span>SandBoxMode (enable)](#apidoc.element.sendgrid.mail.SandBoxMode)
- description and source-code
```javascript
function SandBoxMode(enable) {
  this.enable = enable;

  var json = {
    enable: this.enable,
  };

  return json;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sendgrid.mail.Section"></a>[function <span class="apidocSignatureSpan">sendgrid.mail.</span>Section (key, value)](#apidoc.element.sendgrid.mail.Section)
- description and source-code
```javascript
function Section(key, value) {
  this.key = key;
  this.value = value;

  var json = {};
  json[this.key] = this.value;

  return json;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sendgrid.mail.SpamCheck"></a>[function <span class="apidocSignatureSpan">sendgrid.mail.</span>SpamCheck (enable, threshold, post_to_url)](#apidoc.element.sendgrid.mail.SpamCheck)
- description and source-code
```javascript
function SpamCheck(enable, threshold, post_to_url) {
  this.enable = enable;
  this.threshold = threshold;
  this.post_to_url = post_to_url;

  this.setEnable = function(enable) {
    this.enable = enable;
  };

  this.getEnable = function() {
    return this.enable;
  };

  this.setThreshold = function(threshold) {
    this.threshold = threshold;
  };

  this.getThreshold = function() {
    return this.threshold;
  };

  this.setPostToUrl = function(post_to_url) {
    this.post_to_url = post_to_url;
  };

  this.getPostToUrl = function() {
    return this.post_to_url;
  };

  this.toJSON = function() {
    var json = {
      enable: this.getEnable(),
      threshold: this.getThreshold(),
      post_to_url: this.getPostToUrl(),
    };
    return json;
  };

  return this;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sendgrid.mail.SubscriptionTracking"></a>[function <span class="apidocSignatureSpan">sendgrid.mail.</span>SubscriptionTracking (enable, text, html, substitution_tag)](#apidoc.element.sendgrid.mail.SubscriptionTracking)
- description and source-code
```javascript
function SubscriptionTracking(enable, text, html, substitution_tag) {
  this.enable = enable;
  this.text = text;
  this.html = html;
  this.substitution_tag = substitution_tag;

  this.setEnable = function(enable) {
    this.enable = enable;
  };

  this.getEnable = function() {
    return this.enable;
  };

  this.setText = function(text) {
    this.text = text;
  };

  this.getText = function() {
    return this.text;
  };

  this.setHtml = function(html) {
    this.html = html;
  };

  this.getHtml = function() {
    return this.html;
  };

  this.setSubstitutionTag = function(substitution_tag) {
    this.substitution_tag = substitution_tag;
  };

  this.getSubstitutionTag = function() {
    return this.substitution_tag;
  };

  this.toJSON = function() {
    var json = {
      enable: this.getEnable(),
      text: this.getText(),
      html: this.getHtml(),
      substitution_tag: this.getSubstitutionTag(),
    };
    return json;
  };

  return this;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sendgrid.mail.Substitution"></a>[function <span class="apidocSignatureSpan">sendgrid.mail.</span>Substitution (key, value)](#apidoc.element.sendgrid.mail.Substitution)
- description and source-code
```javascript
function Substitution(key, value) {
  this.key = key;
  this.value = value;

  var json = {};
  json[this.key] = this.value;

  return json;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sendgrid.mail.TrackingSettings"></a>[function <span class="apidocSignatureSpan">sendgrid.mail.</span>TrackingSettings ()](#apidoc.element.sendgrid.mail.TrackingSettings)
- description and source-code
```javascript
function TrackingSettings() {
  this.click_tracking = undefined;
  this.open_tracking = undefined;
  this.subscription_tracking = undefined;
  this.ganalytics = undefined;

  this.setClickTracking = function(click_tracking) {
    this.click_tracking = click_tracking;
  };

  this.getClickTracking = function() {
    return this.click_tracking;
  };

  this.setOpenTracking = function(open_tracking) {
    this.open_tracking = open_tracking;
  };

  this.getOpenTracking = function() {
    return this.open_tracking;
  };

  this.setSubscriptionTracking = function(subscription_tracking) {
    this.subscription_tracking = subscription_tracking;
  };

  this.getSubscriptionTracking = function() {
    return this.subscription_tracking;
  };

  this.setGanalytics = function(ganalytics) {
    this.ganalytics = ganalytics;
  };

  this.getGanalytics = function() {
    return this.ganalytics;
  };

  this.toJSON = function() {
    var json = {
      click_tracking: this.getClickTracking(),
      open_tracking: this.getOpenTracking(),
      subscription_tracking: this.getSubscriptionTracking(),
      ganalytics: this.getGanalytics(),
    };
    return json;
  };

  return this;
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.sendgrid.parse"></a>[module sendgrid.parse](#apidoc.module.sendgrid.parse)

#### <a name="apidoc.element.sendgrid.parse.parse"></a>[function <span class="apidocSignatureSpan">sendgrid.</span>parse (config, request)](#apidoc.element.sendgrid.parse.parse)
- description and source-code
```javascript
function Parse(config, request) {
  this.keys = config.keys;
  this.request = request;
  this.payload = request.body || {};
  this.files = request.files || [];
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.sendgrid.parse.prototype"></a>[module sendgrid.parse.prototype](#apidoc.module.sendgrid.parse.prototype)

#### <a name="apidoc.element.sendgrid.parse.prototype._getAttachments"></a>[function <span class="apidocSignatureSpan">sendgrid.parse.prototype.</span>_getAttachments (callback)](#apidoc.element.sendgrid.parse.prototype._getAttachments)
- description and source-code
```javascript
_getAttachments = function (callback) {
  var file;
  var attachments = [];

  for (var index in this.files) {
    file = this.files[index];

    if (fs.existsSync(file.path)) {
      file.content = fs.readFileSync(file.path);
      attachments.push(createAttachment(file));
    }
  }

  return callback(attachments);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sendgrid.parse.prototype._getAttachmentsRaw"></a>[function <span class="apidocSignatureSpan">sendgrid.parse.prototype.</span>_getAttachmentsRaw (callback)](#apidoc.element.sendgrid.parse.prototype._getAttachmentsRaw)
- description and source-code
```javascript
_getAttachmentsRaw = function (callback) {
  this.getRawEmail(function(parsedEmail) {
    if (!parsedEmail || !parsedEmail.attachments) {
      return callback([]);
    }

    var attachments = parsedEmail.attachments.map(function(file) {
      return createAttachment(file);
    });

    callback(attachments);
  });
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sendgrid.parse.prototype.attachments"></a>[function <span class="apidocSignatureSpan">sendgrid.parse.prototype.</span>attachments (callback)](#apidoc.element.sendgrid.parse.prototype.attachments)
- description and source-code
```javascript
attachments = function (callback) {
  if (this.hasRawEmail()) {
    return this._getAttachmentsRaw(callback);
  }

  this._getAttachments(callback);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sendgrid.parse.prototype.getRawEmail"></a>[function <span class="apidocSignatureSpan">sendgrid.parse.prototype.</span>getRawEmail (callback)](#apidoc.element.sendgrid.parse.prototype.getRawEmail)
- description and source-code
```javascript
getRawEmail = function (callback) {
  var mailparser = new MailParser();
  var rawEmail = this.payload.email;

  if (!rawEmail) {
    return callback(null);
  }

  mailparser.on('end', callback);

  mailparser.write(rawEmail);
  mailparser.end();
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sendgrid.parse.prototype.hasRawEmail"></a>[function <span class="apidocSignatureSpan">sendgrid.parse.prototype.</span>hasRawEmail ()](#apidoc.element.sendgrid.parse.prototype.hasRawEmail)
- description and source-code
```javascript
hasRawEmail = function () {
  return Boolean(this.payload.email);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sendgrid.parse.prototype.keyValues"></a>[function <span class="apidocSignatureSpan">sendgrid.parse.prototype.</span>keyValues ()](#apidoc.element.sendgrid.parse.prototype.keyValues)
- description and source-code
```javascript
keyValues = function () {
  var keyValues = {};
  var key;

  for (var index in this.keys) {
    key = this.keys[index];

    if (this.payload[key]) {
      keyValues[key] = this.payload[key];
    }
  }

  return keyValues;
}
```
- example usage
```shell
n/a
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
