## Sample WSI DICOM image

DICOM WG26 is standardising a format for whole slide imaging, see:

http://dicom.nema.org/Dicom/DICOMWSI/

This is a small, downsampled test image.

Downloaded from:

ftp://medical.nema.org/medical/Dicom/DataSets/WG26/WG26Demo2020_PV/Robert%5EHuron%20[2581674]/20180904%20210000%20[100%2000%200002%20-%20Skin%20excision]/Series%20382183763%20[SM]/

### `-.184.dcm` 

The original high-res image, with 3358 frames. It's over 800MB so it's not
included here, but you can download it from the ilnk above.

### `-.189.dcm` 

A low-res derived image downsampled to only 228 frames.

### `description.txt` 

A TSV with the filenames and image types.

### `dump.txt`

The structure of the file, created with:

```
$ dcmdump 1.2.276.0.7230010.3.1.4.3376381013.14472.1601002191.189.dcm > dump.txt
```

## Images from

All images from WG26, the group putting the WSI DICOM standard together, see:

ftp://medical.nema.org/medical/Dicom/DataSets/WG26






