---
title: "{{ replace .TranslationBaseName "-" " " | title }}"
slug: "{{ (printf "%s-%s" (dateFormat "01-02" .Date) (replace .TranslationBaseName "-" " " | title)) }}"
date: {{ .Date }}
draft: true

tags: []
categories: []
series: []
---
