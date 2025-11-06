# Privacy Policy for TaskRally

**Last Updated: November 5, 2025**

## Introduction

TaskRally ("we," "our," or "us") is committed to protecting your privacy. This Privacy Policy explains how we collect, use, store, and safeguard your information when you use our mobile application.

**Important: TaskRally currently operates as a local-only personal planning app. All your data is stored exclusively on your device, and we do not collect, transmit, or share your data with any servers or third parties.**

## Information We Collect

### Personal Information You Provide
- **Account Information**: Name you provide during setup (no email or password required)
- **Event Data**: Events you create including titles, dates, locations, and notes
- **Task Data**: Tasks, descriptions, due dates, priorities, status, and personal notes
- **Notification Preferences**: Your notification settings and custom reminder times

### Information NOT Collected
TaskRally does NOT collect:
- ❌ Email addresses or passwords (simple name-based login only)
- ❌ Payment information (app is free with no in-app purchases)
- ❌ Precise location data beyond what you manually enter
- ❌ Usage analytics or tracking data
- ❌ Device identifiers for tracking purposes
- ❌ Crash reports or error logs sent to servers
- ❌ Any data transmitted to external servers

### Permissions We Request

TaskRally may request the following permissions to enhance your experience. **All permissions are optional and the app works without them.**

#### Notification Permissions (Recommended)
We request notification permissions to:
- Send reminders about upcoming events
- Alert you about task deadlines (due soon and overdue)
- Daily, weekly, or custom scheduled reminders based on your preferences

**Important**: All notifications are processed locally on your device. No notification data is sent to external servers.

#### Calendar Access (Future Feature - Not Currently Used)
When implemented, calendar access would allow:
- Syncing events between TaskRally and your device calendar
- Importing existing calendar events
- Creating calendar entries for your planned events

#### Camera Access (Future Feature - Not Currently Used)
When implemented, camera access would allow:
- Taking photos for event documentation
- Capturing images to attach to tasks

#### Photo Library Access (Future Feature - Not Currently Used)
When implemented, photo library access would allow:
- Selecting existing photos for events and tasks
- Saving event-related images

#### Location Access (Future Feature - Not Currently Used)
When implemented, location access would allow:
- Suggesting nearby venues when creating events
- Providing location-based recommendations

## How We Use Your Information

**Since TaskRally stores all data locally on your device, we do not "use" your information in the traditional sense. Your data never leaves your device.**

Your information is processed locally on your device to:
- Provide and maintain TaskRally app functionality
- Display your events, tasks, and planning information
- Send local notifications based on your preferences
- Save your notification settings and app preferences
- Persist your data between app launches

**What we do NOT do:**
- ❌ Analyze your usage patterns on external servers
- ❌ Share data with third parties or advertisers
- ❌ Use your data for marketing or promotional purposes
- ❌ Track your behavior across devices
- ❌ Send your data to any backend servers

## Data Storage

**Current Implementation - 100% Local Storage Only**

TaskRally stores ALL data exclusively on your device using:
- **iOS**: NSUserDefaults via AsyncStorage
- **Android**: SharedPreferences via AsyncStorage

### What Data is Stored Locally

The following data is saved in local device storage:

1. **Authentication Storage** (`auth-storage`):
   - Your name
   - User ID (generated locally)
   - Avatar initial
   - Login state

2. **Event Storage** (`event-storage`):
   - All events you create
   - Event titles, dates, locations, notes
   - Event members (stored locally as placeholders)
   - Event creation and update timestamps

3. **Task Storage** (`task-storage`):
   - All tasks across all events
   - Task descriptions, statuses, priorities
   - Due dates and auto-schedule settings
   - Task assignees (local placeholders only)
   - Comments and checklists
   - Task creation and update timestamps

4. **Notification Storage** (`notification-storage`):
   - Notification preferences (enabled/disabled)
   - Custom notification times
   - Quiet hours settings
   - Overdue reminder frequency

