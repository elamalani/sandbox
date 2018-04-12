---
title: SDKs and Tools for Game Developers on Azure
description: SDKs and Tools for Game Developers on Azure
author: BrianPeek
keywords: unity, azure,
ms.topic: article
ms.date: 02/22/2018
ms.author: brpeek
manager: timheuer
---
# SDKs and Tools for Game Developers on Azure

Game developers use a variety of engines and frameworks to create games.  Each of these has its own method to use plugins, SDKs and external tools.  Here are some instructions for getting started wtih some of the most popular engines available today. Please note that this is not an exhaustive list and will be expanded upon over time.

## [![unity logo](media/logos/unity-small.png) Unity](#tab/unity)

We are providing several experimental SDKs for Unity developers to access various Azure services.  The goal is to provide friendly asset packages (.unitypackage) which contain everything you need to access a particular Azure service, along with a sample scene demonstrating how to use it.  In addition, these packages will use the standard .NET SDK binaries, so the API and documentation will be identical.  Today, we have the following packages:

* [Storage](unity/azure-storage-unity)
* [Mobile Apps](unity/azure-mobile-apps-unity)
* [Event Hubs](unity/azure-event-hubs)

Check out the above pages to learn how to download, install, and use these SDKs with your Unity project.

## [![monogame logo](media/logos/monogame-small.png) MonoGame](#tab/monogame)

Since MonoGame runs on top of the full .NET Framework and uses Xamarin for cross-platform builds, the existing Azure SDK NuGet packages work "out of the box" without any modifications.  For more information on how to use these SDKs with Azure, please see the following:

* [Using Azure SDKs with MonoGame](monogame/azure-monogame)
* [Samples](https://aka.ms/azsamples-monogame)

## [![unreal logo](media/logos/unreal-small.png) Unreal Engine](#tab/unreal)

Unreal Engine can use a combination of Blueprints and C++.  To use Azure with C++ code in your Unreal Engine game, take a look at the following:

* Using Unreal Engine with the Azure Storage SDK

## [![c++ logo](media/logos/cpp-small.png) C++](#tab/cpp)

Many game developers choose a native C++ framework, such as Cocos2d-x, SDK, or DirectX.  To use Azure services via C++ there are several options.  For services which have a native SDK, such as Storage, you may be able to use these directly.  For those that do not, many Azure services include a REST endpoint which can be hit from your C++ game by using a library like Casablanca.  For more information, please see the following:

* [Storage Client Library for C++](https://github.com/Azure/azure-storage-cpp)
* [C++ REST SDK](https://github.com/Microsoft/cpprestsdk)

## [![playfab logo](media/logos/playfab-small.png) PlayFab](#tab/playfab)

PlayFab is a complete backend platform for games.  Check out the PlayFab site for more information on how to sign up, use the service, and integrate with your game.

* [PlayFab](https://playfab.com/)