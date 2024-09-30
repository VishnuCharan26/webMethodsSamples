# webMethodsSamples

Sample Log4jLogging webMethods package.

Log4j2.xml config xml path - {ISInstancePath}/packages/Log4jLogging/config/

Log4jLogging.logger:init : To initiate the log4j2.xml.
Log4jLogging.logger:log : To log the content to the log files, execute this service with the below inputs

message : Message to log
level : Possible values : INFO, ERROR, FATAL,WARN,TRACE,DEBUG
loggerName  : Logger name configured in the log4j2.xml file

