<p align="center"><img src=https://avatars2.githubusercontent.com/u/32488600?s=100&v=4></p>

canary.txt is a proposed standard which allows websites to define security policies. The canary.txt file sets clear guidelines for security researchers on how to report security issues. canary.txt is the equivalent of `robots.txt`, but for security issues.

> “ When security vulnerabilities are discovered by researchers, proper reporting channels are often lacking.  As a result, vulnerabilities may be left unreported.  This document defines a format ("canary.txt") to help organizations describe their vulnerability disclosure practices to make it easier for researchers to report vulnerabilities.”

---

# Website

Project website: https://canarytxt.org/ (https://github.com/canarytxt/canarytxt.org)

Internet draft website: https://canarytxt.io/ (https://github.com/canarytxt/canary-txt/tree/master/docs)

# canary.txt GitHub Organization

https://github.com/canarytxt/

# Internet draft

The Internet draft for canary.txt can be found here: https://tools.ietf.org/html/draft-foudil-canarytxt.

# Building the Draft

To build the text and HTML drafts, use the following make command.

```sh
$ make clean
$ make txt
$ make html
```

This requires that you have the necessary software installed.  See [the
instructions](https://github.com/martinthomson/i-d-template/blob/master/doc/SETUP.md).


---

# Frequently asked questions

**What is the main purpose of canary.txt?**

The main purpose of canary.txt is to help make things easier for companies and security researchers when trying to secure platforms. Thanks to canary.txt, security researchers can easily get in touch with companies about security issues.

**Is canary.txt an [RFC](https://en.wikipedia.org/wiki/Request_for_Comments)?**

canary.txt is currently an Internet draft that has been submitted for <abbr title="Request For Comments">RFC</abbr> review. This means that canary.txt is still in the early stages of development. We welcome contributions from the public: [https://github.com/canarytxt/canary-txt](https://github.com/canarytxt/canary-txt)

**Where should I put the canary.txt file?**

For websites, the canary.txt file should be placed under the `/.well-known/` path (`/.well-known/canary.txt`) [[<abbr title="Request For Comments">RFC</abbr>8615](https://tools.ietf.org/html/rfc8615)]. It can also be placed in the root directory (`/canary.txt`) of a website, especially if the `/.well-known/` directory cannot be used for technical reasons, or simply as a fallback. The file can be placed in both locations of a website at the same time. For code repositories, the file should be placed in the root directory of the repository.

**Are there any settings I should apply to the file?**

The canary.txt file should have an Internet Media Type of `text/plain` and must be served over HTTPS.

**Will adding an email address expose me to spam bots?**

The email value is an optional field. If you are worried about spam, you can set a URI as the value and link to your security policy.

# Code of conduct

To maintain an orderly, productive, and fun environment, the _canary.txt_ project have a few guidelines that we ask people to adhere to when they are participating in contributing to the project. These guidelines apply equally to everyone within the _canary.txt_ project. Likewise, they apply to all spaces managed by the _canary.txt_ project, both online and offline. This includes GitHub repositories, chat rooms, in-person events, and any other communication channels.

- Be welcoming, friendly, patient, and kind.
- Be respectful.
- Be cautious with how you word things. Our goal is to remain professional.
- When we disagree, try to understand why.
- Direct contributions to the specification will only be accepted from individuals <sup>[[1]](https://en.oxforddictionaries.com/definition/individual)</sup>. The _canary.txt_ project will not accept contributions to the specification in the name of an organisation. This is to ensure that the specifications and tools remain as neutral as possible.
- Registering an account on any service in the name of the _canary.txt_ project must be clearly communicated via the team first.

# Contributing

Contributions from the public are welcome.

### Using the issue tracker 💡

The issue tracker is the preferred channel for bug reports and features requests. [![GitHub issues](https://img.shields.io/github/issues/canarytxt/canary-txt.svg?style=flat-square)](https://github.com/canarytxt/canary-txt/issues)

### Issues and labels 🏷

The bug tracker utilizes several labels to help organize and identify issues.

### Guidelines for bug reports 🐛

Use the GitHub issue search — check if the issue has already been reported.
