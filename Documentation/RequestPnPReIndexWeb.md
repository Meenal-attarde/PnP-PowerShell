# Request-PnPReIndexWeb

## SYNOPSIS
Marks the web for full indexing during the next incremental crawl

## SYNTAX 

```powershell
Request-PnPReIndexWeb [-Web <WebPipeBind>]
```

## PARAMETERS

### -Web
The GUID, server relative url (i.e. /sites/team1) or web instance of the web to apply the command to. Omit this parameter to use the current web.

```yaml
Type: WebPipeBind
Parameter Sets: (All)

Required: False
Position: Named
Accept pipeline input: False
```

# RELATED LINKS

[SharePoint Developer Patterns and Practices](http://aka.ms/sppnp)