# FME Training Content

This repository contains Safe Software's training content, including archived course manuals (2016-2020) and content for the FME Academy online learning platform.

## FME Academy Content

Current Academy content is available on the `main` branch. Past year's Academy content will be archived in `fme-academy-YEAR` branches. The Academy content is stored as required by our platform, Salesforce myTrailhead. The directory structure contains:

- `badges`: PNG and SVG versions of the FME Academy badges and trail icons
- `modules`: each folder is a separate module (each associated with a badge). These chunks of content take 30 minutes to 2 hours to complete. They roughly correspond to a chapter or major chapter section in the archived training manuals. Module folders contain:
  - Unit folders: each is named after their unit. A unit is 5-20 minutes of content covering a single skill. Some have Exercise sections. All have a Quiz. Unit folders contain:
    - `images`: a folder containing unit images
    - `content.html`: the module text and images
    - `evaluation.json`: a JSON format quiz
    - `toc.html`: an HTML snippet containing links to section headings
  - `labels\labels.yml`: a YAML file containing module metadata
  - `badge.png`: the module badge
  - `module.json`: a file describing the module structure including filters, unit order, and time estimates
- `trails`: each folder is a separate trail. Trails are learning paths that link together two or more modules. Modules can belong to more than one trail. A trail is roughly equivalent to an entire manual or several chapters in the archived training manuals. Each trail folder contains:
  - `labels\labels.yml`: a YAML file containing trail metadata
  - `icon.png`: the trail icon
  - `trail.json`: a file describing the trail structure, including filters and module order

## Mapping Between Archived Manuals and Academy

The FME Academy will eventually provide training modules on most of the skills covered by the now-archived  FME training manuals. This table indicates which new modules/trails cover what content from the manuals.

Note: the FME Academy content was updated and often edited when it was transferred to the Academy. This table represents a mapping of FME skills, not an exact match in content.

