<h1 align=center>🏯 Yosai</h1>

![alt text](http://i.imgur.com/QDhDfKN.jpg "🏯 Yosai")

Yosai is a pythonic port of Apache Shiro-- a powerful security management framework written in Java.  

Yosai offers developers separation of concern between security management and other aspects of any complicated system built today.  An intuitive user-developer API allows Yosai to be integrated with a system within minutes.  Yosai is a framework with well-defined interfaces between components and so it can be easily extended.

Authentication, Authorization, and Session Management that can support whatever you are looking for:

Does your system require a complicated authorization policy? Yosai supports whatever method of access control that you'll need for your system, from DAC to RBAC.

Looking for two-factor authentication?  Yosai supports X-factor authentication.

[ ![Build Status] [travis-image] ] [travis]
[ ![Release] [release-image] ] [releases]


PROJECT OVERVIEW
-----------------------------------------------------------------------
Please, first familiarize yourself with [Apache Shiro](http://shiro.apache.org/).  It is a remarkable system.

Today, no such open-sourced security framework like Shiro exists for the Python community.  There's an unmet need for one.  Shiro has been battle tested and continues to evolve.  Let's learn from history by porting the java source.  Then, we'll refactor the source using techniques and libraries available in Python and with the expertise from this great development community.

I am porting the [v2.0-alpha source code](http://svn.apache.org/repos/asf/shiro/branches/2.0-api-design-changes/)


WORD ORIGIN:  Yosai
-----------------------------------------------------------------------
In Japanese, the word Shiro translates to "Castle".  Yosai translates to "Fortress"🏯  . Like the words, the security platforms are similiar in meaning yet not the same.



PROJECT STATUS
-----------------------------------------------------------------------
05/20/2015:  Testing is well under way.  

05/29/2015:  Latest pytest unit testing coverage stats are as follows:

|Name                        |Stmts|Miss | Cover|
|----------------------------|-----|-----|------|
| yosai/__init__             | 16  | 0   | 100% |
| yosai/account/__init__     | 1   | 0   | 100% |
| yosai/account/interfaces   | 18  | 5   | 72%  |
| yosai/authc/__init__       | 6   | 0   | 100% |
| yosai/authc/authc          | 140 | 11  | 92%  |
| yosai/authc/authc_account  | 50  | 4   | 92%  |
| yosai/authc/context        | 38  | 2   | 95%  |
| yosai/authc/credential     | 49  | 5   | 90%  |
| yosai/authc/interfaces     | 64  | 21  | 67%  |
| yosai/authc/strategy       | 99  | 6   | 94%  |
| yosai/authz/__init__       | 1   | 1   | 0%   |
| yosai/authz/interfaces     | 46  | 46  | 0%   |
| yosai/cache/__init__       | 1   | 0   | 100% |
| yosai/cache/cache          | 35  | 35  | 0%   |
| yosai/cache/interfaces     | 48  | 27  | 44%  |
| yosai/concurrency          | 10  | 10  | 0%   |
| yosai/conf/__init__        | 1   | 0   | 100% |
| yosai/conf/yosaisettings   | 51  | 2   | 96%  |
| yosai/event/__init__       | 2   | 0   | 100% |
| yosai/event/event          | 77  | 54  | 30%  |
| yosai/event/interfaces     | 15  | 5   | 67%  |
| yosai/exceptions           | 127 | 1   | 99%  |
| yosai/init_yosai           | 5   | 5   | 0%   |
| yosai/logging/__init__     | 1   | 0   | 100% |
| yosai/logging/s_logging    | 77  | 56  | 27%  |
| yosai/logging/test_logging | 15  | 15  | 0%   |
| yosai/realm/__init__       | 2   | 0   | 100% |
| yosai/realm/interfaces     | 41  | 12  | 71%  |
| yosai/realm/realm          | 88  | 3   | 97%  |
| yosai/security/__init__    | 1   | 1   | 0%   |
| yosai/security/interfaces  | 22  | 22  | 0%   |
| yosai/security/security    | 462 | 462 | 0%   |
| yosai/subject/__init__     | 1   | 1   | 0%   |
| yosai/subject/interfaces   | 208 | 208 | 0%   |
| yosai/subject/principal    | 85  | 85  | 0%   |
| yosai/subject/subject      | 456 | 456 | 0%   |
| yosai/utils                | 3   | 3   | 0%   |


            
CONTACT INFORMATION
-----------------------------------------------------------------------
If you would like to get involved, please contact me by the email address in my github profile.  I am often
available on FreeNode IRC channels #python and #pyramid under the nickname dowwie.

             
APACHE SHIRO VERSION USED
-----------------------------------------------------------------------
Yosai vX.X.X is as of Apache Shiro 2.0 Alpha, Revision xxxxxx      
