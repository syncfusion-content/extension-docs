---
layout: post
title: Syncfusion template not shown in new project window of Visual Studio
description: The syncfusion templates do not show up in the new project window of visual studio.  how can to get them installed?
platform: extension
control: Syncfusion Extensions
documentation: ug
---

# Syncfusion template not shown in new project window of Visual Studio

Perform the given steps to ensure whether the Syncfusion ASP.NET MVC Extension build has been installed in the machine or not.

1. Navigate to the following either one of the location:

   **Before 17.1.0.32-beta version**

   _{Syncfusion installed location}\Utilities\Extensions\ASP.NET MVC_

   _Ex: C:\Program Files (x86)\Syncfusion\Essential Studio\15.4.0.17\Utilities\Extensions\ASP.NET MVC._

   Refer the following screenshot for more information.



   ![Syncfusion ASP.NET MVC Extension installed location](The-Syncfusion-templatesd_images/The-Syncfusion-templatesd-img1.png)

   **On or After 17.1.0.32-beta version**

   _{Syncfusion installed location}\Utilities\Extensions_

   _Ex: C:\Program Files (x86)\Syncfusion\Essential Studio\ASP.NET MVC - EJ1\18.1.0.52\Utilities\Extensions._

   Refer the following screenshot for more information.

   ![Syncfusion ASP.NET MVC Extension installed location](The-Syncfusion-templatesd_images/The-Syncfusion-templatesd-img4.png)


2. When the above path exists, it means that the ASP.NET MVC Extension build has already been installed in the machine. So now you can install the following Syncfusion
   Extensions manually:
   * Syncfusion Project Templates
   * Syncfusion Visual Studio Extensions

   ## To Install Syncfusion Project Templates: 

   **Before 17.1.0.32-beta version**

   Navigate to the following location and run the “Syncfusion.MVC.VSPackage.Web.vsix” extension.

   _{Syncfusion Build installed location}\Utilities\Extensions\ASP.NET MVC\Project Templates\Web\{Visual Studio Version}_

   Refer the following screenshot.

   _Ex: C:\Program Files (x86)\Syncfusion\Essential Studio\15.4.0.17\Utilities\Extensions\ASP.NET MVC\Project Templates\Web\VS2017_


   ![Syncfusion ASP.NET MVC Project Template VSIX file location](The-Syncfusion-templatesd_images/The-Syncfusion-templatesd-img2.png)

   **On or After 17.1.0.32-beta version**

   Navigate to the following location and run the “Syncfusion Essential JS1 AspNet MVC VSExtensions.vsix” extension.

   _{Syncfusion Build installed location}\Utilities\Extensions_

   Refer the following screenshot.

   _Ex: C:\Program Files (x86)\Syncfusion\Essential Studio\ASP.NET MVC - EJ1\18.1.0.52\Utilities\Extensions_


   ![Syncfusion ASP.NET MVC Project Template VSIX file location](The-Syncfusion-templatesd_images/The-Syncfusion-templatesd-img4.png)

   ## To Install Syncfusion Visual Studio Extension:

   **Before 17.1.0.32-beta version**

   Navigate to the following Location and run the “Syncfusion Web Conversion and Migration.vsix” extension. 

   _{Syncfusion Build installed location}\Utilities\Extensions\Project Conversion\{Visual Studio Version}_
   Refer the following screenshot.

   _Ex: C:\Program Files (x86)\Syncfusion\Essential Studio\15.4.0.17\Utilities\Extensions\Project Conversion\VS2017_


   ![Syncfusion Web Conversion and Migration VSIX file location](The-Syncfusion-templatesd_images/The-Syncfusion-templatesd-img3.png)

   **On or After 17.1.0.32-beta version**

   Syncfusion Web Conversion and Migration.vsix extension has been added as a dependency VSIX package to the Syncfusion Essential JS1 AspNet MVC VSExtensions.vsix extension from the **v17.1.0.32- beta** and the Syncfusion Web Conversion and Migration.vsix extension will be installed along with the Syncfusion Essential JS1 AspNet MVC VSExtensions.vsix extension.

3. If the respective version of Syncfusion MVC Extension is not installed in the machine, download the Extension setup from the following link.        [http://www.syncfusion.com/downloads/extension/](http://www.syncfusion.com/downloads/extension/)
