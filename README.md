# Netdiary

A small tool that monitors my home internet connection and keeps a record
of outages and slow periods.

## Problem

My home internet sometimes drops or becomes very slow, especially in the
evenings. When I contact my ISP, they say everything looks fine on their
side. I have no data to show them.

## Goal

Run a small program on my computer that checks the connection every
30 seconds and saves the results. Later, I want to use this data to see
how often the connection fails and when.

- Check the connection to two different targets every 30 seconds
- Record the response time (latency) of each check
- Record failed checks
- Save the results locally

