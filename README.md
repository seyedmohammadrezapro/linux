# linux
Get-Disk | Select-Object Number,FriendlyName,SerialNumber,BusType,Size,PartitionStyle,IsBoot,IsSystem,OperationalStatus
Get-PhysicalDisk | Select-Object FriendlyName,SerialNumber,MediaType,Size,HealthStatus,OperationalStatus
Get-Volume | Select-Object DriveLetter,FileSystemLabel,FileSystem,Size,SizeRemaining,DriveType


ادامهٔ سرور فیزیکی را طبق docs/runbooks/continue-physical-server.md شروع کن.
