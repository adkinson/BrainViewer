# BrainViewer
BrainViewer is a MATLAB application built for viewing brain imaging data in 3D space. The application was originally designed to visualize multiple brain imaging modalities (CT, MRI, brain surface reconstructions) with localization of implanted sEEG electrodes. The software aggregates multiple imaging modalities into one viewing window, and can be used on datasets of individual subjects or aggregate the electrode localization reconstructions of multiple subject onto an averaged brain surface reconstruction. Over time, additional features have been added, including:
* Exporting of STL files of brain surfaces
* Saving snapshot images of the viewing window
* Generate GIFs of 3D navigations around brain
* Import colored brain atlas onto brain surfaces

![alt text][rotateBrain]

Loaded visualizations also have a number of options for adjusting features like color and opacity in the Image Setting. The options available are dependent of the type of image modality.

## Important Notes
1. This software acts as a wrapper for the [iELVis imaging repository](https://github.com/iELVis/iELVis) and requires that repository to operate properly. When BrainViewer is run for the first time, options are available to download the iELVis repository automatically or select the folder containing the repo.
2. Brain Surface Reconstructions are generated using FreeSurfer.
3. This software has also been made to work in conjunction with the [StimulationMapper application](https://github.com/adkinson/StimulationMapper), which can use BrainViewer to generate simple real-time visualizations of which electrodes implanted in the brain detect responsive behavior from stimulation.

For more details on proper utilization and features of this application, please visit the [Wiki](https://github.com/adkinson/BrainViewer/wiki).

[rotateBrain]: https://github.com/adkinson/BrainViewer/tree/main/docs
