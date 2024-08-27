## 365 MFA Export script

Use this script to export the MFA status and setup methods for all users in a 365 tenancy. Admin permissions required to access Entra via Mg-Graph.

Spawns a graph window for easy viewing, leaves a CSV file in C:\temp\ (path can be modified in script)

Requirements:
- Microsoft.Graph (allow 3rd party repository)
- `Install-Module Microsoft.Graph -Force`
