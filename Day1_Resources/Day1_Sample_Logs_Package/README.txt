DAY 1 SAMPLE LOG PACKAGE
Cyber Threat Monitoring Level 1

FILES
1. auth.log - simulated Ubuntu authentication log
2. system.log - simulated Ubuntu system/service events
3. mixed_security_events.log - simplified beginner-friendly security events
4. basic_indicators.txt - indicators/keywords for guided searching

SUGGESTED COMMANDS
pwd
ls
cat mixed_security_events.log
less auth.log
head auth.log
tail auth.log
grep "Failed" auth.log
grep "192.168.56.50" auth.log
grep "status=failed" mixed_security_events.log
grep "status=failed" mixed_security_events.log | wc -l

All logs are synthetic and created for classroom use only.
