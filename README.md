Jira-Multiselect-Autocomplete
=============================

Enable auto-completion on multi-select fields in Jira 5.x

This is a quick script to enable autocompletion on multiselect **customFields** in Jira 5.x

Why
---

We made quite a lot of changes to my company's (*at that time*) Jira instance and were afraid of moving to a newer version.

I was asked to find a way to :
* enable autocomplete on long multiselect fields that contained a lot of values
* if possible provide ease of use of those fields based on data input in summary for our ticket creators
 
[Chosen] appeared then as a good alternative to all provided plugins at that time.
However the provided help on the Atlassian Support and Atlassian Jira's related tickets wasn't enough (*or just working in some cases*)

* https://jira.atlassian.com/browse/JRA-23013
* https://jira.atlassian.com/browse/JRA-32290

Version
-------

1.0

Information
-----------

It uses/relies on :
* [Atlassian Jira]'s internal [jQuery] - aka AJS
* [Chosen] by [harvesthq]
* [jQuery] - *obviously*

Installation
------------

* Login to your http[s]://[jira-instance]/
* Go to : Administration > User Interface > Announcement Banner
    * http[s]://[jira-instance]/secure/admin/EditAnnouncementBanner!default.jspa
* If none is set yet
    * copy/paste the whole provided code in announcement-banner.html
* If you already have some stuff there
    * remove first line (*containing a single div*)
* Enjoy :)

[Chosen]:https://github.com/harvesthq/chosen
[jQuery]:http://jquery.com
[harvesthq]:https://github.com/harvesthq
[Atlassian Jira]:https://www.atlassian.com/software/jira