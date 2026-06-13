# BIDS_layerfMRI
A project from OHBM BrainHack 2026 <br />
Based on discussions with the community during the OHBM BrainHack (2026), we propose the following structure as “initial prototype” with the minimum requirement for organizing layer-fMRI datasets. Files that required new BIDSfycation are highligted in *italic*.  <br />
Prototype dataset: https://zenodo.org/records/20679524

Dataset_layer-fMRI_example <br />
Dataset_description.json <br />
├── sub-02 <br />
│  ├── sess-02 <br />
│   │   ├── func <br />
│   │   └──  sub-02_sess-04_task-movie_run-01_bold.nii.gz <br />
│   │   ├── anat <br />
│   │   └──  sub-02_sess-01_run-01_T1w.nii.gz <br />
├── derivative <br />
│  ├── anat <br />
│  └──  sub-02_desc-preproc_T1w.nii.gz <br />
│  └──  sub-02_seg-braintissues_dseg.nii.gz <br />
│  └──  braintissues_dseg.tsv <br />
│  └──  sub-02_space-NATIVE_atlas-Glasser.nii.gz <br />
│  └──  atlas-Glasser_description.json <br />
│  └──  *sub-02_seg-depth_method-equivol.nii.gz* <br />
│  └──  *depth_description.json* <br />
│  └──  *sub-02_seg-layer_method-equivol.nii.gz* <br />
│  └──  *layer_dseg.tsv* <br />
│  └──  sub-02_roi-V1_dseg.nii.gz <br />
│  └──  roi_dseg.tsv <br />
│  ├── func <br />
│  └──  sub-02_sess-04_task-movie_run-01_space-NATIVE_desc-prepro_bold.nii.gz <br />
│  └── sub-02_sess-04_task-movie_run-01_space-NATIVE_stat-mean_bold.nii.gz <br />
│  └── sub-02_sess-04_task-movie_run-01_space-NATIVE_stat-tsnr_bold.nii.gz <br />

<img src="logo.jpeg" width="250">
