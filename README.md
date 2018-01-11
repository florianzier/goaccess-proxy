# GoAccess behind a reverse proxy
GoAccess (Visual Web Log Analyzer) with real-time updates behind a HTTPS-secured Reverse-Proxy with Basic Auth.

## Basic Auth
**Username**: *admin*
**Password**: *admin*

## Create multiple real-time reports with Shell
See [How to generate a real-time report for multiple sites](https://github.com/allinurl/goaccess/issues/444).
This *docker-compose* project doesn't support the generation of multiple realtime reports for different hosts yet.
And probably not until [Issue #605](https://github.com/allinurl/goaccess/issues/605) and related [Issue #117](https://github.com/allinurl/goaccess/issues/117) are closed.
At the moment you would need multiple websocket forwardings with many opened ports.

## GoAccess project
Main Site:      <https://goaccess.io/>
GitHub Project: <https://github.com/allinurl/goaccess>
