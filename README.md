# Upgrading TFS 2010 to TFS 2012 with Migration to a New Hardware Guide

This Guide explains a step-by-step tutorial with videos on how to upgrade existing TFS 2010 to TFS 2012-Update-1 with migration to a new hardware, the environment including SharePoint 2010, SQL Server 2012 (DB, Analysis Service and Reporting Service) and how to migrate the old data to work with the new services, the Guide will illustrates its steps in videos as well as images.

There are 3 scenarios for upgrading TFS 2012:
<ul>
<li>Upgrade TFS Basic or Express (Basic upgrade)</li>
<li>TFS Use the Same Hardware (Standard upgrade)</li>
<li>TFS Use Different Hardware (Advanced upgrade)</li>
</ul>
I choose to explain the most complex one which is the 3rd one, so there are a lot of alternative paths for this scenario, I choose a specific path to simplify the Guide and I will try to mention any alternative path that might be needed as we go throughout the Guide. I will try to mention some considerations that you may need to take care of them while you are upgrading.

In the last part of the Guide I will include one video that collect all parts for one-shot view, this Guide consist of following parts: 
<ul>
<li>Part 1 – Introduction.</li>
<li>Part 2 – Prepare SharePoint for the new system.</li>
<li>Part 3 – Prepare the new machine and install SQL Server.</li>
<li>Part 4 – Install TFS 2012 Update 1 & Backup DBs and Reporting Key.</li>
<li>Part 5 – Restore DBs and Reporting Encryption Key.</li>
<li>Part 6 – Configure TFS 2012.</li>
<li>Part 7 – Verify upgrade success and other configuration.</li>
<li>Part 8 – Upgrade TFS 2012 Build Service.</li>
<li>Part 9 – Summary.</li>
</ul>
