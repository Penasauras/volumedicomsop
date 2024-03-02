# Volume DICOM SOP

This operator allow to open DICOM data in Houdini and operate them as volumes.

<img width="350" alt="image" src="https://github.com/mishazawa/volumedicomsop/assets/7611372/ba47fdcf-a93d-4765-b341-e96cff77d48c">

## Instalation

Copy the file, 'VolumeDicom.json', into your houdini packages directory.

 - Example: "C:/Houdini/houdini20.0/packages"

Open the .json file and change the VOLUMEDICOM path to match the download location of this repository.

 - Example: "VOLUMEDICOM": "C:/Houdini/Repositories/volumedicomsop"

## Attributes

It generate volume `@density` with normalized values in range 0-1. Original min/max values stored in detail attributes.  

## Functionality

- open file or directory (currently it load in memory)
- remap density scalar
- remap density vector `@Cd`
- band `@density` filter 

<img width="411" alt="image" src="https://github.com/mishazawa/volumedicomsop/assets/7611372/af733de2-0893-45f2-b035-580f249395ea">
