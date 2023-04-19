---
title: Group Members
description: Read about the AI for Medicine Research Group members.
nav:
  order: 1
  tooltip: About the group members

header-dark: false
footer-dark: false
---


# <i class="fas fa-users"></i>Group Members


<center>The <b>AI for Medicine Research Group</b> is led by <b>Prof. Stefano Diciotti</b>.<br>
For up-to-date info about the Group members, check out their personal links.</center>

{% include section.html %}

{%
  include list.html
  data="members"
  component="portrait"
  filters="role: pi"
%}
{%
  include list.html
  data="members"
  component="portrait"
  filters="role: phd"
%}
{%
  include list.html
  data="members"
  component="portrait"
  filters="role: programmer"
%}
{:.center}
