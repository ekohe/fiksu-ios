## *v3.6.1* (32-bit: Revision 44544, 2013-10-17; 64-bit: Revision 46544, 2013-11-13)

 * No longer accessing UIPasteboard on iOS 7
 * Better subject for email submission to Fiksu
 * Support for 64-bit added 2013-11-13

## *v3.6* (Revision 44543, 2013-08-27)

 * Updated for iOS 7/Xcode 5
 * Added `[FiksuTrackingManager setAppTrackingEnabled:(BOOL)]` and `[FiksuTrackingManager isAppTrackingEnabled]`

## *v3.5.1* (Revision 44542, 2013-09-04) 

 * Added support for custom events via `[FiksuTrackingManager uploadCustomEvent]`
   * This replaces the call from _FiksuSDK 3.5_ for FMA Engagement events: `[FiksuTrackingManager uploadFMAEngagementEvent]`
 * Added custom events to Debug UI
 * Additional Debug UI cleanup

## *v3.5* (Revision 44541, 2013-07-18)

 * Added FMA Engagement events
 * Added request signing

## *v3.3* (Revision 44539, 2013-04-03)

 * Support for client generated ID by calling `[FiksuTrackingManager setClientID:...]`
 * Debug Mode providing visibility into URL configuration

## *v3.2.2* (Revision 44538, 2013-03-28)

 * All UDID references removed
 * Debug Mode bug fix
 
## *v3.2.1* (Revision 44537, 2013-02-08)

 * Moved SDK storage from `Documents/` to `Library/Application Support/com.fiksu.sdk/` or `Library/Caches/com.fiksu.sdk/`, in that order.

## *v3.2* (Revision 44536, 2012-12-26)

 * Added Facebook app attribution support

## *v3.1.1* (Revision 44535, 2012-11-19)

 * Addressed some issues with Debug mode

## *v3.1* (Revision 44534, 2012-11-19)

 * Added Fiksu Debug Mode for verifying proper SDK integration
 * Changed configuration of SDK from editing code to editing plists
 * Provided SDK as embedded framework for ease of integration

## *v3.0* (Revision 44531, 2012-09-13)

 * Using new AdSupport.framework for advertisingIdentifier

## Revision 44530 (2012-08-28)

 * Removed OpenUDID support
 * Enabled transmission of new iOS identifiers
 * Disabled HTML5 tracking by default
