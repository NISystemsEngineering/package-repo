# Overview

This is a central shared repository for hosting NI packages and feeds from the NI Systems Engineering organization.

# Currently Hosted Feeds

| Repository                                                   | NI Package Manger Feed URL                                   |
| ------------------------------------------------------------ | ------------------------------------------------------------ |
| [ni-rfmx-signal-creator](https://github.com/NISystemsEngineering/ni-rfmx-signal-creator) | https://raw.githubusercontent.com/NISystemsEngineering/package-repo/master/ni-rfmx-signal-creator/Packages |

# Using Hosted Feeds in NI Package Manger

NI Package Manger (NIPM) requires a direct link to the hosted feed and packages; these steps below allow you to directly access the feed for use in NIPM.

1. From the GitHub web interface, navigate to your subfolder and click on the **Packages** file that is created by NI Package Manager. This is the feed definition file.

2. Select **Raw** button shown in the screenshot below. This should open the file directly in your browser with a URL such as *https://raw.githubusercontent.com/<Repo_Path_to_File>* ![example_raw_button](/_img/example_raw_button.png)

   # 

3. Copy this URL and [add the new feed in NIPM](https://www.ni.com/documentation/en/ni-package-manager/20.0/manual/add-package-to-feed/)

## Installing Packages from the Feed

Once the feed has been added in NIPM, you can install packages from this feed via the **Packages** tab.

1. Ensure that the *Show available packages and feed management tools* checkbox is **checked** in the NIPM settings. If unchecked, the **Packages** tab used below will not be shown.
  
  ![](/_img/example_feed_management.png)

2. Select the **Packages** tab on the far right to show all packages that are available from the currently configured feeds, and search for your package from there.
# Adding New Feed to Repository

1. Create a new folder in the main directory of this repository with the same name as the source code repository (i.e. *my-source-repo*)
2. Add your packages to the directory
3.  [Create a new feed](https://www.ni.com/documentation/en/ni-package-manager/latest/manual/creating-feed/) using NI Package Manager
4. Commit your changes to the repository
