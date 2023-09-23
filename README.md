# Simple_Logger

Simple_Logger is a minimalistic logging utility that uses `printf` to print templated strings with colored outputs depending on their log level.

## Features
- Header-only, no compilation required.
- Uses `printf` style template strings for log messages.
- Colored output for different log levels: debug, warning, and error.

## Installation

Header-only library: just include `Simple_Logger.h`

## Usage

Initialize using `init()` static function before use. 

Set the level of messages that should be displayed with `setLevel(Logger::LogLevel level)`. Default level is **debug**.

There are no safety checks so it is very easy to break.
