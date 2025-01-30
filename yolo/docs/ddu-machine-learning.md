tensorflow# Hele processen

## Trin 1 annotering
- tag billeder af terninger
- upload til makesense.ai
- annoter med makesense.ai
- download annotations
- konverter til YOLO format (mappestruktur)

## Trin 2 objektdetektering og cropping
- træn objektdetektering med yolo - output: model: best.pt
- test model på billeder
- crop billedfiler efter bounding boxes

**Output: model 1**

## Trin 3 træn klassifikation 1-6
- træn model på croppede billeder: output some-model

**Output: model 2**

## Trin 4 Genkend terning
Tensorflow script?

- læg terning under kamera
- med model 1 genkend objekt
- med model 2 genkend terning 

