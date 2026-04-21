---
title: "{{ replace .Name "-" " " | title }}"
date: {{ .Date }}
draft: true
slug: "{{ .File.ContentBaseName | crypto.MD5 }}"
---