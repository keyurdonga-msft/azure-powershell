## 11.2.0 - May 2024
#### Az.Automation 1.9.1 
* Modified cmdlet `Get-AzAutomationModule`
   * Added parameter `-RuntimeVersion`
* Modified cmdlet `New-AzAutomationModule`
   * Added parameter `-RuntimeVersion`
* Modified cmdlet `Remove-AzAutomationModule`
   * Added parameter `-RuntimeVersion`
* Modified cmdlet `Set-AzAutomationModule`
   * Added parameter `-RuntimeVersion`
#### Az.DevCenter 1.1.0 
* Modified cmdlet `Deploy-AzDevCenterUserEnvironment`
   * Removed parameter `-DevCenter`
   * Added parameters `-DevCenterName`, `-ExpirationDate`
* Modified cmdlet `Get-AzDevCenterUserCatalog`
   * Removed parameter `-DevCenter`
   * Added parameter `-DevCenterName`
* Modified cmdlet `Get-AzDevCenterUserDevBox`
   * Removed parameter `-DevCenter`
   * Added parameter `-DevCenterName`
* Modified cmdlet `Get-AzDevCenterUserDevBoxAction`
   * Removed parameters `-DevCenter`, `-ActionName`
   * Added parameters `-DevCenterName`, `-Name`
* Modified cmdlet `Get-AzDevCenterUserDevBoxRemoteConnection`
   * Removed parameter `-DevCenter`
   * Added parameter `-DevCenterName`
* Modified cmdlet `Get-AzDevCenterUserEnvironment`
   * Removed parameter `-DevCenter`
   * Added parameter `-DevCenterName`
* Modified cmdlet `Get-AzDevCenterUserEnvironmentDefinition`
   * Removed parameter `-DevCenter`
   * Added parameter `-DevCenterName`
* Modified cmdlet `Get-AzDevCenterUserEnvironmentType`
   * Removed parameter `-DevCenter`
   * Added parameter `-DevCenterName`
* Modified cmdlet `Get-AzDevCenterUserPool`
   * Removed parameter `-DevCenter`
   * Added parameter `-DevCenterName`
* Modified cmdlet `Get-AzDevCenterUserProject`
   * Removed parameter `-DevCenter`
   * Added parameter `-DevCenterName`
* Modified cmdlet `Get-AzDevCenterUserSchedule`
   * Removed parameter `-DevCenter`
   * Added parameters `-DevCenterName`, `-ScheduleName`
* Modified cmdlet `Invoke-AzDevCenterUserDelayDevBoxAction`
   * Removed parameters `-DevCenter`, `-ActionName`
   * Added parameters `-DevCenterName`, `-Name`
* Modified cmdlet `New-AzDevCenterAdminDevCenter`
   * Added parameter `-DisplayName`
* Modified cmdlet `New-AzDevCenterAdminEnvironmentType`
   * Added parameter `-DisplayName`
* Modified cmdlet `New-AzDevCenterAdminPool`
   * Added parameters `-DisplayName`, `-ManagedVirtualNetworkRegion`, `-SingleSignOnStatus`, `-VirtualNetworkType`
* Modified cmdlet `New-AzDevCenterAdminProject`
   * Added parameter `-DisplayName`
* Modified cmdlet `New-AzDevCenterUserDevBox`
   * Removed parameter `-DevCenter`
   * Added parameter `-DevCenterName`
* Modified cmdlet `New-AzDevCenterUserEnvironment`
   * Removed parameter `-DevCenter`
   * Added parameters `-DevCenterName`, `-ExpirationDate`
* Modified cmdlet `Remove-AzDevCenterUserDevBox`
   * Removed parameter `-DevCenter`
   * Added parameter `-DevCenterName`
* Modified cmdlet `Remove-AzDevCenterUserEnvironment`
   * Removed parameter `-DevCenter`
   * Added parameter `-DevCenterName`
* Modified cmdlet `Restart-AzDevCenterUserDevBox`
   * Removed parameter `-DevCenter`
   * Added parameter `-DevCenterName`
* Modified cmdlet `Skip-AzDevCenterUserDevBoxAction`
   * Removed parameters `-DevCenter`, `-ActionName`
   * Added parameters `-DevCenterName`, `-Name`
* Modified cmdlet `Start-AzDevCenterUserDevBox`
   * Removed parameter `-DevCenter`
   * Added parameter `-DevCenterName`
* Modified cmdlet `Stop-AzDevCenterUserDevBox`
   * Removed parameter `-DevCenter`
   * Added parameter `-DevCenterName`
* Modified cmdlet `Update-AzDevCenterAdminCatalog`
   * Added parameter `-SyncType`
* Modified cmdlet `Update-AzDevCenterAdminDevCenter`
   * Added parameter `-DisplayName`
* Modified cmdlet `Update-AzDevCenterAdminEnvironmentType`
   * Added parameter `-DisplayName`
* Modified cmdlet `Update-AzDevCenterAdminPool`
   * Added parameters `-DisplayName`, `-ManagedVirtualNetworkRegion`, `-SingleSignOnStatus`, `-VirtualNetworkType`
* Modified cmdlet `Update-AzDevCenterAdminProject`
   * Added parameter `-DisplayName`
* Added cmdlet `Get-AzDevCenterAdminCatalogSyncErrorDetail`
* Added cmdlet `Get-AzDevCenterAdminEnvironmentDefinition`
* Added cmdlet `Get-AzDevCenterAdminEnvironmentDefinitionErrorDetail`
* Added cmdlet `Get-AzDevCenterUserDevBoxOperation`
* Added cmdlet `Get-AzDevCenterUserEnvironmentAction`
* Added cmdlet `Get-AzDevCenterUserEnvironmentLog`
* Added cmdlet `Get-AzDevCenterUserEnvironmentOperation`
* Added cmdlet `Get-AzDevCenterUserEnvironmentOutput`
* Added cmdlet `Invoke-AzDevCenterUserDelayEnvironmentAction`
* Added cmdlet `Repair-AzDevCenterUserDevBox`
* Added cmdlet `Skip-AzDevCenterUserEnvironmentAction`
* Added cmdlet `Start-AzDevCenterAdminPoolHealthCheck`
* Added cmdlet `Update-AzDevCenterUserEnvironment`
#### Az.HDInsight 6.1.0 
* Modified cmdlet `New-AzHDInsightCluster`
   * Added parameter `-EnableSecureChannel`
#### Az.KeyVault 5.1.0 
* Modified cmdlet `Invoke-AzKeyVaultKeyOperation`
   * Added parameter `-ByteArrayValue`
#### Az.RecoveryServices 6.7.0 
* Modified cmdlet `Restore-AzRecoveryServicesBackupItem`
   * Added parameter `-RestoreToEdgeZone`
#### Az.Resources 6.13.0 
* Modified cmdlet `Publish-AzBicepModule`
   * Added parameter `-WithSource`
#### Az.Storage 6.1.0 
* Modified cmdlet `Get-AzRmStorageShare`
   * Added parameter `-Filter`

