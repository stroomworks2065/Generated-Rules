# StroomConfig.zip
This zip folder contains everything needed to demonstrate the rules in Stroom. To set up the rules and necessary feeds in Stroom, follow these steps:
1. Import StroomConfig.zip into Stroom.
2. For each rule, navigate to the Execution tab and add a new processor (Feed is RULE\_FEED, Type = Events). This will eventually be automated with task gh-5024.
3. Select a log from the Test Logs folder and upload it to RULE\_FEED.
4. Observe a detection in RULE\_OUTPUT\_FEED from the rule that corresponds with the selected log.

# Rules
This folder contains a .meta and .node file for each of the 30 generated rules. Each pair of files makes up a Stroom Analytic Rule.

# Test Logs
This folder contains test logs that can be used to prove the functionality of the generated rules. 

There is a separate XML log for each of the 30 rules for them to be tested individually. There is also an XML file named 'All Logs' which is a collection of all 30 logs. When uploaded to RULE\_FEED, this will trigger all 30 rules at once.

# 30 Initial MITRE Techniques
This document outlines each of the 30 techniques that have been chosen from the MITRE ATT\&CK framework for this initial proof of concept.


