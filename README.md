# Upgrading TFS 2010 to TFS 2012 with Migration to a New Hardware Guide

This Guide explains a step-by-step tutorial with videos on how to upgrade existing TFS 2010 to TFS 2012-Update-1 with migration to a new hardware, the environment including SharePoint 2010, SQL Server 2012 (DB, Analysis Service and Reporting Service) and how to migrate the old data to work with the new services, the Guide will illustrates its steps in videos as well as images.

There are 3 scenarios for upgrading TFS 2012:
<li>
<ul>Upgrade TFS Basic or Express (Basic upgrade)</ul>
<ul>TFS Use the Same Hardware (Standard upgrade)</ul>
<ul>TFS Use Different Hardware (Advanced upgrade)</ul>
</li>
I choose to explain the most complex one which is the 3rd one, so there are a lot of alternative paths for this scenario, I choose a specific path to simplify the Guide and I will try to mention any alternative path that might be needed as we go throughout the Guide. I will try to mention some considerations that you may need to take care of them while you are upgrading.

In the last part of the Guide I will include one video that collect all parts for one-shot view, this Guide consist of following parts: 
<li>
<ul>Part 1 – Introduction.</ul>
<ul>Part 2 – Prepare SharePoint for the new system.</ul>
<ul>Part 3 – Prepare the new machine and install SQL Server.</ul>
<ul>Part 4 – Install TFS 2012 Update 1 & Backup DBs and Reporting Key.</ul>
<ul>Part 5 – Restore DBs and Reporting Encryption Key.</ul>
<ul>Part 6 – Configure TFS 2012.</ul>
<ul>Part 7 – Verify upgrade success and other configuration.</ul>
<ul>Part 8 – Upgrade TFS 2012 Build Service.</ul>
<ul>Part 9 – Summary.</ul>
</li>
