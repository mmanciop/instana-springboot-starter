# Instana Spring Boot Starter

Spring Boot Starter for monitoring your Spring apps with [Instana](https://www.instana.com).

## What does it contains?

**NOTHING**.

_Just this README._

"Why? How?", I hear you say.

Because tracing your [Spring Boot applications with Instana](https://www.instana.com/supported-technologies/java-monitoring/) works out of the box.
All automated, end-to-end.

So do all other non-Java applications, by the way.
And [Kotlin](https://www.instana.com/supported-technologies/kotlin-monitoring/), [Clojure](https://www.instana.com/supported-technologies/clojure-monitoring/) and [Scala](https://www.instana.com/supported-technologies/scala-monitoring/).

Did I mention [Python](https://www.instana.com/supported-technologies/python-monitoring/)?
We also have [Josh Long](https://twitter.com/starbuxman?ref_src=twsrc%5Egoogle%7Ctwcamp%5Eserp%7Ctwgr%5Eauthor) covered for his _wild_ nights of alcohol abuse and [PHP](https://www.instana.com/supported-technologies/php-monitoring/).
And, in his really darkest moments, [.NET](https://www.instana.com/supported-technologies/microsoft-net-monitoring/) monitoring should scratch that itch.

And also .NET Core, Node.js, Ruby, Haskell, Crystal and on and on!

[Install the Instana host agent](https://docs.instana.io/setup_and_manage/host_agent#installation), and you are good to go.

## Really? I have to do nothing but installing the Instana agent?

If you insist, you could make sure you have the [actuator](https://docs.spring.io/spring-boot/docs/current/reference/html/production-ready-features.html) in your app and turn on metrics via JMX for even better monitoring of Spring Boot 2.2.x and above via the following property:

```prroperties
spring.jmx.enabled=true
```

After that, you are all set and good to go.
Really.

## Yes but does it work on...

Yup, it does.

You wanna deploy on Cloud Foundry or VMware Tanzu? [We _love_ them](https://docs.instana.io/ecosystem/cloudfoundry/)!

Up for some Kubernetes? Knock yourself out with the best-in-class, out-of-the-box, batteries-included-and-then-some [Kubernetes monitoring by Instana](https://docs.instana.io/ecosystem/kubernetes/).

Amazon? [Sure thing](https://docs.instana.io/ecosystem/aws).
Azure? [Yes please!](https://docs.instana.io/ecosystem/azure)
Google Cloud? [Very nice!](https://docs.instana.io/ecosystem/gcp)
You go classy with some VMware vSphere? [There you go](https://docs.instana.io/ecosystem/vsphere/).

## No, this can't be true

Well, it actually is.
And if you do not take my word for it, how about you have a look at the [Play with Instana](https://play-with.instana.io/) sandbox, and if you like what you see, [try it out](https://www.instana.com/trial/) free for two weeks to monitor your applications, no strings attached?
