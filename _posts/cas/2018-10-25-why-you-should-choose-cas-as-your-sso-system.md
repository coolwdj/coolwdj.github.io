---
layout:     post
title:      Why you should choose CAS as your SSO system
summary:    Discover the true reasons to use CAS
tags:       [Blog, CAS]
---

<div class="alert alert-success">
  <strong>Collaborate</strong><br/>The blog is managed and hosted on GitHub. If you wish to update the contents of this post or if you have found an inaccuracy and wish to make corrections, we recommend that you please submit a pull request to <a href="https://github.com/apereo/apereo.github.io">this repository</a>.
</div>


Most of the customers for whom I work have already chosen the CAS server and its ecosystem when I come in to help them.

Yet, from time to time, I'm contacted earlier in the decision process when the client is still thinking about the products and protocols he wants to use. Advocating for the CAS server is an easy task for me, even if generally, technical reasons are just a small part of the game (politics and relationships really matter).

I especially want to disabuse people who believe that CAS software is just about the CAS protocol, it's so much more.

Some may think that as a CAS committer and as an IAM freelance, I'm biased towards CAS. This is true, but certainly less than any salesman who will earn fees for each sold product.

Eventually, this is what I say:


### 1) CAS is Open Source

Most customers primarily choose Open Source software because it's free. While this is a good reason, they still need to pay consultants to help them.
To me, there are greater benefits, especially the fact that you can contribute to the project.
If you buy an SSO system from a big company, want a new feature and are the only one in the world, it's too bad for you, there is little chance you will get your new feature.
With Open Source software, you can make it happen! 


### 2) CAS is a very modern software

While the general code quality of the CAS server has always been good, I must admit that the whole architecture and design have strongly improved since version 5 where it has embraced the Spring Boot ecosystem. I was a bit reluctant on this huge change, but Misagh was definitely right as using Spring Boot was a big jump forward.
There are some glitches here and there, but overall, the code is easy to read and understand and things are really modular.


### 3) CAS has many features

The CAS server offers many useful capabilities, from obvious ones to more advanced ones. It handles various authentication methods, multi-factor authentication (MFA), can remember the user, force or try authentication, offers a dashboard and monitoring, has logs and audits, manages passwords, etc.
Of course, you cannot only assess a software by the number of its features but having many options is generally a good thing.


### 4) CAS is very popular

The CAS server is one of the most popular software in IAM. With around five thousands stars on github.com, CAS is a well-known project.
Many higher-education schools and companies use it, so you can easily find help from the CAS community or paid consultants. The more the CAS server is installed, the more people read its source code and test it, the more security vulnerabilities are discovered and fixed. It makes it a safe choice for your SSO system.


### 5) CAS fits everywhere

Your existing environment is the first most important criteria when choosing an SSO system. Most companies never start a new project from scratch: for example, they use Redis on CentOS, a bit of MongoDB also and their users' storage is an old LDAP system. You must cope with all that constraints.
If your software only supports technologies A and B, you can only address clients willing to use A or B. The CAS server can:
- use many authentication methods: LDAP, databases, X509, Cassandra, Radius, Spnego, JWT, AWS Cloud Directory and many more
- handle many storage systems: Memcached, Redis, Oracle, Hazelcast, CouchDB, Couchbase, etc.


### 6) CAS is the master of interoperability

Your existing environment is also the second most important criteria when choosing an SSO system! Big bang projects almost always fail and it's hard to deal with legacy. I don't remember having a customer without an existing software to integrate with.
And this is the great strength of CAS:
- the CAS server can act as a SAML IdP, an OAuth provider, an OpenID Connect provder or as a CAS server of course
- but it can also play the role of a client delegating the authentication to another CAS server, to a SAML IdP, to Facebook, Google, Twitter and many other identity providers.

This is one of the main contributions I brought to CAS and I'm especially proud of this interoperability.

CAS clients used for integration in web applications exist in many technologies as well: Java, PHP, .Net, Ruby, Python, Node.js, Apache module, etc.



CAS is a great software, it is worth considering if you plan to choose an SSO system.


[Jérôme LELEU](https://github.com/leleuj)

Originally posted on the [pac4j blog](http://www.pac4j.org/blog/why-you-choose-cas-as-your-sso-system.html)
