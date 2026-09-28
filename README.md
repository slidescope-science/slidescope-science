# SlideScope

**Desktop digital pathology and microscopy viewer for Windows and macOS.**

SlideScope opens whole slide images from the major slide scanner vendors and research
microscopy files in one window, on your own machine, with no image server.

- Website: https://slidescope.science/
- Digital pathology viewer: https://slidescope.science/digital-pathology-viewer/
- What is digital pathology: https://slidescope.science/what-is-digital-pathology/
- Whole slide image viewer comparison: https://slidescope.science/whole-slide-image-viewer-comparison/
- Release notes: https://slidescope.science/en/release-notes/
- Microsoft Store: https://apps.microsoft.com/detail/xpdlmkv6zm2prt
- bio.tools: https://bio.tools/slidescope
- Wikidata: https://www.wikidata.org/wiki/Q140797497

## Formats

| Source | Formats |
|---|---|
| Aperio / Leica Biosystems | SVS, SVSLIDE |
| Hamamatsu NanoZoomer | NDPI, VMS, VMU |
| 3DHISTECH Pannoramic | MRXS |
| Leica SCN400 / GT450 | SCN |
| Ventana / Roche | BIF |
| Akoya / PerkinElmer / Vectra | QPTIFF |
| Agilent ARGOS | AVS |
| Vendor-neutral | DICOM (including DICOM WSI), pyramidal TIFF, OME-TIFF |
| Research microscopes | Zeiss CZI, Nikon ND2, Leica LIF, Imaris IMS |

Not supported: Philips iSyntax, Olympus VSI. Full matrix:
https://slidescope.science/microscopy-file-compatibility/

## What it does

- Reads the scanner's image pyramid so multi-gigabyte slides open in seconds on a laptop.
- Measures in calibrated micrometres from the pixel size the scanner recorded.
- Keeps annotations attached to the slide; exports regions as GeoJSON (QuPath-compatible,
  see [`examples/annotations.geojson`](examples/annotations.geojson)) and measurements as CSV.
- Compares two slides side by side at matched physical scale.
- Shares an exact field of view (slide, position, zoom, plane) as a link.
- Local Quantification: nuclei, cell, and particle counts computed on your own computer.
- Optional AI Analysis that explains the current frame in plain language.

## Platforms and price

Windows 10 and later; macOS 14 and later (Apple Silicon and Intel).
Free 3-day trial with every feature, then a monthly subscription; cancel anytime.
Pricing: https://slidescope.science/plans/

## Scope

SlideScope is for research, education, and review. It is not a medical device and is not
cleared for primary diagnosis.

## This repository

This repository holds public reference material for SlideScope: the GeoJSON annotation
export example and links to documentation. The application itself is proprietary and is
distributed from https://slidescope.science/.

Support: support@slidescope.science
