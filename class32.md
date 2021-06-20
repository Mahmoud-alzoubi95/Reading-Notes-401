# Permissions
Authentication or identification by itself is not usually sufficient to gain access to information or code. For that, the entity requesting access must have authorization.

## How permissions are determined

Permissions in REST framework are always defined as a list of permission classes.

Before running the main body of the view each permission in the list is checked. If any permission check fails an exceptions.PermissionDenied or exceptions.NotAuthenticated exception will be raised, and the main body of the view will not run.

## API Reference