5. **Template Storage** (`template-storage`):
   - Pre-built event templates (Birthday, Wedding, Conference)
   - Template task lists

### Critical Privacy Facts

✅ **Your data stays on your device**
- All data is stored locally using React Native AsyncStorage
- Zero data transmission to external servers
- Complete data privacy and control

❌ **No cloud backup or sync**
- Uninstalling the app permanently deletes all data
- No ability to recover data after uninstall
- No sync between multiple devices

❌ **Collaboration features are placeholders only**
- "Inviting members" creates local-only placeholders
- Other users cannot actually see or access your events
- No real-time sharing or team functionality

### Security of Local Storage

- Data is protected by your device's security (passcode/biometric lock)
- iOS and Android sandbox protections prevent other apps from accessing your data
- No encryption in transit (because no data transmission occurs)
- Data is stored in app-specific storage that is cleared on uninstall

## Data Sharing and Disclosure

**TaskRally does NOT share any data because all data is stored locally on your device.**

### We Do NOT:
- ❌ Sell your personal information to third parties (we never have access to it)
- ❌ Share your event data with advertisers
- ❌ Transmit your data to any backend servers
- ❌ Access your calendar, photos, or location without permission
- ❌ Use your data for marketing purposes
- ❌ Share data with analytics services
- ❌ Send crash reports or telemetry data

### Important Clarification About Team Features

When you "invite team members" to events in TaskRally v1.0:
- This feature is a **local-only placeholder**
- Invited members are stored only on YOUR device
- No actual invitations are sent
- Other users cannot see or access your events
- This is NOT real collaboration

**For real team collaboration**, a future version (TaskRally Pro) will require a backend server and will be accompanied by an updated privacy policy with explicit consent.

### Apple Services We Use

**Apple Push Notification Service (APNs)**:
- Used only for local notification delivery
- No custom data is sent through APNs
- Only device tokens are registered with Apple (standard iOS functionality)
- Notifications are scheduled and processed locally on your device

## Third-Party Services

**TaskRally v1.0 does NOT use any third-party services.**

We do NOT use:
- ❌ Analytics services (no Google Analytics, Mixpanel, etc.)
- ❌ Crash reporting services (no Sentry, Crashlytics, etc.)
- ❌ Advertising networks
- ❌ Social media integrations
- ❌ Cloud storage providers
- ❌ Backend-as-a-Service platforms (no Firebase, Supabase, etc.)

### Expo Application Services (EAS)

TaskRally is built using Expo, but we do NOT use EAS Updates or EAS telemetry in production:
- No over-the-air updates that could track usage
- No analytics data sent to Expo servers
- Standard iOS app distribution through App Store only

### Future Third-Party Services

When TaskRally Pro is released with cloud sync and collaboration features, we will:
1. Update this privacy policy with detailed information
2. Request your explicit consent before enabling cloud features
3. Clearly disclose all third-party services used
4. Provide opt-out mechanisms for analytics and crash reporting

## Data Retention

**Since all data is stored locally on your device, you have complete control over data retention.**

### How Long Data is Stored

- **All Data**: Stored on your device indefinitely until you:
  - Delete individual events or tasks
  - Log out (clears auth data only, preserves events/tasks)
  - Uninstall the app (permanently deletes all data)

### Data Deletion

**To delete specific data**:
- Delete individual events from the Event List screen
- Delete individual tasks from the Task Detail screen
- These actions immediately remove data from local storage

**To delete all data**:
- Uninstall TaskRally from your device
- This permanently deletes all events, tasks, and settings
- Data cannot be recovered after uninstall (no cloud backup)

**Note**: We do not have access to your data, so we cannot delete it remotely or retrieve it for you.

## Your Rights and Choices

**With TaskRally's local-only storage, you have complete control over your data.**

### Access Your Data
- **All data is already on your device** - view it anytime in the app
- No need to request data from us since we don't have access to it
- You can view all events, tasks, and settings within the app

