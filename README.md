[WIP] list-dev_flow
===========
![](http://progressed.io/bar/10)

### Dev Flow Good Parts

I will list modern development styles and tools.

example
===

Slack
---

1. use GitHub integration

- **send GitHub push, issue, comments, pull-requests to #general(or #dev)**
  1. Profit: task visualization
  2. ![](https://dl.dropboxusercontent.com/u/7817937/_github/list-dev_flow/slack-github.png)
 
2. use Qiita:Team integration.
 
- **send changes of Qiita:Team article to #general (so that all things are collected to Slack#general)**
  1. ![](https://dl.dropboxusercontent.com/u/7817937/_github/list-dev_flow/slack-qiitateam.png)

tmp(Drafts)
===

###Communitation

- Slack
- Qiita:Team
- GitHub Issue
- sqwiggle (for remote working)

##### Tool

- Vine (share UI/UX/Interaction)

### CI / Test

- CircleCI
- Wercker
- BrowserStack
- AppThrawk

### Infrastructure 

- Docker
- GCP(HTTP Load balancing, instances, DataStore) -> should write more about GCP.
- AWS(SQS, DynamoDB, S3, SNS, Route53)
- Google BigQuery
- CloudFlare
- Mandrill

### Monitoring

- fluentd
- Mackerel
- NewRelic
- Bugsnug
- CloudWatch

### BaaS 

- Parse.com
- Firebase
- Google App Engine
- MongoHQ (scalable & full managed MongoDB cluster)

### Mobile App Libraries / Services

- Crashlytics
- Crashlytics Beta
- HelpShift

### Nice Tools

- Ghostlab
- ngrok
- [mitmproxy](http://mitmproxy.org/)

##### Code maintainance

- rubycritic
- rubocop

##### Documentation

- (Swift / Objective-C)jazzy https://github.com/realm/jazzy
- (Ruby) yard
- (Android) javadoc
- (JavaScript) YUIDoc
- (API) Swagger-UI

###not ready

- Serf, Consul? (these community are not enough yet?)
- Amazon Cognito?
 
###A/B test

- Apptimize http://apptimize.com/

##### Waiting for investigation

- Fluentd-UI https://rubygems.org/gems/fluentd-ui
 

ngrok
---

1. expose local application to your team using ngrok.
  - just `ngrok 3000` to expose `localhost:3000` to `http://someurl.ngrok.com/`
  - Omit needless deploy for checking on Mobile or trying API.
  - ![](https://dl.dropboxusercontent.com/u/7817937/_github/list-dev_flow/ngrok.png)

References
---

- https://speakerdeck.com/naoya/websabisukai-fa-falsebian-qian-toxian-zai



## [Parse.com](https://parse.com/)

facebook bought this 8.4B$.  This is just a BaaS(Backend as a Service) with the SDK of iOS/Android/JS. And also responds to REST API with ActionScript, Clojure, Corona, Java, Javascript, .NET, PHP, Python, Ruby, Unity.  This means, DataStore and Auth function to be a client-side instance. And nowadays discounted.


## [Firebase](https://www.firebase.com/)

1M -> 100M -> 500M fund raise was done. They has alliance of Backbone, Angular, React and so on.  And they've gotten 80000 user in June.
