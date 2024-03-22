Created: March-22-2024

We can connect to a [[SharePoint Online]] site by first logging in to the site in a web browser.

	$siteURL = "https://capgemini.sharepoint.com/sites/ecollab123456"
	
	Connect-PnPOnline -Url $siteURL -UseWebLogin

After connection is established, we can get all the details that we need.
# Related Notes

1. [[PowerShell]]
# References

1. 