# Get-PnPContentTypePublishingHubUrl

## SYNOPSIS
Returns the url to Content Type Publishing Hub

## EXAMPLES

### ------------------EXAMPLE 1------------------
```powershell
PS:> $url = Get-PnPContentTypePublishingHubUrl
PS:> Connect-PnPOnline -Url $url
PS:> Get-PnPContentType

```

This will retrieve the url to the content type hub, connect to it, and then retrieve the content types form that site

# RELATED LINKS

[SharePoint Developer Patterns and Practices](http://aka.ms/sppnp)