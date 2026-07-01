# Case Study: Termination Access Removal

## Scenario

An employee leaves the company and all access must be removed quickly to prevent unauthorized access after employment ends.

## Objective

Disable the user account, remove application access, revoke group memberships, and document the access removal process.

## IAM Process

1. Receive termination notification from HR or the manager.
2. Confirm the employee’s last working day and termination status.
3. Disable the user account in the identity platform.
4. Remove the user from all security groups.
5. Revoke access to assigned applications.
6. Terminate active sessions where possible.
7. Remove privileged or admin access immediately.
8. Document the completed access removal.
9. Confirm completion with HR, manager, or security team.

## Access Removal Example

| Access Item | Action Taken | Reason |
|---|---|---|
| Microsoft 365 | Disabled / revoked | User no longer employed |
| Finance App | Removed | Business access no longer required |
| VPN Access | Revoked | Prevent remote access |
| Admin Tools | Removed immediately | High-risk privileged access |
| Security Groups | Removed | Prevent inherited access |

## Security Controls

- Leaver lifecycle process
- Account deactivation
- Group membership removal
- Privileged access removal
- Session termination
- Access removal documentation

## Risk Reduced

This process reduces the risk of orphaned accounts, unauthorized access, data exposure, and misuse of active credentials after termination.

## Skills Demonstrated

- Leaver process
- Access revocation
- Identity lifecycle management
- Privileged access control
- Security operations documentation
