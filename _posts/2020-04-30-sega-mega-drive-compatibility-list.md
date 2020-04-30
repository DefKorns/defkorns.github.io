---
date: 2020-04-30 21:11:26
layout: post
title: "Sega Mega Drive Compatibility List"
subtitle:
description:
image: https://raw.githubusercontent.com/DefKorns/defkorns.github.io/master/assets/img/default.png
optimized_image: https://raw.githubusercontent.com/DefKorns/defkorns.github.io/master/assets/img/default-sm.png
category: compatibility list
tags:
  - M2Engage
  - mega drive
  - genesis
  - minis
author: DefKorns
paginate: true
---
<table>
  <thead>
    <tr>
    {% for header in site.data.example.keys %}
      <td>{{header}}</td>
    {% endfor %}
    </tr>
  </thead>
  <tbody>
    {% for row in site.data.example.content %}
    <tr>
    {% for column in row %}
      <td>{{column}}</td>
    {% endfor %}
    </tr>
    {% endfor %}
  </tbody>
</table>