| Training Manual                                                                               | Chapter/Section                                                                                                                                                                    | FME Academy Trail                                                                                                                 | FME Academy Module                                                                                                                                                                                          |
| --------------------------------------------------------------------------------------------- | ---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | --------------------------------------------------------------------------------------------------------------------------------- | ----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| N/A                                                                                           | N/A                                                                                                                                                                                | N/A                                                                                                                               | [Welcome to the FME Academy](https://safe.my.trailhead.com/content/safe/modules/welcome-to-the-fme-academy)                                                                                                 |
| [Introduction to FME Desktop](https://s3.amazonaws.com/gitbook/Desktop-Intro-2020/index.html) | [Getting Started > What Is FME?](https://s3.amazonaws.com/gitbook/Desktop-Intro-2020/1.getting-started/1.02.what-is-fme.html)                                                      | [Integrate Data with the FME Platform](https://safe.my.trailhead.com/en/content/safe/trails/integrate-data-with-the-fme-platform) | [Why Data Integration?](https://safe.my.trailhead.com/en/content/safe/modules/why-data-integration?trail_id=integrate-data-with-the-fme-platform)                                                           |
| [Introduction to FME Desktop](https://s3.amazonaws.com/gitbook/Desktop-Intro-2020/index.html) | [Translations](https://s3.amazonaws.com/gitbook/Desktop-Intro-2020/2.translations/2.01.fme-translations.html)                                                                      | [Integrate Data with the FME Platform](https://safe.my.trailhead.com/en/content/safe/trails/integrate-data-with-the-fme-platform) | [Connect To Data](https://safe.my.trailhead.com/en/content/safe/modules/connect-to-data?trail_id=integrate-data-with-the-fme-platform)                                                                      |
| [Introduction to FME Desktop](https://s3.amazonaws.com/gitbook/Desktop-Intro-2020/index.html) | [Transformations](https://s3.amazonaws.com/gitbook/Desktop-Intro-2020/3.transformations/3.01.fme-transformations.html)                                                             | [Integrate Data with the FME Platform](https://safe.my.trailhead.com/en/content/safe/trails/integrate-data-with-the-fme-platform) | [Transform Data](https://safe.my.trailhead.com/en/content/safe/modules/transform-data?trail_id=integrate-data-with-the-fme-platform)                                                                        |
| [FME Desktop Basic](https://s3.amazonaws.com/gitbook/Desktop-Basic-2019/index.html)           | [Practical Transformer Use > Locating Transformers](https://s3.amazonaws.com/gitbook/Desktop-Basic-2019/DesktopBasic4Transformers/4.01.LocatingTransformers.html)                  | [Integrate Data with the FME Platform](https://safe.my.trailhead.com/en/content/safe/trails/integrate-data-with-the-fme-platform) | [Transform Data](https://safe.my.trailhead.com/en/content/safe/modules/transform-data?trail_id=integrate-data-with-the-fme-platform)                                                                        |
| [FME Desktop Basic](https://s3.amazonaws.com/gitbook/Desktop-Basic-2019/index.html)           | [Data Translation Basics > What Is FME?](https://s3.amazonaws.com/gitbook/Desktop-Basic-2019/DesktopBasic1Basics/1.01.WhatIsFME.html)                                              | [Integrate Data with the FME Platform](https://safe.my.trailhead.com/en/content/safe/trails/integrate-data-with-the-fme-platform) | [Why Data Integration?](https://safe.my.trailhead.com/en/content/safe/modules/why-data-integration?trail_id=integrate-data-with-the-fme-platform)                                                           |
| [FME Server Authoring](https://s3.amazonaws.com/gitbook/Server-Authoring-2020/index.html)     | [Introduction to FME Server](https://s3.amazonaws.com/gitbook/Server-Authoring-2020/ServerAuthoring1Basics/1.00.IntroductionToFMEServer.html)                                      | [Integrate Data with the FME Platform](https://safe.my.trailhead.com/en/content/safe/trails/integrate-data-with-the-fme-platform) | [Automate Workflows](https://safe.my.trailhead.com/en/content/safe/modules/automate-workflows?trail_id=integrate-data-with-the-fme-platform)                                                                |
| [FME Server Authoring](https://s3.amazonaws.com/gitbook/Server-Authoring-2020/index.html)     | [Real-Time with FME Server](https://s3.amazonaws.com/gitbook/Server-Authoring-2020/ServerAuthoring4RealTime/4.00.RealTimeAndFME.html)                                              | [Integrate Data with the FME Platform](https://safe.my.trailhead.com/en/content/safe/trails/integrate-data-with-the-fme-platform) | [Automate Workflows](https://safe.my.trailhead.com/en/content/safe/modules/automate-workflows?trail_id=integrate-data-with-the-fme-platform)                                                                |
| [FME Desktop Basic](https://s3.amazonaws.com/gitbook/Desktop-Basic-2019/index.html)           | [Practical Transformer Use > Managing Attributes](https://s3.amazonaws.com/gitbook/Desktop-Basic-2019/DesktopBasic4Transformers/4.08.ManagingAttributes.html)                      | [Transform Attributes](https://safe.my.trailhead.com/en/content/safe/trails/transform-attributes)                                 | [Create and Modify Attributes](https://safe.my.trailhead.com/content/safe/modules/create-and-modify-attributes?trail_id=transform-attributes)                                                               |
| [FME Desktop Basic](https://s3.amazonaws.com/gitbook/Desktop-Basic-2019/index.html)           | [Data Transformation > Group-By Processing](https://s3.amazonaws.com/gitbook/Desktop-Basic-2019/DesktopBasic2Transformation/2.10.GroupByProcessing.html)                           | [Transform Attributes](https://safe.my.trailhead.com/en/content/safe/trails/transform-attributes)                                 | [Filter Data](https://safe.my.trailhead.com/en/content/safe/modules/filter-data?trail_id=transform-attributes)                                                                                              |
| [FME Desktop Basic](https://s3.amazonaws.com/gitbook/Desktop-Basic-2019/index.html)           | [Practical Transformer Use > Conditional Filtering](https://s3.amazonaws.com/gitbook/Desktop-Basic-2019/DesktopBasic4Transformers/4.15.ConditionalFiltering.html)                  | [Transform Attributes](https://safe.my.trailhead.com/en/content/safe/trails/transform-attributes)                                 | [Filter Data](https://safe.my.trailhead.com/en/content/safe/modules/filter-data?trail_id=transform-attributes)                                                                                              |
| [FME Desktop Basic](https://s3.amazonaws.com/gitbook/Desktop-Basic-2019/index.html)           | [Practical Transformer Use > Data Joins](https://s3.amazonaws.com/gitbook/Desktop-Basic-2019/DesktopBasic4Transformers/4.18.DataJoins.html)                                        | [Transform Attributes](https://safe.my.trailhead.com/en/content/safe/trails/transform-attributes)                                 | [Join Tables](https://safe.my.trailhead.com/en/content/safe/modules/join-tables?trail_id=transform-attributes)                                                                                              |
| [FME Desktop Advanced](https://s3.amazonaws.com/gitbook/Desktop-Advanced-2019/index.html)     | [Advanced Attribute Handling > Conditional Values](https://s3.amazonaws.com/gitbook/Desktop-Advanced-2019/DesktopAdvanced1Attributes/1.04.ConditionalValues.html)                  | [Transform Attributes](https://safe.my.trailhead.com/en/content/safe/trails/transform-attributes)                                 | [Use Conditional Values](https://safe.my.trailhead.com/en/content/safe/modules/use-conditional-values?trail_id=transform-attributes)                                                                        |
| [FME Desktop Basic](https://s3.amazonaws.com/gitbook/Desktop-Basic-2019/index.html)           | [Data Transformation > Coordinate System Transformation](https://s3.amazonaws.com/gitbook/Desktop-Basic-2019/DesktopBasic2Transformation/2.11.CoordinateSystemTransformation.html) | [Integrate Spatial Data](https://safe.my.trailhead.com/en/content/safe/trails/integrate-spatial-data)                             | [Learn Spatial Data Concepts](https://safe.my.trailhead.com/en/content/safe/modules/learn-spatial-data-concepts?trail_id=integrate-spatial-data)                                                            |
| N/A                                                                                           | N/A                                                                                                                                                                                | [Integrate Spatial Data](https://safe.my.trailhead.com/en/content/safe/trails/integrate-spatial-data)                             | [Turn Coordinates into Geometry](https://safe.my.trailhead.com/en/content/safe/modules/turn-coordinates-into-geometry?trail_id=integrate-spatial-data)                                                      |
| [FME Desktop Advanced](https://s3.amazonaws.com/gitbook/Desktop-Advanced-2019/index.html)     | [Exercise: Flood Risk Assessment](https://s3.amazonaws.com/gitbook/Desktop-Advanced-2019/DesktopAdvanced1Attributes/1.Exercise2.html)                                              | [Integrate Spatial Data](https://safe.my.trailhead.com/en/content/safe/trails/integrate-spatial-data)                             | [Analyze Spatial Data](https://safe.my.trailhead.com/en/content/safe/modules/analyze-spatial-data?trail_id=integrate-spatial-data)                                                                          |
| [Introduction to FME Desktop](https://s3.amazonaws.com/gitbook/Desktop-Intro-2020/index.html) | [Workflows > Best Practice](https://s3.amazonaws.com/gitbook/Desktop-Intro-2020/4.workflows/4.05.best-practice.html)                                                               | [Use Data Integration Best Practices](https://safe.my.trailhead.com/en/content/safe/trails/use-data-integration-best-practices)   | [Document Your Workspace](https://safe.my.trailhead.com/content/safe/modules/document-your-workspace)                                                                                                       |
| [FME Desktop Basic](https://s3.amazonaws.com/gitbook/Desktop-Basic-2019/index.html)           | [Best Practice > Style](https://s3.amazonaws.com/gitbook/Desktop-Basic-2019/DesktopBasic5BestPractice/5.10.Style.html)                                                             | [Use Data Integration Best Practices](https://safe.my.trailhead.com/en/content/safe/trails/use-data-integration-best-practices)   | [Document Your Workspace](https://safe.my.trailhead.com/content/safe/modules/document-your-workspace)                                                                                                       |
| [FME Desktop Basic](https://s3.amazonaws.com/gitbook/Desktop-Basic-2019/index.html)           | [Best Practice > Debugging](https://s3.amazonaws.com/gitbook/Desktop-Basic-2019/DesktopBasic5BestPractice/5.01.Debugging.html)                                                     | [Use Data Integration Best Practices](https://safe.my.trailhead.com/en/content/safe/trails/use-data-integration-best-practices)   | [Debug Workspaces](https://safe.my.trailhead.com/en/content/safe/modules/debug-workspaces?trail_id=use-data-integration-best-practices)                                                                     |
| [Introduction to FME Desktop](https://s3.amazonaws.com/gitbook/Desktop-Intro-2020/index.html) | [Workflows](https://s3.amazonaws.com/gitbook/Desktop-Intro-2020/4.workflows/4.01.fme-workflows.html)                                                                               | [Use Data Integration Best Practices](https://safe.my.trailhead.com/en/content/safe/trails/use-data-integration-best-practices)   | [Design Workspaces for Advanced Reading and Writing](https://safe.my.trailhead.com/en/content/safe/modules/design-workspaces-for-advanced-reading-and-writing?trail_id=use-data-integration-best-practices) |
| [FME Desktop Basic](https://s3.amazonaws.com/gitbook/Desktop-Basic-2019/index.html)           | [Workspace Design](https://s3.amazonaws.com/gitbook/Desktop-Basic-2019/DesktopBasic3WorkspaceDesign/3.00.WorkspaceDesign.html)                                                     | [Use Data Integration Best Practices](https://safe.my.trailhead.com/en/content/safe/trails/use-data-integration-best-practices)   | [Design Workspaces for Advanced Reading and Writing](https://safe.my.trailhead.com/en/content/safe/modules/design-workspaces-for-advanced-reading-and-writing?trail_id=use-data-integration-best-practices) |
| [FME Desktop Basic](https://s3.amazonaws.com/gitbook/Desktop-Basic-2019/index.html)           | [Best Practice > Methodology](https://s3.amazonaws.com/gitbook/Desktop-Basic-2019/DesktopBasic5BestPractice/5.07.Methodology.html)                                                 | [Use Data Integration Best Practices](https://safe.my.trailhead.com/en/content/safe/trails/use-data-integration-best-practices)   | [Design For Performance](https://safe.my.trailhead.com/en/content/safe/modules/design-for-performance?trail_id=use-data-integration-best-practices)                                                         |
| [FME Desktop Advanced](https://s3.amazonaws.com/gitbook/Desktop-Advanced-2019/index.html)     | [Advanced Workspace Design](https://s3.amazonaws.com/gitbook/Desktop-Advanced-2019/DesktopAdvanced2WorkspaceDesign/2.00.AdvancedWorkspaceDesign.html)                              | [Use Data Integration Best Practices](https://safe.my.trailhead.com/en/content/safe/trails/use-data-integration-best-practices)   | [Optimize Workspace Performance](https://safe.my.trailhead.com/en/content/safe/modules/optimize-workspace-performance?trail_id=use-data-integration-best-practices)                                         |
| [FME Desktop Basic](https://s3.amazonaws.com/gitbook/Desktop-Basic-2019/index.html)           | [Data Translation Basics > Data Inspection](https://s3.amazonaws.com/gitbook/Desktop-Basic-2019/DesktopBasic1Basics/1.08.DataInspection.html)                                      | N/A                                                                                                                               | [View Data](https://safe.my.trailhead.com/content/safe/modules/view-data)                                                                                                                                   |
| N/A                                                                                           | N/A                                                                                                                                                                                | N/A                                                                                                                               | [Digital Plan Submission](https://safe.my.trailhead.com/content/safe/modules/digital-plan-submission)                                                                                                       |

## Reuse

Partners are free to adapt and reuse this content according to the [License](LICENSE.md).

## Data

Training data is provided in the [FMEData repository](https://github.com/safesoftware/FMEData/). The FME Academy content here links to an [S3-hosted version of the data](https://s3.amazonaws.com/FMEData/FMEData2021/index.html) where possible so that users do not have to download the entire FMEData repository to use the content.

## Archived Training Manuals

Other branches contain annual release versions of archived training manuals built using [`gitbook`](https://www.npmjs.com/package/gitbook). All archived manuals are available online at https://s3.amazonaws.com/gitbook/index.html. Substituting `index.html` for `Course-Name.pdf` gives you the PDF, e.g. https://s3.amazonaws.com/gitbook/Desktop-Basic-2019/index.html becomes https://s3.amazonaws.com/gitbook/Desktop-Basic-2019/Desktop-Basic-2019.pdf.

## Issues/Questions

Any issues or questions can be directed to train@safe.com or through opening a GitHub Issue.
