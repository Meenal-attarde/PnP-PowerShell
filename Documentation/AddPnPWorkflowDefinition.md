# Add-PnPWorkflowDefinition

## SYNOPSIS
Adds a workflow definition

## SYNTAX 

```powershell
Add-PnPWorkflowDefinition -Definition <WorkflowDefinition>
                          [-DoNotPublish [<SwitchParameter>]]
                          [-Web <WebPipeBind>]
```

## EXAMPLES

### ------------------EXAMPLE 1------------------
```powershell
Add-PnPWorkflowDefinition -Definition $wfdef
```

Adds an existing workflow definition, retrieved by Get-PnPWorkflowDefinition, to a site.

## PARAMETERS

### -Definition
The workflow definition to add.

```yaml
Type: WorkflowDefinition
Parameter Sets: (All)

Required: True
Position: Named
Accept pipeline input: False
```

### -DoNotPublish
Overrides the default behaviour, which is to publish workflow definitions.

```yaml
Type: SwitchParameter
Parameter Sets: (All)

Required: False
Position: Named
Accept pipeline input: False
```

### -Web
The GUID, server relative url (i.e. /sites/team1) or web instance of the web to apply the command to. Omit this parameter to use the current web.

```yaml
Type: WebPipeBind
Parameter Sets: (All)

Required: False
Position: Named
Accept pipeline input: False
```

## OUTPUTS

### System.Guid

Returns the Id of the workflow definition

# RELATED LINKS

[SharePoint Developer Patterns and Practices](http://aka.ms/sppnp)