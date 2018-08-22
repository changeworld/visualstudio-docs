---
title: "AutoRecover, Environment, Options Dialog Box | Microsoft Docs"
ms.custom: ""
ms.date: "2018-06-30"
ms.prod: "visual-studio-dev14"
ms.reviewer: ""
ms.suite: ""
ms.technology: 
  - "vs-ide-general"
ms.tgt_pltfrm: ""
ms.topic: "article"
f1_keywords: 
  - "VS.ToolsOptionsPag.Environment.AutoRecover"
  - "VS.DialogAutoRestore"
  - "VS.ToolsOptionsPages.Environment.AutoRecover"
  - "VS.ToolsOptionsPages.Environment.Auto_Save_and_Restore"
helpviewer_keywords: 
  - "files, recovering"
  - "AutoRecover page"
  - "saving files, automatically"
  - "files, saving automatically"
ms.assetid: 397e5e44-4bbe-4289-94d1-642b466c9111
caps.latest.revision: 18
author: gewarren
ms.author: gewarren
manager: "ghogen"
---
# AutoRecover, Environment, Options Dialog Box
[!INCLUDE[vs2017banner](../../includes/vs2017banner.md)]

The latest version of this topic can be found at [AutoRecover, Environment, Options Dialog Box](https://docs.microsoft.com/visualstudio/ide/reference/autorecover-environment-options-dialog-box).  
  
  
Use this page of the Options dialog box to specify whether or not files are automatically backed up. This page also allows you to specify whether or not modified files are restored when the integrated development environment (IDE) shuts down unexpectedly. You can access this dialog box by selecting the **Tools** menu and choosing **Options**, and then selecting the **Environment** folder and choosing the **AutoRecover** page. If this page does not appear in the list, select **Show all setting** in the **Options** dialog box.  
  
> [!NOTE]
>  The dialog boxes and menu commands you see might differ from those described in Help depending on your active settings or edition. To change your settings, choose Import and Export Settings on the Tools menu. For more information, see [Customizing Development Settings in Visual Studio](http://msdn.microsoft.com/en-us/22c4debb-4e31-47a8-8f19-16f328d7dcd3).  
  
 **Save AutoRecover information every \<n> minutes**  
 Use this option to customize how often a file is automatically saved in the editor. For previously saved files, a copy of the file is saved in \\...\My Documents\Visual Studio \<*version*>\Backup Files\\<*projectname*>. If the file is new and has not been manually saved, the file is auto-saved using a randomly generated file name.  
  
 **Keep AutoRecover information for \<n> days**  
 Use this option to specify how long Visual Studio keeps files created for autorecovery.  
  
## See Also  
 [Options Dialog Box](../../ide/reference/options-dialog-box-visual-studio.md)


