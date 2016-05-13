# Barcodes in LabVIEW
This sample VI show, how to use the IC Barcode libary for barcode reading in LabVIEW

## Prerequisites:
- LabVIEW 2013

- IC Imaging Control 3.4 .NET component from
http://www.theimagingsource.com/support/downloads-for-windows/software-development-kits-sdks/icimagingcontrol/

- IC Barcode SDK from
http://www.theimagingsource.com/support/downloads-for-windows/programming-samples/icbarcode/

You may need to edit the reference to the IC Barcode DLL. This is shown in the VI.

![alt tag](https://raw.githubusercontent.com/TheImagingSource/Windows-Sample-LabVIEW-IC-Barcode/master/barcode.png)

### Remarks
There may is a memoryleak on the array returned by FindBarcodes. I currently not figured out, how to delete this array after usage.