### Correct Your Data
- Update your name in App Settings
- Edit events and tasks directly in the app
- All changes are immediate and stored locally

### Delete Your Data
- Delete individual events and tasks in the app
- Uninstall the app to permanently delete all data
- We cannot recover data after deletion (no backups)

### Control Permissions
- **Notifications**: Enable/disable in App Settings or iOS Settings
- **Future Permissions** (Calendar, Camera, Photos, Location):
  - Grant or revoke in iOS Settings → TaskRally
  - App continues to work without these permissions

### Data Portability
**Current Version**: No export feature yet (data is local-only)
**Future Version**: We plan to add export features to save your data as JSON or CSV files for backup or transfer purposes

## Children's Privacy

TaskRally is rated 4+ and suitable for all ages. Since all data is stored locally on the device and no personal information is collected or transmitted:

- We do not collect names, email addresses, or contact information from any users
- No data is transmitted to external servers
- Children can use the app safely for personal event planning
- Parents have full control through device-level restrictions

If you have concerns about your child's use of TaskRally, you can:
- Monitor their device usage through iOS Screen Time
- Control app permissions through iOS Settings
- Delete the app at any time to remove all data

## Security

**TaskRally's local-only architecture provides strong privacy protection by design.**

### Security Measures in Place

1. **Device-Level Security**:
   - Your data is protected by your device's passcode or biometric authentication
   - iOS and Android sandbox protections prevent other apps from accessing TaskRally data
   - App-specific storage is isolated from other applications

2. **No Network Transmission**:
   - Since data never leaves your device, there's no risk of interception during transmission
   - No servers to hack or breach
   - No cloud vulnerabilities

3. **Local Data Storage**:
   - Data stored using React Native AsyncStorage
   - Protected by operating system security features
   - Automatically deleted when app is uninstalled

### What We Cannot Protect Against

- **Physical device access**: If someone has access to your unlocked device, they can access TaskRally
- **Device backups**: iOS device backups may include TaskRally data
- **Lost or stolen devices**: Ensure your device has a strong passcode and Find My iPhone enabled

### Recommendations

To keep your data secure:
- ✅ Use a strong device passcode or biometric lock
- ✅ Keep your device's operating system updated
- ✅ Don't share your device passcode with others
- ✅ Enable Find My iPhone for device security

## California Privacy Rights (CCPA)

**TaskRally's local-only architecture means CCPA requirements largely do not apply, but we provide this information for transparency.**

If you are a California resident:

### What Personal Information We Collect
- **Name** (stored locally on your device only)
- **User-generated content** (events, tasks, notes - all local)

### What We Do NOT Do
- ❌ We do not "collect" data in the traditional sense (no servers, no transmission)
- ❌ We do not sell personal information
- ❌ We do not share data with third parties
- ❌ We do not have access to your data

### Your CCPA Rights
While CCPA may not apply to local-only storage, you have complete control:
- **Right to know**: All your data is visible in the app
- **Right to delete**: Delete data in-app or uninstall
- **Right to opt-out of sale**: Not applicable (we never sell data)
- **Right to non-discrimination**: Not applicable (no account restrictions)

## European Privacy Rights (GDPR)

**TaskRally's local-only architecture means GDPR requirements largely do not apply, but we provide this information for transparency.**

If you are in the European Economic Area (EEA) or UK:

### Data Controller
Since all data is stored locally on your device and we do not have access to it, you are effectively the data controller of your own information.

### Your GDPR Rights
While GDPR may not apply to local-only storage, you have complete control:

- ✅ **Right to access**: All data is accessible within the app
- ✅ **Right to rectification**: Edit data directly in the app
- ✅ **Right to erasure** ("right to be forgotten"): Delete in-app or uninstall
- ✅ **Right to restrict processing**: Not applicable (processing is local only)
- ✅ **Right to data portability**: Currently not available (planned for future versions)
- ✅ **Right to object**: Not applicable (no automated processing or profiling)
- ✅ **Right to withdraw consent**: Revoke permissions in iOS Settings

