# avd
Use at your own risk. This is proof of concept code
avd autoscale with managed identity and disk conversion 
WVDAutoScaleRunbookARMBased.ps1

assumptions:
managed identity enabled on automation account and set on subscription with rbac of contributor logging into gcc high
 $AzAuth = Connect-AzAccount -Identity -EnvironmentName AzureUSGovernment <-remove enviornmentName if you want it to hit commercial cloud
host pool is in its own resource group (not shared with other host pool vms)


