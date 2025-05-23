# Change Log

All notable changes to the "claude-debugs-for-you" extension will be documented in this file.

Check [Keep a Changelog](http://keepachangelog.com/) for recommendations on how to structure this file.

## 0.1.0

- Fixes /sse use via fixing to properly use zod

## 0.0.9

- Fixes bug with tool descriptions

## 0.0.8

- Adds support to resume debugging if already running and LLM requests launch.

## 0.0.7

- Introduces the status menu
- Adds multi-window support
- Improves configuration capabilities and experience
- Simplifies first-time setup

## 0.0.6

- Adds automatic startup and stability improvements

## [0.0.4]
- Add /sse support

## [0.0.3]

- Change built mcp server to be CJS instead of ESM by @jasonjmcghee in #4
- Adds Windows compatibility by fixing a bug by @dkattan in #3, fixing #2

## [0.0.2]

- Adds ability to configure the port of the MCP Server

## [0.0.1]

- Initial release (built initial prototype in hackathon)
- Added support for conditional breakpoints
- Added support for automatically opening the file for debug
- Restructured to work well with .visx and to be language agnostic
