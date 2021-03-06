---
title: Úprava nebo nastavení ochrany aplikací pro zařízení s Windows 10
f1.keywords:
- NOCSH
ms.author: sirkkuw
author: Sirkkuw
manager: scotv
audience: Admin
ms.topic: article
f1_keywords:
- Win10AppPolicy
- O365E_Win10AppPolicy
- BCS365_Win10AppPolicy
ms.service: o365-administration
localization_priority: Normal
ms.collection:
- M365-subscription-management
- M365-identity-device-management
ms.custom:
- Core_O365Admin_Migration
- MiniMaven
- MSB365
- OKR_SMB_M365
- seo-marvel-mar
- AdminSurgePortfolio
search.appverid:
- BCS160
- MET150
- MOE150
ms.assetid: 02e74022-44af-414b-9d74-0ebf5c2197f0
description: Naučte se vytvářet nebo upravovat zásady správy aplikací a chránit pracovní soubory na osobních zařízeních s Windows 10.
ms.openlocfilehash: f85a59649e43c141b62091337b842a490d411833
ms.sourcegitcommit: abf63669daf12993ad3353e4b578f41c8910b20f
ms.translationtype: MT
ms.contentlocale: cs-CZ
ms.lasthandoff: 08/27/2020
ms.locfileid: "47289193"
---
# <a name="set-or-edit-application-protection-settings-for-windows-10-devices"></a>Nastavení nebo úprava nastavení ochrany aplikací pro zařízení s Windows 10

Tento článek se týká Microsoft 365 Business Premium.

## <a name="edit-an-app-management-policy-for-windows-10"></a>Úprava zásad správy aplikací pro Windows 10

1. Přejděte do centra pro správu <a href="https://go.microsoft.com/fwlink/p/?linkid=837890" target="_blank">https://admin.microsoft.com</a> .     
2. Na levém navigačním panelu zvolte zásady **zařízení** \> **Policies** .
1. Zvolte existující zásadu aplikací pro Windows a pak **Úpravy**.
1. Zvolte **Upravit** vedle nastavení, které chcete změnit, a pak ho **uložte**.

## <a name="create-an-app-management-policy-for-windows-10"></a>Vytvoření zásady správy aplikací pro Windows 10

Pokud mají uživatelé osobní zařízení s Windows 10, na kterých dělají pracovní úkoly, můžete chránit vaše data i na těchto zařízeních.
  
1. Přejděte do centra pro správu <a href="https://go.microsoft.com/fwlink/p/?linkid=837890" target="_blank">https://admin.microsoft.com</a> . 
2. Na levém navigačním panelu zvolte zásady **zařízení** \> **Policies** \> **Add**.
3. V podokně **Přidat zásadu** zadejte název, který je jedinečný. 
4. V části **Typ zásady** zvolte **Správa aplikací pro Windows 10**.
5. V části **typ zařízení**zvolte **osobní** nebo **vlastně vlastněno společností**.
6. Možnost **Šifrovat pracovní soubory** je zapnutá automaticky. 
7. Pokud nechcete, aby uživatelé ukládali pracovní soubory na své počítače, **zapněte** možnost **Brání uživatelům v kopírování dat společnosti do osobních souborů a vynucuje, aby ukládali pracovní soubory na OneDrive pro firmy**. 
9. Rozbalte položku **obnovit data na zařízeních s Windows**. Doporučujeme to **zapnout.**
    Než budete moct přejít do umístění certifikátu agenta obnovování dat, musíte nějaký nejprve vytvořit. Pokyny najdete v článku [Vytvoření a ověření certifikátu agenta obnovení dat (EFS) (Encrypting File System)](https://go.microsoft.com/fwlink/p/?linkid=853700).
    
    Ve výchozím nastavení jsou pracovní soubory šifrované pomocí tajného klíče, který je uložený v zařízení a přidružený k profilu uživatele. Soubor může otevřít a dešifrovat jenom uživatel. Pokud ovšem dojde ke ztrátě zařízení nebo odebrání uživatele, soubor může zůstat zašifrovaný. Správce může k dešifrování souboru použít certifikát agenta obnovení dat (DRA).
    
    ![Browse to Data Recovery Agent certificate.](../media/7d7d664f-b72f-4293-a3e7-d0fa7371366c.png)
  
10. Rozšiřte **Další umístění v síti a cloudu** , pokud chcete přidat další domény nebo umístění SharePointu Online, abyste měli jistotu, že jsou chráněné soubory ve všech uvedených aplikacích. Pokud potřebujete zadat do jednoho z polí více než jednu položku, oddělte tyto položky středníkem (;).
    
    ![Expand Protect additional network and cloud locations, and enter domains or SharePoint Online sites you own.](../media/7afaa0c7-ba53-456d-8c61-312c45e09625.png)
  
11. V dalším kroku rozhodněte, **pro koho tato nastavení platí**. Pokud nechcete použít výchozí skupinu zabezpečení **Všichni uživatelé**, zvolte **Změnit** a vyberte skupinu zabezpečení, pro kterou se tato nastavení použijí \> **Vybrat**.
12. Volbou **Přidat** nakonec zásadu uložíte a přiřadíte ji zařízením. 
