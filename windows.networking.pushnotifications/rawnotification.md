---
-api-id: T:Windows.Networking.PushNotifications.RawNotification
-api-type: winrt class
---

<!-- Class syntax.
public class RawNotification : Windows.Networking.PushNotifications.IRawNotification, Windows.Networking.PushNotifications.IRawNotification2
-->

# Windows.Networking.PushNotifications.RawNotification

## -description
Encapsulates the app-defined content of a raw notification (a push notification that does not involve UI). Its contents can be used in an app's background task, if the app has that capability, or otherwise consumed by the app and acted on as needed.

## -remarks
A RawNotification object is obtained through the [TriggerDetails](../windows.applicationmodel.background/ibackgroundtaskinstance_triggerdetails.md) property.

A background task that is intended to run in response to a notification must be registered with a [PushNotificationTrigger](../windows.applicationmodel.background/pushnotificationtrigger.md). If it is not registered, the task will not run when a raw notification is received. For more info, see [Raw notification overview](https://docs.microsoft.com/windows/uwp/controls-and-patterns/tiles-and-notifications-raw-notification-overview).

### Version history

| Windows version | SDK version | Value added |
| -- | -- | -- |
| 1703 | 15063 | ChannelId |
| 1703 | 15063 | Headers |

## -examples

## -see-also
[PushNotificationTrigger](../windows.applicationmodel.background/pushnotificationtrigger.md), [Raw notifications sample](http://code.msdn.microsoft.com/windowsapps/Raw-notifications-sample-3bc28c5d), [Raw notification overview](https://docs.microsoft.com/windows/uwp/controls-and-patterns/tiles-and-notifications-raw-notification-overview), [Guidelines and checklist for raw notifications](https://docs.microsoft.com/windows/uwp/controls-and-patterns/tiles-and-notifications-raw-notification-overview), [Quickstart: Creating and registering a raw notification background task](https://docs.microsoft.com/previous-versions/windows/apps/jj676800(v=win.10)), [Quickstart: Intercepting push notifications for running apps](https://docs.microsoft.com/previous-versions/windows/apps/jj709908(v=win.10))
