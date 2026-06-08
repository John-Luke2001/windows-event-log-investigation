# Windows Event Log Investigation Findings

## Summary

A Windows Security Event Log investigation was performed using Event Viewer. The Security log was filtered for authentication and privilege-related events, including Event IDs 4624, 4625, and 4672.

## Events Reviewed

### Event ID 4624 - Successful Logon

A successful logon event was identified. This confirms that an account successfully authenticated to the Windows system.

Security analysts review successful logon events to understand normal access patterns and identify potentially suspicious logon activity.

### Event ID 4672 - Special Privileges Assigned

A privileged logon event was identified. The event showed that special privileges were assigned to a new logon session.

The event involved the SYSTEM account, which is commonly used by Windows services and system-level processes.

### Event ID 4625 - Failed Logon

The log was filtered for failed logon events. No failed logon events were observed in the visible filtered results.

## Conclusion

The investigation demonstrated how Windows Event Viewer can be used to review authentication and privilege-related activity. Event IDs 4624, 4625, and 4672 are useful for monitoring account activity, identifying failed access attempts, and reviewing privileged logons.

## Skills Demonstrated

- Log analysis
- Windows Security Event investigation
- Authentication monitoring
- Privileged account review
- Incident response documentation
