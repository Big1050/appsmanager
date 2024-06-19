# Apps Manager

Apps Manager is a Flutter package that simplifies app management using the [Apps Manager server](https://appsmanager.tech/)

## Features
1. **Monitor App Installs**
2. **Monitor App Sessions**
3. **Real-Time App Analytics**
4. **Send Push Notifications**
5. **Facebook and Admob Ads Controls**
   - Update Placements ID
   - Update AdUnit ID
6. **Uploads Contents for Content Apps**


## Platform Support

| Feature          | Android | iOS     | macOS  | Web    | Linux   | Windows |
|------------------|---------|--------|--------|--------|---------|---------|
| Apps Manager         | ✅       | ✅      | ✅      | ❌     | ✅       | ✅       |
     |


## Getting Started

![Apps Manager](https://appsmanager.tech/uploads/manager.PNG)

## How To Use
```dart
  void adsmanager() async {
    String appID = "78";
    processAds(appID);
    await appsManagerinit(appID);
    print(facebookBanner);
    Get.to(
      const Homepage(),
      transition: Transition.downToUp,
    );
  }

```

## Usage
Here are some common use cases for Apps Manager:

## Monitoring App Installs and Sessions
Apps Manager automatically tracks app installs and sessions. You can view these metrics in real-time on the AppsManager dashboard.

## Real-Time Analytics
Get insights into how your app is performing with real-time analytics. This includes user engagement metrics and usage patterns.

## Push Notifications
Send targeted push notifications to your users directly from the AppsManager dashboard.

## Ads Management
Easily manage your Facebook and Admob ad placements. Update Placement IDs and AdUnit IDs without the need to release a new app version.

## Content Uploads
If your app provides content to users, you can upload and manage this content through the AppsManager server.

## Support
For more information, visit our website or contact our support team at support@appsmanager.tech.


# Creadits
### -[B.I.G](https://devbig-887f1.web.app/)
### -[Apps Manager - Website](https://appsmanager.tech/)
### -[Apps Manager - Youtube](https://www.youtube.com/channel/UC5faffVnDUHsk0g0I0ASa7Q)
