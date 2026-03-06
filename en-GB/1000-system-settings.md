<!-- Version: 0.0 -->
<!-- Status: To do -->

# System settings

System settings can only be modified by users with administrator privileges.

<!-- To do: -->
<!-- Rewrite Claude's text -->
<!--

# General Settings

Navigate to **Settings > General** to configure basic system behavior.

| Setting | Description |
|---------|-------------|
| **Default Language** | Set the default interface language (EN, DE, ES, FR, IT, ZH) |
| **Session Timeout** | Auto-logout time in seconds after inactivity |
| **Default Home Page** | Choose which page opens after login: Scan page or Categories page |


> **Note:** Individual users can change the language at any time using the language selector in the navigation bar. The default language setting applies to the login page and new sessions.


## 7.2 Appearance

Navigate to **Settings > Appearance** to customize the visual branding of the application.

| Setting | Description |
|---------|-------------|
| **Company Logo** | Upload a custom logo displayed in the navigation bar |



## 7.3 MQTT Configuration

MQTT (Message Queuing Telemetry Transport) is used for real-time communication with electronic cabinet locks. Navigate to **Settings > MQTT** to configure the connection.

| Setting | Description |
|---------|-------------|
| **Broker URL** | MQTT broker address (e.g., `mqtt://broker:1883` or `mqtts://broker:8883`) |
| **Username** | Optional: MQTT broker username |
| **Password** | Optional: MQTT broker password |
| **Topic Base** | Topic prefix for MQTT messages (default: `lista/lec`) |

### Supported Protocols

| Protocol | Description |
|----------|-------------|
| `mqtt://` | Standard MQTT (unencrypted) |
| `mqtts://` | MQTT over TLS (encrypted) |
| `tcp://` | TCP connection (unencrypted) |
| `ssl://` | SSL/TLS connection (encrypted) |

### Testing the Connection

After entering the MQTT settings, use the **Test Connection** button to verify connectivity to the broker.


> **Note:** TLS is automatically enabled for `mqtts://` and `ssl://` protocols. Self-signed certificates can be accepted if configured.

### MQTT Lock Commands

For MQTT lock/unlock commands to work, the following must be configured:
- Cabinet must have a **Serial Number** and **MQTT Address** set
- Drawer must have an **MQTT Address** set and **Has Lock** enabled


## 7.4 SMTP / Email Settings

Navigate to **Settings > SMTP** to configure email delivery for notifications.

| Setting | Description |
|---------|-------------|
| **SMTP Server** | Address of the mail server |
| **SMTP Port** | Mail server port |
| **SMTP Username** | Login name for the mail server |
| **SMTP Password** | Password for the mail server |
| **Use SSL** | Enable SSL/TLS for secure connections |
| **Sender Email** | Email address used as sender |
| **Sender Name** | Display name of the sender |

### Testing Email

Enter a test recipient email address and click **Send Test Email** to verify the configuration.



## 7.5 Notifications

Navigate to **Settings > Notifications** to configure automatic email alerts.

### Available Notification Types

| Notification | Description |
|-------------|-------------|
| **Low Stock Warning** | Alert when product quantity falls below warning threshold |
| **Low Stock Alarm** | Alert when product quantity falls below alarm threshold |
| **Lending Expiry** | Alert when borrowed products exceed their return date |
| **Service Check** | Alert for product inspection reminders |
| **System Error** | Alert for system errors |

### Configuring Notifications

For each notification type:

1. **Enable/Disable** the notification.
2. Set the **recipient email addresses**.
3. Configure **cooldown/batch window** - how often notifications are sent (to prevent email flooding).
4. Set **grace periods** where applicable.



## 7.6 Audit Logs

Audit logs record all product operations (storage, removal, lending) with timestamps, user information, and quantities.

### Viewing Audit Logs

1. Navigate to **Settings > Audit Logs**.
2. The log entries are displayed in reverse chronological order.

### Filtering Audit Logs

Use the filter options to narrow down the log entries:

| Filter | Description |
|--------|-------------|
| **Date Range** | Filter by start and end date |
| **User** | Filter by the user who performed the action |
| **Action Type** | Filter by type of action (store, remove, lend, return, etc.) |


### Audit Log Fields

Each log entry contains:

| Field | Description |
|-------|-------------|
| **Timestamp** | Date and time of the action |
| **Action** | Type of operation (take out, put in, lend, return, etc.) |
| **User** | Name of the user who performed the action |
| **Product** | Product name and article number |
| **Quantity** | Amount stored or removed |
| **Cabinet** | Cabinet name |
| **Drawer** | Drawer name |
| **Commission** | Commission/order number if applicable |


## 7.7 Database Backup and Restore

Regular backups protect against data loss.

### Creating a Manual Backup

1. Navigate to **Settings > Backup**.
2. Click **Create Backup**.
3. The backup is created and added to the backup list with a timestamp.


### Backup History

The backup page shows all available backups with:
- Creation timestamp
- File size
- Option to restore or delete

### Restoring from Backup

1. Navigate to **Settings > Backup**.
2. Select the backup to restore from the list.
3. Click **Restore**.
4. Confirm the restoration.

> **Warning:** Restoring a backup replaces ALL current data (products, users, settings, audit logs) with the backup state. This action cannot be undone.

### Uploading a Backup File

You can also restore from an externally stored backup file:

1. Click **Upload & Restore**.
2. Select the backup file from your computer.
3. Confirm the restoration.

### Automatic Backup Schedule

Navigate to **Settings > Backup Schedule** to configure automated backups:

| Setting | Description |
|---------|-------------|
| **Frequency** | How often backups are created |
| **Retention** | How many backups to keep |



## 7.8 License Management

Navigate to **Settings > License** to manage your E-Control license.

### Viewing License Status

The license page displays:
- Current license status (active/inactive)
- License key
- License features enabled

### Activating a License

1. Navigate to **Settings > License**.
2. Enter the license key provided to you.
3. Click **Activate**.
4. The license is validated and activated.


> **Note:** Unlike the previous version, E-Control V3 does not require a hardware dongle. The license is managed entirely through the software.



-->