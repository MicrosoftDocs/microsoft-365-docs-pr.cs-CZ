---
title: Stavy zařízení
ms.author: sirkkuw
author: Sirkkuw
manager: scotv
ms.audience: Admin
ms.topic: overview
ms.service: o365-administration
localization_priority: Normal
ms.collection: Adm_O365
ms.custom:
- Adm_O365
- Core_O365Admin_Migration
- MiniMaven
- MSB365
search.appverid:
- BCS160
- MET150
- MOE150
ms.assetid: c3ac23c5-d4b4-4b1b-b7ce-ea759521bf8c
description: Informace o stavech zařízení v Microsoft 365 Business.
ms.openlocfilehash: bd6f1ad7f7671d9616fd14d477dfcfb164ff6bd0
ms.sourcegitcommit: eb1a77e4cc4e8f564a1c78d2ef53d7245fe4517a
ms.translationtype: MT
ms.contentlocale: cs-CZ
ms.lasthandoff: 11/28/2018
ms.locfileid: "26982901"
---
# <a name="device-states"></a><span data-ttu-id="c684a-103">Stavy zařízení</span><span class="sxs-lookup"><span data-stu-id="c684a-103">Device states</span></span>

## <a name="device-states"></a><span data-ttu-id="c684a-104">Stavy zařízení</span><span class="sxs-lookup"><span data-stu-id="c684a-104">Device states</span></span>

<span data-ttu-id="c684a-105">Zařízení v seznamu **Akce zařízení** (domovská stránka správce \> **Akce zařízení**) můžou mít následující stavy.</span><span class="sxs-lookup"><span data-stu-id="c684a-105">Devices in the **Device actions** list (Admin home \> **Device actions**) can have the following states.</span></span>
  
![In the Device actions list, you can see the Devices states.](media/a621c47e-45d9-4e1a-beb9-c03254d40c1d.png)
  
|<span data-ttu-id="c684a-107">**Stav**</span><span class="sxs-lookup"><span data-stu-id="c684a-107">**Status**</span></span>|<span data-ttu-id="c684a-108">**Popis**</span><span class="sxs-lookup"><span data-stu-id="c684a-108">**Description**</span></span>|
|:-----|:-----|
|<span data-ttu-id="c684a-109">Spravováno službami Intune</span><span class="sxs-lookup"><span data-stu-id="c684a-109">Managed by Intune</span></span>  <br/> |<span data-ttu-id="c684a-110">Zařízení je spravované v Microsoft 365 Business.</span><span class="sxs-lookup"><span data-stu-id="c684a-110">Managed by Microsoft 365 Business.</span></span>  <br/> |
|<span data-ttu-id="c684a-111">Čeká se na vyřízení</span><span class="sxs-lookup"><span data-stu-id="c684a-111">Retire pending</span></span>  <br/> |<span data-ttu-id="c684a-112">Microsoft 365 Business se připravuje odebrat ze zařízení data společnosti.</span><span class="sxs-lookup"><span data-stu-id="c684a-112">Microsoft 365 Business is getting ready to remove company data from the device.</span></span>  <br/> |
|<span data-ttu-id="c684a-113">Probíhá vyřazování</span><span class="sxs-lookup"><span data-stu-id="c684a-113">Retire in progress</span></span>  <br/> |<span data-ttu-id="c684a-114">Microsoft 365 Business právě odebírá ze zařízení data společnosti.</span><span class="sxs-lookup"><span data-stu-id="c684a-114">Microsoft 365 Business is currently removing company data from the device.</span></span>  <br/> |
|<span data-ttu-id="c684a-115">Vyřazení selhalo</span><span class="sxs-lookup"><span data-stu-id="c684a-115">Retire failed</span></span>  <br/> | <span data-ttu-id="c684a-116">Akce spočívající v odebrání dat společnosti se nezdařila.</span><span class="sxs-lookup"><span data-stu-id="c684a-116">Remove company data action failed.</span></span>  <br/> |
|<span data-ttu-id="c684a-117">Vyřazení bylo zrušeno</span><span class="sxs-lookup"><span data-stu-id="c684a-117">Retire cancelled</span></span>  <br/> |<span data-ttu-id="c684a-118">Akce vyřazení byla zrušena.</span><span class="sxs-lookup"><span data-stu-id="c684a-118">Retire action was cancelled.</span></span>  <br/> |
|<span data-ttu-id="c684a-119">Čeká se na vymazání</span><span class="sxs-lookup"><span data-stu-id="c684a-119">Wipe pending</span></span>  <br/> |<span data-ttu-id="c684a-120">Čeká se na spuštění obnovení továrního nastavení.</span><span class="sxs-lookup"><span data-stu-id="c684a-120">Waiting for factory reset to start.</span></span>  <br/> |
|<span data-ttu-id="c684a-121">Probíhá mazání</span><span class="sxs-lookup"><span data-stu-id="c684a-121">Wipe in progress</span></span>  <br/> |<span data-ttu-id="c684a-122">Byl vydán příkaz k obnovení továrního nastavení.</span><span class="sxs-lookup"><span data-stu-id="c684a-122">Factory reset has been issued.</span></span>  <br/> |
|<span data-ttu-id="c684a-123">Vymazání selhalo</span><span class="sxs-lookup"><span data-stu-id="c684a-123">Wipe failed</span></span>  <br/> |<span data-ttu-id="c684a-124">Obnovení továrního nastavení nejde provést.</span><span class="sxs-lookup"><span data-stu-id="c684a-124">Couldn't perform factory reset.</span></span>  <br/> |
|<span data-ttu-id="c684a-125">Vymazání bylo zrušeno</span><span class="sxs-lookup"><span data-stu-id="c684a-125">Wipe cancelled</span></span>  <br/> |<span data-ttu-id="c684a-126">Vymazání do čistého továrního nastavení bylo zrušeno.</span><span class="sxs-lookup"><span data-stu-id="c684a-126">Factory wipe was cancelled.</span></span>  <br/> |
|<span data-ttu-id="c684a-127">Není v pořádku</span><span class="sxs-lookup"><span data-stu-id="c684a-127">Unhealthy</span></span>  <br/> |<span data-ttu-id="c684a-128">Znamená, že se čeká na provedení akce (nebo akce probíhá), ale zařízení se 30 a více dní nezaregistrovalo.</span><span class="sxs-lookup"><span data-stu-id="c684a-128">This means that an action is pending (or in progress) but the device has not checked in for 30+ days.</span></span>  <br/> |
|<span data-ttu-id="c684a-129">Čeká se na odstranění</span><span class="sxs-lookup"><span data-stu-id="c684a-129">Delete pending</span></span>  <br/> |<span data-ttu-id="c684a-130">Čeká se na provedení akce odstranění.</span><span class="sxs-lookup"><span data-stu-id="c684a-130">Delete action is pending.</span></span>  <br/> |
|<span data-ttu-id="c684a-131">Zjištěné</span><span class="sxs-lookup"><span data-stu-id="c684a-131">Discovered</span></span>  <br/> |<span data-ttu-id="c684a-132">Služba Microsoft 365 Business zařízení rozpoznala</span><span class="sxs-lookup"><span data-stu-id="c684a-132">Microsoft 365 Business has detected the device.</span></span>  <br/> |
   