# SQLQA
SQL QA is a SSRS Report to look at various settings and configurations of your SQL Server Instance on the fly including the following sections. It will also highlight in yellow or grey things to watch out.

# Instance Details
Instance Name, Edition, SQLVersion, ServicePack, Machine Type, Auth Mode, TCP Port, Install Date, Last Start Date

# Configuration Settings
Backup Compression, PowerPlan, Xp_CmdShell, MaxDop

# System Information
Server Memory, Max Server Memory, Min Server Memory and number of CPus

# Drive Space
Drive Name, CapacityGB, UsedGB, FreeGB, Percentage Free

# Database Options
Name, Compatibility, State, User Access Description, Recovery Model, Collation, PageVerify, ReadOnly, AutoClose, AutoShrink, AutoCreate Stats, AutoUpdate Stats, FullText, DB Chaining, Trustworthy, Owner

# Database Size
Name, Size, Used Space MB, Free Space MB, Percent Free, Updateability, State

# Log Size
DB Name, LogSize MB, Percentage USed

# Database Files Details
DB Name, Logical Name, Type, Total Space MB, Used Space MB, Free Space MB, Percent Used, Physical Name, File Group, File Growth, Auto Growth

# User Database Role Membership
DB Name, UserName, DatabaseRole, Login Name, Def DBName

# Login Server Role Membership
Login Name, Type, Server Role, Disabled, Def DBName

# Backups
DB Name, Virtual Full, Virtual Diff, Disk Full, DiskDiff, DiskTlog, Recovery Model State Desc, Updateability
