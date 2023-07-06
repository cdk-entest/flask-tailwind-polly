---
title: flask tailwind polly demo
description: flask tailwind polly demo
author: haimtran
publishedDate: 06/07/2023
date: 2023-06-07
---

## Introduction

## User Data

```bash
#!/bin/bash
cd ~
wget https://github.com/cdk-entest/flask-tailwind-polly/archive/refs/heads/master.zip
unzip master.zip
cd flask-tailwind-polly-master
python3 -m ensurepip --upgrade
python3 -m pip install -r requirements.txt
cd app
export BUCKET_NAME=""
export REGION="ap-southeast-1"
python3 -m app
```
