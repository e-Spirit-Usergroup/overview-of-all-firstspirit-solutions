# overview-of-all-firstspirit-solutions

<p xmlns:cc="http://creativecommons.org/ns#" xmlns:dct="http://purl.org/dc/terms/"><a property="dct:title" rel="cc:attributionURL" href="https://github.com/e-Spirit-Usergroup/overview-of-all-firstspirit-solutions">overview-of-all-firstspirit-solutions</a> by <a rel="cc:attributionURL dct:creator" property="cc:attributionName" href="https://github.com/e-Spirit-Usergroup">e-Spirit Usergroup e.V. members and non-members</a> is marked with <a href="http://creativecommons.org/publicdomain/zero/1.0?ref=chooser-v1" target="_blank" rel="license noopener noreferrer" style="display:inline-block;"> CC0 1.0 Universal<img style="height:22px!important;margin-left:3px;vertical-align:text-bottom;" src="https://mirrors.creativecommons.org/presskit/icons/cc.svg?ref=chooser-v1"><img style="height:22px!important;margin-left:3px;vertical-align:text-bottom;" src="https://mirrors.creativecommons.org/presskit/icons/zero.svg?ref=chooser-v1"></a></p>

This repository is meant to contain all solutions that have been implemented in any project (for internal, customer, commercial, open-source use) so that you know at first sight that somebody has done something beforehand, and you have the possibility to ask him/her about advices, sub-licensing, buying and so on.

## FirstSpirit modules / Module

### e-Spirit modules bundled within FirstSpirit

<table>
<thead>
<tr class="header">
    <th style="width: 10%;">Name</th>
    <th style="width: 60%;">Description</th>
    <th style="width: 10%;">Contact</th>
    <th style="width: 10%;">Type</th>
    <th style="width: 10%;">Link(s)</th>
</tr>
</thead>
<tbody>
{% for column in site.data.eSpiritBundledModulesWithinFirstSpirit %}
  <tr>
     <td markdown="span">{{column.name}}</td>
     <td style="font-size: smaller;" markdown="span">{{column.short_description}}</td>
     <td style="font-size: smaller;" markdown="span">{{column.contact}}</td>
     <td style="font-size: smaller;" markdown="span">{{column.type}}</td>
     <td style="font-size: smaller;" markdown="span">{{column.links}}</td>
  </tr>
{% endfor %}
</tbody>
</table>

### e-Spirit official modules for FirstSpirit

### e-Spirit market-place modules

### e-Spirit Partner modules

<table>
<thead>
<tr class="header">
    <th style="width: 10%;">Name</th>
    <th style="width: 60%;">Description</th>
    <th style="width: 10%;">Contact</th>
    <th style="width: 10%;">Type</th>
    <th style="width: 10%;">Link(s)</th>
</tr>
</thead>
<tbody>
{% for column in site.data.partnerModules %}
  <tr>
     <td markdown="span">{{column.name}}</td>
     <td style="font-size: smaller;" markdown="span">{{column.short_description}}</td>
     <td style="font-size: smaller;" markdown="span">{{column.contact}}</td>
     <td style="font-size: smaller;" markdown="span">{{column.type}}</td>
     <td style="font-size: smaller;" markdown="span">{{column.links}}</td>
  </tr>
{% endfor %}
</tbody>
</table>

## FirstSpirit solutions / (Projekt)L??sungen

## FirstSpirit others / Diverses

## Imprint / Impressum

[https://www.e-spirit-usergroup.de/?page_id=290](https://www.e-spirit-usergroup.de/?page_id=290)
