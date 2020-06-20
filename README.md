# On-Premise Signal Setup Guide

This guide is a community collaboration effort to setup on-premise (self-hosted) Signal Server.

This guide is based on [Setup guide for Signal](https://github.com/madeindra/setup-guide)

*Signal™ is a trademark of Quiet Riddle Ventures LLC. This projects is not affliated with Signal.org, Signal Messenger LLC, nor Signal Foundation.*

## Requirements
* **Twilio** (For SMS OTP)
* **Amazon S3** (For Avatar and Attachments., can be subtituted with [MinIO](../master/signal-minio) )
* **Amazon SQS** (For CDS Queue. can be subtituted with LocalStack)
* **Firebase** (For push notifications)
* **Google Recaptcha** (For anti-spam in authentication)

## Content
What's proven works
* [Signal Server](../master/signal-server)
* [Server dependencies: PostgreSQL & Redis](../master/signal-docker)
* [Turn Server](../master/turn-server)
* [Signal Android](../master/signal-android)
* [Signal iOS](../master/signal-ios)
* [Signal Desktop](../master/signal-desktop)

Work in progress
* Contact Discovery Service (CDS), you still can use your signal server without CDS.

## ToDos

* CDS Server: Find server with Intel SGX to try to setup custom CDS Server.
* Load Test: I want to see the performance of the custom server under stress, will update later.

## Cotributing
You are welcome to contribute on this guide. If you have any questions please write an issues and I will try to help.

You are recommended to [open an issue here](.issues/new/choose) if you face a difficulties to let the communities help you too and contributing to the communities in the process.
