Java5를 지원하는 마지막 logback에 중대한 버그가 있고, 더이상 메인 프로젝트가 Java5 를 지원하지 않아서 그에 대응하기 위해 만들어진 프로젝트입니다.
해당 버그는 로그가 중간에 멈추는 문제로, 다음의 이슈입니다.
http://jira.qos.ch/browse/LOGBACK-875
Java5를 마지막으로 지원하는 1.0.13 에서 해당 버그에 대한 픽스만 했습니다. 
릴리즈 버전은 1.0.13.1 로 명명했습니다. 
로컬에 다운로드 한 후, "mvn install" 하면 됩니다.

====================

Thank you for downloading logback, the reliable, generic, fast and
flexible logging library for Java.

The Logback documentation can be found under the docs/ directory.

Building logback
================

Building logback is documented at:

  http://logback.qos.ch/manual/introduction.html#BuildingLogback

In case of problems
===================

In case of problems please do not hesitate to post an e-mail message
on the logback-user@qos.ch mailing list.  However, please do not
directly e-mail logback developers. The answer to your question might
be useful to other users. Moreover, there are many knowledgeable users
on the logback-user mailing lists who can quickly answer your
questions. 
