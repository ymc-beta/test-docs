<!-- Version: 0.0 -->
<!-- Status: To do -->

## Manage users and groups 

<!-- To do: -->
<!-- Rewrite Claude's text -->
<!--

# 6. User Management (Admin)

E-Control V3 provides user management with role-based access control and group-based product access permissions. These functions require **administrator** privileges.


## 6.1 Users and Roles

### User Accounts

Each user is uniquely identified by:
- **Username**: Used for login
- **Display Name**: Shown in the interface and audit logs
- **Password**: For authentication

### Roles

Each user is assigned one of the following roles:

| Role | Description |
|------|-------------|
| **User** | Standard user with access to product operations (browse, store, remove, borrow) |
| **Admin** | Full access to all features including system configuration and user management |
| **Superadmin** | All admin features plus access to system logs |

**Administrators** have full access to:
- Product and category management
- Cabinet configuration
- User and group management
- Settings and system configuration
- Reports and audit logs

**Standard users** can:
- Browse products by category, storage location, or scan
- Store and remove products
- Borrow and return lendable products
- View lent products and low stock items
- Process pick lists
- Change their own password

### Groups

Groups provide product access control. A group has access to specific products, and all users in that group inherit the same product access.

- Product access only needs to be configured once per group
- A user can belong to multiple groups


## 6.2 Creating and Editing Users

### Creating a New User

1. Navigate to **Settings > Users**.
2. Click **Create**.
3. Fill in the user details:

| Field | Description |
|-------|-------------|
| **Username** | Login name (must be unique) |
| **Display Name** | Name shown in the interface |
| **Password** | Initial password |
| **Password Confirmation** | Repeat the password |
| **Role** | Select User, Admin, or Superadmin |

4. Optionally assign the user to one or more groups.
5. Click **Save**.


### Editing a User

1. Navigate to **Settings > Users**.
2. Find the user in the list (use search to filter).
3. Click on the user to edit.
4. Modify the desired fields.
5. Click **Save**.

### Deleting a User

1. Open the user for editing.
2. Click **Delete** at the bottom.
3. Confirm the deletion.

> **Warning:** Deleted users cannot be restored. Their historical audit log entries are preserved.


## 6.3 Importing Users

Users can be bulk-imported from Excel files.

### Import Process

1. Navigate to **Settings > User Import**.
2. Select the import file.
3. Choose the import mode:

| Mode | Description |
|------|-------------|
| **New only** | Only create new users, skip existing ones |
| **Update existing** | Create new users and update existing ones |
| **Fresh** | Remove all existing users and replace with imported data |
| **Dry Run** | Preview the import without making changes |

4. Click **Start Import**.
5. Review the results showing created, updated, and skipped accounts.


> **Note:** Always run a **Dry Run** first to verify the import data.


## 6.4 Groups

### Viewing Groups

1. Navigate to **Settings > Groups**.
   The list of all groups is displayed.

### Creating a New Group

1. Click **Create**.
2. Enter the group name and description.
3. Add users to the group by selecting them from the user list.
4. Click **Save**.

### Editing a Group

1. Click on the group to edit.
2. Modify the group name, description, or member list.
3. Click **Save**.

### Deleting a Group

1. Open the group for editing.
2. Click **Delete**.
3. Confirm the deletion.

> **Note:** Deleting a group removes the group membership but does not delete the users themselves.


## 6.5 Change Password

### Changing Your Own Password

Any user can change their own password:

1. Navigate to **Settings > Change Password** (or access from the settings menu).
2. Enter your current password.
3. Enter the new password.
4. Confirm the new password.
5. Click **Change Password**.

### Administrator Password Reset

Administrators can reset any user's password by editing the user account and setting a new password in the user detail form.

-->
