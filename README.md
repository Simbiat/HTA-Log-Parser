# HTA-Log-Parser
This one was actually pretty hard for me to write, so I really hope, that someone will be able to use it. Practically, this is a parser of logs, that I create in other snippets with my [HTA Logger](https://github.com/Simbiat/HTA-Logging), but it is way more. For starters it also parsers logs produced by AMUR and UARM software. For advanced usage it also provides functionallity to sort and filter. A sample of the parser is used in my [HTA Launcher](https://github.com/Simbiat/HTA-Launcher).

Note, that it also need to have some JavaScript in your code.

In case of large logs it may take some time to output the log. Also, even though I tried to polish it, a small bug still remains unsolved: in some cases filter may return 1 line less, than it should. If you find what is causing this - let me know.
