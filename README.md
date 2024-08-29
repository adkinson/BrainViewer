# BrainViewer
BrainViewer is a MATLAB application built for viewing brain imaging data in 3D space. The application was originally designed to visualize multiple brain imaging modalities (CT, MRI, brain surface reconstructions) with localization of implanted sEEG electrodes. The software aggregates multiple imaging modalities into one viewing window, and can be used on datasets of individual subjects or aggregate the electrode localization reconstructions of multiple subject onto an averaged brain surface reconstruction. Over time, additional features have been added, including:
* Exporting of STL files of brain surfaces
* Saving snapshot images of the viewing window
* Generate GIFs of 3D navigations around brain
* Import colored brain atlas onto brain surfaces

Loaded visualizations also have a number of options for adjusting features like color and opacity in the Image Settings. The options available are dependent of the type of image modality.

>[!Note]
>This software requires the [iELVis imaging repository](https://github.com/iELVis/iELVis) to operate properly. When BrainViewer is run for the first time, options are available to download the iELVis repository automatically or select the folder containing the repo.

For more details on proper utilization and features of this application, please visit the [Wiki](https://github.com/adkinson/BrainViewer/wiki).
