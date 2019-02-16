---
title: ms-date-too-late
description: Erklärung und Lösung zu Problemen beim Erstellen von Dokumentationsartikeln – ms-date-too-late
author: meganbradley
ms.author: mbradley
ms.topic: error-reference
ms.date: 1/15/2019
ms.prod: non-product-specific
ms.openlocfilehash: 863b13e55c2aaa2057920e3bd77ec75ab5945277
ms.sourcegitcommit: 203ca15fda2d217f082c74ec648c1f1db323f9f1
ms.translationtype: HT
ms.contentlocale: de-DE
ms.lasthandoff: 02/04/2019
ms.locfileid: "55713106"
---
# <a name="ms-date-too-late"></a><span data-ttu-id="c5d43-103">ms-date-too-late</span><span class="sxs-lookup"><span data-stu-id="c5d43-103">ms-date-too-late</span></span>

<span data-ttu-id="c5d43-104">**Bald verfügbar!**</span><span class="sxs-lookup"><span data-stu-id="c5d43-104">**Coming soon!**</span></span>

## <a name="warning"></a><span data-ttu-id="c5d43-105">Warnung</span><span class="sxs-lookup"><span data-stu-id="c5d43-105">Warning</span></span>

`Invalid value for ms.date. The freshness date can't be more than five days in the future.`

<span data-ttu-id="c5d43-106">Mit dem `ms.date`-Attribut wird „Frische“ signalisiert – d.h., wann der Artikel zuletzt auf Relevanz, Genauigkeit, richtige Screenshots und funktionierende Links überprüft wurde.</span><span class="sxs-lookup"><span data-stu-id="c5d43-106">The `ms.date` attribute is used to indicate "freshness" - that is, when the article was last reviewed for relevance, accuracy, correct screen shots, and working links.</span></span> <span data-ttu-id="c5d43-107">Darum kann es nicht in der Zukunft liegen!</span><span class="sxs-lookup"><span data-stu-id="c5d43-107">Therefore, it can't be in the future!</span></span> <span data-ttu-id="c5d43-108">Fünf Tage sind für die Herausgabezeit zulässig, wenn der Inhalt etwa zur Qualitätssicherung in Vorbereitung auf ein wichtiges Ereignis eingefroren wird.</span><span class="sxs-lookup"><span data-stu-id="c5d43-108">Five days are allowed to account for release time, such as when content is frozen for QA in preparation for a major event.</span></span>

## <a name="resolution"></a><span data-ttu-id="c5d43-109">Lösung</span><span class="sxs-lookup"><span data-stu-id="c5d43-109">Resolution</span></span>

<span data-ttu-id="c5d43-110">Geben Sie ein `ms.date`, das vom aktuellen Datum nicht mehr als fünf Tage abweicht, im Format MM/TT/JJJJ an.</span><span class="sxs-lookup"><span data-stu-id="c5d43-110">Specify an `ms.date` no more than five days from today, in format MM/DD/YYYY.</span></span>

<!--make sure to add this file to your includes folder and verify the path-->
[!INCLUDE [validation-reference-help](includes/validation-reference-help.md)]