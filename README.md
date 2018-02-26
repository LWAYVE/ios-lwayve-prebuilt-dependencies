# iOS LWAYVE SDK prebuilt dependencies

The repo contains pre-built dependencies required for LWAYVE iOS SDK https://github.com/LWAYVE/ios-sdk.

The pre-built dependencies supposed to simplify LWAYVE SDK integration process for ones who don't use any dependency manager in their project. 

## How to use pre-built dependencies to integrate LWAYVE SDK

1. Add all frameworks from the [dependencies folder](https://github.com/LWAYVE/ios-lwayve-prebuilt-dependencies/tree/master/dependencies) to your app Embedded Binaries.
2. Follow [Add the ProxSee SDK to Your iOS Project](https://github.com/proxsee/sdk-ios#add-the-proxsee-sdk-to-your-ios-project) section to integrate ProxSee SDK
3. Follow [Section 2: Implementing the LWAYVE and ProxSee SDKs in an iOS Project](https://github.com/LWAYVE/ios-sdk#section-2-implementing-the-lwayve-and-proxsee-sdks-in-an-ios-project) starting from the [Configure Application Background Modes step](https://github.com/LWAYVE/ios-sdk#configure-application-background-modes) to integrate LWAYVE SDK itself.