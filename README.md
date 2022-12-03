# Blockhound Issue

```text
[ERROR] Failed to execute goal org.apache.maven.plugins:maven-surefire-plugin:2.22.2:test (default-test) on project blockhound-issue: There are test failures.
[ERROR] 
[ERROR] Please refer to /home/michael/workspace/blockhound-issue/target/surefire-reports for the individual test results.
[ERROR] Please refer to dump files (if any exist) [date].dump, [date]-jvmRun[N].dump and [date].dumpstream.
[ERROR] There was an error in the forked process
[ERROR] java.util.ServiceConfigurationError: org.junit.platform.launcher.TestExecutionListener: Provider reactor.blockhound.junit.platform.BlockHoundTestExecutionListener could not be instantiated
[ERROR] org.apache.maven.surefire.booter.SurefireBooterForkException: There was an error in the forked process
[ERROR] java.util.ServiceConfigurationError: org.junit.platform.launcher.TestExecutionListener: Provider reactor.blockhound.junit.platform.BlockHoundTestExecutionListener could not be instantiated
```