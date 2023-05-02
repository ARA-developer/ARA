# ARA - Privacy policy
this page explains Permissions needed in ARA application running on Android.

## Permissions
| Permissions | Why it is required |
| :---: | --- |
| `android.permission.INTERNET` and `android.permission.ACCESS_NETWORK_STATE` | To determine if the service is able to connect to the Internet, and inform user of the current state |
| `android.permission.BLUETOOTH_CONNECT` and `android.permission.BLUETOOTH` | Device name is set by using bluetooth name of the device|
| `android.permission.READ_PHONE_STATE` | To detect screen On & Off state. Using this event realtime clipboard update period is setted |
| `android.permission.WRITE_EXTERNAL_STORAGE` and `android.permission.READ_EXTERNAL_STORAGE` | Read & Write file to the device storage when using 'Drop' & 'Clipboard Image Sync' functionality |
| `android.permission.SYSTEM_ALERT_WINDOW` | realtime clipboard synchronization needs popup window for clipboard sync with device |
| `android.permission.ACTION_MANAGE_OVERLAY_PERMISSION` | realtime clipboard synchronization needs popup window for clipboard sync with device |
| `android.permission.KILL_BACKGROUND_PROCESSES` | will be used by Foreground Service management system |
| `android.permission.RECEIVE_BOOT_COMPLETED` | To detect device boot complete and wake Foreground Service up |
| `android.permission.FOREGROUND_SERVICE` | To use Foreground Service |
| `android.permission.REQUEST_IGNORE_BATTERY_OPTIMIZATIONS` | To user Foreground Service |
| `android.permission.POST_NOTIFICATIONS` | To inform user notification |

If you find any security vulnerability that has been inadvertently caused by me, or have any question regarding how the app protectes your privacy, please send me an email or post a discussion on GitHub, and I will surely try to fix it/help you.

## Privacy Policy
check out [pdf](https://github.com/ARA-developer/ARA/blob/main/%E1%84%87%E1%85%A6%E1%84%90%E1%85%A1%20%E1%84%89%E1%85%A5%E1%84%87%E1%85%B5%E1%84%89%E1%85%B3%20%E1%84%80%E1%85%A2%E1%84%8B%E1%85%B5%E1%86%AB%E1%84%8C%E1%85%A5%E1%86%BC%E1%84%87%E1%85%A9%20%E1%84%8E%E1%85%A5%E1%84%85%E1%85%B5%20%E1%84%87%E1%85%A1%E1%86%BC%E1%84%8E%E1%85%B5%E1%86%B7.pdf)

You can contact us on vast.devgroup@gmail.com