### Legal Basis for Processing
- **Consent**: You provide consent by using the app
- **Legitimate Interest**: Personal planning and organization on your own device
- **No third-party processing**: Data never leaves your device

### Data Transfers
- **No international transfers**: Data stays on your device regardless of location
- **No cross-border processing**: No data transmission occurs

## International Data Transfers

**TaskRally does NOT transfer data internationally because all data is stored locally on your device.**

- Your data never leaves your device, regardless of your location
- No data is sent to servers in the United States or any other country
- No cross-border data transfer occurs
- Data protection compliance is determined by your device's location and your local laws

When TaskRally Pro is released with cloud sync:
- We will provide clear information about where data is stored (data centers, regions)
- We will implement appropriate safeguards for international data transfers
- We will comply with GDPR, CCPA, and other applicable data protection laws
- Users will be notified and must provide consent before any cloud sync occurs

## Changes to This Privacy Policy

We may update this Privacy Policy to reflect changes in our practices or legal requirements.

### When Updates Occur
- App feature additions (e.g., cloud sync, collaboration features)
- Changes in data handling practices
- Legal or regulatory requirements
- User feedback and transparency improvements

### How You'll Be Notified
When we make material changes:
1. **In-App Notification**: You'll see a notification when you open the app
2. **Updated Date**: The "Last Updated" date at the top will change
3. **Review Opportunity**: You can review changes before continuing to use the app

### For Major Changes (e.g., Backend Integration)
If we add cloud sync or backend services:
- We will request explicit consent before enabling
- You can opt-out and continue using local-only storage
- A detailed comparison of privacy implications will be provided
- You'll have the choice to upgrade or keep using TaskRally v1.0

### Your Continued Use
By continuing to use TaskRally after changes are posted, you accept the updated Privacy Policy.

## Contact Us

If you have questions, concerns, or requests regarding this Privacy Policy:

**Email**: privacy@taskrally.app
**Support**: support@taskrally.app
**Developer**: Vibecode Inc.

**Important Note**: Since TaskRally v1.0 stores all data locally on your device:
- We cannot access, retrieve, or delete your data remotely
- We cannot recover lost data if you uninstall the app
- For technical support, we can only provide guidance on using the app's features

## Consent

By using TaskRally, you acknowledge that you have read and understood this Privacy Policy.

### What You're Consenting To:
- ✅ Local storage of your events and tasks on your device
- ✅ Optional notification permissions (if you grant them)
- ✅ Optional future permissions like camera and calendar (if you grant them)
- ✅ The terms described in this privacy policy

### What You're NOT Consenting To:
- ❌ Data collection by external servers (doesn't happen)
- ❌ Sharing your information with third parties (doesn't happen)
- ❌ Analytics or tracking (doesn't happen)

**If you do not agree with this Privacy Policy, please do not use TaskRally.**

---

## Summary: TaskRally v1.0 Privacy in Plain English

✅ **What TaskRally Does**:
- Stores all your data locally on your device only
- Never sends your data to any servers
- Never shares your data with anyone
- Gives you complete control over your information

❌ **What TaskRally Does NOT Do**:
- Collect email addresses or passwords
- Track your usage or behavior
- Send analytics to external services
- Access your data from our servers (we have no servers)
- Share data with third parties or advertisers

🔒 **Your Privacy is Protected**:
- No cloud storage = No cloud breaches
- No data transmission = No interception risks
- No third-party services = No data sharing
- Complete local control = Maximum privacy

📱 **Important Limitations**:
- Team collaboration features are placeholder-only (not real)
- No data backup or recovery after uninstall
- No sync between multiple devices

This is a **personal planning app** designed for individual use with complete privacy. When TaskRally Pro adds real collaboration and cloud features, we'll update this policy and ask for your explicit consent.

---

**Last Updated: November 4, 2025**
**Version: 1.0 (Local-Only Storage)**
