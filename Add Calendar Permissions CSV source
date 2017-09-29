$csv = Import-csv -path “C:\temp\rmperms.csv”
foreach($User in $csv)
{
Add-MailboxfolderPermission -identity ($user.UserMailbox+’:\calendar’) -User $user.User -AccessRights $user.Accessrights 
}
