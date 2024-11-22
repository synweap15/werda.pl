---
title: "Gotchas with Digitalocean Functions"
date: 2023-03-24T06:22:50+01:00
draft: true
---

I wanted to share some inkll;;pkkksights regarding the Digitalocean Functions

## .include 
you also need to include the current dir

## max package size 48 MB (Payload Too Large)
uninstall deps if needed

## database has to be in project app
otherwise there will be a connection timeout

## cant' select runtime for the `lib`
you simply can't

## missing runtime logs
appeared by themselves

## can't see activation record while in app

## catching the errors in the frontend
